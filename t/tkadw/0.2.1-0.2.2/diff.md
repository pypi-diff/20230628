# Comparing `tmp/tkadw-0.2.1.tar.gz` & `tmp/tkadw-0.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "tkadw-0.2.1.tar", max compression
+gzip compressed data, was "tkadw-0.2.2.tar", max compression
```

## Comparing `tkadw-0.2.1.tar` & `tkadw-0.2.2.tar`

### file list

```diff
@@ -1,46 +1,49 @@
--rw-r--r--   0        0        0      291 2023-06-24 02:48:13.231068 tkadw-0.2.1/pyproject.toml
--rw-r--r--   0        0        0     6554 2023-06-24 02:48:07.830846 tkadw-0.2.1/README.md
--rw-r--r--   0        0        0      142 2023-06-24 02:43:29.598698 tkadw-0.2.1/tkadw/__init__.py
--rw-r--r--   0        0        0     1162 2023-06-24 02:46:00.468947 tkadw-0.2.1/tkadw/__main__.py
--rw-r--r--   0        0        0      142 2023-06-24 02:43:29.551423 tkadw-0.2.1/tkadw/advanced/__init__.py
--rw-r--r--   0        0        0      383 2023-06-24 02:43:30.014259 tkadw-0.2.1/tkadw/advanced/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0     2906 2023-06-24 02:46:00.929979 tkadw-0.2.1/tkadw/advanced/__pycache__/adw.cpython-311.pyc
--rw-r--r--   0        0        0    18187 2023-06-24 02:38:22.924598 tkadw-0.2.1/tkadw/advanced/__pycache__/icon.cpython-311.pyc
--rw-r--r--   0        0        0     1598 2023-06-24 02:45:43.966706 tkadw-0.2.1/tkadw/advanced/adw.py
--rw-r--r--   0        0        0    17230 2023-06-24 02:38:22.074901 tkadw-0.2.1/tkadw/advanced/icon.py
--rw-r--r--   0        0        0       74 2023-06-09 11:52:45.827295 tkadw-0.2.1/tkadw/app.config
--rw-r--r--   0        0        0      940 2023-06-09 11:52:45.801259 tkadw-0.2.1/tkadw/appconfig.py
--rw-r--r--   0        0        0      959 2023-06-23 11:43:18.569764 tkadw-0.2.1/tkadw/canvas/__init__.py
--rw-r--r--   0        0        0     1801 2023-06-23 11:43:18.792347 tkadw-0.2.1/tkadw/canvas/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0      124 2023-04-15 23:20:17.035856 tkadw-0.2.1/tkadw/canvas/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0        0        0    22598 2023-06-24 01:20:36.024808 tkadw-0.2.1/tkadw/canvas/__pycache__/button.cpython-311.pyc
--rw-r--r--   0        0        0     3479 2023-04-15 23:20:17.037902 tkadw-0.2.1/tkadw/canvas/__pycache__/button.cpython-38.pyc
--rw-r--r--   0        0        0    24261 2023-06-23 09:59:53.052039 tkadw-0.2.1/tkadw/canvas/__pycache__/drawengine.cpython-311.pyc
--rw-r--r--   0        0        0    23658 2023-06-24 02:25:14.940246 tkadw-0.2.1/tkadw/canvas/__pycache__/entry.cpython-311.pyc
--rw-r--r--   0        0        0    11871 2023-06-24 01:50:40.515094 tkadw-0.2.1/tkadw/canvas/__pycache__/frame.cpython-311.pyc
--rw-r--r--   0        0        0    15536 2023-06-10 07:35:47.433931 tkadw-0.2.1/tkadw/canvas/__pycache__/fun6.cpython-311-pytest-7.3.1.pyc
--rw-r--r--   0        0        0     4481 2023-06-24 01:55:47.753570 tkadw-0.2.1/tkadw/canvas/__pycache__/label.cpython-311.pyc
--rw-r--r--   0        0        0    29583 2023-06-24 02:03:31.982563 tkadw-0.2.1/tkadw/canvas/__pycache__/textbox.cpython-311.pyc
--rw-r--r--   0        0        0    16890 2023-06-24 01:20:35.915877 tkadw-0.2.1/tkadw/canvas/button.py
--rw-r--r--   0        0        0    20930 2023-06-23 09:59:52.869076 tkadw-0.2.1/tkadw/canvas/drawengine.py
--rw-r--r--   0        0        0    17378 2023-06-24 02:04:47.104845 tkadw-0.2.1/tkadw/canvas/entry.py
--rw-r--r--   0        0        0     6326 2023-06-24 01:50:40.374060 tkadw-0.2.1/tkadw/canvas/frame.py
--rw-r--r--   0        0        0     2056 2023-06-24 01:55:37.753942 tkadw-0.2.1/tkadw/canvas/label.py
--rw-r--r--   0        0        0    21800 2023-06-24 02:03:31.849264 tkadw-0.2.1/tkadw/canvas/textbox.py
--rw-r--r--   0        0        0     4597 2023-05-27 23:04:22.860566 tkadw-0.2.1/tkadw/canvas/titlebar.py
--rw-r--r--   0        0        0       29 2023-06-23 03:52:51.957932 tkadw-0.2.1/tkadw/tkite/__init__.py
--rw-r--r--   0        0        0      181 2023-06-23 03:52:52.129145 tkadw-0.2.1/tkadw/tkite/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0      341 2023-06-23 11:43:18.508873 tkadw-0.2.1/tkadw/tkite/gtk/__init__.py
--rw-r--r--   0        0        0      719 2023-06-23 11:43:19.769317 tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/__init__.cpython-311.pyc
--rw-r--r--   0        0        0     4723 2023-06-24 01:29:02.487008 tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/button.cpython-311.pyc
--rw-r--r--   0        0        0     3193 2023-06-24 01:44:55.068151 tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/entry.cpython-311.pyc
--rw-r--r--   0        0        0     2375 2023-06-24 01:51:31.925168 tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/frame.cpython-311.pyc
--rw-r--r--   0        0        0     1471 2023-06-23 11:43:19.785605 tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/label.cpython-311.pyc
--rw-r--r--   0        0        0     3149 2023-06-24 02:03:32.305960 tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/textbox.cpython-311.pyc
--rw-r--r--   0        0        0     4735 2023-06-24 01:29:02.053861 tkadw-0.2.1/tkadw/tkite/gtk/button.py
--rw-r--r--   0        0        0     2551 2023-06-24 01:44:54.644195 tkadw-0.2.1/tkadw/tkite/gtk/entry.py
--rw-r--r--   0        0        0     1125 2023-06-24 01:51:31.490298 tkadw-0.2.1/tkadw/tkite/gtk/frame.py
--rw-r--r--   0        0        0      359 2023-06-23 11:43:18.648390 tkadw-0.2.1/tkadw/tkite/gtk/label.py
--rw-r--r--   0        0        0     3555 2023-06-24 00:34:13.973458 tkadw-0.2.1/tkadw/tkite/gtk/notebook.py
--rw-r--r--   0        0        0     2461 2023-06-24 02:03:31.840946 tkadw-0.2.1/tkadw/tkite/gtk/textbox.py
--rw-r--r--   0        0        0     6876 1970-01-01 00:00:00.000000 tkadw-0.2.1/PKG-INFO
+-rw-r--r--   0        0        0      291 2023-06-24 08:02:13.506320 tkadw-0.2.2/pyproject.toml
+-rw-r--r--   0        0        0     6873 2023-06-28 08:48:37.637746 tkadw-0.2.2/README.md
+-rw-r--r--   0        0        0      469 2023-06-24 12:01:11.022261 tkadw-0.2.2/tkadw/__init__.py
+-rw-r--r--   0        0        0     2058 2023-06-24 10:25:22.777909 tkadw-0.2.2/tkadw/__main__.py
+-rw-r--r--   0        0        0      142 2023-06-24 02:43:29.551423 tkadw-0.2.2/tkadw/advanced/__init__.py
+-rw-r--r--   0        0        0      383 2023-06-24 02:43:30.014259 tkadw-0.2.2/tkadw/advanced/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0     2906 2023-06-24 02:46:00.929979 tkadw-0.2.2/tkadw/advanced/__pycache__/adw.cpython-311.pyc
+-rw-r--r--   0        0        0    18187 2023-06-24 02:38:22.924598 tkadw-0.2.2/tkadw/advanced/__pycache__/icon.cpython-311.pyc
+-rw-r--r--   0        0        0     1598 2023-06-24 02:45:43.966706 tkadw-0.2.2/tkadw/advanced/adw.py
+-rw-r--r--   0        0        0    17230 2023-06-24 02:38:22.074901 tkadw-0.2.2/tkadw/advanced/icon.py
+-rw-r--r--   0        0        0       74 2023-06-09 11:52:45.827295 tkadw-0.2.2/tkadw/app.config
+-rw-r--r--   0        0        0      940 2023-06-09 11:52:45.801259 tkadw-0.2.2/tkadw/appconfig.py
+-rw-r--r--   0        0        0     7565 2023-06-24 10:30:34.831550 tkadw-0.2.2/tkadw/bilibili.py
+-rw-r--r--   0        0        0      959 2023-06-23 11:43:18.569764 tkadw-0.2.2/tkadw/canvas/__init__.py
+-rw-r--r--   0        0        0     1801 2023-06-23 11:43:18.792347 tkadw-0.2.2/tkadw/canvas/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0      124 2023-04-15 23:20:17.035856 tkadw-0.2.2/tkadw/canvas/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0        0        0    23047 2023-06-28 08:46:09.743814 tkadw-0.2.2/tkadw/canvas/__pycache__/button.cpython-311.pyc
+-rw-r--r--   0        0        0     3479 2023-04-15 23:20:17.037902 tkadw-0.2.2/tkadw/canvas/__pycache__/button.cpython-38.pyc
+-rw-r--r--   0        0        0    25158 2023-06-24 04:53:01.771318 tkadw-0.2.2/tkadw/canvas/__pycache__/drawengine.cpython-311.pyc
+-rw-r--r--   0        0        0    24544 2023-06-24 12:14:29.830606 tkadw-0.2.2/tkadw/canvas/__pycache__/entry.cpython-311.pyc
+-rw-r--r--   0        0        0    11883 2023-06-24 12:14:29.824607 tkadw-0.2.2/tkadw/canvas/__pycache__/frame.cpython-311.pyc
+-rw-r--r--   0        0        0    15536 2023-06-10 07:35:47.433931 tkadw-0.2.2/tkadw/canvas/__pycache__/fun6.cpython-311-pytest-7.3.1.pyc
+-rw-r--r--   0        0        0     4419 2023-06-24 09:52:58.175090 tkadw-0.2.2/tkadw/canvas/__pycache__/label.cpython-311.pyc
+-rw-r--r--   0        0        0    28157 2023-06-24 11:41:35.170220 tkadw-0.2.2/tkadw/canvas/__pycache__/textbox.cpython-311.pyc
+-rw-r--r--   0        0        0    17976 2023-06-28 08:46:09.599763 tkadw-0.2.2/tkadw/canvas/button.py
+-rw-r--r--   0        0        0     6321 2023-06-24 03:29:46.590796 tkadw-0.2.2/tkadw/canvas/checkbox.py
+-rw-r--r--   0        0        0    21612 2023-06-24 04:00:28.964404 tkadw-0.2.2/tkadw/canvas/drawengine.py
+-rw-r--r--   0        0        0    18319 2023-06-24 12:14:29.680635 tkadw-0.2.2/tkadw/canvas/entry.py
+-rw-r--r--   0        0        0     6506 2023-06-24 12:14:29.672566 tkadw-0.2.2/tkadw/canvas/frame.py
+-rw-r--r--   0        0        0     2020 2023-06-24 06:56:34.581673 tkadw-0.2.2/tkadw/canvas/label.py
+-rw-r--r--   0        0        0    20506 2023-06-24 11:39:54.083259 tkadw-0.2.2/tkadw/canvas/textbox.py
+-rw-r--r--   0        0        0     4597 2023-05-27 23:04:22.860566 tkadw-0.2.2/tkadw/canvas/titlebar.py
+-rw-r--r--   0        0        0       29 2023-06-23 03:52:51.957932 tkadw-0.2.2/tkadw/tkite/__init__.py
+-rw-r--r--   0        0        0      181 2023-06-23 03:52:52.129145 tkadw-0.2.2/tkadw/tkite/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0      341 2023-06-23 11:43:18.508873 tkadw-0.2.2/tkadw/tkite/gtk/__init__.py
+-rw-r--r--   0        0        0      719 2023-06-23 11:43:19.769317 tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/__init__.cpython-311.pyc
+-rw-r--r--   0        0        0     4723 2023-06-24 01:29:02.487008 tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/button.cpython-311.pyc
+-rw-r--r--   0        0        0     3193 2023-06-24 01:44:55.068151 tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/entry.cpython-311.pyc
+-rw-r--r--   0        0        0     2375 2023-06-24 01:51:31.925168 tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/frame.cpython-311.pyc
+-rw-r--r--   0        0        0     1471 2023-06-23 11:43:19.785605 tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/label.cpython-311.pyc
+-rw-r--r--   0        0        0     3149 2023-06-24 02:03:32.305960 tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/textbox.cpython-311.pyc
+-rw-r--r--   0        0        0     4735 2023-06-24 01:29:02.053861 tkadw-0.2.2/tkadw/tkite/gtk/button.py
+-rw-r--r--   0        0        0     2551 2023-06-24 01:44:54.644195 tkadw-0.2.2/tkadw/tkite/gtk/entry.py
+-rw-r--r--   0        0        0     1125 2023-06-24 01:51:31.490298 tkadw-0.2.2/tkadw/tkite/gtk/frame.py
+-rw-r--r--   0        0        0      359 2023-06-23 11:43:18.648390 tkadw-0.2.2/tkadw/tkite/gtk/label.py
+-rw-r--r--   0        0        0     3555 2023-06-24 00:34:13.973458 tkadw-0.2.2/tkadw/tkite/gtk/notebook.py
+-rw-r--r--   0        0        0     2461 2023-06-24 02:03:31.840946 tkadw-0.2.2/tkadw/tkite/gtk/textbox.py
+-rw-r--r--   0        0        0    11241 2023-06-28 08:47:03.187671 tkadw-0.2.2/tkadw/win11.py
+-rw-r--r--   0        0        0     7184 1970-01-01 00:00:00.000000 tkadw-0.2.2/PKG-INFO
```

### Comparing `tkadw-0.2.1/README.md` & `tkadw-0.2.2/README.md`

 * *Files 8% similar despite different names*

```diff
@@ -219,8 +219,19 @@
 >> `202`改变修复`AdwDrawEntry`的`Entry`组件在`Linux`平台下出现边框
 > 
 >> `203`修复各别解释器类似注释的错误
 
 > `0.2.1`
 >> `211`扩充README文档
 >
->> `212`新增组件`Adw`
+>> `212`新增组件`Adw`
+> 
+>> `213`删除多余文件
+
+> `0.2.2` 
+>> `221`扩展额外界面库`BiliBili`，根据`BiliBili桌面版`设计
+> 
+>> `222`修复`palette`修改完后没完全修改配色的问题
+> 
+>> `223`扩展额外界面库`Win11`，根据`Sunvalley`设计
+> 
+>> `224`修复`AdwDrawButton`类边框遮挡的问题
```

### Comparing `tkadw-0.2.1/tkadw/advanced/__pycache__/adw.cpython-311.pyc` & `tkadw-0.2.2/tkadw/advanced/__pycache__/adw.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/advanced/__pycache__/icon.cpython-311.pyc` & `tkadw-0.2.2/tkadw/advanced/__pycache__/icon.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/advanced/adw.py` & `tkadw-0.2.2/tkadw/advanced/adw.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/advanced/icon.py` & `tkadw-0.2.2/tkadw/advanced/icon.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/appconfig.py` & `tkadw-0.2.2/tkadw/appconfig.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/canvas/__init__.py` & `tkadw-0.2.2/tkadw/canvas/__init__.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/canvas/__pycache__/__init__.cpython-311.pyc` & `tkadw-0.2.2/tkadw/canvas/__pycache__/__init__.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/canvas/__pycache__/button.cpython-311.pyc` & `tkadw-0.2.2/tkadw/canvas/__pycache__/button.cpython-311.pyc`

 * *Files 11% similar despite different names*

#### Python bytecode

```diff
@@ -1,10 +1,10 @@
 magic:    0xa70d0d0a
-moddate:  0xe3449664 (Sat Jun 24 01:20:35 2023 UTC)
-files sz: 16890
+moddate:  0x51f39b64 (Wed Jun 28 08:46:09 2023 UTC)
+files sz: 17976
 code
    argcount  : 0
    nlocals   : 0
    stacksize : 5
    flags     : 0
    code
       0x9700640064016c006d015a016d025a020100640064026c036d045a0401
@@ -71,337 +71,337 @@
                 36 MAKE_FUNCTION            0
                 38 LOAD_CONST               4 ('AdwDrawBasicButton')
                 40 LOAD_NAME                4 (AdwDrawEngine)
                 42 PRECALL                  3
                 46 CALL                     3
                 56 STORE_NAME               5 (AdwDrawBasicButton)
    
-   194          58 PUSH_NULL
+   205          58 PUSH_NULL
                 60 LOAD_BUILD_CLASS
-                62 LOAD_CONST               5 (<code object AdwDrawButton, file "D:\tkadw\tkadw\canvas\button.py", line 194>)
+                62 LOAD_CONST               5 (<code object AdwDrawButton, file "D:\tkadw\tkadw\canvas\button.py", line 205>)
                 64 MAKE_FUNCTION            0
                 66 LOAD_CONST               6 ('AdwDrawButton')
                 68 LOAD_NAME                5 (AdwDrawBasicButton)
                 70 PRECALL                  3
                 74 CALL                     3
                 84 STORE_NAME               6 (AdwDrawButton)
    
-   199          86 PUSH_NULL
+   210          86 PUSH_NULL
                 88 LOAD_BUILD_CLASS
-                90 LOAD_CONST               7 (<code object AdwDrawDarkButton, file "D:\tkadw\tkadw\canvas\button.py", line 199>)
+                90 LOAD_CONST               7 (<code object AdwDrawDarkButton, file "D:\tkadw\tkadw\canvas\button.py", line 210>)
                 92 MAKE_FUNCTION            0
                 94 LOAD_CONST               8 ('AdwDrawDarkButton')
                 96 LOAD_NAME                5 (AdwDrawBasicButton)
                 98 PRECALL                  3
                102 CALL                     3
                112 STORE_NAME               7 (AdwDrawDarkButton)
    
-   204         114 PUSH_NULL
+   215         114 PUSH_NULL
                116 LOAD_BUILD_CLASS
-               118 LOAD_CONST               9 (<code object AdwDrawAccentButton, file "D:\tkadw\tkadw\canvas\button.py", line 204>)
+               118 LOAD_CONST               9 (<code object AdwDrawAccentButton, file "D:\tkadw\tkadw\canvas\button.py", line 215>)
                120 MAKE_FUNCTION            0
                122 LOAD_CONST              10 ('AdwDrawAccentButton')
                124 LOAD_NAME                5 (AdwDrawBasicButton)
                126 PRECALL                  3
                130 CALL                     3
                140 STORE_NAME               8 (AdwDrawAccentButton)
    
-   233         142 PUSH_NULL
+   244         142 PUSH_NULL
                144 LOAD_BUILD_CLASS
-               146 LOAD_CONST              11 (<code object AdwDrawBasicRoundButton, file "D:\tkadw\tkadw\canvas\button.py", line 233>)
+               146 LOAD_CONST              11 (<code object AdwDrawBasicRoundButton, file "D:\tkadw\tkadw\canvas\button.py", line 244>)
                148 MAKE_FUNCTION            0
                150 LOAD_CONST              12 ('AdwDrawBasicRoundButton')
                152 LOAD_NAME                5 (AdwDrawBasicButton)
                154 PRECALL                  3
                158 CALL                     3
                168 STORE_NAME               9 (AdwDrawBasicRoundButton)
    
-   318         170 PUSH_NULL
+   334         170 PUSH_NULL
                172 LOAD_BUILD_CLASS
-               174 LOAD_CONST              13 (<code object AdwDrawRoundButton, file "D:\tkadw\tkadw\canvas\button.py", line 318>)
+               174 LOAD_CONST              13 (<code object AdwDrawRoundButton, file "D:\tkadw\tkadw\canvas\button.py", line 334>)
                176 MAKE_FUNCTION            0
                178 LOAD_CONST              14 ('AdwDrawRoundButton')
                180 LOAD_NAME                9 (AdwDrawBasicRoundButton)
                182 PRECALL                  3
                186 CALL                     3
                196 STORE_NAME              10 (AdwDrawRoundButton)
    
-   323         198 PUSH_NULL
+   339         198 PUSH_NULL
                200 LOAD_BUILD_CLASS
-               202 LOAD_CONST              15 (<code object AdwDrawRoundAccentButton, file "D:\tkadw\tkadw\canvas\button.py", line 323>)
+               202 LOAD_CONST              15 (<code object AdwDrawRoundAccentButton, file "D:\tkadw\tkadw\canvas\button.py", line 339>)
                204 MAKE_FUNCTION            0
                206 LOAD_CONST              16 ('AdwDrawRoundAccentButton')
                208 LOAD_NAME                9 (AdwDrawBasicRoundButton)
                210 PRECALL                  3
                214 CALL                     3
                224 STORE_NAME              11 (AdwDrawRoundAccentButton)
    
-   352         226 PUSH_NULL
+   368         226 PUSH_NULL
                228 LOAD_BUILD_CLASS
-               230 LOAD_CONST              17 (<code object AdwDrawRoundDarkButton, file "D:\tkadw\tkadw\canvas\button.py", line 352>)
+               230 LOAD_CONST              17 (<code object AdwDrawRoundDarkButton, file "D:\tkadw\tkadw\canvas\button.py", line 368>)
                232 MAKE_FUNCTION            0
                234 LOAD_CONST              18 ('AdwDrawRoundDarkButton')
                236 LOAD_NAME                9 (AdwDrawBasicRoundButton)
                238 PRECALL                  3
                242 CALL                     3
                252 STORE_NAME              12 (AdwDrawRoundDarkButton)
    
-   357         254 PUSH_NULL
+   373         254 PUSH_NULL
                256 LOAD_BUILD_CLASS
-               258 LOAD_CONST              19 (<code object AdwDrawRoundButton2, file "D:\tkadw\tkadw\canvas\button.py", line 357>)
+               258 LOAD_CONST              19 (<code object AdwDrawRoundButton2, file "D:\tkadw\tkadw\canvas\button.py", line 373>)
                260 MAKE_FUNCTION            0
                262 LOAD_CONST              20 ('AdwDrawRoundButton2')
                264 LOAD_NAME                9 (AdwDrawBasicRoundButton)
                266 PRECALL                  3
                270 CALL                     3
                280 STORE_NAME              13 (AdwDrawRoundButton2)
    
-   379         282 PUSH_NULL
+   399         282 PUSH_NULL
                284 LOAD_BUILD_CLASS
-               286 LOAD_CONST              21 (<code object AdwDrawRoundAccentButton2, file "D:\tkadw\tkadw\canvas\button.py", line 379>)
+               286 LOAD_CONST              21 (<code object AdwDrawRoundAccentButton2, file "D:\tkadw\tkadw\canvas\button.py", line 399>)
                288 MAKE_FUNCTION            0
                290 LOAD_CONST              22 ('AdwDrawRoundAccentButton2')
                292 LOAD_NAME               13 (AdwDrawRoundButton2)
                294 PRECALL                  3
                298 CALL                     3
                308 STORE_NAME              14 (AdwDrawRoundAccentButton2)
    
-   408         310 PUSH_NULL
+   428         310 PUSH_NULL
                312 LOAD_BUILD_CLASS
-               314 LOAD_CONST              23 (<code object AdwDrawRoundDarkButton2, file "D:\tkadw\tkadw\canvas\button.py", line 408>)
+               314 LOAD_CONST              23 (<code object AdwDrawRoundDarkButton2, file "D:\tkadw\tkadw\canvas\button.py", line 428>)
                316 MAKE_FUNCTION            0
                318 LOAD_CONST              24 ('AdwDrawRoundDarkButton2')
                320 LOAD_NAME               13 (AdwDrawRoundButton2)
                322 PRECALL                  3
                326 CALL                     3
                336 STORE_NAME              15 (AdwDrawRoundDarkButton2)
    
-   413         338 PUSH_NULL
+   433         338 PUSH_NULL
                340 LOAD_BUILD_CLASS
-               342 LOAD_CONST              25 (<code object AdwDrawRoundButton3, file "D:\tkadw\tkadw\canvas\button.py", line 413>)
+               342 LOAD_CONST              25 (<code object AdwDrawRoundButton3, file "D:\tkadw\tkadw\canvas\button.py", line 433>)
                344 MAKE_FUNCTION            0
                346 LOAD_CONST              26 ('AdwDrawRoundButton3')
                348 LOAD_NAME                9 (AdwDrawBasicRoundButton)
                350 PRECALL                  3
                354 CALL                     3
                364 STORE_NAME              16 (AdwDrawRoundButton3)
    
-   435         366 PUSH_NULL
+   460         366 PUSH_NULL
                368 LOAD_BUILD_CLASS
-               370 LOAD_CONST              27 (<code object AdwDrawRoundAccentButton3, file "D:\tkadw\tkadw\canvas\button.py", line 435>)
+               370 LOAD_CONST              27 (<code object AdwDrawRoundAccentButton3, file "D:\tkadw\tkadw\canvas\button.py", line 460>)
                372 MAKE_FUNCTION            0
                374 LOAD_CONST              28 ('AdwDrawRoundAccentButton3')
                376 LOAD_NAME               16 (AdwDrawRoundButton3)
                378 PRECALL                  3
                382 CALL                     3
                392 STORE_NAME              17 (AdwDrawRoundAccentButton3)
    
-   464         394 PUSH_NULL
+   489         394 PUSH_NULL
                396 LOAD_BUILD_CLASS
-               398 LOAD_CONST              29 (<code object AdwDrawRoundDarkButton3, file "D:\tkadw\tkadw\canvas\button.py", line 464>)
+               398 LOAD_CONST              29 (<code object AdwDrawRoundDarkButton3, file "D:\tkadw\tkadw\canvas\button.py", line 489>)
                400 MAKE_FUNCTION            0
                402 LOAD_CONST              30 ('AdwDrawRoundDarkButton3')
                404 LOAD_NAME               16 (AdwDrawRoundButton3)
                406 PRECALL                  3
                410 CALL                     3
                420 STORE_NAME              18 (AdwDrawRoundDarkButton3)
    
-   470         422 PUSH_NULL
+   495         422 PUSH_NULL
                424 LOAD_BUILD_CLASS
-               426 LOAD_CONST              31 (<code object AdwDrawBasicCircularButton, file "D:\tkadw\tkadw\canvas\button.py", line 470>)
+               426 LOAD_CONST              31 (<code object AdwDrawBasicCircularButton, file "D:\tkadw\tkadw\canvas\button.py", line 495>)
                428 MAKE_FUNCTION            0
                430 LOAD_CONST              32 ('AdwDrawBasicCircularButton')
                432 LOAD_NAME                5 (AdwDrawBasicButton)
                434 PRECALL                  3
                438 CALL                     3
                448 STORE_NAME              19 (AdwDrawBasicCircularButton)
    
-   490         450 PUSH_NULL
+   517         450 PUSH_NULL
                452 LOAD_BUILD_CLASS
-               454 LOAD_CONST              33 (<code object AdwDrawCircularButton, file "D:\tkadw\tkadw\canvas\button.py", line 490>)
+               454 LOAD_CONST              33 (<code object AdwDrawCircularButton, file "D:\tkadw\tkadw\canvas\button.py", line 517>)
                456 MAKE_FUNCTION            0
                458 LOAD_CONST              34 ('AdwDrawCircularButton')
                460 LOAD_NAME               19 (AdwDrawBasicCircularButton)
                462 PRECALL                  3
                466 CALL                     3
                476 STORE_NAME              20 (AdwDrawCircularButton)
    
-   495         478 PUSH_NULL
+   522         478 PUSH_NULL
                480 LOAD_BUILD_CLASS
-               482 LOAD_CONST              35 (<code object AdwDrawCircularDarkButton, file "D:\tkadw\tkadw\canvas\button.py", line 495>)
+               482 LOAD_CONST              35 (<code object AdwDrawCircularDarkButton, file "D:\tkadw\tkadw\canvas\button.py", line 522>)
                484 MAKE_FUNCTION            0
                486 LOAD_CONST              36 ('AdwDrawCircularDarkButton')
                488 LOAD_NAME               19 (AdwDrawBasicCircularButton)
                490 PRECALL                  3
                494 CALL                     3
                504 STORE_NAME              21 (AdwDrawCircularDarkButton)
    
-   500         506 LOAD_NAME               22 (__name__)
+   527         506 LOAD_NAME               22 (__name__)
                508 LOAD_CONST              37 ('__main__')
                510 COMPARE_OP               2 (==)
                516 EXTENDED_ARG             1
                518 POP_JUMP_FORWARD_IF_FALSE   333 (to 1186)
    
-   501         520 LOAD_CONST               0 (0)
+   528         520 LOAD_CONST               0 (0)
                522 LOAD_CONST              38 (('Tk',))
                524 IMPORT_NAME             23 (tkinter)
                526 IMPORT_FROM             24 (Tk)
                528 STORE_NAME              24 (Tk)
                530 POP_TOP
    
-   503         532 PUSH_NULL
+   530         532 PUSH_NULL
                534 LOAD_NAME               24 (Tk)
                536 PRECALL                  0
                540 CALL                     0
                550 STORE_NAME              25 (root)
    
-   505         552 PUSH_NULL
+   532         552 PUSH_NULL
                554 LOAD_NAME                6 (AdwDrawButton)
                556 LOAD_CONST              39 ('Hello')
                558 KW_NAMES                40
                560 PRECALL                  1
                564 CALL                     1
                574 STORE_NAME              26 (button)
    
-   506         576 LOAD_NAME               26 (button)
+   533         576 LOAD_NAME               26 (button)
                578 LOAD_METHOD             27 (bind)
                600 LOAD_CONST              41 ('<<Click>>')
-               602 LOAD_CONST              42 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 506>)
+               602 LOAD_CONST              42 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 533>)
                604 MAKE_FUNCTION            0
                606 PRECALL                  2
                610 CALL                     2
                620 POP_TOP
    
-   507         622 LOAD_NAME               26 (button)
+   534         622 LOAD_NAME               26 (button)
                624 LOAD_METHOD             28 (pack)
                646 LOAD_CONST              43 ('x')
                648 LOAD_CONST              44 (5)
                650 LOAD_CONST              44 (5)
                652 KW_NAMES                45
                654 PRECALL                  3
                658 CALL                     3
                668 POP_TOP
    
-   509         670 PUSH_NULL
+   536         670 PUSH_NULL
                672 LOAD_NAME               10 (AdwDrawRoundButton)
                674 LOAD_CONST              39 ('Hello')
                676 KW_NAMES                40
                678 PRECALL                  1
                682 CALL                     1
                692 STORE_NAME              29 (button4)
    
-   510         694 LOAD_NAME               29 (button4)
+   537         694 LOAD_NAME               29 (button4)
                696 LOAD_METHOD             27 (bind)
                718 LOAD_CONST              41 ('<<Click>>')
-               720 LOAD_CONST              46 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 510>)
+               720 LOAD_CONST              46 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 537>)
                722 MAKE_FUNCTION            0
                724 PRECALL                  2
                728 CALL                     2
                738 POP_TOP
    
-   511         740 LOAD_NAME               29 (button4)
+   538         740 LOAD_NAME               29 (button4)
                742 LOAD_METHOD             28 (pack)
                764 LOAD_CONST              43 ('x')
                766 LOAD_CONST              44 (5)
                768 LOAD_CONST              44 (5)
                770 KW_NAMES                45
                772 PRECALL                  3
                776 CALL                     3
                786 POP_TOP
    
-   513         788 PUSH_NULL
+   540         788 PUSH_NULL
                790 LOAD_NAME               13 (AdwDrawRoundButton2)
                792 LOAD_CONST              39 ('Hello')
                794 KW_NAMES                40
                796 PRECALL                  1
                800 CALL                     1
                810 STORE_NAME              30 (button7)
    
-   514         812 LOAD_NAME               30 (button7)
+   541         812 LOAD_NAME               30 (button7)
                814 LOAD_METHOD             27 (bind)
                836 LOAD_CONST              41 ('<<Click>>')
-               838 LOAD_CONST              47 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 514>)
+               838 LOAD_CONST              47 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 541>)
                840 MAKE_FUNCTION            0
                842 PRECALL                  2
                846 CALL                     2
                856 POP_TOP
    
-   515         858 LOAD_NAME               30 (button7)
+   542         858 LOAD_NAME               30 (button7)
                860 LOAD_METHOD             28 (pack)
                882 LOAD_CONST              43 ('x')
                884 LOAD_CONST              44 (5)
                886 LOAD_CONST              44 (5)
                888 KW_NAMES                45
                890 PRECALL                  3
                894 CALL                     3
                904 POP_TOP
    
-   517         906 PUSH_NULL
+   544         906 PUSH_NULL
                908 LOAD_NAME               16 (AdwDrawRoundButton3)
                910 LOAD_CONST              39 ('Hello')
                912 KW_NAMES                40
                914 PRECALL                  1
                918 CALL                     1
                928 STORE_NAME              31 (button10)
    
-   518         930 LOAD_NAME               31 (button10)
+   545         930 LOAD_NAME               31 (button10)
                932 LOAD_METHOD             27 (bind)
                954 LOAD_CONST              41 ('<<Click>>')
-               956 LOAD_CONST              48 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 518>)
+               956 LOAD_CONST              48 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 545>)
                958 MAKE_FUNCTION            0
                960 PRECALL                  2
                964 CALL                     2
                974 POP_TOP
    
-   519         976 LOAD_NAME               31 (button10)
+   546         976 LOAD_NAME               31 (button10)
                978 LOAD_METHOD             28 (pack)
               1000 LOAD_CONST              43 ('x')
               1002 LOAD_CONST              44 (5)
               1004 LOAD_CONST              44 (5)
               1006 KW_NAMES                45
               1008 PRECALL                  3
               1012 CALL                     3
               1022 POP_TOP
    
-   521        1024 PUSH_NULL
+   548        1024 PUSH_NULL
               1026 LOAD_NAME               20 (AdwDrawCircularButton)
               1028 LOAD_CONST              39 ('Hello')
               1030 KW_NAMES                40
               1032 PRECALL                  1
               1036 CALL                     1
               1046 STORE_NAME              32 (button13)
    
-   522        1048 LOAD_NAME               32 (button13)
+   549        1048 LOAD_NAME               32 (button13)
               1050 LOAD_METHOD             27 (bind)
               1072 LOAD_CONST              41 ('<<Click>>')
-              1074 LOAD_CONST              49 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 522>)
+              1074 LOAD_CONST              49 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 549>)
               1076 MAKE_FUNCTION            0
               1078 PRECALL                  2
               1082 CALL                     2
               1092 POP_TOP
    
-   523        1094 LOAD_NAME               32 (button13)
+   550        1094 LOAD_NAME               32 (button13)
               1096 LOAD_METHOD             28 (pack)
               1118 LOAD_CONST              43 ('x')
               1120 LOAD_CONST              44 (5)
               1122 LOAD_CONST              44 (5)
               1124 KW_NAMES                45
               1126 PRECALL                  3
               1130 CALL                     3
               1140 POP_TOP
    
-   525        1142 LOAD_NAME               25 (root)
+   552        1142 LOAD_NAME               25 (root)
               1144 LOAD_METHOD             33 (mainloop)
               1166 PRECALL                  0
               1170 CALL                     0
               1180 POP_TOP
               1182 LOAD_CONST              50 (None)
               1184 RETURN_VALUE
    
-   500     >> 1186 LOAD_CONST              50 (None)
+   527     >> 1186 LOAD_CONST              50 (None)
               1188 RETURN_VALUE
    consts
       0
       ('Font', 'nametofont')
       ('AdwDrawEngine',)
       code
          argcount  : 0
@@ -433,70 +433,70 @@
                       28 BUILD_TUPLE              2
                       30 LOAD_CLOSURE             0 (__class__)
                       32 BUILD_TUPLE              1
                       34 LOAD_CONST               7 (<code object __init__, file "D:\tkadw\tkadw\canvas\button.py", line 7>)
                       36 MAKE_FUNCTION           14 (kwdefaults, annotations, closure)
                       38 STORE_NAME               4 (__init__)
          
-          34          40 LOAD_CLOSURE             0 (__class__)
+          36          40 LOAD_CLOSURE             0 (__class__)
                       42 BUILD_TUPLE              1
-                      44 LOAD_CONST               8 (<code object configure, file "D:\tkadw\tkadw\canvas\button.py", line 34>)
+                      44 LOAD_CONST               8 (<code object configure, file "D:\tkadw\tkadw\canvas\button.py", line 36>)
                       46 MAKE_FUNCTION            8 (closure)
                       48 STORE_NAME               5 (configure)
          
-          44          50 LOAD_CONST               9 (<code object _other, file "D:\tkadw\tkadw\canvas\button.py", line 44>)
+          46          50 LOAD_CONST               9 (<code object _other, file "D:\tkadw\tkadw\canvas\button.py", line 46>)
                       52 MAKE_FUNCTION            0
                       54 STORE_NAME               6 (_other)
          
-          48          56 LOAD_CONST              10 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 48>)
+          50          56 LOAD_CONST              10 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 50>)
                       58 MAKE_FUNCTION            0
                       60 STORE_NAME               7 (_draw)
          
-          63          62 LOAD_CONST              21 ((None,))
-                      64 LOAD_CONST              11 (<code object _click, file "D:\tkadw\tkadw\canvas\button.py", line 63>)
+          69          62 LOAD_CONST              21 ((None,))
+                      64 LOAD_CONST              11 (<code object _click, file "D:\tkadw\tkadw\canvas\button.py", line 69>)
                       66 MAKE_FUNCTION            1 (defaults)
                       68 STORE_NAME               8 (_click)
          
-          74          70 LOAD_CONST              21 ((None,))
-                      72 LOAD_CONST              12 (<code object _unclick, file "D:\tkadw\tkadw\canvas\button.py", line 74>)
+          80          70 LOAD_CONST              21 ((None,))
+                      72 LOAD_CONST              12 (<code object _unclick, file "D:\tkadw\tkadw\canvas\button.py", line 80>)
                       74 MAKE_FUNCTION            1 (defaults)
                       76 STORE_NAME               9 (_unclick)
          
-          85          78 LOAD_CONST              21 ((None,))
-                      80 LOAD_CONST              13 (<code object _hover, file "D:\tkadw\tkadw\canvas\button.py", line 85>)
+          91          78 LOAD_CONST              21 ((None,))
+                      80 LOAD_CONST              13 (<code object _hover, file "D:\tkadw\tkadw\canvas\button.py", line 91>)
                       82 MAKE_FUNCTION            1 (defaults)
                       84 STORE_NAME              10 (_hover)
          
-          94          86 LOAD_CONST              21 ((None,))
-                      88 LOAD_CONST              14 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\button.py", line 94>)
+         100          86 LOAD_CONST              21 ((None,))
+                      88 LOAD_CONST              14 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\button.py", line 100>)
                       90 MAKE_FUNCTION            1 (defaults)
                       92 STORE_NAME              11 (_hover_release)
          
-         103          94 LOAD_CONST              21 ((None,))
+         109          94 LOAD_CONST              21 ((None,))
                       96 LOAD_CONST              15 ('font')
                       98 LOAD_NAME               12 (Font)
                      100 BUILD_TUPLE              2
-                     102 LOAD_CONST              16 (<code object font, file "D:\tkadw\tkadw\canvas\button.py", line 103>)
+                     102 LOAD_CONST              16 (<code object font, file "D:\tkadw\tkadw\canvas\button.py", line 109>)
                      104 MAKE_FUNCTION            5 (defaults, annotations)
                      106 STORE_NAME              13 (font)
          
-         109         108 LOAD_CONST              17 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 109>)
+         115         108 LOAD_CONST              17 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 115>)
                      110 MAKE_FUNCTION            0
                      112 STORE_NAME              14 (default_palette)
          
-         112         114 LOAD_CONST              18 (<code object palette_light, file "D:\tkadw\tkadw\canvas\button.py", line 112>)
+         118         114 LOAD_CONST              18 (<code object palette_light, file "D:\tkadw\tkadw\canvas\button.py", line 118>)
                      116 MAKE_FUNCTION            0
                      118 STORE_NAME              15 (palette_light)
          
-         138         120 LOAD_CONST              19 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\button.py", line 138>)
+         144         120 LOAD_CONST              19 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\button.py", line 144>)
                      122 MAKE_FUNCTION            0
                      124 STORE_NAME              16 (palette_dark)
          
-         164         126 LOAD_CONST              21 ((None,))
-                     128 LOAD_CONST              20 (<code object palette, file "D:\tkadw\tkadw\canvas\button.py", line 164>)
+         170         126 LOAD_CONST              21 ((None,))
+                     128 LOAD_CONST              20 (<code object palette, file "D:\tkadw\tkadw\canvas\button.py", line 170>)
                      130 MAKE_FUNCTION            1 (defaults)
                      132 STORE_NAME              17 (palette)
                      134 LOAD_CLOSURE             0 (__class__)
                      136 COPY                     1
                      138 STORE_NAME              18 (__classcell__)
                      140 RETURN_VALUE
          consts
@@ -597,84 +597,84 @@
                 21         256 LOAD_GLOBAL             27 (NULL + nametofont)
                            268 LOAD_CONST               3 ('TkDefaultFont')
                            270 PRECALL                  1
                            274 CALL                     1
                            284 LOAD_FAST                0 (self)
                            286 STORE_ATTR              14 (button_text_font)
                
-                23         296 LOAD_FAST                0 (self)
+                24         296 LOAD_FAST                0 (self)
                            298 LOAD_METHOD             15 (bind)
                            320 LOAD_CONST               4 ('<Configure>')
                            322 LOAD_FAST                0 (self)
                            324 LOAD_ATTR               16 (_draw)
                            334 LOAD_CONST               5 ('+')
                            336 KW_NAMES                 6
                            338 PRECALL                  3
                            342 CALL                     3
                            352 POP_TOP
                
-                24         354 LOAD_FAST                0 (self)
+                25         354 LOAD_FAST                0 (self)
                            356 LOAD_METHOD             15 (bind)
                            378 LOAD_CONST               7 ('<Button>')
                            380 LOAD_FAST                0 (self)
                            382 LOAD_ATTR               17 (_click)
                            392 LOAD_CONST               5 ('+')
                            394 KW_NAMES                 6
                            396 PRECALL                  3
                            400 CALL                     3
                            410 POP_TOP
                
-                25         412 LOAD_FAST                0 (self)
+                26         412 LOAD_FAST                0 (self)
                            414 LOAD_METHOD             15 (bind)
                            436 LOAD_CONST               8 ('<ButtonRelease>')
                            438 LOAD_FAST                0 (self)
                            440 LOAD_ATTR               18 (_unclick)
                            450 LOAD_CONST               5 ('+')
                            452 KW_NAMES                 6
                            454 PRECALL                  3
                            458 CALL                     3
                            468 POP_TOP
                
-                26         470 LOAD_FAST                0 (self)
+                27         470 LOAD_FAST                0 (self)
                            472 LOAD_METHOD             15 (bind)
                            494 LOAD_CONST               9 ('<Enter>')
                            496 LOAD_FAST                0 (self)
                            498 LOAD_ATTR               19 (_hover)
                            508 LOAD_CONST               5 ('+')
                            510 KW_NAMES                 6
                            512 PRECALL                  3
                            516 CALL                     3
                            526 POP_TOP
                
-                27         528 LOAD_FAST                0 (self)
+                28         528 LOAD_FAST                0 (self)
                            530 LOAD_METHOD             15 (bind)
                            552 LOAD_CONST              10 ('<Leave>')
                            554 LOAD_FAST                0 (self)
                            556 LOAD_ATTR               20 (_hover_release)
                            566 LOAD_CONST               5 ('+')
                            568 KW_NAMES                 6
                            570 PRECALL                  3
                            574 CALL                     3
                            584 POP_TOP
                
-                29         586 LOAD_DEREF               4 (command)
+                31         586 LOAD_DEREF               4 (command)
                            588 POP_JUMP_FORWARD_IF_NONE    25 (to 640)
                
-                30         590 LOAD_FAST                0 (self)
+                32         590 LOAD_FAST                0 (self)
                            592 LOAD_METHOD             15 (bind)
                            614 LOAD_CONST              11 ('<<Click>>')
                            616 LOAD_CLOSURE             4 (command)
                            618 BUILD_TUPLE              1
-                           620 LOAD_CONST              12 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 30>)
+                           620 LOAD_CONST              12 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 32>)
                            622 MAKE_FUNCTION            8 (closure)
                            624 PRECALL                  2
                            628 CALL                     2
                            638 POP_TOP
                
-                32     >>  640 LOAD_FAST                0 (self)
+                34     >>  640 LOAD_FAST                0 (self)
                            642 LOAD_METHOD             16 (_draw)
                            664 LOAD_CONST               0 (None)
                            666 PRECALL                  1
                            670 CALL                     1
                            680 POP_TOP
                            682 LOAD_CONST               0 (None)
                            684 RETURN_VALUE
@@ -695,40 +695,40 @@
                      argcount  : 1
                      nlocals   : 1
                      stacksize : 2
                      flags     : 19
                      code 0x9501970002008901a6000000ab0000000000000000005300
                                    0 COPY_FREE_VARS           1
                      
-                      30           2 RESUME                   0
+                      32           2 RESUME                   0
                                    4 PUSH_NULL
                                    6 LOAD_DEREF               1 (command)
                                    8 PRECALL                  0
                                   12 CALL                     0
                                   22 RETURN_VALUE
                      consts
                         None
                      names      ()
                      varnames   ('event',)
                      freevars   ('command',)
                      cellvars   ()
                      filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                      name       '<lambda>'
-                     firstlineno 30
+                     firstlineno 32
                      lnotab 0x
                names      ('super', '__init__', '_other', 'default_palette', 'text', 'button_back', '_button_back', 'button_border', '_button_border', 'button_border_width', '_button_border_width', 'button_text_back', '_button_text_back', 'nametofont', 'button_text_font', 'bind', '_draw', '_click', '_unclick', '_hover', '_hover_release')
                varnames   ('self', 'width', 'height', 'text', 'command', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ('command',)
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '__init__'
                firstlineno 7
                lnotab
-                  0x06013c02280228020e02180118011801180228023a013a013a013a013a
-                  0204013202
+                  0x06013c02280228020e02180118011801180228033a013a013a013a013a
+                  0304013202
             code
                argcount  : 1
                nlocals   : 2
                stacksize : 5
                flags     : 11
                code
                   0x95018700970064017c01760072357c01a0000000000000000000000000
@@ -740,65 +740,65 @@
                   008900a00400000000000000000000000000000000000000006400a60100
                   00ab0100000000000000000100640053000200740b000000000000000000
                   00a6000000ab0000000000000000006a060000000000000000640569007c
                   01a4018e01010064005300
                              0 COPY_FREE_VARS           1
                              2 MAKE_CELL                0 (self)
                
-                34           4 RESUME                   0
+                36           4 RESUME                   0
                
-                35           6 LOAD_CONST               1 ('command')
+                37           6 LOAD_CONST               1 ('command')
                              8 LOAD_FAST                1 (kwargs)
                             10 CONTAINS_OP              0
                             12 POP_JUMP_FORWARD_IF_FALSE    53 (to 120)
                
-                36          14 LOAD_FAST                1 (kwargs)
+                38          14 LOAD_FAST                1 (kwargs)
                             16 LOAD_METHOD              0 (pop)
                             38 LOAD_CONST               1 ('command')
                             40 PRECALL                  1
                             44 CALL                     1
                             54 LOAD_DEREF               0 (self)
                             56 STORE_ATTR               1 (command)
                
-                37          66 LOAD_DEREF               0 (self)
+                39          66 LOAD_DEREF               0 (self)
                             68 LOAD_METHOD              2 (bind)
                             90 LOAD_CONST               2 ('<<Click>>')
                             92 LOAD_CLOSURE             0 (self)
                             94 BUILD_TUPLE              1
-                            96 LOAD_CONST               3 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 37>)
+                            96 LOAD_CONST               3 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\button.py", line 39>)
                             98 MAKE_FUNCTION            8 (closure)
                            100 PRECALL                  2
                            104 CALL                     2
                            114 POP_TOP
                            116 LOAD_CONST               0 (None)
                            118 RETURN_VALUE
                
-                38     >>  120 LOAD_CONST               4 ('text')
+                40     >>  120 LOAD_CONST               4 ('text')
                            122 LOAD_FAST                1 (kwargs)
                            124 CONTAINS_OP              0
                            126 POP_JUMP_FORWARD_IF_FALSE    49 (to 226)
                
-                39         128 LOAD_FAST                1 (kwargs)
+                41         128 LOAD_FAST                1 (kwargs)
                            130 LOAD_METHOD              0 (pop)
                            152 LOAD_CONST               4 ('text')
                            154 PRECALL                  1
                            158 CALL                     1
                            168 LOAD_DEREF               0 (self)
                            170 STORE_ATTR               3 (text)
                
-                40         180 LOAD_DEREF               0 (self)
+                42         180 LOAD_DEREF               0 (self)
                            182 LOAD_METHOD              4 (_draw)
                            204 LOAD_CONST               0 (None)
                            206 PRECALL                  1
                            210 CALL                     1
                            220 POP_TOP
                            222 LOAD_CONST               0 (None)
                            224 RETURN_VALUE
                
-                42     >>  226 PUSH_NULL
+                44     >>  226 PUSH_NULL
                            228 LOAD_GLOBAL             11 (NULL + super)
                            240 PRECALL                  0
                            244 CALL                     0
                            254 LOAD_ATTR                6 (configure)
                            264 LOAD_CONST               5 (())
                            266 BUILD_MAP                0
                            268 LOAD_FAST                1 (kwargs)
@@ -817,240 +817,250 @@
                      stacksize : 2
                      flags     : 19
                      code
                         0x950197008901a0000000000000000000000000000000000000000000a6
                         000000ab0000000000000000005300
                                    0 COPY_FREE_VARS           1
                      
-                      37           2 RESUME                   0
+                      39           2 RESUME                   0
                                    4 LOAD_DEREF               1 (self)
                                    6 LOAD_METHOD              0 (command)
                                   28 PRECALL                  0
                                   32 CALL                     0
                                   42 RETURN_VALUE
                      consts
                         None
                      names      ('command',)
                      varnames   ('event',)
                      freevars   ('self',)
                      cellvars   ()
                      filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                      name       '<lambda>'
-                     firstlineno 37
+                     firstlineno 39
                      lnotab 0x
                   'text'
                   ()
                names      ('pop', 'command', 'bind', 'text', '_draw', 'super', 'configure')
                varnames   ('self', 'kwargs')
                freevars   ('__class__',)
                cellvars   ('self',)
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'configure'
-               firstlineno 34
+               firstlineno 36
                lnotab 0x0601080134013601080134012e02
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 4
                flags     : 3
                code
                   0x97007401000000000000000000007c006401a6020000ab020000000000
                   000000721e7c00a00100000000000000000000000000000000000000007c
                   006a0200000000000000006402ac03a6020000ab02000000000000000001
                   006400530064005300
-                44           0 RESUME                   0
+                46           0 RESUME                   0
                
-                45           2 LOAD_GLOBAL              1 (NULL + hasattr)
+                47           2 LOAD_GLOBAL              1 (NULL + hasattr)
                             14 LOAD_FAST                0 (self)
                             16 LOAD_CONST               1 ('button_frame_back')
                             18 PRECALL                  2
                             22 CALL                     2
                             32 POP_JUMP_FORWARD_IF_FALSE    30 (to 94)
                
-                46          34 LOAD_FAST                0 (self)
+                48          34 LOAD_FAST                0 (self)
                             36 LOAD_METHOD              1 (configure)
                             58 LOAD_FAST                0 (self)
                             60 LOAD_ATTR                2 (button_frame_back)
                             70 LOAD_CONST               2 (0)
                             72 KW_NAMES                 3
                             74 PRECALL                  2
                             78 CALL                     2
                             88 POP_TOP
                             90 LOAD_CONST               0 (None)
                             92 RETURN_VALUE
                
-                45     >>   94 LOAD_CONST               0 (None)
+                47     >>   94 LOAD_CONST               0 (None)
                             96 RETURN_VALUE
                consts
                   None
                   'button_frame_back'
                   0
                   ('background', 'borderwidth')
                names      ('hasattr', 'configure', 'button_frame_back')
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_other'
-               firstlineno 44
+               firstlineno 46
                lnotab 0x020120013cff
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 9
                flags     : 3
                code
                   0x97007c00a00000000000000000000000000000000000000000006401a6
                   010000ab01000000000000000001007c00a0010000000000000000000000
-                  000000000000000000640264027c00a00200000000000000000000000000
-                  00000000000000a6000000ab00000000000000000064037a0a00007c00a0
-                  030000000000000000000000000000000000000000a6000000ab00000000
-                  000000000064037a0a00007c006a0400000000000000007c006a05000000
-                  00000000007c006a060000000000000000ac04a6070000ab070000000000
-                  0000007c005f0700000000000000007c00a0080000000000000000000000
-                  0000000000000000007c00a0020000000000000000000000000000000000
-                  000000a6000000ab00000000000000000064057a0b00007c00a003000000
-                  0000000000000000000000000000000000a6000000ab0000000000000000
-                  0064057a0b00007c006a0900000000000000007c006a0a00000000000000
-                  007c006a0b0000000000000000ac06a6050000ab0500000000000000007c
-                  005f0c000000000000000064005300
-                48           0 RESUME                   0
+                  0000000000000000007c006a0200000000000000007c006a020000000000
+                  0000007c00a0030000000000000000000000000000000000000000a60000
+                  00ab0000000000000000007c006a02000000000000000064027a0500007a
+                  0a00007c00a0040000000000000000000000000000000000000000a60000
+                  00ab0000000000000000007c006a02000000000000000064027a0500007a
+                  0a00007c006a0200000000000000007c006a0500000000000000007c006a
+                  060000000000000000ac03a6070000ab0700000000000000007c005f0700
+                  000000000000007c00a00800000000000000000000000000000000000000
+                  007c00a0030000000000000000000000000000000000000000a6000000ab
+                  00000000000000000064027a0b00007c00a0040000000000000000000000
+                  000000000000000000a6000000ab00000000000000000064027a0b00007c
+                  006a0900000000000000007c006a0a00000000000000007c006a0b000000
+                  0000000000ac04a6050000ab0500000000000000007c005f0c0000000000
+                  00000064005300
+                50           0 RESUME                   0
                
-                49           2 LOAD_FAST                0 (self)
+                51           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-                51          44 LOAD_FAST                0 (self)
+                54          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_rectangle)
                
-                52          68 LOAD_CONST               2 (1.5)
-                            70 LOAD_CONST               2 (1.5)
-                            72 LOAD_FAST                0 (self)
-                            74 LOAD_METHOD              2 (winfo_width)
-                            96 PRECALL                  0
-                           100 CALL                     0
-                           110 LOAD_CONST               3 (3)
-                           112 BINARY_OP               10 (-)
-                           116 LOAD_FAST                0 (self)
-                           118 LOAD_METHOD              3 (winfo_height)
-                           140 PRECALL                  0
-                           144 CALL                     0
-                           154 LOAD_CONST               3 (3)
-                           156 BINARY_OP               10 (-)
-               
-                53         160 LOAD_FAST                0 (self)
-                           162 LOAD_ATTR                4 (_button_border_width)
-               
-                54         172 LOAD_FAST                0 (self)
-                           174 LOAD_ATTR                5 (_button_border)
-                           184 LOAD_FAST                0 (self)
-                           186 LOAD_ATTR                6 (_button_back)
-               
-                51         196 KW_NAMES                 4
-                           198 PRECALL                  7
-                           202 CALL                     7
-                           212 LOAD_FAST                0 (self)
-                           214 STORE_ATTR               7 (button_frame)
-               
-                57         224 LOAD_FAST                0 (self)
-                           226 LOAD_METHOD              8 (create_text)
+                55          68 LOAD_FAST                0 (self)
+                            70 LOAD_ATTR                2 (_button_border_width)
+                            80 LOAD_FAST                0 (self)
+                            82 LOAD_ATTR                2 (_button_border_width)
+               
+                56          92 LOAD_FAST                0 (self)
+                            94 LOAD_METHOD              3 (winfo_width)
+                           116 PRECALL                  0
+                           120 CALL                     0
+                           130 LOAD_FAST                0 (self)
+                           132 LOAD_ATTR                2 (_button_border_width)
+                           142 LOAD_CONST               2 (2)
+                           144 BINARY_OP                5 (*)
+                           148 BINARY_OP               10 (-)
+               
+                57         152 LOAD_FAST                0 (self)
+                           154 LOAD_METHOD              4 (winfo_height)
+                           176 PRECALL                  0
+                           180 CALL                     0
+                           190 LOAD_FAST                0 (self)
+                           192 LOAD_ATTR                2 (_button_border_width)
+                           202 LOAD_CONST               2 (2)
+                           204 BINARY_OP                5 (*)
+                           208 BINARY_OP               10 (-)
+               
+                58         212 LOAD_FAST                0 (self)
+                           214 LOAD_ATTR                2 (_button_border_width)
+               
+                59         224 LOAD_FAST                0 (self)
+                           226 LOAD_ATTR                5 (_button_border)
+                           236 LOAD_FAST                0 (self)
+                           238 LOAD_ATTR                6 (_button_back)
+               
+                54         248 KW_NAMES                 3
+                           250 PRECALL                  7
+                           254 CALL                     7
+                           264 LOAD_FAST                0 (self)
+                           266 STORE_ATTR               7 (button_frame)
+               
+                63         276 LOAD_FAST                0 (self)
+                           278 LOAD_METHOD              8 (create_text)
+               
+                64         300 LOAD_FAST                0 (self)
+                           302 LOAD_METHOD              3 (winfo_width)
+                           324 PRECALL                  0
+                           328 CALL                     0
+                           338 LOAD_CONST               2 (2)
+                           340 BINARY_OP               11 (/)
+                           344 LOAD_FAST                0 (self)
+                           346 LOAD_METHOD              4 (winfo_height)
+                           368 PRECALL                  0
+                           372 CALL                     0
+                           382 LOAD_CONST               2 (2)
+                           384 BINARY_OP               11 (/)
                
-                58         248 LOAD_FAST                0 (self)
-                           250 LOAD_METHOD              2 (winfo_width)
-                           272 PRECALL                  0
-                           276 CALL                     0
-                           286 LOAD_CONST               5 (2)
-                           288 BINARY_OP               11 (/)
-                           292 LOAD_FAST                0 (self)
-                           294 LOAD_METHOD              3 (winfo_height)
-                           316 PRECALL                  0
-                           320 CALL                     0
-                           330 LOAD_CONST               5 (2)
-                           332 BINARY_OP               11 (/)
-               
-                59         336 LOAD_FAST                0 (self)
-                           338 LOAD_ATTR                9 (text)
-                           348 LOAD_FAST                0 (self)
-                           350 LOAD_ATTR               10 (_button_text_back)
+                65         388 LOAD_FAST                0 (self)
+                           390 LOAD_ATTR                9 (text)
+                           400 LOAD_FAST                0 (self)
+                           402 LOAD_ATTR               10 (_button_text_back)
                
-                60         360 LOAD_FAST                0 (self)
-                           362 LOAD_ATTR               11 (button_text_font)
+                66         412 LOAD_FAST                0 (self)
+                           414 LOAD_ATTR               11 (button_text_font)
                
-                57         372 KW_NAMES                 6
-                           374 PRECALL                  5
-                           378 CALL                     5
-                           388 LOAD_FAST                0 (self)
-                           390 STORE_ATTR              12 (button_text)
-                           400 LOAD_CONST               0 (None)
-                           402 RETURN_VALUE
+                63         424 KW_NAMES                 4
+                           426 PRECALL                  5
+                           430 CALL                     5
+                           440 LOAD_FAST                0 (self)
+                           442 STORE_ATTR              12 (button_text)
+                           452 LOAD_CONST               0 (None)
+                           454 RETURN_VALUE
                consts
                   None
                   'all'
-                  1.5
-                  3
-                  ('width', 'outline', 'fill')
                   2
+                  ('width', 'outline', 'fill')
                   ('text', 'fill', 'font')
-               names      ('delete', 'create_rectangle', 'winfo_width', 'winfo_height', '_button_border_width', '_button_border', '_button_back', 'button_frame', 'create_text', 'text', '_button_text_back', 'button_text_font', 'button_text')
+               names      ('delete', 'create_rectangle', '_button_border_width', 'winfo_width', 'winfo_height', '_button_border', '_button_back', 'button_frame', 'create_text', 'text', '_button_text_back', 'button_text_font', 'button_text')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_draw'
-               firstlineno 48
-               lnotab 0x02012a0218015c010c0118fd1c061801580118010cfd
+               firstlineno 50
+               lnotab 0x02012a03180118013c013c010c0118fb1c091801580118010cfd
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x970064017c005f0000000000000000007c006a0100000000000000007c
                   005f0200000000000000007c006a0300000000000000007c005f04000000
                   00000000007c006a0500000000000000007c005f0600000000000000007c
                   006a0700000000000000007c005f0800000000000000007c00a009000000
                   0000000000000000000000000000000000a6000000ab0000000000000000
                   0001007c00a00a00000000000000000000000000000000000000006400a6
                   010000ab010000000000000000010064005300
-                63           0 RESUME                   0
+                69           0 RESUME                   0
                
-                64           2 LOAD_CONST               1 (True)
+                70           2 LOAD_CONST               1 (True)
                              4 LOAD_FAST                0 (self)
                              6 STORE_ATTR               0 (hover)
                
-                65          16 LOAD_FAST                0 (self)
+                71          16 LOAD_FAST                0 (self)
                             18 LOAD_ATTR                1 (button_pressed_back)
                             28 LOAD_FAST                0 (self)
                             30 STORE_ATTR               2 (_button_back)
                
-                66          40 LOAD_FAST                0 (self)
+                72          40 LOAD_FAST                0 (self)
                             42 LOAD_ATTR                3 (button_pressed_border)
                             52 LOAD_FAST                0 (self)
                             54 STORE_ATTR               4 (_button_border)
                
-                67          64 LOAD_FAST                0 (self)
+                73          64 LOAD_FAST                0 (self)
                             66 LOAD_ATTR                5 (button_pressed_border_width)
                             76 LOAD_FAST                0 (self)
                             78 STORE_ATTR               6 (_button_border_width)
                
-                68          88 LOAD_FAST                0 (self)
+                74          88 LOAD_FAST                0 (self)
                             90 LOAD_ATTR                7 (button_pressed_text_back)
                            100 LOAD_FAST                0 (self)
                            102 STORE_ATTR               8 (_button_text_back)
                
-                70         112 LOAD_FAST                0 (self)
+                76         112 LOAD_FAST                0 (self)
                            114 LOAD_METHOD              9 (focus_set)
                            136 PRECALL                  0
                            140 CALL                     0
                            150 POP_TOP
                
-                72         152 LOAD_FAST                0 (self)
+                78         152 LOAD_FAST                0 (self)
                            154 LOAD_METHOD             10 (_draw)
                            176 LOAD_CONST               0 (None)
                            178 PRECALL                  1
                            182 CALL                     1
                            192 POP_TOP
                            194 LOAD_CONST               0 (None)
                            196 RETURN_VALUE
@@ -1059,123 +1069,123 @@
                   True
                names      ('hover', 'button_pressed_back', '_button_back', 'button_pressed_border', '_button_border', 'button_pressed_border_width', '_button_border_width', 'button_pressed_text_back', '_button_text_back', 'focus_set', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_click'
-               firstlineno 63
+               firstlineno 69
                lnotab 0x02010e0118011801180118022802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a000000000000000000725c7c006a0100000000000000007c
                   005f0200000000000000007c006a0300000000000000007c005f04000000
                   00000000007c006a0500000000000000007c005f0600000000000000007c
                   006a0700000000000000007c005f0800000000000000007c00a009000000
                   00000000000000000000000000000000006400a6010000ab010000000000
                   00000001007c00a00a000000000000000000000000000000000000000064
                   01a6010000ab01000000000000000001006400530064005300
-                74           0 RESUME                   0
+                80           0 RESUME                   0
                
-                75           2 LOAD_FAST                0 (self)
+                81           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (hover)
                             14 POP_JUMP_FORWARD_IF_FALSE    92 (to 200)
                
-                76          16 LOAD_FAST                0 (self)
+                82          16 LOAD_FAST                0 (self)
                             18 LOAD_ATTR                1 (button_active_back)
                             28 LOAD_FAST                0 (self)
                             30 STORE_ATTR               2 (_button_back)
                
-                77          40 LOAD_FAST                0 (self)
+                83          40 LOAD_FAST                0 (self)
                             42 LOAD_ATTR                3 (button_active_border)
                             52 LOAD_FAST                0 (self)
                             54 STORE_ATTR               4 (_button_border)
                
-                78          64 LOAD_FAST                0 (self)
+                84          64 LOAD_FAST                0 (self)
                             66 LOAD_ATTR                5 (button_active_border_width)
                             76 LOAD_FAST                0 (self)
                             78 STORE_ATTR               6 (_button_border_width)
                
-                79          88 LOAD_FAST                0 (self)
+                85          88 LOAD_FAST                0 (self)
                             90 LOAD_ATTR                7 (button_active_text_back)
                            100 LOAD_FAST                0 (self)
                            102 STORE_ATTR               8 (_button_text_back)
                
-                81         112 LOAD_FAST                0 (self)
+                87         112 LOAD_FAST                0 (self)
                            114 LOAD_METHOD              9 (_draw)
                            136 LOAD_CONST               0 (None)
                            138 PRECALL                  1
                            142 CALL                     1
                            152 POP_TOP
                
-                83         154 LOAD_FAST                0 (self)
+                89         154 LOAD_FAST                0 (self)
                            156 LOAD_METHOD             10 (event_generate)
                            178 LOAD_CONST               1 ('<<Click>>')
                            180 PRECALL                  1
                            184 CALL                     1
                            194 POP_TOP
                            196 LOAD_CONST               0 (None)
                            198 RETURN_VALUE
                
-                75     >>  200 LOAD_CONST               0 (None)
+                81     >>  200 LOAD_CONST               0 (None)
                            202 RETURN_VALUE
                consts
                   None
                   '<<Click>>'
                names      ('hover', 'button_active_back', '_button_back', 'button_active_border', '_button_border', 'button_active_border_width', '_button_border_width', 'button_active_text_back', '_button_text_back', '_draw', 'event_generate')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_unclick'
-               firstlineno 74
+               firstlineno 80
                lnotab 0x02010e0118011801180118022a022ef8
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x970064017c005f0000000000000000007c006a0100000000000000007c
                   005f0200000000000000007c006a0300000000000000007c005f04000000
                   00000000007c006a0500000000000000007c005f0600000000000000007c
                   006a0700000000000000007c005f0800000000000000007c00a009000000
                   00000000000000000000000000000000006400a6010000ab010000000000
                   000000010064005300
-                85           0 RESUME                   0
+                91           0 RESUME                   0
                
-                86           2 LOAD_CONST               1 (True)
+                92           2 LOAD_CONST               1 (True)
                              4 LOAD_FAST                0 (self)
                              6 STORE_ATTR               0 (hover)
                
-                87          16 LOAD_FAST                0 (self)
+                93          16 LOAD_FAST                0 (self)
                             18 LOAD_ATTR                1 (button_active_back)
                             28 LOAD_FAST                0 (self)
                             30 STORE_ATTR               2 (_button_back)
                
-                88          40 LOAD_FAST                0 (self)
+                94          40 LOAD_FAST                0 (self)
                             42 LOAD_ATTR                3 (button_active_border)
                             52 LOAD_FAST                0 (self)
                             54 STORE_ATTR               4 (_button_border)
                
-                89          64 LOAD_FAST                0 (self)
+                95          64 LOAD_FAST                0 (self)
                             66 LOAD_ATTR                5 (button_active_border_width)
                             76 LOAD_FAST                0 (self)
                             78 STORE_ATTR               6 (_button_border_width)
                
-                90          88 LOAD_FAST                0 (self)
+                96          88 LOAD_FAST                0 (self)
                             90 LOAD_ATTR                7 (button_active_text_back)
                            100 LOAD_FAST                0 (self)
                            102 STORE_ATTR               8 (_button_text_back)
                
-                92         112 LOAD_FAST                0 (self)
+                98         112 LOAD_FAST                0 (self)
                            114 LOAD_METHOD              9 (_draw)
                            136 LOAD_CONST               0 (None)
                            138 PRECALL                  1
                            142 CALL                     1
                            152 POP_TOP
                            154 LOAD_CONST               0 (None)
                            156 RETURN_VALUE
@@ -1184,55 +1194,55 @@
                   True
                names      ('hover', 'button_active_back', '_button_back', 'button_active_border', '_button_border', 'button_active_border_width', '_button_border_width', 'button_active_text_back', '_button_text_back', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_hover'
-               firstlineno 85
+               firstlineno 91
                lnotab 0x02010e011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x970064017c005f0000000000000000007c006a0100000000000000007c
                   005f0200000000000000007c006a0300000000000000007c005f04000000
                   00000000007c006a0500000000000000007c005f0600000000000000007c
                   006a0700000000000000007c005f0800000000000000007c00a009000000
                   00000000000000000000000000000000006400a6010000ab010000000000
                   000000010064005300
-                94           0 RESUME                   0
+               100           0 RESUME                   0
                
-                95           2 LOAD_CONST               1 (False)
+               101           2 LOAD_CONST               1 (False)
                              4 LOAD_FAST                0 (self)
                              6 STORE_ATTR               0 (hover)
                
-                96          16 LOAD_FAST                0 (self)
+               102          16 LOAD_FAST                0 (self)
                             18 LOAD_ATTR                1 (button_back)
                             28 LOAD_FAST                0 (self)
                             30 STORE_ATTR               2 (_button_back)
                
-                97          40 LOAD_FAST                0 (self)
+               103          40 LOAD_FAST                0 (self)
                             42 LOAD_ATTR                3 (button_border)
                             52 LOAD_FAST                0 (self)
                             54 STORE_ATTR               4 (_button_border)
                
-                98          64 LOAD_FAST                0 (self)
+               104          64 LOAD_FAST                0 (self)
                             66 LOAD_ATTR                5 (button_border_width)
                             76 LOAD_FAST                0 (self)
                             78 STORE_ATTR               6 (_button_border_width)
                
-                99          88 LOAD_FAST                0 (self)
+               105          88 LOAD_FAST                0 (self)
                             90 LOAD_ATTR                7 (button_text_back)
                            100 LOAD_FAST                0 (self)
                            102 STORE_ATTR               8 (_button_text_back)
                
-               101         112 LOAD_FAST                0 (self)
+               107         112 LOAD_FAST                0 (self)
                            114 LOAD_METHOD              9 (_draw)
                            136 LOAD_CONST               0 (None)
                            138 PRECALL                  1
                            142 CALL                     1
                            152 POP_TOP
                            154 LOAD_CONST               0 (None)
                            156 RETURN_VALUE
@@ -1241,128 +1251,128 @@
                   False
                names      ('hover', 'button_back', '_button_back', 'button_border', '_button_border', 'button_border_width', '_button_border_width', 'button_text_back', '_button_text_back', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_hover_release'
-               firstlineno 94
+               firstlineno 100
                lnotab 0x02010e011801180118011802
             'font'
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               103           0 RESUME                   0
+               109           0 RESUME                   0
                
-               104           2 LOAD_FAST                1 (font)
+               110           2 LOAD_FAST                1 (font)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               105           6 LOAD_FAST                0 (self)
+               111           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (button_text_font)
                             18 RETURN_VALUE
                
-               107     >>   20 LOAD_FAST                1 (font)
+               113     >>   20 LOAD_FAST                1 (font)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (button_text_font)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('button_text_font',)
                varnames   ('self', 'font')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'font'
-               firstlineno 103
+               firstlineno 109
                lnotab 0x020104010e02
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               109           0 RESUME                   0
+               115           0 RESUME                   0
                
-               110           2 LOAD_FAST                0 (self)
+               116           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 109
+               firstlineno 115
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 13
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   02640364046405640664076408640564099c046406640a640b640564099c
                   04640c9c066901a6010000ab010000000000000000010064005300
-               112           0 RESUME                   0
+               118           0 RESUME                   0
                
-               113           2 LOAD_FAST                0 (self)
+               119           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               115          26 LOAD_CONST               1 ('button')
+               121          26 LOAD_CONST               1 ('button')
                
-               116          28 LOAD_CONST               2 ('#fdfdfd')
+               122          28 LOAD_CONST               2 ('#fdfdfd')
                
-               117          30 LOAD_CONST               3 ('#eaeaea')
+               123          30 LOAD_CONST               3 ('#eaeaea')
                
-               118          32 LOAD_CONST               4 ('#1a1a1a')
+               124          32 LOAD_CONST               4 ('#1a1a1a')
                
-               119          34 LOAD_CONST               5 (1)
+               125          34 LOAD_CONST               5 (1)
                
-               122          36 LOAD_CONST               6 ('#f9f9f9')
+               128          36 LOAD_CONST               6 ('#f9f9f9')
                
-               123          38 LOAD_CONST               7 ('#aaaaaa')
+               129          38 LOAD_CONST               7 ('#aaaaaa')
                
-               124          40 LOAD_CONST               8 ('#5f5f5f')
+               130          40 LOAD_CONST               8 ('#5f5f5f')
                
-               125          42 LOAD_CONST               5 (1)
+               131          42 LOAD_CONST               5 (1)
                
-               121          44 LOAD_CONST               9 (('back', 'border', 'text_back', 'border_width'))
+               127          44 LOAD_CONST               9 (('back', 'border', 'text_back', 'border_width'))
                             46 BUILD_CONST_KEY_MAP      4
                
-               129          48 LOAD_CONST               6 ('#f9f9f9')
+               135          48 LOAD_CONST               6 ('#f9f9f9')
                
-               130          50 LOAD_CONST              10 ('#e2e2e2')
+               136          50 LOAD_CONST              10 ('#e2e2e2')
                
-               131          52 LOAD_CONST              11 ('#8a8a8a')
+               137          52 LOAD_CONST              11 ('#8a8a8a')
                
-               132          54 LOAD_CONST               5 (1)
+               138          54 LOAD_CONST               5 (1)
                
-               128          56 LOAD_CONST               9 (('back', 'border', 'text_back', 'border_width'))
+               134          56 LOAD_CONST               9 (('back', 'border', 'text_back', 'border_width'))
                             58 BUILD_CONST_KEY_MAP      4
                
-               115          60 LOAD_CONST              12 (('back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
+               121          60 LOAD_CONST              12 (('back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
                             62 BUILD_CONST_KEY_MAP      6
                
-               114          64 BUILD_MAP                1
+               120          64 BUILD_MAP                1
                
-               113          66 PRECALL                  1
+               119          66 PRECALL                  1
                             70 CALL                     1
                             80 POP_TOP
                             82 LOAD_CONST               0 (None)
                             84 RETURN_VALUE
                consts
                   None
                   'button'
@@ -1379,70 +1389,70 @@
                   ('back', 'border', 'text_back', 'border_width', 'active', 'pressed')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'palette_light'
-               firstlineno 112
+               firstlineno 118
                lnotab
                   0x020118020201020102010201020302010201020102fc04080201020102
                   0102fc04f304ff02ff
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 13
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   02640364046405640664036407640564089c0464096403640a640564089c
                   04640b9c066901a6010000ab010000000000000000010064005300
-               138           0 RESUME                   0
+               144           0 RESUME                   0
                
-               139           2 LOAD_FAST                0 (self)
+               145           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               141          26 LOAD_CONST               1 ('button')
+               147          26 LOAD_CONST               1 ('button')
                
-               142          28 LOAD_CONST               2 ('#353535')
+               148          28 LOAD_CONST               2 ('#353535')
                
-               143          30 LOAD_CONST               3 ('#454545')
+               149          30 LOAD_CONST               3 ('#454545')
                
-               144          32 LOAD_CONST               4 ('#ffffff')
+               150          32 LOAD_CONST               4 ('#ffffff')
                
-               145          34 LOAD_CONST               5 (1)
+               151          34 LOAD_CONST               5 (1)
                
-               148          36 LOAD_CONST               6 ('#3a3a3a')
+               154          36 LOAD_CONST               6 ('#3a3a3a')
                
-               149          38 LOAD_CONST               3 ('#454545')
+               155          38 LOAD_CONST               3 ('#454545')
                
-               150          40 LOAD_CONST               7 ('#cecece')
+               156          40 LOAD_CONST               7 ('#cecece')
                
-               151          42 LOAD_CONST               5 (1)
+               157          42 LOAD_CONST               5 (1)
                
-               147          44 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
+               153          44 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
                             46 BUILD_CONST_KEY_MAP      4
                
-               155          48 LOAD_CONST               9 ('#2f2f2f')
+               161          48 LOAD_CONST               9 ('#2f2f2f')
                
-               156          50 LOAD_CONST               3 ('#454545')
+               162          50 LOAD_CONST               3 ('#454545')
                
-               157          52 LOAD_CONST              10 ('#9a9a9a')
+               163          52 LOAD_CONST              10 ('#9a9a9a')
                
-               158          54 LOAD_CONST               5 (1)
+               164          54 LOAD_CONST               5 (1)
                
-               154          56 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
+               160          56 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
                             58 BUILD_CONST_KEY_MAP      4
                
-               141          60 LOAD_CONST              11 (('back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
+               147          60 LOAD_CONST              11 (('back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
                             62 BUILD_CONST_KEY_MAP      6
                
-               140          64 BUILD_MAP                1
+               146          64 BUILD_MAP                1
                
-               139          66 PRECALL                  1
+               145          66 PRECALL                  1
                             70 CALL                     1
                             80 POP_TOP
                             82 LOAD_CONST               0 (None)
                             84 RETURN_VALUE
                consts
                   None
                   'button'
@@ -1458,25 +1468,25 @@
                   ('back', 'border', 'text_back', 'border_width', 'active', 'pressed')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'palette_dark'
-               firstlineno 138
+               firstlineno 144
                lnotab
                   0x020118020201020102010201020302010201020102fc04080201020102
                   0102fc04f304ff02ff
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 4
                flags     : 3
                code
-                  0x97007c019001815d64017c017600900172287c01640119000000000000
+                  0x97007c019001818d64017c017600900172287c01640119000000000000
                   0000006402190000000000000000007c005f0000000000000000007c0164
                   01190000000000000000006403190000000000000000007c005f01000000
                   00000000007c016401190000000000000000006404190000000000000000
                   007c005f0200000000000000007c01640119000000000000000000640519
                   0000000000000000007c005f03000000000000000064067c016401190000
                   00000000000000760072647c016401190000000000000000006406190000
                   000000000000006402190000000000000000007c005f0400000000000000
@@ -1488,348 +1498,371 @@
                   0064077c01640119000000000000000000760072647c0164011900000000
                   00000000006407190000000000000000006402190000000000000000007c
                   005f0800000000000000007c016401190000000000000000006407190000
                   000000000000006403190000000000000000007c005f0900000000000000
                   007c01640119000000000000000000640719000000000000000000640419
                   0000000000000000007c005f0a00000000000000007c0164011900000000
                   00000000006407190000000000000000006405190000000000000000007c
-                  005f0b00000000000000007c017c005f0c000000000000000009007c00a0
-                  0d00000000000000000000000000000000000000006400a6010000ab0100
-                  000000000000000100640053002300741c00000000000000000000240072
-                  04010059006400530077007803590077017c006a0c000000000000000053
-                  00
-               164           0 RESUME                   0
+                  005f0b00000000000000007c017c005f0c00000000000000007c006a0000
+                  000000000000007c005f0d00000000000000007c006a0100000000000000
+                  007c005f0e00000000000000007c006a0300000000000000007c005f0f00
+                  000000000000007c006a0200000000000000007c005f1000000000000000
+                  0009007c00a01100000000000000000000000000000000000000006400a6
+                  010000ab0100000000000000000100640053002300742400000000000000
+                  00000024007204010059006400530077007803590077017c006a0c000000
+                  00000000005300
+               170           0 RESUME                   0
                
-               165           2 LOAD_FAST                1 (dict)
+               171           2 LOAD_FAST                1 (dict)
                              4 EXTENDED_ARG             1
-                             6 POP_JUMP_FORWARD_IF_NONE   349 (to 706)
+                             6 POP_JUMP_FORWARD_IF_NONE   397 (to 802)
                
-               166           8 LOAD_CONST               1 ('button')
+               172           8 LOAD_CONST               1 ('button')
                             10 LOAD_FAST                1 (dict)
                             12 CONTAINS_OP              0
                             14 EXTENDED_ARG             1
                             16 POP_JUMP_FORWARD_IF_FALSE   296 (to 610)
                
-               167          18 LOAD_FAST                1 (dict)
+               173          18 LOAD_FAST                1 (dict)
                             20 LOAD_CONST               1 ('button')
                             22 BINARY_SUBSCR
                             32 LOAD_CONST               2 ('back')
                             34 BINARY_SUBSCR
                             44 LOAD_FAST                0 (self)
                             46 STORE_ATTR               0 (button_back)
                
-               168          56 LOAD_FAST                1 (dict)
+               174          56 LOAD_FAST                1 (dict)
                             58 LOAD_CONST               1 ('button')
                             60 BINARY_SUBSCR
                             70 LOAD_CONST               3 ('border')
                             72 BINARY_SUBSCR
                             82 LOAD_FAST                0 (self)
                             84 STORE_ATTR               1 (button_border)
                
-               169          94 LOAD_FAST                1 (dict)
+               175          94 LOAD_FAST                1 (dict)
                             96 LOAD_CONST               1 ('button')
                             98 BINARY_SUBSCR
                            108 LOAD_CONST               4 ('text_back')
                            110 BINARY_SUBSCR
                            120 LOAD_FAST                0 (self)
                            122 STORE_ATTR               2 (button_text_back)
                
-               170         132 LOAD_FAST                1 (dict)
+               176         132 LOAD_FAST                1 (dict)
                            134 LOAD_CONST               1 ('button')
                            136 BINARY_SUBSCR
                            146 LOAD_CONST               5 ('border_width')
                            148 BINARY_SUBSCR
                            158 LOAD_FAST                0 (self)
                            160 STORE_ATTR               3 (button_border_width)
                
-               172         170 LOAD_CONST               6 ('active')
+               178         170 LOAD_CONST               6 ('active')
                            172 LOAD_FAST                1 (dict)
                            174 LOAD_CONST               1 ('button')
                            176 BINARY_SUBSCR
                            186 CONTAINS_OP              0
                            188 POP_JUMP_FORWARD_IF_FALSE   100 (to 390)
                
-               173         190 LOAD_FAST                1 (dict)
+               179         190 LOAD_FAST                1 (dict)
                            192 LOAD_CONST               1 ('button')
                            194 BINARY_SUBSCR
                            204 LOAD_CONST               6 ('active')
                            206 BINARY_SUBSCR
                            216 LOAD_CONST               2 ('back')
                            218 BINARY_SUBSCR
                            228 LOAD_FAST                0 (self)
                            230 STORE_ATTR               4 (button_active_back)
                
-               174         240 LOAD_FAST                1 (dict)
+               180         240 LOAD_FAST                1 (dict)
                            242 LOAD_CONST               1 ('button')
                            244 BINARY_SUBSCR
                            254 LOAD_CONST               6 ('active')
                            256 BINARY_SUBSCR
                            266 LOAD_CONST               3 ('border')
                            268 BINARY_SUBSCR
                            278 LOAD_FAST                0 (self)
                            280 STORE_ATTR               5 (button_active_border)
                
-               175         290 LOAD_FAST                1 (dict)
+               181         290 LOAD_FAST                1 (dict)
                            292 LOAD_CONST               1 ('button')
                            294 BINARY_SUBSCR
                            304 LOAD_CONST               6 ('active')
                            306 BINARY_SUBSCR
                            316 LOAD_CONST               4 ('text_back')
                            318 BINARY_SUBSCR
                            328 LOAD_FAST                0 (self)
                            330 STORE_ATTR               6 (button_active_text_back)
                
-               176         340 LOAD_FAST                1 (dict)
+               182         340 LOAD_FAST                1 (dict)
                            342 LOAD_CONST               1 ('button')
                            344 BINARY_SUBSCR
                            354 LOAD_CONST               6 ('active')
                            356 BINARY_SUBSCR
                            366 LOAD_CONST               5 ('border_width')
                            368 BINARY_SUBSCR
                            378 LOAD_FAST                0 (self)
                            380 STORE_ATTR               7 (button_active_border_width)
                
-               178     >>  390 LOAD_CONST               7 ('pressed')
+               184     >>  390 LOAD_CONST               7 ('pressed')
                            392 LOAD_FAST                1 (dict)
                            394 LOAD_CONST               1 ('button')
                            396 BINARY_SUBSCR
                            406 CONTAINS_OP              0
                            408 POP_JUMP_FORWARD_IF_FALSE   100 (to 610)
                
-               179         410 LOAD_FAST                1 (dict)
+               185         410 LOAD_FAST                1 (dict)
                            412 LOAD_CONST               1 ('button')
                            414 BINARY_SUBSCR
                            424 LOAD_CONST               7 ('pressed')
                            426 BINARY_SUBSCR
                            436 LOAD_CONST               2 ('back')
                            438 BINARY_SUBSCR
                            448 LOAD_FAST                0 (self)
                            450 STORE_ATTR               8 (button_pressed_back)
                
-               180         460 LOAD_FAST                1 (dict)
+               186         460 LOAD_FAST                1 (dict)
                            462 LOAD_CONST               1 ('button')
                            464 BINARY_SUBSCR
                            474 LOAD_CONST               7 ('pressed')
                            476 BINARY_SUBSCR
                            486 LOAD_CONST               3 ('border')
                            488 BINARY_SUBSCR
                            498 LOAD_FAST                0 (self)
                            500 STORE_ATTR               9 (button_pressed_border)
                
-               181         510 LOAD_FAST                1 (dict)
+               187         510 LOAD_FAST                1 (dict)
                            512 LOAD_CONST               1 ('button')
                            514 BINARY_SUBSCR
                            524 LOAD_CONST               7 ('pressed')
                            526 BINARY_SUBSCR
                            536 LOAD_CONST               4 ('text_back')
                            538 BINARY_SUBSCR
                            548 LOAD_FAST                0 (self)
                            550 STORE_ATTR              10 (button_pressed_text_back)
                
-               182         560 LOAD_FAST                1 (dict)
+               188         560 LOAD_FAST                1 (dict)
                            562 LOAD_CONST               1 ('button')
                            564 BINARY_SUBSCR
                            574 LOAD_CONST               7 ('pressed')
                            576 BINARY_SUBSCR
                            586 LOAD_CONST               5 ('border_width')
                            588 BINARY_SUBSCR
                            598 LOAD_FAST                0 (self)
                            600 STORE_ATTR              11 (button_pressed_border_width)
                
-               184     >>  610 LOAD_FAST                1 (dict)
+               190     >>  610 LOAD_FAST                1 (dict)
                            612 LOAD_FAST                0 (self)
                            614 STORE_ATTR              12 (_palette)
                
-               186         624 NOP
-               
-               187         626 LOAD_FAST                0 (self)
-                           628 LOAD_METHOD             13 (_draw)
-                           650 LOAD_CONST               0 (None)
-                           652 PRECALL                  1
-                           656 CALL                     1
-                           666 POP_TOP
-                           668 LOAD_CONST               0 (None)
-                           670 RETURN_VALUE
-                       >>  672 PUSH_EXC_INFO
-               
-               188         674 LOAD_GLOBAL             28 (AttributeError)
-                           686 CHECK_EXC_MATCH
-                           688 POP_JUMP_FORWARD_IF_FALSE     4 (to 698)
-                           690 POP_TOP
-               
-               189         692 POP_EXCEPT
-                           694 LOAD_CONST               0 (None)
-                           696 RETURN_VALUE
-               
-               188     >>  698 RERAISE                  0
-                       >>  700 COPY                     3
-                           702 POP_EXCEPT
-                           704 RERAISE                  1
-               
-               191     >>  706 LOAD_FAST                0 (self)
-                           708 LOAD_ATTR               12 (_palette)
-                           718 RETURN_VALUE
+               192         624 LOAD_FAST                0 (self)
+                           626 LOAD_ATTR                0 (button_back)
+                           636 LOAD_FAST                0 (self)
+                           638 STORE_ATTR              13 (_button_back)
+               
+               193         648 LOAD_FAST                0 (self)
+                           650 LOAD_ATTR                1 (button_border)
+                           660 LOAD_FAST                0 (self)
+                           662 STORE_ATTR              14 (_button_border)
+               
+               194         672 LOAD_FAST                0 (self)
+                           674 LOAD_ATTR                3 (button_border_width)
+                           684 LOAD_FAST                0 (self)
+                           686 STORE_ATTR              15 (_button_border_width)
+               
+               195         696 LOAD_FAST                0 (self)
+                           698 LOAD_ATTR                2 (button_text_back)
+                           708 LOAD_FAST                0 (self)
+                           710 STORE_ATTR              16 (_button_text_back)
+               
+               197         720 NOP
+               
+               198         722 LOAD_FAST                0 (self)
+                           724 LOAD_METHOD             17 (_draw)
+                           746 LOAD_CONST               0 (None)
+                           748 PRECALL                  1
+                           752 CALL                     1
+                           762 POP_TOP
+                           764 LOAD_CONST               0 (None)
+                           766 RETURN_VALUE
+                       >>  768 PUSH_EXC_INFO
+               
+               199         770 LOAD_GLOBAL             36 (AttributeError)
+                           782 CHECK_EXC_MATCH
+                           784 POP_JUMP_FORWARD_IF_FALSE     4 (to 794)
+                           786 POP_TOP
+               
+               200         788 POP_EXCEPT
+                           790 LOAD_CONST               0 (None)
+                           792 RETURN_VALUE
+               
+               199     >>  794 RERAISE                  0
+                       >>  796 COPY                     3
+                           798 POP_EXCEPT
+                           800 RERAISE                  1
+               
+               202     >>  802 LOAD_FAST                0 (self)
+                           804 LOAD_ATTR               12 (_palette)
+                           814 RETURN_VALUE
                ExceptionTable:
-                 626 to 666 -> 672 [0]
-                 672 to 690 -> 700 [1] lasti
-                 698 to 698 -> 700 [1] lasti
+                 722 to 762 -> 768 [0]
+                 768 to 786 -> 796 [1] lasti
+                 794 to 794 -> 796 [1] lasti
                consts
                   None
                   'button'
                   'back'
                   'border'
                   'text_back'
                   'border_width'
                   'active'
                   'pressed'
-               names      ('button_back', 'button_border', 'button_text_back', 'button_border_width', 'button_active_back', 'button_active_border', 'button_active_text_back', 'button_active_border_width', 'button_pressed_back', 'button_pressed_border', 'button_pressed_text_back', 'button_pressed_border_width', '_palette', '_draw', 'AttributeError')
+               names      ('button_back', 'button_border', 'button_text_back', 'button_border_width', 'button_active_back', 'button_active_border', 'button_active_text_back', 'button_active_border_width', 'button_pressed_back', 'button_pressed_border', 'button_pressed_text_back', 'button_pressed_border_width', '_palette', '_button_back', '_button_border', '_button_border_width', '_button_text_back', '_draw', 'AttributeError')
                varnames   ('self', 'dict')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'palette'
-               firstlineno 164
+               firstlineno 170
                lnotab
                   0x020106010a012601260126012602140132013201320132021401320132
-                  01320132020e0202013001120106ff0803
+                  01320132020e02180118011801180202013001120106ff0803
             (None,)
          names      ('__name__', '__module__', '__qualname__', 'str', '__init__', 'configure', '_other', '_draw', '_click', '_unclick', '_hover', '_hover_release', 'Font', 'font', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawBasicButton'
          firstlineno 6
-         lnotab 0x0c011c1b0a0a0604060f080b080b080908090e060603061a061a
+         lnotab 0x0c011c1d0a0a06040613080b080b080908090e060603061a061a
       'AdwDrawBasicButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         194           0 RESUME                   0
+         205           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawButton')
                        8 STORE_NAME               2 (__qualname__)
          
-         195          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 195>)
+         206          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 206>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawButton'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               195           0 RESUME                   0
+               206           0 RESUME                   0
                
-               196           2 LOAD_FAST                0 (self)
+               207           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 195
+               firstlineno 206
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawButton'
-         firstlineno 194
+         firstlineno 205
          lnotab 0x0a01
       'AdwDrawButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         199           0 RESUME                   0
+         210           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawDarkButton')
                        8 STORE_NAME               2 (__qualname__)
          
-         200          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 200>)
+         211          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 211>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawDarkButton'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               200           0 RESUME                   0
+               211           0 RESUME                   0
                
-               201           2 LOAD_FAST                0 (self)
+               212           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 200
+               firstlineno 211
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawDarkButton'
-         firstlineno 199
+         firstlineno 210
          lnotab 0x0a01
       'AdwDrawDarkButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         204           0 RESUME                   0
+         215           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawAccentButton')
                        8 STORE_NAME               2 (__qualname__)
          
-         205          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 205>)
+         216          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 216>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawAccentButton'
             code
@@ -1837,57 +1870,57 @@
                nlocals   : 1
                stacksize : 13
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   02640364046405640664036404640564079c04640864086409640564079c
                   04640a9c066901a6010000ab010000000000000000010064005300
-               205           0 RESUME                   0
+               216           0 RESUME                   0
                
-               206           2 LOAD_FAST                0 (self)
+               217           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               208          26 LOAD_CONST               1 ('button')
+               219          26 LOAD_CONST               1 ('button')
                
-               209          28 LOAD_CONST               2 ('#0067c0')
+               220          28 LOAD_CONST               2 ('#0067c0')
                
-               210          30 LOAD_CONST               3 ('#1473c5')
+               221          30 LOAD_CONST               3 ('#1473c5')
                
-               211          32 LOAD_CONST               4 ('#ffffff')
+               222          32 LOAD_CONST               4 ('#ffffff')
                
-               212          34 LOAD_CONST               5 (1)
+               223          34 LOAD_CONST               5 (1)
                
-               215          36 LOAD_CONST               6 ('#1975c5')
+               226          36 LOAD_CONST               6 ('#1975c5')
                
-               216          38 LOAD_CONST               3 ('#1473c5')
+               227          38 LOAD_CONST               3 ('#1473c5')
                
-               217          40 LOAD_CONST               4 ('#ffffff')
+               228          40 LOAD_CONST               4 ('#ffffff')
                
-               218          42 LOAD_CONST               5 (1)
+               229          42 LOAD_CONST               5 (1)
                
-               214          44 LOAD_CONST               7 (('back', 'border', 'text_back', 'border_width'))
+               225          44 LOAD_CONST               7 (('back', 'border', 'text_back', 'border_width'))
                             46 BUILD_CONST_KEY_MAP      4
                
-               222          48 LOAD_CONST               8 ('#3284cb')
+               233          48 LOAD_CONST               8 ('#3284cb')
                
-               223          50 LOAD_CONST               8 ('#3284cb')
+               234          50 LOAD_CONST               8 ('#3284cb')
                
-               224          52 LOAD_CONST               9 ('#fdfdfd')
+               235          52 LOAD_CONST               9 ('#fdfdfd')
                
-               225          54 LOAD_CONST               5 (1)
+               236          54 LOAD_CONST               5 (1)
                
-               221          56 LOAD_CONST               7 (('back', 'border', 'text_back', 'border_width'))
+               232          56 LOAD_CONST               7 (('back', 'border', 'text_back', 'border_width'))
                             58 BUILD_CONST_KEY_MAP      4
                
-               208          60 LOAD_CONST              10 (('back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
+               219          60 LOAD_CONST              10 (('back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
                             62 BUILD_CONST_KEY_MAP      6
                
-               207          64 BUILD_MAP                1
+               218          64 BUILD_MAP                1
                
-               206          66 PRECALL                  1
+               217          66 PRECALL                  1
                             70 CALL                     1
                             80 POP_TOP
                             82 LOAD_CONST               0 (None)
                             84 RETURN_VALUE
                consts
                   None
                   'button'
@@ -1902,75 +1935,75 @@
                   ('back', 'border', 'text_back', 'border_width', 'active', 'pressed')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 205
+               firstlineno 216
                lnotab
                   0x020118020201020102010201020302010201020102fc04080201020102
                   0102fc04f304ff02ff
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawAccentButton'
-         firstlineno 204
+         firstlineno 215
          lnotab 0x0a01
       'AdwDrawAccentButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 3
          flags     : 0
          code
             0x8700970065005a0164005a0288006601640184085a03640284005a0464
             0384005a05640484005a06640584005a07640684005a0864098800660164
             0884095a09880078015a0a5300
                        0 MAKE_CELL                0 (__class__)
          
-         233           2 RESUME                   0
+         244           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawBasicRoundButton')
                       10 STORE_NAME               2 (__qualname__)
          
-         234          12 LOAD_CLOSURE             0 (__class__)
+         245          12 LOAD_CLOSURE             0 (__class__)
                       14 BUILD_TUPLE              1
-                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\button.py", line 234>)
+                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\button.py", line 245>)
                       18 MAKE_FUNCTION            8 (closure)
                       20 STORE_NAME               3 (__init__)
          
-         237          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\button.py", line 237>)
+         248          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\button.py", line 248>)
                       24 MAKE_FUNCTION            0
                       26 STORE_NAME               4 (_other)
          
-         240          28 LOAD_CONST               3 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 240>)
+         251          28 LOAD_CONST               3 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 251>)
                       30 MAKE_FUNCTION            0
                       32 STORE_NAME               5 (_draw)
          
-         255          34 LOAD_CONST               4 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 255>)
+         271          34 LOAD_CONST               4 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 271>)
                       36 MAKE_FUNCTION            0
                       38 STORE_NAME               6 (default_palette)
          
-         258          40 LOAD_CONST               5 (<code object palette_light, file "D:\tkadw\tkadw\canvas\button.py", line 258>)
+         274          40 LOAD_CONST               5 (<code object palette_light, file "D:\tkadw\tkadw\canvas\button.py", line 274>)
                       42 MAKE_FUNCTION            0
                       44 STORE_NAME               7 (palette_light)
          
-         285          46 LOAD_CONST               6 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\button.py", line 285>)
+         301          46 LOAD_CONST               6 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\button.py", line 301>)
                       48 MAKE_FUNCTION            0
                       50 STORE_NAME               8 (palette_dark)
          
-         312          52 LOAD_CONST               9 ((None,))
+         328          52 LOAD_CONST               9 ((None,))
                       54 LOAD_CLOSURE             0 (__class__)
                       56 BUILD_TUPLE              1
-                      58 LOAD_CONST               8 (<code object palette, file "D:\tkadw\tkadw\canvas\button.py", line 312>)
+                      58 LOAD_CONST               8 (<code object palette, file "D:\tkadw\tkadw\canvas\button.py", line 328>)
                       60 MAKE_FUNCTION            9 (defaults, closure)
                       62 STORE_NAME               9 (palette)
                       64 LOAD_CLOSURE             0 (__class__)
                       66 COPY                     1
                       68 STORE_NAME              10 (__classcell__)
                       70 RETURN_VALUE
          consts
@@ -1981,17 +2014,17 @@
                stacksize : 5
                flags     : 15
                code
                   0x950197000200740100000000000000000000a6000000ab000000000000
                   0000006a0100000000000000007c0169007c02a4018e01010064005300
                              0 COPY_FREE_VARS           1
                
-               234           2 RESUME                   0
+               245           2 RESUME                   0
                
-               235           4 PUSH_NULL
+               246           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                1 (args)
                             44 BUILD_MAP                0
                             46 LOAD_FAST                2 (kwargs)
@@ -2004,29 +2037,29 @@
                   None
                names      ('super', '__init__')
                varnames   ('self', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '__init__'
-               firstlineno 234
+               firstlineno 245
                lnotab 0x0401
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 5
                flags     : 3
                code
                   0x97007c00a00000000000000000000000000000000000000000007c006a
                   010000000000000000a00200000000000000000000000000000000000000
                   006401a6010000ab0100000000000000006402ac03a6020000ab02000000
                   0000000000010064005300
-               237           0 RESUME                   0
+               248           0 RESUME                   0
                
-               238           2 LOAD_FAST                0 (self)
+               249           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (configure)
                             26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                1 (master)
                             38 LOAD_METHOD              2 (cget)
                             60 LOAD_CONST               1 ('bg')
                             62 PRECALL                  1
                             66 CALL                     1
@@ -2044,206 +2077,218 @@
                   ('background', 'borderwidth')
                names      ('configure', 'master', 'cget')
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_other'
-               firstlineno 237
+               firstlineno 248
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 10
                flags     : 3
                code
                   0x97007c00a00000000000000000000000000000000000000000006401a6
                   010000ab01000000000000000001007c00a0010000000000000000000000
-                  000000000000000000640264027c00a00200000000000000000000000000
-                  00000000000000a6000000ab00000000000000000064037a0a00007c00a0
-                  030000000000000000000000000000000000000000a6000000ab00000000
-                  000000000064037a0a00007c006a0400000000000000007c006a05000000
-                  00000000007c006a0600000000000000007c006a070000000000000000ac
-                  04a6080000ab0800000000000000007c005f0800000000000000007c00a0
-                  0900000000000000000000000000000000000000007c00a0020000000000
-                  000000000000000000000000000000a6000000ab00000000000000000064
-                  027a0b00007c00a0030000000000000000000000000000000000000000a6
-                  000000ab00000000000000000064027a0b00007c006a0a00000000000000
-                  007c006a0b00000000000000007c006a0c0000000000000000ac05a60500
-                  00ab0500000000000000007c005f0d000000000000000064005300
-               240           0 RESUME                   0
+                  0000000000000000007c006a0200000000000000007c006a020000000000
+                  0000007c00a0030000000000000000000000000000000000000000a60000
+                  00ab0000000000000000007c006a02000000000000000064027a0500007a
+                  0a00007c00a0040000000000000000000000000000000000000000a60000
+                  00ab0000000000000000007c006a02000000000000000064027a0500007a
+                  0a00007c006a0500000000000000007c006a0200000000000000007c006a
+                  0600000000000000007c006a070000000000000000ac03a6080000ab0800
+                  000000000000007c005f0800000000000000007c00a00900000000000000
+                  000000000000000000000000007c00a00300000000000000000000000000
+                  00000000000000a6000000ab00000000000000000064027a0b00007c00a0
+                  040000000000000000000000000000000000000000a6000000ab00000000
+                  000000000064027a0b00007c006a0a00000000000000007c006a0b000000
+                  00000000007c006a0c0000000000000000ac04a6050000ab050000000000
+                  0000007c005f0d000000000000000064005300
+               251           0 RESUME                   0
                
-               241           2 LOAD_FAST                0 (self)
+               252           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               243          44 LOAD_FAST                0 (self)
+               255          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_round_rect2)
                
-               244          68 LOAD_CONST               2 (2)
-                            70 LOAD_CONST               2 (2)
-                            72 LOAD_FAST                0 (self)
-                            74 LOAD_METHOD              2 (winfo_width)
-                            96 PRECALL                  0
-                           100 CALL                     0
-                           110 LOAD_CONST               3 (3)
-                           112 BINARY_OP               10 (-)
-                           116 LOAD_FAST                0 (self)
-                           118 LOAD_METHOD              3 (winfo_height)
-                           140 PRECALL                  0
-                           144 CALL                     0
-                           154 LOAD_CONST               3 (3)
-                           156 BINARY_OP               10 (-)
-                           160 LOAD_FAST                0 (self)
-                           162 LOAD_ATTR                4 (button_radius)
-               
-               245         172 LOAD_FAST                0 (self)
-                           174 LOAD_ATTR                5 (_button_border_width)
-               
-               246         184 LOAD_FAST                0 (self)
-                           186 LOAD_ATTR                6 (_button_border)
-                           196 LOAD_FAST                0 (self)
-                           198 LOAD_ATTR                7 (_button_back)
+               256          68 LOAD_FAST                0 (self)
+                            70 LOAD_ATTR                2 (_button_border_width)
                
-               243         208 KW_NAMES                 4
-                           210 PRECALL                  8
-                           214 CALL                     8
-                           224 LOAD_FAST                0 (self)
-                           226 STORE_ATTR               8 (button_frame)
-               
-               249         236 LOAD_FAST                0 (self)
-                           238 LOAD_METHOD              9 (create_text)
-               
-               250         260 LOAD_FAST                0 (self)
-                           262 LOAD_METHOD              2 (winfo_width)
-                           284 PRECALL                  0
-                           288 CALL                     0
-                           298 LOAD_CONST               2 (2)
-                           300 BINARY_OP               11 (/)
-                           304 LOAD_FAST                0 (self)
-                           306 LOAD_METHOD              3 (winfo_height)
-                           328 PRECALL                  0
-                           332 CALL                     0
-                           342 LOAD_CONST               2 (2)
-                           344 BINARY_OP               11 (/)
+               257          80 LOAD_FAST                0 (self)
+                            82 LOAD_ATTR                2 (_button_border_width)
                
-               251         348 LOAD_FAST                0 (self)
-                           350 LOAD_ATTR               10 (text)
-                           360 LOAD_FAST                0 (self)
-                           362 LOAD_ATTR               11 (_button_text_back)
+               258          92 LOAD_FAST                0 (self)
+                            94 LOAD_METHOD              3 (winfo_width)
+                           116 PRECALL                  0
+                           120 CALL                     0
+                           130 LOAD_FAST                0 (self)
+                           132 LOAD_ATTR                2 (_button_border_width)
+                           142 LOAD_CONST               2 (2)
+                           144 BINARY_OP                5 (*)
+                           148 BINARY_OP               10 (-)
+               
+               259         152 LOAD_FAST                0 (self)
+                           154 LOAD_METHOD              4 (winfo_height)
+                           176 PRECALL                  0
+                           180 CALL                     0
+                           190 LOAD_FAST                0 (self)
+                           192 LOAD_ATTR                2 (_button_border_width)
+                           202 LOAD_CONST               2 (2)
+                           204 BINARY_OP                5 (*)
+                           208 BINARY_OP               10 (-)
+                           212 LOAD_FAST                0 (self)
+                           214 LOAD_ATTR                5 (button_radius)
                
-               252         372 LOAD_FAST                0 (self)
-                           374 LOAD_ATTR               12 (button_text_font)
+               260         224 LOAD_FAST                0 (self)
+                           226 LOAD_ATTR                2 (_button_border_width)
                
-               249         384 KW_NAMES                 5
-                           386 PRECALL                  5
-                           390 CALL                     5
-                           400 LOAD_FAST                0 (self)
-                           402 STORE_ATTR              13 (button_text)
-                           412 LOAD_CONST               0 (None)
-                           414 RETURN_VALUE
+               261         236 LOAD_FAST                0 (self)
+                           238 LOAD_ATTR                6 (_button_border)
+                           248 LOAD_FAST                0 (self)
+                           250 LOAD_ATTR                7 (_button_back)
+               
+               255         260 KW_NAMES                 3
+                           262 PRECALL                  8
+                           266 CALL                     8
+                           276 LOAD_FAST                0 (self)
+                           278 STORE_ATTR               8 (button_frame)
+               
+               265         288 LOAD_FAST                0 (self)
+                           290 LOAD_METHOD              9 (create_text)
+               
+               266         312 LOAD_FAST                0 (self)
+                           314 LOAD_METHOD              3 (winfo_width)
+                           336 PRECALL                  0
+                           340 CALL                     0
+                           350 LOAD_CONST               2 (2)
+                           352 BINARY_OP               11 (/)
+                           356 LOAD_FAST                0 (self)
+                           358 LOAD_METHOD              4 (winfo_height)
+                           380 PRECALL                  0
+                           384 CALL                     0
+                           394 LOAD_CONST               2 (2)
+                           396 BINARY_OP               11 (/)
+               
+               267         400 LOAD_FAST                0 (self)
+                           402 LOAD_ATTR               10 (text)
+                           412 LOAD_FAST                0 (self)
+                           414 LOAD_ATTR               11 (_button_text_back)
+               
+               268         424 LOAD_FAST                0 (self)
+                           426 LOAD_ATTR               12 (button_text_font)
+               
+               265         436 KW_NAMES                 4
+                           438 PRECALL                  5
+                           442 CALL                     5
+                           452 LOAD_FAST                0 (self)
+                           454 STORE_ATTR              13 (button_text)
+                           464 LOAD_CONST               0 (None)
+                           466 RETURN_VALUE
                consts
                   None
                   'all'
                   2
-                  3
                   ('width', 'outline', 'fill')
                   ('text', 'fill', 'font')
-               names      ('delete', 'create_round_rect2', 'winfo_width', 'winfo_height', 'button_radius', '_button_border_width', '_button_border', '_button_back', 'button_frame', 'create_text', 'text', '_button_text_back', 'button_text_font', 'button_text')
+               names      ('delete', 'create_round_rect2', '_button_border_width', 'winfo_width', 'winfo_height', 'button_radius', '_button_border', '_button_back', 'button_frame', 'create_text', 'text', '_button_text_back', 'button_text_font', 'button_text')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_draw'
-               firstlineno 240
-               lnotab 0x02012a02180168010c0118fd1c061801580118010cfd
+               firstlineno 251
+               lnotab 0x02012a0318010c010c013c0148010c0118fa1c0a1801580118010cfd
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               255           0 RESUME                   0
+               271           0 RESUME                   0
                
-               256           2 LOAD_FAST                0 (self)
+               272           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 255
+               firstlineno 271
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 14
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   0264036404640564066407640864096406640a9c046407640b640c640664
                   0a9c04640d9c076901a6010000ab010000000000000000010064005300
-               258           0 RESUME                   0
+               274           0 RESUME                   0
                
-               259           2 LOAD_FAST                0 (self)
+               275           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               261          26 LOAD_CONST               1 ('button')
+               277          26 LOAD_CONST               1 ('button')
                
-               262          28 LOAD_CONST               2 (8)
+               278          28 LOAD_CONST               2 (8)
                
-               263          30 LOAD_CONST               3 ('#fdfdfd')
+               279          30 LOAD_CONST               3 ('#fdfdfd')
                
-               264          32 LOAD_CONST               4 ('#eaeaea')
+               280          32 LOAD_CONST               4 ('#eaeaea')
                
-               265          34 LOAD_CONST               5 ('#1a1a1a')
+               281          34 LOAD_CONST               5 ('#1a1a1a')
                
-               266          36 LOAD_CONST               6 (1)
+               282          36 LOAD_CONST               6 (1)
                
-               269          38 LOAD_CONST               7 ('#f9f9f9')
+               285          38 LOAD_CONST               7 ('#f9f9f9')
                
-               270          40 LOAD_CONST               8 ('#454545')
+               286          40 LOAD_CONST               8 ('#454545')
                
-               271          42 LOAD_CONST               9 ('#5f5f5f')
+               287          42 LOAD_CONST               9 ('#5f5f5f')
                
-               272          44 LOAD_CONST               6 (1)
+               288          44 LOAD_CONST               6 (1)
                
-               268          46 LOAD_CONST              10 (('back', 'border', 'text_back', 'border_width'))
+               284          46 LOAD_CONST              10 (('back', 'border', 'text_back', 'border_width'))
                             48 BUILD_CONST_KEY_MAP      4
                
-               276          50 LOAD_CONST               7 ('#f9f9f9')
+               292          50 LOAD_CONST               7 ('#f9f9f9')
                
-               277          52 LOAD_CONST              11 ('#e2e2e2')
+               293          52 LOAD_CONST              11 ('#e2e2e2')
                
-               278          54 LOAD_CONST              12 ('#8a8a8a')
+               294          54 LOAD_CONST              12 ('#8a8a8a')
                
-               279          56 LOAD_CONST               6 (1)
+               295          56 LOAD_CONST               6 (1)
                
-               275          58 LOAD_CONST              10 (('back', 'border', 'text_back', 'border_width'))
+               291          58 LOAD_CONST              10 (('back', 'border', 'text_back', 'border_width'))
                             60 BUILD_CONST_KEY_MAP      4
                
-               261          62 LOAD_CONST              13 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
+               277          62 LOAD_CONST              13 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
                             64 BUILD_CONST_KEY_MAP      7
                
-               260          66 BUILD_MAP                1
+               276          66 BUILD_MAP                1
                
-               259          68 PRECALL                  1
+               275          68 PRECALL                  1
                             72 CALL                     1
                             82 POP_TOP
                             84 LOAD_CONST               0 (None)
                             86 RETURN_VALUE
                consts
                   None
                   'button'
@@ -2261,72 +2306,72 @@
                   ('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'palette_light'
-               firstlineno 258
+               firstlineno 274
                lnotab
                   0x0201180202010201020102010201020302010201020102fc0408020102
                   01020102fc04f204ff02ff
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 14
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   026403640464056406640764046408640664099c04640a6404640b640664
                   099c04640c9c076901a6010000ab010000000000000000010064005300
-               285           0 RESUME                   0
+               301           0 RESUME                   0
                
-               286           2 LOAD_FAST                0 (self)
+               302           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               288          26 LOAD_CONST               1 ('button')
+               304          26 LOAD_CONST               1 ('button')
                
-               289          28 LOAD_CONST               2 (8)
+               305          28 LOAD_CONST               2 (8)
                
-               290          30 LOAD_CONST               3 ('#353535')
+               306          30 LOAD_CONST               3 ('#353535')
                
-               291          32 LOAD_CONST               4 ('#454545')
+               307          32 LOAD_CONST               4 ('#454545')
                
-               292          34 LOAD_CONST               5 ('#ffffff')
+               308          34 LOAD_CONST               5 ('#ffffff')
                
-               293          36 LOAD_CONST               6 (1)
+               309          36 LOAD_CONST               6 (1)
                
-               296          38 LOAD_CONST               7 ('#3a3a3a')
+               312          38 LOAD_CONST               7 ('#3a3a3a')
                
-               297          40 LOAD_CONST               4 ('#454545')
+               313          40 LOAD_CONST               4 ('#454545')
                
-               298          42 LOAD_CONST               8 ('#cecece')
+               314          42 LOAD_CONST               8 ('#cecece')
                
-               299          44 LOAD_CONST               6 (1)
+               315          44 LOAD_CONST               6 (1)
                
-               295          46 LOAD_CONST               9 (('back', 'border', 'text_back', 'border_width'))
+               311          46 LOAD_CONST               9 (('back', 'border', 'text_back', 'border_width'))
                             48 BUILD_CONST_KEY_MAP      4
                
-               303          50 LOAD_CONST              10 ('#2f2f2f')
+               319          50 LOAD_CONST              10 ('#2f2f2f')
                
-               304          52 LOAD_CONST               4 ('#454545')
+               320          52 LOAD_CONST               4 ('#454545')
                
-               305          54 LOAD_CONST              11 ('#9a9a9a')
+               321          54 LOAD_CONST              11 ('#9a9a9a')
                
-               306          56 LOAD_CONST               6 (1)
+               322          56 LOAD_CONST               6 (1)
                
-               302          58 LOAD_CONST               9 (('back', 'border', 'text_back', 'border_width'))
+               318          58 LOAD_CONST               9 (('back', 'border', 'text_back', 'border_width'))
                             60 BUILD_CONST_KEY_MAP      4
                
-               288          62 LOAD_CONST              12 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
+               304          62 LOAD_CONST              12 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
                             64 BUILD_CONST_KEY_MAP      7
                
-               287          66 BUILD_MAP                1
+               303          66 BUILD_MAP                1
                
-               286          68 PRECALL                  1
+               302          68 PRECALL                  1
                             72 CALL                     1
                             82 POP_TOP
                             84 LOAD_CONST               0 (None)
                             86 RETURN_VALUE
                consts
                   None
                   'button'
@@ -2343,15 +2388,15 @@
                   ('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'palette_dark'
-               firstlineno 285
+               firstlineno 301
                lnotab
                   0x0201180202010201020102010201020302010201020102fc0408020102
                   01020102fc04f204ff02ff
             None
             code
                argcount  : 2
                nlocals   : 2
@@ -2361,133 +2406,133 @@
                   0x95019700740100000000000000000000a6000000ab0000000000000000
                   00a00100000000000000000000000000000000000000007c01a6010000ab
                   010000000000000000010064017c01760072157c01640119000000000000
                   0000006402190000000000000000007c005f020000000000000000640053
                   0064005300
                              0 COPY_FREE_VARS           1
                
-               312           2 RESUME                   0
+               328           2 RESUME                   0
                
-               313           4 LOAD_GLOBAL              1 (NULL + super)
+               329           4 LOAD_GLOBAL              1 (NULL + super)
                             16 PRECALL                  0
                             20 CALL                     0
                             30 LOAD_METHOD              1 (palette)
                             52 LOAD_FAST                1 (dict)
                             54 PRECALL                  1
                             58 CALL                     1
                             68 POP_TOP
                
-               314          70 LOAD_CONST               1 ('button')
+               330          70 LOAD_CONST               1 ('button')
                             72 LOAD_FAST                1 (dict)
                             74 CONTAINS_OP              0
                             76 POP_JUMP_FORWARD_IF_FALSE    21 (to 120)
                
-               315          78 LOAD_FAST                1 (dict)
+               331          78 LOAD_FAST                1 (dict)
                             80 LOAD_CONST               1 ('button')
                             82 BINARY_SUBSCR
                             92 LOAD_CONST               2 ('radius')
                             94 BINARY_SUBSCR
                            104 LOAD_FAST                0 (self)
                            106 STORE_ATTR               2 (button_radius)
                            116 LOAD_CONST               0 (None)
                            118 RETURN_VALUE
                
-               314     >>  120 LOAD_CONST               0 (None)
+               330     >>  120 LOAD_CONST               0 (None)
                            122 RETURN_VALUE
                consts
                   None
                   'button'
                   'radius'
                names      ('super', 'palette', 'button_radius')
                varnames   ('self', 'dict')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'palette'
-               firstlineno 312
+               firstlineno 328
                lnotab 0x0401420108012aff
             (None,)
          names      ('__name__', '__module__', '__qualname__', '__init__', '_other', '_draw', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawBasicRoundButton'
-         firstlineno 233
-         lnotab 0x0c010a030603060f0603061b061b
+         firstlineno 244
+         lnotab 0x0c010a03060306140603061b061b
       'AdwDrawBasicRoundButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         318           0 RESUME                   0
+         334           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundButton')
                        8 STORE_NAME               2 (__qualname__)
          
-         319          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 319>)
+         335          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 335>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundButton'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               319           0 RESUME                   0
+               335           0 RESUME                   0
                
-               320           2 LOAD_FAST                0 (self)
+               336           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 319
+               firstlineno 335
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawRoundButton'
-         firstlineno 318
+         firstlineno 334
          lnotab 0x0a01
       'AdwDrawRoundButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         323           0 RESUME                   0
+         339           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundAccentButton')
                        8 STORE_NAME               2 (__qualname__)
          
-         324          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 324>)
+         340          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 340>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundAccentButton'
             code
@@ -2495,59 +2540,59 @@
                nlocals   : 1
                stacksize : 14
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   026403640464056406640764046405640664089c0464096409640a640664
                   089c04640b9c076901a6010000ab010000000000000000010064005300
-               324           0 RESUME                   0
+               340           0 RESUME                   0
                
-               325           2 LOAD_FAST                0 (self)
+               341           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               327          26 LOAD_CONST               1 ('button')
+               343          26 LOAD_CONST               1 ('button')
                
-               328          28 LOAD_CONST               2 (8)
+               344          28 LOAD_CONST               2 (8)
                
-               329          30 LOAD_CONST               3 ('#0067c0')
+               345          30 LOAD_CONST               3 ('#0067c0')
                
-               330          32 LOAD_CONST               4 ('#1473c5')
+               346          32 LOAD_CONST               4 ('#1473c5')
                
-               331          34 LOAD_CONST               5 ('#ffffff')
+               347          34 LOAD_CONST               5 ('#ffffff')
                
-               332          36 LOAD_CONST               6 (1)
+               348          36 LOAD_CONST               6 (1)
                
-               335          38 LOAD_CONST               7 ('#1975c5')
+               351          38 LOAD_CONST               7 ('#1975c5')
                
-               336          40 LOAD_CONST               4 ('#1473c5')
+               352          40 LOAD_CONST               4 ('#1473c5')
                
-               337          42 LOAD_CONST               5 ('#ffffff')
+               353          42 LOAD_CONST               5 ('#ffffff')
                
-               338          44 LOAD_CONST               6 (1)
+               354          44 LOAD_CONST               6 (1)
                
-               334          46 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
+               350          46 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
                             48 BUILD_CONST_KEY_MAP      4
                
-               342          50 LOAD_CONST               9 ('#3284cb')
+               358          50 LOAD_CONST               9 ('#3284cb')
                
-               343          52 LOAD_CONST               9 ('#3284cb')
+               359          52 LOAD_CONST               9 ('#3284cb')
                
-               344          54 LOAD_CONST              10 ('#fdfdfd')
+               360          54 LOAD_CONST              10 ('#fdfdfd')
                
-               345          56 LOAD_CONST               6 (1)
+               361          56 LOAD_CONST               6 (1)
                
-               341          58 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
+               357          58 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
                             60 BUILD_CONST_KEY_MAP      4
                
-               327          62 LOAD_CONST              11 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
+               343          62 LOAD_CONST              11 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
                             64 BUILD_CONST_KEY_MAP      7
                
-               326          66 BUILD_MAP                1
+               342          66 BUILD_MAP                1
                
-               325          68 PRECALL                  1
+               341          68 PRECALL                  1
                             72 CALL                     1
                             82 POP_TOP
                             84 LOAD_CONST               0 (None)
                             86 RETURN_VALUE
                consts
                   None
                   'button'
@@ -2563,101 +2608,101 @@
                   ('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 324
+               firstlineno 340
                lnotab
                   0x0201180202010201020102010201020302010201020102fc0408020102
                   01020102fc04f204ff02ff
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawRoundAccentButton'
-         firstlineno 323
+         firstlineno 339
          lnotab 0x0a01
       'AdwDrawRoundAccentButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         352           0 RESUME                   0
+         368           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundDarkButton')
                        8 STORE_NAME               2 (__qualname__)
          
-         353          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 353>)
+         369          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 369>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundDarkButton'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               353           0 RESUME                   0
+               369           0 RESUME                   0
                
-               354           2 LOAD_FAST                0 (self)
+               370           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 353
+               firstlineno 369
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawRoundDarkButton'
-         firstlineno 352
+         firstlineno 368
          lnotab 0x0a01
       'AdwDrawRoundDarkButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a03640284005a0464035300
-         357           0 RESUME                   0
+         373           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundButton2')
                        8 STORE_NAME               2 (__qualname__)
          
-         358          10 LOAD_CONST               1 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 358>)
+         375          10 LOAD_CONST               1 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 375>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (_draw)
          
-         375          16 LOAD_CONST               2 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 375>)
+         395          16 LOAD_CONST               2 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 395>)
                       18 MAKE_FUNCTION            0
                       20 STORE_NAME               4 (default_palette)
                       22 LOAD_CONST               3 (None)
                       24 RETURN_VALUE
          consts
             'AdwDrawRoundButton2'
             code
@@ -2676,84 +2721,85 @@
                   0000000000010064027c005f0700000000000000007c00a0080000000000
                   0000000000000000000000000000007c00a0020000000000000000000000
                   000000000000000000a6000000ab00000000000000000064037a0b00007c
                   00a0030000000000000000000000000000000000000000a6000000ab0000
                   0000000000000064037a0b00007c006a0900000000000000007c006a0a00
                   000000000000007c006a0b0000000000000000ac06a6050000ab05000000
                   00000000007c005f0c000000000000000064005300
-               358           0 RESUME                   0
+               375           0 RESUME                   0
                
-               359           2 LOAD_FAST                0 (self)
+               376           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               361          44 LOAD_FAST                0 (self)
+               379          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_round_rect3)
                
-               362          68 LOAD_CONST               2 ('button_frame')
+               380          68 LOAD_CONST               2 ('button_frame')
                
-               363          70 LOAD_CONST               3 (2)
+               381          70 LOAD_CONST               3 (2)
                             72 LOAD_CONST               3 (2)
-                            74 LOAD_FAST                0 (self)
+               
+               382          74 LOAD_FAST                0 (self)
                             76 LOAD_METHOD              2 (winfo_width)
                             98 PRECALL                  0
                            102 CALL                     0
                            112 LOAD_CONST               4 (3)
                            114 BINARY_OP               10 (-)
                            118 LOAD_FAST                0 (self)
                            120 LOAD_METHOD              3 (winfo_height)
                            142 PRECALL                  0
                            146 CALL                     0
                            156 LOAD_CONST               4 (3)
                            158 BINARY_OP               10 (-)
                            162 LOAD_FAST                0 (self)
                            164 LOAD_ATTR                4 (button_radius)
                
-               364         174 LOAD_FAST                0 (self)
+               383         174 LOAD_FAST                0 (self)
                            176 LOAD_ATTR                5 (_button_border)
                            186 LOAD_FAST                0 (self)
                            188 LOAD_ATTR                6 (_button_back)
                
-               361         198 KW_NAMES                 5
+               379         198 KW_NAMES                 5
                            200 PRECALL                  8
                            204 CALL                     8
                            214 POP_TOP
                
-               367         216 LOAD_CONST               2 ('button_frame')
+               386         216 LOAD_CONST               2 ('button_frame')
                            218 LOAD_FAST                0 (self)
                            220 STORE_ATTR               7 (button_frame)
                
-               369         230 LOAD_FAST                0 (self)
+               389         230 LOAD_FAST                0 (self)
                            232 LOAD_METHOD              8 (create_text)
                
-               370         254 LOAD_FAST                0 (self)
+               390         254 LOAD_FAST                0 (self)
                            256 LOAD_METHOD              2 (winfo_width)
                            278 PRECALL                  0
                            282 CALL                     0
                            292 LOAD_CONST               3 (2)
                            294 BINARY_OP               11 (/)
                            298 LOAD_FAST                0 (self)
                            300 LOAD_METHOD              3 (winfo_height)
                            322 PRECALL                  0
                            326 CALL                     0
                            336 LOAD_CONST               3 (2)
                            338 BINARY_OP               11 (/)
                
-               371         342 LOAD_FAST                0 (self)
+               391         342 LOAD_FAST                0 (self)
                            344 LOAD_ATTR                9 (text)
                            354 LOAD_FAST                0 (self)
                            356 LOAD_ATTR               10 (_button_text_back)
                
-               372         366 LOAD_FAST                0 (self)
+               392         366 LOAD_FAST                0 (self)
                            368 LOAD_ATTR               11 (button_text_font)
                
-               369         378 KW_NAMES                 6
+               389         378 KW_NAMES                 6
                            380 PRECALL                  5
                            384 CALL                     5
                            394 LOAD_FAST                0 (self)
                            396 STORE_ATTR              12 (button_text)
                            406 LOAD_CONST               0 (None)
                            408 RETURN_VALUE
                consts
@@ -2766,66 +2812,66 @@
                   ('text', 'fill', 'font')
                names      ('delete', 'create_round_rect3', 'winfo_width', 'winfo_height', 'button_radius', '_button_border', '_button_back', 'button_frame', 'create_text', 'text', '_button_text_back', 'button_text_font', 'button_text')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_draw'
-               firstlineno 358
-               lnotab 0x02012a0218010201680118fd12060e021801580118010cfd
+               firstlineno 375
+               lnotab 0x02012a03180102010401640118fc12070e031801580118010cfd
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               375           0 RESUME                   0
+               395           0 RESUME                   0
                
-               376           2 LOAD_FAST                0 (self)
+               396           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 375
+               firstlineno 395
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', '_draw', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawRoundButton2'
-         firstlineno 357
-         lnotab 0x0a010611
+         firstlineno 373
+         lnotab 0x0a020614
       'AdwDrawRoundButton2'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         379           0 RESUME                   0
+         399           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundAccentButton2')
                        8 STORE_NAME               2 (__qualname__)
          
-         380          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 380>)
+         400          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 400>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundAccentButton2'
             code
@@ -2833,59 +2879,59 @@
                nlocals   : 1
                stacksize : 14
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   026403640464056406640764046405640664089c0464096409640a640664
                   089c04640b9c076901a6010000ab010000000000000000010064005300
-               380           0 RESUME                   0
+               400           0 RESUME                   0
                
-               381           2 LOAD_FAST                0 (self)
+               401           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               383          26 LOAD_CONST               1 ('button')
+               403          26 LOAD_CONST               1 ('button')
                
-               384          28 LOAD_CONST               2 (8)
+               404          28 LOAD_CONST               2 (8)
                
-               385          30 LOAD_CONST               3 ('#0067c0')
+               405          30 LOAD_CONST               3 ('#0067c0')
                
-               386          32 LOAD_CONST               4 ('#1473c5')
+               406          32 LOAD_CONST               4 ('#1473c5')
                
-               387          34 LOAD_CONST               5 ('#ffffff')
+               407          34 LOAD_CONST               5 ('#ffffff')
                
-               388          36 LOAD_CONST               6 (1)
+               408          36 LOAD_CONST               6 (1)
                
-               391          38 LOAD_CONST               7 ('#1975c5')
+               411          38 LOAD_CONST               7 ('#1975c5')
                
-               392          40 LOAD_CONST               4 ('#1473c5')
+               412          40 LOAD_CONST               4 ('#1473c5')
                
-               393          42 LOAD_CONST               5 ('#ffffff')
+               413          42 LOAD_CONST               5 ('#ffffff')
                
-               394          44 LOAD_CONST               6 (1)
+               414          44 LOAD_CONST               6 (1)
                
-               390          46 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
+               410          46 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
                             48 BUILD_CONST_KEY_MAP      4
                
-               398          50 LOAD_CONST               9 ('#3284cb')
+               418          50 LOAD_CONST               9 ('#3284cb')
                
-               399          52 LOAD_CONST               9 ('#3284cb')
+               419          52 LOAD_CONST               9 ('#3284cb')
                
-               400          54 LOAD_CONST              10 ('#fdfdfd')
+               420          54 LOAD_CONST              10 ('#fdfdfd')
                
-               401          56 LOAD_CONST               6 (1)
+               421          56 LOAD_CONST               6 (1)
                
-               397          58 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
+               417          58 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
                             60 BUILD_CONST_KEY_MAP      4
                
-               383          62 LOAD_CONST              11 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
+               403          62 LOAD_CONST              11 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
                             64 BUILD_CONST_KEY_MAP      7
                
-               382          66 BUILD_MAP                1
+               402          66 BUILD_MAP                1
                
-               381          68 PRECALL                  1
+               401          68 PRECALL                  1
                             72 CALL                     1
                             82 POP_TOP
                             84 LOAD_CONST               0 (None)
                             86 RETURN_VALUE
                consts
                   None
                   'button'
@@ -2901,271 +2947,284 @@
                   ('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 380
+               firstlineno 400
                lnotab
                   0x0201180202010201020102010201020302010201020102fc0408020102
                   01020102fc04f204ff02ff
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawRoundAccentButton2'
-         firstlineno 379
+         firstlineno 399
          lnotab 0x0a01
       'AdwDrawRoundAccentButton2'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         408           0 RESUME                   0
+         428           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundDarkButton2')
                        8 STORE_NAME               2 (__qualname__)
          
-         409          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 409>)
+         429          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 429>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundDarkButton2'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               409           0 RESUME                   0
+               429           0 RESUME                   0
                
-               410           2 LOAD_FAST                0 (self)
+               430           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 409
+               firstlineno 429
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawRoundDarkButton2'
-         firstlineno 408
+         firstlineno 428
          lnotab 0x0a01
       'AdwDrawRoundDarkButton2'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a03640284005a0464035300
-         413           0 RESUME                   0
+         433           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundButton3')
                        8 STORE_NAME               2 (__qualname__)
          
-         414          10 LOAD_CONST               1 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 414>)
+         434          10 LOAD_CONST               1 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 434>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (_draw)
          
-         431          16 LOAD_CONST               2 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 431>)
+         456          16 LOAD_CONST               2 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 456>)
                       18 MAKE_FUNCTION            0
                       20 STORE_NAME               4 (default_palette)
                       22 LOAD_CONST               3 (None)
                       24 RETURN_VALUE
          consts
             'AdwDrawRoundButton3'
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 10
                flags     : 3
                code
                   0x97007c00a00000000000000000000000000000000000000000006401a6
                   010000ab01000000000000000001007c00a0010000000000000000000000
-                  000000000000000000640264027c00a00200000000000000000000000000
-                  00000000000000a6000000ab00000000000000000064037a0a00007c00a0
-                  030000000000000000000000000000000000000000a6000000ab00000000
-                  000000000064037a0a00007c006a0400000000000000007c006a05000000
-                  00000000007c006a0600000000000000007c006a070000000000000000ac
-                  04a6080000ab080000000000000000010064057c005f0800000000000000
-                  007c00a00900000000000000000000000000000000000000007c00a00200
-                  00000000000000000000000000000000000000a6000000ab000000000000
-                  00000064037a0b00007c00a0030000000000000000000000000000000000
-                  000000a6000000ab00000000000000000064037a0b00007c006a0a000000
-                  00000000007c006a0b00000000000000007c006a0c0000000000000000ac
-                  06a6050000ab0500000000000000007c005f0d0000000000000000640053
-                  00
-               414           0 RESUME                   0
+                  0000000000000000007c006a0200000000000000007c006a020000000000
+                  0000007c00a0030000000000000000000000000000000000000000a60000
+                  00ab0000000000000000007c006a02000000000000000064027a0500007a
+                  0a00007c00a0040000000000000000000000000000000000000000a60000
+                  00ab0000000000000000007c006a02000000000000000064027a0500007a
+                  0a00007c006a0500000000000000007c006a0200000000000000007c006a
+                  0600000000000000007c006a070000000000000000ac03a6080000ab0800
+                  00000000000000010064047c005f0800000000000000007c00a009000000
+                  00000000000000000000000000000000007c00a003000000000000000000
+                  0000000000000000000000a6000000ab00000000000000000064027a0b00
+                  007c00a0040000000000000000000000000000000000000000a6000000ab
+                  00000000000000000064027a0b00007c006a0a00000000000000007c006a
+                  0b00000000000000007c006a0c0000000000000000ac05a6050000ab0500
+                  000000000000007c005f0d000000000000000064005300
+               434           0 RESUME                   0
                
-               415           2 LOAD_FAST                0 (self)
+               435           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               417          44 LOAD_FAST                0 (self)
+               438          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_round_rect4)
                
-               418          68 LOAD_CONST               2 (1)
-                            70 LOAD_CONST               2 (1)
-                            72 LOAD_FAST                0 (self)
-                            74 LOAD_METHOD              2 (winfo_width)
-                            96 PRECALL                  0
-                           100 CALL                     0
-                           110 LOAD_CONST               3 (2)
-                           112 BINARY_OP               10 (-)
-                           116 LOAD_FAST                0 (self)
-                           118 LOAD_METHOD              3 (winfo_height)
-                           140 PRECALL                  0
-                           144 CALL                     0
-                           154 LOAD_CONST               3 (2)
-                           156 BINARY_OP               10 (-)
-                           160 LOAD_FAST                0 (self)
-                           162 LOAD_ATTR                4 (button_radius)
-               
-               419         172 LOAD_FAST                0 (self)
-                           174 LOAD_ATTR                5 (_button_border_width)
-               
-               420         184 LOAD_FAST                0 (self)
-                           186 LOAD_ATTR                6 (_button_border)
-                           196 LOAD_FAST                0 (self)
-                           198 LOAD_ATTR                7 (_button_back)
-               
-               417         208 KW_NAMES                 4
-                           210 PRECALL                  8
-                           214 CALL                     8
-                           224 POP_TOP
-               
-               423         226 LOAD_CONST               5 ('button_frame')
-                           228 LOAD_FAST                0 (self)
-                           230 STORE_ATTR               8 (button_frame)
-               
-               425         240 LOAD_FAST                0 (self)
-                           242 LOAD_METHOD              9 (create_text)
-               
-               426         264 LOAD_FAST                0 (self)
-                           266 LOAD_METHOD              2 (winfo_width)
-                           288 PRECALL                  0
-                           292 CALL                     0
-                           302 LOAD_CONST               3 (2)
-                           304 BINARY_OP               11 (/)
-                           308 LOAD_FAST                0 (self)
-                           310 LOAD_METHOD              3 (winfo_height)
-                           332 PRECALL                  0
-                           336 CALL                     0
-                           346 LOAD_CONST               3 (2)
-                           348 BINARY_OP               11 (/)
-               
-               427         352 LOAD_FAST                0 (self)
-                           354 LOAD_ATTR               10 (text)
-                           364 LOAD_FAST                0 (self)
-                           366 LOAD_ATTR               11 (_button_text_back)
-               
-               428         376 LOAD_FAST                0 (self)
-                           378 LOAD_ATTR               12 (button_text_font)
-               
-               425         388 KW_NAMES                 6
-                           390 PRECALL                  5
-                           394 CALL                     5
-                           404 LOAD_FAST                0 (self)
-                           406 STORE_ATTR              13 (button_text)
-                           416 LOAD_CONST               0 (None)
-                           418 RETURN_VALUE
+               439          68 LOAD_FAST                0 (self)
+                            70 LOAD_ATTR                2 (_button_border_width)
+                            80 LOAD_FAST                0 (self)
+                            82 LOAD_ATTR                2 (_button_border_width)
+               
+               440          92 LOAD_FAST                0 (self)
+                            94 LOAD_METHOD              3 (winfo_width)
+                           116 PRECALL                  0
+                           120 CALL                     0
+                           130 LOAD_FAST                0 (self)
+                           132 LOAD_ATTR                2 (_button_border_width)
+                           142 LOAD_CONST               2 (2)
+                           144 BINARY_OP                5 (*)
+                           148 BINARY_OP               10 (-)
+               
+               441         152 LOAD_FAST                0 (self)
+                           154 LOAD_METHOD              4 (winfo_height)
+                           176 PRECALL                  0
+                           180 CALL                     0
+                           190 LOAD_FAST                0 (self)
+                           192 LOAD_ATTR                2 (_button_border_width)
+                           202 LOAD_CONST               2 (2)
+                           204 BINARY_OP                5 (*)
+                           208 BINARY_OP               10 (-)
+               
+               442         212 LOAD_FAST                0 (self)
+                           214 LOAD_ATTR                5 (button_radius)
+               
+               443         224 LOAD_FAST                0 (self)
+                           226 LOAD_ATTR                2 (_button_border_width)
+               
+               444         236 LOAD_FAST                0 (self)
+                           238 LOAD_ATTR                6 (_button_border)
+                           248 LOAD_FAST                0 (self)
+                           250 LOAD_ATTR                7 (_button_back)
+               
+               438         260 KW_NAMES                 3
+                           262 PRECALL                  8
+                           266 CALL                     8
+                           276 POP_TOP
+               
+               447         278 LOAD_CONST               4 ('button_frame')
+                           280 LOAD_FAST                0 (self)
+                           282 STORE_ATTR               8 (button_frame)
+               
+               450         292 LOAD_FAST                0 (self)
+                           294 LOAD_METHOD              9 (create_text)
+               
+               451         316 LOAD_FAST                0 (self)
+                           318 LOAD_METHOD              3 (winfo_width)
+                           340 PRECALL                  0
+                           344 CALL                     0
+                           354 LOAD_CONST               2 (2)
+                           356 BINARY_OP               11 (/)
+                           360 LOAD_FAST                0 (self)
+                           362 LOAD_METHOD              4 (winfo_height)
+                           384 PRECALL                  0
+                           388 CALL                     0
+                           398 LOAD_CONST               2 (2)
+                           400 BINARY_OP               11 (/)
+               
+               452         404 LOAD_FAST                0 (self)
+                           406 LOAD_ATTR               10 (text)
+                           416 LOAD_FAST                0 (self)
+                           418 LOAD_ATTR               11 (_button_text_back)
+               
+               453         428 LOAD_FAST                0 (self)
+                           430 LOAD_ATTR               12 (button_text_font)
+               
+               450         440 KW_NAMES                 5
+                           442 PRECALL                  5
+                           446 CALL                     5
+                           456 LOAD_FAST                0 (self)
+                           458 STORE_ATTR              13 (button_text)
+                           468 LOAD_CONST               0 (None)
+                           470 RETURN_VALUE
                consts
                   None
                   'all'
-                  1
                   2
                   ('width', 'outline', 'fill')
                   'button_frame'
                   ('text', 'fill', 'font')
-               names      ('delete', 'create_round_rect4', 'winfo_width', 'winfo_height', 'button_radius', '_button_border_width', '_button_border', '_button_back', 'button_frame', 'create_text', 'text', '_button_text_back', 'button_text_font', 'button_text')
+               names      ('delete', 'create_round_rect4', '_button_border_width', 'winfo_width', 'winfo_height', 'button_radius', '_button_border', '_button_back', 'button_frame', 'create_text', 'text', '_button_text_back', 'button_text_font', 'button_text')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_draw'
-               firstlineno 414
-               lnotab 0x02012a02180168010c0118fd12060e021801580118010cfd
+               firstlineno 434
+               lnotab
+                  0x02012a03180118013c013c010c010c0118fa12090e031801580118010c
+                  fd
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               431           0 RESUME                   0
+               456           0 RESUME                   0
                
-               432           2 LOAD_FAST                0 (self)
+               457           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 431
+               firstlineno 456
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', '_draw', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawRoundButton3'
-         firstlineno 413
-         lnotab 0x0a010611
+         firstlineno 433
+         lnotab 0x0a010616
       'AdwDrawRoundButton3'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         435           0 RESUME                   0
+         460           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundAccentButton3')
                        8 STORE_NAME               2 (__qualname__)
          
-         436          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 436>)
+         461          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 461>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundAccentButton3'
             code
@@ -3173,59 +3232,59 @@
                nlocals   : 1
                stacksize : 14
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   026403640464056406640764046405640664089c0464096409640a640664
                   089c04640b9c076901a6010000ab010000000000000000010064005300
-               436           0 RESUME                   0
+               461           0 RESUME                   0
                
-               437           2 LOAD_FAST                0 (self)
+               462           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               439          26 LOAD_CONST               1 ('button')
+               464          26 LOAD_CONST               1 ('button')
                
-               440          28 LOAD_CONST               2 (8)
+               465          28 LOAD_CONST               2 (8)
                
-               441          30 LOAD_CONST               3 ('#0067c0')
+               466          30 LOAD_CONST               3 ('#0067c0')
                
-               442          32 LOAD_CONST               4 ('#1473c5')
+               467          32 LOAD_CONST               4 ('#1473c5')
                
-               443          34 LOAD_CONST               5 ('#ffffff')
+               468          34 LOAD_CONST               5 ('#ffffff')
                
-               444          36 LOAD_CONST               6 (1)
+               469          36 LOAD_CONST               6 (1)
                
-               447          38 LOAD_CONST               7 ('#1975c5')
+               472          38 LOAD_CONST               7 ('#1975c5')
                
-               448          40 LOAD_CONST               4 ('#1473c5')
+               473          40 LOAD_CONST               4 ('#1473c5')
                
-               449          42 LOAD_CONST               5 ('#ffffff')
+               474          42 LOAD_CONST               5 ('#ffffff')
                
-               450          44 LOAD_CONST               6 (1)
+               475          44 LOAD_CONST               6 (1)
                
-               446          46 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
+               471          46 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
                             48 BUILD_CONST_KEY_MAP      4
                
-               454          50 LOAD_CONST               9 ('#3284cb')
+               479          50 LOAD_CONST               9 ('#3284cb')
                
-               455          52 LOAD_CONST               9 ('#3284cb')
+               480          52 LOAD_CONST               9 ('#3284cb')
                
-               456          54 LOAD_CONST              10 ('#fdfdfd')
+               481          54 LOAD_CONST              10 ('#fdfdfd')
                
-               457          56 LOAD_CONST               6 (1)
+               482          56 LOAD_CONST               6 (1)
                
-               453          58 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
+               478          58 LOAD_CONST               8 (('back', 'border', 'text_back', 'border_width'))
                             60 BUILD_CONST_KEY_MAP      4
                
-               439          62 LOAD_CONST              11 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
+               464          62 LOAD_CONST              11 (('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed'))
                             64 BUILD_CONST_KEY_MAP      7
                
-               438          66 BUILD_MAP                1
+               463          66 BUILD_MAP                1
                
-               437          68 PRECALL                  1
+               462          68 PRECALL                  1
                             72 CALL                     1
                             82 POP_TOP
                             84 LOAD_CONST               0 (None)
                             86 RETURN_VALUE
                consts
                   None
                   'button'
@@ -3241,111 +3300,111 @@
                   ('radius', 'back', 'border', 'text_back', 'border_width', 'active', 'pressed')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 436
+               firstlineno 461
                lnotab
                   0x0201180202010201020102010201020302010201020102fc0408020102
                   01020102fc04f204ff02ff
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawRoundAccentButton3'
-         firstlineno 435
+         firstlineno 460
          lnotab 0x0a01
       'AdwDrawRoundAccentButton3'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         464           0 RESUME                   0
+         489           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundDarkButton3')
                        8 STORE_NAME               2 (__qualname__)
          
-         465          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 465>)
+         490          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 490>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundDarkButton3'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               465           0 RESUME                   0
+               490           0 RESUME                   0
                
-               466           2 LOAD_FAST                0 (self)
+               491           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 465
+               firstlineno 490
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawRoundDarkButton3'
-         firstlineno 464
+         firstlineno 489
          lnotab 0x0a01
       'AdwDrawRoundDarkButton3'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 3
          flags     : 0
          code
             0x8700970065005a0164005a026401640164029c02880066016403840a5a
             03640484005a04880078015a055300
                        0 MAKE_CELL                0 (__class__)
          
-         470           2 RESUME                   0
+         495           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawBasicCircularButton')
                       10 STORE_NAME               2 (__qualname__)
          
-         471          12 LOAD_CONST               1 (120)
+         496          12 LOAD_CONST               1 (120)
                       14 LOAD_CONST               1 (120)
                       16 LOAD_CONST               2 (('width', 'height'))
                       18 BUILD_CONST_KEY_MAP      2
                       20 LOAD_CLOSURE             0 (__class__)
                       22 BUILD_TUPLE              1
-                      24 LOAD_CONST               3 (<code object __init__, file "D:\tkadw\tkadw\canvas\button.py", line 471>)
+                      24 LOAD_CONST               3 (<code object __init__, file "D:\tkadw\tkadw\canvas\button.py", line 496>)
                       26 MAKE_FUNCTION           10 (kwdefaults, closure)
                       28 STORE_NAME               3 (__init__)
          
-         474          30 LOAD_CONST               4 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 474>)
+         499          30 LOAD_CONST               4 (<code object _draw, file "D:\tkadw\tkadw\canvas\button.py", line 499>)
                       32 MAKE_FUNCTION            0
                       34 STORE_NAME               4 (_draw)
                       36 LOAD_CLOSURE             0 (__class__)
                       38 COPY                     1
                       40 STORE_NAME               5 (__classcell__)
                       42 RETURN_VALUE
          consts
@@ -3359,17 +3418,17 @@
                flags     : 15
                code
                   0x950197000200740100000000000000000000a6000000ab000000000000
                   0000006a0100000000000000007c037c017c0264019c027c04a4018e0101
                   0064005300
                              0 COPY_FREE_VARS           1
                
-               471           2 RESUME                   0
+               496           2 RESUME                   0
                
-               472           4 PUSH_NULL
+               497           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                3 (args)
                             44 LOAD_FAST                1 (width)
                             46 LOAD_FAST                2 (height)
@@ -3386,15 +3445,15 @@
                   ('width', 'height')
                names      ('super', '__init__')
                varnames   ('self', 'width', 'height', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '__init__'
-               firstlineno 471
+               firstlineno 496
                lnotab 0x0401
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 9
                flags     : 3
                code
@@ -3408,80 +3467,80 @@
                   0000007c005f0700000000000000007c00a0080000000000000000000000
                   0000000000000000007c00a0020000000000000000000000000000000000
                   000000a6000000ab00000000000000000064057a0b00007c00a003000000
                   0000000000000000000000000000000000a6000000ab0000000000000000
                   0064057a0b00007c006a0900000000000000007c006a0a00000000000000
                   007c006a0b0000000000000000ac06a6050000ab0500000000000000007c
                   005f0c000000000000000064005300
-               474           0 RESUME                   0
+               499           0 RESUME                   0
                
-               475           2 LOAD_FAST                0 (self)
+               500           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               477          44 LOAD_FAST                0 (self)
+               503          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_oval)
                
-               478          68 LOAD_CONST               2 (1.5)
+               504          68 LOAD_CONST               2 (1.5)
                             70 LOAD_CONST               2 (1.5)
                             72 LOAD_FAST                0 (self)
                             74 LOAD_METHOD              2 (winfo_width)
                             96 PRECALL                  0
                            100 CALL                     0
                            110 LOAD_CONST               3 (3)
                            112 BINARY_OP               10 (-)
                            116 LOAD_FAST                0 (self)
                            118 LOAD_METHOD              3 (winfo_height)
                            140 PRECALL                  0
                            144 CALL                     0
                            154 LOAD_CONST               3 (3)
                            156 BINARY_OP               10 (-)
                
-               479         160 LOAD_FAST                0 (self)
+               505         160 LOAD_FAST                0 (self)
                            162 LOAD_ATTR                4 (button_border_width)
                
-               480         172 LOAD_FAST                0 (self)
+               506         172 LOAD_FAST                0 (self)
                            174 LOAD_ATTR                5 (_button_border)
                            184 LOAD_FAST                0 (self)
                            186 LOAD_ATTR                6 (_button_back)
                
-               477         196 KW_NAMES                 4
+               503         196 KW_NAMES                 4
                            198 PRECALL                  7
                            202 CALL                     7
                            212 LOAD_FAST                0 (self)
                            214 STORE_ATTR               7 (button_frame)
                
-               483         224 LOAD_FAST                0 (self)
+               510         224 LOAD_FAST                0 (self)
                            226 LOAD_METHOD              8 (create_text)
                
-               484         248 LOAD_FAST                0 (self)
+               511         248 LOAD_FAST                0 (self)
                            250 LOAD_METHOD              2 (winfo_width)
                            272 PRECALL                  0
                            276 CALL                     0
                            286 LOAD_CONST               5 (2)
                            288 BINARY_OP               11 (/)
                            292 LOAD_FAST                0 (self)
                            294 LOAD_METHOD              3 (winfo_height)
                            316 PRECALL                  0
                            320 CALL                     0
                            330 LOAD_CONST               5 (2)
                            332 BINARY_OP               11 (/)
                
-               485         336 LOAD_FAST                0 (self)
+               512         336 LOAD_FAST                0 (self)
                            338 LOAD_ATTR                9 (text)
                            348 LOAD_FAST                0 (self)
                            350 LOAD_ATTR               10 (_button_text_back)
                
-               486         360 LOAD_FAST                0 (self)
+               513         360 LOAD_FAST                0 (self)
                            362 LOAD_ATTR               11 (button_text_font)
                
-               483         372 KW_NAMES                 6
+               510         372 KW_NAMES                 6
                            374 PRECALL                  5
                            378 CALL                     5
                            388 LOAD_FAST                0 (self)
                            390 STORE_ATTR              12 (button_text)
                            400 LOAD_CONST               0 (None)
                            402 RETURN_VALUE
                consts
@@ -3494,135 +3553,135 @@
                   ('text', 'fill', 'font')
                names      ('delete', 'create_oval', 'winfo_width', 'winfo_height', 'button_border_width', '_button_border', '_button_back', 'button_frame', 'create_text', 'text', '_button_text_back', 'button_text_font', 'button_text')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       '_draw'
-               firstlineno 474
-               lnotab 0x02012a0218015c010c0118fd1c061801580118010cfd
+               firstlineno 499
+               lnotab 0x02012a0318015c010c0118fd1c071801580118010cfd
          names      ('__name__', '__module__', '__qualname__', '__init__', '_draw', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawBasicCircularButton'
-         firstlineno 470
+         firstlineno 495
          lnotab 0x0c011203
       'AdwDrawBasicCircularButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         490           0 RESUME                   0
+         517           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawCircularButton')
                        8 STORE_NAME               2 (__qualname__)
          
-         491          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 491>)
+         518          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 518>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawCircularButton'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               491           0 RESUME                   0
+               518           0 RESUME                   0
                
-               492           2 LOAD_FAST                0 (self)
+               519           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 491
+               firstlineno 518
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawCircularButton'
-         firstlineno 490
+         firstlineno 517
          lnotab 0x0a01
       'AdwDrawCircularButton'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         495           0 RESUME                   0
+         522           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawCircularDarkButton')
                        8 STORE_NAME               2 (__qualname__)
          
-         496          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 496>)
+         523          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\button.py", line 523>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawCircularDarkButton'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               496           0 RESUME                   0
+               523           0 RESUME                   0
                
-               497           2 LOAD_FAST                0 (self)
+               524           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
                name       'default_palette'
-               firstlineno 496
+               firstlineno 523
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       'AdwDrawCircularDarkButton'
-         firstlineno 495
+         firstlineno 522
          lnotab 0x0a01
       'AdwDrawCircularDarkButton'
       '__main__'
       ('Tk',)
       'Hello'
       ('text',)
       '<<Click>>'
@@ -3630,139 +3689,139 @@
          argcount  : 1
          nlocals   : 1
          stacksize : 3
          flags     : 3
          code
             0x97007401000000000000000000006401a6010000ab0100000000000000
             005300
-         506           0 RESUME                   0
+         533           0 RESUME                   0
                        2 LOAD_GLOBAL              1 (NULL + print)
                       14 LOAD_CONST               1 ('button clicked')
                       16 PRECALL                  1
                       20 CALL                     1
                       30 RETURN_VALUE
          consts
             None
             'button clicked'
          names      ('print',)
          varnames   ('evt',)
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       '<lambda>'
-         firstlineno 506
+         firstlineno 533
          lnotab 0x
       'x'
       5
       ('fill', 'padx', 'pady')
       code
          argcount  : 1
          nlocals   : 1
          stacksize : 3
          flags     : 3
          code
             0x97007401000000000000000000006401a6010000ab0100000000000000
             005300
-         510           0 RESUME                   0
+         537           0 RESUME                   0
                        2 LOAD_GLOBAL              1 (NULL + print)
                       14 LOAD_CONST               1 ('button4 clicked')
                       16 PRECALL                  1
                       20 CALL                     1
                       30 RETURN_VALUE
          consts
             None
             'button4 clicked'
          names      ('print',)
          varnames   ('evt',)
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       '<lambda>'
-         firstlineno 510
+         firstlineno 537
          lnotab 0x
       code
          argcount  : 1
          nlocals   : 1
          stacksize : 3
          flags     : 3
          code
             0x97007401000000000000000000006401a6010000ab0100000000000000
             005300
-         514           0 RESUME                   0
+         541           0 RESUME                   0
                        2 LOAD_GLOBAL              1 (NULL + print)
                       14 LOAD_CONST               1 ('button4 clicked')
                       16 PRECALL                  1
                       20 CALL                     1
                       30 RETURN_VALUE
          consts
             None
             'button4 clicked'
          names      ('print',)
          varnames   ('evt',)
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       '<lambda>'
-         firstlineno 514
+         firstlineno 541
          lnotab 0x
       code
          argcount  : 1
          nlocals   : 1
          stacksize : 3
          flags     : 3
          code
             0x97007401000000000000000000006401a6010000ab0100000000000000
             005300
-         518           0 RESUME                   0
+         545           0 RESUME                   0
                        2 LOAD_GLOBAL              1 (NULL + print)
                       14 LOAD_CONST               1 ('button4 clicked')
                       16 PRECALL                  1
                       20 CALL                     1
                       30 RETURN_VALUE
          consts
             None
             'button4 clicked'
          names      ('print',)
          varnames   ('evt',)
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       '<lambda>'
-         firstlineno 518
+         firstlineno 545
          lnotab 0x
       code
          argcount  : 1
          nlocals   : 1
          stacksize : 3
          flags     : 3
          code
             0x97007401000000000000000000006401a6010000ab0100000000000000
             005300
-         522           0 RESUME                   0
+         549           0 RESUME                   0
                        2 LOAD_GLOBAL              1 (NULL + print)
                       14 LOAD_CONST               1 ('button6 clicked')
                       16 PRECALL                  1
                       20 CALL                     1
                       30 RETURN_VALUE
          consts
             None
             'button6 clicked'
          names      ('print',)
          varnames   ('evt',)
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
          name       '<lambda>'
-         firstlineno 522
+         firstlineno 549
          lnotab 0x
       None
    names      ('tkinter.font', 'Font', 'nametofont', 'tkadw.canvas.drawengine', 'AdwDrawEngine', 'AdwDrawBasicButton', 'AdwDrawButton', 'AdwDrawDarkButton', 'AdwDrawAccentButton', 'AdwDrawBasicRoundButton', 'AdwDrawRoundButton', 'AdwDrawRoundAccentButton', 'AdwDrawRoundDarkButton', 'AdwDrawRoundButton2', 'AdwDrawRoundAccentButton2', 'AdwDrawRoundDarkButton2', 'AdwDrawRoundButton3', 'AdwDrawRoundAccentButton3', 'AdwDrawRoundDarkButton3', 'AdwDrawBasicCircularButton', 'AdwDrawCircularButton', 'AdwDrawCircularDarkButton', '__name__', 'tkinter', 'Tk', 'root', 'button', 'bind', 'pack', 'button4', 'button7', 'button10', 'button13', 'mainloop')
    varnames   ()
    freevars   ()
    cellvars   ()
    filename   'D:\\tkadw\\tkadw\\canvas\\button.py'
    name       '<module>'
    firstlineno 1
    lnotab
-      0x00ff020110010c041c7f003d1c051c051c1d1c551c051c1d1c051c161c
-      1d1c051c161c1d1c061c141c051c050e010c02140218012e01300218012e
+      0x00ff020110010c041c7f00481c051c051c1d1c5a1c051c1d1c051c1a1c
+      1d1c051c1b1c1d1c061c161c051c050e010c02140218012e01300218012e
       01300218012e01300218012e01300218012e0130022ce7
```

### Comparing `tkadw-0.2.1/tkadw/canvas/__pycache__/button.cpython-38.pyc` & `tkadw-0.2.2/tkadw/canvas/__pycache__/button.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/canvas/__pycache__/drawengine.cpython-311.pyc` & `tkadw-0.2.2/tkadw/canvas/__pycache__/drawengine.cpython-311.pyc`

 * *Files 4% similar despite different names*

#### Python bytecode

```diff
@@ -1,247 +1,322 @@
 magic:    0xa70d0d0a
-moddate:  0x186d9564 (Fri Jun 23 09:59:52 2023 UTC)
-files sz: 20930
+moddate:  0x5c6a9664 (Sat Jun 24 04:00:28 2023 UTC)
+files sz: 21612
 code
    argcount  : 0
    nlocals   : 0
    stacksize : 8
    flags     : 0
    code
-      0x9700640064016c006d015a01010064025a0264035a0302004700640484
-      0064056501a6030000ab0300000000000000005a04650564066b02000000
-      007291640064076c006d065a06010002006506a6000000ab000000000000
-      0000005a0702006504a6000000ab0000000000000000005a086508a00900
-      00000000000000000000000000000000000000640864096409640a640a64
-      0ba6060000ab06000000000000000001006508a00a000000000000000000
-      0000000000000000000000640c640c640d640d640ba6050000ab05000000
-      000000000001006508a00b00000000000000000000000000000000000000
-      00640e640f8400a6020000ab02000000000000000001006508a00c000000
-      000000000000000000000000000000000064106411ac12a6020000ab0200
-      0000000000000001006507a00d0000000000000000000000000000000000
-      000000a6000000ab00000000000000000001006413530064135300
+      0x9700640064016c006d015a010100640284005a0264035a0364045a0402
+      0047006405840064066501a6030000ab0300000000000000005a05650664
+      076b0200000000727b640064086c006d075a07010002006507a6000000ab
+      0000000000000000005a0802006505a6000000ab0000000000000000005a
+      096509a00a00000000000000000000000000000000000000006409640964
+      0a640a640ba6050000ab05000000000000000001006509a00b0000000000
+      000000000000000000000000000000640b640b640c640c640d640eac0fa6
+      060000ab06000000000000000001006509a00c0000000000000000000000
+      00000000000000000064106411ac12a6020000ab02000000000000000001
+      006508a00d0000000000000000000000000000000000000000a6000000ab
+      00000000000000000001006413530064135300
      0           0 RESUME                   0
    
      1           2 LOAD_CONST               0 (0)
                  4 LOAD_CONST               1 (('Canvas',))
                  6 IMPORT_NAME              0 (tkinter)
                  8 IMPORT_FROM              1 (Canvas)
                 10 STORE_NAME               1 (Canvas)
                 12 POP_TOP
    
-     3          14 LOAD_CONST               2 ('\n# poly.tcl\n\nproc poly_round {win outline fill args} {\n    if {[llength $args] % 3 != 0 || [llength $args] < 9} {\n        error "wrong # args: should be "poly_round                win outline fill x1 y1 d1 x2 y2 d2 x3 y3 d3 ?...?""\n    }\n\n    # Determine the tag to use.\n    if {![info exists ::poly_next_id]} {\n        set ::poly_next_id 1\n    }\n    set tag poly#$::poly_next_id\n    incr ::poly_next_id\n\n    # Filter out illegal circles and collinear points.\n    set pts [list]\n    lassign [lrange $args 0 4] Ux Uy d Vx Vy\n    foreach {d Wx Wy} [concat [lrange $args 5 end] [lrange $args 0 4]] {\n        set test [expr {$Ux * ($Vy - $Wy) - $Vx * ($Uy - $Wy) +\n                $Wx * ($Uy - $Vy)}]\n        if {($d > 0) && $test != 0} {\n            lappend pts $Vx $Vy $d $test\n            lassign [list $Wx $Wy $Vx $Vy] Vx Vy Ux Uy\n        } else {\n            lassign [list $Wx $Wy] Vx Vy\n        }\n    }\n\n    # V    C    T   W\n    #  *---*----*-+-*-- Given: U, V, W, d\n    #  |\\ /    /|_|     Find:  S, E, T\n    #  | *B   / |\n    #  |/ \\  /  |       The length of ES and ET each is d.\n    # A*   \\/   |\n    #  |   /\\   |       VB bisects angle UVW.  SE _|_ VU; TE _|_ VW.\n    #  |  /  \\  |       B is halfway between A and C.\n    #  | /    \\ |       Angles UVW and SET are not necessarily right.\n    #  |/      \\|       The length of AV and CV each is 1.\n    # S*-+------*E\n    #  |_|       \\      The new polygon is along USTW.\n    # U*          \\     The new arc has center E, radius d, and angle SET, and\n    #  |           \\    it is tangential to VU at S and VW at T.\n\n    # Calculate new polygon vertices and create arcs.\n    set coords [list]\n    lassign [lrange $pts 0 5] Ux Uy d test Vx Vy\n    foreach {d test Wx Wy} [concat [lrange $pts 6 end] [lrange $pts 0 5]] {\n        # Find A and C.\n        foreach {pt x y} [list A $Ux $Uy C $Wx $Wy] {\n            set      k [expr {sqrt(($Vx - $x) ** 2 + ($Vy - $y) ** 2)}]\n            set ${pt}x [expr {($x - $Vx) / $k + $Vx}]\n            set ${pt}y [expr {($y - $Vy) / $k + $Vy}]\n        }\n\n        # Find B.\n        set Bx [expr {($Ax + $Cx) / 2.0}]\n        set By [expr {($Ay + $Cy) / 2.0}]\n\n        # Find the parameters for lines VB and VW.\n        foreach {pt x y} [list B $Bx $By W $Wx $Wy] {\n            set       k [expr {sqrt(($Vx - $x) ** 2 + ($Vy - $y) ** 2)}]\n            set V${pt}a [expr {+($Vy - $y) / $k}]\n            set V${pt}b [expr {-($Vx - $x) / $k}]\n            set V${pt}c [expr {($Vx * $y - $Vy * $x) / $k}]\n        }\n\n        # Find point E.\n        set sign [expr {$test < 0 ? -1 : +1}]\n        set  k [expr {$VWa * $VBb - $VWb * $VBa}]\n        set Ex [expr {(+$VWb * $VBc - ($VWc - $d * $sign) * $VBb) / $k}]\n        set Ey [expr {(-$VWa * $VBc + ($VWc - $d * $sign) * $VBa) / $k}]\n\n        # Find tangent points S and T.\n        foreach {pt x y} [list S $Ux $Uy T $Wx $Wy] {\n            set      k [expr {($Vx - $x) ** 2 + ($Vy - $y) ** 2}]\n            set ${pt}x [expr {($Ex * ($Vx - $x) ** 2 + ($Vy - $y) *\n                              ($Ey * ($Vx - $x) - $Vx * $y + $Vy * $x)) / $k}]\n            set ${pt}y [expr {($Ex * ($Vx - $x) * ($Vy - $y) +\n                              ($Ey * ($Vy - $y) ** 2 + ($Vx - $x) *\n                              ($Vx * $y - $Vy * $x))) / $k}]\n        }\n\n        # Find directions for lines ES and ET.\n        foreach {pt x y} [list S $Sx $Sy T $Tx $Ty] {\n            set E${pt}d [expr {atan2($Ey - $y, $x - $Ex)}]\n        }\n\n        # Find start and extent directions.\n        if {$ESd < 0 && $ETd > 0} {\n            set start  [expr {180 / acos(-1) * $ETd}]\n            set extent [expr {180 / acos(-1) * ($ESd - $ETd)}]\n            if {$sign > 0} {\n                set extent [expr {$extent + 360}]\n            }\n        } else {\n            set start  [expr {180 / acos(-1) * $ESd}]\n            set extent [expr {180 / acos(-1) * ($ETd - $ESd)}]\n            if {$sign < 0 && $ESd > 0 && $ETd < 0} {\n                set extent [expr {$extent + 360}]\n            }\n        }\n\n        # Draw arc.\n        set opts [list                                             [expr {$Ex - $d}] [expr {$Ey - $d}]                [expr {$Ex + $d}] [expr {$Ey + $d}]                -start $start -extent $extent]\n        $win create arc {*}$opts -style pie -tags [list $tag pie]\n        $win create arc {*}$opts -style arc -tags [list $tag arc]\n\n        # Draw border line.\n        if {[info exists prevx]} {\n            $win create line $prevx $prevy $Sx $Sy -tags [list $tag line]\n        } else {\n            lassign [list $Sx $Sy] firstx firsty\n        }\n        lassign [list $Tx $Ty] prevx prevy\n\n        # Remember coordinates for polygon.\n        lappend coords $Sx $Sy $Tx $Ty\n\n        # Rotate vertices.\n        lassign [list $Wx $Wy $Vx $Vy] Vx Vy Ux Uy\n    }\n\n    # Draw final border line.\n    $win create line $prevx $prevy $firstx $firsty -tags [list $tag line]\n\n    # Draw fill polygon.\n    $win create polygon {*}$coords -tags [list $tag poly]\n\n    # Configure colors.\n    $win itemconfigure $tag&&(poly||pie) -fill $fill\n    $win itemconfigure $tag&&pie         -outline ""\n    $win itemconfigure $tag&&line        -fill $outline -capstyle round\n    $win itemconfigure $tag&&arc         -outline $outline\n\n    # Set proper stacking order.\n    $win raise $tag&&poly\n    $win raise $tag&&pie\n    $win raise $tag&&(line||arc)\n\n    return $tag\n}\n       ')
-                16 STORE_NAME               2 (poly)
+     3          14 LOAD_CONST               2 (<code object rounded_rectangle, file "D:\tkadw\tkadw\canvas\drawengine.py", line 3>)
+                16 MAKE_FUNCTION            0
+                18 STORE_NAME               2 (rounded_rectangle)
    
-   151          18 LOAD_CONST               3 ('\n #----------------------------------------------------------------------\n #\n # RoundPoly -- Draw a polygon with rounded corners in the canvas, based\n # off of ideas and code from "Drawing rounded rectangles"\n #\n # Parameters:\n #       w - Path name of the canvas\n #       xy - list of coordinates of the vertices of the polygon\n #       radii - list of radius of the bend each each vertex\n #       args - Other args suitable to a \'polygon\' item on the canvas\n #\n # Results:\n #       Returns the canvas item number of the rounded polygon.\n #\n # Side effects:\n #       Creates a rounded polygon in the canvas.\n #\n #----------------------------------------------------------------------\n \n proc RoundPoly {w xy radii args} {\n    set lenXY [llength $xy]\n    set lenR [llength $radii]\n    if {$lenXY != 2 * $lenR} {\n        error "wrong number of vertices and radii"\n    }\n \n    # Walk down vertices keeping previous, current and next\n    lassign [lrange $xy end-1 end] x0 y0\n    lassign $xy x1 y1\n    eval lappend xy [lrange $xy 0 1]\n    set knots {}                                ;# These are the control points\n \n    for {set i 0} {$i < $lenXY} {incr i 2} {\n        set radius [lindex $radii [expr {$i/2}]]\n        set r [winfo pixels $w $radius]\n \n        lassign [lrange $xy [expr {$i + 2}] [expr {$i + 3}]] x2 y2\n        set z [_RoundPoly2 $x0 $y0 $x1 $y1 $x2 $y2 $r]\n        eval lappend knots $z\n \n        lassign [list $x1 $y1] x0 y0           ;# Current becomes previous\n        lassign [list $x2 $y2] x1 y1           ;# Next becomes current\n    }\n    set n [eval $w create polygon $knots -smooth 1 $args]\n    return $n\n }\n proc _RoundPoly2 {x0 y0 x1 y1 x2 y2 radius} {\n    set d [expr { 2 * $radius }]\n    set maxr 0.75\n \n    set v1x [expr {$x0 - $x1}]\n    set v1y [expr {$y0 - $y1}]\n    set v2x [expr {$x2 - $x1}]\n    set v2y [expr {$y2 - $y1}]\n \n    set vlen1 [expr {sqrt($v1x*$v1x + $v1y*$v1y)}]\n    set vlen2 [expr {sqrt($v2x*$v2x + $v2y*$v2y)}]\n    if {$d > $maxr * $vlen1} {\n        set d [expr {$maxr * $vlen1}]\n    }\n    if {$d > $maxr * $vlen2} {\n        set d [expr {$maxr * $vlen2}]\n    }\n \n    lappend xy [expr {$x1 + $d * $v1x/$vlen1}] [expr {$y1 + $d * $v1y/$vlen1}]\n    lappend xy $x1 $y1\n    lappend xy [expr {$x1 + $d * $v2x/$vlen2}] [expr {$y1 + $d * $v2y/$vlen2}]\n \n    return $xy\n }\n\n')
-                20 STORE_NAME               3 (poly2)
+    10          20 LOAD_CONST               3 ('\n# poly.tcl\n\nproc poly_round {win outline fill args} {\n    if {[llength $args] % 3 != 0 || [llength $args] < 9} {\n        error "wrong # args: should be "poly_round                win outline fill x1 y1 d1 x2 y2 d2 x3 y3 d3 ?...?""\n    }\n\n    # Determine the tag to use.\n    if {![info exists ::poly_next_id]} {\n        set ::poly_next_id 1\n    }\n    set tag poly#$::poly_next_id\n    incr ::poly_next_id\n\n    # Filter out illegal circles and collinear points.\n    set pts [list]\n    lassign [lrange $args 0 4] Ux Uy d Vx Vy\n    foreach {d Wx Wy} [concat [lrange $args 5 end] [lrange $args 0 4]] {\n        set test [expr {$Ux * ($Vy - $Wy) - $Vx * ($Uy - $Wy) +\n                $Wx * ($Uy - $Vy)}]\n        if {($d > 0) && $test != 0} {\n            lappend pts $Vx $Vy $d $test\n            lassign [list $Wx $Wy $Vx $Vy] Vx Vy Ux Uy\n        } else {\n            lassign [list $Wx $Wy] Vx Vy\n        }\n    }\n\n    # V    C    T   W\n    #  *---*----*-+-*-- Given: U, V, W, d\n    #  |\\ /    /|_|     Find:  S, E, T\n    #  | *B   / |\n    #  |/ \\  /  |       The length of ES and ET each is d.\n    # A*   \\/   |\n    #  |   /\\   |       VB bisects angle UVW.  SE _|_ VU; TE _|_ VW.\n    #  |  /  \\  |       B is halfway between A and C.\n    #  | /    \\ |       Angles UVW and SET are not necessarily right.\n    #  |/      \\|       The length of AV and CV each is 1.\n    # S*-+------*E\n    #  |_|       \\      The new polygon is along USTW.\n    # U*          \\     The new arc has center E, radius d, and angle SET, and\n    #  |           \\    it is tangential to VU at S and VW at T.\n\n    # Calculate new polygon vertices and create arcs.\n    set coords [list]\n    lassign [lrange $pts 0 5] Ux Uy d test Vx Vy\n    foreach {d test Wx Wy} [concat [lrange $pts 6 end] [lrange $pts 0 5]] {\n        # Find A and C.\n        foreach {pt x y} [list A $Ux $Uy C $Wx $Wy] {\n            set      k [expr {sqrt(($Vx - $x) ** 2 + ($Vy - $y) ** 2)}]\n            set ${pt}x [expr {($x - $Vx) / $k + $Vx}]\n            set ${pt}y [expr {($y - $Vy) / $k + $Vy}]\n        }\n\n        # Find B.\n        set Bx [expr {($Ax + $Cx) / 2.0}]\n        set By [expr {($Ay + $Cy) / 2.0}]\n\n        # Find the parameters for lines VB and VW.\n        foreach {pt x y} [list B $Bx $By W $Wx $Wy] {\n            set       k [expr {sqrt(($Vx - $x) ** 2 + ($Vy - $y) ** 2)}]\n            set V${pt}a [expr {+($Vy - $y) / $k}]\n            set V${pt}b [expr {-($Vx - $x) / $k}]\n            set V${pt}c [expr {($Vx * $y - $Vy * $x) / $k}]\n        }\n\n        # Find point E.\n        set sign [expr {$test < 0 ? -1 : +1}]\n        set  k [expr {$VWa * $VBb - $VWb * $VBa}]\n        set Ex [expr {(+$VWb * $VBc - ($VWc - $d * $sign) * $VBb) / $k}]\n        set Ey [expr {(-$VWa * $VBc + ($VWc - $d * $sign) * $VBa) / $k}]\n\n        # Find tangent points S and T.\n        foreach {pt x y} [list S $Ux $Uy T $Wx $Wy] {\n            set      k [expr {($Vx - $x) ** 2 + ($Vy - $y) ** 2}]\n            set ${pt}x [expr {($Ex * ($Vx - $x) ** 2 + ($Vy - $y) *\n                              ($Ey * ($Vx - $x) - $Vx * $y + $Vy * $x)) / $k}]\n            set ${pt}y [expr {($Ex * ($Vx - $x) * ($Vy - $y) +\n                              ($Ey * ($Vy - $y) ** 2 + ($Vx - $x) *\n                              ($Vx * $y - $Vy * $x))) / $k}]\n        }\n\n        # Find directions for lines ES and ET.\n        foreach {pt x y} [list S $Sx $Sy T $Tx $Ty] {\n            set E${pt}d [expr {atan2($Ey - $y, $x - $Ex)}]\n        }\n\n        # Find start and extent directions.\n        if {$ESd < 0 && $ETd > 0} {\n            set start  [expr {180 / acos(-1) * $ETd}]\n            set extent [expr {180 / acos(-1) * ($ESd - $ETd)}]\n            if {$sign > 0} {\n                set extent [expr {$extent + 360}]\n            }\n        } else {\n            set start  [expr {180 / acos(-1) * $ESd}]\n            set extent [expr {180 / acos(-1) * ($ETd - $ESd)}]\n            if {$sign < 0 && $ESd > 0 && $ETd < 0} {\n                set extent [expr {$extent + 360}]\n            }\n        }\n\n        # Draw arc.\n        set opts [list                                             [expr {$Ex - $d}] [expr {$Ey - $d}]                [expr {$Ex + $d}] [expr {$Ey + $d}]                -start $start -extent $extent]\n        $win create arc {*}$opts -style pie -tags [list $tag pie]\n        $win create arc {*}$opts -style arc -tags [list $tag arc]\n\n        # Draw border line.\n        if {[info exists prevx]} {\n            $win create line $prevx $prevy $Sx $Sy -tags [list $tag line]\n        } else {\n            lassign [list $Sx $Sy] firstx firsty\n        }\n        lassign [list $Tx $Ty] prevx prevy\n\n        # Remember coordinates for polygon.\n        lappend coords $Sx $Sy $Tx $Ty\n\n        # Rotate vertices.\n        lassign [list $Wx $Wy $Vx $Vy] Vx Vy Ux Uy\n    }\n\n    # Draw final border line.\n    $win create line $prevx $prevy $firstx $firsty -tags [list $tag line]\n\n    # Draw fill polygon.\n    $win create polygon {*}$coords -tags [list $tag poly]\n\n    # Configure colors.\n    $win itemconfigure $tag&&(poly||pie) -fill $fill\n    $win itemconfigure $tag&&pie         -outline ""\n    $win itemconfigure $tag&&line        -fill $outline -capstyle round\n    $win itemconfigure $tag&&arc         -outline $outline\n\n    # Set proper stacking order.\n    $win raise $tag&&poly\n    $win raise $tag&&pie\n    $win raise $tag&&(line||arc)\n\n    return $tag\n}\n       ')
+                22 STORE_NAME               3 (poly)
    
-   226          22 PUSH_NULL
-                24 LOAD_BUILD_CLASS
-                26 LOAD_CONST               4 (<code object AdwDrawEngine, file "D:\tkadw\tkadw\canvas\drawengine.py", line 226>)
-                28 MAKE_FUNCTION            0
-                30 LOAD_CONST               5 ('AdwDrawEngine')
-                32 LOAD_NAME                1 (Canvas)
-                34 PRECALL                  3
-                38 CALL                     3
-                48 STORE_NAME               4 (AdwDrawEngine)
+   158          24 LOAD_CONST               4 ('\n #----------------------------------------------------------------------\n #\n # RoundPoly -- Draw a polygon with rounded corners in the canvas, based\n # off of ideas and code from "Drawing rounded rectangles"\n #\n # Parameters:\n #       w - Path name of the canvas\n #       xy - list of coordinates of the vertices of the polygon\n #       radii - list of radius of the bend each each vertex\n #       args - Other args suitable to a \'polygon\' item on the canvas\n #\n # Results:\n #       Returns the canvas item number of the rounded polygon.\n #\n # Side effects:\n #       Creates a rounded polygon in the canvas.\n #\n #----------------------------------------------------------------------\n \n proc RoundPoly {w xy radii args} {\n    set lenXY [llength $xy]\n    set lenR [llength $radii]\n    if {$lenXY != 2 * $lenR} {\n        error "wrong number of vertices and radii"\n    }\n \n    # Walk down vertices keeping previous, current and next\n    lassign [lrange $xy end-1 end] x0 y0\n    lassign $xy x1 y1\n    eval lappend xy [lrange $xy 0 1]\n    set knots {}                                ;# These are the control points\n \n    for {set i 0} {$i < $lenXY} {incr i 2} {\n        set radius [lindex $radii [expr {$i/2}]]\n        set r [winfo pixels $w $radius]\n \n        lassign [lrange $xy [expr {$i + 2}] [expr {$i + 3}]] x2 y2\n        set z [_RoundPoly2 $x0 $y0 $x1 $y1 $x2 $y2 $r]\n        eval lappend knots $z\n \n        lassign [list $x1 $y1] x0 y0           ;# Current becomes previous\n        lassign [list $x2 $y2] x1 y1           ;# Next becomes current\n    }\n    set n [eval $w create polygon $knots -smooth 1 $args]\n    return $n\n }\n proc _RoundPoly2 {x0 y0 x1 y1 x2 y2 radius} {\n    set d [expr { 2 * $radius }]\n    set maxr 0.75\n \n    set v1x [expr {$x0 - $x1}]\n    set v1y [expr {$y0 - $y1}]\n    set v2x [expr {$x2 - $x1}]\n    set v2y [expr {$y2 - $y1}]\n \n    set vlen1 [expr {sqrt($v1x*$v1x + $v1y*$v1y)}]\n    set vlen2 [expr {sqrt($v2x*$v2x + $v2y*$v2y)}]\n    if {$d > $maxr * $vlen1} {\n        set d [expr {$maxr * $vlen1}]\n    }\n    if {$d > $maxr * $vlen2} {\n        set d [expr {$maxr * $vlen2}]\n    }\n \n    lappend xy [expr {$x1 + $d * $v1x/$vlen1}] [expr {$y1 + $d * $v1y/$vlen1}]\n    lappend xy $x1 $y1\n    lappend xy [expr {$x1 + $d * $v2x/$vlen2}] [expr {$y1 + $d * $v2y/$vlen2}]\n \n    return $xy\n }\n\n')
+                26 STORE_NAME               4 (poly2)
    
-   589          50 LOAD_NAME                5 (__name__)
-                52 LOAD_CONST               6 ('__main__')
-                54 COMPARE_OP               2 (==)
-                60 POP_JUMP_FORWARD_IF_FALSE   145 (to 352)
+   233          28 PUSH_NULL
+                30 LOAD_BUILD_CLASS
+                32 LOAD_CONST               5 (<code object AdwDrawEngine, file "D:\tkadw\tkadw\canvas\drawengine.py", line 233>)
+                34 MAKE_FUNCTION            0
+                36 LOAD_CONST               6 ('AdwDrawEngine')
+                38 LOAD_NAME                1 (Canvas)
+                40 PRECALL                  3
+                44 CALL                     3
+                54 STORE_NAME               5 (AdwDrawEngine)
    
-   590          62 LOAD_CONST               0 (0)
-                64 LOAD_CONST               7 (('Tk',))
-                66 IMPORT_NAME              0 (tkinter)
-                68 IMPORT_FROM              6 (Tk)
-                70 STORE_NAME               6 (Tk)
-                72 POP_TOP
+   604          56 LOAD_NAME                6 (__name__)
+                58 LOAD_CONST               7 ('__main__')
+                60 COMPARE_OP               2 (==)
+                66 POP_JUMP_FORWARD_IF_FALSE   123 (to 314)
    
-   592          74 PUSH_NULL
-                76 LOAD_NAME                6 (Tk)
-                78 PRECALL                  0
-                82 CALL                     0
-                92 STORE_NAME               7 (root)
+   605          68 LOAD_CONST               0 (0)
+                70 LOAD_CONST               8 (('Tk',))
+                72 IMPORT_NAME              0 (tkinter)
+                74 IMPORT_FROM              7 (Tk)
+                76 STORE_NAME               7 (Tk)
+                78 POP_TOP
    
-   594          94 PUSH_NULL
-                96 LOAD_NAME                4 (AdwDrawEngine)
-                98 PRECALL                  0
-               102 CALL                     0
-               112 STORE_NAME               8 (canvas)
+   607          80 PUSH_NULL
+                82 LOAD_NAME                7 (Tk)
+                84 PRECALL                  0
+                88 CALL                     0
+                98 STORE_NAME               8 (root)
    
-   596         114 LOAD_NAME                8 (canvas)
-               116 LOAD_METHOD              9 (create_round_rect3)
-               138 LOAD_CONST               8 (10)
-               140 LOAD_CONST               9 (15)
-               142 LOAD_CONST               9 (15)
-               144 LOAD_CONST              10 (150)
-               146 LOAD_CONST              10 (150)
-               148 LOAD_CONST              11 (50)
-               150 PRECALL                  6
-               154 CALL                     6
-               164 POP_TOP
+   609         100 PUSH_NULL
+               102 LOAD_NAME                5 (AdwDrawEngine)
+               104 PRECALL                  0
+               108 CALL                     0
+               118 STORE_NAME               9 (canvas)
    
-   597         166 LOAD_NAME                8 (canvas)
-               168 LOAD_METHOD             10 (create_round_rect4)
-               190 LOAD_CONST              12 (160)
-               192 LOAD_CONST              12 (160)
-               194 LOAD_CONST              13 (300)
-               196 LOAD_CONST              13 (300)
-               198 LOAD_CONST              11 (50)
-               200 PRECALL                  5
-               204 CALL                     5
-               214 POP_TOP
+   612         120 LOAD_NAME                9 (canvas)
+               122 LOAD_METHOD             10 (create_round_rect4)
+               144 LOAD_CONST               9 (160)
+               146 LOAD_CONST               9 (160)
+               148 LOAD_CONST              10 (300)
+               150 LOAD_CONST              10 (300)
+               152 LOAD_CONST              11 (50)
+               154 PRECALL                  5
+               158 CALL                     5
+               168 POP_TOP
    
-   599         216 LOAD_NAME                8 (canvas)
-               218 LOAD_METHOD             11 (bind)
-               240 LOAD_CONST              14 ('<Configure>')
-               242 LOAD_CONST              15 (<code object <lambda>, file "D:\tkadw\tkadw\canvas\drawengine.py", line 599>)
-               244 MAKE_FUNCTION            0
-               246 PRECALL                  2
-               250 CALL                     2
-               260 POP_TOP
+   614         170 LOAD_NAME                9 (canvas)
+               172 LOAD_METHOD             11 (create_round_rectangle5)
+               194 LOAD_CONST              11 (50)
+               196 LOAD_CONST              11 (50)
+               198 LOAD_CONST              12 (100)
+               200 LOAD_CONST              12 (100)
+               202 LOAD_CONST              13 (16)
+               204 LOAD_CONST              14 ('lightblue')
+               206 KW_NAMES                15
+               208 PRECALL                  6
+               212 CALL                     6
+               222 POP_TOP
    
-   601         262 LOAD_NAME                8 (canvas)
-               264 LOAD_METHOD             12 (pack)
-               286 LOAD_CONST              16 ('both')
-               288 LOAD_CONST              17 ('yes')
-               290 KW_NAMES                18
-               292 PRECALL                  2
-               296 CALL                     2
-               306 POP_TOP
+   618         224 LOAD_NAME                9 (canvas)
+               226 LOAD_METHOD             12 (pack)
+               248 LOAD_CONST              16 ('both')
+               250 LOAD_CONST              17 ('yes')
+               252 KW_NAMES                18
+               254 PRECALL                  2
+               258 CALL                     2
+               268 POP_TOP
    
-   603         308 LOAD_NAME                7 (root)
-               310 LOAD_METHOD             13 (mainloop)
-               332 PRECALL                  0
-               336 CALL                     0
-               346 POP_TOP
-               348 LOAD_CONST              19 (None)
-               350 RETURN_VALUE
+   620         270 LOAD_NAME                8 (root)
+               272 LOAD_METHOD             13 (mainloop)
+               294 PRECALL                  0
+               298 CALL                     0
+               308 POP_TOP
+               310 LOAD_CONST              19 (None)
+               312 RETURN_VALUE
    
-   589     >>  352 LOAD_CONST              19 (None)
-               354 RETURN_VALUE
+   604     >>  314 LOAD_CONST              19 (None)
+               316 RETURN_VALUE
    consts
       0
       ('Canvas',)
+      code
+         argcount  : 3
+         nlocals   : 7
+         stacksize : 7
+         flags     : 3
+         code
+            0x9700640164026c006d017d036d027d0401007c03a00300000000000000
+            0000000000000000000000000064037c006404a6030000ab030000000000
+            0000007d057c04a00400000000000000000000000000000000000000007c
+            05a6010000ab0100000000000000007d067c06a005000000000000000000
+            0000000000000000000000640164017c006401190000000000000000007c
+            0064051900000000000000000066047c017c02a6030000ab030000000000
+            00000001007c055300
+           3           0 RESUME                   0
+         
+           4           2 LOAD_CONST               1 (0)
+                       4 LOAD_CONST               2 (('Image', 'ImageDraw'))
+                       6 IMPORT_NAME              0 (PIL)
+                       8 IMPORT_FROM              1 (Image)
+                      10 STORE_FAST               3 (Image)
+                      12 IMPORT_FROM              2 (ImageDraw)
+                      14 STORE_FAST               4 (ImageDraw)
+                      16 POP_TOP
+         
+           5          18 LOAD_FAST                3 (Image)
+                      20 LOAD_METHOD              3 (new)
+                      42 LOAD_CONST               3 ('RGBA')
+                      44 LOAD_FAST                0 (size)
+                      46 LOAD_CONST               4 ((0, 0, 0, 0))
+                      48 PRECALL                  3
+                      52 CALL                     3
+                      62 STORE_FAST               5 (img)
+         
+           6          64 LOAD_FAST                4 (ImageDraw)
+                      66 LOAD_METHOD              4 (Draw)
+                      88 LOAD_FAST                5 (img)
+                      90 PRECALL                  1
+                      94 CALL                     1
+                     104 STORE_FAST               6 (draw)
+         
+           7         106 LOAD_FAST                6 (draw)
+                     108 LOAD_METHOD              5 (rounded_rectangle)
+                     130 LOAD_CONST               1 (0)
+                     132 LOAD_CONST               1 (0)
+                     134 LOAD_FAST                0 (size)
+                     136 LOAD_CONST               1 (0)
+                     138 BINARY_SUBSCR
+                     148 LOAD_FAST                0 (size)
+                     150 LOAD_CONST               5 (1)
+                     152 BINARY_SUBSCR
+                     162 BUILD_TUPLE              4
+                     164 LOAD_FAST                1 (radius)
+                     166 LOAD_FAST                2 (fill)
+                     168 PRECALL                  3
+                     172 CALL                     3
+                     182 POP_TOP
+         
+           8         184 LOAD_FAST                5 (img)
+                     186 RETURN_VALUE
+         consts
+            None
+            0
+            ('Image', 'ImageDraw')
+            'RGBA'
+            (0, 0, 0, 0)
+            1
+         names      ('PIL', 'Image', 'ImageDraw', 'new', 'Draw', 'rounded_rectangle')
+         varnames   ('size', 'radius', 'fill', 'Image', 'ImageDraw', 'img', 'draw')
+         freevars   ()
+         cellvars   ()
+         filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
+         name       'rounded_rectangle'
+         firstlineno 3
+         lnotab 0x020110012e012a014e01
       '\n# poly.tcl\n\nproc poly_round {win outline fill args} {\n    if {[llength $args] % 3 != 0 || [llength $args] < 9} {\n        error "wrong # args: should be "poly_round                win outline fill x1 y1 d1 x2 y2 d2 x3 y3 d3 ?...?""\n    }\n\n    # Determine the tag to use.\n    if {![info exists ::poly_next_id]} {\n        set ::poly_next_id 1\n    }\n    set tag poly#$::poly_next_id\n    incr ::poly_next_id\n\n    # Filter out illegal circles and collinear points.\n    set pts [list]\n    lassign [lrange $args 0 4] Ux Uy d Vx Vy\n    foreach {d Wx Wy} [concat [lrange $args 5 end] [lrange $args 0 4]] {\n        set test [expr {$Ux * ($Vy - $Wy) - $Vx * ($Uy - $Wy) +\n                $Wx * ($Uy - $Vy)}]\n        if {($d > 0) && $test != 0} {\n            lappend pts $Vx $Vy $d $test\n            lassign [list $Wx $Wy $Vx $Vy] Vx Vy Ux Uy\n        } else {\n            lassign [list $Wx $Wy] Vx Vy\n        }\n    }\n\n    # V    C    T   W\n    #  *---*----*-+-*-- Given: U, V, W, d\n    #  |\\ /    /|_|     Find:  S, E, T\n    #  | *B   / |\n    #  |/ \\  /  |       The length of ES and ET each is d.\n    # A*   \\/   |\n    #  |   /\\   |       VB bisects angle UVW.  SE _|_ VU; TE _|_ VW.\n    #  |  /  \\  |       B is halfway between A and C.\n    #  | /    \\ |       Angles UVW and SET are not necessarily right.\n    #  |/      \\|       The length of AV and CV each is 1.\n    # S*-+------*E\n    #  |_|       \\      The new polygon is along USTW.\n    # U*          \\     The new arc has center E, radius d, and angle SET, and\n    #  |           \\    it is tangential to VU at S and VW at T.\n\n    # Calculate new polygon vertices and create arcs.\n    set coords [list]\n    lassign [lrange $pts 0 5] Ux Uy d test Vx Vy\n    foreach {d test Wx Wy} [concat [lrange $pts 6 end] [lrange $pts 0 5]] {\n        # Find A and C.\n        foreach {pt x y} [list A $Ux $Uy C $Wx $Wy] {\n            set      k [expr {sqrt(($Vx - $x) ** 2 + ($Vy - $y) ** 2)}]\n            set ${pt}x [expr {($x - $Vx) / $k + $Vx}]\n            set ${pt}y [expr {($y - $Vy) / $k + $Vy}]\n        }\n\n        # Find B.\n        set Bx [expr {($Ax + $Cx) / 2.0}]\n        set By [expr {($Ay + $Cy) / 2.0}]\n\n        # Find the parameters for lines VB and VW.\n        foreach {pt x y} [list B $Bx $By W $Wx $Wy] {\n            set       k [expr {sqrt(($Vx - $x) ** 2 + ($Vy - $y) ** 2)}]\n            set V${pt}a [expr {+($Vy - $y) / $k}]\n            set V${pt}b [expr {-($Vx - $x) / $k}]\n            set V${pt}c [expr {($Vx * $y - $Vy * $x) / $k}]\n        }\n\n        # Find point E.\n        set sign [expr {$test < 0 ? -1 : +1}]\n        set  k [expr {$VWa * $VBb - $VWb * $VBa}]\n        set Ex [expr {(+$VWb * $VBc - ($VWc - $d * $sign) * $VBb) / $k}]\n        set Ey [expr {(-$VWa * $VBc + ($VWc - $d * $sign) * $VBa) / $k}]\n\n        # Find tangent points S and T.\n        foreach {pt x y} [list S $Ux $Uy T $Wx $Wy] {\n            set      k [expr {($Vx - $x) ** 2 + ($Vy - $y) ** 2}]\n            set ${pt}x [expr {($Ex * ($Vx - $x) ** 2 + ($Vy - $y) *\n                              ($Ey * ($Vx - $x) - $Vx * $y + $Vy * $x)) / $k}]\n            set ${pt}y [expr {($Ex * ($Vx - $x) * ($Vy - $y) +\n                              ($Ey * ($Vy - $y) ** 2 + ($Vx - $x) *\n                              ($Vx * $y - $Vy * $x))) / $k}]\n        }\n\n        # Find directions for lines ES and ET.\n        foreach {pt x y} [list S $Sx $Sy T $Tx $Ty] {\n            set E${pt}d [expr {atan2($Ey - $y, $x - $Ex)}]\n        }\n\n        # Find start and extent directions.\n        if {$ESd < 0 && $ETd > 0} {\n            set start  [expr {180 / acos(-1) * $ETd}]\n            set extent [expr {180 / acos(-1) * ($ESd - $ETd)}]\n            if {$sign > 0} {\n                set extent [expr {$extent + 360}]\n            }\n        } else {\n            set start  [expr {180 / acos(-1) * $ESd}]\n            set extent [expr {180 / acos(-1) * ($ETd - $ESd)}]\n            if {$sign < 0 && $ESd > 0 && $ETd < 0} {\n                set extent [expr {$extent + 360}]\n            }\n        }\n\n        # Draw arc.\n        set opts [list                                             [expr {$Ex - $d}] [expr {$Ey - $d}]                [expr {$Ex + $d}] [expr {$Ey + $d}]                -start $start -extent $extent]\n        $win create arc {*}$opts -style pie -tags [list $tag pie]\n        $win create arc {*}$opts -style arc -tags [list $tag arc]\n\n        # Draw border line.\n        if {[info exists prevx]} {\n            $win create line $prevx $prevy $Sx $Sy -tags [list $tag line]\n        } else {\n            lassign [list $Sx $Sy] firstx firsty\n        }\n        lassign [list $Tx $Ty] prevx prevy\n\n        # Remember coordinates for polygon.\n        lappend coords $Sx $Sy $Tx $Ty\n\n        # Rotate vertices.\n        lassign [list $Wx $Wy $Vx $Vy] Vx Vy Ux Uy\n    }\n\n    # Draw final border line.\n    $win create line $prevx $prevy $firstx $firsty -tags [list $tag line]\n\n    # Draw fill polygon.\n    $win create polygon {*}$coords -tags [list $tag poly]\n\n    # Configure colors.\n    $win itemconfigure $tag&&(poly||pie) -fill $fill\n    $win itemconfigure $tag&&pie         -outline ""\n    $win itemconfigure $tag&&line        -fill $outline -capstyle round\n    $win itemconfigure $tag&&arc         -outline $outline\n\n    # Set proper stacking order.\n    $win raise $tag&&poly\n    $win raise $tag&&pie\n    $win raise $tag&&(line||arc)\n\n    return $tag\n}\n       '
       '\n #----------------------------------------------------------------------\n #\n # RoundPoly -- Draw a polygon with rounded corners in the canvas, based\n # off of ideas and code from "Drawing rounded rectangles"\n #\n # Parameters:\n #       w - Path name of the canvas\n #       xy - list of coordinates of the vertices of the polygon\n #       radii - list of radius of the bend each each vertex\n #       args - Other args suitable to a \'polygon\' item on the canvas\n #\n # Results:\n #       Returns the canvas item number of the rounded polygon.\n #\n # Side effects:\n #       Creates a rounded polygon in the canvas.\n #\n #----------------------------------------------------------------------\n \n proc RoundPoly {w xy radii args} {\n    set lenXY [llength $xy]\n    set lenR [llength $radii]\n    if {$lenXY != 2 * $lenR} {\n        error "wrong number of vertices and radii"\n    }\n \n    # Walk down vertices keeping previous, current and next\n    lassign [lrange $xy end-1 end] x0 y0\n    lassign $xy x1 y1\n    eval lappend xy [lrange $xy 0 1]\n    set knots {}                                ;# These are the control points\n \n    for {set i 0} {$i < $lenXY} {incr i 2} {\n        set radius [lindex $radii [expr {$i/2}]]\n        set r [winfo pixels $w $radius]\n \n        lassign [lrange $xy [expr {$i + 2}] [expr {$i + 3}]] x2 y2\n        set z [_RoundPoly2 $x0 $y0 $x1 $y1 $x2 $y2 $r]\n        eval lappend knots $z\n \n        lassign [list $x1 $y1] x0 y0           ;# Current becomes previous\n        lassign [list $x2 $y2] x1 y1           ;# Next becomes current\n    }\n    set n [eval $w create polygon $knots -smooth 1 $args]\n    return $n\n }\n proc _RoundPoly2 {x0 y0 x1 y1 x2 y2 radius} {\n    set d [expr { 2 * $radius }]\n    set maxr 0.75\n \n    set v1x [expr {$x0 - $x1}]\n    set v1y [expr {$y0 - $y1}]\n    set v2x [expr {$x2 - $x1}]\n    set v2y [expr {$y2 - $y1}]\n \n    set vlen1 [expr {sqrt($v1x*$v1x + $v1y*$v1y)}]\n    set vlen2 [expr {sqrt($v2x*$v2x + $v2y*$v2y)}]\n    if {$d > $maxr * $vlen1} {\n        set d [expr {$maxr * $vlen1}]\n    }\n    if {$d > $maxr * $vlen2} {\n        set d [expr {$maxr * $vlen2}]\n    }\n \n    lappend xy [expr {$x1 + $d * $v1x/$vlen1}] [expr {$y1 + $d * $v1y/$vlen1}]\n    lappend xy $x1 $y1\n    lappend xy [expr {$x1 + $d * $v2x/$vlen2}] [expr {$y1 + $d * $v2y/$vlen2}]\n \n    return $xy\n }\n\n'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 5
          flags     : 0
          code
             0x8700970065005a0164005a0288006601640184085a03640284005a0464
-            17640484015a056418640965066602640a84055a0765075a08640b84005a
-            0965095a0a6419640c650b640d650b6604640e84055a0c650c5a0d640f84
-            005a0e650e5a0f6419641084015a1065105a11641184005a126412650b66
-            02641384045a13641a641684015a14880078015a155300
+            19640484015a05641a640965066602640a84055a0765075a08640b84005a
+            0965095a0a641b640c650b640d650b6604640e84055a0c650c5a0d640f84
+            005a0e650e5a0f641b641084015a1065105a11641184005a126412650b66
+            02641384045a13641c641684015a14641d641884015a15880078015a1653
+            00
                        0 MAKE_CELL                0 (__class__)
          
-         226           2 RESUME                   0
+         233           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawEngine')
                       10 STORE_NAME               2 (__qualname__)
          
-         227          12 LOAD_CLOSURE             0 (__class__)
+         234          12 LOAD_CLOSURE             0 (__class__)
                       14 BUILD_TUPLE              1
-                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\drawengine.py", line 227>)
+                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\drawengine.py", line 234>)
                       18 MAKE_FUNCTION            8 (closure)
                       20 STORE_NAME               3 (__init__)
          
-         230          22 LOAD_CONST               2 (<code object win32_high_dpi, file "D:\tkadw\tkadw\canvas\drawengine.py", line 230>)
+         237          22 LOAD_CONST               2 (<code object win32_high_dpi, file "D:\tkadw\tkadw\canvas\drawengine.py", line 237>)
                       24 MAKE_FUNCTION            0
                       26 STORE_NAME               4 (win32_high_dpi)
          
-         234          28 LOAD_CONST              23 (('x',))
-                      30 LOAD_CONST               4 (<code object draw_gradient, file "D:\tkadw\tkadw\canvas\drawengine.py", line 234>)
+         241          28 LOAD_CONST              25 (('x',))
+                      30 LOAD_CONST               4 (<code object draw_gradient, file "D:\tkadw\tkadw\canvas\drawengine.py", line 241>)
                       32 MAKE_FUNCTION            1 (defaults)
                       34 STORE_NAME               5 (draw_gradient)
          
-         301          36 LOAD_CONST              24 ((5, 2, 'white', 'black'))
+         308          36 LOAD_CONST              26 ((5, 2, 'white', 'black'))
                       38 LOAD_CONST               9 ('radius')
                       40 LOAD_NAME                6 (float)
                       42 BUILD_TUPLE              2
-                      44 LOAD_CONST              10 (<code object create_round_rectangle, file "D:\tkadw\tkadw\canvas\drawengine.py", line 301>)
+                      44 LOAD_CONST              10 (<code object create_round_rectangle, file "D:\tkadw\tkadw\canvas\drawengine.py", line 308>)
                       46 MAKE_FUNCTION            5 (defaults, annotations)
                       48 STORE_NAME               7 (create_round_rectangle)
          
-         332          50 LOAD_NAME                7 (create_round_rectangle)
+         339          50 LOAD_NAME                7 (create_round_rectangle)
                       52 STORE_NAME               8 (create_round_rect)
          
-         334          54 LOAD_CONST              11 (<code object create_round_rectangle2, file "D:\tkadw\tkadw\canvas\drawengine.py", line 334>)
+         341          54 LOAD_CONST              11 (<code object create_round_rectangle2, file "D:\tkadw\tkadw\canvas\drawengine.py", line 341>)
                       56 MAKE_FUNCTION            0
                       58 STORE_NAME               9 (create_round_rectangle2)
          
-         402          60 LOAD_NAME                9 (create_round_rectangle2)
+         409          60 LOAD_NAME                9 (create_round_rectangle2)
                       62 STORE_NAME              10 (create_round_rect2)
          
-         404          64 LOAD_CONST              25 (('black', 'black'))
+         411          64 LOAD_CONST              27 (('black', 'black'))
                       66 LOAD_CONST              12 ('fill')
                       68 LOAD_NAME               11 (str)
                       70 LOAD_CONST              13 ('outline')
                       72 LOAD_NAME               11 (str)
                       74 BUILD_TUPLE              4
-                      76 LOAD_CONST              14 (<code object create_round_rectangle3, file "D:\tkadw\tkadw\canvas\drawengine.py", line 404>)
+                      76 LOAD_CONST              14 (<code object create_round_rectangle3, file "D:\tkadw\tkadw\canvas\drawengine.py", line 411>)
                       78 MAKE_FUNCTION            5 (defaults, annotations)
                       80 STORE_NAME              12 (create_round_rectangle3)
          
-         421          82 LOAD_NAME               12 (create_round_rectangle3)
+         428          82 LOAD_NAME               12 (create_round_rectangle3)
                       84 STORE_NAME              13 (create_round_rect3)
          
-         423          86 LOAD_CONST              15 (<code object create_round_rectangle4, file "D:\tkadw\tkadw\canvas\drawengine.py", line 423>)
+         430          86 LOAD_CONST              15 (<code object create_round_rectangle4, file "D:\tkadw\tkadw\canvas\drawengine.py", line 430>)
                       88 MAKE_FUNCTION            0
                       90 STORE_NAME              14 (create_round_rectangle4)
          
-         449          92 LOAD_NAME               14 (create_round_rectangle4)
+         456          92 LOAD_NAME               14 (create_round_rectangle4)
                       94 STORE_NAME              15 (create_round_rect4)
          
-         451          96 LOAD_CONST              25 (('black', 'black'))
-                      98 LOAD_CONST              16 (<code object polygon_round, file "D:\tkadw\tkadw\canvas\drawengine.py", line 451>)
+         458          96 LOAD_CONST              27 (('black', 'black'))
+                      98 LOAD_CONST              16 (<code object polygon_round, file "D:\tkadw\tkadw\canvas\drawengine.py", line 458>)
                      100 MAKE_FUNCTION            1 (defaults)
                      102 STORE_NAME              16 (polygon_round)
          
-         457         104 LOAD_NAME               16 (polygon_round)
+         464         104 LOAD_NAME               16 (polygon_round)
                      106 STORE_NAME              17 (poly_round)
          
-         459         108 LOAD_CONST              17 (<code object demo_polygon_round, file "D:\tkadw\tkadw\canvas\drawengine.py", line 459>)
+         466         108 LOAD_CONST              17 (<code object demo_polygon_round, file "D:\tkadw\tkadw\canvas\drawengine.py", line 466>)
                      110 MAKE_FUNCTION            0
                      112 STORE_NAME              18 (demo_polygon_round)
          
-         567         114 LOAD_CONST              18 ('content')
+         574         114 LOAD_CONST              18 ('content')
                      116 LOAD_NAME               11 (str)
                      118 BUILD_TUPLE              2
-                     120 LOAD_CONST              19 (<code object create_svg_image, file "D:\tkadw\tkadw\canvas\drawengine.py", line 567>)
+                     120 LOAD_CONST              19 (<code object create_svg_image, file "D:\tkadw\tkadw\canvas\drawengine.py", line 574>)
                      122 MAKE_FUNCTION            4 (annotations)
                      124 STORE_NAME              19 (create_svg_image)
          
-         582         126 LOAD_CONST              26 ((10, 10, 18))
-                     128 LOAD_CONST              22 (<code object draw_copy_icon, file "D:\tkadw\tkadw\canvas\drawengine.py", line 582>)
+         589         126 LOAD_CONST              28 ((10, 10, 18))
+                     128 LOAD_CONST              22 (<code object draw_copy_icon, file "D:\tkadw\tkadw\canvas\drawengine.py", line 589>)
                      130 MAKE_FUNCTION            1 (defaults)
                      132 STORE_NAME              20 (draw_copy_icon)
-                     134 LOAD_CLOSURE             0 (__class__)
-                     136 COPY                     1
-                     138 STORE_NAME              21 (__classcell__)
-                     140 RETURN_VALUE
+         
+         596         134 LOAD_CONST              29 (('black', 16))
+                     136 LOAD_CONST              24 (<code object create_round_rectangle5, file "D:\tkadw\tkadw\canvas\drawengine.py", line 596>)
+                     138 MAKE_FUNCTION            1 (defaults)
+                     140 STORE_NAME              21 (create_round_rectangle5)
+                     142 LOAD_CLOSURE             0 (__class__)
+                     144 COPY                     1
+                     146 STORE_NAME              22 (__classcell__)
+                     148 RETURN_VALUE
          consts
             'AdwDrawEngine'
             code
                argcount  : 1
                nlocals   : 3
                stacksize : 5
                flags     : 15
                code
                   0x950197000200740100000000000000000000a6000000ab000000000000
                   0000006a0100000000000000007c0169007c02a4018e01010064005300
                              0 COPY_FREE_VARS           1
                
-               227           2 RESUME                   0
+               234           2 RESUME                   0
                
-               228           4 PUSH_NULL
+               235           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                1 (args)
                             44 BUILD_MAP                0
                             46 LOAD_FAST                2 (kwargs)
@@ -254,35 +329,35 @@
                   None
                names      ('super', '__init__')
                varnames   ('self', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       '__init__'
-               firstlineno 227
+               firstlineno 234
                lnotab 0x0401
             code
                argcount  : 1
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x9700640164026c006d017d0101007c016a020000000000000000a00300
                   000000000000000000000000000000000000006403a6010000ab01000000
                   0000000000010064005300
-               230           0 RESUME                   0
+               237           0 RESUME                   0
                
-               231           2 LOAD_CONST               1 (0)
+               238           2 LOAD_CONST               1 (0)
                              4 LOAD_CONST               2 (('windll',))
                              6 IMPORT_NAME              0 (ctypes)
                              8 IMPORT_FROM              1 (windll)
                             10 STORE_FAST               1 (windll)
                             12 POP_TOP
                
-               232          14 LOAD_FAST                1 (windll)
+               239          14 LOAD_FAST                1 (windll)
                             16 LOAD_ATTR                2 (shcore)
                             26 LOAD_METHOD              3 (SetProcessDpiAwareness)
                             48 LOAD_CONST               3 (2)
                             50 PRECALL                  1
                             54 CALL                     1
                             64 POP_TOP
                             66 LOAD_CONST               0 (None)
@@ -294,39 +369,39 @@
                   2
                names      ('ctypes', 'windll', 'shcore', 'SetProcessDpiAwareness')
                varnames   ('self', 'windll')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'win32_high_dpi'
-               firstlineno 230
+               firstlineno 237
                lnotab 0x02010c01
             'x'
             code
                argcount  : 4
                nlocals   : 4
                stacksize : 7
                flags     : 3
                code
                   0x97007c006a000000000000000000a00100000000000000000000000000
                   000000000000006401a6010000ab01000000000000000001007c006a0000
                   00000000000000a002000000000000000000000000000000000000000064
                   027c006a0300000000000000007c037c017c02a6050000ab050000000000
                   000000010064005300
-               234           0 RESUME                   0
+               241           0 RESUME                   0
                
-               235           2 LOAD_FAST                0 (self)
+               242           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (tk)
                             14 LOAD_METHOD              1 (eval)
                             36 LOAD_CONST               1 ('\n  proc + {n1 n2} {\n    expr {$n1 + $n2}\n  }\n  proc - {n1 n2} {\n    expr {$n1 - $n2}\n  }\n  proc * {n1 n2} {\n    expr {$n1 * $n2}\n  }\n  proc / {n1 n2} {\n    expr {$n1 / $n2}\n  }\n  proc toInt {n} {\n    expr int($n)\n  }\n  \n  proc drawGradient {win type col1Str col2Str} {\n    $win delete gradient\n    \n    set width [winfo width $win]\n    set height [winfo height $win]\n    \n    lassign [winfo rgb $win $col1Str] r1 g1 b1\n    lassign  [winfo rgb $win $col2Str] r2 g2 b2\n    set rRange [- $r2.0 $r1]\n    set gRange [- $g2.0 $g1]\n    set bRange [- $b2.0 $b1]\n  \n    if {$type == "x"} {\n      set rRatio [/ $rRange $width]\n      set gRatio [/ $gRange $width]\n      set bRatio [/ $bRange $width]\n    \n      for {set x 0} {$x < $width} {incr x} {\n        set nR [toInt [+ $r1 [* $rRatio $x]]]\n        set nG [toInt [+ $g1 [* $gRatio $x]]]\n        set nB [toInt [+ $b1 [* $bRatio $x]]]\n  \n        set col [format {%4.4x} $nR]\n        append col [format {%4.4x} $nG]\n        append col [format {%4.4x} $nB]\n        $win create line $x 0 $x $height -tags gradient -fill #${col}\n      }\n    } else {\n      set rRatio [/ $rRange $height]\n      set gRatio [/ $gRange $height]\n      set bRatio [/ $bRange $height]\n  \n      for {set y 0} {$y < $height} {incr y} {\n        set nR [toInt [+ $r1 [* $rRatio $y]]]\n        set nG [toInt [+ $g1 [* $gRatio $y]]]\n        set nB [toInt [+ $b1 [* $bRatio $y]]]\n  \n        set col [format {%4.4x} $nR]\n        append col [format {%4.4x} $nG]\n        append col [format {%4.4x} $nB]\n        $win create line 0 $y $width $y -tags gradient -fill #${col}\n      }\n    }\n    return $win\n  }\n        ')
                             38 PRECALL                  1
                             42 CALL                     1
                             52 POP_TOP
                
-               299          54 LOAD_FAST                0 (self)
+               306          54 LOAD_FAST                0 (self)
                             56 LOAD_ATTR                0 (tk)
                             66 LOAD_METHOD              2 (call)
                             88 LOAD_CONST               2 ('drawGradient')
                             90 LOAD_FAST                0 (self)
                             92 LOAD_ATTR                3 (_w)
                            102 LOAD_FAST                3 (type)
                            104 LOAD_FAST                1 (color1)
@@ -342,15 +417,15 @@
                   'drawGradient'
                names      ('tk', 'eval', 'call', '_w')
                varnames   ('self', 'color1', 'color2', 'type')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'draw_gradient'
-               firstlineno 234
+               firstlineno 241
                lnotab 0x02013440
             5
             2
             'white'
             'black'
             'radius'
             code
@@ -388,110 +463,110 @@
                   067a0a00007c037c0664017a0b00007a0a00007c047c0964017a0b00007a
                   0a00007c067a0000007c076405ac08a6060000ab0600000000000000007d
                   137c00a00200000000000000000000000000000000000000007c017c0964
                   017a0b00007a0000007c067a0a00007c047c0964017a0b00007a0a00007c
                   037c0964017a0b00007a0a00007c067a0000007c047c0664017a0b00007a
                   0a00007c076405ac08a6060000ab0600000000000000007d147c0a7c0b7c
                   0c7c0d7c0e7c0f7c107c117c127c137c1464099c0b5300
-               301           0 RESUME                   0
+               308           0 RESUME                   0
                
-               303           2 LOAD_FAST                5 (radius)
+               310           2 LOAD_FAST                5 (radius)
                              4 LOAD_CONST               1 (2)
                              6 BINARY_OP                5 (*)
                             10 STORE_FAST               9 (_radius)
                
-               304          12 LOAD_FAST                0 (self)
+               311          12 LOAD_FAST                0 (self)
                             14 LOAD_METHOD              0 (create_arc)
                             36 LOAD_FAST                1 (x1)
                             38 LOAD_FAST                2 (y1)
                             40 LOAD_FAST                1 (x1)
                             42 LOAD_FAST                9 (_radius)
                             44 BINARY_OP                0 (+)
                             48 LOAD_FAST                2 (y1)
                             50 LOAD_FAST                9 (_radius)
                             52 BINARY_OP                0 (+)
                             56 LOAD_CONST               2 (90)
                             58 LOAD_CONST               2 (90)
                             60 LOAD_FAST                6 (width)
                             62 LOAD_FAST                7 (fill)
                
-               305          64 LOAD_FAST                8 (outline)
+               312          64 LOAD_FAST                8 (outline)
                
-               304          66 KW_NAMES                 3
+               311          66 KW_NAMES                 3
                             68 PRECALL                  9
                             72 CALL                     9
                             82 STORE_FAST              10 (nw)
                
-               306          84 LOAD_FAST                0 (self)
+               313          84 LOAD_FAST                0 (self)
                             86 LOAD_METHOD              0 (create_arc)
                            108 LOAD_FAST                1 (x1)
                            110 LOAD_FAST                4 (y2)
                            112 LOAD_FAST                1 (x1)
                            114 LOAD_FAST                9 (_radius)
                            116 BINARY_OP                0 (+)
                            120 LOAD_FAST                4 (y2)
                            122 LOAD_FAST                9 (_radius)
                            124 BINARY_OP               10 (-)
                            128 LOAD_CONST               4 (180)
                            130 LOAD_CONST               2 (90)
                            132 LOAD_FAST                6 (width)
                            134 LOAD_FAST                7 (fill)
                
-               307         136 LOAD_FAST                8 (outline)
+               314         136 LOAD_FAST                8 (outline)
                
-               306         138 KW_NAMES                 3
+               313         138 KW_NAMES                 3
                            140 PRECALL                  9
                            144 CALL                     9
                            154 STORE_FAST              11 (sw)
                
-               308         156 LOAD_FAST                0 (self)
+               315         156 LOAD_FAST                0 (self)
                            158 LOAD_METHOD              0 (create_arc)
                            180 LOAD_FAST                3 (x2)
                            182 LOAD_FAST                9 (_radius)
                            184 BINARY_OP               10 (-)
                            188 LOAD_FAST                2 (y1)
                            190 LOAD_FAST                3 (x2)
                            192 LOAD_FAST                2 (y1)
                            194 LOAD_FAST                9 (_radius)
                            196 BINARY_OP                0 (+)
                            200 LOAD_CONST               5 (0)
                            202 LOAD_CONST               2 (90)
                            204 LOAD_FAST                6 (width)
                            206 LOAD_FAST                7 (fill)
                
-               309         208 LOAD_FAST                8 (outline)
+               316         208 LOAD_FAST                8 (outline)
                
-               308         210 KW_NAMES                 3
+               315         210 KW_NAMES                 3
                            212 PRECALL                  9
                            216 CALL                     9
                            226 STORE_FAST              12 (ne)
                
-               310         228 LOAD_FAST                0 (self)
+               317         228 LOAD_FAST                0 (self)
                            230 LOAD_METHOD              0 (create_arc)
                            252 LOAD_FAST                3 (x2)
                            254 LOAD_FAST                9 (_radius)
                            256 BINARY_OP               10 (-)
                            260 LOAD_FAST                4 (y2)
                            262 LOAD_FAST                3 (x2)
                            264 LOAD_FAST                4 (y2)
                            266 LOAD_FAST                9 (_radius)
                            268 BINARY_OP               10 (-)
                            272 LOAD_CONST               6 (270)
                            274 LOAD_CONST               2 (90)
                            276 LOAD_FAST                6 (width)
                            278 LOAD_FAST                7 (fill)
                
-               311         280 LOAD_FAST                8 (outline)
+               318         280 LOAD_FAST                8 (outline)
                
-               310         282 KW_NAMES                 3
+               317         282 KW_NAMES                 3
                            284 PRECALL                  9
                            288 CALL                     9
                            298 STORE_FAST              13 (se)
                
-               313         300 LOAD_FAST                0 (self)
+               320         300 LOAD_FAST                0 (self)
                            302 LOAD_METHOD              1 (create_line)
                            324 LOAD_FAST                1 (x1)
                            326 LOAD_FAST                2 (y1)
                            328 LOAD_FAST                9 (_radius)
                            330 LOAD_CONST               1 (2)
                            332 BINARY_OP               11 (/)
                            336 BINARY_OP                0 (+)
@@ -504,15 +579,15 @@
                            356 LOAD_FAST                6 (width)
                            358 LOAD_FAST                8 (outline)
                            360 KW_NAMES                 7
                            362 PRECALL                  6
                            366 CALL                     6
                            376 STORE_FAST              14 (w)
                
-               314         378 LOAD_FAST                0 (self)
+               321         378 LOAD_FAST                0 (self)
                            380 LOAD_METHOD              1 (create_line)
                            402 LOAD_FAST                1 (x1)
                            404 LOAD_FAST                9 (_radius)
                            406 LOAD_CONST               1 (2)
                            408 BINARY_OP               11 (/)
                            412 BINARY_OP                0 (+)
                            416 LOAD_FAST                2 (y1)
@@ -525,15 +600,15 @@
                            434 LOAD_FAST                6 (width)
                            436 LOAD_FAST                8 (outline)
                            438 KW_NAMES                 7
                            440 PRECALL                  6
                            444 CALL                     6
                            454 STORE_FAST              15 (n)
                
-               315         456 LOAD_FAST                0 (self)
+               322         456 LOAD_FAST                0 (self)
                            458 LOAD_METHOD              1 (create_line)
                            480 LOAD_FAST                3 (x2)
                            482 LOAD_FAST                2 (y1)
                            484 LOAD_FAST                9 (_radius)
                            486 LOAD_CONST               1 (2)
                            488 BINARY_OP               11 (/)
                            492 BINARY_OP                0 (+)
@@ -546,15 +621,15 @@
                            512 LOAD_FAST                6 (width)
                            514 LOAD_FAST                8 (outline)
                            516 KW_NAMES                 7
                            518 PRECALL                  6
                            522 CALL                     6
                            532 STORE_FAST              16 (e)
                
-               316         534 LOAD_FAST                0 (self)
+               323         534 LOAD_FAST                0 (self)
                            536 LOAD_METHOD              1 (create_line)
                            558 LOAD_FAST                1 (x1)
                            560 LOAD_FAST                9 (_radius)
                            562 LOAD_CONST               1 (2)
                            564 BINARY_OP               11 (/)
                            568 BINARY_OP                0 (+)
                            572 LOAD_FAST                4 (y2)
@@ -567,15 +642,15 @@
                            590 LOAD_FAST                6 (width)
                            592 LOAD_FAST                8 (outline)
                            594 KW_NAMES                 7
                            596 PRECALL                  6
                            600 CALL                     6
                            610 STORE_FAST              17 (s)
                
-               318         612 LOAD_FAST                0 (self)
+               325         612 LOAD_FAST                0 (self)
                            614 LOAD_METHOD              2 (create_rectangle)
                            636 LOAD_FAST                1 (x1)
                            638 LOAD_FAST                9 (_radius)
                            640 LOAD_CONST               1 (2)
                            642 BINARY_OP               11 (/)
                            646 BINARY_OP                0 (+)
                            650 LOAD_FAST                6 (width)
@@ -595,22 +670,22 @@
                            690 LOAD_FAST                2 (y1)
                            692 LOAD_FAST                9 (_radius)
                            694 LOAD_CONST               1 (2)
                            696 BINARY_OP               11 (/)
                            700 BINARY_OP                0 (+)
                            704 LOAD_FAST                7 (fill)
                
-               319         706 LOAD_CONST               5 (0)
+               326         706 LOAD_CONST               5 (0)
                
-               318         708 KW_NAMES                 8
+               325         708 KW_NAMES                 8
                            710 PRECALL                  6
                            714 CALL                     6
                            724 STORE_FAST              18 (top)
                
-               321         726 LOAD_FAST                0 (self)
+               328         726 LOAD_FAST                0 (self)
                            728 LOAD_METHOD              2 (create_rectangle)
                            750 LOAD_FAST                1 (x1)
                            752 LOAD_FAST                6 (width)
                            754 LOAD_CONST               1 (2)
                            756 BINARY_OP               11 (/)
                            760 BINARY_OP                0 (+)
                            764 LOAD_FAST                2 (y1)
@@ -630,22 +705,22 @@
                            802 LOAD_CONST               1 (2)
                            804 BINARY_OP               11 (/)
                            808 BINARY_OP               10 (-)
                            812 LOAD_FAST                6 (width)
                            814 BINARY_OP                0 (+)
                            818 LOAD_FAST                7 (fill)
                
-               322         820 LOAD_CONST               5 (0)
+               329         820 LOAD_CONST               5 (0)
                
-               321         822 KW_NAMES                 8
+               328         822 KW_NAMES                 8
                            824 PRECALL                  6
                            828 CALL                     6
                            838 STORE_FAST              19 (center)
                
-               324         840 LOAD_FAST                0 (self)
+               331         840 LOAD_FAST                0 (self)
                            842 LOAD_METHOD              2 (create_rectangle)
                            864 LOAD_FAST                1 (x1)
                            866 LOAD_FAST                9 (_radius)
                            868 LOAD_CONST               1 (2)
                            870 BINARY_OP               11 (/)
                            874 BINARY_OP                0 (+)
                            878 LOAD_FAST                6 (width)
@@ -665,35 +740,35 @@
                            918 LOAD_FAST                4 (y2)
                            920 LOAD_FAST                6 (width)
                            922 LOAD_CONST               1 (2)
                            924 BINARY_OP               11 (/)
                            928 BINARY_OP               10 (-)
                            932 LOAD_FAST                7 (fill)
                
-               325         934 LOAD_CONST               5 (0)
+               332         934 LOAD_CONST               5 (0)
                
-               324         936 KW_NAMES                 8
+               331         936 KW_NAMES                 8
                            938 PRECALL                  6
                            942 CALL                     6
                            952 STORE_FAST              20 (bottom)
                
-               328         954 LOAD_FAST               10 (nw)
+               335         954 LOAD_FAST               10 (nw)
                            956 LOAD_FAST               11 (sw)
                            958 LOAD_FAST               12 (ne)
                            960 LOAD_FAST               13 (se)
                            962 LOAD_FAST               14 (w)
                            964 LOAD_FAST               15 (n)
                            966 LOAD_FAST               16 (e)
                            968 LOAD_FAST               17 (s)
                
-               329         970 LOAD_FAST               18 (top)
+               336         970 LOAD_FAST               18 (top)
                            972 LOAD_FAST               19 (center)
                            974 LOAD_FAST               20 (bottom)
                
-               327         976 LOAD_CONST               9 (('nw', 'sw', 'ne', 'se', 'w', 'n', 'e', 's', 'top', 'center', 'bottom'))
+               334         976 LOAD_CONST               9 (('nw', 'sw', 'ne', 'se', 'w', 'n', 'e', 's', 'top', 'center', 'bottom'))
                            978 BUILD_CONST_KEY_MAP     11
                            980 RETURN_VALUE
                consts
                   None
                   2
                   90
                   ('start', 'extent', 'width', 'fill', 'outline')
@@ -705,15 +780,15 @@
                   ('nw', 'sw', 'ne', 'se', 'w', 'n', 'e', 's', 'top', 'center', 'bottom')
                names      ('create_arc', 'create_line', 'create_rectangle')
                varnames   ('self', 'x1', 'y1', 'x2', 'y2', 'radius', 'width', 'fill', 'outline', '_radius', 'nw', 'sw', 'ne', 'se', 'w', 'n', 'e', 's', 'top', 'center', 'bottom')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'create_round_rectangle'
-               firstlineno 301
+               firstlineno 308
                lnotab
                   0x02020a01340102ff1202340102ff1202340102ff1202340102ff12034e
                   014e014e014e025e0102ff12035e0102ff12035e0102ff1204100106fe
             code
                argcount  : 6
                nlocals   : 9
                stacksize : 9
@@ -721,66 +796,66 @@
                code
                   0x97007c006a000000000000000000a00100000000000000000000000000
                   000000000000006401a6010000ab01000000000000000001007c006a0000
                   00000000000000a002000000000000000000000000000000000000000064
                   027c006a0300000000000000007c017c027c037c047c05a6070000ab0700
                   000000000000007d0802007c006a0400000000000000007c0867017c06a2
                   01520069007c07a4018e0101007c085300
-               334           0 RESUME                   0
+               341           0 RESUME                   0
                
-               336           2 LOAD_FAST                0 (self)
+               343           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (tk)
                             14 LOAD_METHOD              1 (eval)
                             36 LOAD_CONST               1 ("\n#----------------------------------------------------------------------\n#\n# roundRect --\n#\n#       Draw a rounded rectangle in the canvas.\n#\n# Parameters:\n#       w - Path name of the canvas\n#       x0, y0 - Co-ordinates of the upper left corner, in pixels\n#       x3, y3 - Co-ordinates of the lower right corner, in pixels\n#       radius - Radius of the bend at the corners, in any form\n#                acceptable to Tk_GetPixels\n#       args - Other args suitable to a 'polygon' item on the canvas\n#\n# Results:\n#       Returns the canvas item number of the rounded rectangle.\n#\n# Side effects:\n#       Creates a rounded rectangle as a smooth polygon in the canvas.\n#\n#----------------------------------------------------------------------\n\nproc roundRect { w x0 y0 x3 y3 radius args } {\n\nset r [winfo pixels $w $radius]\nset d [expr { 2 * $r }]\n\n# Make sure that the radius of the curve is less than 3/8\n# size of the box!\n\nset maxr 0.75\n\nif { $d > $maxr * ( $x3 - $x0 ) } {\n    set d [expr { $maxr * ( $x3 - $x0 ) }]\n}\nif { $d > $maxr * ( $y3 - $y0 ) } {\n    set d [expr { $maxr * ( $y3 - $y0 ) }]\n}\n\nset x1 [expr { $x0 + $d }]\nset x2 [expr { $x3 - $d }]\nset y1 [expr { $y0 + $d }]\nset y2 [expr { $y3 - $d }]\n\nset cmd [list $w create polygon]\nlappend cmd $x0 $y0\nlappend cmd $x1 $y0\nlappend cmd $x2 $y0\nlappend cmd $x3 $y0\nlappend cmd $x3 $y1\nlappend cmd $x3 $y2\nlappend cmd $x3 $y3\nlappend cmd $x2 $y3\nlappend cmd $x1 $y3\nlappend cmd $x0 $y3\nlappend cmd $x0 $y2\nlappend cmd $x0 $y1\nlappend cmd -smooth 1\nreturn [eval $cmd $args]\n}\n        ")
                             38 PRECALL                  1
                             42 CALL                     1
                             52 POP_TOP
                
-               398          54 LOAD_FAST                0 (self)
+               405          54 LOAD_FAST                0 (self)
                             56 LOAD_ATTR                0 (tk)
                             66 LOAD_METHOD              2 (call)
                             88 LOAD_CONST               2 ('roundRect')
                             90 LOAD_FAST                0 (self)
                             92 LOAD_ATTR                3 (_w)
                            102 LOAD_FAST                1 (x0)
                            104 LOAD_FAST                2 (y0)
                            106 LOAD_FAST                3 (x3)
                            108 LOAD_FAST                4 (y3)
                            110 LOAD_FAST                5 (radius)
                            112 PRECALL                  7
                            116 CALL                     7
                            126 STORE_FAST               8 (rect)
                
-               399         128 PUSH_NULL
+               406         128 PUSH_NULL
                            130 LOAD_FAST                0 (self)
                            132 LOAD_ATTR                4 (itemconfig)
                            142 LOAD_FAST                8 (rect)
                            144 BUILD_LIST               1
                            146 LOAD_FAST                6 (args)
                            148 LIST_EXTEND              1
                            150 LIST_TO_TUPLE
                            152 BUILD_MAP                0
                            154 LOAD_FAST                7 (kwargs)
                            156 DICT_MERGE               1
                            158 CALL_FUNCTION_EX         1
                            160 POP_TOP
                
-               400         162 LOAD_FAST                8 (rect)
+               407         162 LOAD_FAST                8 (rect)
                            164 RETURN_VALUE
                consts
                   None
                   "\n#----------------------------------------------------------------------\n#\n# roundRect --\n#\n#       Draw a rounded rectangle in the canvas.\n#\n# Parameters:\n#       w - Path name of the canvas\n#       x0, y0 - Co-ordinates of the upper left corner, in pixels\n#       x3, y3 - Co-ordinates of the lower right corner, in pixels\n#       radius - Radius of the bend at the corners, in any form\n#                acceptable to Tk_GetPixels\n#       args - Other args suitable to a 'polygon' item on the canvas\n#\n# Results:\n#       Returns the canvas item number of the rounded rectangle.\n#\n# Side effects:\n#       Creates a rounded rectangle as a smooth polygon in the canvas.\n#\n#----------------------------------------------------------------------\n\nproc roundRect { w x0 y0 x3 y3 radius args } {\n\nset r [winfo pixels $w $radius]\nset d [expr { 2 * $r }]\n\n# Make sure that the radius of the curve is less than 3/8\n# size of the box!\n\nset maxr 0.75\n\nif { $d > $maxr * ( $x3 - $x0 ) } {\n    set d [expr { $maxr * ( $x3 - $x0 ) }]\n}\nif { $d > $maxr * ( $y3 - $y0 ) } {\n    set d [expr { $maxr * ( $y3 - $y0 ) }]\n}\n\nset x1 [expr { $x0 + $d }]\nset x2 [expr { $x3 - $d }]\nset y1 [expr { $y0 + $d }]\nset y2 [expr { $y3 - $d }]\n\nset cmd [list $w create polygon]\nlappend cmd $x0 $y0\nlappend cmd $x1 $y0\nlappend cmd $x2 $y0\nlappend cmd $x3 $y0\nlappend cmd $x3 $y1\nlappend cmd $x3 $y2\nlappend cmd $x3 $y3\nlappend cmd $x2 $y3\nlappend cmd $x1 $y3\nlappend cmd $x0 $y3\nlappend cmd $x0 $y2\nlappend cmd $x0 $y1\nlappend cmd -smooth 1\nreturn [eval $cmd $args]\n}\n        "
                   'roundRect'
                names      ('tk', 'eval', 'call', '_w', 'itemconfig')
                varnames   ('self', 'x0', 'y0', 'x3', 'y3', 'radius', 'args', 'kwargs', 'rect')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'create_round_rectangle2'
-               firstlineno 334
+               firstlineno 341
                lnotab 0x0202343e4a012201
             'fill'
             'outline'
             code
                argcount  : 9
                nlocals   : 12
                stacksize : 12
@@ -788,25 +863,25 @@
                code
                   0x97007c006a000000000000000000a00100000000000000000000000000
                   000000000000006401a6010000ab01000000000000000001007c006a0000
                   00000000000000a002000000000000000000000000000000000000000064
                   027c006a0300000000000000007c027c037c067c047c057c077c087c01a6
                   0a0000ab0a00000000000000007d0b02007c006a0400000000000000007c
                   0b67017c09a201520069007c0aa4018e0101007c0b5300
-               404           0 RESUME                   0
+               411           0 RESUME                   0
                
-               406           2 LOAD_FAST                0 (self)
+               413           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (tk)
                             14 LOAD_METHOD              1 (eval)
                             36 LOAD_CONST               1 ('\nproc roundRect2 {w L T Rad width height fill outline tag} {\n\n  $w create oval $L $T [expr $L + $Rad] [expr $T + $Rad] -fill $fill -outline $outline -tag $tag\n  $w create oval [expr $width-$Rad] $T $width [expr $T + $Rad] -fill $fill -outline $outline -tag $tag\n  $w create oval $L [expr $height-$Rad] [expr $L+$Rad] $height -fill $fill -outline $outline -tag $tag\n  $w create oval [expr $width-$Rad] [expr $height-$Rad] [expr $width] $height -fill $fill -outline $outline -tag $tag\n  $w create rectangle [expr $L + ($Rad/2.0)] $T [expr $width-($Rad/2.0)] $height -fill $fill -outline $outline -tag $tag\n  $w create rectangle $L [expr $T + ($Rad/2.0)] $width [expr $height-($Rad/2.0)] -fill $fill -outline $outline -tag $tag\n}\n            ')
                             38 PRECALL                  1
                             42 CALL                     1
                             52 POP_TOP
                
-               417          54 LOAD_FAST                0 (self)
+               424          54 LOAD_FAST                0 (self)
                             56 LOAD_ATTR                0 (tk)
                             66 LOAD_METHOD              2 (call)
                             88 LOAD_CONST               2 ('roundRect2')
                             90 LOAD_FAST                0 (self)
                             92 LOAD_ATTR                3 (_w)
                            102 LOAD_FAST                2 (x)
                            104 LOAD_FAST                3 (y)
@@ -816,41 +891,41 @@
                            112 LOAD_FAST                7 (fill)
                            114 LOAD_FAST                8 (outline)
                            116 LOAD_FAST                1 (tag)
                            118 PRECALL                 10
                            122 CALL                    10
                            132 STORE_FAST              11 (_rect)
                
-               418         134 PUSH_NULL
+               425         134 PUSH_NULL
                            136 LOAD_FAST                0 (self)
                            138 LOAD_ATTR                4 (itemconfig)
                            148 LOAD_FAST               11 (_rect)
                            150 BUILD_LIST               1
                            152 LOAD_FAST                9 (args)
                            154 LIST_EXTEND              1
                            156 LIST_TO_TUPLE
                            158 BUILD_MAP                0
                            160 LOAD_FAST               10 (kwargs)
                            162 DICT_MERGE               1
                            164 CALL_FUNCTION_EX         1
                            166 POP_TOP
                
-               419         168 LOAD_FAST               11 (_rect)
+               426         168 LOAD_FAST               11 (_rect)
                            170 RETURN_VALUE
                consts
                   None
                   '\nproc roundRect2 {w L T Rad width height fill outline tag} {\n\n  $w create oval $L $T [expr $L + $Rad] [expr $T + $Rad] -fill $fill -outline $outline -tag $tag\n  $w create oval [expr $width-$Rad] $T $width [expr $T + $Rad] -fill $fill -outline $outline -tag $tag\n  $w create oval $L [expr $height-$Rad] [expr $L+$Rad] $height -fill $fill -outline $outline -tag $tag\n  $w create oval [expr $width-$Rad] [expr $height-$Rad] [expr $width] $height -fill $fill -outline $outline -tag $tag\n  $w create rectangle [expr $L + ($Rad/2.0)] $T [expr $width-($Rad/2.0)] $height -fill $fill -outline $outline -tag $tag\n  $w create rectangle $L [expr $T + ($Rad/2.0)] $width [expr $height-($Rad/2.0)] -fill $fill -outline $outline -tag $tag\n}\n            '
                   'roundRect2'
                names      ('tk', 'eval', 'call', '_w', 'itemconfig')
                varnames   ('self', 'tag', 'x', 'y', 'width', 'height', 'radius', 'fill', 'outline', 'args', 'kwargs', '_rect')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'create_round_rectangle3'
-               firstlineno 404
+               firstlineno 411
                lnotab 0x0202340b50012201
             code
                argcount  : 6
                nlocals   : 9
                stacksize : 6
                flags     : 11
                code
@@ -861,235 +936,235 @@
                   0a000091017c0391017c0491017c037c057a0a000091017c0491017c037c
                   057a0a000091017c0491017c017c057a00000091017c0491017c017c057a
                   00000091017c0491017c0191017c0491017c0191017c047c057a0a000091
                   017c0191017c047c057a0a000091017c0191017c027c057a00000091017c
                   0191017c027c057a00000091017c0191017c0291017d0702007c006a0000
                   000000000000007c07660169007c06a401640164026901a4018e017d087c
                   085300
-               423           0 RESUME                   0
+               430           0 RESUME                   0
                
-               424           2 BUILD_LIST               0
+               431           2 BUILD_LIST               0
                              4 LOAD_FAST                1 (x1)
                              6 LOAD_FAST                5 (radius)
                              8 BINARY_OP                0 (+)
                             12 LIST_APPEND              1
                             14 LOAD_FAST                2 (y1)
                             16 LIST_APPEND              1
                
-               425          18 LOAD_FAST                1 (x1)
+               432          18 LOAD_FAST                1 (x1)
                             20 LOAD_FAST                5 (radius)
                             22 BINARY_OP                0 (+)
                
-               424          26 LIST_APPEND              1
+               431          26 LIST_APPEND              1
                
-               425          28 LOAD_FAST                2 (y1)
+               432          28 LOAD_FAST                2 (y1)
                
-               424          30 LIST_APPEND              1
+               431          30 LIST_APPEND              1
                
-               426          32 LOAD_FAST                3 (x2)
+               433          32 LOAD_FAST                3 (x2)
                             34 LOAD_FAST                5 (radius)
                             36 BINARY_OP               10 (-)
                
-               424          40 LIST_APPEND              1
+               431          40 LIST_APPEND              1
                
-               426          42 LOAD_FAST                2 (y1)
+               433          42 LOAD_FAST                2 (y1)
                
-               424          44 LIST_APPEND              1
+               431          44 LIST_APPEND              1
                
-               427          46 LOAD_FAST                3 (x2)
+               434          46 LOAD_FAST                3 (x2)
                             48 LOAD_FAST                5 (radius)
                             50 BINARY_OP               10 (-)
                
-               424          54 LIST_APPEND              1
+               431          54 LIST_APPEND              1
                
-               427          56 LOAD_FAST                2 (y1)
+               434          56 LOAD_FAST                2 (y1)
                
-               424          58 LIST_APPEND              1
+               431          58 LIST_APPEND              1
                
-               428          60 LOAD_FAST                3 (x2)
+               435          60 LOAD_FAST                3 (x2)
                
-               424          62 LIST_APPEND              1
+               431          62 LIST_APPEND              1
                
-               428          64 LOAD_FAST                2 (y1)
+               435          64 LOAD_FAST                2 (y1)
                
-               424          66 LIST_APPEND              1
+               431          66 LIST_APPEND              1
                
-               429          68 LOAD_FAST                3 (x2)
+               436          68 LOAD_FAST                3 (x2)
                
-               424          70 LIST_APPEND              1
+               431          70 LIST_APPEND              1
                
-               429          72 LOAD_FAST                2 (y1)
+               436          72 LOAD_FAST                2 (y1)
                             74 LOAD_FAST                5 (radius)
                             76 BINARY_OP                0 (+)
                
-               424          80 LIST_APPEND              1
+               431          80 LIST_APPEND              1
                
-               430          82 LOAD_FAST                3 (x2)
+               437          82 LOAD_FAST                3 (x2)
                
-               424          84 LIST_APPEND              1
+               431          84 LIST_APPEND              1
                
-               430          86 LOAD_FAST                2 (y1)
+               437          86 LOAD_FAST                2 (y1)
                             88 LOAD_FAST                5 (radius)
                             90 BINARY_OP                0 (+)
                
-               424          94 LIST_APPEND              1
+               431          94 LIST_APPEND              1
                
-               431          96 LOAD_FAST                3 (x2)
+               438          96 LOAD_FAST                3 (x2)
                
-               424          98 LIST_APPEND              1
+               431          98 LIST_APPEND              1
                
-               431         100 LOAD_FAST                4 (y2)
+               438         100 LOAD_FAST                4 (y2)
                            102 LOAD_FAST                5 (radius)
                            104 BINARY_OP               10 (-)
                
-               424         108 LIST_APPEND              1
+               431         108 LIST_APPEND              1
                
-               432         110 LOAD_FAST                3 (x2)
+               439         110 LOAD_FAST                3 (x2)
                
-               424         112 LIST_APPEND              1
+               431         112 LIST_APPEND              1
                
-               432         114 LOAD_FAST                4 (y2)
+               439         114 LOAD_FAST                4 (y2)
                            116 LOAD_FAST                5 (radius)
                            118 BINARY_OP               10 (-)
                
-               424         122 LIST_APPEND              1
+               431         122 LIST_APPEND              1
                
-               433         124 LOAD_FAST                3 (x2)
+               440         124 LOAD_FAST                3 (x2)
                
-               424         126 LIST_APPEND              1
+               431         126 LIST_APPEND              1
                
-               433         128 LOAD_FAST                4 (y2)
+               440         128 LOAD_FAST                4 (y2)
                
-               424         130 LIST_APPEND              1
+               431         130 LIST_APPEND              1
                
-               434         132 LOAD_FAST                3 (x2)
+               441         132 LOAD_FAST                3 (x2)
                            134 LOAD_FAST                5 (radius)
                            136 BINARY_OP               10 (-)
                
-               424         140 LIST_APPEND              1
+               431         140 LIST_APPEND              1
                
-               434         142 LOAD_FAST                4 (y2)
+               441         142 LOAD_FAST                4 (y2)
                
-               424         144 LIST_APPEND              1
+               431         144 LIST_APPEND              1
                
-               435         146 LOAD_FAST                3 (x2)
+               442         146 LOAD_FAST                3 (x2)
                            148 LOAD_FAST                5 (radius)
                            150 BINARY_OP               10 (-)
                
-               424         154 LIST_APPEND              1
+               431         154 LIST_APPEND              1
                
-               435         156 LOAD_FAST                4 (y2)
+               442         156 LOAD_FAST                4 (y2)
                
-               424         158 LIST_APPEND              1
+               431         158 LIST_APPEND              1
                
-               436         160 LOAD_FAST                1 (x1)
+               443         160 LOAD_FAST                1 (x1)
                            162 LOAD_FAST                5 (radius)
                            164 BINARY_OP                0 (+)
                
-               424         168 LIST_APPEND              1
+               431         168 LIST_APPEND              1
                
-               436         170 LOAD_FAST                4 (y2)
+               443         170 LOAD_FAST                4 (y2)
                
-               424         172 LIST_APPEND              1
+               431         172 LIST_APPEND              1
                
-               437         174 LOAD_FAST                1 (x1)
+               444         174 LOAD_FAST                1 (x1)
                            176 LOAD_FAST                5 (radius)
                            178 BINARY_OP                0 (+)
                
-               424         182 LIST_APPEND              1
+               431         182 LIST_APPEND              1
                
-               437         184 LOAD_FAST                4 (y2)
+               444         184 LOAD_FAST                4 (y2)
                
-               424         186 LIST_APPEND              1
+               431         186 LIST_APPEND              1
                
-               438         188 LOAD_FAST                1 (x1)
+               445         188 LOAD_FAST                1 (x1)
                
-               424         190 LIST_APPEND              1
+               431         190 LIST_APPEND              1
                
-               438         192 LOAD_FAST                4 (y2)
+               445         192 LOAD_FAST                4 (y2)
                
-               424         194 LIST_APPEND              1
+               431         194 LIST_APPEND              1
                
-               439         196 LOAD_FAST                1 (x1)
+               446         196 LOAD_FAST                1 (x1)
                
-               424         198 LIST_APPEND              1
+               431         198 LIST_APPEND              1
                
-               439         200 LOAD_FAST                4 (y2)
+               446         200 LOAD_FAST                4 (y2)
                            202 LOAD_FAST                5 (radius)
                            204 BINARY_OP               10 (-)
                
-               424         208 LIST_APPEND              1
+               431         208 LIST_APPEND              1
                
-               440         210 LOAD_FAST                1 (x1)
+               447         210 LOAD_FAST                1 (x1)
                
-               424         212 LIST_APPEND              1
+               431         212 LIST_APPEND              1
                
-               440         214 LOAD_FAST                4 (y2)
+               447         214 LOAD_FAST                4 (y2)
                            216 LOAD_FAST                5 (radius)
                            218 BINARY_OP               10 (-)
                
-               424         222 LIST_APPEND              1
+               431         222 LIST_APPEND              1
                
-               441         224 LOAD_FAST                1 (x1)
+               448         224 LOAD_FAST                1 (x1)
                
-               424         226 LIST_APPEND              1
+               431         226 LIST_APPEND              1
                
-               441         228 LOAD_FAST                2 (y1)
+               448         228 LOAD_FAST                2 (y1)
                            230 LOAD_FAST                5 (radius)
                            232 BINARY_OP                0 (+)
                
-               424         236 LIST_APPEND              1
+               431         236 LIST_APPEND              1
                
-               442         238 LOAD_FAST                1 (x1)
+               449         238 LOAD_FAST                1 (x1)
                
-               424         240 LIST_APPEND              1
+               431         240 LIST_APPEND              1
                
-               442         242 LOAD_FAST                2 (y1)
+               449         242 LOAD_FAST                2 (y1)
                            244 LOAD_FAST                5 (radius)
                            246 BINARY_OP                0 (+)
                
-               424         250 LIST_APPEND              1
+               431         250 LIST_APPEND              1
                
-               443         252 LOAD_FAST                1 (x1)
+               450         252 LOAD_FAST                1 (x1)
                
-               424         254 LIST_APPEND              1
+               431         254 LIST_APPEND              1
                
-               443         256 LOAD_FAST                2 (y1)
+               450         256 LOAD_FAST                2 (y1)
                
-               424         258 LIST_APPEND              1
+               431         258 LIST_APPEND              1
                            260 STORE_FAST               7 (points)
                
-               445         262 PUSH_NULL
+               452         262 PUSH_NULL
                            264 LOAD_FAST                0 (self)
                            266 LOAD_ATTR                0 (create_polygon)
                            276 LOAD_FAST                7 (points)
                            278 BUILD_TUPLE              1
                            280 BUILD_MAP                0
                            282 LOAD_FAST                6 (kwargs)
                            284 DICT_MERGE               1
                            286 LOAD_CONST               1 ('smooth')
                            288 LOAD_CONST               2 (True)
                            290 BUILD_MAP                1
                            292 DICT_MERGE               1
                            294 CALL_FUNCTION_EX         1
                            296 STORE_FAST               8 (_poly)
                
-               447         298 LOAD_FAST                8 (_poly)
+               454         298 LOAD_FAST                8 (_poly)
                            300 RETURN_VALUE
                consts
                   None
                   'smooth'
                   True
                names      ('create_polygon',)
                varnames   ('self', 'x1', 'y1', 'x2', 'y2', 'radius', 'kwargs', 'points', '_poly')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'create_round_rectangle4'
-               firstlineno 423
+               firstlineno 430
                lnotab
                   0x0201100108ff020102ff020208fe020202fe020308fd020302fd020402
                   fc020402fc020502fb020508fb020602fa020608fa020702f9020708f902
                   0802f8020808f8020902f7020902f7020a08f6020a02f6020b08f5020b02
                   f5020c08f4020c02f4020d08f3020d02f3020e02f2020e02f2020f02f102
                   0f08f1021002f0021008f0021102ef021108ef021202ee021208ee021302
                   ed021302ed04152402
@@ -1101,25 +1176,25 @@
                code
                   0x97007c006a000000000000000000a00100000000000000000000000000
                   00000000000000740400000000000000000000a6010000ab010000000000
                   00000001007c006a000000000000000000a0010000000000000000000000
                   00000000000000000064017c019b0064027c029b0064027c039b009d06a6
                   010000ab0100000000000000007d0602007c006a0300000000000000007c
                   0667017c04a201520069007c05a4018e0101007c065300
-               451           0 RESUME                   0
+               458           0 RESUME                   0
                
-               452           2 LOAD_FAST                0 (self)
+               459           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (tk)
                             14 LOAD_METHOD              1 (eval)
                             36 LOAD_GLOBAL              4 (poly)
                             48 PRECALL                  1
                             52 CALL                     1
                             62 POP_TOP
                
-               453          64 LOAD_FAST                0 (self)
+               460          64 LOAD_FAST                0 (self)
                             66 LOAD_ATTR                0 (tk)
                             76 LOAD_METHOD              1 (eval)
                             98 LOAD_CONST               1 ('poly_round ')
                            100 LOAD_FAST                1 (win)
                            102 FORMAT_VALUE             0
                            104 LOAD_CONST               2 (' ')
                            106 LOAD_FAST                2 (outline)
@@ -1128,67 +1203,67 @@
                            112 LOAD_FAST                3 (fill)
                            114 FORMAT_VALUE             0
                            116 BUILD_STRING             6
                            118 PRECALL                  1
                            122 CALL                     1
                            132 STORE_FAST               6 (_poly)
                
-               454         134 PUSH_NULL
+               461         134 PUSH_NULL
                            136 LOAD_FAST                0 (self)
                            138 LOAD_ATTR                3 (itemconfig)
                            148 LOAD_FAST                6 (_poly)
                            150 BUILD_LIST               1
                            152 LOAD_FAST                4 (args)
                            154 LIST_EXTEND              1
                            156 LIST_TO_TUPLE
                            158 BUILD_MAP                0
                            160 LOAD_FAST                5 (kwargs)
                            162 DICT_MERGE               1
                            164 CALL_FUNCTION_EX         1
                            166 POP_TOP
                
-               455         168 LOAD_FAST                6 (_poly)
+               462         168 LOAD_FAST                6 (_poly)
                            170 RETURN_VALUE
                consts
                   None
                   'poly_round '
                   ' '
                names      ('tk', 'eval', 'poly', 'itemconfig')
                varnames   ('self', 'win', 'outline', 'fill', 'args', 'kwargs', '_poly')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'polygon_round'
-               firstlineno 451
+               firstlineno 458
                lnotab 0x02013e0146012201
             code
                argcount  : 1
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x970064017d017c006a000000000000000000a001000000000000000000
                   0000000000000000000000740400000000000000000000a6010000ab0100
                   0000000000000001007c006a000000000000000000a00100000000000000
                   000000000000000000000000007c01a6010000ab01000000000000000001
                   0064005300
-               459           0 RESUME                   0
+               466           0 RESUME                   0
                
-               460           2 LOAD_CONST               1 ('\n package require Tcl 8.5\n package require Tk\n\n proc draw {win} {\n     global demo\n\n     set sharp_pts [list]\n     set round_pts [list]\n     for {set id 0} {$id < $demo(num_pts)} {incr id} {\n         set x [expr {([lindex [$win coords vtx#$id] 0] +\n                       [lindex [$win coords vtx#$id] 2]) / 2}]\n         set y [expr {([lindex [$win coords vtx#$id] 1] +\n                       [lindex [$win coords vtx#$id] 3]) / 2}]\n         lappend sharp_pts $x $y\n         lappend round_pts $x $y $demo(radius)\n     }\n\n     .c delete sharp_poly\n     .c create polygon {*}$sharp_pts -outline gray50 -fill ""             -dash {6 5} -tags {sharp_poly}\n\n     if {[info exists demo(tag)]} {\n         .c delete $demo(tag)\n     }\n     set demo(tag) [poly_round .c $demo(outline) $demo(fill) {*}$round_pts]\n     .c itemconfigure $demo(tag) -width $demo(thickness)\n\n     .c raise vtx\n }\n\n proc down {win x y} {\n     global demo\n\n     $win dtag selected\n     $win addtag selected withtag current\n     $win raise current\n     set demo(last_x) $x\n     set demo(last_y) $y\n }\n \n proc move {win x y} {\n     global demo\n\n     if {[info exists demo(last_x)]} {\n         $win move selected                 [expr {$x - $demo(last_x)}]                 [expr {$y - $demo(last_y)}]\n         set demo(last_x) $x\n         set demo(last_y) $y\n\n         draw $win\n     }\n }\n\n proc main {args} {\n     global demo\n\n     array set demo {\n         num_pts 3       radius 20      thickness 1\n         outline black   fill   white   background gray\n         width   400     height 400\n     }\n     foreach {option value} $args {\n         set option [regsub {^-} $option ""]\n         if {![info exists demo($option)]} {\n             puts "Options: -[join [array names demo] " -"]"\n             exit\n         } else {\n             set demo([regsub {^-} $option ""]) $value\n         }\n     }\n\n     canvas .c -width $demo(width) -height $demo(height) -highlightthickness 0             -background $demo(background)\n     pack .c\n     wm title . "Round Polygon Demo"\n     wm resizable . 0 0\n\n     set 2pi [expr {2 * acos(-1)}]\n     set cx [expr {$demo(width)  / 2}]; set sx [expr {$demo(width)  * 3 / 8}]\n     set cy [expr {$demo(height) / 2}]; set sy [expr {$demo(height) * 3 / 8}]\n     for {set id 0} {$id < $demo(num_pts)} {incr id} {\n         set x [expr {$cx + $sx * cos(($id + 0.5) * $2pi / $demo(num_pts))}]\n         set y [expr {$cy - $sy * sin(($id + 0.5) * $2pi / $demo(num_pts))}]\n         .c create oval [expr {$x - 3}] [expr {$y - 3}]                        [expr {$x + 3}] [expr {$y + 3}]                        -tags [list vtx vtx#$id] -fill brown\n     }\n\n     .c bind vtx <Any-Enter> {.c itemconfigure current -fill red}\n     .c bind vtx <Any-Leave> {.c itemconfigure current -fill brown}\n     .c bind vtx <ButtonPress-1> {down .c %x %y}\n     .c bind vtx <ButtonRelease-1> {.c dtag selected}\n     bind .c <B1-Motion> {move .c %x %y}\n\n     focus .c\n     draw .c\n }\n\n main\n\n        ')
+               467           2 LOAD_CONST               1 ('\n package require Tcl 8.5\n package require Tk\n\n proc draw {win} {\n     global demo\n\n     set sharp_pts [list]\n     set round_pts [list]\n     for {set id 0} {$id < $demo(num_pts)} {incr id} {\n         set x [expr {([lindex [$win coords vtx#$id] 0] +\n                       [lindex [$win coords vtx#$id] 2]) / 2}]\n         set y [expr {([lindex [$win coords vtx#$id] 1] +\n                       [lindex [$win coords vtx#$id] 3]) / 2}]\n         lappend sharp_pts $x $y\n         lappend round_pts $x $y $demo(radius)\n     }\n\n     .c delete sharp_poly\n     .c create polygon {*}$sharp_pts -outline gray50 -fill ""             -dash {6 5} -tags {sharp_poly}\n\n     if {[info exists demo(tag)]} {\n         .c delete $demo(tag)\n     }\n     set demo(tag) [poly_round .c $demo(outline) $demo(fill) {*}$round_pts]\n     .c itemconfigure $demo(tag) -width $demo(thickness)\n\n     .c raise vtx\n }\n\n proc down {win x y} {\n     global demo\n\n     $win dtag selected\n     $win addtag selected withtag current\n     $win raise current\n     set demo(last_x) $x\n     set demo(last_y) $y\n }\n \n proc move {win x y} {\n     global demo\n\n     if {[info exists demo(last_x)]} {\n         $win move selected                 [expr {$x - $demo(last_x)}]                 [expr {$y - $demo(last_y)}]\n         set demo(last_x) $x\n         set demo(last_y) $y\n\n         draw $win\n     }\n }\n\n proc main {args} {\n     global demo\n\n     array set demo {\n         num_pts 3       radius 20      thickness 1\n         outline black   fill   white   background gray\n         width   400     height 400\n     }\n     foreach {option value} $args {\n         set option [regsub {^-} $option ""]\n         if {![info exists demo($option)]} {\n             puts "Options: -[join [array names demo] " -"]"\n             exit\n         } else {\n             set demo([regsub {^-} $option ""]) $value\n         }\n     }\n\n     canvas .c -width $demo(width) -height $demo(height) -highlightthickness 0             -background $demo(background)\n     pack .c\n     wm title . "Round Polygon Demo"\n     wm resizable . 0 0\n\n     set 2pi [expr {2 * acos(-1)}]\n     set cx [expr {$demo(width)  / 2}]; set sx [expr {$demo(width)  * 3 / 8}]\n     set cy [expr {$demo(height) / 2}]; set sy [expr {$demo(height) * 3 / 8}]\n     for {set id 0} {$id < $demo(num_pts)} {incr id} {\n         set x [expr {$cx + $sx * cos(($id + 0.5) * $2pi / $demo(num_pts))}]\n         set y [expr {$cy - $sy * sin(($id + 0.5) * $2pi / $demo(num_pts))}]\n         .c create oval [expr {$x - 3}] [expr {$y - 3}]                        [expr {$x + 3}] [expr {$y + 3}]                        -tags [list vtx vtx#$id] -fill brown\n     }\n\n     .c bind vtx <Any-Enter> {.c itemconfigure current -fill red}\n     .c bind vtx <Any-Leave> {.c itemconfigure current -fill brown}\n     .c bind vtx <ButtonPress-1> {down .c %x %y}\n     .c bind vtx <ButtonRelease-1> {.c dtag selected}\n     bind .c <B1-Motion> {move .c %x %y}\n\n     focus .c\n     draw .c\n }\n\n main\n\n        ')
                              4 STORE_FAST               1 (demo)
                
-               564           6 LOAD_FAST                0 (self)
+               571           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (tk)
                             18 LOAD_METHOD              1 (eval)
                             40 LOAD_GLOBAL              4 (poly)
                             52 PRECALL                  1
                             56 CALL                     1
                             66 POP_TOP
                
-               565          68 LOAD_FAST                0 (self)
+               572          68 LOAD_FAST                0 (self)
                             70 LOAD_ATTR                0 (tk)
                             80 LOAD_METHOD              1 (eval)
                            102 LOAD_FAST                1 (demo)
                            104 PRECALL                  1
                            108 CALL                     1
                            118 POP_TOP
                            120 LOAD_CONST               0 (None)
@@ -1198,15 +1273,15 @@
                   '\n package require Tcl 8.5\n package require Tk\n\n proc draw {win} {\n     global demo\n\n     set sharp_pts [list]\n     set round_pts [list]\n     for {set id 0} {$id < $demo(num_pts)} {incr id} {\n         set x [expr {([lindex [$win coords vtx#$id] 0] +\n                       [lindex [$win coords vtx#$id] 2]) / 2}]\n         set y [expr {([lindex [$win coords vtx#$id] 1] +\n                       [lindex [$win coords vtx#$id] 3]) / 2}]\n         lappend sharp_pts $x $y\n         lappend round_pts $x $y $demo(radius)\n     }\n\n     .c delete sharp_poly\n     .c create polygon {*}$sharp_pts -outline gray50 -fill ""             -dash {6 5} -tags {sharp_poly}\n\n     if {[info exists demo(tag)]} {\n         .c delete $demo(tag)\n     }\n     set demo(tag) [poly_round .c $demo(outline) $demo(fill) {*}$round_pts]\n     .c itemconfigure $demo(tag) -width $demo(thickness)\n\n     .c raise vtx\n }\n\n proc down {win x y} {\n     global demo\n\n     $win dtag selected\n     $win addtag selected withtag current\n     $win raise current\n     set demo(last_x) $x\n     set demo(last_y) $y\n }\n \n proc move {win x y} {\n     global demo\n\n     if {[info exists demo(last_x)]} {\n         $win move selected                 [expr {$x - $demo(last_x)}]                 [expr {$y - $demo(last_y)}]\n         set demo(last_x) $x\n         set demo(last_y) $y\n\n         draw $win\n     }\n }\n\n proc main {args} {\n     global demo\n\n     array set demo {\n         num_pts 3       radius 20      thickness 1\n         outline black   fill   white   background gray\n         width   400     height 400\n     }\n     foreach {option value} $args {\n         set option [regsub {^-} $option ""]\n         if {![info exists demo($option)]} {\n             puts "Options: -[join [array names demo] " -"]"\n             exit\n         } else {\n             set demo([regsub {^-} $option ""]) $value\n         }\n     }\n\n     canvas .c -width $demo(width) -height $demo(height) -highlightthickness 0             -background $demo(background)\n     pack .c\n     wm title . "Round Polygon Demo"\n     wm resizable . 0 0\n\n     set 2pi [expr {2 * acos(-1)}]\n     set cx [expr {$demo(width)  / 2}]; set sx [expr {$demo(width)  * 3 / 8}]\n     set cy [expr {$demo(height) / 2}]; set sy [expr {$demo(height) * 3 / 8}]\n     for {set id 0} {$id < $demo(num_pts)} {incr id} {\n         set x [expr {$cx + $sx * cos(($id + 0.5) * $2pi / $demo(num_pts))}]\n         set y [expr {$cy - $sy * sin(($id + 0.5) * $2pi / $demo(num_pts))}]\n         .c create oval [expr {$x - 3}] [expr {$y - 3}]                        [expr {$x + 3}] [expr {$y + 3}]                        -tags [list vtx vtx#$id] -fill brown\n     }\n\n     .c bind vtx <Any-Enter> {.c itemconfigure current -fill red}\n     .c bind vtx <Any-Leave> {.c itemconfigure current -fill brown}\n     .c bind vtx <ButtonPress-1> {down .c %x %y}\n     .c bind vtx <ButtonRelease-1> {.c dtag selected}\n     bind .c <B1-Motion> {move .c %x %y}\n\n     focus .c\n     draw .c\n }\n\n main\n\n        '
                names      ('tk', 'eval', 'poly')
                varnames   ('self', 'demo')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'demo_polygon_round'
-               firstlineno 459
+               firstlineno 466
                lnotab 0x020104683e01
             'content'
             code
                argcount  : 4
                nlocals   : 12
                stacksize : 6
                flags     : 11
@@ -1218,68 +1293,68 @@
                   097c09a00600000000000000000000000000000000000000007c03a60100
                   00ab01000000000000000001007c09a00700000000000000000000000000
                   00000000000000a6000000ab0000000000000000000100640064006400a6
                   020000ab02000000000000000001006e0b23003100730477027803590077
                   01010059000100010002007c067c08ac07a6010000ab0100000000000000
                   007d0a02007c006a0800000000000000007c017c02660264087c0a69017c
                   04a4018e017d0b7c0b5300
-               567           0 RESUME                   0
+               574           0 RESUME                   0
                
-               568           2 LOAD_CONST               1 (0)
+               575           2 LOAD_CONST               1 (0)
                              4 LOAD_CONST               2 (('mkstemp',))
                              6 IMPORT_NAME              0 (tempfile)
                              8 IMPORT_FROM              1 (mkstemp)
                             10 STORE_FAST               5 (mkstemp)
                             12 POP_TOP
                
-               569          14 LOAD_CONST               1 (0)
+               576          14 LOAD_CONST               1 (0)
                             16 LOAD_CONST               3 (('SvgImage',))
                             18 IMPORT_NAME              2 (tksvg)
                             20 IMPORT_FROM              3 (SvgImage)
                             22 STORE_FAST               6 (SvgImage)
                             24 POP_TOP
                
-               571          26 PUSH_NULL
+               578          26 PUSH_NULL
                             28 LOAD_FAST                5 (mkstemp)
                             30 LOAD_CONST               4 ('.svg')
                             32 KW_NAMES                 5
                             34 PRECALL                  1
                             38 CALL                     1
                             48 UNPACK_SEQUENCE          2
                             52 STORE_FAST               7 (_)
                             54 STORE_FAST               8 (file)
                
-               572          56 LOAD_GLOBAL              9 (NULL + print)
+               579          56 LOAD_GLOBAL              9 (NULL + print)
                             68 LOAD_FAST                8 (file)
                             70 PRECALL                  1
                             74 CALL                     1
                             84 POP_TOP
                
-               573          86 LOAD_GLOBAL             11 (NULL + open)
+               580          86 LOAD_GLOBAL             11 (NULL + open)
                             98 LOAD_FAST                8 (file)
                            100 LOAD_CONST               6 ('w')
                            102 PRECALL                  2
                            106 CALL                     2
                            116 BEFORE_WITH
                            118 STORE_FAST               9 (f)
                
-               574         120 LOAD_FAST                9 (f)
+               581         120 LOAD_FAST                9 (f)
                            122 LOAD_METHOD              6 (write)
                            144 LOAD_FAST                3 (content)
                            146 PRECALL                  1
                            150 CALL                     1
                            160 POP_TOP
                
-               575         162 LOAD_FAST                9 (f)
+               582         162 LOAD_FAST                9 (f)
                            164 LOAD_METHOD              7 (close)
                            186 PRECALL                  0
                            190 CALL                     0
                            200 POP_TOP
                
-               573         202 LOAD_CONST               0 (None)
+               580         202 LOAD_CONST               0 (None)
                            204 LOAD_CONST               0 (None)
                            206 LOAD_CONST               0 (None)
                            208 PRECALL                  2
                            212 CALL                     2
                            222 POP_TOP
                            224 JUMP_FORWARD            11 (to 248)
                        >>  226 PUSH_EXC_INFO
@@ -1290,37 +1365,37 @@
                            236 POP_EXCEPT
                            238 RERAISE                  1
                        >>  240 POP_TOP
                            242 POP_EXCEPT
                            244 POP_TOP
                            246 POP_TOP
                
-               576     >>  248 PUSH_NULL
+               583     >>  248 PUSH_NULL
                            250 LOAD_FAST                6 (SvgImage)
                            252 LOAD_FAST                8 (file)
                            254 KW_NAMES                 7
                            256 PRECALL                  1
                            260 CALL                     1
                            270 STORE_FAST              10 (image)
                
-               578         272 PUSH_NULL
+               585         272 PUSH_NULL
                            274 LOAD_FAST                0 (self)
                            276 LOAD_ATTR                8 (create_image)
                            286 LOAD_FAST                1 (x)
                            288 LOAD_FAST                2 (y)
                            290 BUILD_TUPLE              2
                            292 LOAD_CONST               8 ('image')
                            294 LOAD_FAST               10 (image)
                            296 BUILD_MAP                1
                            298 LOAD_FAST                4 (kwargs)
                            300 DICT_MERGE               1
                            302 CALL_FUNCTION_EX         1
                            304 STORE_FAST              11 (i)
                
-               580         306 LOAD_FAST               11 (i)
+               587         306 LOAD_FAST               11 (i)
                            308 RETURN_VALUE
                ExceptionTable:
                  118 to 200 -> 226 [1] lasti
                  226 to 232 -> 234 [3] lasti
                  240 to 240 -> 234 [3] lasti
                consts
                   None
@@ -1334,15 +1409,15 @@
                   'image'
                names      ('tempfile', 'mkstemp', 'tksvg', 'SvgImage', 'print', 'open', 'write', 'close', 'create_image')
                varnames   ('self', 'x', 'y', 'content', 'kwargs', 'mkstemp', 'SvgImage', '_', 'file', 'f', 'image', 'i')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'create_svg_image'
-               firstlineno 567
+               firstlineno 574
                lnotab 0x02010c010c021e011e0122012a0128fe2e0318022202
             10
             18
             code
                argcount  : 6
                nlocals   : 10
                stacksize : 8
@@ -1359,17 +1434,17 @@
                   0364057a0500007a0000007c027c0364057a0500007a0000007c05a60500
                   00ab0500000000000000007d087c00a00000000000000000000000000000
                   000000000000007c017c0364027a0500007a0000007c047a0000007c027c
                   0364027a0500007a0000007c047a0000007c017c0364057a0500007a0000
                   007c047a0a00007c027c0364057a0500007a0000007c047a0a00007c0564
                   027a0b00006403ac04a6060000ab0600000000000000007d097c067c077c
                   087c0966045300
-               582           0 RESUME                   0
+               589           0 RESUME                   0
                
-               583           2 LOAD_FAST                0 (self)
+               590           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (create_round_rect4)
                             26 LOAD_FAST                1 (_AdwDrawEngine__x)
                             28 LOAD_FAST                2 (_AdwDrawEngine__y)
                             30 LOAD_FAST                1 (_AdwDrawEngine__x)
                             32 LOAD_FAST                3 (size)
                             34 LOAD_CONST               1 (5)
                             36 BINARY_OP                5 (*)
@@ -1380,15 +1455,15 @@
                             50 BINARY_OP                5 (*)
                             54 BINARY_OP                0 (+)
                             58 LOAD_FAST                5 (radius)
                             60 PRECALL                  5
                             64 CALL                     5
                             74 STORE_FAST               6 (_1)
                
-               584          76 LOAD_FAST                0 (self)
+               591          76 LOAD_FAST                0 (self)
                             78 LOAD_METHOD              0 (create_round_rect4)
                            100 LOAD_FAST                1 (_AdwDrawEngine__x)
                            102 LOAD_FAST                4 (padding)
                            104 BINARY_OP                0 (+)
                            108 LOAD_FAST                2 (_AdwDrawEngine__y)
                            110 LOAD_FAST                4 (padding)
                            112 BINARY_OP                0 (+)
@@ -1411,15 +1486,15 @@
                            160 BINARY_OP               11 (/)
                            164 LOAD_CONST               3 ('white')
                            166 KW_NAMES                 4
                            168 PRECALL                  6
                            172 CALL                     6
                            182 STORE_FAST               7 (_2)
                
-               585         184 LOAD_FAST                0 (self)
+               592         184 LOAD_FAST                0 (self)
                            186 LOAD_METHOD              0 (create_round_rect4)
                            208 LOAD_FAST                1 (_AdwDrawEngine__x)
                            210 LOAD_FAST                3 (size)
                            212 LOAD_CONST               2 (2)
                            214 BINARY_OP                5 (*)
                            218 BINARY_OP                0 (+)
                            222 LOAD_FAST                2 (_AdwDrawEngine__y)
@@ -1438,15 +1513,15 @@
                            256 BINARY_OP                5 (*)
                            260 BINARY_OP                0 (+)
                            264 LOAD_FAST                5 (radius)
                            266 PRECALL                  5
                            270 CALL                     5
                            280 STORE_FAST               8 (_3)
                
-               586         282 LOAD_FAST                0 (self)
+               593         282 LOAD_FAST                0 (self)
                            284 LOAD_METHOD              0 (create_round_rect4)
                            306 LOAD_FAST                1 (_AdwDrawEngine__x)
                            308 LOAD_FAST                3 (size)
                            310 LOAD_CONST               2 (2)
                            312 BINARY_OP                5 (*)
                            316 BINARY_OP                0 (+)
                            320 LOAD_FAST                4 (padding)
@@ -1477,15 +1552,15 @@
                            390 BINARY_OP               11 (/)
                            394 LOAD_CONST               3 ('white')
                            396 KW_NAMES                 4
                            398 PRECALL                  6
                            402 CALL                     6
                            412 STORE_FAST               9 (_4)
                
-               587         414 LOAD_FAST                6 (_1)
+               594         414 LOAD_FAST                6 (_1)
                            416 LOAD_FAST                7 (_2)
                            418 LOAD_FAST                8 (_3)
                            420 LOAD_FAST                9 (_4)
                            422 BUILD_TUPLE              4
                            424 RETURN_VALUE
                consts
                   None
@@ -1496,77 +1571,116 @@
                   7
                names      ('create_round_rect4',)
                varnames   ('self', '_AdwDrawEngine__x', '_AdwDrawEngine__y', 'size', 'padding', 'radius', '_1', '_2', '_3', '_4')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
                name       'draw_copy_icon'
-               firstlineno 582
+               firstlineno 589
                lnotab 0x02014a016c0162018401
+            16
+            code
+               argcount  : 7
+               nlocals   : 12
+               stacksize : 6
+               flags     : 15
+               code
+                  0x9700640164026c006d017d0901007405000000000000000000007c037c
+                  0466027c067c0567037c07a201520069007c08a4018e017d0a7c09a00300
+                  000000000000000000000000000000000000007c0aa6010000ab01000000
+                  00000000007d0b7c00a00400000000000000000000000000000000000000
+                  007c017c027c0b6403ac04a6040000ab0400000000000000005300
+               596           0 RESUME                   0
+               
+               597           2 LOAD_CONST               1 (0)
+                             4 LOAD_CONST               2 (('ImageTk',))
+                             6 IMPORT_NAME              0 (PIL)
+                             8 IMPORT_FROM              1 (ImageTk)
+                            10 STORE_FAST               9 (ImageTk)
+                            12 POP_TOP
+               
+               598          14 LOAD_GLOBAL              5 (NULL + rounded_rectangle)
+                            26 LOAD_FAST                3 (_AdwDrawEngine__width)
+                            28 LOAD_FAST                4 (_AdwDrawEngine__height)
+                            30 BUILD_TUPLE              2
+                            32 LOAD_FAST                6 (radius)
+                            34 LOAD_FAST                5 (fill)
+                            36 BUILD_LIST               3
+                            38 LOAD_FAST                7 (args)
+                            40 LIST_EXTEND              1
+                            42 LIST_TO_TUPLE
+                            44 BUILD_MAP                0
+                            46 LOAD_FAST                8 (kwargs)
+                            48 DICT_MERGE               1
+                            50 CALL_FUNCTION_EX         1
+                            52 STORE_FAST              10 (img)
+               
+               599          54 LOAD_FAST                9 (ImageTk)
+                            56 LOAD_METHOD              3 (PhotoImage)
+                            78 LOAD_FAST               10 (img)
+                            80 PRECALL                  1
+                            84 CALL                     1
+                            94 STORE_FAST              11 (photo)
+               
+               601          96 LOAD_FAST                0 (self)
+                            98 LOAD_METHOD              4 (create_image)
+                           120 LOAD_FAST                1 (_AdwDrawEngine__x)
+                           122 LOAD_FAST                2 (_AdwDrawEngine__y)
+                           124 LOAD_FAST               11 (photo)
+                           126 LOAD_CONST               3 ('nw')
+                           128 KW_NAMES                 4
+                           130 PRECALL                  4
+                           134 CALL                     4
+                           144 RETURN_VALUE
+               consts
+                  None
+                  0
+                  ('ImageTk',)
+                  'nw'
+                  ('image', 'anchor')
+               names      ('PIL', 'ImageTk', 'rounded_rectangle', 'PhotoImage', 'create_image')
+               varnames   ('self', '_AdwDrawEngine__x', '_AdwDrawEngine__y', '_AdwDrawEngine__width', '_AdwDrawEngine__height', 'fill', 'radius', 'args', 'kwargs', 'ImageTk', 'img', 'photo')
+               freevars   ()
+               cellvars   ()
+               filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
+               name       'create_round_rectangle5'
+               firstlineno 596
+               lnotab 0x02010c0128012a02
             ('x',)
             (5, 2, 'white', 'black')
             ('black', 'black')
             (10, 10, 18)
-         names      ('__name__', '__module__', '__qualname__', '__init__', 'win32_high_dpi', 'draw_gradient', 'float', 'create_round_rectangle', 'create_round_rect', 'create_round_rectangle2', 'create_round_rect2', 'str', 'create_round_rectangle3', 'create_round_rect3', 'create_round_rectangle4', 'create_round_rect4', 'polygon_round', 'poly_round', 'demo_polygon_round', 'create_svg_image', 'draw_copy_icon', '__classcell__')
+            ('black', 16)
+         names      ('__name__', '__module__', '__qualname__', '__init__', 'win32_high_dpi', 'draw_gradient', 'float', 'create_round_rectangle', 'create_round_rect', 'create_round_rectangle2', 'create_round_rect2', 'str', 'create_round_rectangle3', 'create_round_rect3', 'create_round_rectangle4', 'create_round_rect4', 'polygon_round', 'poly_round', 'demo_polygon_round', 'create_svg_image', 'draw_copy_icon', 'create_round_rectangle5', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
          name       'AdwDrawEngine'
-         firstlineno 226
+         firstlineno 233
          lnotab
             0x0c010a03060408430e1f04020644040212110402061a04020806040206
-            6c0c0f
+            6c0c0f0807
       'AdwDrawEngine'
       '__main__'
       ('Tk',)
-      10
-      15
-      150
-      50
       160
       300
-      '<Configure>'
-      code
-         argcount  : 1
-         nlocals   : 1
-         stacksize : 5
-         flags     : 3
-         code
-            0x9700740000000000000000000000a00100000000000000000000000000
-            00000000000000640164026403a6030000ab0300000000000000005300
-         599           0 RESUME                   0
-                       2 LOAD_GLOBAL              0 (canvas)
-                      14 LOAD_METHOD              1 (draw_gradient)
-                      36 LOAD_CONST               1 ('#87e9bb')
-                      38 LOAD_CONST               2 ('#d3a6f5')
-                      40 LOAD_CONST               3 ('x')
-                      42 PRECALL                  3
-                      46 CALL                     3
-                      56 RETURN_VALUE
-         consts
-            None
-            '#87e9bb'
-            '#d3a6f5'
-            'x'
-         names      ('canvas', 'draw_gradient')
-         varnames   ('event',)
-         freevars   ()
-         cellvars   ()
-         filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
-         name       '<lambda>'
-         firstlineno 599
-         lnotab 0x
+      50
+      100
+      16
+      'lightblue'
+      ('radius', 'fill')
       'both'
       'yes'
       ('fill', 'expand')
       None
-   names      ('tkinter', 'Canvas', 'poly', 'poly2', 'AdwDrawEngine', '__name__', 'Tk', 'root', 'canvas', 'create_round_rect3', 'create_round_rect4', 'bind', 'pack', 'mainloop')
+   names      ('tkinter', 'Canvas', 'rounded_rectangle', 'poly', 'poly2', 'AdwDrawEngine', '__name__', 'Tk', 'root', 'canvas', 'create_round_rect4', 'create_round_rectangle5', 'pack', 'mainloop')
    varnames   ()
    freevars   ()
    cellvars   ()
    filename   'D:\\tkadw\\tkadw\\canvas\\drawengine.py'
    name       '<module>'
    firstlineno 1
    lnotab
-      0x00ff02010c02047f0015044b1c7f007f006d0c010c0214021402340132
-      022e022e022cf2
+      0x00ff02010c020607047f0015044b1c7f007f00750c010c021402140332
+      0236042e022cf0
```

### Comparing `tkadw-0.2.1/tkadw/canvas/__pycache__/entry.cpython-311.pyc` & `tkadw-0.2.2/tkadw/canvas/__pycache__/entry.cpython-311.pyc`

 * *Files 11% similar despite different names*

#### Python bytecode

```diff
@@ -1,10 +1,10 @@
 magic:    0xa70d0d0a
-moddate:  0x3f4f9664 (Sat Jun 24 02:04:47 2023 UTC)
-files sz: 17378
+moddate:  0x25de9664 (Sat Jun 24 12:14:29 2023 UTC)
+files sz: 18319
 code
    argcount  : 0
    nlocals   : 0
    stacksize : 5
    flags     : 0
    code
       0x9700640064016c006d015a016d025a020100640064026c036d045a0401
@@ -58,229 +58,229 @@
                 36 MAKE_FUNCTION            0
                 38 LOAD_CONST               4 ('AdwDrawBasicEntry')
                 40 LOAD_NAME                4 (AdwDrawEngine)
                 42 PRECALL                  3
                 46 CALL                     3
                 56 STORE_NAME               5 (AdwDrawBasicEntry)
    
-   211          58 PUSH_NULL
+   225          58 PUSH_NULL
                 60 LOAD_BUILD_CLASS
-                62 LOAD_CONST               5 (<code object AdwDrawEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 211>)
+                62 LOAD_CONST               5 (<code object AdwDrawEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 225>)
                 64 MAKE_FUNCTION            0
                 66 LOAD_CONST               6 ('AdwDrawEntry')
                 68 LOAD_NAME                5 (AdwDrawBasicEntry)
                 70 PRECALL                  3
                 74 CALL                     3
                 84 STORE_NAME               6 (AdwDrawEntry)
    
-   216          86 PUSH_NULL
+   230          86 PUSH_NULL
                 88 LOAD_BUILD_CLASS
-                90 LOAD_CONST               7 (<code object AdwDrawDarkEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 216>)
+                90 LOAD_CONST               7 (<code object AdwDrawDarkEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 230>)
                 92 MAKE_FUNCTION            0
                 94 LOAD_CONST               8 ('AdwDrawDarkEntry')
                 96 LOAD_NAME                5 (AdwDrawBasicEntry)
                 98 PRECALL                  3
                102 CALL                     3
                112 STORE_NAME               7 (AdwDrawDarkEntry)
    
-   222         114 PUSH_NULL
+   236         114 PUSH_NULL
                116 LOAD_BUILD_CLASS
-               118 LOAD_CONST               9 (<code object AdwDrawBasicRoundEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 222>)
+               118 LOAD_CONST               9 (<code object AdwDrawBasicRoundEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 236>)
                120 MAKE_FUNCTION            0
                122 LOAD_CONST              10 ('AdwDrawBasicRoundEntry')
                124 LOAD_NAME                5 (AdwDrawBasicEntry)
                126 PRECALL                  3
                130 CALL                     3
                140 STORE_NAME               8 (AdwDrawBasicRoundEntry)
    
-   372         142 PUSH_NULL
+   389         142 PUSH_NULL
                144 LOAD_BUILD_CLASS
-               146 LOAD_CONST              11 (<code object AdwDrawRoundEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 372>)
+               146 LOAD_CONST              11 (<code object AdwDrawRoundEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 389>)
                148 MAKE_FUNCTION            0
                150 LOAD_CONST              12 ('AdwDrawRoundEntry')
                152 LOAD_NAME                8 (AdwDrawBasicRoundEntry)
                154 PRECALL                  3
                158 CALL                     3
                168 STORE_NAME               9 (AdwDrawRoundEntry)
    
-   377         170 PUSH_NULL
+   394         170 PUSH_NULL
                172 LOAD_BUILD_CLASS
-               174 LOAD_CONST              13 (<code object AdwDrawRoundDarkEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 377>)
+               174 LOAD_CONST              13 (<code object AdwDrawRoundDarkEntry, file "D:\tkadw\tkadw\canvas\entry.py", line 394>)
                176 MAKE_FUNCTION            0
                178 LOAD_CONST              14 ('AdwDrawRoundDarkEntry')
                180 LOAD_NAME                8 (AdwDrawBasicRoundEntry)
                182 PRECALL                  3
                186 CALL                     3
                196 STORE_NAME              10 (AdwDrawRoundDarkEntry)
    
-   382         198 PUSH_NULL
+   399         198 PUSH_NULL
                200 LOAD_BUILD_CLASS
-               202 LOAD_CONST              15 (<code object AdwDrawBasicRoundEntry3, file "D:\tkadw\tkadw\canvas\entry.py", line 382>)
+               202 LOAD_CONST              15 (<code object AdwDrawBasicRoundEntry3, file "D:\tkadw\tkadw\canvas\entry.py", line 399>)
                204 MAKE_FUNCTION            0
                206 LOAD_CONST              16 ('AdwDrawBasicRoundEntry3')
                208 LOAD_NAME                8 (AdwDrawBasicRoundEntry)
                210 PRECALL                  3
                214 CALL                     3
                224 STORE_NAME              11 (AdwDrawBasicRoundEntry3)
    
-   476         226 PUSH_NULL
+   496         226 PUSH_NULL
                228 LOAD_BUILD_CLASS
-               230 LOAD_CONST              17 (<code object AdwDrawRoundEntry3, file "D:\tkadw\tkadw\canvas\entry.py", line 476>)
+               230 LOAD_CONST              17 (<code object AdwDrawRoundEntry3, file "D:\tkadw\tkadw\canvas\entry.py", line 496>)
                232 MAKE_FUNCTION            0
                234 LOAD_CONST              18 ('AdwDrawRoundEntry3')
                236 LOAD_NAME               11 (AdwDrawBasicRoundEntry3)
                238 PRECALL                  3
                242 CALL                     3
                252 STORE_NAME              12 (AdwDrawRoundEntry3)
    
-   481         254 PUSH_NULL
+   501         254 PUSH_NULL
                256 LOAD_BUILD_CLASS
-               258 LOAD_CONST              19 (<code object AdwDrawRoundDarkEntry3, file "D:\tkadw\tkadw\canvas\entry.py", line 481>)
+               258 LOAD_CONST              19 (<code object AdwDrawRoundDarkEntry3, file "D:\tkadw\tkadw\canvas\entry.py", line 501>)
                260 MAKE_FUNCTION            0
                262 LOAD_CONST              20 ('AdwDrawRoundDarkEntry3')
                264 LOAD_NAME               11 (AdwDrawBasicRoundEntry3)
                266 PRECALL                  3
                270 CALL                     3
                280 STORE_NAME              13 (AdwDrawRoundDarkEntry3)
    
-   486         282 LOAD_NAME               14 (__name__)
+   506         282 LOAD_NAME               14 (__name__)
                284 LOAD_CONST              21 ('__main__')
                286 COMPARE_OP               2 (==)
                292 POP_JUMP_FORWARD_IF_FALSE   254 (to 802)
    
-   487         294 LOAD_CONST               0 (0)
+   507         294 LOAD_CONST               0 (0)
                296 LOAD_CONST              22 (('Tk',))
                298 IMPORT_NAME             15 (tkinter)
                300 IMPORT_FROM             16 (Tk)
                302 STORE_NAME              16 (Tk)
                304 POP_TOP
    
-   489         306 PUSH_NULL
+   509         306 PUSH_NULL
                308 LOAD_NAME               16 (Tk)
                310 PRECALL                  0
                314 CALL                     0
                324 STORE_NAME              17 (root)
    
-   491         326 PUSH_NULL
+   511         326 PUSH_NULL
                328 LOAD_NAME                6 (AdwDrawEntry)
                330 LOAD_CONST              23 ('Hello')
                332 KW_NAMES                24
                334 PRECALL                  1
                338 CALL                     1
                348 STORE_NAME              18 (entry1)
    
-   492         350 LOAD_NAME               18 (entry1)
+   512         350 LOAD_NAME               18 (entry1)
                352 LOAD_METHOD             19 (pack)
                374 LOAD_CONST              25 ('x')
                376 LOAD_CONST              26 (5)
                378 LOAD_CONST              26 (5)
                380 KW_NAMES                27
                382 PRECALL                  3
                386 CALL                     3
                396 POP_TOP
    
-   494         398 PUSH_NULL
+   514         398 PUSH_NULL
                400 LOAD_NAME                7 (AdwDrawDarkEntry)
                402 LOAD_CONST              23 ('Hello')
                404 KW_NAMES                24
                406 PRECALL                  1
                410 CALL                     1
                420 STORE_NAME              20 (entry2)
    
-   495         422 LOAD_NAME               20 (entry2)
+   515         422 LOAD_NAME               20 (entry2)
                424 LOAD_METHOD             19 (pack)
                446 LOAD_CONST              25 ('x')
                448 LOAD_CONST              26 (5)
                450 LOAD_CONST              26 (5)
                452 KW_NAMES                27
                454 PRECALL                  3
                458 CALL                     3
                468 POP_TOP
    
-   497         470 PUSH_NULL
+   517         470 PUSH_NULL
                472 LOAD_NAME                9 (AdwDrawRoundEntry)
                474 LOAD_CONST              23 ('Hello')
                476 KW_NAMES                24
                478 PRECALL                  1
                482 CALL                     1
                492 STORE_NAME              21 (entry3)
    
-   498         494 LOAD_NAME               21 (entry3)
+   518         494 LOAD_NAME               21 (entry3)
                496 LOAD_METHOD             19 (pack)
                518 LOAD_CONST              25 ('x')
                520 LOAD_CONST              26 (5)
                522 LOAD_CONST              26 (5)
                524 KW_NAMES                27
                526 PRECALL                  3
                530 CALL                     3
                540 POP_TOP
    
-   500         542 PUSH_NULL
+   520         542 PUSH_NULL
                544 LOAD_NAME               10 (AdwDrawRoundDarkEntry)
                546 LOAD_CONST              23 ('Hello')
                548 KW_NAMES                24
                550 PRECALL                  1
                554 CALL                     1
                564 STORE_NAME              22 (entry4)
    
-   501         566 LOAD_NAME               22 (entry4)
+   521         566 LOAD_NAME               22 (entry4)
                568 LOAD_METHOD             19 (pack)
                590 LOAD_CONST              25 ('x')
                592 LOAD_CONST              26 (5)
                594 LOAD_CONST              26 (5)
                596 KW_NAMES                27
                598 PRECALL                  3
                602 CALL                     3
                612 POP_TOP
    
-   503         614 PUSH_NULL
+   523         614 PUSH_NULL
                616 LOAD_NAME               12 (AdwDrawRoundEntry3)
                618 LOAD_CONST              23 ('Hello')
                620 KW_NAMES                24
                622 PRECALL                  1
                626 CALL                     1
                636 STORE_NAME              23 (entry5)
    
-   504         638 LOAD_NAME               23 (entry5)
+   524         638 LOAD_NAME               23 (entry5)
                640 LOAD_METHOD             19 (pack)
                662 LOAD_CONST              25 ('x')
                664 LOAD_CONST              26 (5)
                666 LOAD_CONST              26 (5)
                668 KW_NAMES                27
                670 PRECALL                  3
                674 CALL                     3
                684 POP_TOP
    
-   506         686 PUSH_NULL
+   526         686 PUSH_NULL
                688 LOAD_NAME               13 (AdwDrawRoundDarkEntry3)
                690 LOAD_CONST              23 ('Hello')
                692 KW_NAMES                24
                694 PRECALL                  1
                698 CALL                     1
                708 STORE_NAME              24 (entry6)
    
-   507         710 LOAD_NAME               24 (entry6)
+   527         710 LOAD_NAME               24 (entry6)
                712 LOAD_METHOD             19 (pack)
                734 LOAD_CONST              25 ('x')
                736 LOAD_CONST              26 (5)
                738 LOAD_CONST              26 (5)
                740 KW_NAMES                27
                742 PRECALL                  3
                746 CALL                     3
                756 POP_TOP
    
-   509         758 LOAD_NAME               17 (root)
+   529         758 LOAD_NAME               17 (root)
                760 LOAD_METHOD             25 (mainloop)
                782 PRECALL                  0
                786 CALL                     0
                796 POP_TOP
                798 LOAD_CONST              28 (None)
                800 RETURN_VALUE
    
-   486     >>  802 LOAD_CONST              28 (None)
+   506     >>  802 LOAD_CONST              28 (None)
                804 RETURN_VALUE
    consts
       0
       ('Font', 'nametofont')
       ('AdwDrawEngine',)
       code
          argcount  : 0
@@ -312,80 +312,80 @@
                       26 BUILD_TUPLE              2
                       28 LOAD_CLOSURE             0 (__class__)
                       30 BUILD_TUPLE              1
                       32 LOAD_CONST               6 (<code object __init__, file "D:\tkadw\tkadw\canvas\entry.py", line 7>)
                       34 MAKE_FUNCTION           14 (kwdefaults, annotations, closure)
                       36 STORE_NAME               4 (__init__)
          
-          43          38 LOAD_CONST               5 ('text')
+          44          38 LOAD_CONST               5 ('text')
                       40 LOAD_NAME                3 (str)
                       42 BUILD_TUPLE              2
-                      44 LOAD_CONST               7 (<code object set, file "D:\tkadw\tkadw\canvas\entry.py", line 43>)
+                      44 LOAD_CONST               7 (<code object set, file "D:\tkadw\tkadw\canvas\entry.py", line 44>)
                       46 MAKE_FUNCTION            4 (annotations)
                       48 STORE_NAME               5 (set)
          
-          46          50 LOAD_CONST               8 (<code object get, file "D:\tkadw\tkadw\canvas\entry.py", line 46>)
+          47          50 LOAD_CONST               8 (<code object get, file "D:\tkadw\tkadw\canvas\entry.py", line 47>)
                       52 MAKE_FUNCTION            0
                       54 STORE_NAME               6 (get)
          
-          49          56 LOAD_CONST               9 (<code object _other, file "D:\tkadw\tkadw\canvas\entry.py", line 49>)
+          50          56 LOAD_CONST               9 (<code object _other, file "D:\tkadw\tkadw\canvas\entry.py", line 50>)
                       58 MAKE_FUNCTION            0
                       60 STORE_NAME               7 (_other)
          
-          53          62 LOAD_CONST              10 (<code object _draw, file "D:\tkadw\tkadw\canvas\entry.py", line 53>)
+          54          62 LOAD_CONST              10 (<code object _draw, file "D:\tkadw\tkadw\canvas\entry.py", line 54>)
                       64 MAKE_FUNCTION            0
                       66 STORE_NAME               8 (_draw)
          
-          81          68 LOAD_CONST              23 ((None,))
-                      70 LOAD_CONST              12 (<code object _focus, file "D:\tkadw\tkadw\canvas\entry.py", line 81>)
+          85          68 LOAD_CONST              23 ((None,))
+                      70 LOAD_CONST              12 (<code object _focus, file "D:\tkadw\tkadw\canvas\entry.py", line 85>)
                       72 MAKE_FUNCTION            1 (defaults)
                       74 STORE_NAME               9 (_focus)
          
-          90          76 LOAD_CONST              23 ((None,))
-                      78 LOAD_CONST              13 (<code object _focusout, file "D:\tkadw\tkadw\canvas\entry.py", line 90>)
+          95          76 LOAD_CONST              23 ((None,))
+                      78 LOAD_CONST              13 (<code object _focusout, file "D:\tkadw\tkadw\canvas\entry.py", line 95>)
                       80 MAKE_FUNCTION            1 (defaults)
                       82 STORE_NAME              10 (_focusout)
          
-          99          84 LOAD_CONST              23 ((None,))
-                      86 LOAD_CONST              14 (<code object _click, file "D:\tkadw\tkadw\canvas\entry.py", line 99>)
+         105          84 LOAD_CONST              23 ((None,))
+                      86 LOAD_CONST              14 (<code object _click, file "D:\tkadw\tkadw\canvas\entry.py", line 105>)
                       88 MAKE_FUNCTION            1 (defaults)
                       90 STORE_NAME              11 (_click)
          
-         102          92 LOAD_CONST              23 ((None,))
-                      94 LOAD_CONST              15 (<code object _hover, file "D:\tkadw\tkadw\canvas\entry.py", line 102>)
+         108          92 LOAD_CONST              23 ((None,))
+                      94 LOAD_CONST              15 (<code object _hover, file "D:\tkadw\tkadw\canvas\entry.py", line 108>)
                       96 MAKE_FUNCTION            1 (defaults)
                       98 STORE_NAME              12 (_hover)
          
-         105         100 LOAD_CONST              23 ((None,))
-                     102 LOAD_CONST              16 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\entry.py", line 105>)
+         111         100 LOAD_CONST              23 ((None,))
+                     102 LOAD_CONST              16 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\entry.py", line 111>)
                      104 MAKE_FUNCTION            1 (defaults)
                      106 STORE_NAME              13 (_hover_release)
          
-         116         108 LOAD_CONST              23 ((None,))
+         123         108 LOAD_CONST              23 ((None,))
                      110 LOAD_CONST              17 ('font')
                      112 LOAD_NAME               14 (Font)
                      114 BUILD_TUPLE              2
-                     116 LOAD_CONST              18 (<code object font, file "D:\tkadw\tkadw\canvas\entry.py", line 116>)
+                     116 LOAD_CONST              18 (<code object font, file "D:\tkadw\tkadw\canvas\entry.py", line 123>)
                      118 MAKE_FUNCTION            5 (defaults, annotations)
                      120 STORE_NAME              15 (font)
          
-         122         122 LOAD_CONST              19 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 122>)
+         129         122 LOAD_CONST              19 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 129>)
                      124 MAKE_FUNCTION            0
                      126 STORE_NAME              16 (default_palette)
          
-         125         128 LOAD_CONST              20 (<code object palette_light, file "D:\tkadw\tkadw\canvas\entry.py", line 125>)
+         132         128 LOAD_CONST              20 (<code object palette_light, file "D:\tkadw\tkadw\canvas\entry.py", line 132>)
                      130 MAKE_FUNCTION            0
                      132 STORE_NAME              17 (palette_light)
          
-         152         134 LOAD_CONST              21 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\entry.py", line 152>)
+         159         134 LOAD_CONST              21 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\entry.py", line 159>)
                      136 MAKE_FUNCTION            0
                      138 STORE_NAME              18 (palette_dark)
          
-         179         140 LOAD_CONST              23 ((None,))
-                     142 LOAD_CONST              22 (<code object palette, file "D:\tkadw\tkadw\canvas\entry.py", line 179>)
+         186         140 LOAD_CONST              23 ((None,))
+                     142 LOAD_CONST              22 (<code object palette, file "D:\tkadw\tkadw\canvas\entry.py", line 186>)
                      144 MAKE_FUNCTION            1 (defaults)
                      146 STORE_NAME              19 (palette)
                      148 LOAD_CLOSURE             0 (__class__)
                      150 COPY                     1
                      152 STORE_NAME              20 (__classcell__)
                      154 RETURN_VALUE
          consts
@@ -411,34 +411,34 @@
                   007c00a0080000000000000000000000000000000000000000a6000000ab
                   00000000000000000001007c00a009000000000000000000000000000000
                   0000000000a6000000ab00000000000000000001007c037c005f0a000000
                   00000000007c006a0b00000000000000007c005f0c00000000000000007c
                   006a0d00000000000000007c005f0e00000000000000007c006a0f000000
                   00000000007c005f1000000000000000007c006a1100000000000000007c
                   005f1200000000000000007c006a1300000000000000007c005f14000000
-                  0000000000742b000000000000000000006405a6010000ab010000000000
-                  0000007c005f1600000000000000007c00a0170000000000000000000000
-                  00000000000000000064067c006a1800000000000000006407ac08a60300
-                  00ab03000000000000000001007c00a01700000000000000000000000000
-                  0000000000000064097c006a1900000000000000006407ac08a6030000ab
-                  03000000000000000001007c00a017000000000000000000000000000000
-                  0000000000640a7c006a1a00000000000000006407ac08a6030000ab0300
-                  0000000000000001007c00a0170000000000000000000000000000000000
-                  000000640b7c006a1b00000000000000006407ac08a6030000ab03000000
-                  000000000001007c00a01700000000000000000000000000000000000000
-                  00640c7c006a1c00000000000000006407ac08a6030000ab030000000000
-                  00000001007c006a070000000000000000a0170000000000000000000000
-                  000000000000000000640c7c006a1c00000000000000006407ac08a60300
-                  00ab03000000000000000001007c00a01700000000000000000000000000
-                  00000000000000640d7c006a1d00000000000000006407ac08a6030000ab
-                  03000000000000000001007c006a070000000000000000a0170000000000
-                  000000000000000000000000000000640d7c006a1d000000000000000064
-                  07ac08a6030000ab03000000000000000001007c00a01800000000000000
-                  000000000000000000000000006400a6010000ab01000000000000000001
-                  0064005300
+                  00000000007c006a1500000000000000007c005f16000000000000000074
+                  2f000000000000000000006405a6010000ab0100000000000000007c005f
+                  1800000000000000007c00a0190000000000000000000000000000000000
+                  00000064067c006a1a00000000000000006407ac08a6030000ab03000000
+                  000000000001007c00a01900000000000000000000000000000000000000
+                  0064097c006a1b00000000000000006407ac08a6030000ab030000000000
+                  00000001007c00a019000000000000000000000000000000000000000064
+                  0a7c006a1c00000000000000006407ac08a6030000ab0300000000000000
+                  0001007c00a0190000000000000000000000000000000000000000640b7c
+                  006a1d00000000000000006407ac08a6030000ab03000000000000000001
+                  007c00a0190000000000000000000000000000000000000000640c7c006a
+                  1e00000000000000006407ac08a6030000ab03000000000000000001007c
+                  006a070000000000000000a0190000000000000000000000000000000000
+                  000000640c7c006a1e00000000000000006407ac08a6030000ab03000000
+                  000000000001007c00a01900000000000000000000000000000000000000
+                  00640d7c006a1f00000000000000006407ac08a6030000ab030000000000
+                  00000001007c006a070000000000000000a0190000000000000000000000
+                  000000000000000000640d7c006a1f00000000000000006407ac08a60300
+                  00ab03000000000000000001007c00a01a00000000000000000000000000
+                  000000000000006400a6010000ab010000000000000000010064005300
                              0 COPY_FREE_VARS           1
                
                  7           2 RESUME                   0
                
                  9           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
@@ -520,128 +520,133 @@
                
                 26         352 LOAD_FAST                0 (self)
                            354 LOAD_ATTR               15 (entry_text_back)
                            364 LOAD_FAST                0 (self)
                            366 STORE_ATTR              16 (_entry_text_back)
                
                 27         376 LOAD_FAST                0 (self)
-                           378 LOAD_ATTR               17 (entry_bottom_line)
+                           378 LOAD_ATTR               17 (entry_border_width)
                            388 LOAD_FAST                0 (self)
-                           390 STORE_ATTR              18 (_entry_bottom_line)
+                           390 STORE_ATTR              18 (_entry_border_width)
                
                 28         400 LOAD_FAST                0 (self)
-                           402 LOAD_ATTR               19 (entry_bottom_width)
+                           402 LOAD_ATTR               19 (entry_bottom_line)
                            412 LOAD_FAST                0 (self)
-                           414 STORE_ATTR              20 (_entry_bottom_width)
+                           414 STORE_ATTR              20 (_entry_bottom_line)
                
-                30         424 LOAD_GLOBAL             43 (NULL + nametofont)
-                           436 LOAD_CONST               5 ('TkDefaultFont')
-                           438 PRECALL                  1
-                           442 CALL                     1
-                           452 LOAD_FAST                0 (self)
-                           454 STORE_ATTR              22 (entry_text_font)
-               
-                32         464 LOAD_FAST                0 (self)
-                           466 LOAD_METHOD             23 (bind)
-                           488 LOAD_CONST               6 ('<Configure>')
-                           490 LOAD_FAST                0 (self)
-                           492 LOAD_ATTR               24 (_draw)
-                           502 LOAD_CONST               7 ('+')
-                           504 KW_NAMES                 8
-                           506 PRECALL                  3
-                           510 CALL                     3
-                           520 POP_TOP
-               
-                33         522 LOAD_FAST                0 (self)
-                           524 LOAD_METHOD             23 (bind)
-                           546 LOAD_CONST               9 ('<Button>')
-                           548 LOAD_FAST                0 (self)
-                           550 LOAD_ATTR               25 (_click)
-                           560 LOAD_CONST               7 ('+')
-                           562 KW_NAMES                 8
-                           564 PRECALL                  3
-                           568 CALL                     3
-                           578 POP_TOP
-               
-                34         580 LOAD_FAST                0 (self)
-                           582 LOAD_METHOD             23 (bind)
-                           604 LOAD_CONST              10 ('<Enter>')
-                           606 LOAD_FAST                0 (self)
-                           608 LOAD_ATTR               26 (_hover)
-                           618 LOAD_CONST               7 ('+')
-                           620 KW_NAMES                 8
-                           622 PRECALL                  3
-                           626 CALL                     3
-                           636 POP_TOP
-               
-                35         638 LOAD_FAST                0 (self)
-                           640 LOAD_METHOD             23 (bind)
-                           662 LOAD_CONST              11 ('<Leave>')
-                           664 LOAD_FAST                0 (self)
-                           666 LOAD_ATTR               27 (_hover_release)
-                           676 LOAD_CONST               7 ('+')
-                           678 KW_NAMES                 8
-                           680 PRECALL                  3
-                           684 CALL                     3
-                           694 POP_TOP
-               
-                36         696 LOAD_FAST                0 (self)
-                           698 LOAD_METHOD             23 (bind)
-                           720 LOAD_CONST              12 ('<FocusIn>')
-                           722 LOAD_FAST                0 (self)
-                           724 LOAD_ATTR               28 (_focus)
-                           734 LOAD_CONST               7 ('+')
-                           736 KW_NAMES                 8
-                           738 PRECALL                  3
-                           742 CALL                     3
-                           752 POP_TOP
-               
-                37         754 LOAD_FAST                0 (self)
-                           756 LOAD_ATTR                7 (entry)
-                           766 LOAD_METHOD             23 (bind)
-                           788 LOAD_CONST              12 ('<FocusIn>')
-                           790 LOAD_FAST                0 (self)
-                           792 LOAD_ATTR               28 (_focus)
-                           802 LOAD_CONST               7 ('+')
-                           804 KW_NAMES                 8
-                           806 PRECALL                  3
-                           810 CALL                     3
-                           820 POP_TOP
-               
-                38         822 LOAD_FAST                0 (self)
-                           824 LOAD_METHOD             23 (bind)
-                           846 LOAD_CONST              13 ('<FocusOut>')
-                           848 LOAD_FAST                0 (self)
-                           850 LOAD_ATTR               29 (_focusout)
-                           860 LOAD_CONST               7 ('+')
-                           862 KW_NAMES                 8
-                           864 PRECALL                  3
-                           868 CALL                     3
-                           878 POP_TOP
-               
-                39         880 LOAD_FAST                0 (self)
-                           882 LOAD_ATTR                7 (entry)
-                           892 LOAD_METHOD             23 (bind)
-                           914 LOAD_CONST              13 ('<FocusOut>')
-                           916 LOAD_FAST                0 (self)
-                           918 LOAD_ATTR               29 (_focusout)
-                           928 LOAD_CONST               7 ('+')
-                           930 KW_NAMES                 8
-                           932 PRECALL                  3
-                           936 CALL                     3
-                           946 POP_TOP
-               
-                41         948 LOAD_FAST                0 (self)
-                           950 LOAD_METHOD             24 (_draw)
-                           972 LOAD_CONST               0 (None)
-                           974 PRECALL                  1
-                           978 CALL                     1
-                           988 POP_TOP
-                           990 LOAD_CONST               0 (None)
-                           992 RETURN_VALUE
+                29         424 LOAD_FAST                0 (self)
+                           426 LOAD_ATTR               21 (entry_bottom_width)
+                           436 LOAD_FAST                0 (self)
+                           438 STORE_ATTR              22 (_entry_bottom_width)
+               
+                31         448 LOAD_GLOBAL             47 (NULL + nametofont)
+                           460 LOAD_CONST               5 ('TkDefaultFont')
+                           462 PRECALL                  1
+                           466 CALL                     1
+                           476 LOAD_FAST                0 (self)
+                           478 STORE_ATTR              24 (entry_text_font)
+               
+                33         488 LOAD_FAST                0 (self)
+                           490 LOAD_METHOD             25 (bind)
+                           512 LOAD_CONST               6 ('<Configure>')
+                           514 LOAD_FAST                0 (self)
+                           516 LOAD_ATTR               26 (_draw)
+                           526 LOAD_CONST               7 ('+')
+                           528 KW_NAMES                 8
+                           530 PRECALL                  3
+                           534 CALL                     3
+                           544 POP_TOP
+               
+                34         546 LOAD_FAST                0 (self)
+                           548 LOAD_METHOD             25 (bind)
+                           570 LOAD_CONST               9 ('<Button>')
+                           572 LOAD_FAST                0 (self)
+                           574 LOAD_ATTR               27 (_click)
+                           584 LOAD_CONST               7 ('+')
+                           586 KW_NAMES                 8
+                           588 PRECALL                  3
+                           592 CALL                     3
+                           602 POP_TOP
+               
+                35         604 LOAD_FAST                0 (self)
+                           606 LOAD_METHOD             25 (bind)
+                           628 LOAD_CONST              10 ('<Enter>')
+                           630 LOAD_FAST                0 (self)
+                           632 LOAD_ATTR               28 (_hover)
+                           642 LOAD_CONST               7 ('+')
+                           644 KW_NAMES                 8
+                           646 PRECALL                  3
+                           650 CALL                     3
+                           660 POP_TOP
+               
+                36         662 LOAD_FAST                0 (self)
+                           664 LOAD_METHOD             25 (bind)
+                           686 LOAD_CONST              11 ('<Leave>')
+                           688 LOAD_FAST                0 (self)
+                           690 LOAD_ATTR               29 (_hover_release)
+                           700 LOAD_CONST               7 ('+')
+                           702 KW_NAMES                 8
+                           704 PRECALL                  3
+                           708 CALL                     3
+                           718 POP_TOP
+               
+                37         720 LOAD_FAST                0 (self)
+                           722 LOAD_METHOD             25 (bind)
+                           744 LOAD_CONST              12 ('<FocusIn>')
+                           746 LOAD_FAST                0 (self)
+                           748 LOAD_ATTR               30 (_focus)
+                           758 LOAD_CONST               7 ('+')
+                           760 KW_NAMES                 8
+                           762 PRECALL                  3
+                           766 CALL                     3
+                           776 POP_TOP
+               
+                38         778 LOAD_FAST                0 (self)
+                           780 LOAD_ATTR                7 (entry)
+                           790 LOAD_METHOD             25 (bind)
+                           812 LOAD_CONST              12 ('<FocusIn>')
+                           814 LOAD_FAST                0 (self)
+                           816 LOAD_ATTR               30 (_focus)
+                           826 LOAD_CONST               7 ('+')
+                           828 KW_NAMES                 8
+                           830 PRECALL                  3
+                           834 CALL                     3
+                           844 POP_TOP
+               
+                39         846 LOAD_FAST                0 (self)
+                           848 LOAD_METHOD             25 (bind)
+                           870 LOAD_CONST              13 ('<FocusOut>')
+                           872 LOAD_FAST                0 (self)
+                           874 LOAD_ATTR               31 (_focusout)
+                           884 LOAD_CONST               7 ('+')
+                           886 KW_NAMES                 8
+                           888 PRECALL                  3
+                           892 CALL                     3
+                           902 POP_TOP
+               
+                40         904 LOAD_FAST                0 (self)
+                           906 LOAD_ATTR                7 (entry)
+                           916 LOAD_METHOD             25 (bind)
+                           938 LOAD_CONST              13 ('<FocusOut>')
+                           940 LOAD_FAST                0 (self)
+                           942 LOAD_ATTR               31 (_focusout)
+                           952 LOAD_CONST               7 ('+')
+                           954 KW_NAMES                 8
+                           956 PRECALL                  3
+                           960 CALL                     3
+                           970 POP_TOP
+               
+                42         972 LOAD_FAST                0 (self)
+                           974 LOAD_METHOD             26 (_draw)
+                           996 LOAD_CONST               0 (None)
+                           998 PRECALL                  1
+                          1002 CALL                     1
+                          1012 POP_TOP
+                          1014 LOAD_CONST               0 (None)
+                          1016 RETURN_VALUE
                consts
                   None
                   0
                   ('width', 'height', 'highlightthickness')
                   ('StringVar', 'Entry')
                   ('bd', 'textvariable', 'highlightthickness')
                   'TkDefaultFont'
@@ -649,35 +654,35 @@
                   '+'
                   ('add',)
                   '<Button>'
                   '<Enter>'
                   '<Leave>'
                   '<FocusIn>'
                   '<FocusOut>'
-               names      ('super', '__init__', 'tkinter', 'StringVar', 'Entry', 'var', 'set', 'entry', '_other', 'default_palette', 'text', 'entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_text_back', '_entry_text_back', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', 'nametofont', 'entry_text_font', 'bind', '_draw', '_click', '_hover', '_hover_release', '_focus', '_focusout')
+               names      ('super', '__init__', 'tkinter', 'StringVar', 'Entry', 'var', 'set', 'entry', '_other', 'default_palette', 'text', 'entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_text_back', '_entry_text_back', 'entry_border_width', '_entry_border_width', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', 'nametofont', 'entry_text_font', 'bind', '_draw', '_click', '_hover', '_hover_release', '_focus', '_focusout')
                varnames   ('self', 'width', 'height', 'text', 'args', 'kwargs', 'StringVar', 'Entry')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '__init__'
                firstlineno 7
                lnotab
-                  0x04023a0210021e0134023202280228020e021801180118011801180228
-                  023a013a013a013a013a0144013a014402
+                  0x04023a0210021e0134023202280228020e021801180118011801180118
+                  0228023a013a013a013a013a0144013a014402
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a000000000000000000a00100000000000000000000000000
                   000000000000007c01a6010000ab010000000000000000010064005300
-                43           0 RESUME                   0
+                44           0 RESUME                   0
                
-                44           2 LOAD_FAST                0 (self)
+                45           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (var)
                             14 LOAD_METHOD              1 (set)
                             36 LOAD_FAST                1 (text)
                             38 PRECALL                  1
                             42 CALL                     1
                             52 POP_TOP
                             54 LOAD_CONST               0 (None)
@@ -686,87 +691,87 @@
                   None
                names      ('var', 'set')
                varnames   ('self', 'text')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'set'
-               firstlineno 43
+               firstlineno 44
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c006a000000000000000000a00100000000000000000000000000
                   00000000000000a6000000ab0000000000000000005300
-                46           0 RESUME                   0
+                47           0 RESUME                   0
                
-                47           2 LOAD_FAST                0 (self)
+                48           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (var)
                             14 LOAD_METHOD              1 (get)
                             36 PRECALL                  0
                             40 CALL                     0
                             50 RETURN_VALUE
                consts
                   None
                names      ('var', 'get')
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'get'
-               firstlineno 46
+               firstlineno 47
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 4
                flags     : 3
                code
                   0x97007401000000000000000000007c006401a6020000ab020000000000
                   000000721e7c00a00100000000000000000000000000000000000000007c
                   006a0200000000000000006402ac03a6020000ab02000000000000000001
                   006400530064005300
-                49           0 RESUME                   0
+                50           0 RESUME                   0
                
-                50           2 LOAD_GLOBAL              1 (NULL + hasattr)
+                51           2 LOAD_GLOBAL              1 (NULL + hasattr)
                             14 LOAD_FAST                0 (self)
                             16 LOAD_CONST               1 ('button_frame_back')
                             18 PRECALL                  2
                             22 CALL                     2
                             32 POP_JUMP_FORWARD_IF_FALSE    30 (to 94)
                
-                51          34 LOAD_FAST                0 (self)
+                52          34 LOAD_FAST                0 (self)
                             36 LOAD_METHOD              1 (configure)
                             58 LOAD_FAST                0 (self)
                             60 LOAD_ATTR                2 (button_frame_back)
                             70 LOAD_CONST               2 (0)
                             72 KW_NAMES                 3
                             74 PRECALL                  2
                             78 CALL                     2
                             88 POP_TOP
                             90 LOAD_CONST               0 (None)
                             92 RETURN_VALUE
                
-                50     >>   94 LOAD_CONST               0 (None)
+                51     >>   94 LOAD_CONST               0 (None)
                             96 RETURN_VALUE
                consts
                   None
                   'button_frame_back'
                   0
                   ('background', 'borderwidth')
                names      ('hasattr', 'configure', 'button_frame_back')
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_other'
-               firstlineno 49
+               firstlineno 50
                lnotab 0x020120013cff
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 9
                flags     : 3
                code
@@ -800,174 +805,174 @@
                   00000000000000000000000000000000007c006a0e0000000000000000a6
                   010000ab01000000000000000001007c00a00f0000000000000000000000
                   0000000000000000007c006a0e00000000000000007c006a0b0000000000
                   000000a6020000ab02000000000000000001007c006a0a00000000000000
                   00a01000000000000000000000000000000000000000007c006a06000000
                   00000000007c006a1100000000000000007c006a110000000000000000ac
                   09a6030000ab030000000000000000010064005300
-                53           0 RESUME                   0
+                54           0 RESUME                   0
                
-                54           2 LOAD_FAST                0 (self)
+                55           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-                56          44 LOAD_FAST                0 (self)
+                58          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_rectangle)
                
-                57          68 LOAD_CONST               2 (0)
+                59          68 LOAD_CONST               2 (0)
                             70 LOAD_CONST               2 (0)
                             72 LOAD_FAST                0 (self)
                             74 LOAD_METHOD              2 (winfo_width)
                             96 PRECALL                  0
                            100 CALL                     0
                            110 LOAD_CONST               3 (1)
                            112 BINARY_OP               10 (-)
                            116 LOAD_FAST                0 (self)
                            118 LOAD_METHOD              3 (winfo_height)
                            140 PRECALL                  0
                            144 CALL                     0
                            154 LOAD_CONST               3 (1)
                            156 BINARY_OP               10 (-)
                
-                58         160 LOAD_FAST                0 (self)
-                           162 LOAD_ATTR                4 (entry_border_width)
+                60         160 LOAD_FAST                0 (self)
+                           162 LOAD_ATTR                4 (_entry_border_width)
                
-                59         172 LOAD_FAST                0 (self)
+                61         172 LOAD_FAST                0 (self)
                            174 LOAD_ATTR                5 (_entry_border)
                            184 LOAD_FAST                0 (self)
                            186 LOAD_ATTR                6 (_entry_back)
                
-                56         196 KW_NAMES                 4
+                58         196 KW_NAMES                 4
                            198 PRECALL                  7
                            202 CALL                     7
                            212 LOAD_FAST                0 (self)
                            214 STORE_ATTR               7 (entry_frame)
                
-                62         224 LOAD_FAST                0 (self)
+                65         224 LOAD_FAST                0 (self)
                            226 LOAD_METHOD              8 (create_window)
                
-                63         248 LOAD_FAST                0 (self)
+                66         248 LOAD_FAST                0 (self)
                            250 LOAD_METHOD              2 (winfo_width)
                            272 PRECALL                  0
                            276 CALL                     0
                            286 LOAD_CONST               5 (2)
                            288 BINARY_OP               11 (/)
                            292 LOAD_FAST                0 (self)
                            294 LOAD_METHOD              3 (winfo_height)
                            316 PRECALL                  0
                            320 CALL                     0
                            330 LOAD_CONST               5 (2)
                            332 BINARY_OP               11 (/)
                
-                64         336 LOAD_FAST                0 (self)
+                67         336 LOAD_FAST                0 (self)
                            338 LOAD_METHOD              2 (winfo_width)
                            360 PRECALL                  0
                            364 CALL                     0
                            374 LOAD_FAST                0 (self)
-                           376 LOAD_ATTR                4 (entry_border_width)
+                           376 LOAD_ATTR                4 (_entry_border_width)
                            386 BINARY_OP               10 (-)
                            390 LOAD_CONST               6 (5)
                            392 BINARY_OP               10 (-)
                            396 LOAD_FAST                0 (self)
                            398 LOAD_ATTR                9 (entry_padding)
                            408 LOAD_CONST               2 (0)
                            410 BINARY_SUBSCR
                            420 BINARY_OP               10 (-)
                
-                65         424 LOAD_FAST                0 (self)
+                68         424 LOAD_FAST                0 (self)
                            426 LOAD_METHOD              3 (winfo_height)
                            448 PRECALL                  0
                            452 CALL                     0
                            462 LOAD_FAST                0 (self)
-                           464 LOAD_ATTR                4 (entry_border_width)
+                           464 LOAD_ATTR                4 (_entry_border_width)
                            474 BINARY_OP               10 (-)
                            478 LOAD_CONST               6 (5)
                            480 BINARY_OP               10 (-)
                            484 LOAD_FAST                0 (self)
                            486 LOAD_ATTR                9 (entry_padding)
                            496 LOAD_CONST               3 (1)
                            498 BINARY_SUBSCR
                            508 BINARY_OP               10 (-)
                
-                66         512 LOAD_FAST                0 (self)
+                69         512 LOAD_FAST                0 (self)
                            514 LOAD_ATTR               10 (entry)
                
-                62         524 KW_NAMES                 7
+                65         524 KW_NAMES                 7
                            526 PRECALL                  5
                            530 CALL                     5
                            540 LOAD_FAST                0 (self)
                            542 STORE_ATTR              11 (entry_text)
                
-                69         552 LOAD_FAST                0 (self)
+                73         552 LOAD_FAST                0 (self)
                            554 LOAD_METHOD              1 (create_rectangle)
                            576 LOAD_CONST               3 (1)
                            578 LOAD_FAST                0 (self)
                            580 LOAD_METHOD              3 (winfo_height)
                            602 PRECALL                  0
                            606 CALL                     0
                            616 LOAD_FAST                0 (self)
                            618 LOAD_ATTR               12 (_entry_bottom_width)
                            628 BINARY_OP               10 (-)
                            632 LOAD_CONST               3 (1)
                            634 BINARY_OP               10 (-)
                
-                70         638 LOAD_FAST                0 (self)
+                74         638 LOAD_FAST                0 (self)
                            640 LOAD_METHOD              2 (winfo_width)
                            662 PRECALL                  0
                            666 CALL                     0
                            676 LOAD_CONST               3 (1)
                            678 BINARY_OP               10 (-)
                            682 LOAD_FAST                0 (self)
                            684 LOAD_METHOD              3 (winfo_height)
                            706 PRECALL                  0
                            710 CALL                     0
                            720 LOAD_CONST               3 (1)
                            722 BINARY_OP               10 (-)
                
-                71         726 LOAD_FAST                0 (self)
+                75         726 LOAD_FAST                0 (self)
                            728 LOAD_ATTR               13 (_entry_bottom_line)
                            738 LOAD_FAST                0 (self)
                            740 LOAD_ATTR               13 (_entry_bottom_line)
                
-                72         750 LOAD_CONST               2 (0)
+                76         750 LOAD_CONST               2 (0)
                
-                69         752 KW_NAMES                 8
+                73         752 KW_NAMES                 8
                            754 PRECALL                  7
                            758 CALL                     7
                            768 LOAD_FAST                0 (self)
                            770 STORE_ATTR              14 (entry_bottom)
                
-                74         780 LOAD_FAST                0 (self)
+                78         780 LOAD_FAST                0 (self)
                            782 LOAD_ATTR               12 (_entry_bottom_width)
                            792 LOAD_CONST               2 (0)
                            794 COMPARE_OP               2 (==)
                            800 POP_JUMP_FORWARD_IF_FALSE    26 (to 854)
                
-                75         802 LOAD_FAST                0 (self)
+                79         802 LOAD_FAST                0 (self)
                            804 LOAD_METHOD              0 (delete)
                            826 LOAD_FAST                0 (self)
                            828 LOAD_ATTR               14 (entry_bottom)
                            838 PRECALL                  1
                            842 CALL                     1
                            852 POP_TOP
                
-                77     >>  854 LOAD_FAST                0 (self)
+                81     >>  854 LOAD_FAST                0 (self)
                            856 LOAD_METHOD             15 (tag_raise)
                            878 LOAD_FAST                0 (self)
                            880 LOAD_ATTR               14 (entry_bottom)
                            890 LOAD_FAST                0 (self)
                            892 LOAD_ATTR               11 (entry_text)
                            902 PRECALL                  2
                            906 CALL                     2
                            916 POP_TOP
                
-                79         918 LOAD_FAST                0 (self)
+                83         918 LOAD_FAST                0 (self)
                            920 LOAD_ATTR               10 (entry)
                            930 LOAD_METHOD             16 (configure)
                            952 LOAD_FAST                0 (self)
                            954 LOAD_ATTR                6 (_entry_back)
                            964 LOAD_FAST                0 (self)
                            966 LOAD_ATTR               17 (_entry_text_back)
                            976 LOAD_FAST                0 (self)
@@ -985,374 +990,392 @@
                   1
                   ('width', 'outline', 'fill')
                   2
                   5
                   ('width', 'height', 'window')
                   ('fill', 'outline', 'width')
                   ('background', 'foreground', 'insertbackground')
-               names      ('delete', 'create_rectangle', 'winfo_width', 'winfo_height', 'entry_border_width', '_entry_border', '_entry_back', 'entry_frame', 'create_window', 'entry_padding', 'entry', 'entry_text', '_entry_bottom_width', '_entry_bottom_line', 'entry_bottom', 'tag_raise', 'configure', '_entry_text_back')
+               names      ('delete', 'create_rectangle', 'winfo_width', 'winfo_height', '_entry_border_width', '_entry_border', '_entry_back', 'entry_frame', 'create_window', 'entry_padding', 'entry', 'entry_text', '_entry_bottom_width', '_entry_bottom_line', 'entry_bottom', 'tag_raise', 'configure', '_entry_text_back')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_draw'
-               firstlineno 53
+               firstlineno 54
                lnotab
-                  0x02012a0218015c010c0118fd1c0618015801580158010cfc1c07560158
+                  0x02012a0318015c010c0118fd1c0718015801580158010cfc1c08560158
                   01180102fd1c05160134024002
             None
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
-                  0000007c00a00a00000000000000000000000000000000000000006400a6
-                  010000ab010000000000000000010064005300
-                81           0 RESUME                   0
+                  0000007c006a0a00000000000000007c005f0b00000000000000007c00a0
+                  0c00000000000000000000000000000000000000006400a6010000ab0100
+                  00000000000000010064005300
+                85           0 RESUME                   0
                
-                82           2 LOAD_FAST                0 (self)
+                86           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (entry_focusin_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_entry_back)
                
-                83          26 LOAD_FAST                0 (self)
+                87          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (entry_focusin_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_entry_border)
                
-                84          50 LOAD_FAST                0 (self)
-                            52 LOAD_ATTR                4 (entry_focusin_text_back)
+                88          50 LOAD_FAST                0 (self)
+                            52 LOAD_ATTR                4 (entry_focusin_border_width)
                             62 LOAD_FAST                0 (self)
-                            64 STORE_ATTR               5 (_entry_text_back)
+                            64 STORE_ATTR               5 (_entry_border_width)
                
-                85          74 LOAD_FAST                0 (self)
-                            76 LOAD_ATTR                6 (entry_focusin_bottom_line)
+                89          74 LOAD_FAST                0 (self)
+                            76 LOAD_ATTR                6 (entry_focusin_text_back)
                             86 LOAD_FAST                0 (self)
-                            88 STORE_ATTR               7 (_entry_bottom_line)
+                            88 STORE_ATTR               7 (_entry_text_back)
                
-                86          98 LOAD_FAST                0 (self)
-                           100 LOAD_ATTR                8 (entry_focusin_bottom_width)
+                90          98 LOAD_FAST                0 (self)
+                           100 LOAD_ATTR                8 (entry_focusin_bottom_line)
                            110 LOAD_FAST                0 (self)
-                           112 STORE_ATTR               9 (_entry_bottom_width)
+                           112 STORE_ATTR               9 (_entry_bottom_line)
                
-                88         122 LOAD_FAST                0 (self)
-                           124 LOAD_METHOD             10 (_draw)
-                           146 LOAD_CONST               0 (None)
-                           148 PRECALL                  1
-                           152 CALL                     1
-                           162 POP_TOP
-                           164 LOAD_CONST               0 (None)
-                           166 RETURN_VALUE
+                91         122 LOAD_FAST                0 (self)
+                           124 LOAD_ATTR               10 (entry_focusin_bottom_width)
+                           134 LOAD_FAST                0 (self)
+                           136 STORE_ATTR              11 (_entry_bottom_width)
+               
+                93         146 LOAD_FAST                0 (self)
+                           148 LOAD_METHOD             12 (_draw)
+                           170 LOAD_CONST               0 (None)
+                           172 PRECALL                  1
+                           176 CALL                     1
+                           186 POP_TOP
+                           188 LOAD_CONST               0 (None)
+                           190 RETURN_VALUE
                consts
                   None
-               names      ('entry_focusin_back', '_entry_back', 'entry_focusin_border', '_entry_border', 'entry_focusin_text_back', '_entry_text_back', 'entry_focusin_bottom_line', '_entry_bottom_line', 'entry_focusin_bottom_width', '_entry_bottom_width', '_draw')
+               names      ('entry_focusin_back', '_entry_back', 'entry_focusin_border', '_entry_border', 'entry_focusin_border_width', '_entry_border_width', 'entry_focusin_text_back', '_entry_text_back', 'entry_focusin_bottom_line', '_entry_bottom_line', 'entry_focusin_bottom_width', '_entry_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_focus'
-               firstlineno 81
-               lnotab 0x020118011801180118011802
+               firstlineno 85
+               lnotab 0x0201180118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
-                  0000007c00a00a00000000000000000000000000000000000000006400a6
-                  010000ab010000000000000000010064005300
-                90           0 RESUME                   0
+                  0000007c006a0a00000000000000007c005f0b00000000000000007c00a0
+                  0c00000000000000000000000000000000000000006400a6010000ab0100
+                  00000000000000010064005300
+                95           0 RESUME                   0
                
-                91           2 LOAD_FAST                0 (self)
+                96           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (entry_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_entry_back)
                
-                92          26 LOAD_FAST                0 (self)
+                97          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (entry_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_entry_border)
                
-                93          50 LOAD_FAST                0 (self)
-                            52 LOAD_ATTR                4 (entry_text_back)
+                98          50 LOAD_FAST                0 (self)
+                            52 LOAD_ATTR                4 (entry_border_width)
                             62 LOAD_FAST                0 (self)
-                            64 STORE_ATTR               5 (_entry_text_back)
+                            64 STORE_ATTR               5 (_entry_border_width)
                
-                94          74 LOAD_FAST                0 (self)
-                            76 LOAD_ATTR                6 (entry_bottom_line)
+                99          74 LOAD_FAST                0 (self)
+                            76 LOAD_ATTR                6 (entry_text_back)
                             86 LOAD_FAST                0 (self)
-                            88 STORE_ATTR               7 (_entry_bottom_line)
+                            88 STORE_ATTR               7 (_entry_text_back)
                
-                95          98 LOAD_FAST                0 (self)
-                           100 LOAD_ATTR                8 (entry_bottom_width)
+               100          98 LOAD_FAST                0 (self)
+                           100 LOAD_ATTR                8 (entry_bottom_line)
                            110 LOAD_FAST                0 (self)
-                           112 STORE_ATTR               9 (_entry_bottom_width)
+                           112 STORE_ATTR               9 (_entry_bottom_line)
                
-                97         122 LOAD_FAST                0 (self)
-                           124 LOAD_METHOD             10 (_draw)
-                           146 LOAD_CONST               0 (None)
-                           148 PRECALL                  1
-                           152 CALL                     1
-                           162 POP_TOP
-                           164 LOAD_CONST               0 (None)
-                           166 RETURN_VALUE
+               101         122 LOAD_FAST                0 (self)
+                           124 LOAD_ATTR               10 (entry_bottom_width)
+                           134 LOAD_FAST                0 (self)
+                           136 STORE_ATTR              11 (_entry_bottom_width)
+               
+               103         146 LOAD_FAST                0 (self)
+                           148 LOAD_METHOD             12 (_draw)
+                           170 LOAD_CONST               0 (None)
+                           172 PRECALL                  1
+                           176 CALL                     1
+                           186 POP_TOP
+                           188 LOAD_CONST               0 (None)
+                           190 RETURN_VALUE
                consts
                   None
-               names      ('entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_text_back', '_entry_text_back', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', '_draw')
+               names      ('entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_border_width', '_entry_border_width', 'entry_text_back', '_entry_text_back', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_focusout'
-               firstlineno 90
-               lnotab 0x020118011801180118011802
+               firstlineno 95
+               lnotab 0x0201180118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-                99           0 RESUME                   0
+               105           0 RESUME                   0
                
-               100           2 LOAD_FAST                0 (self)
+               106           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_set)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('focus_set',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_click'
-               firstlineno 99
+               firstlineno 105
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code 0x970064017c005f00000000000000000064005300
-               102           0 RESUME                   0
+               108           0 RESUME                   0
                
-               103           2 LOAD_CONST               1 (True)
+               109           2 LOAD_CONST               1 (True)
                              4 LOAD_FAST                0 (self)
                              6 STORE_ATTR               0 (hover)
                             16 LOAD_CONST               0 (None)
                             18 RETURN_VALUE
                consts
                   None
                   True
                names      ('hover',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_hover'
-               firstlineno 102
+               firstlineno 108
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
-                  00ab000000000000000000735a64017c005f0100000000000000007c006a
+                  00ab000000000000000000736664017c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
-                  0000007c006a0a00000000000000007c005f0b00000000000000007c00a0
-                  0c00000000000000000000000000000000000000006400a6010000ab0100
-                  0000000000000001006400530064005300
-               105           0 RESUME                   0
+                  0000007c006a0a00000000000000007c005f0b00000000000000007c006a
+                  0c00000000000000007c005f0d00000000000000007c00a00e0000000000
+                  0000000000000000000000000000006400a6010000ab0100000000000000
+                  0001006400530064005300
+               111           0 RESUME                   0
                
-               106           2 LOAD_FAST                0 (self)
+               112           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_get)
                             26 PRECALL                  0
                             30 CALL                     0
-                            40 POP_JUMP_FORWARD_IF_TRUE    90 (to 222)
+                            40 POP_JUMP_FORWARD_IF_TRUE   102 (to 246)
                
-               107          42 LOAD_CONST               1 (False)
+               113          42 LOAD_CONST               1 (False)
                             44 LOAD_FAST                0 (self)
                             46 STORE_ATTR               1 (hover)
                
-               108          56 LOAD_FAST                0 (self)
+               114          56 LOAD_FAST                0 (self)
                             58 LOAD_ATTR                2 (entry_back)
                             68 LOAD_FAST                0 (self)
                             70 STORE_ATTR               3 (_entry_back)
                
-               109          80 LOAD_FAST                0 (self)
+               115          80 LOAD_FAST                0 (self)
                             82 LOAD_ATTR                4 (entry_border)
                             92 LOAD_FAST                0 (self)
                             94 STORE_ATTR               5 (_entry_border)
                
-               110         104 LOAD_FAST                0 (self)
-                           106 LOAD_ATTR                6 (entry_text_back)
+               116         104 LOAD_FAST                0 (self)
+                           106 LOAD_ATTR                6 (entry_border_width)
                            116 LOAD_FAST                0 (self)
-                           118 STORE_ATTR               7 (_entry_text_back)
+                           118 STORE_ATTR               7 (_entry_border_width)
                
-               111         128 LOAD_FAST                0 (self)
-                           130 LOAD_ATTR                8 (entry_bottom_line)
+               117         128 LOAD_FAST                0 (self)
+                           130 LOAD_ATTR                8 (entry_text_back)
                            140 LOAD_FAST                0 (self)
-                           142 STORE_ATTR               9 (_entry_bottom_line)
+                           142 STORE_ATTR               9 (_entry_text_back)
                
-               112         152 LOAD_FAST                0 (self)
-                           154 LOAD_ATTR               10 (entry_bottom_width)
+               118         152 LOAD_FAST                0 (self)
+                           154 LOAD_ATTR               10 (entry_bottom_line)
                            164 LOAD_FAST                0 (self)
-                           166 STORE_ATTR              11 (_entry_bottom_width)
+                           166 STORE_ATTR              11 (_entry_bottom_line)
                
-               114         176 LOAD_FAST                0 (self)
-                           178 LOAD_METHOD             12 (_draw)
-                           200 LOAD_CONST               0 (None)
-                           202 PRECALL                  1
-                           206 CALL                     1
-                           216 POP_TOP
-                           218 LOAD_CONST               0 (None)
-                           220 RETURN_VALUE
+               119         176 LOAD_FAST                0 (self)
+                           178 LOAD_ATTR               12 (entry_bottom_width)
+                           188 LOAD_FAST                0 (self)
+                           190 STORE_ATTR              13 (_entry_bottom_width)
+               
+               121         200 LOAD_FAST                0 (self)
+                           202 LOAD_METHOD             14 (_draw)
+                           224 LOAD_CONST               0 (None)
+                           226 PRECALL                  1
+                           230 CALL                     1
+                           240 POP_TOP
+                           242 LOAD_CONST               0 (None)
+                           244 RETURN_VALUE
                
-               106     >>  222 LOAD_CONST               0 (None)
-                           224 RETURN_VALUE
+               112     >>  246 LOAD_CONST               0 (None)
+                           248 RETURN_VALUE
                consts
                   None
                   False
-               names      ('focus_get', 'hover', 'entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_text_back', '_entry_text_back', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', '_draw')
+               names      ('focus_get', 'hover', 'entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_border_width', '_entry_border_width', 'entry_text_back', '_entry_text_back', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_hover_release'
-               firstlineno 105
-               lnotab 0x020128010e01180118011801180118022ef8
+               firstlineno 111
+               lnotab 0x020128010e011801180118011801180118022ef7
             'font'
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               116           0 RESUME                   0
+               123           0 RESUME                   0
                
-               117           2 LOAD_FAST                1 (font)
+               124           2 LOAD_FAST                1 (font)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               118           6 LOAD_FAST                0 (self)
+               125           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (entry_text_font)
                             18 RETURN_VALUE
                
-               120     >>   20 LOAD_FAST                1 (font)
+               127     >>   20 LOAD_FAST                1 (font)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (entry_text_font)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('entry_text_font',)
                varnames   ('self', 'font')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'font'
-               firstlineno 116
+               firstlineno 123
                lnotab 0x020104010e02
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               122           0 RESUME                   0
+               129           0 RESUME                   0
                
-               123           2 LOAD_FAST                0 (self)
+               130           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'default_palette'
-               firstlineno 122
+               firstlineno 129
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 17
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   0264036404640564066404640764086409640a6406640b640c640d9c0664
                   0e9c086901a6010000ab010000000000000000010064005300
-               125           0 RESUME                   0
+               132           0 RESUME                   0
                
-               126           2 LOAD_FAST                0 (self)
+               133           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               128          26 LOAD_CONST               1 ('entry')
+               135          26 LOAD_CONST               1 ('entry')
                
-               129          28 LOAD_CONST               2 ((3, 4))
+               136          28 LOAD_CONST               2 ((3, 4))
                
-               131          30 LOAD_CONST               3 ('#fdfdfd')
+               138          30 LOAD_CONST               3 ('#fdfdfd')
                
-               132          32 LOAD_CONST               4 ('#eaeaea')
+               139          32 LOAD_CONST               4 ('#eaeaea')
                
-               133          34 LOAD_CONST               5 ('#5f5f5f')
+               140          34 LOAD_CONST               5 ('#5f5f5f')
                
-               134          36 LOAD_CONST               6 (1)
+               141          36 LOAD_CONST               6 (1)
                
-               136          38 LOAD_CONST               4 ('#eaeaea')
+               143          38 LOAD_CONST               4 ('#eaeaea')
                
-               137          40 LOAD_CONST               7 (0)
+               144          40 LOAD_CONST               7 (0)
                
-               140          42 LOAD_CONST               8 ('#f9f9f9')
+               147          42 LOAD_CONST               8 ('#f9f9f9')
                
-               141          44 LOAD_CONST               9 ('#e2e2e2')
+               148          44 LOAD_CONST               9 ('#e2e2e2')
                
-               142          46 LOAD_CONST              10 ('#1a1a1a')
+               149          46 LOAD_CONST              10 ('#1a1a1a')
                
-               143          48 LOAD_CONST               6 (1)
+               150          48 LOAD_CONST               6 (1)
                
-               145          50 LOAD_CONST              11 ('#185fb4')
+               152          50 LOAD_CONST              11 ('#185fb4')
                
-               146          52 LOAD_CONST              12 (2)
+               153          52 LOAD_CONST              12 (2)
                
-               139          54 LOAD_CONST              13 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
+               146          54 LOAD_CONST              13 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
                             56 BUILD_CONST_KEY_MAP      6
                
-               128          58 LOAD_CONST              14 (('padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
+               135          58 LOAD_CONST              14 (('padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
                             60 BUILD_CONST_KEY_MAP      8
                
-               127          62 BUILD_MAP                1
+               134          62 BUILD_MAP                1
                
-               126          64 PRECALL                  1
+               133          64 PRECALL                  1
                             68 CALL                     1
                             78 POP_TOP
                             80 LOAD_CONST               0 (None)
                             82 RETURN_VALUE
                consts
                   None
                   'entry'
@@ -1371,69 +1394,69 @@
                   ('padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'palette_light'
-               firstlineno 125
+               firstlineno 132
                lnotab
                   0x0201180202010202020102010201020202010203020102010201020202
                   0102f904f504ff02ff
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 17
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   026403640464056406640764086409640464076406640a640b640c9c0664
                   0d9c086901a6010000ab010000000000000000010064005300
-               152           0 RESUME                   0
+               159           0 RESUME                   0
                
-               153           2 LOAD_FAST                0 (self)
+               160           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               155          26 LOAD_CONST               1 ('entry')
+               162          26 LOAD_CONST               1 ('entry')
                
-               156          28 LOAD_CONST               2 ((3, 4))
+               163          28 LOAD_CONST               2 ((3, 4))
                
-               158          30 LOAD_CONST               3 ('#353535')
+               165          30 LOAD_CONST               3 ('#353535')
                
-               159          32 LOAD_CONST               4 ('#454545')
+               166          32 LOAD_CONST               4 ('#454545')
                
-               160          34 LOAD_CONST               5 ('#cecece')
+               167          34 LOAD_CONST               5 ('#cecece')
                
-               161          36 LOAD_CONST               6 (1)
+               168          36 LOAD_CONST               6 (1)
                
-               163          38 LOAD_CONST               7 ('#ffffff')
+               170          38 LOAD_CONST               7 ('#ffffff')
                
-               164          40 LOAD_CONST               8 (0)
+               171          40 LOAD_CONST               8 (0)
                
-               167          42 LOAD_CONST               9 ('#2f2f2f')
+               174          42 LOAD_CONST               9 ('#2f2f2f')
                
-               168          44 LOAD_CONST               4 ('#454545')
+               175          44 LOAD_CONST               4 ('#454545')
                
-               169          46 LOAD_CONST               7 ('#ffffff')
+               176          46 LOAD_CONST               7 ('#ffffff')
                
-               170          48 LOAD_CONST               6 (1)
+               177          48 LOAD_CONST               6 (1)
                
-               172          50 LOAD_CONST              10 ('#4cc2ff')
+               179          50 LOAD_CONST              10 ('#4cc2ff')
                
-               173          52 LOAD_CONST              11 (2)
+               180          52 LOAD_CONST              11 (2)
                
-               166          54 LOAD_CONST              12 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
+               173          54 LOAD_CONST              12 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
                             56 BUILD_CONST_KEY_MAP      6
                
-               155          58 LOAD_CONST              13 (('padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
+               162          58 LOAD_CONST              13 (('padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
                             60 BUILD_CONST_KEY_MAP      8
                
-               154          62 BUILD_MAP                1
+               161          62 BUILD_MAP                1
                
-               153          64 PRECALL                  1
+               160          64 PRECALL                  1
                             68 CALL                     1
                             78 POP_TOP
                             80 LOAD_CONST               0 (None)
                             82 RETURN_VALUE
                consts
                   None
                   'entry'
@@ -1451,25 +1474,25 @@
                   ('padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'palette_dark'
-               firstlineno 152
+               firstlineno 159
                lnotab
                   0x0201180202010202020102010201020202010203020102010201020202
                   0102f904f504ff02ff
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 4
                flags     : 3
                code
-                  0x97007c019001815a64017c017600900172257c01640119000000000000
+                  0x97007c01900181a264017c017600900172257c01640119000000000000
                   0000006402190000000000000000007c005f0000000000000000007c0164
                   01190000000000000000006403190000000000000000007c005f01000000
                   00000000007c016401190000000000000000006404190000000000000000
                   007c005f0200000000000000007c01640119000000000000000000640519
                   0000000000000000007c005f0300000000000000007c0164011900000000
                   00000000006406190000000000000000007c005f0400000000000000007c
                   016401190000000000000000006407190000000000000000007c005f0500
@@ -1481,333 +1504,368 @@
                   0000007c005f0800000000000000007c0164011900000000000000000064
                   09190000000000000000006405190000000000000000007c005f09000000
                   00000000007c016401190000000000000000006409190000000000000000
                   006406190000000000000000007c005f0a00000000000000007c01640119
                   000000000000000000640919000000000000000000640719000000000000
                   0000007c005f0b00000000000000007c0164011900000000000000000064
                   09190000000000000000006408190000000000000000007c005f0c000000
-                  00000000007c017c005f0d000000000000000009007c00a00e0000000000
-                  0000000000000000000000000000006400a6010000ab0100000000000000
-                  000100640053002300741e00000000000000000000240072040100590064
-                  00530077007803590077017c006a0d00000000000000005300
-               179           0 RESUME                   0
+                  00000000007c017c005f0d00000000000000007c006a0100000000000000
+                  007c005f0e00000000000000007c006a0200000000000000007c005f0f00
+                  000000000000007c006a0300000000000000007c005f1000000000000000
+                  007c006a0400000000000000007c005f1100000000000000007c006a0500
+                  000000000000007c005f1200000000000000007c006a0600000000000000
+                  007c005f13000000000000000009007c00a0140000000000000000000000
+                  0000000000000000006400a6010000ab0100000000000000000100640053
+                  002300742a00000000000000000000240072040100590064005300770078
+                  03590077017c006a0d00000000000000005300
+               186           0 RESUME                   0
                
-               180           2 LOAD_FAST                1 (dict)
+               187           2 LOAD_FAST                1 (dict)
                              4 EXTENDED_ARG             1
-                             6 POP_JUMP_FORWARD_IF_NONE   346 (to 700)
+                             6 POP_JUMP_FORWARD_IF_NONE   418 (to 844)
                
-               181           8 LOAD_CONST               1 ('entry')
+               188           8 LOAD_CONST               1 ('entry')
                             10 LOAD_FAST                1 (dict)
                             12 CONTAINS_OP              0
                             14 EXTENDED_ARG             1
                             16 POP_JUMP_FORWARD_IF_FALSE   293 (to 604)
                
-               182          18 LOAD_FAST                1 (dict)
+               189          18 LOAD_FAST                1 (dict)
                             20 LOAD_CONST               1 ('entry')
                             22 BINARY_SUBSCR
                             32 LOAD_CONST               2 ('padding')
                             34 BINARY_SUBSCR
                             44 LOAD_FAST                0 (self)
                             46 STORE_ATTR               0 (entry_padding)
                
-               184          56 LOAD_FAST                1 (dict)
+               191          56 LOAD_FAST                1 (dict)
                             58 LOAD_CONST               1 ('entry')
                             60 BINARY_SUBSCR
                             70 LOAD_CONST               3 ('back')
                             72 BINARY_SUBSCR
                             82 LOAD_FAST                0 (self)
                             84 STORE_ATTR               1 (entry_back)
                
-               185          94 LOAD_FAST                1 (dict)
+               192          94 LOAD_FAST                1 (dict)
                             96 LOAD_CONST               1 ('entry')
                             98 BINARY_SUBSCR
                            108 LOAD_CONST               4 ('border')
                            110 BINARY_SUBSCR
                            120 LOAD_FAST                0 (self)
                            122 STORE_ATTR               2 (entry_border)
                
-               186         132 LOAD_FAST                1 (dict)
+               193         132 LOAD_FAST                1 (dict)
                            134 LOAD_CONST               1 ('entry')
                            136 BINARY_SUBSCR
                            146 LOAD_CONST               5 ('text_back')
                            148 BINARY_SUBSCR
                            158 LOAD_FAST                0 (self)
                            160 STORE_ATTR               3 (entry_text_back)
                
-               187         170 LOAD_FAST                1 (dict)
+               194         170 LOAD_FAST                1 (dict)
                            172 LOAD_CONST               1 ('entry')
                            174 BINARY_SUBSCR
                            184 LOAD_CONST               6 ('border_width')
                            186 BINARY_SUBSCR
                            196 LOAD_FAST                0 (self)
                            198 STORE_ATTR               4 (entry_border_width)
                
-               189         208 LOAD_FAST                1 (dict)
+               196         208 LOAD_FAST                1 (dict)
                            210 LOAD_CONST               1 ('entry')
                            212 BINARY_SUBSCR
                            222 LOAD_CONST               7 ('bottom_line')
                            224 BINARY_SUBSCR
                            234 LOAD_FAST                0 (self)
                            236 STORE_ATTR               5 (entry_bottom_line)
                
-               190         246 LOAD_FAST                1 (dict)
+               197         246 LOAD_FAST                1 (dict)
                            248 LOAD_CONST               1 ('entry')
                            250 BINARY_SUBSCR
                            260 LOAD_CONST               8 ('bottom_width')
                            262 BINARY_SUBSCR
                            272 LOAD_FAST                0 (self)
                            274 STORE_ATTR               6 (entry_bottom_width)
                
-               192         284 LOAD_CONST               9 ('focusin')
+               199         284 LOAD_CONST               9 ('focusin')
                            286 LOAD_FAST                1 (dict)
                            288 LOAD_CONST               1 ('entry')
                            290 BINARY_SUBSCR
                            300 CONTAINS_OP              0
                            302 POP_JUMP_FORWARD_IF_FALSE   150 (to 604)
                
-               193         304 LOAD_FAST                1 (dict)
+               200         304 LOAD_FAST                1 (dict)
                            306 LOAD_CONST               1 ('entry')
                            308 BINARY_SUBSCR
                            318 LOAD_CONST               9 ('focusin')
                            320 BINARY_SUBSCR
                            330 LOAD_CONST               3 ('back')
                            332 BINARY_SUBSCR
                            342 LOAD_FAST                0 (self)
                            344 STORE_ATTR               7 (entry_focusin_back)
                
-               194         354 LOAD_FAST                1 (dict)
+               201         354 LOAD_FAST                1 (dict)
                            356 LOAD_CONST               1 ('entry')
                            358 BINARY_SUBSCR
                            368 LOAD_CONST               9 ('focusin')
                            370 BINARY_SUBSCR
                            380 LOAD_CONST               4 ('border')
                            382 BINARY_SUBSCR
                            392 LOAD_FAST                0 (self)
                            394 STORE_ATTR               8 (entry_focusin_border)
                
-               195         404 LOAD_FAST                1 (dict)
+               202         404 LOAD_FAST                1 (dict)
                            406 LOAD_CONST               1 ('entry')
                            408 BINARY_SUBSCR
                            418 LOAD_CONST               9 ('focusin')
                            420 BINARY_SUBSCR
                            430 LOAD_CONST               5 ('text_back')
                            432 BINARY_SUBSCR
                            442 LOAD_FAST                0 (self)
                            444 STORE_ATTR               9 (entry_focusin_text_back)
                
-               196         454 LOAD_FAST                1 (dict)
+               203         454 LOAD_FAST                1 (dict)
                            456 LOAD_CONST               1 ('entry')
                            458 BINARY_SUBSCR
                            468 LOAD_CONST               9 ('focusin')
                            470 BINARY_SUBSCR
                            480 LOAD_CONST               6 ('border_width')
                            482 BINARY_SUBSCR
                            492 LOAD_FAST                0 (self)
                            494 STORE_ATTR              10 (entry_focusin_border_width)
                
-               198         504 LOAD_FAST                1 (dict)
+               205         504 LOAD_FAST                1 (dict)
                            506 LOAD_CONST               1 ('entry')
                            508 BINARY_SUBSCR
                            518 LOAD_CONST               9 ('focusin')
                            520 BINARY_SUBSCR
                            530 LOAD_CONST               7 ('bottom_line')
                            532 BINARY_SUBSCR
                            542 LOAD_FAST                0 (self)
                            544 STORE_ATTR              11 (entry_focusin_bottom_line)
                
-               199         554 LOAD_FAST                1 (dict)
+               206         554 LOAD_FAST                1 (dict)
                            556 LOAD_CONST               1 ('entry')
                            558 BINARY_SUBSCR
                            568 LOAD_CONST               9 ('focusin')
                            570 BINARY_SUBSCR
                            580 LOAD_CONST               8 ('bottom_width')
                            582 BINARY_SUBSCR
                            592 LOAD_FAST                0 (self)
                            594 STORE_ATTR              12 (entry_focusin_bottom_width)
                
-               201     >>  604 LOAD_FAST                1 (dict)
+               208     >>  604 LOAD_FAST                1 (dict)
                            606 LOAD_FAST                0 (self)
                            608 STORE_ATTR              13 (_palette)
                
-               203         618 NOP
+               210         618 LOAD_FAST                0 (self)
+                           620 LOAD_ATTR                1 (entry_back)
+                           630 LOAD_FAST                0 (self)
+                           632 STORE_ATTR              14 (_entry_back)
                
-               204         620 LOAD_FAST                0 (self)
-                           622 LOAD_METHOD             14 (_draw)
-                           644 LOAD_CONST               0 (None)
-                           646 PRECALL                  1
-                           650 CALL                     1
-                           660 POP_TOP
-                           662 LOAD_CONST               0 (None)
-                           664 RETURN_VALUE
-                       >>  666 PUSH_EXC_INFO
-               
-               205         668 LOAD_GLOBAL             30 (AttributeError)
-                           680 CHECK_EXC_MATCH
-                           682 POP_JUMP_FORWARD_IF_FALSE     4 (to 692)
-                           684 POP_TOP
-               
-               206         686 POP_EXCEPT
-                           688 LOAD_CONST               0 (None)
-                           690 RETURN_VALUE
-               
-               205     >>  692 RERAISE                  0
-                       >>  694 COPY                     3
-                           696 POP_EXCEPT
-                           698 RERAISE                  1
-               
-               208     >>  700 LOAD_FAST                0 (self)
-                           702 LOAD_ATTR               13 (_palette)
-                           712 RETURN_VALUE
+               211         642 LOAD_FAST                0 (self)
+                           644 LOAD_ATTR                2 (entry_border)
+                           654 LOAD_FAST                0 (self)
+                           656 STORE_ATTR              15 (_entry_border)
+               
+               212         666 LOAD_FAST                0 (self)
+                           668 LOAD_ATTR                3 (entry_text_back)
+                           678 LOAD_FAST                0 (self)
+                           680 STORE_ATTR              16 (_entry_text_back)
+               
+               213         690 LOAD_FAST                0 (self)
+                           692 LOAD_ATTR                4 (entry_border_width)
+                           702 LOAD_FAST                0 (self)
+                           704 STORE_ATTR              17 (_entry_border_width)
+               
+               214         714 LOAD_FAST                0 (self)
+                           716 LOAD_ATTR                5 (entry_bottom_line)
+                           726 LOAD_FAST                0 (self)
+                           728 STORE_ATTR              18 (_entry_bottom_line)
+               
+               215         738 LOAD_FAST                0 (self)
+                           740 LOAD_ATTR                6 (entry_bottom_width)
+                           750 LOAD_FAST                0 (self)
+                           752 STORE_ATTR              19 (_entry_bottom_width)
+               
+               217         762 NOP
+               
+               218         764 LOAD_FAST                0 (self)
+                           766 LOAD_METHOD             20 (_draw)
+                           788 LOAD_CONST               0 (None)
+                           790 PRECALL                  1
+                           794 CALL                     1
+                           804 POP_TOP
+                           806 LOAD_CONST               0 (None)
+                           808 RETURN_VALUE
+                       >>  810 PUSH_EXC_INFO
+               
+               219         812 LOAD_GLOBAL             42 (AttributeError)
+                           824 CHECK_EXC_MATCH
+                           826 POP_JUMP_FORWARD_IF_FALSE     4 (to 836)
+                           828 POP_TOP
+               
+               220         830 POP_EXCEPT
+                           832 LOAD_CONST               0 (None)
+                           834 RETURN_VALUE
+               
+               219     >>  836 RERAISE                  0
+                       >>  838 COPY                     3
+                           840 POP_EXCEPT
+                           842 RERAISE                  1
+               
+               222     >>  844 LOAD_FAST                0 (self)
+                           846 LOAD_ATTR               13 (_palette)
+                           856 RETURN_VALUE
                ExceptionTable:
-                 620 to 660 -> 666 [0]
-                 666 to 684 -> 694 [1] lasti
-                 692 to 692 -> 694 [1] lasti
+                 764 to 804 -> 810 [0]
+                 810 to 828 -> 838 [1] lasti
+                 836 to 836 -> 838 [1] lasti
                consts
                   None
                   'entry'
                   'padding'
                   'back'
                   'border'
                   'text_back'
                   'border_width'
                   'bottom_line'
                   'bottom_width'
                   'focusin'
-               names      ('entry_padding', 'entry_back', 'entry_border', 'entry_text_back', 'entry_border_width', 'entry_bottom_line', 'entry_bottom_width', 'entry_focusin_back', 'entry_focusin_border', 'entry_focusin_text_back', 'entry_focusin_border_width', 'entry_focusin_bottom_line', 'entry_focusin_bottom_width', '_palette', '_draw', 'AttributeError')
+               names      ('entry_padding', 'entry_back', 'entry_border', 'entry_text_back', 'entry_border_width', 'entry_bottom_line', 'entry_bottom_width', 'entry_focusin_back', 'entry_focusin_border', 'entry_focusin_text_back', 'entry_focusin_border_width', 'entry_focusin_bottom_line', 'entry_focusin_bottom_width', '_palette', '_entry_back', '_entry_border', '_entry_text_back', '_entry_border_width', '_entry_bottom_line', '_entry_bottom_width', '_draw', 'AttributeError')
                varnames   ('self', 'dict')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'palette'
-               firstlineno 179
+               firstlineno 186
                lnotab
                   0x020106010a012602260126012601260226012602140132013201320132
-                  02320132020e0202013001120106ff0803
+                  02320132020e0218011801180118011801180202013001120106ff0803
             (None,)
          names      ('__name__', '__module__', '__qualname__', 'str', '__init__', 'set', 'get', '_other', '_draw', '_focus', '_focusout', '_click', '_hover', '_hover_release', 'Font', 'font', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
          name       'AdwDrawBasicEntry'
          firstlineno 6
          lnotab
-            0x0c011a240c0306030604061c0809080908030803080b0e060603061b06
+            0x0c011a250c0306030604061f080a080a08030803080c0e060603061b06
             1b
       'AdwDrawBasicEntry'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         211           0 RESUME                   0
+         225           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawEntry')
                        8 STORE_NAME               2 (__qualname__)
          
-         212          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 212>)
+         226          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 226>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawEntry'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               212           0 RESUME                   0
+               226           0 RESUME                   0
                
-               213           2 LOAD_FAST                0 (self)
+               227           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'default_palette'
-               firstlineno 212
+               firstlineno 226
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
          name       'AdwDrawEntry'
-         firstlineno 211
+         firstlineno 225
          lnotab 0x0a01
       'AdwDrawEntry'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         216           0 RESUME                   0
+         230           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawDarkEntry')
                        8 STORE_NAME               2 (__qualname__)
          
-         217          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 217>)
+         231          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 231>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawDarkEntry'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               217           0 RESUME                   0
+               231           0 RESUME                   0
                
-               218           2 LOAD_FAST                0 (self)
+               232           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'default_palette'
-               firstlineno 217
+               firstlineno 231
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
          name       'AdwDrawDarkEntry'
-         firstlineno 216
+         firstlineno 230
          lnotab 0x0a01
       'AdwDrawDarkEntry'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 3
          flags     : 0
@@ -1815,88 +1873,88 @@
             0x8700970065005a0164005a0288006601640184085a03640284005a0464
             11640484015a05640584005a066411640684015a076411640784015a0864
             11640884015a096411640984015a0a6411640a84015a0b6411640b650c66
             02640c84055a0d640d84005a0e640e84005a0f640f84005a106411880066
             01641084095a11880078015a125300
                        0 MAKE_CELL                0 (__class__)
          
-         222           2 RESUME                   0
+         236           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawBasicRoundEntry')
                       10 STORE_NAME               2 (__qualname__)
          
-         223          12 LOAD_CLOSURE             0 (__class__)
+         237          12 LOAD_CLOSURE             0 (__class__)
                       14 BUILD_TUPLE              1
-                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\entry.py", line 223>)
+                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\entry.py", line 237>)
                       18 MAKE_FUNCTION            8 (closure)
                       20 STORE_NAME               3 (__init__)
          
-         226          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\entry.py", line 226>)
+         240          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\entry.py", line 240>)
                       24 MAKE_FUNCTION            0
                       26 STORE_NAME               4 (_other)
          
-         230          28 LOAD_CONST              17 ((None,))
-                      30 LOAD_CONST               4 (<code object border_radius, file "D:\tkadw\tkadw\canvas\entry.py", line 230>)
+         244          28 LOAD_CONST              17 ((None,))
+                      30 LOAD_CONST               4 (<code object border_radius, file "D:\tkadw\tkadw\canvas\entry.py", line 244>)
                       32 MAKE_FUNCTION            1 (defaults)
                       34 STORE_NAME               5 (border_radius)
          
-         236          36 LOAD_CONST               5 (<code object _draw, file "D:\tkadw\tkadw\canvas\entry.py", line 236>)
+         250          36 LOAD_CONST               5 (<code object _draw, file "D:\tkadw\tkadw\canvas\entry.py", line 250>)
                       38 MAKE_FUNCTION            0
                       40 STORE_NAME               6 (_draw)
          
-         266          42 LOAD_CONST              17 ((None,))
-                      44 LOAD_CONST               6 (<code object _focus, file "D:\tkadw\tkadw\canvas\entry.py", line 266>)
+         283          42 LOAD_CONST              17 ((None,))
+                      44 LOAD_CONST               6 (<code object _focus, file "D:\tkadw\tkadw\canvas\entry.py", line 283>)
                       46 MAKE_FUNCTION            1 (defaults)
                       48 STORE_NAME               7 (_focus)
          
-         275          50 LOAD_CONST              17 ((None,))
-                      52 LOAD_CONST               7 (<code object _focusout, file "D:\tkadw\tkadw\canvas\entry.py", line 275>)
+         292          50 LOAD_CONST              17 ((None,))
+                      52 LOAD_CONST               7 (<code object _focusout, file "D:\tkadw\tkadw\canvas\entry.py", line 292>)
                       54 MAKE_FUNCTION            1 (defaults)
                       56 STORE_NAME               8 (_focusout)
          
-         284          58 LOAD_CONST              17 ((None,))
-                      60 LOAD_CONST               8 (<code object _click, file "D:\tkadw\tkadw\canvas\entry.py", line 284>)
+         301          58 LOAD_CONST              17 ((None,))
+                      60 LOAD_CONST               8 (<code object _click, file "D:\tkadw\tkadw\canvas\entry.py", line 301>)
                       62 MAKE_FUNCTION            1 (defaults)
                       64 STORE_NAME               9 (_click)
          
-         287          66 LOAD_CONST              17 ((None,))
-                      68 LOAD_CONST               9 (<code object _hover, file "D:\tkadw\tkadw\canvas\entry.py", line 287>)
+         304          66 LOAD_CONST              17 ((None,))
+                      68 LOAD_CONST               9 (<code object _hover, file "D:\tkadw\tkadw\canvas\entry.py", line 304>)
                       70 MAKE_FUNCTION            1 (defaults)
                       72 STORE_NAME              10 (_hover)
          
-         290          74 LOAD_CONST              17 ((None,))
-                      76 LOAD_CONST              10 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\entry.py", line 290>)
+         307          74 LOAD_CONST              17 ((None,))
+                      76 LOAD_CONST              10 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\entry.py", line 307>)
                       78 MAKE_FUNCTION            1 (defaults)
                       80 STORE_NAME              11 (_hover_release)
          
-         301          82 LOAD_CONST              17 ((None,))
+         318          82 LOAD_CONST              17 ((None,))
                       84 LOAD_CONST              11 ('font')
                       86 LOAD_NAME               12 (Font)
                       88 BUILD_TUPLE              2
-                      90 LOAD_CONST              12 (<code object font, file "D:\tkadw\tkadw\canvas\entry.py", line 301>)
+                      90 LOAD_CONST              12 (<code object font, file "D:\tkadw\tkadw\canvas\entry.py", line 318>)
                       92 MAKE_FUNCTION            5 (defaults, annotations)
                       94 STORE_NAME              13 (font)
          
-         307          96 LOAD_CONST              13 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 307>)
+         324          96 LOAD_CONST              13 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 324>)
                       98 MAKE_FUNCTION            0
                      100 STORE_NAME              14 (default_palette)
          
-         310         102 LOAD_CONST              14 (<code object palette_light, file "D:\tkadw\tkadw\canvas\entry.py", line 310>)
+         327         102 LOAD_CONST              14 (<code object palette_light, file "D:\tkadw\tkadw\canvas\entry.py", line 327>)
                      104 MAKE_FUNCTION            0
                      106 STORE_NAME              15 (palette_light)
          
-         338         108 LOAD_CONST              15 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\entry.py", line 338>)
+         355         108 LOAD_CONST              15 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\entry.py", line 355>)
                      110 MAKE_FUNCTION            0
                      112 STORE_NAME              16 (palette_dark)
          
-         366         114 LOAD_CONST              17 ((None,))
+         383         114 LOAD_CONST              17 ((None,))
                      116 LOAD_CLOSURE             0 (__class__)
                      118 BUILD_TUPLE              1
-                     120 LOAD_CONST              16 (<code object palette, file "D:\tkadw\tkadw\canvas\entry.py", line 366>)
+                     120 LOAD_CONST              16 (<code object palette, file "D:\tkadw\tkadw\canvas\entry.py", line 383>)
                      122 MAKE_FUNCTION            9 (defaults, closure)
                      124 STORE_NAME              17 (palette)
                      126 LOAD_CLOSURE             0 (__class__)
                      128 COPY                     1
                      130 STORE_NAME              18 (__classcell__)
                      132 RETURN_VALUE
          consts
@@ -1907,17 +1965,17 @@
                stacksize : 5
                flags     : 15
                code
                   0x950197000200740100000000000000000000a6000000ab000000000000
                   0000006a0100000000000000007c0169007c02a4018e01010064005300
                              0 COPY_FREE_VARS           1
                
-               223           2 RESUME                   0
+               237           2 RESUME                   0
                
-               224           4 PUSH_NULL
+               238           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                1 (args)
                             44 BUILD_MAP                0
                             46 LOAD_FAST                2 (kwargs)
@@ -1930,94 +1988,94 @@
                   None
                names      ('super', '__init__')
                varnames   ('self', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '__init__'
-               firstlineno 223
+               firstlineno 237
                lnotab 0x0401
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 4
                flags     : 3
                code
                   0x97007401000000000000000000007c006401a6020000ab020000000000
                   000000721e7c00a00100000000000000000000000000000000000000007c
                   006a0200000000000000006402ac03a6020000ab02000000000000000001
                   006400530064005300
-               226           0 RESUME                   0
+               240           0 RESUME                   0
                
-               227           2 LOAD_GLOBAL              1 (NULL + hasattr)
+               241           2 LOAD_GLOBAL              1 (NULL + hasattr)
                             14 LOAD_FAST                0 (self)
                             16 LOAD_CONST               1 ('button_frame_back')
                             18 PRECALL                  2
                             22 CALL                     2
                             32 POP_JUMP_FORWARD_IF_FALSE    30 (to 94)
                
-               228          34 LOAD_FAST                0 (self)
+               242          34 LOAD_FAST                0 (self)
                             36 LOAD_METHOD              1 (configure)
                             58 LOAD_FAST                0 (self)
                             60 LOAD_ATTR                2 (button_frame_back)
                             70 LOAD_CONST               2 (0)
                             72 KW_NAMES                 3
                             74 PRECALL                  2
                             78 CALL                     2
                             88 POP_TOP
                             90 LOAD_CONST               0 (None)
                             92 RETURN_VALUE
                
-               227     >>   94 LOAD_CONST               0 (None)
+               241     >>   94 LOAD_CONST               0 (None)
                             96 RETURN_VALUE
                consts
                   None
                   'button_frame_back'
                   0
                   ('background', 'borderwidth')
                names      ('hasattr', 'configure', 'button_frame_back')
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_other'
-               firstlineno 226
+               firstlineno 240
                lnotab 0x020120013cff
             None
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               230           0 RESUME                   0
+               244           0 RESUME                   0
                
-               231           2 LOAD_FAST                1 (radius)
+               245           2 LOAD_FAST                1 (radius)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               232           6 LOAD_FAST                0 (self)
+               246           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (button_radius)
                             18 RETURN_VALUE
                
-               234     >>   20 LOAD_FAST                1 (radius)
+               248     >>   20 LOAD_FAST                1 (radius)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (button_radius)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('button_radius',)
                varnames   ('self', 'radius')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'border_radius'
-               firstlineno 230
+               firstlineno 244
                lnotab 0x020104010e02
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 10
                flags     : 3
                code
@@ -2053,27 +2111,27 @@
                   000000000000000000000000007c006a100000000000000000a6010000ab
                   01000000000000000001007c00a011000000000000000000000000000000
                   00000000007c006a1000000000000000007c006a0c0000000000000000a6
                   020000ab02000000000000000001007c006a0b0000000000000000a01200
                   000000000000000000000000000000000000007c006a0700000000000000
                   007c006a1300000000000000007c006a130000000000000000ac0ba60300
                   00ab030000000000000000010064005300
-               236           0 RESUME                   0
+               250           0 RESUME                   0
                
-               237           2 LOAD_FAST                0 (self)
+               251           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               239          44 LOAD_FAST                0 (self)
+               254          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_round_rect2)
                
-               240          68 LOAD_CONST               2 (2)
+               255          68 LOAD_CONST               2 (2)
                             70 LOAD_CONST               2 (2)
                             72 LOAD_FAST                0 (self)
                             74 LOAD_METHOD              2 (winfo_width)
                             96 PRECALL                  0
                            100 CALL                     0
                            110 LOAD_CONST               3 (3)
                            112 BINARY_OP               10 (-)
@@ -2082,159 +2140,159 @@
                            140 PRECALL                  0
                            144 CALL                     0
                            154 LOAD_CONST               3 (3)
                            156 BINARY_OP               10 (-)
                            160 LOAD_FAST                0 (self)
                            162 LOAD_ATTR                4 (entry_radius)
                
-               241         172 LOAD_FAST                0 (self)
-                           174 LOAD_ATTR                5 (entry_border_width)
+               256         172 LOAD_FAST                0 (self)
+                           174 LOAD_ATTR                5 (_entry_border_width)
                
-               242         184 LOAD_FAST                0 (self)
+               257         184 LOAD_FAST                0 (self)
                            186 LOAD_ATTR                6 (_entry_border)
                            196 LOAD_FAST                0 (self)
                            198 LOAD_ATTR                7 (_entry_back)
                
-               239         208 KW_NAMES                 4
+               254         208 KW_NAMES                 4
                            210 PRECALL                  8
                            214 CALL                     8
                            224 LOAD_FAST                0 (self)
                            226 STORE_ATTR               8 (entry_frame)
                
-               245         236 LOAD_FAST                0 (self)
+               261         236 LOAD_FAST                0 (self)
                            238 LOAD_METHOD              9 (create_window)
                
-               246         260 LOAD_FAST                0 (self)
+               262         260 LOAD_FAST                0 (self)
                            262 LOAD_METHOD              2 (winfo_width)
                            284 PRECALL                  0
                            288 CALL                     0
                            298 LOAD_CONST               2 (2)
                            300 BINARY_OP               11 (/)
                            304 LOAD_FAST                0 (self)
                            306 LOAD_METHOD              3 (winfo_height)
                            328 PRECALL                  0
                            332 CALL                     0
                            342 LOAD_CONST               2 (2)
                            344 BINARY_OP               11 (/)
                
-               247         348 LOAD_FAST                0 (self)
+               263         348 LOAD_FAST                0 (self)
                            350 LOAD_METHOD              2 (winfo_width)
                            372 PRECALL                  0
                            376 CALL                     0
                            386 LOAD_FAST                0 (self)
-                           388 LOAD_ATTR                5 (entry_border_width)
+                           388 LOAD_ATTR                5 (_entry_border_width)
                            398 BINARY_OP               10 (-)
                            402 LOAD_CONST               5 (5)
                            404 BINARY_OP               10 (-)
                            408 LOAD_FAST                0 (self)
                            410 LOAD_ATTR               10 (entry_padding)
                            420 LOAD_CONST               6 (0)
                            422 BINARY_SUBSCR
                            432 BINARY_OP               10 (-)
                
-               248         436 LOAD_FAST                0 (self)
+               264         436 LOAD_FAST                0 (self)
                            438 LOAD_METHOD              3 (winfo_height)
                            460 PRECALL                  0
                            464 CALL                     0
                            474 LOAD_FAST                0 (self)
-                           476 LOAD_ATTR                5 (entry_border_width)
+                           476 LOAD_ATTR                5 (_entry_border_width)
                            486 BINARY_OP               10 (-)
                            490 LOAD_CONST               5 (5)
                            492 BINARY_OP               10 (-)
                            496 LOAD_FAST                0 (self)
                            498 LOAD_ATTR               10 (entry_padding)
                            508 LOAD_CONST               7 (1)
                            510 BINARY_SUBSCR
                            520 BINARY_OP               10 (-)
                
-               249         524 LOAD_FAST                0 (self)
+               265         524 LOAD_FAST                0 (self)
                            526 LOAD_ATTR               11 (entry)
                
-               245         536 KW_NAMES                 8
+               261         536 KW_NAMES                 8
                            538 PRECALL                  5
                            542 CALL                     5
                            552 LOAD_FAST                0 (self)
                            554 STORE_ATTR              12 (entry_text)
                
-               252         564 LOAD_FAST                0 (self)
+               269         564 LOAD_FAST                0 (self)
                            566 LOAD_METHOD             13 (create_rectangle)
                            588 LOAD_CONST               3 (3)
                            590 LOAD_FAST                0 (self)
                            592 LOAD_ATTR                4 (entry_radius)
                            602 LOAD_CONST               2 (2)
                            604 BINARY_OP               11 (/)
                            608 BINARY_OP                0 (+)
                
-               253         612 LOAD_FAST                0 (self)
+               270         612 LOAD_FAST                0 (self)
                            614 LOAD_METHOD              3 (winfo_height)
                            636 PRECALL                  0
                            640 CALL                     0
                            650 LOAD_FAST                0 (self)
                            652 LOAD_ATTR               14 (_entry_bottom_width)
                            662 BINARY_OP               10 (-)
                            666 LOAD_CONST               3 (3)
                            668 BINARY_OP               10 (-)
                
-               254         672 LOAD_FAST                0 (self)
+               271         672 LOAD_FAST                0 (self)
                            674 LOAD_METHOD              2 (winfo_width)
                            696 PRECALL                  0
                            700 CALL                     0
                            710 LOAD_CONST               3 (3)
                            712 BINARY_OP               10 (-)
                            716 LOAD_FAST                0 (self)
                            718 LOAD_ATTR                4 (entry_radius)
                            728 LOAD_CONST               2 (2)
                            730 BINARY_OP               11 (/)
                            734 BINARY_OP               10 (-)
                
-               255         738 LOAD_FAST                0 (self)
+               272         738 LOAD_FAST                0 (self)
                            740 LOAD_METHOD              3 (winfo_height)
                            762 PRECALL                  0
                            766 CALL                     0
                            776 LOAD_CONST               9 (3.5)
                            778 BINARY_OP               10 (-)
                
-               256         782 LOAD_FAST                0 (self)
+               273         782 LOAD_FAST                0 (self)
                            784 LOAD_ATTR               15 (_entry_bottom_line)
                            794 LOAD_FAST                0 (self)
                            796 LOAD_ATTR               15 (_entry_bottom_line)
                
-               257         806 LOAD_CONST               6 (0)
+               274         806 LOAD_CONST               6 (0)
                
-               252         808 KW_NAMES                10
+               269         808 KW_NAMES                10
                            810 PRECALL                  7
                            814 CALL                     7
                            824 LOAD_FAST                0 (self)
                            826 STORE_ATTR              16 (entry_bottom)
                
-               259         836 LOAD_FAST                0 (self)
+               276         836 LOAD_FAST                0 (self)
                            838 LOAD_ATTR               14 (_entry_bottom_width)
                            848 LOAD_CONST               6 (0)
                            850 COMPARE_OP               2 (==)
                            856 POP_JUMP_FORWARD_IF_FALSE    26 (to 910)
                
-               260         858 LOAD_FAST                0 (self)
+               277         858 LOAD_FAST                0 (self)
                            860 LOAD_METHOD              0 (delete)
                            882 LOAD_FAST                0 (self)
                            884 LOAD_ATTR               16 (entry_bottom)
                            894 PRECALL                  1
                            898 CALL                     1
                            908 POP_TOP
                
-               262     >>  910 LOAD_FAST                0 (self)
+               279     >>  910 LOAD_FAST                0 (self)
                            912 LOAD_METHOD             17 (tag_raise)
                            934 LOAD_FAST                0 (self)
                            936 LOAD_ATTR               16 (entry_bottom)
                            946 LOAD_FAST                0 (self)
                            948 LOAD_ATTR               12 (entry_text)
                            958 PRECALL                  2
                            962 CALL                     2
                            972 POP_TOP
                
-               264         974 LOAD_FAST                0 (self)
+               281         974 LOAD_FAST                0 (self)
                            976 LOAD_ATTR               11 (entry)
                            986 LOAD_METHOD             18 (configure)
                           1008 LOAD_FAST                0 (self)
                           1010 LOAD_ATTR                7 (_entry_back)
                           1020 LOAD_FAST                0 (self)
                           1022 LOAD_ATTR               19 (_entry_text_back)
                           1032 LOAD_FAST                0 (self)
@@ -2254,64 +2312,64 @@
                   5
                   0
                   1
                   ('width', 'height', 'window')
                   3.5
                   ('fill', 'outline', 'width')
                   ('background', 'foreground', 'insertbackground')
-               names      ('delete', 'create_round_rect2', 'winfo_width', 'winfo_height', 'entry_radius', 'entry_border_width', '_entry_border', '_entry_back', 'entry_frame', 'create_window', 'entry_padding', 'entry', 'entry_text', 'create_rectangle', '_entry_bottom_width', '_entry_bottom_line', 'entry_bottom', 'tag_raise', 'configure', '_entry_text_back')
+               names      ('delete', 'create_round_rect2', 'winfo_width', 'winfo_height', 'entry_radius', '_entry_border_width', '_entry_border', '_entry_back', 'entry_frame', 'create_window', 'entry_padding', 'entry', 'entry_text', 'create_rectangle', '_entry_bottom_width', '_entry_bottom_line', 'entry_bottom', 'tag_raise', 'configure', '_entry_text_back')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_draw'
-               firstlineno 236
+               firstlineno 250
                lnotab
-                  0x02012a02180168010c0118fd1c0618015801580158010cfc1c0730013c
+                  0x02012a03180168010c0118fd1c0718015801580158010cfc1c0830013c
                   0142012c01180102fb1c07160134024002
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c00a00a00000000000000000000000000000000000000006400a6
                   010000ab010000000000000000010064005300
-               266           0 RESUME                   0
+               283           0 RESUME                   0
                
-               267           2 LOAD_FAST                0 (self)
+               284           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (entry_focusin_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_entry_back)
                
-               268          26 LOAD_FAST                0 (self)
+               285          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (entry_focusin_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_entry_border)
                
-               269          50 LOAD_FAST                0 (self)
+               286          50 LOAD_FAST                0 (self)
                             52 LOAD_ATTR                4 (entry_focusin_text_back)
                             62 LOAD_FAST                0 (self)
                             64 STORE_ATTR               5 (_entry_text_back)
                
-               270          74 LOAD_FAST                0 (self)
+               287          74 LOAD_FAST                0 (self)
                             76 LOAD_ATTR                6 (entry_focusin_bottom_line)
                             86 LOAD_FAST                0 (self)
                             88 STORE_ATTR               7 (_entry_bottom_line)
                
-               271          98 LOAD_FAST                0 (self)
+               288          98 LOAD_FAST                0 (self)
                            100 LOAD_ATTR                8 (entry_focusin_bottom_width)
                            110 LOAD_FAST                0 (self)
                            112 STORE_ATTR               9 (_entry_bottom_width)
                
-               273         122 LOAD_FAST                0 (self)
+               290         122 LOAD_FAST                0 (self)
                            124 LOAD_METHOD             10 (_draw)
                            146 LOAD_CONST               0 (None)
                            148 PRECALL                  1
                            152 CALL                     1
                            162 POP_TOP
                            164 LOAD_CONST               0 (None)
                            166 RETURN_VALUE
@@ -2319,56 +2377,56 @@
                   None
                names      ('entry_focusin_back', '_entry_back', 'entry_focusin_border', '_entry_border', 'entry_focusin_text_back', '_entry_text_back', 'entry_focusin_bottom_line', '_entry_bottom_line', 'entry_focusin_bottom_width', '_entry_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_focus'
-               firstlineno 266
+               firstlineno 283
                lnotab 0x020118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c00a00a00000000000000000000000000000000000000006400a6
                   010000ab010000000000000000010064005300
-               275           0 RESUME                   0
+               292           0 RESUME                   0
                
-               276           2 LOAD_FAST                0 (self)
+               293           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (entry_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_entry_back)
                
-               277          26 LOAD_FAST                0 (self)
+               294          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (entry_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_entry_border)
                
-               278          50 LOAD_FAST                0 (self)
+               295          50 LOAD_FAST                0 (self)
                             52 LOAD_ATTR                4 (entry_text_back)
                             62 LOAD_FAST                0 (self)
                             64 STORE_ATTR               5 (_entry_text_back)
                
-               279          74 LOAD_FAST                0 (self)
+               296          74 LOAD_FAST                0 (self)
                             76 LOAD_ATTR                6 (entry_bottom_line)
                             86 LOAD_FAST                0 (self)
                             88 STORE_ATTR               7 (_entry_bottom_line)
                
-               280          98 LOAD_FAST                0 (self)
+               297          98 LOAD_FAST                0 (self)
                            100 LOAD_ATTR                8 (entry_bottom_width)
                            110 LOAD_FAST                0 (self)
                            112 STORE_ATTR               9 (_entry_bottom_width)
                
-               282         122 LOAD_FAST                0 (self)
+               299         122 LOAD_FAST                0 (self)
                            124 LOAD_METHOD             10 (_draw)
                            146 LOAD_CONST               0 (None)
                            148 PRECALL                  1
                            152 CALL                     1
                            162 POP_TOP
                            164 LOAD_CONST               0 (None)
                            166 RETURN_VALUE
@@ -2376,66 +2434,66 @@
                   None
                names      ('entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_text_back', '_entry_text_back', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_focusout'
-               firstlineno 275
+               firstlineno 292
                lnotab 0x020118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               284           0 RESUME                   0
+               301           0 RESUME                   0
                
-               285           2 LOAD_FAST                0 (self)
+               302           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_set)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('focus_set',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_click'
-               firstlineno 284
+               firstlineno 301
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code 0x970064017c005f00000000000000000064005300
-               287           0 RESUME                   0
+               304           0 RESUME                   0
                
-               288           2 LOAD_CONST               1 (True)
+               305           2 LOAD_CONST               1 (True)
                              4 LOAD_FAST                0 (self)
                              6 STORE_ATTR               0 (hover)
                             16 LOAD_CONST               0 (None)
                             18 RETURN_VALUE
                consts
                   None
                   True
                names      ('hover',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_hover'
-               firstlineno 287
+               firstlineno 304
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
@@ -2443,186 +2501,186 @@
                   00ab000000000000000000735a64017c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c006a0a00000000000000007c005f0b00000000000000007c00a0
                   0c00000000000000000000000000000000000000006400a6010000ab0100
                   0000000000000001006400530064005300
-               290           0 RESUME                   0
+               307           0 RESUME                   0
                
-               291           2 LOAD_FAST                0 (self)
+               308           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_get)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_JUMP_FORWARD_IF_TRUE    90 (to 222)
                
-               292          42 LOAD_CONST               1 (False)
+               309          42 LOAD_CONST               1 (False)
                             44 LOAD_FAST                0 (self)
                             46 STORE_ATTR               1 (hover)
                
-               293          56 LOAD_FAST                0 (self)
+               310          56 LOAD_FAST                0 (self)
                             58 LOAD_ATTR                2 (entry_back)
                             68 LOAD_FAST                0 (self)
                             70 STORE_ATTR               3 (_entry_back)
                
-               294          80 LOAD_FAST                0 (self)
+               311          80 LOAD_FAST                0 (self)
                             82 LOAD_ATTR                4 (entry_border)
                             92 LOAD_FAST                0 (self)
                             94 STORE_ATTR               5 (_entry_border)
                
-               295         104 LOAD_FAST                0 (self)
+               312         104 LOAD_FAST                0 (self)
                            106 LOAD_ATTR                6 (entry_text_back)
                            116 LOAD_FAST                0 (self)
                            118 STORE_ATTR               7 (_entry_text_back)
                
-               296         128 LOAD_FAST                0 (self)
+               313         128 LOAD_FAST                0 (self)
                            130 LOAD_ATTR                8 (entry_bottom_line)
                            140 LOAD_FAST                0 (self)
                            142 STORE_ATTR               9 (_entry_bottom_line)
                
-               297         152 LOAD_FAST                0 (self)
+               314         152 LOAD_FAST                0 (self)
                            154 LOAD_ATTR               10 (entry_bottom_width)
                            164 LOAD_FAST                0 (self)
                            166 STORE_ATTR              11 (_entry_bottom_width)
                
-               299         176 LOAD_FAST                0 (self)
+               316         176 LOAD_FAST                0 (self)
                            178 LOAD_METHOD             12 (_draw)
                            200 LOAD_CONST               0 (None)
                            202 PRECALL                  1
                            206 CALL                     1
                            216 POP_TOP
                            218 LOAD_CONST               0 (None)
                            220 RETURN_VALUE
                
-               291     >>  222 LOAD_CONST               0 (None)
+               308     >>  222 LOAD_CONST               0 (None)
                            224 RETURN_VALUE
                consts
                   None
                   False
                names      ('focus_get', 'hover', 'entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_text_back', '_entry_text_back', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_hover_release'
-               firstlineno 290
+               firstlineno 307
                lnotab 0x020128010e01180118011801180118022ef8
             'font'
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               301           0 RESUME                   0
+               318           0 RESUME                   0
                
-               302           2 LOAD_FAST                1 (font)
+               319           2 LOAD_FAST                1 (font)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               303           6 LOAD_FAST                0 (self)
+               320           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (entry_text_font)
                             18 RETURN_VALUE
                
-               305     >>   20 LOAD_FAST                1 (font)
+               322     >>   20 LOAD_FAST                1 (font)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (entry_text_font)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('entry_text_font',)
                varnames   ('self', 'font')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'font'
-               firstlineno 301
+               firstlineno 318
                lnotab 0x020104010e02
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               307           0 RESUME                   0
+               324           0 RESUME                   0
                
-               308           2 LOAD_FAST                0 (self)
+               325           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'default_palette'
-               firstlineno 307
+               firstlineno 324
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 18
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   0264036404640564066407640564086409640a640b6407640c640d640e9c
                   06640f9c096901a6010000ab010000000000000000010064005300
-               310           0 RESUME                   0
+               327           0 RESUME                   0
                
-               311           2 LOAD_FAST                0 (self)
+               328           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               313          26 LOAD_CONST               1 ('entry')
+               330          26 LOAD_CONST               1 ('entry')
                
-               314          28 LOAD_CONST               2 (6)
+               331          28 LOAD_CONST               2 (6)
                
-               315          30 LOAD_CONST               3 ((3, 4))
+               332          30 LOAD_CONST               3 ((3, 4))
                
-               317          32 LOAD_CONST               4 ('#fdfdfd')
+               334          32 LOAD_CONST               4 ('#fdfdfd')
                
-               318          34 LOAD_CONST               5 ('#eaeaea')
+               335          34 LOAD_CONST               5 ('#eaeaea')
                
-               319          36 LOAD_CONST               6 ('#5f5f5f')
+               336          36 LOAD_CONST               6 ('#5f5f5f')
                
-               320          38 LOAD_CONST               7 (1)
+               337          38 LOAD_CONST               7 (1)
                
-               322          40 LOAD_CONST               5 ('#eaeaea')
+               339          40 LOAD_CONST               5 ('#eaeaea')
                
-               323          42 LOAD_CONST               8 (0)
+               340          42 LOAD_CONST               8 (0)
                
-               326          44 LOAD_CONST               9 ('#f9f9f9')
+               343          44 LOAD_CONST               9 ('#f9f9f9')
                
-               327          46 LOAD_CONST              10 ('#e2e2e2')
+               344          46 LOAD_CONST              10 ('#e2e2e2')
                
-               328          48 LOAD_CONST              11 ('#1a1a1a')
+               345          48 LOAD_CONST              11 ('#1a1a1a')
                
-               329          50 LOAD_CONST               7 (1)
+               346          50 LOAD_CONST               7 (1)
                
-               331          52 LOAD_CONST              12 ('#185fb4')
+               348          52 LOAD_CONST              12 ('#185fb4')
                
-               332          54 LOAD_CONST              13 (2)
+               349          54 LOAD_CONST              13 (2)
                
-               325          56 LOAD_CONST              14 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
+               342          56 LOAD_CONST              14 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
                             58 BUILD_CONST_KEY_MAP      6
                
-               313          60 LOAD_CONST              15 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
+               330          60 LOAD_CONST              15 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
                             62 BUILD_CONST_KEY_MAP      9
                
-               312          64 BUILD_MAP                1
+               329          64 BUILD_MAP                1
                
-               311          66 PRECALL                  1
+               328          66 PRECALL                  1
                             70 CALL                     1
                             80 POP_TOP
                             82 LOAD_CONST               0 (None)
                             84 RETURN_VALUE
                consts
                   None
                   'entry'
@@ -2642,71 +2700,71 @@
                   ('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'palette_light'
-               firstlineno 310
+               firstlineno 327
                lnotab
                   0x0201180202010201020202010201020102020201020302010201020102
                   02020102f904f404ff02ff
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 18
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   026403640464056406640764086409640a640564086407640b640c640d9c
                   06640e9c096901a6010000ab010000000000000000010064005300
-               338           0 RESUME                   0
+               355           0 RESUME                   0
                
-               339           2 LOAD_FAST                0 (self)
+               356           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               341          26 LOAD_CONST               1 ('entry')
+               358          26 LOAD_CONST               1 ('entry')
                
-               342          28 LOAD_CONST               2 (6)
+               359          28 LOAD_CONST               2 (6)
                
-               343          30 LOAD_CONST               3 ((3, 4))
+               360          30 LOAD_CONST               3 ((3, 4))
                
-               345          32 LOAD_CONST               4 ('#353535')
+               362          32 LOAD_CONST               4 ('#353535')
                
-               346          34 LOAD_CONST               5 ('#454545')
+               363          34 LOAD_CONST               5 ('#454545')
                
-               347          36 LOAD_CONST               6 ('#cecece')
+               364          36 LOAD_CONST               6 ('#cecece')
                
-               348          38 LOAD_CONST               7 (1)
+               365          38 LOAD_CONST               7 (1)
                
-               350          40 LOAD_CONST               8 ('#ffffff')
+               367          40 LOAD_CONST               8 ('#ffffff')
                
-               351          42 LOAD_CONST               9 (0)
+               368          42 LOAD_CONST               9 (0)
                
-               354          44 LOAD_CONST              10 ('#2f2f2f')
+               371          44 LOAD_CONST              10 ('#2f2f2f')
                
-               355          46 LOAD_CONST               5 ('#454545')
+               372          46 LOAD_CONST               5 ('#454545')
                
-               356          48 LOAD_CONST               8 ('#ffffff')
+               373          48 LOAD_CONST               8 ('#ffffff')
                
-               357          50 LOAD_CONST               7 (1)
+               374          50 LOAD_CONST               7 (1)
                
-               359          52 LOAD_CONST              11 ('#4cc2ff')
+               376          52 LOAD_CONST              11 ('#4cc2ff')
                
-               360          54 LOAD_CONST              12 (2)
+               377          54 LOAD_CONST              12 (2)
                
-               353          56 LOAD_CONST              13 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
+               370          56 LOAD_CONST              13 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
                             58 BUILD_CONST_KEY_MAP      6
                
-               341          60 LOAD_CONST              14 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
+               358          60 LOAD_CONST              14 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
                             62 BUILD_CONST_KEY_MAP      9
                
-               340          64 BUILD_MAP                1
+               357          64 BUILD_MAP                1
                
-               339          66 PRECALL                  1
+               356          66 PRECALL                  1
                             70 CALL                     1
                             80 POP_TOP
                             82 LOAD_CONST               0 (None)
                             84 RETURN_VALUE
                consts
                   None
                   'entry'
@@ -2725,15 +2783,15 @@
                   ('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'palette_dark'
-               firstlineno 338
+               firstlineno 355
                lnotab
                   0x0201180202010201020202010201020102020201020302010201020102
                   02020102f904f404ff02ff
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
@@ -2742,247 +2800,247 @@
                   0x95019700740100000000000000000000a6000000ab0000000000000000
                   00a00100000000000000000000000000000000000000007c01a6010000ab
                   010000000000000000010064017c01760072157c01640119000000000000
                   0000006402190000000000000000007c005f020000000000000000640053
                   0064005300
                              0 COPY_FREE_VARS           1
                
-               366           2 RESUME                   0
+               383           2 RESUME                   0
                
-               367           4 LOAD_GLOBAL              1 (NULL + super)
+               384           4 LOAD_GLOBAL              1 (NULL + super)
                             16 PRECALL                  0
                             20 CALL                     0
                             30 LOAD_METHOD              1 (palette)
                             52 LOAD_FAST                1 (dict)
                             54 PRECALL                  1
                             58 CALL                     1
                             68 POP_TOP
                
-               368          70 LOAD_CONST               1 ('entry')
+               385          70 LOAD_CONST               1 ('entry')
                             72 LOAD_FAST                1 (dict)
                             74 CONTAINS_OP              0
                             76 POP_JUMP_FORWARD_IF_FALSE    21 (to 120)
                
-               369          78 LOAD_FAST                1 (dict)
+               386          78 LOAD_FAST                1 (dict)
                             80 LOAD_CONST               1 ('entry')
                             82 BINARY_SUBSCR
                             92 LOAD_CONST               2 ('radius')
                             94 BINARY_SUBSCR
                            104 LOAD_FAST                0 (self)
                            106 STORE_ATTR               2 (entry_radius)
                            116 LOAD_CONST               0 (None)
                            118 RETURN_VALUE
                
-               368     >>  120 LOAD_CONST               0 (None)
+               385     >>  120 LOAD_CONST               0 (None)
                            122 RETURN_VALUE
                consts
                   None
                   'entry'
                   'radius'
                names      ('super', 'palette', 'entry_radius')
                varnames   ('self', 'dict')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'palette'
-               firstlineno 366
+               firstlineno 383
                lnotab 0x0401420108012aff
             (None,)
          names      ('__name__', '__module__', '__qualname__', '__init__', '_other', 'border_radius', '_draw', '_focus', '_focusout', '_click', '_hover', '_hover_release', 'Font', 'font', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
          name       'AdwDrawBasicRoundEntry'
-         firstlineno 222
-         lnotab 0x0c010a0306040806061e0809080908030803080b0e060603061c061c
+         firstlineno 236
+         lnotab 0x0c010a030604080606210809080908030803080b0e060603061c061c
       'AdwDrawBasicRoundEntry'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         372           0 RESUME                   0
+         389           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundEntry')
                        8 STORE_NAME               2 (__qualname__)
          
-         373          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 373>)
+         390          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 390>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundEntry'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               373           0 RESUME                   0
+               390           0 RESUME                   0
                
-               374           2 LOAD_FAST                0 (self)
+               391           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'default_palette'
-               firstlineno 373
+               firstlineno 390
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
          name       'AdwDrawRoundEntry'
-         firstlineno 372
+         firstlineno 389
          lnotab 0x0a01
       'AdwDrawRoundEntry'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         377           0 RESUME                   0
+         394           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundDarkEntry')
                        8 STORE_NAME               2 (__qualname__)
          
-         378          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 378>)
+         395          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 395>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundDarkEntry'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               378           0 RESUME                   0
+               395           0 RESUME                   0
                
-               379           2 LOAD_FAST                0 (self)
+               396           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'default_palette'
-               firstlineno 378
+               firstlineno 395
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
          name       'AdwDrawRoundDarkEntry'
-         firstlineno 377
+         firstlineno 394
          lnotab 0x0a01
       'AdwDrawRoundDarkEntry'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 3
          flags     : 0
          code
             0x8700970065005a0164005a0288006601640184085a03640284005a0464
             0e640484015a05640584005a06640e640684015a07640e640784015a0864
             0e640884015a09640e640984015a0a640e640a84015a0b640e640b650c66
             02640c84055a0d640d84005a0e880078015a0f5300
                        0 MAKE_CELL                0 (__class__)
          
-         382           2 RESUME                   0
+         399           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawBasicRoundEntry3')
                       10 STORE_NAME               2 (__qualname__)
          
-         383          12 LOAD_CLOSURE             0 (__class__)
+         400          12 LOAD_CLOSURE             0 (__class__)
                       14 BUILD_TUPLE              1
-                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\entry.py", line 383>)
+                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\entry.py", line 400>)
                       18 MAKE_FUNCTION            8 (closure)
                       20 STORE_NAME               3 (__init__)
          
-         386          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\entry.py", line 386>)
+         403          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\entry.py", line 403>)
                       24 MAKE_FUNCTION            0
                       26 STORE_NAME               4 (_other)
          
-         389          28 LOAD_CONST              14 ((None,))
-                      30 LOAD_CONST               4 (<code object border_radius, file "D:\tkadw\tkadw\canvas\entry.py", line 389>)
+         406          28 LOAD_CONST              14 ((None,))
+                      30 LOAD_CONST               4 (<code object border_radius, file "D:\tkadw\tkadw\canvas\entry.py", line 406>)
                       32 MAKE_FUNCTION            1 (defaults)
                       34 STORE_NAME               5 (border_radius)
          
-         395          36 LOAD_CONST               5 (<code object _draw, file "D:\tkadw\tkadw\canvas\entry.py", line 395>)
+         412          36 LOAD_CONST               5 (<code object _draw, file "D:\tkadw\tkadw\canvas\entry.py", line 412>)
                       38 MAKE_FUNCTION            0
                       40 STORE_NAME               6 (_draw)
          
-         431          42 LOAD_CONST              14 ((None,))
-                      44 LOAD_CONST               6 (<code object _focus, file "D:\tkadw\tkadw\canvas\entry.py", line 431>)
+         451          42 LOAD_CONST              14 ((None,))
+                      44 LOAD_CONST               6 (<code object _focus, file "D:\tkadw\tkadw\canvas\entry.py", line 451>)
                       46 MAKE_FUNCTION            1 (defaults)
                       48 STORE_NAME               7 (_focus)
          
-         440          50 LOAD_CONST              14 ((None,))
-                      52 LOAD_CONST               7 (<code object _focusout, file "D:\tkadw\tkadw\canvas\entry.py", line 440>)
+         460          50 LOAD_CONST              14 ((None,))
+                      52 LOAD_CONST               7 (<code object _focusout, file "D:\tkadw\tkadw\canvas\entry.py", line 460>)
                       54 MAKE_FUNCTION            1 (defaults)
                       56 STORE_NAME               8 (_focusout)
          
-         449          58 LOAD_CONST              14 ((None,))
-                      60 LOAD_CONST               8 (<code object _click, file "D:\tkadw\tkadw\canvas\entry.py", line 449>)
+         469          58 LOAD_CONST              14 ((None,))
+                      60 LOAD_CONST               8 (<code object _click, file "D:\tkadw\tkadw\canvas\entry.py", line 469>)
                       62 MAKE_FUNCTION            1 (defaults)
                       64 STORE_NAME               9 (_click)
          
-         452          66 LOAD_CONST              14 ((None,))
-                      68 LOAD_CONST               9 (<code object _hover, file "D:\tkadw\tkadw\canvas\entry.py", line 452>)
+         472          66 LOAD_CONST              14 ((None,))
+                      68 LOAD_CONST               9 (<code object _hover, file "D:\tkadw\tkadw\canvas\entry.py", line 472>)
                       70 MAKE_FUNCTION            1 (defaults)
                       72 STORE_NAME              10 (_hover)
          
-         455          74 LOAD_CONST              14 ((None,))
-                      76 LOAD_CONST              10 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\entry.py", line 455>)
+         475          74 LOAD_CONST              14 ((None,))
+                      76 LOAD_CONST              10 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\entry.py", line 475>)
                       78 MAKE_FUNCTION            1 (defaults)
                       80 STORE_NAME              11 (_hover_release)
          
-         466          82 LOAD_CONST              14 ((None,))
+         486          82 LOAD_CONST              14 ((None,))
                       84 LOAD_CONST              11 ('font')
                       86 LOAD_NAME               12 (Font)
                       88 BUILD_TUPLE              2
-                      90 LOAD_CONST              12 (<code object font, file "D:\tkadw\tkadw\canvas\entry.py", line 466>)
+                      90 LOAD_CONST              12 (<code object font, file "D:\tkadw\tkadw\canvas\entry.py", line 486>)
                       92 MAKE_FUNCTION            5 (defaults, annotations)
                       94 STORE_NAME              13 (font)
          
-         472          96 LOAD_CONST              13 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 472>)
+         492          96 LOAD_CONST              13 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 492>)
                       98 MAKE_FUNCTION            0
                      100 STORE_NAME              14 (default_palette)
                      102 LOAD_CLOSURE             0 (__class__)
                      104 COPY                     1
                      106 STORE_NAME              15 (__classcell__)
                      108 RETURN_VALUE
          consts
@@ -2993,17 +3051,17 @@
                stacksize : 5
                flags     : 15
                code
                   0x950197000200740100000000000000000000a6000000ab000000000000
                   0000006a0100000000000000007c0169007c02a4018e01010064005300
                              0 COPY_FREE_VARS           1
                
-               383           2 RESUME                   0
+               400           2 RESUME                   0
                
-               384           4 PUSH_NULL
+               401           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                1 (args)
                             44 BUILD_MAP                0
                             46 LOAD_FAST                2 (kwargs)
@@ -3016,29 +3074,29 @@
                   None
                names      ('super', '__init__')
                varnames   ('self', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '__init__'
-               firstlineno 383
+               firstlineno 400
                lnotab 0x0401
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 5
                flags     : 3
                code
                   0x97007c00a00000000000000000000000000000000000000000007c006a
                   010000000000000000a00200000000000000000000000000000000000000
                   006401a6010000ab0100000000000000006402ac03a6020000ab02000000
                   0000000000010064005300
-               386           0 RESUME                   0
+               403           0 RESUME                   0
                
-               387           2 LOAD_FAST                0 (self)
+               404           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (configure)
                             26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                1 (master)
                             38 LOAD_METHOD              2 (cget)
                             60 LOAD_CONST               1 ('bg')
                             62 PRECALL                  1
                             66 CALL                     1
@@ -3056,48 +3114,48 @@
                   ('background', 'borderwidth')
                names      ('configure', 'master', 'cget')
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_other'
-               firstlineno 386
+               firstlineno 403
                lnotab 0x0201
             None
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               389           0 RESUME                   0
+               406           0 RESUME                   0
                
-               390           2 LOAD_FAST                1 (radius)
+               407           2 LOAD_FAST                1 (radius)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               391           6 LOAD_FAST                0 (self)
+               408           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (button_radius)
                             18 RETURN_VALUE
                
-               393     >>   20 LOAD_FAST                1 (radius)
+               410     >>   20 LOAD_FAST                1 (radius)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (button_radius)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('button_radius',)
                varnames   ('self', 'radius')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'border_radius'
-               firstlineno 389
+               firstlineno 406
                lnotab 0x020104010e02
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 10
                flags     : 3
                code
@@ -3133,195 +3191,195 @@
                   00000000000000000000000000000000007c006a100000000000000000a6
                   010000ab01000000000000000001007c00a0110000000000000000000000
                   0000000000000000007c006a1000000000000000007c006a0c0000000000
                   000000a6020000ab02000000000000000001007c006a0b00000000000000
                   00a01200000000000000000000000000000000000000007c006a07000000
                   00000000007c006a1300000000000000007c006a130000000000000000ac
                   0aa6030000ab030000000000000000010064005300
-               395           0 RESUME                   0
+               412           0 RESUME                   0
                
-               396           2 LOAD_FAST                0 (self)
+               413           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               398          44 LOAD_FAST                0 (self)
+               416          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_round_rect4)
                
-               399          68 LOAD_CONST               2 (0)
+               417          68 LOAD_CONST               2 (0)
                
-               400          70 LOAD_CONST               2 (0)
+               418          70 LOAD_CONST               2 (0)
                
-               401          72 LOAD_FAST                0 (self)
+               419          72 LOAD_FAST                0 (self)
                             74 LOAD_METHOD              2 (winfo_width)
                             96 PRECALL                  0
                            100 CALL                     0
                            110 LOAD_CONST               3 (1)
                            112 BINARY_OP               10 (-)
                
-               402         116 LOAD_FAST                0 (self)
+               420         116 LOAD_FAST                0 (self)
                            118 LOAD_METHOD              3 (winfo_height)
                            140 PRECALL                  0
                            144 CALL                     0
                            154 LOAD_CONST               3 (1)
                            156 BINARY_OP               10 (-)
                
-               403         160 LOAD_FAST                0 (self)
+               421         160 LOAD_FAST                0 (self)
                            162 LOAD_ATTR                4 (entry_radius)
                
-               404         172 LOAD_FAST                0 (self)
-                           174 LOAD_ATTR                5 (entry_border_width)
+               422         172 LOAD_FAST                0 (self)
+                           174 LOAD_ATTR                5 (_entry_border_width)
                
-               405         184 LOAD_FAST                0 (self)
+               423         184 LOAD_FAST                0 (self)
                            186 LOAD_ATTR                6 (_entry_border)
                            196 LOAD_FAST                0 (self)
                            198 LOAD_ATTR                7 (_entry_back)
                
-               398         208 KW_NAMES                 4
+               416         208 KW_NAMES                 4
                            210 PRECALL                  8
                            214 CALL                     8
                            224 POP_TOP
                
-               408         226 LOAD_CONST               5 ('button_frame')
+               426         226 LOAD_CONST               5 ('button_frame')
                            228 LOAD_FAST                0 (self)
                            230 STORE_ATTR               8 (entry_frame)
                
-               410         240 LOAD_FAST                0 (self)
+               429         240 LOAD_FAST                0 (self)
                            242 LOAD_METHOD              9 (create_window)
                
-               411         264 LOAD_FAST                0 (self)
+               430         264 LOAD_FAST                0 (self)
                            266 LOAD_METHOD              2 (winfo_width)
                            288 PRECALL                  0
                            292 CALL                     0
                            302 LOAD_CONST               6 (2)
                            304 BINARY_OP               11 (/)
                            308 LOAD_FAST                0 (self)
                            310 LOAD_METHOD              3 (winfo_height)
                            332 PRECALL                  0
                            336 CALL                     0
                            346 LOAD_CONST               6 (2)
                            348 BINARY_OP               11 (/)
                
-               412         352 LOAD_FAST                0 (self)
+               431         352 LOAD_FAST                0 (self)
                            354 LOAD_METHOD              2 (winfo_width)
                            376 PRECALL                  0
                            380 CALL                     0
                            390 LOAD_FAST                0 (self)
-                           392 LOAD_ATTR                5 (entry_border_width)
+                           392 LOAD_ATTR                5 (_entry_border_width)
                            402 BINARY_OP               10 (-)
                            406 LOAD_FAST                0 (self)
                            408 LOAD_ATTR               10 (entry_padding)
                            418 LOAD_CONST               2 (0)
                            420 BINARY_SUBSCR
                            430 BINARY_OP               10 (-)
                            434 LOAD_CONST               6 (2)
                            436 BINARY_OP               10 (-)
                
-               413         440 LOAD_FAST                0 (self)
+               432         440 LOAD_FAST                0 (self)
                            442 LOAD_METHOD              3 (winfo_height)
                            464 PRECALL                  0
                            468 CALL                     0
                            478 LOAD_FAST                0 (self)
-                           480 LOAD_ATTR                5 (entry_border_width)
+                           480 LOAD_ATTR                5 (_entry_border_width)
                            490 BINARY_OP               10 (-)
                            494 LOAD_FAST                0 (self)
                            496 LOAD_ATTR               10 (entry_padding)
                            506 LOAD_CONST               3 (1)
                            508 BINARY_SUBSCR
                            518 BINARY_OP               10 (-)
                            522 LOAD_CONST               6 (2)
                            524 BINARY_OP               10 (-)
                
-               414         528 LOAD_FAST                0 (self)
+               433         528 LOAD_FAST                0 (self)
                            530 LOAD_ATTR               11 (entry)
                
-               410         540 KW_NAMES                 7
+               429         540 KW_NAMES                 7
                            542 PRECALL                  5
                            546 CALL                     5
                            556 LOAD_FAST                0 (self)
                            558 STORE_ATTR              12 (entry_text)
                
-               417         568 LOAD_FAST                0 (self)
+               437         568 LOAD_FAST                0 (self)
                            570 LOAD_METHOD             13 (create_rectangle)
                            592 LOAD_CONST               3 (1)
                            594 LOAD_FAST                0 (self)
                            596 LOAD_ATTR                4 (entry_radius)
                            606 LOAD_CONST               8 (5)
                            608 BINARY_OP               11 (/)
                            612 BINARY_OP                0 (+)
                
-               418         616 LOAD_FAST                0 (self)
+               438         616 LOAD_FAST                0 (self)
                            618 LOAD_METHOD              3 (winfo_height)
                            640 PRECALL                  0
                            644 CALL                     0
                            654 LOAD_FAST                0 (self)
                            656 LOAD_ATTR               14 (_entry_bottom_width)
                            666 BINARY_OP               10 (-)
                            670 LOAD_CONST               3 (1)
                            672 BINARY_OP               10 (-)
                
-               419         676 LOAD_FAST                0 (self)
+               439         676 LOAD_FAST                0 (self)
                            678 LOAD_METHOD              2 (winfo_width)
                            700 PRECALL                  0
                            704 CALL                     0
                            714 LOAD_CONST               3 (1)
                            716 BINARY_OP               10 (-)
                            720 LOAD_FAST                0 (self)
                            722 LOAD_ATTR                4 (entry_radius)
                            732 LOAD_CONST               8 (5)
                            734 BINARY_OP               11 (/)
                            738 BINARY_OP               10 (-)
                
-               420         742 LOAD_FAST                0 (self)
+               440         742 LOAD_FAST                0 (self)
                            744 LOAD_METHOD              3 (winfo_height)
                            766 PRECALL                  0
                            770 CALL                     0
                            780 LOAD_CONST               3 (1)
                            782 BINARY_OP               10 (-)
                
-               421         786 LOAD_FAST                0 (self)
+               441         786 LOAD_FAST                0 (self)
                            788 LOAD_ATTR               15 (_entry_bottom_line)
                            798 LOAD_FAST                0 (self)
                            800 LOAD_ATTR               15 (_entry_bottom_line)
                
-               422         810 LOAD_CONST               2 (0)
+               442         810 LOAD_CONST               2 (0)
                
-               417         812 KW_NAMES                 9
+               437         812 KW_NAMES                 9
                            814 PRECALL                  7
                            818 CALL                     7
                            828 LOAD_FAST                0 (self)
                            830 STORE_ATTR              16 (entry_bottom)
                
-               424         840 LOAD_FAST                0 (self)
+               444         840 LOAD_FAST                0 (self)
                            842 LOAD_ATTR               14 (_entry_bottom_width)
                            852 LOAD_CONST               2 (0)
                            854 COMPARE_OP               2 (==)
                            860 POP_JUMP_FORWARD_IF_FALSE    26 (to 914)
                
-               425         862 LOAD_FAST                0 (self)
+               445         862 LOAD_FAST                0 (self)
                            864 LOAD_METHOD              0 (delete)
                            886 LOAD_FAST                0 (self)
                            888 LOAD_ATTR               16 (entry_bottom)
                            898 PRECALL                  1
                            902 CALL                     1
                            912 POP_TOP
                
-               427     >>  914 LOAD_FAST                0 (self)
+               447     >>  914 LOAD_FAST                0 (self)
                            916 LOAD_METHOD             17 (tag_raise)
                            938 LOAD_FAST                0 (self)
                            940 LOAD_ATTR               16 (entry_bottom)
                            950 LOAD_FAST                0 (self)
                            952 LOAD_ATTR               12 (entry_text)
                            962 PRECALL                  2
                            966 CALL                     2
                            976 POP_TOP
                
-               429         978 LOAD_FAST                0 (self)
+               449         978 LOAD_FAST                0 (self)
                            980 LOAD_ATTR               11 (entry)
                            990 LOAD_METHOD             18 (configure)
                           1012 LOAD_FAST                0 (self)
                           1014 LOAD_ATTR                7 (_entry_back)
                           1024 LOAD_FAST                0 (self)
                           1026 LOAD_ATTR               19 (_entry_text_back)
                           1036 LOAD_FAST                0 (self)
@@ -3340,64 +3398,64 @@
                   ('width', 'outline', 'fill')
                   'button_frame'
                   2
                   ('width', 'height', 'window')
                   5
                   ('fill', 'outline', 'width')
                   ('background', 'foreground', 'insertbackground')
-               names      ('delete', 'create_round_rect4', 'winfo_width', 'winfo_height', 'entry_radius', 'entry_border_width', '_entry_border', '_entry_back', 'entry_frame', 'create_window', 'entry_padding', 'entry', 'entry_text', 'create_rectangle', '_entry_bottom_width', '_entry_bottom_line', 'entry_bottom', 'tag_raise', 'configure', '_entry_text_back')
+               names      ('delete', 'create_round_rect4', 'winfo_width', 'winfo_height', 'entry_radius', '_entry_border_width', '_entry_border', '_entry_back', 'entry_frame', 'create_window', 'entry_padding', 'entry', 'entry_text', 'create_rectangle', '_entry_bottom_width', '_entry_bottom_line', 'entry_bottom', 'tag_raise', 'configure', '_entry_text_back')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_draw'
-               firstlineno 395
+               firstlineno 412
                lnotab
-                  0x02012a021801020102012c012c010c010c0118f9120a0e021801580158
-                  0158010cfc1c0730013c0142012c01180102fb1c07160134024002
+                  0x02012a031801020102012c012c010c010c0118f9120a0e031801580158
+                  0158010cfc1c0830013c0142012c01180102fb1c07160134024002
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c00a00a00000000000000000000000000000000000000006400a6
                   010000ab010000000000000000010064005300
-               431           0 RESUME                   0
+               451           0 RESUME                   0
                
-               432           2 LOAD_FAST                0 (self)
+               452           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (entry_focusin_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_entry_back)
                
-               433          26 LOAD_FAST                0 (self)
+               453          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (entry_focusin_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_entry_border)
                
-               434          50 LOAD_FAST                0 (self)
+               454          50 LOAD_FAST                0 (self)
                             52 LOAD_ATTR                4 (entry_focusin_text_back)
                             62 LOAD_FAST                0 (self)
                             64 STORE_ATTR               5 (_entry_text_back)
                
-               435          74 LOAD_FAST                0 (self)
+               455          74 LOAD_FAST                0 (self)
                             76 LOAD_ATTR                6 (entry_focusin_bottom_line)
                             86 LOAD_FAST                0 (self)
                             88 STORE_ATTR               7 (_entry_bottom_line)
                
-               436          98 LOAD_FAST                0 (self)
+               456          98 LOAD_FAST                0 (self)
                            100 LOAD_ATTR                8 (entry_focusin_bottom_width)
                            110 LOAD_FAST                0 (self)
                            112 STORE_ATTR               9 (_entry_bottom_width)
                
-               438         122 LOAD_FAST                0 (self)
+               458         122 LOAD_FAST                0 (self)
                            124 LOAD_METHOD             10 (_draw)
                            146 LOAD_CONST               0 (None)
                            148 PRECALL                  1
                            152 CALL                     1
                            162 POP_TOP
                            164 LOAD_CONST               0 (None)
                            166 RETURN_VALUE
@@ -3405,56 +3463,56 @@
                   None
                names      ('entry_focusin_back', '_entry_back', 'entry_focusin_border', '_entry_border', 'entry_focusin_text_back', '_entry_text_back', 'entry_focusin_bottom_line', '_entry_bottom_line', 'entry_focusin_bottom_width', '_entry_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_focus'
-               firstlineno 431
+               firstlineno 451
                lnotab 0x020118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c00a00a00000000000000000000000000000000000000006400a6
                   010000ab010000000000000000010064005300
-               440           0 RESUME                   0
+               460           0 RESUME                   0
                
-               441           2 LOAD_FAST                0 (self)
+               461           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (entry_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_entry_back)
                
-               442          26 LOAD_FAST                0 (self)
+               462          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (entry_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_entry_border)
                
-               443          50 LOAD_FAST                0 (self)
+               463          50 LOAD_FAST                0 (self)
                             52 LOAD_ATTR                4 (entry_text_back)
                             62 LOAD_FAST                0 (self)
                             64 STORE_ATTR               5 (_entry_text_back)
                
-               444          74 LOAD_FAST                0 (self)
+               464          74 LOAD_FAST                0 (self)
                             76 LOAD_ATTR                6 (entry_bottom_line)
                             86 LOAD_FAST                0 (self)
                             88 STORE_ATTR               7 (_entry_bottom_line)
                
-               445          98 LOAD_FAST                0 (self)
+               465          98 LOAD_FAST                0 (self)
                            100 LOAD_ATTR                8 (entry_bottom_width)
                            110 LOAD_FAST                0 (self)
                            112 STORE_ATTR               9 (_entry_bottom_width)
                
-               447         122 LOAD_FAST                0 (self)
+               467         122 LOAD_FAST                0 (self)
                            124 LOAD_METHOD             10 (_draw)
                            146 LOAD_CONST               0 (None)
                            148 PRECALL                  1
                            152 CALL                     1
                            162 POP_TOP
                            164 LOAD_CONST               0 (None)
                            166 RETURN_VALUE
@@ -3462,66 +3520,66 @@
                   None
                names      ('entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_text_back', '_entry_text_back', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_focusout'
-               firstlineno 440
+               firstlineno 460
                lnotab 0x020118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               449           0 RESUME                   0
+               469           0 RESUME                   0
                
-               450           2 LOAD_FAST                0 (self)
+               470           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_set)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('focus_set',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_click'
-               firstlineno 449
+               firstlineno 469
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code 0x970064017c005f00000000000000000064005300
-               452           0 RESUME                   0
+               472           0 RESUME                   0
                
-               453           2 LOAD_CONST               1 (True)
+               473           2 LOAD_CONST               1 (True)
                              4 LOAD_FAST                0 (self)
                              6 STORE_ATTR               0 (hover)
                             16 LOAD_CONST               0 (None)
                             18 RETURN_VALUE
                consts
                   None
                   True
                names      ('hover',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_hover'
-               firstlineno 452
+               firstlineno 472
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
@@ -3529,253 +3587,253 @@
                   00ab000000000000000000735a64017c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c006a0a00000000000000007c005f0b00000000000000007c00a0
                   0c00000000000000000000000000000000000000006400a6010000ab0100
                   0000000000000001006400530064005300
-               455           0 RESUME                   0
+               475           0 RESUME                   0
                
-               456           2 LOAD_FAST                0 (self)
+               476           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_get)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_JUMP_FORWARD_IF_TRUE    90 (to 222)
                
-               457          42 LOAD_CONST               1 (False)
+               477          42 LOAD_CONST               1 (False)
                             44 LOAD_FAST                0 (self)
                             46 STORE_ATTR               1 (hover)
                
-               458          56 LOAD_FAST                0 (self)
+               478          56 LOAD_FAST                0 (self)
                             58 LOAD_ATTR                2 (entry_back)
                             68 LOAD_FAST                0 (self)
                             70 STORE_ATTR               3 (_entry_back)
                
-               459          80 LOAD_FAST                0 (self)
+               479          80 LOAD_FAST                0 (self)
                             82 LOAD_ATTR                4 (entry_border)
                             92 LOAD_FAST                0 (self)
                             94 STORE_ATTR               5 (_entry_border)
                
-               460         104 LOAD_FAST                0 (self)
+               480         104 LOAD_FAST                0 (self)
                            106 LOAD_ATTR                6 (entry_text_back)
                            116 LOAD_FAST                0 (self)
                            118 STORE_ATTR               7 (_entry_text_back)
                
-               461         128 LOAD_FAST                0 (self)
+               481         128 LOAD_FAST                0 (self)
                            130 LOAD_ATTR                8 (entry_bottom_line)
                            140 LOAD_FAST                0 (self)
                            142 STORE_ATTR               9 (_entry_bottom_line)
                
-               462         152 LOAD_FAST                0 (self)
+               482         152 LOAD_FAST                0 (self)
                            154 LOAD_ATTR               10 (entry_bottom_width)
                            164 LOAD_FAST                0 (self)
                            166 STORE_ATTR              11 (_entry_bottom_width)
                
-               464         176 LOAD_FAST                0 (self)
+               484         176 LOAD_FAST                0 (self)
                            178 LOAD_METHOD             12 (_draw)
                            200 LOAD_CONST               0 (None)
                            202 PRECALL                  1
                            206 CALL                     1
                            216 POP_TOP
                            218 LOAD_CONST               0 (None)
                            220 RETURN_VALUE
                
-               456     >>  222 LOAD_CONST               0 (None)
+               476     >>  222 LOAD_CONST               0 (None)
                            224 RETURN_VALUE
                consts
                   None
                   False
                names      ('focus_get', 'hover', 'entry_back', '_entry_back', 'entry_border', '_entry_border', 'entry_text_back', '_entry_text_back', 'entry_bottom_line', '_entry_bottom_line', 'entry_bottom_width', '_entry_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       '_hover_release'
-               firstlineno 455
+               firstlineno 475
                lnotab 0x020128010e01180118011801180118022ef8
             'font'
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               466           0 RESUME                   0
+               486           0 RESUME                   0
                
-               467           2 LOAD_FAST                1 (font)
+               487           2 LOAD_FAST                1 (font)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               468           6 LOAD_FAST                0 (self)
+               488           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (entry_text_font)
                             18 RETURN_VALUE
                
-               470     >>   20 LOAD_FAST                1 (font)
+               490     >>   20 LOAD_FAST                1 (font)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (entry_text_font)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('entry_text_font',)
                varnames   ('self', 'font')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'font'
-               firstlineno 466
+               firstlineno 486
                lnotab 0x020104010e02
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               472           0 RESUME                   0
+               492           0 RESUME                   0
                
-               473           2 LOAD_FAST                0 (self)
+               493           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'default_palette'
-               firstlineno 472
+               firstlineno 492
                lnotab 0x0201
             (None,)
          names      ('__name__', '__module__', '__qualname__', '__init__', '_other', 'border_radius', '_draw', '_focus', '_focusout', '_click', '_hover', '_hover_release', 'Font', 'font', 'default_palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
          name       'AdwDrawBasicRoundEntry3'
-         firstlineno 382
-         lnotab 0x0c010a030603080606240809080908030803080b0e06
+         firstlineno 399
+         lnotab 0x0c010a030603080606270809080908030803080b0e06
       'AdwDrawBasicRoundEntry3'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         476           0 RESUME                   0
+         496           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundEntry3')
                        8 STORE_NAME               2 (__qualname__)
          
-         477          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 477>)
+         497          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 497>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundEntry3'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               477           0 RESUME                   0
+               497           0 RESUME                   0
                
-               478           2 LOAD_FAST                0 (self)
+               498           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'default_palette'
-               firstlineno 477
+               firstlineno 497
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
          name       'AdwDrawRoundEntry3'
-         firstlineno 476
+         firstlineno 496
          lnotab 0x0a01
       'AdwDrawRoundEntry3'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         481           0 RESUME                   0
+         501           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundDarkEntry3')
                        8 STORE_NAME               2 (__qualname__)
          
-         482          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 482>)
+         502          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\entry.py", line 502>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundDarkEntry3'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               482           0 RESUME                   0
+               502           0 RESUME                   0
                
-               483           2 LOAD_FAST                0 (self)
+               503           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
                name       'default_palette'
-               firstlineno 482
+               firstlineno 502
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
          name       'AdwDrawRoundDarkEntry3'
-         firstlineno 481
+         firstlineno 501
          lnotab 0x0a01
       'AdwDrawRoundDarkEntry3'
       '__main__'
       ('Tk',)
       'Hello'
       ('text',)
       'x'
@@ -3786,10 +3844,10 @@
    varnames   ()
    freevars   ()
    cellvars   ()
    filename   'D:\\tkadw\\tkadw\\canvas\\entry.py'
    name       '<module>'
    firstlineno 1
    lnotab
-      0x00ff020110010c041c7f004e1c051c061c7f00171c051c051c5e1c051c
+      0x00ff020110010c041c7f005c1c051c061c7f001a1c051c051c611c051c
       050c010c0214021801300218013002180130021801300218013002180130
       022ce9
```

### Comparing `tkadw-0.2.1/tkadw/canvas/__pycache__/frame.cpython-311.pyc` & `tkadw-0.2.2/tkadw/canvas/__pycache__/frame.cpython-311.pyc`

 * *Files 3% similar despite different names*

#### Python bytecode

```diff
@@ -1,10 +1,10 @@
 magic:    0xa70d0d0a
-moddate:  0xf04b9664 (Sat Jun 24 01:50:40 2023 UTC)
-files sz: 6326
+moddate:  0x25de9664 (Sat Jun 24 12:14:29 2023 UTC)
+files sz: 6506
 code
    argcount  : 0
    nlocals   : 0
    stacksize : 6
    flags     : 0
    code
       0x9700640064016c006d015a010100640064026c026d035a030100020047
@@ -57,224 +57,224 @@
                 32 MAKE_FUNCTION            0
                 34 LOAD_CONST               4 ('AdwDrawBasicFrame')
                 36 LOAD_NAME                1 (AdwDrawEngine)
                 38 PRECALL                  3
                 42 CALL                     3
                 52 STORE_NAME               4 (AdwDrawBasicFrame)
    
-    82          54 PUSH_NULL
+    84          54 PUSH_NULL
                 56 LOAD_BUILD_CLASS
-                58 LOAD_CONST               5 (<code object AdwDrawFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 82>)
+                58 LOAD_CONST               5 (<code object AdwDrawFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 84>)
                 60 MAKE_FUNCTION            0
                 62 LOAD_CONST               6 ('AdwDrawFrame')
                 64 LOAD_NAME                4 (AdwDrawBasicFrame)
                 66 PRECALL                  3
                 70 CALL                     3
                 80 STORE_NAME               5 (AdwDrawFrame)
    
-    87          82 PUSH_NULL
+    89          82 PUSH_NULL
                 84 LOAD_BUILD_CLASS
-                86 LOAD_CONST               7 (<code object AdwDrawDarkFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 87>)
+                86 LOAD_CONST               7 (<code object AdwDrawDarkFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 89>)
                 88 MAKE_FUNCTION            0
                 90 LOAD_CONST               8 ('AdwDrawDarkFrame')
                 92 LOAD_NAME                4 (AdwDrawBasicFrame)
                 94 PRECALL                  3
                 98 CALL                     3
                108 STORE_NAME               6 (AdwDrawDarkFrame)
    
-    92         110 PUSH_NULL
+    94         110 PUSH_NULL
                112 LOAD_BUILD_CLASS
-               114 LOAD_CONST               9 (<code object AdwDrawBasicRoundFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 92>)
+               114 LOAD_CONST               9 (<code object AdwDrawBasicRoundFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 94>)
                116 MAKE_FUNCTION            0
                118 LOAD_CONST              10 ('AdwDrawBasicRoundFrame')
                120 LOAD_NAME                4 (AdwDrawBasicFrame)
                122 PRECALL                  3
                126 CALL                     3
                136 STORE_NAME               7 (AdwDrawBasicRoundFrame)
    
-   150         138 PUSH_NULL
+   154         138 PUSH_NULL
                140 LOAD_BUILD_CLASS
-               142 LOAD_CONST              11 (<code object AdwDrawRoundFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 150>)
+               142 LOAD_CONST              11 (<code object AdwDrawRoundFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 154>)
                144 MAKE_FUNCTION            0
                146 LOAD_CONST              12 ('AdwDrawRoundFrame')
                148 LOAD_NAME                7 (AdwDrawBasicRoundFrame)
                150 PRECALL                  3
                154 CALL                     3
                164 STORE_NAME               8 (AdwDrawRoundFrame)
    
-   155         166 PUSH_NULL
+   159         166 PUSH_NULL
                168 LOAD_BUILD_CLASS
-               170 LOAD_CONST              13 (<code object AdwDrawDarkRoundFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 155>)
+               170 LOAD_CONST              13 (<code object AdwDrawDarkRoundFrame, file "D:\tkadw\tkadw\canvas\frame.py", line 159>)
                172 MAKE_FUNCTION            0
                174 LOAD_CONST              14 ('AdwDrawDarkRoundFrame')
                176 LOAD_NAME                7 (AdwDrawBasicRoundFrame)
                178 PRECALL                  3
                182 CALL                     3
                192 STORE_NAME               9 (AdwDrawDarkRoundFrame)
    
-   160         194 PUSH_NULL
+   164         194 PUSH_NULL
                196 LOAD_BUILD_CLASS
-               198 LOAD_CONST              15 (<code object AdwDrawBasicRoundFrame3, file "D:\tkadw\tkadw\canvas\frame.py", line 160>)
+               198 LOAD_CONST              15 (<code object AdwDrawBasicRoundFrame3, file "D:\tkadw\tkadw\canvas\frame.py", line 164>)
                200 MAKE_FUNCTION            0
                202 LOAD_CONST              16 ('AdwDrawBasicRoundFrame3')
                204 LOAD_NAME                7 (AdwDrawBasicRoundFrame)
                206 PRECALL                  3
                210 CALL                     3
                220 STORE_NAME              10 (AdwDrawBasicRoundFrame3)
    
-   193         222 PUSH_NULL
+   199         222 PUSH_NULL
                224 LOAD_BUILD_CLASS
-               226 LOAD_CONST              17 (<code object AdwDrawRoundFrame3, file "D:\tkadw\tkadw\canvas\frame.py", line 193>)
+               226 LOAD_CONST              17 (<code object AdwDrawRoundFrame3, file "D:\tkadw\tkadw\canvas\frame.py", line 199>)
                228 MAKE_FUNCTION            0
                230 LOAD_CONST              18 ('AdwDrawRoundFrame3')
                232 LOAD_NAME               10 (AdwDrawBasicRoundFrame3)
                234 PRECALL                  3
                238 CALL                     3
                248 STORE_NAME              11 (AdwDrawRoundFrame3)
    
-   198         250 PUSH_NULL
+   204         250 PUSH_NULL
                252 LOAD_BUILD_CLASS
-               254 LOAD_CONST              19 (<code object AdwDrawDarkRoundFrame3, file "D:\tkadw\tkadw\canvas\frame.py", line 198>)
+               254 LOAD_CONST              19 (<code object AdwDrawDarkRoundFrame3, file "D:\tkadw\tkadw\canvas\frame.py", line 204>)
                256 MAKE_FUNCTION            0
                258 LOAD_CONST              20 ('AdwDrawDarkRoundFrame3')
                260 LOAD_NAME               10 (AdwDrawBasicRoundFrame3)
                262 PRECALL                  3
                266 CALL                     3
                276 STORE_NAME              12 (AdwDrawDarkRoundFrame3)
    
-   203         278 LOAD_NAME               13 (__name__)
+   209         278 LOAD_NAME               13 (__name__)
                280 LOAD_CONST              21 ('__main__')
                282 COMPARE_OP               2 (==)
                288 EXTENDED_ARG             1
                290 POP_JUMP_FORWARD_IF_FALSE   260 (to 812)
    
-   204         292 LOAD_CONST               0 (0)
+   210         292 LOAD_CONST               0 (0)
                294 LOAD_CONST              22 (('Tk',))
                296 IMPORT_NAME              2 (tkinter)
                298 IMPORT_FROM             14 (Tk)
                300 STORE_NAME              14 (Tk)
                302 POP_TOP
    
-   205         304 PUSH_NULL
+   211         304 PUSH_NULL
                306 LOAD_NAME               14 (Tk)
                308 PRECALL                  0
                312 CALL                     0
                322 STORE_NAME              15 (root)
    
-   207         324 PUSH_NULL
+   213         324 PUSH_NULL
                326 LOAD_NAME                6 (AdwDrawDarkFrame)
                328 PRECALL                  0
                332 CALL                     0
                342 STORE_NAME              16 (frame)
    
-   208         344 LOAD_NAME               16 (frame)
+   214         344 LOAD_NAME               16 (frame)
                346 LOAD_METHOD             17 (pack)
                368 LOAD_CONST              23 ('both')
                370 LOAD_CONST              24 ('yes')
                372 KW_NAMES                25
                374 PRECALL                  2
                378 CALL                     2
                388 POP_TOP
    
-   210         390 PUSH_NULL
+   216         390 PUSH_NULL
                392 LOAD_NAME                6 (AdwDrawDarkFrame)
                394 LOAD_NAME               16 (frame)
                396 LOAD_ATTR               16 (frame)
                406 PRECALL                  1
                410 CALL                     1
                420 STORE_NAME              18 (frame2)
    
-   211         422 LOAD_NAME               18 (frame2)
+   217         422 LOAD_NAME               18 (frame2)
                424 LOAD_METHOD             17 (pack)
                446 LOAD_CONST              23 ('both')
                448 LOAD_CONST              24 ('yes')
                450 LOAD_CONST              26 (8)
                452 LOAD_CONST              26 (8)
                454 KW_NAMES                27
                456 PRECALL                  4
                460 CALL                     4
                470 POP_TOP
    
-   213         472 PUSH_NULL
+   219         472 PUSH_NULL
                474 LOAD_NAME                9 (AdwDrawDarkRoundFrame)
                476 PRECALL                  0
                480 CALL                     0
                490 STORE_NAME              19 (frame3)
    
-   214         492 LOAD_NAME               19 (frame3)
+   220         492 LOAD_NAME               19 (frame3)
                494 LOAD_METHOD             17 (pack)
                516 LOAD_CONST              23 ('both')
                518 LOAD_CONST              24 ('yes')
                520 KW_NAMES                25
                522 PRECALL                  2
                526 CALL                     2
                536 POP_TOP
    
-   216         538 PUSH_NULL
+   222         538 PUSH_NULL
                540 LOAD_NAME                9 (AdwDrawDarkRoundFrame)
                542 LOAD_NAME               19 (frame3)
                544 LOAD_ATTR               16 (frame)
                554 PRECALL                  1
                558 CALL                     1
                568 STORE_NAME              20 (frame4)
    
-   217         570 LOAD_NAME               20 (frame4)
+   223         570 LOAD_NAME               20 (frame4)
                572 LOAD_METHOD             17 (pack)
                594 LOAD_CONST              23 ('both')
                596 LOAD_CONST              24 ('yes')
                598 LOAD_CONST              26 (8)
                600 LOAD_CONST              26 (8)
                602 KW_NAMES                27
                604 PRECALL                  4
                608 CALL                     4
                618 POP_TOP
    
-   219         620 PUSH_NULL
+   225         620 PUSH_NULL
                622 LOAD_NAME               12 (AdwDrawDarkRoundFrame3)
                624 PRECALL                  0
                628 CALL                     0
                638 STORE_NAME              21 (frame5)
    
-   220         640 LOAD_NAME               21 (frame5)
+   226         640 LOAD_NAME               21 (frame5)
                642 LOAD_METHOD             17 (pack)
                664 LOAD_CONST              23 ('both')
                666 LOAD_CONST              24 ('yes')
                668 KW_NAMES                25
                670 PRECALL                  2
                674 CALL                     2
                684 POP_TOP
    
-   222         686 PUSH_NULL
+   228         686 PUSH_NULL
                688 LOAD_NAME               12 (AdwDrawDarkRoundFrame3)
                690 LOAD_NAME               21 (frame5)
                692 LOAD_ATTR               16 (frame)
                702 PRECALL                  1
                706 CALL                     1
                716 STORE_NAME              22 (frame6)
    
-   223         718 LOAD_NAME               22 (frame6)
+   229         718 LOAD_NAME               22 (frame6)
                720 LOAD_METHOD             17 (pack)
                742 LOAD_CONST              23 ('both')
                744 LOAD_CONST              24 ('yes')
                746 LOAD_CONST              26 (8)
                748 LOAD_CONST              26 (8)
                750 KW_NAMES                27
                752 PRECALL                  4
                756 CALL                     4
                766 POP_TOP
    
-   225         768 LOAD_NAME               15 (root)
+   231         768 LOAD_NAME               15 (root)
                770 LOAD_METHOD             23 (mainloop)
                792 PRECALL                  0
                796 CALL                     0
                806 POP_TOP
                808 LOAD_CONST              28 (None)
                810 RETURN_VALUE
    
-   203     >>  812 LOAD_CONST              28 (None)
+   209     >>  812 LOAD_CONST              28 (None)
                814 RETURN_VALUE
    consts
       0
       ('AdwDrawEngine',)
       ('Frame',)
       code
          argcount  : 0
@@ -307,28 +307,28 @@
                       32 MAKE_FUNCTION            0
                       34 STORE_NAME               4 (_other)
          
           23          36 LOAD_CONST               5 (<code object _draw, file "D:\tkadw\tkadw\canvas\frame.py", line 23>)
                       38 MAKE_FUNCTION            0
                       40 STORE_NAME               5 (_draw)
          
-          40          42 LOAD_CONST               6 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 40>)
+          42          42 LOAD_CONST               6 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 42>)
                       44 MAKE_FUNCTION            0
                       46 STORE_NAME               6 (default_palette)
          
-          43          48 LOAD_CONST               7 (<code object palette_light, file "D:\tkadw\tkadw\canvas\frame.py", line 43>)
+          45          48 LOAD_CONST               7 (<code object palette_light, file "D:\tkadw\tkadw\canvas\frame.py", line 45>)
                       50 MAKE_FUNCTION            0
                       52 STORE_NAME               7 (palette_light)
          
-          54          54 LOAD_CONST               8 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\frame.py", line 54>)
+          56          54 LOAD_CONST               8 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\frame.py", line 56>)
                       56 MAKE_FUNCTION            0
                       58 STORE_NAME               8 (palette_dark)
          
-          65          60 LOAD_CONST              11 ((None,))
-                      62 LOAD_CONST              10 (<code object palette, file "D:\tkadw\tkadw\canvas\frame.py", line 65>)
+          67          60 LOAD_CONST              11 ((None,))
+                      62 LOAD_CONST              10 (<code object palette, file "D:\tkadw\tkadw\canvas\frame.py", line 67>)
                       64 MAKE_FUNCTION            1 (defaults)
                       66 STORE_NAME               9 (palette)
                       68 LOAD_CLOSURE             0 (__class__)
                       70 COPY                     1
                       72 STORE_NAME              10 (__classcell__)
                       74 RETURN_VALUE
          consts
@@ -475,73 +475,73 @@
                 24           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-                26          44 LOAD_FAST                0 (self)
+                27          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_rectangle)
                
-                27          68 LOAD_CONST               2 (0)
+                28          68 LOAD_CONST               2 (0)
                             70 LOAD_CONST               2 (0)
                             72 LOAD_FAST                0 (self)
                             74 LOAD_METHOD              2 (winfo_width)
                             96 PRECALL                  0
                            100 CALL                     0
                            110 LOAD_FAST                0 (self)
                            112 LOAD_METHOD              3 (winfo_height)
                            134 PRECALL                  0
                            138 CALL                     0
                
-                28         148 LOAD_FAST                0 (self)
+                29         148 LOAD_FAST                0 (self)
                            150 LOAD_ATTR                4 (frame_border_width)
                
-                29         160 LOAD_FAST                0 (self)
+                30         160 LOAD_FAST                0 (self)
                            162 LOAD_ATTR                5 (frame_border)
                            172 LOAD_FAST                0 (self)
                            174 LOAD_ATTR                6 (frame_back)
                
-                26         184 KW_NAMES                 3
+                27         184 KW_NAMES                 3
                            186 PRECALL                  7
                            190 CALL                     7
                            200 LOAD_FAST                0 (self)
                            202 STORE_ATTR               7 (frame_frame)
                
-                32         212 LOAD_FAST                0 (self)
+                33         212 LOAD_FAST                0 (self)
                            214 LOAD_ATTR                8 (frame)
                            224 LOAD_METHOD              9 (configure)
                            246 LOAD_FAST                0 (self)
                            248 LOAD_ATTR                6 (frame_back)
                            258 LOAD_CONST               2 (0)
                            260 KW_NAMES                 4
                            262 PRECALL                  2
                            266 CALL                     2
                            276 POP_TOP
                
-                34         278 LOAD_FAST                0 (self)
+                36         278 LOAD_FAST                0 (self)
                            280 LOAD_METHOD             10 (create_window)
                
-                35         302 LOAD_FAST                0 (self)
+                37         302 LOAD_FAST                0 (self)
                            304 LOAD_METHOD              2 (winfo_width)
                            326 PRECALL                  0
                            330 CALL                     0
                            340 LOAD_CONST               5 (2)
                            342 BINARY_OP               11 (/)
                            346 LOAD_FAST                0 (self)
                            348 LOAD_METHOD              3 (winfo_height)
                            370 PRECALL                  0
                            374 CALL                     0
                            384 LOAD_CONST               5 (2)
                            386 BINARY_OP               11 (/)
                
-                36         390 LOAD_FAST                0 (self)
+                38         390 LOAD_FAST                0 (self)
                            392 LOAD_ATTR                8 (frame)
                
-                37         402 LOAD_FAST                0 (self)
+                39         402 LOAD_FAST                0 (self)
                            404 LOAD_METHOD              2 (winfo_width)
                            426 PRECALL                  0
                            430 CALL                     0
                            440 LOAD_CONST               6 (6)
                            442 BINARY_OP               10 (-)
                            446 LOAD_FAST                0 (self)
                            448 LOAD_ATTR                4 (frame_border_width)
@@ -552,15 +552,15 @@
                            490 CALL                     0
                            500 LOAD_CONST               6 (6)
                            502 BINARY_OP               10 (-)
                            506 LOAD_FAST                0 (self)
                            508 LOAD_ATTR                4 (frame_border_width)
                            518 BINARY_OP               10 (-)
                
-                34         522 KW_NAMES                 7
+                36         522 KW_NAMES                 7
                            524 PRECALL                  5
                            528 CALL                     5
                            538 LOAD_FAST                0 (self)
                            540 STORE_ATTR              11 (frame_f)
                            550 LOAD_CONST               0 (None)
                            552 RETURN_VALUE
                consts
@@ -575,70 +575,70 @@
                names      ('delete', 'create_rectangle', 'winfo_width', 'winfo_height', 'frame_border_width', 'frame_border', 'frame_back', 'frame_frame', 'frame', 'configure', 'create_window', 'frame_f')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       '_draw'
                firstlineno 23
-               lnotab 0x02012a02180150010c0118fd1c064202180158010c0178fd
+               lnotab 0x02012a03180150010c0118fd1c064203180158010c0178fd
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-                40           0 RESUME                   0
+                42           0 RESUME                   0
                
-                41           2 LOAD_FAST                0 (self)
+                43           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'default_palette'
-               firstlineno 40
+               firstlineno 42
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 7
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   026403640464059c036901a6010000ab0100000000000000000100640053
                   00
-                43           0 RESUME                   0
+                45           0 RESUME                   0
                
-                44           2 LOAD_FAST                0 (self)
+                46           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-                46          26 LOAD_CONST               1 ('frame')
+                48          26 LOAD_CONST               1 ('frame')
                
-                47          28 LOAD_CONST               2 ('#ffffff')
+                49          28 LOAD_CONST               2 ('#ffffff')
                
-                48          30 LOAD_CONST               3 ('#eaeaea')
+                50          30 LOAD_CONST               3 ('#eaeaea')
                
-                49          32 LOAD_CONST               4 (2)
+                51          32 LOAD_CONST               4 (2)
                
-                46          34 LOAD_CONST               5 (('back', 'border', 'border_width'))
+                48          34 LOAD_CONST               5 (('back', 'border', 'border_width'))
                             36 BUILD_CONST_KEY_MAP      3
                
-                45          38 BUILD_MAP                1
+                47          38 BUILD_MAP                1
                
-                44          40 PRECALL                  1
+                46          40 PRECALL                  1
                             44 CALL                     1
                             54 POP_TOP
                             56 LOAD_CONST               0 (None)
                             58 RETURN_VALUE
                consts
                   None
                   'frame'
@@ -648,44 +648,44 @@
                   ('back', 'border', 'border_width')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'palette_light'
-               firstlineno 43
+               firstlineno 45
                lnotab 0x0201180202010201020102fd04ff02ff
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 7
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   026403640464059c036901a6010000ab0100000000000000000100640053
                   00
-                54           0 RESUME                   0
+                56           0 RESUME                   0
                
-                55           2 LOAD_FAST                0 (self)
+                57           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-                57          26 LOAD_CONST               1 ('frame')
+                59          26 LOAD_CONST               1 ('frame')
                
-                58          28 LOAD_CONST               2 ('#0f0f0f')
+                60          28 LOAD_CONST               2 ('#0f0f0f')
                
-                59          30 LOAD_CONST               3 ('#333333')
+                61          30 LOAD_CONST               3 ('#333333')
                
-                60          32 LOAD_CONST               4 (2)
+                62          32 LOAD_CONST               4 (2)
                
-                57          34 LOAD_CONST               5 (('back', 'border', 'border_width'))
+                59          34 LOAD_CONST               5 (('back', 'border', 'border_width'))
                             36 BUILD_CONST_KEY_MAP      3
                
-                56          38 BUILD_MAP                1
+                58          38 BUILD_MAP                1
                
-                55          40 PRECALL                  1
+                57          40 PRECALL                  1
                             44 CALL                     1
                             54 POP_TOP
                             56 LOAD_CONST               0 (None)
                             58 RETURN_VALUE
                consts
                   None
                   'frame'
@@ -695,15 +695,15 @@
                   ('back', 'border', 'border_width')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'palette_dark'
-               firstlineno 54
+               firstlineno 56
                lnotab 0x0201180202010201020102fd04ff02ff
             None
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 4
                flags     : 3
@@ -712,79 +712,79 @@
                   02190000000000000000007c005f0000000000000000007c016401190000
                   000000000000006403190000000000000000007c005f0100000000000000
                   007c016401190000000000000000006404190000000000000000007c005f
                   0200000000000000007c017c005f03000000000000000009007c00a00400
                   000000000000000000000000000000000000006400a6010000ab01000000
                   00000000000100640053002300740a000000000000000000002400720401
                   0059006400530077007803590077017c006a0300000000000000005300
-                65           0 RESUME                   0
+                67           0 RESUME                   0
                
-                66           2 LOAD_FAST                1 (dict)
+                68           2 LOAD_FAST                1 (dict)
                              4 POP_JUMP_FORWARD_IF_NONE   109 (to 224)
                
-                67           6 LOAD_CONST               1 ('frame')
+                69           6 LOAD_CONST               1 ('frame')
                              8 LOAD_FAST                1 (dict)
                             10 CONTAINS_OP              0
                             12 POP_JUMP_FORWARD_IF_FALSE    57 (to 128)
                
-                68          14 LOAD_FAST                1 (dict)
+                70          14 LOAD_FAST                1 (dict)
                             16 LOAD_CONST               1 ('frame')
                             18 BINARY_SUBSCR
                             28 LOAD_CONST               2 ('back')
                             30 BINARY_SUBSCR
                             40 LOAD_FAST                0 (self)
                             42 STORE_ATTR               0 (frame_back)
                
-                69          52 LOAD_FAST                1 (dict)
+                71          52 LOAD_FAST                1 (dict)
                             54 LOAD_CONST               1 ('frame')
                             56 BINARY_SUBSCR
                             66 LOAD_CONST               3 ('border')
                             68 BINARY_SUBSCR
                             78 LOAD_FAST                0 (self)
                             80 STORE_ATTR               1 (frame_border)
                
-                70          90 LOAD_FAST                1 (dict)
+                72          90 LOAD_FAST                1 (dict)
                             92 LOAD_CONST               1 ('frame')
                             94 BINARY_SUBSCR
                            104 LOAD_CONST               4 ('border_width')
                            106 BINARY_SUBSCR
                            116 LOAD_FAST                0 (self)
                            118 STORE_ATTR               2 (frame_border_width)
                
-                72     >>  128 LOAD_FAST                1 (dict)
+                74     >>  128 LOAD_FAST                1 (dict)
                            130 LOAD_FAST                0 (self)
                            132 STORE_ATTR               3 (_palette)
                
-                74         142 NOP
+                76         142 NOP
                
-                75         144 LOAD_FAST                0 (self)
+                77         144 LOAD_FAST                0 (self)
                            146 LOAD_METHOD              4 (_draw)
                            168 LOAD_CONST               0 (None)
                            170 PRECALL                  1
                            174 CALL                     1
                            184 POP_TOP
                            186 LOAD_CONST               0 (None)
                            188 RETURN_VALUE
                        >>  190 PUSH_EXC_INFO
                
-                76         192 LOAD_GLOBAL             10 (AttributeError)
+                78         192 LOAD_GLOBAL             10 (AttributeError)
                            204 CHECK_EXC_MATCH
                            206 POP_JUMP_FORWARD_IF_FALSE     4 (to 216)
                            208 POP_TOP
                
-                77         210 POP_EXCEPT
+                79         210 POP_EXCEPT
                            212 LOAD_CONST               0 (None)
                            214 RETURN_VALUE
                
-                76     >>  216 RERAISE                  0
+                78     >>  216 RERAISE                  0
                        >>  218 COPY                     3
                            220 POP_EXCEPT
                            222 RERAISE                  1
                
-                79     >>  224 LOAD_FAST                0 (self)
+                81     >>  224 LOAD_FAST                0 (self)
                            226 LOAD_ATTR                3 (_palette)
                            236 RETURN_VALUE
                ExceptionTable:
                  144 to 184 -> 190 [0]
                  190 to 208 -> 218 [1] lasti
                  216 to 216 -> 218 [1] lasti
                consts
@@ -795,181 +795,181 @@
                   'border_width'
                names      ('frame_back', 'frame_border', 'frame_border_width', '_palette', '_draw', 'AttributeError')
                varnames   ('self', 'dict')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'palette'
-               firstlineno 65
+               firstlineno 67
                lnotab 0x0201040108012601260126020e0202013001120106ff0803
             (None,)
          names      ('__name__', '__module__', '__qualname__', '__init__', '_other', '_draw', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
          name       'AdwDrawBasicFrame'
          firstlineno 6
-         lnotab 0x0c01120d060306110603060b060b
+         lnotab 0x0c01120d060306130603060b060b
       'AdwDrawBasicFrame'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-          82           0 RESUME                   0
+          84           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawFrame')
                        8 STORE_NAME               2 (__qualname__)
          
-          83          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 83>)
+          85          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 85>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawFrame'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-                83           0 RESUME                   0
+                85           0 RESUME                   0
                
-                84           2 LOAD_FAST                0 (self)
+                86           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'default_palette'
-               firstlineno 83
+               firstlineno 85
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
          name       'AdwDrawFrame'
-         firstlineno 82
+         firstlineno 84
          lnotab 0x0a01
       'AdwDrawFrame'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-          87           0 RESUME                   0
+          89           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawDarkFrame')
                        8 STORE_NAME               2 (__qualname__)
          
-          88          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 88>)
+          90          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 90>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawDarkFrame'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-                88           0 RESUME                   0
+                90           0 RESUME                   0
                
-                89           2 LOAD_FAST                0 (self)
+                91           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'default_palette'
-               firstlineno 88
+               firstlineno 90
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
          name       'AdwDrawDarkFrame'
-         firstlineno 87
+         firstlineno 89
          lnotab 0x0a01
       'AdwDrawDarkFrame'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 3
          flags     : 0
          code
             0x8700970065005a0164005a0288006601640184085a03640284005a0464
             0384005a05640484005a06640584005a07640888006601640784095a0888
             0078015a095300
                        0 MAKE_CELL                0 (__class__)
          
-          92           2 RESUME                   0
+          94           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawBasicRoundFrame')
                       10 STORE_NAME               2 (__qualname__)
          
-          93          12 LOAD_CLOSURE             0 (__class__)
+          95          12 LOAD_CLOSURE             0 (__class__)
                       14 BUILD_TUPLE              1
-                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\frame.py", line 93>)
+                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\frame.py", line 95>)
                       18 MAKE_FUNCTION            8 (closure)
                       20 STORE_NAME               3 (__init__)
          
-         100          22 LOAD_CONST               2 (<code object _draw, file "D:\tkadw\tkadw\canvas\frame.py", line 100>)
+         102          22 LOAD_CONST               2 (<code object _draw, file "D:\tkadw\tkadw\canvas\frame.py", line 102>)
                       24 MAKE_FUNCTION            0
                       26 STORE_NAME               4 (_draw)
          
-         117          28 LOAD_CONST               3 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 117>)
+         121          28 LOAD_CONST               3 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 121>)
                       30 MAKE_FUNCTION            0
                       32 STORE_NAME               5 (default_palette)
          
-         120          34 LOAD_CONST               4 (<code object palette_light, file "D:\tkadw\tkadw\canvas\frame.py", line 120>)
+         124          34 LOAD_CONST               4 (<code object palette_light, file "D:\tkadw\tkadw\canvas\frame.py", line 124>)
                       36 MAKE_FUNCTION            0
                       38 STORE_NAME               6 (palette_light)
          
-         132          40 LOAD_CONST               5 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\frame.py", line 132>)
+         136          40 LOAD_CONST               5 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\frame.py", line 136>)
                       42 MAKE_FUNCTION            0
                       44 STORE_NAME               7 (palette_dark)
          
-         144          46 LOAD_CONST               8 ((None,))
+         148          46 LOAD_CONST               8 ((None,))
                       48 LOAD_CLOSURE             0 (__class__)
                       50 BUILD_TUPLE              1
-                      52 LOAD_CONST               7 (<code object palette, file "D:\tkadw\tkadw\canvas\frame.py", line 144>)
+                      52 LOAD_CONST               7 (<code object palette, file "D:\tkadw\tkadw\canvas\frame.py", line 148>)
                       54 MAKE_FUNCTION            9 (defaults, closure)
                       56 STORE_NAME               8 (palette)
                       58 LOAD_CLOSURE             0 (__class__)
                       60 COPY                     1
                       62 STORE_NAME               9 (__classcell__)
                       64 RETURN_VALUE
          consts
@@ -984,31 +984,31 @@
                   0000006a0100000000000000007c0169007c02a4018e01010009007c00a0
                   0200000000000000000000000000000000000000007c006a030000000000
                   000000a00400000000000000000000000000000000000000006401a60100
                   00ab010000000000000000ac02a6010000ab010000000000000000010064
                   00530023000100590064005300780359007701
                              0 COPY_FREE_VARS           1
                
-                93           2 RESUME                   0
+                95           2 RESUME                   0
                
-                94           4 PUSH_NULL
+                96           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                1 (args)
                             44 BUILD_MAP                0
                             46 LOAD_FAST                2 (kwargs)
                             48 DICT_MERGE               1
                             50 CALL_FUNCTION_EX         1
                             52 POP_TOP
                
-                95          54 NOP
+                97          54 NOP
                
-                96          56 LOAD_FAST                0 (self)
+                98          56 LOAD_FAST                0 (self)
                             58 LOAD_METHOD              2 (configure)
                             80 LOAD_FAST                0 (self)
                             82 LOAD_ATTR                3 (master)
                             92 LOAD_METHOD              4 (cget)
                            114 LOAD_CONST               1 ('background')
                            116 PRECALL                  1
                            120 CALL                     1
@@ -1016,17 +1016,17 @@
                            132 PRECALL                  1
                            136 CALL                     1
                            146 POP_TOP
                            148 LOAD_CONST               0 (None)
                            150 RETURN_VALUE
                        >>  152 PUSH_EXC_INFO
                
-                97         154 POP_TOP
+                99         154 POP_TOP
                
-                98         156 POP_EXCEPT
+               100         156 POP_EXCEPT
                            158 LOAD_CONST               0 (None)
                            160 RETURN_VALUE
                        >>  162 COPY                     3
                            164 POP_EXCEPT
                            166 RERAISE                  1
                ExceptionTable:
                  56 to 146 -> 152 [0]
@@ -1037,15 +1037,15 @@
                   ('background',)
                names      ('super', '__init__', 'configure', 'master', 'cget')
                varnames   ('self', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       '__init__'
-               firstlineno 93
+               firstlineno 95
                lnotab 0x04013201020162010201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 10
                flags     : 3
                code
@@ -1064,84 +1064,84 @@
                   00a0030000000000000000000000000000000000000000a6000000ab0000
                   0000000000000064057a0b00007c006a0900000000000000007c00a00200
                   00000000000000000000000000000000000000a6000000ab000000000000
                   00000064067a0a00007c006a0500000000000000007a0a00007c00a00300
                   00000000000000000000000000000000000000a6000000ab000000000000
                   00000064067a0a00007c006a0500000000000000007a0a0000ac07a60500
                   00ab0500000000000000007c005f0c000000000000000064005300
-               100           0 RESUME                   0
+               102           0 RESUME                   0
                
-               101           2 LOAD_FAST                0 (self)
+               103           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               103          44 LOAD_FAST                0 (self)
+               106          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_round_rect2)
                
-               104          68 LOAD_CONST               2 (0)
+               107          68 LOAD_CONST               2 (0)
                             70 LOAD_CONST               2 (0)
                             72 LOAD_FAST                0 (self)
                             74 LOAD_METHOD              2 (winfo_width)
                             96 PRECALL                  0
                            100 CALL                     0
                            110 LOAD_FAST                0 (self)
                            112 LOAD_METHOD              3 (winfo_height)
                            134 PRECALL                  0
                            138 CALL                     0
                            148 LOAD_FAST                0 (self)
                            150 LOAD_ATTR                4 (frame_radius)
                
-               105         160 LOAD_FAST                0 (self)
+               108         160 LOAD_FAST                0 (self)
                            162 LOAD_ATTR                5 (frame_border_width)
                
-               106         172 LOAD_FAST                0 (self)
+               109         172 LOAD_FAST                0 (self)
                            174 LOAD_ATTR                6 (frame_border)
                            184 LOAD_FAST                0 (self)
                            186 LOAD_ATTR                7 (frame_back)
                
-               103         196 KW_NAMES                 3
+               106         196 KW_NAMES                 3
                            198 PRECALL                  8
                            202 CALL                     8
                            212 LOAD_FAST                0 (self)
                            214 STORE_ATTR               8 (frame_frame)
                
-               109         224 LOAD_FAST                0 (self)
+               112         224 LOAD_FAST                0 (self)
                            226 LOAD_ATTR                9 (frame)
                            236 LOAD_METHOD             10 (configure)
                            258 LOAD_FAST                0 (self)
                            260 LOAD_ATTR                7 (frame_back)
                            270 LOAD_CONST               2 (0)
                            272 KW_NAMES                 4
                            274 PRECALL                  2
                            278 CALL                     2
                            288 POP_TOP
                
-               111         290 LOAD_FAST                0 (self)
+               115         290 LOAD_FAST                0 (self)
                            292 LOAD_METHOD             11 (create_window)
                
-               112         314 LOAD_FAST                0 (self)
+               116         314 LOAD_FAST                0 (self)
                            316 LOAD_METHOD              2 (winfo_width)
                            338 PRECALL                  0
                            342 CALL                     0
                            352 LOAD_CONST               5 (2)
                            354 BINARY_OP               11 (/)
                            358 LOAD_FAST                0 (self)
                            360 LOAD_METHOD              3 (winfo_height)
                            382 PRECALL                  0
                            386 CALL                     0
                            396 LOAD_CONST               5 (2)
                            398 BINARY_OP               11 (/)
                
-               113         402 LOAD_FAST                0 (self)
+               117         402 LOAD_FAST                0 (self)
                            404 LOAD_ATTR                9 (frame)
                
-               114         414 LOAD_FAST                0 (self)
+               118         414 LOAD_FAST                0 (self)
                            416 LOAD_METHOD              2 (winfo_width)
                            438 PRECALL                  0
                            442 CALL                     0
                            452 LOAD_CONST               6 (6)
                            454 BINARY_OP               10 (-)
                            458 LOAD_FAST                0 (self)
                            460 LOAD_ATTR                5 (frame_border_width)
@@ -1152,15 +1152,15 @@
                            502 CALL                     0
                            512 LOAD_CONST               6 (6)
                            514 BINARY_OP               10 (-)
                            518 LOAD_FAST                0 (self)
                            520 LOAD_ATTR                5 (frame_border_width)
                            530 BINARY_OP               10 (-)
                
-               111         534 KW_NAMES                 7
+               115         534 KW_NAMES                 7
                            536 PRECALL                  5
                            540 CALL                     5
                            550 LOAD_FAST                0 (self)
                            552 STORE_ATTR              12 (frame_f)
                            562 LOAD_CONST               0 (None)
                            564 RETURN_VALUE
                consts
@@ -1174,73 +1174,73 @@
                   ('window', 'width', 'height')
                names      ('delete', 'create_round_rect2', 'winfo_width', 'winfo_height', 'frame_radius', 'frame_border_width', 'frame_border', 'frame_back', 'frame_frame', 'frame', 'configure', 'create_window', 'frame_f')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       '_draw'
-               firstlineno 100
-               lnotab 0x02012a0218015c010c0118fd1c064202180158010c0178fd
+               firstlineno 102
+               lnotab 0x02012a0318015c010c0118fd1c064203180158010c0178fd
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               117           0 RESUME                   0
+               121           0 RESUME                   0
                
-               118           2 LOAD_FAST                0 (self)
+               122           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'default_palette'
-               firstlineno 117
+               firstlineno 121
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 8
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   0264036404640564069c046901a6010000ab010000000000000000010064
                   005300
-               120           0 RESUME                   0
+               124           0 RESUME                   0
                
-               121           2 LOAD_FAST                0 (self)
+               125           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               123          26 LOAD_CONST               1 ('frame')
+               127          26 LOAD_CONST               1 ('frame')
                
-               124          28 LOAD_CONST               2 (6)
+               128          28 LOAD_CONST               2 (6)
                
-               125          30 LOAD_CONST               3 ('#0f0f0f')
+               129          30 LOAD_CONST               3 ('#0f0f0f')
                
-               126          32 LOAD_CONST               4 ('#333333')
+               130          32 LOAD_CONST               4 ('#333333')
                
-               127          34 LOAD_CONST               5 (2)
+               131          34 LOAD_CONST               5 (2)
                
-               123          36 LOAD_CONST               6 (('radius', 'back', 'border', 'border_width'))
+               127          36 LOAD_CONST               6 (('radius', 'back', 'border', 'border_width'))
                             38 BUILD_CONST_KEY_MAP      4
                
-               122          40 BUILD_MAP                1
+               126          40 BUILD_MAP                1
                
-               121          42 PRECALL                  1
+               125          42 PRECALL                  1
                             46 CALL                     1
                             56 POP_TOP
                             58 LOAD_CONST               0 (None)
                             60 RETURN_VALUE
                consts
                   None
                   'frame'
@@ -1251,46 +1251,46 @@
                   ('radius', 'back', 'border', 'border_width')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'palette_light'
-               firstlineno 120
+               firstlineno 124
                lnotab 0x02011802020102010201020102fc04ff02ff
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 8
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   0264036404640564069c046901a6010000ab010000000000000000010064
                   005300
-               132           0 RESUME                   0
+               136           0 RESUME                   0
                
-               133           2 LOAD_FAST                0 (self)
+               137           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               135          26 LOAD_CONST               1 ('frame')
+               139          26 LOAD_CONST               1 ('frame')
                
-               136          28 LOAD_CONST               2 (6)
+               140          28 LOAD_CONST               2 (6)
                
-               137          30 LOAD_CONST               3 ('#0f0f0f')
+               141          30 LOAD_CONST               3 ('#0f0f0f')
                
-               138          32 LOAD_CONST               4 ('#333333')
+               142          32 LOAD_CONST               4 ('#333333')
                
-               139          34 LOAD_CONST               5 (2)
+               143          34 LOAD_CONST               5 (2)
                
-               135          36 LOAD_CONST               6 (('radius', 'back', 'border', 'border_width'))
+               139          36 LOAD_CONST               6 (('radius', 'back', 'border', 'border_width'))
                             38 BUILD_CONST_KEY_MAP      4
                
-               134          40 BUILD_MAP                1
+               138          40 BUILD_MAP                1
                
-               133          42 PRECALL                  1
+               137          42 PRECALL                  1
                             46 CALL                     1
                             56 POP_TOP
                             58 LOAD_CONST               0 (None)
                             60 RETURN_VALUE
                consts
                   None
                   'frame'
@@ -1301,15 +1301,15 @@
                   ('radius', 'back', 'border', 'border_width')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'palette_dark'
-               firstlineno 132
+               firstlineno 136
                lnotab 0x02011802020102010201020102fc04ff02ff
             None
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
@@ -1317,203 +1317,203 @@
                   0x95019700740100000000000000000000a6000000ab0000000000000000
                   00a00100000000000000000000000000000000000000007c01a6010000ab
                   010000000000000000010064017c01760072157c01640119000000000000
                   0000006402190000000000000000007c005f020000000000000000640053
                   0064005300
                              0 COPY_FREE_VARS           1
                
-               144           2 RESUME                   0
+               148           2 RESUME                   0
                
-               145           4 LOAD_GLOBAL              1 (NULL + super)
+               149           4 LOAD_GLOBAL              1 (NULL + super)
                             16 PRECALL                  0
                             20 CALL                     0
                             30 LOAD_METHOD              1 (palette)
                             52 LOAD_FAST                1 (dict)
                             54 PRECALL                  1
                             58 CALL                     1
                             68 POP_TOP
                
-               146          70 LOAD_CONST               1 ('frame')
+               150          70 LOAD_CONST               1 ('frame')
                             72 LOAD_FAST                1 (dict)
                             74 CONTAINS_OP              0
                             76 POP_JUMP_FORWARD_IF_FALSE    21 (to 120)
                
-               147          78 LOAD_FAST                1 (dict)
+               151          78 LOAD_FAST                1 (dict)
                             80 LOAD_CONST               1 ('frame')
                             82 BINARY_SUBSCR
                             92 LOAD_CONST               2 ('radius')
                             94 BINARY_SUBSCR
                            104 LOAD_FAST                0 (self)
                            106 STORE_ATTR               2 (frame_radius)
                            116 LOAD_CONST               0 (None)
                            118 RETURN_VALUE
                
-               146     >>  120 LOAD_CONST               0 (None)
+               150     >>  120 LOAD_CONST               0 (None)
                            122 RETURN_VALUE
                consts
                   None
                   'frame'
                   'radius'
                names      ('super', 'palette', 'frame_radius')
                varnames   ('self', 'dict')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'palette'
-               firstlineno 144
+               firstlineno 148
                lnotab 0x0401420108012aff
             (None,)
          names      ('__name__', '__module__', '__qualname__', '__init__', '_draw', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
          name       'AdwDrawBasicRoundFrame'
-         firstlineno 92
-         lnotab 0x0c010a0706110603060c060c
+         firstlineno 94
+         lnotab 0x0c010a0706130603060c060c
       'AdwDrawBasicRoundFrame'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         150           0 RESUME                   0
+         154           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundFrame')
                        8 STORE_NAME               2 (__qualname__)
          
-         151          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 151>)
+         155          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 155>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundFrame'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               151           0 RESUME                   0
+               155           0 RESUME                   0
                
-               152           2 LOAD_FAST                0 (self)
+               156           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'default_palette'
-               firstlineno 151
+               firstlineno 155
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
          name       'AdwDrawRoundFrame'
-         firstlineno 150
+         firstlineno 154
          lnotab 0x0a01
       'AdwDrawRoundFrame'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         155           0 RESUME                   0
+         159           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawDarkRoundFrame')
                        8 STORE_NAME               2 (__qualname__)
          
-         156          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 156>)
+         160          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 160>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawDarkRoundFrame'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               156           0 RESUME                   0
+               160           0 RESUME                   0
                
-               157           2 LOAD_FAST                0 (self)
+               161           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'default_palette'
-               firstlineno 156
+               firstlineno 160
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
          name       'AdwDrawDarkRoundFrame'
-         firstlineno 155
+         firstlineno 159
          lnotab 0x0a01
       'AdwDrawDarkRoundFrame'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 2
          flags     : 0
          code
             0x8700970065005a0164005a0288006601640184085a03640284005a0464
             0384005a05880078015a065300
                        0 MAKE_CELL                0 (__class__)
          
-         160           2 RESUME                   0
+         164           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawBasicRoundFrame3')
                       10 STORE_NAME               2 (__qualname__)
          
-         161          12 LOAD_CLOSURE             0 (__class__)
+         165          12 LOAD_CLOSURE             0 (__class__)
                       14 BUILD_TUPLE              1
-                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\frame.py", line 161>)
+                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\frame.py", line 165>)
                       18 MAKE_FUNCTION            8 (closure)
                       20 STORE_NAME               3 (__init__)
          
-         168          22 LOAD_CONST               2 (<code object _draw, file "D:\tkadw\tkadw\canvas\frame.py", line 168>)
+         172          22 LOAD_CONST               2 (<code object _draw, file "D:\tkadw\tkadw\canvas\frame.py", line 172>)
                       24 MAKE_FUNCTION            0
                       26 STORE_NAME               4 (_draw)
          
-         189          28 LOAD_CONST               3 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 189>)
+         195          28 LOAD_CONST               3 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 195>)
                       30 MAKE_FUNCTION            0
                       32 STORE_NAME               5 (default_palette)
                       34 LOAD_CLOSURE             0 (__class__)
                       36 COPY                     1
                       38 STORE_NAME               6 (__classcell__)
                       40 RETURN_VALUE
          consts
@@ -1528,31 +1528,31 @@
                   0000006a0100000000000000007c0169007c02a4018e01010009007c00a0
                   0200000000000000000000000000000000000000007c006a030000000000
                   000000a00400000000000000000000000000000000000000006401a60100
                   00ab010000000000000000ac02a6010000ab010000000000000000010064
                   00530023000100590064005300780359007701
                              0 COPY_FREE_VARS           1
                
-               161           2 RESUME                   0
+               165           2 RESUME                   0
                
-               162           4 PUSH_NULL
+               166           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                1 (args)
                             44 BUILD_MAP                0
                             46 LOAD_FAST                2 (kwargs)
                             48 DICT_MERGE               1
                             50 CALL_FUNCTION_EX         1
                             52 POP_TOP
                
-               163          54 NOP
+               167          54 NOP
                
-               164          56 LOAD_FAST                0 (self)
+               168          56 LOAD_FAST                0 (self)
                             58 LOAD_METHOD              2 (configure)
                             80 LOAD_FAST                0 (self)
                             82 LOAD_ATTR                3 (master)
                             92 LOAD_METHOD              4 (cget)
                            114 LOAD_CONST               1 ('background')
                            116 PRECALL                  1
                            120 CALL                     1
@@ -1560,17 +1560,17 @@
                            132 PRECALL                  1
                            136 CALL                     1
                            146 POP_TOP
                            148 LOAD_CONST               0 (None)
                            150 RETURN_VALUE
                        >>  152 PUSH_EXC_INFO
                
-               165         154 POP_TOP
+               169         154 POP_TOP
                
-               166         156 POP_EXCEPT
+               170         156 POP_EXCEPT
                            158 LOAD_CONST               0 (None)
                            160 RETURN_VALUE
                        >>  162 COPY                     3
                            164 POP_EXCEPT
                            166 RERAISE                  1
                ExceptionTable:
                  56 to 146 -> 152 [0]
@@ -1581,15 +1581,15 @@
                   ('background',)
                names      ('super', '__init__', 'configure', 'master', 'cget')
                varnames   ('self', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       '__init__'
-               firstlineno 161
+               firstlineno 165
                lnotab 0x04013201020162010201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 10
                flags     : 3
                code
@@ -1609,89 +1609,89 @@
                   00ab00000000000000000064067a0b00007c006a0900000000000000007c
                   00a0020000000000000000000000000000000000000000a6000000ab0000
                   0000000000000064077a0a00007c006a0500000000000000007a0a00007c
                   00a0030000000000000000000000000000000000000000a6000000ab0000
                   0000000000000064077a0a00007c006a0500000000000000007a0a0000ac
                   08a6050000ab0500000000000000007c005f0c0000000000000000640053
                   00
-               168           0 RESUME                   0
+               172           0 RESUME                   0
                
-               169           2 LOAD_FAST                0 (self)
+               173           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               171          44 LOAD_FAST                0 (self)
+               176          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_round_rect4)
                
-               172          68 LOAD_CONST               2 (0)
+               177          68 LOAD_CONST               2 (0)
                             70 LOAD_CONST               2 (0)
                
-               173          72 LOAD_FAST                0 (self)
+               178          72 LOAD_FAST                0 (self)
                             74 LOAD_METHOD              2 (winfo_width)
                             96 PRECALL                  0
                            100 CALL                     0
                
-               174         110 LOAD_FAST                0 (self)
+               179         110 LOAD_FAST                0 (self)
                            112 LOAD_METHOD              3 (winfo_height)
                            134 PRECALL                  0
                            138 CALL                     0
                            148 LOAD_FAST                0 (self)
                            150 LOAD_ATTR                4 (frame_radius)
                
-               175         160 LOAD_FAST                0 (self)
+               180         160 LOAD_FAST                0 (self)
                            162 LOAD_ATTR                5 (frame_border_width)
                
-               176         172 LOAD_FAST                0 (self)
+               181         172 LOAD_FAST                0 (self)
                            174 LOAD_ATTR                6 (frame_border)
                            184 LOAD_FAST                0 (self)
                            186 LOAD_ATTR                7 (frame_back)
                
-               171         196 KW_NAMES                 3
+               176         196 KW_NAMES                 3
                            198 PRECALL                  8
                            202 CALL                     8
                            212 POP_TOP
                
-               179         214 LOAD_CONST               4 ('button_frame')
+               184         214 LOAD_CONST               4 ('button_frame')
                            216 LOAD_FAST                0 (self)
                            218 STORE_ATTR               8 (entry_frame)
                
-               181         228 LOAD_FAST                0 (self)
+               186         228 LOAD_FAST                0 (self)
                            230 LOAD_ATTR                9 (frame)
                            240 LOAD_METHOD             10 (configure)
                            262 LOAD_FAST                0 (self)
                            264 LOAD_ATTR                7 (frame_back)
                            274 LOAD_CONST               2 (0)
                            276 KW_NAMES                 5
                            278 PRECALL                  2
                            282 CALL                     2
                            292 POP_TOP
                
-               183         294 LOAD_FAST                0 (self)
+               189         294 LOAD_FAST                0 (self)
                            296 LOAD_METHOD             11 (create_window)
                
-               184         318 LOAD_FAST                0 (self)
+               190         318 LOAD_FAST                0 (self)
                            320 LOAD_METHOD              2 (winfo_width)
                            342 PRECALL                  0
                            346 CALL                     0
                            356 LOAD_CONST               6 (2)
                            358 BINARY_OP               11 (/)
                            362 LOAD_FAST                0 (self)
                            364 LOAD_METHOD              3 (winfo_height)
                            386 PRECALL                  0
                            390 CALL                     0
                            400 LOAD_CONST               6 (2)
                            402 BINARY_OP               11 (/)
                
-               185         406 LOAD_FAST                0 (self)
+               191         406 LOAD_FAST                0 (self)
                            408 LOAD_ATTR                9 (frame)
                
-               186         418 LOAD_FAST                0 (self)
+               192         418 LOAD_FAST                0 (self)
                            420 LOAD_METHOD              2 (winfo_width)
                            442 PRECALL                  0
                            446 CALL                     0
                            456 LOAD_CONST               7 (6)
                            458 BINARY_OP               10 (-)
                            462 LOAD_FAST                0 (self)
                            464 LOAD_ATTR                5 (frame_border_width)
@@ -1702,15 +1702,15 @@
                            506 CALL                     0
                            516 LOAD_CONST               7 (6)
                            518 BINARY_OP               10 (-)
                            522 LOAD_FAST                0 (self)
                            524 LOAD_ATTR                5 (frame_border_width)
                            534 BINARY_OP               10 (-)
                
-               183         538 KW_NAMES                 8
+               189         538 KW_NAMES                 8
                            540 PRECALL                  5
                            544 CALL                     5
                            554 LOAD_FAST                0 (self)
                            556 STORE_ATTR              12 (frame_f)
                            566 LOAD_CONST               0 (None)
                            568 RETURN_VALUE
                consts
@@ -1725,164 +1725,164 @@
                   ('window', 'width', 'height')
                names      ('delete', 'create_round_rect4', 'winfo_width', 'winfo_height', 'frame_radius', 'frame_border_width', 'frame_border', 'frame_back', 'entry_frame', 'frame', 'configure', 'create_window', 'frame_f')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       '_draw'
-               firstlineno 168
+               firstlineno 172
                lnotab
-                  0x02012a0218010401260132010c0118fb12080e024202180158010c0178
+                  0x02012a0318010401260132010c0118fb12080e024203180158010c0178
                   fd
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               189           0 RESUME                   0
+               195           0 RESUME                   0
                
-               190           2 LOAD_FAST                0 (self)
+               196           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'default_palette'
-               firstlineno 189
+               firstlineno 195
                lnotab 0x0201
          names      ('__name__', '__module__', '__qualname__', '__init__', '_draw', 'default_palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
          name       'AdwDrawBasicRoundFrame3'
-         firstlineno 160
-         lnotab 0x0c010a070615
+         firstlineno 164
+         lnotab 0x0c010a070617
       'AdwDrawBasicRoundFrame3'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         193           0 RESUME                   0
+         199           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundFrame3')
                        8 STORE_NAME               2 (__qualname__)
          
-         194          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 194>)
+         200          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 200>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundFrame3'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               194           0 RESUME                   0
+               200           0 RESUME                   0
                
-               195           2 LOAD_FAST                0 (self)
+               201           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'default_palette'
-               firstlineno 194
+               firstlineno 200
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
          name       'AdwDrawRoundFrame3'
-         firstlineno 193
+         firstlineno 199
          lnotab 0x0a01
       'AdwDrawRoundFrame3'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         198           0 RESUME                   0
+         204           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawDarkRoundFrame3')
                        8 STORE_NAME               2 (__qualname__)
          
-         199          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 199>)
+         205          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\frame.py", line 205>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawDarkRoundFrame3'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               199           0 RESUME                   0
+               205           0 RESUME                   0
                
-               200           2 LOAD_FAST                0 (self)
+               206           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
                name       'default_palette'
-               firstlineno 199
+               firstlineno 205
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
          name       'AdwDrawDarkRoundFrame3'
-         firstlineno 198
+         firstlineno 204
          lnotab 0x0a01
       'AdwDrawDarkRoundFrame3'
       '__main__'
       ('Tk',)
       'both'
       'yes'
       ('fill', 'expand')
@@ -1893,9 +1893,9 @@
    varnames   ()
    freevars   ()
    cellvars   ()
    filename   'D:\\tkadw\\tkadw\\canvas\\frame.py'
    name       '<module>'
    firstlineno 1
    lnotab
-      0x00ff02010c010c041c4c1c051c051c3a1c051c051c211c051c050e010c
+      0x00ff02010c010c041c4e1c051c051c3c1c051c051c231c051c050e010c
       01140214012e022001320214012e022001320214012e02200132022cea
```

### Comparing `tkadw-0.2.1/tkadw/canvas/__pycache__/fun6.cpython-311-pytest-7.3.1.pyc` & `tkadw-0.2.2/tkadw/canvas/__pycache__/fun6.cpython-311-pytest-7.3.1.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/canvas/__pycache__/label.cpython-311.pyc` & `tkadw-0.2.2/tkadw/canvas/__pycache__/label.cpython-311.pyc`

 * *Files 8% similar despite different names*

#### Python bytecode

```diff
@@ -1,186 +1,177 @@
 magic:    0xa70d0d0a
-moddate:  0x194d9664 (Sat Jun 24 01:55:37 2023 UTC)
-files sz: 2056
+moddate:  0xa2939664 (Sat Jun 24 06:56:34 2023 UTC)
+files sz: 2020
 code
    argcount  : 0
    nlocals   : 0
    stacksize : 5
    flags     : 0
    code
-      0x9700640064016c006d015a010100640064026c026d035a030100020047
-      006403840064046501a6030000ab0300000000000000005a040200470064
-      05840064066504a6030000ab0300000000000000005a0502004700640784
-      0064086504a6030000ab0300000000000000005a06650764096b02000000
-      0072666400640a6c006d085a08010002006508a6000000ab000000000000
-      0000005a0902006505640bac0ca6010000ab0100000000000000005a0a65
-      0aa00b0000000000000000000000000000000000000000a6000000ab0000
-      00000000000000010002006506640bac0ca6010000ab0100000000000000
-      005a0c650ca00b0000000000000000000000000000000000000000a60000
-      00ab00000000000000000001006509a00d00000000000000000000000000
-      00000000000000a6000000ab0000000000000000000100640d5300640d53
-      00
+      0x9700640064016c006d015a010100020047006402840064036501a60300
+      00ab0300000000000000005a02020047006404840064056502a6030000ab
+      0300000000000000005a03020047006406840064076502a6030000ab0300
+      000000000000005a04650564086b02000000007266640064096c006d065a
+      06010002006506a6000000ab0000000000000000005a0702006503640aac
+      0ba6010000ab0100000000000000005a086508a009000000000000000000
+      0000000000000000000000a6000000ab0000000000000000000100020065
+      04640aac0ba6010000ab0100000000000000005a0a650aa0090000000000
+      000000000000000000000000000000a6000000ab00000000000000000001
+      006507a00b0000000000000000000000000000000000000000a6000000ab
+      0000000000000000000100640c5300640c5300
      0           0 RESUME                   0
    
      1           2 LOAD_CONST               0 (0)
                  4 LOAD_CONST               1 (('Label',))
                  6 IMPORT_NAME              0 (tkinter)
                  8 IMPORT_FROM              1 (Label)
                 10 STORE_NAME               1 (Label)
                 12 POP_TOP
    
-     2          14 LOAD_CONST               0 (0)
-                16 LOAD_CONST               2 (('CTkLabel',))
-                18 IMPORT_NAME              2 (customtkinter)
-                20 IMPORT_FROM              3 (CTkLabel)
-                22 STORE_NAME               3 (CTkLabel)
-                24 POP_TOP
-   
-     5          26 PUSH_NULL
-                28 LOAD_BUILD_CLASS
-                30 LOAD_CONST               3 (<code object AdwDrawBasicLabel, file "D:\tkadw\tkadw\canvas\label.py", line 5>)
-                32 MAKE_FUNCTION            0
-                34 LOAD_CONST               4 ('AdwDrawBasicLabel')
-                36 LOAD_NAME                1 (Label)
-                38 PRECALL                  3
-                42 CALL                     3
-                52 STORE_NAME               4 (AdwDrawBasicLabel)
-   
-    64          54 PUSH_NULL
-                56 LOAD_BUILD_CLASS
-                58 LOAD_CONST               5 (<code object AdwDrawLabel, file "D:\tkadw\tkadw\canvas\label.py", line 64>)
-                60 MAKE_FUNCTION            0
-                62 LOAD_CONST               6 ('AdwDrawLabel')
-                64 LOAD_NAME                4 (AdwDrawBasicLabel)
-                66 PRECALL                  3
-                70 CALL                     3
-                80 STORE_NAME               5 (AdwDrawLabel)
-   
-    69          82 PUSH_NULL
-                84 LOAD_BUILD_CLASS
-                86 LOAD_CONST               7 (<code object AdwDrawDarkLabel, file "D:\tkadw\tkadw\canvas\label.py", line 69>)
-                88 MAKE_FUNCTION            0
-                90 LOAD_CONST               8 ('AdwDrawDarkLabel')
-                92 LOAD_NAME                4 (AdwDrawBasicLabel)
-                94 PRECALL                  3
-                98 CALL                     3
-               108 STORE_NAME               6 (AdwDrawDarkLabel)
-   
-    74         110 LOAD_NAME                7 (__name__)
-               112 LOAD_CONST               9 ('__main__')
-               114 COMPARE_OP               2 (==)
-               120 POP_JUMP_FORWARD_IF_FALSE   102 (to 326)
-   
-    75         122 LOAD_CONST               0 (0)
-               124 LOAD_CONST              10 (('Tk',))
-               126 IMPORT_NAME              0 (tkinter)
-               128 IMPORT_FROM              8 (Tk)
-               130 STORE_NAME               8 (Tk)
-               132 POP_TOP
-   
-    76         134 PUSH_NULL
-               136 LOAD_NAME                8 (Tk)
-               138 PRECALL                  0
-               142 CALL                     0
-               152 STORE_NAME               9 (root)
-   
-    77         154 PUSH_NULL
-               156 LOAD_NAME                5 (AdwDrawLabel)
-               158 LOAD_CONST              11 ('hello')
-               160 KW_NAMES                12
-               162 PRECALL                  1
-               166 CALL                     1
-               176 STORE_NAME              10 (label)
-   
-    78         178 LOAD_NAME               10 (label)
-               180 LOAD_METHOD             11 (pack)
-               202 PRECALL                  0
-               206 CALL                     0
-               216 POP_TOP
-   
-    79         218 PUSH_NULL
-               220 LOAD_NAME                6 (AdwDrawDarkLabel)
-               222 LOAD_CONST              11 ('hello')
-               224 KW_NAMES                12
-               226 PRECALL                  1
-               230 CALL                     1
-               240 STORE_NAME              12 (label2)
-   
-    80         242 LOAD_NAME               12 (label2)
-               244 LOAD_METHOD             11 (pack)
-               266 PRECALL                  0
-               270 CALL                     0
-               280 POP_TOP
-   
-    81         282 LOAD_NAME                9 (root)
-               284 LOAD_METHOD             13 (mainloop)
-               306 PRECALL                  0
-               310 CALL                     0
-               320 POP_TOP
-               322 LOAD_CONST              13 (None)
-               324 RETURN_VALUE
+     4          14 PUSH_NULL
+                16 LOAD_BUILD_CLASS
+                18 LOAD_CONST               2 (<code object AdwDrawBasicLabel, file "D:\tkadw\tkadw\canvas\label.py", line 4>)
+                20 MAKE_FUNCTION            0
+                22 LOAD_CONST               3 ('AdwDrawBasicLabel')
+                24 LOAD_NAME                1 (Label)
+                26 PRECALL                  3
+                30 CALL                     3
+                40 STORE_NAME               2 (AdwDrawBasicLabel)
+   
+    63          42 PUSH_NULL
+                44 LOAD_BUILD_CLASS
+                46 LOAD_CONST               4 (<code object AdwDrawLabel, file "D:\tkadw\tkadw\canvas\label.py", line 63>)
+                48 MAKE_FUNCTION            0
+                50 LOAD_CONST               5 ('AdwDrawLabel')
+                52 LOAD_NAME                2 (AdwDrawBasicLabel)
+                54 PRECALL                  3
+                58 CALL                     3
+                68 STORE_NAME               3 (AdwDrawLabel)
+   
+    68          70 PUSH_NULL
+                72 LOAD_BUILD_CLASS
+                74 LOAD_CONST               6 (<code object AdwDrawDarkLabel, file "D:\tkadw\tkadw\canvas\label.py", line 68>)
+                76 MAKE_FUNCTION            0
+                78 LOAD_CONST               7 ('AdwDrawDarkLabel')
+                80 LOAD_NAME                2 (AdwDrawBasicLabel)
+                82 PRECALL                  3
+                86 CALL                     3
+                96 STORE_NAME               4 (AdwDrawDarkLabel)
+   
+    73          98 LOAD_NAME                5 (__name__)
+               100 LOAD_CONST               8 ('__main__')
+               102 COMPARE_OP               2 (==)
+               108 POP_JUMP_FORWARD_IF_FALSE   102 (to 314)
+   
+    74         110 LOAD_CONST               0 (0)
+               112 LOAD_CONST               9 (('Tk',))
+               114 IMPORT_NAME              0 (tkinter)
+               116 IMPORT_FROM              6 (Tk)
+               118 STORE_NAME               6 (Tk)
+               120 POP_TOP
+   
+    75         122 PUSH_NULL
+               124 LOAD_NAME                6 (Tk)
+               126 PRECALL                  0
+               130 CALL                     0
+               140 STORE_NAME               7 (root)
+   
+    76         142 PUSH_NULL
+               144 LOAD_NAME                3 (AdwDrawLabel)
+               146 LOAD_CONST              10 ('hello')
+               148 KW_NAMES                11
+               150 PRECALL                  1
+               154 CALL                     1
+               164 STORE_NAME               8 (label)
+   
+    77         166 LOAD_NAME                8 (label)
+               168 LOAD_METHOD              9 (pack)
+               190 PRECALL                  0
+               194 CALL                     0
+               204 POP_TOP
+   
+    78         206 PUSH_NULL
+               208 LOAD_NAME                4 (AdwDrawDarkLabel)
+               210 LOAD_CONST              10 ('hello')
+               212 KW_NAMES                11
+               214 PRECALL                  1
+               218 CALL                     1
+               228 STORE_NAME              10 (label2)
+   
+    79         230 LOAD_NAME               10 (label2)
+               232 LOAD_METHOD              9 (pack)
+               254 PRECALL                  0
+               258 CALL                     0
+               268 POP_TOP
+   
+    80         270 LOAD_NAME                7 (root)
+               272 LOAD_METHOD             11 (mainloop)
+               294 PRECALL                  0
+               298 CALL                     0
+               308 POP_TOP
+               310 LOAD_CONST              12 (None)
+               312 RETURN_VALUE
    
-    74     >>  326 LOAD_CONST              13 (None)
-               328 RETURN_VALUE
+    73     >>  314 LOAD_CONST              12 (None)
+               316 RETURN_VALUE
    consts
       0
       ('Label',)
-      ('CTkLabel',)
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 4
          flags     : 0
          code
             0x8700970065005a0164005a02640164029c016403650366028800660164
             04840e5a04640c640684015a05640784005a06640884005a07640984005a
             08640a84005a09640c640b84015a0a880078015a0b5300
                        0 MAKE_CELL                0 (__class__)
          
-           5           2 RESUME                   0
+           4           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawBasicLabel')
                       10 STORE_NAME               2 (__qualname__)
          
-           6          12 LOAD_CONST               1 ('')
+           5          12 LOAD_CONST               1 ('')
                       14 LOAD_CONST               2 (('text',))
                       16 BUILD_CONST_KEY_MAP      1
                       18 LOAD_CONST               3 ('text')
                       20 LOAD_NAME                3 (str)
                       22 BUILD_TUPLE              2
                       24 LOAD_CLOSURE             0 (__class__)
                       26 BUILD_TUPLE              1
-                      28 LOAD_CONST               4 (<code object __init__, file "D:\tkadw\tkadw\canvas\label.py", line 6>)
+                      28 LOAD_CONST               4 (<code object __init__, file "D:\tkadw\tkadw\canvas\label.py", line 5>)
                       30 MAKE_FUNCTION           14 (kwdefaults, annotations, closure)
                       32 STORE_NAME               4 (__init__)
          
-          17          34 LOAD_CONST              12 ((None,))
-                      36 LOAD_CONST               6 (<code object _draw, file "D:\tkadw\tkadw\canvas\label.py", line 17>)
+          16          34 LOAD_CONST              12 ((None,))
+                      36 LOAD_CONST               6 (<code object _draw, file "D:\tkadw\tkadw\canvas\label.py", line 16>)
                       38 MAKE_FUNCTION            1 (defaults)
                       40 STORE_NAME               5 (_draw)
          
-          22          42 LOAD_CONST               7 (<code object _other, file "D:\tkadw\tkadw\canvas\label.py", line 22>)
+          21          42 LOAD_CONST               7 (<code object _other, file "D:\tkadw\tkadw\canvas\label.py", line 21>)
                       44 MAKE_FUNCTION            0
                       46 STORE_NAME               6 (_other)
          
-          25          48 LOAD_CONST               8 (<code object default_palette, file "D:\tkadw\tkadw\canvas\label.py", line 25>)
+          24          48 LOAD_CONST               8 (<code object default_palette, file "D:\tkadw\tkadw\canvas\label.py", line 24>)
                       50 MAKE_FUNCTION            0
                       52 STORE_NAME               7 (default_palette)
          
-          28          54 LOAD_CONST               9 (<code object palette_light, file "D:\tkadw\tkadw\canvas\label.py", line 28>)
+          27          54 LOAD_CONST               9 (<code object palette_light, file "D:\tkadw\tkadw\canvas\label.py", line 27>)
                       56 MAKE_FUNCTION            0
                       58 STORE_NAME               8 (palette_light)
          
-          38          60 LOAD_CONST              10 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\label.py", line 38>)
+          37          60 LOAD_CONST              10 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\label.py", line 37>)
                       62 MAKE_FUNCTION            0
                       64 STORE_NAME               9 (palette_dark)
          
-          48          66 LOAD_CONST              12 ((None,))
-                      68 LOAD_CONST              11 (<code object palette, file "D:\tkadw\tkadw\canvas\label.py", line 48>)
+          47          66 LOAD_CONST              12 ((None,))
+                      68 LOAD_CONST              11 (<code object palette, file "D:\tkadw\tkadw\canvas\label.py", line 47>)
                       70 MAKE_FUNCTION            1 (defaults)
                       72 STORE_NAME              10 (palette)
                       74 LOAD_CLOSURE             0 (__class__)
                       76 COPY                     1
                       78 STORE_NAME              11 (__classcell__)
                       80 RETURN_VALUE
          consts
@@ -205,67 +196,67 @@
                   00000000000000a6000000ab0000000000000000006403ac04a6030000ab
                   03000000000000000001007c00a004000000000000000000000000000000
                   000000000064067c00a00500000000000000000000000000000000000000
                   00a6000000ab0000000000000000006403ac04a6030000ab030000000000
                   000000010064005300
                              0 COPY_FREE_VARS           1
                
-                 6           2 RESUME                   0
+                 5           2 RESUME                   0
                
-                 7           4 PUSH_NULL
+                 6           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                2 (args)
                             44 LOAD_CONST               1 ('text')
                             46 LOAD_FAST                1 (text)
                             48 BUILD_MAP                1
                             50 LOAD_FAST                3 (kwargs)
                             52 DICT_MERGE               1
                             54 CALL_FUNCTION_EX         1
                             56 POP_TOP
                
-                 9          58 LOAD_FAST                0 (self)
+                 8          58 LOAD_FAST                0 (self)
                             60 LOAD_METHOD              2 (_other)
                             82 PRECALL                  0
                             86 CALL                     0
                             96 POP_TOP
                
-                11          98 LOAD_FAST                0 (self)
+                10          98 LOAD_FAST                0 (self)
                            100 LOAD_METHOD              3 (default_palette)
                            122 PRECALL                  0
                            126 CALL                     0
                            136 POP_TOP
                
-                13         138 LOAD_FAST                0 (self)
+                12         138 LOAD_FAST                0 (self)
                            140 LOAD_METHOD              4 (bind)
                            162 LOAD_CONST               2 ('<Configure>')
                            164 LOAD_FAST                0 (self)
                            166 LOAD_ATTR                5 (_draw)
                            176 LOAD_CONST               3 ('+')
                            178 KW_NAMES                 4
                            180 PRECALL                  3
                            184 CALL                     3
                            194 POP_TOP
                
-                14         196 LOAD_FAST                0 (self)
+                13         196 LOAD_FAST                0 (self)
                            198 LOAD_METHOD              4 (bind)
                            220 LOAD_CONST               5 ('<Enter>')
                            222 LOAD_FAST                0 (self)
                            224 LOAD_METHOD              5 (_draw)
                            246 PRECALL                  0
                            250 CALL                     0
                            260 LOAD_CONST               3 ('+')
                            262 KW_NAMES                 4
                            264 PRECALL                  3
                            268 CALL                     3
                            278 POP_TOP
                
-                15         280 LOAD_FAST                0 (self)
+                14         280 LOAD_FAST                0 (self)
                            282 LOAD_METHOD              4 (bind)
                            304 LOAD_CONST               6 ('<Leave>')
                            306 LOAD_FAST                0 (self)
                            308 LOAD_METHOD              5 (_draw)
                            330 PRECALL                  0
                            334 CALL                     0
                            344 LOAD_CONST               3 ('+')
@@ -285,51 +276,51 @@
                   '<Leave>'
                names      ('super', '__init__', '_other', 'default_palette', 'bind', '_draw')
                varnames   ('self', 'text', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
                name       '__init__'
-               firstlineno 6
+               firstlineno 5
                lnotab 0x04013602280228023a015401
             None
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 5
                flags     : 3
                code
                   0x97007c006a00000000000000000064016b0200000000722e7c00a00100
                   000000000000000000000000000000000000007c006a0200000000000000
                   00a00300000000000000000000000000000000000000006402a6010000ab
                   010000000000000000ac03a6010000ab01000000000000000001007c00a0
                   0100000000000000000000000000000000000000007c006a040000000000
                   000000ac04a6010000ab010000000000000000010064005300
-                17           0 RESUME                   0
+                16           0 RESUME                   0
                
-                18           2 LOAD_FAST                0 (self)
+                17           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (label_back)
                             14 LOAD_CONST               1 ('transparent')
                             16 COMPARE_OP               2 (==)
                             22 POP_JUMP_FORWARD_IF_FALSE    46 (to 116)
                
-                19          24 LOAD_FAST                0 (self)
+                18          24 LOAD_FAST                0 (self)
                             26 LOAD_METHOD              1 (configure)
                             48 LOAD_FAST                0 (self)
                             50 LOAD_ATTR                2 (master)
                             60 LOAD_METHOD              3 (cget)
                             82 LOAD_CONST               2 ('bg')
                             84 PRECALL                  1
                             88 CALL                     1
                             98 KW_NAMES                 3
                            100 PRECALL                  1
                            104 CALL                     1
                            114 POP_TOP
                
-                20     >>  116 LOAD_FAST                0 (self)
+                19     >>  116 LOAD_FAST                0 (self)
                            118 LOAD_METHOD              1 (configure)
                            140 LOAD_FAST                0 (self)
                            142 LOAD_ATTR                4 (label_text_back)
                            152 KW_NAMES                 4
                            154 PRECALL                  1
                            158 CALL                     1
                            168 POP_TOP
@@ -343,88 +334,88 @@
                   ('foreground',)
                names      ('label_back', 'configure', 'master', 'cget', 'label_text_back')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
                name       '_draw'
-               firstlineno 17
+               firstlineno 16
                lnotab 0x020116015c01
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 1
                flags     : 3
                code 0x970064005300
-                22           0 RESUME                   0
+                21           0 RESUME                   0
                
-                23           2 LOAD_CONST               0 (None)
+                22           2 LOAD_CONST               0 (None)
                              4 RETURN_VALUE
                consts
                   None
                names      ()
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
                name       '_other'
-               firstlineno 22
+               firstlineno 21
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-                25           0 RESUME                   0
+                24           0 RESUME                   0
                
-                26           2 LOAD_FAST                0 (self)
+                25           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
                name       'default_palette'
-               firstlineno 25
+               firstlineno 24
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 6
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   02640364049c026901a6010000ab010000000000000000010064005300
-                28           0 RESUME                   0
+                27           0 RESUME                   0
                
-                29           2 LOAD_FAST                0 (self)
+                28           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-                31          26 LOAD_CONST               1 ('label')
+                30          26 LOAD_CONST               1 ('label')
                
-                32          28 LOAD_CONST               2 ('transparent')
+                31          28 LOAD_CONST               2 ('transparent')
                
-                33          30 LOAD_CONST               3 ('#000000')
+                32          30 LOAD_CONST               3 ('#000000')
                
-                31          32 LOAD_CONST               4 (('back', 'text_back'))
+                30          32 LOAD_CONST               4 (('back', 'text_back'))
                             34 BUILD_CONST_KEY_MAP      2
                
-                30          36 BUILD_MAP                1
+                29          36 BUILD_MAP                1
                
-                29          38 PRECALL                  1
+                28          38 PRECALL                  1
                             42 CALL                     1
                             52 POP_TOP
                             54 LOAD_CONST               0 (None)
                             56 RETURN_VALUE
                consts
                   None
                   'label'
@@ -433,41 +424,41 @@
                   ('back', 'text_back')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
                name       'palette_light'
-               firstlineno 28
+               firstlineno 27
                lnotab 0x020118020201020102fe04ff02ff
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 6
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   02640364049c026901a6010000ab010000000000000000010064005300
-                38           0 RESUME                   0
+                37           0 RESUME                   0
                
-                39           2 LOAD_FAST                0 (self)
+                38           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-                41          26 LOAD_CONST               1 ('label')
+                40          26 LOAD_CONST               1 ('label')
                
-                42          28 LOAD_CONST               2 ('transparent')
+                41          28 LOAD_CONST               2 ('transparent')
                
-                43          30 LOAD_CONST               3 ('#ffffff')
+                42          30 LOAD_CONST               3 ('#ffffff')
                
-                41          32 LOAD_CONST               4 (('back', 'text_back'))
+                40          32 LOAD_CONST               4 (('back', 'text_back'))
                             34 BUILD_CONST_KEY_MAP      2
                
-                40          36 BUILD_MAP                1
+                39          36 BUILD_MAP                1
                
-                39          38 PRECALL                  1
+                38          38 PRECALL                  1
                             42 CALL                     1
                             52 POP_TOP
                             54 LOAD_CONST               0 (None)
                             56 RETURN_VALUE
                consts
                   None
                   'label'
@@ -476,86 +467,86 @@
                   ('back', 'text_back')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
                name       'palette_dark'
-               firstlineno 38
+               firstlineno 37
                lnotab 0x020118020201020102fe04ff02ff
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 4
                flags     : 3
                code
                   0x97007c01815a64017c01760072267c0164011900000000000000000064
                   02190000000000000000007c005f0000000000000000007c016401190000
                   000000000000006403190000000000000000007c005f0100000000000000
                   007c017c005f02000000000000000009007c00a003000000000000000000
                   00000000000000000000006400a6010000ab010000000000000000010064
                   005300230074080000000000000000000024007204010059006400530077
                   007803590077017c006a0200000000000000005300
-                48           0 RESUME                   0
+                47           0 RESUME                   0
                
-                49           2 LOAD_FAST                1 (dict)
+                48           2 LOAD_FAST                1 (dict)
                              4 POP_JUMP_FORWARD_IF_NONE    90 (to 186)
                
-                50           6 LOAD_CONST               1 ('label')
+                49           6 LOAD_CONST               1 ('label')
                              8 LOAD_FAST                1 (dict)
                             10 CONTAINS_OP              0
                             12 POP_JUMP_FORWARD_IF_FALSE    38 (to 90)
                
-                51          14 LOAD_FAST                1 (dict)
+                50          14 LOAD_FAST                1 (dict)
                             16 LOAD_CONST               1 ('label')
                             18 BINARY_SUBSCR
                             28 LOAD_CONST               2 ('back')
                             30 BINARY_SUBSCR
                             40 LOAD_FAST                0 (self)
                             42 STORE_ATTR               0 (label_back)
                
-                52          52 LOAD_FAST                1 (dict)
+                51          52 LOAD_FAST                1 (dict)
                             54 LOAD_CONST               1 ('label')
                             56 BINARY_SUBSCR
                             66 LOAD_CONST               3 ('text_back')
                             68 BINARY_SUBSCR
                             78 LOAD_FAST                0 (self)
                             80 STORE_ATTR               1 (label_text_back)
                
-                54     >>   90 LOAD_FAST                1 (dict)
+                53     >>   90 LOAD_FAST                1 (dict)
                             92 LOAD_FAST                0 (self)
                             94 STORE_ATTR               2 (_palette)
                
-                56         104 NOP
+                55         104 NOP
                
-                57         106 LOAD_FAST                0 (self)
+                56         106 LOAD_FAST                0 (self)
                            108 LOAD_METHOD              3 (_draw)
                            130 LOAD_CONST               0 (None)
                            132 PRECALL                  1
                            136 CALL                     1
                            146 POP_TOP
                            148 LOAD_CONST               0 (None)
                            150 RETURN_VALUE
                        >>  152 PUSH_EXC_INFO
                
-                58         154 LOAD_GLOBAL              8 (AttributeError)
+                57         154 LOAD_GLOBAL              8 (AttributeError)
                            166 CHECK_EXC_MATCH
                            168 POP_JUMP_FORWARD_IF_FALSE     4 (to 178)
                            170 POP_TOP
                
-                59         172 POP_EXCEPT
+                58         172 POP_EXCEPT
                            174 LOAD_CONST               0 (None)
                            176 RETURN_VALUE
                
-                58     >>  178 RERAISE                  0
+                57     >>  178 RERAISE                  0
                        >>  180 COPY                     3
                            182 POP_EXCEPT
                            184 RERAISE                  1
                
-                61     >>  186 LOAD_FAST                0 (self)
+                60     >>  186 LOAD_FAST                0 (self)
                            188 LOAD_ATTR                2 (_palette)
                            198 RETURN_VALUE
                ExceptionTable:
                  106 to 146 -> 152 [0]
                  152 to 170 -> 180 [1] lasti
                  178 to 178 -> 180 [1] lasti
                consts
@@ -565,146 +556,144 @@
                   'text_back'
                names      ('label_back', 'label_text_back', '_palette', '_draw', 'AttributeError')
                varnames   ('self', 'dict')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
                name       'palette'
-               firstlineno 48
+               firstlineno 47
                lnotab 0x020104010801260126020e0202013001120106ff0803
             (None,)
          names      ('__name__', '__module__', '__qualname__', 'str', '__init__', '_draw', '_other', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
          name       'AdwDrawBasicLabel'
-         firstlineno 5
+         firstlineno 4
          lnotab 0x0c01160b080506030603060a060a
       'AdwDrawBasicLabel'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-          64           0 RESUME                   0
+          63           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawLabel')
                        8 STORE_NAME               2 (__qualname__)
          
-          65          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\label.py", line 65>)
+          64          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\label.py", line 64>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawLabel'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-                65           0 RESUME                   0
+                64           0 RESUME                   0
                
-                66           2 LOAD_FAST                0 (self)
+                65           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
                name       'default_palette'
-               firstlineno 65
+               firstlineno 64
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
          name       'AdwDrawLabel'
-         firstlineno 64
+         firstlineno 63
          lnotab 0x0a01
       'AdwDrawLabel'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-          69           0 RESUME                   0
+          68           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawDarkLabel')
                        8 STORE_NAME               2 (__qualname__)
          
-          70          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\label.py", line 70>)
+          69          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\label.py", line 69>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawDarkLabel'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-                70           0 RESUME                   0
+                69           0 RESUME                   0
                
-                71           2 LOAD_FAST                0 (self)
+                70           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
                name       'default_palette'
-               firstlineno 70
+               firstlineno 69
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
          name       'AdwDrawDarkLabel'
-         firstlineno 69
+         firstlineno 68
          lnotab 0x0a01
       'AdwDrawDarkLabel'
       '__main__'
       ('Tk',)
       'hello'
       ('text',)
       None
-   names      ('tkinter', 'Label', 'customtkinter', 'CTkLabel', 'AdwDrawBasicLabel', 'AdwDrawLabel', 'AdwDrawDarkLabel', '__name__', 'Tk', 'root', 'label', 'pack', 'label2', 'mainloop')
+   names      ('tkinter', 'Label', 'AdwDrawBasicLabel', 'AdwDrawLabel', 'AdwDrawDarkLabel', '__name__', 'Tk', 'root', 'label', 'pack', 'label2', 'mainloop')
    varnames   ()
    freevars   ()
    cellvars   ()
    filename   'D:\\tkadw\\tkadw\\canvas\\label.py'
    name       '<module>'
    firstlineno 1
-   lnotab
-      0x00ff02010c010c031c3b1c051c050c010c01140118012801180128012c
-      f9
+   lnotab 0x00ff02010c031c3b1c051c050c010c01140118012801180128012cf9
```

### Comparing `tkadw-0.2.1/tkadw/canvas/__pycache__/textbox.cpython-311.pyc` & `tkadw-0.2.2/tkadw/canvas/__pycache__/textbox.cpython-311.pyc`

 * *Files 2% similar despite different names*

#### Python bytecode

```diff
@@ -1,24 +1,24 @@
 magic:    0xa70d0d0a
-moddate:  0xf34e9664 (Sat Jun 24 02:03:31 2023 UTC)
-files sz: 21800
+moddate:  0x0ad69664 (Sat Jun 24 11:39:54 2023 UTC)
+files sz: 20506
 code
    argcount  : 0
    nlocals   : 0
    stacksize : 5
    flags     : 0
    code
       0x9700640064016c006d015a016d025a020100640064026c036d045a0401
       00020047006403840064046504a6030000ab0300000000000000005a0502
       0047006405840064066505a6030000ab0300000000000000005a06020047
       006407840064086505a6030000ab0300000000000000005a070200470064
       098400640a6505a6030000ab0300000000000000005a0802004700640b84
       00640c6508a6030000ab0300000000000000005a0902004700640d840064
       0e6508a6030000ab0300000000000000005a0a02004700640f8400641065
-      05a6030000ab0300000000000000005a0b02004700641184006412650ba6
+      08a6030000ab0300000000000000005a0b02004700641184006412650ba6
       030000ab0300000000000000005a0c02004700641384006414650ba60300
       00ab0300000000000000005a0d650e64156b020000000072f2640064166c
       0f6d105a10010002006510a6000000ab0000000000000000005a11020065
       06a6000000ab0000000000000000005a126512a013000000000000000000
       0000000000000000000000641764186418ac19a6030000ab030000000000
       000000010002006507a6000000ab0000000000000000005a146514a01300
       00000000000000000000000000000000000000641764186418ac19a60300
@@ -58,217 +58,217 @@
                 36 MAKE_FUNCTION            0
                 38 LOAD_CONST               4 ('AdwDrawBasicText')
                 40 LOAD_NAME                4 (AdwDrawEngine)
                 42 PRECALL                  3
                 46 CALL                     3
                 56 STORE_NAME               5 (AdwDrawBasicText)
    
-   255          58 PUSH_NULL
+   261          58 PUSH_NULL
                 60 LOAD_BUILD_CLASS
-                62 LOAD_CONST               5 (<code object AdwDrawText, file "D:\tkadw\tkadw\canvas\textbox.py", line 255>)
+                62 LOAD_CONST               5 (<code object AdwDrawText, file "D:\tkadw\tkadw\canvas\textbox.py", line 261>)
                 64 MAKE_FUNCTION            0
                 66 LOAD_CONST               6 ('AdwDrawText')
                 68 LOAD_NAME                5 (AdwDrawBasicText)
                 70 PRECALL                  3
                 74 CALL                     3
                 84 STORE_NAME               6 (AdwDrawText)
    
-   260          86 PUSH_NULL
+   266          86 PUSH_NULL
                 88 LOAD_BUILD_CLASS
-                90 LOAD_CONST               7 (<code object AdwDrawDarkText, file "D:\tkadw\tkadw\canvas\textbox.py", line 260>)
+                90 LOAD_CONST               7 (<code object AdwDrawDarkText, file "D:\tkadw\tkadw\canvas\textbox.py", line 266>)
                 92 MAKE_FUNCTION            0
                 94 LOAD_CONST               8 ('AdwDrawDarkText')
                 96 LOAD_NAME                5 (AdwDrawBasicText)
                 98 PRECALL                  3
                102 CALL                     3
                112 STORE_NAME               7 (AdwDrawDarkText)
    
-   266         114 PUSH_NULL
+   272         114 PUSH_NULL
                116 LOAD_BUILD_CLASS
-               118 LOAD_CONST               9 (<code object AdwDrawBasicRoundText, file "D:\tkadw\tkadw\canvas\textbox.py", line 266>)
+               118 LOAD_CONST               9 (<code object AdwDrawBasicRoundText, file "D:\tkadw\tkadw\canvas\textbox.py", line 272>)
                120 MAKE_FUNCTION            0
                122 LOAD_CONST              10 ('AdwDrawBasicRoundText')
                124 LOAD_NAME                5 (AdwDrawBasicText)
                126 PRECALL                  3
                130 CALL                     3
                140 STORE_NAME               8 (AdwDrawBasicRoundText)
    
-   415         142 PUSH_NULL
+   421         142 PUSH_NULL
                144 LOAD_BUILD_CLASS
-               146 LOAD_CONST              11 (<code object AdwDrawRoundText, file "D:\tkadw\tkadw\canvas\textbox.py", line 415>)
+               146 LOAD_CONST              11 (<code object AdwDrawRoundText, file "D:\tkadw\tkadw\canvas\textbox.py", line 421>)
                148 MAKE_FUNCTION            0
                150 LOAD_CONST              12 ('AdwDrawRoundText')
                152 LOAD_NAME                8 (AdwDrawBasicRoundText)
                154 PRECALL                  3
                158 CALL                     3
                168 STORE_NAME               9 (AdwDrawRoundText)
    
-   420         170 PUSH_NULL
+   426         170 PUSH_NULL
                172 LOAD_BUILD_CLASS
-               174 LOAD_CONST              13 (<code object AdwDrawRoundDarkText, file "D:\tkadw\tkadw\canvas\textbox.py", line 420>)
+               174 LOAD_CONST              13 (<code object AdwDrawRoundDarkText, file "D:\tkadw\tkadw\canvas\textbox.py", line 426>)
                176 MAKE_FUNCTION            0
                178 LOAD_CONST              14 ('AdwDrawRoundDarkText')
                180 LOAD_NAME                8 (AdwDrawBasicRoundText)
                182 PRECALL                  3
                186 CALL                     3
                196 STORE_NAME              10 (AdwDrawRoundDarkText)
    
-   425         198 PUSH_NULL
+   431         198 PUSH_NULL
                200 LOAD_BUILD_CLASS
-               202 LOAD_CONST              15 (<code object AdwDrawBasicRoundText3, file "D:\tkadw\tkadw\canvas\textbox.py", line 425>)
+               202 LOAD_CONST              15 (<code object AdwDrawBasicRoundText3, file "D:\tkadw\tkadw\canvas\textbox.py", line 431>)
                204 MAKE_FUNCTION            0
                206 LOAD_CONST              16 ('AdwDrawBasicRoundText3')
-               208 LOAD_NAME                5 (AdwDrawBasicText)
+               208 LOAD_NAME                8 (AdwDrawBasicRoundText)
                210 PRECALL                  3
                214 CALL                     3
                224 STORE_NAME              11 (AdwDrawBasicRoundText3)
    
-   609         226 PUSH_NULL
+   581         226 PUSH_NULL
                228 LOAD_BUILD_CLASS
-               230 LOAD_CONST              17 (<code object AdwDrawRoundText3, file "D:\tkadw\tkadw\canvas\textbox.py", line 609>)
+               230 LOAD_CONST              17 (<code object AdwDrawRoundText3, file "D:\tkadw\tkadw\canvas\textbox.py", line 581>)
                232 MAKE_FUNCTION            0
                234 LOAD_CONST              18 ('AdwDrawRoundText3')
                236 LOAD_NAME               11 (AdwDrawBasicRoundText3)
                238 PRECALL                  3
                242 CALL                     3
                252 STORE_NAME              12 (AdwDrawRoundText3)
    
-   614         254 PUSH_NULL
+   586         254 PUSH_NULL
                256 LOAD_BUILD_CLASS
-               258 LOAD_CONST              19 (<code object AdwDrawRoundDarkText3, file "D:\tkadw\tkadw\canvas\textbox.py", line 614>)
+               258 LOAD_CONST              19 (<code object AdwDrawRoundDarkText3, file "D:\tkadw\tkadw\canvas\textbox.py", line 586>)
                260 MAKE_FUNCTION            0
                262 LOAD_CONST              20 ('AdwDrawRoundDarkText3')
                264 LOAD_NAME               11 (AdwDrawBasicRoundText3)
                266 PRECALL                  3
                270 CALL                     3
                280 STORE_NAME              13 (AdwDrawRoundDarkText3)
    
-   619         282 LOAD_NAME               14 (__name__)
+   591         282 LOAD_NAME               14 (__name__)
                284 LOAD_CONST              21 ('__main__')
                286 COMPARE_OP               2 (==)
                292 POP_JUMP_FORWARD_IF_FALSE   242 (to 778)
    
-   620         294 LOAD_CONST               0 (0)
+   592         294 LOAD_CONST               0 (0)
                296 LOAD_CONST              22 (('Tk',))
                298 IMPORT_NAME             15 (tkinter)
                300 IMPORT_FROM             16 (Tk)
                302 STORE_NAME              16 (Tk)
                304 POP_TOP
    
-   622         306 PUSH_NULL
+   594         306 PUSH_NULL
                308 LOAD_NAME               16 (Tk)
                310 PRECALL                  0
                314 CALL                     0
                324 STORE_NAME              17 (root)
    
-   624         326 PUSH_NULL
+   596         326 PUSH_NULL
                328 LOAD_NAME                6 (AdwDrawText)
                330 PRECALL                  0
                334 CALL                     0
                344 STORE_NAME              18 (text1)
    
-   625         346 LOAD_NAME               18 (text1)
+   597         346 LOAD_NAME               18 (text1)
                348 LOAD_METHOD             19 (pack)
                370 LOAD_CONST              23 ('x')
                372 LOAD_CONST              24 (5)
                374 LOAD_CONST              24 (5)
                376 KW_NAMES                25
                378 PRECALL                  3
                382 CALL                     3
                392 POP_TOP
    
-   627         394 PUSH_NULL
+   599         394 PUSH_NULL
                396 LOAD_NAME                7 (AdwDrawDarkText)
                398 PRECALL                  0
                402 CALL                     0
                412 STORE_NAME              20 (text2)
    
-   628         414 LOAD_NAME               20 (text2)
+   600         414 LOAD_NAME               20 (text2)
                416 LOAD_METHOD             19 (pack)
                438 LOAD_CONST              23 ('x')
                440 LOAD_CONST              24 (5)
                442 LOAD_CONST              24 (5)
                444 KW_NAMES                25
                446 PRECALL                  3
                450 CALL                     3
                460 POP_TOP
    
-   630         462 PUSH_NULL
+   602         462 PUSH_NULL
                464 LOAD_NAME                9 (AdwDrawRoundText)
                466 PRECALL                  0
                470 CALL                     0
                480 STORE_NAME              21 (text3)
    
-   631         482 LOAD_NAME               21 (text3)
+   603         482 LOAD_NAME               21 (text3)
                484 LOAD_METHOD             19 (pack)
                506 LOAD_CONST              23 ('x')
                508 LOAD_CONST              24 (5)
                510 LOAD_CONST              24 (5)
                512 KW_NAMES                25
                514 PRECALL                  3
                518 CALL                     3
                528 POP_TOP
    
-   633         530 PUSH_NULL
+   605         530 PUSH_NULL
                532 LOAD_NAME               10 (AdwDrawRoundDarkText)
                534 PRECALL                  0
                538 CALL                     0
                548 STORE_NAME              22 (text4)
    
-   634         550 LOAD_NAME               22 (text4)
+   606         550 LOAD_NAME               22 (text4)
                552 LOAD_METHOD             19 (pack)
                574 LOAD_CONST              23 ('x')
                576 LOAD_CONST              24 (5)
                578 LOAD_CONST              24 (5)
                580 KW_NAMES                25
                582 PRECALL                  3
                586 CALL                     3
                596 POP_TOP
    
-   636         598 PUSH_NULL
+   608         598 PUSH_NULL
                600 LOAD_NAME               12 (AdwDrawRoundText3)
                602 PRECALL                  0
                606 CALL                     0
                616 STORE_NAME              23 (text5)
    
-   637         618 LOAD_NAME               23 (text5)
+   609         618 LOAD_NAME               23 (text5)
                620 LOAD_METHOD             19 (pack)
                642 LOAD_CONST              23 ('x')
                644 LOAD_CONST              24 (5)
                646 LOAD_CONST              24 (5)
                648 KW_NAMES                25
                650 PRECALL                  3
                654 CALL                     3
                664 POP_TOP
    
-   639         666 PUSH_NULL
+   611         666 PUSH_NULL
                668 LOAD_NAME               13 (AdwDrawRoundDarkText3)
                670 PRECALL                  0
                674 CALL                     0
                684 STORE_NAME              24 (text6)
    
-   640         686 LOAD_NAME               24 (text6)
+   612         686 LOAD_NAME               24 (text6)
                688 LOAD_METHOD             19 (pack)
                710 LOAD_CONST              23 ('x')
                712 LOAD_CONST              24 (5)
                714 LOAD_CONST              24 (5)
                716 KW_NAMES                25
                718 PRECALL                  3
                722 CALL                     3
                732 POP_TOP
    
-   642         734 LOAD_NAME               17 (root)
+   614         734 LOAD_NAME               17 (root)
                736 LOAD_METHOD             25 (mainloop)
                758 PRECALL                  0
                762 CALL                     0
                772 POP_TOP
                774 LOAD_CONST              26 (None)
                776 RETURN_VALUE
    
-   619     >>  778 LOAD_CONST              26 (None)
+   591     >>  778 LOAD_CONST              26 (None)
                780 RETURN_VALUE
    consts
       0
       ('Font', 'nametofont')
       ('AdwDrawEngine',)
       code
          argcount  : 0
@@ -2164,15 +2164,15 @@
                   0102f904f504ff02ff
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 4
                flags     : 3
                code
-                  0x97007c019001815a64017c017600900172257c01640119000000000000
+                  0x97007c019001819664017c017600900172257c01640119000000000000
                   0000006402190000000000000000007c005f0000000000000000007c0164
                   01190000000000000000006403190000000000000000007c005f01000000
                   00000000007c016401190000000000000000006404190000000000000000
                   007c005f0200000000000000007c01640119000000000000000000640519
                   0000000000000000007c005f0300000000000000007c0164011900000000
                   00000000006406190000000000000000007c005f0400000000000000007c
                   016401190000000000000000006407190000000000000000007c005f0500
@@ -2184,23 +2184,27 @@
                   0000007c005f0800000000000000007c0164011900000000000000000064
                   09190000000000000000006405190000000000000000007c005f09000000
                   00000000007c016401190000000000000000006409190000000000000000
                   006406190000000000000000007c005f0a00000000000000007c01640119
                   000000000000000000640919000000000000000000640719000000000000
                   0000007c005f0b00000000000000007c0164011900000000000000000064
                   09190000000000000000006408190000000000000000007c005f0c000000
-                  00000000007c017c005f0d000000000000000009007c00a00e0000000000
+                  00000000007c006a0100000000000000007c005f0d00000000000000007c
+                  006a0200000000000000007c005f0e00000000000000007c006a03000000
+                  00000000007c005f0f00000000000000007c006a0500000000000000007c
+                  005f1000000000000000007c006a0600000000000000007c005f11000000
+                  00000000007c017c005f12000000000000000009007c00a0130000000000
                   0000000000000000000000000000006400a6010000ab0100000000000000
-                  000100640053002300741e00000000000000000000240072040100590064
-                  00530077007803590077017c006a0d00000000000000005300
+                  000100640053002300742800000000000000000000240072040100590064
+                  00530077007803590077017c006a1200000000000000005300
                223           0 RESUME                   0
                
                224           2 LOAD_FAST                1 (dict)
                              4 EXTENDED_ARG             1
-                             6 POP_JUMP_FORWARD_IF_NONE   346 (to 700)
+                             6 POP_JUMP_FORWARD_IF_NONE   406 (to 820)
                
                225           8 LOAD_CONST               1 ('text')
                             10 LOAD_FAST                1 (dict)
                             12 CONTAINS_OP              0
                             14 EXTENDED_ARG             1
                             16 POP_JUMP_FORWARD_IF_FALSE   293 (to 604)
                
@@ -2323,72 +2327,97 @@
                            568 LOAD_CONST               9 ('focusin')
                            570 BINARY_SUBSCR
                            580 LOAD_CONST               8 ('bottom_width')
                            582 BINARY_SUBSCR
                            592 LOAD_FAST                0 (self)
                            594 STORE_ATTR              12 (text_focusin_bottom_width)
                
-               245     >>  604 LOAD_FAST                1 (dict)
-                           606 LOAD_FAST                0 (self)
-                           608 STORE_ATTR              13 (_palette)
-               
-               247         618 NOP
-               
-               248         620 LOAD_FAST                0 (self)
-                           622 LOAD_METHOD             14 (_draw)
-                           644 LOAD_CONST               0 (None)
-                           646 PRECALL                  1
-                           650 CALL                     1
-                           660 POP_TOP
-                           662 LOAD_CONST               0 (None)
-                           664 RETURN_VALUE
-                       >>  666 PUSH_EXC_INFO
-               
-               249         668 LOAD_GLOBAL             30 (AttributeError)
-                           680 CHECK_EXC_MATCH
-                           682 POP_JUMP_FORWARD_IF_FALSE     4 (to 692)
-                           684 POP_TOP
-               
-               250         686 POP_EXCEPT
-                           688 LOAD_CONST               0 (None)
-                           690 RETURN_VALUE
-               
-               249     >>  692 RERAISE                  0
-                       >>  694 COPY                     3
-                           696 POP_EXCEPT
-                           698 RERAISE                  1
-               
-               252     >>  700 LOAD_FAST                0 (self)
-                           702 LOAD_ATTR               13 (_palette)
-                           712 RETURN_VALUE
+               245     >>  604 LOAD_FAST                0 (self)
+                           606 LOAD_ATTR                1 (text_back)
+                           616 LOAD_FAST                0 (self)
+                           618 STORE_ATTR              13 (_text_back)
+               
+               246         628 LOAD_FAST                0 (self)
+                           630 LOAD_ATTR                2 (text_border)
+                           640 LOAD_FAST                0 (self)
+                           642 STORE_ATTR              14 (_text_border)
+               
+               247         652 LOAD_FAST                0 (self)
+                           654 LOAD_ATTR                3 (text_text_back)
+                           664 LOAD_FAST                0 (self)
+                           666 STORE_ATTR              15 (_text_text_back)
+               
+               248         676 LOAD_FAST                0 (self)
+                           678 LOAD_ATTR                5 (text_bottom_line)
+                           688 LOAD_FAST                0 (self)
+                           690 STORE_ATTR              16 (_text_bottom_line)
+               
+               249         700 LOAD_FAST                0 (self)
+                           702 LOAD_ATTR                6 (text_bottom_width)
+                           712 LOAD_FAST                0 (self)
+                           714 STORE_ATTR              17 (_text_bottom_width)
+               
+               251         724 LOAD_FAST                1 (dict)
+                           726 LOAD_FAST                0 (self)
+                           728 STORE_ATTR              18 (_palette)
+               
+               253         738 NOP
+               
+               254         740 LOAD_FAST                0 (self)
+                           742 LOAD_METHOD             19 (_draw)
+                           764 LOAD_CONST               0 (None)
+                           766 PRECALL                  1
+                           770 CALL                     1
+                           780 POP_TOP
+                           782 LOAD_CONST               0 (None)
+                           784 RETURN_VALUE
+                       >>  786 PUSH_EXC_INFO
+               
+               255         788 LOAD_GLOBAL             40 (AttributeError)
+                           800 CHECK_EXC_MATCH
+                           802 POP_JUMP_FORWARD_IF_FALSE     4 (to 812)
+                           804 POP_TOP
+               
+               256         806 POP_EXCEPT
+                           808 LOAD_CONST               0 (None)
+                           810 RETURN_VALUE
+               
+               255     >>  812 RERAISE                  0
+                       >>  814 COPY                     3
+                           816 POP_EXCEPT
+                           818 RERAISE                  1
+               
+               258     >>  820 LOAD_FAST                0 (self)
+                           822 LOAD_ATTR               18 (_palette)
+                           832 RETURN_VALUE
                ExceptionTable:
-                 620 to 660 -> 666 [0]
-                 666 to 684 -> 694 [1] lasti
-                 692 to 692 -> 694 [1] lasti
+                 740 to 780 -> 786 [0]
+                 786 to 804 -> 814 [1] lasti
+                 812 to 812 -> 814 [1] lasti
                consts
                   None
                   'text'
                   'padding'
                   'back'
                   'border'
                   'text_back'
                   'border_width'
                   'bottom_line'
                   'bottom_width'
                   'focusin'
-               names      ('text_padding', 'text_back', 'text_border', 'text_text_back', 'text_border_width', 'text_bottom_line', 'text_bottom_width', 'text_focusin_back', 'text_focusin_border', 'text_focusin_text_back', 'text_focusin_border_width', 'text_focusin_bottom_line', 'text_focusin_bottom_width', '_palette', '_draw', 'AttributeError')
+               names      ('text_padding', 'text_back', 'text_border', 'text_text_back', 'text_border_width', 'text_bottom_line', 'text_bottom_width', 'text_focusin_back', 'text_focusin_border', 'text_focusin_text_back', 'text_focusin_border_width', 'text_focusin_bottom_line', 'text_focusin_bottom_width', '_text_back', '_text_border', '_text_text_back', '_text_bottom_line', '_text_bottom_width', '_palette', '_draw', 'AttributeError')
                varnames   ('self', 'dict')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'palette'
                firstlineno 223
                lnotab
                   0x020106010a012602260126012601260226012602140132013201320132
-                  02320132020e0202013001120106ff0803
+                  0232013202180118011801180118020e0202013001120106ff0803
             (None,)
          names      ('__name__', '__module__', '__qualname__', '__init__', 'tbbox', 'compare', 'count', 'debug', 'tdelete', 'dump', 'get', 'tindex', 'tinsert', 'search', 'see', 'undo', 'redo', '_other', '_draw', '_focus', '_focusout', '_click', '_hover', '_hover_release', 'Font', 'font', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
          name       'AdwDrawBasicText'
@@ -2399,118 +2428,118 @@
       'AdwDrawBasicText'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         255           0 RESUME                   0
+         261           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawText')
                        8 STORE_NAME               2 (__qualname__)
          
-         256          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 256>)
+         262          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 262>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawText'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               256           0 RESUME                   0
+               262           0 RESUME                   0
                
-               257           2 LOAD_FAST                0 (self)
+               263           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'default_palette'
-               firstlineno 256
+               firstlineno 262
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
          name       'AdwDrawText'
-         firstlineno 255
+         firstlineno 261
          lnotab 0x0a01
       'AdwDrawText'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         260           0 RESUME                   0
+         266           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawDarkText')
                        8 STORE_NAME               2 (__qualname__)
          
-         261          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 261>)
+         267          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 267>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawDarkText'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               261           0 RESUME                   0
+               267           0 RESUME                   0
                
-               262           2 LOAD_FAST                0 (self)
+               268           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'default_palette'
-               firstlineno 261
+               firstlineno 267
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
          name       'AdwDrawDarkText'
-         firstlineno 260
+         firstlineno 266
          lnotab 0x0a01
       'AdwDrawDarkText'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 3
          flags     : 0
@@ -2518,88 +2547,88 @@
             0x8700970065005a0164005a0288006601640184085a03640284005a0464
             11640484015a05640584005a066411640684015a076411640784015a0864
             11640884015a096411640984015a0a6411640a84015a0b6411640b650c66
             02640c84055a0d640d84005a0e640e84005a0f640f84005a106411880066
             01641084095a11880078015a125300
                        0 MAKE_CELL                0 (__class__)
          
-         266           2 RESUME                   0
+         272           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawBasicRoundText')
                       10 STORE_NAME               2 (__qualname__)
          
-         267          12 LOAD_CLOSURE             0 (__class__)
+         273          12 LOAD_CLOSURE             0 (__class__)
                       14 BUILD_TUPLE              1
-                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\textbox.py", line 267>)
+                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\textbox.py", line 273>)
                       18 MAKE_FUNCTION            8 (closure)
                       20 STORE_NAME               3 (__init__)
          
-         270          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\textbox.py", line 270>)
+         276          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\textbox.py", line 276>)
                       24 MAKE_FUNCTION            0
                       26 STORE_NAME               4 (_other)
          
-         273          28 LOAD_CONST              17 ((None,))
-                      30 LOAD_CONST               4 (<code object border_radius, file "D:\tkadw\tkadw\canvas\textbox.py", line 273>)
+         279          28 LOAD_CONST              17 ((None,))
+                      30 LOAD_CONST               4 (<code object border_radius, file "D:\tkadw\tkadw\canvas\textbox.py", line 279>)
                       32 MAKE_FUNCTION            1 (defaults)
                       34 STORE_NAME               5 (border_radius)
          
-         279          36 LOAD_CONST               5 (<code object _draw, file "D:\tkadw\tkadw\canvas\textbox.py", line 279>)
+         285          36 LOAD_CONST               5 (<code object _draw, file "D:\tkadw\tkadw\canvas\textbox.py", line 285>)
                       38 MAKE_FUNCTION            0
                       40 STORE_NAME               6 (_draw)
          
-         309          42 LOAD_CONST              17 ((None,))
-                      44 LOAD_CONST               6 (<code object _focus, file "D:\tkadw\tkadw\canvas\textbox.py", line 309>)
+         315          42 LOAD_CONST              17 ((None,))
+                      44 LOAD_CONST               6 (<code object _focus, file "D:\tkadw\tkadw\canvas\textbox.py", line 315>)
                       46 MAKE_FUNCTION            1 (defaults)
                       48 STORE_NAME               7 (_focus)
          
-         318          50 LOAD_CONST              17 ((None,))
-                      52 LOAD_CONST               7 (<code object _focusout, file "D:\tkadw\tkadw\canvas\textbox.py", line 318>)
+         324          50 LOAD_CONST              17 ((None,))
+                      52 LOAD_CONST               7 (<code object _focusout, file "D:\tkadw\tkadw\canvas\textbox.py", line 324>)
                       54 MAKE_FUNCTION            1 (defaults)
                       56 STORE_NAME               8 (_focusout)
          
-         327          58 LOAD_CONST              17 ((None,))
-                      60 LOAD_CONST               8 (<code object _click, file "D:\tkadw\tkadw\canvas\textbox.py", line 327>)
+         333          58 LOAD_CONST              17 ((None,))
+                      60 LOAD_CONST               8 (<code object _click, file "D:\tkadw\tkadw\canvas\textbox.py", line 333>)
                       62 MAKE_FUNCTION            1 (defaults)
                       64 STORE_NAME               9 (_click)
          
-         330          66 LOAD_CONST              17 ((None,))
-                      68 LOAD_CONST               9 (<code object _hover, file "D:\tkadw\tkadw\canvas\textbox.py", line 330>)
+         336          66 LOAD_CONST              17 ((None,))
+                      68 LOAD_CONST               9 (<code object _hover, file "D:\tkadw\tkadw\canvas\textbox.py", line 336>)
                       70 MAKE_FUNCTION            1 (defaults)
                       72 STORE_NAME              10 (_hover)
          
-         333          74 LOAD_CONST              17 ((None,))
-                      76 LOAD_CONST              10 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\textbox.py", line 333>)
+         339          74 LOAD_CONST              17 ((None,))
+                      76 LOAD_CONST              10 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\textbox.py", line 339>)
                       78 MAKE_FUNCTION            1 (defaults)
                       80 STORE_NAME              11 (_hover_release)
          
-         344          82 LOAD_CONST              17 ((None,))
+         350          82 LOAD_CONST              17 ((None,))
                       84 LOAD_CONST              11 ('font')
                       86 LOAD_NAME               12 (Font)
                       88 BUILD_TUPLE              2
-                      90 LOAD_CONST              12 (<code object font, file "D:\tkadw\tkadw\canvas\textbox.py", line 344>)
+                      90 LOAD_CONST              12 (<code object font, file "D:\tkadw\tkadw\canvas\textbox.py", line 350>)
                       92 MAKE_FUNCTION            5 (defaults, annotations)
                       94 STORE_NAME              13 (font)
          
-         350          96 LOAD_CONST              13 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 350>)
+         356          96 LOAD_CONST              13 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 356>)
                       98 MAKE_FUNCTION            0
                      100 STORE_NAME              14 (default_palette)
          
-         353         102 LOAD_CONST              14 (<code object palette_light, file "D:\tkadw\tkadw\canvas\textbox.py", line 353>)
+         359         102 LOAD_CONST              14 (<code object palette_light, file "D:\tkadw\tkadw\canvas\textbox.py", line 359>)
                      104 MAKE_FUNCTION            0
                      106 STORE_NAME              15 (palette_light)
          
-         381         108 LOAD_CONST              15 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\textbox.py", line 381>)
+         387         108 LOAD_CONST              15 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\textbox.py", line 387>)
                      110 MAKE_FUNCTION            0
                      112 STORE_NAME              16 (palette_dark)
          
-         409         114 LOAD_CONST              17 ((None,))
+         415         114 LOAD_CONST              17 ((None,))
                      116 LOAD_CLOSURE             0 (__class__)
                      118 BUILD_TUPLE              1
-                     120 LOAD_CONST              16 (<code object palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 409>)
+                     120 LOAD_CONST              16 (<code object palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 415>)
                      122 MAKE_FUNCTION            9 (defaults, closure)
                      124 STORE_NAME              17 (palette)
                      126 LOAD_CLOSURE             0 (__class__)
                      128 COPY                     1
                      130 STORE_NAME              18 (__classcell__)
                      132 RETURN_VALUE
          consts
@@ -2610,17 +2639,17 @@
                stacksize : 5
                flags     : 15
                code
                   0x950197000200740100000000000000000000a6000000ab000000000000
                   0000006a0100000000000000007c0169007c02a4018e01010064005300
                              0 COPY_FREE_VARS           1
                
-               267           2 RESUME                   0
+               273           2 RESUME                   0
                
-               268           4 PUSH_NULL
+               274           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                1 (args)
                             44 BUILD_MAP                0
                             46 LOAD_FAST                2 (kwargs)
@@ -2633,29 +2662,29 @@
                   None
                names      ('super', '__init__')
                varnames   ('self', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '__init__'
-               firstlineno 267
+               firstlineno 273
                lnotab 0x0401
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 5
                flags     : 3
                code
                   0x97007c00a00000000000000000000000000000000000000000007c006a
                   010000000000000000a00200000000000000000000000000000000000000
                   006401a6010000ab0100000000000000006402ac03a6020000ab02000000
                   0000000000010064005300
-               270           0 RESUME                   0
+               276           0 RESUME                   0
                
-               271           2 LOAD_FAST                0 (self)
+               277           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (configure)
                             26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                1 (master)
                             38 LOAD_METHOD              2 (cget)
                             60 LOAD_CONST               1 ('bg')
                             62 PRECALL                  1
                             66 CALL                     1
@@ -2673,48 +2702,48 @@
                   ('background', 'borderwidth')
                names      ('configure', 'master', 'cget')
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_other'
-               firstlineno 270
+               firstlineno 276
                lnotab 0x0201
             None
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               273           0 RESUME                   0
+               279           0 RESUME                   0
                
-               274           2 LOAD_FAST                1 (radius)
+               280           2 LOAD_FAST                1 (radius)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               275           6 LOAD_FAST                0 (self)
+               281           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (button_radius)
                             18 RETURN_VALUE
                
-               277     >>   20 LOAD_FAST                1 (radius)
+               283     >>   20 LOAD_FAST                1 (radius)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (button_radius)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('button_radius',)
                varnames   ('self', 'radius')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'border_radius'
-               firstlineno 273
+               firstlineno 279
                lnotab 0x020104010e02
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 10
                flags     : 3
                code
@@ -2750,27 +2779,27 @@
                   000000000000000000000000007c006a100000000000000000a6010000ab
                   01000000000000000001007c00a011000000000000000000000000000000
                   00000000007c006a1000000000000000007c006a0c0000000000000000a6
                   020000ab02000000000000000001007c006a0b0000000000000000a01200
                   000000000000000000000000000000000000007c006a0700000000000000
                   007c006a1300000000000000007c006a130000000000000000ac0ba60300
                   00ab030000000000000000010064005300
-               279           0 RESUME                   0
+               285           0 RESUME                   0
                
-               280           2 LOAD_FAST                0 (self)
+               286           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               282          44 LOAD_FAST                0 (self)
+               288          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_round_rect2)
                
-               283          68 LOAD_CONST               2 (2)
+               289          68 LOAD_CONST               2 (2)
                             70 LOAD_CONST               2 (2)
                             72 LOAD_FAST                0 (self)
                             74 LOAD_METHOD              2 (winfo_width)
                             96 PRECALL                  0
                            100 CALL                     0
                            110 LOAD_CONST               3 (3)
                            112 BINARY_OP               10 (-)
@@ -2779,159 +2808,159 @@
                            140 PRECALL                  0
                            144 CALL                     0
                            154 LOAD_CONST               3 (3)
                            156 BINARY_OP               10 (-)
                            160 LOAD_FAST                0 (self)
                            162 LOAD_ATTR                4 (text_radius)
                
-               284         172 LOAD_FAST                0 (self)
+               290         172 LOAD_FAST                0 (self)
                            174 LOAD_ATTR                5 (text_border_width)
                
-               285         184 LOAD_FAST                0 (self)
+               291         184 LOAD_FAST                0 (self)
                            186 LOAD_ATTR                6 (_text_border)
                            196 LOAD_FAST                0 (self)
                            198 LOAD_ATTR                7 (_text_back)
                
-               282         208 KW_NAMES                 4
+               288         208 KW_NAMES                 4
                            210 PRECALL                  8
                            214 CALL                     8
                            224 LOAD_FAST                0 (self)
                            226 STORE_ATTR               8 (text_frame)
                
-               288         236 LOAD_FAST                0 (self)
+               294         236 LOAD_FAST                0 (self)
                            238 LOAD_METHOD              9 (create_window)
                
-               289         260 LOAD_FAST                0 (self)
+               295         260 LOAD_FAST                0 (self)
                            262 LOAD_METHOD              2 (winfo_width)
                            284 PRECALL                  0
                            288 CALL                     0
                            298 LOAD_CONST               2 (2)
                            300 BINARY_OP               11 (/)
                            304 LOAD_FAST                0 (self)
                            306 LOAD_METHOD              3 (winfo_height)
                            328 PRECALL                  0
                            332 CALL                     0
                            342 LOAD_CONST               2 (2)
                            344 BINARY_OP               11 (/)
                
-               290         348 LOAD_FAST                0 (self)
+               296         348 LOAD_FAST                0 (self)
                            350 LOAD_METHOD              2 (winfo_width)
                            372 PRECALL                  0
                            376 CALL                     0
                            386 LOAD_FAST                0 (self)
                            388 LOAD_ATTR                5 (text_border_width)
                            398 BINARY_OP               10 (-)
                            402 LOAD_CONST               5 (5)
                            404 BINARY_OP               10 (-)
                            408 LOAD_FAST                0 (self)
                            410 LOAD_ATTR               10 (text_padding)
                            420 LOAD_CONST               6 (0)
                            422 BINARY_SUBSCR
                            432 BINARY_OP               10 (-)
                
-               291         436 LOAD_FAST                0 (self)
+               297         436 LOAD_FAST                0 (self)
                            438 LOAD_METHOD              3 (winfo_height)
                            460 PRECALL                  0
                            464 CALL                     0
                            474 LOAD_FAST                0 (self)
                            476 LOAD_ATTR                5 (text_border_width)
                            486 BINARY_OP               10 (-)
                            490 LOAD_CONST               5 (5)
                            492 BINARY_OP               10 (-)
                            496 LOAD_FAST                0 (self)
                            498 LOAD_ATTR               10 (text_padding)
                            508 LOAD_CONST               7 (1)
                            510 BINARY_SUBSCR
                            520 BINARY_OP               10 (-)
                
-               292         524 LOAD_FAST                0 (self)
+               298         524 LOAD_FAST                0 (self)
                            526 LOAD_ATTR               11 (text)
                
-               288         536 KW_NAMES                 8
+               294         536 KW_NAMES                 8
                            538 PRECALL                  5
                            542 CALL                     5
                            552 LOAD_FAST                0 (self)
                            554 STORE_ATTR              12 (text_text)
                
-               295         564 LOAD_FAST                0 (self)
+               301         564 LOAD_FAST                0 (self)
                            566 LOAD_METHOD             13 (create_rectangle)
                            588 LOAD_CONST               3 (3)
                            590 LOAD_FAST                0 (self)
                            592 LOAD_ATTR                4 (text_radius)
                            602 LOAD_CONST               2 (2)
                            604 BINARY_OP               11 (/)
                            608 BINARY_OP                0 (+)
                
-               296         612 LOAD_FAST                0 (self)
+               302         612 LOAD_FAST                0 (self)
                            614 LOAD_METHOD              3 (winfo_height)
                            636 PRECALL                  0
                            640 CALL                     0
                            650 LOAD_FAST                0 (self)
                            652 LOAD_ATTR               14 (_text_bottom_width)
                            662 BINARY_OP               10 (-)
                            666 LOAD_CONST               3 (3)
                            668 BINARY_OP               10 (-)
                
-               297         672 LOAD_FAST                0 (self)
+               303         672 LOAD_FAST                0 (self)
                            674 LOAD_METHOD              2 (winfo_width)
                            696 PRECALL                  0
                            700 CALL                     0
                            710 LOAD_CONST               3 (3)
                            712 BINARY_OP               10 (-)
                            716 LOAD_FAST                0 (self)
                            718 LOAD_ATTR                4 (text_radius)
                            728 LOAD_CONST               2 (2)
                            730 BINARY_OP               11 (/)
                            734 BINARY_OP               10 (-)
                
-               298         738 LOAD_FAST                0 (self)
+               304         738 LOAD_FAST                0 (self)
                            740 LOAD_METHOD              3 (winfo_height)
                            762 PRECALL                  0
                            766 CALL                     0
                            776 LOAD_CONST               9 (3.5)
                            778 BINARY_OP               10 (-)
                
-               299         782 LOAD_FAST                0 (self)
+               305         782 LOAD_FAST                0 (self)
                            784 LOAD_ATTR               15 (_text_bottom_line)
                            794 LOAD_FAST                0 (self)
                            796 LOAD_ATTR               15 (_text_bottom_line)
                
-               300         806 LOAD_CONST               6 (0)
+               306         806 LOAD_CONST               6 (0)
                
-               295         808 KW_NAMES                10
+               301         808 KW_NAMES                10
                            810 PRECALL                  7
                            814 CALL                     7
                            824 LOAD_FAST                0 (self)
                            826 STORE_ATTR              16 (text_bottom)
                
-               302         836 LOAD_FAST                0 (self)
+               308         836 LOAD_FAST                0 (self)
                            838 LOAD_ATTR               14 (_text_bottom_width)
                            848 LOAD_CONST               6 (0)
                            850 COMPARE_OP               2 (==)
                            856 POP_JUMP_FORWARD_IF_FALSE    26 (to 910)
                
-               303         858 LOAD_FAST                0 (self)
+               309         858 LOAD_FAST                0 (self)
                            860 LOAD_METHOD              0 (delete)
                            882 LOAD_FAST                0 (self)
                            884 LOAD_ATTR               16 (text_bottom)
                            894 PRECALL                  1
                            898 CALL                     1
                            908 POP_TOP
                
-               305     >>  910 LOAD_FAST                0 (self)
+               311     >>  910 LOAD_FAST                0 (self)
                            912 LOAD_METHOD             17 (tag_raise)
                            934 LOAD_FAST                0 (self)
                            936 LOAD_ATTR               16 (text_bottom)
                            946 LOAD_FAST                0 (self)
                            948 LOAD_ATTR               12 (text_text)
                            958 PRECALL                  2
                            962 CALL                     2
                            972 POP_TOP
                
-               307         974 LOAD_FAST                0 (self)
+               313         974 LOAD_FAST                0 (self)
                            976 LOAD_ATTR               11 (text)
                            986 LOAD_METHOD             18 (configure)
                           1008 LOAD_FAST                0 (self)
                           1010 LOAD_ATTR                7 (_text_back)
                           1020 LOAD_FAST                0 (self)
                           1022 LOAD_ATTR               19 (_text_text_back)
                           1032 LOAD_FAST                0 (self)
@@ -2957,15 +2986,15 @@
                   ('background', 'foreground', 'insertbackground')
                names      ('delete', 'create_round_rect2', 'winfo_width', 'winfo_height', 'text_radius', 'text_border_width', '_text_border', '_text_back', 'text_frame', 'create_window', 'text_padding', 'text', 'text_text', 'create_rectangle', '_text_bottom_width', '_text_bottom_line', 'text_bottom', 'tag_raise', 'configure', '_text_text_back')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_draw'
-               firstlineno 279
+               firstlineno 285
                lnotab
                   0x02012a02180168010c0118fd1c0618015801580158010cfc1c0730013c
                   0142012c01180102fb1c07160134024002
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
@@ -2973,42 +3002,42 @@
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c00a00a00000000000000000000000000000000000000006400a6
                   010000ab010000000000000000010064005300
-               309           0 RESUME                   0
+               315           0 RESUME                   0
                
-               310           2 LOAD_FAST                0 (self)
+               316           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (text_focusin_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_text_back)
                
-               311          26 LOAD_FAST                0 (self)
+               317          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (text_focusin_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_text_border)
                
-               312          50 LOAD_FAST                0 (self)
+               318          50 LOAD_FAST                0 (self)
                             52 LOAD_ATTR                4 (text_focusin_text_back)
                             62 LOAD_FAST                0 (self)
                             64 STORE_ATTR               5 (_text_text_back)
                
-               313          74 LOAD_FAST                0 (self)
+               319          74 LOAD_FAST                0 (self)
                             76 LOAD_ATTR                6 (text_focusin_bottom_line)
                             86 LOAD_FAST                0 (self)
                             88 STORE_ATTR               7 (_text_bottom_line)
                
-               314          98 LOAD_FAST                0 (self)
+               320          98 LOAD_FAST                0 (self)
                            100 LOAD_ATTR                8 (text_focusin_bottom_width)
                            110 LOAD_FAST                0 (self)
                            112 STORE_ATTR               9 (_text_bottom_width)
                
-               316         122 LOAD_FAST                0 (self)
+               322         122 LOAD_FAST                0 (self)
                            124 LOAD_METHOD             10 (_draw)
                            146 LOAD_CONST               0 (None)
                            148 PRECALL                  1
                            152 CALL                     1
                            162 POP_TOP
                            164 LOAD_CONST               0 (None)
                            166 RETURN_VALUE
@@ -3016,56 +3045,56 @@
                   None
                names      ('text_focusin_back', '_text_back', 'text_focusin_border', '_text_border', 'text_focusin_text_back', '_text_text_back', 'text_focusin_bottom_line', '_text_bottom_line', 'text_focusin_bottom_width', '_text_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_focus'
-               firstlineno 309
+               firstlineno 315
                lnotab 0x020118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c00a00a00000000000000000000000000000000000000006400a6
                   010000ab010000000000000000010064005300
-               318           0 RESUME                   0
+               324           0 RESUME                   0
                
-               319           2 LOAD_FAST                0 (self)
+               325           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (text_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_text_back)
                
-               320          26 LOAD_FAST                0 (self)
+               326          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (text_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_text_border)
                
-               321          50 LOAD_FAST                0 (self)
+               327          50 LOAD_FAST                0 (self)
                             52 LOAD_ATTR                4 (text_text_back)
                             62 LOAD_FAST                0 (self)
                             64 STORE_ATTR               5 (_text_text_back)
                
-               322          74 LOAD_FAST                0 (self)
+               328          74 LOAD_FAST                0 (self)
                             76 LOAD_ATTR                6 (text_bottom_line)
                             86 LOAD_FAST                0 (self)
                             88 STORE_ATTR               7 (_text_bottom_line)
                
-               323          98 LOAD_FAST                0 (self)
+               329          98 LOAD_FAST                0 (self)
                            100 LOAD_ATTR                8 (text_bottom_width)
                            110 LOAD_FAST                0 (self)
                            112 STORE_ATTR               9 (_text_bottom_width)
                
-               325         122 LOAD_FAST                0 (self)
+               331         122 LOAD_FAST                0 (self)
                            124 LOAD_METHOD             10 (_draw)
                            146 LOAD_CONST               0 (None)
                            148 PRECALL                  1
                            152 CALL                     1
                            162 POP_TOP
                            164 LOAD_CONST               0 (None)
                            166 RETURN_VALUE
@@ -3073,66 +3102,66 @@
                   None
                names      ('text_back', '_text_back', 'text_border', '_text_border', 'text_text_back', '_text_text_back', 'text_bottom_line', '_text_bottom_line', 'text_bottom_width', '_text_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_focusout'
-               firstlineno 318
+               firstlineno 324
                lnotab 0x020118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               327           0 RESUME                   0
+               333           0 RESUME                   0
                
-               328           2 LOAD_FAST                0 (self)
+               334           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_set)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('focus_set',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_click'
-               firstlineno 327
+               firstlineno 333
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code 0x970064017c005f00000000000000000064005300
-               330           0 RESUME                   0
+               336           0 RESUME                   0
                
-               331           2 LOAD_CONST               1 (True)
+               337           2 LOAD_CONST               1 (True)
                              4 LOAD_FAST                0 (self)
                              6 STORE_ATTR               0 (hover)
                             16 LOAD_CONST               0 (None)
                             18 RETURN_VALUE
                consts
                   None
                   True
                names      ('hover',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_hover'
-               firstlineno 330
+               firstlineno 336
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
@@ -3140,186 +3169,186 @@
                   00ab000000000000000000735a64017c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c006a0a00000000000000007c005f0b00000000000000007c00a0
                   0c00000000000000000000000000000000000000006400a6010000ab0100
                   0000000000000001006400530064005300
-               333           0 RESUME                   0
+               339           0 RESUME                   0
                
-               334           2 LOAD_FAST                0 (self)
+               340           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_get)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_JUMP_FORWARD_IF_TRUE    90 (to 222)
                
-               335          42 LOAD_CONST               1 (False)
+               341          42 LOAD_CONST               1 (False)
                             44 LOAD_FAST                0 (self)
                             46 STORE_ATTR               1 (hover)
                
-               336          56 LOAD_FAST                0 (self)
+               342          56 LOAD_FAST                0 (self)
                             58 LOAD_ATTR                2 (text_back)
                             68 LOAD_FAST                0 (self)
                             70 STORE_ATTR               3 (_text_back)
                
-               337          80 LOAD_FAST                0 (self)
+               343          80 LOAD_FAST                0 (self)
                             82 LOAD_ATTR                4 (text_border)
                             92 LOAD_FAST                0 (self)
                             94 STORE_ATTR               5 (_text_border)
                
-               338         104 LOAD_FAST                0 (self)
+               344         104 LOAD_FAST                0 (self)
                            106 LOAD_ATTR                6 (text_text_back)
                            116 LOAD_FAST                0 (self)
                            118 STORE_ATTR               7 (_text_text_back)
                
-               339         128 LOAD_FAST                0 (self)
+               345         128 LOAD_FAST                0 (self)
                            130 LOAD_ATTR                8 (text_bottom_line)
                            140 LOAD_FAST                0 (self)
                            142 STORE_ATTR               9 (_text_bottom_line)
                
-               340         152 LOAD_FAST                0 (self)
+               346         152 LOAD_FAST                0 (self)
                            154 LOAD_ATTR               10 (text_bottom_width)
                            164 LOAD_FAST                0 (self)
                            166 STORE_ATTR              11 (_text_bottom_width)
                
-               342         176 LOAD_FAST                0 (self)
+               348         176 LOAD_FAST                0 (self)
                            178 LOAD_METHOD             12 (_draw)
                            200 LOAD_CONST               0 (None)
                            202 PRECALL                  1
                            206 CALL                     1
                            216 POP_TOP
                            218 LOAD_CONST               0 (None)
                            220 RETURN_VALUE
                
-               334     >>  222 LOAD_CONST               0 (None)
+               340     >>  222 LOAD_CONST               0 (None)
                            224 RETURN_VALUE
                consts
                   None
                   False
                names      ('focus_get', 'hover', 'text_back', '_text_back', 'text_border', '_text_border', 'text_text_back', '_text_text_back', 'text_bottom_line', '_text_bottom_line', 'text_bottom_width', '_text_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_hover_release'
-               firstlineno 333
+               firstlineno 339
                lnotab 0x020128010e01180118011801180118022ef8
             'font'
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               344           0 RESUME                   0
+               350           0 RESUME                   0
                
-               345           2 LOAD_FAST                1 (font)
+               351           2 LOAD_FAST                1 (font)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               346           6 LOAD_FAST                0 (self)
+               352           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (text_text_font)
                             18 RETURN_VALUE
                
-               348     >>   20 LOAD_FAST                1 (font)
+               354     >>   20 LOAD_FAST                1 (font)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (text_text_font)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('text_text_font',)
                varnames   ('self', 'font')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'font'
-               firstlineno 344
+               firstlineno 350
                lnotab 0x020104010e02
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               350           0 RESUME                   0
+               356           0 RESUME                   0
                
-               351           2 LOAD_FAST                0 (self)
+               357           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'default_palette'
-               firstlineno 350
+               firstlineno 356
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 18
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   0264036404640564066407640564086409640a640b6407640c640d640e9c
                   06640f9c096901a6010000ab010000000000000000010064005300
-               353           0 RESUME                   0
+               359           0 RESUME                   0
                
-               354           2 LOAD_FAST                0 (self)
+               360           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               356          26 LOAD_CONST               1 ('text')
+               362          26 LOAD_CONST               1 ('text')
                
-               357          28 LOAD_CONST               2 (6)
+               363          28 LOAD_CONST               2 (6)
                
-               358          30 LOAD_CONST               3 ((3, 4))
+               364          30 LOAD_CONST               3 ((3, 4))
                
-               360          32 LOAD_CONST               4 ('#fdfdfd')
+               366          32 LOAD_CONST               4 ('#fdfdfd')
                
-               361          34 LOAD_CONST               5 ('#eaeaea')
+               367          34 LOAD_CONST               5 ('#eaeaea')
                
-               362          36 LOAD_CONST               6 ('#5f5f5f')
+               368          36 LOAD_CONST               6 ('#5f5f5f')
                
-               363          38 LOAD_CONST               7 (1)
+               369          38 LOAD_CONST               7 (1)
                
-               365          40 LOAD_CONST               5 ('#eaeaea')
+               371          40 LOAD_CONST               5 ('#eaeaea')
                
-               366          42 LOAD_CONST               8 (0)
+               372          42 LOAD_CONST               8 (0)
                
-               369          44 LOAD_CONST               9 ('#f9f9f9')
+               375          44 LOAD_CONST               9 ('#f9f9f9')
                
-               370          46 LOAD_CONST              10 ('#e2e2e2')
+               376          46 LOAD_CONST              10 ('#e2e2e2')
                
-               371          48 LOAD_CONST              11 ('#1a1a1a')
+               377          48 LOAD_CONST              11 ('#1a1a1a')
                
-               372          50 LOAD_CONST               7 (1)
+               378          50 LOAD_CONST               7 (1)
                
-               374          52 LOAD_CONST              12 ('#185fb4')
+               380          52 LOAD_CONST              12 ('#185fb4')
                
-               375          54 LOAD_CONST              13 (2)
+               381          54 LOAD_CONST              13 (2)
                
-               368          56 LOAD_CONST              14 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
+               374          56 LOAD_CONST              14 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
                             58 BUILD_CONST_KEY_MAP      6
                
-               356          60 LOAD_CONST              15 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
+               362          60 LOAD_CONST              15 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
                             62 BUILD_CONST_KEY_MAP      9
                
-               355          64 BUILD_MAP                1
+               361          64 BUILD_MAP                1
                
-               354          66 PRECALL                  1
+               360          66 PRECALL                  1
                             70 CALL                     1
                             80 POP_TOP
                             82 LOAD_CONST               0 (None)
                             84 RETURN_VALUE
                consts
                   None
                   'text'
@@ -3339,71 +3368,71 @@
                   ('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'palette_light'
-               firstlineno 353
+               firstlineno 359
                lnotab
                   0x0201180202010201020202010201020102020201020302010201020102
                   02020102f904f404ff02ff
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 18
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
                   026403640464056406640764086409640a640564086407640b640c640d9c
                   06640e9c096901a6010000ab010000000000000000010064005300
-               381           0 RESUME                   0
+               387           0 RESUME                   0
                
-               382           2 LOAD_FAST                0 (self)
+               388           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               384          26 LOAD_CONST               1 ('text')
+               390          26 LOAD_CONST               1 ('text')
                
-               385          28 LOAD_CONST               2 (6)
+               391          28 LOAD_CONST               2 (6)
                
-               386          30 LOAD_CONST               3 ((3, 4))
+               392          30 LOAD_CONST               3 ((3, 4))
                
-               388          32 LOAD_CONST               4 ('#353535')
+               394          32 LOAD_CONST               4 ('#353535')
                
-               389          34 LOAD_CONST               5 ('#454545')
+               395          34 LOAD_CONST               5 ('#454545')
                
-               390          36 LOAD_CONST               6 ('#cecece')
+               396          36 LOAD_CONST               6 ('#cecece')
                
-               391          38 LOAD_CONST               7 (1)
+               397          38 LOAD_CONST               7 (1)
                
-               393          40 LOAD_CONST               8 ('#ffffff')
+               399          40 LOAD_CONST               8 ('#ffffff')
                
-               394          42 LOAD_CONST               9 (0)
+               400          42 LOAD_CONST               9 (0)
                
-               397          44 LOAD_CONST              10 ('#2f2f2f')
+               403          44 LOAD_CONST              10 ('#2f2f2f')
                
-               398          46 LOAD_CONST               5 ('#454545')
+               404          46 LOAD_CONST               5 ('#454545')
                
-               399          48 LOAD_CONST               8 ('#ffffff')
+               405          48 LOAD_CONST               8 ('#ffffff')
                
-               400          50 LOAD_CONST               7 (1)
+               406          50 LOAD_CONST               7 (1)
                
-               402          52 LOAD_CONST              11 ('#4cc2ff')
+               408          52 LOAD_CONST              11 ('#4cc2ff')
                
-               403          54 LOAD_CONST              12 (2)
+               409          54 LOAD_CONST              12 (2)
                
-               396          56 LOAD_CONST              13 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
+               402          56 LOAD_CONST              13 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
                             58 BUILD_CONST_KEY_MAP      6
                
-               384          60 LOAD_CONST              14 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
+               390          60 LOAD_CONST              14 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
                             62 BUILD_CONST_KEY_MAP      9
                
-               383          64 BUILD_MAP                1
+               389          64 BUILD_MAP                1
                
-               382          66 PRECALL                  1
+               388          66 PRECALL                  1
                             70 CALL                     1
                             80 POP_TOP
                             82 LOAD_CONST               0 (None)
                             84 RETURN_VALUE
                consts
                   None
                   'text'
@@ -3422,15 +3451,15 @@
                   ('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'palette_dark'
-               firstlineno 381
+               firstlineno 387
                lnotab
                   0x0201180202010201020202010201020102020201020302010201020102
                   02020102f904f404ff02ff
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
@@ -3439,282 +3468,277 @@
                   0x95019700740100000000000000000000a6000000ab0000000000000000
                   00a00100000000000000000000000000000000000000007c01a6010000ab
                   010000000000000000010064017c01760072157c01640119000000000000
                   0000006402190000000000000000007c005f020000000000000000640053
                   0064005300
                              0 COPY_FREE_VARS           1
                
-               409           2 RESUME                   0
+               415           2 RESUME                   0
                
-               410           4 LOAD_GLOBAL              1 (NULL + super)
+               416           4 LOAD_GLOBAL              1 (NULL + super)
                             16 PRECALL                  0
                             20 CALL                     0
                             30 LOAD_METHOD              1 (palette)
                             52 LOAD_FAST                1 (dict)
                             54 PRECALL                  1
                             58 CALL                     1
                             68 POP_TOP
                
-               411          70 LOAD_CONST               1 ('text')
+               417          70 LOAD_CONST               1 ('text')
                             72 LOAD_FAST                1 (dict)
                             74 CONTAINS_OP              0
                             76 POP_JUMP_FORWARD_IF_FALSE    21 (to 120)
                
-               412          78 LOAD_FAST                1 (dict)
+               418          78 LOAD_FAST                1 (dict)
                             80 LOAD_CONST               1 ('text')
                             82 BINARY_SUBSCR
                             92 LOAD_CONST               2 ('radius')
                             94 BINARY_SUBSCR
                            104 LOAD_FAST                0 (self)
                            106 STORE_ATTR               2 (text_radius)
                            116 LOAD_CONST               0 (None)
                            118 RETURN_VALUE
                
-               411     >>  120 LOAD_CONST               0 (None)
+               417     >>  120 LOAD_CONST               0 (None)
                            122 RETURN_VALUE
                consts
                   None
                   'text'
                   'radius'
                names      ('super', 'palette', 'text_radius')
                varnames   ('self', 'dict')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'palette'
-               firstlineno 409
+               firstlineno 415
                lnotab 0x0401420108012aff
             (None,)
          names      ('__name__', '__module__', '__qualname__', '__init__', '_other', 'border_radius', '_draw', '_focus', '_focusout', '_click', '_hover', '_hover_release', 'Font', 'font', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
          name       'AdwDrawBasicRoundText'
-         firstlineno 266
+         firstlineno 272
          lnotab 0x0c010a0306030806061e0809080908030803080b0e060603061c061c
       'AdwDrawBasicRoundText'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         415           0 RESUME                   0
+         421           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundText')
                        8 STORE_NAME               2 (__qualname__)
          
-         416          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 416>)
+         422          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 422>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundText'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               416           0 RESUME                   0
+               422           0 RESUME                   0
                
-               417           2 LOAD_FAST                0 (self)
+               423           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'default_palette'
-               firstlineno 416
+               firstlineno 422
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
          name       'AdwDrawRoundText'
-         firstlineno 415
+         firstlineno 421
          lnotab 0x0a01
       'AdwDrawRoundText'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         420           0 RESUME                   0
+         426           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundDarkText')
                        8 STORE_NAME               2 (__qualname__)
          
-         421          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 421>)
+         427          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 427>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundDarkText'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               421           0 RESUME                   0
+               427           0 RESUME                   0
                
-               422           2 LOAD_FAST                0 (self)
+               428           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'default_palette'
-               firstlineno 421
+               firstlineno 427
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
          name       'AdwDrawRoundDarkText'
-         firstlineno 420
+         firstlineno 426
          lnotab 0x0a01
       'AdwDrawRoundDarkText'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 3
          flags     : 0
          code
             0x8700970065005a0164005a0288006601640184085a03640284005a0464
-            11640484015a05640584005a066411640684015a076411640784015a0864
-            11640884015a096411640984015a0a6411640a84015a0b6411640b650c66
-            02640c84055a0d640d84005a0e640e84005a0f640f84005a106411641084
-            015a11880078015a125300
+            10640484015a05640584005a066410640684015a076410640784015a0864
+            10640884015a096410640984015a0a6410640a84015a0b6410640b650c66
+            02640c84055a0d640d84005a0e640e84005a0f640f84005a10880078015a
+            115300
                        0 MAKE_CELL                0 (__class__)
          
-         425           2 RESUME                   0
+         431           2 RESUME                   0
                        4 LOAD_NAME                0 (__name__)
                        6 STORE_NAME               1 (__module__)
                        8 LOAD_CONST               0 ('AdwDrawBasicRoundText3')
                       10 STORE_NAME               2 (__qualname__)
          
-         426          12 LOAD_CLOSURE             0 (__class__)
+         432          12 LOAD_CLOSURE             0 (__class__)
                       14 BUILD_TUPLE              1
-                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\textbox.py", line 426>)
+                      16 LOAD_CONST               1 (<code object __init__, file "D:\tkadw\tkadw\canvas\textbox.py", line 432>)
                       18 MAKE_FUNCTION            8 (closure)
                       20 STORE_NAME               3 (__init__)
          
-         429          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\textbox.py", line 429>)
+         435          22 LOAD_CONST               2 (<code object _other, file "D:\tkadw\tkadw\canvas\textbox.py", line 435>)
                       24 MAKE_FUNCTION            0
                       26 STORE_NAME               4 (_other)
          
-         432          28 LOAD_CONST              17 ((None,))
-                      30 LOAD_CONST               4 (<code object border_radius, file "D:\tkadw\tkadw\canvas\textbox.py", line 432>)
+         438          28 LOAD_CONST              16 ((None,))
+                      30 LOAD_CONST               4 (<code object border_radius, file "D:\tkadw\tkadw\canvas\textbox.py", line 438>)
                       32 MAKE_FUNCTION            1 (defaults)
                       34 STORE_NAME               5 (border_radius)
          
-         438          36 LOAD_CONST               5 (<code object _draw, file "D:\tkadw\tkadw\canvas\textbox.py", line 438>)
+         444          36 LOAD_CONST               5 (<code object _draw, file "D:\tkadw\tkadw\canvas\textbox.py", line 444>)
                       38 MAKE_FUNCTION            0
                       40 STORE_NAME               6 (_draw)
          
-         474          42 LOAD_CONST              17 ((None,))
-                      44 LOAD_CONST               6 (<code object _focus, file "D:\tkadw\tkadw\canvas\textbox.py", line 474>)
+         480          42 LOAD_CONST              16 ((None,))
+                      44 LOAD_CONST               6 (<code object _focus, file "D:\tkadw\tkadw\canvas\textbox.py", line 480>)
                       46 MAKE_FUNCTION            1 (defaults)
                       48 STORE_NAME               7 (_focus)
          
-         483          50 LOAD_CONST              17 ((None,))
-                      52 LOAD_CONST               7 (<code object _focusout, file "D:\tkadw\tkadw\canvas\textbox.py", line 483>)
+         489          50 LOAD_CONST              16 ((None,))
+                      52 LOAD_CONST               7 (<code object _focusout, file "D:\tkadw\tkadw\canvas\textbox.py", line 489>)
                       54 MAKE_FUNCTION            1 (defaults)
                       56 STORE_NAME               8 (_focusout)
          
-         492          58 LOAD_CONST              17 ((None,))
-                      60 LOAD_CONST               8 (<code object _click, file "D:\tkadw\tkadw\canvas\textbox.py", line 492>)
+         498          58 LOAD_CONST              16 ((None,))
+                      60 LOAD_CONST               8 (<code object _click, file "D:\tkadw\tkadw\canvas\textbox.py", line 498>)
                       62 MAKE_FUNCTION            1 (defaults)
                       64 STORE_NAME               9 (_click)
          
-         495          66 LOAD_CONST              17 ((None,))
-                      68 LOAD_CONST               9 (<code object _hover, file "D:\tkadw\tkadw\canvas\textbox.py", line 495>)
+         501          66 LOAD_CONST              16 ((None,))
+                      68 LOAD_CONST               9 (<code object _hover, file "D:\tkadw\tkadw\canvas\textbox.py", line 501>)
                       70 MAKE_FUNCTION            1 (defaults)
                       72 STORE_NAME              10 (_hover)
          
-         498          74 LOAD_CONST              17 ((None,))
-                      76 LOAD_CONST              10 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\textbox.py", line 498>)
+         504          74 LOAD_CONST              16 ((None,))
+                      76 LOAD_CONST              10 (<code object _hover_release, file "D:\tkadw\tkadw\canvas\textbox.py", line 504>)
                       78 MAKE_FUNCTION            1 (defaults)
                       80 STORE_NAME              11 (_hover_release)
          
-         509          82 LOAD_CONST              17 ((None,))
+         515          82 LOAD_CONST              16 ((None,))
                       84 LOAD_CONST              11 ('font')
                       86 LOAD_NAME               12 (Font)
                       88 BUILD_TUPLE              2
-                      90 LOAD_CONST              12 (<code object font, file "D:\tkadw\tkadw\canvas\textbox.py", line 509>)
+                      90 LOAD_CONST              12 (<code object font, file "D:\tkadw\tkadw\canvas\textbox.py", line 515>)
                       92 MAKE_FUNCTION            5 (defaults, annotations)
                       94 STORE_NAME              13 (font)
          
-         515          96 LOAD_CONST              13 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 515>)
+         521          96 LOAD_CONST              13 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 521>)
                       98 MAKE_FUNCTION            0
                      100 STORE_NAME              14 (default_palette)
          
-         518         102 LOAD_CONST              14 (<code object palette_light, file "D:\tkadw\tkadw\canvas\textbox.py", line 518>)
+         524         102 LOAD_CONST              14 (<code object palette_light, file "D:\tkadw\tkadw\canvas\textbox.py", line 524>)
                      104 MAKE_FUNCTION            0
                      106 STORE_NAME              15 (palette_light)
          
-         542         108 LOAD_CONST              15 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\textbox.py", line 542>)
+         552         108 LOAD_CONST              15 (<code object palette_dark, file "D:\tkadw\tkadw\canvas\textbox.py", line 552>)
                      110 MAKE_FUNCTION            0
                      112 STORE_NAME              16 (palette_dark)
-         
-         566         114 LOAD_CONST              17 ((None,))
-                     116 LOAD_CONST              16 (<code object palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 566>)
-                     118 MAKE_FUNCTION            1 (defaults)
-                     120 STORE_NAME              17 (palette)
-                     122 LOAD_CLOSURE             0 (__class__)
-                     124 COPY                     1
-                     126 STORE_NAME              18 (__classcell__)
-                     128 RETURN_VALUE
+                     114 LOAD_CLOSURE             0 (__class__)
+                     116 COPY                     1
+                     118 STORE_NAME              17 (__classcell__)
+                     120 RETURN_VALUE
          consts
             'AdwDrawBasicRoundText3'
             code
                argcount  : 1
                nlocals   : 3
                stacksize : 5
                flags     : 15
                code
                   0x950197000200740100000000000000000000a6000000ab000000000000
                   0000006a0100000000000000007c0169007c02a4018e01010064005300
                              0 COPY_FREE_VARS           1
                
-               426           2 RESUME                   0
+               432           2 RESUME                   0
                
-               427           4 PUSH_NULL
+               433           4 PUSH_NULL
                              6 LOAD_GLOBAL              1 (NULL + super)
                             18 PRECALL                  0
                             22 CALL                     0
                             32 LOAD_ATTR                1 (__init__)
                             42 LOAD_FAST                1 (args)
                             44 BUILD_MAP                0
                             46 LOAD_FAST                2 (kwargs)
@@ -3727,29 +3751,29 @@
                   None
                names      ('super', '__init__')
                varnames   ('self', 'args', 'kwargs')
                freevars   ('__class__',)
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '__init__'
-               firstlineno 426
+               firstlineno 432
                lnotab 0x0401
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 5
                flags     : 3
                code
                   0x97007c00a00000000000000000000000000000000000000000007c006a
                   010000000000000000a00200000000000000000000000000000000000000
                   006401a6010000ab0100000000000000006402ac03a6020000ab02000000
                   0000000000010064005300
-               429           0 RESUME                   0
+               435           0 RESUME                   0
                
-               430           2 LOAD_FAST                0 (self)
+               436           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (configure)
                             26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                1 (master)
                             38 LOAD_METHOD              2 (cget)
                             60 LOAD_CONST               1 ('bg')
                             62 PRECALL                  1
                             66 CALL                     1
@@ -3767,48 +3791,48 @@
                   ('background', 'borderwidth')
                names      ('configure', 'master', 'cget')
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_other'
-               firstlineno 429
+               firstlineno 435
                lnotab 0x0201
             None
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               432           0 RESUME                   0
+               438           0 RESUME                   0
                
-               433           2 LOAD_FAST                1 (radius)
+               439           2 LOAD_FAST                1 (radius)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               434           6 LOAD_FAST                0 (self)
+               440           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (button_radius)
                             18 RETURN_VALUE
                
-               436     >>   20 LOAD_FAST                1 (radius)
+               442     >>   20 LOAD_FAST                1 (radius)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (button_radius)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('button_radius',)
                varnames   ('self', 'radius')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'border_radius'
-               firstlineno 432
+               firstlineno 438
                lnotab 0x020104010e02
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 10
                flags     : 3
                code
@@ -3844,195 +3868,195 @@
                   00000000000000000000000000000000007c006a100000000000000000a6
                   010000ab01000000000000000001007c00a0110000000000000000000000
                   0000000000000000007c006a1000000000000000007c006a0c0000000000
                   000000a6020000ab02000000000000000001007c006a0b00000000000000
                   00a01200000000000000000000000000000000000000007c006a07000000
                   00000000007c006a1300000000000000007c006a130000000000000000ac
                   0aa6030000ab030000000000000000010064005300
-               438           0 RESUME                   0
+               444           0 RESUME                   0
                
-               439           2 LOAD_FAST                0 (self)
+               445           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (delete)
                             26 LOAD_CONST               1 ('all')
                             28 PRECALL                  1
                             32 CALL                     1
                             42 POP_TOP
                
-               441          44 LOAD_FAST                0 (self)
+               447          44 LOAD_FAST                0 (self)
                             46 LOAD_METHOD              1 (create_round_rect4)
                
-               442          68 LOAD_CONST               2 (0)
+               448          68 LOAD_CONST               2 (0)
                
-               443          70 LOAD_CONST               2 (0)
+               449          70 LOAD_CONST               2 (0)
                
-               444          72 LOAD_FAST                0 (self)
+               450          72 LOAD_FAST                0 (self)
                             74 LOAD_METHOD              2 (winfo_width)
                             96 PRECALL                  0
                            100 CALL                     0
                            110 LOAD_CONST               3 (1)
                            112 BINARY_OP               10 (-)
                
-               445         116 LOAD_FAST                0 (self)
+               451         116 LOAD_FAST                0 (self)
                            118 LOAD_METHOD              3 (winfo_height)
                            140 PRECALL                  0
                            144 CALL                     0
                            154 LOAD_CONST               3 (1)
                            156 BINARY_OP               10 (-)
                
-               446         160 LOAD_FAST                0 (self)
+               452         160 LOAD_FAST                0 (self)
                            162 LOAD_ATTR                4 (text_radius)
                
-               447         172 LOAD_FAST                0 (self)
+               453         172 LOAD_FAST                0 (self)
                            174 LOAD_ATTR                5 (text_border_width)
                
-               448         184 LOAD_FAST                0 (self)
+               454         184 LOAD_FAST                0 (self)
                            186 LOAD_ATTR                6 (_text_border)
                            196 LOAD_FAST                0 (self)
                            198 LOAD_ATTR                7 (_text_back)
                
-               441         208 KW_NAMES                 4
+               447         208 KW_NAMES                 4
                            210 PRECALL                  8
                            214 CALL                     8
                            224 POP_TOP
                
-               451         226 LOAD_CONST               5 ('button_frame')
+               457         226 LOAD_CONST               5 ('button_frame')
                            228 LOAD_FAST                0 (self)
                            230 STORE_ATTR               8 (text_frame)
                
-               453         240 LOAD_FAST                0 (self)
+               459         240 LOAD_FAST                0 (self)
                            242 LOAD_METHOD              9 (create_window)
                
-               454         264 LOAD_FAST                0 (self)
+               460         264 LOAD_FAST                0 (self)
                            266 LOAD_METHOD              2 (winfo_width)
                            288 PRECALL                  0
                            292 CALL                     0
                            302 LOAD_CONST               6 (2)
                            304 BINARY_OP               11 (/)
                            308 LOAD_FAST                0 (self)
                            310 LOAD_METHOD              3 (winfo_height)
                            332 PRECALL                  0
                            336 CALL                     0
                            346 LOAD_CONST               6 (2)
                            348 BINARY_OP               11 (/)
                
-               455         352 LOAD_FAST                0 (self)
+               461         352 LOAD_FAST                0 (self)
                            354 LOAD_METHOD              2 (winfo_width)
                            376 PRECALL                  0
                            380 CALL                     0
                            390 LOAD_FAST                0 (self)
                            392 LOAD_ATTR                5 (text_border_width)
                            402 BINARY_OP               10 (-)
                            406 LOAD_FAST                0 (self)
                            408 LOAD_ATTR               10 (text_padding)
                            418 LOAD_CONST               2 (0)
                            420 BINARY_SUBSCR
                            430 BINARY_OP               10 (-)
                            434 LOAD_CONST               6 (2)
                            436 BINARY_OP               10 (-)
                
-               456         440 LOAD_FAST                0 (self)
+               462         440 LOAD_FAST                0 (self)
                            442 LOAD_METHOD              3 (winfo_height)
                            464 PRECALL                  0
                            468 CALL                     0
                            478 LOAD_FAST                0 (self)
                            480 LOAD_ATTR                5 (text_border_width)
                            490 BINARY_OP               10 (-)
                            494 LOAD_FAST                0 (self)
                            496 LOAD_ATTR               10 (text_padding)
                            506 LOAD_CONST               3 (1)
                            508 BINARY_SUBSCR
                            518 BINARY_OP               10 (-)
                            522 LOAD_CONST               6 (2)
                            524 BINARY_OP               10 (-)
                
-               457         528 LOAD_FAST                0 (self)
+               463         528 LOAD_FAST                0 (self)
                            530 LOAD_ATTR               11 (text)
                
-               453         540 KW_NAMES                 7
+               459         540 KW_NAMES                 7
                            542 PRECALL                  5
                            546 CALL                     5
                            556 LOAD_FAST                0 (self)
                            558 STORE_ATTR              12 (text_text)
                
-               460         568 LOAD_FAST                0 (self)
+               466         568 LOAD_FAST                0 (self)
                            570 LOAD_METHOD             13 (create_rectangle)
                            592 LOAD_CONST               3 (1)
                            594 LOAD_FAST                0 (self)
                            596 LOAD_ATTR                4 (text_radius)
                            606 LOAD_CONST               8 (5)
                            608 BINARY_OP               11 (/)
                            612 BINARY_OP                0 (+)
                
-               461         616 LOAD_FAST                0 (self)
+               467         616 LOAD_FAST                0 (self)
                            618 LOAD_METHOD              3 (winfo_height)
                            640 PRECALL                  0
                            644 CALL                     0
                            654 LOAD_FAST                0 (self)
                            656 LOAD_ATTR               14 (_text_bottom_width)
                            666 BINARY_OP               10 (-)
                            670 LOAD_CONST               3 (1)
                            672 BINARY_OP               10 (-)
                
-               462         676 LOAD_FAST                0 (self)
+               468         676 LOAD_FAST                0 (self)
                            678 LOAD_METHOD              2 (winfo_width)
                            700 PRECALL                  0
                            704 CALL                     0
                            714 LOAD_CONST               3 (1)
                            716 BINARY_OP               10 (-)
                            720 LOAD_FAST                0 (self)
                            722 LOAD_ATTR                4 (text_radius)
                            732 LOAD_CONST               8 (5)
                            734 BINARY_OP               11 (/)
                            738 BINARY_OP               10 (-)
                
-               463         742 LOAD_FAST                0 (self)
+               469         742 LOAD_FAST                0 (self)
                            744 LOAD_METHOD              3 (winfo_height)
                            766 PRECALL                  0
                            770 CALL                     0
                            780 LOAD_CONST               3 (1)
                            782 BINARY_OP               10 (-)
                
-               464         786 LOAD_FAST                0 (self)
+               470         786 LOAD_FAST                0 (self)
                            788 LOAD_ATTR               15 (_text_bottom_line)
                            798 LOAD_FAST                0 (self)
                            800 LOAD_ATTR               15 (_text_bottom_line)
                
-               465         810 LOAD_CONST               2 (0)
+               471         810 LOAD_CONST               2 (0)
                
-               460         812 KW_NAMES                 9
+               466         812 KW_NAMES                 9
                            814 PRECALL                  7
                            818 CALL                     7
                            828 LOAD_FAST                0 (self)
                            830 STORE_ATTR              16 (text_bottom)
                
-               467         840 LOAD_FAST                0 (self)
+               473         840 LOAD_FAST                0 (self)
                            842 LOAD_ATTR               14 (_text_bottom_width)
                            852 LOAD_CONST               2 (0)
                            854 COMPARE_OP               2 (==)
                            860 POP_JUMP_FORWARD_IF_FALSE    26 (to 914)
                
-               468         862 LOAD_FAST                0 (self)
+               474         862 LOAD_FAST                0 (self)
                            864 LOAD_METHOD              0 (delete)
                            886 LOAD_FAST                0 (self)
                            888 LOAD_ATTR               16 (text_bottom)
                            898 PRECALL                  1
                            902 CALL                     1
                            912 POP_TOP
                
-               470     >>  914 LOAD_FAST                0 (self)
+               476     >>  914 LOAD_FAST                0 (self)
                            916 LOAD_METHOD             17 (tag_raise)
                            938 LOAD_FAST                0 (self)
                            940 LOAD_ATTR               16 (text_bottom)
                            950 LOAD_FAST                0 (self)
                            952 LOAD_ATTR               12 (text_text)
                            962 PRECALL                  2
                            966 CALL                     2
                            976 POP_TOP
                
-               472         978 LOAD_FAST                0 (self)
+               478         978 LOAD_FAST                0 (self)
                            980 LOAD_ATTR               11 (text)
                            990 LOAD_METHOD             18 (configure)
                           1012 LOAD_FAST                0 (self)
                           1014 LOAD_ATTR                7 (_text_back)
                           1024 LOAD_FAST                0 (self)
                           1026 LOAD_ATTR               19 (_text_text_back)
                           1036 LOAD_FAST                0 (self)
@@ -4057,15 +4081,15 @@
                   ('background', 'foreground', 'insertbackground')
                names      ('delete', 'create_round_rect4', 'winfo_width', 'winfo_height', 'text_radius', 'text_border_width', '_text_border', '_text_back', 'text_frame', 'create_window', 'text_padding', 'text', 'text_text', 'create_rectangle', '_text_bottom_width', '_text_bottom_line', 'text_bottom', 'tag_raise', 'configure', '_text_text_back')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_draw'
-               firstlineno 438
+               firstlineno 444
                lnotab
                   0x02012a021801020102012c012c010c010c0118f9120a0e021801580158
                   0158010cfc1c0730013c0142012c01180102fb1c07160134024002
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
@@ -4073,42 +4097,42 @@
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c00a00a00000000000000000000000000000000000000006400a6
                   010000ab010000000000000000010064005300
-               474           0 RESUME                   0
+               480           0 RESUME                   0
                
-               475           2 LOAD_FAST                0 (self)
+               481           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (text_focusin_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_text_back)
                
-               476          26 LOAD_FAST                0 (self)
+               482          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (text_focusin_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_text_border)
                
-               477          50 LOAD_FAST                0 (self)
+               483          50 LOAD_FAST                0 (self)
                             52 LOAD_ATTR                4 (text_focusin_text_back)
                             62 LOAD_FAST                0 (self)
                             64 STORE_ATTR               5 (_text_text_back)
                
-               478          74 LOAD_FAST                0 (self)
+               484          74 LOAD_FAST                0 (self)
                             76 LOAD_ATTR                6 (text_focusin_bottom_line)
                             86 LOAD_FAST                0 (self)
                             88 STORE_ATTR               7 (_text_bottom_line)
                
-               479          98 LOAD_FAST                0 (self)
+               485          98 LOAD_FAST                0 (self)
                            100 LOAD_ATTR                8 (text_focusin_bottom_width)
                            110 LOAD_FAST                0 (self)
                            112 STORE_ATTR               9 (_text_bottom_width)
                
-               481         122 LOAD_FAST                0 (self)
+               487         122 LOAD_FAST                0 (self)
                            124 LOAD_METHOD             10 (_draw)
                            146 LOAD_CONST               0 (None)
                            148 PRECALL                  1
                            152 CALL                     1
                            162 POP_TOP
                            164 LOAD_CONST               0 (None)
                            166 RETURN_VALUE
@@ -4116,56 +4140,56 @@
                   None
                names      ('text_focusin_back', '_text_back', 'text_focusin_border', '_text_border', 'text_focusin_text_back', '_text_text_back', 'text_focusin_bottom_line', '_text_bottom_line', 'text_focusin_bottom_width', '_text_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_focus'
-               firstlineno 474
+               firstlineno 480
                lnotab 0x020118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
                   0x97007c006a0000000000000000007c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c00a00a00000000000000000000000000000000000000006400a6
                   010000ab010000000000000000010064005300
-               483           0 RESUME                   0
+               489           0 RESUME                   0
                
-               484           2 LOAD_FAST                0 (self)
+               490           2 LOAD_FAST                0 (self)
                              4 LOAD_ATTR                0 (text_back)
                             14 LOAD_FAST                0 (self)
                             16 STORE_ATTR               1 (_text_back)
                
-               485          26 LOAD_FAST                0 (self)
+               491          26 LOAD_FAST                0 (self)
                             28 LOAD_ATTR                2 (text_border)
                             38 LOAD_FAST                0 (self)
                             40 STORE_ATTR               3 (_text_border)
                
-               486          50 LOAD_FAST                0 (self)
+               492          50 LOAD_FAST                0 (self)
                             52 LOAD_ATTR                4 (text_text_back)
                             62 LOAD_FAST                0 (self)
                             64 STORE_ATTR               5 (_text_text_back)
                
-               487          74 LOAD_FAST                0 (self)
+               493          74 LOAD_FAST                0 (self)
                             76 LOAD_ATTR                6 (text_bottom_line)
                             86 LOAD_FAST                0 (self)
                             88 STORE_ATTR               7 (_text_bottom_line)
                
-               488          98 LOAD_FAST                0 (self)
+               494          98 LOAD_FAST                0 (self)
                            100 LOAD_ATTR                8 (text_bottom_width)
                            110 LOAD_FAST                0 (self)
                            112 STORE_ATTR               9 (_text_bottom_width)
                
-               490         122 LOAD_FAST                0 (self)
+               496         122 LOAD_FAST                0 (self)
                            124 LOAD_METHOD             10 (_draw)
                            146 LOAD_CONST               0 (None)
                            148 PRECALL                  1
                            152 CALL                     1
                            162 POP_TOP
                            164 LOAD_CONST               0 (None)
                            166 RETURN_VALUE
@@ -4173,66 +4197,66 @@
                   None
                names      ('text_back', '_text_back', 'text_border', '_text_border', 'text_text_back', '_text_text_back', 'text_bottom_line', '_text_bottom_line', 'text_bottom_width', '_text_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_focusout'
-               firstlineno 483
+               firstlineno 489
                lnotab 0x020118011801180118011802
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               492           0 RESUME                   0
+               498           0 RESUME                   0
                
-               493           2 LOAD_FAST                0 (self)
+               499           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_set)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('focus_set',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_click'
-               firstlineno 492
+               firstlineno 498
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code 0x970064017c005f00000000000000000064005300
-               495           0 RESUME                   0
+               501           0 RESUME                   0
                
-               496           2 LOAD_CONST               1 (True)
+               502           2 LOAD_CONST               1 (True)
                              4 LOAD_FAST                0 (self)
                              6 STORE_ATTR               0 (hover)
                             16 LOAD_CONST               0 (None)
                             18 RETURN_VALUE
                consts
                   None
                   True
                names      ('hover',)
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_hover'
-               firstlineno 495
+               firstlineno 501
                lnotab 0x0201
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 3
                flags     : 3
                code
@@ -4240,610 +4264,420 @@
                   00ab000000000000000000735a64017c005f0100000000000000007c006a
                   0200000000000000007c005f0300000000000000007c006a040000000000
                   0000007c005f0500000000000000007c006a0600000000000000007c005f
                   0700000000000000007c006a0800000000000000007c005f090000000000
                   0000007c006a0a00000000000000007c005f0b00000000000000007c00a0
                   0c00000000000000000000000000000000000000006400a6010000ab0100
                   0000000000000001006400530064005300
-               498           0 RESUME                   0
+               504           0 RESUME                   0
                
-               499           2 LOAD_FAST                0 (self)
+               505           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (focus_get)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_JUMP_FORWARD_IF_TRUE    90 (to 222)
                
-               500          42 LOAD_CONST               1 (False)
+               506          42 LOAD_CONST               1 (False)
                             44 LOAD_FAST                0 (self)
                             46 STORE_ATTR               1 (hover)
                
-               501          56 LOAD_FAST                0 (self)
+               507          56 LOAD_FAST                0 (self)
                             58 LOAD_ATTR                2 (text_back)
                             68 LOAD_FAST                0 (self)
                             70 STORE_ATTR               3 (_text_back)
                
-               502          80 LOAD_FAST                0 (self)
+               508          80 LOAD_FAST                0 (self)
                             82 LOAD_ATTR                4 (text_border)
                             92 LOAD_FAST                0 (self)
                             94 STORE_ATTR               5 (_text_border)
                
-               503         104 LOAD_FAST                0 (self)
+               509         104 LOAD_FAST                0 (self)
                            106 LOAD_ATTR                6 (text_text_back)
                            116 LOAD_FAST                0 (self)
                            118 STORE_ATTR               7 (_text_text_back)
                
-               504         128 LOAD_FAST                0 (self)
+               510         128 LOAD_FAST                0 (self)
                            130 LOAD_ATTR                8 (text_bottom_line)
                            140 LOAD_FAST                0 (self)
                            142 STORE_ATTR               9 (_text_bottom_line)
                
-               505         152 LOAD_FAST                0 (self)
+               511         152 LOAD_FAST                0 (self)
                            154 LOAD_ATTR               10 (text_bottom_width)
                            164 LOAD_FAST                0 (self)
                            166 STORE_ATTR              11 (_text_bottom_width)
                
-               507         176 LOAD_FAST                0 (self)
+               513         176 LOAD_FAST                0 (self)
                            178 LOAD_METHOD             12 (_draw)
                            200 LOAD_CONST               0 (None)
                            202 PRECALL                  1
                            206 CALL                     1
                            216 POP_TOP
                            218 LOAD_CONST               0 (None)
                            220 RETURN_VALUE
                
-               499     >>  222 LOAD_CONST               0 (None)
+               505     >>  222 LOAD_CONST               0 (None)
                            224 RETURN_VALUE
                consts
                   None
                   False
                names      ('focus_get', 'hover', 'text_back', '_text_back', 'text_border', '_text_border', 'text_text_back', '_text_text_back', 'text_bottom_line', '_text_bottom_line', 'text_bottom_width', '_text_bottom_width', '_draw')
                varnames   ('self', 'evt')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       '_hover_release'
-               firstlineno 498
+               firstlineno 504
                lnotab 0x020128010e01180118011801180118022ef8
             'font'
             code
                argcount  : 2
                nlocals   : 2
                stacksize : 2
                flags     : 3
                code
                   0x97007c0180077c006a00000000000000000053007c017c005f00000000
                   000000000064005300
-               509           0 RESUME                   0
+               515           0 RESUME                   0
                
-               510           2 LOAD_FAST                1 (font)
+               516           2 LOAD_FAST                1 (font)
                              4 POP_JUMP_FORWARD_IF_NOT_NONE     7 (to 20)
                
-               511           6 LOAD_FAST                0 (self)
+               517           6 LOAD_FAST                0 (self)
                              8 LOAD_ATTR                0 (text_text_font)
                             18 RETURN_VALUE
                
-               513     >>   20 LOAD_FAST                1 (font)
+               519     >>   20 LOAD_FAST                1 (font)
                             22 LOAD_FAST                0 (self)
                             24 STORE_ATTR               0 (text_text_font)
                             34 LOAD_CONST               0 (None)
                             36 RETURN_VALUE
                consts
                   None
                names      ('text_text_font',)
                varnames   ('self', 'font')
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'font'
-               firstlineno 509
+               firstlineno 515
                lnotab 0x020104010e02
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               515           0 RESUME                   0
+               521           0 RESUME                   0
                
-               516           2 LOAD_FAST                0 (self)
+               522           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'default_palette'
-               firstlineno 515
+               firstlineno 521
                lnotab 0x0201
             code
                argcount  : 1
                nlocals   : 1
-               stacksize : 17
+               stacksize : 18
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
-                  0264036404640564066407640864066409640a640b640c640d640e9c0ea6
-                  010000ab010000000000000000010064005300
-               518           0 RESUME                   0
+                  0264036404640564066407640564086409640a640b6407640c640d640e9c
+                  06640f9c096901a6010000ab010000000000000000010064005300
+               524           0 RESUME                   0
                
-               519           2 LOAD_FAST                0 (self)
+               525           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               521          26 LOAD_CONST               1 (13)
+               527          26 LOAD_CONST               1 ('text')
+               
+               528          28 LOAD_CONST               2 (6)
                
-               523          28 LOAD_CONST               2 ((6, 4))
+               529          30 LOAD_CONST               3 ((3, 4))
                
-               525          30 LOAD_CONST               3 ('#f3f3f3')
+               531          32 LOAD_CONST               4 ('#fdfdfd')
                
-               526          32 LOAD_CONST               4 (1)
+               532          34 LOAD_CONST               5 ('#eaeaea')
                
-               527          34 LOAD_CONST               5 (0)
+               533          36 LOAD_CONST               6 ('#5f5f5f')
                
-               529          36 LOAD_CONST               6 ('#eaeaea')
+               534          38 LOAD_CONST               7 (1)
                
-               530          38 LOAD_CONST               7 ('#fdfdfd')
+               536          40 LOAD_CONST               5 ('#eaeaea')
                
-               531          40 LOAD_CONST               8 ('#5f5f5f')
+               537          42 LOAD_CONST               8 (0)
                
-               532          42 LOAD_CONST               6 ('#eaeaea')
+               540          44 LOAD_CONST               9 ('#f9f9f9')
                
-               534          44 LOAD_CONST               9 ('#e2e2e2')
+               541          46 LOAD_CONST              10 ('#e2e2e2')
                
-               535          46 LOAD_CONST              10 ('#f9f9f9')
+               542          48 LOAD_CONST              11 ('#1a1a1a')
                
-               536          48 LOAD_CONST              11 ('#1a1a1a')
+               543          50 LOAD_CONST               7 (1)
                
-               537          50 LOAD_CONST              12 ('#185fb4')
+               545          52 LOAD_CONST              12 ('#185fb4')
+               
+               546          54 LOAD_CONST              13 (2)
+               
+               539          56 LOAD_CONST              14 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
+                            58 BUILD_CONST_KEY_MAP      6
                
-               538          52 LOAD_CONST              13 (2)
+               527          60 LOAD_CONST              15 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
+                            62 BUILD_CONST_KEY_MAP      9
                
-               520          54 LOAD_CONST              14 (('text_radius', 'text_padding', 'text_frame_back', 'text_border_width', 'text_bottom_width', 'text_border', 'text_back', 'text_text_back', 'text_bottom_line', 'text_focusin_border', 'text_focusin_back', 'text_focusin_text_back', 'text_focusin_bottom_line', 'text_focusin_bottom_width'))
-                            56 BUILD_CONST_KEY_MAP     14
+               526          64 BUILD_MAP                1
                
-               519          58 PRECALL                  1
-                            62 CALL                     1
-                            72 POP_TOP
-                            74 LOAD_CONST               0 (None)
-                            76 RETURN_VALUE
+               525          66 PRECALL                  1
+                            70 CALL                     1
+                            80 POP_TOP
+                            82 LOAD_CONST               0 (None)
+                            84 RETURN_VALUE
                consts
                   None
-                  13
-                  (6, 4)
-                  '#f3f3f3'
-                  1
-                  0
-                  '#eaeaea'
+                  'text'
+                  6
+                  (3, 4)
                   '#fdfdfd'
+                  '#eaeaea'
                   '#5f5f5f'
-                  '#e2e2e2'
+                  1
+                  0
                   '#f9f9f9'
+                  '#e2e2e2'
                   '#1a1a1a'
                   '#185fb4'
                   2
-                  ('text_radius', 'text_padding', 'text_frame_back', 'text_border_width', 'text_bottom_width', 'text_border', 'text_back', 'text_text_back', 'text_bottom_line', 'text_focusin_border', 'text_focusin_back', 'text_focusin_text_back', 'text_focusin_bottom_line', 'text_focusin_bottom_width')
+                  ('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width')
+                  ('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'palette_light'
-               firstlineno 518
+               firstlineno 524
                lnotab
-                  0x0201180202020202020102010202020102010201020202010201020102
-                  0102ee04ff
+                  0x0201180202010201020202010201020102020201020302010201020102
+                  02020102f904f404ff02ff
             code
                argcount  : 1
                nlocals   : 1
-               stacksize : 17
+               stacksize : 18
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000640164
-                  0264036404640564066407640864096405640a6408640b640c640d9c0ea6
-                  010000ab010000000000000000010064005300
-               542           0 RESUME                   0
+                  026403640464056406640764086409640a640564086407640b640c640d9c
+                  06640e9c096901a6010000ab010000000000000000010064005300
+               552           0 RESUME                   0
                
-               543           2 LOAD_FAST                0 (self)
+               553           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette)
                
-               545          26 LOAD_CONST               1 (13)
+               555          26 LOAD_CONST               1 ('text')
+               
+               556          28 LOAD_CONST               2 (6)
                
-               547          28 LOAD_CONST               2 ((3, 4))
+               557          30 LOAD_CONST               3 ((3, 4))
                
-               549          30 LOAD_CONST               3 ('#202020')
+               559          32 LOAD_CONST               4 ('#353535')
                
-               550          32 LOAD_CONST               4 (1)
+               560          34 LOAD_CONST               5 ('#454545')
                
-               552          34 LOAD_CONST               5 ('#454545')
+               561          36 LOAD_CONST               6 ('#cecece')
                
-               553          36 LOAD_CONST               6 ('#353535')
+               562          38 LOAD_CONST               7 (1)
                
-               554          38 LOAD_CONST               7 ('#cecece')
+               564          40 LOAD_CONST               8 ('#ffffff')
                
-               555          40 LOAD_CONST               8 ('#ffffff')
+               565          42 LOAD_CONST               9 (0)
                
-               556          42 LOAD_CONST               9 (0)
+               568          44 LOAD_CONST              10 ('#2f2f2f')
                
-               558          44 LOAD_CONST               5 ('#454545')
+               569          46 LOAD_CONST               5 ('#454545')
                
-               559          46 LOAD_CONST              10 ('#2f2f2f')
+               570          48 LOAD_CONST               8 ('#ffffff')
                
-               560          48 LOAD_CONST               8 ('#ffffff')
+               571          50 LOAD_CONST               7 (1)
                
-               561          50 LOAD_CONST              11 ('#4cc2ff')
+               573          52 LOAD_CONST              11 ('#4cc2ff')
+               
+               574          54 LOAD_CONST              12 (2)
+               
+               567          56 LOAD_CONST              13 (('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width'))
+                            58 BUILD_CONST_KEY_MAP      6
                
-               562          52 LOAD_CONST              12 (2)
+               555          60 LOAD_CONST              14 (('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin'))
+                            62 BUILD_CONST_KEY_MAP      9
                
-               544          54 LOAD_CONST              13 (('text_radius', 'text_padding', 'text_frame_back', 'text_border_width', 'text_border', 'text_back', 'text_text_back', 'text_bottom_line', 'text_bottom_width', 'text_focusin_border', 'text_focusin_back', 'text_focusin_text_back', 'text_focusin_bottom_line', 'text_focusin_bottom_width'))
-                            56 BUILD_CONST_KEY_MAP     14
+               554          64 BUILD_MAP                1
                
-               543          58 PRECALL                  1
-                            62 CALL                     1
-                            72 POP_TOP
-                            74 LOAD_CONST               0 (None)
-                            76 RETURN_VALUE
+               553          66 PRECALL                  1
+                            70 CALL                     1
+                            80 POP_TOP
+                            82 LOAD_CONST               0 (None)
+                            84 RETURN_VALUE
                consts
                   None
-                  13
+                  'text'
+                  6
                   (3, 4)
-                  '#202020'
-                  1
-                  '#454545'
                   '#353535'
+                  '#454545'
                   '#cecece'
+                  1
                   '#ffffff'
                   0
                   '#2f2f2f'
                   '#4cc2ff'
                   2
-                  ('text_radius', 'text_padding', 'text_frame_back', 'text_border_width', 'text_border', 'text_back', 'text_text_back', 'text_bottom_line', 'text_bottom_width', 'text_focusin_border', 'text_focusin_back', 'text_focusin_text_back', 'text_focusin_bottom_line', 'text_focusin_bottom_width')
+                  ('back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width')
+                  ('radius', 'padding', 'back', 'border', 'text_back', 'border_width', 'bottom_line', 'bottom_width', 'focusin')
                names      ('palette',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'palette_dark'
-               firstlineno 542
-               lnotab
-                  0x0201180202020202020102020201020102010201020202010201020102
-                  0102ee04ff
-            code
-               argcount  : 2
-               nlocals   : 2
-               stacksize : 11
-               flags     : 3
-               code
-                  0x97007c0181df7c016401190000000000000000007c005f000000000000
-                  0000007c016402190000000000000000007c005f0100000000000000007c
-                  016403190000000000000000007c005f0200000000000000007c01640419
-                  0000000000000000007c005f0300000000000000007c0164051900000000
-                  00000000007c005f0400000000000000007c016406190000000000000000
-                  007c005f0500000000000000007c016407190000000000000000007c005f
-                  0600000000000000007c016408190000000000000000007c005f07000000
-                  00000000007c016409190000000000000000007c005f0800000000000000
-                  007c01640a190000000000000000007c005f0900000000000000007c0164
-                  0b190000000000000000007c005f0a00000000000000007c01640c190000
-                  000000000000007c005f0b00000000000000007c01640d19000000000000
-                  0000007c005f0c00000000000000007c01640e190000000000000000007c
-                  005f0d000000000000000009007c00a00e00000000000000000000000000
-                  000000000000006400a6010000ab01000000000000000001006400530023
-                  00741e000000000000000000002400720401005900640053007700780359
-                  0077017c006a0100000000000000007c006a0200000000000000007c006a
-                  0300000000000000007c006a0800000000000000007c006a040000000000
-                  0000007c006a0500000000000000007c006a0600000000000000007c006a
-                  0900000000000000007c006a0a00000000000000007c006a0b0000000000
-                  000000640f9c0a5300
-               566           0 RESUME                   0
-               
-               567           2 LOAD_FAST                1 (dict)
-                             4 POP_JUMP_FORWARD_IF_NONE   223 (to 452)
-               
-               568           6 LOAD_FAST                1 (dict)
-                             8 LOAD_CONST               1 ('text_radius')
-                            10 BINARY_SUBSCR
-                            20 LOAD_FAST                0 (self)
-                            22 STORE_ATTR               0 (text_radius)
-               
-               570          32 LOAD_FAST                1 (dict)
-                            34 LOAD_CONST               2 ('text_padding')
-                            36 BINARY_SUBSCR
-                            46 LOAD_FAST                0 (self)
-                            48 STORE_ATTR               1 (text_padding)
-               
-               572          58 LOAD_FAST                1 (dict)
-                            60 LOAD_CONST               3 ('text_frame_back')
-                            62 BINARY_SUBSCR
-                            72 LOAD_FAST                0 (self)
-                            74 STORE_ATTR               2 (text_frame_back)
-               
-               573          84 LOAD_FAST                1 (dict)
-                            86 LOAD_CONST               4 ('text_border_width')
-                            88 BINARY_SUBSCR
-                            98 LOAD_FAST                0 (self)
-                           100 STORE_ATTR               3 (text_border_width)
-               
-               575         110 LOAD_FAST                1 (dict)
-                           112 LOAD_CONST               5 ('text_border')
-                           114 BINARY_SUBSCR
-                           124 LOAD_FAST                0 (self)
-                           126 STORE_ATTR               4 (text_border)
-               
-               576         136 LOAD_FAST                1 (dict)
-                           138 LOAD_CONST               6 ('text_back')
-                           140 BINARY_SUBSCR
-                           150 LOAD_FAST                0 (self)
-                           152 STORE_ATTR               5 (text_back)
-               
-               577         162 LOAD_FAST                1 (dict)
-                           164 LOAD_CONST               7 ('text_text_back')
-                           166 BINARY_SUBSCR
-                           176 LOAD_FAST                0 (self)
-                           178 STORE_ATTR               6 (text_text_back)
-               
-               578         188 LOAD_FAST                1 (dict)
-                           190 LOAD_CONST               8 ('text_bottom_line')
-                           192 BINARY_SUBSCR
-                           202 LOAD_FAST                0 (self)
-                           204 STORE_ATTR               7 (text_bottom_line)
-               
-               579         214 LOAD_FAST                1 (dict)
-                           216 LOAD_CONST               9 ('text_bottom_width')
-                           218 BINARY_SUBSCR
-                           228 LOAD_FAST                0 (self)
-                           230 STORE_ATTR               8 (text_bottom_width)
-               
-               581         240 LOAD_FAST                1 (dict)
-                           242 LOAD_CONST              10 ('text_focusin_border')
-                           244 BINARY_SUBSCR
-                           254 LOAD_FAST                0 (self)
-                           256 STORE_ATTR               9 (text_focusin_border)
-               
-               582         266 LOAD_FAST                1 (dict)
-                           268 LOAD_CONST              11 ('text_focusin_back')
-                           270 BINARY_SUBSCR
-                           280 LOAD_FAST                0 (self)
-                           282 STORE_ATTR              10 (text_focusin_back)
-               
-               583         292 LOAD_FAST                1 (dict)
-                           294 LOAD_CONST              12 ('text_focusin_text_back')
-                           296 BINARY_SUBSCR
-                           306 LOAD_FAST                0 (self)
-                           308 STORE_ATTR              11 (text_focusin_text_back)
-               
-               584         318 LOAD_FAST                1 (dict)
-                           320 LOAD_CONST              13 ('text_focusin_bottom_line')
-                           322 BINARY_SUBSCR
-                           332 LOAD_FAST                0 (self)
-                           334 STORE_ATTR              12 (text_focusin_bottom_line)
-               
-               585         344 LOAD_FAST                1 (dict)
-                           346 LOAD_CONST              14 ('text_focusin_bottom_width')
-                           348 BINARY_SUBSCR
-                           358 LOAD_FAST                0 (self)
-                           360 STORE_ATTR              13 (text_focusin_bottom_width)
-               
-               587         370 NOP
-               
-               588         372 LOAD_FAST                0 (self)
-                           374 LOAD_METHOD             14 (_draw)
-                           396 LOAD_CONST               0 (None)
-                           398 PRECALL                  1
-                           402 CALL                     1
-                           412 POP_TOP
-                           414 LOAD_CONST               0 (None)
-                           416 RETURN_VALUE
-                       >>  418 PUSH_EXC_INFO
-               
-               589         420 LOAD_GLOBAL             30 (AttributeError)
-                           432 CHECK_EXC_MATCH
-                           434 POP_JUMP_FORWARD_IF_FALSE     4 (to 444)
-                           436 POP_TOP
-               
-               590         438 POP_EXCEPT
-                           440 LOAD_CONST               0 (None)
-                           442 RETURN_VALUE
-               
-               589     >>  444 RERAISE                  0
-                       >>  446 COPY                     3
-                           448 POP_EXCEPT
-                           450 RERAISE                  1
-               
-               593     >>  452 LOAD_FAST                0 (self)
-                           454 LOAD_ATTR                1 (text_padding)
-               
-               595         464 LOAD_FAST                0 (self)
-                           466 LOAD_ATTR                2 (text_frame_back)
-               
-               596         476 LOAD_FAST                0 (self)
-                           478 LOAD_ATTR                3 (text_border_width)
-               
-               597         488 LOAD_FAST                0 (self)
-                           490 LOAD_ATTR                8 (text_bottom_width)
-               
-               599         500 LOAD_FAST                0 (self)
-                           502 LOAD_ATTR                4 (text_border)
-               
-               600         512 LOAD_FAST                0 (self)
-                           514 LOAD_ATTR                5 (text_back)
-               
-               601         524 LOAD_FAST                0 (self)
-                           526 LOAD_ATTR                6 (text_text_back)
-               
-               603         536 LOAD_FAST                0 (self)
-                           538 LOAD_ATTR                9 (text_focusin_border)
-               
-               604         548 LOAD_FAST                0 (self)
-                           550 LOAD_ATTR               10 (text_focusin_back)
-               
-               605         560 LOAD_FAST                0 (self)
-                           562 LOAD_ATTR               11 (text_focusin_text_back)
-               
-               592         572 LOAD_CONST              15 (('text_padding', 'text_frame_back', 'text_border_width', 'text_bottom_width', 'text_border', 'text_back', 'text_text_back', 'text_focusin_border', 'text_focusin_back', 'text_focusin_text_back'))
-                           574 BUILD_CONST_KEY_MAP     10
-                           576 RETURN_VALUE
-               ExceptionTable:
-                 372 to 412 -> 418 [0]
-                 418 to 436 -> 446 [1] lasti
-                 444 to 444 -> 446 [1] lasti
-               consts
-                  None
-                  'text_radius'
-                  'text_padding'
-                  'text_frame_back'
-                  'text_border_width'
-                  'text_border'
-                  'text_back'
-                  'text_text_back'
-                  'text_bottom_line'
-                  'text_bottom_width'
-                  'text_focusin_border'
-                  'text_focusin_back'
-                  'text_focusin_text_back'
-                  'text_focusin_bottom_line'
-                  'text_focusin_bottom_width'
-                  ('text_padding', 'text_frame_back', 'text_border_width', 'text_bottom_width', 'text_border', 'text_back', 'text_text_back', 'text_focusin_border', 'text_focusin_back', 'text_focusin_text_back')
-               names      ('text_radius', 'text_padding', 'text_frame_back', 'text_border_width', 'text_border', 'text_back', 'text_text_back', 'text_bottom_line', 'text_bottom_width', 'text_focusin_border', 'text_focusin_back', 'text_focusin_text_back', 'text_focusin_bottom_line', 'text_focusin_bottom_width', '_draw', 'AttributeError')
-               varnames   ('self', 'dict')
-               freevars   ()
-               cellvars   ()
-               filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
-               name       'palette'
-               firstlineno 566
+               firstlineno 552
                lnotab
-                  0x020104011a021a021a011a021a011a011a011a011a021a011a011a011a
-                  011a0202013001120106ff08040c020c010c010c020c010c010c020c010c
-                  010cf3
+                  0x0201180202010201020202010201020102020201020302010201020102
+                  02020102f904f404ff02ff
             (None,)
-         names      ('__name__', '__module__', '__qualname__', '__init__', '_other', 'border_radius', '_draw', '_focus', '_focusout', '_click', '_hover', '_hover_release', 'Font', 'font', 'default_palette', 'palette_light', 'palette_dark', 'palette', '__classcell__')
+         names      ('__name__', '__module__', '__qualname__', '__init__', '_other', 'border_radius', '_draw', '_focus', '_focusout', '_click', '_hover', '_hover_release', 'Font', 'font', 'default_palette', 'palette_light', 'palette_dark', '__classcell__')
          varnames   ()
          freevars   ()
          cellvars   ('__class__',)
          filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
          name       'AdwDrawBasicRoundText3'
-         firstlineno 425
-         lnotab 0x0c010a030603080606240809080908030803080b0e06060306180618
+         firstlineno 431
+         lnotab 0x0c010a030603080606240809080908030803080b0e060603061c
       'AdwDrawBasicRoundText3'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         609           0 RESUME                   0
+         581           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundText3')
                        8 STORE_NAME               2 (__qualname__)
          
-         610          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 610>)
+         582          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 582>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundText3'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               610           0 RESUME                   0
+               582           0 RESUME                   0
                
-               611           2 LOAD_FAST                0 (self)
+               583           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_light)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_light',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'default_palette'
-               firstlineno 610
+               firstlineno 582
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
          name       'AdwDrawRoundText3'
-         firstlineno 609
+         firstlineno 581
          lnotab 0x0a01
       'AdwDrawRoundText3'
       code
          argcount  : 0
          nlocals   : 0
          stacksize : 1
          flags     : 0
          code 0x970065005a0164005a02640184005a0364025300
-         614           0 RESUME                   0
+         586           0 RESUME                   0
                        2 LOAD_NAME                0 (__name__)
                        4 STORE_NAME               1 (__module__)
                        6 LOAD_CONST               0 ('AdwDrawRoundDarkText3')
                        8 STORE_NAME               2 (__qualname__)
          
-         615          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 615>)
+         587          10 LOAD_CONST               1 (<code object default_palette, file "D:\tkadw\tkadw\canvas\textbox.py", line 587>)
                       12 MAKE_FUNCTION            0
                       14 STORE_NAME               3 (default_palette)
                       16 LOAD_CONST               2 (None)
                       18 RETURN_VALUE
          consts
             'AdwDrawRoundDarkText3'
             code
                argcount  : 1
                nlocals   : 1
                stacksize : 2
                flags     : 3
                code
                   0x97007c00a0000000000000000000000000000000000000000000a60000
                   00ab000000000000000000010064005300
-               615           0 RESUME                   0
+               587           0 RESUME                   0
                
-               616           2 LOAD_FAST                0 (self)
+               588           2 LOAD_FAST                0 (self)
                              4 LOAD_METHOD              0 (palette_dark)
                             26 PRECALL                  0
                             30 CALL                     0
                             40 POP_TOP
                             42 LOAD_CONST               0 (None)
                             44 RETURN_VALUE
                consts
                   None
                names      ('palette_dark',)
                varnames   ('self',)
                freevars   ()
                cellvars   ()
                filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
                name       'default_palette'
-               firstlineno 615
+               firstlineno 587
                lnotab 0x0201
             None
          names      ('__name__', '__module__', '__qualname__', 'default_palette')
          varnames   ()
          freevars   ()
          cellvars   ()
          filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
          name       'AdwDrawRoundDarkText3'
-         firstlineno 614
+         firstlineno 586
          lnotab 0x0a01
       'AdwDrawRoundDarkText3'
       '__main__'
       ('Tk',)
       'x'
       5
       ('fill', 'padx', 'pady')
@@ -4852,10 +4686,10 @@
    varnames   ()
    freevars   ()
    cellvars   ()
    filename   'D:\\tkadw\\tkadw\\canvas\\textbox.py'
    name       '<module>'
    firstlineno 1
    lnotab
-      0x00ff020110010c041c7f007a1c051c061c7f00161c051c051c7f00391c
-      051c050c010c021402140130021401300214013002140130021401300214
-      0130022ce9
+      0x00ff020110010c041c7f007f00011c051c061c7f00161c051c051c7f00
+      171c051c050c010c02140214013002140130021401300214013002140130
+      02140130022ce9
```

### Comparing `tkadw-0.2.1/tkadw/canvas/button.py` & `tkadw-0.2.2/tkadw/canvas/button.py`

 * *Files 5% similar despite different names*

```diff
@@ -16,20 +16,22 @@
         self._button_back = self.button_back
         self._button_border = self.button_border
         self._button_border_width = self.button_border_width
         self._button_text_back = self.button_text_back
 
         self.button_text_font = nametofont("TkDefaultFont")
 
+        # 绑定事件
         self.bind("<Configure>", self._draw, add="+")
         self.bind("<Button>", self._click, add="+")
         self.bind("<ButtonRelease>", self._unclick, add="+")
         self.bind("<Enter>", self._hover, add="+")
         self.bind("<Leave>", self._hover_release, add="+")
 
+        # 绑定点击事件（不是按下）
         if command is not None:
             self.bind("<<Click>>", lambda event: command())
 
         self._draw(None)
 
     def configure(self, **kwargs):
         if "command" in kwargs:
@@ -44,20 +46,24 @@
     def _other(self):
         if hasattr(self, "button_frame_back"):
             self.configure(background=self.button_frame_back, borderwidth=0)
 
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制按钮边框
         self.button_frame = self.create_rectangle(
-            1.5, 1.5, self.winfo_width() - 3, self.winfo_height() - 3,
+            self._button_border_width, self._button_border_width,
+            self.winfo_width() - self._button_border_width * 2,
+            self.winfo_height() - self._button_border_width * 2,
             width=self._button_border_width,
             outline=self._button_border, fill=self._button_back,
         )
 
+        # 绘制按钮文本
         self.button_text = self.create_text(
             self.winfo_width() / 2, self.winfo_height() / 2,
             text=self.text, fill=self._button_text_back,
             font=self.button_text_font
         )
 
     def _click(self, evt=None):
@@ -179,14 +185,19 @@
                     self.button_pressed_back = dict["button"]["pressed"]["back"]
                     self.button_pressed_border = dict["button"]["pressed"]["border"]
                     self.button_pressed_text_back = dict["button"]["pressed"]["text_back"]
                     self.button_pressed_border_width = dict["button"]["pressed"]["border_width"]
 
             self._palette = dict
 
+            self._button_back = self.button_back
+            self._button_border = self.button_border
+            self._button_border_width = self.button_border_width
+            self._button_text_back = self.button_text_back
+
             try:
                 self._draw(None)
             except AttributeError:
                 pass
         else:
             return self._palette
 
@@ -236,20 +247,25 @@
 
     def _other(self):
         self.configure(background=self.master.cget("bg"), borderwidth=0)
 
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制按钮边框
         self.button_frame = self.create_round_rect2(
-            2, 2, self.winfo_width()-3, self.winfo_height()-3, self.button_radius,
+            self._button_border_width,
+            self._button_border_width,
+            self.winfo_width() - self._button_border_width * 2,
+            self.winfo_height() - self._button_border_width * 2, self.button_radius,
             width=self._button_border_width,
             outline=self._button_border, fill=self._button_back,
         )
 
+        # 绘制按钮文本
         self.button_text = self.create_text(
             self.winfo_width() / 2, self.winfo_height() / 2,
             text=self.text, fill=self._button_text_back,
             font=self.button_text_font
         )
 
     def default_palette(self):
@@ -351,25 +367,29 @@
 
 class AdwDrawRoundDarkButton(AdwDrawBasicRoundButton):
     def default_palette(self):
         self.palette_dark()
 
 
 class AdwDrawRoundButton2(AdwDrawBasicRoundButton):
+    # 使用此控件，不建议使用边框属性
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制按钮文本
         self.create_round_rect3(
             "button_frame",
-            2, 2, self.winfo_width()-3, self.winfo_height()-3, self.button_radius,
+            2, 2,
+            self.winfo_width()-3, self.winfo_height()-3, self.button_radius,
             outline=self._button_border, fill=self._button_back,
         )
 
         self.button_frame = "button_frame"
 
+        # 绘制按钮文本
         self.button_text = self.create_text(
             self.winfo_width() / 2, self.winfo_height() / 2,
             text=self.text, fill=self._button_text_back,
             font=self.button_text_font
         )
 
     def default_palette(self):
@@ -410,22 +430,27 @@
         self.palette_dark()
 
 
 class AdwDrawRoundButton3(AdwDrawBasicRoundButton):
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制按钮边框
         self.create_round_rect4(
-            1, 1, self.winfo_width() - 2, self.winfo_height() - 2, self.button_radius,
+            self._button_border_width, self._button_border_width,
+            self.winfo_width() - self._button_border_width * 2,
+            self.winfo_height() - self._button_border_width * 2,
+            self.button_radius,
             width=self._button_border_width,
             outline=self._button_border, fill=self._button_back,
         )
 
         self.button_frame = "button_frame"
 
+        # 绘制按钮文本
         self.button_text = self.create_text(
             self.winfo_width() / 2, self.winfo_height() / 2,
             text=self.text, fill=self._button_text_back,
             font=self.button_text_font
         )
 
     def default_palette(self):
@@ -470,20 +495,22 @@
 class AdwDrawBasicCircularButton(AdwDrawBasicButton):
     def __init__(self, *args, width=120, height=120, **kwargs):
         super().__init__(*args, width=width, height=height, **kwargs)
 
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制按钮框架
         self.button_frame = self.create_oval(
             1.5, 1.5, self.winfo_width() - 3, self.winfo_height() - 3,
             width=self.button_border_width,
             outline=self._button_border, fill=self._button_back,
         )
 
+        # 绘制按钮文本
         self.button_text = self.create_text(
             self.winfo_width() / 2, self.winfo_height() / 2,
             text=self.text, fill=self._button_text_back,
             font=self.button_text_font
         )
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `tkadw-0.2.1/tkadw/canvas/drawengine.py` & `tkadw-0.2.2/tkadw/canvas/drawengine.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,9 +1,16 @@
 from tkinter import Canvas
 
+def rounded_rectangle(size, radius, fill):
+    from PIL import Image, ImageDraw
+    img = Image.new('RGBA', size, (0, 0, 0, 0))
+    draw = ImageDraw.Draw(img)
+    draw.rounded_rectangle((0, 0, size[0], size[1]), radius, fill)
+    return img
+
 poly = """
 # poly.tcl
 
 proc poly_round {win outline fill args} {
     if {[llength $args] % 3 != 0 || [llength $args] < 9} {
         error "wrong # args: should be \"poly_round\
                 win outline fill x1 y1 d1 x2 y2 d2 x3 y3 d3 ?...?\""
@@ -582,22 +589,32 @@
     def draw_copy_icon(self, __x, __y, size=10, padding=10, radius=18):
         _1 = self.create_round_rect4(__x, __y, __x+size*5, __y+size*5, radius)
         _2 = self.create_round_rect4(__x+padding, __y+padding, __x+size*5-padding, __y+size*5-padding, radius/2, fill="white")
         _3 = self.create_round_rect4(__x+size*2, __y+size*2, __x+size*7, __y+size*7, radius)
         _4 = self.create_round_rect4(__x+size*2+padding, __y+size*2+padding, __x+size*7-padding, __y+size*7-padding, radius/2, fill="white")
         return _1, _2, _3, _4
 
+    def create_round_rectangle5(self, __x, __y, __width, __height, fill="black", radius=16, *args, **kwargs):
+        from PIL import ImageTk
+        img = rounded_rectangle((__width, __height), radius, fill, *args, **kwargs)
+        photo = ImageTk.PhotoImage(img)
+
+        return self.create_image(__x, __y, image=photo, anchor='nw')
+
+
 if __name__ == '__main__':
     from tkinter import Tk
 
     root = Tk()
 
     canvas = AdwDrawEngine()
 
-    canvas.create_round_rect3(10, 15, 15, 150, 150, 50)
+    #canvas.create_round_rect3(10, 15, 15, 150, 150, 50)
     canvas.create_round_rect4(160, 160, 300, 300, 50)
 
-    canvas.bind("<Configure>", lambda event: canvas.draw_gradient("#87e9bb", "#d3a6f5", "x"))
+    canvas.create_round_rectangle5(50, 50, 100, 100, radius=16, fill="lightblue")
+
+    #canvas.bind("<Configure>", lambda event: canvas.draw_gradient("#87e9bb", "#d3a6f5", "x"))
 
     canvas.pack(fill="both", expand="yes")
 
     root.mainloop()
```

### Comparing `tkadw-0.2.1/tkadw/canvas/entry.py` & `tkadw-0.2.2/tkadw/canvas/entry.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,14 +20,15 @@
         self.default_palette()
 
         self.text = text
 
         self._entry_back = self.entry_back
         self._entry_border = self.entry_border
         self._entry_text_back = self.entry_text_back
+        self._entry_border_width = self.entry_border_width
         self._entry_bottom_line = self.entry_bottom_line
         self._entry_bottom_width = self.entry_bottom_width
 
         self.entry_text_font = nametofont("TkDefaultFont")
 
         self.bind("<Configure>", self._draw, add="+")
         self.bind("<Button>", self._click, add="+")
@@ -49,27 +50,30 @@
     def _other(self):
         if hasattr(self, "button_frame_back"):
             self.configure(background=self.button_frame_back, borderwidth=0)
 
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制输入框边框
         self.entry_frame = self.create_rectangle(
             0, 0, self.winfo_width() - 1, self.winfo_height() - 1,
-            width=self.entry_border_width,
+            width=self._entry_border_width,
             outline=self._entry_border, fill=self._entry_back,
         )
 
+        # 绘制输入框输入区域
         self.entry_text = self.create_window(
             self.winfo_width() / 2, self.winfo_height() / 2,
-            width=self.winfo_width() - self.entry_border_width - 5 - self.entry_padding[0],
-            height=self.winfo_height() - self.entry_border_width - 5 - self.entry_padding[1],
+            width=self.winfo_width() - self._entry_border_width - 5 - self.entry_padding[0],
+            height=self.winfo_height() - self._entry_border_width - 5 - self.entry_padding[1],
             window=self.entry
         )
 
+        # 绘制输入框美化效果
         self.entry_bottom = self.create_rectangle(1, self.winfo_height() - self._entry_bottom_width - 1,
                                                   self.winfo_width() - 1, self.winfo_height() - 1,
                                                   fill=self._entry_bottom_line, outline=self._entry_bottom_line,
                                                   width=0)
 
         if self._entry_bottom_width == 0:
             self.delete(self.entry_bottom)
@@ -77,23 +81,25 @@
         self.tag_raise(self.entry_bottom, self.entry_text)
 
         self.entry.configure(background=self._entry_back, foreground=self._entry_text_back, insertbackground=self._entry_text_back)
 
     def _focus(self, evt=None):
         self._entry_back = self.entry_focusin_back
         self._entry_border = self.entry_focusin_border
+        self._entry_border_width = self.entry_focusin_border_width
         self._entry_text_back = self.entry_focusin_text_back
         self._entry_bottom_line = self.entry_focusin_bottom_line
         self._entry_bottom_width = self.entry_focusin_bottom_width
 
         self._draw(None)
 
     def _focusout(self, evt=None):
         self._entry_back = self.entry_back
         self._entry_border = self.entry_border
+        self._entry_border_width = self.entry_border_width
         self._entry_text_back = self.entry_text_back
         self._entry_bottom_line = self.entry_bottom_line
         self._entry_bottom_width = self.entry_bottom_width
 
         self._draw(None)
 
     def _click(self, evt=None):
@@ -103,14 +109,15 @@
         self.hover = True
 
     def _hover_release(self, evt=None):
         if not self.focus_get():
             self.hover = False
             self._entry_back = self.entry_back
             self._entry_border = self.entry_border
+            self._entry_border_width = self.entry_border_width
             self._entry_text_back = self.entry_text_back
             self._entry_bottom_line = self.entry_bottom_line
             self._entry_bottom_width = self.entry_bottom_width
 
             self._draw(None)
 
     def font(self, font: Font = None):
@@ -196,14 +203,21 @@
                     self.entry_focusin_border_width = dict["entry"]["focusin"]["border_width"]
 
                     self.entry_focusin_bottom_line = dict["entry"]["focusin"]["bottom_line"]
                     self.entry_focusin_bottom_width = dict["entry"]["focusin"]["bottom_width"]
 
             self._palette = dict
 
+            self._entry_back = self.entry_back
+            self._entry_border = self.entry_border
+            self._entry_text_back = self.entry_text_back
+            self._entry_border_width = self.entry_border_width
+            self._entry_bottom_line = self.entry_bottom_line
+            self._entry_bottom_width = self.entry_bottom_width
+
             try:
                 self._draw(None)
             except AttributeError:
                 pass
         else:
             return self._palette
 
@@ -232,27 +246,30 @@
             return self.button_radius
         else:
             self.button_radius = radius
 
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制输入框边框
         self.entry_frame = self.create_round_rect2(
             2, 2, self.winfo_width() - 3, self.winfo_height() - 3, self.entry_radius,
-            width=self.entry_border_width,
+            width=self._entry_border_width,
             outline=self._entry_border, fill=self._entry_back,
         )
 
+        # 绘制输入框输入区
         self.entry_text = self.create_window(
             self.winfo_width() / 2, self.winfo_height() / 2,
-            width=self.winfo_width() - self.entry_border_width - 5 - self.entry_padding[0],
-            height=self.winfo_height() - self.entry_border_width - 5 - self.entry_padding[1],
+            width=self.winfo_width() - self._entry_border_width - 5 - self.entry_padding[0],
+            height=self.winfo_height() - self._entry_border_width - 5 - self.entry_padding[1],
             window=self.entry
         )
 
+        # 绘制输入框美化效果
         self.entry_bottom = self.create_rectangle(3 + self.entry_radius / 2,
                                                   self.winfo_height() - self._entry_bottom_width - 3,
                                                   self.winfo_width() - 3 - self.entry_radius / 2,
                                                   self.winfo_height() - 3.5,
                                                   fill=self._entry_bottom_line, outline=self._entry_bottom_line,
                                                   width=0)
 
@@ -391,33 +408,36 @@
             return self.button_radius
         else:
             self.button_radius = radius
 
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制输入框边框
         self.create_round_rect4(
             0,
             0,
             self.winfo_width() - 1,
             self.winfo_height() - 1,
             self.entry_radius,
-            width=self.entry_border_width,
+            width=self._entry_border_width,
             outline=self._entry_border, fill=self._entry_back,
         )
 
         self.entry_frame = "button_frame"
 
+        # 绘制输入框输入区域
         self.entry_text = self.create_window(
             self.winfo_width() / 2, self.winfo_height() / 2,
-            width=self.winfo_width() - self.entry_border_width - self.entry_padding[0] - 2,
-            height=self.winfo_height() - self.entry_border_width - self.entry_padding[1] - 2,
+            width=self.winfo_width() - self._entry_border_width - self.entry_padding[0] - 2,
+            height=self.winfo_height() - self._entry_border_width - self.entry_padding[1] - 2,
             window=self.entry
         )
 
+        # 绘制输入框美化效果
         self.entry_bottom = self.create_rectangle(1 + self.entry_radius / 5,
                                                   self.winfo_height() - self._entry_bottom_width - 1,
                                                   self.winfo_width() - 1 - self.entry_radius / 5,
                                                   self.winfo_height() - 1,
                                                   fill=self._entry_bottom_line, outline=self._entry_bottom_line,
                                                   width=0)
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `tkadw-0.2.1/tkadw/canvas/frame.py` & `tkadw-0.2.2/tkadw/canvas/frame.py`

 * *Files 6% similar despite different names*

```diff
@@ -19,22 +19,24 @@
 
     def _other(self):
         pass
 
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制框架边框
         self.frame_frame = self.create_rectangle(
             0, 0, self.winfo_width(), self.winfo_height(),
             width=self.frame_border_width,
             outline=self.frame_border, fill=self.frame_back,
         )
 
         self.frame.configure(background=self.frame_back, bd=0,)
 
+        # 绘制框架区域
         self.frame_f = self.create_window(
             self.winfo_width()/2, self.winfo_height()/2,
             window = self.frame,
             width=self.winfo_width()-6-self.frame_border_width, height=self.winfo_height()-6-self.frame_border_width,
         )
 
     def default_palette(self):
@@ -96,22 +98,24 @@
             self.configure(background=self.master.cget("background"))
         except:
             pass
 
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制框架边框
         self.frame_frame = self.create_round_rect2(
             0, 0, self.winfo_width(), self.winfo_height(), self.frame_radius,
             width=self.frame_border_width,
             outline=self.frame_border, fill=self.frame_back,
         )
 
         self.frame.configure(background=self.frame_back, bd=0,)
 
+        # 绘制框架区域
         self.frame_f = self.create_window(
             self.winfo_width()/2, self.winfo_height()/2,
             window = self.frame,
             width=self.winfo_width()-6-self.frame_border_width, height=self.winfo_height()-6-self.frame_border_width,
         )
 
     def default_palette(self):
@@ -164,26 +168,28 @@
             self.configure(background=self.master.cget("background"))
         except:
             pass
 
     def _draw(self, evt):
         self.delete("all")
 
+        # 绘制框架边框
         self.create_round_rect4(
             0, 0,
             self.winfo_width(),
             self.winfo_height(), self.frame_radius,
             width=self.frame_border_width,
             outline=self.frame_border, fill=self.frame_back,
         )
 
         self.entry_frame = "button_frame"
 
         self.frame.configure(background=self.frame_back, bd=0,)
 
+        # 绘制框架区域
         self.frame_f = self.create_window(
             self.winfo_width()/2, self.winfo_height()/2,
             window = self.frame,
             width=self.winfo_width()-6-self.frame_border_width, height=self.winfo_height()-6-self.frame_border_width,
         )
 
     def default_palette(self):
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `tkadw-0.2.1/tkadw/canvas/label.py` & `tkadw-0.2.2/tkadw/canvas/label.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,9 +1,8 @@
 from tkinter import Label
-from customtkinter import CTkLabel
 
 
 class AdwDrawBasicLabel(Label):
     def __init__(self, *args, text: str = "", **kwargs):
         super().__init__(*args, text=text, **kwargs)
 
         self._other()
```

### Comparing `tkadw-0.2.1/tkadw/canvas/textbox.py` & `tkadw-0.2.2/tkadw/canvas/textbox.py`

 * *Files 10% similar despite different names*

```diff
@@ -238,14 +238,20 @@
                     self.text_focusin_border = dict["text"]["focusin"]["border"]
                     self.text_focusin_text_back = dict["text"]["focusin"]["text_back"]
                     self.text_focusin_border_width = dict["text"]["focusin"]["border_width"]
 
                     self.text_focusin_bottom_line = dict["text"]["focusin"]["bottom_line"]
                     self.text_focusin_bottom_width = dict["text"]["focusin"]["bottom_width"]
 
+            self._text_back = self.text_back
+            self._text_border = self.text_border
+            self._text_text_back = self.text_text_back
+            self._text_bottom_line = self.text_bottom_line
+            self._text_bottom_width = self.text_bottom_width
+
             self._palette = dict
 
             try:
                 self._draw(None)
             except AttributeError:
                 pass
         else:
@@ -418,15 +424,15 @@
 
 
 class AdwDrawRoundDarkText(AdwDrawBasicRoundText):
     def default_palette(self):
         self.palette_dark()
 
 
-class AdwDrawBasicRoundText3(AdwDrawBasicText):
+class AdwDrawBasicRoundText3(AdwDrawBasicRoundText):
     def __init__(self, *args, **kwargs):
         super().__init__(*args, **kwargs)
 
     def _other(self):
         self.configure(background=self.master.cget("bg"), borderwidth=0)
 
     def border_radius(self, radius=None):
@@ -514,100 +520,66 @@
 
     def default_palette(self):
         self.palette_light()
 
     def palette_light(self):
         self.palette(
             {
-                "text_radius": 13,
+                "text": {
+                    "radius": 6,
+                    "padding": (3, 4),
 
-                "text_padding": (6, 4),
+                    "back": "#fdfdfd",
+                    "border": "#eaeaea",
+                    "text_back": "#5f5f5f",
+                    "border_width": 1,
 
-                "text_frame_back": "#f3f3f3",
-                "text_border_width": 1,
-                "text_bottom_width": 0,
-
-                "text_border": "#eaeaea",
-                "text_back": "#fdfdfd",
-                "text_text_back": "#5f5f5f",
-                "text_bottom_line": "#eaeaea",
-
-                "text_focusin_border": "#e2e2e2",
-                "text_focusin_back": "#f9f9f9",
-                "text_focusin_text_back": "#1a1a1a",
-                "text_focusin_bottom_line": "#185fb4",
-                "text_focusin_bottom_width": 2,
+                    "bottom_line": "#eaeaea",
+                    "bottom_width": 0,
+
+                    "focusin": {
+                        "back": "#f9f9f9",
+                        "border": "#e2e2e2",
+                        "text_back": "#1a1a1a",
+                        "border_width": 1,
+
+                        "bottom_line": "#185fb4",
+                        "bottom_width": 2,
+                    }
+                },
             }
         )
 
     def palette_dark(self):
         self.palette(
             {
-                "text_radius": 13,
-
-                "text_padding": (3, 4),
-
-                "text_frame_back": "#202020",
-                "text_border_width": 1,
-
-                "text_border": "#454545",
-                "text_back": "#353535",
-                "text_text_back": "#cecece",
-                "text_bottom_line": "#ffffff",
-                "text_bottom_width": 0,
-
-                "text_focusin_border": "#454545",
-                "text_focusin_back": "#2f2f2f",
-                "text_focusin_text_back": "#ffffff",
-                "text_focusin_bottom_line": "#4cc2ff",
-                "text_focusin_bottom_width": 2,
-            }
-        )
-
-    def palette(self, dict=None):
-        if dict is not None:
-            self.text_radius = dict["text_radius"]
-
-            self.text_padding = dict["text_padding"]
+                "text": {
+                    "radius": 6,
+                    "padding": (3, 4),
 
-            self.text_frame_back = dict["text_frame_back"]
-            self.text_border_width = dict["text_border_width"]
+                    "back": "#353535",
+                    "border": "#454545",
+                    "text_back": "#cecece",
+                    "border_width": 1,
 
-            self.text_border = dict["text_border"]
-            self.text_back = dict["text_back"]
-            self.text_text_back = dict["text_text_back"]
-            self.text_bottom_line = dict["text_bottom_line"]
-            self.text_bottom_width = dict["text_bottom_width"]
-
-            self.text_focusin_border = dict["text_focusin_border"]
-            self.text_focusin_back = dict["text_focusin_back"]
-            self.text_focusin_text_back = dict["text_focusin_text_back"]
-            self.text_focusin_bottom_line = dict["text_focusin_bottom_line"]
-            self.text_focusin_bottom_width = dict["text_focusin_bottom_width"]
+                    "bottom_line": "#ffffff",
+                    "bottom_width": 0,
 
-            try:
-                self._draw(None)
-            except AttributeError:
-                pass
-        else:
-            return {
-                "text_padding": self.text_padding,
+                    "focusin": {
+                        "back": "#2f2f2f",
+                        "border": "#454545",
+                        "text_back": "#ffffff",
+                        "border_width": 1,
 
-                "text_frame_back": self.text_frame_back,
-                "text_border_width": self.text_border_width,
-                "text_bottom_width": self.text_bottom_width,
-
-                "text_border": self.text_border,
-                "text_back": self.text_back,
-                "text_text_back": self.text_text_back,
-
-                "text_focusin_border": self.text_focusin_border,
-                "text_focusin_back": self.text_focusin_back,
-                "text_focusin_text_back": self.text_focusin_text_back,
+                        "bottom_line": "#4cc2ff",
+                        "bottom_width": 2,
+                    }
+                },
             }
+        )
 
 
 class AdwDrawRoundText3(AdwDrawBasicRoundText3):
     def default_palette(self):
         self.palette_light()
```

### Comparing `tkadw-0.2.1/tkadw/canvas/titlebar.py` & `tkadw-0.2.2/tkadw/canvas/titlebar.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/__init__.cpython-311.pyc` & `tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/__init__.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/button.cpython-311.pyc` & `tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/button.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/entry.cpython-311.pyc` & `tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/entry.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/frame.cpython-311.pyc` & `tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/frame.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/label.cpython-311.pyc` & `tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/label.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/__pycache__/textbox.cpython-311.pyc` & `tkadw-0.2.2/tkadw/tkite/gtk/__pycache__/textbox.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/button.py` & `tkadw-0.2.2/tkadw/tkite/gtk/button.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/entry.py` & `tkadw-0.2.2/tkadw/tkite/gtk/entry.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/frame.py` & `tkadw-0.2.2/tkadw/tkite/gtk/frame.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/notebook.py` & `tkadw-0.2.2/tkadw/tkite/gtk/notebook.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/tkadw/tkite/gtk/textbox.py` & `tkadw-0.2.2/tkadw/tkite/gtk/textbox.py`

 * *Files identical despite different names*

### Comparing `tkadw-0.2.1/PKG-INFO` & `tkadw-0.2.2/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: tkadw
-Version: 0.2.1
+Version: 0.2.2
 Summary: extra for tkinter
 Author: XiangQinxi
 Author-email: 1379773753@qq.com
 Requires-Python: >=3.6,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
@@ -236,7 +236,18 @@
 > 
 >> `203`修复各别解释器类似注释的错误
 
 > `0.2.1`
 >> `211`扩充README文档
 >
 >> `212`新增组件`Adw`
+> 
+>> `213`删除多余文件
+
+> `0.2.2` 
+>> `221`扩展额外界面库`BiliBili`，根据`BiliBili桌面版`设计
+> 
+>> `222`修复`palette`修改完后没完全修改配色的问题
+> 
+>> `223`扩展额外界面库`Win11`，根据`Sunvalley`设计
+> 
+>> `224`修复`AdwDrawButton`类边框遮挡的问题
```


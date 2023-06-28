# Comparing `tmp/FuncsForSPO-6.1.5.tar.gz` & `tmp/FuncsForSPO-6.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "FuncsForSPO-6.1.5.tar", last modified: Mon Jun 26 15:11:17 2023, max compression
+gzip compressed data, was "FuncsForSPO-6.2.0.tar", last modified: Wed Jun 28 13:42:59 2023, max compression
```

## Comparing `FuncsForSPO-6.1.5.tar` & `FuncsForSPO-6.2.0.tar`

### file list

```diff
@@ -1,85 +1,86 @@
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.694553 FuncsForSPO-6.1.5/
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.033790 FuncsForSPO-6.1.5/FuncsForSPO/
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.107194 FuncsForSPO-6.1.5/FuncsForSPO/femails/
--rw-rw-rw-   0        0        0       86 2022-10-17 17:23:21.000000 FuncsForSPO-6.1.5/FuncsForSPO/femails/__init__.py
--rw-rw-rw-   0        0        0     7124 2023-03-30 20:56:34.000000 FuncsForSPO-6.1.5/FuncsForSPO/femails/femails.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.123237 FuncsForSPO-6.1.5/FuncsForSPO/fexceptions/
--rw-rw-rw-   0        0        0       18 2022-08-09 00:49:14.000000 FuncsForSPO-6.1.5/FuncsForSPO/fexceptions/__init__.py
--rw-rw-rw-   0        0        0      602 2022-12-18 16:11:53.000000 FuncsForSPO-6.1.5/FuncsForSPO/fexceptions/exceptions.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.144380 FuncsForSPO-6.1.5/FuncsForSPO/fftp/
--rw-rw-rw-   0        0        0       83 2022-08-09 00:49:14.000000 FuncsForSPO-6.1.5/FuncsForSPO/fftp/__init__.py
--rw-rw-rw-   0        0        0     6205 2022-12-16 20:50:05.000000 FuncsForSPO-6.1.5/FuncsForSPO/fftp/fftp.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.171971 FuncsForSPO-6.1.5/FuncsForSPO/fgpt/
--rw-rw-rw-   0        0        0      886 2023-06-24 20:49:12.000000 FuncsForSPO-6.1.5/FuncsForSPO/fgpt/__fgpt.py
--rw-rw-rw-   0        0        0        0 2023-06-24 21:16:46.000000 FuncsForSPO-6.1.5/FuncsForSPO/fgpt/__init__.py
--rw-rw-rw-   0        0        0     2419 2023-06-09 19:08:44.000000 FuncsForSPO-6.1.5/FuncsForSPO/fgpt/base.py
--rw-rw-rw-   0        0        0    14672 2023-06-26 14:09:10.000000 FuncsForSPO-6.1.5/FuncsForSPO/fgpt/fgpt.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.181117 FuncsForSPO-6.1.5/FuncsForSPO/flanguage/
--rw-rw-rw-   0        0        0        0 2023-06-05 14:56:28.000000 FuncsForSPO-6.1.5/FuncsForSPO/flanguage/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.204298 FuncsForSPO-6.1.5/FuncsForSPO/flanguage/translator/
--rw-rw-rw-   0        0        0        0 2023-06-05 14:56:28.000000 FuncsForSPO-6.1.5/FuncsForSPO/flanguage/translator/__init__.py
--rw-rw-rw-   0        0        0     4400 2023-06-20 16:22:20.000000 FuncsForSPO-6.1.5/FuncsForSPO/flanguage/translator/__translator.py
--rw-rw-rw-   0        0        0     2482 2023-06-18 01:12:40.000000 FuncsForSPO-6.1.5/FuncsForSPO/flanguage/translator/base.py
--rw-rw-rw-   0        0        0      829 2023-06-20 16:21:06.000000 FuncsForSPO-6.1.5/FuncsForSPO/flanguage/translator/translator.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.218305 FuncsForSPO-6.1.5/FuncsForSPO/fopenpyxl/
--rw-rw-rw-   0        0        0       83 2022-08-09 00:49:14.000000 FuncsForSPO-6.1.5/FuncsForSPO/fopenpyxl/__init__.py
--rw-rw-rw-   0        0        0    11048 2022-08-16 17:53:19.000000 FuncsForSPO-6.1.5/FuncsForSPO/fopenpyxl/openpyxl_funcs.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.227201 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/
--rw-rw-rw-   0        0        0       18 2023-06-02 20:07:40.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.279577 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/
--rw-rw-rw-   0        0        0      195 2023-06-02 20:07:25.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/__init__.py
--rw-rw-rw-   0        0        0     8203 2023-06-19 21:37:07.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/__pdfanalyser.py
--rw-rw-rw-   0        0        0     2419 2023-06-09 19:08:44.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/base.py
--rw-rw-rw-   0        0        0     1138 2023-06-09 17:41:46.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v1.py
--rw-rw-rw-   0        0        0     2019 2023-06-07 16:48:53.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v2.py
--rw-rw-rw-   0        0        0     1340 2023-06-17 20:27:40.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v3.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.312054 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fcompress/
--rw-rw-rw-   0        0        0     9145 2023-06-06 21:38:19.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fcompress/__compress_online.py
--rw-rw-rw-   0        0        0      226 2022-11-17 11:12:39.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fcompress/__init__.py
--rw-rw-rw-   0        0        0     1640 2023-06-06 21:39:15.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fcompress/compress.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.340156 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fhtml_to_pdf/
--rw-rw-rw-   0        0        0     7094 2023-02-23 17:58:00.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fhtml_to_pdf/__html_to_pdf.py
--rw-rw-rw-   0        0        0      226 2022-11-17 11:12:39.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fhtml_to_pdf/__init__.py
--rw-rw-rw-   0        0        0     1577 2022-11-30 15:19:23.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fhtml_to_pdf/html_to_pdf.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.386098 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fimgpdf/
--rw-rw-rw-   0        0        0    12539 2023-02-23 17:58:26.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fimgpdf/img_to_pdf.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.442922 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/
--rw-rw-rw-   0        0        0      129 2022-11-17 11:12:22.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/__init__.py
--rw-rw-rw-   0        0        0     8709 2023-06-18 14:37:35.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/__ocr_online.py
--rw-rw-rw-   0        0        0     1034 2023-06-18 14:17:07.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/__ocr_online_v2.py
--rw-rw-rw-   0        0        0     2482 2023-06-18 01:12:40.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/base.py
--rw-rw-rw-   0        0        0     8949 2023-06-26 15:10:17.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/orc.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.470429 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/pdfutils/
--rw-rw-rw-   0        0        0       18 2023-06-02 20:07:40.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/pdfutils/__init__.py
--rw-rw-rw-   0        0        0     3357 2023-06-18 14:25:59.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpdf/pdfutils/pdfutils.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.494502 FuncsForSPO-6.1.5/FuncsForSPO/fpysimplegui/
--rw-rw-rw-   0        0        0       83 2022-08-09 00:49:14.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpysimplegui/__init__.py
--rw-rw-rw-   0        0        0     4696 2023-06-24 21:08:38.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpysimplegui/functions_for_sg.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.512557 FuncsForSPO-6.1.5/FuncsForSPO/fpython/
--rw-rw-rw-   0        0        0       25 2022-08-09 00:49:14.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpython/__init__.py
--rw-rw-rw-   0        0        0    55610 2023-06-26 14:09:24.000000 FuncsForSPO-6.1.5/FuncsForSPO/fpython/functions_for_py.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.545511 FuncsForSPO-6.1.5/FuncsForSPO/fregex/
--rw-rw-rw-   0        0        0       24 2022-08-09 00:49:14.000000 FuncsForSPO-6.1.5/FuncsForSPO/fregex/__init__.py
--rw-rw-rw-   0        0        0    10378 2023-06-24 21:07:45.000000 FuncsForSPO-6.1.5/FuncsForSPO/fregex/functions_re.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.560583 FuncsForSPO-6.1.5/FuncsForSPO/fselenium/
--rw-rw-rw-   0        0        0       27 2022-08-09 00:49:14.000000 FuncsForSPO-6.1.5/FuncsForSPO/fselenium/__init__.py
--rw-rw-rw-   0        0        0    39081 2023-06-26 14:06:50.000000 FuncsForSPO-6.1.5/FuncsForSPO/fselenium/functions_selenium.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.589192 FuncsForSPO-6.1.5/FuncsForSPO/fsqlite/
--rw-rw-rw-   0        0        0       25 2022-08-09 00:49:14.000000 FuncsForSPO-6.1.5/FuncsForSPO/fsqlite/__init__.py
--rw-rw-rw-   0        0        0     1610 2022-12-18 16:12:26.000000 FuncsForSPO-6.1.5/FuncsForSPO/fsqlite/sqlite_functions.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.602738 FuncsForSPO-6.1.5/FuncsForSPO/fwinotify/
--rw-rw-rw-   0        0        0       16 2022-09-12 21:24:16.000000 FuncsForSPO-6.1.5/FuncsForSPO/fwinotify/__init__.py
--rw-rw-rw-   0        0        0     4896 2022-09-12 21:21:52.000000 FuncsForSPO-6.1.5/FuncsForSPO/fwinotify/fwinotify.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.612280 FuncsForSPO-6.1.5/FuncsForSPO/utils/
--rw-rw-rw-   0        0        0   122169 2023-06-24 20:59:57.000000 FuncsForSPO-6.1.5/FuncsForSPO/utils/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-26 15:11:17.094169 FuncsForSPO-6.1.5/FuncsForSPO.egg-info/
--rw-rw-rw-   0        0        0     8023 2023-06-26 15:11:16.000000 FuncsForSPO-6.1.5/FuncsForSPO.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     2082 2023-06-26 15:11:16.000000 FuncsForSPO-6.1.5/FuncsForSPO.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-26 15:11:16.000000 FuncsForSPO-6.1.5/FuncsForSPO.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      220 2023-06-26 15:11:16.000000 FuncsForSPO-6.1.5/FuncsForSPO.egg-info/requires.txt
--rw-rw-rw-   0        0        0      475 2023-06-26 15:11:16.000000 FuncsForSPO-6.1.5/FuncsForSPO.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     1074 2022-12-02 16:50:42.000000 FuncsForSPO-6.1.5/LICENSE
--rw-rw-rw-   0        0        0     8023 2023-06-26 15:11:17.691549 FuncsForSPO-6.1.5/PKG-INFO
--rw-rw-rw-   0        0        0     7604 2023-06-20 16:05:40.000000 FuncsForSPO-6.1.5/README.md
--rw-rw-rw-   0        0        0       42 2023-06-26 15:11:17.695550 FuncsForSPO-6.1.5/setup.cfg
--rw-rw-rw-   0        0        0     2663 2023-06-26 15:11:05.000000 FuncsForSPO-6.1.5/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.958651 FuncsForSPO-6.2.0/
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.596054 FuncsForSPO-6.2.0/FuncsForSPO/
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.649278 FuncsForSPO-6.2.0/FuncsForSPO/femails/
+-rw-rw-rw-   0        0        0       86 2022-10-17 17:23:21.000000 FuncsForSPO-6.2.0/FuncsForSPO/femails/__init__.py
+-rw-rw-rw-   0        0        0     7124 2023-03-30 20:56:34.000000 FuncsForSPO-6.2.0/FuncsForSPO/femails/femails.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.658202 FuncsForSPO-6.2.0/FuncsForSPO/fexceptions/
+-rw-rw-rw-   0        0        0       18 2022-08-09 00:49:14.000000 FuncsForSPO-6.2.0/FuncsForSPO/fexceptions/__init__.py
+-rw-rw-rw-   0        0        0      602 2022-12-18 16:11:53.000000 FuncsForSPO-6.2.0/FuncsForSPO/fexceptions/exceptions.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.668208 FuncsForSPO-6.2.0/FuncsForSPO/fftp/
+-rw-rw-rw-   0        0        0       83 2022-08-09 00:49:14.000000 FuncsForSPO-6.2.0/FuncsForSPO/fftp/__init__.py
+-rw-rw-rw-   0        0        0     6205 2022-12-16 20:50:05.000000 FuncsForSPO-6.2.0/FuncsForSPO/fftp/fftp.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.687738 FuncsForSPO-6.2.0/FuncsForSPO/fgpt/
+-rw-rw-rw-   0        0        0      886 2023-06-24 20:49:12.000000 FuncsForSPO-6.2.0/FuncsForSPO/fgpt/__fgpt.py
+-rw-rw-rw-   0        0        0        0 2023-06-24 21:16:46.000000 FuncsForSPO-6.2.0/FuncsForSPO/fgpt/__init__.py
+-rw-rw-rw-   0        0        0     2419 2023-06-09 19:08:44.000000 FuncsForSPO-6.2.0/FuncsForSPO/fgpt/base.py
+-rw-rw-rw-   0        0        0    14672 2023-06-26 14:09:10.000000 FuncsForSPO-6.2.0/FuncsForSPO/fgpt/fgpt.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.691738 FuncsForSPO-6.2.0/FuncsForSPO/flanguage/
+-rw-rw-rw-   0        0        0        0 2023-06-05 14:56:28.000000 FuncsForSPO-6.2.0/FuncsForSPO/flanguage/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.709599 FuncsForSPO-6.2.0/FuncsForSPO/flanguage/translator/
+-rw-rw-rw-   0        0        0        0 2023-06-05 14:56:28.000000 FuncsForSPO-6.2.0/FuncsForSPO/flanguage/translator/__init__.py
+-rw-rw-rw-   0        0        0     4400 2023-06-20 16:22:20.000000 FuncsForSPO-6.2.0/FuncsForSPO/flanguage/translator/__translator.py
+-rw-rw-rw-   0        0        0     2482 2023-06-18 01:12:40.000000 FuncsForSPO-6.2.0/FuncsForSPO/flanguage/translator/base.py
+-rw-rw-rw-   0        0        0      829 2023-06-20 16:21:06.000000 FuncsForSPO-6.2.0/FuncsForSPO/flanguage/translator/translator.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.720598 FuncsForSPO-6.2.0/FuncsForSPO/fopenpyxl/
+-rw-rw-rw-   0        0        0       83 2022-08-09 00:49:14.000000 FuncsForSPO-6.2.0/FuncsForSPO/fopenpyxl/__init__.py
+-rw-rw-rw-   0        0        0    11048 2022-08-16 17:53:19.000000 FuncsForSPO-6.2.0/FuncsForSPO/fopenpyxl/openpyxl_funcs.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.724601 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/
+-rw-rw-rw-   0        0        0       18 2023-06-02 20:07:40.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.767505 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/
+-rw-rw-rw-   0        0        0      195 2023-06-02 20:07:25.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/__init__.py
+-rw-rw-rw-   0        0        0    10975 2023-06-28 13:37:03.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/__pdfanalyser.py
+-rw-rw-rw-   0        0        0     2419 2023-06-09 19:08:44.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/base.py
+-rw-rw-rw-   0        0        0     1138 2023-06-09 17:41:46.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v1.py
+-rw-rw-rw-   0        0        0     2019 2023-06-07 16:48:53.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v2.py
+-rw-rw-rw-   0        0        0     1340 2023-06-28 13:21:40.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v3.py
+-rw-rw-rw-   0        0        0      586 2023-06-28 13:25:32.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v4.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.783066 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fcompress/
+-rw-rw-rw-   0        0        0     9145 2023-06-06 21:38:19.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fcompress/__compress_online.py
+-rw-rw-rw-   0        0        0      226 2022-11-17 11:12:39.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fcompress/__init__.py
+-rw-rw-rw-   0        0        0     1640 2023-06-06 21:39:15.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fcompress/compress.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.799104 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fhtml_to_pdf/
+-rw-rw-rw-   0        0        0     7094 2023-02-23 17:58:00.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fhtml_to_pdf/__html_to_pdf.py
+-rw-rw-rw-   0        0        0      226 2022-11-17 11:12:39.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fhtml_to_pdf/__init__.py
+-rw-rw-rw-   0        0        0     1577 2022-11-30 15:19:23.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fhtml_to_pdf/html_to_pdf.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.803104 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fimgpdf/
+-rw-rw-rw-   0        0        0    12539 2023-02-23 17:58:26.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fimgpdf/img_to_pdf.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.828113 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/
+-rw-rw-rw-   0        0        0      129 2022-11-17 11:12:22.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/__init__.py
+-rw-rw-rw-   0        0        0     8709 2023-06-18 14:37:35.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/__ocr_online.py
+-rw-rw-rw-   0        0        0     1034 2023-06-18 14:17:07.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/__ocr_online_v2.py
+-rw-rw-rw-   0        0        0     2482 2023-06-18 01:12:40.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/base.py
+-rw-rw-rw-   0        0        0     8949 2023-06-26 15:10:17.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/orc.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.838123 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/pdfutils/
+-rw-rw-rw-   0        0        0       18 2023-06-02 20:07:40.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/pdfutils/__init__.py
+-rw-rw-rw-   0        0        0     3357 2023-06-18 14:25:59.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpdf/pdfutils/pdfutils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.849207 FuncsForSPO-6.2.0/FuncsForSPO/fpysimplegui/
+-rw-rw-rw-   0        0        0       83 2022-08-09 00:49:14.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpysimplegui/__init__.py
+-rw-rw-rw-   0        0        0     4696 2023-06-24 21:08:38.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpysimplegui/functions_for_sg.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.858206 FuncsForSPO-6.2.0/FuncsForSPO/fpython/
+-rw-rw-rw-   0        0        0       25 2022-08-09 00:49:14.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpython/__init__.py
+-rw-rw-rw-   0        0        0    55610 2023-06-26 14:09:24.000000 FuncsForSPO-6.2.0/FuncsForSPO/fpython/functions_for_py.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.868213 FuncsForSPO-6.2.0/FuncsForSPO/fregex/
+-rw-rw-rw-   0        0        0       24 2022-08-09 00:49:14.000000 FuncsForSPO-6.2.0/FuncsForSPO/fregex/__init__.py
+-rw-rw-rw-   0        0        0    10378 2023-06-24 21:07:45.000000 FuncsForSPO-6.2.0/FuncsForSPO/fregex/functions_re.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.877205 FuncsForSPO-6.2.0/FuncsForSPO/fselenium/
+-rw-rw-rw-   0        0        0       27 2022-08-09 00:49:14.000000 FuncsForSPO-6.2.0/FuncsForSPO/fselenium/__init__.py
+-rw-rw-rw-   0        0        0    39081 2023-06-26 14:06:50.000000 FuncsForSPO-6.2.0/FuncsForSPO/fselenium/functions_selenium.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.888871 FuncsForSPO-6.2.0/FuncsForSPO/fsqlite/
+-rw-rw-rw-   0        0        0       25 2022-08-09 00:49:14.000000 FuncsForSPO-6.2.0/FuncsForSPO/fsqlite/__init__.py
+-rw-rw-rw-   0        0        0     1610 2022-12-18 16:12:26.000000 FuncsForSPO-6.2.0/FuncsForSPO/fsqlite/sqlite_functions.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.897420 FuncsForSPO-6.2.0/FuncsForSPO/fwinotify/
+-rw-rw-rw-   0        0        0       16 2022-09-12 21:24:16.000000 FuncsForSPO-6.2.0/FuncsForSPO/fwinotify/__init__.py
+-rw-rw-rw-   0        0        0     4896 2022-09-12 21:21:52.000000 FuncsForSPO-6.2.0/FuncsForSPO/fwinotify/fwinotify.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.903384 FuncsForSPO-6.2.0/FuncsForSPO/utils/
+-rw-rw-rw-   0        0        0   122169 2023-06-24 20:59:57.000000 FuncsForSPO-6.2.0/FuncsForSPO/utils/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:42:59.639063 FuncsForSPO-6.2.0/FuncsForSPO.egg-info/
+-rw-rw-rw-   0        0        0     8023 2023-06-28 13:42:59.000000 FuncsForSPO-6.2.0/FuncsForSPO.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     2127 2023-06-28 13:42:59.000000 FuncsForSPO-6.2.0/FuncsForSPO.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:42:59.000000 FuncsForSPO-6.2.0/FuncsForSPO.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      220 2023-06-28 13:42:59.000000 FuncsForSPO-6.2.0/FuncsForSPO.egg-info/requires.txt
+-rw-rw-rw-   0        0        0      475 2023-06-28 13:42:59.000000 FuncsForSPO-6.2.0/FuncsForSPO.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     1074 2022-12-02 16:50:42.000000 FuncsForSPO-6.2.0/LICENSE
+-rw-rw-rw-   0        0        0     8023 2023-06-28 13:42:59.955652 FuncsForSPO-6.2.0/PKG-INFO
+-rw-rw-rw-   0        0        0     7604 2023-06-20 16:05:40.000000 FuncsForSPO-6.2.0/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:42:59.959653 FuncsForSPO-6.2.0/setup.cfg
+-rw-rw-rw-   0        0        0     2663 2023-06-28 13:42:51.000000 FuncsForSPO-6.2.0/setup.py
```

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/femails/femails.py` & `FuncsForSPO-6.2.0/FuncsForSPO/femails/femails.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fexceptions/exceptions.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fexceptions/exceptions.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fftp/fftp.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fftp/fftp.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fgpt/__fgpt.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fgpt/__fgpt.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fgpt/base.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fgpt/base.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fgpt/fgpt.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fgpt/fgpt.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/flanguage/translator/__translator.py` & `FuncsForSPO-6.2.0/FuncsForSPO/flanguage/translator/__translator.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/flanguage/translator/base.py` & `FuncsForSPO-6.2.0/FuncsForSPO/flanguage/translator/base.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/flanguage/translator/translator.py` & `FuncsForSPO-6.2.0/FuncsForSPO/flanguage/translator/translator.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fopenpyxl/openpyxl_funcs.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fopenpyxl/openpyxl_funcs.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/__pdfanalyser.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/__pdfanalyser.py`

 * *Files 12% similar despite different names*

```diff
@@ -158,8 +158,66 @@
         url = self.DRIVER.current_url
         id_ = re.sub(r'.*?/chat/', '', url)
         self.DRIVER.get('https://askyourpdf.com/delete')
         espera_elemento_e_envia_send_keys(self.WDW, id_, (By.CSS_SELECTOR, 'input'))
         espera_elemento_disponivel_e_clica(self.WDW, (By.CSS_SELECTOR, 'button'))
         sleep(2)
         faz_log('Documento deletado da base de dados!')
-        os.remove(self.TXT_CONTENT)
+        os.remove(self.TXT_CONTENT)
+
+
+class GPTPDFV3(BotMain):    
+    def __init__(self, file_pdf: str, prompt:str, headless: bool=True) -> str:
+        self.FILE_PATH = os.path.abspath(file_pdf)
+        self.PROMPT = prompt
+        self.HEADLESS = headless
+        
+        super().__init__(self.HEADLESS)
+    
+    def run(self):
+        try:
+            faz_log('Indo para chatpdf')
+            self.DRIVER.get('https://www.chatpdf.com/')
+            espera_elemento(self.WDW, (By.CSS_SELECTOR, 'input[type="file"]'), in_dom=True)
+            self.DRIVER.find_element(By.CSS_SELECTOR, 'input[type="file"]').send_keys(self.FILE_PATH)
+            
+            faz_log('Documento enviado, aguardando entrada para o prompt')
+            espera_input_limpa_e_envia_send_keys(self.WDW130, self.PROMPT+' Adicione "AI RESPONSE" apenas no final da sua resposta (isso é de suma importância) e deve ser tudo em português!', (By.CSS_SELECTOR, 'textarea[placeholder="Ask any question…"]'))
+            espera_elemento_disponivel_e_clica(self.WDW130, (By.CSS_SELECTOR, 'button[type="button"]'))
+            faz_log('Esperando a resposta')
+            start_time = time.time()
+            timeout = 180  # Tempo limite em segundos
+
+            while True:
+                try:
+                    text = espera_e_retorna_lista_de_elementos_text(self.WDW, (By.CSS_SELECTOR, 'div[class="chat-message-row ai"]'))[-1]
+                    faz_log(f'Resposta até agora: [green]{text}[/green]')
+                    time.sleep(7)
+                except:
+                    # Lidar com exceções, se necessário
+                    pass
+
+                if 'AI RES' in text:
+                    break
+                if 'try again.' in text.lower():
+                    text = text + '  Não foi possível ter uma interpretação adequada. Tente outro prompt'
+                    break
+
+                elapsed_time = time.time() - start_time
+                if elapsed_time >= timeout:
+                    # Tempo limite atingido, interromper o loop
+                    break
+            faz_log('Recuperando o id do documento')
+            self.apaga_arquivo_da_base_do_site()
+            self.DRIVER.quit()
+            return text
+        except Exception as e:
+            faz_log(repr(e), 'c*')
+            faz_log(self.DRIVER.get_screenshot_as_base64(), 'i*')
+            self.DRIVER.quit()
+            raise ErroPDFAIException
+        
+    def apaga_arquivo_da_base_do_site(self):
+        espera_elemento_disponivel_e_clica(self.WDW, (By.CSS_SELECTOR, 'span[aria-label="delete"]'))
+        espera_elemento_disponivel_e_clica(self.WDW, (By.CSS_SELECTOR, 'button[class*="danger"]'))
+        sleep(2)
+        faz_log('Documento deletado da base de dados!')
```

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/base.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/base.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v1.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v1.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v2.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v2.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v3.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fanalyser/pdfanalyser_v3.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fcompress/__compress_online.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fcompress/__compress_online.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fcompress/compress.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fcompress/compress.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fhtml_to_pdf/__html_to_pdf.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fhtml_to_pdf/__html_to_pdf.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fhtml_to_pdf/html_to_pdf.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fhtml_to_pdf/html_to_pdf.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/fimgpdf/img_to_pdf.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/fimgpdf/img_to_pdf.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/__ocr_online.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/__ocr_online.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/__ocr_online_v2.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/__ocr_online_v2.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/base.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/base.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/focr/orc.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/focr/orc.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpdf/pdfutils/pdfutils.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpdf/pdfutils/pdfutils.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpysimplegui/functions_for_sg.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpysimplegui/functions_for_sg.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fpython/functions_for_py.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fpython/functions_for_py.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fregex/functions_re.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fregex/functions_re.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fselenium/functions_selenium.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fselenium/functions_selenium.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fsqlite/sqlite_functions.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fsqlite/sqlite_functions.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/fwinotify/fwinotify.py` & `FuncsForSPO-6.2.0/FuncsForSPO/fwinotify/fwinotify.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO/utils/utils.py` & `FuncsForSPO-6.2.0/FuncsForSPO/utils/utils.py`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO.egg-info/PKG-INFO` & `FuncsForSPO-6.2.0/FuncsForSPO.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: FuncsForSPO
-Version: 6.1.5
+Version: 6.2.0
 Summary: Funções Para Melhorar Desenvolvimento de Robôs com Selenium
 Home-page: https://github.com/githubpaycon/FuncsForSPO
 Author: Gabriel Lopes de Souza
 Author-email: githubpaycon@gmail.com
 License: MIT License
 Keywords: Funções Para Melhorar Desenvolvimento de Robôs com Selenium
 Description-Content-Type: text/markdown
```

### Comparing `FuncsForSPO-6.1.5/FuncsForSPO.egg-info/SOURCES.txt` & `FuncsForSPO-6.2.0/FuncsForSPO.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -26,14 +26,15 @@
 FuncsForSPO/fpdf/__init__.py
 FuncsForSPO/fpdf/fanalyser/__init__.py
 FuncsForSPO/fpdf/fanalyser/__pdfanalyser.py
 FuncsForSPO/fpdf/fanalyser/base.py
 FuncsForSPO/fpdf/fanalyser/pdfanalyser_v1.py
 FuncsForSPO/fpdf/fanalyser/pdfanalyser_v2.py
 FuncsForSPO/fpdf/fanalyser/pdfanalyser_v3.py
+FuncsForSPO/fpdf/fanalyser/pdfanalyser_v4.py
 FuncsForSPO/fpdf/fcompress/__compress_online.py
 FuncsForSPO/fpdf/fcompress/__init__.py
 FuncsForSPO/fpdf/fcompress/compress.py
 FuncsForSPO/fpdf/fhtml_to_pdf/__html_to_pdf.py
 FuncsForSPO/fpdf/fhtml_to_pdf/__init__.py
 FuncsForSPO/fpdf/fhtml_to_pdf/html_to_pdf.py
 FuncsForSPO/fpdf/fimgpdf/img_to_pdf.py
```

### Comparing `FuncsForSPO-6.1.5/LICENSE` & `FuncsForSPO-6.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/PKG-INFO` & `FuncsForSPO-6.2.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: FuncsForSPO
-Version: 6.1.5
+Version: 6.2.0
 Summary: Funções Para Melhorar Desenvolvimento de Robôs com Selenium
 Home-page: https://github.com/githubpaycon/FuncsForSPO
 Author: Gabriel Lopes de Souza
 Author-email: githubpaycon@gmail.com
 License: MIT License
 Keywords: Funções Para Melhorar Desenvolvimento de Robôs com Selenium
 Description-Content-Type: text/markdown
```

### Comparing `FuncsForSPO-6.1.5/README.md` & `FuncsForSPO-6.2.0/README.md`

 * *Files identical despite different names*

### Comparing `FuncsForSPO-6.1.5/setup.py` & `FuncsForSPO-6.2.0/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import os
 from setuptools import setup
 
-version = '6.1.5'
+version = '6.2.0'
 
 with open("README.md", "r", encoding='utf-8') as fh:
     readme = fh.read()
     setup(
         name='FuncsForSPO',
         version=version,
         url='https://github.com/githubpaycon/FuncsForSPO',
```


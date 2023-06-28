# Comparing `tmp/biomojify-0.3.0.0.tar.gz` & `tmp/biomojify-0.3.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/biomojify-0.3.0.0.tar", last modified: Tue Jul 28 13:17:33 2020, max compression
+gzip compressed data, was "biomojify-0.3.1.0.tar", last modified: Wed Jun 28 06:08:25 2023, max compression
```

## Comparing `biomojify-0.3.0.0.tar` & `biomojify-0.3.1.0.tar`

### file list

```diff
@@ -1,17 +1,18 @@
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2020-07-28 13:17:33.790058 biomojify-0.3.0.0/
--rw-r--r--   0 runner    (1001) docker     (116)      353 2020-07-28 13:17:33.790058 biomojify-0.3.0.0/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (116)    10631 2020-07-28 13:17:27.000000 biomojify-0.3.0.0/README.md
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2020-07-28 13:17:33.786058 biomojify-0.3.0.0/biomojify/
--rw-r--r--   0 runner    (1001) docker     (116)        0 2020-07-28 13:17:27.000000 biomojify-0.3.0.0/biomojify/__init__.py
--rw-r--r--   0 runner    (1001) docker     (116)    22320 2020-07-28 13:17:27.000000 biomojify-0.3.0.0/biomojify/biomojify.py
--rw-r--r--   0 runner    (1001) docker     (116)      698 2020-07-28 13:17:27.000000 biomojify-0.3.0.0/biomojify/biomojify_map.py
--rw-r--r--   0 runner    (1001) docker     (116)     3852 2020-07-28 13:17:27.000000 biomojify-0.3.0.0/biomojify/biomojify_test.py
-drwxr-xr-x   0 runner    (1001) docker     (116)        0 2020-07-28 13:17:33.790058 biomojify-0.3.0.0/biomojify.egg-info/
--rw-r--r--   0 runner    (1001) docker     (116)      353 2020-07-28 13:17:33.000000 biomojify-0.3.0.0/biomojify.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (116)      318 2020-07-28 13:17:33.000000 biomojify-0.3.0.0/biomojify.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (116)        1 2020-07-28 13:17:33.000000 biomojify-0.3.0.0/biomojify.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (116)       56 2020-07-28 13:17:33.000000 biomojify-0.3.0.0/biomojify.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (116)       23 2020-07-28 13:17:33.000000 biomojify-0.3.0.0/biomojify.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (116)       10 2020-07-28 13:17:33.000000 biomojify-0.3.0.0/biomojify.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (116)       38 2020-07-28 13:17:33.790058 biomojify-0.3.0.0/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (116)      691 2020-07-28 13:17:27.000000 biomojify-0.3.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:08:25.872749 biomojify-0.3.1.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1460 2023-06-28 06:08:14.000000 biomojify-0.3.1.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)      345 2023-06-28 06:08:25.872749 biomojify-0.3.1.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    10631 2023-06-28 06:08:14.000000 biomojify-0.3.1.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:08:25.872749 biomojify-0.3.1.0/biomojify/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 06:08:14.000000 biomojify-0.3.1.0/biomojify/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    23008 2023-06-28 06:08:14.000000 biomojify-0.3.1.0/biomojify/biomojify.py
+-rw-r--r--   0 runner    (1001) docker     (123)      698 2023-06-28 06:08:14.000000 biomojify-0.3.1.0/biomojify/biomojify_map.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3852 2023-06-28 06:08:14.000000 biomojify-0.3.1.0/biomojify/biomojify_test.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 06:08:25.872749 biomojify-0.3.1.0/biomojify.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)      345 2023-06-28 06:08:25.000000 biomojify-0.3.1.0/biomojify.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      326 2023-06-28 06:08:25.000000 biomojify-0.3.1.0/biomojify.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 06:08:25.000000 biomojify-0.3.1.0/biomojify.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       55 2023-06-28 06:08:25.000000 biomojify-0.3.1.0/biomojify.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 06:08:25.000000 biomojify-0.3.1.0/biomojify.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 06:08:25.000000 biomojify-0.3.1.0/biomojify.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 06:08:25.872749 biomojify-0.3.1.0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      692 2023-06-28 06:08:14.000000 biomojify-0.3.1.0/setup.py
```

### Comparing `biomojify-0.3.0.0/README.md` & `biomojify-0.3.1.0/README.md`

 * *Files identical despite different names*

### Comparing `biomojify-0.3.0.0/biomojify/biomojify.py` & `biomojify-0.3.1.0/biomojify/biomojify.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,15 +16,15 @@
 import pkg_resources
 from Bio import SeqIO
 from fastqe import fastqe_map as emaps
 from pyemojify import emojify 
 from Bio.SeqIO import QualityIO
 import binascii
 import gzip
-from . import biomojify_map
+# from . import biomojify_map
 import ast
 import vcf
 from Bio.SeqRecord import SeqRecord
 from Bio.Seq import Seq
 
 
 
@@ -51,14 +51,48 @@
     'A': '🥑',  # avocado not in pyemojify, trying a failthrough which works for the noemoji mode
     'C': ':corn:',
     'T': ':tomato:',
     'G': ':grapes:',
     'N': ':question:'
 }
 
+# only suitable for english speakers
+prot_seq_emoji_map = {
+    'A': ':green_apple:',
+    'B': ':banana:',
+    'C': ':cherries:',
+    'D': ':doughnut:',
+    'E': ':elephant:',
+    'F': ':fries:',
+    'G': ':grapes:',
+    'H': ':hamburger:',
+    'I': ':icecream:',
+    'J': ':jeans:',
+    'K': ':key:',
+    'L': ':lemon:',
+    'M': ':mushroom:',
+    'N': ':nose:',
+    'O': ':octopus:',
+    'P': ':pineapple:',
+    'Q': ':princess:',
+    'R': ':rabbit:',
+    'S': ':strawberry:',
+    'T': ':tomato:',
+    'U': ':umbrella:',
+    'V': ':volcano:',
+    'W': ':watermelon:',
+    'X': ':x:',
+    'Y': ':sailboat:',
+    '*': ':hand:',
+    '-': ':wavy_dash:',
+}
+
+prot_scale = "ABCDEFGHIJKLMNOPQRSTUVWXY*-"
+
+
 
 
 try:
     PROGRAM_VERSION = pkg_resources.require(PROGRAM_NAME)[0].version
 except pkg_resources.DistributionNotFound:
     PROGRAM_VERSION = "undefined_version"
 
@@ -403,15 +437,15 @@
 
 # 
 # def convert_filetype(options):
 #     return
 
 
 def convert_fasta_protein(options):
-    convert_fasta(options, mapping_dict=biomojify_map.prot_seq_emoji_map)
+    convert_fasta(options, mapping_dict=prot_seq_emoji_map)
 
     return
 
 
 def convert_fasta(options, mapping_dict=local_seq_emoji_map):
     '''Convert FASTA file to emoji. If no FASTA files are specified on the command line then
     read from the standard input (stdin).
```

### Comparing `biomojify-0.3.0.0/biomojify/biomojify_map.py` & `biomojify-0.3.1.0/biomojify/biomojify_map.py`

 * *Files identical despite different names*

### Comparing `biomojify-0.3.0.0/biomojify/biomojify_test.py` & `biomojify-0.3.1.0/biomojify/biomojify_test.py`

 * *Files identical despite different names*

### Comparing `biomojify-0.3.0.0/setup.py` & `biomojify-0.3.1.0/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -3,21 +3,21 @@
 from setuptools import setup
 
 LONG_DESCRIPTION = """The program reads one or more input FASTA or FASTQ files and converts them to emoji."""
 
 
 setup(
     name="biomojify",
-    version="0.3.0.0",
+    version="0.3.1.0",
     author="Andrew Lonsdale",
     author_email="andrew.lonsdale@lonsbio.com.au",
     packages=["biomojify"],
     package_dir={"biomojify": "biomojify"},
     entry_points={
         "console_scripts": ["biomojify = biomojify.biomojify:main"]
     },
     url="https://github.com/fastqe/biomojify",
     license="LICENSE",
     description=("Convert FASTQ and FASTA files to emoji."),
     long_description=(LONG_DESCRIPTION),
-    install_requires=["biopython","fastqe","pyvcf"],
+    install_requires=["biopython","fastqe","PyVCF3"],
 )
```


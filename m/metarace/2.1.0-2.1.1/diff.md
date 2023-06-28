# Comparing `tmp/metarace-2.1.0.tar.gz` & `tmp/metarace-2.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/home/ndf/dev/metarace/metarace/dist/.tmp-t6cs3kkj/metarace-2.1.0.tar", last modified: Tue Jun  6 07:09:46 2023, max compression
+gzip compressed data, was "metarace-2.1.1.tar", last modified: Wed Jun 28 01:35:08 2023, max compression
```

## Comparing `metarace-2.1.0.tar` & `metarace-2.1.1.tar`

### file list

```diff
@@ -1,45 +1,45 @@
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-06 07:09:46.000000 metarace-2.1.0/
--rw-------   0 ndf       (1000) ndf       (1000)     1092 2022-01-22 06:38:57.000000 metarace-2.1.0/LICENSE
--rw-r--r--   0 ndf       (1000) ndf       (1000)       28 2022-05-31 01:20:37.000000 metarace-2.1.0/MANIFEST.in
--rw-r--r--   0 ndf       (1000) ndf       (1000)     4229 2023-06-06 07:09:46.000000 metarace-2.1.0/PKG-INFO
--rw-------   0 ndf       (1000) ndf       (1000)     3710 2023-06-06 07:07:42.000000 metarace-2.1.0/README.md
--rw-r--r--   0 ndf       (1000) ndf       (1000)      795 2023-06-06 07:05:50.000000 metarace-2.1.0/pyproject.toml
--rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2023-06-06 07:09:46.000000 metarace-2.1.0/setup.cfg
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-06 07:09:46.000000 metarace-2.1.0/src/
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-06 07:09:46.000000 metarace-2.1.0/src/metarace/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     9387 2023-06-05 07:08:46.000000 metarace-2.1.0/src/metarace/__init__.py
--rw-------   0 ndf       (1000) ndf       (1000)     4276 2022-07-23 03:24:44.000000 metarace-2.1.0/src/metarace/countback.py
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-06 07:09:46.000000 metarace-2.1.0/src/metarace/data/
--rw-------   0 ndf       (1000) ndf       (1000)     3067 2022-01-22 22:18:40.000000 metarace-2.1.0/src/metarace/data/IOC_Codes.csv
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.0/src/metarace/data/bg_armfin.svg
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.0/src/metarace/data/bg_armint.svg
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.0/src/metarace/data/bg_armstart.svg
--rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.0/src/metarace/data/bg_idle.svg
--rw-r--r--   0 ndf       (1000) ndf       (1000)     2369 2022-01-22 22:18:40.000000 metarace-2.1.0/src/metarace/data/bg_src.svg
--rw-------   0 ndf       (1000) ndf       (1000)      520 2023-06-05 02:11:31.000000 metarace-2.1.0/src/metarace/data/metarace.json
--rw-------   0 ndf       (1000) ndf       (1000)     8729 2022-01-22 22:18:40.000000 metarace-2.1.0/src/metarace/data/metarace_icon.svg
--rw-------   0 ndf       (1000) ndf       (1000)     2048 2023-06-05 01:23:26.000000 metarace-2.1.0/src/metarace/data/pdf_template.json
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-06 07:09:46.000000 metarace-2.1.0/src/metarace/decoder/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     5730 2023-05-31 00:29:16.000000 metarace-2.1.0/src/metarace/decoder/__init__.py
--rw-------   0 ndf       (1000) ndf       (1000)    15033 2022-11-22 23:22:51.000000 metarace-2.1.0/src/metarace/decoder/rrs.py
--rw-------   0 ndf       (1000) ndf       (1000)    27089 2022-11-22 09:29:11.000000 metarace-2.1.0/src/metarace/decoder/rru.py
--rw-------   0 ndf       (1000) ndf       (1000)    17883 2023-05-31 00:54:01.000000 metarace-2.1.0/src/metarace/decoder/thbc.py
--rw-------   0 ndf       (1000) ndf       (1000)    11440 2023-05-31 00:23:56.000000 metarace-2.1.0/src/metarace/eventdb.py
--rw-------   0 ndf       (1000) ndf       (1000)     3733 2023-05-31 00:53:46.000000 metarace-2.1.0/src/metarace/export.py
--rw-------   0 ndf       (1000) ndf       (1000)     8795 2023-05-31 00:25:22.000000 metarace-2.1.0/src/metarace/gemini.py
--rw-------   0 ndf       (1000) ndf       (1000)     5878 2022-07-23 03:26:18.000000 metarace-2.1.0/src/metarace/htlib.py
--rw-------   0 ndf       (1000) ndf       (1000)     5644 2023-06-05 03:38:44.000000 metarace-2.1.0/src/metarace/jsonconfig.py
--rw-------   0 ndf       (1000) ndf       (1000)   199440 2023-06-05 03:38:44.000000 metarace-2.1.0/src/metarace/report.py
--rw-------   0 ndf       (1000) ndf       (1000)    17480 2023-06-04 10:42:55.000000 metarace-2.1.0/src/metarace/riderdb.py
--rw-------   0 ndf       (1000) ndf       (1000)    10290 2023-05-31 00:17:01.000000 metarace-2.1.0/src/metarace/sender.py
--rw-------   0 ndf       (1000) ndf       (1000)    18207 2023-06-02 02:39:09.000000 metarace-2.1.0/src/metarace/strops.py
--rw-r--r--   0 ndf       (1000) ndf       (1000)    13652 2022-11-14 06:21:05.000000 metarace-2.1.0/src/metarace/telegraph.py
--rw-------   0 ndf       (1000) ndf       (1000)    15088 2023-06-04 10:37:01.000000 metarace-2.1.0/src/metarace/timy.py
--rw-r--r--   0 ndf       (1000) ndf       (1000)    20930 2023-02-21 05:34:28.000000 metarace-2.1.0/src/metarace/tod.py
--rw-------   0 ndf       (1000) ndf       (1000)     4493 2022-07-23 03:27:29.000000 metarace-2.1.0/src/metarace/unt4.py
-drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-06 07:09:46.000000 metarace-2.1.0/src/metarace.egg-info/
--rw-r--r--   0 ndf       (1000) ndf       (1000)     4229 2023-06-06 07:09:46.000000 metarace-2.1.0/src/metarace.egg-info/PKG-INFO
--rw-r--r--   0 ndf       (1000) ndf       (1000)      985 2023-06-06 07:09:46.000000 metarace-2.1.0/src/metarace.egg-info/SOURCES.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2023-06-06 07:09:46.000000 metarace-2.1.0/src/metarace.egg-info/dependency_links.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)       95 2023-06-06 07:09:46.000000 metarace-2.1.0/src/metarace.egg-info/requires.txt
--rw-r--r--   0 ndf       (1000) ndf       (1000)        9 2023-06-06 07:09:46.000000 metarace-2.1.0/src/metarace.egg-info/top_level.txt
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.448818 metarace-2.1.1/
+-rw-------   0 ndf       (1000) ndf       (1000)     1092 2022-01-22 06:38:57.000000 metarace-2.1.1/LICENSE
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       28 2022-05-31 01:20:37.000000 metarace-2.1.1/MANIFEST.in
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     4762 2023-06-28 01:35:08.448818 metarace-2.1.1/PKG-INFO
+-rw-------   0 ndf       (1000) ndf       (1000)     4243 2023-06-28 01:33:45.000000 metarace-2.1.1/README.md
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      753 2023-06-28 00:30:37.000000 metarace-2.1.1/pyproject.toml
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       38 2023-06-28 01:35:08.448818 metarace-2.1.1/setup.cfg
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.440818 metarace-2.1.1/src/
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.444818 metarace-2.1.1/src/metarace/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     9466 2023-06-26 09:40:49.000000 metarace-2.1.1/src/metarace/__init__.py
+-rw-------   0 ndf       (1000) ndf       (1000)     4268 2023-06-25 00:11:43.000000 metarace-2.1.1/src/metarace/countback.py
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.448818 metarace-2.1.1/src/metarace/data/
+-rw-------   0 ndf       (1000) ndf       (1000)     3067 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/IOC_Codes.csv
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_armfin.svg
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_armint.svg
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_armstart.svg
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     1454 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_idle.svg
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     2369 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/bg_src.svg
+-rw-------   0 ndf       (1000) ndf       (1000)      520 2023-06-05 02:11:31.000000 metarace-2.1.1/src/metarace/data/metarace.json
+-rw-------   0 ndf       (1000) ndf       (1000)     8729 2022-01-22 22:18:40.000000 metarace-2.1.1/src/metarace/data/metarace_icon.svg
+-rw-------   0 ndf       (1000) ndf       (1000)     2048 2023-06-05 01:23:26.000000 metarace-2.1.1/src/metarace/data/pdf_template.json
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.448818 metarace-2.1.1/src/metarace/decoder/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     5730 2023-05-31 00:29:16.000000 metarace-2.1.1/src/metarace/decoder/__init__.py
+-rw-------   0 ndf       (1000) ndf       (1000)    15284 2023-06-27 08:32:43.000000 metarace-2.1.1/src/metarace/decoder/rrs.py
+-rw-------   0 ndf       (1000) ndf       (1000)    27311 2023-06-27 08:32:09.000000 metarace-2.1.1/src/metarace/decoder/rru.py
+-rw-------   0 ndf       (1000) ndf       (1000)    18916 2023-06-27 13:14:15.000000 metarace-2.1.1/src/metarace/decoder/thbc.py
+-rw-------   0 ndf       (1000) ndf       (1000)    11424 2023-06-25 00:11:28.000000 metarace-2.1.1/src/metarace/eventdb.py
+-rw-------   0 ndf       (1000) ndf       (1000)     3733 2023-05-31 00:53:46.000000 metarace-2.1.1/src/metarace/export.py
+-rw-------   0 ndf       (1000) ndf       (1000)     8787 2023-06-25 00:11:12.000000 metarace-2.1.1/src/metarace/gemini.py
+-rw-------   0 ndf       (1000) ndf       (1000)     5970 2023-06-28 00:17:21.000000 metarace-2.1.1/src/metarace/htlib.py
+-rw-------   0 ndf       (1000) ndf       (1000)     5636 2023-06-25 00:10:49.000000 metarace-2.1.1/src/metarace/jsonconfig.py
+-rw-------   0 ndf       (1000) ndf       (1000)   199422 2023-06-28 00:18:10.000000 metarace-2.1.1/src/metarace/report.py
+-rw-------   0 ndf       (1000) ndf       (1000)    24615 2023-06-24 14:16:56.000000 metarace-2.1.1/src/metarace/riderdb.py
+-rw-------   0 ndf       (1000) ndf       (1000)    10274 2023-06-25 00:10:28.000000 metarace-2.1.1/src/metarace/sender.py
+-rw-------   0 ndf       (1000) ndf       (1000)    17918 2023-06-25 00:09:45.000000 metarace-2.1.1/src/metarace/strops.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)    13652 2022-11-14 06:21:05.000000 metarace-2.1.1/src/metarace/telegraph.py
+-rw-------   0 ndf       (1000) ndf       (1000)    15088 2023-06-04 10:37:01.000000 metarace-2.1.1/src/metarace/timy.py
+-rw-r--r--   0 ndf       (1000) ndf       (1000)    20914 2023-06-25 00:08:46.000000 metarace-2.1.1/src/metarace/tod.py
+-rw-------   0 ndf       (1000) ndf       (1000)     4485 2023-06-25 00:09:26.000000 metarace-2.1.1/src/metarace/unt4.py
+drwxr-xr-x   0 ndf       (1000) ndf       (1000)        0 2023-06-28 01:35:08.444818 metarace-2.1.1/src/metarace.egg-info/
+-rw-r--r--   0 ndf       (1000) ndf       (1000)     4762 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/PKG-INFO
+-rw-r--r--   0 ndf       (1000) ndf       (1000)      985 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/SOURCES.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        1 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/dependency_links.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)       67 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/requires.txt
+-rw-r--r--   0 ndf       (1000) ndf       (1000)        9 2023-06-28 01:35:08.000000 metarace-2.1.1/src/metarace.egg-info/top_level.txt
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `metarace-2.1.0/LICENSE` & `metarace-2.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/PKG-INFO` & `metarace-2.1.1/README.md`

 * *Files 10% similar despite different names*

```diff
@@ -1,48 +1,35 @@
-Metadata-Version: 2.1
-Name: metarace
-Version: 2.1.0
-Summary: Cyclesport results and timing toolkit
-Author-email: Nathan Fraser <ndf-zz@6-v.org>
-License: MIT
-Project-URL: homepage, https://github.com/ndf-zz/metarace
-Keywords: cyclesport,results,timing
-Classifier: Development Status :: 3 - Alpha
-Classifier: Topic :: Other/Nonlisted Topic
-Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3
-Requires-Python: >=3.6
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
 # metarace
 
 A collection of Python modules to assist with cycle race timekeeping
 and official result preparation. Version 2 of Metarace is a
 re-write for Python 3 which removes static pyGTK/GLib dependencies.
 
-Unlike version 1, application-level modules are not contained in
+Application-level modules are not contained in
 the library, they are available separately:
 
    - [roadmeet](https://github.com/ndf-zz/metarace-roadmeet) : Timing
      and results for UCI Part 2 Road Races, UCI Part 5 Cyclo-Cross,
      criterium, road handicap and ad-hoc time trial events.
    - [tagreg](https://github.com/ndf-zz/metarace-tagreg) : Transponder
      id management.
    - [ttstart](https://github.com/ndf-zz/metarace-ttstart) : Time
      Trial starter console.
 
 
-## Module Overview
+## Work in Progress
 
-For details on module contents, methods and properties, use
-pydoc:
+   - include grapheme support in strops
+   - update pango text layouts to align vertically by text baseline
+   - re-write report library for better sectioning and dynamic updates
+   - module documentation
+   - sample scripts
 
-	$ pydoc metarace.tod
 
+## Module Overview
 
 ### metarace: Base Library
 
    - shared configuration, default files and resources
    - tempfile-backed file writer
    - meet folder locking
 
@@ -56,15 +43,15 @@
 ### riderdb: CSV-backed Competitor Information
 
 Store details for competitors, teams, and categories.
 
 
 ### tod: Time of Day
 
-Represent timing measurements and calculations for
+Represent timing measurements, calculations for
 short intervals (<24 hours) and aggregate times.
 
 
 ### timy: Alge Timy Chronometer
 
 Read time of day measurements from an attached Alge Timy
 in PC-TIMER mode.
@@ -125,53 +112,69 @@
 ### report: Report Generation
 
 Create sectioned reports and save to PDF, HTML, XLS and JSON.
 
 
 ### export: Result Export and Mirroring
 
-Execute a process on the host system, to
+Execute a process on the host system to
 mirror result files to a remote server,
 or to run a script.
 
 
 ### eventdb: CSV Event List
 
 Store details for events within a meet.
 
 
 ## Requirements
 
 System requirements:
 
+   - Python >= 3.9
    - Cairo
    - Pango
-   - PangoCairo
    - Rsvg
    - Python gi
-   - Python gi cairo
-   - tex-gyre (fonts)
+   - Python gi-cairo
+   - tex-gyre (optional, recommended)
+   - evince (optional, recommended)
    - mosquitto (optional)
-   - evince (optional)
    - libreoffice (optional)
 
 Python packages:
 
    - pyserial: Serial port interface
    - python-dateutil: Generic date/time string parser
    - xlwt: XLS file writer
-   - libscrc: 16 bit CRC for thbc
    - paho-mqtt: MQTT interface
-   - importlib-resources: Package data files() interface (transitional)
+   - grapheme: Unicode grapheme support
 
 
 ## Installation
 
-Install system requirements Cairo, Pango, Rsvg,
-Tex-Gyre and optionally Mosquitto, then use pip
-to install metarace.
+Check that your python
+version is at least 3.9 before installing. This library will
+not work with python versions less than 3.9.
+
+
+### Debian 11+
+
+Install system requirements with apt:
+
+	$ sudo apt install python3-venv python3-pip python3-cairo python3-gi python3-gi-cairo
+	$ sudo apt install gir1.2-rsvg-2.0 gir1.2-pango-1.0
+	$ sudo apt install python3-serial python3-paho-mqtt python3-dateutil python3-xlwt
+
+Optionally add fonts, PDF viewer and MQTT broker:
+
+	$ sudo apt install tex-gyre evince mosquitto
+
+Create a virtualenv for metarace and associated packages:
+
+	$ python3 -m venv --system-site-packages mrv
 
+Activate the virtualenv and install packages with pip:
 
-### Debian (11+)
+	$ source ./mrv/bin/activate
+	(mrv) $ pip3 install metarace
 
-	$ sudo apt-get install gir1.2-rsvg-2.0 gir1.2-pango-1.0 tex-gyre python3-cairo python3-gi python3-gi-cairo python3-pip mosquitto evince
-	$ pip install metarace
```

### Comparing `metarace-2.1.0/README.md` & `metarace-2.1.1/PKG-INFO`

 * *Files 18% similar despite different names*

```diff
@@ -1,32 +1,51 @@
+Metadata-Version: 2.1
+Name: metarace
+Version: 2.1.1
+Summary: Cyclesport results and timing toolkit
+Author-email: Nathan Fraser <ndf-zz@6-v.org>
+License: MIT
+Project-URL: homepage, https://github.com/ndf-zz/metarace
+Keywords: cyclesport,results,timing
+Classifier: Development Status :: 3 - Alpha
+Classifier: Topic :: Other/Nonlisted Topic
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Requires-Python: >=3.9
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 # metarace
 
 A collection of Python modules to assist with cycle race timekeeping
 and official result preparation. Version 2 of Metarace is a
 re-write for Python 3 which removes static pyGTK/GLib dependencies.
 
-Unlike version 1, application-level modules are not contained in
+Application-level modules are not contained in
 the library, they are available separately:
 
    - [roadmeet](https://github.com/ndf-zz/metarace-roadmeet) : Timing
      and results for UCI Part 2 Road Races, UCI Part 5 Cyclo-Cross,
      criterium, road handicap and ad-hoc time trial events.
    - [tagreg](https://github.com/ndf-zz/metarace-tagreg) : Transponder
      id management.
    - [ttstart](https://github.com/ndf-zz/metarace-ttstart) : Time
      Trial starter console.
 
 
-## Module Overview
+## Work in Progress
 
-For details on module contents, methods and properties, use
-pydoc:
+   - include grapheme support in strops
+   - update pango text layouts to align vertically by text baseline
+   - re-write report library for better sectioning and dynamic updates
+   - module documentation
+   - sample scripts
 
-	$ pydoc metarace.tod
 
+## Module Overview
 
 ### metarace: Base Library
 
    - shared configuration, default files and resources
    - tempfile-backed file writer
    - meet folder locking
 
@@ -40,15 +59,15 @@
 ### riderdb: CSV-backed Competitor Information
 
 Store details for competitors, teams, and categories.
 
 
 ### tod: Time of Day
 
-Represent timing measurements and calculations for
+Represent timing measurements, calculations for
 short intervals (<24 hours) and aggregate times.
 
 
 ### timy: Alge Timy Chronometer
 
 Read time of day measurements from an attached Alge Timy
 in PC-TIMER mode.
@@ -109,53 +128,69 @@
 ### report: Report Generation
 
 Create sectioned reports and save to PDF, HTML, XLS and JSON.
 
 
 ### export: Result Export and Mirroring
 
-Execute a process on the host system, to
+Execute a process on the host system to
 mirror result files to a remote server,
 or to run a script.
 
 
 ### eventdb: CSV Event List
 
 Store details for events within a meet.
 
 
 ## Requirements
 
 System requirements:
 
+   - Python >= 3.9
    - Cairo
    - Pango
-   - PangoCairo
    - Rsvg
    - Python gi
-   - Python gi cairo
-   - tex-gyre (fonts)
+   - Python gi-cairo
+   - tex-gyre (optional, recommended)
+   - evince (optional, recommended)
    - mosquitto (optional)
-   - evince (optional)
    - libreoffice (optional)
 
 Python packages:
 
    - pyserial: Serial port interface
    - python-dateutil: Generic date/time string parser
    - xlwt: XLS file writer
-   - libscrc: 16 bit CRC for thbc
    - paho-mqtt: MQTT interface
-   - importlib-resources: Package data files() interface (transitional)
+   - grapheme: Unicode grapheme support
 
 
 ## Installation
 
-Install system requirements Cairo, Pango, Rsvg,
-Tex-Gyre and optionally Mosquitto, then use pip
-to install metarace.
+Check that your python
+version is at least 3.9 before installing. This library will
+not work with python versions less than 3.9.
+
+
+### Debian 11+
+
+Install system requirements with apt:
+
+	$ sudo apt install python3-venv python3-pip python3-cairo python3-gi python3-gi-cairo
+	$ sudo apt install gir1.2-rsvg-2.0 gir1.2-pango-1.0
+	$ sudo apt install python3-serial python3-paho-mqtt python3-dateutil python3-xlwt
+
+Optionally add fonts, PDF viewer and MQTT broker:
+
+	$ sudo apt install tex-gyre evince mosquitto
+
+Create a virtualenv for metarace and associated packages:
+
+	$ python3 -m venv --system-site-packages mrv
 
+Activate the virtualenv and install packages with pip:
 
-### Debian (11+)
+	$ source ./mrv/bin/activate
+	(mrv) $ pip3 install metarace
 
-	$ sudo apt-get install gir1.2-rsvg-2.0 gir1.2-pango-1.0 tex-gyre python3-cairo python3-gi python3-gi-cairo python3-pip mosquitto evince
-	$ pip install metarace
```

### Comparing `metarace-2.1.0/pyproject.toml` & `metarace-2.1.1/pyproject.toml`

 * *Files 26% similar despite different names*

```diff
@@ -1,35 +1,33 @@
 [build-system]
 requires = ["setuptools>=62"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "metarace"
-version = "2.1.0"
+version = "2.1.1"
 description = "Cyclesport results and timing toolkit"
 readme = "README.md"
-requires-python = ">=3.6"
+requires-python = ">=3.9"
 license = {text = "MIT"}
 keywords = ["cyclesport", "results", "timing"]
 authors = [
     {email = "ndf-zz@6-v.org", name = "Nathan Fraser"}
 ]
 classifiers = [
     "Development Status :: 3 - Alpha",
     "Topic :: Other/Nonlisted Topic",
     "Operating System :: OS Independent",
     "Programming Language :: Python :: 3",
 ]
 dependencies = [
-    "importlib-resources",
     "pyserial",
     "python-dateutil",
     "pycairo",
     "PyGObject",
-    "libscrc",
     "paho-mqtt",
     "xlwt",
     "grapheme",
 ]
 
 [project.urls]
 homepage = "https://github.com/ndf-zz/metarace"
```

### Comparing `metarace-2.1.0/src/metarace/__init__.py` & `metarace-2.1.1/src/metarace/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -3,18 +3,21 @@
 
 import os
 import logging
 import fcntl
 import errno
 from tempfile import NamedTemporaryFile
 from shutil import copyfile
-from importlib_resources import files, as_file
 from metarace import jsonconfig
+try:
+    from importlib.resources import files, as_file
+except ImportError:
+    print('Python >= 3.9 is required to use this module')
 
-VERSION = '2.1.0'
+VERSION = '2.1.1'
 DATA_PATH = os.path.realpath(
     os.path.expanduser(os.path.join('~', 'Documents', 'metarace')))
 DEFAULTS_PATH = os.path.join(DATA_PATH, 'default')
 RESOURCE_PKG = 'metarace.data'
 LOGO = 'metarace_icon.svg'
 SYSCONF = 'metarace.json'
 PDF_TEMPLATE = 'pdf_template.json'
@@ -164,15 +167,15 @@
     _log.debug('Fetching %r from resource %r', basefile, t)
     if t is not None and t.is_file():
         return as_file(t)
     else:
         raise FileNotFoundError('Named resource not found: ' + repr(name))
 
 
-class savefile(object):
+class savefile:
     """Tempfile-backed save file contextmanager.
 
        Creates a temporary file with the desired mode and encoding
        and returns a context manager and writable file handle.
 
        On close, the temp file is atomically moved to the provided
        filename (if possible).
```

### Comparing `metarace-2.1.0/src/metarace/countback.py` & `metarace-2.1.1/src/metarace/countback.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 # SPDX-License-Identifier: MIT
 """Countback support."""
 
 
-class countback(object):
+class countback:
     """Wrapper for countback store/compare."""
     __hash__ = None
 
     def __init__(self, cbstr=None):
         self.__store = {}
         if cbstr is not None:
             self.fromstring(cbstr)
```

### Comparing `metarace-2.1.0/src/metarace/data/IOC_Codes.csv` & `metarace-2.1.1/src/metarace/data/IOC_Codes.csv`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/data/bg_armfin.svg` & `metarace-2.1.1/src/metarace/data/bg_armfin.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/data/bg_armint.svg` & `metarace-2.1.1/src/metarace/data/bg_armint.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/data/bg_armstart.svg` & `metarace-2.1.1/src/metarace/data/bg_armstart.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/data/bg_idle.svg` & `metarace-2.1.1/src/metarace/data/bg_idle.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/data/bg_src.svg` & `metarace-2.1.1/src/metarace/data/bg_src.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/data/metarace.json` & `metarace-2.1.1/src/metarace/data/metarace.json`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/data/metarace_icon.svg` & `metarace-2.1.1/src/metarace/data/metarace_icon.svg`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/data/pdf_template.json` & `metarace-2.1.1/src/metarace/data/pdf_template.json`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/decoder/__init__.py` & `metarace-2.1.1/src/metarace/decoder/__init__.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/decoder/rrs.py` & `metarace-2.1.1/src/metarace/decoder/rrs.py`

 * *Files 0% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 # decoder port
 _RRS_TCP_PORT = 3601
 # passing record length
 _RRS_PASSLEN = 20
 # status record length
 _RRS_STATUSLEN = 25
 # Warn if battery voltage is below this many volts
-_RRS_LOWBATT = 2.0
+_RRS_LOWBATT = 2.3
 _RRS_SYNFMT = 'SETTIME;{:04d}-{:02d}-{:02d};{:02d}:{:02d}:{:02d}.{:03d}'
 _RRS_EOL = '\r\n'
 _RRS_MARKER = '99999'
 _RRS_ENCODING = 'iso8859-1'
 _RRS_IOTIMEOUT = 1.0
 _RRS_PASSIVEID = '1'
 
@@ -52,14 +52,15 @@
         self._curfile = None
         self._lastpassing = None
         self._dorefetch = True
         self._fetchpending = False
         self._pending_command = None
         self._allowstored = False
         self._passiveloop = 'C1'
+        self._curport = None
 
     # API overrides
     def sync(self, data=None):
         self.stop_session(data)
         self._cqueue.put_nowait(('_sync', data))
         self.start_session(data)
 
@@ -109,28 +110,34 @@
                 'PASSINGS',
         ]:
             self.write(m)
 
     def _port(self, port):
         """Re-establish connection to supplied device port."""
         self._close()
+        if port is None and self._curport is not None:
+            port = self._curport
+        if port is None:
+            _log.debug('Re-connect cancelled: port is None')
+            return
         addr = (port, _RRS_TCP_PORT)
         _log.debug('Connecting to %r', addr)
         self._rdbuf = b''
         s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
         try:
             s.setsockopt(socket.IPPROTO_TCP, socket.TCP_NODELAY, 1)
             s.setsockopt(socket.IPPROTO_TCP, socket.TCP_USER_TIMEOUT, 5000)
         except Exception as e:
             _log.debug('%s setting TCP_NODELAY/TCP_USER_TIMEOUT: %s',
                        e.__class__.__name__, e)
         s.connect(addr)
         s.settimeout(_RRS_IOTIMEOUT)
         self._io = s
         self.sane()
+        self._curport = port
 
     def _sync(self, data=None):
         a = datetime.datetime.now()
         syncmd = _RRS_SYNFMT.format(a.year, a.month, a.day, a.hour, a.minute,
                                     a.second, a.microsecond // 1000)
         self._write(syncmd)
 
@@ -210,15 +217,15 @@
 
             if hits and rssi and tagid:
                 try:
                     hitcount = int(hits, 16)
                     rssival = int(rssi, 16)
                     twofour = -90 + ((rssival & 0x70) >> 2)
                     lstrength = 1 + (rssival & 0x0f)
-                    if lstrength < 5 or twofour < -82 or hitcount < 4:
+                    if lstrength < 3 or twofour < -82 or hitcount < 3:
                         _log.warning(
                             'Poor read %s: Hits:%d RSSI:%ddBm Loop:%ddB',
                             tagid, hitcount, twofour, lstrength)
                 except Exception as e:
                     _log.debug('%s reading hits/RSSI: %s',
                                e.__class__.__name__, e)
```

### Comparing `metarace-2.1.0/src/metarace/decoder/rru.py` & `metarace-2.1.1/src/metarace/decoder/rru.py`

 * *Files 2% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 
 _log = logging.getLogger('metarace.decoder.rru')
 _log.setLevel(logging.DEBUG)
 
 _RRU_BAUD = 19200
 _RRU_PASSLEN = 12
 _RRU_BEACONLEN = 17
-_RRU_LOWBATT = 2.1  # Warn if battery voltage is below this many volts
+_RRU_LOWBATT = 2.3  # Warn if battery voltage is below this many volts
 _RRU_REFCHECK = 1800  # check ref after this many timeouts
 _RRU_REFTHRESH = 0x2a30000  # 2 x 86400 x 256
 _RRU_ENCODING = 'iso8859-1'
 _RRU_MARKER = '_____127'  # trigger marker
 _RRU_EOL = '\n'
 # Serial port I/O read timeout in seconds
 _RRU_IOTIMEOUT = 1.0
@@ -231,14 +231,15 @@
         self._curreply = None  # current multi-line response mode
         self._lastpassing = 0
         self._lastrequest = None
         self._request_pending = False
         self._allowstored = False
         self._autochannelid = None
         self._refcount = 0
+        self._curport = None
 
     # API overrides
     def status(self):
         """Request status info from decoder."""
         for c in sorted(_CONFINFO):
             self.write(''.join(['CONFGET;', c]))
         for c in sorted(_INFOLBLS):
@@ -262,14 +263,19 @@
 
     def _port(self, port):
         """Re-establish connection to supplied device port."""
         self._request_pending = False
         self._rrustamp = None
         self._rruht = None
         self._close()
+        if port is None and self._curport is not None:
+            port = self._curport
+        if port is None:
+            _log.debug('Re-connect cancelled: port is None')
+            return
         self._rdbuf = b''
         _log.debug('Connecting to %r', port)
         s = serial.Serial(baudrate=_RRU_BAUD,
                           rtscts=False,
                           timeout=_RRU_IOTIMEOUT)
         s.dtr = 0  # This must be set _before_ open()
         s.port = port
@@ -556,15 +562,15 @@
 
             if hits and rssi and tagid:
                 try:
                     hitcount = int(hits, 16)
                     rssival = int(rssi, 16)
                     twofour = -90 + ((rssival & 0x70) >> 2)
                     lstrength = 1 + (rssival & 0x0f)
-                    if lstrength < 5 or twofour < -82 or hitcount < 4:
+                    if lstrength < 3 or twofour < -82 or hitcount < 3:
                         _log.warning(
                             'Poor read %s: Hits:%d RSSI:%ddBm Loop:%ddB',
                             tagid, hitcount, twofour, lstrength)
                 except Exception as e:
                     _log.debug('%s reading hits/RSSI: %s',
                                e.__class__.__name__, e)
```

### Comparing `metarace-2.1.0/src/metarace/decoder/thbc.py` & `metarace-2.1.1/src/metarace/decoder/thbc.py`

 * *Files 3% similar despite different names*

```diff
@@ -8,15 +8,14 @@
 import serial
 import socket
 import time
 
 from . import (decoder, DECODER_LOG_LEVEL)
 from metarace import sysconf
 from metarace import tod
-from libscrc import mcrf4xx
 
 _log = logging.getLogger('metarace.decoder.thbc')
 _log.setLevel(logging.DEBUG)
 
 THBC_BAUD = 19200
 THBC_UDP_PORT = 2008
 THBC_ENCODING = 'iso8859-1'
@@ -97,14 +96,47 @@
     'Netmask': '255.255.255.0',
     'Gateway': '0.0.0.0',
     'Host': '192.168.0.255'
 }
 DEFPORT = '/dev/ttyS0'
 
 
+def reflect(dat, width):
+    """Reverse bit order of byte"""
+    out = dat & 0x01
+    for i in range(width - 1):
+        dat >>= 1
+        out = (out << 1) | (dat & 0x01)
+    return out
+
+
+# Build a lookup table for the MCRF4XX CRC
+# Source: pycrc https://pycrc.org/
+_MCRF4XXTBL = [0] * 256
+for i in range(256):
+    r = i
+    r = reflect(r, 8) << 8
+    for j in range(8):
+        if r & 0x8000 != 0:
+            r = (r << 1) ^ 0x1021
+        else:
+            r = (r << 1)
+    r = reflect(r, 16)
+    _MCRF4XXTBL[i] = r & 0xffff
+
+
+def mcrf4xx(msgstr=b''):
+    """Return MCRF4XX CRC for provided byte string."""
+    r = 0xffff  # reflect(0xffff,16) == 0xffff
+    for b in msgstr:
+        i = (r ^ b) & 0xff
+        r = ((r >> 8) ^ _MCRF4XXTBL[i]) & 0xffff
+    return r & 0xffff  # collapse two reflects, mask and ^0
+
+
 def thbc_sum(msgstr=b''):
     """Return sum of character values as decimal string."""
     ret = 0
     for ch in msgstr:
         ret = ret + ch
     return '{0:04d}'.format(ret).encode('ascii', 'ignore')
 
@@ -132,14 +164,15 @@
         self._boxname = None
         self._version = ''
         self._decoderconfig = {}
         self._decoderipconfig = {}
         self._io = None
         self._cksumerr = 0
         self._rdbuf = b''  # bytestring read buffer
+        self._curport = None
 
     # API overrides
     def status(self):
         """Request status message from decoder."""
         self.write(STATCMD)
 
     def connected(self):
@@ -177,28 +210,34 @@
                 cp.close()
             except Exception as e:
                 _log.debug('%s closing io: %s', e.__class__.__name__, e)
 
     def _port(self, port):
         """Re-establish connection to supplied device port."""
         self._close()
+        if port is None and self._curport is not None:
+            port = self._curport
+        if port is None:
+            _log.debug('Re-connect cancelled: port is None')
+            return
         s = None
         self._rdbuf = b''
         if '/' not in port and '.' in port:
             _log.debug('Attempting UDP on %r', port)
             s = dgram(port, THBC_UDP_PORT)
         else:
             # assume device file
             s = serial.Serial(port, THBC_BAUD, rtscts=False, timeout=0.2)
         self._boxname = None
         self._io = s
         self._write(QUECMD)
         # queue sane through command loop
         time.sleep(0.2)
         self.sane()
+        self._curport = port
 
     def _sync(self, data=None):
         _log.debug('Performing blocking sync')
         acceptval = tod.tod('0.001')
         nt = tod.now()
         diff = nt - nt.truncate(0)
         while diff > acceptval and diff < tod.ONE:
@@ -436,32 +475,32 @@
     def _read(self):
         """Read messages from the decoder until a timeout condition."""
         ch = self._io.read(1)
         while ch != b'':
             if ch == LF and len(self._rdbuf) > 0 and self._rdbuf[-1] == CR[0]:
                 # Return ends the current 'message', if preceeded by return
                 self._rdbuf += ch  # include trailing newline
-                _log.debug('RECV: %r', self._rdbuf)
+                #_log.debug('RECV: %r', self._rdbuf)
                 t = self._parse_message(self._rdbuf.lstrip(b'\0'))
                 if t is not None:
                     self._trig(t)
                 self._rdbuf = b''
             elif len(self._rdbuf) > 40 and b'\x1e\x86\x98' in self._rdbuf:
                 # Assume acknowledge from IP Command
-                _log.debug('RECV: %r', self._rdbuf)
+                #_log.debug('RECV: %r', self._rdbuf)
                 self._rdbuf = b''
                 self._ipcompletion()
             else:
                 self._rdbuf += ch
             ch = self._io.read(1)
 
     def _write(self, msg):
         if self._io is not None:
             self._io.write(msg)
-            _log.debug('SEND: %r', msg)
+            #_log.debug('SEND: %r', msg)
 
     def run(self):
         """Decoder main loop."""
         _log.debug('Starting')
         self._running = True
         while self._running:
             try:
@@ -487,15 +526,15 @@
                 _log.critical('%s: %s', e.__class__.__name__, e)
                 self._boxname = None
                 self._running = False
         self.setcb()
         _log.debug('Exiting')
 
 
-class dgram(object):
+class dgram:
     """Serial-like UDP port object."""
 
     def __init__(self, host, port):
         self._host = host
         self._port = port
         self._s = socket.socket(socket.AF_INET, socket.SOCK_DGRAM)
         self._s.settimeout(0.2)
```

### Comparing `metarace-2.1.0/src/metarace/eventdb.py` & `metarace-2.1.1/src/metarace/eventdb.py`

 * *Files 1% similar despite different names*

```diff
@@ -93,15 +93,15 @@
 
 
 def get_header(cols=DEFAULT_COLUMN_ORDER):
     """Return a row of header strings for the provided cols."""
     return [EVENT_COLUMNS[c] for c in cols]
 
 
-class event(object):
+class event:
     """CSV-backed event listing."""
 
     def get_row(self, coldump=DEFAULT_COLUMN_ORDER):
         """Return a row ready to export."""
         return [str(self[c]) for c in coldump]
 
     def event_info(self):
@@ -173,15 +173,15 @@
         key = colkey(item)
         return key in self.__store
 
     def __def_notify(self, data=None):
         pass
 
 
-class eventdb(object):
+class eventdb:
     """Event database."""
 
     def add_empty(self, evno=None):
         """Add a new empty row to the event model."""
         if evno is None:
             evno = self.nextevno()
         nev = event(evid=evno, notify=self.__notify)
```

### Comparing `metarace-2.1.0/src/metarace/export.py` & `metarace-2.1.1/src/metarace/export.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/gemini.py` & `metarace-2.1.1/src/metarace/gemini.py`

 * *Files 1% similar despite different names*

```diff
@@ -70,15 +70,15 @@
 # dispatch thread queue commands
 TCMDS = ('EXIT', 'PORT', 'MSG')
 
 # Character encoding
 ENCODING = 'ascii'
 
 
-class scbport(object):
+class scbport:
     """Gemini scoreboard communication port object."""
 
     def __init__(self, port='/dev/ttyUSB1'):
         self.__s = serial.Serial(port, 9600, rtscts=0, timeout=0.2)
         self.running = True
 
     def sendall(self, buf):
```

### Comparing `metarace-2.1.0/src/metarace/htlib.py` & `metarace-2.1.1/src/metarace/htlib.py`

 * *Files 8% similar despite different names*

```diff
@@ -77,40 +77,40 @@
                         'name': 'viewport',
                         'content': 'width=device-width, initial-scale=1'
                     }),
                 title('__REPORT_TITLE__'),
                 link(
                     attrs={
                         'href':
-                        'https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css',
+                        'https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css',
                         'integrity':
-                        'sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor',
+                        'sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM',
                         'crossorigin': 'anonymous',
                         'rel': 'stylesheet'
                     }),
                 link(
                     attrs={
                         'href':
-                        'https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.3/font/bootstrap-icons.css',
+                        'https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css',
                         'rel': 'stylesheet'
                     }),
                 script(
                     element(
-                        'function ud(){null!==document.querySelector("#pgre")&&setTimeout("history.go(0);",55329)}function rl(){return setTimeout("history.go(0);",10),!1}'
+                        '"use strict";let pageReload=null;function rl(){setTimeout(function(){history.go(0)},10);return false}function pageInit(){pageReload=document.getElementById("pageReload");pageReload.addEventListener("click",rl)}window.addEventListener("load",pageInit,false);'
                     ), ),
             )),
             body((
                 '__REPORT_NAV__',
-                div((
-                    h1('__REPORT_TITLE__'),
+                main((
+                    h2('__REPORT_TITLE__'),
                     '__REPORT_CONTENT__',
                 ),
-                    attrs={'class': 'container'}),
+                     attrs={'class': 'container'}),
             ),
-                 attrs={'onload': 'ud();'}),
+                 attrs={}),
         ), {'lang': 'en'})))
 
 
 # Declare all the empty types
 for empty in ('base', 'link', 'meta', 'hr', 'br', 'wbr', 'source', 'img',
               'embed', 'track', 'area', 'col', 'param', 'hr', 'br', 'img',
               'col'):
```

### Comparing `metarace-2.1.0/src/metarace/jsonconfig.py` & `metarace-2.1.1/src/metarace/jsonconfig.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,15 +12,15 @@
 import os
 import logging
 
 _log = logging.getLogger('metarace.jsonconfig')
 _log.setLevel(logging.DEBUG)
 
 
-class config(object):
+class config:
 
     def __init__(self, default={}):
         """Create config object with a deep copy of the provided default."""
         self.__store = {}
         for section in default:
             self.__store[section] = {}
             for key in default[section]:
```

### Comparing `metarace-2.1.0/src/metarace/report.py` & `metarace-2.1.1/src/metarace/report.py`

 * *Files 0% similar despite different names*

```diff
@@ -264,40 +264,40 @@
     return ret
 
 
 def vec2htmllinkrow(vec=[], xtn='', rep=None):
     # evno -> column one
     # N/A
     # descr -> column two
-    # status
+    # text
     # link
-    # status
+    # text
     # link
     rowmap = vecmapstr(vec, 7)
     cols = []
     cols.append(htlib.td(rowmap[0]))
     if rowmap[6]:  # Startlist/Result links
         cols.append(htlib.td(rowmap[2]))  # DESCR
         bstyle = rep.buttonstyle
         stxt = ''
-        if rowmap[4]:  # startlist is present
-            if 'provisional' in rowmap[3].lower():
-                bstyle = rep.warnbuttonstyle
-            stxt = htlib.a('Startlist', {
-                'href': rowmap[4] + xtn,
-                'class': bstyle
-            })
+        if rowmap[4]:  # 'startlist' is present
+            ltxt = 'Startlist'
+            flnk = rowmap[4] + xtn
+            if rowmap[3]:
+                ltxt = rowmap[3]
+                flnk = rowmap[4]
+            stxt = htlib.a(ltxt, {'href': flnk, 'class': bstyle})
         rtxt = ''
         if rowmap[6]:  # result is present
-            if 'provisional' in rowmap[5].lower():
-                bstyle = rep.warnbuttonstyle
-            rtxt = htlib.a('Result', {
-                'href': rowmap[6] + xtn,
-                'class': bstyle
-            })
+            ltxt = 'Result'
+            flnk = rowmap[6] + xtn
+            if rowmap[5]:
+                ltxt = rowmap[5]
+                flnk = rowmap[6]
+            rtxt = htlib.a(ltxt, {'href': flnk, 'class': bstyle})
         cols.append(htlib.td(stxt))
         cols.append(htlib.td(rtxt))
     else:  # Old-style trackmeet event index
         if rowmap[4]:
             cols.append(htlib.td(htlib.a(rowmap[2],
                                          {'href': rowmap[4] + xtn})))
         else:
@@ -330,15 +330,15 @@
     cols.append(htlib.th(rowmap[4], {'class': 'text-end'}))  # time/gap (right)
     cols.append(htlib.th(rowmap[5], {'class': 'text-end'}))  # time/gap (right)
     cols.append(htlib.th(rowmap[6]))  # Units (left)
     return htlib.tr(cols)
 
 
 # Section Types
-class dual_ittt_startlist(object):
+class dual_ittt_startlist:
     """Two-up time trial for individual riders (eg track pursuit)."""
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
@@ -618,15 +618,15 @@
             f.write('\n')
 
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return False
 
 
-class signon_list(object):
+class signon_list:
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.status = None
         self.heading = None
         self.subheading = None
         self.colheader = None  # ignored for all signon
@@ -820,15 +820,15 @@
                 htlib.table(htlib.tbody(trows), {'class': report.tablestyle}))
             f.write('\n')
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return False
 
 
-class twocol_startlist(object):
+class twocol_startlist:
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
         self.footer = None
@@ -1014,15 +1014,15 @@
                 htlib.table(htlib.tbody(trows), {'class': report.tablestyle}))
             f.write('\n')
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return False
 
 
-class sprintround(object):
+class sprintround:
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
         self.colheader = None
@@ -1205,15 +1205,15 @@
                 htlib.table(htlib.tbody(trows), {'class': report.tablestyle}))
             f.write('\n')
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return ''
 
 
-class sprintfinal(object):
+class sprintfinal:
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.status = None
         self.heading = None
         self.subheading = None
         self.colheader = None
@@ -1410,15 +1410,15 @@
                 htlib.table(htlib.tbody(trows), {'class': report.tablestyle}))
             f.write('\n')
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return ''
 
 
-class rttstartlist(object):
+class rttstartlist:
     """Time trial start list."""
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
@@ -1594,27 +1594,30 @@
             rows = []
             if self.colheader:
                 rows.append(self.colheader)
             for r in self.lines:
                 nv = r[0:6]
                 if len(nv) == 2:
                     nv = [nv[0], None, nv[1]]
+                if len(nv) > 4:
+                    # suppress the printrep underscores
+                    nv[4] = ''
                 rows.append(nv)
             trows = []
             for l in rows:
                 trows.append(vec2htmlrow(l))
             f.write(
                 htlib.table(htlib.tbody(trows), {'class': report.tablestyle}))
             f.write('\n')
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return None
 
 
-class bullet_text(object):
+class bullet_text:
     """List of bullet items, each one a non-breaking pango para."""
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.status = None
         self.heading = None  # scalar
         self.subheading = None  # scalar
@@ -1798,15 +1801,15 @@
                 if l[1]:
                     bstr += l[1]
                 ol.append(htlib.li(bstr.rstrip()))
             f.write(htlib.ul(ol))
             f.write('\n')
 
 
-class preformat_text(object):
+class preformat_text:
     """Block of pre-formatted/monospaced plain text."""
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.status = None
         self.heading = None  # scalar
         self.subheading = None  # scalar
@@ -1958,15 +1961,15 @@
             if self.colheader:
                 prelines.append(self.colheader.rstrip())
             for row in self.lines:
                 prelines.append(row.rstrip())
             f.write(htlib.pre('\n'.join(prelines)))
 
 
-class event_index(object):
+class event_index:
     """Copy of plain section, but in text output text links."""
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.status = None
         self.heading = None  # scalar
         self.colheader = None  # scalar
@@ -2160,15 +2163,15 @@
                 trows.append(vec2htmllinkrow(l, xtn, report))
             f.write(
                 htlib.table((hdr, htlib.tbody(trows)),
                             {'class': report.tablestyle}))
         return None
 
 
-class judge24rep(object):
+class judge24rep:
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
         self.colheader = None
@@ -2407,15 +2410,15 @@
                             {'class': report.tablestyle}))
             f.write('\n')
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return None
 
 
-class judgerep(object):
+class judgerep:
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
         self.colheader = None
@@ -2671,15 +2674,15 @@
                             {'class': report.tablestyle}))
             f.write('\n')
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return None
 
 
-class teampage(object):
+class teampage:
     """One-page teams race startlist, with individuals in 3 columns."""
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
@@ -2933,15 +2936,15 @@
                                     {'class': report.tablestyle}))
                     f.write('\n')
         if rcount > 0:
             f.write(htlib.p(htlib.small('{} starters.'.format(rcount))))
         return None
 
 
-class gamut(object):
+class gamut:
     """Whole view of the entire tour - aka crossoff."""
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
@@ -3101,15 +3104,15 @@
         if len(self.lines) > 0:
             pass
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return None
 
 
-class threecol_section(object):
+class threecol_section:
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
         self.colheader = None
@@ -3327,15 +3330,15 @@
                             {'class': report.tablestyle}))
             f.write('\n')
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return None
 
 
-class section(object):
+class section:
 
     def __init__(self, secid=None):
         self.sectionid = secid
         self.heading = None
         self.status = None
         self.subheading = None
         self.colheader = None
@@ -3345,14 +3348,16 @@
         self.lcount = 0
         self.grey = True
         self.h = None
 
     def serialize(self, rep, sectionid=None):
         """Return a serializable map for JSON export."""
         ret = {}
+        if sectionid is None:
+            sectionid = self.sectionid
         ret['sectionid'] = sectionid
         ret['type'] = 'section'
         ret['heading'] = self.heading
         ret['status'] = self.status
         ret['subheading'] = self.subheading
         ret['colheader'] = self.colheader
         ret['footer'] = self.footer
@@ -3566,15 +3571,15 @@
                             {'class': report.tablestyle}))
             f.write('\n')
         if self.footer:
             f.write(self.footer.strip() + '\n')
         return None
 
 
-class pagebreak(object):
+class pagebreak:
     """Dummy 'section' for page breaks."""
 
     def __init__(self, threshold=None):
         self.sectionid = 'break'
         self.threshold = threshold
 
     def serialize(self, rep, sectionid=None):
@@ -3594,15 +3599,15 @@
         except Exception as e:
             _log.warning('Invalid break thresh %r: %s', threshold, e)
 
     def get_threshold(self):
         return self.threshold
 
 
-class image_elem(object):
+class image_elem:
     """Place an SVG image on the page."""
 
     def __init__(self,
                  x1=None,
                  y1=None,
                  x2=None,
                  y2=None,
@@ -3656,15 +3661,15 @@
             c.save()
             c.translate(self.xof, self.yof)
             c.scale(self.sf, self.sf)
             self.source.render_cairo(c)
             c.restore()
 
 
-class arc_elem(object):
+class arc_elem:
     """Pace an optionally shaded arc on the page."""
 
     def __init__(self,
                  cx=None,
                  cy=None,
                  r=None,
                  a1=None,
@@ -3704,15 +3709,15 @@
                                  self.colour[2])
             if self.dash is not None:
                 c.set_dash(self.dash)
             c.stroke()
         c.restore()
 
 
-class box_elem(object):
+class box_elem:
     """Place an optionally shaded box on the page."""
 
     def __init__(self,
                  x1=None,
                  y1=None,
                  x2=None,
                  y2=None,
@@ -3752,15 +3757,15 @@
                                  self.colour[2])
             if self.dash is not None:
                 c.set_dash(self.dash)
             c.stroke()
         c.restore()
 
 
-class line_elem(object):
+class line_elem:
     """Places a line on the page."""
 
     def __init__(self,
                  x1=None,
                  y1=None,
                  x2=None,
                  y2=None,
@@ -3785,15 +3790,15 @@
             c.set_dash(self.dash)
         c.move_to(self.x1, self.y1)
         c.line_to(self.x2, self.y2)
         c.stroke()
         c.restore()
 
 
-class text_elem(object):
+class text_elem:
     """Places string of text on the page."""
 
     def __init__(self,
                  x=None,
                  y=None,
                  align=None,
                  font=None,
@@ -3829,15 +3834,15 @@
             c.move_to(self.x - (self.align * tw), self.y)
             PangoCairo.update_context(c, p)
             l.context_changed()
             PangoCairo.show_layout(c, l)
             c.restore()
 
 
-class group_elem(object):
+class group_elem:
     """Place each defined element on the page."""
 
     def __init__(self, report=None, elems=[]):
         self.report = report
         self.elems = elems
         self.indraw = False
 
@@ -3849,15 +3854,15 @@
         for e in self.elems:
             if e in self.report.elements:
                 self.report.elements[e].draw(c, p)
         c.restore()
         self.indraw = False
 
 
-class report(object):
+class report:
     """PDF/GTKPrint Report class."""
 
     def __init__(self, template=None):
 
         # load template	-> also declares page geometry variables
         self.html_template = ''
         self.coverpage = None
@@ -4254,14 +4259,20 @@
         self.provisional = flag
 
     def set_pagemarks(self, flag=True):
         self.pagemarks = flag
 
     def output_json(self, file=None):
         """Output the JSON version."""
+        ret = self.serialise()
+        # serialise to the provided file handle
+        json.dump(ret, file, indent=1, sort_keys=True)
+
+    def serialise(self):
+        """Return a serialisable report object"""
         if 'pagestr' in self.strings:
             del self.strings['pagestr']  # remove spurious string data
         ret = {
             'report': {},
             'sections': {},
             'api': 'metarace.report',
             'apiversion': APIVERSION,
@@ -4275,26 +4286,25 @@
         rep['prevlink'] = self.prevlink
         rep['nextlink'] = self.nextlink
         rep['indexlink'] = self.indexlink
         rep['resultlink'] = self.resultlink
         rep['startlink'] = self.startlink
         rep['canonical'] = self.canonical
         rep['customlinks'] = self.customlinks
-        rep['navbar'] = self.navbar
+        #rep['navbar'] = self.navbar
         rep['shortname'] = self.shortname
         rep['pagemarks'] = self.pagemarks
         rep['strings'] = self.strings
         rep['sections'] = []
         secmap = ret['sections']
         for s in self.sections:
             secid = mksectionid(secmap, s.sectionid)
             secmap[secid] = s.serialize(self, secid)
             rep['sections'].append(secid)
-        # serialise to the provided file handle
-        json.dump(ret, file, indent=1, sort_keys=True)
+        return ret
 
     def output_xls(self, file=None):
         """Output xls spreadsheet."""
         wb = xlwt.Workbook()
         sheetname = 'report'
         # Docstring?
         ws = wb.add_sheet(sheetname)
@@ -4392,20 +4402,19 @@
                     htlib.span((), {"class": "bi-file-earmark-text"}), {
                         'href': self.resultlink + '.html',
                         'class': 'nav-link',
                         'title': 'Result'
                     }))
         if self.provisional:  # add refresh button
             navbar.append(
-                htlib.a(
-                    htlib.span((), {"class": "bi-arrow-repeat"}), {
-                        'href': '#',
-                        'class': 'nav-link',
+                htlib.span(
+                    (), {
+                        'id': 'pageReload',
                         'title': 'Reload',
-                        'onclick': 'return rl();'
+                        "class": "nav-link bi-arrow-repeat"
                     }))
         if self.nextlink:
             navbar.append(
                 htlib.a(
                     htlib.span((), {"class": "bi-caret-right"}), {
                         'href': self.nextlink + '.html',
                         'title': 'Next',
@@ -4470,18 +4479,16 @@
                     'id': 'pgre',
                     'class': 'badge bg-warning'
                 })
             carditems = []
             for li in metalist:
                 items = [htlib.i('', {'class': li[0]})]
                 for c in li[1]:
-                    items.append(' ')
                     items.append(c)
                 if pmark is not None:
-                    items.append(' ')
                     items.append(pmark)
                 carditems.append(
                     htlib.li(
                         items,
                         {'class': 'list-group-item list-group-item-secondary'
                          }))
                 pmark = None
```

### Comparing `metarace-2.1.0/src/metarace/sender.py` & `metarace-2.1.1/src/metarace/sender.py`

 * *Files 1% similar despite different names*

```diff
@@ -27,15 +27,15 @@
 TCMDS = ('EXIT', 'PORT', 'MSG')
 
 # module log object
 _log = logging.getLogger('metarace.sender')
 _log.setLevel(logging.DEBUG)
 
 
-class serialport(object):
+class serialport:
     """Scoreboard communication port object."""
 
     def __init__(self, addr, baudrate):
         """Constructor.
 
         Parameters:
 
@@ -61,15 +61,15 @@
         self.running = False
         try:
             self.__s.close()
         except:
             pass
 
 
-class scbport(object):
+class scbport:
     """Scoreboard communication port object."""
 
     def __init__(self, addr, protocol):
         """Constructor.
 
         Parameters:
```

### Comparing `metarace-2.1.0/src/metarace/strops.py` & `metarace-2.1.1/src/metarace/strops.py`

 * *Files 3% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 # "protective" against unencoded ascii strings and control chars
 SPACEBLOCK = ''
 for i in range(0, 256):
     SPACEBLOCK += chr(i)
 
 
 # unicode translation 'map' class
-class unicodetrans(object):
+class unicodetrans:
 
     def __init__(self, keep='', replace=SPACEBLOCK, replacechar=' '):
         self.comp = dict((ord(c), replacechar) for c in replace)
         for c in keep:
             self.comp[ord(c)] = c
 
     def __getitem__(self, k):  # override to return a None
@@ -60,52 +60,33 @@
 # timing channels - this duplicates defs in timy
 CHAN_START = 0
 CHAN_INT = 9
 CHAN_UNKNOWN = -1
 
 # running number comparisons
 RUNNER_NOS = {
-    'red': 0,
-    'whi': 1,
-    'blu': 2,
-    'yel': 3,
-    'grn': 4,
-    'pin': 5,
-    'bla': 6,
-    'gry': 7,
-    'ora': 8,
-    'pur': 9,
-    'rdw': 10,
-    'blw': 11,
-    'ylw': 12,
-    'grw': 13
+    'RED': 0,
+    'WHI': 1,
+    'BLU': 2,
+    'YEL': 3,
+    'GRN': 4,
+    'PIN': 5,
+    'BLA': 6,
+    'GRY': 7,
+    'ORA': 8,
+    'PUR': 9,
+    'RDW': 10,
+    'BLW': 11,
+    'YLW': 12,
+    'GRW': 13
 }
 
 DNFCODEMAP = {'otl': 0, 'dsq': 1, 'dnf': 3, 'dns': 4, '': 2}
 
 
-def cmp_no(x, y):
-    """Replicate py2 cmp() for numeric quantities."""
-    if x == y:
-        return 0
-    elif x < y:
-        return -1
-    else:
-        return 1
-
-
-def cmp_dnf(x, y):
-    """Comparison func for two dnf codes."""
-    if x not in DNFCODEMAP:
-        x = ''
-    if y not in DNFCODEMAP:
-        y = ''
-    return cmp_no(DNFCODEMAP[x], DNFCODEMAP[y])
-
-
 def rand_key(data=None):
     """Return a random integer key for shuffling."""
     return randint(0, 0xffffffff)
 
 
 def riderno_key(bib):
     """Return a comparison key for sorting rider number strings."""
@@ -142,16 +123,16 @@
     if bib.isdigit():
         bval = int(bib)
     else:
         sbib = bib.translate(INTEGER_UTRANS).strip()
         if sbib and sbib.isdigit():
             bval = int(sbib)
         else:
-            if bib.lower()[0:3] in RUNNER_NOS:
-                bval = RUNNER_NOS[bib.lower()[0:3]]
+            if bib.upper()[0:3] in RUNNER_NOS:
+                bval = RUNNER_NOS[bib.upper()[0:3]]
             else:
                 bval = id(bib)
     sval = 0
     if ser != '':
         sval = ord(ser[0]) << 12
     return sval | (bval & 0xfff)
 
@@ -312,17 +293,18 @@
             else:
                 ret = srcline.center(length)
         else:
             ret = srcline
     return ret
 
 
-def resname_bib(bib, first, last, club):
+def resname_bib(bib, first, last, club, series=''):
     """Return rider name formatted for results with bib."""
-    ret = [bib, ' ', fitname(first, last, 64)]
+    bibstr = bibser2bibstr(bib, series)
+    ret = [bibstr, ' ', fitname(first, last, 64)]
     if club is not None and club != '':
         if len(club) < 4:
             club = club.upper()
         ret.extend([' (', club, ')'])
     return ''.join(ret)
 
 
@@ -366,29 +348,29 @@
     """Filter and return a canonically formatted start list."""
     return ' '.join(bibstr.translate(BIBLIST_UTRANS).split())
 
 
 def riderlist_split(riderstr, rdb=None, series=''):
     """Filter, search and return a list of matching riders for entry."""
     ret = []
-    riderstr = riderstr.lower()
+    riderstr = riderstr.upper()
 
     # first do riderdb lookups
     if rdb is not None:
-        if riderstr.strip() == 'all':
+        if riderstr.strip() == 'ALL':
             riderstr = ''
             for r in rdb:
                 # (bib, series), ...
                 if r[1] == series:
                     ret.append(r[0])
         else:
             for cat in rdb.listcats(series):
-                if len(cat) > 0 and cat.lower() in riderstr:
+                if len(cat) > 0 and cat.upper() in riderstr:
                     ret.extend(rdb.biblistfromcat(cat, series))
-                    riderstr = riderstr.replace(cat.lower(), '')
+                    riderstr = riderstr.replace(cat.upper(), '')
 
     # pass 2: append riders and expand any series if possible
     riderstr = reformat_placelist(riderstr)
     for nr in riderstr.split():
         if '-' in nr:
             # try for a range...
             l = None
@@ -606,34 +588,34 @@
 
 def bibstr2bibser(bibstr=''):
     """Split a bib.series string and return bib and series."""
     a = bibstr.strip().split('.')
     ret_bib = ''
     ret_ser = ''
     if len(a) > 0:
-        ret_bib = a[0]
+        ret_bib = a[0].upper()
     if len(a) > 1:
-        ret_ser = a[1]
+        ret_ser = a[1].lower()
     return (ret_bib, ret_ser)
 
 
 def lapstring(lapcount=None):
     lapstr = ''
     if lapcount:
         lapstr = str(lapcount) + ' Lap'
         if lapcount > 1:
             lapstr += 's'
     return lapstr
 
 
 def bibser2bibstr(bib='', ser=''):
     """Return a valid bib.series string."""
-    ret = bib
+    ret = bib.upper()
     if ser != '':
-        ret += '.' + ser
+        ret += '.' + ser.lower()
     return ret
 
 
 def titlesplit(src='', linelen=24):
     """Split a string on word boundaries to try and fit into 3 fixed lines."""
     ret = ['', '', '']
     words = src.split()
```

### Comparing `metarace-2.1.0/src/metarace/telegraph.py` & `metarace-2.1.1/src/metarace/telegraph.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/timy.py` & `metarace-2.1.1/src/metarace/timy.py`

 * *Files identical despite different names*

### Comparing `metarace-2.1.0/src/metarace/tod.py` & `metarace-2.1.1/src/metarace/tod.py`

 * *Files 1% similar despite different names*

```diff
@@ -262,15 +262,15 @@
         # Round off float to max tod precision
         ret = decimal.Decimal('{0:0.6f}'.format(timeval))
     else:
         ret = decimal.Decimal(timeval)
     return ret
 
 
-class tod(object):
+class tod:
     """A class for representing time of day, net time and RFID events."""
 
     def __init__(self,
                  timeval=0,
                  index='',
                  chan='TOD',
                  refid='',
@@ -514,15 +514,15 @@
 extra = decimal.Decimal('0.000001')
 cof = decimal.Decimal('0.000001')
 for c in ['ntr', 'caught', 'rel', 'abort', 'otl', 'dnf', 'dns', 'dsq']:
     FAKETIMES[c].timeval += cof
     cof += extra
 
 
-class todlist(object):
+class todlist:
     """ToD list helper class for managing splits and ranks."""
 
     def __init__(self, lbl=''):
         self.__label = lbl
         self.__store = []
 
     def __iter__(self):
```

### Comparing `metarace-2.1.0/src/metarace/unt4.py` & `metarace-2.1.1/src/metarace/unt4.py`

 * *Files 2% similar despite different names*

```diff
@@ -62,15 +62,15 @@
         tbuf = tbuf.replace(ENCMAP[key], key)
     # decode special char
     tbuf = tbuf.replace('<>', '<')
     return tbuf
 
 
 # UNT4 Packet class
-class unt4(object):
+class unt4:
     """UNT4 Packet Class."""
 
     def __init__(self,
                  unt4str=None,
                  prefix=None,
                  header='',
                  erp=False,
```

### Comparing `metarace-2.1.0/src/metarace.egg-info/PKG-INFO` & `metarace-2.1.1/src/metarace.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,48 +1,51 @@
 Metadata-Version: 2.1
 Name: metarace
-Version: 2.1.0
+Version: 2.1.1
 Summary: Cyclesport results and timing toolkit
 Author-email: Nathan Fraser <ndf-zz@6-v.org>
 License: MIT
 Project-URL: homepage, https://github.com/ndf-zz/metarace
 Keywords: cyclesport,results,timing
 Classifier: Development Status :: 3 - Alpha
 Classifier: Topic :: Other/Nonlisted Topic
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
-Requires-Python: >=3.6
+Requires-Python: >=3.9
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # metarace
 
 A collection of Python modules to assist with cycle race timekeeping
 and official result preparation. Version 2 of Metarace is a
 re-write for Python 3 which removes static pyGTK/GLib dependencies.
 
-Unlike version 1, application-level modules are not contained in
+Application-level modules are not contained in
 the library, they are available separately:
 
    - [roadmeet](https://github.com/ndf-zz/metarace-roadmeet) : Timing
      and results for UCI Part 2 Road Races, UCI Part 5 Cyclo-Cross,
      criterium, road handicap and ad-hoc time trial events.
    - [tagreg](https://github.com/ndf-zz/metarace-tagreg) : Transponder
      id management.
    - [ttstart](https://github.com/ndf-zz/metarace-ttstart) : Time
      Trial starter console.
 
 
-## Module Overview
+## Work in Progress
 
-For details on module contents, methods and properties, use
-pydoc:
+   - include grapheme support in strops
+   - update pango text layouts to align vertically by text baseline
+   - re-write report library for better sectioning and dynamic updates
+   - module documentation
+   - sample scripts
 
-	$ pydoc metarace.tod
 
+## Module Overview
 
 ### metarace: Base Library
 
    - shared configuration, default files and resources
    - tempfile-backed file writer
    - meet folder locking
 
@@ -56,15 +59,15 @@
 ### riderdb: CSV-backed Competitor Information
 
 Store details for competitors, teams, and categories.
 
 
 ### tod: Time of Day
 
-Represent timing measurements and calculations for
+Represent timing measurements, calculations for
 short intervals (<24 hours) and aggregate times.
 
 
 ### timy: Alge Timy Chronometer
 
 Read time of day measurements from an attached Alge Timy
 in PC-TIMER mode.
@@ -125,53 +128,69 @@
 ### report: Report Generation
 
 Create sectioned reports and save to PDF, HTML, XLS and JSON.
 
 
 ### export: Result Export and Mirroring
 
-Execute a process on the host system, to
+Execute a process on the host system to
 mirror result files to a remote server,
 or to run a script.
 
 
 ### eventdb: CSV Event List
 
 Store details for events within a meet.
 
 
 ## Requirements
 
 System requirements:
 
+   - Python >= 3.9
    - Cairo
    - Pango
-   - PangoCairo
    - Rsvg
    - Python gi
-   - Python gi cairo
-   - tex-gyre (fonts)
+   - Python gi-cairo
+   - tex-gyre (optional, recommended)
+   - evince (optional, recommended)
    - mosquitto (optional)
-   - evince (optional)
    - libreoffice (optional)
 
 Python packages:
 
    - pyserial: Serial port interface
    - python-dateutil: Generic date/time string parser
    - xlwt: XLS file writer
-   - libscrc: 16 bit CRC for thbc
    - paho-mqtt: MQTT interface
-   - importlib-resources: Package data files() interface (transitional)
+   - grapheme: Unicode grapheme support
 
 
 ## Installation
 
-Install system requirements Cairo, Pango, Rsvg,
-Tex-Gyre and optionally Mosquitto, then use pip
-to install metarace.
+Check that your python
+version is at least 3.9 before installing. This library will
+not work with python versions less than 3.9.
+
+
+### Debian 11+
+
+Install system requirements with apt:
+
+	$ sudo apt install python3-venv python3-pip python3-cairo python3-gi python3-gi-cairo
+	$ sudo apt install gir1.2-rsvg-2.0 gir1.2-pango-1.0
+	$ sudo apt install python3-serial python3-paho-mqtt python3-dateutil python3-xlwt
+
+Optionally add fonts, PDF viewer and MQTT broker:
+
+	$ sudo apt install tex-gyre evince mosquitto
+
+Create a virtualenv for metarace and associated packages:
+
+	$ python3 -m venv --system-site-packages mrv
 
+Activate the virtualenv and install packages with pip:
 
-### Debian (11+)
+	$ source ./mrv/bin/activate
+	(mrv) $ pip3 install metarace
 
-	$ sudo apt-get install gir1.2-rsvg-2.0 gir1.2-pango-1.0 tex-gyre python3-cairo python3-gi python3-gi-cairo python3-pip mosquitto evince
-	$ pip install metarace
```

### Comparing `metarace-2.1.0/src/metarace.egg-info/SOURCES.txt` & `metarace-2.1.1/src/metarace.egg-info/SOURCES.txt`

 * *Files identical despite different names*


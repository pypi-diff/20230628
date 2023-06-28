# Comparing `tmp/benimang-3.0.0.tar.gz` & `tmp/benimang-3.0.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "benimang-3.0.0.tar", last modified: Wed Jun 28 08:48:36 2023, max compression
+gzip compressed data, was "benimang-3.0.1.tar", last modified: Wed Jun 28 08:52:37 2023, max compression
```

## Comparing `benimang-3.0.0.tar` & `benimang-3.0.1.tar`

### file list

```diff
@@ -1,40 +1,40 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 08:48:36.321391 benimang-3.0.0/
--rw-rw-rw-   0        0        0       29 2023-05-30 09:18:28.000000 benimang-3.0.0/MANIFEST.in
--rw-rw-rw-   0        0        0      258 2023-06-28 08:48:36.321391 benimang-3.0.0/PKG-INFO
--rw-rw-rw-   0        0        0        0 2023-05-30 09:18:28.000000 benimang-3.0.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 08:48:36.312390 benimang-3.0.0/beni/
--rw-rw-rw-   0        0        0        0 2023-05-30 09:18:28.000000 benimang-3.0.0/beni/__init__.py
--rw-rw-rw-   0        0        0     5790 2023-06-12 07:13:35.000000 benimang-3.0.0/beni/bbyte.py
--rw-rw-rw-   0        0        0     5763 2023-06-26 06:18:37.000000 benimang-3.0.0/beni/bcache.py
--rw-rw-rw-   0        0        0    11484 2023-06-28 08:31:40.000000 benimang-3.0.0/beni/bcmd.py
--rw-rw-rw-   0        0        0     1941 2023-06-09 08:30:18.000000 benimang-3.0.0/beni/bcolor.py
--rw-rw-rw-   0        0        0     2423 2023-06-26 06:18:37.000000 benimang-3.0.0/beni/bexecute.py
--rw-rw-rw-   0        0        0     1908 2023-06-28 03:37:11.000000 benimang-3.0.0/beni/bfile.py
--rw-rw-rw-   0        0        0     4494 2023-06-28 07:14:45.000000 benimang-3.0.0/beni/bfunc.py
--rw-rw-rw-   0        0        0     1029 2023-06-28 03:38:59.000000 benimang-3.0.0/beni/bhash.py
--rw-rw-rw-   0        0        0     5745 2023-06-26 09:08:25.000000 benimang-3.0.0/beni/bhttp.py
--rw-rw-rw-   0        0        0     2583 2023-06-13 01:57:12.000000 benimang-3.0.0/beni/binput.py
--rw-rw-rw-   0        0        0     5695 2023-06-26 06:18:37.000000 benimang-3.0.0/beni/block.py
--rw-rw-rw-   0        0        0     4004 2023-06-26 06:18:37.000000 benimang-3.0.0/beni/blog.py
--rw-rw-rw-   0        0        0     5820 2023-06-26 09:08:00.000000 benimang-3.0.0/beni/bpath.py
--rw-rw-rw-   0        0        0     2429 2023-06-26 08:22:01.000000 benimang-3.0.0/beni/bplaywright.py
--rw-rw-rw-   0        0        0     1058 2023-06-27 03:17:47.000000 benimang-3.0.0/beni/bprogress.py
--rw-rw-rw-   0        0        0     3388 2023-06-27 03:37:21.000000 benimang-3.0.0/beni/bqiniu.py
--rw-rw-rw-   0        0        0     9846 2023-06-27 03:26:51.000000 benimang-3.0.0/beni/bsqlite.py
--rw-rw-rw-   0        0        0      759 2023-06-27 03:26:19.000000 benimang-3.0.0/beni/bstorage.py
--rw-rw-rw-   0        0        0     1981 2023-06-26 02:57:46.000000 benimang-3.0.0/beni/btable.py
--rw-rw-rw-   0        0        0     5010 2023-06-28 07:33:32.000000 benimang-3.0.0/beni/btask.py
--rw-rw-rw-   0        0        0     1420 2023-06-27 03:36:08.000000 benimang-3.0.0/beni/btime.py
--rw-rw-rw-   0        0        0      265 2023-06-12 07:08:01.000000 benimang-3.0.0/beni/btype.py
--rw-rw-rw-   0        0        0     2279 2023-06-27 06:14:15.000000 benimang-3.0.0/beni/bzip.py
-drwxrwxrwx   0        0        0        0 2023-06-28 08:48:36.319391 benimang-3.0.0/benimang.egg-info/
--rw-rw-rw-   0        0        0      258 2023-06-28 08:48:36.000000 benimang-3.0.0/benimang.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      609 2023-06-28 08:48:36.000000 benimang-3.0.0/benimang.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 08:48:36.000000 benimang-3.0.0/benimang.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       40 2023-06-28 08:48:36.000000 benimang-3.0.0/benimang.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0       93 2023-06-28 08:48:36.000000 benimang-3.0.0/benimang.egg-info/requires.txt
--rw-rw-rw-   0        0        0        5 2023-06-28 08:48:36.000000 benimang-3.0.0/benimang.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      567 2023-06-28 08:24:30.000000 benimang-3.0.0/pyproject.toml
--rw-rw-rw-   0        0        0       42 2023-06-28 08:48:36.321391 benimang-3.0.0/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-28 08:48:36.320391 benimang-3.0.0/test/
--rw-rw-rw-   0        0        0      638 2023-05-30 09:18:28.000000 benimang-3.0.0/test/test_sample.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:52:37.393483 benimang-3.0.1/
+-rw-rw-rw-   0        0        0       29 2023-05-30 09:18:28.000000 benimang-3.0.1/MANIFEST.in
+-rw-rw-rw-   0        0        0      258 2023-06-28 08:52:37.392483 benimang-3.0.1/PKG-INFO
+-rw-rw-rw-   0        0        0        0 2023-05-30 09:18:28.000000 benimang-3.0.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 08:52:37.385483 benimang-3.0.1/beni/
+-rw-rw-rw-   0        0        0        0 2023-05-30 09:18:28.000000 benimang-3.0.1/beni/__init__.py
+-rw-rw-rw-   0        0        0     5790 2023-06-12 07:13:35.000000 benimang-3.0.1/beni/bbyte.py
+-rw-rw-rw-   0        0        0     5763 2023-06-26 06:18:37.000000 benimang-3.0.1/beni/bcache.py
+-rw-rw-rw-   0        0        0    11477 2023-06-28 08:51:05.000000 benimang-3.0.1/beni/bcmd.py
+-rw-rw-rw-   0        0        0     1941 2023-06-09 08:30:18.000000 benimang-3.0.1/beni/bcolor.py
+-rw-rw-rw-   0        0        0     2423 2023-06-26 06:18:37.000000 benimang-3.0.1/beni/bexecute.py
+-rw-rw-rw-   0        0        0     1908 2023-06-28 03:37:11.000000 benimang-3.0.1/beni/bfile.py
+-rw-rw-rw-   0        0        0     4494 2023-06-28 07:14:45.000000 benimang-3.0.1/beni/bfunc.py
+-rw-rw-rw-   0        0        0     1029 2023-06-28 03:38:59.000000 benimang-3.0.1/beni/bhash.py
+-rw-rw-rw-   0        0        0     5745 2023-06-26 09:08:25.000000 benimang-3.0.1/beni/bhttp.py
+-rw-rw-rw-   0        0        0     2583 2023-06-13 01:57:12.000000 benimang-3.0.1/beni/binput.py
+-rw-rw-rw-   0        0        0     5695 2023-06-26 06:18:37.000000 benimang-3.0.1/beni/block.py
+-rw-rw-rw-   0        0        0     4004 2023-06-26 06:18:37.000000 benimang-3.0.1/beni/blog.py
+-rw-rw-rw-   0        0        0     5820 2023-06-26 09:08:00.000000 benimang-3.0.1/beni/bpath.py
+-rw-rw-rw-   0        0        0     2429 2023-06-26 08:22:01.000000 benimang-3.0.1/beni/bplaywright.py
+-rw-rw-rw-   0        0        0     1058 2023-06-27 03:17:47.000000 benimang-3.0.1/beni/bprogress.py
+-rw-rw-rw-   0        0        0     3388 2023-06-27 03:37:21.000000 benimang-3.0.1/beni/bqiniu.py
+-rw-rw-rw-   0        0        0     9846 2023-06-27 03:26:51.000000 benimang-3.0.1/beni/bsqlite.py
+-rw-rw-rw-   0        0        0      759 2023-06-27 03:26:19.000000 benimang-3.0.1/beni/bstorage.py
+-rw-rw-rw-   0        0        0     1981 2023-06-26 02:57:46.000000 benimang-3.0.1/beni/btable.py
+-rw-rw-rw-   0        0        0     5010 2023-06-28 07:33:32.000000 benimang-3.0.1/beni/btask.py
+-rw-rw-rw-   0        0        0     1420 2023-06-27 03:36:08.000000 benimang-3.0.1/beni/btime.py
+-rw-rw-rw-   0        0        0      265 2023-06-12 07:08:01.000000 benimang-3.0.1/beni/btype.py
+-rw-rw-rw-   0        0        0     2279 2023-06-27 06:14:15.000000 benimang-3.0.1/beni/bzip.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:52:37.390483 benimang-3.0.1/benimang.egg-info/
+-rw-rw-rw-   0        0        0      258 2023-06-28 08:52:37.000000 benimang-3.0.1/benimang.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      609 2023-06-28 08:52:37.000000 benimang-3.0.1/benimang.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:52:37.000000 benimang-3.0.1/benimang.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       40 2023-06-28 08:52:37.000000 benimang-3.0.1/benimang.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       93 2023-06-28 08:52:37.000000 benimang-3.0.1/benimang.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        5 2023-06-28 08:52:37.000000 benimang-3.0.1/benimang.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      567 2023-06-28 08:52:07.000000 benimang-3.0.1/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 08:52:37.393483 benimang-3.0.1/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 08:52:37.391485 benimang-3.0.1/test/
+-rw-rw-rw-   0        0        0      638 2023-05-30 09:18:28.000000 benimang-3.0.1/test/test_sample.py
```

### Comparing `benimang-3.0.0/beni/bbyte.py` & `benimang-3.0.1/beni/bbyte.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bcache.py` & `benimang-3.0.1/beni/bcache.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bcmd.py` & `benimang-3.0.1/beni/bcmd.py`

 * *Files 0% similar despite different names*

```diff
@@ -310,15 +310,15 @@
     pyperclip.copy(msg)
     bcolor.print_yellow('已复制，可直接粘贴使用')
 
 
 # ------------------------------------------------------------------------
 
 @_app.command()
-def btask(path: Path | str = typer.Option(None, help="项目路径")):
+def btask(path: str = typer.Option(None, help="项目路径")):
     '''生成 btask 项目'''
 
     content_dict = {
         # ------------------------------------
         'main.py':
         '''
 from beni import btask
```

### Comparing `benimang-3.0.0/beni/bcolor.py` & `benimang-3.0.1/beni/bcolor.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bexecute.py` & `benimang-3.0.1/beni/bexecute.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bfile.py` & `benimang-3.0.1/beni/bfile.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bfunc.py` & `benimang-3.0.1/beni/bfunc.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bhash.py` & `benimang-3.0.1/beni/bhash.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bhttp.py` & `benimang-3.0.1/beni/bhttp.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/binput.py` & `benimang-3.0.1/beni/binput.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/block.py` & `benimang-3.0.1/beni/block.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/blog.py` & `benimang-3.0.1/beni/blog.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bpath.py` & `benimang-3.0.1/beni/bpath.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bplaywright.py` & `benimang-3.0.1/beni/bplaywright.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bprogress.py` & `benimang-3.0.1/beni/bprogress.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bqiniu.py` & `benimang-3.0.1/beni/bqiniu.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bsqlite.py` & `benimang-3.0.1/beni/bsqlite.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bstorage.py` & `benimang-3.0.1/beni/bstorage.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/btable.py` & `benimang-3.0.1/beni/btable.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/btask.py` & `benimang-3.0.1/beni/btask.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/btime.py` & `benimang-3.0.1/beni/btime.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/beni/bzip.py` & `benimang-3.0.1/beni/bzip.py`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/benimang.egg-info/SOURCES.txt` & `benimang-3.0.1/benimang.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `benimang-3.0.0/pyproject.toml` & `benimang-3.0.1/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 # https://peps.python.org/pep-0621/#example
 
 [project]
 name = "benimang"
-version = "3.0.0"
+version = "3.0.1"
 description = "utils library for Beni"
 requires-python = ">=3.10"
 keywords = ["benimang", "beni"]
 authors = [
   {email = "benimang@126.com"},
   {name = "Beni Mang"}
 ]
```

### Comparing `benimang-3.0.0/test/test_sample.py` & `benimang-3.0.1/test/test_sample.py`

 * *Files identical despite different names*


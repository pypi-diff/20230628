# Comparing `tmp/xlparser-0.5.8.tar.gz` & `tmp/xlparser-0.5.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "xlparser-0.5.8.tar", last modified: Thu Apr 21 07:55:05 2022, max compression
+gzip compressed data, was "xlparser-0.5.9.tar", last modified: Sun Jun 19 01:26:59 2022, max compression
```

## Comparing `xlparser-0.5.8.tar` & `xlparser-0.5.9.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxr-xr-x   0 ahui       (501) staff       (20)        0 2022-04-21 07:55:05.875298 xlparser-0.5.8/
--rw-r--r--   0 ahui       (501) staff       (20)     1063 2022-04-07 12:06:47.000000 xlparser-0.5.8/LICENSE
--rw-r--r--   0 ahui       (501) staff       (20)     3589 2022-04-21 07:55:05.875156 xlparser-0.5.8/PKG-INFO
--rw-r--r--   0 ahui       (501) staff       (20)     2746 2022-04-07 12:06:47.000000 xlparser-0.5.8/README.md
--rw-r--r--   0 ahui       (501) staff       (20)       38 2022-04-21 07:55:05.875339 xlparser-0.5.8/setup.cfg
--rw-r--r--   0 ahui       (501) staff       (20)     4008 2022-04-07 12:06:47.000000 xlparser-0.5.8/setup.py
--rwxr-xr-x   0 ahui       (501) staff       (20)     1227 2022-04-07 12:06:47.000000 xlparser-0.5.8/xlparser
-drwxr-xr-x   0 ahui       (501) staff       (20)        0 2022-04-21 07:55:05.874997 xlparser-0.5.8/xlparser.egg-info/
--rw-r--r--   0 ahui       (501) staff       (20)     3589 2022-04-21 07:55:05.000000 xlparser-0.5.8/xlparser.egg-info/PKG-INFO
--rw-r--r--   0 ahui       (501) staff       (20)      208 2022-04-21 07:55:05.000000 xlparser-0.5.8/xlparser.egg-info/SOURCES.txt
--rw-r--r--   0 ahui       (501) staff       (20)        1 2022-04-21 07:55:05.000000 xlparser-0.5.8/xlparser.egg-info/dependency_links.txt
--rw-r--r--   0 ahui       (501) staff       (20)       50 2022-04-21 07:55:05.000000 xlparser-0.5.8/xlparser.egg-info/requires.txt
--rw-r--r--   0 ahui       (501) staff       (20)        9 2022-04-21 07:55:05.000000 xlparser-0.5.8/xlparser.egg-info/top_level.txt
--rwxr-xr-x   0 ahui       (501) staff       (20)     6634 2022-04-21 07:26:20.000000 xlparser-0.5.8/xlparser.py
+drwxr-xr-x   0 ahui       (501) staff       (20)        0 2022-06-19 01:26:59.252741 xlparser-0.5.9/
+-rw-r--r--   0 ahui       (501) staff       (20)     1063 2022-04-07 12:06:47.000000 xlparser-0.5.9/LICENSE
+-rw-r--r--   0 ahui       (501) staff       (20)     3589 2022-06-19 01:26:59.252617 xlparser-0.5.9/PKG-INFO
+-rw-r--r--   0 ahui       (501) staff       (20)     2746 2022-04-07 12:06:47.000000 xlparser-0.5.9/README.md
+-rw-r--r--   0 ahui       (501) staff       (20)       38 2022-06-19 01:26:59.252780 xlparser-0.5.9/setup.cfg
+-rw-r--r--   0 ahui       (501) staff       (20)     4008 2022-04-07 12:06:47.000000 xlparser-0.5.9/setup.py
+-rwxr-xr-x   0 ahui       (501) staff       (20)     1651 2022-06-19 00:11:14.000000 xlparser-0.5.9/xlparser
+drwxr-xr-x   0 ahui       (501) staff       (20)        0 2022-06-19 01:26:59.252420 xlparser-0.5.9/xlparser.egg-info/
+-rw-r--r--   0 ahui       (501) staff       (20)     3589 2022-06-19 01:26:59.000000 xlparser-0.5.9/xlparser.egg-info/PKG-INFO
+-rw-r--r--   0 ahui       (501) staff       (20)      208 2022-06-19 01:26:59.000000 xlparser-0.5.9/xlparser.egg-info/SOURCES.txt
+-rw-r--r--   0 ahui       (501) staff       (20)        1 2022-06-19 01:26:59.000000 xlparser-0.5.9/xlparser.egg-info/dependency_links.txt
+-rw-r--r--   0 ahui       (501) staff       (20)       50 2022-06-19 01:26:59.000000 xlparser-0.5.9/xlparser.egg-info/requires.txt
+-rw-r--r--   0 ahui       (501) staff       (20)        9 2022-06-19 01:26:59.000000 xlparser-0.5.9/xlparser.egg-info/top_level.txt
+-rwxr-xr-x   0 ahui       (501) staff       (20)     6722 2022-06-19 01:03:19.000000 xlparser-0.5.9/xlparser.py
```

### Comparing `xlparser-0.5.8/LICENSE` & `xlparser-0.5.9/LICENSE`

 * *Files identical despite different names*

### Comparing `xlparser-0.5.8/PKG-INFO` & `xlparser-0.5.9/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: xlparser
-Version: 0.5.8
+Version: 0.5.9
 Summary: xlparser cli/lib for xlsx, json, csv...
 Home-page: http://github.com/ahuigo/xlparser
 Author: ahuigo
 Author-email: ahui132@qq.com
 License: MIT
 Keywords: xlparser,xlsx,csv,json
 Platform: UNKNOWN
```

### Comparing `xlparser-0.5.8/README.md` & `xlparser-0.5.9/README.md`

 * *Files identical despite different names*

### Comparing `xlparser-0.5.8/setup.py` & `xlparser-0.5.9/setup.py`

 * *Files identical despite different names*

### Comparing `xlparser-0.5.8/xlparser` & `xlparser-0.5.9/xlparser`

 * *Files 27% similar despite different names*

```diff
@@ -12,38 +12,51 @@
 if '-d' in argv:
     debug = print
 else:
     debug = lambda *arg: 1
 
 
 @click.command()
+@click.option('-h', is_flag=True, help='Print help usage')
+@click.option('-d', is_flag=True, help='Debug mode')
 @click.argument('args', nargs=-1)
-def main(args):
+def main(args, **kw):
     """
     Usage: 
-        xlparser [options] INFILE [OUTFILE]\n
+        xlparser [options] <src_file> [<out_file>]\n
             options:\n
                 -h       For help.\n
         # From xlsx to csv.\n
         $ xlparser source.xlsx new.csv \n
 
         # From csv to xlsx.\n
         $ xlparser source.csv new.xlsx \n
 
         # From csv to json.\n
         $ xlparser source.csv new.json\n
 
         # From csv to stdout.\n
         $ xlparser source.xlsx | head \n
     """
+    if 'h' in kw and kw['h']:
+        ctx = click.get_current_context()
+        click.echo(ctx.get_help())
+        ctx.exit()
     if len(args)<=1:
         args = args[0],'-'
     file, outfile, *_ = args
-    rows = parse(file)
-    debug(f'Convert xlsx from {argv[1]}')
+    try:
+        rows = parse(file)
+        debug(f'Convert xlsx from {argv[1]}')
+    except BaseException as e:
+        if kw['d']:
+            raise e
+        else:
+            sys.stderr.write(f'\033[41m{e}!\033[0m\n')
+        quit(1)
 
     if outfile.endswith('.json'):
         json.dump(list(rows), open(outfile,'w'), ensure_ascii=False)
     elif outfile.endswith('.xlsx'):
         saveXlsx(rows, outfile)
     else:
         if outfile == '-':
```

### Comparing `xlparser-0.5.8/xlparser.egg-info/PKG-INFO` & `xlparser-0.5.9/xlparser.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: xlparser
-Version: 0.5.8
+Version: 0.5.9
 Summary: xlparser cli/lib for xlsx, json, csv...
 Home-page: http://github.com/ahuigo/xlparser
 Author: ahuigo
 Author-email: ahui132@qq.com
 License: MIT
 Keywords: xlparser,xlsx,csv,json
 Platform: UNKNOWN
```

### Comparing `xlparser-0.5.8/xlparser.py` & `xlparser-0.5.9/xlparser.py`

 * *Files 1% similar despite different names*

```diff
@@ -136,15 +136,17 @@
 def parse(src):
     if src.endswith('.xls'):
         return parseXls(src)
     if src.endswith('.xlsx'):
         return parseXlsx(src)
     if src.endswith('.csv'):
         return parseCsv(src)
-
+    else:
+        errmsg = f'Unsupported filetype:{src}'
+        raise Exception(errmsg)
 
 '''
 " parse xlsx, xls
 '''
 
 
 def parseXlsx(src):
```


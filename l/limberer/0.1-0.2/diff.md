# Comparing `tmp/limberer-0.1.tar.gz` & `tmp/limberer-0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "limberer-0.1.tar", last modified: Wed Jun 28 11:16:42 2023, max compression
+gzip compressed data, was "limberer-0.2.tar", last modified: Wed Jun 28 13:22:18 2023, max compression
```

## Comparing `limberer-0.1.tar` & `limberer-0.2.tar`

### file list

```diff
@@ -1,34 +1,35 @@
-drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 11:16:42.386058 limberer-0.1/
--rw-rw-r--   0 jtd       (1000) jtd       (1000)      104 2023-06-27 23:50:47.000000 limberer-0.1/AUTHORS
--rw-rw-r--   0 jtd       (1000) jtd       (1000)     1296 2023-06-28 11:15:36.000000 limberer-0.1/LICENSE
--rw-rw-r--   0 jtd       (1000) jtd       (1000)       47 2023-06-28 03:48:05.000000 limberer-0.1/MANIFEST.in
--rw-rw-r--   0 jtd       (1000) jtd       (1000)     3407 2023-06-28 11:16:42.386058 limberer-0.1/PKG-INFO
--rw-rw-r--   0 jtd       (1000) jtd       (1000)     1347 2023-06-28 11:10:47.000000 limberer-0.1/README.md
--rw-rw-r--   0 jtd       (1000) jtd       (1000)     1086 2023-06-28 11:11:43.000000 limberer-0.1/pyproject.toml
--rw-rw-r--   0 jtd       (1000) jtd       (1000)       38 2023-06-28 11:16:42.386058 limberer-0.1/setup.cfg
-drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 11:16:42.386058 limberer-0.1/src/
-drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 11:16:42.386058 limberer-0.1/src/limberer/
--rw-rw-r--   0 jtd       (1000) jtd       (1000)     6939 2023-06-28 11:13:06.000000 limberer-0.1/src/limberer/__init__.py
-drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 11:16:42.386058 limberer-0.1/src/limberer/static/
-drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 11:16:42.386058 limberer-0.1/src/limberer/static/assets/
--rw-rw-r--   0 jtd       (1000) jtd       (1000)     1101 2023-06-28 10:57:50.000000 limberer-0.1/src/limberer/static/assets/base.css
--rw-rw-r--   0 jtd       (1000) jtd       (1000)    20981 2023-06-28 10:57:50.000000 limberer-0.1/src/limberer/static/assets/logo.svg
--rw-rw-r--   0 jtd       (1000) jtd       (1000)     3316 2023-06-28 10:57:50.000000 limberer-0.1/src/limberer/static/assets/theme.css
-drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 11:16:42.386058 limberer-0.1/src/limberer/static/custom/
--rw-rw-r--   0 jtd       (1000) jtd       (1000)        0 2023-06-28 04:15:05.000000 limberer-0.1/src/limberer/static/custom/custom.css
--rw-r--r--   0 jtd       (1000) jtd       (1000)      282 2023-06-28 04:38:31.000000 limberer-0.1/src/limberer/static/project.toml
-drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 11:16:42.386058 limberer-0.1/src/limberer/static/sections/
--rw-rw-r--   0 jtd       (1000) jtd       (1000)      141 2023-06-28 10:57:42.000000 limberer-0.1/src/limberer/static/sections/example.md
--rw-rw-r--   0 jtd       (1000) jtd       (1000)     1571 2023-06-28 10:57:42.000000 limberer-0.1/src/limberer/static/sections/example2.md
-drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 11:16:42.386058 limberer-0.1/src/limberer/static/templates/
--rw-r--r--   0 jtd       (1000) jtd       (1000)      317 2023-06-28 10:57:46.000000 limberer-0.1/src/limberer/static/templates/base.html
--rw-r--r--   0 jtd       (1000) jtd       (1000)      752 2023-06-28 10:57:46.000000 limberer-0.1/src/limberer/static/templates/cover.html
--rw-r--r--   0 jtd       (1000) jtd       (1000)      275 2023-06-28 10:57:46.000000 limberer-0.1/src/limberer/static/templates/section.html
--rw-r--r--   0 jtd       (1000) jtd       (1000)      810 2023-06-28 10:57:46.000000 limberer-0.1/src/limberer/static/templates/toc.html
-drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 11:16:42.386058 limberer-0.1/src/limberer.egg-info/
--rw-rw-r--   0 jtd       (1000) jtd       (1000)     3407 2023-06-28 11:16:42.000000 limberer-0.1/src/limberer.egg-info/PKG-INFO
--rw-rw-r--   0 jtd       (1000) jtd       (1000)      719 2023-06-28 11:16:42.000000 limberer-0.1/src/limberer.egg-info/SOURCES.txt
--rw-rw-r--   0 jtd       (1000) jtd       (1000)        1 2023-06-28 11:16:42.000000 limberer-0.1/src/limberer.egg-info/dependency_links.txt
--rw-rw-r--   0 jtd       (1000) jtd       (1000)       43 2023-06-28 11:16:42.000000 limberer-0.1/src/limberer.egg-info/entry_points.txt
--rw-rw-r--   0 jtd       (1000) jtd       (1000)       42 2023-06-28 11:16:42.000000 limberer-0.1/src/limberer.egg-info/requires.txt
--rw-rw-r--   0 jtd       (1000) jtd       (1000)        9 2023-06-28 11:16:42.000000 limberer-0.1/src/limberer.egg-info/top_level.txt
+drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 13:22:18.101885 limberer-0.2/
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)      104 2023-06-27 23:50:47.000000 limberer-0.2/AUTHORS
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     1296 2023-06-28 11:15:36.000000 limberer-0.2/LICENSE
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)       47 2023-06-28 03:48:05.000000 limberer-0.2/MANIFEST.in
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     3407 2023-06-28 13:22:18.101885 limberer-0.2/PKG-INFO
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     1347 2023-06-28 11:10:47.000000 limberer-0.2/README.md
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     1099 2023-06-28 13:21:59.000000 limberer-0.2/pyproject.toml
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)       38 2023-06-28 13:22:18.101885 limberer-0.2/setup.cfg
+drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 13:22:18.101885 limberer-0.2/src/
+drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 13:22:18.101885 limberer-0.2/src/limberer/
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     8435 2023-06-28 13:20:06.000000 limberer-0.2/src/limberer/__init__.py
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     5425 2023-06-28 13:20:04.000000 limberer-0.2/src/limberer/pf.py
+drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 13:22:18.101885 limberer-0.2/src/limberer/static/
+drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 13:22:18.101885 limberer-0.2/src/limberer/static/assets/
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     1101 2023-06-28 10:57:50.000000 limberer-0.2/src/limberer/static/assets/base.css
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)    20981 2023-06-28 10:57:50.000000 limberer-0.2/src/limberer/static/assets/logo.svg
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     3316 2023-06-28 10:57:50.000000 limberer-0.2/src/limberer/static/assets/theme.css
+drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 13:22:18.101885 limberer-0.2/src/limberer/static/custom/
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)        0 2023-06-28 04:15:05.000000 limberer-0.2/src/limberer/static/custom/custom.css
+-rw-r--r--   0 jtd       (1000) jtd       (1000)      282 2023-06-28 04:38:31.000000 limberer-0.2/src/limberer/static/project.toml
+drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 13:22:18.101885 limberer-0.2/src/limberer/static/sections/
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     1155 2023-06-28 13:19:41.000000 limberer-0.2/src/limberer/static/sections/example.md
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     1571 2023-06-28 13:19:41.000000 limberer-0.2/src/limberer/static/sections/example2.md
+drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 13:22:18.101885 limberer-0.2/src/limberer/static/templates/
+-rw-r--r--   0 jtd       (1000) jtd       (1000)      317 2023-06-28 13:19:57.000000 limberer-0.2/src/limberer/static/templates/base.html
+-rw-r--r--   0 jtd       (1000) jtd       (1000)      752 2023-06-28 13:19:57.000000 limberer-0.2/src/limberer/static/templates/cover.html
+-rw-r--r--   0 jtd       (1000) jtd       (1000)      275 2023-06-28 13:19:57.000000 limberer-0.2/src/limberer/static/templates/section.html
+-rw-r--r--   0 jtd       (1000) jtd       (1000)      810 2023-06-28 13:19:57.000000 limberer-0.2/src/limberer/static/templates/toc.html
+drwxrwxr-x   0 jtd       (1000) jtd       (1000)        0 2023-06-28 13:22:18.101885 limberer-0.2/src/limberer.egg-info/
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)     3407 2023-06-28 13:22:18.000000 limberer-0.2/src/limberer.egg-info/PKG-INFO
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)      738 2023-06-28 13:22:18.000000 limberer-0.2/src/limberer.egg-info/SOURCES.txt
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)        1 2023-06-28 13:22:18.000000 limberer-0.2/src/limberer.egg-info/dependency_links.txt
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)       43 2023-06-28 13:22:18.000000 limberer-0.2/src/limberer.egg-info/entry_points.txt
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)       49 2023-06-28 13:22:18.000000 limberer-0.2/src/limberer.egg-info/requires.txt
+-rw-rw-r--   0 jtd       (1000) jtd       (1000)        9 2023-06-28 13:22:18.000000 limberer-0.2/src/limberer.egg-info/top_level.txt
```

### Comparing `limberer-0.1/LICENSE` & `limberer-0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `limberer-0.1/PKG-INFO` & `limberer-0.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: limberer
-Version: 0.1
+Version: 0.2
 Summary: A flexible document generator based on weasyprint, mustache templates, and pandoc.
 Author-email: Jeff Dileo <jtdileo@gmail.com>
 Maintainer-email: Jeff Dileo <jtdileo@gmail.com>
 License: Copyright (c) 2023 Jeff Dileo.
         All rights reserved.
         
         Redistribution and use in source and binary forms, with or without
```

### Comparing `limberer-0.1/README.md` & `limberer-0.2/README.md`

 * *Files identical despite different names*

### Comparing `limberer-0.1/pyproject.toml` & `limberer-0.2/pyproject.toml`

 * *Files 9% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 [project]
 name = "limberer"
 # alternatively, limberr
-version = "0.1"
+version = "0.2"
 authors = [
   { name = "Jeff Dileo", email = "jtdileo@gmail.com" },
 ]
 maintainers = [
   { name = "Jeff Dileo", email = "jtdileo@gmail.com" },
 ]
 license = { file = "LICENSE" }
@@ -18,15 +18,16 @@
   "Programming Language :: Python :: 3.9",
 ]
 dependencies = [
   "panflute",
   "chevron",
   "weasyprint",
   "toml",
-  "markdown"
+  "markdown",
+  "pillow",
 ]
 
 [project.urls]
 repository = "https://github.com/ChaosData/limberer"
 
 [build-system]
 requires = ["setuptools>=61.0"]
```

### Comparing `limberer-0.1/src/limberer/__init__.py` & `limberer-0.2/src/limberer/__init__.py`

 * *Files 23% similar despite different names*

```diff
@@ -30,14 +30,18 @@
 import os.path
 import shutil
 import toml
 from collections.abc import Callable
 import chevron
 import weasyprint
 import markdown # temporary
+import subprocess
+import io
+
+from .pf import entrypoint
 
 # disable remote url resolution and path traversal
 def fetcher(url):
   u = None
   if url.startswith("file://"):
     u = url[7:]
   else:
@@ -65,14 +69,60 @@
   return r
 chevron.renderer._get_key = fake_get_key
 # >>> chevron.render('Hello, {{#mustache}}{{#__class__.__bases__}}{{#__subclasses__}}{{.}}{{/__subclasses__}}{{/__class__.__bases__}}{{/mustache}}!', {'mustache': 'World'})
 # 'Hello, no soup for you.!'
 # >>> chevron.render('Hello, {{#mustache}}{{#upper}}{{.}}{{/upper}}{{/mustache}}!', {'mustache': 'world'})
 # 'Hello, no soup for you!!'
 
+def convert(path, opts, toc):
+  #print("convert(" + repr(path) + ")")
+  proc1 = subprocess.run(['pandoc', '-t', 'json', path], capture_output=True)
+  if proc1.returncode != 0:
+    sys.stderr.write("error running initial pandoc command: \n")
+    sys.stderr.buffer.write(proc1.stderr)
+    sys.stderr.write("\n")
+    sys.exit(1)
+  o1 = proc1.stdout.decode('utf-8')
+
+  # run the panflute filter
+  sys.argv = ["html"]
+  iw = io.StringIO(o1)
+  ow = io.StringIO("")
+
+  headers = []
+  _headers = []
+  r = entrypoint(iw, ow, _headers)
+  ow.seek(0)
+  o2 = ow.read()
+
+  if len(_headers) == 1:
+    headers = _headers[0]
+
+  #print(repr(headers))
+  header_level = int(opts.get('toc_header_level', ['1'])[0])
+
+  for h in headers:
+    if h.level <= header_level:
+      toc.append(opts | {"name": h.identifier, "issubsection": h.level != 1})
+
+  # pass back to pandoc
+  proc2 = subprocess.run(['pandoc', '-f', 'json',
+                          '-t', 'html',
+                          '--wrap=none'],
+                         input=o2, text=True,
+                         capture_output=True)
+  if proc2.returncode != 0:
+    sys.stderr.write("error running initial pandoc command: \n")
+    sys.stderr.write(proc2.stderr)
+    sys.stderr.write("\n")
+    sys.exit(1)
+  content = proc2.stdout
+  return content
+
+
 def parse_args():
   parser = argparse.ArgumentParser(
     description='A flexible document generator based on WeasyPrint, mustache templates, and Pandoc.'
   )
   subparsers = parser.add_subparsers(dest='command', required=True,
                                      title='subcommands',
                                      description='valid subcommands',
@@ -137,29 +187,33 @@
   sections = []
   toc = []
 
   for section in config['sections']:
     if section['type'] == 'section':
       # markdown
       section_name = section['name']
-      content = open('sections/{}.md'.format(section['name']), 'r').read()
+      section_path = 'sections/{}.md'.format(section['name'])
+      content = open(section_path, 'rb').read()
+      #print(repr(content))
+      content = content.decode('utf-8')
       md = markdown.Markdown(extensions=["meta"])
       html = md.convert(content)
       opts = md.Meta | section
+      html = convert(section_path, opts, toc)
       opts['html'] = html
       opts['opts'] = opts # we occasionally need top.down.variable.paths to resolve abiguity
       template = section_template
       if "alt" in section:
         template = open('templates/{}.html'.format(section['alt']), 'r').read()
       #r = chevron.render(template, {"name": section['name'], "html": html})
       #print(opts)
       r = chevron.render(template, opts)
       sections.append(r)
-      if "title" in section:
-        toc.append(opts | {"issubsection": False})
+      #if "title" in section:
+        #toc.append(opts | {"issubsection": False})
     elif section['type'] == 'toc':
       # defer until after we get through everything else
       sections.append(section)
     else:
       # assume in templates/
       template = open('templates/{}.html'.format(section['type']), 'r').read()
       r = chevron.render(template, config)
```

### Comparing `limberer-0.1/src/limberer/static/assets/base.css` & `limberer-0.2/src/limberer/static/assets/base.css`

 * *Files identical despite different names*

### Comparing `limberer-0.1/src/limberer/static/assets/logo.svg` & `limberer-0.2/src/limberer/static/assets/logo.svg`

 * *Files identical despite different names*

### Comparing `limberer-0.1/src/limberer/static/assets/theme.css` & `limberer-0.2/src/limberer/static/assets/theme.css`

 * *Files identical despite different names*

### Comparing `limberer-0.1/src/limberer/static/sections/example2.md` & `limberer-0.2/src/limberer/static/sections/example2.md`

 * *Files identical despite different names*

### Comparing `limberer-0.1/src/limberer/static/templates/cover.html` & `limberer-0.2/src/limberer/static/templates/cover.html`

 * *Files identical despite different names*

### Comparing `limberer-0.1/src/limberer/static/templates/toc.html` & `limberer-0.2/src/limberer/static/templates/toc.html`

 * *Files 0% similar despite different names*

```diff
@@ -1,17 +1,17 @@
     <article id="contents">
       <h3>Table of Contents</h3>
       <ul class="toc">
       {{#sections}}
       {{^issubsection}}
-        <!--<li><a class="toc" href="#{{name}}"><div href="#{{name}}" class="toctext"></div><div href="#{{name}}" class="tocpagenr"></div></a></li>-->
-        <li><a class="toc" href="#{{name}}">{{title}}<div href="#{{name}}" class="tocpagenr"></div></a></li>
+        <li><a class="toc" href="#{{name}}"><div href="#{{name}}" class="toctext"></div><div href="#{{name}}" class="tocpagenr"></div></a></li>
+        <!--<li><a class="toc" href="#{{name}}">{{title}}<div href="#{{name}}" class="tocpagenr"></div></a></li>-->
       {{/issubsection}}
       {{#issubsection}}
         <ul class="toc">
-          <!--<li><a class="toc" href="#{{name}}"><div href="#{{name}}" class="toctext"></div><div href="#{{name}}" class="tocpagenr"></div></a></li>-->
-          <li><a class="toc" href="#{{name}}">{{title}}<div href="#{{name}}" class="tocpagenr"></div></a></li>
+          <li><a class="toc" href="#{{name}}"><div href="#{{name}}" class="toctext"></div><div href="#{{name}}" class="tocpagenr"></div></a></li>
+          <!--<li><a class="toc" href="#{{name}}">{{title}}<div href="#{{name}}" class="tocpagenr"></div></a></li>-->
         </ul>
       {{/issubsection}}
       {{/sections}}
       </ul>
     </article>
```

### Comparing `limberer-0.1/src/limberer.egg-info/PKG-INFO` & `limberer-0.2/src/limberer.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: limberer
-Version: 0.1
+Version: 0.2
 Summary: A flexible document generator based on weasyprint, mustache templates, and pandoc.
 Author-email: Jeff Dileo <jtdileo@gmail.com>
 Maintainer-email: Jeff Dileo <jtdileo@gmail.com>
 License: Copyright (c) 2023 Jeff Dileo.
         All rights reserved.
         
         Redistribution and use in source and binary forms, with or without
```

### Comparing `limberer-0.1/src/limberer.egg-info/SOURCES.txt` & `limberer-0.2/src/limberer.egg-info/SOURCES.txt`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,14 @@
 AUTHORS
 LICENSE
 MANIFEST.in
 README.md
 pyproject.toml
 src/limberer/__init__.py
+src/limberer/pf.py
 src/limberer.egg-info/PKG-INFO
 src/limberer.egg-info/SOURCES.txt
 src/limberer.egg-info/dependency_links.txt
 src/limberer.egg-info/entry_points.txt
 src/limberer.egg-info/requires.txt
 src/limberer.egg-info/top_level.txt
 src/limberer/static/project.toml
```


# Comparing `tmp/sphinx-tags-0.2.0.tar.gz` & `tmp/sphinx_tags-0.2.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sphinx-tags-0.2.0.tar", last modified: Sat Jan 28 20:20:30 2023, max compression
+gzip compressed data, was "sphinx_tags-0.2.1.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
```

## Comparing `sphinx-tags-0.2.0.tar` & `sphinx_tags-0.2.1.tar`

### file list

```diff
@@ -1,6 +1,6 @@
--rw-r--r--   0        0        0      719 2023-01-28 20:19:41.834128 sphinx-tags-0.2.0/CHANGELOG.md
--rw-r--r--   0        0        0     1080 2022-08-21 20:27:39.070633 sphinx-tags-0.2.0/LICENSE
--rw-r--r--   0        0        0     1683 2023-01-28 16:22:45.935737 sphinx-tags-0.2.0/README.md
--rw-r--r--   0        0        0      771 2023-01-28 16:42:11.792894 sphinx-tags-0.2.0/pyproject.toml
--rw-r--r--   0        0        0    12777 2023-01-28 20:16:14.931807 sphinx-tags-0.2.0/src/sphinx_tags/__init__.py
--rw-r--r--   0        0        0     2258 1970-01-01 00:00:00.000000 sphinx-tags-0.2.0/PKG-INFO
+-rw-r--r--   0        0        0      875 2023-06-28 12:58:44.917407 sphinx_tags-0.2.1/CHANGELOG.md
+-rw-r--r--   0        0        0     1080 2022-08-21 20:27:39.070633 sphinx_tags-0.2.1/LICENSE
+-rw-r--r--   0        0        0     1683 2023-01-28 16:22:45.935737 sphinx_tags-0.2.1/README.md
+-rw-r--r--   0        0        0      786 2023-06-28 12:57:47.347674 sphinx_tags-0.2.1/pyproject.toml
+-rw-r--r--   0        0        0    13045 2023-06-28 12:58:44.917407 sphinx_tags-0.2.1/src/sphinx_tags/__init__.py
+-rw-r--r--   0        0        0     2302 1970-01-01 00:00:00.000000 sphinx_tags-0.2.1/PKG-INFO
```

### Comparing `sphinx-tags-0.2.0/CHANGELOG.md` & `sphinx_tags-0.2.1/CHANGELOG.md`

 * *Files 10% similar despite different names*

```diff
@@ -11,7 +11,11 @@
 - Tag intro text as a parameter
 
 ## Version 0.2.0 (January 26, 2023)
 
 - Added optional integration with sphinx-design badges [gh-35](https://github.com/melissawm/sphinx-tags/pull/35)
 - Added support for symlinked sources [gh-37](https://github.com/melissawm/sphinx-tags/pull/37)
 - Documentation improvements [gh-41](https://github.com/melissawm/sphinx-tags/pull/41)
+
+## Version 0.2.1 (June 28, 2023)
+
+- Added support for tagging Jupyter Notebooks using `nbsphinx` [gh-51](https://github.com/melissawm/sphinx-tags/pull/51)
```

### Comparing `sphinx-tags-0.2.0/LICENSE` & `sphinx_tags-0.2.1/LICENSE`

 * *Files identical despite different names*

### Comparing `sphinx-tags-0.2.0/README.md` & `sphinx_tags-0.2.1/README.md`

 * *Files identical despite different names*

### Comparing `sphinx-tags-0.2.0/pyproject.toml` & `sphinx_tags-0.2.1/pyproject.toml`

 * *Files 13% similar despite different names*

```diff
@@ -20,15 +20,16 @@
     "pre-commit",
 ]
 
 [project.optional-dependencies]
 sphinx = [
     "pydata-sphinx-theme",
     "sphinx-design",
-    "myst-parser",
+    "nbsphinx",
+    "myst-parser"
 ]
 
 [project.urls]
 Home = "https://github.com/melissawm/sphinx-tags"
 
 [tool.flit.module]
 name = "sphinx_tags"
```

### Comparing `sphinx-tags-0.2.0/src/sphinx_tags/__init__.py` & `sphinx_tags-0.2.1/src/sphinx_tags/__init__.py`

 * *Files 4% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 from pathlib import Path
 from typing import List
 
 from docutils import nodes
 from sphinx.util.docutils import SphinxDirective
 from sphinx.util.logging import getLogger
 
-__version__ = "0.2.0"
+__version__ = "0.2.1"
 
 logger = getLogger("sphinx-tags")
 
 
 class TagLinks(SphinxDirective):
     """Custom directive for adding tags to Sphinx-generated files.
 
@@ -182,26 +182,33 @@
         with open(
             os.path.join(srcdir, tags_output_dir, filename), "w", encoding="utf8"
         ) as f:
             f.write("\n".join(content))
 
 
 class Entry:
-    """Extracted info from source file (*.rst/*.md)"""
+    """Extracted info from source file (*.rst/*.md/*.ipynb)"""
 
     def __init__(self, entrypath):
         self.filepath = Path(entrypath)
         with open(self.filepath, "r", encoding="utf8") as f:
             self.lines = f.read().split("\n")
         if self.filepath.name.endswith(".rst"):
             tagstart = ".. tags::"
             tagend = ""
         elif self.filepath.name.endswith(".md"):
             tagstart = "```{tags}"
             tagend = "```"
+        elif self.filepath.name.endswith(".ipynb"):
+            tagstart = '".. tags::'
+            tagend = '"'
+        else:
+            raise ValueError(
+                "Unknown file extension. Currently, only .rst, .md .ipynb are supported."
+            )
         tagline = [line for line in self.lines if tagstart in line]
         self.tags = []
         if tagline:
             tagline = tagline[0].replace(tagstart, "").rstrip(tagend)
             self.tags = tagline.split(",")
             self.tags = [tag.strip() for tag in self.tags]
 
@@ -277,15 +284,14 @@
     return tags, pages
 
 
 def update_tags(app):
     """Update tags according to pages found"""
 
     if app.config.tags_create_tags:
-
         tags_output_dir = Path(app.config.tags_output_dir)
 
         if not os.path.exists(os.path.join(app.srcdir, tags_output_dir)):
             os.makedirs(os.path.join(app.srcdir, tags_output_dir))
 
         for file in os.listdir(os.path.join(app.srcdir, tags_output_dir)):
             if file.endswith("md") or file.endswith("rst"):
```

### Comparing `sphinx-tags-0.2.0/PKG-INFO` & `sphinx_tags-0.2.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,19 +1,20 @@
 Metadata-Version: 2.1
 Name: sphinx-tags
-Version: 0.2.0
+Version: 0.2.1
 Summary: Sphinx extension to create tags for documentation pages.
 Keywords: documentation,sphinx
 Author-email: melissawm <melissawm@gmail.com>
 Description-Content-Type: text/markdown
 Classifier: License :: OSI Approved :: MIT License
 Requires-Dist: sphinx>4
 Requires-Dist: pre-commit
 Requires-Dist: pydata-sphinx-theme ; extra == "sphinx"
 Requires-Dist: sphinx-design ; extra == "sphinx"
+Requires-Dist: nbsphinx ; extra == "sphinx"
 Requires-Dist: myst-parser ; extra == "sphinx"
 Project-URL: Home, https://github.com/melissawm/sphinx-tags
 Provides-Extra: sphinx
 
 # sphinx-tags [![sphinx-tags](https://circleci.com/gh/melissawm/sphinx-tags.svg?style=svg)](https://circleci.com/gh/melissawm/sphinx-tags)
 
 A tiny Sphinx extension that implements blog-style tags for documentation.
```


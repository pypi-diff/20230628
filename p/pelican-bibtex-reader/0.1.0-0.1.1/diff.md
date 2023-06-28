# Comparing `tmp/pelican-bibtex-reader-0.1.0.tar.gz` & `tmp/pelican_bibtex_reader-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pelican-bibtex-reader-0.1.0.tar", max compression
+gzip compressed data, was "pelican_bibtex_reader-0.1.1.tar", max compression
```

## Comparing `pelican-bibtex-reader-0.1.0.tar` & `pelican_bibtex_reader-0.1.1.tar`

### file list

```diff
@@ -1,9 +1,8 @@
--rw-r--r--   0        0        0    34523 2022-09-01 12:06:39.207906 pelican-bibtex-reader-0.1.0/LICENSE
--rw-r--r--   0        0        0     2135 2022-09-18 11:41:27.374460 pelican-bibtex-reader-0.1.0/README.md
--rw-r--r--   0        0        0       45 2022-09-01 12:05:18.276528 pelican-bibtex-reader-0.1.0/pelican/plugins/pelican_bibtex_reader/__init__.py
--rw-r--r--   0        0        0     1956 2022-09-01 12:13:44.756319 pelican-bibtex-reader-0.1.0/pelican/plugins/pelican_bibtex_reader/bibtex.py
--rw-r--r--   0        0        0     1771 2022-09-18 11:04:28.267284 pelican-bibtex-reader-0.1.0/pelican/plugins/pelican_bibtex_reader/pelican_bibtex_reader.py
--rw-r--r--   0        0        0        0 2022-09-01 12:05:18.272528 pelican-bibtex-reader-0.1.0/pelican/plugins/pelican_bibtex_reader/test_pelican_bibtex_reader.py
--rw-r--r--   0        0        0     1906 2022-09-18 11:42:43.413591 pelican-bibtex-reader-0.1.0/pyproject.toml
--rw-r--r--   0        0        0     3008 1970-01-01 00:00:00.000000 pelican-bibtex-reader-0.1.0/setup.py
--rw-r--r--   0        0        0     3579 1970-01-01 00:00:00.000000 pelican-bibtex-reader-0.1.0/PKG-INFO
+-rw-r--r--   0        0        0    34523 2023-01-12 08:01:21.441238 pelican_bibtex_reader-0.1.1/LICENSE
+-rw-r--r--   0        0        0     2135 2023-01-12 08:01:21.441238 pelican_bibtex_reader-0.1.1/README.md
+-rw-r--r--   0        0        0       45 2023-01-12 08:01:21.441238 pelican_bibtex_reader-0.1.1/pelican/plugins/pelican_bibtex_reader/__init__.py
+-rw-r--r--   0        0        0     1956 2023-01-12 08:01:21.441238 pelican_bibtex_reader-0.1.1/pelican/plugins/pelican_bibtex_reader/bibtex.py
+-rw-r--r--   0        0        0     1771 2023-01-12 08:01:21.441238 pelican_bibtex_reader-0.1.1/pelican/plugins/pelican_bibtex_reader/pelican_bibtex_reader.py
+-rw-r--r--   0        0        0        0 2023-01-12 08:01:21.441238 pelican_bibtex_reader-0.1.1/pelican/plugins/pelican_bibtex_reader/test_pelican_bibtex_reader.py
+-rw-r--r--   0        0        0     1929 2023-06-28 08:02:02.861672 pelican_bibtex_reader-0.1.1/pyproject.toml
+-rw-r--r--   0        0        0     3667 1970-01-01 00:00:00.000000 pelican_bibtex_reader-0.1.1/PKG-INFO
```

### Comparing `pelican-bibtex-reader-0.1.0/LICENSE` & `pelican_bibtex_reader-0.1.1/LICENSE`

 * *Files identical despite different names*

### Comparing `pelican-bibtex-reader-0.1.0/README.md` & `pelican_bibtex_reader-0.1.1/README.md`

 * *Files identical despite different names*

### Comparing `pelican-bibtex-reader-0.1.0/pelican/plugins/pelican_bibtex_reader/bibtex.py` & `pelican_bibtex_reader-0.1.1/pelican/plugins/pelican_bibtex_reader/bibtex.py`

 * *Files identical despite different names*

### Comparing `pelican-bibtex-reader-0.1.0/pelican/plugins/pelican_bibtex_reader/pelican_bibtex_reader.py` & `pelican_bibtex_reader-0.1.1/pelican/plugins/pelican_bibtex_reader/pelican_bibtex_reader.py`

 * *Files identical despite different names*

### Comparing `pelican-bibtex-reader-0.1.0/pyproject.toml` & `pelican_bibtex_reader-0.1.1/pyproject.toml`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "pelican-bibtex-reader"
-version = "0.1.0"
+version = "0.1.1"
 description = "A Pelican reader to process BibTeX files"
 authors = ["Andreas Fischer <_@ndreas.de>"]
 license = "AGPL-3.0"
 readme = "README.md"
 keywords = ["pelican", "plugin", "bibtex"]
 repository = "https://github.com/balanceofcowards/pelican-bibtex-reader"
 documentation = "https://docs.getpelican.com"
@@ -27,14 +27,15 @@
 "Funding" = "https://donate.getpelican.com/"
 "Issue Tracker" = "https://github.com/balanceofcowards/pelican-bibtex-reader/issues"
 
 [tool.poetry.dependencies]
 python = ">=3.6.2,<4.0"
 pelican = ">=4.5"
 markdown = {version = ">=3.2", optional = true}
+bibtexparser = ">=1.0"
 
 [tool.poetry.dev-dependencies]
 black = "^22"
 flake8 = "^3.9"
 flake8-black = "^0.2"
 invoke = "^1.3"
 isort = "^5.4"
```

### Comparing `pelican-bibtex-reader-0.1.0/setup.py` & `pelican_bibtex_reader-0.1.1/PKG-INFO`

 * *Files 26% similar despite different names*

```diff
@@ -1,34 +1,95 @@
-# -*- coding: utf-8 -*-
-from setuptools import setup
+Metadata-Version: 2.1
+Name: pelican-bibtex-reader
+Version: 0.1.1
+Summary: A Pelican reader to process BibTeX files
+Home-page: https://github.com/balanceofcowards/pelican-bibtex-reader
+License: AGPL-3.0
+Keywords: pelican,plugin,bibtex
+Author: Andreas Fischer
+Author-email: _@ndreas.de
+Requires-Python: >=3.6.2,<4.0
+Classifier: Development Status :: 3 - Alpha
+Classifier: Environment :: Console
+Classifier: Framework :: Pelican
+Classifier: Framework :: Pelican :: Plugins
+Classifier: Intended Audience :: End Users/Desktop
+Classifier: License :: OSI Approved :: GNU Affero General Public License v3
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Topic :: Internet :: WWW/HTTP
+Classifier: Topic :: Software Development :: Libraries :: Python Modules
+Provides-Extra: markdown
+Requires-Dist: bibtexparser (>=1.0)
+Requires-Dist: markdown (>=3.2) ; extra == "markdown"
+Requires-Dist: pelican (>=4.5)
+Project-URL: Documentation, https://docs.getpelican.com
+Project-URL: Funding, https://donate.getpelican.com/
+Project-URL: Issue Tracker, https://github.com/balanceofcowards/pelican-bibtex-reader/issues
+Project-URL: Repository, https://github.com/balanceofcowards/pelican-bibtex-reader
+Description-Content-Type: text/markdown
+
+Pelican BibTeX Reader: A Plugin for Pelican
+====================================================
+
+[![PyPI Version](https://img.shields.io/pypi/v/pelican-bibtex-reader)](https://pypi.org/project/pelican-bibtex-reader/)
+![License](https://img.shields.io/pypi/l/pelican-bibtex-reader?color=blue)
+
+A Pelican reader to process BibTeX files
+
+Installation
+------------
+
+This plugin can be installed via:
+
+    python -m pip install pelican-bibtex-reader
+
+Usage
+-----
+
+This plugin uses [python-bibtexparser](https://github.com/sciunto-org/python-bibtexparser) to parse properly formatted BibTeX files for use in
+[Pelican](https://getpelican.com/). Just put a BibTeX file
+with ending `.bib` anywhere in your content directory.
+
+The content provided by this plugin consists of only a
+crude HTML rendering of the key-value pairs of each
+entry. However, the full bibtex database is available
+as Python object in the metadata of the page (key: `bibtexdatabase`).
+Using an appropriate template, nice lists of literature
+can be rendered, easily. Check out [the literature list on my homepage](https://andreas.fischer-family.online/pages/publications.html)
+for an example.
+
+Metadata needed for Pelican 
+(such as the title, the date, or the template to be used)
+can be added at the top of the `.bib`-file, using the following syntax:
+
+```
+% Title: Some title
+% Date: 01.02.2023
+% ...
+% Feel free to write anything else; only
+% key: value
+% pairs are parsed. All other comments are ignored.
+
+@MISC{...}
+```
+
+Contributing
+------------
+
+Contributions are welcome and much appreciated. Every little bit helps. You can contribute by improving the documentation, adding missing features, and fixing bugs. You can also help out by reviewing and commenting on [existing issues][].
+
+To start contributing to this plugin, review the [Contributing to Pelican][] documentation, beginning with the **Contributing Code** section.
 
-packages = \
-['pelican', 'pelican.plugins.pelican_bibtex_reader']
+[existing issues]: https://github.com/balanceofcowards/pelican-bibtex-reader/issues
+[Contributing to Pelican]: https://docs.getpelican.com/en/latest/contribute.html
 
-package_data = \
-{'': ['*']}
+License
+-------
 
-install_requires = \
-['pelican>=4.5']
-
-extras_require = \
-{'markdown': ['markdown>=3.2']}
-
-setup_kwargs = {
-    'name': 'pelican-bibtex-reader',
-    'version': '0.1.0',
-    'description': 'A Pelican reader to process BibTeX files',
-    'long_description': 'Pelican BibTeX Reader: A Plugin for Pelican\n====================================================\n\n[![PyPI Version](https://img.shields.io/pypi/v/pelican-bibtex-reader)](https://pypi.org/project/pelican-bibtex-reader/)\n![License](https://img.shields.io/pypi/l/pelican-bibtex-reader?color=blue)\n\nA Pelican reader to process BibTeX files\n\nInstallation\n------------\n\nThis plugin can be installed via:\n\n    python -m pip install pelican-bibtex-reader\n\nUsage\n-----\n\nThis plugin uses [python-bibtexparser](https://github.com/sciunto-org/python-bibtexparser) to parse properly formatted BibTeX files for use in\n[Pelican](https://getpelican.com/). Just put a BibTeX file\nwith ending `.bib` anywhere in your content directory.\n\nThe content provided by this plugin consists of only a\ncrude HTML rendering of the key-value pairs of each\nentry. However, the full bibtex database is available\nas Python object in the metadata of the page (key: `bibtexdatabase`).\nUsing an appropriate template, nice lists of literature\ncan be rendered, easily. Check out [the literature list on my homepage](https://andreas.fischer-family.online/pages/publications.html)\nfor an example.\n\nMetadata needed for Pelican \n(such as the title, the date, or the template to be used)\ncan be added at the top of the `.bib`-file, using the following syntax:\n\n```\n% Title: Some title\n% Date: 01.02.2023\n% ...\n% Feel free to write anything else; only\n% key: value\n% pairs are parsed. All other comments are ignored.\n\n@MISC{...}\n```\n\nContributing\n------------\n\nContributions are welcome and much appreciated. Every little bit helps. You can contribute by improving the documentation, adding missing features, and fixing bugs. You can also help out by reviewing and commenting on [existing issues][].\n\nTo start contributing to this plugin, review the [Contributing to Pelican][] documentation, beginning with the **Contributing Code** section.\n\n[existing issues]: https://github.com/balanceofcowards/pelican-bibtex-reader/issues\n[Contributing to Pelican]: https://docs.getpelican.com/en/latest/contribute.html\n\nLicense\n-------\n\nThis project is licensed under the AGPL-3.0 license.\n',
-    'author': 'Andreas Fischer',
-    'author_email': '_@ndreas.de',
-    'maintainer': 'None',
-    'maintainer_email': 'None',
-    'url': 'https://github.com/balanceofcowards/pelican-bibtex-reader',
-    'packages': packages,
-    'package_data': package_data,
-    'install_requires': install_requires,
-    'extras_require': extras_require,
-    'python_requires': '>=3.6.2,<4.0',
-}
+This project is licensed under the AGPL-3.0 license.
 
-
-setup(**setup_kwargs)
```


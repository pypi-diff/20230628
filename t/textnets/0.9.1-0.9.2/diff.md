# Comparing `tmp/textnets-0.9.1.tar.gz` & `tmp/textnets-0.9.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "textnets-0.9.1.tar", max compression
+gzip compressed data, was "textnets-0.9.2.tar", max compression
```

## Comparing `textnets-0.9.1.tar` & `textnets-0.9.2.tar`

### file list

```diff
@@ -1,37 +1,37 @@
--rw-r--r--   0        0        0      264 2023-06-16 09:46:43.209871 textnets-0.9.1/AUTHORS.rst
--rw-r--r--   0        0        0     3868 2023-06-16 09:46:43.209871 textnets-0.9.1/CONTRIBUTING.rst
--rw-r--r--   0        0        0    13699 2023-06-16 09:46:43.209871 textnets-0.9.1/HISTORY.rst
--rw-r--r--   0        0        0    35149 2023-06-16 09:46:43.209871 textnets-0.9.1/LICENSE
--rw-r--r--   0        0        0     4464 2023-06-16 09:46:43.209871 textnets-0.9.1/README.rst
--rw-r--r--   0        0        0      296 2023-06-16 09:46:43.209871 textnets-0.9.1/build.py
--rw-r--r--   0        0        0       83 2023-06-16 09:46:43.209871 textnets-0.9.1/docs/_static/custom.css
--rw-r--r--   0        0        0  1210458 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/_static/impeachment-statements.svg
--rw-r--r--   0        0        0     5739 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/_static/textnets-logo.svg
--rw-r--r--   0        0        0     7861 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/advanced.rst
--rw-r--r--   0        0        0       28 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/authors.rst
--rw-r--r--   0        0        0       78 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/bibliography.rst
--rwxr-xr-x   0        0        0     5470 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/conf.py
--rw-r--r--   0        0        0       33 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/contributing.rst
--rw-r--r--   0        0        0       28 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/history.rst
--rw-r--r--   0        0        0      290 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/index.rst
--rw-r--r--   0        0        0     3821 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/installation.rst
--rw-r--r--   0        0        0      102 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/license.rst
--rw-r--r--   0        0        0      105 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/reference.rst
--rw-r--r--   0        0        0     4423 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/refs.bib
--rw-r--r--   0        0        0     5625 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/textnets-logo-sm.svg
--rw-r--r--   0        0        0    15567 2023-06-16 09:46:43.217871 textnets-0.9.1/docs/tutorial.rst
--rw-r--r--   0        0        0     2543 2023-06-16 09:46:43.221871 textnets-0.9.1/pyproject.toml
--rw-r--r--   0        0        0       38 2023-06-16 09:46:43.221871 textnets-0.9.1/tests/__init__.py
--rw-r--r--   0        0        0      291 2023-06-16 09:46:43.221871 textnets-0.9.1/tests/conftest.py
--rw-r--r--   0        0        0    11722 2023-06-16 09:46:43.221871 textnets-0.9.1/tests/test_textnets.py
--rw-r--r--   0        0        0     1771 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/__init__.py
--rw-r--r--   0        0        0       47 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/_ext.pxd
--rw-r--r--   0        0        0      215 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/_ext.pyx
--rw-r--r--   0        0        0     2488 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/_util.py
--rw-r--r--   0        0        0     3999 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/config.py
--rw-r--r--   0        0        0    22166 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/corpus.py
--rw-r--r--   0        0        0     6093 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/examples.py
--rw-r--r--   0        0        0     1367 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/fca.py
--rw-r--r--   0        0        0    34740 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/network.py
--rw-r--r--   0        0        0     8954 2023-06-16 09:46:43.221871 textnets-0.9.1/textnets/viz.py
--rw-r--r--   0        0        0     6404 1970-01-01 00:00:00.000000 textnets-0.9.1/PKG-INFO
+-rw-r--r--   0        0        0      264 2023-06-28 14:05:40.319017 textnets-0.9.2/AUTHORS.rst
+-rw-r--r--   0        0        0     3868 2023-06-28 14:05:40.319017 textnets-0.9.2/CONTRIBUTING.rst
+-rw-r--r--   0        0        0    13834 2023-06-28 14:05:40.319017 textnets-0.9.2/HISTORY.rst
+-rw-r--r--   0        0        0    35149 2023-06-28 14:05:40.319017 textnets-0.9.2/LICENSE
+-rw-r--r--   0        0        0     4474 2023-06-28 14:05:40.319017 textnets-0.9.2/README.rst
+-rw-r--r--   0        0        0      296 2023-06-28 14:05:40.319017 textnets-0.9.2/build.py
+-rw-r--r--   0        0        0  1210458 2023-06-28 14:05:40.323017 textnets-0.9.2/docs/_static/impeachment-statements.svg
+-rw-r--r--   0        0        0     5739 2023-06-28 14:05:40.323017 textnets-0.9.2/docs/_static/textnets-logo.svg
+-rw-r--r--   0        0        0     7854 2023-06-28 14:05:40.323017 textnets-0.9.2/docs/advanced.rst
+-rw-r--r--   0        0        0       28 2023-06-28 14:05:40.323017 textnets-0.9.2/docs/authors.rst
+-rw-r--r--   0        0        0       78 2023-06-28 14:05:40.323017 textnets-0.9.2/docs/bibliography.rst
+-rwxr-xr-x   0        0        0     5433 2023-06-28 14:05:40.323017 textnets-0.9.2/docs/conf.py
+-rw-r--r--   0        0        0       33 2023-06-28 14:05:40.323017 textnets-0.9.2/docs/contributing.rst
+-rw-r--r--   0        0        0       28 2023-06-28 14:05:40.323017 textnets-0.9.2/docs/history.rst
+-rw-r--r--   0        0        0      290 2023-06-28 14:05:40.327017 textnets-0.9.2/docs/index.rst
+-rw-r--r--   0        0        0     3826 2023-06-28 14:05:40.327017 textnets-0.9.2/docs/installation.rst
+-rw-r--r--   0        0        0      102 2023-06-28 14:05:40.327017 textnets-0.9.2/docs/license.rst
+-rw-r--r--   0        0        0      105 2023-06-28 14:05:40.327017 textnets-0.9.2/docs/reference.rst
+-rw-r--r--   0        0        0     4423 2023-06-28 14:05:40.327017 textnets-0.9.2/docs/refs.bib
+-rw-r--r--   0        0        0     5625 2023-06-28 14:05:40.327017 textnets-0.9.2/docs/textnets-logo-sm.svg
+-rw-r--r--   0        0        0    15533 2023-06-28 14:05:40.327017 textnets-0.9.2/docs/tutorial.rst
+-rw-r--r--   0        0        0     2828 2023-06-28 14:05:40.327017 textnets-0.9.2/pyproject.toml
+-rw-r--r--   0        0        0       38 2023-06-28 14:05:40.327017 textnets-0.9.2/tests/__init__.py
+-rw-r--r--   0        0        0      291 2023-06-28 14:05:40.327017 textnets-0.9.2/tests/conftest.py
+-rw-r--r--   0        0        0    11722 2023-06-28 14:05:40.327017 textnets-0.9.2/tests/test_textnets.py
+-rw-r--r--   0        0        0     1771 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/__init__.py
+-rw-r--r--   0        0        0       47 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/_ext.pxd
+-rw-r--r--   0        0        0      215 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/_ext.pyx
+-rw-r--r--   0        0        0     2488 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/_util.py
+-rw-r--r--   0        0        0     3999 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/config.py
+-rw-r--r--   0        0        0    22166 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/corpus.py
+-rw-r--r--   0        0        0     6093 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/examples.py
+-rw-r--r--   0        0        0     1367 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/fca.py
+-rw-r--r--   0        0        0    34740 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/network.py
+-rw-r--r--   0        0        0     8954 2023-06-28 14:05:40.327017 textnets-0.9.2/textnets/viz.py
+-rw-r--r--   0        0        0     5740 1970-01-01 00:00:00.000000 textnets-0.9.2/setup.py
+-rw-r--r--   0        0        0     6548 1970-01-01 00:00:00.000000 textnets-0.9.2/PKG-INFO
```

### Comparing `textnets-0.9.1/CONTRIBUTING.rst` & `textnets-0.9.2/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/HISTORY.rst` & `textnets-0.9.2/HISTORY.rst`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,17 @@
 =======
 History
 =======
 
+0.9.2 (2023-06-28)
+------------------
+* Improves documentation.
+* Updates to scipy 1.10.
+* Fixes how the compiled extension is built.
+
 0.9.1 (2023-06-16)
 ------------------
 * Only fixes deployment to PyPI, otherwise unchanged from previous version.
 
 0.9.0 (2023-06-15)
 ------------------
 * Improves documentation.
```

### Comparing `textnets-0.9.1/LICENSE` & `textnets-0.9.2/LICENSE`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/README.rst` & `textnets-0.9.2/README.rst`

 * *Files 2% similar despite different names*

```diff
@@ -29,14 +29,17 @@
 .. figure:: https://textnets.readthedocs.io/en/dev/_static/impeachment-statements.svg
    :alt: Bipartite network graph
 
    Network of U.S. Senators and words used in their official statements
    following the acquittal vote in the 2020 Senate impeachment trial (`source
    <https://www.jboy.space/blog/enemies-foreign-and-partisan.html>`_).
 
+**textnets** is free software under the terms of the GNU General Public License
+v3.
+
 The ideas underlying **textnets** are presented in this paper:
 
   Christopher A. Bail, "`Combining natural language processing and network
   analysis to examine how advocacy organizations stimulate conversation on social
   media`__," *Proceedings of the National Academy of Sciences of the United States
   of America* 113, no. 42 (2016), 11823–11828, doi:10.1073/pnas.1607151113.
 
@@ -44,37 +47,34 @@
 
 Initially begun as a Python implementation of `Chris Bail's textnets package
 for R`_, **textnets** now comprises several unique features for term extraction
 and weighing, visualization, and analysis.
 
 .. _`Chris Bail's textnets package for R`: https://github.com/cbail/textnets/
 
-**textnets** is free software under the terms of the GNU General Public License
-v3.
-
 Features
 --------
 
 **textnets** builds on `spaCy`_, a state-of-the-art library for
 natural-language processing, and `igraph`_ for network analysis. It uses the
 `Leiden algorithm`_ for community detection, which is able to perform community
 detection on the bipartite (word–group) network.
 
 .. _`igraph`: http://igraph.org/python/
 .. _`Leiden algorithm`: https://doi.org/10.1038/s41598-019-41695-z
 .. _`spaCy`: https://spacy.io/
 
-**textnets** seamlessly integrates with Python's excellent `scientific stack`_.
+**textnets** is installable using the ``conda``, ``pip`` and ``nix`` package
+managers. It requires Python 3.8 or higher.
+
+**textnets** integrates seamlessly with Python's excellent `scientific stack`_.
 That means that you can use **textnets** to analyze and visualize your data in
 Jupyter notebooks!
 
-.. _`scientific stack`: https://numfocus.org/
-
-**textnets** is easily installable using the ``conda`` and ``pip`` package
-managers. It requires Python 3.8 or higher.
+.. _`scientific stack`: https://scientific-python.org
 
 Read `the documentation <https://textnets.readthedocs.io>`_ to learn more about
 the package's features.
 
 Citation
 --------
```

### Comparing `textnets-0.9.1/docs/_static/impeachment-statements.svg` & `textnets-0.9.2/docs/_static/impeachment-statements.svg`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/docs/_static/textnets-logo.svg` & `textnets-0.9.2/docs/_static/textnets-logo.svg`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/docs/advanced.rst` & `textnets-0.9.2/docs/advanced.rst`

 * *Files 0% similar despite different names*

```diff
@@ -69,15 +69,16 @@
 
    terms.plot(label_nodes=True, color_clusters=part)
 
 Alternately, we can also overwrite the textnet's ``clusters`` property::
 
    terms.clusters = part
 
-To return to the default (clusters detected by the Leiden algorithm), simply delete the clusters property::
+To return to the default (clusters detected by the Leiden algorithm), delete
+the clusters property::
 
    del terms.clusters
 
 Implemented in leidenalg
 ~~~~~~~~~~~~~~~~~~~~~~~~
 
 The ``leidenalg`` package is installed as a dependency of **textnets**. It can
@@ -191,15 +192,15 @@
 
 Alternative methods of term extraction and weighing
 ---------------------------------------------------
 
 By default, **textnets** leverages spaCy language models to break up your
 corpus when you call `noun_phrases`, `ngrams` or `tokenized`, and it uses
 *tf-idf* term weights. There are many alternative ways of extracting terms and
-weighing them, and by defining a simple function, you can use them with
+weighing them, and by defining a custom function, you can use them with
 **textnets**.
 
 This example uses `YAKE! <http://yake.inesctec.pt/>`__, the popular library for
 keyword extraction, to extract keywords from a corpus and weighs them according
 to their significance.
 
 This example requires ``yake`` to be installed.
```

### Comparing `textnets-0.9.1/docs/conf.py` & `textnets-0.9.2/docs/conf.py`

 * *Files 2% similar despite different names*

```diff
@@ -116,17 +116,14 @@
   "github_url": "https://github.com/jboynyc/textnets"
 }
 
 # Add any paths that contain custom static files (such as style sheets) here,
 # relative to this directory. They are copied after the builtin static files,
 # so a file named "default.css" will overwrite the builtin "default.css".
 html_static_path = ["_static"]
-html_css_files = [
-  "custom.css",
-]
 
 html_logo = "_static/textnets-logo.svg"
 
 # -- Options for HTMLHelp output ---------------------------------------
 
 # Output file base name for HTML help builder.
 htmlhelp_basename = "textnetsdoc"
```

### Comparing `textnets-0.9.1/docs/installation.rst` & `textnets-0.9.2/docs/installation.rst`

 * *Files 2% similar despite different names*

```diff
@@ -19,16 +19,16 @@
 
    Please note that **textnets** requires Python 3.8 or newer to run.
 
 Using conda
 -----------
 
 This is the preferred method for most users. The `Anaconda Python
-distribution`_ is an easy way to get up and running with Python, especially if
-you are on a Mac or Windows system.
+distribution`_ is a convenient way to get up and running with Python,
+especially if you are on a Mac or Windows system.
 
 .. _Anaconda Python distribution: https://www.anaconda.com/products/individual
 
 Once it is installed you can use its package manager ``conda`` to install
 **textnets**::
 
    $ conda install -c conda-forge textnets
```

### Comparing `textnets-0.9.1/docs/refs.bib` & `textnets-0.9.2/docs/refs.bib`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/docs/textnets-logo-sm.svg` & `textnets-0.9.2/docs/textnets-logo-sm.svg`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/docs/tutorial.rst` & `textnets-0.9.2/docs/tutorial.rst`

 * *Files 2% similar despite different names*

```diff
@@ -197,15 +197,15 @@
 are only partially supported, so `noun_phrases` will likely not function.)
 
 From Pandas
 ~~~~~~~~~~~
 
 `Corpus` can read documents directly from pandas' `Series <pd:pandas.Series>`
 or `DataFrame <pd:pandas.DataFrame>`; mangling your data into the appropriate
-format should only take :doc:`one or two easy steps
+format should only take :doc:`one or two steps
 <pd:getting_started/intro_tutorials/10_text_data>`. The important thing is to
 have the texts in one column, and the document labels as the index.
 
 .. code:: python
 
    corpus = tn.Corpus(series, lang="nl")
    # or alternately:
@@ -243,15 +243,15 @@
 passed to `pandas.read_sql` and `pandas.read_csv` respectively.
 
 From Files
 ~~~~~~~~~~
 
 Perhaps you have each document you want to include in your textnet stored on
 disk in a separate text file. For such cases, `Corpus` comes with a utility,
-`from_files`. You can simply pass a path to it using a `globbing
+`from_files`. You can pass it a path using a `globbing
 <https://en.wikipedia.org/wiki/Glob_(programming)>`__ pattern:
 
 .. code:: python
 
    corpus = tn.Corpus.from_files("/path/to/texts/*.txt")
 
 You can also pass it a list of paths:
@@ -343,15 +343,15 @@
 ``bipartite_layout``, ``circular_layout``, or ``sugiyama_layout``, which help
 to spatially separate the two node types.
 
 You may want terms that are used in more documents to appear bigger in the
 plot. In that case, use the ``scale_nodes_by`` argument with the value
 ``degree``. Other useful options include ``label_term_nodes``,
 ``label_doc_nodes``, and ``label_edges``. These are all boolean options, so
-simply pass the value ``True`` to enable them.
+your can enable them by passing the value ``True``.
 
 Finally, enabling ``show_clusters`` will draw polygons around detected groups
 of nodes with a community structure.
 
 Projecting
 ----------
 
@@ -417,15 +417,15 @@
 
    words.save_graph("term_network.gml")
 
 This will create a file in the current directory in Graph Modeling Language
 (GML) format. This can then be opened by Pajek, yEd, Gephi and other programs.
 Consult the docs for `Textnet.save_graph` for a list of supported formats.
 
-If instead you want to save a plot of a network, the easiest thing is to pass
-the ``target`` keyword to the `Textnet.plot` method.
+If instead you want to save a plot of a network, pass the ``target`` keyword to
+the `Textnet.plot` method.
 
 .. code:: python
 
    words.plot(label_nodes=True, color_clusters=True, target="term_network.svg")
 
 Supported file formats include PNG, EPS and SVG.
```

### Comparing `textnets-0.9.1/tests/test_textnets.py` & `textnets-0.9.2/tests/test_textnets.py`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/textnets/__init__.py` & `textnets-0.9.2/textnets/__init__.py`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/textnets/_util.py` & `textnets-0.9.2/textnets/_util.py`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/textnets/config.py` & `textnets-0.9.2/textnets/config.py`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/textnets/corpus.py` & `textnets-0.9.2/textnets/corpus.py`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/textnets/examples.py` & `textnets-0.9.2/textnets/examples.py`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/textnets/fca.py` & `textnets-0.9.2/textnets/fca.py`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/textnets/network.py` & `textnets-0.9.2/textnets/network.py`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/textnets/viz.py` & `textnets-0.9.2/textnets/viz.py`

 * *Files identical despite different names*

### Comparing `textnets-0.9.1/PKG-INFO` & `textnets-0.9.2/PKG-INFO`

 * *Files 6% similar despite different names*

```diff
@@ -1,22 +1,25 @@
 Metadata-Version: 2.1
 Name: textnets
-Version: 0.9.1
+Version: 0.9.2
 Summary: Automated text analysis with networks
 Home-page: https://textnets.readthedocs.io
 License: GNU General Public License v3
 Keywords: computational social science,network analysis,nlp,text analysis,visualization
 Author: John D. Boy
 Author-email: jboy@bius.moe
 Requires-Python: >=3.8.1,<3.12
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: License :: Other/Proprietary License
 Classifier: Natural Language :: English
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Cython
+Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: 3 :: Only
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Topic :: Scientific/Engineering :: Visualization
@@ -25,15 +28,15 @@
 Requires-Dist: Cython (>=0.29.24,<0.30.0)
 Requires-Dist: cairocffi (>=1.4.0,<2.0.0) ; sys_platform == "linux" or sys_platform == "darwin"
 Requires-Dist: concepts (>=0.9.2,<0.10.0) ; extra == "fca"
 Requires-Dist: igraph (>=0.10.4,<0.11.0)
 Requires-Dist: leidenalg (>=0.9.0,<0.10.0)
 Requires-Dist: pandas (>=2.0.1,<3.0.0)
 Requires-Dist: pycairo (>=1.22.0,<2.0.0) ; sys_platform == "win32"
-Requires-Dist: scipy (>=1.9.1,<2.0.0)
+Requires-Dist: scipy (>=1.10.0,<2.0.0)
 Requires-Dist: setuptools (>=41)
 Requires-Dist: spacy (>=3.5.3,<4.0.0)
 Requires-Dist: toolz (>=0.12.0,<0.13.0)
 Requires-Dist: tqdm (>=4.64.1,<5.0.0)
 Requires-Dist: wasabi (>=0.10.1)
 Project-URL: Bug Tracker, https://github.com/jboynyc/textnets/issues
 Project-URL: Changelog, https://textnets.readthedocs.io/en/stable/history.html
@@ -72,14 +75,17 @@
 .. figure:: https://textnets.readthedocs.io/en/dev/_static/impeachment-statements.svg
    :alt: Bipartite network graph
 
    Network of U.S. Senators and words used in their official statements
    following the acquittal vote in the 2020 Senate impeachment trial (`source
    <https://www.jboy.space/blog/enemies-foreign-and-partisan.html>`_).
 
+**textnets** is free software under the terms of the GNU General Public License
+v3.
+
 The ideas underlying **textnets** are presented in this paper:
 
   Christopher A. Bail, "`Combining natural language processing and network
   analysis to examine how advocacy organizations stimulate conversation on social
   media`__," *Proceedings of the National Academy of Sciences of the United States
   of America* 113, no. 42 (2016), 11823–11828, doi:10.1073/pnas.1607151113.
 
@@ -87,37 +93,34 @@
 
 Initially begun as a Python implementation of `Chris Bail's textnets package
 for R`_, **textnets** now comprises several unique features for term extraction
 and weighing, visualization, and analysis.
 
 .. _`Chris Bail's textnets package for R`: https://github.com/cbail/textnets/
 
-**textnets** is free software under the terms of the GNU General Public License
-v3.
-
 Features
 --------
 
 **textnets** builds on `spaCy`_, a state-of-the-art library for
 natural-language processing, and `igraph`_ for network analysis. It uses the
 `Leiden algorithm`_ for community detection, which is able to perform community
 detection on the bipartite (word–group) network.
 
 .. _`igraph`: http://igraph.org/python/
 .. _`Leiden algorithm`: https://doi.org/10.1038/s41598-019-41695-z
 .. _`spaCy`: https://spacy.io/
 
-**textnets** seamlessly integrates with Python's excellent `scientific stack`_.
+**textnets** is installable using the ``conda``, ``pip`` and ``nix`` package
+managers. It requires Python 3.8 or higher.
+
+**textnets** integrates seamlessly with Python's excellent `scientific stack`_.
 That means that you can use **textnets** to analyze and visualize your data in
 Jupyter notebooks!
 
-.. _`scientific stack`: https://numfocus.org/
-
-**textnets** is easily installable using the ``conda`` and ``pip`` package
-managers. It requires Python 3.8 or higher.
+.. _`scientific stack`: https://scientific-python.org
 
 Read `the documentation <https://textnets.readthedocs.io>`_ to learn more about
 the package's features.
 
 Citation
 --------
```


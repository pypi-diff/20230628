# Comparing `tmp/afscgap-1.0.3.tar.gz` & `tmp/afscgap-1.0.4.tar.gz`

## Comparing `afscgap-1.0.3.tar` & `afscgap-1.0.4.tar`

### file list

```diff
@@ -1,40 +1,40 @@
--rw-r--r--   0        0        0       52 2020-02-02 00:00:00.000000 afscgap-1.0.3/.gitattributes
--rw-r--r--   0        0        0     2071 2020-02-02 00:00:00.000000 afscgap-1.0.3/.zenodo.json
--rw-r--r--   0        0        0      417 2020-02-02 00:00:00.000000 afscgap-1.0.3/CITATION.cff
--rw-r--r--   0        0        0     2780 2020-02-02 00:00:00.000000 afscgap-1.0.3/CONDUCT.md
--rw-r--r--   0        0        0     7583 2020-02-02 00:00:00.000000 afscgap-1.0.3/CONTRIBUTING.md
--rw-r--r--   0        0        0      330 2020-02-02 00:00:00.000000 afscgap-1.0.3/build_docs.sh
--rw-r--r--   0        0        0      653 2020-02-02 00:00:00.000000 afscgap-1.0.3/gruntfile.js
--rw-r--r--   0        0        0       37 2020-02-02 00:00:00.000000 afscgap-1.0.3/install_browser.sh
--rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 afscgap-1.0.3/mkdocs.yml
--rw-r--r--   0        0        0   178220 2020-02-02 00:00:00.000000 afscgap-1.0.3/package-lock.json
--rw-r--r--   0        0        0      141 2020-02-02 00:00:00.000000 afscgap-1.0.3/package.json
--rw-r--r--   0        0        0       64 2020-02-02 00:00:00.000000 afscgap-1.0.3/setup.cfg
--rw-r--r--   0        0        0      217 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/README.md
--rw-r--r--   0        0        0    58901 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/__init__.py
--rw-r--r--   0        0        0    42895 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/client.py
--rw-r--r--   0        0        0     9440 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/convert.py
--rw-r--r--   0        0        0     5132 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/cursor.py
--rw-r--r--   0        0        0     1110 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/http_util.py
--rw-r--r--   0        0        0    37009 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/inference.py
--rw-r--r--   0        0        0    37762 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/model.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/py.typed
--rw-r--r--   0        0        0     2914 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/query_util.py
--rw-r--r--   0        0        0      750 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/typesdef.py
--rw-r--r--   0        0        0     1451 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/building.md
--rw-r--r--   0        0        0     5761 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/inference.md
--rw-r--r--   0        0        0     3686 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/limitations.md
--rw-r--r--   0        0        0    12988 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/model.md
--rw-r--r--   0        0        0     3063 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/objectives.md
--rw-r--r--   0        0        0    10255 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/usage.md
--rw-r--r--   0        0        0      508 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/README.md
--rw-r--r--   0        0        0    13278 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/architecture.drawio
--rw-r--r--   0        0        0    87762 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/library.png
--rw-r--r--   0        0        0     5641 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/paper.bib
--rw-r--r--   0        0        0     7744 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/paper.md
--rw-r--r--   0        0        0   173860 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/viz.png
--rw-r--r--   0        0        0      295 2020-02-02 00:00:00.000000 afscgap-1.0.3/.gitignore
--rw-r--r--   0        0        0     1613 2020-02-02 00:00:00.000000 afscgap-1.0.3/LICENSE.md
--rw-r--r--   0        0        0    11107 2020-02-02 00:00:00.000000 afscgap-1.0.3/README.md
--rw-r--r--   0        0        0     1434 2020-02-02 00:00:00.000000 afscgap-1.0.3/pyproject.toml
--rw-r--r--   0        0        0    12576 2020-02-02 00:00:00.000000 afscgap-1.0.3/PKG-INFO
+-rw-r--r--   0        0        0       52 2020-02-02 00:00:00.000000 afscgap-1.0.4/.gitattributes
+-rw-r--r--   0        0        0     2071 2020-02-02 00:00:00.000000 afscgap-1.0.4/.zenodo.json
+-rw-r--r--   0        0        0      417 2020-02-02 00:00:00.000000 afscgap-1.0.4/CITATION.cff
+-rw-r--r--   0        0        0     2780 2020-02-02 00:00:00.000000 afscgap-1.0.4/CONDUCT.md
+-rw-r--r--   0        0        0     7583 2020-02-02 00:00:00.000000 afscgap-1.0.4/CONTRIBUTING.md
+-rw-r--r--   0        0        0      330 2020-02-02 00:00:00.000000 afscgap-1.0.4/build_docs.sh
+-rw-r--r--   0        0        0      653 2020-02-02 00:00:00.000000 afscgap-1.0.4/gruntfile.js
+-rw-r--r--   0        0        0       37 2020-02-02 00:00:00.000000 afscgap-1.0.4/install_browser.sh
+-rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 afscgap-1.0.4/mkdocs.yml
+-rw-r--r--   0        0        0   178220 2020-02-02 00:00:00.000000 afscgap-1.0.4/package-lock.json
+-rw-r--r--   0        0        0      141 2020-02-02 00:00:00.000000 afscgap-1.0.4/package.json
+-rw-r--r--   0        0        0       64 2020-02-02 00:00:00.000000 afscgap-1.0.4/setup.cfg
+-rw-r--r--   0        0        0      217 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/README.md
+-rw-r--r--   0        0        0    58901 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/__init__.py
+-rw-r--r--   0        0        0    42895 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/client.py
+-rw-r--r--   0        0        0     9440 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/convert.py
+-rw-r--r--   0        0        0     5132 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/cursor.py
+-rw-r--r--   0        0        0     1110 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/http_util.py
+-rw-r--r--   0        0        0    37009 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/inference.py
+-rw-r--r--   0        0        0    37762 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/model.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/py.typed
+-rw-r--r--   0        0        0     2914 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/query_util.py
+-rw-r--r--   0        0        0      750 2020-02-02 00:00:00.000000 afscgap-1.0.4/afscgap/typesdef.py
+-rw-r--r--   0        0        0     1451 2020-02-02 00:00:00.000000 afscgap-1.0.4/docs/building.md
+-rw-r--r--   0        0        0     5761 2020-02-02 00:00:00.000000 afscgap-1.0.4/docs/inference.md
+-rw-r--r--   0        0        0     3686 2020-02-02 00:00:00.000000 afscgap-1.0.4/docs/limitations.md
+-rw-r--r--   0        0        0    12988 2020-02-02 00:00:00.000000 afscgap-1.0.4/docs/model.md
+-rw-r--r--   0        0        0     3063 2020-02-02 00:00:00.000000 afscgap-1.0.4/docs/objectives.md
+-rw-r--r--   0        0        0    10255 2020-02-02 00:00:00.000000 afscgap-1.0.4/docs/usage.md
+-rw-r--r--   0        0        0      508 2020-02-02 00:00:00.000000 afscgap-1.0.4/paper/README.md
+-rw-r--r--   0        0        0    13278 2020-02-02 00:00:00.000000 afscgap-1.0.4/paper/architecture.drawio
+-rw-r--r--   0        0        0    87762 2020-02-02 00:00:00.000000 afscgap-1.0.4/paper/library.png
+-rw-r--r--   0        0        0     5641 2020-02-02 00:00:00.000000 afscgap-1.0.4/paper/paper.bib
+-rw-r--r--   0        0        0     7743 2020-02-02 00:00:00.000000 afscgap-1.0.4/paper/paper.md
+-rw-r--r--   0        0        0   173860 2020-02-02 00:00:00.000000 afscgap-1.0.4/paper/viz.png
+-rw-r--r--   0        0        0      295 2020-02-02 00:00:00.000000 afscgap-1.0.4/.gitignore
+-rw-r--r--   0        0        0     1613 2020-02-02 00:00:00.000000 afscgap-1.0.4/LICENSE.md
+-rw-r--r--   0        0        0    11149 2020-02-02 00:00:00.000000 afscgap-1.0.4/README.md
+-rw-r--r--   0        0        0     1434 2020-02-02 00:00:00.000000 afscgap-1.0.4/pyproject.toml
+-rw-r--r--   0        0        0    12618 2020-02-02 00:00:00.000000 afscgap-1.0.4/PKG-INFO
```

### Comparing `afscgap-1.0.3/.zenodo.json` & `afscgap-1.0.4/.zenodo.json`

 * *Files 4% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9583333333333334%*

 * *Differences: {"'version'": "'1.0.4'"}*

```diff
@@ -47,9 +47,9 @@
             "identifier": "10.5281/zenodo.7991875",
             "relation": "isNewVersionOf",
             "scheme": "doi"
         }
     ],
     "title": "Pyafscgap.org: Open source multi-modal Python-based tools for NOAA AFSC RACE GAP",
     "upload_type": "software",
-    "version": "1.0.2"
+    "version": "1.0.4"
 }
```

### Comparing `afscgap-1.0.3/CONDUCT.md` & `afscgap-1.0.4/CONDUCT.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/CONTRIBUTING.md` & `afscgap-1.0.4/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/gruntfile.js` & `afscgap-1.0.4/gruntfile.js`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/package-lock.json` & `afscgap-1.0.4/package-lock.json`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/afscgap/__init__.py` & `afscgap-1.0.4/afscgap/__init__.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/afscgap/client.py` & `afscgap-1.0.4/afscgap/client.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/afscgap/convert.py` & `afscgap-1.0.4/afscgap/convert.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/afscgap/cursor.py` & `afscgap-1.0.4/afscgap/cursor.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/afscgap/http_util.py` & `afscgap-1.0.4/afscgap/http_util.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/afscgap/inference.py` & `afscgap-1.0.4/afscgap/inference.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/afscgap/model.py` & `afscgap-1.0.4/afscgap/model.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/afscgap/query_util.py` & `afscgap-1.0.4/afscgap/query_util.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/afscgap/typesdef.py` & `afscgap-1.0.4/afscgap/typesdef.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/docs/building.md` & `afscgap-1.0.4/docs/building.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/docs/inference.md` & `afscgap-1.0.4/docs/inference.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/docs/limitations.md` & `afscgap-1.0.4/docs/limitations.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/docs/model.md` & `afscgap-1.0.4/docs/model.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/docs/objectives.md` & `afscgap-1.0.4/docs/objectives.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/docs/usage.md` & `afscgap-1.0.4/docs/usage.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/paper/architecture.drawio` & `afscgap-1.0.4/paper/architecture.drawio`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/paper/library.png` & `afscgap-1.0.4/paper/library.png`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/paper/paper.bib` & `afscgap-1.0.4/paper/paper.bib`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/paper/paper.md` & `afscgap-1.0.4/paper/paper.md`

 * *Files 0% similar despite different names*

```diff
@@ -42,15 +42,15 @@
  - Improved developer usability.
  - Memory-efficient algorithms for zero catch inference.
  - Zero-code visualization tools.
 
 Altogether, these open source tools extend the reach and approachability of GAP's multiple survey programs to support analysis like longitudinal catch per unit effort (CPUE) in context of environmental changes [@notebook].
 
 ## Developer usability
-Working with these data requires knowledge of tools ouside the Python "standard toolset" like closed-source ORDS query language [@ords]. While the `afscgap` package offers easier access to the official REST service, it also crucially offers ORDS compilation, documented types, and lazy access to these large datasets. Together, these tools enable Python developers to efficiently use familiar patterns to interact with these data: type checking, standard documentation, and compatibility with common Python data-related libraries.
+Working with these data requires knowledge of tools outside the Python "standard toolset" like closed-source ORDS query language [@ords]. While the `afscgap` package offers easier access to the official REST service, it also crucially offers ORDS compilation, documented types, and lazy access to these large datasets. Together, these tools enable Python developers to efficiently use familiar patterns to interact with these data: type checking, standard documentation, and compatibility with common Python data-related libraries.
 
 ## Record inference
 Surveys on their own within the API struggle supporting some investigations as they provide "presence-only" data [@inport]. For example, the API may readily yield total mass of Pacific cod but not its geohash-aggregated CPUE [@geohash].
 
 $$CPUE_{species} = \frac{m_{species}}{A_{swept}}$$
 
 Metrics like CPUE need "absence data" or hauls in which the species was not recorded. This package can efficiently infer those results [@notebook].
@@ -99,17 +99,17 @@
 In addition to use in a graduate classroom setting, five individuals with relevant background offered feedback on this open source visualization with four aided by a think-aloud prompt^[Discussion limited to tool-specific needs assessment / quality improvement, collecting information about the tool and not individuals. IRB questionnaire on file finds "project does not constitute human subjects research" and review is not required.] [@thinkaloud].
 
 ## Limitations
 As further documented in the repository [@readme], these tools:
 
  - Run single-threaded and synchronous.
  - Aggregate hauls as points in visualization due to data limitation.
- - Ignore hauls if entirelly excluded by NOAA.
+ - Ignore hauls if entirely excluded by NOAA.
 
-# Acknowledgements
+# Acknowledgments
 Thanks to:
 
  - Runtime dependencies: ColorBrewer, D3, Flask, Geolib, Requests, Toolz, and Papa Parse [@colorbrewer; @d3; @flask; @geolib; @requests; @toolz; @papa].
  - Library advice: Carl Boettiger, Fernando Perez, and PyOpenSci reviewers.
  - Visualization advice: Magali de Bruyn, Brookie Guzder-Williams, Angela Hayes, David Joy, and Maya Weltman-Fahs.
  - Lewis Barnett, Emily Markowitz, and Ciera Martinez for general guidance.
  - Draw.io for diagrams [@diagrams].
```

### Comparing `afscgap-1.0.3/paper/viz.png` & `afscgap-1.0.4/paper/viz.png`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/LICENSE.md` & `afscgap-1.0.4/LICENSE.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.3/README.md` & `afscgap-1.0.4/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -151,14 +151,15 @@
 
 <br>
 <br>
 
 ## Version history
 Annotated version history:
 
+ - `1.0.4`: Minor documentation fypo fix.
  - `1.0.3`: Documentation edits for journal article.
  - `1.0.2`: Minor documentation touch ups for pyopensci.
  - `1.0.1`: Minor documentation fix.
  - `1.0.0`: Release with pyopensci.
  - `0.0.9`: Fix with issue for certain import modalities and the `http` module.
  - `0.0.8`: New query syntax (builder / chaining) and units conversions.
  - `0.0.7`: Visual analytics tools.
```

### Comparing `afscgap-1.0.3/pyproject.toml` & `afscgap-1.0.4/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [project]
 name = "afscgap"
-version = "1.0.3"
+version = "1.0.4"
 authors = [
   { name="A Samuel Pottinger", email="sam.pottinger@berkeley.edu" },
 ]
 description = "Tools for interacting with the public bottom trawl surveys data from the NOAA AFSC GAP."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `afscgap-1.0.3/PKG-INFO` & `afscgap-1.0.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: afscgap
-Version: 1.0.3
+Version: 1.0.4
 Summary: Tools for interacting with the public bottom trawl surveys data from the NOAA AFSC GAP.
 Project-URL: Homepage, https://pyafscgap.org
 Project-URL: Documentation, https://pyafscgap.org/devdocs/afscgap.html
 Project-URL: Source, https://github.com/SchmidtDSE/afscgap
 Project-URL: Issue Tracker, https://github.com/SchmidtDSE/afscgap/issues
 Project-URL: Changelog, https://github.com/SchmidtDSE/afscgap#version-history
 Author-email: A Samuel Pottinger <sam.pottinger@berkeley.edu>
@@ -185,14 +185,15 @@
 
 <br>
 <br>
 
 ## Version history
 Annotated version history:
 
+ - `1.0.4`: Minor documentation fypo fix.
  - `1.0.3`: Documentation edits for journal article.
  - `1.0.2`: Minor documentation touch ups for pyopensci.
  - `1.0.1`: Minor documentation fix.
  - `1.0.0`: Release with pyopensci.
  - `0.0.9`: Fix with issue for certain import modalities and the `http` module.
  - `0.0.8`: New query syntax (builder / chaining) and units conversions.
  - `0.0.7`: Visual analytics tools.
```


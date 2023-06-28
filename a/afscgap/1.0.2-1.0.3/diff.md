# Comparing `tmp/afscgap-1.0.2.tar.gz` & `tmp/afscgap-1.0.3.tar.gz`

## Comparing `afscgap-1.0.2.tar` & `afscgap-1.0.3.tar`

### file list

```diff
@@ -1,41 +1,40 @@
--rw-r--r--   0        0        0       52 2020-02-02 00:00:00.000000 afscgap-1.0.2/.gitattributes
--rw-r--r--   0        0        0     1889 2020-02-02 00:00:00.000000 afscgap-1.0.2/.zenodo.json
--rw-r--r--   0        0        0      417 2020-02-02 00:00:00.000000 afscgap-1.0.2/CITATION.cff
--rw-r--r--   0        0        0     2780 2020-02-02 00:00:00.000000 afscgap-1.0.2/CONDUCT.md
--rw-r--r--   0        0        0     7583 2020-02-02 00:00:00.000000 afscgap-1.0.2/CONTRIBUTING.md
--rw-r--r--   0        0        0      463 2020-02-02 00:00:00.000000 afscgap-1.0.2/build_docs.sh
--rw-r--r--   0        0        0      653 2020-02-02 00:00:00.000000 afscgap-1.0.2/gruntfile.js
--rw-r--r--   0        0        0       37 2020-02-02 00:00:00.000000 afscgap-1.0.2/install_browser.sh
--rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 afscgap-1.0.2/mkdocs.yml
--rw-r--r--   0        0        0   178220 2020-02-02 00:00:00.000000 afscgap-1.0.2/package-lock.json
--rw-r--r--   0        0        0      141 2020-02-02 00:00:00.000000 afscgap-1.0.2/package.json
--rw-r--r--   0        0        0       64 2020-02-02 00:00:00.000000 afscgap-1.0.2/setup.cfg
--rw-r--r--   0        0        0      217 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/README.md
--rw-r--r--   0        0        0    58901 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/__init__.py
--rw-r--r--   0        0        0    42895 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/client.py
--rw-r--r--   0        0        0     9440 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/convert.py
--rw-r--r--   0        0        0     5132 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/cursor.py
--rw-r--r--   0        0        0     1110 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/http_util.py
--rw-r--r--   0        0        0    37009 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/inference.py
--rw-r--r--   0        0        0    37762 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/model.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/py.typed
--rw-r--r--   0        0        0     2914 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/query_util.py
--rw-r--r--   0        0        0      750 2020-02-02 00:00:00.000000 afscgap-1.0.2/afscgap/typesdef.py
--rw-r--r--   0        0        0     1451 2020-02-02 00:00:00.000000 afscgap-1.0.2/docs/building.md
--rw-r--r--   0        0        0     5761 2020-02-02 00:00:00.000000 afscgap-1.0.2/docs/inference.md
--rw-r--r--   0        0        0     3686 2020-02-02 00:00:00.000000 afscgap-1.0.2/docs/limitations.md
--rw-r--r--   0        0        0    12988 2020-02-02 00:00:00.000000 afscgap-1.0.2/docs/model.md
--rw-r--r--   0        0        0     3063 2020-02-02 00:00:00.000000 afscgap-1.0.2/docs/objectives.md
--rw-r--r--   0        0        0    10255 2020-02-02 00:00:00.000000 afscgap-1.0.2/docs/usage.md
--rw-r--r--   0        0        0      815 2020-02-02 00:00:00.000000 afscgap-1.0.2/paper/README.md
--rw-r--r--   0        0        0    13278 2020-02-02 00:00:00.000000 afscgap-1.0.2/paper/architecture.drawio
--rw-r--r--   0        0        0    87762 2020-02-02 00:00:00.000000 afscgap-1.0.2/paper/library.png
--rw-r--r--   0        0        0     5641 2020-02-02 00:00:00.000000 afscgap-1.0.2/paper/paper.bib
--rw-r--r--   0        0        0     7649 2020-02-02 00:00:00.000000 afscgap-1.0.2/paper/paper.md
--rw-r--r--   0        0        0      592 2020-02-02 00:00:00.000000 afscgap-1.0.2/paper/preview_paper.sh
--rw-r--r--   0        0        0   173860 2020-02-02 00:00:00.000000 afscgap-1.0.2/paper/viz.png
--rw-r--r--   0        0        0      295 2020-02-02 00:00:00.000000 afscgap-1.0.2/.gitignore
--rw-r--r--   0        0        0     1613 2020-02-02 00:00:00.000000 afscgap-1.0.2/LICENSE.md
--rw-r--r--   0        0        0    11415 2020-02-02 00:00:00.000000 afscgap-1.0.2/README.md
--rw-r--r--   0        0        0     1434 2020-02-02 00:00:00.000000 afscgap-1.0.2/pyproject.toml
--rw-r--r--   0        0        0    12884 2020-02-02 00:00:00.000000 afscgap-1.0.2/PKG-INFO
+-rw-r--r--   0        0        0       52 2020-02-02 00:00:00.000000 afscgap-1.0.3/.gitattributes
+-rw-r--r--   0        0        0     2071 2020-02-02 00:00:00.000000 afscgap-1.0.3/.zenodo.json
+-rw-r--r--   0        0        0      417 2020-02-02 00:00:00.000000 afscgap-1.0.3/CITATION.cff
+-rw-r--r--   0        0        0     2780 2020-02-02 00:00:00.000000 afscgap-1.0.3/CONDUCT.md
+-rw-r--r--   0        0        0     7583 2020-02-02 00:00:00.000000 afscgap-1.0.3/CONTRIBUTING.md
+-rw-r--r--   0        0        0      330 2020-02-02 00:00:00.000000 afscgap-1.0.3/build_docs.sh
+-rw-r--r--   0        0        0      653 2020-02-02 00:00:00.000000 afscgap-1.0.3/gruntfile.js
+-rw-r--r--   0        0        0       37 2020-02-02 00:00:00.000000 afscgap-1.0.3/install_browser.sh
+-rw-r--r--   0        0        0      294 2020-02-02 00:00:00.000000 afscgap-1.0.3/mkdocs.yml
+-rw-r--r--   0        0        0   178220 2020-02-02 00:00:00.000000 afscgap-1.0.3/package-lock.json
+-rw-r--r--   0        0        0      141 2020-02-02 00:00:00.000000 afscgap-1.0.3/package.json
+-rw-r--r--   0        0        0       64 2020-02-02 00:00:00.000000 afscgap-1.0.3/setup.cfg
+-rw-r--r--   0        0        0      217 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/README.md
+-rw-r--r--   0        0        0    58901 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/__init__.py
+-rw-r--r--   0        0        0    42895 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/client.py
+-rw-r--r--   0        0        0     9440 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/convert.py
+-rw-r--r--   0        0        0     5132 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/cursor.py
+-rw-r--r--   0        0        0     1110 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/http_util.py
+-rw-r--r--   0        0        0    37009 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/inference.py
+-rw-r--r--   0        0        0    37762 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/model.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/py.typed
+-rw-r--r--   0        0        0     2914 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/query_util.py
+-rw-r--r--   0        0        0      750 2020-02-02 00:00:00.000000 afscgap-1.0.3/afscgap/typesdef.py
+-rw-r--r--   0        0        0     1451 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/building.md
+-rw-r--r--   0        0        0     5761 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/inference.md
+-rw-r--r--   0        0        0     3686 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/limitations.md
+-rw-r--r--   0        0        0    12988 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/model.md
+-rw-r--r--   0        0        0     3063 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/objectives.md
+-rw-r--r--   0        0        0    10255 2020-02-02 00:00:00.000000 afscgap-1.0.3/docs/usage.md
+-rw-r--r--   0        0        0      508 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/README.md
+-rw-r--r--   0        0        0    13278 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/architecture.drawio
+-rw-r--r--   0        0        0    87762 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/library.png
+-rw-r--r--   0        0        0     5641 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/paper.bib
+-rw-r--r--   0        0        0     7744 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/paper.md
+-rw-r--r--   0        0        0   173860 2020-02-02 00:00:00.000000 afscgap-1.0.3/paper/viz.png
+-rw-r--r--   0        0        0      295 2020-02-02 00:00:00.000000 afscgap-1.0.3/.gitignore
+-rw-r--r--   0        0        0     1613 2020-02-02 00:00:00.000000 afscgap-1.0.3/LICENSE.md
+-rw-r--r--   0        0        0    11107 2020-02-02 00:00:00.000000 afscgap-1.0.3/README.md
+-rw-r--r--   0        0        0     1434 2020-02-02 00:00:00.000000 afscgap-1.0.3/pyproject.toml
+-rw-r--r--   0        0        0    12576 2020-02-02 00:00:00.000000 afscgap-1.0.3/PKG-INFO
```

### Comparing `afscgap-1.0.2/.zenodo.json` & `afscgap-1.0.3/.zenodo.json`

 * *Files 25% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9027777777777778%*

 * *Differences: {"'creators'": "{0: {'affiliation': 'University of California, Berkeley, California, United States "*

 * *               "of America'}, 1: {'affiliation': 'University of California, Berkeley, California, "*

 * *               "United States of America'}}",*

 * * "'license'": "'BSD-3-Clause'",*

 * * "'related_identifiers'": "{1: {'relation': 'isNewVersionOf'}}",*

 * * "'title'": "'Pyafscgap.org: Open source multi-modal Python-based tools for NOAA AFSC RACE GAP'"}*

```diff
@@ -12,44 +12,44 @@
             "name": "Zarpellon, Giulia",
             "orcid": "0000-0002-9122-4709",
             "type": "ProjectMember"
         }
     ],
     "creators": [
         {
-            "affiliation": "UC Berkeley",
+            "affiliation": "University of California, Berkeley, California, United States of America",
             "name": "A Samuel Pottinger"
         },
         {
-            "affiliation": "UC Berkeley",
+            "affiliation": "University of California, Berkeley, California, United States of America",
             "name": "Giulia Zarpellon"
         }
     ],
     "description": "<p>Python-based tool chain (&quot;Pyafscgap.org&quot;) for working with the public bottom trawl surveys data from the <a href=\"https://www.fisheries.noaa.gov/contact/groundfish-assessment-program\">NOAA AFSC GAP</a>. This provides information about where certain species were seen and when under what conditions, information useful for research in ocean health.</p>\n\n<p>See <a href=\"https://pyafscgap.org\">webpage</a>, <a href=\"https://github.com/SchmidtDSE/afscgap\">project Github</a>, and <a href=\"https://mybinder.org/v2/gh/SchmidtDSE/afscgap/main?urlpath=/tree/index.ipynb\">example notebook</a>.</p>",
     "keywords": [
         "ocean",
         "fish",
         "python",
         "NOAA",
         "AFSC",
         "GAP",
         "Alaska"
     ],
     "language": "eng",
-    "license": "other-open",
+    "license": "BSD-3-Clause",
     "publication_date": "2023-06-02",
     "related_identifiers": [
         {
             "identifier": "https://github.com/SchmidtDSE/afscgap/tree/1.0.2",
             "relation": "isSupplementTo",
             "scheme": "url"
         },
         {
             "identifier": "10.5281/zenodo.7991875",
-            "relation": "isVersionOf",
+            "relation": "isNewVersionOf",
             "scheme": "doi"
         }
     ],
-    "title": "SchmidtDSE/afscgap: 1.0.2",
+    "title": "Pyafscgap.org: Open source multi-modal Python-based tools for NOAA AFSC RACE GAP",
     "upload_type": "software",
     "version": "1.0.2"
 }
```

### Comparing `afscgap-1.0.2/CONDUCT.md` & `afscgap-1.0.3/CONDUCT.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/CONTRIBUTING.md` & `afscgap-1.0.3/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/gruntfile.js` & `afscgap-1.0.3/gruntfile.js`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/package-lock.json` & `afscgap-1.0.3/package-lock.json`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/afscgap/__init__.py` & `afscgap-1.0.3/afscgap/__init__.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/afscgap/client.py` & `afscgap-1.0.3/afscgap/client.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/afscgap/convert.py` & `afscgap-1.0.3/afscgap/convert.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/afscgap/cursor.py` & `afscgap-1.0.3/afscgap/cursor.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/afscgap/http_util.py` & `afscgap-1.0.3/afscgap/http_util.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/afscgap/inference.py` & `afscgap-1.0.3/afscgap/inference.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/afscgap/model.py` & `afscgap-1.0.3/afscgap/model.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/afscgap/query_util.py` & `afscgap-1.0.3/afscgap/query_util.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/afscgap/typesdef.py` & `afscgap-1.0.3/afscgap/typesdef.py`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/docs/building.md` & `afscgap-1.0.3/docs/building.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/docs/inference.md` & `afscgap-1.0.3/docs/inference.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/docs/limitations.md` & `afscgap-1.0.3/docs/limitations.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/docs/model.md` & `afscgap-1.0.3/docs/model.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/docs/objectives.md` & `afscgap-1.0.3/docs/objectives.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/docs/usage.md` & `afscgap-1.0.3/docs/usage.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/paper/architecture.drawio` & `afscgap-1.0.3/paper/architecture.drawio`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/paper/library.png` & `afscgap-1.0.3/paper/library.png`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/paper/paper.bib` & `afscgap-1.0.3/paper/paper.bib`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/paper/paper.md` & `afscgap-1.0.3/paper/paper.md`

 * *Files 9% similar despite different names*

```diff
@@ -21,56 +21,56 @@
         - ucberkeley
       correspondence: "yes"
       email: sam.pottinger@berkeley.edu
   - "Giulia Zarpellon":
       institute:
         - ucberkeley
 affiliations:
- - name: University of California, Berkeley
+ - name: University of California, Berkeley, California, United States of America
    index: 1
 institute:
-  - ucberkeley: University of California, Berkeley
+  - ucberkeley: University of California Berkeley, California, United States of America
 date: 2 June 2023
 bibliography: paper.bib
 ---
 
 # Summary
-The Groundfish Assessment Program within NOAA's Alaska Fisheries Science Center produces longitudinal catch data for the region [@afscgap]. Supporting ocean health research and fisheries management, these "hauls" report where marine species are found during bottom trawl surveys and in what quantities [@example]. Increasing data usability for communities of diverse programming experience, Pyafscgap.org offers not just friendlier REST API operation for this economically and scientifically important dataset but query language compliation, memory-efficient algorithms for "zero-catch" inference, and interactive visual analytics. Altogether, this research toolset supports investigatory tasks not easily executable using the API service alone and broadens access through game and information design.
+NOAA AFSC's Groundfish Assessment Program produces longitudinal catch data which support ocean health research and fisheries management [@afscgap]. These "hauls" report in what quantities and locations bottom trawl surveys find different marine species along with environmental conditions at the time and place of observation [@example]. Increasing usability for communities of diverse programming experience, Pyafscgap.org offers query language compilation, memory-efficient algorithms for "zero-catch" inference, and interactive visual analytics for these economically and scientifically important GAP datasets. Altogether, this research toolset supports investigatory tasks across survey programs' locations and broadens access through game and information design.
 
 # Statement of need
 Pyafscgap.org reduces barriers for use of NOAA AFSC RACE GAP^[Groundfish Assessment Program in the Resource Assessment and Conservation Engineering Division of the National Oceanic and Atmospheric Administration's Alaska Fisheries Science Center] data, offering:
 
  - Improved developer usability.
- - Memory-efficient algorithms for analysis requiring zero catch inference.
- - Tools for those with less developer experience.
+ - Memory-efficient algorithms for zero catch inference.
+ - Zero-code visualization tools.
 
-Altogether, these open source tools extend the dataset's reach and approachability.
+Altogether, these open source tools extend the reach and approachability of GAP's multiple survey programs to support analysis like longitudinal catch per unit effort (CPUE) in context of environmental changes [@notebook].
 
 ## Developer usability
-Working with these data requires knowledge of tools ouside the Python "standard toolset" like the closed-source Oracle REST Data Services (ORDS) [@ords]. The `afscgap` package offers easier access to the official REST service with automated pagination, ORDS compilation, and documented types. Together, these tools enable Python developers to use familiar patterns to interact with these data: type checking, standard documentation, and compatability with common Python data-related libraries.
+Working with these data requires knowledge of tools ouside the Python "standard toolset" like closed-source ORDS query language [@ords]. While the `afscgap` package offers easier access to the official REST service, it also crucially offers ORDS compilation, documented types, and lazy access to these large datasets. Together, these tools enable Python developers to efficiently use familiar patterns to interact with these data: type checking, standard documentation, and compatibility with common Python data-related libraries.
 
 ## Record inference
-The API struggles supporting some investigations as it provides "presence-only" data [@inport]. For example, the API may readily yield total mass of Pacific cod but not its geohash-aggregated catch per unit effort [@geohash].
+Surveys on their own within the API struggle supporting some investigations as they provide "presence-only" data [@inport]. For example, the API may readily yield total mass of Pacific cod but not its geohash-aggregated CPUE [@geohash].
 
 $$CPUE_{species} = \frac{m_{species}}{A_{swept}}$$
 
-Knowing CPUE (kg/ha) must also include "absence data" or hauls in which the speices was not recorded, this package can efficiently infer those hauls not easily returned from the API service [@notebook].
+Metrics like CPUE need "absence data" or hauls in which the species was not recorded. This package can efficiently infer those results [@notebook].
 
 ## Broad accessibility
-Though the `afscgap` Python package makes GAP catch data more accessible, the size and complexity of this dataset complicates comparative analysis between species, years, and/or geographic areas [@notebook]. Without deep developer experience, it may still be difficult to get started even with scientific background. To address a broader audience, this project offers visualization on top of `afscgap` with CSV and Python code export as a bridge to further analysis.
+Though the `afscgap` Python package makes GAP catch information more accessible, the data's size and complexity complicates comparative analysis between species, years, and/or geographic areas [@notebook]. Without deep developer experience, it may still be difficult to get started even with scientific background. To address a broader audience, this project offers visualization on top of `afscgap` with CSV and Python code export as a bridge to further analysis.
 
 # Functions
-This project improves accessibility of GAP catch data and offers approachable tools to kickstart analysis.
+This project improves accessibility of GAP data and offers approachable tools to kickstart analysis.
 
-## Lazy querying facade
+## Efficient facade
 The `afscgap` library manages significant complexity to offer a simple familiar interface to Python developers:
 
  - Lazy "generator iterables" increase accessibility by encapsulating logic for memory-efficient pagination and "data munging" behind Python-standard iterators [@lazy].
- - To support zero catch data, decorators adapt diverse structures to common interfaces, offering polymorphism [@decorators].
- - Offering a single object entry-point into the library, a "facade" frees users from needing deep understanding of the library's types, a goal furthered by compilation of "standard" Python types to Oracle REST Data Service queries [@facade].
+ - Decorators adapt diverse structures to common interfaces in zero catch data, offering polymorphism that helps to reduce the complexity of code using the library [@decorators].
+ - Providing a single object entry-point into the library, a "facade" frees users from needing deep understanding of the library's types and transparently compiles "standard" Python types to Oracle REST Data Service queries [@facade].
 
 ![Diagram of afscgap.\label{fig:library}](library.png)
 
 ## Zero catch inference
 "Zero catch" inference enables a broader range of analysis with the following algorithm:
 
  - Lazily paginate while records remain available from the API service.
@@ -79,35 +79,35 @@
  - Lazily generate inferred records after API exhaustion.
    - For each species observed in API results, check if it had a record for each haul in a hauls flat file [@flatfile].
    - For any hauls without the species, produce a record from the iterator.
 
 Note `afscgap` performs Python-emulation of ORDS filters on inferred records.
 
 ## Visualization
-This complex dataset requires technical sophistication to navigate and, to further increase accessibility, visualization tools help start temporal, spatial, and species comparisons with deep linking, coordinated highlighting, separated color channels, summary statistics, and side-by-side display [@few].
+These complex data require technical sophistication to navigate and, to increase accessibility, visualization tools help start temporal, spatial, and species comparisons with deep linking, coordinated highlighting, separated color channels, summary statistics, and side-by-side display [@few].
 
 ![Visualization screenshot.\label{fig:viz}](viz.png)
 
-To support learning this UI, an optional introduction sequence tutorializes a "real" analysis via Hayashida level design [@hayashida; @brown]:
+To support learning this UI, an optional introduction sequence tutorializes a "real" analysis via Hayashida design [@hayashida; @brown]:
 
  - **Introduction**: The tool shows information about Pacific cod with pre-filled controls used to achieve that analysis gradually fading in, asking the user for minor modifications.
  - **Development**: Using the mechanics introduced moments prior, the tool invites the user to change the analysis to compare different regions.
  - **Twist**: Enabling overlays on the same display, the user leverages mechanics they just exercised in a now more complex interface.
  - **Conclusion**: The visualization invites the user to demonstrate skills acquired in a new problem.
 
-Note that this visualization also serves as a starting point for continued analysis by generating either CSV or Python code to take work into other tools.
+This visualization also serves as a starting point for continued analysis by generating either CSV or Python code to take work into other tools.
 
 In addition to use in a graduate classroom setting, five individuals with relevant background offered feedback on this open source visualization with four aided by a think-aloud prompt^[Discussion limited to tool-specific needs assessment / quality improvement, collecting information about the tool and not individuals. IRB questionnaire on file finds "project does not constitute human subjects research" and review is not required.] [@thinkaloud].
 
 ## Limitations
 As further documented in the repository [@readme], these tools:
 
- - Run single-threaded and synchoronous.
- - Represents hauls as points not areas in visualization aggregation due to dataset limitation.
- - Must exclude any hauls also excluded by NOAA from their dataset.
+ - Run single-threaded and synchronous.
+ - Aggregate hauls as points in visualization due to data limitation.
+ - Ignore hauls if entirelly excluded by NOAA.
 
 # Acknowledgements
 Thanks to:
 
  - Runtime dependencies: ColorBrewer, D3, Flask, Geolib, Requests, Toolz, and Papa Parse [@colorbrewer; @d3; @flask; @geolib; @requests; @toolz; @papa].
  - Library advice: Carl Boettiger, Fernando Perez, and PyOpenSci reviewers.
  - Visualization advice: Magali de Bruyn, Brookie Guzder-Williams, Angela Hayes, David Joy, and Maya Weltman-Fahs.
```

### Comparing `afscgap-1.0.2/paper/viz.png` & `afscgap-1.0.3/paper/viz.png`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/LICENSE.md` & `afscgap-1.0.3/LICENSE.md`

 * *Files identical despite different names*

### Comparing `afscgap-1.0.2/README.md` & `afscgap-1.0.3/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -3,25 +3,25 @@
 |-------|--------|
 | Status | ![build workflow status](https://github.com/SchmidtDSE/afscgap/actions/workflows/build.yml/badge.svg?branch=main) ![docs workflow status](https://github.com/SchmidtDSE/afscgap/actions/workflows/docs.yml/badge.svg?branch=main) [![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) |
 | Usage | [![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-370/) [![Pypi Badge](https://img.shields.io/pypi/v/afscgap)](https://pypi.org/project/afscgap/) [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SchmidtDSE/afscgap/main?urlpath=/tree/index.ipynb) |
 | Publication | [![pyOpenSci](https://tinyurl.com/y22nb8up)](https://github.com/pyOpenSci/software-submission/issues/93) [![Open in Code Ocean](https://codeocean.com/codeocean-assets/badge/open-in-code-ocean.svg)](https://codeocean.com/capsule/4905407/tree/v2) [![DOI](https://zenodo.org/badge/603308264.svg)](https://zenodo.org/badge/latestdoi/603308264) |
 
 <br>
 
-Python-based tool chain ("Pyafscgap.org") for working with the public bottom trawl surveys data from the [NOAA AFSC GAP](https://www.fisheries.noaa.gov/contact/groundfish-assessment-program). This provides information about where certain species were seen and when under what conditions, information useful for research in ocean health.
+Python-based tool chain ("Pyafscgap.org") for working with the public bottom trawl data from the [NOAA AFSC GAP](https://www.fisheries.noaa.gov/contact/groundfish-assessment-program). This provides information from multiple survey programs about where certain species were seen and when under what conditions, information useful for research in ocean health.
 
 See [webpage](https://pyafscgap.org), [project Github](https://github.com/SchmidtDSE/afscgap), and [example notebook](https://mybinder.org/v2/gh/SchmidtDSE/afscgap/main?urlpath=/tree/index.ipynb).
 
 <br>
 <br>
 
 ## Quickstart
 Taking your first step is easy!
 
-**Explore the data in a UI:** To learn about the dataset, try out an in-browser visual analytics app at [https://app.pyafscgap.org](https://app.pyafscgap.org) without writing any code.
+**Explore the data in a UI:** To learn about the datasets, try out an in-browser visual analytics app at [https://app.pyafscgap.org](https://app.pyafscgap.org) without writing any code.
 
 **Try out a tutorial in your browser:** Learn from and modify an in-depth [tutorial notebook](https://mybinder.org/v2/gh/SchmidtDSE/afscgap/main?urlpath=/tree/index.ipynb) in a free hosted academic environment (all without installing any local software).
 
 **Jump into code:** Ready to build your own scripts? Here's an example querying for Pacific cod in the Gulf of Alaska for 2021:
 
 ```python
 import afscgap  # install with pip install afscgap
@@ -56,17 +56,17 @@
 <br>
 
 ## Purpose
 Unofficial Python-based tool set for interacting with [bottom trawl surveys](https://www.fisheries.noaa.gov/alaska/commercial-fishing/alaska-groundfish-bottom-trawl-survey-data) from the [Ground Fish Assessment Program (GAP)](https://www.fisheries.noaa.gov/contact/groundfish-assessment-program). It offers:
 
  - Pythonic access to the official [NOAA AFSC GAP API service](https://www.fisheries.noaa.gov/foss/f?p=215%3A28).
  - Tools for inference of the "negative" observations not provided by the API service.
- - Visualization tools for quickly exploring and creating comparisons within the dataset, including for audiences with limited programming experience.
+ - Visualization tools for quickly exploring and creating comparisons within the datasets, including for audiences with limited programming experience.
 
-Note that GAP is an excellent dataset produced by the [Resource Assessment and Conservation Engineering (RACE) Division](https://www.fisheries.noaa.gov/about/resource-assessment-and-conservation-engineering-division) of the [Alaska Fisheries Science Center (AFSC)](https://www.fisheries.noaa.gov/about/alaska-fisheries-science-center) as part of the National Oceanic and Atmospheric Administration's Fisheries organization ([NOAA Fisheries](https://www.fisheries.noaa.gov/)).
+Note that GAP are an excellent collection of datasets produced by the [Resource Assessment and Conservation Engineering (RACE) Division](https://www.fisheries.noaa.gov/about/resource-assessment-and-conservation-engineering-division) of the [Alaska Fisheries Science Center (AFSC)](https://www.fisheries.noaa.gov/about/alaska-fisheries-science-center) as part of the National Oceanic and Atmospheric Administration's Fisheries organization ([NOAA Fisheries](https://www.fisheries.noaa.gov/)).
 
 Please see our [objectives documentation](https://pyafscgap.org/docs/objectives/) for additional information about the purpose, developer needs addressed, and goals of the project.
 
 <br>
 <br>
 
 ## Usage
@@ -133,16 +133,14 @@
 
 In addition to Github-provided [Github Actions](https://docs.github.com/en/actions), our build and documentation systems also use the following but are not distributed with or linked to the project itself:
 
  - [mkdocs](https://www.mkdocs.org) under the [BSD License](https://github.com/mkdocs/mkdocs/blob/master/LICENSE).
  - [mkdocs-windmill](https://github.com/gristlabs/mkdocs-windmill) under the [MIT License](https://github.com/gristlabs/mkdocs-windmill/blob/master/LICENSE).
  - [mypy](https://github.com/python/mypy) under the [MIT License](https://github.com/python/mypy/blob/master/LICENSE) from Jukka Lehtosalo, Dropbox, and other contributors.
  - [nose2](https://docs.nose2.io/en/latest/index.html) under a [BSD license](https://github.com/nose-devs/nose2/blob/main/license.txt) from Jason Pellerin and other contributors.
- - [pandoc/luafilters](https://github.com/pandoc/lua-filters) by pandoc Lua filters contributors under the [MIT License](https://github.com/pandoc/lua-filters/blob/master/LICENSE)
- - [pandoc](https://pandoc.org/) (via call to OS package through shell script) by John MacFarlane, Albert Krewinkel, Jesse Rosenthal, and other contributors under the [GPL License](https://github.com/jgm/pandoc#license).
  - [pdoc](https://github.com/mitmproxy/pdoc) under the [Unlicense license](https://github.com/mitmproxy/pdoc/blob/main/LICENSE) from [Andrew Gallant](https://github.com/BurntSushi) and [Maximilian Hils](https://github.com/mhils).
  - [pycodestyle](https://pycodestyle.pycqa.org/en/latest/) under the [Expat License](https://github.com/PyCQA/pycodestyle/blob/main/LICENSE) from Johann C. Rocholl, Florent Xicluna, and Ian Lee.
  - [pyflakes](https://github.com/PyCQA/pyflakes) under the [MIT License](https://github.com/PyCQA/pyflakes/blob/main/LICENSE) from Divmod, Florent Xicluna, and other contributors.
  - [sftp-action](https://github.com/Creepios/sftp-action) under the [MIT License](https://github.com/Creepios/sftp-action/blob/master/LICENSE) from Niklas Creepios.
  - [ssh-action](https://github.com/appleboy/ssh-action) under the [MIT License](https://github.com/appleboy/ssh-action/blob/master/LICENSE) from Bo-Yi Wu.
 
 Next, the visualization tool has additional dependencies as documented in the [visualization readme](https://github.com/SchmidtDSE/afscgap/blob/main/afscgapviz/README.md).
@@ -153,14 +151,15 @@
 
 <br>
 <br>
 
 ## Version history
 Annotated version history:
 
+ - `1.0.3`: Documentation edits for journal article.
  - `1.0.2`: Minor documentation touch ups for pyopensci.
  - `1.0.1`: Minor documentation fix.
  - `1.0.0`: Release with pyopensci.
  - `0.0.9`: Fix with issue for certain import modalities and the `http` module.
  - `0.0.8`: New query syntax (builder / chaining) and units conversions.
  - `0.0.7`: Visual analytics tools.
  - `0.0.6`: Performance and size improvements.
```

### Comparing `afscgap-1.0.2/pyproject.toml` & `afscgap-1.0.3/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [project]
 name = "afscgap"
-version = "1.0.2"
+version = "1.0.3"
 authors = [
   { name="A Samuel Pottinger", email="sam.pottinger@berkeley.edu" },
 ]
 description = "Tools for interacting with the public bottom trawl surveys data from the NOAA AFSC GAP."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
```

### Comparing `afscgap-1.0.2/PKG-INFO` & `afscgap-1.0.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: afscgap
-Version: 1.0.2
+Version: 1.0.3
 Summary: Tools for interacting with the public bottom trawl surveys data from the NOAA AFSC GAP.
 Project-URL: Homepage, https://pyafscgap.org
 Project-URL: Documentation, https://pyafscgap.org/devdocs/afscgap.html
 Project-URL: Source, https://github.com/SchmidtDSE/afscgap
 Project-URL: Issue Tracker, https://github.com/SchmidtDSE/afscgap/issues
 Project-URL: Changelog, https://github.com/SchmidtDSE/afscgap#version-history
 Author-email: A Samuel Pottinger <sam.pottinger@berkeley.edu>
@@ -37,25 +37,25 @@
 |-------|--------|
 | Status | ![build workflow status](https://github.com/SchmidtDSE/afscgap/actions/workflows/build.yml/badge.svg?branch=main) ![docs workflow status](https://github.com/SchmidtDSE/afscgap/actions/workflows/docs.yml/badge.svg?branch=main) [![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active) |
 | Usage | [![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-370/) [![Pypi Badge](https://img.shields.io/pypi/v/afscgap)](https://pypi.org/project/afscgap/) [![License](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SchmidtDSE/afscgap/main?urlpath=/tree/index.ipynb) |
 | Publication | [![pyOpenSci](https://tinyurl.com/y22nb8up)](https://github.com/pyOpenSci/software-submission/issues/93) [![Open in Code Ocean](https://codeocean.com/codeocean-assets/badge/open-in-code-ocean.svg)](https://codeocean.com/capsule/4905407/tree/v2) [![DOI](https://zenodo.org/badge/603308264.svg)](https://zenodo.org/badge/latestdoi/603308264) |
 
 <br>
 
-Python-based tool chain ("Pyafscgap.org") for working with the public bottom trawl surveys data from the [NOAA AFSC GAP](https://www.fisheries.noaa.gov/contact/groundfish-assessment-program). This provides information about where certain species were seen and when under what conditions, information useful for research in ocean health.
+Python-based tool chain ("Pyafscgap.org") for working with the public bottom trawl data from the [NOAA AFSC GAP](https://www.fisheries.noaa.gov/contact/groundfish-assessment-program). This provides information from multiple survey programs about where certain species were seen and when under what conditions, information useful for research in ocean health.
 
 See [webpage](https://pyafscgap.org), [project Github](https://github.com/SchmidtDSE/afscgap), and [example notebook](https://mybinder.org/v2/gh/SchmidtDSE/afscgap/main?urlpath=/tree/index.ipynb).
 
 <br>
 <br>
 
 ## Quickstart
 Taking your first step is easy!
 
-**Explore the data in a UI:** To learn about the dataset, try out an in-browser visual analytics app at [https://app.pyafscgap.org](https://app.pyafscgap.org) without writing any code.
+**Explore the data in a UI:** To learn about the datasets, try out an in-browser visual analytics app at [https://app.pyafscgap.org](https://app.pyafscgap.org) without writing any code.
 
 **Try out a tutorial in your browser:** Learn from and modify an in-depth [tutorial notebook](https://mybinder.org/v2/gh/SchmidtDSE/afscgap/main?urlpath=/tree/index.ipynb) in a free hosted academic environment (all without installing any local software).
 
 **Jump into code:** Ready to build your own scripts? Here's an example querying for Pacific cod in the Gulf of Alaska for 2021:
 
 ```python
 import afscgap  # install with pip install afscgap
@@ -90,17 +90,17 @@
 <br>
 
 ## Purpose
 Unofficial Python-based tool set for interacting with [bottom trawl surveys](https://www.fisheries.noaa.gov/alaska/commercial-fishing/alaska-groundfish-bottom-trawl-survey-data) from the [Ground Fish Assessment Program (GAP)](https://www.fisheries.noaa.gov/contact/groundfish-assessment-program). It offers:
 
  - Pythonic access to the official [NOAA AFSC GAP API service](https://www.fisheries.noaa.gov/foss/f?p=215%3A28).
  - Tools for inference of the "negative" observations not provided by the API service.
- - Visualization tools for quickly exploring and creating comparisons within the dataset, including for audiences with limited programming experience.
+ - Visualization tools for quickly exploring and creating comparisons within the datasets, including for audiences with limited programming experience.
 
-Note that GAP is an excellent dataset produced by the [Resource Assessment and Conservation Engineering (RACE) Division](https://www.fisheries.noaa.gov/about/resource-assessment-and-conservation-engineering-division) of the [Alaska Fisheries Science Center (AFSC)](https://www.fisheries.noaa.gov/about/alaska-fisheries-science-center) as part of the National Oceanic and Atmospheric Administration's Fisheries organization ([NOAA Fisheries](https://www.fisheries.noaa.gov/)).
+Note that GAP are an excellent collection of datasets produced by the [Resource Assessment and Conservation Engineering (RACE) Division](https://www.fisheries.noaa.gov/about/resource-assessment-and-conservation-engineering-division) of the [Alaska Fisheries Science Center (AFSC)](https://www.fisheries.noaa.gov/about/alaska-fisheries-science-center) as part of the National Oceanic and Atmospheric Administration's Fisheries organization ([NOAA Fisheries](https://www.fisheries.noaa.gov/)).
 
 Please see our [objectives documentation](https://pyafscgap.org/docs/objectives/) for additional information about the purpose, developer needs addressed, and goals of the project.
 
 <br>
 <br>
 
 ## Usage
@@ -167,16 +167,14 @@
 
 In addition to Github-provided [Github Actions](https://docs.github.com/en/actions), our build and documentation systems also use the following but are not distributed with or linked to the project itself:
 
  - [mkdocs](https://www.mkdocs.org) under the [BSD License](https://github.com/mkdocs/mkdocs/blob/master/LICENSE).
  - [mkdocs-windmill](https://github.com/gristlabs/mkdocs-windmill) under the [MIT License](https://github.com/gristlabs/mkdocs-windmill/blob/master/LICENSE).
  - [mypy](https://github.com/python/mypy) under the [MIT License](https://github.com/python/mypy/blob/master/LICENSE) from Jukka Lehtosalo, Dropbox, and other contributors.
  - [nose2](https://docs.nose2.io/en/latest/index.html) under a [BSD license](https://github.com/nose-devs/nose2/blob/main/license.txt) from Jason Pellerin and other contributors.
- - [pandoc/luafilters](https://github.com/pandoc/lua-filters) by pandoc Lua filters contributors under the [MIT License](https://github.com/pandoc/lua-filters/blob/master/LICENSE)
- - [pandoc](https://pandoc.org/) (via call to OS package through shell script) by John MacFarlane, Albert Krewinkel, Jesse Rosenthal, and other contributors under the [GPL License](https://github.com/jgm/pandoc#license).
  - [pdoc](https://github.com/mitmproxy/pdoc) under the [Unlicense license](https://github.com/mitmproxy/pdoc/blob/main/LICENSE) from [Andrew Gallant](https://github.com/BurntSushi) and [Maximilian Hils](https://github.com/mhils).
  - [pycodestyle](https://pycodestyle.pycqa.org/en/latest/) under the [Expat License](https://github.com/PyCQA/pycodestyle/blob/main/LICENSE) from Johann C. Rocholl, Florent Xicluna, and Ian Lee.
  - [pyflakes](https://github.com/PyCQA/pyflakes) under the [MIT License](https://github.com/PyCQA/pyflakes/blob/main/LICENSE) from Divmod, Florent Xicluna, and other contributors.
  - [sftp-action](https://github.com/Creepios/sftp-action) under the [MIT License](https://github.com/Creepios/sftp-action/blob/master/LICENSE) from Niklas Creepios.
  - [ssh-action](https://github.com/appleboy/ssh-action) under the [MIT License](https://github.com/appleboy/ssh-action/blob/master/LICENSE) from Bo-Yi Wu.
 
 Next, the visualization tool has additional dependencies as documented in the [visualization readme](https://github.com/SchmidtDSE/afscgap/blob/main/afscgapviz/README.md).
@@ -187,14 +185,15 @@
 
 <br>
 <br>
 
 ## Version history
 Annotated version history:
 
+ - `1.0.3`: Documentation edits for journal article.
  - `1.0.2`: Minor documentation touch ups for pyopensci.
  - `1.0.1`: Minor documentation fix.
  - `1.0.0`: Release with pyopensci.
  - `0.0.9`: Fix with issue for certain import modalities and the `http` module.
  - `0.0.8`: New query syntax (builder / chaining) and units conversions.
  - `0.0.7`: Visual analytics tools.
  - `0.0.6`: Performance and size improvements.
```


# Comparing `tmp/osmnx-1.4.0.tar.gz` & `tmp/osmnx-1.5.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "osmnx-1.4.0.tar", last modified: Mon Jun 12 04:16:56 2023, max compression
+gzip compressed data, last modified: Sun Feb  2 00:00:00 2020, max compression
```

## Comparing `osmnx-1.4.0.tar` & `osmnx-1.5.0.tar`

### file list

```diff
@@ -1,43 +1,75 @@
-drwxr-xr-x   0 geoff      (501) staff       (20)        0 2023-06-12 04:16:56.355613 osmnx-1.4.0/
--rw-r--r--   0 geoff      (501) staff       (20)    20162 2023-06-12 04:14:56.000000 osmnx-1.4.0/CHANGELOG.md
--rw-r--r--   0 geoff      (501) staff       (20)     1111 2022-12-22 03:13:01.000000 osmnx-1.4.0/LICENSE.txt
--rw-r--r--   0 geoff      (501) staff       (20)       45 2022-12-14 16:25:06.000000 osmnx-1.4.0/MANIFEST.in
--rw-r--r--   0 geoff      (501) staff       (20)     2400 2023-06-12 04:16:56.355682 osmnx-1.4.0/PKG-INFO
--rw-r--r--   0 geoff      (501) staff       (20)     4477 2023-06-12 04:14:56.000000 osmnx-1.4.0/README.md
-drwxr-xr-x   0 geoff      (501) staff       (20)        0 2023-06-12 04:16:56.354583 osmnx-1.4.0/osmnx/
--rw-r--r--   0 geoff      (501) staff       (20)       73 2022-09-03 08:24:38.000000 osmnx-1.4.0/osmnx/__init__.py
--rw-r--r--   0 geoff      (501) staff       (20)     1990 2023-05-26 21:21:17.000000 osmnx-1.4.0/osmnx/_api.py
--rw-r--r--   0 geoff      (501) staff       (20)      505 2022-12-17 00:29:35.000000 osmnx-1.4.0/osmnx/_errors.py
--rw-r--r--   0 geoff      (501) staff       (20)     1758 2022-12-17 00:29:35.000000 osmnx-1.4.0/osmnx/_polygon_features.py
--rw-r--r--   0 geoff      (501) staff       (20)       52 2023-06-12 04:14:56.000000 osmnx-1.4.0/osmnx/_version.py
--rw-r--r--   0 geoff      (501) staff       (20)    10201 2023-06-07 21:57:18.000000 osmnx-1.4.0/osmnx/bearing.py
--rw-r--r--   0 geoff      (501) staff       (20)    18742 2023-06-07 21:57:18.000000 osmnx-1.4.0/osmnx/distance.py
--rw-r--r--   0 geoff      (501) staff       (20)    29369 2023-05-22 03:49:01.000000 osmnx-1.4.0/osmnx/downloader.py
--rw-r--r--   0 geoff      (501) staff       (20)     9582 2023-06-07 21:57:18.000000 osmnx-1.4.0/osmnx/elevation.py
--rw-r--r--   0 geoff      (501) staff       (20)     6811 2023-05-29 21:58:27.000000 osmnx-1.4.0/osmnx/folium.py
--rw-r--r--   0 geoff      (501) staff       (20)     8401 2023-06-07 16:58:51.000000 osmnx-1.4.0/osmnx/geocoder.py
--rw-r--r--   0 geoff      (501) staff       (20)    39543 2023-06-07 16:58:51.000000 osmnx-1.4.0/osmnx/geometries.py
--rw-r--r--   0 geoff      (501) staff       (20)    29141 2023-06-03 07:30:43.000000 osmnx-1.4.0/osmnx/graph.py
--rw-r--r--   0 geoff      (501) staff       (20)    14243 2023-05-29 21:58:27.000000 osmnx-1.4.0/osmnx/io.py
--rw-r--r--   0 geoff      (501) staff       (20)    15202 2023-06-03 07:30:43.000000 osmnx-1.4.0/osmnx/osm_xml.py
--rw-r--r--   0 geoff      (501) staff       (20)    31933 2023-06-07 16:17:03.000000 osmnx-1.4.0/osmnx/plot.py
--rw-r--r--   0 geoff      (501) staff       (20)     6384 2023-06-07 17:42:53.000000 osmnx-1.4.0/osmnx/projection.py
--rw-r--r--   0 geoff      (501) staff       (20)     8038 2023-05-26 21:21:17.000000 osmnx-1.4.0/osmnx/settings.py
--rw-r--r--   0 geoff      (501) staff       (20)    25685 2023-03-20 17:40:38.000000 osmnx-1.4.0/osmnx/simplification.py
--rw-r--r--   0 geoff      (501) staff       (20)     9554 2023-06-07 21:57:18.000000 osmnx-1.4.0/osmnx/speed.py
--rw-r--r--   0 geoff      (501) staff       (20)    12691 2022-12-22 03:13:01.000000 osmnx-1.4.0/osmnx/stats.py
--rw-r--r--   0 geoff      (501) staff       (20)     6740 2022-12-17 00:29:36.000000 osmnx-1.4.0/osmnx/truncate.py
--rw-r--r--   0 geoff      (501) staff       (20)    10548 2023-05-29 21:58:27.000000 osmnx-1.4.0/osmnx/utils.py
--rw-r--r--   0 geoff      (501) staff       (20)    16281 2023-06-07 21:57:18.000000 osmnx-1.4.0/osmnx/utils_geo.py
--rw-r--r--   0 geoff      (501) staff       (20)    18237 2023-05-29 21:58:27.000000 osmnx-1.4.0/osmnx/utils_graph.py
-drwxr-xr-x   0 geoff      (501) staff       (20)        0 2023-06-12 04:16:56.355327 osmnx-1.4.0/osmnx.egg-info/
--rw-r--r--   0 geoff      (501) staff       (20)     2400 2023-06-12 04:16:56.000000 osmnx-1.4.0/osmnx.egg-info/PKG-INFO
--rw-r--r--   0 geoff      (501) staff       (20)      691 2023-06-12 04:16:56.000000 osmnx-1.4.0/osmnx.egg-info/SOURCES.txt
--rw-r--r--   0 geoff      (501) staff       (20)        1 2023-06-12 04:16:56.000000 osmnx-1.4.0/osmnx.egg-info/dependency_links.txt
--rw-r--r--   0 geoff      (501) staff       (20)      241 2023-06-12 04:16:56.000000 osmnx-1.4.0/osmnx.egg-info/requires.txt
--rw-r--r--   0 geoff      (501) staff       (20)        6 2023-06-12 04:16:56.000000 osmnx-1.4.0/osmnx.egg-info/top_level.txt
--rw-r--r--   0 geoff      (501) staff       (20)       82 2023-06-12 04:14:56.000000 osmnx-1.4.0/requirements.txt
--rw-r--r--   0 geoff      (501) staff       (20)      405 2023-06-12 04:16:56.356003 osmnx-1.4.0/setup.cfg
--rw-r--r--   0 geoff      (501) staff       (20)     3143 2023-06-12 04:14:56.000000 osmnx-1.4.0/setup.py
-drwxr-xr-x   0 geoff      (501) staff       (20)        0 2023-06-12 04:16:56.355461 osmnx-1.4.0/tests/
--rwxr-xr-x   0 geoff      (501) staff       (20)    20890 2023-06-07 21:57:18.000000 osmnx-1.4.0/tests/test_osmnx.py
+-rw-r--r--   0        0        0      897 2020-02-02 00:00:00.000000 osmnx-1.5.0/.pre-commit-config.yaml
+-rw-r--r--   0        0        0    20892 2020-02-02 00:00:00.000000 osmnx-1.5.0/CHANGELOG.md
+-rw-r--r--   0        0        0     2709 2020-02-02 00:00:00.000000 osmnx-1.5.0/CONTRIBUTING.md
+-rw-r--r--   0        0        0       20 2020-02-02 00:00:00.000000 osmnx-1.5.0/MANIFEST.in
+-rw-r--r--   0        0        0      396 2020-02-02 00:00:00.000000 osmnx-1.5.0/.github/pull_request_template.md
+-rw-r--r--   0        0        0     2707 2020-02-02 00:00:00.000000 osmnx-1.5.0/.github/ISSUE_TEMPLATE/bug_report.md
+-rw-r--r--   0        0        0       28 2020-02-02 00:00:00.000000 osmnx-1.5.0/.github/ISSUE_TEMPLATE/config.yml
+-rw-r--r--   0        0        0     1861 2020-02-02 00:00:00.000000 osmnx-1.5.0/.github/ISSUE_TEMPLATE/feature_request.md
+-rw-r--r--   0        0        0     1368 2020-02-02 00:00:00.000000 osmnx-1.5.0/.github/workflows/ci.yml
+-rw-r--r--   0        0        0     1107 2020-02-02 00:00:00.000000 osmnx-1.5.0/.github/workflows/test-minimal.yml
+-rw-r--r--   0        0        0      291 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/.readthedocs.yaml
+-rw-r--r--   0        0        0      634 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/Makefile
+-rw-r--r--   0        0        0     1690 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/conf.py
+-rw-r--r--   0        0        0     2751 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/further-reading.rst
+-rw-r--r--   0        0        0     9548 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/getting-started.rst
+-rw-r--r--   0        0        0     2193 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/index.rst
+-rw-r--r--   0        0        0     1440 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/installation.rst
+-rw-r--r--   0        0        0     3261 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/internals-reference.rst
+-rw-r--r--   0        0        0      800 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/make.bat
+-rw-r--r--   0        0        0       66 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/requirements.txt
+-rw-r--r--   0        0        0     2241 2020-02-02 00:00:00.000000 osmnx-1.5.0/docs/user-reference.rst
+-rw-r--r--   0        0        0     1570 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/docker/Dockerfile
+-rw-r--r--   0        0        0      781 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/docker/docker-build-single_platform.sh
+-rw-r--r--   0        0        0     1462 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/docker/docker-build.sh
+-rw-r--r--   0        0        0    13614 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/docker/environment.yml
+-rw-r--r--   0        0        0       84 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/docker/overrides.json
+-rw-r--r--   0        0        0      480 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/docker/readme.md
+-rw-r--r--   0        0        0      326 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/docker/requirements.txt
+-rw-r--r--   0        0        0      683 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/linux/create-environment.sh
+-rw-r--r--   0        0        0    12198 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/linux/environment.yml
+-rw-r--r--   0        0        0      738 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/windows/create-environment.bat
+-rw-r--r--   0        0        0    11551 2020-02-02 00:00:00.000000 osmnx-1.5.0/environments/windows/environment.yml
+-rw-r--r--   0        0        0       73 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/__init__.py
+-rw-r--r--   0        0        0     2237 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/_api.py
+-rw-r--r--   0        0        0    29561 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/_downloader.py
+-rw-r--r--   0        0        0      545 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/_errors.py
+-rw-r--r--   0        0        0       64 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/_version.py
+-rw-r--r--   0        0        0    10201 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/bearing.py
+-rw-r--r--   0        0        0    18224 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/distance.py
+-rw-r--r--   0        0        0     9638 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/elevation.py
+-rw-r--r--   0        0        0    41870 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/features.py
+-rw-r--r--   0        0        0     6801 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/folium.py
+-rw-r--r--   0        0        0     8904 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/geocoder.py
+-rw-r--r--   0        0        0     4959 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/geometries.py
+-rw-r--r--   0        0        0    29480 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/graph.py
+-rw-r--r--   0        0        0    18096 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/io.py
+-rw-r--r--   0        0        0    18149 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/osm_xml.py
+-rw-r--r--   0        0        0    31934 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/plot.py
+-rw-r--r--   0        0        0     6400 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/projection.py
+-rw-r--r--   0        0        0     8038 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/settings.py
+-rw-r--r--   0        0        0    25680 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/simplification.py
+-rw-r--r--   0        0        0     9554 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/speed.py
+-rw-r--r--   0        0        0    12691 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/stats.py
+-rw-r--r--   0        0        0     6740 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/truncate.py
+-rw-r--r--   0        0        0    10548 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/utils.py
+-rw-r--r--   0        0        0    16281 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/utils_geo.py
+-rw-r--r--   0        0        0    18217 2020-02-02 00:00:00.000000 osmnx-1.5.0/osmnx/utils_graph.py
+-rw-r--r--   0        0        0     1857 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/README.md
+-rw-r--r--   0        0        0       44 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/format.sh
+-rw-r--r--   0        0        0       57 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/git_repack.sh
+-rw-r--r--   0        0        0      702 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/lint_test.sh
+-rw-r--r--   0        0        0     1742 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/packaging.sh
+-rwxr-xr-x   0        0        0    21856 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/test_osmnx.py
+-rw-r--r--   0        0        0      373 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/environments/env-ci.yml
+-rw-r--r--   0        0        0      839 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/environments/env-test-minimal.yml
+-rw-r--r--   0        0        0    11717 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/input_data/West-Oakland.osm.bz2
+-rw-r--r--   0        0        0     2161 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/input_data/elevation1.tif
+-rw-r--r--   0        0        0     2087 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/input_data/elevation2.tif
+-rw-r--r--   0        0        0    40557 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/input_data/planet_10.068,48.135_10.071,48.137.osm
+-rw-r--r--   0        0        0     1490 2020-02-02 00:00:00.000000 osmnx-1.5.0/tests/input_data/short.graphml
+-rw-r--r--   0        0        0     3134 2020-02-02 00:00:00.000000 osmnx-1.5.0/.gitignore
+-rw-r--r--   0        0        0     1111 2020-02-02 00:00:00.000000 osmnx-1.5.0/LICENSE.txt
+-rw-r--r--   0        0        0     2577 2020-02-02 00:00:00.000000 osmnx-1.5.0/README.md
+-rw-r--r--   0        0        0     2255 2020-02-02 00:00:00.000000 osmnx-1.5.0/pyproject.toml
+-rw-r--r--   0        0        0     4503 2020-02-02 00:00:00.000000 osmnx-1.5.0/PKG-INFO
```

### Comparing `osmnx-1.4.0/CHANGELOG.md` & `osmnx-1.5.0/CHANGELOG.md`

 * *Files 2% similar despite different names*

```diff
@@ -1,13 +1,27 @@
 # Change log
 
-## TBD
+## Unreleased
 
   - adopt NEP 29 policy for minimum required Python and NumPy versions
 
+## 1.5.0 (2023-06-28)
+
+  - fix bug in save_graph_xml due to roundabout ways
+  - fix GeoPandas future warning
+  - make API key properly optional in elevation.add_node_elevations_google function
+  - rename geometries module as features module and deprecate geometries module
+  - remove private \_polygon_features module and move its data to features module
+  - make the internal downloader module private
+  - deprecate interpolate parameter in distance.nearest_edges function
+  - move save_graph_xml function to io module with deprecation warning in osm_xml module
+  - migrate from setup.py, setup.cfg, and requirements.txt to pyproject.toml
+  - pin optional dependencies to minimum required versions
+  - expand and reorganize the documentation
+
 ## 1.4.0 (2023-06-11)
 
   - verify edge weight attribute values before solving shortest paths
   - provide consistent error when no data elements are returned from Overpass
   - add route_to_gdf function to utils_graph module to return a GeoDataFrame of the edges in a path
   - deprecate the get_route_edge_attributes function in favor of the new route_to_gdf function
   - deprecate folium module in favor of using geopandas.GeoDataFrame.explore directly
@@ -15,22 +29,22 @@
   - deprecate utils_geo.round_geometry_coords function
   - move plot_orientation function from bearing module to plot module
   - make matplotlib an optional dependency required only for the plot module
   - drop pyproj package dependency
 
 ## 1.3.1.post0 (2023-05-26)
 
-  - add Python 3.8 compatibility back for one final release
+  - restore Python 3.8 compatibility
 
 ## 1.3.1 (2023-05-24)
 
   - improve DNS resolution when using proxies or on networks blocking DNS-over-HTTPS
   - improve processing of per-lane values when adding edge speeds
   - improve file writing in save_graph_xml function
-  - ensure node coordinates are non-null and covertible to float in the add_edge_lengths function
+  - ensure node coordinates are non-null and convertible to float in the add_edge_lengths function
   - ignore ways tagged highway=no or highway=razed in built-in filters
   - do not assume an edge with key=0 exists between each node pair when simplifying graph
   - drop dateutil package dependency
 
 ## 1.3.0 (2023-01-01)
 
   - fully support Shapely 2.0 and drop support for Shapely 1.x
@@ -136,15 +150,15 @@
   - make graph_to_gdfs multi-index the edges GeoDataFrame by u, v, key
   - refactor consolidate_intersections function for better speed and efficiency
   - refactor count_streets_per_node function for better speed and efficiency
   - refactor folium module for better speed and efficiency
   - refactor get_undirected functionality for better speed and efficiency
   - extract all private/internal .osm XML functionality into new osm_xml module
   - deprecate io.save_graph_xml with warning (function moved to osm_xml module)
-  - remove internal _is_simplified function
+  - remove internal \_is_simplified function
   - remove deprecated pois module
   - remove deprecated footprints module
   - remove deprecated utils_graph.induce_subgraph function
   - remove deprecated node_type parameter from io.load_graphml function
 
 ## 0.16.2 (2020-11-17)
 
@@ -163,15 +177,15 @@
   - fix response caching to save only when status code is 200
   - fix elevation module's grade absolute value calculation when grade is null
   - move shortest path functions from utils_graph module to distance module
 
 ## 0.16.0 (2020-09-07)
 
   - new geometries module for creating GeoDataFrames from tag/value queries
-  - deprecate old pois and fooptrints modules (replaced by geometries module)
+  - deprecate old pois and footprints modules (replaced by geometries module)
   - auto-select first Polygon/MultiPolygon when geocoding with which_result=None
   - new k_shortest_paths function to solve *k* shortest paths from origin to destination
   - new shortest_path convenience function
   - new get_digraph function to correctly convert MultiDiGraph to DiGraph
   - miscellaneous performance improvements and optimizations
   - deprecate induce_subgraph function
   - remove deprecated boundaries module (replaced by geocoder module in v0.15.0)
```

### Comparing `osmnx-1.4.0/LICENSE.txt` & `osmnx-1.5.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `osmnx-1.4.0/osmnx/_api.py` & `osmnx-1.5.0/osmnx/_api.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,18 +1,24 @@
-"""Expose most common parts of public API directly in `osmnx.` namespace."""
+"""Expose most common parts of public API directly in package namespace."""
 
 from .bearing import add_edge_bearings
 from .bearing import orientation_entropy
 from .distance import k_shortest_paths
 from .distance import nearest_edges
 from .distance import nearest_nodes
 from .distance import shortest_path
 from .elevation import add_edge_grades
 from .elevation import add_node_elevations_google
 from .elevation import add_node_elevations_raster
+from .features import features_from_address
+from .features import features_from_bbox
+from .features import features_from_place
+from .features import features_from_point
+from .features import features_from_polygon
+from .features import features_from_xml
 from .folium import plot_graph_folium
 from .folium import plot_route_folium
 from .geocoder import geocode
 from .geocoder import geocode_to_gdf
 from .geometries import geometries_from_address
 from .geometries import geometries_from_bbox
 from .geometries import geometries_from_place
@@ -24,16 +30,16 @@
 from .graph import graph_from_place
 from .graph import graph_from_point
 from .graph import graph_from_polygon
 from .graph import graph_from_xml
 from .io import load_graphml
 from .io import save_graph_geopackage
 from .io import save_graph_shapefile
+from .io import save_graph_xml
 from .io import save_graphml
-from .osm_xml import save_graph_xml
 from .plot import plot_figure_ground
 from .plot import plot_footprints
 from .plot import plot_graph
 from .plot import plot_graph_route
 from .plot import plot_graph_routes
 from .plot import plot_orientation
 from .projection import project_gdf
```

### Comparing `osmnx-1.4.0/osmnx/bearing.py` & `osmnx-1.5.0/osmnx/bearing.py`

 * *Files identical despite different names*

### Comparing `osmnx-1.4.0/osmnx/distance.py` & `osmnx-1.5.0/osmnx/distance.py`

 * *Files 5% similar despite different names*

```diff
@@ -154,16 +154,18 @@
     x = G.nodes(data="x")
     y = G.nodes(data="y")
     try:
         # two-dimensional array of coordinates: y0, x0, y1, x1
         c = np.array([(y[u], x[u], y[v], x[v]) for u, v, k in uvk])
         # ensure all coordinates can be converted to float and are non-null
         assert not np.isnan(c.astype(float)).any()
-    except (AssertionError, KeyError):  # pragma: no cover
-        raise ValueError("some edges missing nodes, possibly due to input data clipping issue")
+    except (AssertionError, KeyError) as e:  # pragma: no cover
+        raise ValueError(
+            "some edges missing nodes, possibly due to input data clipping issue"
+        ) from e
 
     # calculate great circle distances, round, and fill nulls with zeros
     dists = great_circle_vec(c[:, 0], c[:, 1], c[:, 2], c[:, 3]).round(precision)
     dists[np.isnan(dists)] = 0
     nx.set_edge_attributes(G, values=dict(zip(uvk, dists)), name="length")
 
     utils.log("Added length attributes to graph edges")
@@ -247,42 +249,30 @@
 
 def nearest_edges(G, X, Y, interpolate=None, return_dist=False):
     """
     Find the nearest edge to a point or to each of several points.
 
     If `X` and `Y` are single coordinate values, this will return the nearest
     edge to that point. If `X` and `Y` are lists of coordinate values, this
-    will return the nearest edge to each point.
-
-    If `interpolate` is None, search for the nearest edge to each point, one
-    at a time, using an R-tree and minimizing the euclidean distances from the
-    point to the possible matches. For accuracy, use a projected graph and
-    points. This method is precise and fast, particularly when searching for
-    relatively few points compared to the graph's size.
-
-    For an alternative method, use the `interpolate` argument to interpolate
-    points along the edges and index them. If the graph is projected, this
-    uses a k-d tree for euclidean nearest neighbor search, which requires that
-    scipy is installed as an optional dependency. If graph is unprojected,
-    this uses a ball tree for haversine nearest neighbor search, which
-    requires that scikit-learn is installed as an optional dependency.
+    will return the nearest edge to each point. This function uses an R-tree
+    spatial index and minimizes the euclidean distance from each point to the
+    possible matches. For accurate results, use a projected graph and points.
 
     Parameters
     ----------
     G : networkx.MultiDiGraph
         graph in which to find nearest edges
     X : float or list
         points' x (longitude) coordinates, in same CRS/units as graph and
         containing no nulls
     Y : float or list
         points' y (latitude) coordinates, in same CRS/units as graph and
         containing no nulls
     interpolate : float
-        spacing distance between interpolated points, in same units as graph.
-        smaller values generate more points.
+        deprecated, do not use
     return_dist : bool
         optionally also return distance between points and nearest edges
 
     Returns
     -------
     ne or (ne, dist) : tuple or list
         nearest edges as (u, v, key) or optionally a tuple where `dist`
@@ -297,28 +287,33 @@
 
     if np.isnan(X).any() or np.isnan(Y).any():  # pragma: no cover
         raise ValueError("`X` and `Y` cannot contain nulls")
     geoms = utils_graph.graph_to_gdfs(G, nodes=False)["geometry"]
 
     # if no interpolation distance was provided
     if interpolate is None:
-        # build the r-tree spatial index by position for subsequent iloc
+        # build an r-tree spatial index by position for subsequent iloc
         rtree = STRtree(geoms)
 
-        # use r-tree to find each point's nearest neighbor and distance
+        # use the r-tree to find each point's nearest neighbor and distance
         points = [Point(xy) for xy in zip(X, Y)]
         pos, dist = rtree.query_nearest(points, all_matches=False, return_distance=True)
 
         # if user passed X/Y lists, the 2nd subarray contains geom indices
         if len(pos.shape) > 1:
             pos = pos[1]
         ne = geoms.iloc[pos].index
 
     # otherwise, if interpolation distance was provided
     else:
+        warn(
+            "The `interpolate` parameter has been deprecated and will be removed in a future release",
+            stacklevel=2,
+        )
+
         # interpolate points along edges to index with k-d tree or ball tree
         uvk_xy = []
         for uvk, geom in zip(geoms.index, geoms.values):
             uvk_xy.extend((uvk, xy) for xy in utils_geo.interpolate_points(geom, interpolate))
         labels, xy = zip(*uvk_xy)
         vertices = pd.DataFrame(xy, index=labels, columns=["x", "y"])
 
@@ -506,9 +501,9 @@
     None
     """
     try:
         values = np.array(tuple(G.edges(data=attr)))[:, 2]
         values_float = values.astype(float)
         if np.isnan(values_float).any():
             warn(f"The attribute {attr!r} is missing or null on some edges.", stacklevel=2)
-    except ValueError:
-        raise ValueError(f"The edge attribute {attr!r} contains non-numeric values.")
+    except ValueError as e:
+        raise ValueError(f"The edge attribute {attr!r} contains non-numeric values.") from e
```

### Comparing `osmnx-1.4.0/osmnx/downloader.py` & `osmnx-1.5.0/osmnx/_downloader.py`

 * *Files 2% similar despite different names*

```diff
@@ -298,20 +298,20 @@
 
     Resolves the URL's domain to an IP address so that we use the same server
     for both 1) checking the necessary pause duration and 2) sending the query
     itself even if there is round-robin redirecting among multiple server
     machines on the server-side. Mutates the getaddrinfo function so it uses
     the same IP address everytime it finds the hostname in the URL.
 
-    For example, the domain overpass-api.de just redirects to one of its
-    subdomains (currently z.overpass-api.de and lz4.overpass-api.de). So if we
-    check the status endpoint of overpass-api.de, we may see results for
-    subdomain z, but when we submit the query itself it gets redirected to
-    subdomain lz4. This could result in violating server lz4's slot management
-    timing.
+    For example, the server overpass-api.de just redirects to one of the other
+    servers (currently gall.openstreetmap.de and lambert.openstreetmap.de). So
+    if we check the status endpoint of overpass-api.de, we may see results for
+    server gall, but when we submit the query itself it gets redirected to
+    server lambert. This could result in violating server lambert's slot
+    management timing.
 
     Parameters
     ----------
     url : string
         the URL to consistently resolve the IP address of
 
     Returns
@@ -431,26 +431,24 @@
     Project to utm, divide polygon up into sub-polygons if area exceeds a
     max size (in meters), project back to lat-lng, then get a list of
     polygon(s) exterior coordinates
 
     Parameters
     ----------
     polygon : shapely.geometry.Polygon or shapely.geometry.MultiPolygon
-        geographic boundaries to fetch the OSM geometries within
 
     Returns
     -------
     polygon_coord_strs : list
         list of exterior coordinate strings for smaller sub-divided polygons
     """
     geometry_proj, crs_proj = projection.project_geometry(polygon)
     gpcs = utils_geo._consolidate_subdivide_geometry(geometry_proj)
     geometry, _ = projection.project_geometry(gpcs, crs=crs_proj, to_latlong=True)
     polygon_coord_strs = utils_geo._get_polygons_coordinates(geometry)
-    utils.log(f"Requesting data within polygon from API in {len(polygon_coord_strs)} request(s)")
     return polygon_coord_strs
 
 
 def _create_overpass_query(polygon_coord_str, tags):
     """
     Create an overpass query string based on passed tags.
 
@@ -547,34 +545,35 @@
     response_jsons = []
 
     # create overpass settings string
     overpass_settings = _make_overpass_settings()
 
     # subdivide query polygon to get list of sub-divided polygon coord strings
     polygon_coord_strs = _make_overpass_polygon_coord_strs(polygon)
+    utils.log(f"Requesting data from API in {len(polygon_coord_strs)} request(s)")
 
     # pass each polygon exterior coordinates in the list to the API, one at a
     # time. The '>' makes it recurse so we get ways and the ways' nodes.
     for polygon_coord_str in polygon_coord_strs:
         query_str = f"{overpass_settings};(way{osm_filter}(poly:{polygon_coord_str!r});>;);out;"
-        response_json = overpass_request(data={"data": query_str})
+        response_json = _overpass_request(data={"data": query_str})
         response_jsons.append(response_json)
     utils.log(
         f"Got all network data within polygon from API in {len(polygon_coord_strs)} request(s)"
     )
 
     if settings.cache_only_mode:  # pragma: no cover
         raise CacheOnlyModeInterrupt("settings.cache_only_mode=True")
 
     return response_jsons
 
 
-def _osm_geometries_download(polygon, tags):
+def _osm_features_download(polygon, tags):
     """
-    Retrieve non-networked elements within boundary from the Overpass API.
+    Retrieve OSM features within boundary from the Overpass API.
 
     Parameters
     ----------
     polygon : shapely.geometry.Polygon
         boundaries to fetch elements within
     tags : dict
         dict of tags used for finding elements in the selected area
@@ -584,38 +583,39 @@
     response_jsons : list
         list of JSON responses from the Overpass server
     """
     response_jsons = []
 
     # subdivide query polygon to get list of sub-divided polygon coord strings
     polygon_coord_strs = _make_overpass_polygon_coord_strs(polygon)
+    utils.log(f"Requesting data from API in {len(polygon_coord_strs)} request(s)")
 
     # pass exterior coordinates of each polygon in list to API, one at a time
     for polygon_coord_str in polygon_coord_strs:
         query_str = _create_overpass_query(polygon_coord_str, tags)
-        response_json = overpass_request(data={"data": query_str})
+        response_json = _overpass_request(data={"data": query_str})
         response_jsons.append(response_json)
 
     utils.log(
-        f"Got all geometries data within polygon from API in {len(polygon_coord_strs)} request(s)"
+        f"Got all features data within polygon from API in {len(polygon_coord_strs)} request(s)"
     )
 
     return response_jsons
 
 
-def _osm_place_download(query, by_osmid=False, limit=1, polygon_geojson=1):
+def _retrieve_osm_element(query, by_osmid=False, limit=1, polygon_geojson=1):
     """
-    Retrieve a place from the Nominatim API.
+    Retrieve an OSM element from the Nominatim API.
 
     Parameters
     ----------
     query : string or dict
         query string or structured query dict
     by_osmid : bool
-        if True, handle query as an OSM ID for lookup rather than text search
+        if True, treat query as an OSM ID lookup rather than text search
     limit : int
         max number of results to return
     polygon_geojson : int
         retrieve the place's geometry from the API, 0=no, 1=yes
 
     Returns
     -------
@@ -647,32 +647,32 @@
             # each time, for caching purposes
             for key in sorted(query):
                 params[key] = query[key]
         else:  # pragma: no cover
             raise TypeError("query must be a dict or a string")
 
     # request the URL, return the JSON
-    response_json = nominatim_request(params=params, request_type=request_type)
+    response_json = _nominatim_request(params=params, request_type=request_type)
     return response_json
 
 
-def nominatim_request(params, request_type="search", pause=1, error_pause=60):
+def _nominatim_request(params, request_type="search", pause=1, error_pause=60):
     """
     Send a HTTP GET request to the Nominatim API and return JSON response.
 
     Parameters
     ----------
     params : OrderedDict
         key-value pairs of parameters
     request_type : string {"search", "reverse", "lookup"}
         which Nominatim API endpoint to query
-    pause : int
+    pause : float
         how long to pause before request, in seconds. per the nominatim usage
         policy: "an absolute maximum of 1 request per second" is allowed
-    error_pause : int
+    error_pause : float
         how long to pause in seconds before re-trying request if error
 
     Returns
     -------
     response_json : dict
     """
     if request_type not in {"search", "reverse", "lookup"}:  # pragma: no cover
@@ -683,14 +683,15 @@
 
     # prepare Nominatim API URL and see if request already exists in cache
     url = settings.nominatim_endpoint.rstrip("/") + "/" + request_type
 
     prepared_url = requests.Request("GET", url, params=params).prepare().url
     cached_response_json = _retrieve_from_cache(prepared_url)
 
+    # add key after checking cache so the check is key independent
     if settings.nominatim_key:
         params["key"] = settings.nominatim_key
 
     if cached_response_json is not None:
         # found response in the cache, return it instead of calling server
         return cached_response_json
 
@@ -715,44 +716,46 @@
         size_kb = len(response.content) / 1000
         domain = re.findall(r"(?s)//(.*?)/", url)[0]
         utils.log(f"Downloaded {size_kb:,.1f}kB from {domain}")
 
         try:
             response_json = response.json()
 
-        except Exception:  # pragma: no cover
+        except Exception as e:  # pragma: no cover
             if sc in {429, 504}:
                 # 429 is 'too many requests' and 504 is 'gateway timeout' from
                 # server overload: handle these by pausing then recursively
                 # re-trying until we get a valid response from the server
                 utils.log(f"{domain} returned {sc}: retry in {error_pause} secs", level=lg.WARNING)
                 time.sleep(error_pause)
-                response_json = nominatim_request(params, request_type, pause, error_pause)
+                response_json = _nominatim_request(params, request_type, pause, error_pause)
 
             else:
                 # else, this was an unhandled status code, throw an exception
                 utils.log(f"{domain} returned {sc}", level=lg.ERROR)
-                raise Exception(f"Server returned:\n{response} {response.reason}\n{response.text}")
+                raise Exception(
+                    f"Server returned:\n{response} {response.reason}\n{response.text}"
+                ) from e
 
         _save_to_cache(prepared_url, response_json, sc)
         return response_json
 
 
-def overpass_request(data, pause=None, error_pause=60):
+def _overpass_request(data, pause=None, error_pause=60):
     """
     Send a HTTP POST request to the Overpass API and return JSON response.
 
     Parameters
     ----------
     data : OrderedDict
         key-value pairs of parameters
-    pause : int
+    pause : float
         how long to pause in seconds before request, if None, will query API
         status endpoint to find when next slot is available
-    error_pause : int
+    error_pause : float
         how long to pause in seconds (in addition to `pause`) before re-trying
         request if error
 
     Returns
     -------
     response_json : dict
     """
@@ -792,24 +795,26 @@
         utils.log(f"Downloaded {size_kb:,.1f}kB from {domain}")
 
         try:
             response_json = response.json()
             if "remark" in response_json:
                 utils.log(f'Server remark: {response_json["remark"]!r}', level=lg.WARNING)
 
-        except Exception:  # pragma: no cover
+        except Exception as e:  # pragma: no cover
             if sc in {429, 504}:
                 # 429 is 'too many requests' and 504 is 'gateway timeout' from
                 # server overload: handle these by pausing then recursively
                 # re-trying until we get a valid response from the server
                 this_pause = error_pause + _get_pause(base_endpoint)
                 utils.log(f"{domain} returned {sc}: retry in {this_pause} secs", level=lg.WARNING)
                 time.sleep(this_pause)
-                response_json = overpass_request(data, pause, error_pause)
+                response_json = _overpass_request(data, pause, error_pause)
 
             else:
                 # else, this was an unhandled status code, throw an exception
                 utils.log(f"{domain} returned {sc}", level=lg.ERROR)
-                raise Exception(f"Server returned\n{response} {response.reason}\n{response.text}")
+                raise Exception(
+                    f"Server returned\n{response} {response.reason}\n{response.text}"
+                ) from e
 
         _save_to_cache(prepared_url, response_json, sc)
         return response_json
```

### Comparing `osmnx-1.4.0/osmnx/elevation.py` & `osmnx-1.5.0/osmnx/elevation.py`

 * *Files 2% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 from warnings import warn
 
 import networkx as nx
 import numpy as np
 import pandas as pd
 import requests
 
-from . import downloader
+from . import _downloader
 from . import utils
 from . import utils_graph
 
 # rasterio and gdal are optional dependencies for raster querying
 try:
     import rasterio
     from osgeo import gdal
@@ -107,15 +107,15 @@
     nx.set_node_attributes(G, elevs, name="elevation")
     utils.log("Added elevation data from raster to all nodes.")
     return G
 
 
 def add_node_elevations_google(
     G,
-    api_key,
+    api_key=None,
     max_locations_per_batch=350,
     pause_duration=0,
     precision=None,
     url_template="https://maps.googleapis.com/maps/api/elevation/json?locations={}&key={}",
 ):  # pragma: no cover
     """
     Add `elevation` (meters) attribute to each node using a web service.
@@ -129,15 +129,15 @@
     function. See also the `add_edge_grades` function.
 
     Parameters
     ----------
     G : networkx.MultiDiGraph
         input graph
     api_key : string
-        a valid API key
+        a valid API key, сan be None if the API does not require a key
     max_locations_per_batch : int
         max number of coordinate pairs to submit in each API call (if this is
         too high, the server will reject the request because its character
         limit exceeds the max allowed)
     pause_duration : float
         time to pause between API calls, which can be increased if you get
         rate limited
@@ -175,25 +175,25 @@
     results = []
     for i in range(0, len(node_points), max_locations_per_batch):
         chunk = node_points.iloc[i : i + max_locations_per_batch]
         locations = "|".join(chunk)
         url = url_template.format(locations, api_key)
 
         # check if this request is already in the cache (if global use_cache=True)
-        cached_response_json = downloader._retrieve_from_cache(url)
+        cached_response_json = _downloader._retrieve_from_cache(url)
         if cached_response_json is not None:
             response_json = cached_response_json
         else:
             # request the elevations from the API
             utils.log(f"Requesting node elevations: {url}")
             time.sleep(pause_duration)
             response = requests.get(url)
             if response.status_code == 200:
                 response_json = response.json()
-                downloader._save_to_cache(url, response_json, response.status_code)
+                _downloader._save_to_cache(url, response_json, response.status_code)
             else:
                 raise Exception(
                     f"Server responded with {response.status_code}: {response.reason} \n{response.json()}"
                 )
 
         # append these elevation results to the list of all results
         results.extend(response_json["results"])
```

#### encoding

```diff
@@ -1 +1 @@
-us-ascii
+utf-8
```

### Comparing `osmnx-1.4.0/osmnx/folium.py` & `osmnx-1.5.0/osmnx/folium.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 """Create interactive Leaflet web maps of graphs and routes via folium.
 
 This module is deprecated. Do not use. It will be removed in a future release.
 You can generate and explore interactive web maps of graph nodes, edges,
 and/or routes automatically using GeoPandas.GeoDataFrame.explore instead, for
 example like: `ox.graph_to_gdfs(G, nodes=False).explore()`. See the OSMnx
-usage example repo for complete details and demonstrations.
+examples gallery for complete details and demonstrations.
 """
 
 import json
 from warnings import warn
 
 from . import utils_graph
 
@@ -30,15 +30,15 @@
 ):
     """
     Do not use: deprecated.
 
     You can generate and explore interactive web maps of graph nodes, edges,
     and/or routes automatically using GeoPandas.GeoDataFrame.explore instead,
     for example like: `ox.graph_to_gdfs(G, nodes=False).explore()`. See the
-    OSMnx usage example repo for complete details and demonstrations.
+    OSMnx examples gallery for complete details and demonstrations.
 
     Parameters
     ----------
     G : networkx.MultiDiGraph
         deprecated
     graph_map : folium.folium.Map
         deprecated
@@ -58,15 +58,15 @@
     folium.folium.Map
     """
     warn(
         "The `folium` module has been deprecated and will be removed in a future release. "
         "You can generate and explore interactive web maps of graph nodes, edges, "
         "and/or routes automatically using GeoPandas.GeoDataFrame.explore instead, "
         "for example like: `ox.graph_to_gdfs(G, nodes=False).explore()`. See the "
-        "OSMnx usage example repo for complete details and demonstrations.",
+        "OSMnx examples gallery for complete details and demonstrations.",
         stacklevel=2,
     )
     # create gdf of all graph edges
     gdf_edges = utils_graph.graph_to_gdfs(G, nodes=False)
     return _plot_folium(gdf_edges, graph_map, popup_attribute, tiles, zoom, fit_bounds, **kwargs)
 
 
@@ -82,15 +82,15 @@
 ):
     """
     Do not use: deprecated.
 
     You can generate and explore interactive web maps of graph nodes, edges,
     and/or routes automatically using GeoPandas.GeoDataFrame.explore instead,
     for example like: `ox.graph_to_gdfs(G, nodes=False).explore()`. See the
-    OSMnx usage example repo for complete details and demonstrations.
+    OSMnx examples gallery for complete details and demonstrations.
 
     Parameters
     ----------
     G : networkx.MultiDiGraph
         deprecated
     route : list
         deprecated
@@ -112,15 +112,15 @@
     folium.folium.Map
     """
     warn(
         "The `folium` module has been deprecated and will be removed in a future release. "
         "You can generate and explore interactive web maps of graph nodes, edges, "
         "and/or routes automatically using GeoPandas.GeoDataFrame.explore instead, "
         "for example like: `ox.graph_to_gdfs(G, nodes=False).explore()`. See the "
-        "OSMnx usage example repo for complete details and demonstrations.",
+        "OSMnx examples gallery for complete details and demonstrations.",
         stacklevel=2,
     )
     # create gdf of the route edges in order
     node_pairs = zip(route[:-1], route[1:])
     uvk = ((u, v, min(G[u][v].items(), key=lambda k: k[1]["length"])[0]) for u, v in node_pairs)
     gdf_edges = utils_graph.graph_to_gdfs(G.subgraph(route), nodes=False).loc[uvk]
     return _plot_folium(gdf_edges, route_map, popup_attribute, tiles, zoom, fit_bounds, **kwargs)
```

### Comparing `osmnx-1.4.0/osmnx/geocoder.py` & `osmnx-1.5.0/osmnx/geocoder.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,24 +1,32 @@
-"""Geocode queries and create GeoDataFrames of place boundaries."""
+"""
+Geocode place names or addresses or retrieve OSM elements by place name or ID.
+
+This module uses the Nominatim API's "search" and "lookup" endpoints. For more
+details see https://wiki.openstreetmap.org/wiki/Elements and
+https://nominatim.org/.
+"""
 
 import logging as lg
 from collections import OrderedDict
 
 import geopandas as gpd
 import pandas as pd
 
-from . import downloader
+from . import _downloader
 from . import projection
 from . import settings
 from . import utils
 
 
 def geocode(query):
     """
-    Geocode a query string to (lat, lng) with the Nominatim API.
+    Geocode place names or addresses to (lat, lng) with the Nominatim API.
+
+    This geocodes the query via the Nominatim "search" endpoint.
 
     Parameters
     ----------
     query : string
         the query string to geocode
 
     Returns
@@ -28,56 +36,60 @@
     """
     # define the parameters
     params = OrderedDict()
     params["format"] = "json"
     params["limit"] = 1
     params["dedupe"] = 0  # prevent deduping to get precise number of results
     params["q"] = query
-    response_json = downloader.nominatim_request(params=params)
+    response_json = _downloader._nominatim_request(params=params)
 
     # if results were returned, parse lat and lng out of the result
     if response_json and "lat" in response_json[0] and "lon" in response_json[0]:
         lat = float(response_json[0]["lat"])
         lng = float(response_json[0]["lon"])
         point = (lat, lng)
         utils.log(f"Geocoded {query!r} to {point}")
         return point
     else:
         raise ValueError(f"Nominatim could not geocode query {query!r}")
 
 
 def geocode_to_gdf(query, which_result=None, by_osmid=False, buffer_dist=None):
     """
-    Retrieve place(s) by name or ID from the Nominatim API as a GeoDataFrame.
+    Retrieve OSM elements by place name or OSM ID with the Nominatim API.
 
-    You can query by place name or OSM ID. If querying by place name, the
-    query argument can be a string or structured dict, or a list of such
-    strings/dicts to send to geocoder. You can instead query by OSM ID by
-    setting `by_osmid=True`. In this case, geocode_to_gdf treats the query
-    argument as an OSM ID (or list of OSM IDs) for Nominatim lookup rather
-    than text search. OSM IDs must be prepended with their types: node (N),
-    way (W), or relation (R), in accordance with the Nominatim format. For
-    example, `query=["R2192363", "N240109189", "W427818536"]`.
-
-    If query argument is a list, then which_result should be either a single
-    value or a list with the same length as query. The queries you provide
-    must be resolvable to places in the Nominatim database. The resulting
-    GeoDataFrame's geometry column contains place boundaries if they exist in
-    OpenStreetMap.
+    If searching by place name, the `query` argument can be a string or
+    structured dict, or a list of such strings/dicts to send to the geocoder.
+    This uses the Nominatim "search" endpoint to geocode the place name to the
+    best-matching OSM element, then returns that element and its attribute
+    data.
+
+    You can instead query by OSM ID by passing `by_osmid=True`. This uses the
+    Nominatim "lookup" endpoint to retrieve the OSM element with that ID. In
+    this case, the function treats the `query` argument as an OSM ID (or list
+    of OSM IDs), which must be prepended with their types: node (N), way (W),
+    or relation (R) in accordance with the Nominatim API format. For example,
+    `query=["R2192363", "N240109189", "W427818536"]`.
+
+    If `query` is a list, then `which_result` must be either a single value or
+    a list with the same length as `query`. The queries you provide must be
+    resolvable to elements in the Nominatim database. The resulting
+    GeoDataFrame's geometry column contains place boundaries if they exist.
 
     Parameters
     ----------
-    query : string or dict or list
+    query : string or dict or list of strings/dicts
         query string(s) or structured dict(s) to geocode
     which_result : int
-        which geocoding result to use. if None, auto-select the first
+        which search result to return. if None, auto-select the first
         (Multi)Polygon or raise an error if OSM doesn't return one. to get
-        the top match regardless of geometry type, set which_result=1
+        the top match regardless of geometry type, set which_result=1.
+        ignored if by_osmid=True.
     by_osmid : bool
-        if True, handle query as an OSM ID for lookup rather than text search
+        if True, treat query as an OSM ID lookup rather than text search
     buffer_dist : float
         distance to buffer around the place geometry, in meters
 
     Returns
     -------
     gdf : geopandas.GeoDataFrame
         a GeoDataFrame with one row for each query
@@ -108,15 +120,15 @@
     # geocode each query and add to GeoDataFrame as a new row
     gdf = gpd.GeoDataFrame()
     for q, wr in zip(query, which_result):
         gdf = pd.concat([gdf, _geocode_query_to_gdf(q, wr, by_osmid)])
 
     # reset GeoDataFrame index and set its CRS
     gdf = gdf.reset_index(drop=True)
-    gdf.crs = settings.default_crs
+    gdf = gdf.set_crs(settings.default_crs)
 
     # if buffer_dist was passed in, project the geometry to UTM, buffer it in
     # meters, then project it back to lat-lng
     if buffer_dist is not None and len(gdf) > 0:
         gdf_utm = projection.project_gdf(gdf)
         gdf_utm["geometry"] = gdf_utm["geometry"].buffer(buffer_dist)
         gdf = projection.project_gdf(gdf_utm, to_latlong=True)
@@ -133,29 +145,30 @@
     Parameters
     ----------
     query : string or dict
         query string or structured dict to geocode
     which_result : int
         which geocoding result to use. if None, auto-select the first
         (Multi)Polygon or raise an error if OSM doesn't return one. to get
-        the top match regardless of geometry type, set which_result=1
+        the top match regardless of geometry type, set which_result=1.
+        ignored if by_osmid=True.
     by_osmid : bool
         if True, handle query as an OSM ID for lookup rather than text search
 
     Returns
     -------
     gdf : geopandas.GeoDataFrame
         a GeoDataFrame with one row containing the result of geocoding
     """
     if which_result is None:
         limit = 50
     else:
         limit = which_result
 
-    results = downloader._osm_place_download(query, by_osmid=by_osmid, limit=limit)
+    results = _downloader._retrieve_osm_element(query, by_osmid=by_osmid, limit=limit)
 
     # choose the right result from the JSON response
     if not results:
         # if no results were returned, raise error
         raise ValueError(f"Nominatim geocoder returned 0 results for query {query!r}")
 
     elif by_osmid:
@@ -209,15 +222,15 @@
 def _get_first_polygon(results, query):
     """
     Choose first result of geometry type (Multi)Polygon from list of results.
 
     Parameters
     ----------
     results : list
-        list of results from downloader._osm_place_download
+        list of results from _downloader._osm_place_download
     query : str
         the query string or structured dict that was geocoded
 
     Returns
     -------
     result : dict
         the chosen result
```

### Comparing `osmnx-1.4.0/osmnx/geometries.py` & `osmnx-1.5.0/osmnx/features.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,45 +1,93 @@
 """
-Download geospatial entities' geometries and attributes from OpenStreetMap.
+Download OpenStreetMap geospatial features' geometries and attributes.
 
 Retrieve points of interest, building footprints, transit lines/stops, or any
-other objects from OSM, including their geometries and attribute data, and
-construct a GeoDataFrame of them. You can use this module to query for nodes,
-ways, and relations (the latter of type "multipolygon" or "boundary" only) by
-passing a dictionary of desired tags/values.
+other map features from OSM, including their geometries and attribute data,
+then construct a GeoDataFrame of them. You can use this module to query for
+nodes, ways, and relations (the latter of type "multipolygon" or "boundary"
+only) by passing a dictionary of desired OSM tags.
+
+For more details, see https://wiki.openstreetmap.org/wiki/Map_features and
+https://wiki.openstreetmap.org/wiki/Elements
 """
 
 import logging as lg
 import warnings
 
 import geopandas as gpd
-import numpy as np
 import pandas as pd
 from shapely.errors import GEOSException
 from shapely.errors import TopologicalError
 from shapely.geometry import LineString
 from shapely.geometry import MultiPolygon
 from shapely.geometry import Point
 from shapely.geometry import Polygon
 from shapely.ops import linemerge
 from shapely.ops import polygonize
 
-from . import downloader
+from . import _downloader
 from . import geocoder
 from . import osm_xml
 from . import settings
 from . import utils
 from . import utils_geo
 from ._errors import EmptyOverpassResponse
-from ._polygon_features import _polygon_features
 
+# dict of tags to determine if closed ways should be polygons, based on JSON
+# from https://wiki.openstreetmap.org/wiki/Overpass_turbo/Polygon_Features
+_POLYGON_FEATURES = {
+    "building": {"polygon": "all"},
+    "highway": {"polygon": "passlist", "values": ["services", "rest_area", "escape", "elevator"]},
+    "natural": {
+        "polygon": "blocklist",
+        "values": ["coastline", "cliff", "ridge", "arete", "tree_row"],
+    },
+    "landuse": {"polygon": "all"},
+    "waterway": {"polygon": "passlist", "values": ["riverbank", "dock", "boatyard", "dam"]},
+    "amenity": {"polygon": "all"},
+    "leisure": {"polygon": "all"},
+    "barrier": {
+        "polygon": "passlist",
+        "values": ["city_wall", "ditch", "hedge", "retaining_wall", "spikes"],
+    },
+    "railway": {
+        "polygon": "passlist",
+        "values": ["station", "turntable", "roundhouse", "platform"],
+    },
+    "area": {"polygon": "all"},
+    "boundary": {"polygon": "all"},
+    "man_made": {"polygon": "blocklist", "values": ["cutline", "embankment", "pipeline"]},
+    "power": {"polygon": "passlist", "values": ["plant", "substation", "generator", "transformer"]},
+    "place": {"polygon": "all"},
+    "shop": {"polygon": "all"},
+    "aeroway": {"polygon": "blocklist", "values": ["taxiway"]},
+    "tourism": {"polygon": "all"},
+    "historic": {"polygon": "all"},
+    "public_transport": {"polygon": "all"},
+    "office": {"polygon": "all"},
+    "building:part": {"polygon": "all"},
+    "military": {"polygon": "all"},
+    "ruins": {"polygon": "all"},
+    "area:highway": {"polygon": "all"},
+    "craft": {"polygon": "all"},
+    "golf": {"polygon": "all"},
+    "indoor": {"polygon": "all"},
+}
+
+
+def features_from_bbox(north, south, east, west, tags):
+    """
+    Create a GeoDataFrame of OSM features within a N, S, E, W bounding box.
+
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
 
-def geometries_from_bbox(north, south, east, west, tags):
-    """
-    Create a GeoDataFrame of OSM entities within a N, S, E, W bounding box.
+    For more details, see: https://wiki.openstreetmap.org/wiki/Map_features
 
     Parameters
     ----------
     north : float
         northern latitude of bounding box
     south : float
         southern latitude of bounding box
@@ -59,37 +107,38 @@
         the area. `tags = {'amenity':True, 'landuse':['retail','commercial'],
         'highway':'bus_stop'}` would return all amenities, landuse=retail,
         landuse=commercial, and highway=bus_stop.
 
     Returns
     -------
     gdf : geopandas.GeoDataFrame
-
-    Notes
-    -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module.
     """
     # convert bounding box to a polygon
     polygon = utils_geo.bbox_to_poly(north, south, east, west)
 
-    # create GeoDataFrame of geometries within this polygon
-    gdf = geometries_from_polygon(polygon, tags)
+    # create GeoDataFrame of features within this polygon
+    gdf = features_from_polygon(polygon, tags)
 
     return gdf
 
 
-def geometries_from_point(center_point, tags, dist=1000):
+def features_from_point(center_point, tags, dist=1000):
     """
-    Create GeoDataFrame of OSM entities within some distance N, S, E, W of a point.
+    Create GeoDataFrame of OSM features within some distance N, S, E, W of a point.
+
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
+
+    For more details, see: https://wiki.openstreetmap.org/wiki/Map_features
 
     Parameters
     ----------
     center_point : tuple
-        the (lat, lng) center point around which to get the geometries
+        the (lat, lng) center point around which to get the features
     tags : dict
         Dict of tags used for finding objects in the selected area. Results
         returned are the union, not intersection of each individual tag.
         Each result matches at least one given tag. The dict keys should be
         OSM tags, (e.g., `building`, `landuse`, `highway`, etc) and the dict
         values should be either `True` to retrieve all items with the given
         tag, or a string to get a single tag-value combination, or a list of
@@ -100,41 +149,42 @@
         landuse=commercial, and highway=bus_stop.
     dist : numeric
         distance in meters
 
     Returns
     -------
     gdf : geopandas.GeoDataFrame
-
-    Notes
-    -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module.
     """
     # create bounding box from center point and distance in each direction
     north, south, east, west = utils_geo.bbox_from_point(center_point, dist)
 
     # convert the bounding box to a polygon
     polygon = utils_geo.bbox_to_poly(north, south, east, west)
 
-    # create GeoDataFrame of geometries within this polygon
-    gdf = geometries_from_polygon(polygon, tags)
+    # create GeoDataFrame of features within this polygon
+    gdf = features_from_polygon(polygon, tags)
 
     return gdf
 
 
-def geometries_from_address(address, tags, dist=1000):
+def features_from_address(address, tags, dist=1000):
     """
-    Create GeoDataFrame of OSM entities within some distance N, S, E, W of address.
+    Create GeoDataFrame of OSM features within some distance N, S, E, W of address.
+
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
+
+    For more details, see: https://wiki.openstreetmap.org/wiki/Map_features
 
     Parameters
     ----------
     address : string
         the address to geocode and use as the central point around which to
-        get the geometries
+        get the features
     tags : dict
         Dict of tags used for finding objects in the selected area. Results
         returned are the union, not intersection of each individual tag.
         Each result matches at least one given tag. The dict keys should be
         OSM tags, (e.g., `building`, `landuse`, `highway`, etc) and the dict
         values should be either `True` to retrieve all items with the given
         tag, or a string to get a single tag-value combination, or a list of
@@ -145,46 +195,47 @@
         landuse=commercial, and highway=bus_stop.
     dist : numeric
         distance in meters
 
     Returns
     -------
     gdf : geopandas.GeoDataFrame
-
-    Notes
-    -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module.
     """
     # geocode the address string to a (lat, lng) point
     center_point = geocoder.geocode(query=address)
 
-    # create GeoDataFrame of geometries around this point
-    gdf = geometries_from_point(center_point, tags, dist=dist)
+    # create GeoDataFrame of features around this point
+    gdf = features_from_point(center_point, tags, dist=dist)
 
     return gdf
 
 
-def geometries_from_place(query, tags, which_result=None, buffer_dist=None):
+def features_from_place(query, tags, which_result=None, buffer_dist=None):
     """
-    Create GeoDataFrame of OSM entities within boundaries of geocodable place(s).
+    Create GeoDataFrame of OSM features within boundaries of some place(s).
 
     The query must be geocodable and OSM must have polygon boundaries for the
     geocode result. If OSM does not have a polygon for this place, you can
-    instead get geometries within it using the geometries_from_address
-    function, which geocodes the place name to a point and gets the geometries
+    instead get features within it using the `features_from_address`
+    function, which geocodes the place name to a point and gets the features
     within some distance of that point.
 
     If OSM does have polygon boundaries for this place but you're not finding
     it, try to vary the query string, pass in a structured query dict, or vary
-    the which_result argument to use a different geocode result. If you know
+    the `which_result` argument to use a different geocode result. If you know
     the OSM ID of the place, you can retrieve its boundary polygon using the
-    geocode_to_gdf function, then pass it to the geometries_from_polygon
+    `geocode_to_gdf` function, then pass it to the `features_from_polygon`
     function.
 
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
+
+    For more details, see: https://wiki.openstreetmap.org/wiki/Map_features
+
     Parameters
     ----------
     query : string or dict or list
         the query or queries to geocode to get place boundary polygon(s)
     tags : dict
         Dict of tags used for finding objects in the selected area. Results
         returned are the union, not intersection of each individual tag.
@@ -202,19 +253,14 @@
         (Multi)Polygon or raise an error if OSM doesn't return one.
     buffer_dist : float
         distance to buffer around the place geometry, in meters
 
     Returns
     -------
     gdf : geopandas.GeoDataFrame
-
-    Notes
-    -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module.
     """
     # create a GeoDataFrame with the spatial boundaries of the place(s)
     if isinstance(query, (str, dict)):
         # if it is a string (place name) or dict (structured place query),
         # then it is a single place
         gdf_place = geocoder.geocode_to_gdf(
             query, which_result=which_result, buffer_dist=buffer_dist
@@ -226,27 +272,33 @@
         raise TypeError("query must be dict, string, or list of strings")
 
     # extract the geometry from the GeoDataFrame to use in API query
     polygon = gdf_place["geometry"].unary_union
     utils.log("Constructed place geometry polygon(s) to query API")
 
     # create GeoDataFrame using this polygon(s) geometry
-    gdf = geometries_from_polygon(polygon, tags)
+    gdf = features_from_polygon(polygon, tags)
 
     return gdf
 
 
-def geometries_from_polygon(polygon, tags):
+def features_from_polygon(polygon, tags):
     """
-    Create GeoDataFrame of OSM entities within boundaries of a (multi)polygon.
+    Create GeoDataFrame of OSM features within boundaries of a (multi)polygon.
+
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
+
+    For more details, see: https://wiki.openstreetmap.org/wiki/Map_features
 
     Parameters
     ----------
     polygon : shapely.geometry.Polygon or shapely.geometry.MultiPolygon
-        geographic boundaries to fetch geometries within
+        geographic boundaries to fetch features within
     tags : dict
         Dict of tags used for finding objects in the selected area. Results
         returned are the union, not intersection of each individual tag.
         Each result matches at least one given tag. The dict keys should be
         OSM tags, (e.g., `building`, `landuse`, `highway`, etc) and the dict
         values should be either `True` to retrieve all items with the given
         tag, or a string to get a single tag-value combination, or a list of
@@ -255,51 +307,48 @@
         the area. `tags = {'amenity':True, 'landuse':['retail','commercial'],
         'highway':'bus_stop'}` would return all amenities, landuse=retail,
         landuse=commercial, and highway=bus_stop.
 
     Returns
     -------
     gdf : geopandas.GeoDataFrame
-
-    Notes
-    -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module.
     """
     # verify that the geometry is valid and a Polygon/MultiPolygon
     if not polygon.is_valid:
         raise ValueError("The geometry of `polygon` is invalid")
     if not isinstance(polygon, (Polygon, MultiPolygon)):
         raise TypeError(
             "Boundaries must be a shapely Polygon or MultiPolygon. If you requested "
-            "geometries from place name, make sure your query resolves to a Polygon or "
+            "features from place name, make sure your query resolves to a Polygon or "
             "MultiPolygon, and not some other geometry, like a Point. See OSMnx "
             "documentation for details."
         )
 
-    # download the geometry data from OSM
-    response_jsons = downloader._osm_geometries_download(polygon, tags)
+    # download the data from OSM
+    response_jsons = _downloader._osm_features_download(polygon, tags)
 
     # create GeoDataFrame from the downloaded data
     gdf = _create_gdf(response_jsons, polygon, tags)
 
     return gdf
 
 
-def geometries_from_xml(filepath, polygon=None, tags=None):
+def features_from_xml(filepath, polygon=None, tags=None):
     """
-    Create a GeoDataFrame of OSM entities in an OSM-formatted XML file.
+    Create a GeoDataFrame of OSM features in an OSM-formatted XML file.
 
-    Because this function creates a GeoDataFrame of geometries from an
+    Because this function creates a GeoDataFrame of features from an
     OSM-formatted XML file that has already been downloaded (i.e. no query is
     made to the Overpass API) the polygon and tags arguments are not required.
-    If they are not supplied to the function, geometries_from_xml() will
-    return geometries for all of the tagged elements in the file. If they are
+    If they are not supplied to the function, features_from_xml() will
+    return features for all of the tagged elements in the file. If they are
     supplied they will be used to filter the final GeoDataFrame.
 
+    For more details, see: https://wiki.openstreetmap.org/wiki/Map_features
+
     Parameters
     ----------
     filepath : string or pathlib.Path
         path to file containing OSM XML data
     polygon : shapely.geometry.Polygon
         optional geographic boundary to filter objects
     tags : dict
@@ -330,42 +379,42 @@
 
 def _create_gdf(response_jsons, polygon, tags):
     """
     Parse JSON responses from the Overpass API to a GeoDataFrame.
 
     Note: the `polygon` and `tags` arguments can both be `None` and the
     GeoDataFrame will still be created but it won't be filtered at the end
-    i.e. the final GeoDataFrame will contain all tagged geometries in the
+    i.e. the final GeoDataFrame will contain all tagged features in the
     `response_jsons`.
 
     Parameters
     ----------
     response_jsons : list
         list of JSON responses from from the Overpass API
     polygon : shapely.geometry.Polygon
         geographic boundary used for filtering the final GeoDataFrame
     tags : dict
         dict of tags used for filtering the final GeoDataFrame
 
     Returns
     -------
     gdf : geopandas.GeoDataFrame
-        GeoDataFrame of geometries and their associated tags
+        GeoDataFrame of features and their associated tags
     """
     elements_count = sum(len(rj["elements"]) for rj in response_jsons)
 
     # make sure we got data back from the server request(s)
     if elements_count == 0:
         msg = (
             "There are no data elements in the server response. Check log and query location/tags."
         )
         raise EmptyOverpassResponse(msg)
 
     # begin processing the elements retrieved from the server
-    utils.log(f"Converting {elements_count} elements in JSON responses to geometries")
+    utils.log(f"Converting {elements_count} elements in JSON responses to features")
 
     # Dictionaries to hold nodes and complete geometries
     coords = {}
     geometries = {}
 
     # Set to hold the unique IDs of elements that do not have tags
     untagged_element_ids = set()
@@ -418,27 +467,22 @@
 
     utils.log(f"{len(geometries)} geometries created in the dict")
 
     # remove untagged elements from the final dict of geometries
     for untagged_element_id in untagged_element_ids:
         geometries.pop(untagged_element_id, None)
 
-    utils.log(f"{len(untagged_element_ids)} untagged geometries removed")
+    utils.log(f"{len(untagged_element_ids)} untagged features removed")
 
-    # Create GeoDataFrame
+    # create GeoDataFrame, ensure it has geometry, then set crs
     gdf = gpd.GeoDataFrame.from_dict(geometries, orient="index")
-
-    # ensure gdf has a geometry col before assigning crs
     if "geometry" not in gdf.columns:
         # if there is no geometry column, create a null column
-        gdf["geometry"] = np.nan
-    gdf.set_geometry("geometry")
-
-    # Set default crs
-    gdf.crs = settings.default_crs
+        gdf = gdf.set_geometry([None] * len(gdf))
+    gdf = gdf.set_crs(settings.default_crs)
 
     # Apply .buffer(0) to any invalid geometries
     gdf = _buffer_invalid_geometries(gdf)
 
     # Filter final gdf to requested tags and query polygon
     gdf = _filter_gdf_by_polygon_and_tags(gdf, polygon=polygon, tags=tags)
 
@@ -448,15 +492,15 @@
     # or missing (e.g. None) geometry, and suppress gpd warning caused by
     # calling gdf["geometry"].isna() on GeoDataFrame with empty geometries
     if not gdf.empty:
         warnings.filterwarnings("ignore", "GeoSeries.isna", UserWarning)
         gdf = gdf[~(gdf["geometry"].is_empty | gdf["geometry"].isna())].copy()
         warnings.resetwarnings()
 
-    utils.log(f"{len(gdf)} geometries in the final GeoDataFrame")
+    utils.log(f"{len(gdf)} features in the final GeoDataFrame")
     return gdf
 
 
 def _parse_node_to_coords(element):
     """
     Parse coordinates from a node in the overpass response.
 
@@ -501,15 +545,15 @@
         for tag in element["tags"]:
             point[tag] = element["tags"][tag]
 
     point["geometry"] = Point(element["lon"], element["lat"])
     return point
 
 
-def _parse_way_to_linestring_or_polygon(element, coords, polygon_features=_polygon_features):
+def _parse_way_to_linestring_or_polygon(element, coords, polygon_features=_POLYGON_FEATURES):
     """
     Parse open LineString, closed LineString or Polygon from OSM 'way'.
 
     Please see https://wiki.openstreetmap.org/wiki/Overpass_turbo/Polygon_Features
     for more information on which tags should be parsed to polygons
 
     Parameters
@@ -584,15 +628,15 @@
                 )
                 geometry = LineString()
 
     linestring_or_polygon["geometry"] = geometry
     return linestring_or_polygon
 
 
-def _is_closed_way_a_polygon(element, polygon_features=_polygon_features):
+def _is_closed_way_a_polygon(element, polygon_features=_POLYGON_FEATURES):
     """
     Determine whether a closed OSM way represents a Polygon, not a LineString.
 
     Closed OSM ways may represent LineStrings (e.g. a roundabout or hedge
     round a field) or Polygons (e.g. a building footprint or land use area)
     depending on the tags applied to them.
 
@@ -906,15 +950,14 @@
             invalid_geom_urls = [osm_url + unique_id for unique_id in invalid_geometry_ids]
             utils.log(
                 f"{len(invalid_geometry_ids)} invalid geometries"
                 f".buffer(0) applied to {invalid_geom_urls}",
                 level=lg.WARNING,
             )
 
-            # apply .buffer(0)
             gdf.loc[invalid_geometry_filter, "geometry"] = gdf.loc[
                 invalid_geometry_filter, "geometry"
             ].buffer(0)
 
     return gdf
 
 
@@ -943,24 +986,24 @@
     # only apply the filters if the GeoDataFrame is not empty
     if not gdf.empty:
         # create two filters, initially all True
         polygon_filter = pd.Series(True, index=gdf.index)
         combined_tag_filter = pd.Series(True, index=gdf.index)
 
         # if a polygon was supplied, create a filter that is True for
-        # geometries that intersect with the polygon
+        # features that intersect with the polygon
         if polygon:
-            # get set of index labels of geometries that intersect polygon
+            # get set of index labels of features that intersect polygon
             gdf_indices_in_polygon = utils_geo._intersect_index_quadrats(gdf, polygon)
-            # create boolean series, True for geometries whose index is in set
+            # create boolean series, True for features whose index is in set
             polygon_filter = gdf.index.isin(gdf_indices_in_polygon)
 
-            utils.log(f"{sum(~polygon_filter)} geometries removed by the polygon filter")
+            utils.log(f"{sum(~polygon_filter)} features removed by the polygon filter")
 
-        # if tags were supplied, create filter that is True for geometries
+        # if tags were supplied, create filter that is True for features
         # that have at least one of the requested tags
         if tags:
             # Reset all values in the combined_tag_filter to False
             combined_tag_filter[:] = False
 
             # reduce the tags to those that are actually present in the
             # GeoDataFrame columns
@@ -972,20 +1015,20 @@
                 elif isinstance(value, str):
                     tag_filter = gdf[key] == value
                 elif isinstance(value, list):
                     tag_filter = gdf[key].isin(value)
 
                 combined_tag_filter = combined_tag_filter | tag_filter
 
-            utils.log(f"{sum(~combined_tag_filter)} geometries removed by the tag filter")
+            utils.log(f"{sum(~combined_tag_filter)} features removed by the tag filter")
 
         # apply the filters
         gdf = gdf[polygon_filter & combined_tag_filter].copy()
 
-        # remove columns of all nulls (created by discarded component geometries)
+        # remove columns of all nulls (created by discarded component features)
         gdf.dropna(axis="columns", how="all", inplace=True)
 
     # multi-index gdf by element_type and osmid then return
     idx_cols = ["element_type", "osmid"]
     if all(c in gdf.columns for c in idx_cols):
         gdf = gdf.set_index(idx_cols)
     return gdf
```

### Comparing `osmnx-1.4.0/osmnx/graph.py` & `osmnx-1.5.0/osmnx/graph.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,18 +1,18 @@
-"""Graph creation functions."""
+"""Download and create graphs from OpenStreetMap data."""
 
 import itertools
 from warnings import warn
 
 import networkx as nx
 from shapely.geometry import MultiPolygon
 from shapely.geometry import Polygon
 
+from . import _downloader
 from . import distance
-from . import downloader
 from . import geocoder
 from . import osm_xml
 from . import projection
 from . import settings
 from . import simplification
 from . import stats
 from . import truncate
@@ -32,15 +32,19 @@
     simplify=True,
     retain_all=False,
     truncate_by_edge=False,
     clean_periphery=True,
     custom_filter=None,
 ):
     """
-    Create a graph from OSM within some bounding box.
+    Download and create a graph within some bounding box.
+
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
 
     Parameters
     ----------
     north : float
         northern latitude of bounding box
     south : float
         southern latitude of bounding box
@@ -69,18 +73,17 @@
 
     Returns
     -------
     G : networkx.MultiDiGraph
 
     Notes
     -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module. Very large query areas
-    will use the utils_geo._consolidate_subdivide_geometry function to perform
-    multiple queries: see that function's documentation for caveats.
+    Very large query areas use the `utils_geo._consolidate_subdivide_geometry`
+    function to automatically make multiple requests: see that function's
+    documentation for caveats.
     """
     # convert bounding box to a polygon
     polygon = utils_geo.bbox_to_poly(north, south, east, west)
 
     # create graph using this polygon geometry
     G = graph_from_polygon(
         polygon,
@@ -104,28 +107,31 @@
     simplify=True,
     retain_all=False,
     truncate_by_edge=False,
     clean_periphery=True,
     custom_filter=None,
 ):
     """
-    Create a graph from OSM within some distance of some (lat, lng) point.
+    Download and create a graph within some distance of a (lat, lng) point.
+
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
 
     Parameters
     ----------
     center_point : tuple
         the (lat, lng) center point around which to construct the graph
     dist : int
         retain only those nodes within this many meters of the center of the
         graph, with distance determined according to dist_type argument
     dist_type : string {"network", "bbox"}
         if "bbox", retain only those nodes within a bounding box of the
         distance parameter. if "network", retain only those nodes within some
-        network distance from the center-most node (requires that scikit-learn
-        is installed as an optional dependency).
+        network distance from the center-most node.
     network_type : string, {"all_private", "all", "bike", "drive", "drive_service", "walk"}
         what type of street network to get if custom_filter is None
     simplify : bool
         if True, simplify graph topology with the `simplify_graph` function
     retain_all : bool
         if True, return the entire graph even if it is not connected.
         otherwise, retain only the largest weakly connected component.
@@ -143,18 +149,17 @@
 
     Returns
     -------
     G : networkx.MultiDiGraph
 
     Notes
     -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module. Very large query areas
-    will use the utils_geo._consolidate_subdivide_geometry function to perform
-    multiple queries: see that function's documentation for caveats.
+    Very large query areas use the `utils_geo._consolidate_subdivide_geometry`
+    function to automatically make multiple requests: see that function's
+    documentation for caveats.
     """
     if dist_type not in {"bbox", "network"}:  # pragma: no cover
         raise ValueError('dist_type must be "bbox" or "network"')
 
     # create bounding box from center point and distance in each direction
     north, south, east, west = utils_geo.bbox_from_point(center_point, dist)
 
@@ -191,29 +196,32 @@
     retain_all=False,
     truncate_by_edge=False,
     return_coords=False,
     clean_periphery=True,
     custom_filter=None,
 ):
     """
-    Create a graph from OSM within some distance of some address.
+    Download and create a graph within some distance of an address.
+
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
 
     Parameters
     ----------
     address : string
         the address to geocode and use as the central point around which to
         construct the graph
     dist : int
         retain only those nodes within this many meters of the center of the
         graph
     dist_type : string {"network", "bbox"}
         if "bbox", retain only those nodes within a bounding box of the
         distance parameter. if "network", retain only those nodes within some
-        network distance from the center-most node (requires that scikit-learn
-        is installed as an optional dependency).
+        network distance from the center-most node.
     network_type : string {"all_private", "all", "bike", "drive", "drive_service", "walk"}
         what type of street network to get if custom_filter is None
     simplify : bool
         if True, simplify graph topology with the `simplify_graph` function
     retain_all : bool
         if True, return the entire graph even if it is not connected.
         otherwise, retain only the largest weakly connected component.
@@ -233,18 +241,17 @@
 
     Returns
     -------
     networkx.MultiDiGraph or optionally (networkx.MultiDiGraph, (lat, lng))
 
     Notes
     -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module. Very large query areas
-    will use the utils_geo._consolidate_subdivide_geometry function to perform
-    multiple queries: see that function's documentation for caveats.
+    Very large query areas use the `utils_geo._consolidate_subdivide_geometry`
+    function to automatically make multiple requests: see that function's
+    documentation for caveats.
     """
     # geocode the address string to a (lat, lng) point
     point = geocoder.geocode(query=address)
 
     # then create a graph from this point
     G = graph_from_point(
         point,
@@ -273,28 +280,32 @@
     truncate_by_edge=False,
     which_result=None,
     buffer_dist=None,
     clean_periphery=True,
     custom_filter=None,
 ):
     """
-    Create graph from OSM within the boundaries of some geocodable place(s).
+    Download and create a graph within the boundaries of some place(s).
 
     The query must be geocodable and OSM must have polygon boundaries for the
     geocode result. If OSM does not have a polygon for this place, you can
     instead get its street network using the graph_from_address function,
     which geocodes the place name to a point and gets the network within some
     distance of that point.
 
     If OSM does have polygon boundaries for this place but you're not finding
     it, try to vary the query string, pass in a structured query dict, or vary
     the which_result argument to use a different geocode result. If you know
     the OSM ID of the place, you can retrieve its boundary polygon using the
     geocode_to_gdf function, then pass it to the graph_from_polygon function.
 
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
+
     Parameters
     ----------
     query : string or dict or list
         the query or queries to geocode to get place boundary polygon(s)
     network_type : string {"all_private", "all", "bike", "drive", "drive_service", "walk"}
         what type of street network to get if custom_filter is None
     simplify : bool
@@ -321,18 +332,17 @@
 
     Returns
     -------
     G : networkx.MultiDiGraph
 
     Notes
     -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module. Very large query areas
-    will use the utils_geo._consolidate_subdivide_geometry function to perform
-    multiple queries: see that function's documentation for caveats.
+    Very large query areas use the `utils_geo._consolidate_subdivide_geometry`
+    function to automatically make multiple requests: see that function's
+    documentation for caveats.
     """
     # create a GeoDataFrame with the spatial boundaries of the place(s)
     if isinstance(query, (str, dict)):
         # if it is a string (place name) or dict (structured place query),
         # then it is a single place
         gdf_place = geocoder.geocode_to_gdf(
             query, which_result=which_result, buffer_dist=buffer_dist
@@ -368,15 +378,19 @@
     simplify=True,
     retain_all=False,
     truncate_by_edge=False,
     clean_periphery=True,
     custom_filter=None,
 ):
     """
-    Create a graph from OSM within the boundaries of some shapely polygon.
+    Download and create a graph within the boundaries of a (multi)polygon.
+
+    You can use the `settings` module to retrieve a snapshot of historical OSM
+    data as of a certain date, or to configure the Overpass server timeout,
+    memory allocation, and other custom settings.
 
     Parameters
     ----------
     polygon : shapely.geometry.Polygon or shapely.geometry.MultiPolygon
         the shape to get network data within. coordinates should be in
         unprojected latitude-longitude degrees (EPSG:4326).
     network_type : string {"all_private", "all", "bike", "drive", "drive_service", "walk"}
@@ -400,18 +414,17 @@
 
     Returns
     -------
     G : networkx.MultiDiGraph
 
     Notes
     -----
-    You can configure the Overpass server timeout, memory allocation, and
-    other custom settings via the `settings` module. Very large query areas
-    will use the utils_geo._consolidate_subdivide_geometry function to perform
-    multiple queries: see that function's documentation for caveats.
+    Very large query areas use the `utils_geo._consolidate_subdivide_geometry`
+    function to automatically make multiple requests: see that function's
+    documentation for caveats.
     """
     # verify that the geometry is valid and is a shapely Polygon/MultiPolygon
     # before proceeding
     if not polygon.is_valid:  # pragma: no cover
         raise ValueError("The geometry to query within is invalid")
     if not isinstance(polygon, (Polygon, MultiPolygon)):  # pragma: no cover
         raise TypeError(
@@ -425,15 +438,15 @@
         # create a new buffered polygon 0.5km around the desired one
         buffer_dist = 500
         poly_proj, crs_utm = projection.project_geometry(polygon)
         poly_proj_buff = poly_proj.buffer(buffer_dist)
         poly_buff, _ = projection.project_geometry(poly_proj_buff, crs=crs_utm, to_latlong=True)
 
         # download the network data from OSM within buffered polygon
-        response_jsons = downloader._osm_network_download(poly_buff, network_type, custom_filter)
+        response_jsons = _downloader._osm_network_download(poly_buff, network_type, custom_filter)
 
         # create buffered graph from the downloaded data
         bidirectional = network_type in settings.bidirectional_network_types
         G_buff = _create_graph(response_jsons, retain_all=True, bidirectional=bidirectional)
 
         # truncate buffered graph to the buffered polygon and retain_all for
         # now. needed because overpass returns entire ways that also include
@@ -457,15 +470,15 @@
         # intersection, even if some of its neighbors are outside the polygon
         spn = stats.count_streets_per_node(G_buff, nodes=G.nodes)
         nx.set_node_attributes(G, values=spn, name="street_count")
 
     # if clean_periphery=False, just use the polygon as provided
     else:
         # download the network data from OSM
-        response_jsons = downloader._osm_network_download(polygon, network_type, custom_filter)
+        response_jsons = _downloader._osm_network_download(polygon, network_type, custom_filter)
 
         # create graph from the downloaded data
         bidirectional = network_type in settings.bidirectional_network_types
         G = _create_graph(response_jsons, retain_all=True, bidirectional=bidirectional)
 
         # truncate the graph to the extent of the polygon
         G = truncate.truncate_graph_polygon(G, polygon, retain_all, truncate_by_edge)
```

### Comparing `osmnx-1.4.0/osmnx/io.py` & `osmnx-1.5.0/osmnx/io.py`

 * *Files 21% similar despite different names*

```diff
@@ -4,14 +4,15 @@
 from pathlib import Path
 from warnings import warn
 
 import networkx as nx
 import pandas as pd
 from shapely import wkt
 
+from . import osm_xml
 from . import settings
 from . import utils
 from . import utils_graph
 
 
 def save_graph_geopackage(G, filepath=None, encoding="utf-8", directed=False):
     """
@@ -272,14 +273,115 @@
     G = _convert_node_attr_types(G, default_node_dtypes)
     G = _convert_edge_attr_types(G, default_edge_dtypes)
 
     utils.log(f"Loaded graph with {len(G)} nodes and {len(G.edges)} edges from {source!r}")
     return G
 
 
+def save_graph_xml(
+    data,
+    filepath=None,
+    node_tags=settings.osm_xml_node_tags,
+    node_attrs=settings.osm_xml_node_attrs,
+    edge_tags=settings.osm_xml_way_tags,
+    edge_attrs=settings.osm_xml_way_attrs,
+    oneway=False,
+    merge_edges=True,
+    edge_tag_aggs=None,
+    api_version=0.6,
+    precision=6,
+):
+    """
+    Save graph to disk as an OSM-formatted XML .osm file.
+
+    This function exists only to allow serialization to the .osm file format
+    for applications that require it, and has constraints to conform to that.
+    As such, this function has a limited use case which does not include
+    saving/loading graphs for subsequent OSMnx analysis. To save/load graphs
+    to/from disk for later use in OSMnx, use the `io.save_graphml` and
+    `io.load_graphml` functions instead. To load a graph from a .osm file that
+    you have downloaded or generated elsewhere, use the `graph.graph_from_xml`
+    function.
+
+    Note: for large networks this function can take a long time to run. Before
+    using this function, make sure you configured OSMnx as described in the
+    example below when you created the graph.
+
+    Example
+    -------
+    >>> import osmnx as ox
+    >>> utn = ox.settings.useful_tags_node
+    >>> oxna = ox.settings.osm_xml_node_attrs
+    >>> oxnt = ox.settings.osm_xml_node_tags
+    >>> utw = ox.settings.useful_tags_way
+    >>> oxwa = ox.settings.osm_xml_way_attrs
+    >>> oxwt = ox.settings.osm_xml_way_tags
+    >>> utn = list(set(utn + oxna + oxnt))
+    >>> utw = list(set(utw + oxwa + oxwt))
+    >>> ox.settings.all_oneway = True
+    >>> ox.settings.useful_tags_node = utn
+    >>> ox.settings.useful_tags_way = utw
+    >>> G = ox.graph_from_place('Piedmont, CA, USA', network_type='drive')
+    >>> ox.save_graph_xml(G, filepath='./data/graph.osm')
+
+    Parameters
+    ----------
+    data : networkx multi(di)graph OR a length 2 iterable of nodes/edges
+        geopandas GeoDataFrames
+    filepath : string or pathlib.Path
+        path to the .osm file including extension. if None, use default data
+        folder + graph.osm
+    node_tags : list
+        osm node tags to include in output OSM XML
+    node_attrs: list
+        osm node attributes to include in output OSM XML
+    edge_tags : list
+        osm way tags to include in output OSM XML
+    edge_attrs : list
+        osm way attributes to include in output OSM XML
+    oneway : bool
+        the default oneway value used to fill this tag where missing
+    merge_edges : bool
+        if True merges graph edges such that each OSM way has one entry
+        and one entry only in the OSM XML. Otherwise, every OSM way
+        will have a separate entry for each node pair it contains.
+    edge_tag_aggs : list of length-2 string tuples
+        useful only if merge_edges is True, this argument allows the user
+        to specify edge attributes to aggregate such that the merged
+        OSM way entry tags accurately represent the sum total of
+        their component edge attributes. For example, if the user
+        wants the OSM way to have a "length" attribute, the user must
+        specify `edge_tag_aggs=[('length', 'sum')]` in order to tell
+        this method to aggregate the lengths of the individual
+        component edges. Otherwise, the length attribute will simply
+        reflect the length of the first edge associated with the way.
+    api_version : float
+        OpenStreetMap API version to write to the XML file header
+    precision : int
+        number of decimal places to round latitude and longitude values
+
+    Returns
+    -------
+    None
+    """
+    osm_xml._save_graph_xml(
+        data,
+        filepath,
+        node_tags,
+        node_attrs,
+        edge_tags,
+        edge_attrs,
+        oneway,
+        merge_edges,
+        edge_tag_aggs,
+        api_version,
+        precision,
+    )
+
+
 def _convert_graph_attr_types(G, dtypes=None):
     """
     Convert graph-level attributes using a dict of data types.
 
     Parameters
     ----------
     G : networkx.MultiDiGraph
```

### Comparing `osmnx-1.4.0/osmnx/osm_xml.py` & `osmnx-1.5.0/osmnx/osm_xml.py`

 * *Files 22% similar despite different names*

```diff
@@ -97,45 +97,81 @@
     oneway=False,
     merge_edges=True,
     edge_tag_aggs=None,
     api_version=0.6,
     precision=6,
 ):
     """
-    Save graph to disk as an OSM-formatted XML .osm file.
+    Do not use: deprecated.
 
-    This function exists only to allow serialization to the .osm file format
-    for applications that require it, and has constraints to conform to that.
-    As such, this function has a limited use case which does not include
-    saving/loading graphs for subsequent OSMnx analysis. To save/load graphs
-    to/from disk for later use in OSMnx, use the `io.save_graphml` and
-    `io.load_graphml` functions instead. To load a graph from a .osm file that
-    you have downloaded or generated elsewhere, use the `graph.graph_from_xml`
-    function.
-
-    Note: for large networks this function can take a long time to run. Before
-    using this function, make sure you configured OSMnx as described in the
-    example below when you created the graph.
+    Parameters
+    ----------
+    data : networkx.multidigraph
+        do not use, deprecated
+    filepath : string or pathlib.Path
+        do not use, deprecated
+    node_tags : list
+        do not use, deprecated
+    node_attrs: list
+        do not use, deprecated
+    edge_tags : list
+        do not use, deprecated
+    edge_attrs : list
+        do not use, deprecated
+    oneway : bool
+        do not use, deprecated
+    merge_edges : bool
+        do not use, deprecated
+    edge_tag_aggs : list of length-2 string tuples
+        do not use, deprecated
+    api_version : float
+        do not use, deprecated
+    precision : int
+        do not use, deprecated
 
-    Example
+    Returns
     -------
-    >>> import osmnx as ox
-    >>> utn = ox.settings.useful_tags_node
-    >>> oxna = ox.settings.osm_xml_node_attrs
-    >>> oxnt = ox.settings.osm_xml_node_tags
-    >>> utw = ox.settings.useful_tags_way
-    >>> oxwa = ox.settings.osm_xml_way_attrs
-    >>> oxwt = ox.settings.osm_xml_way_tags
-    >>> utn = list(set(utn + oxna + oxnt))
-    >>> utw = list(set(utw + oxwa + oxwt))
-    >>> ox.settings.all_oneway = True
-    >>> ox.settings.useful_tags_node = utn
-    >>> ox.settings.useful_tags_way = utw
-    >>> G = ox.graph_from_place('Piedmont, CA, USA', network_type='drive')
-    >>> ox.save_graph_xml(G, filepath='./data/graph.osm')
+    None
+    """
+    warn(
+        "The save_graph_xml has moved from the osm_xml module to the io module. "
+        " osm_xml.save_graph_xml has been deprecated and will be removed in a "
+        " future release. Access the function via the io module instead.",
+        stacklevel=2,
+    )
+    _save_graph_xml(
+        data,
+        filepath,
+        node_tags,
+        node_attrs,
+        edge_tags,
+        edge_attrs,
+        oneway,
+        merge_edges,
+        edge_tag_aggs,
+        api_version,
+        precision,
+    )
+
+
+def _save_graph_xml(
+    data,
+    filepath=None,
+    node_tags=settings.osm_xml_node_tags,
+    node_attrs=settings.osm_xml_node_attrs,
+    edge_tags=settings.osm_xml_way_tags,
+    edge_attrs=settings.osm_xml_way_attrs,
+    oneway=False,
+    merge_edges=True,
+    edge_tag_aggs=None,
+    api_version=0.6,
+    precision=6,
+):
+    """
+    Save graph to disk as an OSM-formatted XML .osm file.
 
     Parameters
     ----------
     data : networkx multi(di)graph OR a length 2 iterable of nodes/edges
         geopandas GeoDataFrames
     filepath : string or pathlib.Path
         path to the .osm file including extension. if None, use default data
@@ -180,16 +216,16 @@
         filepath = Path(filepath)
 
     # if save folder does not already exist, create it
     filepath.parent.mkdir(parents=True, exist_ok=True)
 
     if not settings.all_oneway:  # pragma: no cover
         warn(
-            "In order for save_graph_xml to behave properly the graph must "
-            "have been created with the `all_oneway` setting set to True.",
+            "For the `save_graph_xml` function to behave properly, the graph "
+            "must have been created with `ox.settings.all_oneway=True`.",
             stacklevel=2,
         )
 
     try:
         gdf_nodes, gdf_edges = data
     except ValueError:
         gdf_nodes, gdf_edges = utils_graph.graph_to_gdfs(
@@ -207,15 +243,15 @@
         gdf_edges = gdf_edges.rename(columns={"uniqueid": "id"})
     else:
         gdf_edges = gdf_edges.reset_index().reset_index().rename(columns={"index": "id"})
 
     # add default values for required attributes
     for table in (gdf_nodes, gdf_edges):
         table["uid"] = "1"
-        table["user"] = "osmnx"
+        table["user"] = "OSMnx"
         table["version"] = "1"
         table["changeset"] = "1"
         table["timestamp"] = utils.ts(template="{:%Y-%m-%dT%H:%M:%SZ}")
 
     # misc. string replacements to meet OSM XML spec
     if "oneway" in gdf_edges.columns:
         # fill blank oneway tags with default (False)
@@ -263,14 +299,122 @@
 
         for tag in node_tags:
             if tag in row:
                 etree.SubElement(node, "tag", attrib={"k": tag, "v": row[tag]})
     return root
 
 
+def _create_way_for_each_edge(root, gdf_edges, edge_attrs, edge_tags):
+    """
+    Append a new way to an empty XML tree graph for each edge in way.
+
+    This will generate separate OSM ways for each network edge, even if the
+    edges are all part of the same original OSM way. As such, each way will be
+    composed of two nodes, and there will be many ways with the same OSM ID.
+    This does not conform to the OSM XML schema standard, but the data will
+    still comprise a valid network and will be readable by most OSM tools.
+
+    Parameters
+    ----------
+    root : ElementTree.Element
+        an empty XML tree
+    gdf_edges : geopandas.GeoDataFrame
+        GeoDataFrame of graph edges
+    edge_attrs : list
+        osm way attributes to include in output OSM XML
+    edge_tags : list
+        osm way tags to include in output OSM XML
+    """
+    for _, row in gdf_edges.iterrows():
+        row = row.dropna().astype(str)
+        edge = etree.SubElement(root, "way", attrib=row[edge_attrs].to_dict())
+        etree.SubElement(edge, "nd", attrib={"ref": row["u"]})
+        etree.SubElement(edge, "nd", attrib={"ref": row["v"]})
+        for tag in edge_tags:
+            if tag in row:
+                etree.SubElement(edge, "tag", attrib={"k": tag, "v": row[tag]})
+    return
+
+
+def _append_merged_edge_attrs(xml_edge, sample_edge, all_edges_df, edge_tags, edge_tag_aggs):
+    """
+    Extract edge attributes and append to XML edge.
+
+    Parameters
+    ----------
+    xml_edge : ElementTree.SubElement
+        XML representation of an output graph edge
+    sample_edge: pandas.Series
+        sample row from the the dataframe of way edges
+    all_edges_df: pandas.DataFrame
+        a dataframe with one row for each edge in an OSM way
+    edge_tags : list
+        osm way tags to include in output OSM XML
+    edge_tag_aggs : list of length-2 string tuples
+        useful only if merge_edges is True, this argument allows the user to
+        specify edge attributes to aggregate such that the merged OSM way
+        entry tags accurately represent the sum total of their component edge
+        attributes. For example if the user wants the OSM way to have a length
+        attribute, the user must specify `edge_tag_aggs=[('length', 'sum')]`
+        to tell this method to aggregate the lengths of the individual
+        component edges. Otherwise, the length attribute will simply reflect
+        the length of the first edge associated with the way.
+
+    """
+    if edge_tag_aggs is None:
+        for tag in edge_tags:
+            if tag in sample_edge:
+                etree.SubElement(xml_edge, "tag", attrib={"k": tag, "v": sample_edge[tag]})
+    else:
+        for tag in edge_tags:
+            if (tag in sample_edge) and (tag not in (t for t, agg in edge_tag_aggs)):
+                etree.SubElement(xml_edge, "tag", attrib={"k": tag, "v": sample_edge[tag]})
+
+        for tag, agg in edge_tag_aggs:
+            if tag in all_edges_df.columns:
+                etree.SubElement(
+                    xml_edge,
+                    "tag",
+                    attrib={
+                        "k": tag,
+                        "v": str(all_edges_df[tag].aggregate(agg)),
+                    },
+                )
+    return
+
+
+def _append_nodes_as_edge_attrs(xml_edge, sample_edge, all_edges_df):
+    """
+    Extract list of ordered nodes and append as attributes of XML edge.
+
+    Parameters
+    ----------
+    xml_edge : ElementTree.SubElement
+        XML representation of an output graph edge
+    sample_edge: pandas.Series
+        sample row from the the dataframe of way edges
+    all_edges_df: pandas.DataFrame
+        a dataframe with one row for each edge in an OSM way
+    """
+    if len(all_edges_df) == 1:
+        etree.SubElement(xml_edge, "nd", attrib={"ref": sample_edge["u"]})
+        etree.SubElement(xml_edge, "nd", attrib={"ref": sample_edge["v"]})
+    else:
+        # topological sort
+        try:
+            ordered_nodes = _get_unique_nodes_ordered_from_way(all_edges_df)
+        except nx.NetworkXUnfeasible:
+            first_node = all_edges_df.iloc[0]["u"]
+            ordered_nodes = _get_unique_nodes_ordered_from_way(all_edges_df.iloc[1:])
+            ordered_nodes = [first_node] + ordered_nodes
+        for node in ordered_nodes:
+            etree.SubElement(xml_edge, "nd", attrib={"ref": str(node)})
+    return
+
+
 def _append_edges_xml_tree(root, gdf_edges, edge_attrs, edge_tags, edge_tag_aggs, merge_edges):
     """
     Append edges to an XML tree.
 
     Parameters
     ----------
     root : ElementTree.Element
@@ -295,90 +439,66 @@
         if True merges graph edges such that each OSM way has one entry
         and one entry only in the OSM XML. Otherwise, every OSM way
         will have a separate entry for each node pair it contains.
 
     Returns
     -------
     root : ElementTree.Element
-        xml tree with edges appended
+        XML tree with edges appended
     """
     gdf_edges.reset_index(inplace=True)
     if merge_edges:
         for _, all_way_edges in gdf_edges.groupby("id"):
             first = all_way_edges.iloc[0].dropna().astype(str)
             edge = etree.SubElement(root, "way", attrib=first[edge_attrs].dropna().to_dict())
+            _append_nodes_as_edge_attrs(
+                xml_edge=edge, sample_edge=first, all_edges_df=all_way_edges
+            )
+            _append_merged_edge_attrs(
+                xml_edge=edge,
+                sample_edge=first,
+                edge_tags=edge_tags,
+                edge_tag_aggs=edge_tag_aggs,
+                all_edges_df=all_way_edges,
+            )
 
-            if len(all_way_edges) == 1:
-                etree.SubElement(edge, "nd", attrib={"ref": first["u"]})
-                etree.SubElement(edge, "nd", attrib={"ref": first["v"]})
-            else:
-                # topological sort
-                ordered_nodes = _get_unique_nodes_ordered_from_way(all_way_edges)
-                for node in ordered_nodes:
-                    etree.SubElement(edge, "nd", attrib={"ref": str(node)})
-
-            if edge_tag_aggs is None:
-                for tag in edge_tags:
-                    if tag in first:
-                        etree.SubElement(edge, "tag", attrib={"k": tag, "v": first[tag]})
-            else:
-                for tag in edge_tags:
-                    if (tag in first) and (tag not in (t for t, agg in edge_tag_aggs)):
-                        etree.SubElement(edge, "tag", attrib={"k": tag, "v": first[tag]})
-
-                for tag, agg in edge_tag_aggs:
-                    if tag in all_way_edges.columns:
-                        etree.SubElement(
-                            edge,
-                            "tag",
-                            attrib={"k": tag, "v": str(all_way_edges[tag].aggregate(agg))},
-                        )
     else:
-        # NOTE: this will generate separate OSM ways for each network edge,
-        # even if the edges are all part of the same original OSM way. As
-        # such, each way will be comprised of two nodes, and there will be
-        # many ways with the same OSM id. This does not conform to the
-        # OSM XML schema standard, however, the data will still comprise a
-        # valid network and will be readable by *most* OSM tools.
-        for _, row in gdf_edges.iterrows():
-            row = row.dropna().astype(str)
-            edge = etree.SubElement(root, "way", attrib=row[edge_attrs].to_dict())
-            etree.SubElement(edge, "nd", attrib={"ref": row["u"]})
-            etree.SubElement(edge, "nd", attrib={"ref": row["v"]})
-            for tag in edge_tags:
-                if tag in row:
-                    etree.SubElement(edge, "tag", attrib={"k": tag, "v": row[tag]})
+        _create_way_for_each_edge(
+            root=root,
+            gdf_edges=gdf_edges,
+            edge_attrs=edge_attrs,
+            edge_tags=edge_tags,
+        )
 
     return root
 
 
 def _get_unique_nodes_ordered_from_way(df_way_edges):
     """
-    Recover original node order from df of edges associated w/ single OSM way.
+    Recover original node order from edges associated with a single OSM way.
 
     Parameters
     ----------
     df_way_edges : pandas.DataFrame
         Dataframe containing columns 'u' and 'v' corresponding to
         origin/destination nodes.
 
     Returns
     -------
     unique_ordered_nodes : list
-        An ordered list of unique node IDs.
-        Note: If the edges do not all connect (e.g. [(1, 2), (2,3),
-        (10, 11), (11, 12), (12, 13)]), then this method will return
-        only those nodes associated with the largest component of
-        connected edges, even if subsequent connected chunks are contain
-        more total nodes. This is done to ensure a proper topological
-        representation of nodes in the XML way records because if there
-        are unconnected components, the sorting algorithm cannot recover
-        their original order. We would not likely ever encounter this
-        kind of disconnected structure of nodes within a given way, but
-        it is not explicitly forbidden in the OSM XML design schema.
+        An ordered list of unique node IDs. If the edges do not all connect
+        (e.g. [(1, 2), (2,3), (10, 11), (11, 12), (12, 13)]), then this method
+        will return only those nodes associated with the largest component of
+        connected edges, even if subsequent connected chunks are contain more
+        total nodes. This ensures a proper topological representation of nodes
+        in the XML way records because if there are unconnected components,
+        the sorting algorithm cannot recover their original order. We would
+        not likely ever encounter this kind of disconnected structure of nodes
+        within a given way, but it is not explicitly forbidden in the OSM XML
+        design schema.
     """
     G = nx.MultiDiGraph()
     df_way_edges.reset_index(inplace=True)
     all_nodes = list(df_way_edges["u"].values) + list(df_way_edges["v"].values)
 
     G.add_nodes_from(all_nodes)
     G.add_edges_from(df_way_edges[["u", "v"]].values)
```

### Comparing `osmnx-1.4.0/osmnx/plot.py` & `osmnx-1.5.0/osmnx/plot.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-"""Visualize spatial footprints, street networks, routes, and orientations."""
+"""Visualize street networks, routes, orientations, and geospatial features."""
 
 from pathlib import Path
 
 import networkx as nx
 import numpy as np
 import pandas as pd
 
@@ -583,15 +583,15 @@
     save=False,
     show=True,
     close=False,
     filepath=None,
     dpi=600,
 ):
     """
-    Visualize a GeoDataFrame of geospatial entities' footprints.
+    Visualize a GeoDataFrame of geospatial features' footprints.
 
     Parameters
     ----------
     gdf : geopandas.GeoDataFrame
         GeoDataFrame of footprints (shapely Polygons and MultiPolygons)
     ax : axis
         if not None, plot on this preexisting axis
```

### Comparing `osmnx-1.4.0/osmnx/projection.py` & `osmnx-1.5.0/osmnx/projection.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-"""Project spatial geometries and spatial networks."""
+"""Reproject a graph, GeoDataFrame, or geometry to a different CRS."""
 
 import geopandas as gpd
 import numpy as np
 
 from . import settings
 from . import utils
 from . import utils_graph
```

### Comparing `osmnx-1.4.0/osmnx/settings.py` & `osmnx-1.5.0/osmnx/settings.py`

 * *Files identical despite different names*

### Comparing `osmnx-1.4.0/osmnx/simplification.py` & `osmnx-1.5.0/osmnx/simplification.py`

 * *Files 0% similar despite different names*

```diff
@@ -175,15 +175,15 @@
         but have edges with different OSM IDs
 
     Yields
     ------
     path_to_simplify : list
     """
     # first identify all the nodes that are endpoints
-    endpoints = set([n for n in G.nodes if _is_endpoint(G, n, strict=strict)])
+    endpoints = {n for n in G.nodes if _is_endpoint(G, n, strict=strict)}
     utils.log(f"Identified {len(endpoints)} edge endpoints")
 
     # for each endpoint node, look at each of its successor nodes
     for endpoint in endpoints:
         for successor in G.successors(endpoint):
             if successor not in endpoints:
                 # if endpoint node's successor is not an endpoint, build path
```

### Comparing `osmnx-1.4.0/osmnx/speed.py` & `osmnx-1.5.0/osmnx/speed.py`

 * *Files identical despite different names*

### Comparing `osmnx-1.4.0/osmnx/stats.py` & `osmnx-1.5.0/osmnx/stats.py`

 * *Files identical despite different names*

### Comparing `osmnx-1.4.0/osmnx/truncate.py` & `osmnx-1.5.0/osmnx/truncate.py`

 * *Files identical despite different names*

### Comparing `osmnx-1.4.0/osmnx/utils.py` & `osmnx-1.5.0/osmnx/utils.py`

 * *Files identical despite different names*

### Comparing `osmnx-1.4.0/osmnx/utils_geo.py` & `osmnx-1.5.0/osmnx/utils_geo.py`

 * *Files identical despite different names*

### Comparing `osmnx-1.4.0/osmnx/utils_graph.py` & `osmnx-1.5.0/osmnx/utils_graph.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,14 @@
 """Graph utility functions."""
 
 import itertools
 from warnings import warn
 
 import geopandas as gpd
 import networkx as nx
-import numpy as np
 import pandas as pd
 from shapely.geometry import LineString
 from shapely.geometry import Point
 
 from . import utils
 
 
@@ -65,30 +64,29 @@
 
         if fill_edge_geometry:
             # subroutine to get geometry for every edge: if edge already has
             # geometry return it, otherwise create it using the incident nodes
             x_lookup = nx.get_node_attributes(G, "x")
             y_lookup = nx.get_node_attributes(G, "y")
 
-            def make_geom(u, v, data, x=x_lookup, y=y_lookup):
+            def _make_geom(u, v, data, x=x_lookup, y=y_lookup):
                 if "geometry" in data:
                     return data["geometry"]
                 else:
                     return LineString((Point((x[u], y[u])), Point((x[v], y[v]))))
 
-            geom = map(make_geom, u, v, data)
+            geom = map(_make_geom, u, v, data)
             gdf_edges = gpd.GeoDataFrame(data, crs=crs, geometry=list(geom))
 
         else:
             gdf_edges = gpd.GeoDataFrame(data)
             if "geometry" not in gdf_edges.columns:
                 # if no edges have a geometry attribute, create null column
-                gdf_edges["geometry"] = np.nan
-            gdf_edges.set_geometry("geometry")
-            gdf_edges.crs = crs
+                gdf_edges = gdf_edges.set_geometry([None] * len(gdf_edges))
+            gdf_edges = gdf_edges.set_crs(crs)
 
         # add u, v, key attributes as index
         gdf_edges["u"] = u
         gdf_edges["v"] = v
         gdf_edges["key"] = k
         gdf_edges.set_index(["u", "v", "key"], inplace=True)
```

### Comparing `osmnx-1.4.0/tests/test_osmnx.py` & `osmnx-1.5.0/tests/test_osmnx.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,23 +1,22 @@
-"""Unit tests for the package."""
+"""Test suite for the package."""
 
 # use agg backend so you don't need a display on ci
 # do this first before pyplot is imported by anything
 import matplotlib as mpl
 
-from osmnx.speed import _clean_maxspeed
-
 mpl.use("Agg")
 
 import bz2
 import logging as lg
 import os
 import tempfile
 from collections import OrderedDict
 from pathlib import Path
+from xml.etree import ElementTree as etree
 
 import folium
 import geopandas as gpd
 import networkx as nx
 import numpy as np
 import pandas as pd
 import pytest
@@ -27,15 +26,14 @@
 from shapely.geometry import MultiPoint
 from shapely.geometry import MultiPolygon
 from shapely.geometry import Point
 from shapely.geometry import Polygon
 
 import osmnx as ox
 
-
 ox.config(log_console=True)
 ox.settings.log_console = True
 ox.settings.log_file = True
 ox.settings.use_cache = True
 ox.settings.data_folder = ".temp/data"
 ox.settings.logs_folder = ".temp/logs"
 ox.settings.imgs_folder = ".temp/imgs"
@@ -174,21 +172,35 @@
     ox.save_graph_xml(G, merge_edges=False, filepath=Path(ox.settings.data_folder) / "graph.osm")
 
     # test osm xml output merge edges
     ox.save_graph_xml(G, merge_edges=True, edge_tag_aggs=[("length", "sum")])
 
     # test osm xml output from gdfs
     nodes, edges = ox.graph_to_gdfs(G)
-    ox.save_graph_xml([nodes, edges])
+    ox.osm_xml.save_graph_xml([nodes, edges])
 
     # test ordered nodes from way
     df = pd.DataFrame({"u": [54, 2, 5, 3, 10, 19, 20], "v": [76, 3, 8, 10, 5, 20, 15]})
     ordered_nodes = ox.osm_xml._get_unique_nodes_ordered_from_way(df)
     assert ordered_nodes == [2, 3, 10, 5, 8]
 
+    # test roundabout handling
+    default_overpass_settings = ox.settings.overpass_settings
+    ox.settings.overpass_settings += '[date:"2023-04-01T00:00:00Z"]'
+    point = (39.0290346, -84.4696884)
+    G = ox.graph_from_point(point, dist=500, dist_type="bbox", network_type="drive", simplify=False)
+    gdf_edges = ox.graph_to_gdfs(G, nodes=False)
+    gdf_way = gdf_edges[gdf_edges["osmid"] == 570883705]  # roundabout
+    first = gdf_way.iloc[0].dropna().astype(str)
+    root = etree.Element("osm", attrib={"version": "0.6", "generator": "OSMnx"})
+    edge = etree.SubElement(root, "way")
+    ox.osm_xml._append_nodes_as_edge_attrs(edge, first, gdf_way)
+
+    # restore settings
+    ox.settings.overpass_settings = default_overpass_settings
     ox.settings.all_oneway = default_all_oneway
 
 
 def test_elevation():
     G = ox.graph_from_address(address=address, dist=500, dist_type="bbox", network_type="bike")
     rasters = list(Path("tests/input_data").glob("elevation*.tif"))
 
@@ -210,22 +222,22 @@
     # give each edge speed and travel time attributes
     G = ox.add_edge_speeds(G)
     G = ox.add_edge_speeds(G, hwy_speeds={"motorway": 100}, precision=2)
     G = ox.add_edge_travel_times(G)
     G = ox.add_edge_travel_times(G, precision=2)
 
     # test value cleaning
-    assert _clean_maxspeed("100,2") == 100.2
-    assert _clean_maxspeed("100.2") == 100.2
-    assert _clean_maxspeed("100 km/h") == 100.0
-    assert _clean_maxspeed("100 mph") == pytest.approx(160.934)
-    assert _clean_maxspeed("60|100") == 80
-    assert _clean_maxspeed("60|100 mph") == pytest.approx(128.7472)
-    assert _clean_maxspeed("signal") is None
-    assert _clean_maxspeed("100;70") is None
+    assert ox.speed._clean_maxspeed("100,2") == 100.2
+    assert ox.speed._clean_maxspeed("100.2") == 100.2
+    assert ox.speed._clean_maxspeed("100 km/h") == 100.0
+    assert ox.speed._clean_maxspeed("100 mph") == pytest.approx(160.934)
+    assert ox.speed._clean_maxspeed("60|100") == 80
+    assert ox.speed._clean_maxspeed("60|100 mph") == pytest.approx(128.7472)
+    assert ox.speed._clean_maxspeed("signal") is None
+    assert ox.speed._clean_maxspeed("100;70") is None
 
     orig_x = np.array([-122.404771])
     dest_x = np.array([-122.401429])
     orig_y = np.array([37.794302])
     dest_y = np.array([37.794987])
     orig_node = ox.distance.nearest_nodes(G, orig_x, orig_y)[0]
     dest_node = ox.distance.nearest_nodes(G, dest_x, dest_y)[0]
@@ -324,56 +336,56 @@
 
     # get nearest edge
     ne0 = ox.distance.nearest_edges(Gp, X[0], Y[0], interpolate=None)
     ne1 = ox.distance.nearest_edges(Gp, X[0], Y[0], interpolate=50)
     ne2 = ox.distance.nearest_edges(G, X[0], Y[0], interpolate=50, return_dist=True)
 
 
-def test_api_endpoints():
-    ip = ox.downloader._resolve_host_via_doh("overpass-api.de")
-    ip = ox.downloader._resolve_host_via_doh("AAAAAAAAAAA")
+def test_endpoints():
+    ip = ox._downloader._resolve_host_via_doh("overpass-api.de")
+    ip = ox._downloader._resolve_host_via_doh("AAAAAAAAAAA")
 
     _doh_url_template_default = ox.settings.doh_url_template
     ox.settings.doh_url_template = "http://aaaaaa.hostdoesntexist.org/nothinguseful"
-    ip = ox.downloader._resolve_host_via_doh("overpass-api.de")
+    ip = ox._downloader._resolve_host_via_doh("overpass-api.de")
     ox.settings.doh_url_template = None
-    ip = ox.downloader._resolve_host_via_doh("overpass-api.de")
+    ip = ox._downloader._resolve_host_via_doh("overpass-api.de")
     ox.settings.doh_url_template = _doh_url_template_default
 
     params = OrderedDict()
     params["format"] = "json"
     params["address_details"] = 0
 
     # Bad Address - should return an empty response
     params["q"] = "AAAAAAAAAAA"
-    response_json = ox.downloader.nominatim_request(params=params, request_type="search")
+    response_json = ox._downloader._nominatim_request(params=params, request_type="search")
 
     # Good Address - should return a valid response with a valid osm_id
     params["q"] = "Newcastle A186 Westgate Rd"
-    response_json = ox.downloader.nominatim_request(params=params, request_type="search")
+    response_json = ox._downloader._nominatim_request(params=params, request_type="search")
 
     # Lookup
     params = OrderedDict()
     params["format"] = "json"
     params["address_details"] = 0
     params["osm_ids"] = "W68876073"
 
-    response_json = ox.downloader.nominatim_request(params=params, request_type="lookup")
+    response_json = ox._downloader._nominatim_request(params=params, request_type="lookup")
 
     # Invalid nominatim query type
     with pytest.raises(ValueError):
-        response_json = ox.downloader.nominatim_request(params=params, request_type="xyz")
+        response_json = ox._downloader._nominatim_request(params=params, request_type="xyz")
 
     default_key = ox.settings.nominatim_key
     default_nominatim_endpoint = ox.settings.nominatim_endpoint
     default_overpass_endpoint = ox.settings.overpass_endpoint
 
     # Searching on public nominatim should work even if a key was provided
     ox.settings.nominatim_key = "NOT_A_KEY"
-    response_json = ox.downloader.nominatim_request(params=params, request_type="search")
+    response_json = ox._downloader._nominatim_request(params=params, request_type="search")
 
     # Test changing the endpoint.
     # This should fail because we didn't provide a valid endpoint
     ox.settings.overpass_endpoint = "http://NOT_A_VALID_ENDPOINT/api/"
     with pytest.raises(Exception) as ex:
         G = ox.graph_from_place(place1, network_type="all")
 
@@ -491,15 +503,15 @@
         location_point,
         dist=500,
         dist_type="network",
         network_type="all_private",
     )
 
 
-def test_geometries():
+def test_features():
     # geometries_from_bbox - bounding box query to return no data
     try:
         gdf = ox.geometries_from_bbox(0.009, -0.009, 0.009, -0.009, tags={"building": True})
     except ox._errors.EmptyOverpassResponse:
         pass
 
     # geometries_from_bbox - successful
@@ -513,14 +525,18 @@
     gdf = ox.geometries_from_point((48.15, 10.02), tags={"landuse": True}, dist=2000)
 
     # geometries_from_place - includes test of list of places
     tags = {"amenity": True, "landuse": ["retail", "commercial"], "highway": "bus_stop"}
     gdf = ox.geometries_from_place(place1, tags=tags)
     gdf = ox.geometries_from_place([place1], tags=tags)
 
+    # geometries_from_polygon
+    polygon = ox.geocode_to_gdf(place1).geometry.iloc[0]
+    ox.geometries_from_polygon(polygon, tags)
+
     # geometries_from_address - includes testing overpass settings and snapshot from 2019
     ox.settings.overpass_settings = '[out:json][timeout:200][date:"2019-10-28T19:20:00Z"]'
     gdf = ox.geometries_from_address(address, tags=tags)
 
     # geometries_from_xml - tests error handling of clipped XMLs with incomplete geometry
     gdf = ox.geometries_from_xml("tests/input_data/planet_10.068,48.135_10.071,48.137.osm")
```


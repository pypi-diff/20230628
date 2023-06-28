# Comparing `tmp/osdatahub-1.2.5.tar.gz` & `tmp/osdatahub-1.2.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "osdatahub-1.2.5.tar", last modified: Wed May 17 08:44:58 2023, max compression
+gzip compressed data, was "osdatahub-1.2.6.tar", last modified: Wed Jun 28 14:27:38 2023, max compression
```

## Comparing `osdatahub-1.2.5.tar` & `osdatahub-1.2.6.tar`

### file list

```diff
@@ -1,132 +1,132 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.445498 osdatahub-1.2.5/
--rw-r--r--   0 runner    (1001) docker     (123)      744 2023-05-17 08:44:28.000000 osdatahub-1.2.5/.readthedocs.yaml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.417498 osdatahub-1.2.5/Examples/
--rw-r--r--   0 runner    (1001) docker     (123)     5693 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/CRS pitfalls.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)   231081 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/Converting API Results into Common Data Formats.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)  1837789 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/Defining Extents for API Queries.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    12538 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/Filtering Attributes for API Queries.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    10298 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/Interactive Plotting for API Results - Folium.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)   945983 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/Plotting API Results - GeoPandas, Matplotlib and Contextily.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    34430 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/Post Processing API Queries.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)     9597 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/Quick Start Guide.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)     5611 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/Setting up an API key.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    86367 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/Using the NGD Features API.ipynb
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.425498 osdatahub-1.2.5/Examples/images/
--rw-r--r--   0 runner    (1001) docker     (123)  2124067 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/images/1_homescreen.PNG
--rw-r--r--   0 runner    (1001) docker     (123)   178174 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/images/2_sign_up.PNG
--rw-r--r--   0 runner    (1001) docker     (123)  1883255 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/images/3_datahub_homepage.PNG
--rw-r--r--   0 runner    (1001) docker     (123)   115385 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/images/4_new_project.PNG
--rw-r--r--   0 runner    (1001) docker     (123)   153664 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/images/5_add_api_to_project.PNG
--rw-r--r--   0 runner    (1001) docker     (123)   113078 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/images/6_view_api_key.PNG
--rw-r--r--   0 runner    (1001) docker     (123)  1790610 2023-05-17 08:44:28.000000 osdatahub-1.2.5/Examples/images/CRS.png
--rw-r--r--   0 runner    (1001) docker     (123)    33604 2023-05-17 08:44:28.000000 osdatahub-1.2.5/LICENSE.txt
--rw-r--r--   0 runner    (1001) docker     (123)      377 2023-05-17 08:44:28.000000 osdatahub-1.2.5/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)    15127 2023-05-17 08:44:58.445498 osdatahub-1.2.5/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)    13892 2023-05-17 08:44:28.000000 osdatahub-1.2.5/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.429498 osdatahub-1.2.5/docs/
--rw-r--r--   0 runner    (1001) docker     (123)      379 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/DownloadsAPI.rst
--rw-r--r--   0 runner    (1001) docker     (123)      182 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/Extent.rst
--rw-r--r--   0 runner    (1001) docker     (123)      391 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/FeaturesAPI.rst
--rw-r--r--   0 runner    (1001) docker     (123)      250 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/LinkedIdentifiersAPI.rst
--rw-r--r--   0 runner    (1001) docker     (123)      186 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/NGD.rst
--rw-r--r--   0 runner    (1001) docker     (123)      200 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/NamesAPI.rst
--rw-r--r--   0 runner    (1001) docker     (123)      204 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/PlacesAPI.rst
--rw-r--r--   0 runner    (1001) docker     (123)      798 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/Utilities.rst
--rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/conf.py
--rw-r--r--   0 runner    (1001) docker     (123)     1087 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/index.rst
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.429498 osdatahub-1.2.5/docs/media/
--rw-r--r--   0 runner    (1001) docker     (123)    23309 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/media/os-logo.png
--rw-r--r--   0 runner    (1001) docker     (123)       79 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/readme_link.rst
--rw-r--r--   0 runner    (1001) docker     (123)       36 2023-05-17 08:44:28.000000 osdatahub-1.2.5/docs/requirements.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.429498 osdatahub-1.2.5/media/
--rw-r--r--   0 runner    (1001) docker     (123)    23309 2023-05-17 08:44:28.000000 osdatahub-1.2.5/media/os-logo.png
--rw-r--r--   0 runner    (1001) docker     (123)       90 2023-05-17 08:44:28.000000 osdatahub-1.2.5/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       96 2023-05-17 08:44:28.000000 osdatahub-1.2.5/requirements.txt
--rw-r--r--   0 runner    (1001) docker     (123)     1588 2023-05-17 08:44:58.445498 osdatahub-1.2.5/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)       69 2023-05-17 08:44:28.000000 osdatahub-1.2.5/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.401497 osdatahub-1.2.5/src/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.433498 osdatahub-1.2.5/src/osdatahub/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.433498 osdatahub-1.2.5/src/osdatahub/DownloadsAPI/
--rw-r--r--   0 runner    (1001) docker     (123)       85 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/DownloadsAPI/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5023 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/DownloadsAPI/data_package.py
--rw-r--r--   0 runner    (1001) docker     (123)     6828 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/DownloadsAPI/downloads_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     4753 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/DownloadsAPI/opendata.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.433498 osdatahub-1.2.5/src/osdatahub/FeaturesAPI/
--rw-r--r--   0 runner    (1001) docker     (123)       59 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/FeaturesAPI/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     9627 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/FeaturesAPI/feature_products.py
--rw-r--r--   0 runner    (1001) docker     (123)     5871 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/FeaturesAPI/features_api.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.437498 osdatahub-1.2.5/src/osdatahub/LinkedIdentifiersAPI/
--rw-r--r--   0 runner    (1001) docker     (123)       87 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/LinkedIdentifiersAPI/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1247 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/LinkedIdentifiersAPI/linked_identifier_options.py
--rw-r--r--   0 runner    (1001) docker     (123)     3583 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/LinkedIdentifiersAPI/linked_identifiers_api.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.437498 osdatahub-1.2.5/src/osdatahub/NGD/
--rw-r--r--   0 runner    (1001) docker     (123)       24 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/NGD/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1841 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/NGD/crs.py
--rw-r--r--   0 runner    (1001) docker     (123)     8966 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/NGD/ngd_api.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.437498 osdatahub-1.2.5/src/osdatahub/NamesAPI/
--rw-r--r--   0 runner    (1001) docker     (123)       50 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/NamesAPI/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     5022 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/NamesAPI/local_types.py
--rw-r--r--   0 runner    (1001) docker     (123)     7265 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/NamesAPI/names_api.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.437498 osdatahub-1.2.5/src/osdatahub/PlacesAPI/
--rw-r--r--   0 runner    (1001) docker     (123)       53 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/PlacesAPI/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    15066 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/PlacesAPI/places_api.py
--rw-r--r--   0 runner    (1001) docker     (123)      638 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      871 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/bbox.py
--rw-r--r--   0 runner    (1001) docker     (123)     1365 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/codes.py
--rw-r--r--   0 runner    (1001) docker     (123)     1878 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/errors.py
--rw-r--r--   0 runner    (1001) docker     (123)     6523 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/extent.py
--rw-r--r--   0 runner    (1001) docker     (123)    11945 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/filters.py
--rw-r--r--   0 runner    (1001) docker     (123)     1319 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/grow_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     1485 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/ons_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     2097 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/requests_wrapper.py
--rw-r--r--   0 runner    (1001) docker     (123)      898 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/spatial_filter_types.py
--rw-r--r--   0 runner    (1001) docker     (123)     7698 2023-05-17 08:44:28.000000 osdatahub-1.2.5/src/osdatahub/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.433498 osdatahub-1.2.5/src/osdatahub.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)    15127 2023-05-17 08:44:58.000000 osdatahub-1.2.5/src/osdatahub.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     3753 2023-05-17 08:44:58.000000 osdatahub-1.2.5/src/osdatahub.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-05-17 08:44:58.000000 osdatahub-1.2.5/src/osdatahub.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      250 2023-05-17 08:44:58.000000 osdatahub-1.2.5/src/osdatahub.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-05-17 08:44:58.000000 osdatahub-1.2.5/src/osdatahub.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.441498 osdatahub-1.2.5/tests/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.445498 osdatahub-1.2.5/tests/data/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/__init__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.445498 osdatahub-1.2.5/tests/data/clean_polygon_data/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.445498 osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/
--rw-r--r--   0 runner    (1001) docker     (123)    29650 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon.geojson
--rw-r--r--   0 runner    (1001) docker     (123)    45345 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon2.geojson
--rw-r--r--   0 runner    (1001) docker     (123)    32875 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon_with_hole.geojson
--rw-r--r--   0 runner    (1001) docker     (123)    20201 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_polygon.geojson
--rw-r--r--   0 runner    (1001) docker     (123)     5677 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_polygon_with_hole.geojson
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-05-17 08:44:58.445498 osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/
--rw-r--r--   0 runner    (1001) docker     (123)    37512 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_multipolygon.geojson
--rw-r--r--   0 runner    (1001) docker     (123)    58496 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_multipolygon2.geojson
--rw-r--r--   0 runner    (1001) docker     (123)    33032 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_multipolygon_with_hole.geojson
--rw-r--r--   0 runner    (1001) docker     (123)    25361 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_polygon.geojson
--rw-r--r--   0 runner    (1001) docker     (123)     7232 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_polygon_with_hole.geojson
--rw-r--r--   0 runner    (1001) docker     (123)     3319 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data/get_uncleaned_polygons.py
--rw-r--r--   0 runner    (1001) docker     (123)     3033 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/clean_polygon_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     3039 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/downloads_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     5671 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/extent_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     7737 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/features_api_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     4276 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/filters_data.py
--rw-r--r--   0 runner    (1001) docker     (123)      882 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/linked_identifiers_api_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     8618 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/names_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     1616 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/ngd_crs_data.py
--rw-r--r--   0 runner    (1001) docker     (123)    24199 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/ngd_merge_geojsons_data.py
--rw-r--r--   0 runner    (1001) docker     (123)    12866 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/ngd_query_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     1175 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/places_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     4594 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/data/utils_data.py
--rw-r--r--   0 runner    (1001) docker     (123)     3170 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/run_functions.py
--rw-r--r--   0 runner    (1001) docker     (123)      365 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_clean_polygon.py
--rw-r--r--   0 runner    (1001) docker     (123)     4683 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_downloads_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     2799 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_extent.py
--rw-r--r--   0 runner    (1001) docker     (123)     1748 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_features_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     1287 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_filters.py
--rw-r--r--   0 runner    (1001) docker     (123)      702 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_grow_list.py
--rw-r--r--   0 runner    (1001) docker     (123)     1601 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_linked_identifiers_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     2897 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_names_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     5604 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_ngd.py
--rw-r--r--   0 runner    (1001) docker     (123)     1176 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_places_api.py
--rw-r--r--   0 runner    (1001) docker     (123)     1045 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tests/test_utils.py
--rw-r--r--   0 runner    (1001) docker     (123)      323 2023-05-17 08:44:28.000000 osdatahub-1.2.5/tox.ini
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.840973 osdatahub-1.2.6/
+-rw-r--r--   0 runner    (1001) docker     (123)      744 2023-06-28 14:27:07.000000 osdatahub-1.2.6/.readthedocs.yaml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.816973 osdatahub-1.2.6/Examples/
+-rw-r--r--   0 runner    (1001) docker     (123)     5693 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/CRS pitfalls.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)   231081 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/Converting API Results into Common Data Formats.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)  1837789 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/Defining Extents for API Queries.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    12538 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/Filtering Attributes for API Queries.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    10298 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/Interactive Plotting for API Results - Folium.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)   945983 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/Plotting API Results - GeoPandas, Matplotlib and Contextily.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    34430 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/Post Processing API Queries.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     9597 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/Quick Start Guide.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     5611 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/Setting up an API key.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    86367 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/Using the NGD Features API.ipynb
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.820973 osdatahub-1.2.6/Examples/images/
+-rw-r--r--   0 runner    (1001) docker     (123)  2124067 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/images/1_homescreen.PNG
+-rw-r--r--   0 runner    (1001) docker     (123)   178174 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/images/2_sign_up.PNG
+-rw-r--r--   0 runner    (1001) docker     (123)  1883255 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/images/3_datahub_homepage.PNG
+-rw-r--r--   0 runner    (1001) docker     (123)   115385 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/images/4_new_project.PNG
+-rw-r--r--   0 runner    (1001) docker     (123)   153664 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/images/5_add_api_to_project.PNG
+-rw-r--r--   0 runner    (1001) docker     (123)   113078 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/images/6_view_api_key.PNG
+-rw-r--r--   0 runner    (1001) docker     (123)  1790610 2023-06-28 14:27:07.000000 osdatahub-1.2.6/Examples/images/CRS.png
+-rw-r--r--   0 runner    (1001) docker     (123)    33604 2023-06-28 14:27:07.000000 osdatahub-1.2.6/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      377 2023-06-28 14:27:07.000000 osdatahub-1.2.6/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)    15127 2023-06-28 14:27:38.840973 osdatahub-1.2.6/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)    13892 2023-06-28 14:27:07.000000 osdatahub-1.2.6/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.828973 osdatahub-1.2.6/docs/
+-rw-r--r--   0 runner    (1001) docker     (123)      379 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/DownloadsAPI.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      182 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/Extent.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      391 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/FeaturesAPI.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      250 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/LinkedIdentifiersAPI.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      186 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/NGD.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      200 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/NamesAPI.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      204 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/PlacesAPI.rst
+-rw-r--r--   0 runner    (1001) docker     (123)      798 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/Utilities.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     2173 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/conf.py
+-rw-r--r--   0 runner    (1001) docker     (123)      876 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/index.rst
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.828973 osdatahub-1.2.6/docs/media/
+-rw-r--r--   0 runner    (1001) docker     (123)    23309 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/media/os-logo.png
+-rw-r--r--   0 runner    (1001) docker     (123)       79 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/readme_link.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       36 2023-06-28 14:27:07.000000 osdatahub-1.2.6/docs/requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.828973 osdatahub-1.2.6/media/
+-rw-r--r--   0 runner    (1001) docker     (123)    23309 2023-06-28 14:27:07.000000 osdatahub-1.2.6/media/os-logo.png
+-rw-r--r--   0 runner    (1001) docker     (123)       90 2023-06-28 14:27:07.000000 osdatahub-1.2.6/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       98 2023-06-28 14:27:07.000000 osdatahub-1.2.6/requirements.txt
+-rw-r--r--   0 runner    (1001) docker     (123)     1588 2023-06-28 14:27:38.840973 osdatahub-1.2.6/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)       69 2023-06-28 14:27:07.000000 osdatahub-1.2.6/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.808973 osdatahub-1.2.6/src/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.828973 osdatahub-1.2.6/src/osdatahub/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.832973 osdatahub-1.2.6/src/osdatahub/DownloadsAPI/
+-rw-r--r--   0 runner    (1001) docker     (123)       85 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/DownloadsAPI/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5023 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/DownloadsAPI/data_package.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7161 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/DownloadsAPI/downloads_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4753 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/DownloadsAPI/opendata.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.832973 osdatahub-1.2.6/src/osdatahub/FeaturesAPI/
+-rw-r--r--   0 runner    (1001) docker     (123)       59 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/FeaturesAPI/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9627 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/FeaturesAPI/feature_products.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5871 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/FeaturesAPI/features_api.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.832973 osdatahub-1.2.6/src/osdatahub/LinkedIdentifiersAPI/
+-rw-r--r--   0 runner    (1001) docker     (123)       87 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/LinkedIdentifiersAPI/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1247 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/LinkedIdentifiersAPI/linked_identifier_options.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3583 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/LinkedIdentifiersAPI/linked_identifiers_api.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.832973 osdatahub-1.2.6/src/osdatahub/NGD/
+-rw-r--r--   0 runner    (1001) docker     (123)       24 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/NGD/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1841 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/NGD/crs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8966 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/NGD/ngd_api.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.832973 osdatahub-1.2.6/src/osdatahub/NamesAPI/
+-rw-r--r--   0 runner    (1001) docker     (123)       50 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/NamesAPI/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5022 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/NamesAPI/local_types.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7265 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/NamesAPI/names_api.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.832973 osdatahub-1.2.6/src/osdatahub/PlacesAPI/
+-rw-r--r--   0 runner    (1001) docker     (123)       53 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/PlacesAPI/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    15066 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/PlacesAPI/places_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)      638 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      871 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/bbox.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1365 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/codes.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1878 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/errors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6523 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/extent.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11945 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/filters.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1319 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/grow_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1485 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/ons_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2097 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/requests_wrapper.py
+-rw-r--r--   0 runner    (1001) docker     (123)      898 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/spatial_filter_types.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7698 2023-06-28 14:27:07.000000 osdatahub-1.2.6/src/osdatahub/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.828973 osdatahub-1.2.6/src/osdatahub.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)    15127 2023-06-28 14:27:38.000000 osdatahub-1.2.6/src/osdatahub.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3753 2023-06-28 14:27:38.000000 osdatahub-1.2.6/src/osdatahub.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:27:38.000000 osdatahub-1.2.6/src/osdatahub.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      250 2023-06-28 14:27:38.000000 osdatahub-1.2.6/src/osdatahub.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 14:27:38.000000 osdatahub-1.2.6/src/osdatahub.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.836973 osdatahub-1.2.6/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.836973 osdatahub-1.2.6/tests/data/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/__init__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.836973 osdatahub-1.2.6/tests/data/clean_polygon_data/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.840973 osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/
+-rw-r--r--   0 runner    (1001) docker     (123)    29650 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon.geojson
+-rw-r--r--   0 runner    (1001) docker     (123)    45345 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon2.geojson
+-rw-r--r--   0 runner    (1001) docker     (123)    32875 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon_with_hole.geojson
+-rw-r--r--   0 runner    (1001) docker     (123)    20201 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_polygon.geojson
+-rw-r--r--   0 runner    (1001) docker     (123)     5677 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_polygon_with_hole.geojson
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:27:38.840973 osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/
+-rw-r--r--   0 runner    (1001) docker     (123)    37512 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_multipolygon.geojson
+-rw-r--r--   0 runner    (1001) docker     (123)    58496 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_multipolygon2.geojson
+-rw-r--r--   0 runner    (1001) docker     (123)    33032 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_multipolygon_with_hole.geojson
+-rw-r--r--   0 runner    (1001) docker     (123)    25361 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_polygon.geojson
+-rw-r--r--   0 runner    (1001) docker     (123)     7232 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_polygon_with_hole.geojson
+-rw-r--r--   0 runner    (1001) docker     (123)     3319 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data/get_uncleaned_polygons.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3033 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/clean_polygon_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3039 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/downloads_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5671 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/extent_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7737 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/features_api_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4276 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/filters_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)      882 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/linked_identifiers_api_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8618 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/names_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1616 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/ngd_crs_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)    24199 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/ngd_merge_geojsons_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12866 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/ngd_query_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1175 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/places_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4594 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/data/utils_data.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3170 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/run_functions.py
+-rw-r--r--   0 runner    (1001) docker     (123)      365 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_clean_polygon.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4683 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_downloads_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2799 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_extent.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1748 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_features_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1287 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_filters.py
+-rw-r--r--   0 runner    (1001) docker     (123)      702 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_grow_list.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1601 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_linked_identifiers_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2897 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_names_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5604 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_ngd.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1176 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_places_api.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1045 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tests/test_utils.py
+-rw-r--r--   0 runner    (1001) docker     (123)      323 2023-06-28 14:27:07.000000 osdatahub-1.2.6/tox.ini
```

### Comparing `osdatahub-1.2.5/.readthedocs.yaml` & `osdatahub-1.2.6/.readthedocs.yaml`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/CRS pitfalls.ipynb` & `osdatahub-1.2.6/Examples/CRS pitfalls.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/Converting API Results into Common Data Formats.ipynb` & `osdatahub-1.2.6/Examples/Converting API Results into Common Data Formats.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/Defining Extents for API Queries.ipynb` & `osdatahub-1.2.6/Examples/Defining Extents for API Queries.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/Filtering Attributes for API Queries.ipynb` & `osdatahub-1.2.6/Examples/Filtering Attributes for API Queries.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/Interactive Plotting for API Results - Folium.ipynb` & `osdatahub-1.2.6/Examples/Interactive Plotting for API Results - Folium.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/Plotting API Results - GeoPandas, Matplotlib and Contextily.ipynb` & `osdatahub-1.2.6/Examples/Plotting API Results - GeoPandas, Matplotlib and Contextily.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/Post Processing API Queries.ipynb` & `osdatahub-1.2.6/Examples/Post Processing API Queries.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/Quick Start Guide.ipynb` & `osdatahub-1.2.6/Examples/Quick Start Guide.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/Setting up an API key.ipynb` & `osdatahub-1.2.6/Examples/Setting up an API key.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/Using the NGD Features API.ipynb` & `osdatahub-1.2.6/Examples/Using the NGD Features API.ipynb`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/images/1_homescreen.PNG` & `osdatahub-1.2.6/Examples/images/1_homescreen.PNG`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/images/2_sign_up.PNG` & `osdatahub-1.2.6/Examples/images/2_sign_up.PNG`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/images/3_datahub_homepage.PNG` & `osdatahub-1.2.6/Examples/images/3_datahub_homepage.PNG`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/images/4_new_project.PNG` & `osdatahub-1.2.6/Examples/images/4_new_project.PNG`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/images/5_add_api_to_project.PNG` & `osdatahub-1.2.6/Examples/images/5_add_api_to_project.PNG`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/images/6_view_api_key.PNG` & `osdatahub-1.2.6/Examples/images/6_view_api_key.PNG`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/Examples/images/CRS.png` & `osdatahub-1.2.6/Examples/images/CRS.png`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/LICENSE.txt` & `osdatahub-1.2.6/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/PKG-INFO` & `osdatahub-1.2.6/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: osdatahub
-Version: 1.2.5
+Version: 1.2.6
 Summary: osdatahub is Ordnance Survey's (OS) Python API wrapper, designed to make data from the OS Data Hub APIs readily accessible to developers.
 Home-page: https://github.com/OrdnanceSurvey/osdatahub
 Download-URL: https://pypi.org/project/osdatahub/
 Author: OS Rapid Prototyping
 Author-email: rapidprototyping@os.uk
 License: OGL
 Project-URL: Code, https://github.com/OrdnanceSurvey/osdatahub
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: osdatahub Version: 1.2.5 Summary: osdatahub is
+Metadata-Version: 2.1 Name: osdatahub Version: 1.2.6 Summary: osdatahub is
 Ordnance Survey's (OS) Python API wrapper, designed to make data from the OS
 Data Hub APIs readily accessible to developers. Home-page: https://github.com/
 OrdnanceSurvey/osdatahub Download-URL: https://pypi.org/project/osdatahub/
 Author: OS Rapid Prototyping Author-email: rapidprototyping@os.uk License: OGL
 Project-URL: Code, https://github.com/OrdnanceSurvey/osdatahub Project-URL:
 Documentation, https://osdatahub.readthedocs.io/en/latest/ Project-URL: Issues,
 https://github.com/OrdnanceSurvey/osdatahub/issues Keywords: Ordnance-
```

### Comparing `osdatahub-1.2.5/README.md` & `osdatahub-1.2.6/README.md`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/docs/Utilities.rst` & `osdatahub-1.2.6/docs/Utilities.rst`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/docs/conf.py` & `osdatahub-1.2.6/docs/conf.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/docs/index.rst` & `osdatahub-1.2.6/docs/index.rst`

 * *Files 18% similar despite different names*

```diff
@@ -1,12 +1,7 @@
-.. osdatahub documentation master file, created by
-sphinx-quickstart on Tue Nov  2 16:09:27 2021.
-You can adapt this file completely to your liking, but it should at least
-contain the root `toctree` directive.
-
 Welcome to ``osdatahub's`` documentation!
 ==========================================
 
 ``osdatahub`` is a python package from Ordnance Survey (OS), designed to make data from the OS Data Hub APIs readily accessible to
 developers.
 
 - OS Data Hub APIs: https://osdatahub.os.uk/
```

### Comparing `osdatahub-1.2.5/docs/media/os-logo.png` & `osdatahub-1.2.6/docs/media/os-logo.png`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/media/os-logo.png` & `osdatahub-1.2.6/media/os-logo.png`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/setup.cfg` & `osdatahub-1.2.6/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = osdatahub
-version = 1.2.5
+version = 1.2.6
 author = OS Rapid Prototyping
 author_email = rapidprototyping@os.uk
 classifiers = 
 	Natural Language :: English
 	Intended Audience :: Developers
 	Intended Audience :: Science/Research
 	Programming Language :: Python :: 3.7
@@ -30,15 +30,15 @@
 	Issues = https://github.com/OrdnanceSurvey/osdatahub/issues
 url = https://github.com/OrdnanceSurvey/osdatahub
 
 [options]
 include_package_data = True
 install_requires = 
 	geojson~=3.0.1
-	requests~=2.25.0
+	requests~=2.31.0
 	typeguard~=2.13.0
 	shapely~=2.0.0
 	tqdm~=4.65.0
 	setuptools~=67.7.2
 python_requires = >=3.7
 package_dir = 
 	=src
```

### Comparing `osdatahub-1.2.5/src/osdatahub/DownloadsAPI/data_package.py` & `osdatahub-1.2.6/src/osdatahub/DownloadsAPI/data_package.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/DownloadsAPI/downloads_api.py` & `osdatahub-1.2.6/src/osdatahub/DownloadsAPI/downloads_api.py`

 * *Files 4% similar despite different names*

```diff
@@ -41,26 +41,33 @@
         if os.path.isfile(output_path) and not overwrite:
             logging.warning(f"Overwrite is set to False and there is a file already in the location {output_path}. "
                             f"Skipping download...")
             return output_path
 
         response = requests.get(self.url, stream=True, proxies=osdatahub.get_proxies())
         response.raise_for_status()
-        size = int(response.headers.get('content-length'))
-        chunk_size = 1024
+        expected_size = int(response.headers.get('content-length'))
+        current_size = 0
+        chunk_size = 1048576 # 1024 ** 2 -> 1MB
         if response.status_code == 200:
             with open(output_path, 'wb') as f:
                 if not pbar:
-                    pbar = tqdm(total=size, desc=self.file_name, unit="B", unit_scale=True, leave=True)
+                    pbar = tqdm(total=expected_size, desc=self.file_name, unit="B", unit_scale=True, leave=True)
                 for chunk in response.iter_content(chunk_size=chunk_size):
+                    current_size += len(chunk)
                     f.write(chunk)
                     f.flush()
                     pbar.update(chunk_size)
 
-        # pbar.write(f"Finished downloading {self.file_name} to {output_path}")
+        if expected_size != current_size:
+            deficit = expected_size - current_size
+            raise IOError(
+                f'incomplete read ({current_size} bytes read, {deficit} more expected)'
+            ) 
+        pbar.write(f"Finished downloading {self.file_name} to {output_path}")
         return output_path
 
 
 class _DownloadsAPIBase(ABC):
     """Parent class for Product and DataPackage classes as part of the DownloadsAPI
     (https://osdatahub.os.uk/docs/downloads/overview)
```

### Comparing `osdatahub-1.2.5/src/osdatahub/DownloadsAPI/opendata.py` & `osdatahub-1.2.6/src/osdatahub/DownloadsAPI/opendata.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/FeaturesAPI/feature_products.py` & `osdatahub-1.2.6/src/osdatahub/FeaturesAPI/feature_products.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/FeaturesAPI/features_api.py` & `osdatahub-1.2.6/src/osdatahub/FeaturesAPI/features_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/LinkedIdentifiersAPI/linked_identifier_options.py` & `osdatahub-1.2.6/src/osdatahub/LinkedIdentifiersAPI/linked_identifier_options.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/LinkedIdentifiersAPI/linked_identifiers_api.py` & `osdatahub-1.2.6/src/osdatahub/LinkedIdentifiersAPI/linked_identifiers_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/NGD/crs.py` & `osdatahub-1.2.6/src/osdatahub/NGD/crs.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/NGD/ngd_api.py` & `osdatahub-1.2.6/src/osdatahub/NGD/ngd_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/NamesAPI/local_types.py` & `osdatahub-1.2.6/src/osdatahub/NamesAPI/local_types.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/NamesAPI/names_api.py` & `osdatahub-1.2.6/src/osdatahub/NamesAPI/names_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/PlacesAPI/places_api.py` & `osdatahub-1.2.6/src/osdatahub/PlacesAPI/places_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/__init__.py` & `osdatahub-1.2.6/src/osdatahub/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 
 def set_proxies(proxies):
     os.environ["_OSDATAHUB_PROXIES"] = json.dumps(proxies)
 
 def get_proxies():
     return json.loads(os.environ["_OSDATAHUB_PROXIES"])
 
-__version__ = "1.2.5"
+__version__ = "1.2.6"
 
 from osdatahub.extent import Extent
 from osdatahub.FeaturesAPI import FeaturesAPI
 from osdatahub.PlacesAPI import PlacesAPI
 from osdatahub.NamesAPI import NamesAPI
 from osdatahub.LinkedIdentifiersAPI import LinkedIdentifiersAPI
 from osdatahub.DownloadsAPI import OpenDataDownload, DataPackageDownload
```

### Comparing `osdatahub-1.2.5/src/osdatahub/bbox.py` & `osdatahub-1.2.6/src/osdatahub/bbox.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/codes.py` & `osdatahub-1.2.6/src/osdatahub/codes.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/errors.py` & `osdatahub-1.2.6/src/osdatahub/errors.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/extent.py` & `osdatahub-1.2.6/src/osdatahub/extent.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/filters.py` & `osdatahub-1.2.6/src/osdatahub/filters.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/grow_list.py` & `osdatahub-1.2.6/src/osdatahub/grow_list.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/ons_api.py` & `osdatahub-1.2.6/src/osdatahub/ons_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/requests_wrapper.py` & `osdatahub-1.2.6/src/osdatahub/requests_wrapper.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/spatial_filter_types.py` & `osdatahub-1.2.6/src/osdatahub/spatial_filter_types.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub/utils.py` & `osdatahub-1.2.6/src/osdatahub/utils.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/src/osdatahub.egg-info/PKG-INFO` & `osdatahub-1.2.6/src/osdatahub.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: osdatahub
-Version: 1.2.5
+Version: 1.2.6
 Summary: osdatahub is Ordnance Survey's (OS) Python API wrapper, designed to make data from the OS Data Hub APIs readily accessible to developers.
 Home-page: https://github.com/OrdnanceSurvey/osdatahub
 Download-URL: https://pypi.org/project/osdatahub/
 Author: OS Rapid Prototyping
 Author-email: rapidprototyping@os.uk
 License: OGL
 Project-URL: Code, https://github.com/OrdnanceSurvey/osdatahub
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: osdatahub Version: 1.2.5 Summary: osdatahub is
+Metadata-Version: 2.1 Name: osdatahub Version: 1.2.6 Summary: osdatahub is
 Ordnance Survey's (OS) Python API wrapper, designed to make data from the OS
 Data Hub APIs readily accessible to developers. Home-page: https://github.com/
 OrdnanceSurvey/osdatahub Download-URL: https://pypi.org/project/osdatahub/
 Author: OS Rapid Prototyping Author-email: rapidprototyping@os.uk License: OGL
 Project-URL: Code, https://github.com/OrdnanceSurvey/osdatahub Project-URL:
 Documentation, https://osdatahub.readthedocs.io/en/latest/ Project-URL: Issues,
 https://github.com/OrdnanceSurvey/osdatahub/issues Keywords: Ordnance-
```

### Comparing `osdatahub-1.2.5/src/osdatahub.egg-info/SOURCES.txt` & `osdatahub-1.2.6/src/osdatahub.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon2.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon2.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon_with_hole.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_multipolygon_with_hole.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_polygon.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_polygon.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/API (uncleaned)/sites_polygon_with_hole.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/API (uncleaned)/sites_polygon_with_hole.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_multipolygon.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_multipolygon.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_multipolygon2.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_multipolygon2.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_multipolygon_with_hole.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_multipolygon_with_hole.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_polygon.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_polygon.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/QGIS/sites_polygon_with_hole.geojson` & `osdatahub-1.2.6/tests/data/clean_polygon_data/QGIS/sites_polygon_with_hole.geojson`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data/get_uncleaned_polygons.py` & `osdatahub-1.2.6/tests/data/clean_polygon_data/get_uncleaned_polygons.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/clean_polygon_data.py` & `osdatahub-1.2.6/tests/data/clean_polygon_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/downloads_data.py` & `osdatahub-1.2.6/tests/data/downloads_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/extent_data.py` & `osdatahub-1.2.6/tests/data/extent_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/features_api_data.py` & `osdatahub-1.2.6/tests/data/features_api_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/filters_data.py` & `osdatahub-1.2.6/tests/data/filters_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/linked_identifiers_api_data.py` & `osdatahub-1.2.6/tests/data/linked_identifiers_api_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/names_data.py` & `osdatahub-1.2.6/tests/data/names_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/ngd_crs_data.py` & `osdatahub-1.2.6/tests/data/ngd_crs_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/ngd_merge_geojsons_data.py` & `osdatahub-1.2.6/tests/data/ngd_merge_geojsons_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/ngd_query_data.py` & `osdatahub-1.2.6/tests/data/ngd_query_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/places_data.py` & `osdatahub-1.2.6/tests/data/places_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/data/utils_data.py` & `osdatahub-1.2.6/tests/data/utils_data.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/run_functions.py` & `osdatahub-1.2.6/tests/run_functions.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_downloads_api.py` & `osdatahub-1.2.6/tests/test_downloads_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_extent.py` & `osdatahub-1.2.6/tests/test_extent.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_features_api.py` & `osdatahub-1.2.6/tests/test_features_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_filters.py` & `osdatahub-1.2.6/tests/test_filters.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_grow_list.py` & `osdatahub-1.2.6/tests/test_grow_list.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_linked_identifiers_api.py` & `osdatahub-1.2.6/tests/test_linked_identifiers_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_names_api.py` & `osdatahub-1.2.6/tests/test_names_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_ngd.py` & `osdatahub-1.2.6/tests/test_ngd.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_places_api.py` & `osdatahub-1.2.6/tests/test_places_api.py`

 * *Files identical despite different names*

### Comparing `osdatahub-1.2.5/tests/test_utils.py` & `osdatahub-1.2.6/tests/test_utils.py`

 * *Files identical despite different names*


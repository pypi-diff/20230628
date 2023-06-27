# Comparing `tmp/utdf2gmns-0.2.4.tar.gz` & `tmp/utdf2gmns-0.2.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "utdf2gmns-0.2.4.tar", last modified: Mon Jun 26 17:41:47 2023, max compression
+gzip compressed data, was "utdf2gmns-0.2.5.tar", last modified: Tue Jun 27 23:11:21 2023, max compression
```

## Comparing `utdf2gmns-0.2.4.tar` & `utdf2gmns-0.2.5.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxrwxrwx   0        0        0        0 2023-06-26 17:41:47.091031 utdf2gmns-0.2.4/
--rw-rw-rw-   0        0        0    11558 2022-12-19 22:02:10.000000 utdf2gmns-0.2.4/LICENSE
--rw-rw-rw-   0        0        0     5429 2023-06-26 17:41:47.089032 utdf2gmns-0.2.4/PKG-INFO
--rw-rw-rw-   0        0        0       42 2023-06-26 17:41:47.091031 utdf2gmns-0.2.4/setup.cfg
--rw-rw-rw-   0        0        0     1489 2023-06-26 17:40:33.000000 utdf2gmns-0.2.4/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-26 17:41:47.039031 utdf2gmns-0.2.4/utdf2gmns/
--rw-rw-rw-   0        0        0     1155 2023-06-26 17:40:57.000000 utdf2gmns-0.2.4/utdf2gmns/__init__.py
--rw-rw-rw-   0        0        0     9196 2023-06-26 02:03:52.000000 utdf2gmns-0.2.4/utdf2gmns/__utdf2gmns.py
-drwxrwxrwx   0        0        0        0 2023-06-26 17:41:47.078030 utdf2gmns-0.2.4/utdf2gmns/func_lib/
--rw-rw-rw-   0        0        0      277 2023-06-24 00:46:51.000000 utdf2gmns-0.2.4/utdf2gmns/func_lib/__init__.py
--rw-rw-rw-   0        0        0     6379 2023-06-26 02:22:27.000000 utdf2gmns-0.2.4/utdf2gmns/func_lib/geocoding_intersection.py
--rw-rw-rw-   0        0        0     7462 2023-06-26 02:25:19.000000 utdf2gmns-0.2.4/utdf2gmns/func_lib/match_node_intersection_movement_utdf.py
--rw-rw-rw-   0        0        0    11276 2023-06-26 02:07:54.000000 utdf2gmns-0.2.4/utdf2gmns/func_lib/read_utdf.py
-drwxrwxrwx   0        0        0        0 2023-06-26 17:41:47.086029 utdf2gmns-0.2.4/utdf2gmns/utils_lib/
--rw-rw-rw-   0        0        0      278 2023-03-07 10:13:11.000000 utdf2gmns-0.2.4/utdf2gmns/utils_lib/__init__.py
--rw-rw-rw-   0        0        0     3356 2023-06-26 02:02:58.000000 utdf2gmns-0.2.4/utdf2gmns/utils_lib/package_settings.py
--rw-rw-rw-   0        0        0     5794 2023-03-14 01:43:28.000000 utdf2gmns-0.2.4/utdf2gmns/utils_lib/utility_lib.py
-drwxrwxrwx   0        0        0        0 2023-06-26 17:41:47.066029 utdf2gmns-0.2.4/utdf2gmns.egg-info/
--rw-rw-rw-   0        0        0     5429 2023-06-26 17:41:46.000000 utdf2gmns-0.2.4/utdf2gmns.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      502 2023-06-26 17:41:46.000000 utdf2gmns-0.2.4/utdf2gmns.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-26 17:41:46.000000 utdf2gmns-0.2.4/utdf2gmns.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       62 2023-06-26 17:41:46.000000 utdf2gmns-0.2.4/utdf2gmns.egg-info/requires.txt
--rw-rw-rw-   0        0        0       10 2023-06-26 17:41:46.000000 utdf2gmns-0.2.4/utdf2gmns.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-27 23:11:21.509945 utdf2gmns-0.2.5/
+-rw-rw-rw-   0        0        0    11558 2022-12-19 22:02:10.000000 utdf2gmns-0.2.5/LICENSE
+-rw-rw-rw-   0        0        0     5631 2023-06-27 23:11:21.507933 utdf2gmns-0.2.5/PKG-INFO
+-rw-rw-rw-   0        0        0       42 2023-06-27 23:11:21.510950 utdf2gmns-0.2.5/setup.cfg
+-rw-rw-rw-   0        0        0     1489 2023-06-27 23:05:59.000000 utdf2gmns-0.2.5/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-27 23:11:21.386935 utdf2gmns-0.2.5/utdf2gmns/
+-rw-rw-rw-   0        0        0     1154 2023-06-27 23:06:07.000000 utdf2gmns-0.2.5/utdf2gmns/__init__.py
+-rw-rw-rw-   0        0        0    10157 2023-06-27 22:38:03.000000 utdf2gmns-0.2.5/utdf2gmns/_utdf2gmns.py
+drwxrwxrwx   0        0        0        0 2023-06-27 23:11:21.490931 utdf2gmns-0.2.5/utdf2gmns/func_lib/
+-rw-rw-rw-   0        0        0      277 2023-06-24 00:46:51.000000 utdf2gmns-0.2.5/utdf2gmns/func_lib/__init__.py
+-rw-rw-rw-   0        0        0     6526 2023-06-27 22:35:05.000000 utdf2gmns-0.2.5/utdf2gmns/func_lib/geocoding_intersection.py
+-rw-rw-rw-   0        0        0     7773 2023-06-27 22:46:50.000000 utdf2gmns-0.2.5/utdf2gmns/func_lib/match_node_intersection_movement_utdf.py
+-rw-rw-rw-   0        0        0    11276 2023-06-26 02:07:54.000000 utdf2gmns-0.2.5/utdf2gmns/func_lib/read_utdf.py
+drwxrwxrwx   0        0        0        0 2023-06-27 23:11:21.503930 utdf2gmns-0.2.5/utdf2gmns/utils_lib/
+-rw-rw-rw-   0        0        0      278 2023-03-07 10:13:11.000000 utdf2gmns-0.2.5/utdf2gmns/utils_lib/__init__.py
+-rw-rw-rw-   0        0        0     3356 2023-06-26 02:02:58.000000 utdf2gmns-0.2.5/utdf2gmns/utils_lib/package_settings.py
+-rw-rw-rw-   0        0        0     5794 2023-03-14 01:43:28.000000 utdf2gmns-0.2.5/utdf2gmns/utils_lib/utility_lib.py
+drwxrwxrwx   0        0        0        0 2023-06-27 23:11:21.470928 utdf2gmns-0.2.5/utdf2gmns.egg-info/
+-rw-rw-rw-   0        0        0     5631 2023-06-27 23:11:20.000000 utdf2gmns-0.2.5/utdf2gmns.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      501 2023-06-27 23:11:21.000000 utdf2gmns-0.2.5/utdf2gmns.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-27 23:11:20.000000 utdf2gmns-0.2.5/utdf2gmns.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       33 2023-06-27 23:11:20.000000 utdf2gmns-0.2.5/utdf2gmns.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       10 2023-06-27 23:11:20.000000 utdf2gmns-0.2.5/utdf2gmns.egg-info/top_level.txt
```

### Comparing `utdf2gmns-0.2.4/LICENSE` & `utdf2gmns-0.2.5/LICENSE`

 * *Files identical despite different names*

### Comparing `utdf2gmns-0.2.4/PKG-INFO` & `utdf2gmns-0.2.5/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: utdf2gmns
-Version: 0.2.4
+Version: 0.2.5
 Summary: This open-source package is a tool to convert utdf file to GMNS format.
 Home-page: https://github.com/asu-trans-ai-lab/utdf2gmns
 Author: Xiangyong Luo, Dr.Xuesong (Simon) Zhou
 Author-email: luoxiangyong01@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -31,14 +31,16 @@
 * A dictionary store utdf data with keys: Networks, Node, Links, Timeplans, Lanes, and utdf_intersection
 * A file named utdf2gmns.pickle to store dictionary object.
 
 **If input folder have extra node.csv and movement.csv, outputs are:**
 
 * Two files named:  movement_utdf.csv and utdf_intersection.csv
 
+Sample results: [datasets](https://github.com/asu-trans-ai-lab/utdf2gmns/tree/main/datasets)
+
 ## **Package dependencies**:
 
 * [X] geocoder==1.38.1
 * [X] numpy==1.23.3
 * [X] openpyxl==3.0.10
 * [X] pandas==1.4.4
 
@@ -110,14 +112,16 @@
 
 ## TODO LIST
 
 * [X] Print out how many intersections being geocoded.
 * [X] Print out check log.
 * [X] Number of lanes of the movements from synchro file.
 * [X] Add function to verify whether geocoded for utdf_geo
+* [X] Print geocoding details (in percentage)
+* [ ] Add three kwargs in function generate_movement_utdf
 * [ ] Print out how many movements being matched or not matched for signalized intersecton nodes.
 * [ ] Check reasonable capacity.
 * [ ] Check each movement is reasonable (like 15s of green time...). other attributes.
 * [ ] Check number of lanes correctness between osm2gmns file and synchro file per movements.
 * [ ] Add signal info to micre-link.cs
 * [ ] Add cycle length and green time for each movement.
```

### Comparing `utdf2gmns-0.2.4/setup.py` & `utdf2gmns-0.2.5/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -16,15 +16,15 @@
     with open("requirements.txt", "r", encoding="utf-8") as f:
         modules_needed = [i.strip() for i in f.readlines()]
 except Exception:
     modules_needed = []
 
 setuptools.setup(
     name="utdf2gmns",  # Replace with your own username
-    version="0.2.4",
+    version="0.2.5",
     author="Xiangyong Luo, Dr.Xuesong (Simon) Zhou",
     author_email="luoxiangyong01@gmail.com",
     description="This open-source package is a tool to convert utdf file to GMNS format.",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url="https://github.com/asu-trans-ai-lab/utdf2gmns",
```

### Comparing `utdf2gmns-0.2.4/utdf2gmns/__init__.py` & `utdf2gmns-0.2.5/utdf2gmns/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 # -*- coding:utf-8 -*-
 ##############################################################
 # Created Date: Tuesday, January 31st 2023
 # Contact Info: luoxiangyong01@gmail.com
 # Author/Copyright: Mr. Xiangyong Luo
 ##############################################################
 
-from .__utdf2gmns import (generate_utdf_dataframes,
+from ._utdf2gmns import (generate_utdf_dataframes,
                           generate_movement_utdf,
                           generate_coordinates_from_intersection,
                           match_intersection_node,
                           match_movement_and_intersection_node,
                           match_movement_utdf_lane,
                           match_movement_utdf_phase_timeplans
                           )
@@ -22,8 +22,8 @@
            'match_intersection_node',
            'match_movement_and_intersection_node',
            'match_movement_utdf_lane',
            'match_movement_utdf_phase_timeplans',
            'package_settings'
            ]
 
-print("utdf2gmns version: ", "0.2.4")
+print("utdf2gmns version: ", "0.2.5")
```

### Comparing `utdf2gmns-0.2.4/utdf2gmns/__utdf2gmns.py` & `utdf2gmns-0.2.5/utdf2gmns/_utdf2gmns.py`

 * *Files 12% similar despite different names*

```diff
@@ -48,18 +48,43 @@
     # with open(os.path.join(os.getcwd(), "utdf2gmns.pickle"), 'wb') as f:
     #     pickle.dump(utdf_dict_data, f, pickle.HIGHEST_PROTOCOL)
 
     return utdf_dict_data
 
 
 @func_running_time
-def generate_movement_utdf(input_dir: str,
+def generate_movement_utdf(input_dir: str = "",
                            city_name: str = "",
+                           UTDF_file: str = None,
+                           node_file: str = None,
+                           movement_file: str = None,
                            output_dir: str = "",
                            isSave2csv: bool = True) -> list:
+    """Des
+
+    Args:
+        input_dir (str, optional): _description_. Defaults to "".
+        city_name (str, optional): _description_. Defaults to "".
+        UTDF_file (str, optional): _description_. Defaults to None.
+        node_file (str, optional): _description_. Defaults to None.
+        movement_file (str, optional): _description_. Defaults to None.
+        output_dir (str, optional): _description_. Defaults to "".
+        isSave2csv (bool, optional): _description_. Defaults to True.
+
+    Raises:
+        Exception: _description_
+        Exception: _description_
+        Exception: _description_
+
+    Returns:
+        list: _description_
+    """
+
+    # if not specified input_dir, use current working directory
+    input_dir = input_dir or os.getcwd()
 
     # check if required files exist in the input directory
     files_from_directory = get_filenames_from_folder_by_type(input_dir, file_type="csv")
 
     # if not required, raise an exception
     isRequired = check_required_files_exist(required_files, files_from_directory)
     isRequired_sub = check_required_files_exist(required_files_sub, files_from_directory)
@@ -165,15 +190,15 @@
     if isSave2csv:
         if not output_dir:
             output_dir = input_dir
         output_file_name = validate_filename(os.path.join(output_dir, "movement_utdf.csv"))
         df_movement_utdf_phase.to_csv(output_file_name, index=False)
 
         output_file_name = validate_filename(os.path.join(output_dir, "utdf_intersection.csv"))
-        df_intersection_node.to_csv(output_file_name, index=False)
+        utdf_dict_data.get("utdf_geo").to_csv(output_file_name, index=False)
 
         # with open(path2linux(os.path.join(output_dir, "utdf2gmns.pickle")), 'wb') as f:
         #     pickle.dump(utdf_dict_data, f, pickle.HIGHEST_PROTOCOL)
 
     return [df_movement_utdf_phase, utdf_dict_data]
```

### Comparing `utdf2gmns-0.2.4/utdf2gmns/func_lib/geocoding_intersection.py` & `utdf2gmns-0.2.5/utdf2gmns/func_lib/geocoding_intersection.py`

 * *Files 3% similar despite different names*

```diff
@@ -66,15 +66,15 @@
     return location_lng_lat
 
 
 @func_running_time
 def generate_coordinates_from_intersection(df_intersection: pd.DataFrame, distance_threshold=0.01) -> pd.DataFrame:
     # distance_threshold is the threshold to determine whether the intersection is able to geocode, using km as unit
 
-    df = df_intersection.copy()
+    df = df_intersection.copy(deep=True)
 
     # check required columns exist in the dataframe
     if not {"intersection_name", "city_name"}.issubset(set(df.columns)):
         raise Exception(
             "intersection_name and city_name are not in the dataframe, please check the input file.")
 
     # Create one column named "reversed_intersection_name"
@@ -90,35 +90,39 @@
     df["full_name_intersection_reversed"] = df["reversed_intersection_name"] + ", " + df["city_name"]
 
     # Step 4: geocoding
     print("   :geocoding intersections...")
     intersection_full_name_list = df["full_name_intersection"].tolist()
     intersection_full_name_reversed_list = df["full_name_intersection_reversed"].tolist()
 
+    # the number of intersections to be geocoded
+    num_intersection = len(intersection_full_name_list)
+
     try:
+        lnglat_values_full_name = []
+        lnglat_values_full_name_reversed = []
+        for i in range(num_intersection):
+            lnglat_values_full_name.append(
+                geocoder_geocoding_from_address(intersection_full_name_list[i]))
+            lnglat_values_full_name_reversed.append(
+                geocoder_geocoding_from_address(intersection_full_name_reversed_list[i]))
+
+            if i % 10 == 0:
+                print(f"    :{i}/{num_intersection} intersections have been geocoded.")
+
         # use multiprocessing to speed up
         # p = Pool()
         # lnglat_values_full_name = p.map(geocoder_geocoding_from_address, intersection_full_name_list)
 
-        # using loop to geocode
-        lnglat_values_full_name = [geocoder_geocoding_from_address(address) for address in intersection_full_name_list]
-
-    except Exception as e:
-        raise Exception("   :geocoding intersections failed, try again...") from e
-
-    try:
-        # use multiprocessing to speed up
         # p1 = Pool()
         # lnglat_values_full_name_reversed = p1.map(geocoder_geocoding_from_address, intersection_full_name_reversed_list)
 
-        # using loop to geocode
-        lnglat_values_full_name_reversed = [geocoder_geocoding_from_address(address) for address in intersection_full_name_reversed_list]
+    except Exception as e:
+        raise Exception("   :geocoding intersections failed, try again...") from e
 
-    except Exception as exc:
-        raise Exception("   :geocoding intersections failed, try again...") from exc
 
     # create new column named distance_from_full_name
     print("   :cross validating...")
     distance = [calculate_point2point_distance_in_km(
         lnglat_values_full_name[i], lnglat_values_full_name_reversed[i]) for i in range(len(lnglat_values_full_name))]
 
     for i in range(len(df)):
@@ -126,16 +130,16 @@
 
         if distance[i] <= distance_threshold:
             df.loc[i, "coord_x"] = lnglat_values_full_name[i][0]
             df.loc[i, "coord_y"] = lnglat_values_full_name[i][1]
 
         else:
             # use None to indicate the intersection is not able to geocode
-            df.loc[i, "coord_x"] = 0
-            df.loc[i, "coord_y"] = 0
+            df.loc[i, "coord_x"] = None
+            df.loc[i, "coord_y"] = None
 
     created_column_names = ["reversed_intersection_name", "full_name_intersection",
                             "full_name_intersection_reversed", "distance_from_full_name"]
     df_final = df.loc[:, ~df.columns.isin(created_column_names)]
 
     # print summary information
     print(
```

### Comparing `utdf2gmns-0.2.4/utdf2gmns/func_lib/match_node_intersection_movement_utdf.py` & `utdf2gmns-0.2.5/utdf2gmns/func_lib/match_node_intersection_movement_utdf.py`

 * *Files 3% similar despite different names*

```diff
@@ -6,15 +6,18 @@
 ##############################################################
 
 
 import pandas as pd
 from utdf2gmns.utils_lib.utility_lib import func_running_time, calculate_point2point_distance_in_km
 
 
-def find_shortest_distance_node(point: tuple, node_df: pd.DataFrame, max_distance_threshold: float = 0.1) -> tuple:
+def find_shortest_distance_node(point: tuple,
+                                node_df: pd.DataFrame,
+                                max_distance_threshold: float = 0.1,
+                                intersection_id="") -> tuple:
     """ point: a tuple of (longitude, latitude),
         node_df: a dataframe of node information,
         max_distance_threshold (km): the maximum distance threshold to find the nearest node
     """
 
     # get node longitude and latitude from node_df
     node_location_list = [(node_df.loc[i, "x_coord"], node_df.loc[i, "y_coord"]) for i in range(node_df.shape[0])]
@@ -24,15 +27,15 @@
 
     # find the minimum distance
     min_distance = min(point_to_node_distance_list)
     # print(f"INFO: The minimum distance is {min_distance} km")
 
     # if the minimum distance is larger than the threshold, then return None
     if min_distance > max_distance_threshold:
-        print(f"  WARNING: {point} is not able to find the nearest node, the minimum distance is {min_distance}, the threshold is {max_distance_threshold}km")
+        print(f"  :Intersection id: {intersection_id} can not find the nearest node within threshold of {max_distance_threshold}km")
         return [""] * len(node_df.columns)
 
     # find the index of the minimum distance
     min_distance_index = point_to_node_distance_list.index(min_distance)
     return list(node_df.loc[min_distance_index, :])
 
 
@@ -52,17 +55,21 @@
     for i in range(len(df_intersection_geo)):
 
         intersection_value = list(df_intersection_geo.loc[i, :])
 
         intersection_lnglat = (
             df_intersection_geo.loc[i, "coord_x"], df_intersection_geo.loc[i, "coord_y"])
 
+        inter_id = df_intersection_geo.loc[i, "intersection_id"]
+
         intersection_node_list.append(
             intersection_value + find_shortest_distance_node(intersection_lnglat,
-                                                             df_node_signal, max_distance_threshold))
+                                                             df_node_signal,
+                                                             max_distance_threshold,
+                                                             intersection_id=inter_id))
 
     df_intersection_node = pd.DataFrame(
         intersection_node_list, columns=col_intersection_geo + col_node)
 
     return df_intersection_node
```

### Comparing `utdf2gmns-0.2.4/utdf2gmns/func_lib/read_utdf.py` & `utdf2gmns-0.2.5/utdf2gmns/func_lib/read_utdf.py`

 * *Files identical despite different names*

### Comparing `utdf2gmns-0.2.4/utdf2gmns/utils_lib/package_settings.py` & `utdf2gmns-0.2.5/utdf2gmns/utils_lib/package_settings.py`

 * *Files identical despite different names*

### Comparing `utdf2gmns-0.2.4/utdf2gmns/utils_lib/utility_lib.py` & `utdf2gmns-0.2.5/utdf2gmns/utils_lib/utility_lib.py`

 * *Files identical despite different names*

### Comparing `utdf2gmns-0.2.4/utdf2gmns.egg-info/PKG-INFO` & `utdf2gmns-0.2.5/utdf2gmns.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: utdf2gmns
-Version: 0.2.4
+Version: 0.2.5
 Summary: This open-source package is a tool to convert utdf file to GMNS format.
 Home-page: https://github.com/asu-trans-ai-lab/utdf2gmns
 Author: Xiangyong Luo, Dr.Xuesong (Simon) Zhou
 Author-email: luoxiangyong01@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
@@ -31,14 +31,16 @@
 * A dictionary store utdf data with keys: Networks, Node, Links, Timeplans, Lanes, and utdf_intersection
 * A file named utdf2gmns.pickle to store dictionary object.
 
 **If input folder have extra node.csv and movement.csv, outputs are:**
 
 * Two files named:  movement_utdf.csv and utdf_intersection.csv
 
+Sample results: [datasets](https://github.com/asu-trans-ai-lab/utdf2gmns/tree/main/datasets)
+
 ## **Package dependencies**:
 
 * [X] geocoder==1.38.1
 * [X] numpy==1.23.3
 * [X] openpyxl==3.0.10
 * [X] pandas==1.4.4
 
@@ -110,14 +112,16 @@
 
 ## TODO LIST
 
 * [X] Print out how many intersections being geocoded.
 * [X] Print out check log.
 * [X] Number of lanes of the movements from synchro file.
 * [X] Add function to verify whether geocoded for utdf_geo
+* [X] Print geocoding details (in percentage)
+* [ ] Add three kwargs in function generate_movement_utdf
 * [ ] Print out how many movements being matched or not matched for signalized intersecton nodes.
 * [ ] Check reasonable capacity.
 * [ ] Check each movement is reasonable (like 15s of green time...). other attributes.
 * [ ] Check number of lanes correctness between osm2gmns file and synchro file per movements.
 * [ ] Add signal info to micre-link.cs
 * [ ] Add cycle length and green time for each movement.
```


# Comparing `tmp/ign-pdal-tools-0.5.6.tar.gz` & `tmp/ign-pdal-tools-1.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ign-pdal-tools-0.5.6.tar", last modified: Wed May 31 15:11:39 2023, max compression
+gzip compressed data, was "ign-pdal-tools-1.0.0.tar", last modified: Wed Jun 28 14:19:10 2023, max compression
```

## Comparing `ign-pdal-tools-0.5.6.tar` & `ign-pdal-tools-1.0.0.tar`

### file list

```diff
@@ -1,27 +1,28 @@
-drwxr-xr-x   0 GLiegard (16037) user_RDS (11150)        0 2023-05-31 15:11:39.209094 ign-pdal-tools-0.5.6/
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     2716 2023-05-31 15:11:39.209094 ign-pdal-tools-0.5.6/PKG-INFO
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     2497 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/README.md
-drwxr-xr-x   0 GLiegard (16037) user_RDS (11150)        0 2023-05-31 15:11:39.205094 ign-pdal-tools-0.5.6/ign_pdal_tools.egg-info/
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     2716 2023-05-31 15:11:39.000000 ign-pdal-tools-0.5.6/ign_pdal_tools.egg-info/PKG-INFO
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)      566 2023-05-31 15:11:39.000000 ign-pdal-tools-0.5.6/ign_pdal_tools.egg-info/SOURCES.txt
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)        1 2023-05-31 15:11:39.000000 ign-pdal-tools-0.5.6/ign_pdal_tools.egg-info/dependency_links.txt
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)       10 2023-05-31 15:11:39.000000 ign-pdal-tools-0.5.6/ign_pdal_tools.egg-info/top_level.txt
-drwxr-xr-x   0 GLiegard (16037) user_RDS (11150)        0 2023-05-31 15:11:39.205094 ign-pdal-tools-0.5.6/pdaltools/
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)       74 2023-05-31 15:11:06.000000 ign-pdal-tools-0.5.6/pdaltools/_version.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     8269 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/pdaltools/color.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     5438 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/pdaltools/las_add_buffer.py
--rwxr-xr-x   0 GLiegard (16037) user_RDS (11150)     1193 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/pdaltools/las_clip.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     4880 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/pdaltools/las_info.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     4183 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/pdaltools/las_merge.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     5270 2023-05-31 09:01:28.000000 ign-pdal-tools-0.5.6/pdaltools/replace_attribute_in_las.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     3050 2023-05-31 13:00:07.000000 ign-pdal-tools-0.5.6/pdaltools/standardize_format.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)      353 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/pyproject.toml
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)       38 2023-05-31 15:11:39.209094 ign-pdal-tools-0.5.6/setup.cfg
-drwxr-xr-x   0 GLiegard (16037) user_RDS (11150)        0 2023-05-31 15:11:39.209094 ign-pdal-tools-0.5.6/test/
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     3306 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/test/test_color.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     2345 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/test/test_las_add_buffer.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     1873 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/test/test_las_clip.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     2628 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/test/test_las_info.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     1853 2023-05-24 14:49:59.000000 ign-pdal-tools-0.5.6/test/test_las_merge.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     3133 2023-05-31 09:01:28.000000 ign-pdal-tools-0.5.6/test/test_replace_attribute_in_las.py
--rw-r--r--   0 GLiegard (16037) user_RDS (11150)     3867 2023-05-31 09:01:28.000000 ign-pdal-tools-0.5.6/test/test_standardize_format.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:19:10.428796 ign-pdal-tools-1.0.0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1120 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/LICENSE.md
+-rw-r--r--   0 runner    (1001) docker     (123)     3952 2023-06-28 14:19:10.428796 ign-pdal-tools-1.0.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     3708 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:19:10.424796 ign-pdal-tools-1.0.0/ign_pdal_tools.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     3952 2023-06-28 14:19:10.000000 ign-pdal-tools-1.0.0/ign_pdal_tools.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      577 2023-06-28 14:19:10.000000 ign-pdal-tools-1.0.0/ign_pdal_tools.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 14:19:10.000000 ign-pdal-tools-1.0.0/ign_pdal_tools.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 14:19:10.000000 ign-pdal-tools-1.0.0/ign_pdal_tools.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:19:10.428796 ign-pdal-tools-1.0.0/pdaltools/
+-rw-r--r--   0 runner    (1001) docker     (123)       74 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/pdaltools/_version.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8269 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/pdaltools/color.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5438 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/pdaltools/las_add_buffer.py
+-rwxr-xr-x   0 runner    (1001) docker     (123)     1193 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/pdaltools/las_clip.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4880 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/pdaltools/las_info.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4183 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/pdaltools/las_merge.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5270 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/pdaltools/replace_attribute_in_las.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3050 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/pdaltools/standardize_format.py
+-rw-r--r--   0 runner    (1001) docker     (123)      353 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 14:19:10.428796 ign-pdal-tools-1.0.0/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 14:19:10.428796 ign-pdal-tools-1.0.0/test/
+-rw-r--r--   0 runner    (1001) docker     (123)     3252 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/test/test_color.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2345 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/test/test_las_add_buffer.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1873 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/test/test_las_clip.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2628 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/test/test_las_info.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1853 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/test/test_las_merge.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3133 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/test/test_replace_attribute_in_las.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3867 2023-06-28 14:18:42.000000 ign-pdal-tools-1.0.0/test/test_standardize_format.py
```

### Comparing `ign-pdal-tools-0.5.6/ign_pdal_tools.egg-info/SOURCES.txt` & `ign-pdal-tools-1.0.0/ign_pdal_tools.egg-info/SOURCES.txt`

 * *Files 14% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+LICENSE.md
 README.md
 pyproject.toml
 ign_pdal_tools.egg-info/PKG-INFO
 ign_pdal_tools.egg-info/SOURCES.txt
 ign_pdal_tools.egg-info/dependency_links.txt
 ign_pdal_tools.egg-info/top_level.txt
 pdaltools/_version.py
```

### Comparing `ign-pdal-tools-0.5.6/pdaltools/color.py` & `ign-pdal-tools-1.0.0/pdaltools/color.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/pdaltools/las_add_buffer.py` & `ign-pdal-tools-1.0.0/pdaltools/las_add_buffer.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/pdaltools/las_clip.py` & `ign-pdal-tools-1.0.0/pdaltools/las_clip.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/pdaltools/las_info.py` & `ign-pdal-tools-1.0.0/pdaltools/las_info.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/pdaltools/las_merge.py` & `ign-pdal-tools-1.0.0/pdaltools/las_merge.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/pdaltools/replace_attribute_in_las.py` & `ign-pdal-tools-1.0.0/pdaltools/replace_attribute_in_las.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/pdaltools/standardize_format.py` & `ign-pdal-tools-1.0.0/pdaltools/standardize_format.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/test/test_color.py` & `ign-pdal-tools-1.0.0/test/test_color.py`

 * *Files 12% similar despite different names*

```diff
@@ -15,64 +15,66 @@
 def setup_module(module):
     try:
         shutil.rmtree(TMPDIR)
     except (FileNotFoundError):
         pass
     os.mkdir(TMPDIR)
 
-input_file = "/var/data/store-lidarhd/developpement/lidarexpress/tests/test_bug_laz_epsg/epsg_fail/Semis_2021_0435_6292_LA93_IGN69.laz"
-ouptput_file = TMPDIR + "Semis_2021_0435_6292_LA93_IGN69.las"
+TEST_PATH = os.path.dirname(os.path.abspath(__file__))
+INPUT_PATH = os.path.join(TEST_PATH, 'data/test_noepsg_043500_629205_IGN69.laz')
+
+OUTPUT_FILE = TMPDIR + "Semis_2021_0435_6292_LA93_IGN69.las"
 
 
 def test_epsg_fail():
     with pytest.raises(requests.exceptions.HTTPError, match="400 Client Error: BadRequest for url") :
-        color.decomp_and_color(input_file, ouptput_file, "", 0.1, 15)
+        color.decomp_and_color(INPUT_PATH, OUTPUT_FILE, "", 0.1, 15)
 
 
 epsg = "2154"
 layer= "ORTHOIMAGERY.ORTHOPHOTOS"
 minx=435000
 miny=6291000
 maxx=436000
 maxy=6292000
 pixel_per_meter=0.1
 
 
 def test_download_image_ok():
-    color.download_image_from_geoportail(epsg, layer, minx, miny, maxx, maxy, pixel_per_meter, ouptput_file, 15)
+    color.download_image_from_geoportail(epsg, layer, minx, miny, maxx, maxy, pixel_per_meter, OUTPUT_FILE, 15)
 
 
 def test_download_image_raise1():
     retry_download = color.retry(2, 5)(color.download_image_from_geoportail)
     with pytest.raises(requests.exceptions.HTTPError):
-        retry_download(epsg, "MAUVAISE_COUCHE", minx, miny, maxx, maxy, pixel_per_meter, ouptput_file, 15)
+        retry_download(epsg, "MAUVAISE_COUCHE", minx, miny, maxx, maxy, pixel_per_meter, OUTPUT_FILE, 15)
 
 
 def test_download_image_raise2():
     retry_download = color.retry(2, 5)(color.download_image_from_geoportail)
     with pytest.raises(requests.exceptions.HTTPError):
-        retry_download("9001", layer, minx, miny, maxx, maxy, pixel_per_meter, ouptput_file, 15)
+        retry_download("9001", layer, minx, miny, maxx, maxy, pixel_per_meter, OUTPUT_FILE, 15)
 
 
 def test_retry_on_server_error():
     with requests_mock.Mocker() as mock:
         mock.get(requests_mock.ANY, status_code=502, reason="Bad Gateway")
         with pytest.raises(requests.exceptions.HTTPError):
             retry_download = color.retry(2, 1, 2)(color.download_image_from_geoportail)
-            retry_download(epsg, layer, minx, miny, maxx, maxy, pixel_per_meter, ouptput_file, 15)
+            retry_download(epsg, layer, minx, miny, maxx, maxy, pixel_per_meter, OUTPUT_FILE, 15)
         history = mock.request_history
         assert len(history) == 3
 
 
 def test_retry_on_connection_error():
       with requests_mock.Mocker() as mock:
         mock.get(requests_mock.ANY, exc=requests.exceptions.ConnectionError)
         with pytest.raises(requests.exceptions.ConnectionError):
             retry_download = color.retry(2, 1)(color.download_image_from_geoportail)
-            retry_download(epsg, layer, minx, miny, maxx, maxy, pixel_per_meter, ouptput_file, 15)
+            retry_download(epsg, layer, minx, miny, maxx, maxy, pixel_per_meter, OUTPUT_FILE, 15)
 
         history = mock.request_history
         assert len(history) == 3
 
 
 def test_retry_param():
 
@@ -81,23 +83,20 @@
     def raise_server_error():
         raise requests.exceptions.HTTPError("Server Error")
 
     with pytest.raises(requests.exceptions.HTTPError):
         raise_server_error()
 
 
-@pytest.mark.skip("TODO: utiliser un fichier sur le store")
-def test_decomp_and_color():
-
-    # bug de l'ouverture des laz
-    # TODO Faire une version legere de ce LAZ et le mettre sur le git
-    LAZ_FILE = "/media/data/Bug_ouverture_laz/one/436000_6469000.laz"
-    LAS_FILE = TMPDIR + "436000_6469000.las"
+def test_copy_and_hack_decorator():
+    # bug during laz opening in pdal (solved with copy_and_hack_decorator)
+    LAZ_FILE = os.path.join(TEST_PATH, 'data/test_pdalfail_0643_6319_LA93_IGN69.laz')
+    LAS_FILE = TMPDIR + "test_pdalfail_0643_6319_LA93_IGN69.las"
 
-    color.decomp_and_color(LAZ_FILE, LAS_FILE, "", 0.1)
+    color.decomp_and_color(LAZ_FILE, LAS_FILE, "", 1)
 
     las = laspy.read(LAS_FILE)
     print(las.header)
     print(list(las.point_format.dimension_names))
     print(las.red)
     print(las.green)
     print(las.blue)
```

### Comparing `ign-pdal-tools-0.5.6/test/test_las_add_buffer.py` & `ign-pdal-tools-1.0.0/test/test_las_add_buffer.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/test/test_las_clip.py` & `ign-pdal-tools-1.0.0/test/test_las_clip.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/test/test_las_info.py` & `ign-pdal-tools-1.0.0/test/test_las_info.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/test/test_las_merge.py` & `ign-pdal-tools-1.0.0/test/test_las_merge.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/test/test_replace_attribute_in_las.py` & `ign-pdal-tools-1.0.0/test/test_replace_attribute_in_las.py`

 * *Files identical despite different names*

### Comparing `ign-pdal-tools-0.5.6/test/test_standardize_format.py` & `ign-pdal-tools-1.0.0/test/test_standardize_format.py`

 * *Files identical despite different names*


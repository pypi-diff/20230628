# Comparing `tmp/pydtk-0.3.0.tar.gz` & `tmp/pydtk-0.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pydtk-0.3.0.tar", max compression
+gzip compressed data, was "pydtk-0.3.1.tar", max compression
```

## Comparing `pydtk-0.3.0.tar` & `pydtk-0.3.1.tar`

### file list

```diff
@@ -1,138 +1,138 @@
--rw-r--r--   0        0        0    11340 2023-06-21 07:48:07.198635 pydtk-0.3.0/LICENSE
--rw-r--r--   0        0        0     2570 2023-06-21 07:48:07.198635 pydtk-0.3.0/README.md
--rw-r--r--   0        0        0      103 2023-06-21 07:48:22.250693 pydtk-0.3.0/pydtk/__init__.py
--rw-r--r--   0        0        0       44 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/bin/__init__.py
--rwxr-xr-x   0        0        0     2184 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/bin/cli.py
--rwxr-xr-x   0        0        0     3649 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/bin/make_meta.py
--rw-r--r--   0        0        0     2595 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/bin/oas.py
--rw-r--r--   0        0        0       28 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/bin/sub_commands/__init__.py
--rw-r--r--   0        0        0    14756 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/bin/sub_commands/db.py
--rw-r--r--   0        0        0      563 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/bin/sub_commands/io.py
--rw-r--r--   0        0        0     4272 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/bin/sub_commands/model.py
--rw-r--r--   0        0        0     1501 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/bin/sub_commands/status.py
--rw-r--r--   0        0        0       44 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/builder/__init__.py
--rwxr-xr-x   0        0        0     1578 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/builder/concat_df.py
--rw-r--r--   0        0        0       44 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/builder/dbdb/__init__.py
--rwxr-xr-x   0        0        0     5103 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/builder/dbdb/file_info.py
--rwxr-xr-x   0        0        0     6439 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/builder/df_list.py
--rwxr-xr-x   0        0        0     1696 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/builder/df_path.py
--rwxr-xr-x   0        0        0     3473 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/builder/meta_db.py
--rwxr-xr-x   0        0        0     6558 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/builder/statistic_db.py
--rw-r--r--   0        0        0      697 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/conf/v1.yaml
--rw-r--r--   0        0        0     1477 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/conf/v2.yaml
--rw-r--r--   0        0        0     2553 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/conf/v3.yaml
--rw-r--r--   0        0        0     2424 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/conf/v4.yaml
--rw-r--r--   0        0        0     1093 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/__init__.py
--rw-r--r--   0        0        0      305 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/exceptions.py
--rw-r--r--   0        0        0     4028 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/__init__.py
--rw-r--r--   0        0        0        0 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/__init__.py
--rw-r--r--   0        0        0        0 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/__init__.py
--rw-r--r--   0        0        0      504 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation.py
--rw-r--r--   0        0        0     1019 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_image_pixel.py
--rw-r--r--   0        0        0     1283 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_image_rectangular_area.py
--rw-r--r--   0        0        0      813 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_point.py
--rw-r--r--   0        0        0      512 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/file.py
--rw-r--r--   0        0        0      399 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/record.py
--rw-r--r--   0        0        0        0 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/__init__.py
--rw-r--r--   0        0        0      541 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation.py
--rw-r--r--   0        0        0     1019 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_image_pixel.py
--rw-r--r--   0        0        0     1283 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_image_rectangular_area.py
--rw-r--r--   0        0        0      813 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_point.py
--rw-r--r--   0        0        0      891 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/file.py
--rw-r--r--   0        0        0      780 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/record.py
--rw-r--r--   0        0        0        0 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/__init__.py
--rw-r--r--   0        0        0      541 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation.py
--rw-r--r--   0        0        0     1019 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_image_pixel.py
--rw-r--r--   0        0        0     1285 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_image_rectangular_area.py
--rw-r--r--   0        0        0      813 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_point.py
--rw-r--r--   0        0        0      891 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/file.py
--rw-r--r--   0        0        0      780 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/record.py
--rw-r--r--   0        0        0        0 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha4/__init__.py
--rw-r--r--   0        0        0      574 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation.py
--rw-r--r--   0        0        0     1019 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_image_pixel.py
--rw-r--r--   0        0        0     1285 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_image_rectangular_area.py
--rw-r--r--   0        0        0      813 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_point.py
--rw-r--r--   0        0        0        0 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/__init__.py
--rw-r--r--   0        0        0      574 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation.py
--rw-r--r--   0        0        0     1023 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_image_pixel.py
--rw-r--r--   0        0        0     1248 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_image_rectangular_area.py
--rw-r--r--   0        0        0      813 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_point.py
--rw-r--r--   0        0        0      820 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/arbitrary_annotation.py
--rw-r--r--   0        0        0      193 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v1/__init__.py
--rw-r--r--   0        0        0     6462 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v1/handlers/__init__.py
--rw-r--r--   0        0        0     4875 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v1/handlers/meta.py
--rw-r--r--   0        0        0      360 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v2/__init__.py
--rw-r--r--   0        0        0    18286 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v2/handlers/__init__.py
--rw-r--r--   0        0        0     4481 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v2/handlers/meta.py
--rw-r--r--   0        0        0     1494 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v2/search_engines/__init__.py
--rw-r--r--   0        0        0     1813 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v2/search_engines/time_series.py
--rw-r--r--   0        0        0      562 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v3/__init__.py
--rw-r--r--   0        0        0    21654 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v3/handlers/__init__.py
--rw-r--r--   0        0        0     9873 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v3/handlers/meta.py
--rw-r--r--   0        0        0     4772 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v3/handlers/statistics.py
--rw-r--r--   0        0        0    11861 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v3/handlers/time_series.py
--rw-r--r--   0        0        0     4376 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v3/search_engines/__init__.py
--rw-r--r--   0        0        0     2383 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v3/search_engines/time_series.py
--rw-r--r--   0        0        0      288 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v4/__init__.py
--rw-r--r--   0        0        0      271 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v4/deps/__init__.py
--rw-r--r--   0        0        0       66 2023-06-21 07:48:07.694637 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/.git
--rw-r--r--   0        0        0       61 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/.gitignore
--rw-r--r--   0        0        0     1496 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/LICENSE
--rw-r--r--   0        0        0     7682 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/README.md
--rw-r--r--   0        0        0     5531 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/aggregation_tests.py
--rw-r--r--   0        0        0     7885 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/find_tests.py
--rw-r--r--   0        0        0     3066 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/pql/__init__.py
--rw-r--r--   0        0        0     4848 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/pql/aggregation.py
--rw-r--r--   0        0        0    14159 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/pql/matching.py
--rw-r--r--   0        0        0      929 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/setup.py
--rw-r--r--   0        0        0       64 2023-06-21 07:48:09.038640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/tox.ini
--rw-r--r--   0        0        0       66 2023-06-21 07:48:08.110638 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/.git
--rw-r--r--   0        0        0       61 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/.gitignore
--rw-r--r--   0        0        0     1496 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/LICENSE
--rw-r--r--   0        0        0     7682 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/README.md
--rw-r--r--   0        0        0     5531 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/aggregation_tests.py
--rw-r--r--   0        0        0     8389 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/find_tests.py
--rw-r--r--   0        0        0     3066 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/pql/__init__.py
--rw-r--r--   0        0        0     4848 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/pql/aggregation.py
--rw-r--r--   0        0        0    15543 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/pql/matching.py
--rw-r--r--   0        0        0     1116 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/setup.py
--rw-r--r--   0        0        0      112 2023-06-21 07:48:09.046640 pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/tox.ini
--rw-r--r--   0        0        0      924 2023-06-21 07:48:07.202635 pydtk-0.3.0/pydtk/db/v4/engines/__init__.py
--rw-r--r--   0        0        0     6284 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/db/v4/engines/mongodb.py
--rw-r--r--   0        0        0     5531 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/db/v4/engines/montydb.py
--rw-r--r--   0        0        0     2854 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/db/v4/engines/tinydb.py
--rw-r--r--   0        0        0     5688 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/db/v4/engines/tinymongo.py
--rw-r--r--   0        0        0    26376 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/db/v4/handlers/__init__.py
--rw-r--r--   0        0        0     3048 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/db/v4/handlers/annotation.py
--rw-r--r--   0        0        0    16169 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/db/v4/handlers/meta.py
--rwxr-xr-x   0        0        0     1456 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/frontend.py
--rw-r--r--   0        0        0      256 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/io/__init__.py
--rw-r--r--   0        0        0      187 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/io/errors.py
--rw-r--r--   0        0        0     4608 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/io/reader.py
--rw-r--r--   0        0        0     2459 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/io/writer.py
--rw-r--r--   0        0        0    18475 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/__init__.py
--rw-r--r--   0        0        0       67 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/autoware/__init__.py
--rw-r--r--   0        0        0     2336 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/autoware/can_packet.py
--rw-r--r--   0        0        0     6941 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/csv.py
--rw-r--r--   0        0        0     1969 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/image.py
--rw-r--r--   0        0        0     2286 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/json_model.py
--rw-r--r--   0        0        0    11670 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/movie.py
--rw-r--r--   0        0        0       58 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/pointcloud/__init__.py
--rw-r--r--   0        0        0     3413 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/pointcloud/pcd.py
--rw-r--r--   0        0        0    11035 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/rosbag.py
--rw-r--r--   0        0        0    14847 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/rosbag2.py
--rw-r--r--   0        0        0       65 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/zstd/__init__.py
--rw-r--r--   0        0        0     4344 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/models/zstd/rosbag.py
--rw-r--r--   0        0        0      131 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/preprocesses/__init__.py
--rwxr-xr-x   0        0        0     2527 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/preprocesses/downsampling.py
--rwxr-xr-x   0        0        0      929 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/preprocesses/passthrough.py
--rwxr-xr-x   0        0        0      352 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/preprocesses/preprocess.py
--rw-r--r--   0        0        0     3626 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/statistics/__init__.py
--rwxr-xr-x   0        0        0     8472 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/statistics/calculator.py
--rw-r--r--   0        0        0       44 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/utils/__init__.py
--rw-r--r--   0        0        0    17583 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/utils/can_decoder.py
--rwxr-xr-x   0        0        0     2728 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/utils/fileutils.py
--rw-r--r--   0        0        0      413 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/utils/imports.py
--rwxr-xr-x   0        0        0     7443 2023-06-21 07:48:07.206635 pydtk-0.3.0/pydtk/utils/utils.py
--rwxr-xr-x   0        0        0     2765 2023-06-21 07:48:22.246693 pydtk-0.3.0/pyproject.toml
--rw-r--r--   0        0        0     4704 1970-01-01 00:00:00.000000 pydtk-0.3.0/PKG-INFO
+-rw-r--r--   0        0        0    11340 2023-06-28 01:25:59.517389 pydtk-0.3.1/LICENSE
+-rw-r--r--   0        0        0     2570 2023-06-28 01:25:59.517389 pydtk-0.3.1/README.md
+-rw-r--r--   0        0        0      103 2023-06-28 01:26:13.565840 pydtk-0.3.1/pydtk/__init__.py
+-rw-r--r--   0        0        0       44 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/bin/__init__.py
+-rwxr-xr-x   0        0        0     2184 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/bin/cli.py
+-rwxr-xr-x   0        0        0     3649 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/bin/make_meta.py
+-rw-r--r--   0        0        0     2595 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/bin/oas.py
+-rw-r--r--   0        0        0       28 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/bin/sub_commands/__init__.py
+-rw-r--r--   0        0        0    14756 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/bin/sub_commands/db.py
+-rw-r--r--   0        0        0      563 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/bin/sub_commands/io.py
+-rw-r--r--   0        0        0     4272 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/bin/sub_commands/model.py
+-rw-r--r--   0        0        0     1501 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/bin/sub_commands/status.py
+-rw-r--r--   0        0        0       44 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/builder/__init__.py
+-rwxr-xr-x   0        0        0     1578 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/builder/concat_df.py
+-rw-r--r--   0        0        0       44 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/builder/dbdb/__init__.py
+-rwxr-xr-x   0        0        0     5103 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/builder/dbdb/file_info.py
+-rwxr-xr-x   0        0        0     6439 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/builder/df_list.py
+-rwxr-xr-x   0        0        0     1696 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/builder/df_path.py
+-rwxr-xr-x   0        0        0     3473 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/builder/meta_db.py
+-rwxr-xr-x   0        0        0     6558 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/builder/statistic_db.py
+-rw-r--r--   0        0        0      697 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/conf/v1.yaml
+-rw-r--r--   0        0        0     1477 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/conf/v2.yaml
+-rw-r--r--   0        0        0     2553 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/conf/v3.yaml
+-rw-r--r--   0        0        0     2424 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/conf/v4.yaml
+-rw-r--r--   0        0        0     1093 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/__init__.py
+-rw-r--r--   0        0        0      305 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/exceptions.py
+-rw-r--r--   0        0        0     4076 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/__init__.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/__init__.py
+-rw-r--r--   0        0        0      504 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation.py
+-rw-r--r--   0        0        0     1019 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_image_pixel.py
+-rw-r--r--   0        0        0     1283 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_image_rectangular_area.py
+-rw-r--r--   0        0        0      813 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_point.py
+-rw-r--r--   0        0        0      512 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/file.py
+-rw-r--r--   0        0        0      399 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/record.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/__init__.py
+-rw-r--r--   0        0        0      541 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation.py
+-rw-r--r--   0        0        0     1019 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_image_pixel.py
+-rw-r--r--   0        0        0     1283 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_image_rectangular_area.py
+-rw-r--r--   0        0        0      813 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_point.py
+-rw-r--r--   0        0        0      891 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/file.py
+-rw-r--r--   0        0        0      780 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/record.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/__init__.py
+-rw-r--r--   0        0        0      541 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation.py
+-rw-r--r--   0        0        0     1019 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_image_pixel.py
+-rw-r--r--   0        0        0     1285 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_image_rectangular_area.py
+-rw-r--r--   0        0        0      813 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_point.py
+-rw-r--r--   0        0        0      891 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/file.py
+-rw-r--r--   0        0        0      780 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/record.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha4/__init__.py
+-rw-r--r--   0        0        0      574 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation.py
+-rw-r--r--   0        0        0     1019 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_image_pixel.py
+-rw-r--r--   0        0        0     1285 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_image_rectangular_area.py
+-rw-r--r--   0        0        0      813 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_point.py
+-rw-r--r--   0        0        0        0 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/__init__.py
+-rw-r--r--   0        0        0      574 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation.py
+-rw-r--r--   0        0        0     1023 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_image_pixel.py
+-rw-r--r--   0        0        0     1248 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_image_rectangular_area.py
+-rw-r--r--   0        0        0      813 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_point.py
+-rw-r--r--   0        0        0      820 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/arbitrary_annotation.py
+-rw-r--r--   0        0        0      193 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v1/__init__.py
+-rw-r--r--   0        0        0     6462 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v1/handlers/__init__.py
+-rw-r--r--   0        0        0     4875 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v1/handlers/meta.py
+-rw-r--r--   0        0        0      360 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v2/__init__.py
+-rw-r--r--   0        0        0    18286 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v2/handlers/__init__.py
+-rw-r--r--   0        0        0     4481 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v2/handlers/meta.py
+-rw-r--r--   0        0        0     1494 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v2/search_engines/__init__.py
+-rw-r--r--   0        0        0     1813 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v2/search_engines/time_series.py
+-rw-r--r--   0        0        0      562 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v3/__init__.py
+-rw-r--r--   0        0        0    21654 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v3/handlers/__init__.py
+-rw-r--r--   0        0        0     9873 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v3/handlers/meta.py
+-rw-r--r--   0        0        0     4772 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v3/handlers/statistics.py
+-rw-r--r--   0        0        0    11861 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v3/handlers/time_series.py
+-rw-r--r--   0        0        0     4376 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v3/search_engines/__init__.py
+-rw-r--r--   0        0        0     2383 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v3/search_engines/time_series.py
+-rw-r--r--   0        0        0      288 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v4/__init__.py
+-rw-r--r--   0        0        0      271 2023-06-28 01:25:59.521389 pydtk-0.3.1/pydtk/db/v4/deps/__init__.py
+-rw-r--r--   0        0        0       66 2023-06-28 01:26:00.033402 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/.git
+-rw-r--r--   0        0        0       61 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/.gitignore
+-rw-r--r--   0        0        0     1496 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/LICENSE
+-rw-r--r--   0        0        0     7682 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/README.md
+-rw-r--r--   0        0        0     5531 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/aggregation_tests.py
+-rw-r--r--   0        0        0     7885 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/find_tests.py
+-rw-r--r--   0        0        0     3066 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/pql/__init__.py
+-rw-r--r--   0        0        0     4848 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/pql/aggregation.py
+-rw-r--r--   0        0        0    14159 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/pql/matching.py
+-rw-r--r--   0        0        0      929 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/setup.py
+-rw-r--r--   0        0        0       64 2023-06-28 01:26:01.417435 pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/tox.ini
+-rw-r--r--   0        0        0       66 2023-06-28 01:26:00.457412 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/.git
+-rw-r--r--   0        0        0       61 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/.gitignore
+-rw-r--r--   0        0        0     1496 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/LICENSE
+-rw-r--r--   0        0        0     7682 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/README.md
+-rw-r--r--   0        0        0     5531 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/aggregation_tests.py
+-rw-r--r--   0        0        0     8389 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/find_tests.py
+-rw-r--r--   0        0        0     3066 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/pql/__init__.py
+-rw-r--r--   0        0        0     4848 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/pql/aggregation.py
+-rw-r--r--   0        0        0    15543 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/pql/matching.py
+-rw-r--r--   0        0        0     1116 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/setup.py
+-rw-r--r--   0        0        0      112 2023-06-28 01:26:01.425436 pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/tox.ini
+-rw-r--r--   0        0        0      924 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/db/v4/engines/__init__.py
+-rw-r--r--   0        0        0     6284 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/db/v4/engines/mongodb.py
+-rw-r--r--   0        0        0     5531 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/db/v4/engines/montydb.py
+-rw-r--r--   0        0        0     2854 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/db/v4/engines/tinydb.py
+-rw-r--r--   0        0        0     5688 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/db/v4/engines/tinymongo.py
+-rw-r--r--   0        0        0    26376 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/db/v4/handlers/__init__.py
+-rw-r--r--   0        0        0     3048 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/db/v4/handlers/annotation.py
+-rw-r--r--   0        0        0    16169 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/db/v4/handlers/meta.py
+-rwxr-xr-x   0        0        0     1456 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/frontend.py
+-rw-r--r--   0        0        0      256 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/io/__init__.py
+-rw-r--r--   0        0        0      187 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/io/errors.py
+-rw-r--r--   0        0        0     4608 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/io/reader.py
+-rw-r--r--   0        0        0     2459 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/io/writer.py
+-rw-r--r--   0        0        0    18475 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/__init__.py
+-rw-r--r--   0        0        0       67 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/autoware/__init__.py
+-rw-r--r--   0        0        0     2336 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/autoware/can_packet.py
+-rw-r--r--   0        0        0     6941 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/csv.py
+-rw-r--r--   0        0        0     1969 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/image.py
+-rw-r--r--   0        0        0     2286 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/json_model.py
+-rw-r--r--   0        0        0    11670 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/movie.py
+-rw-r--r--   0        0        0       58 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/pointcloud/__init__.py
+-rw-r--r--   0        0        0     3413 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/pointcloud/pcd.py
+-rw-r--r--   0        0        0    11035 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/rosbag.py
+-rw-r--r--   0        0        0    14847 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/rosbag2.py
+-rw-r--r--   0        0        0       65 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/zstd/__init__.py
+-rw-r--r--   0        0        0     4344 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/models/zstd/rosbag.py
+-rw-r--r--   0        0        0      131 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/preprocesses/__init__.py
+-rwxr-xr-x   0        0        0     2527 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/preprocesses/downsampling.py
+-rwxr-xr-x   0        0        0      929 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/preprocesses/passthrough.py
+-rwxr-xr-x   0        0        0      352 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/preprocesses/preprocess.py
+-rw-r--r--   0        0        0     3626 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/statistics/__init__.py
+-rwxr-xr-x   0        0        0     8472 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/statistics/calculator.py
+-rw-r--r--   0        0        0       44 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/utils/__init__.py
+-rw-r--r--   0        0        0    17583 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/utils/can_decoder.py
+-rwxr-xr-x   0        0        0     2728 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/utils/fileutils.py
+-rw-r--r--   0        0        0      413 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/utils/imports.py
+-rwxr-xr-x   0        0        0     7443 2023-06-28 01:25:59.525389 pydtk-0.3.1/pydtk/utils/utils.py
+-rwxr-xr-x   0        0        0     2765 2023-06-28 01:26:13.561840 pydtk-0.3.1/pyproject.toml
+-rw-r--r--   0        0        0     4704 1970-01-01 00:00:00.000000 pydtk-0.3.1/PKG-INFO
```

### Comparing `pydtk-0.3.0/LICENSE` & `pydtk-0.3.1/LICENSE`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/README.md` & `pydtk-0.3.1/README.md`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/bin/cli.py` & `pydtk-0.3.1/pydtk/bin/cli.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/bin/make_meta.py` & `pydtk-0.3.1/pydtk/bin/make_meta.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/bin/oas.py` & `pydtk-0.3.1/pydtk/bin/oas.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/bin/sub_commands/db.py` & `pydtk-0.3.1/pydtk/bin/sub_commands/db.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/bin/sub_commands/io.py` & `pydtk-0.3.1/pydtk/bin/sub_commands/io.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/bin/sub_commands/model.py` & `pydtk-0.3.1/pydtk/bin/sub_commands/model.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/bin/sub_commands/status.py` & `pydtk-0.3.1/pydtk/bin/sub_commands/status.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/builder/concat_df.py` & `pydtk-0.3.1/pydtk/builder/concat_df.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/builder/dbdb/file_info.py` & `pydtk-0.3.1/pydtk/builder/dbdb/file_info.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/builder/df_list.py` & `pydtk-0.3.1/pydtk/builder/df_list.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/builder/df_path.py` & `pydtk-0.3.1/pydtk/builder/df_path.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/builder/meta_db.py` & `pydtk-0.3.1/pydtk/builder/meta_db.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/builder/statistic_db.py` & `pydtk-0.3.1/pydtk/builder/statistic_db.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/conf/v1.yaml` & `pydtk-0.3.1/pydtk/conf/v1.yaml`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/conf/v2.yaml` & `pydtk-0.3.1/pydtk/conf/v2.yaml`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/conf/v3.yaml` & `pydtk-0.3.1/pydtk/conf/v3.yaml`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/conf/v4.yaml` & `pydtk-0.3.1/pydtk/conf/v4.yaml`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/__init__.py` & `pydtk-0.3.1/pydtk/db/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/__init__.py` & `pydtk-0.3.1/pydtk/db/schemas/__init__.py`

 * *Files 12% similar despite different names*

```diff
@@ -2,14 +2,15 @@
 import glob
 import importlib
 import inspect
 import logging
 import os
 import pathlib
 from importlib.util import spec_from_file_location
+from typing import Optional
 
 from pydantic import BaseModel, Field, constr
 
 from pydtk.db.exceptions import SchemaNotFoundError
 
 SCHEMAS_BY_VERSIONS = {}  # key: api_version, value: {kind: {"schema": schema}}
 SCHEMAS_BY_FILES = {}  # key: relative file path, value: list of schemas}
@@ -55,20 +56,20 @@
 
     return decorator()
 
 
 class BaseSchema(BaseModel):
     """BaseSchema."""
 
-    api_version: constr(min_length=1, strict=True) = Field(
+    api_version: Optional[constr(min_length=1, strict=True)] = Field(
         ...,
         description="Schema version information.",
         alias="_api_version",
     )
-    kind: constr(min_length=1, strict=True) = Field(
+    kind: Optional[constr(min_length=1, strict=True)] = Field(
         ...,
         description="Kind of information",
         alias="_kind",
     )
     # NOTE(kan-bayashi): `_uuid` and `_creation_time` will be created by pydtk
     #   and therefore we do not validate them.
     # uuid: constr(min_length=1, strict=True) = Field(
```

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_image_pixel.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_image_pixel.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_image_rectangular_area.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_image_rectangular_area.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_point.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/annotation_commented_point.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha1/file.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha1/file.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_image_pixel.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_image_pixel.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_image_rectangular_area.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_image_rectangular_area.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_point.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/annotation_commented_point.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/file.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/file.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha2/record.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha2/record.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_image_pixel.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_image_pixel.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_image_rectangular_area.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_image_rectangular_area.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_point.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/annotation_commented_point.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/file.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/file.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha3/record.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha3/record.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_image_pixel.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_image_pixel.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_image_rectangular_area.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_image_rectangular_area.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_point.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha4/annotation_commented_point.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_image_pixel.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_image_pixel.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_image_rectangular_area.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_image_rectangular_area.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_point.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/annotation_commented_point.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/schemas/dataware-tools.com/v1alpha5/arbitrary_annotation.py` & `pydtk-0.3.1/pydtk/db/schemas/dataware-tools.com/v1alpha5/arbitrary_annotation.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v1/handlers/__init__.py` & `pydtk-0.3.1/pydtk/db/v1/handlers/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v1/handlers/meta.py` & `pydtk-0.3.1/pydtk/db/v1/handlers/meta.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v2/handlers/__init__.py` & `pydtk-0.3.1/pydtk/db/v2/handlers/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v2/handlers/meta.py` & `pydtk-0.3.1/pydtk/db/v2/handlers/meta.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v2/search_engines/__init__.py` & `pydtk-0.3.1/pydtk/db/v2/search_engines/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v2/search_engines/time_series.py` & `pydtk-0.3.1/pydtk/db/v2/search_engines/time_series.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v3/__init__.py` & `pydtk-0.3.1/pydtk/db/v3/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v3/handlers/__init__.py` & `pydtk-0.3.1/pydtk/db/v3/handlers/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v3/handlers/meta.py` & `pydtk-0.3.1/pydtk/db/v3/handlers/meta.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v3/handlers/statistics.py` & `pydtk-0.3.1/pydtk/db/v3/handlers/statistics.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v3/handlers/time_series.py` & `pydtk-0.3.1/pydtk/db/v3/handlers/time_series.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v3/search_engines/__init__.py` & `pydtk-0.3.1/pydtk/db/v3/search_engines/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v3/search_engines/time_series.py` & `pydtk-0.3.1/pydtk/db/v3/search_engines/time_series.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/LICENSE` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/LICENSE`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/README.md` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/README.md`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/aggregation_tests.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/aggregation_tests.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/find_tests.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/find_tests.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/pql/__init__.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/pql/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/pql/aggregation.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/pql/aggregation.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/pql/matching.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/pql/matching.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python37/setup.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python37/setup.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/LICENSE` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/LICENSE`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/README.md` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/README.md`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/aggregation_tests.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/aggregation_tests.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/find_tests.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/find_tests.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/pql/__init__.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/pql/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/pql/aggregation.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/pql/aggregation.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/pql/matching.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/pql/matching.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/deps/pql_python38/setup.py` & `pydtk-0.3.1/pydtk/db/v4/deps/pql_python38/setup.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/engines/__init__.py` & `pydtk-0.3.1/pydtk/db/v4/engines/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/engines/mongodb.py` & `pydtk-0.3.1/pydtk/db/v4/engines/mongodb.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/engines/montydb.py` & `pydtk-0.3.1/pydtk/db/v4/engines/montydb.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/engines/tinydb.py` & `pydtk-0.3.1/pydtk/db/v4/engines/tinydb.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/engines/tinymongo.py` & `pydtk-0.3.1/pydtk/db/v4/engines/tinymongo.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/handlers/__init__.py` & `pydtk-0.3.1/pydtk/db/v4/handlers/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/handlers/annotation.py` & `pydtk-0.3.1/pydtk/db/v4/handlers/annotation.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/db/v4/handlers/meta.py` & `pydtk-0.3.1/pydtk/db/v4/handlers/meta.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/frontend.py` & `pydtk-0.3.1/pydtk/frontend.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/io/reader.py` & `pydtk-0.3.1/pydtk/io/reader.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/io/writer.py` & `pydtk-0.3.1/pydtk/io/writer.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/__init__.py` & `pydtk-0.3.1/pydtk/models/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/autoware/can_packet.py` & `pydtk-0.3.1/pydtk/models/autoware/can_packet.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/csv.py` & `pydtk-0.3.1/pydtk/models/csv.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/image.py` & `pydtk-0.3.1/pydtk/models/image.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/json_model.py` & `pydtk-0.3.1/pydtk/models/json_model.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/movie.py` & `pydtk-0.3.1/pydtk/models/movie.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/pointcloud/pcd.py` & `pydtk-0.3.1/pydtk/models/pointcloud/pcd.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/rosbag.py` & `pydtk-0.3.1/pydtk/models/rosbag.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/rosbag2.py` & `pydtk-0.3.1/pydtk/models/rosbag2.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/models/zstd/rosbag.py` & `pydtk-0.3.1/pydtk/models/zstd/rosbag.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/preprocesses/downsampling.py` & `pydtk-0.3.1/pydtk/preprocesses/downsampling.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/preprocesses/passthrough.py` & `pydtk-0.3.1/pydtk/preprocesses/passthrough.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/statistics/__init__.py` & `pydtk-0.3.1/pydtk/statistics/__init__.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/statistics/calculator.py` & `pydtk-0.3.1/pydtk/statistics/calculator.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/utils/can_decoder.py` & `pydtk-0.3.1/pydtk/utils/can_decoder.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/utils/fileutils.py` & `pydtk-0.3.1/pydtk/utils/fileutils.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pydtk/utils/utils.py` & `pydtk-0.3.1/pydtk/utils/utils.py`

 * *Files identical despite different names*

### Comparing `pydtk-0.3.0/pyproject.toml` & `pydtk-0.3.1/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["poetry >= 1.0.0", "setuptools >= 50.3.0", "wheel >= 0.35.1", "pip >= 21.0.0"]
 build-backend = "poetry.masonry.api"
 
 [tool.poetry]
 name = "pydtk"
-version = "0.3.0"
+version = "0.3.1"
 description = "A Python toolkit for managing, retrieving and processing data."
 license = "Apache-2.0"
 authors = [
     "Yusuke Adachi <adachi.yusuke@hdwlab.co.jp>",
     "Daiki Hayashi <hayashi.daiki@hdwlab.co.jp>",
     "Toshimitsu Watanabe <watanabe.toshimitsu@hdwlab.co.jp>"
 ]
```

### Comparing `pydtk-0.3.0/PKG-INFO` & `pydtk-0.3.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pydtk
-Version: 0.3.0
+Version: 0.3.1
 Summary: A Python toolkit for managing, retrieving and processing data.
 Home-page: https://github.com/dataware-tools/python-toolkit.git
 License: Apache-2.0
 Keywords: toolkit,data,dataware,metadata
 Author: Yusuke Adachi
 Author-email: adachi.yusuke@hdwlab.co.jp
 Requires-Python: >=3.8,<3.11
```


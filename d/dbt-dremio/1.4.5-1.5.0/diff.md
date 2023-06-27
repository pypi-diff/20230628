# Comparing `tmp/dbt-dremio-1.4.5.tar.gz` & `tmp/dbt-dremio-1.5.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dbt-dremio-1.4.5.tar", last modified: Mon Mar 27 18:05:24 2023, max compression
+gzip compressed data, was "dbt-dremio-1.5.0.tar", last modified: Thu Jun 22 17:13:29 2023, max compression
```

## Comparing `dbt-dremio-1.4.5.tar` & `dbt-dremio-1.5.0.tar`

### file list

```diff
@@ -1,85 +1,85 @@
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.637420 dbt-dremio-1.4.5/
--rw-r--r--   0 jaredl     (504) staff       (20)    11348 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/LICENSE
--rw-r--r--   0 jaredl     (504) staff       (20)       47 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/MANIFEST.in
--rw-r--r--   0 jaredl     (504) staff       (20)      562 2023-03-27 18:05:24.637513 dbt-dremio-1.4.5/PKG-INFO
--rw-r--r--   0 jaredl     (504) staff       (20)     2880 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/README.md
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.609568 dbt-dremio-1.4.5/dbt/
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.609038 dbt-dremio-1.4.5/dbt/adapters/
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.616296 dbt-dremio-1.4.5/dbt/adapters/dremio/
--rw-r--r--   0 jaredl     (504) staff       (20)      965 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/__init__.py
--rw-r--r--   0 jaredl     (504) staff       (20)      595 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/__version__.py
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.618773 dbt-dremio-1.4.5/dbt/adapters/dremio/api/
--rw-r--r--   0 jaredl     (504) staff       (20)      737 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/api/__init__.py
--rw-r--r--   0 jaredl     (504) staff       (20)     2248 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/api/authentication.py
--rw-r--r--   0 jaredl     (504) staff       (20)     6111 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/api/cursor.py
--rw-r--r--   0 jaredl     (504) staff       (20)     1552 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/api/handle.py
--rw-r--r--   0 jaredl     (504) staff       (20)     3678 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/api/parameters.py
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.620353 dbt-dremio-1.4.5/dbt/adapters/dremio/api/rest/
--rw-r--r--   0 jaredl     (504) staff       (20)     7551 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/api/rest/endpoints.py
--rw-r--r--   0 jaredl     (504) staff       (20)     1661 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/api/rest/error.py
--rw-r--r--   0 jaredl     (504) staff       (20)     4914 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/api/rest/url_builder.py
--rw-r--r--   0 jaredl     (504) staff       (20)     8507 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/connections.py
--rw-r--r--   0 jaredl     (504) staff       (20)     3814 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/credentials.py
--rw-r--r--   0 jaredl     (504) staff       (20)     5769 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/impl.py
--rw-r--r--   0 jaredl     (504) staff       (20)     2745 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/adapters/dremio/relation.py
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.609686 dbt-dremio-1.4.5/dbt/include/
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.621500 dbt-dremio-1.4.5/dbt/include/dremio/
--rw-r--r--   0 jaredl     (504) staff       (20)       52 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/__init__.py
--rw-r--r--   0 jaredl     (504) staff       (20)      815 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/dbt_project.yml
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.611643 dbt-dremio-1.4.5/dbt/include/dremio/macros/
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.625094 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/
--rw-r--r--   0 jaredl     (504) staff       (20)     2237 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/apply_grants.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     3980 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/columns.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     2540 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/data_preparation.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1985 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/external_query.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     5681 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/format.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     8334 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/metadata.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1518 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/relation.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1080 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/snapshot.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1932 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/sources.sql
--rw-r--r--   0 jaredl     (504) staff       (20)      648 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/timestamp.sql
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.625414 dbt-dremio-1.4.5/dbt/include/dremio/macros/builtins/
--rw-r--r--   0 jaredl     (504) staff       (20)     2369 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/builtins/builtins.sql
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.627326 dbt-dremio-1.4.5/dbt/include/dremio/macros/get_custom_name/
--rw-r--r--   0 jaredl     (504) staff       (20)     1079 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/get_custom_name/get_custom_alias.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1223 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/get_custom_name/get_custom_database.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1185 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/get_custom_name/get_custom_schema.sql
--rw-r--r--   0 jaredl     (504) staff       (20)      791 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/get_custom_name/is_datalake_node.sql
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.627911 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/
--rw-r--r--   0 jaredl     (504) staff       (20)     1604 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/helpers.sql
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.628739 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/incremental/
--rw-r--r--   0 jaredl     (504) staff       (20)     5161 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/incremental/incremental.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1613 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/incremental/strategies.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1502 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/incremental/validate.sql
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.629779 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/reflection/
--rw-r--r--   0 jaredl     (504) staff       (20)     4326 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/reflection/create_reflection.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1448 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/reflection/helpers.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     4388 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/reflection/reflection.sql
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.630525 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/seed/
--rw-r--r--   0 jaredl     (504) staff       (20)     1823 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/seed/helpers.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     2401 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/seed/seed.sql
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.631709 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/table/
--rw-r--r--   0 jaredl     (504) staff       (20)     1956 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/table/alter_pds.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1806 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/table/create_table_as.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1999 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/table/table.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     2425 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/twin_strategy.sql
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.633356 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/view/
--rw-r--r--   0 jaredl     (504) staff       (20)     1445 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/view/create_or_replace_view.sql
--rw-r--r--   0 jaredl     (504) staff       (20)      803 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/view/create_view_as.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1393 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/view/helpers.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     1997 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/view/view.sql
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.635520 dbt-dremio-1.4.5/dbt/include/dremio/macros/utils/
--rw-r--r--   0 jaredl     (504) staff       (20)      732 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/utils/array_append.sql
--rw-r--r--   0 jaredl     (504) staff       (20)      730 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/utils/array_concat.sql
--rw-r--r--   0 jaredl     (504) staff       (20)      848 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/utils/array_construct.sql
--rw-r--r--   0 jaredl     (504) staff       (20)      104 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/macros/utils/data_types.sql
--rw-r--r--   0 jaredl     (504) staff       (20)     2097 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/dbt/include/dremio/profile_template.yml
-drwxr-xr-x   0 jaredl     (504) staff       (20)        0 2023-03-27 18:05:24.637082 dbt-dremio-1.4.5/dbt_dremio.egg-info/
--rw-r--r--   0 jaredl     (504) staff       (20)      562 2023-03-27 18:05:24.000000 dbt-dremio-1.4.5/dbt_dremio.egg-info/PKG-INFO
--rw-r--r--   0 jaredl     (504) staff       (20)     2942 2023-03-27 18:05:24.000000 dbt-dremio-1.4.5/dbt_dremio.egg-info/SOURCES.txt
--rw-r--r--   0 jaredl     (504) staff       (20)        1 2023-03-27 18:05:24.000000 dbt-dremio-1.4.5/dbt_dremio.egg-info/dependency_links.txt
--rw-r--r--   0 jaredl     (504) staff       (20)       22 2023-03-27 18:05:24.000000 dbt-dremio-1.4.5/dbt_dremio.egg-info/requires.txt
--rw-r--r--   0 jaredl     (504) staff       (20)        4 2023-03-27 18:05:24.000000 dbt-dremio-1.4.5/dbt_dremio.egg-info/top_level.txt
--rw-r--r--   0 jaredl     (504) staff       (20)       87 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/pyproject.toml
--rw-r--r--   0 jaredl     (504) staff       (20)       74 2023-03-27 18:05:24.637869 dbt-dremio-1.4.5/setup.cfg
--rw-r--r--   0 jaredl     (504) staff       (20)     1486 2023-03-24 19:08:13.000000 dbt-dremio-1.4.5/setup.py
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.505647 dbt-dremio-1.5.0/
+-rw-r--r--   0 argusl     (503) staff       (20)    11348 2022-11-03 22:51:28.000000 dbt-dremio-1.5.0/LICENSE
+-rw-r--r--   0 argusl     (503) staff       (20)       47 2022-11-03 22:51:28.000000 dbt-dremio-1.5.0/MANIFEST.in
+-rw-r--r--   0 argusl     (503) staff       (20)      562 2023-06-22 17:13:29.505738 dbt-dremio-1.5.0/PKG-INFO
+-rw-r--r--   0 argusl     (503) staff       (20)     2880 2023-06-22 16:42:28.000000 dbt-dremio-1.5.0/README.md
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.456052 dbt-dremio-1.5.0/dbt/
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.455489 dbt-dremio-1.5.0/dbt/adapters/
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.476951 dbt-dremio-1.5.0/dbt/adapters/dremio/
+-rw-r--r--   0 argusl     (503) staff       (20)      965 2022-11-03 22:51:28.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/__init__.py
+-rw-r--r--   0 argusl     (503) staff       (20)      595 2023-06-22 16:42:28.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/__version__.py
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.481469 dbt-dremio-1.5.0/dbt/adapters/dremio/api/
+-rw-r--r--   0 argusl     (503) staff       (20)      737 2022-11-03 22:51:28.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/api/__init__.py
+-rw-r--r--   0 argusl     (503) staff       (20)     2248 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/api/authentication.py
+-rw-r--r--   0 argusl     (503) staff       (20)     6111 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/api/cursor.py
+-rw-r--r--   0 argusl     (503) staff       (20)     1552 2022-11-03 22:51:28.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/api/handle.py
+-rw-r--r--   0 argusl     (503) staff       (20)     3678 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/api/parameters.py
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.483657 dbt-dremio-1.5.0/dbt/adapters/dremio/api/rest/
+-rw-r--r--   0 argusl     (503) staff       (20)     7551 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/api/rest/endpoints.py
+-rw-r--r--   0 argusl     (503) staff       (20)     1661 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/api/rest/error.py
+-rw-r--r--   0 argusl     (503) staff       (20)     4914 2022-12-09 17:11:33.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/api/rest/url_builder.py
+-rw-r--r--   0 argusl     (503) staff       (20)     8507 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/connections.py
+-rw-r--r--   0 argusl     (503) staff       (20)     4138 2023-06-22 16:42:28.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/credentials.py
+-rw-r--r--   0 argusl     (503) staff       (20)     5769 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/impl.py
+-rw-r--r--   0 argusl     (503) staff       (20)     2745 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/adapters/dremio/relation.py
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.456189 dbt-dremio-1.5.0/dbt/include/
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.485736 dbt-dremio-1.5.0/dbt/include/dremio/
+-rw-r--r--   0 argusl     (503) staff       (20)       52 2022-11-03 22:51:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/__init__.py
+-rw-r--r--   0 argusl     (503) staff       (20)      815 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/dbt_project.yml
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.457928 dbt-dremio-1.5.0/dbt/include/dremio/macros/
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.490191 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/
+-rw-r--r--   0 argusl     (503) staff       (20)     2237 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/apply_grants.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     3980 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/columns.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     2540 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/data_preparation.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1985 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/external_query.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     5681 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/format.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     8334 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/metadata.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1518 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/relation.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1080 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/snapshot.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1932 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/sources.sql
+-rw-r--r--   0 argusl     (503) staff       (20)      648 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/timestamp.sql
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.490680 dbt-dremio-1.5.0/dbt/include/dremio/macros/builtins/
+-rw-r--r--   0 argusl     (503) staff       (20)     2369 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/builtins/builtins.sql
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.492465 dbt-dremio-1.5.0/dbt/include/dremio/macros/get_custom_name/
+-rw-r--r--   0 argusl     (503) staff       (20)     1079 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/get_custom_name/get_custom_alias.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1223 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/get_custom_name/get_custom_database.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1185 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/get_custom_name/get_custom_schema.sql
+-rw-r--r--   0 argusl     (503) staff       (20)      791 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/get_custom_name/is_datalake_node.sql
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.493330 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/
+-rw-r--r--   0 argusl     (503) staff       (20)     1604 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/helpers.sql
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.494880 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/incremental/
+-rw-r--r--   0 argusl     (503) staff       (20)     5161 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/incremental/incremental.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1613 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/incremental/strategies.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1502 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/incremental/validate.sql
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.495962 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/reflection/
+-rw-r--r--   0 argusl     (503) staff       (20)     4326 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/reflection/create_reflection.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1448 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/reflection/helpers.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     4388 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/reflection/reflection.sql
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.496557 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/seed/
+-rw-r--r--   0 argusl     (503) staff       (20)     1823 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/seed/helpers.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     2401 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/seed/seed.sql
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.497841 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/table/
+-rw-r--r--   0 argusl     (503) staff       (20)     1956 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/table/alter_pds.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1986 2023-06-22 16:42:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/table/create_table_as.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1999 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/table/table.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     2425 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/twin_strategy.sql
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.500867 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/view/
+-rw-r--r--   0 argusl     (503) staff       (20)     1445 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/view/create_or_replace_view.sql
+-rw-r--r--   0 argusl     (503) staff       (20)      983 2023-06-22 16:42:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/view/create_view_as.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1393 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/view/helpers.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     1997 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/view/view.sql
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.503406 dbt-dremio-1.5.0/dbt/include/dremio/macros/utils/
+-rw-r--r--   0 argusl     (503) staff       (20)      732 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/utils/array_append.sql
+-rw-r--r--   0 argusl     (503) staff       (20)      730 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/utils/array_concat.sql
+-rw-r--r--   0 argusl     (503) staff       (20)      848 2023-04-12 16:35:50.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/utils/array_construct.sql
+-rw-r--r--   0 argusl     (503) staff       (20)      104 2023-02-10 17:10:28.000000 dbt-dremio-1.5.0/dbt/include/dremio/macros/utils/data_types.sql
+-rw-r--r--   0 argusl     (503) staff       (20)     2097 2023-03-13 17:47:36.000000 dbt-dremio-1.5.0/dbt/include/dremio/profile_template.yml
+drwxr-xr-x   0 argusl     (503) staff       (20)        0 2023-06-22 17:13:29.505380 dbt-dremio-1.5.0/dbt_dremio.egg-info/
+-rw-r--r--   0 argusl     (503) staff       (20)      562 2023-06-22 17:13:29.000000 dbt-dremio-1.5.0/dbt_dremio.egg-info/PKG-INFO
+-rw-r--r--   0 argusl     (503) staff       (20)     2942 2023-06-22 17:13:29.000000 dbt-dremio-1.5.0/dbt_dremio.egg-info/SOURCES.txt
+-rw-r--r--   0 argusl     (503) staff       (20)        1 2023-06-22 17:13:29.000000 dbt-dremio-1.5.0/dbt_dremio.egg-info/dependency_links.txt
+-rw-r--r--   0 argusl     (503) staff       (20)       38 2023-06-22 17:13:29.000000 dbt-dremio-1.5.0/dbt_dremio.egg-info/requires.txt
+-rw-r--r--   0 argusl     (503) staff       (20)        4 2023-06-22 17:13:29.000000 dbt-dremio-1.5.0/dbt_dremio.egg-info/top_level.txt
+-rw-r--r--   0 argusl     (503) staff       (20)       87 2022-11-03 22:51:28.000000 dbt-dremio-1.5.0/pyproject.toml
+-rw-r--r--   0 argusl     (503) staff       (20)       74 2023-06-22 17:13:29.506116 dbt-dremio-1.5.0/setup.cfg
+-rw-r--r--   0 argusl     (503) staff       (20)     1513 2023-06-22 16:42:28.000000 dbt-dremio-1.5.0/setup.py
```

### Comparing `dbt-dremio-1.4.5/LICENSE` & `dbt-dremio-1.5.0/LICENSE`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/PKG-INFO` & `dbt-dremio-1.5.0/PKG-INFO`

 * *Files 19% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 Metadata-Version: 2.1
 Name: dbt-dremio
-Version: 1.4.5
+Version: 1.5.0
 Summary: The Dremio adapter plugin for dbt
 Home-page: https://github.com/dremio/dbt-dremio
 Author: Dremio
 License: Apache Software License 2.0 (http://www.apache.org/licenses/LICENSE-2.0)
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Operating System :: Microsoft :: Windows
 Classifier: Operating System :: MacOS :: MacOS X
 Classifier: Operating System :: POSIX :: Linux
-Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 License-File: LICENSE
 
 The Dremio adapter plugin for dbt
```

### Comparing `dbt-dremio-1.4.5/README.md` & `dbt-dremio-1.5.0/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -2,28 +2,28 @@
   <img src="https://resumo.cloud/wp-content/uploads/2021/07/modelo-imagem-rc-16-1.png" alt="dremio logo" width="500"/>
 </p>
 
 **[dbt](https://www.getdbt.com/)** enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications.
 
 dbt is the T in ELT. Organize, cleanse, denormalize, filter, rename, and pre-aggregate the raw data in your warehouse so that it's ready for analysis.
 
-## dbt-dremio version 1.4.5
+## dbt-dremio version 1.5.0
 
 The `dbt-dremio` package contains all of the code enabling dbt to work with [Dremio](https://www.dremio.com/). For more information on using dbt with Dremio, consult [the docs](https://docs.getdbt.com/reference/warehouse-profiles/dremio-profile).
 
 The dbt-dremio package supports both Dremio Cloud and Dremio Software (versions 22.0 and later).
 
-Version 1.4.5 of the dbt-dremio adapter is compatible with dbt-core versions 1.2.0 to 1.4.5.
+Version 1.5.0 of the dbt-dremio adapter is compatible with dbt-core versions 1.2.0 to 1.5.0.
 
 > Prior to version 1.1.0b, dbt-dremio was created and maintained by [Fabrice Etanchaud](https://github.com/fabrice-etanchaud) on [their GitHub repo](https://github.com/fabrice-etanchaud/dbt-dremio). Code for using Dremio REST APIs was originally authored by [Ryan Murray](https://github.com/rymurr). Contributors in this repo are credited for laying the groundwork and maintaining the adapter till version 1.0.6.5. The dbt-dremio adapter is maintained and distributed by Dremio starting with version 1.1.0b.
 
 ## Getting started
 
 -   [Install dbt-dremio](https://docs.getdbt.com/reference/warehouse-setups/dremio-setup)
-    -   Version 1.4.5 of dbt-dremio requires dbt-core >= 1.2.0 and <= 1.4.5. Installing dbt-dremio will automatically upgrade existing dbt-core versions earlier than 1.2.0 to 1.4.5, or install dbt-core v1.4.5 if no version of dbt-core is found.
+    -   Version 1.5.0 of dbt-dremio requires dbt-core >= 1.2.0 and <= 1.5.0. Installing dbt-dremio will automatically upgrade existing dbt-core versions earlier than 1.2.0 to 1.5.0, or install dbt-core v1.5.0 if no version of dbt-core is found.
 -   Read the [introduction](https://docs.getdbt.com/docs/introduction/) and [viewpoint](https://docs.getdbt.com/docs/about/viewpoint/)
 
 ## Join the dbt Community
 
 -   Be part of the conversation in the [dbt Community Slack](http://community.getdbt.com/)
 -   Read more on the [dbt Community Discourse](https://discourse.getdbt.com)
```

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/__init__.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/__init__.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/__version__.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/__version__.py`

 * *Files 2% similar despite different names*

```diff
@@ -5,8 +5,8 @@
 # http://www.apache.org/licenses/LICENSE-2.0
 # Unless required by applicable law or agreed to in writing, software
 # distributed under the License is distributed on an "AS IS" BASIS,
 # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
-version = "1.4.5"
+version = "1.5.0"
```

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/api/__init__.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/api/__init__.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/api/authentication.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/api/authentication.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/api/cursor.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/api/cursor.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/api/handle.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/api/handle.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/api/parameters.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/api/parameters.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/api/rest/endpoints.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/api/rest/endpoints.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/api/rest/error.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/api/rest/error.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/api/rest/url_builder.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/api/rest/url_builder.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/connections.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/connections.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/credentials.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/credentials.py`

 * *Files 10% similar despite different names*

```diff
@@ -50,14 +50,22 @@
     _SPACE_NAME_PLACEHOLDER = "@user"
 
     @property
     def type(self):
         return "dremio"
 
     @property
+    def unique_field(self):
+        """
+        Hashed and included in anonymous telemetry to track adapter adoption.
+        Pick a field that can uniquely identify one team/organization building with this adapter
+        """
+        return self.software_host if self.cloud_host is None else self.cloud_host
+
+    @property
     def aliases(self):
         return self._ALIASES
 
     def _connection_keys(self):
         # return an iterator of keys to pretty-print in 'dbt debug'
         return (
             "cloud_host",
```

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/impl.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/impl.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/adapters/dremio/relation.py` & `dbt-dremio-1.5.0/dbt/adapters/dremio/relation.py`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/dbt_project.yml` & `dbt-dremio-1.5.0/dbt/include/dremio/dbt_project.yml`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/apply_grants.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/apply_grants.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/columns.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/columns.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/data_preparation.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/data_preparation.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/external_query.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/external_query.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/format.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/format.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/metadata.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/metadata.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/relation.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/relation.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/snapshot.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/snapshot.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/sources.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/sources.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/adapters/timestamp.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/adapters/timestamp.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/builtins/builtins.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/builtins/builtins.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/get_custom_name/get_custom_alias.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/get_custom_name/get_custom_alias.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/get_custom_name/get_custom_database.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/get_custom_name/get_custom_database.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/get_custom_name/get_custom_schema.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/get_custom_name/get_custom_schema.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/get_custom_name/is_datalake_node.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/get_custom_name/is_datalake_node.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/helpers.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/helpers.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/incremental/incremental.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/incremental/incremental.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/incremental/strategies.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/incremental/strategies.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/incremental/validate.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/incremental/validate.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/reflection/create_reflection.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/reflection/create_reflection.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/reflection/helpers.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/reflection/helpers.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/reflection/reflection.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/reflection/reflection.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/seed/helpers.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/seed/helpers.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/seed/seed.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/seed/seed.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/table/alter_pds.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/table/alter_pds.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/table/create_table_as.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/table/create_table_as.sql`

 * *Files 10% similar despite different names*

```diff
@@ -22,14 +22,19 @@
  *       [ STORE AS (opt1 => val1, opt2 => val3, ...) ]
  *       [ WITH SINGLE WRITER ]
  *       [ AS select_statement. ]
  */
 #}
 
 {% macro dremio__create_table_as(temporary, relation, sql) -%}
+  {% set contract_config = config.get('contract') %}
+  {% if contract_config.enforced %}
+     {{exceptions.warn("Model contracts are not enforced by dbt-dremio!")}}
+  {% endif %}
+
   {%- set sql_header = config.get('sql_header', none) -%}
 
   {{ sql_header if sql_header is not none }}
 
   create table {{ relation }}
   {{ partition_method() }} {{ config_cols("partition by") }}
   {{ config_cols("distribute by") }}
```

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/table/table.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/table/table.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/twin_strategy.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/twin_strategy.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/view/create_or_replace_view.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/view/create_or_replace_view.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/view/create_view_as.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/utils/array_append.sql`

 * *Files 20% similar despite different names*

```diff
@@ -8,16 +8,10 @@
 
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.*/
 
-{% macro dremio__create_view_as(relation, sql) -%}
-  {%- set sql_header = config.get('sql_header', none) -%}
-
-  {{ sql_header if sql_header is not none }}
-
-  create or replace view {{ relation }} as (
-    {{ sql }}
-  )
-{%- endmacro %}
+{% macro dremio__array_append(array, new_element) -%}
+    {% do exceptions.CompilationError("Array Append is not currently supported by Dremio.") %}
+{%- endmacro %}
```

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/view/helpers.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/view/helpers.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/materializations/view/view.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/materializations/view/view.sql`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/utils/array_append.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/utils/array_concat.sql`

 * *Files 6% similar despite different names*

```diff
@@ -8,10 +8,10 @@
 
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.*/
 
-{% macro dremio__array_append(array, new_element) -%}
-    {% do exceptions.CompilationError("Array Append is not currently supported by Dremio.") %}
+{% macro dremio__array_concat(array_1, array_2) -%}
+    {% do exceptions.CompilationError("Array Concat is not currently supported by Dremio.") %}
 {%- endmacro %}
```

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/macros/utils/array_concat.sql` & `dbt-dremio-1.5.0/dbt/include/dremio/macros/utils/array_construct.sql`

 * *Files 16% similar despite different names*

```diff
@@ -8,10 +8,14 @@
 
 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.*/
 
-{% macro dremio__array_concat(array_1, array_2) -%}
-    {% do exceptions.CompilationError("Array Concat is not currently supported by Dremio.") %}
+{% macro default__array_construct(inputs, data_type) -%}
+    {% if inputs|length > 0 %}
+    array[ {{ inputs|join(' , ') }} ]
+    {% else %}
+    {% do exceptions.CompilationError("Constructing empty arrays is not currently supported by Dremio.") %}
+    {% endif %}
 {%- endmacro %}
```

### Comparing `dbt-dremio-1.4.5/dbt/include/dremio/profile_template.yml` & `dbt-dremio-1.5.0/dbt/include/dremio/profile_template.yml`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/dbt_dremio.egg-info/PKG-INFO` & `dbt-dremio-1.5.0/dbt_dremio.egg-info/PKG-INFO`

 * *Files 19% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 Metadata-Version: 2.1
 Name: dbt-dremio
-Version: 1.4.5
+Version: 1.5.0
 Summary: The Dremio adapter plugin for dbt
 Home-page: https://github.com/dremio/dbt-dremio
 Author: Dremio
 License: Apache Software License 2.0 (http://www.apache.org/licenses/LICENSE-2.0)
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Operating System :: Microsoft :: Windows
 Classifier: Operating System :: MacOS :: MacOS X
 Classifier: Operating System :: POSIX :: Linux
-Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 License-File: LICENSE
 
 The Dremio adapter plugin for dbt
```

### Comparing `dbt-dremio-1.4.5/dbt_dremio.egg-info/SOURCES.txt` & `dbt-dremio-1.5.0/dbt_dremio.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `dbt-dremio-1.4.5/setup.py` & `dbt-dremio-1.5.0/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -9,31 +9,32 @@
 # See the License for the specific language governing permissions and
 # limitations under the License.
 
 #!/usr/bin/env python
 from setuptools import find_namespace_packages, setup
 
 package_name = "dbt-dremio"
-package_version = "1.4.5"
+package_version = "1.5.0"
 description = """The Dremio adapter plugin for dbt"""
 
 setup(
     name=package_name,
     version=package_version,
     description=description,
     long_description=description,
     license="Apache Software License 2.0 (http://www.apache.org/licenses/LICENSE-2.0)",
     author="Dremio",
     url="https://github.com/dremio/dbt-dremio",
     packages=find_namespace_packages(include=["dbt", "dbt.*"]),
     include_package_data=True,
     install_requires=[
-        "dbt-core>=1.2, <=1.4.5",
+        "dbt-core>=1.2, <1.6.0",
+        "requests>=2.31.0",
     ],
     classifiers=[
         "License :: OSI Approved :: Apache Software License",
         "Operating System :: Microsoft :: Windows",
         "Operating System :: MacOS :: MacOS X",
         "Operating System :: POSIX :: Linux",
-        "Programming Language :: Python :: 3.10",
+        "Programming Language :: Python :: 3.11",
     ],
 )
```


# Comparing `tmp/django-better-migrations-0.0.4.tar.gz` & `tmp/django_better_migrations-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/django-better-migrations-0.0.4.tar", last modified: Thu Aug 16 15:34:17 2018, max compression
+gzip compressed data, was "django_better_migrations-1.0.3.tar", max compression
```

## Comparing `django-better-migrations-0.0.4.tar` & `django_better_migrations-1.0.3.tar`

### file list

```diff
@@ -1,17 +1,8 @@
-drwxr-xr-x   0 jbbarth    (501) staff       (20)        0 2018-08-16 15:34:17.000000 django-better-migrations-0.0.4/
--rw-r--r--   0 jbbarth    (501) staff       (20)     2472 2018-08-16 15:34:17.000000 django-better-migrations-0.0.4/PKG-INFO
--rw-r--r--   0 jbbarth    (501) staff       (20)     1088 2017-12-18 08:58:28.000000 django-better-migrations-0.0.4/LICENSE
-drwxr-xr-x   0 jbbarth    (501) staff       (20)        0 2018-08-16 15:34:17.000000 django-better-migrations-0.0.4/django_better_migrations.egg-info/
--rw-r--r--   0 jbbarth    (501) staff       (20)     2472 2018-08-16 15:34:17.000000 django-better-migrations-0.0.4/django_better_migrations.egg-info/PKG-INFO
--rw-r--r--   0 jbbarth    (501) staff       (20)      397 2018-08-16 15:34:17.000000 django-better-migrations-0.0.4/django_better_migrations.egg-info/SOURCES.txt
--rw-r--r--   0 jbbarth    (501) staff       (20)       25 2018-08-16 15:34:17.000000 django-better-migrations-0.0.4/django_better_migrations.egg-info/top_level.txt
--rw-r--r--   0 jbbarth    (501) staff       (20)        1 2018-08-16 15:34:17.000000 django-better-migrations-0.0.4/django_better_migrations.egg-info/dependency_links.txt
--rw-r--r--   0 jbbarth    (501) staff       (20)       27 2017-12-18 08:58:28.000000 django-better-migrations-0.0.4/MANIFEST.in
--rw-r--r--   0 jbbarth    (501) staff       (20)     1420 2018-08-16 15:29:40.000000 django-better-migrations-0.0.4/README.md
--rw-r--r--   0 jbbarth    (501) staff       (20)     1052 2017-12-18 08:58:28.000000 django-better-migrations-0.0.4/setup.py
--rw-r--r--   0 jbbarth    (501) staff       (20)      231 2018-08-16 15:34:17.000000 django-better-migrations-0.0.4/setup.cfg
-drwxr-xr-x   0 jbbarth    (501) staff       (20)        0 2018-08-16 15:34:17.000000 django-better-migrations-0.0.4/django_better_migrations/
--rw-r--r--   0 jbbarth    (501) staff       (20)      789 2018-05-18 19:47:49.000000 django-better-migrations-0.0.4/django_better_migrations/config.py
--rw-r--r--   0 jbbarth    (501) staff       (20)       95 2018-08-16 15:29:48.000000 django-better-migrations-0.0.4/django_better_migrations/__init__.py
--rw-r--r--   0 jbbarth    (501) staff       (20)      465 2018-08-16 15:29:40.000000 django-better-migrations-0.0.4/django_better_migrations/rules.py
--rw-r--r--   0 jbbarth    (501) staff       (20)     2541 2018-05-18 19:47:49.000000 django-better-migrations-0.0.4/django_better_migrations/migration_writer_patch.py
+-rw-r--r--   0        0        0     1096 2023-06-28 13:46:58.898428 django_better_migrations-1.0.3/LICENSE
+-rw-r--r--   0        0        0     1922 2023-06-28 13:46:58.898428 django_better_migrations-1.0.3/README.md
+-rw-r--r--   0        0        0      218 2023-06-28 13:47:20.294505 django_better_migrations-1.0.3/django_better_migrations/__init__.py
+-rw-r--r--   0        0        0      789 2023-06-28 13:46:58.898428 django_better_migrations-1.0.3/django_better_migrations/apps.py
+-rw-r--r--   0        0        0     2702 2023-06-28 13:46:58.898428 django_better_migrations-1.0.3/django_better_migrations/migration_writer_patch.py
+-rw-r--r--   0        0        0      466 2023-06-28 13:46:58.898428 django_better_migrations-1.0.3/django_better_migrations/rules.py
+-rw-r--r--   0        0        0     1184 2023-06-28 13:47:20.290505 django_better_migrations-1.0.3/pyproject.toml
+-rw-r--r--   0        0        0     3067 1970-01-01 00:00:00.000000 django_better_migrations-1.0.3/PKG-INFO
```

### filetype from file(1)

```diff
@@ -1 +1 @@
-POSIX tar archive (GNU)
+POSIX tar archive
```

### Comparing `django-better-migrations-0.0.4/LICENSE` & `django_better_migrations-1.0.3/LICENSE`

 * *Files 6% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 The MIT License (MIT)
 
-Copyright (c) <year> <copyright holders>
+Copyright (c) 2017- Jean-Baptiste Barth - Botify
 
 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:
```

### Comparing `django-better-migrations-0.0.4/README.md` & `django_better_migrations-1.0.3/README.md`

 * *Files 27% similar despite different names*

```diff
@@ -1,15 +1,16 @@
 Django Better Migrations
 ========================
 
-[![Build Status](https://travis-ci.org/botify-labs/django-better-migrations.svg?branch=master)](https://travis-ci.org/botify-labs/django-better-migrations)
+[![Deployed to PyPI](https://img.shields.io/pypi/pyversions/django-better-migrations?logo=pypi&logoColor=white)](https://pypi.org/pypi/django-better-migrations)
+[![GitHub Repository](https://img.shields.io/github/stars/botify-labs/django-better-migrations?logo=github)](https://github.com/botify-labs/django-better-migrations/)
+[![Continuous Integration](https://img.shields.io/github/actions/workflow/status/botify-labs/django-better-migrations/ci.yml?logo=github)](https://github.com/botify-labs/django-better-migrations/actions?workflow=CI)
+[![MIT License](https://img.shields.io/github/license/botify-labs/django-better-migrations?logo=open-source-initiative&logoColor=white)](https://github.com/botify-labs/django-better-migrations/blob/main/LICENSE)
 
 This project aims at providing improvements to Django's default migration system.
-The default migration system is over-engineered, sometimes dangerous, and not
-team work friendly.
 
 
 More informations in the documentation, see "docs/" folder.
 
 
 Example
 -------
```

### Comparing `django-better-migrations-0.0.4/django_better_migrations/config.py` & `django_better_migrations-1.0.3/django_better_migrations/apps.py`

 * *Files identical despite different names*

### Comparing `django-better-migrations-0.0.4/django_better_migrations/migration_writer_patch.py` & `django_better_migrations-1.0.3/django_better_migrations/migration_writer_patch.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,13 +1,13 @@
+import django
 from django.db import DEFAULT_DB_ALIAS, connections
 from django.db.migrations.executor import MigrationExecutor
 from django.db.migrations.writer import MigrationWriter
 
-from .config import get_setting
-
+from .apps import get_setting
 
 # Safety check to ensure we actually can patch MigrationWriter correctly
 if "as_string" not in dir(MigrationWriter):
     raise ValueError(
         "This patch is not compatible with your version of Django: "
         "'django.db.migrations.writer.MigrationWriter' has no method 'as_string()'"
     )
@@ -19,50 +19,61 @@
 
     # check allowed engines in settings
     allowed_engines = get_setting("ALLOW_ENGINES")
     if allowed_engines and connection.vendor not in allowed_engines:
         raise Exception(
             "You are not allowed to generate migrations files "
             "with the DB engine '%s'. Please use an engine among "
-            "the following list: %s" % (
+            "the following list: %s"
+            % (
                 connection.vendor,
                 ", ".join(allowed_engines),
             )
         )
 
     content = self._original_as_string(*args, **kwargs)
-    assert "\nclass Migration" in content, "couldn't find 'class Migration' in migration content"
+    assert (
+        "\nclass Migration" in content
+    ), "couldn't find 'class Migration' in migration content"
 
     # write migration un-processed so the executor can find/read it
     with open(self.path, "w") as f:
         f.write(content)
 
     # get SQL code
     executor = MigrationExecutor(connection)
     app_label = self.migration.app_label
-    mirgation_name = self.migration.name
-    plan = [(executor.loader.graph.nodes[(app_label, mirgation_name)], False)]
-    sql_statements = executor.collect_sql(plan)
+    migration_name = self.migration.name
+    plan = [(executor.loader.graph.nodes[(app_label, migration_name)], False)]
+
+    if django.VERSION < (3, 1):
+        collector = executor
+    else:
+        collector = executor.loader
+
+    sql_statements = collector.collect_sql(plan)
 
     # amend content that will be written to disk
     comment = "\n".join("# %s" % stmt for stmt in sql_statements)
-    comment = "# Generated SQL code (%s):\n#\n%s\n#\n" % (connection.vendor, comment)
+    comment = "# Generated SQL code ({}):\n#\n{}\n#\n".format(
+        connection.vendor, comment
+    )
 
     # check rules
     rules = get_setting("RULES")
     check_results = []
     for rule in rules:
         status = rule().process(self.migration, sql_statements)
         out = (status, rule.title)
         check_results.append(out)
 
     if check_results:
         comment += "\n# Check results:\n"
     for res in check_results:
-        comment += "# CHECK %s: %s\n" % (res[0], res[1])
+        comment += f"# CHECK {res[0]}: {res[1]}\n"
 
     content = content.replace(
         "\nclass Migration",
         "\n%sclass Migration" % comment,
     )
 
     return content
```


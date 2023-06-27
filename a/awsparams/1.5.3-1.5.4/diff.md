# Comparing `tmp/awsparams-1.5.3.tar.gz` & `tmp/awsparams-1.5.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "awsparams-1.5.3.tar", max compression
+gzip compressed data, was "awsparams-1.5.4.tar", max compression
```

## Comparing `awsparams-1.5.3.tar` & `awsparams-1.5.4.tar`

### file list

```diff
@@ -1,6 +1,6 @@
--rw-r--r--   0        0        0    11357 2023-06-14 14:22:05.906460 awsparams-1.5.3/LICENSE
--rw-r--r--   0        0        0     4765 2023-06-14 14:22:05.906460 awsparams-1.5.3/README.md
--rw-r--r--   0        0        0    10098 2023-06-14 14:22:05.906460 awsparams-1.5.3/awsparams/__init__.py
--rwxr-xr-x   0        0        0    11420 2023-06-14 14:22:05.906460 awsparams-1.5.3/awsparams/cli.py
--rw-r--r--   0        0        0      680 2023-06-14 14:22:05.906460 awsparams-1.5.3/pyproject.toml
--rw-r--r--   0        0        0     5658 1970-01-01 00:00:00.000000 awsparams-1.5.3/PKG-INFO
+-rw-r--r--   0        0        0    11357 2023-06-27 23:32:56.705816 awsparams-1.5.4/LICENSE
+-rw-r--r--   0        0        0     5438 2023-06-27 23:32:56.705816 awsparams-1.5.4/README.md
+-rw-r--r--   0        0        0    10098 2023-06-27 23:32:56.705816 awsparams-1.5.4/awsparams/__init__.py
+-rwxr-xr-x   0        0        0    11593 2023-06-27 23:32:56.705816 awsparams-1.5.4/awsparams/cli.py
+-rw-r--r--   0        0        0      680 2023-06-27 23:32:56.709816 awsparams-1.5.4/pyproject.toml
+-rw-r--r--   0        0        0     6331 1970-01-01 00:00:00.000000 awsparams-1.5.4/PKG-INFO
```

### Comparing `awsparams-1.5.3/LICENSE` & `awsparams-1.5.4/LICENSE`

 * *Files identical despite different names*

### Comparing `awsparams-1.5.3/README.md` & `awsparams-1.5.4/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -126,7 +126,20 @@
 copy set of parameters with prefix appname.dev. to appname.prd.: `awsparams cp appname.dev. appname.prd. --prefix`
 
 copy set of parameters starting with prefix repometa-generator.prd
 overwrite existing parameters accross different accounts: `awsparams cp repometa-generator.prd --src_profile=dev --dst_profile=trn
 --prefix=True`
 
 copy single parameters accross different accounts: `awsparams cp appname.dev.username appname.trb.us`
+
+# Contributing
+To contribute:
+1. Make a PR to master
+   - In your changes, make sure to manually bump the package version in the `pyproject.toml` file to whatever version
+   you think is appropriate.
+2. Once the PR is approved, merge it in to master.
+3. Create a new release and a new tag where the version in the tag is equal to the new version you set in the
+   `pyproject.toml` file.
+4. Once you publish the release, check the GitHub actions and notice that it is automatically deploying the package.
+5. Confirm that the deploy succeeds.
+    - If anything goes wrong, fix it and then re-run the workflow. 
+    - You may have to delete your release/tag and recreate it.
```

### Comparing `awsparams-1.5.3/awsparams/__init__.py` & `awsparams-1.5.4/awsparams/__init__.py`

 * *Files identical despite different names*

### Comparing `awsparams-1.5.3/awsparams/cli.py` & `awsparams-1.5.4/awsparams/cli.py`

 * *Files 2% similar despite different names*

```diff
@@ -97,30 +97,34 @@
                     name = parm.Name
                 """
                 run_config - print out separated by '=' and ended with ';'
                 env_vars - print out separated by '=', values wrapped in quotes
                 tfvars - print out separated by ' = ', values wrapped in quotes
                 """
                 if dot_env:
-                    click.echo(f"{name}=\"{escape_quotes(parm.Value) if esc_quotes else parm.Value}\"")
+                    click.echo(f"{name}=\"{escape_char(parm.Value) if esc_quotes else parm.Value}\"")
                 elif tfvars:
-                    click.echo(f"{name} = \"{escape_quotes(parm.Value) if esc_quotes else parm.Value}\"")
+                    click.echo(f"{name} = \"{escape_char(parm.Value) if esc_quotes else parm.Value}\"")
                 elif jetbrains_run_config:
-                    click.echo(f"{name}={parm.Value};")
+                    click.echo(f"{name}={escape_char(parm.Value, ';')};")
             else:
                 click.echo(f"{parm.Name}: {parm.Value}")
         else:
             click.echo(parm.Name)
 
 
-def escape_quotes(string):
+def escape_char(string, char='"'):
+    """
+    Escapes characters in the string by adding backslashes before all occurrences of it
+    By default, escapes quotation marks
+    """
     newstr = ''
     for c in string:
-        if c == '"':
-            newstr += '\\"'
+        if c == char:
+            newstr += '\\' + char
         else:
             newstr += c
     return newstr
 
 
 @main.command("cp")
 @click.argument("src")
```

### Comparing `awsparams-1.5.3/pyproject.toml` & `awsparams-1.5.4/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "awsparams"
-version = "1.5.3"
+version = "1.5.4"
 description = "A simple CLI and Library for adding/removing/renaming/copying AWS Param Store Parameters"
 authors = ["Nate Peterson <ndpete@gmail.com>"]
 license = "Apache-2.0"
 readme = "README.md"
 homepage = "https://github.com/byu-oit/awsparams"
 repository = "https://github.com/byu-oit/awsparams"
```

### Comparing `awsparams-1.5.3/PKG-INFO` & `awsparams-1.5.4/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: awsparams
-Version: 1.5.3
+Version: 1.5.4
 Summary: A simple CLI and Library for adding/removing/renaming/copying AWS Param Store Parameters
 Home-page: https://github.com/byu-oit/awsparams
 License: Apache-2.0
 Author: Nate Peterson
 Author-email: ndpete@gmail.com
 Requires-Python: >=3.6,<4
 Classifier: License :: OSI Approved :: Apache Software License
@@ -149,7 +149,20 @@
 
 copy set of parameters starting with prefix repometa-generator.prd
 overwrite existing parameters accross different accounts: `awsparams cp repometa-generator.prd --src_profile=dev --dst_profile=trn
 --prefix=True`
 
 copy single parameters accross different accounts: `awsparams cp appname.dev.username appname.trb.us`
 
+# Contributing
+To contribute:
+1. Make a PR to master
+   - In your changes, make sure to manually bump the package version in the `pyproject.toml` file to whatever version
+   you think is appropriate.
+2. Once the PR is approved, merge it in to master.
+3. Create a new release and a new tag where the version in the tag is equal to the new version you set in the
+   `pyproject.toml` file.
+4. Once you publish the release, check the GitHub actions and notice that it is automatically deploying the package.
+5. Confirm that the deploy succeeds.
+    - If anything goes wrong, fix it and then re-run the workflow. 
+    - You may have to delete your release/tag and recreate it.
+
```


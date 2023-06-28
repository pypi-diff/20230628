# Comparing `tmp/blacksheep_cli-0.0.1.tar.gz` & `tmp/blacksheep_cli-0.0.2.tar.gz`

## Comparing `blacksheep_cli-0.0.1.tar` & `blacksheep_cli-0.0.2.tar`

### file list

```diff
@@ -1,21 +1,21 @@
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/cli/__init__.py
--rw-r--r--   0        0        0      296 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/cli/main.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/cli/py.typed
--rw-r--r--   0        0        0      442 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/common/__init__.py
--rw-r--r--   0        0        0     5025 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/common/cookiemod.py
--rw-r--r--   0        0        0      955 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/common/prompts.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/create/__init__.py
--rw-r--r--   0        0        0     2020 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/create/cli.py
--rw-r--r--   0        0        0      685 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/create/domain.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/create/py.typed
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/templates/__init__.py
--rw-r--r--   0        0        0     3529 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/templates/cli.py
--rw-r--r--   0        0        0     2694 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/templates/domain.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/templates/py.typed
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/templates/data/__init__.py
--rw-r--r--   0        0        0     3947 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/blacksheepcli/templates/data/default.py
--rw-r--r--   0        0        0     3095 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/.gitignore
--rw-r--r--   0        0        0     1065 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/LICENSE
--rw-r--r--   0        0        0      752 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/README.md
--rw-r--r--   0        0        0     1373 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/pyproject.toml
--rw-r--r--   0        0        0     1876 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.1/PKG-INFO
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/cli/__init__.py
+-rw-r--r--   0        0        0      296 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/cli/main.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/cli/py.typed
+-rw-r--r--   0        0        0      442 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/common/__init__.py
+-rw-r--r--   0        0        0     5032 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/common/cookiemod.py
+-rw-r--r--   0        0        0      955 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/common/prompts.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/create/__init__.py
+-rw-r--r--   0        0        0     2020 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/create/cli.py
+-rw-r--r--   0        0        0      685 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/create/domain.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/create/py.typed
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/templates/__init__.py
+-rw-r--r--   0        0        0     3529 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/templates/cli.py
+-rw-r--r--   0        0        0     2694 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/templates/domain.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/templates/py.typed
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/templates/data/__init__.py
+-rw-r--r--   0        0        0     3947 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/blacksheepcli/templates/data/default.py
+-rw-r--r--   0        0        0     3095 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/.gitignore
+-rw-r--r--   0        0        0     1065 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/LICENSE
+-rw-r--r--   0        0        0      752 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/README.md
+-rw-r--r--   0        0        0     1373 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/pyproject.toml
+-rw-r--r--   0        0        0     1876 2020-02-02 00:00:00.000000 blacksheep_cli-0.0.2/PKG-INFO
```

### Comparing `blacksheep_cli-0.0.1/blacksheepcli/common/cookiemod.py` & `blacksheep_cli-0.0.2/blacksheepcli/common/cookiemod.py`

 * *Files 1% similar despite different names*

```diff
@@ -91,15 +91,15 @@
                 context = load(path, template_name)
     else:
         context_file = os.path.join(repo_dir, "cookiecutter.json")
         logger.debug("context_file is %s", context_file)
 
         questions = get_questions(extra_context, repo_dir)
         if questions:
-            from questionary import prompt as questionary_prompt
+            from questionary import unsafe_prompt as questionary_prompt
 
             answers = questionary_prompt(questions)
             extra_context.update(answers)
 
         context = generate_context(
             context_file=context_file,
             default_context=config_dict["default_context"],
```

### Comparing `blacksheep_cli-0.0.1/blacksheepcli/common/prompts.py` & `blacksheep_cli-0.0.2/blacksheepcli/common/prompts.py`

 * *Files identical despite different names*

### Comparing `blacksheep_cli-0.0.1/blacksheepcli/create/cli.py` & `blacksheep_cli-0.0.2/blacksheepcli/create/cli.py`

 * *Files identical despite different names*

### Comparing `blacksheep_cli-0.0.1/blacksheepcli/create/domain.py` & `blacksheep_cli-0.0.2/blacksheepcli/create/domain.py`

 * *Files identical despite different names*

### Comparing `blacksheep_cli-0.0.1/blacksheepcli/templates/cli.py` & `blacksheep_cli-0.0.2/blacksheepcli/templates/cli.py`

 * *Files identical despite different names*

### Comparing `blacksheep_cli-0.0.1/blacksheepcli/templates/domain.py` & `blacksheep_cli-0.0.2/blacksheepcli/templates/domain.py`

 * *Files identical despite different names*

### Comparing `blacksheep_cli-0.0.1/blacksheepcli/templates/data/default.py` & `blacksheep_cli-0.0.2/blacksheepcli/templates/data/default.py`

 * *Files identical despite different names*

### Comparing `blacksheep_cli-0.0.1/.gitignore` & `blacksheep_cli-0.0.2/.gitignore`

 * *Files identical despite different names*

### Comparing `blacksheep_cli-0.0.1/LICENSE` & `blacksheep_cli-0.0.2/LICENSE`

 * *Files identical despite different names*

### Comparing `blacksheep_cli-0.0.1/README.md` & `blacksheep_cli-0.0.2/README.md`

 * *Files identical despite different names*

### Comparing `blacksheep_cli-0.0.1/pyproject.toml` & `blacksheep_cli-0.0.2/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["hatchling"]
 build-backend = "hatchling.build"
 
 [project]
 name = "blacksheep-cli"
-version = "0.0.1"
+version = "0.0.2"
 authors = [{ name = "Roberto Prevato", email = "roberto.prevato@gmail.com" }]
 description = "CLI experiments."
 readme = "README.md"
 requires-python = ">=3.7"
 classifiers = [
     "Development Status :: 5 - Production/Stable",
     "License :: OSI Approved :: MIT License",
```

### Comparing `blacksheep_cli-0.0.1/PKG-INFO` & `blacksheep_cli-0.0.2/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: blacksheep-cli
-Version: 0.0.1
+Version: 0.0.2
 Summary: CLI experiments.
 Project-URL: Homepage, https://github.com/Neoteroi/BlackSheep-CLI
 Project-URL: Bug Tracker, https://github.com/Neoteroi/BlackSheep-CLI/issues
 Author-email: Roberto Prevato <roberto.prevato@gmail.com>
 License-File: LICENSE
 Keywords: CLI,blacksheep,developer experience,project templates,projects scaffolding
 Classifier: Development Status :: 5 - Production/Stable
```


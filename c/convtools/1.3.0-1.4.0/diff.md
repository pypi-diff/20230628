# Comparing `tmp/convtools-1.3.0.tar.gz` & `tmp/convtools-1.4.0.tar.gz`

## Comparing `convtools-1.3.0.tar` & `convtools-1.4.0.tar`

### file list

```diff
@@ -1,23 +1,23 @@
--rw-r--r--   0        0        0      213 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/__init__.py
--rw-r--r--   0        0        0    51224 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_aggregations.py
--rw-r--r--   0        0        0   108078 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_base.py
--rw-r--r--   0        0        0     7609 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_chunks.py
--rw-r--r--   0        0        0     5696 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_columns.py
--rw-r--r--   0        0        0     5538 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_conversion.py
--rw-r--r--   0        0        0     3207 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_cumulative.py
--rw-r--r--   0        0        0     1328 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_debug.py
--rw-r--r--   0        0        0    20223 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_dt.py
--rw-r--r--   0        0        0     1825 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_expect.py
--rw-r--r--   0        0        0     3610 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_heuristics.py
--rw-r--r--   0        0        0    17783 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_joins.py
--rw-r--r--   0        0        0     5693 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_mutations.py
--rw-r--r--   0        0        0     2330 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_unique.py
--rw-r--r--   0        0        0     8584 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/_utils.py
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/contrib/__init__.py
--rw-r--r--   0        0        0     2574 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/contrib/fs.py
--rw-r--r--   0        0        0    34670 2020-02-02 00:00:00.000000 convtools-1.3.0/convtools/contrib/tables.py
--rw-r--r--   0        0        0      607 2020-02-02 00:00:00.000000 convtools-1.3.0/.gitignore
--rw-r--r--   0        0        0     1116 2020-02-02 00:00:00.000000 convtools-1.3.0/LICENSE.txt
--rw-r--r--   0        0        0     4067 2020-02-02 00:00:00.000000 convtools-1.3.0/README.md
--rw-r--r--   0        0        0     2473 2020-02-02 00:00:00.000000 convtools-1.3.0/pyproject.toml
--rw-r--r--   0        0        0     7634 2020-02-02 00:00:00.000000 convtools-1.3.0/PKG-INFO
+-rw-r--r--   0        0        0      213 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/__init__.py
+-rw-r--r--   0        0        0    51224 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_aggregations.py
+-rw-r--r--   0        0        0   108078 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_base.py
+-rw-r--r--   0        0        0     7609 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_chunks.py
+-rw-r--r--   0        0        0     5696 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_columns.py
+-rw-r--r--   0        0        0     5538 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_conversion.py
+-rw-r--r--   0        0        0     3207 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_cumulative.py
+-rw-r--r--   0        0        0     1328 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_debug.py
+-rw-r--r--   0        0        0    20223 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_dt.py
+-rw-r--r--   0        0        0     1825 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_expect.py
+-rw-r--r--   0        0        0     3610 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_heuristics.py
+-rw-r--r--   0        0        0    17783 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_joins.py
+-rw-r--r--   0        0        0     5947 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_mutations.py
+-rw-r--r--   0        0        0     2330 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_unique.py
+-rw-r--r--   0        0        0     8584 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/_utils.py
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/contrib/__init__.py
+-rw-r--r--   0        0        0     2574 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/contrib/fs.py
+-rw-r--r--   0        0        0    34670 2020-02-02 00:00:00.000000 convtools-1.4.0/convtools/contrib/tables.py
+-rw-r--r--   0        0        0      607 2020-02-02 00:00:00.000000 convtools-1.4.0/.gitignore
+-rw-r--r--   0        0        0     1116 2020-02-02 00:00:00.000000 convtools-1.4.0/LICENSE.txt
+-rw-r--r--   0        0        0     4162 2020-02-02 00:00:00.000000 convtools-1.4.0/README.md
+-rw-r--r--   0        0        0     2473 2020-02-02 00:00:00.000000 convtools-1.4.0/pyproject.toml
+-rw-r--r--   0        0        0     7729 2020-02-02 00:00:00.000000 convtools-1.4.0/PKG-INFO
```

### Comparing `convtools-1.3.0/convtools/_aggregations.py` & `convtools-1.4.0/convtools/_aggregations.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_base.py` & `convtools-1.4.0/convtools/_base.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_chunks.py` & `convtools-1.4.0/convtools/_chunks.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_columns.py` & `convtools-1.4.0/convtools/_columns.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_conversion.py` & `convtools-1.4.0/convtools/_conversion.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_cumulative.py` & `convtools-1.4.0/convtools/_cumulative.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_debug.py` & `convtools-1.4.0/convtools/_debug.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_dt.py` & `convtools-1.4.0/convtools/_dt.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_expect.py` & `convtools-1.4.0/convtools/_expect.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_heuristics.py` & `convtools-1.4.0/convtools/_heuristics.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_joins.py` & `convtools-1.4.0/convtools/_joins.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_mutations.py` & `convtools-1.4.0/convtools/_mutations.py`

 * *Files 2% similar despite different names*

```diff
@@ -16,44 +16,50 @@
             a value for a mutation
         """
         super().__init__()
         self.name = self.ensure_conversion(name)
         self.value = self.ensure_conversion(value)
 
 
-class BaseIndexMutation(BaseMutation):
-    def __init__(self, index):
-        super().__init__()
-        self.index = self.ensure_conversion(index)
-
-
 class SetItem(BaseNameValueMutation):
     def _gen_code_and_update_ctx(self, code_input, ctx):
         name_code = self.name.gen_code_and_update_ctx(code_input, ctx)
         value_code = self.value.gen_code_and_update_ctx(code_input, ctx)
         return f"{code_input}[{name_code}] = {value_code}"
 
 
 class SetAttr(BaseNameValueMutation):
     def _gen_code_and_update_ctx(self, code_input, ctx):
         name_code = self.name.gen_code_and_update_ctx(code_input, ctx)
         value_code = self.value.gen_code_and_update_ctx(code_input, ctx)
         return f"setattr({code_input}, {name_code}, {value_code})"
 
 
+class BaseIndexMutation(BaseMutation):
+    def __init__(self, index, if_exists=False):
+        super().__init__()
+        self.index = self.ensure_conversion(index)
+        self.if_exists = if_exists
+
+
 class DelItem(BaseIndexMutation):
     def _gen_code_and_update_ctx(self, code_input, ctx):
         index_code = self.index.gen_code_and_update_ctx(code_input, ctx)
+        if self.if_exists:
+            return f"{code_input}.pop({index_code}, None)"
         return f"{code_input}.pop({index_code})"
 
 
 class DelAttr(BaseIndexMutation):
     def _gen_code_and_update_ctx(self, code_input, ctx):
         index_code = self.index.gen_code_and_update_ctx(code_input, ctx)
-        return f"delattr({code_input}, {index_code})"
+        code = f"delattr({code_input}, {index_code})"
+        if self.if_exists:
+            return f"hasattr({code_input}, {index_code}) and {code}"
+        return code
 
 
 class Custom(BaseMutation):
     """Mutation to be used in conjunction with `tap` method.
     Runs the code, defined by the conversion argument and returns the input
     as is."""
```

### Comparing `convtools-1.3.0/convtools/_unique.py` & `convtools-1.4.0/convtools/_unique.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/_utils.py` & `convtools-1.4.0/convtools/_utils.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/contrib/fs.py` & `convtools-1.4.0/convtools/contrib/fs.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/convtools/contrib/tables.py` & `convtools-1.4.0/convtools/contrib/tables.py`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/.gitignore` & `convtools-1.4.0/.gitignore`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/LICENSE.txt` & `convtools-1.4.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `convtools-1.3.0/README.md` & `convtools-1.4.0/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -117,10 +117,14 @@
 * convtools is lightweight (_though optional `black` is highly recommended for
   pretty-printing generated code out of curiosity_)
 * convtools fosters building pipelines on top of iterators, allowing for stream
   processing
 * convtools supports nested aggregations
 * convtools is a set of primitives for code generation, so it's just different.
 
+## Support
+
+* westandskif (Nikita Almakov) - [Link to support](https://boosty.to/westandskif)
+
 ## Reporting a Security Vulnerability
 
 See the [security policy](https://github.com/westandskif/convtools/security/policy).
```

### Comparing `convtools-1.3.0/pyproject.toml` & `convtools-1.4.0/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 
 [tool.hatch.build.targets.sdist]
 include = ["/src"]
 
 
 [project]
 name = "convtools"
-version = "1.3.0"
+version = "1.4.0"
 description = "dynamic, declarative data transformations with automatic code generation"
 
 readme = "README.md"
 requires-python = ">=3.6"
 license = {file = "LICENSE.txt"}
 keywords = ["etl", "converters", "codegen", "convtools"]
 authors = [
```

### Comparing `convtools-1.3.0/PKG-INFO` & `convtools-1.4.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: convtools
-Version: 1.3.0
+Version: 1.4.0
 Summary: dynamic, declarative data transformations with automatic code generation
 Project-URL: homepage, https://github.com/westandskif/convtools
 Project-URL: documentation, https://convtools.readthedocs.io/en/latest/
 Project-URL: repository, https://github.com/westandskif/convtools
 Project-URL: changelog, https://github.com/westandskif/convtools/blob/master/docs/CHANGELOG.md
 Author-email: Nikita Almakov <nikita.almakov@gmail.com>
 Maintainer-email: Nikita Almakov <nikita.almakov@gmail.com>
@@ -191,10 +191,14 @@
 * convtools is lightweight (_though optional `black` is highly recommended for
   pretty-printing generated code out of curiosity_)
 * convtools fosters building pipelines on top of iterators, allowing for stream
   processing
 * convtools supports nested aggregations
 * convtools is a set of primitives for code generation, so it's just different.
 
+## Support
+
+* westandskif (Nikita Almakov) - [Link to support](https://boosty.to/westandskif)
+
 ## Reporting a Security Vulnerability
 
 See the [security policy](https://github.com/westandskif/convtools/security/policy).
```


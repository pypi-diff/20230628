# Comparing `tmp/mizdb-tomselect-0.3.1.tar.gz` & `tmp/mizdb-tomselect-0.3.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mizdb-tomselect-0.3.1.tar", last modified: Wed Jun 21 08:29:35 2023, max compression
+gzip compressed data, was "mizdb-tomselect-0.3.2.tar", last modified: Wed Jun 28 08:27:39 2023, max compression
```

## Comparing `mizdb-tomselect-0.3.1.tar` & `mizdb-tomselect-0.3.2.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.469478 mizdb-tomselect-0.3.1/
--rw-r--r--   0 philip    (1000) philip    (1000)     1064 2023-05-18 12:38:24.000000 mizdb-tomselect-0.3.1/LICENSE
--rw-r--r--   0 philip    (1000) philip    (1000)    10466 2023-06-21 08:29:35.468477 mizdb-tomselect-0.3.1/PKG-INFO
--rw-r--r--   0 philip    (1000) philip    (1000)    10128 2023-06-20 11:54:49.000000 mizdb-tomselect-0.3.1/README.md
--rw-r--r--   0 philip    (1000) philip    (1000)     1530 2023-06-20 11:43:52.000000 mizdb-tomselect-0.3.1/pyproject.toml
--rw-r--r--   0 philip    (1000) philip    (1000)       38 2023-06-21 08:29:35.469478 mizdb-tomselect-0.3.1/setup.cfg
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.406476 mizdb-tomselect-0.3.1/src/
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.408476 mizdb-tomselect-0.3.1/src/mizdb_tomselect/
--rw-r--r--   0 philip    (1000) philip    (1000)      123 2023-05-18 12:38:24.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect/__init__.py
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.407476 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.407476 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/mizdb_tomselect/
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.463477 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/mizdb_tomselect/css/
--rw-r--r--   0 philip    (1000) philip    (1000)      430 2023-06-15 10:00:33.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/mizdb_tomselect/css/mizselect.css
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.463477 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/mizdb_tomselect/js/
--rw-r--r--   0 philip    (1000) philip    (1000)   145680 2023-06-21 08:29:32.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/mizdb_tomselect/js/mizselect.js
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.407476 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/vendor/
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.407476 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/vendor/tom-select/
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.465477 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/vendor/tom-select/css/
--rw-r--r--   0 philip    (1000) philip    (1000)    17697 2023-05-26 08:49:37.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/vendor/tom-select/css/tom-select.bootstrap5.css
--rw-r--r--   0 philip    (1000) philip    (1000)    23112 2023-05-26 08:49:37.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/vendor/tom-select/css/tom-select.bootstrap5.css.map
--rw-r--r--   0 philip    (1000) philip    (1000)     3827 2023-06-20 09:53:41.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect/views.py
--rw-r--r--   0 philip    (1000) philip    (1000)     5743 2023-06-20 11:43:52.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect/widgets.py
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.463477 mizdb-tomselect-0.3.1/src/mizdb_tomselect.egg-info/
--rw-r--r--   0 philip    (1000) philip    (1000)    10466 2023-06-21 08:29:35.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect.egg-info/PKG-INFO
--rw-r--r--   0 philip    (1000) philip    (1000)      672 2023-06-21 08:29:35.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect.egg-info/SOURCES.txt
--rw-r--r--   0 philip    (1000) philip    (1000)        1 2023-06-21 08:29:35.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect.egg-info/dependency_links.txt
--rw-r--r--   0 philip    (1000) philip    (1000)        7 2023-06-21 08:29:35.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect.egg-info/requires.txt
--rw-r--r--   0 philip    (1000) philip    (1000)       16 2023-06-21 08:29:35.000000 mizdb-tomselect-0.3.1/src/mizdb_tomselect.egg-info/top_level.txt
-drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-21 08:29:35.468477 mizdb-tomselect-0.3.1/tests/
--rw-r--r--   0 philip    (1000) philip    (1000)    13937 2023-06-20 06:55:07.000000 mizdb-tomselect-0.3.1/tests/test_e2e.py
--rw-r--r--   0 philip    (1000) philip    (1000)     6615 2023-06-20 09:53:41.000000 mizdb-tomselect-0.3.1/tests/test_views.py
--rw-r--r--   0 philip    (1000) philip    (1000)     2718 2023-06-15 09:59:55.000000 mizdb-tomselect-0.3.1/tests/test_widgets.py
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.472917 mizdb-tomselect-0.3.2/
+-rw-r--r--   0 philip    (1000) philip    (1000)     1064 2023-05-18 12:38:24.000000 mizdb-tomselect-0.3.2/LICENSE
+-rw-r--r--   0 philip    (1000) philip    (1000)    10529 2023-06-28 08:27:39.472917 mizdb-tomselect-0.3.2/PKG-INFO
+-rw-r--r--   0 philip    (1000) philip    (1000)    10128 2023-06-20 11:54:49.000000 mizdb-tomselect-0.3.2/README.md
+-rw-r--r--   0 philip    (1000) philip    (1000)     1600 2023-06-28 08:27:16.000000 mizdb-tomselect-0.3.2/pyproject.toml
+-rw-r--r--   0 philip    (1000) philip    (1000)       38 2023-06-28 08:27:39.472917 mizdb-tomselect-0.3.2/setup.cfg
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.469916 mizdb-tomselect-0.3.2/src/
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.470917 mizdb-tomselect-0.3.2/src/mizdb_tomselect/
+-rw-r--r--   0 philip    (1000) philip    (1000)      123 2023-05-18 12:38:24.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect/__init__.py
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.469916 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.469916 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/mizdb_tomselect/
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.471917 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/mizdb_tomselect/css/
+-rw-r--r--   0 philip    (1000) philip    (1000)      430 2023-06-15 10:00:33.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/mizdb_tomselect/css/mizselect.css
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.471917 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/mizdb_tomselect/js/
+-rw-r--r--   0 philip    (1000) philip    (1000)   145941 2023-06-28 08:27:36.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/mizdb_tomselect/js/mizselect.js
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.469916 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/vendor/
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.469916 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/vendor/tom-select/
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.471917 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/vendor/tom-select/css/
+-rw-r--r--   0 philip    (1000) philip    (1000)    17697 2023-05-26 08:49:37.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/vendor/tom-select/css/tom-select.bootstrap5.css
+-rw-r--r--   0 philip    (1000) philip    (1000)    23112 2023-05-26 08:49:37.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/vendor/tom-select/css/tom-select.bootstrap5.css.map
+-rw-r--r--   0 philip    (1000) philip    (1000)     4360 2023-06-27 12:22:49.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect/views.py
+-rw-r--r--   0 philip    (1000) philip    (1000)     5743 2023-06-20 11:43:52.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect/widgets.py
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.471917 mizdb-tomselect-0.3.2/src/mizdb_tomselect.egg-info/
+-rw-r--r--   0 philip    (1000) philip    (1000)    10529 2023-06-28 08:27:39.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect.egg-info/PKG-INFO
+-rw-r--r--   0 philip    (1000) philip    (1000)      672 2023-06-28 08:27:39.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect.egg-info/SOURCES.txt
+-rw-r--r--   0 philip    (1000) philip    (1000)        1 2023-06-28 08:27:39.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect.egg-info/dependency_links.txt
+-rw-r--r--   0 philip    (1000) philip    (1000)        7 2023-06-28 08:27:39.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect.egg-info/requires.txt
+-rw-r--r--   0 philip    (1000) philip    (1000)       16 2023-06-28 08:27:39.000000 mizdb-tomselect-0.3.2/src/mizdb_tomselect.egg-info/top_level.txt
+drwxr-xr-x   0 philip    (1000) philip    (1000)        0 2023-06-28 08:27:39.472917 mizdb-tomselect-0.3.2/tests/
+-rw-r--r--   0 philip    (1000) philip    (1000)    13937 2023-06-20 06:55:07.000000 mizdb-tomselect-0.3.2/tests/test_e2e.py
+-rw-r--r--   0 philip    (1000) philip    (1000)    16071 2023-06-27 12:22:49.000000 mizdb-tomselect-0.3.2/tests/test_views.py
+-rw-r--r--   0 philip    (1000) philip    (1000)     2718 2023-06-15 09:59:55.000000 mizdb-tomselect-0.3.2/tests/test_widgets.py
```

### Comparing `mizdb-tomselect-0.3.1/LICENSE` & `mizdb-tomselect-0.3.2/LICENSE`

 * *Files identical despite different names*

### Comparing `mizdb-tomselect-0.3.1/PKG-INFO` & `mizdb-tomselect-0.3.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,13 @@
 Metadata-Version: 2.1
 Name: mizdb-tomselect
-Version: 0.3.1
+Version: 0.3.2
 Summary: Django autocomplete widgets and views using TomSelect
 Author-email: Philip Becker <yummytea1@gmail.com>
+Project-URL: Source, https://github.com/Actionb/mizdb-tomselet
 Classifier: Framework :: Django
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # TomSelect for Django (MIZDB)
```

### Comparing `mizdb-tomselect-0.3.1/README.md` & `mizdb-tomselect-0.3.2/README.md`

 * *Files identical despite different names*

### Comparing `mizdb-tomselect-0.3.1/pyproject.toml` & `mizdb-tomselect-0.3.2/pyproject.toml`

 * *Files 16% similar despite different names*

```diff
@@ -1,28 +1,31 @@
 [build-system]
 requires = ["setuptools"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "mizdb-tomselect"
-version = "0.3.1"
+version = "0.3.2"
 authors = [
   { name="Philip Becker", email="yummytea1@gmail.com" },
 ]
 description = "Django autocomplete widgets and views using TomSelect"
 readme = "README.md"
 requires-python = ">=3.8"
 dependencies = [
     "Django"
 ]
 classifiers = [
     "Framework :: Django",
     "Programming Language :: Python :: 3",
 ]
 
+[project.urls]
+Source = "https://github.com/Actionb/mizdb-tomselet"
+
 [tool.setuptools]
 package-dir = {"" = "src"}
 
 [tool.setuptools.packages.find]
 where = ["src"]
 
 [tool.setuptools.package-data]
@@ -56,8 +59,8 @@
     "D212",  # D212: Multi-line docstring summary should start at the first line
 ]
 
 [tool.ruff.pydocstyle]
 convention = "google"
 
 [tool.ruff.pycodestyle]
-max-doc-length = 88
+max-doc-length = 88
```

### Comparing `mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/mizdb_tomselect/js/mizselect.js` & `mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/mizdb_tomselect/js/mizselect.js`

 * *Files 0% similar despite different names*

#### js-beautify {}

```diff
@@ -4301,26 +4301,31 @@
                 return element;
             }
         }
     }
 
     function getSettings2(elem) {
         function buildUrl(query, page) {
+            let valuesSelect = [elem.dataset.valueField, elem.dataset.labelField];
+            if (elem.extraColumns) {
+                valuesSelect = valuesSelect.concat(elem.extraColumns);
+            }
             const params = new URLSearchParams({
                 q: encodeURIComponent(query),
                 p: page,
                 model: encodeURIComponent(elem.dataset.model),
-                sl: encodeURIComponent(elem.dataset.searchLookup)
+                sl: encodeURIComponent(elem.dataset.searchLookup),
+                vs: encodeURIComponent(JSON.stringify(valuesSelect))
             });
             if (elem.filterByElem) {
-                params.append("f", `${elem.filterByLookup}=${elem.filterByElem.value}`);
+                params.append("f", encodeURIComponent(`${elem.filterByLookup}=${elem.filterByElem.value}`));
             }
             return `${elem.dataset.autocompleteUrl}?${params.toString()}`;
         }
-        elem.extraColumns = elem.hasAttribute("is-tabular") ? JSON.parse(elem.dataset.extraColumns) : "";
+        elem.extraColumns = elem.hasAttribute("is-tabular") ? JSON.parse(elem.dataset.extraColumns) : [];
         elem.labelColClass = elem.extraColumns.length > 0 && elem.extraColumns.length < 4 ? "col-5" : "col";
         if (elem.dataset.filterBy) {
             const filterBy = JSON.parse(elem.dataset.filterBy);
             elem.filterByElem = getElementByPrefixedName(filterBy[0], [getFormPrefix(elem)]);
             elem.filterByLookup = filterBy[1];
         }
         return {
```

### Comparing `mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/vendor/tom-select/css/tom-select.bootstrap5.css` & `mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/vendor/tom-select/css/tom-select.bootstrap5.css`

 * *Files identical despite different names*

### Comparing `mizdb-tomselect-0.3.1/src/mizdb_tomselect/static/vendor/tom-select/css/tom-select.bootstrap5.css.map` & `mizdb-tomselect-0.3.2/src/mizdb_tomselect/static/vendor/tom-select/css/tom-select.bootstrap5.css.map`

 * *Files identical despite different names*

### Comparing `mizdb-tomselect-0.3.1/src/mizdb_tomselect/views.py` & `mizdb-tomselect-0.3.2/src/mizdb_tomselect/views.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,14 +1,19 @@
+import json
+from urllib.parse import unquote
+
 from django import http, views
 from django.apps import apps
 from django.contrib.auth import get_permission_codename
 
 SEARCH_VAR = "q"
 SEARCH_LOOKUP_VAR = "sl"
 FILTERBY_VAR = "f"
+VALUES_VAR = "vs"
+
 PAGE_VAR = "p"
 PAGE_SIZE = 20
 
 
 class AutocompleteView(views.generic.list.BaseListView):
     """Base list view for queries from TomSelect select elements."""
 
@@ -17,62 +22,71 @@
 
     def setup(self, request, *args, **kwargs):
         super().setup(request, *args, **kwargs)
         request_data = getattr(request, request.method)
         self.model = apps.get_model(request_data["model"])
         self.create_field = request_data.get("create-field")
         self.search_lookup = request.GET.get(SEARCH_LOOKUP_VAR)
+        self.values_select = []
+        if VALUES_VAR in request_data:
+            values = unquote(request_data[VALUES_VAR])
+            self.values_select = json.loads(values)
 
-    def apply_filter_by(self, request, queryset):
+    def apply_filter_by(self, queryset):
         """
-        Filter the result queryset with values set by other form fields.
+        Filter the given queryset against values set by other form fields.
 
         If the widget was set up with a `filter_by` parameter, the request will
         include the `FILTERBY_VAR` parameter, indicating that the results must
         be filtered against the lookup and value provided by `FILTERBY_VAR`.
-        If `FILTERBY_VAR` is present, but no value is set, return an empty
+        If `FILTERBY_VAR` is present but no value is set, return an empty
         queryset.
         """
-        if FILTERBY_VAR not in request.GET:
+        if FILTERBY_VAR not in self.request.GET:
             return queryset
         else:
-            lookup, value = request.GET[FILTERBY_VAR].split("=")
+            lookup, value = unquote(self.request.GET[FILTERBY_VAR]).split("=")
             if not value:
                 # A filter was set up for this autocomplete, but no filter value
                 # was provided; return an empty queryset.
                 return queryset.none()
             return queryset.filter(**{lookup: value})
 
-    def search(self, request, queryset, q):
+    def search(self, queryset, q):
         """Filter the result queryset against the search term."""
         return queryset.filter(**{self.search_lookup: q})
 
     def order_queryset(self, queryset):
         """Order the result queryset."""
         ordering = self.model._meta.ordering or ["id"]
         return queryset.order_by(*ordering)
 
-    def get_results(self, request):
-        """
-        Search for objects that match the search parameters and return the
-        results as a values() queryset.
-        """
-        queryset = self.get_queryset()
-        q = request.GET.get(SEARCH_VAR, "")
-        if q or FILTERBY_VAR in request.GET:
-            queryset = self.apply_filter_by(request, queryset)
-            queryset = self.search(request, queryset, q)
-        return self.order_queryset(queryset.values())
+    def get_queryset(self):
+        """Return a queryset of objects that match the search parameters and filters."""
+        queryset = super().get_queryset()
+        q = unquote(self.request.GET.get(SEARCH_VAR, ""))
+        if q or FILTERBY_VAR in self.request.GET:
+            queryset = self.apply_filter_by(queryset)
+            queryset = self.search(queryset, q)
+        return self.order_queryset(queryset)
+
+    def get_page_results(self, page):
+        """Hook for modifying the result queryset for the given page."""
+        return page.object_list
+
+    def get_result_values(self, results):
+        """Return a list of key:value pairs for the given results."""
+        return list(results.values(*self.values_select))
 
     def get(self, request, *args, **kwargs):
-        queryset = self.get_results(request)
+        queryset = self.get_queryset()
         page_size = self.get_paginate_by(queryset)
-        _, page, queryset, is_paginated = self.paginate_queryset(queryset, page_size)
+        paginator, page, object_list, has_other_pages = self.paginate_queryset(queryset, page_size)
         data = {
-            "results": list(page.object_list),
+            "results": self.get_result_values(self.get_page_results(page)),
             "page": page.number,
             "has_more": page.has_next(),
             "show_create_option": self.has_add_permission(request),
         }
         return http.JsonResponse(data)
 
     def has_add_permission(self, request):
```

### Comparing `mizdb-tomselect-0.3.1/src/mizdb_tomselect/widgets.py` & `mizdb-tomselect-0.3.2/src/mizdb_tomselect/widgets.py`

 * *Files identical despite different names*

### Comparing `mizdb-tomselect-0.3.1/src/mizdb_tomselect.egg-info/PKG-INFO` & `mizdb-tomselect-0.3.2/src/mizdb_tomselect.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,13 @@
 Metadata-Version: 2.1
 Name: mizdb-tomselect
-Version: 0.3.1
+Version: 0.3.2
 Summary: Django autocomplete widgets and views using TomSelect
 Author-email: Philip Becker <yummytea1@gmail.com>
+Project-URL: Source, https://github.com/Actionb/mizdb-tomselet
 Classifier: Framework :: Django
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # TomSelect for Django (MIZDB)
```

### Comparing `mizdb-tomselect-0.3.1/src/mizdb_tomselect.egg-info/SOURCES.txt` & `mizdb-tomselect-0.3.2/src/mizdb_tomselect.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `mizdb-tomselect-0.3.1/tests/test_e2e.py` & `mizdb-tomselect-0.3.2/tests/test_e2e.py`

 * *Files identical despite different names*

### Comparing `mizdb-tomselect-0.3.1/tests/test_widgets.py` & `mizdb-tomselect-0.3.2/tests/test_widgets.py`

 * *Files identical despite different names*


# Comparing `tmp/django-dynamic-datatb-1.0.8.tar.gz` & `tmp/django-dynamic-datatb-1.0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "django-dynamic-datatb-1.0.8.tar", last modified: Wed Feb 15 07:14:50 2023, max compression
+gzip compressed data, was "django-dynamic-datatb-1.0.9.tar", last modified: Wed Feb 15 09:38:18 2023, max compression
```

## Comparing `django-dynamic-datatb-1.0.8.tar` & `django-dynamic-datatb-1.0.9.tar`

### file list

```diff
@@ -1,45 +1,45 @@
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.615139 django-dynamic-datatb-1.0.8/
--rw-rw-rw-   0        0        0     1113 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/LICENSE.md
--rw-rw-rw-   0        0        0      110 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/MANIFEST.in
--rw-rw-rw-   0        0        0     4744 2023-02-15 07:14:50.614140 django-dynamic-datatb-1.0.8/PKG-INFO
--rw-rw-rw-   0        0        0     3654 2023-02-15 07:09:07.000000 django-dynamic-datatb-1.0.8/README.md
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.519149 django-dynamic-datatb-1.0.8/django_dyn_dt/
--rw-rw-rw-   0        0        0        0 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/__init__.py
--rw-rw-rw-   0        0        0       66 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/admin.py
--rw-rw-rw-   0        0        0      164 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/apps.py
--rw-rw-rw-   0        0        0     1720 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/helpers.py
--rw-rw-rw-   0        0        0       60 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/models.py
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.538142 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/
--rw-rw-rw-   0        0        0      797 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/404.html
--rw-rw-rw-   0        0        0     5602 2023-02-15 04:39:28.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/index.html
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.480143 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.555139 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/data/
--rw-rw-rw-   0        0        0      274 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/data/index.js
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.556155 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.569171 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/controller/
--rw-rw-rw-   0        0        0    11460 2023-02-15 04:39:28.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/controller/index.js
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.571142 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/events/
--rw-rw-rw-   0        0        0      412 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/events/index.js
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.573154 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/form/
--rw-rw-rw-   0        0        0     1491 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/form/index.js
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.589140 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/images/
--rw-rw-rw-   0        0        0     3809 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/images/csv.svg
--rw-rw-rw-   0        0        0     4479 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/images/excel.svg
--rw-rw-rw-   0        0        0     4508 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/images/pdf.svg
--rw-rw-rw-   0        0        0     3387 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/index.js
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.601140 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/style/
--rw-rw-rw-   0        0        0      395 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/style/myStyle.css
--rw-rw-rw-   0        0        0       63 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/tests.py
--rw-rw-rw-   0        0        0      471 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/urls.py
--rw-rw-rw-   0        0        0     8397 2023-02-15 04:39:28.000000 django-dynamic-datatb-1.0.8/django_dyn_dt/views.py
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.610140 django-dynamic-datatb-1.0.8/django_dynamic_datatb.egg-info/
--rw-rw-rw-   0        0        0     4744 2023-02-15 07:14:50.000000 django-dynamic-datatb-1.0.8/django_dynamic_datatb.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1029 2023-02-15 07:14:50.000000 django-dynamic-datatb-1.0.8/django_dynamic_datatb.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-02-15 07:14:50.000000 django-dynamic-datatb-1.0.8/django_dynamic_datatb.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        2 2023-02-15 04:42:39.000000 django-dynamic-datatb-1.0.8/django_dynamic_datatb.egg-info/not-zip-safe
--rw-rw-rw-   0        0        0       38 2023-02-15 07:14:50.000000 django-dynamic-datatb-1.0.8/django_dynamic_datatb.egg-info/requires.txt
--rw-rw-rw-   0        0        0       14 2023-02-15 07:14:50.000000 django-dynamic-datatb-1.0.8/django_dynamic_datatb.egg-info/top_level.txt
-drwxrwxrwx   0        0        0        0 2023-02-15 07:14:50.612143 django-dynamic-datatb-1.0.8/docs/
--rw-rw-rw-   0        0        0       13 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.8/docs/blank.txt
--rw-rw-rw-   0        0        0       42 2023-02-15 07:14:50.615139 django-dynamic-datatb-1.0.8/setup.cfg
--rw-rw-rw-   0        0        0     1422 2023-02-15 07:13:16.000000 django-dynamic-datatb-1.0.8/setup.py
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:18.011619 django-dynamic-datatb-1.0.9/
+-rw-rw-rw-   0        0        0     1113 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/LICENSE.md
+-rw-rw-rw-   0        0        0      110 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/MANIFEST.in
+-rw-rw-rw-   0        0        0     4719 2023-02-15 09:38:18.010659 django-dynamic-datatb-1.0.9/PKG-INFO
+-rw-rw-rw-   0        0        0     3629 2023-02-15 09:36:10.000000 django-dynamic-datatb-1.0.9/README.md
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.857233 django-dynamic-datatb-1.0.9/django_dyn_dt/
+-rw-rw-rw-   0        0        0        0 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/__init__.py
+-rw-rw-rw-   0        0        0       66 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/admin.py
+-rw-rw-rw-   0        0        0      164 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/apps.py
+-rw-rw-rw-   0        0        0     1720 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/helpers.py
+-rw-rw-rw-   0        0        0       60 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/models.py
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.883232 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/
+-rw-rw-rw-   0        0        0      797 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/404.html
+-rw-rw-rw-   0        0        0     5602 2023-02-15 04:39:28.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/index.html
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.823233 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.908278 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/data/
+-rw-rw-rw-   0        0        0      274 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/data/index.js
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.909234 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.930851 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/controller/
+-rw-rw-rw-   0        0        0    11460 2023-02-15 04:39:28.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/controller/index.js
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.938849 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/events/
+-rw-rw-rw-   0        0        0      412 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/events/index.js
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.959993 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/form/
+-rw-rw-rw-   0        0        0     1491 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/form/index.js
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.985077 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/images/
+-rw-rw-rw-   0        0        0     3809 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/images/csv.svg
+-rw-rw-rw-   0        0        0     4479 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/images/excel.svg
+-rw-rw-rw-   0        0        0     4508 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/images/pdf.svg
+-rw-rw-rw-   0        0        0     3387 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/index.js
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:17.994623 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/style/
+-rw-rw-rw-   0        0        0      395 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/style/myStyle.css
+-rw-rw-rw-   0        0        0       63 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/tests.py
+-rw-rw-rw-   0        0        0      471 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/urls.py
+-rw-rw-rw-   0        0        0     8397 2023-02-15 04:39:28.000000 django-dynamic-datatb-1.0.9/django_dyn_dt/views.py
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:18.007619 django-dynamic-datatb-1.0.9/django_dynamic_datatb.egg-info/
+-rw-rw-rw-   0        0        0     4719 2023-02-15 09:38:17.000000 django-dynamic-datatb-1.0.9/django_dynamic_datatb.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1029 2023-02-15 09:38:17.000000 django-dynamic-datatb-1.0.9/django_dynamic_datatb.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-02-15 09:38:17.000000 django-dynamic-datatb-1.0.9/django_dynamic_datatb.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        2 2023-02-15 04:42:39.000000 django-dynamic-datatb-1.0.9/django_dynamic_datatb.egg-info/not-zip-safe
+-rw-rw-rw-   0        0        0       38 2023-02-15 09:38:17.000000 django-dynamic-datatb-1.0.9/django_dynamic_datatb.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       14 2023-02-15 09:38:17.000000 django-dynamic-datatb-1.0.9/django_dynamic_datatb.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-02-15 09:38:18.008656 django-dynamic-datatb-1.0.9/docs/
+-rw-rw-rw-   0        0        0       13 2023-02-14 08:59:48.000000 django-dynamic-datatb-1.0.9/docs/blank.txt
+-rw-rw-rw-   0        0        0       42 2023-02-15 09:38:18.011619 django-dynamic-datatb-1.0.9/setup.cfg
+-rw-rw-rw-   0        0        0     1422 2023-02-15 09:37:04.000000 django-dynamic-datatb-1.0.9/setup.py
```

### Comparing `django-dynamic-datatb-1.0.8/LICENSE.md` & `django-dynamic-datatb-1.0.9/LICENSE.md`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/PKG-INFO` & `django-dynamic-datatb-1.0.9/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-dynamic-datatb
-Version: 1.0.8
+Version: 1.0.9
 Summary: Django Dynamic Datatables
 Home-page: https://github.com/app-generator/django-dynamic-datatb
 Author: AppSeed.us
 Author-email: support@appseed.us
 License: MIT License
 Platform: UNKNOWN
 Classifier: Intended Audience :: Developers
@@ -26,27 +26,26 @@
 License-File: LICENSE.md
 
 # [Django Dynamic DataTables](https://appseed.us/developer-tools/django-dynamic-datatables/)
 
 `Open-Source` library for **Django** that provides a `powerful data table interface` (paginated information) with minimum effort - actively supported by [AppSeed](https://appseed.us/).
 
 - [Django Dynamic Services](https://github.com/app-generator/django-dynamic-services) - `sample project that uses the library`
-- Free [support](https://appseed.us/support/) via Email and Discord
+- [Django - Build Services without Coding](https://www.youtube.com/watch?v=EtMCK5AmdQI) - `video presentation`
 
 <br /> 
 
 > Features
 
 - Modern Stack: `Django` & `VanillaJS`
 - `DT` layer provided by [Simple-DataTables](https://github.com/fiduswriter/Simple-DataTables)
 - `Server-side` pagination
 - Search, Filters
 - Exports in PDF, CSV formats
-- `MIT License` (commercial use allowed)
-- Active versioning & Free [support](https://appseed.us/support/)  
+- `MIT License` (commercial use allowed) 
 
 <br />
 
 ![Django Dynamic DataTables - Open-Source tool provided by AppSeed.](https://user-images.githubusercontent.com/51070104/194712823-b8bf1a9e-f5d8-47b3-b7e6-a46a29f3acbe.gif)
 
 <br />
```

### Comparing `django-dynamic-datatb-1.0.8/README.md` & `django-dynamic-datatb-1.0.9/README.md`

 * *Files 4% similar despite different names*

```diff
@@ -1,25 +1,24 @@
 # [Django Dynamic DataTables](https://appseed.us/developer-tools/django-dynamic-datatables/)
 
 `Open-Source` library for **Django** that provides a `powerful data table interface` (paginated information) with minimum effort - actively supported by [AppSeed](https://appseed.us/).
 
 - [Django Dynamic Services](https://github.com/app-generator/django-dynamic-services) - `sample project that uses the library`
-- Free [support](https://appseed.us/support/) via Email and Discord
+- [Django - Build Services without Coding](https://www.youtube.com/watch?v=EtMCK5AmdQI) - `video presentation`
 
 <br /> 
 
 > Features
 
 - Modern Stack: `Django` & `VanillaJS`
 - `DT` layer provided by [Simple-DataTables](https://github.com/fiduswriter/Simple-DataTables)
 - `Server-side` pagination
 - Search, Filters
 - Exports in PDF, CSV formats
-- `MIT License` (commercial use allowed)
-- Active versioning & Free [support](https://appseed.us/support/)  
+- `MIT License` (commercial use allowed) 
 
 <br />
 
 ![Django Dynamic DataTables - Open-Source tool provided by AppSeed.](https://user-images.githubusercontent.com/51070104/194712823-b8bf1a9e-f5d8-47b3-b7e6-a46a29f3acbe.gif)
 
 <br />
```

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/helpers.py` & `django-dynamic-datatb-1.0.9/django_dyn_dt/helpers.py`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/templates/404.html` & `django-dynamic-datatb-1.0.9/django_dyn_dt/templates/404.html`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/templates/index.html` & `django-dynamic-datatb-1.0.9/django_dyn_dt/templates/index.html`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/controller/index.js` & `django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/controller/index.js`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/form/index.js` & `django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/form/index.js`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/images/csv.svg` & `django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/images/csv.svg`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/images/excel.svg` & `django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/images/excel.svg`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/images/pdf.svg` & `django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/images/pdf.svg`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/templates/static/src/index.js` & `django-dynamic-datatb-1.0.9/django_dyn_dt/templates/static/src/index.js`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dyn_dt/views.py` & `django-dynamic-datatb-1.0.9/django_dyn_dt/views.py`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/django_dynamic_datatb.egg-info/PKG-INFO` & `django-dynamic-datatb-1.0.9/django_dynamic_datatb.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: django-dynamic-datatb
-Version: 1.0.8
+Version: 1.0.9
 Summary: Django Dynamic Datatables
 Home-page: https://github.com/app-generator/django-dynamic-datatb
 Author: AppSeed.us
 Author-email: support@appseed.us
 License: MIT License
 Platform: UNKNOWN
 Classifier: Intended Audience :: Developers
@@ -26,27 +26,26 @@
 License-File: LICENSE.md
 
 # [Django Dynamic DataTables](https://appseed.us/developer-tools/django-dynamic-datatables/)
 
 `Open-Source` library for **Django** that provides a `powerful data table interface` (paginated information) with minimum effort - actively supported by [AppSeed](https://appseed.us/).
 
 - [Django Dynamic Services](https://github.com/app-generator/django-dynamic-services) - `sample project that uses the library`
-- Free [support](https://appseed.us/support/) via Email and Discord
+- [Django - Build Services without Coding](https://www.youtube.com/watch?v=EtMCK5AmdQI) - `video presentation`
 
 <br /> 
 
 > Features
 
 - Modern Stack: `Django` & `VanillaJS`
 - `DT` layer provided by [Simple-DataTables](https://github.com/fiduswriter/Simple-DataTables)
 - `Server-side` pagination
 - Search, Filters
 - Exports in PDF, CSV formats
-- `MIT License` (commercial use allowed)
-- Active versioning & Free [support](https://appseed.us/support/)  
+- `MIT License` (commercial use allowed) 
 
 <br />
 
 ![Django Dynamic DataTables - Open-Source tool provided by AppSeed.](https://user-images.githubusercontent.com/51070104/194712823-b8bf1a9e-f5d8-47b3-b7e6-a46a29f3acbe.gif)
 
 <br />
```

### Comparing `django-dynamic-datatb-1.0.8/django_dynamic_datatb.egg-info/SOURCES.txt` & `django-dynamic-datatb-1.0.9/django_dynamic_datatb.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `django-dynamic-datatb-1.0.8/setup.py` & `django-dynamic-datatb-1.0.9/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -4,15 +4,15 @@
 with open(os.path.join(os.path.dirname(__file__), 'README.md')) as readme:
     README = readme.read()
 
 os.chdir(os.path.normpath(os.path.join(os.path.abspath(__file__), os.pardir)))
 
 setup(
 name='django-dynamic-datatb',
-version='1.0.8',
+version='1.0.9',
 zip_safe=False,
 packages=find_packages(),
 include_package_data=True,
 description='Django Dynamic Datatables',
 long_description=README,
 long_description_content_type="text/markdown",
 url='https://github.com/app-generator/django-dynamic-datatb',
```


# Comparing `tmp/webtemplate-dbca-1.5.2.tar.gz` & `tmp/webtemplate-dbca-1.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "webtemplate-dbca-1.5.2.tar", last modified: Wed Jun 22 00:54:20 2022, max compression
+gzip compressed data, was "webtemplate-dbca-1.6.0.tar", last modified: Wed Jun 28 02:33:41 2023, max compression
```

## Comparing `webtemplate-dbca-1.5.2.tar` & `webtemplate-dbca-1.6.0.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.967977 webtemplate-dbca-1.5.2/
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      597 2022-06-21 02:04:08.000000 webtemplate-dbca-1.5.2/LICENSE
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      125 2021-09-17 07:27:03.000000 webtemplate-dbca-1.5.2/MANIFEST.in
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     7545 2022-06-22 00:54:20.967977 webtemplate-dbca-1.5.2/PKG-INFO
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     6289 2021-09-17 07:28:52.000000 webtemplate-dbca-1.5.2/README.md
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      102 2022-06-22 00:54:20.971977 webtemplate-dbca-1.5.2/setup.cfg
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1726 2022-06-21 02:20:46.000000 webtemplate-dbca-1.5.2/setup.py
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.963977 webtemplate-dbca-1.5.2/webtemplate_dbca/
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)        0 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/__init__.py
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.963977 webtemplate-dbca-1.5.2/webtemplate_dbca/static/
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.963977 webtemplate-dbca-1.5.2/webtemplate_dbca/static/css/
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1961 2022-04-20 02:21:34.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/static/css/dbca-custom.css
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      284 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/static/css/dbca-internet.css
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1150 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/static/favicon.ico
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.963977 webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)    11587 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/dbca_logo_sml.png
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     5556 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/dpaw_logo_small.png
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4546 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/logo-dpaw.gif
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4952 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/top-bg.gif
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     3282 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/waTextBlack_80-bluebg.gif
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.959977 webtemplate-dbca-1.5.2/webtemplate_dbca/static/js/
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.963977 webtemplate-dbca-1.5.2/webtemplate_dbca/static/js/vendor/
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     8620 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/static/js/vendor/modernizr-3.11.7.min.js
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.959977 webtemplate-dbca-1.5.2/webtemplate_dbca/templates/
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.967977 webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4703 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base.html
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     5699 2022-06-20 03:33:48.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base_b4.html
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4865 2022-06-20 02:21:44.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base_b5.html
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4703 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base_dbca.html
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4851 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base_internet.html
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      310 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/logged_out.html
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1515 2021-09-20 05:56:51.000000 webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/login.html
-drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2022-06-22 00:54:20.963977 webtemplate-dbca-1.5.2/webtemplate_dbca.egg-info/
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     7545 2022-06-22 00:54:20.000000 webtemplate-dbca-1.5.2/webtemplate_dbca.egg-info/PKG-INFO
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1094 2022-06-22 00:54:20.000000 webtemplate-dbca-1.5.2/webtemplate_dbca.egg-info/SOURCES.txt
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)        1 2022-06-22 00:54:20.000000 webtemplate-dbca-1.5.2/webtemplate_dbca.egg-info/dependency_links.txt
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)       15 2022-06-22 00:54:20.000000 webtemplate-dbca-1.5.2/webtemplate_dbca.egg-info/requires.txt
--rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)       17 2022-06-22 00:54:20.000000 webtemplate-dbca-1.5.2/webtemplate_dbca.egg-info/top_level.txt
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.277696 webtemplate-dbca-1.6.0/
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      597 2023-06-28 02:28:56.000000 webtemplate-dbca-1.6.0/LICENSE
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      125 2021-09-17 07:27:03.000000 webtemplate-dbca-1.6.0/MANIFEST.in
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     7527 2023-06-28 02:33:41.277696 webtemplate-dbca-1.6.0/PKG-INFO
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     6270 2023-06-28 02:30:27.000000 webtemplate-dbca-1.6.0/README.md
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      102 2023-06-28 02:33:41.285696 webtemplate-dbca-1.6.0/setup.cfg
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1727 2023-06-28 02:23:02.000000 webtemplate-dbca-1.6.0/setup.py
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.273696 webtemplate-dbca-1.6.0/webtemplate_dbca/
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)        0 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/__init__.py
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.273696 webtemplate-dbca-1.6.0/webtemplate_dbca/static/
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.273696 webtemplate-dbca-1.6.0/webtemplate_dbca/static/css/
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1961 2022-04-20 02:21:34.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/static/css/dbca-custom.css
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      284 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/static/css/dbca-internet.css
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1150 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/static/favicon.ico
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.277696 webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)    11587 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/dbca_logo_sml.png
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     5556 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/dpaw_logo_small.png
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4546 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/logo-dpaw.gif
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4952 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/top-bg.gif
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     3282 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/waTextBlack_80-bluebg.gif
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.269696 webtemplate-dbca-1.6.0/webtemplate_dbca/static/js/
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.277696 webtemplate-dbca-1.6.0/webtemplate_dbca/static/js/vendor/
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     8620 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/static/js/vendor/modernizr-3.11.7.min.js
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.269696 webtemplate-dbca-1.6.0/webtemplate_dbca/templates/
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.277696 webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4703 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base.html
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     5761 2023-03-03 05:31:25.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base_b4.html
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4927 2023-03-03 05:32:04.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base_b5.html
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4703 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base_dbca.html
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     4851 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base_internet.html
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)      310 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/logged_out.html
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1515 2021-09-20 05:56:51.000000 webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/login.html
+drwxr-xr-x   0 ashleyf  (1711209719) domain users (1711200513)        0 2023-06-28 02:33:41.273696 webtemplate-dbca-1.6.0/webtemplate_dbca.egg-info/
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     7527 2023-06-28 02:33:41.000000 webtemplate-dbca-1.6.0/webtemplate_dbca.egg-info/PKG-INFO
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)     1094 2023-06-28 02:33:41.000000 webtemplate-dbca-1.6.0/webtemplate_dbca.egg-info/SOURCES.txt
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)        1 2023-06-28 02:33:41.000000 webtemplate-dbca-1.6.0/webtemplate_dbca.egg-info/dependency_links.txt
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)       15 2023-06-28 02:33:41.000000 webtemplate-dbca-1.6.0/webtemplate_dbca.egg-info/requires.txt
+-rw-r--r--   0 ashleyf  (1711209719) domain users (1711200513)       17 2023-06-28 02:33:41.000000 webtemplate-dbca-1.6.0/webtemplate_dbca.egg-info/top_level.txt
```

### Comparing `webtemplate-dbca-1.5.2/LICENSE` & `webtemplate-dbca-1.6.0/LICENSE`

 * *Files 18% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-Copyright 2022 Department of Biodiversity, Conservation and Attractions
+Copyright 2023 Department of Biodiversity, Conservation and Attractions
 
 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at
 
    http://www.apache.org/licenses/LICENSE-2.0
```

### Comparing `webtemplate-dbca-1.5.2/PKG-INFO` & `webtemplate-dbca-1.6.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,34 +1,34 @@
 Metadata-Version: 2.1
 Name: webtemplate-dbca
-Version: 1.5.2
+Version: 1.6.0
 Summary: Base HTML templates for DBCA Django projects
 Home-page: https://github.com/dbca-wa/webtemplate
 Author: Ashley Felton
 Author-email: asi@dbca.wa.gov.au
 Maintainer: Ashley Felton
 Maintainer-email: asi@dbca.wa.gov.au
 License: Apache License, Version 2.0
 Keywords: django,html,template,bootstrap
 Platform: UNKNOWN
 Classifier: Framework :: Django
-Classifier: Framework :: Django :: 2.2
-Classifier: Framework :: Django :: 3.0
-Classifier: Framework :: Django :: 3.1
 Classifier: Framework :: Django :: 3.2
+Classifier: Framework :: Django :: 4.0
+Classifier: Framework :: Django :: 4.1
+Classifier: Framework :: Django :: 4.2
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: Developers
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
 Classifier: Topic :: Software Development :: Libraries
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # DBCA Django web template
 
@@ -158,16 +158,15 @@
                     <small class="float-right">&copy; Department of Biodiversity, Conservation and Attractions</small>
                 </div>
             </div>
         </div>
     </footer>
     {% endblock page_footer %}
 
-Bootstrap 3 examples
-====================
+# Bootstrap 3 examples
 
 The following examples apply to the `base.html` template.
 
 To populate the main content area with a narrow left sidebar and content
 area that fills the whole screen width and will collapse elegantly on
 narrow or mobile displays::
```

#### html2text {}

```diff
@@ -1,22 +1,22 @@
-Metadata-Version: 2.1 Name: webtemplate-dbca Version: 1.5.2 Summary: Base HTML
+Metadata-Version: 2.1 Name: webtemplate-dbca Version: 1.6.0 Summary: Base HTML
 templates for DBCA Django projects Home-page: https://github.com/dbca-wa/
 webtemplate Author: Ashley Felton Author-email: asi@dbca.wa.gov.au Maintainer:
 Ashley Felton Maintainer-email: asi@dbca.wa.gov.au License: Apache License,
 Version 2.0 Keywords: django,html,template,bootstrap Platform: UNKNOWN
-Classifier: Framework :: Django Classifier: Framework :: Django :: 2.2
-Classifier: Framework :: Django :: 3.0 Classifier: Framework :: Django :: 3.1
-Classifier: Framework :: Django :: 3.2 Classifier: Environment :: Web
+Classifier: Framework :: Django Classifier: Framework :: Django :: 3.2
+Classifier: Framework :: Django :: 4.0 Classifier: Framework :: Django :: 4.1
+Classifier: Framework :: Django :: 4.2 Classifier: Environment :: Web
 Environment Classifier: Intended Audience :: Developers Classifier: Development
 Status :: 5 - Production/Stable Classifier: License :: OSI Approved :: Apache
 Software License Classifier: Programming Language :: Python Classifier:
 Programming Language :: Python :: 3 Classifier: Programming Language :: Python
-:: 3.6 Classifier: Programming Language :: Python :: 3.7 Classifier:
-Programming Language :: Python :: 3.8 Classifier: Programming Language ::
-Python :: 3.9 Classifier: Topic :: Software Development :: Libraries
+:: 3.7 Classifier: Programming Language :: Python :: 3.8 Classifier:
+Programming Language :: Python :: 3.9 Classifier: Programming Language ::
+Python :: 3.10 Classifier: Topic :: Software Development :: Libraries
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Description-Content-Type: text/markdown License-File: LICENSE # DBCA Django web
 template This project consists of a basic Django application containing HTML
 templates that provide a starting point for web applications used by the
 [Department](http://www.dbca.wa.gov.au). The base template consists of a
 mobile-friendly HTML5 template with a fixed top navbar, plus static assets. The
 project also contains functional examples of **login** and **logged out**
@@ -59,19 +59,18 @@
 {% for message in messages %}
 {{ message|safe }}
 {% endfor %}
 {% endif %}
 {% block page_content_inner %}{% endblock %}
 {% endblock %} {% block page_footer %}
 © Department of Biodiversity, Conservation and Attractions
- {% endblock page_footer %} Bootstrap 3 examples ==================== The
-following examples apply to the `base.html` template. To populate the main
-content area with a narrow left sidebar and content area that fills the whole
-screen width and will collapse elegantly on narrow or mobile displays:: {%
-block page_content %}
+ {% endblock page_footer %} # Bootstrap 3 examples The following examples apply
+to the `base.html` template. To populate the main content area with a narrow
+left sidebar and content area that fills the whole screen width and will
+collapse elegantly on narrow or mobile displays:: {% block page_content %}
 {% include "sidebar.html" %}
 {% block page_content_inner %}{% endblock %}
 {% endblock %} To include a right-aligned copyright line in the footer area::
 {% block page_footer %}
 © Department of Biodiversity, Conservation and Attractions
 {% endblock %} To include no navigation links in the top navbar and to prevent
 the automatic "navbar button" from showing on narrow displays, overide the
```

### Comparing `webtemplate-dbca-1.5.2/README.md` & `webtemplate-dbca-1.6.0/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -126,16 +126,15 @@
                     <small class="float-right">&copy; Department of Biodiversity, Conservation and Attractions</small>
                 </div>
             </div>
         </div>
     </footer>
     {% endblock page_footer %}
 
-Bootstrap 3 examples
-====================
+# Bootstrap 3 examples
 
 The following examples apply to the `base.html` template.
 
 To populate the main content area with a narrow left sidebar and content
 area that fills the whole screen width and will collapse elegantly on
 narrow or mobile displays::
```

#### html2text {}

```diff
@@ -42,19 +42,18 @@
 {% for message in messages %}
 {{ message|safe }}
 {% endfor %}
 {% endif %}
 {% block page_content_inner %}{% endblock %}
 {% endblock %} {% block page_footer %}
 © Department of Biodiversity, Conservation and Attractions
- {% endblock page_footer %} Bootstrap 3 examples ==================== The
-following examples apply to the `base.html` template. To populate the main
-content area with a narrow left sidebar and content area that fills the whole
-screen width and will collapse elegantly on narrow or mobile displays:: {%
-block page_content %}
+ {% endblock page_footer %} # Bootstrap 3 examples The following examples apply
+to the `base.html` template. To populate the main content area with a narrow
+left sidebar and content area that fills the whole screen width and will
+collapse elegantly on narrow or mobile displays:: {% block page_content %}
 {% include "sidebar.html" %}
 {% block page_content_inner %}{% endblock %}
 {% endblock %} To include a right-aligned copyright line in the footer area::
 {% block page_footer %}
 © Department of Biodiversity, Conservation and Attractions
 {% endblock %} To include no navigation links in the top navbar and to prevent
 the automatic "navbar button" from showing on narrow displays, overide the
```

### Comparing `webtemplate-dbca-1.5.2/setup.py` & `webtemplate-dbca-1.6.0/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -3,17 +3,17 @@
 from setuptools import setup
 import os
 
 with open(os.path.join(os.path.dirname(__file__), 'README.md')) as readme:
     README = readme.read()
 
 install_requires = [
-    'Django>=2.2,<4',
+    'Django>=3.2,<5',
 ]
-version = ('1.5.2')
+version = ('1.6.0')
 
 setup(
     name='webtemplate-dbca',
     version=version,
     install_requires=install_requires,
     tests_require=install_requires,
     test_suite='runtests.runtests',
@@ -27,25 +27,25 @@
     url='https://github.com/dbca-wa/webtemplate',
     description='Base HTML templates for DBCA Django projects',
     long_description=README,
     long_description_content_type='text/markdown',
     keywords=['django', 'html', 'template', 'bootstrap'],
     classifiers=[
         'Framework :: Django',
-        'Framework :: Django :: 2.2',
-        'Framework :: Django :: 3.0',
-        'Framework :: Django :: 3.1',
         'Framework :: Django :: 3.2',
+        'Framework :: Django :: 4.0',
+        'Framework :: Django :: 4.1',
+        'Framework :: Django :: 4.2',
         'Environment :: Web Environment',
         'Intended Audience :: Developers',
         'Development Status :: 5 - Production/Stable',
         'License :: OSI Approved :: Apache Software License',
         'Programming Language :: Python',
         'Programming Language :: Python :: 3',
-        'Programming Language :: Python :: 3.6',
         'Programming Language :: Python :: 3.7',
         'Programming Language :: Python :: 3.8',
         'Programming Language :: Python :: 3.9',
+        'Programming Language :: Python :: 3.10',
         'Topic :: Software Development :: Libraries',
         'Topic :: Software Development :: Libraries :: Python Modules',
     ],
 )
```

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/static/css/dbca-custom.css` & `webtemplate-dbca-1.6.0/webtemplate_dbca/static/css/dbca-custom.css`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/static/favicon.ico` & `webtemplate-dbca-1.6.0/webtemplate_dbca/static/favicon.ico`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/dbca_logo_sml.png` & `webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/dbca_logo_sml.png`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/dpaw_logo_small.png` & `webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/dpaw_logo_small.png`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/logo-dpaw.gif` & `webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/logo-dpaw.gif`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/top-bg.gif` & `webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/top-bg.gif`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/static/img/waTextBlack_80-bluebg.gif` & `webtemplate-dbca-1.6.0/webtemplate_dbca/static/img/waTextBlack_80-bluebg.gif`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/static/js/vendor/modernizr-3.11.7.min.js` & `webtemplate-dbca-1.6.0/webtemplate_dbca/static/js/vendor/modernizr-3.11.7.min.js`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base.html` & `webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base.html`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base_b4.html` & `webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base_b4.html`

 * *Files 1% similar despite different names*

```diff
@@ -4,14 +4,15 @@
 <html lang="en">
     <head>
         <title>{{ page_title }}</title>
         <meta charset="utf-8">
         <meta http-equiv="X-UA-Compatible" content="IE=edge">
         <meta name="description" content="{{ page_description }}">
         <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
+        <meta name="author" content="Department of Biodiversity, Conservation and Attractions">
         {% block polyfill_js %}
         <script async src="https://cdnjs.cloudflare.com/ajax/libs/modernizr/2.8.3/modernizr.min.js" integrity="sha256-0rguYS0qgS6L4qVzANq4kjxPLtvnp5nn2nB5G1lWRv4=" crossorigin="anonymous"></script>
         {% endblock polyfill_js %}
         <!-- CSS styling blocks -->
         {% block base_style %}
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/4.6.1/css/bootstrap.min.css" integrity="sha512-T584yQ/tdRR5QwOpfvDfVQUidzfgc2339Lc8uBDtcp/wYu80d7jwBgAxbyMh0a9YM9F8N3tdErpFI8iaGx6x5g==" crossorigin="anonymous" referrerpolicy="no-referrer" />
         {% endblock base_style %}
@@ -32,17 +33,15 @@
         {% block top_navbar %}
         <nav class="{% block navbar_class %}navbar fixed-top navbar-expand-md navbar-dark bg-dark{% endblock navbar_class %}">
             {% block navbar_brand %}
             <a class="navbar-brand d-block d-sm-none" href="/">
                 {{ site_acronym }}
             </a>
             <a class="navbar-brand d-none d-sm-block" href="/">
-                {% block navbar_logo %}
-                <img class="d-inline-block" src="{% static 'img/dbca_logo_sml.png' %}" height="50">
-                {% endblock navbar_logo %}
+                {% block navbar_logo %}<img class="d-inline-block" src="{% static 'img/dbca_logo_sml.png' %}" height="50">{% endblock navbar_logo %}
                 {{ site_title }}
             </a>
             {% endblock navbar_brand %}
 
             {% block navbar_button %}
             <button class="{% block navbar_button_class %}navbar-toggler{% endblock %}" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                 <span class="navbar-toggler-icon"></span>
```

#### html2text {}

```diff
@@ -1,19 +1,20 @@
 {% load static %}
 
 
 
+
  {% block polyfill_js %}
  {% endblock polyfill_js %}  {% block base_style %}
  {% endblock base_style %} {% block extra_style %}
  {% endblock extra_style %} {% block favicon %}
  {% endblock favicon %} {% block extra_head %}{% endblock %}
  {% block top_navbar %}  {% block navbar_brand %} {{_site_acronym_}} {%_block
-navbar_logo_%}_[{%_static_'img/dbca_logo_sml.png'_%}]_{%_endblock_navbar_logo
-%}_{{_site_title_}} {% endblock navbar_brand %} {% block navbar_button %}    {%
+navbar_logo_%}[{%_static_'img/dbca_logo_sml.png'_%}]{%_endblock_navbar_logo_%}_
+{{_site_title_}} {% endblock navbar_brand %} {% block navbar_button %}    {%
 endblock navbar_button %} {% block navbar_links %}
     * Link_1(current)
     * Link_2
     * Disabled
     * Menu
       Action_1 Action_2
       Action_3
```

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base_b5.html` & `webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base_b5.html`

 * *Files 2% similar despite different names*

```diff
@@ -4,14 +4,15 @@
 <html lang="en">
     <head>
         <title>{{ page_title }}</title>
         <meta charset="utf-8">
         <meta http-equiv="X-UA-Compatible" content="IE=edge">
         <meta name="description" content="{{ page_description }}">
         <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
+        <meta name="author" content="Department of Biodiversity, Conservation and Attractions">
         {% block polyfill_js %}
         <script src="{% static 'js/vendor/modernizr-3.11.7.min.js' %}"></script>
         {% endblock polyfill_js %}
         <!-- CSS styling blocks -->
         {% block base_style %}
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/bootstrap/5.1.3/css/bootstrap.min.css" integrity="sha512-GQGU0fMMi238uA+a/bdWJfpUGKUkBdgfFdgBm72SUQ6BeyWjoY/ton0tEjH+OSH9iP4Dfh+7HM0I9f5eR0L/4w==" crossorigin="anonymous" referrerpolicy="no-referrer" />
         {% endblock base_style %}
@@ -29,17 +30,15 @@
           <div class="container-fluid">
 
             {% block navbar_brand %}
             <a class="navbar-brand d-block d-sm-none" href="/">
                 {{ site_acronym }}
             </a>
             <a class="navbar-brand d-none d-sm-block" href="/">
-                {% block navbar_logo %}
-                <img class="d-inline-block" src="{% static 'img/dbca_logo_sml.png' %}" height="50">
-                {% endblock navbar_logo %}
+                {% block navbar_logo %}<img class="d-inline-block" src="{% static 'img/dbca_logo_sml.png' %}" height="50">{% endblock navbar_logo %}
                 {{ site_title }}
             </a>
             {% endblock navbar_brand %}
 
             {% block navbar_links %}
             <button class="{% block navbar_button_class %}navbar-toggler{% endblock %}" type="button" data-bs-toggle="collapse" data-bs-target="#navbarScroll" aria-controls="navbarScroll" aria-expanded="false" aria-label="Toggle navigation">
                 <span class="navbar-toggler-icon"></span>
```

#### html2text {}

```diff
@@ -1,19 +1,20 @@
 {% load static %}
 
 
 
+
  {% block polyfill_js %}
  {% endblock polyfill_js %}  {% block base_style %}
  {% endblock base_style %} {% block extra_style %}
  {% endblock extra_style %} {% block favicon %}
  {% endblock favicon %} {% block extra_head %}{% endblock %}
 {% block top_navbar %}
-{% block navbar_brand %} {{_site_acronym_}} {%_block_navbar_logo_%}_[{%_static
-'img/dbca_logo_sml.png'_%}]_{%_endblock_navbar_logo_%}_{{_site_title_}} {%
+{% block navbar_brand %} {{_site_acronym_}} {%_block_navbar_logo_%}[{%_static
+'img/dbca_logo_sml.png'_%}]{%_endblock_navbar_logo_%}_{{_site_title_}} {%
 endblock navbar_brand %} {% block navbar_links %}
     * Home
     * Link
     * Link
           o Action
           o Another_action
           o ===================================================================
```

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base_dbca.html` & `webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base_dbca.html`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/base_internet.html` & `webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/base_internet.html`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca/templates/webtemplate_dbca/login.html` & `webtemplate-dbca-1.6.0/webtemplate_dbca/templates/webtemplate_dbca/login.html`

 * *Files identical despite different names*

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca.egg-info/PKG-INFO` & `webtemplate-dbca-1.6.0/webtemplate_dbca.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,34 +1,34 @@
 Metadata-Version: 2.1
 Name: webtemplate-dbca
-Version: 1.5.2
+Version: 1.6.0
 Summary: Base HTML templates for DBCA Django projects
 Home-page: https://github.com/dbca-wa/webtemplate
 Author: Ashley Felton
 Author-email: asi@dbca.wa.gov.au
 Maintainer: Ashley Felton
 Maintainer-email: asi@dbca.wa.gov.au
 License: Apache License, Version 2.0
 Keywords: django,html,template,bootstrap
 Platform: UNKNOWN
 Classifier: Framework :: Django
-Classifier: Framework :: Django :: 2.2
-Classifier: Framework :: Django :: 3.0
-Classifier: Framework :: Django :: 3.1
 Classifier: Framework :: Django :: 3.2
+Classifier: Framework :: Django :: 4.0
+Classifier: Framework :: Django :: 4.1
+Classifier: Framework :: Django :: 4.2
 Classifier: Environment :: Web Environment
 Classifier: Intended Audience :: Developers
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
 Classifier: Topic :: Software Development :: Libraries
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # DBCA Django web template
 
@@ -158,16 +158,15 @@
                     <small class="float-right">&copy; Department of Biodiversity, Conservation and Attractions</small>
                 </div>
             </div>
         </div>
     </footer>
     {% endblock page_footer %}
 
-Bootstrap 3 examples
-====================
+# Bootstrap 3 examples
 
 The following examples apply to the `base.html` template.
 
 To populate the main content area with a narrow left sidebar and content
 area that fills the whole screen width and will collapse elegantly on
 narrow or mobile displays::
```

#### html2text {}

```diff
@@ -1,22 +1,22 @@
-Metadata-Version: 2.1 Name: webtemplate-dbca Version: 1.5.2 Summary: Base HTML
+Metadata-Version: 2.1 Name: webtemplate-dbca Version: 1.6.0 Summary: Base HTML
 templates for DBCA Django projects Home-page: https://github.com/dbca-wa/
 webtemplate Author: Ashley Felton Author-email: asi@dbca.wa.gov.au Maintainer:
 Ashley Felton Maintainer-email: asi@dbca.wa.gov.au License: Apache License,
 Version 2.0 Keywords: django,html,template,bootstrap Platform: UNKNOWN
-Classifier: Framework :: Django Classifier: Framework :: Django :: 2.2
-Classifier: Framework :: Django :: 3.0 Classifier: Framework :: Django :: 3.1
-Classifier: Framework :: Django :: 3.2 Classifier: Environment :: Web
+Classifier: Framework :: Django Classifier: Framework :: Django :: 3.2
+Classifier: Framework :: Django :: 4.0 Classifier: Framework :: Django :: 4.1
+Classifier: Framework :: Django :: 4.2 Classifier: Environment :: Web
 Environment Classifier: Intended Audience :: Developers Classifier: Development
 Status :: 5 - Production/Stable Classifier: License :: OSI Approved :: Apache
 Software License Classifier: Programming Language :: Python Classifier:
 Programming Language :: Python :: 3 Classifier: Programming Language :: Python
-:: 3.6 Classifier: Programming Language :: Python :: 3.7 Classifier:
-Programming Language :: Python :: 3.8 Classifier: Programming Language ::
-Python :: 3.9 Classifier: Topic :: Software Development :: Libraries
+:: 3.7 Classifier: Programming Language :: Python :: 3.8 Classifier:
+Programming Language :: Python :: 3.9 Classifier: Programming Language ::
+Python :: 3.10 Classifier: Topic :: Software Development :: Libraries
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Description-Content-Type: text/markdown License-File: LICENSE # DBCA Django web
 template This project consists of a basic Django application containing HTML
 templates that provide a starting point for web applications used by the
 [Department](http://www.dbca.wa.gov.au). The base template consists of a
 mobile-friendly HTML5 template with a fixed top navbar, plus static assets. The
 project also contains functional examples of **login** and **logged out**
@@ -59,19 +59,18 @@
 {% for message in messages %}
 {{ message|safe }}
 {% endfor %}
 {% endif %}
 {% block page_content_inner %}{% endblock %}
 {% endblock %} {% block page_footer %}
 © Department of Biodiversity, Conservation and Attractions
- {% endblock page_footer %} Bootstrap 3 examples ==================== The
-following examples apply to the `base.html` template. To populate the main
-content area with a narrow left sidebar and content area that fills the whole
-screen width and will collapse elegantly on narrow or mobile displays:: {%
-block page_content %}
+ {% endblock page_footer %} # Bootstrap 3 examples The following examples apply
+to the `base.html` template. To populate the main content area with a narrow
+left sidebar and content area that fills the whole screen width and will
+collapse elegantly on narrow or mobile displays:: {% block page_content %}
 {% include "sidebar.html" %}
 {% block page_content_inner %}{% endblock %}
 {% endblock %} To include a right-aligned copyright line in the footer area::
 {% block page_footer %}
 © Department of Biodiversity, Conservation and Attractions
 {% endblock %} To include no navigation links in the top navbar and to prevent
 the automatic "navbar button" from showing on narrow displays, overide the
```

### Comparing `webtemplate-dbca-1.5.2/webtemplate_dbca.egg-info/SOURCES.txt` & `webtemplate-dbca-1.6.0/webtemplate_dbca.egg-info/SOURCES.txt`

 * *Files identical despite different names*


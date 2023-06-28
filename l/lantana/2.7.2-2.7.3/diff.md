# Comparing `tmp/lantana-2.7.2.tar.gz` & `tmp/lantana-2.7.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\lantana-2.7.2.tar", last modified: Wed Jun 28 12:57:37 2023, max compression
+gzip compressed data, was "dist\lantana-2.7.3.tar", last modified: Wed Jun 28 13:21:04 2023, max compression
```

## Comparing `lantana-2.7.2.tar` & `lantana-2.7.3.tar`

### file list

```diff
@@ -1,45 +1,47 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 12:57:37.000000 lantana-2.7.2/
-drwxrwxrwx   0        0        0        0 2023-06-28 12:57:36.000000 lantana-2.7.2/lantana/
--rw-rw-rw-   0        0        0      547 2022-10-28 12:09:36.000000 lantana-2.7.2/lantana/404.html
--rw-rw-rw-   0        0        0     9468 2023-06-28 12:50:49.000000 lantana-2.7.2/lantana/base.html
--rw-rw-rw-   0        0        0      306 2022-10-28 12:09:36.000000 lantana-2.7.2/lantana/breadcrumb.html
-drwxrwxrwx   0        0        0        0 2023-06-28 12:57:37.000000 lantana-2.7.2/lantana/css/
--rw-rw-rw-   0        0        0   210062 2023-05-21 06:29:23.000000 lantana-2.7.2/lantana/css/bootstrap-dark.min.css
--rw-rw-rw-   0        0        0    81940 2023-06-28 12:46:14.000000 lantana-2.7.2/lantana/css/bootstrap-icons.min.css
--rw-rw-rw-   0        0        0   155850 2023-05-21 06:31:31.000000 lantana-2.7.2/lantana/css/bootstrap.min.css
--rw-rw-rw-   0        0        0     1152 2023-05-21 06:34:35.000000 lantana-2.7.2/lantana/css/default.min.css
--rw-rw-rw-   0        0        0     2705 2023-03-05 11:56:33.000000 lantana-2.7.2/lantana/css/theme.css
--rw-rw-rw-   0        0        0     1927 2023-05-21 06:35:24.000000 lantana-2.7.2/lantana/css/vs.min.css
-drwxrwxrwx   0        0        0        0 2023-06-28 12:57:37.000000 lantana-2.7.2/lantana/extensions/
--rw-rw-rw-   0        0        0     3367 2023-06-27 12:47:44.000000 lantana-2.7.2/lantana/extensions/mdx_cards.py
--rw-rw-rw-   0        0        0     1996 2022-11-27 08:35:47.000000 lantana-2.7.2/lantana/extensions/mdx_embedly.py
--rw-rw-rw-   0        0        0     2138 2023-03-08 08:22:38.000000 lantana-2.7.2/lantana/extensions/mdx_wsid.py
--rw-rw-rw-   0        0        0        0 2022-10-28 12:09:36.000000 lantana-2.7.2/lantana/extensions/__init__.py
--rw-rw-rw-   0        0        0     1784 2022-10-28 12:09:36.000000 lantana-2.7.2/lantana/favicon.png
--rw-rw-rw-   0        0        0     4486 2022-10-28 12:09:36.000000 lantana-2.7.2/lantana/favicon.svg
-drwxrwxrwx   0        0        0        0 2023-06-28 12:57:37.000000 lantana-2.7.2/lantana/js/
--rw-rw-rw-   0        0        0    78749 2023-05-21 06:58:58.000000 lantana-2.7.2/lantana/js/bootstrap.bundle.min.js
--rw-rw-rw-   0        0        0   126355 2023-05-21 06:59:30.000000 lantana-2.7.2/lantana/js/highlight.min.js
--rw-rw-rw-   0        0        0    72535 2023-05-21 06:58:42.000000 lantana-2.7.2/lantana/js/jquery-3.6.1.slim.min.js
--rw-rw-rw-   0        0        0     5746 2023-03-05 11:57:02.000000 lantana-2.7.2/lantana/js/theme.js
--rw-rw-rw-   0        0        0     5285 2023-01-15 11:10:45.000000 lantana-2.7.2/lantana/main.html
--rw-rw-rw-   0        0        0      360 2023-02-09 08:21:12.000000 lantana-2.7.2/lantana/mkdocs_theme.yml
--rw-rw-rw-   0        0        0      843 2023-03-04 05:20:30.000000 lantana-2.7.2/lantana/nav.html
--rw-rw-rw-   0        0        0      536 2022-11-07 12:37:39.000000 lantana-2.7.2/lantana/sitemap.html
--rw-rw-rw-   0        0        0     1994 2023-06-28 12:56:36.000000 lantana-2.7.2/lantana/statics.html
--rw-rw-rw-   0        0        0      368 2023-02-16 13:48:35.000000 lantana-2.7.2/lantana/toc.html
--rw-rw-rw-   0        0        0        0 2022-10-28 12:09:36.000000 lantana-2.7.2/lantana/__init__.py
--rw-rw-rw-   0        0        0     2682 2022-12-01 09:12:15.000000 lantana-2.7.2/lantana/__main__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 12:57:37.000000 lantana-2.7.2/lantana.egg-info/
--rw-rw-rw-   0        0        0        1 2023-06-28 12:57:36.000000 lantana-2.7.2/lantana.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      279 2023-06-28 12:57:36.000000 lantana-2.7.2/lantana.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0        2 2023-06-28 12:57:36.000000 lantana-2.7.2/lantana.egg-info/not-zip-safe
--rw-rw-rw-   0        0        0      266 2023-06-28 12:57:36.000000 lantana-2.7.2/lantana.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      224 2023-06-28 12:57:36.000000 lantana-2.7.2/lantana.egg-info/requires.txt
--rw-rw-rw-   0        0        0      927 2023-06-28 12:57:36.000000 lantana-2.7.2/lantana.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        8 2023-06-28 12:57:36.000000 lantana-2.7.2/lantana.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      124 2022-10-28 12:09:36.000000 lantana-2.7.2/MANIFEST.in
--rw-rw-rw-   0        0        0      266 2023-06-28 12:57:37.000000 lantana-2.7.2/PKG-INFO
--rw-rw-rw-   0        0        0     1212 2023-03-04 05:20:30.000000 lantana-2.7.2/README.md
--rw-rw-rw-   0        0        0       42 2023-06-28 12:57:37.000000 lantana-2.7.2/setup.cfg
--rw-rw-rw-   0        0        0     1129 2023-06-28 12:56:36.000000 lantana-2.7.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:04.000000 lantana-2.7.3/
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:04.000000 lantana-2.7.3/lantana/
+-rw-rw-rw-   0        0        0      547 2022-10-28 12:09:36.000000 lantana-2.7.3/lantana/404.html
+-rw-rw-rw-   0        0        0        0 2023-06-28 13:19:19.000000 lantana-2.7.3/lantana/after_header.html
+-rw-rw-rw-   0        0        0     9446 2023-06-28 13:18:45.000000 lantana-2.7.3/lantana/base.html
+-rw-rw-rw-   0        0        0        0 2023-06-28 13:14:52.000000 lantana-2.7.3/lantana/before_header.html
+-rw-rw-rw-   0        0        0      306 2022-10-28 12:09:36.000000 lantana-2.7.3/lantana/breadcrumb.html
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:04.000000 lantana-2.7.3/lantana/css/
+-rw-rw-rw-   0        0        0   210062 2023-05-21 06:29:23.000000 lantana-2.7.3/lantana/css/bootstrap-dark.min.css
+-rw-rw-rw-   0        0        0    81940 2023-06-28 12:46:14.000000 lantana-2.7.3/lantana/css/bootstrap-icons.min.css
+-rw-rw-rw-   0        0        0   155850 2023-05-21 06:31:31.000000 lantana-2.7.3/lantana/css/bootstrap.min.css
+-rw-rw-rw-   0        0        0     1152 2023-05-21 06:34:35.000000 lantana-2.7.3/lantana/css/default.min.css
+-rw-rw-rw-   0        0        0     2705 2023-03-05 11:56:33.000000 lantana-2.7.3/lantana/css/theme.css
+-rw-rw-rw-   0        0        0     1927 2023-05-21 06:35:24.000000 lantana-2.7.3/lantana/css/vs.min.css
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:04.000000 lantana-2.7.3/lantana/extensions/
+-rw-rw-rw-   0        0        0     3367 2023-06-27 12:47:44.000000 lantana-2.7.3/lantana/extensions/mdx_cards.py
+-rw-rw-rw-   0        0        0     1996 2022-11-27 08:35:47.000000 lantana-2.7.3/lantana/extensions/mdx_embedly.py
+-rw-rw-rw-   0        0        0     2138 2023-03-08 08:22:38.000000 lantana-2.7.3/lantana/extensions/mdx_wsid.py
+-rw-rw-rw-   0        0        0        0 2022-10-28 12:09:36.000000 lantana-2.7.3/lantana/extensions/__init__.py
+-rw-rw-rw-   0        0        0     1784 2022-10-28 12:09:36.000000 lantana-2.7.3/lantana/favicon.png
+-rw-rw-rw-   0        0        0     4486 2022-10-28 12:09:36.000000 lantana-2.7.3/lantana/favicon.svg
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:04.000000 lantana-2.7.3/lantana/js/
+-rw-rw-rw-   0        0        0    78749 2023-05-21 06:58:58.000000 lantana-2.7.3/lantana/js/bootstrap.bundle.min.js
+-rw-rw-rw-   0        0        0   126355 2023-05-21 06:59:30.000000 lantana-2.7.3/lantana/js/highlight.min.js
+-rw-rw-rw-   0        0        0    72535 2023-05-21 06:58:42.000000 lantana-2.7.3/lantana/js/jquery-3.6.1.slim.min.js
+-rw-rw-rw-   0        0        0     5746 2023-03-05 11:57:02.000000 lantana-2.7.3/lantana/js/theme.js
+-rw-rw-rw-   0        0        0     5285 2023-01-15 11:10:45.000000 lantana-2.7.3/lantana/main.html
+-rw-rw-rw-   0        0        0      360 2023-02-09 08:21:12.000000 lantana-2.7.3/lantana/mkdocs_theme.yml
+-rw-rw-rw-   0        0        0      843 2023-03-04 05:20:30.000000 lantana-2.7.3/lantana/nav.html
+-rw-rw-rw-   0        0        0      536 2022-11-07 12:37:39.000000 lantana-2.7.3/lantana/sitemap.html
+-rw-rw-rw-   0        0        0     1994 2023-06-28 13:18:59.000000 lantana-2.7.3/lantana/statics.html
+-rw-rw-rw-   0        0        0      368 2023-02-16 13:48:35.000000 lantana-2.7.3/lantana/toc.html
+-rw-rw-rw-   0        0        0        0 2022-10-28 12:09:36.000000 lantana-2.7.3/lantana/__init__.py
+-rw-rw-rw-   0        0        0     2682 2022-12-01 09:12:15.000000 lantana-2.7.3/lantana/__main__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 13:21:04.000000 lantana-2.7.3/lantana.egg-info/
+-rw-rw-rw-   0        0        0        1 2023-06-28 13:21:03.000000 lantana-2.7.3/lantana.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      279 2023-06-28 13:21:03.000000 lantana-2.7.3/lantana.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0        2 2023-06-28 13:21:03.000000 lantana-2.7.3/lantana.egg-info/not-zip-safe
+-rw-rw-rw-   0        0        0      266 2023-06-28 13:21:03.000000 lantana-2.7.3/lantana.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      224 2023-06-28 13:21:03.000000 lantana-2.7.3/lantana.egg-info/requires.txt
+-rw-rw-rw-   0        0        0      980 2023-06-28 13:21:04.000000 lantana-2.7.3/lantana.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        8 2023-06-28 13:21:03.000000 lantana-2.7.3/lantana.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      124 2022-10-28 12:09:36.000000 lantana-2.7.3/MANIFEST.in
+-rw-rw-rw-   0        0        0      266 2023-06-28 13:21:04.000000 lantana-2.7.3/PKG-INFO
+-rw-rw-rw-   0        0        0     1212 2023-03-04 05:20:30.000000 lantana-2.7.3/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 13:21:04.000000 lantana-2.7.3/setup.cfg
+-rw-rw-rw-   0        0        0     1129 2023-06-28 13:18:59.000000 lantana-2.7.3/setup.py
```

### Comparing `lantana-2.7.2/lantana/404.html` & `lantana-2.7.3/lantana/404.html`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/base.html` & `lantana-2.7.3/lantana/base.html`

 * *Files 1% similar despite different names*

```diff
@@ -63,16 +63,15 @@
   <script src="{{ "js/bootstrap.bundle.min.js"|url }}"></script>
   <script async src="{{ "js/highlight.min.js"|url }}"></script>
 
   {% block extrahead %}
   {% endblock %}
 </head>
 <body>
-  {% block before_header %}
-  {% endblock %}
+  {% include "before_header.html" %}
   {% if not config.disable_header %}
     {% block header %}
     <header>
       <nav class="navbar navbar-expand-sm navbar-toggleable-sm  border-bottom box-shadow mb-3 {% if config.disable_header_when_printing %} print-hide {% endif %}">
         <div class="container">
             <a class="navbar-brand text-body" asp-area="" href="{{ "/"|url }}">
               {% if config.logo %}
@@ -196,17 +195,15 @@
           </p>
         </div>
         {% endif %}
       </div>
     </div>
   </footer>{% endblock %}
   {% endif %}
-  
-  {% block after_footer %}
-  {% endblock %}
+  {% include "after_header.html" %}
 
 <div class="modal fade" id="searchModal" data-bs-backdrop="static" data-bs-keyboard="false" tabindex="-1" aria-labelledby="searchModal" aria-hidden="true">
   <div class="modal-dialog modal-lg print-hide">
     <div class="modal-content">
       <div class="modal-header">
         <h5 class="modal-title" id="searchModalLabel">検索</h5>
         <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="閉じる"></button>
```

#### html2text {}

```diff
@@ -30,16 +30,16 @@
  {% endfor %} {% for path2 in page.extra_css %}
  {% endfor %}
 
 query-3.6.1.slim.min.js"|url }}">
 ootstrap.bundle.min.js"|url }}">
 ighlight.min.js"|url }}">
 {% block extrahead %} {% endblock %}
-{% block before_header %} {% endblock %} {% if not config.disable_header %} {%
-block header %}
+{% include "before_header.html" %} {% if not config.disable_header %} {% block
+header %}
 |url }}"> {% if config.logo %} [{{ config.site_name }}] {% endif%} {% if
 config.header_name %} {{ config.header_name }} {% else %} {{ config.site_name
 }} {% endif %}
 {% if config.visible_search!=false %} [Unknown INPUT type]    {% endif %}
 
 {% if page and page.meta.disable_nav %}  {% else %}  {% endif %} {% if
 config.visible_search %} [Unknown INPUT type]  {% endif %} {% if page and
@@ -63,11 +63,11 @@
 block footer %}
 {% if config.copyright %}
 {{ config.copyright }}
 {% endif %}
 {% if config.footimg %}
 [{{ config.footimg|url }}]
 {% endif %}
-{% endblock %} {% endif %} {% block after_footer %} {% endblock %}
+{% endblock %} {% endif %} {% include "after_header.html" %}
 ** æ¤ç´¢ **
 [                    ]
 ã­ã¼ã¯ã¼ããå¥åãã¦æ¤ç´¢ãå§ãã¾ããã
```

### Comparing `lantana-2.7.2/lantana/css/bootstrap-dark.min.css` & `lantana-2.7.3/lantana/css/bootstrap-dark.min.css`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/css/bootstrap-icons.min.css` & `lantana-2.7.3/lantana/css/bootstrap-icons.min.css`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/css/bootstrap.min.css` & `lantana-2.7.3/lantana/css/bootstrap.min.css`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/css/default.min.css` & `lantana-2.7.3/lantana/css/default.min.css`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/css/theme.css` & `lantana-2.7.3/lantana/css/theme.css`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/css/vs.min.css` & `lantana-2.7.3/lantana/css/vs.min.css`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/extensions/mdx_cards.py` & `lantana-2.7.3/lantana/extensions/mdx_cards.py`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/extensions/mdx_embedly.py` & `lantana-2.7.3/lantana/extensions/mdx_embedly.py`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/extensions/mdx_wsid.py` & `lantana-2.7.3/lantana/extensions/mdx_wsid.py`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/favicon.png` & `lantana-2.7.3/lantana/favicon.png`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/favicon.svg` & `lantana-2.7.3/lantana/favicon.svg`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/js/bootstrap.bundle.min.js` & `lantana-2.7.3/lantana/js/bootstrap.bundle.min.js`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/js/highlight.min.js` & `lantana-2.7.3/lantana/js/highlight.min.js`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/js/jquery-3.6.1.slim.min.js` & `lantana-2.7.3/lantana/js/jquery-3.6.1.slim.min.js`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/js/theme.js` & `lantana-2.7.3/lantana/js/theme.js`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/main.html` & `lantana-2.7.3/lantana/main.html`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/nav.html` & `lantana-2.7.3/lantana/nav.html`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/sitemap.html` & `lantana-2.7.3/lantana/sitemap.html`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana/statics.html` & `lantana-2.7.3/lantana/statics.html`

 * *Files 1% similar despite different names*

```diff
@@ -35,15 +35,15 @@
       <tr>
         <th scope="row">リポジトリ</th>
         <td colspan="2"><a href="{{ config.repo_url }}">{% if config.repo_name %}{{ config.repo_name }}{% else %}{{ config.repo_url }}{% endif %}</a></td>
       </tr>
       {% endif %}
       <tr>
         <th scope="row">Lantanaのバージョン</th>
-        <td>WSOFT Lantana v2.7.2(tapioca)</td>
+        <td>WSOFT Lantana v2.7.3(tapioca)</td>
       </tr>
       <tr>
         <th scope="row">MkDocsのバージョン</th>
         <td>{{ mkdocs_version }}</td>
       </tr>
     </tbody>
   </table>
```

#### html2text {}

```diff
@@ -6,15 +6,15 @@
                                         }}
 è¨äºã®ç·æ°          {{ ns.cnt }}
 ãµã¤ãã®æçµæ{{ build_date_utc }}
 ãµã¤ãã®ä½è    {{ config.author }}
                                         {%_if_config.repo_name_%}{
 ãªãã¸ããª          {_config.repo_name_}}{%_else_%}{
                                         {_config.repo_url_}}{%_endif_%}
-Lantanaã®ãã¼ã¸ã§ã�WSOFT Lantana v2.7.2
+Lantanaã®ãã¼ã¸ã§ã�WSOFT Lantana v2.7.3
                                         (tapioca)
 MkDocsã®ãã¼ã¸ã§ã{{ mkdocs_version }}
 Lantana
 Copyright 2022 WSOFT. All rights reserved.
 Lantanaã¯MkDocsããã®ä»ã®ãªã¼ãã³ã½ã¼ã¹
 ã½ããã¦ã§ã¢ã«ãã£ã¦å®ç¾ãã¾ããã
 Lantanaã®ãã¼ã ãã¼ã¸/GitHubãªãã¸ããª/WSOFTã®ãµã¤ã
```

### Comparing `lantana-2.7.2/lantana/__main__.py` & `lantana-2.7.3/lantana/__main__.py`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/lantana.egg-info/SOURCES.txt` & `lantana-2.7.3/lantana.egg-info/SOURCES.txt`

 * *Files 8% similar despite different names*

```diff
@@ -1,14 +1,16 @@
 MANIFEST.in
 README.md
 setup.py
 lantana/404.html
 lantana/__init__.py
 lantana/__main__.py
+lantana/after_header.html
 lantana/base.html
+lantana/before_header.html
 lantana/breadcrumb.html
 lantana/favicon.png
 lantana/favicon.svg
 lantana/main.html
 lantana/mkdocs_theme.yml
 lantana/nav.html
 lantana/sitemap.html
```

### Comparing `lantana-2.7.2/README.md` & `lantana-2.7.3/README.md`

 * *Files identical despite different names*

### Comparing `lantana-2.7.2/setup.py` & `lantana-2.7.3/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 from setuptools import setup, find_packages
 
-VERSION = '2.7.2'
+VERSION = '2.7.3'
 
 setup(
     name="lantana",
     version=VERSION,
     url='http://wsoft-project.github.io/lantana/',
     license='MIT',
     description='Bootstrap theme for MkDocs',
```


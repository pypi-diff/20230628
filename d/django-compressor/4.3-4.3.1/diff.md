# Comparing `tmp/django_compressor-4.3.tar.gz` & `tmp/django_compressor-4.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "django_compressor-4.3.tar", last modified: Fri Jan  6 20:57:53 2023, max compression
+gzip compressed data, was "django_compressor-4.3.1.tar", last modified: Sun Jan 22 12:43:34 2023, max compression
```

## Comparing `django_compressor-4.3.tar` & `django_compressor-4.3.1.tar`

### file list

```diff
@@ -1,350 +1,411 @@
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/
--rw-rw-r--   0 mat       (1000) mat       (1000)     1505 2021-12-12 18:04:27.000000 django_compressor-4.3/AUTHORS
--rw-rw-r--   0 mat       (1000) mat       (1000)     2345 2022-04-23 10:19:10.000000 django_compressor-4.3/LICENSE
--rw-r--r--   0 mat       (1000) mat       (1000)      323 2021-05-01 11:21:12.000000 django_compressor-4.3/MANIFEST.in
--rw-rw-r--   0 mat       (1000) mat       (1000)      406 2023-01-06 17:29:41.000000 django_compressor-4.3/Makefile
--rw-rw-r--   0 mat       (1000) mat       (1000)     4920 2023-01-06 20:57:53.374266 django_compressor-4.3/PKG-INFO
--rw-rw-r--   0 mat       (1000) mat       (1000)     3837 2023-01-06 20:56:38.000000 django_compressor-4.3/README.rst
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/
--rw-rw-r--   0 mat       (1000) mat       (1000)       40 2023-01-06 20:52:16.000000 django_compressor-4.3/compressor/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)    15891 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/base.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     4846 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/cache.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     5179 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/conf.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/contrib/
--rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/contrib/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     3253 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/contrib/jinja2ext.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     2837 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/contrib/sekizai.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     2362 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/css.py
--rw-rw-r--   0 mat       (1000) mat       (1000)      950 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/exceptions.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/filters/
--rw-rw-r--   0 mat       (1000) mat       (1000)      160 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/filters/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     8704 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/filters/base.py
--rw-r--r--   0 mat       (1000) mat       (1000)      312 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/filters/cleancss.py
--rw-r--r--   0 mat       (1000) mat       (1000)      311 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/filters/closure.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     6010 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/filters/css_default.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/filters/cssmin/
--rw-rw-r--   0 mat       (1000) mat       (1000)      558 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/filters/cssmin/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     1825 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/filters/datauri.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/filters/jsmin/
--rw-rw-r--   0 mat       (1000) mat       (1000)     1356 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/filters/jsmin/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)      370 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/filters/template.py
--rw-rw-r--   0 mat       (1000) mat       (1000)      670 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/filters/yuglify.py
--rw-rw-r--   0 mat       (1000) mat       (1000)      730 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/filters/yui.py
--rw-rw-r--   0 mat       (1000) mat       (1000)      448 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/finders.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     2717 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/js.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/management/
--rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/management/__init__.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/management/commands/
--rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/management/commands/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)    15562 2023-01-06 20:52:16.000000 django_compressor-4.3/compressor/management/commands/compress.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     3856 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/management/commands/mtime_cache.py
--rw-r--r--   0 mat       (1000) mat       (1000)       51 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/models.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/offline/
--rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/offline/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     6128 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/offline/django.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     3973 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/offline/jinja2.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/parser/
--rw-rw-r--   0 mat       (1000) mat       (1000)     1149 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/parser/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     1046 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/parser/base.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     1408 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/parser/beautifulsoup.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     2591 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/parser/default_htmlparser.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     1850 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/parser/html5lib.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     1656 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/parser/lxml.py
--rw-rw-r--   0 mat       (1000) mat       (1000)       98 2021-12-12 18:04:27.000000 django_compressor-4.3/compressor/signals.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     4725 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/storage.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.358266 django_compressor-4.3/compressor/templates/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/templates/compressor/
--rw-r--r--   0 mat       (1000) mat       (1000)      134 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/templates/compressor/css_file.html
--rw-r--r--   0 mat       (1000) mat       (1000)      127 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/templates/compressor/css_inline.html
--rw-r--r--   0 mat       (1000) mat       (1000)       61 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/templates/compressor/css_preload.html
--rw-r--r--   0 mat       (1000) mat       (1000)       66 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/templates/compressor/js_file.html
--rw-r--r--   0 mat       (1000) mat       (1000)       46 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/templates/compressor/js_inline.html
--rw-r--r--   0 mat       (1000) mat       (1000)       62 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/templates/compressor/js_preload.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/templatetags/
--rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/templatetags/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     6847 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/templatetags/compress.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     1683 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/test_settings.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/tests/
--rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)      916 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/precompiler.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/tests/static/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.362266 django_compressor-4.3/compressor/tests/static/CACHE/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.366266 django_compressor-4.3/compressor/tests/static/CACHE/css/
--rw-rw-r--   0 mat       (1000) mat       (1000)       16 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/0618b11949aa.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       28 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/19dab3491062.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       29 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/44f5d1102ce5.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       75 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/58a8c0714e59.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       21 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/5c6a60375256.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       62 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/600674ea1d3d.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       25 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/64f74be417da.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       26 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/7f02c21025ae.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       25 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/919e93a2fea0.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/a15af50e715b.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       74 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/block_name.393dbcddb48e.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       61 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/block_name.a1e074d0c4ac.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       20 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/cd0846966de0.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       24 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/dff24a7e6003.css
--rw-r--r--   0 mat       (1000) mat       (1000)       23 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.187e2ce75808.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       46 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.20f9b535162f.css
--rw-r--r--   0 mat       (1000) mat       (1000)       62 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.2db2b4d36380.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       66 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.4263023f49d6.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       37 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.44f040b05f91.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       75 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.58a8c0714e59.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       62 2021-12-12 18:05:54.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.600674ea1d3d.css
--rw-r--r--   0 mat       (1000) mat       (1000)       62 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.7ff52cb38987.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       75 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.aca9bcd16bee.css
--rw-rw-r--   0 mat       (1000) mat       (1000)      112 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.aca9bcd16bee.css.gz
--rw-rw-r--   0 mat       (1000) mat       (1000)       31 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.c836c9caed5c.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       57 2021-12-12 18:05:54.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.d5444a1ab4a3.css
--rw-rw-r--   0 mat       (1000) mat       (1000)        0 2021-12-12 18:05:54.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.e3b0c44298fc.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       62 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.e701f86c6430.css
--rw-rw-r--   0 mat       (1000) mat       (1000)      104 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.e701f86c6430.css.gz
--rw-r--r--   0 mat       (1000) mat       (1000)       23 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/output.fffafcdf428e.css
--rw-r--r--   0 mat       (1000) mat       (1000)       61 2023-01-06 17:37:20.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/relative_url.376db5682982.css
--rw-r--r--   0 mat       (1000) mat       (1000)       43 2023-01-06 17:37:20.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/relative_url.e8602322bfa6.css
--rw-r--r--   0 mat       (1000) mat       (1000)       45 2023-01-06 17:37:20.000000 django_compressor-4.3/compressor/tests/static/CACHE/css/test.222f958fb191.css
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/static/CACHE/js/
--rw-rw-r--   0 mat       (1000) mat       (1000)       10 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/29e69fc86958.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       18 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/302673cb0d9e.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/8a0fed36c317.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       12 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/d5474411b7a5.js
--rw-rw-r--   0 mat       (1000) mat       (1000)        8 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/e1cc01dd11ac.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       19 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/ed0dff257832.js
--rw-r--r--   0 mat       (1000) mat       (1000)       22 2023-01-06 17:37:20.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/one.4b3570601b8c.js
--rw-r--r--   0 mat       (1000) mat       (1000)       10 2023-01-06 17:37:20.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/one.8ab93aace8fa.js
--rw-r--r--   0 mat       (1000) mat       (1000)       43 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.0241107e9a9a.js
--rw-r--r--   0 mat       (1000) mat       (1000)       99 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.055f88f4751f.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       53 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.06a98ccfd380.js
--rw-r--r--   0 mat       (1000) mat       (1000)       26 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.2bb88185b4f5.js
--rw-r--r--   0 mat       (1000) mat       (1000)       16 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.55b3123e884c.js
--rw-r--r--   0 mat       (1000) mat       (1000)       13 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.567bb77b13db.js
--rw-r--r--   0 mat       (1000) mat       (1000)       43 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.5694ca83dd14.js
--rw-r--r--   0 mat       (1000) mat       (1000)       57 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.6ac9e4b29feb.js
--rw-r--r--   0 mat       (1000) mat       (1000)       12 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.7219642b8ab4.js
--rw-r--r--   0 mat       (1000) mat       (1000)       44 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.76a82cfab9ab.js
--rw-r--r--   0 mat       (1000) mat       (1000)       74 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.817b5defb197.js
--rw-r--r--   0 mat       (1000) mat       (1000)       21 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.822ac7501287.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.8a0fed36c317.js
--rw-r--r--   0 mat       (1000) mat       (1000)       16 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.8b4a7452e1c5.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       44 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.8c00f1cf1e0a.js
--rw-r--r--   0 mat       (1000) mat       (1000)        4 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.9a7f06880ce3.js
--rw-r--r--   0 mat       (1000) mat       (1000)       98 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.9cecd41a505f.js
--rw-r--r--   0 mat       (1000) mat       (1000)       14 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.a3275743dc69.js
--rw-r--r--   0 mat       (1000) mat       (1000)       34 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.b0bfc3754fd4.js
--rw-r--r--   0 mat       (1000) mat       (1000)       57 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.b39975a8f6ea.js
--rw-r--r--   0 mat       (1000) mat       (1000)       76 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.b8376aad1357.js
--rw-r--r--   0 mat       (1000) mat       (1000)       26 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.be0b1eade28b.js
--rw-r--r--   0 mat       (1000) mat       (1000)       16 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.bfc63829cc58.js
--rw-r--r--   0 mat       (1000) mat       (1000)       38 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.bfcec76e0f28.js
--rw-r--r--   0 mat       (1000) mat       (1000)       14 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.c6bf81bca7ad.js
--rw-r--r--   0 mat       (1000) mat       (1000)       77 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.c877c436363a.js
--rw-r--r--   0 mat       (1000) mat       (1000)       77 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.cee48db7cedc.js
--rw-r--r--   0 mat       (1000) mat       (1000)      139 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.d3f749e83c81.js
--rw-r--r--   0 mat       (1000) mat       (1000)       55 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.dd79e1bd1527.js
--rw-r--r--   0 mat       (1000) mat       (1000)       15 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.e4d043b4cde4.js
--rw-r--r--   0 mat       (1000) mat       (1000)       58 2023-01-06 17:37:18.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.e4e9263fa4c0.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       30 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.e682d84f6b17.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       20 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.ec862f0ff42c.js
--rw-r--r--   0 mat       (1000) mat       (1000)       57 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.ed565a1d262f.js
--rw-r--r--   0 mat       (1000) mat       (1000)       72 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.eeabdac29232.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       44 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.fb4a0d84e914.js
--rw-rw-r--   0 mat       (1000) mat       (1000)       44 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output.ffc39dec05fd.js
--rw-r--r--   0 mat       (1000) mat       (1000)       21 2023-01-06 17:37:19.000000 django_compressor-4.3/compressor/tests/static/CACHE/js/output_name.822ac7501287.js
--rw-r--r--   0 mat       (1000) mat       (1000)        9 2023-01-06 17:37:20.000000 django_compressor-4.3/compressor/tests/static/CACHE/test.txt
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/static/css/
--rw-r--r--   0 mat       (1000) mat       (1000)      565 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/datauri.css
--rw-r--r--   0 mat       (1000) mat       (1000)       28 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/filename with spaces.css
--rw-r--r--   0 mat       (1000) mat       (1000)       37 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/nonasc.css
--rw-r--r--   0 mat       (1000) mat       (1000)       25 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/one.css
--rw-rw-r--   0 mat       (1000) mat       (1000)       43 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/relative_url.css
--rw-r--r--   0 mat       (1000) mat       (1000)       20 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/two.css
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/static/css/url/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/static/css/url/2/
--rw-r--r--   0 mat       (1000) mat       (1000)      282 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/url/2/url2.css
--rw-r--r--   0 mat       (1000) mat       (1000)       87 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/url/nonasc.css
--rw-r--r--   0 mat       (1000) mat       (1000)       49 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/url/test.css
--rw-r--r--   0 mat       (1000) mat       (1000)      282 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/url/url1.css
--rw-r--r--   0 mat       (1000) mat       (1000)       31 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/css/utf-8_with-BOM.css
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.358266 django_compressor-4.3/compressor/tests/static/custom/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/static/custom/js/
--rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/custom/js/8a0fed36c317.js
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.358266 django_compressor-4.3/compressor/tests/static/custom/nested/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/static/custom/nested/js/
--rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:12.000000 django_compressor-4.3/compressor/tests/static/custom/nested/js/8a0fed36c317.js
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/static/img/
--rw-rw-r--   0 mat       (1000) mat       (1000)      733 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/img/add with spaces.png
--rw-r--r--   0 mat       (1000) mat       (1000)      733 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/img/add.png
--rw-r--r--   0 mat       (1000) mat       (1000)    11155 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/img/python.png
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/static/js/
--rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-12-12 18:05:55.000000 django_compressor-4.3/compressor/tests/static/js/8a0fed36c317.js
--rw-r--r--   0 mat       (1000) mat       (1000)       31 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/js/nonasc-latin1.js
--rw-r--r--   0 mat       (1000) mat       (1000)       24 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/js/nonasc.js
--rw-r--r--   0 mat       (1000) mat       (1000)       21 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/js/one.coffee
--rw-r--r--   0 mat       (1000) mat       (1000)        9 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/js/one.js
--rw-r--r--   0 mat       (1000) mat       (1000)       13 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/js/three.js
--rw-r--r--   0 mat       (1000) mat       (1000)       11 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/static/js/two.js
--rw-r--r--   0 mat       (1000) mat       (1000)        9 2023-01-06 17:37:20.000000 django_compressor-4.3/compressor/tests/static/test.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)      890 2023-01-06 17:37:20.000000 django_compressor-4.3/compressor/tests/static/test.txt.br
--rw-rw-r--   0 mat       (1000) mat       (1000)       36 2023-01-06 17:37:20.000000 django_compressor-4.3/compressor/tests/static/test.txt.gz
--rw-rw-r--   0 mat       (1000) mat       (1000)    20806 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_base.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     1318 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_conf.py
--rw-rw-r--   0 mat       (1000) mat       (1000)    25221 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_filters.py
--rw-rw-r--   0 mat       (1000) mat       (1000)      443 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_finder.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     7625 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_jinja2ext.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     1382 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_mtime_cache.py
--rw-rw-r--   0 mat       (1000) mat       (1000)    34919 2023-01-06 20:52:16.000000 django_compressor-4.3/compressor/tests/test_offline.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     5133 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_parsers.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     2486 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_sekizai.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     2459 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_signals.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     3547 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_storages.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.358266 django_compressor-4.3/compressor/tests/test_templates/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/basic/
--rw-r--r--   0 mat       (1000) mat       (1000)      170 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/basic/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_block_super/
--rw-r--r--   0 mat       (1000) mat       (1000)      283 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super/base.html
--rw-r--r--   0 mat       (1000) mat       (1000)      301 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_block_super_base_compressed/
--rw-r--r--   0 mat       (1000) mat       (1000)      237 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_base_compressed/base.html
--rw-r--r--   0 mat       (1000) mat       (1000)      210 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_base_compressed/base2.html
--rw-r--r--   0 mat       (1000) mat       (1000)      393 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_base_compressed/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_block_super_extra/
--rw-r--r--   0 mat       (1000) mat       (1000)      283 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_extra/base.html
--rw-r--r--   0 mat       (1000) mat       (1000)      439 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_extra/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_block_super_multiple/
--rw-r--r--   0 mat       (1000) mat       (1000)      308 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_multiple/base.html
--rw-r--r--   0 mat       (1000) mat       (1000)      241 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_multiple/base2.html
--rw-r--r--   0 mat       (1000) mat       (1000)      274 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_multiple/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_block_super_multiple_cached/
--rw-r--r--   0 mat       (1000) mat       (1000)      308 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_multiple_cached/base.html
--rw-r--r--   0 mat       (1000) mat       (1000)       57 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_multiple_cached/base2.html
--rw-r--r--   0 mat       (1000) mat       (1000)      274 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_block_super_multiple_cached/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_complex/
--rw-r--r--   0 mat       (1000) mat       (1000)      695 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_complex/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_compress_command/
--rw-rw-r--   0 mat       (1000) mat       (1000)      192 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_compress_command/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_condition/
--rw-r--r--   0 mat       (1000) mat       (1000)      219 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_condition/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_duplicate/
--rw-r--r--   0 mat       (1000) mat       (1000)      285 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_duplicate/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_error_handling/
--rw-r--r--   0 mat       (1000) mat       (1000)      192 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_error_handling/buggy_extends.html
--rw-r--r--   0 mat       (1000) mat       (1000)      167 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_error_handling/buggy_template.html
--rw-r--r--   0 mat       (1000) mat       (1000)      185 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_error_handling/missing_extends.html
--rw-r--r--   0 mat       (1000) mat       (1000)      221 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_error_handling/test_compressor_offline.html
--rw-r--r--   0 mat       (1000) mat       (1000)      137 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_error_handling/with_coffeescript.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_extends_recursion/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_extends_recursion/admin/
--rw-rw-r--   0 mat       (1000) mat       (1000)       33 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_extends_recursion/admin/index.html
--rw-rw-r--   0 mat       (1000) mat       (1000)      115 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_extends_recursion/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_extends_relative/
--rw-rw-r--   0 mat       (1000) mat       (1000)      283 2021-12-12 18:04:27.000000 django_compressor-4.3/compressor/tests/test_templates/test_extends_relative/base.html
--rw-rw-r--   0 mat       (1000) mat       (1000)      303 2021-12-12 18:04:27.000000 django_compressor-4.3/compressor/tests/test_templates/test_extends_relative/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_inline_non_ascii/
--rw-r--r--   0 mat       (1000) mat       (1000)      197 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_inline_non_ascii/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_static_templatetag/
--rw-r--r--   0 mat       (1000) mat       (1000)      212 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_static_templatetag/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_static_url_independence/
--rw-rw-r--   0 mat       (1000) mat       (1000)      142 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_static_url_independence/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_templatetag/
--rw-r--r--   0 mat       (1000) mat       (1000)      190 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_templatetag/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_templatetag_named/
--rw-r--r--   0 mat       (1000) mat       (1000)      186 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_templatetag_named/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_with_context/
--rw-r--r--   0 mat       (1000) mat       (1000)      189 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_with_context/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_with_context_super/
--rw-rw-r--   0 mat       (1000) mat       (1000)      164 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_with_context_super/base.html
--rw-rw-r--   0 mat       (1000) mat       (1000)      322 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_with_context_super/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_with_context_variable_inheritance/
--rw-rw-r--   0 mat       (1000) mat       (1000)      233 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_with_context_variable_inheritance/base.html
--rw-rw-r--   0 mat       (1000) mat       (1000)       30 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_with_context_variable_inheritance/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates/test_with_context_variable_inheritance_super/
--rw-rw-r--   0 mat       (1000) mat       (1000)      200 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_with_context_variable_inheritance_super/base1.html
--rw-rw-r--   0 mat       (1000) mat       (1000)      200 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_with_context_variable_inheritance_super/base2.html
--rw-rw-r--   0 mat       (1000) mat       (1000)      184 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates/test_with_context_variable_inheritance_super/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.358266 django_compressor-4.3/compressor/tests/test_templates_jinja2/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.370266 django_compressor-4.3/compressor/tests/test_templates_jinja2/basic/
--rw-r--r--   0 mat       (1000) mat       (1000)      151 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/basic/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super/
--rw-r--r--   0 mat       (1000) mat       (1000)      283 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super/base.html
--rw-r--r--   0 mat       (1000) mat       (1000)      277 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_extra/
--rw-r--r--   0 mat       (1000) mat       (1000)      283 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_extra/base.html
--rw-r--r--   0 mat       (1000) mat       (1000)      415 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_extra/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_multiple/
--rw-r--r--   0 mat       (1000) mat       (1000)      308 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_multiple/base.html
--rw-r--r--   0 mat       (1000) mat       (1000)       57 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_multiple/base2.html
--rw-r--r--   0 mat       (1000) mat       (1000)      250 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_multiple/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_multiple_cached/
--rw-r--r--   0 mat       (1000) mat       (1000)      308 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_multiple_cached/base.html
--rw-r--r--   0 mat       (1000) mat       (1000)       57 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_multiple_cached/base2.html
--rw-r--r--   0 mat       (1000) mat       (1000)      250 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_block_super_multiple_cached/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_coffin/
--rw-r--r--   0 mat       (1000) mat       (1000)      406 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_coffin/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_complex/
--rw-r--r--   0 mat       (1000) mat       (1000)      801 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_complex/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_compress_command/
--rw-rw-r--   0 mat       (1000) mat       (1000)      173 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_compress_command/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_condition/
--rw-r--r--   0 mat       (1000) mat       (1000)      201 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_condition/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_duplicate/
--rw-r--r--   0 mat       (1000) mat       (1000)      266 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_duplicate/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_error_handling/
--rw-r--r--   0 mat       (1000) mat       (1000)      172 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_error_handling/buggy_extends.html
--rw-r--r--   0 mat       (1000) mat       (1000)      146 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_error_handling/buggy_template.html
--rw-r--r--   0 mat       (1000) mat       (1000)      165 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_error_handling/missing_extends.html
--rw-r--r--   0 mat       (1000) mat       (1000)      202 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_error_handling/test_compressor_offline.html
--rw-r--r--   0 mat       (1000) mat       (1000)      116 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_error_handling/with_coffeescript.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_extends_recursion/
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_extends_recursion/admin/
--rw-r--r--   0 mat       (1000) mat       (1000)       33 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_extends_recursion/admin/index.html
--rw-r--r--   0 mat       (1000) mat       (1000)       94 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_extends_recursion/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_inline_non_ascii/
--rw-r--r--   0 mat       (1000) mat       (1000)      179 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_inline_non_ascii/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_jingo/
--rw-r--r--   0 mat       (1000) mat       (1000)      453 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_jingo/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_static_templatetag/
--rw-r--r--   0 mat       (1000) mat       (1000)      207 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_static_templatetag/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_static_url_independence/
--rw-rw-r--   0 mat       (1000) mat       (1000)      123 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_static_url_independence/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_templatetag/
--rw-r--r--   0 mat       (1000) mat       (1000)      178 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_templatetag/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_templatetag_named/
--rw-r--r--   0 mat       (1000) mat       (1000)      167 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_templatetag_named/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_with_context/
--rw-r--r--   0 mat       (1000) mat       (1000)      171 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_with_context/test_compressor_offline.html
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_with_context_variable_inheritance/
--rw-rw-r--   0 mat       (1000) mat       (1000)      214 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_with_context_variable_inheritance/base.html
--rw-rw-r--   0 mat       (1000) mat       (1000)       30 2021-05-01 11:22:11.000000 django_compressor-4.3/compressor/tests/test_templates_jinja2/test_with_context_variable_inheritance/test_compressor_offline.html
--rw-rw-r--   0 mat       (1000) mat       (1000)    13665 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_templatetags.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     2147 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/tests/test_utils.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/compressor/utils/
--rw-rw-r--   0 mat       (1000) mat       (1000)     1434 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/utils/__init__.py
--rw-rw-r--   0 mat       (1000) mat       (1000)      583 2023-01-06 17:29:41.000000 django_compressor-4.3/compressor/utils/staticfiles.py
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/django_compressor.egg-info/
--rw-rw-r--   0 mat       (1000) mat       (1000)     4920 2023-01-06 20:57:53.000000 django_compressor-4.3/django_compressor.egg-info/PKG-INFO
--rw-rw-r--   0 mat       (1000) mat       (1000)    14027 2023-01-06 20:57:53.000000 django_compressor-4.3/django_compressor.egg-info/SOURCES.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)        1 2023-01-06 20:57:53.000000 django_compressor-4.3/django_compressor.egg-info/dependency_links.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)        1 2021-05-01 11:22:11.000000 django_compressor-4.3/django_compressor.egg-info/not-zip-safe
--rw-rw-r--   0 mat       (1000) mat       (1000)       51 2023-01-06 20:57:53.000000 django_compressor-4.3/django_compressor.egg-info/requires.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)       11 2023-01-06 20:57:53.000000 django_compressor-4.3/django_compressor.egg-info/top_level.txt
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/docs/
--rw-r--r--   0 mat       (1000) mat       (1000)     4634 2021-05-01 11:21:12.000000 django_compressor-4.3/docs/Makefile
--rw-rw-r--   0 mat       (1000) mat       (1000)     2570 2021-05-01 11:21:12.000000 django_compressor-4.3/docs/behind-the-scenes.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)    20558 2023-01-06 20:52:16.000000 django_compressor-4.3/docs/changelog.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)     7285 2022-10-28 17:05:12.000000 django_compressor-4.3/docs/conf.py
--rw-rw-r--   0 mat       (1000) mat       (1000)     6396 2021-12-12 18:04:27.000000 django_compressor-4.3/docs/contributing.txt
--rw-r--r--   0 mat       (1000) mat       (1000)     2684 2021-05-01 11:21:12.000000 django_compressor-4.3/docs/django-sekizai.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)     1231 2021-12-12 18:20:53.000000 django_compressor-4.3/docs/index.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)     3655 2021-05-01 11:21:12.000000 django_compressor-4.3/docs/jinja2.txt
--rw-r--r--   0 mat       (1000) mat       (1000)     4533 2021-05-01 11:21:12.000000 django_compressor-4.3/docs/make.bat
--rw-rw-r--   0 mat       (1000) mat       (1000)     2682 2022-04-23 10:19:10.000000 django_compressor-4.3/docs/quickstart.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)     2207 2021-12-12 18:04:27.000000 django_compressor-4.3/docs/reactjs.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)     4084 2023-01-06 17:29:41.000000 django_compressor-4.3/docs/remote-storages.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)     2591 2021-05-01 11:21:12.000000 django_compressor-4.3/docs/scenarios.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)    19557 2023-01-06 17:29:41.000000 django_compressor-4.3/docs/settings.txt
--rw-rw-r--   0 mat       (1000) mat       (1000)     8682 2022-08-03 16:03:37.000000 django_compressor-4.3/docs/usage.txt
-drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-06 20:57:53.374266 django_compressor-4.3/requirements/
--rw-rw-r--   0 mat       (1000) mat       (1000)      207 2023-01-06 17:29:41.000000 django_compressor-4.3/requirements/tests.txt
--rw-r--r--   0 mat       (1000) mat       (1000)       61 2023-01-06 20:57:53.374266 django_compressor-4.3/setup.cfg
--rw-rw-r--   0 mat       (1000) mat       (1000)     5684 2023-01-06 20:52:16.000000 django_compressor-4.3/setup.py
--rw-rw-r--   0 mat       (1000) mat       (1000)      477 2023-01-06 20:52:16.000000 django_compressor-4.3/tox.ini
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.202607 django_compressor-4.3.1/
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1505 2021-12-12 18:04:27.000000 django_compressor-4.3.1/AUTHORS
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2345 2022-04-23 10:19:10.000000 django_compressor-4.3.1/LICENSE
+-rw-r--r--   0 mat       (1000) mat       (1000)      323 2021-05-01 11:21:12.000000 django_compressor-4.3.1/MANIFEST.in
+-rw-rw-r--   0 mat       (1000) mat       (1000)      406 2023-01-06 17:29:41.000000 django_compressor-4.3.1/Makefile
+-rw-rw-r--   0 mat       (1000) mat       (1000)     4900 2023-01-22 12:43:34.202607 django_compressor-4.3.1/PKG-INFO
+-rw-rw-r--   0 mat       (1000) mat       (1000)     3837 2023-01-20 23:59:53.000000 django_compressor-4.3.1/README.rst
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/
+-rw-rw-r--   0 mat       (1000) mat       (1000)       42 2023-01-22 12:40:08.000000 django_compressor-4.3.1/compressor/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)    15891 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/base.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     4846 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/cache.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     5179 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/conf.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/contrib/
+-rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/contrib/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     3253 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/contrib/jinja2ext.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2837 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/contrib/sekizai.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2362 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/css.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)      950 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/exceptions.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/filters/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      160 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/filters/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     8704 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/filters/base.py
+-rw-r--r--   0 mat       (1000) mat       (1000)      312 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/filters/cleancss.py
+-rw-r--r--   0 mat       (1000) mat       (1000)      311 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/filters/closure.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     6010 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/filters/css_default.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/filters/cssmin/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      558 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/filters/cssmin/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1825 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/filters/datauri.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/filters/jsmin/
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1356 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/filters/jsmin/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)      370 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/filters/template.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)      670 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/filters/yuglify.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)      730 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/filters/yui.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)      448 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/finders.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2717 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/js.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/management/
+-rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/management/__init__.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/management/commands/
+-rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/management/commands/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)    15562 2023-01-20 23:59:53.000000 django_compressor-4.3.1/compressor/management/commands/compress.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     3856 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/management/commands/mtime_cache.py
+-rw-r--r--   0 mat       (1000) mat       (1000)       51 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/models.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/offline/
+-rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/offline/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     6128 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/offline/django.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     3973 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/offline/jinja2.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/parser/
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1149 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/parser/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1046 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/parser/base.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1408 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/parser/beautifulsoup.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2591 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/parser/default_htmlparser.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1850 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/parser/html5lib.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1656 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/parser/lxml.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)       98 2021-12-12 18:04:27.000000 django_compressor-4.3.1/compressor/signals.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     4725 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/storage.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.178607 django_compressor-4.3.1/compressor/templates/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.186607 django_compressor-4.3.1/compressor/templates/compressor/
+-rw-r--r--   0 mat       (1000) mat       (1000)      134 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/templates/compressor/css_file.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      127 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/templates/compressor/css_inline.html
+-rw-r--r--   0 mat       (1000) mat       (1000)       61 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/templates/compressor/css_preload.html
+-rw-r--r--   0 mat       (1000) mat       (1000)       66 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/templates/compressor/js_file.html
+-rw-r--r--   0 mat       (1000) mat       (1000)       46 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/templates/compressor/js_inline.html
+-rw-r--r--   0 mat       (1000) mat       (1000)       62 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/templates/compressor/js_preload.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.186607 django_compressor-4.3.1/compressor/templatetags/
+-rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/templatetags/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     6847 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/templatetags/compress.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1683 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/test_settings.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.186607 django_compressor-4.3.1/compressor/tests/
+-rw-r--r--   0 mat       (1000) mat       (1000)        0 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)      916 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/precompiler.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.186607 django_compressor-4.3.1/compressor/tests/static/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.186607 django_compressor-4.3.1/compressor/tests/static/CACHE/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.186607 django_compressor-4.3.1/compressor/tests/static/CACHE/css/
+-rw-rw-r--   0 mat       (1000) mat       (1000)       16 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/0618b11949aa.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       28 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/19dab3491062.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       29 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/44f5d1102ce5.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       75 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/58a8c0714e59.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       21 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/5c6a60375256.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       62 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/600674ea1d3d.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       25 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/64f74be417da.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       26 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/7f02c21025ae.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       25 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/919e93a2fea0.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/a15af50e715b.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       74 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/block_name.393dbcddb48e.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       61 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/block_name.a1e074d0c4ac.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       20 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/cd0846966de0.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       24 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/dff24a7e6003.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       23 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.187e2ce75808.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       46 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.20f9b535162f.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       62 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.2db2b4d36380.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       66 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.4263023f49d6.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       37 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.44f040b05f91.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       75 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.58a8c0714e59.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       62 2021-12-12 18:05:54.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.600674ea1d3d.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       62 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.7ff52cb38987.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       75 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.aca9bcd16bee.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)      112 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.aca9bcd16bee.css.gz
+-rw-rw-r--   0 mat       (1000) mat       (1000)       31 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.c836c9caed5c.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       57 2021-12-12 18:05:54.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.d5444a1ab4a3.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)        0 2021-12-12 18:05:54.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.e3b0c44298fc.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       62 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.e701f86c6430.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)      104 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.e701f86c6430.css.gz
+-rw-r--r--   0 mat       (1000) mat       (1000)       23 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/output.fffafcdf428e.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       61 2023-01-06 17:37:20.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/relative_url.376db5682982.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       43 2023-01-06 17:37:20.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/relative_url.e8602322bfa6.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       45 2023-01-06 17:37:20.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/css/test.222f958fb191.css
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/static/CACHE/js/
+-rw-rw-r--   0 mat       (1000) mat       (1000)       10 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/29e69fc86958.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       18 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/302673cb0d9e.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/8a0fed36c317.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       12 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/d5474411b7a5.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)        8 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/e1cc01dd11ac.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       19 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/ed0dff257832.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       22 2023-01-06 17:37:20.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/one.4b3570601b8c.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       10 2023-01-06 17:37:20.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/one.8ab93aace8fa.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       43 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.0241107e9a9a.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       99 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.055f88f4751f.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       53 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.06a98ccfd380.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       26 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.2bb88185b4f5.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       16 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.55b3123e884c.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       13 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.567bb77b13db.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       43 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.5694ca83dd14.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       57 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.6ac9e4b29feb.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       12 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.7219642b8ab4.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       44 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.76a82cfab9ab.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       74 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.817b5defb197.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       21 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.822ac7501287.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.8a0fed36c317.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       16 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.8b4a7452e1c5.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       44 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.8c00f1cf1e0a.js
+-rw-r--r--   0 mat       (1000) mat       (1000)        4 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.9a7f06880ce3.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       98 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.9cecd41a505f.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       14 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.a3275743dc69.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       34 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.b0bfc3754fd4.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       57 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.b39975a8f6ea.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       76 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.b8376aad1357.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       26 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.be0b1eade28b.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       16 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.bfc63829cc58.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       38 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.bfcec76e0f28.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       14 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.c6bf81bca7ad.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       77 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.c877c436363a.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       77 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.cee48db7cedc.js
+-rw-r--r--   0 mat       (1000) mat       (1000)      139 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.d3f749e83c81.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       55 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.dd79e1bd1527.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       15 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.e4d043b4cde4.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       58 2023-01-06 17:37:18.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.e4e9263fa4c0.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       30 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.e682d84f6b17.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       20 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.ec862f0ff42c.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       57 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.ed565a1d262f.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       72 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.eeabdac29232.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       44 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.fb4a0d84e914.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       44 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output.ffc39dec05fd.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       21 2023-01-06 17:37:19.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/js/output_name.822ac7501287.js
+-rw-r--r--   0 mat       (1000) mat       (1000)        9 2023-01-06 17:37:20.000000 django_compressor-4.3.1/compressor/tests/static/CACHE/test.txt
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/static/css/
+-rw-r--r--   0 mat       (1000) mat       (1000)      565 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/datauri.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       28 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/filename with spaces.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       37 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/nonasc.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       25 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/one.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       43 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/relative_url.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       20 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/two.css
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/static/css/url/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/static/css/url/2/
+-rw-r--r--   0 mat       (1000) mat       (1000)      282 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/url/2/url2.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       87 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/url/nonasc.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       49 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/url/test.css
+-rw-r--r--   0 mat       (1000) mat       (1000)      282 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/url/url1.css
+-rw-r--r--   0 mat       (1000) mat       (1000)       31 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/css/utf-8_with-BOM.css
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.178607 django_compressor-4.3.1/compressor/tests/static/custom/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/static/custom/js/
+-rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/custom/js/8a0fed36c317.js
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.178607 django_compressor-4.3.1/compressor/tests/static/custom/nested/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/static/custom/nested/js/
+-rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-05-01 11:22:12.000000 django_compressor-4.3.1/compressor/tests/static/custom/nested/js/8a0fed36c317.js
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/static/img/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      733 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/img/add with spaces.png
+-rw-r--r--   0 mat       (1000) mat       (1000)      733 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/img/add.png
+-rw-r--r--   0 mat       (1000) mat       (1000)    11155 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/img/python.png
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/static/js/
+-rw-rw-r--   0 mat       (1000) mat       (1000)       27 2021-12-12 18:05:55.000000 django_compressor-4.3.1/compressor/tests/static/js/8a0fed36c317.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       31 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/js/nonasc-latin1.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       24 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/js/nonasc.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       21 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/js/one.coffee
+-rw-r--r--   0 mat       (1000) mat       (1000)        9 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/js/one.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       13 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/js/three.js
+-rw-r--r--   0 mat       (1000) mat       (1000)       11 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/static/js/two.js
+-rw-r--r--   0 mat       (1000) mat       (1000)        9 2023-01-06 17:37:20.000000 django_compressor-4.3.1/compressor/tests/static/test.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)      890 2023-01-06 17:37:20.000000 django_compressor-4.3.1/compressor/tests/static/test.txt.br
+-rw-rw-r--   0 mat       (1000) mat       (1000)       36 2023-01-06 17:37:20.000000 django_compressor-4.3.1/compressor/tests/static/test.txt.gz
+-rw-rw-r--   0 mat       (1000) mat       (1000)    20806 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_base.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1318 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_conf.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)    25221 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_filters.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)      443 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_finder.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     7625 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_jinja2ext.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1382 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_mtime_cache.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)    34919 2023-01-20 23:59:53.000000 django_compressor-4.3.1/compressor/tests/test_offline.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     5133 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_parsers.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2486 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_sekizai.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2459 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_signals.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     3547 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_storages.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/tests/test_templates/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/basic/
+-rw-r--r--   0 mat       (1000) mat       (1000)      170 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/basic/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super/
+-rw-r--r--   0 mat       (1000) mat       (1000)      283 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super/base.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      301 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_base_compressed/
+-rw-r--r--   0 mat       (1000) mat       (1000)      237 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_base_compressed/base.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      210 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_base_compressed/base2.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      393 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_base_compressed/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_extra/
+-rw-r--r--   0 mat       (1000) mat       (1000)      283 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_extra/base.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      439 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_extra/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_multiple/
+-rw-r--r--   0 mat       (1000) mat       (1000)      308 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_multiple/base.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      241 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_multiple/base2.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      274 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_multiple/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_multiple_cached/
+-rw-r--r--   0 mat       (1000) mat       (1000)      308 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_multiple_cached/base.html
+-rw-r--r--   0 mat       (1000) mat       (1000)       57 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_multiple_cached/base2.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      274 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_block_super_multiple_cached/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_complex/
+-rw-r--r--   0 mat       (1000) mat       (1000)      695 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_complex/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_compress_command/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      192 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_compress_command/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_condition/
+-rw-r--r--   0 mat       (1000) mat       (1000)      219 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_condition/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_duplicate/
+-rw-r--r--   0 mat       (1000) mat       (1000)      285 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_duplicate/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_error_handling/
+-rw-r--r--   0 mat       (1000) mat       (1000)      192 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_error_handling/buggy_extends.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      167 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_error_handling/buggy_template.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      185 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_error_handling/missing_extends.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      221 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_error_handling/test_compressor_offline.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      137 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_error_handling/with_coffeescript.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.190606 django_compressor-4.3.1/compressor/tests/test_templates/test_extends_recursion/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_extends_recursion/admin/
+-rw-rw-r--   0 mat       (1000) mat       (1000)       33 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_extends_recursion/admin/index.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)      115 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_extends_recursion/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_extends_relative/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      283 2021-12-12 18:04:27.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_extends_relative/base.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)      303 2021-12-12 18:04:27.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_extends_relative/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_inline_non_ascii/
+-rw-r--r--   0 mat       (1000) mat       (1000)      197 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_inline_non_ascii/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_static_templatetag/
+-rw-r--r--   0 mat       (1000) mat       (1000)      212 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_static_templatetag/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_static_url_independence/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      142 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_static_url_independence/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_templatetag/
+-rw-r--r--   0 mat       (1000) mat       (1000)      190 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_templatetag/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_templatetag_named/
+-rw-r--r--   0 mat       (1000) mat       (1000)      186 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_templatetag_named/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context/
+-rw-r--r--   0 mat       (1000) mat       (1000)      189 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_super/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      164 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_super/base.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)      322 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_super/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_variable_inheritance/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      233 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_variable_inheritance/base.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)       30 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_variable_inheritance/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_variable_inheritance_super/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      200 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_variable_inheritance_super/base1.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)      200 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_variable_inheritance_super/base2.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)      184 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates/test_with_context_variable_inheritance_super/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/basic/
+-rw-r--r--   0 mat       (1000) mat       (1000)      151 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/basic/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super/
+-rw-r--r--   0 mat       (1000) mat       (1000)      283 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super/base.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      277 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_extra/
+-rw-r--r--   0 mat       (1000) mat       (1000)      283 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_extra/base.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      415 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_extra/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_multiple/
+-rw-r--r--   0 mat       (1000) mat       (1000)      308 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_multiple/base.html
+-rw-r--r--   0 mat       (1000) mat       (1000)       57 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_multiple/base2.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      250 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_multiple/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_multiple_cached/
+-rw-r--r--   0 mat       (1000) mat       (1000)      308 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_multiple_cached/base.html
+-rw-r--r--   0 mat       (1000) mat       (1000)       57 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_multiple_cached/base2.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      250 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_block_super_multiple_cached/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_coffin/
+-rw-r--r--   0 mat       (1000) mat       (1000)      406 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_coffin/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_complex/
+-rw-r--r--   0 mat       (1000) mat       (1000)      801 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_complex/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_compress_command/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      173 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_compress_command/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_condition/
+-rw-r--r--   0 mat       (1000) mat       (1000)      201 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_condition/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_duplicate/
+-rw-r--r--   0 mat       (1000) mat       (1000)      266 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_duplicate/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_error_handling/
+-rw-r--r--   0 mat       (1000) mat       (1000)      172 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_error_handling/buggy_extends.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      146 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_error_handling/buggy_template.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      165 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_error_handling/missing_extends.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      202 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_error_handling/test_compressor_offline.html
+-rw-r--r--   0 mat       (1000) mat       (1000)      116 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_error_handling/with_coffeescript.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_extends_recursion/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_extends_recursion/admin/
+-rw-r--r--   0 mat       (1000) mat       (1000)       33 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_extends_recursion/admin/index.html
+-rw-r--r--   0 mat       (1000) mat       (1000)       94 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_extends_recursion/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_inline_non_ascii/
+-rw-r--r--   0 mat       (1000) mat       (1000)      179 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_inline_non_ascii/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_jingo/
+-rw-r--r--   0 mat       (1000) mat       (1000)      453 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_jingo/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_static_templatetag/
+-rw-r--r--   0 mat       (1000) mat       (1000)      207 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_static_templatetag/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_static_url_independence/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      123 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_static_url_independence/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_templatetag/
+-rw-r--r--   0 mat       (1000) mat       (1000)      178 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_templatetag/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_templatetag_named/
+-rw-r--r--   0 mat       (1000) mat       (1000)      167 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_templatetag_named/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_with_context/
+-rw-r--r--   0 mat       (1000) mat       (1000)      171 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_with_context/test_compressor_offline.html
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_with_context_variable_inheritance/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      214 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_with_context_variable_inheritance/base.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)       30 2021-05-01 11:22:11.000000 django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_with_context_variable_inheritance/test_compressor_offline.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)    13665 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_templatetags.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2147 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/tests/test_utils.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/compressor/utils/
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1434 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/utils/__init__.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)      583 2023-01-06 17:29:41.000000 django_compressor-4.3.1/compressor/utils/staticfiles.py
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.194607 django_compressor-4.3.1/django_compressor.egg-info/
+-rw-rw-r--   0 mat       (1000) mat       (1000)     4900 2023-01-22 12:43:34.000000 django_compressor-4.3.1/django_compressor.egg-info/PKG-INFO
+-rw-rw-r--   0 mat       (1000) mat       (1000)    16127 2023-01-22 12:43:34.000000 django_compressor-4.3.1/django_compressor.egg-info/SOURCES.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)        1 2023-01-22 12:43:34.000000 django_compressor-4.3.1/django_compressor.egg-info/dependency_links.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)        1 2021-05-01 11:22:11.000000 django_compressor-4.3.1/django_compressor.egg-info/not-zip-safe
+-rw-rw-r--   0 mat       (1000) mat       (1000)       51 2023-01-22 12:43:34.000000 django_compressor-4.3.1/django_compressor.egg-info/requires.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)       11 2023-01-22 12:43:34.000000 django_compressor-4.3.1/django_compressor.egg-info/top_level.txt
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.198607 django_compressor-4.3.1/docs/
+-rw-r--r--   0 mat       (1000) mat       (1000)     4634 2021-05-01 11:21:12.000000 django_compressor-4.3.1/docs/Makefile
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.182607 django_compressor-4.3.1/docs/_build/
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.198607 django_compressor-4.3.1/docs/_build/doctrees/
+-rw-rw-r--   0 mat       (1000) mat       (1000)    10862 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/behind-the-scenes.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)   138838 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/changelog.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)    29831 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/contributing.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)    11381 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/django-sekizai.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)    57440 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/environment.pickle
+-rw-rw-r--   0 mat       (1000) mat       (1000)     8444 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/index.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)    18902 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/jinja2.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)    21696 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/quickstart.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)    13039 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/reactjs.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)    21640 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/remote-storages.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)    16545 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/scenarios.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)   129458 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/settings.doctree
+-rw-rw-r--   0 mat       (1000) mat       (1000)    49114 2023-01-22 12:02:33.000000 django_compressor-4.3.1/docs/_build/doctrees/usage.doctree
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.198607 django_compressor-4.3.1/docs/_build/html/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      230 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/.buildinfo
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.202607 django_compressor-4.3.1/docs/_build/html/_sources/
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2576 2023-01-22 11:58:41.000000 django_compressor-4.3.1/docs/_build/html/_sources/behind-the-scenes.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)    20979 2023-01-22 11:58:27.000000 django_compressor-4.3.1/docs/_build/html/_sources/changelog.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     6396 2021-12-12 18:04:27.000000 django_compressor-4.3.1/docs/_build/html/_sources/contributing.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2684 2021-05-01 11:21:12.000000 django_compressor-4.3.1/docs/_build/html/_sources/django-sekizai.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1231 2021-12-12 18:20:53.000000 django_compressor-4.3.1/docs/_build/html/_sources/index.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     3655 2021-05-01 11:21:12.000000 django_compressor-4.3.1/docs/_build/html/_sources/jinja2.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2691 2023-01-22 11:52:37.000000 django_compressor-4.3.1/docs/_build/html/_sources/quickstart.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2207 2021-12-12 18:04:27.000000 django_compressor-4.3.1/docs/_build/html/_sources/reactjs.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     4084 2023-01-06 17:29:41.000000 django_compressor-4.3.1/docs/_build/html/_sources/remote-storages.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2591 2021-05-01 11:21:12.000000 django_compressor-4.3.1/docs/_build/html/_sources/scenarios.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)    19657 2023-01-22 12:02:26.000000 django_compressor-4.3.1/docs/_build/html/_sources/settings.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     8682 2022-08-03 16:03:37.000000 django_compressor-4.3.1/docs/_build/html/_sources/usage.txt
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.202607 django_compressor-4.3.1/docs/_build/html/_static/
+-rw-rw-r--   0 mat       (1000) mat       (1000)    11185 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/_static/alabaster.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)    14667 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/_static/basic.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)       42 2017-05-15 18:58:47.000000 django_compressor-4.3.1/docs/_build/html/_static/custom.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)     9630 2021-11-17 15:50:47.000000 django_compressor-4.3.1/docs/_build/html/_static/doctools.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)      355 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/_static/documentation_options.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)      286 2021-01-01 06:53:29.000000 django_compressor-4.3.1/docs/_build/html/_static/file.png
+-rw-rw-r--   0 mat       (1000) mat       (1000)     4787 2021-06-13 20:25:40.000000 django_compressor-4.3.1/docs/_build/html/_static/forkme_right_darkblue_121621.png
+-rw-rw-r--   0 mat       (1000) mat       (1000)   288550 2022-02-21 10:29:39.000000 django_compressor-4.3.1/docs/_build/html/_static/jquery.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)    10854 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/_static/language_data.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)       90 2021-01-01 06:53:29.000000 django_compressor-4.3.1/docs/_build/html/_static/minus.png
+-rw-rw-r--   0 mat       (1000) mat       (1000)       90 2021-01-01 06:53:29.000000 django_compressor-4.3.1/docs/_build/html/_static/plus.png
+-rw-rw-r--   0 mat       (1000) mat       (1000)     5212 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/_static/pygments.css
+-rw-rw-r--   0 mat       (1000) mat       (1000)    16950 2021-12-19 12:55:13.000000 django_compressor-4.3.1/docs/_build/html/_static/searchtools.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)    68398 2021-12-16 10:20:19.000000 django_compressor-4.3.1/docs/_build/html/_static/underscore.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)     8075 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/behind-the-scenes.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)    46111 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/changelog.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)    13200 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/contributing.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)     9981 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/django-sekizai.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)     9174 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/genindex.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)    14248 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/index.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)    12993 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/jinja2.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)      992 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/objects.inv
+-rw-rw-r--   0 mat       (1000) mat       (1000)    10896 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/quickstart.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)     8441 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/reactjs.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)    13729 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/remote-storages.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)     9062 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/scenarios.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)     3804 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/search.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)    20528 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/searchindex.js
+-rw-rw-r--   0 mat       (1000) mat       (1000)    57224 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/settings.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)    26119 2023-01-22 12:02:34.000000 django_compressor-4.3.1/docs/_build/html/usage.html
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2576 2023-01-22 12:40:08.000000 django_compressor-4.3.1/docs/behind-the-scenes.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)    20979 2023-01-22 12:40:08.000000 django_compressor-4.3.1/docs/changelog.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     7407 2023-01-21 00:06:24.000000 django_compressor-4.3.1/docs/conf.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)     6396 2021-12-12 18:04:27.000000 django_compressor-4.3.1/docs/contributing.txt
+-rw-r--r--   0 mat       (1000) mat       (1000)     2684 2021-05-01 11:21:12.000000 django_compressor-4.3.1/docs/django-sekizai.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     1231 2021-12-12 18:20:53.000000 django_compressor-4.3.1/docs/index.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     3655 2021-05-01 11:21:12.000000 django_compressor-4.3.1/docs/jinja2.txt
+-rw-r--r--   0 mat       (1000) mat       (1000)     4533 2021-05-01 11:21:12.000000 django_compressor-4.3.1/docs/make.bat
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2691 2023-01-22 12:40:08.000000 django_compressor-4.3.1/docs/quickstart.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2207 2021-12-12 18:04:27.000000 django_compressor-4.3.1/docs/reactjs.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     4084 2023-01-06 17:29:41.000000 django_compressor-4.3.1/docs/remote-storages.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     2591 2021-05-01 11:21:12.000000 django_compressor-4.3.1/docs/scenarios.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)    19657 2023-01-22 12:40:08.000000 django_compressor-4.3.1/docs/settings.txt
+-rw-rw-r--   0 mat       (1000) mat       (1000)     8682 2022-08-03 16:03:37.000000 django_compressor-4.3.1/docs/usage.txt
+drwxrwxr-x   0 mat       (1000) mat       (1000)        0 2023-01-22 12:43:34.202607 django_compressor-4.3.1/requirements/
+-rw-rw-r--   0 mat       (1000) mat       (1000)      207 2023-01-22 12:40:32.000000 django_compressor-4.3.1/requirements/tests.txt
+-rw-r--r--   0 mat       (1000) mat       (1000)       61 2023-01-22 12:43:34.202607 django_compressor-4.3.1/setup.cfg
+-rw-rw-r--   0 mat       (1000) mat       (1000)     5668 2023-01-22 12:40:08.000000 django_compressor-4.3.1/setup.py
+-rw-rw-r--   0 mat       (1000) mat       (1000)      477 2023-01-20 23:59:53.000000 django_compressor-4.3.1/tox.ini
```

### Comparing `django_compressor-4.3/AUTHORS` & `django_compressor-4.3.1/AUTHORS`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/LICENSE` & `django_compressor-4.3.1/LICENSE`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/PKG-INFO` & `django_compressor-4.3.1/django_compressor.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,14 +1,13 @@
 Metadata-Version: 2.1
-Name: django_compressor
-Version: 4.3
-Summary: Compresses linked and inline JavaScript or CSS into single cached files.
+Name: django-compressor
+Version: 4.3.1
+Summary: ('Compresses linked and inline JavaScript or CSS into single cached files.',)
 Home-page: https://django-compressor.readthedocs.io/en/latest/
-Author: Jannis Leidel
-Author-email: jannis@leidel.info
+Maintainer: Mathieu Pillard
 License: MIT
 Project-URL: Source, https://github.com/django-compressor/django-compressor
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Framework :: Django
 Classifier: Framework :: Django :: 3.2
 Classifier: Framework :: Django :: 4.0
 Classifier: Framework :: Django :: 4.1
```

#### html2text {}

 * *error from `html2text {}`:*

 * *File "/tmp/diffoscope_mg8n0s4d_/tmpwogvmhkr_TarContainer/0/5", line 107, column 0: CDATA terminal not found*

 * *File "/tmp/diffoscope_mg8n0s4d_/tmpwogvmhkr_TarContainer/0/5", line 107, column 0: CDATA terminal not found*

```diff
@@ -1,24 +1,24 @@
-Metadata-Version: 2.1 Name: django_compressor Version: 4.3 Summary: Compresses
-linked and inline JavaScript or CSS into single cached files. Home-page: https:
-//django-compressor.readthedocs.io/en/latest/ Author: Jannis Leidel Author-
-email: jannis@leidel.info License: MIT Project-URL: Source, https://github.com/
-django-compressor/django-compressor Classifier: Development Status :: 5 -
-Production/Stable Classifier: Framework :: Django Classifier: Framework ::
-Django :: 3.2 Classifier: Framework :: Django :: 4.0 Classifier: Framework ::
-Django :: 4.1 Classifier: Intended Audience :: Developers Classifier: License
-:: OSI Approved :: MIT License Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python Classifier: Programming Language ::
-Python :: 3 :: Only Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9 Classifier: Programming
-Language :: Python :: 3.10 Classifier: Programming Language :: Python :: 3.11
-Classifier: Topic :: Internet :: WWW/HTTP License-File: LICENSE License-File:
-AUTHORS Django Compressor ================= .. image:: https://codecov.io/
-github/django-compressor/django-compressor/coverage.svg?branch=develop :target:
-https://codecov.io/github/django-compressor/django-compressor?branch=develop ..
+Metadata-Version: 2.1 Name: django-compressor Version: 4.3.1 Summary:
+('Compresses linked and inline JavaScript or CSS into single cached files.',)
+Home-page: https://django-compressor.readthedocs.io/en/latest/ Maintainer:
+Mathieu Pillard License: MIT Project-URL: Source, https://github.com/django-
+compressor/django-compressor Classifier: Development Status :: 5 - Production/
+Stable Classifier: Framework :: Django Classifier: Framework :: Django :: 3.2
+Classifier: Framework :: Django :: 4.0 Classifier: Framework :: Django :: 4.1
+Classifier: Intended Audience :: Developers Classifier: License :: OSI Approved
+:: MIT License Classifier: Operating System :: OS Independent Classifier:
+Programming Language :: Python Classifier: Programming Language :: Python :: 3
+:: Only Classifier: Programming Language :: Python :: 3.8 Classifier:
+Programming Language :: Python :: 3.9 Classifier: Programming Language ::
+Python :: 3.10 Classifier: Programming Language :: Python :: 3.11 Classifier:
+Topic :: Internet :: WWW/HTTP License-File: LICENSE License-File: AUTHORS
+Django Compressor ================= .. image:: https://codecov.io/github/
+django-compressor/django-compressor/coverage.svg?branch=develop :target: https:
+//codecov.io/github/django-compressor/django-compressor?branch=develop ..
 image:: https://img.shields.io/pypi/v/django_compressor.svg :target: https://
 pypi.python.org/pypi/django_compressor .. image:: https://img.shields.io/
 github/actions/workflow/status/django-compressor/django-compressor/
 ci.yml?branch=develop :alt: Build Status :target: https://github.com/django-
 compressor/django-compressor/actions?query=workflow%3ACI Django Compressor
 processes, combines and minifies linked and inline Javascript or CSS in a
 Django template into cacheable static files. It supports compilers such as
```

### Comparing `django_compressor-4.3/README.rst` & `django_compressor-4.3.1/README.rst`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/base.py` & `django_compressor-4.3.1/compressor/base.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/cache.py` & `django_compressor-4.3.1/compressor/cache.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/conf.py` & `django_compressor-4.3.1/compressor/conf.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/contrib/jinja2ext.py` & `django_compressor-4.3.1/compressor/contrib/jinja2ext.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/contrib/sekizai.py` & `django_compressor-4.3.1/compressor/contrib/sekizai.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/css.py` & `django_compressor-4.3.1/compressor/css.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/exceptions.py` & `django_compressor-4.3.1/compressor/exceptions.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/filters/base.py` & `django_compressor-4.3.1/compressor/filters/base.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/filters/css_default.py` & `django_compressor-4.3.1/compressor/filters/css_default.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/filters/cssmin/__init__.py` & `django_compressor-4.3.1/compressor/filters/cssmin/__init__.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/filters/datauri.py` & `django_compressor-4.3.1/compressor/filters/datauri.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/filters/jsmin/__init__.py` & `django_compressor-4.3.1/compressor/filters/jsmin/__init__.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/filters/yuglify.py` & `django_compressor-4.3.1/compressor/filters/yuglify.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/filters/yui.py` & `django_compressor-4.3.1/compressor/filters/yui.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/js.py` & `django_compressor-4.3.1/compressor/js.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/management/commands/compress.py` & `django_compressor-4.3.1/compressor/management/commands/compress.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/management/commands/mtime_cache.py` & `django_compressor-4.3.1/compressor/management/commands/mtime_cache.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/offline/django.py` & `django_compressor-4.3.1/compressor/offline/django.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/offline/jinja2.py` & `django_compressor-4.3.1/compressor/offline/jinja2.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/parser/__init__.py` & `django_compressor-4.3.1/compressor/parser/__init__.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/parser/base.py` & `django_compressor-4.3.1/compressor/parser/base.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/parser/beautifulsoup.py` & `django_compressor-4.3.1/compressor/parser/beautifulsoup.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/parser/default_htmlparser.py` & `django_compressor-4.3.1/compressor/parser/default_htmlparser.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/parser/html5lib.py` & `django_compressor-4.3.1/compressor/parser/html5lib.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/parser/lxml.py` & `django_compressor-4.3.1/compressor/parser/lxml.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/storage.py` & `django_compressor-4.3.1/compressor/storage.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/templatetags/compress.py` & `django_compressor-4.3.1/compressor/templatetags/compress.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/test_settings.py` & `django_compressor-4.3.1/compressor/test_settings.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/precompiler.py` & `django_compressor-4.3.1/compressor/tests/precompiler.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/static/css/datauri.css` & `django_compressor-4.3.1/compressor/tests/static/css/datauri.css`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/static/img/add with spaces.png` & `django_compressor-4.3.1/compressor/tests/static/img/add with spaces.png`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/static/img/add.png` & `django_compressor-4.3.1/compressor/tests/static/img/add.png`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/static/img/python.png` & `django_compressor-4.3.1/compressor/tests/static/img/python.png`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/static/test.txt.br` & `django_compressor-4.3.1/compressor/tests/static/test.txt.br`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_base.py` & `django_compressor-4.3.1/compressor/tests/test_base.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_conf.py` & `django_compressor-4.3.1/compressor/tests/test_conf.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_filters.py` & `django_compressor-4.3.1/compressor/tests/test_filters.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_jinja2ext.py` & `django_compressor-4.3.1/compressor/tests/test_jinja2ext.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_mtime_cache.py` & `django_compressor-4.3.1/compressor/tests/test_mtime_cache.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_offline.py` & `django_compressor-4.3.1/compressor/tests/test_offline.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_parsers.py` & `django_compressor-4.3.1/compressor/tests/test_parsers.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_sekizai.py` & `django_compressor-4.3.1/compressor/tests/test_sekizai.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_signals.py` & `django_compressor-4.3.1/compressor/tests/test_signals.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_storages.py` & `django_compressor-4.3.1/compressor/tests/test_storages.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_templates/test_complex/test_compressor_offline.html` & `django_compressor-4.3.1/compressor/tests/test_templates/test_complex/test_compressor_offline.html`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_templates_jinja2/test_complex/test_compressor_offline.html` & `django_compressor-4.3.1/compressor/tests/test_templates_jinja2/test_complex/test_compressor_offline.html`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_templatetags.py` & `django_compressor-4.3.1/compressor/tests/test_templatetags.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/tests/test_utils.py` & `django_compressor-4.3.1/compressor/tests/test_utils.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/utils/__init__.py` & `django_compressor-4.3.1/compressor/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/compressor/utils/staticfiles.py` & `django_compressor-4.3.1/compressor/utils/staticfiles.py`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/django_compressor.egg-info/PKG-INFO` & `django_compressor-4.3.1/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,14 +1,13 @@
 Metadata-Version: 2.1
-Name: django-compressor
-Version: 4.3
-Summary: Compresses linked and inline JavaScript or CSS into single cached files.
+Name: django_compressor
+Version: 4.3.1
+Summary: ('Compresses linked and inline JavaScript or CSS into single cached files.',)
 Home-page: https://django-compressor.readthedocs.io/en/latest/
-Author: Jannis Leidel
-Author-email: jannis@leidel.info
+Maintainer: Mathieu Pillard
 License: MIT
 Project-URL: Source, https://github.com/django-compressor/django-compressor
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Framework :: Django
 Classifier: Framework :: Django :: 3.2
 Classifier: Framework :: Django :: 4.0
 Classifier: Framework :: Django :: 4.1
```

#### html2text {}

 * *error from `html2text {}`:*

 * *File "/tmp/diffoscope_mg8n0s4d_/tmpwogvmhkr_TarContainer/0/323", line 107, column 0: CDATA terminal not found*

 * *File "/tmp/diffoscope_mg8n0s4d_/tmpwogvmhkr_TarContainer/0/323", line 107, column 0: CDATA terminal not found*

```diff
@@ -1,24 +1,24 @@
-Metadata-Version: 2.1 Name: django-compressor Version: 4.3 Summary: Compresses
-linked and inline JavaScript or CSS into single cached files. Home-page: https:
-//django-compressor.readthedocs.io/en/latest/ Author: Jannis Leidel Author-
-email: jannis@leidel.info License: MIT Project-URL: Source, https://github.com/
-django-compressor/django-compressor Classifier: Development Status :: 5 -
-Production/Stable Classifier: Framework :: Django Classifier: Framework ::
-Django :: 3.2 Classifier: Framework :: Django :: 4.0 Classifier: Framework ::
-Django :: 4.1 Classifier: Intended Audience :: Developers Classifier: License
-:: OSI Approved :: MIT License Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python Classifier: Programming Language ::
-Python :: 3 :: Only Classifier: Programming Language :: Python :: 3.8
-Classifier: Programming Language :: Python :: 3.9 Classifier: Programming
-Language :: Python :: 3.10 Classifier: Programming Language :: Python :: 3.11
-Classifier: Topic :: Internet :: WWW/HTTP License-File: LICENSE License-File:
-AUTHORS Django Compressor ================= .. image:: https://codecov.io/
-github/django-compressor/django-compressor/coverage.svg?branch=develop :target:
-https://codecov.io/github/django-compressor/django-compressor?branch=develop ..
+Metadata-Version: 2.1 Name: django_compressor Version: 4.3.1 Summary:
+('Compresses linked and inline JavaScript or CSS into single cached files.',)
+Home-page: https://django-compressor.readthedocs.io/en/latest/ Maintainer:
+Mathieu Pillard License: MIT Project-URL: Source, https://github.com/django-
+compressor/django-compressor Classifier: Development Status :: 5 - Production/
+Stable Classifier: Framework :: Django Classifier: Framework :: Django :: 3.2
+Classifier: Framework :: Django :: 4.0 Classifier: Framework :: Django :: 4.1
+Classifier: Intended Audience :: Developers Classifier: License :: OSI Approved
+:: MIT License Classifier: Operating System :: OS Independent Classifier:
+Programming Language :: Python Classifier: Programming Language :: Python :: 3
+:: Only Classifier: Programming Language :: Python :: 3.8 Classifier:
+Programming Language :: Python :: 3.9 Classifier: Programming Language ::
+Python :: 3.10 Classifier: Programming Language :: Python :: 3.11 Classifier:
+Topic :: Internet :: WWW/HTTP License-File: LICENSE License-File: AUTHORS
+Django Compressor ================= .. image:: https://codecov.io/github/
+django-compressor/django-compressor/coverage.svg?branch=develop :target: https:
+//codecov.io/github/django-compressor/django-compressor?branch=develop ..
 image:: https://img.shields.io/pypi/v/django_compressor.svg :target: https://
 pypi.python.org/pypi/django_compressor .. image:: https://img.shields.io/
 github/actions/workflow/status/django-compressor/django-compressor/
 ci.yml?branch=develop :alt: Build Status :target: https://github.com/django-
 compressor/django-compressor/actions?query=workflow%3ACI Django Compressor
 processes, combines and minifies linked and inline Javascript or CSS in a
 Django template into cacheable static files. It supports compilers such as
```

### Comparing `django_compressor-4.3/django_compressor.egg-info/SOURCES.txt` & `django_compressor-4.3.1/django_compressor.egg-info/SOURCES.txt`

 * *Files 25% similar despite different names*

```diff
@@ -265,8 +265,64 @@
 docs/make.bat
 docs/quickstart.txt
 docs/reactjs.txt
 docs/remote-storages.txt
 docs/scenarios.txt
 docs/settings.txt
 docs/usage.txt
+docs/_build/doctrees/behind-the-scenes.doctree
+docs/_build/doctrees/changelog.doctree
+docs/_build/doctrees/contributing.doctree
+docs/_build/doctrees/django-sekizai.doctree
+docs/_build/doctrees/environment.pickle
+docs/_build/doctrees/index.doctree
+docs/_build/doctrees/jinja2.doctree
+docs/_build/doctrees/quickstart.doctree
+docs/_build/doctrees/reactjs.doctree
+docs/_build/doctrees/remote-storages.doctree
+docs/_build/doctrees/scenarios.doctree
+docs/_build/doctrees/settings.doctree
+docs/_build/doctrees/usage.doctree
+docs/_build/html/.buildinfo
+docs/_build/html/behind-the-scenes.html
+docs/_build/html/changelog.html
+docs/_build/html/contributing.html
+docs/_build/html/django-sekizai.html
+docs/_build/html/genindex.html
+docs/_build/html/index.html
+docs/_build/html/jinja2.html
+docs/_build/html/objects.inv
+docs/_build/html/quickstart.html
+docs/_build/html/reactjs.html
+docs/_build/html/remote-storages.html
+docs/_build/html/scenarios.html
+docs/_build/html/search.html
+docs/_build/html/searchindex.js
+docs/_build/html/settings.html
+docs/_build/html/usage.html
+docs/_build/html/_sources/behind-the-scenes.txt
+docs/_build/html/_sources/changelog.txt
+docs/_build/html/_sources/contributing.txt
+docs/_build/html/_sources/django-sekizai.txt
+docs/_build/html/_sources/index.txt
+docs/_build/html/_sources/jinja2.txt
+docs/_build/html/_sources/quickstart.txt
+docs/_build/html/_sources/reactjs.txt
+docs/_build/html/_sources/remote-storages.txt
+docs/_build/html/_sources/scenarios.txt
+docs/_build/html/_sources/settings.txt
+docs/_build/html/_sources/usage.txt
+docs/_build/html/_static/alabaster.css
+docs/_build/html/_static/basic.css
+docs/_build/html/_static/custom.css
+docs/_build/html/_static/doctools.js
+docs/_build/html/_static/documentation_options.js
+docs/_build/html/_static/file.png
+docs/_build/html/_static/forkme_right_darkblue_121621.png
+docs/_build/html/_static/jquery.js
+docs/_build/html/_static/language_data.js
+docs/_build/html/_static/minus.png
+docs/_build/html/_static/plus.png
+docs/_build/html/_static/pygments.css
+docs/_build/html/_static/searchtools.js
+docs/_build/html/_static/underscore.js
 requirements/tests.txt
```

### Comparing `django_compressor-4.3/docs/Makefile` & `django_compressor-4.3.1/docs/Makefile`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/docs/behind-the-scenes.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/behind-the-scenes.txt`

 * *Files 0% similar despite different names*

```diff
@@ -5,15 +5,15 @@
 
 This document assumes you already have an up and running instance of
 Django Compressor, and that you understand how to use it in your templates.
 The goal is to explain what the main template tag, {% compress %}, does
 behind the scenes, to help you debug performance problems for instance.
 
 Offline compression
--------------
+-------------------
 
 If offline compression is activated, the {% compress %} tag will try to
 retrieve the compressed version for its nodelist from the offline manifest
 cache. It doesn't parse, doesn't check the modified times of the files, doesn't
 even know which files are concerned actually, since it doesn't look inside the
 nodelist of the template block enclosed by the ``compress`` template tag.
 The offline cache manifest is just a json file, stored on disk inside the
```

### Comparing `django_compressor-4.3/docs/changelog.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/changelog.txt`

 * *Files 7% similar despite different names*

```diff
@@ -1,49 +1,57 @@
 Changelog
 =========
 
+v4.3.1 (2023-01-22)
+-------------------
+
+`Full list of changes from v4.3 <https://github.com/django-compressor/django-compressor/compare/4.3...4.3.1>`_
+
+- Documentation fixes only
+
+
 v4.3 (2023-01-06)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/4.2...4.3>`_
+`Full list of changes from v4.2 <https://github.com/django-compressor/django-compressor/compare/4.2...4.3>`_
 
 - Officially support Python 3.11
 
 v4.2 (2023-01-06)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/4.1...4.2>`_
+`Full list of changes from v4.1 <https://github.com/django-compressor/django-compressor/compare/4.1...4.2>`_
 
 - Drop Python 3.6 and 3.7 support
 - Drop Django 2.2 and 3.1 support
 - Drop SlimItFilter
 - Update the `CachedS3Boto3Storage` example storage subclass in "Remote Storages"
   to work properly after the v4.0 change to how duplicate file names are handled
   by `CompressorFileStorage`
 - Update rsmin and jsmin versions
   
 
 v4.1 (2022-08-03)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/4.0...4.1>`_
+`Full list of changes from v4.0 <https://github.com/django-compressor/django-compressor/compare/4.0...4.1>`_
 
 - Add Django 4.1 compatibility
 
 - New setting ``COMPRESS_OFFLINE_MANIFEST_STORAGE`` to customize the offline manifest's file storage (#1112)
 
   With this change the function ``compressor.cache.get_offline_manifest_filename()`` has been removed.
   You can now use the new file storage ``compressor.storage.default_offline_manifest_storage`` to access the
   location of the manifest.
 
 
 v4.0 (2022-03-23)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/3.1...4.0>`_
+`Full list of changes from v3.1 <https://github.com/django-compressor/django-compressor/compare/3.1...4.0>`_
 
 - Fix intermittent No such file or directory errors by changing strategy to
   deal with duplicate filenames in CompressorFileStorage
   
   Note: if your project has a custom storage backend following the example of 
   `CachedS3Boto3Storage` from the "Remote Storages" documentation, it will need
   to be updated to call `save` instead of `_save` to work properly after this
@@ -51,23 +59,23 @@
   
 - Deprecate SlimItFilter, stop testing it with Python 3.7 or higher
 
 
 v3.1 (2021-12-18)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/3.0...3.1>`_
+`Full list of changes from v3.0 <https://github.com/django-compressor/django-compressor/compare/3.0...3.1>`_
 
 - Fix error with verbose offline compression when COMPRESS_OFFLINE_CONTEXT is a generator
 
 
 v3.0 (2021-12-12)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/2.4.1...3.0>`_
+`Full list of changes from v2.4.1 <https://github.com/django-compressor/django-compressor/compare/2.4.1...3.0>`_
 
 - Officially support Python 3.9 and 3.10 as well as Django 3.1, 3.2 and 4.0
 - Drop support for Django 1.11, 2.1 and 3.0
 - Drop support for Python 2.x and 3.4
 - Fix compatibility with Jinja 3.x
 - Require django-sekizai 2.0 for django-sekizai extension
 - Make template compression in compress command threaded to improve performance
@@ -77,36 +85,36 @@
 - Add ability to pass a logger to various classes & methods
 - Removed deprecated ``COMPRESS_JS_FILTERS`` and ``COMPRESS_CSS_FILTERS`` settings
 - Fix offline compression race condition, which could result in incomplete manifest
 
 v2.4.1 (2021-04-17)
 -------------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/2.4...2.4.1>`_
+`Full list of changes from v2.4 <https://github.com/django-compressor/django-compressor/compare/2.4...2.4.1>`_
 
 - Raise proper ``DeprecationWarning`` for ``COMPRESS_JS_FILTERS`` and ``COMPRESS_CSS_FILTERS``
 
 
 v2.4 (2019-12-31)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/2.3...2.4>`_
+`Full list of changes from v2.3 <https://github.com/django-compressor/django-compressor/compare/2.3...2.4>`_
 
 - Add support for Django 3.0 (#950, #967)
 - Officially support Python 3.8 (#967)
 - Add better support for JS strict mode and validation (#952)
 - Add support for rel=preload (#951)
 - Add support for Calmjs (#957)
 
 Note: in 2.3, a new setting ``COMPRESS_FILTERS`` has been introduced that combines the existing ``COMPRESS_CSS_FILTERS`` and ``COMPRESS_JS_FILTERS``. The latter are now deprecated. See `the docs <https://django-compressor.readthedocs.io/en/stable/settings/#django.conf.settings.COMPRESS_FILTERS>`_ on how to use the new setting, the conversion is straightforward.
 
 v2.3 (2019-05-31)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/2.2...2.3>`_
+`Full list of changes from v2.2 <https://github.com/django-compressor/django-compressor/compare/2.2...2.3>`_
 
 - Drop support for Django 1.8, 1.9 and 1.10
 - Add support for Django 2.1 and 2.2, as well as Python 3.7
 - Update all dependencies. This required minor code changes, you might need to update some optional dependencies if you use any
 - Allow the mixed use of JS/CSS in Sekizai's templatetags ``{% addtoblock "js" %}`` and ``{% addtoblock "css" %}`` (#891)
 - Allow the implementation of new types other than css and js. (#900)
 - Update jinja2 extension to behave similar to the django tag (#899)
@@ -115,15 +123,15 @@
 - Improve compress command memory usage (#870)
 - Ensure generated file always contains a base name (#775)
 - Add BrotliCompressorFileStorage (#867)
 
 v2.2 (2017-08-16)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/2.1.1...2.2>`_
+`Full list of changes from v2.1.1 <https://github.com/django-compressor/django-compressor/compare/2.1.1...2.2>`_
 
 - Switch from MD5 to SHA256 for hashes generation.
 
 - Add Django 1.11 compatibility
 
 - Various compatibility fixes for Python 3.6 and Django 1.8
 
@@ -134,21 +142,23 @@
 - Add new CssRelativeFilter which works like CssAbsoluteFilter but outputs relative URLs.
 
 - Fix URL CssAbsoluteFilter URL detection
 
 v2.1.1 (2017-02-02)
 -------------------
 
+`Full list of changes from v2.1 <https://github.com/django-compressor/django-compressor/compare/2.1...2.1.1>`_
+
 - Fix to file permissions issue with packaging.
 
 
 v2.1 (2016-08-09)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/2.0...2.1>`_
+`Full list of changes from v2.0 <https://github.com/django-compressor/django-compressor/compare/2.0...2.1>`_
 
 - Add Django 1.10 compatibility
 
 - Add support for inheritance using a variable in offline compression
 
 - Fix recursion error with offline compression when extending templates with the same name
 
@@ -156,15 +166,15 @@
 
 - Fix CssAbsoluteFilter changing double quotes to single quotes, breaking SVG
 
 
 v2.0 (2016-01-07)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/1.6...2.0>`_
+`Full list of changes from v1.6 <https://github.com/django-compressor/django-compressor/compare/1.6...2.0>`_
 
 - Add Django 1.9 compatibility
 
 - Remove official support for Django 1.4 and 1.7
 
 - Add official support for Python 3.5
 
@@ -182,15 +192,15 @@
 
 - Replace cssmin by csscompressor (cssmin is still available for backwards-compatibility but points to rcssmin)
 
 
 v1.6 (2015-11-19)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/1.5...1.6>`_
+`Full list of changes from v1.5 <https://github.com/django-compressor/django-compressor/compare/1.5...1.6>`_
 
 - Upgrade rcssmin and rjsmin
 
 - Apply CssAbsoluteFilter to precompiled css even when compression is disabled
 
 - Add optional caching to CompilerFilter to avoid re-compiling unchanged files
 
@@ -204,15 +214,15 @@
 
 - Removed some silent exception catching in compress command
 
 
 v1.5 (2015-03-27)
 -----------------
 
-`Full Changelog <https://github.com/django-compressor/django-compressor/compare/1.4...1.5>`_
+`Full list of changes from v1.4 <https://github.com/django-compressor/django-compressor/compare/1.4...1.5>`_
 
 - Fix compress command and run automated tests for Django 1.8
 
 - Fix Django 1.8 warnings
 
 - Handle TypeError from import_module
 
@@ -403,17 +413,16 @@
 
 v1.1
 ----
 
 - Made offline compression completely independent from cache (by writing a
   manifest.json file).
 
-  You can now easily run the :ref:`compress <pre-compression>` management
-  command locally and transfer the :attr:`~django.conf.settings.COMPRESS_ROOT`
-  dir to your server.
+  You can now easily run the ``compress`` management command locally and
+  transfer the :attr:`~django.conf.settings.COMPRESS_ROOT` dir to your server.
 
 - Updated installation instructions to properly mention all dependencies,
   even those internally used.
 
 - Fixed a bug introduced in 1.0 which would prevent the proper deactivation
   of the compression in production.
 
@@ -591,16 +600,15 @@
 - New staticfiles support. With the introduction of the staticfiles app
   to Django 1.3, compressor officially supports finding the files to
   compress using the app's finder API. Have a look at the documentation
   about :ref:`remote storages <remote_storages>` in case you want to use
   those together with compressor.
 
 - New ``compress`` management command which allows pre-running of what the
-  compress template tag does. See the
-  :ref:`pre-compression <pre-compression>` docs for more information.
+  compress template tag does.
 
 - Various performance improvements by better caching and mtime cheking.
 
 - Deprecated ``COMPRESS_LESSC_BINARY`` setting because it's now
   superseded by the :attr:`~django.conf.settings.COMPRESS_PRECOMPILERS`
   setting. Just make sure to use the correct mimetype when linking to less
   files or adding inline code and add the following to your settings::
```

### Comparing `django_compressor-4.3/docs/conf.py` & `django_compressor-4.3.1/docs/conf.py`

 * *Files 7% similar despite different names*

```diff
@@ -16,205 +16,216 @@
 # add these directories to sys.path here. If the directory is relative to the
 # documentation root, use os.path.abspath to make it absolute, like shown here.
 sys.path.insert(0, os.path.abspath('..'))
 
 # -- General configuration -----------------------------------------------------
 
 # If your documentation needs a minimal Sphinx version, state it here.
-#needs_sphinx = '1.0'
+# needs_sphinx = '1.0'
 
 # Add any Sphinx extension module names here, as strings. They can be extensions
 # coming with Sphinx (named 'sphinx.ext.*') or your custom ones.
 # extensions = ['sphinx.ext.autodoc', 'sphinx.ext.coverage']
 
 # Add any paths that contain templates here, relative to this directory.
 templates_path = ['_templates']
 
 # The suffix of source filenames.
 source_suffix = '.txt'
 
 # The encoding of source files.
-#source_encoding = 'utf-8-sig'
+# source_encoding = 'utf-8-sig'
 
 # The master toctree document.
 master_doc = 'index'
 
 # General information about the project.
 project = 'Django Compressor'
-copyright = '2014, Django Compressor authors'
+copyright = '2023, Django Compressor authors'
 
 # The version info for the project you're documenting, acts as replacement for
 # |version| and |release|, also used in various other places throughout the
 # built documents.
 #
 try:
     from compressor import __version__
+
     # The short X.Y version.
     version = '.'.join(__version__.split('.')[:2])
     # The full version, including alpha/beta/rc tags.
     release = __version__
 except ImportError:
     version = release = 'dev'
 
 # The language for content autogenerated by Sphinx. Refer to documentation
 # for a list of supported languages.
-#language = None
+# language = None
 
 # There are two options for replacing |today|: either, you set today to some
 # non-false value, then it is used:
-#today = ''
+# today = ''
 # Else, today_fmt is used as the format for a strftime call.
-#today_fmt = '%B %d, %Y'
+# today_fmt = '%B %d, %Y'
 
 # List of patterns, relative to source directory, that match files and
 # directories to ignore when looking for source files.
 exclude_patterns = ['_build']
 
 # The reST default role (used for this markup: `text`) to use for all documents.
-#default_role = None
+# default_role = None
 
 # If true, '()' will be appended to :func: etc. cross-reference text.
-#add_function_parentheses = True
+# add_function_parentheses = True
 
 # If true, the current module name will be prepended to all description
 # unit titles (such as .. function::).
-#add_module_names = True
+# add_module_names = True
 
 # If true, sectionauthor and moduleauthor directives will be shown in the
 # output. They are ignored by default.
-#show_authors = False
+# show_authors = False
 
 # The name of the Pygments (syntax highlighting) style to use.
 pygments_style = 'murphy'
 
 # A list of ignored prefixes for module index sorting.
-#modindex_common_prefix = []
+# modindex_common_prefix = []
 
 
 # -- Options for HTML output ---------------------------------------------------
 
 # The theme to use for HTML and HTML Help pages.  See the documentation for
 # a list of builtin themes.
 # html_theme = 'default'
 RTD_NEW_THEME = True
 
 # Theme options are theme-specific and customize the look and feel of a theme
 # further.  For a list of options available for each theme, see the
 # documentation.
-#html_theme_options = {}
+# html_theme_options = {}
 
 # Add any paths that contain custom themes here, relative to this directory.
 # html_theme_path = ['_theme']
 
 # The name for this set of Sphinx documents.  If None, it defaults to
 # "<project> v<release> documentation".
-#html_title = None
+# html_title = None
 
 # A shorter title for the navigation bar.  Default is the same as html_title.
-#html_short_title = None
+# html_short_title = None
 
 # The name of an image file (relative to this directory) to place at the top
 # of the sidebar.
-#html_logo = None
+# html_logo = None
 
 # The name of an image file (within the static path) to use as favicon of the
 # docs.  This file should be a Windows icon file (.ico) being 16x16 or 32x32
 # pixels large.
-#html_favicon = None
+# html_favicon = None
 
 # Add any paths that contain custom static files (such as style sheets) here,
 # relative to this directory. They are copied after the builtin static files,
 # so a file named "default.css" will overwrite the builtin "default.css".
 # html_static_path = ['_static']
 
 # If not '', a 'Last updated on:' timestamp is inserted at every page bottom,
 # using the given strftime format.
-#html_last_updated_fmt = '%b %d, %Y'
+# html_last_updated_fmt = '%b %d, %Y'
 
 # If true, SmartyPants will be used to convert quotes and dashes to
 # typographically correct entities.
-#html_use_smartypants = True
+# html_use_smartypants = True
 
 # Custom sidebar templates, maps document names to template names.
-#html_sidebars = {}
+# html_sidebars = {}
 
 # Additional templates that should be rendered to pages, maps page names to
 # template names.
-#html_additional_pages = {}
+# html_additional_pages = {}
 
 # If false, no module index is generated.
-#html_domain_indices = True
+# html_domain_indices = True
 
 # If false, no index is generated.
-#html_use_index = True
+# html_use_index = True
 
 # If true, the index is split into individual pages for each letter.
-#html_split_index = False
+# html_split_index = False
 
 # If true, links to the reST sources are added to the pages.
-#html_show_sourcelink = True
+# html_show_sourcelink = True
 
 # If true, "Created using Sphinx" is shown in the HTML footer. Default is True.
-#html_show_sphinx = True
+# html_show_sphinx = True
 
 # If true, "(C) Copyright ..." is shown in the HTML footer. Default is True.
-#html_show_copyright = True
+# html_show_copyright = True
 
 # If true, an OpenSearch description file will be output, and all pages will
 # contain a <link> tag referring to it.  The value of this option must be the
 # base URL from which the finished HTML is served.
-#html_use_opensearch = ''
+# html_use_opensearch = ''
 
 # This is the file name suffix for HTML files (e.g. ".xhtml").
-#html_file_suffix = None
+# html_file_suffix = None
 
 # Output file base name for HTML help builder.
 htmlhelp_basename = 'django-compressordoc'
 
 
 # -- Options for LaTeX output --------------------------------------------------
 
 # The paper size ('letter' or 'a4').
-#latex_paper_size = 'letter'
+# latex_paper_size = 'letter'
 
 # The font size ('10pt', '11pt' or '12pt').
-#latex_font_size = '10pt'
+# latex_font_size = '10pt'
 
 # Grouping the document tree into LaTeX files. List of tuples
 # (source start file, target name, title, author, documentclass [howto/manual]).
 latex_documents = [
-    ('index', 'django-compressor.tex', 'Django Compressor Documentation',
-    'Django Compressor authors', 'manual'),
+    (
+        'index',
+        'django-compressor.tex',
+        'Django Compressor Documentation',
+        'Django Compressor authors',
+        'manual',
+    ),
 ]
 
 # The name of an image file (relative to this directory) to place at the top of
 # the title page.
-#latex_logo = None
+# latex_logo = None
 
 # For "manual" documents, if this is true, then toplevel headings are parts,
 # not chapters.
-#latex_use_parts = False
+# latex_use_parts = False
 
 # If true, show page references after internal links.
-#latex_show_pagerefs = False
+# latex_show_pagerefs = False
 
 # If true, show URL addresses after external links.
-#latex_show_urls = False
+# latex_show_urls = False
 
 # Additional stuff for the LaTeX preamble.
-#latex_preamble = ''
+# latex_preamble = ''
 
 # Documents to append as an appendix to all manuals.
-#latex_appendices = []
+# latex_appendices = []
 
 # If false, no module index is generated.
-#latex_domain_indices = True
+# latex_domain_indices = True
 
 
 # -- Options for manual page output --------------------------------------------
 
 # One entry per manual page. List of tuples
 # (source start file, name, description, authors, manual section).
 man_pages = [
-    ('index', 'django-compressor', 'Django Compressor Documentation',
-     ['Django Compressor authors'], 1)
+    (
+        'index',
+        'django-compressor',
+        'Django Compressor Documentation',
+        ['Django Compressor authors'],
+        1,
+    )
 ]
```

### Comparing `django_compressor-4.3/docs/contributing.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/contributing.txt`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/docs/django-sekizai.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/django-sekizai.txt`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/docs/index.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/index.txt`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/docs/jinja2.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/jinja2.txt`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/docs/make.bat` & `django_compressor-4.3.1/docs/make.bat`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/docs/quickstart.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/quickstart.txt`

 * *Files 0% similar despite different names*

```diff
@@ -36,15 +36,15 @@
 
 .. _staticfiles: http://docs.djangoproject.com/en/dev/ref/contrib/staticfiles/
 .. _django-staticfiles: http://pypi.python.org/pypi/django-staticfiles
 
 .. _dependencies:
 
 Optional Dependencies
-------------
+---------------------
 
 - BeautifulSoup_
 
   For the :attr:`parser <django.conf.settings.COMPRESS_PARSER>`
   ``compressor.parser.BeautifulSoupParser`` and
   ``compressor.parser.LxmlParser``::
```

### Comparing `django_compressor-4.3/docs/reactjs.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/reactjs.txt`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/docs/remote-storages.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/remote-storages.txt`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/docs/scenarios.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/scenarios.txt`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/docs/settings.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/settings.txt`

 * *Files 2% similar despite different names*

```diff
@@ -222,38 +222,43 @@
            The arguments passed to the compiler.
 
       - ``compressor.filters.yui.YUIJSFilter``
 
         A filter that passes the JavaScript code to the `YUI compressor`_.
 
         .. attribute:: COMPRESS_YUI_BINARY
+          :noindex:
 
            The YUI compressor filesystem path.
 
         .. attribute:: COMPRESS_YUI_JS_ARGUMENTS
+          :noindex:
 
            The arguments passed to the compressor.
 
       - ``compressor.filters.yuglify.YUglifyJSFilter``
 
         A filter that passes the JavaScript code to the `yUglify compressor`_.
 
         .. attribute:: COMPRESS_YUGLIFY_BINARY
+          :noindex:
 
            The yUglify compressor filesystem path.
 
         .. attribute:: COMPRESS_YUGLIFY_JS_ARGUMENTS
+          :noindex:
 
            The arguments passed to the compressor.
 
       - ``compressor.filters.template.TemplateFilter``
 
         A filter that renders the JavaScript code with Django templating system.
 
         .. attribute:: COMPRESS_TEMPLATE_FILTER_CONTEXT
+          :noindex:
 
            The context to render your JavaScript code with.
 
       .. _rJSmin: http://opensource.perlig.de/rjsmin/
       .. _`Google Closure compiler`: http://code.google.com/closure/compiler/
       .. _`YUI compressor`: http://developer.yahoo.com/yui/compressor/
       .. _`yUglify compressor`: https://github.com/yui/yuglify
```

#### html2text {}

```diff
@@ -81,42 +81,43 @@
 the jsmin implementation `Calmjs`_ to compress JavaScript code. -
 ``compressor.filters.closure.ClosureCompilerFilter`` A filter that uses `Google
 Closure compiler`_. .. attribute:: COMPRESS_CLOSURE_COMPILER_BINARY The Closure
 compiler filesystem path. Make sure to also prepend this setting with ``java -
 jar`` if you use that kind of distribution. .. attribute::
 COMPRESS_CLOSURE_COMPILER_ARGUMENTS The arguments passed to the compiler. -
 ``compressor.filters.yui.YUIJSFilter`` A filter that passes the JavaScript code
-to the `YUI compressor`_. .. attribute:: COMPRESS_YUI_BINARY The YUI compressor
-filesystem path. .. attribute:: COMPRESS_YUI_JS_ARGUMENTS The arguments passed
-to the compressor. - ``compressor.filters.yuglify.YUglifyJSFilter`` A filter
-that passes the JavaScript code to the `yUglify compressor`_. .. attribute::
-COMPRESS_YUGLIFY_BINARY The yUglify compressor filesystem path. .. attribute::
-COMPRESS_YUGLIFY_JS_ARGUMENTS The arguments passed to the compressor. -
-``compressor.filters.template.TemplateFilter`` A filter that renders the
-JavaScript code with Django templating system. .. attribute::
-COMPRESS_TEMPLATE_FILTER_CONTEXT The context to render your JavaScript code
-with. .. _rJSmin: http://opensource.perlig.de/rjsmin/ .. _`Google Closure
-compiler`: http://code.google.com/closure/compiler/ .. _`YUI compressor`: http:
-//developer.yahoo.com/yui/compressor/ .. _`yUglify compressor`: https://
-github.com/yui/yuglify .. _`Slim It`: https://github.com/rspivak/slimit ..
-_`Calmjs`: https://github.com/calmjs/calmjs.parse .. attribute::
-COMPRESS_PRECOMPILERS :Default: ``()`` An iterable of two-tuples whose first
-item is the mimetype of the files or hunks you want to compile with the command
-or filter specified as the second item: #. mimetype The mimetype of the file or
-inline code that should be compiled. #. command_or_filter The command to call
-on each of the files. Modern Python string formatting will be provided for the
-two placeholders ``{infile}`` and ``{outfile}`` whose existence in the command
-string also triggers the actual creation of those temporary files. If not given
-in the command string, Django Compressor will use ``stdin`` and ``stdout``
-respectively instead. Alternatively, you may provide the fully qualified class
-name of a filter you wish to use as a precompiler. Example::
-COMPRESS_PRECOMPILERS = ( ('text/coffeescript', 'coffee --compile --stdio'),
-('text/less', 'lessc {infile} {outfile}'), ('text/x-sass', 'sass {infile}
-{outfile}'), ('text/x-scss', 'sass --scss {infile} {outfile}'), ('text/stylus',
-'stylus < {infile} > {outfile}'), ('text/foobar',
+to the `YUI compressor`_. .. attribute:: COMPRESS_YUI_BINARY :noindex: The YUI
+compressor filesystem path. .. attribute:: COMPRESS_YUI_JS_ARGUMENTS :noindex:
+The arguments passed to the compressor. -
+``compressor.filters.yuglify.YUglifyJSFilter`` A filter that passes the
+JavaScript code to the `yUglify compressor`_. .. attribute::
+COMPRESS_YUGLIFY_BINARY :noindex: The yUglify compressor filesystem path. ..
+attribute:: COMPRESS_YUGLIFY_JS_ARGUMENTS :noindex: The arguments passed to the
+compressor. - ``compressor.filters.template.TemplateFilter`` A filter that
+renders the JavaScript code with Django templating system. .. attribute::
+COMPRESS_TEMPLATE_FILTER_CONTEXT :noindex: The context to render your
+JavaScript code with. .. _rJSmin: http://opensource.perlig.de/rjsmin/ ..
+_`Google Closure compiler`: http://code.google.com/closure/compiler/ .. _`YUI
+compressor`: http://developer.yahoo.com/yui/compressor/ .. _`yUglify
+compressor`: https://github.com/yui/yuglify .. _`Slim It`: https://github.com/
+rspivak/slimit .. _`Calmjs`: https://github.com/calmjs/calmjs.parse ..
+attribute:: COMPRESS_PRECOMPILERS :Default: ``()`` An iterable of two-tuples
+whose first item is the mimetype of the files or hunks you want to compile with
+the command or filter specified as the second item: #. mimetype The mimetype of
+the file or inline code that should be compiled. #. command_or_filter The
+command to call on each of the files. Modern Python string formatting will be
+provided for the two placeholders ``{infile}`` and ``{outfile}`` whose
+existence in the command string also triggers the actual creation of those
+temporary files. If not given in the command string, Django Compressor will use
+``stdin`` and ``stdout`` respectively instead. Alternatively, you may provide
+the fully qualified class name of a filter you wish to use as a precompiler.
+Example:: COMPRESS_PRECOMPILERS = ( ('text/coffeescript', 'coffee --compile --
+stdio'), ('text/less', 'lessc {infile} {outfile}'), ('text/x-sass', 'sass
+{infile} {outfile}'), ('text/x-scss', 'sass --scss {infile} {outfile}'),
+('text/stylus', 'stylus < {infile} > {outfile}'), ('text/foobar',
 'path.to.MyPrecompilerFilter'), ) .. note:: Depending on the implementation,
 some precompilers might not support outputting to something else than
 ``stdout``, so you'll need to omit the ``{outfile}`` parameter when working
 with those. For instance, if you are using the Ruby version of lessc, you'll
 need to set up the precompiler like this:: ('text/less', 'lessc {infile}'),
 With that setting (and CoffeeScript_ installed), you could add the following
 code to your templates: .. code-block:: django {% load compress %} {% compress
```

### Comparing `django_compressor-4.3/docs/usage.txt` & `django_compressor-4.3.1/docs/_build/html/_sources/usage.txt`

 * *Files identical despite different names*

### Comparing `django_compressor-4.3/setup.py` & `django_compressor-4.3.1/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -132,18 +132,19 @@
     name="django_compressor",
     version=find_version("compressor", "__init__.py"),
     url="https://django-compressor.readthedocs.io/en/latest/",
     project_urls={
         "Source": "https://github.com/django-compressor/django-compressor",
     },
     license="MIT",
-    description="Compresses linked and inline JavaScript or CSS into single cached files.",
+    description=(
+        "Compresses linked and inline JavaScript or CSS into single cached files.",
+    ),
     long_description=read("README.rst"),
-    author="Jannis Leidel",
-    author_email="jannis@leidel.info",
+    maintainer="Mathieu Pillard",
     packages=find_packages(),
     package_data=find_package_data(),
     classifiers=[
         "Development Status :: 5 - Production/Stable",
         "Framework :: Django",
         "Framework :: Django :: 3.2",
         "Framework :: Django :: 4.0",
```


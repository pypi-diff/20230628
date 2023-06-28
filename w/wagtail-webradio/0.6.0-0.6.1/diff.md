# Comparing `tmp/wagtail-webradio-0.6.0.tar.gz` & `tmp/wagtail-webradio-0.6.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "wagtail-webradio-0.6.0.tar", last modified: Wed Jun 21 14:03:00 2023, max compression
+gzip compressed data, was "wagtail-webradio-0.6.1.tar", last modified: Wed Jun 28 08:59:56 2023, max compression
```

## Comparing `wagtail-webradio-0.6.0.tar` & `wagtail-webradio-0.6.1.tar`

### file list

```diff
@@ -1,139 +1,139 @@
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.855100 wagtail-webradio-0.6.0/
--rw-r--r--   0 jerome    (1000) jerome    (1000)       32 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/.babelrc.json
--rw-r--r--   0 jerome    (1000) jerome    (1000)       17 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/.browserslistrc
--rw-r--r--   0 jerome    (1000) jerome    (1000)      328 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/.editorconfig
--rw-r--r--   0 jerome    (1000) jerome    (1000)      432 2023-06-21 12:12:17.000000 wagtail-webradio-0.6.0/.eslintrc.js
--rw-r--r--   0 jerome    (1000) jerome    (1000)       80 2023-06-14 15:42:43.000000 wagtail-webradio-0.6.0/.gitattributes
--rw-r--r--   0 jerome    (1000) jerome    (1000)      286 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/.gitignore
--rw-r--r--   0 jerome    (1000) jerome    (1000)      732 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.0/.gitlab-ci.yml
--rw-r--r--   0 jerome    (1000) jerome    (1000)      835 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.0/.pre-commit-config.yaml
--rw-r--r--   0 jerome    (1000) jerome    (1000)       83 2023-06-14 14:18:27.000000 wagtail-webradio-0.6.0/.prettierrc
--rw-r--r--   0 jerome    (1000) jerome    (1000)     2559 2023-06-21 13:58:36.000000 wagtail-webradio-0.6.0/CHANGELOG.md
--rw-r--r--   0 jerome    (1000) jerome    (1000)    34500 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/LICENSE
--rw-r--r--   0 jerome    (1000) jerome    (1000)      109 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/MANIFEST.in
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1114 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.0/Makefile
--rw-r--r--   0 jerome    (1000) jerome    (1000)     6194 2023-06-21 14:03:00.855100 wagtail-webradio-0.6.0/PKG-INFO
--rw-r--r--   0 jerome    (1000) jerome    (1000)     5133 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/README.md
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.831100 wagtail-webradio-0.6.0/client/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.843100 wagtail-webradio-0.6.0/client/src/
--rw-r--r--   0 jerome    (1000) jerome    (1000)      221 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/client/src/admin-podcast-form.js
--rw-r--r--   0 jerome    (1000) jerome    (1000)      233 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/client/src/admin-podcast-form_controllers.js
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.843100 wagtail-webradio-0.6.0/client/src/controllers/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     8510 2023-06-21 12:12:22.000000 wagtail-webradio-0.6.0/client/src/controllers/player.js
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1497 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/client/src/controllers/podcast-form.js
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1992 2023-06-21 12:12:17.000000 wagtail-webradio-0.6.0/client/src/player.js
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.831100 wagtail-webradio-0.6.0/examples/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.843100 wagtail-webradio-0.6.0/examples/player/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     5726 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/examples/player/styles.scss
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1690 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/noxfile.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)   181291 2023-06-21 12:12:22.000000 wagtail-webradio-0.6.0/package-lock.json
--rw-r--r--   0 jerome    (1000) jerome    (1000)      691 2023-06-21 12:12:22.000000 wagtail-webradio-0.6.0/package.json
--rw-r--r--   0 jerome    (1000) jerome    (1000)      794 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.0/pyproject.toml
--rw-r--r--   0 jerome    (1000) jerome    (1000)       54 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.0/requirements-dev.txt
--rw-r--r--   0 jerome    (1000) jerome    (1000)      109 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/requirements-test.txt
--rw-r--r--   0 jerome    (1000) jerome    (1000)      780 2023-06-21 12:12:17.000000 wagtail-webradio-0.6.0/rollup.config.mjs
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1207 2023-06-21 14:03:00.855100 wagtail-webradio-0.6.0/setup.cfg
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.847100 wagtail-webradio-0.6.0/tests/
--rw-r--r--   0 jerome    (1000) jerome    (1000)       86 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/tests/__init__.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     3086 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/tests/conftest.py
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.847100 wagtail-webradio-0.6.0/tests/data/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     6843 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/tests/data/sine.ogg
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1662 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.0/tests/factories.py
--rwxr-xr-x   0 jerome    (1000) jerome    (1000)      338 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.0/tests/manage.py
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.847100 wagtail-webradio-0.6.0/tests/migrations/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1024 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/tests/migrations/0001_initial.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)        0 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.0/tests/migrations/__init__.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)      578 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/tests/models.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     2254 2023-06-21 12:12:17.000000 wagtail-webradio-0.6.0/tests/settings.py
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.831100 wagtail-webradio-0.6.0/tests/snapshots/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.847100 wagtail-webradio-0.6.0/tests/snapshots/player/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     2475 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/tests/snapshots/player/empty.html
--rw-r--r--   0 jerome    (1000) jerome    (1000)     3506 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/tests/snapshots/player/with_playlist.html
--rw-r--r--   0 jerome    (1000) jerome    (1000)     5386 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/tests/test_blocks.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     8385 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/tests/test_components.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     5496 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/tests/test_models.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)    28918 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.0/tests/test_permissions.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)      503 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.0/tests/test_utils.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)    27900 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/tests/test_views.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)      524 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/tests/urls.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     3949 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/tests/utils.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)      249 2023-06-15 13:36:54.000000 wagtail-webradio-0.6.0/todo.md
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.847100 wagtail-webradio-0.6.0/wagtail_webradio/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1335 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/wagtail_webradio/__init__.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     2709 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/admin_urls.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)      202 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.0/wagtail_webradio/apps.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1953 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/blocks.py
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.851100 wagtail-webradio-0.6.0/wagtail_webradio/components/
--rw-r--r--   0 jerome    (1000) jerome    (1000)        0 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.0/wagtail_webradio/components/__init__.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     7881 2023-06-07 15:23:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/components/player.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)    10993 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/wagtail_webradio/forms.py
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.831100 wagtail-webradio-0.6.0/wagtail_webradio/locale/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.831100 wagtail-webradio-0.6.0/wagtail_webradio/locale/fr/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.851100 wagtail-webradio-0.6.0/wagtail_webradio/locale/fr/LC_MESSAGES/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     6280 2023-06-21 13:49:30.000000 wagtail-webradio-0.6.0/wagtail_webradio/locale/fr/LC_MESSAGES/django.mo
--rw-r--r--   0 jerome    (1000) jerome    (1000)     9075 2023-06-21 13:49:23.000000 wagtail-webradio-0.6.0/wagtail_webradio/locale/fr/LC_MESSAGES/django.po
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.851100 wagtail-webradio-0.6.0/wagtail_webradio/migrations/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     5030 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/migrations/0001_initial.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)      423 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.0/wagtail_webradio/migrations/0002_podcast_duration.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)      700 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.0/wagtail_webradio/migrations/0003_sound_file.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)        0 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.0/wagtail_webradio/migrations/__init__.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)    10100 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/wagtail_webradio/models.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     3384 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/wagtail_webradio/panels.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)    10640 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/permissions.py
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.831100 wagtail-webradio-0.6.0/wagtail_webradio/static/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.835100 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.835100 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.851100 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/css/
--rw-r--r--   0 jerome    (1000) jerome    (1000)      105 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/css/clearable_file_input.css
--rw-r--r--   0 jerome    (1000) jerome    (1000)      363 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/css/podcast-form.css
--rw-r--r--   0 jerome    (1000) jerome    (1000)      515 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/css/radio_show_permissions.css
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.851100 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/js/
--rw-r--r--   0 jerome    (1000) jerome    (1000)    43313 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form.js
--rw-r--r--   0 jerome    (1000) jerome    (1000)   141234 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form.js.map
--rw-r--r--   0 jerome    (1000) jerome    (1000)     7772 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form_controllers.js
--rw-r--r--   0 jerome    (1000) jerome    (1000)    97745 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form_controllers.js.map
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.835100 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/player/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.851100 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/player/js/
--rw-r--r--   0 jerome    (1000) jerome    (1000)    48537 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/player/js/main.js
--rw-r--r--   0 jerome    (1000) jerome    (1000)   159655 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/player/js/main.js.map
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.835100 wagtail-webradio-0.6.0/wagtail_webradio/templates/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.835100 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.851100 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/components/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     4537 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/components/player.html
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.851100 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/generic/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1141 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/generic/confirm_delete.html
--rw-r--r--   0 jerome    (1000) jerome    (1000)       51 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/generic/create.html
--rw-r--r--   0 jerome    (1000) jerome    (1000)      220 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/generic/edit.html
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1113 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/generic/form.html
--rw-r--r--   0 jerome    (1000) jerome    (1000)       48 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/generic/index.html
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.855100 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/icons/
--rw-r--r--   0 jerome    (1000) jerome    (1000)      772 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/icons/broadcast.svg
--rw-r--r--   0 jerome    (1000) jerome    (1000)      482 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/icons/headphone.svg
--rw-r--r--   0 jerome    (1000) jerome    (1000)      420 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/icons/microphone.svg
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.855100 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/panels/
--rw-r--r--   0 jerome    (1000) jerome    (1000)      132 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/panels/podcast_object_list.html
--rw-r--r--   0 jerome    (1000) jerome    (1000)      264 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/panels/podcast_sound_field_panel.html
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.835100 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/permissions/
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.855100 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/permissions/includes/
--rw-r--r--   0 jerome    (1000) jerome    (1000)      478 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/permissions/includes/radio_show_permissions_form.html
--rw-r--r--   0 jerome    (1000) jerome    (1000)     2699 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/permissions/includes/radio_show_permissions_formset.html
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.855100 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/tables/
--rw-r--r--   0 jerome    (1000) jerome    (1000)      367 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/tables/radio_show_podcasts_cell.html
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.855100 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/widgets/
--rw-r--r--   0 jerome    (1000) jerome    (1000)      650 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/widgets/clearable_file_input.html
--rw-r--r--   0 jerome    (1000) jerome    (1000)      574 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/ui.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)      520 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.0/wagtail_webradio/utils.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1054 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.0/wagtail_webradio/validators.py
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.855100 wagtail-webradio-0.6.0/wagtail_webradio/views/
--rw-r--r--   0 jerome    (1000) jerome    (1000)        0 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.0/wagtail_webradio/views/__init__.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     6508 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/views/admin.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     1499 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/views/chooser.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     4441 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/views/generic.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)     2776 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/wagtail_hooks.py
--rw-r--r--   0 jerome    (1000) jerome    (1000)      463 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.0/wagtail_webradio/widgets.py
-drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-21 14:03:00.851100 wagtail-webradio-0.6.0/wagtail_webradio.egg-info/
--rw-r--r--   0 jerome    (1000) jerome    (1000)     6194 2023-06-21 14:03:00.000000 wagtail-webradio-0.6.0/wagtail_webradio.egg-info/PKG-INFO
--rw-r--r--   0 jerome    (1000) jerome    (1000)     3744 2023-06-21 14:03:00.000000 wagtail-webradio-0.6.0/wagtail_webradio.egg-info/SOURCES.txt
--rw-r--r--   0 jerome    (1000) jerome    (1000)        1 2023-06-21 14:03:00.000000 wagtail-webradio-0.6.0/wagtail_webradio.egg-info/dependency_links.txt
--rw-r--r--   0 jerome    (1000) jerome    (1000)       73 2023-06-21 14:03:00.000000 wagtail-webradio-0.6.0/wagtail_webradio.egg-info/requires.txt
--rw-r--r--   0 jerome    (1000) jerome    (1000)       17 2023-06-21 14:03:00.000000 wagtail-webradio-0.6.0/wagtail_webradio.egg-info/top_level.txt
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.435719 wagtail-webradio-0.6.1/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       32 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/.babelrc.json
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       17 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/.browserslistrc
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      328 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/.editorconfig
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      432 2023-06-21 12:12:17.000000 wagtail-webradio-0.6.1/.eslintrc.js
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       80 2023-06-14 15:42:43.000000 wagtail-webradio-0.6.1/.gitattributes
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      286 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/.gitignore
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      732 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.1/.gitlab-ci.yml
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      835 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.1/.pre-commit-config.yaml
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       83 2023-06-14 14:18:27.000000 wagtail-webradio-0.6.1/.prettierrc
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     2704 2023-06-28 08:54:11.000000 wagtail-webradio-0.6.1/CHANGELOG.md
+-rw-r--r--   0 jerome    (1000) jerome    (1000)    34500 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/LICENSE
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      109 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/MANIFEST.in
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1114 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.1/Makefile
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     6194 2023-06-28 08:59:56.435719 wagtail-webradio-0.6.1/PKG-INFO
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     5133 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/README.md
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.399720 wagtail-webradio-0.6.1/client/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.411720 wagtail-webradio-0.6.1/client/src/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      221 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/client/src/admin-podcast-form.js
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      233 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/client/src/admin-podcast-form_controllers.js
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.411720 wagtail-webradio-0.6.1/client/src/controllers/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     8510 2023-06-21 12:12:22.000000 wagtail-webradio-0.6.1/client/src/controllers/player.js
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1497 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/client/src/controllers/podcast-form.js
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1992 2023-06-21 12:12:17.000000 wagtail-webradio-0.6.1/client/src/player.js
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.399720 wagtail-webradio-0.6.1/examples/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.411720 wagtail-webradio-0.6.1/examples/player/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     5726 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/examples/player/styles.scss
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1690 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/noxfile.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)   181291 2023-06-21 12:12:22.000000 wagtail-webradio-0.6.1/package-lock.json
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      691 2023-06-21 12:12:22.000000 wagtail-webradio-0.6.1/package.json
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      794 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.1/pyproject.toml
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       54 2023-06-07 13:26:55.000000 wagtail-webradio-0.6.1/requirements-dev.txt
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      109 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/requirements-test.txt
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      780 2023-06-21 12:12:17.000000 wagtail-webradio-0.6.1/rollup.config.mjs
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1207 2023-06-28 08:59:56.435719 wagtail-webradio-0.6.1/setup.cfg
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.415720 wagtail-webradio-0.6.1/tests/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       86 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/tests/__init__.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     3086 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/tests/conftest.py
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.415720 wagtail-webradio-0.6.1/tests/data/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     6843 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/tests/data/sine.ogg
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1662 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.1/tests/factories.py
+-rwxr-xr-x   0 jerome    (1000) jerome    (1000)      338 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.1/tests/manage.py
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.415720 wagtail-webradio-0.6.1/tests/migrations/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1024 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/tests/migrations/0001_initial.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)        0 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.1/tests/migrations/__init__.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      578 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/tests/models.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     2254 2023-06-21 12:12:17.000000 wagtail-webradio-0.6.1/tests/settings.py
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.399720 wagtail-webradio-0.6.1/tests/snapshots/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.415720 wagtail-webradio-0.6.1/tests/snapshots/player/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     2475 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/tests/snapshots/player/empty.html
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     3506 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/tests/snapshots/player/with_playlist.html
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     5386 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/tests/test_blocks.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     8385 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/tests/test_components.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     5496 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/tests/test_models.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)    28918 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.1/tests/test_permissions.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      503 2023-06-07 13:35:24.000000 wagtail-webradio-0.6.1/tests/test_utils.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)    27900 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/tests/test_views.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      524 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/tests/urls.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     3949 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/tests/utils.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      249 2023-06-15 13:36:54.000000 wagtail-webradio-0.6.1/todo.md
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.419720 wagtail-webradio-0.6.1/wagtail_webradio/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1335 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/wagtail_webradio/__init__.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     2709 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/admin_urls.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      202 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.1/wagtail_webradio/apps.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1953 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/blocks.py
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.423720 wagtail-webradio-0.6.1/wagtail_webradio/components/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)        0 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.1/wagtail_webradio/components/__init__.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     7881 2023-06-07 15:23:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/components/player.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)    10993 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/wagtail_webradio/forms.py
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.403720 wagtail-webradio-0.6.1/wagtail_webradio/locale/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.403720 wagtail-webradio-0.6.1/wagtail_webradio/locale/fr/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.423720 wagtail-webradio-0.6.1/wagtail_webradio/locale/fr/LC_MESSAGES/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     6280 2023-06-21 14:05:08.000000 wagtail-webradio-0.6.1/wagtail_webradio/locale/fr/LC_MESSAGES/django.mo
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     9075 2023-06-21 14:05:08.000000 wagtail-webradio-0.6.1/wagtail_webradio/locale/fr/LC_MESSAGES/django.po
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.423720 wagtail-webradio-0.6.1/wagtail_webradio/migrations/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     5030 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/migrations/0001_initial.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      423 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.1/wagtail_webradio/migrations/0002_podcast_duration.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      700 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.1/wagtail_webradio/migrations/0003_sound_file.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)        0 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.1/wagtail_webradio/migrations/__init__.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)    10100 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/wagtail_webradio/models.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     3384 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/wagtail_webradio/panels.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)    10640 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/permissions.py
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.403720 wagtail-webradio-0.6.1/wagtail_webradio/static/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.403720 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.403720 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.423720 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/css/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      105 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/css/clearable_file_input.css
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      363 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/css/podcast-form.css
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      515 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/css/radio_show_permissions.css
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.427720 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/js/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)    43313 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form.js
+-rw-r--r--   0 jerome    (1000) jerome    (1000)   141234 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form.js.map
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     7772 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form_controllers.js
+-rw-r--r--   0 jerome    (1000) jerome    (1000)    97745 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form_controllers.js.map
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.403720 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/player/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.427720 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/player/js/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)    48537 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/player/js/main.js
+-rw-r--r--   0 jerome    (1000) jerome    (1000)   159655 2023-06-21 12:37:09.000000 wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/player/js/main.js.map
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.403720 wagtail-webradio-0.6.1/wagtail_webradio/templates/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.403720 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.431720 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/components/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     4537 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/components/player.html
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.431720 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/generic/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1141 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/generic/confirm_delete.html
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       51 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/generic/create.html
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      220 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/generic/edit.html
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1958 2023-06-28 08:54:04.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/generic/form.html
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       48 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/generic/index.html
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.431720 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/icons/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      772 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/icons/broadcast.svg
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      482 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/icons/headphone.svg
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      420 2023-06-07 12:28:42.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/icons/microphone.svg
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.431720 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/panels/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      132 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/panels/podcast_object_list.html
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      264 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/panels/podcast_sound_field_panel.html
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.403720 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/permissions/
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.431720 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/permissions/includes/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      478 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/permissions/includes/radio_show_permissions_form.html
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     2699 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/permissions/includes/radio_show_permissions_formset.html
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.431720 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/tables/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      367 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/tables/radio_show_podcasts_cell.html
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.435719 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/widgets/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      650 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/widgets/clearable_file_input.html
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      574 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/ui.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      520 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.1/wagtail_webradio/utils.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1054 2023-06-21 12:37:25.000000 wagtail-webradio-0.6.1/wagtail_webradio/validators.py
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.435719 wagtail-webradio-0.6.1/wagtail_webradio/views/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)        0 2023-06-07 13:35:20.000000 wagtail-webradio-0.6.1/wagtail_webradio/views/__init__.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     6508 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/views/admin.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     1499 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/views/chooser.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     4441 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/views/generic.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     2776 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/wagtail_hooks.py
+-rw-r--r--   0 jerome    (1000) jerome    (1000)      463 2023-06-15 13:35:57.000000 wagtail-webradio-0.6.1/wagtail_webradio/widgets.py
+drwxr-xr-x   0 jerome    (1000) jerome    (1000)        0 2023-06-28 08:59:56.423720 wagtail-webradio-0.6.1/wagtail_webradio.egg-info/
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     6194 2023-06-28 08:59:56.000000 wagtail-webradio-0.6.1/wagtail_webradio.egg-info/PKG-INFO
+-rw-r--r--   0 jerome    (1000) jerome    (1000)     3744 2023-06-28 08:59:56.000000 wagtail-webradio-0.6.1/wagtail_webradio.egg-info/SOURCES.txt
+-rw-r--r--   0 jerome    (1000) jerome    (1000)        1 2023-06-28 08:59:56.000000 wagtail-webradio-0.6.1/wagtail_webradio.egg-info/dependency_links.txt
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       73 2023-06-28 08:59:56.000000 wagtail-webradio-0.6.1/wagtail_webradio.egg-info/requires.txt
+-rw-r--r--   0 jerome    (1000) jerome    (1000)       17 2023-06-28 08:59:56.000000 wagtail-webradio-0.6.1/wagtail_webradio.egg-info/top_level.txt
```

### Comparing `wagtail-webradio-0.6.0/.gitlab-ci.yml` & `wagtail-webradio-0.6.1/.gitlab-ci.yml`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/.pre-commit-config.yaml` & `wagtail-webradio-0.6.1/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/CHANGELOG.md` & `wagtail-webradio-0.6.1/CHANGELOG.md`

 * *Files 5% similar despite different names*

```diff
@@ -3,14 +3,19 @@
 All notable changes to this project will be documented in this file.
 
 The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
 and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
 
 ## Unreleased
 
+## 0.6.1 - 2023-06-28
+### Fixed
+- Load the required scripts in the create and edit admin views to fix the
+  link feature of the Draftail editor
+
 ## 0.6.0 - 2023-06-21
 
 **Breaking changes!** The following settings have been renamed:
 - ``WEBRADIO_SOUND_FILE`` to ``WEBRADIO_PODCAST_SOUND_FILE``
 - ``WEBRADIO_AUTHORIZED_MIME_TYPES`` to ``WEBRADIO_ALLOWED_AUDIO_MIME_TYPES``
 
 ### Added
```

### Comparing `wagtail-webradio-0.6.0/LICENSE` & `wagtail-webradio-0.6.1/LICENSE`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/Makefile` & `wagtail-webradio-0.6.1/Makefile`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/PKG-INFO` & `wagtail-webradio-0.6.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wagtail-webradio
-Version: 0.6.0
+Version: 0.6.1
 Summary: Manage your web radio - e.g. podcasts, programs - in Wagtail
 Author: Cliss XXI
 Author-email: contact@cliss21.com
 License: AGPLv3+
 Project-URL: Bug Tracker, https://framagit.org/cliss21/wagtail-webradio/-/issues
 Project-URL: Source Code, https://framagit.org/cliss21/wagtail-webradio
 Keywords: wagtail,radio
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: wagtail-webradio Version: 0.6.0 Summary: Manage
+Metadata-Version: 2.1 Name: wagtail-webradio Version: 0.6.1 Summary: Manage
 your web radio - e.g. podcasts, programs - in Wagtail Author: Cliss XXI Author-
 email: contact@cliss21.com License: AGPLv3+ Project-URL: Bug Tracker, https://
 framagit.org/cliss21/wagtail-webradio/-/issues Project-URL: Source Code, https:
 //framagit.org/cliss21/wagtail-webradio Keywords: wagtail,radio Classifier:
 Development Status :: 3 - Alpha Classifier: Environment :: Web Environment
 Classifier: Framework :: Django Classifier: Framework :: Wagtail Classifier:
 Intended Audience :: Developers Classifier: License :: OSI Approved :: GNU
```

### Comparing `wagtail-webradio-0.6.0/README.md` & `wagtail-webradio-0.6.1/README.md`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/client/src/controllers/player.js` & `wagtail-webradio-0.6.1/client/src/controllers/player.js`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/client/src/controllers/podcast-form.js` & `wagtail-webradio-0.6.1/client/src/controllers/podcast-form.js`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/client/src/player.js` & `wagtail-webradio-0.6.1/client/src/player.js`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/examples/player/styles.scss` & `wagtail-webradio-0.6.1/examples/player/styles.scss`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/noxfile.py` & `wagtail-webradio-0.6.1/noxfile.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/package-lock.json` & `wagtail-webradio-0.6.1/package-lock.json`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/package.json` & `wagtail-webradio-0.6.1/package.json`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/pyproject.toml` & `wagtail-webradio-0.6.1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/rollup.config.mjs` & `wagtail-webradio-0.6.1/rollup.config.mjs`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/setup.cfg` & `wagtail-webradio-0.6.1/setup.cfg`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/conftest.py` & `wagtail-webradio-0.6.1/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/data/sine.ogg` & `wagtail-webradio-0.6.1/tests/data/sine.ogg`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/factories.py` & `wagtail-webradio-0.6.1/tests/factories.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/migrations/0001_initial.py` & `wagtail-webradio-0.6.1/tests/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/models.py` & `wagtail-webradio-0.6.1/tests/models.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/settings.py` & `wagtail-webradio-0.6.1/tests/settings.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/snapshots/player/empty.html` & `wagtail-webradio-0.6.1/tests/snapshots/player/empty.html`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/snapshots/player/with_playlist.html` & `wagtail-webradio-0.6.1/tests/snapshots/player/with_playlist.html`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/test_blocks.py` & `wagtail-webradio-0.6.1/tests/test_blocks.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/test_components.py` & `wagtail-webradio-0.6.1/tests/test_components.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/test_models.py` & `wagtail-webradio-0.6.1/tests/test_models.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/test_permissions.py` & `wagtail-webradio-0.6.1/tests/test_permissions.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/test_views.py` & `wagtail-webradio-0.6.1/tests/test_views.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/urls.py` & `wagtail-webradio-0.6.1/tests/urls.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/tests/utils.py` & `wagtail-webradio-0.6.1/tests/utils.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/__init__.py` & `wagtail-webradio-0.6.1/wagtail_webradio/__init__.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/admin_urls.py` & `wagtail-webradio-0.6.1/wagtail_webradio/admin_urls.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/blocks.py` & `wagtail-webradio-0.6.1/wagtail_webradio/blocks.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/components/player.py` & `wagtail-webradio-0.6.1/wagtail_webradio/components/player.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/forms.py` & `wagtail-webradio-0.6.1/wagtail_webradio/forms.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/locale/fr/LC_MESSAGES/django.mo` & `wagtail-webradio-0.6.1/wagtail_webradio/locale/fr/LC_MESSAGES/django.mo`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/locale/fr/LC_MESSAGES/django.po` & `wagtail-webradio-0.6.1/wagtail_webradio/locale/fr/LC_MESSAGES/django.po`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/migrations/0001_initial.py` & `wagtail-webradio-0.6.1/wagtail_webradio/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/migrations/0003_sound_file.py` & `wagtail-webradio-0.6.1/wagtail_webradio/migrations/0003_sound_file.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/models.py` & `wagtail-webradio-0.6.1/wagtail_webradio/models.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/panels.py` & `wagtail-webradio-0.6.1/wagtail_webradio/panels.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/permissions.py` & `wagtail-webradio-0.6.1/wagtail_webradio/permissions.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/css/radio_show_permissions.css` & `wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/css/radio_show_permissions.css`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form.js` & `wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form.js`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form.js.map` & `wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form.js.map`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form_controllers.js` & `wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form_controllers.js`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form_controllers.js.map` & `wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/admin/js/podcast-form_controllers.js.map`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/player/js/main.js` & `wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/player/js/main.js`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/static/wagtail_webradio/player/js/main.js.map` & `wagtail-webradio-0.6.1/wagtail_webradio/static/wagtail_webradio/player/js/main.js.map`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/components/player.html` & `wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/components/player.html`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/generic/confirm_delete.html` & `wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/generic/confirm_delete.html`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/icons/broadcast.svg` & `wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/icons/broadcast.svg`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/permissions/includes/radio_show_permissions_formset.html` & `wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/permissions/includes/radio_show_permissions_formset.html`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/templates/wagtail_webradio/widgets/clearable_file_input.html` & `wagtail-webradio-0.6.1/wagtail_webradio/templates/wagtail_webradio/widgets/clearable_file_input.html`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/ui.py` & `wagtail-webradio-0.6.1/wagtail_webradio/ui.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/utils.py` & `wagtail-webradio-0.6.1/wagtail_webradio/utils.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/validators.py` & `wagtail-webradio-0.6.1/wagtail_webradio/validators.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/views/admin.py` & `wagtail-webradio-0.6.1/wagtail_webradio/views/admin.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/views/chooser.py` & `wagtail-webradio-0.6.1/wagtail_webradio/views/chooser.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/views/generic.py` & `wagtail-webradio-0.6.1/wagtail_webradio/views/generic.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio/wagtail_hooks.py` & `wagtail-webradio-0.6.1/wagtail_webradio/wagtail_hooks.py`

 * *Files identical despite different names*

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio.egg-info/PKG-INFO` & `wagtail-webradio-0.6.1/wagtail_webradio.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: wagtail-webradio
-Version: 0.6.0
+Version: 0.6.1
 Summary: Manage your web radio - e.g. podcasts, programs - in Wagtail
 Author: Cliss XXI
 Author-email: contact@cliss21.com
 License: AGPLv3+
 Project-URL: Bug Tracker, https://framagit.org/cliss21/wagtail-webradio/-/issues
 Project-URL: Source Code, https://framagit.org/cliss21/wagtail-webradio
 Keywords: wagtail,radio
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: wagtail-webradio Version: 0.6.0 Summary: Manage
+Metadata-Version: 2.1 Name: wagtail-webradio Version: 0.6.1 Summary: Manage
 your web radio - e.g. podcasts, programs - in Wagtail Author: Cliss XXI Author-
 email: contact@cliss21.com License: AGPLv3+ Project-URL: Bug Tracker, https://
 framagit.org/cliss21/wagtail-webradio/-/issues Project-URL: Source Code, https:
 //framagit.org/cliss21/wagtail-webradio Keywords: wagtail,radio Classifier:
 Development Status :: 3 - Alpha Classifier: Environment :: Web Environment
 Classifier: Framework :: Django Classifier: Framework :: Wagtail Classifier:
 Intended Audience :: Developers Classifier: License :: OSI Approved :: GNU
```

### Comparing `wagtail-webradio-0.6.0/wagtail_webradio.egg-info/SOURCES.txt` & `wagtail-webradio-0.6.1/wagtail_webradio.egg-info/SOURCES.txt`

 * *Files identical despite different names*


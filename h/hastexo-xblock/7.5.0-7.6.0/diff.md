# Comparing `tmp/hastexo-xblock-7.5.0.tar.gz` & `tmp/hastexo-xblock-7.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist/hastexo-xblock-7.5.0.tar", last modified: Wed Mar 15 14:45:48 2023, max compression
+gzip compressed data, was "dist/hastexo-xblock-7.6.0.tar", last modified: Wed Jun 28 10:04:35 2023, max compression
```

## Comparing `hastexo-xblock-7.5.0.tar` & `hastexo-xblock-7.6.0.tar`

### file list

```diff
@@ -1,181 +1,182 @@
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.687358 hastexo-xblock-7.5.0/
--rw-r--r--   0 root         (0) staff       (20)      328 2023-03-15 14:30:49.000000 hastexo-xblock-7.5.0/.bumpversion.cfg
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.618857 hastexo-xblock-7.5.0/.githooks/
--rwxr-xr-x   0 root         (0) staff       (20)       29 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/.githooks/pre-commit
--rwxr-xr-x   0 root         (0) staff       (20)       19 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/.githooks/pre-push
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.597380 hastexo-xblock-7.5.0/.github/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.619558 hastexo-xblock-7.5.0/.github/workflows/
--rw-r--r--   0 root         (0) staff       (20)     1669 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/.github/workflows/tox.yml
--rw-r--r--   0 root         (0) staff       (20)       58 2022-12-02 10:31:03.000000 hastexo-xblock-7.5.0/.gitignore
--rw-r--r--   0 root         (0) staff       (20)      681 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/.gitlab-ci.yml
--rw-r--r--   0 root         (0) staff       (20)    27822 2023-03-15 14:30:49.000000 hastexo-xblock-7.5.0/Changelog.md
--rw-r--r--   0 root         (0) staff       (20)     5452 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/HACKING.md
--rw-r--r--   0 root         (0) staff       (20)    34520 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/LICENSE
--rw-r--r--   0 root         (0) staff       (20)    35803 2023-03-15 14:45:48.687031 hastexo-xblock-7.5.0/PKG-INFO
--rw-r--r--   0 root         (0) staff       (20)    28946 2023-03-14 14:24:38.000000 hastexo-xblock-7.5.0/README.md
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.598162 hastexo-xblock-7.5.0/fake/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.597844 hastexo-xblock-7.5.0/fake/common/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.597972 hastexo-xblock-7.5.0/fake/common/djangoapps/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.620680 hastexo-xblock-7.5.0/fake/common/djangoapps/student/
--rw-r--r--   0 root         (0) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/fake/common/djangoapps/student/__init__.py
--rw-r--r--   0 root         (0) staff       (20)      443 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/fake/common/djangoapps/student/models.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.621237 hastexo-xblock-7.5.0/fake/course/
--rw-r--r--   0 root         (0) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/fake/course/__init__.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.626914 hastexo-xblock-7.5.0/hastexo/
--rw-r--r--   0 root         (0) staff       (20)      347 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/__init__.py
--rw-r--r--   0 root         (0) staff       (20)     4167 2022-11-17 10:21:18.000000 hastexo-xblock-7.5.0/hastexo/admin.py
--rw-r--r--   0 root         (0) staff       (20)    11305 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/common.py
--rw-r--r--   0 root         (0) staff       (20)     1560 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/gcloud.py
--rw-r--r--   0 root         (0) staff       (20)    41166 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/hastexo.py
--rw-r--r--   0 root         (0) staff       (20)     6099 2022-11-30 14:31:42.000000 hastexo-xblock-7.5.0/hastexo/jobs.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.627491 hastexo-xblock-7.5.0/hastexo/locale/
--rw-r--r--   0 root         (0) staff       (20)      341 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/locale/config.yaml
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.598863 hastexo-xblock-7.5.0/hastexo/locale/en/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.628387 hastexo-xblock-7.5.0/hastexo/locale/en/LC_MESSAGES/
--rw-r--r--   0 root         (0) staff       (20)     3409 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/locale/en/LC_MESSAGES/django-partial.po
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.629254 hastexo-xblock-7.5.0/hastexo/management/
--rw-r--r--   0 root         (0) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/management/__init__.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.629696 hastexo-xblock-7.5.0/hastexo/management/__pycache__/
--rw-r--r--   0 root         (0) staff       (20)      158 2022-11-03 15:09:41.000000 hastexo-xblock-7.5.0/hastexo/management/__pycache__/__init__.cpython-38.pyc
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.631392 hastexo-xblock-7.5.0/hastexo/management/commands/
--rw-r--r--   0 root         (0) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/management/commands/__init__.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.633267 hastexo-xblock-7.5.0/hastexo/management/commands/__pycache__/
--rw-r--r--   0 root         (0) staff       (20)      167 2022-11-03 15:09:41.000000 hastexo-xblock-7.5.0/hastexo/management/commands/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      994 2022-11-03 15:09:41.000000 hastexo-xblock-7.5.0/hastexo/management/commands/__pycache__/reaper.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      925 2022-11-03 15:09:41.000000 hastexo-xblock-7.5.0/hastexo/management/commands/__pycache__/suspender.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      708 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/management/commands/reaper.py
--rw-r--r--   0 root         (0) staff       (20)      639 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/management/commands/suspender.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.641095 hastexo-xblock-7.5.0/hastexo/migrations/
--rw-r--r--   0 root         (0) staff       (20)     1900 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0001_initial.py
--rw-r--r--   0 root         (0) staff       (20)     2016 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0002_stacklog.py
--rw-r--r--   0 root         (0) staff       (20)     2596 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0003_blanks.py
--rw-r--r--   0 root         (0) staff       (20)      560 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0004_auto_20190715_1053.py
--rw-r--r--   0 root         (0) staff       (20)     1647 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0005_auto_20190811_1555.py
--rw-r--r--   0 root         (0) staff       (20)     1469 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0006_auto_20200107_1332.py
--rw-r--r--   0 root         (0) staff       (20)     1034 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0007_add_delete_by_and_delete_age.py
--rw-r--r--   0 root         (0) staff       (20)      581 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0008_add_database_defaults_for_stack_key_and_password.py
--rw-r--r--   0 root         (0) staff       (20)      599 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0009_add_null_true_for_key_and_password.py
--rw-r--r--   0 root         (0) staff       (20)     1748 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0010_add_user_foreign_key.py
--rw-r--r--   0 root         (0) staff       (20)     1018 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0011_allow_null_for_learner.py
--rw-r--r--   0 root         (0) staff       (20)      529 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/0012_add_suspend_by.py
--rw-r--r--   0 root         (0) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/migrations/__init__.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.651952 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/
--rw-r--r--   0 root         (0) staff       (20)     1411 2022-11-03 15:10:42.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0001_initial.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)     1486 2022-11-03 15:10:42.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0002_stacklog.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)     1267 2022-11-03 15:10:43.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0003_blanks.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      750 2022-11-03 15:10:43.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0004_auto_20190715_1053.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)     1089 2022-11-03 15:10:42.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0005_auto_20190811_1555.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)     1202 2022-11-03 15:10:43.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0006_auto_20200107_1332.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      895 2022-11-03 15:10:42.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0007_add_delete_by_and_delete_age.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      778 2022-11-03 15:10:43.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0008_add_database_defaults_for_stack_key_and_password.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      779 2022-11-03 15:10:42.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0009_add_null_true_for_key_and_password.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)     1670 2022-11-03 15:10:42.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0010_add_user_foreign_key.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      844 2022-11-03 15:10:42.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0011_allow_null_for_learner.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      703 2022-11-03 15:10:42.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0012_add_suspend_by.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)      213 2022-11-03 15:10:42.000000 hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/__init__.cpython-38.pyc
--rw-r--r--   0 root         (0) staff       (20)     3644 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/models.py
--rw-r--r--   0 root         (0) staff       (20)     4614 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/openstack.py
--rw-r--r--   0 root         (0) staff       (20)    27375 2022-11-23 14:17:13.000000 hastexo-xblock-7.5.0/hastexo/provider.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.600690 hastexo-xblock-7.5.0/hastexo/public/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.652640 hastexo-xblock-7.5.0/hastexo/public/css/
--rw-r--r--   0 root         (0) staff       (20)     3279 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/public/css/main.css
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.654738 hastexo-xblock-7.5.0/hastexo/public/js/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.657039 hastexo-xblock-7.5.0/hastexo/public/js/guacamole-common-js/
--rw-r--r--   0 root         (0) staff       (20)    67952 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/public/js/guacamole-common-js/0.9.13-incubating-all.min.js
--rw-r--r--   0 root         (0) staff       (20)    70401 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/public/js/guacamole-common-js/1.4.0-all.min.js
--rw-r--r--   0 root         (0) staff       (20)    26635 2023-03-14 14:24:38.000000 hastexo-xblock-7.5.0/hastexo/public/js/main.js
--rw-r--r--   0 root         (0) staff       (20)     2344 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo/public/js/plugins.js
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.602317 hastexo-xblock-7.5.0/hastexo/public/js/translations/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.658490 hastexo-xblock-7.5.0/hastexo/public/js/translations/de-de/
--rw-r--r--   0 root         (0) staff       (20)     6974 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/public/js/translations/de-de/text.js
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.659318 hastexo-xblock-7.5.0/hastexo/public/js/translations/el/
--rw-r--r--   0 root         (0) staff       (20)    13551 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/public/js/translations/el/text.js
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.660244 hastexo-xblock-7.5.0/hastexo/public/js/translations/es-419/
--rw-r--r--   0 root         (0) staff       (20)     6742 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/public/js/translations/es-419/text.js
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.660824 hastexo-xblock-7.5.0/hastexo/public/js/translations/et-ee/
--rw-r--r--   0 root         (0) staff       (20)     6695 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/public/js/translations/et-ee/text.js
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.661434 hastexo-xblock-7.5.0/hastexo/public/js/translations/hi/
--rw-r--r--   0 root         (0) staff       (20)    12293 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/public/js/translations/hi/text.js
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.602701 hastexo-xblock-7.5.0/hastexo/static/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.661998 hastexo-xblock-7.5.0/hastexo/static/html/
--rw-r--r--   0 root         (0) staff       (20)     3301 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/static/html/main.html
--rw-r--r--   0 root         (0) staff       (20)    34430 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/tasks.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.605786 hastexo-xblock-7.5.0/hastexo/translations/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.603366 hastexo-xblock-7.5.0/hastexo/translations/de_DE/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.663228 hastexo-xblock-7.5.0/hastexo/translations/de_DE/LC_MESSAGES/
--rw-r--r--   0 root         (0) staff       (20)     3982 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/de_DE/LC_MESSAGES/text.mo
--rw-r--r--   0 root         (0) staff       (20)     5005 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/de_DE/LC_MESSAGES/text.po
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.603847 hastexo-xblock-7.5.0/hastexo/translations/el/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.664602 hastexo-xblock-7.5.0/hastexo/translations/el/LC_MESSAGES/
--rw-r--r--   0 root         (0) staff       (20)     5293 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/el/LC_MESSAGES/text.mo
--rw-r--r--   0 root         (0) staff       (20)     6358 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/el/LC_MESSAGES/text.po
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.604283 hastexo-xblock-7.5.0/hastexo/translations/en/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.665878 hastexo-xblock-7.5.0/hastexo/translations/en/LC_MESSAGES/
--rw-r--r--   0 root         (0) staff       (20)      380 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/en/LC_MESSAGES/text.mo
--rw-r--r--   0 root         (0) staff       (20)     3409 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/en/LC_MESSAGES/text.po
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.604892 hastexo-xblock-7.5.0/hastexo/translations/es_419/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.667036 hastexo-xblock-7.5.0/hastexo/translations/es_419/LC_MESSAGES/
--rw-r--r--   0 root         (0) staff       (20)     3960 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/es_419/LC_MESSAGES/text.mo
--rw-r--r--   0 root         (0) staff       (20)     4983 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/es_419/LC_MESSAGES/text.po
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.605485 hastexo-xblock-7.5.0/hastexo/translations/et_EE/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.668099 hastexo-xblock-7.5.0/hastexo/translations/et_EE/LC_MESSAGES/
--rw-r--r--   0 root         (0) staff       (20)     3446 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/et_EE/LC_MESSAGES/text.mo
--rw-r--r--   0 root         (0) staff       (20)     4639 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/et_EE/LC_MESSAGES/text.po
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.606070 hastexo-xblock-7.5.0/hastexo/translations/hi/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.669153 hastexo-xblock-7.5.0/hastexo/translations/hi/LC_MESSAGES/
--rw-r--r--   0 root         (0) staff       (20)     5944 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/hi/LC_MESSAGES/text.mo
--rw-r--r--   0 root         (0) staff       (20)     6985 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/hastexo/translations/hi/LC_MESSAGES/text.po
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.670992 hastexo-xblock-7.5.0/hastexo_guacamole_client/
--rw-r--r--   0 root         (0) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo_guacamole_client/__init__.py
--rw-r--r--   0 root         (0) staff       (20)      896 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo_guacamole_client/asgi.py
--rw-r--r--   0 root         (0) staff       (20)     3347 2023-02-01 11:40:27.000000 hastexo-xblock-7.5.0/hastexo_guacamole_client/consumers.py
--rw-r--r--   0 root         (0) staff       (20)     2742 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/hastexo_guacamole_client/settings.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.673264 hastexo-xblock-7.5.0/hastexo_xblock.egg-info/
--rw-r--r--   0 root         (0) staff       (20)    35803 2023-03-15 14:45:48.000000 hastexo-xblock-7.5.0/hastexo_xblock.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) staff       (20)     4821 2023-03-15 14:45:48.000000 hastexo-xblock-7.5.0/hastexo_xblock.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) staff       (20)        1 2023-03-15 14:45:48.000000 hastexo-xblock-7.5.0/hastexo_xblock.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) staff       (20)       53 2023-03-15 14:45:48.000000 hastexo-xblock-7.5.0/hastexo_xblock.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) staff       (20)      138 2023-03-15 14:45:48.000000 hastexo-xblock-7.5.0/hastexo_xblock.egg-info/requires.txt
--rw-r--r--   0 root         (0) staff       (20)        8 2023-03-15 14:45:48.000000 hastexo-xblock-7.5.0/hastexo_xblock.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.675431 hastexo-xblock-7.5.0/requirements/
--rw-r--r--   0 root         (0) staff       (20)      654 2023-03-14 14:24:38.000000 hastexo-xblock-7.5.0/requirements/base.txt
--rw-r--r--   0 root         (0) staff       (20)        7 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/requirements/flake8.txt
--rw-r--r--   0 root         (0) staff       (20)       41 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/requirements/setup.txt
--rw-r--r--   0 root         (0) staff       (20)      359 2023-03-14 14:24:38.000000 hastexo-xblock-7.5.0/requirements/test.txt
--rw-r--r--   0 root         (0) staff       (20)      654 2023-03-14 14:24:38.000000 hastexo-xblock-7.5.0/requirements.txt
--rwxr-xr-x   0 root         (0) staff       (20)     2000 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/run_tests.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.608215 hastexo-xblock-7.5.0/samples/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.676164 hastexo-xblock-7.5.0/samples/gcloud/
--rw-r--r--   0 root         (0) staff       (20)     2198 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/samples/gcloud/sample-template.yaml.jinja
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.676713 hastexo-xblock-7.5.0/samples/hot/
--rw-r--r--   0 root         (0) staff       (20)    13209 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/samples/hot/sample-template.yaml
--rw-r--r--   0 root         (0) staff       (20)       38 2023-03-15 14:45:48.687470 hastexo-xblock-7.5.0/setup.cfg
--rwxr-xr-x   0 root         (0) staff       (20)     2372 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/setup.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.677256 hastexo-xblock-7.5.0/src/
--rw-r--r--   0 root         (0) staff       (20)      185 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/src/pip-delete-this-directory.txt
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.677746 hastexo-xblock-7.5.0/tests/
--rw-r--r--   0 root         (0) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/__init__.py
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.609519 hastexo-xblock-7.5.0/tests/resources/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.609726 hastexo-xblock-7.5.0/tests/resources/course/
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.681575 hastexo-xblock-7.5.0/tests/resources/course/hastexo/
--rw-r--r--   0 root         (0) staff       (20)      488 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/resources/course/hastexo/fake_lab_1.xml
--rw-r--r--   0 root         (0) staff       (20)      346 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/resources/course/hastexo/fake_lab_2.xml
--rw-r--r--   0 root         (0) staff       (20)       67 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/resources/course/hastexo/fake_lab_hook_events_1.xml
--rw-r--r--   0 root         (0) staff       (20)       69 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/resources/course/hastexo/fake_lab_hook_events_2.xml
--rw-r--r--   0 root         (0) staff       (20)       45 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/resources/course/hastexo/fake_lab_no_port_name.xml
--rw-r--r--   0 root         (0) staff       (20)       46 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/resources/course/hastexo/fake_lab_no_port_number.xml
--rw-r--r--   0 root         (0) staff       (20)      301 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/resources/course/hastexo/fake_lab_no_provider_capacity.xml
--rw-r--r--   0 root         (0) staff       (20)      101 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/resources/course/hastexo/fake_lab_no_provider_name.xml
-drwxr-xr-x   0 root         (0) staff       (20)        0 2023-03-15 14:45:48.686051 hastexo-xblock-7.5.0/tests/unit/
--rw-r--r--   0 root         (0) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/unit/__init__.py
--rw-r--r--   0 root         (0) staff       (20)     5947 2022-11-16 13:16:51.000000 hastexo-xblock-7.5.0/tests/unit/test_admin.py
--rw-r--r--   0 root         (0) staff       (20)      976 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/tests/unit/test_commands.py
--rw-r--r--   0 root         (0) staff       (20)     9861 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/tests/unit/test_common.py
--rw-r--r--   0 root         (0) staff       (20)     5062 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/tests/unit/test_gcloud.py
--rw-r--r--   0 root         (0) staff       (20)    61788 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/tests/unit/test_hastexo.py
--rw-r--r--   0 root         (0) staff       (20)    21787 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/tests/unit/test_jobs.py
--rw-r--r--   0 root         (0) staff       (20)     2623 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tests/unit/test_models.py
--rw-r--r--   0 root         (0) staff       (20)     6648 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/tests/unit/test_openstack.py
--rw-r--r--   0 root         (0) staff       (20)    67220 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/tests/unit/test_provider.py
--rw-r--r--   0 root         (0) staff       (20)    70209 2023-01-20 14:29:31.000000 hastexo-xblock-7.5.0/tests/unit/test_tasks.py
--rw-r--r--   0 root         (0) staff       (20)     1422 2022-11-03 14:17:07.000000 hastexo-xblock-7.5.0/tox.ini
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.853397 hastexo-xblock-7.6.0/
+-rw-r--r--   0 maaritamm   (501) staff       (20)      328 2023-06-26 15:16:51.000000 hastexo-xblock-7.6.0/.bumpversion.cfg
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.735396 hastexo-xblock-7.6.0/.githooks/
+-rwxr-xr-x   0 maaritamm   (501) staff       (20)       29 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/.githooks/pre-commit
+-rwxr-xr-x   0 maaritamm   (501) staff       (20)       19 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/.githooks/pre-push
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.712242 hastexo-xblock-7.6.0/.github/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.736180 hastexo-xblock-7.6.0/.github/workflows/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1669 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/.github/workflows/tox.yml
+-rw-r--r--   0 maaritamm   (501) staff       (20)       58 2022-12-02 10:31:03.000000 hastexo-xblock-7.6.0/.gitignore
+-rw-r--r--   0 maaritamm   (501) staff       (20)      681 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/.gitlab-ci.yml
+-rw-r--r--   0 maaritamm   (501) staff       (20)    27967 2023-06-26 15:16:51.000000 hastexo-xblock-7.6.0/Changelog.md
+-rw-r--r--   0 maaritamm   (501) staff       (20)     5452 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/HACKING.md
+-rw-r--r--   0 maaritamm   (501) staff       (20)    34520 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/LICENSE
+-rw-r--r--   0 maaritamm   (501) staff       (20)    35803 2023-06-28 10:04:35.852953 hastexo-xblock-7.6.0/PKG-INFO
+-rw-r--r--   0 maaritamm   (501) staff       (20)    28946 2023-06-26 14:48:36.000000 hastexo-xblock-7.6.0/README.md
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.713043 hastexo-xblock-7.6.0/fake/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.712719 hastexo-xblock-7.6.0/fake/common/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.712846 hastexo-xblock-7.6.0/fake/common/djangoapps/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.737420 hastexo-xblock-7.6.0/fake/common/djangoapps/student/
+-rw-r--r--   0 maaritamm   (501) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/fake/common/djangoapps/student/__init__.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)      443 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/fake/common/djangoapps/student/models.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.738447 hastexo-xblock-7.6.0/fake/course/
+-rw-r--r--   0 maaritamm   (501) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/fake/course/__init__.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.747423 hastexo-xblock-7.6.0/hastexo/
+-rw-r--r--   0 maaritamm   (501) staff       (20)      347 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/__init__.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     4167 2022-11-17 10:21:18.000000 hastexo-xblock-7.6.0/hastexo/admin.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)    11305 2023-06-26 14:48:36.000000 hastexo-xblock-7.6.0/hastexo/common.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1560 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/gcloud.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)    41166 2023-06-26 14:48:36.000000 hastexo-xblock-7.6.0/hastexo/hastexo.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     6099 2022-11-30 14:31:42.000000 hastexo-xblock-7.6.0/hastexo/jobs.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.750979 hastexo-xblock-7.6.0/hastexo/locale/
+-rw-r--r--   0 maaritamm   (501) staff       (20)      341 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/locale/config.yaml
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.713774 hastexo-xblock-7.6.0/hastexo/locale/en/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.752105 hastexo-xblock-7.6.0/hastexo/locale/en/LC_MESSAGES/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     3409 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/locale/en/LC_MESSAGES/django-partial.po
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.753811 hastexo-xblock-7.6.0/hastexo/management/
+-rw-r--r--   0 maaritamm   (501) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/management/__init__.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.754433 hastexo-xblock-7.6.0/hastexo/management/__pycache__/
+-rw-r--r--   0 maaritamm   (501) staff       (20)      158 2022-11-03 15:09:41.000000 hastexo-xblock-7.6.0/hastexo/management/__pycache__/__init__.cpython-38.pyc
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.757187 hastexo-xblock-7.6.0/hastexo/management/commands/
+-rw-r--r--   0 maaritamm   (501) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/management/commands/__init__.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.760571 hastexo-xblock-7.6.0/hastexo/management/commands/__pycache__/
+-rw-r--r--   0 maaritamm   (501) staff       (20)      167 2022-11-03 15:09:41.000000 hastexo-xblock-7.6.0/hastexo/management/commands/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      994 2022-11-03 15:09:41.000000 hastexo-xblock-7.6.0/hastexo/management/commands/__pycache__/reaper.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      925 2022-11-03 15:09:41.000000 hastexo-xblock-7.6.0/hastexo/management/commands/__pycache__/suspender.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      708 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/management/commands/reaper.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)      639 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/management/commands/suspender.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.774948 hastexo-xblock-7.6.0/hastexo/migrations/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1900 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0001_initial.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     2016 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0002_stacklog.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     2596 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0003_blanks.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)      560 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0004_auto_20190715_1053.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1647 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0005_auto_20190811_1555.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1469 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0006_auto_20200107_1332.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1034 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0007_add_delete_by_and_delete_age.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)      581 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0008_add_database_defaults_for_stack_key_and_password.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)      599 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0009_add_null_true_for_key_and_password.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1748 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0010_add_user_foreign_key.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1018 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0011_allow_null_for_learner.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)      529 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/0012_add_suspend_by.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/migrations/__init__.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.787951 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1411 2022-11-03 15:10:42.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0001_initial.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1486 2022-11-03 15:10:42.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0002_stacklog.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1267 2022-11-03 15:10:43.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0003_blanks.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      750 2022-11-03 15:10:43.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0004_auto_20190715_1053.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1089 2022-11-03 15:10:42.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0005_auto_20190811_1555.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1202 2022-11-03 15:10:43.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0006_auto_20200107_1332.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      895 2022-11-03 15:10:42.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0007_add_delete_by_and_delete_age.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      778 2022-11-03 15:10:43.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0008_add_database_defaults_for_stack_key_and_password.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      779 2022-11-03 15:10:42.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0009_add_null_true_for_key_and_password.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1670 2022-11-03 15:10:42.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0010_add_user_foreign_key.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      844 2022-11-03 15:10:42.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0011_allow_null_for_learner.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      703 2022-11-03 15:10:42.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0012_add_suspend_by.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)      213 2022-11-03 15:10:42.000000 hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/__init__.cpython-38.pyc
+-rw-r--r--   0 maaritamm   (501) staff       (20)     3644 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/models.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     4614 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/openstack.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)    27375 2022-11-23 14:17:13.000000 hastexo-xblock-7.6.0/hastexo/provider.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.715468 hastexo-xblock-7.6.0/hastexo/public/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.789403 hastexo-xblock-7.6.0/hastexo/public/css/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     3279 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/public/css/main.css
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.793746 hastexo-xblock-7.6.0/hastexo/public/js/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.798877 hastexo-xblock-7.6.0/hastexo/public/js/guacamole-common-js/
+-rw-r--r--   0 maaritamm   (501) staff       (20)    67952 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/public/js/guacamole-common-js/0.9.13-incubating-all.min.js
+-rw-r--r--   0 maaritamm   (501) staff       (20)    70401 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/public/js/guacamole-common-js/1.4.0-all.min.js
+-rw-r--r--   0 maaritamm   (501) staff       (20)    72449 2023-06-26 14:48:36.000000 hastexo-xblock-7.6.0/hastexo/public/js/guacamole-common-js/1.5.2-all.min.js
+-rw-r--r--   0 maaritamm   (501) staff       (20)    26635 2023-03-14 14:24:38.000000 hastexo-xblock-7.6.0/hastexo/public/js/main.js
+-rw-r--r--   0 maaritamm   (501) staff       (20)     2344 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo/public/js/plugins.js
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.716854 hastexo-xblock-7.6.0/hastexo/public/js/translations/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.800372 hastexo-xblock-7.6.0/hastexo/public/js/translations/de-de/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     6974 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/public/js/translations/de-de/text.js
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.801351 hastexo-xblock-7.6.0/hastexo/public/js/translations/el/
+-rw-r--r--   0 maaritamm   (501) staff       (20)    13551 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/public/js/translations/el/text.js
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.802256 hastexo-xblock-7.6.0/hastexo/public/js/translations/es-419/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     6742 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/public/js/translations/es-419/text.js
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.803167 hastexo-xblock-7.6.0/hastexo/public/js/translations/et-ee/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     6695 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/public/js/translations/et-ee/text.js
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.804569 hastexo-xblock-7.6.0/hastexo/public/js/translations/hi/
+-rw-r--r--   0 maaritamm   (501) staff       (20)    12293 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/public/js/translations/hi/text.js
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.717263 hastexo-xblock-7.6.0/hastexo/static/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.805679 hastexo-xblock-7.6.0/hastexo/static/html/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     3301 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/static/html/main.html
+-rw-r--r--   0 maaritamm   (501) staff       (20)    34430 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/tasks.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.719816 hastexo-xblock-7.6.0/hastexo/translations/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.717785 hastexo-xblock-7.6.0/hastexo/translations/de_DE/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.808141 hastexo-xblock-7.6.0/hastexo/translations/de_DE/LC_MESSAGES/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     3982 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/de_DE/LC_MESSAGES/text.mo
+-rw-r--r--   0 maaritamm   (501) staff       (20)     5005 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/de_DE/LC_MESSAGES/text.po
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.718152 hastexo-xblock-7.6.0/hastexo/translations/el/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.810380 hastexo-xblock-7.6.0/hastexo/translations/el/LC_MESSAGES/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     5293 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/el/LC_MESSAGES/text.mo
+-rw-r--r--   0 maaritamm   (501) staff       (20)     6358 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/el/LC_MESSAGES/text.po
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.718665 hastexo-xblock-7.6.0/hastexo/translations/en/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.812539 hastexo-xblock-7.6.0/hastexo/translations/en/LC_MESSAGES/
+-rw-r--r--   0 maaritamm   (501) staff       (20)      380 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/en/LC_MESSAGES/text.mo
+-rw-r--r--   0 maaritamm   (501) staff       (20)     3409 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/en/LC_MESSAGES/text.po
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.719137 hastexo-xblock-7.6.0/hastexo/translations/es_419/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.814456 hastexo-xblock-7.6.0/hastexo/translations/es_419/LC_MESSAGES/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     3960 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/es_419/LC_MESSAGES/text.mo
+-rw-r--r--   0 maaritamm   (501) staff       (20)     4983 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/es_419/LC_MESSAGES/text.po
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.719546 hastexo-xblock-7.6.0/hastexo/translations/et_EE/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.816406 hastexo-xblock-7.6.0/hastexo/translations/et_EE/LC_MESSAGES/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     3446 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/et_EE/LC_MESSAGES/text.mo
+-rw-r--r--   0 maaritamm   (501) staff       (20)     4639 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/et_EE/LC_MESSAGES/text.po
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.720007 hastexo-xblock-7.6.0/hastexo/translations/hi/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.818131 hastexo-xblock-7.6.0/hastexo/translations/hi/LC_MESSAGES/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     5944 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/hi/LC_MESSAGES/text.mo
+-rw-r--r--   0 maaritamm   (501) staff       (20)     6985 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/hastexo/translations/hi/LC_MESSAGES/text.po
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.821850 hastexo-xblock-7.6.0/hastexo_guacamole_client/
+-rw-r--r--   0 maaritamm   (501) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo_guacamole_client/__init__.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)      896 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo_guacamole_client/asgi.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     3347 2023-02-01 11:40:27.000000 hastexo-xblock-7.6.0/hastexo_guacamole_client/consumers.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     2742 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/hastexo_guacamole_client/settings.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.827055 hastexo-xblock-7.6.0/hastexo_xblock.egg-info/
+-rw-r--r--   0 maaritamm   (501) staff       (20)    35803 2023-06-28 10:04:35.000000 hastexo-xblock-7.6.0/hastexo_xblock.egg-info/PKG-INFO
+-rw-r--r--   0 maaritamm   (501) staff       (20)     4876 2023-06-28 10:04:35.000000 hastexo-xblock-7.6.0/hastexo_xblock.egg-info/SOURCES.txt
+-rw-r--r--   0 maaritamm   (501) staff       (20)        1 2023-06-28 10:04:35.000000 hastexo-xblock-7.6.0/hastexo_xblock.egg-info/dependency_links.txt
+-rw-r--r--   0 maaritamm   (501) staff       (20)       53 2023-06-28 10:04:35.000000 hastexo-xblock-7.6.0/hastexo_xblock.egg-info/entry_points.txt
+-rw-r--r--   0 maaritamm   (501) staff       (20)      138 2023-06-28 10:04:35.000000 hastexo-xblock-7.6.0/hastexo_xblock.egg-info/requires.txt
+-rw-r--r--   0 maaritamm   (501) staff       (20)        8 2023-06-28 10:04:35.000000 hastexo-xblock-7.6.0/hastexo_xblock.egg-info/top_level.txt
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.830633 hastexo-xblock-7.6.0/requirements/
+-rw-r--r--   0 maaritamm   (501) staff       (20)      654 2023-03-14 14:24:38.000000 hastexo-xblock-7.6.0/requirements/base.txt
+-rw-r--r--   0 maaritamm   (501) staff       (20)        7 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/requirements/flake8.txt
+-rw-r--r--   0 maaritamm   (501) staff       (20)       41 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/requirements/setup.txt
+-rw-r--r--   0 maaritamm   (501) staff       (20)      359 2023-03-14 14:24:38.000000 hastexo-xblock-7.6.0/requirements/test.txt
+-rw-r--r--   0 maaritamm   (501) staff       (20)      654 2023-03-14 14:24:38.000000 hastexo-xblock-7.6.0/requirements.txt
+-rwxr-xr-x   0 maaritamm   (501) staff       (20)     2000 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/run_tests.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.721997 hastexo-xblock-7.6.0/samples/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.831520 hastexo-xblock-7.6.0/samples/gcloud/
+-rw-r--r--   0 maaritamm   (501) staff       (20)     2198 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/samples/gcloud/sample-template.yaml.jinja
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.832408 hastexo-xblock-7.6.0/samples/hot/
+-rw-r--r--   0 maaritamm   (501) staff       (20)    13209 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/samples/hot/sample-template.yaml
+-rw-r--r--   0 maaritamm   (501) staff       (20)       38 2023-06-28 10:04:35.853579 hastexo-xblock-7.6.0/setup.cfg
+-rwxr-xr-x   0 maaritamm   (501) staff       (20)     2372 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/setup.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.833229 hastexo-xblock-7.6.0/src/
+-rw-r--r--   0 maaritamm   (501) staff       (20)      185 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/src/pip-delete-this-directory.txt
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.834058 hastexo-xblock-7.6.0/tests/
+-rw-r--r--   0 maaritamm   (501) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/__init__.py
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.723225 hastexo-xblock-7.6.0/tests/resources/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.723451 hastexo-xblock-7.6.0/tests/resources/course/
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.840788 hastexo-xblock-7.6.0/tests/resources/course/hastexo/
+-rw-r--r--   0 maaritamm   (501) staff       (20)      488 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/resources/course/hastexo/fake_lab_1.xml
+-rw-r--r--   0 maaritamm   (501) staff       (20)      346 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/resources/course/hastexo/fake_lab_2.xml
+-rw-r--r--   0 maaritamm   (501) staff       (20)       67 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/resources/course/hastexo/fake_lab_hook_events_1.xml
+-rw-r--r--   0 maaritamm   (501) staff       (20)       69 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/resources/course/hastexo/fake_lab_hook_events_2.xml
+-rw-r--r--   0 maaritamm   (501) staff       (20)       45 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/resources/course/hastexo/fake_lab_no_port_name.xml
+-rw-r--r--   0 maaritamm   (501) staff       (20)       46 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/resources/course/hastexo/fake_lab_no_port_number.xml
+-rw-r--r--   0 maaritamm   (501) staff       (20)      301 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/resources/course/hastexo/fake_lab_no_provider_capacity.xml
+-rw-r--r--   0 maaritamm   (501) staff       (20)      101 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/resources/course/hastexo/fake_lab_no_provider_name.xml
+drwxr-xr-x   0 maaritamm   (501) staff       (20)        0 2023-06-28 10:04:35.851143 hastexo-xblock-7.6.0/tests/unit/
+-rw-r--r--   0 maaritamm   (501) staff       (20)        0 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/unit/__init__.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     5947 2022-11-16 13:16:51.000000 hastexo-xblock-7.6.0/tests/unit/test_admin.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)      976 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/tests/unit/test_commands.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     9861 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/tests/unit/test_common.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     5062 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/tests/unit/test_gcloud.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)    61788 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/tests/unit/test_hastexo.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)    21787 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/tests/unit/test_jobs.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     2623 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tests/unit/test_models.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     6648 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/tests/unit/test_openstack.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)    67220 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/tests/unit/test_provider.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)    70209 2023-01-20 14:29:31.000000 hastexo-xblock-7.6.0/tests/unit/test_tasks.py
+-rw-r--r--   0 maaritamm   (501) staff       (20)     1422 2022-11-03 14:17:07.000000 hastexo-xblock-7.6.0/tox.ini
```

### Comparing `hastexo-xblock-7.5.0/.github/workflows/tox.yml` & `hastexo-xblock-7.6.0/.github/workflows/tox.yml`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/.gitlab-ci.yml` & `hastexo-xblock-7.6.0/.gitlab-ci.yml`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/Changelog.md` & `hastexo-xblock-7.6.0/Changelog.md`

 * *Files 0% similar despite different names*

```diff
@@ -1,7 +1,12 @@
+Version 7.6.0 (2023-06-26)
+-------------------------
+* [Enhancement] Add support for Apache Guacamole 1.5.2;
+  make it the new default version.
+
 Version 7.5.0 (2023-03-14)
 -------------------------
 * [Enhancement] Update requirements for Open edX Olive release.
 
 Version 7.4.0 (2023-02-20)
 -------------------------
 * [Bug fix] Restore the `paste` functionality by addressing
```

### Comparing `hastexo-xblock-7.5.0/HACKING.md` & `hastexo-xblock-7.6.0/HACKING.md`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/LICENSE` & `hastexo-xblock-7.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/PKG-INFO` & `hastexo-xblock-7.6.0/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hastexo-xblock
-Version: 7.5.0
+Version: 7.6.0
 Summary: hastexo XBlock: Makes arbitrarily complex lab environments available on an Open edX LMS
 Home-page: https://github.com/hastexo/hastexo-xblock
 Author: hastexo
 Author-email: pypi@hastexo.com
 License: AGPL-3.0
 Description: [![PyPI version](https://badge.fury.io/py/hastexo-xblock.svg)](https://pypi.python.org/pypi/hastexo-xblock)
         [![Build Status](https://github.com/hastexo/hastexo-xblock/workflows/Python%20package/badge.svg)](https://github.com/hastexo/hastexo-xblock/actions?query=workflow%3A%22Python+package%22) [![codecov](https://codecov.io/gh/hastexo/hastexo-xblock/branch/master/graph/badge.svg)](https://codecov.io/gh/hastexo/hastexo-xblock)
@@ -86,15 +86,15 @@
            ```
            HASTEXO_XBLOCK_SETTINGS:
              check_timeout: 120
              delete_age: 0
              delete_attempts: 3
              delete_interval: 3600
              delete_task_timeout: 900
-             guacamole_js_version: 1.4.0
+             guacamole_js_version: 1.5.2
              instructions_layout: above
              js_timeouts:
                check: 5000
                idle: 3600000
                keepalive: 30000
                status: 15000
              launch_timeout: 900
```

### Comparing `hastexo-xblock-7.5.0/README.md` & `hastexo-xblock-7.6.0/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -78,15 +78,15 @@
    ```
    HASTEXO_XBLOCK_SETTINGS:
      check_timeout: 120
      delete_age: 0
      delete_attempts: 3
      delete_interval: 3600
      delete_task_timeout: 900
-     guacamole_js_version: 1.4.0
+     guacamole_js_version: 1.5.2
      instructions_layout: above
      js_timeouts:
        check: 5000
        idle: 3600000
        keepalive: 30000
        status: 15000
      launch_timeout: 900
```

### Comparing `hastexo-xblock-7.5.0/hastexo/admin.py` & `hastexo-xblock-7.6.0/hastexo/admin.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/common.py` & `hastexo-xblock-7.6.0/hastexo/common.py`

 * *Files 0% similar despite different names*

```diff
@@ -177,15 +177,15 @@
     "js_timeouts": {
         "status": 15000,
         "keepalive": 30000,
         "idle": 3600000,
         "check": 5000
     },
     "providers": {},
-    "guacamole_js_version": '1.4.0',
+    "guacamole_js_version": '1.5.2',
     "lab_usage_limit": None,
     "lab_usage_limit_breach_policy": None
 }
 
 SUPPORTED_LANGUAGES = [
     'en',  # English
     'de-de',  # Deutsch (Deutschland), German (Germany)
```

### Comparing `hastexo-xblock-7.5.0/hastexo/gcloud.py` & `hastexo-xblock-7.6.0/hastexo/gcloud.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/hastexo.py` & `hastexo-xblock-7.6.0/hastexo/hastexo.py`

 * *Files 0% similar despite different names*

```diff
@@ -613,15 +613,15 @@
             self.runtime.local_resource_url(self, 'public/js/main.js')
         )
         text_js_url = self._get_text_js_url()
         if text_js_url:
             frag.add_javascript_url(
                 self.runtime.local_resource_url(self, text_js_url)
             )
-        guac_js_version = settings.get("guacamole_js_version", "1.4.0")
+        guac_js_version = settings.get("guacamole_js_version", "1.5.2")
         frag.add_javascript_url(
             self.runtime.local_resource_url(
                 self,
                 f'public/js/guacamole-common-js/{guac_js_version}-all.min.js')
         )
 
         # Create the stack in the database
```

### Comparing `hastexo-xblock-7.5.0/hastexo/jobs.py` & `hastexo-xblock-7.6.0/hastexo/jobs.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/locale/en/LC_MESSAGES/django-partial.po` & `hastexo-xblock-7.6.0/hastexo/locale/en/LC_MESSAGES/django-partial.po`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/management/commands/__pycache__/reaper.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/management/commands/__pycache__/reaper.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/management/commands/__pycache__/suspender.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/management/commands/__pycache__/suspender.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/management/commands/reaper.py` & `hastexo-xblock-7.6.0/hastexo/management/commands/reaper.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/management/commands/suspender.py` & `hastexo-xblock-7.6.0/hastexo/management/commands/suspender.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0001_initial.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0002_stacklog.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0002_stacklog.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0003_blanks.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0003_blanks.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0004_auto_20190715_1053.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0004_auto_20190715_1053.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0005_auto_20190811_1555.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0005_auto_20190811_1555.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0006_auto_20200107_1332.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0006_auto_20200107_1332.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0007_add_delete_by_and_delete_age.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0007_add_delete_by_and_delete_age.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0008_add_database_defaults_for_stack_key_and_password.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0008_add_database_defaults_for_stack_key_and_password.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0009_add_null_true_for_key_and_password.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0009_add_null_true_for_key_and_password.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0010_add_user_foreign_key.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0010_add_user_foreign_key.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0011_allow_null_for_learner.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0011_allow_null_for_learner.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/0012_add_suspend_by.py` & `hastexo-xblock-7.6.0/hastexo/migrations/0012_add_suspend_by.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0001_initial.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0001_initial.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0002_stacklog.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0002_stacklog.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0003_blanks.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0003_blanks.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0004_auto_20190715_1053.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0004_auto_20190715_1053.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0005_auto_20190811_1555.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0005_auto_20190811_1555.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0006_auto_20200107_1332.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0006_auto_20200107_1332.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0007_add_delete_by_and_delete_age.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0007_add_delete_by_and_delete_age.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0008_add_database_defaults_for_stack_key_and_password.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0008_add_database_defaults_for_stack_key_and_password.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0009_add_null_true_for_key_and_password.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0009_add_null_true_for_key_and_password.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0010_add_user_foreign_key.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0010_add_user_foreign_key.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0011_allow_null_for_learner.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0011_allow_null_for_learner.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/migrations/__pycache__/0012_add_suspend_by.cpython-38.pyc` & `hastexo-xblock-7.6.0/hastexo/migrations/__pycache__/0012_add_suspend_by.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/models.py` & `hastexo-xblock-7.6.0/hastexo/models.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/openstack.py` & `hastexo-xblock-7.6.0/hastexo/openstack.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/provider.py` & `hastexo-xblock-7.6.0/hastexo/provider.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/css/main.css` & `hastexo-xblock-7.6.0/hastexo/public/css/main.css`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/js/guacamole-common-js/0.9.13-incubating-all.min.js` & `hastexo-xblock-7.6.0/hastexo/public/js/guacamole-common-js/0.9.13-incubating-all.min.js`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/js/guacamole-common-js/1.4.0-all.min.js` & `hastexo-xblock-7.6.0/hastexo/public/js/guacamole-common-js/1.4.0-all.min.js`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/js/main.js` & `hastexo-xblock-7.6.0/hastexo/public/js/main.js`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/js/plugins.js` & `hastexo-xblock-7.6.0/hastexo/public/js/plugins.js`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/js/translations/de-de/text.js` & `hastexo-xblock-7.6.0/hastexo/public/js/translations/de-de/text.js`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/js/translations/el/text.js` & `hastexo-xblock-7.6.0/hastexo/public/js/translations/el/text.js`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/js/translations/es-419/text.js` & `hastexo-xblock-7.6.0/hastexo/public/js/translations/es-419/text.js`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/js/translations/et-ee/text.js` & `hastexo-xblock-7.6.0/hastexo/public/js/translations/et-ee/text.js`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/public/js/translations/hi/text.js` & `hastexo-xblock-7.6.0/hastexo/public/js/translations/hi/text.js`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/static/html/main.html` & `hastexo-xblock-7.6.0/hastexo/static/html/main.html`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/tasks.py` & `hastexo-xblock-7.6.0/hastexo/tasks.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/de_DE/LC_MESSAGES/text.mo` & `hastexo-xblock-7.6.0/hastexo/translations/de_DE/LC_MESSAGES/text.mo`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/de_DE/LC_MESSAGES/text.po` & `hastexo-xblock-7.6.0/hastexo/translations/de_DE/LC_MESSAGES/text.po`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/el/LC_MESSAGES/text.mo` & `hastexo-xblock-7.6.0/hastexo/translations/el/LC_MESSAGES/text.mo`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/el/LC_MESSAGES/text.po` & `hastexo-xblock-7.6.0/hastexo/translations/el/LC_MESSAGES/text.po`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/en/LC_MESSAGES/text.po` & `hastexo-xblock-7.6.0/hastexo/translations/en/LC_MESSAGES/text.po`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/es_419/LC_MESSAGES/text.mo` & `hastexo-xblock-7.6.0/hastexo/translations/es_419/LC_MESSAGES/text.mo`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/es_419/LC_MESSAGES/text.po` & `hastexo-xblock-7.6.0/hastexo/translations/es_419/LC_MESSAGES/text.po`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/et_EE/LC_MESSAGES/text.mo` & `hastexo-xblock-7.6.0/hastexo/translations/et_EE/LC_MESSAGES/text.mo`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/et_EE/LC_MESSAGES/text.po` & `hastexo-xblock-7.6.0/hastexo/translations/et_EE/LC_MESSAGES/text.po`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/hi/LC_MESSAGES/text.mo` & `hastexo-xblock-7.6.0/hastexo/translations/hi/LC_MESSAGES/text.mo`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo/translations/hi/LC_MESSAGES/text.po` & `hastexo-xblock-7.6.0/hastexo/translations/hi/LC_MESSAGES/text.po`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo_guacamole_client/asgi.py` & `hastexo-xblock-7.6.0/hastexo_guacamole_client/asgi.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo_guacamole_client/consumers.py` & `hastexo-xblock-7.6.0/hastexo_guacamole_client/consumers.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo_guacamole_client/settings.py` & `hastexo-xblock-7.6.0/hastexo_guacamole_client/settings.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/hastexo_xblock.egg-info/PKG-INFO` & `hastexo-xblock-7.6.0/hastexo_xblock.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hastexo-xblock
-Version: 7.5.0
+Version: 7.6.0
 Summary: hastexo XBlock: Makes arbitrarily complex lab environments available on an Open edX LMS
 Home-page: https://github.com/hastexo/hastexo-xblock
 Author: hastexo
 Author-email: pypi@hastexo.com
 License: AGPL-3.0
 Description: [![PyPI version](https://badge.fury.io/py/hastexo-xblock.svg)](https://pypi.python.org/pypi/hastexo-xblock)
         [![Build Status](https://github.com/hastexo/hastexo-xblock/workflows/Python%20package/badge.svg)](https://github.com/hastexo/hastexo-xblock/actions?query=workflow%3A%22Python+package%22) [![codecov](https://codecov.io/gh/hastexo/hastexo-xblock/branch/master/graph/badge.svg)](https://codecov.io/gh/hastexo/hastexo-xblock)
@@ -86,15 +86,15 @@
            ```
            HASTEXO_XBLOCK_SETTINGS:
              check_timeout: 120
              delete_age: 0
              delete_attempts: 3
              delete_interval: 3600
              delete_task_timeout: 900
-             guacamole_js_version: 1.4.0
+             guacamole_js_version: 1.5.2
              instructions_layout: above
              js_timeouts:
                check: 5000
                idle: 3600000
                keepalive: 30000
                status: 15000
              launch_timeout: 900
```

### Comparing `hastexo-xblock-7.5.0/hastexo_xblock.egg-info/SOURCES.txt` & `hastexo-xblock-7.6.0/hastexo_xblock.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -62,14 +62,15 @@
 hastexo/migrations/__pycache__/0012_add_suspend_by.cpython-38.pyc
 hastexo/migrations/__pycache__/__init__.cpython-38.pyc
 hastexo/public/css/main.css
 hastexo/public/js/main.js
 hastexo/public/js/plugins.js
 hastexo/public/js/guacamole-common-js/0.9.13-incubating-all.min.js
 hastexo/public/js/guacamole-common-js/1.4.0-all.min.js
+hastexo/public/js/guacamole-common-js/1.5.2-all.min.js
 hastexo/public/js/translations/de-de/text.js
 hastexo/public/js/translations/el/text.js
 hastexo/public/js/translations/es-419/text.js
 hastexo/public/js/translations/et-ee/text.js
 hastexo/public/js/translations/hi/text.js
 hastexo/static/html/main.html
 hastexo/translations/de_DE/LC_MESSAGES/text.mo
```

### Comparing `hastexo-xblock-7.5.0/requirements/base.txt` & `hastexo-xblock-7.6.0/requirements/base.txt`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/requirements.txt` & `hastexo-xblock-7.6.0/requirements.txt`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/run_tests.py` & `hastexo-xblock-7.6.0/run_tests.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/samples/gcloud/sample-template.yaml.jinja` & `hastexo-xblock-7.6.0/samples/gcloud/sample-template.yaml.jinja`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/samples/hot/sample-template.yaml` & `hastexo-xblock-7.6.0/samples/hot/sample-template.yaml`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/setup.py` & `hastexo-xblock-7.6.0/setup.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_admin.py` & `hastexo-xblock-7.6.0/tests/unit/test_admin.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_commands.py` & `hastexo-xblock-7.6.0/tests/unit/test_commands.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_common.py` & `hastexo-xblock-7.6.0/tests/unit/test_common.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_gcloud.py` & `hastexo-xblock-7.6.0/tests/unit/test_gcloud.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_hastexo.py` & `hastexo-xblock-7.6.0/tests/unit/test_hastexo.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_jobs.py` & `hastexo-xblock-7.6.0/tests/unit/test_jobs.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_models.py` & `hastexo-xblock-7.6.0/tests/unit/test_models.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_openstack.py` & `hastexo-xblock-7.6.0/tests/unit/test_openstack.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_provider.py` & `hastexo-xblock-7.6.0/tests/unit/test_provider.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tests/unit/test_tasks.py` & `hastexo-xblock-7.6.0/tests/unit/test_tasks.py`

 * *Files identical despite different names*

### Comparing `hastexo-xblock-7.5.0/tox.ini` & `hastexo-xblock-7.6.0/tox.ini`

 * *Files identical despite different names*


# Comparing `tmp/sosse-1.0.1.tar.gz` & `tmp/sosse-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sosse-1.0.1.tar", last modified: Mon May  1 14:24:43 2023, max compression
+gzip compressed data, was "sosse-1.1.0.tar", last modified: Wed Jun 28 15:15:25 2023, max compression
```

## Comparing `sosse-1.0.1.tar` & `sosse-1.1.0.tar`

### file list

```diff
@@ -1,222 +1,229 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.499637 sosse-1.0.1/
--rw-rw-rw-   0 root         (0) root         (0)       30 2023-05-01 14:24:18.000000 sosse-1.0.1/.coveragerc
--rw-rw-rw-   0 root         (0) root         (0)      276 2023-05-01 14:24:18.000000 sosse-1.0.1/.gitignore
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.383640 sosse-1.0.1/.gitlab/
--rw-rw-rw-   0 root         (0) root         (0)       80 2023-05-01 14:24:18.000000 sosse-1.0.1/.gitlab/changelog_config.yml
--rw-rw-rw-   0 root         (0) root         (0)     6965 2023-05-01 14:24:18.000000 sosse-1.0.1/.gitlab-ci.yml
--rw-rw-rw-   0 root         (0) root         (0)      491 2023-05-01 14:24:18.000000 sosse-1.0.1/.readthedocs.yaml
--rw-rw-rw-   0 root         (0) root         (0)      253 2023-05-01 14:24:18.000000 sosse-1.0.1/CHANGELOG.md
--rw-rw-rw-   0 root         (0) root         (0)     1529 2023-05-01 14:24:18.000000 sosse-1.0.1/Dockerfile
--rw-rw-rw-   0 root         (0) root         (0)    34523 2023-05-01 14:24:18.000000 sosse-1.0.1/LICENSE
--rw-rw-rw-   0 root         (0) root         (0)      112 2023-05-01 14:24:18.000000 sosse-1.0.1/MANIFEST.in
--rw-rw-rw-   0 root         (0) root         (0)     7527 2023-05-01 14:24:18.000000 sosse-1.0.1/Makefile
--rw-r--r--   0 root         (0) root         (0)     3182 2023-05-01 14:24:43.499637 sosse-1.0.1/PKG-INFO
--rw-rw-rw-   0 root         (0) root         (0)     2790 2023-05-01 14:24:18.000000 sosse-1.0.1/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.391639 sosse-1.0.1/debian/
--rw-rw-rw-   0 root         (0) root         (0)      284 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/changelog
--rw-rw-rw-   0 root         (0) root         (0)        3 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/compat
--rw-rw-rw-   0 root         (0) root         (0)      710 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/control
--rwxrwxrwx   0 root         (0) root         (0)      182 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/rules
--rw-rw-rw-   0 root         (0) root         (0)      719 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/sosse-crawler.service
--rw-rw-rw-   0 root         (0) root         (0)      803 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/sosse-uwsgi.service
--rw-rw-rw-   0 root         (0) root         (0)     2176 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/sosse.conf
--rw-rw-rw-   0 root         (0) root         (0)      196 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/sosse.install
--rw-rw-rw-   0 root         (0) root         (0)     2733 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/sosse.postinst
--rw-rw-rw-   0 root         (0) root         (0)      465 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/uwsgi.ini
--rw-rw-rw-   0 root         (0) root         (0)      664 2023-05-01 14:24:18.000000 sosse-1.0.1/debian/uwsgi.params
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.395639 sosse-1.0.1/doc/
--rw-rw-rw-   0 root         (0) root         (0)      638 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/Makefile
--rwxrwxrwx   0 root         (0) root         (0)      314 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/build_changelog.sh
--rw-rw-rw-   0 root         (0) root         (0)     1897 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/get_artifacts.py
--rw-rw-rw-   0 root         (0) root         (0)      804 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/make.bat
--rw-rw-rw-   0 root         (0) root         (0)       40 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/requirements.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.403639 sosse-1.0.1/doc/source/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.403639 sosse-1.0.1/doc/source/_extensions/
--rw-rw-rw-   0 root         (0) root         (0)     1124 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/_extensions/code_blocks.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.403639 sosse-1.0.1/doc/source/_static/
--rw-rw-rw-   0 root         (0) root         (0)      262 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/_static/style.css
--rw-rw-rw-   0 root         (0) root         (0)      723 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/admin_ui.rst
--rw-rw-rw-   0 root         (0) root         (0)      332 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/administration.rst
--rw-rw-rw-   0 root         (0) root         (0)      839 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/authentication.rst
--rw-rw-rw-   0 root         (0) root         (0)      433 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/cli.rst
--rw-rw-rw-   0 root         (0) root         (0)     1951 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/conf.py
--rw-rw-rw-   0 root         (0) root         (0)      360 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/config_file.rst
--rw-rw-rw-   0 root         (0) root         (0)      323 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/cookies.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.407639 sosse-1.0.1/doc/source/crawl/
--rw-rw-rw-   0 root         (0) root         (0)      560 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/crawl/add_to_queue.rst
--rw-rw-rw-   0 root         (0) root         (0)     1452 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/crawl/crawl_depth.rst
--rw-rw-rw-   0 root         (0) root         (0)     5773 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/crawl/policies.rst
--rw-rw-rw-   0 root         (0) root         (0)      316 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/crawl/status.rst
--rw-rw-rw-   0 root         (0) root         (0)     1210 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/documents.rst
--rw-rw-rw-   0 root         (0) root         (0)     1408 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/domain_settings.rst
--rw-rw-rw-   0 root         (0) root         (0)      315 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/excluded_urls.rst
--rw-rw-rw-   0 root         (0) root         (0)      531 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/index.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.411639 sosse-1.0.1/doc/source/install/
--rw-rw-rw-   0 root         (0) root         (0)      877 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/install/database.rst
--rw-rw-rw-   0 root         (0) root         (0)     1832 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/install/debian.rst
--rw-rw-rw-   0 root         (0) root         (0)      255 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/install/debian_upgrades.rst
--rw-rw-rw-   0 root         (0) root         (0)     1154 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/install/docker.rst
--rw-rw-rw-   0 root         (0) root         (0)      261 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/install/docker_upgrades.rst
--rw-rw-rw-   0 root         (0) root         (0)     3287 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/install/pip.rst
--rw-rw-rw-   0 root         (0) root         (0)      450 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/install/pip_upgrades.rst
--rw-rw-rw-   0 root         (0) root         (0)      287 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/install.rst
--rw-rw-rw-   0 root         (0) root         (0)      988 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/permissions.rst
--rw-rw-rw-   0 root         (0) root         (0)      989 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/screenshots.rst
--rw-rw-rw-   0 root         (0) root         (0)      980 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/search_engines.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.415639 sosse-1.0.1/doc/source/user/
--rw-rw-rw-   0 root         (0) root         (0)      823 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/user/cached.rst
--rw-rw-rw-   0 root         (0) root         (0)      593 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/user/history.rst
--rw-rw-rw-   0 root         (0) root         (0)     1407 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/user/preferences.rst
--rw-rw-rw-   0 root         (0) root         (0)     4293 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/user/search.rst
--rw-rw-rw-   0 root         (0) root         (0)      253 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/user/shortcut_list.rst
--rw-rw-rw-   0 root         (0) root         (0)     1043 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/user/shortcuts.rst
--rw-rw-rw-   0 root         (0) root         (0)      201 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/user/statistics.rst
--rw-rw-rw-   0 root         (0) root         (0)      245 2023-05-01 14:24:18.000000 sosse-1.0.1/doc/source/user_doc.rst
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.419639 sosse-1.0.1/docker/
--rw-rw-rw-   0 root         (0) root         (0)      882 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/Makefile
--rw-rw-rw-   0 root         (0) root         (0)      334 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/Makefile.common
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.419639 sosse-1.0.1/docker/debian/
--rw-rw-rw-   0 root         (0) root         (0)     2128 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/debian/Dockerfile
--rw-rw-rw-   0 root         (0) root         (0)       46 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/debian/Makefile
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.419639 sosse-1.0.1/docker/debian-pkg/
--rw-rw-rw-   0 root         (0) root         (0)      540 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/debian-pkg/Dockerfile
--rw-rw-rw-   0 root         (0) root         (0)       27 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/debian-pkg/Makefile
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.423639 sosse-1.0.1/docker/debian-test/
--rw-rw-rw-   0 root         (0) root         (0)     1185 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/debian-test/Dockerfile
--rw-rw-rw-   0 root         (0) root         (0)      138 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/debian-test/Makefile
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.423639 sosse-1.0.1/docker/doc/
--rw-rw-rw-   0 root         (0) root         (0)      449 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/doc/Dockerfile
--rw-rw-rw-   0 root         (0) root         (0)      121 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/doc/Makefile
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.423639 sosse-1.0.1/docker/pip-base/
--rw-rw-rw-   0 root         (0) root         (0)      442 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/pip-base/Dockerfile
--rw-rw-rw-   0 root         (0) root         (0)       27 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/pip-base/Makefile
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.427639 sosse-1.0.1/docker/pip-release/
--rw-rw-rw-   0 root         (0) root         (0)     1369 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/pip-release/Dockerfile
--rw-rw-rw-   0 root         (0) root         (0)      139 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/pip-release/Makefile
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.427639 sosse-1.0.1/docker/pip-test/
--rw-rw-rw-   0 root         (0) root         (0)      636 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/pip-test/Dockerfile
--rw-rw-rw-   0 root         (0) root         (0)       27 2023-05-01 14:24:18.000000 sosse-1.0.1/docker/pip-test/Makefile
--rw-rw-rw-   0 root         (0) root         (0)      892 2023-05-01 14:24:18.000000 sosse-1.0.1/pyproject.toml
--rw-rw-rw-   0 root         (0) root         (0)      129 2023-05-01 14:24:18.000000 sosse-1.0.1/requirements.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.443638 sosse-1.0.1/se/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-05-01 14:24:18.000000 sosse-1.0.1/se/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    20299 2023-05-01 14:24:18.000000 sosse-1.0.1/se/admin.py
--rw-rw-rw-   0 root         (0) root         (0)      996 2023-05-01 14:24:18.000000 sosse-1.0.1/se/apps.py
--rw-rw-rw-   0 root         (0) root         (0)     4121 2023-05-01 14:24:18.000000 sosse-1.0.1/se/atom.py
--rw-rw-rw-   0 root         (0) root         (0)    24133 2023-05-01 14:24:18.000000 sosse-1.0.1/se/browser.py
--rw-rw-rw-   0 root         (0) root         (0)     2804 2023-05-01 14:24:18.000000 sosse-1.0.1/se/cached.py
--rw-rw-rw-   0 root         (0) root         (0)     4314 2023-05-01 14:24:18.000000 sosse-1.0.1/se/forms.py
--rw-rw-rw-   0 root         (0) root         (0)     1150 2023-05-01 14:24:18.000000 sosse-1.0.1/se/login.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.447638 sosse-1.0.1/se/management/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-05-01 14:24:18.000000 sosse-1.0.1/se/management/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.451638 sosse-1.0.1/se/management/commands/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-05-01 14:24:18.000000 sosse-1.0.1/se/management/commands/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)     4311 2023-05-01 14:24:18.000000 sosse-1.0.1/se/management/commands/crawl.py
--rw-rw-rw-   0 root         (0) root         (0)     1427 2023-05-01 14:24:18.000000 sosse-1.0.1/se/management/commands/default_admin.py
--rw-rw-rw-   0 root         (0) root         (0)      952 2023-05-01 14:24:18.000000 sosse-1.0.1/se/management/commands/default_conf.py
--rw-rw-rw-   0 root         (0) root         (0)     6143 2023-05-01 14:24:18.000000 sosse-1.0.1/se/management/commands/extract_doc.py
--rw-rw-rw-   0 root         (0) root         (0)     1275 2023-05-01 14:24:18.000000 sosse-1.0.1/se/management/commands/generate_secret.py
--rw-rw-rw-   0 root         (0) root         (0)     1746 2023-05-01 14:24:18.000000 sosse-1.0.1/se/management/commands/load_se.py
--rw-rw-rw-   0 root         (0) root         (0)     2150 2023-05-01 14:24:18.000000 sosse-1.0.1/se/management/commands/update_se.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.451638 sosse-1.0.1/se/migrations/
--rw-rw-rw-   0 root         (0) root         (0)    13998 2023-05-01 14:19:16.000000 sosse-1.0.1/se/migrations/0001_initial.py
--rwxrwxrwx   0 root         (0) root         (0)     2976 2023-05-01 14:19:16.000000 sosse-1.0.1/se/migrations/0002_search_vector.py
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-05-01 14:19:17.000000 sosse-1.0.1/se/migrations/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    55276 2023-05-01 14:24:18.000000 sosse-1.0.1/se/models.py
--rw-rw-rw-   0 root         (0) root         (0)     1941 2023-05-01 14:24:18.000000 sosse-1.0.1/se/screenshot.py
--rw-rw-rw-   0 root         (0) root         (0)     6607 2023-05-01 14:24:18.000000 sosse-1.0.1/se/search.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.371640 sosse-1.0.1/se/static/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.463638 sosse-1.0.1/se/static/se/
--rw-rw-rw-   0 root         (0) root         (0)    19511 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/admin-base.css
--rw-rw-rw-   0 root         (0) root         (0)     8810 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/admin-forms.css
--rw-rw-rw-   0 root         (0) root         (0)     2005 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/base.js
--rw-rw-rw-   0 root         (0) root         (0)     2435 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/icon-atom.svg
--rw-rw-rw-   0 root         (0) root         (0)     2196 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/icon-clear.svg
--rw-rw-rw-   0 root         (0) root         (0)     3722 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/icon-cog.svg
--rw-rw-rw-   0 root         (0) root         (0)     6887 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/icon-search.svg
--rw-rw-rw-   0 root         (0) root         (0)     2488 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/icon-stats.svg
--rw-rw-rw-   0 root         (0) root         (0)     3644 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/icon-trash.svg
--rw-rw-rw-   0 root         (0) root         (0)     2771 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/icon-user.svg
--rw-rw-rw-   0 root         (0) root         (0)     9798 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/index.js
--rw-rw-rw-   0 root         (0) root         (0)     4462 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/logo.png
--rw-rw-rw-   0 root         (0) root         (0)     9908 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/logo.svg
--rw-rw-rw-   0 root         (0) root         (0)     5967 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/pygal-tooltips.min.js
--rw-rw-rw-   0 root         (0) root         (0)      982 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/screenshot.js
--rw-rw-rw-   0 root         (0) root         (0)     2522 2023-05-01 14:24:18.000000 sosse-1.0.1/se/static/se/style.css
--rw-rw-rw-   0 root         (0) root         (0)     8567 2023-05-01 14:24:18.000000 sosse-1.0.1/se/stats.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.371640 sosse-1.0.1/se/templates/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.467638 sosse-1.0.1/se/templates/admin/
--rw-rw-rw-   0 root         (0) root         (0)     3427 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/admin/add_to_queue.html
--rw-rw-rw-   0 root         (0) root         (0)     2518 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/admin/app_list.html
--rw-rw-rw-   0 root         (0) root         (0)     2270 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/admin/base.html
--rw-rw-rw-   0 root         (0) root         (0)      105 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/admin/base_site.html
--rw-rw-rw-   0 root         (0) root         (0)      677 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/admin/change_form.html
--rw-rw-rw-   0 root         (0) root         (0)      905 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/admin/crawl_status.html
--rw-rw-rw-   0 root         (0) root         (0)     2706 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/admin/crawl_status_content.html
--rw-rw-rw-   0 root         (0) root         (0)       69 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/admin/index.html
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.479637 sosse-1.0.1/se/templates/se/
--rw-rw-rw-   0 root         (0) root         (0)      674 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/about.html
--rw-rw-rw-   0 root         (0) root         (0)     1473 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/base.html
--rw-rw-rw-   0 root         (0) root         (0)     2285 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/cached.html
--rw-rw-rw-   0 root         (0) root         (0)     1870 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/history.html
--rw-rw-rw-   0 root         (0) root         (0)     8235 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/index.html
--rw-rw-rw-   0 root         (0) root         (0)     1320 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/main_menu.html
--rw-rw-rw-   0 root         (0) root         (0)      544 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/opensearch.xml
--rw-rw-rw-   0 root         (0) root         (0)      761 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/pagination.html
--rw-rw-rw-   0 root         (0) root         (0)     2242 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/prefs.html
--rw-rw-rw-   0 root         (0) root         (0)     1706 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/screenshot.html
--rw-rw-rw-   0 root         (0) root         (0)     1523 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/search_redirect.html
--rw-rw-rw-   0 root         (0) root         (0)     1547 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/stats.html
--rw-rw-rw-   0 root         (0) root         (0)      741 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/unknown_url.html
--rw-rw-rw-   0 root         (0) root         (0)      474 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/words.html
--rw-rw-rw-   0 root         (0) root         (0)      361 2023-05-01 14:24:18.000000 sosse-1.0.1/se/templates/se/www.html
--rw-rw-rw-   0 root         (0) root         (0)     5979 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_cookie.py
--rw-rw-rw-   0 root         (0) root         (0)    14144 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_crawl.py
--rw-rw-rw-   0 root         (0) root         (0)     9790 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_functionals.py
--rw-rw-rw-   0 root         (0) root         (0)     1459 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_misc.py
--rw-rw-rw-   0 root         (0) root         (0)     4659 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_parser.py
--rw-rw-rw-   0 root         (0) root         (0)     2133 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_redirect.py
--rw-rw-rw-   0 root         (0) root         (0)     1600 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_requests.py
--rw-rw-rw-   0 root         (0) root         (0)     9547 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_search.py
--rw-rw-rw-   0 root         (0) root         (0)     2612 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_url.py
--rw-rw-rw-   0 root         (0) root         (0)     6326 2023-05-01 14:24:18.000000 sosse-1.0.1/se/test_views.py
--rw-rw-rw-   0 root         (0) root         (0)     3101 2023-05-01 14:24:18.000000 sosse-1.0.1/se/utils.py
--rw-rw-rw-   0 root         (0) root         (0)     8408 2023-05-01 14:24:18.000000 sosse-1.0.1/se/views.py
--rw-rw-rw-   0 root         (0) root         (0)     1587 2023-05-01 14:24:18.000000 sosse-1.0.1/se/words.py
--rw-rw-rw-   0 root         (0) root         (0)     2805 2023-05-01 14:24:18.000000 sosse-1.0.1/se/www.py
--rw-r--r--   0 root         (0) root         (0)       38 2023-05-01 14:24:43.499637 sosse-1.0.1/setup.cfg
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.483637 sosse-1.0.1/sosse/
--rw-rw-rw-   0 root         (0) root         (0)        0 2023-05-01 14:24:18.000000 sosse-1.0.1/sosse/__init__.py
--rw-rw-rw-   0 root         (0) root         (0)    16555 2023-05-01 14:24:18.000000 sosse-1.0.1/sosse/conf.py
--rw-rw-rw-   0 root         (0) root         (0)    18193 2023-05-01 14:24:18.000000 sosse-1.0.1/sosse/search_engines.json
--rw-rw-rw-   0 root         (0) root         (0)     7433 2023-05-01 14:24:25.000000 sosse-1.0.1/sosse/settings.py
--rwxrwxrwx   0 root         (0) root         (0)     1328 2023-05-01 14:24:18.000000 sosse-1.0.1/sosse/sosse_admin.py
--rw-rw-rw-   0 root         (0) root         (0)      409 2023-05-01 14:24:18.000000 sosse-1.0.1/sosse/test_runner.py
--rw-rw-rw-   0 root         (0) root         (0)     2548 2023-05-01 14:24:18.000000 sosse-1.0.1/sosse/urls.py
--rw-rw-rw-   0 root         (0) root         (0)     1089 2023-05-01 14:24:18.000000 sosse-1.0.1/sosse/wsgi.py
--rwxrwxrwx   0 root         (0) root         (0)       70 2023-05-01 14:24:18.000000 sosse-1.0.1/sosse-admin
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.487637 sosse-1.0.1/sosse.egg-info/
--rw-r--r--   0 root         (0) root         (0)     3182 2023-05-01 14:24:43.000000 sosse-1.0.1/sosse.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     4621 2023-05-01 14:24:43.000000 sosse-1.0.1/sosse.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-05-01 14:24:43.000000 sosse-1.0.1/sosse.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       55 2023-05-01 14:24:43.000000 sosse-1.0.1/sosse.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)      129 2023-05-01 14:24:43.000000 sosse-1.0.1/sosse.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        9 2023-05-01 14:24:43.000000 sosse-1.0.1/sosse.egg-info/top_level.txt
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.495637 sosse-1.0.1/tests/
--rwxrwxrwx   0 root         (0) root         (0)      281 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/build_doc.sh
--rw-rw-rw-   0 root         (0) root         (0)      809 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/cookies.json
--rwxrwxrwx   0 root         (0) root         (0)     1047 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/doc_test.sh
--rwxrwxrwx   0 root         (0) root         (0)      477 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/docker_run.sh
--rw-rw-rw-   0 root         (0) root         (0)     1015 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/document-ja.json
--rw-rw-rw-   0 root         (0) root         (0)      496 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/opensearch.xml
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.495637 sosse-1.0.1/tests/robotframework/
--rw-rw-rw-   0 root         (0) root         (0)       46 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/robotframework/requirements.txt
--rwxrwxrwx   0 root         (0) root         (0)      605 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/robotframework/start.sh
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-05-01 14:24:43.499637 sosse-1.0.1/tests/robotframework/tests/
--rw-rw-rw-   0 root         (0) root         (0)     5208 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/robotframework/tests/01_crawl.robot
--rw-rw-rw-   0 root         (0) root         (0)     2862 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/robotframework/tests/02_user.robot
--rw-rw-rw-   0 root         (0) root         (0)      129 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/robotframework/tests/__init__.robot
--rw-rw-rw-   0 root         (0) root         (0)     1535 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/robotframework/tests/common.robot
--rw-rw-rw-   0 root         (0) root         (0)      467 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/searchhistory.json
--rwxrwxrwx   0 root         (0) root         (0)      938 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/test_app.sh
--rwxrwxrwx   0 root         (0) root         (0)      101 2023-05-01 14:24:18.000000 sosse-1.0.1/tests/wait_for_pg.sh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.720515 sosse-1.1.0/
+-rw-rw-rw-   0 root         (0) root         (0)       30 2023-06-28 15:14:52.000000 sosse-1.1.0/.coveragerc
+-rw-rw-rw-   0 root         (0) root         (0)      351 2023-06-28 15:14:52.000000 sosse-1.1.0/.gitignore
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.612520 sosse-1.1.0/.gitlab/
+-rw-rw-rw-   0 root         (0) root         (0)       80 2023-06-28 15:14:52.000000 sosse-1.1.0/.gitlab/changelog_config.yml
+-rw-rw-rw-   0 root         (0) root         (0)     6939 2023-06-28 15:14:52.000000 sosse-1.1.0/.gitlab-ci.yml
+-rw-rw-rw-   0 root         (0) root         (0)      491 2023-06-28 15:14:52.000000 sosse-1.1.0/.readthedocs.yaml
+-rw-rw-rw-   0 root         (0) root         (0)     1008 2023-06-28 15:14:52.000000 sosse-1.1.0/CHANGELOG.md
+-rw-rw-rw-   0 root         (0) root         (0)     1635 2023-06-28 15:14:52.000000 sosse-1.1.0/Dockerfile
+-rw-rw-rw-   0 root         (0) root         (0)    34523 2023-06-28 15:14:52.000000 sosse-1.1.0/LICENSE
+-rw-rw-rw-   0 root         (0) root         (0)      112 2023-06-28 15:14:52.000000 sosse-1.1.0/MANIFEST.in
+-rw-rw-rw-   0 root         (0) root         (0)     7504 2023-06-28 15:14:52.000000 sosse-1.1.0/Makefile
+-rw-r--r--   0 root         (0) root         (0)     3198 2023-06-28 15:15:25.720515 sosse-1.1.0/PKG-INFO
+-rw-rw-rw-   0 root         (0) root         (0)     2806 2023-06-28 15:14:52.000000 sosse-1.1.0/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.616520 sosse-1.1.0/debian/
+-rw-rw-rw-   0 root         (0) root         (0)      427 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/changelog
+-rw-rw-rw-   0 root         (0) root         (0)        3 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/compat
+-rw-rw-rw-   0 root         (0) root         (0)      697 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/control
+-rwxrwxrwx   0 root         (0) root         (0)      182 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/rules
+-rw-rw-rw-   0 root         (0) root         (0)      719 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/sosse-crawler.service
+-rw-rw-rw-   0 root         (0) root         (0)      803 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/sosse-uwsgi.service
+-rw-rw-rw-   0 root         (0) root         (0)     2176 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/sosse.conf
+-rw-rw-rw-   0 root         (0) root         (0)      198 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/sosse.install
+-rw-rw-rw-   0 root         (0) root         (0)     2733 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/sosse.postinst
+-rw-rw-rw-   0 root         (0) root         (0)      465 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/uwsgi.ini
+-rw-rw-rw-   0 root         (0) root         (0)      664 2023-06-28 15:14:52.000000 sosse-1.1.0/debian/uwsgi.params
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.620520 sosse-1.1.0/doc/
+-rw-rw-rw-   0 root         (0) root         (0)      638 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/Makefile
+-rwxrwxrwx   0 root         (0) root         (0)      314 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/build_changelog.sh
+-rw-rw-rw-   0 root         (0) root         (0)     1897 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/get_artifacts.py
+-rw-rw-rw-   0 root         (0) root         (0)      804 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/make.bat
+-rw-rw-rw-   0 root         (0) root         (0)       40 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/requirements.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.632519 sosse-1.1.0/doc/source/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.632519 sosse-1.1.0/doc/source/_extensions/
+-rw-rw-rw-   0 root         (0) root         (0)     1124 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/_extensions/code_blocks.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.632519 sosse-1.1.0/doc/source/_static/
+-rw-rw-rw-   0 root         (0) root         (0)      262 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/_static/style.css
+-rw-rw-rw-   0 root         (0) root         (0)      723 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/admin_ui.rst
+-rw-rw-rw-   0 root         (0) root         (0)      347 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/administration.rst
+-rw-rw-rw-   0 root         (0) root         (0)      502 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/archive.rst
+-rw-rw-rw-   0 root         (0) root         (0)      839 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/authentication.rst
+-rw-rw-rw-   0 root         (0) root         (0)      433 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/cli.rst
+-rw-rw-rw-   0 root         (0) root         (0)     1951 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/conf.py
+-rw-rw-rw-   0 root         (0) root         (0)      360 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/config_file.rst
+-rw-rw-rw-   0 root         (0) root         (0)      323 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/cookies.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.636519 sosse-1.1.0/doc/source/crawl/
+-rw-rw-rw-   0 root         (0) root         (0)      560 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/crawl/add_to_queue.rst
+-rw-rw-rw-   0 root         (0) root         (0)     1452 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/crawl/crawl_depth.rst
+-rw-rw-rw-   0 root         (0) root         (0)     5773 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/crawl/policies.rst
+-rw-rw-rw-   0 root         (0) root         (0)      316 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/crawl/status.rst
+-rw-rw-rw-   0 root         (0) root         (0)     1452 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/documents.rst
+-rw-rw-rw-   0 root         (0) root         (0)     1408 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/domain_settings.rst
+-rw-rw-rw-   0 root         (0) root         (0)      315 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/excluded_urls.rst
+-rw-rw-rw-   0 root         (0) root         (0)      531 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/index.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.640519 sosse-1.1.0/doc/source/install/
+-rw-rw-rw-   0 root         (0) root         (0)      883 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/install/database.rst.template
+-rw-rw-rw-   0 root         (0) root         (0)     1463 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/install/debian.rst
+-rw-rw-rw-   0 root         (0) root         (0)      255 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/install/debian_upgrades.rst
+-rw-rw-rw-   0 root         (0) root         (0)     1154 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/install/docker.rst
+-rw-rw-rw-   0 root         (0) root         (0)      261 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/install/docker_upgrades.rst
+-rw-rw-rw-   0 root         (0) root         (0)     3444 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/install/pip.rst
+-rw-rw-rw-   0 root         (0) root         (0)      450 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/install/pip_upgrades.rst
+-rw-rw-rw-   0 root         (0) root         (0)      287 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/install.rst
+-rw-rw-rw-   0 root         (0) root         (0)      988 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/permissions.rst
+-rw-rw-rw-   0 root         (0) root         (0)     1141 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/screenshots.rst
+-rw-rw-rw-   0 root         (0) root         (0)      980 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/search_engines.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.644519 sosse-1.1.0/doc/source/user/
+-rw-rw-rw-   0 root         (0) root         (0)      823 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/user/cached.rst
+-rw-rw-rw-   0 root         (0) root         (0)      593 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/user/history.rst
+-rw-rw-rw-   0 root         (0) root         (0)     1407 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/user/preferences.rst
+-rw-rw-rw-   0 root         (0) root         (0)     4293 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/user/search.rst
+-rw-rw-rw-   0 root         (0) root         (0)      253 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/user/shortcut_list.rst
+-rw-rw-rw-   0 root         (0) root         (0)     1043 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/user/shortcuts.rst
+-rw-rw-rw-   0 root         (0) root         (0)      201 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/user/statistics.rst
+-rw-rw-rw-   0 root         (0) root         (0)      245 2023-06-28 15:14:52.000000 sosse-1.1.0/doc/source/user_doc.rst
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.644519 sosse-1.1.0/docker/
+-rw-rw-rw-   0 root         (0) root         (0)      882 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/Makefile
+-rw-rw-rw-   0 root         (0) root         (0)      445 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/Makefile.common
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.644519 sosse-1.1.0/docker/debian/
+-rw-rw-rw-   0 root         (0) root         (0)     1965 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/debian/Dockerfile
+-rw-rw-rw-   0 root         (0) root         (0)       46 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/debian/Makefile
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.644519 sosse-1.1.0/docker/debian-pkg/
+-rw-rw-rw-   0 root         (0) root         (0)      540 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/debian-pkg/Dockerfile
+-rw-rw-rw-   0 root         (0) root         (0)       27 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/debian-pkg/Makefile
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.648519 sosse-1.1.0/docker/debian-test/
+-rw-rw-rw-   0 root         (0) root         (0)     1166 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/debian-test/Dockerfile
+-rw-rw-rw-   0 root         (0) root         (0)      138 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/debian-test/Makefile
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.648519 sosse-1.1.0/docker/doc/
+-rw-rw-rw-   0 root         (0) root         (0)      435 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/doc/Dockerfile
+-rw-rw-rw-   0 root         (0) root         (0)      121 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/doc/Makefile
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.648519 sosse-1.1.0/docker/pip-base/
+-rw-rw-rw-   0 root         (0) root         (0)      453 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/pip-base/Dockerfile
+-rw-rw-rw-   0 root         (0) root         (0)       27 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/pip-base/Makefile
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.652518 sosse-1.1.0/docker/pip-release/
+-rw-rw-rw-   0 root         (0) root         (0)     1405 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/pip-release/Dockerfile
+-rw-rw-rw-   0 root         (0) root         (0)      139 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/pip-release/Makefile
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.652518 sosse-1.1.0/docker/pip-test/
+-rw-rw-rw-   0 root         (0) root         (0)      617 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/pip-test/Dockerfile
+-rw-rw-rw-   0 root         (0) root         (0)       27 2023-06-28 15:14:52.000000 sosse-1.1.0/docker/pip-test/Makefile
+-rw-rw-rw-   0 root         (0) root         (0)      892 2023-06-28 15:14:52.000000 sosse-1.1.0/pyproject.toml
+-rw-rw-rw-   0 root         (0) root         (0)      129 2023-06-28 15:14:52.000000 sosse-1.1.0/requirements.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.668518 sosse-1.1.0/se/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 15:14:52.000000 sosse-1.1.0/se/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    20834 2023-06-28 15:14:52.000000 sosse-1.1.0/se/admin.py
+-rw-rw-rw-   0 root         (0) root         (0)      996 2023-06-28 15:14:52.000000 sosse-1.1.0/se/apps.py
+-rw-rw-rw-   0 root         (0) root         (0)     4121 2023-06-28 15:14:52.000000 sosse-1.1.0/se/atom.py
+-rw-rw-rw-   0 root         (0) root         (0)    24375 2023-06-28 15:14:52.000000 sosse-1.1.0/se/browser.py
+-rw-rw-rw-   0 root         (0) root         (0)     3135 2023-06-28 15:14:52.000000 sosse-1.1.0/se/cached.py
+-rw-rw-rw-   0 root         (0) root         (0)     4314 2023-06-28 15:14:52.000000 sosse-1.1.0/se/forms.py
+-rw-rw-rw-   0 root         (0) root         (0)     1150 2023-06-28 15:14:52.000000 sosse-1.1.0/se/login.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.668518 sosse-1.1.0/se/management/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 15:14:52.000000 sosse-1.1.0/se/management/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.672517 sosse-1.1.0/se/management/commands/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 15:14:52.000000 sosse-1.1.0/se/management/commands/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)     4311 2023-06-28 15:14:52.000000 sosse-1.1.0/se/management/commands/crawl.py
+-rw-rw-rw-   0 root         (0) root         (0)     1427 2023-06-28 15:14:52.000000 sosse-1.1.0/se/management/commands/default_admin.py
+-rw-rw-rw-   0 root         (0) root         (0)      952 2023-06-28 15:14:52.000000 sosse-1.1.0/se/management/commands/default_conf.py
+-rw-rw-rw-   0 root         (0) root         (0)     6143 2023-06-28 15:14:52.000000 sosse-1.1.0/se/management/commands/extract_doc.py
+-rw-rw-rw-   0 root         (0) root         (0)     1275 2023-06-28 15:14:52.000000 sosse-1.1.0/se/management/commands/generate_secret.py
+-rw-rw-rw-   0 root         (0) root         (0)     1746 2023-06-28 15:14:52.000000 sosse-1.1.0/se/management/commands/load_se.py
+-rw-rw-rw-   0 root         (0) root         (0)     2150 2023-06-28 15:14:52.000000 sosse-1.1.0/se/management/commands/update_se.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.676517 sosse-1.1.0/se/migrations/
+-rw-rw-rw-   0 root         (0) root         (0)    13998 2023-06-28 14:55:25.000000 sosse-1.1.0/se/migrations/0001_initial.py
+-rwxrwxrwx   0 root         (0) root         (0)     2976 2023-06-28 14:55:25.000000 sosse-1.1.0/se/migrations/0002_search_vector.py
+-rw-rw-rw-   0 root         (0) root         (0)     1143 2023-06-28 14:55:25.000000 sosse-1.1.0/se/migrations/0003_sosse_1_1_0.py
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 14:55:25.000000 sosse-1.1.0/se/migrations/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    55878 2023-06-28 15:14:52.000000 sosse-1.1.0/se/models.py
+-rw-rw-rw-   0 root         (0) root         (0)     1974 2023-06-28 15:14:52.000000 sosse-1.1.0/se/screenshot.py
+-rw-rw-rw-   0 root         (0) root         (0)     6607 2023-06-28 15:14:52.000000 sosse-1.1.0/se/search.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.600521 sosse-1.1.0/se/static/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.684517 sosse-1.1.0/se/static/se/
+-rw-rw-rw-   0 root         (0) root         (0)    19511 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/admin-base.css
+-rw-rw-rw-   0 root         (0) root         (0)     8810 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/admin-forms.css
+-rw-rw-rw-   0 root         (0) root         (0)     2005 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/base.js
+-rw-rw-rw-   0 root         (0) root         (0)     2435 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/icon-atom.svg
+-rw-rw-rw-   0 root         (0) root         (0)     2196 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/icon-clear.svg
+-rw-rw-rw-   0 root         (0) root         (0)     3722 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/icon-cog.svg
+-rw-rw-rw-   0 root         (0) root         (0)     6887 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/icon-search.svg
+-rw-rw-rw-   0 root         (0) root         (0)     2488 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/icon-stats.svg
+-rw-rw-rw-   0 root         (0) root         (0)     3644 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/icon-trash.svg
+-rw-rw-rw-   0 root         (0) root         (0)     2771 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/icon-user.svg
+-rw-rw-rw-   0 root         (0) root         (0)     9798 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/index.js
+-rw-rw-rw-   0 root         (0) root         (0)     4462 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/logo.png
+-rw-rw-rw-   0 root         (0) root         (0)     9908 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/logo.svg
+-rw-rw-rw-   0 root         (0) root         (0)     5967 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/pygal-tooltips.min.js
+-rw-rw-rw-   0 root         (0) root         (0)      982 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/screenshot.js
+-rw-rw-rw-   0 root         (0) root         (0)     2522 2023-06-28 15:14:52.000000 sosse-1.1.0/se/static/se/style.css
+-rw-rw-rw-   0 root         (0) root         (0)     8567 2023-06-28 15:14:52.000000 sosse-1.1.0/se/stats.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.600521 sosse-1.1.0/se/templates/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.688517 sosse-1.1.0/se/templates/admin/
+-rw-rw-rw-   0 root         (0) root         (0)     3427 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/admin/add_to_queue.html
+-rw-rw-rw-   0 root         (0) root         (0)     2518 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/admin/app_list.html
+-rw-rw-rw-   0 root         (0) root         (0)     2270 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/admin/base.html
+-rw-rw-rw-   0 root         (0) root         (0)      105 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/admin/base_site.html
+-rw-rw-rw-   0 root         (0) root         (0)      677 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/admin/change_form.html
+-rw-rw-rw-   0 root         (0) root         (0)      905 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/admin/crawl_status.html
+-rw-rw-rw-   0 root         (0) root         (0)     2706 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/admin/crawl_status_content.html
+-rw-rw-rw-   0 root         (0) root         (0)       69 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/admin/index.html
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.700516 sosse-1.1.0/se/templates/se/
+-rw-rw-rw-   0 root         (0) root         (0)      674 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/about.html
+-rw-rw-rw-   0 root         (0) root         (0)     1473 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/base.html
+-rw-rw-rw-   0 root         (0) root         (0)     2285 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/cached.html
+-rw-rw-rw-   0 root         (0) root         (0)     1870 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/history.html
+-rw-rw-rw-   0 root         (0) root         (0)      671 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/home_browse.html
+-rw-rw-rw-   0 root         (0) root         (0)     9293 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/index.html
+-rw-rw-rw-   0 root         (0) root         (0)     1320 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/main_menu.html
+-rw-rw-rw-   0 root         (0) root         (0)      544 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/opensearch.xml
+-rw-rw-rw-   0 root         (0) root         (0)      761 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/pagination.html
+-rw-rw-rw-   0 root         (0) root         (0)     2242 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/prefs.html
+-rw-rw-rw-   0 root         (0) root         (0)     1706 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/screenshot.html
+-rw-rw-rw-   0 root         (0) root         (0)     1523 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/search_redirect.html
+-rw-rw-rw-   0 root         (0) root         (0)     1547 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/stats.html
+-rw-rw-rw-   0 root         (0) root         (0)      741 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/unknown_url.html
+-rw-rw-rw-   0 root         (0) root         (0)      474 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/words.html
+-rw-rw-rw-   0 root         (0) root         (0)      361 2023-06-28 15:14:52.000000 sosse-1.1.0/se/templates/se/www.html
+-rw-rw-rw-   0 root         (0) root         (0)     5979 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_cookie.py
+-rw-rw-rw-   0 root         (0) root         (0)    14987 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_crawl.py
+-rw-rw-rw-   0 root         (0) root         (0)     9790 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_functionals.py
+-rw-rw-rw-   0 root         (0) root         (0)     1459 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_misc.py
+-rw-rw-rw-   0 root         (0) root         (0)     4659 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_parser.py
+-rw-rw-rw-   0 root         (0) root         (0)     2133 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_redirect.py
+-rw-rw-rw-   0 root         (0) root         (0)     1600 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_requests.py
+-rw-rw-rw-   0 root         (0) root         (0)     9547 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_search.py
+-rw-rw-rw-   0 root         (0) root         (0)     2612 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_url.py
+-rw-rw-rw-   0 root         (0) root         (0)     6326 2023-06-28 15:14:52.000000 sosse-1.1.0/se/test_views.py
+-rw-rw-rw-   0 root         (0) root         (0)     3101 2023-06-28 15:14:52.000000 sosse-1.1.0/se/utils.py
+-rw-rw-rw-   0 root         (0) root         (0)     8615 2023-06-28 15:14:52.000000 sosse-1.1.0/se/views.py
+-rw-rw-rw-   0 root         (0) root         (0)     1587 2023-06-28 15:14:52.000000 sosse-1.1.0/se/words.py
+-rw-rw-rw-   0 root         (0) root         (0)     2831 2023-06-28 15:14:52.000000 sosse-1.1.0/se/www.py
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 15:15:25.720515 sosse-1.1.0/setup.cfg
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.704516 sosse-1.1.0/sosse/
+-rw-rw-rw-   0 root         (0) root         (0)        0 2023-06-28 15:14:52.000000 sosse-1.1.0/sosse/__init__.py
+-rw-rw-rw-   0 root         (0) root         (0)    16942 2023-06-28 15:14:52.000000 sosse-1.1.0/sosse/conf.py
+-rw-rw-rw-   0 root         (0) root         (0)    18193 2023-06-28 15:14:52.000000 sosse-1.1.0/sosse/search_engines.json
+-rw-rw-rw-   0 root         (0) root         (0)     7433 2023-06-28 15:15:05.000000 sosse-1.1.0/sosse/settings.py
+-rwxrwxrwx   0 root         (0) root         (0)     1328 2023-06-28 15:14:52.000000 sosse-1.1.0/sosse/sosse_admin.py
+-rw-rw-rw-   0 root         (0) root         (0)      409 2023-06-28 15:14:52.000000 sosse-1.1.0/sosse/test_runner.py
+-rw-rw-rw-   0 root         (0) root         (0)     2548 2023-06-28 15:14:52.000000 sosse-1.1.0/sosse/urls.py
+-rw-rw-rw-   0 root         (0) root         (0)     1089 2023-06-28 15:14:52.000000 sosse-1.1.0/sosse/wsgi.py
+-rwxrwxrwx   0 root         (0) root         (0)       70 2023-06-28 15:14:52.000000 sosse-1.1.0/sosse-admin
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.708516 sosse-1.1.0/sosse.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     3198 2023-06-28 15:15:25.000000 sosse-1.1.0/sosse.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     4845 2023-06-28 15:15:25.000000 sosse-1.1.0/sosse.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 15:15:25.000000 sosse-1.1.0/sosse.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       55 2023-06-28 15:15:25.000000 sosse-1.1.0/sosse.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)      129 2023-06-28 15:15:25.000000 sosse-1.1.0/sosse.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        9 2023-06-28 15:15:25.000000 sosse-1.1.0/sosse.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.716515 sosse-1.1.0/tests/
+-rwxrwxrwx   0 root         (0) root         (0)      281 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/build_doc.sh
+-rw-rw-rw-   0 root         (0) root         (0)      809 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/cookies.json
+-rwxrwxrwx   0 root         (0) root         (0)     1629 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/doc_test.sh
+-rwxrwxrwx   0 root         (0) root         (0)      477 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/docker_run.sh
+-rw-rw-rw-   0 root         (0) root         (0)     1015 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/document-ja.json
+-rw-rw-rw-   0 root         (0) root         (0)      496 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/opensearch.xml
+-rw-rw-rw-   0 root         (0) root         (0)      806 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/release.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.716515 sosse-1.1.0/tests/robotframework/
+-rw-rw-rw-   0 root         (0) root         (0)       25 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/robotframework/config.yaml
+-rw-rw-rw-   0 root         (0) root         (0)     7309 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/robotframework/home_docs.json
+-rw-rw-rw-   0 root         (0) root         (0)    64349 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/robotframework/home_favicon.json
+-rw-rw-rw-   0 root         (0) root         (0)       67 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/robotframework/requirements.txt
+-rwxrwxrwx   0 root         (0) root         (0)      605 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/robotframework/start.sh
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:15:25.720515 sosse-1.1.0/tests/robotframework/tests/
+-rw-rw-rw-   0 root         (0) root         (0)     5212 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/robotframework/tests/01_crawl.robot
+-rw-rw-rw-   0 root         (0) root         (0)     3334 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/robotframework/tests/02_user.robot
+-rw-rw-rw-   0 root         (0) root         (0)      129 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/robotframework/tests/__init__.robot
+-rw-rw-rw-   0 root         (0) root         (0)     1535 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/robotframework/tests/common.robot
+-rw-rw-rw-   0 root         (0) root         (0)      467 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/searchhistory.json
+-rwxrwxrwx   0 root         (0) root         (0)      938 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/test_app.sh
+-rwxrwxrwx   0 root         (0) root         (0)      101 2023-06-28 15:14:52.000000 sosse-1.1.0/tests/wait_for_pg.sh
```

### Comparing `sosse-1.0.1/.gitlab-ci.yml` & `sosse-1.1.0/.gitlab-ci.yml`

 * *Files 2% similar despite different names*

```diff
@@ -111,15 +111,15 @@
     paths:
       - doc/build/*
   needs:
     - doc_gen
     - functional_tests
   script:
     - make _build_doc
-    - test -n "RTD_TOKEN" && curl -X POST -d "branches=main" -d "token=$RTD_TOKEN" -d "default_branch=main" https://readthedocs.org/api/v2/webhook/sosse/236935/ || true
+    - test -n "$RTD_TOKEN" && curl -X POST -d "branches=main" -d "token=$RTD_TOKEN" -d "default_branch=main" https://readthedocs.org/api/v2/webhook/sosse/236935/ || true
 
 pip_pkg:
   image: biolds/sosse:pip-test
   artifacts:
     paths:
       - dist/*
   stage: build
@@ -166,48 +166,48 @@
   script:
     - 'last_ver="$(git tag -l | sort -V | tail -n 1 | sed -e "s/^v//")"'
     - 'new_ver="${last_ver%.*}.$((${last_ver/*./} + 1))"'
     - 'curl -X GET -H "PRIVATE-TOKEN: $GITLAB_REST_API_CHANGELOG" "https://gitlab.com/api/v4/projects/$CI_PROJECT_ID/repository/changelog?version=$new_ver" | jq -r .notes | tee /tmp/new'
     - cat /tmp/new CHANGELOG.md > new.md && mv new.md CHANGELOG.md
 
 doc_test_debian:
-  image: debian:bullseye
+  image: debian:bookworm
   stage: build_check
   needs:
     - doc_code_extract
   script:
     - apt update
     - apt install -y make jq
     - make _doc_test_debian
 
 doc_test_pip:
-  image: debian:bullseye
+  image: debian:bookworm
   stage: build_check
   needs:
     - doc_code_extract
   script:
     - apt update
-    - apt install -y make jq postgresql nginx chromium python3-pip
+    - apt install -y make jq
     - make _doc_test_pip
 
 debian_pkg_check:
-  image: debian:bullseye
+  image: debian:bookworm
   stage: build_check
   artifacts:
     when: always
     paths:
       - tests/robotframework/screenshots/*
       - tests/robotframework/*.html
       - log/*
   needs:
     - doc_code_extract
     - debian_pkg
   script:
     - apt update
-    - apt install -y jq make
+    - apt install -y jq make virtualenv
     - make _deb_pkg_functional_tests
     - (make _rf_functional_tests ; echo -n $? > /tmp/ret_code) || true
     - mv /var/log/sosse log
     - test "$(cat /tmp/ret_code)" -eq 0
 
 pip_pkg_check:
   image: biolds/sosse:pip-test
```

### Comparing `sosse-1.0.1/Dockerfile` & `sosse-1.1.0/Dockerfile`

 * *Files 14% similar despite different names*

```diff
@@ -4,18 +4,19 @@
 RUN mkdir /root/sosse
 WORKDIR /root/sosse
 ADD requirements.txt .
 ADD pyproject.toml .
 ADD MANIFEST.in .
 ADD se/ se/
 ADD sosse/ sosse/
-RUN pip install ./ && pip install uwsgi && pip cache purge
+RUN virtualenv /venv
+RUN /venv/bin/pip install ./ && /venv/bin/pip install uwsgi && /venv/bin/pip cache purge
 ADD debian/sosse.conf /etc/nginx/sites-enabled/default
 RUN mkdir -p /etc/sosse/ /etc/sosse_src/ /var/log/sosse /var/log/uwsgi
-RUN sosse-admin default_conf | sed -e 's/^#db_pass.*/db_pass=sosse/' -e 's/^#\(browser_options=.*\)$/\1 --no-sandbox/' > /etc/sosse_src/sosse.conf
+RUN /venv/bin/sosse-admin default_conf | sed -e 's/^#db_pass.*/db_pass=sosse/' -e 's/^#\(browser_options=.*\)$/\1 --no-sandbox/' > /etc/sosse_src/sosse.conf
 ADD debian/uwsgi.* /etc/sosse_src/
 RUN chown -R root:www-data /etc/sosse /etc/sosse_src && chmod 750 /etc/sosse_src/ && chmod 640 /etc/sosse_src/*
 
 WORKDIR /
 USER postgres
 RUN /etc/init.d/postgresql start && \
     psql --command "CREATE USER sosse WITH PASSWORD 'sosse';" && \
@@ -24,16 +25,16 @@
 USER root
 RUN echo '#!/bin/bash -x \n \
 /etc/init.d/postgresql start \n \
 test -e /etc/sosse/sosse.conf || (cp -p /etc/sosse_src/* /etc/sosse/) \n \
 mkdir -p /run/sosse \n \
 touch /var/log/sosse/{debug.log,main.log,crawler.log,uwsgi.log,webserver.log} \n \
 chown -R www-data:www-data /run/sosse /var/log/sosse/ \n \
-sosse-admin migrate \n \
-sosse-admin collectstatic --noinput \n \
-sosse-admin update_se \n \
-sosse-admin default_admin \n \
-/usr/local/bin/uwsgi --uid www-data --gid www-data --ini /etc/sosse/uwsgi.ini --logto /var/log/sosse/uwsgi.log & \n \
+/venv/bin/sosse-admin migrate \n \
+/venv/bin/sosse-admin collectstatic --noinput \n \
+/venv/bin/sosse-admin update_se \n \
+/venv/bin/sosse-admin default_admin \n \
+/venv/bin/uwsgi --uid www-data --gid www-data --ini /etc/sosse/uwsgi.ini --logto /var/log/sosse/uwsgi.log & \n \
 /etc/init.d/nginx start \n \
-sosse-admin crawl & \n \
+/venv/bin/sosse-admin crawl & \n \
 tail -F /var/log/sosse/crawler.log' > /run.sh ; chmod +x /run.sh
 CMD /run.sh
```

### Comparing `sosse-1.0.1/LICENSE` & `sosse-1.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/Makefile` & `sosse-1.1.0/Makefile`

 * *Files 6% similar despite different names*

```diff
@@ -37,66 +37,68 @@
 
 deb:
 	mkdir $(current_dir)/deb/ &>/dev/null ||:
 	docker run --rm -v $(current_dir):/sosse:ro -v $(current_dir)/deb:/deb biolds/sosse:debian-pkg bash -c 'cp -x -r /sosse /sosse-deb && make -C /sosse-deb _deb'
 
 _build_doc:
 	./doc/build_changelog.sh > doc/source/CHANGELOG.md
+	sed -e 's#|sosse-admin|#sosse-admin#' doc/source/install/database.rst.template > doc/source/install/database_debian.rst
+	sed -e 's#|sosse-admin|#/opt/sosse-venv/bin/sosse-admin#' doc/source/install/database.rst.template > doc/source/install/database_pip.rst
 	. /opt/sosse-doc/bin/activate ; make -C doc linkcheck html SPHINXOPTS="-W"
 	jq . < doc/code_blocks.json > /tmp/code_blocks.json
 	mv /tmp/code_blocks.json doc/code_blocks.json
 
 build_doc:
 	mkdir -p doc/build/
-	docker run --rm -v $(current_dir):/sosse:ro -v $(current_dir)/doc/build:/sosse/doc/build biolds/sosse:doc bash -c 'cd /sosse && make _build_doc'
+	docker run --rm -v $(current_dir):/sosse:ro -v $(current_dir)/doc:/sosse/doc biolds/sosse:doc bash -c 'cd /sosse && make _build_doc'
 
 
 docker_run:
 	docker volume inspect sosse_postgres &>/dev/null || docker volume create sosse_postgres
 	docker volume inspect sosse_var &>/dev/null || docker volume create sosse_var
 	docker run -p 8005:80 --mount source=sosse_postgres,destination=/var/lib/postgresql \
 						--mount source=sosse_var,destination=/var/lib/sosse biolds/sosse:latest
 
 docker_release_push:
 	docker push biolds/sosse:latest
 
 docker_release_build:
-	docker pull debian:bullseye
+	docker pull debian:bookworm
 	$(MAKE) -C docker/pip-base build APT_PROXY=$(APT_PROXY) PIP_INDEX_URL=$(PIP_INDEX_URL) PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST)
 	$(MAKE) -C docker/pip-release build APT_PROXY=$(APT_PROXY) PIP_INDEX_URL=$(PIP_INDEX_URL) PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST)
 	docker tag biolds/sosse:pip-release biolds/sosse:latest
 
 docker_git_build:
-	docker pull debian:bullseye
+	docker pull debian:bookworm
 	$(MAKE) -C docker/pip-base build APT_PROXY=$(APT_PROXY) PIP_INDEX_URL=$(PIP_INDEX_URL) PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST)
 	docker build --build-arg APT_PROXY=$(APT_PROXY) --build-arg PIP_INDEX_URL=$(PIP_INDEX_URL) --build-arg PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST) -t biolds/sosse:git .
 
 docker_push:
 	$(MAKE) -C docker push
 
 docker_build:
 	$(MAKE) -C docker build
 
 _doc_test_debian:
 	cp doc/code_blocks.json /tmp/code_blocks.json
-	grep -q 'apt install -y python3-django/bullseye-backports sosse' /tmp/code_blocks.json
-	sed -e 's#apt install -y python3-django/bullseye-backports sosse#apt install -y python3-django/bullseye-backports sosse; /etc/init.d/nginx start \& /etc/init.d/postgresql start \& bash ./tests/wait_for_pg.sh#' -i /tmp/code_blocks.json
+	grep -q 'apt install -y sosse' /tmp/code_blocks.json
+	sed -e 's#apt install -y sosse#apt install -y sosse; /etc/init.d/nginx start \& /etc/init.d/postgresql start \& bash ./tests/wait_for_pg.sh#' -i /tmp/code_blocks.json
 	bash ./tests/doc_test.sh /tmp/code_blocks.json install/debian
 
 doc_test_debian:
-	docker run -v $(current_dir):/sosse:ro debian:bullseye bash -c 'cd /sosse && apt-get update && apt-get install -y make jq && make _doc_test_debian'
+	docker run -v $(current_dir):/sosse:ro debian:bookworm bash -c 'cd /sosse && apt-get update && apt-get install -y make jq && make _doc_test_debian'
 
 _doc_test_pip:
-	apt install -y chromium chromium-driver postgresql nginx python3-dev libpq-dev
+	apt install -y chromium chromium-driver postgresql libpq-dev nginx python3-dev python3-pip virtualenv
 	/etc/init.d/postgresql start &
 	bash ./tests/wait_for_pg.sh
 	bash ./tests/doc_test.sh doc/code_blocks.json install/pip
 
 doc_test_pip:
-	docker run -v $(current_dir):/sosse:ro debian:bullseye bash -c 'cd /sosse && apt-get update && apt-get install -y make jq && make _doc_test_pip'
+	docker run -v $(current_dir):/sosse:ro debian:bookworm bash -c 'cd /sosse && apt-get update && apt-get install -y make jq && make _doc_test_pip'
 
 _pip_pkg_check:
 	pip install twine
 	twine check dist/*
 
 pip_pkg_check:
 	docker run --rm -v $(current_dir):/sosse:ro biolds/sosse:pip-base bash -c 'cd /sosse && make _pip_pkg_check'
@@ -117,34 +119,33 @@
 	sed -e 's#pip install sosse#pip install dist/*.whl#' -i /tmp/code_blocks.json
 	bash ./tests/doc_test.sh /tmp/code_blocks.json install/pip
 
 _common_pip_functional_tests:
 	cp doc/code_blocks.json /tmp/code_blocks.json
 	grep -q 'sosse-admin default_conf' /tmp/code_blocks.json
 	sed -e 's#sosse-admin default_conf#sosse-admin default_conf | sed -e \\"s/^.browser_options=.*/browser_options=--enable-precise-memory-info --disable-default-apps --incognito --headless --no-sandbox/\\" -e \\"s/^.browser_crash_retry=.*/browser_crash_retry=3/\\" -e \\"s/^.crawler_count=.*/crawler_count=1/\\" -e \\"s/^.debug=.*/debug=true/\\"#' -i /tmp/code_blocks.json # add --no-sandbox to chromium's command line
+	echo 'SOSSE_ADMIN: /opt/sosse-venv/bin/sosse-admin' > tests/robotframework/config.yaml
 
 _deb_pkg_functional_tests:
-	echo 'deb http://deb.debian.org/debian bullseye-backports main' > /etc/apt/sources.list.d/bullseye-backports.list
-	apt update
-	grep ^Depends: debian/control | sed -e "s/.*},//" -e "s#python3-django [^,]*,#python3-django/bullseye-backports#g" -e "s/,//g" | xargs apt install -y
+	grep ^Depends: debian/control | sed -e "s/.*},//" -e "s/,//g" | xargs apt install -y
 	grep '^ExecStartPre=' debian/sosse-uwsgi.service | sed -e 's/^ExecStartPre=-\?+\?//' -e 's/^/---- /'
 	bash -c "`grep '^ExecStartPre=' debian/sosse-uwsgi.service | sed -e 's/^ExecStartPre=-\?+\?//'`"
 	cp doc/code_blocks.json /tmp/code_blocks.json
-	grep -q 'apt install -y python3-django/bullseye-backports sosse' /tmp/code_blocks.json
-	sed -e 's#apt install -y python3-django/bullseye-backports sosse#apt install -y python3-django/bullseye-backports sudo; dpkg -i deb/*.deb ; /etc/init.d/postgresql start \& bash ./tests/wait_for_pg.sh#' -i /tmp/code_blocks.json
+	grep -q 'apt install -y sosse' /tmp/code_blocks.json
+	sed -e 's#apt install -y sosse#apt install -y sudo; dpkg -i deb/*.deb ; /etc/init.d/postgresql start \& bash ./tests/wait_for_pg.sh#' -i /tmp/code_blocks.json
 	bash ./tests/doc_test.sh /tmp/code_blocks.json install/debian
 	sed -e 's/^.browser_options=.*/browser_options=--enable-precise-memory-info --disable-default-apps --incognito --headless --no-sandbox/' -i /etc/sosse/sosse.conf # add --no-sandbox to chromium's command line
 	sed -e 's/^.browser_crash_retry=.*/browser_crash_retry=3/' -i /etc/sosse/sosse.conf
 	sed -e 's/^.debug=.*/debug=true/' -i /etc/sosse/sosse.conf
 	sed -e 's/^.crawler_count=.*/crawler_count=1/' -i /etc/sosse/sosse.conf
 	/etc/init.d/nginx start
 	bash -c 'uwsgi --uid www-data --gid www-data --plugin python3 --ini /etc/sosse/uwsgi.ini --logto /var/log/sosse/uwsgi.log & sudo -u www-data sosse-admin crawl &'
 	bash ./tests/docker_run.sh docker/pip-test/Dockerfile
 
 _rf_functional_tests:
 	cat /etc/sosse/sosse.conf
 	virtualenv /rf-venv
 	/rf-venv/bin/pip install -r tests/robotframework/requirements.txt
-	cd ./tests/robotframework && /rf-venv/bin/robot --exitonerror --exitonfailure tests/
+	cd ./tests/robotframework && /rf-venv/bin/robot -V config.yaml --exitonerror --exitonfailure tests/
 
 functional_tests:
 	docker run --rm -v $(current_dir):/sosse biolds/sosse:pip-test bash -c 'cd /sosse && make _pip_functional_tests _rf_functional_tests'
```

### Comparing `sosse-1.0.1/PKG-INFO` & `sosse-1.1.0/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sosse
-Version: 1.0.1
+Version: 1.1.0
 Summary: Selenium Open Source Search Engine
 Author-email: Laurent Defert <laurent_defert@yahoo.fr>
 License: GNU Affero General Public License v3
 Keywords: search engine,crawler
 Classifier: Framework :: Django
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.9
@@ -31,15 +31,15 @@
 =======
 
 SOSSE (Selenium Open Source Search Engine) is a search engine and crawler written in Python, distributed under the [GNU-AGPLv3 license](https://www.gnu.org/licenses/agpl-3.0.en.html). It is hosted on both [Gitlab](https://gitlab.com/biolds1/sosse) and [Github](https://github.com/biolds/sosse) site, please use any of them to open feature requests, bug report or merge requests, or [open a discussion](https://github.com/biolds/sosse/discussions).
 
 SOSSE main features are:
 - 🌍 Browser based crawling: the crawler can use [Google Chromium](https://www.chromium.org/Home) and [Selenium](https://www.selenium.dev/) to index pages that use Javascript. [Requests](https://docs.python-requests.org/en/latest/index.html) can also be used for faster crawling
 - 🏖 Low resources requirements: SOSSE is entirely written in Python and uses [PostgreSQL](https://www.postgresql.org/) for data storage
-- 🖼 Offline cache: SOSSE can take screenshots of crawled pages and make them browsable offline
+- 🖼 Offline browsing: SOSSE can take screenshots of crawled pages and create archives suitable for offline browsing
 - 🔓 Authentication: the crawlers can submit authentication forms with provided credentials
 - 🔗 Search engines shortcuts: shortcuts search queries can be used to redirect to external search engines (sometime called "bang" searches)
 - 🔖 Search history: users can authenticate to log their search query history privately
 
 See the [documentation](https://sosse.readthedocs.io/en/stable/) and [screenshots](https://sosse.readthedocs.io/en/stable/screenshots.html).
 
 Try it out
@@ -47,15 +47,15 @@
 
 You can try the latest version with Docker:
 
 ```
 docker run -p 8005:80 biolds/sosse:latest
 ```
 
-Connect to port 8005, and log in with user ``admin``, with password ``admin``.
+Connect to port 8005, and log in with user ``admin``, password ``admin``.
 
 To persist Docker data, or find alternative installation methods, please check the [documentation](https://sosse.readthedocs.io/en/stable/install.html).
 
 Keep in touch
 =============
 
 Join the [Discord server](https://discord.gg/Vt9cMf7BGK) to get help and share ideas!
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: sosse Version: 1.0.1 Summary: Selenium Open Source
+Metadata-Version: 2.1 Name: sosse Version: 1.1.0 Summary: Selenium Open Source
 Search Engine Author-email: Laurent Defert
 yahoo.fr> License: GNU Affero General Public License v3 Keywords: search
 engine,crawler Classifier: Framework :: Django Classifier: Programming Language
 :: Python :: 3 Requires-Python: >=3.9 Description-Content-Type: text/markdown
 License-File: LICENSE
 [https://raw.githubusercontent.com/biolds/sosse/main/se/static/se/logo.svg]
 [https://img.shields.io/gitlab/pipeline-coverage/biolds1/
@@ -18,21 +18,22 @@
 or merge requests, or [open a discussion](https://github.com/biolds/sosse/
 discussions). SOSSE main features are: - ð Browser based crawling: the
 crawler can use [Google Chromium](https://www.chromium.org/Home) and [Selenium]
 (https://www.selenium.dev/) to index pages that use Javascript. [Requests]
 (https://docs.python-requests.org/en/latest/index.html) can also be used for
 faster crawling - ð Low resources requirements: SOSSE is entirely written in
 Python and uses [PostgreSQL](https://www.postgresql.org/) for data storage -
-ð¼ Offline cache: SOSSE can take screenshots of crawled pages and make them
-browsable offline - ð Authentication: the crawlers can submit authentication
-forms with provided credentials - ð Search engines shortcuts: shortcuts
-search queries can be used to redirect to external search engines (sometime
-called "bang" searches) - ð Search history: users can authenticate to log
-their search query history privately See the [documentation](https://
-sosse.readthedocs.io/en/stable/) and [screenshots](https://
-sosse.readthedocs.io/en/stable/screenshots.html). Try it out ========== You can
-try the latest version with Docker: ``` docker run -p 8005:80 biolds/sosse:
-latest ``` Connect to port 8005, and log in with user ``admin``, with password
-``admin``. To persist Docker data, or find alternative installation methods,
-please check the [documentation](https://sosse.readthedocs.io/en/stable/
-install.html). Keep in touch ============= Join the [Discord server](https://
-discord.gg/Vt9cMf7BGK) to get help and share ideas!
+ð¼ Offline browsing: SOSSE can take screenshots of crawled pages and create
+archives suitable for offline browsing - ð Authentication: the crawlers can
+submit authentication forms with provided credentials - ð Search engines
+shortcuts: shortcuts search queries can be used to redirect to external search
+engines (sometime called "bang" searches) - ð Search history: users can
+authenticate to log their search query history privately See the
+[documentation](https://sosse.readthedocs.io/en/stable/) and [screenshots]
+(https://sosse.readthedocs.io/en/stable/screenshots.html). Try it out
+========== You can try the latest version with Docker: ``` docker run -p 8005:
+80 biolds/sosse:latest ``` Connect to port 8005, and log in with user
+``admin``, password ``admin``. To persist Docker data, or find alternative
+installation methods, please check the [documentation](https://
+sosse.readthedocs.io/en/stable/install.html). Keep in touch ============= Join
+the [Discord server](https://discord.gg/Vt9cMf7BGK) to get help and share
+ideas!
```

### Comparing `sosse-1.0.1/README.md` & `sosse-1.1.0/README.md`

 * *Files 2% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 =======
 
 SOSSE (Selenium Open Source Search Engine) is a search engine and crawler written in Python, distributed under the [GNU-AGPLv3 license](https://www.gnu.org/licenses/agpl-3.0.en.html). It is hosted on both [Gitlab](https://gitlab.com/biolds1/sosse) and [Github](https://github.com/biolds/sosse) site, please use any of them to open feature requests, bug report or merge requests, or [open a discussion](https://github.com/biolds/sosse/discussions).
 
 SOSSE main features are:
 - 🌍 Browser based crawling: the crawler can use [Google Chromium](https://www.chromium.org/Home) and [Selenium](https://www.selenium.dev/) to index pages that use Javascript. [Requests](https://docs.python-requests.org/en/latest/index.html) can also be used for faster crawling
 - 🏖 Low resources requirements: SOSSE is entirely written in Python and uses [PostgreSQL](https://www.postgresql.org/) for data storage
-- 🖼 Offline cache: SOSSE can take screenshots of crawled pages and make them browsable offline
+- 🖼 Offline browsing: SOSSE can take screenshots of crawled pages and create archives suitable for offline browsing
 - 🔓 Authentication: the crawlers can submit authentication forms with provided credentials
 - 🔗 Search engines shortcuts: shortcuts search queries can be used to redirect to external search engines (sometime called "bang" searches)
 - 🔖 Search history: users can authenticate to log their search query history privately
 
 See the [documentation](https://sosse.readthedocs.io/en/stable/) and [screenshots](https://sosse.readthedocs.io/en/stable/screenshots.html).
 
 Try it out
@@ -34,15 +34,15 @@
 
 You can try the latest version with Docker:
 
 ```
 docker run -p 8005:80 biolds/sosse:latest
 ```
 
-Connect to port 8005, and log in with user ``admin``, with password ``admin``.
+Connect to port 8005, and log in with user ``admin``, password ``admin``.
 
 To persist Docker data, or find alternative installation methods, please check the [documentation](https://sosse.readthedocs.io/en/stable/install.html).
 
 Keep in touch
 =============
 
 Join the [Discord server](https://discord.gg/Vt9cMf7BGK) to get help and share ideas!
```

#### html2text {}

```diff
@@ -12,21 +12,22 @@
 or merge requests, or [open a discussion](https://github.com/biolds/sosse/
 discussions). SOSSE main features are: - ð Browser based crawling: the
 crawler can use [Google Chromium](https://www.chromium.org/Home) and [Selenium]
 (https://www.selenium.dev/) to index pages that use Javascript. [Requests]
 (https://docs.python-requests.org/en/latest/index.html) can also be used for
 faster crawling - ð Low resources requirements: SOSSE is entirely written in
 Python and uses [PostgreSQL](https://www.postgresql.org/) for data storage -
-ð¼ Offline cache: SOSSE can take screenshots of crawled pages and make them
-browsable offline - ð Authentication: the crawlers can submit authentication
-forms with provided credentials - ð Search engines shortcuts: shortcuts
-search queries can be used to redirect to external search engines (sometime
-called "bang" searches) - ð Search history: users can authenticate to log
-their search query history privately See the [documentation](https://
-sosse.readthedocs.io/en/stable/) and [screenshots](https://
-sosse.readthedocs.io/en/stable/screenshots.html). Try it out ========== You can
-try the latest version with Docker: ``` docker run -p 8005:80 biolds/sosse:
-latest ``` Connect to port 8005, and log in with user ``admin``, with password
-``admin``. To persist Docker data, or find alternative installation methods,
-please check the [documentation](https://sosse.readthedocs.io/en/stable/
-install.html). Keep in touch ============= Join the [Discord server](https://
-discord.gg/Vt9cMf7BGK) to get help and share ideas!
+ð¼ Offline browsing: SOSSE can take screenshots of crawled pages and create
+archives suitable for offline browsing - ð Authentication: the crawlers can
+submit authentication forms with provided credentials - ð Search engines
+shortcuts: shortcuts search queries can be used to redirect to external search
+engines (sometime called "bang" searches) - ð Search history: users can
+authenticate to log their search query history privately See the
+[documentation](https://sosse.readthedocs.io/en/stable/) and [screenshots]
+(https://sosse.readthedocs.io/en/stable/screenshots.html). Try it out
+========== You can try the latest version with Docker: ``` docker run -p 8005:
+80 biolds/sosse:latest ``` Connect to port 8005, and log in with user
+``admin``, password ``admin``. To persist Docker data, or find alternative
+installation methods, please check the [documentation](https://
+sosse.readthedocs.io/en/stable/install.html). Keep in touch ============= Join
+the [Discord server](https://discord.gg/Vt9cMf7BGK) to get help and share
+ideas!
```

### Comparing `sosse-1.0.1/debian/control` & `sosse-1.1.0/debian/control`

 * *Files 18% similar despite different names*

```diff
@@ -4,10 +4,10 @@
 Maintainer: Laurent DEFERT <laurent_defert@yahoo.fr>
 Build-Depends: debhelper (>=10), dh-python, python3, python3-setuptools
 Standards-Version: 4.0.0
 Homepage: 
 
 Package: sosse
 Architecture: any
-Depends: ${shlibs:Depends}, ${misc:Depends}, postgresql, nginx, uwsgi, uwsgi-plugin-python3, python3-django (>=2:3.2.12), python3-requests, python3-bs4, python3-html5lib, python3-psycopg2, python3-django-uwsgi, python3-langdetect, python3-pil, python3-publicsuffix2, python3-pygal, python3-lxml, python3-magic, python3-defusedxml, python3-selenium, libjs-jquery, chromium, chromium-driver, fonts-noto
+Depends: ${shlibs:Depends}, ${misc:Depends}, postgresql, nginx, uwsgi, uwsgi-plugin-python3, python3-django, python3-requests, python3-bs4, python3-html5lib, python3-psycopg2, python3-django-uwsgi, python3-langdetect, python3-pil, python3-publicsuffix2, python3-pygal, python3-lxml, python3-magic, python3-defusedxml, python3-selenium, libjs-jquery, chromium, chromium-driver, fonts-noto
 Description: Open Source Search Engine
  Open Source Search Engine
```

### Comparing `sosse-1.0.1/debian/sosse-crawler.service` & `sosse-1.1.0/debian/sosse-crawler.service`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/debian/sosse-uwsgi.service` & `sosse-1.1.0/debian/sosse-uwsgi.service`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/debian/sosse.conf` & `sosse-1.1.0/debian/sosse.conf`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/debian/sosse.postinst` & `sosse-1.1.0/debian/sosse.postinst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/debian/uwsgi.params` & `sosse-1.1.0/debian/uwsgi.params`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/Makefile` & `sosse-1.1.0/doc/Makefile`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/get_artifacts.py` & `sosse-1.1.0/doc/get_artifacts.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/make.bat` & `sosse-1.1.0/doc/make.bat`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/_extensions/code_blocks.py` & `sosse-1.1.0/doc/source/_extensions/code_blocks.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/admin_ui.rst` & `sosse-1.1.0/doc/source/admin_ui.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/authentication.rst` & `sosse-1.1.0/doc/source/authentication.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/conf.py` & `sosse-1.1.0/doc/source/conf.py`

 * *Files 6% similar despite different names*

```diff
@@ -22,15 +22,15 @@
 # https://www.sphinx-doc.org/en/master/usage/configuration.html#project-information
 import os
 import sys
 
 project = 'SOSSE'
 copyright = '2023, Laurent Defert'
 author = 'Laurent Defert'
-release = '1.0'
+release = '1.1'
 
 # -- General configuration ---------------------------------------------------
 # https://www.sphinx-doc.org/en/master/usage/configuration.html#general-configuration
 
 sys.path.append(os.path.abspath('_extensions'))
 extensions = ['code_blocks', 'myst_parser']
 test_code_output = 'code_blocks.json'
```

### Comparing `sosse-1.0.1/doc/source/crawl/add_to_queue.rst` & `sosse-1.1.0/doc/source/crawl/add_to_queue.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/crawl/crawl_depth.rst` & `sosse-1.1.0/doc/source/crawl/crawl_depth.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/crawl/policies.rst` & `sosse-1.1.0/doc/source/crawl/policies.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/documents.rst` & `sosse-1.1.0/doc/source/documents.rst`

 * *Files 20% similar despite different names*

```diff
@@ -37,7 +37,14 @@
 This indicates if the URL was not crawled due to a ``robots.txt`` rule. If necessary the ``robots.txt`` can be ignored in
 the :ref:`Domain settings <domain_ignore_robots>`.
 
 Too many redirects
 """"""""""""""""""
 
 Indicates if the page was not crawled due to too many redirection. The limit can be set in the :ref:`configuration file <conf_option_max_redirects>`.
+
+.. _document_show_on_homepage:
+
+Show on homepage
+""""""""""""""""
+
+When the :ref:`browsable home option <conf_option_browsable_home>` is enabled, this parameter can switch availability of the document from the homepage. (See :doc:`archive`)
```

### Comparing `sosse-1.0.1/doc/source/domain_settings.rst` & `sosse-1.1.0/doc/source/domain_settings.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/index.rst` & `sosse-1.1.0/doc/source/index.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/install/database.rst` & `sosse-1.1.0/doc/source/install/database.rst.template`

 * *Files 15% similar despite different names*

```diff
@@ -15,15 +15,15 @@
 Database schema
 """""""""""""""
 
 The initial database data can be injected with the following commands:
 
 .. code-block:: shell
 
-   sosse-admin migrate
-   sosse-admin update_se
+   |sosse-admin| migrate
+   |sosse-admin| update_se
 
 A default ``admin`` user with password ``admin`` can be created with:
 
 .. code-block:: shell
 
-   sosse-admin default_admin
+   |sosse-admin| default_admin
```

### Comparing `sosse-1.0.1/doc/source/install/debian.rst` & `sosse-1.1.0/doc/source/install/debian.rst`

 * *Files 7% similar despite different names*

```diff
@@ -10,33 +10,27 @@
    mkdir -p /etc/keyrings/
    curl http://piggledy.org/repo/apt/debian/public.gpg.key | gpg --dearmor > /etc/keyrings/piggledy.gpg
 
 Then setup the repository:
 
 .. code-block:: shell
 
-   echo 'deb [signed-by=/etc/keyrings/piggledy.gpg] http://piggledy.org/repo/apt/debian bullseye main' > /etc/apt/sources.list.d/piggledy.list
-
-SOSSE also requires a version of Django (3.2) that is not available in Debian Bullseye. A compatible version can be installed using the `Debian backports <https://backports.debian.org/>`_ repository:
-
-.. code-block:: shell
-
-   echo 'deb http://deb.debian.org/debian bullseye-backports main' > /etc/apt/sources.list.d/bullseye-backports.list
+   echo 'deb [signed-by=/etc/keyrings/piggledy.gpg] http://piggledy.org/repo/apt/debian bookworm main' > /etc/apt/sources.list.d/piggledy.list
 
 The SOSSE package can then be installed with its dependencies:
 
 .. code-block:: shell
 
    apt update
-   apt install -y python3-django/bullseye-backports sosse
+   apt install -y sosse
 
 Database setup
 --------------
 
-.. include:: database.rst
+.. include:: database_debian.rst
 
 Daemons setup
 -------------
 
 And then enable the daemons and start them:
 
 .. code-block:: shell
```

### Comparing `sosse-1.0.1/doc/source/install/docker.rst` & `sosse-1.1.0/doc/source/install/docker.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/install/pip.rst` & `sosse-1.1.0/doc/source/install/pip.rst`

 * *Files 14% similar despite different names*

```diff
@@ -11,55 +11,56 @@
 - `PostgreSQL <https://www.postgresql.org/>`_
 - `Google Chromium <https://www.chromium.org/Home>`_
 - `ChromeDriver <https://chromedriver.chromium.org/>`_
 
 Package install
 ---------------
 
-The installation can be done with the command:
+The installation can be done with the commands:
 
 .. code-block:: shell
 
-    pip install sosse
+    virtualenv /opt/sosse-venv/
+    /opt/sosse-venv/bin/pip install sosse
 
 Default Configuration
 ---------------------
 
 The default configuration and directories can be created with the commands:
 
 .. code-block:: shell
 
    mkdir -p /run/sosse /var/log/sosse /var/lib/sosse/downloads /var/lib/sosse/screenshots
    touch /var/log/sosse/crawler.log /var/log/sosse/debug.log /var/log/sosse/main.log /var/log/sosse/webserver.log
    chown -R www-data:www-data /run/sosse /var/lib/sosse /var/log/sosse
    mkdir /etc/sosse
-   sosse-admin default_conf > /etc/sosse/sosse.conf
+   /opt/sosse-venv/bin/sosse-admin default_conf > /etc/sosse/sosse.conf
 
 Static files
 ------------
 
 Static files will be copied to their target location with the following command.
 
 .. code-block:: shell
 
-   sosse-admin collectstatic --noinput --clear
+   /opt/sosse-venv/bin/sosse-admin collectstatic --noinput --clear
 
 Database setup
 --------------
 
-.. include:: database.rst
+.. include:: database_pip.rst
 
 WSGI server
 -----------
 
 You can install a WSGI server of your choice. If you wish to install `uWSGI <https://uwsgi-docs.readthedocs.io/en/latest/>`_, you can do:
 
 .. code-block:: shell
 
-   pip install uwsgi
+   /opt/sosse-venv/bin/pip install uwsgi
 
 And write the following config files:
 
 .. code-block:: shell
 
    nano /etc/sosse/uwsgi.ini
 
@@ -73,15 +74,15 @@
 
 After that, the server can be run in the background with:
 
 .. code-block:: shell
 
    mkdir /var/log/uwsgi
    chown www-data:www-data /var/log/uwsgi
-   uwsgi --uid www-data --gid www-data --ini /etc/sosse/uwsgi.ini --logto /var/log/uwsgi/sosse.log &
+   /opt/sosse-venv/bin/uwsgi --uid www-data --gid www-data --ini /etc/sosse/uwsgi.ini --logto /var/log/uwsgi/sosse.log &
 
 File permissions
 ----------------
 
 It's advised to restrict the permissions of the configuration files:
 
 .. code-block:: shell
@@ -113,14 +114,14 @@
 Crawlers
 --------
 
 Crawlers can now be started in the background with the command:
 
 .. code-block:: shell
 
-   sudo -u www-data sosse-admin crawl &
+   sudo -u www-data /opt/sosse-venv/bin/sosse-admin crawl &
 
 Next steps
 ----------
 
 Congrats! The installation is done, you can now point your brwoser to the Nginx and log in with the user ``admin`` and the password ``admin``.
 For more information about the configuration, you can follow the :doc:`../administration` pages.
```

### Comparing `sosse-1.0.1/doc/source/permissions.rst` & `sosse-1.1.0/doc/source/permissions.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/screenshots.rst` & `sosse-1.1.0/doc/source/screenshots.rst`

 * *Files 12% similar despite different names*

```diff
@@ -32,7 +32,13 @@
    :doc:`Real-time crawling status <crawl/status>`
 
 .. figure:: ../../tests/robotframework/screenshots/crawl_policy_decision_no_hilight.png
    :class: sosse-screenshot
    :scale: 50%
 
    :doc:`Crawl Policies setup <crawl/policies>`
+
+.. figure:: ../../tests/robotframework/screenshots/browsable_home.png
+   :class: sosse-screenshot
+   :scale: 50%
+
+   :doc:`Archive browsing <archive>`
```

### Comparing `sosse-1.0.1/doc/source/search_engines.rst` & `sosse-1.1.0/doc/source/search_engines.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/user/cached.rst` & `sosse-1.1.0/doc/source/user/cached.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/user/history.rst` & `sosse-1.1.0/doc/source/user/history.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/user/preferences.rst` & `sosse-1.1.0/doc/source/user/preferences.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/user/search.rst` & `sosse-1.1.0/doc/source/user/search.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/doc/source/user/shortcuts.rst` & `sosse-1.1.0/doc/source/user/shortcuts.rst`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/docker/Makefile` & `sosse-1.1.0/docker/Makefile`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 .PHONY=build
 
 build:
-	docker pull debian:bullseye
+	docker pull debian:bookworm
 	$(MAKE) -C debian build APT_PROXY=$(APT_PROXY) PIP_INDEX_URL=$(PIP_INDEX_URL) PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST)
 	$(MAKE) -C debian-pkg build APT_PROXY=$(APT_PROXY) PIP_INDEX_URL=$(PIP_INDEX_URL) PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST)
 	$(MAKE) -C debian-test build APT_PROXY=$(APT_PROXY) PIP_INDEX_URL=$(PIP_INDEX_URL) PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST)
 	$(MAKE) -C pip-base build APT_PROXY=$(APT_PROXY) PIP_INDEX_URL=$(PIP_INDEX_URL) PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST)
 	$(MAKE) -C pip-release build APT_PROXY=$(APT_PROXY) PIP_INDEX_URL=$(PIP_INDEX_URL) PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST)
 	$(MAKE) -C pip-test build APT_PROXY=$(APT_PROXY) PIP_INDEX_URL=$(PIP_INDEX_URL) PIP_TRUSTED_HOST=$(PIP_TRUSTED_HOST)
 	$(MAKE) -C doc build
```

### Comparing `sosse-1.0.1/docker/debian/Dockerfile` & `sosse-1.1.0/docker/debian/Dockerfile`

 * *Files 19% similar despite different names*

```diff
@@ -1,33 +1,32 @@
-FROM debian:bullseye
+FROM debian:bookworm
 ARG APT_PROXY=
 ARG PIP_INDEX_URL=
 ARG PIP_TRUSTED_HOST=
 RUN test -z "$APT_PROXY" || (echo "Acquire::http::Proxy \"$APT_PROXY\";" > /etc/apt/apt.conf.d/proxy.conf)
 RUN apt update
 RUN apt upgrade -y
-RUN apt install -y curl gpg fonts-noto
+RUN apt install -y curl gpg
 RUN curl http://piggledy.org/repo/apt/debian/public.gpg.key | gpg --dearmor > /usr/share/keyrings/piggledy.gpg
-RUN echo 'deb [signed-by=/usr/share/keyrings/piggledy.gpg] http://piggledy.org/repo/apt/debian bullseye main' > /etc/apt/sources.list.d/piggledy.list
-RUN echo 'deb http://deb.debian.org/debian bullseye-backports main' > /etc/apt/sources.list.d/bullseye-backports.list
+RUN echo 'deb [signed-by=/usr/share/keyrings/piggledy.gpg] http://piggledy.org/repo/apt/debian bookworm main' > /etc/apt/sources.list.d/piggledy.list
 RUN apt update
-RUN apt install -y python3-django/bullseye-backports sosse && \
+RUN apt install -y sosse && \
         apt-get clean autoclean && \
         apt-get autoremove --yes && \
         rm -rf /var/lib/cache /var/lib/log /usr/share/doc /usr/share/man
 
 RUN sosse-admin default_conf > /etc/sosse/sosse.conf
 RUN chown -R root:www-data /etc/sosse && chmod 750 /etc/sosse/ && chmod 640 /etc/sosse/*
 RUN sed -e 's/^#\(browser_options=.*\)$/\1 --no-sandbox/' -i /etc/sosse/sosse.conf
 RUN rm /etc/nginx/sites-enabled/default
 RUN ln -s /etc/nginx/sites-available/sosse.conf /etc/nginx/sites-enabled/
 
 WORKDIR /
 USER postgres
-RUN echo "listen_addresses='127.0.0.1'" >> /etc/postgresql/13/main/postgresql.conf
+RUN echo "listen_addresses='127.0.0.1'" >> /etc/postgresql/15/main/postgresql.conf
 RUN /etc/init.d/postgresql start && \
     psql --command "CREATE USER sosse WITH PASSWORD 'CHANGE ME';" && \
     createdb -O sosse sosse && \
     /etc/init.d/postgresql stop
 
 USER root
 RUN /etc/init.d/postgresql start && \
```

### Comparing `sosse-1.0.1/docker/debian-pkg/Dockerfile` & `sosse-1.1.0/docker/debian-pkg/Dockerfile`

 * *Files 4% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-FROM debian:bullseye
+FROM debian:bookworm
 ARG APT_PROXY=
 ARG PIP_INDEX_URL=
 ARG PIP_TRUSTED_HOST=
 RUN test -z "$APT_PROXY" || (echo "Acquire::http::Proxy \"$APT_PROXY\";" > /etc/apt/apt.conf.d/proxy.conf)
 RUN apt update && \
     apt upgrade -y && \
     apt install -y make build-essential python3-dev devscripts cdbs dh-python python3-setuptools curl gnupg2 && \
```

### Comparing `sosse-1.0.1/docker/debian-test/Dockerfile` & `sosse-1.1.0/docker/debian-test/Dockerfile`

 * *Files 10% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 FROM biolds/sosse:debian
 ARG APT_PROXY=
 ARG PIP_INDEX_URL=
 ARG PIP_TRUSTED_HOST=
 RUN test -z "$APT_PROXY" || (echo "Acquire::http::Proxy \"$APT_PROXY\";" > /etc/apt/apt.conf.d/proxy.conf)
 RUN apt purge -y sosse
-RUN apt install -y python3-coverage python3-virtualenv flake8 sudo jq make git/bullseye-backports
+RUN apt install -y python3-coverage python3-virtualenv flake8 sudo jq make git
 RUN /etc/init.d/postgresql start && \
     su - postgres -c "psql --command 'ALTER USER sosse WITH SUPERUSER;'" && \
     /etc/init.d/postgresql stop
 RUN git clone --depth=1 https://gitlab.com/biolds1/httpbin.git /root/httpbin && \
     cd /root/httpbin/httpbin && \
     python3 manage.py migrate && \
     python3 manage.py shell -c "from django.contrib.auth.models import User ; u = User.objects.create(username='admin', is_superuser=True, is_staff=True) ; u.set_password('admin') ; u.save()"
```

### Comparing `sosse-1.0.1/docker/pip-release/Dockerfile` & `sosse-1.1.0/docker/pip-release/Dockerfile`

 * *Files 6% similar despite different names*

```diff
@@ -1,11 +1,12 @@
 FROM biolds/sosse:pip-base
 ARG PIP_INDEX_URL=
 ARG PIP_TRUSTED_HOST=
-RUN pip install sosse uwsgi && pip cache purge
+RUN virtualenv /venv
+RUN /venv/bin/pip install sosse uwsgi && /venv/bin/pip cache purge
 RUN mkdir -p /etc/sosse/ /etc/sosse_src/ /var/log/sosse /var/log/uwsgi
 RUN sosse-admin default_conf | sed -e 's/^#db_pass.*/db_pass=sosse/' -e 's/^#\(browser_options=.*\)$/\1 --no-sandbox/' > /etc/sosse_src/sosse.conf
 ADD uwsgi.* /etc/sosse_src/
 ADD sosse.conf /etc/nginx/sites-enabled/default
 RUN chown -R root:www-data /etc/sosse /etc/sosse_src && chmod 750 /etc/sosse_src/ && chmod 640 /etc/sosse_src/*
 
 WORKDIR /
@@ -21,12 +22,12 @@
 mkdir -p /run/sosse \n \
 touch /var/log/sosse/{debug.log,main.log,crawler.log,uwsgi.log,webserver.log} \n \
 chown -R www-data:www-data /run/sosse /var/log/sosse/ \n \
 sosse-admin migrate \n \
 sosse-admin collectstatic --noinput \n \
 sosse-admin update_se \n \
 sosse-admin default_admin \n \
-/usr/local/bin/uwsgi --uid www-data --gid www-data --ini /etc/sosse/uwsgi.ini --logto /var/log/sosse/uwsgi.log & \n \
+/venv/bin/uwsgi --uid www-data --gid www-data --ini /etc/sosse/uwsgi.ini --logto /var/log/sosse/uwsgi.log & \n \
 /etc/init.d/nginx start \n \
 sosse-admin crawl & \n \
 tail -F /var/log/sosse/crawler.log' > /run.sh ; chmod +x /run.sh
 CMD /run.sh
```

### Comparing `sosse-1.0.1/docker/pip-test/Dockerfile` & `sosse-1.1.0/docker/pip-test/Dockerfile`

 * *Files 11% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 FROM biolds/sosse:pip-base
 ARG APT_PROXY=
 RUN test -z "$APT_PROXY" || (echo "Acquire::http::Proxy \"$APT_PROXY\";" > /etc/apt/apt.conf.d/proxy.conf)
-RUN apt install -y firefox-esr wget jq make git python3-virtualenv
+RUN apt install -y firefox-esr wget jq make git
 RUN test -z "$APT_PROXY" || rm /etc/apt/apt.conf.d/proxy.conf
 RUN wget https://github.com/mozilla/geckodriver/releases/download/v0.33.0/geckodriver-v0.33.0-linux64.tar.gz -O /tmp/gecko.tar.gz && \
     tar xvzf /tmp/gecko.tar.gz && \
     mv geckodriver /usr/local/bin/
 RUN mkdir -p /var/lib/sosse/screenshots && git clone --depth=1 https://github.com/GurvanKervern/dummy-static-website /var/lib/sosse/screenshots/website
```

### Comparing `sosse-1.0.1/pyproject.toml` & `sosse-1.1.0/pyproject.toml`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/admin.py` & `sosse-1.1.0/se/admin.py`

 * *Files 2% similar despite different names*

```diff
@@ -9,14 +9,15 @@
 # SOSSE is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even
 # the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
 # See the GNU Affero General Public License for more details.
 #
 # You should have received a copy of the GNU Affero General Public License along with SOSSE.
 # If not, see <https://www.gnu.org/licenses/>.
 
+from copy import copy
 from urllib.parse import urlencode
 
 from django import forms
 from django.conf import settings
 from django.contrib import admin, messages
 from django.core.exceptions import PermissionDenied
 from django.db import models
@@ -25,15 +26,15 @@
 from django.utils.html import format_html
 from django.utils.timezone import now
 from django.shortcuts import redirect, reverse
 from django.template import defaultfilters, response
 
 from .forms import AddToQueueForm
 from .models import AuthField, Document, DomainSetting, CrawlPolicy, SearchEngine, Cookie, ExcludedUrl, WorkerStats
-from .utils import human_datetime, human_dt
+from .utils import human_datetime, human_dt, reverse_no_escape
 
 
 class SEAdminSite(admin.AdminSite):
     def get_app_list(self, request):
         MODELS_ORDER = (
             ('se', ('CrawlPolicy', 'Document', 'DomainSetting', 'Cookie', 'ExcludedUrl', 'SearchEngine')),
             ('auth', ('Group', 'User'))
@@ -154,20 +155,21 @@
         doc.screenshot_format = Document.SCREENSHOT_JPG
         doc.save()
 
 
 @admin.register(Document)
 class DocumentAdmin(admin.ModelAdmin):
     list_display = ('_url', 'fav', 'title', 'lang', 'status', 'err', '_crawl_last', '_crawl_next', 'crawl_dt')
-    list_filter = (DocumentQueueFilter, 'lang_iso_639_1', DocumentErrorFilter,)
+    list_filter = (DocumentQueueFilter, 'lang_iso_639_1', DocumentErrorFilter, 'show_on_homepage')
     search_fields = ['url__regex', 'title__regex']
-    fields = ('url', 'crawl_policy', 'domain', 'cookies', 'cached', 'link', 'title', 'status',
+    fields = ['url', 'show_on_homepage', 'crawl_policy', 'domain', 'cookies', 'cached', 'link', 'title', 'status',
               'error', 'crawl_first', 'crawl_last', 'crawl_next', 'crawl_dt', 'crawl_recurse',
-              'robotstxt_rejected', 'too_many_redirects', 'mimetype', 'lang', '_content')
-    readonly_fields = fields
+              'robotstxt_rejected', 'too_many_redirects', 'mimetype', 'lang', '_content']
+    readonly_fields = copy(fields)
+    readonly_fields.remove('show_on_homepage')
     ordering = ('-crawl_last',)
     actions = [crawl_now, remove_from_crawl_queue, convert_to_jpg]
     list_per_page = settings.SOSSE_ADMIN_PAGE_SIZE
 
     def has_add_permission(self, request, obj=None):
         return False
 
@@ -196,14 +198,20 @@
         queryset = self.get_queryset(request).filter(id=object_id)
         r = action(self, request, queryset)
         messages.success(request, 'Done.')
         if isinstance(r, HttpResponse):
             return r
         return redirect(reverse('admin:se_document_change', args=(object_id,)))
 
+    def get_fields(self, request, obj=None):
+        fields = copy(super().get_fields(request, obj))
+        if not settings.SOSSE_BROWSABLE_HOME:
+            fields.remove('show_on_homepage')
+        return fields
+
     def render_change_form(self, request, context, *args, **kwargs):
         context['actions'] = self.get_action_choices(request)
         return super().render_change_form(request, context, *args, **kwargs)
 
     def add_to_queue(self, request):
         if not request.user.has_perm('se.add_document'):
             raise PermissionDenied
@@ -233,14 +241,15 @@
             crawl_recurse = form.cleaned_data.get('crawl_depth') or 0
             doc, created = Document.objects.get_or_create(url=form.cleaned_data['url'], defaults={'crawl_recurse': crawl_recurse})
             if not created:
                 doc.crawl_next = now()
                 if crawl_recurse:
                     doc.crawl_recurse = crawl_recurse
 
+            doc.show_on_homepage = True
             doc.save()
             messages.success(request, 'URL was queued.')
             return redirect(reverse('admin:crawl_status'))
 
         crawl_policy = CrawlPolicy.get_from_url(form.cleaned_data['url'])
         form = AddToQueueForm(request.POST, initial={'crawl_depth': crawl_policy.crawl_depth})
         form.is_valid()
@@ -382,17 +391,19 @@
 
     @staticmethod
     @admin.display(ordering='url')
     def _url(obj):
         return format_html('<span title="{}">{}</span>', obj.url, obj.url)
 
     @staticmethod
+    @admin.display(description='Content')
     def _content(obj):
         if obj.redirect_url:
-            return 'Redirected to %s' % obj.redirect_url
+            url = reverse_no_escape('cache', args=[obj.redirect_url])
+            return format_html('Redirected to <a href="{}">{}</a>', url, obj.redirect_url)
         return obj.content
 
     def delete_model(self, request, obj):
         obj.delete_screenshot()
         return super().delete_model(request, obj)
 
     def delete_queryset(self, request, queryset):
```

### Comparing `sosse-1.0.1/se/apps.py` & `sosse-1.1.0/se/apps.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/atom.py` & `sosse-1.1.0/se/atom.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/browser.py` & `sosse-1.1.0/se/browser.py`

 * *Files 1% similar despite different names*

```diff
@@ -643,15 +643,21 @@
             img_no += 1
 
         return os.path.join(base_dir, filename), img_no
 
     @classmethod
     def scroll_to_page(cls, page_no):
         _, height = cls.screen_size()
-        cls.driver.execute_script('window.scroll(0, %s)' % (page_no * height))
+        height *= page_no
+        cls.driver.execute_script('''
+            window.scroll(0, %s);
+            [...document.querySelectorAll('*')].filter(x => x.clientHeight < x.scrollHeight).forEach(e => {
+                e.scroll({left: 0, top: %s, behavior: 'instant'});
+            });
+        ''' % (height, height))
 
     @classmethod
     def get_link_pos_abs(cls, selector):
         return cls.driver.execute_script('''
             const e = document.evaluate('%s', document, null, XPathResult.FIRST_ORDERED_NODE_TYPE, null);
 
             if (e === null) {
```

### Comparing `sosse-1.0.1/se/cached.py` & `sosse-1.1.0/se/cached.py`

 * *Files 8% similar despite different names*

```diff
@@ -11,14 +11,15 @@
 # See the GNU Affero General Public License for more details.
 #
 # You should have received a copy of the GNU Affero General Public License along with SOSSE.
 # If not, see <https://www.gnu.org/licenses/>.
 
 from urllib.parse import unquote, urlparse
 
+from django.conf import settings
 from django.shortcuts import redirect, render, reverse
 from django.utils.html import format_html
 
 from .models import Document, CrawlPolicy, sanitize_url
 from .utils import url_beautify, reverse_no_escape
 
 
@@ -34,14 +35,23 @@
 
     url = urlparse(url)
     url = url._replace(netloc=unquote(url.netloc))
     url = url.geturl()
     return sanitize_url(url, True, True)
 
 
+def get_cached_doc(request, view_name):
+    doc = get_document(request)
+    if doc is None:
+        return unknown_url_view(request)
+    if settings.SOSSE_CACHE_FOLLOWS_REDIRECT and doc.redirect_url:
+        return redirect(reverse_no_escape(view_name, args=[doc.redirect_url]))
+    return doc
+
+
 def get_document(request):
     url = url_from_request(request)
     return Document.objects.filter(url=url).first()
 
 
 def get_context(doc):
     crawl_policy = CrawlPolicy.get_from_url(doc.url)
@@ -54,15 +64,15 @@
         page_title = format_html('<img src="{}" style="height: 32px; width: 32px; vertical-align: bottom" alt="icon"> {}', favicon, title)
     else:
         page_title = title
 
     return {
         'crawl_policy': crawl_policy,
         'doc': doc,
-        'www_redirect_url': doc.redirect_url and reverse_no_escape('www', args=[doc.redirect_url]),
+        'www_redirect_url': doc.redirect_url and reverse_no_escape('cache', args=[doc.redirect_url]),
         'head_title': title,
         'title': page_title,
         'beautified_url': beautified_url,
         'favicon': favicon
     }
```

### Comparing `sosse-1.0.1/se/forms.py` & `sosse-1.1.0/se/forms.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/login.py` & `sosse-1.1.0/se/login.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/management/commands/crawl.py` & `sosse-1.1.0/se/management/commands/crawl.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/management/commands/default_admin.py` & `sosse-1.1.0/se/management/commands/default_admin.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/management/commands/default_conf.py` & `sosse-1.1.0/se/management/commands/default_conf.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/management/commands/extract_doc.py` & `sosse-1.1.0/se/management/commands/extract_doc.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/management/commands/generate_secret.py` & `sosse-1.1.0/se/management/commands/generate_secret.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/management/commands/load_se.py` & `sosse-1.1.0/se/management/commands/load_se.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/management/commands/update_se.py` & `sosse-1.1.0/se/management/commands/update_se.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/migrations/0001_initial.py` & `sosse-1.1.0/se/migrations/0001_initial.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/migrations/0002_search_vector.py` & `sosse-1.1.0/se/migrations/0002_search_vector.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/models.py` & `sosse-1.1.0/se/models.py`

 * *Files 1% similar despite different names*

```diff
@@ -179,26 +179,28 @@
     crawl_first = models.DateTimeField(blank=True, null=True, verbose_name='Crawled first')
     crawl_last = models.DateTimeField(blank=True, null=True, verbose_name='Crawled last')
     crawl_next = models.DateTimeField(blank=True, null=True, verbose_name='Crawl next')
     crawl_dt = models.DurationField(blank=True, null=True, verbose_name='Crawl DT')
     crawl_recurse = models.PositiveIntegerField(default=0, verbose_name='Recursion remaining')
     error = models.TextField(blank=True, default='')
     error_hash = models.TextField(blank=True, default='')
+    show_on_homepage = models.BooleanField(default=False, help_text='Display this document on the homepage')
+
     worker_no = models.PositiveIntegerField(blank=True, null=True)
 
     supported_langs = None
 
     class Meta:
         indexes = [GinIndex(fields=(('vector',)))]
 
     def __str__(self):
         return self.url
 
     def get_absolute_url(self):
-        if self.screenshot_file:
+        if self.screenshot_file or self.redirect_url:
             return reverse_no_escape('screenshot', args=(self.url,))
         else:
             return reverse_no_escape('www', args=(self.url,))
 
     @classmethod
     def get_supported_langs(cls):
         if cls.supported_langs is not None:
@@ -287,15 +289,15 @@
                 _s = self._get_elem_text(child, True)
                 if _s:
                     if s:
                         s += ' '
                     s += _s
         return s
 
-    def _dom_walk(self, elem, crawl_policy, links):
+    def _dom_walk(self, elem, crawl_policy, links, base_url):
         if isinstance(elem, Doctype):
             return
 
         if elem.name in ('[document]', 'title', 'script', 'style'):
             return
 
         s = self._get_elem_text(elem)
@@ -306,30 +308,30 @@
                 links['text'] += ' '
 
             if elem.name == 'a':
                 href = elem.get('href')
                 if href and not href.startswith('data:'):
                     href = href.strip()
 
-                    href_for_policy = absolutize_url(self.url, href, True, True)
+                    href_for_policy = absolutize_url(base_url, href, True, True)
                     child_policy = CrawlPolicy.get_from_url(href_for_policy)
-                    href = absolutize_url(self.url, href, child_policy.keep_params, False)
+                    href = absolutize_url(base_url, href, child_policy.keep_params, False)
                     target = Document.queue(href, crawl_policy, self)
 
                     if target != self:
                         link = None
                         if target:
                             link = Link(doc_from=self,
                                         link_no=len(links['links']),
                                         doc_to=target,
                                         text=s,
                                         pos=len(links['text']))
                         elif crawl_policy.store_extern_links:
                             href = elem.get('href').strip()
-                            href = absolutize_url(self.url, href, True, True)
+                            href = absolutize_url(base_url, href, True, True)
                             link = Link(doc_from=self,
                                         link_no=len(links['links']),
                                         text=s,
                                         pos=len(links['text']),
                                         extern_url=href)
 
                         if link:
@@ -341,15 +343,15 @@
                 links['text'] += s
 
             if elem.name == 'a':
                 return
 
         if hasattr(elem, 'children'):
             for child in elem.children:
-                self._dom_walk(child, crawl_policy, links)
+                self._dom_walk(child, crawl_policy, links, base_url)
 
         if elem.name in ('div', 'p', 'li', 'h1', 'h2', 'h3', 'h4', 'h5', 'h6'):
             if links['text']:
                 if links['text'][-1] == ' ':
                     links['text'] = links['text'][:-1] + '\n'
                 elif links['text'][-1] != '\n':
                     links['text'] += '\n'
@@ -379,38 +381,48 @@
 
         self.content_hash = content_hash
         self._index_log('queuing links', stats, verbose)
 
         beautified_url = url_beautify(page.url)
         normalized_url = beautified_url.split('://', 1)[1].replace('/', ' ').strip()
         self.normalized_url = remove_accent(normalized_url)
-        from magic import from_buffer as magic_from_buffer
-        self.mimetype = magic_from_buffer(page.content, mime=True)
+
+        # dirty hack to avoid some errors (as triggered since bookworm during tests)
+        magic_head = page.content[:10].strip().lower()
+        if magic_head.startswith('<html'):
+            self.mimetype = 'text/html'
+        else:
+            from magic import from_buffer as magic_from_buffer
+            self.mimetype = magic_from_buffer(page.content, mime=True)
 
         if not re.match(crawl_policy.mimetype_regex, self.mimetype):
             crawl_logger.debug('skipping %s due to mimetype %s' % (self.url, self.mimetype))
             return
 
         if self.mimetype.startswith('text/'):
             parsed = page.get_soup()
             if page.title:
                 self.title = page.title
             else:
                 self.title = beautified_url
 
+            base_url = self.url
+            if parsed.head.base and parsed.head.base.get('href'):
+                base_url = absolutize_url(self.url, parsed.head.base.get('href'), False, False)
+
             self.normalized_title = remove_accent(self.title)
 
             self._index_log('get soup', stats, verbose)
 
             links = {
                 'links': [],
                 'text': ''
             }
             for elem in parsed.children:
-                self._dom_walk(elem, crawl_policy, links)
+                self._dom_walk(elem, crawl_policy, links, base_url)
             text = links['text']
 
             self._index_log('text / %i links extraction' % len(links['links']), stats, verbose)
 
             self.content = text
             self.normalized_content = remove_accent(text)
             self.lang_iso_639_1, self.vector_lang = self._get_lang((page.title or '') + '\n' + text)
```

### Comparing `sosse-1.0.1/se/screenshot.py` & `sosse-1.1.0/se/screenshot.py`

 * *Files 6% similar despite different names*

```diff
@@ -10,27 +10,28 @@
 # the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
 # See the GNU Affero General Public License for more details.
 #
 # You should have received a copy of the GNU Affero General Public License along with SOSSE.
 # If not, see <https://www.gnu.org/licenses/>.
 
 from django.conf import settings
+from django.http import HttpResponse
 from django.shortcuts import render
 
 from .browser import SeleniumBrowser
-from .cached import get_document, get_context, unknown_url_view
+from .cached import get_cached_doc, get_context
 from .login import login_required
 from .utils import reverse_no_escape
 
 
 @login_required
 def screenshot(request):
-    doc = get_document(request)
-    if doc is None:
-        return unknown_url_view(request)
+    doc = get_cached_doc(request, 'screenshot')
+    if isinstance(doc, HttpResponse):
+        return doc
 
     base_dir, filename = SeleniumBrowser.screenshot_name(doc.url)
 
     context = get_context(doc)
     context.update({
         'screenshot': settings.SOSSE_SCREENSHOTS_URL + '/' + base_dir + '/' + filename,
         'screenshot_size': doc.screenshot_size.split('x'),
```

### Comparing `sosse-1.0.1/se/search.py` & `sosse-1.1.0/se/search.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/admin-base.css` & `sosse-1.1.0/se/static/se/admin-base.css`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/admin-forms.css` & `sosse-1.1.0/se/static/se/admin-forms.css`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/base.js` & `sosse-1.1.0/se/static/se/base.js`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/icon-atom.svg` & `sosse-1.1.0/se/static/se/icon-atom.svg`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/icon-clear.svg` & `sosse-1.1.0/se/static/se/icon-clear.svg`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/icon-cog.svg` & `sosse-1.1.0/se/static/se/icon-cog.svg`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/icon-search.svg` & `sosse-1.1.0/se/static/se/icon-search.svg`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/icon-stats.svg` & `sosse-1.1.0/se/static/se/icon-stats.svg`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/icon-trash.svg` & `sosse-1.1.0/se/static/se/icon-trash.svg`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/icon-user.svg` & `sosse-1.1.0/se/static/se/icon-user.svg`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/index.js` & `sosse-1.1.0/se/static/se/index.js`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/logo.png` & `sosse-1.1.0/se/static/se/logo.png`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/logo.svg` & `sosse-1.1.0/se/static/se/logo.svg`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/pygal-tooltips.min.js` & `sosse-1.1.0/se/static/se/pygal-tooltips.min.js`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/screenshot.js` & `sosse-1.1.0/se/static/se/screenshot.js`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/static/se/style.css` & `sosse-1.1.0/se/static/se/style.css`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/stats.py` & `sosse-1.1.0/se/stats.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/admin/add_to_queue.html` & `sosse-1.1.0/se/templates/admin/add_to_queue.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/admin/app_list.html` & `sosse-1.1.0/se/templates/admin/app_list.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/admin/base.html` & `sosse-1.1.0/se/templates/admin/base.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/admin/change_form.html` & `sosse-1.1.0/se/templates/admin/change_form.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/admin/crawl_status.html` & `sosse-1.1.0/se/templates/admin/crawl_status.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/admin/crawl_status_content.html` & `sosse-1.1.0/se/templates/admin/crawl_status_content.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/about.html` & `sosse-1.1.0/se/templates/se/about.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/base.html` & `sosse-1.1.0/se/templates/se/base.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/cached.html` & `sosse-1.1.0/se/templates/se/cached.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/history.html` & `sosse-1.1.0/se/templates/se/history.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/index.html` & `sosse-1.1.0/se/templates/se/index.html`

 * *Files 6% similar despite different names*

```diff
@@ -42,14 +42,59 @@
     }
     .res-preview {
         float: right;
         width: 160px;
         height: 100px;
     }
 
+    #home-grid {
+        display: grid;
+        grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
+        grid-auto-rows: minmax(100px, auto);
+    }
+
+    #home-grid a {
+        text-decoration: none;
+    }
+
+    .res-home {
+        display: block;
+        position: relative;
+        grid-column: auto;
+        grid-row: auto;
+        width: 200px;
+        height: 200px;
+        text-align: center;
+        overflow: hidden;
+    }
+    .res-home-icon {
+        padding-top: 30%;
+        width: 100%;
+    }
+    .res-home-icon > img {
+        width: 64px;
+        height: 64px;
+    }
+    .res-home-fade-text {
+      position: absolute;
+      bottom: 0;
+      left: 0;
+      margin: 0;
+      width: 100%;
+      height: 24px;
+    }
+
+    .res .res-home-fade-text {
+      background-image: linear-gradient(to bottom, transparent, white);
+    }
+
+    .res:hover .res-home-fade-text {
+      background-image: linear-gradient(to bottom, transparent, #f4f4f4);
+    }
+
     #search_field {
         text-align: center;
         padding: 10px;
     }
     #more {
         color: #000;
         text-decoration: none;
@@ -256,9 +301,12 @@
                 <div class="res-rank"> · <a href="{{ r.extra_link }}">{{ extra_link_txt }}</a></div>
                 <br/>
                 <a href="{{ r.link }}" class="res-headline">{{ r.headline }}</a>
             </div>
         {% endfor %}
 
         {% include 'se/pagination.html' %}
+    {% elif settings.SOSSE_BROWSABLE_HOME %}
+        {% include 'se/home_browse.html' %}
     {% endif %}
+
 {% endblock %}
```

#### html2text {}

```diff
@@ -3,34 +3,44 @@
  {% endblock %} {% block css %} .res { margin: 6px 0px 6px 0px; padding: 10px
 10px 10px 10px; border-radius: 10px; } .res:hover { background-color: #f4f4f4;
 } .res-img { height: 16px; width: 16px; display: inline; } .res-title { margin-
 bottom: 0px; display: inline; } .res-url { text-decoration: none; color: #080;
 font-size: 13px; } .res-rank { font-size: 10px; display: inline; } .res-
 headline { text-decoration: none; color: #000; } .res-highlight { background-
 color: #c6dcff; } .res-preview { float: right; width: 160px; height: 100px; }
-#search_field { text-align: center; padding: 10px; } #more { color: #000; text-
-decoration: none; font-size: 13px; } #adv_search { padding-top: 20px; }
-#stats_menu { right: 8px; width: 160px; top: 88px; } #atom_menu { right: 8px;
-width: 160px; top: 128px; } #word_stats { float: right; text-align: left;
-overflow-y: scroll; height: 300px; width: 250px; } #word_stats_list { list-
-style-type: none; margin: 0; padding: 0; } .word_stats_txt { width: 90%;
-margin-right: -8px; padding: 2px 0px 2px 8px; display: inline; } .links:hover
-.word_stats_txt { background-color: #e7f0ff; } .word_stats_count { width: 10%;
-text-align: right; display: inline; } .links:hover .word_stats_count
-{ background-color: #e7f0ff; } .dyn_button { width: 38px; text-align: center; }
-#clear_button { background-size: 20px; background-image: url('{% static "se/
-icon-clear.svg" %}'); width: 40px; height: 40px; } #id_q { padding: 11px; min-
-width: 30%; height: 17px; } #id_q:hover + #clear_button { background-color:
-#eee; } #id_q:focus + #clear_button { outline: 0px; border-style: solid;
-border-bottom-width: 1px; border-color: #6066bf; } #search_button { margin-
-left: 5px; background-image: url('{% static "se/icon-search.svg" %}'); width:
-40px; height: 40px; } #stats_button { background-image: url('{% static "se/
-icon-stats.svg" %}'); } #atom_button { background-image: url('{% static "se/
-icon-atom.svg" %}'); } #top_bar { min-height: 157px; padding-bottom: 10px; }
-input[name="fv"] { min-width: 350px; } {% endblock %} {% block top_bar %}
+#home-grid { display: grid; grid-template-columns: repeat(auto-fill, minmax
+(200px, 1fr)); grid-auto-rows: minmax(100px, auto); } #home-grid a { text-
+decoration: none; } .res-home { display: block; position: relative; grid-
+column: auto; grid-row: auto; width: 200px; height: 200px; text-align: center;
+overflow: hidden; } .res-home-icon { padding-top: 30%; width: 100%; } .res-
+home-icon > img { width: 64px; height: 64px; } .res-home-fade-text { position:
+absolute; bottom: 0; left: 0; margin: 0; width: 100%; height: 24px; } .res
+.res-home-fade-text { background-image: linear-gradient(to bottom, transparent,
+white); } .res:hover .res-home-fade-text { background-image: linear-gradient(to
+bottom, transparent, #f4f4f4); } #search_field { text-align: center; padding:
+10px; } #more { color: #000; text-decoration: none; font-size: 13px; }
+#adv_search { padding-top: 20px; } #stats_menu { right: 8px; width: 160px; top:
+88px; } #atom_menu { right: 8px; width: 160px; top: 128px; } #word_stats
+{ float: right; text-align: left; overflow-y: scroll; height: 300px; width:
+250px; } #word_stats_list { list-style-type: none; margin: 0; padding: 0; }
+.word_stats_txt { width: 90%; margin-right: -8px; padding: 2px 0px 2px 8px;
+display: inline; } .links:hover .word_stats_txt { background-color: #e7f0ff; }
+.word_stats_count { width: 10%; text-align: right; display: inline; } .links:
+hover .word_stats_count { background-color: #e7f0ff; } .dyn_button { width:
+38px; text-align: center; } #clear_button { background-size: 20px; background-
+image: url('{% static "se/icon-clear.svg" %}'); width: 40px; height: 40px; }
+#id_q { padding: 11px; min-width: 30%; height: 17px; } #id_q:hover +
+#clear_button { background-color: #eee; } #id_q:focus + #clear_button
+{ outline: 0px; border-style: solid; border-bottom-width: 1px; border-color:
+#6066bf; } #search_button { margin-left: 5px; background-image: url('{% static
+"se/icon-search.svg" %}'); width: 40px; height: 40px; } #stats_button
+{ background-image: url('{% static "se/icon-stats.svg" %}'); } #atom_button
+{ background-image: url('{% static "se/icon-atom.svg" %}'); } #top_bar { min-
+height: 157px; padding-bottom: 10px; } input[name="fv"] { min-width: 350px; }
+{% endblock %} {% block top_bar %}
 {% for field in form.hidden_fields %} {{ field }} {% endfor %} {{ form.q }}[ ]
 â®_params
  [Unknown INPUT type] [Unknown INPUT type] [One of: Keep/Exclude] [One of:
 Document/Content/Title/URL/Mimetype/Links to url/Links to text/Linked by url/
 Linked by text] [One of: Containing/Equal to/Matching Regexp] [fv
 ] ⁰ Case sensitive
 {% for key, val in sosse_langdetect_to_postgres.items %}
@@ -56,8 +66,10 @@
 ****_{{_r.title_}}_****
 {{_r.url_}}
 Â· {{ r.rank|floatformat:"1" }}
 Â· {{ r.lang_flag }}
 Â· {{_extra_link_txt_}}
 
 {{_r.headline_}}
-{% endfor %} {% include 'se/pagination.html' %} {% endif %} {% endblock %}
+{% endfor %} {% include 'se/pagination.html' %} {% elif
+settings.SOSSE_BROWSABLE_HOME %} {% include 'se/home_browse.html' %} {% endif
+%} {% endblock %}
```

### Comparing `sosse-1.0.1/se/templates/se/main_menu.html` & `sosse-1.1.0/se/templates/se/main_menu.html`

 * *Files 1% similar despite different names*

```diff
@@ -15,15 +15,15 @@
         {% else %}
             <a href="{% url 'login' %}" class="links menu_links">Log in</a>
         {% endif %}
         <a href="{% url 'about' %}" class="links menu_links">About</a>
     </div>
 </div>
 {% if user.is_active and user.is_staff %}
-    <div id="conf_menu" class="menu" title="Configuration">
-        <button class="menu_button img_button" id="conf_menu_button"></button>
+    <div id="conf_menu" class="menu">
+        <button class="menu_button img_button" id="conf_menu_button" title="Configuration"></button>
         <div id="conf_menu_panel" class="panel">
             <a href="/stats/" class="links menu_links">Statistics</a>
             <a href="/admin/" class="links menu_links">Administration</a>
         </div>
     </div>
 {% endif %}
```

### Comparing `sosse-1.0.1/se/templates/se/opensearch.xml` & `sosse-1.1.0/se/templates/se/opensearch.xml`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/pagination.html` & `sosse-1.1.0/se/templates/se/pagination.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/prefs.html` & `sosse-1.1.0/se/templates/se/prefs.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/screenshot.html` & `sosse-1.1.0/se/templates/se/screenshot.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/search_redirect.html` & `sosse-1.1.0/se/templates/se/search_redirect.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/stats.html` & `sosse-1.1.0/se/templates/se/stats.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/templates/se/unknown_url.html` & `sosse-1.1.0/se/templates/se/unknown_url.html`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/test_cookie.py` & `sosse-1.1.0/se/test_cookie.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/test_crawl.py` & `sosse-1.1.0/se/test_crawl.py`

 * *Files 1% similar despite different names*

```diff
@@ -304,7 +304,30 @@
         doc = Document.objects.get()
         self.assertEqual(doc.url, 'http://127.0.0.1/')
         self.assertEqual(doc.content, 'Hello world')
         self.assertEqual(doc.crawl_first, self.fake_now)
         self.assertEqual(doc.crawl_last, self.fake_next2)
         self.assertEqual(doc.crawl_next, self.fake_next3)
         self.assertEqual(doc.crawl_dt, timedelta(hours=3))
+
+    @mock.patch('se.browser.RequestBrowser.get')
+    def test_008_base_header(self, RequestBrowser):
+        RequestBrowser.side_effect = BrowserMock({
+            'http://127.0.0.1/': '''
+                <html>
+                    <head><base href="/base/" /></head>
+                    <body>
+                        <a href="test">base test</a>
+                    </body>
+                </html>
+                ''',
+            'http://127.0.0.1/base/test': 'test page'
+        })
+
+        self._crawl()
+
+        self.assertEqual(Document.objects.count(), 2)
+        doc1, doc2 = Document.objects.order_by('id')
+        self.assertEqual(doc1.url, 'http://127.0.0.1/')
+        self.assertEqual(doc1.content, 'base test')
+        self.assertEqual(doc2.url, 'http://127.0.0.1/base/test')
+        self.assertEqual(doc2.content, 'test page')
```

### Comparing `sosse-1.0.1/se/test_functionals.py` & `sosse-1.1.0/se/test_functionals.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/test_misc.py` & `sosse-1.1.0/se/test_misc.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/test_parser.py` & `sosse-1.1.0/se/test_parser.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/test_redirect.py` & `sosse-1.1.0/se/test_redirect.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/test_requests.py` & `sosse-1.1.0/se/test_requests.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/test_search.py` & `sosse-1.1.0/se/test_search.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/test_url.py` & `sosse-1.1.0/se/test_url.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/test_views.py` & `sosse-1.1.0/se/test_views.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/utils.py` & `sosse-1.1.0/se/utils.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/views.py` & `sosse-1.1.0/se/views.py`

 * *Files 2% similar despite different names*

```diff
@@ -134,21 +134,26 @@
                 r.link = r.url
                 r.extra_link = r.get_absolute_url()
 
     extra_link_txt = 'cached'
     if form.cleaned_data['c']:
         extra_link_txt = 'source'
 
+    home_entries = None
+    if not has_query and settings.SOSSE_BROWSABLE_HOME:
+        home_entries = Document.objects.filter(show_on_homepage=True).order_by('title')
+
     context = get_context({
         'hide_title': True,
         'form': form,
         'results': results,
         'results_count': human_nb(len(results)),
         'paginated': paginated,
         'has_query': has_query,
+        'home_entries': home_entries,
         'q': q,
         'title': q,
         'sosse_langdetect_to_postgres': sosse_langdetect_to_postgres,
         'extra_link_txt': extra_link_txt
     })
     context.update(get_pagination(request, paginated))
     return render(request, 'se/index.html', context)
```

### Comparing `sosse-1.0.1/se/words.py` & `sosse-1.1.0/se/words.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/se/www.py` & `sosse-1.1.0/se/www.py`

 * *Files 8% similar despite different names*

```diff
@@ -9,28 +9,29 @@
 # SOSSE is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even
 # the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
 # See the GNU Affero General Public License for more details.
 #
 # You should have received a copy of the GNU Affero General Public License along with SOSSE.
 # If not, see <https://www.gnu.org/licenses/>.
 
+from django.http import HttpResponse
 from django.shortcuts import render
 from django.utils.html import format_html
 
-from .cached import get_document, get_context, unknown_url_view
+from .cached import get_cached_doc, get_context
 from .login import login_required
 from .models import Link
 from .utils import reverse_no_escape
 
 
 @login_required
 def www(request):
-    doc = get_document(request)
-    if doc is None:
-        return unknown_url_view(request)
+    doc = get_cached_doc(request, 'www')
+    if isinstance(doc, HttpResponse):
+        return doc
 
     content = format_html('')
     content_pos = 0
 
     links = Link.objects.filter(doc_from=doc).order_by('link_no')
     links_count = Link.objects.filter(doc_from=doc).count()
     link_no = 0
```

### Comparing `sosse-1.0.1/sosse/conf.py` & `sosse-1.1.0/sosse/conf.py`

 * *Files 2% similar despite different names*

```diff
@@ -165,28 +165,38 @@
             'type': bool
         }],
         ['exclude_redirect', {
             'comment': 'Exclude page redirection from search results.',
             'default': True,
             'type': bool
         }],
+        ['cache_follows_redirect', {
+            'comment': 'Accessing a cached page of an url that redirected automatically follows the redirection.',
+            'default': True,
+            'type': bool
+        }],
         ['admin_page_size', {
             'comment': 'Number of items by list in the administration pages.',
             'default': 100,
             'type': int
         }],
         ['search_strip', {
             'comment': 'Removes this string from search queries.',
             'default': '',
         }],
         ['crawl_status_autorefresh', {
             'comment': 'Delay between crawl status page autorefresh (in seconds).',
             'default': 5,
             'type': int
         }],
+        ['browsable_home', {
+            'comment': 'Display entry point documents on the homepage.',
+            'default': False,
+            'type': bool
+        }],
     ])],
     ['crawler', OrderedDict([
         ['crawler_count', {
             'comment': 'Number of crawlers running concurrently (default to the number of CPU available).',
             'default': ''
         }],
         ['proxy', {
```

### Comparing `sosse-1.0.1/sosse/search_engines.json` & `sosse-1.1.0/sosse/search_engines.json`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/sosse/settings.py` & `sosse-1.1.0/sosse/settings.py`

 * *Files 0% similar despite different names*

```diff
@@ -325,9 +325,9 @@
         'name': 'chinese',
         'flag': '🇹🇼'
     }
 }
 
 globals().update(Conf.get())
 
-SOSSE_VERSION_TAG = '1.0.1'
-SOSSE_VERSION_COMMIT = '90f57b03'
+SOSSE_VERSION_TAG = '1.1.0'
+SOSSE_VERSION_COMMIT = '46ea944e'
```

### Comparing `sosse-1.0.1/sosse/sosse_admin.py` & `sosse-1.1.0/sosse/sosse_admin.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/sosse/urls.py` & `sosse-1.1.0/sosse/urls.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/sosse/wsgi.py` & `sosse-1.1.0/sosse/wsgi.py`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/sosse.egg-info/PKG-INFO` & `sosse-1.1.0/sosse.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: sosse
-Version: 1.0.1
+Version: 1.1.0
 Summary: Selenium Open Source Search Engine
 Author-email: Laurent Defert <laurent_defert@yahoo.fr>
 License: GNU Affero General Public License v3
 Keywords: search engine,crawler
 Classifier: Framework :: Django
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.9
@@ -31,15 +31,15 @@
 =======
 
 SOSSE (Selenium Open Source Search Engine) is a search engine and crawler written in Python, distributed under the [GNU-AGPLv3 license](https://www.gnu.org/licenses/agpl-3.0.en.html). It is hosted on both [Gitlab](https://gitlab.com/biolds1/sosse) and [Github](https://github.com/biolds/sosse) site, please use any of them to open feature requests, bug report or merge requests, or [open a discussion](https://github.com/biolds/sosse/discussions).
 
 SOSSE main features are:
 - 🌍 Browser based crawling: the crawler can use [Google Chromium](https://www.chromium.org/Home) and [Selenium](https://www.selenium.dev/) to index pages that use Javascript. [Requests](https://docs.python-requests.org/en/latest/index.html) can also be used for faster crawling
 - 🏖 Low resources requirements: SOSSE is entirely written in Python and uses [PostgreSQL](https://www.postgresql.org/) for data storage
-- 🖼 Offline cache: SOSSE can take screenshots of crawled pages and make them browsable offline
+- 🖼 Offline browsing: SOSSE can take screenshots of crawled pages and create archives suitable for offline browsing
 - 🔓 Authentication: the crawlers can submit authentication forms with provided credentials
 - 🔗 Search engines shortcuts: shortcuts search queries can be used to redirect to external search engines (sometime called "bang" searches)
 - 🔖 Search history: users can authenticate to log their search query history privately
 
 See the [documentation](https://sosse.readthedocs.io/en/stable/) and [screenshots](https://sosse.readthedocs.io/en/stable/screenshots.html).
 
 Try it out
@@ -47,15 +47,15 @@
 
 You can try the latest version with Docker:
 
 ```
 docker run -p 8005:80 biolds/sosse:latest
 ```
 
-Connect to port 8005, and log in with user ``admin``, with password ``admin``.
+Connect to port 8005, and log in with user ``admin``, password ``admin``.
 
 To persist Docker data, or find alternative installation methods, please check the [documentation](https://sosse.readthedocs.io/en/stable/install.html).
 
 Keep in touch
 =============
 
 Join the [Discord server](https://discord.gg/Vt9cMf7BGK) to get help and share ideas!
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: sosse Version: 1.0.1 Summary: Selenium Open Source
+Metadata-Version: 2.1 Name: sosse Version: 1.1.0 Summary: Selenium Open Source
 Search Engine Author-email: Laurent Defert
 yahoo.fr> License: GNU Affero General Public License v3 Keywords: search
 engine,crawler Classifier: Framework :: Django Classifier: Programming Language
 :: Python :: 3 Requires-Python: >=3.9 Description-Content-Type: text/markdown
 License-File: LICENSE
 [https://raw.githubusercontent.com/biolds/sosse/main/se/static/se/logo.svg]
 [https://img.shields.io/gitlab/pipeline-coverage/biolds1/
@@ -18,21 +18,22 @@
 or merge requests, or [open a discussion](https://github.com/biolds/sosse/
 discussions). SOSSE main features are: - ð Browser based crawling: the
 crawler can use [Google Chromium](https://www.chromium.org/Home) and [Selenium]
 (https://www.selenium.dev/) to index pages that use Javascript. [Requests]
 (https://docs.python-requests.org/en/latest/index.html) can also be used for
 faster crawling - ð Low resources requirements: SOSSE is entirely written in
 Python and uses [PostgreSQL](https://www.postgresql.org/) for data storage -
-ð¼ Offline cache: SOSSE can take screenshots of crawled pages and make them
-browsable offline - ð Authentication: the crawlers can submit authentication
-forms with provided credentials - ð Search engines shortcuts: shortcuts
-search queries can be used to redirect to external search engines (sometime
-called "bang" searches) - ð Search history: users can authenticate to log
-their search query history privately See the [documentation](https://
-sosse.readthedocs.io/en/stable/) and [screenshots](https://
-sosse.readthedocs.io/en/stable/screenshots.html). Try it out ========== You can
-try the latest version with Docker: ``` docker run -p 8005:80 biolds/sosse:
-latest ``` Connect to port 8005, and log in with user ``admin``, with password
-``admin``. To persist Docker data, or find alternative installation methods,
-please check the [documentation](https://sosse.readthedocs.io/en/stable/
-install.html). Keep in touch ============= Join the [Discord server](https://
-discord.gg/Vt9cMf7BGK) to get help and share ideas!
+ð¼ Offline browsing: SOSSE can take screenshots of crawled pages and create
+archives suitable for offline browsing - ð Authentication: the crawlers can
+submit authentication forms with provided credentials - ð Search engines
+shortcuts: shortcuts search queries can be used to redirect to external search
+engines (sometime called "bang" searches) - ð Search history: users can
+authenticate to log their search query history privately See the
+[documentation](https://sosse.readthedocs.io/en/stable/) and [screenshots]
+(https://sosse.readthedocs.io/en/stable/screenshots.html). Try it out
+========== You can try the latest version with Docker: ``` docker run -p 8005:
+80 biolds/sosse:latest ``` Connect to port 8005, and log in with user
+``admin``, password ``admin``. To persist Docker data, or find alternative
+installation methods, please check the [documentation](https://
+sosse.readthedocs.io/en/stable/install.html). Keep in touch ============= Join
+the [Discord server](https://discord.gg/Vt9cMf7BGK) to get help and share
+ideas!
```

### Comparing `sosse-1.0.1/sosse.egg-info/SOURCES.txt` & `sosse-1.1.0/sosse.egg-info/SOURCES.txt`

 * *Files 3% similar despite different names*

```diff
@@ -26,14 +26,15 @@
 doc/Makefile
 doc/build_changelog.sh
 doc/get_artifacts.py
 doc/make.bat
 doc/requirements.txt
 doc/source/admin_ui.rst
 doc/source/administration.rst
+doc/source/archive.rst
 doc/source/authentication.rst
 doc/source/cli.rst
 doc/source/conf.py
 doc/source/config_file.rst
 doc/source/cookies.rst
 doc/source/documents.rst
 doc/source/domain_settings.rst
@@ -46,15 +47,15 @@
 doc/source/user_doc.rst
 doc/source/_extensions/code_blocks.py
 doc/source/_static/style.css
 doc/source/crawl/add_to_queue.rst
 doc/source/crawl/crawl_depth.rst
 doc/source/crawl/policies.rst
 doc/source/crawl/status.rst
-doc/source/install/database.rst
+doc/source/install/database.rst.template
 doc/source/install/debian.rst
 doc/source/install/debian_upgrades.rst
 doc/source/install/docker.rst
 doc/source/install/docker_upgrades.rst
 doc/source/install/pip.rst
 doc/source/install/pip_upgrades.rst
 doc/source/user/cached.rst
@@ -113,14 +114,15 @@
 se/management/commands/default_conf.py
 se/management/commands/extract_doc.py
 se/management/commands/generate_secret.py
 se/management/commands/load_se.py
 se/management/commands/update_se.py
 se/migrations/0001_initial.py
 se/migrations/0002_search_vector.py
+se/migrations/0003_sosse_1_1_0.py
 se/migrations/__init__.py
 se/static/se/admin-base.css
 se/static/se/admin-forms.css
 se/static/se/base.js
 se/static/se/icon-atom.svg
 se/static/se/icon-clear.svg
 se/static/se/icon-cog.svg
@@ -142,14 +144,15 @@
 se/templates/admin/crawl_status.html
 se/templates/admin/crawl_status_content.html
 se/templates/admin/index.html
 se/templates/se/about.html
 se/templates/se/base.html
 se/templates/se/cached.html
 se/templates/se/history.html
+se/templates/se/home_browse.html
 se/templates/se/index.html
 se/templates/se/main_menu.html
 se/templates/se/opensearch.xml
 se/templates/se/pagination.html
 se/templates/se/prefs.html
 se/templates/se/screenshot.html
 se/templates/se/search_redirect.html
@@ -173,16 +176,20 @@
 sosse.egg-info/top_level.txt
 tests/build_doc.sh
 tests/cookies.json
 tests/doc_test.sh
 tests/docker_run.sh
 tests/document-ja.json
 tests/opensearch.xml
+tests/release.md
 tests/searchhistory.json
 tests/test_app.sh
 tests/wait_for_pg.sh
+tests/robotframework/config.yaml
+tests/robotframework/home_docs.json
+tests/robotframework/home_favicon.json
 tests/robotframework/requirements.txt
 tests/robotframework/start.sh
 tests/robotframework/tests/01_crawl.robot
 tests/robotframework/tests/02_user.robot
 tests/robotframework/tests/__init__.robot
 tests/robotframework/tests/common.robot
```

### Comparing `sosse-1.0.1/tests/cookies.json` & `sosse-1.1.0/tests/cookies.json`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/tests/doc_test.sh` & `sosse-1.1.0/tests/doc_test.sh`

 * *Files 19% similar despite different names*

```diff
@@ -1,18 +1,23 @@
 #!/usr/bin/bash
-set -e
 CODE_BLOCK_FILE="$1"
 DOC_SRC="$2"
 
 code_length="$(jq --arg SRC "$DOC_SRC" '[.[] | select(.src == $SRC and (.lang == "shell" or .lang == "default"))] | length' < "$CODE_BLOCK_FILE")"
 
 function code_no() {
     jq -r --arg IDX "$1" --arg SRC "$DOC_SRC" '[.[] | select(.src == $SRC and (.lang == "shell" or .lang == "default"))][$IDX|tonumber].code' < "$CODE_BLOCK_FILE"
 }
 
+function show_error() {
+    f="$(jq -r --arg IDX "$1" --arg SRC "$DOC_SRC" '[.[] | select(.src == $SRC and (.lang == "shell" or .lang == "default"))][$IDX|tonumber].source' < "$CODE_BLOCK_FILE")"
+    l="$(jq -r --arg IDX "$1" --arg SRC "$DOC_SRC" '[.[] | select(.src == $SRC and (.lang == "shell" or .lang == "default"))][$IDX|tonumber].line' < "$CODE_BLOCK_FILE")"
+    echo "Failed on $f, line $l." >&2
+}
+
 if [ "$code_length" == "0" ]
 then
     echo "No step to perform" >&2
     exit 1
 fi
 
 block_no=0
@@ -29,12 +34,18 @@
         _code="$(echo "$code"|grep -v ^systemctl ||:)"
         if [ "$_code" != "" ]
         then
             IFS=$'\n'; for line in $_code
             do
                 echo "----- $line"
                 eval "$line"
+                exit_status=$?
+                if [ $exit_status != 0 ]
+                then
+                    show_error "$block_no"
+                    exit 1
+                fi
             done
         fi
     fi
     block_no=$(($block_no + 1))
 done
```

### Comparing `sosse-1.0.1/tests/document-ja.json` & `sosse-1.1.0/tests/document-ja.json`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/tests/robotframework/start.sh` & `sosse-1.1.0/tests/robotframework/start.sh`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/tests/robotframework/tests/01_crawl.robot` & `sosse-1.1.0/tests/robotframework/tests/01_crawl.robot`

 * *Files 1% similar despite different names*

```diff
@@ -86,15 +86,15 @@
 |  | Wait Until Element Is Visible | id=result_list
 |  | ${dom_count}= | Get Element Count | xpath=//table[@id='result_list']/tbody/tr
 |  | Should Be Equal As Numbers | ${dom_count} | 1
 |  | Click Link | 127.0.0.1
 |  | Capture Page Screenshot | domain_setting.png
 
 | Cookies
-|  | Run Keyword And Ignore Error | Run Command | ../../sosse-admin | loaddata | tests/cookies.json | shell=True
+|  | Run Keyword And Ignore Error | Run Command | ${SOSSE_ADMIN} | loaddata | ${CURDIR}/../cookies.json | shell=True
 |  | Go To | http://127.0.0.1/admin/se/cookie/
 |  | Wait Until Element Is Visible | id=result_list
 |  | ${dom_count}= | Get Element Count | xpath=//table[@id='result_list']/tbody/tr
 |  | Should Be Equal As Numbers | ${dom_count} | 3
 |  | Capture Page Screenshot | cookies_list.png
 
 | Excluded URLs
```

### Comparing `sosse-1.0.1/tests/robotframework/tests/02_user.robot` & `sosse-1.1.0/tests/robotframework/tests/02_user.robot`

 * *Files 8% similar despite different names*

```diff
@@ -36,28 +36,37 @@
 | Preferences
 |  | Click Button | id=user_menu_button
 |  | Click Link | Preferences
 |  | Wait Until Page Contains | Search terms parsing language
 |  | Capture Page Screenshot | preferences.png
 
 | Statistics
-|  | Run Command | ../../sosse-admin | loaddata | tests/document-ja.json | shell=True
-|  | Run Command | ../../sosse-admin | shell | -c | from se.models import CrawlerStats ; from django.utils.timezone import now ; CrawlerStats.create(now()) | shell=True
+|  | Run Command | ${SOSSE_ADMIN} | loaddata | ${CURDIR}/../../document-ja.json | shell=True
+|  | Run Command | ${SOSSE_ADMIN} | shell | -c | from se.models import CrawlerStats ; from django.utils.timezone import now ; CrawlerStats.create(now()) | shell=True
 |  | Go To | http://127.0.0.1/stats/
 |  | Capture Page Screenshot | statistics.png
 
 | History
-|  | Run Command | ../../sosse-admin | loaddata | tests/searchhistory.json | shell=True
+|  | Run Command | ${SOSSE_ADMIN} | loaddata | ${CURDIR}/../../searchhistory.json | shell=True
 |  | Go To | http://127.0.0.1/history/
 |  | Wait Until Page Contains | 4 elements in the history
 |  | Capture Page Screenshot | history.png
 |  | Capture Element Screenshot | xpath=//input[@class='del_button img_button' and @value=''] | history_delete.png
 |  | Capture Element Screenshot | id=del_all | history_delete_all.png
 
 | Cache
 |  | Go To | http://127.0.0.1/screenshot/http://127.0.0.1/screenshots/website/cats.html
 |  | Hilight | id=cache_info
 |  | Capture Page Screenshot | cache_info.png
 |  | Reload Page
 |  | Scroll To Bottom
 |  | Mouse Over | xpath=//a[@class='img_link'][2]
 |  | Capture Page Screenshot | cache_screenshot.png
+
+| Browsable home
+|  | [Tags] | browsable_home
+|  | Run Command | ${SOSSE_ADMIN} | loaddata | ${CURDIR}/../home_favicon.json | shell=True
+|  | Run Command | ${SOSSE_ADMIN} | loaddata | ${CURDIR}/../home_docs.json | shell=True
+|  | Run Command | sed | -e | s/^#browsable_home.*/browsable_home\=true/ | -i | /etc/sosse/sosse.conf
+|  | Run Command | killall | -s | HUP | uwsgi
+|  | Go To | http://127.0.0.1/
+|  | Capture Page Screenshot | browsable_home.png
```

### Comparing `sosse-1.0.1/tests/robotframework/tests/common.robot` & `sosse-1.1.0/tests/robotframework/tests/common.robot`

 * *Files identical despite different names*

### Comparing `sosse-1.0.1/tests/test_app.sh` & `sosse-1.1.0/tests/test_app.sh`

 * *Files identical despite different names*


# Comparing `tmp/alnoda_wrk-0.4.8.tar.gz` & `tmp/alnoda_wrk-0.4.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "alnoda_wrk-0.4.8.tar", max compression
+gzip compressed data, was "alnoda_wrk-0.4.9.tar", max compression
```

## Comparing `alnoda_wrk-0.4.8.tar` & `alnoda_wrk-0.4.9.tar`

### file list

```diff
@@ -1,76 +1,76 @@
--rw-r--r--   0        0        0    34523 2022-08-26 16:21:54.054721 alnoda_wrk-0.4.8/LICENSE
--rw-r--r--   0        0        0       50 2022-08-26 16:21:54.054721 alnoda_wrk-0.4.8/README.md
--rw-r--r--   0        0        0       21 2022-08-26 16:21:54.054721 alnoda_wrk-0.4.8/alnoda_wrk/__init__.py
--rw-r--r--   0        0        0     2159 2023-03-28 22:36:26.036464 alnoda_wrk-0.4.8/alnoda_wrk/alnoda_api.py
--rw-r--r--   0        0        0     5250 2023-03-15 17:54:18.519943 alnoda_wrk-0.4.8/alnoda_wrk/builder.py
--rw-r--r--   0        0        0     7796 2023-03-15 17:54:18.520943 alnoda_wrk-0.4.8/alnoda_wrk/cheatsheet.py
--rw-r--r--   0        0        0     7143 2022-08-26 16:21:54.055721 alnoda_wrk-0.4.8/alnoda_wrk/conf_parser.py
--rw-r--r--   0        0        0     7706 2023-03-15 17:46:54.959179 alnoda_wrk-0.4.8/alnoda_wrk/config_schema.py
--rw-r--r--   0        0        0     7853 2023-04-14 20:52:02.650230 alnoda_wrk-0.4.8/alnoda_wrk/fileops.py
--rw-r--r--   0        0        0     1946 2023-03-15 17:54:18.520943 alnoda_wrk-0.4.8/alnoda_wrk/globals.py
--rw-r--r--   0        0        0    22428 2023-05-10 00:33:34.493365 alnoda_wrk-0.4.8/alnoda_wrk/install_app.py
--rw-r--r--   0        0        0     7523 2023-03-15 17:54:18.520943 alnoda_wrk-0.4.8/alnoda_wrk/links.py
--rw-r--r--   0        0        0     4800 2023-04-21 09:50:53.395581 alnoda_wrk-0.4.8/alnoda_wrk/main.py
--rw-r--r--   0        0        0    11315 2023-03-28 22:36:26.039464 alnoda_wrk-0.4.8/alnoda_wrk/meta_about.py
--rw-r--r--   0        0        0     1668 2022-11-01 14:08:08.668939 alnoda_wrk-0.4.8/alnoda_wrk/processes.py
--rw-r--r--   0        0        0     5362 2023-03-15 17:54:18.522943 alnoda_wrk-0.4.8/alnoda_wrk/share.py
--rw-r--r--   0        0        0     2351 2023-03-15 17:54:18.522943 alnoda_wrk-0.4.8/alnoda_wrk/sign_in.py
--rw-r--r--   0        0        0     3537 2022-10-24 16:31:09.586727 alnoda_wrk-0.4.8/alnoda_wrk/templates.py
--rw-r--r--   0        0        0        0 2022-09-03 08:06:50.028562 alnoda_wrk-0.4.8/alnoda_wrk/tui/__init__.py
--rw-r--r--   0        0        0     4641 2023-03-15 18:04:22.771086 alnoda_wrk-0.4.8/alnoda_wrk/tui/admin.py
--rw-r--r--   0        0        0     5969 2023-03-15 17:54:18.523943 alnoda_wrk-0.4.8/alnoda_wrk/tui/aliases_widget.py
--rw-r--r--   0        0        0    12260 2022-11-01 14:08:08.671939 alnoda_wrk-0.4.8/alnoda_wrk/tui/appearance_widget.py
--rw-r--r--   0        0        0     7166 2022-10-26 09:15:48.183939 alnoda_wrk-0.4.8/alnoda_wrk/tui/apps_services.py
--rw-r--r--   0        0        0    13400 2022-10-26 08:48:00.804887 alnoda_wrk-0.4.8/alnoda_wrk/tui/cheatsheet_widget.py
--rw-r--r--   0        0        0     2357 2022-09-04 16:06:07.306059 alnoda_wrk-0.4.8/alnoda_wrk/tui/description_widget.py
--rw-r--r--   0        0        0     5984 2023-03-15 17:54:18.523943 alnoda_wrk-0.4.8/alnoda_wrk/tui/env_vars_widget.py
--rw-r--r--   0        0        0     3135 2022-09-09 09:42:06.101097 alnoda_wrk-0.4.8/alnoda_wrk/tui/features_widget.py
--rw-r--r--   0        0        0      235 2022-09-03 08:06:50.032562 alnoda_wrk-0.4.8/alnoda_wrk/tui/gvars.py
--rw-r--r--   0        0        0      710 2022-09-06 16:00:47.678829 alnoda_wrk-0.4.8/alnoda_wrk/tui/helper_vidgets.py
--rw-r--r--   0        0        0     8471 2022-09-03 08:06:50.034562 alnoda_wrk-0.4.8/alnoda_wrk/tui/home.py
--rw-r--r--   0        0        0    13540 2022-10-26 09:27:26.705899 alnoda_wrk-0.4.8/alnoda_wrk/tui/interface_widget.py
--rw-r--r--   0        0        0    15046 2022-10-26 08:48:43.025601 alnoda_wrk-0.4.8/alnoda_wrk/tui/links_widget.py
--rw-r--r--   0        0        0      630 2023-03-15 17:54:18.524943 alnoda_wrk-0.4.8/alnoda_wrk/tui/my_notes_widget.py
--rw-r--r--   0        0        0     7868 2022-11-01 14:08:08.673939 alnoda_wrk-0.4.8/alnoda_wrk/tui/processes_widget.py
--rw-r--r--   0        0        0     8546 2023-03-15 17:54:18.524943 alnoda_wrk-0.4.8/alnoda_wrk/tui/share_widget.py
--rw-r--r--   0        0        0     3692 2023-03-15 17:54:18.524943 alnoda_wrk-0.4.8/alnoda_wrk/tui/signin_widget.py
--rw-r--r--   0        0        0      619 2023-03-15 17:54:18.524943 alnoda_wrk-0.4.8/alnoda_wrk/tui/zsh_widget.py
--rw-r--r--   0        0        0    13918 2022-10-27 12:16:55.545298 alnoda_wrk-0.4.8/alnoda_wrk/ui_builder.py
--rw-r--r--   0        0        0     1469 2022-09-10 20:05:49.819958 alnoda_wrk-0.4.8/alnoda_wrk/ui_styles.py
--rw-r--r--   0        0        0     9485 2023-04-13 18:51:15.320292 alnoda_wrk-0.4.8/alnoda_wrk/wrk/cheatsheet.json
--rw-r--r--   0        0        0      292 2023-04-21 05:54:58.452091 alnoda_wrk-0.4.8/alnoda_wrk/wrk/lineage.json
--rw-r--r--   0        0        0     1947 2023-03-19 22:28:40.727499 alnoda_wrk-0.4.8/alnoda_wrk/wrk/links.json
--rw-r--r--   0        0        0      253 2022-09-09 09:42:06.104097 alnoda_wrk-0.4.8/alnoda_wrk/wrk/meta.json
--rw-r--r--   0        0        0       86 2022-08-26 16:21:54.058721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/requires/deps.txt
--rw-r--r--   0        0        0       13 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/requires/mkdocs.txt
--rw-r--r--   0        0        0      803 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/.gitignore
--rw-r--r--   0        0        0     1056 2022-10-27 10:25:21.242272 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/conf/ui-apps.json
--rw-r--r--   0        0        0      489 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/README.md
--rw-r--r--   0        0        0      287 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/about.md
--rw-r--r--   0        0        0    10831 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/Alnoda-logo.svg
--rw-r--r--   0        0        0    15406 2022-08-26 16:21:54.060721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/favicon.ico
--rw-r--r--   0        0        0   256110 2022-08-26 16:21:54.061721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Cronicle.jpg
--rw-r--r--   0        0        0   291683 2022-08-26 16:21:54.064721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Filebrowser.png
--rw-r--r--   0        0        0   145945 2022-08-26 16:21:54.066721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Htop.jpg
--rw-r--r--   0        0        0   110933 2022-08-26 16:21:54.072721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/MC.jpg
--rw-r--r--   0        0        0    52554 2022-08-26 16:21:54.074721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Static-server.png
--rw-r--r--   0        0        0   158518 2022-08-26 16:21:54.075721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Ungit.jpg
--rw-r--r--   0        0        0    58658 2022-08-26 16:21:54.075721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/terminal.png
--rw-r--r--   0        0        0     3322 2022-08-26 16:21:54.075721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/laptop-circle-white.svg
--rw-r--r--   0        0        0     3303 2022-08-26 16:21:54.076721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/laptop-circle.svg
--rw-r--r--   0        0        0        0 2022-10-11 08:46:44.472361 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/cheatsheet.md
--rw-r--r--   0        0        0      300 2022-08-26 16:21:54.076721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/javascript/config.js
--rw-r--r--   0        0        0        0 2022-09-03 08:06:50.051562 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/manifest.txt
--rw-r--r--   0        0        0    28614 2022-10-25 08:07:27.499000 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/pages/my_apps/port-8029.png
--rw-r--r--   0        0        0    26222 2022-08-26 16:21:54.085721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/pages/my_apps/port-8030.png
--rw-r--r--   0        0        0      491 2022-08-26 16:21:54.078721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/pages/my_apps.md
--rw-r--r--   0        0        0      774 2022-09-10 20:04:56.132714 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/stylesheets/extra.css
--rw-r--r--   0        0        0     1112 2022-08-26 16:21:54.087721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/stylesheets/quickstart.css
--rw-r--r--   0        0        0     3875 2022-09-17 17:03:25.346026 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/macros/helpers.py
--rw-r--r--   0        0        0     1528 2023-03-16 00:41:16.909935 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/mkdocs.yml
--rw-r--r--   0        0        0        0 2022-08-26 16:21:54.088721 alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/overrides/partials/footer.html
--rw-r--r--   0        0        0     4428 2023-03-17 00:44:50.092440 alnoda_wrk-0.4.8/alnoda_wrk/wrk_supervisor.py
--rw-r--r--   0        0        0     2916 2023-03-16 14:04:52.728745 alnoda_wrk-0.4.8/alnoda_wrk/zsh.py
--rw-r--r--   0        0        0      688 2023-05-11 14:12:00.357508 alnoda_wrk-0.4.8/pyproject.toml
--rw-r--r--   0        0        0     1509 2023-05-11 14:12:20.990285 alnoda_wrk-0.4.8/setup.py
--rw-r--r--   0        0        0      869 2023-05-11 14:12:20.990578 alnoda_wrk-0.4.8/PKG-INFO
+-rw-r--r--   0        0        0    34523 2022-08-26 16:21:54.054721 alnoda_wrk-0.4.9/LICENSE
+-rw-r--r--   0        0        0       92 2023-05-20 12:17:12.054213 alnoda_wrk-0.4.9/README.md
+-rw-r--r--   0        0        0       21 2022-08-26 16:21:54.054721 alnoda_wrk-0.4.9/alnoda_wrk/__init__.py
+-rw-r--r--   0        0        0     2159 2023-03-28 22:36:26.036464 alnoda_wrk-0.4.9/alnoda_wrk/alnoda_api.py
+-rw-r--r--   0        0        0     5250 2023-03-15 17:54:18.519943 alnoda_wrk-0.4.9/alnoda_wrk/builder.py
+-rw-r--r--   0        0        0     7796 2023-03-15 17:54:18.520943 alnoda_wrk-0.4.9/alnoda_wrk/cheatsheet.py
+-rw-r--r--   0        0        0     7143 2022-08-26 16:21:54.055721 alnoda_wrk-0.4.9/alnoda_wrk/conf_parser.py
+-rw-r--r--   0        0        0     7706 2023-03-15 17:46:54.959179 alnoda_wrk-0.4.9/alnoda_wrk/config_schema.py
+-rw-r--r--   0        0        0     7853 2023-04-14 20:52:02.650230 alnoda_wrk-0.4.9/alnoda_wrk/fileops.py
+-rw-r--r--   0        0        0     1946 2023-03-15 17:54:18.520943 alnoda_wrk-0.4.9/alnoda_wrk/globals.py
+-rw-r--r--   0        0        0    22428 2023-05-10 00:33:34.493365 alnoda_wrk-0.4.9/alnoda_wrk/install_app.py
+-rw-r--r--   0        0        0     7523 2023-03-15 17:54:18.520943 alnoda_wrk-0.4.9/alnoda_wrk/links.py
+-rw-r--r--   0        0        0     4800 2023-04-21 09:50:53.395581 alnoda_wrk-0.4.9/alnoda_wrk/main.py
+-rw-r--r--   0        0        0    11315 2023-03-28 22:36:26.039464 alnoda_wrk-0.4.9/alnoda_wrk/meta_about.py
+-rw-r--r--   0        0        0     1668 2022-11-01 14:08:08.668939 alnoda_wrk-0.4.9/alnoda_wrk/processes.py
+-rw-r--r--   0        0        0     5362 2023-03-15 17:54:18.522943 alnoda_wrk-0.4.9/alnoda_wrk/share.py
+-rw-r--r--   0        0        0     2351 2023-03-15 17:54:18.522943 alnoda_wrk-0.4.9/alnoda_wrk/sign_in.py
+-rw-r--r--   0        0        0     3537 2022-10-24 16:31:09.586727 alnoda_wrk-0.4.9/alnoda_wrk/templates.py
+-rw-r--r--   0        0        0        0 2022-09-03 08:06:50.028562 alnoda_wrk-0.4.9/alnoda_wrk/tui/__init__.py
+-rw-r--r--   0        0        0     4635 2023-05-22 20:09:30.540579 alnoda_wrk-0.4.9/alnoda_wrk/tui/admin.py
+-rw-r--r--   0        0        0     5969 2023-03-15 17:54:18.523943 alnoda_wrk-0.4.9/alnoda_wrk/tui/aliases_widget.py
+-rw-r--r--   0        0        0    12260 2022-11-01 14:08:08.671939 alnoda_wrk-0.4.9/alnoda_wrk/tui/appearance_widget.py
+-rw-r--r--   0        0        0     7166 2022-10-26 09:15:48.183939 alnoda_wrk-0.4.9/alnoda_wrk/tui/apps_services.py
+-rw-r--r--   0        0        0    13400 2022-10-26 08:48:00.804887 alnoda_wrk-0.4.9/alnoda_wrk/tui/cheatsheet_widget.py
+-rw-r--r--   0        0        0     2357 2022-09-04 16:06:07.306059 alnoda_wrk-0.4.9/alnoda_wrk/tui/description_widget.py
+-rw-r--r--   0        0        0     5984 2023-03-15 17:54:18.523943 alnoda_wrk-0.4.9/alnoda_wrk/tui/env_vars_widget.py
+-rw-r--r--   0        0        0     3135 2022-09-09 09:42:06.101097 alnoda_wrk-0.4.9/alnoda_wrk/tui/features_widget.py
+-rw-r--r--   0        0        0      235 2022-09-03 08:06:50.032562 alnoda_wrk-0.4.9/alnoda_wrk/tui/gvars.py
+-rw-r--r--   0        0        0      710 2022-09-06 16:00:47.678829 alnoda_wrk-0.4.9/alnoda_wrk/tui/helper_vidgets.py
+-rw-r--r--   0        0        0     8471 2022-09-03 08:06:50.034562 alnoda_wrk-0.4.9/alnoda_wrk/tui/home.py
+-rw-r--r--   0        0        0    13540 2022-10-26 09:27:26.705899 alnoda_wrk-0.4.9/alnoda_wrk/tui/interface_widget.py
+-rw-r--r--   0        0        0    15046 2022-10-26 08:48:43.025601 alnoda_wrk-0.4.9/alnoda_wrk/tui/links_widget.py
+-rw-r--r--   0        0        0      630 2023-03-15 17:54:18.524943 alnoda_wrk-0.4.9/alnoda_wrk/tui/my_notes_widget.py
+-rw-r--r--   0        0        0     7868 2022-11-01 14:08:08.673939 alnoda_wrk-0.4.9/alnoda_wrk/tui/processes_widget.py
+-rw-r--r--   0        0        0     8546 2023-03-15 17:54:18.524943 alnoda_wrk-0.4.9/alnoda_wrk/tui/share_widget.py
+-rw-r--r--   0        0        0     3692 2023-03-15 17:54:18.524943 alnoda_wrk-0.4.9/alnoda_wrk/tui/signin_widget.py
+-rw-r--r--   0        0        0      619 2023-03-15 17:54:18.524943 alnoda_wrk-0.4.9/alnoda_wrk/tui/zsh_widget.py
+-rw-r--r--   0        0        0    13918 2022-10-27 12:16:55.545298 alnoda_wrk-0.4.9/alnoda_wrk/ui_builder.py
+-rw-r--r--   0        0        0     1469 2022-09-10 20:05:49.819958 alnoda_wrk-0.4.9/alnoda_wrk/ui_styles.py
+-rw-r--r--   0        0        0     9485 2023-04-13 18:51:15.320292 alnoda_wrk-0.4.9/alnoda_wrk/wrk/cheatsheet.json
+-rw-r--r--   0        0        0      292 2023-04-21 05:54:58.452091 alnoda_wrk-0.4.9/alnoda_wrk/wrk/lineage.json
+-rw-r--r--   0        0        0     1947 2023-03-19 22:28:40.727499 alnoda_wrk-0.4.9/alnoda_wrk/wrk/links.json
+-rw-r--r--   0        0        0      253 2022-09-09 09:42:06.104097 alnoda_wrk-0.4.9/alnoda_wrk/wrk/meta.json
+-rw-r--r--   0        0        0       86 2022-08-26 16:21:54.058721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/requires/deps.txt
+-rw-r--r--   0        0        0       13 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/requires/mkdocs.txt
+-rw-r--r--   0        0        0      803 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/.gitignore
+-rw-r--r--   0        0        0     1056 2022-10-27 10:25:21.242272 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/conf/ui-apps.json
+-rw-r--r--   0        0        0      489 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/README.md
+-rw-r--r--   0        0        0      287 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/about.md
+-rw-r--r--   0        0        0    10831 2022-08-26 16:21:54.059721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/Alnoda-logo.svg
+-rw-r--r--   0        0        0    15406 2022-08-26 16:21:54.060721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/favicon.ico
+-rw-r--r--   0        0        0   256110 2022-08-26 16:21:54.061721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Cronicle.jpg
+-rw-r--r--   0        0        0   291683 2022-08-26 16:21:54.064721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Filebrowser.png
+-rw-r--r--   0        0        0   145945 2022-08-26 16:21:54.066721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Htop.jpg
+-rw-r--r--   0        0        0   110933 2022-08-26 16:21:54.072721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/MC.jpg
+-rw-r--r--   0        0        0    52554 2022-08-26 16:21:54.074721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Static-server.png
+-rw-r--r--   0        0        0   158518 2022-08-26 16:21:54.075721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Ungit.jpg
+-rw-r--r--   0        0        0    58658 2022-08-26 16:21:54.075721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/terminal.png
+-rw-r--r--   0        0        0     3322 2022-08-26 16:21:54.075721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/laptop-circle-white.svg
+-rw-r--r--   0        0        0     3303 2022-08-26 16:21:54.076721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/laptop-circle.svg
+-rw-r--r--   0        0        0        0 2022-10-11 08:46:44.472361 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/cheatsheet.md
+-rw-r--r--   0        0        0      300 2022-08-26 16:21:54.076721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/javascript/config.js
+-rw-r--r--   0        0        0        0 2022-09-03 08:06:50.051562 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/manifest.txt
+-rw-r--r--   0        0        0    28614 2022-10-25 08:07:27.499000 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/pages/my_apps/port-8029.png
+-rw-r--r--   0        0        0    26222 2022-08-26 16:21:54.085721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/pages/my_apps/port-8030.png
+-rw-r--r--   0        0        0      491 2022-08-26 16:21:54.078721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/pages/my_apps.md
+-rw-r--r--   0        0        0      774 2022-09-10 20:04:56.132714 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/stylesheets/extra.css
+-rw-r--r--   0        0        0     1112 2022-08-26 16:21:54.087721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/stylesheets/quickstart.css
+-rw-r--r--   0        0        0     3875 2022-09-17 17:03:25.346026 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/macros/helpers.py
+-rw-r--r--   0        0        0     1528 2023-03-16 00:41:16.909935 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/mkdocs.yml
+-rw-r--r--   0        0        0        0 2022-08-26 16:21:54.088721 alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/overrides/partials/footer.html
+-rw-r--r--   0        0        0     4428 2023-03-17 00:44:50.092440 alnoda_wrk-0.4.9/alnoda_wrk/wrk_supervisor.py
+-rw-r--r--   0        0        0     2916 2023-03-16 14:04:52.728745 alnoda_wrk-0.4.9/alnoda_wrk/zsh.py
+-rw-r--r--   0        0        0      688 2023-05-22 20:09:57.665080 alnoda_wrk-0.4.9/pyproject.toml
+-rw-r--r--   0        0        0     1552 2023-05-22 20:10:19.373601 alnoda_wrk-0.4.9/setup.py
+-rw-r--r--   0        0        0      911 2023-05-22 20:10:19.373976 alnoda_wrk-0.4.9/PKG-INFO
```

### Comparing `alnoda_wrk-0.4.8/LICENSE` & `alnoda_wrk-0.4.9/LICENSE`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/alnoda_api.py` & `alnoda_wrk-0.4.9/alnoda_wrk/alnoda_api.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/builder.py` & `alnoda_wrk-0.4.9/alnoda_wrk/builder.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/cheatsheet.py` & `alnoda_wrk-0.4.9/alnoda_wrk/cheatsheet.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/conf_parser.py` & `alnoda_wrk-0.4.9/alnoda_wrk/conf_parser.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/config_schema.py` & `alnoda_wrk-0.4.9/alnoda_wrk/config_schema.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/fileops.py` & `alnoda_wrk-0.4.9/alnoda_wrk/fileops.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/globals.py` & `alnoda_wrk-0.4.9/alnoda_wrk/globals.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/install_app.py` & `alnoda_wrk-0.4.9/alnoda_wrk/install_app.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/links.py` & `alnoda_wrk-0.4.9/alnoda_wrk/links.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/main.py` & `alnoda_wrk-0.4.9/alnoda_wrk/main.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/meta_about.py` & `alnoda_wrk-0.4.9/alnoda_wrk/meta_about.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/processes.py` & `alnoda_wrk-0.4.9/alnoda_wrk/processes.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/share.py` & `alnoda_wrk-0.4.9/alnoda_wrk/share.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/sign_in.py` & `alnoda_wrk-0.4.9/alnoda_wrk/sign_in.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/templates.py` & `alnoda_wrk-0.4.9/alnoda_wrk/templates.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/admin.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/admin.py`

 * *Files 2% similar despite different names*

```diff
@@ -16,15 +16,15 @@
     from .apps_services import get_apps_services_widget
     from .share_widget import get_share_widget
     from .zsh_widget import get_zsh_widget
     from .signin_widget import get_signin_widget
     from .my_notes_widget import get_my_notes_widget
 
     # temporary exclude : "PM2 processes"
-    options = ["Home", "Sign In", "Collaborate", "Features", "Description", "Appearance", "Intrerface", "Apps & Services", "Zsh", "My notes"]
+    options = ["Home", "Sign In", "Share", "Features", "Description", "Appearance", "Intrerface", "Apps & Services", "Zsh", "My notes"]
 
 
     def AlnodaAdminTUI(root= None):
         # ttk.TTkLogViewer(parent=root)
         frame = ttk.TTkFrame(parent=root, border=False)
 
         # Create internal window
@@ -84,15 +84,15 @@
             widget = None
             if   label == "Home":               widget = hello_widget
             elif label == "Sign In":            widget = SignInWidget
             elif label == "Features":           widget = FeaturesWidget
             elif label == "Description":        widget = DescriptionWidget
             elif label == "Intrerface":         widget = InterfaceWidget
             elif label == "Apps & Services":    widget = AppsServicesWidget
-            elif label == "Collaborate":        widget = ShareWidget
+            elif label == "Share":              widget = ShareWidget
             elif label == "Zsh":                widget = ZshWidget
             elif label == "My notes":           widget = MyNotesWidget
             elif label == "Appearance":    
                 widget =  get_appearance_widget()
                 RightFrame.layout().addWidget(widget)
                 widget.show()
             if widget:
```

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/aliases_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/aliases_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/appearance_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/appearance_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/apps_services.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/apps_services.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/cheatsheet_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/cheatsheet_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/description_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/description_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/env_vars_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/env_vars_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/features_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/features_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/helper_vidgets.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/helper_vidgets.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/home.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/home.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/interface_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/interface_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/links_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/links_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/my_notes_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/my_notes_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/processes_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/processes_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/share_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/share_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/signin_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/signin_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/tui/zsh_widget.py` & `alnoda_wrk-0.4.9/alnoda_wrk/tui/zsh_widget.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/ui_builder.py` & `alnoda_wrk-0.4.9/alnoda_wrk/ui_builder.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/ui_styles.py` & `alnoda_wrk-0.4.9/alnoda_wrk/ui_styles.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/cheatsheet.json` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/cheatsheet.json`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/links.json` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/links.json`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/.gitignore` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/.gitignore`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/conf/ui-apps.json` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/conf/ui-apps.json`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/Alnoda-logo.svg` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/Alnoda-logo.svg`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/favicon.ico` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/favicon.ico`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Cronicle.jpg` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Cronicle.jpg`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Filebrowser.png` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Filebrowser.png`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Htop.jpg` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Htop.jpg`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/MC.jpg` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/MC.jpg`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Static-server.png` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Static-server.png`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/Ungit.jpg` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/Ungit.jpg`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/home/terminal.png` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/home/terminal.png`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/laptop-circle-white.svg` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/laptop-circle-white.svg`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/assets/laptop-circle.svg` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/assets/laptop-circle.svg`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/pages/my_apps/port-8029.png` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/pages/my_apps/port-8029.png`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/pages/my_apps/port-8030.png` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/pages/my_apps/port-8030.png`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/stylesheets/extra.css` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/stylesheets/extra.css`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/docs/stylesheets/quickstart.css` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/docs/stylesheets/quickstart.css`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/macros/helpers.py` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/macros/helpers.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk/ui/mkdocs.yml` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk/ui/mkdocs.yml`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/wrk_supervisor.py` & `alnoda_wrk-0.4.9/alnoda_wrk/wrk_supervisor.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/alnoda_wrk/zsh.py` & `alnoda_wrk-0.4.9/alnoda_wrk/zsh.py`

 * *Files identical despite different names*

### Comparing `alnoda_wrk-0.4.8/pyproject.toml` & `alnoda_wrk-0.4.9/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "alnoda_wrk"
-version = "0.4.8"
+version = "0.4.9"
 description = "A tool to build Alnoda workspaces"
 authors = ["bluxmit <bluxmit@gmail.com>"]
 license = "GNU Affero General Public License v3.0"
 readme = "README.md"
 
 [tool.poetry.scripts]
 "alnoda-wrk" = "alnoda_wrk.main:app"
```

### Comparing `alnoda_wrk-0.4.8/setup.py` & `alnoda_wrk-0.4.9/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -31,17 +31,17 @@
 
 entry_points = \
 {'console_scripts': ['alnoda-wrk = alnoda_wrk.main:app',
                      'wrk = alnoda_wrk.main:app']}
 
 setup_kwargs = {
     'name': 'alnoda-wrk',
-    'version': '0.4.8',
+    'version': '0.4.9',
     'description': 'A tool to build Alnoda workspaces',
-    'long_description': '# alnoda-wrk\n\nA tool to build alnoda workspaces\n\n\n',
+    'long_description': '# alnoda-wrk\n\nA tool to build alnoda workspaces\n\nRoadmap:\n\n- https://github.com/schollz/croc',
     'author': 'bluxmit',
     'author_email': 'bluxmit@gmail.com',
     'maintainer': None,
     'maintainer_email': None,
     'url': None,
     'packages': packages,
     'package_data': package_data,
```

### Comparing `alnoda_wrk-0.4.8/PKG-INFO` & `alnoda_wrk-0.4.9/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: alnoda-wrk
-Version: 0.4.8
+Version: 0.4.9
 Summary: A tool to build Alnoda workspaces
 License: AGPL-3.0
 Author: bluxmit
 Author-email: bluxmit@gmail.com
 Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: GNU Affero General Public License v3
 Classifier: Programming Language :: Python :: 3
@@ -21,9 +21,10 @@
 Requires-Dist: typer[all] (>=0.6,<0.7)
 Description-Content-Type: text/markdown
 
 # alnoda-wrk
 
 A tool to build alnoda workspaces
 
+Roadmap:
 
-
+- https://github.com/schollz/croc
```


# Comparing `tmp/ubiquity-student-1.0.1.tar.gz` & `tmp/ubiquity-student-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ubiquity-student-1.0.1.tar", last modified: Wed May 17 06:34:00 2023, max compression
+gzip compressed data, was "ubiquity-student-1.1.0.tar", last modified: Wed Jun 28 07:59:33 2023, max compression
```

## Comparing `ubiquity-student-1.0.1.tar` & `ubiquity-student-1.1.0.tar`

### file list

```diff
@@ -1,219 +1,220 @@
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.541967 ubiquity-student-1.0.1/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     2516 2023-05-17 06:34:00.541967 ubiquity-student-1.0.1/PKG-INFO
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     1554 2022-06-20 11:36:26.000000 ubiquity-student-1.0.1/README.md
--rw-rw-r--   0 houchard  (1000) houchard  (1000)       38 2023-05-17 06:34:00.541967 ubiquity-student-1.0.1/setup.cfg
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     2993 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/setup.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.517967 ubiquity-student-1.0.1/src/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)        5 2023-05-17 06:31:15.000000 ubiquity-student-1.0.1/src/VERSION
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.517967 ubiquity-student-1.0.1/src/ubiquity/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      854 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/__init__.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     8936 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/argument_parser.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.517967 ubiquity-student-1.0.1/src/ubiquity/controllers/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      757 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/controllers/__init__.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     7941 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/controllers/config_file.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     9157 2023-05-10 11:20:34.000000 ubiquity-student-1.0.1/src/ubiquity/controllers/main_controller.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     6247 2023-05-10 11:20:34.000000 ubiquity-student-1.0.1/src/ubiquity/controllers/worker.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.517967 ubiquity-student-1.0.1/src/ubiquity/images/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     2139 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/images/ubiquity_icon.png
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.513967 ubiquity-student-1.0.1/src/ubiquity/locale/
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.513967 ubiquity-student-1.0.1/src/ubiquity/locale/fr/
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.517967 ubiquity-student-1.0.1/src/ubiquity/locale/fr/LC_MESSAGES/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     4589 2023-05-10 11:20:34.000000 ubiquity-student-1.0.1/src/ubiquity/locale/fr/LC_MESSAGES/ubiquity-student.mo
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     5223 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/model.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     3348 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/ubiquity_student.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     2080 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/version.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.517967 ubiquity-student-1.0.1/src/ubiquity/views/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      757 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/__init__.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.517967 ubiquity-student-1.0.1/src/ubiquity/views/cui/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      757 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/cui/__init__.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     8398 2023-01-12 13:40:26.000000 ubiquity-student-1.0.1/src/ubiquity/views/cui/main_view.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.517967 ubiquity-student-1.0.1/src/ubiquity/views/gui/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      757 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/__init__.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.517967 ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      960 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/__init__.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     2001 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/about.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     2000 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/base.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     1901 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/choice.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     3606 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/form.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     6555 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/open.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     3320 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/preference.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     4798 2023-05-10 11:20:34.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/main_view.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     5278 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/menu_bar.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.521967 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     2368 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/__init__.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     1068 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/base.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     1164 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sun_valley_dark.py
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     1168 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sun_valley_light.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.521967 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     1063 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/LICENSE
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)     1349 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/__init__.py
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)     2961 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/sun-valley.tcl
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.521967 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.529967 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      270 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/arrow-down.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      261 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/arrow-right.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      274 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/arrow-up.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      262 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-accent-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      373 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-accent-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      363 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-accent-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      377 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-accent-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      274 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-close-hover.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      274 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-close-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      301 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      276 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      288 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-pressed.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      301 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      245 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-titlebar-hover.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      238 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-titlebar-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      386 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/card.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      383 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      474 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      460 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      475 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      294 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-tri-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      362 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-tri-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      358 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-tri-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      363 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-tri-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      312 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-unsel-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      353 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-unsel-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      302 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-unsel-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      353 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-unsel-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      129 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/empty.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      273 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      335 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-focus.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      269 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      324 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-invalid.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      297 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      337 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/notebook-border.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      186 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/notebook.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      193 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/progress-pbar-hor.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      214 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/progress-pbar-vert.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      157 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/progress-trough-hor.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      160 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/progress-trough-vert.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      553 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      853 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      786 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      830 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      552 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      602 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      616 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      621 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      724 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-disabled.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      808 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-hover.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      735 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-pressed.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      771 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      216 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-trough-hor.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      215 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-trough-vert.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      226 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-down.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      254 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-hor-thumb.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      338 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-hor-trough.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      233 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-left.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      227 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-right.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      236 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-up.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      264 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-vert-thumb.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      343 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-vert-trough.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      128 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/separator.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      276 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/sizegrip.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      733 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      945 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      963 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      895 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      623 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      927 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      936 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      859 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      265 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/tab-hover.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      164 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/tab-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      319 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/tab-selected.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      295 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/treeheading-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      317 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/treeheading-pressed.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      321 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/treeheading-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)    19668 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark.tcl
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.541967 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      278 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/arrow-down.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      273 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/arrow-right.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      285 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/arrow-up.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      271 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-accent-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      374 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-accent-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      367 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-accent-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      384 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-accent-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      326 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-close-hover.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      316 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-close-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      307 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      306 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      289 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      303 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      238 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-titlebar-hover.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      225 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-titlebar-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      394 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/card.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      381 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      476 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      467 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      473 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      299 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-tri-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      365 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-tri-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      362 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-tri-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      367 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-tri-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      324 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-unsel-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      334 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-unsel-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      302 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-unsel-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      333 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-unsel-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      129 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/empty.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      289 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      331 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-focus.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      302 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      324 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-invalid.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      308 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      298 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/notebook-border.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      185 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/notebook.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      192 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/progress-pbar-hor.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      216 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/progress-pbar-vert.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      158 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/progress-trough-hor.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      161 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/progress-trough-vert.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      523 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      837 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      764 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      773 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      521 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      573 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      636 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      576 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      658 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-disabled.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      749 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-hover.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      675 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-pressed.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      701 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      208 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-trough-hor.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      214 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-trough-vert.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      229 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-down.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      234 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-hor-thumb.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      321 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-hor-trough.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      232 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-left.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      223 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-right.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      237 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-up.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      262 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-vert-thumb.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      324 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-vert-trough.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      128 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/separator.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      272 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/sizegrip.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      726 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      867 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      880 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      814 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      590 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-disabled.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      906 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      916 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-pressed.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      857 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      295 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/tab-hover.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      164 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/tab-rest.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      318 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/tab-selected.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      338 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/treeheading-hover.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)      318 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/treeheading-pressed.png
--rw-rw-r--   0 houchard  (1000) houchard  (1000)      330 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/treeheading-rest.png
--rwxrwxr-x   0 houchard  (1000) houchard  (1000)    19846 2022-09-19 07:02:28.000000 ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light.tcl
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     6442 2023-05-10 11:20:34.000000 ubiquity-student-1.0.1/src/ubiquity/views/utils.py
-drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-05-17 06:34:00.541967 ubiquity-student-1.0.1/ubiquity_student.egg-info/
--rw-rw-r--   0 houchard  (1000) houchard  (1000)     2516 2023-05-17 06:34:00.000000 ubiquity-student-1.0.1/ubiquity_student.egg-info/PKG-INFO
--rw-rw-r--   0 houchard  (1000) houchard  (1000)    12271 2023-05-17 06:34:00.000000 ubiquity-student-1.0.1/ubiquity_student.egg-info/SOURCES.txt
--rw-rw-r--   0 houchard  (1000) houchard  (1000)        1 2023-05-17 06:34:00.000000 ubiquity-student-1.0.1/ubiquity_student.egg-info/dependency_links.txt
--rw-rw-r--   0 houchard  (1000) houchard  (1000)       72 2023-05-17 06:34:00.000000 ubiquity-student-1.0.1/ubiquity_student.egg-info/entry_points.txt
--rw-rw-r--   0 houchard  (1000) houchard  (1000)       17 2023-05-17 06:34:00.000000 ubiquity-student-1.0.1/ubiquity_student.egg-info/requires.txt
--rw-rw-r--   0 houchard  (1000) houchard  (1000)        4 2023-05-17 06:34:00.000000 ubiquity-student-1.0.1/ubiquity_student.egg-info/top_level.txt
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.066023 ubiquity-student-1.1.0/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     2516 2023-06-28 07:59:33.066023 ubiquity-student-1.1.0/PKG-INFO
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     1554 2022-06-20 11:36:26.000000 ubiquity-student-1.1.0/README.md
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)       38 2023-06-28 07:59:33.066023 ubiquity-student-1.1.0/setup.cfg
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     2993 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/setup.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.042023 ubiquity-student-1.1.0/src/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)        5 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/VERSION
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      854 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/__init__.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     8936 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/argument_parser.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/controllers/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      757 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/controllers/__init__.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     8795 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/controllers/config_file.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)    10841 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/controllers/main_controller.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     6247 2023-05-24 06:47:03.000000 ubiquity-student-1.1.0/src/ubiquity/controllers/worker.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/images/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     2139 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/images/ubiquity_icon.png
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.042023 ubiquity-student-1.1.0/src/ubiquity/locale/
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.042023 ubiquity-student-1.1.0/src/ubiquity/locale/fr/
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/locale/fr/LC_MESSAGES/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     6756 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/locale/fr/LC_MESSAGES/ubiquity-student.mo
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     5594 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/model.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     3348 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/ubiquity_student.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     2080 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/version.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/views/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      757 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/__init__.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/views/cui/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      757 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/cui/__init__.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     8398 2023-01-12 13:40:26.000000 ubiquity-student-1.1.0/src/ubiquity/views/cui/main_view.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/views/gui/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      757 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/__init__.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      995 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/__init__.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     2001 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/about.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     2000 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/base.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     1901 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/choice.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     2395 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/confirm.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     3606 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/form.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     6555 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/open.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     3320 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/preference.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     4862 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/main_view.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     6535 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/menu_bar.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     2368 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/__init__.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     1221 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/base.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     1253 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sun_valley_dark.py
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     1259 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sun_valley_light.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     1063 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/LICENSE
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)     1383 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/__init__.py
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)     2961 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/sun-valley.tcl
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.046023 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.054023 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      270 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/arrow-down.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      261 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/arrow-right.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      274 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/arrow-up.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      262 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-accent-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      373 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-accent-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      363 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-accent-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      377 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-accent-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      274 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-close-hover.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      274 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-close-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      301 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      276 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      288 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-pressed.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      301 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      245 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-titlebar-hover.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      238 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/button-titlebar-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      386 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/card.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      383 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      474 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      460 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      475 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      294 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-tri-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      362 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-tri-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      358 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-tri-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      363 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-tri-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      312 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-unsel-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      353 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-unsel-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      302 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-unsel-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      353 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/check-unsel-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      129 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/empty.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      273 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      335 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-focus.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      269 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      324 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-invalid.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      297 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/entry-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      337 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/notebook-border.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      186 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/notebook.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      193 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/progress-pbar-hor.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      214 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/progress-pbar-vert.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      157 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/progress-trough-hor.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      160 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/progress-trough-vert.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      553 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      853 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      786 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      830 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      552 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      602 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      616 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      621 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      724 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-disabled.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      808 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-hover.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      735 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-pressed.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      771 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      216 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-trough-hor.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      215 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-trough-vert.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      226 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-down.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      254 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-hor-thumb.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      338 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-hor-trough.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      233 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-left.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      227 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-right.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      236 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-up.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      264 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-vert-thumb.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      343 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scroll-vert-trough.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      128 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/separator.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      276 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/sizegrip.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      733 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      945 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      963 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      895 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      623 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      927 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      936 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      859 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      265 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/tab-hover.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      164 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/tab-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      319 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/tab-selected.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      295 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/treeheading-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      317 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/treeheading-pressed.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      321 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/treeheading-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)    19668 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark.tcl
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.062023 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      278 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/arrow-down.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      273 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/arrow-right.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      285 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/arrow-up.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      271 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-accent-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      374 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-accent-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      367 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-accent-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      384 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-accent-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      326 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-close-hover.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      316 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-close-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      307 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      306 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      289 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      303 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      238 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-titlebar-hover.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      225 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/button-titlebar-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      394 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/card.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      381 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      476 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      467 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      473 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      299 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-tri-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      365 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-tri-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      362 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-tri-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      367 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-tri-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      324 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-unsel-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      334 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-unsel-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      302 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-unsel-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      333 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/check-unsel-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      129 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/empty.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      289 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      331 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-focus.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      302 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      324 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-invalid.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      308 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/entry-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      298 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/notebook-border.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      185 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/notebook.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      192 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/progress-pbar-hor.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      216 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/progress-pbar-vert.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      158 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/progress-trough-hor.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      161 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/progress-trough-vert.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      523 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      837 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      764 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      773 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      521 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      573 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      636 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      576 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      658 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-disabled.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      749 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-hover.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      675 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-pressed.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      701 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      208 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-trough-hor.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      214 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-trough-vert.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      229 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-down.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      234 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-hor-thumb.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      321 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-hor-trough.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      232 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-left.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      223 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-right.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      237 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-up.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      262 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-vert-thumb.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      324 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scroll-vert-trough.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      128 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/separator.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      272 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/sizegrip.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      726 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      867 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      880 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      814 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      590 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-disabled.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      906 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      916 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-pressed.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      857 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      295 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/tab-hover.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      164 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/tab-rest.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      318 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/tab-selected.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      338 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/treeheading-hover.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)      318 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/treeheading-pressed.png
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)      330 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/treeheading-rest.png
+-rwxrwxr-x   0 houchard  (1000) houchard  (1000)    19846 2022-09-19 07:02:28.000000 ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light.tcl
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     6745 2023-06-28 07:49:41.000000 ubiquity-student-1.1.0/src/ubiquity/views/utils.py
+drwxrwxr-x   0 houchard  (1000) houchard  (1000)        0 2023-06-28 07:59:33.066023 ubiquity-student-1.1.0/ubiquity_student.egg-info/
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)     2516 2023-06-28 07:59:33.000000 ubiquity-student-1.1.0/ubiquity_student.egg-info/PKG-INFO
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)    12313 2023-06-28 07:59:33.000000 ubiquity-student-1.1.0/ubiquity_student.egg-info/SOURCES.txt
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)        1 2023-06-28 07:59:33.000000 ubiquity-student-1.1.0/ubiquity_student.egg-info/dependency_links.txt
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)       72 2023-06-28 07:59:33.000000 ubiquity-student-1.1.0/ubiquity_student.egg-info/entry_points.txt
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)       17 2023-06-28 07:59:33.000000 ubiquity-student-1.1.0/ubiquity_student.egg-info/requires.txt
+-rw-rw-r--   0 houchard  (1000) houchard  (1000)        4 2023-06-28 07:59:33.000000 ubiquity-student-1.1.0/ubiquity_student.egg-info/top_level.txt
```

### Comparing `ubiquity-student-1.0.1/PKG-INFO` & `ubiquity-student-1.1.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ubiquity-student
-Version: 1.0.1
+Version: 1.1.0
 Summary: Ubiquity permet le suivi de TP de développement informatique
 Home-page: https://gitlab.insa-rouen.fr/cip/ubiquity
 Download-URL: https://gitlab.insa-rouen.fr/cip/ubiquity/-/tags
 Project-URL: Documentation, https://gitlab.insa-rouen.fr/cip/ubiquity/-/wikis/home
 Project-URL: Bug Tracker, https://gitlab.insa-rouen.fr/cip/ubiquity/-/issues
 Classifier: Topic :: Education
 Classifier: Development Status :: 3 - Alpha
```

### Comparing `ubiquity-student-1.0.1/README.md` & `ubiquity-student-1.1.0/README.md`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/setup.py` & `ubiquity-student-1.1.0/setup.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/__init__.py` & `ubiquity-student-1.1.0/src/ubiquity/__init__.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/argument_parser.py` & `ubiquity-student-1.1.0/src/ubiquity/argument_parser.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/controllers/__init__.py` & `ubiquity-student-1.1.0/src/ubiquity/controllers/__init__.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/controllers/config_file.py` & `ubiquity-student-1.1.0/src/ubiquity/controllers/config_file.py`

 * *Files 4% similar despite different names*

```diff
@@ -45,14 +45,15 @@
 class Config:
     """Class managing the configurations"""
     _CONFIG_FILE_NAME = '.ubiquity'
     HISTORY = 'history'
     THEME = 'theme'
     DEFAULT = 'default'
     NAME = 'name'
+    UPDATE = 'update'
     DATE = 'date'
     SERVER = 'server'
     STUDENT_KEY = 'student_key'
     GROUP_KEY = 'group_key'
     DIRECTORY = 'directory'
 
     def __init__(self) -> None:
@@ -105,23 +106,46 @@
         """Method adding a config; Or updating if exist
 
         :param model: The model
         """
         self._set_default_config(model.server.get(), model.student_key.get())
         key = _get_key(model)
         history = self._get_history()
+        if key in history and Config.UPDATE in history[key]:
+            update = history[key][Config.UPDATE]
+        else:
+            update = 0
         history[key] = {}
         history[key][Config.NAME] = model.name.get()
         history[key][Config.DATE] = datetime.datetime.now().strftime("%d/%m/%Y")
+        history[key][Config.UPDATE] = update
         history[key][Config.SERVER] = model.server.get()
         history[key][Config.STUDENT_KEY] = model.student_key.get()
         history[key][Config.GROUP_KEY] = model.group_key.get()
         history[key][Config.DIRECTORY] = model.directory.get()
         self._write_config_file(self.configs)
 
+    def add_update_config(self, model: Model) -> None:
+        """Method adding a config; Or updating if exist
+
+        :param model: The model
+        """
+        self._get_history()[_get_key(model)][Config.UPDATE] = model.date_update.get()
+        model.updated.set(False)
+        self._write_config_file(self.configs)
+
+    def init_update_config(self, model: Model) -> None:
+        """Method adding a config; Or updating if exist
+
+        :param model: The model
+        """
+        model.updated.set(False)
+        if model.date_update.get() != self._get_history()[_get_key(model)][Config.UPDATE]:
+            model.updated.set(True)
+
     def remove_config(self, model: Model) -> None:
         """Method removing a config by a group key
 
         :param model: The model
         """
         self._get_history().pop(_get_key(model))
         self._write_config_file(self.configs)
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/controllers/main_controller.py` & `ubiquity-student-1.1.0/src/ubiquity/controllers/main_controller.py`

 * *Files 5% similar despite different names*

```diff
@@ -11,14 +11,17 @@
 #      but WITHOUT ANY WARRANTY; without even the implied warranty of
 #      MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 #      GNU General Public License for more details.
 #
 #      You should have received a copy of the GNU General Public License
 #      along with this program.  If not, see <https://www.gnu.org/licenses/>.
 import os.path
+import re
+import shutil
+from datetime import datetime
 from enum import unique, Enum, auto
 from io import BytesIO
 from json import loads
 from json.decoder import JSONDecodeError
 from typing import Optional
 from zipfile import ZipFile
 
@@ -112,14 +115,15 @@
                 return ErrorMessage.PRACTICAL_WORK_SUSPENDED
             if response.status_code != StatusCode.OK:
                 if self.config.check_is_config(self._model):
                     return ErrorMessage.CONFIG_DELETED
                 return ErrorMessage.INVALID_KEYS
             content = loads(response.content)
             self._model.name.set(content['name'])
+            self._model.date_update.set(content['date_update'])
             self.is_new_project = content['is_new']
         except requests.exceptions.RequestException:
             return ErrorMessage.CONNECTION_FAILED
         return None
 
     def _check_directory(self) -> Optional[ErrorMessage]:
         """Method verifying if the directory exits
@@ -160,24 +164,53 @@
             for filename in zip_file.namelist():
                 if not os.path.exists(os.path.join(self._model.directory.get(), filename)):
                     zip_file.extract(filename, self._model.directory.get())
                     print_message(LabelEnum.EXTRACT_RESTORED_FILE, end=" ")
                     print_value(filename)
         print_message(LabelEnum.EXTRACT_ZIP_COMPLETED, 1)
 
+    def extract_updated_zip(self) -> None:
+        """Extract a restored zip file to the working directory"""
+        response = requests.get(self._model.url_api_update_student_environment())
+        print_message(LabelEnum.UPDATING)
+        with ZipFile(BytesIO(response.content)) as zip_file:
+            print_message(LabelEnum.STUDENT_ENVIRONMENT_RECOVERED)
+            for filename in zip_file.namelist():
+                zip_file.extract(filename, self._model.directory.get())
+                print_message(LabelEnum.EXTRACT_UPDATED_FILE, end=" ")
+                print_value(filename)
+        print_message(LabelEnum.EXTRACT_ZIP_COMPLETED, 1)
+
+    def copy_to_back(self):
+        """Method copying files to the ".ubiquity_backs" directory"""
+        file_names = os.listdir(self._model.directory.get())
+        back_base = os.path.join(self._model.directory.get(), ".ubiquity_backs")
+        back_dir = os.path.join(back_base, f'back_{datetime.now().strftime("%Y_%m_%d_%H_%M_%S")}')
+        os.makedirs(back_dir, mode=0o755, exist_ok=True)
+        for file_name in file_names:
+            old_file_path = os.path.join(self._model.directory.get(), file_name)
+            new_file_path = os.path.join(back_dir, file_name)
+            if not re.match(fr'^{re.escape(back_base)}$', old_file_path):
+                shutil.move(old_file_path, new_file_path)
+
     def _check_is_new(self) -> bool:
         """Method checking if is a new project
 
         :return: True if is a new project, False if not
         """
         return not self.config.check_is_config(self._model)
 
     def _add_config(self) -> None:
         """Method adding a config"""
         self.config.add_config(self._model)
+        self.config.init_update_config(self._model)
+
+    def add_update_config(self):
+        """Method adding an update for the current practical work"""
+        self.config.add_update_config(self._model)
 
     def update_with_config(self, config: dict) -> None:
         """Method updating the model with the config values
 
         :param config: The config
         """
         self._model.server.set(config[Config.SERVER])
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/controllers/worker.py` & `ubiquity-student-1.1.0/src/ubiquity/controllers/worker.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/images/ubiquity_icon.png` & `ubiquity-student-1.1.0/src/ubiquity/images/ubiquity_icon.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/model.py` & `ubiquity-student-1.1.0/src/ubiquity/model.py`

 * *Files 6% similar despite different names*

```diff
@@ -11,22 +11,24 @@
 #      but WITHOUT ANY WARRANTY; without even the implied warranty of
 #      MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 #      GNU General Public License for more details.
 #
 #      You should have received a copy of the GNU General Public License
 #      along with this program.  If not, see <https://www.gnu.org/licenses/>.
 
-from tkinter import StringVar
+from tkinter import StringVar, BooleanVar, DoubleVar
 from typing import List, Optional
 
 
 class Model:
     """Class managing the model"""
     def __init__(self, values: List[Optional[str]]):
         self.name = StringVar()
+        self.date_update = DoubleVar()
+        self.updated = BooleanVar()
         self.error = StringVar()
         self.server = StringVar()
         self.student_key = StringVar()
         self.group_key = StringVar()
         self.directory = StringVar()
         self._client_version_min = None
         self._set_values(values)
@@ -117,14 +119,21 @@
     def url_api_restore_student_environment(self) -> str:
         """Method returning the url for get student environment restored
 
         :return: The string url
         """
         return f'{self._url_api_server()}/restore/{self.student_key.get()}/{self.group_key.get()}'
 
+    def url_api_update_student_environment(self) -> str:
+        """Method returning the url for get student environment updated
+
+        :return: The string url
+        """
+        return f'{self._url_api_server()}/update/{self.student_key.get()}/{self.group_key.get()}'
+
     def url_api_get_progress(self) -> str:
         """Method returning the url for get the progress
 
         :return: The string url
         """
         return f'{self._url_api_server()}/progress/{self.student_key.get()}/{self.group_key.get()}'
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/ubiquity_student.py` & `ubiquity-student-1.1.0/src/ubiquity/ubiquity_student.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/version.py` & `ubiquity-student-1.1.0/src/ubiquity/version.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/__init__.py` & `ubiquity-student-1.1.0/src/ubiquity/views/__init__.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/cui/__init__.py` & `ubiquity-student-1.1.0/src/ubiquity/views/cui/__init__.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/cui/main_view.py` & `ubiquity-student-1.1.0/src/ubiquity/views/cui/main_view.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/__init__.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/__init__.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/__init__.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/__init__.py`

 * *Files 5% similar despite different names*

```diff
@@ -16,7 +16,8 @@
 #      along with this program.  If not, see <https://www.gnu.org/licenses/>.
 
 from .about import AboutDialog
 from .form import FormDialog
 from .open import OpenDialog
 from .choice import ChoiceDialog
 from .preference import PreferenceDialog
+from .confirm import ConfirmDialog
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/about.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/about.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/base.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/base.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/choice.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/choice.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/form.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/form.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/open.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/open.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/dialogs/preference.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/dialogs/preference.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/main_view.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/main_view.py`

 * *Files 2% similar despite different names*

```diff
@@ -91,14 +91,15 @@
         self._ui_setup()
         self.model.server.set("")
         self.model.student_key.set("")
         self.model.group_key.set("")
         self.model.directory.set("")
 
     def stop_suspend(self, _signum, _frame):
+        """Method to stop if the practical work is suspended"""
         self.model.error.set(ErrorMessage.PRACTICAL_WORK_SUSPENDED.value)
         if self._has_form:
             self.menu_bar.close_file()
             messagebox.showerror(message=self.model.error.get())
         else:
             self.stop()
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/menu_bar.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/menu_bar.py`

 * *Files 14% similar despite different names*

```diff
@@ -15,27 +15,28 @@
 #      You should have received a copy of the GNU General Public License
 #      along with this program.  If not, see <https://www.gnu.org/licenses/>.
 import webbrowser
 from enum import Enum
 from tkinter import Menu, messagebox
 from tkinter.constants import DISABLED, NORMAL
 
-from .dialogs import AboutDialog, FormDialog, OpenDialog, PreferenceDialog
+from .dialogs import AboutDialog, FormDialog, OpenDialog, PreferenceDialog, ConfirmDialog
 from ..utils import gettext, LabelEnum
 
 _ = gettext.gettext
 
 
 class MenuLabel(Enum):
     """Class Enum for menu label"""
     FILE = _('File')
     NEW_FILE_ACTION = _('New...')
     OPEN_FILE_ACTION = _('Recently open...')
     CLOSE_FILE_ACTION = _('Close')
-    RESTORE_FILE_ACTION = _('Restore')
+    RESTORE_FILE_ACTION = _('Restore...')
+    UPDATE_FILE_ACTION = _('Update...')
     PREFERENCE_FILE_ACTION = _('Preference...')
     EXIT_FILE_ACTION = _('Exit')
     HELP = _('Help')
     HELP_HELP_ACTION = _('Help...')
     ABOUT_HELP_ACTION = _('About...')
 
 
@@ -53,14 +54,15 @@
         """Method setting up the file menu
 
         :return: The file menu
         """
         menu_file = Menu(self, tearoff=False)
         menu_file.add_command(label=f'  {MenuLabel.NEW_FILE_ACTION.value}', command=self.new_file, underline=2)
         menu_file.add_command(label=f'  {MenuLabel.OPEN_FILE_ACTION.value}', command=self.open_file)
+        menu_file.add_command(label=f'  {MenuLabel.UPDATE_FILE_ACTION.value}', command=self.update_file)
         menu_file.add_command(label=f'  {MenuLabel.RESTORE_FILE_ACTION.value}', command=self.restore_file, underline=2)
         menu_file.add_command(label=f'  {MenuLabel.CLOSE_FILE_ACTION.value}', command=self.close_file)
         menu_file.add_command(label=f'  {MenuLabel.PREFERENCE_FILE_ACTION.value}', command=self.preference_file)
         menu_file.add_command(label=f'  {MenuLabel.EXIT_FILE_ACTION.value}', command=self.exit_file)
         self.add_cascade(menu=menu_file, label=MenuLabel.FILE.value, underline=0)
         return menu_file
 
@@ -80,14 +82,17 @@
 
         :param is_opened_file: If a project is opened
         """
         self.menu_file.entryconfigure(f'  {MenuLabel.NEW_FILE_ACTION.value}',
                                       state=DISABLED if is_opened_file else NORMAL)
         self.menu_file.entryconfigure(f'  {MenuLabel.OPEN_FILE_ACTION.value}',
                                       state=DISABLED if is_opened_file else NORMAL)
+        self.menu_file.entryconfigure(f'  {MenuLabel.UPDATE_FILE_ACTION.value}',
+                                      state=NORMAL if is_opened_file and self.parent.controller._model.updated.get()
+                                      else DISABLED)
         self.menu_file.entryconfigure(f'  {MenuLabel.RESTORE_FILE_ACTION.value}',
                                       state=NORMAL if is_opened_file else DISABLED)
         self.menu_file.entryconfigure(f'  {MenuLabel.CLOSE_FILE_ACTION.value}',
                                       state=NORMAL if is_opened_file else DISABLED)
 
     def new_file(self):
         """Method of the action "new" in file menu"""
@@ -95,16 +100,33 @@
 
     def open_file(self):
         """Method of the action "open" in file menu"""
         self.update_menu(OpenDialog(self.parent.view, self.parent.controller.config).is_valid)
 
     def restore_file(self):
         """Method of the action "restore" in file menu"""
-        self.parent.controller.extract_restored_zip()
-        messagebox.showinfo(message=LabelEnum.RESTORE_FINISHED.value)
+        confirm_dialog = ConfirmDialog(self.parent.view, title=LabelEnum.RESTORE.value)
+        if confirm_dialog.choice:
+            self.parent.controller.extract_restored_zip()
+            messagebox.showinfo(message=LabelEnum.RESTORE_FINISHED.value)
+
+    def update_file(self):
+        """Method of the action "update" in file menu"""
+        confirm_dialog = ConfirmDialog(self.parent.view, title=LabelEnum.UPDATE.value)
+        if confirm_dialog.choice:
+            self.parent.controller.stop()
+            self.parent.controller.copy_to_back()
+            self.parent.controller.extract_updated_zip()
+            self.parent.controller.add_update_config()
+            self.update_menu(True)
+            messagebox.showinfo(message=LabelEnum.UPDATE_FINISHED.value)
+            if self.parent.controller.has_gui:
+                self.parent.controller.run()
+            else:
+                self.parent.controller.run(self.parent.controller.worker.fn_display)
 
     def close_file(self):
         """Method of the action "close" in file menu"""
         self.update_menu(False)
         self.parent.view.stop()
 
     def preference_file(self):
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/__init__.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/__init__.py`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/base.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/base.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+"""Module for the abstract theme"""
 #      ubiquity
 #      Copyright (C) 2022  INSA Rouen Normandie - CIP
 #
 #      This program is free software: you can redistribute it and/or modify
 #      it under the terms of the GNU General Public License as published by
 #      the Free Software Foundation, either version 3 of the License, or
 #      (at your option) any later version.
@@ -13,21 +14,23 @@
 #
 #      You should have received a copy of the GNU General Public License
 #      along with this program.  If not, see <https://www.gnu.org/licenses/>.
 import abc
 
 
 class BaseTheme(abc.ABC):
+    """Class for the abstract theme"""
     @classmethod
     @abc.abstractmethod
     def theme_id(cls):
-        pass
+        """Returning the theme id"""
 
     @classmethod
     @abc.abstractmethod
     def theme_name(cls):
-        pass
+        """Returning the theme name"""
 
     @classmethod
     @abc.abstractmethod
     def use_theme(cls, config):
+        """The use theme"""
         config.set_theme(cls.theme_id())
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sun_valley_dark.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sun_valley_dark.py`

 * *Files 25% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+"""Module for the sun valley dark theme"""
 #      ubiquity
 #      Copyright (C) 2022  INSA Rouen Normandie - CIP
 #
 #      This program is free software: you can redistribute it and/or modify
 #      it under the terms of the GNU General Public License as published by
 #      the Free Software Foundation, either version 3 of the License, or
 #      (at your option) any later version.
@@ -18,14 +19,15 @@
 from .base import BaseTheme
 from ...utils import gettext
 
 _ = gettext.gettext
 
 
 class SunValleyDarkTheme(BaseTheme):
+    """Class for the sun valley dark theme"""
     @classmethod
     def theme_id(cls):
         return "sun-valley-dark"
 
     @classmethod
     def theme_name(cls):
         return _("Sun Valley dark")
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sun_valley_light.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sun_valley_light.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+"""Module for the sun valley light theme"""
 #      ubiquity
 #      Copyright (C) 2022  INSA Rouen Normandie - CIP
 #
 #      This program is free software: you can redistribute it and/or modify
 #      it under the terms of the GNU General Public License as published by
 #      the Free Software Foundation, either version 3 of the License, or
 #      (at your option) any later version.
@@ -18,14 +19,15 @@
 from .base import BaseTheme
 from ...utils import gettext
 
 _ = gettext.gettext
 
 
 class SunValleyLightTheme(BaseTheme):
+    """Class for the sun valley light theme"""
     @classmethod
     def theme_id(cls):
         return "sun-valley-light"
 
     @classmethod
     def theme_name(cls):
         return _("Sun Valley light")
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/LICENSE` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/LICENSE`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/__init__.py` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,7 +1,8 @@
+"""Module for the sv_ttk theme"""
 from pathlib import Path
 
 inited = False
 root = None
 
 
 def init(func):
```

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/sun-valley.tcl` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/sun-valley.tcl`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/radio-unsel-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/scale-thumb-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-off-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark/switch-on-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/dark.tcl` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/dark.tcl`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/radio-unsel-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/scale-thumb-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-off-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-disabled.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-disabled.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-hover.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-hover.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-pressed.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-pressed.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-rest.png` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light/switch-on-rest.png`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/gui/themes/sv_ttk/theme/light.tcl` & `ubiquity-student-1.1.0/src/ubiquity/views/gui/themes/sv_ttk/theme/light.tcl`

 * *Files identical despite different names*

### Comparing `ubiquity-student-1.0.1/src/ubiquity/views/utils.py` & `ubiquity-student-1.1.0/src/ubiquity/views/utils.py`

 * *Files 2% similar despite different names*

```diff
@@ -47,14 +47,15 @@
     PREFERENCE = _('Preference')
     OPEN = _("Open")
     RECENTLY_OPEN = _("Recently open")
     SEARCH = _("search")
     ACCESS_GROUP = _("Access to the group")
     WARNING = _("Warning")
     RESTORE = _('Restore')
+    UPDATE = _('Update')
     RESET = _('Reset')
     CANCEL = _('Cancel')
     DELETE = _('Delete')
     ABOUT = _("About")
     VERSION = _("Version:")
     LICENSE = _("License:")
     PROGRESS = _('Progress:')
@@ -62,22 +63,29 @@
     AVERAGE_PROGRESS = _('Average progress:')
     MISSING_FILES = _('Missing files:')
     PROGRESS_INFORMATION = _('Progress information:')
     FILES = _('Files:')
     NEW_VERSION_AVAILABLE = _('New version of Ubiquity-student available:')
     WARNING_FILE_EXISTS = _('Warning: File already exists')
     EXTRACT_RESTORED_FILE = _('A file has been restored:')
+    EXTRACT_UPDATED_FILE = _('A file has been updated:')
     RESTORING = _('Restoration of the practical work...')
+    UPDATING = _('Update of the practical work...')
     NO_CONNECTION = _('No internet connection')
     NO_PRACTICAL_WORK = _('No practical work in progress')
     OPEN_WEB_BROWSER = _('See my progress in the web browser')
     RESTORE_FINISHED = _("The files have been restored")
+    UPDATE_FINISHED = _("The files have been updated")
     DELETE_YES_NO = _("Are you sure you want to delete '%(num)s- %(name)s' ?")
+    ARE_YOU_SURE = _("Are you sure ?")
     APPLY = _("Apply")
     THEME = _("Theme")
+    YES = _("Yes")
+    NO = _("No")
+    DOCUMENTATION = _("Documentation")
 
     @classmethod
     def label_form_list(cls) -> List[str]:
         """Method returning the list of labels of the input fields for the information
 
         :return: The list of labels
         """
```

### Comparing `ubiquity-student-1.0.1/ubiquity_student.egg-info/PKG-INFO` & `ubiquity-student-1.1.0/ubiquity_student.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ubiquity-student
-Version: 1.0.1
+Version: 1.1.0
 Summary: Ubiquity permet le suivi de TP de développement informatique
 Home-page: https://gitlab.insa-rouen.fr/cip/ubiquity
 Download-URL: https://gitlab.insa-rouen.fr/cip/ubiquity/-/tags
 Project-URL: Documentation, https://gitlab.insa-rouen.fr/cip/ubiquity/-/wikis/home
 Project-URL: Bug Tracker, https://gitlab.insa-rouen.fr/cip/ubiquity/-/issues
 Classifier: Topic :: Education
 Classifier: Development Status :: 3 - Alpha
```

### Comparing `ubiquity-student-1.0.1/ubiquity_student.egg-info/SOURCES.txt` & `ubiquity-student-1.1.0/ubiquity_student.egg-info/SOURCES.txt`

 * *Files 0% similar despite different names*

```diff
@@ -19,14 +19,15 @@
 src/ubiquity/views/gui/__init__.py
 src/ubiquity/views/gui/main_view.py
 src/ubiquity/views/gui/menu_bar.py
 src/ubiquity/views/gui/dialogs/__init__.py
 src/ubiquity/views/gui/dialogs/about.py
 src/ubiquity/views/gui/dialogs/base.py
 src/ubiquity/views/gui/dialogs/choice.py
+src/ubiquity/views/gui/dialogs/confirm.py
 src/ubiquity/views/gui/dialogs/form.py
 src/ubiquity/views/gui/dialogs/open.py
 src/ubiquity/views/gui/dialogs/preference.py
 src/ubiquity/views/gui/themes/__init__.py
 src/ubiquity/views/gui/themes/base.py
 src/ubiquity/views/gui/themes/sun_valley_dark.py
 src/ubiquity/views/gui/themes/sun_valley_light.py
```


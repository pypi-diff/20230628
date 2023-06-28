# Comparing `tmp/QT-PyQt-PySide-Custom-Widgets-0.6.6.tar.gz` & `tmp/QT-PyQt-PySide-Custom-Widgets-0.6.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\QT-PyQt-PySide-Custom-Widgets-0.6.6.tar", last modified: Sat Jun 24 14:28:52 2023, max compression
+gzip compressed data, was "dist\QT-PyQt-PySide-Custom-Widgets-0.6.7.tar", last modified: Wed Jun 28 11:35:42 2023, max compression
```

## Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6.tar` & `QT-PyQt-PySide-Custom-Widgets-0.6.7.tar`

### file list

```diff
@@ -1,393 +1,393 @@
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:52.611738 QT-PyQt-PySide-Custom-Widgets-0.6.6/
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:47.780965 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/
--rw-rw-rw-   0        0        0    66370 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/AnalogGaugeWidget.py
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:47.830021 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/
--rw-rw-rw-   0        0        0        0 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:47.847546 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/
--rw-rw-rw-   0        0        0      185 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/__init__.cpython-310.pyc
--rw-rw-rw-   0        0        0      178 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/__init__.cpython-38.pyc
--rw-rw-rw-   0        0        0     3840 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/test.cpython-310.pyc
--rw-rw-rw-   0        0        0     3948 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/test.cpython-38.pyc
--rw-rw-rw-   0        0        0     5285 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-310.pyc
--rw-rw-rw-   0        0        0     5276 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-38.pyc
--rw-rw-rw-   0        0        0     5297 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-39.pyc
--rw-rw-rw-   0        0        0     8502 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/interface.ui
--rw-rw-rw-   0        0        0     9452 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/test.py
--rw-rw-rw-   0        0        0     9629 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/ui_interface.py
--rw-rw-rw-   0        0        0    14071 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProjectMaker.py
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:47.933631 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/
--rw-rw-rw-   0        0        0    39288 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/QSS_Resources.qrc
--rw-rw-rw-   0        0        0     6351 2023-06-22 15:51:45.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/SassCompiler.py
--rw-rw-rw-   0        0        0    15602 2023-06-24 12:21:15.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/SvgToPngIcons.py
--rw-rw-rw-   0        0        0       39 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:48.001951 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/
--rw-rw-rw-   0        0        0   630113 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/QSS_Resources.cpython-39.pyc
--rw-rw-rw-   0        0        0     3122 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-310.pyc
--rw-rw-rw-   0        0        0     8339 2023-06-22 09:04:23.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-311.pyc
--rw-rw-rw-   0        0        0     3459 2023-06-24 11:32:42.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-38.pyc
--rw-rw-rw-   0        0        0     6895 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-310.pyc
--rw-rw-rw-   0        0        0    22615 2023-06-22 09:04:25.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-311.pyc
--rw-rw-rw-   0        0        0     7271 2023-06-24 12:21:39.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-38.pyc
--rw-rw-rw-   0        0        0     3158 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-39.pyc
--rw-rw-rw-   0        0        0      192 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/__init__.cpython-310.pyc
--rw-rw-rw-   0        0        0      221 2023-06-22 09:04:23.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/__init__.cpython-311.pyc
--rw-rw-rw-   0        0        0      177 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/__init__.cpython-37.pyc
--rw-rw-rw-   0        0        0      185 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/__init__.cpython-38.pyc
--rw-rw-rw-   0        0        0      188 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/__init__.cpython-39.pyc
--rw-rw-rw-   0        0        0     6166 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-310.pyc
--rw-rw-rw-   0        0        0    12628 2023-06-22 09:04:23.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-311.pyc
--rw-rw-rw-   0        0        0     6168 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-37.pyc
--rw-rw-rw-   0        0        0     6491 2023-06-24 14:25:53.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-38.pyc
--rw-rw-rw-   0        0        0     6064 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-39.pyc
--rw-rw-rw-   0        0        0   630112 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/resources_rc.cpython-39.pyc
--rw-rw-rw-   0        0        0     2764 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/sassCompiler.cpython-39.pyc
--rw-rw-rw-   0        0        0    60079 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/_styles.scss
--rw-rw-rw-   0        0        0    10333 2023-06-24 14:27:11.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/colorsystem.py
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:47.630917 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:52.434022 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/
--rw-rw-rw-   0        0        0      276 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/activity.svg
--rw-rw-rw-   0        0        0      356 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/airplay.svg
--rw-rw-rw-   0        0        0      350 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/alert-circle.svg
--rw-rw-rw-   0        0        0      410 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/alert-octagon.svg
--rw-rw-rw-   0        0        0      418 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/alert-triangle.svg
--rw-rw-rw-   0        0        0      392 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/align-center.svg
--rw-rw-rw-   0        0        0      393 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/align-justify.svg
--rw-rw-rw-   0        0        0      390 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/align-left.svg
--rw-rw-rw-   0        0        0      391 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/align-right.svg
--rw-rw-rw-   0        0        0      339 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/anchor.svg
--rw-rw-rw-   0        0        0      562 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/aperture.svg
--rw-rw-rw-   0        0        0      355 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/archive.svg
--rw-rw-rw-   0        0        0      354 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-down-circle.svg
--rw-rw-rw-   0        0        0      309 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-down-left.svg
--rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-down-right.svg
--rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-down.svg
--rw-rw-rw-   0        0        0      353 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-left-circle.svg
--rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-left.svg
--rw-rw-rw-   0        0        0      355 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-right-circle.svg
--rw-rw-rw-   0        0        0      308 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-right.svg
--rw-rw-rw-   0        0        0      351 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-up-circle.svg
--rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-up-left.svg
--rw-rw-rw-   0        0        0      308 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-up-right.svg
--rw-rw-rw-   0        0        0      304 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow-up.svg
--rw-rw-rw-   0        0        0     3022 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow_down.svg
--rw-rw-rw-   0        0        0     3023 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow_left.svg
--rw-rw-rw-   0        0        0     3026 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow_right.svg
--rw-rw-rw-   0        0        0     3021 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow_up.svg
--rw-rw-rw-   0        0        0      316 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/at-sign.svg
--rw-rw-rw-   0        0        0      319 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/award.svg
--rw-rw-rw-   0        0        0      349 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/bar-chart-2.svg
--rw-rw-rw-   0        0        0      347 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/bar-chart.svg
--rw-rw-rw-   0        0        0     7594 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/base_icon.svg
--rw-rw-rw-   0        0        0    33666 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/base_palette.svg
--rw-rw-rw-   0        0        0      421 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/battery-charging.svg
--rw-rw-rw-   0        0        0      320 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/battery.svg
--rw-rw-rw-   0        0        0      454 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/bell-off.svg
--rw-rw-rw-   0        0        0      315 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/bell.svg
--rw-rw-rw-   0        0        0      292 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/bluetooth.svg
--rw-rw-rw-   0        0        0      321 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/bold.svg
--rw-rw-rw-   0        0        0      333 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/book-open.svg
--rw-rw-rw-   0        0        0      339 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/book.svg
--rw-rw-rw-   0        0        0      281 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/bookmark.svg
--rw-rw-rw-   0        0        0      456 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/box.svg
--rw-rw-rw-   0        0        0     2755 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_closed.svg
--rw-rw-rw-   0        0        0     2902 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_end.svg
--rw-rw-rw-   0        0        0     3508 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_line.svg
--rw-rw-rw-   0        0        0     2678 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_more.svg
--rw-rw-rw-   0        0        0     2711 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_open.svg
--rw-rw-rw-   0        0        0      337 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/briefcase.svg
--rw-rw-rw-   0        0        0      404 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/calendar.svg
--rw-rw-rw-   0        0        0      379 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/camera-off.svg
--rw-rw-rw-   0        0        0      350 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/camera.svg
--rw-rw-rw-   0        0        0      381 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cast.svg
--rw-rw-rw-   0        0        0      322 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/check-circle.svg
--rw-rw-rw-   0        0        0      339 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/check-square.svg
--rw-rw-rw-   0        0        0      256 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/check.svg
--rw-rw-rw-   0        0        0     2799 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/checkbox_checked.svg
--rw-rw-rw-   0        0        0     2781 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/checkbox_indeterminate.svg
--rw-rw-rw-   0        0        0     2598 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/checkbox_unchecked.svg
--rw-rw-rw-   0        0        0      263 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/chevron-down.svg
--rw-rw-rw-   0        0        0      264 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/chevron-left.svg
--rw-rw-rw-   0        0        0      264 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/chevron-right.svg
--rw-rw-rw-   0        0        0      262 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/chevron-up.svg
--rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/chevrons-down.svg
--rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/chevrons-left.svg
--rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/chevrons-right.svg
--rw-rw-rw-   0        0        0      310 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/chevrons-up.svg
--rw-rw-rw-   0        0        0      442 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/chrome.svg
--rw-rw-rw-   0        0        0      252 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/circle.svg
--rw-rw-rw-   0        0        0      365 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/clipboard.svg
--rw-rw-rw-   0        0        0      298 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/clock.svg
--rw-rw-rw-   0        0        0      551 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cloud-drizzle.svg
--rw-rw-rw-   0        0        0      339 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cloud-lightning.svg
--rw-rw-rw-   0        0        0      365 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cloud-off.svg
--rw-rw-rw-   0        0        0      415 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cloud-rain.svg
--rw-rw-rw-   0        0        0      566 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cloud-snow.svg
--rw-rw-rw-   0        0        0      274 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cloud.svg
--rw-rw-rw-   0        0        0      301 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/code.svg
--rw-rw-rw-   0        0        0      480 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/codepen.svg
--rw-rw-rw-   0        0        0      632 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/codesandbox.svg
--rw-rw-rw-   0        0        0      441 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/coffee.svg
--rw-rw-rw-   0        0        0      320 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/columns.svg
--rw-rw-rw-   0        0        0      415 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/command.svg
--rw-rw-rw-   0        0        0      336 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/compass.svg
--rw-rw-rw-   0        0        0      345 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/copy.svg
--rw-rw-rw-   0        0        0      308 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/corner-down-left.svg
--rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/corner-down-right.svg
--rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/corner-left-down.svg
--rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/corner-left-up.svg
--rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/corner-right-down.svg
--rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/corner-right-up.svg
--rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/corner-up-left.svg
--rw-rw-rw-   0        0        0      310 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/corner-up-right.svg
--rw-rw-rw-   0        0        0      661 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cpu.svg
--rw-rw-rw-   0        0        0      323 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/credit-card.svg
--rw-rw-rw-   0        0        0      304 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/crop.svg
--rw-rw-rw-   0        0        0      431 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/crosshair.svg
--rw-rw-rw-   0        0        0      366 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/database.svg
--rw-rw-rw-   0        0        0      368 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/delete.svg
--rw-rw-rw-   0        0        0      289 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/disc.svg
--rw-rw-rw-   0        0        0      391 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/divide-circle.svg
--rw-rw-rw-   0        0        0      413 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/divide-square.svg
--rw-rw-rw-   0        0        0      333 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/divide.svg
--rw-rw-rw-   0        0        0      328 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/dollar-sign.svg
--rw-rw-rw-   0        0        0      381 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/download-cloud.svg
--rw-rw-rw-   0        0        0      364 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/download.svg
--rw-rw-rw-   0        0        0      418 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/dribbble.svg
--rw-rw-rw-   0        0        0      268 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/droplet.svg
--rw-rw-rw-   0        0        0      285 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/edit-2.svg
--rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/edit-3.svg
--rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/edit.svg
--rw-rw-rw-   0        0        0      382 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/external-link.svg
--rw-rw-rw-   0        0        0      454 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/eye-off.svg
--rw-rw-rw-   0        0        0      310 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/eye.svg
--rw-rw-rw-   0        0        0      297 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/facebook.svg
--rw-rw-rw-   0        0        0      317 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/fast-forward.svg
--rw-rw-rw-   0        0        0      367 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/feather.svg
--rw-rw-rw-   0        0        0      547 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/figma.svg
--rw-rw-rw-   0        0        0      381 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/file-minus.svg
--rw-rw-rw-   0        0        0      425 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/file-plus.svg
--rw-rw-rw-   0        0        0      467 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/file-text.svg
--rw-rw-rw-   0        0        0      331 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/file.svg
--rw-rw-rw-   0        0        0      580 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/film.svg
--rw-rw-rw-   0        0        0      284 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/filter.svg
--rw-rw-rw-   0        0        0      328 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/flag.svg
--rw-rw-rw-   0        0        0      355 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/folder-minus.svg
--rw-rw-rw-   0        0        0      399 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/folder-plus.svg
--rw-rw-rw-   0        0        0      305 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/folder.svg
--rw-rw-rw-   0        0        0      272 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/framer.svg
--rw-rw-rw-   0        0        0      384 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/frown.svg
--rw-rw-rw-   0        0        0      475 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/gift.svg
--rw-rw-rw-   0        0        0      371 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/git-branch.svg
--rw-rw-rw-   0        0        0      352 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/git-commit.svg
--rw-rw-rw-   0        0        0      330 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/git-merge.svg
--rw-rw-rw-   0        0        0      381 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/git-pull-request.svg
--rw-rw-rw-   0        0        0      521 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/github.svg
--rw-rw-rw-   0        0        0      484 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/gitlab.svg
--rw-rw-rw-   0        0        0      403 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/globe.svg
--rw-rw-rw-   0        0        0      398 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/grid.svg
--rw-rw-rw-   0        0        0      478 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/hard-drive.svg
--rw-rw-rw-   0        0        0      383 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/hash.svg
--rw-rw-rw-   0        0        0      389 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/headphones.svg
--rw-rw-rw-   0        0        0      365 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/heart.svg
--rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/help-circle.svg
--rw-rw-rw-   0        0        0      352 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/hexagon.svg
--rw-rw-rw-   0        0        0      326 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/home.svg
--rw-rw-rw-   0        0        0      363 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/image.svg
--rw-rw-rw-   0        0        0      399 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/inbox.svg
--rw-rw-rw-   0        0        0      341 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/info.svg
--rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/instagram.svg
--rw-rw-rw-   0        0        0      342 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/italic.svg
--rw-rw-rw-   0        0        0      346 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/key.svg
--rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/layers.svg
--rw-rw-rw-   0        0        0      358 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/layout.svg
--rw-rw-rw-   0        0        0      569 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/life-buoy.svg
--rw-rw-rw-   0        0        0     2445 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/line_horizontal.svg
--rw-rw-rw-   0        0        0     2454 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/line_vertical.svg
--rw-rw-rw-   0        0        0      349 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/link-2.svg
--rw-rw-rw-   0        0        0      365 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/link.svg
--rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/linkedin.svg
--rw-rw-rw-   0        0        0      476 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/list.svg
--rw-rw-rw-   0        0        0      608 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/loader.svg
--rw-rw-rw-   0        0        0      315 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/lock.svg
--rw-rw-rw-   0        0        0      362 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/log-in.svg
--rw-rw-rw-   0        0        0      361 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/log-out.svg
--rw-rw-rw-   0        0        0      348 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/mail.svg
--rw-rw-rw-   0        0        0      316 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/map-pin.svg
--rw-rw-rw-   0        0        0      367 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/map.svg
--rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/maximize-2.svg
--rw-rw-rw-   0        0        0      325 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/maximize.svg
--rw-rw-rw-   0        0        0      383 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/meh.svg
--rw-rw-rw-   0        0        0      340 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/menu.svg
--rw-rw-rw-   0        0        0      422 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/message-circle.svg
--rw-rw-rw-   0        0        0      299 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/message-square.svg
--rw-rw-rw-   0        0        0      488 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/mic-off.svg
--rw-rw-rw-   0        0        0      412 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/mic.svg
--rw-rw-rw-   0        0        0      398 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/minimize-2.svg
--rw-rw-rw-   0        0        0      325 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/minimize.svg
--rw-rw-rw-   0        0        0      302 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/minus-circle.svg
--rw-rw-rw-   0        0        0      324 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/minus-square.svg
--rw-rw-rw-   0        0        0      255 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/minus.svg
--rw-rw-rw-   0        0        0      364 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/monitor.svg
--rw-rw-rw-   0        0        0      275 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/moon.svg
--rw-rw-rw-   0        0        0      337 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/more-horizontal.svg
--rw-rw-rw-   0        0        0      335 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/more-vertical.svg
--rw-rw-rw-   0        0        0      305 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/mouse-pointer.svg
--rw-rw-rw-   0        0        0      480 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/move.svg
--rw-rw-rw-   0        0        0      321 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/music.svg
--rw-rw-rw-   0        0        0      273 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/navigation-2.svg
--rw-rw-rw-   0        0        0      271 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/navigation.svg
--rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/octagon.svg
--rw-rw-rw-   0        0        0      511 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/package.svg
--rw-rw-rw-   0        0        0      346 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/paperclip.svg
--rw-rw-rw-   0        0        0      346 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/pause-circle.svg
--rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/pause.svg
--rw-rw-rw-   0        0        0      385 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/pen-tool.svg
--rw-rw-rw-   0        0        0      344 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/percent.svg
--rw-rw-rw-   0        0        0      570 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-call.svg
--rw-rw-rw-   0        0        0      612 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-forwarded.svg
--rw-rw-rw-   0        0        0      611 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-incoming.svg
--rw-rw-rw-   0        0        0      607 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-missed.svg
--rw-rw-rw-   0        0        0      585 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-off.svg
--rw-rw-rw-   0        0        0      611 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-outgoing.svg
--rw-rw-rw-   0        0        0      514 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone.svg
--rw-rw-rw-   0        0        0      309 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/pie-chart.svg
--rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/play-circle.svg
--rw-rw-rw-   0        0        0      257 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/play.svg
--rw-rw-rw-   0        0        0      345 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/plus-circle.svg
--rw-rw-rw-   0        0        0      367 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/plus-square.svg
--rw-rw-rw-   0        0        0      298 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/plus.svg
--rw-rw-rw-   0        0        0      352 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/pocket.svg
--rw-rw-rw-   0        0        0      302 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/power.svg
--rw-rw-rw-   0        0        0      401 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/printer.svg
--rw-rw-rw-   0        0        0      383 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/radio.svg
--rw-rw-rw-   0        0        0     2714 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/radio_checked.svg
--rw-rw-rw-   0        0        0     2419 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/radio_unchecked.svg
--rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/refresh-ccw.svg
--rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/refresh-cw.svg
--rw-rw-rw-   0        0        0      386 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/repeat.svg
--rw-rw-rw-   0        0        0      313 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/rewind.svg
--rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/rotate-ccw.svg
--rw-rw-rw-   0        0        0      315 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/rotate-cw.svg
--rw-rw-rw-   0        0        0      324 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/rss.svg
--rw-rw-rw-   0        0        0      386 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/save.svg
--rw-rw-rw-   0        0        0      438 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/scissors.svg
--rw-rw-rw-   0        0        0      302 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/search.svg
--rw-rw-rw-   0        0        0      308 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/send.svg
--rw-rw-rw-   0        0        0      425 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/server.svg
--rw-rw-rw-   0        0        0     1005 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/settings.svg
--rw-rw-rw-   0        0        0      439 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/share-2.svg
--rw-rw-rw-   0        0        0      358 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/share.svg
--rw-rw-rw-   0        0        0      399 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/shield-off.svg
--rw-rw-rw-   0        0        0      273 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/shield.svg
--rw-rw-rw-   0        0        0      366 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/shopping-bag.svg
--rw-rw-rw-   0        0        0      377 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/shopping-cart.svg
--rw-rw-rw-   0        0        0      435 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/shuffle.svg
--rw-rw-rw-   0        0        0      317 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/sidebar.svg
--rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/skip-back.svg
--rw-rw-rw-   0        0        0      309 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/skip-forward.svg
--rw-rw-rw-   0        0        0      993 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/slack.svg
--rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/slash.svg
--rw-rw-rw-   0        0        0      605 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/sliders.svg
--rw-rw-rw-   0        0        0      326 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/smartphone.svg
--rw-rw-rw-   0        0        0      382 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/smile.svg
--rw-rw-rw-   0        0        0      360 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/speaker.svg
--rw-rw-rw-   0        0        0      274 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/square.svg
--rw-rw-rw-   0        0        0      333 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/star.svg
--rw-rw-rw-   0        0        0      303 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/stop-circle.svg
--rw-rw-rw-   0        0        0      644 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/sun.svg
--rw-rw-rw-   0        0        0      583 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/sunrise.svg
--rw-rw-rw-   0        0        0      582 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/sunset.svg
--rw-rw-rw-   0        0        0      322 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/tablet.svg
--rw-rw-rw-   0        0        0      349 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/tag.svg
--rw-rw-rw-   0        0        0      330 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/target.svg
--rw-rw-rw-   0        0        0      304 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/terminal.svg
--rw-rw-rw-   0        0        0      291 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/thermometer.svg
--rw-rw-rw-   0        0        0      368 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/thumbs-down.svg
--rw-rw-rw-   0        0        0      348 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/thumbs-up.svg
--rw-rw-rw-   0        0        0      317 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toggle-left.svg
--rw-rw-rw-   0        0        0      319 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toggle-right.svg
--rw-rw-rw-   0        0        0      380 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/tool.svg
--rw-rw-rw-   0        0        0     2703 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toolbar_move_horizontal.svg
--rw-rw-rw-   0        0        0     2710 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toolbar_move_vertical.svg
--rw-rw-rw-   0        0        0     2464 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toolbar_separator_horizontal.svg
--rw-rw-rw-   0        0        0     2463 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toolbar_separator_vertical.svg
--rw-rw-rw-   0        0        0     2347 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/transparent.svg
--rw-rw-rw-   0        0        0      442 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/trash-2.svg
--rw-rw-rw-   0        0        0      350 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/trash.svg
--rw-rw-rw-   0        0        0      367 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/trello.svg
--rw-rw-rw-   0        0        0      325 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/trending-down.svg
--rw-rw-rw-   0        0        0      322 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/trending-up.svg
--rw-rw-rw-   0        0        0      320 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/triangle.svg
--rw-rw-rw-   0        0        0      409 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/truck.svg
--rw-rw-rw-   0        0        0      314 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/tv.svg
--rw-rw-rw-   0        0        0      271 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/twitch.svg
--rw-rw-rw-   0        0        0      402 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/twitter.svg
--rw-rw-rw-   0        0        0      346 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/type.svg
--rw-rw-rw-   0        0        0      284 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/umbrella.svg
--rw-rw-rw-   0        0        0      313 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/underline.svg
--rw-rw-rw-   0        0        0      316 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/unlock.svg
--rw-rw-rw-   0        0        0      425 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/upload-cloud.svg
--rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/upload.svg
--rw-rw-rw-   0        0        0      361 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/user-check.svg
--rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/user-minus.svg
--rw-rw-rw-   0        0        0      402 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/user-plus.svg
--rw-rw-rw-   0        0        0      398 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/user-x.svg
--rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/user.svg
--rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/users.svg
--rw-rw-rw-   0        0        0      373 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/video-off.svg
--rw-rw-rw-   0        0        0      323 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/video.svg
--rw-rw-rw-   0        0        0      352 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/voicemail.svg
--rw-rw-rw-   0        0        0      322 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/volume-1.svg
--rw-rw-rw-   0        0        0      353 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/volume-2.svg
--rw-rw-rw-   0        0        0      364 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/volume-x.svg
--rw-rw-rw-   0        0        0      274 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/volume.svg
--rw-rw-rw-   0        0        0      456 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/watch.svg
--rw-rw-rw-   0        0        0      563 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/wifi-off.svg
--rw-rw-rw-   0        0        0      395 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/wifi.svg
--rw-rw-rw-   0        0        0      320 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/wind.svg
--rw-rw-rw-   0        0        0     2953 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/window_close.svg
--rw-rw-rw-   0        0        0     3018 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/window_grip.svg
--rw-rw-rw-   0        0        0     2465 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/window_minimize.svg
--rw-rw-rw-   0        0        0     2979 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/window_undock.svg
--rw-rw-rw-   0        0        0      340 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/x-circle.svg
--rw-rw-rw-   0        0        0      400 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/x-octagon.svg
--rw-rw-rw-   0        0        0      362 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/x-square.svg
--rw-rw-rw-   0        0        0      293 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/x.svg
--rw-rw-rw-   0        0        0      559 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/youtube.svg
--rw-rw-rw-   0        0        0      427 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/zap-off.svg
--rw-rw-rw-   0        0        0      276 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/zap.svg
--rw-rw-rw-   0        0        0      391 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/zoom-in.svg
--rw-rw-rw-   0        0        0      348 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/zoom-out.svg
--rw-rw-rw-   0        0        0      134 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/main.scss
--rw-rw-rw-   0        0        0    30871 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/RoundProgressBar.py
--rw-rw-rw-   0        0        0    40717 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/SpiralProgressBar.py
--rw-rw-rw-   0        0        0   156605 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Widgets.py
--rw-rw-rw-   0        0        0     4824 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/WidgetsWorker.py
--rw-rw-rw-   0        0        0       39 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:47.633954 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:52.480988 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/json/
--rw-rw-rw-   0        0        0      344 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/json/style.json
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:52.506046 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:52.517804 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/__pycache__/
--rw-rw-rw-   0        0        0      853 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/__pycache__/main.cpython-310.pyc
--rw-rw-rw-   0        0        0      836 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/__pycache__/main.cpython-38.pyc
--rw-rw-rw-   0        0        0     2561 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/__pycache__/ui_interface.cpython-310.pyc
--rw-rw-rw-   0        0        0     2552 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/__pycache__/ui_interface.cpython-38.pyc
--rw-rw-rw-   0        0        0     2679 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/main.py
--rw-rw-rw-   0        0        0     3127 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/ui_interface.py
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:52.529802 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/uis/
--rw-rw-rw-   0        0        0     2691 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/uis/interface.ui
--rw-rw-rw-   0        0        0     1242 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/interface.ui
--rw-rw-rw-   0        0        0     2368 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/main.py
--rw-rw-rw-   0        0        0    35149 2021-06-11 19:06:36.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/LICENSE
--rw-rw-rw-   0        0        0       82 2022-02-17 19:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/MANIFEST.in
--rw-rw-rw-   0        0        0     4179 2023-06-24 14:28:52.599805 QT-PyQt-PySide-Custom-Widgets-0.6.6/PKG-INFO
-drwxrwxrwx   0        0        0        0 2023-06-24 14:28:52.598805 QT-PyQt-PySide-Custom-Widgets-0.6.6/QT_PyQt_PySide_Custom_Widgets.egg-info/
--rw-rw-rw-   0        0        0     4179 2023-06-24 14:28:45.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/QT_PyQt_PySide_Custom_Widgets.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0    19309 2023-06-24 14:28:46.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/QT_PyQt_PySide_Custom_Widgets.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-24 14:28:45.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/QT_PyQt_PySide_Custom_Widgets.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       45 2023-06-24 14:28:45.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/QT_PyQt_PySide_Custom_Widgets.egg-info/requires.txt
--rw-rw-rw-   0        0        0       15 2023-06-24 14:28:45.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/QT_PyQt_PySide_Custom_Widgets.egg-info/top_level.txt
--rw-rw-rw-   0        0        0     3169 2022-08-11 03:08:01.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/README.md
--rw-rw-rw-   0        0        0       42 2023-06-24 14:28:52.611738 QT-PyQt-PySide-Custom-Widgets-0.6.6/setup.cfg
--rw-rw-rw-   0        0        0     2280 2023-06-24 14:27:59.000000 QT-PyQt-PySide-Custom-Widgets-0.6.6/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:42.686741 QT-PyQt-PySide-Custom-Widgets-0.6.7/
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:40.306594 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/
+-rw-rw-rw-   0        0        0    66370 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/AnalogGaugeWidget.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:40.354567 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/
+-rw-rw-rw-   0        0        0        0 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:40.378553 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/
+-rw-rw-rw-   0        0        0      185 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/__init__.cpython-310.pyc
+-rw-rw-rw-   0        0        0      178 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/__init__.cpython-38.pyc
+-rw-rw-rw-   0        0        0     3840 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/test.cpython-310.pyc
+-rw-rw-rw-   0        0        0     3948 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/test.cpython-38.pyc
+-rw-rw-rw-   0        0        0     5285 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-310.pyc
+-rw-rw-rw-   0        0        0     5276 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-38.pyc
+-rw-rw-rw-   0        0        0     5297 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-39.pyc
+-rw-rw-rw-   0        0        0     8502 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/interface.ui
+-rw-rw-rw-   0        0        0     9452 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/test.py
+-rw-rw-rw-   0        0        0     9629 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/ui_interface.py
+-rw-rw-rw-   0        0        0    14071 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProjectMaker.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:40.455510 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/
+-rw-rw-rw-   0        0        0    39288 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/QSS_Resources.qrc
+-rw-rw-rw-   0        0        0     6351 2023-06-22 15:51:45.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/SassCompiler.py
+-rw-rw-rw-   0        0        0    16118 2023-06-28 11:21:50.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/SvgToPngIcons.py
+-rw-rw-rw-   0        0        0       39 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:40.516476 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/
+-rw-rw-rw-   0        0        0   630113 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/QSS_Resources.cpython-39.pyc
+-rw-rw-rw-   0        0        0     3122 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-310.pyc
+-rw-rw-rw-   0        0        0     8339 2023-06-22 09:04:23.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-311.pyc
+-rw-rw-rw-   0        0        0     3459 2023-06-24 11:32:42.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-38.pyc
+-rw-rw-rw-   0        0        0     6895 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-310.pyc
+-rw-rw-rw-   0        0        0    22615 2023-06-22 09:04:25.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-311.pyc
+-rw-rw-rw-   0        0        0     7414 2023-06-28 11:13:50.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-38.pyc
+-rw-rw-rw-   0        0        0     3158 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-39.pyc
+-rw-rw-rw-   0        0        0      192 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/__init__.cpython-310.pyc
+-rw-rw-rw-   0        0        0      221 2023-06-22 09:04:23.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/__init__.cpython-311.pyc
+-rw-rw-rw-   0        0        0      177 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/__init__.cpython-37.pyc
+-rw-rw-rw-   0        0        0      185 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/__init__.cpython-38.pyc
+-rw-rw-rw-   0        0        0      188 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/__init__.cpython-39.pyc
+-rw-rw-rw-   0        0        0     6166 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-310.pyc
+-rw-rw-rw-   0        0        0    12628 2023-06-22 09:04:23.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-311.pyc
+-rw-rw-rw-   0        0        0     6168 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-37.pyc
+-rw-rw-rw-   0        0        0     6517 2023-06-24 16:00:37.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-38.pyc
+-rw-rw-rw-   0        0        0     6064 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-39.pyc
+-rw-rw-rw-   0        0        0   630112 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/resources_rc.cpython-39.pyc
+-rw-rw-rw-   0        0        0     2764 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/sassCompiler.cpython-39.pyc
+-rw-rw-rw-   0        0        0    60079 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/_styles.scss
+-rw-rw-rw-   0        0        0    10315 2023-06-24 16:00:28.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/colorsystem.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:40.203653 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:42.578803 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/
+-rw-rw-rw-   0        0        0      276 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/activity.svg
+-rw-rw-rw-   0        0        0      356 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/airplay.svg
+-rw-rw-rw-   0        0        0      350 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/alert-circle.svg
+-rw-rw-rw-   0        0        0      410 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/alert-octagon.svg
+-rw-rw-rw-   0        0        0      418 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/alert-triangle.svg
+-rw-rw-rw-   0        0        0      392 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/align-center.svg
+-rw-rw-rw-   0        0        0      393 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/align-justify.svg
+-rw-rw-rw-   0        0        0      390 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/align-left.svg
+-rw-rw-rw-   0        0        0      391 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/align-right.svg
+-rw-rw-rw-   0        0        0      339 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/anchor.svg
+-rw-rw-rw-   0        0        0      562 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/aperture.svg
+-rw-rw-rw-   0        0        0      355 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/archive.svg
+-rw-rw-rw-   0        0        0      354 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-down-circle.svg
+-rw-rw-rw-   0        0        0      309 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-down-left.svg
+-rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-down-right.svg
+-rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-down.svg
+-rw-rw-rw-   0        0        0      353 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-left-circle.svg
+-rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-left.svg
+-rw-rw-rw-   0        0        0      355 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-right-circle.svg
+-rw-rw-rw-   0        0        0      308 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-right.svg
+-rw-rw-rw-   0        0        0      351 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-up-circle.svg
+-rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-up-left.svg
+-rw-rw-rw-   0        0        0      308 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-up-right.svg
+-rw-rw-rw-   0        0        0      304 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow-up.svg
+-rw-rw-rw-   0        0        0     3022 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow_down.svg
+-rw-rw-rw-   0        0        0     3023 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow_left.svg
+-rw-rw-rw-   0        0        0     3026 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow_right.svg
+-rw-rw-rw-   0        0        0     3021 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow_up.svg
+-rw-rw-rw-   0        0        0      316 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/at-sign.svg
+-rw-rw-rw-   0        0        0      319 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/award.svg
+-rw-rw-rw-   0        0        0      349 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/bar-chart-2.svg
+-rw-rw-rw-   0        0        0      347 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/bar-chart.svg
+-rw-rw-rw-   0        0        0     7594 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/base_icon.svg
+-rw-rw-rw-   0        0        0    33666 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/base_palette.svg
+-rw-rw-rw-   0        0        0      421 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/battery-charging.svg
+-rw-rw-rw-   0        0        0      320 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/battery.svg
+-rw-rw-rw-   0        0        0      454 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/bell-off.svg
+-rw-rw-rw-   0        0        0      315 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/bell.svg
+-rw-rw-rw-   0        0        0      292 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/bluetooth.svg
+-rw-rw-rw-   0        0        0      321 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/bold.svg
+-rw-rw-rw-   0        0        0      333 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/book-open.svg
+-rw-rw-rw-   0        0        0      339 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/book.svg
+-rw-rw-rw-   0        0        0      281 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/bookmark.svg
+-rw-rw-rw-   0        0        0      456 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/box.svg
+-rw-rw-rw-   0        0        0     2755 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_closed.svg
+-rw-rw-rw-   0        0        0     2902 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_end.svg
+-rw-rw-rw-   0        0        0     3508 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_line.svg
+-rw-rw-rw-   0        0        0     2678 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_more.svg
+-rw-rw-rw-   0        0        0     2711 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_open.svg
+-rw-rw-rw-   0        0        0      337 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/briefcase.svg
+-rw-rw-rw-   0        0        0      404 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/calendar.svg
+-rw-rw-rw-   0        0        0      379 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/camera-off.svg
+-rw-rw-rw-   0        0        0      350 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/camera.svg
+-rw-rw-rw-   0        0        0      381 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cast.svg
+-rw-rw-rw-   0        0        0      322 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/check-circle.svg
+-rw-rw-rw-   0        0        0      339 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/check-square.svg
+-rw-rw-rw-   0        0        0      256 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/check.svg
+-rw-rw-rw-   0        0        0     2799 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/checkbox_checked.svg
+-rw-rw-rw-   0        0        0     2781 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/checkbox_indeterminate.svg
+-rw-rw-rw-   0        0        0     2598 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/checkbox_unchecked.svg
+-rw-rw-rw-   0        0        0      263 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/chevron-down.svg
+-rw-rw-rw-   0        0        0      264 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/chevron-left.svg
+-rw-rw-rw-   0        0        0      264 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/chevron-right.svg
+-rw-rw-rw-   0        0        0      262 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/chevron-up.svg
+-rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/chevrons-down.svg
+-rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/chevrons-left.svg
+-rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/chevrons-right.svg
+-rw-rw-rw-   0        0        0      310 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/chevrons-up.svg
+-rw-rw-rw-   0        0        0      442 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/chrome.svg
+-rw-rw-rw-   0        0        0      252 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/circle.svg
+-rw-rw-rw-   0        0        0      365 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/clipboard.svg
+-rw-rw-rw-   0        0        0      298 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/clock.svg
+-rw-rw-rw-   0        0        0      551 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cloud-drizzle.svg
+-rw-rw-rw-   0        0        0      339 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cloud-lightning.svg
+-rw-rw-rw-   0        0        0      365 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cloud-off.svg
+-rw-rw-rw-   0        0        0      415 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cloud-rain.svg
+-rw-rw-rw-   0        0        0      566 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cloud-snow.svg
+-rw-rw-rw-   0        0        0      274 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cloud.svg
+-rw-rw-rw-   0        0        0      301 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/code.svg
+-rw-rw-rw-   0        0        0      480 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/codepen.svg
+-rw-rw-rw-   0        0        0      632 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/codesandbox.svg
+-rw-rw-rw-   0        0        0      441 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/coffee.svg
+-rw-rw-rw-   0        0        0      320 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/columns.svg
+-rw-rw-rw-   0        0        0      415 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/command.svg
+-rw-rw-rw-   0        0        0      336 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/compass.svg
+-rw-rw-rw-   0        0        0      345 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/copy.svg
+-rw-rw-rw-   0        0        0      308 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/corner-down-left.svg
+-rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/corner-down-right.svg
+-rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/corner-left-down.svg
+-rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/corner-left-up.svg
+-rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/corner-right-down.svg
+-rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/corner-right-up.svg
+-rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/corner-up-left.svg
+-rw-rw-rw-   0        0        0      310 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/corner-up-right.svg
+-rw-rw-rw-   0        0        0      661 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cpu.svg
+-rw-rw-rw-   0        0        0      323 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/credit-card.svg
+-rw-rw-rw-   0        0        0      304 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/crop.svg
+-rw-rw-rw-   0        0        0      431 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/crosshair.svg
+-rw-rw-rw-   0        0        0      366 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/database.svg
+-rw-rw-rw-   0        0        0      368 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/delete.svg
+-rw-rw-rw-   0        0        0      289 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/disc.svg
+-rw-rw-rw-   0        0        0      391 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/divide-circle.svg
+-rw-rw-rw-   0        0        0      413 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/divide-square.svg
+-rw-rw-rw-   0        0        0      333 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/divide.svg
+-rw-rw-rw-   0        0        0      328 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/dollar-sign.svg
+-rw-rw-rw-   0        0        0      381 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/download-cloud.svg
+-rw-rw-rw-   0        0        0      364 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/download.svg
+-rw-rw-rw-   0        0        0      418 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/dribbble.svg
+-rw-rw-rw-   0        0        0      268 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/droplet.svg
+-rw-rw-rw-   0        0        0      285 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/edit-2.svg
+-rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/edit-3.svg
+-rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/edit.svg
+-rw-rw-rw-   0        0        0      382 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/external-link.svg
+-rw-rw-rw-   0        0        0      454 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/eye-off.svg
+-rw-rw-rw-   0        0        0      310 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/eye.svg
+-rw-rw-rw-   0        0        0      297 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/facebook.svg
+-rw-rw-rw-   0        0        0      317 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/fast-forward.svg
+-rw-rw-rw-   0        0        0      367 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/feather.svg
+-rw-rw-rw-   0        0        0      547 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/figma.svg
+-rw-rw-rw-   0        0        0      381 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/file-minus.svg
+-rw-rw-rw-   0        0        0      425 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/file-plus.svg
+-rw-rw-rw-   0        0        0      467 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/file-text.svg
+-rw-rw-rw-   0        0        0      331 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/file.svg
+-rw-rw-rw-   0        0        0      580 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/film.svg
+-rw-rw-rw-   0        0        0      284 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/filter.svg
+-rw-rw-rw-   0        0        0      328 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/flag.svg
+-rw-rw-rw-   0        0        0      355 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/folder-minus.svg
+-rw-rw-rw-   0        0        0      399 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/folder-plus.svg
+-rw-rw-rw-   0        0        0      305 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/folder.svg
+-rw-rw-rw-   0        0        0      272 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/framer.svg
+-rw-rw-rw-   0        0        0      384 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/frown.svg
+-rw-rw-rw-   0        0        0      475 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/gift.svg
+-rw-rw-rw-   0        0        0      371 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/git-branch.svg
+-rw-rw-rw-   0        0        0      352 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/git-commit.svg
+-rw-rw-rw-   0        0        0      330 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/git-merge.svg
+-rw-rw-rw-   0        0        0      381 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/git-pull-request.svg
+-rw-rw-rw-   0        0        0      521 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/github.svg
+-rw-rw-rw-   0        0        0      484 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/gitlab.svg
+-rw-rw-rw-   0        0        0      403 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/globe.svg
+-rw-rw-rw-   0        0        0      398 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/grid.svg
+-rw-rw-rw-   0        0        0      478 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/hard-drive.svg
+-rw-rw-rw-   0        0        0      383 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/hash.svg
+-rw-rw-rw-   0        0        0      389 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/headphones.svg
+-rw-rw-rw-   0        0        0      365 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/heart.svg
+-rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/help-circle.svg
+-rw-rw-rw-   0        0        0      352 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/hexagon.svg
+-rw-rw-rw-   0        0        0      326 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/home.svg
+-rw-rw-rw-   0        0        0      363 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/image.svg
+-rw-rw-rw-   0        0        0      399 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/inbox.svg
+-rw-rw-rw-   0        0        0      341 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/info.svg
+-rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/instagram.svg
+-rw-rw-rw-   0        0        0      342 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/italic.svg
+-rw-rw-rw-   0        0        0      346 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/key.svg
+-rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/layers.svg
+-rw-rw-rw-   0        0        0      358 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/layout.svg
+-rw-rw-rw-   0        0        0      569 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/life-buoy.svg
+-rw-rw-rw-   0        0        0     2445 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/line_horizontal.svg
+-rw-rw-rw-   0        0        0     2454 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/line_vertical.svg
+-rw-rw-rw-   0        0        0      349 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/link-2.svg
+-rw-rw-rw-   0        0        0      365 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/link.svg
+-rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/linkedin.svg
+-rw-rw-rw-   0        0        0      476 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/list.svg
+-rw-rw-rw-   0        0        0      608 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/loader.svg
+-rw-rw-rw-   0        0        0      315 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/lock.svg
+-rw-rw-rw-   0        0        0      362 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/log-in.svg
+-rw-rw-rw-   0        0        0      361 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/log-out.svg
+-rw-rw-rw-   0        0        0      348 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/mail.svg
+-rw-rw-rw-   0        0        0      316 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/map-pin.svg
+-rw-rw-rw-   0        0        0      367 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/map.svg
+-rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/maximize-2.svg
+-rw-rw-rw-   0        0        0      325 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/maximize.svg
+-rw-rw-rw-   0        0        0      383 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/meh.svg
+-rw-rw-rw-   0        0        0      340 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/menu.svg
+-rw-rw-rw-   0        0        0      422 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/message-circle.svg
+-rw-rw-rw-   0        0        0      299 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/message-square.svg
+-rw-rw-rw-   0        0        0      488 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/mic-off.svg
+-rw-rw-rw-   0        0        0      412 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/mic.svg
+-rw-rw-rw-   0        0        0      398 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/minimize-2.svg
+-rw-rw-rw-   0        0        0      325 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/minimize.svg
+-rw-rw-rw-   0        0        0      302 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/minus-circle.svg
+-rw-rw-rw-   0        0        0      324 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/minus-square.svg
+-rw-rw-rw-   0        0        0      255 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/minus.svg
+-rw-rw-rw-   0        0        0      364 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/monitor.svg
+-rw-rw-rw-   0        0        0      275 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/moon.svg
+-rw-rw-rw-   0        0        0      337 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/more-horizontal.svg
+-rw-rw-rw-   0        0        0      335 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/more-vertical.svg
+-rw-rw-rw-   0        0        0      305 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/mouse-pointer.svg
+-rw-rw-rw-   0        0        0      480 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/move.svg
+-rw-rw-rw-   0        0        0      321 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/music.svg
+-rw-rw-rw-   0        0        0      273 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/navigation-2.svg
+-rw-rw-rw-   0        0        0      271 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/navigation.svg
+-rw-rw-rw-   0        0        0      312 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/octagon.svg
+-rw-rw-rw-   0        0        0      511 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/package.svg
+-rw-rw-rw-   0        0        0      346 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/paperclip.svg
+-rw-rw-rw-   0        0        0      346 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/pause-circle.svg
+-rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/pause.svg
+-rw-rw-rw-   0        0        0      385 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/pen-tool.svg
+-rw-rw-rw-   0        0        0      344 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/percent.svg
+-rw-rw-rw-   0        0        0      570 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-call.svg
+-rw-rw-rw-   0        0        0      612 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-forwarded.svg
+-rw-rw-rw-   0        0        0      611 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-incoming.svg
+-rw-rw-rw-   0        0        0      607 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-missed.svg
+-rw-rw-rw-   0        0        0      585 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-off.svg
+-rw-rw-rw-   0        0        0      611 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-outgoing.svg
+-rw-rw-rw-   0        0        0      514 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone.svg
+-rw-rw-rw-   0        0        0      309 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/pie-chart.svg
+-rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/play-circle.svg
+-rw-rw-rw-   0        0        0      257 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/play.svg
+-rw-rw-rw-   0        0        0      345 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/plus-circle.svg
+-rw-rw-rw-   0        0        0      367 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/plus-square.svg
+-rw-rw-rw-   0        0        0      298 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/plus.svg
+-rw-rw-rw-   0        0        0      352 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/pocket.svg
+-rw-rw-rw-   0        0        0      302 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/power.svg
+-rw-rw-rw-   0        0        0      401 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/printer.svg
+-rw-rw-rw-   0        0        0      383 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/radio.svg
+-rw-rw-rw-   0        0        0     2714 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/radio_checked.svg
+-rw-rw-rw-   0        0        0     2419 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/radio_unchecked.svg
+-rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/refresh-ccw.svg
+-rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/refresh-cw.svg
+-rw-rw-rw-   0        0        0      386 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/repeat.svg
+-rw-rw-rw-   0        0        0      313 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/rewind.svg
+-rw-rw-rw-   0        0        0      311 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/rotate-ccw.svg
+-rw-rw-rw-   0        0        0      315 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/rotate-cw.svg
+-rw-rw-rw-   0        0        0      324 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/rss.svg
+-rw-rw-rw-   0        0        0      386 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/save.svg
+-rw-rw-rw-   0        0        0      438 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/scissors.svg
+-rw-rw-rw-   0        0        0      302 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/search.svg
+-rw-rw-rw-   0        0        0      308 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/send.svg
+-rw-rw-rw-   0        0        0      425 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/server.svg
+-rw-rw-rw-   0        0        0     1005 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/settings.svg
+-rw-rw-rw-   0        0        0      439 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/share-2.svg
+-rw-rw-rw-   0        0        0      358 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/share.svg
+-rw-rw-rw-   0        0        0      399 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/shield-off.svg
+-rw-rw-rw-   0        0        0      273 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/shield.svg
+-rw-rw-rw-   0        0        0      366 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/shopping-bag.svg
+-rw-rw-rw-   0        0        0      377 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/shopping-cart.svg
+-rw-rw-rw-   0        0        0      435 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/shuffle.svg
+-rw-rw-rw-   0        0        0      317 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/sidebar.svg
+-rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/skip-back.svg
+-rw-rw-rw-   0        0        0      309 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/skip-forward.svg
+-rw-rw-rw-   0        0        0      993 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/slack.svg
+-rw-rw-rw-   0        0        0      306 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/slash.svg
+-rw-rw-rw-   0        0        0      605 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/sliders.svg
+-rw-rw-rw-   0        0        0      326 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/smartphone.svg
+-rw-rw-rw-   0        0        0      382 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/smile.svg
+-rw-rw-rw-   0        0        0      360 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/speaker.svg
+-rw-rw-rw-   0        0        0      274 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/square.svg
+-rw-rw-rw-   0        0        0      333 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/star.svg
+-rw-rw-rw-   0        0        0      303 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/stop-circle.svg
+-rw-rw-rw-   0        0        0      644 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/sun.svg
+-rw-rw-rw-   0        0        0      583 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/sunrise.svg
+-rw-rw-rw-   0        0        0      582 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/sunset.svg
+-rw-rw-rw-   0        0        0      322 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/tablet.svg
+-rw-rw-rw-   0        0        0      349 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/tag.svg
+-rw-rw-rw-   0        0        0      330 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/target.svg
+-rw-rw-rw-   0        0        0      304 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/terminal.svg
+-rw-rw-rw-   0        0        0      291 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/thermometer.svg
+-rw-rw-rw-   0        0        0      368 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/thumbs-down.svg
+-rw-rw-rw-   0        0        0      348 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/thumbs-up.svg
+-rw-rw-rw-   0        0        0      317 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toggle-left.svg
+-rw-rw-rw-   0        0        0      319 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toggle-right.svg
+-rw-rw-rw-   0        0        0      380 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/tool.svg
+-rw-rw-rw-   0        0        0     2703 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toolbar_move_horizontal.svg
+-rw-rw-rw-   0        0        0     2710 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toolbar_move_vertical.svg
+-rw-rw-rw-   0        0        0     2464 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toolbar_separator_horizontal.svg
+-rw-rw-rw-   0        0        0     2463 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toolbar_separator_vertical.svg
+-rw-rw-rw-   0        0        0     2347 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/transparent.svg
+-rw-rw-rw-   0        0        0      442 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/trash-2.svg
+-rw-rw-rw-   0        0        0      350 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/trash.svg
+-rw-rw-rw-   0        0        0      367 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/trello.svg
+-rw-rw-rw-   0        0        0      325 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/trending-down.svg
+-rw-rw-rw-   0        0        0      322 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/trending-up.svg
+-rw-rw-rw-   0        0        0      320 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/triangle.svg
+-rw-rw-rw-   0        0        0      409 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/truck.svg
+-rw-rw-rw-   0        0        0      314 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/tv.svg
+-rw-rw-rw-   0        0        0      271 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/twitch.svg
+-rw-rw-rw-   0        0        0      402 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/twitter.svg
+-rw-rw-rw-   0        0        0      346 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/type.svg
+-rw-rw-rw-   0        0        0      284 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/umbrella.svg
+-rw-rw-rw-   0        0        0      313 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/underline.svg
+-rw-rw-rw-   0        0        0      316 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/unlock.svg
+-rw-rw-rw-   0        0        0      425 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/upload-cloud.svg
+-rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/upload.svg
+-rw-rw-rw-   0        0        0      361 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/user-check.svg
+-rw-rw-rw-   0        0        0      359 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/user-minus.svg
+-rw-rw-rw-   0        0        0      402 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/user-plus.svg
+-rw-rw-rw-   0        0        0      398 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/user-x.svg
+-rw-rw-rw-   0        0        0      307 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/user.svg
+-rw-rw-rw-   0        0        0      394 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/users.svg
+-rw-rw-rw-   0        0        0      373 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/video-off.svg
+-rw-rw-rw-   0        0        0      323 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/video.svg
+-rw-rw-rw-   0        0        0      352 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/voicemail.svg
+-rw-rw-rw-   0        0        0      322 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/volume-1.svg
+-rw-rw-rw-   0        0        0      353 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/volume-2.svg
+-rw-rw-rw-   0        0        0      364 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/volume-x.svg
+-rw-rw-rw-   0        0        0      274 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/volume.svg
+-rw-rw-rw-   0        0        0      456 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/watch.svg
+-rw-rw-rw-   0        0        0      563 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/wifi-off.svg
+-rw-rw-rw-   0        0        0      395 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/wifi.svg
+-rw-rw-rw-   0        0        0      320 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/wind.svg
+-rw-rw-rw-   0        0        0     2953 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/window_close.svg
+-rw-rw-rw-   0        0        0     3018 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/window_grip.svg
+-rw-rw-rw-   0        0        0     2465 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/window_minimize.svg
+-rw-rw-rw-   0        0        0     2979 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/window_undock.svg
+-rw-rw-rw-   0        0        0      340 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/x-circle.svg
+-rw-rw-rw-   0        0        0      400 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/x-octagon.svg
+-rw-rw-rw-   0        0        0      362 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/x-square.svg
+-rw-rw-rw-   0        0        0      293 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/x.svg
+-rw-rw-rw-   0        0        0      559 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/youtube.svg
+-rw-rw-rw-   0        0        0      427 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/zap-off.svg
+-rw-rw-rw-   0        0        0      276 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/zap.svg
+-rw-rw-rw-   0        0        0      391 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/zoom-in.svg
+-rw-rw-rw-   0        0        0      348 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/zoom-out.svg
+-rw-rw-rw-   0        0        0      134 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/main.scss
+-rw-rw-rw-   0        0        0    30871 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/RoundProgressBar.py
+-rw-rw-rw-   0        0        0    40717 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/SpiralProgressBar.py
+-rw-rw-rw-   0        0        0   156605 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Widgets.py
+-rw-rw-rw-   0        0        0     4824 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/WidgetsWorker.py
+-rw-rw-rw-   0        0        0       39 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:40.206651 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:42.580802 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/json/
+-rw-rw-rw-   0        0        0      344 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/json/style.json
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:42.598792 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:42.611785 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/__pycache__/
+-rw-rw-rw-   0        0        0      853 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/__pycache__/main.cpython-310.pyc
+-rw-rw-rw-   0        0        0      836 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/__pycache__/main.cpython-38.pyc
+-rw-rw-rw-   0        0        0     2561 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/__pycache__/ui_interface.cpython-310.pyc
+-rw-rw-rw-   0        0        0     2552 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/__pycache__/ui_interface.cpython-38.pyc
+-rw-rw-rw-   0        0        0     2679 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/main.py
+-rw-rw-rw-   0        0        0     3127 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/ui_interface.py
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:42.626776 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/uis/
+-rw-rw-rw-   0        0        0     2691 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/uis/interface.ui
+-rw-rw-rw-   0        0        0     1242 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/interface.ui
+-rw-rw-rw-   0        0        0     2368 2023-06-21 21:32:18.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/main.py
+-rw-rw-rw-   0        0        0    35823 2023-06-27 07:08:33.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/LICENSE
+-rw-rw-rw-   0        0        0       84 2023-06-27 07:08:33.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/MANIFEST.in
+-rw-rw-rw-   0        0        0     4187 2023-06-28 11:35:42.679746 QT-PyQt-PySide-Custom-Widgets-0.6.7/PKG-INFO
+drwxrwxrwx   0        0        0        0 2023-06-28 11:35:42.677748 QT-PyQt-PySide-Custom-Widgets-0.6.7/QT_PyQt_PySide_Custom_Widgets.egg-info/
+-rw-rw-rw-   0        0        0     4187 2023-06-28 11:35:39.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/QT_PyQt_PySide_Custom_Widgets.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0    19309 2023-06-28 11:35:39.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/QT_PyQt_PySide_Custom_Widgets.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 11:35:39.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/QT_PyQt_PySide_Custom_Widgets.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       45 2023-06-28 11:35:39.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/QT_PyQt_PySide_Custom_Widgets.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       15 2023-06-28 11:35:39.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/QT_PyQt_PySide_Custom_Widgets.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0     3169 2023-06-27 07:08:33.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 11:35:42.687741 QT-PyQt-PySide-Custom-Widgets-0.6.7/setup.cfg
+-rw-rw-rw-   0        0        0     2291 2023-06-28 11:34:26.000000 QT-PyQt-PySide-Custom-Widgets-0.6.7/setup.py
```

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/AnalogGaugeWidget.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/AnalogGaugeWidget.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/test.cpython-310.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/test.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/test.cpython-38.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/test.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-310.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-38.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-39.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/__pycache__/ui_interface.cpython-39.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/interface.ui` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/interface.ui`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/test.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/test.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProgressIndicator/ui_interface.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProgressIndicator/ui_interface.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/ProjectMaker.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/ProjectMaker.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/QSS_Resources.qrc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/QSS_Resources.qrc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/SassCompiler.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/SassCompiler.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/SvgToPngIcons.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/SvgToPngIcons.py`

 * *Files 2% similar despite different names*

```diff
@@ -9,14 +9,16 @@
 from urllib.parse import urlparse
 from pathlib import Path
 import __main__
 
 
 
 from . colorsystem import *
+import qtpy
+from qtpy.QtCore import *
 
 settings = QSettings()
 
 class NewIconsGenerator():
     """docstring for NewIconsGenerator"""
     def __init__(self, arg):
         super(NewIconsGenerator, self).__init__()
@@ -172,15 +174,24 @@
             py_resource_path = resource_path.replace(".qrc", ".py")
             py_resource_path = py_resource_path.replace("QSS/", "") #linux
             py_resource_path = py_resource_path.replace("QSS\\", "") #windows
             py_resource_path = py_resource_path.replace("QSS_Resources", "QSS_Resources_rc")
             # Convert qrc to py
             try:
                 settings.setValue("ICONS-COLOR", normal_color)
-                os.system('pyrcc5 "'+resource_path+'" -o "'+py_resource_path+'"')
+                if qtpy.API_NAME == "PyQt5":
+                    os.system('pyrcc5 "'+resource_path+'" -o "'+py_resource_path+'"')
+                if qtpy.API_NAME == "PyQt6":
+                    os.system('pyrcc6 "'+resource_path+'" -o "'+py_resource_path+'"')
+                elif qtpy.API_NAME == "PySide2":
+                    os.system('pyside2-rcc "'+resource_path+'" -o "'+py_resource_path+'"')
+                elif qtpy.API_NAME == "PySide6":
+                    os.system('pyside6-rcc "'+resource_path+'" -o "'+py_resource_path+'"')
+                
+
                 settings.setValue("ICONS-COLOR", normal_color)
             except Exception as e:
                 # raise e
                 print("error while converting resource file")  
 
             # Reload resources:
             resource_module = "QSS_Resources_rc"  # Replace with your resource module name
```

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/QSS_Resources.cpython-39.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/QSS_Resources.cpython-39.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-310.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-311.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-38.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SassCompiler.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-310.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-311.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-38.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Sat Jun 24 12:21:15 2023 UTC, .py size: 15602 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 5% similar despite different names*

```diff
@@ -1,455 +1,464 @@
-00000000: 550d 0d0a 0000 0000 bbdf 9664 f23c 0000  U..........d.<..
+00000000: 550d 0d0a 0000 0000 d715 9c64 d53d 0000  U..........d.=..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
-00000020: 0003 0000 0040 0000 0073 8000 0000 6400  .....@...s....d.
+00000020: 0003 0000 0040 0000 0073 9000 0000 6400  .....@...s....d.
 00000030: 6401 6c00 5a00 6400 6401 6c01 5a01 6400  d.l.Z.d.d.l.Z.d.
 00000040: 6401 6c02 5a02 6400 6401 6c03 5a03 6400  d.l.Z.d.d.l.Z.d.
 00000050: 6401 6c04 5a04 6400 6401 6c05 5a05 6400  d.l.Z.d.d.l.Z.d.
 00000060: 6401 6c06 5a06 6400 6401 6c07 5a07 6400  d.l.Z.d.d.l.Z.d.
 00000070: 6402 6c08 6d09 5a09 0100 6400 6403 6c0a  d.l.m.Z...d.d.l.
 00000080: 6d0b 5a0b 0100 6400 6401 6c0c 5a0c 6404  m.Z...d.d.l.Z.d.
-00000090: 6405 6c0d 5400 650e 8300 5a0f 4700 6406  d.l.T.e...Z.G.d.
-000000a0: 6407 8400 6407 8302 5a10 6401 5300 2908  d...d...Z.d.S.).
-000000b0: e900 0000 004e 2901 da08 7572 6c70 6172  .....N)...urlpar
-000000c0: 7365 2901 da04 5061 7468 e901 0000 0029  se)...Path.....)
-000000d0: 01da 012a 6300 0000 0000 0000 0000 0000  ...*c...........
-000000e0: 0000 0000 0003 0000 0000 0000 0073 3800  .............s8.
-000000f0: 0000 6500 5a01 6400 5a02 6401 5a03 8700  ..e.Z.d.Z.d.Z...
-00000100: 6601 6402 6403 8408 5a04 6404 6405 8400  f.d.d...Z.d.d...
-00000110: 5a05 6406 6407 8400 5a06 6408 6409 8400  Z.d.d...Z.d.d...
-00000120: 5a07 8700 0400 5a08 5300 290a da11 4e65  Z.....Z.S.)...Ne
-00000130: 7749 636f 6e73 4765 6e65 7261 746f 727a  wIconsGeneratorz
-00000140: 1f64 6f63 7374 7269 6e67 2066 6f72 204e  .docstring for N
-00000150: 6577 4963 6f6e 7347 656e 6572 6174 6f72  ewIconsGenerator
-00000160: 6302 0000 0000 0000 0000 0000 0002 0000  c...............
-00000170: 0003 0000 0003 0000 0073 1800 0000 7400  .........s....t.
-00000180: 7401 7c00 8302 a002 a100 0100 7c01 7c00  t.|.........|.|.
-00000190: 5f03 6400 5300 2901 4e29 04da 0573 7570  _.d.S.).N)...sup
-000001a0: 6572 7206 0000 00da 085f 5f69 6e69 745f  err......__init_
-000001b0: 5fda 0361 7267 2902 da04 7365 6c66 7209  _..arg)...selfr.
-000001c0: 0000 00a9 01da 095f 5f63 6c61 7373 5f5f  .......__class__
-000001d0: a900 fa48 653a 5c53 7069 6e6e 2054 6173  ...He:\Spinn Tas
-000001e0: 6b5c 3070 6173 735c 3070 6173 732d 6170  k\0pass\0pass-ap
-000001f0: 702d 6d61 7374 6572 5c43 7573 746f 6d5f  p-master\Custom_
-00000200: 5769 6467 6574 735c 5173 735c 5376 6754  Widgets\Qss\SvgT
-00000210: 6f50 6e67 4963 6f6e 732e 7079 7208 0000  oPngIcons.pyr...
-00000220: 0015 0000 0073 0400 0000 0001 0e01 7a1a  .....s........z.
-00000230: 4e65 7749 636f 6e73 4765 6e65 7261 746f  NewIconsGenerato
-00000240: 722e 5f5f 696e 6974 5f5f 6302 0000 0000  r.__init__c.....
-00000250: 0000 0000 0000 0024 0000 000c 0000 0043  .......$.......C
-00000260: 0000 0073 4a07 0000 7400 8300 7d02 7401  ...sJ...t...}.t.
-00000270: 6a02 a003 7404 a101 7d03 7401 6a02 a005  j...t...}.t.j...
-00000280: 7c03 6401 a102 7d04 6700 7d05 7406 a007  |.d...}.g.}.t...
-00000290: 7c00 a101 7d06 6402 7d07 7408 7c06 6403  |...}.d.}.t.|.d.
-000002a0: 1900 8301 7d08 7409 7c08 6404 8302 7d09  ....}.t.|.d...}.
-000002b0: 7409 7c08 6405 8302 7d0a 7c08 a00a 6406  t.|.d...}.|...d.
-000002c0: 6407 a102 7d0b 7401 6a02 a00b 7401 6a02  d...}.t.j...t.j.
-000002d0: a005 7401 a00c a100 6408 7c0b 1700 a102  ..t.....d.|.....
-000002e0: a101 7d0c 7401 6a02 a00b 7401 6a02 a005  ..}.t.j...t.j...
-000002f0: 7401 a00c a100 6409 a102 a101 7d0d 7c02  t.....d.....}.|.
-00000300: a00d 640a a101 6400 6b08 72da 7406 a007  ..d...d.k.r.t...
-00000310: 7c00 a101 7d0e 7401 6a02 a00b 7401 6a02  |...}.t.j...t.j.
-00000320: a005 7401 a00c a100 6408 7c0e 6403 1900  ..t.....d.|.d...
-00000330: a00a 6406 6407 a102 1700 a102 a101 7d0f  ..d.d.........}.
-00000340: 6e2c 7401 6a02 a00b 7401 6a02 a005 7401  n,t.j...t.j...t.
-00000350: a00c a100 6408 7c02 a00d 640a a101 a00a  ....d.|...d.....
-00000360: 6406 6407 a102 1700 a102 a101 7d0f 7c02  d.d.........}.|.
-00000370: a00d 640a a101 7c08 6b02 9007 733a 7c06  ..d...|.k...s:|.
-00000380: 6403 1900 6400 6b09 9007 723a 7c00 6a0e  d...d.k...r:|.j.
-00000390: 9001 7248 740f 640b 7c02 a00d 640a a101  ..rHt.d.|...d...
-000003a0: 640c 7c08 8304 0100 740f 640d 8301 0100  d.|.....t.d.....
-000003b0: 7401 a010 7c04 a101 4400 5d2c 5c03 7d10  t...|...D.],\.}.
-000003c0: 7d11 7d12 7c12 4400 5d1a 7d13 7c05 a011  }.}.|.D.].}.|...
-000003d0: 7401 6a02 a005 7c10 7c13 a102 a101 0100  t.j...|.|.......
-000003e0: 9001 7160 9001 7152 7412 7c05 8301 7d14  ..q`..qRt.|...}.
-000003f0: 7c05 4400 9001 5d26 7d15 7401 6a02 a013  |.D...]&}.t.j...
-00000400: 7414 7c15 8301 6a02 a101 a00a 640e 640f  t.|...j.....d.d.
-00000410: a102 7d16 7401 6a02 a015 7401 6a02 a005  ..}.t.j...t.j...
-00000420: 7c0d 7c16 a102 a101 9001 72f2 7401 6a02  |.|.......r.t.j.
-00000430: a015 7401 6a02 a005 7c0f 7c16 a102 a101  ..t.j...|.|.....
-00000440: 9001 73f2 7416 a017 7401 6a02 a005 7c0d  ..s.t...t.j...|.
-00000450: 7c16 a102 7c0f a102 0100 7401 6a02 a013  |...|.....t.j...
-00000460: 7414 7c15 8301 6a02 a101 a00a 640e 6410  t.|...j.....d.d.
-00000470: a102 7d16 7401 6a02 a015 7401 6a02 a005  ..}.t.j...t.j...
-00000480: 7c0d 7c16 a102 a101 9002 7252 7401 6a02  |.|.......rRt.j.
-00000490: a015 7401 6a02 a005 7c0f 7c16 a102 a101  ..t.j...|.|.....
-000004a0: 9002 7352 7416 a017 7401 6a02 a005 7c0d  ..sRt...t.j...|.
-000004b0: 7c16 a102 7c0f a102 0100 7401 6a02 a013  |...|.....t.j...
-000004c0: 7414 7c15 8301 6a02 a101 a00a 640e 6411  t.|...j.....d.d.
-000004d0: a102 7d16 7401 6a02 a015 7401 6a02 a005  ..}.t.j...t.j...
-000004e0: 7c0d 7c16 a102 a101 9001 728c 7401 6a02  |.|.......r.t.j.
-000004f0: a015 7401 6a02 a005 7c0f 7c16 a102 a101  ..t.j...|.|.....
-00000500: 9001 738c 7416 a017 7401 6a02 a005 7c0d  ..s.t...t.j...|.
-00000510: 7c16 a102 7c0f a102 0100 9001 718c 7c05  |...|.......q.|.
-00000520: 4400 9002 5d92 7d15 7418 6a19 7c15 6412  D...].}.t.j.|.d.
-00000530: 6413 6414 8d03 8fba 7d17 7c17 a01a a100  d.d.....}.|.....
-00000540: 7d18 7c18 a00a 7c07 7c08 a102 7d19 7408  }.|...|.|...}.t.
-00000550: a01b 7c19 a101 7d1a 7401 6a02 a013 7414  ..|...}.t.j...t.
-00000560: 7c15 8301 6a02 a101 a00a 640e 640f a102  |...j.....d.d...
-00000570: 7d16 7401 6a02 a00b 7401 6a02 a005 7c0c  }.t.j...t.j...|.
-00000580: 7c16 a102 a101 7d04 7401 6a02 a015 7c0c  |.....}.t.j...|.
-00000590: a101 9003 7338 7401 a01c 7c0c a101 0100  ....s8t...|.....
-000005a0: 7401 6a02 a015 7c04 a101 9003 7386 7a12  t.j...|.....s.z.
-000005b0: 741d 6a1e 7c1a 7c04 6415 8d02 0100 5700  t.j.|.|.d.....W.
-000005c0: 6e2c 0400 741f 6b0a 9003 7284 0100 7d1b  n,..t.k...r...}.
-000005d0: 0100 7a0c 740f 7c1b 8301 0100 5700 3500  ..z.t.|.....W.5.
-000005e0: 6400 7d1b 7e1b 5800 5900 6e02 5800 5700  d.}.~.X.Y.n.X.W.
-000005f0: 3500 5100 5200 5800 7418 6a19 7c15 6412  5.Q.R.X.t.j.|.d.
-00000600: 6413 6414 8d03 8fba 7d17 7c17 a01a a100  d.d.....}.|.....
-00000610: 7d18 7c18 a00a 7c07 7c09 a102 7d19 7408  }.|...|.|...}.t.
-00000620: a01b 7c19 a101 7d1a 7401 6a02 a013 7414  ..|...}.t.j...t.
-00000630: 7c15 8301 6a02 a101 a00a 640e 6410 a102  |...j.....d.d...
-00000640: 7d16 7401 6a02 a00b 7401 6a02 a005 7c0c  }.t.j...t.j...|.
-00000650: 7c16 a102 a101 7d04 7401 6a02 a015 7c0c  |.....}.t.j...|.
-00000660: a101 9004 7308 7401 a01c 7c0c a101 0100  ....s.t...|.....
-00000670: 7401 6a02 a015 7c04 a101 9004 7356 7a12  t.j...|.....sVz.
-00000680: 741d 6a1e 7c1a 7c04 6415 8d02 0100 5700  t.j.|.|.d.....W.
-00000690: 6e2c 0400 741f 6b0a 9004 7254 0100 7d1b  n,..t.k...rT..}.
-000006a0: 0100 7a0c 740f 7c1b 8301 0100 5700 3500  ..z.t.|.....W.5.
-000006b0: 6400 7d1b 7e1b 5800 5900 6e02 5800 5700  d.}.~.X.Y.n.X.W.
-000006c0: 3500 5100 5200 5800 7418 6a19 7c15 6412  5.Q.R.X.t.j.|.d.
-000006d0: 6413 6414 8d03 8fba 7d17 7c17 a01a a100  d.d.....}.|.....
-000006e0: 7d18 7c18 a00a 7c07 7c0a a102 7d19 7408  }.|...|.|...}.t.
-000006f0: a01b 7c19 a101 7d1a 7401 6a02 a013 7414  ..|...}.t.j...t.
-00000700: 7c15 8301 6a02 a101 a00a 640e 6411 a102  |...j.....d.d...
-00000710: 7d16 7401 6a02 a00b 7401 6a02 a005 7c0c  }.t.j...t.j...|.
-00000720: 7c16 a102 a101 7d04 7401 6a02 a015 7c0c  |.....}.t.j...|.
-00000730: a101 9004 73d8 7401 a01c 7c0c a101 0100  ....s.t...|.....
-00000740: 7401 6a02 a015 7c04 a101 9005 7326 7a12  t.j...|.....s&z.
-00000750: 741d 6a1e 7c1a 7c04 6415 8d02 0100 5700  t.j.|.|.d.....W.
-00000760: 6e2c 0400 741f 6b0a 9005 7224 0100 7d1b  n,..t.k...r$..}.
-00000770: 0100 7a0c 740f 7c1b 8301 0100 5700 3500  ..z.t.|.....W.5.
-00000780: 6400 7d1b 7e1b 5800 5900 6e02 5800 5700  d.}.~.X.Y.n.X.W.
-00000790: 3500 5100 5200 5800 7c01 a020 7421 7c05  5.Q.R.X.|.. t!|.
-000007a0: a022 7c15 a101 7c14 1b00 6416 1400 8301  ."|...|...d.....
-000007b0: a101 0100 9002 71ba 7c0c 7d1c 7c0d 7d1d  ......q.|.}.|.}.
-000007c0: 7401 a023 7c1c a101 7d1e 7401 6a02 a015  t..#|...}.t.j...
-000007d0: 7c0d a101 9005 737c 7401 a01c 7c0d a101  |.....s|t...|...
-000007e0: 0100 6e18 7401 6a02 a015 7c0d a101 9005  ..n.t.j...|.....
-000007f0: 7394 7401 a01c 7c0d a101 0100 6417 7d1f  s.t...|.....d.}.
-00000800: 7c1e 4400 5d9e 7d20 7401 6a24 6418 6b02  |.D.].} t.j$d.k.
-00000810: 9005 72c4 7416 a025 7401 6a02 a005 7c1c  ..r.t..%t.j...|.
-00000820: 7c20 a102 7c1d a102 0100 6e56 7a1a 7416  | ..|.....nVz.t.
-00000830: a017 7401 6a02 a005 7c1c 7c20 a102 7c1d  ..t.j...|.| ..|.
-00000840: a102 0100 5700 6e3a 0400 741f 6b0a 9006  ....W.n:..t.k...
-00000850: 7218 0100 7d1b 0100 7a1a 7416 a025 7401  r...}...z.t..%t.
-00000860: 6a02 a005 7c1c 7c20 a102 7c1d a102 0100  j...|.| ..|.....
-00000870: 5700 3500 6400 7d1b 7e1b 5800 5900 6e02  W.5.d.}.~.X.Y.n.
-00000880: 5800 7c1f 6419 3700 7d1f 7c01 a020 7421  X.|.d.7.}.|.. t!
-00000890: 7c1f 7c14 1b00 6416 1400 8301 a101 0100  |.|...d.........
-000008a0: 9005 719c 7401 6a02 a00b 7401 6a02 a005  ..q.t.j...t.j...
-000008b0: 7401 a00c a100 641a a102 a101 7d21 7401  t.....d.....}!t.
-000008c0: 6a02 a015 7c21 a101 9006 73a0 7416 a025  j...|!....s.t..%
-000008d0: 7401 6a02 a00b 7401 6a02 a005 7401 6a02  t.j...t.j...t.j.
-000008e0: a003 7404 a101 641b a102 a101 7401 6a02  ..t...d.....t.j.
-000008f0: a00b 7401 6a02 a005 7401 a00c a100 641c  ..t.j...t.....d.
-00000900: a102 a101 a102 0100 7c21 a00a 641d 641e  ........|!..d.d.
-00000910: a102 7d22 7c22 a00a 6408 6407 a102 7d22  ..}"|"..d.d...}"
-00000920: 7c22 a00a 641f 6407 a102 7d22 7c22 a00a  |"..d.d...}"|"..
-00000930: 6420 6421 a102 7d22 7a36 7c02 a026 640a  d d!..}"z6|..&d.
-00000940: 7c08 a102 0100 7401 a027 6422 7c21 1700  |.....t..'d"|!..
-00000950: 6423 1700 7c22 1700 6424 1700 a101 0100  d#..|"..d$......
-00000960: 7c02 a026 640a 7c08 a102 0100 5700 6e2c  |..&d.|.....W.n,
-00000970: 0400 741f 6b0a 9007 7232 0100 7d1b 0100  ..t.k...r2..}...
-00000980: 7a0c 740f 6425 8301 0100 5700 3500 6400  z.t.d%....W.5.d.
-00000990: 7d1b 7e1b 5800 5900 6e02 5800 6421 7d23  }.~.X.Y.n.X.d!}#
-000009a0: 6e0c 7428 a029 7c00 7c01 a102 0100 6400  n.t(.)|.|.....d.
-000009b0: 5300 2926 4efa 1269 636f 6e73 2f6f 7269  S.)&N..icons/ori
-000009c0: 6769 6e61 6c5f 7376 67fa 0423 6666 667a  ginal_svg..#fffz
-000009d0: 0b69 636f 6e73 2d63 6f6c 6f72 e700 0000  .icons-color....
-000009e0: 0000 00f8 3fe7 0000 0000 0000 e03f fa01  ....?........?..
-000009f0: 23da 00fa 0451 5353 2ffa 0951 5353 2f49  #....QSS/..QSS/I
-00000a00: 636f 6e73 fa0b 4943 4f4e 532d 434f 4c4f  cons..ICONS-COLO
-00000a10: 527a 1443 7572 7265 6e74 2069 636f 6e73  Rz.Current icons
-00000a20: 2063 6f6c 6f72 207a 0f4e 6577 2069 636f   color z.New ico
-00000a30: 6e73 2063 6f6c 6f72 7a40 4765 6e65 7261  ns colorz@Genera
-00000a40: 7469 6e67 2069 636f 6e73 2066 6f72 2079  ting icons for y
-00000a50: 6f75 7220 7468 656d 652c 2070 6c65 6173  our theme, pleas
-00000a60: 6520 7761 6974 2e20 5468 6973 206d 6179  e wait. This may
-00000a70: 2074 616b 6520 6c6f 6e67 fa04 2e73 7667   take long...svg
-00000a80: fa04 2e70 6e67 fa0a 5f66 6f63 7573 2e70  ...png.._focus.p
-00000a90: 6e67 fa0d 5f64 6973 6162 6c65 642e 706e  ng.._disabled.pn
-00000aa0: 67fa 0575 7466 2d38 da06 6967 6e6f 7265  g..utf-8..ignore
-00000ab0: a902 da08 656e 636f 6469 6e67 da06 6572  ....encoding..er
-00000ac0: 726f 7273 a902 5a0a 6279 7465 7374 7269  rors..Z.bytestri
-00000ad0: 6e67 5a08 7772 6974 655f 746f e964 0000  ngZ.write_to.d..
-00000ae0: 0072 0100 0000 da02 6e74 7204 0000 007a  .r......ntr....z
-00000af0: 1551 5353 2f51 5353 5f52 6573 6f75 7263  .QSS/QSS_Resourc
-00000b00: 6573 2e71 7263 7a11 5153 535f 5265 736f  es.qrcz.QSS_Reso
-00000b10: 7572 6365 732e 7172 63da 0351 5353 7a04  urces.qrc..QSSz.
-00000b20: 2e71 7263 fa03 2e70 797a 0451 5353 5c5a  .qrc...pyz.QSS\Z
-00000b30: 0d51 5353 5f52 6573 6f75 7263 6573 5a10  .QSS_ResourcesZ.
-00000b40: 5153 535f 5265 736f 7572 6365 735f 7263  QSS_Resources_rc
-00000b50: 7a08 7079 7263 6335 2022 7a06 2220 2d6f  z.pyrcc5 "z." -o
-00000b60: 2022 fa01 227a 2465 7272 6f72 2077 6869   ".."z$error whi
-00000b70: 6c65 2063 6f6e 7665 7274 696e 6720 7265  le converting re
-00000b80: 736f 7572 6365 2066 696c 6529 2ada 0951  source file)*..Q
-00000b90: 5365 7474 696e 6773 da02 6f73 da04 7061  Settings..os..pa
-00000ba0: 7468 da07 6469 726e 616d 65da 085f 5f66  th..dirname..__f
-00000bb0: 696c 655f 5fda 046a 6f69 6eda 1343 7265  ile__..join..Cre
-00000bc0: 6174 6543 6f6c 6f72 5661 7269 6162 6c65  ateColorVariable
-00000bd0: da13 6765 7443 7572 7265 6e74 5468 656d  ..getCurrentThem
-00000be0: 6549 6e66 6fda 0373 7472 da10 6164 6a75  eInfo..str..adju
-00000bf0: 7374 5f6c 6967 6874 6e65 7373 da07 7265  st_lightness..re
-00000c00: 706c 6163 65da 0761 6273 7061 7468 da06  place..abspath..
-00000c10: 6765 7463 7764 da05 7661 6c75 65da 1573  getcwd..value..s
-00000c20: 686f 7743 7573 746f 6d57 6964 6765 7473  howCustomWidgets
-00000c30: 4c6f 6773 da05 7072 696e 74da 0477 616c  Logs..print..wal
-00000c40: 6bda 0661 7070 656e 64da 036c 656e da08  k..append..len..
-00000c50: 6261 7365 6e61 6d65 7202 0000 00da 0665  basenamer......e
-00000c60: 7869 7374 73da 0673 6875 7469 6cda 046d  xists..shutil..m
-00000c70: 6f76 65da 0663 6f64 6563 73da 046f 7065  ove..codecs..ope
-00000c80: 6eda 0472 6561 64da 0665 6e63 6f64 65da  n..read..encode.
-00000c90: 086d 616b 6564 6972 73da 0863 6169 726f  .makedirs..cairo
-00000ca0: 7376 67da 0773 7667 3270 6e67 da09 4578  svg..svg2png..Ex
-00000cb0: 6365 7074 696f 6eda 0465 6d69 74da 0369  ception..emit..i
-00000cc0: 6e74 da05 696e 6465 78da 076c 6973 7464  nt..index..listd
-00000cd0: 6972 da04 6e61 6d65 da04 636f 7079 da08  ir..name..copy..
-00000ce0: 7365 7456 616c 7565 da06 7379 7374 656d  setValue..system
-00000cf0: 7206 0000 00da 1067 656e 6572 6174 6541  r......generateA
-00000d00: 6c6c 4963 6f6e 7329 2472 0a00 0000 da11  llIcons)$r......
-00000d10: 7072 6f67 7265 7373 5f63 616c 6c62 6163  progress_callbac
-00000d20: 6bda 0873 6574 7469 6e67 7372 2a00 0000  k..settingsr*...
-00000d30: da08 6669 6c65 6e61 6d65 da0d 6c69 7374  ..filename..list
-00000d40: 5f6f 665f 6669 6c65 73da 0563 6f6c 6f72  _of_files..color
-00000d50: da09 7376 675f 636f 6c6f 72da 0c6e 6f72  ..svg_color..nor
-00000d60: 6d61 6c5f 636f 6c6f 72da 0d66 6f63 7573  mal_color..focus
-00000d70: 6564 5f63 6f6c 6f72 da0e 6469 7361 626c  ed_color..disabl
-00000d80: 6564 5f63 6f6c 6f72 da0f 6963 6f6e 7346  ed_color..iconsF
-00000d90: 6f6c 6465 724e 616d 65da 0b69 636f 6e73  olderName..icons
-00000da0: 466f 6c64 6572 da0e 6f6c 6449 636f 6e73  Folder..oldIcons
-00000db0: 466f 6c64 6572 da0d 7661 7269 6162 6c65  Folder..variable
-00000dc0: 7346 696c 655a 196f 6c64 4963 6f6e 7344  sFileZ.oldIconsD
-00000dd0: 6573 7469 6e61 7469 6f6e 466f 6c64 6572  estinationFolder
-00000de0: da04 726f 6f74 da04 6469 7273 da05 6669  ..root..dirs..fi
-00000df0: 6c65 73da 0466 696c 65da 0a74 6f74 616c  les..file..total
-00000e00: 4963 6f6e 7372 4a00 0000 da06 6e61 6d65  IconsrJ.....name
-00000e10: 5f32 da01 66da 0763 6f6e 7465 6e74 da06  _2..f..content..
-00000e20: 6e65 7753 5647 da08 6e65 7742 7974 6573  newSVG..newBytes
-00000e30: da01 655a 0a73 6f75 7263 655f 6469 725a  ..eZ.source_dirZ
-00000e40: 0a74 6172 6765 745f 6469 725a 0a66 696c  .target_dirZ.fil
-00000e50: 655f 6e61 6d65 735a 0a66 696c 6573 4d6f  e_namesZ.filesMo
-00000e60: 7665 64da 0966 696c 655f 6e61 6d65 da0d  ved..file_name..
-00000e70: 7265 736f 7572 6365 5f70 6174 685a 1070  resource_pathZ.p
-00000e80: 795f 7265 736f 7572 6365 5f70 6174 68da  y_resource_path.
-00000e90: 0f72 6573 6f75 7263 655f 6d6f 6475 6c65  .resource_module
-00000ea0: 720d 0000 0072 0d00 0000 720e 0000 00da  r....r....r.....
-00000eb0: 1067 656e 6572 6174 654e 6577 4963 6f6e  .generateNewIcon
-00000ec0: 7319 0000 0073 d600 0000 0001 0602 0c01  s....s..........
-00000ed0: 0e01 0402 0a01 0401 0c02 0a01 0a02 0c01  ................
-00000ee0: 1e02 1a02 0e01 0a01 2c02 2c02 1e01 0801  ........,.,.....
-00000ef0: 1401 0802 1401 0801 1c02 0802 0a02 1a01  ................
-00000f00: 3001 1602 1a01 3001 1602 1a01 3001 1a02  0.....0.....0...
-00000f10: 0a02 1201 0802 0c01 0a02 1a01 1602 0e01  ................
-00000f20: 0a02 0e01 0202 1201 1201 2403 1201 0802  ..........$.....
-00000f30: 0c01 0a02 1a01 1602 0e01 0a02 0e01 0202  ................
-00000f40: 1201 1201 2403 1201 0802 0c01 0a02 1a01  ....$...........
-00000f50: 1602 0e01 0a02 0e01 0202 1201 1201 2404  ..............$.
-00000f60: 2003 0401 0402 0a02 0e01 0c02 0e01 0a02   ...............
-00000f70: 0401 0801 0c01 1802 0201 1a01 1201 2803  ..............(.
-00000f80: 0802 1a04 1a01 0e01 3c01 0c01 0c01 0c01  ........<.......
-00000f90: 0c02 0201 0c01 1a01 1001 1202 1a03 0605  ................
-00000fa0: 7a22 4e65 7749 636f 6e73 4765 6e65 7261  z"NewIconsGenera
-00000fb0: 746f 722e 6765 6e65 7261 7465 4e65 7749  tor.generateNewI
-00000fc0: 636f 6e73 6302 0000 0000 0000 0000 0000  consc...........
-00000fd0: 0005 0000 0006 0000 0043 0000 0073 8000  .........C...s..
-00000fe0: 0000 6401 a000 7401 6a02 7403 6a04 6402  ..d...t.j.t.j.d.
-00000ff0: 6403 8d02 a101 7d02 6404 7c02 9b00 6405  d.....}.d.|...d.
-00001000: 9d03 7d03 7405 a006 6406 7c03 a102 0100  ..}.t...d.|.....
-00001010: 7405 a007 a100 4400 5d2a 7d04 7c04 a008  t.....D.]*}.|...
-00001020: 6404 a101 7236 7c04 a009 6405 a101 7236  d...r6|...d...r6
-00001030: 7c04 7c03 6b03 7236 7405 a00a 7c04 a101  |.|.k.r6t...|...
-00001040: 0100 7136 740b a00c 7c03 6400 6407 8502  ..q6t...|.d.d...
-00001050: 1900 a101 7d01 740d 6408 8301 0100 6400  ....}.t.d.....d.
-00001060: 5300 2909 4e72 1400 0000 e908 0000 0029  S.).Nr.........)
-00001070: 01da 016b 5a11 5153 535f 5265 736f 7572  ...kZ.QSS_Resour
-00001080: 6365 735f 7263 5f72 2500 0000 7a13 5153  ces_rc_r%...z.QS
-00001090: 535f 5265 736f 7572 6365 735f 7263 2e70  S_Resources_rc.p
-000010a0: 79e9 fdff ffff 7a0f 7265 736f 7572 6365  y.....z.resource
-000010b0: 206c 6f61 6465 6429 0e72 2c00 0000 da06   loaded).r,.....
-000010c0: 7261 6e64 6f6d da07 6368 6f69 6365 73da  random..choices.
-000010d0: 0673 7472 696e 67da 0f61 7363 6969 5f6c  .string..ascii_l
-000010e0: 6f77 6572 6361 7365 7228 0000 00da 0672  owercaser(.....r
-000010f0: 656e 616d 6572 4900 0000 da0a 7374 6172  enamerI.....star
-00001100: 7473 7769 7468 da08 656e 6473 7769 7468  tswith..endswith
-00001110: da06 7265 6d6f 7665 da09 696d 706f 7274  ..remove..import
-00001120: 6c69 62da 0d69 6d70 6f72 745f 6d6f 6475  lib..import_modu
-00001130: 6c65 7236 0000 0029 0572 0a00 0000 7269  ler6...).r....ri
-00001140: 0000 005a 0b72 616e 646f 6d5f 6e61 6d65  ...Z.random_name
-00001150: 5a11 6e65 775f 7265 736f 7572 6365 5f66  Z.new_resource_f
-00001160: 696c 6572 5f00 0000 720d 0000 0072 0d00  iler_...r....r..
-00001170: 0000 720e 0000 00da 1072 656c 6f61 645f  ..r......reload_
-00001180: 7265 736f 7572 6365 73c1 0000 0073 1000  resources....s..
-00001190: 0000 0002 1601 0c03 0c03 0c01 1c01 0c03  ................
-000011a0: 1202 7a22 4e65 7749 636f 6e73 4765 6e65  ..z"NewIconsGene
-000011b0: 7261 746f 722e 7265 6c6f 6164 5f72 6573  rator.reload_res
-000011c0: 6f75 7263 6573 6302 0000 0000 0000 0000  ourcesc.........
-000011d0: 0000 001c 0000 000d 0000 0043 0000 0073  ...........C...s
-000011e0: ba05 0000 7400 8300 7d02 7401 6a02 a003  ....t...}.t.j...
-000011f0: 7404 a101 7d03 7401 6a02 a005 7c03 6401  t...}.t.j...|.d.
-00001200: a102 7d04 6700 7d05 6402 7d06 7c00 6a06  ..}.g.}.d.}.|.j.
-00001210: 6a07 4400 9005 5d82 7d07 7c02 a008 6403  j.D...].}.|...d.
-00001220: a101 7d08 7c00 6a09 7254 740a 6404 7c07  ..}.|.j.rTt.d.|.
-00001230: 6a0b 1700 8301 0100 740c 7c07 6405 8302  j.......t.|.d...
-00001240: 7280 7c07 6a0d 6406 6b03 7274 740e 7c07  r.|.j.d.k.rtt.|.
-00001250: 6a0d 8301 7d09 71f4 740e 7c07 6a0f 8301  j...}.q.t.|.j...
-00001260: 7d09 6e74 7c08 6407 6b02 72b0 7410 8300  }.nt|.d.k.r.t...
-00001270: 7d0a 7c0a 6a11 6406 6b02 72a4 740e 7c0a  }.|.j.d.k.r.t.|.
-00001280: 6a12 8301 7d09 71f4 740e 7c0a 6a11 8301  j...}.q.t.|.j...
-00001290: 7d09 6e44 7c08 6408 6b02 72e0 7413 8300  }.nD|.d.k.r.t...
-000012a0: 7d0a 7c0a 6a11 6406 6b02 72d4 740e 7c0a  }.|.j.d.k.r.t.|.
-000012b0: 6a12 8301 7d09 71f4 740e 7c0a 6a11 8301  j...}.q.t.|.j...
-000012c0: 7d09 6e14 7c00 6a09 7230 740a 6409 7c07  }.n.|.j.r0t.d.|.
-000012d0: 6a0b 8302 0100 7130 7414 7c09 640a 8302  j.....q0t.|.d...
-000012e0: 7d0b 7414 7c09 640b 8302 7d0c 7c09 a015  }.t.|.d...}.|...
-000012f0: 640c 6406 a102 7d0d 7401 6a02 a016 7401  d.d...}.t.j...t.
-00001300: 6a02 a005 7401 a017 a100 640d 7c0d 1700  j...t.....d.|...
-00001310: a102 a101 7d0e 7c00 6a09 9001 7246 740a  ....}.|.j...rFt.
-00001320: 640e 7c09 640f 8303 0100 7401 a018 7c04  d.|.d.....t...|.
-00001330: a101 4400 5d2c 5c03 7d0f 7d10 7d11 7c11  ..D.],\.}.}.}.|.
-00001340: 4400 5d1a 7d12 7c05 a019 7401 6a02 a005  D.].}.|...t.j...
-00001350: 7c0f 7c12 a102 a101 0100 9001 715e 9001  |.|.........q^..
-00001360: 7150 741a 7c05 8301 7d13 7c05 4400 9004  qPt.|...}.|.D...
-00001370: 5d26 7d14 741b 6a1c 7c14 6410 6411 6412  ]&}.t.j.|.d.d.d.
-00001380: 8d03 9001 8f00 7d15 7c15 a01d a100 7d16  ......}.|.....}.
-00001390: 7c16 a015 7c06 7c09 a102 7d17 740e a01e  |...|.|...}.t...
-000013a0: 7c17 a101 7d18 7401 6a02 a01f 7420 7c14  |...}.t.j...t |.
-000013b0: 8301 6a02 a101 a015 6413 6414 a102 7d19  ..j.....d.d...}.
-000013c0: 7401 6a02 a016 7401 6a02 a005 7c0e 7c19  t.j...t.j...|.|.
-000013d0: a102 a101 7d04 7401 6a02 a021 7c0e a101  ....}.t.j..!|...
-000013e0: 9002 730a 7401 a022 7c0e a101 0100 7401  ..s.t.."|.....t.
-000013f0: 6a02 a021 7c04 a101 9002 7228 5700 3500  j..!|.....r(W.5.
-00001400: 5100 5200 a300 9001 718a 6e36 7c02 a008  Q.R.....q.n6|...
-00001410: 6415 a101 6400 6b09 9002 725e 7c02 a008  d...d.k...r^|...
-00001420: 6415 a101 a015 640c 6406 a102 7c0d 6b02  d.....d.d...|.k.
-00001430: 9002 725e 5700 3500 5100 5200 a300 9001  ..r^W.5.Q.R.....
-00001440: 718a 7a12 7423 6a24 7c18 7c04 6416 8d02  q.z.t#j$|.|.d...
-00001450: 0100 5700 6e2c 0400 7425 6b0a 9002 729c  ..W.n,..t%k...r.
-00001460: 0100 7d1a 0100 7a0c 740a 7c1a 8301 0100  ..}...z.t.|.....
-00001470: 5700 3500 6400 7d1a 7e1a 5800 5900 6e02  W.5.d.}.~.X.Y.n.
-00001480: 5800 5700 3500 5100 5200 5800 741b 6a1c  X.W.5.Q.R.X.t.j.
-00001490: 7c14 6410 6411 6412 8d03 9001 8f5e 7d15  |.d.d.d......^}.
-000014a0: 7c15 a01d a100 7d16 7c16 a015 7c06 7c0b  |.....}.|...|.|.
-000014b0: a102 7d17 740e a01e 7c17 a101 7d18 7401  ..}.t...|...}.t.
-000014c0: 6a02 a01f 7420 7c14 8301 6a02 a101 a015  j...t |...j.....
-000014d0: 6413 6417 a102 7d19 7401 6a02 a016 7401  d.d...}.t.j...t.
-000014e0: 6a02 a005 7c0e 7c19 a102 a101 7d04 7401  j...|.|.....}.t.
-000014f0: 6a02 a021 7c0e a101 9003 7322 7401 a022  j..!|.....s"t.."
-00001500: 7c0e a101 0100 7401 6a02 a021 7c04 a101  |.....t.j..!|...
-00001510: 9003 7240 5700 3500 5100 5200 a300 9001  ..r@W.5.Q.R.....
-00001520: 718a 6e7e 7c02 a008 6415 a101 6400 6b09  q.n~|...d...d.k.
-00001530: 9003 72be 7c02 a008 6415 a101 a015 640c  ..r.|...d.....d.
-00001540: 6406 a102 7c0d 6b02 9003 72be 7401 6a02  d...|.k...r.t.j.
-00001550: a016 7401 6a02 a005 7401 a017 a100 6418  ..t.j...t.....d.
-00001560: a102 a101 7d1b 7401 6a02 a021 7401 6a02  ....}.t.j..!t.j.
-00001570: a005 7c1b 7c19 a102 a101 9003 72be 7426  ..|.|.......r.t&
-00001580: a027 7401 6a02 a005 7c1b 7c19 a102 7c0e  .'t.j...|.|...|.
-00001590: a102 0100 5700 3500 5100 5200 a300 9001  ....W.5.Q.R.....
-000015a0: 718a 7401 6a02 a016 7401 6a02 a005 7c0e  q.t.j...t.j...|.
-000015b0: 7c19 a102 a101 7d04 7a12 7423 6a24 7c18  |.....}.z.t#j$|.
-000015c0: 7c04 6416 8d02 0100 5700 6e2c 0400 7425  |.d.....W.n,..t%
-000015d0: 6b0a 9004 7212 0100 7d1a 0100 7a0c 740a  k...r...}...z.t.
-000015e0: 7c1a 8301 0100 5700 3500 6400 7d1a 7e1a  |.....W.5.d.}.~.
-000015f0: 5800 5900 6e02 5800 5700 3500 5100 5200  X.Y.n.X.W.5.Q.R.
-00001600: 5800 741b 6a1c 7c14 6410 6411 6412 8d03  X.t.j.|.d.d.d...
-00001610: 9001 8f5e 7d15 7c15 a01d a100 7d16 7c16  ...^}.|.....}.|.
-00001620: a015 7c06 7c0c a102 7d17 740e a01e 7c17  ..|.|...}.t...|.
-00001630: a101 7d18 7401 6a02 a01f 7420 7c14 8301  ..}.t.j...t |...
-00001640: 6a02 a101 a015 6413 6419 a102 7d19 7401  j.....d.d...}.t.
-00001650: 6a02 a016 7401 6a02 a005 7c0e 7c19 a102  j...t.j...|.|...
-00001660: a101 7d04 7401 6a02 a021 7c0e a101 9004  ..}.t.j..!|.....
-00001670: 7398 7401 a022 7c0e a101 0100 7401 6a02  s.t.."|.....t.j.
-00001680: a021 7c04 a101 9004 72b6 5700 3500 5100  .!|.....r.W.5.Q.
-00001690: 5200 a300 9001 718a 6e7e 7c02 a008 6415  R.....q.n~|...d.
-000016a0: a101 6400 6b09 9005 7234 7c02 a008 6415  ..d.k...r4|...d.
-000016b0: a101 a015 640c 6406 a102 7c0d 6b02 9005  ....d.d...|.k...
-000016c0: 7234 7401 6a02 a016 7401 6a02 a005 7401  r4t.j...t.j...t.
-000016d0: a017 a100 6418 a102 a101 7d1b 7401 6a02  ....d.....}.t.j.
-000016e0: a021 7401 6a02 a005 7c1b 7c19 a102 a101  .!t.j...|.|.....
-000016f0: 9005 7234 7426 a027 7401 6a02 a005 7c1b  ..r4t&.'t.j...|.
-00001700: 7c19 a102 7c0e a102 0100 5700 3500 5100  |...|.....W.5.Q.
-00001710: 5200 a300 9001 718a 7401 6a02 a016 7401  R.....q.t.j...t.
-00001720: 6a02 a005 7c0e 7c19 a102 a101 7d04 7a12  j...|.|.....}.z.
-00001730: 7423 6a24 7c18 7c04 6416 8d02 0100 5700  t#j$|.|.d.....W.
-00001740: 6e2c 0400 7425 6b0a 9005 7288 0100 7d1a  n,..t%k...r...}.
-00001750: 0100 7a0c 740a 7c1a 8301 0100 5700 3500  ..z.t.|.....W.5.
-00001760: 6400 7d1a 7e1a 5800 5900 6e02 5800 5700  d.}.~.X.Y.n.X.W.
-00001770: 3500 5100 5200 5800 7c01 a028 7429 7c05  5.Q.R.X.|..(t)|.
-00001780: a02a 7c14 a101 7c13 1b00 641a 1400 8301  .*|...|...d.....
-00001790: a101 0100 9001 718a 7130 6400 5300 291b  ......q.q0d.S.).
-000017a0: 4e72 0f00 0000 7210 0000 00da 0554 4845  Nr....r......THE
-000017b0: 4d45 7a13 4368 6563 6b69 6e67 2069 636f  MEz.Checking ico
-000017c0: 6e73 2066 6f72 20da 0a69 636f 6e73 436f  ns for ..iconsCo
-000017d0: 6c6f 7272 1400 0000 da05 4c49 4748 54da  lorr......LIGHT.
-000017e0: 0444 4152 4b7a 224e 6f20 6963 6f6e 7320  .DARKz"No icons 
-000017f0: 636f 6c6f 7220 7370 6563 6966 6965 6420  color specified 
-00001800: 666f 7220 7468 656d 6572 1100 0000 7212  for themer....r.
-00001810: 0000 0072 1300 0000 7215 0000 007a 2747  ...r....r....z'G
-00001820: 656e 6572 6174 696e 6720 6d69 7373 696e  enerating missin
-00001830: 6720 6963 6f6e 7320 666f 7220 796f 7572  g icons for your
-00001840: 2074 6865 6d65 7a1f 706c 6561 7365 2077   themez.please w
-00001850: 6169 742e 2054 6869 7320 6d61 7920 7461  ait. This may ta
-00001860: 6b65 206c 6f6e 6772 1c00 0000 721d 0000  ke longr....r...
-00001870: 0072 1e00 0000 7218 0000 0072 1900 0000  .r....r....r....
-00001880: 7217 0000 0072 2100 0000 721a 0000 0072  r....r!...r....r
-00001890: 1600 0000 721b 0000 0072 2200 0000 292b  ....r....r"...)+
-000018a0: 7227 0000 0072 2800 0000 7229 0000 0072  r'...r(...r)...r
-000018b0: 2a00 0000 722b 0000 0072 2c00 0000 da02  *...r+...r,.....
-000018c0: 7569 da06 7468 656d 6573 7234 0000 0072  ui..themesr4...r
-000018d0: 3500 0000 7236 0000 0072 4a00 0000 da07  5...r6...rJ.....
-000018e0: 6861 7361 7474 7272 7a00 0000 722f 0000  hasattrrz...r/..
-000018f0: 00da 0b61 6363 656e 7443 6f6c 6f72 da05  ...accentColor..
-00001900: 4c69 6768 74da 0b69 636f 6e73 5f63 6f6c  Light..icons_col
-00001910: 6f72 da0c 6163 6365 6e74 5f63 6f6c 6f72  or..accent_color
-00001920: da04 4461 726b 7230 0000 0072 3100 0000  ..Darkr0...r1...
-00001930: 7232 0000 0072 3300 0000 7237 0000 0072  r2...r3...r7...r
-00001940: 3800 0000 7239 0000 0072 3e00 0000 723f  8...r9...r>...r?
-00001950: 0000 0072 4000 0000 7241 0000 0072 3a00  ...r@...rA...r:.
-00001960: 0000 7202 0000 0072 3b00 0000 7242 0000  ..r....r;...rB..
-00001970: 0072 4300 0000 7244 0000 0072 4500 0000  .rC...rD...rE...
-00001980: 723c 0000 0072 3d00 0000 7246 0000 0072  r<...r=...rF...r
-00001990: 4700 0000 7248 0000 0029 1c72 0a00 0000  G...rH...).r....
-000019a0: 724f 0000 0072 5000 0000 722a 0000 0072  rO...rP...r*...r
-000019b0: 5100 0000 7252 0000 0072 5400 0000 da05  Q...rR...rT.....
-000019c0: 7468 656d 6572 7900 0000 7255 0000 005a  themery...rU...Z
-000019d0: 0d74 6865 6d65 5072 6f70 6572 7479 7256  .themePropertyrV
-000019e0: 0000 0072 5700 0000 7258 0000 0072 5900  ...rW...rX...rY.
-000019f0: 0000 725c 0000 0072 5d00 0000 725e 0000  ..r\...r]...r^..
-00001a00: 0072 5f00 0000 7260 0000 0072 4a00 0000  .r_...r`...rJ...
-00001a10: 7262 0000 0072 6300 0000 7264 0000 0072  rb...rc...rd...r
-00001a20: 6500 0000 7261 0000 0072 6600 0000 725a  e...ra...rf...rZ
-00001a30: 0000 0072 0d00 0000 720d 0000 0072 0e00  ...r....r....r..
-00001a40: 0000 724e 0000 00d3 0000 0073 bc00 0000  ..rN.......s....
-00001a50: 0001 0602 0c01 0e01 0402 0402 0e01 0a04  ................
-00001a60: 0601 0e03 0a01 0a01 0c02 0c02 0801 0601  ................
-00001a70: 0a01 0c02 0c02 0801 0601 0a01 0c02 0c03  ................
-00001a80: 0601 0c01 0202 0a01 0a02 0c02 1e02 0801  ................
-00001a90: 0c02 1401 0801 1c02 0801 0a02 1401 0802  ................
-00001aa0: 0c01 0a02 1a01 1602 0e01 0a02 0e01 1002  ................
-00001ab0: 2801 0e01 0202 1201 1201 2403 1401 0802  (.........$.....
-00001ac0: 0c01 0a02 1a01 1602 0e01 0a02 0e01 1002  ................
-00001ad0: 2802 1a02 1801 1601 0e02 1601 0202 1201  (...............
-00001ae0: 1201 2403 1401 0802 0c01 0a02 1a01 1602  ..$.............
-00001af0: 0e01 0a02 0e01 1002 2802 1a02 1801 1601  ........(.......
-00001b00: 0e02 1601 0201 1201 1201 2404 7a22 4e65  ..........$.z"Ne
-00001b10: 7749 636f 6e73 4765 6e65 7261 746f 722e  wIconsGenerator.
-00001b20: 6765 6e65 7261 7465 416c 6c49 636f 6e73  generateAllIcons
-00001b30: 2909 da08 5f5f 6e61 6d65 5f5f da0a 5f5f  )...__name__..__
-00001b40: 6d6f 6475 6c65 5f5f da0c 5f5f 7175 616c  module__..__qual
-00001b50: 6e61 6d65 5f5f da07 5f5f 646f 635f 5f72  name__..__doc__r
-00001b60: 0800 0000 726a 0000 0072 7800 0000 724e  ....rj...rx...rN
-00001b70: 0000 00da 0d5f 5f63 6c61 7373 6365 6c6c  .....__classcell
-00001b80: 5f5f 720d 0000 0072 0d00 0000 720b 0000  __r....r....r...
-00001b90: 0072 0e00 0000 7206 0000 0013 0000 0073  .r....r........s
-00001ba0: 0c00 0000 0801 0401 0c04 087f 0029 0812  .............)..
-00001bb0: 7206 0000 0029 1172 4300 0000 723e 0000  r....).rC...r>..
-00001bc0: 0072 2800 0000 da03 7379 7372 3c00 0000  .r(.....sysr<...
-00001bd0: 7276 0000 0072 6e00 0000 7270 0000 00da  rv...rn...rp....
-00001be0: 0c75 726c 6c69 622e 7061 7273 6572 0200  .urllib.parser..
-00001bf0: 0000 da07 7061 7468 6c69 6272 0300 0000  ....pathlibr....
-00001c00: da08 5f5f 6d61 696e 5f5f da0b 636f 6c6f  ..__main__..colo
-00001c10: 7273 7973 7465 6d72 2700 0000 7250 0000  rsystemr'...rP..
-00001c20: 0072 0600 0000 720d 0000 0072 0d00 0000  .r....r....r....
-00001c30: 720d 0000 0072 0e00 0000 da08 3c6d 6f64  r....r......<mod
-00001c40: 756c 653e 0100 0000 731a 0000 0008 0108  ule>....s.......
-00001c50: 0108 0108 0108 0108 0108 0108 010c 010c  ................
-00001c60: 0108 0408 0206 02                        .......
+00000090: 6405 6c0d 5400 6400 6401 6c0e 5a0e 6400  d.l.T.d.d.l.Z.d.
+000000a0: 6405 6c0f 5400 6510 8300 5a11 4700 6406  d.l.T.e...Z.G.d.
+000000b0: 6407 8400 6407 8302 5a12 6401 5300 2908  d...d...Z.d.S.).
+000000c0: e900 0000 004e 2901 da08 7572 6c70 6172  .....N)...urlpar
+000000d0: 7365 2901 da04 5061 7468 e901 0000 0029  se)...Path.....)
+000000e0: 01da 012a 6300 0000 0000 0000 0000 0000  ...*c...........
+000000f0: 0000 0000 0003 0000 0000 0000 0073 3800  .............s8.
+00000100: 0000 6500 5a01 6400 5a02 6401 5a03 8700  ..e.Z.d.Z.d.Z...
+00000110: 6601 6402 6403 8408 5a04 6404 6405 8400  f.d.d...Z.d.d...
+00000120: 5a05 6406 6407 8400 5a06 6408 6409 8400  Z.d.d...Z.d.d...
+00000130: 5a07 8700 0400 5a08 5300 290a da11 4e65  Z.....Z.S.)...Ne
+00000140: 7749 636f 6e73 4765 6e65 7261 746f 727a  wIconsGeneratorz
+00000150: 1f64 6f63 7374 7269 6e67 2066 6f72 204e  .docstring for N
+00000160: 6577 4963 6f6e 7347 656e 6572 6174 6f72  ewIconsGenerator
+00000170: 6302 0000 0000 0000 0000 0000 0002 0000  c...............
+00000180: 0003 0000 0003 0000 0073 1800 0000 7400  .........s....t.
+00000190: 7401 7c00 8302 a002 a100 0100 7c01 7c00  t.|.........|.|.
+000001a0: 5f03 6400 5300 2901 4e29 04da 0573 7570  _.d.S.).N)...sup
+000001b0: 6572 7206 0000 00da 085f 5f69 6e69 745f  err......__init_
+000001c0: 5fda 0361 7267 2902 da04 7365 6c66 7209  _..arg)...selfr.
+000001d0: 0000 00a9 01da 095f 5f63 6c61 7373 5f5f  .......__class__
+000001e0: a900 fa48 453a 5c53 7069 6e6e 2054 6173  ...HE:\Spinn Tas
+000001f0: 6b5c 3070 6173 735c 3070 6173 732d 6170  k\0pass\0pass-ap
+00000200: 702d 6d61 7374 6572 5c43 7573 746f 6d5f  p-master\Custom_
+00000210: 5769 6467 6574 735c 5173 735c 5376 6754  Widgets\Qss\SvgT
+00000220: 6f50 6e67 4963 6f6e 732e 7079 7208 0000  oPngIcons.pyr...
+00000230: 0017 0000 0073 0400 0000 0001 0e01 7a1a  .....s........z.
+00000240: 4e65 7749 636f 6e73 4765 6e65 7261 746f  NewIconsGenerato
+00000250: 722e 5f5f 696e 6974 5f5f 6302 0000 0000  r.__init__c.....
+00000260: 0000 0000 0000 0024 0000 000c 0000 0043  .......$.......C
+00000270: 0000 0073 7e07 0000 7400 8300 7d02 7401  ...s~...t...}.t.
+00000280: 6a02 a003 7404 a101 7d03 7401 6a02 a005  j...t...}.t.j...
+00000290: 7c03 6401 a102 7d04 6700 7d05 7406 a007  |.d...}.g.}.t...
+000002a0: 7c00 a101 7d06 6402 7d07 7408 7c06 6403  |...}.d.}.t.|.d.
+000002b0: 1900 8301 7d08 7409 7c08 6404 8302 7d09  ....}.t.|.d...}.
+000002c0: 7409 7c08 6405 8302 7d0a 7c08 a00a 6406  t.|.d...}.|...d.
+000002d0: 6407 a102 7d0b 7401 6a02 a00b 7401 6a02  d...}.t.j...t.j.
+000002e0: a005 7401 a00c a100 6408 7c0b 1700 a102  ..t.....d.|.....
+000002f0: a101 7d0c 7401 6a02 a00b 7401 6a02 a005  ..}.t.j...t.j...
+00000300: 7401 a00c a100 6409 a102 a101 7d0d 7c02  t.....d.....}.|.
+00000310: a00d 640a a101 6400 6b08 72da 7406 a007  ..d...d.k.r.t...
+00000320: 7c00 a101 7d0e 7401 6a02 a00b 7401 6a02  |...}.t.j...t.j.
+00000330: a005 7401 a00c a100 6408 7c0e 6403 1900  ..t.....d.|.d...
+00000340: a00a 6406 6407 a102 1700 a102 a101 7d0f  ..d.d.........}.
+00000350: 6e2c 7401 6a02 a00b 7401 6a02 a005 7401  n,t.j...t.j...t.
+00000360: a00c a100 6408 7c02 a00d 640a a101 a00a  ....d.|...d.....
+00000370: 6406 6407 a102 1700 a102 a101 7d0f 7c02  d.d.........}.|.
+00000380: a00d 640a a101 7c08 6b02 9007 736e 7c06  ..d...|.k...sn|.
+00000390: 6403 1900 6400 6b09 9007 726e 7c00 6a0e  d...d.k...rn|.j.
+000003a0: 9001 7248 740f 640b 7c02 a00d 640a a101  ..rHt.d.|...d...
+000003b0: 640c 7c08 8304 0100 740f 640d 8301 0100  d.|.....t.d.....
+000003c0: 7401 a010 7c04 a101 4400 5d2c 5c03 7d10  t...|...D.],\.}.
+000003d0: 7d11 7d12 7c12 4400 5d1a 7d13 7c05 a011  }.}.|.D.].}.|...
+000003e0: 7401 6a02 a005 7c10 7c13 a102 a101 0100  t.j...|.|.......
+000003f0: 9001 7160 9001 7152 7412 7c05 8301 7d14  ..q`..qRt.|...}.
+00000400: 7c05 4400 9001 5d26 7d15 7401 6a02 a013  |.D...]&}.t.j...
+00000410: 7414 7c15 8301 6a02 a101 a00a 640e 640f  t.|...j.....d.d.
+00000420: a102 7d16 7401 6a02 a015 7401 6a02 a005  ..}.t.j...t.j...
+00000430: 7c0d 7c16 a102 a101 9001 72f2 7401 6a02  |.|.......r.t.j.
+00000440: a015 7401 6a02 a005 7c0f 7c16 a102 a101  ..t.j...|.|.....
+00000450: 9001 73f2 7416 a017 7401 6a02 a005 7c0d  ..s.t...t.j...|.
+00000460: 7c16 a102 7c0f a102 0100 7401 6a02 a013  |...|.....t.j...
+00000470: 7414 7c15 8301 6a02 a101 a00a 640e 6410  t.|...j.....d.d.
+00000480: a102 7d16 7401 6a02 a015 7401 6a02 a005  ..}.t.j...t.j...
+00000490: 7c0d 7c16 a102 a101 9002 7252 7401 6a02  |.|.......rRt.j.
+000004a0: a015 7401 6a02 a005 7c0f 7c16 a102 a101  ..t.j...|.|.....
+000004b0: 9002 7352 7416 a017 7401 6a02 a005 7c0d  ..sRt...t.j...|.
+000004c0: 7c16 a102 7c0f a102 0100 7401 6a02 a013  |...|.....t.j...
+000004d0: 7414 7c15 8301 6a02 a101 a00a 640e 6411  t.|...j.....d.d.
+000004e0: a102 7d16 7401 6a02 a015 7401 6a02 a005  ..}.t.j...t.j...
+000004f0: 7c0d 7c16 a102 a101 9001 728c 7401 6a02  |.|.......r.t.j.
+00000500: a015 7401 6a02 a005 7c0f 7c16 a102 a101  ..t.j...|.|.....
+00000510: 9001 738c 7416 a017 7401 6a02 a005 7c0d  ..s.t...t.j...|.
+00000520: 7c16 a102 7c0f a102 0100 9001 718c 7c05  |...|.......q.|.
+00000530: 4400 9002 5d92 7d15 7418 6a19 7c15 6412  D...].}.t.j.|.d.
+00000540: 6413 6414 8d03 8fba 7d17 7c17 a01a a100  d.d.....}.|.....
+00000550: 7d18 7c18 a00a 7c07 7c08 a102 7d19 7408  }.|...|.|...}.t.
+00000560: a01b 7c19 a101 7d1a 7401 6a02 a013 7414  ..|...}.t.j...t.
+00000570: 7c15 8301 6a02 a101 a00a 640e 640f a102  |...j.....d.d...
+00000580: 7d16 7401 6a02 a00b 7401 6a02 a005 7c0c  }.t.j...t.j...|.
+00000590: 7c16 a102 a101 7d04 7401 6a02 a015 7c0c  |.....}.t.j...|.
+000005a0: a101 9003 7338 7401 a01c 7c0c a101 0100  ....s8t...|.....
+000005b0: 7401 6a02 a015 7c04 a101 9003 7386 7a12  t.j...|.....s.z.
+000005c0: 741d 6a1e 7c1a 7c04 6415 8d02 0100 5700  t.j.|.|.d.....W.
+000005d0: 6e2c 0400 741f 6b0a 9003 7284 0100 7d1b  n,..t.k...r...}.
+000005e0: 0100 7a0c 740f 7c1b 8301 0100 5700 3500  ..z.t.|.....W.5.
+000005f0: 6400 7d1b 7e1b 5800 5900 6e02 5800 5700  d.}.~.X.Y.n.X.W.
+00000600: 3500 5100 5200 5800 7418 6a19 7c15 6412  5.Q.R.X.t.j.|.d.
+00000610: 6413 6414 8d03 8fba 7d17 7c17 a01a a100  d.d.....}.|.....
+00000620: 7d18 7c18 a00a 7c07 7c09 a102 7d19 7408  }.|...|.|...}.t.
+00000630: a01b 7c19 a101 7d1a 7401 6a02 a013 7414  ..|...}.t.j...t.
+00000640: 7c15 8301 6a02 a101 a00a 640e 6410 a102  |...j.....d.d...
+00000650: 7d16 7401 6a02 a00b 7401 6a02 a005 7c0c  }.t.j...t.j...|.
+00000660: 7c16 a102 a101 7d04 7401 6a02 a015 7c0c  |.....}.t.j...|.
+00000670: a101 9004 7308 7401 a01c 7c0c a101 0100  ....s.t...|.....
+00000680: 7401 6a02 a015 7c04 a101 9004 7356 7a12  t.j...|.....sVz.
+00000690: 741d 6a1e 7c1a 7c04 6415 8d02 0100 5700  t.j.|.|.d.....W.
+000006a0: 6e2c 0400 741f 6b0a 9004 7254 0100 7d1b  n,..t.k...rT..}.
+000006b0: 0100 7a0c 740f 7c1b 8301 0100 5700 3500  ..z.t.|.....W.5.
+000006c0: 6400 7d1b 7e1b 5800 5900 6e02 5800 5700  d.}.~.X.Y.n.X.W.
+000006d0: 3500 5100 5200 5800 7418 6a19 7c15 6412  5.Q.R.X.t.j.|.d.
+000006e0: 6413 6414 8d03 8fba 7d17 7c17 a01a a100  d.d.....}.|.....
+000006f0: 7d18 7c18 a00a 7c07 7c0a a102 7d19 7408  }.|...|.|...}.t.
+00000700: a01b 7c19 a101 7d1a 7401 6a02 a013 7414  ..|...}.t.j...t.
+00000710: 7c15 8301 6a02 a101 a00a 640e 6411 a102  |...j.....d.d...
+00000720: 7d16 7401 6a02 a00b 7401 6a02 a005 7c0c  }.t.j...t.j...|.
+00000730: 7c16 a102 a101 7d04 7401 6a02 a015 7c0c  |.....}.t.j...|.
+00000740: a101 9004 73d8 7401 a01c 7c0c a101 0100  ....s.t...|.....
+00000750: 7401 6a02 a015 7c04 a101 9005 7326 7a12  t.j...|.....s&z.
+00000760: 741d 6a1e 7c1a 7c04 6415 8d02 0100 5700  t.j.|.|.d.....W.
+00000770: 6e2c 0400 741f 6b0a 9005 7224 0100 7d1b  n,..t.k...r$..}.
+00000780: 0100 7a0c 740f 7c1b 8301 0100 5700 3500  ..z.t.|.....W.5.
+00000790: 6400 7d1b 7e1b 5800 5900 6e02 5800 5700  d.}.~.X.Y.n.X.W.
+000007a0: 3500 5100 5200 5800 7c01 a020 7421 7c05  5.Q.R.X.|.. t!|.
+000007b0: a022 7c15 a101 7c14 1b00 6416 1400 8301  ."|...|...d.....
+000007c0: a101 0100 9002 71ba 7c0c 7d1c 7c0d 7d1d  ......q.|.}.|.}.
+000007d0: 7401 a023 7c1c a101 7d1e 7401 6a02 a015  t..#|...}.t.j...
+000007e0: 7c0d a101 9005 737c 7401 a01c 7c0d a101  |.....s|t...|...
+000007f0: 0100 6e18 7401 6a02 a015 7c0d a101 9005  ..n.t.j...|.....
+00000800: 7394 7401 a01c 7c0d a101 0100 6417 7d1f  s.t...|.....d.}.
+00000810: 7c1e 4400 5d9e 7d20 7401 6a24 6418 6b02  |.D.].} t.j$d.k.
+00000820: 9005 72c4 7416 a025 7401 6a02 a005 7c1c  ..r.t..%t.j...|.
+00000830: 7c20 a102 7c1d a102 0100 6e56 7a1a 7416  | ..|.....nVz.t.
+00000840: a017 7401 6a02 a005 7c1c 7c20 a102 7c1d  ..t.j...|.| ..|.
+00000850: a102 0100 5700 6e3a 0400 741f 6b0a 9006  ....W.n:..t.k...
+00000860: 7218 0100 7d1b 0100 7a1a 7416 a025 7401  r...}...z.t..%t.
+00000870: 6a02 a005 7c1c 7c20 a102 7c1d a102 0100  j...|.| ..|.....
+00000880: 5700 3500 6400 7d1b 7e1b 5800 5900 6e02  W.5.d.}.~.X.Y.n.
+00000890: 5800 7c1f 6419 3700 7d1f 7c01 a020 7421  X.|.d.7.}.|.. t!
+000008a0: 7c1f 7c14 1b00 6416 1400 8301 a101 0100  |.|...d.........
+000008b0: 9005 719c 7401 6a02 a00b 7401 6a02 a005  ..q.t.j...t.j...
+000008c0: 7401 a00c a100 641a a102 a101 7d21 7401  t.....d.....}!t.
+000008d0: 6a02 a015 7c21 a101 9006 73a0 7416 a025  j...|!....s.t..%
+000008e0: 7401 6a02 a00b 7401 6a02 a005 7401 6a02  t.j...t.j...t.j.
+000008f0: a003 7404 a101 641b a102 a101 7401 6a02  ..t...d.....t.j.
+00000900: a00b 7401 6a02 a005 7401 a00c a100 641c  ..t.j...t.....d.
+00000910: a102 a101 a102 0100 7c21 a00a 641d 641e  ........|!..d.d.
+00000920: a102 7d22 7c22 a00a 6408 6407 a102 7d22  ..}"|"..d.d...}"
+00000930: 7c22 a00a 641f 6407 a102 7d22 7c22 a00a  |"..d.d...}"|"..
+00000940: 6420 6421 a102 7d22 7a6a 7c02 a026 640a  d d!..}"zj|..&d.
+00000950: 7c08 a102 0100 7427 6a28 6422 6b02 9007  |.....t'j(d"k...
+00000960: 7206 7401 a029 6423 7c21 1700 6424 1700  r.t..)d#|!..d$..
+00000970: 7c22 1700 6425 1700 a101 0100 6e26 7427  |"..d%......n&t'
+00000980: 6a28 6426 6b02 9007 722c 7401 a029 6427  j(d&k...r,t..)d'
+00000990: 7c21 1700 6424 1700 7c22 1700 6425 1700  |!..d$..|"..d%..
+000009a0: a101 0100 7c02 a026 640a 7c08 a102 0100  ....|..&d.|.....
+000009b0: 5700 6e2c 0400 741f 6b0a 9007 7266 0100  W.n,..t.k...rf..
+000009c0: 7d1b 0100 7a0c 740f 6428 8301 0100 5700  }...z.t.d(....W.
+000009d0: 3500 6400 7d1b 7e1b 5800 5900 6e02 5800  5.d.}.~.X.Y.n.X.
+000009e0: 6421 7d23 6e0c 742a a02b 7c00 7c01 a102  d!}#n.t*.+|.|...
+000009f0: 0100 6400 5300 2929 4efa 1269 636f 6e73  ..d.S.))N..icons
+00000a00: 2f6f 7269 6769 6e61 6c5f 7376 67fa 0423  /original_svg..#
+00000a10: 6666 667a 0b69 636f 6e73 2d63 6f6c 6f72  fffz.icons-color
+00000a20: e700 0000 0000 00f8 3fe7 0000 0000 0000  ........?.......
+00000a30: e03f fa01 23da 00fa 0451 5353 2ffa 0951  .?..#....QSS/..Q
+00000a40: 5353 2f49 636f 6e73 fa0b 4943 4f4e 532d  SS/Icons..ICONS-
+00000a50: 434f 4c4f 527a 1443 7572 7265 6e74 2069  COLORz.Current i
+00000a60: 636f 6e73 2063 6f6c 6f72 207a 0f4e 6577  cons color z.New
+00000a70: 2069 636f 6e73 2063 6f6c 6f72 7a40 4765   icons colorz@Ge
+00000a80: 6e65 7261 7469 6e67 2069 636f 6e73 2066  nerating icons f
+00000a90: 6f72 2079 6f75 7220 7468 656d 652c 2070  or your theme, p
+00000aa0: 6c65 6173 6520 7761 6974 2e20 5468 6973  lease wait. This
+00000ab0: 206d 6179 2074 616b 6520 6c6f 6e67 fa04   may take long..
+00000ac0: 2e73 7667 fa04 2e70 6e67 fa0a 5f66 6f63  .svg...png.._foc
+00000ad0: 7573 2e70 6e67 fa0d 5f64 6973 6162 6c65  us.png.._disable
+00000ae0: 642e 706e 67fa 0575 7466 2d38 da06 6967  d.png..utf-8..ig
+00000af0: 6e6f 7265 a902 da08 656e 636f 6469 6e67  nore....encoding
+00000b00: da06 6572 726f 7273 a902 5a0a 6279 7465  ..errors..Z.byte
+00000b10: 7374 7269 6e67 5a08 7772 6974 655f 746f  stringZ.write_to
+00000b20: e964 0000 0072 0100 0000 da02 6e74 7204  .d...r......ntr.
+00000b30: 0000 007a 1551 5353 2f51 5353 5f52 6573  ...z.QSS/QSS_Res
+00000b40: 6f75 7263 6573 2e71 7263 7a11 5153 535f  ources.qrcz.QSS_
+00000b50: 5265 736f 7572 6365 732e 7172 63da 0351  Resources.qrc..Q
+00000b60: 5353 7a04 2e71 7263 fa03 2e70 797a 0451  SSz..qrc...pyz.Q
+00000b70: 5353 5c5a 0d51 5353 5f52 6573 6f75 7263  SS\Z.QSS_Resourc
+00000b80: 6573 5a10 5153 535f 5265 736f 7572 6365  esZ.QSS_Resource
+00000b90: 735f 7263 da05 5079 5174 357a 0870 7972  s_rc..PyQt5z.pyr
+00000ba0: 6363 3520 227a 0622 202d 6f20 22fa 0122  cc5 "z." -o ".."
+00000bb0: da07 5079 5369 6465 327a 0d70 7973 6964  ..PySide2z.pysid
+00000bc0: 6532 2d72 6363 2022 7a24 6572 726f 7220  e2-rcc "z$error 
+00000bd0: 7768 696c 6520 636f 6e76 6572 7469 6e67  while converting
+00000be0: 2072 6573 6f75 7263 6520 6669 6c65 292c   resource file),
+00000bf0: da09 5153 6574 7469 6e67 73da 026f 73da  ..QSettings..os.
+00000c00: 0470 6174 68da 0764 6972 6e61 6d65 da08  .path..dirname..
+00000c10: 5f5f 6669 6c65 5f5f da04 6a6f 696e da13  __file__..join..
+00000c20: 4372 6561 7465 436f 6c6f 7256 6172 6961  CreateColorVaria
+00000c30: 626c 65da 1367 6574 4375 7272 656e 7454  ble..getCurrentT
+00000c40: 6865 6d65 496e 666f da03 7374 72da 1061  hemeInfo..str..a
+00000c50: 646a 7573 745f 6c69 6768 746e 6573 73da  djust_lightness.
+00000c60: 0772 6570 6c61 6365 da07 6162 7370 6174  .replace..abspat
+00000c70: 68da 0667 6574 6377 64da 0576 616c 7565  h..getcwd..value
+00000c80: da15 7368 6f77 4375 7374 6f6d 5769 6467  ..showCustomWidg
+00000c90: 6574 734c 6f67 73da 0570 7269 6e74 da04  etsLogs..print..
+00000ca0: 7761 6c6b da06 6170 7065 6e64 da03 6c65  walk..append..le
+00000cb0: 6eda 0862 6173 656e 616d 6572 0200 0000  n..basenamer....
+00000cc0: da06 6578 6973 7473 da06 7368 7574 696c  ..exists..shutil
+00000cd0: da04 6d6f 7665 da06 636f 6465 6373 da04  ..move..codecs..
+00000ce0: 6f70 656e da04 7265 6164 da06 656e 636f  open..read..enco
+00000cf0: 6465 da08 6d61 6b65 6469 7273 da08 6361  de..makedirs..ca
+00000d00: 6972 6f73 7667 da07 7376 6732 706e 67da  irosvg..svg2png.
+00000d10: 0945 7863 6570 7469 6f6e da04 656d 6974  .Exception..emit
+00000d20: da03 696e 74da 0569 6e64 6578 da07 6c69  ..int..index..li
+00000d30: 7374 6469 72da 046e 616d 65da 0463 6f70  stdir..name..cop
+00000d40: 79da 0873 6574 5661 6c75 65da 0471 7470  y..setValue..qtp
+00000d50: 79da 0841 5049 5f4e 414d 45da 0673 7973  y..API_NAME..sys
+00000d60: 7465 6d72 0600 0000 da10 6765 6e65 7261  temr......genera
+00000d70: 7465 416c 6c49 636f 6e73 2924 720a 0000  teAllIcons)$r...
+00000d80: 00da 1170 726f 6772 6573 735f 6361 6c6c  ...progress_call
+00000d90: 6261 636b da08 7365 7474 696e 6773 722c  back..settingsr,
+00000da0: 0000 00da 0866 696c 656e 616d 65da 0d6c  .....filename..l
+00000db0: 6973 745f 6f66 5f66 696c 6573 da05 636f  ist_of_files..co
+00000dc0: 6c6f 72da 0973 7667 5f63 6f6c 6f72 da0c  lor..svg_color..
+00000dd0: 6e6f 726d 616c 5f63 6f6c 6f72 da0d 666f  normal_color..fo
+00000de0: 6375 7365 645f 636f 6c6f 72da 0e64 6973  cused_color..dis
+00000df0: 6162 6c65 645f 636f 6c6f 72da 0f69 636f  abled_color..ico
+00000e00: 6e73 466f 6c64 6572 4e61 6d65 da0b 6963  nsFolderName..ic
+00000e10: 6f6e 7346 6f6c 6465 72da 0e6f 6c64 4963  onsFolder..oldIc
+00000e20: 6f6e 7346 6f6c 6465 72da 0d76 6172 6961  onsFolder..varia
+00000e30: 626c 6573 4669 6c65 5a19 6f6c 6449 636f  blesFileZ.oldIco
+00000e40: 6e73 4465 7374 696e 6174 696f 6e46 6f6c  nsDestinationFol
+00000e50: 6465 72da 0472 6f6f 74da 0464 6972 73da  der..root..dirs.
+00000e60: 0566 696c 6573 da04 6669 6c65 da0a 746f  .files..file..to
+00000e70: 7461 6c49 636f 6e73 724c 0000 00da 066e  talIconsrL.....n
+00000e80: 616d 655f 32da 0166 da07 636f 6e74 656e  ame_2..f..conten
+00000e90: 74da 066e 6577 5356 47da 086e 6577 4279  t..newSVG..newBy
+00000ea0: 7465 73da 0165 5a0a 736f 7572 6365 5f64  tes..eZ.source_d
+00000eb0: 6972 5a0a 7461 7267 6574 5f64 6972 5a0a  irZ.target_dirZ.
+00000ec0: 6669 6c65 5f6e 616d 6573 5a0a 6669 6c65  file_namesZ.file
+00000ed0: 734d 6f76 6564 da09 6669 6c65 5f6e 616d  sMoved..file_nam
+00000ee0: 65da 0d72 6573 6f75 7263 655f 7061 7468  e..resource_path
+00000ef0: 5a10 7079 5f72 6573 6f75 7263 655f 7061  Z.py_resource_pa
+00000f00: 7468 da0f 7265 736f 7572 6365 5f6d 6f64  th..resource_mod
+00000f10: 756c 6572 0d00 0000 720d 0000 0072 0e00  uler....r....r..
+00000f20: 0000 da10 6765 6e65 7261 7465 4e65 7749  ....generateNewI
+00000f30: 636f 6e73 1b00 0000 73dc 0000 0000 0106  cons....s.......
+00000f40: 020c 010e 0104 020a 0104 010c 020a 010a  ................
+00000f50: 020c 011e 021a 020e 010a 012c 022c 021e  ...........,.,..
+00000f60: 0108 0114 0108 0214 0108 011c 0208 020a  ................
+00000f70: 021a 0130 0116 021a 0130 0116 021a 0130  ...0.....0.....0
+00000f80: 011a 020a 0212 0108 020c 010a 021a 0116  ................
+00000f90: 020e 010a 020e 0102 0212 0112 0124 0312  .............$..
+00000fa0: 0108 020c 010a 021a 0116 020e 010a 020e  ................
+00000fb0: 0102 0212 0112 0124 0312 0108 020c 010a  .......$........
+00000fc0: 021a 0116 020e 010a 020e 0102 0212 0112  ................
+00000fd0: 0124 0420 0304 0104 020a 020e 010c 020e  .$. ............
+00000fe0: 010a 0204 0108 010c 0118 0202 011a 0112  ................
+00000ff0: 0128 0308 021a 041a 010e 013c 010c 010c  .(.........<....
+00001000: 010c 010c 0202 010c 010c 011c 010c 011a  ................
+00001010: 0110 0112 021a 0306 057a 224e 6577 4963  .........z"NewIc
+00001020: 6f6e 7347 656e 6572 6174 6f72 2e67 656e  onsGenerator.gen
+00001030: 6572 6174 654e 6577 4963 6f6e 7363 0200  erateNewIconsc..
+00001040: 0000 0000 0000 0000 0000 0500 0000 0600  ................
+00001050: 0000 4300 0000 7380 0000 0064 01a0 0074  ..C...s....d...t
+00001060: 016a 0274 036a 0464 0264 038d 02a1 017d  .j.t.j.d.d.....}
+00001070: 0264 047c 029b 0064 059d 037d 0374 05a0  .d.|...d...}.t..
+00001080: 0664 067c 03a1 0201 0074 05a0 07a1 0044  .d.|.....t.....D
+00001090: 005d 2a7d 047c 04a0 0864 04a1 0172 367c  .]*}.|...d...r6|
+000010a0: 04a0 0964 05a1 0172 367c 047c 036b 0372  ...d...r6|.|.k.r
+000010b0: 3674 05a0 0a7c 04a1 0101 0071 3674 0ba0  6t...|.....q6t..
+000010c0: 0c7c 0364 0064 0785 0219 00a1 017d 0174  .|.d.d.......}.t
+000010d0: 0d64 0883 0101 0064 0053 0029 094e 7214  .d.....d.S.).Nr.
+000010e0: 0000 00e9 0800 0000 2901 da01 6b5a 1151  ........)...kZ.Q
+000010f0: 5353 5f52 6573 6f75 7263 6573 5f72 635f  SS_Resources_rc_
+00001100: 7225 0000 007a 1351 5353 5f52 6573 6f75  r%...z.QSS_Resou
+00001110: 7263 6573 5f72 632e 7079 e9fd ffff ff7a  rces_rc.py.....z
+00001120: 0f72 6573 6f75 7263 6520 6c6f 6164 6564  .resource loaded
+00001130: 290e 722e 0000 00da 0672 616e 646f 6dda  ).r......random.
+00001140: 0763 686f 6963 6573 da06 7374 7269 6e67  .choices..string
+00001150: da0f 6173 6369 695f 6c6f 7765 7263 6173  ..ascii_lowercas
+00001160: 6572 2a00 0000 da06 7265 6e61 6d65 724b  er*.....renamerK
+00001170: 0000 00da 0a73 7461 7274 7377 6974 68da  .....startswith.
+00001180: 0865 6e64 7377 6974 68da 0672 656d 6f76  .endswith..remov
+00001190: 65da 0969 6d70 6f72 746c 6962 da0d 696d  e..importlib..im
+000011a0: 706f 7274 5f6d 6f64 756c 6572 3800 0000  port_moduler8...
+000011b0: 2905 720a 0000 0072 6d00 0000 5a0b 7261  ).r....rm...Z.ra
+000011c0: 6e64 6f6d 5f6e 616d 655a 116e 6577 5f72  ndom_nameZ.new_r
+000011d0: 6573 6f75 7263 655f 6669 6c65 7263 0000  esource_filerc..
+000011e0: 0072 0d00 0000 720d 0000 0072 0e00 0000  .r....r....r....
+000011f0: da10 7265 6c6f 6164 5f72 6573 6f75 7263  ..reload_resourc
+00001200: 6573 c600 0000 7310 0000 0000 0216 010c  es....s.........
+00001210: 030c 030c 011c 010c 0312 027a 224e 6577  ...........z"New
+00001220: 4963 6f6e 7347 656e 6572 6174 6f72 2e72  IconsGenerator.r
+00001230: 656c 6f61 645f 7265 736f 7572 6365 7363  eload_resourcesc
+00001240: 0200 0000 0000 0000 0000 0000 1c00 0000  ................
+00001250: 0d00 0000 4300 0000 73ba 0500 0074 0083  ....C...s....t..
+00001260: 007d 0274 016a 02a0 0374 04a1 017d 0374  .}.t.j...t...}.t
+00001270: 016a 02a0 057c 0364 01a1 027d 0467 007d  .j...|.d...}.g.}
+00001280: 0564 027d 067c 006a 066a 0744 0090 055d  .d.}.|.j.j.D...]
+00001290: 827d 077c 02a0 0864 03a1 017d 087c 006a  .}.|...d...}.|.j
+000012a0: 0972 5474 0a64 047c 076a 0b17 0083 0101  .rTt.d.|.j......
+000012b0: 0074 0c7c 0764 0583 0272 807c 076a 0d64  .t.|.d...r.|.j.d
+000012c0: 066b 0372 7474 0e7c 076a 0d83 017d 0971  .k.rtt.|.j...}.q
+000012d0: f474 0e7c 076a 0f83 017d 096e 747c 0864  .t.|.j...}.nt|.d
+000012e0: 076b 0272 b074 1083 007d 0a7c 0a6a 1164  .k.r.t...}.|.j.d
+000012f0: 066b 0272 a474 0e7c 0a6a 1283 017d 0971  .k.r.t.|.j...}.q
+00001300: f474 0e7c 0a6a 1183 017d 096e 447c 0864  .t.|.j...}.nD|.d
+00001310: 086b 0272 e074 1383 007d 0a7c 0a6a 1164  .k.r.t...}.|.j.d
+00001320: 066b 0272 d474 0e7c 0a6a 1283 017d 0971  .k.r.t.|.j...}.q
+00001330: f474 0e7c 0a6a 1183 017d 096e 147c 006a  .t.|.j...}.n.|.j
+00001340: 0972 3074 0a64 097c 076a 0b83 0201 0071  .r0t.d.|.j.....q
+00001350: 3074 147c 0964 0a83 027d 0b74 147c 0964  0t.|.d...}.t.|.d
+00001360: 0b83 027d 0c7c 09a0 1564 0c64 06a1 027d  ...}.|...d.d...}
+00001370: 0d74 016a 02a0 1674 016a 02a0 0574 01a0  .t.j...t.j...t..
+00001380: 17a1 0064 0d7c 0d17 00a1 02a1 017d 0e7c  ...d.|.......}.|
+00001390: 006a 0990 0172 4674 0a64 0e7c 0964 0f83  .j...rFt.d.|.d..
+000013a0: 0301 0074 01a0 187c 04a1 0144 005d 2c5c  ...t...|...D.],\
+000013b0: 037d 0f7d 107d 117c 1144 005d 1a7d 127c  .}.}.}.|.D.].}.|
+000013c0: 05a0 1974 016a 02a0 057c 0f7c 12a1 02a1  ...t.j...|.|....
+000013d0: 0101 0090 0171 5e90 0171 5074 1a7c 0583  .....q^..qPt.|..
+000013e0: 017d 137c 0544 0090 045d 267d 1474 1b6a  .}.|.D...]&}.t.j
+000013f0: 1c7c 1464 1064 1164 128d 0390 018f 007d  .|.d.d.d.......}
+00001400: 157c 15a0 1da1 007d 167c 16a0 157c 067c  .|.....}.|...|.|
+00001410: 09a1 027d 1774 0ea0 1e7c 17a1 017d 1874  ...}.t...|...}.t
+00001420: 016a 02a0 1f74 207c 1483 016a 02a1 01a0  .j...t |...j....
+00001430: 1564 1364 14a1 027d 1974 016a 02a0 1674  .d.d...}.t.j...t
+00001440: 016a 02a0 057c 0e7c 19a1 02a1 017d 0474  .j...|.|.....}.t
+00001450: 016a 02a0 217c 0ea1 0190 0273 0a74 01a0  .j..!|.....s.t..
+00001460: 227c 0ea1 0101 0074 016a 02a0 217c 04a1  "|.....t.j..!|..
+00001470: 0190 0272 2857 0035 0051 0052 00a3 0090  ...r(W.5.Q.R....
+00001480: 0171 8a6e 367c 02a0 0864 15a1 0164 006b  .q.n6|...d...d.k
+00001490: 0990 0272 5e7c 02a0 0864 15a1 01a0 1564  ...r^|...d.....d
+000014a0: 0c64 06a1 027c 0d6b 0290 0272 5e57 0035  .d...|.k...r^W.5
+000014b0: 0051 0052 00a3 0090 0171 8a7a 1274 236a  .Q.R.....q.z.t#j
+000014c0: 247c 187c 0464 168d 0201 0057 006e 2c04  $|.|.d.....W.n,.
+000014d0: 0074 256b 0a90 0272 9c01 007d 1a01 007a  .t%k...r...}...z
+000014e0: 0c74 0a7c 1a83 0101 0057 0035 0064 007d  .t.|.....W.5.d.}
+000014f0: 1a7e 1a58 0059 006e 0258 0057 0035 0051  .~.X.Y.n.X.W.5.Q
+00001500: 0052 0058 0074 1b6a 1c7c 1464 1064 1164  .R.X.t.j.|.d.d.d
+00001510: 128d 0390 018f 5e7d 157c 15a0 1da1 007d  ......^}.|.....}
+00001520: 167c 16a0 157c 067c 0ba1 027d 1774 0ea0  .|...|.|...}.t..
+00001530: 1e7c 17a1 017d 1874 016a 02a0 1f74 207c  .|...}.t.j...t |
+00001540: 1483 016a 02a1 01a0 1564 1364 17a1 027d  ...j.....d.d...}
+00001550: 1974 016a 02a0 1674 016a 02a0 057c 0e7c  .t.j...t.j...|.|
+00001560: 19a1 02a1 017d 0474 016a 02a0 217c 0ea1  .....}.t.j..!|..
+00001570: 0190 0373 2274 01a0 227c 0ea1 0101 0074  ...s"t.."|.....t
+00001580: 016a 02a0 217c 04a1 0190 0372 4057 0035  .j..!|.....r@W.5
+00001590: 0051 0052 00a3 0090 0171 8a6e 7e7c 02a0  .Q.R.....q.n~|..
+000015a0: 0864 15a1 0164 006b 0990 0372 be7c 02a0  .d...d.k...r.|..
+000015b0: 0864 15a1 01a0 1564 0c64 06a1 027c 0d6b  .d.....d.d...|.k
+000015c0: 0290 0372 be74 016a 02a0 1674 016a 02a0  ...r.t.j...t.j..
+000015d0: 0574 01a0 17a1 0064 18a1 02a1 017d 1b74  .t.....d.....}.t
+000015e0: 016a 02a0 2174 016a 02a0 057c 1b7c 19a1  .j..!t.j...|.|..
+000015f0: 02a1 0190 0372 be74 26a0 2774 016a 02a0  .....r.t&.'t.j..
+00001600: 057c 1b7c 19a1 027c 0ea1 0201 0057 0035  .|.|...|.....W.5
+00001610: 0051 0052 00a3 0090 0171 8a74 016a 02a0  .Q.R.....q.t.j..
+00001620: 1674 016a 02a0 057c 0e7c 19a1 02a1 017d  .t.j...|.|.....}
+00001630: 047a 1274 236a 247c 187c 0464 168d 0201  .z.t#j$|.|.d....
+00001640: 0057 006e 2c04 0074 256b 0a90 0472 1201  .W.n,..t%k...r..
+00001650: 007d 1a01 007a 0c74 0a7c 1a83 0101 0057  .}...z.t.|.....W
+00001660: 0035 0064 007d 1a7e 1a58 0059 006e 0258  .5.d.}.~.X.Y.n.X
+00001670: 0057 0035 0051 0052 0058 0074 1b6a 1c7c  .W.5.Q.R.X.t.j.|
+00001680: 1464 1064 1164 128d 0390 018f 5e7d 157c  .d.d.d......^}.|
+00001690: 15a0 1da1 007d 167c 16a0 157c 067c 0ca1  .....}.|...|.|..
+000016a0: 027d 1774 0ea0 1e7c 17a1 017d 1874 016a  .}.t...|...}.t.j
+000016b0: 02a0 1f74 207c 1483 016a 02a1 01a0 1564  ...t |...j.....d
+000016c0: 1364 19a1 027d 1974 016a 02a0 1674 016a  .d...}.t.j...t.j
+000016d0: 02a0 057c 0e7c 19a1 02a1 017d 0474 016a  ...|.|.....}.t.j
+000016e0: 02a0 217c 0ea1 0190 0473 9874 01a0 227c  ..!|.....s.t.."|
+000016f0: 0ea1 0101 0074 016a 02a0 217c 04a1 0190  .....t.j..!|....
+00001700: 0472 b657 0035 0051 0052 00a3 0090 0171  .r.W.5.Q.R.....q
+00001710: 8a6e 7e7c 02a0 0864 15a1 0164 006b 0990  .n~|...d...d.k..
+00001720: 0572 347c 02a0 0864 15a1 01a0 1564 0c64  .r4|...d.....d.d
+00001730: 06a1 027c 0d6b 0290 0572 3474 016a 02a0  ...|.k...r4t.j..
+00001740: 1674 016a 02a0 0574 01a0 17a1 0064 18a1  .t.j...t.....d..
+00001750: 02a1 017d 1b74 016a 02a0 2174 016a 02a0  ...}.t.j..!t.j..
+00001760: 057c 1b7c 19a1 02a1 0190 0572 3474 26a0  .|.|.......r4t&.
+00001770: 2774 016a 02a0 057c 1b7c 19a1 027c 0ea1  't.j...|.|...|..
+00001780: 0201 0057 0035 0051 0052 00a3 0090 0171  ...W.5.Q.R.....q
+00001790: 8a74 016a 02a0 1674 016a 02a0 057c 0e7c  .t.j...t.j...|.|
+000017a0: 19a1 02a1 017d 047a 1274 236a 247c 187c  .....}.z.t#j$|.|
+000017b0: 0464 168d 0201 0057 006e 2c04 0074 256b  .d.....W.n,..t%k
+000017c0: 0a90 0572 8801 007d 1a01 007a 0c74 0a7c  ...r...}...z.t.|
+000017d0: 1a83 0101 0057 0035 0064 007d 1a7e 1a58  .....W.5.d.}.~.X
+000017e0: 0059 006e 0258 0057 0035 0051 0052 0058  .Y.n.X.W.5.Q.R.X
+000017f0: 007c 01a0 2874 297c 05a0 2a7c 14a1 017c  .|..(t)|..*|...|
+00001800: 131b 0064 1a14 0083 01a1 0101 0090 0171  ...d...........q
+00001810: 8a71 3064 0053 0029 1b4e 720f 0000 0072  .q0d.S.).Nr....r
+00001820: 1000 0000 da05 5448 454d 457a 1343 6865  ......THEMEz.Che
+00001830: 636b 696e 6720 6963 6f6e 7320 666f 7220  cking icons for 
+00001840: da0a 6963 6f6e 7343 6f6c 6f72 7214 0000  ..iconsColorr...
+00001850: 00da 054c 4947 4854 da04 4441 524b 7a22  ...LIGHT..DARKz"
+00001860: 4e6f 2069 636f 6e73 2063 6f6c 6f72 2073  No icons color s
+00001870: 7065 6369 6669 6564 2066 6f72 2074 6865  pecified for the
+00001880: 6d65 7211 0000 0072 1200 0000 7213 0000  mer....r....r...
+00001890: 0072 1500 0000 7a27 4765 6e65 7261 7469  .r....z'Generati
+000018a0: 6e67 206d 6973 7369 6e67 2069 636f 6e73  ng missing icons
+000018b0: 2066 6f72 2079 6f75 7220 7468 656d 657a   for your themez
+000018c0: 1f70 6c65 6173 6520 7761 6974 2e20 5468  .please wait. Th
+000018d0: 6973 206d 6179 2074 616b 6520 6c6f 6e67  is may take long
+000018e0: 721c 0000 0072 1d00 0000 721e 0000 0072  r....r....r....r
+000018f0: 1800 0000 7219 0000 0072 1700 0000 7221  ....r....r....r!
+00001900: 0000 0072 1a00 0000 7216 0000 0072 1b00  ...r....r....r..
+00001910: 0000 7222 0000 0029 2b72 2900 0000 722a  ..r"...)+r)...r*
+00001920: 0000 0072 2b00 0000 722c 0000 0072 2d00  ...r+...r,...r-.
+00001930: 0000 722e 0000 00da 0275 69da 0674 6865  ..r......ui..the
+00001940: 6d65 7372 3600 0000 7237 0000 0072 3800  mesr6...r7...r8.
+00001950: 0000 724c 0000 00da 0768 6173 6174 7472  ..rL.....hasattr
+00001960: 727e 0000 0072 3100 0000 da0b 6163 6365  r~...r1.....acce
+00001970: 6e74 436f 6c6f 72da 054c 6967 6874 da0b  ntColor..Light..
+00001980: 6963 6f6e 735f 636f 6c6f 72da 0c61 6363  icons_color..acc
+00001990: 656e 745f 636f 6c6f 72da 0444 6172 6b72  ent_color..Darkr
+000019a0: 3200 0000 7233 0000 0072 3400 0000 7235  2...r3...r4...r5
+000019b0: 0000 0072 3900 0000 723a 0000 0072 3b00  ...r9...r:...r;.
+000019c0: 0000 7240 0000 0072 4100 0000 7242 0000  ..r@...rA...rB..
+000019d0: 0072 4300 0000 723c 0000 0072 0200 0000  .rC...r<...r....
+000019e0: 723d 0000 0072 4400 0000 7245 0000 0072  r=...rD...rE...r
+000019f0: 4600 0000 7247 0000 0072 3e00 0000 723f  F...rG...r>...r?
+00001a00: 0000 0072 4800 0000 7249 0000 0072 4a00  ...rH...rI...rJ.
+00001a10: 0000 291c 720a 0000 0072 5300 0000 7254  ..).r....rS...rT
+00001a20: 0000 0072 2c00 0000 7255 0000 0072 5600  ...r,...rU...rV.
+00001a30: 0000 7258 0000 00da 0574 6865 6d65 727d  ..rX.....themer}
+00001a40: 0000 0072 5900 0000 5a0d 7468 656d 6550  ...rY...Z.themeP
+00001a50: 726f 7065 7274 7972 5a00 0000 725b 0000  ropertyrZ...r[..
+00001a60: 0072 5c00 0000 725d 0000 0072 6000 0000  .r\...r]...r`...
+00001a70: 7261 0000 0072 6200 0000 7263 0000 0072  ra...rb...rc...r
+00001a80: 6400 0000 724c 0000 0072 6600 0000 7267  d...rL...rf...rg
+00001a90: 0000 0072 6800 0000 7269 0000 0072 6500  ...rh...ri...re.
+00001aa0: 0000 726a 0000 0072 5e00 0000 720d 0000  ..rj...r^...r...
+00001ab0: 0072 0d00 0000 720e 0000 0072 5200 0000  .r....r....rR...
+00001ac0: d800 0000 73bc 0000 0000 0106 020c 010e  ....s...........
+00001ad0: 0104 0204 020e 010a 0406 010e 030a 010a  ................
+00001ae0: 010c 020c 0208 0106 010a 010c 020c 0208  ................
+00001af0: 0106 010a 010c 020c 0306 010c 0102 020a  ................
+00001b00: 010a 020c 021e 0208 010c 0214 0108 011c  ................
+00001b10: 0208 010a 0214 0108 020c 010a 021a 0116  ................
+00001b20: 020e 010a 020e 0110 0228 010e 0102 0212  .........(......
+00001b30: 0112 0124 0314 0108 020c 010a 021a 0116  ...$............
+00001b40: 020e 010a 020e 0110 0228 021a 0218 0116  .........(......
+00001b50: 010e 0216 0102 0212 0112 0124 0314 0108  ...........$....
+00001b60: 020c 010a 021a 0116 020e 010a 020e 0110  ................
+00001b70: 0228 021a 0218 0116 010e 0216 0102 0112  .(..............
+00001b80: 0112 0124 047a 224e 6577 4963 6f6e 7347  ...$.z"NewIconsG
+00001b90: 656e 6572 6174 6f72 2e67 656e 6572 6174  enerator.generat
+00001ba0: 6541 6c6c 4963 6f6e 7329 09da 085f 5f6e  eAllIcons)...__n
+00001bb0: 616d 655f 5fda 0a5f 5f6d 6f64 756c 655f  ame__..__module_
+00001bc0: 5fda 0c5f 5f71 7561 6c6e 616d 655f 5fda  _..__qualname__.
+00001bd0: 075f 5f64 6f63 5f5f 7208 0000 0072 6e00  .__doc__r....rn.
+00001be0: 0000 727c 0000 0072 5200 0000 da0d 5f5f  ..r|...rR.....__
+00001bf0: 636c 6173 7363 656c 6c5f 5f72 0d00 0000  classcell__r....
+00001c00: 720d 0000 0072 0b00 0000 720e 0000 0072  r....r....r....r
+00001c10: 0600 0000 1500 0000 730c 0000 0008 0104  ........s.......
+00001c20: 010c 0408 7f00 2c08 1272 0600 0000 2913  ......,..r....).
+00001c30: 7245 0000 0072 4000 0000 722a 0000 00da  rE...r@...r*....
+00001c40: 0373 7973 723e 0000 0072 7a00 0000 7272  .sysr>...rz...rr
+00001c50: 0000 0072 7400 0000 da0c 7572 6c6c 6962  ...rt.....urllib
+00001c60: 2e70 6172 7365 7202 0000 00da 0770 6174  .parser......pat
+00001c70: 686c 6962 7203 0000 00da 085f 5f6d 6169  hlibr......__mai
+00001c80: 6e5f 5fda 0b63 6f6c 6f72 7379 7374 656d  n__..colorsystem
+00001c90: 724f 0000 00da 0b71 7470 792e 5174 436f  rO.....qtpy.QtCo
+00001ca0: 7265 7229 0000 0072 5400 0000 7206 0000  rer)...rT...r...
+00001cb0: 0072 0d00 0000 720d 0000 0072 0d00 0000  .r....r....r....
+00001cc0: 720e 0000 00da 083c 6d6f 6475 6c65 3e01  r......<module>.
+00001cd0: 0000 0073 1e00 0000 0801 0801 0801 0801  ...s............
+00001ce0: 0801 0801 0801 0801 0c01 0c01 0804 0801  ................
+00001cf0: 0801 0802 0602                           ......
```

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-39.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/SvgToPngIcons.cpython-39.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-310.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-311.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-311.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-37.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-37.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-38.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-38.pyc`

 * *Format-specific differences are supported for Python .pyc files but no file-specific differences were detected; falling back to a binary diff. file(1) reports: Byte-compiled Python module for CPython 3.8, timestamp-based, .py timestamp: Sat Jun 24 14:25:41 2023 UTC, .py size: 10333 bytes*

 * *Could not decompile bytecode: bad marshal data (unknown type code)*

 * *Files 3% similar despite different names*

```diff
@@ -1,406 +1,408 @@
-00000000: 550d 0d0a 0000 0000 e5fc 9664 5d28 0000  U..........d](..
+00000000: 550d 0d0a 0000 0000 1c13 9764 4b28 0000  U..........dK(..
 00000010: e300 0000 0000 0000 0000 0000 0000 0000  ................
 00000020: 0004 0000 0040 0000 0073 9400 0000 6400  .....@...s....d.
 00000030: 6401 6c00 5a00 6400 6401 6c01 5a01 6400  d.l.Z.d.d.l.Z.d.
 00000040: 6402 6c02 5400 6400 6401 6c03 6d04 5a05  d.l.T.d.d.l.m.Z.
 00000050: 0100 6400 6401 6c06 5a06 6507 8300 5a08  ..d.d.l.Z.e...Z.
 00000060: 6412 6404 6405 8401 5a09 6406 6407 8400  d.d.d...Z.d.d...
 00000070: 5a0a 4700 6408 6409 8400 6409 8302 5a0b  Z.G.d.d...d...Z.
 00000080: 4700 640a 640b 8400 640b 650b 8303 5a0c  G.d.d...d.e...Z.
 00000090: 4700 640c 640d 8400 640d 650b 8303 5a0d  G.d.d...d.e...Z.
 000000a0: 4700 640e 640f 8400 640f 8302 5a0e 4700  G.d.d...d...Z.G.
 000000b0: 6410 6411 8400 6411 650f 8303 5a10 6401  d.d...d.e...Z.d.
 000000c0: 5300 2913 e900 0000 004e 2901 da01 2ae7  S.)......N)...*.
 000000d0: 0000 0000 0000 e03f 6302 0000 0000 0000  .......?c.......
 000000e0: 0000 0000 0008 0000 0008 0000 0043 0000  .............C..
-000000f0: 0073 a000 0000 7a0e 7400 6a01 7c00 1900  .s....z.t.j.|...
+000000f0: 0073 b600 0000 7a0e 7400 6a01 7c00 1900  .s....z.t.j.|...
 00000100: 7d02 5700 6e18 0400 7402 6b0a 7226 0100  }.W.n...t.k.r&..
 00000110: 0100 0100 7c00 7d02 5900 6e02 5800 7403  ....|.}.Y.n.X.t.
 00000120: 6a04 7400 a005 7c02 a101 8e00 7d02 7c02  j.t...|.....}.|.
-00000130: 6401 1900 7d03 7c02 6402 1900 7c01 1400  d...}.|.d...|...
-00000140: 7c01 1400 7c01 1400 7d04 7c02 6403 1900  |...|...}.|.d...
-00000150: 7d05 7403 a006 7c03 7c04 7c05 a103 7d06  }.t...|.|.|...}.
-00000160: 7407 7408 7c06 6401 1900 6404 1400 8301  t.t.|.d...d.....
-00000170: 7408 7c06 6402 1900 6404 1400 8301 7408  t.|.d...d.....t.
-00000180: 7c06 6403 1900 6404 1400 8301 6603 8301  |.d...d.....f...
-00000190: 7d07 7c07 5300 2905 4e72 0100 0000 e901  }.|.S.).Nr......
-000001a0: 0000 00e9 0200 0000 e9fa 0000 0029 09da  .............)..
-000001b0: 026d 635a 0663 6e61 6d65 73da 084b 6579  .mcZ.cnames..Key
-000001c0: 4572 726f 72da 0863 6f6c 6f72 7379 735a  Error..colorsysZ
-000001d0: 0a72 6762 5f74 6f5f 686c 735a 0674 6f5f  .rgb_to_hlsZ.to_
-000001e0: 7267 625a 0a68 6c73 5f74 6f5f 7267 62da  rgbZ.hls_to_rgb.
-000001f0: 0a72 6762 5f74 6f5f 6865 78da 0369 6e74  .rgb_to_hex..int
-00000200: 2908 da05 636f 6c6f 72da 0661 6d6f 756e  )...color..amoun
-00000210: 74da 0163 5a0c 6164 6a75 7374 6564 5f68  t..cZ.adjusted_h
-00000220: 7565 5a12 6164 6a75 7374 6564 5f6c 6967  ueZ.adjusted_lig
-00000230: 6874 6e65 7373 5a13 6164 6a75 7374 6564  htnessZ.adjusted
-00000240: 5f73 6174 7572 6174 696f 6eda 0372 6762  _saturation..rgb
-00000250: 5a09 6e65 775f 636f 6c6f 72a9 0072 1000  Z.new_color..r..
-00000260: 0000 fa46 653a 5c53 7069 6e6e 2054 6173  ...Fe:\Spinn Tas
-00000270: 6b5c 3070 6173 735c 3070 6173 732d 6170  k\0pass\0pass-ap
-00000280: 702d 6d61 7374 6572 5c43 7573 746f 6d5f  p-master\Custom_
-00000290: 5769 6467 6574 735c 5173 735c 636f 6c6f  Widgets\Qss\colo
-000002a0: 7273 7973 7465 6d2e 7079 da10 6164 6a75  rsystem.py..adju
-000002b0: 7374 5f6c 6967 6874 6e65 7373 1e00 0000  st_lightness....
-000002c0: 7316 0000 0000 0102 010e 010e 010a 0110  s...............
-000002d0: 0a08 0114 0108 020e 0132 0272 1200 0000  .........2.r....
-000002e0: 6301 0000 0000 0000 0000 0000 0002 0000  c...............
-000002f0: 0002 0000 0043 0000 0073 1000 0000 6401  .....C...s....d.
-00000300: 7c00 1600 7d01 6402 7c01 1700 5300 2903  |...}.d.|...S.).
-00000310: 4e7a 0c25 3032 7825 3032 7825 3032 78fa  Nz.%02x%02x%02x.
-00000320: 0123 7210 0000 0029 0272 0f00 0000 5a09  .#r....).r....Z.
-00000330: 6865 785f 636f 6c6f 7272 1000 0000 7210  hex_colorr....r.
-00000340: 0000 0072 1100 0000 720a 0000 0037 0000  ...r....r....7..
-00000350: 0073 0400 0000 0001 0801 720a 0000 0063  .s........r....c
-00000360: 0000 0000 0000 0000 0000 0000 0000 0000  ................
-00000370: 0300 0000 4000 0000 7316 0000 0065 005a  ....@...s....e.Z
-00000380: 0164 005a 0264 0564 0264 0384 015a 0364  .d.Z.d.d.d...Z.d
-00000390: 0453 0029 06da 0554 6865 6d65 da00 6305  .S.)...Theme..c.
-000003a0: 0000 0000 0000 0000 0000 0005 0000 0003  ................
-000003b0: 0000 0043 0000 0073 ca00 0000 7c01 7c00  ...C...s....|.|.
-000003c0: 5f00 7c02 7c00 5f01 7c03 7c00 5f02 7c04  _.|.|._.|.|._.|.
-000003d0: 7c00 5f03 7404 7c01 6401 8302 7c00 5f05  |._.t.|.d...|._.
-000003e0: 7404 7c01 6402 8302 7c00 5f06 7404 7c01  t.|.d...|._.t.|.
-000003f0: 6403 8302 7c00 5f07 7404 7c01 6404 8302  d...|._.t.|.d...
-00000400: 7c00 5f08 7404 7c01 6405 8302 7c00 5f09  |._.t.|.d...|._.
-00000410: 7404 7c01 6406 8302 7c00 5f0a 7404 7c02  t.|.d...|._.t.|.
-00000420: 6401 8302 7c00 5f0b 7404 7c02 6407 8302  d...|._.t.|.d...
-00000430: 7c00 5f0c 7404 7c02 6403 8302 7c00 5f0d  |._.t.|.d...|._.
-00000440: 7404 7c02 6408 8302 7c00 5f0e 7404 7c03  t.|.d...|._.t.|.
-00000450: 6401 8302 7c00 5f0f 7404 7c03 6407 8302  d...|._.t.|.d...
-00000460: 7c00 5f10 7404 7c03 6403 8302 7c00 5f11  |._.t.|.d...|._.
-00000470: 7404 7c03 6408 8302 7c00 5f12 6409 7c00  t.|.d...|._.d.|.
-00000480: 5f13 6400 5300 290a 4e72 0400 0000 6766  _.d.S.).Nr....gf
-00000490: 6666 6666 66ee 3fe7 9a99 9999 9999 e93f  fffff.?........?
-000004a0: 6700 0000 0000 00e8 3fe7 3333 3333 3333  g.......?.333333
-000004b0: e33f 679a 9999 9999 99e1 3fe7 cdcc cccc  .?g.......?.....
-000004c0: cccc ec3f e766 6666 6666 66e6 3ffa 0e3a  ...?.ffffff.?..:
-000004d0: 2f69 636f 6e73 2f49 636f 6e73 2f29 14da  /icons/Icons/)..
-000004e0: 0862 675f 636f 6c6f 72da 0974 7874 5f63  .bg_color..txt_c
-000004f0: 6f6c 6f72 da0c 6163 6365 6e74 5f63 6f6c  olor..accent_col
-00000500: 6f72 da0b 6963 6f6e 735f 636f 6c6f 7272  or..icons_colorr
-00000510: 1200 0000 da04 4247 5f31 da04 4247 5f32  ......BG_1..BG_2
-00000520: da04 4247 5f33 da04 4247 5f34 da04 4247  ..BG_3..BG_4..BG
-00000530: 5f35 da04 4247 5f36 da04 4354 5f31 da04  _5..BG_6..CT_1..
-00000540: 4354 5f32 da04 4354 5f33 da04 4354 5f34  CT_2..CT_3..CT_4
-00000550: da04 4341 5f31 da04 4341 5f32 da04 4341  ..CA_1..CA_2..CA
-00000560: 5f33 da04 4341 5f34 da05 4943 4f4e 5329  _3..CA_4..ICONS)
-00000570: 05da 0473 656c 6672 1b00 0000 721c 0000  ...selfr....r...
-00000580: 0072 1d00 0000 721e 0000 0072 1000 0000  .r....r....r....
-00000590: 7210 0000 0072 1100 0000 da08 5f5f 696e  r....r......__in
-000005a0: 6974 5f5f 3c00 0000 7326 0000 0000 0106  it__<...s&......
-000005b0: 0106 0106 0106 020c 010c 010c 010c 010c  ................
-000005c0: 010c 020c 010c 010c 010c 020c 010c 010c  ................
-000005d0: 010c 027a 0e54 6865 6d65 2e5f 5f69 6e69  ...z.Theme.__ini
-000005e0: 745f 5f4e 2901 7215 0000 0029 04da 085f  t__N).r....)..._
-000005f0: 5f6e 616d 655f 5fda 0a5f 5f6d 6f64 756c  _name__..__modul
-00000600: 655f 5fda 0c5f 5f71 7561 6c6e 616d 655f  e__..__qualname_
-00000610: 5f72 2f00 0000 7210 0000 0072 1000 0000  _r/...r....r....
-00000620: 7210 0000 0072 1100 0000 7214 0000 003b  r....r....r....;
-00000630: 0000 0073 0200 0000 0801 7214 0000 0063  ...s......r....c
-00000640: 0000 0000 0000 0000 0000 0000 0000 0000  ................
-00000650: 0300 0000 0000 0000 731c 0000 0065 005a  ........s....e.Z
-00000660: 0164 005a 0287 0066 0164 0164 0284 085a  .d.Z...f.d.d...Z
-00000670: 0387 0004 005a 0453 0029 03da 0444 6172  .....Z.S.)...Dar
-00000680: 6b63 0100 0000 0000 0000 0000 0000 0100  kc..............
-00000690: 0000 0500 0000 0300 0000 7314 0000 0074  ..........s....t
-000006a0: 0083 00a0 0164 0164 0264 03a1 0301 0064  .....d.d.d.....d
-000006b0: 0053 0029 044e 7a07 2330 4430 4431 34fa  .S.).Nz.#0D0D14.
-000006c0: 0423 6666 667a 0723 4138 4239 4244 a902  .#fffz.#A8B9BD..
-000006d0: da05 7375 7065 7272 2f00 0000 a901 722e  ..superr/.....r.
-000006e0: 0000 00a9 01da 095f 5f63 6c61 7373 5f5f  .......__class__
-000006f0: 7210 0000 0072 1100 0000 722f 0000 0056  r....r....r/...V
-00000700: 0000 0073 0200 0000 0001 7a0d 4461 726b  ...s......z.Dark
-00000710: 2e5f 5f69 6e69 745f 5fa9 0572 3000 0000  .__init__..r0...
-00000720: 7231 0000 0072 3200 0000 722f 0000 00da  r1...r2...r/....
-00000730: 0d5f 5f63 6c61 7373 6365 6c6c 5f5f 7210  .__classcell__r.
-00000740: 0000 0072 1000 0000 7238 0000 0072 1100  ...r....r8...r..
-00000750: 0000 7233 0000 0055 0000 0073 0200 0000  ..r3...U...s....
-00000760: 0801 7233 0000 0063 0000 0000 0000 0000  ..r3...c........
-00000770: 0000 0000 0000 0000 0300 0000 0000 0000  ................
-00000780: 731c 0000 0065 005a 0164 005a 0287 0066  s....e.Z.d.Z...f
-00000790: 0164 0164 0284 085a 0387 0004 005a 0453  .d.d...Z.....Z.S
-000007a0: 0029 03da 054c 6967 6874 6301 0000 0000  .)...Lightc.....
-000007b0: 0000 0000 0000 0001 0000 0005 0000 0003  ................
-000007c0: 0000 0073 1400 0000 7400 8300 a001 6401  ...s....t.....d.
-000007d0: 6402 6403 a103 0100 6400 5300 2904 4e72  d.d.....d.S.).Nr
-000007e0: 3400 0000 7a04 2330 3030 7a07 2330 3062  4...z.#000z.#00b
-000007f0: 6366 6672 3500 0000 7237 0000 0072 3800  cffr5...r7...r8.
-00000800: 0000 7210 0000 0072 1100 0000 722f 0000  ..r....r....r/..
-00000810: 005a 0000 0073 0200 0000 0001 7a0e 4c69  .Z...s......z.Li
-00000820: 6768 742e 5f5f 696e 6974 5f5f 723a 0000  ght.__init__r:..
-00000830: 0072 1000 0000 7210 0000 0072 3800 0000  .r....r....r8...
-00000840: 7211 0000 0072 3c00 0000 5900 0000 7302  r....r<...Y...s.
-00000850: 0000 0008 0172 3c00 0000 6300 0000 0000  .....r<...c.....
-00000860: 0000 0000 0000 0000 0000 0004 0000 0000  ................
-00000870: 0000 0073 2e00 0000 6500 5a01 6400 5a02  ...s....e.Z.d.Z.
-00000880: 6408 8700 6601 6402 6403 8409 5a03 6404  d...f.d.d...Z.d.
-00000890: 6405 8400 5a04 6406 6407 8400 5a05 8700  d...Z.d.d...Z...
-000008a0: 0400 5a06 5300 2909 da13 4372 6561 7465  ..Z.S.)...Create
-000008b0: 436f 6c6f 7256 6172 6961 626c 654e 6302  ColorVariableNc.
-000008c0: 0000 0000 0000 0000 0000 0002 0000 0003  ................
-000008d0: 0000 0003 0000 0073 1400 0000 7400 7401  .......s....t.t.
-000008e0: 7c00 8302 a002 7c01 a101 0100 6400 5300  |.....|.....d.S.
-000008f0: 2901 4e29 0372 3600 0000 723d 0000 0072  ).N).r6...r=...r
-00000900: 2f00 0000 2902 722e 0000 00da 0670 6172  /...).r......par
-00000910: 656e 7472 3800 0000 7210 0000 0072 1100  entr8...r....r..
-00000920: 0000 722f 0000 0066 0000 0073 0200 0000  ..r/...f...s....
-00000930: 0001 7a1c 4372 6561 7465 436f 6c6f 7256  ..z.CreateColorV
-00000940: 6172 6961 626c 652e 5f5f 696e 6974 5f5f  ariable.__init__
-00000950: 6301 0000 0000 0000 0000 0000 0009 0000  c...............
-00000960: 0006 0000 0043 0000 0073 5001 0000 7400  .....C...sP...t.
-00000970: 8300 7d01 7c01 a001 6401 a101 7d02 6900  ..}.|...d...}.i.
-00000980: 7d03 7c02 6402 6b02 7258 7402 8300 7d04  }.|.d.k.rXt...}.
-00000990: 7c04 6a03 6403 6b02 723c 7c04 6a04 7d05  |.j.d.k.r<|.j.}.
-000009a0: 7c04 6a04 7c04 5f03 6e06 7c04 6a03 7d05  |.j.|._.n.|.j.}.
-000009b0: 7c04 6a05 7c04 6a06 7c04 6a04 7c05 6404  |.j.|.j.|.j.|.d.
-000009c0: 9c04 7d03 6eb2 7c02 6405 6b02 729c 7407  ..}.n.|.d.k.r.t.
-000009d0: 8300 7d04 7c04 6a03 6403 6b02 7280 7c04  ..}.|.j.d.k.r.|.
-000009e0: 6a04 7d05 7c04 6a04 7c04 5f03 6e06 7c04  j.}.|.j.|._.n.|.
-000009f0: 6a03 7d05 7c04 6a05 7c04 6a06 7c04 6a04  j.}.|.j.|.j.|.j.
-00000a00: 7c05 6404 9c04 7d03 6e6e 7c00 6a08 6a09  |.d...}.nn|.j.j.
-00000a10: 4400 5d64 7d04 7c04 6a0a 73b8 7c04 6a0b  D.]d}.|.j.s.|.j.
-00000a20: 7c02 6b02 72a4 7c01 a00c 6401 7c04 6a0b  |.k.r.|...d.|.j.
-00000a30: a102 0100 7c04 6a0d 7d06 7c04 6a0e 7d07  ....|.j.}.|.j.}.
-00000a40: 7c04 6a0f 7d08 7c04 6a10 72f6 7c04 6a11  |.j.}.|.j.r.|.j.
-00000a50: 6403 6b02 72ee 7c08 7d05 71fa 7c04 6a11  d.k.r.|.}.q.|.j.
-00000a60: 7d05 6e04 6400 7d05 7c06 7c07 7c08 7c05  }.n.d.}.|.|.|.|.
-00000a70: 6404 9c04 7d03 71a4 7412 7c03 8301 6406  d...}.q.t.|...d.
-00000a80: 6b02 9001 724c 7402 8300 7d04 7c04 6a03  k...rLt...}.|.j.
-00000a90: 6403 6b02 9001 7232 7c04 6a04 7d05 6e06  d.k...r2|.j.}.n.
-00000aa0: 7c04 6a03 7d05 7c04 6a05 7c04 6a06 7c04  |.j.}.|.j.|.j.|.
-00000ab0: 6a04 7c05 6404 9c04 7d03 7c03 5300 2907  j.|.d...}.|.S.).
-00000ac0: 4eda 0554 4845 4d45 da05 4c49 4748 5472  N..THEME..LIGHTr
-00000ad0: 1500 0000 2904 7a10 6261 636b 6772 6f75  ....).z.backgrou
-00000ae0: 6e64 2d63 6f6c 6f72 7a0a 7465 7874 2d63  nd-colorz.text-c
-00000af0: 6f6c 6f72 7a0c 6163 6365 6e74 2d63 6f6c  olorz.accent-col
-00000b00: 6f72 7a0b 6963 6f6e 732d 636f 6c6f 72da  orz.icons-color.
-00000b10: 0444 4152 4b72 0100 0000 2913 da09 5153  .DARKr....)...QS
-00000b20: 6574 7469 6e67 73da 0576 616c 7565 723c  ettings..valuer<
-00000b30: 0000 0072 1e00 0000 721d 0000 0072 1b00  ...r....r....r..
-00000b40: 0000 721c 0000 0072 3300 0000 da02 7569  ..r....r3.....ui
-00000b50: da06 7468 656d 6573 da0c 6465 6661 756c  ..themes..defaul
-00000b60: 7454 6865 6d65 da04 6e61 6d65 da08 7365  tTheme..name..se
-00000b70: 7456 616c 7565 da0f 6261 636b 6772 6f75  tValue..backgrou
-00000b80: 6e64 436f 6c6f 72da 0974 6578 7443 6f6c  ndColor..textCol
-00000b90: 6f72 da0b 6163 6365 6e74 436f 6c6f 72da  or..accentColor.
-00000ba0: 0e63 7265 6174 654e 6577 4963 6f6e 73da  .createNewIcons.
-00000bb0: 0a69 636f 6e73 436f 6c6f 72da 036c 656e  .iconsColor..len
-00000bc0: 2909 722e 0000 00da 0873 6574 7469 6e67  ).r......setting
-00000bd0: 7372 3f00 0000 5a10 6375 7272 656e 7454  sr?...Z.currentT
-00000be0: 6865 6d65 496e 666f da05 7468 656d 6572  hemeInfo..themer
-00000bf0: 4d00 0000 721b 0000 0072 1c00 0000 721d  M...r....r....r.
-00000c00: 0000 0072 1000 0000 7210 0000 0072 1100  ...r....r....r..
-00000c10: 0000 da13 6765 7443 7572 7265 6e74 5468  ....getCurrentTh
-00000c20: 656d 6549 6e66 6f69 0000 0073 4800 0000  emeInfoi...sH...
-00000c30: 0001 0602 0a02 0402 0801 0601 0a01 0601  ................
-00000c40: 0a02 0602 1602 0801 0601 0a01 0601 0a02  ................
-00000c50: 0602 1603 0c01 1002 0e01 0601 0601 0602  ................
-00000c60: 0601 0a01 0602 0802 0402 1002 0e01 0601  ................
-00000c70: 0c01 0802 0602 1402 7a27 4372 6561 7465  ........z'Create
-00000c80: 436f 6c6f 7256 6172 6961 626c 652e 6765  ColorVariable.ge
-00000c90: 7443 7572 7265 6e74 5468 656d 6549 6e66  tCurrentThemeInf
-00000ca0: 6f63 0100 0000 0000 0000 0000 0000 0900  oc..............
-00000cb0: 0000 2000 0000 4300 0000 73e2 0200 0074  .. ...C...s....t
-00000cc0: 0083 007d 017c 01a0 0164 01a1 017d 0264  ...}.|...d...}.d
-00000cd0: 027d 037c 0264 036b 0272 2674 0283 007d  .}.|.d.k.r&t...}
-00000ce0: 0490 016e 3a7c 0264 046b 0272 3874 0383  ...n:|.d.k.r8t..
-00000cf0: 007d 0490 016e 287c 006a 046a 0544 005d  .}...n(|.j.j.D.]
-00000d00: 4a7d 057c 056a 0673 547c 056a 077c 026b  J}.|.j.sT|.j.|.k
-00000d10: 0272 407c 01a0 0864 017c 056a 07a1 0201  .r@|...d.|.j....
-00000d20: 007c 057d 047c 056a 097c 045f 0a7c 056a  .|.}.|.j.|._.|.j
-00000d30: 0b7c 045f 0c7c 056a 0d7c 045f 0e7c 046a  .|._.|.j.|._.|.j
-00000d40: 0f7c 045f 1064 057d 0371 407c 0373 9674  .|._.d.}.q@|.s.t
-00000d50: 0283 007d 0474 117c 046a 0a64 0683 027c  ...}.t.|.j.d...|
-00000d60: 045f 1274 117c 046a 0a64 0783 027c 045f  ._.t.|.j.d...|._
-00000d70: 1374 117c 046a 0a64 0883 027c 045f 1474  .t.|.j.d...|._.t
-00000d80: 117c 046a 0a64 0983 027c 045f 1574 117c  .|.j.d...|._.t.|
-00000d90: 046a 0a64 0a83 027c 045f 1674 117c 046a  .j.d...|._.t.|.j
-00000da0: 0a64 0b83 027c 045f 1774 117c 046a 0c64  .d...|._.t.|.j.d
-00000db0: 0683 027c 045f 1874 117c 046a 0c64 0783  ...|._.t.|.j.d..
-00000dc0: 027c 045f 1974 117c 046a 0c64 0883 027c  .|._.t.|.j.d...|
-00000dd0: 045f 1a74 117c 046a 0c64 0983 027c 045f  ._.t.|.j.d...|._
-00000de0: 1b74 117c 046a 0e64 0683 027c 045f 1c74  .t.|.j.d...|._.t
-00000df0: 117c 046a 0e64 0783 027c 045f 1d74 117c  .|.j.d...|._.t.|
-00000e00: 046a 0e64 0883 027c 045f 1e74 117c 046a  .j.d...|._.t.|.j
-00000e10: 0e64 0983 027c 045f 1f64 0c7c 045f 2074  .d...|._.d.|._ t
-00000e20: 2183 007c 005f 227c 046a 127c 006a 225f  !..|._"|.j.|.j"_
-00000e30: 237c 046a 137c 006a 225f 247c 046a 147c  #|.j.|.j"_$|.j.|
-00000e40: 006a 225f 257c 046a 157c 006a 225f 267c  .j"_%|.j.|.j"_&|
-00000e50: 046a 167c 006a 225f 277c 046a 177c 006a  .j.|.j"_'|.j.|.j
-00000e60: 225f 287c 046a 187c 006a 225f 297c 046a  "_(|.j.|.j"_)|.j
-00000e70: 197c 006a 225f 2a7c 046a 1a7c 006a 225f  .|.j"_*|.j.|.j"_
-00000e80: 2b7c 046a 1b7c 006a 225f 2c7c 046a 1c7c  +|.j.|.j"_,|.j.|
-00000e90: 006a 225f 2d7c 046a 1d7c 006a 225f 2e7c  .j"_-|.j.|.j"_.|
-00000ea0: 046a 1e7c 006a 225f 2f7c 046a 1f7c 006a  .j.|.j"_/|.j.|.j
-00000eb0: 225f 307c 046a 207c 006a 225f 3174 326a  "_0|.j |.j"_1t2j
-00000ec0: 33a0 3474 326a 33a0 3574 32a0 36a1 0064  3.4t2j3.5t2.6..d
-00000ed0: 0da1 02a1 017d 0674 326a 33a0 377c 06a1  .....}.t2j3.7|..
-00000ee0: 0190 0273 3074 32a0 387c 06a1 0101 0074  ...s0t2.8|.....t
-00000ef0: 326a 33a0 3474 326a 33a0 357c 0664 0ea1  2j3.4t2j3.5|.d..
-00000f00: 02a1 017d 0774 397c 0764 0f83 027d 0874  ...}.t9|.d...}.t
-00000f10: 3a64 107c 046a 129b 0064 117c 046a 139b  :d.|.j...d.|.j..
-00000f20: 0064 127c 046a 149b 0064 137c 046a 159b  .d.|.j...d.|.j..
-00000f30: 0064 147c 046a 169b 0064 157c 046a 179b  .d.|.j...d.|.j..
-00000f40: 0064 167c 046a 189b 0064 177c 046a 199b  .d.|.j...d.|.j..
-00000f50: 0064 187c 046a 1a9b 0064 197c 046a 1b9b  .d.|.j...d.|.j..
-00000f60: 0064 1a7c 046a 1c9b 0064 1b7c 046a 1d9b  .d.|.j...d.|.j..
-00000f70: 0064 1c7c 046a 1e9b 0064 1d7c 046a 1f9b  .d.|.j...d.|.j..
-00000f80: 0064 1e7c 046a 209b 0064 1f9d 1f7c 0864  .d.|.j ..d...|.d
-00000f90: 208d 0201 007c 08a0 3ba1 0001 0064 0053   ....|..;....d.S
-00000fa0: 0029 214e 723f 0000 0046 7240 0000 0072  .)!Nr?...Fr@...r
-00000fb0: 4100 0000 5472 0400 0000 7218 0000 0072  A...Tr....r....r
-00000fc0: 1600 0000 7219 0000 0072 1700 0000 7203  ....r....r....r.
-00000fd0: 0000 0072 1a00 0000 da03 5153 537a 0f5f  ...r......QSSz._
-00000fe0: 7661 7269 6162 6c65 732e 7363 7373 da01  variables.scss..
-00000ff0: 777a e00a 2020 2020 2020 2020 2f2f 3d3d  wz..        //==
-00001000: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
-00001010: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
+00000130: 6401 1900 6402 6b04 7256 7c02 6401 1900  d...d.k.rV|.d...
+00000140: 7c01 1400 7c01 1400 7d03 6e0c 6401 7c01  |...|...}.n.d.|.
+00000150: 7c01 1400 1800 7d03 7c02 6402 1900 7d04  |.....}.|.d...}.
+00000160: 7c02 6403 1900 7d05 7403 a006 7c04 7c03  |.d...}.t...|.|.
+00000170: 7c05 a103 7d06 7407 7408 7c06 6402 1900  |...}.t.t.|.d...
+00000180: 6404 1400 8301 7408 7c06 6401 1900 6404  d.....t.|.d...d.
+00000190: 1400 8301 7408 7c06 6403 1900 6404 1400  ....t.|.d...d...
+000001a0: 8301 6603 8301 7d07 7c07 5300 2905 4ee9  ..f...}.|.S.).N.
+000001b0: 0100 0000 7201 0000 00e9 0200 0000 e9fa  ....r...........
+000001c0: 0000 0029 09da 026d 635a 0663 6e61 6d65  ...)...mcZ.cname
+000001d0: 73da 084b 6579 4572 726f 72da 0863 6f6c  s..KeyError..col
+000001e0: 6f72 7379 735a 0a72 6762 5f74 6f5f 686c  orsysZ.rgb_to_hl
+000001f0: 735a 0674 6f5f 7267 625a 0a68 6c73 5f74  sZ.to_rgbZ.hls_t
+00000200: 6f5f 7267 62da 0a72 6762 5f74 6f5f 6865  o_rgb..rgb_to_he
+00000210: 78da 0369 6e74 2908 da05 636f 6c6f 72da  x..int)...color.
+00000220: 0661 6d6f 756e 74da 0163 5a12 6164 6a75  .amount..cZ.adju
+00000230: 7374 6564 5f6c 6967 6874 6e65 7373 5a0c  sted_lightnessZ.
+00000240: 6164 6a75 7374 6564 5f68 7565 5a13 6164  adjusted_hueZ.ad
+00000250: 6a75 7374 6564 5f73 6174 7572 6174 696f  justed_saturatio
+00000260: 6eda 0372 6762 5a09 6e65 775f 636f 6c6f  n..rgbZ.new_colo
+00000270: 72a9 0072 1000 0000 fa46 653a 5c53 7069  r..r.....Fe:\Spi
+00000280: 6e6e 2054 6173 6b5c 3070 6173 735c 3070  nn Task\0pass\0p
+00000290: 6173 732d 6170 702d 6d61 7374 6572 5c43  ass-app-master\C
+000002a0: 7573 746f 6d5f 5769 6467 6574 735c 5173  ustom_Widgets\Qs
+000002b0: 735c 636f 6c6f 7273 7973 7465 6d2e 7079  s\colorsystem.py
+000002c0: da10 6164 6a75 7374 5f6c 6967 6874 6e65  ..adjust_lightne
+000002d0: 7373 1e00 0000 731a 0000 0000 0102 010e  ss....s.........
+000002e0: 010e 010a 0110 030c 0212 020c 0308 0208  ................
+000002f0: 020e 0132 0272 1200 0000 6301 0000 0000  ...2.r....c.....
+00000300: 0000 0000 0000 0002 0000 0002 0000 0043  ...............C
+00000310: 0000 0073 1000 0000 6401 7c00 1600 7d01  ...s....d.|...}.
+00000320: 6402 7c01 1700 5300 2903 4e7a 0c25 3032  d.|...S.).Nz.%02
+00000330: 7825 3032 7825 3032 78fa 0123 7210 0000  x%02x%02x..#r...
+00000340: 0029 0272 0f00 0000 5a09 6865 785f 636f  .).r....Z.hex_co
+00000350: 6c6f 7272 1000 0000 7210 0000 0072 1100  lorr....r....r..
+00000360: 0000 720a 0000 0037 0000 0073 0400 0000  ..r....7...s....
+00000370: 0001 0801 720a 0000 0063 0000 0000 0000  ....r....c......
+00000380: 0000 0000 0000 0000 0000 0300 0000 4000  ..............@.
+00000390: 0000 7316 0000 0065 005a 0164 005a 0264  ..s....e.Z.d.Z.d
+000003a0: 0564 0264 0384 015a 0364 0453 0029 06da  .d.d...Z.d.S.)..
+000003b0: 0554 6865 6d65 da00 6305 0000 0000 0000  .Theme..c.......
+000003c0: 0000 0000 0005 0000 0003 0000 0043 0000  .............C..
+000003d0: 0073 ca00 0000 7c01 7c00 5f00 7c02 7c00  .s....|.|._.|.|.
+000003e0: 5f01 7c03 7c00 5f02 7c04 7c00 5f03 7404  _.|.|._.|.|._.t.
+000003f0: 7c01 6401 8302 7c00 5f05 7404 7c01 6402  |.d...|._.t.|.d.
+00000400: 8302 7c00 5f06 7404 7c01 6403 8302 7c00  ..|._.t.|.d...|.
+00000410: 5f07 7404 7c01 6404 8302 7c00 5f08 7404  _.t.|.d...|._.t.
+00000420: 7c01 6405 8302 7c00 5f09 7404 7c01 6406  |.d...|._.t.|.d.
+00000430: 8302 7c00 5f0a 7404 7c02 6401 8302 7c00  ..|._.t.|.d...|.
+00000440: 5f0b 7404 7c02 6407 8302 7c00 5f0c 7404  _.t.|.d...|._.t.
+00000450: 7c02 6403 8302 7c00 5f0d 7404 7c02 6408  |.d...|._.t.|.d.
+00000460: 8302 7c00 5f0e 7404 7c03 6401 8302 7c00  ..|._.t.|.d...|.
+00000470: 5f0f 7404 7c03 6407 8302 7c00 5f10 7404  _.t.|.d...|._.t.
+00000480: 7c03 6403 8302 7c00 5f11 7404 7c03 6408  |.d...|._.t.|.d.
+00000490: 8302 7c00 5f12 6409 7c00 5f13 6400 5300  ..|._.d.|._.d.S.
+000004a0: 290a 4e72 0400 0000 6766 6666 6666 66ee  ).Nr....gffffff.
+000004b0: 3fe7 9a99 9999 9999 e93f 6700 0000 0000  ?........?g.....
+000004c0: 00e8 3fe7 3333 3333 3333 e33f 679a 9999  ..?.333333.?g...
+000004d0: 9999 99e1 3fe7 cdcc cccc cccc ec3f e766  ....?........?.f
+000004e0: 6666 6666 66e6 3ffa 0e3a 2f69 636f 6e73  fffff.?..:/icons
+000004f0: 2f49 636f 6e73 2f29 14da 0862 675f 636f  /Icons/)...bg_co
+00000500: 6c6f 72da 0974 7874 5f63 6f6c 6f72 da0c  lor..txt_color..
+00000510: 6163 6365 6e74 5f63 6f6c 6f72 da0b 6963  accent_color..ic
+00000520: 6f6e 735f 636f 6c6f 7272 1200 0000 da04  ons_colorr......
+00000530: 4247 5f31 da04 4247 5f32 da04 4247 5f33  BG_1..BG_2..BG_3
+00000540: da04 4247 5f34 da04 4247 5f35 da04 4247  ..BG_4..BG_5..BG
+00000550: 5f36 da04 4354 5f31 da04 4354 5f32 da04  _6..CT_1..CT_2..
+00000560: 4354 5f33 da04 4354 5f34 da04 4341 5f31  CT_3..CT_4..CA_1
+00000570: da04 4341 5f32 da04 4341 5f33 da04 4341  ..CA_2..CA_3..CA
+00000580: 5f34 da05 4943 4f4e 5329 05da 0473 656c  _4..ICONS)...sel
+00000590: 6672 1b00 0000 721c 0000 0072 1d00 0000  fr....r....r....
+000005a0: 721e 0000 0072 1000 0000 7210 0000 0072  r....r....r....r
+000005b0: 1100 0000 da08 5f5f 696e 6974 5f5f 3c00  ......__init__<.
+000005c0: 0000 7326 0000 0000 0106 0106 0106 0106  ..s&............
+000005d0: 020c 010c 010c 010c 010c 010c 020c 010c  ................
+000005e0: 010c 010c 020c 010c 010c 010c 027a 0e54  .............z.T
+000005f0: 6865 6d65 2e5f 5f69 6e69 745f 5f4e 2901  heme.__init__N).
+00000600: 7215 0000 0029 04da 085f 5f6e 616d 655f  r....)...__name_
+00000610: 5fda 0a5f 5f6d 6f64 756c 655f 5fda 0c5f  _..__module__.._
+00000620: 5f71 7561 6c6e 616d 655f 5f72 2f00 0000  _qualname__r/...
+00000630: 7210 0000 0072 1000 0000 7210 0000 0072  r....r....r....r
+00000640: 1100 0000 7214 0000 003b 0000 0073 0200  ....r....;...s..
+00000650: 0000 0801 7214 0000 0063 0000 0000 0000  ....r....c......
+00000660: 0000 0000 0000 0000 0000 0300 0000 0000  ................
+00000670: 0000 731c 0000 0065 005a 0164 005a 0287  ..s....e.Z.d.Z..
+00000680: 0066 0164 0164 0284 085a 0387 0004 005a  .f.d.d...Z.....Z
+00000690: 0453 0029 03da 0444 6172 6b63 0100 0000  .S.)...Darkc....
+000006a0: 0000 0000 0000 0000 0100 0000 0500 0000  ................
+000006b0: 0300 0000 7314 0000 0074 0083 00a0 0164  ....s....t.....d
+000006c0: 0164 0264 03a1 0301 0064 0053 0029 044e  .d.d.....d.S.).N
+000006d0: 7a07 2330 4430 4431 34fa 0423 6666 667a  z.#0D0D14..#fffz
+000006e0: 0723 4138 4239 4244 a902 da05 7375 7065  .#A8B9BD....supe
+000006f0: 7272 2f00 0000 a901 722e 0000 00a9 01da  rr/.....r.......
+00000700: 095f 5f63 6c61 7373 5f5f 7210 0000 0072  .__class__r....r
+00000710: 1100 0000 722f 0000 0056 0000 0073 0200  ....r/...V...s..
+00000720: 0000 0001 7a0d 4461 726b 2e5f 5f69 6e69  ....z.Dark.__ini
+00000730: 745f 5fa9 0572 3000 0000 7231 0000 0072  t__..r0...r1...r
+00000740: 3200 0000 722f 0000 00da 0d5f 5f63 6c61  2...r/.....__cla
+00000750: 7373 6365 6c6c 5f5f 7210 0000 0072 1000  sscell__r....r..
+00000760: 0000 7238 0000 0072 1100 0000 7233 0000  ..r8...r....r3..
+00000770: 0055 0000 0073 0200 0000 0801 7233 0000  .U...s......r3..
+00000780: 0063 0000 0000 0000 0000 0000 0000 0000  .c..............
+00000790: 0000 0300 0000 0000 0000 731c 0000 0065  ..........s....e
+000007a0: 005a 0164 005a 0287 0066 0164 0164 0284  .Z.d.Z...f.d.d..
+000007b0: 085a 0387 0004 005a 0453 0029 03da 054c  .Z.....Z.S.)...L
+000007c0: 6967 6874 6301 0000 0000 0000 0000 0000  ightc...........
+000007d0: 0001 0000 0005 0000 0003 0000 0073 1400  .............s..
+000007e0: 0000 7400 8300 a001 6401 6402 6403 a103  ..t.....d.d.d...
+000007f0: 0100 6400 5300 2904 4e72 3400 0000 7a04  ..d.S.).Nr4...z.
+00000800: 2330 3030 7a07 2330 3062 6366 6672 3500  #000z.#00bcffr5.
+00000810: 0000 7237 0000 0072 3800 0000 7210 0000  ..r7...r8...r...
+00000820: 0072 1100 0000 722f 0000 005a 0000 0073  .r....r/...Z...s
+00000830: 0200 0000 0001 7a0e 4c69 6768 742e 5f5f  ......z.Light.__
+00000840: 696e 6974 5f5f 723a 0000 0072 1000 0000  init__r:...r....
+00000850: 7210 0000 0072 3800 0000 7211 0000 0072  r....r8...r....r
+00000860: 3c00 0000 5900 0000 7302 0000 0008 0172  <...Y...s......r
+00000870: 3c00 0000 6300 0000 0000 0000 0000 0000  <...c...........
+00000880: 0000 0000 0004 0000 0000 0000 0073 2e00  .............s..
+00000890: 0000 6500 5a01 6400 5a02 6408 8700 6601  ..e.Z.d.Z.d...f.
+000008a0: 6402 6403 8409 5a03 6404 6405 8400 5a04  d.d...Z.d.d...Z.
+000008b0: 6406 6407 8400 5a05 8700 0400 5a06 5300  d.d...Z.....Z.S.
+000008c0: 2909 da13 4372 6561 7465 436f 6c6f 7256  )...CreateColorV
+000008d0: 6172 6961 626c 654e 6302 0000 0000 0000  ariableNc.......
+000008e0: 0000 0000 0002 0000 0003 0000 0003 0000  ................
+000008f0: 0073 1400 0000 7400 7401 7c00 8302 a002  .s....t.t.|.....
+00000900: 7c01 a101 0100 6400 5300 2901 4e29 0372  |.....d.S.).N).r
+00000910: 3600 0000 723d 0000 0072 2f00 0000 2902  6...r=...r/...).
+00000920: 722e 0000 00da 0670 6172 656e 7472 3800  r......parentr8.
+00000930: 0000 7210 0000 0072 1100 0000 722f 0000  ..r....r....r/..
+00000940: 0066 0000 0073 0200 0000 0001 7a1c 4372  .f...s......z.Cr
+00000950: 6561 7465 436f 6c6f 7256 6172 6961 626c  eateColorVariabl
+00000960: 652e 5f5f 696e 6974 5f5f 6301 0000 0000  e.__init__c.....
+00000970: 0000 0000 0000 0009 0000 0006 0000 0043  ...............C
+00000980: 0000 0073 5001 0000 7400 8300 7d01 7c01  ...sP...t...}.|.
+00000990: a001 6401 a101 7d02 6900 7d03 7c02 6402  ..d...}.i.}.|.d.
+000009a0: 6b02 7258 7402 8300 7d04 7c04 6a03 6403  k.rXt...}.|.j.d.
+000009b0: 6b02 723c 7c04 6a04 7d05 7c04 6a04 7c04  k.r<|.j.}.|.j.|.
+000009c0: 5f03 6e06 7c04 6a03 7d05 7c04 6a05 7c04  _.n.|.j.}.|.j.|.
+000009d0: 6a06 7c04 6a04 7c05 6404 9c04 7d03 6eb2  j.|.j.|.d...}.n.
+000009e0: 7c02 6405 6b02 729c 7407 8300 7d04 7c04  |.d.k.r.t...}.|.
+000009f0: 6a03 6403 6b02 7280 7c04 6a04 7d05 7c04  j.d.k.r.|.j.}.|.
+00000a00: 6a04 7c04 5f03 6e06 7c04 6a03 7d05 7c04  j.|._.n.|.j.}.|.
+00000a10: 6a05 7c04 6a06 7c04 6a04 7c05 6404 9c04  j.|.j.|.j.|.d...
+00000a20: 7d03 6e6e 7c00 6a08 6a09 4400 5d64 7d04  }.nn|.j.j.D.]d}.
+00000a30: 7c04 6a0a 73b8 7c04 6a0b 7c02 6b02 72a4  |.j.s.|.j.|.k.r.
+00000a40: 7c01 a00c 6401 7c04 6a0b a102 0100 7c04  |...d.|.j.....|.
+00000a50: 6a0d 7d06 7c04 6a0e 7d07 7c04 6a0f 7d08  j.}.|.j.}.|.j.}.
+00000a60: 7c04 6a10 72f6 7c04 6a11 6403 6b02 72ee  |.j.r.|.j.d.k.r.
+00000a70: 7c08 7d05 71fa 7c04 6a11 7d05 6e04 6400  |.}.q.|.j.}.n.d.
+00000a80: 7d05 7c06 7c07 7c08 7c05 6404 9c04 7d03  }.|.|.|.|.d...}.
+00000a90: 71a4 7412 7c03 8301 6406 6b02 9001 724c  q.t.|...d.k...rL
+00000aa0: 7402 8300 7d04 7c04 6a03 6403 6b02 9001  t...}.|.j.d.k...
+00000ab0: 7232 7c04 6a04 7d05 6e06 7c04 6a03 7d05  r2|.j.}.n.|.j.}.
+00000ac0: 7c04 6a05 7c04 6a06 7c04 6a04 7c05 6404  |.j.|.j.|.j.|.d.
+00000ad0: 9c04 7d03 7c03 5300 2907 4eda 0554 4845  ..}.|.S.).N..THE
+00000ae0: 4d45 da05 4c49 4748 5472 1500 0000 2904  ME..LIGHTr....).
+00000af0: 7a10 6261 636b 6772 6f75 6e64 2d63 6f6c  z.background-col
+00000b00: 6f72 7a0a 7465 7874 2d63 6f6c 6f72 7a0c  orz.text-colorz.
+00000b10: 6163 6365 6e74 2d63 6f6c 6f72 7a0b 6963  accent-colorz.ic
+00000b20: 6f6e 732d 636f 6c6f 72da 0444 4152 4b72  ons-color..DARKr
+00000b30: 0100 0000 2913 da09 5153 6574 7469 6e67  ....)...QSetting
+00000b40: 73da 0576 616c 7565 723c 0000 0072 1e00  s..valuer<...r..
+00000b50: 0000 721d 0000 0072 1b00 0000 721c 0000  ..r....r....r...
+00000b60: 0072 3300 0000 da02 7569 da06 7468 656d  .r3.....ui..them
+00000b70: 6573 da0c 6465 6661 756c 7454 6865 6d65  es..defaultTheme
+00000b80: da04 6e61 6d65 da08 7365 7456 616c 7565  ..name..setValue
+00000b90: da0f 6261 636b 6772 6f75 6e64 436f 6c6f  ..backgroundColo
+00000ba0: 72da 0974 6578 7443 6f6c 6f72 da0b 6163  r..textColor..ac
+00000bb0: 6365 6e74 436f 6c6f 72da 0e63 7265 6174  centColor..creat
+00000bc0: 654e 6577 4963 6f6e 73da 0a69 636f 6e73  eNewIcons..icons
+00000bd0: 436f 6c6f 72da 036c 656e 2909 722e 0000  Color..len).r...
+00000be0: 00da 0873 6574 7469 6e67 7372 3f00 0000  ...settingsr?...
+00000bf0: 5a10 6375 7272 656e 7454 6865 6d65 496e  Z.currentThemeIn
+00000c00: 666f da05 7468 656d 6572 4d00 0000 721b  fo..themerM...r.
+00000c10: 0000 0072 1c00 0000 721d 0000 0072 1000  ...r....r....r..
+00000c20: 0000 7210 0000 0072 1100 0000 da13 6765  ..r....r......ge
+00000c30: 7443 7572 7265 6e74 5468 656d 6549 6e66  tCurrentThemeInf
+00000c40: 6f69 0000 0073 4800 0000 0001 0602 0a02  oi...sH.........
+00000c50: 0402 0801 0601 0a01 0601 0a02 0602 1602  ................
+00000c60: 0801 0601 0a01 0601 0a02 0602 1603 0c01  ................
+00000c70: 1002 0e01 0601 0601 0602 0601 0a01 0602  ................
+00000c80: 0802 0402 1002 0e01 0601 0c01 0802 0602  ................
+00000c90: 1402 7a27 4372 6561 7465 436f 6c6f 7256  ..z'CreateColorV
+00000ca0: 6172 6961 626c 652e 6765 7443 7572 7265  ariable.getCurre
+00000cb0: 6e74 5468 656d 6549 6e66 6f63 0100 0000  ntThemeInfoc....
+00000cc0: 0000 0000 0000 0000 0900 0000 2000 0000  ............ ...
+00000cd0: 4300 0000 73e2 0200 0074 0083 007d 017c  C...s....t...}.|
+00000ce0: 01a0 0164 01a1 017d 0264 027d 037c 0264  ...d...}.d.}.|.d
+00000cf0: 036b 0272 2674 0283 007d 0490 016e 3a7c  .k.r&t...}...n:|
+00000d00: 0264 046b 0272 3874 0383 007d 0490 016e  .d.k.r8t...}...n
+00000d10: 287c 006a 046a 0544 005d 4a7d 057c 056a  (|.j.j.D.]J}.|.j
+00000d20: 0673 547c 056a 077c 026b 0272 407c 01a0  .sT|.j.|.k.r@|..
+00000d30: 0864 017c 056a 07a1 0201 007c 057d 047c  .d.|.j.....|.}.|
+00000d40: 056a 097c 045f 0a7c 056a 0b7c 045f 0c7c  .j.|._.|.j.|._.|
+00000d50: 056a 0d7c 045f 0e7c 046a 0f7c 045f 1064  .j.|._.|.j.|._.d
+00000d60: 057d 0371 407c 0373 9674 0283 007d 0474  .}.q@|.s.t...}.t
+00000d70: 117c 046a 0a64 0683 027c 045f 1274 117c  .|.j.d...|._.t.|
+00000d80: 046a 0a64 0783 027c 045f 1374 117c 046a  .j.d...|._.t.|.j
+00000d90: 0a64 0883 027c 045f 1474 117c 046a 0a64  .d...|._.t.|.j.d
+00000da0: 0983 027c 045f 1574 117c 046a 0a64 0a83  ...|._.t.|.j.d..
+00000db0: 027c 045f 1674 117c 046a 0a64 0b83 027c  .|._.t.|.j.d...|
+00000dc0: 045f 1774 117c 046a 0c64 0683 027c 045f  ._.t.|.j.d...|._
+00000dd0: 1874 117c 046a 0c64 0783 027c 045f 1974  .t.|.j.d...|._.t
+00000de0: 117c 046a 0c64 0883 027c 045f 1a74 117c  .|.j.d...|._.t.|
+00000df0: 046a 0c64 0983 027c 045f 1b74 117c 046a  .j.d...|._.t.|.j
+00000e00: 0e64 0683 027c 045f 1c74 117c 046a 0e64  .d...|._.t.|.j.d
+00000e10: 0783 027c 045f 1d74 117c 046a 0e64 0883  ...|._.t.|.j.d..
+00000e20: 027c 045f 1e74 117c 046a 0e64 0983 027c  .|._.t.|.j.d...|
+00000e30: 045f 1f64 0c7c 045f 2074 2183 007c 005f  ._.d.|._ t!..|._
+00000e40: 227c 046a 127c 006a 225f 237c 046a 137c  "|.j.|.j"_#|.j.|
+00000e50: 006a 225f 247c 046a 147c 006a 225f 257c  .j"_$|.j.|.j"_%|
+00000e60: 046a 157c 006a 225f 267c 046a 167c 006a  .j.|.j"_&|.j.|.j
+00000e70: 225f 277c 046a 177c 006a 225f 287c 046a  "_'|.j.|.j"_(|.j
+00000e80: 187c 006a 225f 297c 046a 197c 006a 225f  .|.j"_)|.j.|.j"_
+00000e90: 2a7c 046a 1a7c 006a 225f 2b7c 046a 1b7c  *|.j.|.j"_+|.j.|
+00000ea0: 006a 225f 2c7c 046a 1c7c 006a 225f 2d7c  .j"_,|.j.|.j"_-|
+00000eb0: 046a 1d7c 006a 225f 2e7c 046a 1e7c 006a  .j.|.j"_.|.j.|.j
+00000ec0: 225f 2f7c 046a 1f7c 006a 225f 307c 046a  "_/|.j.|.j"_0|.j
+00000ed0: 207c 006a 225f 3174 326a 33a0 3474 326a   |.j"_1t2j3.4t2j
+00000ee0: 33a0 3574 32a0 36a1 0064 0da1 02a1 017d  3.5t2.6..d.....}
+00000ef0: 0674 326a 33a0 377c 06a1 0190 0273 3074  .t2j3.7|.....s0t
+00000f00: 32a0 387c 06a1 0101 0074 326a 33a0 3474  2.8|.....t2j3.4t
+00000f10: 326a 33a0 357c 0664 0ea1 02a1 017d 0774  2j3.5|.d.....}.t
+00000f20: 397c 0764 0f83 027d 0874 3a64 107c 046a  9|.d...}.t:d.|.j
+00000f30: 129b 0064 117c 046a 139b 0064 127c 046a  ...d.|.j...d.|.j
+00000f40: 149b 0064 137c 046a 159b 0064 147c 046a  ...d.|.j...d.|.j
+00000f50: 169b 0064 157c 046a 179b 0064 167c 046a  ...d.|.j...d.|.j
+00000f60: 189b 0064 177c 046a 199b 0064 187c 046a  ...d.|.j...d.|.j
+00000f70: 1a9b 0064 197c 046a 1b9b 0064 1a7c 046a  ...d.|.j...d.|.j
+00000f80: 1c9b 0064 1b7c 046a 1d9b 0064 1c7c 046a  ...d.|.j...d.|.j
+00000f90: 1e9b 0064 1d7c 046a 1f9b 0064 1e7c 046a  ...d.|.j...d.|.j
+00000fa0: 209b 0064 1f9d 1f7c 0864 208d 0201 007c   ..d...|.d ....|
+00000fb0: 08a0 3ba1 0001 0064 0053 0029 214e 723f  ..;....d.S.)!Nr?
+00000fc0: 0000 0046 7240 0000 0072 4100 0000 5472  ...Fr@...rA...Tr
+00000fd0: 0400 0000 7218 0000 0072 1600 0000 7219  ....r....r....r.
+00000fe0: 0000 0072 1700 0000 7203 0000 0072 1a00  ...r....r....r..
+00000ff0: 0000 da03 5153 537a 0f5f 7661 7269 6162  ....QSSz._variab
+00001000: 6c65 732e 7363 7373 da01 777a e00a 2020  les.scss..wz..  
+00001010: 2020 2020 2020 2f2f 3d3d 3d3d 3d3d 3d3d        //========
 00001020: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
-00001030: 3d2f 2f0a 2020 2020 2020 2020 2f2f 2046  =//.        // F
-00001040: 494c 4520 4155 544f 2d47 454e 4552 4154  ILE AUTO-GENERAT
-00001050: 4544 2c20 414e 5920 4348 414e 4745 5320  ED, ANY CHANGES 
-00001060: 4d41 4445 2057 494c 4c20 4245 204c 4f53  MADE WILL BE LOS
-00001070: 5420 2f2f 0a20 2020 2020 2020 202f 2f3d  T //.        //=
-00001080: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
-00001090: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
+00001030: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
+00001040: 3d3d 3d3d 3d3d 3d3d 3d3d 3d2f 2f0a 2020  ===========//.  
+00001050: 2020 2020 2020 2f2f 2046 494c 4520 4155        // FILE AU
+00001060: 544f 2d47 454e 4552 4154 4544 2c20 414e  TO-GENERATED, AN
+00001070: 5920 4348 414e 4745 5320 4d41 4445 2057  Y CHANGES MADE W
+00001080: 494c 4c20 4245 204c 4f53 5420 2f2f 0a20  ILL BE LOST //. 
+00001090: 2020 2020 2020 202f 2f3d 3d3d 3d3d 3d3d         //=======
 000010a0: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
-000010b0: 3d3d 3d2f 2f0a 2020 2020 2020 2020 2443  ===//.        $C
-000010c0: 4f4c 4f52 5f42 4143 4b47 524f 554e 445f  OLOR_BACKGROUND_
-000010d0: 313a 207a 1f3b 0a20 2020 2020 2020 2024  1: z.;.        $
-000010e0: 434f 4c4f 525f 4241 434b 4752 4f55 4e44  COLOR_BACKGROUND
-000010f0: 5f32 3a20 7a1f 3b0a 2020 2020 2020 2020  _2: z.;.        
-00001100: 2443 4f4c 4f52 5f42 4143 4b47 524f 554e  $COLOR_BACKGROUN
-00001110: 445f 333a 207a 203b 200a 2020 2020 2020  D_3: z ; .      
-00001120: 2020 2443 4f4c 4f52 5f42 4143 4b47 524f    $COLOR_BACKGRO
-00001130: 554e 445f 343a 207a 203b 200a 2020 2020  UND_4: z ; .    
-00001140: 2020 2020 2443 4f4c 4f52 5f42 4143 4b47      $COLOR_BACKG
-00001150: 524f 554e 445f 353a 207a 203b 200a 2020  ROUND_5: z ; .  
-00001160: 2020 2020 2020 2443 4f4c 4f52 5f42 4143        $COLOR_BAC
-00001170: 4b47 524f 554e 445f 363a 207a 1a3b 200a  KGROUND_6: z.; .
-00001180: 2020 2020 2020 2020 2443 4f4c 4f52 5f54          $COLOR_T
-00001190: 4558 545f 313a 207a 193b 0a20 2020 2020  EXT_1: z.;.     
-000011a0: 2020 2024 434f 4c4f 525f 5445 5854 5f32     $COLOR_TEXT_2
-000011b0: 3a20 7a19 3b0a 2020 2020 2020 2020 2443  : z.;.        $C
-000011c0: 4f4c 4f52 5f54 4558 545f 333a 207a 193b  OLOR_TEXT_3: z.;
-000011d0: 0a20 2020 2020 2020 2024 434f 4c4f 525f  .        $COLOR_
-000011e0: 5445 5854 5f34 3a20 7a1b 3b0a 2020 2020  TEXT_4: z.;.    
-000011f0: 2020 2020 2443 4f4c 4f52 5f41 4343 454e      $COLOR_ACCEN
-00001200: 545f 313a 207a 1b3b 0a20 2020 2020 2020  T_1: z.;.       
-00001210: 2024 434f 4c4f 525f 4143 4345 4e54 5f32   $COLOR_ACCENT_2
-00001220: 3a20 7a1b 3b0a 2020 2020 2020 2020 2443  : z.;.        $C
-00001230: 4f4c 4f52 5f41 4343 454e 545f 333a 207a  OLOR_ACCENT_3: z
-00001240: 1b3b 0a20 2020 2020 2020 2024 434f 4c4f  .;.        $COLO
-00001250: 525f 4143 4345 4e54 5f34 3a20 619b 0100  R_ACCENT_4: a...
-00001260: 003b 0a20 2020 2020 2020 2024 4f50 4143  .;.        $OPAC
-00001270: 4954 595f 544f 4f4c 5449 503a 2032 3330  ITY_TOOLTIP: 230
-00001280: 3b0a 2020 2020 2020 2020 2453 495a 455f  ;.        $SIZE_
-00001290: 424f 5244 4552 5f52 4144 4955 533a 2034  BORDER_RADIUS: 4
-000012a0: 7078 3b0a 2020 2020 2020 2020 2442 4f52  px;.        $BOR
-000012b0: 4445 525f 313a 2031 7078 2073 6f6c 6964  DER_1: 1px solid
-000012c0: 2024 434f 4c4f 525f 4241 434b 4752 4f55   $COLOR_BACKGROU
-000012d0: 4e44 5f31 3b0a 2020 2020 2020 2020 2442  ND_1;.        $B
-000012e0: 4f52 4445 525f 323a 2031 7078 2073 6f6c  ORDER_2: 1px sol
-000012f0: 6964 2024 434f 4c4f 525f 4241 434b 4752  id $COLOR_BACKGR
-00001300: 4f55 4e44 5f34 3b0a 2020 2020 2020 2020  OUND_4;.        
-00001310: 2442 4f52 4445 525f 333a 2031 7078 2073  $BORDER_3: 1px s
-00001320: 6f6c 6964 2024 434f 4c4f 525f 4241 434b  olid $COLOR_BACK
-00001330: 4752 4f55 4e44 5f36 3b0a 2020 2020 2020  GROUND_6;.      
-00001340: 2020 2442 4f52 4445 525f 5345 4c45 4354    $BORDER_SELECT
-00001350: 494f 4e5f 333a 2031 7078 2073 6f6c 6964  ION_3: 1px solid
-00001360: 2024 434f 4c4f 525f 4143 4345 4e54 5f33   $COLOR_ACCENT_3
-00001370: 3b0a 2020 2020 2020 2020 2442 4f52 4445  ;.        $BORDE
-00001380: 525f 5345 4c45 4354 494f 4e5f 323a 2031  R_SELECTION_2: 1
-00001390: 7078 2073 6f6c 6964 2024 434f 4c4f 525f  px solid $COLOR_
-000013a0: 4143 4345 4e54 5f32 3b0a 2020 2020 2020  ACCENT_2;.      
-000013b0: 2020 2442 4f52 4445 525f 5345 4c45 4354    $BORDER_SELECT
-000013c0: 494f 4e5f 313a 2031 7078 2073 6f6c 6964  ION_1: 1px solid
-000013d0: 2024 434f 4c4f 525f 4143 4345 4e54 5f31   $COLOR_ACCENT_1
-000013e0: 3b0a 2020 2020 2020 2020 2450 4154 485f  ;.        $PATH_
-000013f0: 5245 534f 5552 4345 533a 2027 7a9e 273b  RESOURCES: 'z.';
-00001400: 0a20 2020 2020 2020 202f 2f3d 3d3d 3d3d  .        //=====
-00001410: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
-00001420: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
-00001430: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 2f2f  ==============//
-00001440: 0a20 2020 2020 2020 202f 2f20 454e 4420  .        // END 
-00001450: 2f2f 0a20 2020 2020 2020 202f 2f3d 3d3d  //.        //===
-00001460: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
-00001470: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
+000010b0: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
+000010c0: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d2f 2f0a  =============//.
+000010d0: 2020 2020 2020 2020 2443 4f4c 4f52 5f42          $COLOR_B
+000010e0: 4143 4b47 524f 554e 445f 313a 207a 1f3b  ACKGROUND_1: z.;
+000010f0: 0a20 2020 2020 2020 2024 434f 4c4f 525f  .        $COLOR_
+00001100: 4241 434b 4752 4f55 4e44 5f32 3a20 7a1f  BACKGROUND_2: z.
+00001110: 3b0a 2020 2020 2020 2020 2443 4f4c 4f52  ;.        $COLOR
+00001120: 5f42 4143 4b47 524f 554e 445f 333a 207a  _BACKGROUND_3: z
+00001130: 203b 200a 2020 2020 2020 2020 2443 4f4c   ; .        $COL
+00001140: 4f52 5f42 4143 4b47 524f 554e 445f 343a  OR_BACKGROUND_4:
+00001150: 207a 203b 200a 2020 2020 2020 2020 2443   z ; .        $C
+00001160: 4f4c 4f52 5f42 4143 4b47 524f 554e 445f  OLOR_BACKGROUND_
+00001170: 353a 207a 203b 200a 2020 2020 2020 2020  5: z ; .        
+00001180: 2443 4f4c 4f52 5f42 4143 4b47 524f 554e  $COLOR_BACKGROUN
+00001190: 445f 363a 207a 1a3b 200a 2020 2020 2020  D_6: z.; .      
+000011a0: 2020 2443 4f4c 4f52 5f54 4558 545f 313a    $COLOR_TEXT_1:
+000011b0: 207a 193b 0a20 2020 2020 2020 2024 434f   z.;.        $CO
+000011c0: 4c4f 525f 5445 5854 5f32 3a20 7a19 3b0a  LOR_TEXT_2: z.;.
+000011d0: 2020 2020 2020 2020 2443 4f4c 4f52 5f54          $COLOR_T
+000011e0: 4558 545f 333a 207a 193b 0a20 2020 2020  EXT_3: z.;.     
+000011f0: 2020 2024 434f 4c4f 525f 5445 5854 5f34     $COLOR_TEXT_4
+00001200: 3a20 7a1b 3b0a 2020 2020 2020 2020 2443  : z.;.        $C
+00001210: 4f4c 4f52 5f41 4343 454e 545f 313a 207a  OLOR_ACCENT_1: z
+00001220: 1b3b 0a20 2020 2020 2020 2024 434f 4c4f  .;.        $COLO
+00001230: 525f 4143 4345 4e54 5f32 3a20 7a1b 3b0a  R_ACCENT_2: z.;.
+00001240: 2020 2020 2020 2020 2443 4f4c 4f52 5f41          $COLOR_A
+00001250: 4343 454e 545f 333a 207a 1b3b 0a20 2020  CCENT_3: z.;.   
+00001260: 2020 2020 2024 434f 4c4f 525f 4143 4345       $COLOR_ACCE
+00001270: 4e54 5f34 3a20 619b 0100 003b 0a20 2020  NT_4: a....;.   
+00001280: 2020 2020 2024 4f50 4143 4954 595f 544f       $OPACITY_TO
+00001290: 4f4c 5449 503a 2032 3330 3b0a 2020 2020  OLTIP: 230;.    
+000012a0: 2020 2020 2453 495a 455f 424f 5244 4552      $SIZE_BORDER
+000012b0: 5f52 4144 4955 533a 2034 7078 3b0a 2020  _RADIUS: 4px;.  
+000012c0: 2020 2020 2020 2442 4f52 4445 525f 313a        $BORDER_1:
+000012d0: 2031 7078 2073 6f6c 6964 2024 434f 4c4f   1px solid $COLO
+000012e0: 525f 4241 434b 4752 4f55 4e44 5f31 3b0a  R_BACKGROUND_1;.
+000012f0: 2020 2020 2020 2020 2442 4f52 4445 525f          $BORDER_
+00001300: 323a 2031 7078 2073 6f6c 6964 2024 434f  2: 1px solid $CO
+00001310: 4c4f 525f 4241 434b 4752 4f55 4e44 5f34  LOR_BACKGROUND_4
+00001320: 3b0a 2020 2020 2020 2020 2442 4f52 4445  ;.        $BORDE
+00001330: 525f 333a 2031 7078 2073 6f6c 6964 2024  R_3: 1px solid $
+00001340: 434f 4c4f 525f 4241 434b 4752 4f55 4e44  COLOR_BACKGROUND
+00001350: 5f36 3b0a 2020 2020 2020 2020 2442 4f52  _6;.        $BOR
+00001360: 4445 525f 5345 4c45 4354 494f 4e5f 333a  DER_SELECTION_3:
+00001370: 2031 7078 2073 6f6c 6964 2024 434f 4c4f   1px solid $COLO
+00001380: 525f 4143 4345 4e54 5f33 3b0a 2020 2020  R_ACCENT_3;.    
+00001390: 2020 2020 2442 4f52 4445 525f 5345 4c45      $BORDER_SELE
+000013a0: 4354 494f 4e5f 323a 2031 7078 2073 6f6c  CTION_2: 1px sol
+000013b0: 6964 2024 434f 4c4f 525f 4143 4345 4e54  id $COLOR_ACCENT
+000013c0: 5f32 3b0a 2020 2020 2020 2020 2442 4f52  _2;.        $BOR
+000013d0: 4445 525f 5345 4c45 4354 494f 4e5f 313a  DER_SELECTION_1:
+000013e0: 2031 7078 2073 6f6c 6964 2024 434f 4c4f   1px solid $COLO
+000013f0: 525f 4143 4345 4e54 5f31 3b0a 2020 2020  R_ACCENT_1;.    
+00001400: 2020 2020 2450 4154 485f 5245 534f 5552      $PATH_RESOUR
+00001410: 4345 533a 2027 7a9e 273b 0a20 2020 2020  CES: 'z.';.     
+00001420: 2020 202f 2f3d 3d3d 3d3d 3d3d 3d3d 3d3d     //===========
+00001430: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
+00001440: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
+00001450: 3d3d 3d3d 3d3d 3d3d 2f2f 0a20 2020 2020  ========//.     
+00001460: 2020 202f 2f20 454e 4420 2f2f 0a20 2020     // END //.   
+00001470: 2020 2020 202f 2f3d 3d3d 3d3d 3d3d 3d3d       //=========
 00001480: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
-00001490: 3d2f 2f0a 2020 2020 2020 2020 2901 da04  =//.        )...
-000014a0: 6669 6c65 293c 7242 0000 0072 4300 0000  file)<rB...rC...
-000014b0: 723c 0000 0072 3300 0000 7244 0000 0072  r<...r3...rD...r
-000014c0: 4500 0000 7246 0000 0072 4700 0000 7248  E...rF...rG...rH
-000014d0: 0000 0072 4900 0000 721b 0000 0072 4a00  ...rI...r....rJ.
-000014e0: 0000 721c 0000 0072 4b00 0000 721d 0000  ..r....rK...r...
-000014f0: 0072 4d00 0000 721e 0000 0072 1200 0000  .rM...r....r....
-00001500: 721f 0000 0072 2000 0000 7221 0000 0072  r....r ...r!...r
-00001510: 2200 0000 7223 0000 0072 2400 0000 7225  "...r#...r$...r%
-00001520: 0000 0072 2600 0000 7227 0000 0072 2800  ...r&...r'...r(.
-00001530: 0000 7229 0000 0072 2a00 0000 722b 0000  ..r)...r*...r+..
-00001540: 0072 2c00 0000 722d 0000 00da 064f 626a  .r,...r-.....Obj
-00001550: 6563 7472 5000 0000 da12 434f 4c4f 525f  ectrP.....COLOR_
-00001560: 4241 434b 4752 4f55 4e44 5f31 5a12 434f  BACKGROUND_1Z.CO
-00001570: 4c4f 525f 4241 434b 4752 4f55 4e44 5f32  LOR_BACKGROUND_2
-00001580: da12 434f 4c4f 525f 4241 434b 4752 4f55  ..COLOR_BACKGROU
-00001590: 4e44 5f33 5a12 434f 4c4f 525f 4241 434b  ND_3Z.COLOR_BACK
-000015a0: 4752 4f55 4e44 5f34 5a12 434f 4c4f 525f  GROUND_4Z.COLOR_
-000015b0: 4241 434b 4752 4f55 4e44 5f35 da12 434f  BACKGROUND_5..CO
-000015c0: 4c4f 525f 4241 434b 4752 4f55 4e44 5f36  LOR_BACKGROUND_6
-000015d0: da0c 434f 4c4f 525f 5445 5854 5f31 5a0c  ..COLOR_TEXT_1Z.
-000015e0: 434f 4c4f 525f 5445 5854 5f32 5a0c 434f  COLOR_TEXT_2Z.CO
-000015f0: 4c4f 525f 5445 5854 5f33 5a0c 434f 4c4f  LOR_TEXT_3Z.COLO
-00001600: 525f 5445 5854 5f34 da0e 434f 4c4f 525f  R_TEXT_4..COLOR_
-00001610: 4143 4345 4e54 5f31 5a0e 434f 4c4f 525f  ACCENT_1Z.COLOR_
-00001620: 4143 4345 4e54 5f32 5a0e 434f 4c4f 525f  ACCENT_2Z.COLOR_
-00001630: 4143 4345 4e54 5f33 5a0e 434f 4c4f 525f  ACCENT_3Z.COLOR_
-00001640: 4143 4345 4e54 5f34 5a0e 5041 5448 5f52  ACCENT_4Z.PATH_R
-00001650: 4553 4f55 5243 4553 da02 6f73 da04 7061  ESOURCES..os..pa
-00001660: 7468 da07 6162 7370 6174 68da 046a 6f69  th..abspath..joi
-00001670: 6eda 0667 6574 6377 64da 0665 7869 7374  n..getcwd..exist
-00001680: 73da 086d 616b 6564 6972 73da 046f 7065  s..makedirs..ope
-00001690: 6eda 0570 7269 6e74 da05 636c 6f73 6529  n..print..close)
-000016a0: 0972 2e00 0000 724f 0000 0072 3f00 0000  .r....rO...r?...
-000016b0: 5a0a 7468 656d 6546 6f75 6e64 7250 0000  Z.themeFoundrP..
-000016c0: 0072 4500 0000 5a0b 7363 7373 5f66 6f6c  .rE...Z.scss_fol
-000016d0: 6465 72da 0973 6373 735f 7061 7468 da01  der..scss_path..
-000016e0: 6672 1000 0000 7210 0000 0072 1100 0000  fr....r....r....
-000016f0: da0f 4372 6561 7465 5661 7269 6162 6c65  ..CreateVariable
-00001700: 73a2 0000 0073 b000 0000 0001 0602 0a01  s....s..........
-00001710: 0401 0801 0a02 0801 0a03 0c01 1002 0e02  ................
-00001720: 0401 0801 0801 0801 0801 0602 0401 0603  ................
-00001730: 0e01 0e01 0e01 0e01 0e01 0e02 0e01 0e01  ................
-00001740: 0e01 0e02 0e01 0e01 0e01 0e02 0603 0801  ................
-00001750: 0a01 0a01 0a01 0a01 0a01 0a02 0a01 0a01  ................
-00001760: 0a01 0a02 0a01 0a01 0a01 0a02 0a03 1a01  ................
-00001770: 0e01 0a02 1601 0a01 0404 04fc 0405 04fb  ................
-00001780: 0406 04fa 0407 04f9 0408 04f8 0409 04f7  ................
-00001790: 040a 04f6 040b 04f5 040c 04f4 040d 04f3  ................
-000017a0: 040e 04f2 040f 04f1 0410 04f0 0411 04ef  ................
-000017b0: 041a 04e6 061e 02e2 0620 7a23 4372 6561  ......... z#Crea
-000017c0: 7465 436f 6c6f 7256 6172 6961 626c 652e  teColorVariable.
-000017d0: 4372 6561 7465 5661 7269 6162 6c65 7329  CreateVariables)
-000017e0: 014e 2907 7230 0000 0072 3100 0000 7232  .N).r0...r1...r2
-000017f0: 0000 0072 2f00 0000 7251 0000 0072 6700  ...r/...rQ...rg.
-00001800: 0000 723b 0000 0072 1000 0000 7210 0000  ..r;...r....r...
-00001810: 0072 3800 0000 7211 0000 0072 3d00 0000  .r8...r....r=...
-00001820: 6500 0000 7306 0000 0008 010e 0308 3972  e...s.........9r
-00001830: 3d00 0000 6300 0000 0000 0000 0000 0000  =...c...........
-00001840: 0000 0000 0001 0000 0040 0000 0073 0c00  .........@...s..
-00001850: 0000 6500 5a01 6400 5a02 6401 5300 2902  ..e.Z.d.Z.d.S.).
-00001860: 7255 0000 004e 2903 7230 0000 0072 3100  rU...N).r0...r1.
-00001870: 0000 7232 0000 0072 1000 0000 7210 0000  ..r2...r....r...
-00001880: 0072 1000 0000 7211 0000 0072 5500 0000  .r....r....rU...
-00001890: 1201 0000 7302 0000 0008 0172 5500 0000  ....s......rU...
-000018a0: 2901 7203 0000 0029 1172 5b00 0000 da03  ).r....).r[.....
-000018b0: 7379 73da 0b71 7470 792e 5174 436f 7265  sys..qtpy.QtCore
-000018c0: 5a11 6d61 7470 6c6f 746c 6962 2e63 6f6c  Z.matplotlib.col
-000018d0: 6f72 73da 0663 6f6c 6f72 7372 0700 0000  ors..colorsr....
-000018e0: 7209 0000 0072 4200 0000 724f 0000 0072  r....rB...rO...r
-000018f0: 1200 0000 720a 0000 0072 1400 0000 7233  ....r....r....r3
-00001900: 0000 0072 3c00 0000 723d 0000 00da 066f  ...r<...r=.....o
-00001910: 626a 6563 7472 5500 0000 7210 0000 0072  bjectrU...r....r
-00001920: 1000 0000 7210 0000 0072 1100 0000 da08  ....r....r......
-00001930: 3c6d 6f64 756c 653e 0800 0000 731a 0000  <module>....s...
-00001940: 0008 0108 0d08 030c 0108 0206 020a 1908  ................
-00001950: 040e 1a10 0410 0c0e 7f00 2e              ...........
+00001490: 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d 3d3d  ================
+000014a0: 3d3d 3d3d 3d3d 3d3d 3d3d 3d2f 2f0a 2020  ===========//.  
+000014b0: 2020 2020 2020 2901 da04 6669 6c65 293c        )...file)<
+000014c0: 7242 0000 0072 4300 0000 723c 0000 0072  rB...rC...r<...r
+000014d0: 3300 0000 7244 0000 0072 4500 0000 7246  3...rD...rE...rF
+000014e0: 0000 0072 4700 0000 7248 0000 0072 4900  ...rG...rH...rI.
+000014f0: 0000 721b 0000 0072 4a00 0000 721c 0000  ..r....rJ...r...
+00001500: 0072 4b00 0000 721d 0000 0072 4d00 0000  .rK...r....rM...
+00001510: 721e 0000 0072 1200 0000 721f 0000 0072  r....r....r....r
+00001520: 2000 0000 7221 0000 0072 2200 0000 7223   ...r!...r"...r#
+00001530: 0000 0072 2400 0000 7225 0000 0072 2600  ...r$...r%...r&.
+00001540: 0000 7227 0000 0072 2800 0000 7229 0000  ..r'...r(...r)..
+00001550: 0072 2a00 0000 722b 0000 0072 2c00 0000  .r*...r+...r,...
+00001560: 722d 0000 00da 064f 626a 6563 7472 5000  r-.....ObjectrP.
+00001570: 0000 da12 434f 4c4f 525f 4241 434b 4752  ....COLOR_BACKGR
+00001580: 4f55 4e44 5f31 5a12 434f 4c4f 525f 4241  OUND_1Z.COLOR_BA
+00001590: 434b 4752 4f55 4e44 5f32 da12 434f 4c4f  CKGROUND_2..COLO
+000015a0: 525f 4241 434b 4752 4f55 4e44 5f33 5a12  R_BACKGROUND_3Z.
+000015b0: 434f 4c4f 525f 4241 434b 4752 4f55 4e44  COLOR_BACKGROUND
+000015c0: 5f34 5a12 434f 4c4f 525f 4241 434b 4752  _4Z.COLOR_BACKGR
+000015d0: 4f55 4e44 5f35 da12 434f 4c4f 525f 4241  OUND_5..COLOR_BA
+000015e0: 434b 4752 4f55 4e44 5f36 da0c 434f 4c4f  CKGROUND_6..COLO
+000015f0: 525f 5445 5854 5f31 5a0c 434f 4c4f 525f  R_TEXT_1Z.COLOR_
+00001600: 5445 5854 5f32 5a0c 434f 4c4f 525f 5445  TEXT_2Z.COLOR_TE
+00001610: 5854 5f33 5a0c 434f 4c4f 525f 5445 5854  XT_3Z.COLOR_TEXT
+00001620: 5f34 da0e 434f 4c4f 525f 4143 4345 4e54  _4..COLOR_ACCENT
+00001630: 5f31 5a0e 434f 4c4f 525f 4143 4345 4e54  _1Z.COLOR_ACCENT
+00001640: 5f32 5a0e 434f 4c4f 525f 4143 4345 4e54  _2Z.COLOR_ACCENT
+00001650: 5f33 5a0e 434f 4c4f 525f 4143 4345 4e54  _3Z.COLOR_ACCENT
+00001660: 5f34 5a0e 5041 5448 5f52 4553 4f55 5243  _4Z.PATH_RESOURC
+00001670: 4553 da02 6f73 da04 7061 7468 da07 6162  ES..os..path..ab
+00001680: 7370 6174 68da 046a 6f69 6eda 0667 6574  spath..join..get
+00001690: 6377 64da 0665 7869 7374 73da 086d 616b  cwd..exists..mak
+000016a0: 6564 6972 73da 046f 7065 6eda 0570 7269  edirs..open..pri
+000016b0: 6e74 da05 636c 6f73 6529 0972 2e00 0000  nt..close).r....
+000016c0: 724f 0000 0072 3f00 0000 5a0a 7468 656d  rO...r?...Z.them
+000016d0: 6546 6f75 6e64 7250 0000 0072 4500 0000  eFoundrP...rE...
+000016e0: 5a0b 7363 7373 5f66 6f6c 6465 72da 0973  Z.scss_folder..s
+000016f0: 6373 735f 7061 7468 da01 6672 1000 0000  css_path..fr....
+00001700: 7210 0000 0072 1100 0000 da0f 4372 6561  r....r......Crea
+00001710: 7465 5661 7269 6162 6c65 73a2 0000 0073  teVariables....s
+00001720: b000 0000 0001 0602 0a01 0401 0801 0a02  ................
+00001730: 0801 0a03 0c01 1002 0e02 0401 0801 0801  ................
+00001740: 0801 0801 0602 0401 0603 0e01 0e01 0e01  ................
+00001750: 0e01 0e01 0e02 0e01 0e01 0e01 0e02 0e01  ................
+00001760: 0e01 0e01 0e02 0603 0801 0a01 0a01 0a01  ................
+00001770: 0a01 0a01 0a02 0a01 0a01 0a01 0a02 0a01  ................
+00001780: 0a01 0a01 0a02 0a03 1a01 0e01 0a02 1601  ................
+00001790: 0a01 0404 04fc 0405 04fb 0406 04fa 0407  ................
+000017a0: 04f9 0408 04f8 0409 04f7 040a 04f6 040b  ................
+000017b0: 04f5 040c 04f4 040d 04f3 040e 04f2 040f  ................
+000017c0: 04f1 0410 04f0 0411 04ef 041a 04e6 061e  ................
+000017d0: 02e2 0620 7a23 4372 6561 7465 436f 6c6f  ... z#CreateColo
+000017e0: 7256 6172 6961 626c 652e 4372 6561 7465  rVariable.Create
+000017f0: 5661 7269 6162 6c65 7329 014e 2907 7230  Variables).N).r0
+00001800: 0000 0072 3100 0000 7232 0000 0072 2f00  ...r1...r2...r/.
+00001810: 0000 7251 0000 0072 6700 0000 723b 0000  ..rQ...rg...r;..
+00001820: 0072 1000 0000 7210 0000 0072 3800 0000  .r....r....r8...
+00001830: 7211 0000 0072 3d00 0000 6500 0000 7306  r....r=...e...s.
+00001840: 0000 0008 010e 0308 3972 3d00 0000 6300  ........9r=...c.
+00001850: 0000 0000 0000 0000 0000 0000 0000 0001  ................
+00001860: 0000 0040 0000 0073 0c00 0000 6500 5a01  ...@...s....e.Z.
+00001870: 6400 5a02 6401 5300 2902 7255 0000 004e  d.Z.d.S.).rU...N
+00001880: 2903 7230 0000 0072 3100 0000 7232 0000  ).r0...r1...r2..
+00001890: 0072 1000 0000 7210 0000 0072 1000 0000  .r....r....r....
+000018a0: 7211 0000 0072 5500 0000 1201 0000 7302  r....rU.......s.
+000018b0: 0000 0008 0172 5500 0000 2901 7203 0000  .....rU...).r...
+000018c0: 0029 1172 5b00 0000 da03 7379 73da 0b71  .).r[.....sys..q
+000018d0: 7470 792e 5174 436f 7265 5a11 6d61 7470  tpy.QtCoreZ.matp
+000018e0: 6c6f 746c 6962 2e63 6f6c 6f72 73da 0663  lotlib.colors..c
+000018f0: 6f6c 6f72 7372 0700 0000 7209 0000 0072  olorsr....r....r
+00001900: 4200 0000 724f 0000 0072 1200 0000 720a  B...rO...r....r.
+00001910: 0000 0072 1400 0000 7233 0000 0072 3c00  ...r....r3...r<.
+00001920: 0000 723d 0000 00da 066f 626a 6563 7472  ..r=.....objectr
+00001930: 5500 0000 7210 0000 0072 1000 0000 7210  U...r....r....r.
+00001940: 0000 0072 1100 0000 da08 3c6d 6f64 756c  ...r......<modul
+00001950: 653e 0800 0000 731a 0000 0008 0108 0d08  e>....s.........
+00001960: 030c 0108 0206 020a 1908 040e 1a10 0410  ................
+00001970: 0c0e 7f00 2e                             .....
```

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-39.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/colorsystem.cpython-39.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/resources_rc.cpython-39.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/resources_rc.cpython-39.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/__pycache__/sassCompiler.cpython-39.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/__pycache__/sassCompiler.cpython-39.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/_styles.scss` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/_styles.scss`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/colorsystem.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/colorsystem.py`

 * *Files 0% similar despite different names*

```diff
@@ -31,23 +31,23 @@
     try:
         c = mc.cnames[color]
     except KeyError:
         c = color
     c = colorsys.rgb_to_hls(*mc.to_rgb(c))
     # print(c)
 
-    # if c[1] > 0:
-    #     # adjusted_lightness = c[1] * amount
-    #     adjusted_lightness = c[1] * amount * amount 
-    # else:
-    #     adjusted_lightness = 1 - (amount * amount)
-    #     # adjusted_lightness = 1 - c[1] * amount * amount
+    if c[1] > 0:
+        # adjusted_lightness = c[1] * amount
+        adjusted_lightness = c[1] * amount * amount 
+    else:
+        adjusted_lightness = 1 - (amount * amount)
+        # adjusted_lightness = 1 - c[1] * amount * amount
 
     adjusted_hue = c[0]
-    adjusted_lightness = c[1] * amount * amount * amount
+    # adjusted_lightness = c[1] * amount * amount 
     adjusted_saturation = c[2] 
 
     rgb = colorsys.hls_to_rgb(adjusted_hue, adjusted_lightness, adjusted_saturation)
     new_color = rgb_to_hex((int(rgb[0] * 250), int(rgb[1] * 250), int(rgb[2] * 250)))
 
     return new_color
```

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/aperture.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/aperture.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow_down.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow_down.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow_left.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow_left.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow_right.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow_right.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/arrow_up.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/arrow_up.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/base_icon.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/base_icon.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/base_palette.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/base_palette.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_closed.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_closed.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_end.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_end.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_line.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_line.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_more.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_more.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/branch_open.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/branch_open.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/checkbox_checked.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/checkbox_checked.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/checkbox_indeterminate.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/checkbox_indeterminate.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/checkbox_unchecked.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/checkbox_unchecked.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cloud-drizzle.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cloud-drizzle.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cloud-snow.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cloud-snow.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/codesandbox.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/codesandbox.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/cpu.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/cpu.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/figma.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/figma.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/film.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/film.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/github.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/github.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/life-buoy.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/life-buoy.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/line_horizontal.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/line_horizontal.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/line_vertical.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/line_vertical.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/loader.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/loader.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-call.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-call.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-forwarded.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-forwarded.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-incoming.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-incoming.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-missed.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-missed.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-off.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-off.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone-outgoing.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone-outgoing.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/phone.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/phone.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/radio_checked.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/radio_checked.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/radio_unchecked.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/radio_unchecked.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/settings.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/settings.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/slack.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/slack.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/sliders.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/sliders.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/sun.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/sun.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/sunrise.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/sunrise.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/sunset.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/sunset.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toolbar_move_horizontal.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toolbar_move_horizontal.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toolbar_move_vertical.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toolbar_move_vertical.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toolbar_separator_horizontal.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toolbar_separator_horizontal.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/toolbar_separator_vertical.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/toolbar_separator_vertical.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/transparent.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/transparent.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/wifi-off.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/wifi-off.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/window_close.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/window_close.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/window_grip.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/window_grip.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/window_minimize.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/window_minimize.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/window_undock.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/window_undock.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Qss/icons/original_svg/youtube.svg` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Qss/icons/original_svg/youtube.svg`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/RoundProgressBar.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/RoundProgressBar.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/SpiralProgressBar.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/SpiralProgressBar.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/Widgets.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/Widgets.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/WidgetsWorker.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/WidgetsWorker.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/__pycache__/main.cpython-310.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/__pycache__/main.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/__pycache__/main.cpython-38.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/__pycache__/main.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/__pycache__/ui_interface.cpython-310.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/__pycache__/ui_interface.cpython-310.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/__pycache__/ui_interface.cpython-38.pyc` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/__pycache__/ui_interface.cpython-38.pyc`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/main.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/main.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/python/ui_interface.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/python/ui_interface.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/components/uis/interface.ui` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/components/uis/interface.ui`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/interface.ui` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/interface.ui`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/Custom_Widgets/main.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/Custom_Widgets/main.py`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/LICENSE` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/LICENSE`

 * *Ordering differences only*

 * *Files 7% similar despite different names*

```diff
@@ -1,674 +1,674 @@
-                    GNU GENERAL PUBLIC LICENSE
-                       Version 3, 29 June 2007
-
- Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
- Everyone is permitted to copy and distribute verbatim copies
- of this license document, but changing it is not allowed.
-
-                            Preamble
-
-  The GNU General Public License is a free, copyleft license for
-software and other kinds of works.
-
-  The licenses for most software and other practical works are designed
-to take away your freedom to share and change the works.  By contrast,
-the GNU General Public License is intended to guarantee your freedom to
-share and change all versions of a program--to make sure it remains free
-software for all its users.  We, the Free Software Foundation, use the
-GNU General Public License for most of our software; it applies also to
-any other work released this way by its authors.  You can apply it to
-your programs, too.
-
-  When we speak of free software, we are referring to freedom, not
-price.  Our General Public Licenses are designed to make sure that you
-have the freedom to distribute copies of free software (and charge for
-them if you wish), that you receive source code or can get it if you
-want it, that you can change the software or use pieces of it in new
-free programs, and that you know you can do these things.
-
-  To protect your rights, we need to prevent others from denying you
-these rights or asking you to surrender the rights.  Therefore, you have
-certain responsibilities if you distribute copies of the software, or if
-you modify it: responsibilities to respect the freedom of others.
-
-  For example, if you distribute copies of such a program, whether
-gratis or for a fee, you must pass on to the recipients the same
-freedoms that you received.  You must make sure that they, too, receive
-or can get the source code.  And you must show them these terms so they
-know their rights.
-
-  Developers that use the GNU GPL protect your rights with two steps:
-(1) assert copyright on the software, and (2) offer you this License
-giving you legal permission to copy, distribute and/or modify it.
-
-  For the developers' and authors' protection, the GPL clearly explains
-that there is no warranty for this free software.  For both users' and
-authors' sake, the GPL requires that modified versions be marked as
-changed, so that their problems will not be attributed erroneously to
-authors of previous versions.
-
-  Some devices are designed to deny users access to install or run
-modified versions of the software inside them, although the manufacturer
-can do so.  This is fundamentally incompatible with the aim of
-protecting users' freedom to change the software.  The systematic
-pattern of such abuse occurs in the area of products for individuals to
-use, which is precisely where it is most unacceptable.  Therefore, we
-have designed this version of the GPL to prohibit the practice for those
-products.  If such problems arise substantially in other domains, we
-stand ready to extend this provision to those domains in future versions
-of the GPL, as needed to protect the freedom of users.
-
-  Finally, every program is threatened constantly by software patents.
-States should not allow patents to restrict development and use of
-software on general-purpose computers, but in those that do, we wish to
-avoid the special danger that patents applied to a free program could
-make it effectively proprietary.  To prevent this, the GPL assures that
-patents cannot be used to render the program non-free.
-
-  The precise terms and conditions for copying, distribution and
-modification follow.
-
-                       TERMS AND CONDITIONS
-
-  0. Definitions.
-
-  "This License" refers to version 3 of the GNU General Public License.
-
-  "Copyright" also means copyright-like laws that apply to other kinds of
-works, such as semiconductor masks.
-
-  "The Program" refers to any copyrightable work licensed under this
-License.  Each licensee is addressed as "you".  "Licensees" and
-"recipients" may be individuals or organizations.
-
-  To "modify" a work means to copy from or adapt all or part of the work
-in a fashion requiring copyright permission, other than the making of an
-exact copy.  The resulting work is called a "modified version" of the
-earlier work or a work "based on" the earlier work.
-
-  A "covered work" means either the unmodified Program or a work based
-on the Program.
-
-  To "propagate" a work means to do anything with it that, without
-permission, would make you directly or secondarily liable for
-infringement under applicable copyright law, except executing it on a
-computer or modifying a private copy.  Propagation includes copying,
-distribution (with or without modification), making available to the
-public, and in some countries other activities as well.
-
-  To "convey" a work means any kind of propagation that enables other
-parties to make or receive copies.  Mere interaction with a user through
-a computer network, with no transfer of a copy, is not conveying.
-
-  An interactive user interface displays "Appropriate Legal Notices"
-to the extent that it includes a convenient and prominently visible
-feature that (1) displays an appropriate copyright notice, and (2)
-tells the user that there is no warranty for the work (except to the
-extent that warranties are provided), that licensees may convey the
-work under this License, and how to view a copy of this License.  If
-the interface presents a list of user commands or options, such as a
-menu, a prominent item in the list meets this criterion.
-
-  1. Source Code.
-
-  The "source code" for a work means the preferred form of the work
-for making modifications to it.  "Object code" means any non-source
-form of a work.
-
-  A "Standard Interface" means an interface that either is an official
-standard defined by a recognized standards body, or, in the case of
-interfaces specified for a particular programming language, one that
-is widely used among developers working in that language.
-
-  The "System Libraries" of an executable work include anything, other
-than the work as a whole, that (a) is included in the normal form of
-packaging a Major Component, but which is not part of that Major
-Component, and (b) serves only to enable use of the work with that
-Major Component, or to implement a Standard Interface for which an
-implementation is available to the public in source code form.  A
-"Major Component", in this context, means a major essential component
-(kernel, window system, and so on) of the specific operating system
-(if any) on which the executable work runs, or a compiler used to
-produce the work, or an object code interpreter used to run it.
-
-  The "Corresponding Source" for a work in object code form means all
-the source code needed to generate, install, and (for an executable
-work) run the object code and to modify the work, including scripts to
-control those activities.  However, it does not include the work's
-System Libraries, or general-purpose tools or generally available free
-programs which are used unmodified in performing those activities but
-which are not part of the work.  For example, Corresponding Source
-includes interface definition files associated with source files for
-the work, and the source code for shared libraries and dynamically
-linked subprograms that the work is specifically designed to require,
-such as by intimate data communication or control flow between those
-subprograms and other parts of the work.
-
-  The Corresponding Source need not include anything that users
-can regenerate automatically from other parts of the Corresponding
-Source.
-
-  The Corresponding Source for a work in source code form is that
-same work.
-
-  2. Basic Permissions.
-
-  All rights granted under this License are granted for the term of
-copyright on the Program, and are irrevocable provided the stated
-conditions are met.  This License explicitly affirms your unlimited
-permission to run the unmodified Program.  The output from running a
-covered work is covered by this License only if the output, given its
-content, constitutes a covered work.  This License acknowledges your
-rights of fair use or other equivalent, as provided by copyright law.
-
-  You may make, run and propagate covered works that you do not
-convey, without conditions so long as your license otherwise remains
-in force.  You may convey covered works to others for the sole purpose
-of having them make modifications exclusively for you, or provide you
-with facilities for running those works, provided that you comply with
-the terms of this License in conveying all material for which you do
-not control copyright.  Those thus making or running the covered works
-for you must do so exclusively on your behalf, under your direction
-and control, on terms that prohibit them from making any copies of
-your copyrighted material outside their relationship with you.
-
-  Conveying under any other circumstances is permitted solely under
-the conditions stated below.  Sublicensing is not allowed; section 10
-makes it unnecessary.
-
-  3. Protecting Users' Legal Rights From Anti-Circumvention Law.
-
-  No covered work shall be deemed part of an effective technological
-measure under any applicable law fulfilling obligations under article
-11 of the WIPO copyright treaty adopted on 20 December 1996, or
-similar laws prohibiting or restricting circumvention of such
-measures.
-
-  When you convey a covered work, you waive any legal power to forbid
-circumvention of technological measures to the extent such circumvention
-is effected by exercising rights under this License with respect to
-the covered work, and you disclaim any intention to limit operation or
-modification of the work as a means of enforcing, against the work's
-users, your or third parties' legal rights to forbid circumvention of
-technological measures.
-
-  4. Conveying Verbatim Copies.
-
-  You may convey verbatim copies of the Program's source code as you
-receive it, in any medium, provided that you conspicuously and
-appropriately publish on each copy an appropriate copyright notice;
-keep intact all notices stating that this License and any
-non-permissive terms added in accord with section 7 apply to the code;
-keep intact all notices of the absence of any warranty; and give all
-recipients a copy of this License along with the Program.
-
-  You may charge any price or no price for each copy that you convey,
-and you may offer support or warranty protection for a fee.
-
-  5. Conveying Modified Source Versions.
-
-  You may convey a work based on the Program, or the modifications to
-produce it from the Program, in the form of source code under the
-terms of section 4, provided that you also meet all of these conditions:
-
-    a) The work must carry prominent notices stating that you modified
-    it, and giving a relevant date.
-
-    b) The work must carry prominent notices stating that it is
-    released under this License and any conditions added under section
-    7.  This requirement modifies the requirement in section 4 to
-    "keep intact all notices".
-
-    c) You must license the entire work, as a whole, under this
-    License to anyone who comes into possession of a copy.  This
-    License will therefore apply, along with any applicable section 7
-    additional terms, to the whole of the work, and all its parts,
-    regardless of how they are packaged.  This License gives no
-    permission to license the work in any other way, but it does not
-    invalidate such permission if you have separately received it.
-
-    d) If the work has interactive user interfaces, each must display
-    Appropriate Legal Notices; however, if the Program has interactive
-    interfaces that do not display Appropriate Legal Notices, your
-    work need not make them do so.
-
-  A compilation of a covered work with other separate and independent
-works, which are not by their nature extensions of the covered work,
-and which are not combined with it such as to form a larger program,
-in or on a volume of a storage or distribution medium, is called an
-"aggregate" if the compilation and its resulting copyright are not
-used to limit the access or legal rights of the compilation's users
-beyond what the individual works permit.  Inclusion of a covered work
-in an aggregate does not cause this License to apply to the other
-parts of the aggregate.
-
-  6. Conveying Non-Source Forms.
-
-  You may convey a covered work in object code form under the terms
-of sections 4 and 5, provided that you also convey the
-machine-readable Corresponding Source under the terms of this License,
-in one of these ways:
-
-    a) Convey the object code in, or embodied in, a physical product
-    (including a physical distribution medium), accompanied by the
-    Corresponding Source fixed on a durable physical medium
-    customarily used for software interchange.
-
-    b) Convey the object code in, or embodied in, a physical product
-    (including a physical distribution medium), accompanied by a
-    written offer, valid for at least three years and valid for as
-    long as you offer spare parts or customer support for that product
-    model, to give anyone who possesses the object code either (1) a
-    copy of the Corresponding Source for all the software in the
-    product that is covered by this License, on a durable physical
-    medium customarily used for software interchange, for a price no
-    more than your reasonable cost of physically performing this
-    conveying of source, or (2) access to copy the
-    Corresponding Source from a network server at no charge.
-
-    c) Convey individual copies of the object code with a copy of the
-    written offer to provide the Corresponding Source.  This
-    alternative is allowed only occasionally and noncommercially, and
-    only if you received the object code with such an offer, in accord
-    with subsection 6b.
-
-    d) Convey the object code by offering access from a designated
-    place (gratis or for a charge), and offer equivalent access to the
-    Corresponding Source in the same way through the same place at no
-    further charge.  You need not require recipients to copy the
-    Corresponding Source along with the object code.  If the place to
-    copy the object code is a network server, the Corresponding Source
-    may be on a different server (operated by you or a third party)
-    that supports equivalent copying facilities, provided you maintain
-    clear directions next to the object code saying where to find the
-    Corresponding Source.  Regardless of what server hosts the
-    Corresponding Source, you remain obligated to ensure that it is
-    available for as long as needed to satisfy these requirements.
-
-    e) Convey the object code using peer-to-peer transmission, provided
-    you inform other peers where the object code and Corresponding
-    Source of the work are being offered to the general public at no
-    charge under subsection 6d.
-
-  A separable portion of the object code, whose source code is excluded
-from the Corresponding Source as a System Library, need not be
-included in conveying the object code work.
-
-  A "User Product" is either (1) a "consumer product", which means any
-tangible personal property which is normally used for personal, family,
-or household purposes, or (2) anything designed or sold for incorporation
-into a dwelling.  In determining whether a product is a consumer product,
-doubtful cases shall be resolved in favor of coverage.  For a particular
-product received by a particular user, "normally used" refers to a
-typical or common use of that class of product, regardless of the status
-of the particular user or of the way in which the particular user
-actually uses, or expects or is expected to use, the product.  A product
-is a consumer product regardless of whether the product has substantial
-commercial, industrial or non-consumer uses, unless such uses represent
-the only significant mode of use of the product.
-
-  "Installation Information" for a User Product means any methods,
-procedures, authorization keys, or other information required to install
-and execute modified versions of a covered work in that User Product from
-a modified version of its Corresponding Source.  The information must
-suffice to ensure that the continued functioning of the modified object
-code is in no case prevented or interfered with solely because
-modification has been made.
-
-  If you convey an object code work under this section in, or with, or
-specifically for use in, a User Product, and the conveying occurs as
-part of a transaction in which the right of possession and use of the
-User Product is transferred to the recipient in perpetuity or for a
-fixed term (regardless of how the transaction is characterized), the
-Corresponding Source conveyed under this section must be accompanied
-by the Installation Information.  But this requirement does not apply
-if neither you nor any third party retains the ability to install
-modified object code on the User Product (for example, the work has
-been installed in ROM).
-
-  The requirement to provide Installation Information does not include a
-requirement to continue to provide support service, warranty, or updates
-for a work that has been modified or installed by the recipient, or for
-the User Product in which it has been modified or installed.  Access to a
-network may be denied when the modification itself materially and
-adversely affects the operation of the network or violates the rules and
-protocols for communication across the network.
-
-  Corresponding Source conveyed, and Installation Information provided,
-in accord with this section must be in a format that is publicly
-documented (and with an implementation available to the public in
-source code form), and must require no special password or key for
-unpacking, reading or copying.
-
-  7. Additional Terms.
-
-  "Additional permissions" are terms that supplement the terms of this
-License by making exceptions from one or more of its conditions.
-Additional permissions that are applicable to the entire Program shall
-be treated as though they were included in this License, to the extent
-that they are valid under applicable law.  If additional permissions
-apply only to part of the Program, that part may be used separately
-under those permissions, but the entire Program remains governed by
-this License without regard to the additional permissions.
-
-  When you convey a copy of a covered work, you may at your option
-remove any additional permissions from that copy, or from any part of
-it.  (Additional permissions may be written to require their own
-removal in certain cases when you modify the work.)  You may place
-additional permissions on material, added by you to a covered work,
-for which you have or can give appropriate copyright permission.
-
-  Notwithstanding any other provision of this License, for material you
-add to a covered work, you may (if authorized by the copyright holders of
-that material) supplement the terms of this License with terms:
-
-    a) Disclaiming warranty or limiting liability differently from the
-    terms of sections 15 and 16 of this License; or
-
-    b) Requiring preservation of specified reasonable legal notices or
-    author attributions in that material or in the Appropriate Legal
-    Notices displayed by works containing it; or
-
-    c) Prohibiting misrepresentation of the origin of that material, or
-    requiring that modified versions of such material be marked in
-    reasonable ways as different from the original version; or
-
-    d) Limiting the use for publicity purposes of names of licensors or
-    authors of the material; or
-
-    e) Declining to grant rights under trademark law for use of some
-    trade names, trademarks, or service marks; or
-
-    f) Requiring indemnification of licensors and authors of that
-    material by anyone who conveys the material (or modified versions of
-    it) with contractual assumptions of liability to the recipient, for
-    any liability that these contractual assumptions directly impose on
-    those licensors and authors.
-
-  All other non-permissive additional terms are considered "further
-restrictions" within the meaning of section 10.  If the Program as you
-received it, or any part of it, contains a notice stating that it is
-governed by this License along with a term that is a further
-restriction, you may remove that term.  If a license document contains
-a further restriction but permits relicensing or conveying under this
-License, you may add to a covered work material governed by the terms
-of that license document, provided that the further restriction does
-not survive such relicensing or conveying.
-
-  If you add terms to a covered work in accord with this section, you
-must place, in the relevant source files, a statement of the
-additional terms that apply to those files, or a notice indicating
-where to find the applicable terms.
-
-  Additional terms, permissive or non-permissive, may be stated in the
-form of a separately written license, or stated as exceptions;
-the above requirements apply either way.
-
-  8. Termination.
-
-  You may not propagate or modify a covered work except as expressly
-provided under this License.  Any attempt otherwise to propagate or
-modify it is void, and will automatically terminate your rights under
-this License (including any patent licenses granted under the third
-paragraph of section 11).
-
-  However, if you cease all violation of this License, then your
-license from a particular copyright holder is reinstated (a)
-provisionally, unless and until the copyright holder explicitly and
-finally terminates your license, and (b) permanently, if the copyright
-holder fails to notify you of the violation by some reasonable means
-prior to 60 days after the cessation.
-
-  Moreover, your license from a particular copyright holder is
-reinstated permanently if the copyright holder notifies you of the
-violation by some reasonable means, this is the first time you have
-received notice of violation of this License (for any work) from that
-copyright holder, and you cure the violation prior to 30 days after
-your receipt of the notice.
-
-  Termination of your rights under this section does not terminate the
-licenses of parties who have received copies or rights from you under
-this License.  If your rights have been terminated and not permanently
-reinstated, you do not qualify to receive new licenses for the same
-material under section 10.
-
-  9. Acceptance Not Required for Having Copies.
-
-  You are not required to accept this License in order to receive or
-run a copy of the Program.  Ancillary propagation of a covered work
-occurring solely as a consequence of using peer-to-peer transmission
-to receive a copy likewise does not require acceptance.  However,
-nothing other than this License grants you permission to propagate or
-modify any covered work.  These actions infringe copyright if you do
-not accept this License.  Therefore, by modifying or propagating a
-covered work, you indicate your acceptance of this License to do so.
-
-  10. Automatic Licensing of Downstream Recipients.
-
-  Each time you convey a covered work, the recipient automatically
-receives a license from the original licensors, to run, modify and
-propagate that work, subject to this License.  You are not responsible
-for enforcing compliance by third parties with this License.
-
-  An "entity transaction" is a transaction transferring control of an
-organization, or substantially all assets of one, or subdividing an
-organization, or merging organizations.  If propagation of a covered
-work results from an entity transaction, each party to that
-transaction who receives a copy of the work also receives whatever
-licenses to the work the party's predecessor in interest had or could
-give under the previous paragraph, plus a right to possession of the
-Corresponding Source of the work from the predecessor in interest, if
-the predecessor has it or can get it with reasonable efforts.
-
-  You may not impose any further restrictions on the exercise of the
-rights granted or affirmed under this License.  For example, you may
-not impose a license fee, royalty, or other charge for exercise of
-rights granted under this License, and you may not initiate litigation
-(including a cross-claim or counterclaim in a lawsuit) alleging that
-any patent claim is infringed by making, using, selling, offering for
-sale, or importing the Program or any portion of it.
-
-  11. Patents.
-
-  A "contributor" is a copyright holder who authorizes use under this
-License of the Program or a work on which the Program is based.  The
-work thus licensed is called the contributor's "contributor version".
-
-  A contributor's "essential patent claims" are all patent claims
-owned or controlled by the contributor, whether already acquired or
-hereafter acquired, that would be infringed by some manner, permitted
-by this License, of making, using, or selling its contributor version,
-but do not include claims that would be infringed only as a
-consequence of further modification of the contributor version.  For
-purposes of this definition, "control" includes the right to grant
-patent sublicenses in a manner consistent with the requirements of
-this License.
-
-  Each contributor grants you a non-exclusive, worldwide, royalty-free
-patent license under the contributor's essential patent claims, to
-make, use, sell, offer for sale, import and otherwise run, modify and
-propagate the contents of its contributor version.
-
-  In the following three paragraphs, a "patent license" is any express
-agreement or commitment, however denominated, not to enforce a patent
-(such as an express permission to practice a patent or covenant not to
-sue for patent infringement).  To "grant" such a patent license to a
-party means to make such an agreement or commitment not to enforce a
-patent against the party.
-
-  If you convey a covered work, knowingly relying on a patent license,
-and the Corresponding Source of the work is not available for anyone
-to copy, free of charge and under the terms of this License, through a
-publicly available network server or other readily accessible means,
-then you must either (1) cause the Corresponding Source to be so
-available, or (2) arrange to deprive yourself of the benefit of the
-patent license for this particular work, or (3) arrange, in a manner
-consistent with the requirements of this License, to extend the patent
-license to downstream recipients.  "Knowingly relying" means you have
-actual knowledge that, but for the patent license, your conveying the
-covered work in a country, or your recipient's use of the covered work
-in a country, would infringe one or more identifiable patents in that
-country that you have reason to believe are valid.
-
-  If, pursuant to or in connection with a single transaction or
-arrangement, you convey, or propagate by procuring conveyance of, a
-covered work, and grant a patent license to some of the parties
-receiving the covered work authorizing them to use, propagate, modify
-or convey a specific copy of the covered work, then the patent license
-you grant is automatically extended to all recipients of the covered
-work and works based on it.
-
-  A patent license is "discriminatory" if it does not include within
-the scope of its coverage, prohibits the exercise of, or is
-conditioned on the non-exercise of one or more of the rights that are
-specifically granted under this License.  You may not convey a covered
-work if you are a party to an arrangement with a third party that is
-in the business of distributing software, under which you make payment
-to the third party based on the extent of your activity of conveying
-the work, and under which the third party grants, to any of the
-parties who would receive the covered work from you, a discriminatory
-patent license (a) in connection with copies of the covered work
-conveyed by you (or copies made from those copies), or (b) primarily
-for and in connection with specific products or compilations that
-contain the covered work, unless you entered into that arrangement,
-or that patent license was granted, prior to 28 March 2007.
-
-  Nothing in this License shall be construed as excluding or limiting
-any implied license or other defenses to infringement that may
-otherwise be available to you under applicable patent law.
-
-  12. No Surrender of Others' Freedom.
-
-  If conditions are imposed on you (whether by court order, agreement or
-otherwise) that contradict the conditions of this License, they do not
-excuse you from the conditions of this License.  If you cannot convey a
-covered work so as to satisfy simultaneously your obligations under this
-License and any other pertinent obligations, then as a consequence you may
-not convey it at all.  For example, if you agree to terms that obligate you
-to collect a royalty for further conveying from those to whom you convey
-the Program, the only way you could satisfy both those terms and this
-License would be to refrain entirely from conveying the Program.
-
-  13. Use with the GNU Affero General Public License.
-
-  Notwithstanding any other provision of this License, you have
-permission to link or combine any covered work with a work licensed
-under version 3 of the GNU Affero General Public License into a single
-combined work, and to convey the resulting work.  The terms of this
-License will continue to apply to the part which is the covered work,
-but the special requirements of the GNU Affero General Public License,
-section 13, concerning interaction through a network will apply to the
-combination as such.
-
-  14. Revised Versions of this License.
-
-  The Free Software Foundation may publish revised and/or new versions of
-the GNU General Public License from time to time.  Such new versions will
-be similar in spirit to the present version, but may differ in detail to
-address new problems or concerns.
-
-  Each version is given a distinguishing version number.  If the
-Program specifies that a certain numbered version of the GNU General
-Public License "or any later version" applies to it, you have the
-option of following the terms and conditions either of that numbered
-version or of any later version published by the Free Software
-Foundation.  If the Program does not specify a version number of the
-GNU General Public License, you may choose any version ever published
-by the Free Software Foundation.
-
-  If the Program specifies that a proxy can decide which future
-versions of the GNU General Public License can be used, that proxy's
-public statement of acceptance of a version permanently authorizes you
-to choose that version for the Program.
-
-  Later license versions may give you additional or different
-permissions.  However, no additional obligations are imposed on any
-author or copyright holder as a result of your choosing to follow a
-later version.
-
-  15. Disclaimer of Warranty.
-
-  THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY
-APPLICABLE LAW.  EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
-HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY
-OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO,
-THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
-PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM
-IS WITH YOU.  SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF
-ALL NECESSARY SERVICING, REPAIR OR CORRECTION.
-
-  16. Limitation of Liability.
-
-  IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
-WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS
-THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY
-GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE
-USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF
-DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD
-PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS),
-EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF
-SUCH DAMAGES.
-
-  17. Interpretation of Sections 15 and 16.
-
-  If the disclaimer of warranty and limitation of liability provided
-above cannot be given local legal effect according to their terms,
-reviewing courts shall apply local law that most closely approximates
-an absolute waiver of all civil liability in connection with the
-Program, unless a warranty or assumption of liability accompanies a
-copy of the Program in return for a fee.
-
-                     END OF TERMS AND CONDITIONS
-
-            How to Apply These Terms to Your New Programs
-
-  If you develop a new program, and you want it to be of the greatest
-possible use to the public, the best way to achieve this is to make it
-free software which everyone can redistribute and change under these terms.
-
-  To do so, attach the following notices to the program.  It is safest
-to attach them to the start of each source file to most effectively
-state the exclusion of warranty; and each file should have at least
-the "copyright" line and a pointer to where the full notice is found.
-
-    <one line to give the program's name and a brief idea of what it does.>
-    Copyright (C) <year>  <name of author>
-
-    This program is free software: you can redistribute it and/or modify
-    it under the terms of the GNU General Public License as published by
-    the Free Software Foundation, either version 3 of the License, or
-    (at your option) any later version.
-
-    This program is distributed in the hope that it will be useful,
-    but WITHOUT ANY WARRANTY; without even the implied warranty of
-    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
-    GNU General Public License for more details.
-
-    You should have received a copy of the GNU General Public License
-    along with this program.  If not, see <https://www.gnu.org/licenses/>.
-
-Also add information on how to contact you by electronic and paper mail.
-
-  If the program does terminal interaction, make it output a short
-notice like this when it starts in an interactive mode:
-
-    <program>  Copyright (C) <year>  <name of author>
-    This program comes with ABSOLUTELY NO WARRANTY; for details type `show w'.
-    This is free software, and you are welcome to redistribute it
-    under certain conditions; type `show c' for details.
-
-The hypothetical commands `show w' and `show c' should show the appropriate
-parts of the General Public License.  Of course, your program's commands
-might be different; for a GUI interface, you would use an "about box".
-
-  You should also get your employer (if you work as a programmer) or school,
-if any, to sign a "copyright disclaimer" for the program, if necessary.
-For more information on this, and how to apply and follow the GNU GPL, see
-<https://www.gnu.org/licenses/>.
-
-  The GNU General Public License does not permit incorporating your program
-into proprietary programs.  If your program is a subroutine library, you
-may consider it more useful to permit linking proprietary applications with
-the library.  If this is what you want to do, use the GNU Lesser General
-Public License instead of this License.  But first, please read
-<https://www.gnu.org/licenses/why-not-lgpl.html>.
+                    GNU GENERAL PUBLIC LICENSE
+                       Version 3, 29 June 2007
+
+ Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
+ Everyone is permitted to copy and distribute verbatim copies
+ of this license document, but changing it is not allowed.
+
+                            Preamble
+
+  The GNU General Public License is a free, copyleft license for
+software and other kinds of works.
+
+  The licenses for most software and other practical works are designed
+to take away your freedom to share and change the works.  By contrast,
+the GNU General Public License is intended to guarantee your freedom to
+share and change all versions of a program--to make sure it remains free
+software for all its users.  We, the Free Software Foundation, use the
+GNU General Public License for most of our software; it applies also to
+any other work released this way by its authors.  You can apply it to
+your programs, too.
+
+  When we speak of free software, we are referring to freedom, not
+price.  Our General Public Licenses are designed to make sure that you
+have the freedom to distribute copies of free software (and charge for
+them if you wish), that you receive source code or can get it if you
+want it, that you can change the software or use pieces of it in new
+free programs, and that you know you can do these things.
+
+  To protect your rights, we need to prevent others from denying you
+these rights or asking you to surrender the rights.  Therefore, you have
+certain responsibilities if you distribute copies of the software, or if
+you modify it: responsibilities to respect the freedom of others.
+
+  For example, if you distribute copies of such a program, whether
+gratis or for a fee, you must pass on to the recipients the same
+freedoms that you received.  You must make sure that they, too, receive
+or can get the source code.  And you must show them these terms so they
+know their rights.
+
+  Developers that use the GNU GPL protect your rights with two steps:
+(1) assert copyright on the software, and (2) offer you this License
+giving you legal permission to copy, distribute and/or modify it.
+
+  For the developers' and authors' protection, the GPL clearly explains
+that there is no warranty for this free software.  For both users' and
+authors' sake, the GPL requires that modified versions be marked as
+changed, so that their problems will not be attributed erroneously to
+authors of previous versions.
+
+  Some devices are designed to deny users access to install or run
+modified versions of the software inside them, although the manufacturer
+can do so.  This is fundamentally incompatible with the aim of
+protecting users' freedom to change the software.  The systematic
+pattern of such abuse occurs in the area of products for individuals to
+use, which is precisely where it is most unacceptable.  Therefore, we
+have designed this version of the GPL to prohibit the practice for those
+products.  If such problems arise substantially in other domains, we
+stand ready to extend this provision to those domains in future versions
+of the GPL, as needed to protect the freedom of users.
+
+  Finally, every program is threatened constantly by software patents.
+States should not allow patents to restrict development and use of
+software on general-purpose computers, but in those that do, we wish to
+avoid the special danger that patents applied to a free program could
+make it effectively proprietary.  To prevent this, the GPL assures that
+patents cannot be used to render the program non-free.
+
+  The precise terms and conditions for copying, distribution and
+modification follow.
+
+                       TERMS AND CONDITIONS
+
+  0. Definitions.
+
+  "This License" refers to version 3 of the GNU General Public License.
+
+  "Copyright" also means copyright-like laws that apply to other kinds of
+works, such as semiconductor masks.
+
+  "The Program" refers to any copyrightable work licensed under this
+License.  Each licensee is addressed as "you".  "Licensees" and
+"recipients" may be individuals or organizations.
+
+  To "modify" a work means to copy from or adapt all or part of the work
+in a fashion requiring copyright permission, other than the making of an
+exact copy.  The resulting work is called a "modified version" of the
+earlier work or a work "based on" the earlier work.
+
+  A "covered work" means either the unmodified Program or a work based
+on the Program.
+
+  To "propagate" a work means to do anything with it that, without
+permission, would make you directly or secondarily liable for
+infringement under applicable copyright law, except executing it on a
+computer or modifying a private copy.  Propagation includes copying,
+distribution (with or without modification), making available to the
+public, and in some countries other activities as well.
+
+  To "convey" a work means any kind of propagation that enables other
+parties to make or receive copies.  Mere interaction with a user through
+a computer network, with no transfer of a copy, is not conveying.
+
+  An interactive user interface displays "Appropriate Legal Notices"
+to the extent that it includes a convenient and prominently visible
+feature that (1) displays an appropriate copyright notice, and (2)
+tells the user that there is no warranty for the work (except to the
+extent that warranties are provided), that licensees may convey the
+work under this License, and how to view a copy of this License.  If
+the interface presents a list of user commands or options, such as a
+menu, a prominent item in the list meets this criterion.
+
+  1. Source Code.
+
+  The "source code" for a work means the preferred form of the work
+for making modifications to it.  "Object code" means any non-source
+form of a work.
+
+  A "Standard Interface" means an interface that either is an official
+standard defined by a recognized standards body, or, in the case of
+interfaces specified for a particular programming language, one that
+is widely used among developers working in that language.
+
+  The "System Libraries" of an executable work include anything, other
+than the work as a whole, that (a) is included in the normal form of
+packaging a Major Component, but which is not part of that Major
+Component, and (b) serves only to enable use of the work with that
+Major Component, or to implement a Standard Interface for which an
+implementation is available to the public in source code form.  A
+"Major Component", in this context, means a major essential component
+(kernel, window system, and so on) of the specific operating system
+(if any) on which the executable work runs, or a compiler used to
+produce the work, or an object code interpreter used to run it.
+
+  The "Corresponding Source" for a work in object code form means all
+the source code needed to generate, install, and (for an executable
+work) run the object code and to modify the work, including scripts to
+control those activities.  However, it does not include the work's
+System Libraries, or general-purpose tools or generally available free
+programs which are used unmodified in performing those activities but
+which are not part of the work.  For example, Corresponding Source
+includes interface definition files associated with source files for
+the work, and the source code for shared libraries and dynamically
+linked subprograms that the work is specifically designed to require,
+such as by intimate data communication or control flow between those
+subprograms and other parts of the work.
+
+  The Corresponding Source need not include anything that users
+can regenerate automatically from other parts of the Corresponding
+Source.
+
+  The Corresponding Source for a work in source code form is that
+same work.
+
+  2. Basic Permissions.
+
+  All rights granted under this License are granted for the term of
+copyright on the Program, and are irrevocable provided the stated
+conditions are met.  This License explicitly affirms your unlimited
+permission to run the unmodified Program.  The output from running a
+covered work is covered by this License only if the output, given its
+content, constitutes a covered work.  This License acknowledges your
+rights of fair use or other equivalent, as provided by copyright law.
+
+  You may make, run and propagate covered works that you do not
+convey, without conditions so long as your license otherwise remains
+in force.  You may convey covered works to others for the sole purpose
+of having them make modifications exclusively for you, or provide you
+with facilities for running those works, provided that you comply with
+the terms of this License in conveying all material for which you do
+not control copyright.  Those thus making or running the covered works
+for you must do so exclusively on your behalf, under your direction
+and control, on terms that prohibit them from making any copies of
+your copyrighted material outside their relationship with you.
+
+  Conveying under any other circumstances is permitted solely under
+the conditions stated below.  Sublicensing is not allowed; section 10
+makes it unnecessary.
+
+  3. Protecting Users' Legal Rights From Anti-Circumvention Law.
+
+  No covered work shall be deemed part of an effective technological
+measure under any applicable law fulfilling obligations under article
+11 of the WIPO copyright treaty adopted on 20 December 1996, or
+similar laws prohibiting or restricting circumvention of such
+measures.
+
+  When you convey a covered work, you waive any legal power to forbid
+circumvention of technological measures to the extent such circumvention
+is effected by exercising rights under this License with respect to
+the covered work, and you disclaim any intention to limit operation or
+modification of the work as a means of enforcing, against the work's
+users, your or third parties' legal rights to forbid circumvention of
+technological measures.
+
+  4. Conveying Verbatim Copies.
+
+  You may convey verbatim copies of the Program's source code as you
+receive it, in any medium, provided that you conspicuously and
+appropriately publish on each copy an appropriate copyright notice;
+keep intact all notices stating that this License and any
+non-permissive terms added in accord with section 7 apply to the code;
+keep intact all notices of the absence of any warranty; and give all
+recipients a copy of this License along with the Program.
+
+  You may charge any price or no price for each copy that you convey,
+and you may offer support or warranty protection for a fee.
+
+  5. Conveying Modified Source Versions.
+
+  You may convey a work based on the Program, or the modifications to
+produce it from the Program, in the form of source code under the
+terms of section 4, provided that you also meet all of these conditions:
+
+    a) The work must carry prominent notices stating that you modified
+    it, and giving a relevant date.
+
+    b) The work must carry prominent notices stating that it is
+    released under this License and any conditions added under section
+    7.  This requirement modifies the requirement in section 4 to
+    "keep intact all notices".
+
+    c) You must license the entire work, as a whole, under this
+    License to anyone who comes into possession of a copy.  This
+    License will therefore apply, along with any applicable section 7
+    additional terms, to the whole of the work, and all its parts,
+    regardless of how they are packaged.  This License gives no
+    permission to license the work in any other way, but it does not
+    invalidate such permission if you have separately received it.
+
+    d) If the work has interactive user interfaces, each must display
+    Appropriate Legal Notices; however, if the Program has interactive
+    interfaces that do not display Appropriate Legal Notices, your
+    work need not make them do so.
+
+  A compilation of a covered work with other separate and independent
+works, which are not by their nature extensions of the covered work,
+and which are not combined with it such as to form a larger program,
+in or on a volume of a storage or distribution medium, is called an
+"aggregate" if the compilation and its resulting copyright are not
+used to limit the access or legal rights of the compilation's users
+beyond what the individual works permit.  Inclusion of a covered work
+in an aggregate does not cause this License to apply to the other
+parts of the aggregate.
+
+  6. Conveying Non-Source Forms.
+
+  You may convey a covered work in object code form under the terms
+of sections 4 and 5, provided that you also convey the
+machine-readable Corresponding Source under the terms of this License,
+in one of these ways:
+
+    a) Convey the object code in, or embodied in, a physical product
+    (including a physical distribution medium), accompanied by the
+    Corresponding Source fixed on a durable physical medium
+    customarily used for software interchange.
+
+    b) Convey the object code in, or embodied in, a physical product
+    (including a physical distribution medium), accompanied by a
+    written offer, valid for at least three years and valid for as
+    long as you offer spare parts or customer support for that product
+    model, to give anyone who possesses the object code either (1) a
+    copy of the Corresponding Source for all the software in the
+    product that is covered by this License, on a durable physical
+    medium customarily used for software interchange, for a price no
+    more than your reasonable cost of physically performing this
+    conveying of source, or (2) access to copy the
+    Corresponding Source from a network server at no charge.
+
+    c) Convey individual copies of the object code with a copy of the
+    written offer to provide the Corresponding Source.  This
+    alternative is allowed only occasionally and noncommercially, and
+    only if you received the object code with such an offer, in accord
+    with subsection 6b.
+
+    d) Convey the object code by offering access from a designated
+    place (gratis or for a charge), and offer equivalent access to the
+    Corresponding Source in the same way through the same place at no
+    further charge.  You need not require recipients to copy the
+    Corresponding Source along with the object code.  If the place to
+    copy the object code is a network server, the Corresponding Source
+    may be on a different server (operated by you or a third party)
+    that supports equivalent copying facilities, provided you maintain
+    clear directions next to the object code saying where to find the
+    Corresponding Source.  Regardless of what server hosts the
+    Corresponding Source, you remain obligated to ensure that it is
+    available for as long as needed to satisfy these requirements.
+
+    e) Convey the object code using peer-to-peer transmission, provided
+    you inform other peers where the object code and Corresponding
+    Source of the work are being offered to the general public at no
+    charge under subsection 6d.
+
+  A separable portion of the object code, whose source code is excluded
+from the Corresponding Source as a System Library, need not be
+included in conveying the object code work.
+
+  A "User Product" is either (1) a "consumer product", which means any
+tangible personal property which is normally used for personal, family,
+or household purposes, or (2) anything designed or sold for incorporation
+into a dwelling.  In determining whether a product is a consumer product,
+doubtful cases shall be resolved in favor of coverage.  For a particular
+product received by a particular user, "normally used" refers to a
+typical or common use of that class of product, regardless of the status
+of the particular user or of the way in which the particular user
+actually uses, or expects or is expected to use, the product.  A product
+is a consumer product regardless of whether the product has substantial
+commercial, industrial or non-consumer uses, unless such uses represent
+the only significant mode of use of the product.
+
+  "Installation Information" for a User Product means any methods,
+procedures, authorization keys, or other information required to install
+and execute modified versions of a covered work in that User Product from
+a modified version of its Corresponding Source.  The information must
+suffice to ensure that the continued functioning of the modified object
+code is in no case prevented or interfered with solely because
+modification has been made.
+
+  If you convey an object code work under this section in, or with, or
+specifically for use in, a User Product, and the conveying occurs as
+part of a transaction in which the right of possession and use of the
+User Product is transferred to the recipient in perpetuity or for a
+fixed term (regardless of how the transaction is characterized), the
+Corresponding Source conveyed under this section must be accompanied
+by the Installation Information.  But this requirement does not apply
+if neither you nor any third party retains the ability to install
+modified object code on the User Product (for example, the work has
+been installed in ROM).
+
+  The requirement to provide Installation Information does not include a
+requirement to continue to provide support service, warranty, or updates
+for a work that has been modified or installed by the recipient, or for
+the User Product in which it has been modified or installed.  Access to a
+network may be denied when the modification itself materially and
+adversely affects the operation of the network or violates the rules and
+protocols for communication across the network.
+
+  Corresponding Source conveyed, and Installation Information provided,
+in accord with this section must be in a format that is publicly
+documented (and with an implementation available to the public in
+source code form), and must require no special password or key for
+unpacking, reading or copying.
+
+  7. Additional Terms.
+
+  "Additional permissions" are terms that supplement the terms of this
+License by making exceptions from one or more of its conditions.
+Additional permissions that are applicable to the entire Program shall
+be treated as though they were included in this License, to the extent
+that they are valid under applicable law.  If additional permissions
+apply only to part of the Program, that part may be used separately
+under those permissions, but the entire Program remains governed by
+this License without regard to the additional permissions.
+
+  When you convey a copy of a covered work, you may at your option
+remove any additional permissions from that copy, or from any part of
+it.  (Additional permissions may be written to require their own
+removal in certain cases when you modify the work.)  You may place
+additional permissions on material, added by you to a covered work,
+for which you have or can give appropriate copyright permission.
+
+  Notwithstanding any other provision of this License, for material you
+add to a covered work, you may (if authorized by the copyright holders of
+that material) supplement the terms of this License with terms:
+
+    a) Disclaiming warranty or limiting liability differently from the
+    terms of sections 15 and 16 of this License; or
+
+    b) Requiring preservation of specified reasonable legal notices or
+    author attributions in that material or in the Appropriate Legal
+    Notices displayed by works containing it; or
+
+    c) Prohibiting misrepresentation of the origin of that material, or
+    requiring that modified versions of such material be marked in
+    reasonable ways as different from the original version; or
+
+    d) Limiting the use for publicity purposes of names of licensors or
+    authors of the material; or
+
+    e) Declining to grant rights under trademark law for use of some
+    trade names, trademarks, or service marks; or
+
+    f) Requiring indemnification of licensors and authors of that
+    material by anyone who conveys the material (or modified versions of
+    it) with contractual assumptions of liability to the recipient, for
+    any liability that these contractual assumptions directly impose on
+    those licensors and authors.
+
+  All other non-permissive additional terms are considered "further
+restrictions" within the meaning of section 10.  If the Program as you
+received it, or any part of it, contains a notice stating that it is
+governed by this License along with a term that is a further
+restriction, you may remove that term.  If a license document contains
+a further restriction but permits relicensing or conveying under this
+License, you may add to a covered work material governed by the terms
+of that license document, provided that the further restriction does
+not survive such relicensing or conveying.
+
+  If you add terms to a covered work in accord with this section, you
+must place, in the relevant source files, a statement of the
+additional terms that apply to those files, or a notice indicating
+where to find the applicable terms.
+
+  Additional terms, permissive or non-permissive, may be stated in the
+form of a separately written license, or stated as exceptions;
+the above requirements apply either way.
+
+  8. Termination.
+
+  You may not propagate or modify a covered work except as expressly
+provided under this License.  Any attempt otherwise to propagate or
+modify it is void, and will automatically terminate your rights under
+this License (including any patent licenses granted under the third
+paragraph of section 11).
+
+  However, if you cease all violation of this License, then your
+license from a particular copyright holder is reinstated (a)
+provisionally, unless and until the copyright holder explicitly and
+finally terminates your license, and (b) permanently, if the copyright
+holder fails to notify you of the violation by some reasonable means
+prior to 60 days after the cessation.
+
+  Moreover, your license from a particular copyright holder is
+reinstated permanently if the copyright holder notifies you of the
+violation by some reasonable means, this is the first time you have
+received notice of violation of this License (for any work) from that
+copyright holder, and you cure the violation prior to 30 days after
+your receipt of the notice.
+
+  Termination of your rights under this section does not terminate the
+licenses of parties who have received copies or rights from you under
+this License.  If your rights have been terminated and not permanently
+reinstated, you do not qualify to receive new licenses for the same
+material under section 10.
+
+  9. Acceptance Not Required for Having Copies.
+
+  You are not required to accept this License in order to receive or
+run a copy of the Program.  Ancillary propagation of a covered work
+occurring solely as a consequence of using peer-to-peer transmission
+to receive a copy likewise does not require acceptance.  However,
+nothing other than this License grants you permission to propagate or
+modify any covered work.  These actions infringe copyright if you do
+not accept this License.  Therefore, by modifying or propagating a
+covered work, you indicate your acceptance of this License to do so.
+
+  10. Automatic Licensing of Downstream Recipients.
+
+  Each time you convey a covered work, the recipient automatically
+receives a license from the original licensors, to run, modify and
+propagate that work, subject to this License.  You are not responsible
+for enforcing compliance by third parties with this License.
+
+  An "entity transaction" is a transaction transferring control of an
+organization, or substantially all assets of one, or subdividing an
+organization, or merging organizations.  If propagation of a covered
+work results from an entity transaction, each party to that
+transaction who receives a copy of the work also receives whatever
+licenses to the work the party's predecessor in interest had or could
+give under the previous paragraph, plus a right to possession of the
+Corresponding Source of the work from the predecessor in interest, if
+the predecessor has it or can get it with reasonable efforts.
+
+  You may not impose any further restrictions on the exercise of the
+rights granted or affirmed under this License.  For example, you may
+not impose a license fee, royalty, or other charge for exercise of
+rights granted under this License, and you may not initiate litigation
+(including a cross-claim or counterclaim in a lawsuit) alleging that
+any patent claim is infringed by making, using, selling, offering for
+sale, or importing the Program or any portion of it.
+
+  11. Patents.
+
+  A "contributor" is a copyright holder who authorizes use under this
+License of the Program or a work on which the Program is based.  The
+work thus licensed is called the contributor's "contributor version".
+
+  A contributor's "essential patent claims" are all patent claims
+owned or controlled by the contributor, whether already acquired or
+hereafter acquired, that would be infringed by some manner, permitted
+by this License, of making, using, or selling its contributor version,
+but do not include claims that would be infringed only as a
+consequence of further modification of the contributor version.  For
+purposes of this definition, "control" includes the right to grant
+patent sublicenses in a manner consistent with the requirements of
+this License.
+
+  Each contributor grants you a non-exclusive, worldwide, royalty-free
+patent license under the contributor's essential patent claims, to
+make, use, sell, offer for sale, import and otherwise run, modify and
+propagate the contents of its contributor version.
+
+  In the following three paragraphs, a "patent license" is any express
+agreement or commitment, however denominated, not to enforce a patent
+(such as an express permission to practice a patent or covenant not to
+sue for patent infringement).  To "grant" such a patent license to a
+party means to make such an agreement or commitment not to enforce a
+patent against the party.
+
+  If you convey a covered work, knowingly relying on a patent license,
+and the Corresponding Source of the work is not available for anyone
+to copy, free of charge and under the terms of this License, through a
+publicly available network server or other readily accessible means,
+then you must either (1) cause the Corresponding Source to be so
+available, or (2) arrange to deprive yourself of the benefit of the
+patent license for this particular work, or (3) arrange, in a manner
+consistent with the requirements of this License, to extend the patent
+license to downstream recipients.  "Knowingly relying" means you have
+actual knowledge that, but for the patent license, your conveying the
+covered work in a country, or your recipient's use of the covered work
+in a country, would infringe one or more identifiable patents in that
+country that you have reason to believe are valid.
+
+  If, pursuant to or in connection with a single transaction or
+arrangement, you convey, or propagate by procuring conveyance of, a
+covered work, and grant a patent license to some of the parties
+receiving the covered work authorizing them to use, propagate, modify
+or convey a specific copy of the covered work, then the patent license
+you grant is automatically extended to all recipients of the covered
+work and works based on it.
+
+  A patent license is "discriminatory" if it does not include within
+the scope of its coverage, prohibits the exercise of, or is
+conditioned on the non-exercise of one or more of the rights that are
+specifically granted under this License.  You may not convey a covered
+work if you are a party to an arrangement with a third party that is
+in the business of distributing software, under which you make payment
+to the third party based on the extent of your activity of conveying
+the work, and under which the third party grants, to any of the
+parties who would receive the covered work from you, a discriminatory
+patent license (a) in connection with copies of the covered work
+conveyed by you (or copies made from those copies), or (b) primarily
+for and in connection with specific products or compilations that
+contain the covered work, unless you entered into that arrangement,
+or that patent license was granted, prior to 28 March 2007.
+
+  Nothing in this License shall be construed as excluding or limiting
+any implied license or other defenses to infringement that may
+otherwise be available to you under applicable patent law.
+
+  12. No Surrender of Others' Freedom.
+
+  If conditions are imposed on you (whether by court order, agreement or
+otherwise) that contradict the conditions of this License, they do not
+excuse you from the conditions of this License.  If you cannot convey a
+covered work so as to satisfy simultaneously your obligations under this
+License and any other pertinent obligations, then as a consequence you may
+not convey it at all.  For example, if you agree to terms that obligate you
+to collect a royalty for further conveying from those to whom you convey
+the Program, the only way you could satisfy both those terms and this
+License would be to refrain entirely from conveying the Program.
+
+  13. Use with the GNU Affero General Public License.
+
+  Notwithstanding any other provision of this License, you have
+permission to link or combine any covered work with a work licensed
+under version 3 of the GNU Affero General Public License into a single
+combined work, and to convey the resulting work.  The terms of this
+License will continue to apply to the part which is the covered work,
+but the special requirements of the GNU Affero General Public License,
+section 13, concerning interaction through a network will apply to the
+combination as such.
+
+  14. Revised Versions of this License.
+
+  The Free Software Foundation may publish revised and/or new versions of
+the GNU General Public License from time to time.  Such new versions will
+be similar in spirit to the present version, but may differ in detail to
+address new problems or concerns.
+
+  Each version is given a distinguishing version number.  If the
+Program specifies that a certain numbered version of the GNU General
+Public License "or any later version" applies to it, you have the
+option of following the terms and conditions either of that numbered
+version or of any later version published by the Free Software
+Foundation.  If the Program does not specify a version number of the
+GNU General Public License, you may choose any version ever published
+by the Free Software Foundation.
+
+  If the Program specifies that a proxy can decide which future
+versions of the GNU General Public License can be used, that proxy's
+public statement of acceptance of a version permanently authorizes you
+to choose that version for the Program.
+
+  Later license versions may give you additional or different
+permissions.  However, no additional obligations are imposed on any
+author or copyright holder as a result of your choosing to follow a
+later version.
+
+  15. Disclaimer of Warranty.
+
+  THERE IS NO WARRANTY FOR THE PROGRAM, TO THE EXTENT PERMITTED BY
+APPLICABLE LAW.  EXCEPT WHEN OTHERWISE STATED IN WRITING THE COPYRIGHT
+HOLDERS AND/OR OTHER PARTIES PROVIDE THE PROGRAM "AS IS" WITHOUT WARRANTY
+OF ANY KIND, EITHER EXPRESSED OR IMPLIED, INCLUDING, BUT NOT LIMITED TO,
+THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
+PURPOSE.  THE ENTIRE RISK AS TO THE QUALITY AND PERFORMANCE OF THE PROGRAM
+IS WITH YOU.  SHOULD THE PROGRAM PROVE DEFECTIVE, YOU ASSUME THE COST OF
+ALL NECESSARY SERVICING, REPAIR OR CORRECTION.
+
+  16. Limitation of Liability.
+
+  IN NO EVENT UNLESS REQUIRED BY APPLICABLE LAW OR AGREED TO IN WRITING
+WILL ANY COPYRIGHT HOLDER, OR ANY OTHER PARTY WHO MODIFIES AND/OR CONVEYS
+THE PROGRAM AS PERMITTED ABOVE, BE LIABLE TO YOU FOR DAMAGES, INCLUDING ANY
+GENERAL, SPECIAL, INCIDENTAL OR CONSEQUENTIAL DAMAGES ARISING OUT OF THE
+USE OR INABILITY TO USE THE PROGRAM (INCLUDING BUT NOT LIMITED TO LOSS OF
+DATA OR DATA BEING RENDERED INACCURATE OR LOSSES SUSTAINED BY YOU OR THIRD
+PARTIES OR A FAILURE OF THE PROGRAM TO OPERATE WITH ANY OTHER PROGRAMS),
+EVEN IF SUCH HOLDER OR OTHER PARTY HAS BEEN ADVISED OF THE POSSIBILITY OF
+SUCH DAMAGES.
+
+  17. Interpretation of Sections 15 and 16.
+
+  If the disclaimer of warranty and limitation of liability provided
+above cannot be given local legal effect according to their terms,
+reviewing courts shall apply local law that most closely approximates
+an absolute waiver of all civil liability in connection with the
+Program, unless a warranty or assumption of liability accompanies a
+copy of the Program in return for a fee.
+
+                     END OF TERMS AND CONDITIONS
+
+            How to Apply These Terms to Your New Programs
+
+  If you develop a new program, and you want it to be of the greatest
+possible use to the public, the best way to achieve this is to make it
+free software which everyone can redistribute and change under these terms.
+
+  To do so, attach the following notices to the program.  It is safest
+to attach them to the start of each source file to most effectively
+state the exclusion of warranty; and each file should have at least
+the "copyright" line and a pointer to where the full notice is found.
+
+    <one line to give the program's name and a brief idea of what it does.>
+    Copyright (C) <year>  <name of author>
+
+    This program is free software: you can redistribute it and/or modify
+    it under the terms of the GNU General Public License as published by
+    the Free Software Foundation, either version 3 of the License, or
+    (at your option) any later version.
+
+    This program is distributed in the hope that it will be useful,
+    but WITHOUT ANY WARRANTY; without even the implied warranty of
+    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
+    GNU General Public License for more details.
+
+    You should have received a copy of the GNU General Public License
+    along with this program.  If not, see <https://www.gnu.org/licenses/>.
+
+Also add information on how to contact you by electronic and paper mail.
+
+  If the program does terminal interaction, make it output a short
+notice like this when it starts in an interactive mode:
+
+    <program>  Copyright (C) <year>  <name of author>
+    This program comes with ABSOLUTELY NO WARRANTY; for details type `show w'.
+    This is free software, and you are welcome to redistribute it
+    under certain conditions; type `show c' for details.
+
+The hypothetical commands `show w' and `show c' should show the appropriate
+parts of the General Public License.  Of course, your program's commands
+might be different; for a GUI interface, you would use an "about box".
+
+  You should also get your employer (if you work as a programmer) or school,
+if any, to sign a "copyright disclaimer" for the program, if necessary.
+For more information on this, and how to apply and follow the GNU GPL, see
+<https://www.gnu.org/licenses/>.
+
+  The GNU General Public License does not permit incorporating your program
+into proprietary programs.  If your program is a subroutine library, you
+may consider it more useful to permit linking proprietary applications with
+the library.  If this is what you want to do, use the GNU Lesser General
+Public License instead of this License.  But first, please read
+<https://www.gnu.org/licenses/why-not-lgpl.html>.
```

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/PKG-INFO` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: QT-PyQt-PySide-Custom-Widgets
-Version: 0.6.6
+Version: 0.6.7
 Summary: Custom widgets and widget animations made for QT applications
 Home-page: https://github.com/KhamisiKibet/QT-PyQt-PySide-Custom-Widgets
 Author: Khamisi Kibet
 Author-email: kibetkhamisi@gmail.com
 License: GNU General Public License v3.0
-Keywords: PySide,PyQt,animation,custom,widgets,QML,C++,QT Creator,Moderm GUI,UI Design
+Keywords: PySide,PyQt,animation,custom,widgets,QML,C++,QT Creator,Moder GUI,Desktop GUI,Design
 Platform: UNKNOWN
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Build Tools
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
```

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/QT_PyQt_PySide_Custom_Widgets.egg-info/PKG-INFO` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/QT_PyQt_PySide_Custom_Widgets.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: QT-PyQt-PySide-Custom-Widgets
-Version: 0.6.6
+Version: 0.6.7
 Summary: Custom widgets and widget animations made for QT applications
 Home-page: https://github.com/KhamisiKibet/QT-PyQt-PySide-Custom-Widgets
 Author: Khamisi Kibet
 Author-email: kibetkhamisi@gmail.com
 License: GNU General Public License v3.0
-Keywords: PySide,PyQt,animation,custom,widgets,QML,C++,QT Creator,Moderm GUI,UI Design
+Keywords: PySide,PyQt,animation,custom,widgets,QML,C++,QT Creator,Moder GUI,Desktop GUI,Design
 Platform: UNKNOWN
 Classifier: Development Status :: 3 - Alpha
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Build Tools
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
```

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/QT_PyQt_PySide_Custom_Widgets.egg-info/SOURCES.txt` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/QT_PyQt_PySide_Custom_Widgets.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/README.md` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/README.md`

 * *Files identical despite different names*

### Comparing `QT-PyQt-PySide-Custom-Widgets-0.6.6/setup.py` & `QT-PyQt-PySide-Custom-Widgets-0.6.7/setup.py`

 * *Files 9% similar despite different names*

```diff
@@ -12,24 +12,24 @@
     name = 'QT-PyQt-PySide-Custom-Widgets',         # How you named your package folder (MyLib)
     packages = [
         'Custom_Widgets',
         'Custom_Widgets.ProgressIndicator',
         'Custom_Widgets.Qss',
     ],
     include_package_data=True,
-    version = '0.6.6',      # Start with a small number and increase it with every change you make
+    version = '0.6.7',      # Start with a small number and increase it with every change you make
     license="GNU General Public License v3.0",        # Chose a license from here: https://help.github.com/articles/licensing-a-repository
     description = 'Custom widgets and widget animations made for QT applications',   # Give a short description about your library
     long_description=README,
     long_description_content_type="text/markdown",
     author = 'Khamisi Kibet',                   # Type in your name
     author_email = 'kibetkhamisi@gmail.com',      # Type in your E-Mail
     url = 'https://github.com/KhamisiKibet/QT-PyQt-PySide-Custom-Widgets',   # Provide either the link to your github or to your website
     # download_url = 'https://github.com/user/reponame/archive/v_01.tar.gz',    # I explain this later on
-    keywords = ['PySide', 'PyQt', 'animation', 'custom', 'widgets', "QML", "C++", "QT Creator", "Moderm GUI", "UI Design"],   # Keywords that define your package best
+    keywords = ['PySide', 'PyQt', 'animation', 'custom', 'widgets', "QML", "C++", "QT Creator", "Moder GUI", "Desktop GUI", "Design"],   # Keywords that define your package best
     install_requires=[
         # "PySide2",
         # "PyQt5",
         "qtpy",
         "iconify",
         "cairosvg",
         "qtsass",
```


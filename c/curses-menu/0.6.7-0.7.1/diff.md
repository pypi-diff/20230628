# Comparing `tmp/curses-menu-0.6.7.tar.gz` & `tmp/curses_menu-0.7.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "curses-menu-0.6.7.tar", max compression
+gzip compressed data, was "curses_menu-0.7.1.tar", max compression
```

## Comparing `curses-menu-0.6.7.tar` & `curses_menu-0.7.1.tar`

### file list

```diff
@@ -1,57 +1,56 @@
--rw-r--r--   0        0        0      922 2022-10-31 02:59:45.963476 curses-menu-0.6.7/CHANGELOG.rst
--rw-r--r--   0        0        0     1100 2020-04-07 07:01:49.000000 curses-menu-0.6.7/LICENSE.md
--rw-r--r--   0        0        0     2896 2022-10-31 02:59:34.275960 curses-menu-0.6.7/README.rst
--rw-r--r--   0        0        0      651 2020-04-07 07:01:49.000000 curses-menu-0.6.7/acknowledgements.md
--rw-r--r--   0        0        0      376 2022-09-08 01:18:00.287787 curses-menu-0.6.7/cursesmenu/__init__.py
--rw-r--r--   0        0        0    18213 2022-09-08 01:18:00.288537 curses-menu-0.6.7/cursesmenu/curses_menu.py
--rw-r--r--   0        0        0     3553 2022-09-08 01:18:00.289236 curses-menu-0.6.7/cursesmenu/item_group.py
--rw-r--r--   0        0        0      345 2021-11-25 21:29:19.218608 curses-menu-0.6.7/cursesmenu/items/__init__.py
--rw-r--r--   0        0        0     2702 2022-09-08 01:18:00.289923 curses-menu-0.6.7/cursesmenu/items/command_item.py
--rw-r--r--   0        0        0     1299 2022-08-10 00:50:43.361815 curses-menu-0.6.7/cursesmenu/items/exit_item.py
--rw-r--r--   0        0        0      807 2021-11-25 21:29:19.219882 curses-menu-0.6.7/cursesmenu/items/external_item.py
--rw-r--r--   0        0        0     1969 2022-08-02 03:13:09.109619 curses-menu-0.6.7/cursesmenu/items/function_item.py
--rw-r--r--   0        0        0     2377 2022-08-10 00:50:43.361990 curses-menu-0.6.7/cursesmenu/items/menu_item.py
--rw-r--r--   0        0        0      801 2022-08-02 03:13:09.110281 curses-menu-0.6.7/cursesmenu/items/selection_item.py
--rw-r--r--   0        0        0     2796 2022-08-02 03:13:09.110095 curses-menu-0.6.7/cursesmenu/items/submenu_item.py
--rw-r--r--   0        0        0     1758 2021-11-25 21:29:19.221780 curses-menu-0.6.7/cursesmenu/old_curses_menu.py
--rw-r--r--   0        0        0      818 2022-08-01 23:24:12.896911 curses-menu-0.6.7/cursesmenu/utils.py
--rw-r--r--   0        0        0      638 2021-11-25 21:29:19.222551 curses-menu-0.6.7/docs/Makefile
--rw-r--r--   0        0        0     2019 2022-09-08 01:18:00.290736 curses-menu-0.6.7/docs/source/conf.py
--rw-r--r--   0        0        0     1527 2021-11-25 21:29:19.264392 curses-menu-0.6.7/docs/source/cursesmenu/CursesMenu.rst
--rw-r--r--   0        0        0      107 2021-11-25 21:29:19.225033 curses-menu-0.6.7/docs/source/cursesmenu/ItemGroup.rst
--rw-r--r--   0        0        0       95 2021-11-25 21:29:19.263852 curses-menu-0.6.7/docs/source/cursesmenu/functions.rst
--rw-r--r--   0        0        0      130 2021-11-25 21:29:19.263350 curses-menu-0.6.7/docs/source/cursesmenu/items/CommandItem.rst
--rw-r--r--   0        0        0      117 2021-11-25 21:29:19.262886 curses-menu-0.6.7/docs/source/cursesmenu/items/ExitItem.rst
--rw-r--r--   0        0        0      129 2021-11-25 21:29:19.262315 curses-menu-0.6.7/docs/source/cursesmenu/items/ExternalItem.rst
--rw-r--r--   0        0        0      133 2021-11-25 21:29:19.261852 curses-menu-0.6.7/docs/source/cursesmenu/items/FunctionItem.rst
--rw-r--r--   0        0        0       74 2021-11-25 21:29:19.261374 curses-menu-0.6.7/docs/source/cursesmenu/items/MenuItem.rst
--rw-r--r--   0        0        0      126 2021-11-25 21:29:19.260962 curses-menu-0.6.7/docs/source/cursesmenu/items/SubmenuItem.rst
--rw-r--r--   0        0        0      145 2021-11-25 21:29:19.264990 curses-menu-0.6.7/docs/source/cursesmenu.rst
--rw-r--r--   0        0        0      490 2021-11-25 21:29:19.260433 curses-menu-0.6.7/docs/source/index.rst
--rw-r--r--   0        0        0      100 2021-11-25 21:29:19.227467 curses-menu-0.6.7/docs/source/installation.rst
--rw-r--r--   0        0        0      231 2021-11-25 21:29:19.259904 curses-menu-0.6.7/docs/source/items.rst
--rw-r--r--   0        0        0     1735 2021-11-25 21:29:19.257379 curses-menu-0.6.7/docs/source/usage.rst
--rw-r--r--   0        0        0     3793 2022-10-31 02:59:45.963750 curses-menu-0.6.7/pyproject.toml
--rw-r--r--   0        0        0        0 2021-11-25 21:29:19.232373 curses-menu-0.6.7/test/__init__.py
--rw-r--r--   0        0        0     2009 2022-08-01 23:24:12.898690 curses-menu-0.6.7/test/conftest.py
--rw-r--r--   0        0        0        0 2021-11-25 21:29:19.233785 curses-menu-0.6.7/test/example_menus/__init__.py
--rw-r--r--   0        0        0      134 2021-11-25 21:29:19.234232 curses-menu-0.6.7/test/example_menus/basic_menu.py
--rw-r--r--   0        0        0      290 2021-11-25 21:29:19.234624 curses-menu-0.6.7/test/example_menus/menu_with_items.py
--rw-r--r--   0        0        0      283 2022-08-02 01:28:06.278287 curses-menu-0.6.7/test/example_menus/menu_with_lots_of_items.py
--rw-r--r--   0        0        0      298 2022-09-08 01:18:00.305476 curses-menu-0.6.7/test/example_menus/zero_padded_menu_with_lots_of_items.py
--rw-r--r--   0        0        0      552 2022-08-01 04:41:23.745334 curses-menu-0.6.7/test/test_clear.py
--rw-r--r--   0        0        0     1761 2022-09-08 01:18:00.306202 curses-menu-0.6.7/test/test_command_item.py
--rw-r--r--   0        0        0     5483 2022-09-08 01:18:00.307068 curses-menu-0.6.7/test/test_curses_menu.py
--rw-r--r--   0        0        0     1030 2022-09-08 01:18:00.307703 curses-menu-0.6.7/test/test_example_menus.py
--rw-r--r--   0        0        0      630 2021-11-25 21:29:19.238787 curses-menu-0.6.7/test/test_exit_item.py
--rw-r--r--   0        0        0      890 2021-11-25 21:29:19.239213 curses-menu-0.6.7/test/test_external_item.py
--rw-r--r--   0        0        0      537 2021-11-25 21:29:19.239616 curses-menu-0.6.7/test/test_function_item.py
--rw-r--r--   0        0        0     3861 2022-09-08 01:18:00.308490 curses-menu-0.6.7/test/test_graphics.py
--rw-r--r--   0        0        0     2283 2021-11-25 21:29:19.240293 curses-menu-0.6.7/test/test_item_group.py
--rw-r--r--   0        0        0      808 2021-11-25 21:29:19.240708 curses-menu-0.6.7/test/test_menu_item.py
--rw-r--r--   0        0        0      283 2021-11-25 21:29:19.241114 curses-menu-0.6.7/test/test_selection_item.py
--rw-r--r--   0        0        0      378 2021-11-25 21:29:19.241525 curses-menu-0.6.7/test/test_selection_menu.py
--rw-r--r--   0        0        0     2838 2021-11-25 21:29:19.241942 curses-menu-0.6.7/test/test_submenu_item.py
--rw-r--r--   0        0        0     1635 2022-10-31 02:59:34.276905 curses-menu-0.6.7/tox.ini
--rw-r--r--   0        0        0     3856 1970-01-01 00:00:00.000000 curses-menu-0.6.7/setup.py
--rw-r--r--   0        0        0     4595 1970-01-01 00:00:00.000000 curses-menu-0.6.7/PKG-INFO
+-rw-r--r--   0        0        0     1465 2023-06-27 22:30:26.979471 curses_menu-0.7.1/CHANGELOG.rst
+-rw-r--r--   0        0        0     1079 2023-06-27 22:30:26.979471 curses_menu-0.7.1/LICENSE.md
+-rw-r--r--   0        0        0     2896 2023-06-27 22:30:26.979471 curses_menu-0.7.1/README.rst
+-rw-r--r--   0        0        0      640 2023-06-27 22:30:26.979471 curses_menu-0.7.1/acknowledgements.md
+-rw-r--r--   0        0        0      247 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/__init__.py
+-rw-r--r--   0        0        0    18621 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/curses_menu.py
+-rw-r--r--   0        0        0     3491 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/item_group.py
+-rw-r--r--   0        0        0      345 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/items/__init__.py
+-rw-r--r--   0        0        0     2894 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/items/command_item.py
+-rw-r--r--   0        0        0     1348 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/items/exit_item.py
+-rw-r--r--   0        0        0      807 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/items/external_item.py
+-rw-r--r--   0        0        0     1984 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/items/function_item.py
+-rw-r--r--   0        0        0     2388 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/items/menu_item.py
+-rw-r--r--   0        0        0      890 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/items/selection_item.py
+-rw-r--r--   0        0        0     2809 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/items/submenu_item.py
+-rw-r--r--   0        0        0     1844 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/old_curses_menu.py
+-rw-r--r--   0        0        0      932 2023-06-27 22:30:26.979471 curses_menu-0.7.1/cursesmenu/utils.py
+-rw-r--r--   0        0        0      638 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/Makefile
+-rw-r--r--   0        0        0     2084 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/conf.py
+-rw-r--r--   0        0        0     1527 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu/CursesMenu.rst
+-rw-r--r--   0        0        0      107 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu/ItemGroup.rst
+-rw-r--r--   0        0        0       95 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu/functions.rst
+-rw-r--r--   0        0        0      130 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu/items/CommandItem.rst
+-rw-r--r--   0        0        0      117 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu/items/ExitItem.rst
+-rw-r--r--   0        0        0      129 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu/items/ExternalItem.rst
+-rw-r--r--   0        0        0      133 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu/items/FunctionItem.rst
+-rw-r--r--   0        0        0       74 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu/items/MenuItem.rst
+-rw-r--r--   0        0        0      126 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu/items/SubmenuItem.rst
+-rw-r--r--   0        0        0      145 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/cursesmenu.rst
+-rw-r--r--   0        0        0      490 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/index.rst
+-rw-r--r--   0        0        0      100 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/installation.rst
+-rw-r--r--   0        0        0      231 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/items.rst
+-rw-r--r--   0        0        0     1735 2023-06-27 22:30:26.979471 curses_menu-0.7.1/docs/source/usage.rst
+-rw-r--r--   0        0        0     5300 2023-06-27 22:30:26.979471 curses_menu-0.7.1/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/__init__.py
+-rw-r--r--   0        0        0     2024 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/conftest.py
+-rw-r--r--   0        0        0        0 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/example_menus/__init__.py
+-rw-r--r--   0        0        0      134 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/example_menus/basic_menu.py
+-rw-r--r--   0        0        0      290 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/example_menus/menu_with_items.py
+-rw-r--r--   0        0        0      275 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/example_menus/menu_with_lots_of_items.py
+-rw-r--r--   0        0        0      290 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/example_menus/zero_padded_menu_with_lots_of_items.py
+-rw-r--r--   0        0        0      538 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/test_clear.py
+-rw-r--r--   0        0        0     1766 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/test_command_item.py
+-rw-r--r--   0        0        0     5573 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/test_curses_menu.py
+-rw-r--r--   0        0        0     1030 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/test_example_menus.py
+-rw-r--r--   0        0        0      634 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/test_exit_item.py
+-rw-r--r--   0        0        0      894 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/test_external_item.py
+-rw-r--r--   0        0        0      537 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/test_function_item.py
+-rw-r--r--   0        0        0     3999 2023-06-27 22:30:26.979471 curses_menu-0.7.1/test/test_graphics.py
+-rw-r--r--   0        0        0     2369 2023-06-27 22:30:26.983471 curses_menu-0.7.1/test/test_item_group.py
+-rw-r--r--   0        0        0      814 2023-06-27 22:30:26.983471 curses_menu-0.7.1/test/test_menu_item.py
+-rw-r--r--   0        0        0      286 2023-06-27 22:30:26.983471 curses_menu-0.7.1/test/test_selection_item.py
+-rw-r--r--   0        0        0      378 2023-06-27 22:30:26.983471 curses_menu-0.7.1/test/test_selection_menu.py
+-rw-r--r--   0        0        0     2838 2023-06-27 22:30:26.983471 curses_menu-0.7.1/test/test_submenu_item.py
+-rw-r--r--   0        0        0     1625 2023-06-27 22:30:26.983471 curses_menu-0.7.1/tox.ini
+-rw-r--r--   0        0        0     4236 1970-01-01 00:00:00.000000 curses_menu-0.7.1/PKG-INFO
```

### Comparing `curses-menu-0.6.7/CHANGELOG.rst` & `curses_menu-0.7.1/CHANGELOG.rst`

 * *Files 18% similar despite different names*

```diff
@@ -1,7 +1,35 @@
+Version 0.7.0
+-------------
+* Drop Python 3.7
+
+Version 0.6.14
+-------------
+* Updating deployment workflow
+* Various dependency and testing updates
+
+Version 0.6.11
+-------------
+* Fix issue with calling stty
+* Various dependency and testing updates
+
+Version 0.6.10
+-------------
+* Testing automatic deployment
+
+Version 0.6.9
+-------------
+* Update dev dependencies
+* Fix dependabot complaint in test/doc dependency
+
+Version 0.6.8
+-------------
+* Added some more pre-commit checks
+* Update dependencies for security fix in documentation build
+
 Version 0.6.7
 -------------
 * Test on release python 3.11
 * Fix readme
 
 Version 0.6.5
 -------------
```

### Comparing `curses-menu-0.6.7/LICENSE.md` & `curses_menu-0.7.1/LICENSE.md`

 * *Ordering differences only*

 * *Files 16% similar despite different names*

```diff
@@ -1,21 +1,21 @@
-The MIT License (MIT)
-
-Copyright (c) 2016 Paul Barrett
-
-Permission is hereby granted, free of charge, to any person obtaining a copy
-of this software and associated documentation files (the "Software"), to deal
-in the Software without restriction, including without limitation the rights
-to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
-copies of the Software, and to permit persons to whom the Software is
-furnished to do so, subject to the following conditions:
-
-The above copyright notice and this permission notice shall be included in all
-copies or substantial portions of the Software.
-
-THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
-IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
-FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
-AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
-LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
-OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
-SOFTWARE.
+The MIT License (MIT)
+
+Copyright (c) 2016 Paul Barrett
+
+Permission is hereby granted, free of charge, to any person obtaining a copy
+of this software and associated documentation files (the "Software"), to deal
+in the Software without restriction, including without limitation the rights
+to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
+copies of the Software, and to permit persons to whom the Software is
+furnished to do so, subject to the following conditions:
+
+The above copyright notice and this permission notice shall be included in all
+copies or substantial portions of the Software.
+
+THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
+IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
+FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
+AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
+LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
+OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
+SOFTWARE.
```

### Comparing `curses-menu-0.6.7/README.rst` & `curses_menu-0.7.1/README.rst`

 * *Files 0% similar despite different names*

```diff
@@ -13,15 +13,15 @@
 
 .. image:: ./images/curses-menu_screenshot1.png
 
 
 Installation
 ~~~~~~~~~~~~
 
-Tested on Python 3.7+ pypy and pypy3.
+Tested on Python 3.8+ pypy and pypy3.
 
 The curses library comes bundled with python on Linux and MacOS. Windows
 users can visit http://www.lfd.uci.edu/~gohlke/pythonlibs/#curses and
 get a third-party build for your platform and Python version.
 
 Then just run
```

### Comparing `curses-menu-0.6.7/acknowledgements.md` & `curses_menu-0.7.1/acknowledgements.md`

 * *Ordering differences only*

 * *Files 27% similar despite different names*

```diff
@@ -1,11 +1,11 @@
-#Acknowledgements
-
-### From the files I started with:
-https://gist.github.com/abishur/2482046
-"Topmenu and the submenus are based of the example found at this location http://blog.skeltonnetworks.com/2010/03/python-curses-custom-menuData/
-The rest of the work was done by Matthew Bennett and he requests you keep these two mentions when you reuse the code :-)
-Basic code refactoring by Andrew Scheller"
-
-Another version of this using classes: https://gist.github.com/etkirsch/53505478f53aeeac24a5
-
-Handy guide that pointed me to a lot of tools I used: https://www.jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/
+#Acknowledgements
+
+### From the files I started with:
+https://gist.github.com/abishur/2482046
+"Topmenu and the submenus are based of the example found at this location http://blog.skeltonnetworks.com/2010/03/python-curses-custom-menuData/
+The rest of the work was done by Matthew Bennett and he requests you keep these two mentions when you reuse the code :-)
+Basic code refactoring by Andrew Scheller"
+
+Another version of this using classes: https://gist.github.com/etkirsch/53505478f53aeeac24a5
+
+Handy guide that pointed me to a lot of tools I used: https://www.jeffknupp.com/blog/2013/08/16/open-sourcing-a-python-project-the-right-way/
```

### Comparing `curses-menu-0.6.7/cursesmenu/curses_menu.py` & `curses_menu-0.7.1/cursesmenu/curses_menu.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,36 +1,42 @@
 """Top level class and functions for a curses-based menu."""
 
+from __future__ import annotations
+
 import atexit
 import curses
 import os
 import pathlib
+import shutil
 import threading
 import time
 from collections import defaultdict
-from typing import TYPE_CHECKING, Any, Callable, DefaultDict, List, Optional, cast
+from typing import TYPE_CHECKING, Any, cast
 
 from deprecated import deprecated
 
 import cursesmenu.utils
 from cursesmenu.item_group import ItemGroup
 
 if TYPE_CHECKING:
     # noinspection PyCompatibility,PyProtectedMember
+    from typing import Callable
+
     from _curses import window
 
     Window = window
     from cursesmenu.items.menu_item import MenuItem
 else:
     Window = Any
     MenuItem = Any
 
 MIN_SIZE = 6  # Top bar, space, title, space, subtitle, space, bottom bar
 
 PROJECT_ROOT = pathlib.Path(__file__).parent.parent.absolute()
+_SCREENDUMP_DIR = PROJECT_ROOT.joinpath("screendumps")
 
 
 class CursesMenu:
     """
     A menu created with the curses library.
 
     :param title: The title of the menu
@@ -58,32 +64,32 @@
     :ivar last_item_index: The index of the max item in the menu, \
     including the exit item
     :cvar currently_active_menu: Class variable that holds the \
     currently active menu or None if no menu\
     is currently active (E.G. when switching between menus)
     """
 
-    currently_active_menu: Optional["CursesMenu"] = None
-    stdscr: Optional[Window] = None
+    currently_active_menu: CursesMenu | None = None
+    stdscr: Window | None = None
 
     def __init__(
         self,
         title: str = "",
         subtitle: str = "",
         *,
         show_exit_item: bool = True,
         zero_pad: bool = False,
         _debug_screens: bool = False,
-    ):
+    ) -> None:
         """Initialize the menu."""
         self.title = title
         self.subtitle = subtitle
         self.zero_pad = zero_pad
 
-        self.screen: Optional[Window] = None
+        self.screen: Window | None = None
 
         # highlight should be initialized to black-on-white, but bold is a fine
         # fallback that doesn't need the screen initialized first
         self.highlight: int = curses.A_BOLD
         self.normal: int = curses.A_NORMAL
 
         # TODO: add a way to replace item indices with letters
@@ -101,17 +107,17 @@
 
         self._running = threading.Event()
         self.should_exit = False
 
         # TODO: Should this be a property
         self.returned_value = None
 
-        self.parent: Optional[CursesMenu] = None
+        self.parent: CursesMenu | None = None
 
-        self.user_input_handlers: DefaultDict[int, Callable[[int], None]] = defaultdict(
+        self.user_input_handlers: defaultdict[int, Callable[[int], None]] = defaultdict(
             cursesmenu.utils.null_input_factory,
         )
         self.user_input_handlers.update(
             {
                 ord("\n"): self.select,
                 curses.KEY_UP: self.go_up,
                 curses.KEY_DOWN: self.go_down,
@@ -131,26 +137,23 @@
             )
         self.user_input_handlers.update(
             {k: self.go_to for k in map(ord, map(str, range(1, 10)))},
         )
 
         self._debug_screens = _debug_screens
 
-    def __repr__(self) -> str:
-        """Get a string representation of the menu."""
-        return f"<{self.title}: {self.subtitle}. {len(self.items)} items>"
-
     @classmethod
     def make_selection_menu(
         cls,
-        selections: List[str],
+        selections: list[str],
         title: str = "",
         subtitle: str = "",
+        *,
         show_exit_item: bool = False,
-    ) -> "CursesMenu":
+    ) -> CursesMenu:
         """
         Create a menu from a list of strings.
 
         The return value of the menu will be an index into the list of strings.
 
         :param selections: A list of strings to be selected from
         :param title: The title of the menu
@@ -167,15 +170,15 @@
                 SelectionItem(text=selection, index=index, should_exit=True),
             )
         return menu
 
     @classmethod
     def get_selection(
         cls,
-        selections: List[str],
+        selections: list[str],
         title: str = "",
         subtitle: str = "",
     ) -> int:
         """
         Present the user with a menu built from a list of strings and get the index\
         of their selection.
 
@@ -194,23 +197,23 @@
 
     @property
     def all_items(self) -> ItemGroup:
         """Get the combined list of items."""
         return self.items + self.end_items
 
     @property
-    def current_item(self) -> Optional[MenuItem]:
+    def current_item(self) -> MenuItem | None:
         """Get the currently selected MenuItem."""
         if not self.all_items:
             return None
         else:
             return self.all_items[self.current_option]
 
     @property
-    def selected_item(self) -> Optional[MenuItem]:
+    def selected_item(self) -> MenuItem | None:
         """Get the most recently selected MenuItem."""
         if self.selected_option == -1:
             return None
         else:
             return self.all_items[self.selected_option]
 
     @property
@@ -220,15 +223,15 @@
 
     @property
     def last_item_index(self) -> int:
         """Get the index of the last item in a list of items including the exit item \
         if it's shown."""
         return len(self.all_items) - 1
 
-    def show(self) -> Any:
+    def show(self) -> Any:  # noqa: ANN401
         """
         Start the menu and blocks until it finishes.
 
         :return: The return value from the last selected item
         """
         self.start()
         return self.join()
@@ -256,31 +259,34 @@
                 os.environ["CURSES_MENU_PID"] = str(pid)
                 atexit.register(cursesmenu.utils.clear_terminal)
 
             try:
                 CursesMenu.stdscr = curses.initscr()
                 curses.noecho()
                 curses.cbreak()
-                CursesMenu.stdscr.keypad(True)
+                CursesMenu.stdscr.keypad(True)  # noqa: FBT003
                 # noinspection PyBroadException
-                try:
+                try:  # noqa: SIM105
                     curses.start_color()
-                except:  # noqa: E722 # pragma: no cover all
+                except:  # noqa: E722,S110 # pragma: no cover all
                     pass
                 self._main_loop()
             finally:
                 # I currently don't remember whether there's a situation where stdscr
                 # should be None at runtime, so I'm leaving this as an if
                 # as opposed to an assert, but using a pragma for coverage
                 if CursesMenu.stdscr is not None:  # pragma: no branch
-                    CursesMenu.stdscr.keypad(False)
+                    CursesMenu.stdscr.keypad(False)  # noqa: FBT003
                 curses.endwin()
                 curses.echo()
                 curses.nocbreak()
-                os.system("stty echo")
+                if (
+                    shutil.which("[") is not None and shutil.which("stty") is not None
+                ):  # pragma: no cover all
+                    os.system("[ -t 0 ] && stty echo")
         else:
             self._main_loop()
 
     def _main_loop(self) -> None:
         assert CursesMenu.stdscr is not None
         self.screen = curses.newpad(self.menu_height, CursesMenu.stdscr.getmaxyx()[1])
         self._set_up_colors()
@@ -311,33 +317,28 @@
         self.screen.addstr(4, 2, self.subtitle, curses.A_BOLD)
 
         for index, item in enumerate(self.all_items):
             self.draw_item(index, item)
 
         self.refresh_screen()
         if self._debug_screens:  # pragma: no cover all
-            with open(
-                PROJECT_ROOT.joinpath("screendumps", f"{self.title}-{time.time()}"),
+            with _SCREENDUMP_DIR.joinpath(f"{self.title}-{time.time()}").open(
                 "wb",
             ) as f:
                 self.screen.putwin(f)
-            with open(
-                PROJECT_ROOT.joinpath(
-                    "screendumps",
-                    f"stdscr-{self.title}-{time.time()}",
-                ),
-                "wb",
-            ) as f:
+            with _SCREENDUMP_DIR.joinpath(
+                f"stdscr-{self.title}-{time.time()}",
+            ).open("wb") as f:
                 self.screen.putwin(f)
 
     def draw_item(
         self,
         index: int,
         item: MenuItem,
-        index_text: Optional[str] = None,
+        index_text: str | None = None,
     ) -> None:
         """
         Draw an individual item.
 
         :param index: The numerical index of the item in the list
         :param item: The item to be drawn
         :param index_text: Text to override the index portion of the item
@@ -345,15 +346,16 @@
         if index_text is None:
             index_text = str(index + 1)
             if self.zero_pad:
                 pad_width = len(str(len(self.items)))
                 index_text = index_text.zfill(pad_width)
 
         text_style = self.highlight if self.current_option == index else self.normal
-        assert self.screen is not None and text_style is not None
+        assert self.screen is not None
+        assert text_style is not None
 
         self.screen.addstr(
             MIN_SIZE - 1 + index,
             4,
             item.show(index_text),
             text_style,
         )
@@ -387,14 +389,22 @@
         Get the user's input.
 
         :return: The character input by the user.
         """
         assert CursesMenu.stdscr is not None
         return CursesMenu.stdscr.getch()
 
+    def _exit(self) -> None:
+        self.should_exit = True
+
+    def _exit_with_return(self) -> int:
+        """Identical to _exit, but return in for type checking"""
+        self.should_exit = True
+        return 0
+
     def select(self, _: int = 0) -> None:
         """
         Select the current item.
 
         Called for the enter/return key.
         """
         if not self.all_items:
@@ -409,17 +419,14 @@
 
         self.returned_value = self.selected_item.get_return()
         self.should_exit = self.selected_item.should_exit
 
         if not self.should_exit:
             self.draw()
 
-    def _exit(self) -> None:
-        self.should_exit = True
-
     def go_to(self, user_input: int) -> None:
         """
         Go to a given numbered item.
 
         Called on numerical input. Currently implementation only works on single digits.
         """
         if self.last_item_index > 9:
@@ -476,15 +483,15 @@
 
     def clear_screen(self) -> None:
         """Clear the screen for this menu."""
         assert self.screen is not None
         self.screen.clear()
         self.refresh_screen()
 
-    def join(self, timeout: Optional[int] = None) -> Any:
+    def join(self, timeout: int | None = None) -> Any:  # noqa: ANN401
         """
         Block until the menu exits.
 
         :param timeout: time in seconds until the menu is forced to close
         :return: The value returned from the last selected item
         """
         self._main_thread.join(timeout=timeout)
@@ -494,15 +501,15 @@
         """
         Check if the menu has is running (has not been paused).
 
         :return: True if the menu has not been paused false otherwise.
         """
         return self._running.is_set()
 
-    def wait_for_start(self, timeout: Optional[int] = None) -> bool:
+    def wait_for_start(self, timeout: int | None = None) -> bool:
         """
         Block until the menu starts.
 
         :param timeout: Timeout in seconds
         :return: True unless the operation times out
         """
         return self._running.wait(timeout)
@@ -519,15 +526,15 @@
         """
         Check if the menu's thread is running.
 
         :return: True if the menu's thread is alive, false if not.
         """
         return self._main_thread.is_alive()
 
-    def exit(self, timeout: Optional[int] = None) -> Any:
+    def exit(self, timeout: int | None = None) -> Any:  # noqa: A003, ANN401
         """
         Signal the menu to exit and block until it does.
 
         :param timeout: timeout before the menu is forced to close
         :return: the value of the last selected item
         """
         self._exit()
@@ -541,7 +548,11 @@
                 self.screen.resize(self.menu_height, max_cols)
             self.draw()
 
     @deprecated(reason="Use self.items.append.", version="0.6.0")
     def append_item(self, item: MenuItem) -> None:
         """Append an item to the list of items."""
         self.items.append(item)
+
+    def __repr__(self) -> str:
+        """Get a string representation of the menu."""
+        return f"<{self.title}: {self.subtitle}. {len(self.items)} items>"
```

### Comparing `curses-menu-0.6.7/cursesmenu/item_group.py` & `curses_menu-0.7.1/cursesmenu/item_group.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,28 +1,22 @@
 """A group of items that belong to a CursesMenu."""
 
+from __future__ import annotations
+
 import sys
-from typing import (
-    TYPE_CHECKING,
-    Any,
-    Iterable,
-    Iterator,
-    List,
-    Optional,
-    Union,
-    cast,
-    overload,
-)
+from typing import TYPE_CHECKING, Any, Iterable, cast, overload
 
 if sys.version_info >= (3, 9):  # pragma: py-lt-39
     from collections.abc import MutableSequence
 else:  # pragma: py-gte-39
     from typing import MutableSequence
 
 if TYPE_CHECKING:
+    from typing import Iterator
+
     from cursesmenu.curses_menu import CursesMenu
     from cursesmenu.items.menu_item import MenuItem
 else:
     CursesMenu = Any
     MenuItem = Any
 
 
@@ -30,50 +24,60 @@
     """
     A group of items that belong to a CursesMenu.
 
     Holds the items and ensures that the menu updates when a new one is added.
     Implements MutableSequence, so should act like a list.
     """
 
-    def __init__(self, menu: CursesMenu, items: Optional[Iterable[MenuItem]] = None):
+    def __init__(
+        self,
+        menu: CursesMenu,
+        items: Iterable[MenuItem] | None = None,
+    ) -> None:
         """Initialize the group."""
         if items is None:
             items = []
-        self.items: List[MenuItem] = list(items)
+        self.items: list[MenuItem] = list(items)
         self.menu = menu
 
         for item in items:
             item.menu = self.menu
 
+    def insert(self, index: int, item: MenuItem) -> None:
+        """Insert an item."""
+        item.menu = self.menu
+        self.items.insert(index, item)
+        self.menu.adjust_screen_size()
+
     @overload
     def __getitem__(self, i: int) -> MenuItem:
         ...
 
     @overload
-    def __getitem__(self, s: slice) -> "ItemGroup":
+    def __getitem__(self, i: slice) -> ItemGroup:
         ...
 
-    def __getitem__(self, i: Union[int, slice]) -> Union[MenuItem, "ItemGroup"]:
+    def __getitem__(self, i: int | slice) -> MenuItem | ItemGroup:
         if isinstance(i, slice):
             return ItemGroup(self.menu, self.items[i])
         else:
             return self.items[i]
 
     @overload
     def __setitem__(self, i: int, item: MenuItem) -> None:
         ...
 
     @overload
-    def __setitem__(self, s: slice, items: Iterable[MenuItem]) -> None:
+    def __setitem__(self, i: slice, item: Iterable[MenuItem]) -> None:
         ...
 
     def __setitem__(
         self,
-        i: Union[int, slice],
-        item: Union[MenuItem, Iterable[MenuItem]],
+        i: int | slice,
+        item: MenuItem | Iterable[MenuItem],
     ) -> None:
         """Set an item."""
         from cursesmenu.items.menu_item import MenuItem
 
         if isinstance(i, int):
             item = cast(MenuItem, item)
             item.menu = self.menu
@@ -87,48 +91,39 @@
         self.menu.adjust_screen_size()
 
     @overload
     def __delitem__(self, i: int) -> None:
         ...
 
     @overload
-    def __delitem__(self, s: slice) -> None:
+    def __delitem__(self, i: slice) -> None:
         ...
 
-    def __delitem__(self, i: Union[int, slice]) -> None:
+    def __delitem__(self, i: int | slice) -> None:
         """Delete an item."""
         del self.items[i]
         self.menu.adjust_screen_size()
 
-    def __len__(self) -> int:
-        """Get the number of items in the group."""
-        return len(self.items)
-
-    def insert(self, index: int, item: MenuItem) -> None:
-        """Insert an item."""
-        item.menu = self.menu
-        self.items.insert(index, item)
-        self.menu.adjust_screen_size()
-
     def __iter__(self) -> Iterator[MenuItem]:
         """Get an iterator for the group."""
         return iter(self.items)
 
-    def __add__(self, other: "ItemGroup") -> "ItemGroup":
+    def __len__(self) -> int:
+        """Get the number of items in the group."""
+        return len(self.items)
+
+    def __add__(self, other: ItemGroup) -> ItemGroup:
         """
         Add two groups together.
 
         The resulting group will have the menu of the first group.
         """
         return ItemGroup(self.menu, self.items + other.items)
 
     def __eq__(self, other: object) -> bool:
         if not isinstance(other, ItemGroup):
             return NotImplemented
         if self.menu != other.menu:
             return False
         if len(self) != len(other):
             return False
-        for item1, item2 in zip(self, other):
-            if item1 != item2:
-                return False
-        return True
+        return all(item1 == item2 for item1, item2 in zip(self, other))
```

### Comparing `curses-menu-0.6.7/cursesmenu/items/exit_item.py` & `curses_menu-0.7.1/cursesmenu/items/exit_item.py`

 * *Files 22% similar despite different names*

```diff
@@ -1,31 +1,36 @@
 """Item that exits a menu or returns to the menu's parent."""
 
-from typing import Optional
+from __future__ import annotations
+
+from typing import TYPE_CHECKING
 
-from cursesmenu.curses_menu import CursesMenu
 from cursesmenu.items.menu_item import MenuItem
 
+if TYPE_CHECKING:
+    from cursesmenu.curses_menu import CursesMenu
+
 
 class ExitItem(MenuItem):
     """
     The exit item for a menu.
 
     Changes representation based on whether the menu is a submenu or the root menu.
 
     :param menu: the menu for this item
     """
 
     def __init__(
         self,
-        menu: Optional[CursesMenu] = None,
-        override_index: Optional[str] = None,
-    ):
+        menu: CursesMenu | None = None,
+        *,
+        override_index: str | None = None,
+    ) -> None:
         """Initialize the exit item."""
-        super(ExitItem, self).__init__(
+        super().__init__(
             text="Exit",
             menu=menu,
             should_exit=True,
             override_index=override_index,
         )
 
     def show(self, index_text: str) -> str:
@@ -38,8 +43,8 @@
         """
         if self.menu and self.menu.parent:
             # TODO: implement an item that exits the whole menu
             #  hierarchy from a submenu.
             self.text = "Return to %s menu" % self.menu.parent.title
         else:
             self.text = "Exit"
-        return super(ExitItem, self).show(index_text)
+        return super().show(index_text)
```

### Comparing `curses-menu-0.6.7/cursesmenu/items/external_item.py` & `curses_menu-0.7.1/cursesmenu/items/external_item.py`

 * *Files identical despite different names*

### Comparing `curses-menu-0.6.7/cursesmenu/items/function_item.py` & `curses_menu-0.7.1/cursesmenu/items/function_item.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,17 +1,19 @@
 """A menu item that executes a Python function with arguments."""
 
-from typing import TYPE_CHECKING, Any, Callable, Dict, List, Optional
+from __future__ import annotations
+
+from typing import TYPE_CHECKING
 
 from cursesmenu.items.external_item import ExternalItem
 
 if TYPE_CHECKING:
+    from typing import Any, Callable
+
     from cursesmenu.curses_menu import CursesMenu
-else:
-    CursesMenu = Any
 
 
 class FunctionItem(ExternalItem):
     """
     A menu item that executes a Python function with arguments.
 
     :param text: The text of the item
@@ -22,41 +24,42 @@
     :param should_exit: Whether the menu will exit when this item is selected
     """
 
     def __init__(
         self,
         text: str,
         function: Callable[..., Any],
-        args: Optional[List[Any]] = None,
-        kwargs: Optional[Dict[Any, Any]] = None,
-        menu: Optional[CursesMenu] = None,
+        args: list[Any] | None = None,
+        kwargs: dict[Any, Any] | None = None,
+        menu: CursesMenu | None = None,
+        *,
         should_exit: bool = False,
-        override_index: Optional[str] = None,
-    ):
+        override_index: str | None = None,
+    ) -> None:
         """Initialize the item."""
-        super(FunctionItem, self).__init__(
+        super().__init__(
             text=text,
             menu=menu,
             should_exit=should_exit,
             override_index=override_index,
         )
         self.function = function
         if args is None:
             args = []
-        self.args: List[Any] = args
+        self.args: list[Any] = args
         if kwargs is None:
             kwargs = {}
-        self.kwargs: Dict[Any, Any] = kwargs
+        self.kwargs: dict[Any, Any] = kwargs
 
         self.return_value: Any = None
 
     def action(self) -> None:
         """Call the function with the provided arguments."""
         self.return_value = self.function(*self.args, **self.kwargs)
 
-    def get_return(self) -> Any:
+    def get_return(self) -> Any:  # noqa: ANN401
         """
         Get the returned value from the function.
 
         :return: The value returned from the function, or None if it hasn't been called.
         """
         return self.return_value
```

### Comparing `curses-menu-0.6.7/cursesmenu/items/submenu_item.py` & `curses_menu-0.7.1/cursesmenu/items/submenu_item.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,17 +1,19 @@
 """A menu item that opens a submenu."""
 
-from typing import TYPE_CHECKING, Any, Optional
+from __future__ import annotations
+
+from typing import TYPE_CHECKING
 
 from cursesmenu.items.menu_item import MenuItem
 
 if TYPE_CHECKING:
+    from typing import Any
+
     from cursesmenu.curses_menu import CursesMenu
-else:
-    CursesMenu = Any
 
 
 class SubmenuItem(MenuItem):
     """
     A menu item that opens a submenu.
 
     :param text: The text of the item
@@ -19,50 +21,51 @@
     :param menu: The menu that this item belongs to
     :param should_exit: Whether the menu will exit when this item is selected
     """
 
     def __init__(
         self,
         text: str,
-        submenu: Optional[CursesMenu] = None,
-        menu: Optional[CursesMenu] = None,
+        submenu: CursesMenu | None = None,
+        menu: CursesMenu | None = None,
+        *,
         should_exit: bool = False,
-        override_index: Optional[str] = None,
-    ):
+        override_index: str | None = None,
+    ) -> None:
         """Initialize the item."""
-        self._submenu: Optional[CursesMenu] = submenu
-        self._menu: Optional[CursesMenu] = menu
+        self._submenu: CursesMenu | None = submenu
+        self._menu: CursesMenu | None = menu
         if self._submenu:
             self._submenu.parent = menu
-        super(SubmenuItem, self).__init__(
+        super().__init__(
             text=text,
             menu=menu,
             should_exit=should_exit,
             override_index=override_index,
         )
 
     @property
-    def submenu(self) -> Optional[CursesMenu]:
+    def submenu(self) -> CursesMenu | None:
         """Get the submenu associated with this item."""
         return self._submenu
 
     @submenu.setter
-    def submenu(self, submenu: Optional[CursesMenu]) -> None:
+    def submenu(self, submenu: CursesMenu | None) -> None:
         """Set the submenu and update its parent."""
         self._submenu = submenu
         if self._submenu is not None:
             self._submenu.parent = self._menu
 
     @property  # type: ignore[override]
-    def menu(self) -> Optional[CursesMenu]:  # type: ignore[override]
+    def menu(self) -> CursesMenu | None:  # type: ignore[override]
         """Get the menu that this item belongs to."""
         return self._menu
 
     @menu.setter
-    def menu(self, menu: Optional[CursesMenu]) -> None:
+    def menu(self, menu: CursesMenu | None) -> None:
         """Set the menu for the item and update the submenu's parent."""
         self._menu = menu
         if self._submenu is not None:
             self._submenu.parent = menu
 
     def set_up(self) -> None:
         """Set the screen up for the submenu."""
@@ -79,12 +82,12 @@
         """Block until the submenu is done and then return to the parent."""
         assert self.menu is not None
         assert self.submenu is not None
         self.submenu.join()
         self.submenu.clear_screen()
         self.menu.resume()
 
-    def get_return(self) -> Any:
+    def get_return(self) -> Any:  # noqa: ANN401
         """Get the returned value from the submenu."""
         if self.submenu is not None:
             return self.submenu.returned_value
         return None
```

### Comparing `curses-menu-0.6.7/cursesmenu/old_curses_menu.py` & `curses_menu-0.7.1/cursesmenu/old_curses_menu.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,32 +1,37 @@
 """
 A parser for the format of menu that this library started out as.
 
 Kept around for compatibility, and because it's a nice format for simple menus.
 """
 
+from __future__ import annotations
+
 from enum import Enum
-from typing import Any, Dict
+from typing import TYPE_CHECKING
 
 from cursesmenu import CursesMenu
 from cursesmenu.items import CommandItem, ExitItem, FunctionItem, SubmenuItem
 from cursesmenu.items.selection_item import SelectionItem
 
+if TYPE_CHECKING:
+    from typing import Any
+
 
 class MenuItemType(Enum):
     """An enum for the types of items in a simple menu."""
 
     MENU = "menu"
     COMMAND = "command"
     EXITMENU = "exitmenu"
     FUNCTION = "function"
     NUMBER = "number"
 
 
-def parse_old_menu(menu_data: Dict[str, Any]) -> CursesMenu:
+def parse_old_menu(menu_data: dict[str, Any]) -> CursesMenu:
     """
     Take an old-style menuData dictionary and return a CursesMenu.
 
     :param dict menu_data:
     :return: A new CursesMenu
     :rtype: CursesMenu
     """
```

### Comparing `curses-menu-0.6.7/docs/Makefile` & `curses_menu-0.7.1/docs/Makefile`

 * *Files identical despite different names*

### Comparing `curses-menu-0.6.7/docs/source/conf.py` & `curses_menu-0.7.1/docs/source/conf.py`

 * *Files 17% similar despite different names*

```diff
@@ -6,27 +6,27 @@
 
 # -- Path setup --------------------------------------------------------------
 
 # If extensions (or modules to document with autodoc) are in another directory,
 # add these directories to sys.path here. If the directory is relative to the
 # documentation root, use os.path.abspath to make it absolute, like shown here.
 #
-import os
+from __future__ import annotations
+
+import pathlib
 import sys
-from typing import List
 
-sys.path.insert(
-    0,
-    os.path.abspath(os.path.join(os.path.dirname(__file__), "..", "..", "cursesmenu")),
-)
+FILE_PATH = pathlib.Path(__file__)
+PROJECT_DIR = FILE_PATH.parent.joinpath("..", "..", "cursesmenu").resolve()
+sys.path.insert(0, str(PROJECT_DIR))
 
 # -- Project information -----------------------------------------------------
 
 project = "curses-menu"
-copyright = "2021, Paul Barrett"
+copyright = "2021, Paul Barrett"  # noqa: A001
 author = "Paul Barrett"
 
 # -- General configuration ---------------------------------------------------
 
 # Add any Sphinx extension module names here, as strings. They can be
 # extensions coming with Sphinx (named 'sphinx.ext.*') or your custom
 # ones.
@@ -38,15 +38,15 @@
 
 # Add any paths that contain templates here, relative to this directory.
 templates_path = ["_templates"]
 
 # List of patterns, relative to source directory, that match files and
 # directories to ignore when looking for source files.
 # This pattern also affects html_static_path and html_extra_path.
-exclude_patterns: List[str] = []
+exclude_patterns: list[str] = []
 
 # -- Options for HTML output -------------------------------------------------
 
 # The theme to use for HTML and HTML Help pages.  See the documentation for
 # a list of builtin themes.
 #
 html_theme = "sphinx_rtd_theme"
```

### Comparing `curses-menu-0.6.7/docs/source/cursesmenu/CursesMenu.rst` & `curses_menu-0.7.1/docs/source/cursesmenu/CursesMenu.rst`

 * *Files identical despite different names*

### Comparing `curses-menu-0.6.7/docs/source/usage.rst` & `curses_menu-0.7.1/docs/source/usage.rst`

 * *Files identical despite different names*

### Comparing `curses-menu-0.6.7/test/conftest.py` & `curses_menu-0.7.1/test/conftest.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 import sys
-import unittest.mock as mock
+from unittest import mock
 
 if not sys.platform.startswith("win"):  # pragma: no cover all
     import curses
 else:  # pragma: no cover all
     curses = None
 
 import pytest
 
 # noinspection PyUnresolvedReferences
-import cursesmenu.curses_menu
+import cursesmenu.curses_menu  # noqa: F401
 
 
 @pytest.fixture()
 def mock_clear():
     with mock.patch("cursesmenu.utils.clear_terminal") as f:
         with mock.patch("cursesmenu.utils.soft_clear_terminal") as g:
             yield f, g
@@ -53,20 +53,20 @@
     f.initscr.return_value = f.mock_window
     f.newpad.return_value = f.mock_window
     f.wrapper = wrapper
 
     return f
 
 
-@pytest.fixture
+@pytest.fixture()
 def mock_curses_window_size(window_rows, window_cols):
     return mock_curses_(window_rows, window_cols)
 
 
-@pytest.fixture
+@pytest.fixture()
 def mock_curses():
     return mock_curses_(99999999, 99999999)
 
 
 @pytest.fixture()
 def mock_cursesmenu_curses(mock_curses):
     with mock.patch("cursesmenu.curses_menu.curses", new=mock_curses) as f:
```

### Comparing `curses-menu-0.6.7/test/test_clear.py` & `curses_menu-0.7.1/test/test_clear.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import sys
 from unittest import mock
 
-import cursesmenu as cursesmenu
+import cursesmenu
 import cursesmenu.utils
 
 
 def test_clear():
     tmp_platform = sys.platform
     sys.platform = "win32"
     with mock.patch("cursesmenu.utils.os.system") as mock_system:
```

### Comparing `curses-menu-0.6.7/test/test_command_item.py` & `curses_menu-0.7.1/test/test_command_item.py`

 * *Files 3% similar despite different names*

```diff
@@ -10,35 +10,35 @@
     "mock_clear",
     "mock_externalitem_curses",
 )
 
 test_file_path = pathlib.Path("test.txt")
 
 
-@pytest.fixture
+@pytest.fixture()
 def create_item():
     return CommandItem(
         "create_item",
         "echo",
         arguments=["hello"],
         stdout_filepath=test_file_path,
     )
 
 
-@pytest.fixture
+@pytest.fixture()
 def delete_item():
     if sys.platform.startswith(
         "win",
     ):  # pragma: no-cover-nonwindows
         return CommandItem("delete_item", "del", arguments=[str(test_file_path)])
     else:  # pragma: no-cover-windows
         return CommandItem("delete_item", "rm", arguments=["-f", str(test_file_path)])
 
 
-@pytest.fixture
+@pytest.fixture()
 def exit_item():
     return CommandItem("return_command_item", "exit", arguments=["42"])
 
 
 def test_init():
     item1 = CommandItem("return_command_item", "exit")
     item2 = CommandItem("return_command_item", "echo", arguments=["hello"])
@@ -57,12 +57,12 @@
     assert exit_item.get_return() == 42
 
 
 def test_create(create_item: CommandItem, delete_item: CommandItem):
     create_item.action()
     assert create_item.get_return() == 0
     assert test_file_path.is_file()
-    with open(test_file_path, "r") as f:
+    with test_file_path.open("r") as f:
         assert f.read().strip() == "hello"
     delete_item.action()
     assert delete_item.get_return() == 0
     assert not test_file_path.exists()
```

### Comparing `curses-menu-0.6.7/test/test_curses_menu.py` & `curses_menu-0.7.1/test/test_curses_menu.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,51 +1,51 @@
-from typing import List
+from __future__ import annotations
 
 import pytest
 
 from cursesmenu import CursesMenu
 from cursesmenu.items import ExitItem, MenuItem
 
 pytestmark = pytest.mark.usefixtures("mock_cursesmenu_curses", "mock_clear")
 
 
-@pytest.fixture
+@pytest.fixture()
 def sample_items():
     item0 = MenuItem("item0")
     item1 = MenuItem("item1")
     return [item0, item1]
 
 
-@pytest.fixture
-def sample_menu(sample_items, mock_cursesmenu_curses_vary_window_size):
+@pytest.fixture()
+def sample_menu(sample_items, mock_cursesmenu_curses_vary_window_size):  # noqa: ARG001
     menu = CursesMenu("menu", "TestSampleMenu")
     menu.items.append(sample_items[0])
     menu.items.append(sample_items[1])
     menu.start()
     menu.wait_for_start(timeout=10)
     yield menu
     menu.exit()
     menu.join(timeout=10)
 
 
-@pytest.fixture
+@pytest.fixture()
 def empty_menu():
     menu = CursesMenu("menu", "empty menu", show_exit_item=False)
     menu.start()
     menu.wait_for_start(timeout=10)
     yield menu
     menu.exit()
     menu.join(timeout=10)
 
 
-@pytest.fixture
+@pytest.fixture()
 def big_menu():
     menu = CursesMenu("Test Menu")
     for i in range(100):
-        menu.items.append(MenuItem("item{}".format(i), should_exit=True))
+        menu.items.append(MenuItem(f"item{i}", should_exit=True))
     menu.start()
     menu.wait_for_start(timeout=10)
     yield menu
     menu.exit()
     menu.join(timeout=10)
 
 
@@ -54,43 +54,43 @@
     assert empty_menu.selected_item is None
     empty_menu.select()
     empty_menu.go_to_exit()
     empty_menu.join(timeout=10)
     assert not empty_menu.is_alive()
 
 
-def test_big_menu(big_menu: CursesMenu):
+def test_big_menu(big_menu: CursesMenu):  # noqa: ARG001
     pass
 
 
-def test_go_down(sample_menu: CursesMenu, sample_items: List[MenuItem]):
+def test_go_down(sample_menu: CursesMenu, sample_items: list[MenuItem]):
     sample_menu.go_down()
     assert sample_menu.current_option == 1
     assert sample_menu.current_item is sample_items[1]
     sample_menu.go_down()
     assert sample_menu.current_option == 2
     assert type(sample_menu.current_item) == ExitItem
     sample_menu.go_down()
     assert sample_menu.current_option == 0
     assert sample_menu.current_item is sample_items[0]
 
 
-def test_go_up(sample_menu: CursesMenu, sample_items: List[MenuItem]):
+def test_go_up(sample_menu: CursesMenu, sample_items: list[MenuItem]):
     sample_menu.go_up()
     assert sample_menu.current_option == 2
     assert type(sample_menu.current_item) == ExitItem
     sample_menu.go_up()
     assert sample_menu.current_option == 1
     assert sample_menu.current_item is sample_items[1]
     sample_menu.go_up()
     assert sample_menu.current_option == 0
     assert sample_menu.current_item is sample_items[0]
 
 
-def test_go_to(sample_menu: CursesMenu, sample_items: List[MenuItem]):
+def test_go_to(sample_menu: CursesMenu, sample_items: list[MenuItem]):
     sample_menu.go_to(ord("2"))
     assert sample_menu.current_option == 1
     assert sample_menu.current_item is sample_items[1]
     sample_menu.go_to(ord("7"))
     assert sample_menu.current_option == 1
     assert sample_menu.current_item is sample_items[1]
 
@@ -101,15 +101,15 @@
     assert big_menu.current_item == big_menu.items[7]
 
 
 def test_go_to_empty(empty_menu: CursesMenu):
     empty_menu.go_to(ord("1"))
 
 
-def test_select(sample_menu: CursesMenu, sample_items: List[MenuItem]):
+def test_select(sample_menu: CursesMenu, sample_items: list[MenuItem]):
     sample_menu.select()
     assert sample_menu.current_option == 0
     assert sample_menu.current_item is sample_items[0]
     sample_menu.go_down()
     sample_menu.select()
     assert sample_menu.current_option == 1
     assert sample_menu.current_item is sample_items[1]
@@ -131,15 +131,15 @@
     sample_menu.exit()
     sample_menu.join(timeout=10)
     assert not sample_menu.is_alive()
 
 
 def test_basic_menu():
     menu = CursesMenu("Test Menu")
-    menu.get_input = menu._exit
+    menu.get_input = menu._exit_with_return
     menu.show()
 
 
 def test_thread_stuff(sample_menu: CursesMenu):
     assert sample_menu.is_running()
     sample_menu.pause()
     assert not sample_menu.is_running()
@@ -166,16 +166,16 @@
     assert menu2.subtitle == "test_init"
     assert menu3.subtitle == "test_init"
 
 
 def test_null_screens_main_loop():
     menu = CursesMenu("menu", "empty menu", show_exit_item=False)
     CursesMenu.stdscr = None
-    menu.get_input = menu._exit
-    with pytest.raises(Exception):
+    menu.get_input = menu._exit_with_return
+    with pytest.raises((AttributeError, AssertionError)):
         menu._main_loop()
 
 
 def test_repr(sample_menu: CursesMenu):
     assert (
         repr(sample_menu) == f"<{sample_menu.title}: {sample_menu.subtitle}. "
         f"{len(sample_menu.items)} items>"
```

### Comparing `curses-menu-0.6.7/test/test_example_menus.py` & `curses_menu-0.7.1/test/test_example_menus.py`

 * *Files identical despite different names*

### Comparing `curses-menu-0.6.7/test/test_exit_item.py` & `curses_menu-0.7.1/test/test_exit_item.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 import pytest
 
 from cursesmenu import CursesMenu
 from cursesmenu.items import ExitItem, SubmenuItem
 
 
-@pytest.fixture
+@pytest.fixture()
 def exit_item():
     return ExitItem()
 
 
-@pytest.fixture
+@pytest.fixture()
 def exit_item_with_parent():
     root_menu = CursesMenu("root_menu")
     submenu = CursesMenu("submenu")
 
     submenu_item = SubmenuItem("submenu_item_1", submenu, menu=root_menu)
     root_menu.items.append(submenu_item)
     return submenu.end_items[0]
```

### Comparing `curses-menu-0.6.7/test/test_external_item.py` & `curses_menu-0.7.1/test/test_external_item.py`

 * *Files 12% similar despite different names*

```diff
@@ -6,22 +6,22 @@
 pytestmark = pytest.mark.usefixtures(
     "mock_cursesmenu_curses",
     "mock_clear",
     "mock_externalitem_curses",
 )
 
 
-@pytest.fixture
+@pytest.fixture()
 def external_items():
     item0 = ExternalItem("item0", should_exit=True)
     item1 = ExternalItem("item1", should_exit=True)
     return [item0, item1]
 
 
-@pytest.fixture
+@pytest.fixture()
 def menu_with_external_items(external_items):
     menu = CursesMenu("menu", "Test External Items")
     menu.items.append(external_items[0])
     menu.items.append(external_items[1])
     menu.start()
     menu.wait_for_start(timeout=10)
     yield menu
```

### Comparing `curses-menu-0.6.7/test/test_function_item.py` & `curses_menu-0.7.1/test/test_function_item.py`

 * *Files identical despite different names*

### Comparing `curses-menu-0.6.7/test/test_graphics.py` & `curses_menu-0.7.1/test/test_graphics.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,18 +1,25 @@
+from __future__ import annotations
+
 import os
 import pathlib
 import sys
-from typing import Generator, List
+from typing import TYPE_CHECKING, cast
 
 import pexpect
 import pexpect.popen_spawn
 import pyte
 import pytest
 
+if TYPE_CHECKING:
+    from typing import Generator
+
 TEST_DIR_PATH = pathlib.Path(__file__).parent.absolute()
+BASIC_MENU_PATH = TEST_DIR_PATH.joinpath("example_menus", "basic_menu.py")
+ITEM_MENU_PATH = TEST_DIR_PATH.joinpath("example_menus", "menu_with_items.py")
 
 on_bad_platform = sys.platform.startswith("win") or (
     "PYCHARM_HOSTED" in os.environ and "TOX_WORK_DIR" not in os.environ
 )
 
 
 @pytest.mark.skipif(
@@ -28,15 +35,15 @@
         self.filepath = filepath
         self.shell_command = f"python {self.filepath}"
 
     @property
     def bottom_row(self):
         return "m" + ("q" * (self.cols - 2)) + "j"
 
-    def spawn_process(self, cmd: str, args: List[str]):
+    def spawn_process(self, cmd: str, args: list[str]):
         env = os.environ.copy()
         env.update({"LINES": str(self.rows), "COLUMNS": str(self.cols)})
         if not sys.platform.startswith("win32"):
             return pexpect.spawn(
                 cmd,
                 args,
                 echo=False,
@@ -46,20 +53,20 @@
             )
         else:  # pragma: no cover all
             # this currently doesn't work on windows but I'm keeping this around
             # in case I decide to have another go at it later
             cmd = "{} {}".format(cmd, " ".join(args))
             return pexpect.popen_spawn.PopenSpawn(cmd, encoding="utf-8", env=env)
 
-    def emulate_ansi_terminal(self, raw_output: str, clean=True):
-        if raw_output in [pexpect.EOF, pexpect.TIMEOUT]:  # pragma: no cover all
+    def emulate_ansi_terminal(self, raw_output: str | None, *, clean=True):
+        if raw_output in [pexpect.EOF, pexpect.TIMEOUT, None]:  # pragma: no cover all
             return ""
-        self.stream.feed(raw_output)
+        self.stream.feed(cast(str, raw_output))
 
-        lines: List[str] | Generator[str, None, None] = self.screen.display
+        lines: list[str] | Generator[str, None, None] = self.screen.display
         self.screen.reset()
 
         if clean:  # pragma: no cover all
             lines = (line.rstrip() for line in lines)
             lines = (line for line in lines if line)
         lines = list(lines)
         return "\n".join(lines) + "\n"
@@ -67,17 +74,17 @@
 
 class TestBasicMenu(MenuTester):  # pragma: no-cover-windows
     def setup_method(
         self,
         _,
         rows=10,
         cols=40,
-        filepath=TEST_DIR_PATH.joinpath("example_menus", "basic_menu.py"),
+        filepath=BASIC_MENU_PATH,
     ):
-        super(TestBasicMenu, self).su(rows, cols, filepath)
+        super().su(rows, cols, filepath)
 
     def test_basic_menu(self):
         child = self.spawn_process(self.shell_command, [])
         child.expect([self.bottom_row, pexpect.EOF, pexpect.TIMEOUT], timeout=5)
         out = self.emulate_ansi_terminal(child.before) + self.emulate_ansi_terminal(
             child.after,
         )
@@ -90,20 +97,20 @@
 
         child.expect(pexpect.EOF, timeout=5)
 
 
 class TestMenuWithItems(MenuTester):  # pragma: no-cover-windows
     def setup_method(
         self,
-        method,
+        _,
         rows=10,
         cols=40,
-        filepath=TEST_DIR_PATH.joinpath("example_menus", "menu_with_items.py"),
+        filepath=ITEM_MENU_PATH,
     ):
-        super(TestMenuWithItems, self).su(rows, cols, filepath)
+        super().su(rows, cols, filepath)
 
     def test_basic_menu(self):
         child = self.spawn_process(self.shell_command, [])
         child.expect([self.bottom_row, pexpect.EOF, pexpect.TIMEOUT], timeout=5)
         out = self.emulate_ansi_terminal(child.before) + self.emulate_ansi_terminal(
             child.after,
         )
```

### Comparing `curses-menu-0.6.7/test/test_item_group.py` & `curses_menu-0.7.1/test/test_item_group.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,34 +1,34 @@
 import pytest
 
 from cursesmenu import CursesMenu
 from cursesmenu.item_group import ItemGroup
 from cursesmenu.items import MenuItem
 
 
-@pytest.fixture
+@pytest.fixture()
 def sample_items():
     item0 = MenuItem("item0")
     item1 = MenuItem("item1")
     return [item0, item1]
 
 
-@pytest.fixture
-def sample_menu(sample_items, mock_cursesmenu_curses_vary_window_size):
+@pytest.fixture()
+def sample_menu(sample_items, mock_cursesmenu_curses_vary_window_size):  # noqa: ARG001
     menu = CursesMenu("menu", "TestSampleMenu")
     menu.items.append(sample_items[0])
     menu.items.append(sample_items[1])
     menu.start()
     menu.wait_for_start(timeout=10)
     yield menu
     menu.exit()
     menu.join(timeout=10)
 
 
-@pytest.fixture
+@pytest.fixture()
 def sample_item_list(sample_menu):
     return ItemGroup(sample_menu, sample_menu.items)
 
 
 def test_init(sample_menu):
     item_list_1 = ItemGroup(sample_menu, sample_menu.items)
     item_list_2 = ItemGroup(sample_menu, None)
@@ -57,16 +57,16 @@
     new_item_2 = MenuItem("Item 5")
     new_items = [new_item_1, new_item_2]
     sample_item_list[0:1] = new_items
 
 
 def test_eq(sample_item_list):
     assert sample_item_list != 1
-
-    item_list_2 = ItemGroup(None, sample_item_list.items)
+    test_menu = CursesMenu("Test menu", "TestEqSampleMenu")
+    item_list_2 = ItemGroup(test_menu, sample_item_list.items)
     assert sample_item_list != item_list_2
     new_item = MenuItem("Item 6")
     item_list_3 = ItemGroup(
         sample_item_list.menu,
         [sample_item_list[0], sample_item_list[1], new_item],
     )
     assert sample_item_list != item_list_3
```

### Comparing `curses-menu-0.6.7/test/test_menu_item.py` & `curses_menu-0.7.1/test/test_menu_item.py`

 * *Files 27% similar despite different names*

```diff
@@ -1,22 +1,22 @@
 import pytest
 
 from cursesmenu import CursesMenu
 from cursesmenu.items import MenuItem
 
 
-@pytest.fixture
+@pytest.fixture()
 def basic_item():
-    yield MenuItem("item")
+    return MenuItem("item")
 
 
-@pytest.fixture
+@pytest.fixture()
 def item_with_menu():
     menu = CursesMenu()
-    yield MenuItem("item with menu", menu=menu)
+    return MenuItem("item with menu", menu=menu)
 
 
 def test_str(basic_item: MenuItem):
     assert str(basic_item) == " item"
 
 
 def test_return(basic_item: MenuItem):
```

### Comparing `curses-menu-0.6.7/test/test_submenu_item.py` & `curses_menu-0.7.1/test/test_submenu_item.py`

 * *Files identical despite different names*

### Comparing `curses-menu-0.6.7/tox.ini` & `curses_menu-0.7.1/tox.ini`

 * *Files 14% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 [tox]
-envlist = clean,py{37,38,39,310,311},py,pypy3,type,lint,docs
+envlist = clean,py{38,39,310,311},py,pypy3,type,lint,docs
 isolated_build = True
 
 [tox:.package]
 # note tox will use the same python version as under what tox is installed to package
 # so unless this is python 3 you can require a given python version for the packaging
 # environment via the basepython key
 basepython = python3
@@ -28,28 +28,29 @@
 deps =
     mypy >= 0.971, < 1
     types-Deprecated >= 1.2.9, < 2
     pytest  >= 7.1.2, < 8
 commands =
     mypy .
 
-basepython = python3.10
+basepython = python3.11
+
 [testenv:lint]
 deps =
-    flake8 >= 5.0.4, < 6
+    ruff == v0.0.275
 commands =
-    flake8 cursesmenu
-    flake8 test
-basepython = python3.10
+    ruff cursesmenu
+    ruff test
+basepython = python3.11
 
 
 [testenv:docs]
 description = invoke sphinx-build to build the HTML docs
-basepython = python3.10
-deps = sphinx >= 5.1.1, < 6
+basepython = python3.11
+deps = sphinx >= 6.0.0, < 7
        sphinx-autodoc-typehints >= 1.19.0, < 2
        sphinx-rtd-theme >= 1.0.0, < 2
        deprecated >= 1.2.13, < 2
 commands = sphinx-build -d "{toxworkdir}/docs_doctree" docs/source "{toxworkdir}/docs_out" --color -W -bhtml {posargs}
            python -c 'import pathlib; print("documentation available under file://\{0\}".format(pathlib.Path(r"{toxworkdir}") / "docs_out" / "index.html"))'
 
 [testenv:clean]
```

### Comparing `curses-menu-0.6.7/setup.py` & `curses_menu-0.7.1/PKG-INFO`

 * *Files 24% similar despite different names*

```diff
@@ -1,35 +1,111 @@
-# -*- coding: utf-8 -*-
-from setuptools import setup
+Metadata-Version: 2.1
+Name: curses-menu
+Version: 0.7.1
+Summary: A simple console menu system using curses
+Home-page: http://github.com/pmbarrett314/curses-menu
+License: MIT
+Author: Paul Barrett
+Author-email: pmbarrett314@gmail.com
+Requires-Python: >=3.8,<4.0
+Classifier: Development Status :: 3 - Alpha
+Classifier: Environment :: Console
+Classifier: Environment :: Console :: Curses
+Classifier: Intended Audience :: Developers
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Operating System :: OS Independent
+Classifier: Programming Language :: Python
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: Implementation :: CPython
+Classifier: Programming Language :: Python :: Implementation :: PyPy
+Classifier: Topic :: Software Development :: Libraries :: Python Modules
+Classifier: Typing :: Typed
+Requires-Dist: Deprecated (>=1.2.13,<2.0.0)
+Requires-Dist: windows-curses (>=2.3.1,<3.0.0) ; sys_platform == "win32"
+Project-URL: Repository, http://github.com/pmbarrett314/curses-menu
+Description-Content-Type: text/x-rst
+
+|Build Status|\ |Documentation Status|\ |Coverage Status|
+
+curses-menu
+===========
+
+A simple Python menu-based GUI system on the terminal using curses.
+Perfect for those times when you need a GUI, but don’t want the overhead
+or learning curve of a full-fledged GUI framework. However, it's also
+flexible enough to do cool stuff like on-the-fly changing of menus and is extensible to
+a large variety of uses.
+
+http://curses-menu.readthedocs.org/en/latest/
+
+.. image:: ./images/curses-menu_screenshot1.png
+
+
+Installation
+~~~~~~~~~~~~
+
+Tested on Python 3.8+ pypy and pypy3.
+
+The curses library comes bundled with python on Linux and MacOS. Windows
+users can visit http://www.lfd.uci.edu/~gohlke/pythonlibs/#curses and
+get a third-party build for your platform and Python version.
+
+Then just run
+
+.. code:: shell
+
+   pip install curses-menu
+
+Usage
+-----
+
+It’s designed to be pretty simple to use. Here’s an example
+
+.. code:: python
+
+    menu = CursesMenu("Root Menu", "Root Menu Subtitle")
+    item1 = MenuItem("Basic item that does nothing", menu)
+    function_item = FunctionItem("FunctionItem, get input", input, ["Enter an input: "])
+    print(__file__)
+    command_item = CommandItem(
+        "CommandItem that opens another menu",
+        f"python {__file__}",
+    )
+
+    submenu = CursesMenu.make_selection_menu([f"item{x}" for x in range(1, 20)])
+    submenu_item = SubmenuItem("Long Selection SubMenu", submenu=submenu, menu=menu)
+
+    submenu_2 = CursesMenu("Submenu Title", "Submenu subtitle")
+    function_item_2 = FunctionItem("Fun item", input, ["Enter an input"])
+    item2 = MenuItem("Another Item")
+    submenu_2.items.append(function_item_2)
+    submenu_2.items.append(item2)
+    submenu_item_2 = SubmenuItem("Short Submenu", submenu=submenu_2, menu=menu)
+
+    menu.items.append(item1)
+    menu.items.append(function_item)
+    menu.items.append(command_item)
+    menu.items.append(submenu_item)
+    menu.items.append(submenu_item_2)
+
+    menu.start()
+    _ = menu.join()
+
+Testing Information
+-------------------
+
+Currently the platforms I'm manually testing on are MacOS in iTerm2 on zsh with and without TMUX and Windows 10\
+with both powersehll and cmd.exe in and out of Windows Terminal. If a bug pops up on another configuration, \
+no promises that I'll be able to reproduce it.
+
+.. |Build Status| image:: https://github.com/pmbarrett314/curses-menu/actions/workflows/github-action-tox.yml/badge.svg
+   :target: https://github.com/pmbarrett314/curses-menu/actions/workflows/github-action-tox.yml/badge.svg
+.. |Documentation Status| image:: https://readthedocs.org/projects/curses-menu/badge/?version=latest
+   :target: http://curses-menu.readthedocs.org/en/latest/?badge=latest
+.. |Coverage Status| image:: https://coveralls.io/repos/github/pmbarrett314/curses-menu/badge.svg?branch=develop
+   :target: https://coveralls.io/github/pmbarrett314/curses-menu?branch=develop
 
-packages = \
-['cursesmenu', 'cursesmenu.items']
-
-package_data = \
-{'': ['*']}
-
-install_requires = \
-['Deprecated>=1.2.13,<2.0.0']
-
-extras_require = \
-{':python_version < "3.8"': ['importlib-metadata>=1.7.0'],
- ':sys_platform == "win32"': ['windows-curses==2.3.0']}
-
-setup_kwargs = {
-    'name': 'curses-menu',
-    'version': '0.6.7',
-    'description': 'A simple console menu system using curses',
-    'long_description': '|Build Status|\\ |Documentation Status|\\ |Coverage Status|\n\ncurses-menu\n===========\n\nA simple Python menu-based GUI system on the terminal using curses.\nPerfect for those times when you need a GUI, but don’t want the overhead\nor learning curve of a full-fledged GUI framework. However, it\'s also\nflexible enough to do cool stuff like on-the-fly changing of menus and is extensible to\na large variety of uses.\n\nhttp://curses-menu.readthedocs.org/en/latest/\n\n.. image:: ./images/curses-menu_screenshot1.png\n\n\nInstallation\n~~~~~~~~~~~~\n\nTested on Python 3.7+ pypy and pypy3.\n\nThe curses library comes bundled with python on Linux and MacOS. Windows\nusers can visit http://www.lfd.uci.edu/~gohlke/pythonlibs/#curses and\nget a third-party build for your platform and Python version.\n\nThen just run\n\n.. code:: shell\n\n   pip install curses-menu\n\nUsage\n-----\n\nIt’s designed to be pretty simple to use. Here’s an example\n\n.. code:: python\n\n    menu = CursesMenu("Root Menu", "Root Menu Subtitle")\n    item1 = MenuItem("Basic item that does nothing", menu)\n    function_item = FunctionItem("FunctionItem, get input", input, ["Enter an input: "])\n    print(__file__)\n    command_item = CommandItem(\n        "CommandItem that opens another menu",\n        f"python {__file__}",\n    )\n\n    submenu = CursesMenu.make_selection_menu([f"item{x}" for x in range(1, 20)])\n    submenu_item = SubmenuItem("Long Selection SubMenu", submenu=submenu, menu=menu)\n\n    submenu_2 = CursesMenu("Submenu Title", "Submenu subtitle")\n    function_item_2 = FunctionItem("Fun item", input, ["Enter an input"])\n    item2 = MenuItem("Another Item")\n    submenu_2.items.append(function_item_2)\n    submenu_2.items.append(item2)\n    submenu_item_2 = SubmenuItem("Short Submenu", submenu=submenu_2, menu=menu)\n\n    menu.items.append(item1)\n    menu.items.append(function_item)\n    menu.items.append(command_item)\n    menu.items.append(submenu_item)\n    menu.items.append(submenu_item_2)\n\n    menu.start()\n    _ = menu.join()\n\nTesting Information\n-------------------\n\nCurrently the platforms I\'m manually testing on are MacOS in iTerm2 on zsh with and without TMUX and Windows 10\\\nwith both powersehll and cmd.exe in and out of Windows Terminal. If a bug pops up on another configuration, \\\nno promises that I\'ll be able to reproduce it.\n\n.. |Build Status| image:: https://github.com/pmbarrett314/curses-menu/actions/workflows/github-action-tox.yml/badge.svg\n   :target: https://github.com/pmbarrett314/curses-menu/actions/workflows/github-action-tox.yml/badge.svg\n.. |Documentation Status| image:: https://readthedocs.org/projects/curses-menu/badge/?version=latest\n   :target: http://curses-menu.readthedocs.org/en/latest/?badge=latest\n.. |Coverage Status| image:: https://coveralls.io/repos/github/pmbarrett314/curses-menu/badge.svg?branch=develop\n   :target: https://coveralls.io/github/pmbarrett314/curses-menu?branch=develop\n',
-    'author': 'Paul Barrett',
-    'author_email': 'pmbarrett314@gmail.com',
-    'maintainer': 'None',
-    'maintainer_email': 'None',
-    'url': 'http://github.com/pmbarrett314/curses-menu',
-    'packages': packages,
-    'package_data': package_data,
-    'install_requires': install_requires,
-    'extras_require': extras_require,
-    'python_requires': '>=3.7,<4.0',
-}
-
-
-setup(**setup_kwargs)
```


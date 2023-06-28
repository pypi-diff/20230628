# Comparing `tmp/PySDL2-0.9.8.tar.gz` & `tmp/PySDL2-0.9.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "/Users/austinhurst/Documents/Programming/py-sdl2/dist/tmp1vgzaa1s/PySDL2-0.9.8.tar", last modified: Fri Aug  6 16:54:27 2021, max compression
+gzip compressed data, was "/Users/austinhurst/Documents/Programming/py-sdl2/dist/tmp_yatrw53/PySDL2-0.9.9.tar", last modified: Thu Sep  2 19:26:09 2021, max compression
```

## Comparing `PySDL2-0.9.8.tar` & `PySDL2-0.9.9.tar`

### file list

```diff
@@ -1,236 +1,234 @@
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/
--rw-r--r--   0 austinhurst   (501) staff       (20)      840 2021-08-06 16:48:15.000000 PySDL2-0.9.8/AUTHORS.txt
--rw-r--r--   0 austinhurst   (501) staff       (20)       20 2021-05-20 17:15:28.000000 PySDL2-0.9.8/COPYING.txt
--rw-r--r--   0 austinhurst   (501) staff       (20)       84 2021-05-20 17:15:28.000000 PySDL2-0.9.8/MANIFEST.in
--rw-r--r--   0 austinhurst   (501) staff       (20)     1324 2021-05-20 17:15:28.000000 PySDL2-0.9.8/Makefile
--rw-r--r--   0 austinhurst   (501) staff       (20)     3688 2021-08-06 16:54:27.000000 PySDL2-0.9.8/PKG-INFO
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/PySDL2.egg-info/
--rw-r--r--   0 austinhurst   (501) staff       (20)     3688 2021-08-06 16:54:27.000000 PySDL2-0.9.8/PySDL2.egg-info/PKG-INFO
--rw-r--r--   0 austinhurst   (501) staff       (20)     5358 2021-08-06 16:54:27.000000 PySDL2-0.9.8/PySDL2.egg-info/SOURCES.txt
--rw-r--r--   0 austinhurst   (501) staff       (20)        1 2021-08-06 16:54:27.000000 PySDL2-0.9.8/PySDL2.egg-info/dependency_links.txt
--rw-r--r--   0 austinhurst   (501) staff       (20)        5 2021-08-06 16:54:27.000000 PySDL2-0.9.8/PySDL2.egg-info/top_level.txt
--rw-r--r--   0 austinhurst   (501) staff       (20)     2524 2021-06-26 23:23:49.000000 PySDL2-0.9.8/README.md
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/doc/
--rw-r--r--   0 austinhurst   (501) staff       (20)     5598 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/Makefile
--rw-r--r--   0 austinhurst   (501) staff       (20)     8137 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/conf.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2322 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/copying.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     2856 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/faq.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)      690 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/index.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     2943 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/install.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     5858 2021-08-06 15:40:35.000000 PySDL2-0.9.8/doc/integration.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     5956 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/make.bat
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/doc/modules/
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/doc/modules/images/
--rw-r--r--   0 austinhurst   (501) staff       (20)      955 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/images/coordinate_rhs.dia
--rw-r--r--   0 austinhurst   (501) staff       (20)     2526 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/images/coordinate_rhs.png
--rw-r--r--   0 austinhurst   (501) staff       (20)     2407 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/images/copprocessing.dia
--rw-r--r--   0 austinhurst   (501) staff       (20)    16539 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/images/copprocessing.png
--rw-r--r--   0 austinhurst   (501) staff       (20)     1834 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/images/ebs.dia
--rw-r--r--   0 austinhurst   (501) staff       (20)    11350 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/images/ebs.png
--rw-r--r--   0 austinhurst   (501) staff       (20)     1862 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/images/uiprocessing.dia
--rw-r--r--   0 austinhurst   (501) staff       (20)    16200 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/images/uiprocessing.png
--rw-r--r--   0 austinhurst   (501) staff       (20)      447 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/index.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     5811 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)      678 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2_sdlgfx.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)      558 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2_sdlimage.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)      556 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2_sdlmixer.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)      534 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2_sdlttf.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)      881 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     1671 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_algorithms.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)    10339 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_array.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     4803 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_color.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     1297 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_colorpalettes.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     1285 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_common.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     2470 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_compat.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     1796 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_draw.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)    15917 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_ebs.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     2840 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_events.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     4109 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_font.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)    10857 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_gui.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)      965 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_image.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     3138 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_particles.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     2790 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_pixelaccess.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     6948 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_resources.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)    15151 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_sprite.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)      387 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_surface.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)     2548 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/modules/sdl2ext_window.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)    15490 2021-08-06 16:51:50.000000 PySDL2-0.9.8/doc/news.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)   114069 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/python.inv
--rw-r--r--   0 austinhurst   (501) staff       (20)      140 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/todos.rst
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/doc/tutorial/
--rw-r--r--   0 austinhurst   (501) staff       (20)     5509 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/tutorial/helloworld.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)      575 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/tutorial/index.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)    22390 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/tutorial/pong.rst
--rw-r--r--   0 austinhurst   (501) staff       (20)    16386 2021-05-20 17:15:28.000000 PySDL2-0.9.8/doc/tutorial/pygamers.rst
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/examples/
--rw-r--r--   0 austinhurst   (501) staff       (20)       75 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/__init__.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     7642 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/colorpalettes.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3991 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/draw.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    16160 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/gfxdrawing.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     6213 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/gui.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3491 2021-06-25 18:37:13.000000 PySDL2-0.9.8/examples/helloworld.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1564 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/opengl.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     9921 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/particles.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     4267 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/pixelaccess.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     7804 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/pong.py
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/examples/resources/
--rw-r--r--   0 austinhurst   (501) staff       (20)    15054 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/resources/button.bmp
--rw-r--r--   0 austinhurst   (501) staff       (20)      355 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/resources/circle.png
--rw-r--r--   0 austinhurst   (501) staff       (20)   254790 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/resources/font.bmp
--rw-r--r--   0 austinhurst   (501) staff       (20)  1089334 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/resources/hello.bmp
--rw-r--r--   0 austinhurst   (501) staff       (20)      272 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/resources/square.png
--rw-r--r--   0 austinhurst   (501) staff       (20)      380 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/resources/star.png
--rw-r--r--   0 austinhurst   (501) staff       (20)    49393 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/resources/testimage.svg
--rw-r--r--   0 austinhurst   (501) staff       (20)    15054 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/resources/textentry.bmp
--rw-r--r--   0 austinhurst   (501) staff       (20)   172324 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/resources/tuffy.ttf
--rw-r--r--   0 austinhurst   (501) staff       (20)     1121 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/sdl2hello.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2867 2021-05-20 17:15:28.000000 PySDL2-0.9.8/examples/transfomations.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1290 2021-05-20 17:15:28.000000 PySDL2-0.9.8/make.bat
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/sdl2/
--rw-r--r--   0 austinhurst   (501) staff       (20)     1821 2021-08-06 16:49:21.000000 PySDL2-0.9.8/sdl2/__init__.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     9163 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/audio.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1911 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/blendmode.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      389 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/clipboard.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1871 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/cpuinfo.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    11587 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/dll.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1496 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/endian.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1011 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/error.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    16375 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/events.py
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/sdl2/ext/
--rw-r--r--   0 austinhurst   (501) staff       (20)      564 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/ext/__init__.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     6480 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/algorithms.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    14029 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/array.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    19346 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/color.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    13628 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/colorpalettes.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3172 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/common.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3682 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/compat.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     7583 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/draw.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    10587 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/ext/ebs.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2978 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/ext/events.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    12873 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/font.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    23192 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/gui.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     5992 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/ext/image.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     4124 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/ext/particles.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     6458 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/pixelaccess.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    11084 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/ext/resources.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    29263 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/sprite.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      805 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/ext/surface.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     9713 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/ext/window.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      253 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/filesystem.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    12761 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/gamecontroller.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      716 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/gesture.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     8588 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/haptic.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    12350 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/hints.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     9006 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/joystick.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2124 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/keyboard.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    12452 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/keycode.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      329 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/loadso.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1610 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/locale.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3335 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/log.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2541 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/messagebox.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      936 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/metal.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      179 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/misc.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3781 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/mouse.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    16914 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/pixels.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      143 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/platform.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      560 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/power.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     4448 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/rect.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    12187 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/render.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     9747 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/rwops.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     6404 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/scancode.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    11355 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/sdlgfx.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     5912 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/sdlimage.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    11142 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/sdlmixer.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     8274 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/sdlttf.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2527 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/sensor.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1855 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/shape.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1394 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/stdinc.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     6914 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/surface.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     5178 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/syswm.py
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/sdl2/test/
--rw-r--r--   0 austinhurst   (501) staff       (20)       72 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/__init__.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    13945 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/audio_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      478 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/blendmode_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1924 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/clipboard_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2859 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/cpuinfo_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3540 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/endian_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1420 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/error_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     7649 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/events_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      891 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/filesystem_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    10688 2021-06-26 23:23:49.000000 PySDL2-0.9.8/sdl2/test/gamecontroller_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3294 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/hints_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    14766 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/joystick_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     6117 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/keyboard_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      366 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/locale_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    12537 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/log_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2636 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/metal_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1022 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/mouse_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    26025 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/pixels_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      640 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/platform_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1075 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/power_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    16352 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/rect_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    39510 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/test/render_test.py
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/sdl2/test/resources/
--rw-r--r--   0 austinhurst   (501) staff       (20)   254790 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/font.bmp
--rw-r--r--   0 austinhurst   (501) staff       (20)      400 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/resources.tar.gz
--rw-r--r--   0 austinhurst   (501) staff       (20)      744 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/resources.zip
--rw-r--r--   0 austinhurst   (501) staff       (20)      142 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/rwopstest.txt
--rw-r--r--   0 austinhurst   (501) staff       (20)     4150 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.bmp
--rw-r--r--   0 austinhurst   (501) staff       (20)     2238 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.cur
--rw-r--r--   0 austinhurst   (501) staff       (20)      979 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.gif
--rw-r--r--   0 austinhurst   (501) staff       (20)     2238 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.ico
--rw-r--r--   0 austinhurst   (501) staff       (20)      358 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.jpg
--rwxr-xr-x   0 austinhurst   (501) staff       (20)     3132 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.lbm
--rw-r--r--   0 austinhurst   (501) staff       (20)      160 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.pbm
--rw-r--r--   0 austinhurst   (501) staff       (20)      672 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.pcx
--rw-r--r--   0 austinhurst   (501) staff       (20)     1060 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.pgm
--rw-r--r--   0 austinhurst   (501) staff       (20)      139 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.png
--rw-r--r--   0 austinhurst   (501) staff       (20)     3085 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.pnm
--rw-r--r--   0 austinhurst   (501) staff       (20)     3108 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.ppm
--rw-r--r--   0 austinhurst   (501) staff       (20)      676 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.svg
--rw-r--r--   0 austinhurst   (501) staff       (20)     3090 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.tga
--rw-r--r--   0 austinhurst   (501) staff       (20)     3298 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.tif
--rw-r--r--   0 austinhurst   (501) staff       (20)      104 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.webp
--rw-r--r--   0 austinhurst   (501) staff       (20)     1054 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.xcf
--rw-r--r--   0 austinhurst   (501) staff       (20)     1299 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/surfacetest.xpm
--rw-r--r--   0 austinhurst   (501) staff       (20)   172324 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/tuffy.copy.ttf
--rw-r--r--   0 austinhurst   (501) staff       (20)   172324 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/resources/tuffy.ttf
--rw-r--r--   0 austinhurst   (501) staff       (20)    14110 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/rwops_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2062 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_algorithms_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    12487 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_array_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    23746 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_color_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     5570 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_draw_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     8893 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_ebs_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     6139 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_events_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     7482 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_font_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     4612 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_gui_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2602 2021-06-26 23:23:49.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_image_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3976 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_particles_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3823 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_pixelaccess_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     9856 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_resources_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    28525 2021-08-06 15:40:35.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_sprite_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2334 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     4076 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdl2ext_window_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1957 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdl_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     7323 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdlgfx_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    21892 2021-06-26 23:23:49.000000 PySDL2-0.9.8/sdl2/test/sdlimage_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     6515 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/sdlmixer_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    13281 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/sdlttf_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     4598 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/sensor_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     4926 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/shape_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    33563 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/surface_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1519 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/syswm_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     3099 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/timer_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     2175 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/touch_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1433 2021-06-27 19:13:27.000000 PySDL2-0.9.8/sdl2/test/version_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    43375 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/test/video_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      977 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/test/vulkan_test.py
--rw-r--r--   0 austinhurst   (501) staff       (20)      953 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/timer.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1555 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/touch.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1183 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/version.py
--rw-r--r--   0 austinhurst   (501) staff       (20)    18540 2021-06-25 18:37:13.000000 PySDL2-0.9.8/sdl2/video.py
--rw-r--r--   0 austinhurst   (501) staff       (20)     1234 2021-05-20 17:15:28.000000 PySDL2-0.9.8/sdl2/vulkan.py
--rw-r--r--   0 austinhurst   (501) staff       (20)       38 2021-08-06 16:54:27.000000 PySDL2-0.9.8/setup.cfg
--rw-r--r--   0 austinhurst   (501) staff       (20)     2413 2021-08-06 16:49:16.000000 PySDL2-0.9.8/setup.py
-drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-08-06 16:54:27.000000 PySDL2-0.9.8/util/
--rwxr-xr-x   0 austinhurst   (501) staff       (20)      863 2021-05-20 17:15:28.000000 PySDL2-0.9.8/util/valgrind.sh
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/
+-rw-r--r--   0 austinhurst   (501) staff       (20)      855 2021-09-02 19:20:10.000000 PySDL2-0.9.9/AUTHORS.txt
+-rw-r--r--   0 austinhurst   (501) staff       (20)       20 2021-05-20 17:15:28.000000 PySDL2-0.9.9/COPYING.txt
+-rw-r--r--   0 austinhurst   (501) staff       (20)       84 2021-05-20 17:15:28.000000 PySDL2-0.9.9/MANIFEST.in
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3688 2021-09-02 19:26:09.000000 PySDL2-0.9.9/PKG-INFO
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/PySDL2.egg-info/
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3688 2021-09-02 19:26:08.000000 PySDL2-0.9.9/PySDL2.egg-info/PKG-INFO
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5340 2021-09-02 19:26:09.000000 PySDL2-0.9.9/PySDL2.egg-info/SOURCES.txt
+-rw-r--r--   0 austinhurst   (501) staff       (20)        1 2021-09-02 19:26:08.000000 PySDL2-0.9.9/PySDL2.egg-info/dependency_links.txt
+-rw-r--r--   0 austinhurst   (501) staff       (20)        5 2021-09-02 19:26:08.000000 PySDL2-0.9.9/PySDL2.egg-info/top_level.txt
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2524 2021-06-26 23:23:49.000000 PySDL2-0.9.9/README.md
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/doc/
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5598 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/Makefile
+-rw-r--r--   0 austinhurst   (501) staff       (20)     8137 2021-09-02 19:18:12.000000 PySDL2-0.9.9/doc/conf.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2322 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/copying.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2856 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/faq.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)      690 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/index.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2943 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/install.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5858 2021-08-06 15:40:35.000000 PySDL2-0.9.9/doc/integration.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5956 2021-09-02 19:05:52.000000 PySDL2-0.9.9/doc/make.bat
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/doc/modules/
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/doc/modules/images/
+-rw-r--r--   0 austinhurst   (501) staff       (20)      955 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/images/coordinate_rhs.dia
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2526 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/images/coordinate_rhs.png
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2407 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/images/copprocessing.dia
+-rw-r--r--   0 austinhurst   (501) staff       (20)    16539 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/images/copprocessing.png
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1834 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/images/ebs.dia
+-rw-r--r--   0 austinhurst   (501) staff       (20)    11350 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/images/ebs.png
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1862 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/images/uiprocessing.dia
+-rw-r--r--   0 austinhurst   (501) staff       (20)    16200 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/images/uiprocessing.png
+-rw-r--r--   0 austinhurst   (501) staff       (20)      447 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/index.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5811 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)      678 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2_sdlgfx.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)      558 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2_sdlimage.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)      556 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2_sdlmixer.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)      534 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2_sdlttf.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)      881 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1671 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_algorithms.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)    10339 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_array.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4803 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_color.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1297 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_colorpalettes.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1285 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_common.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2470 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_compat.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1796 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_draw.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)    15917 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_ebs.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2840 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_events.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4109 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_font.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)    10857 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_gui.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)      965 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_image.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3138 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_particles.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2790 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_pixelaccess.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     6948 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_resources.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)    15151 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_sprite.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)      387 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_surface.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2548 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/modules/sdl2ext_window.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)    15825 2021-09-02 19:18:05.000000 PySDL2-0.9.9/doc/news.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)   114069 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/python.inv
+-rw-r--r--   0 austinhurst   (501) staff       (20)      140 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/todos.rst
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/doc/tutorial/
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5509 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/tutorial/helloworld.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)      575 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/tutorial/index.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)    22390 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/tutorial/pong.rst
+-rw-r--r--   0 austinhurst   (501) staff       (20)    16386 2021-05-20 17:15:28.000000 PySDL2-0.9.9/doc/tutorial/pygamers.rst
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/examples/
+-rw-r--r--   0 austinhurst   (501) staff       (20)       75 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/__init__.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     7642 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/colorpalettes.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3991 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/draw.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    16168 2021-09-02 19:05:52.000000 PySDL2-0.9.9/examples/gfxdrawing.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     6213 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/gui.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3491 2021-06-25 18:37:13.000000 PySDL2-0.9.9/examples/helloworld.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1564 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/opengl.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     9921 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/particles.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4267 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/pixelaccess.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     7804 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/pong.py
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/examples/resources/
+-rw-r--r--   0 austinhurst   (501) staff       (20)    15054 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/resources/button.bmp
+-rw-r--r--   0 austinhurst   (501) staff       (20)      355 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/resources/circle.png
+-rw-r--r--   0 austinhurst   (501) staff       (20)   254790 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/resources/font.bmp
+-rw-r--r--   0 austinhurst   (501) staff       (20)  1089334 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/resources/hello.bmp
+-rw-r--r--   0 austinhurst   (501) staff       (20)      272 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/resources/square.png
+-rw-r--r--   0 austinhurst   (501) staff       (20)      380 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/resources/star.png
+-rw-r--r--   0 austinhurst   (501) staff       (20)    49393 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/resources/testimage.svg
+-rw-r--r--   0 austinhurst   (501) staff       (20)    15054 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/resources/textentry.bmp
+-rw-r--r--   0 austinhurst   (501) staff       (20)   172324 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/resources/tuffy.ttf
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1121 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/sdl2hello.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2867 2021-05-20 17:15:28.000000 PySDL2-0.9.9/examples/transfomations.py
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/sdl2/
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1821 2021-09-02 19:18:11.000000 PySDL2-0.9.9/sdl2/__init__.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     9659 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/audio.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1911 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/blendmode.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      389 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/clipboard.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1871 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/cpuinfo.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    11587 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/dll.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1496 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/endian.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1011 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/error.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    16520 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/events.py
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/sdl2/ext/
+-rw-r--r--   0 austinhurst   (501) staff       (20)      564 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/ext/__init__.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     6480 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/algorithms.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    14029 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/array.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    19346 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/color.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    13628 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/colorpalettes.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3172 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/common.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3682 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/compat.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     7583 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/draw.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    10587 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/ext/ebs.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2978 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/ext/events.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    12873 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/font.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    23192 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/gui.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5992 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/ext/image.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4124 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/ext/particles.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     6458 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/pixelaccess.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    11084 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/ext/resources.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    29263 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/ext/sprite.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      805 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/ext/surface.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     9665 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/ext/window.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      253 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/filesystem.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    13286 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/gamecontroller.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      716 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/gesture.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     8588 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/haptic.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    14207 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/hints.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     9154 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/joystick.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2124 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/keyboard.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    12451 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/keycode.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      329 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/loadso.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1610 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/locale.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3335 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/log.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2541 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/messagebox.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      936 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/metal.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      179 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/misc.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3781 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/mouse.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    16914 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/pixels.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      143 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/platform.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      560 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/power.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4448 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/rect.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    12377 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/render.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     9747 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/rwops.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     6404 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/scancode.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    11355 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/sdlgfx.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5912 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/sdlimage.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    11142 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/sdlmixer.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     8274 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/sdlttf.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2527 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/sensor.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1855 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/shape.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1394 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/stdinc.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     7105 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/surface.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5523 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/syswm.py
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/sdl2/test/
+-rw-r--r--   0 austinhurst   (501) staff       (20)       72 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/__init__.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    15578 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/test/audio_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      478 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/blendmode_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1924 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/clipboard_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2859 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/test/cpuinfo_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3540 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/endian_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1420 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/test/error_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     7649 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/test/events_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      891 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/test/filesystem_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    11158 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/test/gamecontroller_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3294 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/test/hints_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    15046 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/test/joystick_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     6117 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/keyboard_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      366 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/test/locale_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    12537 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/log_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2636 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/test/metal_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1022 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/mouse_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    26025 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/pixels_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      640 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/platform_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1075 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/power_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    16352 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/rect_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    39678 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/test/render_test.py
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/sdl2/test/resources/
+-rw-r--r--   0 austinhurst   (501) staff       (20)   254790 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/font.bmp
+-rw-r--r--   0 austinhurst   (501) staff       (20)      400 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/resources.tar.gz
+-rw-r--r--   0 austinhurst   (501) staff       (20)      744 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/resources.zip
+-rw-r--r--   0 austinhurst   (501) staff       (20)      142 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/rwopstest.txt
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4150 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.bmp
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2238 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.cur
+-rw-r--r--   0 austinhurst   (501) staff       (20)      979 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.gif
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2238 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.ico
+-rw-r--r--   0 austinhurst   (501) staff       (20)      358 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.jpg
+-rwxr-xr-x   0 austinhurst   (501) staff       (20)     3132 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.lbm
+-rw-r--r--   0 austinhurst   (501) staff       (20)      160 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.pbm
+-rw-r--r--   0 austinhurst   (501) staff       (20)      672 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.pcx
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1060 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.pgm
+-rw-r--r--   0 austinhurst   (501) staff       (20)      139 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.png
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3085 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.pnm
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3108 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.ppm
+-rw-r--r--   0 austinhurst   (501) staff       (20)      676 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.svg
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3090 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.tga
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3298 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.tif
+-rw-r--r--   0 austinhurst   (501) staff       (20)      104 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.webp
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1054 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.xcf
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1299 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/surfacetest.xpm
+-rw-r--r--   0 austinhurst   (501) staff       (20)   172324 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/tuffy.copy.ttf
+-rw-r--r--   0 austinhurst   (501) staff       (20)   172324 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/resources/tuffy.ttf
+-rw-r--r--   0 austinhurst   (501) staff       (20)    14110 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/rwops_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2062 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_algorithms_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    12487 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_array_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    23746 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_color_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     5803 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_draw_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     8893 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_ebs_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     6139 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_events_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     7537 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_font_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4612 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_gui_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2602 2021-06-26 23:23:49.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_image_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3976 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_particles_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3823 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_pixelaccess_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     9856 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_resources_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    28525 2021-08-06 15:40:35.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_sprite_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2334 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4076 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdl2ext_window_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1957 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdl_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     7323 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdlgfx_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    21892 2021-06-26 23:23:49.000000 PySDL2-0.9.9/sdl2/test/sdlimage_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     6515 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/sdlmixer_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    13281 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/test/sdlttf_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4598 2021-06-25 18:37:13.000000 PySDL2-0.9.9/sdl2/test/sensor_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     4926 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/shape_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    33733 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/test/surface_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1519 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/syswm_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     3099 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/timer_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2175 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/touch_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1572 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/test/version_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    46330 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/test/video_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      977 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/test/vulkan_test.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)      953 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/timer.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1555 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/touch.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1223 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/version.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)    19738 2021-09-02 19:05:52.000000 PySDL2-0.9.9/sdl2/video.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)     1234 2021-05-20 17:15:28.000000 PySDL2-0.9.9/sdl2/vulkan.py
+-rw-r--r--   0 austinhurst   (501) staff       (20)       38 2021-09-02 19:26:09.000000 PySDL2-0.9.9/setup.cfg
+-rw-r--r--   0 austinhurst   (501) staff       (20)     2413 2021-09-02 19:18:07.000000 PySDL2-0.9.9/setup.py
+drwxr-xr-x   0 austinhurst   (501) staff       (20)        0 2021-09-02 19:26:09.000000 PySDL2-0.9.9/util/
+-rwxr-xr-x   0 austinhurst   (501) staff       (20)      863 2021-05-20 17:15:28.000000 PySDL2-0.9.9/util/valgrind.sh
```

### Comparing `PySDL2-0.9.8/AUTHORS.txt` & `PySDL2-0.9.9/AUTHORS.txt`

 * *Files 11% similar despite different names*

```diff
@@ -9,14 +9,15 @@
 * Marcel Rodrigues
 * Dan Gillett
 
 Thanks to everyone else for their assistance, support, fixes and improvements:
 
 * Andreas Schiefer
 * Bao "Mantle" Rong
+* Ben Greiner 
 * Bil Bas
 * Dan McCombs
 * David Farler
 * DBLobster
 * DR0ID
 * Fabian Jarrett
 * Filip M. Nowak
```

### Comparing `PySDL2-0.9.8/PKG-INFO` & `PySDL2-0.9.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: PySDL2
-Version: 0.9.8
+Version: 0.9.9
 Summary: Python SDL2 bindings
 Home-page: https://github.com/marcusva/py-sdl2
 Author: Marcus von Appen
 Author-email: marcus@sysfault.org
 License: Public Domain / zlib
 Download-URL: https://pypi.python.org/pypi/PySDL2
 Platform: UNKNOWN
```

### Comparing `PySDL2-0.9.8/PySDL2.egg-info/PKG-INFO` & `PySDL2-0.9.9/PySDL2.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: PySDL2
-Version: 0.9.8
+Version: 0.9.9
 Summary: Python SDL2 bindings
 Home-page: https://github.com/marcusva/py-sdl2
 Author: Marcus von Appen
 Author-email: marcus@sysfault.org
 License: Public Domain / zlib
 Download-URL: https://pypi.python.org/pypi/PySDL2
 Platform: UNKNOWN
```

### Comparing `PySDL2-0.9.8/PySDL2.egg-info/SOURCES.txt` & `PySDL2-0.9.9/PySDL2.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -1,13 +1,11 @@
 AUTHORS.txt
 COPYING.txt
 MANIFEST.in
-Makefile
 README.md
-make.bat
 setup.py
 PySDL2.egg-info/PKG-INFO
 PySDL2.egg-info/SOURCES.txt
 PySDL2.egg-info/dependency_links.txt
 PySDL2.egg-info/top_level.txt
 doc/Makefile
 doc/conf.py
```

### Comparing `PySDL2-0.9.8/README.md` & `PySDL2-0.9.9/README.md`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/Makefile` & `PySDL2-0.9.9/doc/Makefile`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/conf.py` & `PySDL2-0.9.9/doc/conf.py`

 * *Files 0% similar despite different names*

```diff
@@ -53,15 +53,15 @@
 # The version info for the project you're documenting, acts as replacement for
 # |version| and |release|, also used in various other places throughout the
 # built documents.
 #
 # The short X.Y version.
 version = '0.9'
 # The full version, including alpha/beta/rc tags.
-release = '0.9.8'
+release = '0.9.9'
 
 # The language for content autogenerated by Sphinx. Refer to documentation
 # for a list of supported languages.
 # language = None
 
 # There are two options for replacing |today|: either, you set today to some
 # non-false value, then it is used:
```

### Comparing `PySDL2-0.9.8/doc/copying.rst` & `PySDL2-0.9.9/doc/copying.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/faq.rst` & `PySDL2-0.9.9/doc/faq.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/index.rst` & `PySDL2-0.9.9/doc/index.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/install.rst` & `PySDL2-0.9.9/doc/install.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/integration.rst` & `PySDL2-0.9.9/doc/integration.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/make.bat` & `PySDL2-0.9.9/doc/make.bat`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/images/coordinate_rhs.dia` & `PySDL2-0.9.9/doc/modules/images/coordinate_rhs.dia`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/images/coordinate_rhs.png` & `PySDL2-0.9.9/doc/modules/images/coordinate_rhs.png`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/images/copprocessing.dia` & `PySDL2-0.9.9/doc/modules/images/copprocessing.dia`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/images/copprocessing.png` & `PySDL2-0.9.9/doc/modules/images/copprocessing.png`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/images/ebs.dia` & `PySDL2-0.9.9/doc/modules/images/ebs.dia`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/images/ebs.png` & `PySDL2-0.9.9/doc/modules/images/ebs.png`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/images/uiprocessing.dia` & `PySDL2-0.9.9/doc/modules/images/uiprocessing.dia`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/images/uiprocessing.png` & `PySDL2-0.9.9/doc/modules/images/uiprocessing.png`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2.rst` & `PySDL2-0.9.9/doc/modules/sdl2.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2_sdlgfx.rst` & `PySDL2-0.9.9/doc/modules/sdl2_sdlgfx.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2_sdlimage.rst` & `PySDL2-0.9.9/doc/modules/sdl2_sdlimage.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2_sdlmixer.rst` & `PySDL2-0.9.9/doc/modules/sdl2_sdlmixer.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2_sdlttf.rst` & `PySDL2-0.9.9/doc/modules/sdl2_sdlttf.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_algorithms.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_algorithms.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_array.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_array.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_color.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_color.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_colorpalettes.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_colorpalettes.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_common.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_common.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_compat.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_compat.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_draw.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_draw.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_ebs.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_ebs.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_events.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_events.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_font.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_font.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_gui.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_gui.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_image.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_image.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_particles.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_particles.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_pixelaccess.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_pixelaccess.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_resources.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_resources.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_sprite.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_sprite.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/modules/sdl2ext_window.rst` & `PySDL2-0.9.9/doc/modules/sdl2ext_window.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/news.rst` & `PySDL2-0.9.9/doc/news.rst`

 * *Files 1% similar despite different names*

```diff
@@ -1,11 +1,27 @@
 Release News
 ============
 This describes the latest changes between the PySDL2 releases.
 
+0.9.9
+-----
+
+Released on 2021-09-02.
+
+New Features:
+
+* Updated to wrap new functions and constants in in SDL2 2.0.16 (PR #190)
+
+Fixed bugs:
+
+* Reverted the fix for (issue #139), which inadvertantly caused a serious bug
+  that prevented usage of any non-software renderer with windows created using
+  :obj:`~sdl2.ext.Window` objects.
+
+
 0.9.8
 -----
 Released on 2021-08-06.
 
 New Features:
 
 * Updated to wrap new functions and constants in introduced in SDL2 2.0.12
```

### Comparing `PySDL2-0.9.8/doc/python.inv` & `PySDL2-0.9.9/doc/python.inv`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/tutorial/helloworld.rst` & `PySDL2-0.9.9/doc/tutorial/helloworld.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/tutorial/index.rst` & `PySDL2-0.9.9/doc/tutorial/index.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/tutorial/pong.rst` & `PySDL2-0.9.9/doc/tutorial/pong.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/doc/tutorial/pygamers.rst` & `PySDL2-0.9.9/doc/tutorial/pygamers.rst`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/colorpalettes.py` & `PySDL2-0.9.9/examples/colorpalettes.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/draw.py` & `PySDL2-0.9.9/examples/draw.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/gfxdrawing.py` & `PySDL2-0.9.9/examples/gfxdrawing.py`

 * *Files 0% similar despite different names*

```diff
@@ -346,15 +346,15 @@
                     curindex = 0
                 # In contrast to colorpalettes.py, our mapping table consists
                 # of functions and their arguments. Thus, we get the currently
                 # requested function and argument tuple and execute the
                 # function with the arguments.
                 func, args = functions[curindex]
                 func(*args)
+                context.present()
                 break
-        context.present()
     sdl2.ext.quit()
     return 0
 
 
 if __name__ == "__main__":
     sys.exit(run())
```

### Comparing `PySDL2-0.9.8/examples/gui.py` & `PySDL2-0.9.9/examples/gui.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/helloworld.py` & `PySDL2-0.9.9/examples/helloworld.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/opengl.py` & `PySDL2-0.9.9/examples/opengl.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/particles.py` & `PySDL2-0.9.9/examples/particles.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/pixelaccess.py` & `PySDL2-0.9.9/examples/pixelaccess.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/pong.py` & `PySDL2-0.9.9/examples/pong.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/resources/button.bmp` & `PySDL2-0.9.9/examples/resources/button.bmp`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/resources/font.bmp` & `PySDL2-0.9.9/examples/resources/font.bmp`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/resources/hello.bmp` & `PySDL2-0.9.9/examples/resources/hello.bmp`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/resources/testimage.svg` & `PySDL2-0.9.9/examples/resources/testimage.svg`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/resources/tuffy.ttf` & `PySDL2-0.9.9/examples/resources/tuffy.ttf`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/sdl2hello.py` & `PySDL2-0.9.9/examples/sdl2hello.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/examples/transfomations.py` & `PySDL2-0.9.9/examples/transfomations.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/__init__.py` & `PySDL2-0.9.9/sdl2/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -64,9 +64,9 @@
 
 SDL_Init = _bind("SDL_Init", [Uint32], _cint)
 SDL_InitSubSystem = _bind("SDL_InitSubSystem", [Uint32], _cint)
 SDL_QuitSubSystem = _bind("SDL_QuitSubSystem", [Uint32])
 SDL_WasInit = _bind("SDL_WasInit", [Uint32], Uint32)
 SDL_Quit = _bind("SDL_Quit")
 
-__version__ = "0.9.8"
-version_info = (0, 9, 8)
+__version__ = "0.9.9"
+version_info = (0, 9, 9)
```

### Comparing `PySDL2-0.9.8/sdl2/audio.py` & `PySDL2-0.9.9/sdl2/audio.py`

 * *Files 4% similar despite different names*

```diff
@@ -29,15 +29,16 @@
     # Macro Functions
     "SDL_AUDIO_ISBIGENDIAN", "SDL_AUDIO_ISSIGNED", "SDL_AUDIO_ISINT",
     "SDL_AUDIO_ISLITTLEENDIAN", "SDL_AUDIO_ISUNSIGNED", "SDL_LoadWAV",
 
     # Functions
     "SDL_GetNumAudioDrivers", "SDL_GetAudioDriver", "SDL_AudioInit",
     "SDL_AudioQuit", "SDL_GetCurrentAudioDriver", "SDL_OpenAudio",
-    "SDL_AudioDeviceID", "SDL_GetNumAudioDevices", "SDL_GetAudioDeviceName",
+    "SDL_AudioDeviceID", "SDL_GetNumAudioDevices",
+    "SDL_GetAudioDeviceName", "SDL_GetAudioDeviceSpec",
     "SDL_OpenAudioDevice", "SDL_GetAudioStatus", "SDL_GetAudioDeviceStatus",
     "SDL_PauseAudio", "SDL_PauseAudioDevice", "SDL_LoadWAV_RW", "SDL_FreeWAV",
     "SDL_BuildAudioCVT", "SDL_ConvertAudio",  "SDL_MixAudio",
     "SDL_MixAudioFormat", "SDL_LockAudio", "SDL_LockAudioDevice",
     "SDL_UnlockAudio", "SDL_UnlockAudioDevice", "SDL_CloseAudio",
     "SDL_CloseAudioDevice", "SDL_QueueAudio", "SDL_GetQueuedAudioSize",
     "SDL_ClearQueuedAudio", "SDL_DequeueAudio", "SDL_AudioStream",
@@ -81,14 +82,26 @@
 AUDIO_F32MSB = 0x9120
 AUDIO_F32 = AUDIO_F32LSB
 
 
 # All of the audio formats should be in this set which is provided as a
 # convenience to the end user for purposes of iteration and validation.
 # (is the provided audio format in the supported set?)
+FORMAT_NAME_MAP = {
+    AUDIO_U8: "AUDIO_U8",
+    AUDIO_S8: "AUDIO_S8",
+    AUDIO_U16LSB: "AUDIO_U16LSB",
+    AUDIO_S16LSB: "AUDIO_S16LSB",
+    AUDIO_U16MSB: "AUDIO_U16MSB",
+    AUDIO_S16MSB: "AUDIO_S16MSB",
+    AUDIO_S32LSB: "AUDIO_S32LSB",
+    AUDIO_S32MSB: "AUDIO_S32MSB",
+    AUDIO_F32LSB: "AUDIO_F32LSB",
+    AUDIO_F32MSB: "AUDIO_F32MSB",
+}
 AUDIO_FORMATS = set([AUDIO_U8, AUDIO_S8, AUDIO_U16LSB, AUDIO_S16LSB,
                      AUDIO_U16MSB, AUDIO_S16MSB, AUDIO_U16, AUDIO_S16,
                      AUDIO_S32LSB, AUDIO_S32MSB, AUDIO_S32, AUDIO_F32LSB,
                      AUDIO_F32MSB, AUDIO_F32])
 
 if SDL_BYTEORDER == SDL_LIL_ENDIAN:
     AUDIO_U16SYS = AUDIO_U16LSB
@@ -160,14 +173,15 @@
 SDL_AudioInit = _bind("SDL_AudioInit", [c_char_p], c_int)
 SDL_AudioQuit = _bind("SDL_AudioQuit")
 SDL_GetCurrentAudioDriver = _bind("SDL_GetCurrentAudioDriver", None, c_char_p)
 SDL_OpenAudio = _bind("SDL_OpenAudio", [POINTER(SDL_AudioSpec), POINTER(SDL_AudioSpec)], c_int)
 SDL_AudioDeviceID = Uint32
 SDL_GetNumAudioDevices = _bind("SDL_GetNumAudioDevices", [c_int], c_int)
 SDL_GetAudioDeviceName = _bind("SDL_GetAudioDeviceName", [c_int, c_int], c_char_p)
+SDL_GetAudioDeviceSpec = _bind("SDL_GetAudioDeviceSpec", [c_int, c_int, POINTER(SDL_AudioSpec)], c_int, added='2.0.16')
 SDL_OpenAudioDevice = _bind("SDL_OpenAudioDevice", [c_char_p, c_int, POINTER(SDL_AudioSpec), POINTER(SDL_AudioSpec), c_int], SDL_AudioDeviceID)
 SDL_AUDIO_STOPPED = 0
 SDL_AUDIO_PLAYING = 1
 SDL_AUDIO_PAUSED = 2
 SDL_AudioStatus = c_int
 SDL_GetAudioStatus = _bind("SDL_GetAudioStatus", None, SDL_AudioStatus)
 SDL_GetAudioDeviceStatus = _bind("SDL_GetAudioDeviceStatus", [SDL_AudioDeviceID], SDL_AudioStatus)
```

### Comparing `PySDL2-0.9.8/sdl2/blendmode.py` & `PySDL2-0.9.9/sdl2/blendmode.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/cpuinfo.py` & `PySDL2-0.9.9/sdl2/cpuinfo.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/dll.py` & `PySDL2-0.9.9/sdl2/dll.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/endian.py` & `PySDL2-0.9.9/sdl2/endian.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/error.py` & `PySDL2-0.9.9/sdl2/error.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/events.py` & `PySDL2-0.9.9/sdl2/events.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 from ctypes import c_char, c_char_p, c_float, c_void_p, c_int, Structure, \
-    Union, CFUNCTYPE, POINTER
+    Union, CFUNCTYPE, POINTER, sizeof
 from .dll import _bind
 from .stdinc import Sint16, Sint32, Uint8, Uint16, Uint32, SDL_bool
 from .keyboard import SDL_Keysym
 from .joystick import SDL_JoystickID
 from .touch import SDL_FingerID, SDL_TouchID
 from .gesture import SDL_GestureID
 from .syswm import SDL_SysWMmsg
@@ -400,14 +400,18 @@
 
 class SDL_SysWMEvent(Structure):
     _fields_ = [("type", Uint32),
                 ("timestamp", Uint32),
                 ("msg", POINTER(SDL_SysWMmsg))
                 ]
 
+_event_pad_size = 56 if sizeof(c_void_p) <= 8 else 64
+if sizeof(c_void_p) > 16:
+    _event_pad_size = 3 * sizeof(c_void_p)
+
 class SDL_Event(Union):
     _fields_ = [("type", Uint32),
                 ("common", SDL_CommonEvent),
                 ("display", SDL_DisplayEvent),
                 ("window", SDL_WindowEvent),
                 ("key", SDL_KeyboardEvent),
                 ("edit", SDL_TextEditingEvent),
@@ -430,15 +434,15 @@
                 ("quit", SDL_QuitEvent),
                 ("user", SDL_UserEvent),
                 ("syswm", SDL_SysWMEvent),
                 ("tfinger", SDL_TouchFingerEvent),
                 ("mgesture", SDL_MultiGestureEvent),
                 ("dgesture", SDL_DollarGestureEvent),
                 ("drop", SDL_DropEvent),
-                ("padding", (Uint8 * 56)),
+                ("padding", (Uint8 * _event_pad_size)),
                 ]
 
 
 SDL_eventaction = c_int
 
 SDL_ADDEVENT = 0
 SDL_PEEKEVENT = 1
```

### Comparing `PySDL2-0.9.8/sdl2/ext/__init__.py` & `PySDL2-0.9.9/sdl2/ext/__init__.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/algorithms.py` & `PySDL2-0.9.9/sdl2/ext/algorithms.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/array.py` & `PySDL2-0.9.9/sdl2/ext/array.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/color.py` & `PySDL2-0.9.9/sdl2/ext/color.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/colorpalettes.py` & `PySDL2-0.9.9/sdl2/ext/colorpalettes.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/common.py` & `PySDL2-0.9.9/sdl2/ext/common.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/compat.py` & `PySDL2-0.9.9/sdl2/ext/compat.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/draw.py` & `PySDL2-0.9.9/sdl2/ext/draw.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/ebs.py` & `PySDL2-0.9.9/sdl2/ext/ebs.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/events.py` & `PySDL2-0.9.9/sdl2/ext/events.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/font.py` & `PySDL2-0.9.9/sdl2/ext/font.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/gui.py` & `PySDL2-0.9.9/sdl2/ext/gui.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/image.py` & `PySDL2-0.9.9/sdl2/ext/image.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/particles.py` & `PySDL2-0.9.9/sdl2/ext/particles.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/pixelaccess.py` & `PySDL2-0.9.9/sdl2/ext/pixelaccess.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/resources.py` & `PySDL2-0.9.9/sdl2/ext/resources.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/sprite.py` & `PySDL2-0.9.9/sdl2/ext/sprite.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/surface.py` & `PySDL2-0.9.9/sdl2/ext/surface.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/ext/window.py` & `PySDL2-0.9.9/sdl2/ext/window.py`

 * *Files 0% similar despite different names*

```diff
@@ -182,15 +182,14 @@
     def show(self):
         """Shows the window on the display.
         
         If the window is already visible, this method does nothing.
 
         """
         video.SDL_ShowWindow(self.window)
-        video.SDL_GetWindowSurface(self.window)
 
     def hide(self):
         """Hides the window.
 
         If the window is already hidden, this method does nothing.
         
         """
```

### Comparing `PySDL2-0.9.8/sdl2/gamecontroller.py` & `PySDL2-0.9.9/sdl2/gamecontroller.py`

 * *Files 2% similar despite different names*

```diff
@@ -15,14 +15,15 @@
 
     # Enums
     "SDL_GameControllerType",
     "SDL_CONTROLLER_TYPE_UNKNOWN", "SDL_CONTROLLER_TYPE_XBOX360",
     "SDL_CONTROLLER_TYPE_XBOXONE", "SDL_CONTROLLER_TYPE_PS3",
     "SDL_CONTROLLER_TYPE_PS4", "SDL_CONTROLLER_TYPE_NINTENDO_SWITCH_PRO",
     "SDL_CONTROLLER_TYPE_VIRTUAL", "SDL_CONTROLLER_TYPE_PS5",
+    "SDL_CONTROLLER_TYPE_AMAZON_LUNA", "SDL_CONTROLLER_TYPE_GOOGLE_STADIA",
 
     "SDL_GameControllerBindType",
     "SDL_CONTROLLER_BINDTYPE_NONE", "SDL_CONTROLLER_BINDTYPE_BUTTON",
     "SDL_CONTROLLER_BINDTYPE_AXIS", "SDL_CONTROLLER_BINDTYPE_HAT", 
 
     "SDL_GameControllerAxis",
     "SDL_CONTROLLER_AXIS_INVALID", "SDL_CONTROLLER_AXIS_LEFTX",
@@ -69,17 +70,19 @@
     "SDL_GameControllerGetStringForButton",
     "SDL_GameControllerGetBindForButton", "SDL_GameControllerHasButton",
     "SDL_GameControllerGetButton",
     "SDL_GameControllerGetNumTouchpads",
     "SDL_GameControllerGetNumTouchpadFingers",
     "SDL_GameControllerGetTouchpadFinger",
     "SDL_GameControllerHasSensor", "SDL_GameControllerSetSensorEnabled",
-    "SDL_GameControllerIsSensorEnabled", "SDL_GameControllerGetSensorData",
+    "SDL_GameControllerIsSensorEnabled", 
+    "SDL_GameControllerGetSensorDataRate", "SDL_GameControllerGetSensorData",
     "SDL_GameControllerRumble", "SDL_GameControllerRumbleTriggers",
     "SDL_GameControllerHasLED", "SDL_GameControllerSetLED",
+    "SDL_GameControllerSendEffect",
     "SDL_GameControllerClose"  
 ]
 
 
 class SDL_GameController(c_void_p):
     pass
 
@@ -98,14 +101,16 @@
 SDL_CONTROLLER_TYPE_XBOX360 = 1
 SDL_CONTROLLER_TYPE_XBOXONE = 2
 SDL_CONTROLLER_TYPE_PS3 = 3
 SDL_CONTROLLER_TYPE_PS4 = 4
 SDL_CONTROLLER_TYPE_NINTENDO_SWITCH_PRO = 5
 SDL_CONTROLLER_TYPE_VIRTUAL = 6
 SDL_CONTROLLER_TYPE_PS5 = 7
+SDL_CONTROLLER_TYPE_AMAZON_LUNA = 8
+SDL_CONTROLLER_TYPE_GOOGLE_STADIA = 9
 
 
 class _gchat(Structure):
     _fields_ = [("hat", c_int), ("hat_mask", c_int)]
 
 class _gcvalue(Union):
     _fields_ = [("button", c_int), ("axis", c_int), ("hat", _gchat)]
@@ -183,14 +188,15 @@
 SDL_GameControllerGetButton = _bind("SDL_GameControllerGetButton", [POINTER(SDL_GameController), SDL_GameControllerButton], Uint8)
 SDL_GameControllerGetNumTouchpads = _bind("SDL_GameControllerGetNumTouchpads", [POINTER(SDL_GameController)], c_int, added='2.0.14')
 SDL_GameControllerGetNumTouchpadFingers = _bind("SDL_GameControllerGetNumTouchpadFingers", [POINTER(SDL_GameController), c_int], c_int, added='2.0.14')
 SDL_GameControllerGetTouchpadFinger = _bind("SDL_GameControllerGetTouchpadFinger", [POINTER(SDL_GameController), c_int, c_int, POINTER(Uint8), POINTER(c_float), POINTER(c_float), POINTER(c_float)], c_int, added='2.0.14')
 SDL_GameControllerHasSensor = _bind("SDL_GameControllerHasSensor", [POINTER(SDL_GameController), SDL_SensorType], SDL_bool, added='2.0.14')
 SDL_GameControllerSetSensorEnabled = _bind("SDL_GameControllerSetSensorEnabled", [POINTER(SDL_GameController), SDL_SensorType, SDL_bool], c_int, added='2.0.14')
 SDL_GameControllerIsSensorEnabled = _bind("SDL_GameControllerIsSensorEnabled", [POINTER(SDL_GameController), SDL_SensorType], SDL_bool, added='2.0.14')
+SDL_GameControllerGetSensorDataRate = _bind("SDL_GameControllerGetSensorDataRate", [POINTER(SDL_GameController), SDL_SensorType], c_float, added='2.0.16')
 # TODO: Read how GetSensorData is implemented to figure out how the # of floats is determined
 SDL_GameControllerGetSensorData = _bind("SDL_GameControllerGetSensorData", [POINTER(SDL_GameController), SDL_SensorType, POINTER(c_float), c_int], c_int, added='2.0.14')
 SDL_GameControllerClose = _bind("SDL_GameControllerClose", [POINTER(SDL_GameController)])
 SDL_GameControllerAddMappingsFromRW = _bind("SDL_GameControllerAddMappingsFromRW", [POINTER(SDL_RWops), c_int], c_int)
 SDL_GameControllerAddMappingsFromFile = lambda fname: SDL_GameControllerAddMappingsFromRW(SDL_RWFromFile(fname, b"rb"), 1)
 SDL_GameControllerFromInstanceID = _bind("SDL_GameControllerFromInstanceID", [SDL_JoystickID], POINTER(SDL_GameController))
 SDL_GameControllerFromPlayerIndex = _bind("SDL_GameControllerFromPlayerIndex", [c_int], POINTER(SDL_GameController), added='2.0.12')
@@ -203,14 +209,15 @@
 SDL_GameControllerNumMappings = _bind("SDL_GameControllerNumMappings", None, c_int, added='2.0.6')
 SDL_GameControllerMappingForIndex = _bind("SDL_GameControllerMappingForIndex", [c_int], c_char_p, added='2.0.6')
 SDL_GameControllerMappingForDeviceIndex = _bind("SDL_GameControllerMappingForDeviceIndex", [c_int], c_char_p, added='2.0.9')
 SDL_GameControllerRumble = _bind("SDL_GameControllerRumble", [POINTER(SDL_GameController), Uint16, Uint16, Uint32], c_int, added='2.0.9')
 SDL_GameControllerRumbleTriggers = _bind("SDL_GameControllerRumbleTriggers", [POINTER(SDL_GameController), Uint16, Uint16, Uint32], c_int, added='2.0.14')
 SDL_GameControllerHasLED = _bind("SDL_GameControllerHasLED", [POINTER(SDL_GameController)], SDL_bool, added='2.0.14')
 SDL_GameControllerSetLED = _bind("SDL_GameControllerSetLED", [POINTER(SDL_GameController), Uint8, Uint8, Uint8], c_int, added='2.0.14')
+SDL_GameControllerSendEffect = _bind("SDL_GameControllerSendEffect", [POINTER(SDL_GameController), c_void_p, c_int], c_int, added='2.0.16')
 
 # Reimplemented w/ other functions due to crash-causing ctypes bug (fixed in 3.8)
 if sys.version_info >= (3, 8, 0, 'final'):
     SDL_GameControllerMappingForGUID = _bind("SDL_GameControllerMappingForGUID", [SDL_JoystickGUID], c_char_p)
 else:
     def SDL_GameControllerMappingForGUID(guid):
         buff = create_string_buffer(33)
```

### Comparing `PySDL2-0.9.8/sdl2/gesture.py` & `PySDL2-0.9.9/sdl2/gesture.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/haptic.py` & `PySDL2-0.9.9/sdl2/haptic.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/hints.py` & `PySDL2-0.9.9/sdl2/hints.py`

 * *Files 2% similar despite different names*

```diff
@@ -2,33 +2,41 @@
 from .dll import _bind
 from .stdinc import SDL_bool
 
 __all__ = [
     # Defines
     "SDL_HINT_FRAMEBUFFER_ACCELERATION", "SDL_HINT_RENDER_DRIVER",
     "SDL_HINT_RENDER_OPENGL_SHADERS", "SDL_HINT_RENDER_SCALE_QUALITY",
-    "SDL_HINT_RENDER_VSYNC", "SDL_HINT_VIDEO_X11_XVIDMODE",
+    "SDL_HINT_RENDER_VSYNC", "SDL_HINT_VIDEO_WAYLAND_ALLOW_LIBDECOR",
+    "SDL_HINT_VIDEO_X11_XVIDMODE",
     "SDL_HINT_VIDEO_X11_XINERAMA", "SDL_HINT_VIDEO_X11_XRANDR",
     "SDL_HINT_VIDEO_X11_WINDOW_VISUALID",
     "SDL_HINT_VIDEO_X11_NET_WM_PING",
     "SDL_HINT_VIDEO_X11_NET_WM_BYPASS_COMPOSITOR",
     "SDL_HINT_VIDEO_X11_FORCE_EGL",
+    "SDL_HINT_X11_FORCE_OVERRIDE_REDIRECT",
     "SDL_HINT_GRAB_KEYBOARD", "SDL_HINT_VIDEO_MINIMIZE_ON_FOCUS_LOSS",
     "SDL_HINT_IDLE_TIMER_DISABLED", "SDL_HINT_ORIENTATIONS",
     "SDL_HINT_XINPUT_ENABLED",
     "SDL_HINT_ALLOW_TOPMOST", "SDL_HINT_JOYSTICK_ALLOW_BACKGROUND_EVENTS",
     "SDL_HINT_JOYSTICK_HIDAPI",
-    "SDL_HINT_JOYSTICK_HIDAPI_PS4", "SDL_HINT_JOYSTICK_HIDAPI_PS5",
-    "SDL_HINT_JOYSTICK_HIDAPI_PS4_RUMBLE",
+    "SDL_HINT_JOYSTICK_HIDAPI_PS4", "SDL_HINT_JOYSTICK_HIDAPI_PS4_RUMBLE",
+    "SDL_HINT_JOYSTICK_HIDAPI_PS5", "SDL_HINT_JOYSTICK_HIDAPI_PS5_RUMBLE",
+    "SDL_HINT_JOYSTICK_HIDAPI_PS5_PLAYER_LED",
+    "SDL_HINT_JOYSTICK_HIDAPI_STADIA",
     "SDL_HINT_JOYSTICK_HIDAPI_STEAM",
     "SDL_HINT_JOYSTICK_HIDAPI_SWITCH",
+    "SDL_HINT_JOYSTICK_HIDAPI_SWITCH_HOME_LED",
+    "SDL_HINT_JOYSTICK_HIDAPI_JOY_CONS",
     "SDL_HINT_JOYSTICK_HIDAPI_XBOX",
     "SDL_HINT_JOYSTICK_HIDAPI_CORRELATE_XINPUT",
     "SDL_HINT_JOYSTICK_HIDAPI_GAMECUBE",
+    "SDL_HINT_JOYSTICK_HIDAPI_LUNA",
     "SDL_HINT_ENABLE_STEAM_CONTROLLERS",
+    "SDL_HINT_JOYSTICK_RAWINPUT_CORRELATE_XINPUT",
     "SDL_HINT_JOYSTICK_RAWINPUT", "SDL_HINT_JOYSTICK_THREAD",
     "SDL_HINT_LINUX_JOYSTICK_DEADZONES", "SDL_HINT_AUTO_UPDATE_JOYSTICKS",
     "SDL_HINT_AUTO_UPDATE_SENSORS",
     "SDL_HINT_VIDEO_HIGHDPI_DISABLED",
     "SDL_HINT_ACCELEROMETER_AS_JOYSTICK",
     "SDL_HINT_MAC_CTRL_CLICK_EMULATE_RIGHT_CLICK",
     "SDL_HINT_RENDER_DIRECT3D_THREADSAFE",
@@ -61,14 +69,16 @@
     "SDL_HINT_MAC_BACKGROUND_APP",
     "SDL_HINT_WINDOWS_NO_CLOSE_ON_ALT_F4",
     "SDL_HINT_MOUSE_FOCUS_CLICKTHROUGH",
     "SDL_HINT_APPLE_TV_CONTROLLER_UI_EVENTS",
     "SDL_HINT_APPLE_TV_REMOTE_ALLOW_ROTATION",
     "SDL_HINT_BMP_SAVE_LEGACY_FORMAT",
     "SDL_HINT_WINDOWS_DISABLE_THREAD_NAMING",
+    "SDL_HINT_WINDOWS_FORCE_MUTEX_CRITICAL_SECTIONS",
+    "SDL_HINT_WINDOWS_FORCE_SEMAPHORE_KERNEL", "SDL_HINT_WINDOWS_USE_D3D9EX",
     "SDL_HINT_RPI_VIDEO_LAYER",
     "SDL_HINT_QTWAYLAND_CONTENT_ORIENTATION",
     "SDL_HINT_QTWAYLAND_WINDOW_FLAGS",
     "SDL_HINT_MOUSE_NORMAL_SPEED_SCALE",
     "SDL_HINT_MOUSE_RELATIVE_SPEED_SCALE",
     "SDL_HINT_MOUSE_RELATIVE_SCALING",
     "SDL_HINT_OPENGL_ES_DRIVER", "SDL_HINT_AUDIO_RESAMPLING_MODE",
@@ -79,19 +89,22 @@
     "SDL_HINT_GAMECONTROLLERCONFIG_FILE",
     "SDL_HINT_GAMECONTROLLER_IGNORE_DEVICES",
     "SDL_HINT_GAMECONTROLLER_IGNORE_DEVICES_EXCEPT",
     "SDL_HINT_GAMECONTROLLER_USE_BUTTON_LABELS",
     "SDL_HINT_WINDOWS_INTRESOURCE_ICON",
     "SDL_HINT_WINDOWS_INTRESOURCE_ICON_SMALL", "SDL_HINT_AUDIO_CATEGORY",
     "SDL_HINT_AUDIO_DEVICE_APP_NAME", "SDL_HINT_AUDIO_DEVICE_STREAM_NAME",
+    "SDL_HINT_AUDIO_DEVICE_STREAM_ROLE", "SDL_HINT_AUDIO_INCLUDE_MONITORS",
+    "SDL_HINT_ALLOW_ALT_TAB_WHILE_GRABBED",
     "SDL_HINT_PREFERRED_LOCALES",
     "SDL_HINT_RENDER_BATCHING", "SDL_HINT_EVENT_LOGGING",
     "SDL_HINT_WAVE_RIFF_CHUNK_SIZE", "SDL_HINT_WAVE_TRUNCATION",
     "SDL_HINT_WAVE_FACT_CHUNK", "SDL_HINT_DISPLAY_USABLE_BOUNDS",
-    "SDL_HINT_VIDEO_DOUBLE_BUFFER", "SDL_HINT_RETURN_KEY_HIDES_IME",
+    "SDL_HINT_VIDEO_DOUBLE_BUFFER", "SDL_HINT_KMSDRM_REQUIRE_DRM_MASTER",
+    "SDL_HINT_RETURN_KEY_HIDES_IME",
     "SDL_HINT_TV_REMOTE_AS_JOYSTICK", "SDL_HINT_IOS_HIDE_HOME_INDICATOR",
 
     # Enums
     "SDL_HintPriority",
     "SDL_HINT_DEFAULT", "SDL_HINT_NORMAL", "SDL_HINT_OVERRIDE",
 
     # Functions
@@ -110,23 +123,26 @@
 SDL_HINT_RENDER_DIRECT3D_THREADSAFE = b"SDL_RENDER_DIRECT3D_THREADSAFE"
 SDL_HINT_RENDER_DIRECT3D11_DEBUG = b"SDL_RENDER_DIRECT3D11_DEBUG"
 SDL_HINT_RENDER_LOGICAL_SIZE_MODE = b"SDL_RENDER_LOGICAL_SIZE_MODE"
 SDL_HINT_RENDER_SCALE_QUALITY = b"SDL_RENDER_SCALE_QUALITY"
 SDL_HINT_RENDER_VSYNC = b"SDL_RENDER_VSYNC"
 SDL_HINT_VIDEO_ALLOW_SCREENSAVER = b"SDL_VIDEO_ALLOW_SCREENSAVER"
 SDL_HINT_VIDEO_EXTERNAL_CONTEXT = b"SDL_VIDEO_EXTERNAL_CONTEXT"
+SDL_HINT_VIDEO_WAYLAND_ALLOW_LIBDECOR = b"SDL_VIDEO_WAYLAND_ALLOW_LIBDECOR"
 SDL_HINT_VIDEO_X11_XVIDMODE = b"SDL_VIDEO_X11_XVIDMODE"
 SDL_HINT_VIDEO_X11_XINERAMA = b"SDL_VIDEO_X11_XINERAMA"
 SDL_HINT_VIDEO_X11_XRANDR = b"SDL_VIDEO_X11_XRANDR"
 SDL_HINT_VIDEO_X11_WINDOW_VISUALID = b"SDL_VIDEO_X11_WINDOW_VISUALID"
 SDL_HINT_VIDEO_X11_NET_WM_PING = b"SDL_VIDEO_X11_NET_WM_PING"
 SDL_HINT_VIDEO_X11_NET_WM_BYPASS_COMPOSITOR = b"SDL_VIDEO_X11_NET_WM_BYPASS_COMPOSITOR"
 SDL_HINT_VIDEO_X11_FORCE_EGL = b"SDL_VIDEO_X11_FORCE_EGL"
+SDL_HINT_X11_FORCE_OVERRIDE_REDIRECT = b"SDL_X11_FORCE_OVERRIDE_REDIRECT"
 SDL_HINT_WINDOW_FRAME_USABLE_WHILE_CURSOR_HIDDEN = b"SDL_WINDOW_FRAME_USABLE_WHILE_CURSOR_HIDDEN"
 
+
 SDL_HINT_WINDOWS_INTRESOURCE_ICON = b"SDL_WINDOWS_INTRESOURCE_ICON"
 SDL_HINT_WINDOWS_INTRESOURCE_ICON_SMALL = b"SDL_WINDOWS_INTRESOURCE_ICON_SMALL"
 SDL_HINT_WINDOWS_ENABLE_MESSAGELOOP = b"SDL_WINDOWS_ENABLE_MESSAGELOOP"
 
 SDL_HINT_GRAB_KEYBOARD = b"SDL_GRAB_KEYBOARD"
 SDL_HINT_MOUSE_DOUBLE_CLICK_TIME = b"SDL_MOUSE_DOUBLE_CLICK_TIME"
 SDL_HINT_MOUSE_DOUBLE_CLICK_RADIUS = b"SDL_MOUSE_DOUBLE_CLICK_RADIUS"
@@ -154,23 +170,30 @@
 SDL_HINT_GAMECONTROLLERCONFIG_FILE = b"SDL_GAMECONTROLLERCONFIG_FILE"
 SDL_HINT_GAMECONTROLLER_IGNORE_DEVICES = b"SDL_GAMECONTROLLER_IGNORE_DEVICES"
 SDL_HINT_GAMECONTROLLER_IGNORE_DEVICES_EXCEPT = b"SDL_GAMECONTROLLER_IGNORE_DEVICES_EXCEPT"
 SDL_HINT_GAMECONTROLLER_USE_BUTTON_LABELS = b"SDL_GAMECONTROLLER_USE_BUTTON_LABELS"
 SDL_HINT_JOYSTICK_ALLOW_BACKGROUND_EVENTS = b"SDL_JOYSTICK_ALLOW_BACKGROUND_EVENTS"
 SDL_HINT_JOYSTICK_HIDAPI = b"SDL_JOYSTICK_HIDAPI"
 SDL_HINT_JOYSTICK_HIDAPI_PS4 = b"SDL_JOYSTICK_HIDAPI_PS4"
-SDL_HINT_JOYSTICK_HIDAPI_PS5 = b"SDL_JOYSTICK_HIDAPI_PS5"
 SDL_HINT_JOYSTICK_HIDAPI_PS4_RUMBLE = b"SDL_JOYSTICK_HIDAPI_PS4_RUMBLE"
+SDL_HINT_JOYSTICK_HIDAPI_PS5 = b"SDL_JOYSTICK_HIDAPI_PS5"
+SDL_HINT_JOYSTICK_HIDAPI_PS5_RUMBLE = b"SDL_JOYSTICK_HIDAPI_PS5_RUMBLE"
+SDL_HINT_JOYSTICK_HIDAPI_PS5_PLAYER_LED = b"SDL_JOYSTICK_HIDAPI_PS5_PLAYER_LED"
+SDL_HINT_JOYSTICK_HIDAPI_STADIA = b"SDL_JOYSTICK_HIDAPI_STADIA"
 SDL_HINT_JOYSTICK_HIDAPI_STEAM = b"SDL_JOYSTICK_HIDAPI_STEAM"
 SDL_HINT_JOYSTICK_HIDAPI_SWITCH = b"SDL_JOYSTICK_HIDAPI_SWITCH"
+SDL_HINT_JOYSTICK_HIDAPI_SWITCH_HOME_LED = b"SDL_JOYSTICK_HIDAPI_SWITCH_HOME_LED"
+SDL_HINT_JOYSTICK_HIDAPI_JOY_CONS = b"SDL_JOYSTICK_HIDAPI_JOY_CONS"
 SDL_HINT_JOYSTICK_HIDAPI_XBOX = b"SDL_JOYSTICK_HIDAPI_XBOX"
 SDL_HINT_JOYSTICK_HIDAPI_CORRELATE_XINPUT = b"SDL_JOYSTICK_HIDAPI_CORRELATE_XINPUT"
 SDL_HINT_JOYSTICK_HIDAPI_GAMECUBE = b"SDL_JOYSTICK_HIDAPI_GAMECUBE"
+SDL_HINT_JOYSTICK_HIDAPI_LUNA = b"SDL_JOYSTICK_HIDAPI_LUNA"
 SDL_HINT_ENABLE_STEAM_CONTROLLERS = b"SDL_ENABLE_STEAM_CONTROLLERS"
 SDL_HINT_JOYSTICK_RAWINPUT = b"SDL_JOYSTICK_RAWINPUT"
+SDL_HINT_JOYSTICK_RAWINPUT_CORRELATE_XINPUT = b"SDL_JOYSTICK_RAWINPUT_CORRELATE_XINPUT"
 SDL_HINT_JOYSTICK_THREAD = b"SDL_JOYSTICK_THREAD"
 SDL_HINT_LINUX_JOYSTICK_DEADZONES = b"SDL_LINUX_JOYSTICK_DEADZONES"
 SDL_HINT_AUTO_UPDATE_JOYSTICKS = b"SDL_AUTO_UPDATE_JOYSTICKS"
 SDL_HINT_AUTO_UPDATE_SENSORS = b"SDL_AUTO_UPDATE_SENSORS"
 
 SDL_HINT_ALLOW_TOPMOST = b"SDL_ALLOW_TOPMOST"
 SDL_HINT_TIMER_RESOLUTION = b"SDL_TIMER_RESOLUTION"
@@ -201,23 +224,31 @@
 
 SDL_HINT_EMSCRIPTEN_KEYBOARD_ELEMENT = b"SDL_EMSCRIPTEN_KEYBOARD_ELEMENT"
 SDL_HINT_EMSCRIPTEN_ASYNCIFY = b"SDL_EMSCRIPTEN_ASYNCIFY"
 SDL_HINT_NO_SIGNAL_HANDLERS = b"SDL_NO_SIGNAL_HANDLERS"
 SDL_HINT_WINDOWS_NO_CLOSE_ON_ALT_F4 = b"SDL_WINDOWS_NO_CLOSE_ON_ALT_F4"
 SDL_HINT_BMP_SAVE_LEGACY_FORMAT = b"SDL_BMP_SAVE_LEGACY_FORMAT"
 SDL_HINT_WINDOWS_DISABLE_THREAD_NAMING = b"SDL_WINDOWS_DISABLE_THREAD_NAMING"
+SDL_HINT_WINDOWS_FORCE_MUTEX_CRITICAL_SECTIONS = b"SDL_WINDOWS_FORCE_MUTEX_CRITICAL_SECTIONS"
+SDL_HINT_WINDOWS_FORCE_SEMAPHORE_KERNEL = b"SDL_WINDOWS_FORCE_SEMAPHORE_KERNEL"
+SDL_HINT_WINDOWS_USE_D3D9EX = b"SDL_WINDOWS_USE_D3D9EX"
 
 SDL_HINT_RPI_VIDEO_LAYER = b"SDL_RPI_VIDEO_LAYER"
 SDL_HINT_VIDEO_DOUBLE_BUFFER = b"SDL_VIDEO_DOUBLE_BUFFER"
+SDL_HINT_KMSDRM_REQUIRE_DRM_MASTER = b"SDL_KMSDRM_REQUIRE_DRM_MASTER"
 SDL_HINT_OPENGL_ES_DRIVER = b"SDL_OPENGL_ES_DRIVER"
 
 SDL_HINT_AUDIO_RESAMPLING_MODE = b"SDL_AUDIO_RESAMPLING_MODE"
 SDL_HINT_AUDIO_CATEGORY = b"SDL_AUDIO_CATEGORY"
 SDL_HINT_AUDIO_DEVICE_APP_NAME = b"SDL_AUDIO_DEVICE_APP_NAME"
 SDL_HINT_AUDIO_DEVICE_STREAM_NAME = b"SDL_AUDIO_DEVICE_STREAM_NAME"
+SDL_HINT_AUDIO_DEVICE_STREAM_ROLE = b"SDL_AUDIO_DEVICE_STREAM_ROLE"
+SDL_HINT_AUDIO_INCLUDE_MONITORS = b"SDL_AUDIO_INCLUDE_MONITORS"
+
+SDL_HINT_ALLOW_ALT_TAB_WHILE_GRABBED = b"SDL_ALLOW_ALT_TAB_WHILE_GRABBED"
 SDL_HINT_PREFERRED_LOCALES = b"SDL_PREFERRED_LOCALES"
 SDL_HINT_RENDER_BATCHING  = b"SDL_RENDER_BATCHING"
 SDL_HINT_EVENT_LOGGING = b"SDL_EVENT_LOGGING"
 SDL_HINT_WAVE_RIFF_CHUNK_SIZE = b"SDL_WAVE_RIFF_CHUNK_SIZE"
 SDL_HINT_WAVE_TRUNCATION = b"SDL_WAVE_TRUNCATION"
 SDL_HINT_WAVE_FACT_CHUNK = b"SDL_WAVE_FACT_CHUNK"
 SDL_HINT_DISPLAY_USABLE_BOUNDS = b"SDL_DISPLAY_USABLE_BOUNDS"
```

### Comparing `PySDL2-0.9.8/sdl2/joystick.py` & `PySDL2-0.9.9/sdl2/joystick.py`

 * *Files 1% similar despite different names*

```diff
@@ -44,15 +44,15 @@
     "SDL_JoystickGetType", "SDL_JoystickGetGUIDString",
     "SDL_JoystickGetGUIDFromString", "SDL_JoystickGetAttached",
     "SDL_JoystickInstanceID", "SDL_JoystickNumAxes", "SDL_JoystickNumBalls",
     "SDL_JoystickNumHats", "SDL_JoystickNumButtons", "SDL_JoystickUpdate",
     "SDL_JoystickEventState", "SDL_JoystickGetAxis", "SDL_JoystickGetAxisInitialState",
     "SDL_JoystickGetHat", "SDL_JoystickGetBall", "SDL_JoystickGetButton",
     "SDL_JoystickRumble", "SDL_JoystickRumbleTriggers",
-    "SDL_JoystickHasLED", "SDL_JoystickSetLED",
+    "SDL_JoystickHasLED", "SDL_JoystickSetLED", "SDL_JoystickSendEffect",
     "SDL_JoystickClose", "SDL_JoystickCurrentPowerLevel"
 ]
 
 
 SDL_JoystickPowerLevel = c_int
 
 SDL_JOYSTICK_POWER_UNKNOWN = -1
@@ -145,14 +145,15 @@
 SDL_JoystickGetPlayerIndex = _bind("SDL_JoystickGetPlayerIndex", [POINTER(SDL_Joystick)], c_int, added='2.0.9')
 SDL_JoystickSetPlayerIndex = _bind("SDL_JoystickSetPlayerIndex", [POINTER(SDL_Joystick), c_int], added='2.0.12')
 SDL_JoystickGetDevicePlayerIndex = _bind("SDL_JoystickGetDevicePlayerIndex", [c_int], c_int, added='2.0.9')
 SDL_JoystickRumble = _bind("SDL_JoystickRumble", [POINTER(SDL_Joystick), Uint16, Uint16, Uint32], c_int, added='2.0.9')
 SDL_JoystickRumbleTriggers = _bind("SDL_JoystickRumbleTriggers", [POINTER(SDL_Joystick), Uint16, Uint16, Uint32], c_int, added='2.0.14')
 SDL_JoystickHasLED = _bind("SDL_JoystickHasLED", [POINTER(SDL_Joystick)], SDL_bool, added='2.0.14')
 SDL_JoystickSetLED = _bind("SDL_JoystickSetLED", [POINTER(SDL_Joystick), Uint8, Uint8, Uint8], c_int, added='2.0.14')
+SDL_JoystickSendEffect = _bind("SDL_JoystickSendEffect", [POINTER(SDL_Joystick), c_void_p, c_int], c_int, added='2.0.16')
 
 # Reimplemented in Python due to crash-causing ctypes bug (fixed in 3.8)
 if sys.version_info >= (3, 8, 0, 'final'):
     SDL_JoystickGetGUIDString = _bind("SDL_JoystickGetGUIDString", [SDL_JoystickGUID, c_char_p, c_int])
 else:
     def SDL_JoystickGetGUIDString(guid, pszGUID, cbGUID):
         s = ""
```

### Comparing `PySDL2-0.9.8/sdl2/keyboard.py` & `PySDL2-0.9.9/sdl2/keyboard.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/keycode.py` & `PySDL2-0.9.9/sdl2/keycode.py`

 * *Files 1% similar despite different names*

```diff
@@ -17,27 +17,26 @@
 KMOD_RALT = 0x0200
 KMOD_LGUI = 0x0400
 KMOD_RGUI = 0x0800
 KMOD_NUM = 0x1000
 KMOD_CAPS = 0x2000
 KMOD_MODE = 0x4000
 KMOD_RESERVED = 0x8000
-
 KMOD_CTRL = KMOD_LCTRL | KMOD_RCTRL
 KMOD_SHIFT = KMOD_LSHIFT | KMOD_RSHIFT
 KMOD_ALT = KMOD_LALT | KMOD_RALT
 KMOD_GUI = KMOD_LGUI | KMOD_RGUI
 
 
 SDL_KeyCode = c_int
 
 SDLK_UNKNOWN = 0
 
 SDLK_RETURN = ord('\r')
-SDLK_ESCAPE = ord('\033')
+SDLK_ESCAPE = ord('\x1B')
 SDLK_BACKSPACE = ord('\b')
 SDLK_TAB = ord('\t')
 SDLK_SPACE = ord(' ')
 SDLK_EXCLAIM = ord('!')
 SDLK_QUOTEDBL = ord('"')
 SDLK_HASH = ord('#')
 SDLK_PERCENT = ord('%')
@@ -123,15 +122,15 @@
 
 SDLK_PRINTSCREEN = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_PRINTSCREEN)
 SDLK_SCROLLLOCK = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_SCROLLLOCK)
 SDLK_PAUSE = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_PAUSE)
 SDLK_INSERT = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_INSERT)
 SDLK_HOME = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_HOME)
 SDLK_PAGEUP = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_PAGEUP)
-SDLK_DELETE = ord('\177')
+SDLK_DELETE = ord('\x7F')
 SDLK_END = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_END)
 SDLK_PAGEDOWN = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_PAGEDOWN)
 SDLK_RIGHT = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_RIGHT)
 SDLK_LEFT = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_LEFT)
 SDLK_DOWN = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_DOWN)
 SDLK_UP = SDL_SCANCODE_TO_KEYCODE(SDL_SCANCODE_UP)
```

### Comparing `PySDL2-0.9.8/sdl2/locale.py` & `PySDL2-0.9.9/sdl2/locale.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/log.py` & `PySDL2-0.9.9/sdl2/log.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/messagebox.py` & `PySDL2-0.9.9/sdl2/messagebox.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/metal.py` & `PySDL2-0.9.9/sdl2/metal.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/mouse.py` & `PySDL2-0.9.9/sdl2/mouse.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/pixels.py` & `PySDL2-0.9.9/sdl2/pixels.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/power.py` & `PySDL2-0.9.9/sdl2/power.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/rect.py` & `PySDL2-0.9.9/sdl2/rect.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/render.py` & `PySDL2-0.9.9/sdl2/render.py`

 * *Files 1% similar despite different names*

```diff
@@ -55,15 +55,16 @@
     "SDL_RenderCopy", "SDL_RenderCopyEx", "SDL_RenderDrawPointF",
     "SDL_RenderDrawPointsF", "SDL_RenderDrawLineF",
     "SDL_RenderDrawLinesF", "SDL_RenderDrawRectF",
     "SDL_RenderDrawRectsF", "SDL_RenderFillRectF",
     "SDL_RenderFillRectsF", "SDL_RenderCopyF", "SDL_RenderCopyExF",
     "SDL_RenderReadPixels", "SDL_RenderPresent",
     "SDL_DestroyTexture", "SDL_DestroyRenderer", "SDL_RenderFlush",
-    "SDL_UpdateYUVTexture", "SDL_GL_BindTexture", "SDL_GL_UnbindTexture",
+    "SDL_UpdateYUVTexture", "SDL_UpdateNVTexture",
+    "SDL_GL_BindTexture", "SDL_GL_UnbindTexture",
     "SDL_GetRendererOutputSize", "SDL_RenderGetIntegerScale",
     "SDL_RenderSetIntegerScale", "SDL_RenderGetMetalLayer",
     "SDL_RenderGetMetalCommandEncoder"
 ]
 
 
 SDL_RendererFlags = c_int
@@ -176,9 +177,10 @@
 SDL_RenderPresent = _bind("SDL_RenderPresent", [POINTER(SDL_Renderer)])
 SDL_DestroyTexture = _bind("SDL_DestroyTexture", [POINTER(SDL_Texture)])
 SDL_DestroyRenderer = _bind("SDL_DestroyRenderer", [POINTER(SDL_Renderer)])
 SDL_RenderFlush = _bind("SDL_RenderFlush", [POINTER(SDL_Renderer)], c_int, added='2.0.10')
 SDL_GL_BindTexture = _bind("SDL_GL_BindTexture", [POINTER(SDL_Texture), POINTER(c_float), POINTER(c_float)], c_int)
 SDL_GL_UnbindTexture = _bind("SDL_GL_UnbindTexture", [POINTER(SDL_Texture)], c_int)
 SDL_UpdateYUVTexture = _bind("SDL_UpdateYUVTexture", [POINTER(SDL_Texture), POINTER(SDL_Rect), POINTER(Uint8), c_int, POINTER(Uint8), c_int, POINTER(Uint8), c_int], c_int)
+SDL_UpdateNVTexture = _bind("SDL_UpdateNVTexture", [POINTER(SDL_Texture), POINTER(SDL_Rect), POINTER(Uint8), c_int, POINTER(Uint8), c_int], c_int, added='2.0.16')
 SDL_RenderGetMetalLayer = _bind("SDL_RenderGetMetalLayer", [POINTER(SDL_Renderer)], c_void_p, added='2.0.8')
 SDL_RenderGetMetalCommandEncoder = _bind("SDL_RenderGetMetalCommandEncoder", [POINTER(SDL_Renderer)], c_void_p, added='2.0.8')
```

### Comparing `PySDL2-0.9.8/sdl2/rwops.py` & `PySDL2-0.9.9/sdl2/rwops.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/scancode.py` & `PySDL2-0.9.9/sdl2/scancode.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/sdlgfx.py` & `PySDL2-0.9.9/sdl2/sdlgfx.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/sdlimage.py` & `PySDL2-0.9.9/sdl2/sdlimage.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/sdlmixer.py` & `PySDL2-0.9.9/sdl2/sdlmixer.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/sdlttf.py` & `PySDL2-0.9.9/sdl2/sdlttf.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/sensor.py` & `PySDL2-0.9.9/sdl2/sensor.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/shape.py` & `PySDL2-0.9.9/sdl2/shape.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/stdinc.py` & `PySDL2-0.9.9/sdl2/stdinc.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/surface.py` & `PySDL2-0.9.9/sdl2/surface.py`

 * *Files 1% similar despite different names*

```diff
@@ -25,15 +25,16 @@
     "SDL_HasColorKey", "SDL_SetColorKey", "SDL_GetColorKey",
     "SDL_SetSurfaceColorMod", "SDL_GetSurfaceColorMod",
     "SDL_SetSurfaceAlphaMod", "SDL_GetSurfaceAlphaMod",
     "SDL_SetSurfaceBlendMode", "SDL_GetSurfaceBlendMode",
     "SDL_SetClipRect", "SDL_GetClipRect", "SDL_ConvertSurface",
     "SDL_ConvertSurfaceFormat", "SDL_ConvertPixels", "SDL_FillRect",
     "SDL_FillRects", "SDL_UpperBlit", "SDL_BlitSurface", "SDL_LowerBlit",
-    "SDL_SoftStretch", "SDL_UpperBlitScaled", "SDL_BlitScaled",
+    "SDL_SoftStretch", "SDL_SoftStretchLinear",
+    "SDL_UpperBlitScaled", "SDL_BlitScaled",
     "SDL_LowerBlitScaled", "SDL_CreateRGBSurfaceWithFormat",
     "SDL_CreateRGBSurfaceWithFormatFrom", "SDL_DuplicateSurface",
     "SDL_SetYUVConversionMode", "SDL_GetYUVConversionMode",
     "SDL_GetYUVConversionModeForResolution",
 
     # Callback Functions
     "SDL_Blit"
@@ -107,14 +108,15 @@
 SDL_FillRect = _bind("SDL_FillRect", [POINTER(SDL_Surface), POINTER(SDL_Rect), Uint32], c_int)
 SDL_FillRects = _bind("SDL_FillRects", [POINTER(SDL_Surface), POINTER(SDL_Rect), c_int, Uint32], c_int)
 
 SDL_UpperBlit = _bind("SDL_UpperBlit", [POINTER(SDL_Surface), POINTER(SDL_Rect), POINTER(SDL_Surface), POINTER(SDL_Rect)], c_int)
 SDL_BlitSurface = SDL_UpperBlit
 SDL_LowerBlit = _bind("SDL_LowerBlit", [POINTER(SDL_Surface), POINTER(SDL_Rect), POINTER(SDL_Surface), POINTER(SDL_Rect)], c_int)
 SDL_SoftStretch = _bind("SDL_SoftStretch", [POINTER(SDL_Surface), POINTER(SDL_Rect), POINTER(SDL_Surface), POINTER(SDL_Rect)], c_int)
+SDL_SoftStretchLinear = _bind("SDL_SoftStretchLinear", [POINTER(SDL_Surface), POINTER(SDL_Rect), POINTER(SDL_Surface), POINTER(SDL_Rect)], c_int, added='2.0.16')
 SDL_UpperBlitScaled = _bind("SDL_UpperBlitScaled", [POINTER(SDL_Surface), POINTER(SDL_Rect), POINTER(SDL_Surface), POINTER(SDL_Rect)], c_int)
 SDL_BlitScaled = SDL_UpperBlitScaled
 SDL_LowerBlitScaled = _bind("SDL_LowerBlitScaled", [POINTER(SDL_Surface), POINTER(SDL_Rect), POINTER(SDL_Surface), POINTER(SDL_Rect)], c_int)
 
 SDL_SetYUVConversionMode = _bind("SDL_SetYUVConversionMode", [SDL_YUV_CONVERSION_MODE], None, added='2.0.8')
 SDL_GetYUVConversionMode = _bind("SDL_GetYUVConversionMode", None, SDL_YUV_CONVERSION_MODE, added='2.0.8')
 SDL_GetYUVConversionModeForResolution = _bind("SDL_GetYUVConversionModeForResolution", [c_int, c_int], SDL_YUV_CONVERSION_MODE, added='2.0.8')
```

### Comparing `PySDL2-0.9.8/sdl2/syswm.py` & `PySDL2-0.9.9/sdl2/syswm.py`

 * *Files 2% similar despite different names*

```diff
@@ -11,15 +11,15 @@
 
     # Enums
     "SDL_SYSWM_TYPE",
     "SDL_SYSWM_UNKNOWN", "SDL_SYSWM_WINDOWS", "SDL_SYSWM_X11",
     "SDL_SYSWM_DIRECTFB", "SDL_SYSWM_COCOA", "SDL_SYSWM_UIKIT",
     "SDL_SYSWM_WAYLAND", "SDL_SYSWM_MIR", "SDL_SYSWM_WINRT",
     "SDL_SYSWM_ANDROID", "SDL_SYSWM_VIVANTE", "SDL_SYSWM_OS2",
-    "SDL_SYSWM_HAIKU",
+    "SDL_SYSWM_HAIKU", "SDL_SYSWM_KMSDRM",
 
     # Functions
     "SDL_GetWindowWMInfo"
 ]
 
 
 SDL_SYSWM_TYPE = c_int
@@ -33,14 +33,15 @@
 SDL_SYSWM_WAYLAND = 6
 SDL_SYSWM_MIR = 7
 SDL_SYSWM_WINRT = 8
 SDL_SYSWM_ANDROID = 9
 SDL_SYSWM_VIVANTE = 10
 SDL_SYSWM_OS2 = 11
 SDL_SYSWM_HAIKU = 12
+SDL_SYSWM_KMSDRM = 13
 
 
 # FIXME: Hack around the ctypes "_type_ 'v' not supported" bug - remove
 # once this has been fixed properly in Python 2.7+
 HWND = c_void_p
 HDC = c_void_p
 HINSTANCE = c_void_p
@@ -147,15 +148,17 @@
                 ("resolveFramebuffer", Uint32)]
 
 
 class _wl(Structure):
     """Window information for Wayland."""
     _fields_ = [("display", c_void_p),
                 ("surface", c_void_p),
-                ("shell_surface", c_void_p)]
+                ("shell_surface", c_void_p),
+                ("egl_window", c_void_p),
+                ("xdg_surface", c_void_p)]
 
 class _mir(Structure):
     """Window information for Mir."""
     _fields_ = [("connection", c_void_p),
                 ("surface", c_void_p)]
 
 
@@ -170,27 +173,34 @@
                 ("hwndFrame", HWND)]
 
 class _vivante(Structure):
     """Window information for Vivante."""
     _fields_ = [("display", c_void_p),
                 ("window", c_void_p)]
 
+class _kmsdrm(Structure):
+    """Window information for KMS/DRM."""
+    _fields_ = [("dev_index", c_int),
+                ("drm_fd", c_int),
+                ("gbm_dev", c_void_p)]
+
 class _info(Union):
     """The platform-specific information of a window."""
     _fields_ = [("win", _wininfo),
                 ("winrt", _winrtinfo),
                 ("x11", _x11info),
                 ("dfb", _dfbinfo),
                 ("cocoa", _cocoainfo),
                 ("uikit", _uikitinfo),
                 ("wl", _wl),
                 ("mir", _mir),
                 ("android", _android),
                 ("os2", _os2),
                 ("vivante", _vivante),
+                ("kmsdrm", _kmsdrm),
                 ("dummy", (Uint8 * 64))
                ]
 
 
 class SDL_SysWMinfo(Structure):
     """System-specific window manager information.
```

### Comparing `PySDL2-0.9.8/sdl2/test/audio_test.py` & `PySDL2-0.9.9/sdl2/test/audio_test.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 import os
 import sys
 import ctypes
+import sdl2
 from sdl2 import SDL_Init, SDL_Quit, SDL_InitSubSystem, SDL_QuitSubSystem, \
     SDL_INIT_AUDIO
 from sdl2.error import SDL_GetError, SDL_ClearError
 from sdl2 import audio
 import pytest
 
 
@@ -253,14 +254,48 @@
         print(backends)
         print("\nAvailable audio drivers and devices:")
         for driver in devices.keys():
             print(driver)
             print(" - input: {0}".format(str(devices[driver]['input'])))
             print(" - output: {0}".format(str(devices[driver]['output'])))
 
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_GetAudioDeviceSpec(self):
+        # Reset audio subsystem
+        SDL_Quit()
+        SDL_Init(0)
+        # Find an audio driver with at least one output
+        SDL_InitSubSystem(SDL_INIT_AUDIO)
+        driver = audio.SDL_GetCurrentAudioDriver()
+        if driver == None or audio.SDL_GetNumAudioDevices(False) == 0:
+            SDL_QuitSubSystem(SDL_INIT_AUDIO)
+            os.environ["SDL_AUDIODRIVER"] = b'dummy'
+            SDL_InitSubSystem(SDL_INIT_AUDIO)
+            driver = audio.SDL_GetCurrentAudioDriver()
+        drivername = driver.decode('utf-8')
+        # Get name and spec of first output device
+        outspec = audio.SDL_AudioSpec(0, 0, 0, 0)
+        outname = audio.SDL_GetAudioDeviceName(0, False).decode('utf-8')
+        ret = audio.SDL_GetAudioDeviceSpec(0, False, ctypes.byref(outspec))
+        SDL_QuitSubSystem(SDL_INIT_AUDIO)
+        assert ret == 0
+        # Validate frequency and channel count were set
+        hz = outspec.freq
+        fmt = audio.FORMAT_NAME_MAP[outspec.format] if outspec.format > 0 else 'unknown'
+        chans = outspec.channels
+        bufsize = outspec.samples if outspec.samples > 0 else 'unknown'
+        if driver != b"dummy":
+            assert hz > 0
+            assert chans > 0
+            # Print out device spec info
+            msg = "Audio device spec for {0} with '{1}' driver:"
+            msg2 = "{0} Hz, {1} channels, {2} format, {3} sample buffer size"
+            print(msg.format(outname, drivername))
+            print(msg2.format(hz, chans, fmt, bufsize))
+
     def test_SDL_OpenCloseAudioDevice(self):
         #TODO: Add tests for callback
         fmt = audio.AUDIO_F32 if sys.platform == "darwin" else audio.AUDIO_U16SYS
         reqspec = audio.SDL_AudioSpec(44100, fmt, 2, 1024)
         outnum = audio.SDL_GetNumAudioDevices(0)
         for x in range(outnum):
             spec = audio.SDL_AudioSpec(0, 0, 0, 0)
```

### Comparing `PySDL2-0.9.8/sdl2/test/clipboard_test.py` & `PySDL2-0.9.9/sdl2/test/clipboard_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/cpuinfo_test.py` & `PySDL2-0.9.9/sdl2/test/cpuinfo_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/endian_test.py` & `PySDL2-0.9.9/sdl2/test/endian_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/error_test.py` & `PySDL2-0.9.9/sdl2/test/error_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/events_test.py` & `PySDL2-0.9.9/sdl2/test/events_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/filesystem_test.py` & `PySDL2-0.9.9/sdl2/test/filesystem_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/gamecontroller_test.py` & `PySDL2-0.9.9/sdl2/test/gamecontroller_test.py`

 * *Files 2% similar despite different names*

```diff
@@ -202,14 +202,19 @@
 
     @pytest.mark.skip("not implemented")
     @pytest.mark.skipif(sdl2.dll.version < 2014, reason="not available")
     def test_SDL_GameControllerIsSensorEnabled(self):
         pass
 
     @pytest.mark.skip("not implemented")
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_GameControllerGetSensorDataRate(self):
+        pass
+
+    @pytest.mark.skip("not implemented")
     @pytest.mark.skipif(sdl2.dll.version < 2014, reason="not available")
     def test_SDL_GameControllerGetSensorData(self):
         pass
 
     @pytest.mark.skip("not implemented")
     def test_SDL_GameControllerClose(self):
         pass
@@ -294,7 +299,14 @@
     def test_SDL_GameControllerRumbleTriggers(self):
         pass
 
     @pytest.mark.skip("not implemented")
     @pytest.mark.skipif(sdl2.dll.version < 2014, reason="not available")
     def test_SDL_GameControllerHasSetLED(self):
         pass
+
+    @pytest.mark.skip("not implemented")
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_GameControllerSendEffect(self):
+        # Probably impossible to test since effect data would be specific
+        # to each controller type?
+        pass
```

### Comparing `PySDL2-0.9.8/sdl2/test/hints_test.py` & `PySDL2-0.9.9/sdl2/test/hints_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/joystick_test.py` & `PySDL2-0.9.9/sdl2/test/joystick_test.py`

 * *Files 4% similar despite different names*

```diff
@@ -336,14 +336,21 @@
             expected = -1 if has_led == SDL_FALSE else 0
             cols = [(255, 0, 0), (0, 255, 0), (0, 0, 255)]
             for r, g, b in cols:
                 ret = joystick.SDL_JoystickSetLED(stick, r, g, b)
                 assert ret == expected
             joystick.SDL_JoystickClose(stick)
 
+    @pytest.mark.skip("not implemented")
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_JoystickSendEffect(self):
+        # Probably impossible to test since effect data would be specific
+        # to each controller type?
+        pass
+
     @pytest.mark.skipif(sdl2.dll.version < 2014, reason="not available")
     def test_SDL_JoystickVirtual(self):
         jtype = joystick.SDL_JOYSTICK_TYPE_GAMECONTROLLER
         index = joystick.SDL_JoystickAttachVirtual(jtype, 1, 2, 1)
         assert index > 0
         assert joystick.SDL_JoystickIsVirtual(index) == SDL_TRUE
         stick = joystick.SDL_JoystickOpen(index)
```

### Comparing `PySDL2-0.9.8/sdl2/test/keyboard_test.py` & `PySDL2-0.9.9/sdl2/test/keyboard_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/log_test.py` & `PySDL2-0.9.9/sdl2/test/log_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/metal_test.py` & `PySDL2-0.9.9/sdl2/test/metal_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/mouse_test.py` & `PySDL2-0.9.9/sdl2/test/mouse_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/pixels_test.py` & `PySDL2-0.9.9/sdl2/test/pixels_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/platform_test.py` & `PySDL2-0.9.9/sdl2/test/platform_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/power_test.py` & `PySDL2-0.9.9/sdl2/test/power_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/rect_test.py` & `PySDL2-0.9.9/sdl2/test/rect_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/render_test.py` & `PySDL2-0.9.9/sdl2/test/render_test.py`

 * *Files 1% similar despite different names*

```diff
@@ -435,14 +435,19 @@
         pass
 
     @pytest.mark.skip("not implemented")
     def test_SDL_UpdateYUVTexture(self):
         pass
 
     @pytest.mark.skip("not implemented")
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_UpdateNVTexture(self):
+        pass
+
+    @pytest.mark.skip("not implemented")
     @pytest.mark.skipif(sdl2.dll.version < 2012, reason="not available")
     def test_SDL_LockTextureToSurface(self):
         pass
 
     @pytest.mark.skip("not implemented")
     def test_SDL_LockUnlockTexture(self):
         pass
```

### Comparing `PySDL2-0.9.8/sdl2/test/resources/font.bmp` & `PySDL2-0.9.9/sdl2/test/resources/font.bmp`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/resources.zip` & `PySDL2-0.9.9/sdl2/test/resources/resources.zip`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.bmp` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.bmp`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.cur` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.cur`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.gif` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.gif`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.ico` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.ico`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.lbm` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.lbm`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.pcx` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.pcx`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.pgm` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.pgm`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.ppm` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.ppm`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.svg` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.svg`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.tif` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.tif`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.xcf` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.xcf`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/surfacetest.xpm` & `PySDL2-0.9.9/sdl2/test/resources/surfacetest.xpm`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/tuffy.copy.ttf` & `PySDL2-0.9.9/sdl2/test/resources/tuffy.copy.ttf`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/resources/tuffy.ttf` & `PySDL2-0.9.9/sdl2/test/resources/tuffy.ttf`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/rwops_test.py` & `PySDL2-0.9.9/sdl2/test/rwops_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_algorithms_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_algorithms_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_array_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_array_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_color_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_color_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_draw_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_draw_test.py`

 * *Files 7% similar despite different names*

```diff
@@ -2,14 +2,19 @@
 import pytest
 from sdl2.surface import SDL_CreateRGBSurface
 from sdl2.rect import SDL_Rect
 from sdl2.ext.color import Color, COLOR
 from sdl2.ext.compat import ExperimentalWarning
 from sdl2 import ext as sdl2ext
 
+try:
+    import numpy
+    _HASNUMPY = True
+except:
+    _HASNUMPY = False
 
 class TestSDL2ExtDraw(object):
     __tags__ = ["sdl", "sdl2ext"]
 
     @classmethod
     def setup_class(cls):
         try:
@@ -17,14 +22,15 @@
         except sdl2ext.SDLError:
             raise pytest.skip('Video subsystem not supported')
 
     @classmethod
     def teardown_class(cls):
         sdl2ext.quit()
 
+    @pytest.mark.skipif(not _HASNUMPY, reason="pixels3d requires numpy module")
     def test_fill(self):
         # Initialize colour and surface/view
         WHITE = (255, 255, 255)
         BLACK = (0, 0, 0)
         sf = SDL_CreateRGBSurface(0, 10, 10, 32, 0, 0, 0, 0)
         with pytest.warns(ExperimentalWarning):
             view = sdl2ext.pixels3d(sf.contents, False)
@@ -59,14 +65,15 @@
         assert all(x == 255 for x in view[-1][-1][:3])
         assert all(x == 0 for x in view[-1][4][:3])
 
         # Test exception on bad input
         with pytest.raises(ValueError):
             sdl2ext.fill(sf.contents, WHITE, (1, 2, 3))
 
+    @pytest.mark.skipif(not _HASNUMPY, reason="pixels3d requires numpy module")
     def test_line(self):
         # Initialize colour and surface/view
         WHITE = (255, 255, 255)
         BLACK = (0, 0, 0)
         sf = SDL_CreateRGBSurface(0, 10, 10, 32, 0, 0, 0, 0)
         with pytest.warns(ExperimentalWarning):
             view = sdl2ext.pixels3d(sf.contents, False)
```

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_ebs_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_ebs_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_events_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_events_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_font_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_font_test.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,9 @@
 # -*- coding: utf-8 -*-
 import pytest
-import numpy as np
 from sdl2 import ext as sdl2ext
 from sdl2.ext.compat import byteify, ExperimentalWarning
 from sdl2.ext.pixelaccess import pixels2d
 from sdl2 import surface, sdlttf
 
 
 RESOURCES = sdl2ext.Resources(__file__, "resources")
@@ -42,15 +41,15 @@
         # Try SoftwareSprite surface
         font = sdl2ext.BitmapFont(sprite, (32, 32), FONTMAP)
         assert font.size == (32, 32)
 
         # Try SDL_Surface surface
         font = sdl2ext.BitmapFont(sf.contents, (32, 32), FONTMAP)
         assert font.size == (32, 32)
-        
+
         # Try SDL_Surface pointer surface
         font = sdl2ext.BitmapFont(sf, (32, 32), FONTMAP)
         assert font.size == (32, 32)
 
         # Try invalid surface type
         with pytest.raises(TypeError):
             font = sdl2ext.BitmapFont("hello", (32, 32), FONTMAP)
@@ -68,14 +67,15 @@
         assert text.size[0] == 32 * len(msg)
 
         # Test exception for missing glyph
         with pytest.raises(ValueError):
             font.render("this_should_fail")
 
     def test_BitmapFont_render_on(self):
+        np = pytest.importorskip("numpy", reason="numpy module is not available")
         # Initialize font, surface, and BitmapFont for tests
         fontpath = byteify(RESOURCES.get_path("font.bmp"), "utf-8")
         sf = surface.SDL_LoadBMP(fontpath)
         font = sdl2ext.BitmapFont(sf.contents, (32, 32), FONTMAP)
 
         # Try rendering some text
         target = surface.SDL_CreateRGBSurface(0, 32*5, 32, 32, 0, 0, 0, 0)
```

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_gui_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_gui_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_image_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_image_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_particles_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_particles_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_pixelaccess_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_pixelaccess_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_resources_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_resources_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_sprite_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_sprite_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl2ext_window_test.py` & `PySDL2-0.9.9/sdl2/test/sdl2ext_window_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdl_test.py` & `PySDL2-0.9.9/sdl2/test/sdl_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdlgfx_test.py` & `PySDL2-0.9.9/sdl2/test/sdlgfx_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdlimage_test.py` & `PySDL2-0.9.9/sdl2/test/sdlimage_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdlmixer_test.py` & `PySDL2-0.9.9/sdl2/test/sdlmixer_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sdlttf_test.py` & `PySDL2-0.9.9/sdl2/test/sdlttf_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/sensor_test.py` & `PySDL2-0.9.9/sdl2/test/sensor_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/shape_test.py` & `PySDL2-0.9.9/sdl2/test/shape_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/surface_test.py` & `PySDL2-0.9.9/sdl2/test/surface_test.py`

 * *Files 0% similar despite different names*

```diff
@@ -653,14 +653,19 @@
     def test_SDL_UpperBlitScaled(self):
         pass
 
     @pytest.mark.skip("not implemented")
     def test_SDL_SoftStretch(self):
         pass
 
+    @pytest.mark.skip("not implemented")
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_SoftStretchLinear(self):
+        pass
+
     def test_SDL_SetSurfacePalette(self):
         invpalette = pixels.SDL_AllocPalette(10)
         palette = pixels.SDL_AllocPalette(1 << 16)
         sf = surface.SDL_CreateRGBSurface(0, 10, 10, 16, 0, 0, 0, 0)
 
         assert not sf.contents.format.contents.palette
         surface.SDL_SetSurfacePalette(sf, palette)
```

### Comparing `PySDL2-0.9.8/sdl2/test/syswm_test.py` & `PySDL2-0.9.9/sdl2/test/syswm_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/timer_test.py` & `PySDL2-0.9.9/sdl2/test/timer_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/touch_test.py` & `PySDL2-0.9.9/sdl2/test/touch_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/test/version_test.py` & `PySDL2-0.9.9/sdl2/test/version_test.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 import sys
 import ctypes
 import pytest
-from sdl2 import version, __version__, version_info
+from sdl2 import version, dll, __version__, version_info
 
 
 class TestSDLVersion(object):
     __tags__ = ["sdl"]
 
     def test_SDL_version(self):
         v = version.SDL_version(0, 0, 0)
@@ -30,15 +30,18 @@
     def test_SDL_VERSION_ATLEAST(self):
         assert version.SDL_VERSION_ATLEAST(1, 2, 3)
         assert version.SDL_VERSION_ATLEAST(2, 0, 0)
         assert version.SDL_VERSION_ATLEAST(2, 0, 1)
         assert not version.SDL_VERSION_ATLEAST(2, 0, 100)
 
     def test_SDL_GetRevision(self):
-        assert version.SDL_GetRevision()[0:3] == b"hg-"
+        if dll.version >= 2016:
+            assert version.SDL_GetRevision()[0:4] == b"http"
+        else:
+            assert version.SDL_GetRevision()[0:3] == b"hg-"
 
     def test_SDL_GetRevisionNumber(self):
-        if sys.platform in ("win32",):
+        if sys.platform in ("win32",) or dll.version >= 2016:
             # HG tip on Win32 does not set any revision number
             assert version.SDL_GetRevisionNumber() >= 0
         else:
             assert version.SDL_GetRevisionNumber() >= 7000
```

### Comparing `PySDL2-0.9.8/sdl2/test/video_test.py` & `PySDL2-0.9.9/sdl2/test/video_test.py`

 * *Files 2% similar despite different names*

```diff
@@ -625,26 +625,57 @@
             #                  window, rectlist)
             sf = surface.SDL_Surface()
             video.SDL_GetWindowSurface(window, byref(sf))
             ret = video.SDL_UpdateWindowSurfaceRects(window, rptr, 4)
             assert ret == 0
             video.SDL_DestroyWindow(window)
 
-    @pytest.mark.skip("SDL_GetWindowGrab fails right now")
+    @pytest.mark.skip("Test doesn't work, may need to be interactive")
     def test_SDL_GetSetWindowGrab(self):
         flags = (video.SDL_WINDOW_BORDERLESS,
                  video.SDL_WINDOW_BORDERLESS | video.SDL_WINDOW_HIDDEN,
                  video.SDL_WINDOW_RESIZABLE | video.SDL_WINDOW_MINIMIZED)
         for flag in flags:
             window = video.SDL_CreateWindow(b"Test", 200, 200, 200, 200, flag)
             assert video.SDL_GetWindowGrab(window) == SDL_FALSE
             video.SDL_SetWindowGrab(window, SDL_TRUE)
             assert video.SDL_GetWindowGrab(window) == SDL_TRUE
             video.SDL_SetWindowGrab(window, SDL_FALSE)
             assert video.SDL_GetWindowGrab(window) == SDL_FALSE
+            video.SDL_DestroyWindow(window)
+
+    @pytest.mark.skip("Test doesn't work, may need to be interactive")
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_GetSetWindowKeyboardGrab(self):
+        flags = (video.SDL_WINDOW_BORDERLESS,
+                 video.SDL_WINDOW_BORDERLESS | video.SDL_WINDOW_HIDDEN,
+                 video.SDL_WINDOW_RESIZABLE | video.SDL_WINDOW_MINIMIZED)
+        for flag in flags:
+            window = video.SDL_CreateWindow(b"Test", 200, 200, 200, 200, flag)
+            assert video.SDL_GetWindowKeyboardGrab(window) == SDL_FALSE
+            video.SDL_SetWindowKeyboardGrab(window, SDL_TRUE)
+            assert video.SDL_GetWindowKeyboardGrab(window) == SDL_TRUE
+            video.SDL_SetWindowKeyboardGrab(window, SDL_FALSE)
+            assert video.SDL_GetWindowKeyboardGrab(window) == SDL_FALSE
+            video.SDL_DestroyWindow(window)
+
+    @pytest.mark.skip("Test doesn't work, may need to be interactive")
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_GetSetWindowMouseGrab(self):
+        flags = (video.SDL_WINDOW_BORDERLESS,
+                 video.SDL_WINDOW_BORDERLESS | video.SDL_WINDOW_HIDDEN,
+                 video.SDL_WINDOW_RESIZABLE | video.SDL_WINDOW_MINIMIZED)
+        for flag in flags:
+            window = video.SDL_CreateWindow(b"Test", 200, 200, 200, 200, flag)
+            assert video.SDL_GetWindowMouseGrab(window) == SDL_FALSE
+            video.SDL_SetWindowMouseGrab(window, SDL_TRUE)
+            assert video.SDL_GetWindowMouseGrab(window) == SDL_TRUE
+            video.SDL_SetWindowMouseGrab(window, SDL_FALSE)
+            assert video.SDL_GetWindowMouseGrab(window) == SDL_FALSE
+            video.SDL_DestroyWindow(window)
 
     @pytest.mark.skip("not implemented")
     def test_SDL_GetGrabbedWindow(self):
         pass
 
     @pytest.mark.skipif(os.environ.get("APPVEYOR") == "True",
         reason="Appveyor cannot set the brightness")
@@ -675,15 +706,21 @@
         pass
 
     @pytest.mark.skip("not implemented")
     def test_SDL_GetWindowGammaRamp(self):
         pass
 
     @pytest.mark.skip("not implemented")
-    def test_SDL_SetWindowHitTest(self):
+    def test_SDL_GetWindowGammaRamp(self):
+        pass
+
+    @pytest.mark.skip("not implemented")
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_FlashWindow(self):
+        # Would need to be an interactive test
         pass
 
     def test_SDL_GL_LoadUnloadLibrary(self):
         if video.SDL_GetCurrentVideoDriver() == b"dummy":
             pytest.skip("dummy video driver does not support GL loading")
         # Try the default library
         assert video.SDL_GL_LoadLibrary(None) == 0, SDL_GetError()
@@ -923,14 +960,31 @@
         flags = video.SDL_GetWindowFlags(window)
         assert flags & video.SDL_WINDOW_RESIZABLE != video.SDL_WINDOW_RESIZABLE
         video.SDL_SetWindowResizable(window, SDL_TRUE)
         flags = video.SDL_GetWindowFlags(window)
         assert flags & video.SDL_WINDOW_RESIZABLE == video.SDL_WINDOW_RESIZABLE
         video.SDL_DestroyWindow(window)
 
+    @pytest.mark.skip("Test doesn't work, may need to be interactive")
+    @pytest.mark.skipif(sdl2.dll.version < 2016, reason="not available")
+    def test_SDL_SetWindowAlwaysOnTop(self):
+        ON_TOP_FLAG = video.SDL_WINDOW_ALWAYS_ON_TOP
+        window = video.SDL_CreateWindow(b"Always On Top", 10, 10, 10, 10,
+                                        video.SDL_WINDOW_ALWAYS_ON_TOP)
+        video.SDL_ShowWindow(window)
+        flags = video.SDL_GetWindowFlags(window)
+        assert flags & ON_TOP_FLAG == ON_TOP_FLAG
+        video.SDL_SetWindowAlwaysOnTop(window, SDL_FALSE)
+        flags = video.SDL_GetWindowFlags(window)
+        assert flags & ON_TOP_FLAG != ON_TOP_FLAG
+        video.SDL_SetWindowAlwaysOnTop(window, SDL_TRUE)
+        flags = video.SDL_GetWindowFlags(window)
+        assert flags & ON_TOP_FLAG == ON_TOP_FLAG
+        video.SDL_DestroyWindow(window)
+
     def test_SDL_GetSetWindowOpacity(self):
         window = video.SDL_CreateWindow(b"Opacity", 10, 10, 10, 10, 0)
         opacity = c_float()
         ret = video.SDL_GetWindowOpacity(window, byref(opacity))
         assert ret == 0
         assert opacity.value == 1.0
         if video.SDL_GetCurrentVideoDriver() != b"dummy":
@@ -954,14 +1008,15 @@
             assert ret == 0
             assert not rect.SDL_RectEmpty(bounds)
 
     def test_SDL_GetWindowsBordersSize(self):
         if video.SDL_GetCurrentVideoDriver() == b"dummy":
             pytest.skip("dummy video driver does not support the window border size")
         window = video.SDL_CreateWindow(b"Borders", 10, 10, 10, 10, 0)
+        video.SDL_ShowWindow(window)
         l, r, t, b = c_int(), c_int(), c_int(), c_int()
         ret = video.SDL_GetWindowBordersSize(window, byref(t), byref(l),
                                              byref(b), byref(r))
         if sys.platform in ("cygwin", "darwin"):
             assert ret == -1
             assert t.value == 0
             assert l.value == 0
@@ -972,14 +1027,15 @@
             assert t.value != 0
             assert l.value != 0
             assert b.value != 0
             assert r.value != 0
         video.SDL_DestroyWindow(window)
         window = video.SDL_CreateWindow(b"No Borders", 10, 10, 10, 10,
                                         video.SDL_WINDOW_BORDERLESS)
+        video.SDL_ShowWindow(window)
         ret = video.SDL_GetWindowBordersSize(window, byref(t), byref(l),
                                              byref(b), byref(r))
         if sys.platform not in ("cygwin", "darwin"):
             assert ret == 0
             assert t.value == 0
             assert l.value == 0
             assert b.value == 0
```

### Comparing `PySDL2-0.9.8/sdl2/test/vulkan_test.py` & `PySDL2-0.9.9/sdl2/test/vulkan_test.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/timer.py` & `PySDL2-0.9.9/sdl2/timer.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/touch.py` & `PySDL2-0.9.9/sdl2/touch.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/sdl2/version.py` & `PySDL2-0.9.9/sdl2/version.py`

 * *Files 19% similar despite different names*

```diff
@@ -22,20 +22,20 @@
     _fields_ = [("major", Uint8),
                 ("minor", Uint8),
                 ("patch", Uint8),
                 ]
 
 SDL_MAJOR_VERSION = 2
 SDL_MINOR_VERSION = 0
-SDL_PATCHLEVEL = 14
+SDL_PATCHLEVEL = 16
 
 def SDL_VERSION(x):
     x.major = SDL_MAJOR_VERSION
     x.minor = SDL_MINOR_VERSION
     x.patch = SDL_PATCHLEVEL
 
 SDL_VERSIONNUM = lambda x, y, z: (x * 1000 + y * 100 + z)
 SDL_COMPILEDVERSION = SDL_VERSIONNUM(SDL_MAJOR_VERSION, SDL_MINOR_VERSION, SDL_PATCHLEVEL)
 SDL_VERSION_ATLEAST = lambda x, y, z: (SDL_COMPILEDVERSION >= SDL_VERSIONNUM(x, y, z))
 SDL_GetVersion = _bind("SDL_GetVersion", [POINTER(SDL_version)])
 SDL_GetRevision = _bind("SDL_GetRevision", None, c_char_p)
-SDL_GetRevisionNumber = _bind("SDL_GetRevisionNumber", None, c_int)
+SDL_GetRevisionNumber = _bind("SDL_GetRevisionNumber", None, c_int) # Deprecated as of 2.0.16, add warning?
```

### Comparing `PySDL2-0.9.8/sdl2/video.py` & `PySDL2-0.9.9/sdl2/video.py`

 * *Files 3% similar despite different names*

```diff
@@ -10,21 +10,23 @@
     "SDL_DisplayMode", "SDL_Window", "SDL_GLContext",
 
     # Enums
     "SDL_WindowFlags",
     "SDL_WINDOW_FULLSCREEN", "SDL_WINDOW_OPENGL", "SDL_WINDOW_SHOWN",
     "SDL_WINDOW_HIDDEN", "SDL_WINDOW_BORDERLESS",
     "SDL_WINDOW_RESIZABLE", "SDL_WINDOW_MINIMIZED",
-    "SDL_WINDOW_MAXIMIZED", "SDL_WINDOW_INPUT_GRABBED",
+    "SDL_WINDOW_MAXIMIZED", "SDL_WINDOW_MOUSE_GRABBED",
     "SDL_WINDOW_INPUT_FOCUS", "SDL_WINDOW_MOUSE_FOCUS",
     "SDL_WINDOW_FULLSCREEN_DESKTOP", "SDL_WINDOW_FOREIGN",
     "SDL_WINDOW_ALLOW_HIGHDPI", "SDL_WINDOW_MOUSE_CAPTURE",
     "SDL_WINDOW_ALWAYS_ON_TOP", "SDL_WINDOW_SKIP_TASKBAR",
-    "SDL_WINDOW_UTILITY", "SDL_WINDOW_TOOLTIP", "SDL_WINDOW_POPUP_MENU",
+    "SDL_WINDOW_UTILITY", "SDL_WINDOW_TOOLTIP",
+    "SDL_WINDOW_POPUP_MENU", "SDL_WINDOW_KEYBOARD_GRABBED",
     "SDL_WINDOW_VULKAN", "SDL_WINDOW_METAL",
+    "SDL_WINDOW_INPUT_FOCUS",
 
     "SDL_WindowEventID",
     "SDL_WINDOWEVENT_NONE",
     "SDL_WINDOWEVENT_SHOWN", "SDL_WINDOWEVENT_HIDDEN",
     "SDL_WINDOWEVENT_EXPOSED", "SDL_WINDOWEVENT_MOVED",
     "SDL_WINDOWEVENT_RESIZED", "SDL_WINDOWEVENT_SIZE_CHANGED",
     "SDL_WINDOWEVENT_MINIMIZED", "SDL_WINDOWEVENT_MAXIMIZED",
@@ -38,14 +40,17 @@
     "SDL_DISPLAYEVENT_CONNECTED", "SDL_DISPLAYEVENT_DISCONNECTED",
     
     "SDL_DisplayOrientation",
     "SDL_ORIENTATION_UNKNOWN", "SDL_ORIENTATION_LANDSCAPE",
     "SDL_ORIENTATION_LANDSCAPE_FLIPPED", "SDL_ORIENTATION_PORTRAIT",
     "SDL_ORIENTATION_PORTRAIT_FLIPPED",
 
+    "SDL_FlashOperation",
+    "SDL_FLASH_CANCEL", "SDL_FLASH_BRIEFLY", "SDL_FLASH_UNTIL_FOCUSED",
+
     "SDL_GLattr",
     "SDL_GL_RED_SIZE",
     "SDL_GL_GREEN_SIZE", "SDL_GL_BLUE_SIZE", "SDL_GL_ALPHA_SIZE",
     "SDL_GL_BUFFER_SIZE", "SDL_GL_DOUBLEBUFFER", "SDL_GL_DEPTH_SIZE",
     "SDL_GL_STENCIL_SIZE", "SDL_GL_ACCUM_RED_SIZE",
     "SDL_GL_ACCUM_GREEN_SIZE", "SDL_GL_ACCUM_BLUE_SIZE",
     "SDL_GL_ACCUM_ALPHA_SIZE", "SDL_GL_STEREO",
@@ -108,18 +113,20 @@
     "SDL_SetWindowMinimumSize", "SDL_GetWindowMinimumSize",
     "SDL_SetWindowMaximumSize", "SDL_GetWindowMaximumSize",
     "SDL_SetWindowBordered", "SDL_ShowWindow", "SDL_HideWindow",
     "SDL_RaiseWindow", "SDL_MaximizeWindow", "SDL_MinimizeWindow",
     "SDL_RestoreWindow", "SDL_SetWindowFullscreen",
     "SDL_GetWindowSurface", "SDL_UpdateWindowSurface",
     "SDL_UpdateWindowSurfaceRects", "SDL_SetWindowGrab",
-    "SDL_GetWindowGrab", "SDL_GetGrabbedWindow",
-    "SDL_SetWindowBrightness",
-    "SDL_GetWindowBrightness", "SDL_SetWindowGammaRamp",
-    "SDL_GetWindowGammaRamp", "SDL_DestroyWindow",
+    "SDL_SetWindowKeyboardGrab", "SDL_SetWindowMouseGrab",
+    "SDL_GetWindowGrab", "SDL_GetWindowKeyboardGrab",
+    "SDL_GetWindowMouseGrab", "SDL_GetGrabbedWindow",
+    "SDL_SetWindowBrightness", "SDL_GetWindowBrightness",
+    "SDL_SetWindowGammaRamp", "SDL_GetWindowGammaRamp", 
+    "SDL_FlashWindow", "SDL_DestroyWindow",
     "SDL_DisableScreenSaver", "SDL_IsScreenSaverEnabled",
     "SDL_EnableScreenSaver",
     "SDL_SetWindowHitTest", "SDL_GL_LoadLibrary",
     "SDL_GL_GetProcAddress", "SDL_GL_UnloadLibrary",
     "SDL_GL_ExtensionSupported", "SDL_GL_SetAttribute",
     "SDL_GL_GetAttribute", "SDL_GL_CreateContext",
     "SDL_GL_MakeCurrent", "SDL_GL_SetSwapInterval",
@@ -127,14 +134,15 @@
     "SDL_GL_GetDrawableSize", "SDL_GL_GetCurrentWindow",
     "SDL_GL_GetCurrentContext", "SDL_GL_DeleteContext",
     "SDL_GL_ResetAttributes",
     "SDL_GetDisplayDPI", "SDL_GetDisplayUsableBounds",
     "SDL_GetWindowBordersSize", "SDL_GetWindowOpacity",
     "SDL_SetWindowOpacity", "SDL_SetWindowInputFocus",
     "SDL_SetWindowModalFor", "SDL_SetWindowResizable",
+    "SDL_SetWindowAlwaysOnTop",
 
     # Callback Functions
     "SDL_HitTest"
 ]
 
 
 class SDL_DisplayMode(Structure):
@@ -175,27 +183,28 @@
 SDL_WINDOW_OPENGL = 0x00000002
 SDL_WINDOW_SHOWN = 0x00000004
 SDL_WINDOW_HIDDEN = 0x00000008
 SDL_WINDOW_BORDERLESS = 0x00000010
 SDL_WINDOW_RESIZABLE = 0x00000020
 SDL_WINDOW_MINIMIZED = 0x00000040
 SDL_WINDOW_MAXIMIZED = 0x00000080
-SDL_WINDOW_INPUT_GRABBED = 0x00000100
+SDL_WINDOW_MOUSE_GRABBED = 0x00000100
+SDL_WINDOW_INPUT_GRABBED = SDL_WINDOW_MOUSE_GRABBED  # for < 2.0.16
 SDL_WINDOW_INPUT_FOCUS = 0x00000200
 SDL_WINDOW_MOUSE_FOCUS = 0x00000400
 SDL_WINDOW_FULLSCREEN_DESKTOP = (SDL_WINDOW_FULLSCREEN | 0x00001000)
 SDL_WINDOW_FOREIGN = 0x00000800
 SDL_WINDOW_ALLOW_HIGHDPI = 0x00002000
 SDL_WINDOW_MOUSE_CAPTURE = 0x00004000
 SDL_WINDOW_ALWAYS_ON_TOP = 0x00008000
-
 SDL_WINDOW_SKIP_TASKBAR  = 0x00010000
 SDL_WINDOW_UTILITY = 0x00020000
 SDL_WINDOW_TOOLTIP = 0x00040000
 SDL_WINDOW_POPUP_MENU = 0x00080000
+SDL_WINDOW_KEYBOARD_GRABBED = 0x00100000
 SDL_WINDOW_VULKAN = 0x10000000
 SDL_WINDOW_METAL = 0x20000000
 
 SDL_WINDOWPOS_UNDEFINED_MASK = 0x1FFF0000
 SDL_WINDOWPOS_UNDEFINED_DISPLAY = lambda x: (SDL_WINDOWPOS_UNDEFINED_MASK | x)
 SDL_WINDOWPOS_UNDEFINED = SDL_WINDOWPOS_UNDEFINED_DISPLAY(0)
 SDL_WINDOWPOS_ISUNDEFINED = lambda x: ((x & 0xFFFF0000) == SDL_WINDOWPOS_UNDEFINED_MASK)
@@ -240,14 +249,21 @@
 SDL_ORIENTATION_UNKNOWN = 0
 SDL_ORIENTATION_LANDSCAPE = 1
 SDL_ORIENTATION_LANDSCAPE_FLIPPED = 2
 SDL_ORIENTATION_PORTRAIT = 3
 SDL_ORIENTATION_PORTRAIT_FLIPPED = 4
 
 
+SDL_FlashOperation = c_int
+
+SDL_FLASH_CANCEL = 0
+SDL_FLASH_BRIEFLY = 1
+SDL_FLASH_UNTIL_FOCUSED = 2
+
+
 SDL_GLContext = c_void_p
 
 
 SDL_GLattr = c_int
 
 SDL_GL_RED_SIZE = 0
 SDL_GL_GREEN_SIZE = 1
@@ -365,33 +381,39 @@
 SDL_MinimizeWindow = _bind("SDL_MinimizeWindow", [POINTER(SDL_Window)])
 SDL_RestoreWindow = _bind("SDL_RestoreWindow", [POINTER(SDL_Window)])
 SDL_SetWindowFullscreen = _bind("SDL_SetWindowFullscreen", [POINTER(SDL_Window), Uint32], c_int)
 SDL_GetWindowSurface = _bind("SDL_GetWindowSurface", [POINTER(SDL_Window)], POINTER(SDL_Surface))
 SDL_UpdateWindowSurface = _bind("SDL_UpdateWindowSurface", [POINTER(SDL_Window)], c_int)
 SDL_UpdateWindowSurfaceRects = _bind("SDL_UpdateWindowSurfaceRects", [POINTER(SDL_Window), POINTER(SDL_Rect), c_int], c_int)
 SDL_SetWindowGrab = _bind("SDL_SetWindowGrab", [POINTER(SDL_Window), SDL_bool])
+SDL_SetWindowKeyboardGrab = _bind("SDL_SetWindowKeyboardGrab", [POINTER(SDL_Window), SDL_bool], added='2.0.16')
+SDL_SetWindowMouseGrab = _bind("SDL_SetWindowMouseGrab", [POINTER(SDL_Window), SDL_bool], added='2.0.16')
 SDL_GetWindowGrab = _bind("SDL_GetWindowGrab", [POINTER(SDL_Window)], SDL_bool)
+SDL_GetWindowKeyboardGrab = _bind("SDL_GetWindowKeyboardGrab", [POINTER(SDL_Window)], SDL_bool, added='2.0.16')
+SDL_GetWindowMouseGrab = _bind("SDL_GetWindowMouseGrab", [POINTER(SDL_Window)], SDL_bool, added='2.0.16')
 SDL_GetGrabbedWindow = _bind("SDL_GetGrabbedWindow", None, POINTER(SDL_Window))
 SDL_SetWindowBrightness = _bind("SDL_SetWindowBrightness", [POINTER(SDL_Window), c_float], c_int)
 SDL_GetWindowBrightness = _bind("SDL_GetWindowBrightness", [POINTER(SDL_Window)], c_float)
 SDL_SetWindowGammaRamp = _bind("SDL_SetWindowGammaRamp", [POINTER(SDL_Window), POINTER(Uint16), POINTER(Uint16), POINTER(Uint16)], c_int)
 SDL_GetWindowGammaRamp = _bind("SDL_GetWindowGammaRamp", [POINTER(SDL_Window), POINTER(Uint16), POINTER(Uint16), POINTER(Uint16)], c_int)
+SDL_FlashWindow = _bind("SDL_FlashWindow", [POINTER(SDL_Window), SDL_FlashOperation], c_int, added='2.0.16')
 SDL_DestroyWindow = _bind("SDL_DestroyWindow", [POINTER(SDL_Window)])
 SDL_IsScreenSaverEnabled = _bind("SDL_IsScreenSaverEnabled", None, SDL_bool)
 SDL_EnableScreenSaver = _bind("SDL_EnableScreenSaver")
 SDL_DisableScreenSaver = _bind("SDL_DisableScreenSaver")
 SDL_SetWindowHitTest = _bind("SDL_SetWindowHitTest", [POINTER(SDL_Window), SDL_HitTest, c_void_p], c_int)
 SDL_GetDisplayDPI = _bind("SDL_GetDisplayDPI", [c_int, POINTER(c_float), POINTER(c_float), POINTER(c_float)], c_int)
 SDL_GetDisplayUsableBounds = _bind("SDL_GetDisplayUsableBounds", [c_int, POINTER(SDL_Rect)], c_int)
 SDL_GetWindowBordersSize = _bind("SDL_GetWindowBordersSize", [POINTER(SDL_Window), POINTER(c_int), POINTER(c_int), POINTER(c_int), POINTER(c_int)], c_int)
 SDL_GetWindowOpacity = _bind("SDL_GetWindowOpacity", [POINTER(SDL_Window), POINTER(c_float)], c_int)
 SDL_SetWindowOpacity = _bind("SDL_SetWindowOpacity", [POINTER(SDL_Window), c_float], c_int)
 SDL_SetWindowInputFocus = _bind("SDL_SetWindowInputFocus", [POINTER(SDL_Window)], c_int)
 SDL_SetWindowModalFor = _bind("SDL_SetWindowModalFor", [POINTER(SDL_Window), POINTER(SDL_Window)], c_int)
 SDL_SetWindowResizable = _bind("SDL_SetWindowResizable", [POINTER(SDL_Window), SDL_bool])
+SDL_SetWindowAlwaysOnTop = _bind("SDL_SetWindowAlwaysOnTop", [POINTER(SDL_Window), SDL_bool], added='2.0.16')
 
 SDL_GL_LoadLibrary = _bind("SDL_GL_LoadLibrary", [c_char_p], c_int)
 SDL_GL_GetProcAddress = _bind("SDL_GL_GetProcAddress", [c_char_p], c_void_p)
 SDL_GL_UnloadLibrary = _bind("SDL_GL_UnloadLibrary")
 SDL_GL_ExtensionSupported = _bind("SDL_GL_ExtensionSupported", [c_char_p], SDL_bool)
 SDL_GL_SetAttribute = _bind("SDL_GL_SetAttribute", [SDL_GLattr, c_int], c_int)
 SDL_GL_GetAttribute = _bind("SDL_GL_GetAttribute", [SDL_GLattr, POINTER(c_int)], c_int)
```

### Comparing `PySDL2-0.9.8/sdl2/vulkan.py` & `PySDL2-0.9.9/sdl2/vulkan.py`

 * *Files identical despite different names*

### Comparing `PySDL2-0.9.8/setup.py` & `PySDL2-0.9.9/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 #!/usr/bin/env python
 import os
 import sys
 import re
 # from distutils.core import setup
 from setuptools import setup
 
-VERSION = "0.9.8"
+VERSION = "0.9.9"
 
 if __name__ == "__main__":
 
     if "--format=msi" in sys.argv or "bdist_msi" in sys.argv:
         # hack the version name to a format msi doesn't have trouble with
         VERSION = VERSION.replace("-alpha", "a")
         VERSION = VERSION.replace("-beta", "b")
```

### Comparing `PySDL2-0.9.8/util/valgrind.sh` & `PySDL2-0.9.9/util/valgrind.sh`

 * *Files identical despite different names*


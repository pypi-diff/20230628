# Comparing `tmp/hciplot-0.2.3.tar.gz` & `tmp/hciplot-0.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "hciplot-0.2.3.tar", last modified: Thu Feb  9 14:27:47 2023, max compression
+gzip compressed data, was "hciplot-0.2.4.tar", last modified: Wed Jun 28 10:10:48 2023, max compression
```

## Comparing `hciplot-0.2.3.tar` & `hciplot-0.2.4.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 valentin   (501) staff       (20)        0 2023-02-09 14:27:47.130276 hciplot-0.2.3/
--rw-r--r--   0 valentin   (501) staff       (20)     6148 2022-02-15 18:32:34.000000 hciplot-0.2.3/.DS_Store
--rw-r--r--   0 valentin   (501) staff       (20)     1221 2021-12-01 15:26:15.000000 hciplot-0.2.3/.gitignore
--rw-r--r--   0 valentin   (501) staff       (20)     1086 2021-12-01 15:26:15.000000 hciplot-0.2.3/LICENSE
--rw-r--r--   0 valentin   (501) staff       (20)     2743 2023-02-09 14:27:47.130028 hciplot-0.2.3/PKG-INFO
--rw-r--r--   0 valentin   (501) staff       (20)     1841 2021-12-01 15:26:15.000000 hciplot-0.2.3/README.md
-drwxr-xr-x   0 valentin   (501) staff       (20)        0 2023-02-09 14:27:47.128218 hciplot-0.2.3/hciplot/
--rw-r--r--   0 valentin   (501) staff       (20)       68 2023-02-09 14:26:15.000000 hciplot-0.2.3/hciplot/__init__.py
--rw-r--r--   0 valentin   (501) staff       (20)    44698 2023-02-08 23:29:34.000000 hciplot-0.2.3/hciplot/hciplot.py
-drwxr-xr-x   0 valentin   (501) staff       (20)        0 2023-02-09 14:27:47.129730 hciplot-0.2.3/hciplot.egg-info/
--rw-r--r--   0 valentin   (501) staff       (20)     2743 2023-02-09 14:27:46.000000 hciplot-0.2.3/hciplot.egg-info/PKG-INFO
--rw-r--r--   0 valentin   (501) staff       (20)      257 2023-02-09 14:27:46.000000 hciplot-0.2.3/hciplot.egg-info/SOURCES.txt
--rw-r--r--   0 valentin   (501) staff       (20)        1 2023-02-09 14:27:46.000000 hciplot-0.2.3/hciplot.egg-info/dependency_links.txt
--rw-r--r--   0 valentin   (501) staff       (20)       67 2023-02-09 14:27:46.000000 hciplot-0.2.3/hciplot.egg-info/requires.txt
--rw-r--r--   0 valentin   (501) staff       (20)        8 2023-02-09 14:27:46.000000 hciplot-0.2.3/hciplot.egg-info/top_level.txt
--rw-r--r--   0 valentin   (501) staff       (20)       66 2022-03-25 09:25:14.000000 hciplot-0.2.3/requirements.txt
--rw-r--r--   0 valentin   (501) staff       (20)       38 2023-02-09 14:27:47.130347 hciplot-0.2.3/setup.cfg
--rw-r--r--   0 valentin   (501) staff       (20)     2213 2022-05-16 15:51:24.000000 hciplot-0.2.3/setup.py
+drwxr-xr-x   0 valentin   (501) staff       (20)        0 2023-06-28 10:10:48.681573 hciplot-0.2.4/
+-rw-r--r--   0 valentin   (501) staff       (20)     6148 2022-02-15 18:32:34.000000 hciplot-0.2.4/.DS_Store
+-rw-r--r--   0 valentin   (501) staff       (20)     1221 2021-12-01 15:26:15.000000 hciplot-0.2.4/.gitignore
+-rw-r--r--   0 valentin   (501) staff       (20)     1086 2021-12-01 15:26:15.000000 hciplot-0.2.4/LICENSE
+-rw-r--r--   0 valentin   (501) staff       (20)     2743 2023-06-28 10:10:48.681391 hciplot-0.2.4/PKG-INFO
+-rw-r--r--   0 valentin   (501) staff       (20)     1841 2021-12-01 15:26:15.000000 hciplot-0.2.4/README.md
+drwxr-xr-x   0 valentin   (501) staff       (20)        0 2023-06-28 10:10:48.674675 hciplot-0.2.4/hciplot/
+-rw-r--r--   0 valentin   (501) staff       (20)       68 2023-06-28 10:10:22.000000 hciplot-0.2.4/hciplot/__init__.py
+-rw-r--r--   0 valentin   (501) staff       (20)    50776 2023-05-23 15:18:50.000000 hciplot-0.2.4/hciplot/hciplot.py
+drwxr-xr-x   0 valentin   (501) staff       (20)        0 2023-06-28 10:10:48.681178 hciplot-0.2.4/hciplot.egg-info/
+-rw-r--r--   0 valentin   (501) staff       (20)     2743 2023-06-28 10:10:48.000000 hciplot-0.2.4/hciplot.egg-info/PKG-INFO
+-rw-r--r--   0 valentin   (501) staff       (20)      257 2023-06-28 10:10:48.000000 hciplot-0.2.4/hciplot.egg-info/SOURCES.txt
+-rw-r--r--   0 valentin   (501) staff       (20)        1 2023-06-28 10:10:48.000000 hciplot-0.2.4/hciplot.egg-info/dependency_links.txt
+-rw-r--r--   0 valentin   (501) staff       (20)       67 2023-06-28 10:10:48.000000 hciplot-0.2.4/hciplot.egg-info/requires.txt
+-rw-r--r--   0 valentin   (501) staff       (20)        8 2023-06-28 10:10:48.000000 hciplot-0.2.4/hciplot.egg-info/top_level.txt
+-rw-r--r--   0 valentin   (501) staff       (20)       66 2023-06-28 08:22:08.000000 hciplot-0.2.4/requirements.txt
+-rw-r--r--   0 valentin   (501) staff       (20)       38 2023-06-28 10:10:48.681619 hciplot-0.2.4/setup.cfg
+-rw-r--r--   0 valentin   (501) staff       (20)     2213 2022-05-16 15:51:24.000000 hciplot-0.2.4/setup.py
```

### Comparing `hciplot-0.2.3/.DS_Store` & `hciplot-0.2.4/.DS_Store`

 * *Files identical despite different names*

### Comparing `hciplot-0.2.3/.gitignore` & `hciplot-0.2.4/.gitignore`

 * *Files identical despite different names*

### Comparing `hciplot-0.2.3/LICENSE` & `hciplot-0.2.4/LICENSE`

 * *Files identical despite different names*

### Comparing `hciplot-0.2.3/PKG-INFO` & `hciplot-0.2.4/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hciplot
-Version: 0.2.3
+Version: 0.2.4
 Summary: High-contrast Imaging Plotting library
 Home-page: https://github.com/carlgogo/hciplot
 Download-URL: https://github.com/carlgogo/hciplot/archive/refs/tags/v0.1.8.tar.gz
 Author: Carlos Alberto Gomez Gonzalez, Valentin Christiaens
 Author-email: valentinchrist@hotmail.com
 License: MIT
 Keywords: plotting,hci,package
```

### Comparing `hciplot-0.2.3/README.md` & `hciplot-0.2.4/README.md`

 * *Files identical despite different names*

### Comparing `hciplot-0.2.3/hciplot/hciplot.py` & `hciplot-0.2.4/hciplot/hciplot.py`

 * *Files 10% similar despite different names*

```diff
@@ -5,16 +5,17 @@
 from decimal import *
 import os
 import shutil
 import numpy as np
 import holoviews as hv
 from holoviews import opts
 from subprocess import call
-from matplotlib.pyplot import (figure, subplot, show, Circle, savefig, close,
-                               hlines, annotate)
+from matplotlib.pyplot import (figure, subplot, show, savefig, close, hlines,
+                               annotate)
+from matplotlib.patches import Circle, Ellipse
 from matplotlib.pyplot import colorbar as plt_colorbar
 from mpl_toolkits.axes_grid1 import make_axes_locatable
 from matplotlib.cm import register_cmap
 import matplotlib.colors as colors
 from matplotlib.colors import LinearSegmentedColormap
 import warnings
 warnings.filterwarnings("ignore", module="matplotlib")
@@ -32,21 +33,24 @@
 cmap_binary = colors.ListedColormap(['black', 'white'])
 default_cmap = 'viridis'
 
 
 def plot_frames(data, backend='matplotlib', mode='mosaic', rows=1, vmax=None,
                 vmin=None, circle=None, circle_alpha=0.8, circle_color='white',
                 circle_linestyle='-', circle_radius=6, circle_label=False,
-                circle_label_color='white', arrow=None, arrow_alpha=0.8,
+                circle_label_color='white', ellipse=None, ellipse_alpha=0.8,
+                ellipse_color='white', ellipse_linestyle='-', ellipse_a=6,
+                ellipse_b=4, ellipse_angle=0, ellipse_label=False,
+                ellipse_label_color='white', arrow=None, arrow_alpha=0.8,
                 arrow_length=10, arrow_shiftx=5, arrow_label=None, label=None,
                 label_pad=5, label_size=12, label_color='white', grid=False,
                 grid_alpha=0.4,  grid_color='#f7f7f7', grid_spacing=None,
                 cross=None, cross_alpha=0.4, lab_fontsize=8, cross_color='white',
-                ang_scale=False, ang_ticksep=50, tick_direction='out', 
-                tick_color='black', ndec=1, pxscale=0.01, auscale=1., 
+                ang_scale=False, ang_ticksep=50, tick_direction='out',
+                tick_color='black', ndec=1, pxscale=0.01, auscale=1.,
                 ang_legend=False, au_legend=False, axis=True,
                 show_center=False, cmap=None, log=False, colorbar=True,
                 top_colorbar=False, colorbar_ticks=None, colorbar_ticksize=8,
                 colorbar_label='', colorbar_label_size=8, patch=None, dpi=100,
                 size_factor=6, horsp=0.4, versp=0.2, width=400, height=400,
                 title=None, tit_size=16, sampling=1, save=None,
                 return_fig_ax=False, transparent=False):
@@ -90,14 +94,35 @@
     circle_label : bool or string, optional
         [backend='matplotlib'] Whether to show the coordinates next to each
         circle. If a string: the string to be printed. If a tuple, should be 
         a tuple of strings with same length as 'circle'.
     circle_label_color : str, optional
         [backend='matplotlib'] Default 'white'. Sets the color of the circle
         label
+    ellipse : None, tuple or tuple of tuples, optional
+        [backend='matplotlib'] To show a circle at the given px coordinates. The
+        circles are shown on all subplots.
+    ellipse_alpha : float or tuple of floats, optional
+        [backend='matplotlib'] Alpha transparency for each circle.
+    ellipse_color : str, optional
+        [backend='matplotlib'] Color of the circles. White by default.
+    ellipse_a : int, optional
+        [backend='matplotlib'] Major axis of the ellipses, 6 px by default.
+    ellipse_b : int, optional
+        [backend='matplotlib'] Minor axis of the ellipses, 4 px by default.
+    ellipse_angle : float, optional
+        [backend='matplotlib'] Position angle of the major axis in deg, 0 by 
+        default.
+    ellipse_label : bool or string, optional
+        [backend='matplotlib'] Whether to show the coordinates next to each
+        circle. If a string: the string to be printed. If a tuple, should be 
+        a tuple of strings with same length as 'circle'.
+    ellipse_label_color : str, optional
+        [backend='matplotlib'] Default 'white'. Sets the color of the circle
+        label
     arrow : None or tuple of floats, optional
         [backend='matplotlib'] To show an arrow pointing to the given pixel
         coordinates.
     arrow_alpha : float, optional
         [backend='matplotlib'] Alpha transparency for the arrow.
     arrow_length : int, optional
         [backend='matplotlib'] Length of the arrow, 10 px by default.
@@ -318,20 +343,26 @@
     else:
         cols = int((num_plots / rows) + 1)
 
     # CIRCLE -------------------------------------------------------------------
     if circle is not None:
         if isinstance(circle, tuple):
             show_circle = True
-            if isinstance(circle[0], tuple):
+            if isinstance(circle[0], (tuple, list)):
                 n_circ = len(circle)
                 coor_circle = circle
-            elif isinstance(circle[0], (float, int)):
+                if len(circle[0]) != 2:
+                    raise TypeError("Circle coordinates should have length 2")
+            elif np.isscalar(circle[0]):
                 n_circ = 1
                 coor_circle = [circle] * n_circ
+            else:
+                msg = "Type of first element of input 'circle' not recognised."
+                msg += " Should be either scalar or tuple/list."
+                raise TypeError(msg)
         else:
             print("`circle` must be a tuple (X,Y) or tuple of tuples (X,Y)")
             show_circle = False
     else:
         show_circle = False
 
     if show_circle:
@@ -351,14 +382,61 @@
             circle_alpha = [circle_alpha] * n_circ
         elif isinstance(circle_alpha, tuple):
             # a different value for each circle
             if not n_circ == len(circle_alpha):
                 msg = '`circle_alpha` must have the same len as `circle`'
                 raise ValueError(msg)
 
+    # ELLIPSE ------------------------------------------------------------------
+    if ellipse is not None:
+        if isinstance(ellipse, tuple):
+            show_ellipse = True
+            if isinstance(ellipse[0], (tuple, list)):
+                n_ell = len(ellipse)
+                coor_ellipse = ellipse
+                if len(ellipse[0]) != 2:
+                    raise TypeError("Circle coordinates should have length 2")
+            elif np.isscalar(ellipse[0]):
+                n_ell = 1
+                coor_ellipse = [ellipse] * n_ell
+            else:
+                msg = "Type of first element of input 'circle' not recognised."
+                msg += " Should be either scalar or tuple/list."
+                raise TypeError(msg)
+        else:
+            print("`circle` must be a tuple (X,Y) or tuple of tuples (X,Y)")
+            show_ellipse = False
+    else:
+        show_ellipse = False
+
+    if show_ellipse:
+        if np.isscalar(ellipse_a) and np.isscalar(ellipse_b) and np.isscalar(ellipse_angle):
+            # single value is provided, used for all circles
+            ellipse_a = [ellipse_a] * n_ell
+            ellipse_b = [ellipse_b] * n_ell
+            ellipse_angle = [ellipse_angle] * n_ell
+        elif isinstance(ellipse_a, tuple) and isinstance(ellipse_b, tuple) and isinstance(ellipse_angle, tuple):
+            # a different value for each circle
+            if not n_ell == len(ellipse_a) or not n_ell == len(ellipse_b) or not n_ell == len(ellipse_angle):
+                msg = '`ellipse_a` and `ellipse_b` and `ellipse_angle` must have the same len as `ellipse`'
+                raise ValueError(msg)
+        else:
+            msg = "`ellipse_a`, `ellipse_b` and `ellipse_angle` must either all be scalars or "
+            msg += "all tuples of the same length as the number of ellipses to plot"
+            raise TypeError(msg)
+
+    if show_ellipse:
+        if isinstance(ellipse_alpha, (float, int)):
+            ellipse_alpha = [ellipse_alpha] * n_ell
+        elif isinstance(ellipse_alpha, tuple):
+            # a different value for each circle
+            if not n_ell == len(ellipse_alpha):
+                msg = '`ellipse_alpha` must have the same len as `ellipse`'
+                raise ValueError(msg)
+
     # ARROW --------------------------------------------------------------------
     if arrow is not None:
         if isinstance(arrow, tuple):
             show_arrow = True
         else:
             raise ValueError("`arrow` must be a tuple (X,Y)")
     else:
@@ -577,17 +655,52 @@
                         if isinstance(circle_label, str):
                             cirlabel = circle_label
                         elif isinstance(circle_label, tuple):
                             cirlabel = circle_label[j]
                         else:
                             cirlabel = str(int(x))+','+str(int(y))
                         ax.text(x, y + circle_radius[j] + c_offset, cirlabel,
-                                fontsize=label_size, color=circle_label_color, family='monospace',
-                                ha='center', va='center', weight='bold',
-                                alpha=circle_alpha[j])
+                                fontsize=label_size, color=circle_label_color,
+                                family='monospace', ha='center', va='center',
+                                weight='bold', alpha=circle_alpha[j])
+
+            if show_ellipse and plot_mosaic:
+                if isinstance(ellipse_linestyle, tuple):
+                    e_offset = ellipse_linestyle[0]
+                    ellipse_linestyle = ellipse_linestyle[1]
+                else:
+                    e_offset = label_size+1  # vertical offset is equal to the font size + 1, was 2
+                for j in range(n_ell):
+                    if isinstance(ellipse_color, (list, tuple)):
+                        ellipse_color_tmp = ellipse_color[j]
+                    else:
+                        ellipse_color_tmp = ellipse_color
+                    if isinstance(ellipse_linestyle, (list, tuple)):
+                        ellipse_linestyle_tmp = ellipse_linestyle[j]
+                    else:
+                        ellipse_linestyle_tmp = ellipse_linestyle
+                    ell = Ellipse(coor_ellipse[j], width=ellipse_a[j],
+                                  height=ellipse_b[j], angle=ellipse_angle[j],
+                                  fill=False, color=ellipse_color_tmp,
+                                  alpha=ellipse_alpha[j],
+                                  ls=ellipse_linestyle_tmp)
+                    ax.add_artist(ell)
+                    if ellipse_label:
+                        x = coor_ellipse[j][0]
+                        y = coor_ellipse[j][1]
+                        if isinstance(ellipse_label, str):
+                            elllabel = ellipse_label
+                        elif isinstance(ellipse_label, tuple):
+                            elllabel = ellipse_label[j]
+                        else:
+                            elllabel = str(int(x))+','+str(int(y))
+                        ax.text(x, y + ellipse_a[j] + e_offset, elllabel,
+                                fontsize=label_size, color=ellipse_label_color,
+                                family='monospace', ha='center', va='center',
+                                weight='bold', alpha=ellipse_alpha[j])
 
             if show_cross and plot_mosaic:
                 ax.axhline(coor_cross[0], xmin=0, xmax=frame_size, alpha=cross_alpha, lw=0.6,
                            linestyle='dashed', color='white')
                 ax.axvline(coor_cross[1], ymin=0, ymax=frame_size, alpha=cross_alpha, lw=0.6,
                            linestyle='dashed', color='white')
 
@@ -667,53 +780,58 @@
                     labels_x.append(
                         round(Decimal(t * (ang_ticksep * pxscale)), ndec))
                 ax.set_xticklabels(labels_x)
                 ax.set_yticklabels(labels_y)
                 ax.set_xlabel('\u0394RA ["]', fontsize=label_size)
                 ax.set_ylabel('\u0394Dec ["]', fontsize=label_size)
                 ax.minorticks_on()
-                ax.tick_params(axis='both', which='both', labelsize=label_size, direction=tick_direction, color=tick_color)
+                ax.tick_params(axis='both', which='both', labelsize=label_size,
+                               direction=tick_direction, color=tick_color)
 
             else:
                 ax.set_xlabel("x", fontsize=label_size)
                 ax.set_ylabel("y", fontsize=label_size)
 
             if not axis[i]:
                 ax.set_axis_off()
 
             if colorbar[i] and plot_mosaic:
                 divider = make_axes_locatable(ax)
                 # the width of cax is 5% of ax and the padding between cax
                 # and ax wis fixed at 0.05 inch
                 if top_colorbar:
                     cax = divider.append_axes("top", size="5%", pad=0.05)
-                    cb = plt_colorbar(im, ax=ax, cax=cax, drawedges=False, ticks=cbticks, orientation='horizontal')
+                    cb = plt_colorbar(
+                        im, ax=ax, cax=cax, drawedges=False, ticks=cbticks, orientation='horizontal')
                     cb.ax.xaxis.set_ticks_position('top')
                     cb.ax.xaxis.set_label_position('top')
                 else:
                     cax = divider.append_axes("right", size="5%", pad=0.05)
-                    cb = plt_colorbar(im, ax=ax, cax=cax, drawedges=False, ticks=cbticks)
+                    cb = plt_colorbar(im, ax=ax, cax=cax,
+                                      drawedges=False, ticks=cbticks)
                 cb.outline.set_linewidth(0.1)
                 cb.ax.tick_params(labelsize=colorbar_ticksize)
                 if colorbar_label != '':
-                    cb.set_label(label=colorbar_label, fontsize=colorbar_label_size)
+                    cb.set_label(label=colorbar_label,
+                                 fontsize=colorbar_label_size)
 
             if patch is not None:
-                beam = Circle(xy=(frame_size/10, frame_size/6), radius=patch/2, color='grey', fill=True, alpha=1)
+                beam = Circle(xy=(frame_size/10, frame_size/6),
+                              radius=patch/2, color='grey', fill=True, alpha=1)
                 ax.add_artist(beam)
 
         fig.subplots_adjust(wspace=horsp, hspace=versp)
         if save is not None and isinstance(save, str):
             savefig(save, dpi=dpi, bbox_inches='tight', pad_inches=0,
                     transparent=transparent)
             close()
         elif return_fig_ax is False and save is None:
             show()
         elif return_fig_ax and save is None:
-            return fig,ax
+            return fig, ax
 
     elif backend == 'bokeh':
         hv.extension(backend)
         subplots = []
         # options = "Image (cmap='" + custom_cmap[0] + "')"  # taking first item
         # hv.opts(options)
```

### Comparing `hciplot-0.2.3/hciplot.egg-info/PKG-INFO` & `hciplot-0.2.4/hciplot.egg-info/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hciplot
-Version: 0.2.3
+Version: 0.2.4
 Summary: High-contrast Imaging Plotting library
 Home-page: https://github.com/carlgogo/hciplot
 Download-URL: https://github.com/carlgogo/hciplot/archive/refs/tags/v0.1.8.tar.gz
 Author: Carlos Alberto Gomez Gonzalez, Valentin Christiaens
 Author-email: valentinchrist@hotmail.com
 License: MIT
 Keywords: plotting,hci,package
```

### Comparing `hciplot-0.2.3/setup.py` & `hciplot-0.2.4/setup.py`

 * *Files identical despite different names*


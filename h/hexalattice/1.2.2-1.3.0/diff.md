# Comparing `tmp/hexalattice-1.2.2.tar.gz` & `tmp/hexalattice-1.3.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\hexalattice-1.2.2.tar", last modified: Mon Mar  6 23:21:01 2023, max compression
+gzip compressed data, was "hexalattice-1.3.0.tar", last modified: Wed Jun 28 10:51:26 2023, max compression
```

## Comparing `hexalattice-1.2.2.tar` & `hexalattice-1.3.0.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxrwxrwx   0        0        0        0 2023-03-06 23:21:01.847511 hexalattice-1.2.2/
--rw-rw-rw-   0        0        0     1119 2023-03-06 21:54:43.000000 hexalattice-1.2.2/LICENSE
--rw-rw-rw-   0        0        0     4535 2023-03-06 23:21:01.846512 hexalattice-1.2.2/PKG-INFO
--rw-rw-rw-   0        0        0     4043 2023-03-06 21:54:43.000000 hexalattice-1.2.2/README.md
-drwxrwxrwx   0        0        0        0 2023-03-06 23:21:01.819583 hexalattice-1.2.2/hexalattice/
--rw-rw-rw-   0        0        0        0 2023-03-06 21:54:43.000000 hexalattice-1.2.2/hexalattice/__init__.py
--rw-rw-rw-   0        0        0    17753 2023-03-06 22:58:46.000000 hexalattice-1.2.2/hexalattice/hexalattice.py
-drwxrwxrwx   0        0        0        0 2023-03-06 23:21:01.845518 hexalattice-1.2.2/hexalattice.egg-info/
--rw-rw-rw-   0        0        0     4535 2023-03-06 23:21:01.000000 hexalattice-1.2.2/hexalattice.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      251 2023-03-06 23:21:01.000000 hexalattice-1.2.2/hexalattice.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-03-06 23:21:01.000000 hexalattice-1.2.2/hexalattice.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       22 2023-03-06 23:21:01.000000 hexalattice-1.2.2/hexalattice.egg-info/requires.txt
--rw-rw-rw-   0        0        0       12 2023-03-06 23:21:01.000000 hexalattice-1.2.2/hexalattice.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-03-06 23:21:01.847511 hexalattice-1.2.2/setup.cfg
--rw-rw-rw-   0        0        0     1033 2023-03-06 23:20:03.000000 hexalattice-1.2.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:51:26.847886 hexalattice-1.3.0/
+-rw-rw-rw-   0        0        0     1098 2023-06-28 10:34:52.000000 hexalattice-1.3.0/LICENSE
+-rw-rw-rw-   0        0        0     4722 2023-06-28 10:51:26.847886 hexalattice-1.3.0/PKG-INFO
+-rw-rw-rw-   0        0        0     4113 2023-06-28 10:44:48.000000 hexalattice-1.3.0/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 10:51:26.833925 hexalattice-1.3.0/hexalattice/
+-rw-rw-rw-   0        0        0        0 2023-06-28 10:34:52.000000 hexalattice-1.3.0/hexalattice/__init__.py
+-rw-rw-rw-   0        0        0    17481 2023-06-28 10:49:10.000000 hexalattice-1.3.0/hexalattice/hexalattice.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:51:26.846888 hexalattice-1.3.0/hexalattice.egg-info/
+-rw-rw-rw-   0        0        0     4722 2023-06-28 10:51:26.000000 hexalattice-1.3.0/hexalattice.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      251 2023-06-28 10:51:26.000000 hexalattice-1.3.0/hexalattice.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:51:26.000000 hexalattice-1.3.0/hexalattice.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       22 2023-06-28 10:51:26.000000 hexalattice-1.3.0/hexalattice.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       12 2023-06-28 10:51:26.000000 hexalattice-1.3.0/hexalattice.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 10:51:26.848884 hexalattice-1.3.0/setup.cfg
+-rw-rw-rw-   0        0        0      997 2023-06-28 10:42:26.000000 hexalattice-1.3.0/setup.py
```

### Comparing `hexalattice-1.2.2/LICENSE` & `hexalattice-1.3.0/LICENSE`

 * *Ordering differences only*

 * *Files 16% similar despite different names*

```diff
@@ -1,21 +1,21 @@
-The MIT License
-
-Copyright (c) 2010-2020 Google LLC. http://angularjs.org
-
-Permission is hereby granted, free of charge, to any person obtaining a copy
-of this software and associated documentation files (the "Software"), to deal
-in the Software without restriction, including without limitation the rights
-to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
-copies of the Software, and to permit persons to whom the Software is
-furnished to do so, subject to the following conditions:
-
-The above copyright notice and this permission notice shall be included in
-all copies or substantial portions of the Software.
-
-THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
-IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
-FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
-AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
-LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
-OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
-THE SOFTWARE.
+The MIT License
+
+Copyright (c) 2010-2020 Google LLC. http://angularjs.org
+
+Permission is hereby granted, free of charge, to any person obtaining a copy
+of this software and associated documentation files (the "Software"), to deal
+in the Software without restriction, including without limitation the rights
+to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
+copies of the Software, and to permit persons to whom the Software is
+furnished to do so, subject to the following conditions:
+
+The above copyright notice and this permission notice shall be included in
+all copies or substantial portions of the Software.
+
+THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
+IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
+FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
+AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
+LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
+OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
+THE SOFTWARE.
```

### Comparing `hexalattice-1.2.2/PKG-INFO` & `hexalattice-1.3.0/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: hexalattice
-Version: 1.2.2
+Version: 1.3.0
 Summary: Compute and plot hexagonal grids
 Home-page: https://github.com/alexkaz2/hexalattice/wiki
 Author: Alex Kazakov
 Author-email: alex.kazakov@mail.huji.ac.il
 License: MIT
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
@@ -23,18 +23,19 @@
 </p>
 
 
 
 ## Installation
 
 [![PyPI version](https://badge.fury.io/py/hexalattice.svg)](https://badge.fury.io/py/hexalattice)
+![conda](https://anaconda.org/conda-forge/hexalattice/badges/version.svg)
 ![python version](https://upload.wikimedia.org/wikipedia/commons/f/fc/Blue_Python_3.7_Shield_Badge.svg)
-![conda](https://anaconda.org/conda-forge/hexalattice/badges/installer/conda.svg)
 ![downloads_anaconda](https://anaconda.org/conda-forge/hexalattice/badges/downloads.svg)
 ![license](https://anaconda.org/conda-forge/hexalattice/badges/license.svg)
+![last updated](https://anaconda.org/conda-forge/hexalattice/badges/latest_release_relative_date.svg)
 
 ```sh
 # Using pip
 pip install hexalattice
 ```
 ```sh
 # Using conda
@@ -77,15 +78,15 @@
 plt.show()
 ```
 
 <p align="center">
   <img width="600" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice5.png">
 </p>
 
-Create MoirÃ© pattern from two circularly cropped hexagrids:
+Create Moirֳ© pattern from two circularly cropped hexagrids:
 ```sh
 hex_grid1, h_ax = create_hex_grid(nx=50,
                                   ny=50,
                                   rotate_deg=0,
                                   min_diam=1,
                                   crop_circ=20,
                                   do_plot=True)
@@ -115,15 +116,17 @@
 </p>
 
 ## Release History
 
 * v1.0.0 - First version
 * v1.1.0 - Added the option to assign different colors to hexagons
 * v1.2.0 - Added control over the outer line width of the hexagons
+* v1.2.2 - Added control over the axis background color
+* v1.3.0 - Reduced runtime by 50%
 
 ## About & License
 
-Alex Kazakov â€“ [@bio_vs_silico](https://twitter.com/bio_vs_silico) â€“ alex.kazakov@mail.huji.ac.il
+Alex Kazakov ג€“ [@bio_vs_silico](https://twitter.com/bio_vs_silico) ג€“ alex.kazakov@mail.huji.ac.il
 
 Distributed under the MIT license. See ``LICENSE`` for more information.
 
 [https://github.com/alexkaz2/hexalattice](https://github.com/alexkaz2/)
```

### Comparing `hexalattice-1.2.2/README.md` & `hexalattice-1.3.0/hexalattice.egg-info/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,25 +1,41 @@
+Metadata-Version: 2.1
+Name: hexalattice
+Version: 1.3.0
+Summary: Compute and plot hexagonal grids
+Home-page: https://github.com/alexkaz2/hexalattice/wiki
+Author: Alex Kazakov
+Author-email: alex.kazakov@mail.huji.ac.il
+License: MIT
+Classifier: License :: OSI Approved :: MIT License
+Classifier: Programming Language :: Python :: 3
+Classifier: Programming Language :: Python :: 3.7
+Requires-Python: >=3.5
+Description-Content-Type: text/markdown
+License-File: LICENSE
+
 # hexalattice
 
 Generate and plot hexagonal lattices in 2D, with fine control over spacing between hexagons, arbitrary rotation of the grid around central tile, etc.
 The module computes and returns the center point for each of the tiles in the lattice. 
 
 <p align="center">
   <img width="1000" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/collage.png">
 </p>
 
 
 
 ## Installation
 
 [![PyPI version](https://badge.fury.io/py/hexalattice.svg)](https://badge.fury.io/py/hexalattice)
+![conda](https://anaconda.org/conda-forge/hexalattice/badges/version.svg)
 ![python version](https://upload.wikimedia.org/wikipedia/commons/f/fc/Blue_Python_3.7_Shield_Badge.svg)
-![conda](https://anaconda.org/conda-forge/hexalattice/badges/installer/conda.svg)
 ![downloads_anaconda](https://anaconda.org/conda-forge/hexalattice/badges/downloads.svg)
 ![license](https://anaconda.org/conda-forge/hexalattice/badges/license.svg)
+![last updated](https://anaconda.org/conda-forge/hexalattice/badges/latest_release_relative_date.svg)
 
 ```sh
 # Using pip
 pip install hexalattice
 ```
 ```sh
 # Using conda
@@ -62,15 +78,15 @@
 plt.show()
 ```
 
 <p align="center">
   <img width="600" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice5.png">
 </p>
 
-Create Moiré pattern from two circularly cropped hexagrids:
+Create Moirֳ© pattern from two circularly cropped hexagrids:
 ```sh
 hex_grid1, h_ax = create_hex_grid(nx=50,
                                   ny=50,
                                   rotate_deg=0,
                                   min_diam=1,
                                   crop_circ=20,
                                   do_plot=True)
@@ -100,15 +116,17 @@
 </p>
 
 ## Release History
 
 * v1.0.0 - First version
 * v1.1.0 - Added the option to assign different colors to hexagons
 * v1.2.0 - Added control over the outer line width of the hexagons
+* v1.2.2 - Added control over the axis background color
+* v1.3.0 - Reduced runtime by 50%
 
 ## About & License
 
-Alex Kazakov – [@bio_vs_silico](https://twitter.com/bio_vs_silico) – alex.kazakov@mail.huji.ac.il
+Alex Kazakov ג€“ [@bio_vs_silico](https://twitter.com/bio_vs_silico) ג€“ alex.kazakov@mail.huji.ac.il
 
 Distributed under the MIT license. See ``LICENSE`` for more information.
 
 [https://github.com/alexkaz2/hexalattice](https://github.com/alexkaz2/)
```

### Comparing `hexalattice-1.2.2/hexalattice/hexalattice.py` & `hexalattice-1.3.0/hexalattice/hexalattice.py`

 * *Files 18% similar despite different names*

```diff
@@ -1,379 +1,390 @@
-# -----------------------------------------------------------
-# hexalattice module creates and prints hexagonal lattices
-#
-# (C) 2020 Alex Kazakov,
-# Released under MIT License
-# email alex.kazakov@mail.huji.ac.il
-# Full documentation: https://github.com/alexkaz2/hexalattice
-# -----------------------------------------------------------
-
-
-import numpy as np
-import matplotlib.pyplot as plt
-import matplotlib.patches as mpatches
-from matplotlib.collections import PatchCollection
-from typing import List, Union
-import matplotlib
-matplotlib.use('Qt5Agg')
-
-
-def create_hex_grid(nx: int = 4,
-                    ny: int = 5,
-                    min_diam: float = 1.,
-                    n: int = 0,
-                    align_to_origin: bool = True,
-                    face_color: Union[List[float], str] = None,
-                    edge_color: Union[List[float], str] = None,
-                    plotting_gap: float = 0.,
-                    crop_circ: float = 0.,
-                    do_plot: bool = False,
-                    rotate_deg: float = 0.,
-                    keep_x_sym: bool = True,
-                    h_ax: plt.Axes = None,
-                    line_width: float = 0.2,
-                    background_color: Union[List[float], str] = None) -> (np.ndarray, plt.Axes):
-    """
-    Creates and prints hexagonal lattices.
-    :param nx: Number of horizontal hexagons in rectangular grid, [nx * ny]
-    :param ny: Number of vertical hexagons in rectangular grid, [nx * ny]
-    :param min_diam: Minimal diameter of each hexagon.
-    :param n: Alternative way to create rectangular grid. The final grid might have less hexagons
-    :param align_to_origin: Shift the grid s.t. the central tile will center at the origin
-    :param face_color: Provide RGB triplet, valid abbreviation (e.g. 'k') or RGB+alpha
-    :param edge_color: Provide RGB triplet, valid abbreviation (e.g. 'k') or RGB+alpha
-    :param plotting_gap: Gap between the edges of adjacent tiles, in fraction of min_diam
-    :param crop_circ: Disabled if 0. If >0 a circle of central tiles will be kept, with radius r=crop_circ
-    :param do_plot: Add the hexagon to an axes. If h_ax not provided a new figure will be opened.
-    :param rotate_deg: Rotate the grid around the center of the central tile, by rotate_deg degrees
-    :param keep_x_sym: NOT YET IMPLEMENTED
-    :param h_ax: Handle to axes. If provided the grid will be added to it, if not a new figure will be opened.
-    :param line_width: The width of the hexagon lines
-    :param background_color: The color of the axis background
-    :return:
-    """
-
-    args_are_ok = check_inputs(nx, ny, min_diam, n, align_to_origin, face_color, edge_color, plotting_gap, crop_circ,
-                               do_plot, rotate_deg, keep_x_sym, background_color)
-    if not args_are_ok:
-        print('Aborting hexagonal grid creation...')
-        exit()
-    coord_x, coord_y = make_grid(nx, ny, min_diam, n, crop_circ, rotate_deg, align_to_origin)
-
-    if do_plot:
-        h_ax = plot_single_lattice(coord_x, coord_y, face_color, edge_color, min_diam, plotting_gap, rotate_deg, h_ax,
-                                   background_color, line_width)
-
-    return np.hstack([coord_x, coord_y]), h_ax
-
-
-def check_inputs(nx, ny, min_diam, n, align_to_origin, face_color, edge_color, plotting_gap, crop_circ, do_plot,
-                 rotate_deg, keep_x_sym, background_color):
-    """
-    Validate input types, ranges and co-compatibility
-    :return: bool - Assertion verdict
-    """
-    args_are_valid = True
-    if (not isinstance(nx, (int, float))) or (not isinstance(ny, (int, float))) or (not isinstance(n, (int, float))) \
-            or (nx < 0) or (nx < 0) or (nx < 0):
-        print('Argument error in hex_grid: nx, ny and n are expected to be integers')
-        args_are_valid = False
-
-    if (not isinstance(min_diam, (float, int))) or (not isinstance(crop_circ, (float, int))) or (min_diam < 0) or \
-            (crop_circ < 0):
-        print('Argument error in hex_grid: min_diam and crop_circ are expected to be floats')
-        args_are_valid = False
-
-    if (not isinstance(align_to_origin, bool)) or (not isinstance(do_plot, bool)):
-        print('Argument error in hex_grid: align_to_origin and do_plot are expected to be booleans')
-        args_are_valid = False
-
-    VALID_C_ABBR = {'b', 'g', 'r', 'c', 'm', 'y', 'k', 'w'}
-    if (isinstance(face_color, str) and (not face_color in VALID_C_ABBR)) or \
-            (isinstance(background_color, str) and (not background_color in VALID_C_ABBR)) or \
-            (isinstance(edge_color, str) and (not edge_color in VALID_C_ABBR)):
-        print('Argument error in hex_grid: edge_color and face_color are expected to valid color abbrs, e.g. `k`')
-        args_are_valid = False
-
-    if (isinstance(face_color, List) and ((len(face_color) not in (3, 4)) or
-                                          (True in ((x < 0) or (x > 1) for x in face_color)))) or \
-            (isinstance(background_color, List) and ((len(background_color) not in (3, 4)) or
-                                               (True in ((x < 0) or (x > 1) for x in face_color)))) or \
-            (isinstance(edge_color, List) and ((len(edge_color) not in (3, 4)) or
-                                          (True in ((x < 0) or (x > 1) for x in edge_color)))):
-        print('Argument error in hex_grid: edge_color and face_color are expected to be valid RGB color triplets or '
-              'color abbreviations, e.g. [0.1 0.3 0.95] or `k`')
-        args_are_valid = False
-
-    if (not isinstance(plotting_gap, float)) or (plotting_gap < 0) or (plotting_gap >= 1):
-        print('Argument error in hex_grid: plotting_gap is expected to be a float in range [0, 1)')
-        args_are_valid = False
-
-    if not isinstance(rotate_deg, (float, int)):
-        print('Argument error in hex_grid: float is expected to be float or integer')
-        args_are_valid = False
-
-    if (n == 0) and ((nx == 0) or (ny == 0)):
-        print('Argument error in hex_grid: Expected either n>0 or both [nx.ny]>0')
-        args_are_valid = False
-
-    if (isinstance(min_diam, (float, int)) and isinstance(crop_circ, (float, int))) and \
-            (not np.isclose(crop_circ, 0)) and (crop_circ < min_diam):
-        print('Argument error in hex_grid: Cropping radius is expected to be bigger than a single hexagon diameter')
-        args_are_valid = False
-
-    if not isinstance(keep_x_sym, bool):
-        print('Argument error in hex_grid: keep_x_sym is expected to be boolean')
-        args_are_valid = False
-
-    return args_are_valid
-
-
-def plot_single_lattice(coord_x, coord_y, face_color, edge_color, min_diam, plotting_gap, rotate_deg, h_ax=None,
-                        background_color=None, line_width=0.2):
-    """
-    Adds a single lattice to the axes canvas. Multiple calls can be made to overlay few lattices.
-    :return:
-    """
-    if face_color is None:
-        face_color = (1, 1, 1, 0)  # Make the face transparent
-    if edge_color is None:
-        edge_color = 'k'
-
-    if h_ax is None:
-        h_fig = plt.figure(figsize=(5, 5))
-        h_ax = h_fig.add_axes([0.05, 0.05, 0.9, 0.9])
-
-    if background_color is not None:
-        h_ax.set_facecolor(background_color)
-    patches = []
-    for curr_x, curr_y in zip(coord_x, coord_y):
-        polygon = mpatches.RegularPolygon((curr_x, curr_y), numVertices=6,
-                                          radius=min_diam / np.sqrt(3) * (1 - plotting_gap),
-                                          orientation=np.deg2rad(-rotate_deg))
-        patches.append(polygon)
-    collection = PatchCollection(patches, edgecolor=edge_color, facecolor=face_color, linewidths=line_width)
-    h_ax.add_collection(collection)
-
-    h_ax.set_aspect('equal')
-    h_ax.axis([coord_x.min() - 2 * min_diam, coord_x.max() + 2 * min_diam, coord_y.min() - 2 * min_diam,
-               coord_y.max() + 2 * min_diam])
-    # plt.plot(0, 0, 'r.', markersize=5)   # Add red point at the origin
-    return h_ax
-
-
-def make_grid(nx, ny, min_diam, n, crop_circ, rotate_deg, align_to_origin) -> (np.ndarray, np.ndarray):
-    """
-    Computes the coordinates of the hexagon centers, given the size rotation and layout specifications
-    :return:
-    """
-    ratio = np.sqrt(3) / 2
-    if n > 0:  # n variable overwrites (nx, ny) in case all three were provided
-        ny = int(np.sqrt(n / ratio))
-        nx = n // ny
-
-    coord_x, coord_y = np.meshgrid(np.arange(nx), np.arange(ny), sparse=False, indexing='xy')
-    coord_y = coord_y * ratio
-    coord_x = coord_x.astype('float')
-    coord_x[1::2, :] += 0.5
-    coord_x = coord_x.reshape(-1, 1)
-    coord_y = coord_y.reshape(-1, 1)
-
-    coord_x *= min_diam  # Scale to requested size
-    coord_y = coord_y.astype('float') * min_diam
-
-    mid_x = (np.ceil(nx / 2) - 1) + 0.5 * (np.ceil(ny/2) % 2 == 0)  # Pick center of some hexagon as origin for rotation or crop...
-    mid_y = (np.ceil(ny / 2) - 1) * ratio  # np.median() averages center 2 values for even arrays :\
-    mid_x *= min_diam
-    mid_y *= min_diam
-
-    # mid_x = (nx // 2 - (nx % 2 == 1)) * min_diam + 0.5 * (ny % 2 == 1)
-    # mid_y = (ny // 2 - (ny % 2)) * min_diam * ratio
-
-    if crop_circ > 0:
-        rad = ((coord_x - mid_x)**2 + (coord_y - mid_y)**2)**0.5
-        coord_x = coord_x[rad.flatten() <= crop_circ, :]
-        coord_y = coord_y[rad.flatten() <= crop_circ, :]
-
-    if not np.isclose(rotate_deg, 0):  # Check if rotation is not 0, with tolerance due to float format
-        # Clockwise, 2D rotation matrix
-        RotMatrix = np.array([[np.cos(np.deg2rad(rotate_deg)), np.sin(np.deg2rad(rotate_deg))],
-                              [-np.sin(np.deg2rad(rotate_deg)), np.cos(np.deg2rad(rotate_deg))]])
-        rot_locs = np.hstack((coord_x - mid_x, coord_y - mid_y)) @ RotMatrix.T
-        # rot_locs = np.hstack((coord_x - mid_x, coord_y - mid_y))
-        coord_x, coord_y = np.hsplit(rot_locs + np.array([mid_x, mid_y]), 2)
-
-    if align_to_origin:
-        coord_x -= mid_x
-        coord_y -= mid_y
-
-    return coord_x, coord_y
-
-
-def plot_single_lattice_custom_colors(coord_x, coord_y, face_color, edge_color, min_diam, plotting_gap, rotate_deg,
-                                      line_width=1., h_ax=None, background_color=None):
-    """
-    Plot hexagonal lattice where every hexagon is colored by an individual color.
-    All inputs are similar to the plot_single_lattice() except:
-    :param line_width:
-    :param h_ax:
-    :param rotate_deg:
-    :param plotting_gap:
-    :param min_diam:
-    :param coord_y:
-    :param coord_x:
-    :param face_color: numpy array, Nx3 or Nx4 - Color list of length |coord_x| for each hexagon face.
-                                                 Each row is a RGB or RGBA values, e.g. [0.3 0.3 0.3 1]
-    :param edge_color: numpy array, Nx3 or Nx4 - Color list of length |coord_x| for each hexagon edge.
-                                                 Each row is a RGB or RGBA values, e.g. [0.3 0.3 0.3 1]
-    :return:
-    """
-
-    if h_ax is None:
-        h_fig = plt.figure(figsize=(5, 5))
-        h_ax = h_fig.add_axes([0.05, 0.05, 0.9, 0.9])
-        if background_color is not None:
-            h_ax.set_facecolor(background_color)
-
-    for i, (curr_x, curr_y) in enumerate(zip(coord_x, coord_y)):
-        polygon = mpatches.RegularPolygon((curr_x, curr_y), numVertices=6,
-                                          radius=min_diam / np.sqrt(3) * (1 - plotting_gap),
-                                          orientation=np.deg2rad(-rotate_deg),
-                                          edgecolor=edge_color[i],
-                                          facecolor=face_color[i], linewidth=line_width)
-        h_ax.add_artist(polygon)
-
-    h_ax.set_aspect('equal')
-    h_ax.axis([coord_x.min() - 2 * min_diam, coord_x.max() + 2 * min_diam, coord_y.min() - 2 * min_diam,
-               coord_y.max() + 2 * min_diam])
-    # plt.plot(0, 0, 'r.', markersize=5)   # Add red point at the origin
-    return h_ax
-
-
-def sample_colors_from_image_by_grid(image_path: str, x_coords, y_coords):
-    """
-    Sample colors of a set of points from an image.
-    :param image_path: str - Path to an image file (.png, .jpg)
-    :param x_coords: list - x coordinates of the hexagons. The range doesn't matter since it is rescaled to fit the image
-    :param y_coords: list - y -----//------
-    :return:
-    """
-    from matplotlib.image import imread
-    img = imread(image_path) / 255
-    img = np.flip(img, 0)  # Flip Y axis. Images = matrices where pixel [0, 0] is in the upper left corner
-
-    abs_min = np.min([x_coords.T, y_coords.T])
-    abs_max = np.max([x_coords.T, y_coords.T]) + 0.001
-    minor_image_dim = min(img.shape[0], img.shape[1])
-    p_x = np.floor((x_coords - abs_min) / (abs_max - abs_min) * minor_image_dim)
-    p_y = np.floor((y_coords - abs_min) / (abs_max - abs_min) * minor_image_dim)
-
-    colors = img[p_y.astype('int'), p_x.astype('int'), :]
-    return colors
-
-
-def main():
-
-    plt.ion()
-
-    # (1) === Create single hexagonal 5*5 lattice and plot it. Extract the [x,y] locations of the tile centers
-    hex_centers, h_ax = create_hex_grid(nx=5, ny=5, do_plot=True)
-    tile_centers_x = hex_centers[:, 0]
-    tile_centers_y = hex_centers[:, 1]
-    # plt.show(block=True)   % The 'show' call should be done explicitly
-
-    # (2) === Create single hexagonal lattice, 5*5, rotated around central tile ====
-    hex_centers, _ = create_hex_grid(nx=5,
-                                     ny=5,
-                                     plotting_gap=0.05,
-                                     min_diam=1,
-                                     rotate_deg=5,
-                                     face_color=[0.9, 0.1, 0.1, 0.05],
-                                     do_plot=True)
-
-    # (3) === Plot Moire pattern with two round hexagonal grids ====
-    hex_grid1, h_ax = create_hex_grid(nx=50,
-                                      ny=50,
-                                      rotate_deg=0,
-                                      min_diam=1,
-                                      crop_circ=20,
-                                      do_plot=True)
-    create_hex_grid(nx=50,
-                    ny=50,
-                    min_diam=1,
-                    rotate_deg=5,
-                    crop_circ=20,
-                    do_plot=True,
-                    h_ax=h_ax)
-
-    # (4) === Create 5 layers of grids of various sizes ====
-    face_c = [0.7, 0.7, 0.7, 0.1]
-    _, h_ax = create_hex_grid(nx=5,
-                              ny=4,
-                              plotting_gap=0.2,
-                              face_color=face_c,
-                              min_diam=1,
-                              do_plot=True)
-    create_hex_grid(nx=4,
-                    ny=3,
-                    min_diam=1,
-                    plotting_gap=0.3,
-                    face_color=face_c,
-                    do_plot=True,
-                    h_ax=h_ax)
-    create_hex_grid(nx=2,
-                    ny=2,
-                    plotting_gap=0.4,
-                    face_color=face_c,
-                    do_plot=True,
-                    h_ax=h_ax)
-    create_hex_grid(nx=1,
-                    ny=1,
-                    plotting_gap=0.5,
-                    face_color=face_c,
-                    do_plot=True,
-                    h_ax=h_ax)
-    create_hex_grid(nx=10,
-                    ny=10,
-                    edge_color=[0.9, 0.9, 0.9],
-                    line_width=0.3,
-                    do_plot=True,
-                    h_ax=h_ax)
-
-    # (5) === Color hexagons with custom colors ===
-    image_path = r'example_image.jpg'  # taken from https://en.wikipedia.org/wiki/Apple#/media/File:Red_Apple.jpg
-    hex_centers, h_ax = create_hex_grid(nx=50, ny=50, do_plot=False)
-    colors = sample_colors_from_image_by_grid(image_path, hex_centers[:, 0], hex_centers[:, 1])
-
-    fig, axs = plt.subplots(2, 2)
-    axs[0, 0].imshow(plt.imread(image_path))
-    plot_single_lattice_custom_colors(hex_centers[:, 0], hex_centers[:, 1],
-                                      face_color=colors,
-                                      edge_color=colors,
-                                      min_diam=1.,
-                                      plotting_gap=0,
-                                      rotate_deg=0,
-                                      line_width=0.3,
-                                      h_ax=axs[0, 1])
-    plot_single_lattice_custom_colors(hex_centers[:, 0], hex_centers[:, 1],
-                                      face_color=colors,
-                                      edge_color=colors*0,
-                                      min_diam=1.,
-                                      plotting_gap=0,
-                                      rotate_deg=0,
-                                      line_width=1.,
-                                      h_ax=axs[1, 0])
-    plot_single_lattice_custom_colors(hex_centers[:, 0], hex_centers[:, 1],
-                                      face_color=colors,
-                                      edge_color=colors*0,
-                                      min_diam=1.,
-                                      plotting_gap=0,
-                                      rotate_deg=0,
-                                      line_width=0.1,
-                                      h_ax=axs[1, 1])
-
-    plt.show(block=True)
-
-
-if __name__ == "__main__":
-    # Main function includes multiple examples
-    main()
+# -----------------------------------------------------------
+# hexalattice module creates and prints hexagonal lattices
+#
+# (C) 2020 Alex Kazakov,
+# Released under MIT License
+# email alex.kazakov@mail.huji.ac.il
+# Full documentation: https://github.com/alexkaz2/hexalattice
+# -----------------------------------------------------------
+
+
+import numpy as np
+import matplotlib.pyplot as plt
+import matplotlib.patches as mpatches
+from matplotlib.collections import PatchCollection
+from typing import List, Union
+
+
+def create_hex_grid(nx: int = 4,
+                    ny: int = 5,
+                    min_diam: float = 1.,
+                    n: int = 0,
+                    align_to_origin: bool = True,
+                    face_color: Union[List[float], str] = None,
+                    edge_color: Union[List[float], str] = None,
+                    plotting_gap: float = 0.,
+                    crop_circ: float = 0.,
+                    do_plot: bool = False,
+                    rotate_deg: float = 0.,
+                    keep_x_sym: bool = True,
+                    h_ax: plt.Axes = None,
+                    line_width: float = 0.2,
+                    background_color: Union[List[float], str] = None) -> (np.ndarray, plt.Axes):
+    """
+    Creates and prints hexagonal lattices.
+    :param nx: Number of horizontal hexagons in rectangular grid, [nx * ny]
+    :param ny: Number of vertical hexagons in rectangular grid, [nx * ny]
+    :param min_diam: Minimal diameter of each hexagon.
+    :param n: Alternative way to create rectangular grid. The final grid might have less hexagons
+    :param align_to_origin: Shift the grid s.t. the central tile will center at the origin
+    :param face_color: Provide RGB triplet, valid abbreviation (e.g. 'k') or RGB+alpha
+    :param edge_color: Provide RGB triplet, valid abbreviation (e.g. 'k') or RGB+alpha
+    :param plotting_gap: Gap between the edges of adjacent tiles, in fraction of min_diam
+    :param crop_circ: Disabled if 0. If >0 a circle of central tiles will be kept, with radius r=crop_circ
+    :param do_plot: Add the hexagon to an axes. If h_ax not provided a new figure will be opened.
+    :param rotate_deg: Rotate the grid around the center of the central tile, by rotate_deg degrees
+    :param keep_x_sym: NOT YET IMPLEMENTED
+    :param h_ax: Handle to axes. If provided the grid will be added to it, if not a new figure will be opened.
+    :param line_width: The width of the hexagon lines
+    :param background_color: The color of the axis background
+    :return:
+    """
+
+    args_are_ok = check_inputs(nx, ny, min_diam, n, align_to_origin, face_color, edge_color, plotting_gap, crop_circ,
+                               do_plot, rotate_deg, keep_x_sym, background_color)
+    if not args_are_ok:
+        print('Aborting hexagonal grid creation...')
+        exit()
+    coord_x, coord_y = make_grid(nx, ny, min_diam, n, crop_circ, rotate_deg, align_to_origin)
+
+    if do_plot:
+        h_ax = plot_single_lattice(coord_x, coord_y, face_color, edge_color, min_diam, plotting_gap, rotate_deg, h_ax,
+                                   background_color, line_width)
+
+    return np.hstack([coord_x, coord_y]), h_ax
+
+
+def check_inputs(nx, ny, min_diam, n, align_to_origin, face_color, edge_color, plotting_gap, crop_circ, do_plot,
+                 rotate_deg, keep_x_sym, background_color):
+    """
+    Validate input types, ranges and co-compatibility
+    :return: bool - Assertion verdict
+    """
+    args_are_valid = True
+    if (not isinstance(nx, (int, float))) or (not isinstance(ny, (int, float))) or (not isinstance(n, (int, float))) \
+            or (nx < 0) or (nx < 0) or (nx < 0):
+        print('Argument error in hex_grid: nx, ny and n are expected to be integers')
+        args_are_valid = False
+
+    if (not isinstance(min_diam, (float, int))) or (not isinstance(crop_circ, (float, int))) or (min_diam < 0) or \
+            (crop_circ < 0):
+        print('Argument error in hex_grid: min_diam and crop_circ are expected to be floats')
+        args_are_valid = False
+
+    if (not isinstance(align_to_origin, bool)) or (not isinstance(do_plot, bool)):
+        print('Argument error in hex_grid: align_to_origin and do_plot are expected to be booleans')
+        args_are_valid = False
+
+    VALID_C_ABBR = {'b', 'g', 'r', 'c', 'm', 'y', 'k', 'w'}
+    if (isinstance(face_color, str) and (not face_color in VALID_C_ABBR)) or \
+            (isinstance(background_color, str) and (not background_color in VALID_C_ABBR)) or \
+            (isinstance(edge_color, str) and (not edge_color in VALID_C_ABBR)):
+        print('Argument error in hex_grid: edge_color and face_color are expected to valid color abbrs, e.g. `k`')
+        args_are_valid = False
+
+    if (isinstance(face_color, List) and ((len(face_color) not in (3, 4)) or
+                                          (True in ((x < 0) or (x > 1) for x in face_color)))) or \
+            (isinstance(background_color, List) and ((len(background_color) not in (3, 4)) or
+                                               (True in ((x < 0) or (x > 1) for x in face_color)))) or \
+            (isinstance(edge_color, List) and ((len(edge_color) not in (3, 4)) or
+                                          (True in ((x < 0) or (x > 1) for x in edge_color)))):
+        print('Argument error in hex_grid: edge_color and face_color are expected to be valid RGB color triplets or '
+              'color abbreviations, e.g. [0.1 0.3 0.95] or `k`')
+        args_are_valid = False
+
+    if (not isinstance(plotting_gap, float)) or (plotting_gap < 0) or (plotting_gap >= 1):
+        print('Argument error in hex_grid: plotting_gap is expected to be a float in range [0, 1)')
+        args_are_valid = False
+
+    if not isinstance(rotate_deg, (float, int)):
+        print('Argument error in hex_grid: float is expected to be float or integer')
+        args_are_valid = False
+
+    if (n == 0) and ((nx == 0) or (ny == 0)):
+        print('Argument error in hex_grid: Expected either n>0 or both [nx.ny]>0')
+        args_are_valid = False
+
+    if (isinstance(min_diam, (float, int)) and isinstance(crop_circ, (float, int))) and \
+            (not np.isclose(crop_circ, 0)) and (crop_circ < min_diam):
+        print('Argument error in hex_grid: Cropping radius is expected to be bigger than a single hexagon diameter')
+        args_are_valid = False
+
+    if not isinstance(keep_x_sym, bool):
+        print('Argument error in hex_grid: keep_x_sym is expected to be boolean')
+        args_are_valid = False
+
+    return args_are_valid
+
+
+def plot_single_lattice(coord_x, coord_y, face_color, edge_color, min_diam, plotting_gap, rotate_deg, h_ax=None,
+                        background_color=None, line_width=0.2):
+    """
+    Adds a single lattice to the axes canvas. Multiple calls can be made to overlay few lattices.
+    :return:
+    """
+    if face_color is None:
+        face_color = (1, 1, 1, 0)  # Make the face transparent
+    if edge_color is None:
+        edge_color = 'k'
+
+    if h_ax is None:
+        h_fig = plt.figure(figsize=(5, 5))
+        h_ax = h_fig.add_axes([0.05, 0.05, 0.9, 0.9])
+
+    if background_color is not None:
+        h_ax.set_facecolor(background_color)
+        
+    radius = radius=min_diam / np.sqrt(3) * (1 - plotting_gap)
+    orientation = np.deg2rad(-rotate_deg)
+    
+    patches = []
+    for curr_x, curr_y in zip(coord_x, coord_y):
+        polygon = mpatches.RegularPolygon((curr_x, curr_y), numVertices=6,
+                                          radius=radius,
+                                          orientation=orientation)
+        patches.append(polygon)
+    collection = PatchCollection(patches, edgecolor=edge_color, facecolor=face_color, linewidths=line_width)
+    h_ax.add_collection(collection)
+
+    h_ax.set_aspect('equal')
+    h_ax.axis([coord_x.min() - 2 * min_diam, coord_x.max() + 2 * min_diam, coord_y.min() - 2 * min_diam,
+               coord_y.max() + 2 * min_diam])
+    # plt.plot(0, 0, 'r.', markersize=5)   # Add red point at the origin
+    return h_ax
+
+
+def make_grid(nx, ny, min_diam, n, crop_circ, rotate_deg, align_to_origin) -> (np.ndarray, np.ndarray):
+    """
+    Computes the coordinates of the hexagon centers, given the size rotation and layout specifications
+    :return:
+    """
+    ratio = np.sqrt(3) / 2
+    if n > 0:  # n variable overwrites (nx, ny) in case all three were provided
+        ny = int(np.sqrt(n / ratio))
+        nx = n // ny
+
+    coord_x, coord_y = np.meshgrid(np.arange(nx), np.arange(ny), sparse=False, indexing='xy')
+    coord_y = coord_y * ratio
+    coord_x = coord_x.astype('float')
+    coord_x[1::2, :] += 0.5
+    coord_x = coord_x.reshape(-1, 1)
+    coord_y = coord_y.reshape(-1, 1)
+
+    coord_x *= min_diam  # Scale to requested size
+    coord_y = coord_y.astype('float') * min_diam
+
+    mid_x = (np.ceil(nx / 2) - 1) + 0.5 * (np.ceil(ny/2) % 2 == 0)  # Pick center of some hexagon as origin for rotation or crop...
+    mid_y = (np.ceil(ny / 2) - 1) * ratio  # np.median() averages center 2 values for even arrays :\
+    mid_x *= min_diam
+    mid_y *= min_diam
+
+    # mid_x = (nx // 2 - (nx % 2 == 1)) * min_diam + 0.5 * (ny % 2 == 1)
+    # mid_y = (ny // 2 - (ny % 2)) * min_diam * ratio
+
+    if crop_circ > 0:
+        rad = ((coord_x - mid_x)**2 + (coord_y - mid_y)**2)**0.5
+        coord_x = coord_x[rad.flatten() <= crop_circ, :]
+        coord_y = coord_y[rad.flatten() <= crop_circ, :]
+
+    if not np.isclose(rotate_deg, 0):  # Check if rotation is not 0, with tolerance due to float format
+        # Clockwise, 2D rotation matrix
+        RotMatrix = np.array([[np.cos(np.deg2rad(rotate_deg)), np.sin(np.deg2rad(rotate_deg))],
+                              [-np.sin(np.deg2rad(rotate_deg)), np.cos(np.deg2rad(rotate_deg))]])
+        rot_locs = np.hstack((coord_x - mid_x, coord_y - mid_y)) @ RotMatrix.T
+        # rot_locs = np.hstack((coord_x - mid_x, coord_y - mid_y))
+        coord_x, coord_y = np.hsplit(rot_locs + np.array([mid_x, mid_y]), 2)
+
+    if align_to_origin:
+        coord_x -= mid_x
+        coord_y -= mid_y
+
+    return coord_x, coord_y
+
+
+def plot_single_lattice_custom_colors(coord_x, coord_y, face_color, edge_color, min_diam, plotting_gap, rotate_deg,
+                                      line_width=1., h_ax=None, background_color=None):
+    """
+    Plot hexagonal lattice where every hexagon is colored by an individual color.
+    All inputs are similar to the plot_single_lattice() except:
+    :param line_width:
+    :param h_ax:
+    :param rotate_deg:
+    :param plotting_gap:
+    :param min_diam:
+    :param coord_y:
+    :param coord_x:
+    :param face_color: numpy array, Nx3 or Nx4 - Color list of length |coord_x| for each hexagon face.
+                                                 Each row is a RGB or RGBA values, e.g. [0.3 0.3 0.3 1]
+    :param edge_color: numpy array, Nx3 or Nx4 - Color list of length |coord_x| for each hexagon edge.
+                                                 Each row is a RGB or RGBA values, e.g. [0.3 0.3 0.3 1]
+    :return:
+    """
+
+    if h_ax is None:
+        h_fig = plt.figure(figsize=(5, 5))
+        h_ax = h_fig.add_axes([0.05, 0.05, 0.9, 0.9])
+        if background_color is not None:
+            h_ax.set_facecolor(background_color)
+
+    radius = min_diam / np.sqrt(3) * (1 - plotting_gap)
+    orientation = np.deg2rad(-rotate_deg)
+
+    polygons = []
+
+    for curr_x, curr_y in zip(coord_x, coord_y):
+        polygon = mpatches.RegularPolygon((curr_x, curr_y), numVertices=6,
+                                          radius=radius,
+                                          orientation=orientation)
+        polygons.append(polygon)
+
+    h_ax.add_artist(
+        PatchCollection(
+            patches=polygons,
+            facecolors=face_color,
+            edgecolors=edge_color,
+            linewidth=line_width))
+
+    h_ax.set_aspect('equal')
+    h_ax.axis([coord_x.min() - 2 * min_diam, coord_x.max() + 2 * min_diam, coord_y.min() - 2 * min_diam,
+               coord_y.max() + 2 * min_diam])
+    # plt.plot(0, 0, 'r.', markersize=5)   # Add red point at the origin
+    return h_ax
+
+
+def sample_colors_from_image_by_grid(image_path: str, x_coords, y_coords):
+    """
+    Sample colors of a set of points from an image.
+    :param image_path: str - Path to an image file (.png, .jpg)
+    :param x_coords: list - x coordinates of the hexagons. The range doesn't matter since it is rescaled to fit the image
+    :param y_coords: list - y -----//------
+    :return:
+    """
+    from matplotlib.image import imread
+    img = imread(image_path) / 255
+    img = np.flip(img, 0)  # Flip Y axis. Images = matrices where pixel [0, 0] is in the upper left corner
+
+    abs_min = np.min([x_coords.T, y_coords.T])
+    abs_max = np.max([x_coords.T, y_coords.T]) + 0.001
+    minor_image_dim = min(img.shape[0], img.shape[1])
+    p_x = np.floor((x_coords - abs_min) / (abs_max - abs_min) * minor_image_dim)
+    p_y = np.floor((y_coords - abs_min) / (abs_max - abs_min) * minor_image_dim)
+
+    colors = img[p_y.astype('int'), p_x.astype('int'), :]
+    return colors
+
+
+def main():
+    plt.ion()
+
+    # (1) === Create single hexagonal 5*5 lattice and plot it. Extract the [x,y] locations of the tile centers
+    hex_centers, h_ax = create_hex_grid(nx=5, ny=5, do_plot=True)
+    tile_centers_x = hex_centers[:, 0]
+    tile_centers_y = hex_centers[:, 1]
+    # plt.show(block=True)   % The 'show' call should be done explicitly
+
+    # (2) === Create single hexagonal lattice, 5*5, rotated around central tile ====
+    hex_centers, _ = create_hex_grid(nx=5,
+                                     ny=5,
+                                     plotting_gap=0.05,
+                                     min_diam=1,
+                                     rotate_deg=5,
+                                     face_color=[0.9, 0.1, 0.1, 0.05],
+                                     do_plot=True)
+
+    # (3) === Plot Moire pattern with two round hexagonal grids ====
+    hex_grid1, h_ax = create_hex_grid(nx=50,
+                                      ny=50,
+                                      rotate_deg=0,
+                                      min_diam=1,
+                                      crop_circ=20,
+                                      do_plot=True)
+    create_hex_grid(nx=50,
+                    ny=50,
+                    min_diam=1,
+                    rotate_deg=5,
+                    crop_circ=20,
+                    do_plot=True,
+                    h_ax=h_ax)
+
+    # (4) === Create 5 layers of grids of various sizes ====
+    face_c = [0.7, 0.7, 0.7, 0.1]
+    _, h_ax = create_hex_grid(nx=5,
+                              ny=4,
+                              plotting_gap=0.2,
+                              face_color=face_c,
+                              min_diam=1,
+                              do_plot=True)
+    create_hex_grid(nx=4,
+                    ny=3,
+                    min_diam=1,
+                    plotting_gap=0.3,
+                    face_color=face_c,
+                    do_plot=True,
+                    h_ax=h_ax)
+    create_hex_grid(nx=2,
+                    ny=2,
+                    plotting_gap=0.4,
+                    face_color=face_c,
+                    do_plot=True,
+                    h_ax=h_ax)
+    create_hex_grid(nx=1,
+                    ny=1,
+                    plotting_gap=0.5,
+                    face_color=face_c,
+                    do_plot=True,
+                    h_ax=h_ax)
+    create_hex_grid(nx=10,
+                    ny=10,
+                    edge_color=[0.9, 0.9, 0.9],
+                    line_width=0.3,
+                    do_plot=True,
+                    h_ax=h_ax)
+
+    # (5) === Color hexagons with custom colors ===
+    image_path = r'example_image.jpg'  # taken from https://en.wikipedia.org/wiki/Apple#/media/File:Red_Apple.jpg
+    hex_centers, h_ax = create_hex_grid(nx=50, ny=50, do_plot=False)
+    colors = sample_colors_from_image_by_grid(image_path, hex_centers[:, 0], hex_centers[:, 1])
+
+    fig, axs = plt.subplots(2, 2)
+    axs[0, 0].imshow(plt.imread(image_path))
+    plot_single_lattice_custom_colors(hex_centers[:, 0], hex_centers[:, 1],
+                                      face_color=colors,
+                                      edge_color=colors,
+                                      min_diam=1.,
+                                      plotting_gap=0,
+                                      rotate_deg=0,
+                                      line_width=0.3,
+                                      h_ax=axs[0, 1])
+    plot_single_lattice_custom_colors(hex_centers[:, 0], hex_centers[:, 1],
+                                      face_color=colors,
+                                      edge_color=colors*0,
+                                      min_diam=1.,
+                                      plotting_gap=0,
+                                      rotate_deg=0,
+                                      line_width=1.,
+                                      h_ax=axs[1, 0])
+    plot_single_lattice_custom_colors(hex_centers[:, 0], hex_centers[:, 1],
+                                      face_color=colors,
+                                      edge_color=colors*0,
+                                      min_diam=1.,
+                                      plotting_gap=0,
+                                      rotate_deg=0,
+                                      line_width=0.1,
+                                      h_ax=axs[1, 1])
+
+    plt.show(block=True)
+
+
+if __name__ == "__main__":
+    # Main function includes multiple examples
+    main()
```

### Comparing `hexalattice-1.2.2/hexalattice.egg-info/PKG-INFO` & `hexalattice-1.3.0/README.md`

 * *Files 26% similar despite different names*

```diff
@@ -1,129 +1,117 @@
-Metadata-Version: 2.1
-Name: hexalattice
-Version: 1.2.2
-Summary: Compute and plot hexagonal grids
-Home-page: https://github.com/alexkaz2/hexalattice/wiki
-Author: Alex Kazakov
-Author-email: alex.kazakov@mail.huji.ac.il
-License: MIT
-Classifier: License :: OSI Approved :: MIT License
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.7
-Requires-Python: >=3.5
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
-# hexalattice
-
-Generate and plot hexagonal lattices in 2D, with fine control over spacing between hexagons, arbitrary rotation of the grid around central tile, etc.
-The module computes and returns the center point for each of the tiles in the lattice. 
-
-<p align="center">
-  <img width="1000" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/collage.png">
-</p>
-
-
-
-## Installation
-
-[![PyPI version](https://badge.fury.io/py/hexalattice.svg)](https://badge.fury.io/py/hexalattice)
-![python version](https://upload.wikimedia.org/wikipedia/commons/f/fc/Blue_Python_3.7_Shield_Badge.svg)
-![conda](https://anaconda.org/conda-forge/hexalattice/badges/installer/conda.svg)
-![downloads_anaconda](https://anaconda.org/conda-forge/hexalattice/badges/downloads.svg)
-![license](https://anaconda.org/conda-forge/hexalattice/badges/license.svg)
-
-```sh
-# Using pip
-pip install hexalattice
-```
-```sh
-# Using conda
-conda install -c conda-forge hexalattice
-```
-
-
-
-## Usage example
-
-Create and plot 5x5 lattice of hexagons (as in first image):
-```sh
-from hexalattice.hexalattice import *
-hex_centers, _ = create_hex_grid(nx=5,
-                                 ny=5,
-                                 do_plot=True)
-                                 
-plt.show()    # import matplotlib.pyplot as plt
-```
-
-Get central points of the hexagons:
-```sh
-tile_centers_x = hex_centers[:, 0]
-tile_centers_y = hex_centers[:, 1]
-```
-
-Plot one grid over the other, second with spacing around the hexagons:
-```sh
-_, h_ax = create_hex_grid(nx=5, 
-                          ny=7,
-                          do_plot=True,
-                          edge_color=(0.85, 0.85, 0.85))
-                                    
-create_hex_grid(nx=5,
-                ny=7,
-                do_plot=True,
-                edge_color=(0.25,0.25, 0.25),
-                h_ax=h_ax,
-                plotting_gap=0.3)
-plt.show()
-```
-
-<p align="center">
-  <img width="600" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice5.png">
-</p>
-
-Create MoirÃ© pattern from two circularly cropped hexagrids:
-```sh
-hex_grid1, h_ax = create_hex_grid(nx=50,
-                                  ny=50,
-                                  rotate_deg=0,
-                                  min_diam=1,
-                                  crop_circ=20,
-                                  do_plot=True)
-    create_hex_grid(nx=50,
-                    ny=50,
-                    min_diam=1,
-                    rotate_deg=5,
-                    crop_circ=20,
-                    do_plot=True,
-                    h_ax=h_ax)
-```
-
-<p align="center">
-  <img width="600" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice2.png">
-</p>
-
-_For API and additional examples see the wiki [hexalattice API](https://github.com/alexkaz2/hexalattice/wiki) and [assigning individual colors to hexagons](https://github.com/alexkaz2/hexalattice/wiki/Assigning-individual-colors-to-hexagons)._
-
-<p align="center">
-  <img width="450" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/hexalattice_5x5_nogaps.png" hspace="10"/>
-</p> 
-<p align="center">
-  <img width="450" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice4.png" hspace="10"/>
-</p>
-<p align="center">
-  <img width="450" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice7.png" hspace="10"/>
-</p>
-
-## Release History
-
-* v1.0.0 - First version
-* v1.1.0 - Added the option to assign different colors to hexagons
-* v1.2.0 - Added control over the outer line width of the hexagons
-
-## About & License
-
-Alex Kazakov â€“ [@bio_vs_silico](https://twitter.com/bio_vs_silico) â€“ alex.kazakov@mail.huji.ac.il
-
-Distributed under the MIT license. See ``LICENSE`` for more information.
-
-[https://github.com/alexkaz2/hexalattice](https://github.com/alexkaz2/)
+# hexalattice
+
+Generate and plot hexagonal lattices in 2D, with fine control over spacing between hexagons, arbitrary rotation of the grid around central tile, etc.
+The module computes and returns the center point for each of the tiles in the lattice. 
+
+<p align="center">
+  <img width="1000" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/collage.png">
+</p>
+
+
+
+## Installation
+
+[![PyPI version](https://badge.fury.io/py/hexalattice.svg)](https://badge.fury.io/py/hexalattice)
+![conda](https://anaconda.org/conda-forge/hexalattice/badges/version.svg)
+![python version](https://upload.wikimedia.org/wikipedia/commons/f/fc/Blue_Python_3.7_Shield_Badge.svg)
+![downloads_anaconda](https://anaconda.org/conda-forge/hexalattice/badges/downloads.svg)
+![license](https://anaconda.org/conda-forge/hexalattice/badges/license.svg)
+![last updated](https://anaconda.org/conda-forge/hexalattice/badges/latest_release_relative_date.svg)
+
+```sh
+# Using pip
+pip install hexalattice
+```
+```sh
+# Using conda
+conda install -c conda-forge hexalattice
+```
+
+
+
+## Usage example
+
+Create and plot 5x5 lattice of hexagons (as in first image):
+```sh
+from hexalattice.hexalattice import *
+hex_centers, _ = create_hex_grid(nx=5,
+                                 ny=5,
+                                 do_plot=True)
+                                 
+plt.show()    # import matplotlib.pyplot as plt
+```
+
+Get central points of the hexagons:
+```sh
+tile_centers_x = hex_centers[:, 0]
+tile_centers_y = hex_centers[:, 1]
+```
+
+Plot one grid over the other, second with spacing around the hexagons:
+```sh
+_, h_ax = create_hex_grid(nx=5, 
+                          ny=7,
+                          do_plot=True,
+                          edge_color=(0.85, 0.85, 0.85))
+                                    
+create_hex_grid(nx=5,
+                ny=7,
+                do_plot=True,
+                edge_color=(0.25,0.25, 0.25),
+                h_ax=h_ax,
+                plotting_gap=0.3)
+plt.show()
+```
+
+<p align="center">
+  <img width="600" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice5.png">
+</p>
+
+Create Moiré pattern from two circularly cropped hexagrids:
+```sh
+hex_grid1, h_ax = create_hex_grid(nx=50,
+                                  ny=50,
+                                  rotate_deg=0,
+                                  min_diam=1,
+                                  crop_circ=20,
+                                  do_plot=True)
+    create_hex_grid(nx=50,
+                    ny=50,
+                    min_diam=1,
+                    rotate_deg=5,
+                    crop_circ=20,
+                    do_plot=True,
+                    h_ax=h_ax)
+```
+
+<p align="center">
+  <img width="600" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice2.png">
+</p>
+
+_For API and additional examples see the wiki [hexalattice API](https://github.com/alexkaz2/hexalattice/wiki) and [assigning individual colors to hexagons](https://github.com/alexkaz2/hexalattice/wiki/Assigning-individual-colors-to-hexagons)._
+
+<p align="center">
+  <img width="450" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/hexalattice_5x5_nogaps.png" hspace="10"/>
+</p> 
+<p align="center">
+  <img width="450" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice4.png" hspace="10"/>
+</p>
+<p align="center">
+  <img width="450" src="https://github.com/alexkaz2/hexalattice/blob/master/example_hexagonal_lattices/lattice7.png" hspace="10"/>
+</p>
+
+## Release History
+
+* v1.0.0 - First version
+* v1.1.0 - Added the option to assign different colors to hexagons
+* v1.2.0 - Added control over the outer line width of the hexagons
+* v1.2.2 - Added control over the axis background color
+* v1.3.0 - Reduced runtime by 50%
+
+## About & License
+
+Alex Kazakov – [@bio_vs_silico](https://twitter.com/bio_vs_silico) – alex.kazakov@mail.huji.ac.il
+
+Distributed under the MIT license. See ``LICENSE`` for more information.
+
+[https://github.com/alexkaz2/hexalattice](https://github.com/alexkaz2/)
```

### Comparing `hexalattice-1.2.2/setup.py` & `hexalattice-1.3.0/setup.py`

 * *Files 21% similar despite different names*

```diff
@@ -1,37 +1,37 @@
-import setuptools
-import pathlib
-
-# The directory containing this file
-HERE = pathlib.Path(__file__).parent
-
-# The text of the README file
-with open("README.md", "r") as fh:
-    long_description = fh.read()
-
-# This call to setup() does all the work
-setuptools.setup(
-    name="hexalattice",
-    version="1.2.2",
-    description="Compute and plot hexagonal grids",
-    long_description=long_description,
-    long_description_content_type="text/markdown",
-    url="https://github.com/alexkaz2/hexalattice/wiki",
-    author="Alex Kazakov",
-    author_email="alex.kazakov@mail.huji.ac.il",
-    license="MIT",
-    classifiers=[
-        "License :: OSI Approved :: MIT License",
-        "Programming Language :: Python :: 3",
-        "Programming Language :: Python :: 3.7",
-    ],
-    packages=setuptools.find_packages(),
-    python_requires='>=3.5',
-    install_requires=[
-        "numpy",
-        "matplotlib >= 3.1",
-    ],
-    setup_requires=[
-        "numpy",
-        "matplotlib >= 3.1",
-    ],
+import setuptools
+import pathlib
+
+# The directory containing this file
+HERE = pathlib.Path(__file__).parent
+
+# The text of the README file
+with open("README.md", "r") as fh:
+    long_description = fh.read()
+
+# This call to setup() does all the work
+setuptools.setup(
+    name="hexalattice",
+    version="1.3.0",
+    description="Compute and plot hexagonal grids",
+    long_description=long_description,
+    long_description_content_type="text/markdown",
+    url="https://github.com/alexkaz2/hexalattice/wiki",
+    author="Alex Kazakov",
+    author_email="alex.kazakov@mail.huji.ac.il",
+    license="MIT",
+    classifiers=[
+        "License :: OSI Approved :: MIT License",
+        "Programming Language :: Python :: 3",
+        "Programming Language :: Python :: 3.7",
+    ],
+    packages=setuptools.find_packages(),
+    python_requires='>=3.5',
+    install_requires=[
+        "numpy",
+        "matplotlib >= 3.1",
+    ],
+    setup_requires=[
+        "numpy",
+        "matplotlib >= 3.1",
+    ],
 )
```


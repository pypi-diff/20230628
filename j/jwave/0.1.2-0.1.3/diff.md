# Comparing `tmp/jwave-0.1.2.tar.gz` & `tmp/jwave-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jwave-0.1.2.tar", max compression
+gzip compressed data, was "jwave-0.1.3.tar", max compression
```

## Comparing `jwave-0.1.2.tar` & `jwave-0.1.3.tar`

### file list

```diff
@@ -1,20 +1,20 @@
--rwxr-xr-x   0        0        0     7652 2023-06-22 15:50:58.991539 jwave-0.1.2/LICENSE
--rwxr-xr-x   0        0        0     4467 2023-06-22 15:50:58.991539 jwave-0.1.2/README.md
--rwxr-xr-x   0        0        0       19 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/__about__.py
--rwxr-xr-x   0        0        0      885 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/__init__.py
--rw-r--r--   0        0        0      768 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/acoustics/__init__.py
--rw-r--r--   0        0        0     1951 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/acoustics/conversion.py
--rw-r--r--   0        0        0    10119 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/acoustics/operators.py
--rw-r--r--   0        0        0     4561 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/acoustics/pml.py
--rwxr-xr-x   0        0        0     1186 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/acoustics/spectral.py
--rw-r--r--   0        0        0    20569 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/acoustics/time_harmonic.py
--rwxr-xr-x   0        0        0    19105 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/acoustics/time_varying.py
--rw-r--r--   0        0        0       85 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/extras/__init__.py
--rw-r--r--   0        0        0     3029 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/extras/export.py
--rwxr-xr-x   0        0        0    15953 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/geometry.py
--rwxr-xr-x   0        0        0     1423 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/phantoms.py
--rwxr-xr-x   0        0        0     8798 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/signal_processing.py
--rw-r--r--   0        0        0      835 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/transformations.py
--rwxr-xr-x   0        0        0     6265 2023-06-22 15:50:59.027540 jwave-0.1.2/jwave/utils.py
--rw-r--r--   0        0        0     2944 2023-06-22 15:50:59.027540 jwave-0.1.2/pyproject.toml
--rw-r--r--   0        0        0     6246 1970-01-01 00:00:00.000000 jwave-0.1.2/PKG-INFO
+-rwxr-xr-x   0        0        0     7652 2023-06-28 09:22:58.524655 jwave-0.1.3/LICENSE
+-rwxr-xr-x   0        0        0     5131 2023-06-28 09:22:58.524655 jwave-0.1.3/README.md
+-rwxr-xr-x   0        0        0       19 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/__about__.py
+-rwxr-xr-x   0        0        0      885 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/__init__.py
+-rw-r--r--   0        0        0      768 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/acoustics/__init__.py
+-rw-r--r--   0        0        0     1951 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/acoustics/conversion.py
+-rw-r--r--   0        0        0    10119 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/acoustics/operators.py
+-rw-r--r--   0        0        0     4561 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/acoustics/pml.py
+-rwxr-xr-x   0        0        0     1186 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/acoustics/spectral.py
+-rw-r--r--   0        0        0    20569 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/acoustics/time_harmonic.py
+-rwxr-xr-x   0        0        0    19105 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/acoustics/time_varying.py
+-rw-r--r--   0        0        0       85 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/extras/__init__.py
+-rw-r--r--   0        0        0     3029 2023-06-28 09:22:58.560656 jwave-0.1.3/jwave/extras/export.py
+-rwxr-xr-x   0        0        0    19433 2023-06-28 09:22:58.564656 jwave-0.1.3/jwave/geometry.py
+-rwxr-xr-x   0        0        0     1423 2023-06-28 09:22:58.564656 jwave-0.1.3/jwave/phantoms.py
+-rwxr-xr-x   0        0        0     8798 2023-06-28 09:22:58.564656 jwave-0.1.3/jwave/signal_processing.py
+-rw-r--r--   0        0        0      835 2023-06-28 09:22:58.564656 jwave-0.1.3/jwave/transformations.py
+-rwxr-xr-x   0        0        0     6265 2023-06-28 09:22:58.564656 jwave-0.1.3/jwave/utils.py
+-rw-r--r--   0        0        0     2944 2023-06-28 09:22:58.564656 jwave-0.1.3/pyproject.toml
+-rw-r--r--   0        0        0     6910 1970-01-01 00:00:00.000000 jwave-0.1.3/PKG-INFO
```

### Comparing `jwave-0.1.2/LICENSE` & `jwave-0.1.3/LICENSE`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/README.md` & `jwave-0.1.3/README.md`

 * *Files 15% similar despite different names*

```diff
@@ -78,14 +78,28 @@
 
 [![Support](https://dcbadge.vercel.app/api/server/VtUb4fFznt?style=flat)](https://discord.gg/VtUb4fFznt)
 
 If you encounter any problems with the code or wish to propose new features, please feel free to open an issue. If you need general guidance, wish to discuss something, or just want to say hi, don't hesitate to leave a message in our [Discord channel](https://discord.gg/VtUb4fFznt).
 
 <br/>
 
+## Contributing
+
+Contributions are absolutely welcome! Most contributions start with an issue. Please don't hesitate to create issues in which you ask for features, give feedback on performances, or simply want to reach out.
+
+To make a pull request, please look at the detailed [Contributing guide](CONTRIBUTING.md) for how to do it, but fundamentally keep in mind the following main guidelines:
+
+- If you add a new feature or fix a bug:
+  - Make sure it is covered by tests
+  - Add a line in the changelog using `kacl-cli`
+- If you changed something in the documentation, make sure that the documentation site can be correctly build using `mkdocs serve`
+
+<br/>
+
+
 ## Citation
 
 [![arXiv](https://img.shields.io/badge/arXiv-2207.01499-b31b1b.svg?style=flat)](https://arxiv.org/abs/2207.01499)
 
 If you use `jwave` for your research, please consider citing it as:
 
 ```bibtex
```

### Comparing `jwave-0.1.2/jwave/__init__.py` & `jwave-0.1.3/jwave/__init__.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/acoustics/__init__.py` & `jwave-0.1.3/jwave/acoustics/__init__.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/acoustics/conversion.py` & `jwave-0.1.3/jwave/acoustics/conversion.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/acoustics/operators.py` & `jwave-0.1.3/jwave/acoustics/operators.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/acoustics/pml.py` & `jwave-0.1.3/jwave/acoustics/pml.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/acoustics/spectral.py` & `jwave-0.1.3/jwave/acoustics/spectral.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/acoustics/time_harmonic.py` & `jwave-0.1.3/jwave/acoustics/time_harmonic.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/acoustics/time_varying.py` & `jwave-0.1.3/jwave/acoustics/time_varying.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/extras/export.py` & `jwave-0.1.3/jwave/extras/export.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/geometry.py` & `jwave-0.1.3/jwave/geometry.py`

 * *Files 14% similar despite different names*

```diff
@@ -12,14 +12,15 @@
 #
 # You should have received a copy of the GNU Lesser General Public
 # License along with j-Wave. If not, see <https://www.gnu.org/licenses/>.
 
 import math
 from dataclasses import dataclass
 from typing import List, Tuple, Union
+from numpy.typing import ArrayLike
 
 import numpy as np
 from jax import numpy as jnp
 from jax.tree_util import register_pytree_node_class
 from jaxdf import Field, FourierSeries, OnGrid
 from jaxdf.geometry import Domain
 from jaxdf.operators import dot_product, functional
@@ -31,15 +32,15 @@
 @register_pytree_node_class
 class Medium:
     r"""
     Medium structure
 
     Attributes:
       domain (Domain): domain of the medium
-      sound_speed (jnp.darray): speed of sound map, can be a scalar
+      sound_speed (jnp.ndarray): speed of sound map, can be a scalar
       density (jnp.ndarray): density map, can be a scalar
       attenuation (jnp.ndarray): attenuation map, can be a scalar
       pml_size (int): size of the PML layer in grid-points
 
     !!! example
 
       ```python
@@ -144,16 +145,16 @@
 class MediumType(Medium):
     """A type for Medium objects that depends on the discretization of its components"""
 
 
 @type_of.dispatch
 def type_of(m: Medium):
     return MediumType[type(m.sound_speed),
-                      type(m.density),
-                      type(m.attenuation)]
+    type(m.density),
+    type(m.attenuation)]
 
 
 MediumAllScalars = MediumType[object, object, object]
 """A type for Medium objects that have all scalar components"""
 
 MediumFourierSeries = Union[
     MediumType[FourierSeries, object, object],
@@ -183,19 +184,19 @@
         Default is 128.
 
     Returns:
     points (list): A list of tuples representing the (x, y, z)
         coordinates of the points on the sphere.
     """
     points = []
-    phi = math.pi * (3.0 - math.sqrt(5.0))    # golden angle in radians
+    phi = math.pi * (3.0 - math.sqrt(5.0))  # golden angle in radians
     for i in range(samples):
-        y = 1 - (i / float(samples - 1)) * 2    # y goes from 1 to -1
-        radius = math.sqrt(1 - y * y)    # radius at y
-        theta = phi * i    # golden angle increment
+        y = 1 - (i / float(samples - 1)) * 2  # y goes from 1 to -1
+        radius = math.sqrt(1 - y * y)  # radius at y
+        theta = phi * i  # golden angle increment
         x = math.cos(theta) * radius
         z = math.sin(theta) * radius
         points.append((x, y, z))
     return points
 
 
 def _fibonacci_sphere(
@@ -224,23 +225,23 @@
     if cast_int:
         points = points.astype(int)
     return points[:, 0], points[:, 1], points[:, 2]
 
 
 def _circ_mask(N, radius, centre):
     x, y = np.mgrid[0:N[0], 0:N[1]]
-    dist_from_centre = np.sqrt((x - centre[0])**2 + (y - centre[1])**2)
+    dist_from_centre = np.sqrt((x - centre[0]) ** 2 + (y - centre[1]) ** 2)
     mask = (dist_from_centre < radius).astype(int)
     return mask
 
 
 def _sphere_mask(N, radius, centre):
     x, y, z = np.mgrid[0:N[0], 0:N[1], 0:N[2]]
-    dist_from_centre = np.sqrt((x - centre[0])**2 + (y - centre[1])**2 +
-                               (z - centre[2])**2)
+    dist_from_centre = np.sqrt((x - centre[0]) ** 2 + (y - centre[1]) ** 2 +
+                               (z - centre[2]) ** 2)
     mask = (dist_from_centre < radius).astype(int)
     return mask
 
 
 @register_pytree_node_class
 class Sources:
     r"""Sources structure
@@ -323,15 +324,15 @@
         self.mask = mask
         self.signal = signal
         self.dt = dt
         self.domain = domain
 
     def tree_flatten(self):
         children = (self.mask, self.signal, self.dt)
-        aux = (self.domain, )
+        aux = (self.domain,)
         return (children, aux)
 
     @classmethod
     def tree_unflatten(cls, aux, children):
         mask, signal, dt = children
         domain = aux[0]
         a = cls(mask, signal, dt, domain)
@@ -426,15 +427,15 @@
     positions: Tuple[tuple]
 
     def __init__(self, positions):
         self.positions = positions
 
     def tree_flatten(self):
         children = None
-        aux = (self.positions, )
+        aux = (self.positions,)
         return (children, aux)
 
     @classmethod
     def tree_unflatten(cls, aux, children):
         positions = aux[0]
         return cls(positions)
 
@@ -457,18 +458,123 @@
         Args:
           u (Field): The field to be sampled.
         """
         if len(self.positions) == 1:
             return p.on_grid[self.positions[0]]
         elif len(self.positions) == 2:
             return p.on_grid[self.positions[0],
-                             self.positions[1]]    # type: ignore
+            self.positions[1]]  # type: ignore
         elif len(self.positions) == 3:
             return p.on_grid[self.positions[0], self.positions[1],
-                             self.positions[2]]    # type: ignore
+            self.positions[2]]  # type: ignore
+        else:
+            raise ValueError(
+                "Sensors positions must be 1, 2 or 3 dimensional. Not {}".
+                format(len(self.positions)))
+
+
+def _bli_function(x0: jnp.ndarray, x: jnp.ndarray, n: int, include_imag: bool = False) -> jnp.ndarray:
+    """
+    The function used to compute the band limited interpolation function.
+
+    Args:
+        x0 (jnp.ndarray): Position of the sensors along the axis.
+        x (jnp.ndarray): Grid positions.
+        n (int): Size of the grid
+        include_imag (bool): Include the imaginary component?
+
+    Returns:
+    jnp.ndarray: The values of the function at the grid positions.
+    """
+    dx = jnp.where((x - x0[:, None]) == 0, 1, x - x0[:, None])  # https://github.com/google/jax/issues/1052
+    dx_nonzero = (x - x0[:, None]) != 0
+
+    if n % 2 == 0:
+        y = jnp.sin(jnp.pi * dx) / \
+            jnp.tan(jnp.pi * dx / n) / n
+        y -= jnp.sin(jnp.pi * x0[:, None]) * jnp.sin(jnp.pi * x) / n
+        if include_imag:
+            y += 1j * jnp.cos(jnp.pi * x0[:, None]) * jnp.sin(jnp.pi * x) / n
+    else:
+        y = jnp.sin(jnp.pi * dx) / \
+            jnp.sin(jnp.pi * dx / n) / n
+
+    # Deal with case of precisely on grid.
+    y = y * jnp.all(dx_nonzero, axis=1)[:, None] + (1 - dx_nonzero) * (~jnp.all(dx_nonzero, axis=1)[:, None])
+    return y
+
+
+@register_pytree_node_class
+class BLISensors:
+    """ Band-limited interpolant (off-grid) sensors.
+
+    Args:
+        positions (Tuple of List of float): Sensor positions.
+        n (Tuple of int): Grid size.
+
+    Attributes:
+        positions (Tuple[jnp.ndarray]): Sensor positions
+        n (Tuple[int]): Grid size.
+    """
+
+    positions: Tuple[jnp.ndarray]
+    n: Tuple[int]
+
+    def __init__(self, positions: Tuple[jnp.ndarray], n: Tuple[int]):
+        self.positions = positions
+        self.n = n
+
+        # Calculate the band-limited interpolant weights if not provided.
+        x = jnp.arange(n[0])[None]
+        self.bx = jnp.expand_dims(_bli_function(positions[0], x, n[0]),
+                                  axis=range(2, 2 + len(n)))
+
+        if len(n) > 1:
+            y = jnp.arange(n[1])[None]
+            self.by = jnp.expand_dims(_bli_function(positions[1], y, n[1]),
+                                      axis=range(2, 2 + len(n) - 1))
+        else:
+            self.by = None
+
+        if len(n) > 2:
+            z = jnp.arange(n[2])[None]
+            self.bz = jnp.expand_dims(_bli_function(positions[2], z, n[2]),
+                                      axis=range(2, 2 + len(n) - 2))
+        else:
+            self.bz = None
+
+    def tree_flatten(self):
+        children = self.positions,
+        aux = self.n,
+        return children, aux
+
+    @classmethod
+    def tree_unflatten(cls, aux, children):
+        return cls(*children, *aux)
+
+    def __call__(self, p: Field, u, v):
+        r"""Returns the values of the field p at the sensors positions.
+        Args:
+          p (Field): The field to be sampled.
+        """
+        if len(self.positions) == 1:
+            # 1D
+            pw = jnp.sum(p.on_grid[None] * self.bx, axis=1)
+            return pw
+        elif len(self.positions) == 2:
+            # 2D
+            pw = jnp.sum(p.on_grid[None] * self.bx, axis=1)
+            pw = jnp.sum(pw * self.by, axis=1)
+            return pw
+        elif len(self.positions) == 3:
+            # 3D
+            pw = jnp.sum(p.on_grid[None] * self.bx, axis=1)
+            pw = jnp.sum(pw * self.by, axis=1)
+            pw = jnp.sum(pw * self.bz, axis=1)
+            return pw
         else:
             raise ValueError(
                 "Sensors positions must be 1, 2 or 3 dimensional. Not {}".
                 format(len(self.positions)))
 
 
 @register_pytree_node_class
@@ -484,15 +590,15 @@
     t_end: float
 
     def __init__(self, dt, t_end):
         self.dt = dt
         self.t_end = t_end
 
     def tree_flatten(self):
-        children = (None, )
+        children = (None,)
         aux = (self.dt, self.t_end)
         return (children, aux)
 
     @classmethod
     def tree_unflatten(cls, aux, children):
         dt, t_end = aux
         return cls(dt, t_end)
@@ -518,11 +624,11 @@
               it is automatically calculated as the time required to travel
               from one corner of the domain to the opposite one.
         """
         dt = cfl * min(medium.domain.dx) / functional(medium.sound_speed)(
             np.max)
         if t_end is None:
             t_end = np.sqrt(
-                sum((x[-1] - x[0])**2
+                sum((x[-1] - x[0]) ** 2
                     for x in medium.domain.spatial_axis)) / functional(
-                        medium.sound_speed)(np.min)
+                medium.sound_speed)(np.min)
         return TimeAxis(dt=float(dt), t_end=float(t_end))
```

### Comparing `jwave-0.1.2/jwave/phantoms.py` & `jwave-0.1.3/jwave/phantoms.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/signal_processing.py` & `jwave-0.1.3/jwave/signal_processing.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/transformations.py` & `jwave-0.1.3/jwave/transformations.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/jwave/utils.py` & `jwave-0.1.3/jwave/utils.py`

 * *Files identical despite different names*

### Comparing `jwave-0.1.2/pyproject.toml` & `jwave-0.1.3/pyproject.toml`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "jwave"
-version = "0.1.2"
+version = "0.1.3"
 description = "Fast and differentiable acoustic simulations in JAX."
 authors = [
   "Antonio Stanziola <a.stanziola@ucl.ac.uk>",
   "Simon Arridge",
   "Ben T. Cox",
   "Bradley E. Treeby",
 ]
@@ -51,26 +51,26 @@
 
 [tool.poetry.dependencies]
 python = "^3.9"
 jaxdf = "^0.2.4"
 matplotlib = "^3.0.0"
 
 [tool.poetry.group.dev.dependencies]
-coverage = "7.0.4"
+coverage = "^7.2.7"
 pytest = "^7.2.0"
-pre-commit = "^2.20.0"
+pre-commit = "^3.3.3"
 pycln = "^2.1.5"
 isort = "^5.12.0"
 griffe = "^0.29.1"
 mkdocs-material = "^9.1.16"
 mkdocstrings = "^0.22.0"
 mkdocs-jupyter = "^0.24.1"
-mkdocs-macros-plugin = "^0.7.0"
+mkdocs-macros-plugin = "^1.0.1"
 mkdocs-mermaid2-plugin = "^0.6.0"
-mkdocstrings-python = "^0.8.0"
+mkdocstrings-python = "^1.1.2"
 python-kacl = "^0.4.6"
 pymdown-extensions = "^10.0.1"
 plumkdocs = "0.0.2"
 imageio = "^2.31.1"
 tqdm = "^4.65.0"
 imageio-ffmpeg = "^0.4.8"
```

### Comparing `jwave-0.1.2/PKG-INFO` & `jwave-0.1.3/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: jwave
-Version: 0.1.2
+Version: 0.1.3
 Summary: Fast and differentiable acoustic simulations in JAX.
 License: LGPL-3.0-only
 Keywords: jax,acoustics,simulation,ultrasound,differentiable-programming
 Author: Antonio Stanziola
 Author-email: a.stanziola@ucl.ac.uk
 Requires-Python: >=3.9,<4.0
 Classifier: Environment :: GPU
@@ -116,14 +116,28 @@
 
 [![Support](https://dcbadge.vercel.app/api/server/VtUb4fFznt?style=flat)](https://discord.gg/VtUb4fFznt)
 
 If you encounter any problems with the code or wish to propose new features, please feel free to open an issue. If you need general guidance, wish to discuss something, or just want to say hi, don't hesitate to leave a message in our [Discord channel](https://discord.gg/VtUb4fFznt).
 
 <br/>
 
+## Contributing
+
+Contributions are absolutely welcome! Most contributions start with an issue. Please don't hesitate to create issues in which you ask for features, give feedback on performances, or simply want to reach out.
+
+To make a pull request, please look at the detailed [Contributing guide](CONTRIBUTING.md) for how to do it, but fundamentally keep in mind the following main guidelines:
+
+- If you add a new feature or fix a bug:
+  - Make sure it is covered by tests
+  - Add a line in the changelog using `kacl-cli`
+- If you changed something in the documentation, make sure that the documentation site can be correctly build using `mkdocs serve`
+
+<br/>
+
+
 ## Citation
 
 [![arXiv](https://img.shields.io/badge/arXiv-2207.01499-b31b1b.svg?style=flat)](https://arxiv.org/abs/2207.01499)
 
 If you use `jwave` for your research, please consider citing it as:
 
 ```bibtex
```


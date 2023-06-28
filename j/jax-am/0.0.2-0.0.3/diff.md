# Comparing `tmp/jax-am-0.0.2.tar.gz` & `tmp/jax-am-0.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "jax-am-0.0.2.tar", last modified: Sun Nov  6 23:21:09 2022, max compression
+gzip compressed data, was "jax-am-0.0.3.tar", last modified: Wed Jun 28 14:25:29 2023, max compression
```

## Comparing `jax-am-0.0.2.tar` & `jax-am-0.0.3.tar`

### file list

```diff
@@ -1,33 +1,34 @@
-drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2022-11-06 23:21:09.127231 jax-am-0.0.2/
--rw-r--r--   0 tianjuxue   (501) staff       (20)    35149 2022-08-14 14:15:11.000000 jax-am-0.0.2/LICENSE
--rw-r--r--   0 tianjuxue   (501) staff       (20)     1278 2022-11-06 23:21:09.126985 jax-am-0.0.2/PKG-INFO
--rw-r--r--   0 tianjuxue   (501) staff       (20)      669 2022-11-06 20:42:30.000000 jax-am-0.0.2/README.md
-drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2022-11-06 23:21:09.120530 jax-am-0.0.2/jax_am/
--rw-r--r--   0 tianjuxue   (501) staff       (20)      799 2022-11-06 20:53:19.000000 jax-am-0.0.2/jax_am/__init__.py
-drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2022-11-06 23:21:09.123120 jax-am-0.0.2/jax_am/cfd/
--rw-r--r--   0 tianjuxue   (501) staff       (20)       90 2022-11-06 20:01:17.000000 jax-am-0.0.2/jax_am/cfd/__init__.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)    26939 2022-10-27 19:23:57.000000 jax-am-0.0.2/jax_am/cfd/cfd_am.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)     1091 2022-10-23 18:35:55.000000 jax-am-0.0.2/jax_am/cfd/generate_mesh.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)      205 2022-10-22 20:52:30.000000 jax-am-0.0.2/jax_am/cfd/json_parser.py
-drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2022-11-06 23:21:09.125229 jax-am-0.0.2/jax_am/fem/
--rw-r--r--   0 tianjuxue   (501) staff       (20)       90 2022-11-06 20:01:07.000000 jax-am-0.0.2/jax_am/fem/__init__.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)     6836 2022-11-05 21:11:50.000000 jax-am-0.0.2/jax_am/fem/basis.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)    30356 2022-11-06 19:47:13.000000 jax-am-0.0.2/jax_am/fem/core.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)     5774 2022-11-05 19:03:41.000000 jax-am-0.0.2/jax_am/fem/generate_mesh.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)     9105 2022-11-05 21:20:27.000000 jax-am-0.0.2/jax_am/fem/models.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)    19619 2022-11-02 17:14:59.000000 jax-am-0.0.2/jax_am/fem/solver.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)     1420 2022-10-27 01:27:25.000000 jax-am-0.0.2/jax_am/fem/utils.py
-drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2022-11-06 23:21:09.126635 jax-am-0.0.2/jax_am/phase_field/
--rw-r--r--   0 tianjuxue   (501) staff       (20)       89 2022-11-06 20:01:26.000000 jax-am-0.0.2/jax_am/phase_field/__init__.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)     9788 2022-10-24 15:39:10.000000 jax-am-0.0.2/jax_am/phase_field/allen_cahn.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)     1067 2022-11-06 20:02:54.000000 jax-am-0.0.2/jax_am/phase_field/neper.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)    12422 2022-11-06 19:42:12.000000 jax-am-0.0.2/jax_am/phase_field/utils.py
--rw-r--r--   0 tianjuxue   (501) staff       (20)      340 2022-10-26 21:47:35.000000 jax-am-0.0.2/jax_am/phase_field/yaml_parser.py
-drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2022-11-06 23:21:09.121922 jax-am-0.0.2/jax_am.egg-info/
--rw-r--r--   0 tianjuxue   (501) staff       (20)     1278 2022-11-06 23:21:09.000000 jax-am-0.0.2/jax_am.egg-info/PKG-INFO
--rw-r--r--   0 tianjuxue   (501) staff       (20)      598 2022-11-06 23:21:09.000000 jax-am-0.0.2/jax_am.egg-info/SOURCES.txt
--rw-r--r--   0 tianjuxue   (501) staff       (20)        1 2022-11-06 23:21:09.000000 jax-am-0.0.2/jax_am.egg-info/dependency_links.txt
--rw-r--r--   0 tianjuxue   (501) staff       (20)       79 2022-11-06 23:21:09.000000 jax-am-0.0.2/jax_am.egg-info/requires.txt
--rw-r--r--   0 tianjuxue   (501) staff       (20)        7 2022-11-06 23:21:09.000000 jax-am-0.0.2/jax_am.egg-info/top_level.txt
--rw-r--r--   0 tianjuxue   (501) staff       (20)       38 2022-11-06 23:21:09.127309 jax-am-0.0.2/setup.cfg
--rw-r--r--   0 tianjuxue   (501) staff       (20)     1619 2022-11-06 23:18:53.000000 jax-am-0.0.2/setup.py
+drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2023-06-28 14:25:29.545404 jax-am-0.0.3/
+-rw-r--r--   0 tianjuxue   (501) staff       (20)    35149 2022-08-14 14:15:11.000000 jax-am-0.0.3/LICENSE
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     6192 2023-06-28 14:25:29.545021 jax-am-0.0.3/PKG-INFO
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     5582 2023-06-08 22:04:33.000000 jax-am-0.0.3/README.md
+drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2023-06-28 14:25:29.528948 jax-am-0.0.3/jax_am/
+-rw-r--r--   0 tianjuxue   (501) staff       (20)      799 2023-06-28 14:20:49.000000 jax-am-0.0.3/jax_am/__init__.py
+drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2023-06-28 14:25:29.533087 jax-am-0.0.3/jax_am/cfd/
+-rw-r--r--   0 tianjuxue   (501) staff       (20)       90 2022-11-06 20:01:17.000000 jax-am-0.0.3/jax_am/cfd/__init__.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)    32368 2023-06-09 18:36:17.000000 jax-am-0.0.3/jax_am/cfd/cfd_am.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     3025 2023-06-10 21:13:23.000000 jax-am-0.0.3/jax_am/cfd/gamma.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     3862 2023-06-14 20:48:14.000000 jax-am-0.0.3/jax_am/common.py
+drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2023-06-28 14:25:29.540325 jax-am-0.0.3/jax_am/fem/
+-rw-r--r--   0 tianjuxue   (501) staff       (20)       90 2022-11-06 20:01:07.000000 jax-am-0.0.3/jax_am/fem/__init__.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     7630 2023-06-11 14:12:38.000000 jax-am-0.0.3/jax_am/fem/basis.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)    35305 2023-06-18 14:32:32.000000 jax-am-0.0.3/jax_am/fem/core.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     6256 2023-06-11 13:55:26.000000 jax-am-0.0.3/jax_am/fem/generate_mesh.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)    16820 2023-06-03 15:25:32.000000 jax-am-0.0.3/jax_am/fem/mma.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     8952 2022-12-15 18:44:08.000000 jax-am-0.0.3/jax_am/fem/models.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)    28296 2023-06-21 20:21:41.000000 jax-am-0.0.3/jax_am/fem/solver.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     1842 2023-06-06 22:04:06.000000 jax-am-0.0.3/jax_am/fem/utils.py
+drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2023-06-28 14:25:29.544188 jax-am-0.0.3/jax_am/phase_field/
+-rw-r--r--   0 tianjuxue   (501) staff       (20)       89 2022-11-06 20:01:26.000000 jax-am-0.0.3/jax_am/phase_field/__init__.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     9439 2023-01-25 16:33:15.000000 jax-am-0.0.3/jax_am/phase_field/allen_cahn.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     1067 2022-11-06 20:02:40.000000 jax-am-0.0.3/jax_am/phase_field/neper.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)    10865 2023-04-28 03:22:07.000000 jax-am-0.0.3/jax_am/phase_field/utils.py
+-rw-r--r--   0 tianjuxue   (501) staff       (20)      340 2022-10-26 21:47:35.000000 jax-am-0.0.3/jax_am/phase_field/yaml_parser.py
+drwxr-xr-x   0 tianjuxue   (501) staff       (20)        0 2023-06-28 14:25:29.530707 jax-am-0.0.3/jax_am.egg-info/
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     6192 2023-06-28 14:25:29.000000 jax-am-0.0.3/jax_am.egg-info/PKG-INFO
+-rw-r--r--   0 tianjuxue   (501) staff       (20)      599 2023-06-28 14:25:29.000000 jax-am-0.0.3/jax_am.egg-info/SOURCES.txt
+-rw-r--r--   0 tianjuxue   (501) staff       (20)        1 2023-06-28 14:25:29.000000 jax-am-0.0.3/jax_am.egg-info/dependency_links.txt
+-rw-r--r--   0 tianjuxue   (501) staff       (20)       86 2023-06-28 14:25:29.000000 jax-am-0.0.3/jax_am.egg-info/requires.txt
+-rw-r--r--   0 tianjuxue   (501) staff       (20)        7 2023-06-28 14:25:29.000000 jax-am-0.0.3/jax_am.egg-info/top_level.txt
+-rw-r--r--   0 tianjuxue   (501) staff       (20)       38 2023-06-28 14:25:29.545533 jax-am-0.0.3/setup.cfg
+-rw-r--r--   0 tianjuxue   (501) staff       (20)     1625 2023-05-10 01:39:05.000000 jax-am-0.0.3/setup.py
```

### Comparing `jax-am-0.0.2/LICENSE` & `jax-am-0.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `jax-am-0.0.2/jax_am/__init__.py` & `jax-am-0.0.3/jax_am/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -23,9 +23,9 @@
     Tianju Xue (https://tianjuxue.github.io/)
 
 """
 
 # TODO: public API management
 # __all__ = ()
 
-__version__ = "0.0.2"
+__version__ = "0.0.3"
```

### Comparing `jax-am-0.0.2/jax_am/cfd/cfd_am.py` & `jax-am-0.0.3/jax_am/cfd/cfd_am.py`

 * *Files 14% similar despite different names*

```diff
@@ -6,144 +6,15 @@
 from functools import partial
 import os
 import time
 import glob
 jax.config.update("jax_enable_x64", True)
 
 
-class poisson():
-    def __init__(self, mesh, nonlinear=False, miu=None, miu_fn=None,source_fn=None,bc_type=None, bc_value=None):
-        self.msh = mesh
-        self.ndof = self.msh.cell_num
-
-        self.nonlinear = nonlinear
-        if self.nonlinear == False:
-            assert np.isscalar(
-                miu), 'For linear problem, a constant miu value is required'
-            self.miu = miu
-            self.laplace_kernel = self.linear_laplace_kernal
-        else:
-            assert miu_fn != None, 'For nonlinear problem, please input miu_fn: miu = miu_fn(U)'
-            self.miu_fn = miu_fn
-            self.laplace_kernel = self.nonlinear_laplace_kernal
-
-        if source_fn == None:
-            self.source_fn = lambda *args : 0
-        else:
-            self.source_fn = source_fn
-
-        self.set_bc(bc_type, bc_value)
-
-    def linear_laplace_kernal(self, Up, Unb):
-        return ((Unb - Up) / self.msh.D * self.miu * self.msh.dS).sum()
-
-    def nonlinear_laplace_kernal(self, Up, Unb):
-        miu = self.miu_fn(Up / 2. + Unb / 2.)
-        return ((Unb - Up) / self.msh.D * miu * self.msh.dS).sum()
-
-    def laplace(self, U):
-        U_cell_nb = U[self.msh.cell_conn]
-        return jax.vmap(self.laplace_kernel)(U_cell_nb[:, 0], U_cell_nb[:, 1:])
-
-    def source(self,U,*args):
-        return jax.vmap(self.source_fn)(U,*args)
-
-    def apply_BC_to_residual(self, U, residual):
-        flux = np.array([])
-        if self.bc_type != None:
-            for i in range(len(self.bc_type)):
-                if self.bc_type[i] == 0:
-                    if self.nonlinear == True:
-                        miu = self.miu_fn(self.bc_value[i])
-                    else:
-                        miu = self.miu
-                    flux = np.concatenate(
-                        (flux, miu * 2 *
-                         (self.bc_value[i] -
-                          U[self.msh.surf_cell[self.msh.surf_sets[i]]]) /
-                         self.msh.D[i] * self.msh.dS[i]))
-                if self.bc_type[i] == 1:
-                    flux = np.concatenate(
-                        (flux, self.bc_value[i] * np.abs(self.msh.dS[i])))
-            residual = residual.at[self.msh.surf_cell].add(-flux)
-        return residual
-
-    def compute_residual_kernel(self, U_cell_nb, *args):
-        Up = U_cell_nb[0]
-        Unb = U_cell_nb[1:]
-        return -self.laplace_kernel(Up, Unb) - self.source_fn(Up,*args)*self.msh.dV
-
-    def compute_residual(self, U, *args):
-        residual = -self.laplace(U) - self.source(U,*args)*self.msh.dV
-        residual = self.apply_BC_to_residual(U, residual)
-        return residual
-
-    def apply_BC_to_matrix(self, values):
-        value_Dirichlet = np.array([])
-        loc_Dirichlet = np.array([], dtype=int)
-        if self.bc_type != None:
-            for i in range(len(self.bc_type)):
-                if self.bc_type[i] == 0:
-                    if self.nonlinear == True:
-                        miu = self.miu_fn(self.bc_value[i])
-                    else:
-                        miu = self.miu + self.bc_value[i]*0.
-                    value_Dirichlet = np.concatenate(
-                        (value_Dirichlet,
-                         miu * 2 / self.msh.D[i] * self.msh.dS[i]))
-                    loc_Dirichlet = np.concatenate(
-                        (loc_Dirichlet, self.msh.surf_cell[self.msh.surf_sets[i]]))
-            values = values.at[loc_Dirichlet, 0].add(value_Dirichlet)
-        return values
-
-    def newton_update(self, U, *args):
-        def D_fn(cell_nb_sol, *args):
-            return jax.jacrev(self.compute_residual_kernel)(cell_nb_sol, *args)
-
-        vmap_fn = jax.vmap(D_fn)
-        values = vmap_fn(U[self.msh.cell_conn],*args)
-        self.values = self.apply_BC_to_matrix(values)
-
-    def compute_linearized_residual(self, U):
-        return (self.values * U[self.msh.cell_conn]).sum(axis=1)
-
-    def jacobiPreconditioner(self,U):
-        return (self.values[:,0]*U)
-
-    def set_bc(self, bc_type, bc_value):
-        self.bc_type = bc_type
-        self.bc_value = bc_value
-
-
-class poisson_transient():
-    def __init__(self,
-                 mesh,
-                 dt,
-                 nonlinear=False,
-                 miu=None,
-                 rho=None,
-                 miu_fn=None,
-                 rho_fn=None,
-                 source_fn=None):
-        
-        if source_fn == None:
-            source_fn = lambda *args : 0
-        if nonlinear: 
-            assert rho_fn != None, 'For nonlinear problem, please input rho_fn: rho = rho_fn(U)'
-            self.rho_fn = rho_fn
-            fn = lambda U,U0,*args: -(rho_fn(U)/2.+rho_fn(U0)/2.)*(U-U0)/dt + source_fn(U,*args)
-        else:
-            assert np.isscalar(rho), 'For linear problem, a constant rho value is required'
-            fn = lambda U,U0,*args: -rho*(U-U0)/dt + source_fn(U,*args)
-            self.rho = rho
-        self.step = poisson(mesh, nonlinear, miu, miu_fn, source_fn=fn)
-
-
-
-# calculate ghost_cell values
+ # calculate ghost_cell values
 def ghost_cell(BC, value, dx=None, neighbor=None):
     if BC == 'Dirchlet' or BC == 0:
         return 2 * value - neighbor
     if BC == 'Neumann' or BC == 1:
         return neighbor + dx * value
     if BC == 'Marangoni_Z' or BC == 2:
         return np.concatenate(
@@ -158,14 +29,30 @@
         ghost_cell(BCs[0][1], BCs[1][1], dX[0], f[[-1], :, :]),
         ghost_cell(BCs[0][2], BCs[1][2], -dX[1], f[:, [0], :]),
         ghost_cell(BCs[0][3], BCs[1][3], dX[1], f[:, [-1], :]),
         ghost_cell(BCs[0][4], BCs[1][4], -dX[2], f[:, :, [0]]),
         ghost_cell(BCs[0][5], BCs[1][5], dX[2], f[:, :, [-1]])
     ]
 
+def laplace(f,f_gc,miu,dX,BCs=None):
+    if BCs == None:
+        BCs = [[1, 1, 1, 1, 1, 1], [0., 0., 0., 0., 0., 0.]]
+        f_gc = get_GC_values(f, BCs, dX)
+    if np.isscalar(miu):
+        dif = ((np.diff(f,axis=0,append=f_gc[1]) - np.diff(f,axis=0,prepend=f_gc[0]))/dX[0]*dX[1]*dX[2] +
+               (np.diff(f,axis=1,append=f_gc[3]) - np.diff(f,axis=1,prepend=f_gc[2]))/dX[1]*dX[2]*dX[0] +
+               (np.diff(f,axis=2,append=f_gc[5]) - np.diff(f,axis=2,prepend=f_gc[4]))/dX[2]*dX[0]*dX[1])*miu
+    else:
+        dif = ((np.diff(f,axis=0,append=f_gc[1])*miu[0][1:,:,:] 
+                    - np.diff(f,axis=0,prepend=f_gc[0])*miu[0][:-1,:,:])/dX[0]*dX[1]*dX[2] +
+               (np.diff(f,axis=1,append=f_gc[3])*miu[1][:,1:,:] 
+                    - np.diff(f,axis=1,prepend=f_gc[2])*miu[1][:,:-1,:])/dX[1]*dX[2]*dX[0] +
+               (np.diff(f,axis=2,append=f_gc[5])*miu[2][:,:,1:] 
+                    - np.diff(f,axis=2,prepend=f_gc[4])*miu[2][:,:,:-1])/dX[2]*dX[0]*dX[1])
+    return dif
 
 def div(f, vel_f, dX, theta=0.125, BCs=None):
     if BCs == None:
         BCs = [[1, 1, 1, 1, 1, 1], [0., 0., 0., 0., 0., 0.]]
     f_gc = get_GC_values(f, BCs, dX)
     u_f, v_f, w_f = vel_f
     fx = np.concatenate((f_gc[0], f_gc[0], f, f_gc[1], f_gc[1]), axis=0)
@@ -188,28 +75,26 @@
              f_face_x[:-1, :, :] * u_f[:-1, :, :]) / dX[0] +
             (f_face_y[:, 1:, :] * v_f[:, 1:, :] -
              f_face_y[:, :-1, :] * v_f[:, :-1, :]) / dX[1] +
             (f_face_z[:, :, 1:] * w_f[:, :, 1:] -
              f_face_z[:, :, :-1] * w_f[:, :, :-1]) / dX[2])
     return flux
 
-
 def gradient(f, dX, BCs=None):
     if BCs == None:
         BCs = [[1, 1, 1, 1, 1, 1], [0., 0., 0., 0., 0., 0.]]
     f_gc = get_GC_values(f, [[1, 1, 1, 1, 1, 1], [0., 0., 0., 0., 0., 0.]], dX)
     return np.concatenate(((np.diff(f, axis=0, append=f_gc[1]) +
                             np.diff(f, axis=0, prepend=f_gc[0])) / dX[0] / 2.,
                            (np.diff(f, axis=1, append=f_gc[3]) +
                             np.diff(f, axis=1, prepend=f_gc[2])) / dX[1] / 2.,
                            (np.diff(f, axis=2, append=f_gc[5]) +
                             np.diff(f, axis=2, prepend=f_gc[4])) / dX[2] / 2.),
                           axis=-1)
 
-
 def get_face_vels(vel, dX, BCs=None):
     if BCs == None:
         BCs = [[1, 1, 1, 1, 1, 1], [0., 0., 0., 0., 0., 0.]]
     vel_gc = get_GC_values(vel, BCs, dX)
 
     u = np.concatenate(
         (vel_gc[0][:, :, :, [0]], vel[:, :, :, [0]], vel_gc[1][:, :, :, [0]]),
@@ -223,254 +108,491 @@
 
     w = np.concatenate(
         (vel_gc[4][:, :, :, [2]], vel[:, :, :, [2]], vel_gc[5][:, :, :, [2]]),
         axis=2)
     w_f = (w[:, :, 1:] + w[:, :, :-1]) / 2
     return u_f, v_f, w_f
 
+def get_face_vel_component(vel, dX, axis=0, BCs=None):
+    if BCs == None:
+        BCs = [[1, 1, 1, 1, 1, 1], [0., 0., 0., 0., 0., 0.]]
+    vel_gc = get_GC_values(vel, BCs, dX)
 
+    if axis == 0:
+        u = np.concatenate(
+            (vel_gc[0], vel, vel_gc[1]),
+            axis=0)
+        u_f = (u[1:, :, :] + u[:-1, :, :]) / 2
+        return u_f
+
+    if axis == 1:
+        v = np.concatenate(
+            (vel_gc[2], vel, vel_gc[3]),
+            axis=1)
+        v_f = (v[:, 1:, :] + v[:, :-1, :]) / 2
+        return v_f
+
+    if axis == 2:
+        w = np.concatenate(
+            (vel_gc[4], vel, vel_gc),
+            axis=2)
+        w_f = (w[:, :, 1:] + w[:, :, :-1]) / 2
+        return v_f
 
-class AM_3d():
-    def __init__(self, params):
-        self.params = params
-        self.meshio_mesh = params['meshio_mesh']
-        self.msh = params['mesh']
-        self.msh_v = params['mesh_local']
-        self.shape = params['mesh'].shape
-
-        self.clean_sols()
 
+class AM_3d():
+    def __init__(self, args):
+        self.args = args
+        self.default_args()
+        self.msh = args['mesh']
+        self.msh_local = args['mesh_local']
+        self.meshio_mesh = args['meshio_mesh']
         self.t = 0.
-        self.dt = params['dt']
-        self.T0 = np.zeros(self.shape) + params['T_ref']
-        self.conv_T0 = np.zeros(self.shape)
-        self.vel0 = np.zeros((self.shape[0],self.shape[1],self.shape[2], 3))
-        self.conv0 = np.zeros((self.shape[0],self.shape[1],self.shape[2], 3))
-        self.p0 = np.zeros((self.shape[0],self.shape[1],self.shape[2], 1))
-
-        rho_cp = lambda T: params['cp'](T) * params['rho']
-        source = lambda T, conv: -conv
-        self.eqn_T = poisson_transient(mesh=params['mesh'],
-                                       dt=params['dt'],
-                                       nonlinear=True,
-                                       miu_fn=params['k'],
-                                       rho_fn=rho_cp,
-                                       source_fn=source)
-
-        source = lambda u, conv, fl, grad_p: -1e5 * params['rho'] * (
-            1 - fl)**2 / (fl**3 + 1e-3) * u - params['rho'] * conv - grad_p
-
-        self.eqn_v = poisson_transient(mesh=params['mesh_local'],
-                                       dt=params['dt'],
-                                       nonlinear=False,
-                                       miu=params['visco'],
-                                       rho=params['rho'],
-                                       source_fn=source)
-
-        source = lambda p, div_v: -div_v
-        self.poisson_for_p = poisson(mesh=params['mesh_local'],
-                                     miu=1.,
-                                     source_fn=source)
-        self.poisson_for_p.newton_update(np.zeros(self.poisson_for_p.ndof),
-                                         np.zeros(self.poisson_for_p.ndof))
-
-        # for better JIT time, very ugly, to be modified
-        self.cell_conn = np.copy(params['mesh'].cell_conn)
-        self.cell_conn_local = np.copy(params['mesh_local'].cell_conn)
-
-        ## vector form, for calculate ghost cell value
-        self.vel_bc_type = [0, 0, 0, 0, 0, 0]
-        v0 = np.array([0., 0., 0.])
-        self.vel_bc_values = [v0, v0, v0, v0, v0, v0]
-
-    def fluid_frac(self, T):
-        Tl = self.params['Tl']
-        Ts = self.params['Ts']
-        return (np.clip(T, Ts, Tl) - Ts) / (Tl - Ts)
+        self.eqn_T_init(args)
+        self.eqn_V_init(args)
+        self.clean_sols()
         
-    def update_vel_BC(self, T_top):
-        fl_top = self.fluid_frac(T_top)
-        Dgamma_Dt = self.params['Marangoni']
-        visco = self.params['visco']
-        T_top = np.pad(T_top, ((1, 1), (1, 1), (0, 0)), 'symmetric')
-
-        marangoni = np.stack(
-            ((T_top[2:, 1:-1] - T_top[:-2, 1:-1]) / 2 / self.msh_v.dX[0] *
-             Dgamma_Dt / visco * fl_top,
-             (T_top[1:-1, 2:] - T_top[1:-1, :-2]) / 2 / self.msh_v.dX[1] *
-             Dgamma_Dt / visco * fl_top, np.zeros_like(T_top[1:-1, 1:-1])),
-            axis=3)
-
-        ## vector form, for calculate ghost cell value
-        self.vel_bc_type = [0, 0, 0, 0, 0, 2]
-        v0 = np.array([0., 0., 0.])
-        self.vel_bc_values = [v0, v0, v0, v0, v0, marangoni]
-
-        ## scaler form, for solving the poisson eqn
-        vel_bc_type = [[0, 0, 0, 0, 0, 1], [0, 0, 0, 0, 0, 1],
-                       [0, 0, 0, 0, 0, 0]]
+    def default_args(self):
+        if 'h' not in self.args:
+            self.args['h'] = 0.
+        if 'stefan_boltzmann' not in self.args:
+            self.args['stefan_boltzmann'] = 5.67e-8
+        if 'emissivity' not in self.args:
+            self.args['emissivity'] = 0.
+        if self.args['heat_source'] == 1:
+            print(f"Body heat souce model is used.")
+            assert 'phi' in self.args, f"Body heat source is used but necessary parameter 'phi' is not set!"
+        else:
+            print(f"Surface heat source model is used.")
 
-        vel_bc_values = []
-        for i in range(3):
-            vel_bc_values.append([
-                np.zeros(self.msh_v.surf_set_num[0]),
-                np.zeros(self.msh_v.surf_set_num[1]),
-                np.zeros(self.msh_v.surf_set_num[2]),
-                np.zeros(self.msh_v.surf_set_num[3]),
-                np.zeros(self.msh_v.surf_set_num[4]),
-                marangoni[:, :, :, i].flatten() * visco,
-            ])
-        return vel_bc_type, vel_bc_values
-
-    def update_engergy_BC(self, eqn, t):
-        xl = self.params['X0'][0] + t * self.params['speed']
-        yl = self.params['X0'][1]
-        P = self.params['P']
-        eta = self.params['eta']
-        r = self.params['rb']
-
-        xc = eqn.msh.surface[eqn.msh.surf_sets[-1]][:, 0]
-        yc = eqn.msh.surface[eqn.msh.surf_sets[-1]][:, 1]
-        q_laser = 2 * P * eta / np.pi / r**2 * np.exp(-2 *
-                                                      ((xc - xl)**2 +
-                                                       (yc - yl)**2) / r**2)
-
-        q_laser = q_laser*(t<self.params['t_OFF']) ## laser off
-        # top surf: laser + conv., other surfs: adiabatic
-        bc_type = [1, 1, 1, 1, 1, 1]
-        bc_values = [
-            np.zeros(eqn.msh.surf_set_num[0]),
-            np.zeros(eqn.msh.surf_set_num[1]),
-            np.zeros(eqn.msh.surf_set_num[2]),
-            np.zeros(eqn.msh.surf_set_num[3]),
-            np.zeros(eqn.msh.surf_set_num[4]), q_laser
-        ]
-        eqn.set_bc(bc_type, bc_values)
+    def time_integration(self):
+        if self.args['heat_source'] == 1:
+            Q = self.get_body_heat_source(self.t)
+        else:
+            Q = self.T*0.
+        self.T, T_BCs, _ = self.eqn_T.update(self.T, self.conv_T, Q,
+                                             bc_args = (self.t,self.T[:,:,-1,:]), cell_conn = self.cell_conn)
+        fl0 = self.fluid_frac(self.T)
+
+        # self.solidID += fl0
+        self.solidID = np.maximum(self.solidID,fl0)
+
+        x0, x1, y0, y1, z0, z1 = self.get_moving_box_boundary(self.t)
+
+        vel, vel_BCs, grad_p0 = self.eqn_V.update(
+            self.vel[x0:x1, y0:y1, z0:z1], self.conv[x0:x1, y0:y1, z0:z1],
+            self.grad_p0[x0:x1, y0:y1, z0:z1], fl0[x0:x1, y0:y1, z0:z1],
+            self.T[x0:x1, y0:y1, z0:z1], self.cell_conn_local)
+
+        conv_T, conv = self.update_convective_terms(
+            self.T[x0:x1, y0:y1, z0:z1], vel, vel_BCs)
+
+        self.vel = self.vel.at[x0:x1, y0:y1, z0:z1].set(vel)
+        self.grad_p0 = self.grad_p0.at[x0:x1, y0:y1, z0:z1].set(grad_p0)
+        self.conv = self.conv.at[x0:x1, y0:y1, z0:z1].set(conv)
+        self.conv_T = self.conv_T.at[x0:x1, y0:y1, z0:z1].set(conv_T)
+        self.t += self.args['dt']
         
-    @partial(jax.jit, static_argnums=0)
-    def update_tempearture(self, t, T0, conv_T0,cell_conn):
-        # for better JIT time, very ugly, to be modified
-        self.eqn_T.step.msh.cell_conn = cell_conn
-        self.update_engergy_BC(self.eqn_T.step, t)
-
-        T = solver_nonlinear(self.eqn_T.step, T0.flatten(), conv_T0.flatten(), init=T0.flatten()).reshape(self.shape)
-        fl = self.fluid_frac(T)
-
-        # for update vel BC
-        T_top = T[:, :, -1] + self.msh.dX[2] / 2 * self.eqn_T.step.bc_value[
-            -1].reshape(self.shape[0], self.shape[1]) / self.eqn_T.step.miu_fn(
-                T[:, :, -1])
+# #### iterative scheme as a comparsion with the Non-iterative scheme (explicit convection)       
+#     def time_integration_iter(self,it=10):
+#         Q = self.get_body_heat_source(self.t)
         
-        return T, fl, T_top
-
-    @partial(jax.jit, static_argnums=0)
-    def update_velosity(self, vel0, p0, conv0, fl, T0_top, cell_conn):
-        # for better JIT time, very ugly, to be modified
-        self.eqn_v.step.msh.cell_conn = cell_conn
+#         for i in range(it):
+#             T, T_BCs, _ = self.eqn_T.update(self.T, self.conv_T, Q,
+#                                                  self.t, self.cell_conn)
+#             fl0 = self.fluid_frac(T)
+
+#             self.solidID += fl0
+
+#             x0, x1, y0, y1, z0, z1 = self.get_moving_box_boundary(self.t)
+
+#             vel, vel_BCs, grad_p0 = self.eqn_V.update(
+#                 self.vel[x0:x1, y0:y1, z0:z1], self.conv[x0:x1, y0:y1, z0:z1],
+#                 self.grad_p0[x0:x1, y0:y1, z0:z1], fl0[x0:x1, y0:y1, z0:z1],
+#                 T[x0:x1, y0:y1, z0:z1], self.cell_conn_local)
+
+#             conv_T, conv = self.update_convective_terms(T[x0:x1, y0:y1, z0:z1], vel, vel_BCs)
+            
+#             self.grad_p0 = self.grad_p0.at[x0:x1, y0:y1, z0:z1].set(grad_p0)
+#             self.conv = self.conv.at[x0:x1, y0:y1, z0:z1].set(conv)
+#             self.conv_T = self.conv_T.at[x0:x1, y0:y1, z0:z1].set(conv_T)
+
+#         self.vel = self.vel.at[x0:x1, y0:y1, z0:z1].set(vel)
+#         self.T = T
+#         self.t += self.args['dt']
+
+    def get_body_heat_source(self, t):
+        def Gaussian_cylinder(xl, yl, zl, P, xc, yc, zc):
+            eta = self.args['eta']
+            r = self.args['rb']
+            d = self.args['phi'] * P / self.args['speed'] / self.args['rb']**2
+            Q_laser = 2 * P * eta / d / np.pi / r**2 * np.exp(-2 * (
+                (xc - xl)**2 + (yc - yl)**2) / r**2)
+            Q_laser = Q_laser * ((zl - zc) <= d)
+            return Q_laser
+
+        xl, yl, zl, P = self.toolpath(t)
+        return Gaussian_cylinder(xl, yl, zl, P, self.msh.Xc[:, 0],
+                              self.msh.Xc[:, 1], self.msh.Xc[:, 2])
+
+    def get_moving_box_boundary(self, t):
+        ### for moving box
+        xl, yl, zl, _ = self.toolpath(t)
+        x0 = round(xl / self.msh.dX[0]) - round(self.msh_local.shape[0] / 2)
+        x0 = np.clip(x0,0,self.msh.shape[0]-self.msh_local.shape[0])
+        x1 = x0 + self.msh_local.shape[0]
+
+        y0 = round(yl / self.msh.dX[1]) - round(self.msh_local.shape[1] / 2)
+        y0 = np.clip(y0,0,self.msh.shape[1]-self.msh_local.shape[1])
+        y1 = y0 + self.msh_local.shape[1]
 
-        grad_p0 = gradient(p0, self.msh_v.dX)
-
-        # update vel BC
-        vel_bc_type, vel_bc_values = self.update_vel_BC(T0_top)
-
-        # prediction step
-        vel = []
-        for i in range(0, 3):
-            self.eqn_v.step.set_bc(vel_bc_type[i], vel_bc_values[i])
-            vel.append(
-                solver_linear(self.eqn_v.step,
-                              vel0[:, :, :, i].flatten(),
-                              conv0[:, :, :, i].flatten(),
-                              fl.flatten(),
-                              grad_p0[:, :, :, i].flatten(),
-                              tol=1e-10))
-
-        vel = np.stack((vel[0].reshape(self.msh_v.shape), vel[1].reshape(
-            self.msh_v.shape), vel[2].reshape(self.msh_v.shape)),
-                       axis=3)
-
-        # pressure eqn
-        u_f, v_f, w_f = get_face_vels(vel, self.msh_v.dX,
-                                      [self.vel_bc_type, self.vel_bc_values])
-        div_vel = ((u_f[1:, :, :] - u_f[:-1, :, :]) / self.msh_v.dX[0] +
-                   (v_f[:, 1:, :] - v_f[:, :-1, :]) / self.msh_v.dX[1] +
-                   (w_f[:, :, 1:] - w_f[:, :, :-1]) /
-                   self.msh_v.dX[2]) / self.dt * self.params['rho']
-        p = solver_linear(self.poisson_for_p,
-                          div_vel.flatten(),
-                          tol=1e-10,
-                          update=True)
-        p = p.reshape(self.msh_v.shape[0], self.msh_v.shape[1],
-                      self.msh_v.shape[2], 1)
+        z0 = round(zl / self.msh.dX[2]) - self.msh_local.shape[2]
+        z0 = self.msh.shape[2] - self.msh_local.shape[2]
+        z1 = self.msh.shape[2]
 
+        return x0, x1, y0, y1, z0, z1
 
-        vel_gc = get_GC_values(vel, [self.vel_bc_type, self.vel_bc_values],
-                                self.msh_v.dX)
-        vel_f = get_face_vels(vel, self.msh_v.dX,
-                               [self.vel_bc_type, self.vel_bc_values])
+    def update_convective_terms(self, T, vel, vel_BCs):
+        vel_f = get_face_vels(vel, self.msh.dX, vel_BCs)
+        conv_T = div(T, vel_f, self.msh.dX)
+#         conv = div(vel, vel_f, self.msh.dX, BCs=vel_BCs)
+        conv = div(vel, vel_f, self.msh.dX)
+        return conv_T, conv
+
+    def eqn_T_init(self, args):
+        self.eqn_T = energy_eqn(args)
+        self.eqn_T.bc_fn = self.get_energy_bc_fn()
+        self.cell_conn = np.copy(args['mesh'].cell_conn)
+
+        self.T = np.zeros(args['mesh'].shape + [1]) + args['T_ref']
+        self.solidID = np.zeros(args['mesh'].shape + [1])
+        self.conv_T = self.T * 0.
+        self.Q = self.T * 0.
+
+    def eqn_V_init(self, args):
+        self.eqn_V = velocity_eqn(args)
+        self.eqn_V.bc_fn = self.get_vel_bc_fn()
+        self.cell_conn_local = np.copy(args['mesh_local'].cell_conn)
+
+        self.vel = np.zeros(args['mesh'].shape + [3])
+        self.conv = self.vel * 0.
+        self.grad_p0 = self.vel * 0.
+
+    def toolpath(self, t):
+        xl = self.args['X0'][0] + t * self.args['speed']
+        yl = self.args['X0'][1]
+        zl = self.args['X0'][2]
+        P = self.args['P'] * (t < self.args['t_OFF'])
+        return xl, yl, zl, P
+
+    def get_vel_bc_fn(self):
+        Dgamma_Dt = self.args['Marangoni']
+        visco = self.args['visco']
+
+        def marangoni_effect(T_top):
+            fl_top = self.fluid_frac(T_top)
+            T_top = np.pad(T_top, ((1, 1), (1, 1), (0, 0)), 'symmetric')
+            return np.stack(((T_top[2:, 1:-1] - T_top[:-2, 1:-1]) / 2. /
+                             self.msh_local.dX[0] * Dgamma_Dt / visco * fl_top,
+                             (T_top[1:-1, 2:] - T_top[1:-1, :-2]) / 2. /
+                             self.msh_local.dX[1] * Dgamma_Dt / visco * fl_top,
+                             np.zeros_like(T_top[1:-1, 1:-1])),
+                            axis=3)
+
+        def vel_bc(T):
+            marangoni = marangoni_effect(T[:, :, -1])
+            vel_bc_type = [0, 0, 0, 0, 0, 2]
+            v0 = np.array([0., 0., 0.])
+            vel_bc_values = [v0, v0, v0, v0, v0, marangoni]
+            vel_BCs = [vel_bc_type, vel_bc_values]
 
-        # correction step
-        vel = vel - self.dt * gradient(p, self.msh.dX) / self.params['rho']
-        p += p0
-        conv = div(vel,vel_f,self.msh_v.dX,BCs=[self.vel_bc_type, self.vel_bc_values])
+            ## scaler form, for solving the poisson eqn
+            bc_type = [[0, 0, 0, 0, 0, 1], [0, 0, 0, 0, 0, 1],
+                       [0, 0, 0, 0, 0, 0]]
+            bc_values = []
+            for i in range(3):
+                bc_values.append([
+                    np.zeros(self.msh_local.surf_set_num[0]),
+                    np.zeros(self.msh_local.surf_set_num[1]),
+                    np.zeros(self.msh_local.surf_set_num[2]),
+                    np.zeros(self.msh_local.surf_set_num[3]),
+                    np.zeros(self.msh_local.surf_set_num[4]),
+                    marangoni[:, :, :, i].flatten() * visco,
+                ])
+            return vel_BCs, bc_type, bc_values
+
+        return vel_bc
+
+    def get_energy_bc_fn(self):
+        def Gaussian_flux(xl, yl, P, xc, yc):
+            eta = self.args['eta']
+            r = self.args['rb']
+            q_laser = 2 * P * eta / np.pi / r**2 * np.exp(-2 * (
+                (xc - xl)**2 + (yc - yl)**2) / r**2)
+
+            return q_laser
+
+        def energe_bc(args):
+            t,T_top = args
+            q_conv = self.args['h']*(T_top-self.args['T_ref'])
+            q_rad = self.args['stefan_boltzmann']*self.args['emissivity']*(T_top**4-self.args['T_ref']**4)
+            q = -q_conv - q_rad
+            bc_type = [1, 1, 1, 1, 1, 1]
+            bc_values = [
+                np.zeros(self.msh.surf_set_num[0]),
+                np.zeros(self.msh.surf_set_num[1]),
+                np.zeros(self.msh.surf_set_num[2]),
+                np.zeros(self.msh.surf_set_num[3]),
+                np.zeros(self.msh.surf_set_num[4]),
+                q.flatten()
+            ]
+
+            if self.args['heat_source'] == 0:
+                xc = self.msh.surface[self.msh.surf_sets[-1]][:, 0]
+                yc = self.msh.surface[self.msh.surf_sets[-1]][:, 1]
+                xl, yl, zl, P = self.toolpath(t)
+                q_laser = Gaussian_flux(xl, yl, P, xc, yc)
+                bc_values[-1] = bc_values[-1] + q_laser
 
-        return vel, p, conv
-    
-    def time_integration(self):
-        self.T0, fl, T0_top = self.update_tempearture(self.t, self.T0,self.conv_T0,
-                                                       self.cell_conn)
-        
-        ### for moving box, modification needed
-        x0 = int(self.msh.shape[0]/2) - int(self.msh_v.shape[0]/2)
-        x1 = x0 + self.msh_v.shape[0]
+            return bc_type, bc_values
 
-        y0 = int(self.msh.shape[1]/2) - int(self.msh_v.shape[1]/2)
-        y1 = y0 + self.msh_v.shape[1]
+        return energe_bc
 
-        z0 = self.msh.shape[2] - self.msh_v.shape[2]
-        z1 = self.msh.shape[2]
-        
-        vel_local, p, conv  = self.update_velosity(self.vel0[x0:x1,y0:y1,z0:z1], 
-                                                self.p0[x0:x1,y0:y1,z0:z1],
-                                                self.conv0[x0:x1,y0:y1,z0:z1],
-                                                fl[x0:x1,y0:y1,z0:z1], 
-                                                T0_top[x0:x1,y0:y1, None],
-                                                self.cell_conn_local)
+    def fluid_frac(self, T):
+        Tl = self.args['Tl']
+        Ts = self.args['Ts']
+        return (np.clip(T, Ts, Tl) - Ts) / (Tl - Ts)
 
-    
-        self.vel0 = self.vel0.at[x0:x1,y0:y1,z0:z1].set(vel_local)
-        self.p0 = self.p0.at[x0:x1,y0:y1,z0:z1].set(p)
-        self.conv0 = self.conv0.at[x0:x1,y0:y1,z0:z1].set(conv)
-        
-        vel0_f = get_face_vels(self.vel0,self.msh.dX)
-        self.conv_T0 = div(self.T0[:,:,:,None]*self.eqn_T.rho_fn(self.T0[:,:,:,None]),vel0_f,self.msh.dX)[:,:,:,0]
-    
-        self.t += self.dt
 
     def clean_sols(self):
-        cfd_vtk_sols_folder = os.path.join(self.params['data_dir'], "vtk/cfd/sols")
+        cfd_vtk_sols_folder = os.path.join(self.args['data_dir'], "vtk/cfd/sols")
         os.makedirs(cfd_vtk_sols_folder, exist_ok=True)
         files_vtk = glob.glob(cfd_vtk_sols_folder + f"/*")
         for f in files_vtk:
             os.remove(f)
 
     def inspect_sol(self, step, num_steps):
         print(f"\nstep {step} of {num_steps}, unix timestamp = {time.time()}")
-        print(f"T_max:{self.T0.max()}, vmax:{np.linalg.norm(self.vel0,axis=3).max()}")
-        if not np.all(np.isfinite(self.T0)):          
+        print(f"T_max:{self.T.max()}, vmax:{np.linalg.norm(self.vel,axis=3).max()}")
+        if not np.all(np.isfinite(self.T)):          
             raise ValueError(f"Found np.inf or np.nan in T0 - stop the program")
 
     def write_sols(self, step):
         print(f"\nWrite CFD sols to file...")
-        step = step // self.params['write_sol_interval']
-        self.meshio_mesh.cell_data['T'] = [onp.array(self.T0.reshape(-1, 1), dtype=onp.float32)]
-        self.meshio_mesh.cell_data['vel'] = [onp.array(self.vel0.reshape(-1, 3), dtype=onp.float32)]
-        self.meshio_mesh.cell_data['p'] = [onp.array(self.p0.reshape(-1, 1), dtype=onp.float32)]
-        self.meshio_mesh.write(os.path.join(self.params['data_dir'], f"vtk/cfd/sols/u{step:03d}.vtu"))
-       
+        step = step // self.args['write_sol_interval']
+        self.meshio_mesh.cell_data['T'] = [onp.array(self.T.reshape(-1, 1), dtype=onp.float32)]
+        self.meshio_mesh.cell_data['vel'] = [onp.array(self.vel.reshape(-1, 3), dtype=onp.float32)]
+        self.meshio_mesh.cell_data['solidID'] = [onp.array(self.solidID.reshape(-1, 1), dtype=onp.float32)]
+        self.meshio_mesh.write(os.path.join(self.args['data_dir'], f"vtk/cfd/sols/u{step:03d}.vtu"))
+
+        
+class poisson():
+    def __init__(self, mesh, nonlinear=False, mu=None, mu_fn=None,source_fn=None,bc_type=None, bc_value=None):
+        self.msh = mesh
+        self.ndof = self.msh.cell_num
+
+        self.nonlinear = nonlinear
+        if self.nonlinear == False:
+            assert np.isscalar(
+                mu), 'For linear problem, a constant mu value is required'
+            self.mu = mu
+            self.laplace_kernel = self.linear_laplace_kernel
+        else:
+            assert mu_fn != None, 'For nonlinear problem, please input mu_fn: mu = mu_fn(U)'
+            self.mu_fn = mu_fn
+            self.laplace_kernel = self.nonlinear_laplace_kernel
+
+        if source_fn == None:
+            self.source_fn = lambda *args : 0
+        else:
+            self.source_fn = source_fn
+
+        self.set_bc(bc_type, bc_value)
+
+    def linear_laplace_kernel(self, Up, Unb):
+        return ((Unb - Up) / self.msh.D * self.mu * self.msh.dS).sum()
+
+    def nonlinear_laplace_kernel(self, Up, Unb):
+        # see Patankar, Suhas V. Numerical heat transfer and fluid flow. CRC press, 2018. page 44-47
+        mu = 2*self.mu_fn(Up)*self.mu_fn(Unb)/(self.mu_fn(Unb)+self.mu_fn(Up))
+        return ((Unb - Up) / self.msh.D * mu * self.msh.dS).sum()
+
+    def laplace(self, U):
+        U_cell_nb = U[self.msh.cell_conn]
+        return jax.vmap(self.laplace_kernel)(U_cell_nb[:, 0], U_cell_nb[:, 1:])
+
+    def source(self,U,*args):
+        return jax.vmap(self.source_fn)(U,*args)
+
+    def apply_BC_to_residual(self, U, residual):
+        flux = np.array([])
+        if self.bc_type != None:
+            for i in range(len(self.bc_type)):
+                if self.bc_type[i] == 0:
+                    if self.nonlinear == True:
+                        mu = self.mu_fn(self.bc_value[i])
+                    else:
+                        mu = self.mu
+                    flux = np.concatenate(
+                        (flux, mu * 2 *
+                         (self.bc_value[i] -
+                          U[self.msh.surf_cell[self.msh.surf_sets[i]]]) /
+                         self.msh.D[i] * self.msh.dS[i]))
+                if self.bc_type[i] == 1:
+                    flux = np.concatenate(
+                        (flux, self.bc_value[i] * np.abs(self.msh.dS[i])))
+            residual = residual.at[self.msh.surf_cell].add(-flux)
+        return residual
+
+    def compute_residual_kernel(self, U_cell_nb, *args):
+        Up = U_cell_nb[0]
+        Unb = U_cell_nb[1:]
+        return -self.laplace_kernel(Up, Unb) - self.source_fn(Up,*args)*self.msh.dV
+
+    def compute_residual(self, U, *args):
+        residual = -self.laplace(U) - self.source(U,*args)*self.msh.dV
+        residual = self.apply_BC_to_residual(U, residual)
+        return residual
+
+    def apply_BC_to_matrix(self, values):
+        value_Dirichlet = np.array([])
+        loc_Dirichlet = np.array([], dtype=int)
+        if self.bc_type != None:
+            for i in range(len(self.bc_type)):
+                if self.bc_type[i] == 0:
+                    if self.nonlinear == True:
+                        mu = self.mu_fn(self.bc_value[i])
+                    else:
+                        mu = self.mu + self.bc_value[i]*0.
+                    value_Dirichlet = np.concatenate(
+                        (value_Dirichlet,
+                         mu * 2 / self.msh.D[i] * self.msh.dS[i]))
+                    loc_Dirichlet = np.concatenate(
+                        (loc_Dirichlet, self.msh.surf_cell[self.msh.surf_sets[i]]))
+            values = values.at[loc_Dirichlet, 0].add(value_Dirichlet)
+        return values
+
+    def newton_update(self, U, *args):
+        def D_fn(cell_nb_sol, *args):
+            return jax.jacrev(self.compute_residual_kernel)(cell_nb_sol, *args)
+
+        vmap_fn = jax.vmap(D_fn)
+        values = vmap_fn(U[self.msh.cell_conn],*args)
+        self.values = self.apply_BC_to_matrix(values)
+        self.precond_values = ((self.msh.cell_conn == np.arange(self.msh.cell_num)[:,None])*self.values).sum(axis=1)
+
+    def compute_linearized_residual(self, U):
+        return (self.values * U[self.msh.cell_conn]).sum(axis=1)
+
+    def jacobiPreconditioner(self,U):
+        # return (1./self.values[:,0]*U)
+        return (1./self.precond_values*U)
+
+    def set_bc(self, bc_type, bc_value):
+        self.bc_type = bc_type
+        self.bc_value = bc_value
+
+
+class energy_eqn():
+    def __init__(self, args):
+        cp_fn = lambda T: args['cp'](T) + args['latent_heat'] / (args[
+            'Tl'] - args['Ts']) * (T > args['Ts']) * (T < args['Tl'])
+        fn = lambda T, T0, conv, Q: -args['rho'] * (T - T0) * cp_fn(
+            T0) / args['dt'] - args['rho'] * cp_fn(T0) * conv + Q
+        mu_fn = lambda T: args['k'](T)
+        self.step = poisson(mesh=args['mesh'],
+                            nonlinear='True',
+                            mu_fn=mu_fn,
+                            source_fn=fn)
+        self.bc_fn = None
+    
+    def update_BCs(self,*bc_args):
+        if self.bc_fn != None:
+            bc_types,bc_values = self.bc_fn(*bc_args)
+            self.BCs = [bc_types,bc_values]
+            self.step.set_bc(bc_types,bc_values)
+        
+
+    @partial(jax.jit, static_argnums=(0))
+    def update(self, T0, conv_T0, Q, bc_args, cell_conn):
+        self.step.msh.cell_conn = cell_conn
+        self.update_BCs(bc_args)
+        T, it = solver_nonlinear(self.step,
+                                 T0.flatten(),
+                                 conv_T0.flatten(),
+                                 Q.flatten(),
+                                 init=T0.flatten(),
+                                 precond=True)
+        return T.reshape(T0.shape), self.BCs, it
+
+
+class velocity_eqn():
+    def __init__(self, args):
+
+        self.dt = args['dt']
+        self.rho = args['rho']
+        fn = lambda u, u0, conv, grad_p, fl: -self.rho * (
+            u - u0) / self.dt - self.rho*conv - grad_p - 1e7 * self.rho * (
+                1 - fl)**2 / (fl**3 + 1e-5) * u
+        self.step = poisson(mesh=args['mesh_local'],
+                            nonlinear= False,
+                            mu=args['visco'],
+                            source_fn=fn)
+
+        source = lambda p, div_v: -div_v
+        self.poisson_for_p = poisson(mesh=args['mesh_local'],
+                                     mu=1.,
+                                     source_fn=source)
+
+        self.poisson_for_p.newton_update(np.zeros(self.poisson_for_p.ndof),
+                                         np.zeros(self.poisson_for_p.ndof))
+
+        self.bc_fn = None
+
+    def update_BCs(self,*bc_args):
+        if self.bc_fn != None:
+            self.vel_BCs,bc_types,bc_values = self.bc_fn(*bc_args) #vel_BCs: vector form for calculate face velosities;
+            return bc_types,bc_values
+
+    @partial(jax.jit, static_argnums=(0))
+    def update(self, vel0, conv0, grad_p0, fl, bc_args, cell_conn):
+        self.step.msh.cell_conn = cell_conn
+        # prediction step
+        vel = []
+        bc_types,bc_values = self.update_BCs(bc_args)
+        for i in range(0, 3):
+            self.step.set_bc(bc_types[i],bc_values[i])
+            vel_i = solver_linear(self.step,
+                        vel0[:, :, :, i].flatten(),
+                        conv0[:, :, :, i].flatten(),
+                        grad_p0[:, :, :, i].flatten(),
+                        fl.flatten(),
+                        tol=1e-10,
+                        precond=True).reshape(self.step.msh.shape)
+            vel.append(vel_i)
+        vel = np.stack((vel[0], vel[1], vel[2]),axis=3)
+
+        # correction step
+        u_f, v_f, w_f = get_face_vels(vel, self.step.msh.dX, self.vel_BCs)
+        div_vel = ((u_f[1:, :, :] - u_f[:-1, :, :]) / self.step.msh.dX[0] +
+                   (v_f[:, 1:, :] - v_f[:, :-1, :]) / self.step.msh.dX[1] +
+                   (w_f[:, :, 1:] - w_f[:, :, :-1]) /
+                   self.step.msh.dX[2]) / self.dt * self.rho 
+
+        p = solver_linear(self.poisson_for_p,
+                          div_vel.flatten(),
+                          tol=1e-10,
+                          update=False,
+                          precond=False)
+
+        p = p.reshape(self.step.msh.shape + [1])
+        vel = vel - self.dt * gradient(p, self.step.msh.dX) / self.rho
+        # vel_f = get_face_vels(vel,self.step.msh.dX,self.vel_BCs)
+        return vel, self.vel_BCs, grad_p0 + gradient(p, self.step.msh.dX)
+
 
 class uniform_mesh():
     def __init__(self, domain, N):
         self.shape = N
         self.dim = len(N)
         self.generate_mesh(domain, N)
         self.get_neighbor(N)
@@ -619,56 +741,73 @@
         surf_y_pos = self.Xc[y_pos_idx] + onp.array([0., self.dX[1] / 2., 0.])
         surf_z_neg = self.Xc[z_neg_idx] - onp.array([0., 0., self.dX[2] / 2.])
         surf_z_pos = self.Xc[z_pos_idx] + onp.array([0., 0., self.dX[2] / 2.])
         self.surface = np.concatenate((surf_x_neg, surf_x_pos, surf_y_neg,
                                        surf_y_pos, surf_z_neg, surf_z_pos))
 
 
-def solver_linear(eqn,*args,tol=1e-6,precond=False,update=True):
+def solver_linear(eqn,*args,tol=1e-6,precond=False,update=True,relative=False):
 # solve linear problems
     
     dofs = np.zeros(eqn.ndof)
     
     res = eqn.compute_residual(dofs,*args)
     if update:
         eqn.newton_update(dofs,*args)
 
+    if relative:
+        eqn.values = eqn.values.at[0].set(np.array([1., 0., 0., 0., 0., 0., 0.]))
+
+
     A_fn = eqn.compute_linearized_residual
     if precond:
         preconditoner = eqn.jacobiPreconditioner
+        if relative:
+            eqn.precond_values = eqn.precond_values.at[0].set(1.)
     else:
         preconditoner = None
+
     b = -res
+    if relative:
+        b = b.at[0].set(0.)
 
-    # TODO(Tianju): Any way to detect if CG does not converge? The program can get stuck.
+    # TODO (Tianju): Any way to detect if CG does not converge? The program can get stuck.
     inc, info = jax.scipy.sparse.linalg.bicgstab(A_fn, b, M=preconditoner, x0=None, tol=tol,maxiter=10000) # bicgstab
     dofs =  dofs + inc
     
     return dofs
 
 
-def solver_nonlinear(eqn,*args,init=None,tol=1e-5,max_it=5000):
+def solver_nonlinear(eqn,*args,init=None,tol=1e-5,max_it=50,relaxation=1.,precond=False):
 # solve nonlinear problems
 
+    if precond:
+        preconditoner = eqn.jacobiPreconditioner
+    else:
+        preconditoner = None
+
+    if init == None:
+        dofs = np.zeros(eqn.ndof)
+    else:
+        dofs = init
+
+    b = -eqn.compute_residual(dofs,*args)
+    res_init = np.linalg.norm(b)
+
     def cond_fun(carry):
-        dofs,inc,it = carry
-        return (np.linalg.norm(inc)/np.linalg.norm(dofs) > tol) & (it < max_it)
+        dofs,b,it = carry
+        return (np.linalg.norm(b)/np.linalg.norm(res_init) > tol) & (it < max_it)
 
     def body_fun(carry):
-        dofs,inc,it = carry
-        b = -eqn.compute_residual(dofs,*args)
+        dofs,b,it = carry
         eqn.newton_update(dofs,*args)
         A_fn_linear = eqn.compute_linearized_residual
-        inc, info = jax.scipy.sparse.linalg.bicgstab(A_fn_linear, b)
-        dofs = dofs + inc
-        return (dofs,inc,it+1)
+        inc, info = jax.scipy.sparse.linalg.bicgstab(A_fn_linear, b, M=preconditoner)
+        dofs = dofs + inc*relaxation
+        b = -eqn.compute_residual(dofs,*args)
+        return (dofs,b,it+1)
     
-    if init == None:
-        dofs = np.zeros(eqn.ndof)
-    else:
-        dofs = init
     it = 0
     inc = np.ones_like(dofs)
-    dofs,inc,it = jax.lax.while_loop(cond_fun, body_fun, (dofs,inc,it))
+    dofs,b,it = jax.lax.while_loop(cond_fun, body_fun, (dofs,b,it))
 
-    
-    return dofs
+    return dofs,it
```

### Comparing `jax-am-0.0.2/jax_am/fem/basis.py` & `jax-am-0.0.3/jax_am/fem/basis.py`

 * *Files 22% similar despite different names*

```diff
@@ -10,94 +10,122 @@
 #     """
 #     if ele_type == 'hexahedron' or ele_type == 'quadrilateral':
 #         return 2 * (dim*lag_order - 1)
 
 #     if ele_type == 'tetrahedron' or ele_type == 'triangle':
 #         return 2 * (dim*(lag_order - 1) - 1)
 
-def get_elements(ele_type, lag_order):
+def get_elements(ele_type):
     """Mesh node ordering is important.
     If the input mesh file is Gmsh .msh or Abaqus .inp, meshio would convert it to
     its own ordering. My experience shows that meshio ordering is the same as Abaqus.
     For example, for a 10-node tetrahedron element, the ordering of meshio is the following
     https://web.mit.edu/calculix_v2.7/CalculiX/ccx_2.7/doc/ccx/node33.html
     The troublesome thing is that basix has a different ordering. As shown below
     https://defelement.com/elements/lagrange.html
     The consequence is that we need to define this "re_order" variable to make sure the 
     ordering is correct.
     """
-    if (ele_type, lag_order) == ('hexahedron', 1):
+    element_family = basix.ElementFamily.P
+    if ele_type == 'HEX8':
         re_order = [0, 1, 3, 2, 4, 5, 7, 6]
         basix_ele = basix.CellType.hexahedron
         basix_face_ele = basix.CellType.quadrilateral
         gauss_order = 2 # 2x2x2, TODO: is this full integration?
-    elif (ele_type, lag_order) == ('hexahedron', 2):
+        degree = 1
+    elif ele_type == 'HEX27':
         print(f"Warning: 27-node hexahedron is rarely used in practice and not recommended.")
         re_order = [0, 1, 3, 2, 4, 5, 7, 6, 8, 11, 13, 9, 16, 18, 19, 
                     17, 10, 12, 15, 14, 22, 23, 21, 24, 20, 25, 26]
         basix_ele = basix.CellType.hexahedron
         basix_face_ele = basix.CellType.quadrilateral
         gauss_order = 10 # 6x6x6, full integration
-    elif (ele_type, lag_order) == ('tetrahedron', 1):
+        degree = 2
+    elif ele_type == 'HEX20':
+        re_order = [0, 1, 3, 2, 4, 5, 7, 6, 8, 11, 13, 9, 16, 18, 19, 17, 10, 12, 15, 14]
+        element_family = basix.ElementFamily.serendipity
+        basix_ele = basix.CellType.hexahedron
+        basix_face_ele = basix.CellType.quadrilateral
+        gauss_order = 2 # 6x6x6, full integration
+        degree = 2
+    elif ele_type == 'TET4':
         re_order = [0, 1, 2, 3]
         basix_ele = basix.CellType.tetrahedron
         basix_face_ele = basix.CellType.triangle
         gauss_order = 0 # 1, full integration
-    elif (ele_type, lag_order) == ('tetrahedron', 2):
+        degree = 1
+    elif ele_type == 'TET10':
         re_order = [0, 1, 2, 3, 9, 6, 8, 7, 5, 4]
         basix_ele = basix.CellType.tetrahedron
         basix_face_ele = basix.CellType.triangle
         gauss_order = 2 # 4, full integration
-    elif (ele_type, lag_order) == ('triangle', 1):
+        degree = 2
+    # TODO: Check if this is correct.
+    elif ele_type == 'QUAD4':
+        re_order = [0, 1, 3, 2]
+        basix_ele = basix.CellType.quadrilateral
+        basix_face_ele = basix.CellType.interval
+        gauss_order = 2
+        degree = 1
+    elif ele_type == 'QUAD8':
+        re_order = [0, 1, 3, 2, 4, 6, 7, 5]
+        element_family = basix.ElementFamily.serendipity
+        basix_ele = basix.CellType.quadrilateral
+        basix_face_ele = basix.CellType.interval
+        gauss_order = 2 
+        degree = 2 
+    elif ele_type == 'TRI3':
         re_order = [0, 1, 2]
         basix_ele = basix.CellType.triangle
         basix_face_ele = basix.CellType.interval
-        gauss_order = 0 # 1, full integration        
-    elif (ele_type, lag_order) == ('triangle', 2):
+        gauss_order = 0 # 1, full integration    
+        degree = 1    
+    elif  ele_type == 'TRI6':
         re_order = [0, 1, 2, 5, 3, 4]
         basix_ele = basix.CellType.triangle
         basix_face_ele = basix.CellType.interval
-        gauss_order = 2 # 3, full integration  
+        gauss_order = 2 # 3, full integration 
+        degree = 2 
     else:
         raise NotImplementedError
 
-    return basix_ele, basix_face_ele, gauss_order, re_order
+    return element_family, basix_ele, basix_face_ele, gauss_order, degree, re_order
 
 
 def reorder_inds(inds, re_order):
     new_inds = []
     for ind in inds.reshape(-1): 
         new_inds.append(onp.argwhere(re_order == ind))
     new_inds = onp.array(new_inds).reshape(inds.shape)
     return new_inds
 
 
-def get_shape_vals_and_grads(ele_type, lag_order):
+def get_shape_vals_and_grads(ele_type):
     """TODO: Add comments
 
     Returns
     ------- 
     shape_values: ndarray
         (8, 8) = (num_quads, num_nodes)
     shape_grads_ref: ndarray
         (8, 8, 3) = (num_quads, num_nodes, dim)
     weights: ndarray
         (8,) = (num_quads,)
     """
-    basix_ele, basix_face_ele, gauss_order, re_order = get_elements(ele_type, lag_order)
+    element_family, basix_ele, basix_face_ele, gauss_order, degree, re_order = get_elements(ele_type)
     quad_points, weights = basix.make_quadrature(basix_ele, gauss_order)  
-    lagrange = basix.create_element(basix.ElementFamily.P, basix_ele, lag_order, basix.LagrangeVariant.equispaced)
-    vals_and_grads = lagrange.tabulate(1, quad_points)[:, :, re_order, :]
+    element = basix.create_element(element_family, basix_ele, degree)
+    vals_and_grads = element.tabulate(1, quad_points)[:, :, re_order, :]
     shape_values = vals_and_grads[0, :, :, 0]
     shape_grads_ref = onp.transpose(vals_and_grads[1:, :, :, 0], axes=(1, 2, 0))
-    print(f"ele_type = {ele_type}, lag_order = {lag_order}, quad_points.shape= {quad_points.shape}")
+    print(f"ele_type = {ele_type}, quad_points.shape = (num_quads, dim) = {quad_points.shape}")
     return shape_values, shape_grads_ref, weights
 
 
-def get_face_shape_vals_and_grads(ele_type, lag_order):
+def get_face_shape_vals_and_grads(ele_type):
     """TODO: Add comments
 
     Returns
     ------- 
     face_shape_vals: ndarray
         (6, 4, 8) = (num_faces, num_face_quads, num_nodes)
     face_shape_grads_ref: ndarray
@@ -105,21 +133,21 @@
     face_weights: ndarray
         (6, 4) = (num_faces, num_face_quads)
     face_normals:ndarray
         (6, 3) = (num_faces, dim)
     face_inds: ndarray
         (6, 4) = (num_faces, num_face_vertices)
     """
-    basix_ele, basix_face_ele, gauss_order, re_order = get_elements(ele_type, lag_order)
+    element_family, basix_ele, basix_face_ele, gauss_order, degree, re_order = get_elements(ele_type)
 
     # TODO: Check if this is correct.
     points, weights = basix.make_quadrature(basix_face_ele, gauss_order)
 
-    map_lag_order = 1
-    lagrange_map = basix.create_element(basix.ElementFamily.P, basix_face_ele, map_lag_order, basix.LagrangeVariant.equispaced)
+    map_degree = 1
+    lagrange_map = basix.create_element(basix.ElementFamily.P, basix_face_ele, map_degree)
     values = lagrange_map.tabulate(0, points)[0, :, :, 0]
     vertices = basix.geometry(basix_ele)
     dim = len(vertices[0])
     facets = basix.cell.sub_entity_connectivity(basix_ele)[dim - 1] 
     # Map face points
     # Reference: https://docs.fenicsproject.org/basix/main/python/demo/demo_facet_integral.py.html
     face_quad_points = []
@@ -142,14 +170,14 @@
     face_quad_points = onp.stack(face_quad_points)
     face_weights = onp.stack(face_weights)
 
     face_normals = basix.cell.facet_outward_normals(basix_ele)
     face_inds = onp.array(face_inds)
     face_inds = reorder_inds(face_inds, re_order)
     num_faces, num_face_quads, dim = face_quad_points.shape
-    lagrange = basix.create_element(basix.ElementFamily.P, basix_ele, lag_order, basix.LagrangeVariant.equispaced)
-    vals_and_grads = lagrange.tabulate(1, face_quad_points.reshape(-1, dim))[:, :, re_order, :]
+    element = basix.create_element(element_family, basix_ele, degree)
+    vals_and_grads = element.tabulate(1, face_quad_points.reshape(-1, dim))[:, :, re_order, :]
     face_shape_vals = vals_and_grads[0, :, :, 0].reshape(num_faces, num_face_quads, -1)
     face_shape_grads_ref = vals_and_grads[1:, :, :, 0].reshape(dim, num_faces, num_face_quads, -1)
     face_shape_grads_ref = onp.transpose(face_shape_grads_ref, axes=(1, 2, 3, 0))
-    print(f"face_quad_points.shape = {face_quad_points.shape}")
+    print(f"face_quad_points.shape = (num_faces, num_face_quads, dim) = {face_quad_points.shape}")
     return face_shape_vals, face_shape_grads_ref, face_weights, face_normals, face_inds
```

### Comparing `jax-am-0.0.2/jax_am/fem/core.py` & `jax-am-0.0.3/jax_am/fem/core.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,14 +1,15 @@
 import numpy as onp
 import jax
 import jax.numpy as np
 from jax.experimental.sparse import BCOO
 import scipy
 import sys
 import time
+import functools
 from dataclasses import dataclass
 from typing import Any, Callable, Optional, List, Union
 
 from jax_am.fem.generate_mesh import Mesh
 from jax_am.fem.basis import get_face_shape_vals_and_grads, get_shape_vals_and_grads
 
 from jax.config import config
@@ -38,16 +39,14 @@
     vec : int
         The number of vector variable components of the solution.
         E.g., a 3D displacement field has u_x, u_y and u_z components, so vec=3 
     dim : int
         The dimension of the problem.
     ele_type : str
         Element type
-    lag_order : int
-        Lagrangian shape function order
     dirichlet_bc_info : [location_fns, vecs, value_fns]
         location_fns : List[Callable]
             Callable : a function that inputs a point and returns if the point satisfies the location condition
         vecs: List[int]
             integer value must be in the range of 0 to vec - 1, 
             specifying which component of the (vector) variable to apply Dirichlet condition to
         value_fns : List[Callable]
@@ -75,16 +74,15 @@
         A function that inputs a point and returns the body force at this point
     additional_info : Any
         Other information that the FEM solver should know
     """
     mesh: Mesh
     vec: int
     dim: int
-    ele_type: str = 'hexahedron'
-    lag_order: int = 1
+    ele_type: str = 'HEX8'
     dirichlet_bc_info: Optional[List[Union[List[Callable], List[int], List[Callable]]]] = None 
     periodic_bc_info: Optional[List[Union[List[Callable], List[Callable], List[Callable], List[int]]]] = None
     neumann_bc_info: Optional[List[Union[List[Callable], List[Callable]]]] = None
     cauchy_bc_info: Optional[List[Union[List[Callable], List[Callable]]]] = None
     source_info: Callable = None
     additional_info: Any = ()
 
@@ -92,69 +90,57 @@
         self.points = self.mesh.points
         self.cells = self.mesh.cells
         self.num_cells = len(self.cells)
         self.num_total_nodes = len(self.mesh.points)
         self.num_total_dofs = self.num_total_nodes*self.vec
 
         start = time.time()
+        print(f"Start timing - Compute shape function values, gradients, etc.")
 
-        self.shape_vals, self.shape_grads_ref, self.quad_weights = get_shape_vals_and_grads(self.ele_type, self.lag_order)
+        self.shape_vals, self.shape_grads_ref, self.quad_weights = get_shape_vals_and_grads(self.ele_type)
         self.face_shape_vals, self.face_shape_grads_ref, self.face_quad_weights, self.face_normals, self.face_inds \
-        = get_face_shape_vals_and_grads(self.ele_type, self.lag_order)
-
+        = get_face_shape_vals_and_grads(self.ele_type)
         self.num_quads = self.shape_vals.shape[0]
         self.num_nodes = self.shape_vals.shape[1]
         self.num_faces = self.face_shape_vals.shape[0]
-
         self.shape_grads, self.JxW = self.get_shape_grads()
 
-        # Note: Assume Dirichlet B.C. must be provided. This is probably true for all the problems we will encounter.
         self.node_inds_list, self.vec_inds_list, self.vals_list = self.Dirichlet_boundary_conditions(self.dirichlet_bc_info)
-        if self.periodic_bc_info is not None:
-            self.p_node_inds_list_A, self.p_node_inds_list_B, self.p_vec_inds_list = \
-            self.periodic_boundary_conditions(self.periodic_bc_info)
+        self.p_node_inds_list_A, self.p_node_inds_list_B, self.p_vec_inds_list = self.periodic_boundary_conditions()
+
+        # (num_cells, num_quads, num_nodes, 1, dim)
+        self.v_grads_JxW = self.shape_grads[:, :, :, None, :] * self.JxW[:, :, None, None, None]
 
         end = time.time()
         compute_time = end - start
-        print(f"\nDone pre-computations, took {compute_time} [s]")
-        print(f"Solving a problem with {len(self.cells)} cells, {self.num_total_nodes}x{self.vec} = {self.num_total_dofs} dofs.")
 
-        # TODO: full_field_infer/poisson.py
-        # A better way to pass design parameters in
-        # Do not compute it here.
-        self.body_force = self.compute_body_force(self.source_info)
+        self.internal_vars = {}
+        self.compute_Neumann_boundary_inds()
 
-        if self.neumann_bc_info is not None:
-            self.neumann_location_fns, self.neumann_value_fns = self.neumann_bc_info
-            if self.neumann_location_fns is not None:
-                self.neumann_boundary_inds_list = self.get_boundary_conditions_inds(self.neumann_location_fns)
-            
-        # self.neumann = self.compute_Neumann_integral()
-
-        # (num_cells, num_quads, num_nodes, 1, dim)
-        self.v_grads_JxW = self.shape_grads[:, :, :, None, :] * self.JxW[:, :, None, None, None]
+        print(f"Done pre-computations, took {compute_time} [s]")
+        print(f"Solving a problem with {len(self.cells)} cells, {self.num_total_nodes}x{self.vec} = {self.num_total_dofs} dofs.")
 
         self.custom_init(*self.additional_info)
 
     def custom_init(self):
         """Child class should override if more things need to be done in initialization
         """
         pass
 
     def get_shape_grads(self):
-        """Pre-compute shape function gradient value
+        """Compute shape function gradient value
         The gradient is w.r.t physical coordinates.
         See Hughes, Thomas JR. The finite element method: linear static and dynamic finite element analysis. Courier Corporation, 2012.
         Page 147, Eq. (3.9.3)
-
+        
         Returns
         -------
-        shape_grads_physical: ndarray
+        shape_grads_physical : onp.ndarray
             (num_cells, num_quads, num_nodes, dim)  
-        JxW: ndarray
+        JxW : onp.ndarray
             (num_cells, num_quads)
         """
         assert self.shape_grads_ref.shape == (self.num_quads, self.num_nodes, self.dim)
         physical_coos = onp.take(self.points, self.cells, axis=0) # (num_cells, num_nodes, dim)
         # (num_cells, num_quads, num_nodes, dim, dim) -> (num_cells, num_quads, 1, dim, dim)
         jacobian_dx_deta = onp.sum(physical_coos[:, None, :, :, None] * self.shape_grads_ref[None, :, :, None, :], axis=2, keepdims=True)
         jacobian_det = onp.linalg.det(jacobian_dx_deta)[:, :, 0] # (num_cells, num_quads)
@@ -165,25 +151,25 @@
         JxW = jacobian_det * self.quad_weights[None, :]
         return shape_grads_physical, JxW
 
     def get_face_shape_grads(self, boundary_inds):
         """Face shape function gradients and JxW (for surface integral)
         Nanson's formula is used to map physical surface ingetral to reference domain
         Reference: https://en.wikiversity.org/wiki/Continuum_mechanics/Volume_change_and_area_change
-
+        
         Parameters
         ----------
-        boundary_inds: List[ndarray]
-            ndarray shape: (num_selected_faces, 2)
-
+        boundary_inds : List[onp.ndarray]
+            (num_selected_faces, 2)
+        
         Returns
-        ------- 
-        face_shape_grads_physical: ndarray
+        -------
+        face_shape_grads_physical : onp.ndarray
             (num_selected_faces, num_face_quads, num_nodes, dim)
-        nanson_scale: ndarray
+        nanson_scale : onp.ndarray
             (num_selected_faces, num_face_quads)
         """
         physical_coos = onp.take(self.points, self.cells, axis=0) # (num_cells, num_nodes, dim)
         selected_coos = physical_coos[boundary_inds[:, 0]] # (num_selected_faces, num_nodes, dim)
         selected_f_shape_grads_ref = self.face_shape_grads_ref[boundary_inds[:, 1]] # (num_selected_faces, num_face_quads, num_nodes, dim)
         selected_f_normals = self.face_normals[boundary_inds[:, 1]] # (num_selected_faces, dim)
 
@@ -202,133 +188,131 @@
         nanson_scale = onp.linalg.norm((selected_f_normals[:, None, None, :] @ jacobian_deta_dx)[:, :, 0, :], axis=-1)
         selected_weights = self.face_quad_weights[boundary_inds[:, 1]] # (num_selected_faces, num_face_quads)
         nanson_scale = nanson_scale * jacobian_det * selected_weights
         return face_shape_grads_physical, nanson_scale
 
     def get_physical_quad_points(self):
         """Compute physical quadrature points
- 
+        
         Returns
-        ------- 
-        physical_quad_points: ndarray
+        -------
+        physical_quad_points : onp.ndarray
             (num_cells, num_quads, dim) 
         """
         physical_coos = onp.take(self.points, self.cells, axis=0)
         # (1, num_quads, num_nodes, 1) * (num_cells, 1, num_nodes, dim) -> (num_cells, num_quads, dim) 
         physical_quad_points = onp.sum(self.shape_vals[None, :, :, None] * physical_coos[:, None, :, :], axis=2)
         return physical_quad_points
 
     def get_physical_surface_quad_points(self, boundary_inds):
         """Compute physical quadrature points on the surface
-
+        
         Parameters
         ----------
-        boundary_inds: List[ndarray]
+        boundary_inds : List[onp.ndarray]
             ndarray shape: (num_selected_faces, 2)
-
+        
         Returns
-        ------- 
-        physical_surface_quad_points: ndarray
+        -------
+        physical_surface_quad_points : ndarray
             (num_selected_faces, num_face_quads, dim) 
         """
         physical_coos = onp.take(self.points, self.cells, axis=0)
         selected_coos = physical_coos[boundary_inds[:, 0]] # (num_selected_faces, num_nodes, dim)
         selected_face_shape_vals = self.face_shape_vals[boundary_inds[:, 1]] # (num_selected_faces, num_face_quads, num_nodes)  
         # (num_selected_faces, num_face_quads, num_nodes, 1) * (num_selected_faces, 1, num_nodes, dim) -> (num_selected_faces, num_face_quads, dim) 
         physical_surface_quad_points = onp.sum(selected_face_shape_vals[:, :, :, None] * selected_coos[:, None, :, :], axis=2)
         return physical_surface_quad_points
 
     def Dirichlet_boundary_conditions(self, dirichlet_bc_info):
         """Indices and values for Dirichlet B.C. 
-
+        
         Parameters
         ----------
-        dirichlet_bc_info: [location_fns, vecs, value_fns]
-            location_fns: List[callable]
-                callable: a function that inputs a point (ndarray) and returns if the point satisfies the location condition
-            vecs: List[int]
-                integer value must be in the range of 0 to vec - 1, 
-                specifying which component of the (vector) variable to apply Dirichlet condition to
-            value_fns: List[callable]
-                callable: a function that inputs a point (ndarray) and returns the Dirichlet value
+        dirichlet_bc_info : [location_fns, vecs, value_fns]
 
         Returns
-        ------- 
-        node_inds_List: List[ndarray]
+        -------
+        node_inds_List : List[onp.ndarray]
             The ndarray ranges from 0 to num_total_nodes - 1
-        vec_inds_List: List[ndarray]
+        vec_inds_List : List[onp.ndarray]
             The ndarray ranges from 0 to to vec - 1
-        vals_List: List[ndarray]
+        vals_List : List[ndarray]
             Dirichlet values to be assigned
         """
-        location_fns, vecs, value_fns = dirichlet_bc_info
-        # TODO: add assertion for vecs, vecs must only contain 0 or 1 or 2, and must be integer
-        assert len(location_fns) == len(value_fns) and len(value_fns) == len(vecs)
         node_inds_list = []
         vec_inds_list = []
         vals_list = []
-        for i in range(len(location_fns)):
-            node_inds = onp.argwhere(jax.vmap(location_fns[i])(self.mesh.points)).reshape(-1)
-            vec_inds = onp.ones_like(node_inds, dtype=onp.int32)*vecs[i]
-            values = jax.vmap(value_fns[i])(self.mesh.points[node_inds].reshape(-1, self.dim)).reshape(-1)
-            node_inds_list.append(node_inds)
-            vec_inds_list.append(vec_inds)
-            vals_list.append(values)
+        if dirichlet_bc_info is not None:
+            location_fns, vecs, value_fns = dirichlet_bc_info
+            assert len(location_fns) == len(value_fns) and len(value_fns) == len(vecs)
+            for i in range(len(location_fns)):
+                node_inds = onp.argwhere(jax.vmap(location_fns[i])(self.mesh.points)).reshape(-1)
+                vec_inds = onp.ones_like(node_inds, dtype=onp.int32)*vecs[i]
+                values = jax.vmap(value_fns[i])(self.mesh.points[node_inds].reshape(-1, self.dim)).reshape(-1)
+                node_inds_list.append(node_inds)
+                vec_inds_list.append(vec_inds)
+                vals_list.append(values)
         return node_inds_list, vec_inds_list, vals_list
 
     def update_Dirichlet_boundary_conditions(self, dirichlet_bc_info):
         """Reset Dirichlet boundary conditions.
         Useful when a time-dependent problem is solved, and at each iteration the boundary condition needs to be updated.
+        
+        Parameters
+        ----------
+        dirichlet_bc_info : [location_fns, vecs, value_fns]
         """
-        # TODO: use getter and setter!
         self.node_inds_list, self.vec_inds_list, self.vals_list = self.Dirichlet_boundary_conditions(dirichlet_bc_info)
 
-    def periodic_boundary_conditions(self, periodic_bc_info):
-        """TODO: comment
-        """
-        location_fns_A, location_fns_B, mappings, vecs = periodic_bc_info
+    def periodic_boundary_conditions(self):
         p_node_inds_list_A = []
         p_node_inds_list_B = []
         p_vec_inds_list = []
-        for i in range(len(location_fns_A)):
-            node_inds_A = onp.argwhere(jax.vmap(location_fns_A[i])(self.mesh.points)).reshape(-1)
-            node_inds_B = onp.argwhere(jax.vmap(location_fns_B[i])(self.mesh.points)).reshape(-1)
-            points_set_A = self.mesh.points[node_inds_A]
-            points_set_B = self.mesh.points[node_inds_B]
-
-            EPS = 1e-5
-            node_inds_B_ordered = []
-            for node_ind in node_inds_A:
-                point_A = self.mesh.points[node_ind]
-                dist = onp.linalg.norm(mappings[i](point_A)[None, :] - points_set_B, axis=-1)
-                node_ind_B_ordered = node_inds_B[onp.argwhere(dist < EPS)].reshape(-1)
-                node_inds_B_ordered.append(node_ind_B_ordered)
-
-            node_inds_B_ordered = onp.array(node_inds_B_ordered).reshape(-1)
-            vec_inds = onp.ones_like(node_inds_A, dtype=onp.int32)*vecs[i]
-
-            p_node_inds_list_A.append(node_inds_A)
-            p_node_inds_list_B.append(node_inds_B_ordered)
-            p_vec_inds_list.append(vec_inds)
-            assert len(node_inds_A) == len(node_inds_B_ordered)
+        if self.periodic_bc_info is not None:
+            location_fns_A, location_fns_B, mappings, vecs = self.periodic_bc_info
+            for i in range(len(location_fns_A)):
+                node_inds_A = onp.argwhere(jax.vmap(location_fns_A[i])(self.mesh.points)).reshape(-1)
+                node_inds_B = onp.argwhere(jax.vmap(location_fns_B[i])(self.mesh.points)).reshape(-1)
+                points_set_A = self.mesh.points[node_inds_A]
+                points_set_B = self.mesh.points[node_inds_B]
+
+                EPS = 1e-5
+                node_inds_B_ordered = []
+                for node_ind in node_inds_A:
+                    point_A = self.mesh.points[node_ind]
+                    dist = onp.linalg.norm(mappings[i](point_A)[None, :] - points_set_B, axis=-1)
+                    node_ind_B_ordered = node_inds_B[onp.argwhere(dist < EPS)].reshape(-1)
+                    node_inds_B_ordered.append(node_ind_B_ordered)
+
+                node_inds_B_ordered = onp.array(node_inds_B_ordered).reshape(-1)
+                vec_inds = onp.ones_like(node_inds_A, dtype=onp.int32)*vecs[i]
+
+                p_node_inds_list_A.append(node_inds_A)
+                p_node_inds_list_B.append(node_inds_B_ordered)
+                p_vec_inds_list.append(vec_inds)
+                assert len(node_inds_A) == len(node_inds_B_ordered)
 
         return p_node_inds_list_A, p_node_inds_list_B, p_vec_inds_list
 
     def get_boundary_conditions_inds(self, location_fns):
         """Given location functions, compute which faces satisfy the condition. 
+        
         Parameters
         ----------
-        location_fns: list[callable]
-            callable: a function that inputs a point (ndarray) and returns if the point satisfies the location condition
+        location_fns : List[Callable]
+            Callable: a function that inputs a point (ndarray) and returns if the point satisfies the location condition
                       e.g., lambda x: np.isclose(x[0], 0.)
+        
         Returns
-        ------- 
-        boundary_inds_list: list[ndarray]
-            ndarray shape: (num_selected_faces, 2)
-            boundary_inds_list[k][i, j] returns the index of face j of cell i of surface k
+        -------
+        boundary_inds_list : List[onp.ndarray]
+            (num_selected_faces, 2)
+            boundary_inds_list[k][i, 0] returns the global cell index of the ith selected face of boundary subset k
+            boundary_inds_list[k][i, 1] returns the local face index of the ith selected face of boundary subset k
         """
         cell_points = onp.take(self.points, self.cells, axis=0) # (num_cells, num_nodes, dim)
         cell_face_points = onp.take(cell_points, self.face_inds, axis=1) # (num_cells, num_faces, num_face_nodes, dim)
         boundary_inds_list = []
         for i in range(len(location_fns)):
             vmap_location_fn = jax.vmap(location_fns[i])
             def on_boundary(cell_points):
@@ -336,105 +320,96 @@
                 return onp.all(boundary_flag)
             vvmap_on_boundary = jax.vmap(jax.vmap(on_boundary))
             boundary_flags = vvmap_on_boundary(cell_face_points)
             boundary_inds = onp.argwhere(boundary_flags) # (num_selected_faces, 2)
             boundary_inds_list.append(boundary_inds)
         return boundary_inds_list
 
-    def Neuman_boundary_conditions_vals(self, *internal_vars):
-        """Compute traction values on the face quadrature points.
-        TODO: comments not be correct. Merge into compute_Neumann_integral_vars
-
-        Parameters
-        ----------
-        neumann_value_fns: List[callable]
-            callable: a function that inputs a point (ndarray) and returns the value
-                      e.g., lambda x: x[0]**2
-        boundary_inds_list: List[ndarray]
-            ndarray shape: (num_selected_faces, 2)    
-
-        Returns
-        ------- 
-            traction_list: List[ndarray]
-            ndarray shape: (num_selected_faces, num_face_quads, vec)
-        """
-        traction_list = []
-        for i in range(len(self.neumann_value_fns)):
-            boundary_inds = self.neumann_boundary_inds_list[i]
-            # (num_cells, num_faces, num_face_quads, dim) -> (num_selected_faces, num_face_quads, dim)
-            subset_quad_points = self.get_physical_surface_quad_points(boundary_inds)
-            int_vars = [x[i] for x in internal_vars]
-            traction = jax.vmap(jax.vmap(self.neumann_value_fns[i]))(subset_quad_points, *int_vars) # (num_selected_faces, num_face_quads, vec)
-            assert len(traction.shape) == 3
-            traction_list.append(traction)
-        return traction_list
-
-    def compute_Neumann_integral_vars(self, *internal_vars):
+    def compute_Neumann_integral_vars(self, **internal_vars):
         """In the weak form, we have the Neumann integral: (traction, v) * ds, and this function computes this.
 
-        Parameters
-        ----------
-        neumann_bc_info: [location_fns, value_fns]
-            location_fns: List[callable]
-            value_fns: List[callable]
-
         Returns
         -------
-        integral: ndarray
+        integral: np.DeviceArray
             (num_total_nodes, vec)
         """
         integral = np.zeros((self.num_total_nodes, self.vec))
         if self.neumann_bc_info is not None:
-            # location_fns, value_fns = self.neumann_bc_info
-            integral = np.zeros((self.num_total_nodes, self.vec))
-            traction_list = self.Neuman_boundary_conditions_vals(*internal_vars)
             for i, boundary_inds in enumerate(self.neumann_boundary_inds_list):
-                traction = traction_list[i]
+                if 'neumann' in internal_vars.keys():
+                    int_vars = internal_vars['neumann'][i]
+                else:
+                    int_vars = ()
+                # (num_cells, num_faces, num_face_quads, dim) -> (num_selected_faces, num_face_quads, dim)
+                subset_quad_points = self.get_physical_surface_quad_points(boundary_inds)
+                # int_vars = [x[i] for x in internal_vars]
+                traction = jax.vmap(jax.vmap(self.neumann_value_fns[i]))(subset_quad_points, *int_vars) # (num_selected_faces, num_face_quads, vec)
+                assert len(traction.shape) == 3
                 _, nanson_scale = self.get_face_shape_grads(boundary_inds) # (num_selected_faces, num_face_quads)
                 # (num_faces, num_face_quads, num_nodes) ->  (num_selected_faces, num_face_quads, num_nodes)
                 v_vals = np.take(self.face_shape_vals, boundary_inds[:, 1], axis=0)
                 v_vals = np.repeat(v_vals[:, :, :, None], self.vec, axis=-1) # (num_selected_faces, num_face_quads, num_nodes, vec)
                 subset_cells = np.take(self.cells, boundary_inds[:, 0], axis=0) # (num_selected_faces, num_nodes)
                 # (num_selected_faces, num_nodes, vec) -> (num_selected_faces*num_nodes, vec)
                 int_vals = np.sum(v_vals * traction[:, :, None, :] * nanson_scale[:, :, None, None], axis=1).reshape(-1, self.vec) 
                 integral = integral.at[subset_cells.reshape(-1)].add(int_vals)   
         return integral
 
-    def compute_Neumann_integral(self):
-        # TODO: not necessarily override?
+    def compute_Neumann_boundary_inds(self):
         """Child class should override if internal variables exist
         """
-        return self.compute_Neumann_integral_vars()
-
-    def compute_body_force(self, source_info):
-        """In the weak form, we have (body_force, v) * dx, and this function computes this.
+        if self.neumann_bc_info is not None:
+            self.neumann_location_fns, self.neumann_value_fns = self.neumann_bc_info
+            if self.neumann_location_fns is not None:
+                self.neumann_boundary_inds_list = self.get_boundary_conditions_inds(self.neumann_location_fns)
 
-        Parameters
-        ----------
-        source_info: callable
-            A function that inputs a point (ndarray) and returns the body force at this point.
+    def compute_body_force_by_fn(self):
+        """In the weak form, we have (body_force, v) * dx, and this function computes this
 
         Returns
         -------
-        body_force: ndarray
+        body_force: np.DeviceArray
             (num_total_nodes, vec)
         """
         rhs = np.zeros((self.num_total_nodes, self.vec))
-        if source_info is not None:
-            body_force_fn = source_info
+        if self.source_info is not None:
+            body_force_fn = self.source_info
             physical_quad_points = self.get_physical_quad_points() # (num_cells, num_quads, dim) 
             body_force = jax.vmap(jax.vmap(body_force_fn))(physical_quad_points) # (num_cells, num_quads, vec) 
             assert len(body_force.shape) == 3
             v_vals = np.repeat(self.shape_vals[None, :, :, None], self.num_cells, axis=0) # (num_cells, num_quads, num_nodes, 1)
             v_vals = np.repeat(v_vals, self.vec, axis=-1) # (num_cells, num_quads, num_nodes, vec)
             # (num_cells, num_nodes, vec) -> (num_cells*num_nodes, vec)
             rhs_vals = np.sum(v_vals * body_force[:, :, None, :] * self.JxW[:, :, None, None], axis=1).reshape(-1, self.vec) 
             rhs = rhs.at[self.cells.reshape(-1)].add(rhs_vals) 
         return rhs
 
+    def compute_body_force_by_sol(self, sol, mass_map):
+        """In the weak form, we have (old_solution, v) * dx, and this function computes this
+        
+        Parameters
+        ----------
+        sol : np.DeviceArray
+            (num_total_nodes, vec)
+        mass_map : Callable
+            Transformation on sol
+        
+        Returns
+        -------
+        body_force : np.DeviceArray
+            (num_total_nodes, vec)
+        """
+        mass_kernel = self.get_mass_kernel(mass_map)
+        cells_sol = sol[self.cells] # (num_cells, num_nodes, vec)
+        val = jax.vmap(mass_kernel)(cells_sol, self.JxW) # (num_cells, num_nodes, vec)
+        val = val.reshape(-1, self.vec) # (num_cells*num_nodes, vec)
+        body_force = np.zeros_like(sol)
+        body_force = body_force.at[self.cells.reshape(-1)].add(val) 
+        return body_force
+
     def get_laplace_kernel(self, tensor_map):
         def laplace_kernel(cell_sol, cell_shape_grads, cell_v_grads_JxW, *cell_internal_vars):
             # (1, num_nodes, vec, 1) * (num_quads, num_nodes, 1, dim) -> (num_quads, num_nodes, vec, dim)
             u_grads = cell_sol[None, :, :, None] * cell_shape_grads[:, :, None, :] 
             u_grads = np.sum(u_grads, axis=1) # (num_quads, vec, dim)
             u_grads_reshape = u_grads.reshape(-1, self.vec, self.dim) # (num_quads, vec, dim) 
             # (num_quads, vec, dim) 
@@ -474,14 +449,26 @@
             laplace_internal_vars = internal_vars['laplace']
         else:
             laplace_internal_vars = ()
 
         return [mass_internal_vars, laplace_internal_vars]        
 
     def split_and_compute_cell(self, cells_sol, np_version, jac_flag, **internal_vars):
+        def value_and_jacrev(f, x):
+            y, pullback = jax.vjp(f, x)
+            basis = np.eye(len(y.reshape(-1)), dtype=y.dtype).reshape(-1, *y.shape)
+            jac, = jax.vmap(pullback)(basis)
+            return y, jac.reshape(self.num_nodes, self.vec, self.num_nodes, self.vec)
+
+        def value_and_jacfwd(f, x):
+            pushfwd = functools.partial(jax.jvp, f, (x,))
+            basis = np.eye(len(x.reshape(-1)), dtype=x.dtype).reshape(-1, *x.shape)
+            y, jac = jax.vmap(pushfwd, out_axes=(None, -1))((basis,))
+            return y, jac.reshape(self.num_nodes, self.vec, self.num_nodes, self.vec)
+
         def get_kernel_fn_cell():
             def kernel(cell_sol, cell_shape_grads, cell_JxW, cell_v_grads_JxW, cell_mass_internal_vars, cell_laplace_internal_vars):
                 if hasattr(self, 'get_mass_map'):
                     mass_kernel = self.get_mass_kernel(self.get_mass_map())
                     mass_val = mass_kernel(cell_sol, cell_JxW, *cell_mass_internal_vars)
                 else:
                     mass_val = 0.
@@ -491,55 +478,74 @@
                     laplace_val = laplace_kernel(cell_sol, cell_shape_grads, cell_v_grads_JxW, *cell_laplace_internal_vars)
                 else:
                     laplace_val = 0.
                 
                 return laplace_val + mass_val
 
             def kernel_jac(cell_sol, *args):
-                return jax.jacfwd(kernel)(cell_sol, *args)
+                kernel_partial = lambda cell_sol: kernel(cell_sol, *args)
+                return value_and_jacfwd(kernel_partial, cell_sol) # kernel(cell_sol, *args), jax.jacfwd(kernel)(cell_sol, *args)
 
             return kernel, kernel_jac
 
         kernel, kernel_jac = get_kernel_fn_cell()
         fn = kernel_jac if jac_flag else kernel
         vmap_fn = jax.jit(jax.vmap(fn))
         kernal_vars = self.unpack_kernels_vars(**internal_vars)
         num_cuts = 20
         if num_cuts > len(self.cells):
             num_cuts = len(self.cells)
         batch_size = len(self.cells) // num_cuts
         input_collection = [cells_sol, self.shape_grads, self.JxW, self.v_grads_JxW, *kernal_vars]
-        values = []
-        for i in range(num_cuts):
-            if i < num_cuts - 1:
-                input_col = jax.tree_map(lambda x: x[i*batch_size:(i + 1)*batch_size], input_collection)
-            else:
-                input_col = jax.tree_map(lambda x: x[i*batch_size:], input_collection)
 
-            val = vmap_fn(*input_col)
-            values.append(val)
+        if jac_flag:
+            values = []
+            jacs = []
+            for i in range(num_cuts):
+                if i < num_cuts - 1:
+                    input_col = jax.tree_map(lambda x: x[i*batch_size:(i + 1)*batch_size], input_collection)
+                else:
+                    input_col = jax.tree_map(lambda x: x[i*batch_size:], input_collection)
 
-        # np_version set to jax.numpy allows for auto diff, but uses GPU memory
-        # np_version set to ordinary numpy saves GPU memory, but can't use auto diff 
-        values = np_version.vstack(values)
-        return values
+                val, jac = vmap_fn(*input_col)
+
+                values.append(val)
+                jacs.append(jac)
+
+            # np_version set to jax.numpy allows for auto diff, but uses GPU memory
+            # np_version set to ordinary numpy saves GPU memory, but can't use auto diff 
+            values = np_version.vstack(values)
+            jacs = np_version.vstack(jacs)
+            return values, jacs
+        else:
+            values = []
+            for i in range(num_cuts):
+                if i < num_cuts - 1:
+                    input_col = jax.tree_map(lambda x: x[i*batch_size:(i + 1)*batch_size], input_collection)
+                else:
+                    input_col = jax.tree_map(lambda x: x[i*batch_size:], input_collection)
+
+                val = vmap_fn(*input_col)
+                values.append(val)
+            values = np_version.vstack(values)
+            return values
 
     def compute_face(self, cells_sol, np_version, jac_flag):
         def get_kernel_fn_face(cauchy_map): 
             def kernel(cell_sol, face_shape_vals, face_nanson_scale):
                 cauchy_kernel = self.get_cauchy_kernel(cauchy_map)
                 val = cauchy_kernel(cell_sol, face_shape_vals, face_nanson_scale)
                 return val
 
             def kernel_jac(cell_sol, *args):
                 return jax.jacfwd(kernel)(cell_sol, *args)
 
-            return kernel, kernel_jac        
+            return kernel, kernel_jac
 
-        # TODO: Better to move the following to __init__ function
+        # TODO: Better to move the following to __init__ function?
         location_fns, value_fns = self.cauchy_bc_info
         boundary_inds_list = self.get_boundary_conditions_inds(location_fns)
         values = []
         selected_cells = []
         for i, boundary_inds in enumerate(boundary_inds_list):
             selected_cell_sols = cells_sol[boundary_inds[:, 0]] # (num_selected_faces, num_nodes, vec))
             selected_face_shape_vals = self.face_shape_vals[boundary_inds[:, 1]] # (num_selected_faces, num_face_quads, num_nodes)
@@ -554,58 +560,157 @@
         values = np_version.vstack(values)
         selected_cells = onp.vstack(selected_cells)
 
         assert len(values) == len(selected_cells)
 
         return values, selected_cells
 
-    def compute_residual_vars(self, sol, **internal_vars):
-        res = np.zeros_like(sol)
-        cells_sol = sol[self.cells] # (num_cells, num_nodes, vec)
-        weak_form = self.split_and_compute_cell(cells_sol, np, False, **internal_vars) # (num_cells, num_nodes, vec)
+    def convert_from_dof_to_quad(self, sol):
+        """Obtain quad values from nodal solution
+
+        Parameters
+        ----------
+        sol : np.DeviceArray
+            (num_total_nodes, vec)
+
+        Returns
+        -------
+        u : np.DeviceArray
+            (num_cells, num_quads, vec)
+        """
+        # (num_total_nodes, vec) -> (num_cells, num_nodes, vec)
+        cells_sol = sol[self.cells] 
+        # (num_cells, 1, num_nodes, vec) * (1, num_quads, num_nodes, 1) -> (num_cells, num_quads, num_nodes, vec) -> (num_cells, num_quads, vec)
+        u = np.sum(cells_sol[:, None, :, :] * self.shape_vals[None, :, :, None], axis=2)
+        return u
+
+    def convert_neumann_from_dof(self, sol, index):
+        """Obtain surface solution from nodal solution
+        
+        Parameters
+        ----------
+        sol : np.DeviceArray
+            (num_total_nodes, vec)
+        index : int
+
+        Returns
+        -------
+        u : np.DeviceArray
+            (num_selected_faces, num_face_quads, vec) 
+        """
+        cells_old_sol = sol[self.cells] # (num_cells, num_nodes, vec)
+        boundary_inds = self.neumann_boundary_inds_list[index]
+        selected_cell_sols = cells_old_sol[boundary_inds[:, 0]] # (num_selected_faces, num_nodes, vec))
+        selected_face_shape_vals = self.face_shape_vals[boundary_inds[:, 1]] # (num_selected_faces, num_face_quads, num_nodes)
+        # (num_selected_faces, 1, num_nodes, vec) * (num_selected_faces, num_face_quads, num_nodes, 1) -> (num_selected_faces, num_face_quads, vec) 
+        u = np.sum(selected_cell_sols[:, None, :, :] * selected_face_shape_vals[:, :, :, None], axis=2)
+        return u
+
+    def sol_to_grad(self, sol):
+        """Obtain solution gradient from nodal solution
+        
+        Parameters
+        ----------
+        sol : np.DeviceArray
+            (num_total_nodes, vec)
+        index : int
+
+        Returns
+        -------
+        u_grads : np.DeviceArray
+            (num_cells, num_quads, vec, dim)
+        """
+        # (num_cells, 1, num_nodes, vec, 1) * (num_cells, num_quads, num_nodes, 1, dim) -> (num_cells, num_quads, num_nodes, vec, dim) 
+        u_grads = np.take(sol, self.cells, axis=0)[:, None, :, :, None] * self.shape_grads[:, :, :, None, :] 
+        u_grads = np.sum(u_grads, axis=2) # (num_cells, num_quads, vec, dim)
+        return u_grads
+
+    def compute_residual_vars_helper(self, sol, weak_form, **internal_vars):
+        res = np.zeros((self.num_total_nodes, self.vec))
         weak_form = weak_form.reshape(-1, self.vec) # (num_cells*num_nodes, vec)
         res = res.at[self.cells.reshape(-1)].add(weak_form) 
 
         if self.cauchy_bc_info is not None:
+            cells_sol = sol[self.cells]
             values, selected_cells = self.compute_face(cells_sol, np, False)
             values = values.reshape(-1, self.vec)
             res = res.at[selected_cells.reshape(-1)].add(values) 
 
-        self.neumann = self.compute_Neumann_integral()
+        self.body_force = self.compute_body_force_by_fn()
+        if 'body' in internal_vars.keys():
+            self.body_force = self.compute_body_force_by_sol(internal_vars['body'], self.get_body_map())
 
-        res = res - self.body_force - self.neumann
-        return res 
+        self.neumann = self.compute_Neumann_integral_vars(**internal_vars)    
 
-    def compute_residual(self, sol):
-        """Child class should override if internal variables exist
-        """
-        return self.compute_residual_vars(sol)
+        res = res - self.body_force - self.neumann
+        return res
 
-    def newton_vars(self, sol, **internal_vars):
-        print(f"Update solution, internal variable...")
+    def compute_residual_vars(self, sol, **internal_vars):
+        print(f"Compute cell residual...")
+        cells_sol = sol[self.cells] # (num_cells, num_nodes, vec)
+        weak_form = self.split_and_compute_cell(cells_sol, np, False, **internal_vars) # (num_cells, num_nodes, vec)
+        return self.compute_residual_vars_helper(sol, weak_form, **internal_vars)
+    
+    def compute_newton_vars(self, sol, **internal_vars):
+        print(f"Compute cell Jacobian and cell residual...")
         cells_sol = sol[self.cells] # (num_cells, num_nodes, vec)
-        print(f"Compute cell Jacobian...")
-        # (num_cells, num_nodes, vec, num_nodes, vec)
-        cells_jac = self.split_and_compute_cell(cells_sol, onp, True, **internal_vars)
+        # (num_cells, num_nodes, vec), (num_cells, num_nodes, vec, num_nodes, vec)
+        weak_form, cells_jac = self.split_and_compute_cell(cells_sol, onp, True, **internal_vars)
         V = cells_jac.reshape(-1)
         inds = (self.vec * self.cells[:, :, None] + onp.arange(self.vec)[None, None, :]).reshape(len(self.cells), -1)
         I = onp.repeat(inds[:, :, None], self.num_nodes*self.vec, axis=2).reshape(-1)
         J = onp.repeat(inds[:, None, :], self.num_nodes*self.vec, axis=1).reshape(-1)
-        # print(f"type(V) = {type(V)}, type(I) = {type(I)}, type(J) = {type(J)}")
         self.I = I
         self.J = J
         self.V = V
 
         if self.cauchy_bc_info is not None:
             D_face, selected_cells = self.compute_face(cells_sol, onp, True)
             V_face = D_face.reshape(-1)
             inds_face = (self.vec * selected_cells[:, :, None] + onp.arange(self.vec)[None, None, :]).reshape(len(selected_cells), -1)
             I_face = onp.repeat(inds_face[:, :, None], self.num_nodes*self.vec, axis=2).reshape(-1)
             J_face = onp.repeat(inds_face[:, None, :], self.num_nodes*self.vec, axis=1).reshape(-1)
             self.I = onp.hstack((self.I, I_face))
             self.J = onp.hstack((self.J, J_face))
             self.V = onp.hstack((self.V, V_face))
 
+        return self.compute_residual_vars_helper(sol, weak_form, **internal_vars) 
+
+    def compute_residual(self, sol):
+        return self.compute_residual_vars(sol, **self.internal_vars)
+
     def newton_update(self, sol):
-        """Child class should override if internal variables exist
+        return self.compute_newton_vars(sol, **self.internal_vars)
+
+    def set_params(self, params):
+        """Used for solving inverse problems.
         """
-        return self.newton_vars(sol)
+        raise NotImplementedError("Child class must implement this function!")
+
+    def print_BC_info(self):
+        """Print boundary condition information for debugging purposes.
+        """
+        if hasattr(self, 'neumann_boundary_inds_list'):
+            print(f"\n\n### Neumann B.C. is specified")
+            for i in range(len(self.neumann_boundary_inds_list)):
+                print(f"\nNeumann Boundary part {i + 1} information:")
+                print(self.neumann_boundary_inds_list[i]) 
+                print(f"Array.shape = (num_selected_faces, 2) = {self.neumann_boundary_inds_list[i].shape}")
+                print(f"Interpretation:")
+                print(f"    Array[i, 0] returns the global cell index of the ith selected face")
+                print(f"    Array[i, 1] returns the local face index of the ith selected face")
+        else:
+            print(f"\n\n### No Neumann B.C. found.")
+
+        if len(self.node_inds_list) != 0:
+            print(f"\n\n### Dirichlet B.C. is specified")
+            for i in range(len(self.node_inds_list)):
+                print(f"\nDirichlet Boundary part {i + 1} information:")
+                bc_array = onp.stack([self.node_inds_list[i], self.vec_inds_list[i], self.vals_list[i]]).T
+                print(bc_array)
+                print(f"Array.shape = (num_selected_dofs, 3) = {bc_array.shape}")
+                print(f"Interpretation:")
+                print(f"    Array[i, 0] returns the node index of the ith selected dof")
+                print(f"    Array[i, 1] returns the vec index of the ith selected dof")
+                print(f"    Array[i, 2] returns the value assigned to ith selected dof")
+        else:
+            print(f"\n\n### No Dirichlet B.C. found.")
```

### Comparing `jax-am-0.0.2/jax_am/fem/generate_mesh.py` & `jax-am-0.0.3/jax_am/fem/generate_mesh.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,54 +1,82 @@
 import os
 import gmsh
 import numpy as onp
 import meshio
 
+from jax_am.fem.basis import get_elements
+
 
 class Mesh():
     """A custom mesh manager might be better than just use third-party packages like meshio?
     """
     def __init__(self, points, cells):
         # TODO: Assert that cells must have correct orders
         # TODO: first cells, then points?
         self.points = points
         self.cells = cells
 
 
-def get_meshio_cell_type(ele_type, lag_order):
+def check_mesh_TET4(points, cells):
+    # TODO
+    def quality(pts):
+        p1, p2, p3, p4 = pts
+        v1 = p2 - p1
+        v2 = p3 - p1
+        v12 = np.cross(v1, v2)
+        v3 = p4 - p1
+        return np.dot(v12, v3)
+    qlts = jax.vmap(quality)(points[cells])
+    return qlts
+
+
+def get_meshio_cell_type(ele_type):
     """Reference:
     https://github.com/nschloe/meshio/blob/9dc6b0b05c9606cad73ef11b8b7785dd9b9ea325/src/meshio/xdmf/common.py#L36
     """
-    if ele_type == 'tetrahedron' and lag_order == 1:
+    if ele_type == 'TET4':
         cell_type = 'tetra'
-    elif ele_type == 'tetrahedron' and lag_order == 2:
+    elif ele_type == 'TET10':
         cell_type = 'tetra10'
-    elif ele_type == 'hexahedron' and lag_order == 1:
+    elif ele_type == 'HEX8':
         cell_type = 'hexahedron'
-    elif ele_type == 'hexahedron' and lag_order == 2:
+    elif ele_type == 'HEX27':
         cell_type = 'hexahedron27'
-    elif ele_type == 'triangle' and lag_order == 1:
+    elif  ele_type == 'HEX20':
+        cell_type = 'hexahedron20'
+    elif ele_type == 'TRI3':
         cell_type = 'triangle'
-    elif ele_type == 'triangle' and lag_order == 2:
+    elif ele_type == 'TRI6':
         cell_type = 'triangle6'
+    elif ele_type == 'QUAD4':
+        cell_type = 'quad'
+    elif ele_type == 'QUAD8':
+        cell_type = 'quad8'
     else:
         raise NotImplementedError
     return cell_type
 
 
-def box_mesh(Nx, Ny, Nz, Lx, Ly, Lz, data_dir, ele_type='hexahedron', lag_order=1):
+def box_mesh(Nx, Ny, Nz, Lx, Ly, Lz, data_dir, ele_type='HEX8'):
     """References:
     https://gitlab.onelab.info/gmsh/gmsh/-/blob/master/examples/api/hex.py
     https://gitlab.onelab.info/gmsh/gmsh/-/blob/gmsh_4_7_1/tutorial/python/t1.py
     https://gitlab.onelab.info/gmsh/gmsh/-/blob/gmsh_4_7_1/tutorial/python/t3.py
+
+    Accepts ele_type = 'HEX8', 'TET4' or 'TET10'
     """
-    cell_type = get_meshio_cell_type(ele_type, lag_order)
+
+    assert ele_type != 'HEX20', f"gmsh cannot produce HEX20 mesh?"
+
+    cell_type = get_meshio_cell_type(ele_type)
+    _, _, _, _, degree, _ = get_elements(ele_type)
+
     msh_dir = os.path.join(data_dir, 'msh')
     os.makedirs(msh_dir, exist_ok=True)
-    msh_file = os.path.join(msh_dir, 'box_order_2.msh')
+    msh_file = os.path.join(msh_dir, 'box.msh')
 
     offset_x = 0.
     offset_y = 0.
     offset_z = 0.
     domain_x = Lx
     domain_y = Ly
     domain_z = Lz
@@ -64,15 +92,15 @@
     p = gmsh.model.geo.addPoint(offset_x, offset_y, offset_z)
     l = gmsh.model.geo.extrude([(0, p)], domain_x, 0, 0, [Nx], [1])
     s = gmsh.model.geo.extrude([l[1]], 0, domain_y, 0, [Ny], [1], recombine=Rec2d)
     v = gmsh.model.geo.extrude([s[1]], 0, 0, domain_z, [Nz], [1], recombine=Rec3d)
 
     gmsh.model.geo.synchronize()
     gmsh.model.mesh.generate(3)
-    gmsh.model.mesh.setOrder(lag_order)
+    gmsh.model.mesh.setOrder(degree)
     gmsh.write(msh_file)
     gmsh.finalize()
       
     mesh = meshio.read(msh_file)
     points = mesh.points # (num_total_nodes, dim)
     cells =  mesh.cells_dict[cell_type] # (num_cells, num_nodes)
     out_mesh = meshio.Mesh(points=points, cells={cell_type: cells})
```

### Comparing `jax-am-0.0.2/jax_am/fem/models.py` & `jax-am-0.0.3/jax_am/fem/models.py`

 * *Files 4% similar despite different names*

```diff
@@ -65,15 +65,14 @@
         traction = surface_fn(u_grads_face) # (num_selected_faces, num_face_quads, vec)
         # (num_selected_faces, num_face_quads, vec) * (num_selected_faces, num_face_quads, 1)
         int_val = np.sum(traction * nanson_scale[:, :, None], axis=(0, 1))
         return int_val    
 
     def compute_traction(self, location_fn, sol):
         """For post-processing only
-        TODO: duplicated code
         """
         stress = self.get_tensor_map()
         vmap_stress = jax.vmap(stress)
         def traction_fn(u_grads):
             """
             Returns
             ------- 
@@ -137,31 +136,27 @@
         return first_PK_stress
 
 
 class Plasticity(Mechanics):
     def custom_init(self):
         self.epsilons_old = onp.zeros((len(self.cells), self.num_quads, self.vec, self.dim))
         self.sigmas_old = onp.zeros_like(self.epsilons_old)
+        self.internal_vars = {'laplace': [self.sigmas_old, self.epsilons_old]}
 
     def get_tensor_map(self):
         _, stress_return_map = self.get_maps()
         return stress_return_map
 
-    def newton_update(self, sol):
-        return self.newton_vars(sol, laplace=[self.sigmas_old, self.epsilons_old])
-
-    def compute_residual(self, sol):
-        return self.compute_residual_vars(sol, laplace=[self.sigmas_old, self.epsilons_old])
-
     def get_maps(self):
-        EPS = 1e-10
-        # TODO
         def safe_sqrt(x):  
-            safe_x = np.where(x > 0., x, EPS)
-            return np.sqrt(safe_x)
+            safe_x = np.where(x > 0., np.sqrt(x), 0.)
+            return safe_x
+
+        def safe_divide(x, y):
+            return np.where(y == 0., 0., x/y)
 
         def strain(u_grad):
             epsilon = 0.5*(u_grad + u_grad.T)
             return epsilon
 
         def stress(epsilon):
             E = 70e3
@@ -172,24 +167,19 @@
             return sigma
 
         def stress_return_map(u_grad, sigma_old, epsilon_old):
             sig0 = 250.
             epsilon_crt = strain(u_grad)
             epsilon_inc = epsilon_crt - epsilon_old
             sigma_trial = stress(epsilon_inc) + sigma_old
-
             s_dev = sigma_trial - 1./self.dim*np.trace(sigma_trial)*np.eye(self.dim)
-
-            # s_norm = np.sqrt(3./2.*np.sum(s_dev*s_dev))
             s_norm = safe_sqrt(3./2.*np.sum(s_dev*s_dev))
-
             f_yield = s_norm - sig0
             f_yield_plus = np.where(f_yield > 0., f_yield, 0.)
-            # TODO
-            sigma = sigma_trial - f_yield_plus*s_dev/(s_norm + EPS)
+            sigma = sigma_trial - safe_divide(f_yield_plus*s_dev, s_norm)
             return sigma
 
         return strain, stress_return_map
 
     def stress_strain_fns(self):
         strain, stress_return_map = self.get_maps()
         vmap_strain = jax.vmap(jax.vmap(strain))
@@ -199,14 +189,15 @@
     def update_stress_strain(self, sol):
         # (num_cells, 1, num_nodes, vec, 1) * (num_cells, num_quads, num_nodes, 1, dim) -> (num_cells, num_quads, num_nodes, vec, dim) 
         u_grads = np.take(sol, self.cells, axis=0)[:, None, :, :, None] * self.shape_grads[:, :, :, None, :] 
         u_grads = np.sum(u_grads, axis=2) # (num_cells, num_quads, vec, dim)
         vmap_strain, vmap_stress_rm = self.stress_strain_fns()
         self.sigmas_old = vmap_stress_rm(u_grads, self.sigmas_old, self.epsilons_old)
         self.epsilons_old = vmap_strain(u_grads)
+        self.internal_vars = {'laplace': [self.sigmas_old, self.epsilons_old]}
 
     def compute_avg_stress(self):
         """For post-processing only
         """
         # num_cells*num_quads, vec, dim) * (num_cells*num_quads, 1, 1)
         sigma = np.sum(self.sigmas_old.reshape(-1, self.vec, self.dim) * self.JxW.reshape(-1)[:, None, None], 0)
         vol = np.sum(self.JxW)
```

### Comparing `jax-am-0.0.2/jax_am/fem/solver.py` & `jax-am-0.0.3/jax_am/fem/solver.py`

 * *Files 20% similar despite different names*

```diff
@@ -2,36 +2,80 @@
 import jax.numpy as np
 import numpy as onp
 from jax.experimental.sparse import BCOO
 import scipy
 import time
 from functools import partial
 
+import petsc4py
+# petsc4py.init()
+from petsc4py import PETSc
+
+
+################################################################################
+# PETSc linear solver or JAX linear solver
+
+def petsc_solve(A, b, ksp_type, pc_type):
+    rhs = PETSc.Vec().createSeq(len(b))
+    rhs.setValues(range(len(b)), onp.array(b))
+    ksp = PETSc.KSP().create() 
+    ksp.setOperators(A)
+    ksp.setFromOptions()
+    ksp.setType(ksp_type)
+    ksp.pc.setType(pc_type)
+    print (f'PETSc - Solving with ksp_type = {ksp.getType()}, pc = {ksp.pc.getType()}') 
+    x = PETSc.Vec().createSeq(len(b))
+    ksp.solve(rhs, x) 
+
+    # Verify convergence
+    y = PETSc.Vec().createSeq(len(b))
+    A.mult(x, y)
+    err = np.linalg.norm(y.getArray() - rhs.getArray())
+    assert err < 0.1, f"PETSc linear solver failed to converge with err = {err}"
+
+    return x.getArray()
+
+
+def jax_solve(problem, A_fn, b, x0, precond):
+    pc = get_jacobi_precond(jacobi_preconditioner(problem)) if precond else None
+    x, info = jax.scipy.sparse.linalg.bicgstab(A_fn, b, x0=x0, M=pc, tol=1e-10, atol=1e-10, maxiter=10000)
+
+    # Verify convergence
+    err = np.linalg.norm(A_fn(x) - b)
+    print(f"JAX scipy linear solve res = {err}")
+    assert err < 0.1, f"JAX linear solver failed to converge with err = {err}"
+    return x
+
 
 ################################################################################
 # "row elimination" solver
 
+def apply_bc_vec(res_vec, dofs, problem):
+    sol = dofs.reshape((problem.num_total_nodes, problem.vec))
+    res = res_vec.reshape(sol.shape)
+    for i in range(len(problem.node_inds_list)):
+        res = (res.at[problem.node_inds_list[i], problem.vec_inds_list[i]].set
+               (sol[problem.node_inds_list[i], problem.vec_inds_list[i]], unique_indices=True))
+        res = res.at[problem.node_inds_list[i], problem.vec_inds_list[i]].add(-problem.vals_list[i])
+    return res.reshape(-1)
+
+
 def apply_bc(res_fn, problem):
     def A_fn(dofs):
         """Apply Dirichlet boundary conditions
         """
-        sol = dofs.reshape((problem.num_total_nodes, problem.vec))
-        res = res_fn(dofs).reshape(sol.shape)
-        for i in range(len(problem.node_inds_list)):
-            res = (res.at[problem.node_inds_list[i], problem.vec_inds_list[i]].set
-                   (sol[problem.node_inds_list[i], problem.vec_inds_list[i]], unique_indices=True))
-            res = res.at[problem.node_inds_list[i], problem.vec_inds_list[i]].add(-problem.vals_list[i])
-        return res.reshape(-1)
+        res_vec = res_fn(dofs)
+        return apply_bc_vec(res_vec, dofs, problem)
     return A_fn
 
 
-def row_elimination(res_fn, problem):
+def row_elimination(fn, problem):
     def fn_dofs_row(dofs):
         sol = dofs.reshape((problem.num_total_nodes, problem.vec))
-        res = res_fn(dofs).reshape(sol.shape)
+        res = fn(dofs).reshape(sol.shape)
         for i in range(len(problem.node_inds_list)):
             res = (res.at[problem.node_inds_list[i], problem.vec_inds_list[i]].set
                    (sol[problem.node_inds_list[i], problem.vec_inds_list[i]], unique_indices=True))
         return res.reshape(-1)
     return fn_dofs_row
 
 
@@ -45,23 +89,41 @@
 def assign_ones_bc(dofs, problem):
     sol = dofs.reshape((problem.num_total_nodes, problem.vec))
     for i in range(len(problem.node_inds_list)):
         sol = sol.at[problem.node_inds_list[i], problem.vec_inds_list[i]].set(1.)
     return sol.reshape(-1)
 
 
+def assign_zeros_bc(dofs, problem):
+    sol = dofs.reshape((problem.num_total_nodes, problem.vec))
+    for i in range(len(problem.node_inds_list)):
+        sol = sol.at[problem.node_inds_list[i], problem.vec_inds_list[i]].set(0.)
+    return sol.reshape(-1)
+
+
+def copy_bc(dofs, problem):
+    sol = dofs.reshape((problem.num_total_nodes, problem.vec))
+    new_sol = np.zeros_like(sol)
+    for i in range(len(problem.node_inds_list)):
+        new_sol = (new_sol.at[problem.node_inds_list[i], problem.vec_inds_list[i]].set(sol[problem.node_inds_list[i], 
+            problem.vec_inds_list[i]]))
+    return new_sol.reshape(-1)
+
+
 def get_flatten_fn(fn_sol, problem):
     def fn_dofs(dofs):
         sol = dofs.reshape((problem.num_total_nodes, problem.vec))
         val_sol = fn_sol(sol)
         return val_sol.reshape(-1)
     return fn_dofs
 
 
 def get_A_fn_linear_fn(dofs, fn):
+    """Not quite used.
+    """
     def A_fn_linear_fn(inc):
         primals, tangents = jax.jvp(fn, (dofs,), (inc,))
         return tangents
     return A_fn_linear_fn
 
 
 def get_A_fn_linear_fn_JFNK(dofs, fn):
@@ -74,15 +136,15 @@
     def A_fn_linear_fn(inc):
         EPS = 1e-3
         return (fn(dofs + EPS*inc) - fn(dofs))/EPS
     return A_fn_linear_fn
 
 
 def operator_to_matrix(operator_fn, problem):
-    """Only used for debugging purpose.
+    """Only used for when debugging.
     Can be used to print the matrix, check the conditional number, etc.
     """
     J = jax.jacfwd(operator_fn)(np.zeros(problem.num_total_nodes*problem.vec))
     return J
 
 
 def jacobi_preconditioner(problem):
@@ -106,93 +168,127 @@
         print(f"{A_fn(test_vec)[ind]}, {jacobi[ind]}, ratio = {A_fn(test_vec)[ind]/jacobi[ind]}")
 
     print(f"test jacobi preconditioner")
     print(f"np.min(jacobi) = {np.min(jacobi)}, np.max(jacobi) = {np.max(jacobi)}")
     print(f"finish jacobi preconditioner")
  
 
-def linear_guess_solve(problem, A_fn, precond):
-    b = np.zeros((problem.num_total_nodes, problem.vec))
+def linear_guess_solve(problem, A_fn, precond, use_petsc):
+    print(f"Linear guess solve...")
+    # b = np.zeros((problem.num_total_nodes, problem.vec))
+    b = problem.body_force + problem.neumann
     b = assign_bc(b, problem)
-    pc = get_jacobi_precond(jacobi_preconditioner(problem)) if precond else None
-    dofs, info = jax.scipy.sparse.linalg.bicgstab(A_fn, b, x0=b, M=pc, tol=1e-10, atol=1e-10, maxiter=10000)
+    if use_petsc:
+        dofs = petsc_solve(A_fn, b, 'bcgsl', 'ilu')
+    else:
+        dofs = jax_solve(problem, A_fn, b, b, precond)
     return dofs
 
 
-def linear_incremental_solver(problem, res_fn, A_fn, dofs, precond):
-    """
-    Lift solver
-    dofs must already satisfy Dirichlet boundary conditions
+def linear_incremental_solver(problem, res_vec, A_fn, dofs, precond, use_petsc):
+    """Lift solver
     """
-    b = -res_fn(dofs)
-    pc = get_jacobi_precond(jacobi_preconditioner(problem)) if precond else None
-    inc, info = jax.scipy.sparse.linalg.bicgstab(A_fn, b, x0=None, M=pc, tol=1e-10, atol=1e-10, maxiter=10000) # bicgstab
-    dofs = dofs + inc
-    return dofs
+    print(f"Solving linear system with lift solver...")
+    b = -res_vec
 
+    if use_petsc:
+        inc = petsc_solve(A_fn, b, 'bcgsl', 'ilu')
+    else:
+        x0_1 = assign_bc(np.zeros_like(b), problem) 
+        x0_2 = copy_bc(dofs, problem)
+        x0 = x0_1 - x0_2
+        inc = jax_solve(problem, A_fn, b, x0, precond)
 
-def compute_residual_val(res_fn, dofs):
-   res_vec = res_fn(dofs)
-   res_val = np.linalg.norm(res_vec)
-   return res_val
+    dofs = dofs + inc
+    return dofs
 
 
-def get_A_fn(problem):
+def get_A_fn(problem, use_petsc):
     print(f"Creating sparse matrix with scipy...")
-    A_sp_scipy = scipy.sparse.csc_array((problem.V, (problem.I, problem.J)), shape=(problem.num_total_dofs, problem.num_total_dofs))
-    print(f"Creating sparse matrix from scipy using JAX BCOO...")
+    A_sp_scipy = scipy.sparse.csr_array((problem.V, (problem.I, problem.J)), shape=(problem.num_total_dofs, problem.num_total_dofs))
+    # print(f"Creating sparse matrix from scipy using JAX BCOO...")
     A_sp = BCOO.from_scipy_sparse(A_sp_scipy).sort_indices()
-    print(f"self.A_sp.data.shape = {A_sp.data.shape}")
-    print(f"Global sparse matrix takes about {A_sp.data.shape[0]*8*3/2**30} G memory to store.")
+    # print(f"Global sparse matrix takes about {A_sp.data.shape[0]*8*3/2**30} G memory to store.")
     problem.A_sp_scipy = A_sp_scipy
 
     def compute_linearized_residual(dofs):
         return A_sp @ dofs
 
-    return compute_linearized_residual
+    if use_petsc:
+        A = PETSc.Mat().createAIJ(size=A_sp_scipy.shape, csr=(A_sp_scipy.indptr, A_sp_scipy.indices, A_sp_scipy.data))
+        for i in range(len(problem.node_inds_list)):
+            row_inds = onp.array(problem.node_inds_list[i]*problem.vec + problem.vec_inds_list[i], dtype=onp.int32)
+            A.zeroRows(row_inds)
+    else:
+        A = row_elimination(compute_linearized_residual, problem)
+
+    return A
+
+
+def solver_row_elimination(problem, linear, precond, initial_guess, use_petsc):
+    """The solver imposes Dirichlet B.C. with "row elimination" method.
+
+    Some memo:
 
+    res(u) = D*r(u) + (I - D)u - u_b
+    D = [[1 0 0 0]
+         [0 1 0 0]
+         [0 0 0 0]
+         [0 0 0 1]]
+    I = [[1 0 0 0]
+         [0 1 0 0]
+         [0 0 1 0]
+         [0 0 0 1]
+    A_fn = d(res)/d(u) = D*dr/du + (I - D)
 
-def solver_row_elimination(problem, linear=False, precond=True):
-    """Imposing Dirichlet B.C. with "row elimination" method.
+    The function newton_update computes r(u) and dr/du
     """
     print(f"Calling the row elimination solver for imposing Dirichlet B.C.")
     print("Start timing")
     start = time.time()
+    sol_shape = (problem.num_total_nodes, problem.vec)
+    dofs = np.zeros(sol_shape).reshape(-1)
 
-    sol = np.zeros((problem.num_total_nodes, problem.vec))
-    dofs = sol.reshape(-1)
+    def newton_update_helper(dofs):
+        res_vec = problem.newton_update(dofs.reshape(sol_shape)).reshape(-1)
+        res_vec = apply_bc_vec(res_vec, dofs, problem)
+        A_fn = get_A_fn(problem, use_petsc)
+        return res_vec, A_fn
 
-    res_fn = problem.compute_residual
-    res_fn = get_flatten_fn(res_fn, problem)
-    res_fn = apply_bc(res_fn, problem) 
-
-    problem.newton_update(dofs.reshape(sol.shape))
-    A_fn = get_A_fn(problem)
-    A_fn = row_elimination(A_fn, problem)
-
-    # TODO: more notes here
-    # TODO: detect np.nan and assert
     if linear:
         dofs = assign_bc(dofs, problem)
-        dofs = linear_incremental_solver(problem, res_fn, A_fn, dofs, precond)
+        res_vec, A_fn = newton_update_helper(dofs)
+        dofs = linear_incremental_solver(problem, res_vec, A_fn, dofs, precond, use_petsc)
+
+
+        res_vec, A_fn = newton_update_helper(dofs)
+        res_val = np.linalg.norm(res_vec)
+        print(f"Linear solve, res l_2 = {res_val}")
+
     else:
-        dofs = linear_guess_solve(problem, A_fn, precond)
-        res_val = compute_residual_val(res_fn, dofs)
+        if initial_guess is None:
+            res_vec, A_fn = newton_update_helper(dofs)
+            dofs = linear_guess_solve(problem, A_fn, precond, use_petsc)
+        else:
+            dofs = initial_guess.reshape(-1)
+
+        res_vec, A_fn = newton_update_helper(dofs)
+        res_val = np.linalg.norm(res_vec)
         print(f"Before, res l_2 = {res_val}") 
         tol = 1e-6
         while res_val > tol:
-            problem.newton_update(dofs.reshape(sol.shape))
-            A_fn = get_A_fn(problem)
-            A_fn = row_elimination(A_fn, problem)            
-            dofs = linear_incremental_solver(problem, res_fn, A_fn, dofs, precond)
+            dofs = linear_incremental_solver(problem, res_vec, A_fn, dofs, precond, use_petsc)
+            res_vec, A_fn = newton_update_helper(dofs)
             # test_jacobi_precond(problem, jacobi_preconditioner(problem, dofs), A_fn)
-            res_val = compute_residual_val(res_fn, dofs)
+            res_val = np.linalg.norm(res_vec)
             print(f"res l_2 = {res_val}") 
-
-    sol = dofs.reshape(sol.shape)
+        
+        assert np.all(np.isfinite(res_val)), f"res_val contains NaN, stop the program!" 
+    
+    sol = dofs.reshape(sol_shape)
     end = time.time()
     solve_time = end - start
     print(f"Solve took {solve_time} [s]")
     print(f"max of sol = {np.max(sol)}")
     print(f"min of sol = {np.min(sol)}")
 
     return sol
@@ -215,36 +311,42 @@
     for i in range(len(problem.node_inds_list)):
         aug_d = np.hstack((aug_d, p_num_eps*problem.vals_list[i]))
     for i in range(len(problem.p_node_inds_list_A)):
         aug_d = np.hstack((aug_d, np.zeros(len(problem.p_node_inds_list_A[i]))))
     return np.hstack((dofs, aug_d))
 
 
-def linear_guess_solve_lm(problem, A_fn_aug, p_num_eps):
-    x0 = np.zeros((problem.num_total_nodes, problem.vec))
-    x0 = assign_bc(x0, problem)
-    x0 = aug_dof_w_zero_bc(problem, x0)
-    b = np.zeros(problem.num_total_dofs)
+def linear_guess_solve_lm(problem, A_aug, p_num_eps, use_petsc):
+    b = (problem.body_force + problem.neumann).reshape(-1)
     b_aug = aug_dof_w_bc(problem, b, p_num_eps)
-    dofs_aug, info = jax.scipy.sparse.linalg.bicgstab(A_fn_aug, b_aug, x0=x0, M=None, tol=1e-10, atol=1e-10, maxiter=10000)
+    if use_petsc:
+        dofs_aug = petsc_solve(A_aug, b_aug, 'minres', 'none')
+    else:
+        x0 = np.zeros((problem.num_total_nodes, problem.vec))
+        x0 = assign_bc(x0, problem)
+        x0 = aug_dof_w_zero_bc(problem, x0)
+        dofs_aug = jax_solve(problem, A_aug, b_aug, x0, None)
     return dofs_aug
 
 
-def linear_incremental_solver_lm(problem, res_fn, A_fn_aug, dofs_aug, p_num_eps):
-    """
-    Lift solver
-    dofs must already satisfy Dirichlet boundary conditions
-    """
-    b_aug = -compute_residual_lm(problem, res_fn, dofs_aug, p_num_eps)
-    inc_aug, info = jax.scipy.sparse.linalg.bicgstab(A_fn_aug, b_aug, x0=None, M=None, tol=1e-10, atol=1e-10, maxiter=10000) # bicgstab
+def linear_incremental_solver_lm(problem, res_vec_aug, A_aug, dofs_aug, p_num_eps, use_petsc):
+    b_aug = -res_vec_aug
+    if use_petsc:
+        inc_aug = petsc_solve(A_aug, b_aug, 'minres', 'none')
+    else:
+        inc_aug = jax_solve(problem, A_aug, b_aug, None, None)
     dofs_aug = dofs_aug + inc_aug
     return dofs_aug
 
 
-def compute_residual_lm(problem, res_fn, dofs_aug, p_num_eps):
+def compute_residual_lm(problem, res_vec, dofs_aug, p_num_eps):
+    """Some memo here
+    Saddle point problem energy function: L(u, lmbda) = E(u) + lmbda*(u - u0)
+    with dL/d(u, lmbda) = res_vec_aug and dE/du = res_vec
+    """
     d_splits = np.cumsum(np.array([len(x) for x in problem.node_inds_list])).tolist()
     p_splits = np.cumsum(np.array([len(x) for x in problem.p_node_inds_list_A])).tolist()
 
     d_lmbda_len = d_splits[-1] if len(d_splits) > 0 else 0
     p_lmbda_len = p_splits[-1] if len(p_splits) > 0 else 0
 
     def get_Lagrangian():
@@ -263,33 +365,28 @@
             lag = 0.
             for i in range(len(problem.node_inds_list)):
                 lag += np.sum(d_lmbda_split[i] * (sol[problem.node_inds_list[i], problem.vec_inds_list[i]] - problem.vals_list[i]))
 
             for i in range(len(problem.p_node_inds_list_A)):
                 lag += np.sum(p_lmbda_split[i] * (sol[problem.p_node_inds_list_A[i], problem.p_vec_inds_list[i]] - 
                                                     sol[problem.p_node_inds_list_B[i], problem.p_vec_inds_list[i]]))
-
             return p_num_eps*lag
 
         return Lagrangian_fn
 
     Lagrangian_fn = get_Lagrangian()
     A_fn = jax.grad(Lagrangian_fn)
     res_vec_1 = A_fn(dofs_aug)
-
-    dofs = dofs_aug[:problem.num_total_dofs]
-    res_vec = res_fn(dofs)
     res_vec_2 = aug_dof_w_zero_bc(problem, res_vec)
-
     res_vec_aug = res_vec_1 + res_vec_2
 
     return res_vec_aug
 
 
-def get_A_fn_aug(problem, p_num_eps):
+def get_A_fn_and_res_aug(problem, dofs_aug, res_vec, p_num_eps, use_petsc):
     def symmetry(I, J, V):
         I_sym = onp.hstack((I, J))
         J_sym = onp.hstack((J, I))
         V_sym = onp.hstack((V, V))
         return I_sym, J_sym, V_sym
 
     I_d = onp.array([])
@@ -320,200 +417,362 @@
 
     I = onp.hstack((problem.I, I_d_sym, I_p_sym))
     J = onp.hstack((problem.J, J_d_sym, J_p_sym))
     V = onp.hstack((problem.V, V_d_sym, V_p_sym))
 
     print(f"Aug - Creating sparse matrix with scipy...")
     A_sp_scipy_aug = scipy.sparse.csc_array((V, (I, J)), shape=(group_index, group_index))
-    print(f"Aug - Creating sparse matrix from scipy using JAX BCOO...")
+    # print(f"Aug - Creating sparse matrix from scipy using JAX BCOO...")
     A_sp_aug = BCOO.from_scipy_sparse(A_sp_scipy_aug).sort_indices()
-    print(f"Aug - self.A_sp.data.shape = {A_sp_aug.data.shape}")
-    print(f"Aug - Global sparse matrix takes about {A_sp_aug.data.shape[0]*8*3/2**30} G memory to store.")
-    problem.A_sp_scipy_aug = A_sp_scipy_aug
+    # print(f"Aug - Global sparse matrix takes about {A_sp_aug.data.shape[0]*8*3/2**30} G memory to store.")
+
+    # TODO: Potential bug
+    # Used only in jacobi_preconditioner
+    # problem.A_sp_scipy = A_sp_scipy_aug
 
     def compute_linearized_residual(dofs_aug):
         return A_sp_aug @ dofs_aug
 
-    return compute_linearized_residual
+    if use_petsc:
+        A_aug = PETSc.Mat().createAIJ(size=A_sp_scipy_aug.shape, csr=(A_sp_scipy_aug.indptr, A_sp_scipy_aug.indices, A_sp_scipy_aug.data))
+    else:
+        A_aug = compute_linearized_residual
+
+    res_vec_aug = compute_residual_lm(problem, res_vec, dofs_aug, p_num_eps)
+
+    return A_aug, res_vec_aug
 
 
-def solver_lagrange_multiplier(problem, linear=False):
-    """Imposing Dirichlet B.C. and periodic B.C. with lagrangian multiplier method.
+def solver_lagrange_multiplier(problem, linear, use_petsc=True):
+    """The solver imposes Dirichlet B.C. and periodic B.C. with lagrangian multiplier method.
 
     The global matrix is of the form 
     [A   B 
      B^T 0]
-    and a good preconditioner is needed.
-    The problem is well studied, though.
-    However, in the current code, there is no trick applied. 
+    JAX built solver gmres and bicgstab sometimes fail to solve such a system.
+    PESTc solver minres seems to work. 
+    TODO: explore which solver in PESTc is the best, and which preconditioner should be used.
 
     Reference:
     https://ethz.ch/content/dam/ethz/special-interest/baug/ibk/structural-mechanics-dam/education/femI/Presentation.pdf
     """
     print(f"Calling the lagrange multiplier solver for imposing Dirichlet B.C. and periodic B.C.")
     print("Start timing")
     start = time.time()
+    sol_shape = (problem.num_total_nodes, problem.vec)
+    dofs = np.zeros(sol_shape).reshape(-1)
 
-    # Ad-hoc parameter to get a better conditioned global matrix.
-    # Currently, this parameter needs to be manually tuned.
-    # We need a (much) better way to deal with this type of saddle-point problem.
-    # Will interfacing with PETSc be a good idea?
+    # Ad-hoc parameter to get a better conditioned global matrix. Not useful for PETSc solver.
     if hasattr(problem, 'p_num_eps'):
         p_num_eps = problem.p_num_eps
     else:
         p_num_eps = 1.
 
-    print(f"Setting p_num_eps = {p_num_eps}. If periodic B.C. fails to be applied, consider modifying this parameter.")
+    if not use_petsc:
+        print(f"Setting p_num_eps = {p_num_eps}. If periodic B.C. fails to be applied, consider modifying this parameter.")
 
-    sol = np.zeros((problem.num_total_nodes, problem.vec))
-    dofs = sol.reshape(-1)
-
-    res_fn = problem.compute_residual
-    res_fn = get_flatten_fn(res_fn, problem)
-
-    problem.newton_update(dofs.reshape(sol.shape))
-    A_fn_aug = get_A_fn_aug(problem, p_num_eps)
+    def newton_update_helper(dofs_aug):
+        res_vec = problem.newton_update(dofs_aug[:problem.num_total_dofs].reshape(sol_shape)).reshape(-1)
+        A_aug, res_vec_aug = get_A_fn_and_res_aug(problem, dofs_aug, res_vec, p_num_eps, use_petsc)
+        return res_vec_aug, A_aug
 
     if linear:
         # If we know the problem is linear, this way of solving seems faster.
         dofs = assign_bc(dofs, problem)
         dofs_aug = aug_dof_w_zero_bc(problem, dofs)
-        dofs_aug = linear_incremental_solver_lm(problem, res_fn, A_fn_aug, dofs_aug, p_num_eps)
-        print(f"Linear problem res l_2 = {np.linalg.norm(compute_residual_lm(problem, res_fn, dofs_aug, p_num_eps))}")
+        res_vec_aug, A_aug = newton_update_helper(dofs_aug)
+        dofs_aug = linear_incremental_solver_lm(problem, res_vec_aug, A_aug, dofs_aug, p_num_eps, use_petsc)
     else:
-        dofs_aug = linear_guess_solve_lm(problem, A_fn_aug, p_num_eps)
-        res_val = np.linalg.norm(compute_residual_lm(problem, res_fn, dofs_aug, p_num_eps))
+        dofs_aug = aug_dof_w_zero_bc(problem, dofs)
+        res_vec_aug, A_aug = newton_update_helper(dofs_aug)
+        dofs_aug = linear_guess_solve_lm(problem, A_aug, p_num_eps, use_petsc)
+
+        res_vec_aug, A_aug = newton_update_helper(dofs_aug)
+        res_val = np.linalg.norm(res_vec_aug)
         print(f"Before, res l_2 = {res_val}") 
         tol = 1e-6
         while res_val > tol:
-            problem.newton_update(dofs_aug[:problem.num_total_dofs].reshape(sol.shape))
-            A_fn_aug = get_A_fn_aug(problem, p_num_eps)
-            dofs_aug = linear_incremental_solver_lm(problem, res_fn, A_fn_aug, dofs_aug, p_num_eps)
-            res_val = np.linalg.norm(compute_residual_lm(problem, res_fn, dofs_aug, p_num_eps))
+            dofs_aug = linear_incremental_solver_lm(problem, res_vec_aug, A_aug, dofs_aug, p_num_eps, use_petsc)
+            res_vec_aug, A_aug = newton_update_helper(dofs_aug)
+            res_val = np.linalg.norm(res_vec_aug)
             print(f"res l_2 dofs_aug = {res_val}") 
- 
-    sol = dofs_aug[:problem.num_total_dofs].reshape(sol.shape)
+
+    sol = dofs_aug[:problem.num_total_dofs].reshape(sol_shape)
     end = time.time()
     solve_time = end - start
     print(f"Solve took {solve_time} [s]")
     print(f"max of sol = {np.max(sol)}")
     print(f"min of sol = {np.min(sol)}")
 
     return sol
 
 
+
+################################################################################
+# Dynamic relaxation solver
+
+def assembleVec(problem, dofs):
+    res_fn = get_flatten_fn(problem.compute_residual, problem)
+    res_vec = res_fn(dofs)
+    res_vec = assign_zeros_bc(res_vec, problem)
+    res_vec = onp.array(res_vec)
+    return res_vec
+
+
+def assembleCSR(problem, dofs):
+    problem.newton_update(dofs.reshape((problem.num_total_nodes, problem.vec))).reshape(-1)
+    A_sp_scipy = scipy.sparse.csr_array((problem.V, (problem.I, problem.J)), shape=(problem.num_total_dofs, problem.num_total_dofs))
+
+    A = PETSc.Mat().createAIJ(size=A_sp_scipy.shape, csr=(A_sp_scipy.indptr, A_sp_scipy.indices, A_sp_scipy.data))
+    for i in range(len(problem.node_inds_list)):
+        row_inds = onp.array(problem.node_inds_list[i]*problem.vec + problem.vec_inds_list[i], dtype=onp.int32)
+        A.zeroRows(row_inds)
+
+    row, col, val = A.getValuesCSR()
+    A_sp_scipy.data = val; A_sp_scipy.indices = col; A_sp_scipy.indptr = row
+
+    return A_sp_scipy
+
+
+def calC(t, cmin, cmax):
+
+    if t<0.: t=0.
+
+    c = 2. * onp.sqrt(t)
+    if (c<cmin): c=cmin
+    if (c>cmax): c=cmax
+
+    return c
+
+
+def printInfo(error, t, c, tol,
+              eps, qdot, qdotdot, 
+              nIters, nPrint, 
+              info_force, info): 
+    
+    ## printing control
+    if nIters % nPrint == 1:
+        #print('\t------------------------------------')
+        if info_force == True:
+            print(('  DR Iteration %d: Max force = %g (tol = %g)' +
+                   ' Max velocity = %g') % (nIters, error, tol, 
+                                            np.max(np.absolute(qdot))))
+        if info == True: 
+            print('Damping t: ',t, );
+            print('Damping coefficient: ', c)
+            print('Max epsilon: ',np.max(eps))
+            print('Max acceleration: ',np.max(np.absolute(qdotdot)))
+
+
+def DynamicRelaxSolve(problem, initial_guess, 
+                      # default parameters
+                      tol = 1e-6, nKMat = 50, nPrint = 1000, 
+                      info = True, info_force = True):
+
+    dofs = np.array(initial_guess).reshape(-1)
+    dofs = assign_bc(dofs, problem)
+
+    sol_shape = (problem.num_total_nodes, problem.vec)
+    dofs = np.zeros(sol_shape).reshape(-1)
+    def newton_update_helper(dofs):
+        res_vec = problem.newton_update(dofs.reshape(sol_shape)).reshape(-1)
+        res_vec = apply_bc_vec(res_vec, dofs, problem)
+        A_fn = get_A_fn(problem, use_petsc=False)
+        return res_vec, A_fn
+    
+    res_vec, A_fn = newton_update_helper(dofs)
+    dofs = linear_guess_solve(problem, A_fn, precond=True, use_petsc=False)
+ 
+    # parameters not to change
+    cmin  = 1e-3; cmax = 3.9; h_tilde=1.1; h=1.
+
+    # initialize all arrays
+    N = len(dofs) #print("--------num of DOF's: %d-----------" % N)
+    #initialize displacements, velocities and accelerations
+    q, qdot, qdotdot = onp.zeros(N), onp.zeros(N), onp.zeros(N)
+    #initialize displacements, velocities and accelerations from a previous time step
+    q_old, qdot_old, qdotdot_old = onp.zeros(N), onp.zeros(N), onp.zeros(N)
+    #initialize the M, eps, R_old arrays
+    eps, M, R, R_old = onp.zeros(N), onp.zeros(N), onp.zeros(N), onp.zeros(N)
+ 
+    R = assembleVec(problem, dofs)
+    KCSR = assembleCSR(problem, dofs)
+
+    M[:] = h_tilde*h_tilde/4. * onp.array(onp.absolute(KCSR).sum(axis = 1)).squeeze()
+    q[:] = dofs
+    qdot[:] = - h/2. * R / M
+    # set the counters for iterations and 
+    nIters, iKMat = 0, 0; error = 1.0;
+
+    timeZ = time.time() #Measurement of loop time.
+    
+
+    assert onp.all(onp.isfinite(M)), f"M not finite"
+    assert onp.all(onp.isfinite(q)), f"q not finite"
+    assert onp.all(onp.isfinite(qdot)), f"qdot not finite"
+
+
+    error = onp.max(onp.absolute(R))
+ 
+    while error > tol:
+
+        print(f"error = {error}")
+        
+        # marching forward
+        q_old[:] = q[:]; R_old[:] = R[:]
+        q[:] += h*qdot; dofs = np.array(q)
+
+        # assembleVec(F, bcs, RVec, R)
+        R = assembleVec(problem, dofs)
+
+        nIters += 1; iKMat += 1; error = onp.max(onp.absolute(R))
+        
+        # damping calculation
+        S0 = onp.dot((R - R_old)/h,  qdot)
+        t = S0 / onp.einsum('i,i,i', qdot, M, qdot)
+        c = calC(t, cmin, cmax)
+
+        # determine whether to recal KMat
+        eps = h_tilde*h_tilde/4. * onp.absolute(
+                onp.divide((qdotdot - qdotdot_old), (q - q_old),
+                out = onp.zeros_like( (qdotdot - qdotdot_old) ),
+                where = (q - q_old)!=0))
+        
+        # calculating the jacobian matrix
+        if ((onp.max(eps) > 1) and (iKMat > nKMat)): #SPR JAN max --> min
+            if info==True: 
+                print('\tRecalculating the tangent matrix: ', nIters)
+            iKMat = 0
+            # assembleCSR(J, bcs, KMat, KCSR)
+            KCSR = assembleCSR(problem, dofs)
+            M[:] = h_tilde*h_tilde/4. * onp.array(onp.absolute(KCSR).sum(axis = 1)).squeeze()
+
+        #compute new velocities and accelerations
+        qdot_old[:] = qdot[:]; qdotdot_old[:] = qdotdot[:];
+        qdot = (2.- c*h)/(2 + c*h) * qdot_old - 2.*h/(2.+c*h)* R / M
+        qdotdot = qdot - qdot_old 
+            
+        # output on screen
+        printInfo(error, t, c, tol,
+                  eps, qdot, qdotdot,
+                  nIters, nPrint,
+                  info_force, info)
+
+    # check if converged
+    convergence = True
+    if onp.isnan(onp.max(onp.absolute(R))):
+        convergence = False
+
+    # print final info
+    if convergence:
+        print("  DRSolve finished in %d iterations and %fs" % \
+              (nIters, time.time() - timeZ))
+    else:
+        print("  FAILED to converged")
+
+    sol = dofs.reshape((problem.num_total_nodes, problem.vec))
+    return sol
+
+
+
 ################################################################################
-# General solver
+# General
 
-def solver(problem, linear=False, precond=True):
+def solver(problem, linear=False, precond=True, initial_guess=None, use_petsc=False):
     """periodic B.C. is a special form of adding a linear constraint. 
     Lagrange multiplier seems to be convenient to impose this constraint.
     """
+    # TODO: print platform jax.lib.xla_bridge.get_backend().platform
+    # and suggest PETSc or jax solver
     if problem.periodic_bc_info is None:
-        return solver_row_elimination(problem, linear, precond)
+        return solver_row_elimination(problem, linear, precond, initial_guess, use_petsc)
     else:
-        return solver_lagrange_multiplier(problem, linear)
+        return solver_lagrange_multiplier(problem, linear, use_petsc)
 
 
 ################################################################################
-# Adjoint method for inverse problem
-
-def adjoint_method(problem, J_fn, output_sol, linear=False):
-    """Adjoint method with automatic differentiation.
-
-    Currently, the function cannot deal with periodic B.C.,
-    but it should not be easy to add.
-    """
-    def fn(params):
-        """J(u(p), p)
-        """
-        print(f"\nStep {fn.counter}")
-        problem.params = params
-        sol = solver(problem, linear=linear)
-        dofs = sol.reshape(-1)
-        obj_val = J_fn(dofs, params)
-        fn.dofs = dofs
-        output_sol(params, dofs, obj_val)
-        fn.counter += 1
-        return obj_val
-
-    fn.counter = 0
+# Implicit differentiation with the adjoint method
 
+def implicit_vjp(problem, sol, params, v, use_petsc):
     def constraint_fn(dofs, params):
         """c(u, p)
         """
-        problem.params = params
+        problem.set_params(params)
         res_fn = problem.compute_residual
         res_fn = get_flatten_fn(res_fn, problem)
         res_fn = apply_bc(res_fn, problem)
         return res_fn(dofs)
 
-    def get_partial_dofs_c_fn(params):
-        """c(u, p=p)
-        """
-        def partial_dofs_c_fn(dofs):
-            return constraint_fn(dofs, params)
-        return partial_dofs_c_fn
-
-    def get_partial_params_c_fn(dofs):
-        """c(u=u, p)
-        """
-        def partial_params_c_fn(params):
-            return constraint_fn(dofs, params)
-        return partial_params_c_fn
+    def constraint_fn_sol_to_sol(sol, params):
+        return constraint_fn(sol.reshape(-1), params).reshape(sol.shape)
 
-    def get_vjp_contraint_fn_dofs_slow(params, dofs):
-        """v*(partial dc/du)
-        This version is slow.
-        Linearization from "problem.compute_residual" with vjp (or jvp) is slow!
-        """
-        partial_c_fn = get_partial_dofs_c_fn(params)
+    def get_vjp_contraint_fn_dofs(dofs):
+        # Just a transpose of A_fn
         def adjoint_linear_fn(adjoint):
-            primals, f_vjp = jax.vjp(partial_c_fn, dofs)
+            primals, f_vjp = jax.vjp(A_fn, dofs)
             val, = f_vjp(adjoint)
             return val
         return adjoint_linear_fn
 
-    def get_vjp_contraint_fn_dofs(params, dofs):
-        """v*(partial dc/du)
-        This version should be fast even for nonlinear problem.
-        If not, consider implementing the adjoint version of "problem.compute_linearized_residual" directly.
+    def get_partial_params_c_fn(sol):
+        """c(u=u, p)
         """
-        # The following two lines may not be needed
-        problem.params = params
-        A_fn = get_A_fn(problem)
-        A_fn = row_elimination(A_fn, problem)
-        def adjoint_linear_fn(adjoint):
-            primals, f_vjp = jax.vjp(A_fn, dofs)
-            val, = f_vjp(adjoint)
-            return val
-        return adjoint_linear_fn
+        def partial_params_c_fn(params):
+            return constraint_fn_sol_to_sol(sol, params)
+        return partial_params_c_fn
 
-    def get_vjp_contraint_fn_params(params, dofs):
+    def get_vjp_contraint_fn_params(params, sol):
         """v*(partial dc/dp)
         """
-        partial_c_fn = get_partial_params_c_fn(dofs)
+        partial_c_fn = get_partial_params_c_fn(sol)
         def vjp_linear_fn(v):
             primals, f_vjp = jax.vjp(partial_c_fn, params)
             val, = f_vjp(v)
             return val
         return vjp_linear_fn
 
-    def fn_grad(params):
-        """total dJ/dp
-        """
-        dofs = fn.dofs
-        partial_dJ_du = jax.grad(J_fn, argnums=0)(dofs, params)
-        partial_dJ_dp = jax.grad(J_fn, argnums=1)(dofs, params)
-        adjoint_linear_fn = get_vjp_contraint_fn_dofs(params, dofs)
-        vjp_linear_fn = get_vjp_contraint_fn_params(params, dofs)
-        # test_jacobi_precond(problem, jacobi_preconditioner(problem), adjoint_linear_fn)
-        problem.newton_update(dofs.reshape((problem.num_total_nodes, problem.vec)))
-        pc = get_jacobi_precond(jacobi_preconditioner(problem))
-        start = time.time()
-        adjoint, info = jax.scipy.sparse.linalg.bicgstab(adjoint_linear_fn, partial_dJ_du, x0=None, M=pc, tol=1e-10, atol=1e-10, maxiter=10000)
-        end = time.time()
-        print(f"Adjoint solve took {end - start} [s]")
-        total_dJ_dp = -vjp_linear_fn(adjoint) + partial_dJ_dp
-        return total_dJ_dp
+    problem.set_params(params)
+    problem.newton_update(sol)
+    A_fn = get_A_fn(problem, use_petsc)
+
+    if use_petsc:
+        A_transpose = A_fn.transpose()
+
+        # Remark: Eliminating rows seems to make A better conditioned. 
+        # If Dirichlet B.C. is part of the design variable, the following should NOT be implemented.
+        # for i in range(len(problem.node_inds_list)):
+        #     row_inds = onp.array(problem.node_inds_list[i]*problem.vec + problem.vec_inds_list[i], dtype=onp.int32)
+        #     A_transpose.zeroRows(row_inds)
+        # v = assign_zeros_bc(v, problem)
+
+        adjoint = petsc_solve(A_transpose, v.reshape(-1), 'minres', 'ilu')
+
+    else:
+        adjoint_linear_fn = get_vjp_contraint_fn_dofs(sol.reshape(-1))
+        adjoint = jax_solve(problem, adjoint_linear_fn, v.reshape(-1), None, True)
+
+    vjp_linear_fn = get_vjp_contraint_fn_params(params, sol)
+    vjp_result = vjp_linear_fn(adjoint.reshape(sol.shape))
+    vjp_result = jax.tree_map(lambda x: -x, vjp_result)
+
+    return vjp_result
+
+
+def ad_wrapper(problem, linear=False, use_petsc=False):
+    @jax.custom_vjp
+    def fwd_pred(params):
+        problem.set_params(params)
+        sol = solver(problem, linear=linear, use_petsc=use_petsc)
+        return sol
+ 
+    def f_fwd(params):
+        sol = fwd_pred(params)
+        return sol, (params, sol)
+
+    def f_bwd(res, v):
+        print("\nRunning backward and solving the adjoint problem...")
+        params, sol = res 
+        vjp_result = implicit_vjp(problem, sol, params, v, use_petsc)
+        return (vjp_result,)
 
-    return fn, fn_grad
+    fwd_pred.defvjp(f_fwd, f_bwd)
+    return fwd_pred
```

### Comparing `jax-am-0.0.2/jax_am/fem/utils.py` & `jax-am-0.0.3/jax_am/fem/utils.py`

 * *Files 11% similar despite different names*

```diff
@@ -1,21 +1,25 @@
 import meshio
 import os
 import numpy as onp
 
+from jax_am.fem.generate_mesh import get_meshio_cell_type
 
-def save_sol(problem, sol, sol_file, cell_infos=None, point_infos=None, cell_type='hexahedron'):
+
+def save_sol(problem, sol, sol_file, cell_infos=None, point_infos=None):
+    cell_type = get_meshio_cell_type(problem.ele_type)
     sol_dir = os.path.dirname(sol_file)
     os.makedirs(sol_dir, exist_ok=True)
     out_mesh = meshio.Mesh(points=problem.points, cells={cell_type: problem.cells})
     out_mesh.point_data['sol'] = onp.array(sol, dtype=onp.float32)
     if cell_infos is not None:
         for cell_info in cell_infos:
             name, data = cell_info
-            assert data.shape == (problem.num_cells,), "cell data wrong shape!"
+            # TODO: vector-valued cell data
+            assert data.shape == (problem.num_cells,), f"cell data wrong shape, get {data.shape}, while num_cells = {problem.num_cells}"
             out_mesh.cell_data[name] = [onp.array(data, dtype=onp.float32)]
     if point_infos is not None:
         for point_info in point_infos:
             name, data = point_info
             assert len(data) == len(sol), "point data wrong shape!"
             out_mesh.point_data[name] = onp.array(data, dtype=onp.float32)
     out_mesh.write(sol_file)
@@ -28,7 +32,15 @@
     """
     fin = open(input_file_path, "r")
     fout = open(output_file_path, "w")
     for line in fin:
         fout.write(line.replace('<VTKFile type="UnstructuredGrid" version="2.2">', '<VTKFile type="UnstructuredGrid" version="1.0">'))
     fin.close()
     fout.close()
+
+
+def read_abaqus_and_write_vtk(abaqus_file, vtk_file):
+    """Used for a quick inspection. Paraview can't open .inp file so we convert it to .vtu
+    """
+    meshio_mesh = meshio.read(abaqus_file)
+    meshio_mesh.write(vtk_file)
+
```

### Comparing `jax-am-0.0.2/jax_am/phase_field/allen_cahn.py` & `jax-am-0.0.3/jax_am/phase_field/allen_cahn.py`

 * *Files 10% similar despite different names*

```diff
@@ -8,27 +8,41 @@
 
 
 def phase_field(polycrystal, pf_args):
     # TODO: make this simpler
     h_x, h_y, h_z = polycrystal.mesh_h_xyz
 
     def update_anisotropy_helper(edges):
-        edge_directions = edges.reshape(-1, pf_args['dim'])
-        edge_directions = np.repeat(edge_directions[:, None, :], pf_args['num_oris'], axis=1) # (num_edges, num_oris, dim)
+        edge_directions = edges.reshape(-1, pf_args['num_oris'], pf_args['dim']) # (num_edges, num_oris, dim)
         unique_grain_directions = polycrystal.unique_grain_directions # (num_directions_per_cube, num_oris, dim)
         cosines = np.sum(unique_grain_directions[None, :, :, :] * edge_directions[:, None, :, :], axis=-1) \
                   / (np.linalg.norm(edge_directions, axis=-1)[:, None, :])
         angles = np.arccos(cosines) 
         angles = np.where(np.isfinite(angles), angles, 0.)
         angles = np.where(angles < np.pi/2., angles, np.pi - angles)
         angles = np.min(angles, axis=1)
         anisotropy_term = 1. + pf_args['anisotropy'] * (np.cos(angles)**4 + np.sin(angles)**4) # (num_edges, num_oris)
         anisotropy_term = anisotropy_term.reshape((edges.shape[0], edges.shape[1], edges.shape[2], pf_args['num_oris']))
         return anisotropy_term
 
+
+    def update_anisotropy_helper(edges):
+        edge_directions = edges.reshape(-1, pf_args['num_oris'], pf_args['dim']) # (num_edges, num_oris, dim)
+        unique_grain_directions = polycrystal.unique_grain_directions # (num_directions_per_cube, num_oris, dim)
+        cosines = np.sum(unique_grain_directions[None, :, :, :] * edge_directions[:, None, :, :], axis=-1) \
+                  / (np.linalg.norm(edge_directions, axis=-1)[:, None, :])
+        angles = np.arccos(cosines) 
+        angles = np.where(np.isfinite(angles), angles, 0.)
+        angles = np.where(angles < np.pi/2., angles, np.pi - angles)
+        angles = np.min(angles, axis=1)
+        anisotropy_term = 1. + pf_args['anisotropy'] * (np.cos(angles)**4 + np.sin(angles)**4) # (num_edges, num_oris)
+        anisotropy_term = anisotropy_term.reshape((edges.shape[0], edges.shape[1], edges.shape[2], pf_args['num_oris']))
+        return anisotropy_term
+
+
     def local_energy_fn(eta, zeta):
         gamma = 1
         vmap_outer = jax.vmap(np.outer, in_axes=(0, 0))
         grain_energy_1 = np.sum((eta**4/4. - eta**2/2.))
         graph_energy_2 = gamma * (np.sum(vmap_outer(eta, eta)**2) - np.sum(eta**4))  
         graph_energy_3 = np.sum((1 - zeta.reshape(-1))**2 * np.sum(eta**2, axis=1).reshape(-1))
         grain_energy = pf_args['m_g'] * (grain_energy_1 +  graph_energy_2 + graph_energy_3)
@@ -48,40 +62,24 @@
         eta_pos_x = np.concatenate((eta_xyz[:, :, 1:, :], eta_xyz[:, :, -1:, :]), axis=2)
         eta_neg_y = np.concatenate((eta_xyz[:, :1, :, :], eta_xyz[:, :-1, :, :]), axis=1)
         eta_pos_y = np.concatenate((eta_xyz[:, 1:, :, :], eta_xyz[:, -1:, :, :]), axis=1)
         eta_neg_z = np.concatenate((eta_xyz[:1, :, :, :], eta_xyz[:-1, :, :, :]), axis=0)
         eta_pos_z = np.concatenate((eta_xyz[1:, :, :, :], eta_xyz[-1:, :, :, :]), axis=0)
 
         if pf_args['anisotropy'] > 0.:
-            # TODO: Make the code concise
-            # https://github.com/google/jax-cfd/blob/8eff9c47bdc7fb19b6453db94ca65f6be64d91f6/jax_cfd/base/finite_differences.py#L74
-            centroids = polycrystal.centroids
-            centroids_xyz = np.reshape(centroids, (pf_args['Nz'], pf_args['Ny'], pf_args['Nx'], pf_args['dim']))
-            edges_x = centroids_xyz[:, :, 1:, :] - centroids_xyz[:, :, :-1, :]
-            edges_y = centroids_xyz[:, 1:, :, :] - centroids_xyz[:, :-1, :, :] 
-            edges_z = centroids_xyz[1:, :, :, :] - centroids_xyz[:-1, :, :, :]
-            aniso_x = update_anisotropy_helper(edges_x)
-            aniso_y = update_anisotropy_helper(edges_y)
-            aniso_z = update_anisotropy_helper(edges_z)
-
-            aniso_neg_x = np.pad(aniso_x, ((0, 0), (0, 0), (1, 0), (0, 0)))
-            aniso_pos_x = np.pad(aniso_x, ((0, 0), (0, 0), (0, 1), (0, 0)))
-            aniso_neg_y = np.pad(aniso_y, ((0, 0), (1, 0), (0, 0), (0, 0)))
-            aniso_pos_y = np.pad(aniso_y, ((0, 0), (0, 1), (0, 0), (0, 0)))
-            aniso_neg_z = np.pad(aniso_z, ((1, 0), (0, 0), (0, 0), (0, 0)))
-            aniso_pos_z = np.pad(aniso_z, ((0, 1), (0, 0), (0, 0), (0, 0)))
+            aniso = update_anisotropy_helper(np.stack((eta_pos_x - eta_neg_x, eta_pos_y - eta_neg_y, eta_pos_z - eta_neg_z), axis=-1))[..., None]
             print("End of compute_anisotropy...")
         else:
-            aniso_neg_x, aniso_pos_x, aniso_neg_y, aniso_pos_y, aniso_neg_z, aniso_pos_z = 1., 1., 1., 1., 1., 1
+            aniso = 1.
 
         # See https://en.wikipedia.org/wiki/Finite_difference "Second-order central"
-        laplace_xyz = -(np.stack((((eta_pos_x - eta_xyz)*aniso_neg_x + (eta_neg_x - eta_xyz)*aniso_pos_x)/h_x**2, 
-                                  ((eta_pos_y - eta_xyz)*aniso_neg_y + (eta_neg_y - eta_xyz)*aniso_pos_y)/h_y**2, 
-                                  ((eta_pos_z - eta_xyz)*aniso_neg_z + (eta_neg_z - eta_xyz)*aniso_pos_z)/h_z**2), axis=-1) *
-                                   pf_args['kappa_g'] * pf_args['ad_hoc'])
+        laplace_xyz = -(np.stack((((eta_pos_x - eta_xyz) + (eta_neg_x - eta_xyz))/h_x**2, 
+                                  ((eta_pos_y - eta_xyz) + (eta_neg_y - eta_xyz))/h_y**2, 
+                                  ((eta_pos_z - eta_xyz) + (eta_neg_z - eta_xyz))/h_z**2), axis=-1)
+                                   * aniso * pf_args['kappa_g'] * pf_args['ad_hoc'])
 
         assert laplace_xyz.shape == (pf_args['Nz'], pf_args['Ny'], pf_args['Nx'], pf_args['num_oris'], pf_args['dim'])
         laplace = np.sum(laplace_xyz.reshape(-1, pf_args['num_oris'], pf_args['dim']), axis=-1)
         assert local_energy_grad.shape == laplace.shape
         Lg = pf_args['L0'] * np.exp(-pf_args['Qg'] / (T*pf_args['gas_const']))
         rhs = -Lg * (local_energy_grad + laplace)
         return rhs
@@ -137,15 +135,15 @@
         self.state_rhs = phase_field(self.polycrystal, self.pf_args)
         self.force_eta_fn = get_force_eta_fn(self.pf_args)
         self.clean_sols()
 
     def stepper(self, state_pre, t_crt, ode_params):
         T, = ode_params
         state, y = explicit_euler(state_pre, t_crt, self.state_rhs, ode_params) 
-        state = self.force_eta_fn(state, T)
+        # state = self.force_eta_fn(state, T)
         return state, state[0]
         
     def ini_cond(self):
         '''
         Prescribe the initial conditions for eta.
         '''
         num_nodes = len(self.polycrystal.centroids)
```

### Comparing `jax-am-0.0.2/jax_am/phase_field/neper.py` & `jax-am-0.0.3/jax_am/phase_field/neper.py`

 * *Files identical despite different names*

### Comparing `jax-am-0.0.2/jax_am/phase_field/utils.py` & `jax-am-0.0.3/jax_am/phase_field/utils.py`

 * *Files 16% similar despite different names*

```diff
@@ -181,15 +181,14 @@
     eta_results = compute_aspect_ratios_and_vols(grain_vols, grain_centroids)
 
     # print(eta_results)
 
     return eta_results
 
 
-
 def compute_edges_in_order(pf_args):
     Nx, Ny, Nz = pf_args['Nx'], pf_args['Ny'], pf_args['Nz']
     num_total_cells = Nx*Ny*Nz
     cell_inds = onp.arange(num_total_cells).reshape(Nz, Ny, Nx)
     edges_x = onp.stack((cell_inds[:, :, :-1], cell_inds[:, :, 1:]), axis=3).reshape(-1, 2)
     edges_y = onp.stack((cell_inds[:, :-1, :], cell_inds[:, 1:, :]), axis=3).reshape(-1, 2)
     edges_z = onp.stack((cell_inds[:-1, :, :], cell_inds[1:, :, :]), axis=3).reshape(-1, 2)
@@ -277,41 +276,7 @@
 
         grain_sum_vols.append(sum_vol)
 
     print(len(grain_sum_vols))
     print(len(grain_sum_aspect_ratios))
     return [grain_sum_vols, grain_sum_aspect_ratios]
 
-
-def walltime(data_dir=None):
-    def decorate(func):
-        def wrapper(*list_args, **keyword_args):
-            start_time = time.time()
-            return_values = func(*list_args, **keyword_args)
-            end_time = time.time()
-            time_elapsed = end_time - start_time
-            platform = jax.lib.xla_bridge.get_backend().platform
-            print(f"Time elapsed {time_elapsed} of function {func.__name__} on platform {platform}")
-            if data_dir is not None:
-                txt_dir = os.path.join(data_dir, f'txt')
-                os.makedirs(txt_dir, exist_ok=True)
-                with open(os.path.join(txt_dir, f"walltime_{platform}.txt"), 'w') as f:
-                    f.write(f'{start_time}, {end_time}, {time_elapsed}\n')
-            return return_values
-        return wrapper
-    return decorate
-
-
-def make_video(pf_args):
-    # The command -pix_fmt yuv420p is to ensure preview of video on Mac OS is enabled
-    # https://apple.stackexchange.com/questions/166553/why-wont-video-from-ffmpeg-show-in-quicktime-imovie-or-quick-preview
-    # The command -vf "pad=ceil(iw/2)*2:ceil(ih/2)*2" is to solve the following "not-divisible-by-2" problem
-    # https://stackoverflow.com/questions/20847674/ffmpeg-libx264-height-not-divisible-by-2
-    # -y means always overwrite
-
-    # TODO
-    os.system(f'ffmpeg -y -framerate 10 -i {pf_args["data_dir"]}/png/tmp/u.%04d.png -pix_fmt yuv420p -vf \
-               "crop=trunc(iw/2)*2:trunc(ih/2)*2" {pf_args["data_dir"]}/mp4/test.mp4')
-
-
-if __name__=="__main__":
-    make_video()
```

### Comparing `jax-am-0.0.2/setup.py` & `jax-am-0.0.3/setup.py`

 * *Files 16% similar despite different names*

```diff
@@ -31,15 +31,15 @@
             "numpy",
             "scipy",
             "orix",
             "meshio",
             "gmsh",
             "pyfiglet",
             "scikit-learn",
-            "basix",
+            "fenics-basix"
         ],
         url="https://github.com/tianjuxue/jax-am",
         license="GPL-3.0",
         classifiers=[
             'Programming Language :: Python :: 3',
             'Operating System :: MacOS',
             'Operating System :: POSIX :: Linux',
```


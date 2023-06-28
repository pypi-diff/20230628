# Comparing `tmp/pyFBS-0.3.0.tar.gz` & `tmp/pyFBS-0.3.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyFBS-0.3.0.tar", last modified: Fri Jun  9 11:38:24 2023, max compression
+gzip compressed data, was "pyFBS-0.3.1.tar", last modified: Wed Jun 28 10:54:52 2023, max compression
```

## Comparing `pyFBS-0.3.0.tar` & `pyFBS-0.3.1.tar`

### file list

```diff
@@ -1,43 +1,43 @@
-drwxrwxrwx   0        0        0        0 2023-06-09 11:38:24.299283 pyFBS-0.3.0/
--rw-rw-rw-   0        0        0      396 2023-06-09 11:36:13.000000 pyFBS-0.3.0/AUTHORS.rst
--rw-rw-rw-   0        0        0     8409 2023-06-09 11:36:13.000000 pyFBS-0.3.0/CONTRIBUTING.rst
--rw-rw-rw-   0        0        0     1101 2023-06-09 11:36:13.000000 pyFBS-0.3.0/LICENSE
--rw-rw-rw-   0        0        0      265 2023-06-09 11:36:13.000000 pyFBS-0.3.0/MANIFEST.in
--rw-rw-rw-   0        0        0     2786 2023-06-09 11:38:24.298280 pyFBS-0.3.0/PKG-INFO
--rw-rw-rw-   0        0        0     2035 2023-06-09 11:36:13.000000 pyFBS-0.3.0/README.rst
-drwxrwxrwx   0        0        0        0 2023-06-09 11:38:24.137101 pyFBS-0.3.0/data/
--rw-rw-rw-   0        0        0    15168 2023-06-09 11:36:13.000000 pyFBS-0.3.0/data/logo-small.png
--rw-rw-rw-   0        0        0    42036 2023-06-09 11:36:13.000000 pyFBS-0.3.0/data/logo_new.png
-drwxrwxrwx   0        0        0        0 2023-06-09 11:38:24.047355 pyFBS-0.3.0/pyFBS/
--rw-rw-rw-   0        0        0    12319 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/IO.py
--rw-rw-rw-   0        0        0    33594 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/MCK.py
--rw-rw-rw-   0        0        0    13879 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/OSI.py
--rw-rw-rw-   0        0        0    22066 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/SEMM.py
--rw-rw-rw-   0        0        0     7632 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/SVT.py
--rw-rw-rw-   0        0        0    18601 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/VPT.py
--rw-rw-rw-   0        0        0      199 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/__init__.py
--rw-rw-rw-   0        0        0    35062 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/app_stability.py
--rw-rw-rw-   0        0        0    51438 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/display.py
--rw-rw-rw-   0        0        0    37294 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/modal_id.py
--rw-rw-rw-   0        0        0    46545 2023-06-09 11:36:16.000000 pyFBS-0.3.0/pyFBS/utility.py
-drwxrwxrwx   0        0        0        0 2023-06-09 11:38:24.109821 pyFBS-0.3.0/pyFBS.egg-info/
--rw-rw-rw-   0        0        0     2786 2023-06-09 11:38:22.000000 pyFBS-0.3.0/pyFBS.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      685 2023-06-09 11:38:23.000000 pyFBS-0.3.0/pyFBS.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-09 11:38:22.000000 pyFBS-0.3.0/pyFBS.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       41 2023-06-09 11:38:22.000000 pyFBS-0.3.0/pyFBS.egg-info/entry_points.txt
--rw-rw-rw-   0        0        0      140 2023-06-09 11:38:23.000000 pyFBS-0.3.0/pyFBS.egg-info/requires.txt
--rw-rw-rw-   0        0        0        6 2023-06-09 11:38:23.000000 pyFBS-0.3.0/pyFBS.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      294 2023-06-09 11:36:16.000000 pyFBS-0.3.0/requirements.txt
--rw-rw-rw-   0        0        0      146 2023-06-09 11:36:16.000000 pyFBS-0.3.0/requirements_dev.txt
--rw-rw-rw-   0        0        0       42 2023-06-09 11:38:24.299746 pyFBS-0.3.0/setup.cfg
--rw-rw-rw-   0        0        0     2238 2023-06-09 11:36:16.000000 pyFBS-0.3.0/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-09 11:38:24.297048 pyFBS-0.3.0/tests/
--rw-rw-rw-   0        0        0       36 2023-06-09 11:36:16.000000 pyFBS-0.3.0/tests/__init__.py
--rw-rw-rw-   0        0        0     4334 2023-06-09 11:36:16.000000 pyFBS-0.3.0/tests/build_examples.py
--rw-rw-rw-   0        0        0     2320 2023-06-09 11:36:16.000000 pyFBS-0.3.0/tests/conftest.py
--rw-rw-rw-   0        0        0      686 2023-06-09 11:36:16.000000 pyFBS-0.3.0/tests/test_IO.py
--rw-rw-rw-   0        0        0     1549 2023-06-09 11:36:16.000000 pyFBS-0.3.0/tests/test_MCK.py
--rw-rw-rw-   0        0        0     1115 2023-06-09 11:36:16.000000 pyFBS-0.3.0/tests/test_SVT.py
--rw-rw-rw-   0        0        0      956 2023-06-09 11:36:16.000000 pyFBS-0.3.0/tests/test_VPT.py
--rw-rw-rw-   0        0        0     2661 2023-06-09 11:36:16.000000 pyFBS-0.3.0/tests/test_display.py
--rw-rw-rw-   0        0        0      748 2023-06-09 11:36:16.000000 pyFBS-0.3.0/tests/test_modal_id.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:54:52.155805 pyFBS-0.3.1/
+-rw-rw-rw-   0        0        0      396 2023-06-28 10:50:43.000000 pyFBS-0.3.1/AUTHORS.rst
+-rw-rw-rw-   0        0        0     8409 2023-06-28 10:50:43.000000 pyFBS-0.3.1/CONTRIBUTING.rst
+-rw-rw-rw-   0        0        0     1101 2023-06-28 10:50:43.000000 pyFBS-0.3.1/LICENSE
+-rw-rw-rw-   0        0        0      265 2023-06-28 10:50:43.000000 pyFBS-0.3.1/MANIFEST.in
+-rw-rw-rw-   0        0        0     2765 2023-06-28 10:54:52.154809 pyFBS-0.3.1/PKG-INFO
+-rw-rw-rw-   0        0        0     2035 2023-06-28 10:50:43.000000 pyFBS-0.3.1/README.rst
+drwxrwxrwx   0        0        0        0 2023-06-28 10:54:51.953068 pyFBS-0.3.1/data/
+-rw-rw-rw-   0        0        0    15168 2023-06-28 10:50:43.000000 pyFBS-0.3.1/data/logo-small.png
+-rw-rw-rw-   0        0        0    42036 2023-06-28 10:50:43.000000 pyFBS-0.3.1/data/logo_new.png
+drwxrwxrwx   0        0        0        0 2023-06-28 10:54:51.812202 pyFBS-0.3.1/pyFBS/
+-rw-rw-rw-   0        0        0    12319 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/IO.py
+-rw-rw-rw-   0        0        0    33582 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/MCK.py
+-rw-rw-rw-   0        0        0    13879 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/OSI.py
+-rw-rw-rw-   0        0        0    22066 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/SEMM.py
+-rw-rw-rw-   0        0        0     7632 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/SVT.py
+-rw-rw-rw-   0        0        0    18601 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/VPT.py
+-rw-rw-rw-   0        0        0      199 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/__init__.py
+-rw-rw-rw-   0        0        0    35081 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/app_stability.py
+-rw-rw-rw-   0        0        0    51438 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/display.py
+-rw-rw-rw-   0        0        0    37507 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/modal_id.py
+-rw-rw-rw-   0        0        0    46526 2023-06-28 10:50:44.000000 pyFBS-0.3.1/pyFBS/utility.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:54:51.925606 pyFBS-0.3.1/pyFBS.egg-info/
+-rw-rw-rw-   0        0        0     2765 2023-06-28 10:54:50.000000 pyFBS-0.3.1/pyFBS.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      685 2023-06-28 10:54:51.000000 pyFBS-0.3.1/pyFBS.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:54:50.000000 pyFBS-0.3.1/pyFBS.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       41 2023-06-28 10:54:51.000000 pyFBS-0.3.1/pyFBS.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0      140 2023-06-28 10:54:51.000000 pyFBS-0.3.1/pyFBS.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 10:54:51.000000 pyFBS-0.3.1/pyFBS.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      294 2023-06-28 10:50:44.000000 pyFBS-0.3.1/requirements.txt
+-rw-rw-rw-   0        0        0      146 2023-06-28 10:50:44.000000 pyFBS-0.3.1/requirements_dev.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 10:54:52.155805 pyFBS-0.3.1/setup.cfg
+-rw-rw-rw-   0        0        0     2238 2023-06-28 10:50:44.000000 pyFBS-0.3.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:54:52.153078 pyFBS-0.3.1/tests/
+-rw-rw-rw-   0        0        0       36 2023-06-28 10:50:44.000000 pyFBS-0.3.1/tests/__init__.py
+-rw-rw-rw-   0        0        0     4334 2023-06-28 10:50:44.000000 pyFBS-0.3.1/tests/build_examples.py
+-rw-rw-rw-   0        0        0     2320 2023-06-28 10:50:44.000000 pyFBS-0.3.1/tests/conftest.py
+-rw-rw-rw-   0        0        0      686 2023-06-28 10:50:44.000000 pyFBS-0.3.1/tests/test_IO.py
+-rw-rw-rw-   0        0        0     1549 2023-06-28 10:50:44.000000 pyFBS-0.3.1/tests/test_MCK.py
+-rw-rw-rw-   0        0        0     1115 2023-06-28 10:50:44.000000 pyFBS-0.3.1/tests/test_SVT.py
+-rw-rw-rw-   0        0        0      956 2023-06-28 10:50:44.000000 pyFBS-0.3.1/tests/test_VPT.py
+-rw-rw-rw-   0        0        0     2661 2023-06-28 10:50:44.000000 pyFBS-0.3.1/tests/test_display.py
+-rw-rw-rw-   0        0        0      748 2023-06-28 10:50:44.000000 pyFBS-0.3.1/tests/test_modal_id.py
```

### Comparing `pyFBS-0.3.0/CONTRIBUTING.rst` & `pyFBS-0.3.1/CONTRIBUTING.rst`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/LICENSE` & `pyFBS-0.3.1/LICENSE`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/PKG-INFO` & `pyFBS-0.3.1/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,17 +1,16 @@
 Metadata-Version: 2.1
 Name: pyFBS
-Version: 0.3.0
+Version: 0.3.1
 Summary: pyFBS: A Python package for Frequency Based Substructuring and Transfer Path Analysis
 Home-page: https://pyfbs.readthedocs.io/en/latest/intro.html
 Author: Tomaž Bregar, Ahmed El Mahmoudi, Miha Kodrič, Domen Ocepek, Francesco Trainotti, Miha Pogačar, Mert Göldeli
 Author-email: info.pyfbs@gmail.com
 License: MIT license
 Keywords: pyFBS
-Platform: UNKNOWN
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Science/Research
 Classifier: Operating System :: OS Independent
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3.8
 Requires-Python: >=3.8
 License-File: LICENSE
@@ -68,8 +67,7 @@
    :target: https://opensource.org/licenses/MIT
    
 .. |codecov| image:: https://codecov.io/gl/pyFBS/pyFBS/branch/\x6d6173746572/graph/badge.svg?token=XSGM89JGMF
    :target: https://codecov.io/gl/pyFBS/pyFBS
 
 .. |codequality| image:: https://app.codacy.com/project/badge/Grade/dbb59e10c07543b6b61c083a09eac500    
    :target: https://www.codacy.com/gl/pyFBS/pyFBS/dashboard?utm_source=gitlab.com&amp;utm_medium=referral&amp;utm_content=pyFBS/pyFBS&amp;utm_campaign=Badge_Grade
-
```

### Comparing `pyFBS-0.3.0/README.rst` & `pyFBS-0.3.1/README.rst`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/data/logo-small.png` & `pyFBS-0.3.1/data/logo-small.png`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/data/logo_new.png` & `pyFBS-0.3.1/data/logo_new.png`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/pyFBS/IO.py` & `pyFBS-0.3.1/pyFBS/IO.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/pyFBS/MCK.py` & `pyFBS-0.3.1/pyFBS/MCK.py`

 * *Files 0% similar despite different names*

```diff
@@ -256,15 +256,15 @@
         directions = df[["Direction_1", "Direction_2", "Direction_3"]].values.astype(float)[:,:n_dim]       
 
         unique_nodes = nodes[np.sort(np.unique(nodes, axis=0, return_index=True)[1])]
         direction_nodes = []
         for node in unique_nodes:
             loc = np.where((nodes == node).all(axis=1))
             direction_nodes.append(directions[loc])
-        return unique_nodes, np.asarray(direction_nodes)
+        return unique_nodes, direction_nodes
 
     def loc_definition(self, node_index):
         """
         DoF index generation for the node index in the global model.
 
         :param point_index: response/excitation node index in the global model (starting with 1)
         :type response_point: int or array(int)
```

### Comparing `pyFBS-0.3.0/pyFBS/OSI.py` & `pyFBS-0.3.1/pyFBS/OSI.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/pyFBS/SEMM.py` & `pyFBS-0.3.1/pyFBS/SEMM.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/pyFBS/SVT.py` & `pyFBS-0.3.1/pyFBS/SVT.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/pyFBS/VPT.py` & `pyFBS-0.3.1/pyFBS/VPT.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/pyFBS/app_stability.py` & `pyFBS-0.3.1/pyFBS/app_stability.py`

 * *Files 1% similar despite different names*

```diff
@@ -378,15 +378,16 @@
         self.setGeometry(self.left, self.top, self.width, self.height)
         self.show()
 
         # plot
         # initialize plots
         self.fig, self.axlog = plt.subplots(facecolor='#F0F0F0', figsize=(10, 5)) #gray
         self.axlog.set_facecolor("#E1E1E1")
-        self.fig.set_tight_layout(True) #pad=2
+        self.fig.set_layout_engine('tight')
+
         self.ax = self.axlog.twinx()
         
         # self.ax.yaxis.set_label_position("right")
         
         self.ax.set_yticks(np.unique(self.poles[:, 0]))
         self.ax.set_axisbelow(True)
         self.ax.grid()
@@ -778,15 +779,15 @@
         damp_ratio = []
 
         for index_ in self.selected_ind:
             pole_, mpf_ = self.modal_id.pL_from_index(index_)
             selected_poles_id.append(pole_)
             selected_mpf_id.append(mpf_)
 
-            nat_freq_, damp_ratio_, _, __ = self.modal_id.transform_poles(pole_, mpf_.T, 1)
+            nat_freq_, damp_ratio_, _, __ = self.modal_id.transform_poles(pole_, mpf_.T, 1, self.modal_id.freq)
 
             nat_freq.append(nat_freq_[0])
             damp_ratio.append(damp_ratio_[0])
             
         self.modal_id.selected_poles = np.asarray(selected_poles_id)
         self.modal_id.selected_mpf = np.asarray(selected_mpf_id).T
         self.modal_id.nat_freq = np.asarray(nat_freq)
```

### Comparing `pyFBS-0.3.0/pyFBS/display.py` & `pyFBS-0.3.1/pyFBS/display.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/pyFBS/modal_id.py` & `pyFBS-0.3.1/pyFBS/modal_id.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,13 +1,12 @@
 import numpy as np
 from scipy import linalg
 from .utility import MAC
 from PyQt5 import QtCore, QtWidgets
 from scipy.optimize import least_squares
-import polyrat
 
 class modal_id(object):
     """
     Poly-reference frequency domain identification for modal parameter estimation as a combination of 
     poly-reference Least-Squares Complex Frequency (pLSCF) and Least-Squares Frequency Domain (LSFD) methods.
 
     :param freq: Frequency range.
@@ -26,29 +25,35 @@
     def __init__(self, freq, FRF):
         self.FRF = FRF
         self.freq = freq
         self.No = FRF.shape[1]
         self.Ni = FRF.shape[2]
         try:
             from IPython import get_ipython
-            get_ipython().magic('gui qt')
+            get_ipython().run_line_magic('gui', 'qt')
+            
         except BaseException as e:
             # issued if code runs in bare Python
             print('Could not enable IPython gui support: %s.' % e)
 
         # get QApplication instance
         self.app = QtCore.QCoreApplication.instance()
         if self.app is None:
             self.app = QtWidgets.QApplication(['app'])
             self.app.references = set()
 
     def stabilization(self):  
         from .app_stability import App
+
         self.win = App(self)
-        self.app.references.add(self.win)
+
+        if hasattr(self.app, 'references'):
+            self.app.references.add(self.win)
+        else:
+            self.app.references = {self.win}
         
     def pLSCF(self, max_order, step_order=2, stab_f=0.01, stab_damp=0.05, stab_mpf=0.05):
         """
         Poly-reference Least-Squares Complex Frequency (pLSCF) method for system's poles and modal
         participation factors estimation.
 
         :param max_order: Highest order of the polynomial basis functions.
@@ -131,14 +136,15 @@
             stab_damp (float, optional): Stability criterion for the damping component. Defaults to 0.05.
             stab_mpf (float, optional): Stability criterion for the mode participation factor component. Defaults to 0.05.
             sol_type (str, optional): Type of solver to use ('linearized' or 'iterative'). Defaults to 'iterative'.
 
         Returns:
             None
         """
+        import polyrat
                
         stab_plot = np.asarray([[0,1e-12,1e-12,0]])
         p = [[np.array([0])]]
         L = [[np.zeros((self.Ni,1))]]
         
         n_p_all = np.arange(2, max_order+1, step_order)
         for n_p in n_p_all:            
@@ -601,14 +607,16 @@
                         ndp = len(dp_values)
                         print('Mode '+ str(r+1) + ' - Passed: ' + str(ndp) + '/' + str(len(output_dp_ind)))
                     else:
                         raise Exception('For at least one mode none of the provided driving point values seems to be physically valid. If you want to proceed anyway, apply check_dp_values = False.')
 
                     output_dp_ind = np.delete(output_dp_ind, ind_2)
                     input_dp_ind = np.delete(input_dp_ind, ind_2)
+                else:
+                    ndp = len(dp_values)
 
                 # least squares solution (of absolute values due to the global/absolute phase shifts between residue vectors)
                     # columns -> modeshapes
                 b_output = np.hstack(A_r[:,input_dp_ind].T) # stacked residue columns at input_dp_dof ind
                 a_output = (np.repeat(dp_values**0.5,self.No)[:,None] * np.tile(np.eye(self.No),ndp).T)
                 x_abs_output = np.linalg.lstsq(a_output, np.abs(b_output))[0]
                 phi_o.append(x_abs_output*np.sign(A_r[:,0]))
```

### Comparing `pyFBS-0.3.0/pyFBS/utility.py` & `pyFBS-0.3.1/pyFBS/utility.py`

 * *Files 2% similar despite different names*

```diff
@@ -197,15 +197,15 @@
     if phi_1.shape[0] != phi_2.shape[0]:
         raise Exception('Input dimensions are not compatible.')
     if phi_1.ndim == 1:
         phi_1 = phi_1[:,np.newaxis]
     if phi_2.ndim == 1:
         phi_2 = phi_2[:,np.newaxis]
 
-    MAC_mat = np.abs(np.einsum('ri,ik->rk',np.conj(phi_1).T,phi_2))**2 / (np.einsum('ri,ir->r',np.conj(phi_1).T,phi_1)[:,np.newaxis] * np.einsum('ri,ir->r',np.conj(phi_2).T,phi_2))
+    MAC_mat = (np.abs(np.einsum('ri,ik->rk',np.conj(phi_1).T,phi_2))**2 / (np.einsum('ri,ir->r',np.conj(phi_1).T,phi_1)[:,np.newaxis] * np.einsum('ri,ir->r',np.conj(phi_2).T,phi_2))).real
     if output_type == 'matrix':
         return MAC_mat
     if output_type == 'diagonal':
         return np.diagonal(MAC_mat)
     else:
         raise Exception('Unknown output type.')
 
@@ -878,15 +878,15 @@
 def plot_FRF(freq, FRF_data, width=500, height=400, circle_size=4E3):
     """
     Wrapper function for plotting Frequency Response Functions (magnitude and phase) using Altair.
     :param freq: Frequency vector for x axis.
     :type freq: 1D array
     :param FRF_data: Admittance matrix to be displayed.
     :type FRF_data: 3D array
-    :param width: Width of the plot.
+    :param width: Width of the plot.freqselection_point
     :type width: int, optional
     :param height: Height of the plot.
     :type height: int, optional
     :param circle_size: Size of the circles intendted for interactive selection of displayed FRFs.
     :type circle_size: int, optional
     """
 
@@ -895,21 +895,21 @@
     for i in range(FRF_data.shape[1]):
         for j in range(FRF_data.shape[2]):
 
             df_temp = pd.DataFrame({"f" : freq, "A" : np.abs(FRF_data[:,i,j]),"ph" : np.angle(FRF_data[:,i,j]),"out" : [str(i)]*_f,\
                                     "in" : [str(j)]*_f,"out_in" : ['o'+str(i)+', i'+str(j)]*_f})
             df = df.append(df_temp)
             
-    selector = alt.selection_multi(empty='all', fields=['out_in'])
+    selector = alt.selection_point(empty='all', fields=['out_in'])
     resize = alt.selection_interval(bind='scales')
 
     base = alt.Chart(df).properties(
         width=width,
         height=height
-    ).add_selection(selector)
+    ).add_params(selector)
 
     points = base.mark_circle(size=circle_size).encode(
         alt.X('out', axis=alt.Axis(title='Output DoF')),
         alt.Y('in', axis=alt.Axis(title='Input DoF')),
         color=alt.condition(selector, 'out_in', alt.value('lightgray'), legend=None)
     )
 
@@ -918,24 +918,24 @@
         alt.Y('in'),
         text='out_in'
     )
 
     A = alt.Chart(df).mark_line().encode(
         alt.X("f", axis=alt.Axis(title='Frequency [Hz]')),
         alt.Y('A', axis=alt.Axis(title='Amplitude(Y)'), scale=alt.Scale(type='log',base=10)),
-        color='out_in').properties(width=width,height=1/2*height).add_selection(
+        color='out_in').properties(width=width,height=1/2*height).add_params(
         resize
     ).transform_filter(
         selector
     )
 
     P = alt.Chart(df).mark_line().encode(
         alt.X("f", axis=alt.Axis(title='Frequency [Hz]')),
         alt.Y('ph', axis=alt.Axis(title='Phase(Y)')),
-        color='out_in').properties(width=width,height=1/3*height).add_selection(
+        color='out_in').properties(width=width,height=1/3*height).add_params(
         resize
     ).transform_filter(
         selector
     )
 
     AP = alt.vconcat(A,P)
 
@@ -975,36 +975,36 @@
         for j in range(FR_data.shape[2]):
 
             df_temp = pd.DataFrame({"f" : freq, "A" : np.abs(FR_data[:,i,j]),"ph" : np.angle(FR_data[:,i,j]),"out" : [str(i)]*_f,\
                                     "in" : [str(j)]*_f,"out_in" : [labels[k]]*_f})
             df = df.append(df_temp)
             k=k+1
     
-    selection = alt.selection_multi(fields=['out_in'], bind='legend')
+    selection = alt.selection_point(fields=['out_in'], bind='legend')
     resize = alt.selection_interval(bind='scales')
 
     A = alt.Chart(df).mark_line().encode(
             alt.X("f", axis=alt.Axis(title='Frequency [Hz]')),
             alt.Y('A', axis=alt.Axis(title='Amplitude'), scale=alt.Scale(type='log',base=10)),
             color=alt.Color('out_in', legend=alt.Legend(title="Click to highlight")),
             opacity=alt.condition(selection, alt.value(1), alt.value(0.2))).properties(width=width,height=1/2*height
-        ).add_selection(
+        ).add_params(
             resize
-        ).add_selection(
+        ).add_params(
             selection
         )
 
     P = alt.Chart(df).mark_line().encode(
             alt.X("f", axis=alt.Axis(title='Frequency [Hz]')),
             alt.Y('ph', axis=alt.Axis(title='Phase')),
             opacity=alt.condition(selection, alt.value(1), alt.value(0.2)),
             color='out_in').properties(width=width,height=1/3*height
-        ).add_selection(
+        ).add_params(
             resize
-        ).add_selection(
+        ).add_params(
             selection
         )
 
     if amplitude_only == False:
         AP = alt.vconcat(A,P)
     else:
         AP = A
@@ -1049,25 +1049,25 @@
         for j in range(y.shape[2]):
 
             df_temp = pd.DataFrame({"x" : x, "y" : y[:,i,j],"out" : [str(i)]*_x,\
                                     "in" : [str(j)]*_x,"out_in" : [labels[k]]*_x})
             df = df.append(df_temp)
             k=k+1
     
-    selection = alt.selection_multi(fields=['out_in'], bind='legend')
+    selection = alt.selection_point(fields=['out_in'], bind='legend')
     resize = alt.selection_interval(bind='scales')
     
     A = alt.Chart(df, title=title).mark_line().encode(
             alt.X("x", axis=alt.Axis(title=x_label)),
             alt.Y('y', axis=alt.Axis(title=y_label), scale=alt.Scale()),
             color=alt.Color('out_in', legend=alt.Legend(title="Click to highlight")),
             opacity=alt.condition(selection, alt.value(1), alt.value(0.2))).properties(width=width,height=height
-        ).add_selection(
+        ).add_params(
             resize
-        ).add_selection(
+        ).add_params(
             selection
         )
         
     return A
 
 def plot_comparison_multiple(freq,master_Y, labels):
 
@@ -1082,42 +1082,42 @@
                                         "in" : [str(j)]*_f,"out_in" : ['o'+str(i)+', i'+str(j)]*_f, "master" : str(i_master), "ID" : [''+str(i)+','+str(j)+' '+str(labels[i_master])]*_f})
                 df = df.append(df_temp)
 
     width = 500
     height = 300
     circle_size = 1e3
 
-    selector = alt.selection_multi(empty='all', fields=['out_in'])
+    selector = alt.selection_point(empty='all', fields=['out_in'])
     resize = alt.selection_interval(bind='scales')
 
     base = alt.Chart(df).properties(
         width=width,
         height=height
-    ).add_selection(selector)
+    ).add_params(selector)
 
     points = base.mark_circle(size=circle_size).encode(
         alt.X('in', axis=alt.Axis(title='Output DoF')),
         alt.Y('out', axis=alt.Axis(title='Input DoF')),
         color=alt.condition(selector, 'out_in', alt.value('lightgray'),legend = None)
     )
 
 
     A = alt.Chart(df).mark_line().encode(
         alt.X("f", axis=alt.Axis(title='Frequency [Hz]')),
         alt.Y('A', axis=alt.Axis(title='Amplitude(Y)'), scale=alt.Scale(type='log',base=10)),
-        color=alt.Color('ID', legend=alt.Legend())).properties(width=width,height=1/2*height).add_selection(
+        color=alt.Color('ID', legend=alt.Legend())).properties(width=width,height=1/2*height).add_params(
         resize
     ).transform_filter(
         selector
     )
 
     P = alt.Chart(df).mark_line().encode(
         alt.X("f", axis=alt.Axis(title='Frequency [Hz]')),
         alt.Y('ph', axis=alt.Axis(title='Phase(Y)')),
-        color='ID').properties(width=width,height=1/3*height).add_selection(
+        color='ID').properties(width=width,height=1/3*height).add_params(
         resize
     ).transform_filter(
         selector
     )
 
     AP = alt.vconcat(A,P)
 
@@ -1154,15 +1154,15 @@
         line={'color':'out'},
         color='out',
         opacity=opacity
     ).encode(
         alt.X('f', axis=alt.Axis(title='Frequency [Hz]')),
         alt.Y('coh', axis=alt.Axis(title='Coherence [/]')),
         color=alt.value(color)
-    ).add_selection(
+    ).add_params(
         resize
     ).properties(
         width=width,
         height=height
     )
 
     return A
@@ -1189,21 +1189,21 @@
     for i in range(coh_data.shape[1]):
         for j in range(coh_data.shape[2]):
 
             df_temp = pd.DataFrame({"f" : freq, "coh" : np.abs(coh_data[:,i,j]),"out" : [str(i)]*_f,\
                                     "in" : [str(j)]*_f,"out_in" : [str(i)+str(j)]*_f, "avg_coh" : [str(np.round(np.average(coh_data[:,i,j]),3))]*_f})
             df = df.append(df_temp)
             
-    selector = alt.selection_multi(empty='all', fields=['out_in'])
+    selector = alt.selection_point(empty='all', fields=['out_in'])
     resize = alt.selection_interval(bind='scales')
 
     base = alt.Chart(df).properties(
         width=width,
         height=height
-    ).add_selection(selector)
+    ).add_params(selector)
 
     points = base.mark_circle().encode(
         alt.X('out', axis=alt.Axis(title='Output DoF')),
         alt.Y('in', axis=alt.Axis(title='Input DoF')),
         size=alt.Size('avg_coh', scale=alt.Scale(range=[circle_size/2, circle_size]), legend=None),
         color=alt.condition(selector, 'out_in', alt.value('lightgray'), legend=None)
     )
@@ -1220,15 +1220,15 @@
         opacity=opacity
     ).encode(
         alt.X('f', axis=alt.Axis(title='Frequency [Hz]')),
         alt.Y('coh', axis=alt.Axis(title='Coherence [/]')),
         color='out_in'
     ).transform_filter(
         selector
-    ).add_selection(
+    ).add_params(
         resize
     )
 
     return points + text | A
 
 def tranfer_path(freq, u3_partial, width=700, height=150):
     """
```

### Comparing `pyFBS-0.3.0/pyFBS.egg-info/PKG-INFO` & `pyFBS-0.3.1/pyFBS.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,17 +1,16 @@
 Metadata-Version: 2.1
 Name: pyFBS
-Version: 0.3.0
+Version: 0.3.1
 Summary: pyFBS: A Python package for Frequency Based Substructuring and Transfer Path Analysis
 Home-page: https://pyfbs.readthedocs.io/en/latest/intro.html
 Author: Tomaž Bregar, Ahmed El Mahmoudi, Miha Kodrič, Domen Ocepek, Francesco Trainotti, Miha Pogačar, Mert Göldeli
 Author-email: info.pyfbs@gmail.com
 License: MIT license
 Keywords: pyFBS
-Platform: UNKNOWN
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Science/Research
 Classifier: Operating System :: OS Independent
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3.8
 Requires-Python: >=3.8
 License-File: LICENSE
@@ -68,8 +67,7 @@
    :target: https://opensource.org/licenses/MIT
    
 .. |codecov| image:: https://codecov.io/gl/pyFBS/pyFBS/branch/\x6d6173746572/graph/badge.svg?token=XSGM89JGMF
    :target: https://codecov.io/gl/pyFBS/pyFBS
 
 .. |codequality| image:: https://app.codacy.com/project/badge/Grade/dbb59e10c07543b6b61c083a09eac500    
    :target: https://www.codacy.com/gl/pyFBS/pyFBS/dashboard?utm_source=gitlab.com&amp;utm_medium=referral&amp;utm_content=pyFBS/pyFBS&amp;utm_campaign=Badge_Grade
-
```

### Comparing `pyFBS-0.3.0/pyFBS.egg-info/SOURCES.txt` & `pyFBS-0.3.1/pyFBS.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/setup.py` & `pyFBS-0.3.1/setup.py`

 * *Files identical despite different names*

```diff
@@ -66,9 +66,9 @@
     include_package_data=True,
     package_data={'': extra_files},
     keywords='pyFBS',
     name='pyFBS',
     packages=["pyFBS"],
     test_suite='tests',
     url='https://pyfbs.readthedocs.io/en/latest/intro.html',
-    version='0.3.0',
+    version='0.3.1',
 )
```

### Comparing `pyFBS-0.3.0/tests/build_examples.py` & `pyFBS-0.3.1/tests/build_examples.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/tests/conftest.py` & `pyFBS-0.3.1/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/tests/test_IO.py` & `pyFBS-0.3.1/tests/test_IO.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/tests/test_MCK.py` & `pyFBS-0.3.1/tests/test_MCK.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/tests/test_SVT.py` & `pyFBS-0.3.1/tests/test_SVT.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/tests/test_VPT.py` & `pyFBS-0.3.1/tests/test_VPT.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/tests/test_display.py` & `pyFBS-0.3.1/tests/test_display.py`

 * *Files identical despite different names*

### Comparing `pyFBS-0.3.0/tests/test_modal_id.py` & `pyFBS-0.3.1/tests/test_modal_id.py`

 * *Files identical despite different names*


# Comparing `tmp/matan-0.1.5.2.7.3.dev4.tar.gz` & `tmp/MatAn-0.1.5.2.7.dev1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "matan-0.1.5.2.7.3.dev4.tar", last modified: Wed Jun 28 09:31:47 2023, max compression
+gzip compressed data, was "MatAn-0.1.5.2.7.dev1.tar", last modified: Tue Jun 27 13:59:08 2023, max compression
```

## Comparing `matan-0.1.5.2.7.3.dev4.tar` & `MatAn-0.1.5.2.7.dev1.tar`

### file list

```diff
@@ -1,26 +1,21 @@
-drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-28 09:31:47.660078 matan-0.1.5.2.7.3.dev4/
--rw-r--r--   0 uuu       (1000) uuu       (1000)    34670 2023-06-18 20:22:37.000000 matan-0.1.5.2.7.3.dev4/LICENSE
--rw-r--r--   0 uuu       (1000) uuu       (1000)     4258 2023-06-28 09:31:47.660078 matan-0.1.5.2.7.3.dev4/PKG-INFO
--rw-r--r--   0 uuu       (1000) uuu       (1000)     3337 2023-06-24 20:58:42.000000 matan-0.1.5.2.7.3.dev4/README.md
-drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-28 09:31:47.660078 matan-0.1.5.2.7.3.dev4/matan/
--rw-r--r--   0 uuu       (1000) uuu       (1000)       84 2023-06-19 18:03:25.000000 matan-0.1.5.2.7.3.dev4/matan/__init__.py
--rw-r--r--   0 uuu       (1000) uuu       (1000)      156 2023-06-19 18:03:25.000000 matan-0.1.5.2.7.3.dev4/matan/_misc.py
--rw-r--r--   0 uuu       (1000) uuu       (1000)     4960 2023-06-19 18:03:25.000000 matan-0.1.5.2.7.3.dev4/matan/files.py
-drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-28 09:31:47.660078 matan-0.1.5.2.7.3.dev4/matan/polymers/
--rw-r--r--   0 uuu       (1000) uuu       (1000)        0 2023-06-19 19:18:34.000000 matan-0.1.5.2.7.3.dev4/matan/polymers/__init__.py
-drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-28 09:31:47.660078 matan-0.1.5.2.7.3.dev4/matan/polymers/charpy/
--rw-r--r--   0 uuu       (1000) uuu       (1000)      815 2023-06-19 19:11:47.000000 matan-0.1.5.2.7.3.dev4/matan/polymers/charpy/__init__.py
-drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-28 09:31:47.660078 matan-0.1.5.2.7.3.dev4/matan/polymers/tensile/
-drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-28 09:31:47.660078 matan-0.1.5.2.7.3.dev4/matan/polymers/tensile/ISO527/
--rw-r--r--   0 uuu       (1000) uuu       (1000)     2710 2023-06-24 22:10:32.000000 matan-0.1.5.2.7.3.dev4/matan/polymers/tensile/ISO527/__init__.py
--rw-r--r--   0 uuu       (1000) uuu       (1000)    13784 2023-06-28 07:21:10.000000 matan-0.1.5.2.7.3.dev4/matan/polymers/tensile/__init__.py
--rw-r--r--   0 uuu       (1000) uuu       (1000)       33 2023-06-28 07:43:43.000000 matan-0.1.5.2.7.3.dev4/matan/polymers/tensile/misc.py
--rw-r--r--   0 uuu       (1000) uuu       (1000)     7948 2023-06-27 15:16:07.000000 matan-0.1.5.2.7.3.dev4/matan/sample.py
-drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-28 09:31:47.660078 matan-0.1.5.2.7.3.dev4/matan.egg-info/
--rw-r--r--   0 uuu       (1000) uuu       (1000)     4258 2023-06-28 09:31:47.000000 matan-0.1.5.2.7.3.dev4/matan.egg-info/PKG-INFO
--rw-r--r--   0 uuu       (1000) uuu       (1000)      413 2023-06-28 09:31:47.000000 matan-0.1.5.2.7.3.dev4/matan.egg-info/SOURCES.txt
--rw-r--r--   0 uuu       (1000) uuu       (1000)        1 2023-06-28 09:31:47.000000 matan-0.1.5.2.7.3.dev4/matan.egg-info/dependency_links.txt
--rw-r--r--   0 uuu       (1000) uuu       (1000)       17 2023-06-28 09:31:47.000000 matan-0.1.5.2.7.3.dev4/matan.egg-info/requires.txt
--rw-r--r--   0 uuu       (1000) uuu       (1000)        6 2023-06-28 09:31:47.000000 matan-0.1.5.2.7.3.dev4/matan.egg-info/top_level.txt
--rw-r--r--   0 uuu       (1000) uuu       (1000)      103 2023-06-28 09:31:47.660078 matan-0.1.5.2.7.3.dev4/setup.cfg
--rw-r--r--   0 uuu       (1000) uuu       (1000)     1698 2023-06-28 09:29:27.000000 matan-0.1.5.2.7.3.dev4/setup.py
+drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-27 13:59:08.299691 MatAn-0.1.5.2.7.dev1/
+-rw-r--r--   0 uuu       (1000) uuu       (1000)    34670 2023-06-18 20:22:37.000000 MatAn-0.1.5.2.7.dev1/LICENSE
+-rw-r--r--   0 uuu       (1000) uuu       (1000)     4218 2023-06-27 13:59:08.299691 MatAn-0.1.5.2.7.dev1/PKG-INFO
+-rw-r--r--   0 uuu       (1000) uuu       (1000)     3337 2023-06-24 20:58:42.000000 MatAn-0.1.5.2.7.dev1/README.md
+drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-27 13:59:08.299691 MatAn-0.1.5.2.7.dev1/matan/
+drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-27 13:59:08.299691 MatAn-0.1.5.2.7.dev1/matan/MatAn.egg-info/
+-rw-r--r--   0 uuu       (1000) uuu       (1000)     4218 2023-06-27 13:59:08.000000 MatAn-0.1.5.2.7.dev1/matan/MatAn.egg-info/PKG-INFO
+-rw-r--r--   0 uuu       (1000) uuu       (1000)      348 2023-06-27 13:59:08.000000 MatAn-0.1.5.2.7.dev1/matan/MatAn.egg-info/SOURCES.txt
+-rw-r--r--   0 uuu       (1000) uuu       (1000)        1 2023-06-27 13:59:08.000000 MatAn-0.1.5.2.7.dev1/matan/MatAn.egg-info/dependency_links.txt
+-rw-r--r--   0 uuu       (1000) uuu       (1000)       17 2023-06-27 13:59:08.000000 MatAn-0.1.5.2.7.dev1/matan/MatAn.egg-info/requires.txt
+-rw-r--r--   0 uuu       (1000) uuu       (1000)        9 2023-06-27 13:59:08.000000 MatAn-0.1.5.2.7.dev1/matan/MatAn.egg-info/top_level.txt
+drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-27 13:59:08.299691 MatAn-0.1.5.2.7.dev1/matan/polymers/
+-rw-r--r--   0 uuu       (1000) uuu       (1000)        0 2023-06-19 19:18:34.000000 MatAn-0.1.5.2.7.dev1/matan/polymers/__init__.py
+drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-27 13:59:08.299691 MatAn-0.1.5.2.7.dev1/matan/polymers/charpy/
+-rw-r--r--   0 uuu       (1000) uuu       (1000)      815 2023-06-19 19:11:47.000000 MatAn-0.1.5.2.7.dev1/matan/polymers/charpy/__init__.py
+drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-27 13:59:08.299691 MatAn-0.1.5.2.7.dev1/matan/polymers/tensile/
+drwxr-xr-x   0 uuu       (1000) uuu       (1000)        0 2023-06-27 13:59:08.299691 MatAn-0.1.5.2.7.dev1/matan/polymers/tensile/ISO527/
+-rw-r--r--   0 uuu       (1000) uuu       (1000)     2710 2023-06-24 22:10:32.000000 MatAn-0.1.5.2.7.dev1/matan/polymers/tensile/ISO527/__init__.py
+-rw-r--r--   0 uuu       (1000) uuu       (1000)    13537 2023-06-24 22:18:44.000000 MatAn-0.1.5.2.7.dev1/matan/polymers/tensile/__init__.py
+-rw-r--r--   0 uuu       (1000) uuu       (1000)      103 2023-06-27 13:59:08.303691 MatAn-0.1.5.2.7.dev1/setup.cfg
+-rw-r--r--   0 uuu       (1000) uuu       (1000)     1612 2023-06-27 13:54:24.000000 MatAn-0.1.5.2.7.dev1/setup.py
```

### Comparing `matan-0.1.5.2.7.3.dev4/LICENSE` & `MatAn-0.1.5.2.7.dev1/LICENSE`

 * *Files identical despite different names*

### Comparing `matan-0.1.5.2.7.3.dev4/PKG-INFO` & `MatAn-0.1.5.2.7.dev1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
-Name: matan
-Version: 0.1.5.2.7.3.dev4
+Name: MatAn
+Version: 0.1.5.2.7.dev1
 Summary: Material analysis package to plot or extract properties like tensile modulus etc. 
 Home-page: https://codeberg.org/309631/matan
 Author: Igor Cudnik
 Author-email: igor.cudnik@student.put.poznan.pl
 License: GPLv3
-Keywords: material analysis,ISO 527,ISO 527-1,polymers analysis,material analysis,tensile test,charpy
+Keywords: material analysis,ISO 527,ISO 527-1,polymers analysis
 Classifier: Development Status :: 1 - Planning
 Classifier: Intended Audience :: Science/Research
 Classifier: Topic :: Scientific/Engineering
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
```

### Comparing `matan-0.1.5.2.7.3.dev4/README.md` & `MatAn-0.1.5.2.7.dev1/README.md`

 * *Files identical despite different names*

### Comparing `matan-0.1.5.2.7.3.dev4/matan/polymers/charpy/__init__.py` & `MatAn-0.1.5.2.7.dev1/matan/polymers/charpy/__init__.py`

 * *Files identical despite different names*

### Comparing `matan-0.1.5.2.7.3.dev4/matan/polymers/tensile/ISO527/__init__.py` & `MatAn-0.1.5.2.7.dev1/matan/polymers/tensile/ISO527/__init__.py`

 * *Files identical despite different names*

### Comparing `matan-0.1.5.2.7.3.dev4/matan/polymers/tensile/__init__.py` & `MatAn-0.1.5.2.7.dev1/matan/polymers/tensile/__init__.py`

 * *Files 7% similar despite different names*

```diff
@@ -9,15 +9,15 @@
         def __init__(self,
                      width,
                      thickness,
                      name=None,
                      elongation_array: Union[list, np.array] =None,
                      force_array: Union[list, np.array] =None,
                      force_units="N",
-                     length_units="mm",
+                     lenght_units="mm",
                    norm="ISO527"
                      ):
             global properties
             properties = importlib.import_module(f".{norm}", package=__package__)
             """initializer of engineering values class
 
             This class is used to menage the properties of engineering values
@@ -31,24 +31,25 @@
             --------
             FIXME: Add docs.
 
             """
             
             self.name=name
             self.force_units = force_units
-            self.length_units=length_units
+            self.lenght_units=lenght_units
             self.thickness=thickness,
             self.width=width
             self.stress, self.strain=None,None
         def _calculate(self,
                       thickness:float,
                       width:float,
                       elongation_array,
                       force_array,
                       ):
+            # breakpoint()
             """Calculates the engineering stress and strain
 
             This method is used to calculate engineering stress and strain from height
 
             Parameters
             ----------
             thickness : float
@@ -57,20 +58,20 @@
                 larger initial dimension of the rectangular cross-section in the central part of the test specimen
             elongation_array : list
                 list of the sample elongation
             force_array : list
                 list of the forces from the machinge
             force_units : str
                 Units used as force units. Newtons [N] by default. Use shorten strings, as it is used in output
-            length : str
+            lenght_units : str
                 Units used for lenght, mm by default. Use short strings, as they are used in output. If you wanna use percent, just use % sign or percent
             """
             
 
-            if self.length_units=="%" or self.length_units=="percent":
+            if self.lenght_units=="%" or self.lenght_units=="percent":
                 self.percent_strain=True
             else:
                 self.percent_strain=False
 
 
             if  self.stress is  None and self.strain is None:
                 initial_area=thickness*width
@@ -169,23 +170,23 @@
             """
 
             E=properties.tensile_modulus(self.stress,
                                          self.strain,
                                          percent_strain=self.percent_strain
                                          )
             if plot:
-                label=rf"Young's modulus {int(E.tensile_modulus)} $\left[\frac{{{self.force_units}}}{{{self.length}^2}}\right]$"
+                label=rf"Young's modulus {int(E.tensile_modulus)} $\left[\frac{{{self.force_units}}}{{{self.lenght_units}^2}}\right]$"
                 if r2:
                     label+="\n"+rf"$R^{{{2}}}={E.r2}$"
                     plt.plot(E.module_strain,
                              E.module_stress,
                              label=label
                              )
             if output:
-                print(f"Tensile modulus is equal to {int(E.tensile_modulus)} [{self.force_units}/{self.length}^2]")
+                print(f"Tensile modulus is equal to {int(E.tensile_modulus)} [{self.force_units}/{self.lenght_units}^2]")
             return   E.tensile_modulus
 
                 
         def set(self,
                 engineering_stress: Union[list, np.array] =None,
                 engineering_strain:Union[list, np.array] =None,
                 # TODO: gives TypeError: only size-1 arrays can be converted to Python scalars while using numpy array
@@ -228,34 +229,32 @@
             Examples
             --------
             FIXME: Add docs.
 
             """
             plt.plot(self.strain,self.stress, label=self.name)
             plt.title(self.name)
-            plt.ylabel(rf"Stress $\left[\frac{{{self.force_units}}}{{{self.length_units}^2}}\right]$")
-            plt.xlabel(f"Strain [{self.length_units}]")
+            plt.ylabel(rf"Stress $\left[\frac{{{self.force_units}}}{{{self.lenght_units}^2}}\right]$")
+            plt.xlabel(f"Strain [{self.lenght_units}]")
             plt.legend()
             if show:
                 plt.show()
 
 class _real_values(_engineering_values):
 
         def __init__(self,
                      name,
                      thickness,
                      width,
-                     stress,
-                     strain,
                      force_units,
-                     length_units,
+                     lenght_units,
                      ):
             self.force_units=force_units
-            self.length_units=length_units
-            if length_units=="%" or length_units=="percent":
+            self.lenght_units=lenght_units
+            if lenght_units=="%" or lenght_units=="percent":
                 self.percent_strain=True
             else:
                 self.percent_strain=False
 
     
             _engineering_values.__init__(self,
                                         name=name,
@@ -263,17 +262,16 @@
                                         width=width
                                         )
             self.name=name + " [real]"
             width=self.width
             thickness=self.thickness
             super().__init__(self,
                              name=self.name,
-                             thickness=self.thickness
+                             thickness=thickness
                              )
-            self._calculate(stress, strain)
 
         def _calculate(self, stress, strain):
             """
                 Calculates the true stress and strain, from engineering values.
                 Read more there:
                         https://courses.ansys.com/index.php/courses/topics-in-metal-plasticity/lessons/how-to-define-a-multilinear-hardening-plasticity-model-lesson-1/
             
@@ -302,53 +300,49 @@
 
 
 
 
 class _tensile:
     
     def __init__(self,
-                 name: str,
+                 name:str,
                  thickness: Union[float, int],
-                 width: Union[float, int],
-                 elongation_array: Union[list, np.array] = None,
-                 force_array: Union[list, np.array] = None,
-                 stress_array: Union[list, np.array] = None,
-                 strain_array: Union[list, np.array] = None,
-                 force_units: str = "N",
-                 length_units: str = "mm"
+                 width: Union[float, int] ,
+                 elongation_array: Union[list, np.array] =None,
+                 force_array: Union[list, np.array] =None,
+                 stress_array: Union[list, np.array] =None,
+                 strain_array: Union[list, np.array] =None,
+                 force_units: str="N",
+                 lenght_units: str="mm"
                  ):
-        self.name, self.thickness, self.width=name, thickness, width
-        self.engineering_values = _engineering_values(
+        self.engineering_values=_engineering_values(
             width=width,
             thickness=thickness,
             name=name,
             elongation_array=elongation_array,
             force_array=force_array,
             force_units=force_units,
-            length_units=length_units
+            lenght_units=lenght_units
         )
-        self.force_units, self.length_units = force_units, length_units
-        self.stress_units = f"{force_units}/{length_units}^2"
-        self.strain_units = f"{length_units}/{length_units}"
+        self.force_units, self.lenght_units=force_units,lenght_units
+        self.stress_units=f"{force_units}/{lenght_units}^2"
+        self.strain_units=f"{lenght_units}/{lenght_units}"
         if stress_array is None and strain_array is None:
-            if elongation_array is None and force_array is None:
-                raise ValueError("None of elongation/force or stress/strain arrays are defined!")
-            elif thickness is None:
-                raise ValueError("Thickness is not defined!")
-            elif width is None:
-                raise ValueError("Width is not defined!")
-            else:
-                self.elongation_array = elongation_array
-                self.force_array = force_array
-                self.engineering_values._calculate(thickness, width, elongation_array, force_array)
+                if elongation_array is None and force_array is None:
+                    raise ValueError("None of elongation/force or stress/strain arrays are defined!")
+                elif thickness is None:
+                    raise ValueError("Thickness is not defined!")
+                elif width is None:
+                    raise ValueError(" Width is not defined!")
+                else:
+                    self.elongation_array=elongation_array
+                    self.force_array=force_array
+                    self.engineering_values._calculate(thickness, width, elongation_array, force_array)
         else:
-            self.engineering_values.set(stress_array, strain_array)
+                self.engineering_values.set(stress_array, strain_array)
 
-    def convert2real(self):
-        self.real_values = _real_values(self.name,
-                                        self.thickness,
-                                        self.width,
-                                        self.engineering_values.stress,
-                                        self.engineering_values.strain,
-                                        self.force_units,
-                                        self.length_units)
-    f
+        def convert2real():
+            self.real_values=_real_values(self.name,
+                                          self.thickness,
+                                          self.width,
+                                          self.force_units,
+                                          self.lenght_units)
```

### Comparing `matan-0.1.5.2.7.3.dev4/matan.egg-info/PKG-INFO` & `MatAn-0.1.5.2.7.dev1/matan/MatAn.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
-Name: matan
-Version: 0.1.5.2.7.3.dev4
+Name: MatAn
+Version: 0.1.5.2.7.dev1
 Summary: Material analysis package to plot or extract properties like tensile modulus etc. 
 Home-page: https://codeberg.org/309631/matan
 Author: Igor Cudnik
 Author-email: igor.cudnik@student.put.poznan.pl
 License: GPLv3
-Keywords: material analysis,ISO 527,ISO 527-1,polymers analysis,material analysis,tensile test,charpy
+Keywords: material analysis,ISO 527,ISO 527-1,polymers analysis
 Classifier: Development Status :: 1 - Planning
 Classifier: Intended Audience :: Science/Research
 Classifier: Topic :: Scientific/Engineering
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
```

### Comparing `matan-0.1.5.2.7.3.dev4/setup.py` & `MatAn-0.1.5.2.7.dev1/setup.py`

 * *Files 6% similar despite different names*

```diff
@@ -3,32 +3,29 @@
 
 
 def readme():
     with open('README.md') as f:
         return f.read()
 
 setup(
-    name='matan',
-    version='0.1.5.2.7.3dev4',
+    name='MatAn',
+    version='0.1.5.2.7.dev1',
     license='GPLv3',
     author="Igor Cudnik",
     author_email='igor.cudnik@student.put.poznan.pl',
     description='Material analysis package to plot or extract properties like tensile modulus etc. ',
     long_description=readme(),
     long_description_content_type='text/markdown',
-    packages=find_packages(),
-    # package_dir={'': 'matan/'},
+    packages=find_packages('matan'),
+    package_dir={'': 'matan'},
     url='https://codeberg.org/309631/matan',
     keywords=['material analysis',
               'ISO 527',
               'ISO 527-1',
-              'polymers analysis',
-              'material analysis',
-              'tensile test',
-              'charpy'],
+              'polymers analysis'],
     install_requires=[
           'numpy',
         'matplotlib'
       ],
     classifiers=[
     # How mature is this project? Common values are
     #   3 - Alpha
```


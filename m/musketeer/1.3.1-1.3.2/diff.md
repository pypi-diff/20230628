# Comparing `tmp/musketeer-1.3.1.tar.gz` & `tmp/musketeer-1.3.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "musketeer-1.3.1.tar", last modified: Sun Jun 25 23:16:47 2023, max compression
+gzip compressed data, was "musketeer-1.3.2.tar", last modified: Wed Jun 28 10:52:24 2023, max compression
```

## Comparing `musketeer-1.3.1.tar` & `musketeer-1.3.2.tar`

### file list

```diff
@@ -1,43 +1,47 @@
-drwxrwxrwx   0        0        0        0 2023-06-25 23:16:37.125744 musketeer-1.3.1/
--rw-rw-rw-   0        0        0      118 2023-06-25 21:15:48.000000 musketeer-1.3.1/.flake8
--rw-rw-rw-   0        0        0      107 2023-06-25 23:14:54.000000 musketeer-1.3.1/.gitignore
--rw-rw-rw-   0        0        0     1093 2021-05-07 10:14:54.000000 musketeer-1.3.1/LICENSE
--rw-rw-rw-   0        0        0       35 2021-07-24 12:56:15.000000 musketeer-1.3.1/MANIFEST.in
--rw-rw-rw-   0        0        0      867 2023-06-25 23:16:47.628323 musketeer-1.3.1/PKG-INFO
--rw-rw-rw-   0        0        0      186 2023-02-23 14:24:54.000000 musketeer-1.3.1/README.md
-drwxrwxrwx   0        0        0        0 2023-06-25 23:16:36.991743 musketeer-1.3.1/cx_freeze/
--rw-rw-rw-   0        0        0    21310 2023-06-25 23:03:25.000000 musketeer-1.3.1/cx_freeze/logo 48px.ico
--rw-rw-rw-   0        0        0    38648 2023-06-25 00:00:13.000000 musketeer-1.3.1/cx_freeze/logo 512px.png
--rw-rw-rw-   0        0        0      781 2023-06-25 23:10:18.000000 musketeer-1.3.1/cx_freeze/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-25 23:16:37.081744 musketeer-1.3.1/musketeer/
--rw-rw-rw-   0        0        0       23 2023-06-25 22:01:09.000000 musketeer-1.3.1/musketeer/__init__.py
--rw-rw-rw-   0        0        0    12128 2023-06-25 21:46:41.000000 musketeer-1.3.1/musketeer/__main__.py
--rw-rw-rw-   0        0        0     1082 2023-06-24 19:22:11.000000 musketeer-1.3.1/musketeer/combineResiduals.py
--rw-rw-rw-   0        0        0     8068 2023-06-25 22:00:40.000000 musketeer-1.3.1/musketeer/contributingSpecies.py
--rw-rw-rw-   0        0        0    19168 2023-06-25 22:00:19.000000 musketeer-1.3.1/musketeer/contributors.py
--rw-rw-rw-   0        0        0     8404 2023-06-24 19:22:11.000000 musketeer-1.3.1/musketeer/editData.py
--rw-rw-rw-   0        0        0    14743 2023-06-25 21:59:35.000000 musketeer-1.3.1/musketeer/equilibriumConstants.py
--rw-rw-rw-   0        0        0     8433 2023-06-24 19:22:11.000000 musketeer-1.3.1/musketeer/fitSignals.py
--rw-rw-rw-   0        0        0    10506 2023-06-24 19:22:11.000000 musketeer-1.3.1/musketeer/knownSignals.py
--rw-rw-rw-   0        0        0     2007 2023-06-25 00:19:37.000000 musketeer-1.3.1/musketeer/logo 48px.png
--rw-rw-rw-   0        0        0    38648 2023-06-25 00:00:13.000000 musketeer-1.3.1/musketeer/logo 512px.png
--rw-rw-rw-   0        0        0     5452 2023-06-24 19:16:36.000000 musketeer-1.3.1/musketeer/moduleFrame.py
--rw-rw-rw-   0        0        0     8875 2023-06-24 19:22:11.000000 musketeer-1.3.1/musketeer/patchMatplotlib.py
--rw-rw-rw-   0        0        0     1266 2023-06-24 19:22:11.000000 musketeer-1.3.1/musketeer/proportionality.py
--rw-rw-rw-   0        0        0    12401 2023-05-04 16:25:44.000000 musketeer-1.3.1/musketeer/scrolledFrame.py
--rw-rw-rw-   0        0        0    22755 2023-06-25 22:00:34.000000 musketeer-1.3.1/musketeer/speciation.py
--rw-rw-rw-   0        0        0      607 2023-04-19 11:14:04.000000 musketeer-1.3.1/musketeer/style.py
--rw-rw-rw-   0        0        0    17174 2023-06-24 19:22:11.000000 musketeer-1.3.1/musketeer/table.py
--rw-rw-rw-   0        0        0     9381 2023-06-24 19:22:11.000000 musketeer-1.3.1/musketeer/titration.py
--rw-rw-rw-   0        0        0    48125 2023-06-24 19:22:11.000000 musketeer-1.3.1/musketeer/titrationFrame.py
--rw-rw-rw-   0        0        0     8961 2023-06-25 22:45:55.000000 musketeer-1.3.1/musketeer/titrationReader.py
--rw-rw-rw-   0        0        0    17310 2023-06-25 22:00:29.000000 musketeer-1.3.1/musketeer/totalConcentrations.py
--rw-rw-rw-   0        0        0     2903 2023-03-09 17:30:25.000000 musketeer-1.3.1/musketeer/windowsHighDpiPatch.py
-drwxrwxrwx   0        0        0        0 2023-06-25 23:16:47.626324 musketeer-1.3.1/musketeer.egg-info/
--rw-rw-rw-   0        0        0      867 2023-06-25 23:16:46.000000 musketeer-1.3.1/musketeer.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      895 2023-06-25 23:16:47.000000 musketeer-1.3.1/musketeer.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-25 23:16:46.000000 musketeer-1.3.1/musketeer.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       84 2023-06-25 23:16:46.000000 musketeer-1.3.1/musketeer.egg-info/requires.txt
--rw-rw-rw-   0        0        0       10 2023-06-25 23:16:46.000000 musketeer-1.3.1/musketeer.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-25 23:16:47.632322 musketeer-1.3.1/setup.cfg
--rw-rw-rw-   0        0        0     1836 2023-04-19 11:14:04.000000 musketeer-1.3.1/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:52:24.743877 musketeer-1.3.2/
+-rw-rw-rw-   0        0        0      118 2023-06-25 21:15:48.000000 musketeer-1.3.2/.flake8
+-rw-rw-rw-   0        0        0      107 2023-06-25 23:14:54.000000 musketeer-1.3.2/.gitignore
+-rw-rw-rw-   0        0        0     1093 2021-05-07 10:14:54.000000 musketeer-1.3.2/LICENSE
+-rw-rw-rw-   0        0        0       35 2021-07-24 12:56:15.000000 musketeer-1.3.2/MANIFEST.in
+-rw-rw-rw-   0        0        0     4345 2023-06-28 10:52:24.737973 musketeer-1.3.2/PKG-INFO
+-rw-rw-rw-   0        0        0     3664 2023-06-26 16:34:36.000000 musketeer-1.3.2/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 10:52:23.049288 musketeer-1.3.2/cx_freeze/
+-rw-rw-rw-   0        0        0    21310 2023-06-25 23:03:25.000000 musketeer-1.3.2/cx_freeze/logo 48px.ico
+-rw-rw-rw-   0        0        0    38648 2023-06-25 00:00:13.000000 musketeer-1.3.2/cx_freeze/logo 512px.png
+-rw-rw-rw-   0        0        0       46 2023-06-25 23:30:16.000000 musketeer-1.3.2/cx_freeze/musketeer_loader.py
+-rw-rw-rw-   0        0        0      941 2023-06-26 00:35:56.000000 musketeer-1.3.2/cx_freeze/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:52:23.117027 musketeer-1.3.2/examples/
+-rw-rw-rw-   0        0        0    19329 2023-06-27 13:13:17.000000 musketeer-1.3.2/examples/NMR_example.fit
+-rw-rw-rw-   0        0        0    97169 2023-06-26 16:07:00.000000 musketeer-1.3.2/examples/UV-Vis_example.fit
+drwxrwxrwx   0        0        0        0 2023-06-28 10:52:24.356653 musketeer-1.3.2/musketeer/
+-rw-rw-rw-   0        0        0       23 2023-06-28 10:51:20.000000 musketeer-1.3.2/musketeer/__init__.py
+-rw-rw-rw-   0        0        0    12128 2023-06-28 09:00:51.000000 musketeer-1.3.2/musketeer/__main__.py
+-rw-rw-rw-   0        0        0     1082 2023-06-24 19:22:11.000000 musketeer-1.3.2/musketeer/combineResiduals.py
+-rw-rw-rw-   0        0        0     8068 2023-06-25 22:00:40.000000 musketeer-1.3.2/musketeer/contributingSpecies.py
+-rw-rw-rw-   0        0        0    19168 2023-06-25 22:00:19.000000 musketeer-1.3.2/musketeer/contributors.py
+-rw-rw-rw-   0        0        0     8489 2023-06-28 10:46:03.000000 musketeer-1.3.2/musketeer/editData.py
+-rw-rw-rw-   0        0        0    14568 2023-06-28 08:45:15.000000 musketeer-1.3.2/musketeer/equilibriumConstants.py
+-rw-rw-rw-   0        0        0     8433 2023-06-24 19:22:11.000000 musketeer-1.3.2/musketeer/fitSignals.py
+-rw-rw-rw-   0        0        0    10468 2023-06-28 10:47:58.000000 musketeer-1.3.2/musketeer/knownSignals.py
+-rw-rw-rw-   0        0        0     2007 2023-06-25 00:19:37.000000 musketeer-1.3.2/musketeer/logo 48px.png
+-rw-rw-rw-   0        0        0    38648 2023-06-25 00:00:13.000000 musketeer-1.3.2/musketeer/logo 512px.png
+-rw-rw-rw-   0        0        0     5452 2023-06-24 19:16:36.000000 musketeer-1.3.2/musketeer/moduleFrame.py
+-rw-rw-rw-   0        0        0     8875 2023-06-24 19:22:11.000000 musketeer-1.3.2/musketeer/patchMatplotlib.py
+-rw-rw-rw-   0        0        0     1266 2023-06-24 19:22:11.000000 musketeer-1.3.2/musketeer/proportionality.py
+-rw-rw-rw-   0        0        0    12401 2023-05-04 16:25:44.000000 musketeer-1.3.2/musketeer/scrolledFrame.py
+-rw-rw-rw-   0        0        0    22693 2023-06-28 10:47:43.000000 musketeer-1.3.2/musketeer/speciation.py
+-rw-rw-rw-   0        0        0      607 2023-04-19 11:14:04.000000 musketeer-1.3.2/musketeer/style.py
+-rw-rw-rw-   0        0        0    17174 2023-06-24 19:22:11.000000 musketeer-1.3.2/musketeer/table.py
+-rw-rw-rw-   0        0        0     9460 2023-06-28 10:47:51.000000 musketeer-1.3.2/musketeer/titration.py
+-rw-rw-rw-   0        0        0    48880 2023-06-28 10:47:45.000000 musketeer-1.3.2/musketeer/titrationFrame.py
+-rw-rw-rw-   0        0        0     8961 2023-06-25 22:45:55.000000 musketeer-1.3.2/musketeer/titrationReader.py
+-rw-rw-rw-   0        0        0    17310 2023-06-25 22:00:29.000000 musketeer-1.3.2/musketeer/totalConcentrations.py
+-rw-rw-rw-   0        0        0     2903 2023-03-09 17:30:25.000000 musketeer-1.3.2/musketeer/windowsHighDpiPatch.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:52:24.734989 musketeer-1.3.2/musketeer.egg-info/
+-rw-rw-rw-   0        0        0     4345 2023-06-28 10:52:19.000000 musketeer-1.3.2/musketeer.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      978 2023-06-28 10:52:20.000000 musketeer-1.3.2/musketeer.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:52:19.000000 musketeer-1.3.2/musketeer.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       84 2023-06-28 10:52:19.000000 musketeer-1.3.2/musketeer.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       10 2023-06-28 10:52:19.000000 musketeer-1.3.2/musketeer.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 10:52:24.786258 musketeer-1.3.2/setup.cfg
+-rw-rw-rw-   0        0        0     1836 2023-04-19 11:14:04.000000 musketeer-1.3.2/setup.py
```

### Comparing `musketeer-1.3.1/LICENSE` & `musketeer-1.3.2/LICENSE`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/cx_freeze/logo 48px.ico` & `musketeer-1.3.2/cx_freeze/logo 48px.ico`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/cx_freeze/logo 512px.png` & `musketeer-1.3.2/cx_freeze/logo 512px.png`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/cx_freeze/setup.py` & `musketeer-1.3.2/cx_freeze/setup.py`

 * *Files 7% similar despite different names*

```diff
@@ -1,32 +1,37 @@
 import sys
 
+import musketeer
 from cx_Freeze import Executable, setup
 
 build_options = {
     "packages": [],
     "excludes": [],
     "include_files": [] if sys.platform == "win32" else ["logo 512px.png"],
 }
-msi_options = {"install_icon": "logo 48px.ico"}
+msi_options = {
+    "install_icon": "logo 48px.ico",
+    "upgrade_code": "{C327C15B-6058-313C-AADF-E979233602A5}",
+    "summary_data": {"author": "Daniil Soloviev"},
+}
 
 
 base = "Win32GUI" if sys.platform == "win32" else None
 
 executables = [
     Executable(
-        "Musketeer_test.py",
+        "musketeer_loader.py",
         base=base,
         target_name="Musketeer",
         shortcut_name="Musketeer",
-        shortcut_dir="StartMenuFolder",
+        shortcut_dir="ProgramMenuFolder",
         icon="logo 48px.ico" if sys.platform == "win32" else "logo 512px.png",
     )
 ]
 
 setup(
     name="Musketeer",
-    version="1.3.0",
+    version=musketeer.__version__,
     description="Musketeer",
     options={"build_exe": build_options, "bdist_mis": msi_options},
     executables=executables,
 )
```

### Comparing `musketeer-1.3.1/musketeer/__main__.py` & `musketeer-1.3.2/musketeer/__main__.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/combineResiduals.py` & `musketeer-1.3.2/musketeer/combineResiduals.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/contributingSpecies.py` & `musketeer-1.3.2/musketeer/contributingSpecies.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/contributors.py` & `musketeer-1.3.2/musketeer/contributors.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/editData.py` & `musketeer-1.3.2/musketeer/editData.py`

 * *Files 2% similar despite different names*

```diff
@@ -170,14 +170,16 @@
 
     def processData(self):
         titration = self.titration
         data = np.array(self.sheet.get_sheet_data())
         data = data[~np.all(data == "", 1), :][:, ~np.all(data == "", 0)]
 
         titration.hasSignalTitles = self.signalTitlesCheckbutton.instate(["selected"])
+        if not titration.hasSignalTitles:
+            titration.continuous = False
         titration.hasAdditionTitles = self.additionTitlesCheckbutton.instate(
             ["selected"]
         )
         titration.transposeData = self.additionsColumnsRadiobutton.instate(["selected"])
 
         if titration.transposeData:
             data = data.T
```

### Comparing `musketeer-1.3.1/musketeer/equilibriumConstants.py` & `musketeer-1.3.2/musketeer/equilibriumConstants.py`

 * *Files 1% similar despite different names*

```diff
@@ -347,18 +347,14 @@
         height = int(self.master.winfo_height() * 0.4)
         frame = ScrolledFrame(
             self,
             height=height,
             max_width=self.winfo_toplevel().master.winfo_width() - 200,
         )
         frame.pack(expand=True, fill="both")
-        frame = ScrolledFrame(
-            self, height=height, max_width=self.winfo_toplevel().winfo_width() - 200
-        )
-        frame.pack(expand=True, fill="both")
 
         innerFrame = frame.display_widget(ttk.Frame, stretch=True)
         knownKsLabel = WrappedLabel(
             innerFrame,
             text=(
                 "Enter known K values, leave empty to optimise the value, or write"
                 " ~number to provide an initial guess for the optimisation.\n\nThe K"
```

### Comparing `musketeer-1.3.1/musketeer/fitSignals.py` & `musketeer-1.3.2/musketeer/fitSignals.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/knownSignals.py` & `musketeer-1.3.2/musketeer/knownSignals.py`

 * *Files 1% similar despite different names*

```diff
@@ -48,16 +48,14 @@
 
         loadButton = ttk.Button(buttonFrame, text="Load from CSV", command=self.loadCSV)
         loadButton.pack(side="left", padx=padding)
 
         self.sheet.pack(side="top", expand=True, fill="both")
 
     def reset(self):
-        breakpoint()
-        return
         self.sheet.set_sheet_data(
             self.formatData(self.titration.knownSignals.knownSpectra)
         )
 
     def saveData(self):
         data = np.array(self.sheet.get_sheet_data(), dtype=object)
         data[data == ""] = "nan"
```

### Comparing `musketeer-1.3.1/musketeer/logo 48px.png` & `musketeer-1.3.2/musketeer/logo 48px.png`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/logo 512px.png` & `musketeer-1.3.2/musketeer/logo 512px.png`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/moduleFrame.py` & `musketeer-1.3.2/musketeer/moduleFrame.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/patchMatplotlib.py` & `musketeer-1.3.2/musketeer/patchMatplotlib.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/proportionality.py` & `musketeer-1.3.2/musketeer/proportionality.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/scrolledFrame.py` & `musketeer-1.3.2/musketeer/scrolledFrame.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/speciation.py` & `musketeer-1.3.2/musketeer/speciation.py`

 * *Files 1% similar despite different names*

```diff
@@ -551,17 +551,14 @@
             if any(lb > ub):
                 # Correct for rounding errors. Unsure if this is necessary, as the only
                 # obvious case when it should happen is if no complexes are formed,
                 # which should be caught above.
                 mask = np.logical_and(lb > ub, np.isclose(lb, ub))
                 lb[mask], ub[mask] = ub[mask], lb[mask]
 
-            if any(lb > ub):
-                breakpoint()
-
             if i == 0:
                 # Initial guess: all species 100% free
                 x0 = ub
             else:
                 # If the total concentration increased, the initial guess is that all
                 # the added molecules are free.
                 # If the total concentration decreased, the initial guess is that the
```

### Comparing `musketeer-1.3.1/musketeer/style.py` & `musketeer-1.3.2/musketeer/style.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/table.py` & `musketeer-1.3.2/musketeer/table.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/titration.py` & `musketeer-1.3.2/musketeer/titration.py`

 * *Files 1% similar despite different names*

```diff
@@ -80,14 +80,16 @@
                 ["Signal " + str(i + 1) for i in range(self.rawData.shape[1])]
             )
 
     @signalTitles.setter
     def signalTitles(self, titles):
         # TODO: replace flag with just setting titles to None
         if titles.size == 0:
+            self.hasSignalTitles = False
+            self.continuous = False
             return
         self.hasSignalTitles = True
         try:
             _signalTitles = np.array(titles, dtype=float)
         except ValueError:
             self._signalTitles = np.array(titles, dtype=str)
             self.continuous = False
```

### Comparing `musketeer-1.3.1/musketeer/titrationFrame.py` & `musketeer-1.3.2/musketeer/titrationFrame.py`

 * *Files 1% similar despite different names*

```diff
@@ -242,16 +242,20 @@
         self.columnconfigure(1, weight=1)
 
     def editData(self):
         root = self.winfo_toplevel()
         popup = editData.EditDataPopup(self.currentTab.titration, master=root)
         popup.geometry(f"+{root.winfo_x()+100}+{root.winfo_y()+100}")
         popup.show()
-        if hasattr(self.currentTab, "inputSpectraFrame"):
-            self.currentTab.inputSpectraFrame.plot()
+        self.currentTab.inputSpectraFrame.updateData()
+        if (
+            len(self.currentTab.tabs()) == 1
+            and self.currentTab.inputSpectraFrame.loaded
+        ):
+            self.currentTab.select(self.currentTab.inputSpectraFrame)
 
     def updateDpi(self):
         for tab in self.notebook.tabs():
             if isinstance(fitNotebook := self.nametowidget(tab), FitNotebook):
                 fitNotebook.updateDpi()
 
     @property
@@ -387,22 +391,24 @@
 
 
 class FitNotebook(ttk.Notebook):
     def __init__(self, master, titration, *args, **kwargs):
         super().__init__(master, padding=padding, style="Flat.TNotebook")
         self.titration = titration
 
-    def add(self, *args, **kwargs):
-        super().add(*args, **kwargs)
+    def add(self, tab, *args, hidden=False, **kwargs):
+        super().add(tab, *args, **kwargs)
+        if hidden:
+            self.hide(tab)
         self.update()
 
     def loadTabs(self):
-        if self.titration.continuous:
-            self.inputSpectraFrame = InputSpectraFrame(self, self.titration)
-            self.add(self.inputSpectraFrame, text="Input Spectra")
+        self.inputSpectraFrame = InputSpectraFrame(self, self.titration)
+        self.add(self.inputSpectraFrame, text="Input Spectra", hidden=True)
+        self.inputSpectraFrame.updateData()
 
         if hasattr(self.titration, "fitResult"):
             try:
                 self.showFit()
             except Exception as e:
                 print("Warning: failed to load previous fit result:", e)
 
@@ -558,44 +564,42 @@
         self.draw_idle()
 
 
 class InputSpectraFrame(PlotFrame):
     def __init__(self, parent, titration, *args, **kwargs):
         super().__init__(parent, *args, **kwargs)
         self.titration = titration
+        self.populate()
 
-        rangeSelection = ttk.Frame(self)
-        rangeSelection.grid(row=0, column=1, sticky="s")
+        self.loaded = False
 
-        ttk.Label(rangeSelection, text=f"Range of {titration.xQuantity} to fit:").pack(
-            side="left"
-        )
-
-        signalMin = self.titration.signalTitles.min()
-        signalMax = self.titration.signalTitles.max()
+    def updateData(self):
+        if self.titration.continuous:
+            if not self.loaded:
+                self.master.add(self, text="Input Spectra")
+                self.loaded = True
+            self.updateRangeSelection()
+            self.plot()
+        else:
+            self.loaded = False
+            self.master.hide(self)
 
-        currentMin, currentMax = self.titration.continuousRange
-        currentMin = max(currentMin, signalMin)
-        currentMax = min(currentMax, signalMax)
+    def populate(self):
+        rangeSelection = ttk.Frame(self)
+        rangeSelection.grid(row=0, column=1, sticky="s")
 
-        decimals = self.titration.signalTitlesDecimals
-        step = 1 / (10**decimals)
+        self.rangeLabel = ttk.Label(rangeSelection)
+        self.rangeLabel.pack(side="left")
 
-        self.fromSpinbox = ttk.Spinbox(
-            rangeSelection, from_=signalMin, to=signalMax, width=5, increment=step
-        )
-        self.fromSpinbox.set(f"{currentMin:.{decimals}f}")
+        self.fromSpinbox = ttk.Spinbox(rangeSelection, width=5)
         self.fromSpinbox.pack(padx=padding, side="left")
 
         ttk.Label(rangeSelection, text="to").pack(side="left")
 
-        self.toSpinbox = ttk.Spinbox(
-            rangeSelection, from_=signalMin, to=signalMax, width=5, increment=step
-        )
-        self.toSpinbox.set(f"{currentMax:.{decimals}f}")
+        self.toSpinbox = ttk.Spinbox(rangeSelection, width=5)
         self.toSpinbox.pack(padx=padding, side="left")
 
         self.fig = Figure(
             layout="constrained", figsize=(self.figwidth, self.figheight), dpi=self.dpi
         )
         self.ax = self.fig.add_subplot()
 
@@ -625,15 +629,31 @@
             uniform="row",
             minsize=max(w.winfo_reqheight() for w in rangeSelection.children.values()),
         )
         self.rowconfigure(1, weight=1)
         self.rowconfigure(2, weight=1000, uniform="row")
         self.grid_anchor("center")
 
-        self.plot()
+    def updateRangeSelection(self):
+        self.rangeLabel.configure(text=f"Range of {self.titration.xQuantity} to fit:")
+
+        signalMin = self.titration.signalTitles.min()
+        signalMax = self.titration.signalTitles.max()
+
+        currentMin, currentMax = self.titration.continuousRange
+        currentMin = max(currentMin, signalMin)
+        currentMax = min(currentMax, signalMax)
+
+        decimals = self.titration.signalTitlesDecimals
+        step = 1 / (10**decimals)
+
+        self.fromSpinbox.configure(from_=signalMin, to=signalMax, increment=step)
+        self.fromSpinbox.set(f"{currentMin:.{decimals}f}")
+        self.toSpinbox.configure(from_=signalMin, to=signalMax, increment=step)
+        self.toSpinbox.set(f"{currentMax:.{decimals}f}")
 
     def plot(self):
         ax = self.ax
         fig = self.fig
         titration = self.titration
 
         ax.cla()
```

### Comparing `musketeer-1.3.1/musketeer/titrationReader.py` & `musketeer-1.3.2/musketeer/titrationReader.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/totalConcentrations.py` & `musketeer-1.3.2/musketeer/totalConcentrations.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer/windowsHighDpiPatch.py` & `musketeer-1.3.2/musketeer/windowsHighDpiPatch.py`

 * *Files identical despite different names*

### Comparing `musketeer-1.3.1/musketeer.egg-info/SOURCES.txt` & `musketeer-1.3.2/musketeer.egg-info/SOURCES.txt`

 * *Files 8% similar despite different names*

```diff
@@ -2,15 +2,18 @@
 .gitignore
 LICENSE
 MANIFEST.in
 README.md
 setup.py
 cx_freeze/logo 48px.ico
 cx_freeze/logo 512px.png
+cx_freeze/musketeer_loader.py
 cx_freeze/setup.py
+examples/NMR_example.fit
+examples/UV-Vis_example.fit
 musketeer/__init__.py
 musketeer/__main__.py
 musketeer/combineResiduals.py
 musketeer/contributingSpecies.py
 musketeer/contributors.py
 musketeer/editData.py
 musketeer/equilibriumConstants.py
```

### Comparing `musketeer-1.3.1/setup.py` & `musketeer-1.3.2/setup.py`

 * *Files identical despite different names*


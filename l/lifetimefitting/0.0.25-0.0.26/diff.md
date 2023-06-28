# Comparing `tmp/lifetimefitting-0.0.25.tar.gz` & `tmp/lifetimefitting-0.0.26.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "lifetimefitting-0.0.25.tar", last modified: Tue Jun  6 23:42:51 2023, max compression
+gzip compressed data, was "lifetimefitting-0.0.26.tar", last modified: Wed Jun 28 03:12:43 2023, max compression
```

## Comparing `lifetimefitting-0.0.25.tar` & `lifetimefitting-0.0.26.tar`

### file list

```diff
@@ -1,21 +1,21 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 23:42:51.761957 lifetimefitting-0.0.25/
--rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-06-06 23:42:39.000000 lifetimefitting-0.0.25/LICENSE.md
--rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-06 23:42:51.761957 lifetimefitting-0.0.25/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     2171 2023-06-06 23:42:39.000000 lifetimefitting-0.0.25/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 23:42:51.757957 lifetimefitting-0.0.25/app/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 23:42:51.757957 lifetimefitting-0.0.25/app/lifetimefitting/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-06 23:42:39.000000 lifetimefitting-0.0.25/app/lifetimefitting/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     3333 2023-06-06 23:42:39.000000 lifetimefitting-0.0.25/app/lifetimefitting/__main__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 23:42:51.761957 lifetimefitting-0.0.25/app/lifetimefitting/funcs/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-06 23:42:39.000000 lifetimefitting-0.0.25/app/lifetimefitting/funcs/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     2680 2023-06-06 23:42:39.000000 lifetimefitting-0.0.25/app/lifetimefitting/funcs/expFuncs.py
--rw-r--r--   0 runner    (1001) docker     (123)     6951 2023-06-06 23:42:39.000000 lifetimefitting-0.0.25/app/lifetimefitting/funcs/fittingFuncs.py
--rw-r--r--   0 runner    (1001) docker     (123)    12735 2023-06-06 23:42:39.000000 lifetimefitting-0.0.25/app/lifetimefitting/funcs/gui.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-06 23:42:51.761957 lifetimefitting-0.0.25/app/lifetimefitting.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-06 23:42:51.000000 lifetimefitting-0.0.25/app/lifetimefitting.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-06 23:42:51.000000 lifetimefitting-0.0.25/app/lifetimefitting.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-06 23:42:51.000000 lifetimefitting-0.0.25/app/lifetimefitting.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       61 2023-06-06 23:42:51.000000 lifetimefitting-0.0.25/app/lifetimefitting.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-06 23:42:51.000000 lifetimefitting-0.0.25/app/lifetimefitting.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-06 23:42:51.761957 lifetimefitting-0.0.25/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      883 2023-06-06 23:42:39.000000 lifetimefitting-0.0.25/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:12:43.292704 lifetimefitting-0.0.26/
+-rw-r--r--   0 runner    (1001) docker     (123)     1062 2023-06-28 03:12:31.000000 lifetimefitting-0.0.26/LICENSE.md
+-rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-28 03:12:43.292704 lifetimefitting-0.0.26/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     2171 2023-06-28 03:12:31.000000 lifetimefitting-0.0.26/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:12:43.288704 lifetimefitting-0.0.26/app/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:12:43.288704 lifetimefitting-0.0.26/app/lifetimefitting/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 03:12:31.000000 lifetimefitting-0.0.26/app/lifetimefitting/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3713 2023-06-28 03:12:31.000000 lifetimefitting-0.0.26/app/lifetimefitting/__main__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:12:43.292704 lifetimefitting-0.0.26/app/lifetimefitting/funcs/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 03:12:31.000000 lifetimefitting-0.0.26/app/lifetimefitting/funcs/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2680 2023-06-28 03:12:31.000000 lifetimefitting-0.0.26/app/lifetimefitting/funcs/expFuncs.py
+-rw-r--r--   0 runner    (1001) docker     (123)     7173 2023-06-28 03:12:31.000000 lifetimefitting-0.0.26/app/lifetimefitting/funcs/fittingFuncs.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12735 2023-06-28 03:12:31.000000 lifetimefitting-0.0.26/app/lifetimefitting/funcs/gui.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 03:12:43.292704 lifetimefitting-0.0.26/app/lifetimefitting.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2646 2023-06-28 03:12:43.000000 lifetimefitting-0.0.26/app/lifetimefitting.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      458 2023-06-28 03:12:43.000000 lifetimefitting-0.0.26/app/lifetimefitting.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 03:12:43.000000 lifetimefitting-0.0.26/app/lifetimefitting.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       68 2023-06-28 03:12:43.000000 lifetimefitting-0.0.26/app/lifetimefitting.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       16 2023-06-28 03:12:43.000000 lifetimefitting-0.0.26/app/lifetimefitting.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 03:12:43.292704 lifetimefitting-0.0.26/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      890 2023-06-28 03:12:31.000000 lifetimefitting-0.0.26/setup.py
```

### Comparing `lifetimefitting-0.0.25/LICENSE.md` & `lifetimefitting-0.0.26/LICENSE.md`

 * *Files identical despite different names*

### Comparing `lifetimefitting-0.0.25/PKG-INFO` & `lifetimefitting-0.0.26/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: lifetimefitting
-Version: 0.0.25
+Version: 0.0.26
 Summary: PicoHarp TCSPC lifetime fitting tool
 Home-page: https://github.com/adreasnow/LifetimeFittingTool
 Author: Adrea Snow
 Author-email: adrea.snow@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `lifetimefitting-0.0.25/README.md` & `lifetimefitting-0.0.26/README.md`

 * *Files identical despite different names*

### Comparing `lifetimefitting-0.0.25/app/lifetimefitting/__main__.py` & `lifetimefitting-0.0.26/app/lifetimefitting/__main__.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,17 +1,23 @@
 import matplotlib.pyplot as plt
-from PyQt6 import QtWidgets
-from PyQt6.QtWidgets import QFileDialog
+from PyQt6 import QtWidgets, uic
+from PyQt6.QtWidgets import QFileDialog, QMainWindow, QApplication
 from matplotlib.backends.backend_qt5agg import FigureCanvasQTAgg as FigureCanvas
 from matplotlib.backends.backend_qt5agg import NavigationToolbar2QT as NavigationToolbar
 from phdimporter import TRF
-from .funcs.gui import Ui_Form
+from pathlib import Path
 from .funcs.fittingFuncs import loadAndCull, fitFL
 import sys
 
+class Ui(QMainWindow):
+    def __init__(self) -> None:
+        super(Ui, self).__init__()
+        uic.loadUi(f'{Path(__file__).parent.resolve()}/../lifetimeGui.ui', self)
+        self.show()
+
 def plotFL() -> None:
     global csv
     plt.close('all')
     for i in ui.axList:
         i.remove()
     ui.axList = []
     ui.ax1.relim()
@@ -24,18 +30,30 @@
     ui.ax4.autoscale_view()
     _, irf, loaded1 = loadAndCull(ui.irf_file, ui)
     x, y, loaded2 = loadAndCull(ui.trf_file, ui)
     if loaded1 and loaded2:
         csv = fitFL(ui, x_in=x, y_in=y, irf_in=irf)
 
 def trf_browse() -> None:
-    ui.trf_file.setText(file_dialog.getOpenFileName(directory="/Users/adrea/gdrive/Monash/PhD/Fluorophore/data/tr/AAQ", filter="PicoHarp binary of text file (*.phd *.txt)")[0])
+    file_dialog = QFileDialog()
+    directory = ''
+    if ui.trf_file.text() != '':
+        path = Path(ui.trf_file.text())
+        if path.exists:
+            directory = path.parent.as_posix()
+    ui.trf_file.setText(file_dialog.getOpenFileName(directory=directory, filter="Photon Time Histrogram (*.phd *.txt *.asc)")[0])
 
 def irf_browse() -> None:
-    ui.irf_file.setText(file_dialog.getOpenFileName(directory="/Users/adrea/gdrive/Monash/PhD/Fluorophore/data/tr/AAQ", filter="PicoHarp binary of text file (*.phd *.txt)")[0])
+    file_dialog = QFileDialog()
+    directory = ''
+    if ui.trf_file.text() != '':
+        path = Path(ui.trf_file.text())
+        if path.exists:
+            directory = path.parent.as_posix()
+    ui.irf_file.setText(file_dialog.getOpenFileName(directory=directory, filter="Photon Time Histrogram (*.phd *.txt *.asc)")[0])
 
 def update_max_x() -> None:
     ui.max_x_out.setValue(ui.max_x.value())
 
 def update_max_x_from_out() -> None:
     ui.max_x.setValue(ui.max_x_out.value())
 
@@ -74,25 +92,20 @@
         save_csv_dialog = QFileDialog()
         name = save_csv_dialog.getSaveFileName(filter="CSV Sheet (*.csv)")[0]
         if name != '':
             with open(name, 'w+') as f:
                 f.writelines(csv)
 
 if __name__ == "__main__":
-    app = QtWidgets.QApplication(sys.argv)
-    Form = QtWidgets.QWidget()
-    ui = Ui_Form()
-    ui.setupUi(Form)
+    app = QApplication(sys.argv)
+    ui = Ui()
     setupPlot()
 
-    # file loading
-    file_dialog = QFileDialog()
     ui.trf_browse.clicked.connect(trf_browse)
     ui.irf_browse.clicked.connect(irf_browse)
     ui.csv_browse.clicked.connect(saveCSV)
     ui.max_x.sliderMoved.connect(update_max_x)
     ui.max_x_out.valueChanged.connect(update_max_x_from_out)
 
     ui.fit_button.clicked.connect(plotFL)
 
-    Form.show()
     sys.exit(app.exec())
```

### Comparing `lifetimefitting-0.0.25/app/lifetimefitting/funcs/expFuncs.py` & `lifetimefitting-0.0.26/app/lifetimefitting/funcs/expFuncs.py`

 * *Files identical despite different names*

### Comparing `lifetimefitting-0.0.25/app/lifetimefitting/funcs/fittingFuncs.py` & `lifetimefitting-0.0.26/app/lifetimefitting/funcs/fittingFuncs.py`

 * *Files 3% similar despite different names*

```diff
@@ -16,18 +16,20 @@
 
 def loadAndCull(fc: QLineEdit, ui: Ui_Form) -> tuple[list[float], list[int], bool]:
     loaded = False
     x = y = []
 
     if fc.text() == '':
         QMessageBox(icon=QMessageBox.Icon.Critical, text='TRF or IRF not loaded!').exec()
+    elif fc.text()[-4:] == '.asc' and ui.binSize_widg.value() == 0.0:
+        QMessageBox(icon=QMessageBox.Icon.Critical, text='BinWidth must be manually set when using .asc files').exec()
     else:
         filename = fc.text().split("/")[-1].split("\\")[-1]
         try:
-            trf = TRF(fc.text())
+            trf = TRF(fc.text(), binSize=ui.binSize_widg.value())
             y = trf.y
             x = trf.x
             ui.binSize_widg.setValue(trf.Resolution_int)
             loaded = True
         except struct.error:
             QMessageBox(icon=QMessageBox.Icon.Critical, text=f'There was a problem reading {filename}').exec()
         except UnboundLocalError:
```

### Comparing `lifetimefitting-0.0.25/app/lifetimefitting/funcs/gui.py` & `lifetimefitting-0.0.26/app/lifetimefitting/funcs/gui.py`

 * *Files identical despite different names*

### Comparing `lifetimefitting-0.0.25/app/lifetimefitting.egg-info/PKG-INFO` & `lifetimefitting-0.0.26/app/lifetimefitting.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: lifetimefitting
-Version: 0.0.25
+Version: 0.0.26
 Summary: PicoHarp TCSPC lifetime fitting tool
 Home-page: https://github.com/adreasnow/LifetimeFittingTool
 Author: Adrea Snow
 Author-email: adrea.snow@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
```

### Comparing `lifetimefitting-0.0.25/setup.py` & `lifetimefitting-0.0.26/setup.py`

 * *Files 12% similar despite different names*

```diff
@@ -1,25 +1,25 @@
 from setuptools import find_packages, setup
 
 with open("README.md", "r", encoding = "utf-8") as fh:
     long_description = fh.read()
 
 setup(
     name = "lifetimefitting",
-    version = "0.0.25",
+    version = "0.0.26",
     author = "Adrea Snow",
     author_email = "adrea.snow@gmail.com",
     description = "PicoHarp TCSPC lifetime fitting tool",
     long_description = long_description,
     long_description_content_type = "text/markdown",
     url = "https://github.com/adreasnow/LifetimeFittingTool",
     classifiers = [
         "Programming Language :: Python :: 3",
         "License :: OSI Approved :: MIT License",
         "Operating System :: OS Independent",
     ],
     package_dir = {"": "app"},
     packages = find_packages(where="app"),
     extras_require = {"dev": ["twine>=4.0.2"]},
-    install_requires=['matplotlib', 'numpy', 'scipy', 'pyqt6', 'phdimporter'],
+    install_requires=['matplotlib', 'numpy', 'scipy', 'pyqt6', 'phdimporter>=0.0.3'],
     python_requires = ">=3.8",
 )
```


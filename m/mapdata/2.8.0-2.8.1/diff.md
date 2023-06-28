# Comparing `tmp/mapdata-2.8.0.tar.gz` & `tmp/mapdata-2.8.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mapdata-2.8.0.tar", last modified: Wed Jun 28 01:49:17 2023, max compression
+gzip compressed data, was "mapdata-2.8.1.tar", last modified: Wed Jun 28 16:00:53 2023, max compression
```

## Comparing `mapdata-2.8.0.tar` & `mapdata-2.8.1.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-28 01:49:17.651124 mapdata-2.8.0/
--rw-------   0 dreas     (1000) dreas     (1000)      614 2023-05-10 02:52:31.000000 mapdata-2.8.0/LICENSE.txt
--rw-------   0 dreas     (1000) dreas     (1000)       88 2022-01-15 18:16:09.000000 mapdata-2.8.0/MANIFEST.in
--rw-rw-r--   0 dreas     (1000) dreas     (1000)     4155 2023-06-28 01:49:17.647124 mapdata-2.8.0/PKG-INFO
--rw-r--r--   0 dreas     (1000) dreas     (1000)     2910 2023-06-28 01:40:30.000000 mapdata-2.8.0/README.md
-drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-28 01:49:17.647124 mapdata-2.8.0/mapdata/
--rwxrwxr-x   0 dreas     (1000) dreas     (1000)   335717 2023-06-28 00:57:35.000000 mapdata-2.8.0/mapdata/mapdata.py
-drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-28 01:49:17.647124 mapdata-2.8.0/mapdata.egg-info/
--rw-rw-r--   0 dreas     (1000) dreas     (1000)     4155 2023-06-28 01:49:17.000000 mapdata-2.8.0/mapdata.egg-info/PKG-INFO
--rw-rw-r--   0 dreas     (1000) dreas     (1000)      185 2023-06-28 01:49:17.000000 mapdata-2.8.0/mapdata.egg-info/SOURCES.txt
--rw-rw-r--   0 dreas     (1000) dreas     (1000)        1 2023-06-28 01:49:17.000000 mapdata-2.8.0/mapdata.egg-info/dependency_links.txt
--rw-rw-r--   0 dreas     (1000) dreas     (1000)        1 2023-06-28 01:49:17.000000 mapdata-2.8.0/mapdata.egg-info/top_level.txt
--rw-rw-r--   0 dreas     (1000) dreas     (1000)       38 2023-06-28 01:49:17.651124 mapdata-2.8.0/setup.cfg
--rw-rw-r--   0 dreas     (1000) dreas     (1000)     1366 2023-06-28 01:00:55.000000 mapdata-2.8.0/setup.py
+drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-28 16:00:53.520729 mapdata-2.8.1/
+-rw-------   0 dreas     (1000) dreas     (1000)      614 2023-05-10 02:52:31.000000 mapdata-2.8.1/LICENSE.txt
+-rw-------   0 dreas     (1000) dreas     (1000)       88 2022-01-15 18:16:09.000000 mapdata-2.8.1/MANIFEST.in
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)     4115 2023-06-28 16:00:53.520729 mapdata-2.8.1/PKG-INFO
+-rw-r--r--   0 dreas     (1000) dreas     (1000)     2870 2023-06-28 13:59:57.000000 mapdata-2.8.1/README.md
+drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-28 16:00:53.520729 mapdata-2.8.1/mapdata/
+-rwxrwxr-x   0 dreas     (1000) dreas     (1000)   335743 2023-06-28 13:41:11.000000 mapdata-2.8.1/mapdata/mapdata.py
+drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-28 16:00:53.520729 mapdata-2.8.1/mapdata.egg-info/
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)     4115 2023-06-28 16:00:53.000000 mapdata-2.8.1/mapdata.egg-info/PKG-INFO
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)      185 2023-06-28 16:00:53.000000 mapdata-2.8.1/mapdata.egg-info/SOURCES.txt
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)        1 2023-06-28 16:00:53.000000 mapdata-2.8.1/mapdata.egg-info/dependency_links.txt
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)        1 2023-06-28 16:00:53.000000 mapdata-2.8.1/mapdata.egg-info/top_level.txt
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)       38 2023-06-28 16:00:53.520729 mapdata-2.8.1/setup.cfg
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)     1366 2023-06-28 15:56:27.000000 mapdata-2.8.1/setup.py
```

### Comparing `mapdata-2.8.0/LICENSE.txt` & `mapdata-2.8.1/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `mapdata-2.8.0/PKG-INFO` & `mapdata-2.8.1/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mapdata
-Version: 2.8.0
+Version: 2.8.1
 Summary: An interactive map and table explorer for geographic coordinates in a spreadsheet, CSV file, or database
 Home-page: https://osdn.net/project/mapdata/
 Author: Dreas Nielsen
 Author-email: dreas.nielsen@gmail.com
 License: GPL
 Keywords: Map,Locations,CRS,CSV,Spreadsheet,Database,PNG,JPG,Postscript
 Platform: UNKNOWN
@@ -68,15 +68,15 @@
 
 Data can also be displayed in several different types of plots: box plots, scatter
 plots, line charts, and counts of categorical and quantitative variables.  Plots
 can use either all data or only data values that are selected in the map and
 table.  Plots have a live connection to the data table, so when selections are
 changed the plots are automatically updated.
 
-<img src="https://mapdata.osdn.io/_images/UI_brownfields_plot.png" alt="Plot illustration", width="300"/>
+![example plot](https://mapdata.osdn.io/_images/Histogram_sm.png)
 
 SQL commands can be used when pulling a data set from a database, to create
 a temporary table, for example, instead of using a base table.  The SQL
 commands can be augmented with [execsql](https://pypi.org/project/execsql/)
 metacommands and substitution variables.
```

### Comparing `mapdata-2.8.0/README.md` & `mapdata-2.8.1/README.md`

 * *Files 6% similar despite different names*

```diff
@@ -34,15 +34,15 @@
 
 Data can also be displayed in several different types of plots: box plots, scatter
 plots, line charts, and counts of categorical and quantitative variables.  Plots
 can use either all data or only data values that are selected in the map and
 table.  Plots have a live connection to the data table, so when selections are
 changed the plots are automatically updated.
 
-<img src="https://mapdata.osdn.io/_images/UI_brownfields_plot.png" alt="Plot illustration", width="300"/>
+![example plot](https://mapdata.osdn.io/_images/Histogram_sm.png)
 
 SQL commands can be used when pulling a data set from a database, to create
 a temporary table, for example, instead of using a base table.  The SQL
 commands can be augmented with [execsql](https://pypi.org/project/execsql/)
 metacommands and substitution variables.
```

### Comparing `mapdata-2.8.0/mapdata/mapdata.py` & `mapdata-2.8.1/mapdata/mapdata.py`

 * *Files 0% similar despite different names*

```diff
@@ -20,16 +20,16 @@
 # 	The GNU General Public License is available at <http://www.gnu.org/licenses/>
 #
 # AUTHOR
 #	Dreas Nielsen (RDN)
 #
 # ==================================================================
 
-version = "2.8.0"
-vdate = "2023-06-27"
+version = "2.8.1"
+vdate = "2023-06-28"
 
 copyright = "2023"
 
 
 import sys
 import os.path
 import io
@@ -3105,15 +3105,18 @@
 		num_bins = dlg.show()
 		if num_bins is not None:
 			self.bins = num_bins
 			if self.type_var.get() == "Histogram":
 				self.q_redraw()
 	def do_close(self, *args):
 		self.parent.remove_plot(self)
-		self.dlg.destroy()
+		try:
+			self.dlg.destroy()
+		except:
+			pass
 	def show(self):
 		self.dlg.update_idle_tasks()
 		self.dlg.minsize(width=500, height=500)
 		self.dlg.wait_window(self.dlg)
```

### Comparing `mapdata-2.8.0/mapdata.egg-info/PKG-INFO` & `mapdata-2.8.1/mapdata.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: mapdata
-Version: 2.8.0
+Version: 2.8.1
 Summary: An interactive map and table explorer for geographic coordinates in a spreadsheet, CSV file, or database
 Home-page: https://osdn.net/project/mapdata/
 Author: Dreas Nielsen
 Author-email: dreas.nielsen@gmail.com
 License: GPL
 Keywords: Map,Locations,CRS,CSV,Spreadsheet,Database,PNG,JPG,Postscript
 Platform: UNKNOWN
@@ -68,15 +68,15 @@
 
 Data can also be displayed in several different types of plots: box plots, scatter
 plots, line charts, and counts of categorical and quantitative variables.  Plots
 can use either all data or only data values that are selected in the map and
 table.  Plots have a live connection to the data table, so when selections are
 changed the plots are automatically updated.
 
-<img src="https://mapdata.osdn.io/_images/UI_brownfields_plot.png" alt="Plot illustration", width="300"/>
+![example plot](https://mapdata.osdn.io/_images/Histogram_sm.png)
 
 SQL commands can be used when pulling a data set from a database, to create
 a temporary table, for example, instead of using a base table.  The SQL
 commands can be augmented with [execsql](https://pypi.org/project/execsql/)
 metacommands and substitution variables.
```

### Comparing `mapdata-2.8.0/setup.py` & `mapdata-2.8.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 import io
 
 with io.open('README.md', encoding='utf-8') as f:
 	long_description = f.read()
 
 setuptools.setup(name='mapdata',
-	version='2.8.0',
+	version='2.8.1',
 	description="An interactive map and table explorer for geographic coordinates in a spreadsheet, CSV file, or database",
 	author='Dreas Nielsen',
 	author_email='dreas.nielsen@gmail.com',
     url='https://osdn.net/project/mapdata/',
 	scripts=['mapdata/mapdata.py'],
     license='GPL',
 	requires=['tkintermapview', 'pyproj', 'odfpy', 'openpyxl', 'xlrd', 'matplotlib'],
```


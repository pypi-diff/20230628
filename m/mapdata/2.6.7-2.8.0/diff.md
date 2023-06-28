# Comparing `tmp/mapdata-2.6.7.tar.gz` & `tmp/mapdata-2.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mapdata-2.6.7.tar", last modified: Mon Jun 26 15:22:42 2023, max compression
+gzip compressed data, was "mapdata-2.8.0.tar", last modified: Wed Jun 28 01:49:17 2023, max compression
```

## Comparing `mapdata-2.6.7.tar` & `mapdata-2.8.0.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-26 15:22:42.653816 mapdata-2.6.7/
--rw-------   0 dreas     (1000) dreas     (1000)      614 2023-05-10 02:52:31.000000 mapdata-2.6.7/LICENSE.txt
--rw-------   0 dreas     (1000) dreas     (1000)       88 2022-01-15 18:16:09.000000 mapdata-2.6.7/MANIFEST.in
--rw-rw-r--   0 dreas     (1000) dreas     (1000)     4027 2023-06-26 15:22:42.653816 mapdata-2.6.7/PKG-INFO
--rw-r--r--   0 dreas     (1000) dreas     (1000)     2803 2023-06-26 15:16:31.000000 mapdata-2.6.7/README.md
-drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-26 15:22:42.649816 mapdata-2.6.7/mapdata/
--rwxrwxr-x   0 dreas     (1000) dreas     (1000)   331501 2023-06-26 15:06:23.000000 mapdata-2.6.7/mapdata/mapdata.py
-drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-26 15:22:42.653816 mapdata-2.6.7/mapdata.egg-info/
--rw-rw-r--   0 dreas     (1000) dreas     (1000)     4027 2023-06-26 15:22:42.000000 mapdata-2.6.7/mapdata.egg-info/PKG-INFO
--rw-rw-r--   0 dreas     (1000) dreas     (1000)      185 2023-06-26 15:22:42.000000 mapdata-2.6.7/mapdata.egg-info/SOURCES.txt
--rw-rw-r--   0 dreas     (1000) dreas     (1000)        1 2023-06-26 15:22:42.000000 mapdata-2.6.7/mapdata.egg-info/dependency_links.txt
--rw-rw-r--   0 dreas     (1000) dreas     (1000)        1 2023-06-26 15:22:42.000000 mapdata-2.6.7/mapdata.egg-info/top_level.txt
--rw-rw-r--   0 dreas     (1000) dreas     (1000)       38 2023-06-26 15:22:42.653816 mapdata-2.6.7/setup.cfg
--rw-rw-r--   0 dreas     (1000) dreas     (1000)     1339 2023-06-26 15:06:56.000000 mapdata-2.6.7/setup.py
+drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-28 01:49:17.651124 mapdata-2.8.0/
+-rw-------   0 dreas     (1000) dreas     (1000)      614 2023-05-10 02:52:31.000000 mapdata-2.8.0/LICENSE.txt
+-rw-------   0 dreas     (1000) dreas     (1000)       88 2022-01-15 18:16:09.000000 mapdata-2.8.0/MANIFEST.in
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)     4155 2023-06-28 01:49:17.647124 mapdata-2.8.0/PKG-INFO
+-rw-r--r--   0 dreas     (1000) dreas     (1000)     2910 2023-06-28 01:40:30.000000 mapdata-2.8.0/README.md
+drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-28 01:49:17.647124 mapdata-2.8.0/mapdata/
+-rwxrwxr-x   0 dreas     (1000) dreas     (1000)   335717 2023-06-28 00:57:35.000000 mapdata-2.8.0/mapdata/mapdata.py
+drwxrwxr-x   0 dreas     (1000) dreas     (1000)        0 2023-06-28 01:49:17.647124 mapdata-2.8.0/mapdata.egg-info/
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)     4155 2023-06-28 01:49:17.000000 mapdata-2.8.0/mapdata.egg-info/PKG-INFO
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)      185 2023-06-28 01:49:17.000000 mapdata-2.8.0/mapdata.egg-info/SOURCES.txt
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)        1 2023-06-28 01:49:17.000000 mapdata-2.8.0/mapdata.egg-info/dependency_links.txt
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)        1 2023-06-28 01:49:17.000000 mapdata-2.8.0/mapdata.egg-info/top_level.txt
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)       38 2023-06-28 01:49:17.651124 mapdata-2.8.0/setup.cfg
+-rw-rw-r--   0 dreas     (1000) dreas     (1000)     1366 2023-06-28 01:00:55.000000 mapdata-2.8.0/setup.py
```

### Comparing `mapdata-2.6.7/LICENSE.txt` & `mapdata-2.8.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `mapdata-2.6.7/PKG-INFO` & `mapdata-2.8.0/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: mapdata
-Version: 2.6.7
+Version: 2.8.0
 Summary: An interactive map and table explorer for geographic coordinates in a spreadsheet, CSV file, or database
 Home-page: https://osdn.net/project/mapdata/
 Author: Dreas Nielsen
 Author-email: dreas.nielsen@gmail.com
 License: GPL
-Keywords: Map,Locations,CRS,CSV,PNG,JPG,Postscript
+Keywords: Map,Locations,CRS,CSV,Spreadsheet,Database,PNG,JPG,Postscript
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Environment :: X11 Applications
 Classifier: Environment :: Win32 (MS Windows)
 Classifier: Intended Audience :: End Users/Desktop
 Classifier: Intended Audience :: Information Technology
@@ -68,14 +68,16 @@
 
 Data can also be displayed in several different types of plots: box plots, scatter
 plots, line charts, and counts of categorical and quantitative variables.  Plots
 can use either all data or only data values that are selected in the map and
 table.  Plots have a live connection to the data table, so when selections are
 changed the plots are automatically updated.
 
+<img src="https://mapdata.osdn.io/_images/UI_brownfields_plot.png" alt="Plot illustration", width="300"/>
+
 SQL commands can be used when pulling a data set from a database, to create
 a temporary table, for example, instead of using a base table.  The SQL
 commands can be augmented with [execsql](https://pypi.org/project/execsql/)
 metacommands and substitution variables.
 
 
 Complete documentation is at [https://mapdata.osdn.io](https://mapdata.osdn.io).
```

### Comparing `mapdata-2.6.7/README.md` & `mapdata-2.8.0/README.md`

 * *Files 12% similar despite different names*

```diff
@@ -34,14 +34,16 @@
 
 Data can also be displayed in several different types of plots: box plots, scatter
 plots, line charts, and counts of categorical and quantitative variables.  Plots
 can use either all data or only data values that are selected in the map and
 table.  Plots have a live connection to the data table, so when selections are
 changed the plots are automatically updated.
 
+<img src="https://mapdata.osdn.io/_images/UI_brownfields_plot.png" alt="Plot illustration", width="300"/>
+
 SQL commands can be used when pulling a data set from a database, to create
 a temporary table, for example, instead of using a base table.  The SQL
 commands can be augmented with [execsql](https://pypi.org/project/execsql/)
 metacommands and substitution variables.
 
 
 Complete documentation is at [https://mapdata.osdn.io](https://mapdata.osdn.io).
```

### Comparing `mapdata-2.6.7/mapdata/mapdata.py` & `mapdata-2.8.0/mapdata/mapdata.py`

 * *Files 1% similar despite different names*

```diff
@@ -20,16 +20,16 @@
 # 	The GNU General Public License is available at <http://www.gnu.org/licenses/>
 #
 # AUTHOR
 #	Dreas Nielsen (RDN)
 #
 # ==================================================================
 
-version = "2.6.7"
-vdate = "2023-06-26"
+version = "2.8.0"
+vdate = "2023-06-27"
 
 copyright = "2023"
 
 
 import sys
 import os.path
 import io
@@ -47,14 +47,15 @@
 import queue
 import sqlite3
 import tempfile
 import random
 import uuid
 import traceback
 import subprocess
+import multiprocessing
 import copy
 import tkinter as tk
 import tkinter.ttk as ttk
 import tkinter.font as tkfont
 import tkinter.filedialog as tkfiledialog
 import tkintermapview as tkmv
 from PIL import ImageGrab
@@ -607,27 +608,41 @@
 	if parse_datetimetz(v):
 		return "timestamptz"
 	return None
 
 def data_type(v):
 	# Characterizes the value v as one of a simple set of data types.
 	# Returns "timestamp", "date", "timestamptz", "int", "float", "boolean", or "string"
-	if v is None or (type(v) is str and v == ''):
+	if v is None or (type(v) is str and v.strip() == ''):
 		return None
 	if isint(v):
 		return "int"
 	if isfloat(v):
 		return "float"
 	dt = dt_type(v)
 	if dt is not None:
 		return dt
 	if isboolean(v):
 		return "boolean"
 	return "string"
 
+# Lookup table for priorities among data types
+data_type_pair_priorities = {
+		"int" : {"int":"int", "float":"float", "date":"string", "timestamp":"string", "timestamptz":"string", "boolean":"string", "string":"string"},
+		"float" : {"int":"float", "float":"float", "date":"string", "timestamp":"string", "timestamptz":"string", "boolean":"string", "string":"string"},
+		"date" : {"int":"string", "float":"string", "date":"date", "timestamp":"timestamp", "timestamptz":"string", "boolean":"string", "string":"string"},
+		"timestamp" : {"int":"string", "float":"string", "date":"timestamp", "timestamp":"timestamp", "datetimetz":"string", "boolean":"string", "string":"string"},
+		"timestamptz" : {"int":"string", "float":"string", "date":"string", "timestamp":"string", "timestamptz":"timestamptz", "boolean":"string", "string":"string"},
+		"string" : {"int":"string", "float":"string", "date":"string", "timestamp":"string", "timestamptz":"string", "boolean":"string", "string":"string"},
+		"boolean" : {"int":"string", "float":"string", "date":"string", "timestamp":"string", "timestamptz":"string", "boolean":"boolean", "string":"string"}
+		}
+def priority_data_type(dt1, dt2):
+	return data_type_pair_priorities[dt1][dt2]
+
+
 def data_type_cast_fn(data_type_str):
 	if data_type_str == "string":
 		return str
 	elif data_type_str == "date":
 		return parse_date
 	elif data_type_str == "timestamp":
 		return conv_datetime
@@ -660,44 +675,55 @@
 				if 'date' in uq_types and 'timestamp' in uq_types:
 					return 'timestamp'
 				else:
 					return "string"
 		else:
 			return "string"
 
-def set_data_types(headers, rows):
+
+def set_data_types(headers, rows, q):
+	# Column-by-column processing is slightly faster than row-by-row processing.
 	coltypes = []
 	for i, colname in enumerate(headers):
 		datavals = [row[i] for row in rows]
 		non_null = [d for d in datavals if d is not None and not (type(d) is str and d.strip() == '')]
 		nullcount = len(datavals) - len(non_null)
 		uniquevals = len(set(non_null))
 		coltypes.append((colname, common_data_type(datavals), nullcount, uniquevals))
-	return coltypes
+	q.put(coltypes)
+
 
 # Translations to SQLite type affinity names
 sqlite_type_x = {'int': 'INTEGER', 'float': 'REAL', 'string': 'TEXT', 'timestamptz': 'TEXT',
 		'timestamp': 'TEXT', 'date': 'TEXT', 'boolean': 'INTEGER'}
 
-def center_window(win):
+def center_window(win, x_offset=0, y_offset=0):
 	win.update_idletasks()
 	m = re.match(r"(\d+)x(\d+)\+(-?\d+)\+(-?\d+)", win.geometry())
 	if m is not None:
 		wwd = int(m.group(1))
 		wht = int(m.group(2))
 		swd = win.winfo_screenwidth()
 		sht = win.winfo_screenheight()
-		xpos = (swd/2) - (wwd/2)
-		ypos = (sht/2) - (wht/2)
+		xpos = (swd/2) - (wwd/2) + x_offset
+		ypos = (sht/2) - (wht/2) + y_offset
 		win.geometry("%dx%d+%d+%d" % (wwd, wht, xpos, ypos))
 
 def raise_window(win):
 	win.attributes('-topmost', 1)
 	win.attributes('-topmost', 0)
 
+def shift_window(win, x_offset=0, y_offset=0):
+	win.update_idletasks()
+	m = re.match(r"(\d+)x(\d+)\+(-?\d+)\+(-?\d+)", win.geometry())
+	if m is not None:
+		xpos = int(m.group(1)) + x_offset
+		ypos = int(m.group(2)) + y_offset
+		win.geometry("+%d+%d" % (xpos, ypos))
+
 
 
 class MapUI(object):
 	def __init__(self, src_name, message, lat_col, lon_col, crs=4326, sheet=None,
 			label_col=None, symbol_col=None, color_col=None,
 			map_export_file=None, export_time_sec=10):
 		self.win = tk.Tk()
@@ -1098,15 +1124,14 @@
 					newx = None
 					newy = None
 				if len(r) < len(headers):
 					r.extend([newy, newx])
 				else:
 					r[self.lat_index] = newy
 					r[self.lon_index] = newx
-		self.data_types = []
 
 		# Populate the treeview
 		tframe, tdata = treeview_table(self.tblframe, rows, headers, "browse")
 		self.table_row_count = len(tdata.get_children())
 		# Scan the table, put points on the map, and find the map extent.
 		self.min_lat = self.max_lat = self.min_lon = self.max_lon = None
 		self.sel_map_markers = []
@@ -1140,16 +1165,19 @@
 			tbldata.append(row_vals)
 		params = ",".join(['?'] * len(colnames))
 		cur.executemany("insert into mapdata values (%s)" % params, tbldata)
 		cur.close()
 		# Initial value for user-entered WHERE clause
 		self.whereclause = ""
 
-		# Save data types for use in column selection for plotting
-		self.data_types = set_data_types(headers, rows)
+		# Determe data types for use in table statistics display and in column selection for plotting
+		self.data_types = None
+		self.data_types_queue = multiprocessing.Queue()
+		self.data_types_process = multiprocessing.Process(target=set_data_types, args=(headers, rows, self.data_types_queue))
+		self.data_types_process.start()
 
 		# Return frame and data table
 		return tframe, tdata
 	def remove_data(self):
 		while len(self.sel_map_markers) > 0:
 			self.sel_map_markers.pop().delete()
 		while len(self.loc_map_markers) > 0:
@@ -1294,14 +1322,56 @@
 			for i, index in enumerate(indices):
 				res[i].append(datarow[index])
 		return res
 	def update_plot_data(self):
 		for plot in self.plot_list:
 			if plot.sel_only_var.get() == "1" and plot.auto_update:
 				plot.q_redraw()
+	def clone_plot(self, plot_obj):
+		if self.data_types is None:
+			self.loading_dlg.display("Evaluating data types")
+			self.data_types = self.data_types_queue.get()
+			self.data_types_process.join()
+			self.data_types_process.close()
+			self.loading_dlg.hide()
+		clone = PlotDialog(self, self.data_types)
+		self.plot_list.append(clone)
+		clone.dlg.geometry(plot_obj.dlg.geometry())
+		shift_window(clone.dlg, x_offset=10, y_offset=10)
+		clone.type_var.set(plot_obj.type_var.get())
+		clone.sel_only_var.set(plot_obj.sel_only_var.get())
+		clone.autoupdate_var.set(plot_obj.autoupdate_var.get())
+		clone.x_var.set(plot_obj.x_var.get())
+		clone.y_var.set(plot_obj.y_var.get())
+		clone.xlog_var.set(plot_obj.xlog_var.get())
+		clone.ylog_var.set(plot_obj.ylog_var.get())
+		clone.x_sel["values"] = copy.copy(plot_obj.x_sel["values"])
+		clone.y_sel["values"] = copy.copy(plot_obj.y_sel["values"])
+		clone.x_sel["state"] = plot_obj.x_sel["state"]
+		clone.y_sel["state"] = plot_obj.y_sel["state"]
+		clone.xlog_ck["state"] = plot_obj.xlog_ck["state"]
+		clone.ylog_ck["state"] = plot_obj.ylog_ck["state"]
+		clone.data_btn["state"] = plot_obj.data_btn["state"]
+		clone.plot_data_btn["state"] = plot_obj.plot_data_btn["state"]
+		clone.dlg.bind("<Alt-h>", clone.do_help)
+		clone.dlg.bind("<Alt-n>", clone.clone_plot)
+		clone.dlg.bind("<Alt-c>", clone.do_close)
+		clone.dlg.bind("<Escape>", clone.do_close)
+		clone.dlg.bind("<Alt-t>", clone.set_title)
+		clone.dlg.bind("<Alt-x>", clone.set_xlabel)
+		clone.dlg.bind("<Alt-y>", clone.set_ylabel)
+		if clone.type_var.get() == "Histogram":
+			clone.dlg.bind("<Alt-b>", clone.set_bins)
+		clone.dataset = copy.copy(plot_obj.dataset)
+		clone.plot_data = copy.copy(plot_obj.plot_data)
+		clone.data_labels = copy.copy(plot_obj.data_labels)
+		clone.plot_data_labels = copy.copy(plot_obj.plot_data_labels)
+		clone.q_redraw(get_data=False)
+		raise_window(clone.dlg)
+		clone.dlg.focus()
 	def remove_plot(self, plot_obj):
 		# For use by the plot 'do_close()' method.
 		try:
 			self.plot_list.remove(plot_obj)
 		except:
 			pass
 	def close_plot(self, plot_obj):
@@ -1566,14 +1636,20 @@
 		def set_editor():
 			global editor
 			dlg = GetEditorDialog(self.win, editor)
 			new_editor = dlg.show()
 			if new_editor is not None:
 				editor = new_editor
 		def show_data_types():
+			if self.data_types is None:
+				self.loading_dlg.display("Evaluating data types")
+				self.data_types = self.data_types_queue.get()
+				self.data_types_process.join()
+				self.data_types_process.close()
+				self.loading_dlg.hide()
 			dlg = MsgDialog("Data Types", "Data types, data completeness, and number of unique non-missing values for columns of the data table:", can_resize=True)
 			tframe, tdata = treeview_table(dlg.content_frame, self.data_types, ["Column", "Type", "Missing", "Unique"], "browse")
 			tframe.grid(row=0, column=0, sticky=tk.NSEW)
 			dlg.show()
 		def run_query():
 			dlg = QueryDialog(self.headers, self.db, self.whereclause)
 			whereclause, action = dlg.get_where()
@@ -1614,14 +1690,20 @@
 			for iid in self.tbl.get_children():
 				if not iid in selected:
 					new_selections.append(iid)
 			self.tbl.selection_set(tuple(new_selections))
 			self.mark_map(None)
 			self.set_status()
 		def new_plot():
+			if self.data_types is None:
+				self.loading_dlg.display("Evaluating data types")
+				self.data_types = self.data_types_queue.get()
+				self.data_types_process.join()
+				self.data_types_process.close()
+				self.loading_dlg.hide()
 			dlg = PlotDialog(self, self.data_types)
 			self.plot_list.append(dlg)
 			dlg.show
 
 		def online_help():
 			webbrowser.open("https://mapdata.osdn.io", new=2, autoraise=True)
 		def show_config_files():
@@ -1701,31 +1783,34 @@
 			self.dlg.update()
 			self.after_id = self.dlg.after(250, self.update_lbl)
 	def display(self, message):
 		self.messages.append(message)
 		self.var_lbl.set(message)
 		self.dlg.deiconify()
 		raise_window(self.dlg)
+		self.dlg.config(cursor="watch")
 		self.dlg.update()
-		self.dlg.focus_force()
+		#self.dlg.focus_force()
 		#self.after_id = self.dlg.after(250, self.update_lbl)
 	def hide(self):
 		self.var_lbl.set("")
 		#self.dlg.after_cancel(self.after_id)
 		do_withdraw = True
+		self.dlg.config(cursor="arrow")
 		if len(self.messages) > 0:
 			self.messages.pop(-1)
 			if len(self.messages) > 0:
 				self.var_lbl.set(self.messages[0])
 				do_withdraw = False
 		if do_withdraw:
 			self.dlg.withdraw()
 	def hide_all(self):
 		self.var_lbl.set("")
 		self.messages = []
+		self.dlg.config(cursor="arrow")
 		self.dlg.withdraw()
 
 
 
 
 class LabelDialog(object):
 	def __init__(self, parent, column_list, label_col):
@@ -2637,22 +2722,22 @@
 		self.autoupdate_ck.grid(row=1, column=2, sticky=tk.W, padx=(3,3), pady=(3,3))
 
 		self.x_var = tk.StringVar(ctrl_frame, "")
 		x_lbl = ttk.Label(ctrl_frame, text="X column:")
 		x_lbl.grid(row=0, column=3, sticky=tk.E, padx=(6,3), pady=(3,3))
 		self.x_sel = ttk.Combobox(ctrl_frame, state="disabled", textvariable=self.x_var, width=20)
 		self.x_sel.grid(row=0, column=4, sticky=tk.W, padx=(3,6), pady=(3,3))
-		self.x_sel.bind("<<ComboboxSelected>>", self.q_redraw)
+		self.x_sel.bind("<<ComboboxSelected>>", self.x_changed)
 
 		self.y_var = tk.StringVar(ctrl_frame, "")
 		y_lbl = ttk.Label(ctrl_frame, text="Y column:")
 		y_lbl.grid(row=1, column=3, sticky=tk.E, padx=(6,3), pady=(3,3))
 		self.y_sel = ttk.Combobox(ctrl_frame, state="disabled", textvariable=self.y_var, width=20)
 		self.y_sel.grid(row=1, column=4, sticky=tk.W, padx=(3,6), pady=(3,3))
-		self.y_sel.bind("<<ComboboxSelected>>", self.q_redraw)
+		self.y_sel.bind("<<ComboboxSelected>>", self.y_changed)
 
 		self.xlog_var = tk.StringVar(ctrl_frame, "0")
 		self.xlog_ck = ttk.Checkbutton(ctrl_frame, text="Log X", state="disabled", command=self.q_redraw, variable=self.xlog_var,
 				onvalue="1", offvalue="0")
 		self.xlog_ck.grid(row=0, column=5, sticky=tk.W, padx=(6,6), pady=(3,3))
 
 		self.ylog_var = tk.StringVar(ctrl_frame, "0")
@@ -2678,25 +2763,29 @@
 		# Buttons
 		btn_frame = tk.Frame(self.dlg, borderwidth=3, relief=tk.RIDGE)
 		btn_frame.columnconfigure(0, weight=1)
 		btn_frame.grid(row=3, column=0, sticky=tk.EW, pady=(3,3))
 		btn_frame.columnconfigure(0, weight=0)
 		btn_frame.columnconfigure(1, weight=0)
 		btn_frame.columnconfigure(2, weight=0)
-		btn_frame.columnconfigure(3, weight=1)
+		btn_frame.columnconfigure(3, weight=0)
+		btn_frame.columnconfigure(4, weight=1)
 		self.canceled = False
 		self.help_btn = ttk.Button(btn_frame, text="Help", command=self.do_help, underline=0)
 		self.help_btn.grid(row=0, column=0, sticky=tk.W, padx=(6,3))
 		self.dlg.bind("<Alt-h>", self.do_help)
 		self.data_btn = ttk.Button(btn_frame, text="Source Data", state="disabled", command=self.show_data, underline=0)
 		self.data_btn.grid(row=0, column=1, sticky=tk.W, padx=(3,3))
 		self.plot_data_btn = ttk.Button(btn_frame, text="Plot Data", state="disabled", command=self.show_plot_data, underline=0)
-		self.plot_data_btn.grid(row=0, column=2, sticky=tk.W, padx=(3,6))
+		self.plot_data_btn.grid(row=0, column=2, sticky=tk.W, padx=(3,3))
+		self.clone_btn = ttk.Button(btn_frame, text="Clone", command=self.clone_plot, underline=3)
+		self.clone_btn.grid(row=0, column=3, sticky=tk.W, padx=(3,6))
 		close_btn = ttk.Button(btn_frame, text="Close", command=self.do_close, underline=0)
-		close_btn.grid(row=0, column=3, sticky=tk.E, padx=(6,6))
+		close_btn.grid(row=0, column=4, sticky=tk.E, padx=(6,6))
+		self.dlg.bind("<Alt-n>", self.clone_plot)
 		self.dlg.bind("<Alt-c>", self.do_close)
 		self.dlg.bind("<Escape>", self.do_close)
 		self.dlg.bind("<Alt-t>", self.set_title)
 		self.dlg.bind("<Alt-x>", self.set_xlabel)
 		self.dlg.bind("<Alt-y>", self.set_ylabel)
 		center_window(self.dlg)
 		raise_window(self.dlg)
@@ -2734,14 +2823,33 @@
 						row.append(self.plot_data[j][i])
 					except:
 						row.append(None)
 				rowwise_data.append(row)
 			tframe, tdata = treeview_table(dlg.content_frame, rowwise_data, self.plot_data_labels)
 			tframe.grid(row=0, column=0, sticky=tk.NSEW)
 			dlg.show()
+	
+	def clone_plot(self, *args):
+		self.parent.clone_plot(self)
+
+	def x_changed(self, *args):
+		plot_type = self.type_var.get()
+		if plot_type in ("Category counts", "Box plot"):
+			self.xlog_ck["state"] = "disabled"
+		else:
+			self.xlog_ck["state"] = "normal"
+		self.q_redraw(args)
+
+	def y_changed(self, *args):
+		plot_type = self.type_var.get()
+		if plot_type in ("Category counts", "Histogram", "Empirical CDF"):
+			self.ylog_ck["state"] = "disabled"
+		else:
+			self.ylog_ck["state"] = "normal"
+		self.q_redraw(args)
 
 	def set_xy(self, *args):
 		# Enable X and Y value selection, and set Combobox values based on plot type and column types.
 		self.plotfig.clear()
 		self.plot_title = None
 		self.dlg.bind("<Alt-b>")
 		self.plot_axes = self.plotfig.add_subplot(111)
@@ -2757,56 +2865,51 @@
 		# quant_columns includes date and timestamp columns
 		quant_columns = [c[0] for c in self.column_specs if c[1] not in ("string", "boolean")]
 		quant_columns.sort()
 		numeric_columns = [c[0] for c in self.column_specs if c[1] in ("int", "float")]
 		numeric_columns.sort()
 		date_columns = [c[0] for c in self.column_specs if c[1] in ("date", "timestamp", "timestamptz")]
 		date_columns.sort()
-		plot_type = self.type_var.get()
 		self.x_var.set('')
 		self.y_var.set('')
+		self.xlog_ck["state"] = "normal"
+		self.ylog_ck["state"] = "normal"
+		self.x_sel["state"] = "readonly"
+		self.y_sel["state"] = "readonly"
+		plot_type = self.type_var.get()
 		if plot_type == "Category counts":
 			self.x_sel["values"] = categ_columns
 			self.xlog_ck["state"] = "disabled"
-			self.x_sel["state"] = "readonly"
 			self.y_sel["state"] = "disabled"
 			self.ylog_ck["state"] = "disabled"
 		elif plot_type in ("Histogram", "Empirical CDF"):
 			self.x_sel["values"] = numeric_columns
-			self.xlog_ck["state"] = "normal"
-			self.x_sel["state"] = "readonly"
 			self.y_sel["state"] = "disabled"
 			self.ylog_ck["state"] = "disabled"
 			if plot_type == "Histogram":
 				self.dlg.bind("<Alt-b>", self.set_bins)
 		elif plot_type == "Box plot":
 			self.x_sel["values"] = list(set(categ_columns) | set(date_columns))
 			self.xlog_ck["state"] = "disabled"
-			self.y_sel["values"] = quant_columns
-			self.x_sel["state"] = "readonly"
-			self.y_sel["state"] = "readonly"
-			self.ylog_ck["state"] = "normal"
+			self.y_sel["values"] = numeric_columns
 		else:
 			self.x_sel["values"] = quant_columns
-			self.xlog_ck["state"] = "normal"
 			self.y_sel["values"] = quant_columns
-			self.x_sel["state"] = "readonly"
-			self.y_sel["state"] = "readonly"
-			self.ylog_ck["state"] = "normal"
 
-	def q_redraw(self, *args):
+	def q_redraw(self, get_data=True, *args):
 		# Conditionally (re)draw the plot.
 		plot_type = self.type_var.get()
 		can_redraw = (plot_type in ("Category counts", "Empirical CDF", "Histogram") and self.x_var.get() != '') \
 				or (plot_type in ("Scatter plot", "Line plot", "Box plot", "Y range plot") and self.x_var.get() != '' and self.y_var.get() != '')
 		if can_redraw:
 			self.plotfig.clear()
 			self.plot_axes = self.plotfig.add_subplot(111)
 			self.plotfig_canvas.draw()
-			self.get_data()
+			if get_data or self.dataset is None or self.plot_data is None:
+				self.get_data()
 			if self.dataset is not None:
 				self.redraw()
 
 	def get_data(self):
 		self.data_btn["state"] = "disabled"
 		self.plot_data_btn["state"] = "disabled"
 		self.dataset = None
@@ -2859,25 +2962,29 @@
 			log_error = False
 			if self.xlog_ck["state"] != "disabled" and self.xlog_var.get() == "1":
 				for i in range(len(clean_data[0])):
 					try:
 						log_data[0].append(math.log10(clean_data[0][i]))
 					except:
 						log_error = True
+						self.xlog_var.set("0")
+						self.xlog_ck["state"] = "disabled"
 						break
 				if not log_error:
 					clean_data[0] = log_data[0]
 					self.data_labels[0] = "Log10 of " + self.x_var.get()
 			if self.ylog_ck["state"] != "disabled" and self.ylog_var.get() == "1" and len(clean_data) > 1:
 				log_error = False
 				for i in range(len(clean_data[1])):
 					try:
 						log_data[1].append(math.log10(clean_data[1][i]))
 					except:
 						log_error = True
+						self.ylog_var.set("0")
+						self.ylog_ck["state"] = "disabled"
 						break
 				if not log_error:
 					clean_data[1] = log_data[1]
 					self.data_labels[1] = "Log10 of " + self.y_var.get()
 			log_data = None
 			#
 			self.dataset = clean_data
@@ -4074,21 +4181,14 @@
 				"%Y/%m/%d %H:%M:%S",
 				"%Y/%m/%d %I:%M%p",
 				"%Y/%m/%d %I:%M %p",
 				"%Y/%m/%d %I:%M:%S%p",
 				"%Y/%m/%d %I:%M:%S %p",
 				"%Y/%m/%d %X",
 				"%c",
-				"%m/%d/%y %H%M",
-				"%m/%d/%y %H:%M",
-				"%m/%d/%y %H:%M:%S",
-				"%m/%d/%y %I:%M%p",
-				"%m/%d/%y %I:%M %p",
-				"%m/%d/%y %I:%M:%S%p",
-				"%m/%d/%y %I:%M:%S %p",
 				"%b %d, %Y %X",
 				"%b %d, %Y %I:%M %p",
 				"%b %d %Y %X",
 				"%b %d %Y %I:%M %p",
 				"%d %b, %Y %X",
 				"%d %b, %Y %I:%M %p",
 				"%d %b %Y %X",
@@ -4104,52 +4204,33 @@
 				"%B %d, %Y %X",
 				"%B %d, %Y %I:%M %p",
 				"%B %d %Y %X",
 				"%B %d %Y %I:%M %p",
 				"%d %B, %Y %X",
 				"%d %B, %Y %I:%M %p",
 				"%d %B %Y %X",
-				"%d %B %Y %I:%M %p",
-				"%x",
-				"%m/%d/%Y",
-				"%m/%d/%y",
-				"%Y-%m-%d",
-				"%Y/%m/%d",
-				"%b %d, %Y",
-				"%b %d %Y",
-				"%d %b, %Y",
-				"%d %b %Y",
-				"%b. %d, %Y",
-				"%b. %d %Y",
-				"%d %b., %Y",
-				"%d %b. %Y",
-				"%B %d, %Y",
-				"%B %d %Y",
-				"%d %B, %Y",
-				"%d %B %Y"
+				"%d %B %Y %I:%M %p"
 				)
 	if type(datestr) == datetime.datetime:
 		return datestr
 	if not isinstance(datestr, str):
 		try:
-			if sys.version_info < (3,):
-				datestr = unicode(datestr)
-			else:
-				datestr = str(datestr)
+			datestr = str(datestr)
 		except:
 			return None
 	dt = None
 	for f in dt_fmts:
 		try:
 			dt = datetime.datetime.strptime(datestr, f)
 		except:
 			continue
 		break
 	return dt
 
+dtzrx = re.compile(u"(.+)\s*([+-])(\d{1,2}):?(\d{2})$")
 def parse_datetimetz(data):
 	timestamptz_fmts = (
 		"%Y-%m-%d %H%M%Z", "%Y-%m-%d %H%M %Z",
 		"%Y-%m-%dT%H%M%Z", "%Y-%m-%dT%H%M %Z",
 		"%Y-%m-%d %H:%M%Z", "%Y-%m-%d %H:%M %Z",
 		"%Y-%m-%dT%H:%M%Z", "%Y-%m-%dT%H:%M %Z",
 		"%Y-%m-%d %H:%M:%S%Z", "%Y-%m-%d %H:%M:%S %Z",
@@ -4162,21 +4243,14 @@
 		"%Y-%m-%dT%I:%M:%S%p%Z", "%Y-%m-%dT%I:%M:%S%p %Z",
 		"%Y-%m-%d %I:%M:%S %p%Z", "%Y-%m-%d %I:%M:%S %p %Z",
 		"%Y-%m-%dT%I:%M:%S %p%Z", "%Y-%m-%dT%I:%M:%S %p %Z",
 		"%c%Z", "%c %Z",
 		"%x %X%Z", "%x %X %Z",
 		"%m/%d/%Y%Z", "%m/%d/%Y %Z",
 		"%m/%d/%y%Z", "%m/%d/%y %Z",
-		"%m/%d/%y %H%M%Z", "%m/%d/%y %H%M %Z",
-		"%m/%d/%y %H:%M%Z", "%m/%d/%y %H:%M %Z",
-		"%m/%d/%y %H:%M:%S%Z", "%m/%d/%y %H:%M:%S %Z",
-		"%m/%d/%y %I:%M%p%Z", "%m/%d/%y %I:%M%p %Z",
-		"%m/%d/%y %I:%M %p%Z", "%m/%d/%y %I:%M %p %Z",
-		"%m/%d/%y %I:%M:%S%p%Z", "%m/%d/%y %I:%M:%S%p %Z",
-		"%m/%d/%y %I:%M:%S %p%Z", "%m/%d/%y %I:%M:%S %p %Z",
 		"%m/%d/%Y %H%M%Z", "%m/%d/%Y %H%M %Z",
 		"%m/%d/%Y %H:%M%Z", "%m/%d/%Y %H:%M %Z",
 		"%m/%d/%Y %H:%M:%S%Z", "%m/%d/%Y %H:%M:%S %Z",
 		"%m/%d/%Y %I:%M%p%Z", "%m/%d/%Y %I:%M%p %Z",
 		"%m/%d/%Y %I:%M %p%Z", "%m/%d/%Y %I:%M %p %Z",
 		"%m/%d/%Y %I:%M:%S%p%Z", "%m/%d/%Y %I:%M:%S%p %Z",
 		"%m/%d/%Y %I:%M:%S %p%Z", "%m/%d/%Y %I:%M:%S %p %Z",
@@ -4217,15 +4291,14 @@
 		if data.tzinfo is None or data.tzinfo.utcoffset(data) is None:
 			return None
 		return data
 	if not isinstance(data, str):
 		return None
 	dt = None
 	# Check for numeric timezone
-	dtzrx = re.compile(u"(.+)\s*([+-])(\d{1,2}):?(\d{2})$")
 	try:
 		datestr, sign, hr, min = dtzrx.match(data).groups()
 		dt = parse_datetime(datestr)
 		if not dt:
 			return None
 		sign = -1 if sign=='-' else 1
 		return datetime.datetime(dt.year, dt.month, dt.day, dt.hour, dt.minute, dt.second, tzinfo=Tz(sign, int(hr), int(min)))
@@ -4239,15 +4312,14 @@
 			break
 		return dt
 
 def parse_date(data):
 	date_fmts = ("%x",
 			"%Y-%m-%d",
 			"%m/%d/%Y",
-			"%m/%d/%y",
 			"%Y/%m/%d",
 			"%b %d, %Y",
 			"%b %d %Y",
 			"%d %b, %Y",
 			"%d %b %Y",
 			"%b. %d, %Y",
 			"%b. %d %Y",
```

### Comparing `mapdata-2.6.7/mapdata.egg-info/PKG-INFO` & `mapdata-2.8.0/mapdata.egg-info/PKG-INFO`

 * *Files 3% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: mapdata
-Version: 2.6.7
+Version: 2.8.0
 Summary: An interactive map and table explorer for geographic coordinates in a spreadsheet, CSV file, or database
 Home-page: https://osdn.net/project/mapdata/
 Author: Dreas Nielsen
 Author-email: dreas.nielsen@gmail.com
 License: GPL
-Keywords: Map,Locations,CRS,CSV,PNG,JPG,Postscript
+Keywords: Map,Locations,CRS,CSV,Spreadsheet,Database,PNG,JPG,Postscript
 Platform: UNKNOWN
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Environment :: X11 Applications
 Classifier: Environment :: Win32 (MS Windows)
 Classifier: Intended Audience :: End Users/Desktop
 Classifier: Intended Audience :: Information Technology
@@ -68,14 +68,16 @@
 
 Data can also be displayed in several different types of plots: box plots, scatter
 plots, line charts, and counts of categorical and quantitative variables.  Plots
 can use either all data or only data values that are selected in the map and
 table.  Plots have a live connection to the data table, so when selections are
 changed the plots are automatically updated.
 
+<img src="https://mapdata.osdn.io/_images/UI_brownfields_plot.png" alt="Plot illustration", width="300"/>
+
 SQL commands can be used when pulling a data set from a database, to create
 a temporary table, for example, instead of using a base table.  The SQL
 commands can be augmented with [execsql](https://pypi.org/project/execsql/)
 metacommands and substitution variables.
 
 
 Complete documentation is at [https://mapdata.osdn.io](https://mapdata.osdn.io).
```

### Comparing `mapdata-2.6.7/setup.py` & `mapdata-2.8.0/setup.py`

 * *Files 8% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 import io
 
 with io.open('README.md', encoding='utf-8') as f:
 	long_description = f.read()
 
 setuptools.setup(name='mapdata',
-	version='2.6.7',
+	version='2.8.0',
 	description="An interactive map and table explorer for geographic coordinates in a spreadsheet, CSV file, or database",
 	author='Dreas Nielsen',
 	author_email='dreas.nielsen@gmail.com',
     url='https://osdn.net/project/mapdata/',
 	scripts=['mapdata/mapdata.py'],
     license='GPL',
 	requires=['tkintermapview', 'pyproj', 'odfpy', 'openpyxl', 'xlrd', 'matplotlib'],
@@ -26,11 +26,11 @@
 		'Operating System :: OS Independent',
 		'Operating System :: POSIX',
 		'Operating System :: Microsoft :: Windows',
 		'Programming Language :: Python :: 3',
 		'Topic :: Office/Business',
 		'Topic :: Scientific/Engineering'
 		],
-	keywords=['Map', 'Locations', 'CRS', 'CSV', 'PNG', 'JPG', 'Postscript'],
+	keywords=['Map', 'Locations', 'CRS', 'CSV', 'Spreadsheet', 'Database', 'PNG', 'JPG', 'Postscript'],
 	long_description_content_type="text/markdown",
 	long_description=long_description
 	)
```


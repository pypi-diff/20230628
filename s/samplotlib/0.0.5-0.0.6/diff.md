# Comparing `tmp/samplotlib-0.0.5.tar.gz` & `tmp/samplotlib-0.0.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "samplotlib-0.0.5.tar", last modified: Fri Mar 31 00:15:06 2023, max compression
+gzip compressed data, was "samplotlib-0.0.6.tar", last modified: Wed Jun 28 07:01:52 2023, max compression
```

## Comparing `samplotlib-0.0.5.tar` & `samplotlib-0.0.6.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 sam        (501) staff       (20)        0 2023-03-31 00:15:06.486905 samplotlib-0.0.5/
--rw-r--r--   0 sam        (501) staff       (20)    15579 2022-05-06 09:03:13.000000 samplotlib-0.0.5/LICENSE.md
--rw-r--r--   0 sam        (501) staff       (20)      591 2023-03-31 00:15:06.486976 samplotlib-0.0.5/PKG-INFO
--rw-r--r--   0 sam        (501) staff       (20)       84 2022-11-01 05:52:30.000000 samplotlib-0.0.5/README.md
--rw-r--r--   0 sam        (501) staff       (20)       86 2022-11-01 05:43:18.000000 samplotlib-0.0.5/pyproject.toml
-drwxr-xr-x   0 sam        (501) staff       (20)        0 2023-03-31 00:15:06.485466 samplotlib-0.0.5/samplotlib/
--rw-r--r--   0 sam        (501) staff       (20)        0 2022-05-06 01:48:16.000000 samplotlib-0.0.5/samplotlib/__init__.py
--rw-r--r--   0 sam        (501) staff       (20)    12027 2023-03-20 03:58:07.000000 samplotlib-0.0.5/samplotlib/baseplot.py
--rw-r--r--   0 sam        (501) staff       (20)     2968 2022-11-16 02:11:43.000000 samplotlib-0.0.5/samplotlib/circusboy.py
--rw-r--r--   0 sam        (501) staff       (20)     6958 2022-04-29 11:53:16.000000 samplotlib-0.0.5/samplotlib/colors.py
--rw-r--r--   0 sam        (501) staff       (20)     3431 2022-11-16 05:48:58.000000 samplotlib-0.0.5/samplotlib/graylady.py
--rw-r--r--   0 sam        (501) staff       (20)    13555 2022-08-26 10:58:32.000000 samplotlib-0.0.5/samplotlib/utils.py
-drwxr-xr-x   0 sam        (501) staff       (20)        0 2023-03-31 00:15:06.486743 samplotlib-0.0.5/samplotlib.egg-info/
--rw-r--r--   0 sam        (501) staff       (20)      591 2023-03-31 00:15:06.000000 samplotlib-0.0.5/samplotlib.egg-info/PKG-INFO
--rw-r--r--   0 sam        (501) staff       (20)      348 2023-03-31 00:15:06.000000 samplotlib-0.0.5/samplotlib.egg-info/SOURCES.txt
--rw-r--r--   0 sam        (501) staff       (20)        1 2023-03-31 00:15:06.000000 samplotlib-0.0.5/samplotlib.egg-info/dependency_links.txt
--rw-r--r--   0 sam        (501) staff       (20)       17 2023-03-31 00:15:06.000000 samplotlib-0.0.5/samplotlib.egg-info/requires.txt
--rw-r--r--   0 sam        (501) staff       (20)       11 2023-03-31 00:15:06.000000 samplotlib-0.0.5/samplotlib.egg-info/top_level.txt
--rw-r--r--   0 sam        (501) staff       (20)      641 2023-03-31 00:15:06.487310 samplotlib-0.0.5/setup.cfg
+drwxr-xr-x   0 sam        (501) staff       (20)        0 2023-06-28 07:01:52.646416 samplotlib-0.0.6/
+-rw-r--r--   0 sam        (501) staff       (20)    15579 2022-05-06 09:03:13.000000 samplotlib-0.0.6/LICENSE.md
+-rw-r--r--   0 sam        (501) staff       (20)      591 2023-06-28 07:01:52.646502 samplotlib-0.0.6/PKG-INFO
+-rw-r--r--   0 sam        (501) staff       (20)       84 2022-11-01 05:52:30.000000 samplotlib-0.0.6/README.md
+-rw-r--r--   0 sam        (501) staff       (20)       86 2022-11-01 05:43:18.000000 samplotlib-0.0.6/pyproject.toml
+drwxr-xr-x   0 sam        (501) staff       (20)        0 2023-06-28 07:01:52.645018 samplotlib-0.0.6/samplotlib/
+-rw-r--r--   0 sam        (501) staff       (20)        0 2022-05-06 01:48:16.000000 samplotlib-0.0.6/samplotlib/__init__.py
+-rw-r--r--   0 sam        (501) staff       (20)    12230 2023-06-26 09:45:56.000000 samplotlib-0.0.6/samplotlib/baseplot.py
+-rw-r--r--   0 sam        (501) staff       (20)     2968 2022-11-16 02:11:43.000000 samplotlib-0.0.6/samplotlib/circusboy.py
+-rw-r--r--   0 sam        (501) staff       (20)     6958 2022-04-29 11:53:16.000000 samplotlib-0.0.6/samplotlib/colors.py
+-rw-r--r--   0 sam        (501) staff       (20)     3431 2022-11-16 05:48:58.000000 samplotlib-0.0.6/samplotlib/graylady.py
+-rw-r--r--   0 sam        (501) staff       (20)    13555 2022-08-26 10:58:32.000000 samplotlib-0.0.6/samplotlib/utils.py
+drwxr-xr-x   0 sam        (501) staff       (20)        0 2023-06-28 07:01:52.646227 samplotlib-0.0.6/samplotlib.egg-info/
+-rw-r--r--   0 sam        (501) staff       (20)      591 2023-06-28 07:01:52.000000 samplotlib-0.0.6/samplotlib.egg-info/PKG-INFO
+-rw-r--r--   0 sam        (501) staff       (20)      348 2023-06-28 07:01:52.000000 samplotlib-0.0.6/samplotlib.egg-info/SOURCES.txt
+-rw-r--r--   0 sam        (501) staff       (20)        1 2023-06-28 07:01:52.000000 samplotlib-0.0.6/samplotlib.egg-info/dependency_links.txt
+-rw-r--r--   0 sam        (501) staff       (20)       17 2023-06-28 07:01:52.000000 samplotlib-0.0.6/samplotlib.egg-info/requires.txt
+-rw-r--r--   0 sam        (501) staff       (20)       11 2023-06-28 07:01:52.000000 samplotlib-0.0.6/samplotlib.egg-info/top_level.txt
+-rw-r--r--   0 sam        (501) staff       (20)      641 2023-06-28 07:01:52.646864 samplotlib-0.0.6/setup.cfg
```

### Comparing `samplotlib-0.0.5/LICENSE.md` & `samplotlib-0.0.6/LICENSE.md`

 * *Files identical despite different names*

### Comparing `samplotlib-0.0.5/PKG-INFO` & `samplotlib-0.0.6/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: samplotlib
-Version: 0.0.5
+Version: 0.0.6
 Summary: Plotting scripts extending matplotlib
 Home-page: https://github.com/passaglia/samplotlib
 Author: Sam Passaglia
 Project-URL: Bug Tracker, https://github.com/passaglia/samplotlib/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: Mozilla Public License 2.0 (MPL 2.0)
 Classifier: Operating System :: OS Independent
```

### Comparing `samplotlib-0.0.5/samplotlib/baseplot.py` & `samplotlib-0.0.6/samplotlib/baseplot.py`

 * *Files 2% similar despite different names*

```diff
@@ -204,53 +204,57 @@
                 textcoords="offset points",
                 color=self.grey,
                 va="top",
                 ha="left",
                 fontsize=self.fontsize - 2,
             )
 
-    def set_title(self, ax, title, subtitle=None, pad=None, gap=None):
+    def set_title(self, ax, title, subtitle=None, pad=None, gap=None, titlesize=None, subtitlesize=None):
+        if titlesize is None:
+            titlesize = self.titlesize
+        if subtitlesize is None:
+            subtitlesize = self.subtitlesize
         if pad is None:
             pad = 1.5 * self.fontsize  ## pad is the spacing between subtitle and axis
         if gap is None:
             gap = (
                 2 / 3 * self.fontsize
             )  ## gap is the spacing between title and subtitle
         if title is not None:
             if subtitle is None:
                 # ax.figure.suptitle(title, x=0,y=1.1, fontsize=self.titlesize,ha='left',va='bottom', transform=ax.transAxes,fontdict={'family':self.titleFont})
                 ax.figure.suptitle(
                     self.stringWithFont(self.titleFont, title),
                     x=0,
                     y=1.1,
-                    fontsize=self.titlesize,
+                    fontsize=titlesize,
                     ha="left",
                     va="bottom",
                     transform=ax.transAxes,
                 )
             else:
                 subtitle_nlines = 1 + subtitle.count("\n")
                 lineheight = self.fontsize
 
                 ax.set_title(
                     self.stringWithFont(self.textFont, subtitle),
                     x=0.0,
                     y=1.0,
-                    fontsize=self.subtitlesize,
+                    fontsize=subtitlesize,
                     ha="left",
                     va="bottom",
                     wrap=True,
                     pad=pad,
                 )
 
                 ax.annotate(
                     self.stringWithFont(self.titleFont, title),
                     (0, 1),
                     (0, pad + gap + subtitle_nlines * lineheight),
-                    fontsize=self.titlesize,
+                    fontsize=titlesize,
                     xycoords="axes fraction",
                     textcoords="offset points",
                     va="bottom",
                     ha="left",
                 )
 
     def set_xYear(self, ax):
@@ -308,22 +312,22 @@
                 return currency + label + unit
             else:
                 return label
 
         ax.yaxis.set_major_formatter(matplotlib.ticker.FuncFormatter(yformatter))
         return ax
 
-    def set_yTickLabels(self, ax):
+    def set_yTickLabels(self, ax, xoffset=0, yoffset=0):
         for label in ax.yaxis.get_ticklabels():
             label.set_verticalalignment("bottom")
             label.set_horizontalalignment("left")
 
         # Create offset transform by fontsize/3 points in y direction
-        dx = 0 / 72.0
-        dy = (self.fontsize / 3) / 72.0
+        dx = xoffset / 72.0
+        dy = (self.fontsize/3 + yoffset) / 72.0
         offset = matplotlib.transforms.ScaledTranslation(
             dx, dy, ax.figure.dpi_scale_trans
         )
         # apply offset transform to all y ticklabels.
         for label in ax.yaxis.get_majorticklabels():
             label.set_transform(label.get_transform() + offset)
```

### Comparing `samplotlib-0.0.5/samplotlib/circusboy.py` & `samplotlib-0.0.6/samplotlib/circusboy.py`

 * *Files identical despite different names*

### Comparing `samplotlib-0.0.5/samplotlib/colors.py` & `samplotlib-0.0.6/samplotlib/colors.py`

 * *Files identical despite different names*

### Comparing `samplotlib-0.0.5/samplotlib/graylady.py` & `samplotlib-0.0.6/samplotlib/graylady.py`

 * *Files identical despite different names*

### Comparing `samplotlib-0.0.5/samplotlib/utils.py` & `samplotlib-0.0.6/samplotlib/utils.py`

 * *Files identical despite different names*

### Comparing `samplotlib-0.0.5/samplotlib.egg-info/PKG-INFO` & `samplotlib-0.0.6/samplotlib.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: samplotlib
-Version: 0.0.5
+Version: 0.0.6
 Summary: Plotting scripts extending matplotlib
 Home-page: https://github.com/passaglia/samplotlib
 Author: Sam Passaglia
 Project-URL: Bug Tracker, https://github.com/passaglia/samplotlib/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: Mozilla Public License 2.0 (MPL 2.0)
 Classifier: Operating System :: OS Independent
```

### Comparing `samplotlib-0.0.5/setup.cfg` & `samplotlib-0.0.6/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = samplotlib
-version = 0.0.5
+version = 0.0.6
 author = Sam Passaglia
 description = Plotting scripts extending matplotlib
 long_description = file: README.md
 long_description_content_type = text/markdown
 url = https://github.com/passaglia/samplotlib
 project_urls = 
 	Bug Tracker = https://github.com/passaglia/samplotlib/issues
```


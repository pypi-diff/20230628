# Comparing `tmp/gofigr-0.11.2.tar.gz` & `tmp/gofigr-0.11.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "gofigr-0.11.2.tar", last modified: Fri Jun 23 13:39:31 2023, max compression
+gzip compressed data, was "gofigr-0.11.3.tar", last modified: Tue Jun 27 20:50:53 2023, max compression
```

## Comparing `gofigr-0.11.2.tar` & `gofigr-0.11.3.tar`

### file list

```diff
@@ -1,28 +1,29 @@
-drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-23 13:39:31.187308 gofigr-0.11.2/
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1078 2023-06-23 13:18:52.000000 gofigr-0.11.2/LICENSE
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)       80 2023-06-23 13:18:52.000000 gofigr-0.11.2/MANIFEST.in
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     7833 2023-06-23 13:39:31.187308 gofigr-0.11.2/PKG-INFO
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     6023 2023-06-23 13:18:52.000000 gofigr-0.11.2/README.rst
-drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-23 13:39:31.187308 gofigr-0.11.2/gofigr/
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)    12765 2023-06-23 13:18:52.000000 gofigr-0.11.2/gofigr/__init__.py
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     4991 2023-06-23 13:18:52.000000 gofigr-0.11.2/gofigr/gfconfig.py
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)    21114 2023-06-23 13:18:52.000000 gofigr-0.11.2/gofigr/jupyter.py
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)    42702 2023-06-23 13:18:52.000000 gofigr-0.11.2/gofigr/models.py
-drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-23 13:39:31.187308 gofigr-0.11.2/gofigr/resources/
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)   584424 2023-06-23 13:18:52.000000 gofigr-0.11.2/gofigr/resources/FreeMono.ttf
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)       76 2023-06-23 13:18:52.000000 gofigr-0.11.2/gofigr/resources/__init__.py
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     3170 2023-06-23 13:18:52.000000 gofigr-0.11.2/gofigr/watermarks.py
-drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-23 13:39:31.187308 gofigr-0.11.2/gofigr.egg-info/
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     7833 2023-06-23 13:39:31.000000 gofigr-0.11.2/gofigr.egg-info/PKG-INFO
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)      466 2023-06-23 13:39:31.000000 gofigr-0.11.2/gofigr.egg-info/SOURCES.txt
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)        1 2023-06-23 13:39:31.000000 gofigr-0.11.2/gofigr.egg-info/dependency_links.txt
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)       50 2023-06-23 13:39:31.000000 gofigr-0.11.2/gofigr.egg-info/entry_points.txt
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)      255 2023-06-23 13:39:31.000000 gofigr-0.11.2/gofigr.egg-info/requires.txt
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)        7 2023-06-23 13:39:31.000000 gofigr-0.11.2/gofigr.egg-info/top_level.txt
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1631 2023-06-23 13:18:52.000000 gofigr-0.11.2/pyproject.toml
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)       38 2023-06-23 13:39:31.187308 gofigr-0.11.2/setup.cfg
-drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-23 13:39:31.187308 gofigr-0.11.2/tests/
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)    40823 2023-06-23 13:18:52.000000 gofigr-0.11.2/tests/test_client.py
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1967 2023-06-23 13:18:52.000000 gofigr-0.11.2/tests/test_logs.py
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     2698 2023-06-23 13:18:52.000000 gofigr-0.11.2/tests/test_models.py
--rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1007 2023-06-23 13:18:52.000000 gofigr-0.11.2/tests/test_watermarks.py
+drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 20:50:53.472050 gofigr-0.11.3/
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1078 2023-06-27 20:31:07.000000 gofigr-0.11.3/LICENSE
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)       80 2023-06-27 20:31:07.000000 gofigr-0.11.3/MANIFEST.in
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     7833 2023-06-27 20:50:53.472050 gofigr-0.11.3/PKG-INFO
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     6023 2023-06-27 20:31:07.000000 gofigr-0.11.3/README.rst
+drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 20:50:53.468050 gofigr-0.11.3/gofigr/
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)    12765 2023-06-27 20:31:07.000000 gofigr-0.11.3/gofigr/__init__.py
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     4991 2023-06-27 20:31:07.000000 gofigr-0.11.3/gofigr/gfconfig.py
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)    23406 2023-06-27 20:31:07.000000 gofigr-0.11.3/gofigr/jupyter.py
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     3785 2023-06-27 20:31:07.000000 gofigr-0.11.3/gofigr/listener.py
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)    42702 2023-06-27 20:31:07.000000 gofigr-0.11.3/gofigr/models.py
+drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 20:50:53.468050 gofigr-0.11.3/gofigr/resources/
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)   584424 2023-06-27 20:31:07.000000 gofigr-0.11.3/gofigr/resources/FreeMono.ttf
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)       76 2023-06-27 20:31:07.000000 gofigr-0.11.3/gofigr/resources/__init__.py
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     5189 2023-06-27 20:31:07.000000 gofigr-0.11.3/gofigr/watermarks.py
+drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 20:50:53.468050 gofigr-0.11.3/gofigr.egg-info/
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     7833 2023-06-27 20:50:53.000000 gofigr-0.11.3/gofigr.egg-info/PKG-INFO
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)      485 2023-06-27 20:50:53.000000 gofigr-0.11.3/gofigr.egg-info/SOURCES.txt
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)        1 2023-06-27 20:50:53.000000 gofigr-0.11.3/gofigr.egg-info/dependency_links.txt
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)       50 2023-06-27 20:50:53.000000 gofigr-0.11.3/gofigr.egg-info/entry_points.txt
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)      266 2023-06-27 20:50:53.000000 gofigr-0.11.3/gofigr.egg-info/requires.txt
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)        7 2023-06-27 20:50:53.000000 gofigr-0.11.3/gofigr.egg-info/top_level.txt
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1645 2023-06-27 20:31:07.000000 gofigr-0.11.3/pyproject.toml
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)       38 2023-06-27 20:50:53.472050 gofigr-0.11.3/setup.cfg
+drwxrwxr-x   0 ubuntu    (1000) ubuntu    (1000)        0 2023-06-27 20:50:53.472050 gofigr-0.11.3/tests/
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)    40823 2023-06-27 20:31:07.000000 gofigr-0.11.3/tests/test_client.py
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1967 2023-06-27 20:31:07.000000 gofigr-0.11.3/tests/test_logs.py
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     2698 2023-06-27 20:31:07.000000 gofigr-0.11.3/tests/test_models.py
+-rw-rw-r--   0 ubuntu    (1000) ubuntu    (1000)     1007 2023-06-27 20:31:07.000000 gofigr-0.11.3/tests/test_watermarks.py
```

### Comparing `gofigr-0.11.2/LICENSE` & `gofigr-0.11.3/LICENSE`

 * *Files identical despite different names*

### Comparing `gofigr-0.11.2/PKG-INFO` & `gofigr-0.11.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gofigr
-Version: 0.11.2
+Version: 0.11.3
 Summary: GoFigr client library
 Author-email: Maciej Pacula <maciej@gofigr.io>
 License: Copyright 2022-2023 Flagstaff Solutions, LLC
         
         Permission is hereby granted, free of charge, to any person obtaining a copy of
         this software and associated documentation files (the “Software”), to deal in
         the Software without restriction, including without limitation the rights to
@@ -20,28 +20,28 @@
         FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
         AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
         LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
         OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
         THE SOFTWARE.
         
 Project-URL: Homepage, https://www.gofigr.io
-Project-URL: Documentation, https://gofigr.io/docs/gofigr-python/0.11.2/
+Project-URL: Documentation, https://gofigr.io/docs/gofigr-python/0.11.3/
 Keywords: science,visualization,version control,plotting,data,reproducibility
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
 Provides-Extra: dev
 License-File: LICENSE
 
 .. figure:: docs/source/images/logo_wide_light.png
   :alt: GoFigr.io logo
 
-GoFigr - Python Client (0.11.2)
+GoFigr - Python Client (0.11.3)
 ====================================
 GoFigr (https://www.gofigr.io) is a service which provides sophisticated version control for figures.
 
 This repository contains the Python client for GoFigr.
 
 Account registration
 ********************
```

### Comparing `gofigr-0.11.2/README.rst` & `gofigr-0.11.3/README.rst`

 * *Files 0% similar despite different names*

```diff
@@ -1,11 +1,11 @@
 .. figure:: docs/source/images/logo_wide_light.png
   :alt: GoFigr.io logo
 
-GoFigr - Python Client (0.11.2)
+GoFigr - Python Client (0.11.3)
 ====================================
 GoFigr (https://www.gofigr.io) is a service which provides sophisticated version control for figures.
 
 This repository contains the Python client for GoFigr.
 
 Account registration
 ********************
```

### Comparing `gofigr-0.11.2/gofigr/__init__.py` & `gofigr-0.11.3/gofigr/__init__.py`

 * *Files identical despite different names*

### Comparing `gofigr-0.11.2/gofigr/gfconfig.py` & `gofigr-0.11.3/gofigr/gfconfig.py`

 * *Files identical despite different names*

### Comparing `gofigr-0.11.2/gofigr/jupyter.py` & `gofigr-0.11.3/gofigr/jupyter.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,36 +1,41 @@
 """\
 Copyright (c) 2022, Flagstaff Solutions, LLC
 All rights reserved.
 
 """
 
-# pylint: disable=cyclic-import, no-member, global-statement, protected-access
+# pylint: disable=cyclic-import, no-member, global-statement, protected-access, wrong-import-order
 
 import inspect
 import io
 import json
 import os
 import subprocess
 import sys
 from collections import namedtuple
 from functools import wraps
+from urllib.parse import unquote, urlparse
 from uuid import UUID
 
 import PIL
 import ipynbname
+import matplotlib
 import matplotlib.pyplot as plt
 import six
 
 try:
     from IPython.core.display_functions import display
 except ModuleNotFoundError:
     from IPython.core.display import display
 
+from IPython.core.display import Javascript
+
 from gofigr import GoFigr, CodeLanguage, API_URL
+from gofigr.listener import run_listener_async
 from gofigr.watermarks import DefaultWatermark
 
 
 class _GoFigrExtension:
     """\
     Implements the main Jupyter extension functionality. You will not want to instantiate this class directly.
     Instead, please refer to the _GF_EXTENSION singleton.
@@ -98,14 +103,15 @@
 
         handlers = [self.post_execute] + handlers
         for handler in handlers:
             self.shell.events.register('post_execute', handler)
 
 
 _GF_EXTENSION = None  # GoFigrExtension global
+_NOTEBOOK_METADATA = None
 
 
 def require_configured(func):
     """\
     Decorator which throws an exception if configure() has not been called yet.
 
     :param func:
@@ -203,35 +209,57 @@
         :param revision: FigureRevision
         :return: annotated FigureRevision
 
         """
         return revision
 
 
+PATH_WARNING = "To fix this warning, you can manually specify the notebook name & path in the call to configure(). " \
+               "Please see https://gofigr.io/docs/gofigr-python/latest/customization.html#notebook-name-path " \
+               "for details."
+
+
 class NotebookNameAnnotator(Annotator):
     """"Annotates revisions with the name & path of the current notebook"""
+    def infer_from_metadata(self):
+        """Infers the notebook path & name from metadata passed through the WebSocket (if available)"""
+        meta = _NOTEBOOK_METADATA
+        if meta is None:
+            raise RuntimeError("No Notebook metadata available")
+        if 'url' not in meta:
+            raise RuntimeError("No URL found in Notebook metadata")
+
+        notebook_name = unquote(urlparse(meta['url']).path.rsplit('/', 1)[-1])
+        notebook_dir = _GF_EXTENSION.shell.starting_dir
+        full_path = os.path.join(notebook_dir, notebook_name)
+        if not os.path.exists(full_path):
+            print(f"The inferred path for the notebook does not exist: {full_path}. {PATH_WARNING}", file=sys.stderr)
+
+        return full_path, notebook_name
+
     def annotate(self, revision):
         if revision.metadata is None:
             revision.metadata = {}
 
         try:
             if 'notebook_name' not in revision.metadata:
                 revision.metadata['notebook_name'] = ipynbname.name()
             if 'notebook_path' not in revision.metadata:
                 revision.metadata['notebook_path'] = str(ipynbname.path())
 
         except Exception:  # pylint: disable=broad-exception-caught
-            print("GoFigr could not automatically obtain the name of the currently running notebook. To fix this error,"
-                  " you can manually specify the notebook name & path in the call to configure(). "
-                  "Please see https://gofigr.io/docs/gofigr-python/latest/customization.html#notebook-name-path "
-                  "for details.",
-                  file=sys.stderr)
+            try:
+                revision.metadata['notebook_path'], revision.metadata['notebook_name'] = self.infer_from_metadata()
+            except Exception:  # pylint: disable=broad-exception-caught
+                print(f"GoFigr could not automatically obtain the name of the currently"
+                      f" running notebook. {PATH_WARNING}",
+                      file=sys.stderr)
 
-            revision.metadata['notebook_name'] = "N/A"
-            revision.metadata['notebook_path'] = "N/A"
+                revision.metadata['notebook_name'] = "N/A"
+                revision.metadata['notebook_path'] = "N/A"
 
         return revision
 
 
 class CellIdAnnotator(Annotator):
     """Annotates revisions with the ID of the Jupyter cell"""
     def annotate(self, revision):
@@ -337,19 +365,31 @@
         """
         for num in plt.get_fignums():
             fig = plt.figure(num)
             if not getattr(fig, '_gf_is_published', False):
                 self.publish(fig=fig)
 
     @staticmethod
+    def _title_to_string(title):
+        """Extracts the title as a string from a title-like object (e.g. Text)"""
+        if title is None:
+            return None
+        elif isinstance(title, matplotlib.text.Text):
+            return title.get_text()
+        elif isinstance(title, str):
+            return title
+        else:
+            return None
+
+    @staticmethod
     def _resolve_target(gf, fig, target):
         if target is None:
             # Try to get the figure's title
-            suptitle = getattr(fig, "_suptitle", "")
-            title = fig.axes[0].get_title() if len(fig.axes) > 0 else None
+            suptitle = Publisher._title_to_string(getattr(fig, "_suptitle", ""))
+            title = Publisher._title_to_string(fig.axes[0].get_title() if len(fig.axes) > 0 else None)
             if suptitle is not None and suptitle.strip() != "":
                 fig_name = suptitle
             elif title is not None and title.strip() != "":
                 fig_name = title
             else:
                 print("Your figure doesn't have a title and will be published as 'Anonymous Figure'. "
                       "To avoid this warning, set a figure title or manually call publish() with a target figure. "
@@ -520,14 +560,22 @@
     elif len(matches) > 1:
         raise RuntimeError(f'Multiple (n={len(matches)}) workspaces match name "{search.name}". '
                            f'Please use an API ID instead.')
     else:
         return matches[0]
 
 
+def listener_callback(result):
+    """WebSocket callback"""
+    global _NOTEBOOK_METADATA
+
+    if result is not None and isinstance(result, dict) and result['message_type'] == "metadata":
+        _NOTEBOOK_METADATA = result
+
+
 # pylint: disable=too-many-arguments
 @from_config_or_env("GF_", os.path.join(os.environ['HOME'], '.gofigr'))
 def configure(username, password, workspace=None, analysis=None, url=API_URL,
               default_metadata=None, auto_publish=True,
               watermark=None, annotators=DEFAULT_ANNOTATORS,
               notebook_name=None, notebook_path=None):
     """\
@@ -586,14 +634,28 @@
     extension.analysis = analysis
     extension.workspace = workspace
     extension.publisher = publisher
 
     if auto_publish:
         extension.post_execute_hook = publisher.auto_publish_hook
 
+    listener_port = run_listener_async(listener_callback)
+
+    display(Javascript(f"""
+    document._ws_gf = new WebSocket("ws://localhost:{listener_port}");
+    document._ws_gf.onopen = () => {{
+      console.log("GoFigr WebSocket open at ws://localhost:{listener_port}");
+      document._ws_gf.send(JSON.stringify(
+      {{
+        message_type: "metadata",
+        url: document.URL
+      }}))
+    }}
+    """))
+
 
 @require_configured
 def publish(*args, **kwargs):
     """\
     Publishes a figure. See :func:`gofigr.jupyter.Publisher.publish` for a list of arguments.
 
     :param args:
```

### Comparing `gofigr-0.11.2/gofigr/models.py` & `gofigr-0.11.3/gofigr/models.py`

 * *Files identical despite different names*

### Comparing `gofigr-0.11.2/gofigr/resources/FreeMono.ttf` & `gofigr-0.11.3/gofigr/resources/FreeMono.ttf`

 * *Files identical despite different names*

### Comparing `gofigr-0.11.2/gofigr.egg-info/PKG-INFO` & `gofigr-0.11.3/gofigr.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: gofigr
-Version: 0.11.2
+Version: 0.11.3
 Summary: GoFigr client library
 Author-email: Maciej Pacula <maciej@gofigr.io>
 License: Copyright 2022-2023 Flagstaff Solutions, LLC
         
         Permission is hereby granted, free of charge, to any person obtaining a copy of
         this software and associated documentation files (the “Software”), to deal in
         the Software without restriction, including without limitation the rights to
@@ -20,28 +20,28 @@
         FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
         AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
         LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
         OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
         THE SOFTWARE.
         
 Project-URL: Homepage, https://www.gofigr.io
-Project-URL: Documentation, https://gofigr.io/docs/gofigr-python/0.11.2/
+Project-URL: Documentation, https://gofigr.io/docs/gofigr-python/0.11.3/
 Keywords: science,visualization,version control,plotting,data,reproducibility
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
 Requires-Python: >=3.7
 Description-Content-Type: text/x-rst
 Provides-Extra: dev
 License-File: LICENSE
 
 .. figure:: docs/source/images/logo_wide_light.png
   :alt: GoFigr.io logo
 
-GoFigr - Python Client (0.11.2)
+GoFigr - Python Client (0.11.3)
 ====================================
 GoFigr (https://www.gofigr.io) is a service which provides sophisticated version control for figures.
 
 This repository contains the Python client for GoFigr.
 
 Account registration
 ********************
```

### Comparing `gofigr-0.11.2/pyproject.toml` & `gofigr-0.11.3/pyproject.toml`

 * *Files 6% similar despite different names*

```diff
@@ -2,44 +2,44 @@
 
 [build-system]
 requires      = ["setuptools>=61.0.0", "wheel"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "gofigr"
-version = "0.11.2"
+version = "0.11.3"
 description = "GoFigr client library"
 readme = "README.rst"
 authors = [{ name = "Maciej Pacula", email = "maciej@gofigr.io" }]
 license = { file = "LICENSE" }
 classifiers = [
     "License :: OSI Approved :: MIT License",
     "Programming Language :: Python",
     "Programming Language :: Python :: 3",
 ]
 keywords = ["science", "visualization", "version control", "plotting", "data", "reproducibility"]
 dependencies = [
     "numpy", "pandas", "pyqrcode", "pillow", "matplotlib", "dateutils",
-    "python-dateutil", "ipython", "requests", "pypng", "ipynbname"
+    "python-dateutil", "ipython", "requests", "pypng", "ipynbname", "websockets"
 ]
 requires-python = ">=3.7"
 
 [project.optional-dependencies]
 dev = ["pip-tools", "bumpver", "build", "twine", "pylint", "flake8", "sphinx", "sphinx_rtd_theme", "sphinxcontrib-jquery",
        "seaborn", "matplotlib", "tqdm", "selenium", "webdriver-manager", "openpyxl"]
 
 [project.urls]
 Homepage = "https://www.gofigr.io"
-Documentation = "https://gofigr.io/docs/gofigr-python/0.11.2/"
+Documentation = "https://gofigr.io/docs/gofigr-python/0.11.3/"
 
 [project.scripts]
 gfconfig = "gofigr.gfconfig:main"
 
 [tool.bumpver]
-current_version = "0.11.2"
+current_version = "0.11.3"
 version_pattern = "MAJOR.MINOR.PATCH"
 commit_message = "Bump version {old_version} -> {new_version}"
 commit = true
 tag = true
 push = false
 
 [tool.bumpver.file_patterns]
```

### Comparing `gofigr-0.11.2/tests/test_client.py` & `gofigr-0.11.3/tests/test_client.py`

 * *Files identical despite different names*

### Comparing `gofigr-0.11.2/tests/test_logs.py` & `gofigr-0.11.3/tests/test_logs.py`

 * *Files identical despite different names*

### Comparing `gofigr-0.11.2/tests/test_models.py` & `gofigr-0.11.3/tests/test_models.py`

 * *Files identical despite different names*

### Comparing `gofigr-0.11.2/tests/test_watermarks.py` & `gofigr-0.11.3/tests/test_watermarks.py`

 * *Files identical despite different names*


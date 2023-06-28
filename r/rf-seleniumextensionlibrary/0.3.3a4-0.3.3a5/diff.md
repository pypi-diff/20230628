# Comparing `tmp/rf_seleniumextensionlibrary-0.3.3a4-py3-none-any.whl.zip` & `tmp/rf_seleniumextensionlibrary-0.3.3a5-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,10 +1,10 @@
-Zip file size: 11352 bytes, number of entries: 8
--rw-rw-r--  2.0 unx    21992 b- defN 21-Sep-08 07:27 SeleniumExtensionLibrary/SeleniumExtensionLibrary.py
--rw-rw-r--  2.0 unx     1193 b- defN 21-Sep-07 13:26 SeleniumExtensionLibrary/__init__.py
--rw-rw-r--  2.0 unx     1132 b- defN 21-Sep-08 07:27 SeleniumExtensionLibrary/version.py
--rw-rw-r--  2.0 unx     1078 b- defN 21-Sep-08 07:52 rf_seleniumextensionlibrary-0.3.3a4.dist-info/LICENSE
--rw-rw-r--  2.0 unx     3055 b- defN 21-Sep-08 07:52 rf_seleniumextensionlibrary-0.3.3a4.dist-info/METADATA
--rw-rw-r--  2.0 unx       92 b- defN 21-Sep-08 07:52 rf_seleniumextensionlibrary-0.3.3a4.dist-info/WHEEL
--rw-rw-r--  2.0 unx       25 b- defN 21-Sep-08 07:52 rf_seleniumextensionlibrary-0.3.3a4.dist-info/top_level.txt
-?rw-rw-r--  2.0 unx      791 b- defN 21-Sep-08 07:52 rf_seleniumextensionlibrary-0.3.3a4.dist-info/RECORD
-8 files, 29358 bytes uncompressed, 9938 bytes compressed:  66.1%
+Zip file size: 11430 bytes, number of entries: 8
+-rw-r--r--  2.0 unx    22369 b- defN 23-Jun-28 15:25 SeleniumExtensionLibrary/SeleniumExtensionLibrary.py
+-rw-r--r--  2.0 unx     1193 b- defN 23-Jun-28 15:24 SeleniumExtensionLibrary/__init__.py
+-rw-r--r--  2.0 unx     1132 b- defN 22-Sep-16 07:46 SeleniumExtensionLibrary/version.py
+-rw-r--r--  2.0 unx     1078 b- defN 23-Jun-28 16:04 rf_seleniumextensionlibrary-0.3.3a5.dist-info/LICENSE
+-rw-r--r--  2.0 unx     3055 b- defN 23-Jun-28 16:04 rf_seleniumextensionlibrary-0.3.3a5.dist-info/METADATA
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 16:04 rf_seleniumextensionlibrary-0.3.3a5.dist-info/WHEEL
+-rw-r--r--  2.0 unx       25 b- defN 23-Jun-28 16:04 rf_seleniumextensionlibrary-0.3.3a5.dist-info/top_level.txt
+?rw-rw-r--  2.0 unx      791 b- defN 23-Jun-28 16:04 rf_seleniumextensionlibrary-0.3.3a5.dist-info/RECORD
+8 files, 29735 bytes uncompressed, 10016 bytes compressed:  66.3%
```

## zipnote {}

```diff
@@ -3,23 +3,23 @@
 
 Filename: SeleniumExtensionLibrary/__init__.py
 Comment: 
 
 Filename: SeleniumExtensionLibrary/version.py
 Comment: 
 
-Filename: rf_seleniumextensionlibrary-0.3.3a4.dist-info/LICENSE
+Filename: rf_seleniumextensionlibrary-0.3.3a5.dist-info/LICENSE
 Comment: 
 
-Filename: rf_seleniumextensionlibrary-0.3.3a4.dist-info/METADATA
+Filename: rf_seleniumextensionlibrary-0.3.3a5.dist-info/METADATA
 Comment: 
 
-Filename: rf_seleniumextensionlibrary-0.3.3a4.dist-info/WHEEL
+Filename: rf_seleniumextensionlibrary-0.3.3a5.dist-info/WHEEL
 Comment: 
 
-Filename: rf_seleniumextensionlibrary-0.3.3a4.dist-info/top_level.txt
+Filename: rf_seleniumextensionlibrary-0.3.3a5.dist-info/top_level.txt
 Comment: 
 
-Filename: rf_seleniumextensionlibrary-0.3.3a4.dist-info/RECORD
+Filename: rf_seleniumextensionlibrary-0.3.3a5.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## SeleniumExtensionLibrary/SeleniumExtensionLibrary.py

```diff
@@ -20,14 +20,15 @@
 
 import json
 import psutil
 import time
 import warnings
 import datetime
 from browsermobproxy import Server
+from datetime import timedelta
 from urllib.parse import urlparse, parse_qs
 from .version import VERSION
 from SeleniumLibrary import SeleniumLibrary
 from SeleniumLibrary.utils import LibraryListener, timestr_to_secs, is_truthy
 
 from robotlibcore import DynamicCore
 
@@ -218,18 +219,27 @@
 class SeleniumExtensionLibrary(SeleniumLibrary):
     # use the same doc as SeleniumLibrary
     __doc__ = "SeleniumExtensionLibrary is SeleniumLibrary extension.\n" + SeleniumLibrary.__doc__
 
     ROBOT_LIBRARY_SCOPE = 'GLOBAL'
     ROBOT_LIBRARY_VERSION = VERSION
 
-    def __init__(self, timeout=5.0, implicit_wait=0.0, run_on_failure='Capture Page',
-                 screenshot_root_directory=None, plugins=None, event_firing_webdriver=None):
+    def __init__(self, 
+                 timeout=5.0, 
+                 implicit_wait=0.0, 
+                 run_on_failure='Capture Page',
+                 screenshot_root_directory=None, 
+                 plugins=None, 
+                 event_firing_webdriver=None,
+                 page_load_timeout=timedelta(minutes=5),
+                 action_chain_delay=timedelta(seconds=0.25)):
         self.timeout = timestr_to_secs(timeout)
         self.implicit_wait = timestr_to_secs(implicit_wait)
+        self.page_load_timeout = timestr_to_secs(page_load_timeout)
+        self.action_chain_delay = timestr_to_secs(action_chain_delay)
         self.speed = 0.0
         self.run_on_failure_keyword \
             = RunOnFailureKeywords.resolve_keyword(run_on_failure)
         self._running_on_failure_keyword = False
         self.screenshot_root_directory = screenshot_root_directory
         self._element_finder = ElementFinder(self)
         self._plugin_keywords = []
```

## SeleniumExtensionLibrary/version.py

```diff
@@ -14,8 +14,8 @@
 # IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 # FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 # AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 # LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 # OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
 # SOFTWARE.
 
-VERSION = '0.3.3a4'
+VERSION = '0.3.3a5'
```

## Comparing `rf_seleniumextensionlibrary-0.3.3a4.dist-info/LICENSE` & `rf_seleniumextensionlibrary-0.3.3a5.dist-info/LICENSE`

 * *Files identical despite different names*

## Comparing `rf_seleniumextensionlibrary-0.3.3a4.dist-info/METADATA` & `rf_seleniumextensionlibrary-0.3.3a5.dist-info/METADATA`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: rf-seleniumextensionlibrary
-Version: 0.3.3a4
+Version: 0.3.3a5
 Summary: Selenium Extension Library
 Home-page: https://github.com/MainSystemDev/rf-seleniumextensionlibray
 Author: Shiela Buitizon
 Author-email: shiela.buitizon@mnltechnology.com
 License: Type license() to see the full license text
 Platform: any
 Classifier: Development Status :: 5 - Production/Stable
@@ -14,15 +14,15 @@
 Classifier: Topic :: Software Development :: Testing
 Classifier: Framework :: Robot Framework
 Classifier: Framework :: Robot Framework :: Library
 Description-Content-Type: text/markdown
 Requires-Dist: browsermob-proxy (==0.8.0)
 Requires-Dist: image (==1.5.33)
 Requires-Dist: psutil (==5.8.0)
-Requires-Dist: robotframework-seleniumlibrary (>=5.1.3)
+Requires-Dist: robotframework-seleniumlibrary (>=6.0.0)
 
 SeleniumExtensionLibrary
 ================
 
 Library Scope: __GLOBAL__  
 Created: __10/29/2019 16:21 PM UTC-8__
```

## Comparing `rf_seleniumextensionlibrary-0.3.3a4.dist-info/RECORD` & `rf_seleniumextensionlibrary-0.3.3a5.dist-info/RECORD`

 * *Files 12% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-SeleniumExtensionLibrary/SeleniumExtensionLibrary.py,sha256=w708KlXRiQXMTBMEiQ9hP6q7aN0NQ7MvbtjFYPZNk20,21992
+SeleniumExtensionLibrary/SeleniumExtensionLibrary.py,sha256=Q4nNkDHnPH4LYpjVfu9ZemYtbPkxo83r_-Hv7KOoCSs,22369
 SeleniumExtensionLibrary/__init__.py,sha256=2r275jS82S8hR29yOtr5TMpNqbUdlbNjWj71vOibJjc,1193
-SeleniumExtensionLibrary/version.py,sha256=b_NbHIWYx0ARAdTgC615qhBgNKxTg6N5JpvXX5pQ4Rg,1132
-rf_seleniumextensionlibrary-0.3.3a4.dist-info/LICENSE,sha256=MCWiTNF96jwMFJj70Vvg0MHzcbpSdvfzQA-xdP-lHZg,1078
-rf_seleniumextensionlibrary-0.3.3a4.dist-info/METADATA,sha256=Ob-GnQxdsNLQVuffD4ZItarz6mrqu29_aOtl8q1fXoM,3055
-rf_seleniumextensionlibrary-0.3.3a4.dist-info/WHEEL,sha256=p46_5Uhzqz6AzeSosiOnxK-zmFja1i22CrQCjmYe8ec,92
-rf_seleniumextensionlibrary-0.3.3a4.dist-info/top_level.txt,sha256=4tbxRI2xc5qtOVEV3CTuLbMOqF6Hg62OemloDL7QwlM,25
-rf_seleniumextensionlibrary-0.3.3a4.dist-info/RECORD,,
+SeleniumExtensionLibrary/version.py,sha256=2VzVB4T0SwWDAuc7RLsHrbT4ZCz3jVmuR6_HNoX03Uc,1132
+rf_seleniumextensionlibrary-0.3.3a5.dist-info/LICENSE,sha256=MCWiTNF96jwMFJj70Vvg0MHzcbpSdvfzQA-xdP-lHZg,1078
+rf_seleniumextensionlibrary-0.3.3a5.dist-info/METADATA,sha256=-9wYLL_6wztzosCWIZ-Xrjr5dxzSE12KIfPdeXCWLN0,3055
+rf_seleniumextensionlibrary-0.3.3a5.dist-info/WHEEL,sha256=S6zePDbUAjzMmpYOg2cHDxuYFWw7WiOXt6ogM6hIB5Q,92
+rf_seleniumextensionlibrary-0.3.3a5.dist-info/top_level.txt,sha256=4tbxRI2xc5qtOVEV3CTuLbMOqF6Hg62OemloDL7QwlM,25
+rf_seleniumextensionlibrary-0.3.3a5.dist-info/RECORD,,
```


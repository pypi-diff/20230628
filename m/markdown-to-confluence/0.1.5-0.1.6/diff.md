# Comparing `tmp/markdown-to-confluence-0.1.5.tar.gz` & `tmp/markdown-to-confluence-0.1.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "markdown-to-confluence-0.1.5.tar", last modified: Fri Apr 21 20:22:41 2023, max compression
+gzip compressed data, was "markdown-to-confluence-0.1.6.tar", last modified: Wed Jun 28 12:35:13 2023, max compression
```

## Comparing `markdown-to-confluence-0.1.5.tar` & `markdown-to-confluence-0.1.6.tar`

### file list

```diff
@@ -1,23 +1,23 @@
-drwxr-xr-x   0 levente.hunyadi   (503) staff       (20)        0 2023-04-21 20:22:41.874459 markdown-to-confluence-0.1.5/
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)     1077 2023-04-21 19:22:25.000000 markdown-to-confluence-0.1.5/LICENSE
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)     3720 2023-04-21 20:22:41.874640 markdown-to-confluence-0.1.5/PKG-INFO
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)     2907 2022-12-09 13:01:59.000000 markdown-to-confluence-0.1.5/README.md
-drwxr-xr-x   0 levente.hunyadi   (503) staff       (20)        0 2023-04-21 20:22:41.870827 markdown-to-confluence-0.1.5/markdown_to_confluence.egg-info/
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)     3720 2023-04-21 20:22:41.000000 markdown-to-confluence-0.1.5/markdown_to_confluence.egg-info/PKG-INFO
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)      455 2023-04-21 20:22:41.000000 markdown-to-confluence-0.1.5/markdown_to_confluence.egg-info/SOURCES.txt
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)        1 2023-04-21 20:22:41.000000 markdown-to-confluence-0.1.5/markdown_to_confluence.egg-info/dependency_links.txt
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)      105 2023-04-21 20:22:41.000000 markdown-to-confluence-0.1.5/markdown_to_confluence.egg-info/requires.txt
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)        8 2023-04-21 20:22:41.000000 markdown-to-confluence-0.1.5/markdown_to_confluence.egg-info/top_level.txt
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)        1 2023-04-21 20:22:41.000000 markdown-to-confluence-0.1.5/markdown_to_confluence.egg-info/zip-safe
-drwxr-xr-x   0 levente.hunyadi   (503) staff       (20)        0 2023-04-21 20:22:41.873672 markdown-to-confluence-0.1.5/md2conf/
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)      402 2023-04-21 19:21:10.000000 markdown-to-confluence-0.1.5/md2conf/__init__.py
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)     1574 2022-07-15 10:45:42.000000 markdown-to-confluence-0.1.5/md2conf/__main__.py
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)    10672 2023-04-21 20:09:24.000000 markdown-to-confluence-0.1.5/md2conf/api.py
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)      786 2022-12-09 13:03:45.000000 markdown-to-confluence-0.1.5/md2conf/application.py
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)     8506 2023-04-21 20:13:41.000000 markdown-to-confluence-0.1.5/md2conf/converter.py
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)        0 2023-04-21 19:11:21.000000 markdown-to-confluence-0.1.5/md2conf/py.typed
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)       94 2022-06-17 11:04:46.000000 markdown-to-confluence-0.1.5/pyproject.toml
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)     1082 2023-04-21 20:22:41.875537 markdown-to-confluence-0.1.5/setup.cfg
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)       69 2022-06-17 11:09:13.000000 markdown-to-confluence-0.1.5/setup.py
-drwxr-xr-x   0 levente.hunyadi   (503) staff       (20)        0 2023-04-21 20:22:41.874047 markdown-to-confluence-0.1.5/tests/
--rw-r--r--   0 levente.hunyadi   (503) staff       (20)     2358 2023-04-21 19:25:53.000000 markdown-to-confluence-0.1.5/tests/test_api.py
+drwxr-xr-x   0 levente.hunyadi   (503) staff       (20)        0 2023-06-28 12:35:13.070721 markdown-to-confluence-0.1.6/
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)     1077 2023-04-21 19:22:25.000000 markdown-to-confluence-0.1.6/LICENSE
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)     3743 2023-06-28 12:35:13.071026 markdown-to-confluence-0.1.6/PKG-INFO
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)     2907 2022-12-09 13:01:59.000000 markdown-to-confluence-0.1.6/README.md
+drwxr-xr-x   0 levente.hunyadi   (503) staff       (20)        0 2023-06-28 12:35:13.065700 markdown-to-confluence-0.1.6/markdown_to_confluence.egg-info/
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)     3743 2023-06-28 12:35:13.000000 markdown-to-confluence-0.1.6/markdown_to_confluence.egg-info/PKG-INFO
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)      455 2023-06-28 12:35:13.000000 markdown-to-confluence-0.1.6/markdown_to_confluence.egg-info/SOURCES.txt
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)        1 2023-06-28 12:35:13.000000 markdown-to-confluence-0.1.6/markdown_to_confluence.egg-info/dependency_links.txt
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)      105 2023-06-28 12:35:13.000000 markdown-to-confluence-0.1.6/markdown_to_confluence.egg-info/requires.txt
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)        8 2023-06-28 12:35:13.000000 markdown-to-confluence-0.1.6/markdown_to_confluence.egg-info/top_level.txt
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)        1 2023-06-28 12:35:12.000000 markdown-to-confluence-0.1.6/markdown_to_confluence.egg-info/zip-safe
+drwxr-xr-x   0 levente.hunyadi   (503) staff       (20)        0 2023-06-28 12:35:13.069494 markdown-to-confluence-0.1.6/md2conf/
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)      402 2023-06-28 12:33:21.000000 markdown-to-confluence-0.1.6/md2conf/__init__.py
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)     2354 2023-06-28 12:33:51.000000 markdown-to-confluence-0.1.6/md2conf/__main__.py
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)    11273 2023-05-31 12:50:28.000000 markdown-to-confluence-0.1.6/md2conf/api.py
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)      864 2023-06-28 12:33:51.000000 markdown-to-confluence-0.1.6/md2conf/application.py
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)     9018 2023-06-28 12:33:51.000000 markdown-to-confluence-0.1.6/md2conf/converter.py
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)        0 2023-04-21 19:11:21.000000 markdown-to-confluence-0.1.6/md2conf/py.typed
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)       94 2022-06-17 11:04:46.000000 markdown-to-confluence-0.1.6/pyproject.toml
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)     1106 2023-06-28 12:35:13.072240 markdown-to-confluence-0.1.6/setup.cfg
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)       69 2022-06-17 11:09:13.000000 markdown-to-confluence-0.1.6/setup.py
+drwxr-xr-x   0 levente.hunyadi   (503) staff       (20)        0 2023-06-28 12:35:13.070021 markdown-to-confluence-0.1.6/tests/
+-rw-r--r--   0 levente.hunyadi   (503) staff       (20)     2460 2023-06-28 12:33:51.000000 markdown-to-confluence-0.1.6/tests/test_api.py
```

### Comparing `markdown-to-confluence-0.1.5/LICENSE` & `markdown-to-confluence-0.1.6/LICENSE`

 * *Files identical despite different names*

### Comparing `markdown-to-confluence-0.1.5/PKG-INFO` & `markdown-to-confluence-0.1.6/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: markdown-to-confluence
-Version: 0.1.5
+Version: 0.1.6
 Summary: Publish Markdown files to Confluence wiki
 Home-page: https://github.com/hunyadi/md2conf
 Author: Levente Hunyadi
 Author-email: hunyadi@gmail.com
 License: MIT
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
@@ -13,14 +13,15 @@
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Typing :: Typed
+Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # Publish Markdown files to Confluence wiki
 
 Contributors to software projects typically write documentation in Markdown format and host Markdown files in collaborative version control systems (VCS) such as GitHub or GitLab to track changes and facilitate the review process. However, not everyone at a company has access to VCS, and documents are often circulated in Confluence wiki instead.
```

### Comparing `markdown-to-confluence-0.1.5/README.md` & `markdown-to-confluence-0.1.6/README.md`

 * *Files identical despite different names*

### Comparing `markdown-to-confluence-0.1.5/markdown_to_confluence.egg-info/PKG-INFO` & `markdown-to-confluence-0.1.6/markdown_to_confluence.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: markdown-to-confluence
-Version: 0.1.5
+Version: 0.1.6
 Summary: Publish Markdown files to Confluence wiki
 Home-page: https://github.com/hunyadi/md2conf
 Author: Levente Hunyadi
 Author-email: hunyadi@gmail.com
 License: MIT
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
@@ -13,14 +13,15 @@
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Typing :: Typed
+Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # Publish Markdown files to Confluence wiki
 
 Contributors to software projects typically write documentation in Markdown format and host Markdown files in collaborative version control systems (VCS) such as GitHub or GitLab to track changes and facilitate the review process. However, not everyone at a company has access to VCS, and documents are often circulated in Confluence wiki instead.
```

### Comparing `markdown-to-confluence-0.1.5/md2conf/api.py` & `markdown-to-confluence-0.1.6/md2conf/api.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,12 +1,13 @@
 import json
 import logging
 import mimetypes
 import os
 import os.path
+import sys
 import typing
 from contextlib import contextmanager
 from dataclasses import dataclass
 from types import TracebackType
 from typing import Dict, Generator, List, Optional, Type, Union
 from urllib.parse import urlencode, urlparse, urlunparse
 
@@ -38,14 +39,32 @@
     if fragment:
         raise ValueError("expected: url with no fragment")
 
     url_parts = (scheme, netloc, path, None, urlencode(query) if query else None, None)
     return urlunparse(url_parts)
 
 
+if sys.version_info >= (3, 9):
+
+    def removeprefix(string: str, prefix: str) -> str:
+        "If the string starts with the prefix, return the string without the prefix; otherwise, return the original string."
+
+        return string.removeprefix(prefix)
+
+else:
+
+    def removeprefix(string: str, prefix: str) -> str:
+        "If the string starts with the prefix, return the string without the prefix; otherwise, return the original string."
+
+        if string.startswith(prefix):
+            return string[len(prefix) :]
+        else:
+            return string
+
+
 LOGGER = logging.getLogger(__name__)
 
 
 class ConfluenceError(RuntimeError):
     pass
 
 
@@ -196,15 +215,15 @@
         try:
             attachment = self.get_attachment_by_name(page_id, attachment_name)
 
             if attachment.file_size == os.path.getsize(attachment_path):
                 LOGGER.info("Up-to-date attachment: %s", attachment_name)
                 return
 
-            id = attachment.id.removeprefix("att")
+            id = removeprefix(attachment.id, "att")
             path = f"/content/{page_id}/child/attachment/{id}/data"
 
         except ConfluenceError:
             path = f"/content/{page_id}/child/attachment"
 
         url = self._build_url(path)
 
@@ -238,15 +257,15 @@
 
         # ensure path component is retained in attachment name
         self._update_attachment(page_id, attachment_id, version, attachment_name)
 
     def _update_attachment(
         self, page_id: str, attachment_id: str, version: int, attachment_title: str
     ) -> None:
-        id = attachment_id.removeprefix("att")
+        id = removeprefix(attachment_id, "att")
         path = f"/content/{page_id}/child/attachment/{id}"
         data = {
             "id": attachment_id,
             "type": "attachment",
             "status": "current",
             "title": attachment_title,
             "space": {"key": self.space_key},
@@ -309,16 +328,16 @@
         page = self.get_page(page_id)
 
         try:
             old_content = sanitize_confluence(page.content)
             if old_content == new_content:
                 LOGGER.info("Up-to-date page: %s", page_id)
                 return
-        except ParseError:
-            pass
+        except ParseError as exc:
+            LOGGER.warning(exc)
 
         path = f"/content/{page_id}"
         data = {
             "id": page_id,
             "type": "page",
             "title": page.title,
             "space": {"key": self.space_key},
```

### Comparing `markdown-to-confluence-0.1.5/md2conf/application.py` & `markdown-to-confluence-0.1.6/md2conf/application.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,28 +1,30 @@
 import os.path
 
 from .api import ConfluenceSession
-from .converter import ConfluenceDocument
+from .converter import ConfluenceDocument, ConfluenceDocumentOptions
 
 
 def update_document(
     api: ConfluenceSession, document: ConfluenceDocument, base_path: str
 ) -> None:
     for image in document.images:
         api.upload_attachment(
             document.page_id, os.path.join(base_path, image), image, ""
         )
 
     api.update_page(document.page_id, document.xhtml())
 
 
-def synchronize_page(api: ConfluenceSession, path: str) -> None:
+def synchronize_page(
+    api: ConfluenceSession, path: str, options: ConfluenceDocumentOptions
+) -> None:
     page_path = os.path.abspath(path)
     base_path = os.path.dirname(page_path)
 
-    document = ConfluenceDocument(path)
+    document = ConfluenceDocument(path, options)
 
     if document.space_key:
         with api.switch_space(document.space_key):
             update_document(api, document, base_path)
     else:
         update_document(api, document, base_path)
```

### Comparing `markdown-to-confluence-0.1.5/md2conf/converter.py` & `markdown-to-confluence-0.1.6/md2conf/converter.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,9 +1,10 @@
 import os.path
 import re
+from dataclasses import dataclass
 from typing import List, Optional, Tuple
 from urllib.parse import urlparse
 
 import lxml.etree as ET
 import markdown
 from lxml.builder import ElementMaker
 
@@ -225,23 +226,37 @@
         return ""
 
     string = re.sub(pattern, _repl_func, string, 1, re.ASCII)
     value = values[0] if values else None
     return value, string
 
 
+@dataclass
+class ConfluenceDocumentOptions:
+    """
+    Options that control the generated page content.
+
+    :param show_generated: Whether to display a prompt "This page has been generated with a tool."
+    """
+
+    generated_by: bool = True
+
+
 class ConfluenceDocument:
     page_id: str
     space_key: Optional[str] = None
     links: List[str]
     images: List[str]
 
+    options: ConfluenceDocumentOptions
     root: ET.Element
 
-    def __init__(self, path: str) -> None:
+    def __init__(self, path: str, options: ConfluenceDocumentOptions) -> None:
+        self.options = options
+
         path = os.path.abspath(path)
 
         with open(path, "r") as f:
             html = markdown_to_html(f.read())
 
         # extract Confluence page ID
         page_id, html = _extract_value(
@@ -255,35 +270,40 @@
 
         # extract Confluence space key
         self.space_key, html = _extract_value(
             r"<!--\s+confluence-space-key:\s*(\w+)\s+-->", html
         )
 
         # parse Markdown document
-        self.root = elements_from_strings(
-            [
+        if self.options.generated_by:
+            content = [
                 '<ac:structured-macro ac:name="info" ac:schema-version="1">',
                 "<ac:rich-text-body><p>This page has been generated with a tool.</p></ac:rich-text-body>",
                 "</ac:structured-macro>",
                 html,
             ]
-        )
+        else:
+            content = [html]
+        self.root = elements_from_strings(content)
 
         converter = ConfluenceStorageFormatConverter(os.path.dirname(path))
         converter.visit(self.root)
         self.links = converter.links
         self.images = converter.images
 
     def xhtml(self) -> str:
         return _content_to_string(self.root)
 
 
 def sanitize_confluence(html: str) -> str:
     "Generates a sanitized version of a Confluence storage format XHTML document with no volatile attributes."
 
+    if not html:
+        return ""
+
     root = elements_from_strings([html])
     ConfluenceStorageFormatCleaner().visit(root)
     return _content_to_string(root)
 
 
 def _content_to_string(root: ET.Element) -> str:
     xml = ET.tostring(root, encoding="utf8", method="xml").decode("utf8")
```

### Comparing `markdown-to-confluence-0.1.5/setup.cfg` & `markdown-to-confluence-0.1.6/setup.cfg`

 * *Files 14% similar despite different names*

```diff
@@ -21,14 +21,15 @@
 	Programming Language :: Python :: 3.11
 	Typing :: Typed
 
 [options]
 zip_safe = True
 include_package_data = True
 packages = find:
+python_requires = >=3.8
 install_requires = 
 	lxml >= 4.9
 	markdown >= 3.4
 	pymdown-extensions >= 9.11
 	requests >= 2.28
 	types-markdown >= 3.4
 	types-requests >= 2.28
```

### Comparing `markdown-to-confluence-0.1.5/tests/test_api.py` & `markdown-to-confluence-0.1.6/tests/test_api.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,25 +1,29 @@
 import logging
 import os
 import os.path
 import unittest
 
 from md2conf.api import ConfluenceAPI, ConfluenceAttachment, ConfluencePage
 from md2conf.application import synchronize_page
-from md2conf.converter import ConfluenceDocument, sanitize_confluence
+from md2conf.converter import (
+    ConfluenceDocument,
+    ConfluenceDocumentOptions,
+    sanitize_confluence,
+)
 
 logging.basicConfig(
     level=logging.INFO,
     format="%(asctime)s - %(levelname)s - %(funcName)s [%(lineno)d] - %(message)s",
 )
 
 
 class TestAPI(unittest.TestCase):
     def test_markdown(self) -> None:
-        document = ConfluenceDocument("example.md")
+        document = ConfluenceDocument("example.md", ConfluenceDocumentOptions())
         self.assertListEqual(document.links, [])
         self.assertListEqual(
             document.images,
             ["figure/interoperability.png", "figure/interoperability.png"],
         )
 
         with open(os.path.join("tests", "output", "document.html"), "w") as f:
@@ -58,12 +62,12 @@
                 os.path.join(os.getcwd(), "figure", "interoperability.png"),
                 "figure/interoperability.png",
                 "A sample figure",
             )
 
     def test_synchronize_page(self) -> None:
         with ConfluenceAPI() as api:
-            synchronize_page(api, "example.md")
+            synchronize_page(api, "example.md", ConfluenceDocumentOptions())
 
 
 if __name__ == "__main__":
     unittest.main()
```


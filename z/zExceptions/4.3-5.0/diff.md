# Comparing `tmp/zExceptions-4.3.tar.gz` & `tmp/zExceptions-5.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "zExceptions-4.3.tar", last modified: Sun Dec 18 14:08:42 2022, max compression
+gzip compressed data, was "zExceptions-5.0.tar", last modified: Wed Jun 28 06:04:48 2023, max compression
```

## Comparing `zExceptions-4.3.tar` & `zExceptions-5.0.tar`

### file list

```diff
@@ -1,32 +1,31 @@
-drwxr-xr-x   0 jens       (501) staff       (20)        0 2022-12-18 14:08:42.850122 zExceptions-4.3/
--rw-r--r--   0 jens       (501) staff       (20)     1961 2022-12-18 14:05:58.000000 zExceptions-4.3/CHANGES.rst
--rw-r--r--   0 jens       (501) staff       (20)      804 2022-12-18 12:50:39.000000 zExceptions-4.3/CONTRIBUTING.md
--rw-r--r--   0 jens       (501) staff       (20)       32 2021-11-02 08:53:08.000000 zExceptions-4.3/COPYRIGHT.txt
--rw-r--r--   0 jens       (501) staff       (20)     2070 2021-11-02 08:53:08.000000 zExceptions-4.3/LICENSE.txt
--rw-r--r--   0 jens       (501) staff       (20)      196 2022-12-18 12:50:39.000000 zExceptions-4.3/MANIFEST.in
--rw-r--r--   0 jens       (501) staff       (20)     3558 2022-12-18 14:08:42.850183 zExceptions-4.3/PKG-INFO
--rw-r--r--   0 jens       (501) staff       (20)      118 2021-11-02 08:53:08.000000 zExceptions-4.3/README.rst
--rw-r--r--   0 jens       (501) staff       (20)      301 2022-12-18 14:06:23.000000 zExceptions-4.3/buildout.cfg
--rw-r--r--   0 jens       (501) staff       (20)      417 2022-12-18 14:08:42.850430 zExceptions-4.3/setup.cfg
--rw-r--r--   0 jens       (501) staff       (20)     2601 2022-12-18 14:06:06.000000 zExceptions-4.3/setup.py
-drwxr-xr-x   0 jens       (501) staff       (20)        0 2022-12-18 14:08:42.845908 zExceptions-4.3/src/
-drwxr-xr-x   0 jens       (501) staff       (20)        0 2022-12-18 14:08:42.848440 zExceptions-4.3/src/zExceptions/
--rw-r--r--   0 jens       (501) staff       (20)     7831 2022-12-18 12:52:09.000000 zExceptions-4.3/src/zExceptions/ExceptionFormatter.py
--rw-r--r--   0 jens       (501) staff       (20)     2684 2022-12-18 12:52:09.000000 zExceptions-4.3/src/zExceptions/ITracebackSupplement.py
--rw-r--r--   0 jens       (501) staff       (20)     1399 2021-11-02 08:53:08.000000 zExceptions-4.3/src/zExceptions/TracebackSupplement.py
--rw-r--r--   0 jens       (501) staff       (20)    11787 2022-12-18 12:52:09.000000 zExceptions-4.3/src/zExceptions/__init__.py
--rw-r--r--   0 jens       (501) staff       (20)      411 2022-12-18 12:52:09.000000 zExceptions-4.3/src/zExceptions/_compat.py
-drwxr-xr-x   0 jens       (501) staff       (20)        0 2022-12-18 14:08:42.850026 zExceptions-4.3/src/zExceptions/tests/
--rw-r--r--   0 jens       (501) staff       (20)       36 2021-11-02 08:53:08.000000 zExceptions-4.3/src/zExceptions/tests/__init__.py
--rw-r--r--   0 jens       (501) staff       (20)     4099 2021-11-02 08:53:08.000000 zExceptions-4.3/src/zExceptions/tests/testExceptionFormatter.py
--rw-r--r--   0 jens       (501) staff       (20)     6867 2021-11-02 08:53:08.000000 zExceptions-4.3/src/zExceptions/tests/test___init__.py
--rw-r--r--   0 jens       (501) staff       (20)     4355 2022-12-18 12:52:09.000000 zExceptions-4.3/src/zExceptions/tests/test_unauthorized.py
--rw-r--r--   0 jens       (501) staff       (20)     3599 2022-12-18 12:52:09.000000 zExceptions-4.3/src/zExceptions/unauthorized.py
-drwxr-xr-x   0 jens       (501) staff       (20)        0 2022-12-18 14:08:42.849322 zExceptions-4.3/src/zExceptions.egg-info/
--rw-r--r--   0 jens       (501) staff       (20)     3558 2022-12-18 14:08:42.000000 zExceptions-4.3/src/zExceptions.egg-info/PKG-INFO
--rw-r--r--   0 jens       (501) staff       (20)      716 2022-12-18 14:08:42.000000 zExceptions-4.3/src/zExceptions.egg-info/SOURCES.txt
--rw-r--r--   0 jens       (501) staff       (20)        1 2022-12-18 14:08:42.000000 zExceptions-4.3/src/zExceptions.egg-info/dependency_links.txt
--rw-r--r--   0 jens       (501) staff       (20)        1 2022-12-18 12:50:45.000000 zExceptions-4.3/src/zExceptions.egg-info/not-zip-safe
--rw-r--r--   0 jens       (501) staff       (20)       55 2022-12-18 14:08:42.000000 zExceptions-4.3/src/zExceptions.egg-info/requires.txt
--rw-r--r--   0 jens       (501) staff       (20)       12 2022-12-18 14:08:42.000000 zExceptions-4.3/src/zExceptions.egg-info/top_level.txt
--rw-r--r--   0 jens       (501) staff       (20)     1528 2022-12-18 12:50:39.000000 zExceptions-4.3/tox.ini
+drwxr-xr-x   0 m.howitz   (502) staff       (20)        0 2023-06-28 06:04:48.068085 zExceptions-5.0/
+-rw-r--r--   0 m.howitz   (502) staff       (20)     2039 2023-06-28 06:04:47.000000 zExceptions-5.0/CHANGES.rst
+-rw-r--r--   0 m.howitz   (502) staff       (20)      804 2023-06-28 06:04:47.000000 zExceptions-5.0/CONTRIBUTING.md
+-rw-r--r--   0 m.howitz   (502) staff       (20)       32 2023-06-28 06:04:47.000000 zExceptions-5.0/COPYRIGHT.txt
+-rw-r--r--   0 m.howitz   (502) staff       (20)     2070 2023-06-28 06:04:47.000000 zExceptions-5.0/LICENSE.txt
+-rw-r--r--   0 m.howitz   (502) staff       (20)      196 2023-06-28 06:04:47.000000 zExceptions-5.0/MANIFEST.in
+-rw-r--r--   0 m.howitz   (502) staff       (20)     3332 2023-06-28 06:04:48.068294 zExceptions-5.0/PKG-INFO
+-rw-r--r--   0 m.howitz   (502) staff       (20)      118 2023-06-28 06:04:47.000000 zExceptions-5.0/README.rst
+-rw-r--r--   0 m.howitz   (502) staff       (20)      301 2023-06-28 06:04:47.000000 zExceptions-5.0/buildout.cfg
+-rw-r--r--   0 m.howitz   (502) staff       (20)      418 2023-06-28 06:04:48.069119 zExceptions-5.0/setup.cfg
+-rw-r--r--   0 m.howitz   (502) staff       (20)     2303 2023-06-28 06:04:47.000000 zExceptions-5.0/setup.py
+drwxr-xr-x   0 m.howitz   (502) staff       (20)        0 2023-06-28 06:04:48.044912 zExceptions-5.0/src/
+drwxr-xr-x   0 m.howitz   (502) staff       (20)        0 2023-06-28 06:04:48.058746 zExceptions-5.0/src/zExceptions/
+-rw-r--r--   0 m.howitz   (502) staff       (20)     7750 2023-06-28 06:04:47.000000 zExceptions-5.0/src/zExceptions/ExceptionFormatter.py
+-rw-r--r--   0 m.howitz   (502) staff       (20)     2684 2023-06-28 06:04:47.000000 zExceptions-5.0/src/zExceptions/ITracebackSupplement.py
+-rw-r--r--   0 m.howitz   (502) staff       (20)     1328 2023-06-28 06:04:47.000000 zExceptions-5.0/src/zExceptions/TracebackSupplement.py
+-rw-r--r--   0 m.howitz   (502) staff       (20)    11718 2023-06-28 06:04:47.000000 zExceptions-5.0/src/zExceptions/__init__.py
+drwxr-xr-x   0 m.howitz   (502) staff       (20)        0 2023-06-28 06:04:48.067385 zExceptions-5.0/src/zExceptions/tests/
+-rw-r--r--   0 m.howitz   (502) staff       (20)       36 2023-06-28 06:04:47.000000 zExceptions-5.0/src/zExceptions/tests/__init__.py
+-rw-r--r--   0 m.howitz   (502) staff       (20)     4091 2023-06-28 06:04:47.000000 zExceptions-5.0/src/zExceptions/tests/testExceptionFormatter.py
+-rw-r--r--   0 m.howitz   (502) staff       (20)     6867 2023-06-28 06:04:47.000000 zExceptions-5.0/src/zExceptions/tests/test___init__.py
+-rw-r--r--   0 m.howitz   (502) staff       (20)     4264 2023-06-28 06:04:47.000000 zExceptions-5.0/src/zExceptions/tests/test_unauthorized.py
+-rw-r--r--   0 m.howitz   (502) staff       (20)     3352 2023-06-28 06:04:47.000000 zExceptions-5.0/src/zExceptions/unauthorized.py
+drwxr-xr-x   0 m.howitz   (502) staff       (20)        0 2023-06-28 06:04:48.063909 zExceptions-5.0/src/zExceptions.egg-info/
+-rw-r--r--   0 m.howitz   (502) staff       (20)     3332 2023-06-28 06:04:48.000000 zExceptions-5.0/src/zExceptions.egg-info/PKG-INFO
+-rw-r--r--   0 m.howitz   (502) staff       (20)      689 2023-06-28 06:04:48.000000 zExceptions-5.0/src/zExceptions.egg-info/SOURCES.txt
+-rw-r--r--   0 m.howitz   (502) staff       (20)        1 2023-06-28 06:04:48.000000 zExceptions-5.0/src/zExceptions.egg-info/dependency_links.txt
+-rw-r--r--   0 m.howitz   (502) staff       (20)        1 2023-06-28 06:04:48.000000 zExceptions-5.0/src/zExceptions.egg-info/not-zip-safe
+-rw-r--r--   0 m.howitz   (502) staff       (20)       55 2023-06-28 06:04:48.000000 zExceptions-5.0/src/zExceptions.egg-info/requires.txt
+-rw-r--r--   0 m.howitz   (502) staff       (20)       12 2023-06-28 06:04:48.000000 zExceptions-5.0/src/zExceptions.egg-info/top_level.txt
+-rw-r--r--   0 m.howitz   (502) staff       (20)     1430 2023-06-28 06:04:47.000000 zExceptions-5.0/tox.ini
```

### Comparing `zExceptions-4.3/CHANGES.rst` & `zExceptions-5.0/CHANGES.rst`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,16 @@
 Changelog
 =========
 
+5.0 (2023-06-28)
+----------------
+
+
+- Drop support for Python 2.7, 3.5, 3.6.
+
 4.3 (2022-12-18)
 ----------------
 
 - Sort imports with isort.
 
 - Add support for Python 3.11.
```

### Comparing `zExceptions-4.3/CONTRIBUTING.md` & `zExceptions-5.0/CONTRIBUTING.md`

 * *Files identical despite different names*

### Comparing `zExceptions-4.3/LICENSE.txt` & `zExceptions-5.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `zExceptions-4.3/PKG-INFO` & `zExceptions-5.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,49 +1,49 @@
 Metadata-Version: 2.1
 Name: zExceptions
-Version: 4.3
+Version: 5.0
 Summary: zExceptions contains common exceptions used in Zope.
 Home-page: https://github.com/zopefoundation/zExceptions
 Author: Zope Foundation and Contributors
-Author-email: zope-dev@zope.org
+Author-email: zope-dev@zope.dev
 License: ZPL 2.1
 Project-URL: Issue Tracker, https://github.com/zopefoundation/zExceptions/issues
 Project-URL: Sources, https://github.com/zopefoundation/zExceptions
 Classifier: Development Status :: 6 - Mature
 Classifier: Environment :: Web Environment
-Classifier: Framework :: Zope2
-Classifier: Framework :: Zope :: 2
-Classifier: Framework :: Zope :: 4
+Classifier: Framework :: Zope :: 5
 Classifier: License :: OSI Approved :: Zope Public License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 2
-Classifier: Programming Language :: Python :: 2.7
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.5
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
-Requires-Python: >=2.7,!=3.0.*,!=3.1.*,!=3.2.*,!=3.3.*,!=3.4.*
+Requires-Python: >=3.7
 License-File: LICENSE.txt
 
 Overview
 ========
 
 zExceptions contains common exceptions and helper functions related to
 exceptions as used in Zope.
 
 Changelog
 =========
 
+5.0 (2023-06-28)
+----------------
+
+
+- Drop support for Python 2.7, 3.5, 3.6.
+
 4.3 (2022-12-18)
 ----------------
 
 - Sort imports with isort.
 
 - Add support for Python 3.11.
```

### Comparing `zExceptions-4.3/setup.py` & `zExceptions-5.0/setup.py`

 * *Files 24% similar despite different names*

```diff
@@ -14,51 +14,45 @@
 
 from setuptools import find_packages
 from setuptools import setup
 
 
 setup(
     name='zExceptions',
-    version='4.3',
+    version='5.0',
     url='https://github.com/zopefoundation/zExceptions',
     license='ZPL 2.1',
     description="zExceptions contains common exceptions used in Zope.",
     author='Zope Foundation and Contributors',
-    author_email='zope-dev@zope.org',
+    author_email='zope-dev@zope.dev',
     project_urls={
         'Issue Tracker': 'https://github.com/zopefoundation/'
                          'zExceptions/issues',
         'Sources': 'https://github.com/zopefoundation/zExceptions',
     },
 
     long_description=(open('README.rst').read() + '\n' +
                       open('CHANGES.rst').read()),
     packages=find_packages('src'),
     package_dir={'': 'src'},
-    python_requires='>=2.7,!=3.0.*,!=3.1.*,!=3.2.*,!=3.3.*,!=3.4.*',
+    python_requires='>=3.7',
     install_requires=[
         'setuptools',
         'zope.interface',
         'zope.publisher',
         'zope.security',
     ],
     classifiers=[
         "Development Status :: 6 - Mature",
         "Environment :: Web Environment",
-        "Framework :: Zope2",
-        "Framework :: Zope :: 2",
-        "Framework :: Zope :: 4",
+        "Framework :: Zope :: 5",
         "License :: OSI Approved :: Zope Public License",
         "Operating System :: OS Independent",
         "Programming Language :: Python",
-        "Programming Language :: Python :: 2",
-        "Programming Language :: Python :: 2.7",
         "Programming Language :: Python :: 3",
-        "Programming Language :: Python :: 3.5",
-        "Programming Language :: Python :: 3.6",
         "Programming Language :: Python :: 3.7",
         "Programming Language :: Python :: 3.8",
         "Programming Language :: Python :: 3.9",
         "Programming Language :: Python :: 3.10",
         "Programming Language :: Python :: 3.11",
         "Programming Language :: Python :: Implementation :: CPython",
         "Programming Language :: Python :: Implementation :: PyPy",
```

### Comparing `zExceptions-4.3/src/zExceptions/ExceptionFormatter.py` & `zExceptions-5.0/src/zExceptions/ExceptionFormatter.py`

 * *Files 2% similar despite different names*

```diff
@@ -12,25 +12,21 @@
 #
 ##############################################################################
 """An exception formatter that shows traceback supplements and traceback info,
 optionally in HTML.
 """
 
 import sys
+from html import escape as html_escape
 
 
-try:
-    from html import escape as html_escape
-except ImportError:  # PY2
-    from cgi import escape as html_escape
-
 DEBUG_EXCEPTION_FORMATTER = 1
 
 
-class TextExceptionFormatter(object):
+class TextExceptionFormatter:
 
     line_sep = '\n'
     show_revisions = 0
 
     def __init__(self, limit=None):
         self.limit = limit
 
@@ -84,15 +80,15 @@
 
         line = getattr(supplement, 'line', 0)
         if line == -1:
             line = tb.tb_lineno
         col = getattr(supplement, 'column', -1)
         if line:
             if col is not None and col >= 0:
-                result.append(fmtLine('Line %s, Column %s' % (
+                result.append(fmtLine('Line {}, Column {}'.format(
                     line, col)))
             else:
                 result.append(fmtLine('Line %s' % line))
         elif col is not None and col >= 0:
             result.append(fmtLine('Column %s' % col))
 
         expr = getattr(supplement, 'expression', None)
@@ -114,15 +110,15 @@
         if getInfo is not None:
             extra = getInfo()
             if extra:
                 return extra
         return None
 
     def formatTracebackInfo(self, tbi):
-        return self.formatSupplementLine('__traceback_info__: %s' % (tbi, ))
+        return self.formatSupplementLine('__traceback_info__: {}'.format(tbi))
 
     def formatLine(self, tb):
         f = tb.tb_frame
         lineno = tb.tb_lineno
         co = f.f_code
         filename = co.co_filename
         name = co.co_name
```

### Comparing `zExceptions-4.3/src/zExceptions/ITracebackSupplement.py` & `zExceptions-5.0/src/zExceptions/ITracebackSupplement.py`

 * *Files identical despite different names*

### Comparing `zExceptions-4.3/src/zExceptions/TracebackSupplement.py` & `zExceptions-5.0/src/zExceptions/TracebackSupplement.py`

 * *Files 24% similar despite different names*

```diff
@@ -9,21 +9,18 @@
 # WARRANTIES ARE DISCLAIMED, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
 # WARRANTIES OF TITLE, MERCHANTABILITY, AGAINST INFRINGEMENT, AND FITNESS
 # FOR A PARTICULAR PURPOSE.
 #
 ##############################################################################
 # Stock __traceback_supplement__ implementations
 
-try:
-    from html import escape
-except ImportError:  # PY2
-    from cgi import escape
+from html import escape
 
 
-class PathTracebackSupplement(object):
+class PathTracebackSupplement:
     """Implementation of ITracebackSupplement"""
     pp = None
 
     def __init__(self, object):
         self.object = object
         if hasattr(object, 'getPhysicalPath'):
             self.pp = '/'.join(object.getPhysicalPath())
```

### Comparing `zExceptions-4.3/src/zExceptions/__init__.py` & `zExceptions-5.0/src/zExceptions/__init__.py`

 * *Files 1% similar despite different names*

```diff
@@ -11,26 +11,25 @@
 #
 ##############################################################################
 """General exceptions that wish they were standard exceptions
 
 These exceptions are so general purpose that they don't belong in Zope
 application-specific packages.
 """
+import builtins
+
 from zope.interface import implementer
 from zope.interface.common.interfaces import IException
 from zope.publisher.interfaces import IBadRequest
 from zope.publisher.interfaces import INotFound
 from zope.publisher.interfaces import IRedirect
 from zope.publisher.interfaces.http import IHTTPException
 from zope.publisher.interfaces.http import IMethodNotAllowed
 from zope.security.interfaces import IForbidden
 
-from ._compat import builtins
-from ._compat import class_types
-
 
 status_reasons = {
     # Informational
     100: 'Continue',
     101: 'Switching Protocols',
     102: 'Processing',
 
@@ -235,15 +234,15 @@
     """Base class for 3xx status codes."""
 
 
 class _HTTPMove(HTTPRedirection):
     """Base class for redirections requiring a location header."""
 
     def __init__(self, *args):
-        super(_HTTPMove, self).__init__(*args)
+        super().__init__(*args)
         self.setHeader('Location', args[0])
 
 
 class HTTPMultipleChoices(_HTTPMove):
     errmsg = 'Multiple Choices'
     status = 300
 
@@ -512,15 +511,15 @@
     import zExceptions
     etype = None
     if name in builtins.__dict__:
         etype = getattr(builtins, name)
     elif hasattr(zExceptions, name):
         etype = getattr(zExceptions, name)
     if (etype is not None and
-            isinstance(etype, class_types) and
+            isinstance(etype, type) and
             issubclass(etype, Exception)):
         return etype
 
 
 def upgradeException(t, v):
     etype = convertExceptionType(t.__name__)
     if etype is not None:
```

### Comparing `zExceptions-4.3/src/zExceptions/tests/testExceptionFormatter.py` & `zExceptions-5.0/src/zExceptions/tests/testExceptionFormatter.py`

 * *Files 0% similar despite different names*

```diff
@@ -30,15 +30,15 @@
         del b
 
 
 class ExceptionForTesting(HTTPException):
     pass
 
 
-class TestingTracebackSupplement(object):
+class TestingTracebackSupplement:
 
     source_url = '/somepath'
     line = 634
     column = 57
     warnings = ['Repent, for the end is nigh']
 
     def __init__(self, expression):
```

### Comparing `zExceptions-4.3/src/zExceptions/tests/test___init__.py` & `zExceptions-5.0/src/zExceptions/tests/test___init__.py`

 * *Files identical despite different names*

### Comparing `zExceptions-4.3/src/zExceptions/tests/test_unauthorized.py` & `zExceptions-5.0/src/zExceptions/tests/test_unauthorized.py`

 * *Files 6% similar despite different names*

```diff
@@ -14,16 +14,14 @@
 """Unit tests for unauthorized module.
 """
 
 import unittest
 
 from zope.interface.verify import verifyClass
 
-from .._compat import unicode
-
 
 class UnauthorizedTests(unittest.TestCase):
 
     def _getTargetClass(self):
         from zExceptions.unauthorized import Unauthorized
         return Unauthorized
 
@@ -40,96 +38,96 @@
 
         self.assertEqual(exc.name, None)
         self.assertEqual(exc.message, None)
         self.assertEqual(exc.value, None)
         self.assertEqual(exc.needed, None)
 
         self.assertEqual(bytes(exc), b'Unauthorized()')
-        self.assertEqual(unicode(exc), u'Unauthorized()')
+        self.assertEqual(str(exc), 'Unauthorized()')
 
     def test_ascii_message(self):
         arg = b'ERROR MESSAGE'
         exc = self._makeOne(arg)
 
         self.assertEqual(exc.name, None)
         self.assertEqual(exc.message, arg)
         self.assertEqual(exc.value, None)
         self.assertEqual(exc.needed, None)
 
         self.assertEqual(bytes(exc), arg)
-        self.assertEqual(unicode(exc), arg.decode('ascii'))
+        self.assertEqual(str(exc), arg.decode('ascii'))
 
     def test_encoded_message(self):
-        arg = u'ERROR MESSAGE \u03A9'.encode('utf-8')
+        arg = 'ERROR MESSAGE \u03A9'.encode()
         exc = self._makeOne(arg)
 
         self.assertEqual(exc.name, None)
         self.assertEqual(exc.message, arg)
         self.assertEqual(exc.value, None)
         self.assertEqual(exc.needed, None)
 
         self.assertEqual(bytes(exc), arg)
-        self.assertEqual(unicode(exc), arg.decode('utf-8'))
+        self.assertEqual(str(exc), arg.decode('utf-8'))
 
-    def test_unicode_message(self):
-        arg = u'ERROR MESSAGE \u03A9'
+    def test_str_message(self):
+        arg = 'ERROR MESSAGE \u03A9'
         exc = self._makeOne(arg)
 
         self.assertEqual(exc.name, None)
         self.assertEqual(exc.message, arg)
         self.assertEqual(exc.value, None)
         self.assertEqual(exc.needed, None)
 
         self.assertEqual(bytes(exc), arg.encode('utf-8'))
-        self.assertEqual(unicode(exc), arg)
+        self.assertEqual(str(exc), arg)
 
     def test_ascii_name(self):
         arg = b'ERROR_NAME'
         exc = self._makeOne(arg)
 
         self.assertEqual(exc.name, arg)
         self.assertEqual(exc.message, None)
         self.assertEqual(exc.value, None)
         self.assertEqual(exc.needed, None)
 
         self.assertEqual(
             bytes(exc),
             b"You are not allowed to access 'ERROR_NAME' in this context")
         self.assertEqual(
-            unicode(exc),
-            u"You are not allowed to access 'ERROR_NAME' in this context")
+            str(exc),
+            "You are not allowed to access 'ERROR_NAME' in this context")
 
     def test_encoded_name(self):
-        arg = u'ERROR_NAME_\u03A9'.encode('utf-8')
+        arg = 'ERROR_NAME_\u03A9'.encode()
         exc = self._makeOne(arg)
 
         self.assertEqual(exc.name, arg)
         self.assertEqual(exc.message, None)
         self.assertEqual(exc.value, None)
         self.assertEqual(exc.needed, None)
 
         self.assertEqual(
             bytes(exc),
             (b"You are not allowed to access "
              b"'ERROR_NAME_\xce\xa9' in this context"))
         self.assertEqual(
-            unicode(exc),
-            u"You are not allowed to access "
-            u"'ERROR_NAME_\u03A9' in this context")
+            str(exc),
+            "You are not allowed to access "
+            "'ERROR_NAME_\u03A9' in this context")
 
-    def test_unicode_name(self):
-        arg = u'ERROR_NAME_\u03A9'
+    def test_str_name(self):
+        arg = 'ERROR_NAME_\u03A9'
         exc = self._makeOne(arg)
 
         self.assertEqual(exc.name, arg)
         self.assertEqual(exc.message, None)
         self.assertEqual(exc.value, None)
         self.assertEqual(exc.needed, None)
 
         self.assertEqual(
             bytes(exc),
             (b"You are not allowed to access "
              b"'ERROR_NAME_\xce\xa9' in this context"))
         self.assertEqual(
-            unicode(exc),
-            u"You are not allowed to access "
-            u"'ERROR_NAME_\u03A9' in this context")
+            str(exc),
+            "You are not allowed to access "
+            "'ERROR_NAME_\u03A9' in this context")
```

### Comparing `zExceptions-4.3/src/zExceptions/unauthorized.py` & `zExceptions-5.0/src/zExceptions/unauthorized.py`

 * *Files 6% similar despite different names*

```diff
@@ -12,18 +12,14 @@
 ##############################################################################
 
 from zope.interface import implementer
 from zope.security.interfaces import IUnauthorized
 
 from zExceptions import HTTPClientError
 
-from ._compat import PY3
-from ._compat import string_types
-from ._compat import unicode
-
 
 @implementer(IUnauthorized)
 class Unauthorized(HTTPClientError):
     """Some user wasn't allowed to access a resource
     """
     errmsg = 'Unauthorized'
     realm = None
@@ -47,15 +43,15 @@
         Unauthorized(message, value, needed, name, realm)
 
         Where needed is a mapping objects with items representing requirements
         (e.g. {'permission': 'add spam'}). Any extra keyword arguments
         provides are added to needed.
         """
         if (name is None and (
-                not isinstance(message, string_types) or
+                not isinstance(message, (str, bytes)) or
                 len(message.split()) <= 1)):
             # First arg is a name, not a message
             name = message
             message = None
 
         self.name = name
         self._message = message
@@ -66,39 +62,33 @@
             if needed:
                 needed.update(kw)
             else:
                 needed = kw
 
         self.needed = needed
 
-    def __unicode__(self):
+    def __str__(self):
         if self.message is not None:
             message = (self.message if
-                       isinstance(self.message, unicode) else
+                       isinstance(self.message, str) else
                        self.message.decode('utf-8'))
             return message
         if self.name is not None:
             name = (self.name if
-                    isinstance(self.name, unicode) else
+                    isinstance(self.name, str) else
                     self.name.decode('utf-8'))
             return ("You are not allowed to access '%s' in this context"
                     % name)
         elif self.value is not None:
             return ("You are not allowed to access '%s' in this context"
                     % self.getValueName())
         return repr(self)
 
-    if PY3:
-        __str__ = __unicode__
-
-        def __bytes__(self):
-            return self.__unicode__().encode('utf-8')
-    else:
-        def __str__(self):
-            return self.__unicode__().encode('utf-8')
+    def __bytes__(self):
+        return self.__str__().encode('utf-8')
 
     def setRealm(self, value):
         self.realm = value
         if value:
             self.setHeader('WWW-Authenticate', 'basic realm="%s"' % value)
 
     def getValueName(self):
```

### Comparing `zExceptions-4.3/src/zExceptions.egg-info/PKG-INFO` & `zExceptions-5.0/src/zExceptions.egg-info/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,49 +1,49 @@
 Metadata-Version: 2.1
 Name: zExceptions
-Version: 4.3
+Version: 5.0
 Summary: zExceptions contains common exceptions used in Zope.
 Home-page: https://github.com/zopefoundation/zExceptions
 Author: Zope Foundation and Contributors
-Author-email: zope-dev@zope.org
+Author-email: zope-dev@zope.dev
 License: ZPL 2.1
 Project-URL: Issue Tracker, https://github.com/zopefoundation/zExceptions/issues
 Project-URL: Sources, https://github.com/zopefoundation/zExceptions
 Classifier: Development Status :: 6 - Mature
 Classifier: Environment :: Web Environment
-Classifier: Framework :: Zope2
-Classifier: Framework :: Zope :: 2
-Classifier: Framework :: Zope :: 4
+Classifier: Framework :: Zope :: 5
 Classifier: License :: OSI Approved :: Zope Public License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python
-Classifier: Programming Language :: Python :: 2
-Classifier: Programming Language :: Python :: 2.7
 Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3.5
-Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
-Requires-Python: >=2.7,!=3.0.*,!=3.1.*,!=3.2.*,!=3.3.*,!=3.4.*
+Requires-Python: >=3.7
 License-File: LICENSE.txt
 
 Overview
 ========
 
 zExceptions contains common exceptions and helper functions related to
 exceptions as used in Zope.
 
 Changelog
 =========
 
+5.0 (2023-06-28)
+----------------
+
+
+- Drop support for Python 2.7, 3.5, 3.6.
+
 4.3 (2022-12-18)
 ----------------
 
 - Sort imports with isort.
 
 - Add support for Python 3.11.
```

### Comparing `zExceptions-4.3/src/zExceptions.egg-info/SOURCES.txt` & `zExceptions-5.0/src/zExceptions.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -8,15 +8,14 @@
 setup.cfg
 setup.py
 tox.ini
 src/zExceptions/ExceptionFormatter.py
 src/zExceptions/ITracebackSupplement.py
 src/zExceptions/TracebackSupplement.py
 src/zExceptions/__init__.py
-src/zExceptions/_compat.py
 src/zExceptions/unauthorized.py
 src/zExceptions.egg-info/PKG-INFO
 src/zExceptions.egg-info/SOURCES.txt
 src/zExceptions.egg-info/dependency_links.txt
 src/zExceptions.egg-info/not-zip-safe
 src/zExceptions.egg-info/requires.txt
 src/zExceptions.egg-info/top_level.txt
```


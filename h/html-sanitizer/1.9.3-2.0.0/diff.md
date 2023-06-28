# Comparing `tmp/html_sanitizer-1.9.3.tar.gz` & `tmp/html_sanitizer-2.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "html_sanitizer-1.9.3.tar", last modified: Sat Jan 15 16:13:33 2022, max compression
+gzip compressed data, last modified: Sun Feb  2 00:00:00 2020, max compression
```

## Comparing `html_sanitizer-1.9.3.tar` & `html_sanitizer-2.0.0.tar`

### file list

```diff
@@ -1,19 +1,15 @@
-drwxrwxr-x   0 matthias  (1000) matthias  (1000)        0 2022-01-15 16:13:33.757442 html_sanitizer-1.9.3/
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     1553 2020-01-20 08:19:45.000000 html_sanitizer-1.9.3/LICENSE
--rw-rw-r--   0 matthias  (1000) matthias  (1000)       55 2020-01-20 08:19:45.000000 html_sanitizer-1.9.3/MANIFEST.in
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     7541 2022-01-15 16:13:33.757442 html_sanitizer-1.9.3/PKG-INFO
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     6795 2021-04-27 06:41:48.000000 html_sanitizer-1.9.3/README.rst
-drwxrwxr-x   0 matthias  (1000) matthias  (1000)        0 2022-01-15 16:13:33.757442 html_sanitizer-1.9.3/html_sanitizer/
--rw-rw-r--   0 matthias  (1000) matthias  (1000)      155 2022-01-15 16:12:54.000000 html_sanitizer-1.9.3/html_sanitizer/__init__.py
--rw-rw-r--   0 matthias  (1000) matthias  (1000)      293 2021-04-27 06:41:48.000000 html_sanitizer-1.9.3/html_sanitizer/__main__.py
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     1144 2021-04-27 06:41:48.000000 html_sanitizer-1.9.3/html_sanitizer/django.py
--rw-rw-r--   0 matthias  (1000) matthias  (1000)    13360 2021-04-27 06:41:48.000000 html_sanitizer-1.9.3/html_sanitizer/sanitizer.py
--rw-rw-r--   0 matthias  (1000) matthias  (1000)    21677 2022-01-15 16:11:15.000000 html_sanitizer-1.9.3/html_sanitizer/tests.py
-drwxrwxr-x   0 matthias  (1000) matthias  (1000)        0 2022-01-15 16:13:33.757442 html_sanitizer-1.9.3/html_sanitizer.egg-info/
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     7541 2022-01-15 16:13:33.000000 html_sanitizer-1.9.3/html_sanitizer.egg-info/PKG-INFO
--rw-rw-r--   0 matthias  (1000) matthias  (1000)      369 2022-01-15 16:13:33.000000 html_sanitizer-1.9.3/html_sanitizer.egg-info/SOURCES.txt
--rw-rw-r--   0 matthias  (1000) matthias  (1000)        1 2022-01-15 16:13:33.000000 html_sanitizer-1.9.3/html_sanitizer.egg-info/dependency_links.txt
--rw-rw-r--   0 matthias  (1000) matthias  (1000)       27 2022-01-15 16:13:33.000000 html_sanitizer-1.9.3/html_sanitizer.egg-info/requires.txt
--rw-rw-r--   0 matthias  (1000) matthias  (1000)       15 2022-01-15 16:13:33.000000 html_sanitizer-1.9.3/html_sanitizer.egg-info/top_level.txt
--rw-rw-r--   0 matthias  (1000) matthias  (1000)     1111 2022-01-15 16:13:33.757442 html_sanitizer-1.9.3/setup.cfg
--rwxrwxr-x   0 matthias  (1000) matthias  (1000)       62 2021-04-27 06:47:38.000000 html_sanitizer-1.9.3/setup.py
+-rw-r--r--   0        0        0      200 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/.editorconfig
+-rw-r--r--   0        0        0     1221 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/.pre-commit-config.yaml
+-rw-r--r--   0        0        0     5310 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/CHANGELOG.rst
+-rw-r--r--   0        0        0      187 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/tox.ini
+-rw-r--r--   0        0        0      726 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/.github/workflows/test.yml
+-rw-r--r--   0        0        0      126 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/html_sanitizer/__init__.py
+-rw-r--r--   0        0        0      280 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/html_sanitizer/__main__.py
+-rw-r--r--   0        0        0     1146 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/html_sanitizer/django.py
+-rw-r--r--   0        0        0    13144 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/html_sanitizer/sanitizer.py
+-rw-r--r--   0        0        0    23444 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/html_sanitizer/tests.py
+-rw-r--r--   0        0        0       97 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/.gitignore
+-rw-r--r--   0        0        0     1553 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/LICENSE
+-rw-r--r--   0        0        0     6795 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/README.rst
+-rw-r--r--   0        0        0     2087 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/pyproject.toml
+-rw-r--r--   0        0        0     7835 2020-02-02 00:00:00.000000 html_sanitizer-2.0.0/PKG-INFO
```

### Comparing `html_sanitizer-1.9.3/LICENSE` & `html_sanitizer-2.0.0/LICENSE`

 * *Files identical despite different names*

### Comparing `html_sanitizer-1.9.3/PKG-INFO` & `html_sanitizer-2.0.0/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,28 +1,33 @@
 Metadata-Version: 2.1
-Name: html_sanitizer
-Version: 1.9.3
+Name: html-sanitizer
+Version: 2.0.0
 Summary: HTML sanitizer
-Home-page: https://github.com/matthiask/html-sanitizer/
-Author: Matthias Kestenholz
-Author-email: mk@feinheit.ch
+Project-URL: Homepage, https://github.com/matthiask/html-sanitizer/
+Author-email: Matthias Kestenholz <mk@feinheit.ch>
 License: BSD-3-Clause
-Platform: OS Independent
+License-File: LICENSE
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Web Environment
 Classifier: Framework :: Django
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: BSD License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python
+Classifier: Programming Language :: Python :: 3 :: Only
+Classifier: Programming Language :: Python :: 3.8
+Classifier: Programming Language :: Python :: 3.9
+Classifier: Programming Language :: Python :: 3.10
+Classifier: Programming Language :: Python :: 3.11
 Classifier: Topic :: Internet :: WWW/HTTP :: Dynamic Content
 Classifier: Topic :: Software Development
-Requires-Python: >=3.6
+Requires-Python: >=3.8
+Requires-Dist: beautifulsoup4
+Requires-Dist: lxml>=4.9.1
 Description-Content-Type: text/x-rst
-License-File: LICENSE
 
 ==============
 HTML sanitizer
 ==============
 
 This is a allowlist-based and very opinionated HTML sanitizer that
 can be used both for untrusted and trusted sources. It attempts to clean
@@ -189,9 +194,7 @@
 .. _Django: https://www.djangoproject.com/
 .. _django-content-editor: http://django-content-editor.readthedocs.io/
 .. _FeinCMS: https://pypi.python.org/pypi/FeinCMS
 .. _feincms-cleanse: https://pypi.python.org/pypi/feincms-cleanse
 .. _design decisions: http://django-content-editor.readthedocs.io/en/latest/#design-decisions
 .. _lxml: http://lxml.de/
 .. _autolinker: http://lxml.de/api/lxml.html.clean-module.html
-
-
```

### Comparing `html_sanitizer-1.9.3/README.rst` & `html_sanitizer-2.0.0/README.rst`

 * *Files identical despite different names*

### Comparing `html_sanitizer-1.9.3/html_sanitizer/django.py` & `html_sanitizer-2.0.0/html_sanitizer/django.py`

 * *Files 13% similar despite different names*

```diff
@@ -10,16 +10,16 @@
 def _get_sanitizer(name="default"):
     sanitizers = getattr(settings, "HTML_SANITIZERS", {})
     if name in sanitizers:
         return Sanitizer(sanitizers[name])
     elif name == "default":
         return Sanitizer()
     raise ImproperlyConfigured(
-        "Unknown sanitizer %r, did you define HTML_SANITIZERS[%r] in your"
-        " Django settings module?" % (name, name)
+        "Unknown sanitizer {!r}, did you define HTML_SANITIZERS[{!r}] in your"
+        " Django settings module?".format(name, name)
     )
 
 
 get_sanitizer = lru_cache(maxsize=None)(_get_sanitizer)
 
 
 @checks.register()
@@ -28,13 +28,13 @@
     sanitizers = ["default"] + list(getattr(settings, "HTML_SANITIZERS", {}))
     for name in sorted(set(sanitizers)):
         try:
             _get_sanitizer(name)
         except TypeError as exc:
             errors.append(
                 checks.Error(
-                    "Invalid sanitizer configuration '%s': %s" % (name, exc),
+                    f"Invalid sanitizer configuration '{name}': {exc}",
                     id="html_sanitizer.E001",
                 )
             )
 
     return errors
```

### Comparing `html_sanitizer-1.9.3/html_sanitizer/sanitizer.py` & `html_sanitizer-2.0.0/html_sanitizer/sanitizer.py`

 * *Files 3% similar despite different names*

```diff
@@ -41,25 +41,34 @@
 
 typographic_whitespace = "".join(
     {unicodedata.lookup(n) for n in typographic_whitespace_names}
 )
 
 
 def normalize_overall_whitespace(
-    html, keep_typographic_whitespace=False, whitespace_re=None
+    html, *, keep_typographic_whitespace=False, whitespace_re=None
 ):
-    # remove all sorts of newline and nbsp characters
-    whitespace = ["\n", "&#10;", "&#xa;", "\r", "&#13;", "&#xd;"]
-    if not keep_typographic_whitespace:
-        # non-breaking space representations
-        whitespace += ["\xa0", "&nbsp;", "&#160;", "&#xa0;"]
-    if whitespace_re is None:
-        whitespace_re = r"\s+"
+    if keep_typographic_whitespace:
+        return html
+    whitespace = [
+        "\xa0",
+        "&nbsp;",
+        "&#160;",
+        "&#xa0;",
+        "\n",
+        "&#10;",
+        "&#xa;",
+        "\r",
+        "&#13;",
+        "&#xd;",
+    ]
     for ch in whitespace:
         html = html.replace(ch, " ")
+    if whitespace_re is None:
+        whitespace_re = r"\s+"
     html = re.sub(whitespace_re, " ", html)
     return html
 
 
 def bold_span_to_strong(element):
     if element.tag == "span" and "bold" in element.get("style", ""):
         element.tag = "strong"
@@ -160,62 +169,54 @@
         target_blank_noopener,
         anchor_id_to_name,
     ],
     "element_postprocessors": [],
 }
 
 
-class Sanitizer(object):
+class Sanitizer:
     def __init__(self, settings=None):
         self.__dict__.update(DEFAULT_SETTINGS)
         self.__dict__.update(settings or {})
 
         # Allow iterables of any kind, not just sets.
         self.tags = set(self.tags)
         self.empty = set(self.empty)
         self.separate = set(self.separate)
         self.whitespace = set(self.whitespace)
 
         if self.keep_typographic_whitespace:
             re_whitespace = r"[^\S%s]" % typographic_whitespace
         else:
             re_whitespace = r"\s"
-        import sys
 
-        if int(sys.version.split(".")[0]) == 2:
-            force_unicode_prefix = "(?u)"
-        else:
-            force_unicode_prefix = ""
-        self.only_whitespace_re = re.compile(
-            r"%s^%s*$" % (force_unicode_prefix, re_whitespace)
-        )
-        self.whitespace_re = re.compile(
-            r"%s%s+" % (force_unicode_prefix, re_whitespace)
-        )
+        self.only_whitespace_re = re.compile(rf"^{re_whitespace}*$")
+        self.whitespace_re = re.compile(rf"{re_whitespace}+")
 
         # Validate the settings.
         if not self.tags:
             raise TypeError(
                 "Empty list of allowed tags is not supported by the underlying"
                 " lxml cleaner. If you really do not want to pass any tags"
                 " pass a made-up tag name which will never exist in your"
                 " document."
             )
         if not self.tags.issuperset(self.empty):
             raise TypeError(
-                'Tags in "empty", but not allowed: %r' % (self.empty - self.tags,)
+                f'Tags in "empty", but not allowed: {self.empty - self.tags!r}'
             )
         if not self.tags.issuperset(self.separate):
             raise TypeError(
-                'Tags in "separate", but not allowed: %r' % (self.separate - self.tags,)
+                'Tags in "separate", but not allowed: {!r}'.format(
+                    self.separate - self.tags
+                )
             )
         if not self.tags.issuperset(self.attributes.keys()):
             raise TypeError(
-                'Tags in "attributes", but not allowed: %r'
-                % (set(self.attributes.keys()) - self.tags,)
+                f'Tags in "attributes", but not allowed: {set(self.attributes.keys()) - self.tags!r}'
             )
 
         anchor_attributes = self.attributes.get("a", ())
         if "target" in anchor_attributes and "rel" not in anchor_attributes:
             raise TypeError(
                 'Always allow "rel" when allowing "target" as anchor' " attribute"
             )
@@ -343,20 +344,20 @@
                     and nx.tag == element.tag
                     and self.is_mergeable(element, nx)
                 ):
                     # Yes, we should. Tail is empty, that is, no text between
                     # tags of a mergeable type.
                     if nx.text:
                         if len(element):
-                            list(element)[-1].tail = "%s %s" % (
+                            list(element)[-1].tail = "{} {}".format(
                                 list(element)[-1].tail or "",
                                 nx.text,
                             )
                         else:
-                            element.text = "%s %s" % (element.text or "", nx.text)
+                            element.text = "{} {}".format(element.text or "", nx.text)
 
                     for child in nx:
                         element.append(child)
 
                     # tail is merged with previous element.
                     nx.drop_tree()
 
@@ -365,15 +366,15 @@
                     continue
 
             for processor in self.element_postprocessors:
                 element = processor(element)
 
             # remove all attributes which are not explicitly allowed
             allowed = self.attributes.get(element.tag, [])
-            for key in element.keys():
+            for key in element.keys():  # noqa: SIM118 (do not remove .keys())
                 if key not in allowed:
                     del element.attrib[key]
 
             # Clean hrefs so that they are benign
             href = element.get("href")
             if href is not None:
                 element.set("href", self.sanitize_href(href))
```

### Comparing `html_sanitizer-1.9.3/html_sanitizer/tests.py` & `html_sanitizer-2.0.0/html_sanitizer/tests.py`

 * *Files 19% similar despite different names*

```diff
@@ -6,20 +6,20 @@
 default_sanitizer = Sanitizer()
 
 
 class SanitizerTestCase(TestCase):
     def run_tests(self, entries, *, sanitizer=default_sanitizer, strip=False):
         for before, after in entries:
             with self.subTest(before=before, after=after):
-                after = before if after is None else after
+                after = before if after is None else after  # noqa: PLW2901
                 result = sanitizer.sanitize(before)
                 self.assertEqual(
                     result.strip() if strip else result,
                     after.strip() if strip else after,
-                    "Cleaning '%s', expected '%s' but got '%s'"
+                    b"Cleaning '%s', expected '%s' but got '%s'"
                     % (
                         before.encode("unicode-escape"),
                         after.encode("unicode-escape"),
                         result.encode("unicode-escape"),
                     ),
                 )
 
@@ -394,18 +394,18 @@
 verpflichtet, ihre Spesen im Rahmen dieses Reglements möglichst tief
 zu halten. Aufwendungen, die für die Arbeitsausführung nicht
 notwendig waren, werden von der Firma nicht übernommen, sondern sind
 von den Mitarbeitenden selbst zu tragen.</font></p>
 <p class="western" style="margin-left: 0.39in; margin-top: 0.13in; margin-bottom: 0in; line-height: 0.19in" lang="de-DE" align="justify">
 <font style="font-size: 12pt" size="3">Im Wesentlichen werden den
 Mitarbeitenden folgende geschäftlich bedingten Auslagen ersetzt:</font></p>
-<ul><li><p class="western" style="margin-top: 0.13in; margin-bottom: 0in; line-height: 0.19in" lang="de-DE" align="justify"> <font style="font-size: 12pt" size="3">-	Fahrtkosten					(nachfolgend 2.)</font></p> </li><li><p class="western" style="margin-bottom: 0in; line-height: 0.19in" lang="de-DE" align="justify"> <font style="font-size: 12pt" size="3">-	Verpflegungskosten			(nachfolgend 3.)</font></p> </li><li><p class="western" style="margin-bottom: 0in; line-height: 0.19in" lang="de-DE" align="justify"> <font style="font-size: 12pt" size="3">-	Übernachtungskosten			(nachfolgend 4.)</font></p> </li><li><p class="western" style="margin-bottom: 0in; line-height: 0.19in" lang="de-DE" align="justify"> <font style="font-size: 12pt" size="3">-	Übrige Kosten				(nachfolgend 5.)</font></p> </li></ul>"""  # noqa
+<ul><li><p class="western" style="margin-top: 0.13in; margin-bottom: 0in; line-height: 0.19in" lang="de-DE" align="justify"> <font style="font-size: 12pt" size="3">-	Fahrtkosten					(nachfolgend 2.)</font></p> </li><li><p class="western" style="margin-bottom: 0in; line-height: 0.19in" lang="de-DE" align="justify"> <font style="font-size: 12pt" size="3">-	Verpflegungskosten			(nachfolgend 3.)</font></p> </li><li><p class="western" style="margin-bottom: 0in; line-height: 0.19in" lang="de-DE" align="justify"> <font style="font-size: 12pt" size="3">-	Übernachtungskosten			(nachfolgend 4.)</font></p> </li><li><p class="western" style="margin-bottom: 0in; line-height: 0.19in" lang="de-DE" align="justify"> <font style="font-size: 12pt" size="3">-	Übrige Kosten				(nachfolgend 5.)</font></p> </li></ul>"""
 
         result = """\
-<p> <strong>1.2. Definition des Spesenbegriffs</strong></p> <p> Als Spesen im Sinne dieses Reglements gelten die Auslagen, die einem Mitarbeitenden im Interesse des Arbeitgebers angefallen sind. Sämtliche Mitarbeitende sind verpflichtet, ihre Spesen im Rahmen dieses Reglements möglichst tief zu halten. Aufwendungen, die für die Arbeitsausführung nicht notwendig waren, werden von der Firma nicht übernommen, sondern sind von den Mitarbeitenden selbst zu tragen.</p> <p> Im Wesentlichen werden den Mitarbeitenden folgende geschäftlich bedingten Auslagen ersetzt:</p> <ul><li> - Fahrtkosten (nachfolgend 2.) </li><li> - Verpflegungskosten (nachfolgend 3.) </li><li> - Übernachtungskosten (nachfolgend 4.) </li><li> - Übrige Kosten (nachfolgend 5.) </li></ul>"""  # noqa
+<p> <strong>1.2. Definition des Spesenbegriffs</strong></p> <p> Als Spesen im Sinne dieses Reglements gelten die Auslagen, die einem Mitarbeitenden im Interesse des Arbeitgebers angefallen sind. Sämtliche Mitarbeitende sind verpflichtet, ihre Spesen im Rahmen dieses Reglements möglichst tief zu halten. Aufwendungen, die für die Arbeitsausführung nicht notwendig waren, werden von der Firma nicht übernommen, sondern sind von den Mitarbeitenden selbst zu tragen.</p> <p> Im Wesentlichen werden den Mitarbeitenden folgende geschäftlich bedingten Auslagen ersetzt:</p> <ul><li> - Fahrtkosten (nachfolgend 2.) </li><li> - Verpflegungskosten (nachfolgend 3.) </li><li> - Übernachtungskosten (nachfolgend 4.) </li><li> - Übrige Kosten (nachfolgend 5.) </li></ul>"""
 
         # XXX An exact match isn't really required. Using Django's
         # assertHTMLEqual would be great but we'd have to depend on Django in
         # the test suite for this (not a big problem really, because then we
         # could also test html_sanitizer.django but I didn't yet *have* to do
         # this)
         self.run_tests([(source, result)])
@@ -417,15 +417,23 @@
         self.run_tests(
             [
                 (
                     "\u200a\u2001\u202f\u2004\xa0\u2007\u2002\u2000"
                     "\u2003\u2009\u205f\u2005\u2006\u2008\u3000",
                     "\u200a\u2003\u202f\u2004\xa0\u2007\u2002\u2002"
                     "\u2003\u2009\u205f\u2005\u2006\u2008\u3000",
-                )
+                ),
+                (
+                    "Hello This is a paragraph. \n"
+                    "\tHello. This is a tabled line."
+                    "Hello.This is beginning of the end.\r",
+                    "Hello This is a paragraph. \n"
+                    "\tHello. This is a tabled line."
+                    "Hello.This is beginning of the end.\r",
+                ),
             ],
             sanitizer=sanitizer,
         )
 
     def test_strip_typographic_whitespace(self):
         sanitizer = Sanitizer({"keep_typographic_whitespace": False})
 
@@ -510,15 +518,15 @@
                     "empty": set(),
                     "separate": set(),
                 }
             ),
         )
 
     def test_billion_laughs(self):
-        source = """\
+        before = """\
 <?xml version="1.0"?>
 <!DOCTYPE lolz [
  <!ENTITY lol "lol">
  <!ELEMENT lolz (#PCDATA)>
  <!ENTITY lol1 "&lol;&lol;&lol;&lol;&lol;&lol;&lol;&lol;&lol;&lol;">
  <!ENTITY lol2 "&lol1;&lol1;&lol1;&lol1;&lol1;&lol1;&lol1;&lol1;&lol1;&lol1;">
  <!ENTITY lol3 "&lol2;&lol2;&lol2;&lol2;&lol2;&lol2;&lol2;&lol2;&lol2;&lol2;">
@@ -527,26 +535,32 @@
  <!ENTITY lol6 "&lol5;&lol5;&lol5;&lol5;&lol5;&lol5;&lol5;&lol5;&lol5;&lol5;">
  <!ENTITY lol7 "&lol6;&lol6;&lol6;&lol6;&lol6;&lol6;&lol6;&lol6;&lol6;&lol6;">
  <!ENTITY lol8 "&lol7;&lol7;&lol7;&lol7;&lol7;&lol7;&lol7;&lol7;&lol7;&lol7;">
  <!ENTITY lol9 "&lol8;&lol8;&lol8;&lol8;&lol8;&lol8;&lol8;&lol8;&lol8;&lol8;">
 ]>
 <lolz>&lol9;</lolz>
 """
+        after = """\
+  &lt;!ELEMENT lolz (#PCDATA)&gt; &lt;!ENTITY lol1 "&amp;lol;&amp;lol;&amp;lol;&amp;lol;&amp;lol;&amp;lol;&amp;lol;&amp;lol;&amp;lol;&amp;lol;"&gt; &lt;!ENTITY lol2 "&amp;lol1;&amp;lol1;&amp;lol1;&amp;lol1;&amp;lol1;&amp;lol1;&amp;lol1;&amp;lol1;&amp;lol1;&amp;lol1;"&gt; &lt;!ENTITY lol3 "&amp;lol2;&amp;lol2;&amp;lol2;&amp;lol2;&amp;lol2;&amp;lol2;&amp;lol2;&amp;lol2;&amp;lol2;&amp;lol2;"&gt; &lt;!ENTITY lol4 "&amp;lol3;&amp;lol3;&amp;lol3;&amp;lol3;&amp;lol3;&amp;lol3;&amp;lol3;&amp;lol3;&amp;lol3;&amp;lol3;"&gt; &lt;!ENTITY lol5 "&amp;lol4;&amp;lol4;&amp;lol4;&amp;lol4;&amp;lol4;&amp;lol4;&amp;lol4;&amp;lol4;&amp;lol4;&amp;lol4;"&gt; &lt;!ENTITY lol6 "&amp;lol5;&amp;lol5;&amp;lol5;&amp;lol5;&amp;lol5;&amp;lol5;&amp;lol5;&amp;lol5;&amp;lol5;&amp;lol5;"&gt; &lt;!ENTITY lol7 "&amp;lol6;&amp;lol6;&amp;lol6;&amp;lol6;&amp;lol6;&amp;lol6;&amp;lol6;&amp;lol6;&amp;lol6;&amp;lol6;"&gt; &lt;!ENTITY lol8 "&amp;lol7;&amp;lol7;&amp;lol7;&amp;lol7;&amp;lol7;&amp;lol7;&amp;lol7;&amp;lol7;&amp;lol7;&amp;lol7;"&gt; &lt;!ENTITY lol9 "&amp;lol8;&amp;lol8;&amp;lol8;&amp;lol8;&amp;lol8;&amp;lol8;&amp;lol8;&amp;lol8;&amp;lol8;&amp;lol8;"&gt; ]&gt; &amp;lol9;
+"""
 
         external_entities = """\
  <?xml version="1.0"?>
   <!DOCTYPE foo [
    <!ELEMENT foo ANY >
    <!ENTITY xxe SYSTEM "file:///dev/random" >]><foo>&xxe;</foo>
 """
 
         self.run_tests(
             [
-                (source, "             ]&gt; &amp;lol9; "),
-                (external_entities, "    ]&gt;&amp;xxe; "),
+                (before, after),
+                (
+                    external_entities,
+                    """&lt;!ENTITY xxe SYSTEM "file:///dev/random" &gt;]&gt;&amp;xxe;""",
+                ),
             ],
             strip=True,
         )
 
     def test_data_attributes(self):
         sanitizer = Sanitizer(
             {
@@ -565,7 +579,14 @@
             (
                 '<span data-title="Test" data-other="Stuff">Content</span>',
                 '<span data-title="Test">Content</span>',
             ),
         )
 
         self.run_tests(entries, sanitizer=sanitizer)
+
+    def test_entities(self):
+        self.run_tests(
+            [
+                ("&lsquo;", "\u2018"),
+            ],
+        )
```


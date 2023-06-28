# Comparing `tmp/pretext-1.6.1.dev20230627.tar.gz` & `tmp/pretext-1.6.1.dev20230628.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pretext-1.6.1.dev20230627.tar", max compression
+gzip compressed data, was "pretext-1.6.1.dev20230628.tar", max compression
```

## Comparing `pretext-1.6.1.dev20230627.tar` & `pretext-1.6.1.dev20230628.tar`

### file list

```diff
@@ -1,28 +1,28 @@
--rw-r--r--   0        0        0    35148 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/LICENSE
--rw-r--r--   0        0        0     9757 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/README.md
--rw-r--r--   0        0        0     1909 2023-06-27 06:16:29.860806 pretext-1.6.1.dev20230627/pretext/__init__.py
--rw-r--r--   0        0        0       61 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/pretext/__main__.py
--rw-r--r--   0        0        0     8531 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/pretext/build.py
--rw-r--r--   0        0        0    25736 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/pretext/cli.py
--rw-r--r--   0        0        0     5856 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/pretext/codechat.py
--rw-r--r--   0        0        0     5943 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/pretext/config/xml_overlay.py
--rw-r--r--   0        0        0      350 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/pretext/core/__init__.py
--rw-r--r--   0        0        0   172492 2023-06-27 06:16:35.016815 pretext-1.6.1.dev20230627/pretext/core/pretext.py
--rw-r--r--   0        0        0     1484 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/pretext/core/resources.py
--rw-r--r--   0        0        0  1041222 2023-06-27 06:16:35.016815 pretext-1.6.1.dev20230627/pretext/core/resources.zip
--rw-r--r--   0        0        0    16741 2023-06-27 06:15:55.672754 pretext-1.6.1.dev20230627/pretext/generate.py
--rw-r--r--   0        0        0    29108 2023-06-27 06:15:55.676754 pretext-1.6.1.dev20230627/pretext/project.py
--rw-r--r--   0        0        0      739 2023-06-27 06:15:55.676754 pretext-1.6.1.dev20230627/pretext/templates/__init__.py
--rw-r--r--   0        0        0     1676 2023-06-27 06:16:35.092815 pretext-1.6.1.dev20230627/pretext/templates/resources/.gitignore
--rw-r--r--   0        0        0        0 2023-06-27 06:16:35.092815 pretext-1.6.1.dev20230627/pretext/templates/resources/__init__.py
--rw-r--r--   0        0        0   160110 2023-06-27 06:16:35.068815 pretext-1.6.1.dev20230627/pretext/templates/resources/article.zip
--rw-r--r--   0        0        0     7616 2023-06-27 06:16:35.072815 pretext-1.6.1.dev20230627/pretext/templates/resources/book.zip
--rw-r--r--   0        0        0   173309 2023-06-27 06:16:35.092815 pretext-1.6.1.dev20230627/pretext/templates/resources/demo.zip
--rw-r--r--   0        0        0     2192 2023-06-27 06:16:35.092815 pretext-1.6.1.dev20230627/pretext/templates/resources/devcontainer.json
--rw-r--r--   0        0        0     4657 2023-06-27 06:16:35.076815 pretext-1.6.1.dev20230627/pretext/templates/resources/hello.zip
--rw-r--r--   0        0        0     1710 2023-06-27 06:16:35.092815 pretext-1.6.1.dev20230627/pretext/templates/resources/project.ptx
--rw-r--r--   0        0        0      242 2023-06-27 06:16:35.092815 pretext-1.6.1.dev20230627/pretext/templates/resources/publication.ptx
--rw-r--r--   0        0        0     8392 2023-06-27 06:16:35.076815 pretext-1.6.1.dev20230627/pretext/templates/resources/slideshow.zip
--rw-r--r--   0        0        0    25086 2023-06-27 06:15:55.676754 pretext-1.6.1.dev20230627/pretext/utils.py
--rw-r--r--   0        0        0     3333 2023-06-27 06:16:29.860806 pretext-1.6.1.dev20230627/pyproject.toml
--rw-r--r--   0        0        0    10854 1970-01-01 00:00:00.000000 pretext-1.6.1.dev20230627/PKG-INFO
+-rw-r--r--   0        0        0    35148 2023-06-28 06:14:51.233658 pretext-1.6.1.dev20230628/LICENSE
+-rw-r--r--   0        0        0     9757 2023-06-28 06:14:51.233658 pretext-1.6.1.dev20230628/README.md
+-rw-r--r--   0        0        0     1909 2023-06-28 06:15:30.025987 pretext-1.6.1.dev20230628/pretext/__init__.py
+-rw-r--r--   0        0        0       61 2023-06-28 06:14:51.233658 pretext-1.6.1.dev20230628/pretext/__main__.py
+-rw-r--r--   0        0        0     8531 2023-06-28 06:14:51.233658 pretext-1.6.1.dev20230628/pretext/build.py
+-rw-r--r--   0        0        0    25736 2023-06-28 06:14:51.233658 pretext-1.6.1.dev20230628/pretext/cli.py
+-rw-r--r--   0        0        0     5856 2023-06-28 06:14:51.233658 pretext-1.6.1.dev20230628/pretext/codechat.py
+-rw-r--r--   0        0        0     5943 2023-06-28 06:14:51.237658 pretext-1.6.1.dev20230628/pretext/config/xml_overlay.py
+-rw-r--r--   0        0        0      350 2023-06-28 06:14:51.237658 pretext-1.6.1.dev20230628/pretext/core/__init__.py
+-rw-r--r--   0        0        0   172492 2023-06-28 06:15:35.234025 pretext-1.6.1.dev20230628/pretext/core/pretext.py
+-rw-r--r--   0        0        0     1484 2023-06-28 06:14:51.237658 pretext-1.6.1.dev20230628/pretext/core/resources.py
+-rw-r--r--   0        0        0  1041510 2023-06-28 06:15:35.234025 pretext-1.6.1.dev20230628/pretext/core/resources.zip
+-rw-r--r--   0        0        0    16741 2023-06-28 06:14:51.237658 pretext-1.6.1.dev20230628/pretext/generate.py
+-rw-r--r--   0        0        0    29108 2023-06-28 06:14:51.237658 pretext-1.6.1.dev20230628/pretext/project.py
+-rw-r--r--   0        0        0      739 2023-06-28 06:14:51.237658 pretext-1.6.1.dev20230628/pretext/templates/__init__.py
+-rw-r--r--   0        0        0     1676 2023-06-28 06:15:35.338025 pretext-1.6.1.dev20230628/pretext/templates/resources/.gitignore
+-rw-r--r--   0        0        0        0 2023-06-28 06:15:35.338025 pretext-1.6.1.dev20230628/pretext/templates/resources/__init__.py
+-rw-r--r--   0        0        0   160110 2023-06-28 06:15:35.302025 pretext-1.6.1.dev20230628/pretext/templates/resources/article.zip
+-rw-r--r--   0        0        0     7616 2023-06-28 06:15:35.306025 pretext-1.6.1.dev20230628/pretext/templates/resources/book.zip
+-rw-r--r--   0        0        0   173309 2023-06-28 06:15:35.334025 pretext-1.6.1.dev20230628/pretext/templates/resources/demo.zip
+-rw-r--r--   0        0        0     2192 2023-06-28 06:15:35.338025 pretext-1.6.1.dev20230628/pretext/templates/resources/devcontainer.json
+-rw-r--r--   0        0        0     4657 2023-06-28 06:15:35.318025 pretext-1.6.1.dev20230628/pretext/templates/resources/hello.zip
+-rw-r--r--   0        0        0     1710 2023-06-28 06:15:35.338025 pretext-1.6.1.dev20230628/pretext/templates/resources/project.ptx
+-rw-r--r--   0        0        0      242 2023-06-28 06:15:35.338025 pretext-1.6.1.dev20230628/pretext/templates/resources/publication.ptx
+-rw-r--r--   0        0        0     8392 2023-06-28 06:15:35.310025 pretext-1.6.1.dev20230628/pretext/templates/resources/slideshow.zip
+-rw-r--r--   0        0        0    25086 2023-06-28 06:14:51.237658 pretext-1.6.1.dev20230628/pretext/utils.py
+-rw-r--r--   0        0        0     3333 2023-06-28 06:15:30.025987 pretext-1.6.1.dev20230628/pyproject.toml
+-rw-r--r--   0        0        0    10854 1970-01-01 00:00:00.000000 pretext-1.6.1.dev20230628/PKG-INFO
```

### Comparing `pretext-1.6.1.dev20230627/LICENSE` & `pretext-1.6.1.dev20230628/LICENSE`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/README.md` & `pretext-1.6.1.dev20230628/README.md`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/__init__.py` & `pretext-1.6.1.dev20230628/pretext/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -14,15 +14,15 @@
 # along with this program.  If not, see <https://www.gnu.org/licenses/>.
 
 from pathlib import Path
 from single_version import get_version
 
 VERSION = get_version("pretext", Path(__file__).parent.parent)
 
-CORE_COMMIT = '3af9f7123aab845bc4dbc4dc6a3607c3b7980030'
+CORE_COMMIT = '61af1390d2c4f631f1cc6affc27bebdd0db1dfe9'
 
 # List of templates, build formats, and assets that are supported by the CLI.
 NEW_TEMPLATES = ["book", "article", "demo", "hello", "slideshow"]
 BUILD_FORMATS = [
     "html",
     "pdf",
     "latex",
```

### Comparing `pretext-1.6.1.dev20230627/pretext/build.py` & `pretext-1.6.1.dev20230628/pretext/build.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/cli.py` & `pretext-1.6.1.dev20230628/pretext/cli.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/codechat.py` & `pretext-1.6.1.dev20230628/pretext/codechat.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/config/xml_overlay.py` & `pretext-1.6.1.dev20230628/pretext/config/xml_overlay.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/core/pretext.py` & `pretext-1.6.1.dev20230628/pretext/core/pretext.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/core/resources.py` & `pretext-1.6.1.dev20230628/pretext/core/resources.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/core/resources.zip` & `pretext-1.6.1.dev20230628/pretext/core/resources.zip`

 * *Files 11% similar despite different names*

#### zipinfo {}

```diff
@@ -1,144 +1,144 @@
-Zip file size: 1041222 bytes, number of entries: 142
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 css/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 pretext/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 schema/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 script/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 xsl/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 script/mjsre/
--rw-r--r--  2.0 unx      258 b- defN 23-Jun-27 06:16 script/README.md
--rw-r--r--  2.0 unx     2666 b- defN 23-Jun-27 06:16 script/mbx
--rw-r--r--  2.0 unx      481 b- defN 23-Jun-27 06:16 script/mjsre/README.md
--rw-r--r--  2.0 unx      116 b- defN 23-Jun-27 06:16 script/mjsre/package.json
--rw-r--r--  2.0 unx       92 b- defN 23-Jun-27 06:16 script/mjsre/update-sre
--rw-r--r--  2.0 unx     9251 b- defN 23-Jun-27 06:16 script/mjsre/mj-sre-page.js
--rw-r--r--  2.0 unx        0 b- defN 23-Jun-27 06:16 pretext/__init__.py
--rw-r--r--  2.0 unx    30908 b- defN 23-Jun-27 06:16 pretext/pretext
--rw-r--r--  2.0 unx     1367 b- defN 23-Jun-27 06:16 pretext/README.md
--rw-r--r--  2.0 unx     2566 b- defN 23-Jun-27 06:16 pretext/pretext.cfg
--rw-r--r--  2.0 unx   172492 b- defN 23-Jun-27 06:16 pretext/pretext.py
--rw-r--r--  2.0 unx     1955 b- defN 23-Jun-27 06:16 pretext/module-test.py
--rw-r--r--  2.0 unx    35449 b- defN 23-Jun-27 06:16 pretext/braille_format.py
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 xsl/latex/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 xsl/localizations/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 xsl/support/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 xsl/utilities/
--rw-r--r--  2.0 unx     2248 b- defN 23-Jun-27 06:16 xsl/extract-mom.xsl
--rw-r--r--  2.0 unx   612399 b- defN 23-Jun-27 06:16 xsl/pretext-html.xsl
--rw-r--r--  2.0 unx    12084 b- defN 23-Jun-27 06:16 xsl/xml-to-json.xsl
--rw-r--r--  2.0 unx   231265 b- defN 23-Jun-27 06:16 xsl/publisher-variables.xsl
--rw-r--r--  2.0 unx    10708 b- defN 23-Jun-27 06:16 xsl/pretext-units.xsl
--rw-r--r--  2.0 unx     1768 b- defN 23-Jun-27 06:16 xsl/README.md
--rw-r--r--  2.0 unx    39918 b- defN 23-Jun-27 06:16 xsl/pretext-runestone-static.xsl
--rw-r--r--  2.0 unx    21086 b- defN 23-Jun-27 06:16 xsl/pretext-smc.xsl
--rw-r--r--  2.0 unx   546938 b- defN 23-Jun-27 06:16 xsl/pretext-common.xsl
--rw-r--r--  2.0 unx    11766 b- defN 23-Jun-27 06:16 xsl/pretext-sage-doctest.xsl
--rw-r--r--  2.0 unx    43020 b- defN 23-Jun-27 06:16 xsl/pretext-text-utilities.xsl
--rw-r--r--  2.0 unx   109017 b- defN 23-Jun-27 06:16 xsl/pretext-runestone.xsl
--rw-r--r--  2.0 unx    13037 b- defN 23-Jun-27 06:16 xsl/pretext-text.xsl
--rw-r--r--  2.0 unx    13186 b- defN 23-Jun-27 06:16 xsl/pretext-solution-manual-latex.xsl
--rw-r--r--  2.0 unx     2846 b- defN 23-Jun-27 06:16 xsl/extract-datafile.xsl
--rw-r--r--  2.0 unx    40230 b- defN 23-Jun-27 06:16 xsl/pretext-jupyter.xsl
--rw-r--r--  2.0 unx    17293 b- defN 23-Jun-27 06:16 xsl/pretext-ww-problem-sets.xsl
--rw-r--r--  2.0 unx   544229 b- defN 23-Jun-27 06:16 xsl/pretext-latex.xsl
--rw-r--r--  2.0 unx    19072 b- defN 23-Jun-27 06:16 xsl/extract-latex-image.xsl
--rw-r--r--  2.0 unx     8535 b- defN 23-Jun-27 06:16 xsl/pretext-view-source.xsl
--rw-r--r--  2.0 unx     2740 b- defN 23-Jun-27 06:16 xsl/extract-youtube.xsl
--rw-r--r--  2.0 unx   112450 b- defN 23-Jun-27 06:16 xsl/pretext-assembly.xsl
--rw-r--r--  2.0 unx     8130 b- defN 23-Jun-27 06:16 xsl/extract-identity.xsl
--rw-r--r--  2.0 unx     2725 b- defN 23-Jun-27 06:16 xsl/extract-asymptote.xsl
--rw-r--r--  2.0 unx     2601 b- defN 23-Jun-27 06:16 xsl/pretext-merge.xsl
--rw-r--r--  2.0 unx     2709 b- defN 23-Jun-27 06:16 xsl/extract-qrcode.xsl
--rw-r--r--  2.0 unx     8125 b- defN 23-Jun-27 06:16 xsl/extract-sageplot.xsl
--rw-r--r--  2.0 unx     6281 b- defN 23-Jun-27 06:16 xsl/pretext-numbers.xsl
--rw-r--r--  2.0 unx     3239 b- defN 23-Jun-27 06:16 xsl/extract-interactive.xsl
--rw-r--r--  2.0 unx     4571 b- defN 23-Jun-27 06:16 xsl/pretext-litprog.xsl
--rw-r--r--  2.0 unx     2597 b- defN 23-Jun-27 06:16 xsl/extract-trace.xsl
--rw-r--r--  2.0 unx    22121 b- defN 23-Jun-27 06:16 xsl/pretext-revealjs.xsl
--rw-r--r--  2.0 unx    41730 b- defN 23-Jun-27 06:16 xsl/pretext-beamer.xsl
--rw-r--r--  2.0 unx    89128 b- defN 23-Jun-27 06:16 xsl/pretext-braille-preprint.xsl
--rw-r--r--  2.0 unx   139486 b- defN 23-Jun-27 06:16 xsl/extract-pg.xsl
--rw-r--r--  2.0 unx    67275 b- defN 23-Jun-27 06:16 xsl/pretext-epub.xsl
--rw-r--r--  2.0 unx     3560 b- defN 23-Jun-27 06:16 xsl/pretext-basic-html.xsl
--rw-r--r--  2.0 unx     9787 b- defN 23-Jun-27 06:16 xsl/entities.ent
--rw-r--r--  2.0 unx     6066 b- defN 23-Jun-27 06:16 xsl/pretext-json-manifest.xsl
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 xsl/support/play-button/
--rw-r--r--  2.0 unx      504 b- defN 23-Jun-27 06:16 xsl/support/README.md
--rw-r--r--  2.0 unx     5065 b- defN 23-Jun-27 06:16 xsl/support/extract-latex-image-labels.xsl
--rw-r--r--  2.0 unx    10306 b- defN 23-Jun-27 06:16 xsl/support/extract-math.xsl
--rw-r--r--  2.0 unx     5800 b- defN 23-Jun-27 06:16 xsl/support/tactile-svg.xsl
--rw-r--r--  2.0 unx     5241 b- defN 23-Jun-27 06:16 xsl/support/pretext-pg-macros.xsl
--rw-r--r--  2.0 unx      486 b- defN 23-Jun-27 06:16 xsl/support/runestone-services.xml
--rw-r--r--  2.0 unx     5879 b- defN 23-Jun-27 06:16 xsl/support/package-math.xsl
--rw-r--r--  2.0 unx     2657 b- defN 23-Jun-27 06:16 xsl/support/play-button/README.md
--rw-r--r--  2.0 unx      722 b- defN 23-Jun-27 06:16 xsl/support/play-button/play-button.svg
--rw-r--r--  2.0 unx     6621 b- defN 23-Jun-27 06:16 xsl/support/play-button/play-button.png
--rw-r--r--  2.0 unx    14482 b- defN 23-Jun-27 06:16 xsl/latex/pretext-latex-chaos.xsl
--rw-r--r--  2.0 unx     7526 b- defN 23-Jun-27 06:16 xsl/latex/pretext-latex-CLP.xsl
--rw-r--r--  2.0 unx     3024 b- defN 23-Jun-27 06:16 xsl/latex/pretext-latex-dyslexic-font.xsl
--rw-r--r--  2.0 unx     5135 b- defN 23-Jun-27 06:16 xsl/latex/pretext-latex-guide.xsl
--rw-r--r--  2.0 unx     2261 b- defN 23-Jun-27 06:16 xsl/latex/pretext-latex-AIM.xsl
--rw-r--r--  2.0 unx    17040 b- defN 23-Jun-27 06:16 xsl/localizations/bg-BG.xml
--rw-r--r--  2.0 unx     2286 b- defN 23-Jun-27 06:16 xsl/localizations/localizations.xml
--rw-r--r--  2.0 unx    16518 b- defN 23-Jun-27 06:16 xsl/localizations/es-ES.xml
--rw-r--r--  2.0 unx     4760 b- defN 23-Jun-27 06:16 xsl/localizations/README.md
--rw-r--r--  2.0 unx    17215 b- defN 23-Jun-27 06:16 xsl/localizations/de-DE.xml
--rw-r--r--  2.0 unx    16821 b- defN 23-Jun-27 06:16 xsl/localizations/af-ZA.xml
--rw-r--r--  2.0 unx    16333 b- defN 23-Jun-27 06:16 xsl/localizations/fr-FR.xml
--rw-r--r--  2.0 unx    16484 b- defN 23-Jun-27 06:16 xsl/localizations/fr-CA.xml
--rw-r--r--  2.0 unx    17065 b- defN 23-Jun-27 06:16 xsl/localizations/pt-PT.xml
--rw-r--r--  2.0 unx    20465 b- defN 23-Jun-27 06:16 xsl/localizations/ku-CKB.xml
--rw-r--r--  2.0 unx    17285 b- defN 23-Jun-27 06:16 xsl/localizations/fi-FI.xml
--rw-r--r--  2.0 unx    19169 b- defN 23-Jun-27 06:16 xsl/localizations/nl-NL.xml
--rw-r--r--  2.0 unx    15566 b- defN 23-Jun-27 06:16 xsl/localizations/cs-CZ.xml
--rw-r--r--  2.0 unx    15850 b- defN 23-Jun-27 06:16 xsl/localizations/it-IT.xml
--rw-r--r--  2.0 unx    16236 b- defN 23-Jun-27 06:16 xsl/localizations/ca-ES.xml
--rw-r--r--  2.0 unx    16296 b- defN 23-Jun-27 06:16 xsl/localizations/pt-BR.xml
--rw-r--r--  2.0 unx    19049 b- defN 23-Jun-27 06:16 xsl/localizations/en-US.xml
--rw-r--r--  2.0 unx    16069 b- defN 23-Jun-27 06:16 xsl/localizations/hu-HU.xml
--rw-r--r--  2.0 unx      787 b- defN 23-Jun-27 06:16 xsl/utilities/deprecate-index.sed
--rw-r--r--  2.0 unx     1810 b- defN 23-Jun-27 06:16 xsl/utilities/README.md
--rw-r--r--  2.0 unx      513 b- defN 23-Jun-27 06:16 xsl/utilities/deprecate-autoname.sed
--rw-r--r--  2.0 unx     4926 b- defN 23-Jun-27 06:16 xsl/utilities/pretext-enhanced-source.xsl
--rw-r--r--  2.0 unx    30257 b- defN 23-Jun-27 06:16 xsl/utilities/fix-deprecations.xsl
--rw-r--r--  2.0 unx     4299 b- defN 23-Jun-27 06:16 xsl/utilities/author-report.xsl
--rw-r--r--  2.0 unx    34210 b- defN 23-Jun-27 06:16 schema/pretext-dev.rng
--rw-r--r--  2.0 unx    17587 b- defN 23-Jun-27 06:16 schema/pretext-dev.rnc
--rw-r--r--  2.0 unx     1180 b- defN 23-Jun-27 06:16 schema/README.md
--rw-r--r--  2.0 unx    18421 b- defN 23-Jun-27 06:16 schema/pretext-schematron.xsl
--rw-r--r--  2.0 unx   101829 b- defN 23-Jun-27 06:16 schema/pretext.rng
--rw-r--r--  2.0 unx   134043 b- defN 23-Jun-27 06:16 schema/pretext.xml
--rw-r--r--  2.0 unx    58086 b- defN 23-Jun-27 06:16 schema/pretext.rnc
--rw-r--r--  2.0 unx     3135 b- defN 23-Jun-27 06:16 schema/build.sh
--rw-r--r--  2.0 unx      326 b- defN 23-Jun-27 06:16 schema/xml.xsd
--rw-r--r--  2.0 unx    25870 b- defN 23-Jun-27 06:16 schema/pretext-validation-plus.xsl
--rw-r--r--  2.0 unx   125135 b- defN 23-Jun-27 06:16 schema/pretext.xsd
--rw-r--r--  2.0 unx     2446 b- defN 23-Jun-27 06:16 css/colors_martiansands.css
--rw-r--r--  2.0 unx     2446 b- defN 23-Jun-27 06:16 css/colors_darkmartiansands.css
--rw-r--r--  2.0 unx     1276 b- defN 23-Jun-27 06:16 css/colors_maroon_grey.css
--rw-r--r--  2.0 unx     4021 b- defN 23-Jun-27 06:16 css/update_css
--rw-r--r--  2.0 unx     1865 b- defN 23-Jun-27 06:16 css/README.md
--rw-r--r--  2.0 unx      691 b- defN 23-Jun-27 06:16 css/colors_pastel_blue_orange.css
--rw-r--r--  2.0 unx    12567 b- defN 23-Jun-27 06:16 css/style_oscarlevin.css
--rw-r--r--  2.0 unx   146685 b- defN 23-Jun-27 06:16 css/mathbook-content.css
--rw-r--r--  2.0 unx     2397 b- defN 23-Jun-27 06:16 css/colors_blue_red.css
--rw-r--r--  2.0 unx     2608 b- defN 23-Jun-27 06:16 css/colors_default.css
--rw-r--r--  2.0 unx     2397 b- defN 23-Jun-27 06:16 css/colors_ruby_amethyst.css
--rw-r--r--  2.0 unx     2438 b- defN 23-Jun-27 06:16 css/colors_blue_grey.css
--rw-r--r--  2.0 unx     1338 b- defN 23-Jun-27 06:16 css/colors_red_blue.css
--rw-r--r--  2.0 unx     2397 b- defN 23-Jun-27 06:16 css/colors_orange_navy.css
--rw-r--r--  2.0 unx     2397 b- defN 23-Jun-27 06:16 css/colors_green_blue.css
--rw-r--r--  2.0 unx     1362 b- defN 23-Jun-27 06:16 css/epub.css
--rw-r--r--  2.0 unx     2397 b- defN 23-Jun-27 06:16 css/colors_ruby_turquoise.css
--rw-r--r--  2.0 unx    22438 b- defN 23-Jun-27 06:16 css/pretext.css
--rw-r--r--  2.0 unx     2397 b- defN 23-Jun-27 06:16 css/colors_ruby_emerald.css
--rw-r--r--  2.0 unx     2397 b- defN 23-Jun-27 06:16 css/colors_green_plum.css
--rw-r--r--  2.0 unx     2441 b- defN 23-Jun-27 06:16 css/kindle.css
--rw-r--r--  2.0 unx     7761 b- defN 23-Jun-27 06:16 css/style_default.css
--rw-r--r--  2.0 unx    71198 b- defN 23-Jun-27 06:16 css/pretext_add_on.css
--rw-r--r--  2.0 unx    14069 b- defN 23-Jun-27 06:16 css/setcolors.css
--rw-r--r--  2.0 unx     3473 b- defN 23-Jun-27 06:16 css/style_soundwriting.css
--rw-r--r--  2.0 unx     4308 b- defN 23-Jun-27 06:16 css/colors_blue_green.css
--rw-r--r--  2.0 unx     1280 b- defN 23-Jun-27 06:16 css/colors_brown_gold.css
--rw-r--r--  2.0 unx   435680 b- defN 23-Jun-27 06:16 css/mathbook-3.css
--rw-r--r--  2.0 unx    63664 b- defN 23-Jun-27 06:16 css/mathbook-add-on.css
-142 files, 4835031 bytes uncompressed, 1023648 bytes compressed:  78.8%
+Zip file size: 1041510 bytes, number of entries: 142
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 css/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 pretext/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 schema/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 script/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 xsl/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 script/mjsre/
+-rw-r--r--  2.0 unx      258 b- defN 23-Jun-28 06:15 script/README.md
+-rw-r--r--  2.0 unx     2666 b- defN 23-Jun-28 06:15 script/mbx
+-rw-r--r--  2.0 unx      481 b- defN 23-Jun-28 06:15 script/mjsre/README.md
+-rw-r--r--  2.0 unx      116 b- defN 23-Jun-28 06:15 script/mjsre/package.json
+-rw-r--r--  2.0 unx       92 b- defN 23-Jun-28 06:15 script/mjsre/update-sre
+-rw-r--r--  2.0 unx     9251 b- defN 23-Jun-28 06:15 script/mjsre/mj-sre-page.js
+-rw-r--r--  2.0 unx        0 b- defN 23-Jun-28 06:15 pretext/__init__.py
+-rw-r--r--  2.0 unx    30908 b- defN 23-Jun-28 06:15 pretext/pretext
+-rw-r--r--  2.0 unx     1367 b- defN 23-Jun-28 06:15 pretext/README.md
+-rw-r--r--  2.0 unx     2566 b- defN 23-Jun-28 06:15 pretext/pretext.cfg
+-rw-r--r--  2.0 unx   172492 b- defN 23-Jun-28 06:15 pretext/pretext.py
+-rw-r--r--  2.0 unx     1955 b- defN 23-Jun-28 06:15 pretext/module-test.py
+-rw-r--r--  2.0 unx    35449 b- defN 23-Jun-28 06:15 pretext/braille_format.py
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 xsl/latex/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 xsl/localizations/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 xsl/support/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 xsl/utilities/
+-rw-r--r--  2.0 unx     2248 b- defN 23-Jun-28 06:15 xsl/extract-mom.xsl
+-rw-r--r--  2.0 unx   612399 b- defN 23-Jun-28 06:15 xsl/pretext-html.xsl
+-rw-r--r--  2.0 unx    12084 b- defN 23-Jun-28 06:15 xsl/xml-to-json.xsl
+-rw-r--r--  2.0 unx   231265 b- defN 23-Jun-28 06:15 xsl/publisher-variables.xsl
+-rw-r--r--  2.0 unx    10708 b- defN 23-Jun-28 06:15 xsl/pretext-units.xsl
+-rw-r--r--  2.0 unx     1768 b- defN 23-Jun-28 06:15 xsl/README.md
+-rw-r--r--  2.0 unx    39918 b- defN 23-Jun-28 06:15 xsl/pretext-runestone-static.xsl
+-rw-r--r--  2.0 unx    21086 b- defN 23-Jun-28 06:15 xsl/pretext-smc.xsl
+-rw-r--r--  2.0 unx   546938 b- defN 23-Jun-28 06:15 xsl/pretext-common.xsl
+-rw-r--r--  2.0 unx    11766 b- defN 23-Jun-28 06:15 xsl/pretext-sage-doctest.xsl
+-rw-r--r--  2.0 unx    43020 b- defN 23-Jun-28 06:15 xsl/pretext-text-utilities.xsl
+-rw-r--r--  2.0 unx   110044 b- defN 23-Jun-28 06:15 xsl/pretext-runestone.xsl
+-rw-r--r--  2.0 unx    13037 b- defN 23-Jun-28 06:15 xsl/pretext-text.xsl
+-rw-r--r--  2.0 unx    13186 b- defN 23-Jun-28 06:15 xsl/pretext-solution-manual-latex.xsl
+-rw-r--r--  2.0 unx     2846 b- defN 23-Jun-28 06:15 xsl/extract-datafile.xsl
+-rw-r--r--  2.0 unx    40230 b- defN 23-Jun-28 06:15 xsl/pretext-jupyter.xsl
+-rw-r--r--  2.0 unx    17293 b- defN 23-Jun-28 06:15 xsl/pretext-ww-problem-sets.xsl
+-rw-r--r--  2.0 unx   544229 b- defN 23-Jun-28 06:15 xsl/pretext-latex.xsl
+-rw-r--r--  2.0 unx    19072 b- defN 23-Jun-28 06:15 xsl/extract-latex-image.xsl
+-rw-r--r--  2.0 unx     8535 b- defN 23-Jun-28 06:15 xsl/pretext-view-source.xsl
+-rw-r--r--  2.0 unx     2740 b- defN 23-Jun-28 06:15 xsl/extract-youtube.xsl
+-rw-r--r--  2.0 unx   112450 b- defN 23-Jun-28 06:15 xsl/pretext-assembly.xsl
+-rw-r--r--  2.0 unx     8130 b- defN 23-Jun-28 06:15 xsl/extract-identity.xsl
+-rw-r--r--  2.0 unx     2725 b- defN 23-Jun-28 06:15 xsl/extract-asymptote.xsl
+-rw-r--r--  2.0 unx     2601 b- defN 23-Jun-28 06:15 xsl/pretext-merge.xsl
+-rw-r--r--  2.0 unx     2709 b- defN 23-Jun-28 06:15 xsl/extract-qrcode.xsl
+-rw-r--r--  2.0 unx     8125 b- defN 23-Jun-28 06:15 xsl/extract-sageplot.xsl
+-rw-r--r--  2.0 unx     6281 b- defN 23-Jun-28 06:15 xsl/pretext-numbers.xsl
+-rw-r--r--  2.0 unx     3239 b- defN 23-Jun-28 06:15 xsl/extract-interactive.xsl
+-rw-r--r--  2.0 unx     4571 b- defN 23-Jun-28 06:15 xsl/pretext-litprog.xsl
+-rw-r--r--  2.0 unx     2597 b- defN 23-Jun-28 06:15 xsl/extract-trace.xsl
+-rw-r--r--  2.0 unx    22121 b- defN 23-Jun-28 06:15 xsl/pretext-revealjs.xsl
+-rw-r--r--  2.0 unx    41730 b- defN 23-Jun-28 06:15 xsl/pretext-beamer.xsl
+-rw-r--r--  2.0 unx    89128 b- defN 23-Jun-28 06:15 xsl/pretext-braille-preprint.xsl
+-rw-r--r--  2.0 unx   139486 b- defN 23-Jun-28 06:15 xsl/extract-pg.xsl
+-rw-r--r--  2.0 unx    67275 b- defN 23-Jun-28 06:15 xsl/pretext-epub.xsl
+-rw-r--r--  2.0 unx     3560 b- defN 23-Jun-28 06:15 xsl/pretext-basic-html.xsl
+-rw-r--r--  2.0 unx     9787 b- defN 23-Jun-28 06:15 xsl/entities.ent
+-rw-r--r--  2.0 unx     6066 b- defN 23-Jun-28 06:15 xsl/pretext-json-manifest.xsl
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 xsl/support/play-button/
+-rw-r--r--  2.0 unx      504 b- defN 23-Jun-28 06:15 xsl/support/README.md
+-rw-r--r--  2.0 unx     5065 b- defN 23-Jun-28 06:15 xsl/support/extract-latex-image-labels.xsl
+-rw-r--r--  2.0 unx    10306 b- defN 23-Jun-28 06:15 xsl/support/extract-math.xsl
+-rw-r--r--  2.0 unx     5800 b- defN 23-Jun-28 06:15 xsl/support/tactile-svg.xsl
+-rw-r--r--  2.0 unx     5241 b- defN 23-Jun-28 06:15 xsl/support/pretext-pg-macros.xsl
+-rw-r--r--  2.0 unx      486 b- defN 23-Jun-28 06:15 xsl/support/runestone-services.xml
+-rw-r--r--  2.0 unx     5879 b- defN 23-Jun-28 06:15 xsl/support/package-math.xsl
+-rw-r--r--  2.0 unx     2657 b- defN 23-Jun-28 06:15 xsl/support/play-button/README.md
+-rw-r--r--  2.0 unx      722 b- defN 23-Jun-28 06:15 xsl/support/play-button/play-button.svg
+-rw-r--r--  2.0 unx     6621 b- defN 23-Jun-28 06:15 xsl/support/play-button/play-button.png
+-rw-r--r--  2.0 unx    14482 b- defN 23-Jun-28 06:15 xsl/latex/pretext-latex-chaos.xsl
+-rw-r--r--  2.0 unx     7526 b- defN 23-Jun-28 06:15 xsl/latex/pretext-latex-CLP.xsl
+-rw-r--r--  2.0 unx     3024 b- defN 23-Jun-28 06:15 xsl/latex/pretext-latex-dyslexic-font.xsl
+-rw-r--r--  2.0 unx     5135 b- defN 23-Jun-28 06:15 xsl/latex/pretext-latex-guide.xsl
+-rw-r--r--  2.0 unx     2261 b- defN 23-Jun-28 06:15 xsl/latex/pretext-latex-AIM.xsl
+-rw-r--r--  2.0 unx    17040 b- defN 23-Jun-28 06:15 xsl/localizations/bg-BG.xml
+-rw-r--r--  2.0 unx     2286 b- defN 23-Jun-28 06:15 xsl/localizations/localizations.xml
+-rw-r--r--  2.0 unx    16518 b- defN 23-Jun-28 06:15 xsl/localizations/es-ES.xml
+-rw-r--r--  2.0 unx     4760 b- defN 23-Jun-28 06:15 xsl/localizations/README.md
+-rw-r--r--  2.0 unx    17215 b- defN 23-Jun-28 06:15 xsl/localizations/de-DE.xml
+-rw-r--r--  2.0 unx    16821 b- defN 23-Jun-28 06:15 xsl/localizations/af-ZA.xml
+-rw-r--r--  2.0 unx    16333 b- defN 23-Jun-28 06:15 xsl/localizations/fr-FR.xml
+-rw-r--r--  2.0 unx    16484 b- defN 23-Jun-28 06:15 xsl/localizations/fr-CA.xml
+-rw-r--r--  2.0 unx    17065 b- defN 23-Jun-28 06:15 xsl/localizations/pt-PT.xml
+-rw-r--r--  2.0 unx    20465 b- defN 23-Jun-28 06:15 xsl/localizations/ku-CKB.xml
+-rw-r--r--  2.0 unx    17285 b- defN 23-Jun-28 06:15 xsl/localizations/fi-FI.xml
+-rw-r--r--  2.0 unx    19169 b- defN 23-Jun-28 06:15 xsl/localizations/nl-NL.xml
+-rw-r--r--  2.0 unx    15566 b- defN 23-Jun-28 06:15 xsl/localizations/cs-CZ.xml
+-rw-r--r--  2.0 unx    15850 b- defN 23-Jun-28 06:15 xsl/localizations/it-IT.xml
+-rw-r--r--  2.0 unx    16236 b- defN 23-Jun-28 06:15 xsl/localizations/ca-ES.xml
+-rw-r--r--  2.0 unx    16296 b- defN 23-Jun-28 06:15 xsl/localizations/pt-BR.xml
+-rw-r--r--  2.0 unx    19049 b- defN 23-Jun-28 06:15 xsl/localizations/en-US.xml
+-rw-r--r--  2.0 unx    16069 b- defN 23-Jun-28 06:15 xsl/localizations/hu-HU.xml
+-rw-r--r--  2.0 unx      787 b- defN 23-Jun-28 06:15 xsl/utilities/deprecate-index.sed
+-rw-r--r--  2.0 unx     1810 b- defN 23-Jun-28 06:15 xsl/utilities/README.md
+-rw-r--r--  2.0 unx      513 b- defN 23-Jun-28 06:15 xsl/utilities/deprecate-autoname.sed
+-rw-r--r--  2.0 unx     4926 b- defN 23-Jun-28 06:15 xsl/utilities/pretext-enhanced-source.xsl
+-rw-r--r--  2.0 unx    30257 b- defN 23-Jun-28 06:15 xsl/utilities/fix-deprecations.xsl
+-rw-r--r--  2.0 unx     4299 b- defN 23-Jun-28 06:15 xsl/utilities/author-report.xsl
+-rw-r--r--  2.0 unx    34210 b- defN 23-Jun-28 06:15 schema/pretext-dev.rng
+-rw-r--r--  2.0 unx    17587 b- defN 23-Jun-28 06:15 schema/pretext-dev.rnc
+-rw-r--r--  2.0 unx     1180 b- defN 23-Jun-28 06:15 schema/README.md
+-rw-r--r--  2.0 unx    18421 b- defN 23-Jun-28 06:15 schema/pretext-schematron.xsl
+-rw-r--r--  2.0 unx   101829 b- defN 23-Jun-28 06:15 schema/pretext.rng
+-rw-r--r--  2.0 unx   134043 b- defN 23-Jun-28 06:15 schema/pretext.xml
+-rw-r--r--  2.0 unx    58086 b- defN 23-Jun-28 06:15 schema/pretext.rnc
+-rw-r--r--  2.0 unx     3135 b- defN 23-Jun-28 06:15 schema/build.sh
+-rw-r--r--  2.0 unx      326 b- defN 23-Jun-28 06:15 schema/xml.xsd
+-rw-r--r--  2.0 unx    25870 b- defN 23-Jun-28 06:15 schema/pretext-validation-plus.xsl
+-rw-r--r--  2.0 unx   125135 b- defN 23-Jun-28 06:15 schema/pretext.xsd
+-rw-r--r--  2.0 unx     2446 b- defN 23-Jun-28 06:15 css/colors_martiansands.css
+-rw-r--r--  2.0 unx     2446 b- defN 23-Jun-28 06:15 css/colors_darkmartiansands.css
+-rw-r--r--  2.0 unx     1276 b- defN 23-Jun-28 06:15 css/colors_maroon_grey.css
+-rw-r--r--  2.0 unx     4021 b- defN 23-Jun-28 06:15 css/update_css
+-rw-r--r--  2.0 unx     1865 b- defN 23-Jun-28 06:15 css/README.md
+-rw-r--r--  2.0 unx      691 b- defN 23-Jun-28 06:15 css/colors_pastel_blue_orange.css
+-rw-r--r--  2.0 unx    12567 b- defN 23-Jun-28 06:15 css/style_oscarlevin.css
+-rw-r--r--  2.0 unx   146685 b- defN 23-Jun-28 06:15 css/mathbook-content.css
+-rw-r--r--  2.0 unx     2397 b- defN 23-Jun-28 06:15 css/colors_blue_red.css
+-rw-r--r--  2.0 unx     2608 b- defN 23-Jun-28 06:15 css/colors_default.css
+-rw-r--r--  2.0 unx     2397 b- defN 23-Jun-28 06:15 css/colors_ruby_amethyst.css
+-rw-r--r--  2.0 unx     2438 b- defN 23-Jun-28 06:15 css/colors_blue_grey.css
+-rw-r--r--  2.0 unx     1338 b- defN 23-Jun-28 06:15 css/colors_red_blue.css
+-rw-r--r--  2.0 unx     2397 b- defN 23-Jun-28 06:15 css/colors_orange_navy.css
+-rw-r--r--  2.0 unx     2397 b- defN 23-Jun-28 06:15 css/colors_green_blue.css
+-rw-r--r--  2.0 unx     1362 b- defN 23-Jun-28 06:15 css/epub.css
+-rw-r--r--  2.0 unx     2397 b- defN 23-Jun-28 06:15 css/colors_ruby_turquoise.css
+-rw-r--r--  2.0 unx    22438 b- defN 23-Jun-28 06:15 css/pretext.css
+-rw-r--r--  2.0 unx     2397 b- defN 23-Jun-28 06:15 css/colors_ruby_emerald.css
+-rw-r--r--  2.0 unx     2397 b- defN 23-Jun-28 06:15 css/colors_green_plum.css
+-rw-r--r--  2.0 unx     2441 b- defN 23-Jun-28 06:15 css/kindle.css
+-rw-r--r--  2.0 unx     7761 b- defN 23-Jun-28 06:15 css/style_default.css
+-rw-r--r--  2.0 unx    71198 b- defN 23-Jun-28 06:15 css/pretext_add_on.css
+-rw-r--r--  2.0 unx    14069 b- defN 23-Jun-28 06:15 css/setcolors.css
+-rw-r--r--  2.0 unx     3473 b- defN 23-Jun-28 06:15 css/style_soundwriting.css
+-rw-r--r--  2.0 unx     4308 b- defN 23-Jun-28 06:15 css/colors_blue_green.css
+-rw-r--r--  2.0 unx     1280 b- defN 23-Jun-28 06:15 css/colors_brown_gold.css
+-rw-r--r--  2.0 unx   435680 b- defN 23-Jun-28 06:15 css/mathbook-3.css
+-rw-r--r--  2.0 unx    63664 b- defN 23-Jun-28 06:15 css/mathbook-add-on.css
+142 files, 4836058 bytes uncompressed, 1023936 bytes compressed:  78.8%
```

#### xsl/pretext-runestone.xsl

##### xsl/pretext-runestone.xsl

```diff
@@ -668,14 +668,28 @@
   <!--   - every clickable area problem "exercise"      -->
   <!--   - every "exercise" with fill-in blanks         -->
   <!--   - every "exercise" with additional "program"   -->
   <!--   - every "exercise" elected as "shortanswer"    -->
   <!--   - every PROJECT-LIKE with additional "program" -->
   <xsl:template match="exercise[ (@exercise-interactive = 'truefalse') or                                (@exercise-interactive = 'multiplechoice') or                                (@exercise-interactive = 'parson') or                                (@exercise-interactive = 'parson-horizontal') or                                (@exercise-interactive = 'matching') or                                (@exercise-interactive = 'clickablearea') or                                (@exercise-interactive = 'select') or                                (@exercise-interactive = 'fillin-basic') or                                (@exercise-interactive = 'coding') or                                (@exercise-interactive = 'shortanswer')]                       |                       project[ (@exercise-interactive = 'truefalse') or                                (@exercise-interactive = 'multiplechoice') or                                (@exercise-interactive = 'parson') or                                (@exercise-interactive = 'parson-horizontal') or                                (@exercise-interactive = 'matching') or                                (@exercise-interactive = 'clickablearea') or                                (@exercise-interactive = 'select') or                                (@exercise-interactive = 'fillin-basic') or                                (@exercise-interactive = 'coding') or                                (@exercise-interactive = 'shortanswer')]                      |                      activity[ (@exercise-interactive = 'truefalse') or                                (@exercise-interactive = 'multiplechoice') or                                (@exercise-interactive = 'parson') or                                (@exercise-interactive = 'parson-horizontal') or                                (@exercise-interactive = 'matching') or                                (@exercise-interactive = 'clickablearea') or                                (@exercise-interactive = 'select') or                                (@exercise-interactive = 'fillin-basic') or                                (@exercise-interactive = 'coding') or                                (@exercise-interactive = 'shortanswer')]                      |                   exploration[ (@exercise-interactive = 'truefalse') or                                (@exercise-interactive = 'multiplechoice') or                                (@exercise-interactive = 'parson') or                                (@exercise-interactive = 'matching') or                                (@exercise-interactive = 'parson-horizontal') or                                (@exercise-interactive = 'clickablearea') or                                (@exercise-interactive = 'select') or                                (@exercise-interactive = 'fillin-basic') or                                (@exercise-interactive = 'coding') or                                (@exercise-interactive = 'shortanswer')]                      |                 investigation[ (@exercise-interactive = 'truefalse') or                                (@exercise-interactive = 'multiplechoice') or                                (@exercise-interactive = 'parson') or                                (@exercise-interactive = 'parson-horizontal') or                                (@exercise-interactive = 'matching') or                                (@exercise-interactive = 'clickablearea') or                                (@exercise-interactive = 'select') or                                (@exercise-interactive = 'fillin-basic') or                                (@exercise-interactive = 'coding') or                                (@exercise-interactive = 'shortanswer')]                      |                          task[ (@exercise-interactive = 'truefalse') or                                (@exercise-interactive = 'multiplechoice') or                                (@exercise-interactive = 'parson') or                                (@exercise-interactive = 'parson-horizontal') or                                (@exercise-interactive = 'matching') or                                (@exercise-interactive = 'clickablearea') or                                (@exercise-interactive = 'select') or                                (@exercise-interactive = 'fillin-basic') or                                (@exercise-interactive = 'coding') or                                (@exercise-interactive = 'shortanswer')]" mode="runestone-manifest">
     <question>
+      <!-- A divisional exercise ("exercises/../exercise") is not really   -->
+      <!-- a reading activity in the Runestone model, so we flag these     -->
+      <!-- exercises as such.  Also, interactive "task" come through here, -->
+      <!-- so we need to look to an ancestor to see if the containing      -->
+      <!-- "exercise" is divisional. The @optional attribute matches the   -->
+      <!-- "optional" flag in the Runestone database.  We simply set the   -->
+      <!-- value to "yes" and nevver bother to say "no".  The  only        -->
+      <!-- consumer is the import into the Runestone database, so any      -->
+      <!-- change needs only coordinate there.                             -->
+      <xsl:if test="(@exercise-customization = 'divisional') or                       (self::task and ancestor::exercise[@exercise-customization = 'divisional'])">
+        <xsl:attribute name="optional">
+          <xsl:text>yes</xsl:text>
+        </xsl:attribute>
+      </xsl:if>
       <!-- label is from the "exercise" -->
       <xsl:apply-templates select="." mode="runestone-manifest-label"/>
       <!-- Duplicate, but still should look like original (ID, etc.),  -->
       <!-- not knowled. Solutions are available in the originals, via  -->
       <!-- an "in context" link off the Assignment page                -->
       <htmlsrc>
         <xsl:apply-templates select="." mode="exercise-components">
```

### Comparing `pretext-1.6.1.dev20230627/pretext/generate.py` & `pretext-1.6.1.dev20230628/pretext/generate.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/project.py` & `pretext-1.6.1.dev20230628/pretext/project.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/templates/__init__.py` & `pretext-1.6.1.dev20230628/pretext/templates/__init__.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/templates/resources/.gitignore` & `pretext-1.6.1.dev20230628/pretext/templates/resources/.gitignore`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/templates/resources/article.zip` & `pretext-1.6.1.dev20230628/pretext/templates/resources/article.zip`

 * *Files 3% similar despite different names*

#### zipinfo {}

```diff
@@ -1,16 +1,16 @@
 Zip file size: 160110 bytes, number of entries: 14
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 .devcontainer/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 assets/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 publication/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 source/
--rw-r--r--  2.0 unx     1710 b- defN 23-Jun-27 06:16 project.ptx
--rw-r--r--  2.0 unx       86 b- defN 23-Jun-27 06:15 README.md
--rw-r--r--  2.0 unx     1676 b- defN 23-Jun-27 06:16 .gitignore
--rw-r--r--  2.0 unx     2268 b- defN 23-Jun-27 06:16 codechat_config.yaml
--rw-r--r--  2.0 unx     2192 b- defN 23-Jun-27 06:16 .devcontainer/devcontainer.json
--rw-r--r--  2.0 unx   154806 b- defN 23-Jun-27 06:15 assets/frog.jpg
--rw-r--r--  2.0 unx      449 b- defN 23-Jun-27 06:15 source/section-1.ptx
--rw-r--r--  2.0 unx      982 b- defN 23-Jun-27 06:15 source/section-2.ptx
--rw-r--r--  2.0 unx      430 b- defN 23-Jun-27 06:15 source/main.ptx
--rw-r--r--  2.0 unx      242 b- defN 23-Jun-27 06:15 publication/publication.ptx
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 .devcontainer/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 assets/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 publication/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 source/
+-rw-r--r--  2.0 unx     1710 b- defN 23-Jun-28 06:15 project.ptx
+-rw-r--r--  2.0 unx       86 b- defN 23-Jun-28 06:14 README.md
+-rw-r--r--  2.0 unx     1676 b- defN 23-Jun-28 06:15 .gitignore
+-rw-r--r--  2.0 unx     2268 b- defN 23-Jun-28 06:15 codechat_config.yaml
+-rw-r--r--  2.0 unx     2192 b- defN 23-Jun-28 06:15 .devcontainer/devcontainer.json
+-rw-r--r--  2.0 unx   154806 b- defN 23-Jun-28 06:14 assets/frog.jpg
+-rw-r--r--  2.0 unx      449 b- defN 23-Jun-28 06:14 source/section-1.ptx
+-rw-r--r--  2.0 unx      982 b- defN 23-Jun-28 06:14 source/section-2.ptx
+-rw-r--r--  2.0 unx      430 b- defN 23-Jun-28 06:14 source/main.ptx
+-rw-r--r--  2.0 unx      242 b- defN 23-Jun-28 06:14 publication/publication.ptx
 14 files, 164841 bytes uncompressed, 158588 bytes compressed:  3.8%
```

### Comparing `pretext-1.6.1.dev20230627/pretext/templates/resources/book.zip` & `pretext-1.6.1.dev20230628/pretext/templates/resources/book.zip`

 * *Files 19% similar despite different names*

#### zipinfo {}

```diff
@@ -1,12 +1,12 @@
 Zip file size: 7616 bytes, number of entries: 10
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 .devcontainer/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 publication/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 source/
--rw-r--r--  2.0 unx     1710 b- defN 23-Jun-27 06:16 project.ptx
--rw-r--r--  2.0 unx       82 b- defN 23-Jun-27 06:15 README.md
--rw-r--r--  2.0 unx     1676 b- defN 23-Jun-27 06:16 .gitignore
--rw-r--r--  2.0 unx     2268 b- defN 23-Jun-27 06:16 codechat_config.yaml
--rw-r--r--  2.0 unx     2192 b- defN 23-Jun-27 06:16 .devcontainer/devcontainer.json
--rw-r--r--  2.0 unx     1767 b- defN 23-Jun-27 06:15 source/main.ptx
--rw-r--r--  2.0 unx     6114 b- defN 23-Jun-27 06:15 publication/publication.ptx
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 .devcontainer/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 publication/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 source/
+-rw-r--r--  2.0 unx     1710 b- defN 23-Jun-28 06:15 project.ptx
+-rw-r--r--  2.0 unx       82 b- defN 23-Jun-28 06:14 README.md
+-rw-r--r--  2.0 unx     1676 b- defN 23-Jun-28 06:15 .gitignore
+-rw-r--r--  2.0 unx     2268 b- defN 23-Jun-28 06:15 codechat_config.yaml
+-rw-r--r--  2.0 unx     2192 b- defN 23-Jun-28 06:15 .devcontainer/devcontainer.json
+-rw-r--r--  2.0 unx     1767 b- defN 23-Jun-28 06:14 source/main.ptx
+-rw-r--r--  2.0 unx     6114 b- defN 23-Jun-28 06:14 publication/publication.ptx
 10 files, 15809 bytes uncompressed, 6522 bytes compressed:  58.7%
```

### Comparing `pretext-1.6.1.dev20230627/pretext/templates/resources/demo.zip` & `pretext-1.6.1.dev20230628/pretext/templates/resources/demo.zip`

 * *Files 5% similar despite different names*

#### zipinfo {}

```diff
@@ -1,36 +1,36 @@
 Zip file size: 173309 bytes, number of entries: 34
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 .devcontainer/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 assets/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 publication/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 source/
--rw-r--r--  2.0 unx     1710 b- defN 23-Jun-27 06:16 project.ptx
--rw-r--r--  2.0 unx       82 b- defN 23-Jun-27 06:15 README.md
--rw-r--r--  2.0 unx     1676 b- defN 23-Jun-27 06:16 .gitignore
--rw-r--r--  2.0 unx     2268 b- defN 23-Jun-27 06:16 codechat_config.yaml
--rw-r--r--  2.0 unx     2192 b- defN 23-Jun-27 06:16 .devcontainer/devcontainer.json
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 assets/jsxgraph/
--rw-r--r--  2.0 unx   154806 b- defN 23-Jun-27 06:15 assets/frog.jpg
--rw-r--r--  2.0 unx     1737 b- defN 23-Jun-27 06:15 assets/jsxgraph/infinity.js
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 source/images/
--rw-r--r--  2.0 unx     1515 b- defN 23-Jun-27 06:15 source/ex-first.ptx
--rw-r--r--  2.0 unx     1115 b- defN 23-Jun-27 06:15 source/ch-first with spaces.ptx
--rw-r--r--  2.0 unx      230 b- defN 23-Jun-27 06:15 source/ch-empty.ptx
--rw-r--r--  2.0 unx      411 b- defN 23-Jun-27 06:15 source/fig-sage3d.ptx
--rw-r--r--  2.0 unx     2080 b- defN 23-Jun-27 06:15 source/frontmatter.ptx
--rw-r--r--  2.0 unx     1697 b- defN 23-Jun-27 06:15 source/sec-first-examples.ptx
--rw-r--r--  2.0 unx      335 b- defN 23-Jun-27 06:15 source/fig-asymptote.ptx
--rw-r--r--  2.0 unx      867 b- defN 23-Jun-27 06:15 source/sec-features.ptx
--rw-r--r--  2.0 unx      381 b- defN 23-Jun-27 06:15 source/fig-tikz.ptx
--rw-r--r--  2.0 unx     3036 b- defN 23-Jun-27 06:15 source/ch-generate.ptx
--rw-r--r--  2.0 unx      339 b- defN 23-Jun-27 06:15 source/ch-features.ptx
--rw-r--r--  2.0 unx     1616 b- defN 23-Jun-27 06:15 source/docinfo.ptx
--rw-r--r--  2.0 unx      847 b- defN 23-Jun-27 06:15 source/sec-first-intro.ptx
--rw-r--r--  2.0 unx     2517 b- defN 23-Jun-27 06:15 source/main.ptx
--rw-r--r--  2.0 unx      375 b- defN 23-Jun-27 06:15 source/fig-sage2d.ptx
--rw-r--r--  2.0 unx      885 b- defN 23-Jun-27 06:15 source/backmatter.ptx
--rw-r--r--  2.0 unx      835 b- defN 23-Jun-27 06:15 source/images/cflag.asy
--rw-r--r--  2.0 unx       10 b- defN 23-Jun-27 06:15 source/images/sageplot2d.sage
--rw-r--r--  2.0 unx       93 b- defN 23-Jun-27 06:15 source/images/sageplot3d.sage
--rw-r--r--  2.0 unx      357 b- defN 23-Jun-27 06:15 source/images/tikz.tex
--rw-r--r--  2.0 unx     6092 b- defN 23-Jun-27 06:15 publication/publication.ptx
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 .devcontainer/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 assets/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 publication/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 source/
+-rw-r--r--  2.0 unx     1710 b- defN 23-Jun-28 06:15 project.ptx
+-rw-r--r--  2.0 unx       82 b- defN 23-Jun-28 06:14 README.md
+-rw-r--r--  2.0 unx     1676 b- defN 23-Jun-28 06:15 .gitignore
+-rw-r--r--  2.0 unx     2268 b- defN 23-Jun-28 06:15 codechat_config.yaml
+-rw-r--r--  2.0 unx     2192 b- defN 23-Jun-28 06:15 .devcontainer/devcontainer.json
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 assets/jsxgraph/
+-rw-r--r--  2.0 unx   154806 b- defN 23-Jun-28 06:14 assets/frog.jpg
+-rw-r--r--  2.0 unx     1737 b- defN 23-Jun-28 06:14 assets/jsxgraph/infinity.js
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 source/images/
+-rw-r--r--  2.0 unx     1515 b- defN 23-Jun-28 06:14 source/ex-first.ptx
+-rw-r--r--  2.0 unx     1115 b- defN 23-Jun-28 06:14 source/ch-first with spaces.ptx
+-rw-r--r--  2.0 unx      230 b- defN 23-Jun-28 06:14 source/ch-empty.ptx
+-rw-r--r--  2.0 unx      411 b- defN 23-Jun-28 06:14 source/fig-sage3d.ptx
+-rw-r--r--  2.0 unx     2080 b- defN 23-Jun-28 06:14 source/frontmatter.ptx
+-rw-r--r--  2.0 unx     1697 b- defN 23-Jun-28 06:14 source/sec-first-examples.ptx
+-rw-r--r--  2.0 unx      335 b- defN 23-Jun-28 06:14 source/fig-asymptote.ptx
+-rw-r--r--  2.0 unx      867 b- defN 23-Jun-28 06:14 source/sec-features.ptx
+-rw-r--r--  2.0 unx      381 b- defN 23-Jun-28 06:14 source/fig-tikz.ptx
+-rw-r--r--  2.0 unx     3036 b- defN 23-Jun-28 06:14 source/ch-generate.ptx
+-rw-r--r--  2.0 unx      339 b- defN 23-Jun-28 06:14 source/ch-features.ptx
+-rw-r--r--  2.0 unx     1616 b- defN 23-Jun-28 06:14 source/docinfo.ptx
+-rw-r--r--  2.0 unx      847 b- defN 23-Jun-28 06:14 source/sec-first-intro.ptx
+-rw-r--r--  2.0 unx     2517 b- defN 23-Jun-28 06:14 source/main.ptx
+-rw-r--r--  2.0 unx      375 b- defN 23-Jun-28 06:14 source/fig-sage2d.ptx
+-rw-r--r--  2.0 unx      885 b- defN 23-Jun-28 06:14 source/backmatter.ptx
+-rw-r--r--  2.0 unx      835 b- defN 23-Jun-28 06:14 source/images/cflag.asy
+-rw-r--r--  2.0 unx       10 b- defN 23-Jun-28 06:14 source/images/sageplot2d.sage
+-rw-r--r--  2.0 unx       93 b- defN 23-Jun-28 06:14 source/images/sageplot3d.sage
+-rw-r--r--  2.0 unx      357 b- defN 23-Jun-28 06:14 source/images/tikz.tex
+-rw-r--r--  2.0 unx     6092 b- defN 23-Jun-28 06:14 publication/publication.ptx
 34 files, 190104 bytes uncompressed, 169353 bytes compressed:  10.9%
```

### Comparing `pretext-1.6.1.dev20230627/pretext/templates/resources/devcontainer.json` & `pretext-1.6.1.dev20230628/pretext/templates/resources/devcontainer.json`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/templates/resources/hello.zip` & `pretext-1.6.1.dev20230628/pretext/templates/resources/hello.zip`

 * *Files 10% similar despite different names*

#### zipinfo {}

```diff
@@ -1,12 +1,12 @@
 Zip file size: 4657 bytes, number of entries: 10
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 .devcontainer/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 publication/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 source/
--rw-r--r--  2.0 unx     1217 b- defN 23-Jun-27 06:15 project.ptx
--rw-r--r--  2.0 unx       69 b- defN 23-Jun-27 06:15 README.md
--rw-r--r--  2.0 unx     1676 b- defN 23-Jun-27 06:16 .gitignore
--rw-r--r--  2.0 unx     2268 b- defN 23-Jun-27 06:16 codechat_config.yaml
--rw-r--r--  2.0 unx     2192 b- defN 23-Jun-27 06:16 .devcontainer/devcontainer.json
--rw-r--r--  2.0 unx      156 b- defN 23-Jun-27 06:15 source/main.ptx
--rw-r--r--  2.0 unx      242 b- defN 23-Jun-27 06:15 publication/publication.ptx
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 .devcontainer/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 publication/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 source/
+-rw-r--r--  2.0 unx     1217 b- defN 23-Jun-28 06:14 project.ptx
+-rw-r--r--  2.0 unx       69 b- defN 23-Jun-28 06:14 README.md
+-rw-r--r--  2.0 unx     1676 b- defN 23-Jun-28 06:15 .gitignore
+-rw-r--r--  2.0 unx     2268 b- defN 23-Jun-28 06:15 codechat_config.yaml
+-rw-r--r--  2.0 unx     2192 b- defN 23-Jun-28 06:15 .devcontainer/devcontainer.json
+-rw-r--r--  2.0 unx      156 b- defN 23-Jun-28 06:14 source/main.ptx
+-rw-r--r--  2.0 unx      242 b- defN 23-Jun-28 06:14 publication/publication.ptx
 10 files, 7820 bytes uncompressed, 3563 bytes compressed:  54.4%
```

### Comparing `pretext-1.6.1.dev20230627/pretext/templates/resources/project.ptx` & `pretext-1.6.1.dev20230628/pretext/templates/resources/project.ptx`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pretext/templates/resources/slideshow.zip` & `pretext-1.6.1.dev20230628/pretext/templates/resources/slideshow.zip`

 * *Files 10% similar despite different names*

#### zipinfo {}

```diff
@@ -1,13 +1,13 @@
 Zip file size: 8392 bytes, number of entries: 11
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:16 .devcontainer/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 publication/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 source/
-drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-27 06:15 xsl/
--rw-r--r--  2.0 unx      784 b- defN 23-Jun-27 06:15 project.ptx
--rw-r--r--  2.0 unx     1676 b- defN 23-Jun-27 06:16 .gitignore
--rw-r--r--  2.0 unx     2268 b- defN 23-Jun-27 06:16 codechat_config.yaml
--rw-r--r--  2.0 unx     2192 b- defN 23-Jun-27 06:16 .devcontainer/devcontainer.json
--rw-r--r--  2.0 unx      190 b- defN 23-Jun-27 06:15 xsl/slides.xsl
--rw-r--r--  2.0 unx    11200 b- defN 23-Jun-27 06:15 source/main.ptx
--rw-r--r--  2.0 unx     2097 b- defN 23-Jun-27 06:15 publication/publication.ptx
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:15 .devcontainer/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 publication/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 source/
+drwxr-xr-x  2.0 unx        0 b- stor 23-Jun-28 06:14 xsl/
+-rw-r--r--  2.0 unx      784 b- defN 23-Jun-28 06:14 project.ptx
+-rw-r--r--  2.0 unx     1676 b- defN 23-Jun-28 06:15 .gitignore
+-rw-r--r--  2.0 unx     2268 b- defN 23-Jun-28 06:15 codechat_config.yaml
+-rw-r--r--  2.0 unx     2192 b- defN 23-Jun-28 06:15 .devcontainer/devcontainer.json
+-rw-r--r--  2.0 unx      190 b- defN 23-Jun-28 06:14 xsl/slides.xsl
+-rw-r--r--  2.0 unx    11200 b- defN 23-Jun-28 06:14 source/main.ptx
+-rw-r--r--  2.0 unx     2097 b- defN 23-Jun-28 06:14 publication/publication.ptx
 11 files, 20407 bytes uncompressed, 7204 bytes compressed:  64.7%
```

### Comparing `pretext-1.6.1.dev20230627/pretext/utils.py` & `pretext-1.6.1.dev20230628/pretext/utils.py`

 * *Files identical despite different names*

### Comparing `pretext-1.6.1.dev20230627/pyproject.toml` & `pretext-1.6.1.dev20230628/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 # See https://python-poetry.org/docs/dependency-specification/ to get an understanding of
 # how poetry specifies dependencies.
 #
 # Project metadata
 # ----------------
 [tool.poetry]
 name = "pretext"
-version = "1.6.1.dev20230627"
+version = "1.6.1.dev20230628"
 description = "A package to author, build, and deploy PreTeXt projects."
 readme = "README.md"
 homepage = "https://pretextbook.org"
 repository = "https://github.com/PreTeXtBook/pretext-cli"
 authors = ["Oscar Levin <oscar.levin@unco.edu>", "Steven Clontz <steven.clontz@gmail.com>",]
 license = "GPL-3.0-or-later"
 include = [
```

### Comparing `pretext-1.6.1.dev20230627/PKG-INFO` & `pretext-1.6.1.dev20230628/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pretext
-Version: 1.6.1.dev20230627
+Version: 1.6.1.dev20230628
 Summary: A package to author, build, and deploy PreTeXt projects.
 Home-page: https://pretextbook.org
 License: GPL-3.0-or-later
 Author: Oscar Levin
 Author-email: oscar.levin@unco.edu
 Requires-Python: >=3.8.5,<4.0.0
 Classifier: License :: OSI Approved :: GNU General Public License v3 or later (GPLv3+)
```


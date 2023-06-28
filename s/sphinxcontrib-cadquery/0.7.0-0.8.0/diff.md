# Comparing `tmp/sphinxcontrib_cadquery-0.7.0.tar.gz` & `tmp/sphinxcontrib_cadquery-0.8.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sphinxcontrib_cadquery-0.7.0.tar", max compression
+gzip compressed data, was "sphinxcontrib_cadquery-0.8.0.tar", max compression
```

## Comparing `sphinxcontrib_cadquery-0.7.0.tar` & `sphinxcontrib_cadquery-0.8.0.tar`

### file list

```diff
@@ -1,15 +1,20 @@
--rw-r--r--   0        0        0     1302 2023-05-28 09:40:53.827492 sphinxcontrib_cadquery-0.7.0/CHANGELOG.md
--rw-r--r--   0        0        0      611 2023-01-05 04:01:57.599868 sphinxcontrib_cadquery-0.7.0/LICENSE
--rw-r--r--   0        0        0     1490 2023-01-05 04:03:49.236254 sphinxcontrib_cadquery-0.7.0/LICENSE.vtk-js
--rw-r--r--   0        0        0     1161 2023-05-27 22:41:49.419150 sphinxcontrib_cadquery-0.7.0/README.rst
--rw-r--r--   0        0        0     2743 2023-05-28 09:40:12.659533 sphinxcontrib_cadquery-0.7.0/pyproject.toml
--rw-r--r--   0        0        0     1975 2023-05-28 09:40:12.639533 sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/__init__.py
--rw-r--r--   0        0        0     6465 2023-05-27 22:41:49.423150 sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/cq_core.py
--rw-r--r--   0        0        0      882 2023-05-27 22:41:49.423150 sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/option_converters.py
--rw-r--r--   0        0        0     1317 2023-05-07 00:57:15.044268 sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/static/cadquery.css
--rw-r--r--   0        0        0  2305881 2023-05-27 23:41:34.519895 sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/static/dist/vtk-lite.js
--rw-r--r--   0        0        0       66 2023-01-05 11:41:56.759400 sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/static/dist/vtk-lite.js.LICENSE.txt
--rw-r--r--   0        0        0     4845 2023-05-27 05:46:34.942578 sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/static/render.js
--rw-r--r--   0        0        0      653 2023-03-05 00:20:28.997334 sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/templates/svg.rst.jinja
--rw-r--r--   0        0        0     1278 2023-05-07 00:57:15.044268 sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/templates/vtk.rst.jinja
--rw-r--r--   0        0        0     2861 1970-01-01 00:00:00.000000 sphinxcontrib_cadquery-0.7.0/PKG-INFO
+-rw-r--r--   0        0        0     1810 2023-06-28 09:45:17.172306 sphinxcontrib_cadquery-0.8.0/CHANGELOG.md
+-rw-r--r--   0        0        0      611 2023-01-05 04:01:57.599868 sphinxcontrib_cadquery-0.8.0/LICENSE
+-rw-r--r--   0        0        0     1490 2023-01-05 04:03:49.236254 sphinxcontrib_cadquery-0.8.0/LICENSE.vtk-js
+-rw-r--r--   0        0        0     1121 2023-06-10 01:06:41.200783 sphinxcontrib_cadquery-0.8.0/README.rst
+-rw-r--r--   0        0        0     2751 2023-06-28 09:44:58.672232 sphinxcontrib_cadquery-0.8.0/pyproject.toml
+-rw-r--r--   0        0        0     2128 2023-06-28 09:44:58.628232 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/__init__.py
+-rw-r--r--   0        0        0       60 2023-06-03 23:50:32.611640 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/common.py
+-rw-r--r--   0        0        0     5329 2023-06-27 04:59:24.290899 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/cq_core.py
+-rw-r--r--   0        0        0     2488 2023-06-25 09:24:39.172787 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/cqgi.py
+-rw-r--r--   0        0        0    12699 2023-06-27 04:51:49.566949 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/domain.py
+-rw-r--r--   0        0        0     1191 2023-06-26 05:49:50.320550 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/option_converters.py
+-rw-r--r--   0        0        0     1631 2023-06-26 05:32:16.262509 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/static/cadquery.css
+-rw-r--r--   0        0        0  2305881 2023-05-27 23:41:34.519895 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/static/dist/vtk-lite.js
+-rw-r--r--   0        0        0       66 2023-01-05 11:41:56.759400 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/static/dist/vtk-lite.js.LICENSE.txt
+-rw-r--r--   0        0        0     4845 2023-06-12 06:37:52.294968 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/static/render.js
+-rw-r--r--   0        0        0      650 2023-06-26 05:32:16.262509 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/templates/cadquery-svg.rst.jinja
+-rw-r--r--   0        0        0     1275 2023-06-26 05:32:16.262509 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/templates/cadquery-vtk.rst.jinja
+-rw-r--r--   0        0        0      215 2023-06-26 05:32:16.262509 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/templates/svg-overlay.html.jinja
+-rw-r--r--   0        0        0      707 2023-06-26 05:32:16.262509 sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/templates/vtk-container.html.jinja
+-rw-r--r--   0        0        0     2680 1970-01-01 00:00:00.000000 sphinxcontrib_cadquery-0.8.0/PKG-INFO
```

### Comparing `sphinxcontrib_cadquery-0.7.0/CHANGELOG.md` & `sphinxcontrib_cadquery-0.8.0/CHANGELOG.md`

 * *Files 7% similar despite different names*

```diff
@@ -1,7 +1,29 @@
+## 0.8.0 (2023-06-28)
+
+### Feat
+
+- cadquery:svg help dropdown
+- add option inline-uri to cadquery:svg
+- cadquery:svg directive
+- cadquery:vtk directive
+- stable api for cadquery-{vtk,svg}, cadquery, cq_plot
+
+### Refactor
+
+- use pathlib as_posix()
+- fix shadow name from outer scope
+- rename help widget to overlay
+- make cqgi.cqgi_parse public
+- inherit from shphinxdirective
+- reduce complexity
+- extract figure node assembly
+- move vtk json exporter to cqgi module
+- move cqgi class to independent module
+
 ## 0.7.0 (2023-05-28)
 
 ### Feat
 
 - upgrade vtk.js to 28.2.0
 - add option color to cadquery-vtk directive
```

### Comparing `sphinxcontrib_cadquery-0.7.0/LICENSE` & `sphinxcontrib_cadquery-0.8.0/LICENSE`

 * *Files identical despite different names*

### Comparing `sphinxcontrib_cadquery-0.7.0/LICENSE.vtk-js` & `sphinxcontrib_cadquery-0.8.0/LICENSE.vtk-js`

 * *Files identical despite different names*

### Comparing `sphinxcontrib_cadquery-0.7.0/README.rst` & `sphinxcontrib_cadquery-0.8.0/README.rst`

 * *Files 18% similar despite different names*

```diff
@@ -3,15 +3,14 @@
 ======================
 
 |pypi-version| |lint-status| |test-status| |docs-status|
 
 
 A `Sphinx`_ extension for rendering `CadQuery`_ models.
 
-**Development Status :: 2 - Pre-Alpha**
 
 .. _Sphinx: https://www.sphinx-doc.org/
 .. _CadQuery: https://cadquery.readthedocs.io/
 
 
 .. |pypi-version| image:: https://img.shields.io/pypi/v/sphinxcontrib-cadquery
     :target: https://pypi.org/project/sphinxcontrib-cadquery/
```

### Comparing `sphinxcontrib_cadquery-0.7.0/pyproject.toml` & `sphinxcontrib_cadquery-0.8.0/pyproject.toml`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "sphinxcontrib-cadquery"
-version = "0.7.0"
+version = "0.8.0"
 description = "Sphinx extension for rendering CadQuery models."
 packages = [
     {include = "sphinxcontrib"},
 ]
 include = [
     "CHANGELOG.md",
     "sphinxcontrib/cadquery/static/dist/vtk-lite.js*",
@@ -25,15 +25,15 @@
     "programmatic",
     "sphinx",
     "svg",
     "vtk",
     "vtk.js",
 ]
 classifiers = [
-    "Development Status :: 2 - Pre-Alpha",
+    "Development Status :: 5 - Production/Stable",
     "Environment :: Console",
     "Environment :: Web Environment",
     "Framework :: Sphinx :: Extension",
     "Framework :: Sphinx",
     "Intended Audience :: Developers",
     "Intended Audience :: Science/Research",
     "License :: OSI Approved :: Apache Software License",
@@ -82,15 +82,15 @@
 logbook = "^1.5.3"
 pyqt5 = "^5.15.7"
 pyqtgraph = "^0.13.1"
 spyder = "^5.4.1"
 
 [tool.commitizen]
 name = "cz_conventional_commits"
-version = "0.7.0"
+version = "0.8.0"
 major_version_zero = true
 tag_format = "$version"
 annotated_tag = true
 version_files = [
     "pyproject.toml",
     "sphinxcontrib/cadquery/__init__.py",
 ]
```

### Comparing `sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/__init__.py` & `sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/__init__.py`

 * *Files 9% similar despite different names*

```diff
@@ -8,16 +8,17 @@
 
 from .cq_core import (
     CqSvgDirective,
     CqVtkDirective,
     LegacyCqSvgDirective,
     LegacyCqVtkDirective,
 )
+from .domain import CadQueryDomain, set_svg_image_uri
 
-__version__ = "0.7.0"
+__version__ = "0.8.0"
 
 _ROOT_DIR = Path(__file__).absolute().parent
 
 _JS_FILES = {
     "static/dist/vtk-lite.js": {"priority": 90},
     "static/render.js": {"priority": 100},
 }
@@ -39,26 +40,29 @@
         app_outdir_dist.mkdir(parents=True, exist_ok=True)
 
         for filename, metadata in _JS_FILES.items():
             js_source = _ROOT_DIR / filename
             js_destination = app_outdir_dist / Path(filename).name
 
             app.add_js_file(
-                str(js_destination.relative_to(app_static_directory)),
+                js_destination.relative_to(app_static_directory).as_posix(),
                 priority=metadata["priority"],
             )
 
             shutil.copyfile(js_source, js_destination)
 
         css_destination = app_static_directory / "cadquery.css"
-        app.add_css_file(str(css_destination.relative_to(app_static_directory)))
+        app.add_css_file(css_destination.relative_to(app_static_directory).as_posix())
         shutil.copyfile(_ROOT_DIR / "static/cadquery.css", css_destination)
 
         setattr(app, "_sphinxcontrib_cadquery_assets_installed", True)
 
+    app.add_domain(CadQueryDomain)
+    app.connect("doctree-read", set_svg_image_uri)
+
     app.add_directive("cadquery-svg", CqSvgDirective)
     app.add_directive("cadquery-vtk", CqVtkDirective)
 
     app.add_directive("cq_plot", LegacyCqSvgDirective)  # deprecated, use cadquery-svg
     app.add_directive("cadquery", LegacyCqVtkDirective)  # deprecated, use cadquery-vtk
 
     app.add_config_value("cadquery_include_source", True, "env")
```

### Comparing `sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/cq_core.py` & `sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/cq_core.py`

 * *Files 21% similar despite different names*

```diff
@@ -8,202 +8,165 @@
 SPDX-FileContributor: Adam Urbańczyk <adam.jan.urbanczyk@gmail.com>
 SPDX-FileContributor: Dave Cowden <dave.cowden@gmail.com>
 SPDX-FileContributor: Marcus Boyd <mwb@geosol.com.au>
 SPDX-FileContributor: Miguel Sánchez de León Peque <peque@neosit.es>
 SPDX-FileContributor: Seth Fischer <seth@fischer.nz>
 """
 
-from json import dumps
 from pathlib import Path
+from typing import Any
 
-from cadquery import Assembly, Color, Sketch, cqgi, exporters
-from cadquery.occ_impl.assembly import toJSON as cq_assembly_toJSON
+from cadquery import exporters
 from docutils import nodes
-from docutils.parsers.rst import Directive, directives
+from docutils.parsers.rst import directives
 from jinja2 import Environment, PackageLoader, select_autoescape
 from sphinx.util import logging
+from sphinx.util.docutils import SphinxDirective
 
+from .common import DEFAULT_COLOR
+from .cqgi import Cqgi, VtkJsonExporter
 from .option_converters import rgba
 
 logger = logging.getLogger(__name__)
 
-DEFAULT_COLOR = [1, 0.8, 0, 1]
-
 _JINJA_ENV = Environment(
     loader=PackageLoader("sphinxcontrib.cadquery"),
     autoescape=select_autoescape(),
 )
 
 
-class Cqgi:
-    """Execute script source using CQGI."""
-
-    @staticmethod
-    def _cqgi_parse(script_source: str):
-        """Execute script source using CQGI."""
-        result = cqgi.parse(script_source).build()
-
-        if not result.success:
-            raise result.exception
-
-        return result
-
-
-class CqSvgDirective(Directive, Cqgi):
+class CqSvgDirective(SphinxDirective, Cqgi):
     """CadQuery SVG directive."""
 
     has_content = True
     required_arguments = 0
     optional_arguments = 0
     option_spec = {}  # type: ignore[var-annotated]
 
-    def run(self):
+    def run(self) -> list[Any]:
         """Generate SVG render of CadQuery model."""
-        content = self.content
-        state_machine = self.state_machine
-        env = self.state.document.settings.env
 
         self.assert_has_content()
-        script_source = "\n".join(content)
+        script_source = "\n".join(self.content)
 
         try:
-            result = self._cqgi_parse(script_source)
+            result = self.cqgi_parse(script_source)
         except Exception as err:
             message = f"CQGI error in {self.name} directive: {err}."
             p = nodes.paragraph("", "", nodes.Text(message))
-            state_machine.reporter.error(message)
+            self.state_machine.reporter.error(message)
             return [p]
 
         try:
             compound = exporters.toCompound(result.first_result.shape)
         except AttributeError as err:
             raise self.error(
                 f"{err} Does your script source include a call to `show_object()`?"
             )
 
         svg_document = exporters.getSVG(compound)
 
-        rst_markup = _JINJA_ENV.get_template("svg.rst.jinja").render(
-            include_source=env.config.cadquery_include_source,
+        rst_markup = _JINJA_ENV.get_template("cadquery-svg.rst.jinja").render(
+            include_source=self.config.cadquery_include_source,
             script_source=script_source,
             svg_document=svg_document,
         )
 
-        state_machine.insert_input(
-            rst_markup.splitlines(), state_machine.input_lines.source(0)
+        self.state_machine.insert_input(
+            rst_markup.splitlines(), self.state_machine.input_lines.source(0)
         )
 
         return []
 
 
-class CqVtkDirective(Directive, Cqgi):
+class CqVtkDirective(SphinxDirective, Cqgi):
     """CadQuery VTK directive."""
 
     has_content = True
     required_arguments = 0
     optional_arguments = 1
     option_spec = {
         "align": directives.unchanged,
         "color": rgba,
         "height": directives.length_or_unitless,
         "select": directives.unchanged,
         "width": directives.length_or_percentage_or_unitless,
     }
 
-    def run(self):
+    def run(self) -> list[Any]:
         """Generate VTK render of CadQuery model."""
+
         options = self.options
-        state_machine = self.state_machine
-        env = self.state.document.settings.env
 
         script_source = self._script_source()
 
         try:
-            result = self._cqgi_parse(script_source)
+            result = self.cqgi_parse(script_source)
         except Exception as err:
             message = f"CQGI error in {self.name} directive: {err}."
             p = nodes.paragraph("", "", nodes.Text(message))
-            state_machine.reporter.error(message)
+            self.state_machine.reporter.error(message)
             return [p]
 
         color = options.get("color", DEFAULT_COLOR)
-        shape = self._select_shape(result, options.get("select", "result"))
-        assembly = self._to_assembly(shape, color=color)
-        vtk_json = dumps(cq_assembly_toJSON(assembly), separators=(",", ":"))
+        vtk_json = VtkJsonExporter(result, options.get("select", "result"))
 
-        rst_markup = _JINJA_ENV.get_template("vtk.rst.jinja").render(
-            include_source=env.config.cadquery_include_source,
+        rst_markup = _JINJA_ENV.get_template("cadquery-vtk.rst.jinja").render(
+            include_source=self.config.cadquery_include_source,
             script_source=script_source,
-            vtk_json=vtk_json,
+            vtk_json=vtk_json(color=color),
             element="document.currentScript.parentNode",
             align=options.get("align", "none"),
             width=options.get("width", "100%"),
             height=options.get("height", "500px"),
         )
 
-        state_machine.insert_input(
-            rst_markup.splitlines(), state_machine.input_lines.source(0)
+        self.state_machine.insert_input(
+            rst_markup.splitlines(), self.state_machine.input_lines.source(0)
         )
 
         return []
 
     def _script_source(self):
         """Get script source."""
-        env = self.state.document.settings.env
 
         if len(self.arguments):
-            path_name = Path(env.app.builder.srcdir) / self.arguments[0]
+            path_name = Path(self.env.app.builder.srcdir) / self.arguments[0]
             path_name = path_name.resolve()
             if not path_name.is_file():
                 logger.error(f"File does not exist: {path_name}")
 
             return path_name.read_text()
 
         if not self.content:
             raise self.error(
                 f"{self.name} Expected script source as content"
                 " as path name not provided as first argument."
             )
 
         return "\n".join(self.content)
 
-    @staticmethod
-    def _select_shape(result, select: str):
-        """Select shape from CQGI environment."""
-        if result.first_result:
-            return result.first_result.shape
-
-        return result.env[select]
-
-    @staticmethod
-    def _to_assembly(shape, color: list[float]):
-        """Convert shape to assembly."""
-        if isinstance(shape, Assembly):
-            return shape
-        elif isinstance(shape, Sketch):
-            return Assembly(shape._faces, color=Color(*color))
-
-        return Assembly(shape, color=Color(*color))
-
 
 class LegacyCqSvgDirective(CqSvgDirective):
     """Legacy SVG directive."""
 
-    def run(self):
+    def run(self) -> list[Any]:
         """Deprecate legacy SVG directive."""
+
         logger.info(
             "use of the cq_plot directive is deprecated, "
             'replace ".. cq_plot::" with ".. cadquery-svg::"'
         )
         return super().run()
 
 
 class LegacyCqVtkDirective(CqVtkDirective):
     """Legacy VTK directive."""
 
-    def run(self):
+    def run(self) -> list[Any]:
         """Deprecate legacy VTK directive."""
+
         logger.info(
             "direct use of the cadquery directive is deprecated, "
             'replace ".. cadquery::" with ".. cadquery-vtk::"'
         )
         return super().run()
```

### Comparing `sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/static/cadquery.css` & `sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/static/cadquery.css`

 * *Files 19% similar despite different names*

```diff
@@ -12,68 +12,90 @@
 
 .cadquery-align-center {
     margin: 0px auto;
 }
 
 .cadquery-container-model {
     border: 1px solid #ddd;
-    color: white;
     position: relative;
 }
 
 button.cadquery-credit {
     border: 1px;
     color: white;
     cursor: pointer;
     font-size: 75%;
 }
 
-div.cadquery-help-dropdown {
+div.cadquery-overlay {
     color: black;
     float: right;
     margin: 0;
     padding: 0;
     position: absolute;
     right: 16px;
     top: 8px;
     z-index: 100;
 }
 
-.cadquery-help-dropdown-content {
+.cadquery-overlay-dropdown-content {
     background-color: #f9f9f9;
     display: none;
     min-width: 100%;
     position: absolute;
     right: 0;
     z-index: 1;
 }
 
-.cadquery-help-dropdown-content dl,
-.cadquery-help-dropdown-content dl dd,
-.cadquery-help-dropdown-content p {
+.cadquery-overlay-dropdown-content dl,
+.cadquery-overlay-dropdown-content dl dd,
+.cadquery-overlay-dropdown-content p {
     margin: 1px;
 }
-.cadquery-help-dropdown-content p.footer {
+.cadquery-overlay-dropdown-content p.footer {
         font-size: 75%;
 }
 
-.cadquery-help-dropdown:hover
-.cadquery-help-dropdown-content {
+.cadquery-overlay:hover
+.cadquery-overlay-dropdown-content {
     display: block;
 }
 
-.cadquery-help-dropdown:hover button.cadquery-credit {
+.cadquery-overlay:hover button.cadquery-credit {
     background-color: #2980b9;
 }
 
-.cadquery-help-dropdown-content dl {
+.cadquery-overlay-dropdown-content dl {
     display: grid;
     grid-template-columns: 40% auto;
 }
 
-.cadquery-help-dropdown-content dl dt {
+.cadquery-overlay-dropdown-content dl dt {
     grid-column: 1;
 }
 
-.cadquery-help-dropdown-content dl dd {
+.cadquery-overlay-dropdown-content dl dd {
     grid-column: 2;
 }
+
+.cadquery-container {
+    border: 1px solid #ddd;
+    padding: 4px;
+}
+
+.cadquery-container * pre {
+    text-align: left;
+}
+
+figcaption *:last-child,
+figure *:last-child,
+.cadquery-container *:last-child {
+    margin-bottom: 0 !important;
+}
+
+.cadquery-notes * {
+    font-size: small;
+}
+
+.cadquery-error {
+    color: red;
+}
```

### Comparing `sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/static/dist/vtk-lite.js` & `sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/static/dist/vtk-lite.js`

 * *Files identical despite different names*

### Comparing `sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/static/render.js` & `sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/static/render.js`

 * *Files identical despite different names*

### Comparing `sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/templates/svg.rst.jinja` & `sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/templates/cadquery-svg.rst.jinja`

 * *Files 22% similar despite different names*

```diff
@@ -1,17 +1,17 @@
 .. raw:: html
 
     <div class="cadquery-container" style="margin-bottom: 24px">
         <div class="cadquery-container-model">
             <div class="cadquery-svg">
                 {{svg_document|indent(8)}}
             </div>
-            <div class="cadquery-help-dropdown">
+            <div class="cadquery-overlay">
                 <button class="cadquery-credit">Modeled with CadQuery</button>
-                <div class="cadquery-help-dropdown-content">
+                <div class="cadquery-overlay-dropdown-content">
                     <p class="footer">Exported as SVG.</p>
                 </div>
             </div>
         </div>
 
 {% if include_source %}
 .. code-block:: python
```

### Comparing `sphinxcontrib_cadquery-0.7.0/sphinxcontrib/cadquery/templates/vtk.rst.jinja` & `sphinxcontrib_cadquery-0.8.0/sphinxcontrib/cadquery/templates/cadquery-vtk.rst.jinja`

 * *Files 2% similar despite different names*

```diff
@@ -5,17 +5,17 @@
             <div class="cadquery-vtk" style="height:{{height}};">
                 <script>
                     var parent_element = {{element}};
                     var data = {{vtk_json}};
                     render(data, parent_element);
                 </script>
             </div>
-            <div class="cadquery-help-dropdown">
+            <div class="cadquery-overlay">
                 <button class="cadquery-credit">Modeled with CadQuery</button>
-                <div class="cadquery-help-dropdown-content">
+                <div class="cadquery-overlay-dropdown-content">
                     <dl>
                         <dt>roll</dt>
                         <dd>MB1</dd>
                         <dt>pan</dt>
                         <dd>MB2</dd>
                         <dt>zoom</dt>
                         <dd>MB3</dd>
```

### Comparing `sphinxcontrib_cadquery-0.7.0/PKG-INFO` & `sphinxcontrib_cadquery-0.8.0/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,35 +1,32 @@
 Metadata-Version: 2.1
 Name: sphinxcontrib-cadquery
-Version: 0.7.0
+Version: 0.8.0
 Summary: Sphinx extension for rendering CadQuery models.
 Home-page: https://github.com/sethfischer/sphinxcontrib-cadquery
 License: Apache-2.0
 Keywords: cad,cadquery,parametric,programmatic,sphinx,svg,vtk,vtk.js
 Author: Seth Fischer
 Author-email: seth@fischer.nz
 Requires-Python: >=3.9,<3.11
-Classifier: Development Status :: 2 - Pre-Alpha
+Classifier: Development Status :: 5 - Production/Stable
 Classifier: Environment :: Console
 Classifier: Environment :: Web Environment
 Classifier: Framework :: Sphinx
 Classifier: Framework :: Sphinx :: Extension
 Classifier: Intended Audience :: Developers
 Classifier: Intended Audience :: Science/Research
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Operating System :: POSIX
 Classifier: Operating System :: Unix
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3 :: Only
-Classifier: Programming Language :: Python :: 3.10
-Classifier: Programming Language :: Python :: 3.9
 Classifier: Topic :: Documentation
 Classifier: Topic :: Documentation :: Sphinx
 Classifier: Topic :: Scientific/Engineering
 Requires-Dist: Sphinx (>=5.3.0,<7.0.0)
 Requires-Dist: ipython (>=7.31.1)
 Requires-Dist: jinja2 (>=3.0)
 Project-URL: Bug Tracker, https://github.com/sethfischer/sphinxcontrib-cadquery/issues
@@ -42,15 +39,14 @@
 ======================
 
 |pypi-version| |lint-status| |test-status| |docs-status|
 
 
 A `Sphinx`_ extension for rendering `CadQuery`_ models.
 
-**Development Status :: 2 - Pre-Alpha**
 
 .. _Sphinx: https://www.sphinx-doc.org/
 .. _CadQuery: https://cadquery.readthedocs.io/
 
 
 .. |pypi-version| image:: https://img.shields.io/pypi/v/sphinxcontrib-cadquery
     :target: https://pypi.org/project/sphinxcontrib-cadquery/
```


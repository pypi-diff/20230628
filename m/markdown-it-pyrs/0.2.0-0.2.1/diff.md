# Comparing `tmp/markdown_it_pyrs-0.2.0.tar.gz` & `tmp/markdown_it_pyrs-0.2.1.tar.gz`

## Comparing `markdown_it_pyrs-0.2.0.tar` & `markdown_it_pyrs-0.2.1.tar`

### file list

```diff
@@ -1,38 +1,38 @@
--rw-r--r--   0        0        0      486 1970-01-01 00:00:00.000000 markdown_it_pyrs-0.2.0/Cargo.toml
--rw-r--r--   0     1001      123      722 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/.github/dependabot.yml
--rw-r--r--   0     1001      123     6016 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/.github/workflows/CI.yml
--rw-r--r--   0     1001      123      696 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/.gitignore
--rw-r--r--   0     1001      123     1001 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/.pre-commit-config.yaml
--rw-r--r--   0     1001      123    11357 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/LICENSE
--rw-r--r--   0     1001      123      554 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/NOTICE
--rw-r--r--   0     1001      123     9563 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/README.md
--rw-r--r--   0     1001      123     1452 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/pyproject.toml
--rw-r--r--   0     1001      123      208 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/python/markdown_it_pyrs/__init__.py
--rw-r--r--   0     1001      123     2365 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/python/markdown_it_pyrs/cli.py
--rw-r--r--   0     1001      123     3614 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/python/markdown_it_pyrs/markdown_it_pyrs.pyi
--rw-r--r--   0     1001      123        0 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/python/markdown_it_pyrs/py.typed
--rw-r--r--   0     1001      123     8653 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/src/lib.rs
--rw-r--r--   0     1001      123    16310 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/src/nodes.rs
--rw-r--r--   0     1001      123      693 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/bench_html.py
--rw-r--r--   0     1001      123      838 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/bench_tree.py
--rw-r--r--   0     1001      123     3412 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/ast.md
--rw-r--r--   0     1001      123     6483 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/autolink_ext.md
--rw-r--r--   0     1001      123     8424 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/commonmark_extras.md
--rw-r--r--   0     1001      123   150858 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/commonmark_spec.json
--rw-r--r--   0     1001      123     8323 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/footnote.md
--rw-r--r--   0     1001      123      791 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/front_matter.md
--rw-r--r--   0     1001      123     3909 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/linkify.md
--rw-r--r--   0     1001      123      817 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/normalize.md
--rw-r--r--   0     1001      123     2639 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/smartquotes.md
--rw-r--r--   0     1001      123      512 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/sourcepos.md
--rw-r--r--   0     1001      123   202694 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/spec.md
--rw-r--r--   0     1001      123     1562 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/strikethrough.md
--rw-r--r--   0     1001      123    10687 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/tables.md
--rw-r--r--   0     1001      123     3648 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/tasklists.md
--rw-r--r--   0     1001      123     1108 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/fixtures/typographer.md
--rw-r--r--   0     1001      123     1988 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/test_api.py
--rw-r--r--   0     1001      123     2452 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/test_cli.py
--rw-r--r--   0     1001      123     4146 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tests/test_fixtures.py
--rw-r--r--   0     1001      123      701 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/tox.ini
--rw-r--r--   0     1001      123    25466 2023-06-27 08:54:32.000000 markdown_it_pyrs-0.2.0/Cargo.lock
--rw-r--r--   0        0        0    10764 1970-01-01 00:00:00.000000 markdown_it_pyrs-0.2.0/PKG-INFO
+-rw-r--r--   0        0        0      486 1970-01-01 00:00:00.000000 markdown_it_pyrs-0.2.1/Cargo.toml
+-rw-r--r--   0     1001      123      722 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/.github/dependabot.yml
+-rw-r--r--   0     1001      123     6124 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/.github/workflows/CI.yml
+-rw-r--r--   0     1001      123      696 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/.gitignore
+-rw-r--r--   0     1001      123     1001 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/.pre-commit-config.yaml
+-rw-r--r--   0     1001      123    11357 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/LICENSE
+-rw-r--r--   0     1001      123      554 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/NOTICE
+-rw-r--r--   0     1001      123     9563 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/README.md
+-rw-r--r--   0     1001      123     1452 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/pyproject.toml
+-rw-r--r--   0     1001      123      208 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/python/markdown_it_pyrs/__init__.py
+-rw-r--r--   0     1001      123     2763 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/python/markdown_it_pyrs/cli.py
+-rw-r--r--   0     1001      123     3723 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/python/markdown_it_pyrs/markdown_it_pyrs.pyi
+-rw-r--r--   0     1001      123        0 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/python/markdown_it_pyrs/py.typed
+-rw-r--r--   0     1001      123     8733 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/src/lib.rs
+-rw-r--r--   0     1001      123    16310 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/src/nodes.rs
+-rw-r--r--   0     1001      123      693 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/bench_html.py
+-rw-r--r--   0     1001      123      838 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/bench_tree.py
+-rw-r--r--   0     1001      123     3412 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/ast.md
+-rw-r--r--   0     1001      123     6483 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/autolink_ext.md
+-rw-r--r--   0     1001      123     8424 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/commonmark_extras.md
+-rw-r--r--   0     1001      123   150858 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/commonmark_spec.json
+-rw-r--r--   0     1001      123     8323 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/footnote.md
+-rw-r--r--   0     1001      123      791 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/front_matter.md
+-rw-r--r--   0     1001      123     3909 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/linkify.md
+-rw-r--r--   0     1001      123      817 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/normalize.md
+-rw-r--r--   0     1001      123     2639 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/smartquotes.md
+-rw-r--r--   0     1001      123      512 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/sourcepos.md
+-rw-r--r--   0     1001      123   202694 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/spec.md
+-rw-r--r--   0     1001      123     1562 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/strikethrough.md
+-rw-r--r--   0     1001      123    10687 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/tables.md
+-rw-r--r--   0     1001      123     3648 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/tasklists.md
+-rw-r--r--   0     1001      123     1108 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/fixtures/typographer.md
+-rw-r--r--   0     1001      123     2202 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/test_api.py
+-rw-r--r--   0     1001      123     2452 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/test_cli.py
+-rw-r--r--   0     1001      123     4146 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tests/test_fixtures.py
+-rw-r--r--   0     1001      123      701 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/tox.ini
+-rw-r--r--   0     1001      123    25466 2023-06-27 15:22:17.000000 markdown_it_pyrs-0.2.1/Cargo.lock
+-rw-r--r--   0        0        0    10764 1970-01-01 00:00:00.000000 markdown_it_pyrs-0.2.1/PKG-INFO
```

### Comparing `markdown_it_pyrs-0.2.0/.github/dependabot.yml` & `markdown_it_pyrs-0.2.1/.github/dependabot.yml`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/.github/workflows/CI.yml` & `markdown_it_pyrs-0.2.1/.github/workflows/CI.yml`

 * *Files 3% similar despite different names*

```diff
@@ -99,14 +99,15 @@
           name: wheels
           path: dist
       - name: pytest
         if: ${{ startsWith(matrix.target, 'x86_64') }}
         shell: bash
         run: |
           set -e
+          pip install --upgrade pip
           pip install markdown_it_pyrs --find-links dist --force-reinstall
           pip install pytest pytest-param-files
           pytest
       - name: pytest
         if: ${{ !startsWith(matrix.target, 'x86') && matrix.target != 'ppc64' }}
         uses: uraimo/run-on-arch-action@v2.5.0
         with:
@@ -146,14 +147,15 @@
           name: wheels
           path: dist
       - name: pytest
         if: ${{ !startsWith(matrix.target, 'aarch64') }}
         shell: bash
         run: |
           set -e
+          pip install --upgrade pip
           pip install markdown_it_pyrs --find-links dist --force-reinstall
           pip install pytest pytest-param-files
           pytest
 
   macos:
     runs-on: macos-latest
     strategy:
@@ -177,14 +179,15 @@
           name: wheels
           path: dist
       - name: pytest
         if: ${{ !startsWith(matrix.target, 'aarch64') }}
         shell: bash
         run: |
           set -e
+          pip install --upgrade pip
           pip install markdown_it_pyrs --find-links dist --force-reinstall
           pip install pytest pytest-param-files
           pytest
 
   sdist:
     runs-on: ubuntu-latest
     steps:
```

### Comparing `markdown_it_pyrs-0.2.0/.gitignore` & `markdown_it_pyrs-0.2.1/.gitignore`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/.pre-commit-config.yaml` & `markdown_it_pyrs-0.2.1/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/LICENSE` & `markdown_it_pyrs-0.2.1/LICENSE`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/NOTICE` & `markdown_it_pyrs-0.2.1/NOTICE`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/README.md` & `markdown_it_pyrs-0.2.1/README.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/pyproject.toml` & `markdown_it_pyrs-0.2.1/pyproject.toml`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/python/markdown_it_pyrs/cli.py` & `markdown_it_pyrs-0.2.1/python/markdown_it_pyrs/cli.py`

 * *Files 6% similar despite different names*

```diff
@@ -25,38 +25,49 @@
         action=ListPlugins,
         nargs=0,
         help="Print available plugins and exit",
     )
 
     subparsers = parser.add_subparsers(title="Commands", metavar="", dest="subcommand")
 
-    parser_html = subparsers.add_parser("html", help="Render to HTML")
-    add_shared_args(parser_html)
-
     parser_ast = subparsers.add_parser("ast", help="Render to Abstract Syntax Tree")
     add_shared_args(parser_ast)
     parser_ast.add_argument(
         "--verbose",
         "-v",
         action="store_true",
         help="Print node metadata",
     )
 
+    parser_html = subparsers.add_parser("html", help="Render to HTML")
+    add_shared_args(parser_html)
+    group = parser_html.add_mutually_exclusive_group(required=False)
+    group.add_argument(
+        "--no-xhtml",
+        dest="xhtml",
+        action="store_false",
+        help="Don't add /> to self-closing tags",
+    )
+    group.add_argument(
+        "--xhtml", dest="xhtml", action="store_true", help=argparse.SUPPRESS
+    )
+    parser_html.set_defaults(xhtml=True)
+
     parsed_args = parser.parse_args(args)
     md = MarkdownIt(parsed_args.config)
     if parsed_args.enable:
         md.enable_many(parsed_args.enable.split(","))
-    if parsed_args.subcommand == "html":
-        print(md.render(parsed_args.file.read()))
     if parsed_args.subcommand == "ast":
         print(
             md.tree(parsed_args.file.read()).pretty(
                 attrs=True, meta=parsed_args.verbose
             )
         )
+    elif parsed_args.subcommand == "html":
+        print(md.render(parsed_args.file.read(), xhtml=parsed_args.xhtml))
 
 
 class ListPlugins(argparse.Action):
     def __call__(self, parser, namespace, values, option_string=None):
         print("\n".join(MarkdownIt.list_plugins()))
         sys.exit(0)
```

### Comparing `markdown_it_pyrs-0.2.0/python/markdown_it_pyrs/markdown_it_pyrs.pyi` & `markdown_it_pyrs-0.2.1/python/markdown_it_pyrs/markdown_it_pyrs.pyi`

 * *Files 3% similar despite different names*

```diff
@@ -120,18 +120,19 @@
         self,
         names: List[_PLUGIN_NAME],
     ) -> "MarkdownIt":
         """Enable multiple plugin rules.
 
         :param names: Plugin names.
         """
-    def render(self, src: str) -> str:
+    def render(self, src: str, *, xhtml: bool = True) -> str:
         """Render Markdown to HTML.
 
         :param src: Markdown source.
+        :param xhtml: If true, self-closing tags will include a slash, e.g. `<br />`.
         :returns: HTML.
         """
     def tree(self, src: str) -> Node:
         """Create a syntax tree from the Markdown source.
 
         :param src: Markdown source.
         """
```

### Comparing `markdown_it_pyrs-0.2.0/src/lib.rs` & `markdown_it_pyrs-0.2.1/src/lib.rs`

 * *Files 1% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 use pyo3::prelude::*;
 
 mod nodes;
 
 /// Main parser class
 #[pyclass]
+#[derive(Debug)]
 pub struct MarkdownIt {
     parser: markdown_it::MarkdownIt,
-    xhtml_out: bool,
 }
 
 impl MarkdownIt {
     fn _enable(&mut self, name: &str) -> Result<(), PyErr> {
         match name {
             "blockquote" => {
                 markdown_it::plugins::cmark::block::blockquote::add(&mut self.parser);
@@ -121,43 +121,41 @@
     #[pyo3(signature = (config="commonmark"))]
     fn new(config: &str) -> PyResult<Self> {
         match config {
             "commonmark" => {
                 let mut parser = markdown_it::MarkdownIt::new();
                 markdown_it::plugins::cmark::add(&mut parser);
                 markdown_it::plugins::html::add(&mut parser);
-                Ok(Self {
-                    parser,
-                    xhtml_out: true,
-                })
+                Ok(Self { parser })
             }
             "gfm" => {
                 let mut parser = markdown_it::MarkdownIt::new();
                 markdown_it::plugins::cmark::add(&mut parser);
                 markdown_it::plugins::html::add(&mut parser);
                 markdown_it::plugins::extra::tables::add(&mut parser);
                 markdown_it::plugins::extra::strikethrough::add(&mut parser);
                 markdown_it_autolink::add(&mut parser);
                 markdown_it_tasklist::add(&mut parser);
-                Ok(Self {
-                    parser,
-                    xhtml_out: true,
-                })
+                Ok(Self { parser })
             }
             "zero" => Ok(Self {
                 parser: markdown_it::MarkdownIt::new(),
-                xhtml_out: false,
             }),
             _ => Err(pyo3::exceptions::PyValueError::new_err(format!(
                 "Unknown config: {}",
                 config
             ))),
         }
     }
 
+    /// Return a debug representation of the rust struct
+    fn _debug(&self) -> String {
+        format!("{:#?}", self)
+    }
+
     // keep this private for now, whilst we work out how to expose it properly
     fn _unset_lang_prefix(&mut self) {
         markdown_it::plugins::cmark::block::fence::set_lang_prefix(&mut self.parser, "");
     }
 
     #[staticmethod]
     fn list_plugins() -> Vec<String> {
@@ -209,17 +207,19 @@
         for name in names {
             slf.borrow_mut(py)._enable(name)?;
         }
         Ok(slf)
     }
 
     /// Render markdown string into HTML.
-    fn render(&self, src: &str) -> String {
+    /// If `xhtml` is true, then self-closing tags will include a slash, e.g. `<br />`.
+    #[pyo3(signature = (src, *, xhtml=true))]
+    fn render(&self, src: &str, xhtml: bool) -> String {
         let ast = self.parser.parse(src);
-        match self.xhtml_out {
+        match xhtml {
             true => ast.xrender(),
             false => ast.render(),
         }
     }
 
     /// Create a syntax tree from the markdown string.
     fn tree(&self, py: Python, src: &str) -> nodes::Node {
```

### Comparing `markdown_it_pyrs-0.2.0/src/nodes.rs` & `markdown_it_pyrs-0.2.1/src/nodes.rs`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/bench_html.py` & `markdown_it_pyrs-0.2.1/tests/bench_html.py`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/bench_tree.py` & `markdown_it_pyrs-0.2.1/tests/bench_tree.py`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/ast.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/ast.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/autolink_ext.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/autolink_ext.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/commonmark_extras.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/commonmark_extras.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/commonmark_spec.json` & `markdown_it_pyrs-0.2.1/tests/fixtures/commonmark_spec.json`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/footnote.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/footnote.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/front_matter.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/front_matter.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/linkify.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/linkify.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/normalize.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/normalize.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/smartquotes.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/smartquotes.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/sourcepos.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/sourcepos.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/spec.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/spec.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/strikethrough.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/strikethrough.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/tables.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/tables.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/tasklists.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/tasklists.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/fixtures/typographer.md` & `markdown_it_pyrs-0.2.1/tests/fixtures/typographer.md`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/test_api.py` & `markdown_it_pyrs-0.2.1/tests/test_api.py`

 * *Files 6% similar despite different names*

```diff
@@ -27,14 +27,20 @@
 
 
 def test_gfm() -> None:
     mdit = MarkdownIt("gfm")
     assert mdit.render("# markdown-it rulezz!") == "<h1>markdown-it rulezz!</h1>\n"
 
 
+def test_render_xhtml() -> None:
+    mdit = MarkdownIt()
+    assert mdit.render("![a](b)") == '<p><img src="b" alt="a" /></p>\n'
+    assert mdit.render("![a](b)", xhtml=False) == '<p><img src="b" alt="a"></p>\n'
+
+
 def test_node() -> None:
     node = Node("root")
     assert node.name == "root"
     assert node.children == []
     assert node.srcmap is None
     assert node.attrs == {}
     assert node.meta == {}
```

### Comparing `markdown_it_pyrs-0.2.0/tests/test_cli.py` & `markdown_it_pyrs-0.2.1/tests/test_cli.py`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tests/test_fixtures.py` & `markdown_it_pyrs-0.2.1/tests/test_fixtures.py`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/tox.ini` & `markdown_it_pyrs-0.2.1/tox.ini`

 * *Files identical despite different names*

### Comparing `markdown_it_pyrs-0.2.0/Cargo.lock` & `markdown_it_pyrs-0.2.1/Cargo.lock`

 * *Files 0% similar despite different names*

```diff
@@ -373,15 +373,15 @@
  "once_cell",
  "regex",
  "stacker",
 ]
 
 [[package]]
 name = "markdown_it_pyrs"
-version = "0.2.0"
+version = "0.2.1"
 dependencies = [
  "itertools",
  "markdown-it",
  "markdown-it-autolink",
  "markdown-it-footnote",
  "markdown-it-front-matter",
  "markdown-it-heading-anchors",
```

### Comparing `markdown_it_pyrs-0.2.0/PKG-INFO` & `markdown_it_pyrs-0.2.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: markdown_it_pyrs
-Version: 0.2.0
+Version: 0.2.1
 Classifier: Development Status :: 4 - Beta
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Programming Language :: Rust
 Classifier: Programming Language :: Python :: Implementation :: CPython
 Classifier: Programming Language :: Python :: Implementation :: PyPy
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Topic :: Text Processing :: Markup
```


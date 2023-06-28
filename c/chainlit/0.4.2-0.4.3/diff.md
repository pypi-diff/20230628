# Comparing `tmp/chainlit-0.4.2.tar.gz` & `tmp/chainlit-0.4.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "chainlit-0.4.2.tar", max compression
+gzip compressed data, was "chainlit-0.4.3.tar", max compression
```

## Comparing `chainlit-0.4.2.tar` & `chainlit-0.4.3.tar`

### file list

```diff
@@ -1,43 +1,48 @@
--rw-r--r--   0        0        0     2827 2023-06-26 10:56:43.424850 chainlit-0.4.2/README.md
--rw-r--r--   0        0        0     7956 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/__init__.py
--rw-r--r--   0        0        0       87 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/__main__.py
--rw-r--r--   0        0        0     1209 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/action.py
--rw-r--r--   0        0        0     1343 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/cache.py
--rw-r--r--   0        0        0     4535 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/cli/__init__.py
--rw-r--r--   0        0        0     4093 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/cli/auth.py
--rw-r--r--   0        0        0     2594 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/cli/deploy.py
--rw-r--r--   0        0        0     1147 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/cli/mock.py
--rw-r--r--   0        0        0      716 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/cli/utils.py
--rw-r--r--   0        0        0     3284 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/client/base.py
--rw-r--r--   0        0        0    14109 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/client/cloud.py
--rw-r--r--   0        0        0     7324 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/client/local.py
--rw-r--r--   0        0        0      682 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/client/utils.py
--rw-r--r--   0        0        0     8323 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/config.py
--rw-r--r--   0        0        0      709 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/context.py
--rw-r--r--   0        0        0      982 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/db/__init__.py
--rw-r--r--   0        0        0     1373 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/db/prisma/schema.prisma
--rw-r--r--   0        0        0     6317 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/element.py
--rw-r--r--   0        0        0     4142 2023-06-26 10:55:54.903821 chainlit-0.4.2/chainlit/emitter.py
--rw-r--r--   0        0        0   614554 2023-06-26 10:57:07.541359 chainlit-0.4.2/chainlit/frontend/dist/assets/index-995e21ad.js
--rw-r--r--   0        0        0     5697 2023-06-26 10:57:07.537359 chainlit-0.4.2/chainlit/frontend/dist/assets/index-f93cc942.css
--rw-r--r--   0        0        0  1334132 2023-06-26 10:57:07.541359 chainlit-0.4.2/chainlit/frontend/dist/assets/index-fb1e167a.js
--rw-r--r--   0        0        0     8889 2023-06-26 10:57:07.533359 chainlit-0.4.2/chainlit/frontend/dist/assets/logo_dark-bc7401f6.svg
--rw-r--r--   0        0        0     8891 2023-06-26 10:57:07.537359 chainlit-0.4.2/chainlit/frontend/dist/assets/logo_light-f19fc2ea.svg
--rw-r--r--   0        0        0     6455 2023-06-26 10:57:06.453336 chainlit-0.4.2/chainlit/frontend/dist/favicon.svg
--rw-r--r--   0        0        0      793 2023-06-26 10:57:07.541359 chainlit-0.4.2/chainlit/frontend/dist/index.html
--rw-r--r--   0        0        0      417 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/hello.py
--rw-r--r--   0        0        0      292 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/lc/__init__.py
--rw-r--r--   0        0        0     1121 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/lc/agent.py
--rw-r--r--   0        0        0    12783 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/lc/callbacks.py
--rw-r--r--   0        0        0      374 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/logger.py
--rw-r--r--   0        0        0     1623 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/markdown.py
--rw-r--r--   0        0        0    12198 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/message.py
--rw-r--r--   0        0        0    17267 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/server.py
--rw-r--r--   0        0        0      812 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/session.py
--rw-r--r--   0        0        0      539 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/sync.py
--rw-r--r--   0        0        0     2358 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/telemetry.py
--rw-r--r--   0        0        0     1981 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/types.py
--rw-r--r--   0        0        0     1213 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/user_session.py
--rw-r--r--   0        0        0      196 2023-06-26 10:55:54.907821 chainlit-0.4.2/chainlit/version.py
--rw-r--r--   0        0        0     1014 2023-06-26 10:55:54.907821 chainlit-0.4.2/pyproject.toml
--rw-r--r--   0        0        0     4280 1970-01-01 00:00:00.000000 chainlit-0.4.2/PKG-INFO
+-rw-r--r--   0        0        0     2827 2023-06-28 15:41:04.727995 chainlit-0.4.3/README.md
+-rw-r--r--   0        0        0     4078 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/__init__.py
+-rw-r--r--   0        0        0       87 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/__main__.py
+-rw-r--r--   0        0        0     1209 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/action.py
+-rw-r--r--   0        0        0     1343 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/cache.py
+-rw-r--r--   0        0        0     4888 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/cli/__init__.py
+-rw-r--r--   0        0        0     4093 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/cli/auth.py
+-rw-r--r--   0        0        0     2594 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/cli/deploy.py
+-rw-r--r--   0        0        0    67012 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/cli/mock.py
+-rw-r--r--   0        0        0      716 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/cli/utils.py
+-rw-r--r--   0        0        0     3284 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/client/base.py
+-rw-r--r--   0        0        0    14109 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/client/cloud.py
+-rw-r--r--   0        0        0     7324 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/client/local.py
+-rw-r--r--   0        0        0      682 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/client/utils.py
+-rw-r--r--   0        0        0     8493 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/config.py
+-rw-r--r--   0        0        0      709 2023-06-28 15:40:08.915050 chainlit-0.4.3/chainlit/context.py
+-rw-r--r--   0        0        0      982 2023-06-28 15:40:08.919050 chainlit-0.4.3/chainlit/db/__init__.py
+-rw-r--r--   0        0        0     1373 2023-06-28 15:40:08.919050 chainlit-0.4.3/chainlit/db/prisma/schema.prisma
+-rw-r--r--   0        0        0     6317 2023-06-28 15:40:08.919050 chainlit-0.4.3/chainlit/element.py
+-rw-r--r--   0        0        0     4142 2023-06-28 15:40:08.919050 chainlit-0.4.3/chainlit/emitter.py
+-rw-r--r--   0        0        0   614554 2023-06-28 15:41:29.836420 chainlit-0.4.3/chainlit/frontend/dist/assets/index-37b5009c.js
+-rw-r--r--   0        0        0  1334161 2023-06-28 15:41:29.836420 chainlit-0.4.3/chainlit/frontend/dist/assets/index-51393291.js
+-rw-r--r--   0        0        0     5697 2023-06-28 15:41:29.836420 chainlit-0.4.3/chainlit/frontend/dist/assets/index-f93cc942.css
+-rw-r--r--   0        0        0     8889 2023-06-28 15:41:29.828420 chainlit-0.4.3/chainlit/frontend/dist/assets/logo_dark-bc7401f6.svg
+-rw-r--r--   0        0        0     8891 2023-06-28 15:41:29.836420 chainlit-0.4.3/chainlit/frontend/dist/assets/logo_light-f19fc2ea.svg
+-rw-r--r--   0        0        0     6455 2023-06-28 15:41:28.652400 chainlit-0.4.3/chainlit/frontend/dist/favicon.svg
+-rw-r--r--   0        0        0      793 2023-06-28 15:41:29.836420 chainlit-0.4.3/chainlit/frontend/dist/index.html
+-rw-r--r--   0        0        0      417 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/hello.py
+-rw-r--r--   0        0        0     2339 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/langflow/__init__.py
+-rw-r--r--   0        0        0     3281 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/lc/__init__.py
+-rw-r--r--   0        0        0     1140 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/lc/agent.py
+-rw-r--r--   0        0        0    12788 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/lc/callbacks.py
+-rw-r--r--   0        0        0      953 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/llama_index/__init__.py
+-rw-r--r--   0        0        0     2994 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/llama_index/callbacks.py
+-rw-r--r--   0        0        0     1230 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/llama_index/run.py
+-rw-r--r--   0        0        0      374 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/logger.py
+-rw-r--r--   0        0        0     1623 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/markdown.py
+-rw-r--r--   0        0        0    12216 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/message.py
+-rw-r--r--   0        0        0    17625 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/server.py
+-rw-r--r--   0        0        0      866 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/session.py
+-rw-r--r--   0        0        0      688 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/sync.py
+-rw-r--r--   0        0        0     2358 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/telemetry.py
+-rw-r--r--   0        0        0     1981 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/types.py
+-rw-r--r--   0        0        0     1213 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/user_session.py
+-rw-r--r--   0        0        0     1561 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/utils.py
+-rw-r--r--   0        0        0      196 2023-06-28 15:40:08.923050 chainlit-0.4.3/chainlit/version.py
+-rw-r--r--   0        0        0     1038 2023-06-28 15:40:08.923050 chainlit-0.4.3/pyproject.toml
+-rw-r--r--   0        0        0     4325 1970-01-01 00:00:00.000000 chainlit-0.4.3/PKG-INFO
```

### Comparing `chainlit-0.4.2/README.md` & `chainlit-0.4.3/README.md`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/action.py` & `chainlit-0.4.3/chainlit/action.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/cache.py` & `chainlit-0.4.3/chainlit/cache.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/cli/__init__.py` & `chainlit-0.4.3/chainlit/cli/__init__.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,11 +1,15 @@
 import click
 import os
 import sys
 import uvicorn
+import asyncio
+import nest_asyncio
+
+nest_asyncio.apply()
 
 from chainlit.config import (
     config,
     init_config,
     load_module,
     PACKAGE_ROOT,
     DEFAULT_HOST,
@@ -48,15 +52,23 @@
     init_lc_cache()
 
     # Initialize the local database if configured to use it
     init_local_db()
 
     log_level = "debug" if config.run.debug else "error"
 
-    uvicorn.run(app, host=host, port=port, log_level=log_level)
+    # Start the server
+    async def start():
+        config = uvicorn.Config(app, host=host, port=port, log_level=log_level)
+        server = uvicorn.Server(config)
+        await server.serve()
+
+    # Run the asyncio event loop instead of uvloop to enable re entrance
+    asyncio.run(start())
+    # uvicorn.run(app, host=host, port=port, log_level=log_level)
 
 
 # Define the "run" command for Chainlit CLI
 @cli.command("run")
 @click.argument("target", required=True, envvar="RUN_TARGET")
 @click.option(
     "-w",
```

### Comparing `chainlit-0.4.2/chainlit/cli/auth.py` & `chainlit-0.4.3/chainlit/cli/auth.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/cli/deploy.py` & `chainlit-0.4.3/chainlit/cli/deploy.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/cli/utils.py` & `chainlit-0.4.3/chainlit/cli/utils.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/client/base.py` & `chainlit-0.4.3/chainlit/client/base.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/client/cloud.py` & `chainlit-0.4.3/chainlit/client/cloud.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/client/local.py` & `chainlit-0.4.3/chainlit/client/local.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/client/utils.py` & `chainlit-0.4.3/chainlit/client/utils.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/config.py` & `chainlit-0.4.3/chainlit/config.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,8 +1,8 @@
-from typing import Optional, Any, Callable, Literal, List, Dict, TYPE_CHECKING
+from typing import Optional, Any, Callable, Union, Literal, List, Dict, TYPE_CHECKING
 import os
 import sys
 import tomli
 from pydantic.dataclasses import dataclass
 from dataclasses_json import dataclass_json
 from importlib import util
 from chainlit.logger import logger
@@ -104,24 +104,27 @@
     on_chat_start: Optional[Callable[[], Any]] = None
     on_message: Optional[Callable[[str], Any]] = None
     lc_agent_is_async: Optional[bool] = None
     lc_run: Optional[Callable[[Any, str], str]] = None
     lc_postprocess: Optional[Callable[[Any], str]] = None
     lc_factory: Optional[Callable[[], Any]] = None
     lc_rename: Optional[Callable[[str], str]] = None
+    llama_index_factory: Optional[Callable[[], Any]] = None
+    langflow_schema: Union[Dict, str] = None
     client_factory: Optional[Callable[[str], "BaseClient"]] = None
 
     def validate(self):
         requires_one_of = [
             "lc_factory",
+            "llama_index_factory",
             "on_message",
             "on_chat_start",
         ]
 
-        mutually_exclusive = ["lc_factory"]
+        mutually_exclusive = ["lc_factory", "llama_index_factory"]
 
         # Check if at least one of the required attributes is set
         if not any(getattr(self, attr) for attr in requires_one_of):
             raise ValueError(
                 f"Module should at least expose one of {', '.join(requires_one_of)} function"
             )
```

### Comparing `chainlit-0.4.2/chainlit/context.py` & `chainlit-0.4.3/chainlit/context.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/db/__init__.py` & `chainlit-0.4.3/chainlit/db/__init__.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/db/prisma/schema.prisma` & `chainlit-0.4.3/chainlit/db/prisma/schema.prisma`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/element.py` & `chainlit-0.4.3/chainlit/element.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/emitter.py` & `chainlit-0.4.3/chainlit/emitter.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/frontend/dist/assets/index-995e21ad.js` & `chainlit-0.4.3/chainlit/frontend/dist/assets/index-37b5009c.js`

 * *Files 0% similar despite different names*

#### js-beautify {}

```diff
@@ -1,11 +1,11 @@
 import {
     c as me,
     g as Xc
-} from "./index-fb1e167a.js";
+} from "./index-51393291.js";
 
 function Qc(e, t) {
     for (var r = 0; r < t.length; r++) {
         const a = t[r];
         if (typeof a != "string" && !Array.isArray(a)) {
             for (const n in a)
                 if (n !== "default" && !(n in e)) {
```

### Comparing `chainlit-0.4.2/chainlit/frontend/dist/assets/index-f93cc942.css` & `chainlit-0.4.3/chainlit/frontend/dist/assets/index-f93cc942.css`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/frontend/dist/assets/index-fb1e167a.js` & `chainlit-0.4.3/chainlit/frontend/dist/assets/index-51393291.js`

 * *Files 0% similar despite different names*

#### js-beautify {}

```diff
@@ -37302,15 +37302,15 @@
             if (a.astGenerator) return r(a.astGenerator, s, l);
             a.languages.set(s, l)
         }), a
     },
     CCe = ["abap", "abnf", "actionscript", "ada", "agda", "al", "antlr4", "apacheconf", "apex", "apl", "applescript", "aql", "arduino", "arff", "asciidoc", "asm6502", "asmatmel", "aspnet", "autohotkey", "autoit", "avisynth", "avro-idl", "bash", "basic", "batch", "bbcode", "bicep", "birb", "bison", "bnf", "brainfuck", "brightscript", "bro", "bsl", "c", "cfscript", "chaiscript", "cil", "clike", "clojure", "cmake", "cobol", "coffeescript", "concurnas", "coq", "cpp", "crystal", "csharp", "cshtml", "csp", "css-extras", "css", "csv", "cypher", "d", "dart", "dataweave", "dax", "dhall", "diff", "django", "dns-zone-file", "docker", "dot", "ebnf", "editorconfig", "eiffel", "ejs", "elixir", "elm", "erb", "erlang", "etlua", "excel-formula", "factor", "false", "firestore-security-rules", "flow", "fortran", "fsharp", "ftl", "gap", "gcode", "gdscript", "gedcom", "gherkin", "git", "glsl", "gml", "gn", "go-module", "go", "graphql", "groovy", "haml", "handlebars", "haskell", "haxe", "hcl", "hlsl", "hoon", "hpkp", "hsts", "http", "ichigojam", "icon", "icu-message-format", "idris", "iecst", "ignore", "inform7", "ini", "io", "j", "java", "javadoc", "javadoclike", "javascript", "javastacktrace", "jexl", "jolie", "jq", "js-extras", "js-templates", "jsdoc", "json", "json5", "jsonp", "jsstacktrace", "jsx", "julia", "keepalived", "keyman", "kotlin", "kumir", "kusto", "latex", "latte", "less", "lilypond", "liquid", "lisp", "livescript", "llvm", "log", "lolcode", "lua", "magma", "makefile", "markdown", "markup-templating", "markup", "matlab", "maxscript", "mel", "mermaid", "mizar", "mongodb", "monkey", "moonscript", "n1ql", "n4js", "nand2tetris-hdl", "naniscript", "nasm", "neon", "nevod", "nginx", "nim", "nix", "nsis", "objectivec", "ocaml", "opencl", "openqasm", "oz", "parigp", "parser", "pascal", "pascaligo", "pcaxis", "peoplecode", "perl", "php-extras", "php", "phpdoc", "plsql", "powerquery", "powershell", "processing", "prolog", "promql", "properties", "protobuf", "psl", "pug", "puppet", "pure", "purebasic", "purescript", "python", "q", "qml", "qore", "qsharp", "r", "racket", "reason", "regex", "rego", "renpy", "rest", "rip", "roboconf", "robotframework", "ruby", "rust", "sas", "sass", "scala", "scheme", "scss", "shell-session", "smali", "smalltalk", "smarty", "sml", "solidity", "solution-file", "soy", "sparql", "splunk-spl", "sqf", "sql", "squirrel", "stan", "stylus", "swift", "systemd", "t4-cs", "t4-templating", "t4-vb", "tap", "tcl", "textile", "toml", "tremor", "tsx", "tt2", "turtle", "twig", "typescript", "typoscript", "unrealscript", "uorazor", "uri", "v", "vala", "vbnet", "velocity", "verilog", "vhdl", "vim", "visual-basic", "warpscript", "wasm", "web-idl", "wiki", "wolfram", "wren", "xeora", "xml-doc", "xojo", "xquery", "yaml", "yang", "zig"],
     ECe = _Ce({
         loader: function() {
-            return dCe(() => import("./index-995e21ad.js").then(t => t.i), []).then(function(t) {
+            return dCe(() => import("./index-37b5009c.js").then(t => t.i), []).then(function(t) {
                 return t.default || t
             })
         },
         noAsyncLoadingLanguages: !0,
         supportedLanguages: CCe
     }),
     kCe = {
@@ -38568,15 +38568,15 @@
 function PEe({
     id: e,
     elements: t,
     actions: n,
     content: r,
     language: i
 }) {
-    const o = t.map(h => h.name);
+    const o = t.filter(h => h.type !== "avatar").map(h => h.name);
     o.sort((h, p) => p.length - h.length);
     const a = o.length ? new RegExp(`(${o.join("|")})`, "g") : void 0,
         s = n.filter(h => h.forId ? h.forId === e : !0);
     let l = r ? r.trim() : "";
     const c = t.filter(h => jL(e, h == null ? void 0 : h.forIds) && h.display === "inline"),
         f = [];
     return a && (l = l.replaceAll(a, h => {
```

### Comparing `chainlit-0.4.2/chainlit/frontend/dist/assets/logo_dark-bc7401f6.svg` & `chainlit-0.4.3/chainlit/frontend/dist/assets/logo_dark-bc7401f6.svg`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/frontend/dist/assets/logo_light-f19fc2ea.svg` & `chainlit-0.4.3/chainlit/frontend/dist/assets/logo_light-f19fc2ea.svg`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/frontend/dist/favicon.svg` & `chainlit-0.4.3/chainlit/frontend/dist/favicon.svg`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/frontend/dist/index.html` & `chainlit-0.4.3/chainlit/frontend/dist/index.html`

 * *Files 16% similar despite different names*

```diff
@@ -10,15 +10,15 @@
     <link
       href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;700&display=swap"
       rel="stylesheet"
     />
     <script>
       const global = globalThis;
     </script>
-    <script type="module" crossorigin src="/assets/index-fb1e167a.js"></script>
+    <script type="module" crossorigin src="/assets/index-51393291.js"></script>
     <link rel="stylesheet" href="/assets/index-f93cc942.css">
   </head>
   <body>
     <div id="root"></div>
     
   </body>
 </html>
```

### Comparing `chainlit-0.4.2/chainlit/lc/agent.py` & `chainlit-0.4.3/chainlit/lc/agent.py`

 * *Files 13% similar despite different names*

```diff
@@ -1,32 +1,35 @@
 from typing import Any
-from chainlit.lc.callbacks import ChainlitCallbackHandler, AsyncChainlitCallbackHandler
+from chainlit.lc.callbacks import (
+    LangchainCallbackHandler,
+    AsyncLangchainCallbackHandler,
+)
 from chainlit.sync import make_async
 from chainlit.context import emitter_var
 
 
 async def run_langchain_agent(agent: Any, input_str: str, use_async: bool):
     if hasattr(agent, "input_keys"):
         input_key = agent.input_keys[0]
         if use_async:
             raw_res = await agent.acall(
-                {input_key: input_str}, callbacks=[AsyncChainlitCallbackHandler()]
+                {input_key: input_str}, callbacks=[AsyncLangchainCallbackHandler()]
             )
         else:
             raw_res = await make_async(agent.__call__)(
-                {input_key: input_str}, callbacks=[ChainlitCallbackHandler()]
+                {input_key: input_str}, callbacks=[LangchainCallbackHandler()]
             )
     else:
         if use_async:
             raw_res = await agent.acall(
-                input_str, callbacks=[AsyncChainlitCallbackHandler()]
+                input_str, callbacks=[AsyncLangchainCallbackHandler()]
             )
         else:
             raw_res = await make_async(agent.__call__)(
-                input_str, callbacks=[ChainlitCallbackHandler()]
+                input_str, callbacks=[LangchainCallbackHandler()]
             )
 
     if hasattr(agent, "output_keys"):
         output_key = agent.output_keys[0]
     else:
         output_key = None
```

### Comparing `chainlit-0.4.2/chainlit/lc/callbacks.py` & `chainlit-0.4.3/chainlit/lc/callbacks.py`

 * *Files 1% similar despite different names*

```diff
@@ -34,15 +34,15 @@
             model_name=invocation_params["model_name"],
             stop=invocation_params["stop"],
         )
     else:
         return None
 
 
-class BaseChainlitCallbackHandler(BaseCallbackHandler):
+class BaseLangchainCallbackHandler(BaseCallbackHandler):
     emitter: ChainlitEmitter
     # Keep track of the formatted prompts to display them in the prompt playground.
     prompts: List[str]
     # Keep track of the LLM settings for the last prompt
     llm_settings: LLMSettings
     # Keep track of the call sequence, like [AgentExecutor, LLMMathChain, Calculator, ...]
     sequence: List[str]
@@ -96,15 +96,15 @@
             author = self.sequence[-1]
         else:
             author = config.ui.name
 
         return author, indent, llm_settings
 
 
-class ChainlitCallbackHandler(BaseChainlitCallbackHandler, BaseCallbackHandler):
+class LangchainCallbackHandler(BaseLangchainCallbackHandler, BaseCallbackHandler):
     def start_stream(self):
         author, indent, llm_settings = self.get_message_params()
 
         if author in IGNORE_LIST:
             return
 
         if config.code.lc_rename:
@@ -248,15 +248,15 @@
         pass
 
     def on_agent_finish(self, finish: AgentFinish, **kwargs: Any) -> None:
         """Run on agent end."""
         pass
 
 
-class AsyncChainlitCallbackHandler(BaseChainlitCallbackHandler, AsyncCallbackHandler):
+class AsyncLangchainCallbackHandler(BaseLangchainCallbackHandler, AsyncCallbackHandler):
     async def start_stream(self):
         author, indent, llm_settings = self.get_message_params()
 
         if author in IGNORE_LIST:
             return
 
         if config.code.lc_rename:
```

### Comparing `chainlit-0.4.2/chainlit/markdown.py` & `chainlit-0.4.3/chainlit/markdown.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/message.py` & `chainlit-0.4.3/chainlit/message.py`

 * *Files 2% similar despite different names*

```diff
@@ -243,18 +243,18 @@
         Return the ID of the message.
         """
         trace_event("send_error_message")
         return await super().send()
 
 
 class AskMessageBase(MessageBase):
-    def remove(self):
-        removed = super().remove()
+    async def remove(self):
+        removed = await super().remove()
         if removed:
-            self.emitter.clear_ask()
+            await self.emitter.clear_ask()
 
 
 class AskUserMessage(AskMessageBase):
     """
     Ask for the user input before continuing.
     If the user does not answer in time (see timeout), a TimeoutError will be raised or None will be returned depending on raise_on_timeout.
     If a project ID is configured, the message will be uploaded to the cloud storage.
```

### Comparing `chainlit-0.4.2/chainlit/server.py` & `chainlit-0.4.3/chainlit/server.py`

 * *Files 2% similar despite different names*

```diff
@@ -404,22 +404,26 @@
 
 @socket.on("connection_successful")
 async def connection_successful(sid):
     session = need_session(sid)
     emitter_var.set(ChainlitEmitter(session))
     loop_var.set(asyncio.get_event_loop())
 
+    if config.code.on_chat_start:
+        """Call the on_chat_start function provided by the developer."""
+        await config.code.on_chat_start()
+
     if config.code.lc_factory:
         """Instantiate the langchain agent and store it in the session."""
         agent = await config.code.lc_factory()
         session["agent"] = agent
 
-    if config.code.on_chat_start:
-        """Call the on_chat_start function provided by the developer."""
-        await config.code.on_chat_start()
+    if config.code.llama_index_factory:
+        llama_instance = await config.code.llama_index_factory()
+        session["llama_instance"] = llama_instance
 
 
 @socket.on("disconnect")
 async def disconnect(sid):
     if sid in sessions:
         # Clean up the session
         sessions.pop(sid)
@@ -463,14 +467,16 @@
                     "author": author,
                     "content": input_str,
                     "authorIsUser": True,
                 }
             )
 
         langchain_agent = session.get("agent")
+        llama_instance = session.get("llama_instance")
+
         if langchain_agent:
             from chainlit.lc.agent import run_langchain_agent
 
             # If a langchain agent is available, run it
             if config.code.lc_run:
                 # If the developer provided a custom run function, use it
                 await config.code.lc_run(
@@ -493,14 +499,19 @@
                     res = raw_res[output_key]
                 else:
                     # Otherwise, use the raw response
                     res = raw_res
             # Finally, send the response to the user
             await Message(author=config.ui.name, content=res).send()
 
+        elif llama_instance:
+            from chainlit.llama_index.run import run_llama
+
+            await run_llama(llama_instance, input_str)
+
         elif config.code.on_message:
             # If no langchain agent is available, call the on_message function provided by the developer
             await config.code.on_message(input_str)
     except InterruptedError:
         pass
     except Exception as e:
         logger.exception(e)
```

### Comparing `chainlit-0.4.2/chainlit/session.py` & `chainlit-0.4.3/chainlit/session.py`

 * *Files 7% similar despite different names*

```diff
@@ -12,14 +12,16 @@
     ask_user: Callable[[Any, Optional[int]], Union[AskResponse, None]]
     # Function to emit a message to the user
     emit: Callable[[str, Any], None]
     # User specific environment variables. Empty if no user environment variables are required.
     user_env: Dict[str, str]
     # Optional langchain agent
     agent: Any
+    # Optional llama instance
+    llama_instance: Any
     # Whether the current task should be stopped
     should_stop: bool
     # Optional client to persist messages and files
     client: Optional[BaseClient]
 
 
 sessions: Dict[str, Session] = {}
```

### Comparing `chainlit-0.4.2/chainlit/telemetry.py` & `chainlit-0.4.3/chainlit/telemetry.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/types.py` & `chainlit-0.4.3/chainlit/types.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/chainlit/user_session.py` & `chainlit-0.4.3/chainlit/user_session.py`

 * *Files identical despite different names*

### Comparing `chainlit-0.4.2/pyproject.toml` & `chainlit-0.4.3/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "chainlit"
-version = "0.4.2"
+version = "0.4.3"
 keywords = ['LLM', 'Agents', 'gen ai', 'chat ui', 'chatbot ui', 'langchain']
 description = "A faster way to build chatbot UIs."
 authors = ["Chainlit"]
 license = "Apache-2.0 license"
 repository = "https://github.com/Chainlit/chainlit"
 readme = "README.md"
 exclude = [
@@ -18,20 +18,21 @@
 # command_name = module_for_handler : function_for_handler
 chainlit = 'chainlit.cli:cli'
 
 [tool.poetry.dependencies]
 python = "^3.8"
 dataclasses_json = "^0.5.7"
 uvicorn = "^0.22.0"
-fastapi = "^0.96.0"
+fastapi = "^0.97.0"
 fastapi-socketio = "^0.0.10"
 aiohttp = "^3.8.4"
 aiofiles = "^23.1.0"
 syncer = "^2.0.3"
 asyncer = "^0.0.2"
+nest-asyncio = "^1.5.6"
 click = "^8.1.3"
 openai = "^0.27.7"
 tomli = "^2.0.1"
 pydantic = "^1.10.8"
 python-graphql-client = "^0.4.3"
 python-dotenv = "^1.0.0"
 auth0-python = "^4.1.1"
```

### Comparing `chainlit-0.4.2/PKG-INFO` & `chainlit-0.4.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: chainlit
-Version: 0.4.2
+Version: 0.4.3
 Summary: A faster way to build chatbot UIs.
 Home-page: https://github.com/Chainlit/chainlit
 License: Apache-2.0 license
 Keywords: LLM,Agents,gen ai,chat ui,chatbot ui,langchain
 Author: Chainlit
 Requires-Python: >=3.8,<4.0
 Classifier: License :: Other/Proprietary License
@@ -15,16 +15,17 @@
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: aiofiles (>=23.1.0,<24.0.0)
 Requires-Dist: aiohttp (>=3.8.4,<4.0.0)
 Requires-Dist: asyncer (>=0.0.2,<0.0.3)
 Requires-Dist: auth0-python (>=4.1.1,<5.0.0)
 Requires-Dist: click (>=8.1.3,<9.0.0)
 Requires-Dist: dataclasses_json (>=0.5.7,<0.6.0)
-Requires-Dist: fastapi (>=0.96.0,<0.97.0)
+Requires-Dist: fastapi (>=0.97.0,<0.98.0)
 Requires-Dist: fastapi-socketio (>=0.0.10,<0.0.11)
+Requires-Dist: nest-asyncio (>=1.5.6,<2.0.0)
 Requires-Dist: openai (>=0.27.7,<0.28.0)
 Requires-Dist: prisma (>=0.9.0,<0.10.0)
 Requires-Dist: pydantic (>=1.10.8,<2.0.0)
 Requires-Dist: python-dotenv (>=1.0.0,<2.0.0)
 Requires-Dist: python-graphql-client (>=0.4.3,<0.5.0)
 Requires-Dist: syncer (>=2.0.3,<3.0.0)
 Requires-Dist: tomli (>=2.0.1,<3.0.0)
```


# Comparing `tmp/opengeode-4.1.6.tar.gz` & `tmp/opengeode-4.1.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "opengeode-4.1.6.tar", last modified: Fri Jun  2 09:04:34 2023, max compression
+gzip compressed data, was "opengeode-4.1.9.tar", last modified: Wed Jun 28 11:43:26 2023, max compression
```

## Comparing `opengeode-4.1.6.tar` & `opengeode-4.1.9.tar`

### file list

```diff
@@ -1,42 +1,42 @@
-drwxr-xr-x   0 taste     (1001) taste     (1001)        0 2023-06-02 09:04:34.401009 opengeode-4.1.6/
--rw-r--r--   0 taste     (1001) taste     (1001)     4673 2022-05-15 08:02:36.000000 opengeode-4.1.6/FONT-LICENCE.txt
--rw-r--r--   0 taste     (1001) taste     (1001)     7651 2022-05-15 08:02:36.000000 opengeode-4.1.6/LICENSE
--rw-r--r--   0 taste     (1001) taste     (1001)       54 2022-05-15 08:02:36.000000 opengeode-4.1.6/MANIFEST.in
--rw-r--r--   0 taste     (1001) taste     (1001)    44405 2023-06-02 09:04:34.401009 opengeode-4.1.6/PKG-INFO
--rw-r--r--   0 taste     (1001) taste     (1001)    34782 2023-06-02 09:04:15.000000 opengeode-4.1.6/README.md
-drwxr-xr-x   0 taste     (1001) taste     (1001)        0 2023-06-02 09:04:34.401009 opengeode-4.1.6/opengeode/
--rw-r--r--   0 taste     (1001) taste     (1001)   158021 2023-05-25 08:53:21.000000 opengeode-4.1.6/opengeode/AdaGenerator.py
--rwxr-xr-x   0 taste     (1001) taste     (1001)    13961 2023-05-25 08:53:21.000000 opengeode-4.1.6/opengeode/Asn1scc.py
--rw-r--r--   0 taste     (1001) taste     (1001)   116013 2022-11-13 15:59:02.000000 opengeode-4.1.6/opengeode/CGenerator.py
--rw-r--r--   0 taste     (1001) taste     (1001)    11750 2023-05-09 20:41:05.000000 opengeode-4.1.6/opengeode/Clipboard.py
--rw-r--r--   0 taste     (1001) taste     (1001)    29689 2022-12-08 11:28:57.000000 opengeode-4.1.6/opengeode/Connectors.py
--rw-r--r--   0 taste     (1001) taste     (1001)    38556 2023-05-25 08:53:21.000000 opengeode-4.1.6/opengeode/Helper.py
--rw-r--r--   0 taste     (1001) taste     (1001)    12719 2023-04-14 16:02:15.000000 opengeode-4.1.6/opengeode/Lander.py
--rw-r--r--   0 taste     (1001) taste     (1001)    82924 2023-01-22 14:09:04.000000 opengeode-4.1.6/opengeode/LlvmGenerator.py
--rw-r--r--   0 taste     (1001) taste     (1001)    18655 2023-05-10 20:42:44.000000 opengeode-4.1.6/opengeode/Pr.py
--rw-r--r--   0 taste     (1001) taste     (1001)     2462 2022-05-15 08:02:36.000000 opengeode-4.1.6/opengeode/QGenSDL.py
--rw-r--r--   0 taste     (1001) taste     (1001)    15873 2023-01-03 10:27:29.000000 opengeode-4.1.6/opengeode/Renderer.py
--rw-r--r--   0 taste     (1001) taste     (1001)    36467 2022-08-25 09:25:42.000000 opengeode-4.1.6/opengeode/Statechart.py
--rw-r--r--   0 taste     (1001) taste     (1001)    73348 2022-07-25 21:01:25.000000 opengeode-4.1.6/opengeode/StgBackend.py
--rw-r--r--   0 taste     (1001) taste     (1001)    18658 2022-11-04 15:55:28.000000 opengeode-4.1.6/opengeode/TextInteraction.py
--rw-r--r--   0 taste     (1001) taste     (1001)     1058 2022-05-15 08:02:36.000000 opengeode-4.1.6/opengeode/__init__.py
--rw-r--r--   0 taste     (1001) taste     (1001)    57607 2023-05-10 20:42:44.000000 opengeode-4.1.6/opengeode/genericSymbols.py
--rw-r--r--   0 taste     (1001) taste     (1001) 21475752 2023-02-01 06:37:57.000000 opengeode-4.1.6/opengeode/icons.py
--rw-r--r--   0 taste     (1001) taste     (1001)    45021 2023-05-25 08:53:21.000000 opengeode-4.1.6/opengeode/ogAST.py
--rw-r--r--   0 taste     (1001) taste     (1001)     9297 2023-05-25 08:53:21.000000 opengeode-4.1.6/opengeode/ogASTDumper.py
--rw-r--r--   0 taste     (1001) taste     (1001)   340998 2023-06-02 09:04:15.000000 opengeode-4.1.6/opengeode/ogParser.py
--rw-r--r--   0 taste     (1001) taste     (1001)   160565 2023-05-25 08:53:21.000000 opengeode-4.1.6/opengeode/opengeode.py
--rw-r--r--   0 taste     (1001) taste     (1001)   183270 2023-05-10 20:42:44.000000 opengeode-4.1.6/opengeode/sdl92Lexer.py
--rw-r--r--   0 taste     (1001) taste     (1001)  4922318 2023-05-10 20:42:44.000000 opengeode-4.1.6/opengeode/sdl92Parser.py
--rw-r--r--   0 taste     (1001) taste     (1001)     2077 2022-10-06 09:09:20.000000 opengeode-4.1.6/opengeode/sdlHelp.py
--rw-r--r--   0 taste     (1001) taste     (1001)    64900 2023-05-10 20:42:44.000000 opengeode-4.1.6/opengeode/sdlSymbols.py
--rw-r--r--   0 taste     (1001) taste     (1001)     9445 2022-07-25 21:01:25.000000 opengeode-4.1.6/opengeode/undoCommands.py
--rw-r--r--   0 taste     (1001) taste     (1001)      358 2023-06-02 09:04:15.000000 opengeode-4.1.6/opengeode/version.py
-drwxr-xr-x   0 taste     (1001) taste     (1001)        0 2023-06-02 09:04:34.401009 opengeode-4.1.6/opengeode.egg-info/
--rw-r--r--   0 taste     (1001) taste     (1001)    44405 2023-06-02 09:04:34.000000 opengeode-4.1.6/opengeode.egg-info/PKG-INFO
--rw-r--r--   0 taste     (1001) taste     (1001)      843 2023-06-02 09:04:34.000000 opengeode-4.1.6/opengeode.egg-info/SOURCES.txt
--rw-r--r--   0 taste     (1001) taste     (1001)        1 2023-06-02 09:04:34.000000 opengeode-4.1.6/opengeode.egg-info/dependency_links.txt
--rw-r--r--   0 taste     (1001) taste     (1001)       61 2023-06-02 09:04:34.000000 opengeode-4.1.6/opengeode.egg-info/entry_points.txt
--rw-r--r--   0 taste     (1001) taste     (1001)       10 2023-06-02 09:04:34.000000 opengeode-4.1.6/opengeode.egg-info/top_level.txt
--rw-r--r--   0 taste     (1001) taste     (1001)       38 2023-06-02 09:04:34.401009 opengeode-4.1.6/setup.cfg
--rwxr-xr-x   0 taste     (1001) taste     (1001)     1220 2023-01-22 14:13:21.000000 opengeode-4.1.6/setup.py
+drwxr-xr-x   0 taste     (1001) taste     (1001)        0 2023-06-28 11:43:26.393108 opengeode-4.1.9/
+-rw-r--r--   0 taste     (1001) taste     (1001)     4673 2022-05-15 08:02:36.000000 opengeode-4.1.9/FONT-LICENCE.txt
+-rw-r--r--   0 taste     (1001) taste     (1001)     7651 2022-05-15 08:02:36.000000 opengeode-4.1.9/LICENSE
+-rw-r--r--   0 taste     (1001) taste     (1001)       54 2022-05-15 08:02:36.000000 opengeode-4.1.9/MANIFEST.in
+-rw-r--r--   0 taste     (1001) taste     (1001)    44727 2023-06-28 11:43:26.389108 opengeode-4.1.9/PKG-INFO
+-rw-r--r--   0 taste     (1001) taste     (1001)    35032 2023-06-28 11:43:14.000000 opengeode-4.1.9/README.md
+drwxr-xr-x   0 taste     (1001) taste     (1001)        0 2023-06-28 11:43:26.389108 opengeode-4.1.9/opengeode/
+-rw-r--r--   0 taste     (1001) taste     (1001)   159470 2023-06-28 11:43:14.000000 opengeode-4.1.9/opengeode/AdaGenerator.py
+-rwxr-xr-x   0 taste     (1001) taste     (1001)    13961 2023-05-25 08:53:21.000000 opengeode-4.1.9/opengeode/Asn1scc.py
+-rw-r--r--   0 taste     (1001) taste     (1001)   116296 2023-06-28 11:43:14.000000 opengeode-4.1.9/opengeode/CGenerator.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    11750 2023-05-09 20:41:05.000000 opengeode-4.1.9/opengeode/Clipboard.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    29689 2022-12-08 11:28:57.000000 opengeode-4.1.9/opengeode/Connectors.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    38902 2023-06-28 11:43:14.000000 opengeode-4.1.9/opengeode/Helper.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    12719 2023-04-14 16:02:15.000000 opengeode-4.1.9/opengeode/Lander.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    82924 2023-01-22 14:09:04.000000 opengeode-4.1.9/opengeode/LlvmGenerator.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    18655 2023-05-10 20:42:44.000000 opengeode-4.1.9/opengeode/Pr.py
+-rw-r--r--   0 taste     (1001) taste     (1001)     2462 2022-05-15 08:02:36.000000 opengeode-4.1.9/opengeode/QGenSDL.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    15873 2023-01-03 10:27:29.000000 opengeode-4.1.9/opengeode/Renderer.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    36465 2023-06-28 11:43:14.000000 opengeode-4.1.9/opengeode/Statechart.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    73348 2022-07-25 21:01:25.000000 opengeode-4.1.9/opengeode/StgBackend.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    18658 2022-11-04 15:55:28.000000 opengeode-4.1.9/opengeode/TextInteraction.py
+-rw-r--r--   0 taste     (1001) taste     (1001)     1058 2022-05-15 08:02:36.000000 opengeode-4.1.9/opengeode/__init__.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    57607 2023-05-10 20:42:44.000000 opengeode-4.1.9/opengeode/genericSymbols.py
+-rw-r--r--   0 taste     (1001) taste     (1001) 21475752 2023-02-01 06:37:57.000000 opengeode-4.1.9/opengeode/icons.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    45021 2023-05-25 08:53:21.000000 opengeode-4.1.9/opengeode/ogAST.py
+-rw-r--r--   0 taste     (1001) taste     (1001)     9297 2023-05-25 08:53:21.000000 opengeode-4.1.9/opengeode/ogASTDumper.py
+-rw-r--r--   0 taste     (1001) taste     (1001)   341714 2023-06-28 11:43:14.000000 opengeode-4.1.9/opengeode/ogParser.py
+-rw-r--r--   0 taste     (1001) taste     (1001)   160565 2023-05-25 08:53:21.000000 opengeode-4.1.9/opengeode/opengeode.py
+-rw-r--r--   0 taste     (1001) taste     (1001)   183270 2023-05-10 20:42:44.000000 opengeode-4.1.9/opengeode/sdl92Lexer.py
+-rw-r--r--   0 taste     (1001) taste     (1001)  4922318 2023-05-10 20:42:44.000000 opengeode-4.1.9/opengeode/sdl92Parser.py
+-rw-r--r--   0 taste     (1001) taste     (1001)     2077 2022-10-06 09:09:20.000000 opengeode-4.1.9/opengeode/sdlHelp.py
+-rw-r--r--   0 taste     (1001) taste     (1001)    64900 2023-05-10 20:42:44.000000 opengeode-4.1.9/opengeode/sdlSymbols.py
+-rw-r--r--   0 taste     (1001) taste     (1001)     9445 2022-07-25 21:01:25.000000 opengeode-4.1.9/opengeode/undoCommands.py
+-rw-r--r--   0 taste     (1001) taste     (1001)      358 2023-06-28 11:43:14.000000 opengeode-4.1.9/opengeode/version.py
+drwxr-xr-x   0 taste     (1001) taste     (1001)        0 2023-06-28 11:43:26.389108 opengeode-4.1.9/opengeode.egg-info/
+-rw-r--r--   0 taste     (1001) taste     (1001)    44727 2023-06-28 11:43:26.000000 opengeode-4.1.9/opengeode.egg-info/PKG-INFO
+-rw-r--r--   0 taste     (1001) taste     (1001)      843 2023-06-28 11:43:26.000000 opengeode-4.1.9/opengeode.egg-info/SOURCES.txt
+-rw-r--r--   0 taste     (1001) taste     (1001)        1 2023-06-28 11:43:26.000000 opengeode-4.1.9/opengeode.egg-info/dependency_links.txt
+-rw-r--r--   0 taste     (1001) taste     (1001)       61 2023-06-28 11:43:26.000000 opengeode-4.1.9/opengeode.egg-info/entry_points.txt
+-rw-r--r--   0 taste     (1001) taste     (1001)       10 2023-06-28 11:43:26.000000 opengeode-4.1.9/opengeode.egg-info/top_level.txt
+-rw-r--r--   0 taste     (1001) taste     (1001)       38 2023-06-28 11:43:26.393108 opengeode-4.1.9/setup.cfg
+-rwxr-xr-x   0 taste     (1001) taste     (1001)     1220 2023-01-22 14:13:21.000000 opengeode-4.1.9/setup.py
```

### Comparing `opengeode-4.1.6/FONT-LICENCE.txt` & `opengeode-4.1.9/FONT-LICENCE.txt`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/LICENSE` & `opengeode-4.1.9/LICENSE`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/PKG-INFO` & `opengeode-4.1.9/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: opengeode
-Version: 4.1.6
+Version: 4.1.9
 Summary: A free SDL editor for TASTE
 Home-page: http://opengeode.net
 Author: Maxime Perrotin
 Author-email: maxime.perrotin@esa.int
 License: UNKNOWN
 Description: ![OpenGEODE Logo](icons/opengeode4.png)
         
@@ -129,14 +129,23 @@
         There is no runtime, and the generated code is not subject to any license.
         
         The fonts are the fonts from Ubuntu, check licence in file [FONT-LICENSE.TXT](https://github.com/esa/opengeode/blob/master/FONT-LICENCE.txt)
         The background pattern was downloaded from www.subtlepatterns.com
         
         Changelog
         =========
+        **4.1.9 (06/2023)**
+        - Fix support of the renaming clause in C and Ada backends
+        
+        **4.1.8 (06/2023)**
+        - Fix generation of inner calls to exported procedures in Ada backend
+        
+        **4.1.7 (06/2023)**
+        - Fix octet string synonym declaration using hex notation
+        
         **4.1.6 (05/2023)**
         - Fix more issues with  computation of modulo operator range (negative numbers)
         
         **4.1.5 (05/2023)**
         - Fix computation of modulo operator range
         
         **4.1.4 (05/2023)**
```

### Comparing `opengeode-4.1.6/README.md` & `opengeode-4.1.9/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -121,14 +121,23 @@
 There is no runtime, and the generated code is not subject to any license.
 
 The fonts are the fonts from Ubuntu, check licence in file [FONT-LICENSE.TXT](https://github.com/esa/opengeode/blob/master/FONT-LICENCE.txt)
 The background pattern was downloaded from www.subtlepatterns.com
 
 Changelog
 =========
+**4.1.9 (06/2023)**
+- Fix support of the renaming clause in C and Ada backends
+
+**4.1.8 (06/2023)**
+- Fix generation of inner calls to exported procedures in Ada backend
+
+**4.1.7 (06/2023)**
+- Fix octet string synonym declaration using hex notation
+
 **4.1.6 (05/2023)**
 - Fix more issues with  computation of modulo operator range (negative numbers)
 
 **4.1.5 (05/2023)**
 - Fix computation of modulo operator range
 
 **4.1.4 (05/2023)**
```

### Comparing `opengeode-4.1.6/opengeode/AdaGenerator.py` & `opengeode-4.1.9/opengeode/AdaGenerator.py`

 * *Files 1% similar despite different names*

```diff
@@ -86,14 +86,15 @@
 
 PROCESS_NAME = ""
 
 # reference to the ASN.1 Data view and to the visible variables (in scope)
 TYPES = None
 
 VARIABLES = {}
+ALIASES = {}
 MONITORS = {}
 LOCAL_VAR = {}
 # List of output signals and procedures
 OUT_SIGNALS = []
 PROCEDURES = []
 
 # Avoid Unicode characters, they cause occasional annoying issues
@@ -237,14 +238,16 @@
 
     pr = process.name.lower()
 
     LOG.info(f'Generating Ada code for process {process.name}')
 
     #  Prepare the AST for code generation (flatten states, etc.)
     no_renames = Helper.code_generation_preprocessing(process)
+    # Make the aliases visible
+    ALIASES.update(process.aliases)
 
     if not stop_condition:
         Helper.generate_asn1_datamodel(process)
 
     for (var_name, content) in process.variables.items():
         # filter out the aliases and put them in the local variable pool
         # to avoid unwanted prefixes when using them
@@ -284,26 +287,27 @@
     context_decl = []
     if not stop_condition:
         # but not in stop condition code, since we reuse the context type
         # of the state machine being observed
 
         # First add SDL constants (synonyms) - they can be used in the context
         for const in process.DV.SDL_Constants.values():
-            bkind = find_basic_type (const.type).kind
+            bconst = find_basic_type(const.type)
+            bkind = bconst.kind
             if bkind in ('IntegerType', 'RealType', 'NullType',
                          'BooleanType', 'Integer32Type', 'IntegerU8Type'):
                 val = const.value
                 if isinstance(val, ogAST.PrimSelector):
                     # synonym may reference a field of an ASN.1 constant
                     _, val, _ = expression(const.value, readonly=1)
             else:
                 # complex value - must be a ground expression
                 _, val, _ = expression(const.value, readonly=1)
                 if bkind in('SequenceOfType', 'OctetStringType', 'BitStringType'):
-                    val = array_content(const.value, val, bkind)
+                    val = array_content(const.value, val, bconst)
                 elif bkind == 'IA5StringType':
                     val = ia5string_raw(const.value)
                 elif bkind == 'NullType':
                     val = '0'
                 elif bkind not in ("EnumeratedType", "SequenceType"):
                     # should have been detected by ogParser
                     raise TypeError(f'Constant "{const.varName}" value is not a ground expression')
@@ -1300,15 +1304,16 @@
     local_decl = []
 
     # Add the traceability information
     code.extend(traceability(output))
     #code.extend(debug_trace())
 
     # Calling a procedure or RI usually needs a prefix (RI_.. or p_...)
-    # Exception is the _Transition procedures called after exported PIs (RPC)
+    # Exceptions are the _Transition procedures called after exported PIs (RPC)
+    # and the inner call of exported procedures
     need_prefix = True
 
     for out in output.output:
         signal_name = out['outputName']
         list_of_params = []
 
         if signal_name.lower() in ('write', 'writeln'):
@@ -1352,16 +1357,24 @@
         proc, out_sig = None, None
         try:
             out_sig, = [sig for sig in OUT_SIGNALS
                         if sig['name'].lower() == signal_name.lower()]
         except ValueError:
             # Not an output, try if it is an external or inner procedure
             try:
-                proc, = [sig for sig in PROCEDURES
+                candidates = [sig for sig in PROCEDURES
                             if sig.inputString.lower() == signal_name.lower()]
+                if not candidates:
+                    raise ValueError
+                if len(candidates) == 2:
+                    # there are 2 results when the procedure is exported
+                    # (happens in the case of a call of an inner procedure
+                    # that is exported)
+                    need_prefix = False
+                proc = candidates[0]
                 if proc.external:
                     out_sig = proc
             except ValueError:
                 # Last chance to find it: if it is an exported procedure,
                 # in that case an additional signal with _Transition suffix
                 # exists but is not visible in the model at this point
                 for sig in PROCEDURES:
@@ -1448,15 +1461,17 @@
                     code.append(f'{prefix}{name}(Dest_PID => {dest_pid});')
                 else:
                     code.append(f'{prefix}{name};')
         else:
             # inner procedure call without a RETURN statement
             # retrieve the procedure signature
             ident = proc.inputString
-            p, = [p for p in PROCEDURES if p.inputString.lower() == ident.lower()]
+            p, = [p for p in PROCEDURES
+                    if p.inputString.lower() == ident.lower()
+                    and not p.referenced]
 
             list_of_params = []
             for idx, param in enumerate(out.get('params', [])):
                 # Expected basic type of the parameter
                 param_type = p.fpar[idx]['type']
                 basic_param = find_basic_type (param_type)
 
@@ -1468,23 +1483,32 @@
                         (ogAST.PrimSequenceOf, ogAST.PrimStringLiteral)):
                     if basic_param.kind == 'IA5StringType':
                         p_id = ia5string_raw(param)
                     elif basic_param.kind.startswith('Integer'):
                         p_id = str(param.numeric_value)
                     else:
                         p_id = array_content(param, p_id, basic_param)
+                    # Here at least we need a temporary variable, it's never
+                    # possible to send a raw string as a parameter
+                    tmp_string = f'tmp{param.tmpVar}'
+                    local_decl.append(f'{tmp_string} : {type_name(param_type)} := {p_id};')
+                    p_id = tmp_string
 
                 code.extend(p_code)
                 local_decl.extend(p_local)
                 # no need to use temporary variables, we are in pure Ada
                 list_of_params.append(p_id)
+            if need_prefix:
+                full_name = f'p{SEPARATOR}{proc.inputString}'
+            else:
+                full_name = proc.inputString
             if list_of_params:
-                code.append(f'p{SEPARATOR}{proc.inputString}({", ".join(list_of_params)});')
+                code.append(f'{full_name}({", ".join(list_of_params)});')
             else:
-                code.append(f'p{SEPARATOR}{proc.inputString};')
+                code.append(f'{full_name};')
     return code, local_decl
 
 
 @generate.register(ogAST.TaskAssign)
 def _task_assign(task, **kwargs):
     ''' A list of assignments in a task symbol '''
     code, local_decl = [], []
@@ -1635,15 +1659,22 @@
     raise TypeError(f'Unsupported expression: {str(expr)}')
     return [], '', []
 
 
 @expression.register(ogAST.PrimVariable)
 def _primary_variable(prim, **kwargs):
     ''' Single variable reference '''
-    var = find_var(prim.value[0])
+    # The variable name is prim.value[0]. In principle it should be a single
+    # name.. However if it was originally an alias, it may have been renamed
+    # to a string with field accesses. In that case we must take only the
+    # first element to get the actual variable name.
+    name = prim.value[0]
+    if '.' in name:
+        name = name.split('.')[0]
+    var = find_var(name)
     if (not var) or is_local(var):
         sep = ''
     else:
         sep = LPREFIX + '.'
 
     ada_string = f'{sep}{prim.value[0]}'
 
@@ -1906,15 +1937,17 @@
         #  For observers (model checking) only: return the state status
         #  The procedure is generated at process level when it is needed
         ada_string += f"Observer_State_Status"
 
     else:
         # inner procedure call (with a RETURN statement)
         # retrieve the procedure signature
-        p, = [p for p in PROCEDURES if p.inputString.lower() == ident.lower()]
+        p, = [p for p in PROCEDURES
+                if p.inputString.lower() == ident.lower()
+                and not p.referenced]
 
         # for inner procedures we do not use a temporary variable because
         # we remain in Ada and therefore in parameters do not need to
         # be pointers (in out).
         ada_string += f'p{SEPARATOR}{ident}' + (' (' if params else '')
         # Take all params and join them with commas
         list_of_params = []
```

### Comparing `opengeode-4.1.6/opengeode/Asn1scc.py` & `opengeode-4.1.9/opengeode/Asn1scc.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/CGenerator.py` & `opengeode-4.1.9/opengeode/CGenerator.py`

 * *Files 1% similar despite different names*

```diff
@@ -22,14 +22,15 @@
 from . import Helper, ogAST
 
 LOG = logging.getLogger(__name__)
 
 __all__ = ['generate']
 
 VARIABLES = {}
+ALIASES = {}
 LOCAL_OUT_PARS = {}
 LOCAL_VAR = {}
 LOCAL_VARIABLE_TYPES = {}
 OUT_SIGNALS = []
 PROCEDURES = []
 
 UNICODE_SEP = '___'
@@ -598,14 +599,16 @@
 '''.format(pr=process_name)
 
 
     LOG.info('Generating C code for process ' + str(process_name))
 
     #  Prepare the AST for code generation (flatten states, etc.)
     no_renames = Helper.code_generation_preprocessing(process)
+    # Make the aliases visible
+    ALIASES.update(process.aliases)
 
     Helper.generate_asn1_datamodel(process)
 
     # Make an mapping {input: {state: transition...}} in order to easily
     # generate the lookup tables for the state machine runtime
     mapping = process.input_mapping
 
@@ -1163,21 +1166,27 @@
     raise TypeError('Unsupported expression: ' + str(expr))
     return [], '', []
 
 
 @expression.register(ogAST.PrimVariable)
 def _primary_variable(prim):
     ''' Single variable reference '''
-    var = find_var(prim.value[0])
-    if prim.value[0] in LOCAL_OUT_PARS:
-        string = u'(*{name})'.format(name=prim.value[0])
-    elif not var or is_local(var):
-        string = u'{name}'.format(name=prim.value[0])
+    name = prim.value[0]
+    if '.' in name:
+        name = name.split('.')[0]
+        _, qualified = ALIASES[prim.renamed_from]
+        _, string, _ = expression(qualified)
     else:
-        string = u'{lp}.{name}'.format(lp=LPREFIX, name=prim.value[0])
+        var = find_var(name)
+        if prim.value[0] in LOCAL_OUT_PARS:
+            string = u'(*{name})'.format(name=prim.value[0])
+        elif not var or is_local(var):
+            string = u'{name}'.format(name=prim.value[0])
+        else:
+            string = u'{lp}.{name}'.format(lp=LPREFIX, name=prim.value[0])
 
     return [], str(string.lower()), []
 
 
 @expression.register(ogAST.PrimCall)
 def _prim_call(prim):
     global math_include
```

### Comparing `opengeode-4.1.6/opengeode/Clipboard.py` & `opengeode-4.1.9/opengeode/Clipboard.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/Connectors.py` & `opengeode-4.1.9/opengeode/Connectors.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/Helper.py` & `opengeode-4.1.9/opengeode/Helper.py`

 * *Files 1% similar despite different names*

```diff
@@ -610,14 +610,20 @@
 
 
 @rename_everything.register(ogAST.PrimVariable)
 def _rename_path(ast, from_name, to_name):
     ''' Ultimate seek point for the renaming: primary path/variables '''
     if ast.value[0].lower() == from_name.lower():
         ast.value[0] = to_name
+        # Renaming a variable can be due to the use of an alias
+        # in that case we must keep track of the alias name because
+        # the renamging may lead to what actually should not be
+        # a PrimVariable but a PrimSelector.
+        # Keeping the original name allows backend to resolve this.
+        ast.renamed_from = from_name
 
 
 @rename_everything.register(ogAST.PrimCall)
 def _rename_primcall(ast, from_name, to_name):
     ''' PrimCall is used e.g. by function "length" (special operators) '''
     for each in ast.value[1]['procParams']:
         rename_everything(each, from_name, to_name)
```

### Comparing `opengeode-4.1.6/opengeode/Lander.py` & `opengeode-4.1.9/opengeode/Lander.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/LlvmGenerator.py` & `opengeode-4.1.9/opengeode/LlvmGenerator.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/Pr.py` & `opengeode-4.1.9/opengeode/Pr.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/QGenSDL.py` & `opengeode-4.1.9/opengeode/QGenSDL.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/Renderer.py` & `opengeode-4.1.9/opengeode/Renderer.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/Statechart.py` & `opengeode-4.1.9/opengeode/Statechart.py`

 * *Files 0% similar despite different names*

```diff
@@ -659,15 +659,15 @@
             elif each:
                 valid_inputs.add(each.lower())
     except IOError:
         valid_inputs = input_signals
         config_params = config_params or {"-Nfontsize" : "14",
                          "-Efontsize" : "8",
                          "-Gsplines"  : "curved",
-                         "-Gsep"      : "0.3",
+                         "-Gsep"      : "2",
                          "-Gdpi"      : "72",
                          "-Gstart"    : "random10",
                          "-Goverlap"  : "scale",
                          "-Nstyle"    : "rounded",
                          "-Nshape"    : "record",
                          "-Elen"      : "1"}
         LOG.info ("... valid signals: " + ", ".join(valid_inputs))
```

### Comparing `opengeode-4.1.6/opengeode/StgBackend.py` & `opengeode-4.1.9/opengeode/StgBackend.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/TextInteraction.py` & `opengeode-4.1.9/opengeode/TextInteraction.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/__init__.py` & `opengeode-4.1.9/opengeode/__init__.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/genericSymbols.py` & `opengeode-4.1.9/opengeode/genericSymbols.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/icons.py` & `opengeode-4.1.9/opengeode/icons.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/ogAST.py` & `opengeode-4.1.9/opengeode/ogAST.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/ogASTDumper.py` & `opengeode-4.1.9/opengeode/ogASTDumper.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/ogParser.py` & `opengeode-4.1.9/opengeode/ogParser.py`

 * *Files 0% similar despite different names*

```diff
@@ -747,15 +747,14 @@
         return_type = new_ref_type(sort) #types()[sort].type
         return (return_type, warnings)
 
     elif name in ('to_selector', 'to_enum'):
         if len(params) != 2:
             raise TypeError(name + " takes 2 parameters: variable, type")
         variable, target_type = params
-        #breakpoint()
         variable_sort = find_basic_type(variable.exprType)
         if variable_sort.kind == 'UnknownType':
             raise TypeError(name + ': variable not found (parameter 1)')
         if variable_sort.kind != 'EnumeratedType':
             raise TypeError(name + ': First parameter is not an enumerated')
         sort_name = target_type.value[0]  #  raw string of the type to cast
 
@@ -1470,14 +1469,20 @@
         if lowest_a != lowest_b:
             mismatch = '"{}" is not "{}"'.format(type_a.ReferencedTypeName,
                                                  type_b.ReferencedTypeName)
         else:
             # We flag the fact that one type is a subtype of the other type
             # to avoid the signed/unsigned check to raise an error
             is_same_type = True
+    # there is another case where we can consider that the types are the same,
+    # in some mathematical operations like power, that can return either
+    # signed or unsigned value, according to what they are used with.
+    if any(sort.__name__ == 'Power' for sort in (type_a, type_b)):
+        is_same_type = True
+
     type_a = find_basic_type(type_a)
     type_b = find_basic_type(type_b)
 
     if type_a == type_b:
         return warnings
     elif NUMERICAL in (type_a, type_b) and is_numeric(type_a) \
             and is_numeric(type_b):
@@ -2488,18 +2493,24 @@
         # no numbers, two ASN.1 types. raise an error if there is a
         # signed/unsigned mismatch
         # otherwise (sign ok), set the computed bounds
         # before concluding on the mismatch, check that one side is not
         # a forloop index with positive values (it is signed!)
         else:
             sign_mismatch = False
-            if (minL < 0) != (minR < 0):
+            # Test only integers, not reals!!
+            if is_integer(expr.left.exprType) and is_integer(expr.right.exprType) and (minL < 0) != (minR < 0):
                 sign_mismatch = \
                         (minL >= 0 and basic_left.kind  != 'Integer32Type')\
                      or (minR >= 0 and basic_right.kind != 'Integer32Type')
+                # Exception: if one side is a "power" expression, it does
+                # not need to match
+                if expr.left.exprType.__name__ == 'Power' or expr.right.exprType.__name__ == 'Power':
+                    sign_mismatch = False
+
             if sign_mismatch:
                 msg = '"' + expr.left.inputString + '" is ' + ("un"
                       if minL >= 0 else "") + 'signed while "' \
                               + expr.right.inputString + '" is not'
                 errors.append(error(root, msg))
             else:  #  sign is consistent on both sides
                 bound_min = str(float(bounds['Min']))
@@ -4304,31 +4315,31 @@
             else:
                 warnings.append(
                     'Unsupported synonym construct' +
                     sdl92Parser.tokenNamesMap[child.type])
         if asn1_sort is not None:
             # Use the right type spelling
             sort = asn1_sort.ReferencedTypeName
-        return name, sort, ground
+        return name, sort, ground, asn1_sort
 
     for child in root.getChildren():
         if child.type == lexer.SYNONYM:
-            name, sort, value = parse_synonym(child)
+            name, sort, value, asn1_sort = parse_synonym(child)
 
         if name and sort and value:
             nameDash = name.replace('_', '-')
             sortDash = sort.replace('_', '-')
 
             # The value field will depend on the type..If the constant is a
             # numerical value then we transform it to a number, because it
             # can be used by the parser for range checks
             # Same for booleans and enumerated. But complex types are kept as
             # expressions
             if isinstance(value, (ogAST.PrimOctetStringLiteral,
-                                  ogAST.PrimBitStringLiteral)):
+                                  ogAST.PrimBitStringLiteral)) and is_numeric(asn1_sort):
                 concrete_val = value.numeric_value
             elif is_numeric(value.exprType) or is_boolean(value.exprType):
                 # value.value is an array of one element
                 try:
                     concrete_val, = value.value
                 except:
                     # If not, it is because this is a PrimSelector
```

### Comparing `opengeode-4.1.6/opengeode/opengeode.py` & `opengeode-4.1.9/opengeode/opengeode.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/sdl92Lexer.py` & `opengeode-4.1.9/opengeode/sdl92Lexer.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/sdl92Parser.py` & `opengeode-4.1.9/opengeode/sdl92Parser.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/sdlHelp.py` & `opengeode-4.1.9/opengeode/sdlHelp.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/sdlSymbols.py` & `opengeode-4.1.9/opengeode/sdlSymbols.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode/undoCommands.py` & `opengeode-4.1.9/opengeode/undoCommands.py`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/opengeode.egg-info/PKG-INFO` & `opengeode-4.1.9/opengeode.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: opengeode
-Version: 4.1.6
+Version: 4.1.9
 Summary: A free SDL editor for TASTE
 Home-page: http://opengeode.net
 Author: Maxime Perrotin
 Author-email: maxime.perrotin@esa.int
 License: UNKNOWN
 Description: ![OpenGEODE Logo](icons/opengeode4.png)
         
@@ -129,14 +129,23 @@
         There is no runtime, and the generated code is not subject to any license.
         
         The fonts are the fonts from Ubuntu, check licence in file [FONT-LICENSE.TXT](https://github.com/esa/opengeode/blob/master/FONT-LICENCE.txt)
         The background pattern was downloaded from www.subtlepatterns.com
         
         Changelog
         =========
+        **4.1.9 (06/2023)**
+        - Fix support of the renaming clause in C and Ada backends
+        
+        **4.1.8 (06/2023)**
+        - Fix generation of inner calls to exported procedures in Ada backend
+        
+        **4.1.7 (06/2023)**
+        - Fix octet string synonym declaration using hex notation
+        
         **4.1.6 (05/2023)**
         - Fix more issues with  computation of modulo operator range (negative numbers)
         
         **4.1.5 (05/2023)**
         - Fix computation of modulo operator range
         
         **4.1.4 (05/2023)**
```

### Comparing `opengeode-4.1.6/opengeode.egg-info/SOURCES.txt` & `opengeode-4.1.9/opengeode.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `opengeode-4.1.6/setup.py` & `opengeode-4.1.9/setup.py`

 * *Files identical despite different names*


# Comparing `tmp/sdd2rdf-1.0.4.tar.gz` & `tmp/sdd2rdf-1.1.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "sdd2rdf-1.0.4.tar", last modified: Mon Dec 19 03:26:31 2022, max compression
+gzip compressed data, was "sdd2rdf-1.1.0.tar", last modified: Wed Jun 28 15:21:51 2023, max compression
```

## Comparing `sdd2rdf-1.0.4.tar` & `sdd2rdf-1.1.0.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0 jamie      (501) staff       (20)        0 2022-12-19 03:26:31.211187 sdd2rdf-1.0.4/
--rw-r--r--   0 jamie      (501) staff       (20)    11357 2017-02-17 16:59:51.000000 sdd2rdf-1.0.4/LICENSE
--rw-r--r--   0 jamie      (501) staff       (20)      576 2022-12-19 03:26:31.210914 sdd2rdf-1.0.4/PKG-INFO
--rw-r--r--   0 jamie      (501) staff       (20)     1241 2020-11-25 18:51:52.000000 sdd2rdf-1.0.4/README.md
-drwxr-xr-x   0 jamie      (501) staff       (20)        0 2022-12-19 03:26:31.208408 sdd2rdf-1.0.4/sdd2rdf/
--rw-r--r--   0 jamie      (501) staff       (20)      303 2020-11-25 18:51:52.000000 sdd2rdf-1.0.4/sdd2rdf/__init__.py
--rw-r--r--   0 jamie      (501) staff       (20)   111243 2022-05-10 17:59:06.000000 sdd2rdf-1.0.4/sdd2rdf/sdd2rdf.py
--rw-r--r--   0 jamie      (501) staff       (20)    10147 2022-12-14 04:16:13.000000 sdd2rdf-1.0.4/sdd2rdf/sdd2setl.py
-drwxr-xr-x   0 jamie      (501) staff       (20)        0 2022-12-19 03:26:31.210504 sdd2rdf-1.0.4/sdd2rdf/templates/
--rw-r--r--   0 jamie      (501) staff       (20)    10272 2022-12-14 00:50:33.000000 sdd2rdf-1.0.4/sdd2rdf/templates/sdd_setl_template.jinja
-drwxr-xr-x   0 jamie      (501) staff       (20)        0 2022-12-19 03:26:31.210250 sdd2rdf-1.0.4/sdd2rdf.egg-info/
--rw-r--r--   0 jamie      (501) staff       (20)      576 2022-12-19 03:26:31.000000 sdd2rdf-1.0.4/sdd2rdf.egg-info/PKG-INFO
--rw-r--r--   0 jamie      (501) staff       (20)      315 2022-12-19 03:26:31.000000 sdd2rdf-1.0.4/sdd2rdf.egg-info/SOURCES.txt
--rw-r--r--   0 jamie      (501) staff       (20)        1 2022-12-19 03:26:31.000000 sdd2rdf-1.0.4/sdd2rdf.egg-info/dependency_links.txt
--rw-r--r--   0 jamie      (501) staff       (20)       52 2022-12-19 03:26:31.000000 sdd2rdf-1.0.4/sdd2rdf.egg-info/entry_points.txt
--rw-r--r--   0 jamie      (501) staff       (20)       90 2022-12-19 03:26:31.000000 sdd2rdf-1.0.4/sdd2rdf.egg-info/requires.txt
--rw-r--r--   0 jamie      (501) staff       (20)        8 2022-12-19 03:26:31.000000 sdd2rdf-1.0.4/sdd2rdf.egg-info/top_level.txt
--rw-r--r--   0 jamie      (501) staff       (20)       38 2022-12-19 03:26:31.211274 sdd2rdf-1.0.4/setup.cfg
--rw-r--r--   0 jamie      (501) staff       (20)     1499 2022-12-19 03:24:59.000000 sdd2rdf-1.0.4/setup.py
+drwxr-xr-x   0 jamie      (501) staff       (20)        0 2023-06-28 15:21:51.988533 sdd2rdf-1.1.0/
+-rw-r--r--   0 jamie      (501) staff       (20)    11357 2017-02-17 16:59:51.000000 sdd2rdf-1.1.0/LICENSE
+-rw-r--r--   0 jamie      (501) staff       (20)      557 2023-06-28 15:21:51.988197 sdd2rdf-1.1.0/PKG-INFO
+-rw-r--r--   0 jamie      (501) staff       (20)     1241 2020-11-25 18:51:52.000000 sdd2rdf-1.1.0/README.md
+drwxr-xr-x   0 jamie      (501) staff       (20)        0 2023-06-28 15:21:51.985269 sdd2rdf-1.1.0/sdd2rdf/
+-rw-r--r--   0 jamie      (501) staff       (20)      303 2020-11-25 18:51:52.000000 sdd2rdf-1.1.0/sdd2rdf/__init__.py
+-rw-r--r--   0 jamie      (501) staff       (20)   111243 2023-06-28 15:18:59.000000 sdd2rdf-1.1.0/sdd2rdf/sdd2rdf.py
+-rw-r--r--   0 jamie      (501) staff       (20)    14603 2023-06-27 22:04:38.000000 sdd2rdf-1.1.0/sdd2rdf/sdd2setl.py
+drwxr-xr-x   0 jamie      (501) staff       (20)        0 2023-06-28 15:21:51.987735 sdd2rdf-1.1.0/sdd2rdf/templates/
+-rw-r--r--   0 jamie      (501) staff       (20)    11431 2023-06-28 03:49:30.000000 sdd2rdf-1.1.0/sdd2rdf/templates/sdd_setl_template.jinja
+drwxr-xr-x   0 jamie      (501) staff       (20)        0 2023-06-28 15:21:51.987288 sdd2rdf-1.1.0/sdd2rdf.egg-info/
+-rw-r--r--   0 jamie      (501) staff       (20)      557 2023-06-28 15:21:51.000000 sdd2rdf-1.1.0/sdd2rdf.egg-info/PKG-INFO
+-rw-r--r--   0 jamie      (501) staff       (20)      315 2023-06-28 15:21:51.000000 sdd2rdf-1.1.0/sdd2rdf.egg-info/SOURCES.txt
+-rw-r--r--   0 jamie      (501) staff       (20)        1 2023-06-28 15:21:51.000000 sdd2rdf-1.1.0/sdd2rdf.egg-info/dependency_links.txt
+-rw-r--r--   0 jamie      (501) staff       (20)       51 2023-06-28 15:21:51.000000 sdd2rdf-1.1.0/sdd2rdf.egg-info/entry_points.txt
+-rw-r--r--   0 jamie      (501) staff       (20)       90 2023-06-28 15:21:51.000000 sdd2rdf-1.1.0/sdd2rdf.egg-info/requires.txt
+-rw-r--r--   0 jamie      (501) staff       (20)        8 2023-06-28 15:21:51.000000 sdd2rdf-1.1.0/sdd2rdf.egg-info/top_level.txt
+-rw-r--r--   0 jamie      (501) staff       (20)       38 2023-06-28 15:21:51.988639 sdd2rdf-1.1.0/setup.cfg
+-rw-r--r--   0 jamie      (501) staff       (20)     1499 2023-06-28 15:18:29.000000 sdd2rdf-1.1.0/setup.py
```

### Comparing `sdd2rdf-1.0.4/LICENSE` & `sdd2rdf-1.1.0/LICENSE`

 * *Files identical despite different names*

### Comparing `sdd2rdf-1.0.4/README.md` & `sdd2rdf-1.1.0/README.md`

 * *Files identical despite different names*

### Comparing `sdd2rdf-1.0.4/sdd2rdf/sdd2rdf.py` & `sdd2rdf-1.1.0/sdd2rdf/sdd2rdf.py`

 * *Files 1% similar despite different names*

```diff
@@ -61,15 +61,16 @@
         # Check for entry in column list
         for item in explicit_entry_list :
             if args[0] == item.Column :
                 if (len(args) == 2) :
                     return "<" + prefixes[kb] + args[0].replace(" ","_").replace(",","").replace("(","").replace(")","").replace("/","-").replace("\\","-") + "-" + args[1] + ">"
                 else :
                     return "<" + prefixes[kb] + args[0].replace(" ","_").replace(",","").replace("(","").replace(")","").replace("/","-").replace("\\","-") + ">"
-        return '"' + args[0] + "\"^^xsd:string"
+        #return '"' + args[0] + "\"^^xsd:string"
+        return args[0]
     else :
         return args[0]
 
 def checkImplicit(input_word) :
     try:
         if (input_word[:2] == "??") :
             return True
@@ -1189,40 +1190,40 @@
                                         if cb_tuple != {} :
                                             if a_tuple["Column"] in cb_tuple :
                                                 #print(a_tuple["Column"])
                                                 for tuple_row in cb_tuple[a_tuple["Column"]] :
                                                     #print(tuple_row)
                                                     if ("Code" in tuple_row) and (str(tuple_row['Code']) == str(row[col_headers.index(a_tuple["Column"])+1]) ):
                                                         #print(tuple_row['Code'])
-                                                        if ("Class" in tuple_row) and (tuple_row['Class'] is not "") :
+                                                        if ("Class" in tuple_row) and (tuple_row['Class'] != "") :
                                                             if ',' in tuple_row['Class'] :
                                                                 classTerms = parseString(tuple_row['Class'],',')
                                                                 for classTerm in classTerms :
                                                                     assertionString += " ;\n        <" + rdf.type + ">    " + convertImplicitToKGEntry(codeMapper(classTerm))
                                                             else :
                                                                 assertionString += " ;\n        <" + rdf.type + ">    "+ convertImplicitToKGEntry(codeMapper(tuple_row['Class']))
-                                                        if ("Resource" in tuple_row) and (tuple_row['Resource'] is not "") :
+                                                        if ("Resource" in tuple_row) and (tuple_row['Resource'] != "") :
                                                             if ',' in tuple_row['Resource'] :
                                                                 classTerms = parseString(tuple_row['Resource'],',')
                                                                 for classTerm in classTerms :
                                                                     assertionString += " ;\n        <" + rdf.type + ">    " + convertImplicitToKGEntry(codeMapper(classTerm))
                                                             else :
                                                                 assertionString += " ;\n        <" + rdf.type + ">    " + convertImplicitToKGEntry(codeMapper(tuple_row['Resource']))
-                                                        if ("Label" in tuple_row) and (tuple_row['Label'] is not "") :
+                                                        if ("Label" in tuple_row) and (tuple_row['Label'] != "") :
                                                             assertionString += " ;\n        <" + properties_tuple["Label"] + ">    \"" + tuple_row['Label'] + "\"^^xsd:string"
-                                                        if ("Comment" in tuple_row) and (tuple_row['Comment'] is not "") :
+                                                        if ("Comment" in tuple_row) and (tuple_row['Comment'] != "") :
                                                             assertionString += " ;\n        <" + properties_tuple["Comment"] + ">    \"" + tuple_row['Comment'] + "\"^^xsd:string"
-                                                        if ("Definition" in tuple_row) and (tuple_row['Definition'] is not "") :
+                                                        if ("Definition" in tuple_row) and (tuple_row['Definition'] != "") :
                                                             assertionString += " ;\n        <" + properties_tuple["Definition"] + ">    \"" + tuple_row['Definition'] + "\"^^xsd:string"
                                         #print(str(row[col_headers.index(a_tuple["Column"])]))
                                         try :
                                             if str(row[col_headers.index(a_tuple["Column"])+1]) == "nan" :
                                                 pass
                                             # Check if Format was populated in the DM row of the current data point
-                                            if ("Format" in a_tuple) and (a_tuple['Format'] is not "") :
+                                            if ("Format" in a_tuple) and (a_tuple['Format'] != "") :
                                                 # Check if an xsd prefix is included in the populated Format cell
                                                 if("xsd:" in a_tuple['Format']):
                                                     assertionString += " ;\n        <" + properties_tuple["Value"] + ">    \"" + str(row[col_headers.index(a_tuple["Column"])+1]) + "\"^^" + a_tuple['Format']
                                                 # If the Format cell is populated, but the xsd prefix isn't specified, do a string match over the set of primitive xsd types
                                                 elif a_tuple['Format'] in xsd_datatype_list :
                                                     assertionString += " ;\n        <" + properties_tuple["Value"] + ">    \"" + str(row[col_headers.index(a_tuple["Column"])+1]) + "\"^^xsd:" + a_tuple['Format']
                                             # If the Format cell isn't populated, check is the data value is an integer
```

### Comparing `sdd2rdf-1.0.4/sdd2rdf/sdd2setl.py` & `sdd2rdf-1.1.0/sdd2rdf/sdd2setl.py`

 * *Files 24% similar despite different names*

```diff
@@ -5,14 +5,16 @@
 import argparse
 import numpy as np
 import re
 from setlr import isempty
 from slugify import slugify
 import io
 import puremagic
+import json
+import fnmatch
 
 base_context = {
     "void" : "http://rdfs.org/ns/void#",
     "csvw" : "http://www.w3.org/ns/csvw#",
     "sio": "http://semanticscience.org/resource/",
     "owl": "http://www.w3.org/2002/07/owl#",
     "rdf": "http://www.w3.org/1999/02/22-rdf-syntax-ns#",
@@ -30,33 +32,53 @@
     "Unit" : { "@id" : "sio:hasUnit", "@type" : "@id"},
     "Value" : { "@id" : "sio:hasValue"},
     "hasStart" : { "@id" : "sio:hasStartTime"},
     "hasEnd" : { "@id" : "sio:hasEndTime"},
     "TimeInterval" : {"@id" : "sio:TimeInterval"},
     "wasDerivedFrom" : { "@id" : "prov:wasDerivedFrom", "@type" : "@id"},
     "wasGeneratedBy" : { "@id" : "prov:wasGeneratedBy", "@type" : "@id"},
+    "a" : {"@id": "rdf:type"}
 }
 
+
+
 class SemanticDataDictionary:
     columns = None
     codebook = None
     resource_codebook = None
     context = None
     codemap = None
     timeline = None
     infosheet = None
     sdd_format = None
     sheets = None
     data = None
+    data_type = None
 
-    def __init__(self, sdd_path, prefix):
+    def __init__(self, sdd_path, prefix, data_type):
         self.sdd_path = sdd_path
         self.prefix = prefix
+        self.data_type = data_type
         self.load()
 
+    def _expand_codebook(self):
+        codebook = dict(self.codebook)
+        for key, value in self.codebook.items():
+            for column in self.columns.keys():
+                if key[0] != column and fnmatch.fnmatch(column, key[0]):
+                    codebook[(column,key[1])] = value
+        self.codebook = codebook
+
+        resource_codebook = dict(self.resource_codebook)
+        for key, value in self.resource_codebook.items():
+            for column in self.columns.keys():
+                if key != column and fnmatch.fnmatch(column, key):
+                    resource_codebook[column] = value
+        self.resource_codebook = resource_codebook
+
     def load(self):
         infosheet = self._get_table()
         self.infosheet = dict([(row.Attribute, row.Value)
                                for i, row in infosheet.iterrows()
                                if not isempty(row.Value)])
 
         codemap = self._get_table('Code Mapping')
@@ -84,60 +106,123 @@
             prefixes = self._get_table('Prefixes')
             prefix_dict = dict([(str(row.prefix), row.url)
                                 for i, row in prefixes.iterrows()
                                 if not isempty(row.prefix) and not isempty(row.url)])
             self.context.update(prefix_dict)
 
         dm = self._get_table('Dictionary Mapping')
-        self.columns = dict([(col.Column, col.to_dict())
+        self.columns = dict([(col.Column, col.dropna().to_dict())
                              for i, col in dm.iterrows()
                              if not isempty(col['Column'])])
+        for key, col in self.columns.items():
+            col['Column'] = col['Column'].strip()
         timeline = self._get_table('Timeline')
         for i, t in timeline.iterrows():
             if isempty(t.Name):
                 continue
             if t.Name in self.columns:
                 self.columns[t.Name].update(t.to_dict())
             else:
                 self.columns[t.Name] = t.to_dict()
                 self.columns[t.Name]['Column'] = t.Name
         self.column_templates = {}
         self.value_templates = {}
         for key, col in self.columns.items():
+            col['children'] = []
+        for key, col in self.columns.items():
             for annotation in ['Unit','Format','Role','Relation']:
                 if annotation in col and not isempty(col[annotation]):
                     col[annotation] = self.codemap.get(col[annotation],col[annotation])
             for annotation in ['attributeOf','wasDerivedFrom','wasGeneratedBy', 'inRelationTo']:
                 if annotation in col:
                     col[annotation] = self._split(col[annotation])
             for annotation in ['Attribute','Entity','Type']:
                 if annotation in col and not isempty(col[annotation]):
                     col[annotation] = self._split_and_map(col[annotation])
-            self.value_templates[slugify(col['Column'],separator="_")] = "{{row.get('%s')}}"%col['Column']
-            #self.column_templates[slugify(col['Column'],separator="_")] = "{{row.get('%s').replace(' ','_').replace('>','').replace('\\','')}}"%col['Column']
-            self.column_templates[slugify(col['Column'],separator="_")] = "{{slugify(str(row.get('%s')),separator='_',lowercase=False)}}"%col['Column']
-            if not col['Column'].startswith('??'):
+            et = element_templates[self.data_type]
+            column_id = slugify(col['Column'],separator="_")
+            parent = col.get('SelectorParent','__tree_root__')
+            if parent != '__tree_root__':
+                self.columns[parent]['children'].append(col)
+                col['parent_column'] = self.columns[parent]
+            selector = col.get('Selector', None)
+#            if parent is None:
+#                col['iterator'] = '[row]'
+#            else:
+            if 'Selector' in col:
+                col['iterator'] = et['iterate_template']%(parent, selector)
+            else:
+                col['iterator'] = et['iterate_template']
+            self.value_templates[column_id] = et['value_template']%col['Column']
+            self.column_templates[column_id] = et['column_template']%col['Column']
+            col['value_access'] = et['value'] % col['Column']
+            if not col['Column'].startswith('??') and not col['Column'].startswith('__'):
                 col['@value'] = '{%s}'%slugify(col['Column'],separator="_")
             if 'Format' in col and not isempty(col['Format']):
                 value_type = col['Format'].split("^^")
                 if len(value_type) == 1:
                     col['@type'] = value_type[0]
                 elif len(value_type) == 2:
                     col['@type'] = value_type[1]
                     if len(value_type[0]) > 0:
                         col['@value'] = value_type[0]
+        self.root_columns = [c for c in self.columns.values() if 'SelectorParent' not in c]
+        self.root_columns = [{
+            'Column': '__tree_root__',
+            'iterator': '[row]',
+            'children': self.root_columns
+        }]
+        for col in self.root_columns + list(self.columns.values()):
+            # create a @with statement to set the local scope for this subtree.
+            if len(col['children']) > 0:
+                col['leaves'] = []
+                col['branches'] = []
+                assignments = []
+                variables = []
+                for child in col['children']:
+                    if len(child['children']) > 0:
+                        col['branches'].append(child)
+                    else:
+                        col['leaves'].append(child)
+                        if not child['Column'].startswith('??'):
+                            variables.append("%s" % child['Column'])
+                            assignments.append('%s[0] if len(%s) > 0 else None, ' % (child['iterator'].replace('\\','\\\\'), child['iterator'].replace('\\','\\\\')))
+                col['with'] = ['('] + assignments + [') as ', ', '.join(variables)]
+            del col['children']
+                #print(col.get('Column',"root"))
+                #print(col['with'])
+                #print(col['leaves'])
+                #print(col['branches'])
+
+        #print(json.dumps(self.root_columns, indent=4))
+
+        self._expand_codebook()
+
         for col in self.columns.values():
             default = slugify(col['Column'],separator="_")+'_{i}'
-
             template = col.get('Template', default)
+            print(col['Column'], template)
             if isempty(template):
                 template = slugify(col['Column'],separator="_")+'_{i}'
 
             template = re.sub(r'(:<=\{).*(:=\})',lambda x:str(slugify(x.group(0),separator="_")),template)
-            col['uri_template'] = template.format(i='{{name}}',**self.column_templates)
+            formatted_template = template.format(i='{{name}}',**self.column_templates)
+            if col['Column'] in self.resource_codebook:
+                formatted_template = ''.join([
+                    "{% if '",
+                    col['Column'],
+                    "' in resource_codebook %}{{resource_codebook['",
+                    col['Column'],
+                    "'][",
+                    col['value_access'],
+                    "]}}{% else %}",
+                    formatted_template,
+                    "{% endif %}"])
+            col['uri_template'] = formatted_template
+
             if '@value' in col:
                 col['@value'] = col['@value'].format(i='{{name}}',**self.value_templates)
 
     loaders = {
         "text/csv" : pd.read_csv,
         'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet': pd.read_excel,
         'application/vnd.openxmlformats-officedocument.wordprocessingml.document': pd.read_excel
@@ -187,27 +272,54 @@
         return result
 
     def _split_and_map(self, value):
         if isempty(value):
             return []
         return [self.codemap.get(x,x) for x in self._split(value)]
 
+element_templates = {
+    'setl:XML': {
+        # How are we going to handle nested iteration?
+        'value_template' : "{{%s}}",
+        'value' : "%s",
+        'iterate_template' : "%s.xpath('%s')",
+        'column_template' : "{{slugify(str(%s),separator='_',lowercase=False)}}"
+    },
+    "setl:Excel" : {
+        'value_template' : "{{row.get('%s')}}",
+        'value' : "row.get('%s')",
+        'iterate_template' : "[row]",
+        'column_template' : "{{slugify(str(row.get('%s')),separator='_',lowercase=False)}}"
+    },
+    "csvw:Table" : {
+        'value_template' : "{{row.get('%s')}}",
+        'value' : "row.get('%s')",
+        'iterate_template' : "[row]",
+        'column_template' : "{{slugify(str(row.get('%s')),separator='_',lowercase=False)}}"
+    }
+}
+
 file_types = {
     "text/csv" : "csvw:Table",
     "csv" : "csvw:Table",
+    "application/xml" : 'setl:XML',
+    'text/xml': 'setl:XML',
+    'xml' : 'setl:XML',
     "excel" : "setl:Excel",
     'application/vnd.ms-excel': "setl:Excel",
     'application/vnd.openxmlformats-officedocument.spreadsheetml.sheet': "setl:Excel",
 }
 
 def sdd2setl(semantic_data_dictionary, prefix, datafile,
              format='csv', delimiter=',', sheetname=None, output=None, dataset_uri=None):
     if dataset_uri is None:
         dataset_uri = prefix+'dataset'
-    sdd = SemanticDataDictionary(semantic_data_dictionary,prefix)
+    if format != 'csv':
+        delimiter = None
+    sdd = SemanticDataDictionary(semantic_data_dictionary,prefix, data_type=file_types[format])
     env = Environment(loader=PackageLoader('sdd2rdf', 'templates'))
     template = env.get_template('sdd_setl_template.jinja')
     output = template.render(sdd=sdd,
                              prefix=prefix,
                              data=datafile,
                              data_type=file_types[format],
                              delimiter=delimiter,
@@ -221,15 +333,15 @@
 def sdd2setl_main():
     parser = argparse.ArgumentParser()
     parser.add_argument("semantic_data_dictionary")
     parser.add_argument("prefix")
     parser.add_argument("data_file")
     parser.add_argument("setl_output")
     parser.add_argument('-o', "--output")
-    parser.add_argument('-f', "--format",default='csv', choices=['csv','excel'])
+    parser.add_argument('-f', "--format",default='csv', choices=['csv','excel','xml'])
     parser.add_argument('-d', "--delimiter", default=',')
     parser.add_argument('-s', '--sheetname')
     parser.add_argument("--dataset_uri")
 
     args = parser.parse_args()
     output = sdd2setl(args.semantic_data_dictionary,
                       args.prefix,
```

### Comparing `sdd2rdf-1.0.4/sdd2rdf/templates/sdd_setl_template.jinja` & `sdd2rdf-1.1.0/sdd2rdf/templates/sdd_setl_template.jinja`

 * *Files 10% similar despite different names*

```diff
@@ -16,14 +16,16 @@
 @prefix bibo:          <http://purl.org/ontology/bibo/>.
 
 @prefix :              <{{prefix}}> .
 
 :data a {{data_type}}, setl:Table;
   {% if delimiter %} csvw:delimiter "{{delimiter}}";{% endif %}
   {% if sheetname %} csvw:sheetname "{{sheetname}}";{% endif %}
+  {% if data_type == 'setl:XML' and sdd.infosheet.get('selector') -%}
+  setl:xpath '''{{ sdd.infosheet.get('selector') }}''';{% endif %}
   prov:wasGeneratedBy [
     a setl:Extract;
     prov:used <{{data}}>;
   ].
 
 :codebook a owl:Class, prov:SoftwareAgent, setl:PythonScript;
     rdfs:subClassOf prov:Activity;
@@ -33,183 +35,179 @@
 
 :resource_codebook a owl:Class, prov:SoftwareAgent, setl:PythonScript;
     rdfs:subClassOf prov:Activity;
     prov:value '''
 result = {{str(sdd.resource_codebook)}}
 '''.
 
+:nested_enumerate a owl:Class, prov:SoftwareAgent, setl:PythonScript;
+      rdfs:subClassOf prov:Activity;
+      prov:value '''
+def result(iter, name):
+    for i, x in enumerate(iter):
+        print(name, x, i, "%s_%s"% (name, i))
+        yield "%s_%s"% (name, i), x
+'''.
 
 :setl a setl:SemanticETLScript;
   rdfs:label "Semantic Data Dictionary-generated SETL Script".
 
 <{{dataset}}> a void:Dataset;
   prov:wasGeneratedBy :setl, [
     a setl:Transform, setl:JSLDT;
     prov:used :data;
+    prov:qualifiedUsage [ a prov:Use; prov:entity :nested_enumerate; prov:hadRole [ dcterms:identifier "nested_enumerate"]];
     prov:qualifiedUsage [ a prov:Use; prov:entity :codebook; prov:hadRole [ dcterms:identifier "codebook"]];
     prov:qualifiedUsage [ a prov:Use; prov:entity :resource_codebook; prov:hadRole [ dcterms:identifier "resource_codebook"]];
     setl:hasContext '''
     {{ sdd.context | tojson }}
     ''';
-    prov:value '''[{
-{#    "@id" : "nanopub/{% raw %}{{name}}{% endraw %}",
-    "@graph" : {
-        "@id" : "nanopub/{% raw %}{{name}}{% endraw %}",
-        "@type" : "np:Nanopublication",
-        "np:hasAssertion" : {
-            "@type" : "np:Assertion",
-            "@id" : "nanopub/{% raw %}{{name}}{% endraw %}_assertion",#}
-            "@graph" : [
-                {%for column in sdd.columns.values() %}
-                {%- if ('Attribute' in column and not isempty(column['Attribute'])) or
-                       ('Entity' in column and not isempty(column['Entity'])) %} {
-                    {%for predicate_column in sdd.columns.values() %}
-                    {%- if 'Subject' in predicate_column and predicate_column['Subject'] == column['Column'] %}
-                    "{{predicate_column['Predicate']}}" : [{
-                        {%- if 'Format' in predicate_column and not isempty(predicate_column['Format']) %}
-                        "@type" : "{{predicate_column.get('@type')}}",
-                        {%- endif %}
-                        "@if" : "not isempty(row.get('{{predicate_column['Column']}}'))",
-                        "@value" : "{{predicate_column['@value']}}"
-                    }],
-                    {% endif -%}
-                    {% endfor %}
-                    "attributeOf" : [
-                        {%- for attr in column['attributeOf'] %}
-                        { "@id" : "{{sdd.columns[attr]['uri_template']}}" }
-                        {%- if not loop.last %},{% endif %}
-                        {%- endfor %}
-                    ],
-                    {%- if 'Unit' in column and not isempty(column['Unit']) %}
-                    "Unit" : { "@id" : "{{column['Unit']}}" },
-                    {%- endif %}
-                    {%- if 'Time' in column and not isempty(column['Time']) %}
-                    "Time" : { "@id" : "{{sdd.columns[column['Time']]['uri_template']}}" },
-                    {%- endif %}
-                    {%- if 'wasDerivedFrom' in column and not isempty(column['wasDerivedFrom']) %}
-                    "wasDerivedFrom" : [
-                        {% for entity in column['wasDerivedFrom'] -%}
-                        { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
-                        {%- if not loop.last %},{% endif %}
-                        {%- endfor %}
-                    ],
-                    {%- endif %}
-                    {%- if 'wasGeneratedBy' in column and not isempty(column['wasGeneratedBy']) %}
-                    "wasGeneratedBy" : [
-                        {% for entity in column['wasGeneratedBy'] -%}
-                            { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
-                            {%- if not loop.last %},{% endif %}
-                        {%- endfor %}
-                    ],
-                    {%- endif %}
-                    {%- if 'Role' in column and not isempty(column['Role']) %}
-                    "Role" : {
-                        {% if not isempty(column['inRelationTo']) -%}
-                            "inRelationTo" : [
-                                {% for entity in column['inRelationTo'] -%}
-                                    { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
-                                    {%- if not loop.last %},{% endif %}
-                                {%- endfor %}
-                            ],
-                        {% endif -%}
-                        "@type" : {{column['Role'] | tojson}}
-                    },
-                    {%- elif 'Relation' in column and not isempty(column['Relation']) and not isempty(column['inRelationTo']) -%}
-                    "{{column['Relation']}}" : [
-                        {% for entity in column['inRelationTo'] -%}
-                            { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
-                            {%- if not loop.last %},{% endif %}
-                        {%- endfor %}
-                    ],
-                    {%- else -%}
-                    "inRelationTo" : [
-                        {% for entity in column['inRelationTo'] -%}
-                            { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
-                            {%- if not loop.last %},{% endif %}
-                        {%- endfor %}
-                    ],
-                    {%- endif %}
-                    {%- if not column['Column'].startswith("??") %}
-                    "rdf:type" : [
-                        {
-                            "@for" : "class in codebook.get(('{{column['Column']}}', row['{{column['Column']}}']), [])",
-                            {% raw %}"@do" : { "@id" : "{{class}}"}{% endraw %}
-                        }
-                    ],
-                    "Value" : [{
-                        {%- if 'Format' in column and not isempty(column['Format']) %}
-                        "@type" : "{{column.get('@type')}}",
-                        {%- endif %}
-                        "@if" : "not isempty(row.get('{{column['Column']}}'))",
-                        "@value" : "{{column['@value']}}"
-                    }],
-                    {%- endif %}
-                    {%- if 'Start' in column and not isempty(column['Start']) and 'End' in column and not isempty(column['End']) %}
-                    {%- if column['End'] == column['Start'] %}
-                    "Value" : {
-                        "@type" : "xsd:decimal",
-                        "@value" : "{{column['Start']}}"
-                    },
-                    {%- else -%}
-                    "hasStart" : {
-                        "@type" : "TimeInterval",
-                        "Value" : {
-                            "@type" : "xsd:decimal",
-                            "@value" : "{{column['Start']}}"
-                        }
-                    },
-                    "hasEnd" : {
-                        "@type" : "TimeInterval",
-                        "Value" : {
-                            "@type" : "xsd:decimal",
-                            "@value" : "{{column['End']}}"
-                        }
-                    },
-                    {%- endif %}
-                    {%- endif %}
-                    {%- if 'Attribute' in column and not isempty(column['Attribute']) %}
-                    "Attribute" : {{column['Attribute'] | tojson }},
-                    {%- endif %}
-                    {%- if 'Entity' in column and not isempty(column['Entity']) %}
-                    "Entity" : {{column['Entity'] | tojson }},
-                    {%- endif %}
-                    {%- if 'Type' in column and not isempty(column['Type']) %}
-                    "Entity" : {{column['Type'] | tojson }},
-                    {%- endif %}
-                    {%- if column['Column'] in sdd.resource_codebook %}
-                    "@id" : "{% raw %}{{{%endraw%} resource_codebook['{{column['Column']}}'][row['{{column['Column']}}']] {%raw%}}}{% endraw %}"
-                    {%- else -%}
-                    "@id" : "{{column['uri_template']}}"
-                    {%- endif %}
-                }{#}{% if not loop.last %} ,{% endif %} #},{% endif %}{% endfor %}{}
-            ]
-{#        },
-        "np:hasProvenance" : {
-            "@type" : "np:Provenance",
-            "@id" : "nanopub/{% raw %}{{name}}{% endraw %}_provenance",
-            "@graph" : [
-            ]
-        },
-        "np:hasPublicationInfo" : {
-            "@type" : "np:PublicationInfo",
-            "@id" : "nanopub/{% raw %}{{name}}{% endraw %}_pubinfo",
-            "@graph" : [
+    prov:value '''[
+              {% for branch_column in sdd.root_columns recursive   %}
                 {
-                    "@id" : "nanopub/{% raw %}{{name}}{% endraw %}",
-                    "void:inDataset" : {"@id" : "{{dataset}}"},
-                    "prov:wasDerivedFrom" : {
-                        "@type" : "csvw:Row",
-                        "@reverse" : {"csvw:row" : {"@id" : "{{data}}"} },
-                        {% raw %}"csvw:rownum" : { "@value" : "{{name}}", "@type" : "xsd:integer"}{% endraw %}
+                  "@for" : "{{branch_column['Column']}}_name, {{branch_column['Column']}} in enumerate({{branch_column['iterator']}})",
+                  "@do" : [
+                    {
+                      "@with": {{branch_column['with'] | tojson}},
+                      "@do" : [
+                        {% for column in branch_column['leaves']  %}
+                          {%- if ('Attribute' in column and not isempty(column['Attribute'])) or
+                                 ('Entity' in column and not isempty(column['Entity'])) %} {
+                              {%for predicate_column in sdd.columns.values() %}
+                              {%- if 'Subject' in predicate_column and predicate_column['Subject'] == column['Column'] %}
+                              "{{predicate_column['Predicate']}}" : [{
+                                  {%- if 'Format' in predicate_column and not isempty(predicate_column['Format']) %}
+                                  "@type" : "{{predicate_column.get('@type')}}",
+                                  {%- endif %}
+                                  "@if" : "not isempty(row.get('{{predicate_column['Column']}}'))",
+                                  "@value" : "{{predicate_column['@value']}}"
+                              }],
+                              {% endif -%}
+                              {% endfor %}
+                              "attributeOf" : [
+                                  {%- for attr in column['attributeOf'] %}
+                                  { "@id" : "{{sdd.columns[attr]['uri_template']}}" }
+                                  {%- if not loop.last %},{% endif %}
+                                  {%- endfor %}
+                              ],
+                              {% if 'Unit' in column and not isempty(column['Unit']) -%}
+                                {%- if column['Unit'] in sdd.columns -%}
+                                "Unit" : { "@id" : "{{sdd.columns[column['Unit']]['uri_template']}}" },
+                                {%- else -%}
+                                "Unit" : { "@id" : "{{column['Unit']}}" },
+                                {%- endif -%}
+                              {% endif %}
+                              {%- if 'Time' in column and not isempty(column['Time']) %}
+                              "Time" : { "@id" : "{{sdd.columns[column['Time']]['uri_template']}}" },
+                              {%- endif %}
+                              {%- if 'wasDerivedFrom' in column and not isempty(column['wasDerivedFrom']) %}
+                              "wasDerivedFrom" : [
+                                  {% for entity in column['wasDerivedFrom'] -%}
+                                  { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
+                                  {%- if not loop.last %},{% endif %}
+                                  {%- endfor %}
+                              ],
+                              {%- endif %}
+                              {%- if 'wasGeneratedBy' in column and not isempty(column['wasGeneratedBy']) %}
+                              "wasGeneratedBy" : [
+                                  {% for entity in column['wasGeneratedBy'] -%}
+                                      { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
+                                      {%- if not loop.last %},{% endif %}
+                                  {%- endfor %}
+                              ],
+                              {%- endif %}
+                              {%- if 'Role' in column and not isempty(column['Role']) %}
+                              "Role" : {
+                                  {% if not isempty(column['inRelationTo']) -%}
+                                      "inRelationTo" : [
+                                          {% for entity in column['inRelationTo'] -%}
+                                              { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
+                                              {%- if not loop.last %},{% endif %}
+                                          {%- endfor %}
+                                      ],
+                                  {% endif -%}
+                                  "@type" : {{column['Role'] | tojson}}
+                              },
+                              {%- elif 'Relation' in column and not isempty(column['Relation']) and not isempty(column['inRelationTo']) -%}
+                              "{{column['Relation']}}" : [
+                                  {% for entity in column['inRelationTo'] -%}
+                                      { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
+                                      {%- if not loop.last %},{% endif %}
+                                  {%- endfor %}
+                              ],
+                              {% else -%}
+                              "inRelationTo" : [
+                                  {% for entity in column['inRelationTo'] -%}
+                                      { "@id" : "{{sdd.columns[entity]['uri_template']}}" }
+                                      {%- if not loop.last %},{% endif %}
+                                  {%- endfor %}
+                              ],
+                              {%- endif %}
+                              {%- if not column['Column'].startswith("??") %}
+                              "a" : [
+                                  {
+                                      "@for" : "class in codebook.get(('{{column['Column']}}', {{column['value_access']}}), [])",
+                                      {% raw %}"@do" : { "@id" : "{{class}}"}{% endraw %}
+                                  }
+                              ],
+                              "Value" : [{
+                                  {%- if 'Format' in column and not isempty(column['Format']) %}
+                                  "@type" : "{{column.get('@type')}}",
+                                  {%- endif %}
+                                  "@if" : "not isempty({{column['value_access']}})",
+                                  "@value" : "{{column['@value']}}"
+                              }],
+                              {%- endif %}
+                              {%- if 'Start' in column and not isempty(column['Start']) and 'End' in column and not isempty(column['End']) %}
+                              {%- if column['End'] == column['Start'] %}
+                              "Value" : {
+                                  "@type" : "xsd:decimal",
+                                  "@value" : "{{column['Start']}}"
+                              },
+                              {%- else -%}
+                              "hasStart" : {
+                                  "@type" : "TimeInterval",
+                                  "Value" : {
+                                      "@type" : "xsd:decimal",
+                                      "@value" : "{{column['Start']}}"
+                                  }
+                              },
+                              "hasEnd" : {
+                                  "@type" : "TimeInterval",
+                                  "Value" : {
+                                      "@type" : "xsd:decimal",
+                                      "@value" : "{{column['End']}}"
+                                  }
+                              },
+                              {%- endif %}
+                              {%- endif %}
+                              {%- if 'Attribute' in column and not isempty(column['Attribute']) %}
+                              "Attribute" : {{column['Attribute'] | tojson }},
+                              {%- endif %}
+                              {%- if 'Entity' in column and not isempty(column['Entity']) %}
+                              "Entity" : {{column['Entity'] | tojson }},
+                              {%- endif %}
+                              {%- if 'Type' in column and not isempty(column['Type']) %}
+                              "Entity" : {{column['Type'] | tojson }},
+                              {%- endif %}
+                              "@id" : "{{column['uri_template']}}"
+                          },
+                          {% else %}{},
+                          {% endif %}
+                        {% endfor %}
+                        {% set parent = branch_column %}
+                        {{ loop (branch_column['branches']) }}
+                          {}
+                      ]
                     }
-                }
-            ]
-        }
-    } #}
-}]'''].
+                  ]
+                },
+              {% endfor %}
+                {}
+]'''].
 
 {% if data_out %}
 <{{data_out}}> a pv:File;
     dcterms:format "application/trig";
     prov:wasGeneratedBy [
       a setl:Load;
       prov:used <{{dataset}}> ;
```

### Comparing `sdd2rdf-1.0.4/setup.py` & `sdd2rdf-1.1.0/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -6,15 +6,15 @@
 # README file and 2) it's easier to type in the README file than to put a raw
 # string in below ...
 def read(fname):
     return open(os.path.join(os.path.dirname(__file__), fname)).read()
 
 setup(
     name = "sdd2rdf",
-    version = "1.0.4",
+    version = "1.1.0",
     author = "Jamie McCusker",
     author_email = "mccusj@cs.rpi.edu",
     description = ("sdd2rdf generates RDF graphs from semantically annotated data."),
     license = "Apache License 2.0",
     keywords = "rdf semantic etl",
     url = "http://packages.python.org/sdd2rdf",
     packages=['sdd2rdf'],
```


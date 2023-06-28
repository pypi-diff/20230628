# Comparing `tmp/dsp_tools-2.3.3.tar.gz` & `tmp/dsp_tools-2.3.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dsp_tools-2.3.3.tar", max compression
+gzip compressed data, was "dsp_tools-2.3.4.tar", max compression
```

## Comparing `dsp_tools-2.3.3.tar` & `dsp_tools-2.3.4.tar`

### file list

```diff
@@ -1,63 +1,63 @@
--rw-r--r--   0        0        0    35149 2023-06-14 06:25:24.712451 dsp_tools-2.3.3/LICENSE
--rw-r--r--   0        0        0     4373 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/docs/index.md
--rw-r--r--   0        0        0     4850 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/pyproject.toml
--rw-r--r--   0        0        0        0 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/__init__.py
--rw-r--r--   0        0        0    20433 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/dsp_tools.py
--rw-r--r--   0        0        0    89229 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/excel2xml.py
--rw-r--r--   0        0        0        0 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/fast_xmlupload/__init__.py
--rw-r--r--   0        0        0    31627 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/fast_xmlupload/process_files.py
--rw-r--r--   0        0        0    14293 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/fast_xmlupload/upload_files.py
--rw-r--r--   0        0        0     4185 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/fast_xmlupload/upload_xml.py
--rw-r--r--   0        0        0        0 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/models/__init__.py
--rw-r--r--   0        0        0      929 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/models/bitstream.py
--rw-r--r--   0        0        0     9662 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/models/connection.py
--rw-r--r--   0        0        0     3325 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/models/exceptions.py
--rw-r--r--   0        0        0     9470 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/models/group.py
--rw-r--r--   0        0        0    16545 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/models/helpers.py
--rw-r--r--   0        0        0     9798 2023-06-14 06:25:24.728452 dsp_tools-2.3.3/src/dsp_tools/models/langstring.py
--rw-r--r--   0        0        0    22159 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/listnode.py
--rw-r--r--   0        0        0      506 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/model.py
--rw-r--r--   0        0        0    17509 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/ontology.py
--rw-r--r--   0        0        0     2956 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/permission.py
--rw-r--r--   0        0        0    18974 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/project.py
--rw-r--r--   0        0        0     1914 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/projectContext.py
--rw-r--r--   0        0        0    21045 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/propertyclass.py
--rw-r--r--   0        0        0     1897 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/propertyelement.py
--rw-r--r--   0        0        0    21692 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/resource.py
--rw-r--r--   0        0        0    34024 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/resourceclass.py
--rw-r--r--   0        0        0      419 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/set_encoder.py
--rw-r--r--   0        0        0      919 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/sipi.py
--rw-r--r--   0        0        0    27078 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/user.py
--rw-r--r--   0        0        0    33467 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/value.py
--rw-r--r--   0        0        0     2151 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/xmlallow.py
--rw-r--r--   0        0        0      747 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/xmlbitstream.py
--rw-r--r--   0        0        0     1841 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/xmlpermission.py
--rw-r--r--   0        0        0     2373 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/xmlproperty.py
--rw-r--r--   0        0        0     8943 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/xmlresource.py
--rw-r--r--   0        0        0     2613 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/models/xmlvalue.py
--rw-r--r--   0        0        0        0 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/py.typed
--rw-r--r--   0        0        0     1488 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/resources/0100-template-repo/template.json
--rw-r--r--   0        0        0     1036 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/resources/0100-template-repo/template.xml
--rw-r--r--   0        0        0    23543 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/resources/schema/data.xsd
--rw-r--r--   0        0        0     2770 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/resources/schema/lists-only.json
--rw-r--r--   0        0        0    42584 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/resources/schema/project.json
--rw-r--r--   0        0        0    32171 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/resources/schema/properties-only.json
--rw-r--r--   0        0        0     4341 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/resources/schema/resources-only.json
--rw-r--r--   0        0        0     2526 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/resources/start-stack/docker-compose.yml
--rw-r--r--   0        0        0        0 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/__init__.py
--rw-r--r--   0        0        0    15315 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/excel_to_json_lists.py
--rw-r--r--   0        0        0     4886 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/excel_to_json_project.py
--rw-r--r--   0        0        0     8237 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/excel_to_json_properties.py
--rw-r--r--   0        0        0    10530 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/excel_to_json_resources.py
--rw-r--r--   0        0        0     1170 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/generate_templates.py
--rw-r--r--   0        0        0     3189 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/id_to_iri.py
--rw-r--r--   0        0        0     1134 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/logging.py
--rw-r--r--   0        0        0    41163 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/project_create.py
--rw-r--r--   0        0        0     8371 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/project_create_lists.py
--rw-r--r--   0        0        0     4689 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/project_get.py
--rw-r--r--   0        0        0    18807 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/project_validate.py
--rw-r--r--   0        0        0     4259 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/rosetta.py
--rw-r--r--   0        0        0    12793 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/shared.py
--rw-r--r--   0        0        0     6988 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/stack_handling.py
--rw-r--r--   0        0        0    51652 2023-06-14 06:25:24.732452 dsp_tools-2.3.3/src/dsp_tools/utils/xml_upload.py
--rw-r--r--   0        0        0     5676 1970-01-01 00:00:00.000000 dsp_tools-2.3.3/PKG-INFO
+-rw-r--r--   0        0        0    35149 2023-06-28 06:11:19.583652 dsp_tools-2.3.4/LICENSE
+-rw-r--r--   0        0        0     4373 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/docs/index.md
+-rw-r--r--   0        0        0     4845 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/pyproject.toml
+-rw-r--r--   0        0        0        0 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/__init__.py
+-rw-r--r--   0        0        0    20433 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/dsp_tools.py
+-rw-r--r--   0        0        0    89229 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/excel2xml.py
+-rw-r--r--   0        0        0        0 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/fast_xmlupload/__init__.py
+-rw-r--r--   0        0        0    31627 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/fast_xmlupload/process_files.py
+-rw-r--r--   0        0        0    14293 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/fast_xmlupload/upload_files.py
+-rw-r--r--   0        0        0     4185 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/fast_xmlupload/upload_xml.py
+-rw-r--r--   0        0        0        0 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/__init__.py
+-rw-r--r--   0        0        0      929 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/bitstream.py
+-rw-r--r--   0        0        0     8271 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/connection.py
+-rw-r--r--   0        0        0     3325 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/exceptions.py
+-rw-r--r--   0        0        0     8757 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/group.py
+-rw-r--r--   0        0        0    16339 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/helpers.py
+-rw-r--r--   0        0        0     8853 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/langstring.py
+-rw-r--r--   0        0        0    20424 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/listnode.py
+-rw-r--r--   0        0        0      381 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/model.py
+-rw-r--r--   0        0        0    14778 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/ontology.py
+-rw-r--r--   0        0        0     2280 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/permission.py
+-rw-r--r--   0        0        0    16628 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/project.py
+-rw-r--r--   0        0        0     1744 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/projectContext.py
+-rw-r--r--   0        0        0    18683 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/propertyclass.py
+-rw-r--r--   0        0        0     1930 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/propertyelement.py
+-rw-r--r--   0        0        0    20694 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/resource.py
+-rw-r--r--   0        0        0    29981 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/resourceclass.py
+-rw-r--r--   0        0        0      401 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/set_encoder.py
+-rw-r--r--   0        0        0      998 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/sipi.py
+-rw-r--r--   0        0        0    25540 2023-06-28 06:11:19.603652 dsp_tools-2.3.4/src/dsp_tools/models/user.py
+-rw-r--r--   0        0        0    33279 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/models/value.py
+-rw-r--r--   0        0        0     1971 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/models/xmlallow.py
+-rw-r--r--   0        0        0      594 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/models/xmlbitstream.py
+-rw-r--r--   0        0        0     1504 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/models/xmlpermission.py
+-rw-r--r--   0        0        0     2172 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/models/xmlproperty.py
+-rw-r--r--   0        0        0     8619 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/models/xmlresource.py
+-rw-r--r--   0        0        0     2141 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/models/xmlvalue.py
+-rw-r--r--   0        0        0        0 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/py.typed
+-rw-r--r--   0        0        0     1488 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/resources/0100-template-repo/template.json
+-rw-r--r--   0        0        0     1036 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/resources/0100-template-repo/template.xml
+-rw-r--r--   0        0        0    23544 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/resources/schema/data.xsd
+-rw-r--r--   0        0        0     2770 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/resources/schema/lists-only.json
+-rw-r--r--   0        0        0    42584 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/resources/schema/project.json
+-rw-r--r--   0        0        0    32171 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/resources/schema/properties-only.json
+-rw-r--r--   0        0        0     4341 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/resources/schema/resources-only.json
+-rw-r--r--   0        0        0     2526 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/resources/start-stack/docker-compose.yml
+-rw-r--r--   0        0        0        0 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/__init__.py
+-rw-r--r--   0        0        0    15315 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/excel_to_json_lists.py
+-rw-r--r--   0        0        0     4886 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/excel_to_json_project.py
+-rw-r--r--   0        0        0     8237 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/excel_to_json_properties.py
+-rw-r--r--   0        0        0    10530 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/excel_to_json_resources.py
+-rw-r--r--   0        0        0     1170 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/generate_templates.py
+-rw-r--r--   0        0        0     3189 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/id_to_iri.py
+-rw-r--r--   0        0        0     1134 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/logging.py
+-rw-r--r--   0        0        0    42405 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/project_create.py
+-rw-r--r--   0        0        0     8373 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/project_create_lists.py
+-rw-r--r--   0        0        0     4694 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/project_get.py
+-rw-r--r--   0        0        0    18807 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/project_validate.py
+-rw-r--r--   0        0        0     4259 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/rosetta.py
+-rw-r--r--   0        0        0    13302 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/shared.py
+-rw-r--r--   0        0        0     6988 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/stack_handling.py
+-rw-r--r--   0        0        0    51523 2023-06-28 06:11:19.607652 dsp_tools-2.3.4/src/dsp_tools/utils/xml_upload.py
+-rw-r--r--   0        0        0     5676 1970-01-01 00:00:00.000000 dsp_tools-2.3.4/PKG-INFO
```

### Comparing `dsp_tools-2.3.3/LICENSE` & `dsp_tools-2.3.4/LICENSE`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/docs/index.md` & `dsp_tools-2.3.4/docs/index.md`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/pyproject.toml` & `dsp_tools-2.3.4/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 # See https://packaging.python.org/en/latest/specifications/declaring-project-metadata
 
 [tool.poetry]
 name = "dsp-tools"
-version = "2.3.3"
+version = "2.3.4"
 description = "DSP-TOOLS is a Python package with a command line interface that helps you interact with a DaSCH service platform (DSP) server."
 authors = ["DaSCH - Swiss National Data and Service Center for the Humanities <info@dasch.swiss>"]
 readme = "docs/index.md"
 license = "GPL-3.0-only"
 classifiers = [
     "Programming Language :: Python :: 3",
     "License :: OSI Approved :: GNU General Public License v3 (GPLv3)",
@@ -36,15 +36,15 @@
 docker = "^6.1.2"
 
 
 [tool.poetry.group.dev.dependencies]
 black = "^23.3.0"
 mkdocs = "^1.4.3"
 mkdocs-material = "^9.1.11"
-mkdocs-include-markdown-plugin = "^4.0.4"
+mkdocs-include-markdown-plugin = "*"
 mypy = "^1.3.0"
 pylint = "^2.17.4"
 pytest = "^7.3.1"
 types-requests = "^2.30.0.0"
 types-lxml = "^2023.3.28"
 types-jsonschema = "^4.17.0.8"
 types-openpyxl = "^3.1.0.7"
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/dsp_tools.py` & `dsp_tools-2.3.4/src/dsp_tools/dsp_tools.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/excel2xml.py` & `dsp_tools-2.3.4/src/dsp_tools/excel2xml.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/fast_xmlupload/process_files.py` & `dsp_tools-2.3.4/src/dsp_tools/fast_xmlupload/process_files.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/fast_xmlupload/upload_files.py` & `dsp_tools-2.3.4/src/dsp_tools/fast_xmlupload/upload_files.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/fast_xmlupload/upload_xml.py` & `dsp_tools-2.3.4/src/dsp_tools/fast_xmlupload/upload_xml.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/bitstream.py` & `dsp_tools-2.3.4/src/dsp_tools/models/bitstream.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/connection.py` & `dsp_tools-2.3.4/src/dsp_tools/models/connection.py`

 * *Files 9% similar despite different names*

```diff
@@ -162,15 +162,15 @@
                 "return-headers": dict(response.headers),
                 "return": response.json()
                 if response.status_code == 200
                 else {"status": str(response.status_code), "message": response.text},
             }
             tmp = path.split("/")
             filename = "POST" + "_".join(tmp) + ".json"
-            with open(filename, "w", encoding="utf8") as f:
+            with open(filename, "w", encoding="utf-8") as f:
                 json.dump(logobj, f, indent=4)
         check_for_api_error(response)
         result = response.json()
         return result
 
     def get(self, path: str, headers: Optional[dict[str, str]] = None) -> dict[str, Any]:
         """
@@ -252,32 +252,7 @@
                 self._server + path,
                 headers={"Authorization": "Bearer " + self._token},
                 timeout=5,
             )
         check_for_api_error(response)
         result = response.json()
         return result
-
-    def reset_triplestore_content(self):
-        rdfdata = [
-            {"path": "./knora-ontologies/knora-admin.ttl", "name": "http://www.knora.org/ontology/knora-admin"},
-            {"path": "./knora-ontologies/knora-base.ttl", "name": "http://www.knora.org/ontology/knora-base"},
-            {"path": "./knora-ontologies/standoff-onto.ttl", "name": "http://www.knora.org/ontology/standoff"},
-            {"path": "./knora-ontologies/standoff-data.ttl", "name": "http://www.knora.org/data/standoff"},
-            {"path": "./knora-ontologies/salsah-gui.ttl", "name": "http://www.knora.org/ontology/salsah-gui"},
-            {"path": "./_test_data/all_data/admin-data.ttl", "name": "http://www.knora.org/data/admin"},
-            {"path": "./_test_data/all_data/permissions-data.ttl", "name": "http://www.knora.org/data/permissions"},
-            {"path": "./_test_data/all_data/system-data.ttl", "name": "http://www.knora.org/data/0000/SystemProject"},
-        ]
-        jsondata = json.dumps(rdfdata)
-        url = self._server + "/admin/store/ResetTriplestoreContent?prependdefaults=false"
-
-        response = requests.post(
-            url,
-            headers={"Content-Type": "application/json; charset=UTF-8"},
-            data=jsondata,
-            timeout=5,
-        )
-        check_for_api_error(response)
-        res = response.json()
-        #  pprint(res)
-        return res
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/exceptions.py` & `dsp_tools-2.3.4/src/dsp_tools/models/exceptions.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/group.py` & `dsp_tools-2.3.4/src/dsp_tools/models/group.py`

 * *Files 8% similar despite different names*

```diff
@@ -90,15 +90,15 @@
         status: Optional[bool] = None,
     ) -> None:
         super().__init__(con)
         self._iri = iri
         self._name = str(name) if name is not None else None
         self._descriptions = LangString(descriptions)
         if project is not None and isinstance(project, Project):
-            self._project = project.id
+            self._project = project.iri
         else:
             self._project = str(project) if project is not None else None
         self._selfjoin = bool(selfjoin) if selfjoin is not None else None
         self._status = bool(status) if status is not None else None
 
     @property
     def iri(self) -> Optional[str]:
@@ -148,20 +148,14 @@
         return self._status
 
     @status.setter
     def status(self, value: bool) -> None:
         self._status = value
         self._changed.add("status")
 
-    def has_changed(self) -> bool:
-        if self._changed:
-            return True
-        else:
-            return False
-
     @classmethod
     def fromJsonObj(cls, con: Connection, json_obj: Any):
         group_id = json_obj.get("id")
         if group_id is None:
             raise BaseError('Group "id" is missing')
         name = json_obj.get("name")
         if name is None:
@@ -255,21 +249,7 @@
         group = {
             "name": self.name,
             "descriptions": self.descriptions.createDefinitionFileObj(),
             "selfjoin": self.selfjoin,
             "status": self.status,
         }
         return group
-
-    def print(self) -> None:
-        print("Group Info:")
-        print("  IRI:         {}".format(self._iri))
-        print("  Name:        {}".format(self._name))
-        if self._descriptions is not None:
-            print("  Descriptions:")
-            for descr in self._descriptions.items():
-                print("    {}: {}".format(descr[0], descr[1]))
-        else:
-            print("  Descriptions: None")
-        print("  Project:     {}".format(self._project))
-        print("  Selfjoin:    {}".format(self._selfjoin))
-        print("  Status:      {}".format(self._status))
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/helpers.py` & `dsp_tools-2.3.4/src/dsp_tools/models/helpers.py`

 * *Files 4% similar despite different names*

```diff
@@ -185,18 +185,14 @@
         :return: None
         """
         if value is not None and isinstance(value, ContextType):
             self._context = value
         else:
             raise BaseError("Error in parameter to context setter")
 
-    @property
-    def rcontext(self) -> dict[str, str]:
-        return self._rcontext
-
     def add_context(self, prefix: str, iri: Optional[str] = None) -> None:
         """
         Add a new context to a context instance
 
         :param prefix: The prefix that should be used
         :param iri: The IRI that belongs to this context prefix
         :return: None
@@ -373,18 +369,14 @@
         """
         return {prefix: oinfo.iri + "#" if oinfo.hashtag else oinfo.iri for prefix, oinfo in self._context.items()}
 
     def get_externals_used(self) -> dict[str, str]:
         exclude = ["rdf", "rdfs", "owl", "xsd", "knora-api", "salsah-gui"]
         return {prefix: onto.iri for prefix, onto in self._context.items() if prefix not in exclude}
 
-    def print(self) -> None:
-        for a in self._context.items():
-            print(a[0] + ': "' + a[1].iri + '"')
-
 
 class DateTimeStamp:
     """
     Class to hold and process an xsd:dateTimeStamp
     """
 
     _dateTimeStamp: str
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/langstring.py` & `dsp_tools-2.3.4/src/dsp_tools/models/langstring.py`

 * *Files 1% similar despite different names*

```diff
@@ -160,26 +160,14 @@
         if equal:
             for lang in Languages:
                 equal = self._langstrs.get(lang) == other._langstrs.get(lang)
                 if not equal:
                     break
         return equal
 
-    def get_by_lang(self, key: Optional[Union[Languages, str]] = None) -> Optional[str]:
-        if key is None:
-            return self._simplestring
-        else:
-            if isinstance(key, Enum):
-                return self._langstrs.get(key)
-            else:
-                lmap = dict(map(lambda a: (a.value, a), Languages))
-                if lmap.get(key.lower()) is None:
-                    raise BaseError('Invalid language string "' + key + '"!')
-                return self._langstrs.get(lmap[key.lower()])
-
     def items(self):
         return self._langstrs.items()
 
     def isEmpty(self) -> bool:
         return not (bool(self._langstrs) or bool(self._simplestring))
 
     def empty(self) -> None:
@@ -255,27 +243,14 @@
             elif lang == "rm":
                 lstrs[Languages.RM] = o.get("value")
             else:
                 if o.get("value") is not None:
                     return cls(o.get("value"))
         return cls(lstrs)
 
-    def print(self, offset: Optional[int] = None):
-        blank = " "
-        # print(f'{blank:>{offset}}LangString:')
-        if self._simplestring is not None:
-            print(f"{blank:>{offset + 2}}{self._simplestring}")
-        else:
-            for p in self._langstrs.items():
-                print(f"{blank:>{offset + 2}}{p[0]} : {p[1]}")
-
-    @property
-    def langstrs(self):
-        return self._langstrs
-
     def createDefinitionFileObj(self) -> Union[str, dict[str, str]]:
         if self._simplestring:
             return self._simplestring
         langstring = {}
         for p in self.items():
             langstring[p[0].value] = p[1]
         return langstring
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/listnode.py` & `dsp_tools-2.3.4/src/dsp_tools/models/listnode.py`

 * *Files 8% similar despite different names*

```diff
@@ -177,15 +177,15 @@
             isRootNode: Is True if the ListNode is a root node of a list Cannot be set [read].
             children: list of children nodes. Only available for nodes that have been read by getAllNodes()
             rootNodeIri: IRI of the root node. Only available for nodes that have been read by the method getAllNodes()
         """
 
         super().__init__(con)
 
-        self._project = project.id if isinstance(project, Project) else str(project) if project else None
+        self._project = project.iri if isinstance(project, Project) else str(project) if project else None
         self._id = iri
         self._label = LangString(label)
         self._comments = LangString(comments) if comments else None
         self._name = name
         if parent and isinstance(parent, ListNode):
             self._parent = parent.iri
         else:
@@ -352,20 +352,14 @@
     def rootNodeIri(self) -> Optional[str]:
         return self._rootNodeIri
 
     @rootNodeIri.setter
     def rootNodeIri(self, value: str):
         raise BaseError("rootNodeIri cannot be set!")
 
-    def has_changed(self) -> bool:
-        if self._changed:
-            return True
-        else:
-            return False
-
     @classmethod
     def fromJsonObj(cls, con: Connection, json_obj: Any) -> Any:
         """
         Internal method! Should not be used directly!
 
         This method is used to create a ListNode instance from the JSON data returned by DSP
 
@@ -559,65 +553,21 @@
             if not listnode.comments.isEmpty():
                 listnodeobj["comments"] = listnode.comments.createDefinitionFileObj()
             if listnode.children:
                 listnodeobj["nodes"] = self._createDefinitionFileObj(listnode.children)
             listnodeobjs.append(listnodeobj)
         return listnodeobjs
 
-    @staticmethod
-    def readDefinitionFileObj(con: Connection, project: Project, rootnode: Any) -> "ListNode":
-        """
-        Reads a JSON obj that corresponds to the syntax of the input to "create_onto".
-
-        :param self:
-        :param con: Connection object
-        :param project: Project instance
-        :param rootnode: root node of the list
-        :return: an instance of ListNode corresponding to the root node
-        """
-        root_list_node = ListNode(
-            con=con, project=project, label=rootnode["labels"], comments=rootnode.get("comments"), name=rootnode["name"]
-        )
-        listnodes = list_creator(con, project, root_list_node, rootnode.get("nodes"))
-        root_list_node.children = listnodes
-        return root_list_node
-
     def createDefinitionFileObj(self) -> dict[str, Any]:
         """
         Create an object that corresponds to the syntax of the input to "create_onto".
         :return: A python object that can be jsonfied to correspond to the syntax of the input to "create_onto".
         """
         listnode = {
             "name": self._name,
             "labels": self._label.createDefinitionFileObj(),
         }
         if not self._comments.isEmpty():
             listnode["comments"] = self._comments.createDefinitionFileObj()
         if self._children:
             listnode["nodes"] = self._createDefinitionFileObj(self._children)
         return listnode
-
-    def print(self):
-        """
-        print info to stdout
-
-        :return: None
-        """
-
-        print("Node Info:")
-        print("  IRI:       {}".format(self._id))
-        print("  Project:   {}".format(self._project))
-        print("  Name:      {}".format(self._name))
-        print("  Label:     ")
-        if self._label:
-            for lbl in self._label.items():
-                print("             {}: {}".format(lbl[0], lbl[1]))
-        else:
-            print("             None")
-        print("  Comments:   ")
-        if self._comments.isEmpty():
-            for lbl in self._comments.items():
-                print("             {}: {}".format(lbl[0], lbl[1]))
-        else:
-            print("             None")
-        print("  Parent", self._parent)
-        print("  IsRootNode: {}".format(self._isRootNode))
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/ontology.py` & `dsp_tools-2.3.4/src/dsp_tools/models/ontology.py`

 * *Files 18% similar despite different names*

```diff
@@ -69,15 +69,15 @@
         resource_classes: Optional[list[ResourceClass]] = None,
         property_classes: Optional[list[PropertyClass]] = None,
         context: Context = None,
     ):
         super().__init__(con)
         self._iri = iri
         if isinstance(project, Project):
-            self._project = project.id
+            self._project = project.iri
         else:
             self._project = project
         self._name = name
         self._label = label
         self._comment = comment
         if lastModificationDate is None:
             self._lastModificationDate = None
@@ -144,63 +144,22 @@
     def resource_classes(self) -> list[ResourceClass]:
         return self._resource_classes
 
     @resource_classes.setter
     def resource_classes(self, value: list[ResourceClass]) -> None:
         self._resource_classes = value
 
-    def addResourceClass(self, resourceclass: ResourceClass, create: bool = False) -> tuple[int, ResourceClass]:
-        if create:
-            print("Calling resourceclass.create in Ontology.addResourceClass")
-            lmd, resourceclass = resourceclass.create(self._lastModificationDate)
-            self._lastModificationDate = lmd
-        self._resource_classes.append(resourceclass)
-        index = len(self._resource_classes) - 1
-        return index, resourceclass
-
-    def updateResourceClass(self, index: int, resourceclass: ResourceClass) -> ResourceClass:
-        lmd, resourceclass = resourceclass.update(self._lastModificationDate)
-        self._lastModificationDate = lmd
-        self._resource_classes[index] = resourceclass
-        return resourceclass
-
-    def removeResourceClass(self, index: int, erase: bool = False) -> None:
-        if erase:
-            lmd = self._resource_classes[index].delete(self._lastModificationDate)
-            self._lastModificationDate = lmd
-        del self._resource_classes[index]
-
     @property
     def property_classes(self) -> list[PropertyClass]:
         return self._property_classes
 
     @property_classes.setter
     def property_classes(self, value: list[PropertyClass]):
         self._property_classes = value
 
-    def addPropertyClass(self, propclass: PropertyClass, create: bool = False) -> tuple[int, ResourceClass]:
-        if create:
-            lmd, resourceclass = propclass.create(self._lastModificationDate)
-            self._lastModificationDate = lmd
-        self._property_classes.append(resourceclass)
-        index = len(self._property_classes) - 1
-        return index, propclass
-
-    def updatePropertyClass(self, index: int, propclass: PropertyClass) -> PropertyClass:
-        lmd, propclass = propclass.update(self._lastModificationDate)
-        self._lastModificationDate = lmd
-        self._property_classes[index] = propclass
-        return propclass
-
-    def removePropertyClass(self, index: int, erase: bool = False) -> None:
-        if erase:
-            lmd = self._property_classes[index].delete(self._lastModificationDate)
-            self._lastModificationDate = lmd
-        del self._property_classes[index]
-
     @property
     def context(self):
         return self._context
 
     @context.setter
     def context(self, value: Context):
         raise BaseError('"Context" cannot be set!')
@@ -413,24 +372,7 @@
                 continue
             ontology["properties"].append(prop.createDefinitionFileObj(self.context, self.name))
 
         for res in self.resource_classes:
             ontology["resources"].append(res.createDefinitionFileObj(self.context, self.name, self._skiplist))
 
         return ontology
-
-    def print(self, short: bool = True) -> None:
-        print("Ontology Info:")
-        print("  IRI:                  {}".format(self._iri))
-        print("  Label:                {}".format(self._label))
-        print("  Name:                 {}".format(self._name))
-        print("  Project:              {}".format(self._project))
-        print("  LastModificationDate: {}".format(str(self._lastModificationDate)))
-        if not short:
-            print("  Property Classes:")
-            if self._property_classes:
-                for pc in self._property_classes:
-                    pc.print(4)
-            print("  Resource Classes:")
-            if self._resource_classes:
-                for rc in self._resource_classes:
-                    rc.print(4)
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/permission.py` & `dsp_tools-2.3.4/src/dsp_tools/models/permission.py`

 * *Files 19% similar despite different names*

```diff
@@ -18,34 +18,14 @@
             4: "M",
             8: "D",
             16: "CR",
         }
         return tmp[self.value]
 
 
-class PermissionsIterator:
-    _permissions: "Permissions"
-    _group: list[str]
-    _index: int
-
-    def __init__(self, permissions: "Permissions"):
-        self._permissions = permissions
-        self._index = 0
-
-    def __next__(self):
-        if len(self._permissions.permissions) == 0 and self._index == 0:
-            return None, None
-        elif self._index < len(self._permissions.permissions):
-            tmp = self._prefixes[self._index]
-            self._index += 1
-            return tmp, self._permissions.permissions[tmp]
-        else:
-            raise StopIteration
-
-
 class Permissions:
     _permissions: Union[dict[PermissionValue, list[str]], None]
 
     def __init__(self, permissions: Optional[dict[PermissionValue, list[str]]] = None):
         if permissions is None:
             self._permissions = {}
         else:
@@ -59,17 +39,14 @@
 
     def __delitem__(self, key: PermissionValue) -> None:
         del self._permissions[key]
 
     def __missing__(self, key: PermissionValue) -> None:
         return None
 
-    def __iter__(self) -> PermissionsIterator:
-        return PermissionsIterator(self)
-
     def __contains__(self, key: PermissionValue) -> bool:
         return key in self._permissions
 
     def __str__(self):
         tmpstr = ""
         for permission, groups in self._permissions.items():
             if tmpstr:
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/project.py` & `dsp_tools-2.3.4/src/dsp_tools/models/project.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,57 +1,56 @@
-from __future__ import annotations
-
-import json
-from pprint import pprint
-from typing import Any, Optional, Union
-from urllib.parse import quote_plus
-
-from dsp_tools.models.connection import Connection
-from dsp_tools.models.exceptions import BaseError
-from dsp_tools.models.helpers import Actions
-from dsp_tools.models.langstring import LangString, Languages
-from dsp_tools.models.model import Model
-from dsp_tools.models.set_encoder import SetEncoder
-
 """
 This module implements the handling (CRUD) of DSP projects.
 
 CREATE:
     * Instantiate a new object of the class Project with all required parameters
     * Call the ``create``-method on the instance
 
 READ:
-    * Instantiate a new object with ``id``(IRI of project) given
+    * Instantiate a new object with ``iri`` given
     * Call the ``read``-method on the instance
     * Access the information that has been provided to the instance
 
 UPDATE:
     * You need an instance of an existing Project by reading an instance
     * Change the attributes by assigning the new values
     * Call the ``update```method on the instance
 
 DELETE
-    * Instantiate a new objects with ``id``(IRI of project) given, or use any instance that has the id set
+    * Instantiate a new objects with ``iri`` given, or use any instance that has the iri set
     * Call the ``delete``-method on the instance
 
 In addition there is a static methods ``getAllProjects`` which returns a list of all projects
 """
 
+from __future__ import annotations
+
+import json
+from typing import Any, Optional, Union
+from urllib.parse import quote_plus
+
+from dsp_tools.models.connection import Connection
+from dsp_tools.models.exceptions import BaseError
+from dsp_tools.models.helpers import Actions
+from dsp_tools.models.langstring import LangString, Languages
+from dsp_tools.models.model import Model
+from dsp_tools.models.set_encoder import SetEncoder
+
 
 class Project(Model):
     """
     This class represents a project in DSP.
 
     Attributes
     ----------
 
     con : Connection
         A Connection instance to a DSP server
 
-    id : str
+    iri : str
         IRI of the project [readonly, cannot be modified after creation of instance]
 
     shortcode : str
         DSP project shortcode [readonly, cannot be modified after creation of instance]
 
     shortname : str
         DSP project shortname [read/write]
@@ -96,15 +95,15 @@
         Prints the project information to stdout
 
     """
 
     ROUTE: str = "/admin/projects"
     IRI: str = ROUTE + "/iri/"
 
-    _id: str
+    _iri: str
     _shortcode: str
     _shortname: str
     _longname: str
     _description: LangString
     _keywords: set[str]
     _ontologies: set[str]
     _selfjoin: bool
@@ -112,68 +111,68 @@
     _logo: Optional[str]
 
     SYSTEM_PROJECT: str = "http://www.knora.org/ontology/knora-admin#SystemProject"
 
     def __init__(
         self,
         con: Connection,
-        id: Optional[str] = None,
+        iri: Optional[str] = None,
         shortcode: Optional[str] = None,
         shortname: Optional[str] = None,
         longname: Optional[str] = None,
         description: LangString = None,
         keywords: Optional[set[str]] = None,
         ontologies: Optional[set[str]] = None,
         selfjoin: Optional[bool] = None,
         status: Optional[bool] = None,
         logo: Optional[str] = None,
     ):
         """
         Constructor for Project
 
         :param con: Connection instance
-        :param id: IRI of the project [required for CREATE, READ]
-        :param shortcode: Shortcode of the project. String inf the form 'XXXX' where each X is a hexadezimal sign 0-1,A,B,C,D,E,F. [required for CREATE]
+        :param iri: IRI of the project [required for CREATE, READ]
+        :param shortcode: Shortcode of the project. Four-digit hexadecimal number. [required for CREATE]
         :param shortname: Shortname of the project [required for CREATE]
         :param longname: Longname of the project [required for CREATE]
         :param description: LangString instance containing the description [required for CREATE]
         :param keywords: Set of keywords [required for CREATE]
         :param ontologies: Set of ontologies that belong to this project [optional]
         :param selfjoin: Allow selfjoin [required for CREATE]
         :param status: Status of project (active if True) [required for CREATE]
         :param logo: Path to logo image file [optional] NOT YET USED
         """
         super().__init__(con)
-        self._id = id
+        self._iri = iri
         self._shortcode = shortcode
         self._shortname = shortname
         self._longname = longname
         self._description = LangString(description)
         self._keywords = keywords
         if not isinstance(ontologies, set) and ontologies is not None:
             raise BaseError("Ontologies must be a set of strings or None!")
         self._ontologies = ontologies
         self._selfjoin = selfjoin
         self._status = status
         self._logo = logo
 
     def __str__(self):
-        tmpstr = self._id + "\n  " + self._shortcode + "\n  " + self._shortname
+        tmpstr = self._iri + "\n  " + self._shortcode + "\n  " + self._shortname
         return tmpstr
 
     #
     # Here follows a list of getters/setters
     #
     @property
-    def id(self) -> Optional[str]:
-        return self._id
+    def iri(self) -> Optional[str]:
+        return self._iri
 
-    @id.setter
-    def id(self, value: str) -> None:
-        raise BaseError("Project id cannot be modified!")
+    @iri.setter
+    def iri(self, value: str) -> None:
+        raise BaseError("Project iri cannot be modified!")
 
     @property
     def shortcode(self) -> Optional[str]:
         return self._shortcode
 
     @shortcode.setter
     def shortcode(self, value: str) -> None:
@@ -220,15 +219,15 @@
         self._description[lang] = value
         self._changed.add("description")
 
     def rmDescription(self, lang: Union[Languages, str]) -> None:
         """
         Remove a description from a project (executed at next update)
 
-        :param lang: The language the description to be removed is in, either a string "EN", "DE", "FR", "IT" or a Language instance
+        :param lang: language of the description, either "EN", "DE", "FR", "IT", "RM", or a Language instance
         :return: None
         """
 
         del self._description[lang]
         self._changed.add("description")
 
     @property
@@ -265,15 +264,15 @@
 
         :param value: keyword
         :return: None
         """
         try:
             self._keywords.remove(value)
         except KeyError as ke:
-            raise BaseError('Keyword "' + value + '" is not in keyword set')
+            raise BaseError('Keyword "' + value + '" is not in keyword set') from ke
         self._changed.add("keywords")
 
     @property
     def ontologies(self) -> set[str]:
         return self._ontologies
 
     @ontologies.setter
@@ -317,17 +316,17 @@
 
         This method is used to create a Project instance from the JSON data returned by DSP
 
         :param con: Connection instance
         :param json_obj: JSON data returned by DSP as python3 object
         :return: Project instance
         """
-        id = json_obj.get("id")
-        if id is None:
-            raise BaseError("Project id is missing")
+        iri = json_obj.get("id")
+        if iri is None:
+            raise BaseError("Project iri is missing")
         shortcode = json_obj.get("shortcode")
         if shortcode is None:
             raise BaseError("Shortcode is missing")
         shortname = json_obj.get("shortname")
         if shortname is None:
             raise BaseError("Shortname is missing")
         longname = json_obj.get("longname")
@@ -345,15 +344,15 @@
             raise BaseError("Selfjoin is missing")
         status = json_obj.get("status")
         if status is None:
             raise BaseError("Status is missing")
         logo = json_obj.get("logo")
         return cls(
             con=con,
-            id=id,
+            iri=iri,
             shortcode=shortcode,
             shortname=shortname,
             longname=longname,
             description=description,
             keywords=keywords,
             ontologies=ontologies,
             selfjoin=selfjoin,
@@ -435,119 +434,55 @@
     def read(self) -> Project:
         """
         Read a project from DSP
 
         :return: JSON-object from DSP
         """
         result = None
-        if self._id is not None:
-            result = self._con.get(Project.IRI + quote_plus(self._id))
+        if self._iri is not None:
+            result = self._con.get(Project.IRI + quote_plus(self._iri))
         elif self._shortcode is not None:
             result = self._con.get(Project.ROUTE + "/shortcode/" + quote_plus(self._shortcode))
         elif self._shortname is not None:
             result = self._con.get(Project.ROUTE + "/shortname/" + quote_plus(self._shortname))
         if result is not None:
             return Project.fromJsonObj(self._con, result["project"])
         else:
             raise BaseError(
-                f"ERROR: Could not read project '{self.shortname}' ({self.shortcode}) with IRI {self._id} "
+                f"ERROR: Could not read project '{self.shortname}' ({self.shortcode}) with IRI {self._iri} "
                 f"from DSP server."
             )
 
     def update(self) -> Project:
         """
         Update the project information on the DSP with the modified data in this project instance
 
         Returns: JSON object returned as response from DSP reflecting the update
         """
 
         jsonobj = self.toJsonObj(Actions.Update)
         jsondata = json.dumps(jsonobj, cls=SetEncoder)
-        result = self._con.put(Project.IRI + quote_plus(self.id), jsondata)
+        result = self._con.put(Project.IRI + quote_plus(self.iri), jsondata)
         return Project.fromJsonObj(self._con, result["project"])
 
     def delete(self) -> Project:
         """
         Delete the given DSP project
 
         :return: DSP response
         """
 
-        result = self._con.delete(Project.IRI + quote_plus(self._id))
+        result = self._con.delete(Project.IRI + quote_plus(self._iri))
         return Project.fromJsonObj(self._con, result["project"])
 
-    def set_default_permissions(self, group_id: str) -> None:
-        permobj = {
-            "forGroup": "http://www.knora.org/ontology/knora-admin#ProjectMember",
-            "forProject": self._id,
-            "hasPermissions": [
-                {
-                    "additionalInformation": None,
-                    "name": "ProjectResourceCreateAllPermission",
-                    "permissionCode": None,
-                }
-            ],
-        }
-        jsondata = json.dumps(permobj, indent=4)
-        print(jsondata)
-        result = self._con.post("/admin/permissions/ap", jsondata)
-        pprint(result)
-
-        return
-        permobj = {
-            "forGroup": group_id,
-            "forProject": self._id,
-            "forProperty": None,
-            "forResourceClass": None,
-            "hasPermissions": [
-                {
-                    "additionalInformation": "http://www.knora.org/ontology/knora-admin#ProjectMember",
-                    "name": "D",
-                    "permissionCode": 7,
-                }
-            ],
-        }
-        jsondata = json.dumps(permobj)
-        result = self._con.post("/admin/permissions/ap", jsondata)
-        pprint(result)
-
     @staticmethod
     def getAllProjects(con: Connection) -> list[Project]:
         """
         Get all existing projects in DSP
 
         :param con: Connection instance
         :return:
         """
         result = con.get(Project.ROUTE)
         if "projects" not in result:
             raise BaseError("Request got no projects!")
         return [Project.fromJsonObj(con, a) for a in result["projects"]]
-
-    def print(self) -> None:
-        """
-        print info to stdout
-
-        :return: None
-        """
-
-        print("Project Info:")
-        print("  Id:         {}".format(self._id))
-        print("  Shortcode:  {}".format(self._shortcode))
-        print("  Shortname:  {}".format(self._shortname))
-        print("  Longname:   {}".format(self._longname))
-        if self._description is not None:
-            print("  Description:")
-            for descr in self._description.items():
-                print("    {}: {}".format(descr[0], descr[1]))
-        else:
-            print("  Description: None")
-        if self._keywords is not None:
-            print("  Keywords:   {}".format(" ".join(self._keywords)))
-        else:
-            print("  Keywords:   None")
-        if self._ontologies is not None:
-            print("  Ontologies: {}".format(" ".join(self._ontologies)))
-        else:
-            print("  Ontologies: None")
-        print("  Selfjoin:   {}".format(self._selfjoin))
-        print("  Status:     {}".format(self._status))
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/projectContext.py` & `dsp_tools-2.3.4/src/dsp_tools/models/projectContext.py`

 * *Files 19% similar despite different names*

```diff
@@ -6,26 +6,24 @@
 from dsp_tools.models.project import Project
 
 
 class ProjectContext:
     """Represents the project context"""
 
     _projects: list[Project]
-    _project_map: dict[str, str]  # dictionary of (project name:project IRI) pairs
     _inv_project_map: dict[str, str]  # dictionary of (project IRI:project name) pairs
     _groups: Optional[list[Group]]
     _group_map: Optional[dict[str, str]]
     _shortcode: Optional[str]
     _project_name: Optional[str]
 
     def __init__(self, con: Connection, shortcode: Optional[str] = None):
         self._shortcode = shortcode
         self._projects = Project.getAllProjects(con=con)
-        self._project_map: dict[str, str] = {x.shortname: x.id for x in self._projects}
-        self._inv_project_map: dict[str, str] = {x.id: x.shortname for x in self._projects}
+        self._inv_project_map: dict[str, str] = {x.iri: x.shortname for x in self._projects}
         try:
             self._groups = Group.getAllGroups(con=con)
         except BaseError:
             self._groups = None
         if self._groups:
             self._group_map: dict[str, str] = {
                 self._inv_project_map[x.project] + ":" + x.name: x.iri for x in self._groups
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/propertyclass.py` & `dsp_tools-2.3.4/src/dsp_tools/models/propertyclass.py`

 * *Files 8% similar despite different names*

```diff
@@ -12,57 +12,57 @@
 from dsp_tools.models.set_encoder import SetEncoder
 
 
 class PropertyClass(Model):
     ROUTE: str = "/v2/ontologies/properties"
 
     _context: Context
-    _id: str
+    _iri: str
     _name: str
     _ontology_id: str
     _superproperties: list[str]
-    _object: str
-    _subject: str
+    _rdf_object: str
+    _rdf_subject: str
     _gui_element: str
     _gui_attributes: dict[str, str]
     _label: LangString
     _comment: LangString
     _editable: bool
     _linkvalue: bool
 
     def __init__(
         self,
         con: Connection,
         context: Context,
-        id: Optional[str] = None,
+        iri: Optional[str] = None,
         name: Optional[str] = None,
         ontology_id: Optional[str] = None,
         superproperties: Optional[Sequence[Union["PropertyClass", str]]] = None,
-        object: Optional[str] = None,
-        subject: Optional[str] = None,
+        rdf_object: Optional[str] = None,
+        rdf_subject: Optional[str] = None,
         gui_element: Optional[str] = None,
         gui_attributes: Optional[dict[str, str]] = None,
         label: Optional[Union[LangString, str]] = None,
         comment: Optional[Union[LangString, str]] = None,
         editable: Optional[bool] = None,
         linkvalue: Optional[bool] = None,
     ):
         super().__init__(con)
         if not isinstance(context, Context):
             raise BaseError('"context"-parameter must be an instance of Context')
         self._context = context
-        self._id = id
+        self._iri = iri
         self._name = name
         self._ontology_id = ontology_id
         if isinstance(superproperties, PropertyClass):
-            self._superproperties = list(map(lambda a: a.id, superproperties))
+            self._superproperties = list(map(lambda a: a.iri, superproperties))
         else:
             self._superproperties = superproperties
-        self._object = object
-        self._subject = subject
+        self._rdf_object = rdf_object
+        self._rdf_subject = rdf_subject
         self._gui_element = gui_element
         self._gui_attributes = gui_attributes
         #
         # process label
         #
         if label is not None:
             if isinstance(label, str):
@@ -97,20 +97,20 @@
         return self._name
 
     @name.setter
     def name(self, value: str) -> None:
         raise BaseError('"name" cannot be modified!')
 
     @property
-    def id(self) -> Optional[str]:
-        return self._id
+    def iri(self) -> Optional[str]:
+        return self._iri
 
-    @id.setter
-    def id(self, value: str) -> None:
-        raise BaseError('"id" cannot be modified!')
+    @iri.setter
+    def iri(self, value: str) -> None:
+        raise BaseError('"iri" cannot be modified!')
 
     @property
     def ontology_id(self) -> Optional[str]:
         return self._ontology_id
 
     @ontology_id.setter
     def ontology_id(self, value: str) -> None:
@@ -121,56 +121,37 @@
         return self._superproperties
 
     @superproperties.setter
     def superproperties(self, value: str) -> None:
         raise BaseError('"superproperties" cannot be modified!')
 
     @property
-    def object(self) -> Optional[str]:
-        return self._object
+    def rdf_object(self) -> Optional[str]:
+        return self._rdf_object
 
-    @object.setter
-    def object(self, value: Any):
-        raise BaseError('"object" cannot be modified!')
+    @rdf_object.setter
+    def rdf_object(self, value: Any):
+        raise BaseError('"rdf_object" cannot be modified!')
 
     @property
-    def subject(self) -> Optional[str]:
-        return self._subject
+    def rdf_subject(self) -> Optional[str]:
+        return self._rdf_subject
 
-    @subject.setter
-    def subject(self, value: Any):
-        raise BaseError('"subject" cannot be modified!')
+    @rdf_subject.setter
+    def rdf_subject(self, value: Any):
+        raise BaseError('"rdf_subject" cannot be modified!')
 
     @property
     def gui_element(self) -> Optional[str]:
         return self._gui_element
 
-    @gui_element.setter
-    def gui_element(self, value: str) -> None:
-        self._gui_element = value
-        self._changed.append("gui_element")
-
     @property
     def gui_attributes(self) -> Optional[dict[str, str]]:
         return self._gui_attributes
 
-    @gui_attributes.setter
-    def gui_attributes(self, value: list[dict[str, str]]) -> None:
-        self._gui_attributes = value
-        self._changed.append("gui_attributes")
-
-    def addGuiAttribute(self, key: str, value: str) -> None:
-        self._gui_attributes[key] = value
-        self._changed.append("gui_attributes")
-
-    def rmGuiAttribute(self, key: str) -> None:
-        if self._gui_attributes.get(key) is not None:
-            del self._gui_attributes[key]
-            self._changed.append("gui_attributes")
-
     @property
     def label(self) -> LangString:
         return self._label
 
     @label.setter
     def label(self, value: Optional[Union[LangString, str]]) -> None:
         if value is None:
@@ -230,46 +211,43 @@
         return self._linkvalue
 
     @linkvalue.setter
     def linkvalue(self) -> None:
         raise BaseError('"linkvalue" cannot be modified!')
 
     @classmethod
-    def fromJsonObj(cls, con: Connection, context: Context, json_obj: Any) -> Any:
+    def fromJsonObj(cls, con: Connection, context: Context, json_obj: Any) -> "PropertyClass":
         if isinstance(json_obj, list):
-            json_obj = json_obj[0]  # TODO: Is it possible to have more than one element in the list??
+            json_obj = json_obj[0]
         if not isinstance(con, Connection):
             raise BaseError('"con"-parameter must be an instance of Connection')
         if not isinstance(context, Context):
             raise BaseError('"context"-parameter must be an instance of Context')
-        rdf = context.prefix_from_iri("http://www.w3.org/1999/02/22-rdf-syntax-ns#")
         rdfs = context.prefix_from_iri("http://www.w3.org/2000/01/rdf-schema#")
-        owl = context.prefix_from_iri("http://www.w3.org/2002/07/owl#")
-        xsd = context.prefix_from_iri("http://www.w3.org/2001/XMLSchema#")
         knora_api = context.prefix_from_iri("http://api.knora.org/ontology/knora-api/v2#")
         salsah_gui = context.prefix_from_iri("http://api.knora.org/ontology/salsah-gui/v2#")
 
-        if not (json_obj.get(knora_api + ":isResourceProperty")):
+        if not json_obj.get(knora_api + ":isResourceProperty"):
             raise BaseError("This is not a property!")
         if json_obj.get("@id") is None:
             raise BaseError('Property class has no "@id"!')
         tmp_id = json_obj.get("@id").split(":")
-        id = context.iri_from_prefix(tmp_id[0]) + "#" + tmp_id[1]
+        iri = context.iri_from_prefix(tmp_id[0]) + "#" + tmp_id[1]
         ontology_id = tmp_id[0]
         name = tmp_id[1]
         superproperties_obj = json_obj.get(rdfs + ":subPropertyOf")
         superproperties: list[Union[None, str]]
         if not isinstance(superproperties_obj, list):
             superproperties_obj = [superproperties_obj]  # make a list out of it
         if superproperties_obj:
             superproperties = [x["@id"] for x in superproperties_obj if x and x.get("@id")]
         else:
             superproperties = None
-        object = WithId(json_obj.get(knora_api + ":objectType")).str()
-        subject = WithId(json_obj.get(knora_api + ":subjectType")).str()
+        rdf_object = WithId(json_obj.get(knora_api + ":objectType")).str()
+        rdf_subject = WithId(json_obj.get(knora_api + ":subjectType")).str()
         label = LangString.fromJsonLdObj(json_obj.get(rdfs + ":label"))
         comment = LangString.fromJsonLdObj(json_obj.get(rdfs + ":comment"))
         gui_element = None
         if json_obj.get(salsah_gui + ":guiElement") is not None:
             gui_element = WithId(json_obj.get(salsah_gui + ":guiElement")).str()
             gui_element = gui_element.replace("Pulldown", "List")
             gui_element = gui_element.replace("Radio", "List")
@@ -287,20 +265,20 @@
                     gui_attributes[tmp[0]] = tmp[1]
 
         editable = json_obj.get(knora_api + ":isEditable")
         linkvalue = json_obj.get(knora_api + ":isLinkProperty")
         return cls(
             con=con,
             context=context,
-            id=id,
+            iri=iri,
             name=name,
             ontology_id=ontology_id,
             superproperties=superproperties,
-            object=object,
-            subject=subject,
+            rdf_object=rdf_object,
+            rdf_subject=rdf_subject,
             gui_element=gui_element,
             gui_attributes=gui_attributes,
             label=label,
             comment=comment,
             editable=editable,
             linkvalue=linkvalue,
         )
@@ -351,18 +329,18 @@
                         "rdfs:subPropertyOf": superproperties,
                     }
                 ],
                 "@context": self._context.toJsonObj(),
             }
             if self._comment:
                 tmp["@graph"][0]["rdfs:comment"] = self._comment.toJsonLdObj()
-            if self._subject:
-                tmp["@graph"][0]["knora-api:subjectType"] = resolve_propref(self._subject)
-            if self._object:
-                tmp["@graph"][0]["knora-api:objectType"] = resolve_propref(self._object)
+            if self._rdf_subject:
+                tmp["@graph"][0]["knora-api:subjectType"] = resolve_propref(self._rdf_subject)
+            if self._rdf_object:
+                tmp["@graph"][0]["knora-api:objectType"] = resolve_propref(self._rdf_object)
             if self._gui_element:
                 tmp["@graph"][0]["salsah-gui:guiElement"] = {"@id": self._gui_element}
             if self._gui_attributes:
                 ga = list(map(lambda x: x[0] + "=" + str(x[1]), self._gui_attributes.items()))
                 tmp["@graph"][0]["salsah-gui:guiAttribute"] = ga
         elif action == Actions.Update:
             tmp = {
@@ -389,15 +367,15 @@
     def create(self, last_modification_date: DateTimeStamp) -> tuple[DateTimeStamp, "PropertyClass"]:
         jsonobj = self.toJsonObj(last_modification_date, Actions.Create)
         jsondata = json.dumps(jsonobj, cls=SetEncoder, indent=2)
         result = self._con.post(PropertyClass.ROUTE, jsondata)
         last_modification_date = DateTimeStamp(result["knora-api:lastModificationDate"])
         return last_modification_date, PropertyClass.fromJsonObj(self._con, self._context, result["@graph"])
 
-    def update(self, last_modification_date: DateTimeStamp) -> tuple[DateTimeStamp, "ResourceClass"]:
+    def update(self, last_modification_date: DateTimeStamp) -> tuple[DateTimeStamp, "PropertyClass"]:
         #
         # Note: DSP is able to change only one thing per call, either label or comment!
         #
         result = None
         something_changed = False
         if "label" in self._changed:
             jsonobj = self.toJsonObj(last_modification_date, Actions.Update, "label")
@@ -414,44 +392,44 @@
         if something_changed:
             return last_modification_date, PropertyClass.fromJsonObj(self._con, self._context, result["@graph"])
         else:
             return last_modification_date, self
 
     def delete(self, last_modification_date: DateTimeStamp) -> DateTimeStamp:
         result = self._con.delete(
-            PropertyClass.ROUTE + "/" + quote_plus(self._id) + "?lastModificationDate=" + str(last_modification_date)
+            PropertyClass.ROUTE + "/" + quote_plus(self._iri) + "?lastModificationDate=" + str(last_modification_date)
         )
         return DateTimeStamp(result["knora-api:lastModificationDate"])
 
     def createDefinitionFileObj(self, context: Context, shortname: str):
         """
         Create an object that can be used as input for `create_onto()` to create an ontology on a DSP server
 
         :param context: Context of the ontology
         :param shortname: Shortname of the ontology
         :return: Python object to be jsonfied
         """
-        property = {"name": self.name}
-        if self.object:
-            property["name"] = self.name
+        def_file_obj = {"name": self.name}
+        if self.rdf_object:
+            def_file_obj["name"] = self.name
         if self.superproperties:
             superprops = []
             for sc in self.superproperties:
                 superprops.append(context.reduce_iri(sc, shortname))
-            property["super"] = superprops
-        if self.subject:
-            property["subject"] = context.reduce_iri(self.subject, shortname)
-        if self.object:
-            property["object"] = context.reduce_iri(self.object, shortname)
+            def_file_obj["super"] = superprops
+        if self.rdf_subject:
+            def_file_obj["subject"] = context.reduce_iri(self.rdf_subject, shortname)
+        if self.rdf_object:
+            def_file_obj["object"] = context.reduce_iri(self.rdf_object, shortname)
         if not self.label.isEmpty():
-            property["labels"] = self.label.createDefinitionFileObj()
+            def_file_obj["labels"] = self.label.createDefinitionFileObj()
         if not self.comment.isEmpty():
-            property["comments"] = self.comment.createDefinitionFileObj()
+            def_file_obj["comments"] = self.comment.createDefinitionFileObj()
         if self.gui_element:
-            property["gui_element"] = context.reduce_iri(self.gui_element, shortname)
+            def_file_obj["gui_element"] = context.reduce_iri(self.gui_element, shortname)
         if self.gui_attributes:
             gui_elements = {}
             for attname, attvalue in self.gui_attributes.items():
                 if attname == "size":
                     gui_elements[attname] = int(attvalue)
                 elif attname == "maxlength":
                     gui_elements[attname] = int(attvalue)
@@ -475,40 +453,9 @@
                     gui_elements[attname] = str(attvalue)
                 elif attname == "max":
                     gui_elements[attname] = float(attvalue)
                 elif attname == "min":
                     gui_elements[attname] = float(attvalue)
                 else:
                     gui_elements[attname] = str(attvalue)
-            property["gui_attributes"] = gui_elements
-        return property
-
-    def print(self, offset: int = 0):
-        blank = " "
-        print(f"{blank:>{offset}}Property Class Info")
-        print(f"{blank:>{offset + 2}}Name:            {self._name}")
-        print(f"{blank:>{offset + 2}}Ontology prefix: {self._ontology_id}")
-        print(f"{blank:>{offset + 2}}Superproperties:")
-        if self._superproperties is not None:
-            for sc in self._superproperties:
-                print(f"{blank:>{offset + 4}}{sc}")
-        if self._label is not None:
-            print(f"{blank:>{offset + 2}}Labels:")
-            self._label.print(offset + 4)
-        if self._subject is not None:
-            print(f"{blank:>{offset + 4}}Subject: {self._subject}")
-        if self._object is not None:
-            print(f"{blank:>{offset + 4}}Object: {self._object}")
-        if self._gui_element is not None:
-            print(f"{blank:>{offset + 4}}Guielement: {self._gui_element}")
-        if self._gui_attributes is not None:
-            print(f"{blank:>{offset + 4}}Gui Attributes:")
-            if self._gui_attributes is not None:
-                for attname, attvalue in self._gui_attributes.items():
-                    print(f"{blank:>{offset + 6}}Attribute: {attname} Value: {attvalue}")
-        if self._comment is not None:
-            print(f"{blank:>{offset + 2}}Comments:")
-            self._comment.print(offset + 4)
-        if self._editable is not None:
-            print(f"{blank:>{offset + 4}}Editable: {self._editable}")
-        if self._linkvalue is not None:
-            print(f"{blank:>{offset + 4}}Editable: {self._linkvalue}")
+            def_file_obj["gui_attributes"] = gui_elements
+        return def_file_obj
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/propertyelement.py` & `dsp_tools-2.3.4/src/dsp_tools/models/propertyelement.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,12 +1,14 @@
 from dataclasses import dataclass
 from typing import Optional, Union
 
 from dsp_tools.models.exceptions import BaseError
 
+# pylint: disable=line-too-long
+
 
 @dataclass(frozen=True)
 class PropertyElement:
     """
     A PropertyElement object carries more information about a property value than the value itself.
     The "value" is the value that could be passed to a method as plain string/int/float/bool. Use a PropertyElement
     instead to define more precisely what attributes your value tag (e.g. <text>, <uri>, ...) will have.
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/resource.py` & `dsp_tools-2.3.4/src/dsp_tools/models/resource.py`

 * *Files 5% similar despite different names*

```diff
@@ -34,22 +34,22 @@
     fromJsonLdObj,
 )
 
 
 class KnoraStandoffXmlEncoder(json.JSONEncoder):
     """Classes used as wrapper for DSP standoff-XML"""
 
-    def default(self, obj) -> str:
-        if isinstance(obj, KnoraStandoffXml):
-            return '<?xml version="1.0" encoding="UTF-8"?>\n<text>' + str(obj) + "</text>"
-        elif isinstance(obj, OntoIri):
-            return obj.iri + "#" if obj.hashtag else ""
-        elif isinstance(obj, DateTimeStamp):
-            return str(obj)
-        return json.JSONEncoder.default(self, obj)
+    def default(self, o) -> str:
+        if isinstance(o, KnoraStandoffXml):
+            return '<?xml version="1.0" encoding="UTF-8"?>\n<text>' + str(o) + "</text>"
+        elif isinstance(o, OntoIri):
+            return o.iri + "#" if o.hashtag else ""
+        elif isinstance(o, DateTimeStamp):
+            return str(o)
+        return json.JSONEncoder.default(self, o)
 
 
 @dataclass
 class Propinfo:
     valtype: Type
     cardinality: Cardinality
     gui_order: int
@@ -120,76 +120,80 @@
 
         if self.baseclass in self.baseclasses_with_bitstream and bitstream is None:
             raise BaseError(
                 f"ERROR in resource with label '{self._label}': Baseclass '{self.baseclass}' requires a bitstream value"
             )
         if self.baseclass not in self.baseclasses_with_bitstream and bitstream:
             raise BaseError(
-                f"ERROR in resource with label '{self._label}': Baseclass '{self.baseclass}' does not allow a bitstream value"
+                f"ERROR in resource with label '{self._label}': "
+                f"Baseclass '{self.baseclass}' does not allow a bitstream value"
             )
         if self.baseclass in self.baseclasses_with_bitstream and bitstream:
             self._bitstream = bitstream
         else:
             self._bitstream = None
 
         self._values = {}
         if values:
             for property_name, property_info in self.properties.items():
                 cardinality = property_info.cardinality
                 value_type = property_info.valtype
                 value = values.get(property_name)
                 if value:
                     # property has multiple values
-                    if type(value) is list:
+                    if isinstance(value, list):
                         self._values[property_name] = []
                         for val in value:
                             # check if cardinality allows multiple values for a property
                             if cardinality == Cardinality.C_0_1 or cardinality == Cardinality.C_1:
                                 raise BaseError(
-                                    f"ERROR in resource with label '{self._label}': Ontology does not allow multiple values for '{property_name}'"
+                                    f"ERROR in resource with label '{self._label}': "
+                                    f"Ontology does not allow multiple values for '{property_name}'"
                                 )
 
-                            if type(val) is Value:
+                            if isinstance(val, Value):
                                 self._values[property_name].append(val)
 
-                            elif type(val) is dict:
+                            elif isinstance(val, dict):
                                 if value_type is ListValue:
                                     val["lists"] = self.lists
                                 self._values[property_name].append(value_type(**val))
 
                             else:
                                 if value_type is ListValue:
                                     val = {"value": val, "lists": self.lists}
                                 self._values[property_name].append(value_type(val))
                     # property has one value
                     else:
-                        if type(value) is Value:
+                        if isinstance(value, Value):
                             self._values[property_name] = value
 
-                        elif type(value) is dict:
+                        elif isinstance(value, dict):
                             if value_type is ListValue:
                                 value["lists"] = self.lists
                             self._values[property_name] = value_type(**value)
 
                         else:
                             if value_type is ListValue:
                                 value = {"value": value, "lists": self.lists}
                                 self._values[property_name] = value_type(**value)
                             else:
                                 self._values[property_name] = value_type(value)
                 else:
                     if cardinality == Cardinality.C_1 or cardinality == Cardinality.C_1_n:
                         raise BaseError(
-                            f"ERROR in resource with label '{self._label}': The ontology requires at least one value for '{property_name}'"
+                            f"ERROR in resource with label '{self._label}': "
+                            f"The ontology requires at least one value for '{property_name}'"
                         )
 
             for property_name in values:
                 if property_name not in self.knora_properties and not self.properties.get(property_name):
                     raise BaseError(
-                        f"ERROR in resource with label '{self._label}': Property '{property_name}' is not part of ontology"
+                        f"ERROR in resource with label '{self._label}': "
+                        f"Property '{property_name}' is not part of ontology"
                     )
 
     def value(self, item) -> Optional[list[Value]]:
         if self._values.get(item):
             value = self._values[item]
 
             # value has multiple values
@@ -212,34 +216,25 @@
     def ark(self) -> str:
         return self._ark
 
     @property
     def creation_date(self) -> Optional[DateTimeStamp]:
         return self._creation_date
 
-    @property
-    def vark(self) -> str:
-        return self._version_ark
-
     def clone(self) -> "ResourceInstance":
         return deepcopy(self)
 
-    def fromJsonLdObj(self, con: Connection, jsonld_obj: Any) -> "ResourceInstance":
+    def fromJsonLdObj(self, jsonld_obj: dict[str, Any]) -> "ResourceInstance":
         newinstance = self.clone()
         newinstance._iri = jsonld_obj.get("@id")
-        resclass = jsonld_obj.get("@type")
-        context = Context(jsonld_obj.get("@context"))
         newinstance._label = jsonld_obj.get("rdfs:label")
         newinstance._ark = Value.get_typed_value("knora-api:arkUrl", jsonld_obj)
         newinstance._version_ark = Value.get_typed_value("knora-api:versionArkUrl", jsonld_obj)
         newinstance._permissions = Permissions.fromString(jsonld_obj.get("knora-api:hasPermissions"))
         newinstance._user_permission = PermissionValue[jsonld_obj.get("knora-api:userHasPermission", jsonld_obj)]
-        creation_date = Value.get_typed_value("knora-api:creationDate", jsonld_obj)
-        user = Value.get_typed_value("knora-api:attachedToUser", jsonld_obj)
-        project = Value.get_typed_value("knora-api:attachedToProject", jsonld_obj)
         to_be_ignored = [
             "@id",
             "@type",
             "@context",
             "rdfs:label",
             "knora-api:arkUrl",
             "knora-api:versionArkUrl",
@@ -247,28 +242,27 @@
             "knora-api:attachedToUser",
             "knora-api:attachedToProject",
             "knora-api:hasPermissions",
             "knora-api:userHasPermission",
         ]
         if id is None:
             raise BaseError('Resource "id" is missing in JSON-LD from DSP-API')
-        type = jsonld_obj.get("@type")
         newinstance._values: dict[str, Union[Value, list[Value]]] = {}
         for key, obj in jsonld_obj.items():
             if key in to_be_ignored:
                 continue
             try:
                 if isinstance(obj, list):
                     newinstance._values[key] = []
                     for o in obj:
                         newinstance._values[key].append(fromJsonLdObj(o))
                 else:
                     newinstance._values[key] = fromJsonLdObj(obj)
             except KeyError as kerr:
-                raise BaseError('Invalid data in JSON-LD: "{}" has value class "{}"!'.format(key, obj.get("@type")))
+                raise BaseError(f'Invalid data in JSON-LD: "{key}" has value class "{obj.get("@type")}"!') from kerr
         return newinstance
 
     def toJsonLdObj(self, action: Actions) -> Any:
         tmp = {}
         if action == Actions.Create:
             # if a custom IRI is provided, use it
             if self._iri:
@@ -306,23 +300,23 @@
                     bitstream_attributes["@type"] = "knora-api:MovingImageFileValue"
                     tmp["knora-api:hasMovingImageFileValue"] = bitstream_attributes
                 else:
                     raise BaseError(f"Baseclass '{self.baseclass}' not yet supported!")
 
             for property_name, value in self._values.items():
                 # if the property has several values
-                if type(value) is list:
-                    if type(value[0]) is LinkValue:
+                if isinstance(value, list):
+                    if isinstance(value[0], LinkValue):
                         property_name += "Value"
                     # append all values to that property
                     tmp[property_name] = []
                     for vt in value:
                         tmp[property_name].append(vt.toJsonLdObj(action))
                 # if property is a link
-                elif type(value) is LinkValue:
+                elif isinstance(value, LinkValue):
                     property_name += "Value"
                     tmp[property_name] = value.toJsonLdObj(action)
                 else:
                     tmp[property_name] = value.toJsonLdObj(action)
 
             tmp["@context"] = self.context
 
@@ -338,67 +332,50 @@
         newinstance._iri = result["@id"]
         newinstance._ark = result["knora-api:arkUrl"]["@value"]
         newinstance._version_ark = result["knora-api:versionArkUrl"]["@value"]
         return newinstance
 
     def read(self) -> "ResourceInstance":
         result = self._con.get(ResourceInstance.ROUTE + "/" + quote_plus(self._iri))
-        return self.fromJsonLdObj(con=self._con, jsonld_obj=result)
+        return self.fromJsonLdObj(result)
 
     def update(self):
         pass
 
     def delete(self):
         pass
 
-    def print(self):
-        print("IRI:", self._iri)
-        print("ARK:", self._ark)
-        print("Version ARK:", self._version_ark)
-        print("Label:", self._label)
-        print("Permissions:", str(self._permissions))
-        print("User permission:", str(self._user_permission))
-        for name, val in self._values.items():
-            if isinstance(val, list):
-                tmp = [str(x) for x in val]
-                print(name, ":", " | ".join(tmp))
-                pass
-            else:
-                print(name, ":", str(val))
-
 
 class ResourceInstanceFactory:
     _con: Connection
     _project: Project
     _lists = list[ListNode]
     _ontologies = dict[str, Ontology]
-    _ontoname2iri = dict[str, str]
     _context: Context
 
     def __init__(self, con: Connection, projident: str) -> None:
         self._con = con
         if re.match("^[0-9a-fA-F]{4}$", projident):
             project = Project(con=con, shortcode=projident)
         elif re.match("^[\\w-]+$", projident):
             project = Project(con=con, shortname=projident)
         elif re.match("^(http)s?://([\\w\\.\\-~]+:?\\d{,4})(/[\\w\\-~]+)+$", projident):
             project = Project(con=con, shortname=projident)
         else:
             raise BaseError("Invalid project identification!")
         self._project = project.read()
 
-        self._lists = [x.getAllNodes() for x in ListNode.getAllLists(con=con, project_iri=self._project.id)]
+        self._lists = [x.getAllNodes() for x in ListNode.getAllLists(con=con, project_iri=self._project.iri)]
 
-        tmp_ontologies = Ontology.getProjectOntologies(con=con, project_id=self._project.id)
+        tmp_ontologies = Ontology.getProjectOntologies(con=con, project_id=self._project.iri)
         shared_project = Project(con=con, shortcode="0000").read()
-        shared_ontologies = Ontology.getProjectOntologies(con=con, project_id=shared_project.id)
+        shared_ontologies = Ontology.getProjectOntologies(con=con, project_id=shared_project.iri)
         tmp_ontologies.extend(shared_ontologies)
         knora_api_onto = [x for x in Ontology.getAllOntologies(con=con) if x.name == "knora-api"][0]
         tmp_ontologies.append(knora_api_onto)
-        self._ontoname2iri = {x.name: x.iri for x in tmp_ontologies}
 
         ontology_ids = [x.iri for x in tmp_ontologies]
         self._ontologies = {}
         self._properties = {}
         self._context = {}
         for onto in ontology_ids:
             oparts = onto.split("/")
@@ -410,17 +387,17 @@
 
     @property
     def lists(self) -> list[ListNode]:
         return self._lists
 
     def get_resclass_names(self) -> list[str]:
         resclass_names: list[str] = []
-        for name, onto in self._ontologies.items():
+        for _, onto in self._ontologies.items():
             for resclass in onto.resource_classes:
-                resclass_names.append(onto.context.get_prefixed_iri(resclass.id))
+                resclass_names.append(onto.context.get_prefixed_iri(resclass.iri))
         return resclass_names
 
     def _get_baseclass(self, superclasses: list[str]) -> Union[str, None]:
         for sc in superclasses:
             ontoname, classname = sc.split(":")
             if ontoname == "knora-api":
                 return classname
@@ -486,34 +463,34 @@
                 )
             elif propname == "knora-api:hasSequenceBounds":
                 valtype = IntervalValue
                 props[propname] = Propinfo(
                     valtype=valtype, cardinality=has_property.cardinality, gui_order=has_property.gui_order
                 )
             elif has_property.ptype == HasProperty.Ptype.other:
-                valtype = switcher.get(self._properties[propname].object)
+                valtype = switcher.get(self._properties[propname].rdf_object)
                 if valtype == LinkValue:
                     continue  # we have the Link to the LinkValue which we do not use
                 if valtype is None:
                     valtype = LinkValue
                     props[propname] = Propinfo(
                         valtype=valtype,
                         cardinality=has_property.cardinality,
                         gui_order=has_property.gui_order,
-                        attributes=self._properties[propname].object,
+                        attributes=self._properties[propname].rdf_object,
                     )
                 else:
                     props[propname] = Propinfo(
                         valtype=valtype, cardinality=has_property.cardinality, gui_order=has_property.gui_order
                     )
         return type(
             resclass_name,
             (ResourceInstance,),
             {
-                "project": self._project.id,
+                "project": self._project.iri,
                 "classname": prefixedresclass,
                 "baseclass": baseclass,
                 "context": self._context,
                 "properties": props,
                 "lists": self._lists,
             },
         )
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/resourceclass.py` & `dsp_tools-2.3.4/src/dsp_tools/models/resourceclass.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,27 +1,27 @@
+"""
+This model implements the handling of resource classes. It contains two classes that work closely together:
+    * "HasProperty" deals with the association of Property-instances with the Resource-instances. This association
+      is done using the "cardinality"-clause
+    * "ResourceClass" is the main class representing a DSP resource class.
+"""
+
 import json
 import re
 from enum import Enum
 from typing import Any, Optional, Sequence, Union
 from urllib.parse import quote_plus
 
 from dsp_tools.models.connection import Connection
 from dsp_tools.models.exceptions import BaseError
 from dsp_tools.models.helpers import Actions, Cardinality, Context, DateTimeStamp
 from dsp_tools.models.langstring import LangString, Languages
 from dsp_tools.models.model import Model
 from dsp_tools.models.set_encoder import SetEncoder
 
-"""
-This model implements the handling of resource classes. It contains two classes that work closely together:
-    * "HasProperty" deals with the association of Property-instances with the Resource-instances. This association
-      is done using the "cardinality"-clause
-    * "ResourceClass" is the main class representing a DSP resource class.
-"""
-
 
 class HasProperty(Model):
     ROUTE: str = "/v2/ontologies/cardinalities"
 
     class Ptype(Enum):
         system = 1
         knora = 2
@@ -29,15 +29,14 @@
 
     _context: Context
     _ontology_id: str
     _property_id: str
     _resclass_id: str
     _cardinality: Cardinality
     _gui_order: int
-    _is_inherited: bool
     _ptype: Ptype
 
     def __init__(
         self,
         con: Connection,
         context: Context,
         ontology_id: Optional[str] = None,
@@ -56,15 +55,14 @@
             self._ontology_id = context.iri_from_prefix(ontology_id)
         else:
             self._ontology_id = None
         self._property_id = property_id
         self._resclass_id = resclass_id
         self._cardinality = cardinality
         self._gui_order = gui_order
-        self._is_inherited = is_inherited
         self._ptype = ptype
         self._changed = set()
 
     #
     # Here follows a list of getters/setters
     #
     @property
@@ -77,15 +75,15 @@
 
     @property
     def property_id(self) -> Optional[str]:
         return self._property_id
 
     @property_id.setter
     def property_id(self, value: str) -> None:
-        raise BaseError('property_id "{}" cannot be modified!'.format(self._property_id))
+        raise BaseError(f'property_id "{self._property_id}" cannot be modified!')
 
     @property
     def resclass_id(self) -> Optional[str]:
         return self._resclass_id
 
     @resclass_id.setter
     def resclass_id(self, value: Optional[str]) -> None:
@@ -119,15 +117,14 @@
             raise BaseError('"con"-parameter must be an instance of Connection')
         if not isinstance(context, Context):
             raise BaseError('"context"-parameter must be an instance of Context')
 
         rdf = context.prefix_from_iri("http://www.w3.org/1999/02/22-rdf-syntax-ns#")
         rdfs = context.prefix_from_iri("http://www.w3.org/2000/01/rdf-schema#")
         owl = context.prefix_from_iri("http://www.w3.org/2002/07/owl#")
-        xsd = context.prefix_from_iri("http://www.w3.org/2001/XMLSchema#")
         knora_api = context.prefix_from_iri("http://api.knora.org/ontology/knora-api/v2#")
         salsah_gui = context.prefix_from_iri("http://api.knora.org/ontology/salsah-gui/v2#")
 
         if jsonld_obj.get("@type") is None or jsonld_obj.get("@type") != owl + ":Restriction":
             raise BaseError("Expected restriction type")
 
         #
@@ -263,61 +260,42 @@
             raise BaseError("Property id required")
         if self._cardinality is None:
             raise BaseError("Cardinality id required")
         jsonobj = self.toJsonObj(last_modification_date, Actions.Update)
         jsondata = json.dumps(jsonobj, indent=4, cls=SetEncoder)
         result = self._con.put(HasProperty.ROUTE, jsondata)
         last_modification_date = DateTimeStamp(result["knora-api:lastModificationDate"])
-        # TODO: self._changed = str()
         return last_modification_date, ResourceClass.fromJsonObj(self._con, self._context, result["@graph"])
 
-    def delete(self, last_modification_date: DateTimeStamp) -> DateTimeStamp:
-        raise BaseError("Cannot remove a single property from a class!")
-        # ToDo: Check with Ben if we could add this feature...
-
     def createDefinitionFileObj(self, context: Context, shortname: str):
         cardinality = {}
         if self._ptype == HasProperty.Ptype.other or self.property_id in [
             "knora-api:isSequenceOf",
             "knora-api:hasSequenceBounds",
             "knora-api:isPartOf",
             "knora-api:seqnum",
         ]:
             cardinality["propname"] = context.reduce_iri(self._property_id, shortname)
             cardinality["cardinality"] = self._cardinality.value
             if self._gui_order is not None:
                 cardinality["gui_order"] = self._gui_order
         return cardinality
 
-    def print(self, offset: int = 0):
-        blank = " "
-        if self._ptype == HasProperty.Ptype.system:
-            print(f"{blank:>{offset}}Has Property (system)")
-        elif self._ptype == HasProperty.Ptype.knora:
-            print(f"{blank:>{offset}}Has Property (knora)")
-        else:
-            print(f"{blank:>{offset}}Has Property (project)")
-        print(f"{blank:>{offset + 2}}Property: {self._property_id}")
-        print(f"{blank:>{offset + 2}}Cardinality: {self._cardinality.value}")
-        if self._ptype == HasProperty.Ptype.other:
-            print(f"{blank:>{offset + 2}}Ontology_id: {self._ontology_id}")
-        print(f"{blank:>{offset + 2}}Resclass: {self._resclass_id}")
-
 
 class ResourceClass(Model):
     """
     This class represents a DSP resource class
 
     Attributes
     ----------
 
     con : Connection
         A Connection instance to a DSP server
 
-    id : str
+    iri : str
         IRI of the ResourceClass [readonly, cannot be modified after creation of instance]
 
     name: str
         The name of the resource class, e.g. "Book", "Person", "Portait". Usually these names start
         with a capital letter
 
     ontology_id: str
@@ -363,19 +341,14 @@
         getPropertery(prop_id: str) -> HasProperty
         returns a HasProperty-instance
 
     addProperty: Add a new property to the resource class
         addProperty(property_id: str, cardinality: Cardinality, last_modification_date: DateTimeStamp)
         -> Optional[DateTimeStamp]
 
-    updateProperty: Updates the cardinality parameters of the given property with the resource class
-        updateProperty(self, property_id: str, cardinality: Cardinality, last_modification_date: DateTimeStamp)
-        -> Optional[DateTimeStamp]
-        Please note that the cardinality usually can only be changed to be *less* restrictive!
-
     create: Create a new resource class on the connected server
 
     update: Update the information of a resource class on the connected server
 
     delete: Mark a resource class as deleted (on the connected server)
 
     createDefinitionFileObj: Create an object suitable for jsonification that conforms the the DSP-TOOLS ontology tools
@@ -383,62 +356,62 @@
     print: Print the content of this class to the console
 
     """
 
     ROUTE: str = "/v2/ontologies/classes"
 
     _context: Context
-    _id: str
+    _iri: str
     _name: str
     _ontology_id: str
     _superclasses: list[str]
     _label: LangString
     _comment: LangString
     _permissions: str
     _has_properties: dict[str, HasProperty]
 
     def __init__(
         self,
         con: Connection,
         context: Context,
-        id: Optional[str] = None,
+        iri: Optional[str] = None,
         name: Optional[str] = None,
         ontology_id: Optional[str] = None,
         superclasses: Optional[Sequence[Union["ResourceClass", str]]] = None,
         label: Optional[Union[LangString, str]] = None,
         comment: Optional[Union[LangString, str]] = None,
         permissions: Optional[str] = None,
         has_properties: Optional[dict[str, HasProperty]] = None,
     ):
         """
         Create an instance of  ResourceClass
 
         :param con:
         :param context:
-        :param id:
+        :param iri:
         :param name:
         :param ontology_id:
         :param superclasses:
         :param label:
         :param comment:
         :param permissions:
         :param has_properties:
         """
         super().__init__(con)
         if not isinstance(con, Connection):
             raise BaseError('"con"-parameter must be an instance of Connection')
         if not isinstance(context, Context):
             raise BaseError('"context"-parameter must be an instance of Context')
         self._context = context
-        self._id = id
+        self._iri = iri
         self._name = name
         if ontology_id is not None:
             self._ontology_id = context.iri_from_prefix(ontology_id)
         if isinstance(superclasses, ResourceClass):
-            self._superclasses = list(map(lambda a: a.id, superclasses))
+            self._superclasses = list(map(lambda a: a.iri, superclasses))
         else:
             self._superclasses = superclasses
         #
         # process label
         #
         if label is not None:
             if isinstance(label, str):
@@ -473,20 +446,20 @@
         return self._name
 
     @name.setter
     def name(self, value: str) -> None:
         raise BaseError('"name" cannot be modified!')
 
     @property
-    def id(self) -> Optional[str]:
-        return self._id
+    def iri(self) -> Optional[str]:
+        return self._iri
 
-    @id.setter
-    def id(self, value: str) -> None:
-        raise BaseError('"id" cannot be modified!')
+    @iri.setter
+    def iri(self, value: str) -> None:
+        raise BaseError('"iri" cannot be modified!')
 
     @property
     def ontology_id(self) -> Optional[str]:
         return self._ontology_id
 
     @ontology_id.setter
     def ontology_id(self, value: str) -> None:
@@ -581,75 +554,45 @@
     ) -> DateTimeStamp:
         if self._has_properties.get(property_id) is None:
             latest_modification_date, resclass = HasProperty(
                 con=self._con,
                 context=self._context,
                 ontology_id=self._ontology_id,
                 property_id=property_id,
-                resclass_id=self.id,
+                resclass_id=self.iri,
                 cardinality=cardinality,
                 gui_order=gui_order,
             ).create(last_modification_date)
             hp = resclass.getProperty(property_id)
-            hp._ontology_id = self._context.iri_from_prefix(self._ontology_id)
-            hp._resclass_id = self._id
+            hp.ontology_id = self._context.iri_from_prefix(self._ontology_id)
+            hp.resclass_id = self._iri
             self._has_properties[hp.property_id] = hp
             return latest_modification_date
         else:
             raise BaseError("Property already has cardinality in this class! " + property_id)
 
-    def updateProperty(
-        self,
-        last_modification_date: DateTimeStamp,
-        property_id: str,
-        cardinality: Optional[Cardinality],
-        gui_order: Optional[int] = None,
-    ) -> Optional[DateTimeStamp]:
-        property_id = self._context.get_prefixed_iri(property_id)
-        if self._has_properties.get(property_id) is not None:
-            has_properties = self._has_properties[property_id]
-            # onto_id = has_properties.ontology_id  # save for later user
-            # rescl_id = has_properties.resclass_id  # save for later user
-            has_properties.ontology_id = self._ontology_id
-            has_properties.resclass_id = self._id
-            if cardinality:
-                has_properties.cardinality = cardinality
-            if gui_order:
-                has_properties.gui_order = gui_order
-            latest_modification_date, resclass = has_properties.update(last_modification_date)
-            hp = resclass.getProperty(property_id)
-            hp.ontology_id = self._ontology_id  # self.__context.iri_from_prefix(onto_id)  # restore value
-            hp.resclass_id = self._id  # rescl_id  # restore value
-            self._has_properties[hp.property_id] = hp
-            return latest_modification_date
-        else:
-            return last_modification_date
-
     @classmethod
     def fromJsonObj(cls, con: Connection, context: Context, json_obj: Any) -> Any:
         if isinstance(json_obj, list):
-            json_obj = json_obj[0]  # TODO: Is it possible to have more than one element in the list??
+            json_obj = json_obj[0]
         if not isinstance(con, Connection):
             raise BaseError('"con"-parameter must be an instance of Connection')
         if not isinstance(context, Context):
             raise BaseError('"context"-parameter must be an instance of Context')
-        rdf = context.prefix_from_iri("http://www.w3.org/1999/02/22-rdf-syntax-ns#")
         rdfs = context.prefix_from_iri("http://www.w3.org/2000/01/rdf-schema#")
         owl = context.prefix_from_iri("http://www.w3.org/2002/07/owl#")
-        xsd = context.prefix_from_iri("http://www.w3.org/2001/XMLSchema#")
         knora_api = context.prefix_from_iri("http://api.knora.org/ontology/knora-api/v2#")
-        salsah_gui = context.prefix_from_iri("http://api.knora.org/ontology/salsah-gui/v2#")
 
         if not (json_obj.get(knora_api + ":isResourceClass") or json_obj.get(knora_api + ":isStandoffClass")):
             raise BaseError("This is not a resource!")
 
         if json_obj.get("@id") is None:
             raise BaseError('Resource class has no "@id"!')
         tmp_id = json_obj.get("@id").split(":")
-        id = context.iri_from_prefix(tmp_id[0]) + "#" + tmp_id[1]
+        iri = context.iri_from_prefix(tmp_id[0]) + "#" + tmp_id[1]
         ontology_id = tmp_id[0]
         name = tmp_id[1]
         superclasses_obj = json_obj.get(rdfs + ":subClassOf")
         if superclasses_obj is not None:
             supercls: list[Any] = list(filter(lambda a: a.get("@id") is not None, superclasses_obj))
             superclasses: list[str] = list(map(lambda a: a["@id"], supercls))
             has_props: list[Any] = list(filter(lambda a: a.get("@type") == (owl + ":Restriction"), superclasses_obj))
@@ -671,15 +614,15 @@
 
         label = LangString.fromJsonLdObj(json_obj.get(rdfs + ":label"))
         comment = LangString.fromJsonLdObj(json_obj.get(rdfs + ":comment"))
         return cls(
             con=con,
             context=context,
             name=name,
-            id=id,
+            iri=iri,
             ontology_id=ontology_id,
             superclasses=superclasses,
             label=label,
             comment=comment,
             has_properties=has_properties,
         )
 
@@ -782,15 +725,15 @@
         if something_changed:
             return last_modification_date, ResourceClass.fromJsonObj(self._con, self._context, result["@graph"])
         else:
             return last_modification_date, self
 
     def delete(self, last_modification_date: DateTimeStamp) -> DateTimeStamp:
         result = self._con.delete(
-            ResourceClass.ROUTE + "/" + quote_plus(self._id) + "?lastModificationDate=" + str(last_modification_date)
+            ResourceClass.ROUTE + "/" + quote_plus(self._iri) + "?lastModificationDate=" + str(last_modification_date)
         )
         return DateTimeStamp(result["knora-api:lastModificationDate"])
 
     def createDefinitionFileObj(self, context: Context, shortname: str, skiplist: list[str]):
         resource = {"name": self._name}
         if self._superclasses:
             if len(self._superclasses) > 1:
@@ -801,42 +744,21 @@
                 superclasses = context.reduce_iri(self._superclasses[0], shortname)
             resource["super"] = superclasses
         resource["labels"] = self._label.createDefinitionFileObj()
         if not self._comment.isEmpty():
             resource["comments"] = self._comment.createDefinitionFileObj()
         if self._has_properties:
             cardinalities = []
-            for pid, hp in self._has_properties.items():
+            for _, hp in self._has_properties.items():
                 if hp.property_id in skiplist:
                     continue
                 if hp.ptype == HasProperty.Ptype.other or hp.property_id in [
                     "knora-api:isSequenceOf",
                     "knora-api:hasSequenceBounds",
                     "knora-api:isPartOf",
                     "knora-api:seqnum",
                 ]:
                     cardinalities.append(hp.createDefinitionFileObj(context, shortname))
             if cardinalities:
                 resource["cardinalities"] = cardinalities
 
         return resource
-
-    def print(self, offset: int = 0):
-        blank = " "
-        print(f"{blank:>{offset}}Resource Class Info")
-        print(f"{blank:>{offset + 2}}Name:            {self._name}")
-        print(f"{blank:>{offset + 2}}Ontology prefix: {self._ontology_id}")
-        print(f"{blank:>{offset + 2}}Superclasses:")
-        if self._superclasses is not None:
-            for sc in self._superclasses:
-                print(f"{blank:>{offset + 4}}{sc}")
-        if self._label is not None:
-            print(f"{blank:>{offset + 2}}Labels:")
-            self._label.print(offset + 4)
-        if self._comment is not None:
-            print(f"{blank:>{offset + 2}}Comments:")
-            self._comment.print(offset + 4)
-        if self._has_properties is not None:
-            print(f"{blank:>{offset + 2}}Has properties:")
-            if self._has_properties is not None:
-                for pid, hp in self._has_properties.items():
-                    hp.print(offset + 4)
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/sipi.py` & `dsp_tools-2.3.4/src/dsp_tools/models/sipi.py`

 * *Files 6% similar despite different names*

```diff
@@ -23,11 +23,15 @@
         Returns:
             API response
         """
         with open(filepath, "rb") as bitstream_file:
             files = {
                 "file": (os.path.basename(filepath), bitstream_file),
             }
-            response = requests.post(self.sipi_server + "/upload?token=" + self.token, files=files)
+            response = requests.post(
+                self.sipi_server + "/upload?token=" + self.token,
+                files=files,
+                timeout=5 * 60,
+            )
         check_for_api_error(response)
         res: dict[Any, Any] = response.json()
         return res
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/user.py` & `dsp_tools-2.3.4/src/dsp_tools/models/user.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,64 +1,55 @@
-from __future__ import annotations
-
-import json
-import os
-import sys
-import urllib.parse
-from typing import Any, Optional, Union
-from urllib.parse import quote_plus
-
-from dsp_tools.models.connection import Connection
-from dsp_tools.models.exceptions import BaseError
-from dsp_tools.models.group import Group
-from dsp_tools.models.helpers import Actions
-from dsp_tools.models.langstring import Languages
-from dsp_tools.models.model import Model
-from dsp_tools.models.project import Project
-
-path = os.path.abspath(os.path.dirname(__file__))
-(head, tail) = os.path.split(path)
-if not head in sys.path:
-    sys.path.insert(0, head)
-if not path in sys.path:
-    sys.path.insert(0, path)
-
 """
 This module implements the handling (CRUD) of DSP users.
 
 CREATE:
     * Instantiate a new object of the class User with all required parameters
     * Call the ``create``-method on the instance to create the new user
 
 READ:
-    * Instantiate a new objects with ``id``(IRI of user) given
+    * Instantiate a new objects with ``iri`` given
     * Call the ``read``-method on the instance
     * Access the information that has been ptovided to the instance
 
 UPDATE:
     * You need an instance of an existing User by reading an instance
     * Change the attributes by assigning the new values
     * Call the ``update```method on the instance
 
 DELETE
-    * Instantiate a new objects with ``id``(IRI of user) given, or use any instance that has the id set
+    * Instantiate a new objects with ``iri`` given, or use any instance that has the iri set
     * Call the ``delete``-method on the instance
 
 In addition there is a static methods ``getAllProjects`` which returns a list of all projects
 """
 
+from __future__ import annotations
+
+import json
+import urllib.parse
+from typing import Any, Optional, Union
+from urllib.parse import quote_plus
+
+from dsp_tools.models.connection import Connection
+from dsp_tools.models.exceptions import BaseError
+from dsp_tools.models.group import Group
+from dsp_tools.models.helpers import Actions
+from dsp_tools.models.langstring import Languages
+from dsp_tools.models.model import Model
+from dsp_tools.models.project import Project
+
 
 class User(Model):
     """
     This class represents a user in DSP.
 
     Attributes
     ----------
 
-    id : str
+    iri : str
         IRI of the user [readonly, cannot be modified after creation of instance]
 
     username : str
         Unique identifier (not an IRI) of the user [read/write]
 
     email : str
         Email of the user [read/write]
@@ -134,15 +125,15 @@
 
     ROUTE: str = "/admin/users"
     IRI: str = ROUTE + "/iri/"
     PROJECT_MEMBERSHIPS: str = "/project-memberships/"
     PROJECT_ADMIN_MEMBERSHIPS: str = "/project-admin-memberships/"
     GROUP_MEMBERSHIPS: str = "/group-memberships/"
 
-    _id: str
+    _iri: str
     _username: str
     _email: str
     _givenName: str
     _familyName: str
     _password: str
     _lang: Languages
     _status: bool
@@ -154,15 +145,15 @@
     _add_to_group: set[str]
     _rm_from_group: set[str]
     _change_admin: dict[str, bool]
 
     def __init__(
         self,
         con: Connection,
-        id: Optional[str] = None,
+        iri: Optional[str] = None,
         username: Optional[str] = None,
         email: Optional[str] = None,
         givenName: Optional[str] = None,
         familyName: Optional[str] = None,
         password: Optional[str] = None,
         lang: Optional[Union[str, Languages]] = None,
         status: Optional[bool] = None,
@@ -172,28 +163,28 @@
     ):
         """
         Constructor for User
 
         The constructor is user internally or externally, when a new user should be created in DSP.
 
         :param con: Connection instance [required]
-        :param id: IRI of the user [required for CREATE, READ]
+        :param iri: IRI of the user [required for CREATE, READ]
         :param username: Username [required for CREATE]
         :param email: Email address [required for CREATE]
         :param givenName: Given name (firstname) of user [required for CREATE]
         :param familyName: Family name (lastname) of user [required for CREATE]
         :param password: Password [required for CREATE]
         :param lang: Preferred language of the user [optional]
         :param status: Status (active = True, inactive/deleted = False) [optional]
         :param sysadmin: User has system administration privileges [optional]
         :param in_projects: Dict with project-IRI as key, boolean(True=project admin) as value [optional]
         :param in_groups: Set with group-IRI's the user should belong to [optional]
         """
         super().__init__(con)
-        self._id = str(id) if id is not None else None
+        self._iri = iri
         self._username = str(username) if username is not None else None
         self._email = str(email) if email is not None else None
         self._givenName = str(givenName) if givenName is not None else None
         self._familyName = str(familyName) if familyName is not None else None
         self._password = str(password) if password is not None else None
         if lang is not None:
             if isinstance(lang, Languages):
@@ -221,20 +212,20 @@
         self._add_to_project = {}
         self._rm_from_project = {}
         self._change_admin = {}
         self._add_to_group = set()
         self._rm_from_group = set()
 
     @property
-    def id(self) -> Optional[str]:
-        return self._id
+    def iri(self) -> Optional[str]:
+        return self._iri
 
-    @id.setter
-    def id(self, value: str) -> None:
-        raise BaseError("User id cannot be modified!")
+    @iri.setter
+    def iri(self, value: str) -> None:
+        raise BaseError("User iri cannot be modified!")
 
     @property
     def username(self) -> Optional[str]:
         return self._username
 
     @username.setter
     def username(self, value: Optional[str]):
@@ -435,36 +426,29 @@
             self._change_admin[value] = False
             self._changed.add("in_projects")
         elif value in self._add_to_project:
             self._add_to_project[value] = False
         else:
             raise BaseError("User is not member of project!")
 
-    @property
-    def changed(self) -> set[str]:
-        return self._changed
-
-    def has_changed(self, name: str):
-        return name in self._changed
-
     @classmethod
     def fromJsonObj(cls, con: Connection, json_obj: Any) -> User:
         """
         Internal method! Should not be used directly!
 
         This method is used to create a User instance from the JSON data returned by DSP
 
         :param con: Connection instance
         :param json_obj: JSON data returned by DSP as python3 object
         :return: User instance
         """
 
-        id = json_obj.get("id")
-        if id is None:
-            raise BaseError('User "id" is missing in JSON from DSP')
+        iri = json_obj.get("id")
+        if iri is None:
+            raise BaseError('User "iri" is missing in JSON from DSP')
         email = json_obj.get("email")
         if email is None:
             raise BaseError('User "email" is missing in JSON from DSP')
         username = json_obj.get("username")
         if username is None:
             raise BaseError('User "username" is missing in JSON from DSP')
         familyName = json_obj.get("familyName")
@@ -489,15 +473,15 @@
                                 in_projects[project_iri] = False
                         elif group == Group.PROJECT_ADMIN_GROUP:
                             in_projects[project_iri] = True
                         else:
                             in_groups.add(group)
         return cls(
             con=con,
-            id=id,
+            iri=iri,
             username=username,
             email=email,
             givenName=givenName,
             familyName=familyName,
             lang=lang,
             status=status,
             sysadmin=sysadmin,
@@ -564,108 +548,100 @@
 
         :return: JSON-object from DSP
         """
 
         jsonobj = self.toJsonObj(Actions.Create)
         jsondata = json.dumps(jsonobj)
         result = self._con.post(User.ROUTE, jsondata)
-        id = result["user"]["id"]
+        iri = result["user"]["id"]
         if self._in_projects is not None:
             for project in self._in_projects:
-                result = self._con.post(User.IRI + quote_plus(id) + User.PROJECT_MEMBERSHIPS + quote_plus(project))
+                result = self._con.post(User.IRI + quote_plus(iri) + User.PROJECT_MEMBERSHIPS + quote_plus(project))
                 if self._in_projects[project]:
                     result = self._con.post(
-                        User.IRI + quote_plus(id) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(project)
+                        User.IRI + quote_plus(iri) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(project)
                     )
         if self._in_groups is not None:
             for group in self._in_groups:
-                result = self._con.post(User.IRI + quote_plus(id) + User.GROUP_MEMBERSHIPS + quote_plus(group))
+                result = self._con.post(User.IRI + quote_plus(iri) + User.GROUP_MEMBERSHIPS + quote_plus(group))
         return User.fromJsonObj(self._con, result["user"])
 
     def read(self) -> Any:
         """
-        Read the user information from DSP. The User object must have a valid id or email!
+        Read the user information from DSP. The User object must have a valid iri or email!
 
         :return: JSON-object from DSP
         """
-        if self._id is not None:
-            result = self._con.get(User.IRI + quote_plus(self._id))
+        if self._iri is not None:
+            result = self._con.get(User.IRI + quote_plus(self._iri))
         elif self._email is not None:
             result = self._con.get(User.ROUTE + "/email/" + quote_plus(self._email))
         elif self._username is not None:
             result = self._con.get(User.ROUTE + "/username/" + quote_plus(self._username))
         else:
-            raise BaseError("Either user-id or email is required!")
+            raise BaseError("Either user-iri or email is required!")
         return User.fromJsonObj(self._con, result["user"])
 
     def update(self, requesterPassword: Optional[str] = None) -> Any:
         """
         Udate the user info in DSP with the modified data in this user instance
 
         :param requesterPassword: Old password if a user wants to change it's own password
         :return: JSON-object from DSP
         """
 
         jsonobj = self.toJsonObj(Actions.Update)
         if jsonobj:
             jsondata = json.dumps(jsonobj)
-            result = self._con.put(User.IRI + quote_plus(self.id) + "/BasicUserInformation", jsondata)
+            self._con.put(User.IRI + quote_plus(self.iri) + "/BasicUserInformation", jsondata)
         if "status" in self._changed:
             jsonobj = {"status": self._status}
             jsondata = json.dumps(jsonobj)
-            result = self._con.put(User.IRI + quote_plus(self.id) + "/Status", jsondata)
+            self._con.put(User.IRI + quote_plus(self.iri) + "/Status", jsondata)
         if "password" in self._changed:
             if requesterPassword is None:
                 raise BaseError("Requester's password is missing!")
             jsonobj = {"requesterPassword": requesterPassword, "newPassword": self._password}
             jsondata = json.dumps(jsonobj)
-            result = self._con.put(User.IRI + quote_plus(self.id) + "/Password", jsondata)
+            self._con.put(User.IRI + quote_plus(self.iri) + "/Password", jsondata)
         if "sysadmin" in self._changed:
             jsonobj = {"systemAdmin": self._sysadmin}
             jsondata = json.dumps(jsonobj)
-            result = self._con.put(User.IRI + quote_plus(self.id) + "/SystemAdmin", jsondata)
+            self._con.put(User.IRI + quote_plus(self.iri) + "/SystemAdmin", jsondata)
         for p in self._add_to_project.items():
-            result = self._con.post(User.IRI + quote_plus(self._id) + User.PROJECT_MEMBERSHIPS + quote_plus(p[0]))
+            self._con.post(User.IRI + quote_plus(self._iri) + User.PROJECT_MEMBERSHIPS + quote_plus(p[0]))
             if p[1]:
-                result = self._con.post(
-                    User.IRI + quote_plus(self._id) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(p[0])
-                )
+                self._con.post(User.IRI + quote_plus(self._iri) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(p[0]))
 
         for p in self._rm_from_project:
             if self._in_projects.get(p) is not None and self._in_projects[p]:
-                result = self._con.delete(
-                    User.IRI + quote_plus(self._id) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(p)
-                )
-            result = self._con.delete(User.IRI + quote_plus(self._id) + User.PROJECT_MEMBERSHIPS + quote_plus(p))
+                self._con.delete(User.IRI + quote_plus(self._iri) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(p))
+            self._con.delete(User.IRI + quote_plus(self._iri) + User.PROJECT_MEMBERSHIPS + quote_plus(p))
 
         for p in self._change_admin.items():
             if not p[0] in self._in_projects:
                 raise BaseError("user must be member of project!")
             if p[1]:
-                result = self._con.post(
-                    User.IRI + quote_plus(self._id) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(p[0])
-                )
+                self._con.post(User.IRI + quote_plus(self._iri) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(p[0]))
             else:
-                result = self._con.delete(
-                    User.IRI + quote_plus(self._id) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(p[0])
-                )
+                self._con.delete(User.IRI + quote_plus(self._iri) + User.PROJECT_ADMIN_MEMBERSHIPS + quote_plus(p[0]))
 
         for p in self._add_to_group:
-            result = self._con.post(User.IRI + quote_plus(self._id) + User.GROUP_MEMBERSHIPS + quote_plus(p))
+            self._con.post(User.IRI + quote_plus(self._iri) + User.GROUP_MEMBERSHIPS + quote_plus(p))
         for p in self._rm_from_group:
-            result = self._con.delete(User.IRI + quote_plus(self._id) + User.GROUP_MEMBERSHIPS + quote_plus(p))
-        user = User(con=self._con, id=self._id).read()
+            self._con.delete(User.IRI + quote_plus(self._iri) + User.GROUP_MEMBERSHIPS + quote_plus(p))
+        user = User(con=self._con, iri=self._iri).read()
         return user
 
     def delete(self):
         """
         Delete the user in nore (NOT YET IMPLEMENTED)
         :return: None
         """
-        result = self._con.delete(User.IRI + quote_plus(self._id))
+        result = self._con.delete(User.IRI + quote_plus(self._iri))
         return User.fromJsonObj(self._con, result["user"])
 
     @staticmethod
     def getAllUsers(con: Connection) -> list[Any]:
         """
         Get a list of all users (static method)
 
@@ -723,31 +699,7 @@
             if proj == proj_iri:
                 if is_admin:
                     user["projects"].append(f"{proj_shortname}:admin")
                 else:
                     user["projects"].append(f"{proj_shortname}:member")
         user["status"] = self.status
         return user
-
-    def print(self) -> None:
-        """
-        Prin user info to stdout
-
-        :return: None
-        """
-
-        print("User info:")
-        print("  Id:          {}".format(self._id))
-        print("  Username:    {}".format(self._username))
-        print("  Family name: {}".format(self._familyName))
-        print("  Given name:  {}".format(self._givenName))
-        print("  Language:    {}".format(self._lang.value))
-        print("  Status:      {}".format(self._status))
-        print("  Sysadmin:    {}".format(self._sysadmin))
-        print("  In projects:")
-        if self._in_projects is not None:
-            for p in self._in_projects:
-                print("    {} : project admin: {}".format(p, self._in_projects[p]))
-        print("   In groups:")
-        if self._in_groups is not None:
-            for g in self._in_groups:
-                print("    {}".format(g))
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/value.py` & `dsp_tools-2.3.4/src/dsp_tools/models/value.py`

 * *Files 0% similar despite different names*

```diff
@@ -118,15 +118,15 @@
             elif tmp.get("@type") == "xsd:anyURI":
                 result = str(tmp["@value"])
             elif tmp.get("@type") == "xsd:dateTimeStamp":
                 result = str(tmp["@value"])
             elif tmp.get("@id"):
                 result = tmp["@id"]
             else:
-                raise BaseError('Invalid data type in JSON-LD: "{}"!'.format(tmp["@type"]))
+                raise BaseError(f'Invalid data type in JSON-LD: "{tmp["@type"]}')
             return result
         except KeyError as kerr:
             raise BaseError("Error in JSON-LD returned!") from kerr
 
     @staticmethod
     def getFromJsonLd(jsonld_obj) -> dict[str, Any]:
         return {
@@ -275,19 +275,20 @@
         ark_url: Optional[str] = None,
         vark_url: Optional[str] = None,
     ):
         #
         # A DSP date value
         #
         m = re.match(
-            r"^(GREGORIAN:|JULIAN:)?(CE:|BCE:)?(\d{4})(-\d{1,2})?(-\d{1,2})?((:CE|:BCE)?(:\d{4})(-\d{1,2})?(-\d{1,2})?)?$",
+            r"^(GREGORIAN:|JULIAN:)?(CE:|BCE:)?(\d{4})(-\d{1,2})?(-\d{1,2})?"
+            r"((:CE|:BCE)?(:\d{4})(-\d{1,2})?(-\d{1,2})?)?$",
             str(value),
         )
         if not m:
-            raise BaseError('Invalid date format: "{}"!'.format(str(value)))
+            raise BaseError(f'Invalid date format: "{value}"!')
         dp = m.groups()
         self._calendar = "GREGORIAN" if dp[0] is None else dp[0].strip("-: ")
         self._e1 = "CE" if dp[1] is None else dp[1].strip("-: ")
         self._y1 = None if dp[2] is None else int(dp[2].strip("-: "))
         self._m1 = None if dp[3] is None else int(dp[3].strip("-: "))
         self._d1 = None if dp[4] is None else int(dp[4].strip("-: "))
         self._e2 = "CE" if dp[6] is None else dp[6].strip("-: ")
@@ -631,15 +632,15 @@
         comment: Optional[LangString] = None,
         permissions: Optional[Permissions] = None,
         upermission: Optional[PermissionValue] = None,
         iri: Optional[str] = None,
         ark_url: Optional[str] = None,
         vark_url: Optional[str] = None,
     ):
-        if type(value) is bool:
+        if isinstance(value, bool):
             self._value = value
         else:
             if value == 1 or value.upper() == "TRUE" or value == "1":
                 self._value = True
             elif value == 0 or value.upper() == "FALSE" or value == "0":
                 self._value = False
             else:
@@ -689,15 +690,15 @@
         vark_url: Optional[str] = None,
     ):
         # URI = scheme ":" ["//" host [":" port]] path ["?" query] ["#" fragment]
         scheme = r"(?<scheme>[a-z][a-z0-9+.\-]*)"
         host = r"(?<host>[\w_.\-~:\[\]]+)"
         port = r"(?<port>:\d{0,6})"
         path = r"(?<path>/[\w_.\-~:%()]*)"
-        query = r"(?<query>\?[\w_.\-%=*&]+)"
+        query = r"(?<query>\?[\w_.\-:%=*&]+)"
         fragment = r"(?<fragment>#[\w_.\-~:/]*)"
         m = regex.match(rf"{scheme}:(//{host}{port}?){path}*{query}*{fragment}?", str(value), flags=regex.UNICODE)
         if m:
             self._value = str(value)
         else:
             raise BaseError('Invalid IRI/URI! "' + value + '"')
         super().__init__(
@@ -729,18 +730,14 @@
     def __str__(self) -> str:
         return self._value + " " + super().__str__()
 
 
 class TimeValue(Value):
     _value: str
 
-    @property
-    def value(self) -> str:
-        return self._value
-
     def __init__(
         self,
         value: str,
         comment: Optional[LangString] = None,
         permissions: Optional[Permissions] = None,
         upermission: Optional[PermissionValue] = None,
         iri: Optional[str] = None,
@@ -891,28 +888,24 @@
             node_iri = None
             for list_item in lists:
                 if list_item.name == listname:
                     node_iri = find_listnode(list_item.children, nodename)
             if node_iri is not None:
                 self._value = node_iri
             else:
-                raise BaseError('Listnode "{}" not found'.format(value))
+                raise BaseError(f'Listnode "{value}" not found')
         super().__init__(
             iri=iri,
             comment=comment,
             permissions=permissions,
             upermission=upermission,
             ark_url=ark_url,
             vark_url=vark_url,
         )
 
-    def print(self, offset: int = 0):
-        blank = " "
-        print(f"{blank:>{offset}}{self._value}")
-
     @property
     def value(self) -> str:
         return self._value
 
     @classmethod
     def fromJsonLdObj(cls, jsonld_obj: Any) -> dict[str, Any]:
         tmp = Value.getFromJsonLd(jsonld_obj)
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/xmlallow.py` & `dsp_tools-2.3.4/src/dsp_tools/models/xmlallow.py`

 * *Files 15% similar despite different names*

```diff
@@ -26,32 +26,28 @@
         if len(tmp) > 1:
             if tmp[0]:
                 if tmp[0] == "knora-admin" and tmp[1] in sysgroups:
                     self._group = node.attrib["group"]
                 else:
                     self._group = project_context.group_map.get(node.attrib["group"])
                     if self._group is None:
-                        raise XmlError('Group "{}" is not known: Cannot find project!'.format(node.attrib["group"]))
+                        raise XmlError(f'Group "{node.attrib["group"]}" is not known: Cannot find project!')
             else:
                 if project_context.project_name is None:
                     raise XmlError("Project shortcode has not been set in ProjectContext")
                 self._group = project_context.project_name + ":" + tmp[1]
         else:
             if tmp[0] in sysgroups:
                 self._group = "knora-admin:" + node.attrib["group"]
             else:
-                raise XmlError('Group "{}" is not known: '.format(node.attrib["group"]))
+                raise XmlError(f'Group "{node.attrib["group"]}" is not known: ')
         self._permission = node.text
 
     @property
     def group(self) -> str:
         """The group specified in the allow element"""
         return self._group
 
     @property
     def permission(self) -> str:
         """The reference to a set of permissions"""
         return self._permission
-
-    def print(self) -> None:
-        """Prints the attributes of the XmlAllow instance"""
-        print("  group=", self._group, " permission=", self._permission)
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/xmlbitstream.py` & `dsp_tools-2.3.4/src/dsp_tools/models/xmlbitstream.py`

 * *Files 6% similar despite different names*

```diff
@@ -16,11 +16,7 @@
         """The file path of the bitstream object"""
         return self._value
 
     @property
     def permissions(self) -> str:
         """Reference to the set of permissions for the bitstream object"""
         return self._permissions
-
-    def print(self) -> None:
-        """Prints the bitstream object and its attributes."""
-        print("   Bitstream file path: " + str(self._value))
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/xmlpermission.py` & `dsp_tools-2.3.4/src/dsp_tools/models/xmlpermission.py`

 * *Files 17% similar despite different names*

```diff
@@ -25,30 +25,19 @@
             self._allows.append(XmlAllow(allow_node, project_context))
 
     @property
     def id(self) -> str:
         """The id of the permission set, p.ex. res-default"""
         return self._id
 
-    @property
-    def allows(self) -> list[XmlAllow]:
-        """List of XmlAllow elements defining permissions for specific groups"""
-        return self._allows
-
     def get_permission_instance(self) -> Permissions:
         """Returns a list of allow elements of this permission instance"""
         permissions = Permissions()
         for allow in self._allows:
             permissions.add(allow.permission, allow.group)
         return permissions
 
     def __str__(self) -> str:
         allow_str: list[str] = []
         for allow in self._allows:
-            allow_str.append("{} {}".format(allow.permission, allow.group))
+            allow_str.append(f"{allow.permission} {allow.group}")
         return "|".join(allow_str)
-
-    def print(self) -> None:
-        """Prints the permission set"""
-        print("Permission: ", self._id)
-        for a in self._allows:
-            a.print()
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/xmlproperty.py` & `dsp_tools-2.3.4/src/dsp_tools/models/xmlproperty.py`

 * *Files 6% similar despite different names*

```diff
@@ -53,13 +53,7 @@
         """The value type of the property"""
         return self._valtype
 
     @property
     def values(self) -> list[XMLValue]:
         """List of values of this property"""
         return self._values
-
-    def print(self) -> None:
-        """Prints the property."""
-        print("  Property: {} Type: {}".format(self._name, self._valtype))
-        for value in self._values:
-            value.print()
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/models/xmlresource.py` & `dsp_tools-2.3.4/src/dsp_tools/models/xmlresource.py`

 * *Files 2% similar despite different names*

```diff
@@ -108,22 +108,14 @@
     def properties(self) -> list[XMLProperty]:
         return self._properties
 
     @properties.setter
     def properties(self, new_properties: list[XMLProperty]) -> None:
         self._properties = new_properties
 
-    def print(self) -> None:
-        """Prints the resource and its attributes."""
-        print(f"Resource: id={self._id}, restype: {self._restype}, label: {self._label}")
-        if self._bitstream:
-            print("  Bitstream: " + self._bitstream.value)
-        for prop in self._properties:
-            prop.print()
-
     def get_props_with_links(self) -> list[XMLProperty]:
         """
         Get a list of all XMLProperties that have an outgoing link to another resource, be it a resptr-prop link
         or a standoff link in a text.
         """
         link_properties: list[XMLProperty] = []
         for prop in self._properties:
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/resources/0100-template-repo/template.json` & `dsp_tools-2.3.4/src/dsp_tools/resources/0100-template-repo/template.json`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/resources/0100-template-repo/template.xml` & `dsp_tools-2.3.4/src/dsp_tools/resources/0100-template-repo/template.xml`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/resources/schema/data.xsd` & `dsp_tools-2.3.4/src/dsp_tools/resources/schema/data.xsd`

 * *Files 0% similar despite different names*

#### Comparing `dsp_tools-2.3.3/src/dsp_tools/resources/schema/data.xsd` & `dsp_tools-2.3.4/src/dsp_tools/resources/schema/data.xsd`

```diff
@@ -29,15 +29,15 @@
     <xs:restriction base="xs:token">
       <xs:pattern value="#([0-9a-fA-F]{3}){1,2}"/>
     </xs:restriction>
   </xs:simpleType>
   <!-- data type for knora uri -->
   <xs:simpleType name="knorauri_type">
     <xs:restriction base="xs:string">
-      <xs:pattern value="([a-z][a-z0-9+.\-]*):(//([\w_.\-~:\[\]]+)(:\d{0,6})?)(/[\w_.\-~:%()]*)*(\?[\w_.\-%=*&amp;]+)*(#[\w_.\-~:/]*)?"/>
+      <xs:pattern value="([a-z][a-z0-9+.\-]*):(//([\w_.\-~:\[\]]+)(:\d{0,6})?)(/[\w_.\-~:%()]*)*(\?[\w_.\-:%=*&amp;]+)*(#[\w_.\-~:/]*)?"/>
     </xs:restriction>
   </xs:simpleType>
   <!-- data type for knora interval -->
   <xs:simpleType name="knorainterval_type">
     <xs:restriction base="xs:token">
       <xs:pattern value="([+-]?([0-9]+([.][0-9]*)?|[.][0-9]+)):([+-]?([0-9]+([.][0-9]*)?|[.][0-9]+))"/>
     </xs:restriction>
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/resources/schema/lists-only.json` & `dsp_tools-2.3.4/src/dsp_tools/resources/schema/lists-only.json`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/resources/schema/project.json` & `dsp_tools-2.3.4/src/dsp_tools/resources/schema/project.json`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/resources/schema/properties-only.json` & `dsp_tools-2.3.4/src/dsp_tools/resources/schema/properties-only.json`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/resources/schema/resources-only.json` & `dsp_tools-2.3.4/src/dsp_tools/resources/schema/resources-only.json`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/resources/start-stack/docker-compose.yml` & `dsp_tools-2.3.4/src/dsp_tools/resources/start-stack/docker-compose.yml`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 ---
 
 version: '3.7'
 
 services:
 
   app:
-    image: daschswiss/dsp-app:v10.20.3  # on the verge of every deployment (fortnightly), update this from the "app" value of
+    image: daschswiss/dsp-app:v10.21.0  # on the verge of every deployment (fortnightly), update this from the "app" value of
                                         # https://github.com/dasch-swiss/ops-deploy/blob/main/roles/dsp-deploy/files/RELEASE.json
     ports:
       - "4200:4200"
     networks:
       - knora-net
 
   db:
@@ -21,15 +21,15 @@
       - knora-net
     environment:
       - TZ=Europe/Zurich
       - ADMIN_PASSWORD=test
       - JVM_ARGS=-Xmx3G
 
   sipi:
-    image: daschswiss/knora-sipi:29.0.0  # on the verge of every deployment (fortnightly), take the same tag as DSP-API
+    image: daschswiss/knora-sipi:29.0.1  # on the verge of every deployment (fortnightly), take the same tag as DSP-API
     ports:
       - "1024:1024"
     volumes:
       - .:/docker
     networks:
       - knora-net
     environment:
@@ -40,15 +40,15 @@
       - SIPI_WEBAPI_HOSTNAME=api
       - SIPI_WEBAPI_PORT=3333
       - KNORA_WEBAPI_KNORA_API_EXTERNAL_HOST=0.0.0.0
       - KNORA_WEBAPI_KNORA_API_EXTERNAL_PORT=3333
     command: --config=/docker/sipi.docker-config.lua
 
   api:
-    image: daschswiss/knora-api:29.0.0  # on the verge of every deployment (fortnightly), update this from the "api" value of
+    image: daschswiss/knora-api:29.0.1  # on the verge of every deployment (fortnightly), update this from the "api" value of
                                         # https://github.com/dasch-swiss/ops-deploy/blob/main/roles/dsp-deploy/files/RELEASE.json
     depends_on:
       - sipi
       - db
     ports:
       - "3333:3333"
     networks:
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/excel_to_json_lists.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/excel_to_json_lists.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/excel_to_json_project.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/excel_to_json_project.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/excel_to_json_properties.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/excel_to_json_properties.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/excel_to_json_resources.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/excel_to_json_resources.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/generate_templates.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/generate_templates.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/id_to_iri.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/id_to_iri.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/logging.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/logging.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/project_create.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/project_create.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 """This module handles the ontology creation, update and upload to a DSP server. This includes the creation and update
 of the project, the creation of groups, users, lists, resource classes, properties and cardinalities."""
 import re
 from pathlib import Path
-from typing import Any, Union, cast
+from typing import Any, Optional, Union, cast
 
 from dsp_tools.models.connection import Connection
 from dsp_tools.models.exceptions import BaseError, UserError
 from dsp_tools.models.group import Group
 from dsp_tools.models.helpers import Cardinality, Context, DateTimeStamp
 from dsp_tools.models.langstring import LangString
 from dsp_tools.models.ontology import Ontology
@@ -149,15 +149,15 @@
         for all groups that have successfully been created (or already exist).
         The dict is empty if no group was created.
     """
     overall_success = True
     current_project_groups: dict[str, Group] = {}
     try:
         remote_groups: list[Group] = try_network_action(
-            lambda: Group.getAllGroupsForProject(con=con, proj_iri=project.id)  # type: ignore
+            lambda: Group.getAllGroupsForProject(con=con, proj_iri=project.iri)  # type: ignore
         )
     except BaseError:
         err_msg = (
             "Unable to check if group names are already existing on DSP server, because it is "
             "not possible to retrieve the remote groups from the DSP server."
         )
         print(f"WARNING: {err_msg}")
@@ -262,15 +262,15 @@
                     f"User '{username}' is referring to the group {full_group_name} that "
                     f"exists on the DSP server, but no groups could be retrieved from the DSP server."
                 )
                 print(f"\tWARNING: {err_msg}")
                 logger.warning(err_msg, exc_info=True)
                 success = False
                 continue
-            existing_group = [g for g in remote_groups if g.project == current_project.id and g.name == group_name]
+            existing_group = [g for g in remote_groups if g.project == current_project.iri and g.name == group_name]
             if not existing_group:
                 print(f"\tWARNING: {inexisting_group_msg}")
                 success = False
                 continue
             group = existing_group[0]
 
         if not group.iri:
@@ -334,15 +334,15 @@
                 print(
                     f"\tWARNING: Provided project '{full_project_name}' for user '{username}' is not valid. Skipping..."
                 )
                 success = False
                 continue
             in_project = in_project_list[0]
 
-        project_info[in_project.id] = bool(project_role == "admin")  # type: ignore
+        project_info[in_project.iri] = bool(project_role == "admin")  # type: ignore
         if verbose:
             print(f"\tAdded user '{username}' as {project_role} to project '{in_project.shortname}'.")
 
     return project_info, success
 
 
 def _create_users(
@@ -496,14 +496,78 @@
             if all(parent_classes_ok):
                 sorted_prop_classes.append(prop)
                 ok_propclass_names.append(prop_name)
                 prop_classes_to_sort.remove(prop)
     return sorted_prop_classes
 
 
+def _create_ontology(
+    ontology_definition: dict[str, Any],
+    project_ontologies: list[Ontology],
+    con: Connection,
+    project_remote: Project,
+    context: Context,
+    verbose: bool,
+) -> Optional[Ontology]:
+    """
+    Create an ontology on the DSP server,
+    and add the prefixes defined in the JSON file to its context.
+    If the ontology already exists on the DSP server, it is skipped.
+
+    Args:
+        ontology_definition: one ontology from the "ontologies" section of a parsed JSON project file
+        project_ontologies: ontologies existing on the DSP server
+        con: Connection to the DSP server
+        project_remote: representation of the project on the DSP server
+        context: prefixes and the ontology IRIs they stand for
+        verbose: verbose switch
+
+    Raises:
+        UserError: if the ontology cannot be created on the DSP server
+
+    Returns:
+        representation of the created ontology on the DSP server, or None if it already existed
+    """
+    # skip if it already exists on the DSP server
+    if ontology_definition["name"] in [onto.name for onto in project_ontologies]:
+        print(f"\tWARNING: Ontology '{ontology_definition['name']}' already exists on the DSP server. Skipping...")
+        return None
+
+    print(f"Create ontology '{ontology_definition['name']}'...")
+    ontology_local = Ontology(
+        con=con,
+        project=project_remote,
+        label=ontology_definition["label"],
+        name=ontology_definition["name"],
+        comment=ontology_definition.get("comment"),
+    )
+    try:
+        ontology_remote: Ontology = try_network_action(ontology_local.create)
+    except BaseError:
+        # if ontology cannot be created, let the error escalate
+        logger.error(f"ERROR while trying to create ontology '{ontology_definition['name']}'.", exc_info=True)
+        raise UserError(f"ERROR while trying to create ontology '{ontology_definition['name']}'.") from None
+
+    if verbose:
+        print(f"\tCreated ontology '{ontology_definition['name']}'.")
+
+    context.add_context(
+        ontology_remote.name,
+        ontology_remote.iri + ("#" if not ontology_remote.iri.endswith("#") else ""),
+    )
+
+    # add the prefixes defined in the JSON file
+    for onto_prefix, onto_info in context:
+        if onto_info and str(onto_prefix) not in ontology_remote.context:
+            onto_iri = onto_info.iri + ("#" if onto_info.hashtag else "")
+            ontology_remote.context.add_context(prefix=str(onto_prefix), iri=onto_iri)
+
+    return ontology_remote
+
+
 def _create_ontologies(
     con: Connection,
     context: Context,
     knora_api_prefix: str,
     list_root_nodes: dict[str, Any],
     project_definition: dict[str, Any],
     project_remote: Project,
@@ -532,63 +596,42 @@
     """
 
     overall_success = True
 
     print("Create ontologies...")
     try:
         project_ontologies: list[Ontology] = try_network_action(
-            lambda: Ontology.getProjectOntologies(con=con, project_id=project_remote.id)  # type: ignore
+            lambda: Ontology.getProjectOntologies(con=con, project_id=project_remote.iri)  # type: ignore
         )
     except BaseError:
         err_msg = "Unable to retrieve remote ontologies. Cannot check if your ontology already exists."
         print("WARNING: {err_msg}")
         logger.warning(err_msg, exc_info=True)
         project_ontologies = []
+
     for ontology_definition in project_definition.get("project", {}).get("ontologies", {}):
         ontology_definition = cast(dict[str, Any], ontology_definition)
-        if ontology_definition["name"] in [onto.name for onto in project_ontologies]:
-            print(f"\tWARNING: Ontology '{ontology_definition['name']}' already exists on the DSP server. Skipping...")
-            overall_success = False
-            continue
-
-        # create the ontology
-        print(f"Create ontology '{ontology_definition['name']}'...")
-        ontology_local = Ontology(
+        ontology_remote = _create_ontology(
+            ontology_definition=ontology_definition,
+            project_ontologies=project_ontologies,
             con=con,
-            project=project_remote,
-            label=ontology_definition["label"],
-            name=ontology_definition["name"],
-            comment=ontology_definition.get("comment"),
-        )
-        # if ontology cannot be created, let the error escalate
-        try:
-            ontology_remote: Ontology = try_network_action(ontology_local.create)
-        except BaseError:
-            logger.error(f"ERROR while trying to create ontology '{ontology_definition['name']}'.", exc_info=True)
-            raise UserError(f"ERROR while trying to create ontology '{ontology_definition['name']}'.") from None
-        context.add_context(
-            ontology_remote.name,
-            ontology_remote.iri + ("#" if not ontology_remote.iri.endswith("#") else ""),
+            project_remote=project_remote,
+            context=context,
+            verbose=verbose,
         )
-        last_modification_date = ontology_remote.lastModificationDate
-        if verbose:
-            print(f"\tCreated ontology '{ontology_definition['name']}'.")
-
-        # add the prefixes defined in the JSON file
-        for onto_prefix, onto_info in context:
-            if onto_info and str(onto_prefix) not in ontology_remote.context:
-                onto_iri = onto_info.iri + ("#" if onto_info.hashtag else "")
-                ontology_remote.context.add_context(prefix=str(onto_prefix), iri=onto_iri)
+        if not ontology_remote:
+            overall_success = False
+            continue
 
         # add the empty resource classes to the remote ontology
         last_modification_date, remote_res_classes, success = _add_resource_classes_to_remote_ontology(
             ontology_definition=ontology_definition,
             ontology_remote=ontology_remote,
             con=con,
-            last_modification_date=last_modification_date,
+            last_modification_date=ontology_remote.lastModificationDate,
             verbose=verbose,
         )
         if not success:
             overall_success = False
 
         # add the property classes to the remote ontology
         last_modification_date, success = _add_property_classes_to_remote_ontology(
@@ -662,15 +705,15 @@
             comment=LangString(res_class.get("comments")) if res_class.get("comments") else None,
         )
         try:
             last_modification_date, res_class_remote = try_network_action(
                 res_class_local.create, last_modification_date
             )
             res_class_remote = cast(ResourceClass, res_class_remote)
-            new_res_classes[str(res_class_remote.id)] = res_class_remote
+            new_res_classes[str(res_class_remote.iri)] = res_class_remote
             ontology_remote.lastModificationDate = last_modification_date
             if verbose:
                 print(f"\tCreated resource class '{res_class['name']}'")
         except BaseError:
             print(f"WARNING: Unable to create resource class '{res_class['name']}'.")
             logger.warning(f"Unable to create resource class '{res_class['name']}'.", exc_info=True)
             overall_success = False
@@ -744,16 +787,16 @@
         prop_class_local = PropertyClass(
             con=con,
             context=ontology_remote.context,
             label=LangString(prop_class.get("labels")),
             name=prop_class["name"],
             ontology_id=ontology_remote.iri,
             superproperties=super_props,
-            object=prop_object,
-            subject=prop_class.get("subject"),
+            rdf_object=prop_object,
+            rdf_subject=prop_class.get("subject"),
             gui_element="salsah-gui:" + prop_class["gui_element"],
             gui_attributes=gui_attributes,
             comment=LangString(prop_class["comments"]) if prop_class.get("comments") else None,
         )
         try:
             last_modification_date, _ = try_network_action(prop_class_local.create, last_modification_date)
             ontology_remote.lastModificationDate = last_modification_date
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/project_create_lists.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/project_create_lists.py`

 * *Files 0% similar despite different names*

```diff
@@ -89,27 +89,27 @@
     """
 
     overall_success = True
 
     # retrieve existing lists
     try:
         existing_lists: list[ListNode] = try_network_action(
-            lambda: ListNode.getAllLists(con=con, project_iri=project_remote.id)
+            lambda: ListNode.getAllLists(con=con, project_iri=project_remote.iri)
         )
     except BaseError:
         err_msg = "Unable to retrieve existing lists on DSP server. Cannot check if your lists are already existing."
         print("WARNING: " + err_msg)
         logger.warning(err_msg, exc_info=True)
         existing_lists = []
         overall_success = False
 
     current_project_lists: dict[str, Any] = {}
     for new_list in lists_to_create:
         # if list exists already, add it to "current_project_lists" (for later usage), then skip it
-        existing_list = [x for x in existing_lists if x.project == project_remote.id and x.name == new_list["name"]]
+        existing_list = [x for x in existing_lists if x.project == project_remote.iri and x.name == new_list["name"]]
         if existing_list:
             existing_list_name = existing_list[0].name
             if not existing_list_name:
                 raise BaseError(f"Node {existing_list[0]} has no name.")
             current_project_lists[existing_list_name] = {
                 "id": existing_list[0].iri,
                 "nodes": new_list["nodes"],
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/project_get.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/project_get.py`

 * *Files 5% similar despite different names*

```diff
@@ -55,15 +55,15 @@
     project = project.read()
     project_obj = project.createDefinitionFileObj()
 
     # get groups
     if verbose:
         print("Getting groups...")
     groups_obj: list[dict[str, Any]] = []
-    groups = Group.getAllGroupsForProject(con=con, proj_iri=str(project.id))
+    groups = Group.getAllGroupsForProject(con=con, proj_iri=str(project.iri))
     if groups:
         for group in groups:
             groups_obj.append(group.createDefinitionFileObj())
             if verbose:
                 print(f"\tGot group '{group.name}'")
     project_obj["groups"] = groups_obj
 
@@ -74,40 +74,40 @@
     users = User.getAllUsersForProject(con=con, proj_shortcode=str(project.shortcode))
     if users:
         for usr in users:
             users_obj.append(
                 usr.createDefinitionFileObj(
                     con=con,
                     proj_shortname=str(project.shortname),
-                    proj_iri=str(project.id),
+                    proj_iri=str(project.iri),
                 )
             )
             if verbose:
                 print(f"\tGot user '{usr.username}'")
         project_obj["users"] = users_obj
 
     # get the lists
     if verbose:
         print("Getting lists...")
     list_obj: list[dict[str, Any]] = []
-    list_roots = ListNode.getAllLists(con=con, project_iri=project.id)
+    list_roots = ListNode.getAllLists(con=con, project_iri=project.iri)
     if list_roots:
         for list_root in list_roots:
             complete_list = list_root.getAllNodes()
             list_obj.append(complete_list.createDefinitionFileObj())
             if verbose:
                 print(f"\tGot list '{list_root.name}'")
     project_obj["lists"] = list_obj
 
     # get the ontologies
     if verbose:
         print("Getting ontologies...")
     project_obj["ontologies"] = []
     prefixes: dict[str, str] = dict()
-    ontologies = Ontology.getProjectOntologies(con, str(project.id))
+    ontologies = Ontology.getProjectOntologies(con, str(project.iri))
     ontology_ids = [onto.iri for onto in ontologies]
     for ontology_id in ontology_ids:
         onto_url_parts = ontology_id.split("/")  # an id has the form http://0.0.0.0:3333/ontology/4123/testonto/v2
         name = onto_url_parts[len(onto_url_parts) - 2]
         shortcode = onto_url_parts[len(onto_url_parts) - 3]
         ontology = Ontology.getOntologyFromServer(con=con, shortcode=shortcode, name=name)
         project_obj["ontologies"].append(ontology.createDefinitionFileObj())
@@ -118,11 +118,11 @@
     schema = "https://raw.githubusercontent.com/dasch-swiss/dsp-tools/main/src/dsp_tools/resources/schema/project.json"
     outfile_content = {
         "prefixes": prefixes,
         "$schema": schema,
         "project": project_obj,
     }
 
-    with open(outfile_path, "w", encoding="utf8") as f:
+    with open(outfile_path, "w", encoding="utf-8") as f:
         json.dump(outfile_content, f, indent=4, ensure_ascii=False)
 
     return True
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/project_validate.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/project_validate.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/rosetta.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/rosetta.py`

 * *Files identical despite different names*

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/shared.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/shared.py`

 * *Files 3% similar despite different names*

```diff
@@ -8,15 +8,15 @@
 from datetime import datetime
 from pathlib import Path
 from typing import Any, Callable, Optional, Union
 
 import pandas as pd
 import regex
 from lxml import etree
-from requests import RequestException
+from requests import ReadTimeout, RequestException
 
 from dsp_tools.models.connection import Connection
 from dsp_tools.models.exceptions import BaseError, UserError
 from dsp_tools.models.propertyelement import PropertyElement
 from dsp_tools.utils.logging import get_logger
 
 logger = get_logger(__name__)
@@ -71,39 +71,46 @@
 
     Raises:
         BaseError or unexpected exception if the action fails permanently
 
     Returns:
         the return value of action
     """
-
+    action_as_str = f"action='{action}', args='{args}', kwargs='{kwargs}'"
     for i in range(7):
         try:
             if args and not kwargs:
                 return action(*args)
             elif kwargs and not args:
                 return action(**kwargs)
             elif args and kwargs:
                 return action(*args, **kwargs)
             else:
                 return action()
+        except (TimeoutError, ReadTimeout):
+            msg = f"Timeout Error: Try reconnecting to DSP server, next attempt in {2 ** i} seconds..."
+            print(f"{datetime.now().isoformat()}: {msg}")
+            logger.error(f"{msg} {action_as_str} (retry-counter i={i})", exc_info=True)
+            time.sleep(2**i)
+            continue
         except (ConnectionError, RequestException):
-            print(f"{datetime.now().isoformat()}: Try reconnecting to DSP server, next attempt in {2 ** i} seconds...")
-            logger.error(f"Try reconnecting to DSP server, next attempt in {2 ** i} seconds...", exc_info=True)
+            msg = f"Network Error: Try reconnecting to DSP server, next attempt in {2 ** i} seconds..."
+            print(f"{datetime.now().isoformat()}: {msg}")
+            logger.error(f"{msg} {action_as_str} (retry-counter i={i})", exc_info=True)
             time.sleep(2**i)
             continue
         except BaseError as err:
             in_500_range = False
             if err.status_code:
                 in_500_range = 500 <= err.status_code < 600
             try_again_later = "try again later" in err.message
             if try_again_later or in_500_range:
-                msg = f"Try reconnecting to DSP server, next attempt in {2 ** i} seconds..."
+                msg = f"Transient Error: Try reconnecting to DSP server, next attempt in {2 ** i} seconds..."
                 print(f"{datetime.now().isoformat()}: {msg}")
-                logger.error(msg, exc_info=True)
+                logger.error(f"{msg} {action_as_str} (retry-counter i={i})", exc_info=True)
                 time.sleep(2**i)
                 continue
             else:
                 raise err
 
     logger.error("Permanently unable to execute the network action. See logs for more details.")
     raise BaseError("Permanently unable to execute the network action. See logs for more details.")
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/stack_handling.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/stack_handling.py`

 * *Files 3% similar despite different names*

```diff
@@ -46,15 +46,15 @@
     for file in docker_path_of_distribution.iterdir():
         with importlib.resources.as_file(file) as f:
             file_path = Path(f)
         shutil.copy(file_path, docker_path_of_user / file.name)
 
     # get sipi.docker-config.lua
     # take commit hash of latest DSP-API release from https://github.com/dasch-swiss/dsp-api/commits/main
-    commit_of_used_api_version = "29b437e14b4d6382c3ffb2981a68f1bfac0a6212"
+    commit_of_used_api_version = "e3a19dd975425ca75fca9f5841952fa9429837a7"
     url_prefix = f"https://github.com/dasch-swiss/dsp-api/raw/{commit_of_used_api_version}/"
     docker_config_lua_text = requests.get(f"{url_prefix}sipi/config/sipi.docker-config.lua", timeout=5).text
     if max_file_size:
         max_post_size_regex = r"max_post_size ?= ?[\'\"]\d+M[\'\"]"
         if not re.search(max_post_size_regex, docker_config_lua_text):
             raise BaseError("Unable to set max_file_size. Please try again without this flag.")
         docker_config_lua_text = re.sub(
```

### Comparing `dsp_tools-2.3.3/src/dsp_tools/utils/xml_upload.py` & `dsp_tools-2.3.4/src/dsp_tools/utils/xml_upload.py`

 * *Files 1% similar despite different names*

```diff
@@ -1023,44 +1023,47 @@
     In case the xmlupload must be interrupted,
     e.g. because of an error that could not be handled,
     or due to keyboard interrupt,
     this method ensures
     that all information about what is already in DSP
     is written into diagnostic files.
 
-    It then re-raises the original error.
+    It then quits the Python interpreter with exit code 1.
 
     Args:
         err: error that was the cause of the abort
         id2iri_mapping: mapping of ids from the XML file to IRIs in DSP (only successful uploads appear here)
         failed_uploads: resources that caused an error when uploading to DSP
         stashed_xml_texts: all xml texts that have been stashed
         stashed_resptr_props: all resptr props that have been stashed
         save_location: path where to save the diagnostic info
         timestamp_str: timestamp for the name of the diagnostic files
 
     Returns:
         None
     """
-
-    print("\n==========================================\nxmlupload must be aborted because of an error")
-    logger.info("xmlupload must be aborted because of an error")
+    print(
+        f"\n==========================================\n"
+        f"xmlupload must be aborted because of an error.\n"
+        f"Error message: '{err}'\n"
+    )
+    logger.error("xmlupload must be aborted because of an error", exc_info=err)
 
     # only stashed properties of resources that already exist in DSP are of interest
     stashed_xml_texts = _purge_stashed_xml_texts(
         stashed_xml_texts=stashed_xml_texts,
         id2iri_mapping=id2iri_mapping,
     )
     stashed_resptr_props = _purge_stashed_resptr_props(
         stashed_resptr_props=stashed_resptr_props,
         id2iri_mapping=id2iri_mapping,
     )
 
     if id2iri_mapping:
-        id2iri_mapping_file = f"{save_location}/{timestamp_str}_id2iri_mapping.json"
+        id2iri_mapping_file = f"{save_location}/{timestamp_str}_id2iri_mapping.json\n"
         with open(id2iri_mapping_file, "x", encoding="utf-8") as f:
             json.dump(id2iri_mapping, f, ensure_ascii=False, indent=4)
         print(f"The mapping of internal IDs to IRIs was written to {id2iri_mapping_file}")
         logger.info(f"The mapping of internal IDs to IRIs was written to {id2iri_mapping_file}")
 
     if stashed_xml_texts:
         stashed_xml_texts_serializable = {
@@ -1073,15 +1076,15 @@
                 fp=f,
                 ensure_ascii=False,
                 indent=4,
                 cls=KnoraStandoffXmlEncoder,
             )
         msg = (
             f"There are stashed text properties that could not be reapplied to the resources they were stripped from. "
-            f"They were saved to {xml_filename}."
+            f"They were saved to {xml_filename}.\n"
         )
         print(msg)
         logger.info(msg)
 
     if stashed_resptr_props:
         stashed_resptr_props_serializable = {
             r.id: {p.name: plist for p, plist in rdict.items()} for r, rdict in stashed_resptr_props.items()
@@ -1092,24 +1095,19 @@
                 obj=stashed_resptr_props_serializable,
                 fp=f,
                 ensure_ascii=False,
                 indent=4,
             )
         msg = (
             f"There are stashed resptr properties that could not be reapplied "
-            f"to the resources they were stripped from. They were saved to {resptr_filename}"
+            f"to the resources they were stripped from. They were saved to {resptr_filename}\n"
         )
         print(msg)
         logger.info(msg)
 
     # print the resources that threw an error when they were tried to be uploaded
     if failed_uploads:
         msg = f"Independently of this error, there were some resources that could not be uploaded: {failed_uploads}"
         print(msg)
         logger.info(msg)
 
-    if isinstance(err, KeyboardInterrupt):
-        sys.exit(1)
-    else:
-        print("The error will now be raised again:\n==========================================\n")
-        logger.info("The error will now be raised again")
-        raise err
+    sys.exit(1)
```

### Comparing `dsp_tools-2.3.3/PKG-INFO` & `dsp_tools-2.3.4/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: dsp-tools
-Version: 2.3.3
+Version: 2.3.4
 Summary: DSP-TOOLS is a Python package with a command line interface that helps you interact with a DaSCH service platform (DSP) server.
 Home-page: https://www.dasch.swiss/
 License: GPL-3.0-only
 Author: DaSCH - Swiss National Data and Service Center for the Humanities
 Author-email: info@dasch.swiss
 Requires-Python: >=3.9,<4.0
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
```


# Comparing `tmp/ScriptCollection-3.3.97-py3-none-any.whl.zip` & `tmp/ScriptCollection-3.4.0-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,16 +1,16 @@
-Zip file size: 59634 bytes, number of entries: 14
--rw-rw-rw-  2.0 fat    18064 b- defN 23-Mar-05 15:39 ScriptCollection/Executables.py
--rw-rw-rw-  2.0 fat    34151 b- defN 23-May-26 16:46 ScriptCollection/GeneralUtilities.py
+Zip file size: 61676 bytes, number of entries: 14
+-rw-rw-rw-  2.0 fat    18794 b- defN 23-Jun-27 21:57 ScriptCollection/Executables.py
+-rw-rw-rw-  2.0 fat    34378 b- defN 23-Jun-27 21:57 ScriptCollection/GeneralUtilities.py
 -rw-rw-rw-  2.0 fat     1937 b- defN 22-Aug-30 21:59 ScriptCollection/ProgramRunnerBase.py
 -rw-rw-rw-  2.0 fat     6275 b- defN 23-May-26 16:46 ScriptCollection/ProgramRunnerEpew.py
 -rw-rw-rw-  2.0 fat     3023 b- defN 22-Aug-30 21:59 ScriptCollection/ProgramRunnerPopen.py
--rw-rw-rw-  2.0 fat    90693 b- defN 23-Jun-06 19:19 ScriptCollection/ScriptCollectionCore.py
--rw-rw-rw-  2.0 fat   133998 b- defN 23-Jun-06 10:08 ScriptCollection/TasksForCommonProjectStructure.py
+-rw-rw-rw-  2.0 fat    95771 b- defN 23-Jun-27 21:57 ScriptCollection/ScriptCollectionCore.py
+-rw-rw-rw-  2.0 fat   139730 b- defN 23-Jun-27 21:57 ScriptCollection/TasksForCommonProjectStructure.py
 -rw-rw-rw-  2.0 fat     7918 b- defN 22-Aug-30 21:59 ScriptCollection/UpdateCertificates.py
 -rw-rw-rw-  2.0 fat        0 b- defN 22-Aug-29 05:45 ScriptCollection/__init__.py
--rw-rw-rw-  2.0 fat     7795 b- defN 23-Jun-06 19:19 ScriptCollection-3.3.97.dist-info/METADATA
--rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-06 19:19 ScriptCollection-3.3.97.dist-info/WHEEL
--rw-rw-rw-  2.0 fat     1968 b- defN 23-Jun-06 19:19 ScriptCollection-3.3.97.dist-info/entry_points.txt
--rw-rw-rw-  2.0 fat       17 b- defN 23-Jun-06 19:19 ScriptCollection-3.3.97.dist-info/top_level.txt
--rw-rw-r--  2.0 fat     1295 b- defN 23-Jun-06 19:19 ScriptCollection-3.3.97.dist-info/RECORD
-14 files, 307226 bytes uncompressed, 57442 bytes compressed:  81.3%
+-rw-rw-rw-  2.0 fat     7649 b- defN 23-Jun-27 21:58 ScriptCollection-3.4.0.dist-info/METADATA
+-rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-27 21:58 ScriptCollection-3.4.0.dist-info/WHEEL
+-rw-rw-rw-  2.0 fat     2088 b- defN 23-Jun-27 21:58 ScriptCollection-3.4.0.dist-info/entry_points.txt
+-rw-rw-rw-  2.0 fat       17 b- defN 23-Jun-27 21:58 ScriptCollection-3.4.0.dist-info/top_level.txt
+-rw-rw-r--  2.0 fat     1290 b- defN 23-Jun-27 21:58 ScriptCollection-3.4.0.dist-info/RECORD
+14 files, 318962 bytes uncompressed, 59494 bytes compressed:  81.3%
```

## zipnote {}

```diff
@@ -21,23 +21,23 @@
 
 Filename: ScriptCollection/UpdateCertificates.py
 Comment: 
 
 Filename: ScriptCollection/__init__.py
 Comment: 
 
-Filename: ScriptCollection-3.3.97.dist-info/METADATA
+Filename: ScriptCollection-3.4.0.dist-info/METADATA
 Comment: 
 
-Filename: ScriptCollection-3.3.97.dist-info/WHEEL
+Filename: ScriptCollection-3.4.0.dist-info/WHEEL
 Comment: 
 
-Filename: ScriptCollection-3.3.97.dist-info/entry_points.txt
+Filename: ScriptCollection-3.4.0.dist-info/entry_points.txt
 Comment: 
 
-Filename: ScriptCollection-3.3.97.dist-info/top_level.txt
+Filename: ScriptCollection-3.4.0.dist-info/top_level.txt
 Comment: 
 
-Filename: ScriptCollection-3.3.97.dist-info/RECORD
+Filename: ScriptCollection-3.4.0.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## ScriptCollection/Executables.py

```diff
@@ -193,29 +193,47 @@
 
 
 def ShowMissingFiles() -> int:
     parser = argparse.ArgumentParser(description='Shows all files which are in folderA but not in folder B. This program does not do any content-comparisons.')
     parser.add_argument('folderA')
     parser.add_argument('folderB')
     args = parser.parse_args()
-    ScriptCollectionCore().SCShowMissingFiles(args.folderA, args.folderB)
+    ScriptCollectionCore().show_missing_files(args.folderA, args.folderB)
+    return 0
+
+
+def ExtractPDFPages() -> int:
+    parser = argparse.ArgumentParser(description='Extract pages from PDF-file')
+    parser.add_argument('file', help='Input file')
+    parser.add_argument('frompage', help='First page')
+    parser.add_argument('topage', help='Last page')
+    parser.add_argument('outputfile', help='File for the resulting PDF-document')
+    args = parser.parse_args()
+    ScriptCollectionCore().extract_pdf_pages(args.file, int(args.frompage), int(args.topage), args.outputfile)
     return 0
 
 
 def MergePDFs() -> int:
-    parser = argparse.ArgumentParser(description='merges pdf-files')
+    parser = argparse.ArgumentParser(description='Merges PDF-files')
     parser.add_argument('files', help='Comma-separated filenames')
-    parser = argparse.ArgumentParser(description='''Takes some pdf-files and merge them to one single pdf-file.
-Usage: "python MergePDFs.py myfile1.pdf,myfile2.pdf,myfile3.pdf result.pdf"''')
-    parser.add_argument('outputfile', help='File for the resulting pdf-document')
+    parser.add_argument('outputfile', help='File for the resulting PDF-document')
     args = parser.parse_args()
     ScriptCollectionCore().merge_pdf_files(args.files.split(','), args.outputfile)
     return 0
 
 
+def PDFToImage() -> int:
+    parser = argparse.ArgumentParser(description='Converts a PDF-document to an image')
+    parser.add_argument('file', help='Input-file')
+    parser.add_argument('outputfilename_without_extension', help='File for the resulting image')
+    args = parser.parse_args()
+    ScriptCollectionCore().pdf_to_image(args.file, args.outputfilename_without_extension)
+    return 0
+
+
 def KeyboardDiagnosis() -> None:
     """Caution: This function does usually never terminate"""
     keyboard.hook(__keyhook)
     while True:
         time.sleep(10)
```

## ScriptCollection/GeneralUtilities.py

```diff
@@ -819,7 +819,12 @@
         # TODO add more hosts to check to return true if at least one is available
         try:
             with urllib.request.urlopen("https://google.com") as url_result:
                 return (url_result.code // 100) == 2
         except:
             pass
         return False
+
+    @staticmethod
+    @check_arguments
+    def replace_variable_in_string(input_string: str, variable_name: str, variable_value: str) -> None:
+        return input_string.replace(f"__[{variable_name}]__", variable_value)
```

## ScriptCollection/ScriptCollectionCore.py

```diff
@@ -9,28 +9,31 @@
 from pathlib import Path
 from random import randrange
 from subprocess import Popen
 import re
 import shutil
 import traceback
 import uuid
+import tempfile
 import io
 import requests
 import ntplib
 import qrcode
 import pycdlib
+from PIL import Image
 import send2trash
-from PyPDF2 import PdfFileMerger
+import fitz
+import PyPDF2
 from .GeneralUtilities import GeneralUtilities
 from .ProgramRunnerBase import ProgramRunnerBase
 from .ProgramRunnerPopen import ProgramRunnerPopen
 from .ProgramRunnerEpew import ProgramRunnerEpew, CustomEpewArgument
 
 
-version = "3.3.97"
+version = "3.4.0"
 __version__ = version
 
 
 class ScriptCollectionCore:
 
     # The purpose of this property is to use it when testing your code which uses scriptcollection for external program-calls.
     # Do not change this value for productive environments.
@@ -656,25 +659,44 @@
             self.__create_thumbnail(filename_without_extension, folder, length_in_seconds, tempname_for_thumbnails, amounf_of_previewframes)
         finally:
             for thumbnail_to_delete in Path(folder).rglob(tempname_for_thumbnails+"-*"):
                 file = str(thumbnail_to_delete)
                 os.remove(file)
 
     @GeneralUtilities.check_arguments
-    def merge_pdf_files(self, files, outputfile: str) -> None:
+    def extract_pdf_pages(self, file: str, from_page: int, to_page: int, outputfile: str) -> None:
+        pdf_reader = PyPDF2.PdfReader(file)
+        pdf_writer = PyPDF2.PdfWriter()
+        start = from_page
+        end = to_page
+        while start <= end:
+            pdf_writer.add_page(pdf_reader.pages[start-1])
+            start += 1
+        with open(outputfile, 'wb') as out:
+            pdf_writer.write(out)
+
+    @GeneralUtilities.check_arguments
+    def merge_pdf_files(self, files: list[str], outputfile: str) -> None:
         # TODO add wildcard-option
-        pdfFileMerger = PdfFileMerger()
+        pdfFileMerger = PyPDF2.PdfFileMerger()
         for file in files:
             pdfFileMerger.append(file.strip())
         pdfFileMerger.write(outputfile)
         pdfFileMerger.close()
-        return 0
 
     @GeneralUtilities.check_arguments
-    def SCShowMissingFiles(self, folderA: str, folderB: str):
+    def pdf_to_image(self, file: str, outputfilename_without_extension: str) -> None:
+        doc = fitz.open(file)
+        for i, page in enumerate(doc):
+            pix = page.get_pixmap()
+            img = Image.frombytes("RGB", [pix.width, pix.height], pix.samples)
+            img.save(f"{outputfilename_without_extension}_{i}.png", "PNG")
+
+    @GeneralUtilities.check_arguments
+    def show_missing_files(self, folderA: str, folderB: str):
         for file in GeneralUtilities.get_missing_files(folderA, folderB):
             GeneralUtilities.write_message_to_stdout(file)
 
     @GeneralUtilities.check_arguments
     def SCCreateEmptyFileWithSpecificSize(self, name: str, size_string: str) -> int:
         if size_string.isdigit():
             size = int(size_string)
@@ -1625,7 +1647,85 @@
         result = self.run_program("dotnet", f"list {csproj_filename} package --outdated", folder)
         for line in result[1].replace("\r", "").split("\n"):
             # Relevant output-lines are something like "    > NJsonSchema             10.7.0        10.7.0      10.9.0"
             if ">" in line:
                 package_name = line.replace(">", "").strip().split(" ")[0]
                 GeneralUtilities.write_message_to_stderr(f"Update package {package_name}")
                 self.run_program("dotnet", f"add {csproj_filename} package {package_name}", folder)
+
+    @GeneralUtilities.check_arguments
+    def create_deb_package(self, codeunit_name: str, binary_folder: str, control_file_content: str,
+                           deb_output_folder: str, verbosity: int, permission_of_executable_file_as_octet_triple: int) -> None:
+
+        # prepare
+        GeneralUtilities.ensure_directory_exists(deb_output_folder)
+        toolname = codeunit_name
+        temp_folder = os.path.join(tempfile.gettempdir(), str(uuid.uuid4()))
+        GeneralUtilities.ensure_directory_exists(temp_folder)
+        bin_folder = binary_folder
+        tool_content_folder_name = toolname+"Content"
+
+        # create folder
+        GeneralUtilities.ensure_directory_exists(temp_folder)
+        control_content_folder_name = "controlcontent"
+        packagecontent_control_folder = os.path.join(temp_folder, control_content_folder_name)
+        GeneralUtilities.ensure_directory_exists(packagecontent_control_folder)
+        data_content_folder_name = "datacontent"
+        packagecontent_data_folder = os.path.join(temp_folder, data_content_folder_name)
+        GeneralUtilities.ensure_directory_exists(packagecontent_data_folder)
+        entireresult_content_folder_name = "entireresultcontent"
+        packagecontent_entireresult_folder = os.path.join(temp_folder, entireresult_content_folder_name)
+        GeneralUtilities.ensure_directory_exists(packagecontent_entireresult_folder)
+
+        # create "debian-binary"-file
+        debianbinary_file = os.path.join(packagecontent_entireresult_folder, "debian-binary")
+        GeneralUtilities.ensure_file_exists(debianbinary_file)
+        GeneralUtilities.write_text_to_file(debianbinary_file, "2.0\n")
+
+        # create control-content
+
+        #  conffiles
+        conffiles_file = os.path.join(packagecontent_control_folder, "conffiles")
+        GeneralUtilities.ensure_file_exists(conffiles_file)
+
+        #  postinst-script
+        postinst_file = os.path.join(packagecontent_control_folder, "postinst")
+        GeneralUtilities.ensure_file_exists(postinst_file)
+        exe_file = f"/usr/bin/{tool_content_folder_name}/{toolname}"
+        link_file = f"/usr/bin/{toolname.lower()}"
+        permission = str(permission_of_executable_file_as_octet_triple)
+        GeneralUtilities.write_text_to_file(postinst_file, f"""#!/bin/sh
+    ln -s {exe_file} {link_file}
+    chmod {permission} {exe_file}
+    chmod {permission} {link_file}
+    """)
+
+        #  control
+        control_file = os.path.join(packagecontent_control_folder, "control")
+        GeneralUtilities.ensure_file_exists(control_file)
+        GeneralUtilities.write_text_to_file(control_file, control_file_content)
+
+        #  md5sums
+        md5sums_file = os.path.join(packagecontent_control_folder, "md5sums")
+        GeneralUtilities.ensure_file_exists(md5sums_file)
+
+        # create data-content
+
+        #  copy binaries
+        usr_bin_folder = os.path.join(packagecontent_data_folder, "usr/bin")
+        GeneralUtilities.ensure_directory_exists(usr_bin_folder)
+        usr_bin_content_folder = os.path.join(usr_bin_folder, tool_content_folder_name)
+        GeneralUtilities.copy_content_of_folder(bin_folder, usr_bin_content_folder)
+
+        # create debfile
+        deb_filename = f"{toolname}.deb"
+        self.run_program_argsasarray("tar", ["czf", f"../{entireresult_content_folder_name}/control.tar.gz", "*"],
+                                     packagecontent_control_folder, verbosity=verbosity)
+        self.run_program_argsasarray("tar", ["czf", f"../{entireresult_content_folder_name}/data.tar.gz", "*"],
+                                     packagecontent_data_folder, verbosity=verbosity)
+        self.run_program_argsasarray("ar", ["r", deb_filename, "debian-binary", "control.tar.gz", "data.tar.gz"],
+                                     packagecontent_entireresult_folder, verbosity=verbosity)
+        result_file = os.path.join(packagecontent_entireresult_folder, deb_filename)
+        shutil.copy(result_file, os.path.join(deb_output_folder, deb_filename))
+
+        # cleanup
+        GeneralUtilities.ensure_directory_does_not_exist(temp_folder)
```

## ScriptCollection/TasksForCommonProjectStructure.py

```diff
@@ -1,18 +1,20 @@
 from datetime import datetime
 from graphlib import TopologicalSorter
 import os
 from pathlib import Path
 from functools import cmp_to_key
 import shutil
+import math
 import re
 import urllib.request
 import zipfile
 import json
 import configparser
+import requests
 from packaging import version
 import xmlschema
 from OpenSSL import crypto
 from lxml import etree
 from .GeneralUtilities import GeneralUtilities
 from .ScriptCollectionCore import ScriptCollectionCore
 from .ProgramRunnerEpew import ProgramRunnerEpew
@@ -146,22 +148,29 @@
     def get_testcoverage_threshold_from_codeunit_file(self, codeunit_file):
         root: etree._ElementTree = etree.parse(codeunit_file)
         return float(str(root.xpath('//cps:minimalcodecoverageinpercent/text()', namespaces={
             'cps': 'https://projects.aniondev.de/PublicProjects/Common/ProjectTemplates/-/tree/main/Conventions/RepositoryStructure/CommonProjectStructure'
         })[0]))
 
     @GeneralUtilities.check_arguments
-    def codeunit_hast_testable_sourcecode(self, codeunit_file) -> bool:
+    def codeunit_has_testable_sourcecode(self, codeunit_file) -> bool:
         root: etree._ElementTree = etree.parse(codeunit_file)
         return GeneralUtilities.string_to_boolean(str(root.xpath('//cps:properties/@codeunithastestablesourcecode', namespaces={
             'cps': 'https://projects.aniondev.de/PublicProjects/Common/ProjectTemplates/-/tree/main/Conventions/RepositoryStructure/CommonProjectStructure'
         })[0]))
 
     @GeneralUtilities.check_arguments
-    def codeunit_hast_updatable_dependencies(self, codeunit_file) -> bool:
+    def codeunit_throws_exception_if_codeunitfile_is_not_validatable(self, codeunit_file) -> bool:
+        root: etree._ElementTree = etree.parse(codeunit_file)
+        return GeneralUtilities.string_to_boolean(str(root.xpath('//cps:properties/@throwexceptionifcodeunitfilecannotbevalidated', namespaces={
+            'cps': 'https://projects.aniondev.de/PublicProjects/Common/ProjectTemplates/-/tree/main/Conventions/RepositoryStructure/CommonProjectStructure'
+        })[0]))
+
+    @GeneralUtilities.check_arguments
+    def codeunit_has_updatable_dependencies(self, codeunit_file) -> bool:
         root: etree._ElementTree = etree.parse(codeunit_file)
         return GeneralUtilities.string_to_boolean(str(root.xpath('//cps:properties/@codeunithasupdatabledependencies', namespaces={
             'cps': 'https://projects.aniondev.de/PublicProjects/Common/ProjectTemplates/-/tree/main/Conventions/RepositoryStructure/CommonProjectStructure'
         })[0]))
 
     @GeneralUtilities.check_arguments
     def check_testcoverage(self, testcoverage_file_in_cobertura_format: str, repository_folder: str, codeunitname: str):
@@ -384,14 +393,15 @@
         codeunit_file: str = os.path.join(GeneralUtilities.resolve_relative_path("..", os.path.dirname(common_tasks_file)), f"{codeunit_name}.codeunit.xml")
         self.write_version_to_codeunit_file(codeunit_file, current_version)
 
     @GeneralUtilities.check_arguments
     def t4_transform(self, commontasks_script_file_of_current_file: str, verbosity: int):
         sc = ScriptCollectionCore()
         codeunit_folder = GeneralUtilities.resolve_relative_path("../..", commontasks_script_file_of_current_file)
+        self.__ensure_grylibrary_is_available(codeunit_folder)
         repository_folder: str = os.path.dirname(codeunit_folder)
         codeunitname: str = os.path.basename(codeunit_folder)
         codeunit_folder = os.path.join(repository_folder, codeunitname)
         for search_result in Path(codeunit_folder).glob('**/*.tt'):
             tt_file = str(search_result)
             relative_path_to_tt_file = str(Path(tt_file).relative_to(codeunit_folder))
             argument = f"--parameter=repositoryFolder={repository_folder} --parameter=codeUnitName={codeunitname} {relative_path_to_tt_file}"
@@ -792,15 +802,15 @@
 
     @GeneralUtilities.check_arguments
     def __export_codeunit_reference_content_to_reference_repository(self, project_version_identifier: str, replace_existing_content: bool,
                                                                     target_folder_for_reference_repository: str, repository: str, codeunitname: str, projectname: str,
                                                                     codeunit_version: str, public_repository_url: str, branch: str) -> None:
         codeunit_folder = os.path.join(repository, codeunitname)
         codeunit_file = os.path.join(codeunit_folder, f"{codeunitname}.codeunit.xml")
-        codeunit_has_testcases = self.codeunit_hast_testable_sourcecode(codeunit_file)
+        codeunit_has_testcases = self.codeunit_has_testable_sourcecode(codeunit_file)
         target_folder = os.path.join(target_folder_for_reference_repository, project_version_identifier, codeunitname)
         if os.path.isdir(target_folder) and not replace_existing_content:
             raise ValueError(f"Folder '{target_folder}' already exists.")
         GeneralUtilities.ensure_directory_does_not_exist(target_folder)
         GeneralUtilities.ensure_directory_exists(target_folder)
         codeunit_version_identifier = "Latest" if project_version_identifier == "Latest" else "v"+codeunit_version
         page_title = f"{codeunitname} {codeunit_version_identifier} codeunit-reference"
@@ -1248,31 +1258,38 @@
             raise ValueError(f'Codeunitfile "{codeunit_file}" does not exist.')
         # TODO implement usage of self.reference_latest_version_of_xsd_when_generating_xml
         namespaces = {'cps': 'https://projects.aniondev.de/PublicProjects/Common/ProjectTemplates/-/tree/main/Conventions/RepositoryStructure/CommonProjectStructure',
                       'xsi': 'http://www.w3.org/2001/XMLSchema-instance'}
         root: etree._ElementTree = etree.parse(codeunit_file)
 
         # Check codeunit-spcecification-version
-        codeunit_file_version = root.xpath('//cps:codeunit/@codeunitspecificationversion', namespaces=namespaces)[0]
-        supported_codeunitspecificationversion = "2.7.1"  # must always be the latest version of the ProjectTemplates-repository
-        if codeunit_file_version != supported_codeunitspecificationversion:
-            raise ValueError(f"ScriptCollection only supports processing codeunits with codeunit-specification-version={supported_codeunitspecificationversion}.")
-        schemaLocation = root.xpath('//cps:codeunit/@xsi:schemaLocation', namespaces=namespaces)[0]
-        xmlschema.validate(codeunit_file, schemaLocation)
+        try:
+            codeunit_file_version = root.xpath('//cps:codeunit/@codeunitspecificationversion', namespaces=namespaces)[0]
+            supported_codeunitspecificationversion = "2.7.2"  # should always be the latest version of the ProjectTemplates-repository
+            if codeunit_file_version != supported_codeunitspecificationversion:
+                raise ValueError(f"ScriptCollection only supports processing codeunits with codeunit-specification-version={supported_codeunitspecificationversion}.")
+            schemaLocation = root.xpath('//cps:codeunit/@xsi:schemaLocation', namespaces=namespaces)[0]
+            xmlschema.validate(codeunit_file, schemaLocation)
+        except Exception as exception:
+            if self.codeunit_throws_exception_if_codeunitfile_is_not_validatable(codeunit_file):
+                raise exception
+            else:
+                GeneralUtilities.write_message_to_stderr(f'Warning: Codeunitfile "{codeunit_file}" can not be validated due to the following exception:')
+                GeneralUtilities.write_exception_to_stderr(exception)
 
         # Check codeunit-name
         codeunit_name_in_codeunit_file = root.xpath('//cps:codeunit/cps:name/text()', namespaces=namespaces)[0]
         if codeunit_name != codeunit_name_in_codeunit_file:
             raise ValueError(f"The folder-name ('{codeunit_name}') is not equal to the codeunit-name ('{codeunit_name_in_codeunit_file}').")
 
         # Check for mandatory files
         files = ["Other/Build/Build.py", "Other/QualityCheck/Linting.py", "Other/Reference/GenerateReference.py"]
-        if self.codeunit_hast_testable_sourcecode(codeunit_file):
+        if self.codeunit_has_testable_sourcecode(codeunit_file):
             files.append("Other/QualityCheck/RunTestcases.py")
-        if self.codeunit_hast_updatable_dependencies(codeunit_file):
+        if self.codeunit_has_updatable_dependencies(codeunit_file):
             files.append("Other/UpdateDependencies.py")
         for file in files:
             combined_file = os.path.join(codeunit_folder, file)
             if not os.path.isfile(combined_file):
                 raise ValueError(f'The mandatory file "{file}" does not exist in the codeunit-folder.')
 
         # Check developer
@@ -1746,15 +1763,15 @@
     def update_dependency_in_resources_folder(self, update_dependencies_file, dependency_name: str, latest_version_function: str):
         version_file = GeneralUtilities.resolve_relative_path(f"../Resources/Dependencies/{dependency_name}/Version.txt", update_dependencies_file)
         current_version = GeneralUtilities.read_text_from_file(version_file)
         if current_version != latest_version_function:
             GeneralUtilities.write_text_to_file(version_file, latest_version_function)
 
     @GeneralUtilities.check_arguments
-    def ensure_grylibrary_is_available(self, codeunit_folder: str):
+    def __ensure_grylibrary_is_available(self, codeunit_folder: str):
         grylibrary_folder = os.path.join(codeunit_folder, "Other", "Resources", "GRYLibrary")
         grylibrary_dll_file = os.path.join(grylibrary_folder, "BuildResult_DotNet_win-x64", "GRYLibrary.dll")
         internet_connection_is_available = GeneralUtilities.internet_connection_is_available()
         grylibrary_dll_file_exists = os.path.isfile(grylibrary_dll_file)
         if internet_connection_is_available:  # Load/Update GRYLibrary
             grylibrary_latest_codeunit_file = "https://raw.githubusercontent.com/anionDev/GRYLibrary/stable/GRYLibrary/GRYLibrary.codeunit.xml"
             with urllib.request.urlopen(grylibrary_latest_codeunit_file) as url_result:
@@ -1777,14 +1794,79 @@
         else:
             if grylibrary_dll_file_exists:
                 GeneralUtilities.write_message_to_stdout("Warning: Can not check for updates of GRYLibrary due to missing internet-connection.")
             else:
                 raise ValueError("Can not download GRYLibrary.")
 
     @GeneralUtilities.check_arguments
+    def __ensure_plant_uml_is_available(self, codeunit_folder: str) -> None:
+        plant_uml_folder = os.path.join(codeunit_folder, "Other", "Resources", "PlantUML")
+        internet_connection_is_available = GeneralUtilities.internet_connection_is_available()
+        jar_file = f"{plant_uml_folder}/plantuml.jar"
+        plantuml_jar_file_exists = os.path.isfile(jar_file)
+        if internet_connection_is_available:  # Load/Update PlantUML
+            GeneralUtilities.ensure_directory_does_not_exist(plant_uml_folder)
+            GeneralUtilities.ensure_directory_exists(plant_uml_folder)
+            response = requests.get("https://api.github.com/repos/plantuml/plantuml/releases/latest", timeout=5)
+            latest_version = response.json()["name"]
+            jar_link = f"https://github.com/plantuml/plantuml/releases/download/{latest_version}/plantuml.jar"
+            urllib.request.urlretrieve(jar_link, jar_file)
+        else:
+            if plantuml_jar_file_exists:
+                GeneralUtilities.write_message_to_stdout("Warning: Can not check for updates of PlantUML due to missing internet-connection.")
+            else:
+                raise ValueError("Can not download PlantUML.")
+
+    @GeneralUtilities.check_arguments
+    def generate_svg_files_from_plantuml_files(self, codeunit_folder: str) -> None:
+        self.__ensure_plant_uml_is_available(codeunit_folder)
+        plant_uml_folder = os.path.join(codeunit_folder, "Other", "Resources", "PlantUML")
+        files_folder = os.path.join(codeunit_folder, "Other/Reference")
+        sc = ScriptCollectionCore()
+        for file in GeneralUtilities.get_all_files_of_folder(files_folder):
+            if file.endswith(".plantuml"):
+                argument = ['-jar', f'{plant_uml_folder}/plantuml.jar', os.path.basename(file).replace("\\", "/"), '-tsvg']
+                sc.run_program_argsasarray("java", argument, os.path.dirname(file))
+
+    @GeneralUtilities.check_arguments
+    def load_deb_control_file_content(self, file: str,
+                                      codeunitname: str, codeunitversion: str, installedsize: int,
+                                      maintainername: str, maintaineremail: str, description: str,) -> str:
+        content = GeneralUtilities.read_text_from_file(file)
+        content = GeneralUtilities.replace_variable_in_string(content, "codeunitname", codeunitname)
+        content = GeneralUtilities.replace_variable_in_string(content, "codeunitversion", codeunitversion)
+        content = GeneralUtilities.replace_variable_in_string(content, "installedsize", str(installedsize))
+        content = GeneralUtilities.replace_variable_in_string(content, "maintainername", maintainername)
+        content = GeneralUtilities.replace_variable_in_string(content, "maintaineremail", maintaineremail)
+        content = GeneralUtilities.replace_variable_in_string(content, "description", description)
+        return content
+
+    @GeneralUtilities.check_arguments
+    def calculate_deb_package_size(self, binary_folder: str) -> int:
+        size_in_bytes = 0
+        for file in GeneralUtilities.get_all_files_of_folder(binary_folder):
+            size_in_bytes = size_in_bytes+os.path.getsize(file)
+        result = math.ceil(size_in_bytes/1024)
+        return result
+
+    @GeneralUtilities.check_arguments
+    def create_deb_package_for_artifact(self, codeunit_folder: str,
+                                        maintainername: str, maintaineremail: str, description: str,
+                                        verbosity: int, cmd_arguments: list[str]) -> None:
+        verbosity = self.get_verbosity_from_commandline_arguments(cmd_arguments, verbosity)
+        codeunit_name = os.path.basename(codeunit_folder)
+        binary_folder = GeneralUtilities.resolve_relative_path("Other/Artifacts/BuildResult_DotNet_linux-x64", codeunit_folder)
+        deb_output_folder = GeneralUtilities.resolve_relative_path("Other/Artifacts/BuildResult_Deb", codeunit_folder)
+        control_file = GeneralUtilities.resolve_relative_path("Other/Build/DebControlFile.txt", codeunit_folder)
+        installedsize = self.calculate_deb_package_size(binary_folder)
+        control_file_content = self.load_deb_control_file_content(control_file, codeunit_name, self.get_version_of_codeunit_folder(codeunit_folder),
+                                                                  installedsize, maintainername, maintaineremail, description)
+        self.__sc.create_deb_package(codeunit_name, binary_folder, control_file_content, deb_output_folder, verbosity, 555)
+
+    @GeneralUtilities.check_arguments
     def verify_artifact_exists(self, codeunit_folder: str, artifact_name_regexes: dict[str, bool]) -> None:
         codeunit_name: str = os.path.basename(codeunit_folder)
         artifacts_folder = os.path.join(codeunit_folder, "Other/Artifacts")
         existing_artifacts = [os.path.basename(x) for x in GeneralUtilities.get_direct_folders_of_folder(artifacts_folder)]
         for artifact_name_regex, required in artifact_name_regexes.items():
             artifact_exists = False
             for existing_artifact in existing_artifacts:
@@ -1863,15 +1945,15 @@
         GeneralUtilities.write_message_to_stdout('Run "Build.py"...')
         execution_result = self.__sc.run_program("python", f"Build.py{additional_arguments_b}{general_argument}",
                                                  build_folder, verbosity=verbosity_for_executed_programs, throw_exception_if_exitcode_is_not_zero=False)
         if execution_result[0] != 0:
             raise ValueError(f"Build.py resulted in exitcode {execution_result[0]}. StdOut: '{execution_result[1]}' StdOut: '{execution_result[2]}'")
         self.verify_artifact_exists(codeunit_folder, dict[str, bool]({"BuildResult_.+": True, "BOM": False, "CodeAnalysisResult": False, "SourceCode": True}))
 
-        codeunit_hast_testable_sourcecode = self.codeunit_hast_testable_sourcecode(codeunit_file)
+        codeunit_hast_testable_sourcecode = self.codeunit_has_testable_sourcecode(codeunit_file)
         if codeunit_hast_testable_sourcecode:
             GeneralUtilities.write_message_to_stdout('Run "RunTestcases.py"...')
             execution_result = self.__sc.run_program("python", f"RunTestcases.py{additional_arguments_r}{general_argument}",
                                                      quality_folder, verbosity=verbosity_for_executed_programs, throw_exception_if_exitcode_is_not_zero=False)
             if execution_result[0] != 0:
                 raise ValueError(f"RunTestcases.py resulted in exitcode {execution_result[0]}. StdOut: '{execution_result[1]}' StdOut: '{execution_result[2]}'")
             self.verify_artifact_exists(codeunit_folder, dict[str, bool]({"TestCoverage": True, "TestCoverageReport": False}))
```

## Comparing `ScriptCollection-3.3.97.dist-info/METADATA` & `ScriptCollection-3.4.0.dist-info/METADATA`

 * *Files 2% similar despite different names*

```diff
@@ -1,21 +1,21 @@
 Metadata-Version: 2.1
 Name: ScriptCollection
-Version: 3.3.97
+Version: 3.4.0
 Summary: The ScriptCollection is the place for reusable scripts.
 Home-page: https://github.com/anionDev/ScriptCollection
 Author: Marius Göcke
 Author-email: marius.goecke@gmail.com
 Project-URL: Documentation, https://aniondev.github.io/ScriptCollectionReference/index.html
 Project-URL: Changelog, https://github.com/anionDev/ScriptCollection/tree/main/Other/Resources/Changelog
 Keywords: package release build management
 Classifier: Intended Audience :: Developers
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
 Classifier: Programming Language :: Python :: 3.10
-Classifier: License :: OSI Approved :: MIT License
+Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Operating System :: POSIX :: Linux
 Classifier: Operating System :: Microsoft :: Windows :: Windows 10
 Classifier: Topic :: System :: Logging
 Classifier: Topic :: System :: Monitoring
 Classifier: Topic :: System :: Archiving :: Packaging
 Classifier: Topic :: System :: Systems Administration
 Classifier: Topic :: Terminals
@@ -24,18 +24,20 @@
 Description-Content-Type: text/markdown
 Requires-Dist: coverage (>=7.2.5)
 Requires-Dist: cyclonedx-bom (>=3.11.0)
 Requires-Dist: defusedxml (>=0.7.1)
 Requires-Dist: keyboard (>=0.13.5)
 Requires-Dist: lxml (>=4.9.2)
 Requires-Dist: ntplib (>=0.4.0)
+Requires-Dist: Pillow (>=9.5.0)
 Requires-Dist: pycdlib (>=1.14.0)
 Requires-Dist: Pygments (>=2.15.1)
 Requires-Dist: pylint (>=2.17.4)
 Requires-Dist: pyOpenSSL (>=23.1.1)
+Requires-Dist: PyMuPDF (>=1.22.3)
 Requires-Dist: PyPDF2 (>=3.0.1)
 Requires-Dist: pytest (>=7.3.1)
 Requires-Dist: qrcode (>=7.4.2)
 Requires-Dist: send2trash (>=1.8.2)
 Requires-Dist: twine (>=4.0.2)
 Requires-Dist: xmlschema (>=2.3.0)
 
@@ -47,31 +49,27 @@
 ![PyPI](https://img.shields.io/pypi/v/ScriptCollection)
 ![Dependencies](https://img.shields.io/librariesio/github/anionDev/ScriptCollection)
 
 [![CodeFactor](https://www.codefactor.io/repository/github/aniondev/scriptcollection/badge/main)](https://www.codefactor.io/repository/github/aniondev/scriptcollection/overview/main)
 [![Downloads](https://pepy.tech/badge/scriptcollection)](https://pepy.tech/project/scriptcollection)
 ![Coverage](https://raw.githubusercontent.com/anionDev/ScriptCollection/main/ScriptCollection/Other/Resources/TestCoverageBadges/badge_shieldsio_linecoverage_blue.svg)
 
-![License](https://img.shields.io/badge/license-MIT-blue)
-![GitHub last commit](https://img.shields.io/github/last-commit/anionDev/ScriptCollection)
-![GitHub issues](https://img.shields.io/github/issues-raw/anionDev/ScriptCollection)
-
 The ScriptCollection is the place for reusable scripts.
 
 ## Reference
 
 The reference can be found [here](https://aniondev.github.io/ScriptCollectionReference/index.html).
 
 ## Hints
 
 Most of the scripts are written in [python](https://www.python.org) 3.
 
 Caution: Before executing **any** script of this repository read the sourcecode of the script (and the sourcecode of all functions called by this function directly or transitively) carefully and verify that the script does exactly what you want to do and nothing else.
 
-Some functions are not entirely available on windows or require common third-party tools. See the [Runtime dependencies](#Runtime-dependencies)-section for more information.
+Some functions are not entirely available on windows or require common third-party tools. See the [Runtime dependencies](#runtime-dependencies)-section for more information.
 
 When using ScriptCollection it is not required but recommended for better usability to have [epew](https://github.com/anionDev/Epew) installed.
 
 ## Get ScriptCollection
 
 ### Installation via pip
```

## Comparing `ScriptCollection-3.3.97.dist-info/entry_points.txt` & `ScriptCollection-3.4.0.dist-info/entry_points.txt`

 * *Files 2% similar despite different names*

```diff
@@ -3,25 +3,27 @@
 SCBuildCodeUnits = ScriptCollection.Executables:BuildCodeUnits
 SCCalculateBitcoinBlockHash = ScriptCollection.Executables:CalculateBitcoinBlockHash
 SCChangeHashOfProgram = ScriptCollection.Executables:ChangeHashOfProgram
 SCCreateEmptyFileWithSpecificSize = ScriptCollection.Executables:CreateEmptyFileWithSpecificSize
 SCCreateHashOfAllFiles = ScriptCollection.Executables:CreateHashOfAllFiles
 SCCreateISOFileWithObfuscatedFiles = ScriptCollection.Executables:CreateISOFileWithObfuscatedFiles
 SCCreateSimpleMergeWithoutRelease = ScriptCollection.Executables:CreateSimpleMergeWithoutRelease
+SCExtractPDFPages = ScriptCollection.Executables:ExtractPDFPages
 SCFilenameObfuscator = ScriptCollection.Executables:FilenameObfuscator
 SCGenerateCertificate = ScriptCollection.Executables:GenerateCertificate
 SCGenerateCertificateAuthority = ScriptCollection.Executables:GenerateCertificateAuthority
 SCGenerateCertificateSignRequest = ScriptCollection.Executables:GenerateCertificateSignRequest
 SCGenerateSnkFiles = ScriptCollection.Executables:GenerateSnkFiles
 SCGenerateThumbnail = ScriptCollection.Executables:GenerateThumbnail
 SCHealthcheck = ScriptCollection.Executables:Healthcheck
 SCKeyboardDiagnosis = ScriptCollection.Executables:KeyboardDiagnosis
 SCMergePDFs = ScriptCollection.Executables:MergePDFs
 SCObfuscateFilesFolder = ScriptCollection.Executables:ObfuscateFilesFolder
 SCOrganizeLinesInFile = ScriptCollection.Executables:OrganizeLinesInFile
+SCPDFToImage = ScriptCollection.Executables:PDFToImage
 SCReplaceSubstringsInFilenames = ScriptCollection.Executables:ReplaceSubstringsInFilenames
 SCSearchInFiles = ScriptCollection.Executables:SearchInFiles
 SCShow2FAAsQRCode = ScriptCollection.Executables:Show2FAAsQRCode
 SCShowMissingFiles = ScriptCollection.Executables:ShowMissingFiles
 SCSignCertificate = ScriptCollection.Executables:SignCertificate
 SCUpdateNugetpackagesInCsharpProject = ScriptCollection.Executables:UpdateNugetpackagesInCsharpProject
 SCUploadFile = ScriptCollection.Executables:UploadFile
```

## Comparing `ScriptCollection-3.3.97.dist-info/RECORD` & `ScriptCollection-3.4.0.dist-info/RECORD`

 * *Files 16% similar despite different names*

```diff
@@ -1,14 +1,14 @@
-ScriptCollection/Executables.py,sha256=kXTIX92KLeFuxnYOlsyFs5lkznsxkuoBMVrV3OU7FZU,18064
-ScriptCollection/GeneralUtilities.py,sha256=rRQPyyRNZ1U0UDEuAqKZl3lHj38_4KofM6ON6hXqyRA,34151
+ScriptCollection/Executables.py,sha256=8uVVxyXrndRwTVxcL1rRlbyzaP6ZYvzxj41f7sy6L90,18794
+ScriptCollection/GeneralUtilities.py,sha256=vZDiW5lWJRCrIZVs1bTCZ-O5slQnM5dv4GcJ-RTMowY,34378
 ScriptCollection/ProgramRunnerBase.py,sha256=2kyOuoM3oFjBfLc9Q5t5RTz7Ya2CjUxFtB1rBBDmnjU,1937
 ScriptCollection/ProgramRunnerEpew.py,sha256=nIzY4dG6W-xEpkeoTbozwNZtFSIo-bU_W6t6u1AZKtE,6275
 ScriptCollection/ProgramRunnerPopen.py,sha256=HOs1QVnXiQtwXy1_xvH79bWBdd0i-2tUyyLloQBvMto,3023
-ScriptCollection/ScriptCollectionCore.py,sha256=1IRlwsjd62EYM0U5ocd-gXD1dGM5bjEx39djCpDN43Q,90693
-ScriptCollection/TasksForCommonProjectStructure.py,sha256=R641ijodm622j-BTdAFgZNTWJ1vXRN1Y7ZOEPEBIkRw,133998
+ScriptCollection/ScriptCollectionCore.py,sha256=6MoxE0Xrj1SKZzqCZ9bU6tUUlogYGaPkIkbsxhy2pJw,95771
+ScriptCollection/TasksForCommonProjectStructure.py,sha256=1VUPMfK3EWKydgUplqujzlH7ZKZgX3CgFvnVjOoc2Ds,139730
 ScriptCollection/UpdateCertificates.py,sha256=Go-JJK-YTi7aBB1phlLxypa8GHkmFHBEPB0_TT9G-bw,7918
 ScriptCollection/__init__.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
-ScriptCollection-3.3.97.dist-info/METADATA,sha256=McuUCTtysRWBw6qw7UFk2c5jH9B_VEGkZdIALfBrsjg,7795
-ScriptCollection-3.3.97.dist-info/WHEEL,sha256=pkctZYzUS4AYVn6dJ-7367OJZivF2e8RA9b_ZBjif18,92
-ScriptCollection-3.3.97.dist-info/entry_points.txt,sha256=VIuxVCOpX38lSJUwRRENBNgcGKTIBxQyrCfbJVRHP8g,1968
-ScriptCollection-3.3.97.dist-info/top_level.txt,sha256=hY2hOVH0V0Ce51WB76zKkIWTUNwMUdHo4XDkR2vYVwg,17
-ScriptCollection-3.3.97.dist-info/RECORD,,
+ScriptCollection-3.4.0.dist-info/METADATA,sha256=S-qHlKVq3dAMCTvoDw4aDUHSHto1vxkyqwE2E2qQe7U,7649
+ScriptCollection-3.4.0.dist-info/WHEEL,sha256=pkctZYzUS4AYVn6dJ-7367OJZivF2e8RA9b_ZBjif18,92
+ScriptCollection-3.4.0.dist-info/entry_points.txt,sha256=dJKdWcH41owxlKx_khj4P7DItr9lhxWP9JU2Dq8GSsQ,2088
+ScriptCollection-3.4.0.dist-info/top_level.txt,sha256=hY2hOVH0V0Ce51WB76zKkIWTUNwMUdHo4XDkR2vYVwg,17
+ScriptCollection-3.4.0.dist-info/RECORD,,
```


# Comparing `tmp/turbinia-client-1.0.2.tar.gz` & `tmp/turbinia-client-1.0.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "turbinia-client-1.0.2.tar", last modified: Wed Jan 18 23:59:10 2023, max compression
+gzip compressed data, was "turbinia-client-1.0.3.tar", last modified: Wed Jun 28 15:31:08 2023, max compression
```

## Comparing `turbinia-client-1.0.2.tar` & `turbinia-client-1.0.3.tar`

### file list

```diff
@@ -1,30 +1,30 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-18 23:59:10.705520 turbinia-client-1.0.2/
--rw-r--r--   0 root         (0) root         (0)    11358 2023-01-11 03:05:46.000000 turbinia-client-1.0.2/LICENSE
--rw-r--r--   0 root         (0) root         (0)     7872 2023-01-18 23:59:10.701519 turbinia-client-1.0.2/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     7463 2023-01-18 23:54:18.000000 turbinia-client-1.0.2/README.md
--rw-r--r--   0 root         (0) root         (0)       38 2023-01-18 23:59:10.705520 turbinia-client-1.0.2/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     1045 2023-01-18 23:58:52.000000 turbinia-client-1.0.2/setup.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-18 23:59:10.697519 turbinia-client-1.0.2/turbinia_client/
--rw-r--r--   0 root         (0) root         (0)      645 2023-01-11 03:05:46.000000 turbinia-client-1.0.2/turbinia_client/__init__.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-18 23:59:10.701519 turbinia-client-1.0.2/turbinia_client/core/
--rw-r--r--   0 root         (0) root         (0)      645 2023-01-11 03:05:46.000000 turbinia-client-1.0.2/turbinia_client/core/__init__.py
--rw-r--r--   0 root         (0) root         (0)    11256 2023-01-17 21:21:32.000000 turbinia-client-1.0.2/turbinia_client/core/commands.py
--rw-r--r--   0 root         (0) root         (0)     1108 2023-01-17 21:21:32.000000 turbinia-client-1.0.2/turbinia_client/core/groups.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-18 23:59:10.701519 turbinia-client-1.0.2/turbinia_client/factory/
--rw-r--r--   0 root         (0) root         (0)      645 2023-01-11 03:05:46.000000 turbinia-client-1.0.2/turbinia_client/factory/__init__.py
--rw-r--r--   0 root         (0) root         (0)     5716 2023-01-11 03:05:46.000000 turbinia-client-1.0.2/turbinia_client/factory/factory.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-18 23:59:10.701519 turbinia-client-1.0.2/turbinia_client/helpers/
--rw-r--r--   0 root         (0) root         (0)      645 2023-01-11 03:05:46.000000 turbinia-client-1.0.2/turbinia_client/helpers/__init__.py
--rw-r--r--   0 root         (0) root         (0)     2603 2023-01-17 18:55:30.000000 turbinia-client-1.0.2/turbinia_client/helpers/auth_helper.py
--rw-r--r--   0 root         (0) root         (0)      959 2023-01-11 03:05:46.000000 turbinia-client-1.0.2/turbinia_client/helpers/click_helper.py
--rw-r--r--   0 root         (0) root         (0)     9139 2023-01-11 03:05:46.000000 turbinia-client-1.0.2/turbinia_client/helpers/formatter.py
--rw-r--r--   0 root         (0) root         (0)     8702 2023-01-17 21:21:32.000000 turbinia-client-1.0.2/turbinia_client/turbiniacli.py
--rw-r--r--   0 root         (0) root         (0)     2664 2023-01-17 21:21:32.000000 turbinia-client-1.0.2/turbinia_client/turbiniacli_test.py
--rw-r--r--   0 root         (0) root         (0)     4728 2023-01-11 03:05:46.000000 turbinia-client-1.0.2/turbinia_client/turbiniacli_tool.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-01-18 23:59:10.701519 turbinia-client-1.0.2/turbinia_client.egg-info/
--rw-r--r--   0 root         (0) root         (0)     7872 2023-01-18 23:59:10.000000 turbinia-client-1.0.2/turbinia_client.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)      713 2023-01-18 23:59:10.000000 turbinia-client-1.0.2/turbinia_client.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-01-18 23:59:10.000000 turbinia-client-1.0.2/turbinia_client.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       74 2023-01-18 23:59:10.000000 turbinia-client-1.0.2/turbinia_client.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)       23 2023-01-18 23:59:10.000000 turbinia-client-1.0.2/turbinia_client.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)       16 2023-01-18 23:59:10.000000 turbinia-client-1.0.2/turbinia_client.egg-info/top_level.txt
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:31:08.778075 turbinia-client-1.0.3/
+-rw-r-----   0 root         (0) root         (0)    11358 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/LICENSE
+-rw-r--r--   0 root         (0) root         (0)     8676 2023-06-28 15:31:08.778075 turbinia-client-1.0.3/PKG-INFO
+-rw-r-----   0 root         (0) root         (0)     8248 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/README.rst
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 15:31:08.778075 turbinia-client-1.0.3/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     1023 2023-06-28 15:27:49.000000 turbinia-client-1.0.3/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:31:08.778075 turbinia-client-1.0.3/turbinia_client/
+-rw-r-----   0 root         (0) root         (0)      645 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/__init__.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:31:08.778075 turbinia-client-1.0.3/turbinia_client/core/
+-rw-r-----   0 root         (0) root         (0)      645 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/core/__init__.py
+-rw-r-----   0 root         (0) root         (0)    11256 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/core/commands.py
+-rw-r-----   0 root         (0) root         (0)     1108 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/core/groups.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:31:08.778075 turbinia-client-1.0.3/turbinia_client/factory/
+-rw-r-----   0 root         (0) root         (0)      645 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/factory/__init__.py
+-rw-r--r--   0 root         (0) root         (0)     5729 2023-06-23 15:21:36.000000 turbinia-client-1.0.3/turbinia_client/factory/factory.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:31:08.778075 turbinia-client-1.0.3/turbinia_client/helpers/
+-rw-r-----   0 root         (0) root         (0)      645 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/helpers/__init__.py
+-rw-r-----   0 root         (0) root         (0)     2623 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/helpers/auth_helper.py
+-rw-r-----   0 root         (0) root         (0)      959 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/helpers/click_helper.py
+-rw-r--r--   0 root         (0) root         (0)     9264 2023-06-23 15:21:36.000000 turbinia-client-1.0.3/turbinia_client/helpers/formatter.py
+-rw-r-----   0 root         (0) root         (0)     8702 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/turbiniacli.py
+-rw-r-----   0 root         (0) root         (0)     2664 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/turbiniacli_test.py
+-rw-r-----   0 root         (0) root         (0)     4728 2023-06-06 17:33:20.000000 turbinia-client-1.0.3/turbinia_client/turbiniacli_tool.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 15:31:08.778075 turbinia-client-1.0.3/turbinia_client.egg-info/
+-rw-r--r--   0 root         (0) root         (0)     8676 2023-06-28 15:31:08.000000 turbinia-client-1.0.3/turbinia_client.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)      714 2023-06-28 15:31:08.000000 turbinia-client-1.0.3/turbinia_client.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 15:31:08.000000 turbinia-client-1.0.3/turbinia_client.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       75 2023-06-28 15:31:08.000000 turbinia-client-1.0.3/turbinia_client.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)       44 2023-06-28 15:31:08.000000 turbinia-client-1.0.3/turbinia_client.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)       16 2023-06-28 15:31:08.000000 turbinia-client-1.0.3/turbinia_client.egg-info/top_level.txt
```

### Comparing `turbinia-client-1.0.2/LICENSE` & `turbinia-client-1.0.3/LICENSE`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/setup.py` & `turbinia-client-1.0.3/setup.py`

 * *Files 17% similar despite different names*

```diff
@@ -3,40 +3,28 @@
 
 Install via 'pip install turbinia-client'
 """
 from setuptools import setup, find_packages
 from pathlib import Path
 
 NAME = "turbinia-client"
-VERSION = "1.0.2"
+VERSION = "1.0.3"
 
-REQUIRES = [
-    "click",
-    "turbinia-api-lib",
-]
+REQUIRES = ["click", "turbinia-api-lib", 'google-auth-oauthlib']
 
 this_directory = Path(__file__).parent
-README = (this_directory / "README.md").read_text()
+README = (this_directory / "README.rst").read_text()
 
 setup(
-    name=NAME, 
-    version=VERSION,
+    name=NAME, version=VERSION,
     description="Turbinia API Client command-line tool.",
     long_description_content_type="text/markdown",
-    long_description=README,
-    keywords=[
+    long_description=README, keywords=[
         "Turbinia Client", "Turbinia", "Turbinia API Server"
-    ], 
-    python_requires=">=3.6", 
-    install_requires=REQUIRES,
-    packages=find_packages(),
-    include_package_data=True,
-    entry_points={
+    ], python_requires=">=3.6", install_requires=REQUIRES,
+    packages=find_packages(), include_package_data=True, entry_points={
         'console_scripts': [
             'turbinia-client=turbinia_client.turbiniacli_tool:main'
         ]
-    },
-    license='Apache License, Version 2.0',
-    url='http://turbinia.plumbing/',
+    }, license='Apache License, Version 2.0', url='http://turbinia.plumbing/',
     maintainer='Turbinia development team',
-    maintainer_email='turbinia-dev@googlegroups.com'
-)
+    maintainer_email='turbinia-dev@googlegroups.com')
```

### Comparing `turbinia-client-1.0.2/turbinia_client/__init__.py` & `turbinia-client-1.0.3/turbinia_client/__init__.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client/core/__init__.py` & `turbinia-client-1.0.3/turbinia_client/core/__init__.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client/core/commands.py` & `turbinia-client-1.0.3/turbinia_client/core/commands.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client/core/groups.py` & `turbinia-client-1.0.3/turbinia_client/core/groups.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client/factory/__init__.py` & `turbinia-client-1.0.3/turbinia_client/factory/__init__.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client/factory/factory.py` & `turbinia-client-1.0.3/turbinia_client/factory/factory.py`

 * *Files 4% similar despite different names*

```diff
@@ -59,14 +59,15 @@
   @abstractmethod
   def create_dynamic_objects(
       cls: Type[T], name: str, evidence_mapping: dict,
       request_options: dict) -> None:
     """Creates one or more click.Command or click.Options objects.
     
     Args:
+      name (str): Object name.
       evidence_mapping (dict): A dictionary of Evidence types
           and attributes retrieved from the Turbinia API server.
       request_options (dict): A dictionary of BaseRequestOptions
           attributes and types retrieved from the Turbinia APi server.
     """
     raise NotImplementedError
 
@@ -106,15 +107,15 @@
     option_objects = []
     if not name:
       log.info('An evidence type was not provided.')
       return []
     options = OptionFactory.get_evidence_attributes(evidence_mapping)
     for evidence_name, param_decls, attrs in options:
       if name == evidence_name:
-        log.debug('Creating option for {0:s}'.format(name))
+        log.debug(f'Creating option for {name:s}')
         click_option = OptionFactory.create_object(params=(param_decls, attrs))
         option_objects.append(click_option)
     return option_objects
 
   @classmethod
   def create_object(
       cls: Type[T], name: str = None, params: Tuple[Any, dict] = None,
@@ -134,15 +135,15 @@
   def create_dynamic_objects(
       cls, name: str = None, evidence_mapping: dict = None,
       request_options: dict = None) -> List[click.Command]:
     """Creates a list of click.Command objects."""
 
     command_objects = []
     for evidence_name in list(evidence_mapping.keys()):
-      log.debug('Creating command for {0:s}'.format(evidence_name))
+      log.debug(f'Creating command for {evidence_name:s}')
       # Use lowercase evidence names.
       evidence_name_lower = evidence_name.lower()
       params = OptionFactory.create_dynamic_objects(
           name=evidence_name, evidence_mapping=evidence_mapping,
           request_options=request_options)
       OptionFactory.append_request_option_objects(params, request_options)
       cmd = CommandFactory.create_object(
```

### Comparing `turbinia-client-1.0.2/turbinia_client/helpers/__init__.py` & `turbinia-client-1.0.3/turbinia_client/helpers/__init__.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client/helpers/auth_helper.py` & `turbinia-client-1.0.3/turbinia_client/helpers/auth_helper.py`

 * *Files 5% similar despite different names*

```diff
@@ -55,15 +55,15 @@
       log.error(f'Client secrets file not found: {exception!s}')
       sys.exit(1)
 
     log.info(
         'Starting local HTTP server on localhost:8888 for OAUTH flow. '
         'If running turbinia-client remotely over SSH you will need to tunnel '
         'port 8888.')
-    appflow.run_local_server(host='localhost', port=8888)
+    appflow.run_local_server(host='localhost', port=8888, open_browser=False)
     credentials = appflow.credentials
 
     # Save credentials
     with open(credentials_path, 'w', encoding='utf-8') as token:
       token.write(credentials.to_json())
 
   return credentials.id_token
```

### Comparing `turbinia-client-1.0.2/turbinia_client/helpers/click_helper.py` & `turbinia-client-1.0.3/turbinia_client/helpers/click_helper.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client/helpers/formatter.py` & `turbinia-client-1.0.3/turbinia_client/helpers/formatter.py`

 * *Files 1% similar despite different names*

```diff
@@ -131,14 +131,15 @@
     return f'##### {text.strip():s}'
 
   def bullet(self, text, level=1):
     """Formats text as a bullet in Markdown format.
 
       Args:
         text(string): Text to format
+        level(int): Indentation level.
       Return:
         string: Formatted text.
     """
     return f"{'    ' * (level - 1):s}* {text.strip():s}"
 
   def code(self, text):
     """Formats text as code in Markdown format.
@@ -288,18 +289,22 @@
   def __init__(self, requests_summary: list[dict]):
     """Initialize SummaryMarkdownReport."""
     super().__init__()
     self._requests_summary = requests_summary
 
   def generate_markdown(self) -> str:
     """Generate a Markdown version of Requests summary results."""
-    if not self._requests_summary:
-      return ''
     report: list[str] = []
-    requests_status_list = self._requests_summary.get('requests_status')
+    requests_status_list = None
+    if self._requests_summary:
+      requests_status_list = self._requests_summary.get('requests_status')
+
+    if not requests_status_list:
+      return '## No requests found.'
+
     for request_dict in requests_status_list:
       request_report = RequestMarkdownReport(request_dict).generate_markdown()
       report.append(request_report)
 
     self.report = '\n'.join(report)
     return self.report
```

### Comparing `turbinia-client-1.0.2/turbinia_client/turbiniacli.py` & `turbinia-client-1.0.3/turbinia_client/turbiniacli.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client/turbiniacli_test.py` & `turbinia-client-1.0.3/turbinia_client/turbiniacli_test.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client/turbiniacli_tool.py` & `turbinia-client-1.0.3/turbinia_client/turbiniacli_tool.py`

 * *Files identical despite different names*

### Comparing `turbinia-client-1.0.2/turbinia_client.egg-info/SOURCES.txt` & `turbinia-client-1.0.3/turbinia_client.egg-info/SOURCES.txt`

 * *Files 1% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 LICENSE
-README.md
+README.rst
 setup.py
 turbinia_client/__init__.py
 turbinia_client/turbiniacli.py
 turbinia_client/turbiniacli_test.py
 turbinia_client/turbiniacli_tool.py
 turbinia_client.egg-info/PKG-INFO
 turbinia_client.egg-info/SOURCES.txt
```


# Comparing `tmp/resume-as-code-0.0.8.tar.gz` & `tmp/resume-as-code-0.0.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "resume-as-code-0.0.8.tar", max compression
+gzip compressed data, was "resume-as-code-0.0.9.tar", max compression
```

## Comparing `resume-as-code-0.0.8.tar` & `resume-as-code-0.0.9.tar`

### file list

```diff
@@ -1,9 +1,9 @@
--rw-r--r--   0        0        0       24 2022-06-21 09:24:59.109196 resume-as-code-0.0.8/LICENSE
--rw-r--r--   0        0        0     2970 2022-06-21 09:24:59.109196 resume-as-code-0.0.8/README.md
--rw-r--r--   0        0        0      587 2022-06-21 09:24:59.109196 resume-as-code-0.0.8/pyproject.toml
--rw-r--r--   0        0        0        1 2022-06-21 09:24:59.109196 resume-as-code-0.0.8/resume_as_code/__init__.py
--rw-r--r--   0        0        0     6743 2022-06-21 09:24:59.109196 resume-as-code-0.0.8/resume_as_code/resume_generation.py
--rw-r--r--   0        0        0     2132 2022-06-21 09:24:59.109196 resume-as-code-0.0.8/resume_as_code/util.py
--rw-r--r--   0        0        0     1049 2022-06-21 09:24:59.109196 resume-as-code-0.0.8/resume_as_code/validation.py
--rw-r--r--   0        0        0     3980 2022-06-21 09:25:17.469421 resume-as-code-0.0.8/setup.py
--rw-r--r--   0        0        0     3921 2022-06-21 09:25:17.469715 resume-as-code-0.0.8/PKG-INFO
+-rw-r--r--   0        0        0       24 2022-06-22 07:35:22.837526 resume-as-code-0.0.9/LICENSE
+-rw-r--r--   0        0        0     2970 2022-06-22 07:35:22.837526 resume-as-code-0.0.9/README.md
+-rw-r--r--   0        0        0      587 2022-06-22 07:35:22.837526 resume-as-code-0.0.9/pyproject.toml
+-rw-r--r--   0        0        0        1 2022-06-22 07:35:22.837526 resume-as-code-0.0.9/resume_as_code/__init__.py
+-rw-r--r--   0        0        0     6751 2022-06-22 07:35:22.837526 resume-as-code-0.0.9/resume_as_code/resume_generation.py
+-rw-r--r--   0        0        0     2132 2022-06-22 07:35:22.837526 resume-as-code-0.0.9/resume_as_code/util.py
+-rw-r--r--   0        0        0     1049 2022-06-22 07:35:22.837526 resume-as-code-0.0.9/resume_as_code/validation.py
+-rw-r--r--   0        0        0     3980 2022-06-22 07:35:41.337620 resume-as-code-0.0.9/setup.py
+-rw-r--r--   0        0        0     3921 2022-06-22 07:35:41.337998 resume-as-code-0.0.9/PKG-INFO
```

### Comparing `resume-as-code-0.0.8/README.md` & `resume-as-code-0.0.9/README.md`

 * *Files identical despite different names*

### Comparing `resume-as-code-0.0.8/pyproject.toml` & `resume-as-code-0.0.9/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "resume-as-code"
-version = "0.0.8"
+version = "0.0.9"
 description = "A tool for automatic resume generation based on Jinja-Word-templates and YAML-files"
 authors = ["Tim Van Erum <tim.vanerum@dataroots.io>"]
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.6.0"
 python-magic = "^0.4.24"
```

### Comparing `resume-as-code-0.0.8/resume_as_code/resume_generation.py` & `resume-as-code-0.0.9/resume_as_code/resume_generation.py`

 * *Files 0% similar despite different names*

```diff
@@ -85,16 +85,16 @@
         target_location (str): [the location to store the file in]
 
     Returns:
         int: [an integer status code]
     """
     with tempfile.TemporaryDirectory() as image_folder:
         preprocess_context(context, template, image_folder)
-    template.render(context=context, jinja_env=jinja_env)
-    template.save(target_location)
+        template.render(context=context, jinja_env=jinja_env)
+        template.save(target_location)
     return 0
 
 
 def preprocess_context(
     context: Dict[str, Dict], template: DocxTemplate, image_folder: str
 ) -> None:
     """
```

### Comparing `resume-as-code-0.0.8/resume_as_code/util.py` & `resume-as-code-0.0.9/resume_as_code/util.py`

 * *Files identical despite different names*

### Comparing `resume-as-code-0.0.8/resume_as_code/validation.py` & `resume-as-code-0.0.9/resume_as_code/validation.py`

 * *Files identical despite different names*

### Comparing `resume-as-code-0.0.8/setup.py` & `resume-as-code-0.0.9/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -16,15 +16,15 @@
  'python-dotenv>=0.19.2,<0.20.0',
  'python-magic>=0.4.24,<0.5.0',
  'requests>=2.27.1,<3.0.0',
  'validators>=0.18.2,<0.19.0']
 
 setup_kwargs = {
     'name': 'resume-as-code',
-    'version': '0.0.8',
+    'version': '0.0.9',
     'description': 'A tool for automatic resume generation based on Jinja-Word-templates and YAML-files',
     'long_description': '# Resume-as-code\n\nTODO: update ReadMe\n\n## Description\n\nThis project is aimed at reducing the work required to create resumes.\n\nIn the business context, it is often required to have resumes in all kinds of different formats, styles, etc.\n\nWe want our team members at Dataroots to spend as little as time possible on formatting their resume(s), and have the ability to generate their resume in an efficient fashion.\n\nFor this, resume-as-code was created.\nThis resume generator combines technologies such as Jinja, yaml and allows the decoupling of creating a resume from formatting a resume.\n\nThe idea is that it is possible to define template, such as LaTex, Word, Markdown, etc. and using the same YAML-file, all different kinds of resumes can be generated.\n\n---\n\n## Installation\n\nThis is a Python-based tool.\n\nIt is developed on Python 3.9.1 and it hasn\'t been tested on other python versions.\n\nFor the remainder of this installation and usage guide, it is assomed that you have python version 3.9.1 installed, together with pip@21.3.1.\n\nSet up:\n\n- Download the code from github\n\n```bash\ngit clone git@github.com:datarootsio/resume-as-code.git\n```\n\n- Install the requirements in `requirements.txt`\n\n```bash\npip install -r requirements.txt\n```\n\n- Generate Google Drive credentials in https://console.cloud.google.com/apis/dashboard \n- Store the credentials in a secrets folder.\n- Create an environment file in /src (execute from project root).\n  - Add the path to the credentials folder\n  - Add a path to the file that will be used to store the Google Drive token in.\n  - Add the location of the resume_schema\n  - Add the allowed image format\n\n```bash\ntouch ./src/.env\ncat << EOT >> ./src/.env\nCREDENTIALS_FILENAME=/path/to/secrets/credentials.json\nTOKEN_FILENAME=/path/to/secrets/token.json\nSCHEMA_FILENAME=/path/to/resume_schema.yaml\nIMAGE_FORMATS=\'["image/png","image/jpeg","image/jpg"]\'\nEOT\n```\n\n---\n\n## Usage\n\nCurrently, the tool only supports Word templates.\n\nThere is 1 non-optional argument, namely the location of the resume (yaml-file) on your disk.\n\n### Local template, local target\n\n- Use a local template on disk\n- Store the template locally on disk\n\nExample usage:\n\n```bash\npython main.py /path/to/resume.yaml --template_location /path/to/template.docx --target_location /path/to/target.docx\n```\n\n### Local template, target on drive\n\n- Use a local template on disk\n- Store the template on your google drive.\n  - If we do no specify `target_location`, the generated file is sent to Google Drive\n\nExample usage:\n\n```bash\npython main.py /path/to/resume.yaml --template_location /path/to/template.docx\n```\n\n### Template on drive\n\n- Use a template from your drive\n- This is done by passing the name of the docx-template (without the extension) to the command\n\nExample usage:\n\n```bash\npython main.py /path/to/resume.yaml --template_name name-of-template-on-drive\n```\n\n### Verbosity\n\nVerbosity can be enabled by passing the `--verbose`- or `-v`-flag to the tool.\n',
     'author': 'Tim Van Erum',
     'author_email': 'tim.vanerum@dataroots.io',
     'maintainer': None,
     'maintainer_email': None,
     'url': None,
```

### Comparing `resume-as-code-0.0.8/PKG-INFO` & `resume-as-code-0.0.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: resume-as-code
-Version: 0.0.8
+Version: 0.0.9
 Summary: A tool for automatic resume generation based on Jinja-Word-templates and YAML-files
 Author: Tim Van Erum
 Author-email: tim.vanerum@dataroots.io
 Requires-Python: >=3.6.0,<4.0.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.6
```


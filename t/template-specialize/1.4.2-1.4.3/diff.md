# Comparing `tmp/template-specialize-1.4.2.tar.gz` & `tmp/template-specialize-1.4.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "template-specialize-1.4.2.tar", last modified: Mon Oct 31 17:50:05 2022, max compression
+gzip compressed data, was "template-specialize-1.4.3.tar", last modified: Wed Jun 28 14:33:05 2023, max compression
```

## Comparing `template-specialize-1.4.2.tar` & `template-specialize-1.4.3.tar`

### file list

```diff
@@ -1,19 +1,19 @@
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:50:05.271580 template-specialize-1.4.2/
--rw-r--r--   0       20 dialout     (20)     1081 2022-10-27 21:45:04.000000 template-specialize-1.4.2/LICENSE
--rw-r--r--   0       20 dialout     (20)     7046 2022-10-31 17:50:05.271735 template-specialize-1.4.2/PKG-INFO
--rw-r--r--   0       20 dialout     (20)     6203 2022-10-27 21:45:04.000000 template-specialize-1.4.2/README.md
--rw-r--r--   0       20 dialout     (20)       50 2022-10-30 15:02:13.000000 template-specialize-1.4.2/pyproject.toml
--rw-r--r--   0       20 dialout     (20)      998 2022-10-31 17:50:05.272338 template-specialize-1.4.2/setup.cfg
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:50:05.260203 template-specialize-1.4.2/src/
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:50:05.267738 template-specialize-1.4.2/src/template_specialize/
--rw-r--r--   0       20 dialout     (20)      104 2022-10-27 21:45:04.000000 template-specialize-1.4.2/src/template_specialize/__init__.py
--rw-r--r--   0       20 dialout     (20)      245 2022-10-27 21:45:04.000000 template-specialize-1.4.2/src/template_specialize/__main__.py
--rw-r--r--   0       20 dialout     (20)     1685 2022-10-27 21:45:04.000000 template-specialize-1.4.2/src/template_specialize/aws_parameter_store.py
--rw-r--r--   0       20 dialout     (20)    10418 2022-10-27 21:45:04.000000 template-specialize-1.4.2/src/template_specialize/main.py
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:50:05.271221 template-specialize-1.4.2/src/template_specialize.egg-info/
--rw-r--r--   0       20 dialout     (20)     7046 2022-10-31 17:50:05.000000 template-specialize-1.4.2/src/template_specialize.egg-info/PKG-INFO
--rw-r--r--   0       20 dialout     (20)      477 2022-10-31 17:50:05.000000 template-specialize-1.4.2/src/template_specialize.egg-info/SOURCES.txt
--rw-r--r--   0       20 dialout     (20)        1 2022-10-31 17:50:05.000000 template-specialize-1.4.2/src/template_specialize.egg-info/dependency_links.txt
--rw-r--r--   0       20 dialout     (20)       70 2022-10-31 17:50:05.000000 template-specialize-1.4.2/src/template_specialize.egg-info/entry_points.txt
--rw-r--r--   0       20 dialout     (20)       13 2022-10-31 17:50:05.000000 template-specialize-1.4.2/src/template_specialize.egg-info/requires.txt
--rw-r--r--   0       20 dialout     (20)       20 2022-10-31 17:50:05.000000 template-specialize-1.4.2/src/template_specialize.egg-info/top_level.txt
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:33:05.777498 template-specialize-1.4.3/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1081 2023-06-11 21:05:16.000000 template-specialize-1.4.3/LICENSE
+-rw-r--r--   0 craighobbs   (501) staff       (20)     7228 2023-06-28 14:33:05.777570 template-specialize-1.4.3/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)     6384 2023-06-11 21:05:16.000000 template-specialize-1.4.3/README.md
+-rw-r--r--   0 craighobbs   (501) staff       (20)       50 2023-06-11 21:05:16.000000 template-specialize-1.4.3/pyproject.toml
+-rw-r--r--   0 craighobbs   (501) staff       (20)      999 2023-06-28 14:33:05.777864 template-specialize-1.4.3/setup.cfg
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:33:05.775302 template-specialize-1.4.3/src/
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:33:05.776534 template-specialize-1.4.3/src/template_specialize/
+-rw-r--r--   0 craighobbs   (501) staff       (20)      104 2023-06-11 21:05:16.000000 template-specialize-1.4.3/src/template_specialize/__init__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)      245 2023-06-11 21:05:16.000000 template-specialize-1.4.3/src/template_specialize/__main__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1685 2023-06-11 21:05:16.000000 template-specialize-1.4.3/src/template_specialize/aws_parameter_store.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)    10418 2023-06-11 21:05:16.000000 template-specialize-1.4.3/src/template_specialize/main.py
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:33:05.777380 template-specialize-1.4.3/src/template_specialize.egg-info/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     7228 2023-06-28 14:33:05.000000 template-specialize-1.4.3/src/template_specialize.egg-info/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)      477 2023-06-28 14:33:05.000000 template-specialize-1.4.3/src/template_specialize.egg-info/SOURCES.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)        1 2023-06-28 14:33:05.000000 template-specialize-1.4.3/src/template_specialize.egg-info/dependency_links.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       70 2023-06-28 14:33:05.000000 template-specialize-1.4.3/src/template_specialize.egg-info/entry_points.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       13 2023-06-28 14:33:05.000000 template-specialize-1.4.3/src/template_specialize.egg-info/requires.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       20 2023-06-28 14:33:05.000000 template-specialize-1.4.3/src/template_specialize.egg-info/top_level.txt
```

### Comparing `template-specialize-1.4.2/LICENSE` & `template-specialize-1.4.3/LICENSE`

 * *Files identical despite different names*

### Comparing `template-specialize-1.4.2/PKG-INFO` & `template-specialize-1.4.3/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,25 +1,25 @@
 Metadata-Version: 2.1
 Name: template-specialize
-Version: 1.4.2
+Version: 1.4.3
 Summary: Command-line tool for rendering Jinja2 templates
 Home-page: https://github.com/craigahobbs/template-specialize
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: jinja2,template,render,specialize
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Topic :: Utilities
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # template-specialize
 
 [![PyPI - Status](https://img.shields.io/pypi/status/template-specialize)](https://pypi.org/project/template-specialize/)
@@ -27,55 +27,66 @@
 [![GitHub](https://img.shields.io/github/license/craigahobbs/template-specialize)](https://github.com/craigahobbs/template-specialize/blob/main/LICENSE)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/template-specialize)](https://pypi.org/project/template-specialize/)
 
 **template-specialize** is a command-line tool for rendering
 [Jinja2](https://jinja.palletsprojects.com/en/3.0.x/templates/)
 templates.
 
+
+## Links
+
+- [Source code](https://github.com/craigahobbs/template-specialize)
+
+
+## Render a Template File
+
 For example, consider this Markdown name tag template, "nametag.md":
 
-``` jinja2
+~~~ jinja2
 ## Hello, my name is
 
 # {{name}}
 {% if title is defined %}
 ### {{title}}
 {% endif %}
-```
+~~~
 
 To render the template, execute template-specialize as follows:
 
-```
+~~~
 $ template-specialize nametag.md nametag-roy.md -k name 'Roy Hobbs' -k title 'The best there ever was'
-```
+~~~
 
 Afterward, the output file contains the rendered template:
 
-```
+~~~
 ## Hello, my name is
 
 # Roy Hobbs
 
 ### The best there ever was
-```
+~~~
+
+
+## Render a Directory Template
 
 You can also render directories of templates to an output directory:
 
-```
+~~~
 $ template-specialize template/ output/ -k name value
-```
+~~~
 
 
 ## Environment Files
 
 template-specialize was originally created to "specialize" web service configuration files for different runtime
 environments. Environment files are JSON files that allow for the definition of inheritable, structured template
 configuration values. Consider the following environments file:
 
-``` javascript
+~~~ javascript
 {
     "base": {
         "values": {
             "service_name": "my-service"
         }
     },
     "test_base": {
@@ -98,135 +109,137 @@
         "parents": ["base"],
         "values": {
             "db_host": "live-db-host",
             "db_name": "live-db"
         }
     }
 }
-```
+~~~
 
 To render a template file using an environment, specify the environment file (or files) and the environment name with
 which to render the template:
 
-```
+~~~
 $ template-specialize config-template.json config.json -c environments.json -e test
-```
+~~~
 
 To view the template configuration data use the "--dump" argument:
 
-```
+~~~
 $ template-specialize config-template.json config.json -c environments.json -e test --dump
 {
     "db_host": "test-db-host",
     "db_name": "test-db",
     "service_name": "my-service"
 }
-```
+~~~
 
 
 ## Renaming and Deleting Output Files
 
 When specializing a template directory, it is sometimes necessary to rename an output file or directory. For example,
 consider a Python project template with the following structure:
 
-```
+~~~
 .
 |-- README.md
 |-- package-name.txt
-|-- setup.py
+|-- pyproject.toml
+|-- setup.cfg
 `-- src
     |-- __init__.py
     |-- package_name
     |   |-- __init__.py
     |   `-- package_name.py
     `-- tests
         |-- __init__.py
         `-- test_package_name.py
-```
+~~~
 
 As part of the specialization, we'd like to rename the "package_name" directory, the "package_name.py" file, and the
 "test_package_name.py" file to the specialized package name. To accomplish this, we add the "package-name.txt' utility
 file and call the "template_specialize_rename" Jinja2 extension:
 
-``` jinja2
+~~~ jinja2
 {# Rename template files #}
 {% template_specialize_rename 'src/tests/test_package_name.py', 'test_' + package_name + '.py' %}
 {% template_specialize_rename 'src/package_name/package_name.py', package_name + '.py' %}
 {% template_specialize_rename 'src/package_name', package_name %}
 
 {# Delete the package-name.txt utility template file #}
 {% template_specialize_rename 'package-name.txt' %}
-```
+~~~
 
 First, the "template_specialize_rename" extension is used to rename the package output files and directories. Finally,
 since we don't want the empty utility file in the output, we delete it using the "template_specialize_rename" extension
 with no second argument. Here's an example usage of our Python project template:
 
-```
+~~~
 $ template-specialize python-package my-package -k package_name my_package
-```
+~~~
 
 This command produces the following specialized template output with appropriately named package source directory and
 source files:
 
-```
+~~~
 .
 |-- README.md
-|-- setup.py
+|-- pyproject.toml
+|-- setup.cfg
 `-- src
     |-- __init__.py
     |-- my_package
     |   |-- __init__.py
     |   `-- my_package.py
     `-- tests
         |-- __init__.py
         `-- test_my_package.py
-```
+~~~
 
 
 ## AWS Parameter Store
 
 template-specialize can retrieve template values from
 [AWS Parameter Store](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html)
 using
 [botocore](https://pypi.org/project/botocore/).
 
 Here's an example of a JSON configuration file with a Parameter Store secret:
 
-``` jinja2
+~~~ jinja2
 {
     "my_secret": {% filter tojson %}{% aws_parameter_store 'parameter-name' %}{% endfilter %}
 }
-```
+~~~
 
 botocore is usually configured using
 [environment variables](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/configuration.html#using-environment-variables).
 
 
 ## Usage
 
-```
+~~~
 usage: template-specialize [-h] [-c FILE] [-e ENV] [-k KEY VALUE] [--dump]
                            SRC DST
 
 positional arguments:
   SRC                   the source template file or directory
   DST                   the destination file or directory
 
 options:
   -h, --help            show this help message and exit
   -c FILE               the environment files
   -e ENV                the environment name
   -k KEY VALUE, --key KEY VALUE
                         add a template key and value
   --dump                dump the template variables
-```
+~~~
 
 
 ## Development
 
-This project is developed using [python-build](https://github.com/craigahobbs/python-build#readme). It was started
-using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
+This package is developed using [python-build](https://github.com/craigahobbs/python-build#readme).
+It was started using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
 
-```
+~~~
 template-specialize python-template/template/ template-specialize/ -k package template-specialize -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k noapi 1
-```
+~~~
```

### Comparing `template-specialize-1.4.2/README.md` & `template-specialize-1.4.3/README.md`

 * *Files 7% similar despite different names*

```diff
@@ -5,55 +5,66 @@
 [![GitHub](https://img.shields.io/github/license/craigahobbs/template-specialize)](https://github.com/craigahobbs/template-specialize/blob/main/LICENSE)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/template-specialize)](https://pypi.org/project/template-specialize/)
 
 **template-specialize** is a command-line tool for rendering
 [Jinja2](https://jinja.palletsprojects.com/en/3.0.x/templates/)
 templates.
 
+
+## Links
+
+- [Source code](https://github.com/craigahobbs/template-specialize)
+
+
+## Render a Template File
+
 For example, consider this Markdown name tag template, "nametag.md":
 
-``` jinja2
+~~~ jinja2
 ## Hello, my name is
 
 # {{name}}
 {% if title is defined %}
 ### {{title}}
 {% endif %}
-```
+~~~
 
 To render the template, execute template-specialize as follows:
 
-```
+~~~
 $ template-specialize nametag.md nametag-roy.md -k name 'Roy Hobbs' -k title 'The best there ever was'
-```
+~~~
 
 Afterward, the output file contains the rendered template:
 
-```
+~~~
 ## Hello, my name is
 
 # Roy Hobbs
 
 ### The best there ever was
-```
+~~~
+
+
+## Render a Directory Template
 
 You can also render directories of templates to an output directory:
 
-```
+~~~
 $ template-specialize template/ output/ -k name value
-```
+~~~
 
 
 ## Environment Files
 
 template-specialize was originally created to "specialize" web service configuration files for different runtime
 environments. Environment files are JSON files that allow for the definition of inheritable, structured template
 configuration values. Consider the following environments file:
 
-``` javascript
+~~~ javascript
 {
     "base": {
         "values": {
             "service_name": "my-service"
         }
     },
     "test_base": {
@@ -76,135 +87,137 @@
         "parents": ["base"],
         "values": {
             "db_host": "live-db-host",
             "db_name": "live-db"
         }
     }
 }
-```
+~~~
 
 To render a template file using an environment, specify the environment file (or files) and the environment name with
 which to render the template:
 
-```
+~~~
 $ template-specialize config-template.json config.json -c environments.json -e test
-```
+~~~
 
 To view the template configuration data use the "--dump" argument:
 
-```
+~~~
 $ template-specialize config-template.json config.json -c environments.json -e test --dump
 {
     "db_host": "test-db-host",
     "db_name": "test-db",
     "service_name": "my-service"
 }
-```
+~~~
 
 
 ## Renaming and Deleting Output Files
 
 When specializing a template directory, it is sometimes necessary to rename an output file or directory. For example,
 consider a Python project template with the following structure:
 
-```
+~~~
 .
 |-- README.md
 |-- package-name.txt
-|-- setup.py
+|-- pyproject.toml
+|-- setup.cfg
 `-- src
     |-- __init__.py
     |-- package_name
     |   |-- __init__.py
     |   `-- package_name.py
     `-- tests
         |-- __init__.py
         `-- test_package_name.py
-```
+~~~
 
 As part of the specialization, we'd like to rename the "package_name" directory, the "package_name.py" file, and the
 "test_package_name.py" file to the specialized package name. To accomplish this, we add the "package-name.txt' utility
 file and call the "template_specialize_rename" Jinja2 extension:
 
-``` jinja2
+~~~ jinja2
 {# Rename template files #}
 {% template_specialize_rename 'src/tests/test_package_name.py', 'test_' + package_name + '.py' %}
 {% template_specialize_rename 'src/package_name/package_name.py', package_name + '.py' %}
 {% template_specialize_rename 'src/package_name', package_name %}
 
 {# Delete the package-name.txt utility template file #}
 {% template_specialize_rename 'package-name.txt' %}
-```
+~~~
 
 First, the "template_specialize_rename" extension is used to rename the package output files and directories. Finally,
 since we don't want the empty utility file in the output, we delete it using the "template_specialize_rename" extension
 with no second argument. Here's an example usage of our Python project template:
 
-```
+~~~
 $ template-specialize python-package my-package -k package_name my_package
-```
+~~~
 
 This command produces the following specialized template output with appropriately named package source directory and
 source files:
 
-```
+~~~
 .
 |-- README.md
-|-- setup.py
+|-- pyproject.toml
+|-- setup.cfg
 `-- src
     |-- __init__.py
     |-- my_package
     |   |-- __init__.py
     |   `-- my_package.py
     `-- tests
         |-- __init__.py
         `-- test_my_package.py
-```
+~~~
 
 
 ## AWS Parameter Store
 
 template-specialize can retrieve template values from
 [AWS Parameter Store](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html)
 using
 [botocore](https://pypi.org/project/botocore/).
 
 Here's an example of a JSON configuration file with a Parameter Store secret:
 
-``` jinja2
+~~~ jinja2
 {
     "my_secret": {% filter tojson %}{% aws_parameter_store 'parameter-name' %}{% endfilter %}
 }
-```
+~~~
 
 botocore is usually configured using
 [environment variables](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/configuration.html#using-environment-variables).
 
 
 ## Usage
 
-```
+~~~
 usage: template-specialize [-h] [-c FILE] [-e ENV] [-k KEY VALUE] [--dump]
                            SRC DST
 
 positional arguments:
   SRC                   the source template file or directory
   DST                   the destination file or directory
 
 options:
   -h, --help            show this help message and exit
   -c FILE               the environment files
   -e ENV                the environment name
   -k KEY VALUE, --key KEY VALUE
                         add a template key and value
   --dump                dump the template variables
-```
+~~~
 
 
 ## Development
 
-This project is developed using [python-build](https://github.com/craigahobbs/python-build#readme). It was started
-using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
+This package is developed using [python-build](https://github.com/craigahobbs/python-build#readme).
+It was started using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
 
-```
+~~~
 template-specialize python-template/template/ template-specialize/ -k package template-specialize -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k noapi 1
-```
+~~~
```

### Comparing `template-specialize-1.4.2/setup.cfg` & `template-specialize-1.4.3/setup.cfg`

 * *Files 10% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 [metadata]
 name = template-specialize
-version = 1.4.2
+version = 1.4.3
 url = https://github.com/craigahobbs/template-specialize
 author = Craig A. Hobbs
 author_email = craigahobbs@gmail.com
 license = MIT
 description = Command-line tool for rendering Jinja2 templates
 long_description = file:README.md
 long_description_content_type = text/markdown
 keywords = jinja2, template, render, specialize
 classifiers = 
 	Development Status :: 5 - Production/Stable
 	Intended Audience :: Developers
 	License :: OSI Approved :: MIT License
 	Operating System :: OS Independent
-	Programming Language :: Python :: 3.7
 	Programming Language :: Python :: 3.8
 	Programming Language :: Python :: 3.9
 	Programming Language :: Python :: 3.10
 	Programming Language :: Python :: 3.11
+	Programming Language :: Python :: 3.12
 	Topic :: Utilities
 
 [options]
 packages = template_specialize
 package_dir = 
 	= src
 install_requires =
```

### Comparing `template-specialize-1.4.2/src/template_specialize/aws_parameter_store.py` & `template-specialize-1.4.3/src/template_specialize/aws_parameter_store.py`

 * *Files identical despite different names*

### Comparing `template-specialize-1.4.2/src/template_specialize/main.py` & `template-specialize-1.4.3/src/template_specialize/main.py`

 * *Files identical despite different names*

### Comparing `template-specialize-1.4.2/src/template_specialize.egg-info/PKG-INFO` & `template-specialize-1.4.3/src/template_specialize.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,25 +1,25 @@
 Metadata-Version: 2.1
 Name: template-specialize
-Version: 1.4.2
+Version: 1.4.3
 Summary: Command-line tool for rendering Jinja2 templates
 Home-page: https://github.com/craigahobbs/template-specialize
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: jinja2,template,render,specialize
 Classifier: Development Status :: 5 - Production/Stable
 Classifier: Intended Audience :: Developers
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
-Classifier: Programming Language :: Python :: 3.7
 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
+Classifier: Programming Language :: Python :: 3.12
 Classifier: Topic :: Utilities
 Description-Content-Type: text/markdown
 License-File: LICENSE
 
 # template-specialize
 
 [![PyPI - Status](https://img.shields.io/pypi/status/template-specialize)](https://pypi.org/project/template-specialize/)
@@ -27,55 +27,66 @@
 [![GitHub](https://img.shields.io/github/license/craigahobbs/template-specialize)](https://github.com/craigahobbs/template-specialize/blob/main/LICENSE)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/template-specialize)](https://pypi.org/project/template-specialize/)
 
 **template-specialize** is a command-line tool for rendering
 [Jinja2](https://jinja.palletsprojects.com/en/3.0.x/templates/)
 templates.
 
+
+## Links
+
+- [Source code](https://github.com/craigahobbs/template-specialize)
+
+
+## Render a Template File
+
 For example, consider this Markdown name tag template, "nametag.md":
 
-``` jinja2
+~~~ jinja2
 ## Hello, my name is
 
 # {{name}}
 {% if title is defined %}
 ### {{title}}
 {% endif %}
-```
+~~~
 
 To render the template, execute template-specialize as follows:
 
-```
+~~~
 $ template-specialize nametag.md nametag-roy.md -k name 'Roy Hobbs' -k title 'The best there ever was'
-```
+~~~
 
 Afterward, the output file contains the rendered template:
 
-```
+~~~
 ## Hello, my name is
 
 # Roy Hobbs
 
 ### The best there ever was
-```
+~~~
+
+
+## Render a Directory Template
 
 You can also render directories of templates to an output directory:
 
-```
+~~~
 $ template-specialize template/ output/ -k name value
-```
+~~~
 
 
 ## Environment Files
 
 template-specialize was originally created to "specialize" web service configuration files for different runtime
 environments. Environment files are JSON files that allow for the definition of inheritable, structured template
 configuration values. Consider the following environments file:
 
-``` javascript
+~~~ javascript
 {
     "base": {
         "values": {
             "service_name": "my-service"
         }
     },
     "test_base": {
@@ -98,135 +109,137 @@
         "parents": ["base"],
         "values": {
             "db_host": "live-db-host",
             "db_name": "live-db"
         }
     }
 }
-```
+~~~
 
 To render a template file using an environment, specify the environment file (or files) and the environment name with
 which to render the template:
 
-```
+~~~
 $ template-specialize config-template.json config.json -c environments.json -e test
-```
+~~~
 
 To view the template configuration data use the "--dump" argument:
 
-```
+~~~
 $ template-specialize config-template.json config.json -c environments.json -e test --dump
 {
     "db_host": "test-db-host",
     "db_name": "test-db",
     "service_name": "my-service"
 }
-```
+~~~
 
 
 ## Renaming and Deleting Output Files
 
 When specializing a template directory, it is sometimes necessary to rename an output file or directory. For example,
 consider a Python project template with the following structure:
 
-```
+~~~
 .
 |-- README.md
 |-- package-name.txt
-|-- setup.py
+|-- pyproject.toml
+|-- setup.cfg
 `-- src
     |-- __init__.py
     |-- package_name
     |   |-- __init__.py
     |   `-- package_name.py
     `-- tests
         |-- __init__.py
         `-- test_package_name.py
-```
+~~~
 
 As part of the specialization, we'd like to rename the "package_name" directory, the "package_name.py" file, and the
 "test_package_name.py" file to the specialized package name. To accomplish this, we add the "package-name.txt' utility
 file and call the "template_specialize_rename" Jinja2 extension:
 
-``` jinja2
+~~~ jinja2
 {# Rename template files #}
 {% template_specialize_rename 'src/tests/test_package_name.py', 'test_' + package_name + '.py' %}
 {% template_specialize_rename 'src/package_name/package_name.py', package_name + '.py' %}
 {% template_specialize_rename 'src/package_name', package_name %}
 
 {# Delete the package-name.txt utility template file #}
 {% template_specialize_rename 'package-name.txt' %}
-```
+~~~
 
 First, the "template_specialize_rename" extension is used to rename the package output files and directories. Finally,
 since we don't want the empty utility file in the output, we delete it using the "template_specialize_rename" extension
 with no second argument. Here's an example usage of our Python project template:
 
-```
+~~~
 $ template-specialize python-package my-package -k package_name my_package
-```
+~~~
 
 This command produces the following specialized template output with appropriately named package source directory and
 source files:
 
-```
+~~~
 .
 |-- README.md
-|-- setup.py
+|-- pyproject.toml
+|-- setup.cfg
 `-- src
     |-- __init__.py
     |-- my_package
     |   |-- __init__.py
     |   `-- my_package.py
     `-- tests
         |-- __init__.py
         `-- test_my_package.py
-```
+~~~
 
 
 ## AWS Parameter Store
 
 template-specialize can retrieve template values from
 [AWS Parameter Store](https://docs.aws.amazon.com/systems-manager/latest/userguide/systems-manager-parameter-store.html)
 using
 [botocore](https://pypi.org/project/botocore/).
 
 Here's an example of a JSON configuration file with a Parameter Store secret:
 
-``` jinja2
+~~~ jinja2
 {
     "my_secret": {% filter tojson %}{% aws_parameter_store 'parameter-name' %}{% endfilter %}
 }
-```
+~~~
 
 botocore is usually configured using
 [environment variables](https://boto3.amazonaws.com/v1/documentation/api/latest/guide/configuration.html#using-environment-variables).
 
 
 ## Usage
 
-```
+~~~
 usage: template-specialize [-h] [-c FILE] [-e ENV] [-k KEY VALUE] [--dump]
                            SRC DST
 
 positional arguments:
   SRC                   the source template file or directory
   DST                   the destination file or directory
 
 options:
   -h, --help            show this help message and exit
   -c FILE               the environment files
   -e ENV                the environment name
   -k KEY VALUE, --key KEY VALUE
                         add a template key and value
   --dump                dump the template variables
-```
+~~~
 
 
 ## Development
 
-This project is developed using [python-build](https://github.com/craigahobbs/python-build#readme). It was started
-using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
+This package is developed using [python-build](https://github.com/craigahobbs/python-build#readme).
+It was started using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
 
-```
+~~~
 template-specialize python-template/template/ template-specialize/ -k package template-specialize -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k noapi 1
-```
+~~~
```


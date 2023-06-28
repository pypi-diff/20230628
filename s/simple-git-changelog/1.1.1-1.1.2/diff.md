# Comparing `tmp/simple-git-changelog-1.1.1.tar.gz` & `tmp/simple-git-changelog-1.1.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "simple-git-changelog-1.1.1.tar", last modified: Mon Oct 31 17:44:15 2022, max compression
+gzip compressed data, was "simple-git-changelog-1.1.2.tar", last modified: Wed Jun 28 14:30:58 2023, max compression
```

## Comparing `simple-git-changelog-1.1.1.tar` & `simple-git-changelog-1.1.2.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:44:15.550124 simple-git-changelog-1.1.1/
--rw-r--r--   0       20 dialout     (20)     1081 2022-10-27 21:45:03.000000 simple-git-changelog-1.1.1/LICENSE
--rw-r--r--   0       20 dialout     (20)     3044 2022-10-31 17:44:15.550343 simple-git-changelog-1.1.1/PKG-INFO
--rw-r--r--   0       20 dialout     (20)     2232 2022-10-27 21:45:03.000000 simple-git-changelog-1.1.1/README.md
--rw-r--r--   0       20 dialout     (20)       50 2022-10-30 14:58:04.000000 simple-git-changelog-1.1.1/pyproject.toml
--rw-r--r--   0       20 dialout     (20)      932 2022-10-31 17:44:15.551103 simple-git-changelog-1.1.1/setup.cfg
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:44:15.538084 simple-git-changelog-1.1.1/src/
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:44:15.545296 simple-git-changelog-1.1.1/src/simple_git_changelog/
--rw-r--r--   0       20 dialout     (20)      105 2022-10-27 21:45:03.000000 simple-git-changelog-1.1.1/src/simple_git_changelog/__init__.py
--rw-r--r--   0       20 dialout     (20)      247 2022-10-27 21:45:03.000000 simple-git-changelog-1.1.1/src/simple_git_changelog/__main__.py
--rw-r--r--   0       20 dialout     (20)     3334 2022-10-27 21:45:03.000000 simple-git-changelog-1.1.1/src/simple_git_changelog/main.py
-drwxr-xr-x   0       20 dialout     (20)        0 2022-10-31 17:44:15.549556 simple-git-changelog-1.1.1/src/simple_git_changelog.egg-info/
--rw-r--r--   0       20 dialout     (20)     3044 2022-10-31 17:44:15.000000 simple-git-changelog-1.1.1/src/simple_git_changelog.egg-info/PKG-INFO
--rw-r--r--   0       20 dialout     (20)      392 2022-10-31 17:44:15.000000 simple-git-changelog-1.1.1/src/simple_git_changelog.egg-info/SOURCES.txt
--rw-r--r--   0       20 dialout     (20)        1 2022-10-31 17:44:15.000000 simple-git-changelog-1.1.1/src/simple_git_changelog.egg-info/dependency_links.txt
--rw-r--r--   0       20 dialout     (20)       72 2022-10-31 17:44:15.000000 simple-git-changelog-1.1.1/src/simple_git_changelog.egg-info/entry_points.txt
--rw-r--r--   0       20 dialout     (20)       21 2022-10-31 17:44:15.000000 simple-git-changelog-1.1.1/src/simple_git_changelog.egg-info/top_level.txt
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:30:58.251566 simple-git-changelog-1.1.2/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     1081 2023-06-11 21:05:16.000000 simple-git-changelog-1.1.2/LICENSE
+-rw-r--r--   0 craighobbs   (501) staff       (20)     3246 2023-06-28 14:30:58.251615 simple-git-changelog-1.1.2/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)     2433 2023-06-11 21:05:16.000000 simple-git-changelog-1.1.2/README.md
+-rw-r--r--   0 craighobbs   (501) staff       (20)       50 2023-06-11 21:05:16.000000 simple-git-changelog-1.1.2/pyproject.toml
+-rw-r--r--   0 craighobbs   (501) staff       (20)      933 2023-06-28 14:30:58.251840 simple-git-changelog-1.1.2/setup.cfg
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:30:58.250150 simple-git-changelog-1.1.2/src/
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:30:58.250919 simple-git-changelog-1.1.2/src/simple_git_changelog/
+-rw-r--r--   0 craighobbs   (501) staff       (20)      105 2023-06-11 21:05:16.000000 simple-git-changelog-1.1.2/src/simple_git_changelog/__init__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)      247 2023-06-11 21:05:16.000000 simple-git-changelog-1.1.2/src/simple_git_changelog/__main__.py
+-rw-r--r--   0 craighobbs   (501) staff       (20)     3334 2023-06-11 21:05:16.000000 simple-git-changelog-1.1.2/src/simple_git_changelog/main.py
+drwxr-xr-x   0 craighobbs   (501) staff       (20)        0 2023-06-28 14:30:58.251475 simple-git-changelog-1.1.2/src/simple_git_changelog.egg-info/
+-rw-r--r--   0 craighobbs   (501) staff       (20)     3246 2023-06-28 14:30:58.000000 simple-git-changelog-1.1.2/src/simple_git_changelog.egg-info/PKG-INFO
+-rw-r--r--   0 craighobbs   (501) staff       (20)      392 2023-06-28 14:30:58.000000 simple-git-changelog-1.1.2/src/simple_git_changelog.egg-info/SOURCES.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)        1 2023-06-28 14:30:58.000000 simple-git-changelog-1.1.2/src/simple_git_changelog.egg-info/dependency_links.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       72 2023-06-28 14:30:58.000000 simple-git-changelog-1.1.2/src/simple_git_changelog.egg-info/entry_points.txt
+-rw-r--r--   0 craighobbs   (501) staff       (20)       21 2023-06-28 14:30:58.000000 simple-git-changelog-1.1.2/src/simple_git_changelog.egg-info/top_level.txt
```

### Comparing `simple-git-changelog-1.1.1/LICENSE` & `simple-git-changelog-1.1.2/LICENSE`

 * *Files identical despite different names*

### Comparing `simple-git-changelog-1.1.1/PKG-INFO` & `simple-git-changelog-1.1.2/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,86 +1,101 @@
 Metadata-Version: 2.1
 Name: simple-git-changelog
-Version: 1.1.1
+Version: 1.1.2
 Summary: Simple git changelog file generator
 Home-page: https://github.com/craigahobbs/simple-git-changelog
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: git,changelog
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
 
 # simple-git-changelog
 
 [![PyPI - Status](https://img.shields.io/pypi/status/simple-git-changelog)](https://pypi.org/project/simple-git-changelog/)
 [![PyPI](https://img.shields.io/pypi/v/simple-git-changelog)](https://pypi.org/project/simple-git-changelog/)
 [![GitHub](https://img.shields.io/github/license/craigahobbs/simple-git-changelog)](https://github.com/craigahobbs/simple-git-changelog/blob/main/LICENSE)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/simple-git-changelog)](https://pypi.org/project/simple-git-changelog/)
 
 **simple-git-changelog** is a command-line tool for creating and updating a git project's changelog
 file.
 
+
+## Links
+
+- [Source code](https://github.com/craigahobbs/simple-git-changelog)
+
+
+## Create the Changelog File
+
 To create your project's changelog file, run simple-git-changelog in your project's root directory:
 
-``` sh
+~~~ sh
 $ simple-git-changelog
-```
+~~~
 
 By default, the "CHANGELOG.md" file is created with your project's changes. For example:
 
-``` markdown
+~~~ markdown
 # Changelog
 
 ## 2021-04-30
 
 - [abcdf0](https://github.com/username/project-name/commit/abcdf0) most recent change
 
 - [abcdef](https://github.com/username/project-name/commit/abcdef) previous change
-```
+~~~
 
-Edit "CHANGELOG.md" as appropriate and commit. To update your changelog file later, simply run
-simple-git-changelog again. Change items for new git changes are added to the top of the changelog:
+Edit "CHANGELOG.md" as appropriate and commit. Changes to the changelog title are maintained across
+updates.
 
-``` markdown
+
+## Update the Changelog File
+
+To update your changelog file, simply run simple-git-changelog again. Change items for new git
+changes are added to the top of the changelog:
+
+~~~ markdown
 # MyProject Changelog
 
 ## 2021-05-01
 
 - [abcdf1](https://github.com/username/project-name/commit/abcdf1) one more thing
 
 ## 2021-04-30
 
 - [abcdf0](https://github.com/username/project-name/commit/abcdf0) most recent change
 
 - [abcdef](https://github.com/username/project-name/commit/abcdef) previous change
-```
+~~~
 
 
 ## Usage
 
-```
+~~~
 usage: simple-git-changelog [-h] [-o FILE]
 
 options:
   -h, --help  show this help message and exit
   -o FILE     specify the change log file (default is "CHANGELOG.md")
-```
+~~~
+
 
 ## Development
 
-This project is developed using [python-build](https://github.com/craigahobbs/python-build#readme). It was started
-using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
+This package is developed using [python-build](https://github.com/craigahobbs/python-build#readme).
+It was started using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
 
-```
+~~~
 template-specialize python-template/template/ simple-git-changelog/ -k package simple-git-changelog -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k noapi 1
-```
+~~~
```

### Comparing `simple-git-changelog-1.1.1/README.md` & `simple-git-changelog-1.1.2/README.md`

 * *Files 12% similar despite different names*

```diff
@@ -4,61 +4,76 @@
 [![PyPI](https://img.shields.io/pypi/v/simple-git-changelog)](https://pypi.org/project/simple-git-changelog/)
 [![GitHub](https://img.shields.io/github/license/craigahobbs/simple-git-changelog)](https://github.com/craigahobbs/simple-git-changelog/blob/main/LICENSE)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/simple-git-changelog)](https://pypi.org/project/simple-git-changelog/)
 
 **simple-git-changelog** is a command-line tool for creating and updating a git project's changelog
 file.
 
+
+## Links
+
+- [Source code](https://github.com/craigahobbs/simple-git-changelog)
+
+
+## Create the Changelog File
+
 To create your project's changelog file, run simple-git-changelog in your project's root directory:
 
-``` sh
+~~~ sh
 $ simple-git-changelog
-```
+~~~
 
 By default, the "CHANGELOG.md" file is created with your project's changes. For example:
 
-``` markdown
+~~~ markdown
 # Changelog
 
 ## 2021-04-30
 
 - [abcdf0](https://github.com/username/project-name/commit/abcdf0) most recent change
 
 - [abcdef](https://github.com/username/project-name/commit/abcdef) previous change
-```
+~~~
 
-Edit "CHANGELOG.md" as appropriate and commit. To update your changelog file later, simply run
-simple-git-changelog again. Change items for new git changes are added to the top of the changelog:
+Edit "CHANGELOG.md" as appropriate and commit. Changes to the changelog title are maintained across
+updates.
 
-``` markdown
+
+## Update the Changelog File
+
+To update your changelog file, simply run simple-git-changelog again. Change items for new git
+changes are added to the top of the changelog:
+
+~~~ markdown
 # MyProject Changelog
 
 ## 2021-05-01
 
 - [abcdf1](https://github.com/username/project-name/commit/abcdf1) one more thing
 
 ## 2021-04-30
 
 - [abcdf0](https://github.com/username/project-name/commit/abcdf0) most recent change
 
 - [abcdef](https://github.com/username/project-name/commit/abcdef) previous change
-```
+~~~
 
 
 ## Usage
 
-```
+~~~
 usage: simple-git-changelog [-h] [-o FILE]
 
 options:
   -h, --help  show this help message and exit
   -o FILE     specify the change log file (default is "CHANGELOG.md")
-```
+~~~
+
 
 ## Development
 
-This project is developed using [python-build](https://github.com/craigahobbs/python-build#readme). It was started
-using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
+This package is developed using [python-build](https://github.com/craigahobbs/python-build#readme).
+It was started using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
 
-```
+~~~
 template-specialize python-template/template/ simple-git-changelog/ -k package simple-git-changelog -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k noapi 1
-```
+~~~
```

### Comparing `simple-git-changelog-1.1.1/setup.cfg` & `simple-git-changelog-1.1.2/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,28 +1,28 @@
 [metadata]
 name = simple-git-changelog
-version = 1.1.1
+version = 1.1.2
 url = https://github.com/craigahobbs/simple-git-changelog
 author = Craig A. Hobbs
 author_email = craigahobbs@gmail.com
 license = MIT
 description = Simple git changelog file generator
 long_description = file:README.md
 long_description_content_type = text/markdown
 keywords = git, changelog
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
 packages = simple_git_changelog
 package_dir = 
 	= src
```

### Comparing `simple-git-changelog-1.1.1/src/simple_git_changelog/main.py` & `simple-git-changelog-1.1.2/src/simple_git_changelog/main.py`

 * *Files identical despite different names*

### Comparing `simple-git-changelog-1.1.1/src/simple_git_changelog.egg-info/PKG-INFO` & `simple-git-changelog-1.1.2/src/simple_git_changelog.egg-info/PKG-INFO`

 * *Files 15% similar despite different names*

```diff
@@ -1,86 +1,101 @@
 Metadata-Version: 2.1
 Name: simple-git-changelog
-Version: 1.1.1
+Version: 1.1.2
 Summary: Simple git changelog file generator
 Home-page: https://github.com/craigahobbs/simple-git-changelog
 Author: Craig A. Hobbs
 Author-email: craigahobbs@gmail.com
 License: MIT
 Keywords: git,changelog
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
 
 # simple-git-changelog
 
 [![PyPI - Status](https://img.shields.io/pypi/status/simple-git-changelog)](https://pypi.org/project/simple-git-changelog/)
 [![PyPI](https://img.shields.io/pypi/v/simple-git-changelog)](https://pypi.org/project/simple-git-changelog/)
 [![GitHub](https://img.shields.io/github/license/craigahobbs/simple-git-changelog)](https://github.com/craigahobbs/simple-git-changelog/blob/main/LICENSE)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/simple-git-changelog)](https://pypi.org/project/simple-git-changelog/)
 
 **simple-git-changelog** is a command-line tool for creating and updating a git project's changelog
 file.
 
+
+## Links
+
+- [Source code](https://github.com/craigahobbs/simple-git-changelog)
+
+
+## Create the Changelog File
+
 To create your project's changelog file, run simple-git-changelog in your project's root directory:
 
-``` sh
+~~~ sh
 $ simple-git-changelog
-```
+~~~
 
 By default, the "CHANGELOG.md" file is created with your project's changes. For example:
 
-``` markdown
+~~~ markdown
 # Changelog
 
 ## 2021-04-30
 
 - [abcdf0](https://github.com/username/project-name/commit/abcdf0) most recent change
 
 - [abcdef](https://github.com/username/project-name/commit/abcdef) previous change
-```
+~~~
 
-Edit "CHANGELOG.md" as appropriate and commit. To update your changelog file later, simply run
-simple-git-changelog again. Change items for new git changes are added to the top of the changelog:
+Edit "CHANGELOG.md" as appropriate and commit. Changes to the changelog title are maintained across
+updates.
 
-``` markdown
+
+## Update the Changelog File
+
+To update your changelog file, simply run simple-git-changelog again. Change items for new git
+changes are added to the top of the changelog:
+
+~~~ markdown
 # MyProject Changelog
 
 ## 2021-05-01
 
 - [abcdf1](https://github.com/username/project-name/commit/abcdf1) one more thing
 
 ## 2021-04-30
 
 - [abcdf0](https://github.com/username/project-name/commit/abcdf0) most recent change
 
 - [abcdef](https://github.com/username/project-name/commit/abcdef) previous change
-```
+~~~
 
 
 ## Usage
 
-```
+~~~
 usage: simple-git-changelog [-h] [-o FILE]
 
 options:
   -h, --help  show this help message and exit
   -o FILE     specify the change log file (default is "CHANGELOG.md")
-```
+~~~
+
 
 ## Development
 
-This project is developed using [python-build](https://github.com/craigahobbs/python-build#readme). It was started
-using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
+This package is developed using [python-build](https://github.com/craigahobbs/python-build#readme).
+It was started using [python-template](https://github.com/craigahobbs/python-template#readme) as follows:
 
-```
+~~~
 template-specialize python-template/template/ simple-git-changelog/ -k package simple-git-changelog -k name 'Craig A. Hobbs' -k email 'craigahobbs@gmail.com' -k github 'craigahobbs' -k noapi 1
-```
+~~~
```


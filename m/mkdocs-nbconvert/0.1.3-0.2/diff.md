# Comparing `tmp/mkdocs-nbconvert-0.1.3.tar.gz` & `tmp/mkdocs-nbconvert-0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mkdocs-nbconvert-0.1.3.tar", last modified: Mon Apr 18 04:28:06 2022, max compression
+gzip compressed data, was "mkdocs-nbconvert-0.2.tar", last modified: Wed Jun 28 08:45:11 2023, max compression
```

## Comparing `mkdocs-nbconvert-0.1.3.tar` & `mkdocs-nbconvert-0.2.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxr-x   0 liuxy     (1000) liuxy     (1000)        0 2022-04-18 04:28:06.143003 mkdocs-nbconvert-0.1.3/
--rwxrwxrwx   0 liuxy     (1000) liuxy     (1000)       49 2019-08-05 11:14:05.000000 mkdocs-nbconvert-0.1.3/AUTHORS.md
--rw-rw-r--   0 liuxy     (1000) liuxy     (1000)      379 2022-04-18 04:27:23.000000 mkdocs-nbconvert-0.1.3/CHANGELOG.md
--rwxrwxrwx   0 liuxy     (1000) liuxy     (1000)       15 2019-08-05 11:14:05.000000 mkdocs-nbconvert-0.1.3/CONTRIBUTING.md
--rw-rw-r--   0 liuxy     (1000) liuxy     (1000)     1295 2022-04-18 04:27:15.000000 mkdocs-nbconvert-0.1.3/LICENSE
--rw-rw-r--   0 liuxy     (1000) liuxy     (1000)      480 2021-09-23 06:43:31.000000 mkdocs-nbconvert-0.1.3/MANIFEST.in
--rw-rw-r--   0 liuxy     (1000) liuxy     (1000)     2382 2022-04-18 04:28:06.143003 mkdocs-nbconvert-0.1.3/PKG-INFO
--rw-rw-r--   0 liuxy     (1000) liuxy     (1000)     1062 2022-04-18 04:27:15.000000 mkdocs-nbconvert-0.1.3/README.md
--rw-rw-r--   0 liuxy     (1000) liuxy     (1000)      293 2022-04-18 04:27:15.000000 mkdocs-nbconvert-0.1.3/pyproject.toml
--rw-rw-r--   0 liuxy     (1000) liuxy     (1000)     1120 2022-04-18 04:28:06.143003 mkdocs-nbconvert-0.1.3/setup.cfg
-drwxrwxr-x   0 liuxy     (1000) liuxy     (1000)        0 2022-04-18 04:28:06.139003 mkdocs-nbconvert-0.1.3/src/
-drwxrwxr-x   0 liuxy     (1000) liuxy     (1000)        0 2022-04-18 04:28:06.139003 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert/
--rwxrwxrwx   0 liuxy     (1000) liuxy     (1000)      120 2020-07-17 02:44:40.000000 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert/__init__.py
--rw-rw-r--   0 liuxy     (1000) liuxy     (1000)     4982 2022-04-18 04:27:15.000000 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert/plugin.py
--rwxrwxrwx   0 liuxy     (1000) liuxy     (1000)      142 2022-04-18 04:28:05.000000 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert/version.py
-drwxrwxr-x   0 liuxy     (1000) liuxy     (1000)        0 2022-04-18 04:28:06.143003 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert.egg-info/
--rwxrwxrwx   0 liuxy     (1000) liuxy     (1000)     2382 2022-04-18 04:28:05.000000 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert.egg-info/PKG-INFO
--rwxrwxrwx   0 liuxy     (1000) liuxy     (1000)      456 2022-04-18 04:28:06.000000 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert.egg-info/SOURCES.txt
--rwxrwxrwx   0 liuxy     (1000) liuxy     (1000)        1 2022-04-18 04:28:05.000000 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert.egg-info/dependency_links.txt
--rw-rw-r--   0 liuxy     (1000) liuxy     (1000)       62 2022-04-18 04:28:05.000000 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert.egg-info/entry_points.txt
--rwxrwxrwx   0 liuxy     (1000) liuxy     (1000)       17 2022-04-18 04:28:05.000000 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert.egg-info/requires.txt
--rwxrwxrwx   0 liuxy     (1000) liuxy     (1000)       17 2022-04-18 04:28:06.000000 mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 08:45:11.459754 mkdocs-nbconvert-0.2/
+-rw-rw-rw-   0        0        0       52 2023-06-28 03:05:47.000000 mkdocs-nbconvert-0.2/AUTHORS.md
+-rw-rw-rw-   0        0        0      737 2023-06-28 08:43:13.000000 mkdocs-nbconvert-0.2/CHANGELOG.md
+-rw-rw-rw-   0        0        0       16 2023-06-28 03:05:47.000000 mkdocs-nbconvert-0.2/CONTRIBUTING.md
+-rw-rw-rw-   0        0        0     1304 2023-06-28 03:05:47.000000 mkdocs-nbconvert-0.2/LICENSE
+-rw-rw-rw-   0        0        0      127 2023-06-28 08:42:45.000000 mkdocs-nbconvert-0.2/MANIFEST.in
+-rw-rw-rw-   0        0        0     1976 2023-06-28 08:45:11.458755 mkdocs-nbconvert-0.2/PKG-INFO
+-rw-rw-rw-   0        0        0     1067 2023-06-28 08:42:45.000000 mkdocs-nbconvert-0.2/README.md
+-rw-rw-rw-   0        0        0     1343 2023-06-28 08:42:45.000000 mkdocs-nbconvert-0.2/pyproject.toml
+-rw-rw-rw-   0        0        0       42 2023-06-28 08:45:11.459754 mkdocs-nbconvert-0.2/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-28 08:45:11.303756 mkdocs-nbconvert-0.2/src/
+drwxrwxrwx   0        0        0        0 2023-06-28 08:45:11.345756 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert/
+-rw-rw-rw-   0        0        0       88 2023-06-28 08:42:45.000000 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert/__init__.py
+-rw-rw-rw-   0        0        0     5962 2023-06-28 08:42:45.000000 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert/plugin.py
+-rw-rw-rw-   0        0        0      159 2023-06-28 08:45:06.000000 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert/version.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:45:11.456753 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert.egg-info/
+-rw-rw-rw-   0        0        0     1976 2023-06-28 08:45:07.000000 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      446 2023-06-28 08:45:11.000000 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:45:07.000000 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       62 2023-06-28 08:45:07.000000 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert.egg-info/entry_points.txt
+-rw-rw-rw-   0        0        0       17 2023-06-28 08:45:07.000000 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       17 2023-06-28 08:45:07.000000 mkdocs-nbconvert-0.2/src/mkdocs_nbconvert.egg-info/top_level.txt
```

### Comparing `mkdocs-nbconvert-0.1.3/LICENSE` & `mkdocs-nbconvert-0.2/LICENSE`

 * *Ordering differences only*

 * *Files 10% similar despite different names*

```diff
@@ -1,9 +1,9 @@
-Copyright 2019-present, Liu Xue Yan. All rights reserved.
-
-Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
-
-1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
-
-2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
-
-THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
+Copyright 2019-present, Liu Xue Yan. All rights reserved.
+
+Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:
+
+1. Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
+
+2. Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
+
+THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

### Comparing `mkdocs-nbconvert-0.1.3/PKG-INFO` & `mkdocs-nbconvert-0.2/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,83 +1,50 @@
-Metadata-Version: 2.1
-Name: mkdocs-nbconvert
-Version: 0.1.3
-Summary: A MkDocs plug-in provides a source parser for *.ipynb files
-Home-page: https://tanbro.github.io/mkdocs-nbconvert
-Author: liu xue yan
-Author-email: liu_xue_yan@foxmail.com
-License: BSD 3-Clause License
-Project-URL: Documentation, https://tanbro.github.io/mkdocs-nbconvert
-Project-URL: Source, https://github.com/tanbro/mkdocs-nbconvert
-Keywords: mkdocs,mkdocs-plugin,jupyter,notebook,jupyter-notebook,markdown,md,nbconvert
-Platform: UNKNOWN
-Classifier: License :: OSI Approved :: BSD License
-Classifier: Development Status :: 4 - Beta
-Classifier: Topic :: Documentation
-Classifier: Intended Audience :: Developers
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3 :: Only
-Requires-Python: >=3.6
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
-# mkdocs-nbconvert
-
-[![PyPI](https://img.shields.io/pypi/v/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
-[![PyPI - Status](https://img.shields.io/pypi/status/mkdocs-nbconvert)](https://pypi.org/project/mkdocs-nbconvert/)
-[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
-[![PyPI - Format](https://img.shields.io/pypi/format/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
-
-A [MkDocs][] plug-in provides a source parser for `*.ipynb` [Jupyter][] Notebook files, base on [nbconvert][].
-
-## Features
-
-- doc: <https://tanbro.github.io/mkdocs-nbconvert/>
-- ref: <https://www.mkdocs.org/user-guide/plugins/>
-
-## Build the documentation
-
-The project itself's documentation site is a demo of how to use is in [MkDocs][].
-
-To serve it:
-
-```bash
-mkdocs serve -a 127.0.0.1:8080
-```
-
-Then open `http://127.0.0.1:8080` with your browser.
-
-[MkDocs]: http://www.mkdocs.org/
-[Jupyter]: https://jupyter.org/
-[nbconvert]: https://pypi.org/project/nbconvert/
-
-# Contributing
-
-# Changelog
-
-## v0.1.3
-
-Date: 2022-04-18
-
-- Changes:
-  - Switch to BSD 2-Clause License, and add the license file to repo.
-  - Drop supports of old python (<=3.6))
-  - Change the package's build system to PEP517
-
-## v0.1.2
-
-- Date: 2020-07-17
-
-  - New documentation site
-  - `kwargs` to plugin method
-
-## v0.1
-
-- Date: 2020-01-16
-
-A very early alpha version, not for production.
-
-# Authors
-
-liu xue yan <liu_xue_yan@foxmail.com>
-
-
+Metadata-Version: 2.1
+Name: mkdocs-nbconvert
+Version: 0.2
+Summary: A MkDocs plug-in provides a source parser for *.ipynb Jupyter notebook files, base on nbconvert.
+Author-email: liu xue yan <liu_xue_yan@foxmail.com>
+License: BSD-3-Clause
+Project-URL: Homepage, https://tanbro.github.io/mkdocs-nbconvert
+Project-URL: Repository, https://github.com/tanbro/mkdocs_nbconvert.git
+Project-URL: Documentation, https://tanbro.github.io/mkdocs-nbconvert
+Keywords: mkdocs,mkdocs-plugin,jupyter,notebook,jupyter-notebook,markdown,md,nbconvert
+Classifier: License :: OSI Approved :: BSD License
+Classifier: Development Status :: 4 - Beta
+Classifier: Topic :: Documentation
+Classifier: Intended Audience :: Developers
+Classifier: Programming Language :: Python
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+License-File: AUTHORS.md
+
+# mkdocs-nbconvert
+
+[![PyPI](https://img.shields.io/pypi/v/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
+[![PyPI - Status](https://img.shields.io/pypi/status/mkdocs-nbconvert)](https://pypi.org/project/mkdocs-nbconvert/)
+[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
+[![PyPI - Format](https://img.shields.io/pypi/format/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
+
+A [MkDocs][] plug-in provides a source parser for `*.ipynb` [Jupyter][] Notebook files, base on [nbconvert][].
+
+## References
+
+- <https://tanbro.github.io/mkdocs-nbconvert/>
+- <https://www.mkdocs.org/user-guide/plugins/>
+
+## Build the site
+
+The project itself's documentation site is a demo of how to use it.
+
+To build and serve the doc-site:
+
+```bash
+pip install -r dev.requirements.txt
+mkdocs serve
+```
+
+Then open `http://127.0.0.1:8000` in your browser.
+
+[MkDocs]: http://www.mkdocs.org/
+[Jupyter]: https://jupyter.org/
+[nbconvert]: https://pypi.org/project/nbconvert/
```

### Comparing `mkdocs-nbconvert-0.1.3/README.md` & `mkdocs-nbconvert-0.2/README.md`

 * *Files 23% similar despite different names*

```diff
@@ -3,27 +3,28 @@
 [![PyPI](https://img.shields.io/pypi/v/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
 [![PyPI - Status](https://img.shields.io/pypi/status/mkdocs-nbconvert)](https://pypi.org/project/mkdocs-nbconvert/)
 [![PyPI - Python Version](https://img.shields.io/pypi/pyversions/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
 [![PyPI - Format](https://img.shields.io/pypi/format/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
 
 A [MkDocs][] plug-in provides a source parser for `*.ipynb` [Jupyter][] Notebook files, base on [nbconvert][].
 
-## Features
+## References
 
-- doc: <https://tanbro.github.io/mkdocs-nbconvert/>
-- ref: <https://www.mkdocs.org/user-guide/plugins/>
+- <https://tanbro.github.io/mkdocs-nbconvert/>
+- <https://www.mkdocs.org/user-guide/plugins/>
 
-## Build the documentation
+## Build the site
 
-The project itself's documentation site is a demo of how to use is in [MkDocs][].
+The project itself's documentation site is a demo of how to use it.
 
-To serve it:
+To build and serve the doc-site:
 
 ```bash
-mkdocs serve -a 127.0.0.1:8080
+pip install -r dev.requirements.txt
+mkdocs serve
 ```
 
-Then open `http://127.0.0.1:8080` with your browser.
+Then open `http://127.0.0.1:8000` in your browser.
 
 [MkDocs]: http://www.mkdocs.org/
 [Jupyter]: https://jupyter.org/
 [nbconvert]: https://pypi.org/project/nbconvert/
```

### Comparing `mkdocs-nbconvert-0.1.3/src/mkdocs_nbconvert.egg-info/PKG-INFO` & `mkdocs-nbconvert-0.2/src/mkdocs_nbconvert.egg-info/PKG-INFO`

 * *Files 12% similar despite different names*

```diff
@@ -1,83 +1,50 @@
-Metadata-Version: 2.1
-Name: mkdocs-nbconvert
-Version: 0.1.3
-Summary: A MkDocs plug-in provides a source parser for *.ipynb files
-Home-page: https://tanbro.github.io/mkdocs-nbconvert
-Author: liu xue yan
-Author-email: liu_xue_yan@foxmail.com
-License: BSD 3-Clause License
-Project-URL: Documentation, https://tanbro.github.io/mkdocs-nbconvert
-Project-URL: Source, https://github.com/tanbro/mkdocs-nbconvert
-Keywords: mkdocs,mkdocs-plugin,jupyter,notebook,jupyter-notebook,markdown,md,nbconvert
-Platform: UNKNOWN
-Classifier: License :: OSI Approved :: BSD License
-Classifier: Development Status :: 4 - Beta
-Classifier: Topic :: Documentation
-Classifier: Intended Audience :: Developers
-Classifier: Programming Language :: Python :: 3
-Classifier: Programming Language :: Python :: 3 :: Only
-Requires-Python: >=3.6
-Description-Content-Type: text/markdown
-License-File: LICENSE
-
-# mkdocs-nbconvert
-
-[![PyPI](https://img.shields.io/pypi/v/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
-[![PyPI - Status](https://img.shields.io/pypi/status/mkdocs-nbconvert)](https://pypi.org/project/mkdocs-nbconvert/)
-[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
-[![PyPI - Format](https://img.shields.io/pypi/format/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
-
-A [MkDocs][] plug-in provides a source parser for `*.ipynb` [Jupyter][] Notebook files, base on [nbconvert][].
-
-## Features
-
-- doc: <https://tanbro.github.io/mkdocs-nbconvert/>
-- ref: <https://www.mkdocs.org/user-guide/plugins/>
-
-## Build the documentation
-
-The project itself's documentation site is a demo of how to use is in [MkDocs][].
-
-To serve it:
-
-```bash
-mkdocs serve -a 127.0.0.1:8080
-```
-
-Then open `http://127.0.0.1:8080` with your browser.
-
-[MkDocs]: http://www.mkdocs.org/
-[Jupyter]: https://jupyter.org/
-[nbconvert]: https://pypi.org/project/nbconvert/
-
-# Contributing
-
-# Changelog
-
-## v0.1.3
-
-Date: 2022-04-18
-
-- Changes:
-  - Switch to BSD 2-Clause License, and add the license file to repo.
-  - Drop supports of old python (<=3.6))
-  - Change the package's build system to PEP517
-
-## v0.1.2
-
-- Date: 2020-07-17
-
-  - New documentation site
-  - `kwargs` to plugin method
-
-## v0.1
-
-- Date: 2020-01-16
-
-A very early alpha version, not for production.
-
-# Authors
-
-liu xue yan <liu_xue_yan@foxmail.com>
-
-
+Metadata-Version: 2.1
+Name: mkdocs-nbconvert
+Version: 0.2
+Summary: A MkDocs plug-in provides a source parser for *.ipynb Jupyter notebook files, base on nbconvert.
+Author-email: liu xue yan <liu_xue_yan@foxmail.com>
+License: BSD-3-Clause
+Project-URL: Homepage, https://tanbro.github.io/mkdocs-nbconvert
+Project-URL: Repository, https://github.com/tanbro/mkdocs_nbconvert.git
+Project-URL: Documentation, https://tanbro.github.io/mkdocs-nbconvert
+Keywords: mkdocs,mkdocs-plugin,jupyter,notebook,jupyter-notebook,markdown,md,nbconvert
+Classifier: License :: OSI Approved :: BSD License
+Classifier: Development Status :: 4 - Beta
+Classifier: Topic :: Documentation
+Classifier: Intended Audience :: Developers
+Classifier: Programming Language :: Python
+Requires-Python: >=3.7
+Description-Content-Type: text/markdown
+License-File: LICENSE
+License-File: AUTHORS.md
+
+# mkdocs-nbconvert
+
+[![PyPI](https://img.shields.io/pypi/v/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
+[![PyPI - Status](https://img.shields.io/pypi/status/mkdocs-nbconvert)](https://pypi.org/project/mkdocs-nbconvert/)
+[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
+[![PyPI - Format](https://img.shields.io/pypi/format/mkdocs-nbconvert.svg)](https://pypi.org/project/mkdocs-nbconvert/)
+
+A [MkDocs][] plug-in provides a source parser for `*.ipynb` [Jupyter][] Notebook files, base on [nbconvert][].
+
+## References
+
+- <https://tanbro.github.io/mkdocs-nbconvert/>
+- <https://www.mkdocs.org/user-guide/plugins/>
+
+## Build the site
+
+The project itself's documentation site is a demo of how to use it.
+
+To build and serve the doc-site:
+
+```bash
+pip install -r dev.requirements.txt
+mkdocs serve
+```
+
+Then open `http://127.0.0.1:8000` in your browser.
+
+[MkDocs]: http://www.mkdocs.org/
+[Jupyter]: https://jupyter.org/
+[nbconvert]: https://pypi.org/project/nbconvert/
```


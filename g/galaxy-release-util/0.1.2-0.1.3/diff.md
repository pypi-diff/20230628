# Comparing `tmp/galaxy-release-util-0.1.2.tar.gz` & `tmp/galaxy-release-util-0.1.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "galaxy-release-util-0.1.2.tar", last modified: Tue Jun 13 16:50:29 2023, max compression
+gzip compressed data, was "galaxy-release-util-0.1.3.tar", last modified: Wed Jun 28 09:36:30 2023, max compression
```

## Comparing `galaxy-release-util-0.1.2.tar` & `galaxy-release-util-0.1.3.tar`

### file list

```diff
@@ -1,30 +1,30 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-13 16:50:28.999202 galaxy-release-util-0.1.2/
--rw-r--r--   0 runner    (1001) docker     (123)      348 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/HISTORY.rst
--rw-r--r--   0 runner    (1001) docker     (123)     1036 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/LICENSE.txt
--rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (123)     1987 2023-06-13 16:50:28.999202 galaxy-release-util-0.1.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      525 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/README.rst
--rw-r--r--   0 runner    (1001) docker     (123)       93 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/dev-requirements.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-13 16:50:28.995202 galaxy-release-util-0.1.2/galaxy_release_util/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/galaxy_release_util/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    22421 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/galaxy_release_util/bootstrap_history.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-13 16:50:28.999202 galaxy-release-util-0.1.2/galaxy_release_util/cli/
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/galaxy_release_util/cli/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      860 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/galaxy_release_util/cli/options.py
--rw-r--r--   0 runner    (1001) docker     (123)      285 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/galaxy_release_util/cli/release_util.py
--rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/galaxy_release_util/github_client.py
--rw-r--r--   0 runner    (1001) docker     (123)     3224 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/galaxy_release_util/metadata.py
--rw-r--r--   0 runner    (1001) docker     (123)    26254 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/galaxy_release_util/point_release.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/galaxy_release_util/py.typed
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-13 16:50:28.999202 galaxy-release-util-0.1.2/galaxy_release_util.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1987 2023-06-13 16:50:28.000000 galaxy-release-util-0.1.2/galaxy_release_util.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      715 2023-06-13 16:50:28.000000 galaxy-release-util-0.1.2/galaxy_release_util.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-13 16:50:28.000000 galaxy-release-util-0.1.2/galaxy_release_util.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       81 2023-06-13 16:50:28.000000 galaxy-release-util-0.1.2/galaxy_release_util.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)       55 2023-06-13 16:50:28.000000 galaxy-release-util-0.1.2/galaxy_release_util.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-13 16:50:28.000000 galaxy-release-util-0.1.2/galaxy_release_util.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)     1369 2023-06-13 16:50:28.999202 galaxy-release-util-0.1.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/test-requirements.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-13 16:50:28.999202 galaxy-release-util-0.1.2/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-13 16:50:18.000000 galaxy-release-util-0.1.2/tests/test_release.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:36:30.409322 galaxy-release-util-0.1.3/
+-rw-r--r--   0 runner    (1001) docker     (123)      489 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/HISTORY.rst
+-rw-r--r--   0 runner    (1001) docker     (123)     1036 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       39 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (123)     2128 2023-06-28 09:36:30.409322 galaxy-release-util-0.1.3/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      525 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/README.rst
+-rw-r--r--   0 runner    (1001) docker     (123)       93 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/dev-requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:36:30.409322 galaxy-release-util-0.1.3/galaxy_release_util/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/galaxy_release_util/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    22447 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/galaxy_release_util/bootstrap_history.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:36:30.409322 galaxy-release-util-0.1.3/galaxy_release_util/cli/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/galaxy_release_util/cli/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      860 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/galaxy_release_util/cli/options.py
+-rw-r--r--   0 runner    (1001) docker     (123)      285 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/galaxy_release_util/cli/release_util.py
+-rw-r--r--   0 runner    (1001) docker     (123)      888 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/galaxy_release_util/github_client.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3224 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/galaxy_release_util/metadata.py
+-rw-r--r--   0 runner    (1001) docker     (123)    26254 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/galaxy_release_util/point_release.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/galaxy_release_util/py.typed
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:36:30.409322 galaxy-release-util-0.1.3/galaxy_release_util.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     2128 2023-06-28 09:36:30.000000 galaxy-release-util-0.1.3/galaxy_release_util.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      715 2023-06-28 09:36:30.000000 galaxy-release-util-0.1.3/galaxy_release_util.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 09:36:30.000000 galaxy-release-util-0.1.3/galaxy_release_util.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       81 2023-06-28 09:36:30.000000 galaxy-release-util-0.1.3/galaxy_release_util.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       55 2023-06-28 09:36:30.000000 galaxy-release-util-0.1.3/galaxy_release_util.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       20 2023-06-28 09:36:30.000000 galaxy-release-util-0.1.3/galaxy_release_util.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      230 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)     1369 2023-06-28 09:36:30.409322 galaxy-release-util-0.1.3/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)        7 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/test-requirements.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 09:36:30.409322 galaxy-release-util-0.1.3/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      931 2023-06-28 09:36:20.000000 galaxy-release-util-0.1.3/tests/test_release.py
```

### Comparing `galaxy-release-util-0.1.2/LICENSE.txt` & `galaxy-release-util-0.1.3/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `galaxy-release-util-0.1.2/PKG-INFO` & `galaxy-release-util-0.1.3/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: galaxy-release-util
-Version: 0.1.2
+Version: 0.1.3
 Summary: Utlity for various tasks around creating Galaxy releases
 Home-page: https://github.com/galaxyproject/galaxy-release-util
 Author: Galaxy Project and Community
 Author-email: galaxy-committers@lists.galaxyproject.org
 License: AFL
 Keywords: Galaxy
 Classifier: Development Status :: 5 - Production/Stable
@@ -54,14 +54,22 @@
 * Tag a new version and create a release from the GitHub interface
 
 History
 -------
 
 .. to_doc
 
+
+
+------------------
+0.1.3 (28-06-2023)
+------------------
+* Add step/checkbox on updating db revision identifier
+* Bootstrap history fixes
+
 ------------------
 0.1.2 (12-06-2023)
 ------------------
 * Fix isinstance assertion
 
 ------------------
 0.1.1 (12-06-2023)
```

### Comparing `galaxy-release-util-0.1.2/README.rst` & `galaxy-release-util-0.1.3/README.rst`

 * *Files identical despite different names*

### Comparing `galaxy-release-util-0.1.2/galaxy_release_util/bootstrap_history.py` & `galaxy-release-util-0.1.3/galaxy_release_util/bootstrap_history.py`

 * *Files 2% similar despite different names*

```diff
@@ -204,14 +204,16 @@
 
 - [ ] **Branch Release (on or around ${freeze_date})**
 
     - [ ] Ensure all [blocking milestone PRs](https://github.com/galaxyproject/galaxy/pulls?q=is%3Aopen+is%3Apr+milestone%3A${version}) have been merged, delayed, or closed.
 
           make release-check-blocking-prs
 
+    - [ ] Add latest database revision identifier (for ``release_${version}`` and ``${version}``) to ``REVISION_TAGS`` in ``galaxy/model/migrations/dbscript.py``.
+
     - [ ] Merge the latest release into dev and push upstream.
 
           make release-merge-stable-to-next RELEASE_PREVIOUS=release_${previous_version}
           make release-push-dev
 
     - [ ] Create and push release branch:
 
@@ -235,33 +237,30 @@
 
 - [ ] **Deploy and Test Release**
 
     - [ ] Update test.galaxyproject.org to ensure it is running a dev at or past branch point (${freeze_date} + 1 day).
     - [ ] Update testtoolshed.g2.bx.psu.edu to ensure it is running a dev at or past branch point (${freeze_date} + 1 day).
     - [ ] Deploy to usegalaxy.org (${freeze_date} + 1 week).
     - [ ] Deploy to toolshed.g2.bx.psu.edu (${freeze_date} + 1 week).
-    - [ ] [Update BioBlend CI testing](https://github.com/galaxyproject/bioblend/commit/b74b1c302a1b8fed86786b40d7ecc3520cbadcd3) to include a ``release_${version}`` target: add ``- TOX_ENV=py27 GALAXY_VERSION=release_${version}`` to the ``env`` list in ``.travis.yml`` .
+    - [ ] [Update BioBlend CI testing](https://github.com/galaxyproject/bioblend/blob/main/.github/workflows/test.yaml) to include a ``release_${version}`` target: add ``- release_${version}`` to the ``galaxy_version`` list in ``.github/workflows/test.yaml`` .
     - [ ] Update GALAXY_RELEASE in IUC and devteam github workflows
         - [ ] https://github.com/galaxyproject/tools-iuc/blob/master/.github/workflows/
         - [ ] https://github.com/galaxyproject/tools-devteam/blob/master/.github/workflows/
 
 - [ ] **Create Release Notes**
 
     - [ ] Review merged PRs and ensure they all have a milestones attached. [Link](https://github.com/galaxyproject/galaxy/pulls?utf8=%E2%9C%93&q=is%3Apr+is%3Amerged+no%3Amilestone+-label%3Amerge+)
     - [ ] Checkout release branch
 
           git checkout release_${version} -b ${version}_release_notes
-    - [ ] Check for obvious missing metadata in release PRs
-
-          make release-check-metadata RELEASE_CURR=${version}
     - [ ] Bootstrap the release notes
 
           make release-bootstrap-history RELEASE_CURR=${version}
     - [ ] Open newly created files and manually curate major topics and release notes.
-    - [ ] Run python scripts/scripts/release-diff.py release_${previous_version} and add configuration changes to release notes.
+    - [ ] Run ``python scripts/release-diff.py release_${previous_version}`` and add configuration changes to release notes.
     - [ ] Add new release to doc/source/releases/index.rst
     - [ ] Commit release notes.
 
           git add docs/; git commit -m "Release notes for $version"; git push upstream ${version}_release_notes
     - [ ] Open a pull request for new release note branch.
     - [ ] Merge release note pull request.
```

### Comparing `galaxy-release-util-0.1.2/galaxy_release_util/cli/options.py` & `galaxy-release-util-0.1.3/galaxy_release_util/cli/options.py`

 * *Files identical despite different names*

### Comparing `galaxy-release-util-0.1.2/galaxy_release_util/github_client.py` & `galaxy-release-util-0.1.3/galaxy_release_util/github_client.py`

 * *Files identical despite different names*

### Comparing `galaxy-release-util-0.1.2/galaxy_release_util/metadata.py` & `galaxy-release-util-0.1.3/galaxy_release_util/metadata.py`

 * *Files identical despite different names*

### Comparing `galaxy-release-util-0.1.2/galaxy_release_util/point_release.py` & `galaxy-release-util-0.1.3/galaxy_release_util/point_release.py`

 * *Files identical despite different names*

### Comparing `galaxy-release-util-0.1.2/galaxy_release_util.egg-info/PKG-INFO` & `galaxy-release-util-0.1.3/galaxy_release_util.egg-info/PKG-INFO`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: galaxy-release-util
-Version: 0.1.2
+Version: 0.1.3
 Summary: Utlity for various tasks around creating Galaxy releases
 Home-page: https://github.com/galaxyproject/galaxy-release-util
 Author: Galaxy Project and Community
 Author-email: galaxy-committers@lists.galaxyproject.org
 License: AFL
 Keywords: Galaxy
 Classifier: Development Status :: 5 - Production/Stable
@@ -54,14 +54,22 @@
 * Tag a new version and create a release from the GitHub interface
 
 History
 -------
 
 .. to_doc
 
+
+
+------------------
+0.1.3 (28-06-2023)
+------------------
+* Add step/checkbox on updating db revision identifier
+* Bootstrap history fixes
+
 ------------------
 0.1.2 (12-06-2023)
 ------------------
 * Fix isinstance assertion
 
 ------------------
 0.1.1 (12-06-2023)
```

### Comparing `galaxy-release-util-0.1.2/galaxy_release_util.egg-info/SOURCES.txt` & `galaxy-release-util-0.1.3/galaxy_release_util.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `galaxy-release-util-0.1.2/setup.cfg` & `galaxy-release-util-0.1.3/setup.cfg`

 * *Files 5% similar despite different names*

```diff
@@ -23,15 +23,15 @@
 license = AFL
 license_files = 
 	LICENSE
 long_description = file: README.rst, HISTORY.rst
 long_description_content_type = text/x-rst
 name = galaxy-release-util
 url = https://github.com/galaxyproject/galaxy-release-util
-version = 0.1.2
+version = 0.1.3
 
 [options]
 include_package_data = True
 install_requires = 
 	build
 	click
 	docutils
```

### Comparing `galaxy-release-util-0.1.2/tests/test_release.py` & `galaxy-release-util-0.1.3/tests/test_release.py`

 * *Files identical despite different names*


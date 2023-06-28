# Comparing `tmp/ai-aside-1.2.1.tar.gz` & `tmp/ai-aside-2.0.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ai-aside-1.2.1.tar", last modified: Fri May 19 14:37:31 2023, max compression
+gzip compressed data, was "ai-aside-2.0.0.tar", last modified: Wed Jun 28 13:34:29 2023, max compression
```

## Comparing `ai-aside-1.2.1.tar` & `ai-aside-2.0.0.tar`

### file list

```diff
@@ -1,39 +1,40 @@
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:31.973521 ai-aside-1.2.1/
--rw-r--r--   0 runner    (1001) docker     (122)      747 2023-05-19 14:37:27.000000 ai-aside-1.2.1/CHANGELOG.rst
--rw-r--r--   0 runner    (1001) docker     (122)    35139 2023-05-19 14:37:27.000000 ai-aside-1.2.1/LICENSE.txt
--rw-r--r--   0 runner    (1001) docker     (122)      203 2023-05-19 14:37:27.000000 ai-aside-1.2.1/MANIFEST.in
--rw-r--r--   0 runner    (1001) docker     (122)     6666 2023-05-19 14:37:31.973521 ai-aside-1.2.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)     5208 2023-05-19 14:37:27.000000 ai-aside-1.2.1/README.rst
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:31.969521 ai-aside-1.2.1/ai_aside/
--rw-r--r--   0 runner    (1001) docker     (122)      109 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)      750 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/apps.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:31.973521 ai-aside-1.2.1/ai_aside/settings/
--rw-r--r--   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/settings/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)      111 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/settings/common.py
--rw-r--r--   0 runner    (1001) docker     (122)      109 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/settings/devstack.py
--rw-r--r--   0 runner    (1001) docker     (122)      111 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/settings/production.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:31.973521 ai-aside-1.2.1/ai_aside/summaryhook_aside/
--rw-r--r--   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/summaryhook_aside/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)      761 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/summaryhook_aside/apps.py
--rw-r--r--   0 runner    (1001) docker     (122)     2899 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/summaryhook_aside/block.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:31.973521 ai-aside-1.2.1/ai_aside/summaryhook_aside/settings/
--rw-r--r--   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/summaryhook_aside/settings/__init__.py
--rw-r--r--   0 runner    (1001) docker     (122)      360 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/summaryhook_aside/settings/common.py
--rw-r--r--   0 runner    (1001) docker     (122)      553 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/summaryhook_aside/settings/devstack.py
--rw-r--r--   0 runner    (1001) docker     (122)      111 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/summaryhook_aside/settings/production.py
--rw-r--r--   0 runner    (1001) docker     (122)     1836 2023-05-19 14:37:27.000000 ai-aside-1.2.1/ai_aside/summaryhook_aside/waffle.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:31.973521 ai-aside-1.2.1/ai_aside.egg-info/
--rw-r--r--   0 runner    (1001) docker     (122)     6666 2023-05-19 14:37:31.000000 ai-aside-1.2.1/ai_aside.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (122)      865 2023-05-19 14:37:31.000000 ai-aside-1.2.1/ai_aside.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (122)        1 2023-05-19 14:37:31.000000 ai-aside-1.2.1/ai_aside.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (122)      209 2023-05-19 14:37:31.000000 ai-aside-1.2.1/ai_aside.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (122)        1 2023-05-19 14:37:31.000000 ai-aside-1.2.1/ai_aside.egg-info/not-zip-safe
--rw-r--r--   0 runner    (1001) docker     (122)       31 2023-05-19 14:37:31.000000 ai-aside-1.2.1/ai_aside.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (122)        9 2023-05-19 14:37:31.000000 ai-aside-1.2.1/ai_aside.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:31.973521 ai-aside-1.2.1/requirements/
--rw-r--r--   0 runner    (1001) docker     (122)      138 2023-05-19 14:37:27.000000 ai-aside-1.2.1/requirements/base.in
--rw-r--r--   0 runner    (1001) docker     (122)      561 2023-05-19 14:37:27.000000 ai-aside-1.2.1/requirements/constraints.txt
--rw-r--r--   0 runner    (1001) docker     (122)      176 2023-05-19 14:37:31.973521 ai-aside-1.2.1/setup.cfg
--rwxr-xr-x   0 runner    (1001) docker     (122)     5399 2023-05-19 14:37:27.000000 ai-aside-1.2.1/setup.py
-drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-05-19 14:37:31.973521 ai-aside-1.2.1/tests/
--rw-r--r--   0 runner    (1001) docker     (122)      252 2023-05-19 14:37:27.000000 ai-aside-1.2.1/tests/test_placeholder.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:29.925830 ai-aside-2.0.0/
+-rw-r--r--   0 runner    (1001) docker     (122)      953 2023-06-28 13:34:25.000000 ai-aside-2.0.0/CHANGELOG.rst
+-rw-r--r--   0 runner    (1001) docker     (122)    35139 2023-06-28 13:34:25.000000 ai-aside-2.0.0/LICENSE.txt
+-rw-r--r--   0 runner    (1001) docker     (122)      203 2023-06-28 13:34:25.000000 ai-aside-2.0.0/MANIFEST.in
+-rw-r--r--   0 runner    (1001) docker     (122)     7562 2023-06-28 13:34:29.925830 ai-aside-2.0.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)     5898 2023-06-28 13:34:25.000000 ai-aside-2.0.0/README.rst
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:29.925830 ai-aside-2.0.0/ai_aside/
+-rw-r--r--   0 runner    (1001) docker     (122)      109 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)      750 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/apps.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:29.925830 ai-aside-2.0.0/ai_aside/settings/
+-rw-r--r--   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/settings/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)      111 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/settings/common.py
+-rw-r--r--   0 runner    (1001) docker     (122)      109 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/settings/devstack.py
+-rw-r--r--   0 runner    (1001) docker     (122)      111 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/settings/production.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:29.925830 ai-aside-2.0.0/ai_aside/summaryhook_aside/
+-rw-r--r--   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/summaryhook_aside/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)      761 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/summaryhook_aside/apps.py
+-rw-r--r--   0 runner    (1001) docker     (122)     7412 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/summaryhook_aside/block.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:29.925830 ai-aside-2.0.0/ai_aside/summaryhook_aside/settings/
+-rw-r--r--   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/summaryhook_aside/settings/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (122)      429 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/summaryhook_aside/settings/common.py
+-rw-r--r--   0 runner    (1001) docker     (122)      655 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/summaryhook_aside/settings/devstack.py
+-rw-r--r--   0 runner    (1001) docker     (122)      111 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/summaryhook_aside/settings/production.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1396 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/summaryhook_aside/text_utils.py
+-rw-r--r--   0 runner    (1001) docker     (122)     1836 2023-06-28 13:34:25.000000 ai-aside-2.0.0/ai_aside/summaryhook_aside/waffle.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:29.925830 ai-aside-2.0.0/ai_aside.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (122)     7562 2023-06-28 13:34:29.000000 ai-aside-2.0.0/ai_aside.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (122)      906 2023-06-28 13:34:29.000000 ai-aside-2.0.0/ai_aside.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-28 13:34:29.000000 ai-aside-2.0.0/ai_aside.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (122)      209 2023-06-28 13:34:29.000000 ai-aside-2.0.0/ai_aside.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        1 2023-06-28 13:34:29.000000 ai-aside-2.0.0/ai_aside.egg-info/not-zip-safe
+-rw-r--r--   0 runner    (1001) docker     (122)       31 2023-06-28 13:34:29.000000 ai-aside-2.0.0/ai_aside.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (122)        9 2023-06-28 13:34:29.000000 ai-aside-2.0.0/ai_aside.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:29.925830 ai-aside-2.0.0/requirements/
+-rw-r--r--   0 runner    (1001) docker     (122)      138 2023-06-28 13:34:25.000000 ai-aside-2.0.0/requirements/base.in
+-rw-r--r--   0 runner    (1001) docker     (122)      561 2023-06-28 13:34:25.000000 ai-aside-2.0.0/requirements/constraints.txt
+-rw-r--r--   0 runner    (1001) docker     (122)      176 2023-06-28 13:34:29.925830 ai-aside-2.0.0/setup.cfg
+-rwxr-xr-x   0 runner    (1001) docker     (122)     5399 2023-06-28 13:34:25.000000 ai-aside-2.0.0/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (122)        0 2023-06-28 13:34:29.925830 ai-aside-2.0.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (122)      252 2023-06-28 13:34:25.000000 ai-aside-2.0.0/tests/test_placeholder.py
```

### Comparing `ai-aside-1.2.1/CHANGELOG.rst` & `ai-aside-2.0.0/CHANGELOG.rst`

 * *Files 24% similar despite different names*

```diff
@@ -10,15 +10,23 @@
    This project adheres to Semantic Versioning (https://semver.org/).
 
 .. There should always be an "Unreleased" section for changes pending release.
 
 Unreleased
 **********
 
-*
+2.0.0 – 2023-06-28
+**********************************************
+
+Added
+=====
+
+* Adds a handler endpoint to provide summarizable content
+* Improves content length checking using that summarizable content
+
 
 1.2.1 – 2023-05-19
 **********************************************
 
 Fixes
 =====
```

### Comparing `ai-aside-1.2.1/LICENSE.txt` & `ai-aside-2.0.0/LICENSE.txt`

 * *Files identical despite different names*

### Comparing `ai-aside-1.2.1/PKG-INFO` & `ai-aside-2.0.0/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ai-aside
-Version: 1.2.1
+Version: 2.0.0
 Summary: A plugin containing xblocks and apps supporting GPT and other LLM use on edX.
 Home-page: https://github.com/openedx/ai-aside
 Author: edX
 Author-email: ashultz@edx.org
 License: AGPL 3.0
 Keywords: Python edx
 Classifier: Development Status :: 3 - Alpha
@@ -46,14 +46,26 @@
   # Set up a virtualenv using virtualenvwrapper with the same name as the repo and activate it
   mkvirtualenv -p python3.8 ai-aside
 
 Local testing
 ~~~~~~~~~~~~~
 To test your changes locally, you will need to install the package from your local branch into edx-platform. For example, if using devstack, copy or clone your branch into <devstack-parent>/src/ai-aside. Then, in an lms or cms shell, run ``pip install -e /edx/src/ai-aside``.  The plug-in configuration will automatically be picked up once installed, and changes will be hot reloaded.
 
+Testing in Docker with AI-spot
+..............................
+
+If you are running both devstack and a local instance of the supporting ai-spot in docker, you need two pieces of special setup to let ai-spot call the aside handler and retrieve content.
+
+The first is to connect ai-spot to the devstack network with a docker command::
+
+  docker network connect devstack_default ai-spot-server-1
+
+The second is to change the handler URLs generated by ai-aside to a URL that is accessible by ai-spot in the same docker. This is already set up for you in ``summaryhook_aside/settings/devstack.py``. If your AI service is running locally outside of docker, you will need to change that setting.
+
+
 Enabling the Aside
 ~~~~~~~~~~~~~~~~~~
 
 For the summary aside to work, you will have to make two changes in the LMS admin:
 
 1. You must create an ``XBlockAsidesConfig`` (admin URL: `/admin/lms_xblock/xblockasidesconfig/`). This model has a list of blocks you do not want asides to apply to that can be left alone, and an enabled setting that unsurprisingly should be True.
 
@@ -184,15 +196,23 @@
    This project adheres to Semantic Versioning (https://semver.org/).
 
 .. There should always be an "Unreleased" section for changes pending release.
 
 Unreleased
 **********
 
-*
+2.0.0 – 2023-06-28
+**********************************************
+
+Added
+=====
+
+* Adds a handler endpoint to provide summarizable content
+* Improves content length checking using that summarizable content
+
 
 1.2.1 – 2023-05-19
 **********************************************
 
 Fixes
 =====
```

### Comparing `ai-aside-1.2.1/README.rst` & `ai-aside-2.0.0/README.rst`

 * *Files 5% similar despite different names*

```diff
@@ -26,14 +26,26 @@
   # Set up a virtualenv using virtualenvwrapper with the same name as the repo and activate it
   mkvirtualenv -p python3.8 ai-aside
 
 Local testing
 ~~~~~~~~~~~~~
 To test your changes locally, you will need to install the package from your local branch into edx-platform. For example, if using devstack, copy or clone your branch into <devstack-parent>/src/ai-aside. Then, in an lms or cms shell, run ``pip install -e /edx/src/ai-aside``.  The plug-in configuration will automatically be picked up once installed, and changes will be hot reloaded.
 
+Testing in Docker with AI-spot
+..............................
+
+If you are running both devstack and a local instance of the supporting ai-spot in docker, you need two pieces of special setup to let ai-spot call the aside handler and retrieve content.
+
+The first is to connect ai-spot to the devstack network with a docker command::
+
+  docker network connect devstack_default ai-spot-server-1
+
+The second is to change the handler URLs generated by ai-aside to a URL that is accessible by ai-spot in the same docker. This is already set up for you in ``summaryhook_aside/settings/devstack.py``. If your AI service is running locally outside of docker, you will need to change that setting.
+
+
 Enabling the Aside
 ~~~~~~~~~~~~~~~~~~
 
 For the summary aside to work, you will have to make two changes in the LMS admin:
 
 1. You must create an ``XBlockAsidesConfig`` (admin URL: `/admin/lms_xblock/xblockasidesconfig/`). This model has a list of blocks you do not want asides to apply to that can be left alone, and an enabled setting that unsurprisingly should be True.
```

### Comparing `ai-aside-1.2.1/ai_aside/apps.py` & `ai-aside-2.0.0/ai_aside/apps.py`

 * *Files identical despite different names*

### Comparing `ai-aside-1.2.1/ai_aside/summaryhook_aside/apps.py` & `ai-aside-2.0.0/ai_aside/summaryhook_aside/apps.py`

 * *Files identical despite different names*

### Comparing `ai-aside-1.2.1/ai_aside/summaryhook_aside/waffle.py` & `ai-aside-2.0.0/ai_aside/summaryhook_aside/waffle.py`

 * *Files identical despite different names*

### Comparing `ai-aside-1.2.1/ai_aside.egg-info/PKG-INFO` & `ai-aside-2.0.0/ai_aside.egg-info/PKG-INFO`

 * *Files 17% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ai-aside
-Version: 1.2.1
+Version: 2.0.0
 Summary: A plugin containing xblocks and apps supporting GPT and other LLM use on edX.
 Home-page: https://github.com/openedx/ai-aside
 Author: edX
 Author-email: ashultz@edx.org
 License: AGPL 3.0
 Keywords: Python edx
 Classifier: Development Status :: 3 - Alpha
@@ -46,14 +46,26 @@
   # Set up a virtualenv using virtualenvwrapper with the same name as the repo and activate it
   mkvirtualenv -p python3.8 ai-aside
 
 Local testing
 ~~~~~~~~~~~~~
 To test your changes locally, you will need to install the package from your local branch into edx-platform. For example, if using devstack, copy or clone your branch into <devstack-parent>/src/ai-aside. Then, in an lms or cms shell, run ``pip install -e /edx/src/ai-aside``.  The plug-in configuration will automatically be picked up once installed, and changes will be hot reloaded.
 
+Testing in Docker with AI-spot
+..............................
+
+If you are running both devstack and a local instance of the supporting ai-spot in docker, you need two pieces of special setup to let ai-spot call the aside handler and retrieve content.
+
+The first is to connect ai-spot to the devstack network with a docker command::
+
+  docker network connect devstack_default ai-spot-server-1
+
+The second is to change the handler URLs generated by ai-aside to a URL that is accessible by ai-spot in the same docker. This is already set up for you in ``summaryhook_aside/settings/devstack.py``. If your AI service is running locally outside of docker, you will need to change that setting.
+
+
 Enabling the Aside
 ~~~~~~~~~~~~~~~~~~
 
 For the summary aside to work, you will have to make two changes in the LMS admin:
 
 1. You must create an ``XBlockAsidesConfig`` (admin URL: `/admin/lms_xblock/xblockasidesconfig/`). This model has a list of blocks you do not want asides to apply to that can be left alone, and an enabled setting that unsurprisingly should be True.
 
@@ -184,15 +196,23 @@
    This project adheres to Semantic Versioning (https://semver.org/).
 
 .. There should always be an "Unreleased" section for changes pending release.
 
 Unreleased
 **********
 
-*
+2.0.0 – 2023-06-28
+**********************************************
+
+Added
+=====
+
+* Adds a handler endpoint to provide summarizable content
+* Improves content length checking using that summarizable content
+
 
 1.2.1 – 2023-05-19
 **********************************************
 
 Fixes
 =====
```

### Comparing `ai-aside-1.2.1/ai_aside.egg-info/SOURCES.txt` & `ai-aside-2.0.0/ai_aside.egg-info/SOURCES.txt`

 * *Files 8% similar despite different names*

```diff
@@ -16,14 +16,15 @@
 ai_aside/settings/__init__.py
 ai_aside/settings/common.py
 ai_aside/settings/devstack.py
 ai_aside/settings/production.py
 ai_aside/summaryhook_aside/__init__.py
 ai_aside/summaryhook_aside/apps.py
 ai_aside/summaryhook_aside/block.py
+ai_aside/summaryhook_aside/text_utils.py
 ai_aside/summaryhook_aside/waffle.py
 ai_aside/summaryhook_aside/settings/__init__.py
 ai_aside/summaryhook_aside/settings/common.py
 ai_aside/summaryhook_aside/settings/devstack.py
 ai_aside/summaryhook_aside/settings/production.py
 requirements/base.in
 requirements/constraints.txt
```

### Comparing `ai-aside-1.2.1/requirements/constraints.txt` & `ai-aside-2.0.0/requirements/constraints.txt`

 * *Files identical despite different names*

### Comparing `ai-aside-1.2.1/setup.py` & `ai-aside-2.0.0/setup.py`

 * *Files identical despite different names*


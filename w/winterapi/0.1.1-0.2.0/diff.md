# Comparing `tmp/winterapi-0.1.1.tar.gz` & `tmp/winterapi-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "winterapi-0.1.1.tar", last modified: Mon Jun 12 02:35:34 2023, max compression
+gzip compressed data, was "winterapi-0.2.0.tar", last modified: Wed Jun 28 02:24:29 2023, max compression
```

## Comparing `winterapi-0.1.1.tar` & `winterapi-0.2.0.tar`

### file list

```diff
@@ -1,38 +1,38 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-12 02:35:34.481500 winterapi-0.1.1/
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-12 02:35:34.477500 winterapi-0.1.1/.github/
--rw-r--r--   0 runner    (1001) docker     (123)      502 2023-06-12 02:33:59.000000 winterapi-0.1.1/.github/dependabot.yml
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-12 02:35:34.477500 winterapi-0.1.1/.github/workflows/
--rw-r--r--   0 runner    (1001) docker     (123)      896 2023-06-12 02:33:59.000000 winterapi-0.1.1/.github/workflows/automerge.yml
--rw-r--r--   0 runner    (1001) docker     (123)      526 2023-06-12 02:33:59.000000 winterapi-0.1.1/.github/workflows/black.yml
--rw-r--r--   0 runner    (1001) docker     (123)     2634 2023-06-12 02:33:59.000000 winterapi-0.1.1/.github/workflows/continuous_integration.yml
--rw-r--r--   0 runner    (1001) docker     (123)      479 2023-06-12 02:33:59.000000 winterapi-0.1.1/.github/workflows/isort.yml
--rw-r--r--   0 runner    (1001) docker     (123)      552 2023-06-12 02:33:59.000000 winterapi-0.1.1/.github/workflows/pylint.yml
--rw-r--r--   0 runner    (1001) docker     (123)     1806 2023-06-12 02:33:59.000000 winterapi-0.1.1/.gitignore
--rw-r--r--   0 runner    (1001) docker     (123)      713 2023-06-12 02:33:59.000000 winterapi-0.1.1/.pre-commit-config.yaml
--rw-r--r--   0 runner    (1001) docker     (123)     1063 2023-06-12 02:33:59.000000 winterapi-0.1.1/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     1638 2023-06-12 02:35:34.481500 winterapi-0.1.1/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      743 2023-06-12 02:33:59.000000 winterapi-0.1.1/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-12 02:35:34.481500 winterapi-0.1.1/notebooks/
--rw-r--r--   0 runner    (1001) docker     (123)    17962 2023-06-12 02:33:59.000000 winterapi-0.1.1/notebooks/0_intro_accounts.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    22608 2023-06-12 02:33:59.000000 winterapi-0.1.1/notebooks/1_too_models.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)    23058 2023-06-12 02:33:59.000000 winterapi-0.1.1/notebooks/2_submitting_toos.ipynb
--rw-r--r--   0 runner    (1001) docker     (123)     2259 2023-06-12 02:33:59.000000 winterapi-0.1.1/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-12 02:35:34.481500 winterapi-0.1.1/setup.cfg
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-12 02:35:34.481500 winterapi-0.1.1/tests/
--rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-12 02:33:59.000000 winterapi-0.1.1/tests/test_login.py
--rw-r--r--   0 runner    (1001) docker     (123)     2207 2023-06-12 02:33:59.000000 winterapi-0.1.1/tests/test_schedule.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-12 02:35:34.481500 winterapi-0.1.1/tests/testdata/
--rw-r--r--   0 runner    (1001) docker     (123)      820 2023-06-12 02:35:18.000000 winterapi-0.1.1/tests/testdata/test_schedule.csv
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-12 02:35:34.481500 winterapi-0.1.1/winterapi/
--rw-r--r--   0 runner    (1001) docker     (123)      117 2023-06-12 02:33:59.000000 winterapi-0.1.1/winterapi/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      611 2023-06-12 02:33:59.000000 winterapi-0.1.1/winterapi/configure_tests.py
--rw-r--r--   0 runner    (1001) docker     (123)     4288 2023-06-12 02:33:59.000000 winterapi-0.1.1/winterapi/credentials.py
--rw-r--r--   0 runner    (1001) docker     (123)      333 2023-06-12 02:33:59.000000 winterapi-0.1.1/winterapi/endpoints.py
--rw-r--r--   0 runner    (1001) docker     (123)     4957 2023-06-12 02:33:59.000000 winterapi-0.1.1/winterapi/fidelius.py
--rw-r--r--   0 runner    (1001) docker     (123)     9684 2023-06-12 02:33:59.000000 winterapi-0.1.1/winterapi/messenger.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-12 02:35:34.481500 winterapi-0.1.1/winterapi.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     1638 2023-06-12 02:35:34.000000 winterapi-0.1.1/winterapi.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      732 2023-06-12 02:35:34.000000 winterapi-0.1.1/winterapi.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-12 02:35:34.000000 winterapi-0.1.1/winterapi.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)      141 2023-06-12 02:35:34.000000 winterapi-0.1.1/winterapi.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-12 02:35:34.000000 winterapi-0.1.1/winterapi.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:24:29.494828 winterapi-0.2.0/
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:24:29.486828 winterapi-0.2.0/.github/
+-rw-r--r--   0 runner    (1001) docker     (123)      502 2023-06-28 02:22:35.000000 winterapi-0.2.0/.github/dependabot.yml
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:24:29.490828 winterapi-0.2.0/.github/workflows/
+-rw-r--r--   0 runner    (1001) docker     (123)      896 2023-06-28 02:22:35.000000 winterapi-0.2.0/.github/workflows/automerge.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      526 2023-06-28 02:22:35.000000 winterapi-0.2.0/.github/workflows/black.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     2635 2023-06-28 02:22:35.000000 winterapi-0.2.0/.github/workflows/continuous_integration.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      479 2023-06-28 02:22:35.000000 winterapi-0.2.0/.github/workflows/isort.yml
+-rw-r--r--   0 runner    (1001) docker     (123)      552 2023-06-28 02:22:35.000000 winterapi-0.2.0/.github/workflows/pylint.yml
+-rw-r--r--   0 runner    (1001) docker     (123)     1806 2023-06-28 02:22:35.000000 winterapi-0.2.0/.gitignore
+-rw-r--r--   0 runner    (1001) docker     (123)      713 2023-06-28 02:22:35.000000 winterapi-0.2.0/.pre-commit-config.yaml
+-rw-r--r--   0 runner    (1001) docker     (123)     1063 2023-06-28 02:22:35.000000 winterapi-0.2.0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1638 2023-06-28 02:24:29.490828 winterapi-0.2.0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      743 2023-06-28 02:22:35.000000 winterapi-0.2.0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:24:29.490828 winterapi-0.2.0/notebooks/
+-rw-r--r--   0 runner    (1001) docker     (123)    17962 2023-06-28 02:22:35.000000 winterapi-0.2.0/notebooks/0_intro_accounts.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    22608 2023-06-28 02:22:35.000000 winterapi-0.2.0/notebooks/1_too_models.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)    23058 2023-06-28 02:22:35.000000 winterapi-0.2.0/notebooks/2_submitting_toos.ipynb
+-rw-r--r--   0 runner    (1001) docker     (123)     2260 2023-06-28 02:22:35.000000 winterapi-0.2.0/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 02:24:29.494828 winterapi-0.2.0/setup.cfg
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:24:29.490828 winterapi-0.2.0/tests/
+-rw-r--r--   0 runner    (1001) docker     (123)      445 2023-06-28 02:22:35.000000 winterapi-0.2.0/tests/test_login.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2209 2023-06-28 02:22:35.000000 winterapi-0.2.0/tests/test_schedule.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:24:29.490828 winterapi-0.2.0/tests/testdata/
+-rw-r--r--   0 runner    (1001) docker     (123)      826 2023-06-28 02:22:35.000000 winterapi-0.2.0/tests/testdata/test_schedule.csv
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:24:29.490828 winterapi-0.2.0/winterapi/
+-rw-r--r--   0 runner    (1001) docker     (123)      117 2023-06-28 02:22:35.000000 winterapi-0.2.0/winterapi/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      611 2023-06-28 02:22:35.000000 winterapi-0.2.0/winterapi/configure_tests.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4288 2023-06-28 02:22:35.000000 winterapi-0.2.0/winterapi/credentials.py
+-rw-r--r--   0 runner    (1001) docker     (123)      333 2023-06-28 02:22:35.000000 winterapi-0.2.0/winterapi/endpoints.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4957 2023-06-28 02:22:35.000000 winterapi-0.2.0/winterapi/fidelius.py
+-rw-r--r--   0 runner    (1001) docker     (123)     9684 2023-06-28 02:22:35.000000 winterapi-0.2.0/winterapi/messenger.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 02:24:29.490828 winterapi-0.2.0/winterapi.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1638 2023-06-28 02:24:29.000000 winterapi-0.2.0/winterapi.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      732 2023-06-28 02:24:29.000000 winterapi-0.2.0/winterapi.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 02:24:29.000000 winterapi-0.2.0/winterapi.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      142 2023-06-28 02:24:29.000000 winterapi-0.2.0/winterapi.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       10 2023-06-28 02:24:29.000000 winterapi-0.2.0/winterapi.egg-info/top_level.txt
```

### Comparing `winterapi-0.1.1/.github/workflows/automerge.yml` & `winterapi-0.2.0/.github/workflows/automerge.yml`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/.github/workflows/black.yml` & `winterapi-0.2.0/.github/workflows/black.yml`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/.github/workflows/continuous_integration.yml` & `winterapi-0.2.0/.github/workflows/continuous_integration.yml`

 * *Files 0% similar despite different names*

```diff
@@ -58,15 +58,15 @@
         if: ${{ success() }}
         run: |
           coveralls --service=github
         env:
           GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
 
       - name: Echo tag name
-        run: echo "Tag is ${{ github.ref }}, Tagged is ${{ startsWith(github.ref, 'refs/tags/')}}, Python Check is ${{matrix.python-version == 3.11}},  Deploy is ${{ startsWith(github.ref, 'refs/tags/') && matrix.python-version == 3.9}}"
+        run: echo "Tag is ${{ github.ref }}, Tagged is ${{ startsWith(github.ref, 'refs/tags/')}}, Python Check is ${{matrix.python-version == 3.11}},  Deploy is ${{ startsWith(github.ref, 'refs/tags/') && matrix.python-version == 3.11}}"
 
       - name: Install pypa/build
         run: >-
           python -m
           pip install
           build
           --user
```

### Comparing `winterapi-0.1.1/.github/workflows/pylint.yml` & `winterapi-0.2.0/.github/workflows/pylint.yml`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/.gitignore` & `winterapi-0.2.0/.gitignore`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/.pre-commit-config.yaml` & `winterapi-0.2.0/.pre-commit-config.yaml`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/LICENSE` & `winterapi-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/PKG-INFO` & `winterapi-0.2.0/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: winterapi
-Version: 0.1.1
+Version: 0.2.0
 Author-email: Robert Stein <rdstein@caltech.edu>
 License: MIT
 Project-URL: Homepage, https://github.com/winter-telescope/winterapi
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Intended Audience :: Science/Research
```

### Comparing `winterapi-0.1.1/README.md` & `winterapi-0.2.0/README.md`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/notebooks/0_intro_accounts.ipynb` & `winterapi-0.2.0/notebooks/0_intro_accounts.ipynb`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/notebooks/1_too_models.ipynb` & `winterapi-0.2.0/notebooks/1_too_models.ipynb`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/notebooks/2_submitting_toos.ipynb` & `winterapi-0.2.0/notebooks/2_submitting_toos.ipynb`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/pyproject.toml` & `winterapi-0.2.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools>=45", "setuptools-scm"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name = "winterapi"
-version = "0.1.1"
+version = "0.2.0"
 description = ""
 authors = [
     {name = "Robert Stein", email = "rdstein@caltech.edu"}
 ]
 license = {text = "MIT"}
 readme = "README.md"
 requires-python = ">=3.10"
@@ -31,15 +31,15 @@
     "pandas",
     "keyring",
     "cryptography",
     "pre-commit",
     "jupyter",
     "backoff",
     "pydantic",
-    "wintertoo>=0.3.8"
+    "wintertoo>=0.3.10"
 ]
 [project.optional-dependencies]
 dev = [
     "black == 23.3.0",
     "isort == 5.12.0",
     "pylint == 2.17.4",
     "coveralls",
```

### Comparing `winterapi-0.1.1/tests/test_schedule.py` & `winterapi-0.2.0/tests/test_schedule.py`

 * *Files 2% similar despite different names*

```diff
@@ -55,15 +55,15 @@
         too_list = [too_field, too_radec]
 
         local_schedule = winter.build_schedule_locally(
             program_name=TEST_PROGRAM_NAME, data=too_list
         )
 
         # Uncomment to update the schedule
-        local_schedule.to_csv(test_schedule_path, index=False)
+        # local_schedule.to_csv(test_schedule_path, index=False)
 
         pd.testing.assert_frame_equal(test_df, local_schedule, check_like=True)
 
         api_res, api_schedule = winter.submit_too(
             program_name=TEST_PROGRAM_NAME, data=too_list, submit_trigger=False
         )
```

### Comparing `winterapi-0.1.1/tests/testdata/test_schedule.csv` & `winterapi-0.2.0/tests/testdata/test_schedule.csv`

 * *Files 14% similar despite different names*

```diff
@@ -1,7 +1,7 @@
 raDeg,decDeg,fieldID,filter,visitExpTime,priority,progPI,progName,progID,validStart,validStop,observed,maxAirmass,ditherNumber,ditherStepSize,obsHistID
-211.56398,54.0,3944,Y,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,9,15.0,0
-211.56398,54.0,3944,J,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,9,15.0,1
-211.56398,54.0,3944,Hs,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,9,15.0,2
-210.910674637,54.3116510708,999999999,Y,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,1,15.0,3
-210.910674637,54.3116510708,999999999,J,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,1,15.0,4
-210.910674637,54.3116510708,999999999,Hs,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,1,15.0,5
+211.56398,54.0,3944,Y,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,9,600.0,0
+211.56398,54.0,3944,J,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,9,600.0,1
+211.56398,54.0,3944,Hs,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,9,600.0,2
+210.910674637,54.3116510708,999999999,Y,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,1,600.0,3
+210.910674637,54.3116510708,999999999,J,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,1,600.0,4
+210.910674637,54.3116510708,999999999,Hs,30.0,50.0,Stein,2023A999,1,62721.1894969287,62722.1894969452,False,2.0,1,600.0,5
```

### Comparing `winterapi-0.1.1/winterapi/configure_tests.py` & `winterapi-0.2.0/winterapi/configure_tests.py`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/winterapi/credentials.py` & `winterapi-0.2.0/winterapi/credentials.py`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/winterapi/fidelius.py` & `winterapi-0.2.0/winterapi/fidelius.py`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/winterapi/messenger.py` & `winterapi-0.2.0/winterapi/messenger.py`

 * *Files identical despite different names*

### Comparing `winterapi-0.1.1/winterapi.egg-info/PKG-INFO` & `winterapi-0.2.0/winterapi.egg-info/PKG-INFO`

 * *Files 5% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: winterapi
-Version: 0.1.1
+Version: 0.2.0
 Author-email: Robert Stein <rdstein@caltech.edu>
 License: MIT
 Project-URL: Homepage, https://github.com/winter-telescope/winterapi
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.10
 Classifier: Programming Language :: Python :: 3.11
 Classifier: Intended Audience :: Science/Research
```

### Comparing `winterapi-0.1.1/winterapi.egg-info/SOURCES.txt` & `winterapi-0.2.0/winterapi.egg-info/SOURCES.txt`

 * *Files identical despite different names*


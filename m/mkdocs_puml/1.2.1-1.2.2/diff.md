# Comparing `tmp/mkdocs_puml-1.2.1.tar.gz` & `tmp/mkdocs_puml-1.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "mkdocs_puml-1.2.1.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
+gzip compressed data, was "mkdocs_puml-1.2.2.tar", last modified: Fri Jan  1 00:00:00 2016, max compression
```

## Comparing `mkdocs_puml-1.2.1.tar` & `mkdocs_puml-1.2.2.tar`

### file list

```diff
@@ -1,28 +1,28 @@
--rw-r--r--   0        0        0      237 2022-09-15 12:01:38.953711 mkdocs_puml-1.2.1/.coveragerc
--rw-r--r--   0        0        0    31089 2023-01-25 09:20:39.582596 mkdocs_puml-1.2.1/.docs/logo.png
--rw-r--r--   0        0        0       43 2022-09-15 12:01:38.953802 mkdocs_puml-1.2.1/.flake8
--rw-r--r--   0        0        0      655 2023-01-25 09:42:12.642417 mkdocs_puml-1.2.1/.github/ISSUE_TEMPLATE/bug_report.md
--rw-r--r--   0        0        0      595 2022-11-13 12:18:46.573988 mkdocs_puml-1.2.1/.github/ISSUE_TEMPLATE/feature_request.md
--rw-r--r--   0        0        0     1298 2023-03-22 10:02:51.666715 mkdocs_puml-1.2.1/.github/workflows/checks.yml
--rw-r--r--   0        0        0     5163 2022-09-20 17:56:58.445961 mkdocs_puml-1.2.1/.gitignore
--rw-r--r--   0        0        0      404 2022-09-15 12:01:38.954254 mkdocs_puml-1.2.1/.pre-commit-config.yaml
--rw-r--r--   0        0        0     1082 2022-09-15 12:01:38.954367 mkdocs_puml-1.2.1/LICENSE
--rw-r--r--   0        0        0      448 2023-06-27 15:32:44.516649 mkdocs_puml-1.2.1/Pipfile
--rw-r--r--   0        0        0    72345 2023-06-27 15:33:31.946477 mkdocs_puml-1.2.1/Pipfile.lock
--rw-r--r--   0        0        0     3881 2023-03-22 10:02:51.666879 mkdocs_puml-1.2.1/README.md
--rw-r--r--   0        0        0       68 2023-06-27 15:40:54.778324 mkdocs_puml-1.2.1/mkdocs_puml/__init__.py
--rw-r--r--   0        0        0      948 2023-02-18 11:50:55.936744 mkdocs_puml-1.2.1/mkdocs_puml/encoder.py
--rw-r--r--   0        0        0     4901 2023-06-27 15:27:04.642079 mkdocs_puml-1.2.1/mkdocs_puml/plugin.py
--rw-r--r--   0        0        0     3841 2023-03-22 10:02:51.667311 mkdocs_puml-1.2.1/mkdocs_puml/puml.py
--rw-r--r--   0        0        0      630 2023-06-27 15:44:09.578054 mkdocs_puml-1.2.1/pyproject.toml
--rw-r--r--   0        0        0        0 2022-09-15 12:01:38.956165 mkdocs_puml-1.2.1/tests/__init__.py
--rw-r--r--   0        0        0      866 2023-03-22 10:02:51.667442 mkdocs_puml-1.2.1/tests/conftest.py
--rw-r--r--   0        0        0        0 2022-09-20 17:56:58.447859 mkdocs_puml-1.2.1/tests/plugins/__init__.py
--rw-r--r--   0        0        0     2374 2023-06-27 15:31:49.821706 mkdocs_puml-1.2.1/tests/plugins/conftest.py
--rw-r--r--   0        0        0     2247 2023-06-27 15:24:25.113333 mkdocs_puml-1.2.1/tests/plugins/test_plugin.py
--rw-r--r--   0        0        0      197 2022-09-15 12:01:38.956431 mkdocs_puml-1.2.1/tests/test_encoder.py
--rw-r--r--   0        0        0      876 2023-01-25 09:21:05.750584 mkdocs_puml-1.2.1/tests/test_puml.py
--rw-r--r--   0        0        0     1074 2023-03-22 10:02:51.667954 mkdocs_puml-1.2.1/tests/testdata/markdown.md
--rw-r--r--   0        0        0      375 2022-09-20 17:56:58.448279 mkdocs_puml-1.2.1/tests/testdata/output.html
--rw-r--r--   0        0        0     2255 2022-09-15 12:01:38.956767 mkdocs_puml-1.2.1/tests/testdata/plantuml.svg
--rw-r--r--   0        0        0     4336 1970-01-01 00:00:00.000000 mkdocs_puml-1.2.1/PKG-INFO
+-rw-r--r--   0        0        0      237 2022-09-15 12:01:38.953711 mkdocs_puml-1.2.2/.coveragerc
+-rw-r--r--   0        0        0    31089 2023-01-25 09:20:39.582596 mkdocs_puml-1.2.2/.docs/logo.png
+-rw-r--r--   0        0        0       43 2022-09-15 12:01:38.953802 mkdocs_puml-1.2.2/.flake8
+-rw-r--r--   0        0        0      655 2023-01-25 09:42:12.642417 mkdocs_puml-1.2.2/.github/ISSUE_TEMPLATE/bug_report.md
+-rw-r--r--   0        0        0      595 2022-11-13 12:18:46.573988 mkdocs_puml-1.2.2/.github/ISSUE_TEMPLATE/feature_request.md
+-rw-r--r--   0        0        0     1298 2023-03-22 10:02:51.666715 mkdocs_puml-1.2.2/.github/workflows/checks.yml
+-rw-r--r--   0        0        0     5163 2022-09-20 17:56:58.445961 mkdocs_puml-1.2.2/.gitignore
+-rw-r--r--   0        0        0      404 2022-09-15 12:01:38.954254 mkdocs_puml-1.2.2/.pre-commit-config.yaml
+-rw-r--r--   0        0        0     1082 2022-09-15 12:01:38.954367 mkdocs_puml-1.2.2/LICENSE
+-rw-r--r--   0        0        0      573 2023-06-28 09:32:47.756816 mkdocs_puml-1.2.2/Pipfile
+-rw-r--r--   0        0        0    71332 2023-06-28 09:32:47.757288 mkdocs_puml-1.2.2/Pipfile.lock
+-rw-r--r--   0        0        0     3881 2023-03-22 10:02:51.666879 mkdocs_puml-1.2.2/README.md
+-rw-r--r--   0        0        0       68 2023-06-28 09:32:47.757628 mkdocs_puml-1.2.2/mkdocs_puml/__init__.py
+-rw-r--r--   0        0        0      948 2023-02-18 11:50:55.936744 mkdocs_puml-1.2.2/mkdocs_puml/encoder.py
+-rw-r--r--   0        0        0     5077 2023-06-28 09:32:47.757849 mkdocs_puml-1.2.2/mkdocs_puml/plugin.py
+-rw-r--r--   0        0        0     3841 2023-03-22 10:02:51.667311 mkdocs_puml-1.2.2/mkdocs_puml/puml.py
+-rw-r--r--   0        0        0      628 2023-06-28 09:32:47.758075 mkdocs_puml-1.2.2/pyproject.toml
+-rw-r--r--   0        0        0        0 2022-09-15 12:01:38.956165 mkdocs_puml-1.2.2/tests/__init__.py
+-rw-r--r--   0        0        0      866 2023-03-22 10:02:51.667442 mkdocs_puml-1.2.2/tests/conftest.py
+-rw-r--r--   0        0        0        0 2022-09-20 17:56:58.447859 mkdocs_puml-1.2.2/tests/plugins/__init__.py
+-rw-r--r--   0        0        0     2374 2023-06-28 09:10:05.717513 mkdocs_puml-1.2.2/tests/plugins/conftest.py
+-rw-r--r--   0        0        0     2247 2023-06-28 09:10:05.717746 mkdocs_puml-1.2.2/tests/plugins/test_plugin.py
+-rw-r--r--   0        0        0      197 2022-09-15 12:01:38.956431 mkdocs_puml-1.2.2/tests/test_encoder.py
+-rw-r--r--   0        0        0      876 2023-01-25 09:21:05.750584 mkdocs_puml-1.2.2/tests/test_puml.py
+-rw-r--r--   0        0        0     1074 2023-03-22 10:02:51.667954 mkdocs_puml-1.2.2/tests/testdata/markdown.md
+-rw-r--r--   0        0        0      375 2022-09-20 17:56:58.448279 mkdocs_puml-1.2.2/tests/testdata/output.html
+-rw-r--r--   0        0        0     2255 2022-09-15 12:01:38.956767 mkdocs_puml-1.2.2/tests/testdata/plantuml.svg
+-rw-r--r--   0        0        0     4334 1970-01-01 00:00:00.000000 mkdocs_puml-1.2.2/PKG-INFO
```

### Comparing `mkdocs_puml-1.2.1/.docs/logo.png` & `mkdocs_puml-1.2.2/.docs/logo.png`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/.github/ISSUE_TEMPLATE/bug_report.md` & `mkdocs_puml-1.2.2/.github/ISSUE_TEMPLATE/bug_report.md`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/.github/ISSUE_TEMPLATE/feature_request.md` & `mkdocs_puml-1.2.2/.github/ISSUE_TEMPLATE/feature_request.md`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/.github/workflows/checks.yml` & `mkdocs_puml-1.2.2/.github/workflows/checks.yml`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/.gitignore` & `mkdocs_puml-1.2.2/.gitignore`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/LICENSE` & `mkdocs_puml-1.2.2/LICENSE`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/Pipfile.lock` & `mkdocs_puml-1.2.2/Pipfile.lock`

 * *Files 2% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9611928104575164%*

 * *Differences: {"'_meta'": "{'hash': {'sha256': "*

 * *            "'07c0b6f3bb841007f9906449f08e2a556ce169915f6e63a27cacc2a666d20990'}, 'requires': "*

 * *            "{'python_version': '3.11'}}",*

 * * "'default'": "{delete: ['importlib-metadata', 'zipp']}",*

 * * "'develop'": "{'pytest': {'hashes': "*

 * *              "['sha256:78bf16451a2eb8c7a2ea98e32dc119fd2aa758f1d5d66dbf0a59d69a3969df32', "*

 * *              "'sha256:b4bf8c45bd59934ed84001ad51e11b4ee40d40a1229d2c79f9c592b0a3f6bd8a'], "*

 * *              '\'version\': \'==7.4.0\'}, \'zipp\': {\' […]*

```diff
@@ -1,15 +1,15 @@
 {
     "_meta": {
         "hash": {
-            "sha256": "5c598a2ec407cc0f41ec75ddb78bc692a8808b4edb792caf915beb6627c1aa88"
+            "sha256": "07c0b6f3bb841007f9906449f08e2a556ce169915f6e63a27cacc2a666d20990"
         },
         "pipfile-spec": 6,
         "requires": {
-            "python_version": "3.10"
+            "python_version": "3.11"
         },
         "sources": [
             {
                 "name": "pypi",
                 "url": "https://pypi.org/simple",
                 "verify_ssl": true
             }
@@ -148,22 +148,14 @@
             "hashes": [
                 "sha256:814f528e8dead7d329833b91c5faa87d60bf71824cd12a7530b5526063d02cb4",
                 "sha256:90b77e79eaa3eba6de819a0c442c0b4ceefc341a7a2ab77d7562bf49f425c5c2"
             ],
             "markers": "python_version >= '3.5'",
             "version": "==3.4"
         },
-        "importlib-metadata": {
-            "hashes": [
-                "sha256:1aaf550d4f73e5d6783e7acb77aec43d49da8017410afae93822cc9cca98c4d4",
-                "sha256:cb52082e659e97afc5dac71e79de97d8681de3aa07ff18578330904a9d18e5b5"
-            ],
-            "markers": "python_version < '3.10'",
-            "version": "==6.7.0"
-        },
         "jinja2": {
             "hashes": [
                 "sha256:31351a702a408a9e7595a8fc6150fc3f43bb6bf7e319770cbc0db9df9437e852",
                 "sha256:6088930bfe239f0e6710546ab9c19c9ef35e29792895fed6e6e31a023a182a61"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==3.1.2"
@@ -378,33 +370,17 @@
                 "sha256:c07253088265c363d1ddf4b3cdb808d59a0468ecd017770ed716991620b8f77a",
                 "sha256:c9d8c8ec7efb887333cf71e328e39cffbf771d8f8f95d308ea4125bf5f90ba64",
                 "sha256:d00e6be486affb5781468457b21a6cbe848c33ef43f9ea4a73b4882e5f188a44",
                 "sha256:d429c2430c93b7903914e4db9a966c7f2b068dd2ebdd2fa9b9ce094c7d459f33"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==3.0.0"
-        },
-        "zipp": {
-            "hashes": [
-                "sha256:112929ad649da941c23de50f356a2b5570c954b65150642bccdd66bf194d224b",
-                "sha256:48904fc76a60e542af151aded95726c1a5c34ed43ab4134b597665c86d7ad556"
-            ],
-            "markers": "python_version >= '3.7'",
-            "version": "==3.15.0"
         }
     },
     "develop": {
-        "attrs": {
-            "hashes": [
-                "sha256:1f28b4522cdc2fb4256ac1a020c78acf9cba2c6b461ccd2c126f3aa8e8335d04",
-                "sha256:6279836d581513a26f1bf235f9acd333bc9115683f14f7e8fae46c98fc50e015"
-            ],
-            "markers": "python_version >= '3.7'",
-            "version": "==23.1.0"
-        },
         "bracex": {
             "hashes": [
                 "sha256:351b7f20d56fb9ea91f9b9e9e7664db466eb234188c175fd943f8f755c807e73",
                 "sha256:e7b23fc8b2cd06d3dec0692baabecb249dda94e06a617901ff03a6c56fd71693"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==2.3.post1"
@@ -859,19 +835,19 @@
                 "sha256:b44e1093a43b8a975eae17b03c3a77aad4681b3b56fce60ce746dbef1944c8cb"
             ],
             "markers": "python_version >= '3.7'",
             "version": "==10.0.1"
         },
         "pytest": {
             "hashes": [
-                "sha256:130328f552dcfac0b1cec75c12e3f005619dc5f874f0a06e8ff7263f0ee6225e",
-                "sha256:c99ab0c73aceb050f68929bc93af19ab6db0558791c6a0715723abe9d0ade9d4"
+                "sha256:78bf16451a2eb8c7a2ea98e32dc119fd2aa758f1d5d66dbf0a59d69a3969df32",
+                "sha256:b4bf8c45bd59934ed84001ad51e11b4ee40d40a1229d2c79f9c592b0a3f6bd8a"
             ],
             "index": "pypi",
-            "version": "==7.2.2"
+            "version": "==7.4.0"
         },
         "pytest-cov": {
             "hashes": [
                 "sha256:3904b13dfbfec47f003b8e77fd5b589cd11904a21ddf1ab38a64f204d6a10ef6",
                 "sha256:6ba70b9e97e69fcc3fb45bfeab2d0a138fb65c4d0d6a41ef33983ad114be8c3a"
             ],
             "index": "pypi",
@@ -1123,12 +1099,12 @@
             "version": "==8.4.1"
         },
         "zipp": {
             "hashes": [
                 "sha256:112929ad649da941c23de50f356a2b5570c954b65150642bccdd66bf194d224b",
                 "sha256:48904fc76a60e542af151aded95726c1a5c34ed43ab4134b597665c86d7ad556"
             ],
-            "markers": "python_version >= '3.7'",
+            "markers": "python_version < '3.10'",
             "version": "==3.15.0"
         }
     }
 }
```

### Comparing `mkdocs_puml-1.2.1/README.md` & `mkdocs_puml-1.2.2/README.md`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/mkdocs_puml/encoder.py` & `mkdocs_puml-1.2.2/mkdocs_puml/encoder.py`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/mkdocs_puml/plugin.py` & `mkdocs_puml-1.2.2/mkdocs_puml/plugin.py`

 * *Files 2% similar despite different names*

```diff
@@ -123,15 +123,20 @@
         Returns:
             HTML page containing SVG diagrams
         """
         schemes = self.uuid_regex.findall(output)
         for v in schemes:
             output = self._replace(v, output)
             page.content = self._replace(v, page.content)
-            page.html = self._replace(v, page.html)
+
+            # MkDocs >=1.4 doesn't have html attribute.
+            # TODO: Remove the support of older versions in future releases
+            if hasattr(page, 'html'):
+                page.html = self._replace(v, page.html)
+
         return output
 
     def _replace(self, key: str, content: str) -> str:
         """Replace a UUID key with a real diagram in a
         content
         """
         return content.replace(
```

### Comparing `mkdocs_puml-1.2.1/mkdocs_puml/puml.py` & `mkdocs_puml-1.2.2/mkdocs_puml/puml.py`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/pyproject.toml` & `mkdocs_puml-1.2.2/pyproject.toml`

 * *Files 15% similar despite different names*

```diff
@@ -7,15 +7,15 @@
 authors = [{name = "Mikhail Kravets", email = "michkravets@gmail.com"}]
 readme = "README.md"
 license = {file = "LICENSE"}
 classifiers = ["License :: OSI Approved :: MIT License"]
 dynamic = ["version", "description"]
 requires-python = ">=3.8"
 dependencies = [
-    "requests >= 2.27.0, < 3.0",
+    "requests >= 2.27, < 3.0",
     "markdown >= 3.2.1, < 4.0",
     "mkdocs >= 1.3, < 2.0"
 ]
 
 [project.urls]
 Home = "https://github.com/MikhailKravets/mkdocs_puml"
```

### Comparing `mkdocs_puml-1.2.1/tests/conftest.py` & `mkdocs_puml-1.2.2/tests/conftest.py`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/tests/plugins/conftest.py` & `mkdocs_puml-1.2.2/tests/plugins/conftest.py`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/tests/plugins/test_plugin.py` & `mkdocs_puml-1.2.2/tests/plugins/test_plugin.py`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/tests/test_puml.py` & `mkdocs_puml-1.2.2/tests/test_puml.py`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/tests/testdata/markdown.md` & `mkdocs_puml-1.2.2/tests/testdata/markdown.md`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/tests/testdata/plantuml.svg` & `mkdocs_puml-1.2.2/tests/testdata/plantuml.svg`

 * *Files identical despite different names*

### Comparing `mkdocs_puml-1.2.1/PKG-INFO` & `mkdocs_puml-1.2.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,16 +1,16 @@
 Metadata-Version: 2.1
 Name: mkdocs_puml
-Version: 1.2.1
+Version: 1.2.2
 Summary: Package that brings PlantUML to MkDocs
 Author-email: Mikhail Kravets <michkravets@gmail.com>
 Requires-Python: >=3.8
 Description-Content-Type: text/markdown
 Classifier: License :: OSI Approved :: MIT License
-Requires-Dist: requests >= 2.27.0, < 3.0
+Requires-Dist: requests >= 2.27, < 3.0
 Requires-Dist: markdown >= 3.2.1, < 4.0
 Requires-Dist: mkdocs >= 1.3, < 2.0
 Project-URL: Home, https://github.com/MikhailKravets/mkdocs_puml
 
 ![logo](.docs/logo.png)
 
 [![PyPI version](https://badge.fury.io/py/mkdocs_puml.svg)](https://badge.fury.io/py/mkdocs_puml)
```


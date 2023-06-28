# Comparing `tmp/alephclient-2.3.5.tar.gz` & `tmp/alephclient-2.3.6.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "alephclient-2.3.5.tar", last modified: Fri Aug 20 14:35:09 2021, max compression
+gzip compressed data, was "alephclient-2.3.6.tar", last modified: Wed Jun 28 11:41:48 2023, max compression
```

## Comparing `alephclient-2.3.5.tar` & `alephclient-2.3.6.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2021-08-20 14:35:09.662690 alephclient-2.3.5/
--rw-r--r--   0 runner    (1001) docker     (121)     1099 2021-08-20 14:34:54.000000 alephclient-2.3.5/LICENSE
--rw-r--r--   0 runner    (1001) docker     (121)     1198 2021-08-20 14:35:09.662690 alephclient-2.3.5/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      472 2021-08-20 14:34:54.000000 alephclient-2.3.5/README.md
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2021-08-20 14:35:09.662690 alephclient-2.3.5/alephclient/
--rw-r--r--   0 runner    (1001) docker     (121)        0 2021-08-20 14:34:54.000000 alephclient-2.3.5/alephclient/__init__.py
--rw-r--r--   0 runner    (1001) docker     (121)    18979 2021-08-20 14:34:54.000000 alephclient-2.3.5/alephclient/api.py
--rw-r--r--   0 runner    (1001) docker     (121)    12016 2021-08-20 14:34:54.000000 alephclient-2.3.5/alephclient/cli.py
--rw-r--r--   0 runner    (1001) docker     (121)     6079 2021-08-20 14:34:54.000000 alephclient-2.3.5/alephclient/crawldir.py
--rw-r--r--   0 runner    (1001) docker     (121)      751 2021-08-20 14:34:54.000000 alephclient-2.3.5/alephclient/errors.py
--rw-r--r--   0 runner    (1001) docker     (121)     2645 2021-08-20 14:34:54.000000 alephclient-2.3.5/alephclient/fetchdir.py
--rw-r--r--   0 runner    (1001) docker     (121)      504 2021-08-20 14:34:54.000000 alephclient-2.3.5/alephclient/settings.py
--rw-r--r--   0 runner    (1001) docker     (121)      545 2021-08-20 14:34:54.000000 alephclient-2.3.5/alephclient/util.py
-drwxr-xr-x   0 runner    (1001) docker     (121)        0 2021-08-20 14:35:09.662690 alephclient-2.3.5/alephclient.egg-info/
--rw-r--r--   0 runner    (1001) docker     (121)     1198 2021-08-20 14:35:09.000000 alephclient-2.3.5/alephclient.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (121)      424 2021-08-20 14:35:09.000000 alephclient-2.3.5/alephclient.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (121)        1 2021-08-20 14:35:09.000000 alephclient-2.3.5/alephclient.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (121)       53 2021-08-20 14:35:09.000000 alephclient-2.3.5/alephclient.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (121)      118 2021-08-20 14:35:09.000000 alephclient-2.3.5/alephclient.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (121)       12 2021-08-20 14:35:09.000000 alephclient-2.3.5/alephclient.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (121)      108 2021-08-20 14:35:09.666689 alephclient-2.3.5/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (121)     1214 2021-08-20 14:34:54.000000 alephclient-2.3.5/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:41:48.718828 alephclient-2.3.6/
+-rw-r--r--   0 runner    (1001) docker     (123)     1099 2023-06-28 11:41:30.000000 alephclient-2.3.6/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     1038 2023-06-28 11:41:48.718828 alephclient-2.3.6/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      472 2023-06-28 11:41:30.000000 alephclient-2.3.6/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:41:48.718828 alephclient-2.3.6/alephclient/
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 11:41:30.000000 alephclient-2.3.6/alephclient/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    19103 2023-06-28 11:41:30.000000 alephclient-2.3.6/alephclient/api.py
+-rw-r--r--   0 runner    (1001) docker     (123)    12016 2023-06-28 11:41:30.000000 alephclient-2.3.6/alephclient/cli.py
+-rw-r--r--   0 runner    (1001) docker     (123)     6079 2023-06-28 11:41:30.000000 alephclient-2.3.6/alephclient/crawldir.py
+-rw-r--r--   0 runner    (1001) docker     (123)      751 2023-06-28 11:41:30.000000 alephclient-2.3.6/alephclient/errors.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2645 2023-06-28 11:41:30.000000 alephclient-2.3.6/alephclient/fetchdir.py
+-rw-r--r--   0 runner    (1001) docker     (123)      504 2023-06-28 11:41:30.000000 alephclient-2.3.6/alephclient/settings.py
+-rw-r--r--   0 runner    (1001) docker     (123)      545 2023-06-28 11:41:30.000000 alephclient-2.3.6/alephclient/util.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 11:41:48.718828 alephclient-2.3.6/alephclient.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     1038 2023-06-28 11:41:48.000000 alephclient-2.3.6/alephclient.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      424 2023-06-28 11:41:48.000000 alephclient-2.3.6/alephclient.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 11:41:48.000000 alephclient-2.3.6/alephclient.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       52 2023-06-28 11:41:48.000000 alephclient-2.3.6/alephclient.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      118 2023-06-28 11:41:48.000000 alephclient-2.3.6/alephclient.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-28 11:41:48.000000 alephclient-2.3.6/alephclient.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      108 2023-06-28 11:41:48.718828 alephclient-2.3.6/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1214 2023-06-28 11:41:30.000000 alephclient-2.3.6/setup.py
```

### Comparing `alephclient-2.3.5/LICENSE` & `alephclient-2.3.6/LICENSE`

 * *Files identical despite different names*

### Comparing `alephclient-2.3.5/PKG-INFO` & `alephclient-2.3.6/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,36 +1,37 @@
 Metadata-Version: 2.1
 Name: alephclient
-Version: 2.3.5
+Version: 2.3.6
 Summary: Command-line client for Aleph API
 Home-page: http://github.com/alephdata/alephclient
 Author: Organized Crime and Corruption Reporting Project
 Author-email: data@occrp.org
 License: MIT
-Description: # alephclient
-        
-        Command-line client for Aleph. It can be used to bulk import document sets via
-        the API, without direct access to the server. It requires an active API client
-        to perform uploads.
-        
-        ## Installation
-        
-        Install using `pip`.
-        
-        ```bash
-        pip install alephclient
-        ```
-        
-        ## Usage
-        
-        Refer to the `aleph` handbook for an introduction on how to use `alephclient`,
-        e.g. to crawl a local file directory, or to stream entities:
-        
-        * https://docs.alephdata.org/developers/alephclient
-Platform: UNKNOWN
 Classifier: Intended Audience :: Developers
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Description-Content-Type: text/markdown
 Provides-Extra: dev
+License-File: LICENSE
+
+# alephclient
+
+Command-line client for Aleph. It can be used to bulk import document sets via
+the API, without direct access to the server. It requires an active API client
+to perform uploads.
+
+## Installation
+
+Install using `pip`.
+
+```bash
+pip install alephclient
+```
+
+## Usage
+
+Refer to the `aleph` handbook for an introduction on how to use `alephclient`,
+e.g. to crawl a local file directory, or to stream entities:
+
+* https://docs.alephdata.org/developers/alephclient
```

### Comparing `alephclient-2.3.5/alephclient/api.py` & `alephclient-2.3.6/alephclient/api.py`

 * *Files 2% similar despite different names*

```diff
@@ -3,14 +3,15 @@
 import logging
 import pkg_resources
 from itertools import count
 from pathlib import Path
 from urllib.parse import urlencode, urljoin
 from banal import ensure_dict, ensure_list
 from requests import RequestException, Session
+from requests.exceptions import HTTPError
 from requests_toolbelt import MultipartEncoder  # type: ignore
 from typing import Dict, Mapping, Iterable, Iterator, List, Optional, Any
 
 from alephclient import settings
 from alephclient.errors import AlephException
 from alephclient.util import backoff, prop_push
 
@@ -154,15 +155,15 @@
         Having a single point to make all requests let's us set headers, manage
         successful and failed responses and possibly manage session etc
         conviniently in a single place.
         """
         try:
             response = self.session.request(method=method, url=url, **kwargs)
             response.raise_for_status()
-        except RequestException as exc:
+        except (RequestException, HTTPError) as exc:
             raise AlephException(exc) from exc
 
         if len(response.text):
             return response.json()
         return {}
 
     def search(
@@ -252,15 +253,15 @@
                 "category": config_.get("category", "other"),
                 "languages": config_.get("languages", []),
                 "summary": config_.get("summary", ""),
             }
         )
 
     def filter_collections(
-        self, query: str = None, filters: Optional[List] = None, **kwargs
+        self, query: Optional[str] = None, filters: Optional[List] = None, **kwargs
     ) -> "APIResultSet":
         """Filter collections for the given query and/or filters.
 
         params
         ------
         query: query string
         filters: list of key, value pairs to filter collections
@@ -322,15 +323,15 @@
             res = self.session.get(url, params=params, stream=True)
             res.raise_for_status()
             for entity in res.iter_lines(chunk_size=None):
                 entity = json.loads(entity)
                 yield self._patch_entity(
                     entity, publisher=publisher, collection=collection
                 )
-        except RequestException as exc:
+        except (RequestException, HTTPError) as exc:
             raise AlephException(exc) from exc
 
     def _bulk_chunk(
         self,
         collection_id: str,
         chunk: List,
         entityset_id: Optional[str] = None,
@@ -340,25 +341,25 @@
         for attempt in count(1):
             url = self._make_url(f"collections/{collection_id}/_bulk")
             params = {"unsafe": unsafe, "entityset_id": entityset_id}
             try:
                 response = self.session.post(url, json=chunk, params=params)
                 response.raise_for_status()
                 return
-            except RequestException as exc:
+            except (RequestException, HTTPError) as exc:
                 ae = AlephException(exc)
                 if not ae.transient or attempt > self.retries:
                     if not force:
                         raise ae from exc
                     log.error(ae)
                     return
                 backoff(ae, attempt)
 
     def write_entity(
-        self, collection_id: str, entity: Dict, entity_id: str = None, **kw
+        self, collection_id: str, entity: Dict, entity_id: Optional[str] = None, **kw
     ) -> Dict:
         """Create a single entity via the API, in the given
         collection.
 
         params
         ------
         collection_id: id of the collection to use. This will overwrite any
@@ -410,27 +411,27 @@
         if len(chunk):
             self._bulk_chunk(collection_id, chunk, **kw)
 
     def match(
         self,
         entity: Dict,
         collection_ids: Optional[str] = None,
-        url: str = None,
+        url: Optional[str] = None,
         publisher: bool = False,
     ) -> Iterator[List]:
         """Find similar entities given a sample entity."""
         params = {"collection_ids": ensure_list(collection_ids)}
         if url is None:
             url = self._make_url("match")
         try:
             response = self.session.post(url, json=entity, params=params)  # type: ignore
             response.raise_for_status()
             for result in response.json().get("results", []):
                 yield self._patch_entity(result, publisher=publisher)
-        except RequestException as exc:
+        except (RequestException, HTTPError) as exc:
             raise AlephException(exc) from exc
 
     def entitysets(
         self,
         collection_id: Optional[str] = None,
         set_types: Optional[List] = None,
         prefix: Optional[str] = None,
```

### Comparing `alephclient-2.3.5/alephclient/cli.py` & `alephclient-2.3.6/alephclient/cli.py`

 * *Files identical despite different names*

### Comparing `alephclient-2.3.5/alephclient/crawldir.py` & `alephclient-2.3.6/alephclient/crawldir.py`

 * *Files identical despite different names*

### Comparing `alephclient-2.3.5/alephclient/errors.py` & `alephclient-2.3.6/alephclient/errors.py`

 * *Files identical despite different names*

### Comparing `alephclient-2.3.5/alephclient/fetchdir.py` & `alephclient-2.3.6/alephclient/fetchdir.py`

 * *Files identical despite different names*

### Comparing `alephclient-2.3.5/alephclient/util.py` & `alephclient-2.3.6/alephclient/util.py`

 * *Files identical despite different names*

### Comparing `alephclient-2.3.5/alephclient.egg-info/PKG-INFO` & `alephclient-2.3.6/alephclient.egg-info/PKG-INFO`

 * *Files 14% similar despite different names*

```diff
@@ -1,36 +1,37 @@
 Metadata-Version: 2.1
 Name: alephclient
-Version: 2.3.5
+Version: 2.3.6
 Summary: Command-line client for Aleph API
 Home-page: http://github.com/alephdata/alephclient
 Author: Organized Crime and Corruption Reporting Project
 Author-email: data@occrp.org
 License: MIT
-Description: # alephclient
-        
-        Command-line client for Aleph. It can be used to bulk import document sets via
-        the API, without direct access to the server. It requires an active API client
-        to perform uploads.
-        
-        ## Installation
-        
-        Install using `pip`.
-        
-        ```bash
-        pip install alephclient
-        ```
-        
-        ## Usage
-        
-        Refer to the `aleph` handbook for an introduction on how to use `alephclient`,
-        e.g. to crawl a local file directory, or to stream entities:
-        
-        * https://docs.alephdata.org/developers/alephclient
-Platform: UNKNOWN
 Classifier: Intended Audience :: Developers
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python
 Classifier: Programming Language :: Python :: 3.6
 Classifier: Programming Language :: Python :: 3.7
 Description-Content-Type: text/markdown
 Provides-Extra: dev
+License-File: LICENSE
+
+# alephclient
+
+Command-line client for Aleph. It can be used to bulk import document sets via
+the API, without direct access to the server. It requires an active API client
+to perform uploads.
+
+## Installation
+
+Install using `pip`.
+
+```bash
+pip install alephclient
+```
+
+## Usage
+
+Refer to the `aleph` handbook for an introduction on how to use `alephclient`,
+e.g. to crawl a local file directory, or to stream entities:
+
+* https://docs.alephdata.org/developers/alephclient
```

### Comparing `alephclient-2.3.5/setup.py` & `alephclient-2.3.6/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from setuptools import setup, find_packages  # type: ignore
 
 with open("README.md") as f:
     long_description = f.read()
 
 setup(
     name="alephclient",
-    version="2.3.5",
+    version="2.3.6",
     description="Command-line client for Aleph API",
     long_description=long_description,
     long_description_content_type="text/markdown",
     author="Organized Crime and Corruption Reporting Project",
     author_email="data@occrp.org",
     url="http://github.com/alephdata/alephclient",
     license="MIT",
```


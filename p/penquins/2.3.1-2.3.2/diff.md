# Comparing `tmp/penquins-2.3.1.tar.gz` & `tmp/penquins-2.3.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "penquins-2.3.1.tar", last modified: Wed Jun  7 07:31:43 2023, max compression
+gzip compressed data, was "penquins-2.3.2.tar", last modified: Wed Jun 28 08:03:04 2023, max compression
```

## Comparing `penquins-2.3.1.tar` & `penquins-2.3.2.tar`

### file list

```diff
@@ -1,14 +1,14 @@
-drwxr-xr-x   0 mcoughlin   (501) staff       (20)        0 2023-06-07 07:31:43.822434 penquins-2.3.1/
--rw-r--r--   0 mcoughlin   (501) staff       (20)     1068 2023-06-07 07:31:26.000000 penquins-2.3.1/LICENSE
--rw-r--r--   0 mcoughlin   (501) staff       (20)      229 2023-06-07 07:31:43.822250 penquins-2.3.1/PKG-INFO
-drwxr-xr-x   0 mcoughlin   (501) staff       (20)        0 2023-06-07 07:31:43.821272 penquins-2.3.1/penquins/
--rw-r--r--   0 mcoughlin   (501) staff       (20)       24 2023-06-07 07:31:26.000000 penquins-2.3.1/penquins/__init__.py
--rw-r--r--   0 mcoughlin   (501) staff       (20)    34772 2023-06-07 07:31:26.000000 penquins-2.3.1/penquins/penquins.py
-drwxr-xr-x   0 mcoughlin   (501) staff       (20)        0 2023-06-07 07:31:43.822034 penquins-2.3.1/penquins.egg-info/
--rw-r--r--   0 mcoughlin   (501) staff       (20)      229 2023-06-07 07:31:43.000000 penquins-2.3.1/penquins.egg-info/PKG-INFO
--rw-r--r--   0 mcoughlin   (501) staff       (20)      217 2023-06-07 07:31:43.000000 penquins-2.3.1/penquins.egg-info/SOURCES.txt
--rw-r--r--   0 mcoughlin   (501) staff       (20)        1 2023-06-07 07:31:43.000000 penquins-2.3.1/penquins.egg-info/dependency_links.txt
--rw-r--r--   0 mcoughlin   (501) staff       (20)      125 2023-06-07 07:31:43.000000 penquins-2.3.1/penquins.egg-info/requires.txt
--rw-r--r--   0 mcoughlin   (501) staff       (20)        9 2023-06-07 07:31:43.000000 penquins-2.3.1/penquins.egg-info/top_level.txt
--rw-r--r--   0 mcoughlin   (501) staff       (20)       38 2023-06-07 07:31:43.822482 penquins-2.3.1/setup.cfg
--rw-r--r--   0 mcoughlin   (501) staff       (20)     5197 2023-06-07 07:31:26.000000 penquins-2.3.1/setup.py
+drwxr-xr-x   0 mcoughlin   (501) staff       (20)        0 2023-06-28 08:03:04.442830 penquins-2.3.2/
+-rw-r--r--   0 mcoughlin   (501) staff       (20)     1068 2023-06-28 08:02:36.000000 penquins-2.3.2/LICENSE
+-rw-r--r--   0 mcoughlin   (501) staff       (20)      229 2023-06-28 08:03:04.442651 penquins-2.3.2/PKG-INFO
+drwxr-xr-x   0 mcoughlin   (501) staff       (20)        0 2023-06-28 08:03:04.441705 penquins-2.3.2/penquins/
+-rw-r--r--   0 mcoughlin   (501) staff       (20)       24 2023-06-28 08:02:36.000000 penquins-2.3.2/penquins/__init__.py
+-rw-r--r--   0 mcoughlin   (501) staff       (20)    29236 2023-06-28 08:02:36.000000 penquins-2.3.2/penquins/penquins.py
+drwxr-xr-x   0 mcoughlin   (501) staff       (20)        0 2023-06-28 08:03:04.442459 penquins-2.3.2/penquins.egg-info/
+-rw-r--r--   0 mcoughlin   (501) staff       (20)      229 2023-06-28 08:03:04.000000 penquins-2.3.2/penquins.egg-info/PKG-INFO
+-rw-r--r--   0 mcoughlin   (501) staff       (20)      217 2023-06-28 08:03:04.000000 penquins-2.3.2/penquins.egg-info/SOURCES.txt
+-rw-r--r--   0 mcoughlin   (501) staff       (20)        1 2023-06-28 08:03:04.000000 penquins-2.3.2/penquins.egg-info/dependency_links.txt
+-rw-r--r--   0 mcoughlin   (501) staff       (20)       60 2023-06-28 08:03:04.000000 penquins-2.3.2/penquins.egg-info/requires.txt
+-rw-r--r--   0 mcoughlin   (501) staff       (20)        9 2023-06-28 08:03:04.000000 penquins-2.3.2/penquins.egg-info/top_level.txt
+-rw-r--r--   0 mcoughlin   (501) staff       (20)       38 2023-06-28 08:03:04.442876 penquins-2.3.2/setup.cfg
+-rw-r--r--   0 mcoughlin   (501) staff       (20)     5088 2023-06-28 08:02:36.000000 penquins-2.3.2/setup.py
```

### Comparing `penquins-2.3.1/LICENSE` & `penquins-2.3.2/LICENSE`

 * *Files identical despite different names*

### Comparing `penquins-2.3.1/penquins/penquins.py` & `penquins-2.3.2/penquins/penquins.py`

 * *Files 14% similar despite different names*

```diff
@@ -5,71 +5,41 @@
 import os
 import secrets
 import string
 import traceback
 from copy import deepcopy
 from multiprocessing.pool import ThreadPool
 from netrc import netrc
-from pathlib import Path
-from typing import List, Mapping, Optional, Sequence, Union, Tuple
+from typing import Mapping, Optional, Sequence, Union, Tuple
 
-import astropy.units as u
-import astropy_healpix as ah
-import healpy as hp
 import requests
-from astropy.io import fits
 from bson.json_util import loads
-from mocpy import MOC
 from requests.adapters import DEFAULT_POOLBLOCK, DEFAULT_POOLSIZE, HTTPAdapter
 from requests.packages.urllib3.util.retry import Retry
 from tqdm.auto import tqdm
 
-__version__ = "2.3.1"
+__version__ = "2.3.2"
 
 Num = Union[int, float]
 
 DEFAULT_TIMEOUT: int = 5  # seconds
 DEFAULT_RETRIES: int = 3
 DEFAULT_BACKOFF_FACTOR: int = 1
 
 query_type_one_catalog = [
     "find_one",
     "find",
+    "skymap",
     "schemas",
     "count_documents",
     "estimated_document_count",
 ]
 query_type_multiple_catalogs = ["cone_search", "near"]
 
 
-def get_cones(path, cumprob):  # path or file-like object
-    max_order = None
-    with fits.open(path) as hdul:
-        hdul[1].columns
-        data = hdul[1].data
-        max_order = hdul[1].header["MOCORDER"]
-
-    uniq = data["UNIQ"]
-    probdensity = data["PROBDENSITY"]
-
-    level, _ = ah.uniq_to_level_ipix(uniq)
-    area = ah.nside_to_pixel_area(ah.level_to_nside(level)).to_value(u.steradian)
-    prob = probdensity * area
-
-    moc = MOC.from_valued_healpix_cells(uniq, prob, max_order, cumul_to=cumprob)
-    moc_json = moc.serialize(format="json")
-    cones = []
-    for order, values in moc_json.items():
-        for value in values:
-            ra, dec = hp.pix2ang(2 ** int(order), int(value), lonlat=True, nest=True)
-            r = hp.max_pixrad(2 ** int(order), degrees=True)
-            cones.append([ra, dec, r])
-    return cones
-
-
 class TimeoutHTTPAdapter(HTTPAdapter):
     def __init__(self, *args, **kwargs):
         self.timeout = DEFAULT_TIMEOUT
         if "timeout" in kwargs:
             self.timeout = kwargs["timeout"]
             del kwargs["timeout"]
         super().__init__(*args, **kwargs)
@@ -197,14 +167,15 @@
             self.instances[name]["session"].trust_env = False
             self.instances[name]["methods"] = {
                 "get": self.instances[name]["session"].get,
                 "post": self.instances[name]["session"].post,
                 "put": self.instances[name]["session"].put,
                 "patch": self.instances[name]["session"].patch,
                 "delete": self.instances[name]["session"].delete,
+                "head": self.instances[name]["session"].head,
             }
             # mount session adapters
             timeout = kwargs.get("timeout", DEFAULT_TIMEOUT)
             pool_connections = kwargs.get("pool_connections", DEFAULT_POOLSIZE)
             pool_maxsize = kwargs.get("pool_maxsize", DEFAULT_POOLSIZE)
             max_retries = kwargs.get("max_retries", DEFAULT_RETRIES)
             backoff_factor = kwargs.get("backoff_factor", DEFAULT_BACKOFF_FACTOR)
@@ -226,15 +197,15 @@
             self.instances[name]["session"].mount("https://", adapter)
             self.instances[name]["session"].mount("http://", adapter)
 
             # set up authentication headers
             if cfg.get("token", None) is None:
                 self.instances[name]["username"] = cfg.get("username", None)
                 self.instances[name]["password"] = cfg.get("password", None)
-                self.instances[name]["token"] = self.authenticate()
+                self.instances[name]["token"] = self.authenticate(name)
             else:
                 self.instances[name]["token"] = cfg.get("token", None)
 
             self.instances[name]["headers"] = {
                 "Authorization": self.instances[name]["token"]
             }
             # if we now have more than one instance, set multiple_instances to True
@@ -398,15 +369,15 @@
 
         method = method.lower()
         # allow using both "/<path>/<endpoint>" and "<path>/<endpoint>"
         endpoint = endpoint[1:] if endpoint.startswith("/") else endpoint
 
         if endpoint is None:
             raise ValueError("Endpoint not specified")
-        if method not in ["get", "post", "put", "patch", "delete"]:
+        if method not in ["get", "post", "put", "patch", "delete", "head"]:
             raise ValueError(f"Unsupported method: {method}")
 
         if method != "get":
             resp = self.instances[name]["methods"][method](
                 os.path.join(self.instances[name]["base_url"], endpoint),
                 json=data,
                 headers=self.instances[name]["headers"],
@@ -414,15 +385,28 @@
         else:
             resp = self.instances[name]["methods"][method](
                 os.path.join(self.instances[name]["base_url"], endpoint),
                 params=data,
                 headers=self.instances[name]["headers"],
             )
 
-        return loads(resp.text)
+        status_mapper = {
+            200: "success",
+            400: "error",
+        }
+        content = {}
+        try:
+            content = loads(resp.text)
+        except Exception:
+            content = {
+                "status": status_mapper.get(resp.status_code, "unknown"),
+                "message": resp.text,
+            }
+
+        return content
 
     def get_catalogs(self, name=None) -> dict:
         if name is None:
             if not self.multiple_instances:
                 name = list(self.instances.keys())[0]
             else:
                 raise ValueError(
@@ -744,144 +728,7 @@
             else:
                 results = {}
                 for name in queries_split_in_queries.keys():
                     for query in queries_split_in_queries[name]:
                         if query is not None:
                             results.update(self.single_query((query, name)))
                 return results
-
-    def query_skymap(
-        self,
-        path: Path,  # path or file-like object
-        cumprob: float,
-        jd_start: float,
-        jd_end: float,
-        jdstarthist_start: float,
-        jdstarthist_end: float,
-        catalogs: List[str],
-        program_ids: List[int],
-        filter_kwargs: Optional[Mapping] = dict(),
-        projection_kwargs: Optional[Mapping] = dict(),
-        max_n_threads: int = 4,
-    ) -> List[dict]:
-        """
-        Query Kowalski for objects in a skymap
-
-        :param path: path to skymap file
-        :param cumprob: cumulative probability threshold
-        :param jd_start: Query candidates detected after this JD
-        :param jd_end: Query candidates detected before this JD
-        :param jdstarthist_start: Query candidates first detected after this JD
-        (i.e. with jdstarthist > jdstarthist_start). This is to ensure sub-threshold
-        detections that sometimes show up in jdstarthist are also retrieved.
-        :param jdstarthist_end: Query candidates first detected before this JD
-        (i.e. with jdstarthist < jdstarthist_end)
-        :param catalogs: List of catalogs to query
-        :param program_ids: List of program IDs to query
-        :param filter_kwargs: Additional filter kwargs
-        :param projection_kwargs: Additional projection kwargs
-        :param max_n_threads: Maximum number of threads to use
-        """
-        missing_args = [
-            arg
-            for arg in [
-                path,
-                cumprob,
-                jd_start,
-                jd_end,
-                catalogs,
-                program_ids,
-            ]
-            if arg is None
-        ]
-        if len(missing_args) > 0:
-            raise ValueError(f"Missing arguments: {missing_args}")
-
-        cones = get_cones(path, cumprob)
-
-        if isinstance(projection_kwargs, dict):
-            if projection_kwargs.get("candid", 1) == 0:
-                raise ValueError(
-                    "candid cannot be excluded from projection. Do not set it to 0."
-                )
-
-        filter = {
-            "candidate.jd": {"$gt": jd_start, "$lt": jd_end},
-            "candidate.jdstarthist": {
-                "$gt": jdstarthist_start,
-                "$lt": jdstarthist_end,
-            },
-            "candidate.programid": {
-                "$in": program_ids
-            },  # 1 = ZTF Public, 2 = ZTF Public+Partnership, 3 = ZTF Public+Partnership+Caltech
-        }
-
-        for k in filter_kwargs.keys():
-            filter[k] = filter_kwargs[k]
-
-        projection = {
-            "_id": 0,
-            "candid": 1,
-            "objectId": 1,
-            "candidate.ra": 1,
-            "candidate.dec": 1,
-            "candidate.jd": 1,
-            "candidate.jdendhist": 1,
-            "candidate.magpsf": 1,
-            "candidate.sigmapsf": 1,
-        }
-
-        for k in projection_kwargs.keys():
-            projection[k] = projection_kwargs[k]
-
-        queries = []
-        for cone in cones:
-            query = {
-                "query_type": "cone_search",
-                "query": {
-                    "object_coordinates": {
-                        "cone_search_radius": cone[2],
-                        "cone_search_unit": "deg",
-                        "radec": {"object": [cone[0], cone[1]]},
-                    },
-                    "catalogs": {
-                        catalog: {
-                            "filter": filter,
-                            "projection": projection,
-                        }
-                        for catalog in catalogs
-                    },
-                },
-            }
-
-            queries.append(query)
-
-        response = self.query(
-            queries=queries, use_batch_query=True, max_n_threads=max_n_threads
-        )
-
-        candidates_per_catalogs_per_instance = {
-            name: {catalog: [] for catalog in self.instances[name]["catalogs"]}
-            for name in list(self.instances.keys())
-        }
-
-        # first we have on response per query. Each response contains a dict with one key per instance
-        for name in list(response.keys()):
-            for response in response[name]:
-                data = response.get("data", None)
-                if data is None:
-                    continue
-                for catalog in catalogs:
-                    candidates_per_catalogs_per_instance[name][catalog].extend(
-                        data[catalog]["object"]
-                    )
-
-        for name in candidates_per_catalogs_per_instance.keys():  # remove duplicates
-            for catalog in candidates_per_catalogs_per_instance[name].keys():
-                candidates_per_catalogs_per_instance[name][catalog] = list(
-                    {
-                        c["candid"]: c
-                        for c in candidates_per_catalogs_per_instance[name][catalog]
-                    }.values()
-                )
-
-        return candidates_per_catalogs_per_instance
```

### Comparing `penquins-2.3.1/setup.py` & `penquins-2.3.2/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -130,33 +130,29 @@
 LONG_DESCRIPTION = ""
 AUTHOR = "Dmitry A. Duev"
 AUTHOR_EMAIL = "duev@caltech.edu"
 LICENSE = "MIT"
 URL = "https://github.com/dmitryduev/penquins"
 
 # VERSION should be PEP386 compatible (http://www.python.org/dev/peps/pep-0386)
-VERSION = "2.3.1"
+VERSION = "2.3.2"
 
 # Indicates if this version is a release version
 RELEASE = "dev" not in VERSION
 
 if not RELEASE:
     VERSION += get_git_devstr(sha=False)
 
 
 setup(
     name=PACKAGENAME,
     version=VERSION,
     description=DESCRIPTION,
     packages=["penquins"],
     install_requires=[
-        "astropy>=5.2.1",
-        "astropy-healpix>=0.7",
-        "healpy>=1.16.0",
-        "mocpy>=0.11.0",
         "pymongo>=3.10.1",
         "pytest>=5.3.1",
         "requests>=2.25.0",
         "tqdm>=4.46.0",
     ],
     author=AUTHOR,
     author_email=AUTHOR_EMAIL,
```


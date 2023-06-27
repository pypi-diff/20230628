# Comparing `tmp/whistleaio-0.1.0.tar.gz` & `tmp/whistleaio-0.1.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "whistleaio-0.1.0.tar", last modified: Tue Aug 30 18:49:03 2022, max compression
+gzip compressed data, was "whistleaio-0.1.1.tar", last modified: Tue Jun 27 23:37:50 2023, max compression
```

## Comparing `whistleaio-0.1.0.tar` & `whistleaio-0.1.1.tar`

### file list

```diff
@@ -1,18 +1,18 @@
-drwxr-xr-x   0 robertdrinovac   (501) staff       (20)        0 2022-08-30 18:49:03.906084 whistleaio-0.1.0/
--rw-rw-r--   0 robertdrinovac   (501) staff       (20)     1067 2022-08-17 23:44:55.000000 whistleaio-0.1.0/LICENSE
--rw-r--r--   0 robertdrinovac   (501) staff       (20)     1282 2022-08-30 18:49:03.905661 whistleaio-0.1.0/PKG-INFO
--rw-r--r--   0 robertdrinovac   (501) staff       (20)      460 2022-08-29 21:32:07.000000 whistleaio-0.1.0/README.md
--rw-r--r--   0 robertdrinovac   (501) staff       (20)       38 2022-08-30 18:49:03.906254 whistleaio-0.1.0/setup.cfg
--rw-rw-r--   0 robertdrinovac   (501) staff       (20)      981 2022-08-29 21:35:48.000000 whistleaio-0.1.0/setup.py
-drwxr-xr-x   0 robertdrinovac   (501) staff       (20)        0 2022-08-30 18:49:03.903119 whistleaio-0.1.0/whistleaio/
--rw-r--r--   0 robertdrinovac   (501) staff       (20)      499 2022-08-29 21:27:36.000000 whistleaio-0.1.0/whistleaio/__init__.py
--rw-r--r--   0 robertdrinovac   (501) staff       (20)     6654 2022-08-29 21:23:59.000000 whistleaio-0.1.0/whistleaio/client.py
--rw-r--r--   0 robertdrinovac   (501) staff       (20)      666 2022-08-29 20:14:30.000000 whistleaio-0.1.0/whistleaio/const.py
--rw-r--r--   0 robertdrinovac   (501) staff       (20)      255 2022-08-26 20:52:04.000000 whistleaio-0.1.0/whistleaio/exceptions.py
--rw-r--r--   0 robertdrinovac   (501) staff       (20)      470 2022-08-26 22:31:17.000000 whistleaio-0.1.0/whistleaio/model.py
-drwxr-xr-x   0 robertdrinovac   (501) staff       (20)        0 2022-08-30 18:49:03.905107 whistleaio-0.1.0/whistleaio.egg-info/
--rw-r--r--   0 robertdrinovac   (501) staff       (20)     1282 2022-08-30 18:49:03.000000 whistleaio-0.1.0/whistleaio.egg-info/PKG-INFO
--rw-r--r--   0 robertdrinovac   (501) staff       (20)      304 2022-08-30 18:49:03.000000 whistleaio-0.1.0/whistleaio.egg-info/SOURCES.txt
--rw-r--r--   0 robertdrinovac   (501) staff       (20)        1 2022-08-30 18:49:03.000000 whistleaio-0.1.0/whistleaio.egg-info/dependency_links.txt
--rw-r--r--   0 robertdrinovac   (501) staff       (20)       15 2022-08-30 18:49:03.000000 whistleaio-0.1.0/whistleaio.egg-info/requires.txt
--rw-r--r--   0 robertdrinovac   (501) staff       (20)       11 2022-08-30 18:49:03.000000 whistleaio-0.1.0/whistleaio.egg-info/top_level.txt
+drwxr-xr-x   0 robertdrinovac   (501) staff       (20)        0 2023-06-27 23:37:50.621311 whistleaio-0.1.1/
+-rw-rw-r--   0 robertdrinovac   (501) staff       (20)     1067 2023-06-27 23:35:50.000000 whistleaio-0.1.1/LICENSE
+-rw-r--r--   0 robertdrinovac   (501) staff       (20)     1282 2023-06-27 23:37:50.620865 whistleaio-0.1.1/PKG-INFO
+-rw-rw-r--   0 robertdrinovac   (501) staff       (20)      460 2023-06-27 23:35:50.000000 whistleaio-0.1.1/README.md
+-rw-r--r--   0 robertdrinovac   (501) staff       (20)       38 2023-06-27 23:37:50.621521 whistleaio-0.1.1/setup.cfg
+-rw-rw-r--   0 robertdrinovac   (501) staff       (20)     1007 2023-06-27 23:35:50.000000 whistleaio-0.1.1/setup.py
+drwxr-xr-x   0 robertdrinovac   (501) staff       (20)        0 2023-06-27 23:37:50.618145 whistleaio-0.1.1/whistleaio/
+-rw-rw-r--   0 robertdrinovac   (501) staff       (20)      312 2023-06-27 23:35:50.000000 whistleaio-0.1.1/whistleaio/__init__.py
+-rw-rw-r--   0 robertdrinovac   (501) staff       (20)     7255 2023-06-27 23:35:50.000000 whistleaio-0.1.1/whistleaio/client.py
+-rw-rw-r--   0 robertdrinovac   (501) staff       (20)      696 2023-06-27 23:35:50.000000 whistleaio-0.1.1/whistleaio/const.py
+-rw-rw-r--   0 robertdrinovac   (501) staff       (20)      448 2023-06-27 23:35:50.000000 whistleaio-0.1.1/whistleaio/exceptions.py
+-rw-rw-r--   0 robertdrinovac   (501) staff       (20)      497 2023-06-27 23:35:50.000000 whistleaio-0.1.1/whistleaio/model.py
+drwxr-xr-x   0 robertdrinovac   (501) staff       (20)        0 2023-06-27 23:37:50.620143 whistleaio-0.1.1/whistleaio.egg-info/
+-rw-r--r--   0 robertdrinovac   (501) staff       (20)     1282 2023-06-27 23:37:50.000000 whistleaio-0.1.1/whistleaio.egg-info/PKG-INFO
+-rw-r--r--   0 robertdrinovac   (501) staff       (20)      304 2023-06-27 23:37:50.000000 whistleaio-0.1.1/whistleaio.egg-info/SOURCES.txt
+-rw-r--r--   0 robertdrinovac   (501) staff       (20)        1 2023-06-27 23:37:50.000000 whistleaio-0.1.1/whistleaio.egg-info/dependency_links.txt
+-rw-r--r--   0 robertdrinovac   (501) staff       (20)       30 2023-06-27 23:37:50.000000 whistleaio-0.1.1/whistleaio.egg-info/requires.txt
+-rw-r--r--   0 robertdrinovac   (501) staff       (20)       11 2023-06-27 23:37:50.000000 whistleaio-0.1.1/whistleaio.egg-info/top_level.txt
```

### Comparing `whistleaio-0.1.0/LICENSE` & `whistleaio-0.1.1/LICENSE`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 MIT License
 
-Copyright (c) 2022 RobertD502
+Copyright (c) 2023 RobertD502
 
 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:
```

### Comparing `whistleaio-0.1.0/PKG-INFO` & `whistleaio-0.1.1/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: whistleaio
-Version: 0.1.0
+Version: 0.1.1
 Summary: Asynchronous Python library for Whistle's API
 Home-page: https://github.com/RobertD502/whistleaio
 Author: Robert Drinovac
 Author-email: unlisted@gmail.com
 License: UNKNOWN
 Project-URL: Bug Reports, https://github.com/RobertD502/whistleaio/issues
 Project-URL: Source, https://github.com/RobertD502/whistleaio/
```

### Comparing `whistleaio-0.1.0/setup.py` & `whistleaio-0.1.1/setup.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,26 +1,27 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="whistleaio",
-    version="0.1.0",
+    version="0.1.1",
     author="Robert Drinovac",
     author_email="unlisted@gmail.com",
     description="Asynchronous Python library for Whistle's API",
     long_description=long_description,
     long_description_content_type="text/markdown",
     url='https://github.com/RobertD502/whistleaio',
     keywords='whistle, whistle fit, whistle api, whistle client, whistle gps, whistle pet',
     packages=setuptools.find_packages(),
     python_requires= ">=3.7",
     install_requires=[
         "aiohttp>=3.8.1",
+        "strenum>=0.4.8",
     ],
     classifiers=(
         "Programming Language :: Python :: 3",
         "License :: OSI Approved :: MIT License",
         "Operating System :: OS Independent"
     ),
     project_urls={  # Optional
```

### Comparing `whistleaio-0.1.0/whistleaio/client.py` & `whistleaio-0.1.1/whistleaio/client.py`

 * *Files 6% similar despite different names*

```diff
@@ -2,19 +2,19 @@
 from __future__ import annotations
 
 from typing import Any
 
 import asyncio
 from aiohttp import ClientResponse, ClientSession
 
-from .const import Endpoint, Header, TIMEOUT
+from whistleaio.const import Endpoint, Header, TIMEOUT
 
-from .exceptions import WhistleAuthError
+from whistleaio.exceptions import WhistleAuthError, WhistleError
 
-from .model import WhistleData, Pet
+from whistleaio.model import WhistleData, Pet
 
 
 class WhistleClient:
     """ Whistle Client. """
 
     def __init__(
             self, email: str, password: str,
@@ -62,18 +62,18 @@
                     id=str(pet['id']),
                     data=pet,
                     device=all_endpoints[0],
                     dailies=all_endpoints[1],
                     events=daily_item,
                     places=all_endpoints[2],
                     stats=all_endpoints[3],
+                    health=all_endpoints[4]
                 )
         return WhistleData(pets=pets_data)
 
-
     async def get_pets(self) -> dict[str, Any]:
         """ Get all pets. """
 
         if self.token is None:
             await self.get_token()
         header = await self.create_header()
         response = await self._get(endpoint=Endpoint.PETS, header=header)
@@ -126,25 +126,35 @@
 
         if self.token is None:
             await self.get_token()
         header = await self.create_header()
         response = await self._get(endpoint=Endpoint.PLACES, header=header)
         return response
 
+    async def get_health_trends(self, pet_id: int) -> dict[str, Any]:
+        """Get all the health trends associated with a pet."""
+
+        if self.token is None:
+            await self.get_token()
+        header = await self.create_header()
+        endpoint = f'{Endpoint.PETS}/{pet_id}{Endpoint.HEALTH}'
+        response = await self._get(endpoint=endpoint, header=header)
+        return response
 
-    async def fetch_all_endpoints(self, pet: dict[str, Any]) -> tuple:
+    async def fetch_all_endpoints(self, pet: dict[str, Any]) -> list:
         """Parallel request are made to all endpoints needed to
         get data for device, dailies, places, and stats of the Pet Object.
         """
 
         results = await asyncio.gather(*[
             self.get_device_data(pet['device']['serial_number']),
             self.get_dailies(pet['id']),
             self.get_places(),
-            self.get_stats(pet['id'])
+            self.get_stats(pet['id']),
+            self.get_health_trends(pet['id'])
             ],
         )
         return results
 
     async def create_header(self) -> dict[str, str]:
         """ Creates header that is used in all calls except token retrieval. """
 
@@ -156,34 +166,36 @@
             "Connection": 'keep-alive',
             "Content-Type": Header.CONTENT_TYPE,
             "User-Agent": Header.AGENT,
             "Authorization": f'Bearer {self.token}'
         }
         return header
 
-
     async def _post(self, endpoint: str, header: dict[str, Any], data: dict[str, Any]) -> dict[str, Any]:
         """ Make POST call to Whistle servers. """
 
         async with self._session.post(
-                url=f'{Endpoint.BASE_URL}{endpoint}', headers=header,
+            url=f'{Endpoint.BASE_URL}{endpoint}', headers=header,
                 data=data, timeout=self.timeout) as resp:
-                return await self._response(resp)
+            return await self._response(resp)
 
     async def _get(self, endpoint: str, header: dict[str, Any]) -> dict[str, Any]:
         """ Make GET call to Whistle servers. """
 
         async with self._session.get(
-                url=f'{Endpoint.BASE_URL}{endpoint}', headers=header,
+            url=f'{Endpoint.BASE_URL}{endpoint}', headers=header,
                 timeout=self.timeout) as resp:
-                return await self._response(resp)
+            return await self._response(resp)
 
     @staticmethod
     async def _response(resp: ClientResponse) -> dict[str, Any] | None:
         """ Check response for any errors & return original response if none """
 
-        response: dict[str, Any] = await resp.json()
+        try:
+            response: dict[str, Any] = await resp.json()
+        except Exception as ex:
+            raise WhistleError(ex)
         if resp.status == 422:
             if response['errors'][0]['message'] == 'Invalid email address or password':
                 raise WhistleAuthError('Invalid email address or password')
         else:
             return response
```

### Comparing `whistleaio-0.1.0/whistleaio/const.py` & `whistleaio-0.1.1/whistleaio/const.py`

 * *Files 16% similar despite different names*

```diff
@@ -7,14 +7,15 @@
 
 class Endpoint(StrEnum):
     """ Endpoint type for Whistle API. """
 
     BASE_URL = 'https://app.whistle.com/api'
     DAILIES = '/dailies'
     DEVICES = '/devices'
+    HEALTH = '/health/trends'
     LOGIN = '/login'
     PETS = '/pets'
     PLACES= '/places'
     STATS = '/stats'
 
 
 """ Header """
```

### Comparing `whistleaio-0.1.0/whistleaio.egg-info/PKG-INFO` & `whistleaio-0.1.1/whistleaio.egg-info/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: whistleaio
-Version: 0.1.0
+Version: 0.1.1
 Summary: Asynchronous Python library for Whistle's API
 Home-page: https://github.com/RobertD502/whistleaio
 Author: Robert Drinovac
 Author-email: unlisted@gmail.com
 License: UNKNOWN
 Project-URL: Bug Reports, https://github.com/RobertD502/whistleaio/issues
 Project-URL: Source, https://github.com/RobertD502/whistleaio/
```


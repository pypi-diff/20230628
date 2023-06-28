# Comparing `tmp/nood-0.1.8.tar.gz` & `tmp/nood-0.1.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nood-0.1.8.tar", max compression
+gzip compressed data, was "nood-0.1.9.tar", max compression
```

## Comparing `nood-0.1.8.tar` & `nood-0.1.9.tar`

### file list

```diff
@@ -1,19 +1,19 @@
--rw-r--r--   0        0        0     3127 2023-01-18 22:39:12.135259 nood-0.1.8/README.md
--rw-r--r--   0        0        0       39 2023-01-18 22:39:12.135259 nood-0.1.8/nood/__init__.py
--rw-r--r--   0        0        0       84 2023-01-18 22:39:12.135259 nood-0.1.8/nood/api/__init__.py
--rw-r--r--   0        0        0     1628 2023-01-18 22:39:12.135259 nood-0.1.8/nood/api/mapper.py
--rw-r--r--   0        0        0      317 2023-01-18 22:39:12.135259 nood-0.1.8/nood/api/responses.py
--rw-r--r--   0        0        0      163 2023-01-18 22:39:12.135259 nood-0.1.8/nood/api/types.py
--rw-r--r--   0        0        0       41 2023-01-18 22:39:12.135259 nood-0.1.8/nood/config.py
--rw-r--r--   0        0        0       85 2023-01-18 22:39:12.135259 nood-0.1.8/nood/monitor/__init__.py
--rw-r--r--   0        0        0      310 2023-01-18 22:39:12.135259 nood-0.1.8/nood/monitor/exceptions.py
--rw-r--r--   0        0        0     4245 2023-01-18 22:39:12.135259 nood-0.1.8/nood/monitor/monitor.py
--rw-r--r--   0        0        0      463 2023-01-18 22:39:12.135259 nood-0.1.8/nood/monitor/parser.py
--rw-r--r--   0        0        0     2182 2023-01-18 22:39:12.135259 nood-0.1.8/nood/monitor/scraper.py
--rw-r--r--   0        0        0       84 2023-01-18 22:39:12.135259 nood-0.1.8/nood/objects/__init__.py
--rw-r--r--   0        0        0       79 2023-01-18 22:39:12.135259 nood-0.1.8/nood/objects/config.py
--rw-r--r--   0        0        0      630 2023-01-18 22:39:12.135259 nood-0.1.8/nood/objects/product.py
--rw-r--r--   0        0        0     1786 2023-01-18 22:39:12.135259 nood-0.1.8/nood/objects/proxy.py
--rw-r--r--   0        0        0      533 2023-01-18 22:39:12.135259 nood-0.1.8/pyproject.toml
--rw-r--r--   0        0        0     4015 1970-01-01 00:00:00.000000 nood-0.1.8/setup.py
--rw-r--r--   0        0        0     3710 1970-01-01 00:00:00.000000 nood-0.1.8/PKG-INFO
+-rw-r--r--   0        0        0     3127 2023-01-18 22:53:36.825829 nood-0.1.9/README.md
+-rw-r--r--   0        0        0       39 2023-01-18 22:53:36.825829 nood-0.1.9/nood/__init__.py
+-rw-r--r--   0        0        0       84 2023-01-18 22:53:36.825829 nood-0.1.9/nood/api/__init__.py
+-rw-r--r--   0        0        0     1628 2023-01-18 22:53:36.825829 nood-0.1.9/nood/api/mapper.py
+-rw-r--r--   0        0        0      317 2023-01-18 22:53:36.825829 nood-0.1.9/nood/api/responses.py
+-rw-r--r--   0        0        0      163 2023-01-18 22:53:36.825829 nood-0.1.9/nood/api/types.py
+-rw-r--r--   0        0        0       41 2023-01-18 22:53:36.825829 nood-0.1.9/nood/config.py
+-rw-r--r--   0        0        0       85 2023-01-18 22:53:36.825829 nood-0.1.9/nood/monitor/__init__.py
+-rw-r--r--   0        0        0      310 2023-01-18 22:53:36.825829 nood-0.1.9/nood/monitor/exceptions.py
+-rw-r--r--   0        0        0     4245 2023-01-18 22:53:36.825829 nood-0.1.9/nood/monitor/monitor.py
+-rw-r--r--   0        0        0      463 2023-01-18 22:53:36.825829 nood-0.1.9/nood/monitor/parser.py
+-rw-r--r--   0        0        0     2182 2023-01-18 22:53:36.825829 nood-0.1.9/nood/monitor/scraper.py
+-rw-r--r--   0        0        0       84 2023-01-18 22:53:36.825829 nood-0.1.9/nood/objects/__init__.py
+-rw-r--r--   0        0        0       79 2023-01-18 22:53:36.825829 nood-0.1.9/nood/objects/config.py
+-rw-r--r--   0        0        0      640 2023-01-18 22:53:36.825829 nood-0.1.9/nood/objects/product.py
+-rw-r--r--   0        0        0     1786 2023-01-18 22:53:36.825829 nood-0.1.9/nood/objects/proxy.py
+-rw-r--r--   0        0        0      533 2023-01-18 22:53:36.825829 nood-0.1.9/pyproject.toml
+-rw-r--r--   0        0        0     4015 1970-01-01 00:00:00.000000 nood-0.1.9/setup.py
+-rw-r--r--   0        0        0     3710 1970-01-01 00:00:00.000000 nood-0.1.9/PKG-INFO
```

### Comparing `nood-0.1.8/README.md` & `nood-0.1.9/README.md`

 * *Files identical despite different names*

### Comparing `nood-0.1.8/nood/api/mapper.py` & `nood-0.1.9/nood/api/mapper.py`

 * *Files identical despite different names*

### Comparing `nood-0.1.8/nood/monitor/monitor.py` & `nood-0.1.9/nood/monitor/monitor.py`

 * *Files identical despite different names*

### Comparing `nood-0.1.8/nood/monitor/scraper.py` & `nood-0.1.9/nood/monitor/scraper.py`

 * *Files identical despite different names*

### Comparing `nood-0.1.8/nood/objects/product.py` & `nood-0.1.9/nood/objects/product.py`

 * *Files 16% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 
 from typing import List, Optional
 
 from pydantic import BaseModel
 
 
 class Variant(BaseModel):
-    id: str
+    id: Optional[str]
     value: str
     stock: Optional[int]
     atc_url: Optional[str]
     direct_url: Optional[str]
 
     class Config:
         allow_population_by_field_name = True
```

### Comparing `nood-0.1.8/nood/objects/proxy.py` & `nood-0.1.9/nood/objects/proxy.py`

 * *Files identical despite different names*

### Comparing `nood-0.1.8/pyproject.toml` & `nood-0.1.9/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "nood"
-version = "0.1.8"
+version = "0.1.9"
 description = "All tools you need to interact with nood."
 authors = ["timreibe <github@timreibe.de>"]
 readme = "README.md"
 
 [tool.poetry.dependencies]
 python = "^3.9"
 loguru = ">=0.6.0,<0.7.0"
```

### Comparing `nood-0.1.8/setup.py` & `nood-0.1.9/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -11,15 +11,15 @@
 ['loguru>=0.6.0,<0.7.0',
  'pydantic>=1.10.4,<1.11.0',
  'pytest>=7.2.0,<7.3.0',
  'requests>=2.28.1,<2.29.0']
 
 setup_kwargs = {
     'name': 'nood',
-    'version': '0.1.8',
+    'version': '0.1.9',
     'description': 'All tools you need to interact with nood.',
     'long_description': '# nood - Notifications On Demand\n\nA wrapping library for web crawlers automation.\n\nThe main objective of this service is to easily enable developers to build and\nrun monitors. Basically, developers only have to write a download function and\na corresponding parse function to run a monitor.\n\n## Prerequisites\n\nTo use `nood`, you need an API key.\n[Please join our Discord](https://discord.gg/yMYnGcKKnR) and contact\n`turner#0069`.\n\nWe also encourage you to use `pm2` ([click here for more information](https://www.npmjs.com/package/pm2)) to \nrun your monitors.\n\n## Installation\n\nInstall `nood` with pip.\n\n```\npip install nood\n```\n\n## Configuration\n\nThe configuration for each monitor is stored in a json file. The default\ndirectory for the config file is the same as the monitor\'s script directory.\nThe default name for the config file is `config.json`, but can be configured\nindividually.\n\n```json\n{\n  "siteId": 1234,\n  "apiKey": "abcdefg1234567890",\n  "proxies": [\n    "ip:port:user:pass"\n  ],\n  "urls": [\n    "https://example.com/1",\n    "https://example.com/2"\n  ],\n  "pids": [\n    "example-pid-1",\n    "example-pid-2"\n  ]\n}\n```\n\n## Example Scraper with Config\n\nFor each monitor, the `Scraper` and `Parser` class must be defined. The\nmonitoring logic is managed in the `Monitor` class which is defined by `nood`.\n\n```python\nimport requests\n\nfrom nood import monitor, objects\n\n\nclass MMSScraper(monitor.Scraper):\n    def __init__(self, url: str, **kwargs):\n        super(MMSScraper, self).__init__(url=url, **kwargs)\n\n    def download(self) -> requests.Response:\n        headers = {\n            \'user-agent\': \'Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) \'\n                          \'AppleWebKit/537.36 (KHTML, like Gecko) \'\n                          \'Chrome/108.0.0.0 Safari/537.36\'\n        }\n        response = self._s.get(\n            url=self.url,\n            proxies=self.get_static_proxy(),\n            headers=headers\n        )\n\n        return response\n\n\nclass MMSParser(monitor.Parser):\n    def __init__(self):\n        super().__init__()\n\n    def parse(self, *, response: requests.Response):\n        name = response.text.split(\'<title data-rh="true">\')[1].split("|")[0]\n        turl = response.text.split(\'"og:image" content="\')[1].split(\'"\')[0]\n        variants = []\n        if "</div>In den Warenkorb</button>" in response.text:\n            variants.append(objects.Variant(value="OS"))\n\n        return objects.Product(\n            url=response.url,\n            name=name,\n            variants=variants,\n            thumbnail_url=turl\n        )\n\n\nif __name__ == "__main__":\n    monitor.Monitor.launch_tasks(scraper=MMSScraper, parser=MMSParser)\n```\n\nThe configuration file for Mediamarkt would look like this:\n\n```json\n{\n  "siteId": 1234,\n  "apiKey": "abcdefg1234567890",\n  "proxies": [],\n  "urls": [\n    "https://www.mediamarkt.de/de/product/_apple-airpods-mit-ladecase-2-generation-2539111.html"\n  ],\n  "pids": []\n}\n```\n\nTo run and keep track of the monitoring script with `pm2`, you can use the \nfollowing commands:\n\n```shell\npm2 start mms.py\npm2 monit\n```\n\nTo stop the script, use\n\n```shell\npm2 stop mm2.py\n```',
     'author': 'timreibe',
     'author_email': 'github@timreibe.de',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
```

### Comparing `nood-0.1.8/PKG-INFO` & `nood-0.1.9/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: nood
-Version: 0.1.8
+Version: 0.1.9
 Summary: All tools you need to interact with nood.
 Author: timreibe
 Author-email: github@timreibe.de
 Requires-Python: >=3.9,<4.0
 Classifier: Programming Language :: Python :: 3
 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10
```


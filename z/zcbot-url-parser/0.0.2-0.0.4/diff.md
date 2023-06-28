# Comparing `tmp/zcbot-url-parser-0.0.2.tar.gz` & `tmp/zcbot-url-parser-0.0.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\zcbot-url-parser-0.0.2.tar", last modified: Wed Jun 28 05:17:21 2023, max compression
+gzip compressed data, was "dist\zcbot-url-parser-0.0.4.tar", last modified: Wed Jun 28 06:27:52 2023, max compression
```

## Comparing `zcbot-url-parser-0.0.2.tar` & `zcbot-url-parser-0.0.4.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 05:17:21.667008 zcbot-url-parser-0.0.2/
--rw-rw-rw-   0        0        0        0 2023-03-14 04:29:15.000000 zcbot-url-parser-0.0.2/MANIFEST.in
--rw-rw-rw-   0        0        0      379 2023-06-28 05:17:21.667008 zcbot-url-parser-0.0.2/PKG-INFO
--rw-rw-rw-   0        0        0      135 2023-05-30 07:06:49.000000 zcbot-url-parser-0.0.2/README.rst
--rw-rw-rw-   0        0        0       42 2023-06-28 05:17:21.668007 zcbot-url-parser-0.0.2/setup.cfg
--rw-rw-rw-   0        0        0      592 2023-06-28 05:16:49.000000 zcbot-url-parser-0.0.2/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 05:17:21.660008 zcbot-url-parser-0.0.2/zcbot_url_parser/
--rw-rw-rw-   0        0        0       40 2023-03-14 03:58:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser/__init__.py
--rw-rw-rw-   0        0        0     3647 2023-06-28 05:16:36.000000 zcbot-url-parser-0.0.2/zcbot_url_parser/parser.py
--rw-rw-rw-   0        0        0     2090 2023-05-30 07:12:16.000000 zcbot-url-parser-0.0.2/zcbot_url_parser/rule.py
--rw-rw-rw-   0        0        0      272 2023-05-30 07:12:11.000000 zcbot-url-parser-0.0.2/zcbot_url_parser/utils.py
-drwxrwxrwx   0        0        0        0 2023-06-28 05:17:21.665010 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/
--rw-rw-rw-   0        0        0      379 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      337 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        9 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/requires.txt
--rw-rw-rw-   0        0        0       17 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 06:27:52.487358 zcbot-url-parser-0.0.4/
+-rw-rw-rw-   0        0        0        0 2023-03-14 04:29:15.000000 zcbot-url-parser-0.0.4/MANIFEST.in
+-rw-rw-rw-   0        0        0      379 2023-06-28 06:27:52.486358 zcbot-url-parser-0.0.4/PKG-INFO
+-rw-rw-rw-   0        0        0      135 2023-05-30 07:06:49.000000 zcbot-url-parser-0.0.4/README.rst
+-rw-rw-rw-   0        0        0       42 2023-06-28 06:27:52.487358 zcbot-url-parser-0.0.4/setup.cfg
+-rw-rw-rw-   0        0        0      603 2023-06-28 06:08:53.000000 zcbot-url-parser-0.0.4/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:27:52.478359 zcbot-url-parser-0.0.4/zcbot_url_parser/
+-rw-rw-rw-   0        0        0       40 2023-03-14 03:58:21.000000 zcbot-url-parser-0.0.4/zcbot_url_parser/__init__.py
+-rw-rw-rw-   0        0        0     3647 2023-06-28 05:34:27.000000 zcbot-url-parser-0.0.4/zcbot_url_parser/parser.py
+-rw-rw-rw-   0        0        0     3013 2023-06-28 06:05:15.000000 zcbot-url-parser-0.0.4/zcbot_url_parser/rule.py
+-rw-rw-rw-   0        0        0      272 2023-05-30 07:12:11.000000 zcbot-url-parser-0.0.4/zcbot_url_parser/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:27:52.485358 zcbot-url-parser-0.0.4/zcbot_url_parser.egg-info/
+-rw-rw-rw-   0        0        0      379 2023-06-28 06:27:52.000000 zcbot-url-parser-0.0.4/zcbot_url_parser.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      337 2023-06-28 06:27:52.000000 zcbot-url-parser-0.0.4/zcbot_url_parser.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 06:27:52.000000 zcbot-url-parser-0.0.4/zcbot_url_parser.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       17 2023-06-28 06:27:52.000000 zcbot-url-parser-0.0.4/zcbot_url_parser.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       17 2023-06-28 06:27:52.000000 zcbot-url-parser-0.0.4/zcbot_url_parser.egg-info/top_level.txt
```

### Comparing `zcbot-url-parser-0.0.2/setup.py` & `zcbot-url-parser-0.0.4/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,20 +1,20 @@
 from distutils.core import setup
 from setuptools import find_packages
 
 with open('README.rst', 'r') as f:
     long_description = f.read()
 
 setup(name='zcbot-url-parser',
-      version='0.0.2',
+      version='0.0.4',
       description='zcbot url parser for zsodata',
       long_description=long_description,
       author='zsodata',
       author_email='team@zso.io',
       url='http://www.zsodata.com',
-      install_requires=['requests'],
+      install_requires=['requests', 'pymongo'],
       python_requires='>=3.7',
       license='BSD License',
       packages=find_packages(),
       platforms=['all'],
       include_package_data=True
       )
```

### Comparing `zcbot-url-parser-0.0.2/zcbot_url_parser/parser.py` & `zcbot-url-parser-0.0.4/zcbot_url_parser/parser.py`

 * *Files 2% similar despite different names*

```diff
@@ -19,24 +19,24 @@
     plat_code: str = None
     # 网站名称  如：京东
     plat_name: str = None
     # 链接商品编码（多编码链接，编码之间逗号分隔）  如：5129155、576748721316,3985068128611
     ec_sku_id: str = None
 
 
-def parse_url(url) -> Union[UrlModel, None]:
+def parse_url(url) -> Union[UrlModel]:
     """
     解析url链接
     """
     plat_code, plat_name, ec_sku_id = _match_url(url)
     if plat_code and ec_sku_id:
         link_sn = _build_link_sn(plat_code, ec_sku_id)
         return UrlModel(link_sn=link_sn, plat_code=plat_code, plat_name=plat_name, ec_sku_id=ec_sku_id)
 
-    return None
+    return UrlModel()
 
 
 def _build_link_sn(plat_code, ec_sku_id):
     """
     构建link_sn编码规则
     """
     if plat_code and ec_sku_id:
```

### Comparing `zcbot-url-parser-0.0.2/zcbot_url_parser/rule.py` & `zcbot-url-parser-0.0.4/zcbot_url_parser/rule.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,10 +1,12 @@
 import logging
 import re
 import requests
+from pymongo import MongoClient
+
 from .utils import singleton
 
 LOGGER = logging.getLogger(__name__)
 
 
 @singleton
 class RuleHolder(object):
@@ -47,24 +49,48 @@
                 'sku_param': row.get('params', []),
                 'patterns': [
                     re.compile(x) for x in row.get('regex', [])
                 ],
             }
         LOGGER.info(f'更新链接分拣规则: {len(self.rule_map)}条')
 
+    # def _fetch_platforms(self):
+    #     platforms = []
+    #     # TODO 待优化
+    #     rs = requests.get('http://www.zcbot.cn/zcbot-api/api/meta/platforms', timeout=15)
+    #     if rs:
+    #         platforms = rs.json().get('data', []) or []
+    #
+    #     return platforms
+    #
+    # def _fetch_url_rules(self):
+    #     rules = []
+    #     # TODO 待优化
+    #     rs = requests.get('http://www.zcbot.cn/zcbot-api/api/meta/url-rules', timeout=15)
+    #     if rs:
+    #         rules = rs.json().get('data', []) or []
+    #
+    #     return rules
+
     def _fetch_platforms(self):
-        platforms = []
-        # TODO 待优化
-        rs = requests.get('http://www.zcbot.cn/zcbot-api/api/meta/platforms', timeout=15)
-        if rs:
-            platforms = rs.json().get('data', []) or []
+        try:
+            client = MongoClient('mongodb://public_read:public_read_zsodata@zcbot-outer.mongodb.rds.aliyuncs.com:3717')
+            rs = client.get_database('zcbot_pool').get_collection('zcbot_platforms').find()
+            rows = list(rs)
+            client.close()
+            return rows
+        except Exception as e:
+            print(e)
 
-        return platforms
+        return []
 
     def _fetch_url_rules(self):
-        rules = []
-        # TODO 待优化
-        rs = requests.get('http://www.zcbot.cn/zcbot-api/api/meta/url-rules', timeout=15)
-        if rs:
-            rules = rs.json().get('data', []) or []
+        try:
+            client = MongoClient('mongodb://public_read:public_read_zsodata@zcbot-outer.mongodb.rds.aliyuncs.com:3717')
+            rs = client.get_database('zcbot_pool').get_collection('zcbot_url_parse_rule').find()
+            rows = list(rs)
+            client.close()
+            return rows
+        except Exception as e:
+            print(e)
 
-        return rules
+        return []
```


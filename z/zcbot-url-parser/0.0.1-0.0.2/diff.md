# Comparing `tmp/zcbot-url-parser-0.0.1.tar.gz` & `tmp/zcbot-url-parser-0.0.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\zcbot-url-parser-0.0.1.tar", last modified: Tue May 30 07:37:54 2023, max compression
+gzip compressed data, was "dist\zcbot-url-parser-0.0.2.tar", last modified: Wed Jun 28 05:17:21 2023, max compression
```

## Comparing `zcbot-url-parser-0.0.1.tar` & `zcbot-url-parser-0.0.2.tar`

### file list

```diff
@@ -1,17 +1,17 @@
-drwxrwxrwx   0        0        0        0 2023-05-30 07:37:54.917586 zcbot-url-parser-0.0.1/
--rw-rw-rw-   0        0        0        0 2023-03-14 04:29:15.000000 zcbot-url-parser-0.0.1/MANIFEST.in
--rw-rw-rw-   0        0        0      379 2023-05-30 07:37:54.916586 zcbot-url-parser-0.0.1/PKG-INFO
--rw-rw-rw-   0        0        0      135 2023-05-30 07:06:49.000000 zcbot-url-parser-0.0.1/README.rst
--rw-rw-rw-   0        0        0       42 2023-05-30 07:37:54.918586 zcbot-url-parser-0.0.1/setup.cfg
--rw-rw-rw-   0        0        0      592 2023-05-30 07:32:26.000000 zcbot-url-parser-0.0.1/setup.py
-drwxrwxrwx   0        0        0        0 2023-05-30 07:37:54.909586 zcbot-url-parser-0.0.1/zcbot_url_parser/
--rw-rw-rw-   0        0        0       40 2023-03-14 03:58:21.000000 zcbot-url-parser-0.0.1/zcbot_url_parser/__init__.py
--rw-rw-rw-   0        0        0     3546 2023-05-30 07:36:23.000000 zcbot-url-parser-0.0.1/zcbot_url_parser/parser.py
--rw-rw-rw-   0        0        0     2090 2023-05-30 07:12:16.000000 zcbot-url-parser-0.0.1/zcbot_url_parser/rule.py
--rw-rw-rw-   0        0        0      272 2023-05-30 07:12:11.000000 zcbot-url-parser-0.0.1/zcbot_url_parser/utils.py
-drwxrwxrwx   0        0        0        0 2023-05-30 07:37:54.915586 zcbot-url-parser-0.0.1/zcbot_url_parser.egg-info/
--rw-rw-rw-   0        0        0      379 2023-05-30 07:37:54.000000 zcbot-url-parser-0.0.1/zcbot_url_parser.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      337 2023-05-30 07:37:54.000000 zcbot-url-parser-0.0.1/zcbot_url_parser.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-05-30 07:37:54.000000 zcbot-url-parser-0.0.1/zcbot_url_parser.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        9 2023-05-30 07:37:54.000000 zcbot-url-parser-0.0.1/zcbot_url_parser.egg-info/requires.txt
--rw-rw-rw-   0        0        0       17 2023-05-30 07:37:54.000000 zcbot-url-parser-0.0.1/zcbot_url_parser.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 05:17:21.667008 zcbot-url-parser-0.0.2/
+-rw-rw-rw-   0        0        0        0 2023-03-14 04:29:15.000000 zcbot-url-parser-0.0.2/MANIFEST.in
+-rw-rw-rw-   0        0        0      379 2023-06-28 05:17:21.667008 zcbot-url-parser-0.0.2/PKG-INFO
+-rw-rw-rw-   0        0        0      135 2023-05-30 07:06:49.000000 zcbot-url-parser-0.0.2/README.rst
+-rw-rw-rw-   0        0        0       42 2023-06-28 05:17:21.668007 zcbot-url-parser-0.0.2/setup.cfg
+-rw-rw-rw-   0        0        0      592 2023-06-28 05:16:49.000000 zcbot-url-parser-0.0.2/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 05:17:21.660008 zcbot-url-parser-0.0.2/zcbot_url_parser/
+-rw-rw-rw-   0        0        0       40 2023-03-14 03:58:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser/__init__.py
+-rw-rw-rw-   0        0        0     3647 2023-06-28 05:16:36.000000 zcbot-url-parser-0.0.2/zcbot_url_parser/parser.py
+-rw-rw-rw-   0        0        0     2090 2023-05-30 07:12:16.000000 zcbot-url-parser-0.0.2/zcbot_url_parser/rule.py
+-rw-rw-rw-   0        0        0      272 2023-05-30 07:12:11.000000 zcbot-url-parser-0.0.2/zcbot_url_parser/utils.py
+drwxrwxrwx   0        0        0        0 2023-06-28 05:17:21.665010 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/
+-rw-rw-rw-   0        0        0      379 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      337 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        9 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/requires.txt
+-rw-rw-rw-   0        0        0       17 2023-06-28 05:17:21.000000 zcbot-url-parser-0.0.2/zcbot_url_parser.egg-info/top_level.txt
```

### Comparing `zcbot-url-parser-0.0.1/setup.py` & `zcbot-url-parser-0.0.2/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 from distutils.core import setup
 from setuptools import find_packages
 
 with open('README.rst', 'r') as f:
     long_description = f.read()
 
 setup(name='zcbot-url-parser',
-      version='0.0.1',
+      version='0.0.2',
       description='zcbot url parser for zsodata',
       long_description=long_description,
       author='zsodata',
       author_email='team@zso.io',
       url='http://www.zsodata.com',
       install_requires=['requests'],
       python_requires='>=3.7',
```

### Comparing `zcbot-url-parser-0.0.1/zcbot_url_parser/parser.py` & `zcbot-url-parser-0.0.2/zcbot_url_parser/parser.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,9 +1,11 @@
 import logging
 import urllib.parse as parser
+from typing import Union
+
 from pydantic import BaseModel
 from .rule import RuleHolder
 
 LOGGER = logging.getLogger(__name__)
 rule_holder = RuleHolder()
 
 
@@ -13,19 +15,19 @@
     """
     # 链接序列号（全局唯一）  如：jd:5129155、tmall:576748721316,3985068128611
     link_sn: str = None
     # 网站编码  如：jd
     plat_code: str = None
     # 网站名称  如：京东
     plat_name: str = None
-    # 链接商品编码  如：5129155、576748721316,3985068128611
+    # 链接商品编码（多编码链接，编码之间逗号分隔）  如：5129155、576748721316,3985068128611
     ec_sku_id: str = None
 
 
-def parse_url(url):
+def parse_url(url) -> Union[UrlModel, None]:
     """
     解析url链接
     """
     plat_code, plat_name, ec_sku_id = _match_url(url)
     if plat_code and ec_sku_id:
         link_sn = _build_link_sn(plat_code, ec_sku_id)
         return UrlModel(link_sn=link_sn, plat_code=plat_code, plat_name=plat_name, ec_sku_id=ec_sku_id)
```

### Comparing `zcbot-url-parser-0.0.1/zcbot_url_parser/rule.py` & `zcbot-url-parser-0.0.2/zcbot_url_parser/rule.py`

 * *Files identical despite different names*


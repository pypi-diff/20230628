# Comparing `tmp/lazynovel-0.1.4.tar.gz` & `tmp/lazynovel-0.1.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "lazynovel-0.1.4.tar", last modified: Tue Jun 27 08:26:26 2023, max compression
+gzip compressed data, was "lazynovel-0.1.5.tar", last modified: Wed Jun 28 07:20:07 2023, max compression
```

## Comparing `lazynovel-0.1.4.tar` & `lazynovel-0.1.5.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 zeroseeker   (501) staff       (20)        0 2023-06-27 08:26:26.688337 lazynovel-0.1.4/
--rw-r--r--   0 zeroseeker   (501) staff       (20)    35181 2023-02-28 06:27:15.000000 lazynovel-0.1.4/LICENSE
--rw-r--r--   0 zeroseeker   (501) staff       (20)     1305 2023-06-27 08:26:26.688196 lazynovel-0.1.4/PKG-INFO
--rw-r--r--   0 zeroseeker   (501) staff       (20)      954 2023-02-28 06:27:15.000000 lazynovel-0.1.4/README.md
-drwxr-xr-x   0 zeroseeker   (501) staff       (20)        0 2023-06-27 08:26:26.687309 lazynovel-0.1.4/lazynovel/
--rw-r--r--   0 zeroseeker   (501) staff       (20)      415 2023-05-25 10:17:10.000000 lazynovel-0.1.4/lazynovel/__init__.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)     6989 2023-05-25 08:04:09.000000 lazynovel-0.1.4/lazynovel/crawler_changdu.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)    10729 2023-02-28 06:27:15.000000 lazynovel-0.1.4/lazynovel/crawler_mbookcn.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)     5902 2023-06-27 08:25:54.000000 lazynovel-0.1.4/lazynovel/crawler_reading163.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)    10568 2023-02-28 06:27:15.000000 lazynovel-0.1.4/lazynovel/open_changdu.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)     9853 2023-02-28 06:27:15.000000 lazynovel-0.1.4/lazynovel/open_dianzhong.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)     9680 2023-02-28 06:27:15.000000 lazynovel-0.1.4/lazynovel/open_mbookcn.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)    21587 2023-05-29 10:32:37.000000 lazynovel-0.1.4/lazynovel/open_reading163.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)      830 2023-02-28 06:27:15.000000 lazynovel-0.1.4/lazynovel/open_yangguang.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)     2694 2023-02-28 06:27:15.000000 lazynovel-0.1.4/lazynovel/open_yiqbook.py
--rw-r--r--   0 zeroseeker   (501) staff       (20)    57844 2023-02-28 06:27:15.000000 lazynovel-0.1.4/lazynovel/open_yuewen.py
-drwxr-xr-x   0 zeroseeker   (501) staff       (20)        0 2023-06-27 08:26:26.688031 lazynovel-0.1.4/lazynovel.egg-info/
--rw-r--r--   0 zeroseeker   (501) staff       (20)     1305 2023-06-27 08:26:26.000000 lazynovel-0.1.4/lazynovel.egg-info/PKG-INFO
--rw-r--r--   0 zeroseeker   (501) staff       (20)      490 2023-06-27 08:26:26.000000 lazynovel-0.1.4/lazynovel.egg-info/SOURCES.txt
--rw-r--r--   0 zeroseeker   (501) staff       (20)        1 2023-06-27 08:26:26.000000 lazynovel-0.1.4/lazynovel.egg-info/dependency_links.txt
--rw-r--r--   0 zeroseeker   (501) staff       (20)       15 2023-06-27 08:26:26.000000 lazynovel-0.1.4/lazynovel.egg-info/requires.txt
--rw-r--r--   0 zeroseeker   (501) staff       (20)       10 2023-06-27 08:26:26.000000 lazynovel-0.1.4/lazynovel.egg-info/top_level.txt
--rw-r--r--   0 zeroseeker   (501) staff       (20)       38 2023-06-27 08:26:26.688389 lazynovel-0.1.4/setup.cfg
--rw-r--r--   0 zeroseeker   (501) staff       (20)      869 2023-06-27 08:24:54.000000 lazynovel-0.1.4/setup.py
+drwxr-xr-x   0 zeroseeker   (501) staff       (20)        0 2023-06-28 07:20:07.651406 lazynovel-0.1.5/
+-rw-r--r--   0 zeroseeker   (501) staff       (20)    35181 2023-02-28 06:27:15.000000 lazynovel-0.1.5/LICENSE
+-rw-r--r--   0 zeroseeker   (501) staff       (20)     1305 2023-06-28 07:20:07.651290 lazynovel-0.1.5/PKG-INFO
+-rw-r--r--   0 zeroseeker   (501) staff       (20)      954 2023-02-28 06:27:15.000000 lazynovel-0.1.5/README.md
+drwxr-xr-x   0 zeroseeker   (501) staff       (20)        0 2023-06-28 07:20:07.650371 lazynovel-0.1.5/lazynovel/
+-rw-r--r--   0 zeroseeker   (501) staff       (20)      415 2023-05-25 10:17:10.000000 lazynovel-0.1.5/lazynovel/__init__.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)     6989 2023-05-25 08:04:09.000000 lazynovel-0.1.5/lazynovel/crawler_changdu.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)    10870 2023-06-28 07:17:21.000000 lazynovel-0.1.5/lazynovel/crawler_mbookcn.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)     5902 2023-06-27 08:25:54.000000 lazynovel-0.1.5/lazynovel/crawler_reading163.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)    10568 2023-02-28 06:27:15.000000 lazynovel-0.1.5/lazynovel/open_changdu.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)     9853 2023-02-28 06:27:15.000000 lazynovel-0.1.5/lazynovel/open_dianzhong.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)     9680 2023-02-28 06:27:15.000000 lazynovel-0.1.5/lazynovel/open_mbookcn.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)    21587 2023-05-29 10:32:37.000000 lazynovel-0.1.5/lazynovel/open_reading163.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)      830 2023-02-28 06:27:15.000000 lazynovel-0.1.5/lazynovel/open_yangguang.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)     2694 2023-02-28 06:27:15.000000 lazynovel-0.1.5/lazynovel/open_yiqbook.py
+-rw-r--r--   0 zeroseeker   (501) staff       (20)    57844 2023-02-28 06:27:15.000000 lazynovel-0.1.5/lazynovel/open_yuewen.py
+drwxr-xr-x   0 zeroseeker   (501) staff       (20)        0 2023-06-28 07:20:07.651120 lazynovel-0.1.5/lazynovel.egg-info/
+-rw-r--r--   0 zeroseeker   (501) staff       (20)     1305 2023-06-28 07:20:07.000000 lazynovel-0.1.5/lazynovel.egg-info/PKG-INFO
+-rw-r--r--   0 zeroseeker   (501) staff       (20)      490 2023-06-28 07:20:07.000000 lazynovel-0.1.5/lazynovel.egg-info/SOURCES.txt
+-rw-r--r--   0 zeroseeker   (501) staff       (20)        1 2023-06-28 07:20:07.000000 lazynovel-0.1.5/lazynovel.egg-info/dependency_links.txt
+-rw-r--r--   0 zeroseeker   (501) staff       (20)       15 2023-06-28 07:20:07.000000 lazynovel-0.1.5/lazynovel.egg-info/requires.txt
+-rw-r--r--   0 zeroseeker   (501) staff       (20)       10 2023-06-28 07:20:07.000000 lazynovel-0.1.5/lazynovel.egg-info/top_level.txt
+-rw-r--r--   0 zeroseeker   (501) staff       (20)       38 2023-06-28 07:20:07.651450 lazynovel-0.1.5/setup.cfg
+-rw-r--r--   0 zeroseeker   (501) staff       (20)      869 2023-06-28 07:17:21.000000 lazynovel-0.1.5/setup.py
```

### Comparing `lazynovel-0.1.4/LICENSE` & `lazynovel-0.1.5/LICENSE`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/PKG-INFO` & `lazynovel-0.1.5/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: lazynovel
-Version: 0.1.4
+Version: 0.1.5
 Summary: 小说平台接口封包
 Home-page: https://gitee.com/ZeroSeeker/lazynovel
 Author: ZeroSeeker
 Author-email: zeroseeker@foxmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown
```

### Comparing `lazynovel-0.1.4/README.md` & `lazynovel-0.1.5/README.md`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel/crawler_changdu.py` & `lazynovel-0.1.5/lazynovel/crawler_changdu.py`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel/crawler_mbookcn.py` & `lazynovel-0.1.5/lazynovel/crawler_mbookcn.py`

 * *Files 1% similar despite different names*

```diff
@@ -82,15 +82,15 @@
         msg_type: int,
         send_time: int,
         text_content: str = None,
         picture_url: str = None,
         graphic_title: str = None,
         graphic_text: str = None,
         description: str = None,
-
+        recharge: int = -1,
         openid: str = ""
 ):
     """
     新建客服消息
     :param token:
 
     :param msg_name: 【必填】名称（标题）
@@ -98,27 +98,28 @@
     :param text_content: 【文字消息必填】消息正文（文字消息）
     :param send_time: 预约发送 时间，13位时间戳，默认时间戳*1000
     :param openid: 测试openid
     :param picture_url: 图片（地址）
     :param graphic_title: 【图文消息必填】标题（图文消息）
     :param graphic_text: 【图文消息必填】消息正文（图文消息）
     :param description: 【非必填】消息描述（图文消息）
+    :param recharge: 【非必填】设置标签-付费情况，-1｜不限，0｜未付费，1｜已付费
 
     :return:
     """
     url = f'https://{host}/prod-api/v3/open/mng/scheduled-msg'
     data = {
         "msgType": msg_type,  # 消息类型，0：文字消息
         "msgName": str(msg_name),  # 名称（标题）
         "sendTime": send_time,  # 预约发送时间，13位时间戳，默认时间戳*1000
         "openid": openid,  # 测试openid
         "rule": {
             "sex": -1,
             "op": -1,
-            "recharge": -1,
+            "recharge": recharge,
             "coinType": -1,
             "subStart": -1,
             "subEnd": -1,
             "prefer": -1,
             "coinAmount": -1,
             "isVip": -1,
             "times": []
```

### Comparing `lazynovel-0.1.4/lazynovel/crawler_reading163.py` & `lazynovel-0.1.5/lazynovel/crawler_reading163.py`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel/open_changdu.py` & `lazynovel-0.1.5/lazynovel/open_changdu.py`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel/open_dianzhong.py` & `lazynovel-0.1.5/lazynovel/open_dianzhong.py`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel/open_mbookcn.py` & `lazynovel-0.1.5/lazynovel/open_mbookcn.py`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel/open_reading163.py` & `lazynovel-0.1.5/lazynovel/open_reading163.py`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel/open_yangguang.py` & `lazynovel-0.1.5/lazynovel/open_yangguang.py`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel/open_yiqbook.py` & `lazynovel-0.1.5/lazynovel/open_yiqbook.py`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel/open_yuewen.py` & `lazynovel-0.1.5/lazynovel/open_yuewen.py`

 * *Files identical despite different names*

### Comparing `lazynovel-0.1.4/lazynovel.egg-info/PKG-INFO` & `lazynovel-0.1.5/lazynovel.egg-info/PKG-INFO`

 * *Files 11% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: lazynovel
-Version: 0.1.4
+Version: 0.1.5
 Summary: 小说平台接口封包
 Home-page: https://gitee.com/ZeroSeeker/lazynovel
 Author: ZeroSeeker
 Author-email: zeroseeker@foxmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: Operating System :: OS Independent
 Description-Content-Type: text/markdown
```

### Comparing `lazynovel-0.1.4/setup.py` & `lazynovel-0.1.5/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -9,15 +9,15 @@
 import setuptools
 
 with open("README.md", "r", encoding='utf-8') as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="lazynovel",
-    version="0.1.4",
+    version="0.1.5",
     description="小说平台接口封包",
     long_description=long_description,
     long_description_content_type="text/markdown",
     author="ZeroSeeker",
     author_email="zeroseeker@foxmail.com",
     url="https://gitee.com/ZeroSeeker/lazynovel",
     packages=setuptools.find_packages(),
```


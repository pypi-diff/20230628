# Comparing `tmp/yplib-1.8.9.tar.gz` & `tmp/yplib-1.9.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\yplib-1.8.9.tar", last modified: Wed Jun 28 07:13:16 2023, max compression
+gzip compressed data, was "dist\yplib-1.9.0.tar", last modified: Wed Jun 28 08:09:20 2023, max compression
```

## Comparing `yplib-1.8.9.tar` & `yplib-1.9.0.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 07:13:16.654607 yplib-1.8.9/
--rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.8.9/LICENSE
--rw-rw-rw-   0        0        0      352 2023-06-28 07:13:16.653940 yplib-1.8.9/PKG-INFO
--rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.8.9/README.md
--rw-rw-rw-   0        0        0       42 2023-06-28 07:13:16.654930 yplib-1.8.9/setup.cfg
--rw-rw-rw-   0        0        0      513 2023-06-28 07:12:37.000000 yplib-1.8.9/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 07:13:16.650584 yplib-1.8.9/yplib/
--rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.8.9/yplib/__init__.py
--rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.8.9/yplib/chart.py
--rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.8.9/yplib/chart_html.py
--rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.8.9/yplib/db.py
--rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.8.9/yplib/file.py
--rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.8.9/yplib/http_util.py
--rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.8.9/yplib/index.py
--rw-rw-rw-   0        0        0     3918 2023-06-28 07:12:13.000000 yplib-1.8.9/yplib/mail.py
--rw-rw-rw-   0        0        0     3546 2023-06-28 07:11:30.000000 yplib-1.8.9/yplib/mail_html.py
--rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.8.9/yplib/temp.py
-drwxrwxrwx   0        0        0        0 2023-06-28 07:13:16.653440 yplib-1.8.9/yplib.egg-info/
--rw-rw-rw-   0        0        0      352 2023-06-28 07:13:16.000000 yplib-1.8.9/yplib.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      302 2023-06-28 07:13:16.000000 yplib-1.8.9/yplib.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 07:13:16.000000 yplib-1.8.9/yplib.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        6 2023-06-28 07:13:16.000000 yplib-1.8.9/yplib.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 08:09:20.118804 yplib-1.9.0/
+-rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.9.0/LICENSE
+-rw-rw-rw-   0        0        0      352 2023-06-28 08:09:20.118098 yplib-1.9.0/PKG-INFO
+-rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.9.0/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 08:09:20.119304 yplib-1.9.0/setup.cfg
+-rw-rw-rw-   0        0        0      513 2023-06-28 08:08:55.000000 yplib-1.9.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:09:20.115405 yplib-1.9.0/yplib/
+-rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.9.0/yplib/__init__.py
+-rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.9.0/yplib/chart.py
+-rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.9.0/yplib/chart_html.py
+-rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.9.0/yplib/db.py
+-rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.9.0/yplib/file.py
+-rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.9.0/yplib/http_util.py
+-rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.9.0/yplib/index.py
+-rw-rw-rw-   0        0        0     3805 2023-06-28 08:00:53.000000 yplib-1.9.0/yplib/mail.py
+-rw-rw-rw-   0        0        0     3557 2023-06-28 08:08:12.000000 yplib-1.9.0/yplib/mail_html.py
+-rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.9.0/yplib/temp.py
+drwxrwxrwx   0        0        0        0 2023-06-28 08:09:20.118098 yplib-1.9.0/yplib.egg-info/
+-rw-rw-rw-   0        0        0      352 2023-06-28 08:09:20.000000 yplib-1.9.0/yplib.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      302 2023-06-28 08:09:20.000000 yplib-1.9.0/yplib.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 08:09:20.000000 yplib-1.9.0/yplib.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 08:09:20.000000 yplib-1.9.0/yplib.egg-info/top_level.txt
```

### Comparing `yplib-1.8.9/LICENSE` & `yplib-1.9.0/LICENSE`

 * *Files identical despite different names*

### Comparing `yplib-1.8.9/setup.py` & `yplib-1.9.0/setup.py`

 * *Files 4% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
   long_description = fh.read()
 
 setuptools.setup(
   name="yplib",
-  version="1.8.9",
+  version="1.9.0",
   author="yangpu",
   author_email="wantwaterfish@gmail.com",
   description="util",
   long_description=long_description,
   long_description_content_type="text/markdown",
   packages=setuptools.find_packages(),
   classifiers=[
```

### Comparing `yplib-1.8.9/yplib/__init__.py` & `yplib-1.9.0/yplib/__init__.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.9/yplib/chart.py` & `yplib-1.9.0/yplib/chart.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.9/yplib/chart_html.py` & `yplib-1.9.0/yplib/chart_html.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.9/yplib/db.py` & `yplib-1.9.0/yplib/db.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.9/yplib/file.py` & `yplib-1.9.0/yplib/file.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.9/yplib/http_util.py` & `yplib-1.9.0/yplib/http_util.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.9/yplib/index.py` & `yplib-1.9.0/yplib/index.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.9/yplib/mail.py` & `yplib-1.9.0/yplib/mail.py`

 * *Files 22% similar despite different names*

```diff
@@ -33,95 +33,94 @@
 # 	title: "里面的一份小标题",
 # 	type: "error",
 # 	content: [
 # 		{ "调用次数": 100, "成功次数": 50 },
 # 		"总体还算可以的"
 # 	]
 # }
-#
-# data_obj = [
-#         { "调用次数": 100, "成功次数": 50 },
-#         { "查询次数": 200, "失败次数": 150 },
-#         { value: 735, name: "Direct" },
-# 		"总体还算可以的"
-#       ]
 # data_obj = [
 # 	{
-# 		title: "里面的一份小标题",
-# 		type: "error",
-# 		content: [
+# 		"title": "里面的一份小标题",
+# 		"type": "error",
+# 		"content": [
 # 			{ "调用次数": 100, "成功次数": 50 },
 # 			"总体还算可以的"
 # 		]
 # 	},
 # 	{
-# 		title: "里面的一份正常的标题",
-# 		content: [
+# 		"title": "里面的一份正常的标题",
+# 		"content": [
 # 			{ "调用次数": 500, "成功次数": 500 },
 # 			"总体不行的"
 # 		]
 # 	}
 # ]
+#
+# data_obj = [
+#     {"调用次数": 100, "成功次数": 50},
+#     {"查询次数": 200, "失败次数": 150},
+#     {"value": 735, "name": "Direct"},
+#     "总体还算可以的"
+# ]
 def get_mail_html(data_obj):
-    # if isinstance(data, dict) or isinstance(data, list) or isinstance(data, tuple) or isinstance(data, set):
     html_list = []
-    if isinstance(data_obj, list):
+    if isinstance(data_obj, list) or isinstance(data_obj, set):
         for data_one in data_obj:
-            print(data_one)
             html_list.append(get_mail_html_one(data_one))
     else:
         html_list.append(get_mail_html_one(data_obj))
     return ''.join(mail_html(html_list))
 
 
 # 获得 邮件的内容信息
-# 正常的数据
-# data_obj = {
-# 	title: "里面的一份小标题",
-# 	type: "error",
-# 	content: [
-#       {"调用次数": 100, "成功次数": 50},
-#       {"调用次数": 1020, "成功次数": 510},
-#       {"调用次数": 1030, "成功次数": 550},
-#       {"调用次数": 1090, "成功次数": 590},
-# 		"总体还算可以的"
+# data_obj =
+# {
+# 	"title": "里面的一份小标题",
+# 	"type": "error",
+# 	"content": {
+# 		"调用次数1": 100,
+# 		"成功次数2": 50,
+# 		"调用次数3": 1020,
+# 		"成功次数4": 510,
+# 		"调用次数5": 1030,
+# 		"成功次数6": 550,
+# 		"调用次数7": 1090,
+# 		"成功次数8": 590
+# 	}
+# }
+# data_obj =
+# {
+# 	"title": "里面的一份小标题",
+# 	"type": "error",
+# 	"content": [
+# 		"调用次数1",
+# 		"可以",
+# 		{"调用次数1": 100},
+# 		{"成功次数2": 50},
 # 	]
 # }
+# data_obj = {"调用次数": 100, "成功次数": 50}
 def get_mail_html_one(data_obj):
     title = data_obj['title'] if 'title' in data_obj else str(to_datetime())
     type = data_obj['type'] if 'type' in data_obj else 'normal'
     content = data_obj['content'] if 'content' in data_obj else data_obj
     stripe = True
     html_list = []
-    for o_c in content:
-        if isinstance(o_c, dict) or isinstance(o_c, tuple) or isinstance(o_c, set):
-            for o_k in o_c:
-                html_list.extend(mail_content_html(key=o_k, value=o_c[o_k], error=type == 'error', stripe=stripe))
+    if isinstance(content, list) or isinstance(content, set):
+        for o_c in content:
+            if isinstance(o_c, dict) or isinstance(o_c, tuple):
+                for o_k in o_c:
+                    html_list.extend(mail_content_html(key=o_k, value=o_c[o_k], error=type == 'error', stripe=stripe))
+                    stripe = not stripe
+            else:
+                html_list.extend(mail_content_html(key=o_c, error=type == 'error', stripe=stripe))
                 stripe = not stripe
-        else:
-            html_list.extend(mail_content_html(key=o_c, error=type == 'error', stripe=stripe))
+    elif isinstance(content, dict) or isinstance(content, tuple):
+        for o_k in content:
+            html_list.extend(mail_content_html(key=o_k, value=content[o_k], error=type == 'error', stripe=stripe))
             stripe = not stripe
+    else:
+        html_list.extend(mail_content_html(key=str(content), error=type == 'error', stripe=stripe))
     return ''.join(mail_title_html(title, html_list, type == 'error'))
 
-# print('end')
 
-#
-# h = get_mail_html({
-#     'title': "里面的一份小标题",
-#     # 'type': "error",
-#     'content': [
-#         {"调用次数": 100, "成功次数": 50},
-#         {"调用次数": 1020, "成功次数": 510},
-#         {"调用次数": 1030, "成功次数": 550},
-#         {"调用次数": 1090, "成功次数": 590},
-#         "总体还算可以的"
-#     ]
-# })
-#
-# send_mail(str(to_datetime())[0:19] + ' 测试', h,
-#           user='wantwaterfish@163.com',
-#           password='CKGCCQTBIDQVIITZ',
-#           send='smtp.163.com',
-#           send_port=465,
-#           receivers=['1547878995@qq.com'])
-#
-#
+# print('end')
```

### Comparing `yplib-1.8.9/yplib/mail_html.py` & `yplib-1.9.0/yplib/mail_html.py`

 * *Files 1% similar despite different names*

```diff
@@ -52,15 +52,15 @@
         color_value = color_normal_value
 
     one = ['<div style="padding: 5px;background:#-color_stripe-;border-radius:5px;">',
            '    <span>-key-</span>',
            '</div>']
     key_value = ['<div style="border-radius:5px;padding:2px;background: #-color_stripe-;">',
                  '    <div style="width: 48%;display: inline-block;white-space: normal;word-wrap: break-word;">',
-                 '        <div style="width: 94%;display: inline-block;text-align: right;">',
+                 '        <div style="width:calc(100%-15px);display: inline-block;text-align: right;">',
                  '            <span>-key-</span>',
                  '        </div>',
                  '        <div style="text-align: center;width: 10px;display: inline-block;float: right;border-radius: 3px;background: #-color_colon-;">',
                  '            <span>:</span>',
                  '        </div>',
                  '    </div>',
                  '    <div style="width: 50%;background: #-color_value-;display: inline-block;white-space: normal;word-wrap: break-word;border-radius:5px;">',
```


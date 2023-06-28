# Comparing `tmp/yplib-1.8.7.tar.gz` & `tmp/yplib-1.8.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\yplib-1.8.7.tar", last modified: Wed Jun 28 06:42:03 2023, max compression
+gzip compressed data, was "dist\yplib-1.8.8.tar", last modified: Wed Jun 28 06:55:11 2023, max compression
```

## Comparing `yplib-1.8.7.tar` & `yplib-1.8.8.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 06:42:03.633951 yplib-1.8.7/
--rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.8.7/LICENSE
--rw-rw-rw-   0        0        0      352 2023-06-28 06:42:03.633451 yplib-1.8.7/PKG-INFO
--rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.8.7/README.md
--rw-rw-rw-   0        0        0       42 2023-06-28 06:42:03.634451 yplib-1.8.7/setup.cfg
--rw-rw-rw-   0        0        0      513 2023-06-28 06:42:00.000000 yplib-1.8.7/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:42:03.630181 yplib-1.8.7/yplib/
--rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.8.7/yplib/__init__.py
--rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.8.7/yplib/chart.py
--rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.8.7/yplib/chart_html.py
--rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.8.7/yplib/db.py
--rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.8.7/yplib/file.py
--rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.8.7/yplib/http_util.py
--rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.8.7/yplib/index.py
--rw-rw-rw-   0        0        0     2506 2023-06-28 06:40:01.000000 yplib-1.8.7/yplib/mail.py
--rw-rw-rw-   0        0        0     3520 2023-06-27 09:03:17.000000 yplib-1.8.7/yplib/mail_html.py
--rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.8.7/yplib/temp.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:42:03.632938 yplib-1.8.7/yplib.egg-info/
--rw-rw-rw-   0        0        0      352 2023-06-28 06:42:03.000000 yplib-1.8.7/yplib.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      302 2023-06-28 06:42:03.000000 yplib-1.8.7/yplib.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 06:42:03.000000 yplib-1.8.7/yplib.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        6 2023-06-28 06:42:03.000000 yplib-1.8.7/yplib.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 06:55:11.407999 yplib-1.8.8/
+-rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.8.8/LICENSE
+-rw-rw-rw-   0        0        0      352 2023-06-28 06:55:11.407999 yplib-1.8.8/PKG-INFO
+-rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.8.8/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 06:55:11.408647 yplib-1.8.8/setup.cfg
+-rw-rw-rw-   0        0        0      513 2023-06-28 06:54:50.000000 yplib-1.8.8/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:55:11.404503 yplib-1.8.8/yplib/
+-rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.8.8/yplib/__init__.py
+-rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.8.8/yplib/chart.py
+-rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.8.8/yplib/chart_html.py
+-rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.8.8/yplib/db.py
+-rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.8.8/yplib/file.py
+-rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.8.8/yplib/http_util.py
+-rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.8.8/yplib/index.py
+-rw-rw-rw-   0        0        0     3072 2023-06-28 06:54:43.000000 yplib-1.8.8/yplib/mail.py
+-rw-rw-rw-   0        0        0     3530 2023-06-28 06:54:33.000000 yplib-1.8.8/yplib/mail_html.py
+-rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.8.8/yplib/temp.py
+drwxrwxrwx   0        0        0        0 2023-06-28 06:55:11.406987 yplib-1.8.8/yplib.egg-info/
+-rw-rw-rw-   0        0        0      352 2023-06-28 06:55:11.000000 yplib-1.8.8/yplib.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      302 2023-06-28 06:55:11.000000 yplib-1.8.8/yplib.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 06:55:11.000000 yplib-1.8.8/yplib.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 06:55:11.000000 yplib-1.8.8/yplib.egg-info/top_level.txt
```

### Comparing `yplib-1.8.7/LICENSE` & `yplib-1.8.8/LICENSE`

 * *Files identical despite different names*

### Comparing `yplib-1.8.7/setup.py` & `yplib-1.8.8/setup.py`

 * *Files 2% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
   long_description = fh.read()
 
 setuptools.setup(
   name="yplib",
-  version="1.8.7",
+  version="1.8.8",
   author="yangpu",
   author_email="wantwaterfish@gmail.com",
   description="util",
   long_description=long_description,
   long_description_content_type="text/markdown",
   packages=setuptools.find_packages(),
   classifiers=[
```

### Comparing `yplib-1.8.7/yplib/__init__.py` & `yplib-1.8.8/yplib/__init__.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.7/yplib/chart.py` & `yplib-1.8.8/yplib/chart.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.7/yplib/chart_html.py` & `yplib-1.8.8/yplib/chart_html.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.7/yplib/db.py` & `yplib-1.8.8/yplib/db.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.7/yplib/file.py` & `yplib-1.8.8/yplib/file.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.7/yplib/http_util.py` & `yplib-1.8.8/yplib/http_util.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.7/yplib/index.py` & `yplib-1.8.8/yplib/index.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.7/yplib/mail.py` & `yplib-1.8.8/yplib/mail.py`

 * *Files 14% similar despite different names*

```diff
@@ -1,8 +1,9 @@
 from yplib.index import *
+from yplib.mail_html import *
 import smtplib
 from email.mime.text import MIMEText
 
 
 def send_mail(title,
               content,
               user='',
@@ -56,31 +57,44 @@
 # 		title: "里面的一份正常的标题",
 # 		content: [
 # 			{ "调用次数": 500, "成功次数": 500 },
 # 			"总体不行的"
 # 		]
 # 	}
 # ]
-def get_mail_content(data_obj):
+def get_mail_html(data_obj):
     # if isinstance(data, dict) or isinstance(data, list) or isinstance(data, tuple) or isinstance(data, set):
     if isinstance(data_obj, dict) or isinstance(data_obj, tuple) or isinstance(data_obj, set):
         title = data_obj['title'] if 'title' in data_obj else str(to_datetime())
         type = data_obj['type'] if 'type' in data_obj else 'normal'
         content = data_obj['content']
+        stripe = True
+        html_list = []
         for o_c in content:
             if isinstance(o_c, dict) or isinstance(o_c, tuple) or isinstance(o_c, set):
                 for o_k in o_c:
-                    print(o_k, o_c[o_k])
+                    html_list.extend(mail_content_html(o_k, o_c[o_k], type == 'error', stripe))
+                    stripe = not stripe
             else:
-                print(o_c)
-
+                html_list.extend(mail_content_html(o_c, type == 'error', stripe))
+        return mail_html(title, mail_title_html(title, html_list, type == 'error'))
 
 # print('end')
+
 #
-# get_mail_content({
+# h = get_mail_html({
 #     'title': "里面的一份小标题",
 #     'type': "error",
 #     'content': [
 #         {"调用次数": 100, "成功次数": 50},
 #         "总体还算可以的"
 #     ]
 # })
+#
+# send_mail(str(to_datetime())[0:19] + ' 测试', h,
+#           user='wantwaterfish@163.com',
+#           password='CKGCCQTBIDQVIITZ',
+#           send='smtp.163.com',
+#           send_port=465,
+#           receivers=['1547878995@qq.com'])
+
+
```

### Comparing `yplib-1.8.7/yplib/mail_html.py` & `yplib-1.8.8/yplib/mail_html.py`

 * *Files 2% similar despite different names*

```diff
@@ -66,11 +66,11 @@
                  '        <div style="padding: 3px;">',
                  '            <span>-value-</span>',
                  '        </div>',
                  '    </div>',
                  '</div>']
     s = one if value is None else key_value
     return list(map(lambda x: x.replace('-color_stripe-', color_stripe)
-                    .replace('-key-', key)
-                    .replace('-value-', value)
+                    .replace('-key-', str(key))
+                    .replace('-value-', str(value))
                     .replace('-color_colon-', color_colon)
                     .replace('-color_value-', color_value), s))
```

#### html2text {}

```diff
@@ -40,10 +40,10 @@
 ', '
 ', '
 ', '
 ', ' -value-', '
 ', '
 ', '
 '] s = one if value is None else key_value return list(map(lambda x: x.replace
-('-color_stripe-', color_stripe) .replace('-key-', key) .replace('-value-',
-value) .replace('-color_colon-', color_colon) .replace('-color_value-',
+('-color_stripe-', color_stripe) .replace('-key-', str(key)) .replace('-value-
+', str(value)) .replace('-color_colon-', color_colon) .replace('-color_value-',
 color_value), s))
```


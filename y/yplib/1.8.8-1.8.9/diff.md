# Comparing `tmp/yplib-1.8.8.tar.gz` & `tmp/yplib-1.8.9.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "dist\yplib-1.8.8.tar", last modified: Wed Jun 28 06:55:11 2023, max compression
+gzip compressed data, was "dist\yplib-1.8.9.tar", last modified: Wed Jun 28 07:13:16 2023, max compression
```

## Comparing `yplib-1.8.8.tar` & `yplib-1.8.9.tar`

### file list

```diff
@@ -1,22 +1,22 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 06:55:11.407999 yplib-1.8.8/
--rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.8.8/LICENSE
--rw-rw-rw-   0        0        0      352 2023-06-28 06:55:11.407999 yplib-1.8.8/PKG-INFO
--rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.8.8/README.md
--rw-rw-rw-   0        0        0       42 2023-06-28 06:55:11.408647 yplib-1.8.8/setup.cfg
--rw-rw-rw-   0        0        0      513 2023-06-28 06:54:50.000000 yplib-1.8.8/setup.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:55:11.404503 yplib-1.8.8/yplib/
--rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.8.8/yplib/__init__.py
--rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.8.8/yplib/chart.py
--rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.8.8/yplib/chart_html.py
--rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.8.8/yplib/db.py
--rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.8.8/yplib/file.py
--rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.8.8/yplib/http_util.py
--rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.8.8/yplib/index.py
--rw-rw-rw-   0        0        0     3072 2023-06-28 06:54:43.000000 yplib-1.8.8/yplib/mail.py
--rw-rw-rw-   0        0        0     3530 2023-06-28 06:54:33.000000 yplib-1.8.8/yplib/mail_html.py
--rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.8.8/yplib/temp.py
-drwxrwxrwx   0        0        0        0 2023-06-28 06:55:11.406987 yplib-1.8.8/yplib.egg-info/
--rw-rw-rw-   0        0        0      352 2023-06-28 06:55:11.000000 yplib-1.8.8/yplib.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      302 2023-06-28 06:55:11.000000 yplib-1.8.8/yplib.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 06:55:11.000000 yplib-1.8.8/yplib.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0        6 2023-06-28 06:55:11.000000 yplib-1.8.8/yplib.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-28 07:13:16.654607 yplib-1.8.9/
+-rw-rw-rw-   0        0        0     1091 2023-06-08 01:05:18.000000 yplib-1.8.9/LICENSE
+-rw-rw-rw-   0        0        0      352 2023-06-28 07:13:16.653940 yplib-1.8.9/PKG-INFO
+-rw-rw-rw-   0        0        0       13 2023-06-14 02:50:41.000000 yplib-1.8.9/README.md
+-rw-rw-rw-   0        0        0       42 2023-06-28 07:13:16.654930 yplib-1.8.9/setup.cfg
+-rw-rw-rw-   0        0        0      513 2023-06-28 07:12:37.000000 yplib-1.8.9/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:13:16.650584 yplib-1.8.9/yplib/
+-rw-rw-rw-   0        0        0      558 2023-06-28 06:41:55.000000 yplib-1.8.9/yplib/__init__.py
+-rw-rw-rw-   0        0        0    11744 2023-06-26 01:25:08.000000 yplib-1.8.9/yplib/chart.py
+-rw-rw-rw-   0        0        0     8553 2023-06-26 00:52:29.000000 yplib-1.8.9/yplib/chart_html.py
+-rw-rw-rw-   0        0        0      838 2023-06-26 01:33:00.000000 yplib-1.8.9/yplib/db.py
+-rw-rw-rw-   0        0        0     6984 2023-06-16 00:59:15.000000 yplib-1.8.9/yplib/file.py
+-rw-rw-rw-   0        0        0     3471 2023-06-19 01:33:36.000000 yplib-1.8.9/yplib/http_util.py
+-rw-rw-rw-   0        0        0    26791 2023-06-27 01:45:16.000000 yplib-1.8.9/yplib/index.py
+-rw-rw-rw-   0        0        0     3918 2023-06-28 07:12:13.000000 yplib-1.8.9/yplib/mail.py
+-rw-rw-rw-   0        0        0     3546 2023-06-28 07:11:30.000000 yplib-1.8.9/yplib/mail_html.py
+-rw-rw-rw-   0        0        0      124 2023-06-25 07:57:19.000000 yplib-1.8.9/yplib/temp.py
+drwxrwxrwx   0        0        0        0 2023-06-28 07:13:16.653440 yplib-1.8.9/yplib.egg-info/
+-rw-rw-rw-   0        0        0      352 2023-06-28 07:13:16.000000 yplib-1.8.9/yplib.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      302 2023-06-28 07:13:16.000000 yplib-1.8.9/yplib.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 07:13:16.000000 yplib-1.8.9/yplib.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0        6 2023-06-28 07:13:16.000000 yplib-1.8.9/yplib.egg-info/top_level.txt
```

### Comparing `yplib-1.8.8/LICENSE` & `yplib-1.8.9/LICENSE`

 * *Files identical despite different names*

### Comparing `yplib-1.8.8/setup.py` & `yplib-1.8.9/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
   long_description = fh.read()
 
 setuptools.setup(
   name="yplib",
-  version="1.8.8",
+  version="1.8.9",
   author="yangpu",
   author_email="wantwaterfish@gmail.com",
   description="util",
   long_description=long_description,
   long_description_content_type="text/markdown",
   packages=setuptools.find_packages(),
   classifiers=[
```

### Comparing `yplib-1.8.8/yplib/__init__.py` & `yplib-1.8.9/yplib/__init__.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.8/yplib/chart.py` & `yplib-1.8.9/yplib/chart.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.8/yplib/chart_html.py` & `yplib-1.8.9/yplib/chart_html.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.8/yplib/db.py` & `yplib-1.8.9/yplib/db.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.8/yplib/file.py` & `yplib-1.8.9/yplib/file.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.8/yplib/http_util.py` & `yplib-1.8.9/yplib/http_util.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.8/yplib/index.py` & `yplib-1.8.9/yplib/index.py`

 * *Files identical despite different names*

### Comparing `yplib-1.8.8/yplib/mail.py` & `yplib-1.8.9/yplib/mail.py`

 * *Files 19% similar despite different names*

```diff
@@ -59,42 +59,69 @@
 # 			{ "调用次数": 500, "成功次数": 500 },
 # 			"总体不行的"
 # 		]
 # 	}
 # ]
 def get_mail_html(data_obj):
     # if isinstance(data, dict) or isinstance(data, list) or isinstance(data, tuple) or isinstance(data, set):
-    if isinstance(data_obj, dict) or isinstance(data_obj, tuple) or isinstance(data_obj, set):
-        title = data_obj['title'] if 'title' in data_obj else str(to_datetime())
-        type = data_obj['type'] if 'type' in data_obj else 'normal'
-        content = data_obj['content']
-        stripe = True
-        html_list = []
-        for o_c in content:
-            if isinstance(o_c, dict) or isinstance(o_c, tuple) or isinstance(o_c, set):
-                for o_k in o_c:
-                    html_list.extend(mail_content_html(o_k, o_c[o_k], type == 'error', stripe))
-                    stripe = not stripe
-            else:
-                html_list.extend(mail_content_html(o_c, type == 'error', stripe))
-        return mail_html(title, mail_title_html(title, html_list, type == 'error'))
+    html_list = []
+    if isinstance(data_obj, list):
+        for data_one in data_obj:
+            print(data_one)
+            html_list.append(get_mail_html_one(data_one))
+    else:
+        html_list.append(get_mail_html_one(data_obj))
+    return ''.join(mail_html(html_list))
+
+
+# 获得 邮件的内容信息
+# 正常的数据
+# data_obj = {
+# 	title: "里面的一份小标题",
+# 	type: "error",
+# 	content: [
+#       {"调用次数": 100, "成功次数": 50},
+#       {"调用次数": 1020, "成功次数": 510},
+#       {"调用次数": 1030, "成功次数": 550},
+#       {"调用次数": 1090, "成功次数": 590},
+# 		"总体还算可以的"
+# 	]
+# }
+def get_mail_html_one(data_obj):
+    title = data_obj['title'] if 'title' in data_obj else str(to_datetime())
+    type = data_obj['type'] if 'type' in data_obj else 'normal'
+    content = data_obj['content'] if 'content' in data_obj else data_obj
+    stripe = True
+    html_list = []
+    for o_c in content:
+        if isinstance(o_c, dict) or isinstance(o_c, tuple) or isinstance(o_c, set):
+            for o_k in o_c:
+                html_list.extend(mail_content_html(key=o_k, value=o_c[o_k], error=type == 'error', stripe=stripe))
+                stripe = not stripe
+        else:
+            html_list.extend(mail_content_html(key=o_c, error=type == 'error', stripe=stripe))
+            stripe = not stripe
+    return ''.join(mail_title_html(title, html_list, type == 'error'))
 
 # print('end')
 
 #
 # h = get_mail_html({
 #     'title': "里面的一份小标题",
-#     'type': "error",
+#     # 'type': "error",
 #     'content': [
 #         {"调用次数": 100, "成功次数": 50},
+#         {"调用次数": 1020, "成功次数": 510},
+#         {"调用次数": 1030, "成功次数": 550},
+#         {"调用次数": 1090, "成功次数": 590},
 #         "总体还算可以的"
 #     ]
 # })
 #
 # send_mail(str(to_datetime())[0:19] + ' 测试', h,
 #           user='wantwaterfish@163.com',
 #           password='CKGCCQTBIDQVIITZ',
 #           send='smtp.163.com',
 #           send_port=465,
 #           receivers=['1547878995@qq.com'])
-
-
+#
+#
```

### Comparing `yplib-1.8.8/yplib/mail_html.py` & `yplib-1.8.9/yplib/mail_html.py`

 * *Files 5% similar despite different names*

```diff
@@ -1,221 +1,222 @@
-00000000: 2320 6d61 696c 20e9 82ae e4bb b6e4 b8ad  # mail .........
-00000010: e79a 8420 6874 6d6c 20e6 a8a1 e69d bf0d  ... html .......
-00000020: 0a64 6566 206d 6169 6c5f 6874 6d6c 2874  .def mail_html(t
-00000030: 6974 6c65 3d27 7469 746c 6527 2c20 626f  itle='title', bo
-00000040: 6479 3d27 7465 7374 2729 3a0d 0a20 2020  dy='test'):..   
-00000050: 2073 203d 205b 273c 2144 4f43 5459 5045   s = ['<!DOCTYPE
-00000060: 2068 746d 6c3e 272c 0d0a 2020 2020 2020   html>',..      
-00000070: 2020 2027 3c68 746d 6c3e 272c 0d0a 2020     '<html>',..  
-00000080: 2020 2020 2020 2027 3c68 6561 643e 272c         '<head>',
-00000090: 0d0a 2020 2020 2020 2020 2027 2020 2020  ..         '    
-000000a0: 3c6d 6574 6120 6368 6172 7365 743d 2275  <meta charset="u
-000000b0: 7466 2d38 222f 3e27 2c0d 0a20 2020 2020  tf-8"/>',..     
-000000c0: 2020 2020 2720 2020 203c 6d65 7461 2068      '    <meta h
-000000d0: 7474 702d 6571 7569 763d 2258 2d55 412d  ttp-equiv="X-UA-
-000000e0: 436f 6d70 6174 6962 6c65 2220 636f 6e74  Compatible" cont
-000000f0: 656e 743d 2249 453d 6564 6765 2c63 6872  ent="IE=edge,chr
-00000100: 6f6d 653d 3122 3e27 2c0d 0a20 2020 2020  ome=1">',..     
-00000110: 2020 2020 2720 2020 203c 7469 746c 653e      '    <title>
-00000120: 2d74 6974 6c65 2d3c 2f74 6974 6c65 3e27  -title-</title>'
-00000130: 2c0d 0a20 2020 2020 2020 2020 273c 2f68  ,..         '</h
-00000140: 6561 643e 272c 0d0a 2020 2020 2020 2020  ead>',..        
-00000150: 2027 3c62 6f64 793e 272c 0d0a 2020 2020   '<body>',..    
-00000160: 2020 2020 2027 2d62 6f64 792d 272c 0d0a       '-body-',..
-00000170: 2020 2020 2020 2020 2027 3c2f 626f 6479           '</body
-00000180: 3e27 2c0d 0a20 2020 2020 2020 2020 273c  >',..         '<
-00000190: 2f68 746d 6c3e 275d 0d0a 2020 2020 7265  /html>']..    re
-000001a0: 7475 726e 206c 6973 7428 6d61 7028 6c61  turn list(map(la
-000001b0: 6d62 6461 2078 3a20 782e 7265 706c 6163  mbda x: x.replac
-000001c0: 6528 272d 7469 746c 652d 272c 2027 272e  e('-title-', ''.
-000001d0: 6a6f 696e 2874 6974 6c65 2929 2e72 6570  join(title)).rep
-000001e0: 6c61 6365 2827 2d62 6f64 792d 272c 2027  lace('-body-', '
-000001f0: 272e 6a6f 696e 2862 6f64 7929 292c 2073  '.join(body)), s
-00000200: 2929 0d0a 0d0a 0d0a 2320 e982 aee4 bbb6  ))......# ......
-00000210: e4b8 ade7 9a84 2074 6974 6c65 20e7 9a84  ...... title ...
-00000220: 6874 6d6c 20e4 bba3 e7a0 810d 0a64 6566  html ........def
-00000230: 206d 6169 6c5f 7469 746c 655f 6874 6d6c   mail_title_html
-00000240: 2874 6974 6c65 3d27 7469 746c 6527 2c20  (title='title', 
-00000250: 626f 6479 3d27 7465 7374 272c 2065 7272  body='test', err
-00000260: 6f72 3d46 616c 7365 293a 0d0a 2020 2020  or=False):..    
-00000270: 636f 6c6f 7220 3d20 2766 3335 3232 3227  color = 'f35222'
-00000280: 2069 6620 6572 726f 7220 656c 7365 2027   if error else '
-00000290: 3365 6366 3538 270d 0a20 2020 2073 203d  3ecf58'..    s =
-000002a0: 205b 273c 6469 7620 7374 796c 653d 2270   ['<div style="p
-000002b0: 6164 6469 6e67 2d62 6f74 746f 6d3a 2035  adding-bottom: 5
-000002c0: 7078 3b62 6163 6b67 726f 756e 643a 2077  px;background: w
-000002d0: 6869 7465 3b74 6578 742d 616c 6967 6e3a  hite;text-align:
-000002e0: 6365 6e74 6572 3b22 3e27 2c0d 0a20 2020  center;">',..   
-000002f0: 2020 2020 2020 2720 2020 203c 6469 7620        '    <div 
-00000300: 7374 796c 653d 2262 6f72 6465 722d 7261  style="border-ra
-00000310: 6469 7573 3a35 7078 3b22 3e27 2c0d 0a20  dius:5px;">',.. 
-00000320: 2020 2020 2020 2020 2720 2020 2020 2020          '       
-00000330: 203c 6469 7620 7374 796c 653d 2270 6164   <div style="pad
-00000340: 6469 6e67 3a20 3570 783b 6261 636b 6772  ding: 5px;backgr
-00000350: 6f75 6e64 3a23 2d63 6f6c 6f72 2d3b 626f  ound:#-color-;bo
-00000360: 7264 6572 2d72 6164 6975 733a 3570 783b  rder-radius:5px;
-00000370: 223e 272c 0d0a 2020 2020 2020 2020 2027  ">',..         '
-00000380: 2020 2020 2020 2020 2020 2020 3c73 7061              <spa
-00000390: 6e20 7374 796c 653d 2266 6f6e 742d 7369  n style="font-si
-000003a0: 7a65 3a31 3770 783b 223e 2d74 6974 6c65  ze:17px;">-title
-000003b0: 2d3c 2f73 7061 6e3e 272c 0d0a 2020 2020  -</span>',..    
-000003c0: 2020 2020 2027 2020 2020 2020 2020 3c2f       '        </
-000003d0: 6469 763e 272c 0d0a 2020 2020 2020 2020  div>',..        
-000003e0: 2027 2020 2020 2020 2020 3c64 6976 2073   '        <div s
-000003f0: 7479 6c65 3d22 666f 6e74 2d73 697a 653a  tyle="font-size:
-00000400: 3133 7078 3b74 6578 742d 616c 6967 6e3a  13px;text-align:
-00000410: 6365 6e74 6572 3b62 6f72 6465 722d 7261  center;border-ra
-00000420: 6469 7573 3a35 7078 3b22 3e27 2c0d 0a20  dius:5px;">',.. 
-00000430: 2020 2020 2020 2020 2720 2020 2020 2020          '       
-00000440: 2020 2020 202d 626f 6479 2d27 2c0d 0a20       -body-',.. 
-00000450: 2020 2020 2020 2020 2720 2020 2020 2020          '       
-00000460: 203c 2f64 6976 3e27 2c0d 0a20 2020 2020   </div>',..     
-00000470: 2020 2020 2720 2020 203c 2f64 6976 3e27      '    </div>'
-00000480: 2c0d 0a20 2020 2020 2020 2020 273c 2f64  ,..         '</d
-00000490: 6976 3e27 5d0d 0a20 2020 2072 6574 7572  iv>']..    retur
-000004a0: 6e20 6c69 7374 286d 6170 286c 616d 6264  n list(map(lambd
-000004b0: 6120 783a 2078 2e72 6570 6c61 6365 2827  a x: x.replace('
-000004c0: 2d74 6974 6c65 2d27 2c20 7469 746c 6529  -title-', title)
-000004d0: 2e72 6570 6c61 6365 2827 2d62 6f64 792d  .replace('-body-
-000004e0: 272c 2027 272e 6a6f 696e 2862 6f64 7929  ', ''.join(body)
-000004f0: 292e 7265 706c 6163 6528 272d 636f 6c6f  ).replace('-colo
-00000500: 722d 272c 2063 6f6c 6f72 292c 2073 2929  r-', color), s))
-00000510: 0d0a 0d0a 0d0a 2320 e982 aee4 bbb6 e4b8  ......# ........
-00000520: ade7 9a84 2063 6f6e 7465 6e74 20e7 9a84  .... content ...
-00000530: 6874 6d6c 20e4 bba3 e7a0 810d 0a64 6566  html ........def
-00000540: 206d 6169 6c5f 636f 6e74 656e 745f 6874   mail_content_ht
-00000550: 6d6c 286b 6579 3d4e 6f6e 652c 2076 616c  ml(key=None, val
-00000560: 7565 3d4e 6f6e 652c 2065 7272 6f72 3d46  ue=None, error=F
-00000570: 616c 7365 2c20 7374 7269 7065 3d46 616c  alse, stripe=Fal
-00000580: 7365 293a 0d0a 2020 2020 636f 6c6f 725f  se):..    color_
-00000590: 6e6f 726d 616c 5f31 203d 2027 6265 6539  normal_1 = 'bee9
-000005a0: 6336 270d 0a20 2020 2063 6f6c 6f72 5f6e  c6'..    color_n
-000005b0: 6f72 6d61 6c5f 3220 3d20 2763 6266 3964  ormal_2 = 'cbf9d
-000005c0: 3327 0d0a 2020 2020 636f 6c6f 725f 6e6f  3'..    color_no
-000005d0: 726d 616c 5f63 6f6c 6f6e 203d 2027 6633  rmal_colon = 'f3
-000005e0: 6534 6534 270d 0a20 2020 2063 6f6c 6f72  e4e4'..    color
-000005f0: 5f6e 6f72 6d61 6c5f 7661 6c75 6520 3d20  _normal_value = 
-00000600: 2739 6265 6461 3927 0d0a 0d0a 2020 2020  '9beda9'....    
-00000610: 636f 6c6f 725f 6572 726f 725f 3120 3d20  color_error_1 = 
-00000620: 2765 3962 3339 3427 0d0a 2020 2020 636f  'e9b394'..    co
-00000630: 6c6f 725f 6572 726f 725f 3220 3d20 2765  lor_error_2 = 'e
-00000640: 3762 3864 3627 0d0a 2020 2020 636f 6c6f  7b8d6'..    colo
-00000650: 725f 6572 726f 725f 636f 6c6f 6e20 3d20  r_error_colon = 
-00000660: 2765 3938 6338 6327 0d0a 2020 2020 636f  'e98c8c'..    co
-00000670: 6c6f 725f 6572 726f 725f 7661 6c75 6520  lor_error_value 
-00000680: 3d20 2765 6439 3062 6227 0d0a 2020 2020  = 'ed90bb'..    
-00000690: 6966 2065 7272 6f72 3a0d 0a20 2020 2020  if error:..     
-000006a0: 2020 2063 6f6c 6f72 5f73 7472 6970 6520     color_stripe 
-000006b0: 3d20 636f 6c6f 725f 6572 726f 725f 3120  = color_error_1 
-000006c0: 6966 2073 7472 6970 6520 656c 7365 2063  if stripe else c
-000006d0: 6f6c 6f72 5f65 7272 6f72 5f32 0d0a 2020  olor_error_2..  
-000006e0: 2020 2020 2020 636f 6c6f 725f 636f 6c6f        color_colo
-000006f0: 6e20 3d20 636f 6c6f 725f 6572 726f 725f  n = color_error_
-00000700: 636f 6c6f 6e0d 0a20 2020 2020 2020 2063  colon..        c
-00000710: 6f6c 6f72 5f76 616c 7565 203d 2063 6f6c  olor_value = col
-00000720: 6f72 5f65 7272 6f72 5f76 616c 7565 0d0a  or_error_value..
-00000730: 2020 2020 656c 7365 3a0d 0a20 2020 2020      else:..     
-00000740: 2020 2063 6f6c 6f72 5f73 7472 6970 6520     color_stripe 
-00000750: 3d20 636f 6c6f 725f 6e6f 726d 616c 5f31  = color_normal_1
-00000760: 2069 6620 7374 7269 7065 2065 6c73 6520   if stripe else 
-00000770: 636f 6c6f 725f 6e6f 726d 616c 5f32 0d0a  color_normal_2..
-00000780: 2020 2020 2020 2020 636f 6c6f 725f 636f          color_co
-00000790: 6c6f 6e20 3d20 636f 6c6f 725f 6e6f 726d  lon = color_norm
-000007a0: 616c 5f63 6f6c 6f6e 0d0a 2020 2020 2020  al_colon..      
-000007b0: 2020 636f 6c6f 725f 7661 6c75 6520 3d20    color_value = 
-000007c0: 636f 6c6f 725f 6e6f 726d 616c 5f76 616c  color_normal_val
-000007d0: 7565 0d0a 0d0a 2020 2020 6f6e 6520 3d20  ue....    one = 
-000007e0: 5b27 3c64 6976 2073 7479 6c65 3d22 7061  ['<div style="pa
-000007f0: 6464 696e 673a 2035 7078 3b62 6163 6b67  dding: 5px;backg
-00000800: 726f 756e 643a 232d 636f 6c6f 725f 7374  round:#-color_st
-00000810: 7269 7065 2d3b 626f 7264 6572 2d72 6164  ripe-;border-rad
-00000820: 6975 733a 3570 783b 223e 272c 0d0a 2020  ius:5px;">',..  
-00000830: 2020 2020 2020 2020 2027 2020 2020 3c73           '    <s
-00000840: 7061 6e3e 2d6b 6579 2d3c 2f73 7061 6e3e  pan>-key-</span>
-00000850: 272c 0d0a 2020 2020 2020 2020 2020 2027  ',..           '
-00000860: 3c2f 6469 763e 275d 0d0a 2020 2020 6b65  </div>']..    ke
-00000870: 795f 7661 6c75 6520 3d20 5b27 3c64 6976  y_value = ['<div
-00000880: 2073 7479 6c65 3d22 626f 7264 6572 2d72   style="border-r
-00000890: 6164 6975 733a 3570 783b 7061 6464 696e  adius:5px;paddin
-000008a0: 673a 3270 783b 6261 636b 6772 6f75 6e64  g:2px;background
-000008b0: 3a20 232d 636f 6c6f 725f 7374 7269 7065  : #-color_stripe
-000008c0: 2d3b 223e 272c 0d0a 2020 2020 2020 2020  -;">',..        
-000008d0: 2020 2020 2020 2020 2027 2020 2020 3c64           '    <d
-000008e0: 6976 2073 7479 6c65 3d22 7769 6474 683a  iv style="width:
-000008f0: 2034 3825 3b64 6973 706c 6179 3a20 696e   48%;display: in
-00000900: 6c69 6e65 2d62 6c6f 636b 3b77 6869 7465  line-block;white
-00000910: 2d73 7061 6365 3a20 6e6f 726d 616c 3b77  -space: normal;w
-00000920: 6f72 642d 7772 6170 3a20 6272 6561 6b2d  ord-wrap: break-
-00000930: 776f 7264 3b22 3e27 2c0d 0a20 2020 2020  word;">',..     
-00000940: 2020 2020 2020 2020 2020 2020 2720 2020              '   
-00000950: 2020 2020 203c 6469 7620 7374 796c 653d       <div style=
-00000960: 2277 6964 7468 3a20 3934 253b 6469 7370  "width: 94%;disp
-00000970: 6c61 793a 2069 6e6c 696e 652d 626c 6f63  lay: inline-bloc
-00000980: 6b3b 7465 7874 2d61 6c69 676e 3a20 7269  k;text-align: ri
-00000990: 6768 743b 223e 272c 0d0a 2020 2020 2020  ght;">',..      
-000009a0: 2020 2020 2020 2020 2020 2027 2020 2020             '    
-000009b0: 2020 2020 2020 2020 3c73 7061 6e3e 2d6b          <span>-k
-000009c0: 6579 2d3c 2f73 7061 6e3e 272c 0d0a 2020  ey-</span>',..  
-000009d0: 2020 2020 2020 2020 2020 2020 2020 2027                 '
-000009e0: 2020 2020 2020 2020 3c2f 6469 763e 272c          </div>',
-000009f0: 0d0a 2020 2020 2020 2020 2020 2020 2020  ..              
-00000a00: 2020 2027 2020 2020 2020 2020 3c64 6976     '        <div
-00000a10: 2073 7479 6c65 3d22 7465 7874 2d61 6c69   style="text-ali
-00000a20: 676e 3a20 6365 6e74 6572 3b77 6964 7468  gn: center;width
-00000a30: 3a20 3130 7078 3b64 6973 706c 6179 3a20  : 10px;display: 
-00000a40: 696e 6c69 6e65 2d62 6c6f 636b 3b66 6c6f  inline-block;flo
-00000a50: 6174 3a20 7269 6768 743b 626f 7264 6572  at: right;border
-00000a60: 2d72 6164 6975 733a 2033 7078 3b62 6163  -radius: 3px;bac
-00000a70: 6b67 726f 756e 643a 2023 2d63 6f6c 6f72  kground: #-color
-00000a80: 5f63 6f6c 6f6e 2d3b 223e 272c 0d0a 2020  _colon-;">',..  
-00000a90: 2020 2020 2020 2020 2020 2020 2020 2027                 '
-00000aa0: 2020 2020 2020 2020 2020 2020 3c73 7061              <spa
-00000ab0: 6e3e 3a3c 2f73 7061 6e3e 272c 0d0a 2020  n>:</span>',..  
-00000ac0: 2020 2020 2020 2020 2020 2020 2020 2027                 '
-00000ad0: 2020 2020 2020 2020 3c2f 6469 763e 272c          </div>',
-00000ae0: 0d0a 2020 2020 2020 2020 2020 2020 2020  ..              
-00000af0: 2020 2027 2020 2020 3c2f 6469 763e 272c     '    </div>',
-00000b00: 0d0a 2020 2020 2020 2020 2020 2020 2020  ..              
-00000b10: 2020 2027 2020 2020 3c64 6976 2073 7479     '    <div sty
-00000b20: 6c65 3d22 7769 6474 683a 2035 3025 3b62  le="width: 50%;b
-00000b30: 6163 6b67 726f 756e 643a 2023 2d63 6f6c  ackground: #-col
-00000b40: 6f72 5f76 616c 7565 2d3b 6469 7370 6c61  or_value-;displa
-00000b50: 793a 2069 6e6c 696e 652d 626c 6f63 6b3b  y: inline-block;
-00000b60: 7768 6974 652d 7370 6163 653a 206e 6f72  white-space: nor
-00000b70: 6d61 6c3b 776f 7264 2d77 7261 703a 2062  mal;word-wrap: b
-00000b80: 7265 616b 2d77 6f72 643b 626f 7264 6572  reak-word;border
-00000b90: 2d72 6164 6975 733a 3570 783b 223e 272c  -radius:5px;">',
-00000ba0: 0d0a 2020 2020 2020 2020 2020 2020 2020  ..              
-00000bb0: 2020 2027 2020 2020 2020 2020 3c64 6976     '        <div
-00000bc0: 2073 7479 6c65 3d22 7061 6464 696e 673a   style="padding:
-00000bd0: 2033 7078 3b22 3e27 2c0d 0a20 2020 2020   3px;">',..     
-00000be0: 2020 2020 2020 2020 2020 2020 2720 2020              '   
-00000bf0: 2020 2020 2020 2020 203c 7370 616e 3e2d           <span>-
-00000c00: 7661 6c75 652d 3c2f 7370 616e 3e27 2c0d  value-</span>',.
-00000c10: 0a20 2020 2020 2020 2020 2020 2020 2020  .               
-00000c20: 2020 2720 2020 2020 2020 203c 2f64 6976    '        </div
-00000c30: 3e27 2c0d 0a20 2020 2020 2020 2020 2020  >',..           
-00000c40: 2020 2020 2020 2720 2020 203c 2f64 6976        '    </div
-00000c50: 3e27 2c0d 0a20 2020 2020 2020 2020 2020  >',..           
-00000c60: 2020 2020 2020 273c 2f64 6976 3e27 5d0d        '</div>'].
-00000c70: 0a20 2020 2073 203d 206f 6e65 2069 6620  .    s = one if 
-00000c80: 7661 6c75 6520 6973 204e 6f6e 6520 656c  value is None el
-00000c90: 7365 206b 6579 5f76 616c 7565 0d0a 2020  se key_value..  
-00000ca0: 2020 7265 7475 726e 206c 6973 7428 6d61    return list(ma
-00000cb0: 7028 6c61 6d62 6461 2078 3a20 782e 7265  p(lambda x: x.re
-00000cc0: 706c 6163 6528 272d 636f 6c6f 725f 7374  place('-color_st
-00000cd0: 7269 7065 2d27 2c20 636f 6c6f 725f 7374  ripe-', color_st
-00000ce0: 7269 7065 290d 0a20 2020 2020 2020 2020  ripe)..         
-00000cf0: 2020 2020 2020 2020 2020 202e 7265 706c             .repl
-00000d00: 6163 6528 272d 6b65 792d 272c 2073 7472  ace('-key-', str
-00000d10: 286b 6579 2929 0d0a 2020 2020 2020 2020  (key))..        
-00000d20: 2020 2020 2020 2020 2020 2020 2e72 6570              .rep
-00000d30: 6c61 6365 2827 2d76 616c 7565 2d27 2c20  lace('-value-', 
-00000d40: 7374 7228 7661 6c75 6529 290d 0a20 2020  str(value))..   
-00000d50: 2020 2020 2020 2020 2020 2020 2020 2020                  
-00000d60: 202e 7265 706c 6163 6528 272d 636f 6c6f   .replace('-colo
-00000d70: 725f 636f 6c6f 6e2d 272c 2063 6f6c 6f72  r_colon-', color
-00000d80: 5f63 6f6c 6f6e 290d 0a20 2020 2020 2020  _colon)..       
-00000d90: 2020 2020 2020 2020 2020 2020 202e 7265               .re
-00000da0: 706c 6163 6528 272d 636f 6c6f 725f 7661  place('-color_va
-00000db0: 6c75 652d 272c 2063 6f6c 6f72 5f76 616c  lue-', color_val
-00000dc0: 7565 292c 2073 2929 0d0a                 ue), s))..
+00000000: 6672 6f6d 2079 706c 6962 2e69 6e64 6578  from yplib.index
+00000010: 2069 6d70 6f72 7420 2a0d 0a23 206d 6169   import *..# mai
+00000020: 6c20 e982 aee4 bbb6 e4b8 ade7 9a84 2068  l ............ h
+00000030: 746d 6c20 e6a8 a1e6 9dbf 0d0a 6465 6620  tml ........def 
+00000040: 6d61 696c 5f68 746d 6c28 626f 6479 3d27  mail_html(body='
+00000050: 7465 7374 2729 3a0d 0a20 2020 2073 203d  test'):..    s =
+00000060: 205b 273c 2144 4f43 5459 5045 2068 746d   ['<!DOCTYPE htm
+00000070: 6c3e 272c 0d0a 2020 2020 2020 2020 2027  l>',..         '
+00000080: 3c68 746d 6c3e 272c 0d0a 2020 2020 2020  <html>',..      
+00000090: 2020 2027 3c68 6561 643e 272c 0d0a 2020     '<head>',..  
+000000a0: 2020 2020 2020 2027 2020 2020 3c6d 6574         '    <met
+000000b0: 6120 6368 6172 7365 743d 2275 7466 2d38  a charset="utf-8
+000000c0: 222f 3e27 2c0d 0a20 2020 2020 2020 2020  "/>',..         
+000000d0: 2720 2020 203c 6d65 7461 2068 7474 702d  '    <meta http-
+000000e0: 6571 7569 763d 2258 2d55 412d 436f 6d70  equiv="X-UA-Comp
+000000f0: 6174 6962 6c65 2220 636f 6e74 656e 743d  atible" content=
+00000100: 2249 453d 6564 6765 2c63 6872 6f6d 653d  "IE=edge,chrome=
+00000110: 3122 3e27 2c0d 0a20 2020 2020 2020 2020  1">',..         
+00000120: 2720 2020 203c 7469 746c 653e 2d74 6974  '    <title>-tit
+00000130: 6c65 2d3c 2f74 6974 6c65 3e27 2c0d 0a20  le-</title>',.. 
+00000140: 2020 2020 2020 2020 273c 2f68 6561 643e          '</head>
+00000150: 272c 0d0a 2020 2020 2020 2020 2027 3c62  ',..         '<b
+00000160: 6f64 793e 272c 0d0a 2020 2020 2020 2020  ody>',..        
+00000170: 2027 2d62 6f64 792d 272c 0d0a 2020 2020   '-body-',..    
+00000180: 2020 2020 2027 3c2f 626f 6479 3e27 2c0d       '</body>',.
+00000190: 0a20 2020 2020 2020 2020 273c 2f68 746d  .         '</htm
+000001a0: 6c3e 275d 0d0a 2020 2020 7265 7475 726e  l>']..    return
+000001b0: 206c 6973 7428 6d61 7028 6c61 6d62 6461   list(map(lambda
+000001c0: 2078 3a20 782e 7265 706c 6163 6528 272d   x: x.replace('-
+000001d0: 7469 746c 652d 272c 2073 7472 2874 6f5f  title-', str(to_
+000001e0: 6461 7465 7469 6d65 2829 2929 2e72 6570  datetime())).rep
+000001f0: 6c61 6365 2827 2d62 6f64 792d 272c 2027  lace('-body-', '
+00000200: 272e 6a6f 696e 2862 6f64 7929 292c 2073  '.join(body)), s
+00000210: 2929 0d0a 0d0a 0d0a 2320 e982 aee4 bbb6  ))......# ......
+00000220: e4b8 ade7 9a84 2074 6974 6c65 20e7 9a84  ...... title ...
+00000230: 6874 6d6c 20e4 bba3 e7a0 810d 0a64 6566  html ........def
+00000240: 206d 6169 6c5f 7469 746c 655f 6874 6d6c   mail_title_html
+00000250: 2874 6974 6c65 3d27 7469 746c 6527 2c20  (title='title', 
+00000260: 626f 6479 3d27 7465 7374 272c 2065 7272  body='test', err
+00000270: 6f72 3d46 616c 7365 293a 0d0a 2020 2020  or=False):..    
+00000280: 636f 6c6f 7220 3d20 2766 3335 3232 3227  color = 'f35222'
+00000290: 2069 6620 6572 726f 7220 656c 7365 2027   if error else '
+000002a0: 3365 6366 3538 270d 0a20 2020 2073 203d  3ecf58'..    s =
+000002b0: 205b 273c 6469 7620 7374 796c 653d 2270   ['<div style="p
+000002c0: 6164 6469 6e67 2d62 6f74 746f 6d3a 2035  adding-bottom: 5
+000002d0: 7078 3b62 6163 6b67 726f 756e 643a 2077  px;background: w
+000002e0: 6869 7465 3b74 6578 742d 616c 6967 6e3a  hite;text-align:
+000002f0: 6365 6e74 6572 3b22 3e27 2c0d 0a20 2020  center;">',..   
+00000300: 2020 2020 2020 2720 2020 203c 6469 7620        '    <div 
+00000310: 7374 796c 653d 2262 6f72 6465 722d 7261  style="border-ra
+00000320: 6469 7573 3a35 7078 3b22 3e27 2c0d 0a20  dius:5px;">',.. 
+00000330: 2020 2020 2020 2020 2720 2020 2020 2020          '       
+00000340: 203c 6469 7620 7374 796c 653d 2270 6164   <div style="pad
+00000350: 6469 6e67 3a20 3570 783b 6261 636b 6772  ding: 5px;backgr
+00000360: 6f75 6e64 3a23 2d63 6f6c 6f72 2d3b 626f  ound:#-color-;bo
+00000370: 7264 6572 2d72 6164 6975 733a 3570 783b  rder-radius:5px;
+00000380: 223e 272c 0d0a 2020 2020 2020 2020 2027  ">',..         '
+00000390: 2020 2020 2020 2020 2020 2020 3c73 7061              <spa
+000003a0: 6e20 7374 796c 653d 2266 6f6e 742d 7369  n style="font-si
+000003b0: 7a65 3a31 3770 783b 223e 2d74 6974 6c65  ze:17px;">-title
+000003c0: 2d3c 2f73 7061 6e3e 272c 0d0a 2020 2020  -</span>',..    
+000003d0: 2020 2020 2027 2020 2020 2020 2020 3c2f       '        </
+000003e0: 6469 763e 272c 0d0a 2020 2020 2020 2020  div>',..        
+000003f0: 2027 2020 2020 2020 2020 3c64 6976 2073   '        <div s
+00000400: 7479 6c65 3d22 666f 6e74 2d73 697a 653a  tyle="font-size:
+00000410: 3133 7078 3b74 6578 742d 616c 6967 6e3a  13px;text-align:
+00000420: 6365 6e74 6572 3b62 6f72 6465 722d 7261  center;border-ra
+00000430: 6469 7573 3a35 7078 3b22 3e27 2c0d 0a20  dius:5px;">',.. 
+00000440: 2020 2020 2020 2020 2720 2020 2020 2020          '       
+00000450: 2020 2020 202d 626f 6479 2d27 2c0d 0a20       -body-',.. 
+00000460: 2020 2020 2020 2020 2720 2020 2020 2020          '       
+00000470: 203c 2f64 6976 3e27 2c0d 0a20 2020 2020   </div>',..     
+00000480: 2020 2020 2720 2020 203c 2f64 6976 3e27      '    </div>'
+00000490: 2c0d 0a20 2020 2020 2020 2020 273c 2f64  ,..         '</d
+000004a0: 6976 3e27 5d0d 0a20 2020 2072 6574 7572  iv>']..    retur
+000004b0: 6e20 6c69 7374 286d 6170 286c 616d 6264  n list(map(lambd
+000004c0: 6120 783a 2078 2e72 6570 6c61 6365 2827  a x: x.replace('
+000004d0: 2d74 6974 6c65 2d27 2c20 7469 746c 6529  -title-', title)
+000004e0: 2e72 6570 6c61 6365 2827 2d62 6f64 792d  .replace('-body-
+000004f0: 272c 2027 272e 6a6f 696e 2862 6f64 7929  ', ''.join(body)
+00000500: 292e 7265 706c 6163 6528 272d 636f 6c6f  ).replace('-colo
+00000510: 722d 272c 2063 6f6c 6f72 292c 2073 2929  r-', color), s))
+00000520: 0d0a 0d0a 0d0a 2320 e982 aee4 bbb6 e4b8  ......# ........
+00000530: ade7 9a84 2063 6f6e 7465 6e74 20e7 9a84  .... content ...
+00000540: 6874 6d6c 20e4 bba3 e7a0 810d 0a64 6566  html ........def
+00000550: 206d 6169 6c5f 636f 6e74 656e 745f 6874   mail_content_ht
+00000560: 6d6c 286b 6579 3d4e 6f6e 652c 2076 616c  ml(key=None, val
+00000570: 7565 3d4e 6f6e 652c 2065 7272 6f72 3d46  ue=None, error=F
+00000580: 616c 7365 2c20 7374 7269 7065 3d46 616c  alse, stripe=Fal
+00000590: 7365 293a 0d0a 2020 2020 636f 6c6f 725f  se):..    color_
+000005a0: 6e6f 726d 616c 5f31 203d 2027 6265 6539  normal_1 = 'bee9
+000005b0: 6336 270d 0a20 2020 2063 6f6c 6f72 5f6e  c6'..    color_n
+000005c0: 6f72 6d61 6c5f 3220 3d20 2763 6266 3964  ormal_2 = 'cbf9d
+000005d0: 3327 0d0a 2020 2020 636f 6c6f 725f 6e6f  3'..    color_no
+000005e0: 726d 616c 5f63 6f6c 6f6e 203d 2027 6633  rmal_colon = 'f3
+000005f0: 6534 6534 270d 0a20 2020 2063 6f6c 6f72  e4e4'..    color
+00000600: 5f6e 6f72 6d61 6c5f 7661 6c75 6520 3d20  _normal_value = 
+00000610: 2739 6265 6461 3927 0d0a 0d0a 2020 2020  '9beda9'....    
+00000620: 636f 6c6f 725f 6572 726f 725f 3120 3d20  color_error_1 = 
+00000630: 2765 3962 3339 3427 0d0a 2020 2020 636f  'e9b394'..    co
+00000640: 6c6f 725f 6572 726f 725f 3220 3d20 2765  lor_error_2 = 'e
+00000650: 3762 3864 3627 0d0a 2020 2020 636f 6c6f  7b8d6'..    colo
+00000660: 725f 6572 726f 725f 636f 6c6f 6e20 3d20  r_error_colon = 
+00000670: 2765 3938 6338 6327 0d0a 2020 2020 636f  'e98c8c'..    co
+00000680: 6c6f 725f 6572 726f 725f 7661 6c75 6520  lor_error_value 
+00000690: 3d20 2765 6439 3062 6227 0d0a 2020 2020  = 'ed90bb'..    
+000006a0: 6966 2065 7272 6f72 3a0d 0a20 2020 2020  if error:..     
+000006b0: 2020 2063 6f6c 6f72 5f73 7472 6970 6520     color_stripe 
+000006c0: 3d20 636f 6c6f 725f 6572 726f 725f 3120  = color_error_1 
+000006d0: 6966 2073 7472 6970 6520 656c 7365 2063  if stripe else c
+000006e0: 6f6c 6f72 5f65 7272 6f72 5f32 0d0a 2020  olor_error_2..  
+000006f0: 2020 2020 2020 636f 6c6f 725f 636f 6c6f        color_colo
+00000700: 6e20 3d20 636f 6c6f 725f 6572 726f 725f  n = color_error_
+00000710: 636f 6c6f 6e0d 0a20 2020 2020 2020 2063  colon..        c
+00000720: 6f6c 6f72 5f76 616c 7565 203d 2063 6f6c  olor_value = col
+00000730: 6f72 5f65 7272 6f72 5f76 616c 7565 0d0a  or_error_value..
+00000740: 2020 2020 656c 7365 3a0d 0a20 2020 2020      else:..     
+00000750: 2020 2063 6f6c 6f72 5f73 7472 6970 6520     color_stripe 
+00000760: 3d20 636f 6c6f 725f 6e6f 726d 616c 5f31  = color_normal_1
+00000770: 2069 6620 7374 7269 7065 2065 6c73 6520   if stripe else 
+00000780: 636f 6c6f 725f 6e6f 726d 616c 5f32 0d0a  color_normal_2..
+00000790: 2020 2020 2020 2020 636f 6c6f 725f 636f          color_co
+000007a0: 6c6f 6e20 3d20 636f 6c6f 725f 6e6f 726d  lon = color_norm
+000007b0: 616c 5f63 6f6c 6f6e 0d0a 2020 2020 2020  al_colon..      
+000007c0: 2020 636f 6c6f 725f 7661 6c75 6520 3d20    color_value = 
+000007d0: 636f 6c6f 725f 6e6f 726d 616c 5f76 616c  color_normal_val
+000007e0: 7565 0d0a 0d0a 2020 2020 6f6e 6520 3d20  ue....    one = 
+000007f0: 5b27 3c64 6976 2073 7479 6c65 3d22 7061  ['<div style="pa
+00000800: 6464 696e 673a 2035 7078 3b62 6163 6b67  dding: 5px;backg
+00000810: 726f 756e 643a 232d 636f 6c6f 725f 7374  round:#-color_st
+00000820: 7269 7065 2d3b 626f 7264 6572 2d72 6164  ripe-;border-rad
+00000830: 6975 733a 3570 783b 223e 272c 0d0a 2020  ius:5px;">',..  
+00000840: 2020 2020 2020 2020 2027 2020 2020 3c73           '    <s
+00000850: 7061 6e3e 2d6b 6579 2d3c 2f73 7061 6e3e  pan>-key-</span>
+00000860: 272c 0d0a 2020 2020 2020 2020 2020 2027  ',..           '
+00000870: 3c2f 6469 763e 275d 0d0a 2020 2020 6b65  </div>']..    ke
+00000880: 795f 7661 6c75 6520 3d20 5b27 3c64 6976  y_value = ['<div
+00000890: 2073 7479 6c65 3d22 626f 7264 6572 2d72   style="border-r
+000008a0: 6164 6975 733a 3570 783b 7061 6464 696e  adius:5px;paddin
+000008b0: 673a 3270 783b 6261 636b 6772 6f75 6e64  g:2px;background
+000008c0: 3a20 232d 636f 6c6f 725f 7374 7269 7065  : #-color_stripe
+000008d0: 2d3b 223e 272c 0d0a 2020 2020 2020 2020  -;">',..        
+000008e0: 2020 2020 2020 2020 2027 2020 2020 3c64           '    <d
+000008f0: 6976 2073 7479 6c65 3d22 7769 6474 683a  iv style="width:
+00000900: 2034 3825 3b64 6973 706c 6179 3a20 696e   48%;display: in
+00000910: 6c69 6e65 2d62 6c6f 636b 3b77 6869 7465  line-block;white
+00000920: 2d73 7061 6365 3a20 6e6f 726d 616c 3b77  -space: normal;w
+00000930: 6f72 642d 7772 6170 3a20 6272 6561 6b2d  ord-wrap: break-
+00000940: 776f 7264 3b22 3e27 2c0d 0a20 2020 2020  word;">',..     
+00000950: 2020 2020 2020 2020 2020 2020 2720 2020              '   
+00000960: 2020 2020 203c 6469 7620 7374 796c 653d       <div style=
+00000970: 2277 6964 7468 3a20 3934 253b 6469 7370  "width: 94%;disp
+00000980: 6c61 793a 2069 6e6c 696e 652d 626c 6f63  lay: inline-bloc
+00000990: 6b3b 7465 7874 2d61 6c69 676e 3a20 7269  k;text-align: ri
+000009a0: 6768 743b 223e 272c 0d0a 2020 2020 2020  ght;">',..      
+000009b0: 2020 2020 2020 2020 2020 2027 2020 2020             '    
+000009c0: 2020 2020 2020 2020 3c73 7061 6e3e 2d6b          <span>-k
+000009d0: 6579 2d3c 2f73 7061 6e3e 272c 0d0a 2020  ey-</span>',..  
+000009e0: 2020 2020 2020 2020 2020 2020 2020 2027                 '
+000009f0: 2020 2020 2020 2020 3c2f 6469 763e 272c          </div>',
+00000a00: 0d0a 2020 2020 2020 2020 2020 2020 2020  ..              
+00000a10: 2020 2027 2020 2020 2020 2020 3c64 6976     '        <div
+00000a20: 2073 7479 6c65 3d22 7465 7874 2d61 6c69   style="text-ali
+00000a30: 676e 3a20 6365 6e74 6572 3b77 6964 7468  gn: center;width
+00000a40: 3a20 3130 7078 3b64 6973 706c 6179 3a20  : 10px;display: 
+00000a50: 696e 6c69 6e65 2d62 6c6f 636b 3b66 6c6f  inline-block;flo
+00000a60: 6174 3a20 7269 6768 743b 626f 7264 6572  at: right;border
+00000a70: 2d72 6164 6975 733a 2033 7078 3b62 6163  -radius: 3px;bac
+00000a80: 6b67 726f 756e 643a 2023 2d63 6f6c 6f72  kground: #-color
+00000a90: 5f63 6f6c 6f6e 2d3b 223e 272c 0d0a 2020  _colon-;">',..  
+00000aa0: 2020 2020 2020 2020 2020 2020 2020 2027                 '
+00000ab0: 2020 2020 2020 2020 2020 2020 3c73 7061              <spa
+00000ac0: 6e3e 3a3c 2f73 7061 6e3e 272c 0d0a 2020  n>:</span>',..  
+00000ad0: 2020 2020 2020 2020 2020 2020 2020 2027                 '
+00000ae0: 2020 2020 2020 2020 3c2f 6469 763e 272c          </div>',
+00000af0: 0d0a 2020 2020 2020 2020 2020 2020 2020  ..              
+00000b00: 2020 2027 2020 2020 3c2f 6469 763e 272c     '    </div>',
+00000b10: 0d0a 2020 2020 2020 2020 2020 2020 2020  ..              
+00000b20: 2020 2027 2020 2020 3c64 6976 2073 7479     '    <div sty
+00000b30: 6c65 3d22 7769 6474 683a 2035 3025 3b62  le="width: 50%;b
+00000b40: 6163 6b67 726f 756e 643a 2023 2d63 6f6c  ackground: #-col
+00000b50: 6f72 5f76 616c 7565 2d3b 6469 7370 6c61  or_value-;displa
+00000b60: 793a 2069 6e6c 696e 652d 626c 6f63 6b3b  y: inline-block;
+00000b70: 7768 6974 652d 7370 6163 653a 206e 6f72  white-space: nor
+00000b80: 6d61 6c3b 776f 7264 2d77 7261 703a 2062  mal;word-wrap: b
+00000b90: 7265 616b 2d77 6f72 643b 626f 7264 6572  reak-word;border
+00000ba0: 2d72 6164 6975 733a 3570 783b 223e 272c  -radius:5px;">',
+00000bb0: 0d0a 2020 2020 2020 2020 2020 2020 2020  ..              
+00000bc0: 2020 2027 2020 2020 2020 2020 3c64 6976     '        <div
+00000bd0: 2073 7479 6c65 3d22 7061 6464 696e 673a   style="padding:
+00000be0: 2033 7078 3b22 3e27 2c0d 0a20 2020 2020   3px;">',..     
+00000bf0: 2020 2020 2020 2020 2020 2020 2720 2020              '   
+00000c00: 2020 2020 2020 2020 203c 7370 616e 3e2d           <span>-
+00000c10: 7661 6c75 652d 3c2f 7370 616e 3e27 2c0d  value-</span>',.
+00000c20: 0a20 2020 2020 2020 2020 2020 2020 2020  .               
+00000c30: 2020 2720 2020 2020 2020 203c 2f64 6976    '        </div
+00000c40: 3e27 2c0d 0a20 2020 2020 2020 2020 2020  >',..           
+00000c50: 2020 2020 2020 2720 2020 203c 2f64 6976        '    </div
+00000c60: 3e27 2c0d 0a20 2020 2020 2020 2020 2020  >',..           
+00000c70: 2020 2020 2020 273c 2f64 6976 3e27 5d0d        '</div>'].
+00000c80: 0a20 2020 2073 203d 206f 6e65 2069 6620  .    s = one if 
+00000c90: 7661 6c75 6520 6973 204e 6f6e 6520 656c  value is None el
+00000ca0: 7365 206b 6579 5f76 616c 7565 0d0a 2020  se key_value..  
+00000cb0: 2020 7265 7475 726e 206c 6973 7428 6d61    return list(ma
+00000cc0: 7028 6c61 6d62 6461 2078 3a20 782e 7265  p(lambda x: x.re
+00000cd0: 706c 6163 6528 272d 636f 6c6f 725f 7374  place('-color_st
+00000ce0: 7269 7065 2d27 2c20 636f 6c6f 725f 7374  ripe-', color_st
+00000cf0: 7269 7065 290d 0a20 2020 2020 2020 2020  ripe)..         
+00000d00: 2020 2020 2020 2020 2020 202e 7265 706c             .repl
+00000d10: 6163 6528 272d 6b65 792d 272c 2073 7472  ace('-key-', str
+00000d20: 286b 6579 2929 0d0a 2020 2020 2020 2020  (key))..        
+00000d30: 2020 2020 2020 2020 2020 2020 2e72 6570              .rep
+00000d40: 6c61 6365 2827 2d76 616c 7565 2d27 2c20  lace('-value-', 
+00000d50: 7374 7228 7661 6c75 6529 290d 0a20 2020  str(value))..   
+00000d60: 2020 2020 2020 2020 2020 2020 2020 2020                  
+00000d70: 202e 7265 706c 6163 6528 272d 636f 6c6f   .replace('-colo
+00000d80: 725f 636f 6c6f 6e2d 272c 2063 6f6c 6f72  r_colon-', color
+00000d90: 5f63 6f6c 6f6e 290d 0a20 2020 2020 2020  _colon)..       
+00000da0: 2020 2020 2020 2020 2020 2020 202e 7265               .re
+00000db0: 706c 6163 6528 272d 636f 6c6f 725f 7661  place('-color_va
+00000dc0: 6c75 652d 272c 2063 6f6c 6f72 5f76 616c  lue-', color_val
+00000dd0: 7565 292c 2073 2929 0d0a                 ue), s))..
```


# Comparing `tmp/general_calculator_zsd-1.2.0.tar.gz` & `tmp/general_calculator_zsd-1.2.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "general_calculator_zsd-1.2.0.tar", last modified: Thu Jun  1 09:11:42 2023, max compression
+gzip compressed data, was "general_calculator_zsd-1.2.1.tar", last modified: Wed Jun 28 03:34:24 2023, max compression
```

## Comparing `general_calculator_zsd-1.2.0.tar` & `general_calculator_zsd-1.2.1.tar`

### file list

```diff
@@ -1,15 +1,15 @@
-drwxrwxrwx   0        0        0        0 2023-06-01 09:11:42.354030 general_calculator_zsd-1.2.0/
--rw-rw-rw-   0        0        0     1089 2022-11-17 02:56:12.000000 general_calculator_zsd-1.2.0/LICENSE
--rw-rw-rw-   0        0        0      418 2023-06-01 09:11:42.338411 general_calculator_zsd-1.2.0/PKG-INFO
--rw-rw-rw-   0        0        0      314 2023-03-30 02:25:01.000000 general_calculator_zsd-1.2.0/README.md
-drwxrwxrwx   0        0        0        0 2023-06-01 09:11:42.275925 general_calculator_zsd-1.2.0/general_calculator_zsd/
--rw-rw-rw-   0        0        0        0 2022-11-16 09:26:23.000000 general_calculator_zsd-1.2.0/general_calculator_zsd/__init__.py
--rw-rw-rw-   0        0        0    48475 2023-06-01 05:36:17.000000 general_calculator_zsd-1.2.0/general_calculator_zsd/general_calculator.py
--rw-rw-rw-   0        0        0    65572 2023-06-01 05:20:50.000000 general_calculator_zsd-1.2.0/general_calculator_zsd/mysql_transmit_data4all.py
-drwxrwxrwx   0        0        0        0 2023-06-01 09:11:42.338411 general_calculator_zsd-1.2.0/general_calculator_zsd.egg-info/
--rw-rw-rw-   0        0        0      418 2023-06-01 09:11:41.000000 general_calculator_zsd-1.2.0/general_calculator_zsd.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      340 2023-06-01 09:11:41.000000 general_calculator_zsd-1.2.0/general_calculator_zsd.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-01 09:11:41.000000 general_calculator_zsd-1.2.0/general_calculator_zsd.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       23 2023-06-01 09:11:41.000000 general_calculator_zsd-1.2.0/general_calculator_zsd.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       42 2023-06-01 09:11:42.354030 general_calculator_zsd-1.2.0/setup.cfg
--rw-rw-rw-   0        0        0      531 2023-06-01 09:10:40.000000 general_calculator_zsd-1.2.0/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:34:24.158194 general_calculator_zsd-1.2.1/
+-rw-rw-rw-   0        0        0     1089 2022-11-17 02:56:12.000000 general_calculator_zsd-1.2.1/LICENSE
+-rw-rw-rw-   0        0        0      418 2023-06-28 03:34:24.157195 general_calculator_zsd-1.2.1/PKG-INFO
+-rw-rw-rw-   0        0        0      314 2023-03-30 02:25:01.000000 general_calculator_zsd-1.2.1/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 03:34:24.116483 general_calculator_zsd-1.2.1/general_calculator_zsd/
+-rw-rw-rw-   0        0        0        0 2022-11-16 09:26:23.000000 general_calculator_zsd-1.2.1/general_calculator_zsd/__init__.py
+-rw-rw-rw-   0        0        0    49969 2023-06-28 03:31:22.000000 general_calculator_zsd-1.2.1/general_calculator_zsd/general_calculator.py
+-rw-rw-rw-   0        0        0    67692 2023-06-28 03:25:53.000000 general_calculator_zsd-1.2.1/general_calculator_zsd/mysql_transmit_data4all.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:34:24.154198 general_calculator_zsd-1.2.1/general_calculator_zsd.egg-info/
+-rw-rw-rw-   0        0        0      418 2023-06-28 03:34:23.000000 general_calculator_zsd-1.2.1/general_calculator_zsd.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      340 2023-06-28 03:34:23.000000 general_calculator_zsd-1.2.1/general_calculator_zsd.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 03:34:23.000000 general_calculator_zsd-1.2.1/general_calculator_zsd.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       23 2023-06-28 03:34:23.000000 general_calculator_zsd-1.2.1/general_calculator_zsd.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 03:34:24.158194 general_calculator_zsd-1.2.1/setup.cfg
+-rw-rw-rw-   0        0        0      531 2023-06-28 03:31:55.000000 general_calculator_zsd-1.2.1/setup.py
```

### Comparing `general_calculator_zsd-1.2.0/LICENSE` & `general_calculator_zsd-1.2.1/LICENSE`

 * *Files identical despite different names*

### Comparing `general_calculator_zsd-1.2.0/general_calculator_zsd/general_calculator.py` & `general_calculator_zsd-1.2.1/general_calculator_zsd/general_calculator.py`

 * *Files 17% similar despite different names*

```diff
@@ -24,33 +24,50 @@
 from selenium import webdriver
 from selenium.webdriver.common.action_chains import ActionChains
 from selenium.webdriver.common.keys import Keys
 import pickle
 from textrank4zh import TextRank4Keyword
 import cpca
 
-# 读取json文件变成字典
-def read_json(json_file):
+
+# 文件读取
+#########################################################################
+
+# 功能：读取json文件变成字典格式
+# 输入：json_file - json文件的路径 - str
+# 输出：data_dict - json文件转化成的字典 - dict
+def read_json(json_file:str):
     with open(json_file, 'r', encoding='utf-8') as load_f:
-        data = json.load(load_f)
-    return data
+        data_dict = json.load(load_f)
+    return data_dict
 
 
-# --------------------------------------------------------------------------
-# 1.时间处理的模块
+# 时间处理的模块
+#########################################################################
 
-# 获取当前时间，返回字符串，精确到秒（时间戳格式）
+# 功能：获取当前时间，返回yyyymmss格式的时间字符串
+# 输入：-
+# 输出：time_out - yyyymmss格式的时间字符串 - str
 def get_time_now():
-    return time.strftime('%Y%m%d%H%M%S', time.localtime(time.time()))
+    time_out = time.strftime('%Y%m%d%H%M%S', time.localtime(time.time()))
+    return time_out
 
+# 功能：获取当前时间，返回 %Y-%m-%d %H:%M:%S 格式的时间字符串
+# 输入：-
+# 输出：datetime_out - %Y-%m-%d %H:%M:%S格式的时间字符串 - str
 def get_datetime_now():
-    return datetime.datetime.now().strftime('%Y-%m-%d %H:%M:%S')
+    datetime_out = datetime.datetime.now().strftime('%Y-%m-%d %H:%M:%S')
+    return datetime_out
 
-# 比较yyyy-mm-dd时间字符串的大小
-def compare_time_v1(time1, time2, identifier):
+# 功能：比较"yyyy-mm-dd"格式时间字符串的大小
+# 输入：time1 - 时间1 - str，如'2022-01-01'
+#      time2 - 时间2 - str，如'2022-01-01'
+#      identifier - 比较符，可选5种：大于（>)、大于等于（>=）、等于（=）、小于等于（<=）、小于（<） - str
+# 输出：True/False - 比较结果 - bool
+def compare_time_v1(time1:str, time2:str, identifier:str):
     s_time = time.mktime(time.strptime(time1, '%Y-%m-%d'))
     e_time = time.mktime(time.strptime(time2, '%Y-%m-%d'))
     if identifier == '>':
         if int(s_time) - int(e_time) > 0:
             return True
         else:
             return False
@@ -71,17 +88,20 @@
             return False
     if identifier == '=':
         if int(s_time) - int(e_time) == 0:
             return True
         else:
             return False
 
-
-# 比较yyyy-mm-dd hh:mm:ss时间字符串的大小
-def compare_time_v2(time1, time2, identifier):
+# 功能：比较"yyyy-mm-dd hh:mm:ss"格式时间字符串的大小
+# 输入：time1 - 时间1 - str，如'2022-01-01 00:00:00'
+#      time2 - 时间2 - str，如'2022-01-01 00:00:00'
+#      identifier - 比较符，可选5种：大于（>)、大于等于（>=）、等于（=）、小于等于（<=）、小于（<） - str
+# 输出：True/False - 比较结果 - bool
+def compare_time_v2(time1:str, time2:str, identifier:str):
     s_time = time.mktime(time.strptime(time1, '%Y-%m-%d %H:%M:%S'))
     e_time = time.mktime(time.strptime(time2, '%Y-%m-%d %H:%M:%S'))
     if identifier == '>':
         if int(s_time) - int(e_time) > 0:
             return True
         else:
             return False
@@ -102,33 +122,45 @@
             return False
     if identifier == '=':
         if int(s_time) - int(e_time) == 0:
             return True
         else:
             return False
 
-# 将时间戳字符串转化为时间格式
-def stamp2date(stamp_string):
+# 功能：将自epoch以来经过的秒数字符串转化为"yyyy-mm-dd hh:mm:ss"格式
+# 输入：stamp_string - 自epoch以来经过的秒数字符串 - str，如'1545925769'
+# 输出：date_time - "yyyy-mm-dd hh:mm:ss"格式的时间字符串 - str
+def stamp2date(stamp_string:str):
     time_array = time.localtime(int(stamp_string))
     date_time = time.strftime("%Y-%m-%d %H:%M:%S", time_array)
     return date_time
 
-# 随机sleep n - m 秒，k表示小数点后k位
-def sleep_some_seconds(m, n, k):
+# 功能：随机sleep n - m 秒，k表示小数点后k位的时间
+# 输入：m - 最短时间 - int
+#      n - 最长时间 - int
+#      k - 小数点后k位 - int
+# 输出：True - 表示完成 - bool
+def sleep_some_seconds(m:int, n:int, k:int):
     time.sleep(round(random.uniform(m, n), k))
     return True
 
-def change2date(sec, date_format):
+# 功能：计算sec（秒数）与当前时间的时间间隔，并且输出指定格式的字符串形式
+# 输入：sec - 最短时间 - int/str
+#      date_format - 指定的输出格式 - str
+# 输出：time_gap - 指定格式的时间间隔 - str
+def change2date(sec, date_format:str):
     sec = int(sec)
-    t = time.time() - sec
-    t = time.strftime(date_format, time.localtime(t))
-    return t
-
-# 将n天前/n小时前/n周前转化为 %Y-%m-%d %H:%M:%S 格式
-def before2datetime(before):
+    time_gap = time.time() - sec
+    time_gap = time.strftime(date_format, time.localtime(time_gap))
+    return time_gap
+
+# 功能：将n天前/n小时前/n周前转化为%Y-%m-%d %H:%M:%S的字符串格式
+# 输入：before - 时间表达形式 - str
+# 输出：datetime_str - 格式化的时间字符串 - str
+def before2datetime(before:str):
     before_str = re.findall(r"(\d{4}-\d{1,2}-\d{1,2}\s\d{1,2}:\d{1,2}:\d{1,2})", before)
     if before_str != []:
         datetime_str = before_str[0]
     else:
         if '前天' in before:
             sec = 2 * 86400
             datetime_str = change2date(sec, date_format='%Y-%m-%d %H:%M:%S')
@@ -148,32 +180,42 @@
             a = re.findall('(.*?)分钟前', before)
             sec = int(a[0]) * 60
             datetime_str = change2date(sec, date_format='%Y-%m-%d %H:%M:%S')
         elif '秒钟前' in before:
             a = re.findall('(.*?)秒钟前', before)
             sec = int(a[0])
             datetime_str = change2date(sec, date_format='%Y-%m-%d %H:%M:%S')
+        elif '刚刚' in before:
+            sec = 0
+            datetime_str = change2date(sec, date_format='%Y-%m-%d %H:%M:%S')
         else:
             print('意外的时间表达方式！！！！！！return当前时间')
             sec = 0
             datetime_str = change2date(sec, date_format='%Y-%m-%d %H:%M:%S')
     return datetime_str
 
-def split_yyyymmdd(text):
+# 功能：将yyyymmdd-yyyymmdd格式的字符串拆分，并转化为前后两个时间的起始及结束datetime
+# 输入：text - 两个时间的表达形式，yyyymmdd-yyyymmdd - str
+# 输出：True/False - 若输入不符合格式要求，则直接返回False - bool
+#      start_dt - 起始的dateframe字符串
+#      end_dt - 结束的dateframe字符串
+def split_yyyymmdd(text:str):
     date_list = text.split('-')
     start_text = date_list[0]
     end_text = date_list[1]
     if len(date_list) != 2 or len(start_text) != 8 or len(end_text) != 8 or int(start_text) > int(end_text):
         return False, '', ''
     else:
         start_dt = start_text[:4]+'-'+start_text[4:6]+'-'+start_text[6:8]+' 00:00:00'
         end_dt = end_text[:4] + '-' + end_text[4:6] + '-' + end_text[6:8] + ' 23:59:59'
         return True, start_dt, end_dt
 
-# 计算今天是周几
+# 功能：根据当前时间，反馈现在是周几
+# 输入：-
+# 输出：weekday - 周几 - str
 def get_day_of_week():
     day_of_week = datetime.datetime.now().weekday() + 1
     if day_of_week == 1:
         weekday = '周一'
     elif day_of_week == 2:
         weekday = '周二'
     elif day_of_week == 3:
@@ -184,105 +226,33 @@
         weekday = '周五'
     elif day_of_week == 6:
         weekday = '周六'
     else:
         weekday = '周日'
     return weekday
 
-#根据输入的date格式，得到n_day前的date
-def get_date_before(date_now, n_day):
+# 功能：根据输入的date格式，得到n_day前的date格式日期
+# 输入：date_start - 起始的日期 - datetime.date
+#      n_day - n天前 - int
+# 输出：date_before - n_day天之前的date - datetime.date
+def get_date_before(date_start, n_day):
     days = datetime.timedelta(days=n_day)
-    date_before = date_now - days
+    date_before = date_start - days
     return date_before
 
-# --------------------------------------------------------------------------
-# 2.字体处理的模块
-
-# 比较两个列表的坐标信息是否相同，位置是否接近
-def cor_compare(l1, l2):
-    if len(l1) != len(l2):
-        return False
-    else:
-        mark = True
-        # 一个字的所有坐标中，有一个与base存在大于40的差异，就退出比较
-        for idx in range(len(l1)):
-            if abs(l1[idx][0] - l2[idx][0]) < 40 and abs(l1[idx][1] - l2[idx][1]) < 40:
-                pass
-            else:
-                mark = False
-                break
-        return mark
-
-
-# 根据font基准寻找新的word_list
-def find_new_word_list(font_base, word_list_base, font_new):
-    # 手动确定一组编码和字符的对应关系
-    uni_list = font_base['cmap'].tables[0].ttFont.getGlyphOrder()[1:]
-
-    # 获取38个字符的（x,y）信息
-    cor_base_all = []
-    for uni in uni_list:
-        p1 = []  # 保存一个字符的(x,y)信息
-        p = font_base['glyf'][uni].coordinates  # 获取对象的x,y信息，返回的是一个GlyphCoordinates对象，可以当作列表操作，每个元素是（x,y）元组
-        for f in p:  # 把GlyphCoordinates对象改成一个列表
-            p1.append(f)
-        cor_base_all.append(p1)
-
-    uni_list_new = font_new.getGlyphOrder()[1:]
-    cor_list_new = []
-    ss = []
-    for i in uni_list_new:
-        pp1 = []
-        p = font_new['glyf'][i].coordinates
-        for f in p:
-            pp1.append(f)
-        cor_list_new.append(pp1)
-
-    word_list_new = []
-    for cor_new in cor_list_new:
-        idx_new = 0
-        for cor_base in cor_base_all:
-            idx_new += 1
-            if cor_compare(cor_base, cor_new):
-                word_list_new.append(word_list_base[idx_new - 1])
-
-    return word_list_new
+# 爬虫代理的模块
+#########################################################################
 
-
-# --------------------------------------------------------------------------
-# 3.爬虫代理的模块
-
-# 随机获取user-agent
-# def get_fake_header(cookies):
-#     header = {}
-#     ua_object = UserAgent(path='user_agent_fix.json')
-#     user_agent = ua_object.random
-#     header['User-Agent'] = user_agent
-#     header['Cookie'] = cookies[0]  # 之后会扩充cookie的获取方式
-#     return header
-
-# 随机获取user-agent，读取最新的cookie
-# def get_fake_header(cookies, task):
-#     if task == 'weibo':
-#         cookies_path = f'../cookie_{task}.txt'
-#     else:
-#         cookies_path = f'cookie_{task}.txt'
-#     with open(cookies_path, 'r') as f:  # 打开文件
-#         lines = f.readlines()  # 读取所有行
-#         print(lines[-1])
-#         last_line = lines[-1].replace('\n', '')[20:]
-#     header = {}
-#     ua_object = UserAgent()
-#     user_agent = ua_object.random
-#     header['User-Agent'] = user_agent
-#     header['Cookie'] = last_line
-#     # header['Cookie'] = cookies[0]
-#     return header
-
-def get_fake_header(task, creator, db_config, connect):
+# 功能：根据task和creator，找到task对应平台的最新cookie和useragent，最终输出一个header
+# 输入：task - 任务名，包括autohome/weibo/bilibili等 - str
+#      creator - 任务创建人，与cookie记录相一致 - str
+#      db_config - 数据库config信息 - dict
+#      connect - 数据库名 - str
+# 输出：header - 生成的header - dict
+def get_fake_header(task:str, creator:str, db_config:dict, connect:str):
     cursor, conn = get_cursor_times(db_config[connect], 10)
     sql = f'''
         SELECT cookie
         FROM log_cookies_info a
         where cookie_datetime = (select max(cookie_datetime) from log_cookies_info where task_name = '{task}' and cookie_owner = '{creator}') 
         and task_name = '{task}' and cookie_owner = '{creator}'
         '''
@@ -290,49 +260,30 @@
     results = cursor.fetchall()
     cookie = results[0][0]
     header = {}
     ua_object = UserAgent(path='user_agent_fix.json')
     user_agent = ua_object.random
     header['User-Agent'] = user_agent
     header['Cookie'] = cookie
-    # print('header获取成功！！！！！')
     return header
 
-# 获取代理ip，并验证可用性
-# def get_fake_proxy(user_agent, cookie):
-#     url = "http://ip.memories1999.com/api.php?dh=1393428387670776856&sl=500"  # 代理IP获取地址
-#     header4proxy = {
-#         "User-Agent": user_agent
-#     }
-#     proxy_list = requests.get(url, headers=header4proxy)
-#     if proxy_list.status_code == 200:
-#         lines = proxy_list.text.replace("\r", "").split('\n')
-#
-#     test_url = 'https://www.autohome.com.cn/'
-#     header = {"User-Agent": user_agent, "cookie": cookie}
-#     ip = lines[0]
-#     proxy = {'http': ip, 'https': ip}
-#     try:
-#         r = requests.get(test_url, headers=header, proxies=proxy, timeout=20)
-#         if r.status_code == 200:
-#             return ip
-#     except:
-#         return 'error'
-
-def get_proxy(proxy_info):
+# 功能：解析代理proxy的信息
+# 输入：proxy_info - 代理信息 - dict
+# 输出：proxy_out - 代理地址字典 - dict
+def get_proxy(proxy_info:dict):
     proxy = 'http://{}:{}@{}:{}'.format(proxy_info['key'], proxy_info['passwd'], proxy_info['host'], proxy_info['port'])
     #return {"http": proxy, "https": proxy}
-    return {"http": proxy}
+    proxy_out = {"http": proxy}
+    return proxy_out
 
 # 动态隧道转发。返回response
 def get_resp_by_proxy(url, timeout, headers, proxies, params=None, verify=True, try_cnt=20):
     try:
         resp = req.get(url, timeout=timeout, headers=headers, proxies=proxies, params=params, verify=verify)
     except:
-        # print('ip代理失败，使用smart自有ip~~~')
         print(url)
         try_cnt -= 1
         print(f'ip代理失败，开启第{try_cnt}次调用！')
         sleep_some_seconds(1, 2, 1)
         # resp = req.get(url, timeout=timeout, headers=headers, params=params)
         if try_cnt > 0:
             resp = get_resp_by_proxy(url, timeout, headers, proxies, params=params, verify=verify, try_cnt=try_cnt)
@@ -1338,8 +1289,60 @@
         emo_pn = 0
     return final_sen, emo_pn
 
 def keywords_extraction(text, keyword_cnt):
     tr4w = TextRank4Keyword()
     tr4w.analyze(text=text, lower=True)
     keywords = tr4w.get_keywords(num=keyword_cnt, word_min_len=1)
-    return keywords
+    return keywords
+
+# 字体处理的模块
+#########################################################################
+
+# 功能：比较两个列表的坐标信息是否相同，位置是否接近。汽车之家专用。
+def cor_compare(l1, l2):
+    if len(l1) != len(l2):
+        return False
+    else:
+        mark = True
+        # 一个字的所有坐标中，有一个与base存在大于40的差异，就退出比较
+        for idx in range(len(l1)):
+            if abs(l1[idx][0] - l2[idx][0]) < 40 and abs(l1[idx][1] - l2[idx][1]) < 40:
+                pass
+            else:
+                mark = False
+                break
+        return mark
+
+# 功能：根据font基准寻找新的word_list。汽车之家专用。
+def find_new_word_list(font_base, word_list_base, font_new):
+    # 手动确定一组编码和字符的对应关系
+    uni_list = font_base['cmap'].tables[0].ttFont.getGlyphOrder()[1:]
+
+    # 获取38个字符的（x,y）信息
+    cor_base_all = []
+    for uni in uni_list:
+        p1 = []  # 保存一个字符的(x,y)信息
+        p = font_base['glyf'][uni].coordinates  # 获取对象的x,y信息，返回的是一个GlyphCoordinates对象，可以当作列表操作，每个元素是（x,y）元组
+        for f in p:  # 把GlyphCoordinates对象改成一个列表
+            p1.append(f)
+        cor_base_all.append(p1)
+
+    uni_list_new = font_new.getGlyphOrder()[1:]
+    cor_list_new = []
+    ss = []
+    for i in uni_list_new:
+        pp1 = []
+        p = font_new['glyf'][i].coordinates
+        for f in p:
+            pp1.append(f)
+        cor_list_new.append(pp1)
+
+    word_list_new = []
+    for cor_new in cor_list_new:
+        idx_new = 0
+        for cor_base in cor_base_all:
+            idx_new += 1
+            if cor_compare(cor_base, cor_new):
+                word_list_new.append(word_list_base[idx_new - 1])
+
+    return word_list_new
```

### Comparing `general_calculator_zsd-1.2.0/general_calculator_zsd/mysql_transmit_data4all.py` & `general_calculator_zsd-1.2.1/general_calculator_zsd/mysql_transmit_data4all.py`

 * *Files 2% similar despite different names*

```diff
@@ -136,17 +136,17 @@
             mc.rootid rootid, mc.createdby createdby, mc.commentscount commentscount, m.source from {table} mc
             left join moment m on m.id=mc.momentid where mc.createtime >= '{start_datetime}' 
             and mc.createtime < '{end_datetime}';
             """.format(table=select_table, start_datetime=start_datetime, end_datetime=end_datetime)
     elif select_table == 'bilibili_video_comment':
         select_sql = """
             select c.*, p.video_id from {table} c
-            left join bilibili_video_post p on c.vid=p.video_bvid where c.spider_datetime >='{start_datetime}'
+            left join bilibili_video_post p on c.video_bvid=p.video_bvid where c.spider_datetime >='{start_datetime}'
             and c.spider_datetime < '{end_datetime}'
-            order by time desc
+            order by comment_datetime desc
             """.format(table=select_table, start_datetime=start_datetime, end_datetime=end_datetime)
     elif select_table == 'user_base':
         select_sql = """
                 select u.user_id as user_id, u.nick_name as user_nickname, u.sex as user_gender, u.province_name as user_province,
                 u.city_name as user_city, u.birthday as user_birth_date, u.signature as user_summary, u.badges as verified_reason,
                 u.role as user_label, DATE_FORMAT(u.create_time,'%Y-%m-%d') as register_date, u.hobby as user_interests
                 from bi.{table} u
@@ -196,15 +196,15 @@
                 mc.rootid rootid, mc.createdby createdby, mc.commentscount commentscount, m.source from {select_table} mc
                 left join moment m on m.id=mc.momentid where mc.{select_key} not in 
                 (select {goal_key} from {goal_table} where platform_id >={plat_low} and platform_id < {plat_high});
                 """
     elif select_table == 'bilibili_video_comment':
         select_sql = f"""
                 select c.*, p.video_id from {select_table} c
-                left join bilibili_video_post p on c.vid=p.video_bvid where {select_key} not in 
+                left join bilibili_video_post p on c.video_bvid=p.video_bvid where {select_key} not in 
                 (select {goal_key} from {goal_table} where platform_id >={plat_low} and platform_id < {plat_high});
                 """
     elif select_table == 'user_base':
         select_sql = f"""
                 select u.user_id as user_id, u.nick_name as user_nickname, u.sex as user_gender, u.province_name as user_province,
                 u.city_name as user_city, u.birthday as user_birth_date, u.signature as user_summary, u.badges as verified_reason,
                 u.role as user_label, DATE_FORMAT(u.create_time,'%Y-%m-%d') as register_date, u.hobby as user_interests
@@ -239,23 +239,16 @@
     if select_table == "autohome_koubei_post":
         df = fix_koubei_post(df)
     df1 = np.array(df)  # 获取列名
     column_list = list(df.columns)
     for row in df1:  # 循环每一行数据，组装成一个字典，然后得到字典的列表
         lst.append(dict(zip(column_list, list(row))))
     conn.close() # 关闭数据库连接
-    # except Exception as ex:
-    #     print(ex)
     return lst
 
-# def get_flag(value):
-#     if value is not None and value != 'nan':
-#         return 0
-#     elif value is None or value == 'nan':
-#         return 1
 def get_flag(value):
     if type(value) is int:
         if value != 0:
             return 0
         else:
             return 1
     else:
@@ -272,15 +265,15 @@
 def get_hashtag(value):
     if value is not None:
         ls = eval((value))
         res = []
         for item in ls:
             hashtag = item["subject"]
             res.append(hashtag)
-        result = ",".join(i for i in res)
+        result = "|".join(i for i in res)
         return result
     else:
         return None
     
 def get_content4moment(content_data):
     if content_data is not None:
         ls = eval(content_data)
@@ -413,14 +406,15 @@
         insert_data["keyword"] = json_data["keyword"]
         insert_data["account_name"] = "搜索"
         insert_data["brand_id"] = json_data["brand_id"]
         insert_data["series_id"] = json_data["series_id"]
         insert_data["publish_country"] = json_data["wenzhang_country"]
         insert_data["publish_province"] = json_data["wenzhang_province"]
         insert_data["hot_degree"] = json_data["comment_count_all"]
+        insert_data["post_url"] = json_data["wenzhang_url"]
     elif select_table == 'autohome_luntan_post':
         insert_data["platform_id"] = json_data["platform_id"]
         insert_data["post_id"] = json_data["tiezi_id"]
         insert_data["user_id"] = json_data["user_id"]
         insert_data["post_datetime"] = json_data["tiezi_datetime"]
         try:
             insert_data["post_content"] = json_data["tiezi_content"].replace('图片已删除', '')
@@ -435,14 +429,15 @@
         # insert_data["keyword"] = json_data["keyword"]
         insert_data["account_name"] = json_data["account_name"]
         insert_data["brand_id"] = json_data["brand_id"]
         insert_data["series_id"] = json_data["series_id"]
         insert_data["publish_country"] = json_data["tiezi_country"]
         insert_data["publish_province"] = json_data["tiezi_province"]
         insert_data["hot_degree"] = int(json_data["read_count"]) + 72*int(json_data["comment_count"])
+        insert_data["post_url"] = json_data["tiezi_url"]
     elif select_table == 'autohome_koubei_post':
         insert_data["platform_id"] = json_data["platform_id"]
         insert_data["post_id"] = json_data["post_id"]
         insert_data["user_id"] = json_data["user_id"]
         insert_data["post_datetime"] = json_data["post_datetime"]
         insert_data["post_content"] = json_data["post_content"]
         insert_data["post_subject"] = None
@@ -474,14 +469,15 @@
         # insert_data["user_label"] = json_data["tiezi_datetime"]
         insert_data["user_post_count"] = json_data["tiezi_count"]
         insert_data["following_count"] = json_data["following_count"]
         insert_data["follower_count"] = json_data["follower_count"]
         insert_data["user_level"] = json_data["vip_level"]
         insert_data["register_date"] = json_data["register_date"]
         insert_data["spider_datetime"] = json_data["spider_datetime"]
+        insert_data["user_url"] = json_data["user_url"]
     elif select_table == 'bilibili_video_post':
         insert_data["platform_id"] = 301
         insert_data["post_id"] = json_data["video_id"]
         insert_data["user_id"] = json_data["user_id"]
         insert_data["post_datetime"] = json_data["video_pubdate"]
         insert_data["post_content"] = json_data["video_summary"]
         insert_data["post_subject"] = json_data["video_title"]
@@ -498,29 +494,30 @@
         insert_data["keyword"] = json_data["search_keyword"]
         insert_data["account_name"] = "搜索"
         # insert_data["brand_id"] = get_brand_id(json_data["video_summary"])
         # insert_data["series_id"] = get_series_id(json_data["video_summary"])
         insert_data["brand_id"] = json_data["brand_id"]
         insert_data["series_id"] = json_data["series_id"]
         insert_data["hot_degree"] = 2*json_data["like_count"] + 15*json_data["favorite_count"] + 10*json_data["comment_count"]
+        insert_data["post_url"] = json_data["video_url"]
     elif select_table == 'bilibili_video_comment':
         insert_data["platform_id"] = 301
-        insert_data["comment_id"] = json_data["rpid"]
-        insert_data["user_id"] = json_data["uid"]
-        insert_data["comment_datetime"] = json_data["time"]
+        insert_data["comment_id"] = json_data["comment_id"]
+        insert_data["user_id"] = json_data["user_id"]
+        insert_data["comment_datetime"] = json_data["comment_datetime"]
         insert_data["comment_country"] = json_data["comment_country"]
         insert_data["comment_province"] = json_data["comment_province"]
-        insert_data["comment_content"] = json_data["content"]
-        insert_data["comment_like_count"] = json_data["star"]
-        insert_data["comment_reply_count"] = json_data["reply"]
-        insert_data["comment_main_flag"] = json_data['main_flag']
-        insert_data["comment_main_id"] = json_data['main_id']
+        insert_data["comment_content"] = json_data["comment_content"]
+        insert_data["comment_like_count"] = json_data["like_count"]
+        insert_data["comment_reply_count"] = json_data["reply_count"]
+        insert_data["comment_main_flag"] = json_data["main_flag"]
+        insert_data["comment_main_id"] = json_data["main_id"]
         insert_data["post_id"] = json_data["video_id"]
         insert_data["spider_datetime"] = json_data["spider_datetime"]
-        insert_data["hot_degree"] = 1*int(json_data["star"]) + 6*int(json_data["reply"])
+        insert_data["hot_degree"] = 1*int(json_data["like_count"]) + 6*int(json_data["reply_count"])
     elif select_table == 'bilibili_video_danmu':
         insert_data["platform_id"] = 302
         insert_data["comment_id"] = json_data["danmu_comment_id"]
         insert_data["user_id"] = json_data["user_id"]
         insert_data["comment_datetime"] = json_data["pub_datetime"]
         # insert_data["comment_province"] = ""
         insert_data["comment_content"] = json_data["danmu_content"]
@@ -531,16 +528,41 @@
         insert_data["post_id"] = json_data["video_id"]
         insert_data["spider_datetime"] = json_data["spider_datetime"]
         insert_data["hot_degree"] = 0
     elif select_table == 'bilibili_user_info':
         insert_data["media_id"] = 300
         insert_data["user_id"] = json_data["user_id"]
         insert_data["user_nickname"] = json_data["user_nickname"]
+        insert_data["user_gender"] = json_data["user_gender"]
+        # insert_data["user_country"] = json_data["user_country"]
+        # insert_data["user_province"] = json_data["user_province"]
+        # insert_data["user_city"] = json_data["user_city"]
+        # insert_data["true_country"] = json_data["true_country"]
+        # insert_data["true_province"] = json_data["true_province"]
+        # insert_data["user_birth_date"] = json_data["user_birth_date"]
+        insert_data["user_education"] = json_data["user_school"]
+        # insert_data["user_work"] = json_data["user_work"]
+        insert_data["user_summary"] = json_data["user_summary"]
+        # insert_data["verified_flag"] = json_data["verified_flag"]
+        # insert_data["verified_type"] = json_data["verified_type"]
+        # insert_data["verified_reason"] = json_data["verified_reason"]
+        # insert_data["user_label"] = json_data["user_label"]
+        # insert_data["user_post_count"] = json_data["user_post_count"]
+        insert_data["following_count"] = json_data["following_count"]
+        insert_data["follower_count"] = json_data["follower_count"]
+        insert_data["user_level"] = json_data["user_level"]
+        # insert_data["register_date"] = json_data["register_date"]
         insert_data["spider_datetime"] = json_data["spider_datetime"]
-        insert_data["user_summary"] = None
+        # insert_data["user_type"] = json_data["user_type"]
+        # insert_data["user_feature"] = json_data["user_feature"]
+        # insert_data["summary_keyword"] = json_data["summary_keyword"]
+        # insert_data["user_interests"] = json_data["user_interests"]
+        # insert_data["user_car_owned"] = json_data["user_car_owned"]
+        # insert_data["user_car_interested"] = json_data["user_car_interested"]
+        insert_data["user_url"] = json_data["user_url"]
     elif select_table == 'moment':
         insert_data["platform_id"] = get_platform_id(json_data["source"])
         insert_data["post_id"] = json_data["id"]
         insert_data["user_id"] = int(json_data["createdby"].replace("CMS", "9999999999").replace("smarter_unknown", "1111111111"))
         insert_data["post_datetime"] = json_data["createtime"]
         insert_data["post_content"], insert_data['post_image'] = get_content4moment(json_data["contentdata"])
         # insert_data["post_content"] = json_data["content"]
@@ -606,14 +628,15 @@
             insert_data["keyword"] = json_data["search_keyword"]
             insert_data["hot_degree"] = json_data["attitudes_count"] + 4*json_data["comments_count"]
         else:
             insert_data["keyword"] = None
             insert_data["hot_degree"] = json_data["attitudes_count"] + 8*json_data["comments_count"]
         img_list = json_data["pics"].split(',')
         insert_data["post_image"] = str(img_list)
+        insert_data["post_url"] = json_data["post_url"]
     elif select_table == 'weibo_comment':
         insert_data["platform_id"] = 101
         insert_data["comment_id"] = json_data["comment_id"]
         insert_data["user_id"] = json_data["comment_user_id"]
         insert_data["comment_datetime"] = json_data["comment_publish_time"]
         insert_data["comment_country"] = json_data["comment_user_country"]
         insert_data["comment_province"] = json_data["comment_user_province"]
@@ -647,14 +670,15 @@
         insert_data["user_label"] = json_data["user_label"]
         insert_data["user_post_count"] = json_data["weibo_count"]
         insert_data["following_count"] = json_data["following_count"]
         insert_data["follower_count"] = json_data["follower_count"]
         insert_data["user_level"] = json_data["vip_level"]
         insert_data["register_date"] = json_data["register_time"]
         insert_data["spider_datetime"] = json_data["spider_datetime"]
+        insert_data["user_url"] = json_data["user_url"]
     elif select_table == 'user_base':
         insert_data["media_id"] = 500
         insert_data["user_id"] = json_data["user_id"]
         insert_data["user_nickname"] = json_data["user_nickname"]
         gender = json_data["user_gender"]
         if gender == 'M':
             insert_data["user_gender"] = '男'
@@ -977,14 +1001,18 @@
         # 检查方式2：检查简介中是否包含某个异常类型关键词
         keyword, user_type2 = gc.speacial_identify_summmary(insert_data['user_summary'])
         if user_type2 and user_type1 != user_type2:
             feature_list.append('简介中包含"{}"'.format(keyword))
             type_list.append(user_type2)
         insert_data['user_feature'] = '|'.join(feature_list)
         insert_data['user_type'] = '|'.join(type_list)
+        if insert_data['user_feature'] == '':
+            insert_data['user_feature'] = None
+        if insert_data['user_type'] == '':
+            insert_data['user_type'] = None
         # 用户简介的关键词提取
         try:
             keyword_list = []
             user_summary = insert_data["user_summary"]
             keyword_out = gc.keywords_extraction(user_summary, 3)
             for word_score in keyword_out:
                 keyword_list.append(word_score['word'])
@@ -1063,8 +1091,8 @@
                     if np.isnan(data[k]):
                         data[k] = None
                 except:
                     continue
             try:
                 insert_json_sql(data, insert_ip, insert_tbl, select_tbl, cover_flag)
             except:
-                print('数据插入失败：', data)
+                print('数据插入失败：', data)
```

### Comparing `general_calculator_zsd-1.2.0/setup.py` & `general_calculator_zsd-1.2.1/setup.py`

 * *Files 1% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 from setuptools import setup, find_packages
 
 setup(
     name='general_calculator_zsd',
-    version='1.2.0',
+    version='1.2.1',
     author='colin zhang',
     author_email='zsd0830@163.com',
     description='通用脚本及数据导入脚本，不定期按需更新。',
     long_description_content_type="""text/markdown""",
     url='',
     packages=find_packages(),
     classifiers=[
```


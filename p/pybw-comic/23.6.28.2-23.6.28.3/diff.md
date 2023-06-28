# Comparing `tmp/pybw_comic-23.6.28.2.tar.gz` & `tmp/pybw_comic-23.6.28.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pybw_comic-23.6.28.2.tar", last modified: Wed Jun 28 01:31:02 2023, max compression
+gzip compressed data, was "pybw_comic-23.6.28.3.tar", last modified: Wed Jun 28 02:30:21 2023, max compression
```

## Comparing `pybw_comic-23.6.28.2.tar` & `pybw_comic-23.6.28.3.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 01:31:02.486626 pybw_comic-23.6.28.2/
--rw-rw-rw-   0        0        0      577 2023-03-14 13:35:46.000000 pybw_comic-23.6.28.2/- command.txt
--rw-rw-rw-   0        0        0     1167 2023-03-13 12:06:00.000000 pybw_comic-23.6.28.2/LICENSE
--rw-rw-rw-   0        0        0       17 2023-03-13 14:36:52.000000 pybw_comic-23.6.28.2/MANIFEST.in
--rw-rw-rw-   0        0        0      765 2023-06-28 01:31:02.485627 pybw_comic-23.6.28.2/PKG-INFO
--rw-rw-rw-   0        0        0       26 2023-06-21 09:53:53.000000 pybw_comic-23.6.28.2/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 01:31:02.351616 pybw_comic-23.6.28.2/pybw_comic/
--rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.2/pybw_comic/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 01:31:02.463627 pybw_comic-23.6.28.2/pybw_comic/engines/
--rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.2/pybw_comic/engines/__init__.py
--rw-rw-rw-   0        0        0    18753 2023-06-20 12:37:25.000000 pybw_comic-23.6.28.2/pybw_comic/engines/_todo_dmzj_cn.py
--rw-rw-rw-   0        0        0    18538 2023-06-21 10:30:25.000000 pybw_comic-23.6.28.2/pybw_comic/engines/_todo_dmzj_requests.py
--rw-rw-rw-   0        0        0    17144 2022-09-21 08:09:06.000000 pybw_comic-23.6.28.2/pybw_comic/engines/cnanjie.py
--rw-rw-rw-   0        0        0    22662 2023-06-28 01:30:25.000000 pybw_comic-23.6.28.2/pybw_comic/engines/copymanga.py
--rw-rw-rw-   0        0        0    22139 2023-06-21 12:15:34.000000 pybw_comic-23.6.28.2/pybw_comic/engines/dmzj_selenium.py
--rw-rw-rw-   0        0        0    23738 2022-09-21 08:08:24.000000 pybw_comic-23.6.28.2/pybw_comic/engines/manhuaDB.py
--rw-rw-rw-   0        0        0    24178 2022-09-21 08:09:13.000000 pybw_comic-23.6.28.2/pybw_comic/engines/maofly.py
--rw-rw-rw-   0        0        0    20791 2022-09-21 08:08:55.000000 pybw_comic-23.6.28.2/pybw_comic/engines/mhkan.py
--rw-rw-rw-   0        0        0    20845 2022-09-21 08:08:09.000000 pybw_comic-23.6.28.2/pybw_comic/engines/www_1kkk.py
--rw-rw-rw-   0        0        0    20667 2023-06-21 12:06:21.000000 pybw_comic-23.6.28.2/pybw_comic/engines/xmanhua.py
-drwxrwxrwx   0        0        0        0 2023-06-28 01:31:02.470625 pybw_comic-23.6.28.2/pybw_comic/scripts/
--rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.2/pybw_comic/scripts/__init__.py
--rw-rw-rw-   0        0        0     3433 2023-06-28 01:12:21.000000 pybw_comic-23.6.28.2/pybw_comic/scripts/comic.py
-drwxrwxrwx   0        0        0        0 2023-06-28 01:31:02.379619 pybw_comic-23.6.28.2/pybw_comic.egg-info/
--rw-rw-rw-   0        0        0      765 2023-06-28 01:31:02.000000 pybw_comic-23.6.28.2/pybw_comic.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      687 2023-06-28 01:31:02.000000 pybw_comic-23.6.28.2/pybw_comic.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 01:31:02.000000 pybw_comic-23.6.28.2/pybw_comic.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       11 2023-06-28 01:31:02.000000 pybw_comic-23.6.28.2/pybw_comic.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       23 2023-06-21 09:53:36.000000 pybw_comic-23.6.28.2/requirements.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 01:31:02.486626 pybw_comic-23.6.28.2/setup.cfg
--rw-rw-rw-   0        0        0     1508 2023-06-28 01:30:52.000000 pybw_comic-23.6.28.2/setup.py
--rwxrwxrwx   0        0        0      353 2023-06-27 09:41:06.000000 pybw_comic-23.6.28.2/upload_pypi.bat
+drwxrwxrwx   0        0        0        0 2023-06-28 02:30:21.088518 pybw_comic-23.6.28.3/
+-rw-rw-rw-   0        0        0      577 2023-03-14 13:35:46.000000 pybw_comic-23.6.28.3/- command.txt
+-rw-rw-rw-   0        0        0     1167 2023-03-13 12:06:00.000000 pybw_comic-23.6.28.3/LICENSE
+-rw-rw-rw-   0        0        0       17 2023-03-13 14:36:52.000000 pybw_comic-23.6.28.3/MANIFEST.in
+-rw-rw-rw-   0        0        0      765 2023-06-28 02:30:21.086521 pybw_comic-23.6.28.3/PKG-INFO
+-rw-rw-rw-   0        0        0       26 2023-06-21 09:53:53.000000 pybw_comic-23.6.28.3/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 02:30:20.963508 pybw_comic-23.6.28.3/pybw_comic/
+-rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.3/pybw_comic/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:30:21.069518 pybw_comic-23.6.28.3/pybw_comic/engines/
+-rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.3/pybw_comic/engines/__init__.py
+-rw-rw-rw-   0        0        0    18753 2023-06-20 12:37:25.000000 pybw_comic-23.6.28.3/pybw_comic/engines/_todo_dmzj_cn.py
+-rw-rw-rw-   0        0        0    18538 2023-06-21 10:30:25.000000 pybw_comic-23.6.28.3/pybw_comic/engines/_todo_dmzj_requests.py
+-rw-rw-rw-   0        0        0    17144 2022-09-21 08:09:06.000000 pybw_comic-23.6.28.3/pybw_comic/engines/cnanjie.py
+-rw-rw-rw-   0        0        0    22670 2023-06-28 02:29:50.000000 pybw_comic-23.6.28.3/pybw_comic/engines/copymanga.py
+-rw-rw-rw-   0        0        0    22139 2023-06-21 12:15:34.000000 pybw_comic-23.6.28.3/pybw_comic/engines/dmzj_selenium.py
+-rw-rw-rw-   0        0        0    23738 2022-09-21 08:08:24.000000 pybw_comic-23.6.28.3/pybw_comic/engines/manhuaDB.py
+-rw-rw-rw-   0        0        0    24178 2022-09-21 08:09:13.000000 pybw_comic-23.6.28.3/pybw_comic/engines/maofly.py
+-rw-rw-rw-   0        0        0    20791 2022-09-21 08:08:55.000000 pybw_comic-23.6.28.3/pybw_comic/engines/mhkan.py
+-rw-rw-rw-   0        0        0    20845 2022-09-21 08:08:09.000000 pybw_comic-23.6.28.3/pybw_comic/engines/www_1kkk.py
+-rw-rw-rw-   0        0        0    20667 2023-06-21 12:06:21.000000 pybw_comic-23.6.28.3/pybw_comic/engines/xmanhua.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:30:21.076518 pybw_comic-23.6.28.3/pybw_comic/scripts/
+-rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.3/pybw_comic/scripts/__init__.py
+-rw-rw-rw-   0        0        0     3433 2023-06-28 01:12:21.000000 pybw_comic-23.6.28.3/pybw_comic/scripts/comic.py
+drwxrwxrwx   0        0        0        0 2023-06-28 02:30:20.987511 pybw_comic-23.6.28.3/pybw_comic.egg-info/
+-rw-rw-rw-   0        0        0      765 2023-06-28 02:30:20.000000 pybw_comic-23.6.28.3/pybw_comic.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      687 2023-06-28 02:30:20.000000 pybw_comic-23.6.28.3/pybw_comic.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 02:30:20.000000 pybw_comic-23.6.28.3/pybw_comic.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       11 2023-06-28 02:30:20.000000 pybw_comic-23.6.28.3/pybw_comic.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       23 2023-06-21 09:53:36.000000 pybw_comic-23.6.28.3/requirements.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 02:30:21.088518 pybw_comic-23.6.28.3/setup.cfg
+-rw-rw-rw-   0        0        0     1508 2023-06-28 02:30:11.000000 pybw_comic-23.6.28.3/setup.py
+-rwxrwxrwx   0        0        0      353 2023-06-27 09:41:06.000000 pybw_comic-23.6.28.3/upload_pypi.bat
```

### Comparing `pybw_comic-23.6.28.2/- command.txt` & `pybw_comic-23.6.28.3/- command.txt`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/LICENSE` & `pybw_comic-23.6.28.3/LICENSE`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/PKG-INFO` & `pybw_comic-23.6.28.3/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pybw_comic
-Version: 23.6.28.2
+Version: 23.6.28.3
 Summary: comic spider
 Home-page: https://gitee.com/pubowei/comic
 Author: Bowei Pu
 Author-email: pubowei@foxmail.com
 License: MIT
 Project-URL: Docs, https://gitee.com/pubowei/comic
 Project-URL: Package, https://pypi.org/project/pybw
```

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/_todo_dmzj_cn.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/_todo_dmzj_cn.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/_todo_dmzj_requests.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/_todo_dmzj_requests.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/cnanjie.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/cnanjie.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/copymanga.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/copymanga.py`

 * *Files 0% similar despite different names*

```diff
@@ -484,15 +484,15 @@
         if not dire:
             dire = '{} {} [{}] [{}] [{}] [{}]'.format(
                 time_label, self.catelogue.book_name, 
                 self.author, self.book_topic, self.book_state, 
                 self.website_label)
         return dire 
         
-    def download(self, start_labels=[], mode='0'):
+    def download(self, start_labels=[], mode=0):
         """
         Execute download the comic book.
         
         Args:
             start_labels: [Todo]
             mode: 0, 'not_all': don not download column "全部"
                   1, 'all': only download column "全部"
@@ -519,18 +519,18 @@
         if start_labels:
             start_ok = False
             start_labels = [CleanText(i).clean_text for i in start_labels]
         else:
             start_ok = True
         
         for col_idx, col_name in enumerate(self.catelogue.chapters.keys()):
-            if mode in [0, 'not_all']:
+            if mode in [0, '0', 'not_all']:
                 if col_name == '全部':
                     continue
-            elif mode in [1, 'all']:
+            elif mode in [1, '1', 'all']:
                 if col_name != '全部':
                     continue
             elif mode in self.catelogue.chapters.keys():
                 if col_name != mode:
                     continue
             
             for i in start_labels:
```

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/dmzj_selenium.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/dmzj_selenium.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/manhuaDB.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/manhuaDB.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/maofly.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/maofly.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/mhkan.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/mhkan.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/www_1kkk.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/www_1kkk.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic/engines/xmanhua.py` & `pybw_comic-23.6.28.3/pybw_comic/engines/xmanhua.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic/scripts/comic.py` & `pybw_comic-23.6.28.3/pybw_comic/scripts/comic.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/pybw_comic.egg-info/PKG-INFO` & `pybw_comic-23.6.28.3/pybw_comic.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pybw-comic
-Version: 23.6.28.2
+Version: 23.6.28.3
 Summary: comic spider
 Home-page: https://gitee.com/pubowei/comic
 Author: Bowei Pu
 Author-email: pubowei@foxmail.com
 License: MIT
 Project-URL: Docs, https://gitee.com/pubowei/comic
 Project-URL: Package, https://pypi.org/project/pybw
```

### Comparing `pybw_comic-23.6.28.2/pybw_comic.egg-info/SOURCES.txt` & `pybw_comic-23.6.28.3/pybw_comic.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.2/setup.py` & `pybw_comic-23.6.28.3/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -10,15 +10,15 @@
 
 with open('README.md', encoding='utf-8') as f:
     readme = f.read()
 
 
 setup(
     name='pybw_comic',
-    version='23.6.28.2',
+    version='23.6.28.3',
     python_requires='>=3.6',
     
     author='Bowei Pu',
     author_email='pubowei@foxmail.com',
     
     description='comic spider',
     long_description=readme,
```


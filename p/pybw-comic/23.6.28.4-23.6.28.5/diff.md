# Comparing `tmp/pybw_comic-23.6.28.4.tar.gz` & `tmp/pybw_comic-23.6.28.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pybw_comic-23.6.28.4.tar", last modified: Wed Jun 28 02:49:11 2023, max compression
+gzip compressed data, was "pybw_comic-23.6.28.5.tar", last modified: Wed Jun 28 03:37:45 2023, max compression
```

## Comparing `pybw_comic-23.6.28.4.tar` & `pybw_comic-23.6.28.5.tar`

### file list

```diff
@@ -1,32 +1,32 @@
-drwxrwxrwx   0        0        0        0 2023-06-28 02:49:11.805250 pybw_comic-23.6.28.4/
--rw-rw-rw-   0        0        0      577 2023-03-14 13:35:46.000000 pybw_comic-23.6.28.4/- command.txt
--rw-rw-rw-   0        0        0     1167 2023-03-13 12:06:00.000000 pybw_comic-23.6.28.4/LICENSE
--rw-rw-rw-   0        0        0       17 2023-03-13 14:36:52.000000 pybw_comic-23.6.28.4/MANIFEST.in
--rw-rw-rw-   0        0        0      765 2023-06-28 02:49:11.804249 pybw_comic-23.6.28.4/PKG-INFO
--rw-rw-rw-   0        0        0       26 2023-06-21 09:53:53.000000 pybw_comic-23.6.28.4/README.md
-drwxrwxrwx   0        0        0        0 2023-06-28 02:49:11.678239 pybw_comic-23.6.28.4/pybw_comic/
--rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.4/pybw_comic/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-28 02:49:11.786251 pybw_comic-23.6.28.4/pybw_comic/engines/
--rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.4/pybw_comic/engines/__init__.py
--rw-rw-rw-   0        0        0    18753 2023-06-20 12:37:25.000000 pybw_comic-23.6.28.4/pybw_comic/engines/_todo_dmzj_cn.py
--rw-rw-rw-   0        0        0    18538 2023-06-21 10:30:25.000000 pybw_comic-23.6.28.4/pybw_comic/engines/_todo_dmzj_requests.py
--rw-rw-rw-   0        0        0    17144 2022-09-21 08:09:06.000000 pybw_comic-23.6.28.4/pybw_comic/engines/cnanjie.py
--rw-rw-rw-   0        0        0    22747 2023-06-28 02:47:35.000000 pybw_comic-23.6.28.4/pybw_comic/engines/copymanga.py
--rw-rw-rw-   0        0        0    22139 2023-06-21 12:15:34.000000 pybw_comic-23.6.28.4/pybw_comic/engines/dmzj_selenium.py
--rw-rw-rw-   0        0        0    23738 2022-09-21 08:08:24.000000 pybw_comic-23.6.28.4/pybw_comic/engines/manhuaDB.py
--rw-rw-rw-   0        0        0    24178 2022-09-21 08:09:13.000000 pybw_comic-23.6.28.4/pybw_comic/engines/maofly.py
--rw-rw-rw-   0        0        0    20791 2022-09-21 08:08:55.000000 pybw_comic-23.6.28.4/pybw_comic/engines/mhkan.py
--rw-rw-rw-   0        0        0    20845 2022-09-21 08:08:09.000000 pybw_comic-23.6.28.4/pybw_comic/engines/www_1kkk.py
--rw-rw-rw-   0        0        0    20667 2023-06-21 12:06:21.000000 pybw_comic-23.6.28.4/pybw_comic/engines/xmanhua.py
-drwxrwxrwx   0        0        0        0 2023-06-28 02:49:11.795250 pybw_comic-23.6.28.4/pybw_comic/scripts/
--rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.4/pybw_comic/scripts/__init__.py
--rw-rw-rw-   0        0        0     3433 2023-06-28 01:12:21.000000 pybw_comic-23.6.28.4/pybw_comic/scripts/comic.py
-drwxrwxrwx   0        0        0        0 2023-06-28 02:49:11.709242 pybw_comic-23.6.28.4/pybw_comic.egg-info/
--rw-rw-rw-   0        0        0      765 2023-06-28 02:49:11.000000 pybw_comic-23.6.28.4/pybw_comic.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      687 2023-06-28 02:49:11.000000 pybw_comic-23.6.28.4/pybw_comic.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-28 02:49:11.000000 pybw_comic-23.6.28.4/pybw_comic.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       11 2023-06-28 02:49:11.000000 pybw_comic-23.6.28.4/pybw_comic.egg-info/top_level.txt
--rw-rw-rw-   0        0        0       23 2023-06-21 09:53:36.000000 pybw_comic-23.6.28.4/requirements.txt
--rw-rw-rw-   0        0        0       42 2023-06-28 02:49:11.806247 pybw_comic-23.6.28.4/setup.cfg
--rw-rw-rw-   0        0        0     1508 2023-06-28 02:49:02.000000 pybw_comic-23.6.28.4/setup.py
--rwxrwxrwx   0        0        0      360 2023-06-28 02:30:55.000000 pybw_comic-23.6.28.4/upload_pypi.bat
+drwxrwxrwx   0        0        0        0 2023-06-28 03:37:45.406540 pybw_comic-23.6.28.5/
+-rw-rw-rw-   0        0        0      577 2023-03-14 13:35:46.000000 pybw_comic-23.6.28.5/- command.txt
+-rw-rw-rw-   0        0        0     1167 2023-03-13 12:06:00.000000 pybw_comic-23.6.28.5/LICENSE
+-rw-rw-rw-   0        0        0       17 2023-03-13 14:36:52.000000 pybw_comic-23.6.28.5/MANIFEST.in
+-rw-rw-rw-   0        0        0      765 2023-06-28 03:37:45.405540 pybw_comic-23.6.28.5/PKG-INFO
+-rw-rw-rw-   0        0        0       26 2023-06-21 09:53:53.000000 pybw_comic-23.6.28.5/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 03:37:45.285530 pybw_comic-23.6.28.5/pybw_comic/
+-rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.5/pybw_comic/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:37:45.390539 pybw_comic-23.6.28.5/pybw_comic/engines/
+-rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.5/pybw_comic/engines/__init__.py
+-rw-rw-rw-   0        0        0    18753 2023-06-20 12:37:25.000000 pybw_comic-23.6.28.5/pybw_comic/engines/_todo_dmzj_cn.py
+-rw-rw-rw-   0        0        0    18538 2023-06-21 10:30:25.000000 pybw_comic-23.6.28.5/pybw_comic/engines/_todo_dmzj_requests.py
+-rw-rw-rw-   0        0        0    17144 2022-09-21 08:09:06.000000 pybw_comic-23.6.28.5/pybw_comic/engines/cnanjie.py
+-rw-rw-rw-   0        0        0    22932 2023-06-28 03:36:56.000000 pybw_comic-23.6.28.5/pybw_comic/engines/copymanga.py
+-rw-rw-rw-   0        0        0    22139 2023-06-21 12:15:34.000000 pybw_comic-23.6.28.5/pybw_comic/engines/dmzj_selenium.py
+-rw-rw-rw-   0        0        0    23738 2022-09-21 08:08:24.000000 pybw_comic-23.6.28.5/pybw_comic/engines/manhuaDB.py
+-rw-rw-rw-   0        0        0    24178 2022-09-21 08:09:13.000000 pybw_comic-23.6.28.5/pybw_comic/engines/maofly.py
+-rw-rw-rw-   0        0        0    20791 2022-09-21 08:08:55.000000 pybw_comic-23.6.28.5/pybw_comic/engines/mhkan.py
+-rw-rw-rw-   0        0        0    20845 2022-09-21 08:08:09.000000 pybw_comic-23.6.28.5/pybw_comic/engines/www_1kkk.py
+-rw-rw-rw-   0        0        0    20667 2023-06-21 12:06:21.000000 pybw_comic-23.6.28.5/pybw_comic/engines/xmanhua.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:37:45.396539 pybw_comic-23.6.28.5/pybw_comic/scripts/
+-rw-rw-rw-   0        0        0        0 2022-07-27 05:24:03.000000 pybw_comic-23.6.28.5/pybw_comic/scripts/__init__.py
+-rw-rw-rw-   0        0        0     3433 2023-06-28 01:12:21.000000 pybw_comic-23.6.28.5/pybw_comic/scripts/comic.py
+drwxrwxrwx   0        0        0        0 2023-06-28 03:37:45.309533 pybw_comic-23.6.28.5/pybw_comic.egg-info/
+-rw-rw-rw-   0        0        0      765 2023-06-28 03:37:44.000000 pybw_comic-23.6.28.5/pybw_comic.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      687 2023-06-28 03:37:45.000000 pybw_comic-23.6.28.5/pybw_comic.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 03:37:44.000000 pybw_comic-23.6.28.5/pybw_comic.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       11 2023-06-28 03:37:45.000000 pybw_comic-23.6.28.5/pybw_comic.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0       23 2023-06-21 09:53:36.000000 pybw_comic-23.6.28.5/requirements.txt
+-rw-rw-rw-   0        0        0       42 2023-06-28 03:37:45.407540 pybw_comic-23.6.28.5/setup.cfg
+-rw-rw-rw-   0        0        0     1508 2023-06-28 03:37:35.000000 pybw_comic-23.6.28.5/setup.py
+-rwxrwxrwx   0        0        0      360 2023-06-28 02:30:55.000000 pybw_comic-23.6.28.5/upload_pypi.bat
```

### Comparing `pybw_comic-23.6.28.4/- command.txt` & `pybw_comic-23.6.28.5/- command.txt`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/LICENSE` & `pybw_comic-23.6.28.5/LICENSE`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/PKG-INFO` & `pybw_comic-23.6.28.5/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pybw_comic
-Version: 23.6.28.4
+Version: 23.6.28.5
 Summary: comic spider
 Home-page: https://gitee.com/pubowei/comic
 Author: Bowei Pu
 Author-email: pubowei@foxmail.com
 License: MIT
 Project-URL: Docs, https://gitee.com/pubowei/comic
 Project-URL: Package, https://pypi.org/project/pybw
```

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/_todo_dmzj_cn.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/_todo_dmzj_cn.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/_todo_dmzj_requests.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/_todo_dmzj_requests.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/cnanjie.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/cnanjie.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/copymanga.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/copymanga.py`

 * *Files 2% similar despite different names*

```diff
@@ -534,14 +534,15 @@
                 if col_name != mode:
                     continue
             
             for i in start_labels:
                 if col_name in i:
                     start_label = i
             chaps = self.catelogue.chapters[col_name]
+            chap_amount = len(chaps)
             for chap_idx, chap in enumerate(chaps):
                 chap_idx += 1
                 time0 = time.time()
                 
                 chap_title = CleanText(chap['title']).clean_text
                 chap_title = '{}_{} {}'.format(
                     col_name, str(chap_idx).zfill(3), chap_title)
@@ -563,16 +564,19 @@
                 
                 chap_url = chap['url']
                 onechap = Chapter(chap_url, headless=self.headless,
                                   driver_img=self.driver_img)
                 onechap.driver.close()
                 images = onechap.images
                 
-                print('\nDownloading [{0}/{1}]: {2}'.format(
-                    chap_idx, self.chapter_amount, chap_title))
+                # print('\nDownloading [{0}/{1}]: {2}'.format(
+                    # chap_idx, self.chapter_amount, chap_title))
+                print('\nDownloading [] [{}/{}]: {}'.format(
+                    col_name, chap_idx, chap_amount, chap_title))
+                
                 
                 for i, img_url in enumerate(tqdm(images)):
                     file_prefix = 'page_{}-'.format(str(i+1).zfill(6))
                     file = Path(img_url).name
                     file = file_prefix + file
                     file_path = Path(path_chap).joinpath(file).as_posix()
                     if os.path.exists(file_path):
```

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/dmzj_selenium.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/dmzj_selenium.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/manhuaDB.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/manhuaDB.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/maofly.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/maofly.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/mhkan.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/mhkan.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/www_1kkk.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/www_1kkk.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic/engines/xmanhua.py` & `pybw_comic-23.6.28.5/pybw_comic/engines/xmanhua.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic/scripts/comic.py` & `pybw_comic-23.6.28.5/pybw_comic/scripts/comic.py`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/pybw_comic.egg-info/PKG-INFO` & `pybw_comic-23.6.28.5/pybw_comic.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pybw-comic
-Version: 23.6.28.4
+Version: 23.6.28.5
 Summary: comic spider
 Home-page: https://gitee.com/pubowei/comic
 Author: Bowei Pu
 Author-email: pubowei@foxmail.com
 License: MIT
 Project-URL: Docs, https://gitee.com/pubowei/comic
 Project-URL: Package, https://pypi.org/project/pybw
```

### Comparing `pybw_comic-23.6.28.4/pybw_comic.egg-info/SOURCES.txt` & `pybw_comic-23.6.28.5/pybw_comic.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `pybw_comic-23.6.28.4/setup.py` & `pybw_comic-23.6.28.5/setup.py`

 * *Files 0% similar despite different names*

```diff
@@ -10,15 +10,15 @@
 
 with open('README.md', encoding='utf-8') as f:
     readme = f.read()
 
 
 setup(
     name='pybw_comic',
-    version='23.6.28.4',
+    version='23.6.28.5',
     python_requires='>=3.6',
     
     author='Bowei Pu',
     author_email='pubowei@foxmail.com',
     
     description='comic spider',
     long_description=readme,
```


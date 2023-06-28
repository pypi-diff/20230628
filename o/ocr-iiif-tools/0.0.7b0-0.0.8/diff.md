# Comparing `tmp/ocr_iiif_tools-0.0.7b0.tar.gz` & `tmp/ocr_iiif_tools-0.0.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ocr_iiif_tools-0.0.7b0.tar", last modified: Thu Jun 22 21:33:03 2023, max compression
+gzip compressed data, was "ocr_iiif_tools-0.0.8.tar", last modified: Wed Jun 28 04:19:14 2023, max compression
```

## Comparing `ocr_iiif_tools-0.0.7b0.tar` & `ocr_iiif_tools-0.0.8.tar`

### file list

```diff
@@ -1,29 +1,29 @@
-drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-22 21:33:03.095660 ocr_iiif_tools-0.0.7b0/
--rw-r--r--   0 nakamura   (501) staff       (20)    11337 2023-06-21 11:48:10.000000 ocr_iiif_tools-0.0.7b0/LICENSE
--rw-r--r--   0 nakamura   (501) staff       (20)      111 2023-06-21 11:48:10.000000 ocr_iiif_tools-0.0.7b0/MANIFEST.in
--rw-r--r--   0 nakamura   (501) staff       (20)     1112 2023-06-22 21:33:03.095484 ocr_iiif_tools-0.0.7b0/PKG-INFO
--rw-r--r--   0 nakamura   (501) staff       (20)      339 2023-06-21 23:57:18.000000 ocr_iiif_tools-0.0.7b0/README.md
-drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-22 21:33:03.091236 ocr_iiif_tools-0.0.7b0/iida/
--rw-r--r--   0 nakamura   (501) staff       (20)       22 2023-06-21 11:48:10.000000 ocr_iiif_tools-0.0.7b0/iida/__init__.py
--rw-r--r--   0 nakamura   (501) staff       (20)      912 2023-06-21 11:48:10.000000 ocr_iiif_tools-0.0.7b0/iida/_modidx.py
--rw-r--r--   0 nakamura   (501) staff       (20)     5202 2023-06-21 11:48:10.000000 ocr_iiif_tools-0.0.7b0/iida/core.py
-drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-22 21:33:03.092274 ocr_iiif_tools-0.0.7b0/ocr_iiif/
--rw-r--r--   0 nakamura   (501) staff       (20)       22 2023-06-21 11:48:10.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif/__init__.py
--rw-r--r--   0 nakamura   (501) staff       (20)     1077 2023-06-21 11:48:10.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif/_modidx.py
--rw-r--r--   0 nakamura   (501) staff       (20)     5202 2023-06-21 11:48:10.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif/core.py
-drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-22 21:33:03.093723 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools/
--rw-r--r--   0 nakamura   (501) staff       (20)       22 2023-06-22 04:03:40.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools/__init__.py
--rw-r--r--   0 nakamura   (501) staff       (20)     3466 2023-06-22 04:03:40.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools/_modidx.py
--rw-r--r--   0 nakamura   (501) staff       (20)     5202 2023-06-22 04:03:40.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools/core.py
--rw-r--r--   0 nakamura   (501) staff       (20)    22342 2023-06-22 04:03:40.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools/pdf.py
-drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-22 21:33:03.095248 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/
--rw-r--r--   0 nakamura   (501) staff       (20)     1112 2023-06-22 21:33:03.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/PKG-INFO
--rw-r--r--   0 nakamura   (501) staff       (20)      520 2023-06-22 21:33:03.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/SOURCES.txt
--rw-r--r--   0 nakamura   (501) staff       (20)        1 2023-06-22 21:33:03.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/dependency_links.txt
--rw-r--r--   0 nakamura   (501) staff       (20)       71 2023-06-22 21:33:03.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/entry_points.txt
--rw-r--r--   0 nakamura   (501) staff       (20)        1 2023-06-21 11:50:57.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/not-zip-safe
--rw-r--r--   0 nakamura   (501) staff       (20)       38 2023-06-22 21:33:03.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/requires.txt
--rw-r--r--   0 nakamura   (501) staff       (20)       29 2023-06-22 21:33:03.000000 ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/top_level.txt
--rw-r--r--   0 nakamura   (501) staff       (20)      943 2023-06-22 21:32:55.000000 ocr_iiif_tools-0.0.7b0/settings.ini
--rw-r--r--   0 nakamura   (501) staff       (20)       38 2023-06-22 21:33:03.095720 ocr_iiif_tools-0.0.7b0/setup.cfg
--rw-r--r--   0 nakamura   (501) staff       (20)     2596 2023-06-21 11:48:10.000000 ocr_iiif_tools-0.0.7b0/setup.py
+drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-28 04:19:14.799333 ocr_iiif_tools-0.0.8/
+-rw-rw-r--   0 nakamura   (501) staff       (20)    11337 2023-04-27 10:12:58.000000 ocr_iiif_tools-0.0.8/LICENSE
+-rw-rw-r--   0 nakamura   (501) staff       (20)      111 2023-04-27 10:12:58.000000 ocr_iiif_tools-0.0.8/MANIFEST.in
+-rw-r--r--   0 nakamura   (501) staff       (20)     1110 2023-06-28 04:19:14.799137 ocr_iiif_tools-0.0.8/PKG-INFO
+-rw-r--r--   0 nakamura   (501) staff       (20)      339 2023-06-25 23:33:01.000000 ocr_iiif_tools-0.0.8/README.md
+drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-28 04:19:14.795059 ocr_iiif_tools-0.0.8/iida/
+-rw-r--r--   0 nakamura   (501) staff       (20)       22 2023-06-20 21:23:20.000000 ocr_iiif_tools-0.0.8/iida/__init__.py
+-rw-r--r--   0 nakamura   (501) staff       (20)      912 2023-06-20 21:23:20.000000 ocr_iiif_tools-0.0.8/iida/_modidx.py
+-rw-r--r--   0 nakamura   (501) staff       (20)     5262 2023-06-20 21:23:20.000000 ocr_iiif_tools-0.0.8/iida/core.py
+drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-28 04:19:14.795819 ocr_iiif_tools-0.0.8/ocr_iiif/
+-rw-r--r--   0 nakamura   (501) staff       (20)       22 2023-06-20 20:09:43.000000 ocr_iiif_tools-0.0.8/ocr_iiif/__init__.py
+-rw-r--r--   0 nakamura   (501) staff       (20)     1173 2023-06-20 20:11:42.000000 ocr_iiif_tools-0.0.8/ocr_iiif/_modidx.py
+-rw-r--r--   0 nakamura   (501) staff       (20)     5202 2023-06-20 20:11:42.000000 ocr_iiif_tools-0.0.8/ocr_iiif/core.py
+drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-28 04:19:14.797094 ocr_iiif_tools-0.0.8/ocr_iiif_tools/
+-rw-r--r--   0 nakamura   (501) staff       (20)       22 2023-06-27 08:28:44.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools/__init__.py
+-rw-r--r--   0 nakamura   (501) staff       (20)     4457 2023-06-27 08:28:44.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools/_modidx.py
+-rw-r--r--   0 nakamura   (501) staff       (20)     5202 2023-06-27 08:28:44.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools/core.py
+-rw-r--r--   0 nakamura   (501) staff       (20)    22014 2023-06-27 08:28:44.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools/pdf.py
+drwxr-xr-x   0 nakamura   (501) staff       (20)        0 2023-06-28 04:19:14.798722 ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/
+-rw-r--r--   0 nakamura   (501) staff       (20)     1110 2023-06-28 04:19:14.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/PKG-INFO
+-rw-r--r--   0 nakamura   (501) staff       (20)      520 2023-06-28 04:19:14.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/SOURCES.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)        1 2023-06-28 04:19:14.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/dependency_links.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)       71 2023-06-28 04:19:14.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/entry_points.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)        1 2023-06-20 20:10:31.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/not-zip-safe
+-rw-r--r--   0 nakamura   (501) staff       (20)       31 2023-06-28 04:19:14.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/requires.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)       29 2023-06-28 04:19:14.000000 ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/top_level.txt
+-rw-r--r--   0 nakamura   (501) staff       (20)      931 2023-06-28 04:16:58.000000 ocr_iiif_tools-0.0.8/settings.ini
+-rw-r--r--   0 nakamura   (501) staff       (20)       38 2023-06-28 04:19:14.799398 ocr_iiif_tools-0.0.8/setup.cfg
+-rw-rw-r--   0 nakamura   (501) staff       (20)     2596 2023-04-27 10:12:58.000000 ocr_iiif_tools-0.0.8/setup.py
```

### Comparing `ocr_iiif_tools-0.0.7b0/LICENSE` & `ocr_iiif_tools-0.0.8/LICENSE`

 * *Files identical despite different names*

### Comparing `ocr_iiif_tools-0.0.7b0/PKG-INFO` & `ocr_iiif_tools-0.0.8/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ocr_iiif_tools
-Version: 0.0.7b0
+Version: 0.0.8
 Summary: UNKNOWN
 Home-page: https://github.com/nakamura196/ocr_iiif_tools
 Author: Satoru
 Author-email: you@example.com
 License: Apache Software License 2.0
 Keywords: nbdev jupyter notebook python
 Platform: UNKNOWN
```

### Comparing `ocr_iiif_tools-0.0.7b0/iida/_modidx.py` & `ocr_iiif_tools-0.0.8/iida/_modidx.py`

 * *Files identical despite different names*

### Comparing `ocr_iiif_tools-0.0.7b0/iida/core.py` & `ocr_iiif_tools-0.0.8/ocr_iiif/core.py`

 * *Files identical despite different names*

### Comparing `ocr_iiif_tools-0.0.7b0/ocr_iiif/_modidx.py` & `ocr_iiif_tools-0.0.8/ocr_iiif/_modidx.py`

 * *Files 24% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 # Autogenerated by nbdev
 
 d = { 'settings': { 'branch': 'main',
-                'doc_baseurl': '/ocr_iiif',
+                'doc_baseurl': '/ocr_iiif_tools',
                 'doc_host': 'https://nakamura196.github.io',
-                'git_url': 'https://github.com/nakamura196/ocr_iiif',
-                'lib_path': 'ocr_iiif'},
-  'syms': { 'ocr_iiif.core': { 'ocr_iiif.core.Client': ('core.html#client', 'ocr_iiif/core.py'),
-                               'ocr_iiif.core.Client.__init__': ('core.html#client.__init__', 'ocr_iiif/core.py'),
-                               'ocr_iiif.core.Client.create_annotation_list': ( 'core.html#client.create_annotation_list',
-                                                                                'ocr_iiif/core.py'),
-                               'ocr_iiif.core.Client.create_manifest': ('core.html#client.create_manifest', 'ocr_iiif/core.py'),
-                               'ocr_iiif.core.Client.get_size': ('core.html#client.get_size', 'ocr_iiif/core.py'),
-                               'ocr_iiif.core.Client.get_xywh': ('core.html#client.get_xywh', 'ocr_iiif/core.py')}}}
+                'git_url': 'https://github.com/nakamura196/ocr_iiif_tools',
+                'lib_path': 'ocr_iiif_tools'},
+  'syms': { 'ocr_iiif_tools.core': { 'ocr_iiif_tools.core.Client': ('core.html#client', 'ocr_iiif_tools/core.py'),
+                               'ocr_iiif_tools.core.Client.__init__': ('core.html#client.__init__', 'ocr_iiif_tools/core.py'),
+                               'ocr_iiif_tools.core.Client.create_annotation_list': ( 'core.html#client.create_annotation_list',
+                                                                                'ocr_iiif_tools/core.py'),
+                               'ocr_iiif_tools.core.Client.create_manifest': ('core.html#client.create_manifest', 'ocr_iiif_tools/core.py'),
+                               'ocr_iiif_tools.core.Client.get_size': ('core.html#client.get_size', 'ocr_iiif_tools/core.py'),
+                               'ocr_iiif_tools.core.Client.get_xywh': ('core.html#client.get_xywh', 'ocr_iiif_tools/core.py')}}}
```

### Comparing `ocr_iiif_tools-0.0.7b0/ocr_iiif/core.py` & `ocr_iiif_tools-0.0.8/ocr_iiif_tools/core.py`

 * *Files identical despite different names*

### Comparing `ocr_iiif_tools-0.0.7b0/ocr_iiif_tools/core.py` & `ocr_iiif_tools-0.0.8/iida/core.py`

 * *Files 2% similar despite different names*

```diff
@@ -92,21 +92,23 @@
                     x,y,w,h = self.get_xywh(word)
 
                     x = math.ceil(x / page_w * canvas_w)
                     y = math.ceil(y / page_h * canvas_h)
                     w = math.ceil(w / page_w * canvas_w)
                     h = math.ceil(h / page_h * canvas_h)
 
+                    aid = f"a-{x}-{y}-{w}-{h}"
+
                     anno = {
                         "@context": "http://iiif.io/api/presentation/2/context.json",
                         "@type": "oa:Annotation",
                         "motivation": "oa:commenting",
                         "resource": {
                             "@type": "cnt:ContentAsText",
-                            "chars": word_str,
+                            "chars": f"{aid}: {word_str}",
                             "format": "text/plain"
                         },
                         "on": f"{self.canvas_uri}#xywh={x},{y},{w},{h}",
                         "@id": f"{self.canvas_uri}/annotation/p{x},{y},{w},{h}"
                     }
 
                     annotations.append(anno)
```

### Comparing `ocr_iiif_tools-0.0.7b0/ocr_iiif_tools/pdf.py` & `ocr_iiif_tools-0.0.8/ocr_iiif_tools/pdf.py`

 * *Files 26% similar despite different names*

```diff
@@ -13,20 +13,22 @@
 import json
 import requests
 from PIL import Image
 from reportlab.lib.colors import *
 from tqdm import tqdm
 from reportlab.lib import colors
 import random
+from bs4 import BeautifulSoup
 
 # %% ../nbs/pdf.ipynb 4
 class PdfClient:
     """PDFを操作するクラス"""
 
     tmp_dir = "tmp"
+    debug = False
 
     def __init__(self):
         """
         コンストラクタ。一時フォルダを作成します。
         """
         os.makedirs(self.tmp_dir, exist_ok=True)
 
@@ -67,74 +69,139 @@
 
         if not os.path.exists(path):
             os.makedirs(os.path.dirname(path), exist_ok=True)
             df = requests.get(iiif_manifest_url).json()
             json.dump(df, open(path, "w"), ensure_ascii=False, indent=4)
 
         return self.get_manifest_json_from_path(path)
-    
-    def _initialize_canvas(self, newPdfPage, image_size):
+
+    def getHiImagePath(self, image_url):
+        tmp = image_url.replace("https://clioimg.hi.u-tokyo.ac.jp/viewer/api/image/idata", "").replace(".jpg", "")
+        spl = tmp.split("%2F")
+        image_url = "https://clioimg.hi.u-tokyo.ac.jp/viewer/image/idata" # 850/8500/58/0201/0001.tif
+
+        for t in spl:
+            if t != "":
+                image_url += "/" + t
+
+        image_url += ".tif"
+        
+        image_hash = hashlib.md5(image_url.encode()).hexdigest()
+        img_path = f"{self.task_tmp_dir}/images/{image_hash}.tif"
+        
+
+        if not os.path.exists(img_path):
+            os.makedirs(os.path.dirname(img_path), exist_ok=True)
+            df = requests.get(image_url).content
+            open(img_path, "wb").write(df)
+
+        return img_path
+
+    def set_image(self, newPdfPage, im, img_path, page_size):
+        is_copressed = self.is_compressed
+        compress_quality = self.compress_quality
+
+        if is_copressed:
+            im_jpg_path = img_path + "_resized.jpg"
+            im.save(im_jpg_path, optimize=True, quality=compress_quality)
+        else:
+            im_jpg_path = img_path
+
+        newPdfPage.drawImage(im_jpg_path,0,0,width=page_size['width'], height=page_size['height'], preserveAspectRatio=True)
+
+    def get_scale(self, page_size, image_width, image_height):
+
+        p_height = page_size['height'] / image_height
+        p_width = page_size['width'] / image_width
+        
+        return min(p_height, p_width)
+
+
+    def get_canvases(self):
+        canvas_range = self.canvas_range
+        iiif_manifest_url = self.iiif_manifest_url
+        iiif_manifest_path = self.iiif_manifest_path
+
+        if iiif_manifest_url is not None:
+            
+            manifest_json = self.get_manifest_json_from_url(iiif_manifest_url)
+
+        elif iiif_manifest_path is not None:
+            manifest_json = self.get_manifest_json_from_path(iiif_manifest_path)
+
+        contexts = manifest_json["@context"]
+        if not isinstance(contexts, list):
+            contexts = [contexts]
+        if contexts[0] != "http://iiif.io/api/presentation/3/context.json":
+            raise Exception("Not supported context")
+        
+        canvases = manifest_json["items"]
+
+        if canvas_range is not None:
+            canvases = canvases[canvas_range[0]:canvas_range[1]]
+
+        return canvases
+
+    def download_image(self, image_url, i):
         """
-        Canvasの初期化を行います。ページサイズを設定し、そのサイズを返します。
+        イメージをダウンロードし、そのパスを返します。
 
         Parameters
         ----------
-        newPdfPage : reportlab.pdfgen.canvas.Canvas
-            初期化するCanvas
-        image_size : tuple
-            画像のサイズ (width, height)
+        image_url : str
+            ダウンロードするイメージのURL
+        i : int
+            イメージのインデックス
 
         Returns
         -------
-        dict
-            ページサイズ {'width': float, 'height': float}
+        str
+            ダウンロードしたイメージのパス
         """
-        image_width, image_height = image_size
-        ratio = image_width / image_height
-        page_size = {}
-
-        if ratio > 1.0:
-            newPdfPage.setPageSize(landscape(A4))
-            page_size['width'], page_size['height'] = landscape(A4)
+        if self.image_download_dir is None:
+            image_hash = hashlib.md5(image_url.encode()).hexdigest()
+            img_path = f"{self.task_tmp_dir}/images/{image_hash}.jpg"
         else:
-            newPdfPage.setPageSize(A4)
-            page_size['width'], page_size['height'] = A4
+            img_path = f"{self.image_download_dir}/{str(i+1).zfill(4)}.jpg"
 
-        return page_size
-    
-    def _draw_on_canvas(self, newPdfPage, annotations, image_size, page_size, font_page_limit, default_color, default_alpha, default_main_color, default_main_alpha):
+        if not os.path.exists(img_path):
+            os.makedirs(os.path.dirname(img_path), exist_ok=True)
+            image_content = requests.get(image_url).content
+            with open(img_path, "wb") as img_file:
+                img_file.write(image_content)
+
+        return img_path
+
+    def get_img_path(self, iiif_canvas, i):
         """
-        Canvasに画像とアノテーションを描画します。
+        イメージのパスを取得します。もし特定のURLが含まれている場合は特定のメソッドを呼び出し、
+        そうでなければ画像をダウンロードしてそのパスを返します。
 
         Parameters
         ----------
-        newPdfPage : reportlab.pdfgen.canvas.Canvas
-            描画するCanvas
-        annotations : list
-            描画するアノテーションのリスト
-        image_size : tuple
-            画像のサイズ (width, height)
-        page_size : dict
-            ページのサイズ {'width': float, 'height': float}
-        font_page_limit : int
-            フォントサイズの上限
-        default_color : str
-            デフォルトの色
-        default_alpha : float
-            デフォルトの透明度
-        default_main_color : str
-            メインテキストのデフォルトの色
-        default_main_alpha : float
-            メインテキストのデフォルトの透明度
+        iiif_canvas : dict
+            IIIFマニフェストのキャンバス
+        i : int
+            キャンバスのインデックス
+
+        Returns
+        -------
+        str
+            イメージのパス
         """
-        # ... annotation drawing code ...
+        image_url = iiif_canvas["items"][0]["items"][0]["body"]["id"]
+
+        if "https://clioimg.hi.u-tokyo.ac.jp/viewer/api/image/idata" in image_url:
+            img_path = self.getHiImagePath(image_url)
+        else:
+            img_path = self.download_image(image_url, i)
 
-    def convert_iiif2pdf(self, output_path, iiif_manifest_url=None, iiif_manifest_path=None, post_text_size=5,
-                         default_color="red", default_alpha=0.5, default_main_color="gray", default_main_alpha=0.5,
-                         canvas_range=None, font_page_limit=24, task_id="base"):
+        return img_path
+
+    def convert_iiif2pdf(self, output_path, iiif_manifest_url = None, iiif_manifest_path = None, post_text_size = 0, default_color = "red", default_alpha=0.0, default_main_color = "gray", default_main_alpha = 0.0, canvas_range=None, font_page_limit = 24, task_id = "base", compress_quality = 100, image_download_dir = None, is_copressed = False, dictionary = {}, with_ocr = True):
         """
         IIIFマニフェストをPDFに変換します。
 
         Parameters
         ----------
         output_path : str
             出力するPDFのパス
@@ -156,255 +223,178 @@
             キャンバスの範囲 [start, end]
         font_page_limit : int, optional
             フォントサイズの上限
         task_id : str, optional
             タスクID
         compress_quality : int, optional
             圧縮率
+        image_download_dir : str, optional
+            画像をダウンロードするディレクトリ
+        is_copressed : bool, optional
+            画像を圧縮するかどうか
+        dictionary : dict, optional
+            異体字辞書
+        with_ocr : bool, optional
+            OCRを行うかどうか
         """
-        # ... method content ...
 
         '''
-        newPdfPage = canvas.Canvas(output_path)
-        image_size = (image_width, image_height)
-
-        page_size = self._initialize_canvas(newPdfPage, image_size)
-        self._draw_on_canvas(newPdfPage, annotations, image_size, page_size, font_page_limit,
-                             default_color, default_alpha, default_main_color, default_main_alpha)
-
-        newPdfPage.save()
+        if isItaiji:
+            self.getItaiji()
         '''
-        pass
 
-    def convert_iiif2pdf(self, output_path, iiif_manifest_url = None, iiif_manifest_path = None, post_text_size = 0, default_color = "red", default_alpha=0.0, default_main_color = "gray", default_main_alpha = 0.0, canvas_range=None, font_page_limit = 24, task_id = "base", compress_quality = 10, image_download_dir = None):
-        """
-        IIIFマニフェストをPDFに変換します。
+        self.task_tmp_dir = f"{self.tmp_dir}/{task_id}"
 
-        Parameters
-        ----------
-        output_path : str
-            出力するPDFのパス
-        iiif_manifest_url : str, optional
-            IIIFマニフェストのURL
-        iiif_manifest_path : str, optional
-            IIIFマニフェストのファイルパス
-        post_text_size : int, optional
-            ポストテキストのサイズ
-        default_color : str, optional
-            デフォルトの色
-        default_alpha : float, optional
-            デフォルトの透明度
-        default_main_color : str, optional
-            メインテキストのデフォルトの色
-        default_main_alpha : float, optional
-            メインテキストのデフォルトの透明度
-        canvas_range : list, optional
-            キャンバスの範囲 [start, end]
-        font_page_limit : int, optional
-            フォントサイズの上限
-        task_id : str, optional
-            タスクID
-        compress_quality : int, optional
-            圧縮率
-        """
+        self.isItaiji = True if dictionary != {} else False
+        self.dictionary = dictionary
+        self.font_page_limit = font_page_limit
+
+        self.post_text_size = post_text_size
+        self.default_color = default_color
+        self.default_alpha = default_alpha
+        self.default_main_color = default_main_color
+        self.default_main_alpha = default_main_alpha
+
+        self.is_compressed = is_copressed
+        self.compress_quality = compress_quality
+
+        self.canvas_range = canvas_range
+        self.iiif_manifest_url = iiif_manifest_url
+        self.iiif_manifest_path = iiif_manifest_path
+
+        self.image_download_dir = image_download_dir
 
         if iiif_manifest_url is None and iiif_manifest_path is None:
             raise Exception('iiif_manifest_url or iiif_manifest_path must be specified.')
 
         # pass
         newPdfPage = canvas.Canvas(output_path)
 
         pdfmetrics.registerFont(UnicodeCIDFont('HeiseiKakuGo-W5', isVertical=True))
 
-        if iiif_manifest_url is not None:
-            
-            manifest_json = self.get_manifest_json_from_url(iiif_manifest_url)
-
-        elif iiif_manifest_path is not None:
-            manifest_json = self.get_manifest_json_from_path(iiif_manifest_path)
-
-        contexts = manifest_json["@context"]
-        if not isinstance(contexts, list):
-            contexts = [contexts]
-        if contexts[0] != "http://iiif.io/api/presentation/3/context.json":
-            raise Exception("Not supported context")
-        
-        canvases = manifest_json["items"]
-
-        if canvas_range is not None:
-            canvases = canvases[canvas_range[0]:canvas_range[1]]
+        canvases = self.get_canvases()
 
         # for iiif_canvas in tqdm(canvases):
         for i in tqdm(range(len(canvases))):
             iiif_canvas = canvases[i]
 
-            image_url = iiif_canvas["items"][0]["items"][0]["body"]["id"]
-
-            if image_download_dir is None:
-                image_hash = hashlib.md5(image_url.encode()).hexdigest()
-                img_path = f"{self.tmp_dir}/{task_id}/images/{image_hash}.jpg"
-            else:
-                img_path = f"{image_download_dir}/{str(i+1).zfill(4)}.jpg"
-
-            if not os.path.exists(img_path):
-                os.makedirs(os.path.dirname(img_path), exist_ok=True)
-                df = requests.get(image_url).content
-                open(img_path, "wb").write(df)
+            img_path = self.get_img_path(iiif_canvas, i)
 
             # fliped_img_path = img_path + ".fliped.jpg"
             im = Image.open(img_path)
-            image_original_width, image_original_height = im.size
-            image_width = image_original_width
-            image_height = image_original_height
-
-            canvas_width = iiif_canvas["width"]
-            canvas_height = iiif_canvas["height"]
-
-            '''
-            print("image_width", image_width)
-            print("image_height", image_height)
-
-            print("canvas_width", canvas_width)
-            print("canvas_height", canvas_height)
-
-            print("----")
-            '''
-
-            # 
-            image_width = canvas_width
-            image_height = canvas_height
+            image_width, image_height = im.size
 
             # ページサイズ
             page_size = {}
 
             ratio = image_width / image_height
 
 
-            page_size = {}
-
-
             if ratio > 1.0 :
                 newPdfPage.setPageSize(landscape(A4))
                 page_size['width'], page_size['height'] = landscape(A4)
             else:
                 newPdfPage.setPageSize(A4)
                 page_size['width'], page_size['height'] = A4
 
             # 画像のほうが横に長い
-
-            p_height = page_size['height'] / image_height
-            p_width = page_size['width'] / image_width
-
-            '''
-            print("p_height", p_height)
-            print("p_width", p_width)
-            
-            '''
             
             # 小さい方のスケールを維持する
-            scale = min(p_height, p_width)
+            scale = self.get_scale(page_size, image_width, image_height)
 
-            '''
-            image_page_height = image_height * scale
-            image_page_width = image_width * scale
-            
-            print("image_original_height", image_height)
-            print("image_original_width", image_width)
-
-            print("image_page_height", image_page_height)
-            print("image_page_width", image_page_width)
-            '''
-
-            '''
-            im_resized = im.resize((int(image_page_width), int(image_page_height))) # , Image.LANCZOS
-            
-            im_resized_path = img_path + ".resized.jpg"
-            
-            im_resized.save(im_resized_path)
-
-            im_webp_path = img_path + ".webp"
-
-            im.save(im_webp_path, optimize=True, quality=comp_q)
-            '''
-
-            # 画像が大きい場合は圧縮する
-            if image_original_height > 1024:
-                im_jpg_path = img_path + "_comp.jpg"
-                im.save(im_jpg_path, optimize=True, quality=compress_quality)
-            else:
-                im_jpg_path = img_path
+            self.set_image(newPdfPage, im, img_path, page_size)
 
-            # newPdfPage.drawImage(im_resized_path,0,0,width=page_size['width'], height=page_size['height'], preserveAspectRatio=True)
-            # newPdfPage.drawImage(im_webp_path,0,0,width=page_size['width'], height=page_size['height'], preserveAspectRatio=True)
-            newPdfPage.drawImage(im_jpg_path,0,0,width=page_size['width'], height=page_size['height'], preserveAspectRatio=True)
+            if with_ocr:
+                self.appendOcr(newPdfPage, scale, page_size, iiif_canvas, image_width, image_height)
+                
 
-            offset_page_x = (page_size['width'] - image_width * scale) / 2
-            offset_page_y = (page_size['height'] - image_height * scale) / 2
-
-            annotations = iiif_canvas["annotations"][0]["items"]
+            newPdfPage.showPage()
 
-            sorted_annotations = self.sort_annotation(annotations)
+        newPdfPage.save()
 
-            prev_group = None
+    def appendOcr(self, newPdfPage, scale, page_size, iiif_canvas, image_width, image_height):
+        dictionary = self.dictionary
+        font_page_limit = self.font_page_limit
+
+        post_text_size = self.post_text_size
+        default_main_alpha = self.default_main_alpha
+        default_color = self.default_color
+        default_alpha = self.default_alpha
+        default_main_color = self.default_main_color
+
+        offset_page_x = (page_size['width'] - image_width * scale) / 2
+        offset_page_y = (page_size['height'] - image_height * scale) / 2
+
+        annotations = iiif_canvas["annotations"][0]["items"]
+
+        sorted_annotations = self.sort_annotation(annotations)
+
+        prev_group = None
+
+        for i in range(len(sorted_annotations)):
+            row = sorted_annotations[i]
+            x1 = row["x1"]
+            y1 = row["y1"]
+            x2 = row["x2"]
+            
+            text_value = row["text"]
+            if self.isItaiji:
+                ts = list(text_value)
+                for j in range(len(ts)):
+                    if ts[j] in dictionary:
+                        ts[j] = dictionary[ts[j]]
+                text_value = "".join(ts)
 
-            for i in range(len(sorted_annotations)):
-                row = sorted_annotations[i]
-                x1 = row["x1"]
-                y1 = row["y1"]
-                x2 = row["x2"]
-                text_value = row["text"]
-                w = row["w"]
-                h = row["h"]
 
-                if len(text_value) == 0:
-                    continue
+            w = row["w"]
+            h = row["h"]
 
-                anchor_y = image_height - y1
-                anchor_x = x1
+            if len(text_value) == 0:
+                continue
 
-                text_height = h / len(text_value)
-                font_image_size = text_height
+            anchor_y = image_height - y1
+            anchor_x = x1
 
-                font_page_size = font_image_size * scale
+            text_height = h / len(text_value)
+            font_image_size = text_height
 
-                if font_page_size > font_page_limit:
-                    # continue
-                    font_page_size = font_page_limit
+            font_page_size = font_image_size * scale
 
-                newPdfPage.setFont('HeiseiKakuGo-W5', font_page_size)
+            if font_page_size > font_page_limit:
+                # continue
+                font_page_size = font_page_limit
 
-                preText = ""
+            newPdfPage.setFont('HeiseiKakuGo-W5', font_page_size)
 
-                postText = self.getPostText(i, sorted_annotations, size=post_text_size)
+            preText = ""
 
-                start = (anchor_y + text_height * len(preText))
+            postText = self.getPostText(i, sorted_annotations, size=post_text_size)
 
-                fixed_text_value = preText + text_value + postText
+            start = (anchor_y + text_height * len(preText))
 
-                color, alpha = self.get_color(prev_group, row, default_color=default_color, default_alpha=default_alpha, default_main_color=default_main_color, default_main_alpha=default_main_alpha)
+            fixed_text_value = preText + text_value + postText
 
-                newPdfPage.setFillColor(color, alpha=alpha)
+            color, alpha = self.get_color(prev_group, row, default_color=default_color, default_alpha=default_alpha, default_main_color=default_main_color, default_main_alpha=default_main_alpha)
 
-                # newPdfPage.drawString(scale * anchor_x, scale * start, fixed_text_value)
+            newPdfPage.setFillColor(color, alpha=alpha)
 
-                x_start = anchor_x + font_image_size / 2
-                x_start = (x1 + x2) / 2
+            # newPdfPage.drawString(scale * anchor_x, scale * start, fixed_text_value)
 
-                x_page_start = offset_page_x + scale * x_start
-                y_page_start = offset_page_y + scale * start
+            x_start = anchor_x + font_image_size / 2
+            x_start = (x1 + x2) / 2
 
-                newPdfPage.drawString(x_page_start, y_page_start, fixed_text_value)
+            x_page_start = offset_page_x + scale * x_start
+            y_page_start = offset_page_y + scale * start
 
-                prev_group = row["group"]
+            newPdfPage.drawString(x_page_start, y_page_start, fixed_text_value)
 
-                # break
+            prev_group = row["group"]
 
-            newPdfPage.showPage()
+            # break
 
-        newPdfPage.save()
 
     def get_color(self, prev_group, row, default_color = "red", default_alpha = 0.5, default_main_color = "gray", default_main_alpha = 0.5):
         color = default_color
         alpha = default_alpha
 
         if prev_group != row["group"]:
             # Get a list of color names from the colors module
@@ -589,17 +579,17 @@
                             # rows2.append(obj)
             
             else:
                 for i, obj in enumerate(rows):
                     obj["group"] = f"{text_type}-{i+1}"
                     rows2.append(obj)
 
-        
-        with open(f"{self.tmp_dir}/sorted_annotaions.json", "w") as f:
-            json.dump(rows2, f, indent=4, ensure_ascii=False)
+        if self.debug:
+            with open(f"{self.tmp_dir}/sorted_annotaions.json", "w") as f:
+                json.dump(rows2, f, indent=4, ensure_ascii=False)
         
 
         return rows2
 
 
     def getPostText(self, i, rows, size=5):
         current_type = rows[i]["group"]
@@ -633,7 +623,36 @@
         for i, group in enumerate(groups):
             # print(f"Group2 {i+1}:")
             # print(json.dumps(group, indent=4, ensure_ascii=False))
             pass
         '''
 
         return groups
+
+    @staticmethod    
+    def getHiItaiji(): # self
+        itaijiMap = {}
+
+        url = "https://wwwap.hi.u-tokyo.ac.jp/ships/itaiji_list.jsp"
+        r = requests.get(url)
+        soup = BeautifulSoup(r.content, "html.parser")
+
+        trs = soup.find_all("tr")
+        for tr in trs:
+            tds = tr.find_all("td")
+
+            if len(tds) != 3:
+                continue
+
+            w_new = tds[1].text
+            ws_old = tds[2].text.split("\u3000")
+
+            # print(w_new, w_old)
+
+            for w_old in ws_old:
+                if w_old != "\xa0":
+                    itaijiMap[w_old] = w_new
+
+        # return itaijiMap
+        # self.itaijiMap = itaijiMap
+        return itaijiMap
+
```

### Comparing `ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/PKG-INFO` & `ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ocr-iiif-tools
-Version: 0.0.7b0
+Version: 0.0.8
 Summary: UNKNOWN
 Home-page: https://github.com/nakamura196/ocr_iiif_tools
 Author: Satoru
 Author-email: you@example.com
 License: Apache Software License 2.0
 Keywords: nbdev jupyter notebook python
 Platform: UNKNOWN
```

### Comparing `ocr_iiif_tools-0.0.7b0/ocr_iiif_tools.egg-info/SOURCES.txt` & `ocr_iiif_tools-0.0.8/ocr_iiif_tools.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `ocr_iiif_tools-0.0.7b0/settings.ini` & `ocr_iiif_tools-0.0.8/settings.ini`

 * *Files 14% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 [DEFAULT]
 # All sections below are required unless otherwise specified.
 # See https://github.com/fastai/nbdev/blob/master/settings.ini for examples.
 
 ### Python library ###
 repo = ocr_iiif_tools
 lib_name = %(repo)s
-version = 0.0.7.beta
+version = 0.0.8
 min_python = 3.7
 license = apache2
 black_formatting = False
 
 ### nbdev ###
 doc_path = _docs
 lib_path = ocr_iiif_tools
@@ -34,10 +34,10 @@
 description = 
 keywords = nbdev jupyter notebook python
 language = English
 status = 3
 user = nakamura196
 
 ### Optional ###
-requirements = reportlab==3.6.9 requests tqdm
+requirements = reportlab requests tqdm
 # dev_requirements = 
 # console_scripts =
```

### Comparing `ocr_iiif_tools-0.0.7b0/setup.py` & `ocr_iiif_tools-0.0.8/setup.py`

 * *Files identical despite different names*


# Comparing `tmp/get_eyedata-1.2.1-py3-none-any.whl.zip` & `tmp/get_eyedata-1.2.2-py3-none-any.whl.zip`

## zipinfo {}

```diff
@@ -1,11 +1,11 @@
-Zip file size: 5500 bytes, number of entries: 9
+Zip file size: 5908 bytes, number of entries: 9
 -rw-rw-rw-  2.0 fat        6 b- defN 23-Jun-05 08:24 get_eyedata/__init__.py
--rw-rw-rw-  2.0 fat     1581 b- defN 23-Jun-05 08:24 get_eyedata/frame_utils.py
+-rw-rw-rw-  2.0 fat     2452 b- defN 23-Jun-28 06:35 get_eyedata/frame_utils.py
 -rw-rw-rw-  2.0 fat        0 b- defN 23-Jun-05 08:24 get_eyedata/ow2.py
--rw-rw-rw-  2.0 fat     3757 b- defN 23-Jun-23 06:17 get_eyedata/valo.py
--rw-rw-rw-  2.0 fat     1091 b- defN 23-Jun-23 06:23 get_eyedata-1.2.1.dist-info/LICENCE
--rw-rw-rw-  2.0 fat     1816 b- defN 23-Jun-23 06:23 get_eyedata-1.2.1.dist-info/METADATA
--rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-23 06:23 get_eyedata-1.2.1.dist-info/WHEEL
--rw-rw-rw-  2.0 fat       12 b- defN 23-Jun-23 06:23 get_eyedata-1.2.1.dist-info/top_level.txt
-?rw-rw-r--  2.0 fat      714 b- defN 23-Jun-23 06:23 get_eyedata-1.2.1.dist-info/RECORD
-9 files, 9069 bytes uncompressed, 4264 bytes compressed:  53.0%
+-rw-rw-rw-  2.0 fat     3871 b- defN 23-Jun-28 06:35 get_eyedata/valo.py
+-rw-rw-rw-  2.0 fat     1091 b- defN 23-Jun-28 07:53 get_eyedata-1.2.2.dist-info/LICENCE
+-rw-rw-rw-  2.0 fat     1869 b- defN 23-Jun-28 07:53 get_eyedata-1.2.2.dist-info/METADATA
+-rw-rw-rw-  2.0 fat       92 b- defN 23-Jun-28 07:53 get_eyedata-1.2.2.dist-info/WHEEL
+-rw-rw-rw-  2.0 fat       12 b- defN 23-Jun-28 07:53 get_eyedata-1.2.2.dist-info/top_level.txt
+?rw-rw-r--  2.0 fat      714 b- defN 23-Jun-28 07:53 get_eyedata-1.2.2.dist-info/RECORD
+9 files, 10107 bytes uncompressed, 4672 bytes compressed:  53.8%
```

## zipnote {}

```diff
@@ -6,23 +6,23 @@
 
 Filename: get_eyedata/ow2.py
 Comment: 
 
 Filename: get_eyedata/valo.py
 Comment: 
 
-Filename: get_eyedata-1.2.1.dist-info/LICENCE
+Filename: get_eyedata-1.2.2.dist-info/LICENCE
 Comment: 
 
-Filename: get_eyedata-1.2.1.dist-info/METADATA
+Filename: get_eyedata-1.2.2.dist-info/METADATA
 Comment: 
 
-Filename: get_eyedata-1.2.1.dist-info/WHEEL
+Filename: get_eyedata-1.2.2.dist-info/WHEEL
 Comment: 
 
-Filename: get_eyedata-1.2.1.dist-info/top_level.txt
+Filename: get_eyedata-1.2.2.dist-info/top_level.txt
 Comment: 
 
-Filename: get_eyedata-1.2.1.dist-info/RECORD
+Filename: get_eyedata-1.2.2.dist-info/RECORD
 Comment: 
 
 Zip file comment:
```

## get_eyedata/frame_utils.py

```diff
@@ -43,7 +43,33 @@
         bottom_half = image[corrd:, :]
     else:
         # 動画を上下で半分に分割
         top_half = image[:2160 // 2, :]
         bottom_half = image[2160 // 2:, :]
     
     return top_half,bottom_half
+
+from moviepy.editor import VideoFileClip
+import os
+
+from moviepy.editor import VideoFileClip
+import os
+
+from moviepy.editor import VideoFileClip
+import os
+
+def make_displayonly_video(video_path:str, output_dir:str='displayonly_video'):
+    clip = VideoFileClip(video_path)
+    cropped_clip = clip.crop(y1=0, y2=clip.h // 2)  # cropping the upper half of the video
+    
+    os.makedirs(output_dir, exist_ok=True)  # create the directory if it doesn't exist
+    
+    output_path = os.path.join(output_dir, os.path.basename(video_path))
+    base_name, ext = os.path.splitext(output_path)
+    i = 1
+    while os.path.exists(output_path):
+        print(f"{output_path} already exists, saving as {base_name}{i}.mp4 instead.")
+        output_path = f"{base_name}{i}.mp4"
+        i += 1
+
+    cropped_clip.write_videofile(output_path, codec='libx264')
+
```

## get_eyedata/valo.py

```diff
@@ -1,8 +1,8 @@
-from .frame_utils import cog, sep_y, binarize_image
+from .frame_utils import cog, sep_y, binarize_image, make_displayonly_video
 import os 
 import cv2
 from tqdm import tqdm
 import numpy as np
 import pandas as pd
 from dataclasses import dataclass
 
@@ -61,15 +61,15 @@
 def check(file_path:str):
     if os.path.exists(file_path):
         return True
     else:
         print('FileNotFoundError')
         return False
 
-def make_dataset(video_path:str, save:bool = True):
+def make_dataset(video_path:str, save:bool = True, get_display:bool = True):
     #動画の読み込み
     mov_file = os.path.normpath(video_path)
     check(mov_file)
     cap = cv2.VideoCapture(mov_file)
     total_frames = int(cap.get(cv2.CAP_PROP_FRAME_COUNT))
     print(f'total_frames:{total_frames}')
     #中心座標を格納するリスト
@@ -100,12 +100,14 @@
         else:
             print(f'error occurd at frame{frame_id}')
             break   
     cap.release()
     df = pd.DataFrame({'frame_ids':frame_ids,'x':eye_x,'y':eye_y,'roi':rois})
     if save:
         df.to_csv('eye_data.csv',index=False)
+    if get_display:
+        make_displayonly_video(video_path)
     return df
 
 if __name__ == "__main__":
     df = make_dataset('F:\git-repo\get_eyedata\data\test.mkv')
     print(df)
```

## Comparing `get_eyedata-1.2.1.dist-info/LICENCE` & `get_eyedata-1.2.2.dist-info/LICENCE`

 * *Files identical despite different names*

## Comparing `get_eyedata-1.2.1.dist-info/METADATA` & `get_eyedata-1.2.2.dist-info/METADATA`

 * *Files 3% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: get-eyedata
-Version: 1.2.1
+Version: 1.2.2
 Summary: gat gaze data form record.
 Home-page: https://github.com/ikrfun/get_eyedata
 Download-URL: https://github.com/ikrfun/get_eyedata
 Author: ikrfun
 Author-email: t.nobuto130625@gmail.com
 Maintainer: ikrfun
 Maintainer-email: t.nobuto130625@gmail.com
@@ -23,15 +23,15 @@
 Requires-Dist: pandas (>=2.0.2)
 Requires-Dist: setuptools (>=67.8.0)
 Requires-Dist: tqdm (>=4.65.0)
 Requires-Dist: utils (>=1.0.1)
 
 # Get-eyedata
 
-this library is an application that allows you to track objects in a video file and save the tracking data to a CSV file.
+this library is an application that allows you to track objects in a video file and save the tracking data to pandas dataframe 
 
 ## Installation
 ---
 you can use pip to install get-eyedata.
 ```bash
 pip install get-eyedata
 ```
@@ -55,12 +55,14 @@
 To use mekeing eye dataset, run the following command in your terminal
 
 ```python
 from get_eyedata import valo
 
 # valo_df is pandas dataframe
 valo_df = valo.make_dataset('{video-file-path}')
+# save as csv
+valo_df.to_csv('out-csv-path')
 ```
 ---
 ## License
 
 This project is licensed under the MIT License. See the `LICENSE` file for more information.
```

## Comparing `get_eyedata-1.2.1.dist-info/RECORD` & `get_eyedata-1.2.2.dist-info/RECORD`

 * *Files 17% similar despite different names*

```diff
@@ -1,9 +1,9 @@
 get_eyedata/__init__.py,sha256=rqUtJyMLicobcyhmr74TepjmUQAEmlazKT3vjV_n3aA,6
-get_eyedata/frame_utils.py,sha256=UBuyN_aDdRql7TOv8E0Hjut5UqBlz41gYsG01aTmlFc,1581
+get_eyedata/frame_utils.py,sha256=t-mazRo1bOlR9TqUGLnJJKesVewPyyQpxfC8u9loeBk,2452
 get_eyedata/ow2.py,sha256=47DEQpj8HBSa-_TImW-5JCeuQeRkm5NMpJWZG3hSuFU,0
-get_eyedata/valo.py,sha256=PqrMdKP8scFrlIFQN5qutlEaPgPJID7iT_lh5Z9PRZY,3757
-get_eyedata-1.2.1.dist-info/LICENCE,sha256=44r0hK-BnpFZTBiPxTYe52HFlT034sEPBfHrJyaNI0g,1091
-get_eyedata-1.2.1.dist-info/METADATA,sha256=6tCoBF9jVlA_aRzUwe0GogbdbWcuyW0-2BjxZO2BqKQ,1816
-get_eyedata-1.2.1.dist-info/WHEEL,sha256=2wepM1nk4DS4eFpYrW1TTqPcoGNfHhhO_i5m4cOimbo,92
-get_eyedata-1.2.1.dist-info/top_level.txt,sha256=zlueM7ZefajCSIgOyib56hk_6HWx15EsED6S68g0mWE,12
-get_eyedata-1.2.1.dist-info/RECORD,,
+get_eyedata/valo.py,sha256=fuaFnwBjdVxHHgDHIfPnhY4ulGesBKH63CdNxMfSfXE,3871
+get_eyedata-1.2.2.dist-info/LICENCE,sha256=44r0hK-BnpFZTBiPxTYe52HFlT034sEPBfHrJyaNI0g,1091
+get_eyedata-1.2.2.dist-info/METADATA,sha256=wVGH4Xu3Zazvbtf4QRsVP2sTzS13i2S4EKxv_7v75F4,1869
+get_eyedata-1.2.2.dist-info/WHEEL,sha256=2wepM1nk4DS4eFpYrW1TTqPcoGNfHhhO_i5m4cOimbo,92
+get_eyedata-1.2.2.dist-info/top_level.txt,sha256=zlueM7ZefajCSIgOyib56hk_6HWx15EsED6S68g0mWE,12
+get_eyedata-1.2.2.dist-info/RECORD,,
```


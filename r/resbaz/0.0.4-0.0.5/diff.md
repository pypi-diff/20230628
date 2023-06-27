# Comparing `tmp/resbaz-0.0.4.tar.gz` & `tmp/resbaz-0.0.5.tar.gz`

## Comparing `resbaz-0.0.4.tar` & `resbaz-0.0.5.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 resbaz-0.0.4/src/resbaz/__init__.py
--rw-r--r--   0        0        0     1117 2020-02-02 00:00:00.000000 resbaz-0.0.4/src/resbaz/certificate.py
--rw-r--r--   0        0        0     1799 2020-02-02 00:00:00.000000 resbaz-0.0.4/.gitignore
--rw-r--r--   0        0        0     1074 2020-02-02 00:00:00.000000 resbaz-0.0.4/LICENSE
--rw-r--r--   0        0        0       80 2020-02-02 00:00:00.000000 resbaz-0.0.4/README.md
--rw-r--r--   0        0        0      501 2020-02-02 00:00:00.000000 resbaz-0.0.4/pyproject.toml
--rw-r--r--   0        0        0      513 2020-02-02 00:00:00.000000 resbaz-0.0.4/PKG-INFO
+-rw-r--r--   0        0        0        0 2020-02-02 00:00:00.000000 resbaz-0.0.5/src/resbaz/__init__.py
+-rw-r--r--   0        0        0     1061 2020-02-02 00:00:00.000000 resbaz-0.0.5/src/resbaz/certificate.py
+-rw-r--r--   0        0        0     1799 2020-02-02 00:00:00.000000 resbaz-0.0.5/.gitignore
+-rw-r--r--   0        0        0     1074 2020-02-02 00:00:00.000000 resbaz-0.0.5/LICENSE
+-rw-r--r--   0        0        0       80 2020-02-02 00:00:00.000000 resbaz-0.0.5/README.md
+-rw-r--r--   0        0        0      501 2020-02-02 00:00:00.000000 resbaz-0.0.5/pyproject.toml
+-rw-r--r--   0        0        0      513 2020-02-02 00:00:00.000000 resbaz-0.0.5/PKG-INFO
```

### Comparing `resbaz-0.0.4/src/resbaz/certificate.py` & `resbaz-0.0.5/src/resbaz/certificate.py`

 * *Files 23% similar despite different names*

```diff
@@ -1,23 +1,21 @@
 def get_certificate(name):
   from PIL import Image, ImageDraw, ImageFont
   import pandas as pd
   from google.colab import files
   import os
-  os.system("wget https://dl.dropboxusercontent.com/s/mxgxuqe9ejptl2k/Certificate.png -O Certificate.png --quiet")
+  os.system("wget https://dl.dropboxusercontent.com/s/pb9sf1jwxvt5wf7/Certificate.png -O Certificate.png --quiet")
   os.system("wget https://dl.dropboxusercontent.com/s/hpd7246qdczd5wq/bellania.ttf?dl=0 -O bellania.ttf --quiet")
   url = "https://drive.google.com/uc?export=download&id=1MUlHNAjZ_n40ciSW4f0enZgnz2AG5ilI"
   form = pd.read_excel(url)
   name_list = form['Name'].to_list()
   if name in name_list:
     im = Image.open("Certificate.png")
     d = ImageDraw.Draw(im)
-    # location = (360, 350)
-    W, H = (960, 750)
-    # text_color = (0, 0, 0)
+    W, H = (1289, 968)
     font = ImageFont.truetype("bellania.ttf", 25)
     w,h = font.getsize(name)
     d.text(((W-w)/2,(H-h)/2), name, font=font, fill="black")
     # d.text(location, name, fill=text_color, font=font)
     im.save(f"certificate_{name}.pdf")
     print(f"Congratulations {name}, your certificate is ready!")
     files.download(f"certificate_{name}.pdf")
```

### Comparing `resbaz-0.0.4/.gitignore` & `resbaz-0.0.5/.gitignore`

 * *Files identical despite different names*

### Comparing `resbaz-0.0.4/LICENSE` & `resbaz-0.0.5/LICENSE`

 * *Files identical despite different names*

### Comparing `resbaz-0.0.4/PKG-INFO` & `resbaz-0.0.5/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: resbaz
-Version: 0.0.4
+Version: 0.0.5
 Summary: ResBaz example package
 Project-URL: Homepage, https://resbaz.auckland.ac.nz/
 Author-email: Victor Gambarini <victor.gambarini@auckland.ac.nz>
 License-File: LICENSE
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Operating System :: OS Independent
 Classifier: Programming Language :: Python :: 3
```


# Comparing `tmp/WIDscript-1.2.1.tar.gz` & `tmp/WIDscript-1.2.2.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "WIDscript-1.2.1.tar", last modified: Tue Jun 27 21:41:32 2023, max compression
+gzip compressed data, was "WIDscript-1.2.2.tar", last modified: Tue Jun 27 23:00:12 2023, max compression
```

## Comparing `WIDscript-1.2.1.tar` & `WIDscript-1.2.2.tar`

### file list

```diff
@@ -1,16 +1,14 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 21:41:32.911864 WIDscript-1.2.1/
--rw-rw-rw-   0        0        0        0 2023-06-19 20:14:16.000000 WIDscript-1.2.1/LICENSE
--rw-rw-rw-   0        0        0      520 2023-06-27 21:41:32.911864 WIDscript-1.2.1/PKG-INFO
--rw-rw-rw-   0        0        0        0 2023-06-19 20:32:17.000000 WIDscript-1.2.1/README.md
--rw-rw-rw-   0        0        0      108 2023-06-21 01:38:12.000000 WIDscript-1.2.1/pyproject.toml
--rw-rw-rw-   0        0        0      661 2023-06-27 21:41:32.913872 WIDscript-1.2.1/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-27 21:41:32.881255 WIDscript-1.2.1/src/
-drwxrwxrwx   0        0        0        0 2023-06-27 21:41:32.897821 WIDscript-1.2.1/src/WIDscript/
--rw-rw-rw-   0        0        0     3466 2023-06-27 21:40:36.000000 WIDscript-1.2.1/src/WIDscript/WIDscript_dpir.py
--rw-rw-rw-   0        0        0     3470 2023-06-27 21:33:05.000000 WIDscript-1.2.1/src/WIDscript/WIDscript_dpirNCNN.py
--rw-rw-rw-   0        0        0    26377 2023-06-27 21:39:10.000000 WIDscript-1.2.1/src/WIDscript/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-27 21:41:32.910855 WIDscript-1.2.1/src/WIDscript.egg-info/
--rw-rw-rw-   0        0        0      520 2023-06-27 21:41:32.000000 WIDscript-1.2.1/src/WIDscript.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      284 2023-06-27 21:41:32.000000 WIDscript-1.2.1/src/WIDscript.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 21:41:32.000000 WIDscript-1.2.1/src/WIDscript.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       10 2023-06-27 21:41:32.000000 WIDscript-1.2.1/src/WIDscript.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-27 23:00:12.908611 WIDscript-1.2.2/
+-rw-rw-rw-   0        0        0        0 2023-06-19 20:14:16.000000 WIDscript-1.2.2/LICENSE
+-rw-rw-rw-   0        0        0      520 2023-06-27 23:00:12.908611 WIDscript-1.2.2/PKG-INFO
+-rw-rw-rw-   0        0        0        0 2023-06-19 20:32:17.000000 WIDscript-1.2.2/README.md
+-rw-rw-rw-   0        0        0      108 2023-06-21 01:38:12.000000 WIDscript-1.2.2/pyproject.toml
+-rw-rw-rw-   0        0        0      661 2023-06-27 23:00:12.909616 WIDscript-1.2.2/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-27 23:00:12.883062 WIDscript-1.2.2/src/
+drwxrwxrwx   0        0        0        0 2023-06-27 23:00:12.894590 WIDscript-1.2.2/src/WIDscript/
+-rw-rw-rw-   0        0        0    26656 2023-06-27 22:59:53.000000 WIDscript-1.2.2/src/WIDscript/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-27 23:00:12.908104 WIDscript-1.2.2/src/WIDscript.egg-info/
+-rw-rw-rw-   0        0        0      520 2023-06-27 23:00:12.000000 WIDscript-1.2.2/src/WIDscript.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      216 2023-06-27 23:00:12.000000 WIDscript-1.2.2/src/WIDscript.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-27 23:00:12.000000 WIDscript-1.2.2/src/WIDscript.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       10 2023-06-27 23:00:12.000000 WIDscript-1.2.2/src/WIDscript.egg-info/top_level.txt
```

### Comparing `WIDscript-1.2.1/PKG-INFO` & `WIDscript-1.2.2/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: WIDscript
-Version: 1.2.1
+Version: 1.2.2
 Summary: A private wrapper made for WIDOWN releases.
 Home-page: https://github.com/pypa/sampleproject
 Author: WIDOWN
 Author-email: widown.ma@gmail.com
 Project-URL: Bug Tracker, https://github.com/pypa/sampleproject/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `WIDscript-1.2.1/setup.cfg` & `WIDscript-1.2.2/setup.cfg`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 2057 4944 7363 7269 7074 0d0a 7665   = WIDscript..ve
-00000020: 7273 696f 6e20 3d20 312e 322e 310d 0a61  rsion = 1.2.1..a
+00000020: 7273 696f 6e20 3d20 312e 322e 320d 0a61  rsion = 1.2.2..a
 00000030: 7574 686f 7220 3d20 5749 444f 574e 0d0a  uthor = WIDOWN..
 00000040: 6175 7468 6f72 5f65 6d61 696c 203d 2077  author_email = w
 00000050: 6964 6f77 6e2e 6d61 4067 6d61 696c 2e63  idown.ma@gmail.c
 00000060: 6f6d 0d0a 6465 7363 7269 7074 696f 6e20  om..description 
 00000070: 3d20 4120 7072 6976 6174 6520 7772 6170  = A private wrap
 00000080: 7065 7220 6d61 6465 2066 6f72 2057 4944  per made for WID
 00000090: 4f57 4e20 7265 6c65 6173 6573 2e0d 0a6c  OWN releases...l
```

### Comparing `WIDscript-1.2.1/src/WIDscript/__init__.py` & `WIDscript-1.2.2/src/WIDscript/__init__.py`

 * *Files 4% similar despite different names*

```diff
@@ -12,14 +12,16 @@
 # If you have acquired this content from any other source, it may not be genuine.
 # It could have been "stolen" or someone could be impersonating us.
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 # WIDscript
 
+# pyright: reportMissingImports=false
+
 from    enum           import Enum
 
 from    vapoursynth    import core
 import  vapoursynth    as vs
 
 core = vs.core
 
@@ -256,22 +258,28 @@
          enableNCNN             : bool = True,
          dpirTileDenominator    : int  = 2,
          dpirDeblocking         : bool = True,
          dpirDenoising          : bool = True,
          dpirDeblockingStrength : int  = 15,
          dpirDenoisingStrength  : int  = 1) :
     
-    if (enableNCNN == False) :
-        from . import WIDscript_dpir as dpir
-        clip = dpir.dpir(clip, dpirTileDenominator, dpirDeblocking, dpirDenoising, dpirDeblockingStrength, dpirDenoisingStrength)
-        return clip
-    else :
-        from . import WIDscript_dpirNCNN as dpir
-        clip = dpir.dpir(clip, dpirTileDenominator, dpirDeblocking, dpirDenoising, dpirDeblockingStrength, dpirDenoisingStrength)
-        return clip
+    if (enableNCNN == True) : from vsdpir_ncnn import DPIR
+    else                    : from vsdpir import DPIR
+        
+    clip = cFormat(clip, cFormatEnum.RGBS)
+
+    # Divide frames by tiles to save on VRAM.
+    dpirTileW = int(clip.width  / dpirTileDenominator)
+    dpirTileH = int(clip.height / dpirTileDenominator)
+
+    # AI Assisted deblocking & denoising.
+    if (dpirDeblocking == True) : clip = DPIR(task='deblock').run(clip, strength=dpirDeblockingStrength, tile_w=dpirTileW, tile_h=dpirTileH)
+    if (dpirDenoising  == True) : clip = DPIR(task='denoise').run(clip, strength=dpirDenoisingStrength,  tile_w=dpirTileW, tile_h=dpirTileH)
+    
+    return clip
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def deband(clip          : vs.VideoNode,
            dbRemBinarize : int = 1500) :
 
     clip_edge = cFormat(clip)
```

### Comparing `WIDscript-1.2.1/src/WIDscript.egg-info/PKG-INFO` & `WIDscript-1.2.2/src/WIDscript.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: WIDscript
-Version: 1.2.1
+Version: 1.2.2
 Summary: A private wrapper made for WIDOWN releases.
 Home-page: https://github.com/pypa/sampleproject
 Author: WIDOWN
 Author-email: widown.ma@gmail.com
 Project-URL: Bug Tracker, https://github.com/pypa/sampleproject/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```


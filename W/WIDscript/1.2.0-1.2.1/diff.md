# Comparing `tmp/WIDscript-1.2.0.tar.gz` & `tmp/WIDscript-1.2.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "WIDscript-1.2.0.tar", last modified: Tue Jun 27 21:20:56 2023, max compression
+gzip compressed data, was "WIDscript-1.2.1.tar", last modified: Tue Jun 27 21:41:32 2023, max compression
```

## Comparing `WIDscript-1.2.0.tar` & `WIDscript-1.2.1.tar`

### file list

```diff
@@ -1,16 +1,16 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 21:20:56.367304 WIDscript-1.2.0/
--rw-rw-rw-   0        0        0        0 2023-06-19 20:14:16.000000 WIDscript-1.2.0/LICENSE
--rw-rw-rw-   0        0        0      520 2023-06-27 21:20:56.367304 WIDscript-1.2.0/PKG-INFO
--rw-rw-rw-   0        0        0        0 2023-06-19 20:32:17.000000 WIDscript-1.2.0/README.md
--rw-rw-rw-   0        0        0      108 2023-06-21 01:38:12.000000 WIDscript-1.2.0/pyproject.toml
--rw-rw-rw-   0        0        0      661 2023-06-27 21:20:56.368809 WIDscript-1.2.0/setup.cfg
-drwxrwxrwx   0        0        0        0 2023-06-27 21:20:56.339265 WIDscript-1.2.0/src/
-drwxrwxrwx   0        0        0        0 2023-06-27 21:20:56.353788 WIDscript-1.2.0/src/WIDscript/
--rw-rw-rw-   0        0        0     3512 2023-06-27 21:18:06.000000 WIDscript-1.2.0/src/WIDscript/WIDscript_dpir.py
--rw-rw-rw-   0        0        0     3516 2023-06-27 21:17:58.000000 WIDscript-1.2.0/src/WIDscript/WIDscript_dpirNCNN.py
--rw-rw-rw-   0        0        0    26342 2023-06-27 21:19:51.000000 WIDscript-1.2.0/src/WIDscript/__init__.py
-drwxrwxrwx   0        0        0        0 2023-06-27 21:20:56.366302 WIDscript-1.2.0/src/WIDscript.egg-info/
--rw-rw-rw-   0        0        0      520 2023-06-27 21:20:56.000000 WIDscript-1.2.0/src/WIDscript.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0      284 2023-06-27 21:20:56.000000 WIDscript-1.2.0/src/WIDscript.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 21:20:56.000000 WIDscript-1.2.0/src/WIDscript.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0       10 2023-06-27 21:20:56.000000 WIDscript-1.2.0/src/WIDscript.egg-info/top_level.txt
+drwxrwxrwx   0        0        0        0 2023-06-27 21:41:32.911864 WIDscript-1.2.1/
+-rw-rw-rw-   0        0        0        0 2023-06-19 20:14:16.000000 WIDscript-1.2.1/LICENSE
+-rw-rw-rw-   0        0        0      520 2023-06-27 21:41:32.911864 WIDscript-1.2.1/PKG-INFO
+-rw-rw-rw-   0        0        0        0 2023-06-19 20:32:17.000000 WIDscript-1.2.1/README.md
+-rw-rw-rw-   0        0        0      108 2023-06-21 01:38:12.000000 WIDscript-1.2.1/pyproject.toml
+-rw-rw-rw-   0        0        0      661 2023-06-27 21:41:32.913872 WIDscript-1.2.1/setup.cfg
+drwxrwxrwx   0        0        0        0 2023-06-27 21:41:32.881255 WIDscript-1.2.1/src/
+drwxrwxrwx   0        0        0        0 2023-06-27 21:41:32.897821 WIDscript-1.2.1/src/WIDscript/
+-rw-rw-rw-   0        0        0     3466 2023-06-27 21:40:36.000000 WIDscript-1.2.1/src/WIDscript/WIDscript_dpir.py
+-rw-rw-rw-   0        0        0     3470 2023-06-27 21:33:05.000000 WIDscript-1.2.1/src/WIDscript/WIDscript_dpirNCNN.py
+-rw-rw-rw-   0        0        0    26377 2023-06-27 21:39:10.000000 WIDscript-1.2.1/src/WIDscript/__init__.py
+drwxrwxrwx   0        0        0        0 2023-06-27 21:41:32.910855 WIDscript-1.2.1/src/WIDscript.egg-info/
+-rw-rw-rw-   0        0        0      520 2023-06-27 21:41:32.000000 WIDscript-1.2.1/src/WIDscript.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0      284 2023-06-27 21:41:32.000000 WIDscript-1.2.1/src/WIDscript.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-27 21:41:32.000000 WIDscript-1.2.1/src/WIDscript.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0       10 2023-06-27 21:41:32.000000 WIDscript-1.2.1/src/WIDscript.egg-info/top_level.txt
```

### Comparing `WIDscript-1.2.0/PKG-INFO` & `WIDscript-1.2.1/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: WIDscript
-Version: 1.2.0
+Version: 1.2.1
 Summary: A private wrapper made for WIDOWN releases.
 Home-page: https://github.com/pypa/sampleproject
 Author: WIDOWN
 Author-email: widown.ma@gmail.com
 Project-URL: Bug Tracker, https://github.com/pypa/sampleproject/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```

### Comparing `WIDscript-1.2.0/setup.cfg` & `WIDscript-1.2.1/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 2057 4944 7363 7269 7074 0d0a 7665   = WIDscript..ve
-00000020: 7273 696f 6e20 3d20 312e 322e 300d 0a61  rsion = 1.2.0..a
+00000020: 7273 696f 6e20 3d20 312e 322e 310d 0a61  rsion = 1.2.1..a
 00000030: 7574 686f 7220 3d20 5749 444f 574e 0d0a  uthor = WIDOWN..
 00000040: 6175 7468 6f72 5f65 6d61 696c 203d 2077  author_email = w
 00000050: 6964 6f77 6e2e 6d61 4067 6d61 696c 2e63  idown.ma@gmail.c
 00000060: 6f6d 0d0a 6465 7363 7269 7074 696f 6e20  om..description 
 00000070: 3d20 4120 7072 6976 6174 6520 7772 6170  = A private wrap
 00000080: 7065 7220 6d61 6465 2066 6f72 2057 4944  per made for WID
 00000090: 4f57 4e20 7265 6c65 6173 6573 2e0d 0a6c  OWN releases...l
```

### Comparing `WIDscript-1.2.0/src/WIDscript/WIDscript_dpir.py` & `WIDscript-1.2.1/src/WIDscript/WIDscript_dpir.py`

 * *Files 3% similar despite different names*

```diff
@@ -13,33 +13,32 @@
 # It could have been "stolen" or someone could be impersonating us.
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 # WIDscript_dpir
 
 from    .              import cFormatEnum
-from    .              import format
+from    .              import cFormat
 
 import  vapoursynth    as vs
 
 core = vs.core
 
 from    vsdpir         import DPIR
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def dpir(clip                   : vs.VideoNode,
-         enableNCNN             : bool = True,
          dpirTileDenominator    : int  = 2,
          dpirDeblocking         : bool = True,
          dpirDenoising          : bool = True,
          dpirDeblockingStrength : int  = 15,
          dpirDenoisingStrength  : int  = 1) :
     
-    clip = format(clip, cFormatEnum.RGBS)
+    clip = cFormat(clip, cFormatEnum.RGBS)
 
     # Divide frames by tiles to save on VRAM.
     dpirTileW = int(clip.width  / dpirTileDenominator)
     dpirTileH = int(clip.height / dpirTileDenominator)
 
     # AI Assisted deblocking & denoising.
     if (dpirDeblocking == True) : clip = DPIR(task='deblock').run(clip, strength=dpirDeblockingStrength, tile_w=dpirTileW, tile_h=dpirTileH)
```

### Comparing `WIDscript-1.2.0/src/WIDscript/WIDscript_dpirNCNN.py` & `WIDscript-1.2.1/src/WIDscript/WIDscript_dpirNCNN.py`

 * *Files 6% similar despite different names*

```diff
@@ -13,33 +13,32 @@
 # It could have been "stolen" or someone could be impersonating us.
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 # WIDscript_dpirNCNN
 
 from    .              import cFormatEnum
-from    .              import format
+from    .              import cFormat
 
 import  vapoursynth    as vs
 
 core = vs.core
 
 from    vsdpir_ncnn    import DPIR
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def dpir(clip                   : vs.VideoNode,
-         enableNCNN             : bool = True,
          dpirTileDenominator    : int  = 2,
          dpirDeblocking         : bool = True,
          dpirDenoising          : bool = True,
          dpirDeblockingStrength : int  = 15,
          dpirDenoisingStrength  : int  = 1) :
     
-    clip = format(clip, cFormatEnum.RGBS)
+    clip = cFormat(clip, cFormatEnum.RGBS)
 
     # Divide frames by tiles to save on VRAM.
     dpirTileW = int(clip.width  / dpirTileDenominator)
     dpirTileH = int(clip.height / dpirTileDenominator)
 
     # AI Assisted deblocking & denoising.
     if (dpirDeblocking == True) : clip = DPIR(task='deblock').run(clip, strength=dpirDeblockingStrength, tile_w=dpirTileW, tile_h=dpirTileH)
```

### Comparing `WIDscript-1.2.0/src/WIDscript/__init__.py` & `WIDscript-1.2.1/src/WIDscript/__init__.py`

 * *Files 2% similar despite different names*

```diff
@@ -37,16 +37,16 @@
 class cFormatEnum(str, Enum):
     YUV420P10 = "YUV420P10",
     YUV420P16 = "YUV420P16",
     RGBS      = "RGBS"
     
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
-def format(clip    : vs.VideoNode,
-           cFormat : cFormatEnum = cFormatEnum.YUV420P16) :
+def cFormat(clip    : vs.VideoNode,
+            cFormat : cFormatEnum = cFormatEnum.YUV420P16) :
         
     match cFormat :
         case "YUV420P10":
             if (clip.format.name != cFormatEnum.YUV420P10) : clip = core.resize.Spline36(clip, format=vs.YUV420P10, matrix_s="709", matrix_in_s="709", dither_type="error_diffusion")
         case "YUV420P16":
             if (clip.format.name != cFormatEnum.YUV420P16) : clip = core.resize.Spline36(clip, format=vs.YUV420P16, matrix_s="709", matrix_in_s="709", dither_type="error_diffusion")
         case "RGBS":
@@ -110,25 +110,25 @@
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def hdr2SDR(clip    : vs.VideoNode,
             dst_max : int   = 110,
             src_max : int   = 4000,
             src_min : float = 0.0050) :
     
-    clip = format(clip)
+    clip = cFormat(clip)
     clip = core.placebo.Tonemap(clip, src_csp=1, dst_csp=0, dst_prim=3, dynamic_peak_detection=1, dst_max=dst_max, src_max=src_max, src_min=src_min, tone_mapping_function=6, tone_mapping_mode=4, gamut_mode=0)
     return clip
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def downscale(clip     : vs.VideoNode,
               dsWidth  : int = 1920,
               dsHeight : int = 1080) :
 
-    clip = format(clip)
+    clip = cFormat(clip)
     clip = SSIM.scale(clip, dsWidth, dsHeight)
     return clip
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def mage(clip             : vs.VideoNode,
          thsxdxMultiplier : float = 0.65) :
@@ -136,15 +136,15 @@
     """## MAGE - Managing All Grain Elegantly, made by Clybius and modified by WIDOWN.
     
     The "MAGE" function aims to fix any issues present in the original video clip such as agressive noise, while preserving details and improving sharpness.\n
     It is recommended to use it for anim-type content because otherwise, it can create "wrapping" effects, similar to those caused by AI video interpolation.
     
     """
 
-    clip = format(clip)
+    clip = cFormat(clip)
 
     # all levels for MAnalyse
     super = core.mv.Super(clip, hpad=32, vpad=32, rfilter=4)
 
     # Truemotion for max denoising on original vid
     backward2 = core.mv.Analyse(super, isb=True, blksize=32, overlap=16, delta=2, search=5, truemotion=True)
     backward  = core.mv.Analyse(super, isb=True, blksize=32, overlap=16, search=5, truemotion=True)
@@ -219,38 +219,38 @@
             fsrcnnxLaPath : str  = "C:/Softwares/AV1AN/FSRCNNX_x2_8-0-4-1_LineArt.glsl",
             usWidth       : int  = 1920,
             usHeight      : int  = 1080) :
     
     # Verifying which upcaling model should be used depending on the content.
     fsrcnnxFinalPath = fsrcnnxLaPath if (isAnime == True) else fsrcnnxPath
     
-    clip = format(clip)
+    clip = cFormat(clip)
     clip = core.placebo.Shader(clip, fsrcnnxFinalPath,  usWidth, usHeight, filter="catmull_rom", antiring=0.7)
     return clip
     
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def dehalo(clip : vs.VideoNode) :
-    clip = format(clip)
+    clip = cFormat(clip)
     clip = DeHalo_alpha(clip, darkstr=0.4)
     return clip
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
     
 def dering(clip : vs.VideoNode) :
-    clip = format(clip)
+    clip = cFormat(clip)
     clip = HQDeringmod(clip, mrad=8, nrmode=0, darkthr=True)
     return clip
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def aa(clip    : vs.VideoNode,
        useUsAA : bool = True) :
     
-    clip = format(clip)
+    clip = cFormat(clip)
     clip = TAAmbk(clip, aatype='Nnedi3UpscaleSangNom', opencl=True) if (useUsAA == True) else TAAmbk(clip, aatype='Eedi3', opencl=True)
     return clip
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def dpir(clip                   : vs.VideoNode,
          enableNCNN             : bool = True,
@@ -258,42 +258,44 @@
          dpirDeblocking         : bool = True,
          dpirDenoising          : bool = True,
          dpirDeblockingStrength : int  = 15,
          dpirDenoisingStrength  : int  = 1) :
     
     if (enableNCNN == False) :
         from . import WIDscript_dpir as dpir
-        clip = dpir.dpir(clip, enableNCNN, dpirTileDenominator, dpirDeblocking, dpirDenoising, dpirDeblockingStrength, dpirDenoisingStrength)
+        clip = dpir.dpir(clip, dpirTileDenominator, dpirDeblocking, dpirDenoising, dpirDeblockingStrength, dpirDenoisingStrength)
+        return clip
     else :
         from . import WIDscript_dpirNCNN as dpir
-        clip = dpir.dpir(clip, enableNCNN, dpirTileDenominator, dpirDeblocking, dpirDenoising, dpirDeblockingStrength, dpirDenoisingStrength)
+        clip = dpir.dpir(clip, dpirTileDenominator, dpirDeblocking, dpirDenoising, dpirDeblockingStrength, dpirDenoisingStrength)
+        return clip
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def deband(clip          : vs.VideoNode,
            dbRemBinarize : int = 1500) :
 
-    clip_edge = format(clip)
+    clip_edge = cFormat(clip)
 
     # Creating a retinex edge mask before applying debanding to keep fine details.
     mask = retinex_edgemask(clip_edge).std.Binarize(dbRemBinarize).std.Inflate()
 
-    clip = format(clip, cFormatEnum.RGBS)
+    clip = cFormat(clip, cFormatEnum.RGBS)
     clip = core.placebo.Deband(clip, planes = 1 | 2 | 4, iterations=4, radius=8, threshold=8, grain=6, dither = True, dither_algo = 0)
-    clip = format(clip)
+    clip = cFormat(clip)
 
     # # Take the edge clip, and apply it on top of the debanded clip via the mask.
     clip = core.std.MaskedMerge(clip, clip_edge, mask)
 
     return clip
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def finalize(clip: vs.VideoNode) :
-    clip = format(clip, cFormatEnum.YUV420P10)
+    clip = cFormat(clip, cFormatEnum.YUV420P10)
     clip = finalize_clip(clip)
     return clip
 
 ############################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################################
 
 def everything(clip                   : vs.VideoNode,
                #
@@ -316,31 +318,31 @@
                useUpscaling           : bool  = False,
                isAnime                : bool  = True,
                fsrcnnxPath            : str   = "C:/Softwares/AV1AN/FSRCNNX_x2_8-0-4-1.glsl",
                fsrcnnxLaPath          : str   = "C:/Softwares/AV1AN/FSRCNNX_x2_8-0-4-1_LineArt.glsl",
                usWidth                : int   = 1920,
                usHeight               : int   = 1080,
                #
-               useDehaloing           : bool  = True,
-               useDeringing           : bool  = True,
-               useAA                  : bool  = True,
+               useDehaloing           : bool  = False,
+               useDeringing           : bool  = False,
+               useAA                  : bool  = False,
                useUsAA                : bool  = True,
                #
                useDPIR                : bool  = False,
                enableNCNN             : bool  = True,
                dpirTileDenominator    : int   = 2,
                dpirDeblocking         : bool  = True,
                dpirDenoising          : bool  = True,
                dpirDeblockingStrength : int   = 15,
                dpirDenoisingStrength  : int   = 1,
                #
                useDebanding           : bool  = False,
                dbRemBinarize          : int   = 1500,
                #
-               useFinalizing          : bool  = True) :
+               useFinalizing          : bool  = False) :
     
     if (slice          == True) : clip = clip[start:end]
     if (useHDR2SDR     == True) : clip = hdr2SDR(clip, dst_max, src_max, src_min)
     if (useDownscaling == True) : clip = downscale(clip, dsWidth, dsHeight)
     if (useMAGE        == True) : clip = mage(clip, thsxdxMultiplier)
     if (useUpscaling   == True) : clip = upscale(clip, isAnime, fsrcnnxPath, fsrcnnxLaPath, usWidth, usHeight)
     if (useDehaloing   == True) : clip = dehalo(clip)
```

### Comparing `WIDscript-1.2.0/src/WIDscript.egg-info/PKG-INFO` & `WIDscript-1.2.1/src/WIDscript.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: WIDscript
-Version: 1.2.0
+Version: 1.2.1
 Summary: A private wrapper made for WIDOWN releases.
 Home-page: https://github.com/pypa/sampleproject
 Author: WIDOWN
 Author-email: widown.ma@gmail.com
 Project-URL: Bug Tracker, https://github.com/pypa/sampleproject/issues
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: MIT License
```


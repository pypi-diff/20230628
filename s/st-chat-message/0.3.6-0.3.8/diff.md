# Comparing `tmp/st_chat_message-0.3.6.tar.gz` & `tmp/st_chat_message-0.3.8.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "st_chat_message-0.3.6.tar", max compression
+gzip compressed data, was "st_chat_message-0.3.8.tar", max compression
```

## Comparing `st_chat_message-0.3.6.tar` & `st_chat_message-0.3.8.tar`

### file list

```diff
@@ -1,81 +1,81 @@
--rw-r--r--   0        0        0      856 2023-06-27 12:09:00.859182 st_chat_message-0.3.6/README.md
--rw-r--r--   0        0        0      680 2023-06-27 13:46:15.994804 st_chat_message-0.3.6/pyproject.toml
--rw-r--r--   0        0        0     3854 2023-06-27 09:20:42.712230 st_chat_message-0.3.6/st_chat_message/__init__.py
--rw-r--r--   0        0        0     2648 2023-06-27 12:05:02.635642 st_chat_message-0.3.6/st_chat_message/frontend/out/404.html
--rw-r--r--   0        0        0      361 2023-06-27 12:05:02.513541 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/Dg5cdAEY-RCHv3LVfP7Lo/_buildManifest.js
--rw-r--r--   0        0        0       77 2023-06-27 12:05:02.513809 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/Dg5cdAEY-RCHv3LVfP7Lo/_ssgManifest.js
--rw-r--r--   0        0        0   266404 2023-06-27 12:05:02.518587 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/175675d1-280cba64f0247428.js
--rw-r--r--   0        0        0   141045 2023-06-27 12:05:02.518454 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/framework-5e8ac8dd643904dd.js
--rw-r--r--   0        0        0    96246 2023-06-27 12:05:02.518453 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/main-c6459c6dbdcff8e8.js
--rw-r--r--   0        0        0      448 2023-06-27 12:05:02.518720 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/pages/_app-345c8177130438ac.js
--rw-r--r--   0        0        0      250 2023-06-27 12:05:02.518774 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/pages/_error-3f6d1c55bb8051ab.js
--rw-r--r--   0        0        0  1407017 2023-06-27 12:05:02.519868 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/pages/index-56e240b261b33c91.js
--rw-r--r--   0        0        0    91381 2023-06-27 12:05:02.518454 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/polyfills-78c92fac7aa8fdd8.js
--rw-r--r--   0        0        0     1639 2023-06-27 12:05:02.518644 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/webpack-9d2bee59a0ebae7b.js
--rw-r--r--   0        0        0    26985 2023-06-27 12:05:02.513726 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/css/1f759626be541cb1.css
--rw-r--r--   0        0        0    20655 2023-06-27 12:05:02.513783 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/css/2c1d693913146cab.css
--rw-r--r--   0        0        0    33516 2023-06-27 12:05:02.514334 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.1608a09b.woff
--rw-r--r--   0        0        0    63632 2023-06-27 12:05:02.514441 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.4aafdb68.ttf
--rw-r--r--   0        0        0    28076 2023-06-27 12:05:02.514374 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.a79f1c31.woff2
--rw-r--r--   0        0        0     7716 2023-06-27 12:05:02.514314 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.b6770918.woff
--rw-r--r--   0        0        0    12368 2023-06-27 12:05:02.514515 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.cce5b8ec.ttf
--rw-r--r--   0        0        0     6912 2023-06-27 12:05:02.514513 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.ec17d132.woff2
--rw-r--r--   0        0        0    12344 2023-06-27 12:05:02.514614 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.07ef19e7.ttf
--rw-r--r--   0        0        0     6908 2023-06-27 12:05:02.514682 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.55fac258.woff2
--rw-r--r--   0        0        0     7656 2023-06-27 12:05:02.514726 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.dad44a7f.woff
--rw-r--r--   0        0        0    13296 2023-06-27 12:05:02.514746 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.9f256b85.woff
--rw-r--r--   0        0        0    19584 2023-06-27 12:05:02.514921 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.b18f59e1.ttf
--rw-r--r--   0        0        0    11348 2023-06-27 12:05:02.514874 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.d42a5579.woff2
--rw-r--r--   0        0        0    13208 2023-06-27 12:05:02.514951 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.7c187121.woff
--rw-r--r--   0        0        0    11316 2023-06-27 12:05:02.515013 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.d3c882a6.woff2
--rw-r--r--   0        0        0    19572 2023-06-27 12:05:02.515174 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.ed38e79f.ttf
--rw-r--r--   0        0        0    51336 2023-06-27 12:05:02.515383 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.b74a1a8b.ttf
--rw-r--r--   0        0        0    25324 2023-06-27 12:05:02.515270 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.c3fb5ac2.woff2
--rw-r--r--   0        0        0    29912 2023-06-27 12:05:02.515315 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.d181c465.woff
--rw-r--r--   0        0        0    16780 2023-06-27 12:05:02.515359 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.6f2bb1df.woff2
--rw-r--r--   0        0        0    32968 2023-06-27 12:05:02.515490 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.70d8b0a5.ttf
--rw-r--r--   0        0        0    19412 2023-06-27 12:05:02.515499 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.e3f82f9d.woff
--rw-r--r--   0        0        0    33580 2023-06-27 12:05:02.515653 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.47373d1e.ttf
--rw-r--r--   0        0        0    16988 2023-06-27 12:05:02.515607 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.8916142b.woff2
--rw-r--r--   0        0        0    19676 2023-06-27 12:05:02.515669 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.9024d815.woff
--rw-r--r--   0        0        0    26272 2023-06-27 12:05:02.515761 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.0462f03b.woff2
--rw-r--r--   0        0        0    30772 2023-06-27 12:05:02.515863 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.7f51fe03.woff
--rw-r--r--   0        0        0    53580 2023-06-27 12:05:02.516049 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.b7f8fe9b.ttf
--rw-r--r--   0        0        0    16400 2023-06-27 12:05:02.515992 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.572d331f.woff2
--rw-r--r--   0        0        0    31196 2023-06-27 12:05:02.516086 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.a879cf83.ttf
--rw-r--r--   0        0        0    18668 2023-06-27 12:05:02.516089 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.f1035d8d.woff
--rw-r--r--   0        0        0    18748 2023-06-27 12:05:02.516217 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.5295ba48.woff
--rw-r--r--   0        0        0    31308 2023-06-27 12:05:02.516275 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.939bc644.ttf
--rw-r--r--   0        0        0    16440 2023-06-27 12:05:02.516411 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.f28c23ac.woff2
--rw-r--r--   0        0        0    12216 2023-06-27 12:05:02.516336 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.8c5b5494.woff2
--rw-r--r--   0        0        0    24504 2023-06-27 12:05:02.516420 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.94e1e8dc.ttf
--rw-r--r--   0        0        0    14408 2023-06-27 12:05:02.516450 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.bf59d231.woff
--rw-r--r--   0        0        0    12028 2023-06-27 12:05:02.516564 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.3b1e59b3.woff2
--rw-r--r--   0        0        0    14112 2023-06-27 12:05:02.516678 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.7c9bc82b.woff
--rw-r--r--   0        0        0    22364 2023-06-27 12:05:02.516706 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.b4c20c84.ttf
--rw-r--r--   0        0        0    12316 2023-06-27 12:05:02.516682 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.74048478.woff
--rw-r--r--   0        0        0    10344 2023-06-27 12:05:02.516843 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.ba21ed5f.woff2
--rw-r--r--   0        0        0    19436 2023-06-27 12:05:02.517011 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.d4d7ba48.ttf
--rw-r--r--   0        0        0     9644 2023-06-27 12:05:02.516944 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.03e9641d.woff2
--rw-r--r--   0        0        0    10588 2023-06-27 12:05:02.517004 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.07505710.woff
--rw-r--r--   0        0        0    16648 2023-06-27 12:05:02.517130 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.fe9cbbe1.ttf
--rw-r--r--   0        0        0     6496 2023-06-27 12:05:02.517137 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.e1e279cb.woff
--rw-r--r--   0        0        0     5468 2023-06-27 12:05:02.517236 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.eae34984.woff2
--rw-r--r--   0        0        0    12228 2023-06-27 12:05:02.517260 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.fabc004a.ttf
--rw-r--r--   0        0        0     6188 2023-06-27 12:05:02.517325 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.57727022.woff
--rw-r--r--   0        0        0     5208 2023-06-27 12:05:02.517353 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.5916a24f.woff2
--rw-r--r--   0        0        0    11508 2023-06-27 12:05:02.517383 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.d6b476ec.ttf
--rw-r--r--   0        0        0     4420 2023-06-27 12:05:02.517433 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.9acaf01c.woff
--rw-r--r--   0        0        0     7588 2023-06-27 12:05:02.517464 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.a144ef58.ttf
--rw-r--r--   0        0        0     3624 2023-06-27 12:05:02.517564 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.b4230e7e.woff2
--rw-r--r--   0        0        0     4928 2023-06-27 12:05:02.517601 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.10d95fd3.woff2
--rw-r--r--   0        0        0     5980 2023-06-27 12:05:02.517664 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.7a996c9d.woff
--rw-r--r--   0        0        0    10364 2023-06-27 12:05:02.517678 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.fbccdabe.ttf
--rw-r--r--   0        0        0    16028 2023-06-27 12:05:02.517759 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.6258592b.woff
--rw-r--r--   0        0        0    13568 2023-06-27 12:05:02.517824 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.a8709e36.woff2
--rw-r--r--   0        0        0    27556 2023-06-27 12:05:02.517905 st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.d97aaf4a.ttf
--rw-r--r--   0        0        0    25931 2023-06-27 12:05:02.521914 st_chat_message-0.3.6/st_chat_message/frontend/out/favicon.ico
--rw-r--r--   0        0        0     2335 2023-06-27 12:05:02.608502 st_chat_message-0.3.6/st_chat_message/frontend/out/index.html
--rw-r--r--   0        0        0     1101 2023-06-27 12:05:02.521703 st_chat_message-0.3.6/st_chat_message/frontend/out/vercel.svg
--rw-r--r--   0        0        0     1991 1970-01-01 00:00:00.000000 st_chat_message-0.3.6/setup.py
--rw-r--r--   0        0        0     1525 1970-01-01 00:00:00.000000 st_chat_message-0.3.6/PKG-INFO
+-rw-r--r--   0        0        0      856 2023-06-27 12:09:00.859182 st_chat_message-0.3.8/README.md
+-rw-r--r--   0        0        0      680 2023-06-28 08:56:28.157105 st_chat_message-0.3.8/pyproject.toml
+-rw-r--r--   0        0        0     3042 2023-06-28 08:43:08.997228 st_chat_message-0.3.8/st_chat_message/__init__.py
+-rw-r--r--   0        0        0     2648 2023-06-28 08:56:26.861824 st_chat_message-0.3.8/st_chat_message/frontend/out/404.html
+-rw-r--r--   0        0        0      361 2023-06-28 08:56:26.739580 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/6ygvE_r4CKVPLu_JlsWil/_buildManifest.js
+-rw-r--r--   0        0        0       77 2023-06-28 08:56:26.739592 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/6ygvE_r4CKVPLu_JlsWil/_ssgManifest.js
+-rw-r--r--   0        0        0   266404 2023-06-28 08:56:26.740351 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/175675d1-280cba64f0247428.js
+-rw-r--r--   0        0        0   141045 2023-06-28 08:56:26.740166 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/framework-5e8ac8dd643904dd.js
+-rw-r--r--   0        0        0    96246 2023-06-28 08:56:26.740035 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/main-c6459c6dbdcff8e8.js
+-rw-r--r--   0        0        0      448 2023-06-28 08:56:26.743863 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/pages/_app-345c8177130438ac.js
+-rw-r--r--   0        0        0      250 2023-06-28 08:56:26.743901 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/pages/_error-3f6d1c55bb8051ab.js
+-rw-r--r--   0        0        0  1407029 2023-06-28 08:56:26.744879 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/pages/index-df2a1fafbbf92047.js
+-rw-r--r--   0        0        0    91381 2023-06-28 08:56:26.740121 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/polyfills-78c92fac7aa8fdd8.js
+-rw-r--r--   0        0        0     1639 2023-06-28 08:56:26.740198 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/webpack-9d2bee59a0ebae7b.js
+-rw-r--r--   0        0        0    26985 2023-06-28 08:56:26.743803 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/css/1f759626be541cb1.css
+-rw-r--r--   0        0        0    20661 2023-06-28 08:56:26.743828 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/css/ecb6d8ff2db7565c.css
+-rw-r--r--   0        0        0    33516 2023-06-28 08:56:26.740357 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.1608a09b.woff
+-rw-r--r--   0        0        0    63632 2023-06-28 08:56:26.740424 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.4aafdb68.ttf
+-rw-r--r--   0        0        0    28076 2023-06-28 08:56:26.740426 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.a79f1c31.woff2
+-rw-r--r--   0        0        0     7716 2023-06-28 08:56:26.740572 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.b6770918.woff
+-rw-r--r--   0        0        0    12368 2023-06-28 08:56:26.740506 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.cce5b8ec.ttf
+-rw-r--r--   0        0        0     6912 2023-06-28 08:56:26.740572 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.ec17d132.woff2
+-rw-r--r--   0        0        0    12344 2023-06-28 08:56:26.740618 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.07ef19e7.ttf
+-rw-r--r--   0        0        0     6908 2023-06-28 08:56:26.740697 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.55fac258.woff2
+-rw-r--r--   0        0        0     7656 2023-06-28 08:56:26.740720 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.dad44a7f.woff
+-rw-r--r--   0        0        0    13296 2023-06-28 08:56:26.740753 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.9f256b85.woff
+-rw-r--r--   0        0        0    19584 2023-06-28 08:56:26.740973 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.b18f59e1.ttf
+-rw-r--r--   0        0        0    11348 2023-06-28 08:56:26.740913 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.d42a5579.woff2
+-rw-r--r--   0        0        0    13208 2023-06-28 08:56:26.740918 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.7c187121.woff
+-rw-r--r--   0        0        0    11316 2023-06-28 08:56:26.741001 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.d3c882a6.woff2
+-rw-r--r--   0        0        0    19572 2023-06-28 08:56:26.741166 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.ed38e79f.ttf
+-rw-r--r--   0        0        0    51336 2023-06-28 08:56:26.741277 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.b74a1a8b.ttf
+-rw-r--r--   0        0        0    25324 2023-06-28 08:56:26.741319 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.c3fb5ac2.woff2
+-rw-r--r--   0        0        0    29912 2023-06-28 08:56:26.741286 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.d181c465.woff
+-rw-r--r--   0        0        0    16780 2023-06-28 08:56:26.741364 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.6f2bb1df.woff2
+-rw-r--r--   0        0        0    32968 2023-06-28 08:56:26.741573 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.70d8b0a5.ttf
+-rw-r--r--   0        0        0    19412 2023-06-28 08:56:26.741548 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.e3f82f9d.woff
+-rw-r--r--   0        0        0    33580 2023-06-28 08:56:26.741629 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.47373d1e.ttf
+-rw-r--r--   0        0        0    16988 2023-06-28 08:56:26.741600 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.8916142b.woff2
+-rw-r--r--   0        0        0    19676 2023-06-28 08:56:26.741713 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.9024d815.woff
+-rw-r--r--   0        0        0    26272 2023-06-28 08:56:26.741838 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.0462f03b.woff2
+-rw-r--r--   0        0        0    30772 2023-06-28 08:56:26.741829 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.7f51fe03.woff
+-rw-r--r--   0        0        0    53580 2023-06-28 08:56:26.741889 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.b7f8fe9b.ttf
+-rw-r--r--   0        0        0    16400 2023-06-28 08:56:26.741862 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.572d331f.woff2
+-rw-r--r--   0        0        0    31196 2023-06-28 08:56:26.742120 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.a879cf83.ttf
+-rw-r--r--   0        0        0    18668 2023-06-28 08:56:26.742082 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.f1035d8d.woff
+-rw-r--r--   0        0        0    18748 2023-06-28 08:56:26.742115 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.5295ba48.woff
+-rw-r--r--   0        0        0    31308 2023-06-28 08:56:26.742121 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.939bc644.ttf
+-rw-r--r--   0        0        0    16440 2023-06-28 08:56:26.742276 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.f28c23ac.woff2
+-rw-r--r--   0        0        0    12216 2023-06-28 08:56:26.742278 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.8c5b5494.woff2
+-rw-r--r--   0        0        0    24504 2023-06-28 08:56:26.742410 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.94e1e8dc.ttf
+-rw-r--r--   0        0        0    14408 2023-06-28 08:56:26.742396 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.bf59d231.woff
+-rw-r--r--   0        0        0    12028 2023-06-28 08:56:26.742515 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.3b1e59b3.woff2
+-rw-r--r--   0        0        0    14112 2023-06-28 08:56:26.742585 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.7c9bc82b.woff
+-rw-r--r--   0        0        0    22364 2023-06-28 08:56:26.742632 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.b4c20c84.ttf
+-rw-r--r--   0        0        0    12316 2023-06-28 08:56:26.742646 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.74048478.woff
+-rw-r--r--   0        0        0    10344 2023-06-28 08:56:26.742682 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.ba21ed5f.woff2
+-rw-r--r--   0        0        0    19436 2023-06-28 08:56:26.742815 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.d4d7ba48.ttf
+-rw-r--r--   0        0        0     9644 2023-06-28 08:56:26.742869 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.03e9641d.woff2
+-rw-r--r--   0        0        0    10588 2023-06-28 08:56:26.742919 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.07505710.woff
+-rw-r--r--   0        0        0    16648 2023-06-28 08:56:26.742934 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.fe9cbbe1.ttf
+-rw-r--r--   0        0        0     6496 2023-06-28 08:56:26.743035 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.e1e279cb.woff
+-rw-r--r--   0        0        0     5468 2023-06-28 08:56:26.743064 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.eae34984.woff2
+-rw-r--r--   0        0        0    12228 2023-06-28 08:56:26.743182 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.fabc004a.ttf
+-rw-r--r--   0        0        0     6188 2023-06-28 08:56:26.743181 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.57727022.woff
+-rw-r--r--   0        0        0     5208 2023-06-28 08:56:26.743173 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.5916a24f.woff2
+-rw-r--r--   0        0        0    11508 2023-06-28 08:56:26.743266 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.d6b476ec.ttf
+-rw-r--r--   0        0        0     4420 2023-06-28 08:56:26.743409 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.9acaf01c.woff
+-rw-r--r--   0        0        0     7588 2023-06-28 08:56:26.743461 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.a144ef58.ttf
+-rw-r--r--   0        0        0     3624 2023-06-28 08:56:26.743445 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.b4230e7e.woff2
+-rw-r--r--   0        0        0     4928 2023-06-28 08:56:26.743447 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.10d95fd3.woff2
+-rw-r--r--   0        0        0     5980 2023-06-28 08:56:26.743533 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.7a996c9d.woff
+-rw-r--r--   0        0        0    10364 2023-06-28 08:56:26.743581 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.fbccdabe.ttf
+-rw-r--r--   0        0        0    16028 2023-06-28 08:56:26.743630 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.6258592b.woff
+-rw-r--r--   0        0        0    13568 2023-06-28 08:56:26.743644 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.a8709e36.woff2
+-rw-r--r--   0        0        0    27556 2023-06-28 08:56:26.743735 st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.d97aaf4a.ttf
+-rw-r--r--   0        0        0    25931 2023-06-28 08:56:26.746964 st_chat_message-0.3.8/st_chat_message/frontend/out/favicon.ico
+-rw-r--r--   0        0        0     2335 2023-06-28 08:56:26.834998 st_chat_message-0.3.8/st_chat_message/frontend/out/index.html
+-rw-r--r--   0        0        0     1101 2023-06-28 08:56:26.746764 st_chat_message-0.3.8/st_chat_message/frontend/out/vercel.svg
+-rw-r--r--   0        0        0     1991 1970-01-01 00:00:00.000000 st_chat_message-0.3.8/setup.py
+-rw-r--r--   0        0        0     1525 1970-01-01 00:00:00.000000 st_chat_message-0.3.8/PKG-INFO
```

### Comparing `st_chat_message-0.3.6/README.md` & `st_chat_message-0.3.8/README.md`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/pyproject.toml` & `st_chat_message-0.3.8/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "st-chat-message"
-version = "0.3.6"
+version = "0.3.8"
 description = "A Streamlit component to display chat messages"
 authors = ["Manolo Santos <manolo.santos@gmail.com>"]
 readme = "README.md"
 packages = [{ include = "st_chat_message"}]
 
 license = "MIT"
```

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/404.html` & `st_chat_message-0.3.8/st_chat_message/frontend/out/404.html`

 * *Files 10% similar despite different names*

```diff
@@ -1 +1 @@
-<!DOCTYPE html><html><head><meta charSet="utf-8"/><meta name="viewport" content="width=device-width"/><title>404: This page could not be found</title><meta name="next-head-count" content="3"/><link rel="preload" href="/component/st_chat_message.st_chat_message/_next/static/css/2c1d693913146cab.css" as="style"/><link rel="stylesheet" href="/component/st_chat_message.st_chat_message/_next/static/css/2c1d693913146cab.css" data-n-g=""/><noscript data-n-css=""></noscript><script defer="" nomodule="" src="/component/st_chat_message.st_chat_message/_next/static/chunks/polyfills-78c92fac7aa8fdd8.js"></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/webpack-9d2bee59a0ebae7b.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/framework-5e8ac8dd643904dd.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/main-c6459c6dbdcff8e8.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/pages/_app-345c8177130438ac.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/pages/_error-3f6d1c55bb8051ab.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/Dg5cdAEY-RCHv3LVfP7Lo/_buildManifest.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/Dg5cdAEY-RCHv3LVfP7Lo/_ssgManifest.js" defer=""></script></head><body><div id="__next"><div style="font-family:system-ui,&quot;Segoe UI&quot;,Roboto,Helvetica,Arial,sans-serif,&quot;Apple Color Emoji&quot;,&quot;Segoe UI Emoji&quot;;height:100vh;text-align:center;display:flex;flex-direction:column;align-items:center;justify-content:center"><div style="line-height:48px"><style>body{color:#000;background:#fff;margin:0}.next-error-h1{border-right:1px solid rgba(0,0,0,.3)}@media (prefers-color-scheme:dark){body{color:#fff;background:#000}.next-error-h1{border-right:1px solid rgba(255,255,255,.3)}}</style><h1 class="next-error-h1" style="display:inline-block;margin:0 20px 0 0;padding-right:23px;font-size:24px;font-weight:500;vertical-align:top">404</h1><div style="display:inline-block"><h2 style="font-size:14px;font-weight:400;line-height:28px">This page could not be found<!-- -->.</h2></div></div></div></div><script id="__NEXT_DATA__" type="application/json">{"props":{"pageProps":{"statusCode":404}},"page":"/_error","query":{},"buildId":"Dg5cdAEY-RCHv3LVfP7Lo","assetPrefix":"/component/st_chat_message.st_chat_message","nextExport":true,"isFallback":false,"gip":true,"scriptLoader":[]}</script></body></html>
+<!DOCTYPE html><html><head><meta charSet="utf-8"/><meta name="viewport" content="width=device-width"/><title>404: This page could not be found</title><meta name="next-head-count" content="3"/><link rel="preload" href="/component/st_chat_message.st_chat_message/_next/static/css/ecb6d8ff2db7565c.css" as="style"/><link rel="stylesheet" href="/component/st_chat_message.st_chat_message/_next/static/css/ecb6d8ff2db7565c.css" data-n-g=""/><noscript data-n-css=""></noscript><script defer="" nomodule="" src="/component/st_chat_message.st_chat_message/_next/static/chunks/polyfills-78c92fac7aa8fdd8.js"></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/webpack-9d2bee59a0ebae7b.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/framework-5e8ac8dd643904dd.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/main-c6459c6dbdcff8e8.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/pages/_app-345c8177130438ac.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/pages/_error-3f6d1c55bb8051ab.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/6ygvE_r4CKVPLu_JlsWil/_buildManifest.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/6ygvE_r4CKVPLu_JlsWil/_ssgManifest.js" defer=""></script></head><body><div id="__next"><div style="font-family:system-ui,&quot;Segoe UI&quot;,Roboto,Helvetica,Arial,sans-serif,&quot;Apple Color Emoji&quot;,&quot;Segoe UI Emoji&quot;;height:100vh;text-align:center;display:flex;flex-direction:column;align-items:center;justify-content:center"><div style="line-height:48px"><style>body{color:#000;background:#fff;margin:0}.next-error-h1{border-right:1px solid rgba(0,0,0,.3)}@media (prefers-color-scheme:dark){body{color:#fff;background:#000}.next-error-h1{border-right:1px solid rgba(255,255,255,.3)}}</style><h1 class="next-error-h1" style="display:inline-block;margin:0 20px 0 0;padding-right:23px;font-size:24px;font-weight:500;vertical-align:top">404</h1><div style="display:inline-block"><h2 style="font-size:14px;font-weight:400;line-height:28px">This page could not be found<!-- -->.</h2></div></div></div></div><script id="__NEXT_DATA__" type="application/json">{"props":{"pageProps":{"statusCode":404}},"page":"/_error","query":{},"buildId":"6ygvE_r4CKVPLu_JlsWil","assetPrefix":"/component/st_chat_message.st_chat_message","nextExport":true,"isFallback":false,"gip":true,"scriptLoader":[]}</script></body></html>
```

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/175675d1-280cba64f0247428.js` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/175675d1-280cba64f0247428.js`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/framework-5e8ac8dd643904dd.js` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/framework-5e8ac8dd643904dd.js`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/main-c6459c6dbdcff8e8.js` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/main-c6459c6dbdcff8e8.js`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/pages/index-56e240b261b33c91.js` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/pages/index-df2a1fafbbf92047.js`

 * *Files 0% similar despite different names*

#### js-beautify {}

```diff
@@ -18992,19 +18992,19 @@
                 oQ = function() {
                     let {
                         theme: e,
                         disabled: t,
                         args: n
                     } = (0, u.QO)();
                     return (0, s.jsxs)("div", {
-                        className: p("pb-2 flex", n.isUser ? "flex-row-reverse" : "flex-row"),
+                        className: p("pb-2 flex", n.isUser ? "flex-row-reverse ml-12" : "flex-row mr-12"),
                         children: [(0, s.jsx)(oZ(), {
                             src: n.logo ? n.logo : "https://api.dicebear.com/5.x/".concat(n.avatarStyle, "/svg?seed=").concat(n.seed),
                             alt: "avatar",
-                            className: p("border-transparent rounded-lg h-8 w-8", n.isUser ? "ml-4" : "mr-4"),
+                            className: p("rounded-md h-8 w-8 shadow bg-gray-200", n.isUser ? "ml-4" : "mr-4"),
                             width: 32,
                             height: 32
                         }), (0, s.jsx)(oq, {
                             content: n.message,
                             role: n.isUser ? "user" : "assistant",
                             richContent: n.richContent,
                             partial: n.partial
```

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/polyfills-78c92fac7aa8fdd8.js` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/polyfills-78c92fac7aa8fdd8.js`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/chunks/webpack-9d2bee59a0ebae7b.js` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/chunks/webpack-9d2bee59a0ebae7b.js`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/css/1f759626be541cb1.css` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/css/1f759626be541cb1.css`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/css/2c1d693913146cab.css` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/css/ecb6d8ff2db7565c.css`

 * *Files 1% similar despite different names*

```diff
@@ -1,3 +1,3 @@
 /*
 ! tailwindcss v3.3.2 | MIT License | https://tailwindcss.com
-*/*,:after,:before{box-sizing:border-box;border:0 solid #e5e7eb}:after,:before{--tw-content:""}html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;-o-tab-size:4;tab-size:4;font-family:ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;font-feature-settings:normal;font-variation-settings:normal}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,Liberation Mono,Courier New,monospace;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-size:100%;font-weight:inherit;line-height:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}[type=button],[type=reset],[type=submit],button{-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0}fieldset,legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}textarea{resize:vertical}input::-moz-placeholder,textarea::-moz-placeholder{opacity:1;color:#9ca3af}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]{display:none}*,:after,:before{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgba(59,130,246,.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgba(59,130,246,.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: }.prose{color:var(--tw-prose-body);max-width:65ch}.prose :where(p):not(:where([class~=not-prose] *)){margin-top:1.25em;margin-bottom:1.25em}.prose :where([class~=lead]):not(:where([class~=not-prose] *)){color:var(--tw-prose-lead);font-size:1.25em;line-height:1.6;margin-top:1.2em;margin-bottom:1.2em}.prose :where(a):not(:where([class~=not-prose] *)){color:var(--tw-prose-links);text-decoration:underline;font-weight:500}.prose :where(strong):not(:where([class~=not-prose] *)){color:var(--tw-prose-bold);font-weight:600}.prose :where(a strong):not(:where([class~=not-prose] *)){color:inherit}.prose :where(blockquote strong):not(:where([class~=not-prose] *)){color:inherit}.prose :where(thead th strong):not(:where([class~=not-prose] *)){color:inherit}.prose :where(ol):not(:where([class~=not-prose] *)){list-style-type:decimal;margin-top:1.25em;margin-bottom:1.25em;padding-left:1.625em}.prose :where(ol[type=A]):not(:where([class~=not-prose] *)){list-style-type:upper-alpha}.prose :where(ol[type=a]):not(:where([class~=not-prose] *)){list-style-type:lower-alpha}.prose :where(ol[type=A s]):not(:where([class~=not-prose] *)){list-style-type:upper-alpha}.prose :where(ol[type=a s]):not(:where([class~=not-prose] *)){list-style-type:lower-alpha}.prose :where(ol[type=I]):not(:where([class~=not-prose] *)){list-style-type:upper-roman}.prose :where(ol[type=i]):not(:where([class~=not-prose] *)){list-style-type:lower-roman}.prose :where(ol[type=I s]):not(:where([class~=not-prose] *)){list-style-type:upper-roman}.prose :where(ol[type=i s]):not(:where([class~=not-prose] *)){list-style-type:lower-roman}.prose :where(ol[type="1"]):not(:where([class~=not-prose] *)){list-style-type:decimal}.prose :where(ul):not(:where([class~=not-prose] *)){list-style-type:disc;margin-top:1.25em;margin-bottom:1.25em;padding-left:1.625em}.prose :where(ol>li):not(:where([class~=not-prose] *))::marker{font-weight:400;color:var(--tw-prose-counters)}.prose :where(ul>li):not(:where([class~=not-prose] *))::marker{color:var(--tw-prose-bullets)}.prose :where(hr):not(:where([class~=not-prose] *)){border-color:var(--tw-prose-hr);border-top-width:1px;margin-top:3em;margin-bottom:3em}.prose :where(blockquote):not(:where([class~=not-prose] *)){font-weight:500;font-style:italic;color:var(--tw-prose-quotes);border-left-width:.25rem;border-left-color:var(--tw-prose-quote-borders);quotes:"\201C""\201D""\2018""\2019";margin-top:1.6em;margin-bottom:1.6em;padding-left:1em}.prose :where(blockquote p:first-of-type):not(:where([class~=not-prose] *)):before{content:open-quote}.prose :where(blockquote p:last-of-type):not(:where([class~=not-prose] *)):after{content:close-quote}.prose :where(h1):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:800;font-size:2.25em;margin-top:0;margin-bottom:.8888889em;line-height:1.1111111}.prose :where(h1 strong):not(:where([class~=not-prose] *)){font-weight:900;color:inherit}.prose :where(h2):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:700;font-size:1.5em;margin-top:2em;margin-bottom:1em;line-height:1.3333333}.prose :where(h2 strong):not(:where([class~=not-prose] *)){font-weight:800;color:inherit}.prose :where(h3):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:600;font-size:1.25em;margin-top:1.6em;margin-bottom:.6em;line-height:1.6}.prose :where(h3 strong):not(:where([class~=not-prose] *)){font-weight:700;color:inherit}.prose :where(h4):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:600;margin-top:1.5em;margin-bottom:.5em;line-height:1.5}.prose :where(h4 strong):not(:where([class~=not-prose] *)){font-weight:700;color:inherit}.prose :where(img):not(:where([class~=not-prose] *)){margin-top:2em;margin-bottom:2em}.prose :where(figure>*):not(:where([class~=not-prose] *)){margin-top:0;margin-bottom:0}.prose :where(figcaption):not(:where([class~=not-prose] *)){color:var(--tw-prose-captions);font-size:.875em;line-height:1.4285714;margin-top:.8571429em}.prose :where(code):not(:where([class~=not-prose] *)){color:var(--tw-prose-code);font-weight:600;font-size:.875em}.prose :where(code):not(:where([class~=not-prose] *)):before{content:"`"}.prose :where(code):not(:where([class~=not-prose] *)):after{content:"`"}.prose :where(a code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(h1 code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(h2 code):not(:where([class~=not-prose] *)){color:inherit;font-size:.875em}.prose :where(h3 code):not(:where([class~=not-prose] *)){color:inherit;font-size:.9em}.prose :where(h4 code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(blockquote code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(thead th code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(pre):not(:where([class~=not-prose] *)){color:var(--tw-prose-pre-code);background-color:var(--tw-prose-pre-bg);overflow-x:auto;font-weight:400;font-size:.875em;line-height:1.7142857;margin-top:1.7142857em;margin-bottom:1.7142857em;border-radius:.375rem;padding:.8571429em 1.1428571em}.prose :where(pre code):not(:where([class~=not-prose] *)){background-color:transparent;border-width:0;border-radius:0;padding:0;font-weight:inherit;color:inherit;font-size:inherit;font-family:inherit;line-height:inherit}.prose :where(pre code):not(:where([class~=not-prose] *)):before{content:none}.prose :where(pre code):not(:where([class~=not-prose] *)):after{content:none}.prose :where(table):not(:where([class~=not-prose] *)){width:100%;table-layout:auto;text-align:left;margin-top:2em;margin-bottom:2em;font-size:.875em;line-height:1.7142857}.prose :where(thead):not(:where([class~=not-prose] *)){border-bottom-width:1px;border-bottom-color:var(--tw-prose-th-borders)}.prose :where(thead th):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:600;vertical-align:bottom;padding-right:.5714286em;padding-bottom:.5714286em;padding-left:.5714286em}.prose :where(tbody tr):not(:where([class~=not-prose] *)){border-bottom-width:1px;border-bottom-color:var(--tw-prose-td-borders)}.prose :where(tbody tr:last-child):not(:where([class~=not-prose] *)){border-bottom-width:0}.prose :where(tbody td):not(:where([class~=not-prose] *)){vertical-align:baseline}.prose :where(tfoot):not(:where([class~=not-prose] *)){border-top-width:1px;border-top-color:var(--tw-prose-th-borders)}.prose :where(tfoot td):not(:where([class~=not-prose] *)){vertical-align:top}.prose{--tw-prose-body:#374151;--tw-prose-headings:#111827;--tw-prose-lead:#4b5563;--tw-prose-links:#111827;--tw-prose-bold:#111827;--tw-prose-counters:#6b7280;--tw-prose-bullets:#d1d5db;--tw-prose-hr:#e5e7eb;--tw-prose-quotes:#111827;--tw-prose-quote-borders:#e5e7eb;--tw-prose-captions:#6b7280;--tw-prose-code:#111827;--tw-prose-pre-code:#e5e7eb;--tw-prose-pre-bg:#1f2937;--tw-prose-th-borders:#d1d5db;--tw-prose-td-borders:#e5e7eb;--tw-prose-invert-body:#d1d5db;--tw-prose-invert-headings:#fff;--tw-prose-invert-lead:#9ca3af;--tw-prose-invert-links:#fff;--tw-prose-invert-bold:#fff;--tw-prose-invert-counters:#9ca3af;--tw-prose-invert-bullets:#4b5563;--tw-prose-invert-hr:#374151;--tw-prose-invert-quotes:#f3f4f6;--tw-prose-invert-quote-borders:#374151;--tw-prose-invert-captions:#9ca3af;--tw-prose-invert-code:#fff;--tw-prose-invert-pre-code:#d1d5db;--tw-prose-invert-pre-bg:rgba(0,0,0,.5);--tw-prose-invert-th-borders:#4b5563;--tw-prose-invert-td-borders:#374151;font-size:1rem;line-height:1.75}.prose :where(video):not(:where([class~=not-prose] *)){margin-top:2em;margin-bottom:2em}.prose :where(figure):not(:where([class~=not-prose] *)){margin-top:2em;margin-bottom:2em}.prose :where(li):not(:where([class~=not-prose] *)){margin-top:.5em;margin-bottom:.5em}.prose :where(ol>li):not(:where([class~=not-prose] *)){padding-left:.375em}.prose :where(ul>li):not(:where([class~=not-prose] *)){padding-left:.375em}.prose :where(.prose>ul>li p):not(:where([class~=not-prose] *)){margin-top:.75em;margin-bottom:.75em}.prose :where(.prose>ul>li>:first-child):not(:where([class~=not-prose] *)){margin-top:1.25em}.prose :where(.prose>ul>li>:last-child):not(:where([class~=not-prose] *)){margin-bottom:1.25em}.prose :where(.prose>ol>li>:first-child):not(:where([class~=not-prose] *)){margin-top:1.25em}.prose :where(.prose>ol>li>:last-child):not(:where([class~=not-prose] *)){margin-bottom:1.25em}.prose :where(ul ul,ul ol,ol ul,ol ol):not(:where([class~=not-prose] *)){margin-top:.75em;margin-bottom:.75em}.prose :where(hr+*):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(h2+*):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(h3+*):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(h4+*):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(thead th:first-child):not(:where([class~=not-prose] *)){padding-left:0}.prose :where(thead th:last-child):not(:where([class~=not-prose] *)){padding-right:0}.prose :where(tbody td,tfoot td):not(:where([class~=not-prose] *)){padding:.5714286em}.prose :where(tbody td:first-child,tfoot td:first-child):not(:where([class~=not-prose] *)){padding-left:0}.prose :where(tbody td:last-child,tfoot td:last-child):not(:where([class~=not-prose] *)){padding-right:0}.prose :where(.prose>:first-child):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(.prose>:last-child):not(:where([class~=not-prose] *)){margin-bottom:0}.prose-sm{font-size:.875rem;line-height:1.7142857}.prose-sm :where(p):not(:where([class~=not-prose] *)){margin-top:1.1428571em;margin-bottom:1.1428571em}.prose-sm :where([class~=lead]):not(:where([class~=not-prose] *)){font-size:1.2857143em;line-height:1.5555556;margin-top:.8888889em;margin-bottom:.8888889em}.prose-sm :where(blockquote):not(:where([class~=not-prose] *)){margin-top:1.3333333em;margin-bottom:1.3333333em;padding-left:1.1111111em}.prose-sm :where(h1):not(:where([class~=not-prose] *)){font-size:2.1428571em;margin-top:0;margin-bottom:.8em;line-height:1.2}.prose-sm :where(h2):not(:where([class~=not-prose] *)){font-size:1.4285714em;margin-top:1.6em;margin-bottom:.8em;line-height:1.4}.prose-sm :where(h3):not(:where([class~=not-prose] *)){font-size:1.2857143em;margin-top:1.5555556em;margin-bottom:.4444444em;line-height:1.5555556}.prose-sm :where(h4):not(:where([class~=not-prose] *)){margin-top:1.4285714em;margin-bottom:.5714286em;line-height:1.4285714}.prose-sm :where(img):not(:where([class~=not-prose] *)){margin-top:1.7142857em;margin-bottom:1.7142857em}.prose-sm :where(video):not(:where([class~=not-prose] *)){margin-top:1.7142857em;margin-bottom:1.7142857em}.prose-sm :where(figure):not(:where([class~=not-prose] *)){margin-top:1.7142857em;margin-bottom:1.7142857em}.prose-sm :where(figure>*):not(:where([class~=not-prose] *)){margin-top:0;margin-bottom:0}.prose-sm :where(figcaption):not(:where([class~=not-prose] *)){font-size:.8571429em;line-height:1.3333333;margin-top:.6666667em}.prose-sm :where(code):not(:where([class~=not-prose] *)){font-size:.8571429em}.prose-sm :where(h2 code):not(:where([class~=not-prose] *)){font-size:.9em}.prose-sm :where(h3 code):not(:where([class~=not-prose] *)){font-size:.8888889em}.prose-sm :where(pre):not(:where([class~=not-prose] *)){font-size:.8571429em;line-height:1.6666667;margin-top:1.6666667em;margin-bottom:1.6666667em;border-radius:.25rem;padding:.6666667em 1em}.prose-sm :where(ol):not(:where([class~=not-prose] *)){margin-top:1.1428571em;margin-bottom:1.1428571em;padding-left:1.5714286em}.prose-sm :where(ul):not(:where([class~=not-prose] *)){margin-top:1.1428571em;margin-bottom:1.1428571em;padding-left:1.5714286em}.prose-sm :where(li):not(:where([class~=not-prose] *)){margin-top:.2857143em;margin-bottom:.2857143em}.prose-sm :where(ol>li):not(:where([class~=not-prose] *)){padding-left:.4285714em}.prose-sm :where(ul>li):not(:where([class~=not-prose] *)){padding-left:.4285714em}.prose-sm :where(.prose-sm>ul>li p):not(:where([class~=not-prose] *)){margin-top:.5714286em;margin-bottom:.5714286em}.prose-sm :where(.prose-sm>ul>li>:first-child):not(:where([class~=not-prose] *)){margin-top:1.1428571em}.prose-sm :where(.prose-sm>ul>li>:last-child):not(:where([class~=not-prose] *)){margin-bottom:1.1428571em}.prose-sm :where(.prose-sm>ol>li>:first-child):not(:where([class~=not-prose] *)){margin-top:1.1428571em}.prose-sm :where(.prose-sm>ol>li>:last-child):not(:where([class~=not-prose] *)){margin-bottom:1.1428571em}.prose-sm :where(ul ul,ul ol,ol ul,ol ol):not(:where([class~=not-prose] *)){margin-top:.5714286em;margin-bottom:.5714286em}.prose-sm :where(hr):not(:where([class~=not-prose] *)){margin-top:2.8571429em;margin-bottom:2.8571429em}.prose-sm :where(hr+*):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(h2+*):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(h3+*):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(h4+*):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(table):not(:where([class~=not-prose] *)){font-size:.8571429em;line-height:1.5}.prose-sm :where(thead th):not(:where([class~=not-prose] *)){padding-right:1em;padding-bottom:.6666667em;padding-left:1em}.prose-sm :where(thead th:first-child):not(:where([class~=not-prose] *)){padding-left:0}.prose-sm :where(thead th:last-child):not(:where([class~=not-prose] *)){padding-right:0}.prose-sm :where(tbody td,tfoot td):not(:where([class~=not-prose] *)){padding:.6666667em 1em}.prose-sm :where(tbody td:first-child,tfoot td:first-child):not(:where([class~=not-prose] *)){padding-left:0}.prose-sm :where(tbody td:last-child,tfoot td:last-child):not(:where([class~=not-prose] *)){padding-right:0}.prose-sm :where(.prose-sm>:first-child):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(.prose-sm>:last-child):not(:where([class~=not-prose] *)){margin-bottom:0}.absolute{position:absolute}.relative{position:relative}.bottom-1{bottom:.25rem}.right-1{right:.25rem}.right-2{right:.5rem}.top-2{top:.5rem}.ml-4{margin-left:1rem}.mr-4{margin-right:1rem}.\!inline{display:inline!important}.inline{display:inline}.flex{display:flex}.h-4{height:1rem}.h-8{height:2rem}.w-4{width:1rem}.w-8{width:2rem}.max-w-none{max-width:none}.flex-1{flex:1 1 0%}.flex-row{flex-direction:row}.flex-row-reverse{flex-direction:row-reverse}.justify-around{justify-content:space-around}.overflow-x-auto{overflow-x:auto}.whitespace-pre-wrap{white-space:pre-wrap}.break-words{overflow-wrap:break-word}.rounded{border-radius:.25rem}.rounded-lg{border-radius:.5rem}.rounded-xl{border-radius:.75rem}.border{border-width:1px}.border-blue-200{--tw-border-opacity:1;border-color:rgb(191 219 254/var(--tw-border-opacity))}.border-green-200{--tw-border-opacity:1;border-color:rgb(187 247 208/var(--tw-border-opacity))}.border-orange-200{--tw-border-opacity:1;border-color:rgb(254 215 170/var(--tw-border-opacity))}.border-transparent{border-color:transparent}.bg-blue-50{--tw-bg-opacity:1;background-color:rgb(239 246 255/var(--tw-bg-opacity))}.bg-gray-200{--tw-bg-opacity:1;background-color:rgb(229 231 235/var(--tw-bg-opacity))}.bg-gray-600{--tw-bg-opacity:1;background-color:rgb(75 85 99/var(--tw-bg-opacity))}.bg-green-50{--tw-bg-opacity:1;background-color:rgb(240 253 244/var(--tw-bg-opacity))}.bg-orange-100{--tw-bg-opacity:1;background-color:rgb(255 237 213/var(--tw-bg-opacity))}.p-1{padding:.25rem}.px-4{padding-left:1rem;padding-right:1rem}.py-3{padding-top:.75rem;padding-bottom:.75rem}.pb-2{padding-bottom:.5rem}.font-mono{font-family:ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,Liberation Mono,Courier New,monospace}.text-sm{font-size:.875rem;line-height:1.25rem}.text-xs{font-size:.75rem;line-height:1rem}.text-white{--tw-text-opacity:1;color:rgb(255 255 255/var(--tw-text-opacity))}.opacity-50{opacity:.5}.opacity-60{opacity:.6}.shadow{--tw-shadow:0 1px 3px 0 rgba(0,0,0,.1),0 1px 2px -1px rgba(0,0,0,.1);--tw-shadow-colored:0 1px 3px 0 var(--tw-shadow-color),0 1px 2px -1px var(--tw-shadow-color)}.shadow,.shadow-md{box-shadow:var(--tw-ring-offset-shadow,0 0 #0000),var(--tw-ring-shadow,0 0 #0000),var(--tw-shadow)}.shadow-md{--tw-shadow:0 4px 6px -1px rgba(0,0,0,.1),0 2px 4px -2px rgba(0,0,0,.1);--tw-shadow-colored:0 4px 6px -1px var(--tw-shadow-color),0 2px 4px -2px var(--tw-shadow-color)}.hover\:bg-gray-500:hover{--tw-bg-opacity:1;background-color:rgb(107 114 128/var(--tw-bg-opacity))}
+*/*,:after,:before{box-sizing:border-box;border:0 solid #e5e7eb}:after,:before{--tw-content:""}html{line-height:1.5;-webkit-text-size-adjust:100%;-moz-tab-size:4;-o-tab-size:4;tab-size:4;font-family:ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Helvetica Neue,Arial,Noto Sans,sans-serif,Apple Color Emoji,Segoe UI Emoji,Segoe UI Symbol,Noto Color Emoji;font-feature-settings:normal;font-variation-settings:normal}body{margin:0;line-height:inherit}hr{height:0;color:inherit;border-top-width:1px}abbr:where([title]){-webkit-text-decoration:underline dotted;text-decoration:underline dotted}h1,h2,h3,h4,h5,h6{font-size:inherit;font-weight:inherit}a{color:inherit;text-decoration:inherit}b,strong{font-weight:bolder}code,kbd,pre,samp{font-family:ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,Liberation Mono,Courier New,monospace;font-size:1em}small{font-size:80%}sub,sup{font-size:75%;line-height:0;position:relative;vertical-align:baseline}sub{bottom:-.25em}sup{top:-.5em}table{text-indent:0;border-color:inherit;border-collapse:collapse}button,input,optgroup,select,textarea{font-family:inherit;font-size:100%;font-weight:inherit;line-height:inherit;color:inherit;margin:0;padding:0}button,select{text-transform:none}[type=button],[type=reset],[type=submit],button{-webkit-appearance:button;background-color:transparent;background-image:none}:-moz-focusring{outline:auto}:-moz-ui-invalid{box-shadow:none}progress{vertical-align:baseline}::-webkit-inner-spin-button,::-webkit-outer-spin-button{height:auto}[type=search]{-webkit-appearance:textfield;outline-offset:-2px}::-webkit-search-decoration{-webkit-appearance:none}::-webkit-file-upload-button{-webkit-appearance:button;font:inherit}summary{display:list-item}blockquote,dd,dl,figure,h1,h2,h3,h4,h5,h6,hr,p,pre{margin:0}fieldset{margin:0}fieldset,legend{padding:0}menu,ol,ul{list-style:none;margin:0;padding:0}textarea{resize:vertical}input::-moz-placeholder,textarea::-moz-placeholder{opacity:1;color:#9ca3af}input::placeholder,textarea::placeholder{opacity:1;color:#9ca3af}[role=button],button{cursor:pointer}:disabled{cursor:default}audio,canvas,embed,iframe,img,object,svg,video{display:block;vertical-align:middle}img,video{max-width:100%;height:auto}[hidden]{display:none}*,:after,:before{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgba(59,130,246,.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: }::backdrop{--tw-border-spacing-x:0;--tw-border-spacing-y:0;--tw-translate-x:0;--tw-translate-y:0;--tw-rotate:0;--tw-skew-x:0;--tw-skew-y:0;--tw-scale-x:1;--tw-scale-y:1;--tw-pan-x: ;--tw-pan-y: ;--tw-pinch-zoom: ;--tw-scroll-snap-strictness:proximity;--tw-gradient-from-position: ;--tw-gradient-via-position: ;--tw-gradient-to-position: ;--tw-ordinal: ;--tw-slashed-zero: ;--tw-numeric-figure: ;--tw-numeric-spacing: ;--tw-numeric-fraction: ;--tw-ring-inset: ;--tw-ring-offset-width:0px;--tw-ring-offset-color:#fff;--tw-ring-color:rgba(59,130,246,.5);--tw-ring-offset-shadow:0 0 #0000;--tw-ring-shadow:0 0 #0000;--tw-shadow:0 0 #0000;--tw-shadow-colored:0 0 #0000;--tw-blur: ;--tw-brightness: ;--tw-contrast: ;--tw-grayscale: ;--tw-hue-rotate: ;--tw-invert: ;--tw-saturate: ;--tw-sepia: ;--tw-drop-shadow: ;--tw-backdrop-blur: ;--tw-backdrop-brightness: ;--tw-backdrop-contrast: ;--tw-backdrop-grayscale: ;--tw-backdrop-hue-rotate: ;--tw-backdrop-invert: ;--tw-backdrop-opacity: ;--tw-backdrop-saturate: ;--tw-backdrop-sepia: }.prose{color:var(--tw-prose-body);max-width:65ch}.prose :where(p):not(:where([class~=not-prose] *)){margin-top:1.25em;margin-bottom:1.25em}.prose :where([class~=lead]):not(:where([class~=not-prose] *)){color:var(--tw-prose-lead);font-size:1.25em;line-height:1.6;margin-top:1.2em;margin-bottom:1.2em}.prose :where(a):not(:where([class~=not-prose] *)){color:var(--tw-prose-links);text-decoration:underline;font-weight:500}.prose :where(strong):not(:where([class~=not-prose] *)){color:var(--tw-prose-bold);font-weight:600}.prose :where(a strong):not(:where([class~=not-prose] *)){color:inherit}.prose :where(blockquote strong):not(:where([class~=not-prose] *)){color:inherit}.prose :where(thead th strong):not(:where([class~=not-prose] *)){color:inherit}.prose :where(ol):not(:where([class~=not-prose] *)){list-style-type:decimal;margin-top:1.25em;margin-bottom:1.25em;padding-left:1.625em}.prose :where(ol[type=A]):not(:where([class~=not-prose] *)){list-style-type:upper-alpha}.prose :where(ol[type=a]):not(:where([class~=not-prose] *)){list-style-type:lower-alpha}.prose :where(ol[type=A s]):not(:where([class~=not-prose] *)){list-style-type:upper-alpha}.prose :where(ol[type=a s]):not(:where([class~=not-prose] *)){list-style-type:lower-alpha}.prose :where(ol[type=I]):not(:where([class~=not-prose] *)){list-style-type:upper-roman}.prose :where(ol[type=i]):not(:where([class~=not-prose] *)){list-style-type:lower-roman}.prose :where(ol[type=I s]):not(:where([class~=not-prose] *)){list-style-type:upper-roman}.prose :where(ol[type=i s]):not(:where([class~=not-prose] *)){list-style-type:lower-roman}.prose :where(ol[type="1"]):not(:where([class~=not-prose] *)){list-style-type:decimal}.prose :where(ul):not(:where([class~=not-prose] *)){list-style-type:disc;margin-top:1.25em;margin-bottom:1.25em;padding-left:1.625em}.prose :where(ol>li):not(:where([class~=not-prose] *))::marker{font-weight:400;color:var(--tw-prose-counters)}.prose :where(ul>li):not(:where([class~=not-prose] *))::marker{color:var(--tw-prose-bullets)}.prose :where(hr):not(:where([class~=not-prose] *)){border-color:var(--tw-prose-hr);border-top-width:1px;margin-top:3em;margin-bottom:3em}.prose :where(blockquote):not(:where([class~=not-prose] *)){font-weight:500;font-style:italic;color:var(--tw-prose-quotes);border-left-width:.25rem;border-left-color:var(--tw-prose-quote-borders);quotes:"\201C""\201D""\2018""\2019";margin-top:1.6em;margin-bottom:1.6em;padding-left:1em}.prose :where(blockquote p:first-of-type):not(:where([class~=not-prose] *)):before{content:open-quote}.prose :where(blockquote p:last-of-type):not(:where([class~=not-prose] *)):after{content:close-quote}.prose :where(h1):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:800;font-size:2.25em;margin-top:0;margin-bottom:.8888889em;line-height:1.1111111}.prose :where(h1 strong):not(:where([class~=not-prose] *)){font-weight:900;color:inherit}.prose :where(h2):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:700;font-size:1.5em;margin-top:2em;margin-bottom:1em;line-height:1.3333333}.prose :where(h2 strong):not(:where([class~=not-prose] *)){font-weight:800;color:inherit}.prose :where(h3):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:600;font-size:1.25em;margin-top:1.6em;margin-bottom:.6em;line-height:1.6}.prose :where(h3 strong):not(:where([class~=not-prose] *)){font-weight:700;color:inherit}.prose :where(h4):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:600;margin-top:1.5em;margin-bottom:.5em;line-height:1.5}.prose :where(h4 strong):not(:where([class~=not-prose] *)){font-weight:700;color:inherit}.prose :where(img):not(:where([class~=not-prose] *)){margin-top:2em;margin-bottom:2em}.prose :where(figure>*):not(:where([class~=not-prose] *)){margin-top:0;margin-bottom:0}.prose :where(figcaption):not(:where([class~=not-prose] *)){color:var(--tw-prose-captions);font-size:.875em;line-height:1.4285714;margin-top:.8571429em}.prose :where(code):not(:where([class~=not-prose] *)){color:var(--tw-prose-code);font-weight:600;font-size:.875em}.prose :where(code):not(:where([class~=not-prose] *)):before{content:"`"}.prose :where(code):not(:where([class~=not-prose] *)):after{content:"`"}.prose :where(a code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(h1 code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(h2 code):not(:where([class~=not-prose] *)){color:inherit;font-size:.875em}.prose :where(h3 code):not(:where([class~=not-prose] *)){color:inherit;font-size:.9em}.prose :where(h4 code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(blockquote code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(thead th code):not(:where([class~=not-prose] *)){color:inherit}.prose :where(pre):not(:where([class~=not-prose] *)){color:var(--tw-prose-pre-code);background-color:var(--tw-prose-pre-bg);overflow-x:auto;font-weight:400;font-size:.875em;line-height:1.7142857;margin-top:1.7142857em;margin-bottom:1.7142857em;border-radius:.375rem;padding:.8571429em 1.1428571em}.prose :where(pre code):not(:where([class~=not-prose] *)){background-color:transparent;border-width:0;border-radius:0;padding:0;font-weight:inherit;color:inherit;font-size:inherit;font-family:inherit;line-height:inherit}.prose :where(pre code):not(:where([class~=not-prose] *)):before{content:none}.prose :where(pre code):not(:where([class~=not-prose] *)):after{content:none}.prose :where(table):not(:where([class~=not-prose] *)){width:100%;table-layout:auto;text-align:left;margin-top:2em;margin-bottom:2em;font-size:.875em;line-height:1.7142857}.prose :where(thead):not(:where([class~=not-prose] *)){border-bottom-width:1px;border-bottom-color:var(--tw-prose-th-borders)}.prose :where(thead th):not(:where([class~=not-prose] *)){color:var(--tw-prose-headings);font-weight:600;vertical-align:bottom;padding-right:.5714286em;padding-bottom:.5714286em;padding-left:.5714286em}.prose :where(tbody tr):not(:where([class~=not-prose] *)){border-bottom-width:1px;border-bottom-color:var(--tw-prose-td-borders)}.prose :where(tbody tr:last-child):not(:where([class~=not-prose] *)){border-bottom-width:0}.prose :where(tbody td):not(:where([class~=not-prose] *)){vertical-align:baseline}.prose :where(tfoot):not(:where([class~=not-prose] *)){border-top-width:1px;border-top-color:var(--tw-prose-th-borders)}.prose :where(tfoot td):not(:where([class~=not-prose] *)){vertical-align:top}.prose{--tw-prose-body:#374151;--tw-prose-headings:#111827;--tw-prose-lead:#4b5563;--tw-prose-links:#111827;--tw-prose-bold:#111827;--tw-prose-counters:#6b7280;--tw-prose-bullets:#d1d5db;--tw-prose-hr:#e5e7eb;--tw-prose-quotes:#111827;--tw-prose-quote-borders:#e5e7eb;--tw-prose-captions:#6b7280;--tw-prose-code:#111827;--tw-prose-pre-code:#e5e7eb;--tw-prose-pre-bg:#1f2937;--tw-prose-th-borders:#d1d5db;--tw-prose-td-borders:#e5e7eb;--tw-prose-invert-body:#d1d5db;--tw-prose-invert-headings:#fff;--tw-prose-invert-lead:#9ca3af;--tw-prose-invert-links:#fff;--tw-prose-invert-bold:#fff;--tw-prose-invert-counters:#9ca3af;--tw-prose-invert-bullets:#4b5563;--tw-prose-invert-hr:#374151;--tw-prose-invert-quotes:#f3f4f6;--tw-prose-invert-quote-borders:#374151;--tw-prose-invert-captions:#9ca3af;--tw-prose-invert-code:#fff;--tw-prose-invert-pre-code:#d1d5db;--tw-prose-invert-pre-bg:rgba(0,0,0,.5);--tw-prose-invert-th-borders:#4b5563;--tw-prose-invert-td-borders:#374151;font-size:1rem;line-height:1.75}.prose :where(video):not(:where([class~=not-prose] *)){margin-top:2em;margin-bottom:2em}.prose :where(figure):not(:where([class~=not-prose] *)){margin-top:2em;margin-bottom:2em}.prose :where(li):not(:where([class~=not-prose] *)){margin-top:.5em;margin-bottom:.5em}.prose :where(ol>li):not(:where([class~=not-prose] *)){padding-left:.375em}.prose :where(ul>li):not(:where([class~=not-prose] *)){padding-left:.375em}.prose :where(.prose>ul>li p):not(:where([class~=not-prose] *)){margin-top:.75em;margin-bottom:.75em}.prose :where(.prose>ul>li>:first-child):not(:where([class~=not-prose] *)){margin-top:1.25em}.prose :where(.prose>ul>li>:last-child):not(:where([class~=not-prose] *)){margin-bottom:1.25em}.prose :where(.prose>ol>li>:first-child):not(:where([class~=not-prose] *)){margin-top:1.25em}.prose :where(.prose>ol>li>:last-child):not(:where([class~=not-prose] *)){margin-bottom:1.25em}.prose :where(ul ul,ul ol,ol ul,ol ol):not(:where([class~=not-prose] *)){margin-top:.75em;margin-bottom:.75em}.prose :where(hr+*):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(h2+*):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(h3+*):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(h4+*):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(thead th:first-child):not(:where([class~=not-prose] *)){padding-left:0}.prose :where(thead th:last-child):not(:where([class~=not-prose] *)){padding-right:0}.prose :where(tbody td,tfoot td):not(:where([class~=not-prose] *)){padding:.5714286em}.prose :where(tbody td:first-child,tfoot td:first-child):not(:where([class~=not-prose] *)){padding-left:0}.prose :where(tbody td:last-child,tfoot td:last-child):not(:where([class~=not-prose] *)){padding-right:0}.prose :where(.prose>:first-child):not(:where([class~=not-prose] *)){margin-top:0}.prose :where(.prose>:last-child):not(:where([class~=not-prose] *)){margin-bottom:0}.prose-sm{font-size:.875rem;line-height:1.7142857}.prose-sm :where(p):not(:where([class~=not-prose] *)){margin-top:1.1428571em;margin-bottom:1.1428571em}.prose-sm :where([class~=lead]):not(:where([class~=not-prose] *)){font-size:1.2857143em;line-height:1.5555556;margin-top:.8888889em;margin-bottom:.8888889em}.prose-sm :where(blockquote):not(:where([class~=not-prose] *)){margin-top:1.3333333em;margin-bottom:1.3333333em;padding-left:1.1111111em}.prose-sm :where(h1):not(:where([class~=not-prose] *)){font-size:2.1428571em;margin-top:0;margin-bottom:.8em;line-height:1.2}.prose-sm :where(h2):not(:where([class~=not-prose] *)){font-size:1.4285714em;margin-top:1.6em;margin-bottom:.8em;line-height:1.4}.prose-sm :where(h3):not(:where([class~=not-prose] *)){font-size:1.2857143em;margin-top:1.5555556em;margin-bottom:.4444444em;line-height:1.5555556}.prose-sm :where(h4):not(:where([class~=not-prose] *)){margin-top:1.4285714em;margin-bottom:.5714286em;line-height:1.4285714}.prose-sm :where(img):not(:where([class~=not-prose] *)){margin-top:1.7142857em;margin-bottom:1.7142857em}.prose-sm :where(video):not(:where([class~=not-prose] *)){margin-top:1.7142857em;margin-bottom:1.7142857em}.prose-sm :where(figure):not(:where([class~=not-prose] *)){margin-top:1.7142857em;margin-bottom:1.7142857em}.prose-sm :where(figure>*):not(:where([class~=not-prose] *)){margin-top:0;margin-bottom:0}.prose-sm :where(figcaption):not(:where([class~=not-prose] *)){font-size:.8571429em;line-height:1.3333333;margin-top:.6666667em}.prose-sm :where(code):not(:where([class~=not-prose] *)){font-size:.8571429em}.prose-sm :where(h2 code):not(:where([class~=not-prose] *)){font-size:.9em}.prose-sm :where(h3 code):not(:where([class~=not-prose] *)){font-size:.8888889em}.prose-sm :where(pre):not(:where([class~=not-prose] *)){font-size:.8571429em;line-height:1.6666667;margin-top:1.6666667em;margin-bottom:1.6666667em;border-radius:.25rem;padding:.6666667em 1em}.prose-sm :where(ol):not(:where([class~=not-prose] *)){margin-top:1.1428571em;margin-bottom:1.1428571em;padding-left:1.5714286em}.prose-sm :where(ul):not(:where([class~=not-prose] *)){margin-top:1.1428571em;margin-bottom:1.1428571em;padding-left:1.5714286em}.prose-sm :where(li):not(:where([class~=not-prose] *)){margin-top:.2857143em;margin-bottom:.2857143em}.prose-sm :where(ol>li):not(:where([class~=not-prose] *)){padding-left:.4285714em}.prose-sm :where(ul>li):not(:where([class~=not-prose] *)){padding-left:.4285714em}.prose-sm :where(.prose-sm>ul>li p):not(:where([class~=not-prose] *)){margin-top:.5714286em;margin-bottom:.5714286em}.prose-sm :where(.prose-sm>ul>li>:first-child):not(:where([class~=not-prose] *)){margin-top:1.1428571em}.prose-sm :where(.prose-sm>ul>li>:last-child):not(:where([class~=not-prose] *)){margin-bottom:1.1428571em}.prose-sm :where(.prose-sm>ol>li>:first-child):not(:where([class~=not-prose] *)){margin-top:1.1428571em}.prose-sm :where(.prose-sm>ol>li>:last-child):not(:where([class~=not-prose] *)){margin-bottom:1.1428571em}.prose-sm :where(ul ul,ul ol,ol ul,ol ol):not(:where([class~=not-prose] *)){margin-top:.5714286em;margin-bottom:.5714286em}.prose-sm :where(hr):not(:where([class~=not-prose] *)){margin-top:2.8571429em;margin-bottom:2.8571429em}.prose-sm :where(hr+*):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(h2+*):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(h3+*):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(h4+*):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(table):not(:where([class~=not-prose] *)){font-size:.8571429em;line-height:1.5}.prose-sm :where(thead th):not(:where([class~=not-prose] *)){padding-right:1em;padding-bottom:.6666667em;padding-left:1em}.prose-sm :where(thead th:first-child):not(:where([class~=not-prose] *)){padding-left:0}.prose-sm :where(thead th:last-child):not(:where([class~=not-prose] *)){padding-right:0}.prose-sm :where(tbody td,tfoot td):not(:where([class~=not-prose] *)){padding:.6666667em 1em}.prose-sm :where(tbody td:first-child,tfoot td:first-child):not(:where([class~=not-prose] *)){padding-left:0}.prose-sm :where(tbody td:last-child,tfoot td:last-child):not(:where([class~=not-prose] *)){padding-right:0}.prose-sm :where(.prose-sm>:first-child):not(:where([class~=not-prose] *)){margin-top:0}.prose-sm :where(.prose-sm>:last-child):not(:where([class~=not-prose] *)){margin-bottom:0}.absolute{position:absolute}.relative{position:relative}.bottom-1{bottom:.25rem}.right-1{right:.25rem}.right-2{right:.5rem}.top-2{top:.5rem}.ml-12{margin-left:3rem}.ml-4{margin-left:1rem}.mr-12{margin-right:3rem}.mr-4{margin-right:1rem}.\!inline{display:inline!important}.inline{display:inline}.flex{display:flex}.h-4{height:1rem}.h-8{height:2rem}.w-4{width:1rem}.w-8{width:2rem}.max-w-none{max-width:none}.flex-1{flex:1 1 0%}.flex-row{flex-direction:row}.flex-row-reverse{flex-direction:row-reverse}.justify-around{justify-content:space-around}.overflow-x-auto{overflow-x:auto}.whitespace-pre-wrap{white-space:pre-wrap}.break-words{overflow-wrap:break-word}.rounded{border-radius:.25rem}.rounded-md{border-radius:.375rem}.rounded-xl{border-radius:.75rem}.border{border-width:1px}.border-blue-200{--tw-border-opacity:1;border-color:rgb(191 219 254/var(--tw-border-opacity))}.border-green-200{--tw-border-opacity:1;border-color:rgb(187 247 208/var(--tw-border-opacity))}.border-orange-200{--tw-border-opacity:1;border-color:rgb(254 215 170/var(--tw-border-opacity))}.bg-blue-50{--tw-bg-opacity:1;background-color:rgb(239 246 255/var(--tw-bg-opacity))}.bg-gray-200{--tw-bg-opacity:1;background-color:rgb(229 231 235/var(--tw-bg-opacity))}.bg-gray-600{--tw-bg-opacity:1;background-color:rgb(75 85 99/var(--tw-bg-opacity))}.bg-green-50{--tw-bg-opacity:1;background-color:rgb(240 253 244/var(--tw-bg-opacity))}.bg-orange-100{--tw-bg-opacity:1;background-color:rgb(255 237 213/var(--tw-bg-opacity))}.p-1{padding:.25rem}.px-4{padding-left:1rem;padding-right:1rem}.py-3{padding-top:.75rem;padding-bottom:.75rem}.pb-2{padding-bottom:.5rem}.font-mono{font-family:ui-monospace,SFMono-Regular,Menlo,Monaco,Consolas,Liberation Mono,Courier New,monospace}.text-sm{font-size:.875rem;line-height:1.25rem}.text-xs{font-size:.75rem;line-height:1rem}.text-white{--tw-text-opacity:1;color:rgb(255 255 255/var(--tw-text-opacity))}.opacity-50{opacity:.5}.opacity-60{opacity:.6}.shadow{--tw-shadow:0 1px 3px 0 rgba(0,0,0,.1),0 1px 2px -1px rgba(0,0,0,.1);--tw-shadow-colored:0 1px 3px 0 var(--tw-shadow-color),0 1px 2px -1px var(--tw-shadow-color)}.shadow,.shadow-md{box-shadow:var(--tw-ring-offset-shadow,0 0 #0000),var(--tw-ring-shadow,0 0 #0000),var(--tw-shadow)}.shadow-md{--tw-shadow:0 4px 6px -1px rgba(0,0,0,.1),0 2px 4px -2px rgba(0,0,0,.1);--tw-shadow-colored:0 4px 6px -1px var(--tw-shadow-color),0 2px 4px -2px var(--tw-shadow-color)}.hover\:bg-gray-500:hover{--tw-bg-opacity:1;background-color:rgb(107 114 128/var(--tw-bg-opacity))}
```

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.1608a09b.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.1608a09b.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.4aafdb68.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.4aafdb68.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.a79f1c31.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_AMS-Regular.a79f1c31.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.b6770918.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.b6770918.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.cce5b8ec.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.cce5b8ec.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.ec17d132.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Bold.ec17d132.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.07ef19e7.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.07ef19e7.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.55fac258.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.55fac258.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.dad44a7f.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Caligraphic-Regular.dad44a7f.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.9f256b85.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.9f256b85.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.b18f59e1.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.b18f59e1.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.d42a5579.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Bold.d42a5579.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.7c187121.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.7c187121.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.d3c882a6.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.d3c882a6.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.ed38e79f.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Fraktur-Regular.ed38e79f.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.b74a1a8b.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.b74a1a8b.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.c3fb5ac2.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.c3fb5ac2.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.d181c465.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Bold.d181c465.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.6f2bb1df.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.6f2bb1df.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.70d8b0a5.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.70d8b0a5.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.e3f82f9d.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-BoldItalic.e3f82f9d.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.47373d1e.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.47373d1e.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.8916142b.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.8916142b.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.9024d815.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Italic.9024d815.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.0462f03b.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.0462f03b.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.7f51fe03.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.7f51fe03.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.b7f8fe9b.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Main-Regular.b7f8fe9b.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.572d331f.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.572d331f.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.a879cf83.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.a879cf83.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.f1035d8d.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-BoldItalic.f1035d8d.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.5295ba48.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.5295ba48.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.939bc644.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.939bc644.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.f28c23ac.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Math-Italic.f28c23ac.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.8c5b5494.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.8c5b5494.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.94e1e8dc.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.94e1e8dc.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.bf59d231.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Bold.bf59d231.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.3b1e59b3.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.3b1e59b3.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.7c9bc82b.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.7c9bc82b.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.b4c20c84.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Italic.b4c20c84.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.74048478.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.74048478.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.ba21ed5f.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.ba21ed5f.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.d4d7ba48.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_SansSerif-Regular.d4d7ba48.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.03e9641d.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.03e9641d.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.07505710.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.07505710.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.fe9cbbe1.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Script-Regular.fe9cbbe1.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.e1e279cb.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.e1e279cb.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.eae34984.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.eae34984.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.fabc004a.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size1-Regular.fabc004a.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.57727022.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.57727022.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.5916a24f.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.5916a24f.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.d6b476ec.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size2-Regular.d6b476ec.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.9acaf01c.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.9acaf01c.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.a144ef58.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.a144ef58.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.b4230e7e.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size3-Regular.b4230e7e.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.10d95fd3.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.10d95fd3.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.7a996c9d.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.7a996c9d.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.fbccdabe.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Size4-Regular.fbccdabe.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.6258592b.woff` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.6258592b.woff`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.a8709e36.woff2` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.a8709e36.woff2`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.d97aaf4a.ttf` & `st_chat_message-0.3.8/st_chat_message/frontend/out/_next/static/media/KaTeX_Typewriter-Regular.d97aaf4a.ttf`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/favicon.ico` & `st_chat_message-0.3.8/st_chat_message/frontend/out/favicon.ico`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/index.html` & `st_chat_message-0.3.8/st_chat_message/frontend/out/index.html`

 * *Files 5% similar despite different names*

```diff
@@ -1 +1 @@
-<!DOCTYPE html><html><head><meta charSet="utf-8"/><meta name="viewport" content="width=device-width"/><title>Create Next App</title><meta name="description" content="Generated by create next app"/><link rel="icon" href="/favicon.ico"/><meta name="next-head-count" content="5"/><link data-next-font="" rel="preconnect" href="/" crossorigin="anonymous"/><link rel="preload" href="/component/st_chat_message.st_chat_message/_next/static/css/2c1d693913146cab.css" as="style"/><link rel="stylesheet" href="/component/st_chat_message.st_chat_message/_next/static/css/2c1d693913146cab.css" data-n-g=""/><link rel="preload" href="/component/st_chat_message.st_chat_message/_next/static/css/1f759626be541cb1.css" as="style"/><link rel="stylesheet" href="/component/st_chat_message.st_chat_message/_next/static/css/1f759626be541cb1.css" data-n-p=""/><noscript data-n-css=""></noscript><script defer="" nomodule="" src="/component/st_chat_message.st_chat_message/_next/static/chunks/polyfills-78c92fac7aa8fdd8.js"></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/webpack-9d2bee59a0ebae7b.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/framework-5e8ac8dd643904dd.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/main-c6459c6dbdcff8e8.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/pages/_app-345c8177130438ac.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/175675d1-280cba64f0247428.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/pages/index-56e240b261b33c91.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/Dg5cdAEY-RCHv3LVfP7Lo/_buildManifest.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/Dg5cdAEY-RCHv3LVfP7Lo/_ssgManifest.js" defer=""></script></head><body><div id="__next"></div><script id="__NEXT_DATA__" type="application/json">{"props":{"pageProps":{}},"page":"/","query":{},"buildId":"Dg5cdAEY-RCHv3LVfP7Lo","assetPrefix":"/component/st_chat_message.st_chat_message","nextExport":true,"autoExport":true,"isFallback":false,"scriptLoader":[]}</script></body></html>
+<!DOCTYPE html><html><head><meta charSet="utf-8"/><meta name="viewport" content="width=device-width"/><title>Create Next App</title><meta name="description" content="Generated by create next app"/><link rel="icon" href="/favicon.ico"/><meta name="next-head-count" content="5"/><link data-next-font="" rel="preconnect" href="/" crossorigin="anonymous"/><link rel="preload" href="/component/st_chat_message.st_chat_message/_next/static/css/ecb6d8ff2db7565c.css" as="style"/><link rel="stylesheet" href="/component/st_chat_message.st_chat_message/_next/static/css/ecb6d8ff2db7565c.css" data-n-g=""/><link rel="preload" href="/component/st_chat_message.st_chat_message/_next/static/css/1f759626be541cb1.css" as="style"/><link rel="stylesheet" href="/component/st_chat_message.st_chat_message/_next/static/css/1f759626be541cb1.css" data-n-p=""/><noscript data-n-css=""></noscript><script defer="" nomodule="" src="/component/st_chat_message.st_chat_message/_next/static/chunks/polyfills-78c92fac7aa8fdd8.js"></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/webpack-9d2bee59a0ebae7b.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/framework-5e8ac8dd643904dd.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/main-c6459c6dbdcff8e8.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/pages/_app-345c8177130438ac.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/175675d1-280cba64f0247428.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/chunks/pages/index-df2a1fafbbf92047.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/6ygvE_r4CKVPLu_JlsWil/_buildManifest.js" defer=""></script><script src="/component/st_chat_message.st_chat_message/_next/static/6ygvE_r4CKVPLu_JlsWil/_ssgManifest.js" defer=""></script></head><body><div id="__next"></div><script id="__NEXT_DATA__" type="application/json">{"props":{"pageProps":{}},"page":"/","query":{},"buildId":"6ygvE_r4CKVPLu_JlsWil","assetPrefix":"/component/st_chat_message.st_chat_message","nextExport":true,"autoExport":true,"isFallback":false,"scriptLoader":[]}</script></body></html>
```

### Comparing `st_chat_message-0.3.6/st_chat_message/frontend/out/vercel.svg` & `st_chat_message-0.3.8/st_chat_message/frontend/out/vercel.svg`

 * *Files identical despite different names*

### Comparing `st_chat_message-0.3.6/setup.py` & `st_chat_message-0.3.8/setup.py`

 * *Files 3% similar despite different names*

```diff
@@ -3,26 +3,26 @@
 
 packages = \
 ['st_chat_message']
 
 package_data = \
 {'': ['*'],
  'st_chat_message': ['frontend/out/*',
-                     'frontend/out/_next/static/Dg5cdAEY-RCHv3LVfP7Lo/*',
+                     'frontend/out/_next/static/6ygvE_r4CKVPLu_JlsWil/*',
                      'frontend/out/_next/static/chunks/*',
                      'frontend/out/_next/static/chunks/pages/*',
                      'frontend/out/_next/static/css/*',
                      'frontend/out/_next/static/media/*']}
 
 install_requires = \
 ['streamlit>=0.63']
 
 setup_kwargs = {
     'name': 'st-chat-message',
-    'version': '0.3.6',
+    'version': '0.3.8',
     'description': 'A Streamlit component to display chat messages',
     'long_description': '# st-chat-message\n\n## Description\n\nThis is a simple chat message component for streamlit. It is based on the [streamlit-chat](https://github.com/AI-Yash/st-chat) component, trying to be as compatible as possible, but it adding a few features:\n\n- Markdown support\n- LaTeX support\n- Tables\n\n## Installation\n\n```bash\npip install st-chat-message\n```\n\nor\n\n```bash\npoetry add st-chat-message\n```\n## Usage\n\n```python\nimport streamlit as st\nfrom st_chat_message import message\n\nmessage("Hello world!", is_user=True)\nmessage("Hi")\n```\n\n![img.png](docs/img.png)\n\n## Buiding from source\n\n### Prerequisites\n\n- nodejs >= 18.x\n- yarn >= 1.22.x\n- poetry >= 1.2.x\n- python >= 3.8.x\n\n### Building\n\n```bash\n./build.sh\n```\n\n### Publishing\n\n```bash\npoetry publish \n```\n\n\n## License\n\nThis project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details\n',
     'author': 'Manolo Santos',
     'author_email': 'manolo.santos@gmail.com',
     'maintainer': 'None',
     'maintainer_email': 'None',
     'url': 'None',
```

### Comparing `st_chat_message-0.3.6/PKG-INFO` & `st_chat_message-0.3.8/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: st-chat-message
-Version: 0.3.6
+Version: 0.3.8
 Summary: A Streamlit component to display chat messages
 License: MIT
 Author: Manolo Santos
 Author-email: manolo.santos@gmail.com
 Requires-Python: >=3.8, !=2.7.*, !=3.0.*, !=3.1.*, !=3.2.*, !=3.3.*, !=3.4.*, !=3.5.*, !=3.6.*, !=3.7.*
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
```


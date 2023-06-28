# Comparing `tmp/home-assistant-intents-2023.6.28.tar.gz` & `tmp/home-assistant-intents-2023.6.5.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "home-assistant-intents-2023.6.28.tar", last modified: Wed Jun 28 14:15:07 2023, max compression
+gzip compressed data, was "home-assistant-intents-2023.6.5.tar", last modified: Mon Jun  5 15:46:39 2023, max compression
```

## Comparing `home-assistant-intents-2023.6.28.tar` & `home-assistant-intents-2023.6.5.tar`

### file list

```diff
@@ -1,128 +1,125 @@
-drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-28 14:15:07.779174 home-assistant-intents-2023.6.28/
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    18657 2023-02-15 17:17:10.000000 home-assistant-intents-2023.6.28/LICENSE.md
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)       72 2023-01-11 16:06:16.000000 home-assistant-intents-2023.6.28/MANIFEST.in
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1287 2023-06-28 14:15:07.779174 home-assistant-intents-2023.6.28/PKG-INFO
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      523 2023-05-30 16:59:24.000000 home-assistant-intents-2023.6.28/README.md
-drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-28 14:15:07.771174 home-assistant-intents-2023.6.28/home_assistant_intents/
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      935 2023-04-17 16:30:47.000000 home-assistant-intents-2023.6.28/home_assistant_intents/__init__.py
-drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-28 14:15:07.771174 home-assistant-intents-2023.6.28/home_assistant_intents/data/
-drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-28 14:15:07.775174 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    15762 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ar.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    54168 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/bg.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1903 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/bn.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    12544 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ca.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    21247 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/cs.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    19985 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/da.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    19712 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/de-CH.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    35995 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/de.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    61958 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/el.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    56864 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/en.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14986 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/es.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      975 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/et.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     6147 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/eu.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2885 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/fa.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    40173 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/fi.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     6747 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/fr-CA.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    78566 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/fr.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     5245 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/gl.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1373 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/gu.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    16181 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/he.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1525 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/hi.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    18547 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/hr.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     7330 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/hu.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3603 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/id.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3834 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/is.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14790 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/it.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3331 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ka.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1197 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/kn.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    59207 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ko.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11801 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/lb.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11322 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/lt.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     8002 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/lv.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11714 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ml.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1367 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/mn.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     4824 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ms.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    16333 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/nb.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    75862 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/nl.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    28368 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/pl.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     7860 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/pt-br.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    13050 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/pt.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    51451 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ro.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14961 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ru.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11029 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sk.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3079 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sl.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     4312 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sr.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11472 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sv.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1197 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sw.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1760 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/te.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     5477 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/tr.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14445 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/uk.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14341 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ur.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    12024 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/vi.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    16782 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/zh-cn.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    13464 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/zh-hk.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)    38206 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/zh-tw.json
-drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-28 14:15:07.779174 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3727 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ar.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     4257 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/bg.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/bn.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      725 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ca.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3620 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/cs.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1479 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/da.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1696 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/de-CH.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2248 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/de.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1209 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/el.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3236 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/en.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1608 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/es.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      180 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/eu.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/fa.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     5421 2023-06-28 14:15:03.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/fi.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1876 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/fr-CA.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3063 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/fr.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1350 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/gl.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/gu.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1223 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/he.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/hi.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2274 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/hr.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1723 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/hu.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1258 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/id.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      422 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/is.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1774 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/it.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      598 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ka.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/kn.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3222 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ko.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2574 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/lb.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2145 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/lt.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2062 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/lv.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2720 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ml.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/mn.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1368 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ms.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2174 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/nb.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2594 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/nl.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1163 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/pl.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      419 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/pt-br.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1950 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/pt.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3315 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ro.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1857 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ru.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1548 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/sk.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/sl.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1554 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/sr.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2563 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/sv.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/sw.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/te.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/tr.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1681 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/uk.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1405 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ur.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1510 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/vi.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2172 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/zh-cn.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2008 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/zh-hk.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2322 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/data/light/zh-tw.json
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1642 2023-06-28 14:15:04.000000 home-assistant-intents-2023.6.28/home_assistant_intents/domains.py
-drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-28 14:15:07.775174 home-assistant-intents-2023.6.28/home_assistant_intents.egg-info/
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1287 2023-06-28 14:15:07.000000 home-assistant-intents-2023.6.28/home_assistant_intents.egg-info/PKG-INFO
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     5395 2023-06-28 14:15:07.000000 home-assistant-intents-2023.6.28/home_assistant_intents.egg-info/SOURCES.txt
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)        1 2023-06-28 14:15:07.000000 home-assistant-intents-2023.6.28/home_assistant_intents.egg-info/dependency_links.txt
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)       23 2023-06-28 14:15:07.000000 home-assistant-intents-2023.6.28/home_assistant_intents.egg-info/top_level.txt
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)        1 2023-05-30 16:35:50.000000 home-assistant-intents-2023.6.28/home_assistant_intents.egg-info/zip-safe
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1036 2023-06-28 14:14:01.000000 home-assistant-intents-2023.6.28/pyproject.toml
--rw-r--r--   0 hansenm   (1000) hansenm   (1000)       38 2023-06-28 14:15:07.779174 home-assistant-intents-2023.6.28/setup.cfg
+drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-05 15:46:39.333424 home-assistant-intents-2023.6.5/
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    18657 2023-02-15 17:17:10.000000 home-assistant-intents-2023.6.5/LICENSE.md
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)       72 2023-01-11 16:06:16.000000 home-assistant-intents-2023.6.5/MANIFEST.in
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1286 2023-06-05 15:46:39.333424 home-assistant-intents-2023.6.5/PKG-INFO
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      523 2023-05-30 16:59:24.000000 home-assistant-intents-2023.6.5/README.md
+drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-05 15:46:39.325424 home-assistant-intents-2023.6.5/home_assistant_intents/
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      935 2023-04-17 16:30:47.000000 home-assistant-intents-2023.6.5/home_assistant_intents/__init__.py
+drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-05 15:46:39.325424 home-assistant-intents-2023.6.5/home_assistant_intents/data/
+drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-05 15:46:39.329424 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    15762 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ar.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    54166 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/bg.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1903 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/bn.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    12544 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ca.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    21247 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/cs.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    19985 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/da.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    19712 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/de-CH.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    35995 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/de.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    61958 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/el.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    56864 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/en.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14986 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/es.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2885 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/fa.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    40173 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/fi.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     6747 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/fr-CA.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    78566 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/fr.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     5245 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/gl.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1373 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/gu.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    16181 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/he.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1525 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/hi.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    18547 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/hr.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     7330 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/hu.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3603 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/id.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3834 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/is.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14790 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/it.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3331 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ka.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1197 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/kn.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3160 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ko.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11801 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/lb.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11322 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/lt.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     8002 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/lv.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11714 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ml.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1367 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/mn.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     4824 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ms.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    16333 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/nb.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    74600 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/nl.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    28368 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/pl.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     7860 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/pt-br.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    13050 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/pt.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    51451 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ro.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14961 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ru.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11029 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sk.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3079 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sl.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     4312 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sr.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    11472 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sv.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1197 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sw.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1296 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/te.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     5477 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/tr.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14445 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/uk.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    14341 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ur.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    12024 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/vi.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    16782 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/zh-cn.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    13464 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/zh-hk.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)    38206 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/zh-tw.json
+drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-05 15:46:39.333424 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3727 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ar.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     4257 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/bg.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/bn.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      725 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ca.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3620 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/cs.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1479 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/da.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1696 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/de-CH.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2248 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/de.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1209 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/el.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3236 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/en.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1608 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/es.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:32.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/fa.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     5421 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/fi.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1876 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/fr-CA.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3063 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/fr.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1350 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/gl.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/gu.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1223 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/he.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/hi.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2274 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/hr.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1723 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/hu.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1258 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/id.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      422 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/is.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1774 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/it.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      598 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ka.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/kn.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      180 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ko.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2574 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/lb.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2145 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/lt.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2062 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/lv.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2720 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ml.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/mn.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1368 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ms.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2174 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/nb.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2594 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/nl.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1163 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/pl.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      419 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/pt-br.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1950 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/pt.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     3315 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ro.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1857 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ru.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1548 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/sk.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/sl.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1554 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/sr.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2563 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/sv.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/sw.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/te.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)      416 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/tr.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1681 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/uk.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1405 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ur.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1510 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/vi.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2172 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/zh-cn.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2008 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/zh-hk.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     2322 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/data/light/zh-tw.json
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1600 2023-06-05 15:46:33.000000 home-assistant-intents-2023.6.5/home_assistant_intents/domains.py
+drwxr-xr-x   0 hansenm   (1000) hansenm   (1000)        0 2023-06-05 15:46:39.325424 home-assistant-intents-2023.6.5/home_assistant_intents.egg-info/
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1286 2023-06-05 15:46:38.000000 home-assistant-intents-2023.6.5/home_assistant_intents.egg-info/PKG-INFO
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     5253 2023-06-05 15:46:39.000000 home-assistant-intents-2023.6.5/home_assistant_intents.egg-info/SOURCES.txt
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)        1 2023-06-05 15:46:38.000000 home-assistant-intents-2023.6.5/home_assistant_intents.egg-info/dependency_links.txt
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)       23 2023-06-05 15:46:39.000000 home-assistant-intents-2023.6.5/home_assistant_intents.egg-info/top_level.txt
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)        1 2023-05-30 16:35:50.000000 home-assistant-intents-2023.6.5/home_assistant_intents.egg-info/zip-safe
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)     1035 2023-06-05 15:45:56.000000 home-assistant-intents-2023.6.5/pyproject.toml
+-rw-r--r--   0 hansenm   (1000) hansenm   (1000)       38 2023-06-05 15:46:39.333424 home-assistant-intents-2023.6.5/setup.cfg
```

### Comparing `home-assistant-intents-2023.6.28/LICENSE.md` & `home-assistant-intents-2023.6.5/LICENSE.md`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/PKG-INFO` & `home-assistant-intents-2023.6.5/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: home-assistant-intents
-Version: 2023.6.28
+Version: 2023.6.5
 Summary: Intents for Home Assistant
 Author-email: The Home Assistant Authors <hello@home-assistant.io>
 License: Apache-2.0
 Project-URL: Source Code, https://github.com/home-assistant/intents
 Keywords: home,assistant,intent,recognition
 Platform: any
 Classifier: Development Status :: 3 - Alpha
```

### Comparing `home-assistant-intents-2023.6.28/README.md` & `home-assistant-intents-2023.6.5/README.md`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/__init__.py` & `home-assistant-intents-2023.6.5/home_assistant_intents/__init__.py`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ar.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ar.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/bg.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/bg.json`

 * *Files 0% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.999951774691358%*

 * *Differences: {"'lists'": "{'on_off_domains': {'values': {0: {'in': "*

 * *            "'свтлин(а|и|ата|ите)|ламп(а|и|ата|ите)|крушк(а|и|ата|ите)|осветлен(ия|ие|ието|ията)'}}}}"}*

```diff
@@ -1315,15 +1315,15 @@
                     "out": "unlocked"
                 }
             ]
         },
         "on_off_domains": {
             "values": [
                 {
-                    "in": "\u0441\u0432\u0435\u0442\u043b\u0438\u043d(\u0430|\u0438|\u0430\u0442\u0430|\u0438\u0442\u0435)|\u043b\u0430\u043c\u043f(\u0430|\u0438|\u0430\u0442\u0430|\u0438\u0442\u0435)|\u043a\u0440\u0443\u0448\u043a(\u0430|\u0438|\u0430\u0442\u0430|\u0438\u0442\u0435)|\u043e\u0441\u0432\u0435\u0442\u043b\u0435\u043d(\u0438\u044f|\u0438\u0435|\u0438\u0435\u0442\u043e|\u0438\u044f\u0442\u0430)",
+                    "in": "\u0441\u0432\u0442\u043b\u0438\u043d(\u0430|\u0438|\u0430\u0442\u0430|\u0438\u0442\u0435)|\u043b\u0430\u043c\u043f(\u0430|\u0438|\u0430\u0442\u0430|\u0438\u0442\u0435)|\u043a\u0440\u0443\u0448\u043a(\u0430|\u0438|\u0430\u0442\u0430|\u0438\u0442\u0435)|\u043e\u0441\u0432\u0435\u0442\u043b\u0435\u043d(\u0438\u044f|\u0438\u0435|\u0438\u0435\u0442\u043e|\u0438\u044f\u0442\u0430)",
                     "out": "light"
                 },
                 {
                     "in": "\u0432\u0435\u043d\u0442\u0438\u043b\u0430\u0442\u043e\u0440[\u0438|\u0430|\u044a\u0442|\u0438\u0442\u0435]",
                     "out": "fan"
                 },
                 {
```

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/bn.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/bn.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ca.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ca.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/cs.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/cs.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/da.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/da.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/de-CH.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/de-CH.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/de.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/de.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/el.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/el.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/en.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/en.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/es.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/es.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/et.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/pl.json`

 * *Files 27% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.2708333333333333%*

 * *Differences: {"'intents'": "{replace: OrderedDict([('HassLightSet', OrderedDict([('data', "*

 * *              "[OrderedDict([('sentences', ['<set> [jasność] <name> na <brightness>']), "*

 * *              "('response', 'brightness')]), OrderedDict([('sentences', ['<set> [jasność] <area> "*

 * *              "na <brightness>']), ('slots', OrderedDict([('name', 'all')])), ('response', "*

 * *              "'brightness_area')]), OrderedDict([('sentences', ['<set> [kolor] <name> na "*

 * *              "{color}']), ('response', 'color')]), Ordered […]*

```diff
@@ -1,46 +1,46 @@
 {
-    "expansion_rules": {},
     "intents": {
-        "HassTurnOff": {
+        "HassLightSet": {
             "data": [
                 {
+                    "response": "brightness",
                     "sentences": [
-                        "kustuta {name}"
+                        "<set> [jasno\u015b\u0107] <name> na <brightness>"
                     ]
-                }
-            ]
-        },
-        "HassTurnOn": {
-            "data": [
+                },
+                {
+                    "response": "brightness_area",
+                    "sentences": [
+                        "<set> [jasno\u015b\u0107] <area> na <brightness>"
+                    ],
+                    "slots": {
+                        "name": "all"
+                    }
+                },
                 {
+                    "response": "color",
                     "sentences": [
-                        "{name} p\u00f5lema"
+                        "<set> [kolor] <name> na {color}"
+                    ]
+                },
+                {
+                    "response": "color_area",
+                    "sentences": [
+                        "<set> [wszystkie kolory|kolory] <area> na {color}"
                     ]
                 }
             ]
         }
     },
-    "language": "et",
-    "lists": {},
+    "language": "pl",
     "responses": {
-        "errors": {
-            "handle_error": "Soovi t\u00f6\u00f6tlemisel tekkis tundmatu viga",
-            "no_area": "Puudub ala nimega {{ area }}",
-            "no_device_class": "{{ area }} ei sisalda {{ device_class }}",
-            "no_domain": "{{ area }} ei sisalda {{ domain }}",
-            "no_entity": "Puudub seade v\u00f5i \u00fcksus nimega {{ entity }}",
-            "no_intent": "Vabandust, ma ei saanud aru"
-        },
         "intents": {
-            "HassTurnOff": {
-                "default": "Turned off {{ slots.name }}"
-            },
-            "HassTurnOn": {
-                "default": "Turned on {{ slots.name }}"
+            "HassLightSet": {
+                "brightness": "Ustawiono jasno\u015b\u0107 {{ slots.name }} na {{ slots.brightness }}",
+                "brightness_area": "Ustawiono jasno\u015b\u0107 w {{ slots.area }} na {{ slots.brightness }}",
+                "color": "Ustawiono kolor {{ slots.name }} na {{ slots.color }}",
+                "color_area": "Ustawiono kolor w {{ slots.area }} na {{ slots.color }}"
             }
         }
-    },
-    "skip_words": [
-        "palun"
-    ]
+    }
 }
```

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/eu.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/tr.json`

 * *Files 27% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.6849647266313933%*

 * *Differences: {"'expansion_rules'": "{'name': '{name}<cogulluk><ismin_halleri>', 'area': "*

 * *                      "'{area}<ismin_halleri>', 'ismin_halleri': "*

 * *                      "'[([(n|ın|in|un|ün|y|t|d|nd|nt)]ı|[(n|ın|in|un|ün|y|t|d|nd|nt)]i|[(n|ın|in|un|ün|y|t|d|nd|nt)]ü|[(n|ın|in|un|ün|y|t|d|nd|nt)]u|[(n|ın|in|un|ün|y|t|d|nd|nt)]e|[(n|ın|in|un|ün|y|t|d|nd|nt)]a)][n][ki]', "*

 * *                      "'cogulluk': '[(ler|leri|lar|ları)]', 'temperature': '{temperature} "*

 * *                      "[{temperature_unit}]', delet […]*

```diff
@@ -1,207 +1,228 @@
 {
     "expansion_rules": {
-        "area": "{area}[n]",
-        "itzali": "(itzali|desaktibatu|ezgaitu)",
-        "name": "{name}[n]",
-        "piztu": "(piztu|aktibatu|gaitu)"
+        "area": "{area}<ismin_halleri>",
+        "cogulluk": "[(ler|leri|lar|lar\u0131)]",
+        "ismin_halleri": "[([(n|\u0131n|in|un|\u00fcn|y|t|d|nd|nt)]\u0131|[(n|\u0131n|in|un|\u00fcn|y|t|d|nd|nt)]i|[(n|\u0131n|in|un|\u00fcn|y|t|d|nd|nt)]\u00fc|[(n|\u0131n|in|un|\u00fcn|y|t|d|nd|nt)]u|[(n|\u0131n|in|un|\u00fcn|y|t|d|nd|nt)]e|[(n|\u0131n|in|un|\u00fcn|y|t|d|nd|nt)]a)][n][ki]",
+        "name": "{name}<cogulluk><ismin_halleri>",
+        "temperature": "{temperature} [{temperature_unit}]"
     },
     "intents": {
         "HassTurnOff": {
             "data": [
                 {
-                    "excludes_context": {
-                        "domain": [
-                            "cover",
-                            "lock",
-                            "scene",
-                            "script"
-                        ]
-                    },
-                    "sentences": [
-                        "<itzali> <name> [argia[k]|etengailua[k]]",
-                        "<name> [argia[k]|etengailua[k]] itzali",
-                        "desaktibatu <name> [argia[k]|etengailua[k]]"
+                    "sentences": [
+                        "<name> (kapa | kapat | s\u00f6nd\u00fcr )"
+                    ]
+                },
+                {
+                    "response": "cover",
+                    "sentences": [
+                        "<name> (kapa | kapat | indir ) "
+                    ]
+                },
+                {
+                    "response": "cover_area",
+                    "sentences": [
+                        "<area> <name> (kapa | kapat | indir )"
                     ]
+                },
+                {
+                    "response": "cover_device_class",
+                    "sentences": [
+                        "garaj kap\u0131s\u0131n\u0131 (kapa | kapat | indir )"
+                    ],
+                    "slots": {
+                        "device_class": "garage",
+                        "domain": "cover"
+                    }
+                },
+                {
+                    "response": "cover_area",
+                    "sentences": [
+                        "<area> (perde|jaluzi|kepeng|panjur)<cogulluk><ismin_halleri> (kapa | kapat | indir | \u00e7ek)"
+                    ],
+                    "slots": {
+                        "device_class": [
+                            "blind",
+                            "curtain",
+                            "shutter"
+                        ],
+                        "domain": "cover"
+                    }
                 }
             ]
         },
         "HassTurnOn": {
             "data": [
                 {
-                    "excludes_context": {
-                        "domain": [
-                            "cover",
-                            "lock",
-                            "scene",
-                            "script"
-                        ]
-                    },
-                    "sentences": [
-                        "<piztu> <name> [argia[k]|etengailua[k]]",
-                        "<name> [argia[k]|etengailua[k]] piztu",
-                        "aktibatu <name> [argia[k]|etengailua[k]]"
+                    "response": "cover_device_class",
+                    "sentences": [
+                        "garaj kap\u0131s\u0131n\u0131 (a\u00e7 | y\u00fckselt)"
+                    ],
+                    "slots": {
+                        "device_class": "garage",
+                        "domain": "cover"
+                    }
+                },
+                {
+                    "response": "cover_area",
+                    "sentences": [
+                        "<area> (perde|jaluzi|kepeng|panjur)<cogulluk><ismin_halleri> (a\u00e7 | y\u00fckselt)"
+                    ],
+                    "slots": {
+                        "device_class": [
+                            "blind",
+                            "curtain",
+                            "shutter"
+                        ],
+                        "domain": "cover"
+                    }
+                },
+                {
+                    "sentences": [
+                        "<name> ( a\u00e7 | yak | \u00e7al\u0131\u015ft\u0131r)"
+                    ]
+                },
+                {
+                    "response": "cover",
+                    "sentences": [
+                        "<name> (a\u00e7 | y\u00fckselt) "
+                    ]
+                },
+                {
+                    "response": "cover_area",
+                    "sentences": [
+                        "<area> <name> (a\u00e7 | y\u00fckselt)"
                     ]
                 }
             ]
         }
     },
-    "language": "eu",
+    "language": "tr",
     "lists": {
         "brightness": {
             "range": {
                 "from": 0,
                 "to": 100,
                 "type": "percentage"
             }
         },
-        "brightness_level": {
-            "values": [
-                {
-                    "in": "(maximoa|altuena|gorena)",
-                    "out": 100
-                },
-                {
-                    "in": "(minimoa|baxuena|txikiena)",
-                    "out": 1
-                }
-            ]
-        },
         "color": {
             "values": [
                 {
-                    "in": "zuria",
+                    "in": "beyaz",
                     "out": "white"
                 },
                 {
-                    "in": "beltza",
+                    "in": "siyah",
                     "out": "black"
                 },
                 {
-                    "in": "gorria",
+                    "in": "k\u0131rm\u0131z\u0131",
                     "out": "red"
                 },
                 {
-                    "in": "laranja",
+                    "in": "turuncu",
                     "out": "orange"
                 },
                 {
-                    "in": "horia",
+                    "in": "sar\u0131",
                     "out": "yellow"
                 },
                 {
-                    "in": "berdea",
+                    "in": "ye\u015fil",
                     "out": "green"
                 },
                 {
-                    "in": "urdina",
+                    "in": "mavi",
                     "out": "blue"
                 },
                 {
-                    "in": "morea",
+                    "in": "mor",
                     "out": "purple"
                 },
                 {
-                    "in": "marroia",
+                    "in": "kahverengi",
                     "out": "brown"
-                }
-            ]
-        },
-        "on_off_domains": {
-            "values": [
+                },
                 {
-                    "in": "argi(a)[k]|lanpara[k]",
-                    "out": "light"
+                    "in": "gri",
+                    "out": "grey"
                 },
                 {
-                    "in": "haizegailu(a)[k]",
-                    "out": "fan"
+                    "in": "pembe",
+                    "out": "pink"
                 },
                 {
-                    "in": "etengailu(a)[k]",
-                    "out": "switch"
-                }
-            ]
-        },
-        "on_off_states": {
-            "values": [
+                    "in": "turkuaz",
+                    "out": "turquoise"
+                },
                 {
-                    "in": "piztu",
-                    "out": "on"
+                    "in": "bordo",
+                    "out": "maroon"
                 },
                 {
-                    "in": "itzali",
-                    "out": "off"
+                    "in": "bej",
+                    "out": "beige"
+                },
+                {
+                    "in": "lacivert",
+                    "out": "navy"
                 }
             ]
         },
         "temperature": {
             "range": {
                 "from": 0,
                 "to": 100,
                 "type": "temperature"
             }
         },
         "temperature_unit": {
             "values": [
                 "celsius",
                 {
-                    "in": "c",
-                    "out": "celsius"
-                },
-                {
-                    "in": "zentigrado",
+                    "in": "c | santigrat",
                     "out": "celsius"
                 },
                 "fahrenheit",
                 {
-                    "in": "f",
+                    "in": "f | fahrenhayt",
                     "out": "fahrenheit"
                 }
             ]
         }
     },
     "responses": {
         "errors": {
-            "handle_error": "Espero ez zen errore bat gertatu da agindua prozesatzean",
-            "no_area": "Ez dago {{ area }} izeneko gunerik",
-            "no_device_class": "Ez dago {{ device_class }} motako elementurik {{ area }} gunean",
-            "no_domain": "{{ area }} guneak ez dauka {{ domain }} moduko elementurik",
-            "no_entity": "Ez da {{ entity }} izeneko gailu edo entitaterik existitzen",
-            "no_intent": "Barkatu, ez dizut ulertu"
+            "handle_error": "\u0130stenilen ama\u00e7 i\u015flenirken bir hata olu\u015ftu.",
+            "no_area": "{{ area }}  ad\u0131nda alan yok.",
+            "no_device_class": "{{ area }}  bir {{ device_class }} i\u00e7ermiyor.",
+            "no_domain": "{{ area }}  bir {{ domain }} i\u00e7ermiyor.",
+            "no_entity": "{{ entity }} ad\u0131nda bir cihaz yok.",
+            "no_intent": "\u00dczg\u00fcn\u00fcm, bunu anlayamad\u0131m."
         },
         "intents": {
-            "HassGetState": {
-                "all": "TODO: {% if not query.unmatched: %}\n  Yes\n{% else %}\n  {% set no_match = query.unmatched | map(attribute=\"name\") | sort | list %}\n  {% if no_match | length > 4 %}\n    No, {{ no_match[:3] | join(\", \") }} and {{ (no_match | length - 3) }} more not\n  {%- else -%}\n    No,\n    {% for name in no_match -%}\n      {% if not loop.first and not loop.last %}, {% elif loop.last and not loop.first %} and {% endif -%}\n      {{ name }}\n    {%- endfor %} not\n  {% endif %}\n{% endif %}\n",
-                "any": "TODO: {% if query.matched %}\n  {% set match = query.matched | map(attribute=\"name\") | sort | list %}\n  {% if match | length > 4 %}\n    Yes, {{ match[:3] | join(\", \") }} and {{ (match | length - 3) }} more\n  {%- else -%}\n    Yes,\n    {% for name in match -%}\n      {% if not loop.first and not loop.last %}, {% elif loop.last and not loop.first %} and {% endif -%}\n      {{ name }}\n    {%- endfor -%}\n  {% endif %}\n{% else %}\n  No\n{% endif %}\n",
-                "how_many": "TODO: {{ query.matched | length }}\n",
-                "one": "TODO: {{ slots.name | capitalize }} is {{ state.state_with_unit }}\n",
-                "one_yesno": "TODO: {% if query.matched %}\n  Yes\n{% else %}\n  No, {{ state.state_with_unit }}\n{% endif %}\n",
-                "which": "TODO: {% if not query.matched %}\n  Not any\n{% else: %}\n  {% set match = query.matched | map(attribute=\"name\") | sort | list %}\n  {% if match | length > 4 %}\n    {{ match[:3] | join(\", \") }} and {{ (match | length - 3) }} more\n  {% else %}\n    {%- for name in match -%}\n      {% if not loop.first and not loop.last %}, {% elif loop.last and not loop.first %} and {% endif -%}\n      {{ name }}\n    {%- endfor -%}\n  {% endif %}\n{% endif %}\n"
-            },
+            "HassGetState": {},
             "HassTurnOff": {
-                "cover": "Itxita",
-                "cover_device_class": "{{ slots.device_class }} itxita",
-                "default": "{{ slots.name }} itzalita",
-                "fan_all": "Haizegailu guztiak itzalita",
-                "fans_area": "Haizegailuak itzalita",
-                "light_all": "Argi guztiak itzalita",
-                "lights_area": "Argiak itzalita",
-                "lock": "Irekita"
+                "cover": "Closed {{ slots.name }}",
+                "cover_area": "Closed {{ slots.area }}",
+                "cover_device_class": "Closed {{ slots.device_class }}",
+                "default": "Turned off {{ slots.name }}",
+                "fans_area": "Turned off fans in {{ slots.area }}",
+                "lights_area": "Turned off lights in {{ slots.area }}"
             },
             "HassTurnOn": {
-                "cover": "Irekita",
-                "cover_device_class": "{{ slots.device_class }} irekita",
-                "default": "{{ slots.name }} piztuta",
-                "fans_area": "Haizegailuak piztuta",
-                "lights_area": "Argiak piztuta",
-                "lock": "Itxita",
-                "scene": "Aktibatuta",
-                "script": "Hasita"
+                "cover": "Opened {{ slots.name }}",
+                "cover_area": "Opened {{ slots.area }}",
+                "cover_device_class": "Opened {{ slots.device_class }}",
+                "default": "Turned on {{ slots.name }}",
+                "fans_area": "Turned on fans in {{ slots.area }}",
+                "lights_area": "Turned on lights in {{ slots.area }}"
             }
         }
     },
     "skip_words": [
-        "mesedez",
-        "eskerrik asko"
+        "L\u00fctfen"
     ]
 }
```

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/fa.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/fa.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/fi.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/fi.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/fr-CA.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/fr-CA.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/fr.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/fr.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/gl.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/gl.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/gu.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/gu.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/he.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/he.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/hi.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/hi.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/hr.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/hr.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/hu.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/hu.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/id.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/id.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/is.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/is.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/it.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/it.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ka.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ka.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/kn.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/kn.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ko.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ro.json`

 * *Files 23% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.6515906555839635%*

 * *Differences: {"'expansion_rules'": "{'name': '({name})', 'area': '[(zona | regiunea | spa(ț|t)iul)] {area}', "*

 * *                      "'brightness': '{brightness}[ ][(% | la sut(ă|a) | [de ]procente)]', "*

 * *                      "'temperature': '{temperature}[ ][[de ]grad[e]][[ ]{temperature_unit}]', "*

 * *                      "'brightness_percent': '{brightness}[ ](% | la sut(ă|a) | [de] procente)', "*

 * *                      "'maximum': '(maxim[(ă|a|um)] [posibil[(ă|a)]])', 'jumatate': '(jum(ă|a)tate "*

 * *                      "| […]*

```diff
@@ -1,2152 +1,1740 @@
 {
     "expansion_rules": {
-        "area": "{area}",
-        "brightness": "{brightness}[ ][%|\ud37c\uc13c\ud2b8|\ud504\ub85c]",
-        "close": "(\ub2eb\uae30|\ub2eb\uc544|\ub2eb\uc544\uc918|\ub0b4\ub9ac\uae30|\ub0b4\ub824|\ub0b4\ub824\uc918|\uccd0|\uccd0\uc918)",
-        "light": "(\uc870\uba85|\uc804\ub4f1|\ub4f1|\ubd88)",
-        "name": "{name}",
-        "numeric_value_set": "(\uc124\uc815|\ubcc0\uacbd|\uc62c\ub824|\uc99d\uac00|\ub0b4\ub824|\uac10\uc18c)",
-        "open": "(\uc5f4\uae30|\uc5f4\uc5b4|\uc5f4\uc5b4\uc918|\uc62c\ub9ac\uae30|\uc62c\ub824|\uc62c\ub824\uc918|\uac77\uae30|\uac77\uc5b4|\uac77\uc5b4\uc918)",
-        "set": "(\uc124\uc815|\ub9de\ucdb0|\ubcc0\uacbd)",
-        "temp": "\uc628\ub3c4",
-        "temperature": "{temperature}[ ][\u00b0|\ub3c4][ ][{temperature_unit}]",
-        "turn": "(\uc804\uc6d0|\uc2a4\uc704\uce58)",
-        "what_is": "(\ubb34\uc5c7\uc778\uac00\uc694|\ubb50\uc57c)"
+        "area": "[(zona | regiunea | spa(\u021b|t)iul)] {area}",
+        "brightness": "{brightness}[ ][(% | la sut(\u0103|a) | [de ]procente)]",
+        "brightness_percent": "{brightness}[ ](% | la sut(\u0103|a) | [de] procente)",
+        "cald": "(cald | fierbinte | (\u00ee|i)ncins)",
+        "cald_frig": "(<cald> | <frig>)",
+        "care": "(care | ce)",
+        "cat": "(<cat_quant> | cum)",
+        "cat_quant": "(c(\u00e2|a)t)",
+        "cate": "(c(\u00e2|a)te | c(\u00e2|a)(\u021b|t)i)",
+        "culoarea": "(culoare[a])",
+        "deschide": "(deschide | ridic(\u0103|a))",
+        "deschis": "(deschis[(\u0103|a)] | ridicat[(\u0103|a)])",
+        "deschise": "(deschise | ridicate)",
+        "descuiat": "descuiat[(\u0103|a)]",
+        "descuiate": "descuia((\u021b|t)i|te)",
+        "detectat": "(detectat[(\u0103|a)] | prezent[(\u0103|a)] | observabil[(\u0103|a)])",
+        "detectate": "(detecta((\u021b|t)i|te) | prezen((\u021b|t)i|te) | observabil(i|e))",
+        "din": "(din | (\u00ee|i)n | pentru | [de] la | [de] pe | de)",
+        "este": "(e | este | sunt)",
+        "fereastra": "(fereastr(\u0103|a) | geam[ul])",
+        "ferestrele": "(ferestre[le] | geamuri[le])",
+        "frig": "(frig | rece | r(\u0103|a)coare)",
+        "in": "((\u00ee|i)n)",
+        "inchide": "((\u00ee|i)nchide | coboar(\u0103|a))",
+        "inchis": "((\u00ee|i)nchis[(\u0103|a)] | coboar(\u00e2|a)t[(\u0103|a)])",
+        "inchise": "((\u00ee|i)nchise | coboar(\u00e2|a)te)",
+        "incuiat": "(\u00ee|i)ncuiat[(\u0103|a)]",
+        "incuiate": "(\u00ee|i)ncuia((\u021b|t)i|te)",
+        "intrerupatoarele": "((\u00ee|i)ntrerup(\u0103|a)toare[le] | comutatoare[le])",
+        "intrerupatorul": "((\u00ee|i)ntrerup(\u0103|a)tor[ul] | comutator[ul])",
+        "jumatate": "(jum(\u0103|a)tate | jumate)",
+        "lumina": "(lumin(\u0103|a) | bec[ul])",
+        "luminile": "(lumini[le] | becuri[le])",
+        "luminozitatea": "(luminozitate[a])",
+        "maximum": "(maxim[(\u0103|a|um)] [posibil[(\u0103|a)]])",
+        "minimum": "(minim[(\u0103|a|um)] [posibil[(\u0103|a)]])",
+        "name": "({name})",
+        "nedetectat": "(nedetectat[(\u0103|a)] | absent[(\u0103|a)] | neobservabil[(\u0103|a)] | liber[(\u0103|a)])",
+        "nedetectate": "(nedetecta((\u021b|t)i|te) | absen((\u021b|t)i|te) | neobservabil(i|e) | liber(i|e))",
+        "opreste": "(stop | opre(\u0219|s)te | (\u00ee|i)nchide | stinge | dezactiveaz(\u0103|a))",
+        "oprit": "(oprit[(\u0103|a)] | (\u00ee|i)nchis[(\u0103|a)] | stins[(\u0103|a)] | dezactivat[(\u0103|a)])",
+        "oprite": "(oprite | (\u00ee|i)nchise | stinse | dezactivate)",
+        "poarta": "poart(\u0103|a)",
+        "porneste": "(start | porne(\u0219|s)te | deschide | aprinde | activeaz(\u0103|a))",
+        "pornit": "(pornit[(\u0103|a)] | deschis[(\u0103|a)]) | aprins[(\u0103|a)] | activat[(\u0103|a)]",
+        "pornite": "(pornite | deschise | aprinse | activate)",
+        "portile": "por(\u021b|t)i[le]",
+        "ruleaza": "(ruleaz(\u0103|a) | start | porne(\u0219|s)te | activeaz(\u0103|a))",
+        "seteaza": "(seteaz(\u0103|a) | pune | a[d]justeaz(\u0103|a) | schimb(\u0103|a) | modific(\u0103|a))",
+        "temperatura": "(temperatur(\u0103|a))",
+        "temperature": "{temperature}[ ][[de ]grad[e]][[ ]{temperature_unit}]",
+        "usa": "u(\u0219|s)(\u0103|a)",
+        "usile": "u(\u0219|s)i[le]",
+        "ventilatoarele": "(ventilatoare[le] | aerisiri[le])",
+        "ventilatorul": "(ventilator[ul] | aerisire[a])",
+        "vreun": "(vre(o|un))"
     },
     "intents": {
         "HassGetState": {
             "data": [
                 {
                     "requires_context": {
                         "device_class": "battery",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_battery_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "battery",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_battery_states:state}\uc778\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "battery",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 \uae30\uae30[\uac00] {bs_battery_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "battery",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 \uae30\uae30[\uac00] {bs_battery_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "battery",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 \uae30\uae30[\uac00] {bs_battery_states:state}\uc774\uc57c"
+                        "[bateria [<din>]] <name> [<din> <area>] e[ste] {bs_battery_states_singular:state}",
+                        "e[ste] {bs_battery_states_singular:state} [bateria [<din>]] <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "battery",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "battery_charging",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> [\ubc30\ud130\ub9ac] {bs_battery_charging_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "battery_charging",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubc30\ud130\ub9ac[\uac00] {bs_battery_charging_states:state}\uc778\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "battery_charging",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 \ubc30\ud130\ub9ac[\uac00] {bs_battery_charging_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "battery_charging",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 \ubc30\ud130\ub9ac[\uac00] {bs_battery_charging_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "battery_charging",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 \ubc30\ud130\ub9ac[\uac00] {bs_battery_charging_states:state}\uc774\uc57c"
+                        "[bateria [<din>]] <name> [<din> <area>] e[ste] {bs_battery_charging_states:state}",
+                        "e[ste] {bs_battery_charging_states:state} [bateria [<din>]] <name> [<din> <area>]",
+                        "{bs_battery_charging_states_passive:state} [bateria [<din>]] <name> [<din> <area>]",
+                        "[bateria [<din>]] <name> [<din> <area>] {bs_battery_charging_states_passive:state}"
                     ],
                     "slots": {
                         "device_class": "battery_charging",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "carbon_monoxide",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_carbon_monoxide_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "carbon_monoxide",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc77c\uc0b0\ud654\ud0c4\uc18c \uc13c\uc11c[\uac00] {bs_carbon_monoxide_states:state}\ub41c\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "carbon_monoxide",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "<area>\uc5d0 \uc77c\uc0b0\ud654\ud0c4\uc18c \uc13c\uc11c[\uac00] \uac10\uc9c0\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "carbon_monoxide",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 \uc77c\uc0b0\ud654\ud0c4\uc18c \uc13c\uc11c[\uac00] {bs_carbon_monoxide_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "carbon_monoxide",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4|\uc5b4\ub514) \uc77c\uc0b0\ud654\ud0c4\uc18c \uc13c\uc11c[\uac00] {bs_carbon_monoxide_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "carbon_monoxide",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 \uc77c\uc0b0\ud654\ud0c4\uc18c \uc13c\uc11c[\uac00] {bs_carbon_monoxide_states:state}\ub410\uc5b4"
+                        "e[ste] {bs_detection_states_singular:state} monoxid[ul] de carbon [(<in> | de [c(\u0103|a)tre])] <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_detection_states_active:state} monoxid[ul] de carbon",
+                        "{bs_detection_states_active:state} <name> [<din> <area>] monoxid[ul] de carbon",
+                        "<name> {bs_detection_states_active:state} monoxid[ul] de carbon [<din> <area>]",
+                        "{bs_detection_states_active:state} <name> monoxid[ul] de carbon [<din> <area>]",
+                        "{bs_detection_states_active:state} monoxid[ul] de carbon <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "carbon_monoxide",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "cold",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_cold_states:state}\uc6cc"
+                        "e[ste] {bs_cold_states:state} [<din>] <name> [<din> <area>]",
+                        "e[ste] {bs_cold_states_singular:state} [<din>] <name> [<din> <area>]",
+                        "<name> [<din> <area>] e[ste] {bs_cold_states_singular:state}",
+                        "sunt {bs_cold_states_plural:state} [<din>] <name> [<din> <area>]",
+                        "<name> [<din> <area>] sunt {bs_cold_states_plural:state}"
                     ],
                     "slots": {
                         "device_class": "cold",
                         "domain": "binary_sensor"
                     }
                 },
                 {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_cold_states:state}\uc6b4\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "cold",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4\uac8c|\ubb34\uc5c7\uc774|\ubb50\uac00) {bs_cold_states:state}\uc6cc"
-                    ],
-                    "slots": {
+                    "requires_context": {
                         "device_class": "cold",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "how_many",
+                        "domain": "binary_sensor"
+                    },
+                    "response": "one_yesno",
                     "sentences": [
-                        "[<area>\uc5d0] {bs_cold_states:state}\uc6b4\uac8c \uc5bc\ub9c8\ub098 \uc788\uc5b4"
+                        "(s-a[u] r(\u0103|a)cit | a[u] (\u00ee|i)nghe(\u021b|t)at) <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "cold",
                         "domain": "binary_sensor",
                         "state": "on"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "connectivity",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_connectivity_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "connectivity",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_connectivity_states:state}\ub41c (\uae30\uae30|\uc7a5\uce58)\uac00 \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "connectivity",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_connectivity_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "connectivity",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_connectivity_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "connectivity",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_connectivity_states:state}\ub410\uc5b4"
+                        "e[ste] {bs_connectivity_states_singular:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] e[ste] {bs_connectivity_states_singular:state}",
+                        "sunt {bs_connectivity_states_plural:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] sunt {bs_connectivity_states_plural:state}"
                     ],
                     "slots": {
                         "device_class": "connectivity",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
-                        "device_class": "door",
+                        "device_class": "connectivity",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_door_states:state}\uc788\uc5b4"
+                        "are conexiune <name> [<din> <area>]",
+                        "<name> [<din> <area>] are conexiune"
                     ],
                     "slots": {
-                        "device_class": "door",
-                        "domain": "binary_sensor"
+                        "device_class": "connectivity",
+                        "domain": "binary_sensor",
+                        "state": "on"
                     }
                 },
                 {
                     "requires_context": {
-                        "device_class": "garage_door",
+                        "device_class": [
+                            "door",
+                            "garage_door",
+                            "opening",
+                            "window"
+                        ],
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_garage_door_states:state}\uc788\uc5b4"
+                        "e[ste] {bs_door_states_singular:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] e[ste] {bs_door_states_singular:state}",
+                        "sunt {bs_door_states_plural:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] sunt {bs_door_states_plural:state}",
+                        "{bs_door_states_passive:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_door_states_passive:state}",
+                        "{bs_door_states_active:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_door_states_active:state}"
                     ],
                     "slots": {
-                        "device_class": "garage_door",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "gas",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_gas_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "gas",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] \uac00\uc2a4 \uc13c\uc11c[\uac00] {bs_gas_states:state}\ub41c\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "gas",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "<area>\uc5d0 \uac00\uc2a4[\uac00] \uac10\uc9c0\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "gas",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 \uac00\uc2a4 \uc13c\uc11c[\uac00] {bs_gas_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "gas",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4|\uc5b4\ub514) \uac00\uc2a4 \uc13c\uc11c[\uac00] {bs_gas_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "gas",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 \uac00\uc2a4 \uc13c\uc11c[\uac00] {bs_gas_states:state}\ub410\uc5b4"
+                        "(e[ste] {bs_detection_states_singular:state} gaz | sunt {bs_detection_states_plural:state} gaze) [(<in> | de [c(\u0103|a)tre])] <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_detection_states_active:state} gaz[e]",
+                        "{bs_detection_states_active:state} <name> [<din> <area>] gaz[e]",
+                        "<name> {bs_detection_states_active:state} gaz[e] [<din> <area>]",
+                        "{bs_detection_states_active:state} gaz[e] <name> [<din> <area>]",
+                        "{bs_detection_states_active:state} <name> gaz[e] [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "gas",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "heat",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_heat_states:state}\uc6cc"
+                        "e[ste] {bs_heat_states:state} [<din>] <name> [<din> <area>]",
+                        "e[ste] {bs_heat_states_singular:state} [<din>] <name> [<din> <area>]",
+                        "<name> [<din> <area>] e[ste] {bs_heat_states_singular:state}",
+                        "sunt {bs_heat_states_plural:state} [<din>] <name> [<din> <area>]",
+                        "<name> [<din> <area>] sunt {bs_heat_states_plural:state}"
                     ],
                     "slots": {
                         "device_class": "heat",
                         "domain": "binary_sensor"
                     }
                 },
                 {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_heat_states:state}\uc6b4\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "heat",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4\uac8c|\ubb34\uc5c7\uc774|\ubb50\uac00) {bs_heat_states:state}\uc6cc"
-                    ],
-                    "slots": {
+                    "requires_context": {
                         "device_class": "heat",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "how_many",
+                        "domain": "binary_sensor"
+                    },
+                    "response": "one_yesno",
                     "sentences": [
-                        "[<area>\uc5d0] {bs_heat_states:state}\uc6b4\uac8c \uc5bc\ub9c8\ub098 \uc788\uc5b4"
+                        "s-a[u] ((\u00ee|i)nc(\u0103|a)lzit | (\u00ee|i)ncins) <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "heat",
                         "domain": "binary_sensor",
                         "state": "on"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "light",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name>[\uc774] {bs_light_states:state}\uc838\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "light",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] \ud45c\uc2dc\ub4f1[\uc774] {bs_light_states:state}\uc838\uc788\ub294\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "light",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 \ud45c\uc2dc\ub4f1[\uc774] {bs_light_states:state}\uc838\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "light",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 \ud45c\uc2dc\ub4f1[\uc774] {bs_light_states:state}\uc838\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "light",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 \ud45c\uc2dc\ub4f1[\uc774] {bs_light_states:state}\uc838\uc788\uc5b4"
+                        "e[ste] {bs_detection_states_singular:state} lumin(\u0103|a) [(<in> | de [c(\u0103|a)tre])] <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_detection_states_active:state} lumin(\u0103|a)",
+                        "{bs_detection_states_active:state} <name> [<din> <area>] lumin(\u0103|a)",
+                        "<name> {bs_detection_states_active:state} lumin(\u0103|a) [<din> <area>]",
+                        "{bs_detection_states_active:state} <name> lumin(\u0103|a) [<din> <area>]",
+                        "{bs_detection_states_active:state} lumin(\u0103|a) <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "light",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "lock",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_lock_states:state}\uc788\uc5b4"
+                        "e[ste] {bs_lock_states_singular:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] e[ste] {bs_lock_states_singular:state}",
+                        "sunt {bs_lock_states_plural:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] sunt {bs_lock_states_plural:state}",
+                        "{bs_lock_states_passive:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_lock_states_passive:state}",
+                        "{bs_lock_states_active:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_lock_states_active:state}"
                     ],
                     "slots": {
-                        "device_class": "lock",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "moisture",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_moisture_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "moisture",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] (\ub204\uc218|\ub204\uc218 \uac10\uc9c0) \uc13c\uc11c[\uac00] {bs_moisture_states:state}\ub41c\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "moisture",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "<area> \ub204\uc218\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "moisture",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\ub204\uc218|\ub204\uc218 \uac10\uc9c0) \uc13c\uc11c[\uac00] {bs_moisture_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "moisture",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4|\uc5b4\ub514) (\ub204\uc218|\ub204\uc218 \uac10\uc9c0) \uc13c\uc11c[\uac00] {bs_moisture_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "moisture",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\ub204\uc218|\ub204\uc218 \uac10\uc9c0) \uc13c\uc11c[\uac00] {bs_moisture_states:state}\ub410\uc5b4"
+                        "e[ste] {bs_moisture_states:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] e[ste] {bs_moisture_states:state}"
                     ],
                     "slots": {
                         "device_class": "moisture",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "motion",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_motion_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "motion",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] (\ubaa8\uc158|\uc6c0\uc9c1\uc784) \uc13c\uc11c[\uac00] {bs_motion_states:state}\ub41c\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "motion",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] (\ubaa8\uc158|\uc6c0\uc9c1\uc784) \uac10\uc9c0\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "motion",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\ubaa8\uc158|\uc6c0\uc9c1\uc784) \uc13c\uc11c[\uac00] {bs_motion_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "motion",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4|\uc5b4\ub514) (\ubaa8\uc158|\uc6c0\uc9c1\uc784) \uc13c\uc11c[\uac00] {bs_motion_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "motion",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\ubaa8\uc158|\uc6c0\uc9c1\uc784) \uc13c\uc11c[\uac00] {bs_motion_states:state}\ub410\uc5b4"
+                        "e[ste] {bs_detection_states_singular:state} mi(\u0219|s)care [(<in> | de [c(\u0103|a)tre])] <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_detection_states_active:state} mi(\u0219|s)care",
+                        "{bs_detection_states_active:state} <name> [<din> <area>] mi(\u0219|s)care",
+                        "<name> {bs_detection_states_active:state} mi(\u0219|s)care [<din> <area>]",
+                        "{bs_detection_states_active:state} <name> mi(\u0219|s)care [<din> <area>]",
+                        "{bs_detection_states_active:state} mi(\u0219|s)care <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "motion",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "occupancy",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_occupancy_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "occupancy",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc874\uc7ac \uac10\uc9c0|\uc7ac\uc2e4) \uc13c\uc11c[\uac00] {bs_occupancy_states:state}\ub41c\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "occupancy",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc874\uc7ac \uac10\uc9c0|\uc7ac\uc2e4) \uac10\uc9c0\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "occupancy",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\uc874\uc7ac \uac10\uc9c0|\uc7ac\uc2e4) \uc13c\uc11c[\uac00] {bs_occupancy_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "occupancy",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4|\uc5b4\ub514) (\uc874\uc7ac \uac10\uc9c0|\uc7ac\uc2e4) \uc13c\uc11c[\uac00] {bs_occupancy_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "occupancy",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\uc874\uc7ac \uac10\uc9c0|\uc7ac\uc2e4) \uc13c\uc11c[\uac00] {bs_occupancy_states:state}\ub410\uc5b4"
+                        "e[ste] {bs_detection_states_singular:state} ocupare [(<in> | de [c(\u0103|a)tre])] <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_detection_states_active:state} ocupare",
+                        "{bs_detection_states_active:state} <name> [<din> <area>] ocupare",
+                        "<name> {bs_detection_states_active:state} ocupare [<din> <area>]",
+                        "{bs_detection_states_active:state} <name> ocupare [<din> <area>]",
+                        "{bs_detection_states_active:state} ocupare <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "occupancy",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
-                        "device_class": "opening",
-                        "domain": "binary_sensor"
-                    },
-                    "response": "one_yesno",
-                    "sentences": [
-                        "[<area>] <name> {bs_opening_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "opening",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubb38\uc774 {bs_opening_states:state}\uc788\ub294\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "opening",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 \ubb38\uc774 {bs_opening_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "opening",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4|\uc5b4\ub514) \ubb38\uc774 {bs_opening_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "opening",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 \ubb38\uc774 {bs_opening_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "opening",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "requires_context": {
                         "device_class": "plug",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_plug_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "plug",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_plug_states:state}\uc788\ub294 (\uae30\uae30|\uc7a5\uce58)\uac00 \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "plug",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_plug_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "plug",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_plug_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "plug",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_plug_states:state}\uc788\uc5b4"
+                        "e[ste] {bs_plug_states_singular:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] e[ste] {bs_plug_states_singular:state}",
+                        "sunt {bs_plug_states_plural:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] sunt {bs_plug_states_plural:state}"
                     ],
                     "slots": {
                         "device_class": "plug",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "power",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_power_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "power",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_power_states:state}\uc788\ub294 (\uae30\uae30|\uc7a5\uce58)\uac00 \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "power",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_power_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "power",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_power_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "power",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_power_states:state}\uc788\uc5b4"
+                        "e[ste] {bs_power_states_singular:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] e[ste] {bs_power_states_singular:state}",
+                        "sunt {bs_power_states_plural:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] sunt {bs_power_states_plural:state}"
                     ],
                     "slots": {
                         "device_class": "power",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "presence",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_presence_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "presence",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_presence_states:state}\uc778 (\uae30\uae30|\uc7a5\uce58)\uac00 \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "presence",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_presence_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "presence",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_presence_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "presence",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_presence_states:state}\uc774\uc57c"
+                        "<name> [<din> <area>] e[ste] {bs_presence_states:state}",
+                        "e[ste] {bs_presence_states:state} <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "presence",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "problem",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name>\uc5d0 \ubb38\uc81c\uac00 \uc788\uc5b4"
+                        "(sunt probleme | (e[ste] | exist(\u0103|a)) [[vre]o] problem(\u0103|a)) [<detectat>] ([<in> leg(\u0103|a)tur(\u0103|a)] cu | la) <name> [<din> <area>]",
+                        "are (probleme | vreo problema) <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "problem",
                         "domain": "binary_sensor",
                         "state": "on"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "running",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_running_states:state}\uc774\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "running",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_running_states:state} (\uae30\uae30|\uc7a5\uce58)\uac00 \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "running",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_running_states:state}\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "running",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_running_states:state}\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "running",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\uae30\uae30|\uc7a5\uce58)\uac00 {bs_running_states:state}\uc57c"
+                        "<name> [<din> <area>] e[ste] {bs_running_states:state}",
+                        "e[ste] {bs_running_states:state} <name> [<din> <area>]",
+                        "{bs_running_states_active:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_running_states_active:state}"
                     ],
                     "slots": {
                         "device_class": "running",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "safety",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_safety_states:state}\ud574"
+                        "<name> [<din> <area>] e[ste] {bs_safety_states:state}",
+                        "e[ste] {bs_safety_states:state} <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "safety",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "smoke",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_smoke_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "smoke",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5f0\uae30 \uac10\uc9c0|\uc5f0\uae30) \uc13c\uc11c[\uac00] {bs_smoke_states:state}\ub41c\uac8c \uc788\uc5b4"
+                        "e[ste] {bs_detection_states_singular:state} fum[ul] [(<in> | de [c(\u0103|a)tre])] <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_detection_states_active:state} fum[ul]",
+                        "{bs_detection_states_active:state} <name> [<din> <area>] fum[ul]",
+                        "<name> {bs_detection_states_active:state} fum[ul] [<din> <area>]",
+                        "{bs_detection_states_active:state} <name> fum[ul] [<din> <area>]",
+                        "{bs_detection_states_active:state} fum[ul] <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "smoke",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "response": "any",
                     "sentences": [
-                        "<area>\uc5d0 \uc5f0\uae30 (\uc788\uc5b4|\uac10\uc9c0\ub410\uc5b4)"
+                        "e[ste] [<detectat>] [vreun pic de] fum[ul] <in> <area>"
                     ],
                     "slots": {
                         "device_class": "smoke",
                         "domain": "binary_sensor",
                         "state": "on"
                     }
                 },
                 {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\uc5f0\uae30 \uac10\uc9c0|\uc5f0\uae30) \uc13c\uc11c[\uac00] {bs_smoke_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "smoke",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 (\uc5f0\uae30 \uac10\uc9c0|\uc5f0\uae30) \uc13c\uc11c[\uac00] {bs_smoke_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "smoke",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\uc5f0\uae30 \uac10\uc9c0|\uc5f0\uae30) \uc13c\uc11c[\uac00] {bs_smoke_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "smoke",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
                     "requires_context": {
                         "device_class": "sound",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_sound_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "sound",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc18c\ub9ac|\uc18c\uc74c|\uc0ac\uc6b4\ub4dc|\uc18c\ub9ac \uac10\uc9c0) \uc13c\uc11c[\uac00] {bs_sound_states:state}\ub41c\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "sound",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "<area>\uc5d0 (\uc18c\ub9ac|\uc18c\uc74c|\uc0ac\uc6b4\ub4dc|\uc18c\ub9ac \uac10\uc9c0) (\ub4e4\ub824|\ub098|\uac10\uc9c0\ub410\uc5b4)"
-                    ],
-                    "slots": {
-                        "device_class": "sound",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "all",
-                    "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 (\uc18c\ub9ac|\uc18c\uc74c|\uc0ac\uc6b4\ub4dc|\uc18c\ub9ac \uac10\uc9c0) \uc13c\uc11c[\uac00] {bs_sound_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "sound",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4|\uc5b4\ub514) (\uc18c\ub9ac|\uc18c\uc74c|\uc0ac\uc6b4\ub4dc|\uc18c\ub9ac \uac10\uc9c0) \uc13c\uc11c[\uac00] {bs_sound_states:state}\ub410\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "sound",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 (\uc18c\ub9ac|\uc18c\uc74c|\uc0ac\uc6b4\ub4dc|\uc18c\ub9ac \uac10\uc9c0) \uc13c\uc11c[\uac00] {bs_sound_states:state}\ub410\uc5b4"
+                        "e[ste] {bs_detection_states_singular:state} (zgomot|sunet)[(ul|e)] [(<in> | de [c(\u0103|a)tre])] <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_detection_states_active:state} (zgomot|sunet)[(ul|e)]",
+                        "{bs_detection_states_active:state} <name> [<din> <area>] (zgomot|sunet)[(ul|e)]",
+                        "<name> {bs_detection_states_active:state} (zgomot|sunet)[(ul|e)] [<din> <area>]",
+                        "{bs_detection_states_active:state} <name> (zgomot|sunet)[(ul|e)] [<din> <area>]",
+                        "{bs_detection_states_active:state} (zgomot|sunet)[(ul|e)] <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "sound",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "tamper",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_tamper_states:state}\ub410\uc5b4"
+                        "<name> [<din> <area>] (e[ste] | a fost) {bs_tamper_states:state}",
+                        "(e[ste] | a fost) {bs_tamper_states:state} <name> [<din> <area>]"
                     ],
                     "slots": {
                         "device_class": "tamper",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "update",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_update_states:state}\uc57c"
-                    ],
-                    "slots": {
-                        "device_class": "update",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_update_states:state}\ud55c \uae30\uae30\uac00 \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "update",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "which",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5b4\ub5a4 \uae30\uae30\uac00 {bs_update_states:state}\ud574"
-                    ],
-                    "slots": {
-                        "device_class": "update",
-                        "domain": "binary_sensor",
-                        "state": "on"
-                    }
-                },
-                {
-                    "response": "how_many",
-                    "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 \uae30\uae30\uac00 {bs_update_states:state}\ud574"
+                        "(e[ste] | exist(\u0103|a)) [<vreun>] update [disponibil] (pentru | la) <name> [<din> <area>]",
+                        "sunt update[[-]uri] [disponibile] (pentru | la) <name> [<din> <area>]",
+                        "<name> [<din> <area>] are ([<vreun>] update [disponibil] | update[-]uri [disponibile])"
                     ],
                     "slots": {
                         "device_class": "update",
                         "domain": "binary_sensor",
                         "state": "on"
                     }
                 },
                 {
                     "requires_context": {
-                        "device_class": "vibration",
+                        "device_class": "update",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_vibration_states:state}\ub410\uc5b4"
+                        "e[ste] (actualizat | la zi) <name> [<din> <area>]",
+                        "<name> [<din> <area>] este (actualizat | la zi)"
                     ],
                     "slots": {
-                        "device_class": "vibration",
-                        "domain": "binary_sensor"
-                    }
-                },
-                {
-                    "requires_context": {
-                        "device_class": "vibration",
-                        "domain": "binary_sensor"
-                    },
-                    "response": "any",
-                    "sentences": [
-                        "[<area>\uc5d0] {bs_vibration_states:state}\ub41c\uac8c \uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "device_class": "vibration",
+                        "device_class": "update",
                         "domain": "binary_sensor",
-                        "state": "on"
+                        "state": "off"
                     }
                 },
                 {
                     "requires_context": {
-                        "device_class": "window",
+                        "device_class": "vibration",
                         "domain": "binary_sensor"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {bs_window_states:state}\uc788\uc5b4"
+                        "sunt {bs_detection_states_plural:state} vibra(\u021b|t)ii [(<in> | de [c(\u0103|a)tre])] <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_detection_states_active:state} vibra(\u021b|t)ii",
+                        "{bs_detection_states_active:state} <name> [<din> <area>] vibra(\u021b|t)ii",
+                        "<name> {bs_detection_states_active:state} vibra(\u021b|t)ii [<din> <area>]",
+                        "{bs_detection_states_active:state} <name> vibra(\u021b|t)ii [<din> <area>]",
+                        "{bs_detection_states_active:state} vibra(\u021b|t)ii <name> [<din> <area>]",
+                        "{bs_vibration_states_active:state} <name> [<din> <area>]",
+                        "<name> [<din> <area>] {bs_vibration_states_active:state}"
                     ],
                     "slots": {
-                        "device_class": "window",
+                        "device_class": "vibration",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "excludes_context": {
                         "domain": [
                             "scene",
                             "script"
                         ]
                     },
                     "response": "one",
                     "sentences": [
-                        "[<area>] <name> [\uc0c1\ud0dc] (<what_is>|\uc5b4\ub54c|\ub9d0\ud574\uc918|\uc54c\ub824\uc918|\uc54c\uc544)",
-                        "[<area>] <name> \uc0c1\ud0dc[\ub294] [<what_is>]"
+                        "<cat> e[ste] <name> [<din> <area>]",
+                        "(ce stare are|(\u00ee|i)n ce stare e[ste]) <name> [<din> <area>]"
                     ]
                 },
                 {
                     "excludes_context": {
                         "domain": [
-                            "cover"
+                            "cover",
+                            "binary_sensor"
                         ]
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> [\uc0c1\ud0dc\uac00] {on_off_states:state}\uc788\uc5b4"
+                        "<name> [<din> <area>] e[ste] {on_off_states_singular:state}",
+                        "e[ste] {on_off_states_singular:state} <name> [<din> <area>]"
                     ]
                 },
                 {
                     "response": "any",
                     "sentences": [
-                        "[<area>\uc5d0] {on_off_domains:domain}(\uac00|\uc774) {on_off_states:state}\uc788\uc5b4",
-                        "[<area>\uc5d0] {on_off_domains:domain}(\uac00|\uc774) {on_off_states:state}\uc788\ub294\uc9c0 (\uc54c\uc544|\uc54c\ub824\uc918|\ub9d0\ud574\uc918)"
+                        "(e[ste] | exist(\u0103|a)) [<vreun>] {on_off_domains_singular:domain} {on_off_states_singular:state} [<in> <area>]",
+                        "(sunt | exist(\u0103|a)) {on_off_domains_plural:domain} {on_off_states_plural:state} [<in> <area>]"
                     ]
                 },
                 {
                     "response": "all",
                     "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 {on_off_domains:domain}(\uac00|\uc774) {on_off_states:state}\uc788\uc5b4"
+                        "sunt toate {on_off_domains_plural:domain} {on_off_states_plural:state} [<in> <area>]",
+                        "sunt {on_off_states_plural:state} toate {on_off_domains_plural:domain} [<in> <area>]",
+                        "toate {on_off_domains_plural:domain} sunt {on_off_states_plural:state} [<in> <area>]"
                     ]
                 },
                 {
                     "response": "which",
                     "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4|\ubb34\uc2a8) {on_off_domains:domain}(\uac00|\uc774) {on_off_states:state}\uc788\ub294\uc9c0 (\uc54c\uc544|\uc54c\ub824\uc918|\ub9d0\ud574\uc918)"
+                        "<care> {on_off_domains_singular:domain} e[ste] {on_off_states_singular:state} [<in> <area>]",
+                        "<care> {on_off_domains_plural:domain} sunt {on_off_states_plural:state} [<in> <area>]"
                     ]
                 },
                 {
                     "response": "how_many",
                     "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 {on_off_domains:domain}(\uac00|\uc774) {on_off_states:state}\uc788\ub294\uc9c0 (\uc54c\uc544|\uc54c\ub824\uc918|\ub9d0\ud574\uc918)"
+                        "<cate> {on_off_domains_plural:domain} sunt {on_off_states_plural:state} [<in> <area>]"
                     ]
                 },
                 {
                     "requires_context": {
                         "domain": "cover"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {cover_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "domain": "cover"
-                    }
+                        "<name> [<din> <area>] e[ste] {cover_states_singular:state}",
+                        "e[ste] {cover_states_singular:state} <name> [<din> <area>]"
+                    ]
                 },
                 {
+                    "requires_context": {
+                        "domain": "cover"
+                    },
                     "response": "any",
                     "sentences": [
-                        "[<area>\uc5d0] {cover_classes:device_class}(\uc774|\uac00) {cover_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "domain": "cover"
-                    }
+                        "(e[ste] | exist(\u0103|a)) [<vreun>] {cover_classes_singular:device_class} {cover_states_singular:state} [<in> <area>]",
+                        "(sunt | exist(\u0103|a)) {cover_classes_plural:device_class} {cover_states_plural:state} [<in> <area>]"
+                    ]
                 },
                 {
+                    "requires_context": {
+                        "domain": "cover"
+                    },
                     "response": "all",
                     "sentences": [
-                        "[<area>\uc5d0] \ubaa8\ub4e0 {cover_classes:device_class}(\uc774|\uac00) {cover_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "domain": "cover"
-                    }
+                        "sunt toate {cover_classes_plural:device_class} {cover_states_plural:state} [<in> <area>]",
+                        "toate {cover_classes_plural:device_class} sunt {cover_states_plural:state} [<in> <area>]"
+                    ]
                 },
                 {
+                    "requires_context": {
+                        "domain": "cover"
+                    },
                     "response": "which",
                     "sentences": [
-                        "[<area>\uc5d0] (\uc5b4\ub5a4|\uc5b4\ub514) {cover_classes:device_class}(\uc774|\uac00) {cover_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
+                        "<care> {cover_classes_singular:device_class} e[ste] {cover_states_singular:state} [<in> <area>]",
+                        "<care> {cover_classes_plural:device_class} sunt {cover_states_plural:state} [<in> <area>]"
+                    ]
+                },
+                {
+                    "requires_context": {
                         "domain": "cover"
-                    }
+                    },
+                    "response": "how_many",
+                    "sentences": [
+                        "<cate> {cover_classes_plural:device_class} sunt {cover_states_plural:state} [<in> <area>]"
+                    ]
+                },
+                {
+                    "requires_context": {
+                        "domain": "light"
+                    },
+                    "response": "one_yesno",
+                    "sentences": [
+                        "<name> [<din> <area>] e[ste] {on_off_states_singular:state}",
+                        "e[ste] {on_off_states_singular:state} <name> [<din> <area>]"
+                    ]
                 },
                 {
+                    "requires_context": {
+                        "domain": "light"
+                    },
+                    "response": "any",
+                    "sentences": [
+                        "(e[ste] | exist(\u0103|a)) [<vreun>] <lumina> {on_off_states_singular:state} [<in> <area>]",
+                        "(sunt | exist(\u0103|a)) <luminile> {on_off_states_plural:state} [<in> <area>]"
+                    ]
+                },
+                {
+                    "requires_context": {
+                        "domain": "light"
+                    },
+                    "response": "all",
+                    "sentences": [
+                        "sunt toate <luminile> {on_off_states_plural:state} [<in> <area>]",
+                        "toate <luminile> sunt {on_off_states_plural:state} [<in> <area>]"
+                    ]
+                },
+                {
+                    "requires_context": {
+                        "domain": "light"
+                    },
+                    "response": "which",
+                    "sentences": [
+                        "<care> <lumina> e[ste] {on_off_states_singular:state} [<in> <area>]",
+                        "<care> <luminile> sunt {on_off_states_plural:state} [<in> <area>]"
+                    ]
+                },
+                {
+                    "requires_context": {
+                        "domain": "light"
+                    },
                     "response": "how_many",
                     "sentences": [
-                        "[<area>\uc5d0] \uc5bc\ub9c8\ub098 \ub9ce\uc740 {cover_classes:device_class}(\uc774|\uac00) {cover_states:state}\uc788\uc5b4"
-                    ],
-                    "slots": {
-                        "domain": "cover"
-                    }
+                        "<cate> <luminile> sunt {on_off_states_plural:state} [<in> <area>]"
+                    ]
                 },
                 {
                     "requires_context": {
                         "domain": "lock"
                     },
                     "response": "one_yesno",
                     "sentences": [
-                        "[<area>] <name> {lock_states:state}\uc788\uc5b4"
+                        "<name> [<din> <area>] e[ste] {lock_states_singular:state}",
+                        "e[ste] {lock_states_singular:state} <name> [<din> <area>]"
                     ],
                     "slots": {
                         "domain": "lock"
                     }
                 },
                 {
                     "response": "any",
                     "sentences": [
-                        "[<area>] {lock_states:state}\uc788\ub294 \ubb38\uc774 \uc788\uc5b4"
+                        "(e[ste] | exist(\u0103|a)) [<vreun>] <usa> {lock_states_singular:state} [<in> <area>]",
+                        "(sunt | exist(\u0103|a)) <usile> {lock_states_plural:state} [<in> <area>]"
                     ],
                     "slots": {
                         "domain": "lock"
                     }
                 },
                 {
                     "response": "all",
                     "sentences": [
-                        "[<area>] \ubaa8\ub4e0 \ubb38 {lock_states:state}\uc788\uc5b4"
+                        "sunt toate <usile> {lock_states_plural:state} [<in> <area>]",
+                        "toate <usile> sunt {lock_states_plural:state} [<in> <area>]"
                     ],
                     "slots": {
                         "domain": "lock"
                     }
                 },
                 {
                     "response": "which",
                     "sentences": [
-                        "(\uc5b4\ub5a4|\uc5b4\ub514) [<area>] \ubb38\uc774 {lock_states:state}\uc788\uc5b4"
+                        "<care> <usa> e[ste] {lock_states_singular:state} [<in> <area>]",
+                        "<care> <usile> sunt {lock_states_plural:state} [<in> <area>]"
                     ],
                     "slots": {
                         "domain": "lock"
                     }
                 },
                 {
                     "response": "how_many",
                     "sentences": [
-                        "(\uc5bc\ub9c8\ub098 \ub9ce\uc740) [<area>] \ubb38\uc774 {lock_states:state}\uc788\uc5b4"
+                        "<cate> <usile> sunt {lock_states_plural:state} [<in> <area>]"
                     ],
                     "slots": {
                         "domain": "lock"
                     }
                 }
             ]
         },
         "HassTurnOff": {
             "data": [
                 {
                     "response": "fans_area",
                     "sentences": [
-                        "<area>\uc5d0 [\ubaa8\ub4e0] \ud32c <turn> \uaebc",
-                        "<area> \ud32c <turn> \uaebc",
-                        "[\ubaa8\ub4e0] <area> \ud32c [<turn>] \uaebc",
-                        "<area>\uc5d0 [\ubaa8\ub4e0] \ud32c [<turn>] \uaebc",
-                        "<area>\uc5d0 [\ubaa8\ub4e0] \ud32c \uc885\ub8cc",
-                        "[\ubaa8\ub4e0] <area> \ud32c \uc885\ub8cc",
-                        "<area> [\ubaa8\ub4e0] \ud32c \uaebc"
+                        "<opreste> (<ventilatorul> | [toate] <ventilatoarele>) [<din>] <area>",
+                        "<opreste> [<din>] <area> (<ventilatorul> | [toate] <ventilatoarele>)"
                     ],
                     "slots": {
-                        "domain": "fan",
-                        "name": "all"
+                        "domain": "fan"
+                    }
+                },
+                {
+                    "requires_context": {
+                        "area": null
+                    },
+                    "response": "fans_area",
+                    "sentences": [
+                        "<opreste> (<ventilatorul> | [toate] <ventilatoarele>)"
+                    ],
+                    "slots": {
+                        "domain": "fan"
                     }
                 },
                 {
                     "excludes_context": {
                         "domain": [
-                            "binary_sensor",
                             "light",
-                            "lock",
+                            "cover",
                             "scene",
                             "script",
-                            "sensor",
-                            "fan"
+                            "sensor"
                         ]
                     },
                     "sentences": [
-                        "<name> (\ub2eb\uc544|\ub2eb\uc544\uc918)"
+                        "<opreste> <name>"
                     ]
                 },
                 {
-                    "response": "lights_area",
+                    "requires_context": {
+                        "domain": "light"
+                    },
+                    "response": "light",
                     "sentences": [
-                        "<area>[\uc5d0|\uc758] [\ubaa8\ub4e0] <light> <turn> \uaebc",
-                        "<area> [\ubaa8\ub4e0] <light> <turn> \uaebc",
-                        "[\ubaa8\ub4e0] <area> <light> [<turn>] \uaebc",
-                        "<area>\uc5d0 \uc788\ub294 [\ubaa8\ub4e0] <light> [<turn>] \uaebc",
-                        "<area>\uc5d0 \uc788\ub294 [\ubaa8\ub4e0] <light> \uc885\ub8cc",
-                        "[\ubaa8\ub4e0] <area> <light> \uc885\ub8cc"
+                        "<opreste> <name>"
                     ],
                     "slots": {
                         "domain": "light"
                     }
                 },
                 {
-                    "requires_context": {
-                        "domain": "cover"
-                    },
-                    "sentences": [
-                        "[<area>] <name> <close>"
-                    ]
-                },
-                {
+                    "response": "lights_area",
                     "sentences": [
-                        "\ucc28\uace0\ubb38 <close>"
+                        "<opreste> (<lumina> | [toate] <luminile>) [<din>] <area>",
+                        "<opreste> [<din>] <area> (<lumina> | [toate] <luminile>)"
                     ],
                     "slots": {
-                        "device_class": "garage",
-                        "domain": "cover"
+                        "domain": "light"
                     }
                 },
                 {
-                    "response": "cover_device_class",
+                    "requires_context": {
+                        "area": null
+                    },
+                    "response": "lights_area",
                     "sentences": [
-                        "<area>\uc5d0 {cover_classes:device_class} <close>",
-                        "<area> {cover_classes:device_class} <close>"
+                        "<opreste> (<lumina> | [toate] <luminile>)"
                     ],
                     "slots": {
-                        "domain": "cover"
+                        "domain": "light"
                     }
                 },
                 {
                     "requires_context": {
-                        "domain": "lock"
+                        "domain": "cover"
                     },
-                    "response": "lock",
+                    "response": "cover",
                     "sentences": [
-                        "[<area>] <name> \uc7a0\uae08 \ud574\uc81c"
+                        "<inchide> <name> [[<din>] <area>]"
                     ]
                 },
                 {
-                    "response": "lock",
+                    "response": "covers_area",
                     "sentences": [
-                        "<area>[\uc758] [\ubaa8\ub4e0] [\uc7a0\uae08\uc7a5\uce58|\uc790\ubb3c\uc1e0|\ubb38] \uc7a0\uae08 \ud574\uc81c",
-                        "[\ubaa8\ub4e0] <area> [\uc7a0\uae08\uc7a5\uce58|\uc790\ubb3c\uc1e0|\ubb38] \uc7a0\uae08 \ud574\uc81c"
+                        "<inchide> ({cover_classes_singular:device_class} | [toate] {cover_classes_plural:device_class}) [<din>] <area>"
                     ],
                     "slots": {
-                        "domain": "lock",
-                        "name": "all"
+                        "domain": "cover"
                     }
                 }
             ]
         },
         "HassTurnOn": {
             "data": [
                 {
                     "requires_context": {
                         "domain": "scene"
                     },
                     "response": "scene",
                     "sentences": [
-                        "<name> [\uc7a5\uba74|\ubaa8\ub4dc] [\ud65c\uc131\ud654|<turn>] [\ucf1c|\uc791\ub3d9]"
+                        "<porneste> [scena] <name>"
                     ],
                     "slots": {
                         "domain": "scene"
                     }
                 },
                 {
-                    "response": "lights_area",
+                    "requires_context": {
+                        "domain": "light"
+                    },
+                    "response": "light",
                     "sentences": [
-                        "<area>[\uc5d0|\uc758] [\ubaa8\ub4e0] <light> <turn> \ucf1c",
-                        "<area> [\ubaa8\ub4e0] <light> <turn> \ucf1c",
-                        "[\ubaa8\ub4e0] <area> <light> [<turn>] \ucf1c",
-                        "<area>\uc5d0 \uc788\ub294 [\ubaa8\ub4e0] <light> [<turn>] \ucf1c",
-                        "<area>\uc5d0 \uc788\ub294 [\ubaa8\ub4e0] <light> \uc791\ub3d9",
-                        "[\ubaa8\ub4e0] <area> <light> \uc791\ub3d9"
+                        "<porneste> <name>"
                     ],
                     "slots": {
                         "domain": "light"
                     }
                 },
                 {
-                    "requires_context": {
-                        "domain": "cover"
-                    },
+                    "response": "lights_area",
                     "sentences": [
-                        "[<area>] <name> <open>"
-                    ]
+                        "<porneste> (<lumina> | [toate] <luminile>) [<din>] <area>",
+                        "<porneste> [<din>] <area> (<lumina> | [toate] <luminile>)"
+                    ],
+                    "slots": {
+                        "domain": "light"
+                    }
                 },
                 {
+                    "requires_context": {
+                        "area": null
+                    },
+                    "response": "lights_area",
                     "sentences": [
-                        "\ucc28\uace0\ubb38 <open>"
+                        "<porneste> (<lumina> | [toate] <luminile>)"
                     ],
                     "slots": {
-                        "device_class": "garage",
-                        "domain": "cover"
+                        "domain": "light"
                     }
                 },
                 {
-                    "response": "cover_device_class",
+                    "requires_context": {
+                        "domain": "cover"
+                    },
+                    "response": "cover",
+                    "sentences": [
+                        "<deschide> <name> [[<din>] <area>]"
+                    ]
+                },
+                {
+                    "response": "covers_area",
                     "sentences": [
-                        "<area>\uc5d0 {cover_classes:device_class} <open>",
-                        "<area> {cover_classes:device_class} <open>"
+                        "<deschide> ({cover_classes_singular:device_class} | [toate] {cover_classes_plural:device_class}) [<din>] <area>"
                     ],
                     "slots": {
                         "domain": "cover"
                     }
                 },
                 {
                     "response": "fans_area",
                     "sentences": [
-                        "<area>\uc5d0 [\ubaa8\ub4e0] \ud32c <turn> \ucf1c",
-                        "<area> \ud32c <turn> \ucf1c",
-                        "[\ubaa8\ub4e0] <area> \ud32c [<turn>] \ucf1c",
-                        "<area>\uc5d0 [\ubaa8\ub4e0] \ud32c [<turn>] \ucf1c",
-                        "<area>\uc5d0 [\ubaa8\ub4e0] \ud32c \uc791\ub3d9",
-                        "[\ubaa8\ub4e0] <area> \ud32c \uc791\ub3d9",
-                        "<area> [\ubaa8\ub4e0] \ud32c \ucf1c"
+                        "<porneste> (<ventilatorul> | [toate] <ventilatoarele>) <din> <area>",
+                        "<porneste> <din> <area> (<ventilatorul> | [toate] <ventilatoarele>)"
                     ],
                     "slots": {
-                        "domain": "fan",
-                        "name": "all"
+                        "domain": "fan"
                     }
                 },
                 {
                     "requires_context": {
-                        "domain": "lock"
+                        "area": null
                     },
-                    "response": "lock",
-                    "sentences": [
-                        "[<area>] <name> \uc7a0\uac00"
-                    ]
-                },
-                {
-                    "response": "lock",
+                    "response": "fans_area",
                     "sentences": [
-                        "<area>[\uc758] [\ubaa8\ub4e0] [\uc7a0\uae08\uc7a5\uce58|\uc790\ubb3c\uc1e0|\ubb38] \uc7a0\uac00",
-                        "[\ubaa8\ub4e0] <area> [\uc7a0\uae08\uc7a5\uce58|\uc790\ubb3c\uc1e0|\ubb38] \uc7a0\uac00"
+                        "<porneste> (<ventilatorul> | [toate] <ventilatoarele>)"
                     ],
                     "slots": {
-                        "domain": "lock",
-                        "name": "all"
+                        "domain": "fan"
                     }
                 },
                 {
                     "requires_context": {
                         "domain": "script"
                     },
                     "response": "script",
                     "sentences": [
-                        "<name> [\uc2a4\ud06c\ub9bd\ud2b8] [\uc2e4\ud589|\uc2dc\uc791|<turn>] [\ucf1c|\uc791\ub3d9]"
+                        "<ruleaza> [script[ul]] <name>"
                     ],
                     "slots": {
                         "domain": "script"
                     }
                 },
                 {
                     "excludes_context": {
                         "domain": [
-                            "binary_sensor",
                             "light",
-                            "lock",
+                            "cover",
                             "scene",
                             "script",
-                            "sensor",
-                            "fan"
+                            "sensor"
                         ]
                     },
                     "sentences": [
-                        "<name> (\uc5f4\uc5b4|\uc5f4\uc5b4\uc918)"
+                        "<porneste> <name>"
                     ]
                 }
             ]
         }
     },
-    "language": "ko",
+    "language": "ro",
     "lists": {
         "brightness": {
             "range": {
                 "from": 0,
                 "to": 100,
                 "type": "percentage"
             }
         },
-        "brightness_level": {
+        "brightness_min_max": {
             "values": [
                 {
-                    "in": "(\ucd5c\ub300|\uac00\uc7a5 \ubc1d\uac8c|\ucd5c\ub300\uce58|\uc81c\uc77c \ubc1d\uac8c)",
+                    "in": "<maximum>",
                     "out": 100
                 },
                 {
-                    "in": "(\ucd5c\uc18c|\uac00\uc7a5 \uc5b4\ub461\uac8c|\ucd5c\uc18c\uce58|\uc81c\uc77c \uc5b4\ub461\uac8c)",
+                    "in": "<jumatate>",
+                    "out": 50
+                },
+                {
+                    "in": "<minimum>",
                     "out": 1
                 }
             ]
         },
         "bs_battery_charging_states": {
             "values": [
                 {
-                    "in": "\ucda9\uc804 \uc911",
+                    "in": "(\u00ee|i)n curs de (\u00ee|i)nc(\u0103|a)rcare",
                     "out": "on"
                 },
                 {
-                    "in": "\ucda9\uc804 \uc911 \uc544\ub2d8",
+                    "in": "la (\u00ee|i)nc(\u0103|a)rca(re|t)",
+                    "out": "on"
+                },
+                {
+                    "in": "(\u00ee|i)n curs de desc(\u0103|a)rcare",
                     "out": "off"
                 }
             ]
         },
-        "bs_battery_states": {
+        "bs_battery_charging_states_passive": {
             "values": [
                 {
-                    "in": "(\ubc30\ud130\ub9ac \ubd80\uc871)",
+                    "in": "se (\u00ee|i)ncarc(\u0103|a)",
+                    "out": "on"
+                },
+                {
+                    "in": "e[ste] la (\u00ee|i)nc(\u0103|a)rcat",
                     "out": "on"
                 },
                 {
-                    "in": "(\ubc30\ud130\ub9ac \ubcf4\ud1b5)",
+                    "in": "se descarc(\u0103|a)",
                     "out": "off"
                 }
             ]
         },
-        "bs_carbon_monoxide_states": {
+        "bs_battery_states_singular": {
             "values": [
                 {
-                    "in": "(\uac10\uc9c0\ub428|\uac10\uc9c0|\ucf1c\uc9d0)",
+                    "in": "descarcat(\u0103|a)",
                     "out": "on"
                 },
                 {
-                    "in": "(\uac10\uc9c0 \ud574\uc81c\ub428|\uc5c6\uc74c|\uac10\uc9c0\ud574\uc81c)",
+                    "in": "(normal(\u0103|a) | (\u00ee|i)nc(\u0103|a)rcat(\u0103|a))",
                     "out": "off"
                 }
             ]
         },
         "bs_cold_states": {
             "values": [
                 {
-                    "in": "(\ucc28\uac00\uc6c0|\ucc28\uac00)",
+                    "in": "<frig>",
                     "out": "on"
                 },
                 {
-                    "in": "(\ubcf4\ud1b5|\uc815\uc0c1)",
+                    "in": "normal",
                     "out": "off"
                 }
             ]
         },
-        "bs_connectivity_states": {
+        "bs_cold_states_plural": {
             "values": [
                 {
-                    "in": "(\uc5f0\uacb0\ub428|\uc5f0\uacb0)",
+                    "in": "(reci | (\u00ee|i)nghe(\u021b|t)a((\u021b|t)i|te))",
                     "out": "on"
                 },
                 {
-                    "in": "(\uc5f0\uacb0 \ud574\uc81c\ub428|\uc5f0\uacb0\ud574\uc81c|\uc5f0\uacb0\ub418\uc9c0 \uc54a\uc74c)",
+                    "in": "normal(i|e)",
                     "out": "off"
                 }
             ]
         },
-        "bs_door_states": {
+        "bs_cold_states_singular": {
             "values": [
                 {
-                    "in": "(\uc5f4\ub9bc|\uc5f4\ub824)",
+                    "in": "(rece | (\u00ee|i)nghe(\u021b|t)at[(\u0103|a)])",
                     "out": "on"
                 },
                 {
-                    "in": "(\ub2eb\ud798|\ub2eb\ud600)",
+                    "in": "normal[(\u0103|a)]",
                     "out": "off"
                 }
             ]
         },
-        "bs_garage_door_states": {
+        "bs_connectivity_states_plural": {
             "values": [
                 {
-                    "in": "(\uc5f4\ub9bc|\uc5f4\ub824)",
+                    "in": "conecta((\u021b|t)i|te)",
                     "out": "on"
                 },
                 {
-                    "in": "(\ub2eb\ud798|\ub2eb\ud600)",
+                    "in": "deconecta((\u021b|t)i|te)",
                     "out": "off"
                 }
             ]
         },
-        "bs_gas_states": {
+        "bs_connectivity_states_singular": {
             "values": [
                 {
-                    "in": "(\uac10\uc9c0\ub428|\uac10\uc9c0|\ucf1c\uc9d0)",
+                    "in": "conectat[(\u0103|a)]",
                     "out": "on"
                 },
                 {
-                    "in": "(\uac10\uc9c0 \ud574\uc81c\ub428|\uc5c6\uc74c|\uac10\uc9c0\ud574\uc81c)",
+                    "in": "deconectat[(\u0103|a)]",
                     "out": "off"
                 }
             ]
         },
-        "bs_heat_states": {
+        "bs_detection_states_active": {
             "values": [
                 {
-                    "in": "(\ub728\uac70\uc6c0|\ub728\uac70)",
+                    "in": "(detecteaz(\u0103|a) | simte)",
+                    "out": "on"
+                },
+                {
+                    "in": "a (detectat | sim(\u021b|t)it)",
                     "out": "on"
                 },
                 {
-                    "in": "(\ubcf4\ud1b5|\uc815\uc0c1)",
+                    "in": "nu (detecteaz(\u0103|a) | simte)",
+                    "out": "off"
+                },
+                {
+                    "in": "nu a (detectat | sim(\u021b|t)it)",
                     "out": "off"
                 }
             ]
         },
-        "bs_light_states": {
+        "bs_detection_states_plural": {
             "values": [
                 {
-                    "in": "(\ucf1c\uc9d0|\ucf1c)",
+                    "in": "<detectate>",
                     "out": "on"
                 },
                 {
-                    "in": "(\uaebc\uc9d0|\uaebc)",
+                    "in": "<nedetectate>",
                     "out": "off"
                 }
             ]
         },
-        "bs_lock_states": {
+        "bs_detection_states_singular": {
             "values": [
                 {
-                    "in": "(\uc7a0\uae08 \ud574\uc81c|\uc7a0\uae08 \ud574\uc81c\ub418\uc5b4)",
+                    "in": "<detectat>",
                     "out": "on"
                 },
                 {
-                    "in": "(\uc7a0\uae08|\uc7a0\uae40|\uc7a0\uae08 \uc124\uc815|\uc7a0\uae08 \uc124\uc815\ub418\uc5b4|\uc7a0\uaca8)",
+                    "in": "<nedetectat>",
                     "out": "off"
                 }
             ]
         },
-        "bs_moisture_states": {
+        "bs_door_states_active": {
             "values": [
                 {
-                    "in": "(\uc2b5\ud568|\ucd95\ucd95|\uc2b5|\ub204\uc218|\uac10\uc9c0\ub428|\uac10\uc9c0|\ucf1c\uc9d0)",
+                    "in": "am deschis",
+                    "out": "on"
+                },
+                {
+                    "in": "a deschis cineva",
                     "out": "on"
                 },
                 {
-                    "in": "(\uac74\uc870|\uac10\uc9c0 \ud574\uc81c\ub428|\uc5c6\uc74c|\uac10\uc9c0\ud574\uc81c)",
+                    "in": "am (\u00ee|i)nchis",
+                    "out": "off"
+                },
+                {
+                    "in": "a (\u00ee|i)nchis cineva",
                     "out": "off"
                 }
             ]
         },
-        "bs_motion_states": {
+        "bs_door_states_passive": {
             "values": [
                 {
-                    "in": "(\uac10\uc9c0\ub428|\uac10\uc9c0|\ucf1c\uc9d0)",
+                    "in": "s-a[u] deschis",
                     "out": "on"
                 },
                 {
-                    "in": "(\uac10\uc9c0 \ud574\uc81c\ub428|\uc5c6\uc74c|\uac10\uc9c0\ud574\uc81c)",
+                    "in": "s-a[u] (\u00ee|i)nchis",
                     "out": "off"
                 }
             ]
         },
-        "bs_occupancy_states": {
+        "bs_door_states_plural": {
             "values": [
                 {
-                    "in": "(\uac10\uc9c0\ub428|\uac10\uc9c0|\ucf1c\uc9d0)",
+                    "in": "<deschise>",
                     "out": "on"
                 },
                 {
-                    "in": "(\uac10\uc9c0 \ud574\uc81c\ub428|\uc5c6\uc74c|\uac10\uc9c0\ud574\uc81c)",
+                    "in": "<inchise>",
                     "out": "off"
                 }
             ]
         },
-        "bs_opening_states": {
+        "bs_door_states_singular": {
             "values": [
                 {
-                    "in": "(\uc5f4\ub9bc|\uc5f4\ub824)",
+                    "in": "<deschis>",
                     "out": "on"
                 },
                 {
-                    "in": "(\ub2eb\ud798|\ub2eb\ud600)",
+                    "in": "<inchis>",
                     "out": "off"
                 }
             ]
         },
-        "bs_plug_states": {
+        "bs_heat_states": {
             "values": [
                 {
-                    "in": "(\ud50c\ub7ec\uadf8 \uaf3d\ud798|\ud50c\ub7ec\uadf8 \uaf3d\ud600|\ud50c\ub7ec\uadf8 \uc5f0\uacb0)",
+                    "in": "<cald>",
                     "out": "on"
                 },
                 {
-                    "in": "(\ud50c\ub7ec\uadf8 \ubf51\ud798|\ud50c\ub7ec\uadf8 \ubf51\ud600|\ud50c\ub7ec\uadf8 \uc5f0\uacb0\ud574\uc81c)",
+                    "in": "normal",
                     "out": "off"
                 }
             ]
         },
-        "bs_power_states": {
+        "bs_heat_states_plural": {
             "values": [
                 {
-                    "in": "(\ucf1c\uc9d0|\ucf1c\uc838)",
+                    "in": "(cal(zi|de) | fierbin(\u021b|t)i | (\u00ee|i)ncin((\u0219|s)i|se))",
                     "out": "on"
                 },
                 {
-                    "in": "(\uaebc\uc9d0|\uaebc\uc838)",
+                    "in": "normal(i|e)",
                     "out": "off"
                 }
             ]
         },
-        "bs_presence_states": {
+        "bs_heat_states_singular": {
             "values": [
                 {
-                    "in": "\uc7ac\uc2e4",
+                    "in": "(cald[(\u0103|a)] | fierbinte | (\u00ee|i)ncins)",
                     "out": "on"
                 },
                 {
-                    "in": "\uc678\ucd9c",
+                    "in": "normal[(\u0103|a)]",
                     "out": "off"
                 }
             ]
         },
-        "bs_problem_states": {
+        "bs_lock_states_active": {
             "values": [
                 {
-                    "in": "\ube44\uc815\uc0c1",
+                    "in": "am descuiat",
+                    "out": "on"
+                },
+                {
+                    "in": "a descuiat cineva",
                     "out": "on"
                 },
                 {
-                    "in": "\uc815\uc0c1",
+                    "in": "am (\u00ee|i)ncuiat",
+                    "out": "off"
+                },
+                {
+                    "in": "a (\u00ee|i)ncuiat cineva",
                     "out": "off"
                 }
             ]
         },
-        "bs_running_states": {
+        "bs_lock_states_passive": {
             "values": [
                 {
-                    "in": "(\uc791\ub3d9 \uc911|\uc791\ub3d9 \uc911\uc774|\uc791\ub3d9 \uc911\uc778)",
+                    "in": "s-a[u] descuiat",
                     "out": "on"
                 },
                 {
-                    "in": "(\uc791\ub3d9 \uc911 \uc544\ub2d8|\uc791\ub3d9 \uc911 \uc544\ub2c8|\uc791\ub3d9 \uc911 \uc544\ub2cc)",
+                    "in": "s-a[u] (\u00ee|i)ncuiat",
                     "out": "off"
                 }
             ]
         },
-        "bs_safety_states": {
+        "bs_lock_states_plural": {
             "values": [
                 {
-                    "in": "\uc704\ud5d8",
+                    "in": "<descuiate>",
                     "out": "on"
                 },
                 {
-                    "in": "\uc548\uc804",
+                    "in": "<incuiate>",
                     "out": "off"
                 }
             ]
         },
-        "bs_smoke_states": {
+        "bs_lock_states_singular": {
             "values": [
                 {
-                    "in": "(\uac10\uc9c0\ub428|\uac10\uc9c0|\ucf1c\uc9d0)",
+                    "in": "<descuiat>",
                     "out": "on"
                 },
                 {
-                    "in": "(\uac10\uc9c0 \ud574\uc81c\ub428|\uc5c6\uc74c|\uac10\uc9c0\ud574\uc81c)",
+                    "in": "<incuiat>",
                     "out": "off"
                 }
             ]
         },
-        "bs_sound_states": {
+        "bs_moisture_states": {
             "values": [
                 {
-                    "in": "(\uac10\uc9c0\ub428|\uac10\uc9c0|\ucf1c\uc9d0)",
+                    "in": "u[me]d[(\u0103|a)]",
                     "out": "on"
                 },
                 {
-                    "in": "(\uac10\uc9c0 \ud574\uc81c\ub428|\uc5c6\uc74c|\uac10\uc9c0\ud574\uc81c)",
+                    "in": "uscat[(\u0103|a)]",
                     "out": "off"
                 }
             ]
         },
-        "bs_tamper_states": {
+        "bs_plug_states_plural": {
             "values": [
                 {
-                    "in": "(\uac10\uc9c0\ub428|\uac10\uc9c0|\ucf1c\uc9d0|\ud0ec\ud37c \uac10\uc9c0)",
+                    "in": "conecta((\u021b|t)i|te)",
                     "out": "on"
                 },
                 {
-                    "in": "(\uac10\uc9c0 \ud574\uc81c\ub428|\uc5c6\uc74c|\ud0ec\ud37c \uac10\uc9c0\ud574\uc81c)",
+                    "in": "deconecta((\u021b|t)i|te)",
                     "out": "off"
                 }
             ]
         },
-        "bs_update_states": {
+        "bs_plug_states_singular": {
             "values": [
                 {
-                    "in": "(\uc5c5\ub370\uc774\ud2b8 \uac00\ub2a5|\uc5c5\ub370\uc774\ud2b8 \uc788)",
+                    "in": "conectat[(\u0103|a)]",
                     "out": "on"
                 },
                 {
-                    "in": "(\ucd5c\uc2e0 \uc5c5\ub370\uc774\ud2b8|\uc5c5\ub370\uc774\ud2b8 \uc5c6)",
+                    "in": "deconectat[(\u0103|a)]",
                     "out": "off"
                 }
             ]
         },
-        "bs_vibration_states": {
+        "bs_power_states_plural": {
             "values": [
                 {
-                    "in": "(\uac10\uc9c0\ub428|\uac10\uc9c0|\ucf1c\uc9d0|\uc9c4\ub3d9 \uac10\uc9c0)",
+                    "in": "(alimenta((\u021b|t)i|te) | sub tensiune | [(b(\u0103|a)ga((\u021b|t)i|te) | introdu((\u0219|s)i|se)) ]<in> priz(\u0103|a))",
                     "out": "on"
                 },
                 {
-                    "in": "(\uac10\uc9c0 \ud574\uc81c\ub428|\uc5c6\uc74c|\uac10\uc9c0\ud574\uc81c|\uc9c4\ub3d9 \uac10\uc9c0\ud574\uc81c)",
+                    "in": "(nealimentat((\u021b|t)i|te) | (sco(\u0219|s)i | scoase) din priz(\u0103|a))",
                     "out": "off"
                 }
             ]
         },
-        "bs_window_states": {
+        "bs_power_states_singular": {
             "values": [
                 {
-                    "in": "(\uc5f4\ub9bc|\uc5f4\ub824)",
+                    "in": "(alimentat[(\u0103|a)] | sub tensiune | [(b(\u0103|a)gat[(\u0103|a)] | introdus[(\u0103|a)]) ]<in> priz(\u0103|a))",
                     "out": "on"
                 },
                 {
-                    "in": "(\ub2eb\ud798|\ub2eb\ud600)",
-                    "out": "closed"
+                    "in": "(nealimentat[(\u0103|a)] | (b(\u0103|a)gat[(\u0103|a)] <in> | (scos | scoas(\u0103|a)) din) priz(\u0103|a))",
+                    "out": "off"
+                }
+            ]
+        },
+        "bs_presence_states": {
+            "values": [
+                {
+                    "in": "(acas(\u0103|a) | prezent[(\u0103|a)])",
+                    "out": "on"
+                },
+                {
+                    "in": "(plecat[(\u0103|a)] | absent[(\u0103|a)])",
+                    "out": "off"
+                }
+            ]
+        },
+        "bs_running_states": {
+            "values": [
+                {
+                    "in": "(pornit[(\u0103|a)] | (\u00ee|i)n [curs de] (rulare | desf(\u0103|a)(\u0219|s)urare))",
+                    "out": "on"
+                },
+                {
+                    "in": "((\u00ee|i)n repaus | oprit[(\u0103|a)])",
+                    "out": "off"
+                }
+            ]
+        },
+        "bs_running_states_active": {
+            "values": [
+                {
+                    "in": "ruleaz(\u0103|a)",
+                    "out": "on"
+                },
+                {
+                    "in": "s-a oprit",
+                    "out": "off"
+                }
+            ]
+        },
+        "bs_safety_states": {
+            "values": [
+                {
+                    "in": "nesigur",
+                    "out": "on"
+                },
+                {
+                    "in": "sigur",
+                    "out": "off"
+                }
+            ]
+        },
+        "bs_tamper_states": {
+            "values": [
+                {
+                    "in": "vandalizat",
+                    "out": "on"
+                },
+                {
+                    "in": "(normal | nevandalizat)",
+                    "out": "off"
+                }
+            ]
+        },
+        "bs_vibration_states_active": {
+            "values": [
+                {
+                    "in": "vibreaz(\u0103|a)",
+                    "out": "on"
+                },
+                {
+                    "in": "nu vibreaz(\u0103|a)",
+                    "out": "off"
                 }
             ]
         },
         "color": {
             "values": [
                 {
-                    "in": "(\ud770\uc0c9|\ud558\uc580\uc0c9|\ubc31\uc0c9|\ud654\uc774\ud2b8)",
+                    "in": "alb",
                     "out": "white"
                 },
                 {
-                    "in": "(\uac80\uc740\uc0c9|\uac80\uc815|\uac80\uc815\uc0c9|\ube14\ub799)",
+                    "in": "negru",
                     "out": "black"
                 },
                 {
-                    "in": "(\ube68\uac15|\ube68\uac04\uc0c9|\ube68\uac15\uc0c9|\ubd89\uc740\uc0c9|\ub808\ub4dc)",
+                    "in": "ro(\u0219|s)u",
                     "out": "red"
                 },
                 {
-                    "in": "(\uc624\ub80c\uc9c0\uc0c9|\uc8fc\ud669\uc0c9|\uc8fc\ud669|\uc624\ub80c\uc9c0)",
+                    "in": "(portocaliu | oranj)",
                     "out": "orange"
                 },
                 {
-                    "in": "(\ub178\ub780\uc0c9|\ub178\ub791|\ub178\ub780|\ub178\ub791\uc0c9|\uc610\ub85c\uc6b0)",
+                    "in": "galben",
                     "out": "yellow"
                 },
                 {
-                    "in": "(\ub179\uc0c9|\ucd08\ub85d|\ucd08\ub85d\uc0c9|\uadf8\ub9b0)",
+                    "in": "verde",
                     "out": "green"
                 },
                 {
-                    "in": "(\ud30c\ub791|\ud30c\ub780\uc0c9|\ud30c\ub791\uc0c9|\ud478\ub978\uc0c9|\uccad\uc0c9|\ube14\ub8e8)",
+                    "in": "(albastru | bleu)",
                     "out": "blue"
                 },
                 {
-                    "in": "(\ubcf4\ub77c\uc0c9|\ubcf4\ub77c|\ud37c\ud50c)",
+                    "in": "(lila | violet | purpuriu | mov)",
                     "out": "purple"
                 },
                 {
-                    "in": "(\uac08\uc0c9|\ubc24\uc0c9|\uace0\ub3d9\uc0c9|\ube0c\ub77c\uc6b4)",
+                    "in": "maro",
                     "out": "brown"
+                }
+            ]
+        },
+        "cover_classes_plural": {
+            "values": [
+                {
+                    "in": "copertine[le]",
+                    "out": "awning"
                 },
                 {
-                    "in": "(\ubd84\ud64d\uc0c9|\ubd84\ud64d|\ud551\ud06c)",
-                    "out": "pink"
+                    "in": "jaluzele[le]",
+                    "out": "blind"
                 },
                 {
-                    "in": "(\ud558\ub298\uc0c9|\uccad\ub85d\uc0c9|\uccad\ub85d)",
-                    "out": "turquoise"
+                    "in": "perdele[le]",
+                    "out": "curtain"
+                },
+                {
+                    "in": "<usile>",
+                    "out": "door"
+                },
+                {
+                    "in": "u(\u0219|s)ile (de la garaj | garajului)",
+                    "out": "garage"
+                },
+                {
+                    "in": "<portile>",
+                    "out": "gate"
+                },
+                {
+                    "in": "draperii[le]",
+                    "out": "shade"
+                },
+                {
+                    "in": "(rulouri[le] | obloane[le])",
+                    "out": "shutter"
+                },
+                {
+                    "in": "<ferestrele>",
+                    "out": "window"
                 }
             ]
         },
-        "cover_classes": {
+        "cover_classes_singular": {
             "values": [
                 {
-                    "in": "(\ucc28\uc591\ub9c9|\uc5b4\ub2dd|\ucc9c\ub9c9|\ucc28\uc591|\uac00\ub9ac\uac1c)",
+                    "in": "copertin(\u0103|a)",
                     "out": "awning"
                 },
                 {
-                    "in": "\ube14\ub77c\uc778\ub4dc",
+                    "in": "jaluzea[ua]",
                     "out": "blind"
                 },
                 {
-                    "in": "(\ucee4\ud2bc|\ucee4\ud150)",
+                    "in": "perdea[ua]",
                     "out": "curtain"
                 },
                 {
-                    "in": "(\ubb38|\ubc29\ubb38)",
+                    "in": "<usa>",
                     "out": "door"
                 },
                 {
-                    "in": "(\ucc28\uace0|\ucc28\uace0\ubb38)",
+                    "in": "u(\u0219|s)a (de la garaj | garajului)",
                     "out": "garage"
                 },
                 {
-                    "in": "(\uac8c\uc774\ud2b8|\ub300\ubb38|\ud604\uad00\ubb38|\ud604\uad00)",
+                    "in": "<poarta>",
                     "out": "gate"
                 },
                 {
-                    "in": "(\uc170\uc774\ub4dc|\uc250\uc774\ub4dc|\ubc84\ud2f0\uceec)",
+                    "in": "draperi(e|a)",
                     "out": "shade"
                 },
                 {
-                    "in": "(\ub8e8\ubc84|\ub8e8\ubc84\ucc3d)",
+                    "in": "(rulou[l] | oblon[ul])",
                     "out": "shutter"
                 },
                 {
-                    "in": "(\ucc3d\ubb38|\uc720\ub9ac\ucc3d|\ucc3d)",
+                    "in": "<fereastra>",
                     "out": "window"
                 }
             ]
         },
-        "cover_states": {
+        "cover_states_plural": {
             "values": [
                 {
-                    "in": "(\uc5f4\ub9bc|\uac77\uc74c|\uc5f4\ub824|\uac77\ud600|\uc5f4\uc5b4|\uac77\uc5b4)",
+                    "in": "<deschise>",
                     "out": "open"
                 },
                 {
-                    "in": "(\ub2eb\ud798|\uce68|\ub2eb\ud600|\ub2eb\uc544|\uccd0)",
+                    "in": "<inchise>",
                     "out": "closed"
                 },
                 {
-                    "in": "(\uc5ec\ub294 \uc911|\uac77\ub294 \uc911)",
+                    "in": "(\u00ee|i)n curs de (deschidere | ridicare)",
                     "out": "opening"
                 },
                 {
-                    "in": "(\ub2eb\ub294 \uc911|\uce58\ub294 \uc911)",
+                    "in": "(\u00ee|i)n curs de (inchidere | cobor\u00e2re)",
                     "out": "closing"
                 }
             ]
         },
-        "lock_states": {
+        "cover_states_singular": {
             "values": [
                 {
-                    "in": "(\uc7a0\uae08|\uc7a0\uae40|\uc7a0\uae08 \uc124\uc815|\uc7a0\uae08 \uc124\uc815\ub418\uc5b4|\uc7a0\uaca8)",
+                    "in": "<deschis>",
+                    "out": "open"
+                },
+                {
+                    "in": "<inchis>",
+                    "out": "closed"
+                },
+                {
+                    "in": "(\u00ee|i)n curs de (deschidere | ridicare)",
+                    "out": "opening"
+                },
+                {
+                    "in": "(\u00ee|i)n curs de (inchidere | cobor\u00e2re)",
+                    "out": "closing"
+                }
+            ]
+        },
+        "lock_states_plural": {
+            "values": [
+                {
+                    "in": "<incuiate>",
+                    "out": "locked"
+                },
+                {
+                    "in": "<descuiate>",
+                    "out": "unlocked"
+                }
+            ]
+        },
+        "lock_states_singular": {
+            "values": [
+                {
+                    "in": "<incuiat>",
                     "out": "locked"
                 },
                 {
-                    "in": "(\uc7a0\uae08 \ud574\uc81c|\uc7a0\uae08 \ud574\uc81c\ub418\uc5b4)",
+                    "in": "<descuiat>",
                     "out": "unlocked"
                 }
             ]
         },
-        "on_off_domains": {
+        "on_off_domains_plural": {
+            "values": [
+                {
+                    "in": "<luminile>",
+                    "out": "light"
+                },
+                {
+                    "in": "<ventilatoarele>",
+                    "out": "fan"
+                },
+                {
+                    "in": "<intrerupatoarele>",
+                    "out": "switch"
+                }
+            ]
+        },
+        "on_off_domains_singular": {
             "values": [
                 {
-                    "in": "(\uc870\uba85|\uc804\ub4f1|\ub4f1|\ubd88)",
+                    "in": "<lumina>",
                     "out": "light"
                 },
                 {
-                    "in": "(\uc120\ud48d\uae30|\ud32c|\ud658\uae30\uad6c|\ud658\ud48d\uae30|\uc2e4\ub9c1\ud32c)",
+                    "in": "<ventilatorul>",
                     "out": "fan"
                 },
                 {
-                    "in": "\uc2a4\uc704\uce58",
+                    "in": "<intrerupatorul>",
                     "out": "switch"
                 }
             ]
         },
-        "on_off_states": {
+        "on_off_states_plural": {
+            "values": [
+                {
+                    "in": "<pornite>",
+                    "out": "on"
+                },
+                {
+                    "in": "<oprite>",
+                    "out": "off"
+                }
+            ]
+        },
+        "on_off_states_singular": {
             "values": [
                 {
-                    "in": "(\ucf1c\uc9d0|\ucf2c|\ucf1c\uc838\uc788\ub2e4|\ucf1c\uc838)",
+                    "in": "<pornit>",
                     "out": "on"
                 },
                 {
-                    "in": "(\uaebc\uc9d0|\ub054|\uaebc\uc838\uc788\ub2e4|\uaebc\uc838)",
+                    "in": "<oprit>",
                     "out": "off"
                 }
             ]
         },
         "temperature": {
             "range": {
-                "from": 0,
+                "from": -100,
                 "to": 100,
                 "type": "temperature"
             }
         },
         "temperature_unit": {
             "values": [
                 "celsius",
                 {
-                    "in": "(\uc12d\uc528|\u00b0C|\u2103|\ub3c4)",
+                    "in": "c",
                     "out": "celsius"
                 },
                 "fahrenheit",
                 {
-                    "in": "(\ud654\uc528|\u00b0F|\u2109)",
+                    "in": "f",
                     "out": "fahrenheit"
                 }
             ]
         }
     },
     "responses": {
         "errors": {
-            "handle_error": "\uc758\ub3c4\ub97c \ucc98\ub9ac\ud558\ub294 \ub3d9\uc548 \uc608\uae30\uce58 \uc54a\uc740 \uc624\ub958\uac00 \ubc1c\uc0dd\ud588\uc2b5\ub2c8\ub2e4",
-            "no_area": "{{ area }}\uc774\ub77c\ub294 \uc601\uc5ed\uc744 \ucc3e\uc744 \uc218 \uc5c6\uc2b5\ub2c8\ub2e4",
-            "no_device_class": "{{ area }}\uc5d0\uc11c {{ device_class }}\uc744 \ucc3e\uc744 \uc218 \uc5c6\uc2b5\ub2c8\ub2e4",
-            "no_domain": "{{ area }}\uc5d0\uc11c {{ domain }}\uc744 \ucc3e\uc744 \uc218 \uc5c6\uc2b5\ub2c8\ub2e4",
-            "no_entity": "{{ entity }}\uc774\ub77c\ub294 \uad6c\uc131\uc694\uc18c\ub098 \uae30\uae30\ub97c \ucc3e\uc744 \uc218 \uc5c6\uc2b5\ub2c8\ub2e4",
-            "no_intent": "\uc8c4\uc1a1\ud569\ub2c8\ub2e4, \uc774\ud574\ud558\uc9c0 \ubabb\ud588\uc2b5\ub2c8\ub2e4"
+            "handle_error": "\u00cemi pare r\u0103u, a intervenit o eroare \u00een timpul proces\u0103rii cererii",
+            "no_area": "\u00cemi pare r\u0103u, nu este nici o zon\u0103 numit\u0103 {{ area }}",
+            "no_device_class": "\u00cemi pare r\u0103u, zona {{ area }} nu con\u021bine {{ device_class }}",
+            "no_domain": "\u00cemi pare r\u0103u, \u00een {{ area }} nu este {{ domain }}",
+            "no_entity": "\u00cemi pare r\u0103u, nu am g\u0103sit niciun dispozitiv sau entitate cu numele {{ entity }}",
+            "no_intent": "\u00cemi pare r\u0103u, nu am \u00een\u021beles cererea. Po\u021bi, te rog, s\u0103 repe\u021bi?"
         },
         "intents": {
             "HassGetState": {
-                "all": "{% if not query.unmatched: %}\n  \ub124\n{% else %}\n  {% set no_match = query.unmatched | map(attribute=\"name\") | sort | list %}\n  {% if no_match | length > 4 %}\n    \uc544\ub2c8\uc694, {{ no_match[:3] | join(\", \") }} \uadf8\ub9ac\uace0 {{ (no_match | length - 3) }}\uac1c\uc758 \uae30\uae30\ub294 \uadf8\ub807\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4\n  {% else %}\n    {% if no_match | length == 1 %}\n      \uc544\ub2c8\uc694, {{ no_match|first }} \uae30\uae30\ub294 \uadf8\ub807\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4\n    {%- else -%}\n      \uc544\ub2c8\uc694,\n      {% for name in no_match -%}\n        {% if not loop.first and not loop.last %}, {% elif loop.last and not loop.first %} \uadf8\ub9ac\uace0 {% endif -%}\n        {{ name }}\n      {%- endfor %}\n      \uae30\uae30\uac00 \uadf8\ub807\uc2b5\ub2c8\ub2e4\n    {% endif %}\n  {% endif %}\n{% endif %}\n",
-                "any": "{% if query.matched %}\n  {% set match = query.matched | map(attribute=\"name\") | sort | list %}\n  {% if match | length > 4 %}\n    \ub124, {{ match[:3] | join(\", \") }} \uadf8\ub9ac\uace0 {{ (match | length - 3) }}\uac1c\uc758 \uae30\uae30\uac00 \uadf8\ub807\uc2b5\ub2c8\ub2e4\n  {%- else -%}\n    {% if match | length == 1 %}\n      \ub124, {{ match|first }} \uae30\uae30\uac00 \uadf8\ub807\uc2b5\ub2c8\ub2e4\n    {% else %}\n      \ub124,\n      {% for name in match -%}\n        {% if not loop.first and not loop.last %}, {% elif loop.last and not loop.first %} \uadf8\ub9ac\uace0 {% endif -%}\n        {{ name }}\n      {%- endfor -%}\n      \uae30\uae30\uac00 \uadf8\ub807\uc2b5\ub2c8\ub2e4\n    {% endif %}\n  {% endif %}\n{% else %}\n  \uc544\ub2c8\uc694\n{% endif %}\n",
-                "default": "\uc8c4\uc1a1\ud569\ub2c8\ub2e4, \uc774\ud574\ud558\uc9c0 \ubabb\ud588\uc2b5\ub2c8\ub2e4, \ub2e4\uc2dc \uc2dc\ub3c4\ud574 \uc8fc\uc138\uc694",
-                "how_many": "{{ query.matched | length }}\uac1c\uc758 \uae30\uae30\uac00 \uadf8\ub807\uc2b5\ub2c8\ub2e4\n",
-                "one": "{{ slots.name }}\uc758 \uc0c1\ud0dc\ub294 {{ state.state_with_unit }}\uc785\ub2c8\ub2e4",
-                "one_yesno": "{% if query.matched %}\n  \ub124\n{% else %}\n  \uc544\ub2c8\uc694, {{ slots.name }}\uc758 \uc0c1\ud0dc\ub294 {{ state.state }}\uc785\ub2c8\ub2e4\n{% endif %}\n",
-                "which": "{% if not query.matched %}\n  \uc5b4\ub5a4 \uae30\uae30\ub3c4 \uadf8\ub807\uc9c0 \uc54a\uc2b5\ub2c8\ub2e4\n{% else: %}\n  {% set match = query.matched | map(attribute=\"name\") | sort | list %}\n  {% if match | length > 4 %}\n    {{ match[:3] | join(\", \") }} \uadf8\ub9ac\uace0 {{ (match | length - 3) }}\uac1c\uc758 \uae30\uae30\uac00 \uadf8\ub807\uc2b5\ub2c8\ub2e4\n  {% else %}\n    {%- for name in match -%}\n      {% if not loop.first and not loop.last %}, {% elif loop.last and not loop.first %} \uadf8\ub9ac\uace0 {% endif -%}\n      {{ name }}\n    {%- endfor %}\n    \uae30\uae30\uac00 \uadf8\ub807\uc2b5\ub2c8\ub2e4\n  {% endif %}\n{% endif %}\n"
+                "all": "{% if not query.unmatched: %}\n  Da\n{% else %}\n  {% set no_match = query.unmatched | map(attribute=\"name\") | sort | list %}\n  {% if no_match | length > 4 %}\n    Nu, {{ no_match[:3] | join(\", \") }} \u0219i \u00eenc\u0103 {{ (no_match | length - 3) }} nu sunt {{ slots.state }}\n  {%- else -%}\n    Nu,\n    {% for name in no_match -%}\n      {% if not loop.first and not loop.last %}, {% elif loop.last and not loop.first %} \u0219i {% endif -%}\n      {{ name }}\n    {%- endfor %} nu {{ 'este' if (query.unmatched|length) == 1 else 'sunt' }}\n  {% endif %}\n{% endif %}\n",
+                "any": "{% if query.matched %}\n  {% set match = query.matched | map(attribute=\"name\") | sort | list %}\n  {% if match | length > 4 %}\n    Da, {{ match[:3] | join(\", \") }} \u0219i \u00eenc\u0103 {{ (match | length - 3) }}\n  {%- else -%}\n    Da,\n    {% for name in match -%}\n      {% if not loop.first and not loop.last %}, {% elif loop.last and not loop.first %} \u0219i {% endif -%}\n      {{ name }}\n    {%- endfor -%}\n  {% endif %}\n{% else %}\n  Nu\n{% endif %}\n",
+                "how_many": "{{ query.matched | length }}\n",
+                "one": "{{ slots.name | capitalize }} este {{ state.state_with_unit }}",
+                "one_yesno": "{% if query.matched: %}\nDa\n{% else: %}\nNu, ci {{ state.state_with_unit }}\n{% endif %}\n",
+                "which": "{% if not query.matched %}\n  Nu exist\u0103 niciun astfel de element\n{% else: %}\n  {% set match = query.matched | map(attribute=\"name\") | sort | list %}\n  {% if match | length > 4 %}\n    {{ match[:3] | join(\", \") }} \u0219i \u00eenc\u0103 {{ (match | length - 3) }}\n  {% else %}\n    {%- for name in match -%}\n      {% if not loop.first and not loop.last %}, {% elif loop.last and not loop.first %} \u0219i {% endif -%}\n      {{ name }}\n    {%- endfor -%}\n  {% endif %}\n{% endif %}\n"
             },
             "HassTurnOff": {
-                "cover_device_class": "{{ slots.device_class }} \ub2eb\uc558\uc2b5\ub2c8\ub2e4",
-                "default": "{{ slots.name|default('') }} \ub2eb\uc558\uc2b5\ub2c8\ub2e4",
-                "fans_area": "{{ slots.area }} \ud32c\uc744 \uaed0\uc2b5\ub2c8\ub2e4",
-                "lights_area": "{{ slots.area }} \uc870\uba85\uc744 \uaed0\uc2b5\ub2c8\ub2e4",
-                "lock": "\uc7a0\uae08 \ud574\uc81c\ub418\uc5c8\uc2b5\ub2c8\ub2e4"
+                "cover": "Am \u00eenchis",
+                "covers_area": "Am \u00eenchis {{ slots.device_class }}",
+                "default": "Am oprit {{ slots.name }}",
+                "fans_area": "Am oprit ventilatoarele",
+                "light": "Am stins lumina",
+                "lights_area": "Am stins luminile"
             },
             "HassTurnOn": {
-                "cover_device_class": "{{ slots.device_class }} \uc5f4\uc5c8\uc2b5\ub2c8\ub2e4",
-                "default": "{{ slots.name|default('') }} \uc5f4\uc5c8\uc2b5\ub2c8\ub2e4",
-                "fans_area": "{{ slots.area }} \ud32c\uc744 \ucf30\uc2b5\ub2c8\ub2e4",
-                "lights_area": "{{ slots.area }} \uc870\uba85\uc744 \ucf30\uc2b5\ub2c8\ub2e4",
-                "lock": "\uc7a0\uac14\uc2b5\ub2c8\ub2e4",
-                "scene": "\ud65c\uc131\ud654\ud588\uc2b5\ub2c8\ub2e4",
-                "script": "\uc2dc\uc791\ud588\uc2b5\ub2c8\ub2e4"
+                "cover": "Am deschis",
+                "covers_area": "Am deschis {{ slots.device_class }}",
+                "default": "Am pornit {{ slots.name }}",
+                "fans_area": "Am pornit ventilatoarele",
+                "light": "Am aprins lumina",
+                "lights_area": "Am aprins luminile",
+                "scene": "Am activat",
+                "script": "Am pornit"
             }
         }
     },
     "skip_words": [
-        "\ud574\uc8fc\uc138\uc694",
-        "\uc8fc\uc138\uc694",
-        "\ud574\uc918"
+        "mul\u021bumesc",
+        "multumesc",
+        "te rog",
+        "te rog frumos",
+        "merci",
+        "mersi"
     ]
 }
```

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/lb.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/lb.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/lt.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/lt.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/lv.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/lv.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ml.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ml.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/mn.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/mn.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ms.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ms.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/nb.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/nb.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/nl.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/nl.json`

 * *Files 3% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.9962711683249879%*

 * *Differences: {"'expansion_rules'": "{'name_area': '(\\n  [[door|met|bij] [de|het] {area}][ ]{name}\\n  |[<in> "*

 * *                      '[de|het] {area}] [door|met|bij] <name>\\n  |[<met>] [de|het] {name} '*

 * *                      "[[in|op|van|bij] <area>]\\n)\\n', delete: ['sensor_name_area']}",*

 * * "'intents'": "{'HassTurnOff': {'data': {2: {'sentences': ['[<doe>] <name>[ ][<type>] [<naar>] "*

 * *              "uit', '<zou> <name>[ ][<type>] [<naar>] (uit willen |uit kunnen |uit [ ])<doe>', "*

 * *              "'[<zou>] <name>[ ][<t […]*

```diff
@@ -16,21 +16,20 @@
         "helderheid": "[de] (helderheid|felheid|intensiteit|lichtsterkte)",
         "in": "[in|op|van|bij]",
         "is": "(zijn|is|staa(n|t)|zit[ten]|word[t|en]|lig(t|gen))",
         "lamp": "[de|het|een] (lamp[en]|licht[en]|verlichting)",
         "met": "(door|met|bij)",
         "naar": "(naar|op)",
         "name": "[de|het] {name}",
-        "name_area": "(\n  [[<in> de|het|een] {area}][ ]<name>\n  |[de|het|een] {name}[ ][<type>] [[in|op|van|bij] <area>]\n)\n",
+        "name_area": "(\n  [[door|met|bij] [de|het] {area}][ ]{name}\n  |[<in> [de|het] {area}] [door|met|bij] <name>\n  |[<met>] [de|het] {name} [[in|op|van|bij] <area>]\n)\n",
         "op_slot": "<naar> (slot|vergrendeld)",
         "open": "(open|omhoog|naar boven|opwaarts)",
         "schakelaar": "[de|een] (schakelaar[s]|switch[es]|plug[gen])",
         "sensor": "[een|de] (apparaat|apparaten|sensor[s|en]|iets)",
         "sensor_area": "(\n  [[de|een] {area}][ ](apparaat|apparaten|sensor[s|en])\n  |[<in> [de|het] {area}] <sensor>\n  |[een|de] (apparaat|apparaten|sensor[s|en]|iets) [[in|op|van|bij] <area>]\n)\n",
-        "sensor_name_area": "(\n  [[door|met|bij] [de|het|een] {area}][ ]{name}\n  |[<in> [de|het|een] {area}] [door|met|bij] <name>\n  |[<met>] [de|het|een] {name} [[in|op|van|bij] <area>]\n)\n",
         "shade": "(screen[s]|rolgordijn[en])",
         "shutter": "(rolluik[en]|shutter[s])",
         "slot": "[de|het|een] ([deur]slot[en]|vergrendeling[en])",
         "slot_name_area": "[<in> <area>] (<slot> [van] [{area}[ ]]<name>|[de|het] {name}[ ]([deur]slot[en]|vergrendeling[en])) [[in|op|van|bij] [de|het] {area}]",
         "staat": "(status|staat|stand)",
         "temperature": "{temperature}[\u00b0|graden] [{temperature_unit}]",
         "type": "(<lamp>|<ventilator>|<afdekking>|<schakelaar>)",
@@ -74,215 +73,215 @@
                 {
                     "requires_context": {
                         "device_class": "carbon_monoxide",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "<detecteer> [<met>] <sensor_name_area> {bs_carbon_monoxide_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_carbon_monoxide_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_carbon_monoxide_states:state} <detecteer> <sensor_name_area>",
+                        "<detecteer> [<met>] <name_area> {bs_carbon_monoxide_states:state} [<in> <area>]",
+                        "neemt <name_area> {bs_carbon_monoxide_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_carbon_monoxide_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_carbon_monoxide_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_carbon_monoxide_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_carbon_monoxide_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "carbon_monoxide",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "cold",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "(is|<detecteer>) [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_cold_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_cold_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_cold_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_cold_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_cold_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_cold_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area>  {bs_cold_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area>  {bs_cold_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "cold",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "connectivity",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "<is> <sensor_name_area> {bs_connectivity_states:state} [<in> <area>]"
+                        "<is> <name_area> {bs_connectivity_states:state} [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "connectivity",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "door",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "<is> <sensor_name_area> {bs_door_states:state} [<in> <area>]"
+                        "<is> <name_area> {bs_door_states:state} [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "door",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "garage_door",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "<is> <sensor_name_area> {bs_garage_door_states:state} [<in> <area>]"
+                        "<is> <name_area> {bs_garage_door_states:state} [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "garage_door",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "gas",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "<detecteer> [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_gas_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_gas_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_gas_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_gas_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_gas_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_gas_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_gas_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_gas_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "gas",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "heat",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "(<is>|<detecteer>) [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_heat_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_heat_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_heat_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_heat_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_heat_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_heat_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_heat_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_heat_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "heat",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "light",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "(<is>|<detecteer>) [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_light_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_light_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_light_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_light_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_light_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_light_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_light_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_light_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "light",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "lock",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "<is> <sensor_name_area> {bs_lock_states:state} [<in> <area>]"
+                        "<is> <name_area> {bs_lock_states:state} [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "lock",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "moisture",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "(<is>|<detecteer>) [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_moisture_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_moisture_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_moisture_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_moisture_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_moisture_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_moisture_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_moisture_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_moisture_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "moisture",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "motion",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "<detecteer> [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_motion_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_motion_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_motion_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_motion_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_motion_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_motion_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_motion_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_motion_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "motion",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "occupancy",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "<detecteer> [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_occupancy_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_occupancy_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "(is|zijn|word[t|en]) [er] [<in> <area>] {bs_occupancy_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_occupancy_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "(is|zijn|word[t|en]) [er] [<in> <area>] {bs_occupancy_states:state} <detecteer> <name_area>",
                         "(is|zijn|wordt[t|en]) [er] [<in> <area>] {bs_occupancy_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_occupancy_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_occupancy_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "occupancy",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "opening",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "<is> <sensor_name_area> {bs_opening_states:state} [<in> <area>]"
+                        "<is> <name_area> {bs_opening_states:state} [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "opening",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -304,51 +303,51 @@
                     "requires_context": {
                         "device_class": "power",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "(<is>|<detecteer>) [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_power_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_power_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_power_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_power_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_power_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_power_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_power_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_power_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "power",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "presence",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "<is> <sensor_name_area> {bs_presence_states:state} [<in> <area>]"
+                        "<is> <name_area> {bs_presence_states:state} [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "presence",
                         "domain": "binary_sensor"
                     }
                 },
                 {
                     "requires_context": {
                         "device_class": "problem",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "<is> er [<in> <area>] {bs_problem_states:state} <sensor_name_area>",
-                        "(heeft|<detecteer>) <sensor_name_area> {bs_problem_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_problem_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_problem_states:state} <detecteer> <sensor_name_area>",
+                        "<is> er [<in> <area>] {bs_problem_states:state} <name_area>",
+                        "(heeft|<detecteer>) <name_area> {bs_problem_states:state} [<in> <area>]",
+                        "neemt <name_area> {bs_problem_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_problem_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_problem_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_problem_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_problem_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "problem",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -400,20 +399,20 @@
                 {
                     "requires_context": {
                         "device_class": "running",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "{bs_running_states:state} <sensor_name_area>",
+                        "{bs_running_states:state} <name_area>",
                         "(<is>|<detecteer>) [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_running_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_running_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_running_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_running_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_running_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_running_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_running_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_running_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "running",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -468,18 +467,18 @@
                     "requires_context": {
                         "device_class": "safety",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "(<is>|<detecteer>) [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_safety_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_safety_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_safety_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_safety_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_safety_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_safety_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_safety_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_safety_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "safety",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -532,18 +531,18 @@
                     "requires_context": {
                         "device_class": "smoke",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "(<is>|<detecteer>) [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_smoke_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_smoke_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_smoke_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_smoke_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_smoke_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_smoke_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_smoke_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_smoke_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "smoke",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -594,20 +593,20 @@
                 {
                     "requires_context": {
                         "device_class": "sound",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "maakt <sensor_name_area> {bs_sound_states:state}",
+                        "maakt <name_area> {bs_sound_states:state}",
                         "(<is>|<detecteer>) [er] [<in>|<met>] [<area>][ ]<name> [<in> <area>] {bs_sound_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_sound_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_sound_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_sound_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_sound_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_sound_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_sound_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_sound_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "sound",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -665,18 +664,18 @@
                     "requires_context": {
                         "device_class": "tamper",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "(<is>|<detecteer>) [er] [in|op|van|bij] [<area>][ |door |met |bij ]<name> [<in> <area>] {bs_tamper_states:state} [<in> <area>]",
-                        "neemt <sensor_name_area> {bs_tamper_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_tamper_states:state} <detecteer> <sensor_name_area>",
+                        "neemt <name_area> {bs_tamper_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
+                        "<is> [er] [<in> <area>] {bs_tamper_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_tamper_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_tamper_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_tamper_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "tamper",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -732,16 +731,16 @@
                     "requires_context": {
                         "device_class": "update",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
                         "<is> [<in> <area>][ ]<name> [[in|op|van] [<area>]] {bs_update_states:state} [<in> <area>]",
-                        "<is> [er] [<in> <area>] [een] {bs_update_states:state} [klaar|beschikbaar] voor <sensor_name_area>",
-                        "<is> [er] voor <sensor_name_area> [een] {bs_update_states:state} [klaar|beschikbaar] [<in> <area>]"
+                        "<is> [er] [<in> <area>] [een] {bs_update_states:state} [klaar|beschikbaar] voor <name_area>",
+                        "<is> [er] voor <name_area> [een] {bs_update_states:state} [klaar|beschikbaar] [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "update",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -792,20 +791,20 @@
                 {
                     "requires_context": {
                         "device_class": "vibration",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "{bs_vibration_states:state} <sensor_name_area>",
-                        "(is|<detecteer>) [er] <sensor_name_area> {bs_vibration_states:state} [<in> <area>]",
+                        "{bs_vibration_states:state} <name_area>",
+                        "(is|<detecteer>) [er] <name_area> {bs_vibration_states:state} [<in> <area>]",
                         "neemt [<area>][ ]<name> [<in> <area>] {bs_vibration_states:state} (waar [<in> <area>]|[<in> <area>] waar)",
-                        "<is> [er] [<in> <area>] {bs_vibration_states:state} <detecteer> <sensor_name_area>",
+                        "<is> [er] [<in> <area>] {bs_vibration_states:state} <detecteer> <name_area>",
                         "<is> [er] [<in> <area>] {bs_vibration_states:state} <met> [<area>][ ]<name> <detecteer> [<in> <area>]",
-                        "<is> [er] <sensor_name_area> {bs_vibration_states:state} <detecteer> [<in> <area>]"
+                        "<is> [er] <name_area> {bs_vibration_states:state} <detecteer> [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "vibration",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -862,15 +861,15 @@
                 {
                     "requires_context": {
                         "device_class": "window",
                         "domain": "binary_sensor"
                     },
                     "response": "bs_yesno",
                     "sentences": [
-                        "<is> <sensor_name_area> {bs_window_states:state} [<in> <area>]"
+                        "<is> <name_area> {bs_window_states:state} [<in> <area>]"
                     ],
                     "slots": {
                         "device_class": "window",
                         "domain": "binary_sensor"
                     }
                 },
                 {
@@ -1054,20 +1053,17 @@
                     "excludes_context": {
                         "domain": [
                             "cover",
                             "script"
                         ]
                     },
                     "sentences": [
-                        "[<doe>] <name>[ ][<type>] [<naar>] uit [<in> <area>]",
-                        "[<doe>] <name_area>[ ][<type>] [<naar>] uit",
-                        "<zou> <name>[ ][<type>] [<naar>] (uit willen |uit kunnen |uit [ ])<doe> [<in> <area>]",
-                        "<zou> <name_area>[ ][<type>] [<naar>] (uit willen |uit kunnen |uit [ ])<doe>",
-                        "[<zou>] <name>[ ][<type>] [willen|kunnen] (uit[ ](zetten|doen)|uitschakelen|doen) [<in> <area>]",
-                        "[<zou>] <name_area>[ ][<type>] [willen|kunnen] (uit[ ](zetten|doen)|uitschakelen|doen)"
+                        "[<doe>] <name>[ ][<type>] [<naar>] uit",
+                        "<zou> <name>[ ][<type>] [<naar>] (uit willen |uit kunnen |uit [ ])<doe>",
+                        "[<zou>] <name>[ ][<type>] [willen|kunnen] (uit[ ](zetten|doen)|uitschakelen|doen)"
                     ]
                 },
                 {
                     "response": "lights_area",
                     "sentences": [
                         "[<doe>] [<alle>] <lamp> [<naar>] uit <in> <area>",
                         "<zou> [<alle>] <lamp> [<naar>] (uit willen |uit kunnen |uit[ ])<doe> <in> <area>",
@@ -1426,22 +1422,18 @@
                         "domain": [
                             "cover",
                             "scene",
                             "script"
                         ]
                     },
                     "sentences": [
-                        "[<doe>] <name>[ ][<type>] [<naar>] aan [<in> <area>]",
-                        "[<doe>] <name_area>[ ][<type>] [<naar>] aan",
-                        "<zou> <name>[ ][<type>] [<naar>] ((aan|in) willen |(aan|in) kunnen |(aan|in) [ ])<doe> [<in> <area>]",
-                        "<zou> <name_area>[ ][<type>] [<naar>] ((aan|in) willen |(aan|in) kunnen |(aan|in) [ ])<doe>",
-                        "schakel <name>[ ][<type>] [<naar>] in [<in> <area>]",
-                        "schakel <name_area>[ ][<type>] [<naar>] in",
-                        "[<zou>] <name>[ ][<type>] [willen|kunnen] (aan[ ](zetten|doen)|inschakelen|doen) [<in> <area>]",
-                        "[<zou>] <name_area>[ ][<type>] [willen|kunnen] (aan[ ](zetten|doen)|inschakelen|doen)"
+                        "[<doe>] <name>[ ][<type>] [<naar>] aan",
+                        "<zou> <name>[ ][<type>] [<naar>] ((aan|in) willen |(aan|in) kunnen |(aan|in) [ ])<doe>",
+                        "schakel <name>[ ][<type>] [<naar>] in",
+                        "[<zou>] <name>[ ][<type>] [willen|kunnen] (aan[ ](zetten|doen)|inschakelen|doen)"
                     ]
                 }
             ]
         }
     },
     "language": "nl",
     "lists": {
```

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/pl.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/pl.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/pt-br.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/pt-br.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/pt.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/pt.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ru.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ru.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sk.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sk.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sl.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sl.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sr.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sr.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sv.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sv.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/sw.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/sw.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/uk.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/uk.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/ur.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/ur.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/vi.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/vi.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/zh-cn.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/zh-cn.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/zh-hk.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/zh-hk.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/homeassistant/zh-tw.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/homeassistant/zh-tw.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ar.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ar.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/bg.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/bg.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ca.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ca.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/cs.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/cs.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/da.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/da.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/de-CH.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/de-CH.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/de.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/de.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/el.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/el.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/en.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/en.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/es.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/es.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/fi.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/fi.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/fr-CA.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/fr-CA.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/fr.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/fr.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/gl.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/gl.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/he.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/he.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/hr.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/hr.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/hu.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/hu.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/id.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/id.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/it.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/it.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ka.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ka.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ko.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/nl.json`

 * *Files 26% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.7934027777777778%*

 * *Differences: {"'intents'": "{'HassLightSet': {'data': {0: {'sentences': ['[<doe>|<zou>] <name>[ ][<lamp>][ "*

 * *              "][<helderheid>] [<naar>] <brightness> [[willen|kunnen] <doe>]', '[<doe>|<zou>] "*

 * *              '<helderheid> [van] <name>[ ][<lamp>] [<naar>] <brightness> [[willen|kunnen] '*

 * *              "<doe>]'], delete: ['slots']}, 1: {'sentences': ['[<doe>|<zou>] [<helderheid>] <in> "*

 * *              "<area>[[ ]<lamp>] [<naar>] <brightness> [[willen|kunnen] <doe>]', '[<doe>|<zou>] "*

 * *              "<area>[ ][<hel […]*

```diff
@@ -1,103 +1,72 @@
 {
     "intents": {
         "HassLightSet": {
             "data": [
                 {
-                    "requires_context": {
-                        "domain": "light"
-                    },
-                    "response": "brightness",
-                    "sentences": [
-                        "<name> \ubc1d\uae30 <brightness>[\ub85c] [<numeric_value_set>]",
-                        "<name>\uc758 \ubc1d\uae30 <brightness>[\ub85c] [<numeric_value_set>]",
-                        "<name> <brightness> \ubc1d\uae30[\ub85c] [<numeric_value_set>]"
-                    ]
-                },
-                {
-                    "requires_context": {
-                        "domain": "light"
-                    },
                     "response": "brightness",
                     "sentences": [
-                        "<name> <brightness>[\ub85c] <numeric_value_set>"
+                        "[<doe>|<zou>] <name>[ ][<lamp>][ ][<helderheid>] [<naar>] <brightness> [[willen|kunnen] <doe>]",
+                        "[<doe>|<zou>] <helderheid> [van] <name>[ ][<lamp>] [<naar>] <brightness> [[willen|kunnen] <doe>]"
                     ]
                 },
                 {
                     "response": "brightness",
                     "sentences": [
-                        "<area> \ubc1d\uae30\ub97c <brightness>\ub85c [<numeric_value_set>]",
-                        "<area>\uc758 \ubc1d\uae30\ub97c <brightness>\ub85c [<numeric_value_set>]",
-                        "<area>\uc744 <brightness> \ubc1d\uae30\ub85c [<numeric_value_set>]",
-                        "<area> <brightness>\ub85c [<numeric_value_set>]"
-                    ],
-                    "slots": {
-                        "name": "all"
-                    }
-                },
-                {
-                    "response": "brightness",
-                    "sentences": [
-                        "<area> <brightness>\ub85c <numeric_value_set>"
+                        "[<doe>|<zou>] [<helderheid>] <in> <area>[[ ]<lamp>] [<naar>] <brightness> [[willen|kunnen] <doe>]",
+                        "[<doe>|<zou>] <area>[ ][<helderheid>|lamp] [<naar>] <brightness> [[willen|kunnen] <doe>]"
                     ],
                     "slots": {
                         "name": "all"
                     }
                 },
                 {
                     "requires_context": {
                         "domain": "light"
                     },
                     "response": "brightness",
                     "sentences": [
-                        "<name> \ubc1d\uae30 {brightness_level:brightness}[\ub85c] [<numeric_value_set>]",
-                        "<name>\uc758 \ubc1d\uae30 {brightness_level:brightness}[\ub85c] [<numeric_value_set>]",
-                        "<name> {brightness_level:brightness} \ubc1d\uae30[\ub85c] [<numeric_value_set>]",
-                        "<name> {brightness_level:brightness}"
+                        "[<doe>|<zou>] <name>[ ][lamp][ ][<helderheid>] [<naar>] [het] {brightness_level:brightness} [[willen|kunnen] <doe>]",
+                        "[<doe>|<zou>] <helderheid> [van] <name>[ ][<lamp>] [<naar>] [het] {brightness_level:brightness} [[willen|kunnen] <doe>]",
+                        "[<doe>|<zou>] <name>[ ][lamp] [<naar>] [de|het] {brightness_level:brightness} <helderheid> [[willen|kunnen] <doe>]"
                     ]
                 },
                 {
                     "response": "brightness",
                     "sentences": [
-                        "<area> \ubc1d\uae30\ub97c [the] {brightness_level:brightness}[\ub85c] [<numeric_value_set>]",
-                        "<area>\uc758 \ubc1d\uae30\ub97c [the] {brightness_level:brightness}[\ub85c] [<numeric_value_set>]",
-                        "<area> {brightness_level:brightness} \ubc1d\uae30[\ub85c] [<numeric_value_set>]",
-                        "<area> \ubc1d\uae30 {brightness_level:brightness}[\ub85c] [<numeric_value_set>]",
-                        "<area> {brightness_level:brightness}"
+                        "[<doe>|<zou>] [<helderheid>] <in> <area> [<naar>] [het] {brightness_level:brightness} [[willen|kunnen] <doe>]",
+                        "[<doe>|<zou>] <area>[ ][<helderheid>] [<naar>] [het] {brightness_level:brightness} [[willen|kunnen] <doe>]",
+                        "[<doe>|<zou>] <area> [<naar>] [de|het] {brightness_level:brightness} [<helderheid>] [[willen|kunnen] <doe>]"
                     ],
                     "slots": {
                         "name": "all"
                     }
                 },
                 {
-                    "requires_context": {
-                        "domain": "light"
-                    },
                     "response": "color",
                     "sentences": [
-                        "<name> [\uc0c9\uc0c1] {color}[\ub85c|\uc73c\ub85c] [<set>]",
-                        "<name>\uc758 [\uc0c9\uc0c1] {color}[\ub85c|\uc73c\ub85c] [<set>]"
+                        "[<doe>|<zou>] <name>[ ][<lamp>][ ][kleur] [<naar>] {color} [[willen|kunnen] <doe>]",
+                        "[<doe>|<zou>] [[de] kleur van] <name>[ ][<lamp>] [<naar>] {color} [[willen|kunnen] <doe>]"
                     ]
                 },
                 {
                     "response": "color",
                     "sentences": [
-                        "(<area> | <area> \ubaa8\ub4e0 \uc870\uba85 | \ubaa8\ub4e0 <area> \uc870\uba85)\uc758 [\uc0c9\uc0c1] {color}[\ub85c|\uc73c\ub85c] [<set>]",
-                        "(<area> | <area> \ubaa8\ub4e0 \uc870\uba85 | \ubaa8\ub4e0 <area> \uc870\uba85) [\uc0c9\uc0c1]  {color}[\ub85c|\uc73c\ub85c] [<set>]"
+                        "[<doe>|<zou>] [[de] kleur van] [[<alle>] <lamp>] [in|van] <area>[[ ]<lamp>] [<naar>] {color} [[willen|kunnen] <doe>]"
                     ],
                     "slots": {
                         "name": "all"
                     }
                 }
             ]
         }
     },
-    "language": "ko",
+    "language": "nl",
     "responses": {
         "intents": {
             "HassLightSet": {
-                "brightness": "\ubc1d\uae30\uac00 \uc124\uc815\ub418\uc5c8\uc2b5\ub2c8\ub2e4",
-                "color": "\uc0c9\uc0c1\uc774 \uc124\uc815\ub418\uc5c8\uc2b5\ub2c8\ub2e4"
+                "brightness": "Helderheid aangepast",
+                "color": "Kleur aangepast"
             }
         }
     }
 }
```

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/lb.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/lb.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/lt.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/lt.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/lv.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/lv.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ml.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ml.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ms.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ms.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/nb.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/nb.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/pl.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/zh-tw.json`

 * *Files 21% similar despite different names*

#### Pretty-printed

 * *Similarity: 0.7847222222222222%*

 * *Differences: {"'intents'": "{'HassLightSet': {'data': {2: {'sentences': "*

 * *              "['<let><name>[(燈|燈光)][亮度]<set_to>{brightness_level:brightness}', "*

 * *              "'<set><name>[(燈|燈光)][亮度][<to>]{brightness_level:brightness}'], 'requires_context': "*

 * *              "OrderedDict([('domain', 'light')])}, 3: {'sentences': "*

 * *              "['<let><area>[(照明|燈光)][亮度]<set_to>{brightness_level:brightness}', "*

 * *              "'<set><area>[(照明|燈光)][亮度][<to>]{brightness_level:brightness}'], 'response': "*

 * *              "'bright […]*

```diff
@@ -1,46 +1,79 @@
 {
     "intents": {
         "HassLightSet": {
             "data": [
                 {
+                    "requires_context": {
+                        "domain": "light"
+                    },
                     "response": "brightness",
                     "sentences": [
-                        "<set> [jasno\u015b\u0107] <name> na <brightness>"
+                        "[<let>]<name>[(\u71c8|\u71c8\u5149)][\u4eae\u5ea6]<set_to><brightness>",
+                        "<set><name>[(\u71c8|\u71c8\u5149)][\u4eae\u5ea6]<to><brightness>"
                     ]
                 },
                 {
-                    "response": "brightness_area",
+                    "response": "brightness",
                     "sentences": [
-                        "<set> [jasno\u015b\u0107] <area> na <brightness>"
+                        "<let><area>[(\u7167\u660e|\u71c8\u5149)][\u4eae\u5ea6]<set_to><brightness>",
+                        "<set><area>[(\u7167\u660e|\u71c8\u5149)][\u4eae\u5ea6][<to>]<brightness>"
                     ],
                     "slots": {
                         "name": "all"
                     }
                 },
                 {
-                    "response": "color",
+                    "requires_context": {
+                        "domain": "light"
+                    },
+                    "response": "brightness",
                     "sentences": [
-                        "<set> [kolor] <name> na {color}"
+                        "<let><name>[(\u71c8|\u71c8\u5149)][\u4eae\u5ea6]<set_to>{brightness_level:brightness}",
+                        "<set><name>[(\u71c8|\u71c8\u5149)][\u4eae\u5ea6][<to>]{brightness_level:brightness}"
                     ]
                 },
                 {
-                    "response": "color_area",
+                    "response": "brightness",
+                    "sentences": [
+                        "<let><area>[(\u7167\u660e|\u71c8\u5149)][\u4eae\u5ea6]<set_to>{brightness_level:brightness}",
+                        "<set><area>[(\u7167\u660e|\u71c8\u5149)][\u4eae\u5ea6][<to>]{brightness_level:brightness}"
+                    ],
+                    "slots": {
+                        "name": "all"
+                    }
+                },
+                {
+                    "requires_context": {
+                        "domain": "light"
+                    },
+                    "response": "color",
                     "sentences": [
-                        "<set> [wszystkie kolory|kolory] <area> na {color}"
+                        "<let><name>[(\u7167\u660e|\u71c8\u5149)][(\u984f\u8272|\u8272\u6eab)][<set_to>]{color}",
+                        "<set><name>[(\u7167\u660e|\u71c8\u5149)][(\u984f\u8272|\u8272\u6eab)]<to>{color}"
                     ]
+                },
+                {
+                    "response": "color",
+                    "sentences": [
+                        "<let><area>[(\u7167\u660e|\u71c8\u5149)][(\u984f\u8272|\u8272\u6eab)][<set_to>]{color}",
+                        "<set><area>[(\u7167\u660e|\u71c8\u5149)][(\u984f\u8272|\u8272\u6eab)]<to>{color}"
+                    ],
+                    "slots": {
+                        "name": "all"
+                    }
                 }
             ]
         }
     },
-    "language": "pl",
+    "language": "zh-tw",
     "responses": {
         "intents": {
             "HassLightSet": {
-                "brightness": "Ustawiono jasno\u015b\u0107 {{ slots.name }} na {{ slots.brightness }}",
-                "brightness_area": "Ustawiono jasno\u015b\u0107 w {{ slots.area }} na {{ slots.brightness }}",
-                "color": "Ustawiono kolor {{ slots.name }} na {{ slots.color }}",
-                "color_area": "Ustawiono kolor w {{ slots.area }} na {{ slots.color }}"
+                "brightness": "{{ slots.name }}\u4eae\u5ea6\u5df2\u8abf\u6574",
+                "brightness_area": "{{ slots.area }}\u4eae\u5ea6\u5df2\u8abf\u6574\u70ba{{ slots.brightness }}",
+                "color": "{{ slots.area }}\u984f\u8272\u5df2\u8abf\u6574",
+                "color_area": "{{ slots.area }}\u984f\u8272\u5df2\u8abf\u6574\u70ba{{ slots.color }}"
             }
         }
     }
 }
```

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/pt.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/pt.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ro.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ro.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ru.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ru.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/sk.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/sk.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/sr.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/sr.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/sv.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/sv.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/uk.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/uk.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/ur.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/ur.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/vi.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/vi.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/zh-cn.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/zh-cn.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/data/light/zh-hk.json` & `home-assistant-intents-2023.6.5/home_assistant_intents/data/light/zh-hk.json`

 * *Files identical despite different names*

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents/domains.py` & `home-assistant-intents-2023.6.5/home_assistant_intents/domains.py`

 * *Files 11% similar despite different names*

```diff
@@ -7,16 +7,14 @@
         "cs",
         "da",
         "de",
         "de-CH",
         "el",
         "en",
         "es",
-        "et",
-        "eu",
         "fa",
         "fi",
         "fr",
         "fr-CA",
         "gl",
         "gu",
         "he",
@@ -64,15 +62,14 @@
         "cs",
         "da",
         "de",
         "de-CH",
         "el",
         "en",
         "es",
-        "eu",
         "fa",
         "fi",
         "fr",
         "fr-CA",
         "gl",
         "gu",
         "he",
```

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents.egg-info/PKG-INFO` & `home-assistant-intents-2023.6.5/home_assistant_intents.egg-info/PKG-INFO`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: home-assistant-intents
-Version: 2023.6.28
+Version: 2023.6.5
 Summary: Intents for Home Assistant
 Author-email: The Home Assistant Authors <hello@home-assistant.io>
 License: Apache-2.0
 Project-URL: Source Code, https://github.com/home-assistant/intents
 Keywords: home,assistant,intent,recognition
 Platform: any
 Classifier: Development Status :: 3 - Alpha
```

### Comparing `home-assistant-intents-2023.6.28/home_assistant_intents.egg-info/SOURCES.txt` & `home-assistant-intents-2023.6.5/home_assistant_intents.egg-info/SOURCES.txt`

 * *Files 0% similar despite different names*

```diff
@@ -16,16 +16,14 @@
 home_assistant_intents/data/homeassistant/cs.json
 home_assistant_intents/data/homeassistant/da.json
 home_assistant_intents/data/homeassistant/de-CH.json
 home_assistant_intents/data/homeassistant/de.json
 home_assistant_intents/data/homeassistant/el.json
 home_assistant_intents/data/homeassistant/en.json
 home_assistant_intents/data/homeassistant/es.json
-home_assistant_intents/data/homeassistant/et.json
-home_assistant_intents/data/homeassistant/eu.json
 home_assistant_intents/data/homeassistant/fa.json
 home_assistant_intents/data/homeassistant/fi.json
 home_assistant_intents/data/homeassistant/fr-CA.json
 home_assistant_intents/data/homeassistant/fr.json
 home_assistant_intents/data/homeassistant/gl.json
 home_assistant_intents/data/homeassistant/gu.json
 home_assistant_intents/data/homeassistant/he.json
@@ -71,15 +69,14 @@
 home_assistant_intents/data/light/cs.json
 home_assistant_intents/data/light/da.json
 home_assistant_intents/data/light/de-CH.json
 home_assistant_intents/data/light/de.json
 home_assistant_intents/data/light/el.json
 home_assistant_intents/data/light/en.json
 home_assistant_intents/data/light/es.json
-home_assistant_intents/data/light/eu.json
 home_assistant_intents/data/light/fa.json
 home_assistant_intents/data/light/fi.json
 home_assistant_intents/data/light/fr-CA.json
 home_assistant_intents/data/light/fr.json
 home_assistant_intents/data/light/gl.json
 home_assistant_intents/data/light/gu.json
 home_assistant_intents/data/light/he.json
```

### Comparing `home-assistant-intents-2023.6.28/pyproject.toml` & `home-assistant-intents-2023.6.5/pyproject.toml`

 * *Files 14% similar despite different names*

```diff
@@ -1,14 +1,14 @@
 [build-system]
 requires = ["setuptools~=62.3", "wheel~=0.37.1"]
 build-backend = "setuptools.build_meta"
 
 [project]
 name        = "home-assistant-intents"
-version     = "2023.6.28"
+version     = "2023.6.5"
 license     = {text = "Apache-2.0"}
 description = "Intents for Home Assistant"
 readme      = "README.md"
 authors     = [
     {name = "The Home Assistant Authors", email = "hello@home-assistant.io"}
 ]
 keywords    = ["home", "assistant", "intent", "recognition"]
```


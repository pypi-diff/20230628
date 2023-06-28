# Comparing `tmp/kk-0.9.3.tar.gz` & `tmp/kk-0.9.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "kk-0.9.3.tar", last modified: Mon Jun 19 02:28:53 2023, max compression
+gzip compressed data, was "kk-0.9.4.tar", last modified: Wed Jun 28 09:10:15 2023, max compression
```

## Comparing `kk-0.9.3.tar` & `kk-0.9.4.tar`

### file list

```diff
@@ -1,170 +1,170 @@
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.766532 kk-0.9.3/
--rw-r--r--   0 root         (0) root         (0)      589 2023-06-19 02:28:53.766532 kk-0.9.3/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     3203 2022-07-14 13:13:22.000000 kk-0.9.3/README.md
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.746532 kk-0.9.3/kk/
--rw-r--r--   0 root         (0) root         (0)      129 2023-06-19 02:28:50.000000 kk-0.9.3/kk/__init__.py
--rw-r--r--   0 root         (0) root         (0)    36952 2023-06-19 01:39:51.000000 kk-0.9.3/kk/handler.py
--rwxr-xr-x   0 root         (0) root         (0)     4035 2022-07-14 13:13:22.000000 kk-0.9.3/kk/index.py
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.750532 kk-0.9.3/kk/static/
--rw-r--r--   0 root         (0) root         (0)     4286 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/favicon.ico
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.750532 kk-0.9.3/kk/static/img/
--rw-rw-r--   0 root         (0) root         (0)     3397 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/apk.png
--rw-rw-r--   0 root         (0) root         (0)     3105 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/audio.png
--rw-rw-r--   0 root         (0) root         (0)     4154 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/c.png
--rw-rw-r--   0 root         (0) root         (0)     3638 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/cpp.png
--rw-rw-r--   0 root         (0) root         (0)     5479 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/css.png
--rw-rw-r--   0 root         (0) root         (0)     4934 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/database.png
--rw-rw-r--   0 root         (0) root         (0)     3229 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/dmg.png
--rw-rw-r--   0 root         (0) root         (0)     4321 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/docx.png
--rw-rw-r--   0 root         (0) root         (0)     4436 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/exe.png
--rw-rw-r--   0 root         (0) root         (0)     3409 2023-06-19 00:58:34.000000 kk-0.9.3/kk/static/img/file.png
--rw-rw-r--   0 root         (0) root         (0)     1595 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/folder.png
--rw-rw-r--   0 root         (0) root         (0)     6366 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/golang.png
--rw-rw-r--   0 root         (0) root         (0)     3457 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/html.png
--rw-rw-r--   0 root         (0) root         (0)     3494 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/image.png
--rw-rw-r--   0 root         (0) root         (0)     5324 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/ini.png
--rw-rw-r--   0 root         (0) root         (0)     5633 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/iso.png
--rw-rw-r--   0 root         (0) root         (0)     5994 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/java.png
--rw-rw-r--   0 root         (0) root         (0)     5472 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/javascript.png
--rw-rw-r--   0 root         (0) root         (0)     4946 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/json.png
--rw-rw-r--   0 root         (0) root         (0)    11198 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/kindle.png
--rw-rw-r--   0 root         (0) root         (0)     3968 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/markdown.png
--rw-rw-r--   0 root         (0) root         (0)     4285 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/pdf.png
--rw-rw-r--   0 root         (0) root         (0)     3158 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/pptx.png
--rw-rw-r--   0 root         (0) root         (0)     3859 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/python.png
--rw-rw-r--   0 root         (0) root         (0)     2114 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/rar.png
--rw-rw-r--   0 root         (0) root         (0)     1394 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/shell.png
--rw-rw-r--   0 root         (0) root         (0)     3806 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/txt.png
--rw-rw-r--   0 root         (0) root         (0)     2448 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/video.png
--rw-rw-r--   0 root         (0) root         (0)     3623 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/vue.png
--rw-rw-r--   0 root         (0) root         (0)     3406 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/xlsx.png
--rw-r--r--   0 root         (0) root         (0)     3446 2023-06-19 01:39:13.000000 kk-0.9.3/kk/static/img/xml.png
--rw-rw-r--   0 root         (0) root         (0)     4812 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/yaml.png
--rw-rw-r--   0 root         (0) root         (0)     1930 2023-06-19 00:48:55.000000 kk-0.9.3/kk/static/img/zip.png
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.754532 kk-0.9.3/kk/static/img2/
--rw-r--r--   0 root         (0) root         (0)     5153 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/apk.png
--rw-r--r--   0 root         (0) root         (0)    17071 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/audio.png
--rw-r--r--   0 root         (0) root         (0)     6382 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/c.png
--rw-r--r--   0 root         (0) root         (0)     6673 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/cpp.png
--rw-r--r--   0 root         (0) root         (0)     5635 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/css.png
--rw-r--r--   0 root         (0) root         (0)    16755 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/database.png
--rw-r--r--   0 root         (0) root         (0)     4006 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/dmg.png
--rw-r--r--   0 root         (0) root         (0)     7904 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/docx.png
--rw-r--r--   0 root         (0) root         (0)     2245 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/exe.png
--rw-r--r--   0 root         (0) root         (0)     2822 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/file.png
--rw-r--r--   0 root         (0) root         (0)     3688 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/folder.png
--rw-r--r--   0 root         (0) root         (0)    12494 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/golang.png
--rw-r--r--   0 root         (0) root         (0)     8140 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/html.png
--rw-r--r--   0 root         (0) root         (0)     7301 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/image.png
--rw-r--r--   0 root         (0) root         (0)     8962 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/ini.png
--rw-r--r--   0 root         (0) root         (0)     7287 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/iso.png
--rw-r--r--   0 root         (0) root         (0)    15616 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/java.png
--rw-r--r--   0 root         (0) root         (0)    10518 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/javascript.png
--rw-r--r--   0 root         (0) root         (0)     3847 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/json.png
--rw-r--r--   0 root         (0) root         (0)     2997 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/kindle.png
--rw-r--r--   0 root         (0) root         (0)     2901 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/markdown.png
--rw-r--r--   0 root         (0) root         (0)    12717 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/pdf.png
--rw-r--r--   0 root         (0) root         (0)    12577 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/php.png
--rw-r--r--   0 root         (0) root         (0)     3574 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/pptx.png
--rw-r--r--   0 root         (0) root         (0)     9024 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/python.png
--rw-r--r--   0 root         (0) root         (0)     7434 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/shell.png
--rw-r--r--   0 root         (0) root         (0)     2901 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/txt.png
--rw-r--r--   0 root         (0) root         (0)    15897 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/video.png
--rw-r--r--   0 root         (0) root         (0)    13413 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/vue.png
--rw-r--r--   0 root         (0) root         (0)     8139 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/xlsx.png
--rw-r--r--   0 root         (0) root         (0)     3449 2023-06-19 02:22:37.000000 kk-0.9.3/kk/static/img2/xml.png
--rw-r--r--   0 root         (0) root         (0)    11355 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/yaml.png
--rw-r--r--   0 root         (0) root         (0)     3509 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/img2/zip.png
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.746532 kk-0.9.3/kk/static/src/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.758532 kk-0.9.3/kk/static/src/css/
--rw-r--r--   0 root         (0) root         (0)    45250 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/css/DPlayer.min.css
--rw-r--r--   0 root         (0) root         (0)     5254 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/css/iconfont.css
--rw-r--r--   0 root         (0) root         (0)     5572 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/css/iconfont.eot
--rw-r--r--   0 root         (0) root         (0)    15798 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/css/iconfont.svg
--rw-r--r--   0 root         (0) root         (0)     5404 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/css/iconfont.ttf
--rw-r--r--   0 root         (0) root         (0)     3536 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/css/iconfont.woff
--rw-r--r--   0 root         (0) root         (0)     2904 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/css/iconfont.woff2
--rw-r--r--   0 root         (0) root         (0)     3584 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/css/markdown.css
--rw-r--r--   0 root         (0) root         (0)     2477 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/css/monokai_sublime.css
--rw-r--r--   0 root         (0) root         (0)     9750 2023-06-19 02:23:34.000000 kk-0.9.3/kk/static/src/css/style.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.758532 kk-0.9.3/kk/static/src/js/
--rw-r--r--   0 root         (0) root         (0)   116781 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/DPlayer.min.js
--rw-r--r--   0 root         (0) root         (0)    10453 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/clipboard.min.js
--rw-r--r--   0 root         (0) root         (0)   173418 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/flv.min.js
--rw-r--r--   0 root         (0) root         (0)    80655 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/highcharts-more.js
--rw-r--r--   0 root         (0) root         (0)   254576 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/highcharts.js
--rw-r--r--   0 root         (0) root         (0)   749330 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/highlight.pack.min.js
--rw-r--r--   0 root         (0) root         (0)   231552 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/hls.min.js
--rw-r--r--   0 root         (0) root         (0)     5595 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/imagesloaded.pkgd.min.js
--rw-r--r--   0 root         (0) root         (0)    88145 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/jquery.min.js
--rw-r--r--   0 root         (0) root         (0)    24104 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/masonry.pkgd.min.js
--rw-r--r--   0 root         (0) root         (0)    19990 2023-06-11 23:06:09.000000 kk-0.9.3/kk/static/src/js/page.js
--rw-r--r--   0 root         (0) root         (0)     2221 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/utils.js
--rw-r--r--   0 root         (0) root         (0)    70754 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/js/webuploader.nolog.min.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.762532 kk-0.9.3/kk/static/src/layui/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.762532 kk-0.9.3/kk/static/src/layui/css/
--rw-r--r--   0 root         (0) root         (0)    74304 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/layui.css
--rw-r--r--   0 root         (0) root         (0)     9886 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/layui.mobile.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.762532 kk-0.9.3/kk/static/src/layui/css/modules/
--rw-r--r--   0 root         (0) root         (0)     1064 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/modules/code.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.746532 kk-0.9.3/kk/static/src/layui/css/modules/laydate/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.762532 kk-0.9.3/kk/static/src/layui/css/modules/laydate/default/
--rw-r--r--   0 root         (0) root         (0)     7538 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/modules/laydate/default/laydate.css
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.746532 kk-0.9.3/kk/static/src/layui/css/modules/layer/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.762532 kk-0.9.3/kk/static/src/layui/css/modules/layer/default/
--rw-r--r--   0 root         (0) root         (0)     5911 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/modules/layer/default/icon-ext.png
--rw-r--r--   0 root         (0) root         (0)    11493 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/modules/layer/default/icon.png
--rw-r--r--   0 root         (0) root         (0)    14426 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/modules/layer/default/layer.css
--rw-r--r--   0 root         (0) root         (0)     5793 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/modules/layer/default/loading-0.gif
--rw-r--r--   0 root         (0) root         (0)      701 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/modules/layer/default/loading-1.gif
--rw-r--r--   0 root         (0) root         (0)     1787 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/css/modules/layer/default/loading-2.gif
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.762532 kk-0.9.3/kk/static/src/layui/font/
--rw-r--r--   0 root         (0) root         (0)    46684 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/font/iconfont.eot
--rw-r--r--   0 root         (0) root         (0)   305858 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/font/iconfont.svg
--rw-r--r--   0 root         (0) root         (0)    46508 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/font/iconfont.ttf
--rw-r--r--   0 root         (0) root         (0)    30628 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/font/iconfont.woff
--rw-r--r--   0 root         (0) root         (0)    25964 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/font/iconfont.woff2
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.746532 kk-0.9.3/kk/static/src/layui/lay/
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.766532 kk-0.9.3/kk/static/src/layui/lay/modules/
--rw-r--r--   0 root         (0) root         (0)     3863 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/carousel.js
--rw-r--r--   0 root         (0) root         (0)     1178 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/code.js
--rw-r--r--   0 root         (0) root         (0)    11740 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/colorpicker.js
--rw-r--r--   0 root         (0) root         (0)     7265 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/element.js
--rw-r--r--   0 root         (0) root         (0)     2027 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/flow.js
--rw-r--r--   0 root         (0) root         (0)     9464 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/form.js
--rw-r--r--   0 root         (0) root         (0)    97649 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/jquery.js
--rw-r--r--   0 root         (0) root         (0)    27378 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/laydate.js
--rw-r--r--   0 root         (0) root         (0)    12636 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/layedit.js
--rw-r--r--   0 root         (0) root         (0)    22042 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/layer.js
--rw-r--r--   0 root         (0) root         (0)     4473 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/laypage.js
--rw-r--r--   0 root         (0) root         (0)     1837 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/laytpl.js
--rw-r--r--   0 root         (0) root         (0)    53632 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/mobile.js
--rw-r--r--   0 root         (0) root         (0)     2754 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/rate.js
--rw-r--r--   0 root         (0) root         (0)     7050 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/slider.js
--rw-r--r--   0 root         (0) root         (0)    31564 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/table.js
--rw-r--r--   0 root         (0) root         (0)     6325 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/transfer.js
--rw-r--r--   0 root         (0) root         (0)    11545 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/tree.js
--rw-r--r--   0 root         (0) root         (0)     7467 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/upload.js
--rw-r--r--   0 root         (0) root         (0)     3837 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/lay/modules/util.js
--rw-r--r--   0 root         (0) root         (0)   278423 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/layui.all.js
--rw-r--r--   0 root         (0) root         (0)     7348 2022-07-14 13:13:22.000000 kk-0.9.3/kk/static/src/layui/layui.js
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.766532 kk-0.9.3/kk/templates/
--rw-r--r--   0 root         (0) root         (0)     3760 2022-07-14 13:13:22.000000 kk-0.9.3/kk/templates/admin.html
--rw-r--r--   0 root         (0) root         (0)     4262 2023-02-19 15:22:17.000000 kk-0.9.3/kk/templates/base.html
--rw-r--r--   0 root         (0) root         (0)     4032 2022-07-14 13:13:22.000000 kk-0.9.3/kk/templates/chart.html
--rw-r--r--   0 root         (0) root         (0)    13677 2023-06-19 02:26:08.000000 kk-0.9.3/kk/templates/index.html
--rw-r--r--   0 root         (0) root         (0)     1772 2022-07-14 13:13:22.000000 kk-0.9.3/kk/templates/manage.html
--rw-r--r--   0 root         (0) root         (0)     1461 2022-07-14 13:13:22.000000 kk-0.9.3/kk/templates/reset.html
--rw-r--r--   0 root         (0) root         (0)     2995 2022-07-14 13:13:22.000000 kk-0.9.3/kk/templates/search.html
--rw-r--r--   0 root         (0) root         (0)     1052 2022-07-14 13:13:22.000000 kk-0.9.3/kk/templates/signin.html
--rw-r--r--   0 root         (0) root         (0)     1849 2022-07-14 13:13:22.000000 kk-0.9.3/kk/templates/signup.html
--rw-r--r--   0 root         (0) root         (0)     5965 2022-07-14 13:13:22.000000 kk-0.9.3/kk/templates/table.html
-drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-19 02:28:53.746532 kk-0.9.3/kk.egg-info/
--rw-r--r--   0 root         (0) root         (0)      589 2023-06-19 02:28:53.000000 kk-0.9.3/kk.egg-info/PKG-INFO
--rw-r--r--   0 root         (0) root         (0)     4424 2023-06-19 02:28:53.000000 kk-0.9.3/kk.egg-info/SOURCES.txt
--rw-r--r--   0 root         (0) root         (0)        1 2023-06-19 02:28:53.000000 kk-0.9.3/kk.egg-info/dependency_links.txt
--rw-r--r--   0 root         (0) root         (0)       37 2023-06-19 02:28:53.000000 kk-0.9.3/kk.egg-info/entry_points.txt
--rw-r--r--   0 root         (0) root         (0)       24 2023-06-19 02:28:53.000000 kk-0.9.3/kk.egg-info/requires.txt
--rw-r--r--   0 root         (0) root         (0)        3 2023-06-19 02:28:53.000000 kk-0.9.3/kk.egg-info/top_level.txt
--rw-r--r--   0 root         (0) root         (0)       38 2023-06-19 02:28:53.766532 kk-0.9.3/setup.cfg
--rw-r--r--   0 root         (0) root         (0)     1319 2023-01-10 04:30:46.000000 kk-0.9.3/setup.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.965628 kk-0.9.4/
+-rw-r--r--   0 root         (0) root         (0)      589 2023-06-28 09:10:15.965628 kk-0.9.4/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     3203 2022-07-14 13:13:22.000000 kk-0.9.4/README.md
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.949629 kk-0.9.4/kk/
+-rw-r--r--   0 root         (0) root         (0)      129 2023-06-28 09:10:09.000000 kk-0.9.4/kk/__init__.py
+-rw-r--r--   0 root         (0) root         (0)    36753 2023-06-28 09:09:06.000000 kk-0.9.4/kk/handler.py
+-rwxr-xr-x   0 root         (0) root         (0)     4035 2022-07-14 13:13:22.000000 kk-0.9.4/kk/index.py
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.949629 kk-0.9.4/kk/static/
+-rw-r--r--   0 root         (0) root         (0)     4286 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/favicon.ico
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.953629 kk-0.9.4/kk/static/img/
+-rw-rw-r--   0 root         (0) root         (0)     3397 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/apk.png
+-rw-rw-r--   0 root         (0) root         (0)     3105 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/audio.png
+-rw-rw-r--   0 root         (0) root         (0)     4154 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/c.png
+-rw-rw-r--   0 root         (0) root         (0)     3638 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/cpp.png
+-rw-rw-r--   0 root         (0) root         (0)     5479 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/css.png
+-rw-rw-r--   0 root         (0) root         (0)     4934 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/database.png
+-rw-rw-r--   0 root         (0) root         (0)     3229 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/dmg.png
+-rw-rw-r--   0 root         (0) root         (0)     4321 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/docx.png
+-rw-rw-r--   0 root         (0) root         (0)     4436 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/exe.png
+-rw-rw-r--   0 root         (0) root         (0)     3409 2023-06-19 00:58:34.000000 kk-0.9.4/kk/static/img/file.png
+-rw-rw-r--   0 root         (0) root         (0)     1595 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/folder.png
+-rw-rw-r--   0 root         (0) root         (0)     6366 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/golang.png
+-rw-rw-r--   0 root         (0) root         (0)     3457 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/html.png
+-rw-rw-r--   0 root         (0) root         (0)     3494 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/image.png
+-rw-rw-r--   0 root         (0) root         (0)     5324 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/ini.png
+-rw-rw-r--   0 root         (0) root         (0)     5633 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/iso.png
+-rw-rw-r--   0 root         (0) root         (0)     5994 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/java.png
+-rw-rw-r--   0 root         (0) root         (0)     5472 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/javascript.png
+-rw-rw-r--   0 root         (0) root         (0)     4946 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/json.png
+-rw-rw-r--   0 root         (0) root         (0)    11198 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/kindle.png
+-rw-rw-r--   0 root         (0) root         (0)     3968 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/markdown.png
+-rw-rw-r--   0 root         (0) root         (0)     4285 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/pdf.png
+-rw-rw-r--   0 root         (0) root         (0)     3158 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/pptx.png
+-rw-rw-r--   0 root         (0) root         (0)     3859 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/python.png
+-rw-rw-r--   0 root         (0) root         (0)     2114 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/rar.png
+-rw-rw-r--   0 root         (0) root         (0)     1394 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/shell.png
+-rw-rw-r--   0 root         (0) root         (0)     3806 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/txt.png
+-rw-rw-r--   0 root         (0) root         (0)     2448 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/video.png
+-rw-rw-r--   0 root         (0) root         (0)     3623 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/vue.png
+-rw-rw-r--   0 root         (0) root         (0)     3406 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/xlsx.png
+-rw-r--r--   0 root         (0) root         (0)     3446 2023-06-19 01:39:13.000000 kk-0.9.4/kk/static/img/xml.png
+-rw-rw-r--   0 root         (0) root         (0)     4812 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/yaml.png
+-rw-rw-r--   0 root         (0) root         (0)     1930 2023-06-19 00:48:55.000000 kk-0.9.4/kk/static/img/zip.png
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.957629 kk-0.9.4/kk/static/img2/
+-rw-r--r--   0 root         (0) root         (0)     5153 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/apk.png
+-rw-r--r--   0 root         (0) root         (0)    17071 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/audio.png
+-rw-r--r--   0 root         (0) root         (0)     6382 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/c.png
+-rw-r--r--   0 root         (0) root         (0)     6673 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/cpp.png
+-rw-r--r--   0 root         (0) root         (0)     5635 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/css.png
+-rw-r--r--   0 root         (0) root         (0)    16755 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/database.png
+-rw-r--r--   0 root         (0) root         (0)     4006 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/dmg.png
+-rw-r--r--   0 root         (0) root         (0)     7904 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/docx.png
+-rw-r--r--   0 root         (0) root         (0)     2245 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/exe.png
+-rw-r--r--   0 root         (0) root         (0)     2822 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/file.png
+-rw-r--r--   0 root         (0) root         (0)     3688 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/folder.png
+-rw-r--r--   0 root         (0) root         (0)    12494 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/golang.png
+-rw-r--r--   0 root         (0) root         (0)     8140 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/html.png
+-rw-r--r--   0 root         (0) root         (0)     7301 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/image.png
+-rw-r--r--   0 root         (0) root         (0)     8962 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/ini.png
+-rw-r--r--   0 root         (0) root         (0)     7287 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/iso.png
+-rw-r--r--   0 root         (0) root         (0)    15616 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/java.png
+-rw-r--r--   0 root         (0) root         (0)    10518 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/javascript.png
+-rw-r--r--   0 root         (0) root         (0)     3847 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/json.png
+-rw-r--r--   0 root         (0) root         (0)     2997 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/kindle.png
+-rw-r--r--   0 root         (0) root         (0)     2901 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/markdown.png
+-rw-r--r--   0 root         (0) root         (0)    12717 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/pdf.png
+-rw-r--r--   0 root         (0) root         (0)    12577 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/php.png
+-rw-r--r--   0 root         (0) root         (0)     3574 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/pptx.png
+-rw-r--r--   0 root         (0) root         (0)     9024 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/python.png
+-rw-r--r--   0 root         (0) root         (0)     7434 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/shell.png
+-rw-r--r--   0 root         (0) root         (0)     2901 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/txt.png
+-rw-r--r--   0 root         (0) root         (0)    15897 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/video.png
+-rw-r--r--   0 root         (0) root         (0)    13413 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/vue.png
+-rw-r--r--   0 root         (0) root         (0)     8139 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/xlsx.png
+-rw-r--r--   0 root         (0) root         (0)     3449 2023-06-19 02:22:37.000000 kk-0.9.4/kk/static/img2/xml.png
+-rw-r--r--   0 root         (0) root         (0)    11355 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/yaml.png
+-rw-r--r--   0 root         (0) root         (0)     3509 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/img2/zip.png
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.945629 kk-0.9.4/kk/static/src/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.957629 kk-0.9.4/kk/static/src/css/
+-rw-r--r--   0 root         (0) root         (0)    45250 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/css/DPlayer.min.css
+-rw-r--r--   0 root         (0) root         (0)     5254 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/css/iconfont.css
+-rw-r--r--   0 root         (0) root         (0)     5572 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/css/iconfont.eot
+-rw-r--r--   0 root         (0) root         (0)    15798 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/css/iconfont.svg
+-rw-r--r--   0 root         (0) root         (0)     5404 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/css/iconfont.ttf
+-rw-r--r--   0 root         (0) root         (0)     3536 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/css/iconfont.woff
+-rw-r--r--   0 root         (0) root         (0)     2904 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/css/iconfont.woff2
+-rw-r--r--   0 root         (0) root         (0)     3584 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/css/markdown.css
+-rw-r--r--   0 root         (0) root         (0)     2477 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/css/monokai_sublime.css
+-rw-r--r--   0 root         (0) root         (0)     9750 2023-06-19 02:23:34.000000 kk-0.9.4/kk/static/src/css/style.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.957629 kk-0.9.4/kk/static/src/js/
+-rw-r--r--   0 root         (0) root         (0)   116781 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/DPlayer.min.js
+-rw-r--r--   0 root         (0) root         (0)    10453 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/clipboard.min.js
+-rw-r--r--   0 root         (0) root         (0)   173418 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/flv.min.js
+-rw-r--r--   0 root         (0) root         (0)    80655 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/highcharts-more.js
+-rw-r--r--   0 root         (0) root         (0)   254576 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/highcharts.js
+-rw-r--r--   0 root         (0) root         (0)   749330 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/highlight.pack.min.js
+-rw-r--r--   0 root         (0) root         (0)   231552 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/hls.min.js
+-rw-r--r--   0 root         (0) root         (0)     5595 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/imagesloaded.pkgd.min.js
+-rw-r--r--   0 root         (0) root         (0)    88145 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/jquery.min.js
+-rw-r--r--   0 root         (0) root         (0)    24104 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/masonry.pkgd.min.js
+-rw-r--r--   0 root         (0) root         (0)    20032 2023-06-21 03:28:51.000000 kk-0.9.4/kk/static/src/js/page.js
+-rw-r--r--   0 root         (0) root         (0)     2221 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/utils.js
+-rw-r--r--   0 root         (0) root         (0)    70754 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/js/webuploader.nolog.min.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.957629 kk-0.9.4/kk/static/src/layui/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.957629 kk-0.9.4/kk/static/src/layui/css/
+-rw-r--r--   0 root         (0) root         (0)    74304 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/layui.css
+-rw-r--r--   0 root         (0) root         (0)     9886 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/layui.mobile.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.961629 kk-0.9.4/kk/static/src/layui/css/modules/
+-rw-r--r--   0 root         (0) root         (0)     1064 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/modules/code.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.945629 kk-0.9.4/kk/static/src/layui/css/modules/laydate/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.961629 kk-0.9.4/kk/static/src/layui/css/modules/laydate/default/
+-rw-r--r--   0 root         (0) root         (0)     7538 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/modules/laydate/default/laydate.css
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.949629 kk-0.9.4/kk/static/src/layui/css/modules/layer/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.961629 kk-0.9.4/kk/static/src/layui/css/modules/layer/default/
+-rw-r--r--   0 root         (0) root         (0)     5911 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/modules/layer/default/icon-ext.png
+-rw-r--r--   0 root         (0) root         (0)    11493 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/modules/layer/default/icon.png
+-rw-r--r--   0 root         (0) root         (0)    14426 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/modules/layer/default/layer.css
+-rw-r--r--   0 root         (0) root         (0)     5793 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/modules/layer/default/loading-0.gif
+-rw-r--r--   0 root         (0) root         (0)      701 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/modules/layer/default/loading-1.gif
+-rw-r--r--   0 root         (0) root         (0)     1787 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/css/modules/layer/default/loading-2.gif
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.961629 kk-0.9.4/kk/static/src/layui/font/
+-rw-r--r--   0 root         (0) root         (0)    46684 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/font/iconfont.eot
+-rw-r--r--   0 root         (0) root         (0)   305858 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/font/iconfont.svg
+-rw-r--r--   0 root         (0) root         (0)    46508 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/font/iconfont.ttf
+-rw-r--r--   0 root         (0) root         (0)    30628 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/font/iconfont.woff
+-rw-r--r--   0 root         (0) root         (0)    25964 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/font/iconfont.woff2
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.949629 kk-0.9.4/kk/static/src/layui/lay/
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.961629 kk-0.9.4/kk/static/src/layui/lay/modules/
+-rw-r--r--   0 root         (0) root         (0)     3863 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/carousel.js
+-rw-r--r--   0 root         (0) root         (0)     1178 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/code.js
+-rw-r--r--   0 root         (0) root         (0)    11740 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/colorpicker.js
+-rw-r--r--   0 root         (0) root         (0)     7265 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/element.js
+-rw-r--r--   0 root         (0) root         (0)     2027 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/flow.js
+-rw-r--r--   0 root         (0) root         (0)     9464 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/form.js
+-rw-r--r--   0 root         (0) root         (0)    97649 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/jquery.js
+-rw-r--r--   0 root         (0) root         (0)    27378 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/laydate.js
+-rw-r--r--   0 root         (0) root         (0)    12636 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/layedit.js
+-rw-r--r--   0 root         (0) root         (0)    22042 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/layer.js
+-rw-r--r--   0 root         (0) root         (0)     4473 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/laypage.js
+-rw-r--r--   0 root         (0) root         (0)     1837 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/laytpl.js
+-rw-r--r--   0 root         (0) root         (0)    53632 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/mobile.js
+-rw-r--r--   0 root         (0) root         (0)     2754 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/rate.js
+-rw-r--r--   0 root         (0) root         (0)     7050 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/slider.js
+-rw-r--r--   0 root         (0) root         (0)    31564 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/table.js
+-rw-r--r--   0 root         (0) root         (0)     6325 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/transfer.js
+-rw-r--r--   0 root         (0) root         (0)    11545 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/tree.js
+-rw-r--r--   0 root         (0) root         (0)     7467 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/upload.js
+-rw-r--r--   0 root         (0) root         (0)     3837 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/lay/modules/util.js
+-rw-r--r--   0 root         (0) root         (0)   278423 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/layui.all.js
+-rw-r--r--   0 root         (0) root         (0)     7348 2022-07-14 13:13:22.000000 kk-0.9.4/kk/static/src/layui/layui.js
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.965628 kk-0.9.4/kk/templates/
+-rw-r--r--   0 root         (0) root         (0)     3760 2022-07-14 13:13:22.000000 kk-0.9.4/kk/templates/admin.html
+-rw-r--r--   0 root         (0) root         (0)     4262 2023-02-19 15:22:17.000000 kk-0.9.4/kk/templates/base.html
+-rw-r--r--   0 root         (0) root         (0)     4032 2022-07-14 13:13:22.000000 kk-0.9.4/kk/templates/chart.html
+-rw-r--r--   0 root         (0) root         (0)    13923 2023-06-21 03:24:29.000000 kk-0.9.4/kk/templates/index.html
+-rw-r--r--   0 root         (0) root         (0)     1772 2022-07-14 13:13:22.000000 kk-0.9.4/kk/templates/manage.html
+-rw-r--r--   0 root         (0) root         (0)     1461 2022-07-14 13:13:22.000000 kk-0.9.4/kk/templates/reset.html
+-rw-r--r--   0 root         (0) root         (0)     2995 2022-07-14 13:13:22.000000 kk-0.9.4/kk/templates/search.html
+-rw-r--r--   0 root         (0) root         (0)     1052 2022-07-14 13:13:22.000000 kk-0.9.4/kk/templates/signin.html
+-rw-r--r--   0 root         (0) root         (0)     1849 2022-07-14 13:13:22.000000 kk-0.9.4/kk/templates/signup.html
+-rw-r--r--   0 root         (0) root         (0)     5965 2022-07-14 13:13:22.000000 kk-0.9.4/kk/templates/table.html
+drwxr-xr-x   0 root         (0) root         (0)        0 2023-06-28 09:10:15.949629 kk-0.9.4/kk.egg-info/
+-rw-r--r--   0 root         (0) root         (0)      589 2023-06-28 09:10:15.000000 kk-0.9.4/kk.egg-info/PKG-INFO
+-rw-r--r--   0 root         (0) root         (0)     4424 2023-06-28 09:10:15.000000 kk-0.9.4/kk.egg-info/SOURCES.txt
+-rw-r--r--   0 root         (0) root         (0)        1 2023-06-28 09:10:15.000000 kk-0.9.4/kk.egg-info/dependency_links.txt
+-rw-r--r--   0 root         (0) root         (0)       37 2023-06-28 09:10:15.000000 kk-0.9.4/kk.egg-info/entry_points.txt
+-rw-r--r--   0 root         (0) root         (0)       24 2023-06-28 09:10:15.000000 kk-0.9.4/kk.egg-info/requires.txt
+-rw-r--r--   0 root         (0) root         (0)        3 2023-06-28 09:10:15.000000 kk-0.9.4/kk.egg-info/top_level.txt
+-rw-r--r--   0 root         (0) root         (0)       38 2023-06-28 09:10:15.965628 kk-0.9.4/setup.cfg
+-rw-r--r--   0 root         (0) root         (0)     1319 2023-01-10 04:30:46.000000 kk-0.9.4/setup.py
```

### Comparing `kk-0.9.3/PKG-INFO` & `kk-0.9.4/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kk
-Version: 0.9.3
+Version: 0.9.4
 Summary: a simple file server
 Home-page: https://github.com/zkdfbb/kk
 Author: digua
 Author-email: zkdfbb@qq.com
 License: GPL
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Developers
```

### Comparing `kk-0.9.3/README.md` & `kk-0.9.4/README.md`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/handler.py` & `kk-0.9.4/kk/handler.py`

 * *Files 4% similar despite different names*

```diff
@@ -230,14 +230,20 @@
         tornado.web.StaticFileHandler.__init__(self, application, request, path=self.app.root)
         BaseHandler.__init__(self, application, request, path=self.app.root)
 
     def compute_etag(self):
         if hasattr(self, 'absolute_path'):
             return super().compute_etag()
 
+    def set_extra_headers(self, path):
+        if path.endswith('.webp'):
+            self.set_header('content-type', 'image/webp')
+        elif path.endswith('.ts'):
+            self.set_header('content-type', 'application/octet-stream')
+
     async def prepare(self):
         path = self.root / self.request.path[6:]
         if self.request.method in ['POST'] and path in self.cache:
             self.cache.pop(path)
         elif self.request.method in ['PUT', 'DELETE', 'HEAD'] and path.parent in self.cache:
             self.cache.pop(path.parent)
 
@@ -333,27 +339,21 @@
         return nodes
 
     async def get_info(self, name):
         info = Dict()
         if self.app.options.auth and not name.startswith('public'):
             doc = await self.db.share.find_one({'name': name, 'token': self.current_user.token})
             info.share = True if doc else False
-        if self.current_user.admin:
-            doc = await self.db.files.find_one({'name': name})
         return info
 
     def set_default_headers(self):
         self.set_header('Cache-Control', 'no-cache, no-store, must-revalidate')
         self.set_header('Pragma', 'no-cache')
         self.set_header('Expires', '0')
 
-    def set_extra_headers(self, path):
-        if path.endswith('.ts'):
-            self.set_header('Content-Type', 'application/octet-stream')
-
     def preview_html(self, html, padding=0, background='#23241f'):
         lines = [
             '<html><head>',
             '<link rel="stylesheet" href="/static/src/css/monokai_sublime.css">',
             '<style>img{margin:10px auto;max-width:100%}</style>',
             f'</head><body style="padding:{padding}px;margin:0;background:{background};">',
             html,
@@ -432,64 +432,55 @@
                 'is_dir': item.isdir(),
             }))
         self.render('index.html', entries=entries, absolute=True)
 
     async def check(self, name):
         if not self.app.options.auth or self.current_user.admin:
             return True
-        key = name.split('/')[0]
-        if key == str(self.current_user.id):
+        uid = name.split('/')[0]
+        if uid == str(self.current_user.id):
             return True
         if self.request.method not in ['GET', 'HEAD']:
             return False
-        if key == 'public':
+        if uid == 'public':
             return True
-        if not key.isdigit():
+        if not uid.isdigit():
             return False
-        user = await self.db.users.find_one({'id': int(key)})
+        user = await self.db.users.find_one({'id': int(uid)})
         if user and user.public:
             return True
         if not self.args.key:
             return False
         doc = await self.db.share.find_one({'_id': ObjectId(self.args.key)})
         if not doc:
             return False
         if doc.expired_at and doc.expired_at < datetime.datetime.now():
             return await self.db.share.delete_one({'_id': doc._id})
         return name.startswith(doc.path)
 
-    async def send(self, name, include_body=True):
-        if include_body and self.app.options.auth:
-            doc = await self.db.files.find_one({'name': name})
-            if doc:
-                return self.redirect(doc.url)
-        await super().get(name, include_body)
-
     @check_auth
     async def get(self, name, include_body=True):
         path = self.root / name
         if self.args.q:
             entries = await self.search(name)
             self.render('index.html', entries=entries, absolute=True)
         elif self.args.f == 'tree':
             nodes = self.get_nodes(path)
             self.finish({'nodes': nodes})
         elif self.args.f == 'info':
             info = await self.get_info(name)
             self.finish(info)
-        elif self.request.path.startswith('/download') or self.args.f == 'download' or re.match('wget|curl', self.ua.lower()):
+        elif self.request.path.startswith('/download'):
             self.set_header('Content-Type', 'application/octet-stream')
             zh = re.compile('[\u4e00-\u9fa5]+')
-            if zh.search(path.name):
-                filename = urllib.parse.quote(path.name.encode('UTF-8'))
-            else:
-                filename = urllib.parse.quote(path.name)
+            name = path.name.encode('UTF-8') if zh.search(path.name) else path.name
+            filename = urllib.parse.quote(name)
             if path.is_file():
                 self.set_header('Content-Disposition', f'attachment;filename={filename}')
-                await self.send(name, include_body)
+                await super().get(name, include_body)
             elif path.is_dir():
                 await self.download(path)
             else:
                 raise tornado.web.HTTPError(404)
         elif path.is_file() and self.args.f == 'preview':
             suffix = path.suffix.lower()[1:]
             if suffix == 'zip':
@@ -529,23 +520,26 @@
                 }.get(suffix, suffix)
                 try:
                     text = path.read_text()
                 except:
                     text = path.read_text(encoding='unicode_escape')
                 self.preview_html(f'<pre><code class="{code}">{ tornado.escape.xhtml_escape(text) }</code></pre>')
             elif re.match('(jpeg|jpg|png|gif|bmp|webp|svg|tif|webp|ai|ico|exif|pdf|xml)$', suffix):
-                if suffix.find('webp') >= 0:
-                    self.set_header('content-type', 'image/webp')
-                await self.send(name, include_body)
+                await super().get(name, include_body)
             else:
                 self.finish('该格式不支持预览')
         elif path.is_file():
-            await self.send(name, include_body)
+            await super().get(name, include_body)
         else:
             entries = await self.listdir(path)
+            if self.app.options.auth:
+                cursor = self.db.share.find({'path': {'$in': [str(x.path) for x in entries]}}, {'path': 1})
+                docs = {Path(x.path): True async for x in cursor}
+                for entry in entries:
+                    entry.share = docs.get(entry.path, False)
             self.render('index.html', entries=entries, absolute=False)
 
     async def merge(self, path):
         dirname = Path(f'/tmp/upload/{self.args.guid}-{self.args.id}')
         filename = path / urllib.parse.unquote(self.args.name)
         filename.parent.mkdir(parents=True, exist_ok=True)
         chunks = int(list(dirname.glob("*"))[0].name.split('_')[0])
```

### Comparing `kk-0.9.3/kk/index.py` & `kk-0.9.4/kk/index.py`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/favicon.ico` & `kk-0.9.4/kk/static/favicon.ico`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/apk.png` & `kk-0.9.4/kk/static/img/apk.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/audio.png` & `kk-0.9.4/kk/static/img/audio.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/c.png` & `kk-0.9.4/kk/static/img/c.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/cpp.png` & `kk-0.9.4/kk/static/img/cpp.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/css.png` & `kk-0.9.4/kk/static/img/css.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/database.png` & `kk-0.9.4/kk/static/img/database.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/dmg.png` & `kk-0.9.4/kk/static/img/dmg.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/docx.png` & `kk-0.9.4/kk/static/img/docx.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/exe.png` & `kk-0.9.4/kk/static/img/exe.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/file.png` & `kk-0.9.4/kk/static/img/file.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/folder.png` & `kk-0.9.4/kk/static/img/folder.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/golang.png` & `kk-0.9.4/kk/static/img/golang.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/html.png` & `kk-0.9.4/kk/static/img/html.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/image.png` & `kk-0.9.4/kk/static/img/image.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/ini.png` & `kk-0.9.4/kk/static/img/ini.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/iso.png` & `kk-0.9.4/kk/static/img/iso.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/java.png` & `kk-0.9.4/kk/static/img/java.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/javascript.png` & `kk-0.9.4/kk/static/img/javascript.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/json.png` & `kk-0.9.4/kk/static/img/json.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/kindle.png` & `kk-0.9.4/kk/static/img/kindle.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/markdown.png` & `kk-0.9.4/kk/static/img/markdown.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/pdf.png` & `kk-0.9.4/kk/static/img/pdf.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/pptx.png` & `kk-0.9.4/kk/static/img/pptx.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/python.png` & `kk-0.9.4/kk/static/img/python.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/rar.png` & `kk-0.9.4/kk/static/img/rar.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/shell.png` & `kk-0.9.4/kk/static/img/shell.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/txt.png` & `kk-0.9.4/kk/static/img/txt.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/video.png` & `kk-0.9.4/kk/static/img/video.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/vue.png` & `kk-0.9.4/kk/static/img/vue.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/xlsx.png` & `kk-0.9.4/kk/static/img/xlsx.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/xml.png` & `kk-0.9.4/kk/static/img/xml.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/yaml.png` & `kk-0.9.4/kk/static/img/yaml.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img/zip.png` & `kk-0.9.4/kk/static/img/zip.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/apk.png` & `kk-0.9.4/kk/static/img2/apk.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/audio.png` & `kk-0.9.4/kk/static/img2/audio.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/c.png` & `kk-0.9.4/kk/static/img2/c.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/cpp.png` & `kk-0.9.4/kk/static/img2/cpp.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/css.png` & `kk-0.9.4/kk/static/img2/css.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/database.png` & `kk-0.9.4/kk/static/img2/database.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/dmg.png` & `kk-0.9.4/kk/static/img2/dmg.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/docx.png` & `kk-0.9.4/kk/static/img2/docx.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/exe.png` & `kk-0.9.4/kk/static/img2/exe.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/file.png` & `kk-0.9.4/kk/static/img2/file.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/folder.png` & `kk-0.9.4/kk/static/img2/folder.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/golang.png` & `kk-0.9.4/kk/static/img2/golang.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/html.png` & `kk-0.9.4/kk/static/img2/html.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/image.png` & `kk-0.9.4/kk/static/img2/image.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/ini.png` & `kk-0.9.4/kk/static/img2/ini.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/iso.png` & `kk-0.9.4/kk/static/img2/iso.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/java.png` & `kk-0.9.4/kk/static/img2/java.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/javascript.png` & `kk-0.9.4/kk/static/img2/javascript.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/json.png` & `kk-0.9.4/kk/static/img2/json.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/kindle.png` & `kk-0.9.4/kk/static/img2/kindle.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/markdown.png` & `kk-0.9.4/kk/static/img2/markdown.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/pdf.png` & `kk-0.9.4/kk/static/img2/pdf.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/php.png` & `kk-0.9.4/kk/static/img2/php.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/pptx.png` & `kk-0.9.4/kk/static/img2/pptx.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/python.png` & `kk-0.9.4/kk/static/img2/python.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/shell.png` & `kk-0.9.4/kk/static/img2/shell.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/txt.png` & `kk-0.9.4/kk/static/img2/txt.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/video.png` & `kk-0.9.4/kk/static/img2/video.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/vue.png` & `kk-0.9.4/kk/static/img2/vue.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/xlsx.png` & `kk-0.9.4/kk/static/img2/xlsx.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/xml.png` & `kk-0.9.4/kk/static/img2/xml.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/yaml.png` & `kk-0.9.4/kk/static/img2/yaml.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/img2/zip.png` & `kk-0.9.4/kk/static/img2/zip.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/DPlayer.min.css` & `kk-0.9.4/kk/static/src/css/DPlayer.min.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/iconfont.css` & `kk-0.9.4/kk/static/src/css/iconfont.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/iconfont.eot` & `kk-0.9.4/kk/static/src/css/iconfont.eot`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/iconfont.svg` & `kk-0.9.4/kk/static/src/css/iconfont.svg`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/iconfont.ttf` & `kk-0.9.4/kk/static/src/css/iconfont.ttf`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/iconfont.woff` & `kk-0.9.4/kk/static/src/css/iconfont.woff`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/iconfont.woff2` & `kk-0.9.4/kk/static/src/css/iconfont.woff2`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/markdown.css` & `kk-0.9.4/kk/static/src/css/markdown.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/monokai_sublime.css` & `kk-0.9.4/kk/static/src/css/monokai_sublime.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/css/style.css` & `kk-0.9.4/kk/static/src/css/style.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/DPlayer.min.js` & `kk-0.9.4/kk/static/src/js/DPlayer.min.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/clipboard.min.js` & `kk-0.9.4/kk/static/src/js/clipboard.min.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/flv.min.js` & `kk-0.9.4/kk/static/src/js/flv.min.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/highcharts-more.js` & `kk-0.9.4/kk/static/src/js/highcharts-more.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/highcharts.js` & `kk-0.9.4/kk/static/src/js/highcharts.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/highlight.pack.min.js` & `kk-0.9.4/kk/static/src/js/highlight.pack.min.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/hls.min.js` & `kk-0.9.4/kk/static/src/js/hls.min.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/imagesloaded.pkgd.min.js` & `kk-0.9.4/kk/static/src/js/imagesloaded.pkgd.min.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/jquery.min.js` & `kk-0.9.4/kk/static/src/js/jquery.min.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/masonry.pkgd.min.js` & `kk-0.9.4/kk/static/src/js/masonry.pkgd.min.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/page.js` & `kk-0.9.4/kk/static/src/js/page.js`

 * *Files 1% similar despite different names*

#### js-beautify {}

```diff
@@ -399,15 +399,17 @@
                 title: name,
                 content: url,
                 shadeClose: true,
                 area: ['1000px', '700px'],
                 success: function(layero, index) {
                     var css = {
                         "display": "block",
-                        "max-width": "100%"
+                        "max-width": "100%",
+                        "max-height": "100%",
+                        "margin": "0 auto"
                     };
                     $($("iframe").contents().find("body")).children("img:first").css(css);
                 }
             })
         })
 
         $(document).on("click", ".btn-link", function() {
```

### Comparing `kk-0.9.3/kk/static/src/js/utils.js` & `kk-0.9.4/kk/static/src/js/utils.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/js/webuploader.nolog.min.js` & `kk-0.9.4/kk/static/src/js/webuploader.nolog.min.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/layui.css` & `kk-0.9.4/kk/static/src/layui/css/layui.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/layui.mobile.css` & `kk-0.9.4/kk/static/src/layui/css/layui.mobile.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/modules/code.css` & `kk-0.9.4/kk/static/src/layui/css/modules/code.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/modules/laydate/default/laydate.css` & `kk-0.9.4/kk/static/src/layui/css/modules/laydate/default/laydate.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/modules/layer/default/icon-ext.png` & `kk-0.9.4/kk/static/src/layui/css/modules/layer/default/icon-ext.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/modules/layer/default/icon.png` & `kk-0.9.4/kk/static/src/layui/css/modules/layer/default/icon.png`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/modules/layer/default/layer.css` & `kk-0.9.4/kk/static/src/layui/css/modules/layer/default/layer.css`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/modules/layer/default/loading-0.gif` & `kk-0.9.4/kk/static/src/layui/css/modules/layer/default/loading-0.gif`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/modules/layer/default/loading-1.gif` & `kk-0.9.4/kk/static/src/layui/css/modules/layer/default/loading-1.gif`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/css/modules/layer/default/loading-2.gif` & `kk-0.9.4/kk/static/src/layui/css/modules/layer/default/loading-2.gif`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/font/iconfont.eot` & `kk-0.9.4/kk/static/src/layui/font/iconfont.eot`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/font/iconfont.svg` & `kk-0.9.4/kk/static/src/layui/font/iconfont.svg`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/font/iconfont.ttf` & `kk-0.9.4/kk/static/src/layui/font/iconfont.ttf`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/font/iconfont.woff` & `kk-0.9.4/kk/static/src/layui/font/iconfont.woff`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/font/iconfont.woff2` & `kk-0.9.4/kk/static/src/layui/font/iconfont.woff2`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/carousel.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/carousel.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/code.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/code.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/colorpicker.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/colorpicker.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/element.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/element.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/flow.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/flow.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/form.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/form.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/jquery.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/jquery.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/laydate.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/laydate.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/layedit.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/layedit.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/layer.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/layer.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/laypage.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/laypage.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/laytpl.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/laytpl.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/mobile.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/mobile.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/rate.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/rate.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/slider.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/slider.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/table.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/table.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/transfer.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/transfer.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/tree.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/tree.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/upload.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/upload.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/lay/modules/util.js` & `kk-0.9.4/kk/static/src/layui/lay/modules/util.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/layui.all.js` & `kk-0.9.4/kk/static/src/layui/layui.all.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/static/src/layui/layui.js` & `kk-0.9.4/kk/static/src/layui/layui.js`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/templates/admin.html` & `kk-0.9.4/kk/templates/admin.html`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/templates/base.html` & `kk-0.9.4/kk/templates/base.html`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/templates/chart.html` & `kk-0.9.4/kk/templates/chart.html`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/templates/index.html` & `kk-0.9.4/kk/templates/index.html`

 * *Files 2% similar despite different names*

```diff
@@ -124,15 +124,15 @@
         </tr>
       </thead>
       <tbody>
         {% for doc in entries %}
         <tr>
           <td class="btn-select" style="text-align:left !important">
             {% if not handler.get_cookie('preview') and doc.path.suffix.lower() in ['.jpg', '.jpeg', '.png', '.bmp', '.gif', '.webp'] %}
-            <img style="display:block" src="/disk/{{ doc.path }}{% if doc.key or handler.args.key %}?key={{ doc.key or handler.args.key }}{% end %}" {% if handler.args.w %}width="{{ int(handler.args.w) }}"{% end %} {% if handler.args.h %}height="{{ int(handler.args.h) }}"{% end %}>
+            <a href="/disk/{{ doc.path }}{% if doc.key or handler.args.key %}?key={{ doc.key or handler.args.key }}{% end %}"><img style="display:block" src="/disk/{{ doc.path }}{% if doc.key or handler.args.key %}?key={{ doc.key or handler.args.key }}{% end %}" {% if handler.args.w %}width="{{ int(handler.args.w) }}"{% end %} {% if handler.args.h %}height="{{ int(handler.args.h) }}"{% end %}></a>
             {% elif not handler.get_cookie('preview') and doc.path.suffix.lower() in ['.mp3', '.amr', '.ogg', '.wav'] %}
             <audio style="display:block" controls="controls" ><source src="/disk/{{ doc.path }}{% if doc.key or handler.args.key %}?key={{ doc.key or handler.args.key }}{% end %}"></audio>
             {% elif not handler.get_cookie('preview') and doc.path.suffix.lower() in ['.mp4', 'mkv'] %}
             <video style="display:block" controls="controls"><source src="/disk/{{ doc.path }}{% if doc.key or handler.args.key %}?key={{ doc.key or handler.args.key }}{% end %}"></video>
             {% else %}
             {% set icon = 'folder.png' if doc.is_dir else handler.icon.get(doc.path.suffix.lower(), 'file.png') %}
             <img class="icon" src="{{ static_url(f'img/{icon}') }}" {% if icon in ['folder.png'] %}style="width:22px;height:22px"{% elif icon in ['pdf.png', 'audio.png', 'excel.png'] %}style="width:18px;height:18px"{% end %}>
@@ -165,24 +165,27 @@
             </button>
             {% elif handler.app.options.auth %}
             <ul class="layui-nav layui-btn-menu layui-btn-radius layui-btn-primary layui-btn-xs">
               <li class="layui-nav-item">
                 <a class="btn-menu" href="javascript:;"><i class="layui-icon layui-icon-more"></i></a>
                 <dl class="layui-nav-child">
                   <dd><a href="javascript:;" class="btn-rename">重命名</a></dd>
-                  <dd><a href="javascript:;" class="btn-move">移动至</a></dd>
+                  {# <dd><a href="javascript:;" class="btn-move">移动至</a></dd> #}
                   <dd><a href="javascript:;" class="btn-info" data-md5="{{ doc.md5 or '' }}">文件信息</a></dd>
-                  {% if re.match('.(pdf|txt|mobi|azw|doc|docx|html|htm|rtf|jpeg|jpg|png|gif|bmp|webp)$', doc.path.suffix.lower()) %}
+                  {% if current_user.kindle and re.match('.(pdf|txt|mobi|azw|doc|docx|html|htm|rtf|jpeg|jpg|png|gif|bmp|webp)$', doc.path.suffix.lower()) %}
                   <dd><a href="javascript:;" text="正在推送" action="kindle" class="btn-action">推送至Kindle</a></dd>
                   {% end %}
                   {% if not handler.request.path.startswith('/disk/public') %}
                   <dd><a href="javascript:;" action="public" class="btn-action user-admin layui-hide">公共文件</a></dd>
+                  {% if not doc.share %}
                   <dd><a href="javascript:;" action="share" class="btn-share">分享文件</a></dd>
+                  {% else %}
                   <dd><a href="javascript:;" action="unshare" class="btn-action">取消分享</a></dd>
                   {% end %}
+                  {% end %}
                 </dl>
               </li>
             </ul>
             {% end %}
           </td>
           <td class="pc btn-select" style="width:140px">{{ handler.convert_time(doc.mtime) }}</td>
           <td class="pc btn-select" style="width:70px">{{ handler.convert_size(doc.size) }}</td>
```

#### html2text {}

```diff
@@ -35,18 +35,18 @@
 {% else %}
 æä»¶å{%_if_handler.args.sort_in_[None,_'name']_and_handler.args.order_in_[è¿ææ�æä»¶æä½         ä¿®æ¹æ¶é´{%_if_handler.args.sort_==_'time'_and_handler.args.order_==_1_%}{æä»¶å¤§å°{%_if_handler.args.sort_==_'size'_and_handler.args.order_==_1_%}{%_elif
 %}{%_elif_handler.args.sort_==_'name'_and_handler.args.order_==_-_1_%}{%_end_%}                                                        handler.args.sort_==_'time'_and_handler.args.order_==_-_1_%}{%_end_%}                    handler.args.sort_==_'size'_and_handler.args.order_==_-_1_%}{%_end_%}
                                                                                                              {% if
 {% if not handler.get_cookie('preview') and doc.path.suffix.lower() in ['.jpg',                       handler.app.options.delete and
 '.jpeg', '.png', '.bmp', '.gif', '.webp'] %}                                                          not
 % if handler.args.w %}width="{{ int(handler.args.w) }}"{% end %} {% if handler.args.h                 (handler.request.path.startswith
-%}height="{{ int(handler.args.h) }}"{% end %}> {% elif not handler.get_cookie          {              ('/disk/public') and not
-('preview') and doc.path.suffix.lower() in ['.mp3', '.amr', '.ogg', '.wav'] %}  {%     {              current_user.admin)%}    {% end
-elif not handler.get_cookie('preview') and doc.path.suffix.lower() in ['.mp4', 'mkv']  doc.expired_at %} {% if                         {{ handler.convert_time(doc.mtime) }}                                                    {{ handler.convert_size(doc.size) }}
-%}  {% else %} {% set icon = 'folder.png' if doc.is_dir else handler.icon.get          or '' }}       (handler.app.options.auth and
-(doc.path.suffix.lower(), 'file.png') %}                                                              handler.request.path.startswith
+%}height="{{ int(handler.args.h) }}"{% end %}>                                         {              ('/disk/public') and not
+ {% elif not handler.get_cookie('preview') and doc.path.suffix.lower() in ['.mp3',     {              current_user.admin)%}    {% end
+'.amr', '.ogg', '.wav'] %}  {% elif not handler.get_cookie('preview') and              doc.expired_at %} {% if                         {{ handler.convert_time(doc.mtime) }}                                                    {{ handler.convert_size(doc.size) }}
+doc.path.suffix.lower() in ['.mp4', 'mkv'] %}  {% else %} {% set icon = 'folder.png'   or '' }}       (handler.app.options.auth and
+if doc.is_dir else handler.icon.get(doc.path.suffix.lower(), 'file.png') %}                           handler.request.path.startswith
 % if icon in ['folder.png'] %}style="width:22px;height:22px"{% elif icon in                           ('/disk/public') and not
 ['pdf.png', 'audio.png', 'excel.png'] %}style="width:18px;height:18px"{% end %}> {%                   current_user.admin) %}    {%
 end %} {%_if_absolute_%}{{_doc.path_}}{%_else_%}{{_doc.path.name_}}{%_end_%}                          elif handler.app.options.auth %}
                                                                                                       {% end %}
 {% end %}
 {% end %}
```

### Comparing `kk-0.9.3/kk/templates/manage.html` & `kk-0.9.4/kk/templates/manage.html`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/templates/reset.html` & `kk-0.9.4/kk/templates/reset.html`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/templates/search.html` & `kk-0.9.4/kk/templates/search.html`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/templates/signin.html` & `kk-0.9.4/kk/templates/signin.html`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/templates/signup.html` & `kk-0.9.4/kk/templates/signup.html`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk/templates/table.html` & `kk-0.9.4/kk/templates/table.html`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/kk.egg-info/PKG-INFO` & `kk-0.9.4/kk.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: kk
-Version: 0.9.3
+Version: 0.9.4
 Summary: a simple file server
 Home-page: https://github.com/zkdfbb/kk
 Author: digua
 Author-email: zkdfbb@qq.com
 License: GPL
 Classifier: Development Status :: 4 - Beta
 Classifier: Intended Audience :: Developers
```

### Comparing `kk-0.9.3/kk.egg-info/SOURCES.txt` & `kk-0.9.4/kk.egg-info/SOURCES.txt`

 * *Files identical despite different names*

### Comparing `kk-0.9.3/setup.py` & `kk-0.9.4/setup.py`

 * *Files identical despite different names*


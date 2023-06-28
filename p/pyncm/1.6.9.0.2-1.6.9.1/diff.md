# Comparing `tmp/pyncm-1.6.9.0.2.tar.gz` & `tmp/pyncm-1.6.9.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "pyncm-1.6.9.0.2.tar", last modified: Sat Jun 24 10:58:22 2023, max compression
+gzip compressed data, was "pyncm-1.6.9.1.tar", last modified: Wed Jun 28 10:49:41 2023, max compression
```

## Comparing `pyncm-1.6.9.0.2.tar` & `pyncm-1.6.9.1.tar`

### file list

```diff
@@ -1,48 +1,49 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:58:22.163691 pyncm-1.6.9.0.2/
--rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     6916 2023-06-24 10:58:22.163691 pyncm-1.6.9.0.2/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     6432 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:58:22.159691 pyncm-1.6.9.0.2/demos/
--rw-r--r--   0 runner    (1001) docker     (123)     1219 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/demos/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1074 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/demos/二维码登录.py
--rw-r--r--   0 runner    (1001) docker     (123)     1915 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/demos/云盘上传.py
--rw-r--r--   0 runner    (1001) docker     (123)     1665 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/demos/手机登录.py
--rw-r--r--   0 runner    (1001) docker     (123)      334 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/demos/获取单曲下载链接.py
--rw-r--r--   0 runner    (1001) docker     (123)      953 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/demos/足迹伪装.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:58:22.159691 pyncm-1.6.9.0.2/pyncm/
--rw-r--r--   0 runner    (1001) docker     (123)    10501 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    28446 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/__main__.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:58:22.163691 pyncm-1.6.9.0.2/pyncm/apis/
--rw-r--r--   0 runner    (1001) docker     (123)     6282 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)      994 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/album.py
--rw-r--r--   0 runner    (1001) docker     (123)     1723 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/artist.py
--rw-r--r--   0 runner    (1001) docker     (123)     5389 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/cloud.py
--rw-r--r--   0 runner    (1001) docker     (123)      920 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/cloudsearch.py
--rw-r--r--   0 runner    (1001) docker     (123)     8395 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/login.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:58:22.163691 pyncm-1.6.9.0.2/pyncm/apis/miniprograms/
--rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/miniprograms/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)     1724 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/miniprograms/difm.py
--rw-r--r--   0 runner    (1001) docker     (123)     2220 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/miniprograms/radio.py
--rw-r--r--   0 runner    (1001) docker     (123)     1576 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/miniprograms/sportsfm.py
--rw-r--r--   0 runner    (1001) docker     (123)     1086 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/miniprograms/zonefm.py
--rw-r--r--   0 runner    (1001) docker     (123)     3024 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/playlist.py
--rw-r--r--   0 runner    (1001) docker     (123)     5511 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/track.py
--rw-r--r--   0 runner    (1001) docker     (123)     2273 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/user.py
--rw-r--r--   0 runner    (1001) docker     (123)     1272 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/apis/video.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:58:22.163691 pyncm-1.6.9.0.2/pyncm/utils/
--rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/utils/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)    11115 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/utils/aes.py
--rw-r--r--   0 runner    (1001) docker     (123)     3855 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/utils/crypto.py
--rw-r--r--   0 runner    (1001) docker     (123)     8331 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/utils/helper.py
--rw-r--r--   0 runner    (1001) docker     (123)     8268 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/utils/lrcparser.py
--rw-r--r--   0 runner    (1001) docker     (123)     5257 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyncm/utils/security.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-24 10:58:22.159691 pyncm-1.6.9.0.2/pyncm.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     6916 2023-06-24 10:58:22.000000 pyncm-1.6.9.0.2/pyncm.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      915 2023-06-24 10:58:22.000000 pyncm-1.6.9.0.2/pyncm.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-24 10:58:22.000000 pyncm-1.6.9.0.2/pyncm.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       50 2023-06-24 10:58:22.000000 pyncm-1.6.9.0.2/pyncm.egg-info/entry_points.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-24 10:58:22.000000 pyncm-1.6.9.0.2/pyncm.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-24 10:58:22.000000 pyncm-1.6.9.0.2/pyncm.egg-info/top_level.txt
--rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/pyproject.toml
--rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-24 10:58:22.163691 pyncm-1.6.9.0.2/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)      839 2023-06-24 10:58:11.000000 pyncm-1.6.9.0.2/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:49:41.280014 pyncm-1.6.9.1/
+-rw-r--r--   0 runner    (1001) docker     (123)    11357 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     7308 2023-06-28 10:49:41.280014 pyncm-1.6.9.1/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     6826 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:49:41.276014 pyncm-1.6.9.1/demos/
+-rw-r--r--   0 runner    (1001) docker     (123)     1219 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/demos/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1074 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/demos/二维码登录.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1915 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/demos/云盘上传.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1665 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/demos/手机登录.py
+-rw-r--r--   0 runner    (1001) docker     (123)      334 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/demos/获取单曲下载链接.py
+-rw-r--r--   0 runner    (1001) docker     (123)      953 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/demos/足迹伪装.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:49:41.276014 pyncm-1.6.9.1/pyncm/
+-rw-r--r--   0 runner    (1001) docker     (123)    10499 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    29918 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/__main__.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:49:41.280014 pyncm-1.6.9.1/pyncm/apis/
+-rw-r--r--   0 runner    (1001) docker     (123)     6282 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)      994 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/album.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1723 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/artist.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5389 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/cloud.py
+-rw-r--r--   0 runner    (1001) docker     (123)      920 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/cloudsearch.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8395 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/login.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:49:41.280014 pyncm-1.6.9.1/pyncm/apis/miniprograms/
+-rw-r--r--   0 runner    (1001) docker     (123)       45 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/miniprograms/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1724 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/miniprograms/difm.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2220 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/miniprograms/radio.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1576 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/miniprograms/sportsfm.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1086 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/miniprograms/zonefm.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3024 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/playlist.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5511 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/track.py
+-rw-r--r--   0 runner    (1001) docker     (123)     2273 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/user.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1272 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/apis/video.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:49:41.280014 pyncm-1.6.9.1/pyncm/utils/
+-rw-r--r--   0 runner    (1001) docker     (123)      943 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/utils/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11115 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/utils/aes.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3855 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/utils/crypto.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8453 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/utils/helper.py
+-rw-r--r--   0 runner    (1001) docker     (123)     8422 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/utils/lrcparser.py
+-rw-r--r--   0 runner    (1001) docker     (123)     5257 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/utils/security.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4640 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyncm/utils/yrcparser.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 10:49:41.276014 pyncm-1.6.9.1/pyncm.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     7308 2023-06-28 10:49:41.000000 pyncm-1.6.9.1/pyncm.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      940 2023-06-28 10:49:41.000000 pyncm-1.6.9.1/pyncm.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 10:49:41.000000 pyncm-1.6.9.1/pyncm.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       50 2023-06-28 10:49:41.000000 pyncm-1.6.9.1/pyncm.egg-info/entry_points.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 10:49:41.000000 pyncm-1.6.9.1/pyncm.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)       12 2023-06-28 10:49:41.000000 pyncm-1.6.9.1/pyncm.egg-info/top_level.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      102 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/pyproject.toml
+-rw-r--r--   0 runner    (1001) docker     (123)       38 2023-06-28 10:49:41.280014 pyncm-1.6.9.1/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)      839 2023-06-28 10:49:30.000000 pyncm-1.6.9.1/setup.py
```

### Comparing `pyncm-1.6.9.0.2/LICENSE` & `pyncm-1.6.9.1/LICENSE`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/PKG-INFO` & `pyncm-1.6.9.1/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyncm
-Version: 1.6.9.0.2
+Version: 1.6.9.1
 Summary: NeteaseCloudMusic APIs for Python 3.x 适用于 Python 3 的网易云音乐 API
 Home-page: https://github.com/greats3an/pyncm
 Author: greats3an
 Author-email: greats3an@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Operating System :: OS Independent
@@ -52,37 +52,42 @@
                                         hires  - Hi-Res
                                         lossless- “无损”
                                         exhigh  - 较高
                                         standard- 标准
         --no-overwrite        不重复下载已经存在的音频文件
 
         歌词:
-        --lyric-no 跳过歌词 [跳过歌词 ...]
-                                跳过某些歌词类型的合并
+        --lyric-no 跳过歌词       跳过某些歌词类型的下载
                                     参数：
-                                        lrc    - 源语言歌词
-                                        tlyric - 翻译后歌词
-                                        romalrc- 罗马音歌词
+                                        lrc    - 源语言歌词  (合并到 .lrc)
+                                        tlyric - 翻译后歌词  (合并到 .lrc)
+                                        romalrc- 罗马音歌词  (合并到 .lrc)
+                                        yrc    - 逐词滚动歌词 (保存到 .ass)
+                                        none   - 下载所有歌词
                                     例：
-                                        --lyric-no tlyric --lyric-no romalrc 将只下载源语言歌词
+                                        --lyric-no tlyric romalrc yrc 将只下载源语言歌词
+                                        --lyric-no none 将下载所有歌词
+                                    注：
+                                        默认不下载 *逐词滚动歌词*
+
 
         登陆:
         --phone 手机            网易账户手机号
         --pwd 密码, --password 密码
                                 网易账户密码
         --save [保存到]          写本次登录信息于文件
         --load [保存的登陆信息文件]    从文件读取登录信息供本次登陆使用
         --http                优先使用 HTTP，不保证不被升级
         --log-level LOG_LEVEL
                                 日志等级
 
         限量及过滤（注：只适用于*每单个*链接 / ID）:
         -n 下载总量, --count 下载总量
-                                限制下载歌曲总量，n=0即不限制
-        --sort-by 歌曲排序        【限制总量时】歌曲排序方式 (default: 默认排序 hot: 热度高（相对于其所在专辑）在前 time: 发行时间新在前)
+                                限制下载歌曲总量，n=0即不限制（注：过大值可能导致限流）
+        --sort-by 歌曲排序        【限制总量时】歌曲排序方式 (default: 默认排序 hot: 热度高（相对于其所在专辑）在前 time:  发行时间新在前)
         --reverse-sort        【限制总量时】倒序排序歌曲
 
         工具:
         --save-m3u 保存M3U播放列表文件名
                                 将本次下载的歌曲文件名依一定顺序保存在M3U文件中；写入的文件目录相对于该M3U文件
                                         文件编码为 UTF-8
                                         顺序为：链接先后优先——每个连接的所有歌曲依照歌曲排序设定 （--sort-by）排序
```

### Comparing `pyncm-1.6.9.0.2/README.md` & `pyncm-1.6.9.1/README.md`

 * *Files 5% similar despite different names*

```diff
@@ -38,37 +38,42 @@
                                         hires  - Hi-Res
                                         lossless- “无损”
                                         exhigh  - 较高
                                         standard- 标准
         --no-overwrite        不重复下载已经存在的音频文件
 
         歌词:
-        --lyric-no 跳过歌词 [跳过歌词 ...]
-                                跳过某些歌词类型的合并
+        --lyric-no 跳过歌词       跳过某些歌词类型的下载
                                     参数：
-                                        lrc    - 源语言歌词
-                                        tlyric - 翻译后歌词
-                                        romalrc- 罗马音歌词
+                                        lrc    - 源语言歌词  (合并到 .lrc)
+                                        tlyric - 翻译后歌词  (合并到 .lrc)
+                                        romalrc- 罗马音歌词  (合并到 .lrc)
+                                        yrc    - 逐词滚动歌词 (保存到 .ass)
+                                        none   - 下载所有歌词
                                     例：
-                                        --lyric-no tlyric --lyric-no romalrc 将只下载源语言歌词
+                                        --lyric-no tlyric romalrc yrc 将只下载源语言歌词
+                                        --lyric-no none 将下载所有歌词
+                                    注：
+                                        默认不下载 *逐词滚动歌词*
+
 
         登陆:
         --phone 手机            网易账户手机号
         --pwd 密码, --password 密码
                                 网易账户密码
         --save [保存到]          写本次登录信息于文件
         --load [保存的登陆信息文件]    从文件读取登录信息供本次登陆使用
         --http                优先使用 HTTP，不保证不被升级
         --log-level LOG_LEVEL
                                 日志等级
 
         限量及过滤（注：只适用于*每单个*链接 / ID）:
         -n 下载总量, --count 下载总量
-                                限制下载歌曲总量，n=0即不限制
-        --sort-by 歌曲排序        【限制总量时】歌曲排序方式 (default: 默认排序 hot: 热度高（相对于其所在专辑）在前 time: 发行时间新在前)
+                                限制下载歌曲总量，n=0即不限制（注：过大值可能导致限流）
+        --sort-by 歌曲排序        【限制总量时】歌曲排序方式 (default: 默认排序 hot: 热度高（相对于其所在专辑）在前 time:  发行时间新在前)
         --reverse-sort        【限制总量时】倒序排序歌曲
 
         工具:
         --save-m3u 保存M3U播放列表文件名
                                 将本次下载的歌曲文件名依一定顺序保存在M3U文件中；写入的文件目录相对于该M3U文件
                                         文件编码为 UTF-8
                                         顺序为：链接先后优先——每个连接的所有歌曲依照歌曲排序设定 （--sort-by）排序
```

### Comparing `pyncm-1.6.9.0.2/demos/__init__.py` & `pyncm-1.6.9.1/demos/__init__.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/demos/二维码登录.py` & `pyncm-1.6.9.1/demos/二维码登录.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/demos/云盘上传.py` & `pyncm-1.6.9.1/demos/云盘上传.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/demos/手机登录.py` & `pyncm-1.6.9.1/demos/手机登录.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/demos/足迹伪装.py` & `pyncm-1.6.9.1/demos/足迹伪装.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/__init__.py` & `pyncm-1.6.9.1/pyncm/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -28,15 +28,15 @@
     >>> pyncm.SetNewSession(
             pyncm.LoadSessionFromString(save)
         )
 
 # 注意事项
     - (PR#11) 海外用户可能经历 460 "Cheating" 问题，可通过添加以下 Header 解决: `X-Real-IP = 118.88.88.88`    
 """
-__version__ = "1.6.9.0.2"
+__version__ = "1.6.9.1"
 
 from threading import current_thread
 from typing import Text, Union
 from time import time
 from .utils.crypto import EapiEncrypt, EapiDecrypt, HexCompose
 import requests, logging, json, os
 logger = logging.getLogger("pyncm.api")
```

### Comparing `pyncm-1.6.9.0.2/pyncm/__main__.py` & `pyncm-1.6.9.1/pyncm/__main__.py`

 * *Files 3% similar despite different names*

```diff
@@ -5,14 +5,15 @@
     DumpSessionAsString,
     GetCurrentSession,
     LoadSessionFromString,
     SetCurrentSession,
     __version__
 )
 from pyncm.utils.lrcparser import LrcParser
+from pyncm.utils.yrcparser import YrcParser , ASSWriter , YrcLine , YrcBlock
 from pyncm.utils.helper import TrackHelper,ArtistHelper, FuzzyPathHelper, SubstituteWithFullwidth
 from pyncm.apis import artist, login, track, playlist, album
 from queue import Queue
 from concurrent.futures import ThreadPoolExecutor
 from threading import Thread
 from time import sleep
 from os.path import join, exists
@@ -217,25 +218,42 @@
                         task.save_as + "." + dAudio["type"].lower(),                    
                         xfer=True,
                     )
                     # Downloading cover
                     dest_cvr = self.download_by_url(
                         task.cover.url, task.save_as + '.jpg'
                     )
-                    # Downloading & Parsing lyrics
-                    dest_lrc = task.save_as + '.lrc'
+                    # Downloading & Parsing lyrics                    
                     lrc = LrcParser()
-                    dLyrics = track.GetTrackLyrics(task.lyrics.id)
+                    dLyrics = track.GetTrackLyricsNew(task.lyrics.id)
                     for k in set(dLyrics.keys()) & (
                         {"lrc", "tlyric", "romalrc"} - task.lyrics.lrc_blacklist
                     ):  # Filtering LRCs
                         lrc.LoadLrc(dLyrics[k]["lyric"])
                     lrc_text = lrc.DumpLyrics()
                     if lrc_text:
-                        open(dest_lrc, "w", encoding="utf-8").write(lrc_text)
+                        open(task.save_as + '.lrc', "w", encoding="utf-8").write(lrc_text)
+                    # `yrc` (whatever that means) lyrics contains syllable-by-syllable time sigs                                        
+                    if not 'yrc' in task.lyrics.lrc_blacklist and 'yrc' in dLyrics:
+                        yrc = YrcParser(dLyrics['yrc']['version'],dLyrics['yrc']['lyric'])
+                        parsed = yrc.parse()
+                        writer = ASSWriter()
+
+                        for line in parsed:
+                            line : YrcLine
+                            writer.begin_line(line.t_begin,line.t_end)
+                            for block in line:
+                                block : YrcBlock
+                                if block.meta:
+                                    writer.add_meta(YrcParser.extract_meta(block.meta))
+                                else:
+                                    writer.add_syllable(block.t_duration,block.text)
+                            writer.end_line()
+
+                        open(task.save_as + '.ass', "w", encoding="utf-8").write(writer.content)
                     # Tagging the audio
                     try:
                         self.tag_audio(task.song, dest_src, dest_cvr)
                     except Exception as e:
                         logger.warning("标签失败 - %s - %s" % (task.song.Title, e))
                     logger.info(
                         "完成下载 #%d / %d - %s" % (task.index + 1, task.total, task.song.Title)
@@ -510,24 +528,28 @@
         default="standard",
     )
     group.add_argument("--no-overwrite", action="store_true", help="不重复下载已经存在的音频文件")
     group = parser.add_argument_group("歌词")
     group.add_argument(
         "--lyric-no",
         metavar="跳过歌词",
-        help=r"""跳过某些歌词类型的合并
-    参数：
-        lrc    - 源语言歌词
-        tlyric - 翻译后歌词
-        romalrc- 罗马音歌词
+        help=r"""跳过某些歌词类型的下载
+    参数：        
+        lrc    - 源语言歌词  (合并到 .lrc)
+        tlyric - 翻译后歌词  (合并到 .lrc)
+        romalrc- 罗马音歌词  (合并到 .lrc)
+        yrc    - 逐词滚动歌词 (保存到 .ass)
+        none   - 下载所有歌词
     例：
-        --lyric-no tlyric --lyric-no romalrc 将只下载源语言歌词""",
-        choices=["lrc", "tlyric", "romalrc"],
-        default="",
-        nargs="+",
+        --lyric-no tlyric romalrc yrc 将只下载源语言歌词
+        --lyric-no none 将下载所有歌词
+    注：
+        默认不下载 *逐词滚动歌词*
+        """,
+        default="yrc",
     )
     group = parser.add_argument_group("登陆")
     group.add_argument("--phone", metavar="手机", default="", help="网易账户手机号")
     group.add_argument("--pwd", "--password", metavar="密码", default="", help="网易账户密码")
     group.add_argument("--save", metavar="[保存到]", default="", help="写本次登录信息于文件")
     group.add_argument(
         "--load", metavar="[保存的登陆信息文件]", default="", help="从文件读取登录信息供本次登陆使用"
@@ -550,15 +572,19 @@
         metavar="保存M3U播放列表文件名",
         default="",
         help=r"""将本次下载的歌曲文件名依一定顺序保存在M3U文件中；写入的文件目录相对于该M3U文件
         文件编码为 UTF-8
         顺序为：链接先后优先——每个连接的所有歌曲依照歌曲排序设定 （--sort-by）排序"""
     )
     args = parser.parse_args()
-    
+    # Clean up    
+    args.lyric_no = args.lyric_no.lower()
+    args.lyric_no = args.lyric_no.split(' ')
+    if 'none' in args.lyric_no:
+        args.lyric_no = []
     try:
         return args , [parse_sharelink(url) for url in args.url]
     except AssertionError:
         if args.url == PLACEHOLDER_URL:
             sys.argv.append("-h")  # If using placeholder, no argument is really passed
             return __main__()  # In which case, print help and exit
         assert args.save, "无效分享链接 %s" % ' '.join(args.url) # Allow invalid links for this one
```

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/__init__.py` & `pyncm-1.6.9.1/pyncm/apis/__init__.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/album.py` & `pyncm-1.6.9.1/pyncm/apis/album.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/artist.py` & `pyncm-1.6.9.1/pyncm/apis/artist.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/cloud.py` & `pyncm-1.6.9.1/pyncm/apis/cloud.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/cloudsearch.py` & `pyncm-1.6.9.1/pyncm/apis/cloudsearch.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/login.py` & `pyncm-1.6.9.1/pyncm/apis/login.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/miniprograms/difm.py` & `pyncm-1.6.9.1/pyncm/apis/miniprograms/difm.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/miniprograms/radio.py` & `pyncm-1.6.9.1/pyncm/apis/miniprograms/radio.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/miniprograms/sportsfm.py` & `pyncm-1.6.9.1/pyncm/apis/miniprograms/sportsfm.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/miniprograms/zonefm.py` & `pyncm-1.6.9.1/pyncm/apis/miniprograms/zonefm.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/playlist.py` & `pyncm-1.6.9.1/pyncm/apis/playlist.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/track.py` & `pyncm-1.6.9.1/pyncm/apis/track.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/user.py` & `pyncm-1.6.9.1/pyncm/apis/user.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/apis/video.py` & `pyncm-1.6.9.1/pyncm/apis/video.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/utils/__init__.py` & `pyncm-1.6.9.1/pyncm/utils/__init__.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/utils/aes.py` & `pyncm-1.6.9.1/pyncm/utils/aes.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/utils/crypto.py` & `pyncm-1.6.9.1/pyncm/utils/crypto.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm/utils/helper.py` & `pyncm-1.6.9.1/pyncm/utils/helper.py`

 * *Files 1% similar despite different names*

```diff
@@ -132,14 +132,19 @@
 class TrackHelper:
     """Helper class for handling generic track objects"""
 
     def __init__(self, track_dict) -> None:
         self.__dict__.update({"data":track_dict})
 
     @property
+    def Duration(self) -> int:
+        """歌曲时长 （毫秒）"""
+        return int(self.data["dt"])
+
+    @property
     def Album(self) -> AlbumHelper:
         """专辑对象，会有更多歌曲元数据"""
         return AlbumHelper(self.data["al"]["id"])        
     
     @Default()
     def ID(self):
         """网易云音乐 ID"""
```

### Comparing `pyncm-1.6.9.0.2/pyncm/utils/lrcparser.py` & `pyncm-1.6.9.1/pyncm/utils/lrcparser.py`

 * *Files 2% similar despite different names*

```diff
@@ -20,18 +20,18 @@
 
         return _wrapper
 
     return wrapper
 
 
 class LrcRegexes:
-    LIDTag_ = re.compile(r"(?<=\[)[^\[\]]*(?=\])")
     LIDTag_Type = re.compile(r"[a-z]{2,}(?=:)")
     LIDTag_Content = re.compile(r"(?<=[a-z]{2}:).*")
-    LLyrics_ = re.compile(r"[^\[\]]*$")
+    LIDTag = re.compile(r"(?<=^\[)[^\[\]]*(?=\])")
+    LLyrics = re.compile(r"[^\[\]]*$")
     LBrackets = re.compile(r"(?<=\[).*(?=\])")
     LTimestamp = re.compile(r"\d*[\.,:]\d*[\.,:]\d*")
 
 
 # region Static methods
 # Timestamp parsers
 def stamp2tag(timestamp):
@@ -149,18 +149,22 @@
             return self.lyrics_sorted
         else:
             return lastDict
 
     def LoadLrc(self, lrc):
         """Loads a LRC formmated lryics file"""
         for line in lrc.split("\n"):
-            IDTag = LrcRegexes.LIDTag_.findall(line)
+            IDTag = LrcRegexes.LIDTag.findall(line)
+            if not IDTag:
+                # Known causes:
+                # 1. There's JSON in my LRC (wtf netease)                
+                continue
             IDTagType = "".join(LrcRegexes.LIDTag_Type.findall("".join(IDTag)))
             IDTagContent = "".join(LrcRegexes.LIDTag_Content.findall("".join(IDTag)))
-            Lyrics = "".join(LrcRegexes.LLyrics_.findall(line))
+            Lyrics = "".join(LrcRegexes.LLyrics.findall(line))
             if IDTagType:
                 # Tag's type is set,write as class attribute
                 setattr(self, IDTagType, IDTagContent)
             elif IDTag:
                 # Tag's type is not set but we got the values,treat as lyrics
                 # We'll use the timestamp (into seconds) as lyrics' keys,as hashtables can handle that
                 try:
```

### Comparing `pyncm-1.6.9.0.2/pyncm/utils/security.py` & `pyncm-1.6.9.1/pyncm/utils/security.py`

 * *Files identical despite different names*

### Comparing `pyncm-1.6.9.0.2/pyncm.egg-info/PKG-INFO` & `pyncm-1.6.9.1/pyncm.egg-info/PKG-INFO`

 * *Files 9% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pyncm
-Version: 1.6.9.0.2
+Version: 1.6.9.1
 Summary: NeteaseCloudMusic APIs for Python 3.x 适用于 Python 3 的网易云音乐 API
 Home-page: https://github.com/greats3an/pyncm
 Author: greats3an
 Author-email: greats3an@gmail.com
 Classifier: Programming Language :: Python :: 3
 Classifier: License :: OSI Approved :: Apache Software License
 Classifier: Operating System :: OS Independent
@@ -52,37 +52,42 @@
                                         hires  - Hi-Res
                                         lossless- “无损”
                                         exhigh  - 较高
                                         standard- 标准
         --no-overwrite        不重复下载已经存在的音频文件
 
         歌词:
-        --lyric-no 跳过歌词 [跳过歌词 ...]
-                                跳过某些歌词类型的合并
+        --lyric-no 跳过歌词       跳过某些歌词类型的下载
                                     参数：
-                                        lrc    - 源语言歌词
-                                        tlyric - 翻译后歌词
-                                        romalrc- 罗马音歌词
+                                        lrc    - 源语言歌词  (合并到 .lrc)
+                                        tlyric - 翻译后歌词  (合并到 .lrc)
+                                        romalrc- 罗马音歌词  (合并到 .lrc)
+                                        yrc    - 逐词滚动歌词 (保存到 .ass)
+                                        none   - 下载所有歌词
                                     例：
-                                        --lyric-no tlyric --lyric-no romalrc 将只下载源语言歌词
+                                        --lyric-no tlyric romalrc yrc 将只下载源语言歌词
+                                        --lyric-no none 将下载所有歌词
+                                    注：
+                                        默认不下载 *逐词滚动歌词*
+
 
         登陆:
         --phone 手机            网易账户手机号
         --pwd 密码, --password 密码
                                 网易账户密码
         --save [保存到]          写本次登录信息于文件
         --load [保存的登陆信息文件]    从文件读取登录信息供本次登陆使用
         --http                优先使用 HTTP，不保证不被升级
         --log-level LOG_LEVEL
                                 日志等级
 
         限量及过滤（注：只适用于*每单个*链接 / ID）:
         -n 下载总量, --count 下载总量
-                                限制下载歌曲总量，n=0即不限制
-        --sort-by 歌曲排序        【限制总量时】歌曲排序方式 (default: 默认排序 hot: 热度高（相对于其所在专辑）在前 time: 发行时间新在前)
+                                限制下载歌曲总量，n=0即不限制（注：过大值可能导致限流）
+        --sort-by 歌曲排序        【限制总量时】歌曲排序方式 (default: 默认排序 hot: 热度高（相对于其所在专辑）在前 time:  发行时间新在前)
         --reverse-sort        【限制总量时】倒序排序歌曲
 
         工具:
         --save-m3u 保存M3U播放列表文件名
                                 将本次下载的歌曲文件名依一定顺序保存在M3U文件中；写入的文件目录相对于该M3U文件
                                         文件编码为 UTF-8
                                         顺序为：链接先后优先——每个连接的所有歌曲依照歌曲排序设定 （--sort-by）排序
```

### Comparing `pyncm-1.6.9.0.2/pyncm.egg-info/SOURCES.txt` & `pyncm-1.6.9.1/pyncm.egg-info/SOURCES.txt`

 * *Files 5% similar despite different names*

```diff
@@ -32,8 +32,9 @@
 pyncm/apis/miniprograms/sportsfm.py
 pyncm/apis/miniprograms/zonefm.py
 pyncm/utils/__init__.py
 pyncm/utils/aes.py
 pyncm/utils/crypto.py
 pyncm/utils/helper.py
 pyncm/utils/lrcparser.py
-pyncm/utils/security.py
+pyncm/utils/security.py
+pyncm/utils/yrcparser.py
```

### Comparing `pyncm-1.6.9.0.2/setup.py` & `pyncm-1.6.9.1/setup.py`

 * *Files identical despite different names*


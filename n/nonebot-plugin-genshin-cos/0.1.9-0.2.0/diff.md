# Comparing `tmp/nonebot_plugin_genshin_cos-0.1.9.tar.gz` & `tmp/nonebot_plugin_genshin_cos-0.2.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nonebot_plugin_genshin_cos-0.1.9.tar", max compression
+gzip compressed data, was "nonebot_plugin_genshin_cos-0.2.0.tar", max compression
```

## Comparing `nonebot_plugin_genshin_cos-0.1.9.tar` & `nonebot_plugin_genshin_cos-0.2.0.tar`

### file list

```diff
@@ -1,8 +1,9 @@
--rw-r--r--   0        0        0     1085 2023-03-28 09:06:05.557316 nonebot_plugin_genshin_cos-0.1.9/LICENSE
--rw-r--r--   0        0        0     9064 2023-06-12 11:50:54.865621 nonebot_plugin_genshin_cos-0.1.9/nonebot_plugin_genshin_cos/__init__.py
--rw-r--r--   0        0        0      269 2023-06-05 05:24:06.712318 nonebot_plugin_genshin_cos-0.1.9/nonebot_plugin_genshin_cos/config.py
--rw-r--r--   0        0        0   459180 2023-06-05 05:24:06.718316 nonebot_plugin_genshin_cos-0.1.9/nonebot_plugin_genshin_cos/fonts/CONSOLA.TTF
--rw-r--r--   0        0        0    11068 2023-06-05 05:24:06.719317 nonebot_plugin_genshin_cos-0.1.9/nonebot_plugin_genshin_cos/utils.py
--rw-r--r--   0        0        0      661 2023-06-12 11:52:40.997032 nonebot_plugin_genshin_cos-0.1.9/pyproject.toml
--rw-r--r--   0        0        0     3636 2023-06-05 05:24:06.711314 nonebot_plugin_genshin_cos-0.1.9/README.md
--rw-r--r--   0        0        0     4423 1970-01-01 00:00:00.000000 nonebot_plugin_genshin_cos-0.1.9/PKG-INFO
+-rw-r--r--   0        0        0     1085 2023-03-28 09:06:05.557316 nonebot_plugin_genshin_cos-0.2.0/LICENSE
+-rw-r--r--   0        0        0    14359 2023-06-28 07:36:48.597725 nonebot_plugin_genshin_cos-0.2.0/nonebot_plugin_genshin_cos/__init__.py
+-rw-r--r--   0        0        0      230 2023-06-28 07:41:10.710745 nonebot_plugin_genshin_cos-0.2.0/nonebot_plugin_genshin_cos/config.py
+-rw-r--r--   0        0        0   459180 2023-06-05 05:24:06.718316 nonebot_plugin_genshin_cos-0.2.0/nonebot_plugin_genshin_cos/fonts/CONSOLA.TTF
+-rw-r--r--   0        0        0    11088 2023-06-28 04:58:44.275589 nonebot_plugin_genshin_cos-0.2.0/nonebot_plugin_genshin_cos/hoyospider.py
+-rw-r--r--   0        0        0     4019 2023-06-28 11:15:13.406876 nonebot_plugin_genshin_cos-0.2.0/nonebot_plugin_genshin_cos/utils.py
+-rw-r--r--   0        0        0      636 2023-06-28 11:14:48.437590 nonebot_plugin_genshin_cos-0.2.0/pyproject.toml
+-rw-r--r--   0        0        0     3882 2023-06-27 09:24:22.854792 nonebot_plugin_genshin_cos-0.2.0/README.md
+-rw-r--r--   0        0        0     4635 1970-01-01 00:00:00.000000 nonebot_plugin_genshin_cos-0.2.0/PKG-INFO
```

### Comparing `nonebot_plugin_genshin_cos-0.1.9/LICENSE` & `nonebot_plugin_genshin_cos-0.2.0/LICENSE`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_genshin_cos-0.1.9/nonebot_plugin_genshin_cos/fonts/CONSOLA.TTF` & `nonebot_plugin_genshin_cos-0.2.0/nonebot_plugin_genshin_cos/fonts/CONSOLA.TTF`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_genshin_cos-0.1.9/pyproject.toml` & `nonebot_plugin_genshin_cos-0.2.0/pyproject.toml`

 * *Files 4% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "nonebot-plugin-genshin-cos"
-version = "0.1.9"
+version = "0.2.0"
 description = "米游社原神cos图获取"
 authors = ["Cvandia <106718176+Cvandia@users.noreply.github.com>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "nonebot_plugin_genshin_cos"}]
 
 [tool.poetry.dependencies]
@@ -13,13 +13,12 @@
 nonebot-adapter-onebot = ">=2.0.0-beta.1"
 httpx = ">=0.19.0"
 nonebot-plugin-apscheduler= ">=0.1.3"
 aiofiles = ">=0.7.0"
 pydantic = ">=1.10.2"
 pathlib = ">=1.0.1"
 ujson = ">=5.5.0"
-playwright = ">=1.30.0"
 
 
 [build-system]
 requires = ["poetry-core"]
 build-backend = "poetry.core.masonry.api"
```

### Comparing `nonebot_plugin_genshin_cos-0.1.9/PKG-INFO` & `nonebot_plugin_genshin_cos-0.2.0/PKG-INFO`

 * *Files 8% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: nonebot-plugin-genshin-cos
-Version: 0.1.9
+Version: 0.2.0
 Summary: 米游社原神cos图获取
 License: MIT
 Author: Cvandia
 Author-email: 106718176+Cvandia@users.noreply.github.com
 Requires-Python: >=3.8,<4
 Classifier: License :: OSI Approved :: MIT License
 Classifier: Programming Language :: Python :: 3
@@ -14,15 +14,14 @@
 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: aiofiles (>=0.7.0)
 Requires-Dist: httpx (>=0.19.0)
 Requires-Dist: nonebot-adapter-onebot (>=2.0.0-beta.1)
 Requires-Dist: nonebot-plugin-apscheduler (>=0.1.3)
 Requires-Dist: nonebot2 (>=2.0.0-beta.1)
 Requires-Dist: pathlib (>=1.0.1)
-Requires-Dist: playwright (>=1.30.0)
 Requires-Dist: pydantic (>=1.10.2)
 Requires-Dist: ujson (>=5.5.0)
 Description-Content-Type: text/markdown
 
 
 <div align="center">
 
@@ -88,64 +87,61 @@
  
  推荐镜像站下载
   
  清华源```https://pypi.tuna.tsinghua.edu.cn/simple```
  
  阿里源```https://mirrors.aliyun.com/pypi/simple/```
 
-
- 安装完后记得执行一下：
- ```playwright install```
-~~懒，没写自动下载chrome~~ 
 </details>
 
 
 ## ⚙️ 配置
 ### 在env.中添加以下配置
 
 | 配置 | 类型 | 默认值 | 说明 |
 |:-----:|:----:|:----:|:---:|
 |cos_max|int|5|最大返回cos图片数量|
 |cos_path|str|无|不配置则默认下载到bot根目录的`"data/genshin_cos"`,支持绝对路劲如`"C:/Users/image"`和相对bot根目录路劲如`"coser/image"`
 |cos_cd|int|30|用户触发cd|
-|cos_time_out|int|60|cosplus用户超时时间|
-|cos_swipe_time|int|1|获取页面的时间，时间越长图片越多|
 
 > 注意：绝对路劲中用`/`，用`\`可能会被转义
 
 ## ⭐ 使用
 
 ### 指令：
 | 指令 | 需要@ | 范围 | 说明 |权限|
 |:-----:|:----:|:----:|:----:|:----:|
-|原神cos|否|私聊、群聊|随机发送x张cos图，如：米游社cos x3|任何|
-|下载cos|否|私聊、群聊|爬取cos图片至本地,如：下载cos|超管|
-|cosplus|否|私聊、群聊|通过playwright获取cos图|任何|
-|xmx|否|私聊、群聊|？？？？？s|超管|
+|下载cos|否|群聊、私聊|下载热门cos图|超管、群主、管理员|
+|热门cos|否|同上|获取指定游戏热门cos图，如`热门cos 原神 x3`|全部|
+|日、周、月榜cos|否|同上|获取排行榜cos图。如`日榜cos 原神 x3`|全部|
+|最新cos|否|同上|和上面差不多，不写了，哼哼|全部|
+|精品cos|否|同上|上上面一样的道理！|全部|
+|开启每日推送xx (时间)|否|仅群聊|如`开启每日推送原神 8:30`,注意时间的格式|超管、群主、管理员|
 
 **注意**
 
 指令触发方式是正则匹配的，不需要加指令前缀
 
 ## 🌙 未来
  - [x] 缓慢更新，最近学业繁忙哦~
  - [x] 随机发送cos图片
  - [x] 保存cos图
  - [x] 内置cd和用户触发上限
  - [x] 合并转发发送多张cos图
- - [x] playwright获取cos图
- - [ ] 选择发送图库方式：离线 (迅速) or 在线（缓慢、目前是的）
-
+~~playwright获取cos图~~
+~~选择发送图库方式：离线 (迅速) or 在线（缓慢、目前是的）~~
+ - [x] 支持米游社其他社区cos获取
+ - [x] 支持每日推送热榜的cos图
 
 --- 喜欢记得点个star⭐---
 
 ## ❗免责声明
 
 图片版权归米游社原神cos社区所属，请尊重
 coser的创作权
 
 
 
-## 💝 鸣谢
+## 💝 特别鸣谢
 
 - [x] [Nonebot](https://github.com/nonebot/nonebot2): 本项目的基础，非常好用的聊天机器人框架。
-
+- [x] [@qxdn](https://github.com/qxdn):感谢qxdn的[博客文章](https://qianxu.run/2021/11/12/mihoyo-bbs-crawler/),有兴趣大家也去看看咯
```

#### html2text {}

```diff
@@ -1,20 +1,19 @@
-Metadata-Version: 2.1 Name: nonebot-plugin-genshin-cos Version: 0.1.9 Summary:
+Metadata-Version: 2.1 Name: nonebot-plugin-genshin-cos Version: 0.2.0 Summary:
 ç±³æ¸¸ç¤¾åç¥coså¾è·å License: MIT Author: Cvandia Author-email:
 106718176+Cvandia@users.noreply.github.com Requires-Python: >=3.8,<4
 Classifier: License :: OSI Approved :: MIT License Classifier: Programming
 Language :: Python :: 3 Classifier: Programming Language :: Python :: 3.8
 Classifier: Programming Language :: Python :: 3.9 Classifier: Programming
 Language :: Python :: 3.10 Classifier: Programming Language :: Python :: 3.11
 Requires-Dist: aiofiles (>=0.7.0) Requires-Dist: httpx (>=0.19.0) Requires-
 Dist: nonebot-adapter-onebot (>=2.0.0-beta.1) Requires-Dist: nonebot-plugin-
 apscheduler (>=0.1.3) Requires-Dist: nonebot2 (>=2.0.0-beta.1) Requires-Dist:
-pathlib (>=1.0.1) Requires-Dist: playwright (>=1.30.0) Requires-Dist: pydantic
-(>=1.10.2) Requires-Dist: ujson (>=5.5.0) Description-Content-Type: text/
-markdown
+pathlib (>=1.0.1) Requires-Dist: pydantic (>=1.10.2) Requires-Dist: ujson
+(>=5.5.0) Description-Content-Type: text/markdown
                               [NoneBotPluginLogo]
                          # nonebot-plugin-genshin-cos
           _â­åºäºNonebot2çä¸æ¬¾è·åç±³æ¸¸ç¤¾cosçæä»¶â­_
 [https://img.shields.io/badge/python-3.8+-blue] [https://img.shields.io/badge/
 QQ-1141538825-yellow] [https://img.shields.io/badge/license-MIT-blue] [https://
                     img.shields.io/badge/Nonebot2-rc1+-red]
 ## â­ ä»ç» åå°[æç¨](https://juejin.cn/post/
@@ -25,34 +24,38 @@
 ``` - å¨nonebotçpyproject.tomlä¸­çplugins = ["xxx"]æ·»å æ­¤æä»¶ nb-
 cliå®è£ ``` nb plugin install nonebot-plugin-genshin-cos --upgrade ``` git
 cloneå®è£(ä¸æ¨è) - è¿è¡ ```git clone https://github.com/Cvandia/
 nonebot_plugin_genshin_cos``` - å¨è¿è¡å¤ ææä»¶å¤¹`nonebot-plugin-
 genshen-cos`å¤å¶å°botæ ¹ç®å½ä¸ç`src/plugins`
 (æèä½ åå»ºbotæ¶çå¶ä»åç§°`xxx/plugins`)   æ³¨æ
 æ¨èéåç«ä¸è½½ æ¸åæº```https://pypi.tuna.tsinghua.edu.cn/simple```
-é¿éæº```https://mirrors.aliyun.com/pypi/simple/```
-å®è£å®åè®°å¾æ§è¡ä¸ä¸ï¼ ```playwright install```
-~~æï¼æ²¡åèªå¨ä¸è½½chrome~~  ## âï¸ éç½® ###
+é¿éæº```https://mirrors.aliyun.com/pypi/simple/```  ## âï¸ éç½® ###
 å¨env.ä¸­æ·»å ä»¥ä¸éç½® | éç½® | ç±»å | é»è®¤å¼ | è¯´æ | |:-----:
 |:----:|:----:|:---:| |cos_max|int|5|æå¤§è¿åcoså¾çæ°é|
 |cos_path|str|æ |ä¸éç½®åé»è®¤ä¸è½½å°botæ ¹ç®å½ç`"data/
 genshin_cos"`,æ¯æç»å¯¹è·¯å²å¦`"C:/Users/
 image"`åç¸å¯¹botæ ¹ç®å½è·¯å²å¦`"coser/image"`
-|cos_cd|int|30|ç¨æ·è§¦åcd| |cos_time_out|int|60|cosplusç¨æ·è¶æ¶æ¶é´|
-|cos_swipe_time|int|1|è·åé¡µé¢çæ¶é´ï¼æ¶é´è¶é¿å¾çè¶å¤| >
-æ³¨æï¼ç»å¯¹è·¯å²ä¸­ç¨`/`ï¼ç¨`\`å¯è½ä¼è¢«è½¬ä¹ ## â­ ä½¿ç¨ ###
-æä»¤ï¼ | æä»¤ | éè¦@ | èå´ | è¯´æ |æé| |:-----:|:----:|:----:
-|:----:|:----:
-| |åç¥cos|å¦|ç§èãç¾¤è|éæºåéxå¼ coså¾ï¼å¦ï¼ç±³æ¸¸ç¤¾cos
-x3|ä»»ä½|
-|ä¸è½½cos|å¦|ç§èãç¾¤è|ç¬åcoså¾çè³æ¬å°,å¦ï¼ä¸è½½cos|è¶ç®¡|
-|cosplus|å¦|ç§èãç¾¤è|éè¿playwrightè·åcoså¾|ä»»ä½|
-|xmx|å¦|ç§èãç¾¤è|ï¼ï¼ï¼ï¼ï¼s|è¶ç®¡| **æ³¨æ**
+|cos_cd|int|30|ç¨æ·è§¦åcd| > æ³¨æï¼ç»å¯¹è·¯å²ä¸­ç¨`/
+`ï¼ç¨`\`å¯è½ä¼è¢«è½¬ä¹ ## â­ ä½¿ç¨ ### æä»¤ï¼ | æä»¤ | éè¦@ |
+èå´ | è¯´æ |æé| |:-----:|:----:|:----:|:----:|:----:
+|
+|ä¸è½½cos|å¦|ç¾¤èãç§è|ä¸è½½ç­é¨coså¾|è¶ç®¡ãç¾¤ä¸»ãç®¡çå|
+|ç­é¨cos|å¦|åä¸|è·åæå®æ¸¸æç­é¨coså¾ï¼å¦`ç­é¨cos åç¥
+x3`|å¨é¨|
+|æ¥ãå¨ãææ¦cos|å¦|åä¸|è·åæè¡æ¦coså¾ãå¦`æ¥æ¦cos åç¥
+x3`|å¨é¨|
+|ææ°cos|å¦|åä¸|åä¸é¢å·®ä¸å¤ï¼ä¸åäºï¼å¼å¼|å¨é¨|
+|ç²¾åcos|å¦|åä¸|ä¸ä¸é¢ä¸æ ·çéçï¼|å¨é¨| |å¼å¯æ¯æ¥æ¨éxx
+(æ¶é´)|å¦|ä»ç¾¤è|å¦`å¼å¯æ¯æ¥æ¨éåç¥ 8:
+30`,æ³¨ææ¶é´çæ ¼å¼|è¶ç®¡ãç¾¤ä¸»ãç®¡çå| **æ³¨æ**
 æä»¤è§¦åæ¹å¼æ¯æ­£åå¹éçï¼ä¸éè¦å æä»¤åç¼ ## ð æªæ¥
 - [x] ç¼æ¢æ´æ°ï¼æè¿å­¦ä¸ç¹å¿å¦~ - [x] éæºåécoså¾ç - [x]
 ä¿å­coså¾ - [x] åç½®cdåç¨æ·è§¦åä¸é - [x]
-åå¹¶è½¬ååéå¤å¼ coså¾ - [x] playwrightè·åcoså¾ - [ ]
-éæ©åéå¾åºæ¹å¼ï¼ç¦»çº¿ (è¿é) or å¨çº¿ï¼ç¼æ¢ãç®åæ¯çï¼
---- åæ¬¢è®°å¾ç¹ä¸ªstarâ­--- ## âåè´£å£°æ
-å¾ççæå½ç±³æ¸¸ç¤¾åç¥cosç¤¾åºæå±ï¼è¯·å°é coserçåä½æ ##
-ð é¸£è°¢ - [x] [Nonebot](https://github.com/nonebot/nonebot2):
-æ¬é¡¹ç®çåºç¡ï¼éå¸¸å¥½ç¨çèå¤©æºå¨äººæ¡æ¶ã
+åå¹¶è½¬ååéå¤å¼ coså¾ ~~playwrightè·åcoså¾~~
+~~éæ©åéå¾åºæ¹å¼ï¼ç¦»çº¿ (è¿é) or
+å¨çº¿ï¼ç¼æ¢ãç®åæ¯çï¼~~ - [x] æ¯æç±³æ¸¸ç¤¾å¶ä»ç¤¾åºcosè·å
+- [x] æ¯ææ¯æ¥æ¨éç­æ¦çcoså¾ --- åæ¬¢è®°å¾ç¹ä¸ªstarâ­--- ##
+âåè´£å£°æ å¾ççæå½ç±³æ¸¸ç¤¾åç¥cosç¤¾åºæå±ï¼è¯·å°é
+coserçåä½æ ## ð ç¹å«é¸£è°¢ - [x] [Nonebot](https://github.com/
+nonebot/nonebot2): æ¬é¡¹ç®çåºç¡ï¼éå¸¸å¥½ç¨çèå¤©æºå¨äººæ¡æ¶ã
+- [x] [@qxdn](https://github.com/qxdn):æè°¢qxdnç[åå®¢æç« ](https://
+qianxu.run/2021/11/12/mihoyo-bbs-crawler/),æå´è¶£å¤§å®¶ä¹å»ççå¯
```


# Comparing `tmp/nonebot_plugin_rename-1.5.6.tar.gz` & `tmp/nonebot_plugin_rename-1.6.0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nonebot_plugin_rename-1.5.6.tar", max compression
+gzip compressed data, was "nonebot_plugin_rename-1.6.0.tar", max compression
```

## Comparing `nonebot_plugin_rename-1.5.6.tar` & `nonebot_plugin_rename-1.6.0.tar`

### file list

```diff
@@ -1,22 +1,22 @@
--rw-r--r--   0        0        0     1066 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/LICENSE
--rw-r--r--   0        0        0     6090 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/README.md
--rw-r--r--   0        0        0      550 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/__init__.py
--rw-r--r--   0        0        0      479 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/__init__.py
--rw-r--r--   0        0        0     1616 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/exam_time.py
--rw-r--r--   0        0        0      689 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/get_times.py
--rw-r--r--   0        0        0     1274 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/hot_search.py
--rw-r--r--   0        0        0      450 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/message.py
--rw-r--r--   0        0        0     1500 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/mhy_time.py
--rw-r--r--   0        0        0      607 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/one_word.py
--rw-r--r--   0        0        0      307 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/status.py
--rw-r--r--   0        0        0      697 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/year_time.py
--rw-r--r--   0        0        0      593 2023-06-21 06:24:10.017716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/config.py
--rw-r--r--   0        0        0  1878036 2023-06-21 06:24:10.033716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/fonts/draw.ttf
--rw-r--r--   0        0        0     8733 2023-06-21 06:24:10.037716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/main.py
--rw-r--r--   0        0        0      264 2023-06-21 06:24:10.037716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/utils/__init__.py
--rw-r--r--   0        0        0      479 2023-06-21 06:24:10.037716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/utils/card_choice.py
--rw-r--r--   0        0        0      970 2023-06-21 06:24:10.037716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/utils/card_name.py
--rw-r--r--   0        0        0     1528 2023-06-21 06:24:10.037716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/utils/draw.py
--rw-r--r--   0        0        0      400 2023-06-21 06:24:10.037716 nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/utils/my_yaml.py
--rw-r--r--   0        0        0      700 2023-06-21 06:24:10.037716 nonebot_plugin_rename-1.5.6/pyproject.toml
--rw-r--r--   0        0        0     6995 1970-01-01 00:00:00.000000 nonebot_plugin_rename-1.5.6/PKG-INFO
+-rw-r--r--   0        0        0     1066 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/LICENSE
+-rw-r--r--   0        0        0     6175 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/README.md
+-rw-r--r--   0        0        0      542 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/__init__.py
+-rw-r--r--   0        0        0      479 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/__init__.py
+-rw-r--r--   0        0        0     1616 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/exam_time.py
+-rw-r--r--   0        0        0      689 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/get_times.py
+-rw-r--r--   0        0        0     1763 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/hot_search.py
+-rw-r--r--   0        0        0      450 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/message.py
+-rw-r--r--   0        0        0     1500 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/mhy_time.py
+-rw-r--r--   0        0        0      601 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/one_word.py
+-rw-r--r--   0        0        0      307 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/status.py
+-rw-r--r--   0        0        0      697 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/year_time.py
+-rw-r--r--   0        0        0      621 2023-06-28 03:36:56.252143 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/config.py
+-rw-r--r--   0        0        0  1878036 2023-06-28 03:36:56.268142 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/fonts/draw.ttf
+-rw-r--r--   0        0        0     8733 2023-06-28 03:36:56.268142 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/main.py
+-rw-r--r--   0        0        0      264 2023-06-28 03:36:56.268142 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/utils/__init__.py
+-rw-r--r--   0        0        0      479 2023-06-28 03:36:56.268142 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/utils/card_choice.py
+-rw-r--r--   0        0        0      970 2023-06-28 03:36:56.268142 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/utils/card_name.py
+-rw-r--r--   0        0        0     1528 2023-06-28 03:36:56.268142 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/utils/draw.py
+-rw-r--r--   0        0        0      400 2023-06-28 03:36:56.268142 nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/utils/my_yaml.py
+-rw-r--r--   0        0        0      700 2023-06-28 03:36:56.268142 nonebot_plugin_rename-1.6.0/pyproject.toml
+-rw-r--r--   0        0        0     7080 1970-01-01 00:00:00.000000 nonebot_plugin_rename-1.6.0/PKG-INFO
```

### Comparing `nonebot_plugin_rename-1.5.6/LICENSE` & `nonebot_plugin_rename-1.6.0/LICENSE`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_rename-1.5.6/README.md` & `nonebot_plugin_rename-1.6.0/README.md`

 * *Files 3% similar despite different names*

```diff
@@ -17,24 +17,23 @@
     <img src="https://img.shields.io/pypi/v/nonebot-plugin-rename.svg" alt="pypi">
 </a>
 <img src="https://img.shields.io/badge/python-3.8+-yellow.svg" alt="python">
 
 </div>
 
 <!-- TOC -->
-* [nonebot-plugin-rename](#nonebot-plugin-rename)
-  * [📖简介](#简介)
-  * [🔐许可](#许可)
-  * [💿 安装方法](#-安装方法)
-  * [🏷️插件命令](#插件命令)
-  * [⚙️插件配置项](#插件配置项)
-  * [🎉目前已实现的群名片功能](#目前已实现的群名片功能)
-  * [🧐PR需知](#pr需知)
-  * [🔥鸣谢](#鸣谢)
-  <!-- TOC -->
+- [nonebot-plugin-rename](#nonebot-plugin-rename)
+  - [📖简介](#简介)
+  - [🔐许可](#许可)
+  - [💿 安装方法](#-安装方法)
+  - [🏷️插件命令](#️插件命令)
+  - [⚙️插件配置项](#️插件配置项)
+  - [🎉目前已实现的群名片功能](#目前已实现的群名片功能)
+  - [🧐PR需知](#pr需知)
+  - [🔥鸣谢](#鸣谢)
 
 ## 📖简介
 
 通过定时任务更改bot(s)所在群自己的群名片
 
 ## 🔐许可
 
@@ -87,14 +86,15 @@
 | use_nickname_front            | 是否在群名片前加上bot名称              | bool | True           |
 | self_name                     | 自定义前缀(需开启上一个配置)             | str  | None           |
 | is_one_bot_set_all_group_card | 是否允许与单个bot会话可以设置所有bot所在的群名片 | bool | False          |
 | is_show_aps_info_log          | 是否显示定时任务的info级别日志           | bool | True           |
 | is_show_hot_search_from       | 热搜是否显示来源                    | bool | False          |
 | zk_time_start                 | 中考开始时间                      | str  | 06-12 09:00:00 |
 | zk_time_end                   | 中考结束时间                      | str  | 06-14 11:00:00 |
+| hot_search_url                | 热搜获取API，1为作者提供，2为tenapi| int  | 1 |
 
 **如果要使用中考剩余时间，由于每个地方中考时间并不统一，请务必填写`zk_time`系列配置项，否则获取的时间并不是你们当地的中考时间节点（开始和结束时间），参考配置如下**
 ```dotenv
 zk_time_start="06-12 09:00:00"
 zk_time_end="06-14 11:00:00"
 ```
```

#### html2text {}

```diff
@@ -1,18 +1,18 @@
                              [NoneBotPluginLogo]
                               [NoneBotPluginText]
                          # nonebot-plugin-rename _â¨
 éè¿å®æ¶ä»»å¡æ´æ¹botæå¨ç¾¤èªå·±çç¾¤åç,åç½®äºå ç§å¸¸è§çç¾¤åçå¹¶ä¸åæ­¥æ¯æäºå¤bot,æ¬¢è¿**pr**æ°çç¾¤åç!
                         â¨_ [license] [pypi] [python]
- * [nonebot-plugin-rename](#nonebot-plugin-rename) * [ðç®ä»](#ç®ä») *
-[ðè®¸å¯](#è®¸å¯) * [ð¿ å®è£æ¹æ³](#-å®è£æ¹æ³) *
-[ð·ï¸æä»¶å½ä»¤](#æä»¶å½ä»¤) * [âï¸æä»¶éç½®é¡¹]
-(#æä»¶éç½®é¡¹) * [ðç®åå·²å®ç°çç¾¤åçåè½]
-(#ç®åå·²å®ç°çç¾¤åçåè½) * [ð§PRéç¥](#préç¥) * [ð¥é¸£è°¢]
-(#é¸£è°¢)  ## ðç®ä» éè¿å®æ¶ä»»å¡æ´æ¹bot
+ - [nonebot-plugin-rename](#nonebot-plugin-rename) - [ðç®ä»](#ç®ä») -
+[ðè®¸å¯](#è®¸å¯) - [ð¿ å®è£æ¹æ³](#-å®è£æ¹æ³) -
+[ð·ï¸æä»¶å½ä»¤](#ï¸æä»¶å½ä»¤) - [âï¸æä»¶éç½®é¡¹]
+(#ï¸æä»¶éç½®é¡¹) - [ðç®åå·²å®ç°çç¾¤åçåè½]
+(#ç®åå·²å®ç°çç¾¤åçåè½) - [ð§PRéç¥](#préç¥) - [ð¥é¸£è°¢]
+(#é¸£è°¢) ## ðç®ä» éè¿å®æ¶ä»»å¡æ´æ¹bot
 (s)æå¨ç¾¤èªå·±çç¾¤åç ## ðè®¸å¯ [MIT](https://github.com/
 forchannot/nonebot-plugin-rename/blob/main/LICENSE) ## ð¿ å®è£æ¹æ³
 ä½¿ç¨ nb-cli å®è£ å¨ nonebot2 é¡¹ç®çæ ¹ç®å½ä¸æå¼å½ä»¤è¡,
 è¾å¥ä»¥ä¸æä»¤å³å¯å®è£ nb plugin install nonebot-plugin-rename   pip
 pip install nonebot-plugin-rename æå¼ nonebot2 é¡¹ç®æ ¹ç®å½ä¸ç
 `pyproject.toml` æä»¶, å¨ `[tool.nonebot]` é¨åè¿½å åå¥ plugins =
 ["nonebot_plugin_rename"] ``` [tool.nonebot] plugins = [] plugin_dirs = ["src/
@@ -32,15 +32,16 @@
 æ¯å¦å¨ç¾¤åçåå ä¸botåç§° | bool | True | | self_name |
 èªå®ä¹åç¼(éå¼å¯ä¸ä¸ä¸ªéç½®) | str | None | |
 is_one_bot_set_all_group_card |
 æ¯å¦åè®¸ä¸åä¸ªbotä¼è¯å¯ä»¥è®¾ç½®ææbotæå¨çç¾¤åç | bool |
 False | | is_show_aps_info_log | æ¯å¦æ¾ç¤ºå®æ¶ä»»å¡çinfoçº§å«æ¥å¿ |
 bool | True | | is_show_hot_search_from | ç­ææ¯å¦æ¾ç¤ºæ¥æº | bool |
 False | | zk_time_start | ä¸­èå¼å§æ¶é´ | str | 06-12 09:00:00 | |
-zk_time_end | ä¸­èç»ææ¶é´ | str | 06-14 11:00:00 |
+zk_time_end | ä¸­èç»ææ¶é´ | str | 06-14 11:00:00 | | hot_search_url |
+ç­æè·åAPIï¼1ä¸ºä½èæä¾ï¼2ä¸ºtenapi| int | 1 |
 **å¦æè¦ä½¿ç¨ä¸­èå©ä½æ¶é´ï¼ç±äºæ¯ä¸ªå°æ¹ä¸­èæ¶é´å¹¶ä¸ç»ä¸ï¼è¯·å¡å¿å¡«å`zk_time`ç³»åéç½®é¡¹ï¼å¦åè·åçæ¶é´å¹¶ä¸æ¯ä½ ä»¬å½å°çä¸­èæ¶é´èç¹ï¼å¼å§åç»ææ¶é´ï¼ï¼åèéç½®å¦ä¸**
 ```dotenv zk_time_start="06-12 09:00:00" zk_time_end="06-14 11:00:00" ```
 **è¯·æ³¨æä¸è¦å°`set_group_card_hour`å`set_group_card_minute`é½è®¾ä¸º0**
 **ç±äºqqç¾¤åçç¹æ®æ§,é´éå¤ªç­å¯è½æä¹å¹¶ä¸å¤§åèå®¹æå¯¼è´é£æ§,å»ºè®®å¨30åéä»¥ä¸**
 ## ðç®åå·²å®ç°çç¾¤åçåè½  ä¸å¾æµ [help]   æ¶é´
 -- é«èæ¶é´
 -- ä¸­èæ¶é´
```

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/__init__.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/__init__.py`

 * *Files 19% similar despite different names*

```diff
@@ -1,19 +1,19 @@
 from nonebot.plugin import PluginMetadata
 
-from .config import env_config
+from .config import Config
 from .main import *  # noqa
 
-__version__ = "1.5.6"
+__version__ = "1.6.0"
 __plugin_meta__ = PluginMetadata(
     name="nonebot_plugin_rename",
     description="用于更改qq机器人的群名片，内置多种有趣名片",
     usage="查看本仓库readme",
     supported_adapters={"~onebot.v11"},
     type="application",
-    config=env_config,
+    config=Config,
     homepage="https://github.com/forchannot/nonebot_plugin_rename",
     extra={
         "author": "forchannot",
         "version": __version__,
     },
 )
```

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/exam_time.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/exam_time.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/get_times.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/get_times.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/hot_search.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/hot_search.py`

 * *Files 22% similar despite different names*

```diff
@@ -3,37 +3,50 @@
 import random
 
 import httpx
 from nonebot import logger
 
 from ..config import env_config
 
-# URL = {
-#     "1": "https://tenapi.cn/v2/bilihot/",  # B站
-#     "2": "https://tenapi.cn/v2/weibohot",  # 微博
-#     "3": "https://tenapi.cn/v2/douyinhot",  # 抖音
-#     "4": "https://tenapi.cn/v2/baiduhot/",  # 百度
-#     "5": "https://tenapi.cn/v2/zhihuhot",  # 知乎
-#     "6": "https://tenapi.cn/v2/toutiaohot",  # 今日头条
-# }
-URL = {
+URL1 = {
     "1": ("bilibili", "B站"),  # B站
     "2": ("weibo", "微博"),  # 微博
     "3": ("newsqq", "腾讯"),  # 腾讯新闻
     "4": ("baidu", "百度"),  # 百度
     "5": ("zhihu", "知乎"),  # 知乎
     "6": ("toutiao", "头条"),  # 今日头条
-}
+}  # hot.zhenxun.buzz
+URL2 = {
+    "1": ("bilihot", "B站"),  # B站
+    "2": ("weibohot", "微博"),  # 微博
+    "3": ("douyinhot", "抖音"),  # 抖音
+    "4": ("baiduhot", "百度"),  # 百度
+    "5": ("zhihuhot", "知乎"),  # 知乎
+    "6": ("toutiaohot", "头条"),  # 今日头条
+}  # tenapi.cn
 
 
 async def hot(num: int) -> str:
+    URLSTART = (
+        "https://hot.zhenxun.buzz"
+        if env_config.hot_search_url == 1
+        else "https://tenapi.cn/v2"
+    )
+    URL = URL1 if env_config.hot_search_url == 1 else URL2
     async with httpx.AsyncClient(follow_redirects=True) as client:
         try:
-            res = await client.get(f"https://hot.zhenxun.buzz/{URL[str(num)][0]}")
+            res = await client.get(f"{URLSTART}/{URL[str(num)][0]}")
+            if res.status_code != 200:
+                return "热搜获取失败"
             data = res.json()["data"]
-            result = random.choice(data)["title"]
+            result = (
+                random.choice(data)["title"]
+                if env_config.hot_search_url == 1
+                else random.choice(data)["name"]
+            )
             if env_config.is_show_hot_search_from:
+                logger.warning(f"获取热搜失败: {res.status_code}，请尝试更换API后重启")
                 result = f"{URL[str(num)][1]}：{result}"
             return result
         except Exception as e:
-            logger.warning(f"获取热搜失败: {e}")
+            logger.warning(f"获取热搜失败: {e}，请尝试更换API后重启")
             return "热搜获取失败"
```

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/mhy_time.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/mhy_time.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/card/year_time.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/card/year_time.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/config.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/config.py`

 * *Files 25% similar despite different names*

```diff
@@ -11,10 +11,11 @@
     use_nickname_front: bool = True
     is_show_hot_search_from: bool = False
     self_name: Optional[str] = None
     is_one_bot_set_all_group_card: bool = False
     is_show_aps_info_log: bool = True
     zk_time_start: str = "06-12 09:00:00"
     zk_time_end: str = "06-14 11:00:00"
+    hot_search_url: int = 1
 
 
 env_config = Config.parse_obj(get_driver().config.dict())
```

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/fonts/draw.ttf` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/fonts/draw.ttf`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/main.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/main.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/utils/card_name.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/utils/card_name.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_rename-1.5.6/nonebot_plugin_rename/utils/draw.py` & `nonebot_plugin_rename-1.6.0/nonebot_plugin_rename/utils/draw.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_rename-1.5.6/pyproject.toml` & `nonebot_plugin_rename-1.6.0/pyproject.toml`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "nonebot-plugin-rename"
-version = "1.5.6"
+version = "1.6.0"
 description = "更改qq机器人的群名片，内置多种有趣名片"
 authors = ["forchannot <yy320206@gmail.com>"]
 license = "GPL-3.0"
 readme = "README.md"
 packages = [{include = "nonebot_plugin_rename"}]
```

### Comparing `nonebot_plugin_rename-1.5.6/PKG-INFO` & `nonebot_plugin_rename-1.6.0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: nonebot-plugin-rename
-Version: 1.5.6
+Version: 1.6.0
 Summary: 更改qq机器人的群名片，内置多种有趣名片
 License: GPL-3.0
 Author: forchannot
 Author-email: yy320206@gmail.com
 Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Programming Language :: Python :: 3
@@ -40,24 +40,23 @@
     <img src="https://img.shields.io/pypi/v/nonebot-plugin-rename.svg" alt="pypi">
 </a>
 <img src="https://img.shields.io/badge/python-3.8+-yellow.svg" alt="python">
 
 </div>
 
 <!-- TOC -->
-* [nonebot-plugin-rename](#nonebot-plugin-rename)
-  * [📖简介](#简介)
-  * [🔐许可](#许可)
-  * [💿 安装方法](#-安装方法)
-  * [🏷️插件命令](#插件命令)
-  * [⚙️插件配置项](#插件配置项)
-  * [🎉目前已实现的群名片功能](#目前已实现的群名片功能)
-  * [🧐PR需知](#pr需知)
-  * [🔥鸣谢](#鸣谢)
-  <!-- TOC -->
+- [nonebot-plugin-rename](#nonebot-plugin-rename)
+  - [📖简介](#简介)
+  - [🔐许可](#许可)
+  - [💿 安装方法](#-安装方法)
+  - [🏷️插件命令](#️插件命令)
+  - [⚙️插件配置项](#️插件配置项)
+  - [🎉目前已实现的群名片功能](#目前已实现的群名片功能)
+  - [🧐PR需知](#pr需知)
+  - [🔥鸣谢](#鸣谢)
 
 ## 📖简介
 
 通过定时任务更改bot(s)所在群自己的群名片
 
 ## 🔐许可
 
@@ -110,14 +109,15 @@
 | use_nickname_front            | 是否在群名片前加上bot名称              | bool | True           |
 | self_name                     | 自定义前缀(需开启上一个配置)             | str  | None           |
 | is_one_bot_set_all_group_card | 是否允许与单个bot会话可以设置所有bot所在的群名片 | bool | False          |
 | is_show_aps_info_log          | 是否显示定时任务的info级别日志           | bool | True           |
 | is_show_hot_search_from       | 热搜是否显示来源                    | bool | False          |
 | zk_time_start                 | 中考开始时间                      | str  | 06-12 09:00:00 |
 | zk_time_end                   | 中考结束时间                      | str  | 06-14 11:00:00 |
+| hot_search_url                | 热搜获取API，1为作者提供，2为tenapi| int  | 1 |
 
 **如果要使用中考剩余时间，由于每个地方中考时间并不统一，请务必填写`zk_time`系列配置项，否则获取的时间并不是你们当地的中考时间节点（开始和结束时间），参考配置如下**
 ```dotenv
 zk_time_start="06-12 09:00:00"
 zk_time_end="06-14 11:00:00"
 ```
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: nonebot-plugin-rename Version: 1.5.6 Summary:
+Metadata-Version: 2.1 Name: nonebot-plugin-rename Version: 1.6.0 Summary:
 æ´æ¹qqæºå¨äººçç¾¤åçï¼åç½®å¤ç§æè¶£åç License: GPL-3.0
 Author: forchannot Author-email: yy320206@gmail.com Requires-Python: >=3.8,<4.0
 Classifier: License :: OSI Approved :: GNU General Public License v3 (GPLv3)
 Classifier: Programming Language :: Python :: 3 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
 Classifier: Programming Language :: Python :: 3.10 Classifier: Programming
 Language :: Python :: 3.11 Requires-Dist: httpx (>=0.20.0,<1.0.0) Requires-
@@ -11,20 +11,20 @@
 Dist: pillow (>=9.5.0,<10.0.0) Requires-Dist: psutil (>=5.9.5,<6.0.0) Requires-
 Dist: pyyaml (>=6.0,<7.0) Description-Content-Type: text/markdown
                              [NoneBotPluginLogo]
                               [NoneBotPluginText]
                          # nonebot-plugin-rename _â¨
 éè¿å®æ¶ä»»å¡æ´æ¹botæå¨ç¾¤èªå·±çç¾¤åç,åç½®äºå ç§å¸¸è§çç¾¤åçå¹¶ä¸åæ­¥æ¯æäºå¤bot,æ¬¢è¿**pr**æ°çç¾¤åç!
                         â¨_ [license] [pypi] [python]
- * [nonebot-plugin-rename](#nonebot-plugin-rename) * [ðç®ä»](#ç®ä») *
-[ðè®¸å¯](#è®¸å¯) * [ð¿ å®è£æ¹æ³](#-å®è£æ¹æ³) *
-[ð·ï¸æä»¶å½ä»¤](#æä»¶å½ä»¤) * [âï¸æä»¶éç½®é¡¹]
-(#æä»¶éç½®é¡¹) * [ðç®åå·²å®ç°çç¾¤åçåè½]
-(#ç®åå·²å®ç°çç¾¤åçåè½) * [ð§PRéç¥](#préç¥) * [ð¥é¸£è°¢]
-(#é¸£è°¢)  ## ðç®ä» éè¿å®æ¶ä»»å¡æ´æ¹bot
+ - [nonebot-plugin-rename](#nonebot-plugin-rename) - [ðç®ä»](#ç®ä») -
+[ðè®¸å¯](#è®¸å¯) - [ð¿ å®è£æ¹æ³](#-å®è£æ¹æ³) -
+[ð·ï¸æä»¶å½ä»¤](#ï¸æä»¶å½ä»¤) - [âï¸æä»¶éç½®é¡¹]
+(#ï¸æä»¶éç½®é¡¹) - [ðç®åå·²å®ç°çç¾¤åçåè½]
+(#ç®åå·²å®ç°çç¾¤åçåè½) - [ð§PRéç¥](#préç¥) - [ð¥é¸£è°¢]
+(#é¸£è°¢) ## ðç®ä» éè¿å®æ¶ä»»å¡æ´æ¹bot
 (s)æå¨ç¾¤èªå·±çç¾¤åç ## ðè®¸å¯ [MIT](https://github.com/
 forchannot/nonebot-plugin-rename/blob/main/LICENSE) ## ð¿ å®è£æ¹æ³
 ä½¿ç¨ nb-cli å®è£ å¨ nonebot2 é¡¹ç®çæ ¹ç®å½ä¸æå¼å½ä»¤è¡,
 è¾å¥ä»¥ä¸æä»¤å³å¯å®è£ nb plugin install nonebot-plugin-rename   pip
 pip install nonebot-plugin-rename æå¼ nonebot2 é¡¹ç®æ ¹ç®å½ä¸ç
 `pyproject.toml` æä»¶, å¨ `[tool.nonebot]` é¨åè¿½å åå¥ plugins =
 ["nonebot_plugin_rename"] ``` [tool.nonebot] plugins = [] plugin_dirs = ["src/
@@ -44,15 +44,16 @@
 æ¯å¦å¨ç¾¤åçåå ä¸botåç§° | bool | True | | self_name |
 èªå®ä¹åç¼(éå¼å¯ä¸ä¸ä¸ªéç½®) | str | None | |
 is_one_bot_set_all_group_card |
 æ¯å¦åè®¸ä¸åä¸ªbotä¼è¯å¯ä»¥è®¾ç½®ææbotæå¨çç¾¤åç | bool |
 False | | is_show_aps_info_log | æ¯å¦æ¾ç¤ºå®æ¶ä»»å¡çinfoçº§å«æ¥å¿ |
 bool | True | | is_show_hot_search_from | ç­ææ¯å¦æ¾ç¤ºæ¥æº | bool |
 False | | zk_time_start | ä¸­èå¼å§æ¶é´ | str | 06-12 09:00:00 | |
-zk_time_end | ä¸­èç»ææ¶é´ | str | 06-14 11:00:00 |
+zk_time_end | ä¸­èç»ææ¶é´ | str | 06-14 11:00:00 | | hot_search_url |
+ç­æè·åAPIï¼1ä¸ºä½èæä¾ï¼2ä¸ºtenapi| int | 1 |
 **å¦æè¦ä½¿ç¨ä¸­èå©ä½æ¶é´ï¼ç±äºæ¯ä¸ªå°æ¹ä¸­èæ¶é´å¹¶ä¸ç»ä¸ï¼è¯·å¡å¿å¡«å`zk_time`ç³»åéç½®é¡¹ï¼å¦åè·åçæ¶é´å¹¶ä¸æ¯ä½ ä»¬å½å°çä¸­èæ¶é´èç¹ï¼å¼å§åç»ææ¶é´ï¼ï¼åèéç½®å¦ä¸**
 ```dotenv zk_time_start="06-12 09:00:00" zk_time_end="06-14 11:00:00" ```
 **è¯·æ³¨æä¸è¦å°`set_group_card_hour`å`set_group_card_minute`é½è®¾ä¸º0**
 **ç±äºqqç¾¤åçç¹æ®æ§,é´éå¤ªç­å¯è½æä¹å¹¶ä¸å¤§åèå®¹æå¯¼è´é£æ§,å»ºè®®å¨30åéä»¥ä¸**
 ## ðç®åå·²å®ç°çç¾¤åçåè½  ä¸å¾æµ [help]   æ¶é´
 -- é«èæ¶é´
 -- ä¸­èæ¶é´
```


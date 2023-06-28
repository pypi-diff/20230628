# Comparing `tmp/nonebot_plugin_talk_with_chatgpt-0.6.0.tar.gz` & `tmp/nonebot_plugin_talk_with_chatgpt-0.6.1.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nonebot_plugin_talk_with_chatgpt-0.6.0.tar", max compression
+gzip compressed data, was "nonebot_plugin_talk_with_chatgpt-0.6.1.tar", max compression
```

## Comparing `nonebot_plugin_talk_with_chatgpt-0.6.0.tar` & `nonebot_plugin_talk_with_chatgpt-0.6.1.tar`

### file list

```diff
@@ -1,7 +1,7 @@
--rw-r--r--   0        0        0    10762 2023-06-06 06:19:54.130482 nonebot_plugin_talk_with_chatgpt-0.6.0/nonebot_plugin_talk_with_chatgpt/__init__.py
--rw-r--r--   0        0        0    14035 2023-06-06 06:18:10.409339 nonebot_plugin_talk_with_chatgpt-0.6.0/nonebot_plugin_talk_with_chatgpt/config.py
--rw-r--r--   0        0        0     6397 2023-06-06 06:12:19.089000 nonebot_plugin_talk_with_chatgpt-0.6.0/nonebot_plugin_talk_with_chatgpt/data_handle.py
--rw-r--r--   0        0        0  7232220 2023-01-06 09:31:31.000000 nonebot_plugin_talk_with_chatgpt-0.6.0/nonebot_plugin_talk_with_chatgpt/HYWenHei-85W.ttf
--rw-r--r--   0        0        0      994 2023-06-06 06:47:18.019759 nonebot_plugin_talk_with_chatgpt-0.6.0/pyproject.toml
--rw-r--r--   0        0        0     6039 2023-06-06 06:47:10.419571 nonebot_plugin_talk_with_chatgpt-0.6.0/README.md
--rw-r--r--   0        0        0     6977 1970-01-01 00:00:00.000000 nonebot_plugin_talk_with_chatgpt-0.6.0/PKG-INFO
+-rw-r--r--   0        0        0    10755 2023-06-27 15:17:02.686329 nonebot_plugin_talk_with_chatgpt-0.6.1/nonebot_plugin_talk_with_chatgpt/__init__.py
+-rw-r--r--   0        0        0    14035 2023-06-06 06:18:10.409339 nonebot_plugin_talk_with_chatgpt-0.6.1/nonebot_plugin_talk_with_chatgpt/config.py
+-rw-r--r--   0        0        0     6397 2023-06-06 06:12:19.089000 nonebot_plugin_talk_with_chatgpt-0.6.1/nonebot_plugin_talk_with_chatgpt/data_handle.py
+-rw-r--r--   0        0        0  7232220 2023-01-06 09:31:31.000000 nonebot_plugin_talk_with_chatgpt-0.6.1/nonebot_plugin_talk_with_chatgpt/HYWenHei-85W.ttf
+-rw-r--r--   0        0        0      994 2023-06-28 03:41:50.273493 nonebot_plugin_talk_with_chatgpt-0.6.1/pyproject.toml
+-rw-r--r--   0        0        0     6040 2023-06-28 03:42:12.597928 nonebot_plugin_talk_with_chatgpt-0.6.1/README.md
+-rw-r--r--   0        0        0     6978 1970-01-01 00:00:00.000000 nonebot_plugin_talk_with_chatgpt-0.6.1/PKG-INFO
```

### Comparing `nonebot_plugin_talk_with_chatgpt-0.6.0/nonebot_plugin_talk_with_chatgpt/__init__.py` & `nonebot_plugin_talk_with_chatgpt-0.6.1/nonebot_plugin_talk_with_chatgpt/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -47,29 +47,29 @@
     if id not in var.session_data:
         var.session_data[id] = ["", "", "默认"]
     return id
 
 
 async def rule_check(event: MessageEvent, bot: Bot) -> bool:
     """对话响应判断"""
-    # bot判断
-    if pc.talk_with_chatgpt_bot_qqnum_list != ["all"] and bot != var.handle_bot:
-        return False
 
     # 获取纯文本
     text = event.get_plaintext().strip()
 
     if isinstance(event, GroupMessageEvent):
         # 判断是否启用
         if (
             pc.talk_with_chatgpt_all_group_enable is False
             and event.group_id not in var.enable_group_list
         ):
             return False
 
+        if pc.talk_with_chatgpt_bot_qqnum_list != ["all"] and bot != var.handle_bot:
+            return False
+
         # 仅艾特但没发内容
         if event.is_tome() and pc.talk_with_chatgpt_talk_at:
             if text:
                 return True
             else:
                 return False
```

### Comparing `nonebot_plugin_talk_with_chatgpt-0.6.0/nonebot_plugin_talk_with_chatgpt/config.py` & `nonebot_plugin_talk_with_chatgpt-0.6.1/nonebot_plugin_talk_with_chatgpt/config.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_talk_with_chatgpt-0.6.0/nonebot_plugin_talk_with_chatgpt/data_handle.py` & `nonebot_plugin_talk_with_chatgpt-0.6.1/nonebot_plugin_talk_with_chatgpt/data_handle.py`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_talk_with_chatgpt-0.6.0/nonebot_plugin_talk_with_chatgpt/HYWenHei-85W.ttf` & `nonebot_plugin_talk_with_chatgpt-0.6.1/nonebot_plugin_talk_with_chatgpt/HYWenHei-85W.ttf`

 * *Files identical despite different names*

### Comparing `nonebot_plugin_talk_with_chatgpt-0.6.0/pyproject.toml` & `nonebot_plugin_talk_with_chatgpt-0.6.1/pyproject.toml`

 * *Files 10% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [tool.poetry]
 name = "nonebot_plugin_talk_with_chatgpt"
-version = "0.6.0"
+version = "0.6.1"
 description = "Nonebot2 基于accessToken登录的ChatGPT聊天插件"
 authors = ["nikissXI <1299577815@qq.com>"]
 license = "MIT"
 readme = "README.md"
 packages = [{include = "nonebot_plugin_talk_with_chatgpt"}]
 homepage = "https://github.com/nikissXI/nonebot_plugins/tree/main/nonebot_plugin_talk_with_chatgpt"
 repository = "https://github.com/nikissXI/nonebot_plugins/tree/main/nonebot_plugin_talk_with_chatgpt"
```

### Comparing `nonebot_plugin_talk_with_chatgpt-0.6.0/README.md` & `nonebot_plugin_talk_with_chatgpt-0.6.1/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -109,15 +109,15 @@
 | /talk | 开始对话，默认群里@机器人也可以 |
 | /hi | 沉浸式对话（仅限私聊） |
 | /reset | 重置对话（不会重置预设） |
 | /prompt | 设置预设（人格），设置后会重置对话 |
 | /chatgpt | 设置预设（人格），设置后会重置对话 |
 
 ## 更新日志
-### 2023/6/6 \[v0.6.0]
+### 2023/6/28 \[v0.6.1]
 
 * 新增配置项 talk_with_chatgpt_send_with_img 和 talk_with_chatgpt_ban_word
 
 ### 2023/5/30 \[v0.5.0]
 
 * 更换了自带预设“猫娘”的内容，新增配置项 talk_with_chatgpt_all_group_enable 和 talk_with_chatgpt_group_enable_cmd ，新增命令/chatgpt
```

#### html2text {}

```diff
@@ -59,15 +59,15 @@
 å¦æä½¿ç¨å¾çåå¤ï¼å­ä½å¤§å° talk_with_chatgpt_font_size = 18 ``` ##
 æä»¶å½ä»¤ï¼åå¯ä¿®æ¹ï¼ï¼ | æä»¤ | è¯´æ | |:-----:|:----:| | /talk
 | å¼å§å¯¹è¯ï¼é»è®¤ç¾¤é@æºå¨äººä¹å¯ä»¥ | | /hi |
 æ²æµ¸å¼å¯¹è¯ï¼ä»éç§èï¼ | | /reset |
 éç½®å¯¹è¯ï¼ä¸ä¼éç½®é¢è®¾ï¼ | | /prompt |
 è®¾ç½®é¢è®¾ï¼äººæ ¼ï¼ï¼è®¾ç½®åä¼éç½®å¯¹è¯ | | /chatgpt |
 è®¾ç½®é¢è®¾ï¼äººæ ¼ï¼ï¼è®¾ç½®åä¼éç½®å¯¹è¯ | ## æ´æ°æ¥å¿ ### 2023/
-6/6 \[v0.6.0] * æ°å¢éç½®é¡¹ talk_with_chatgpt_send_with_img å
+6/28 \[v0.6.1] * æ°å¢éç½®é¡¹ talk_with_chatgpt_send_with_img å
 talk_with_chatgpt_ban_word ### 2023/5/30 \[v0.5.0] *
 æ´æ¢äºèªå¸¦é¢è®¾âç«å¨âçåå®¹ï¼æ°å¢éç½®é¡¹
 talk_with_chatgpt_all_group_enable å talk_with_chatgpt_group_enable_cmd
 ï¼æ°å¢å½ä»¤/chatgpt ### 2023/5/29 \[v0.4.3] *
 [æ¯ææææºå¨äººååºå½ä»¤](https://github.com/nikissXI/
 nonebot_plugins/issues/22) ### 2023/5/18 \[v0.4.2] *
 [ä¿®å¤ä¼è¯ä¸¢å¤±ä¸éç½®çé®é¢](https://github.com/nikissXI/
```

### Comparing `nonebot_plugin_talk_with_chatgpt-0.6.0/PKG-INFO` & `nonebot_plugin_talk_with_chatgpt-0.6.1/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: nonebot-plugin-talk-with-chatgpt
-Version: 0.6.0
+Version: 0.6.1
 Summary: Nonebot2 基于accessToken登录的ChatGPT聊天插件
 Home-page: https://github.com/nikissXI/nonebot_plugins/tree/main/nonebot_plugin_talk_with_chatgpt
 License: MIT
 Author: nikissXI
 Author-email: 1299577815@qq.com
 Requires-Python: >=3.8
 Classifier: License :: OSI Approved :: MIT License
@@ -133,15 +133,15 @@
 | /talk | 开始对话，默认群里@机器人也可以 |
 | /hi | 沉浸式对话（仅限私聊） |
 | /reset | 重置对话（不会重置预设） |
 | /prompt | 设置预设（人格），设置后会重置对话 |
 | /chatgpt | 设置预设（人格），设置后会重置对话 |
 
 ## 更新日志
-### 2023/6/6 \[v0.6.0]
+### 2023/6/28 \[v0.6.1]
 
 * 新增配置项 talk_with_chatgpt_send_with_img 和 talk_with_chatgpt_ban_word
 
 ### 2023/5/30 \[v0.5.0]
 
 * 更换了自带预设“猫娘”的内容，新增配置项 talk_with_chatgpt_all_group_enable 和 talk_with_chatgpt_group_enable_cmd ，新增命令/chatgpt
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: nonebot-plugin-talk-with-chatgpt Version: 0.6.0
+Metadata-Version: 2.1 Name: nonebot-plugin-talk-with-chatgpt Version: 0.6.1
 Summary: Nonebot2 åºäºaccessTokenç»å½çChatGPTèå¤©æä»¶ Home-page:
 https://github.com/nikissXI/nonebot_plugins/tree/main/
 nonebot_plugin_talk_with_chatgpt License: MIT Author: nikissXI Author-email:
 1299577815@qq.com Requires-Python: >=3.8 Classifier: License :: OSI Approved ::
 MIT License Classifier: Programming Language :: Python :: 3 Classifier:
 Programming Language :: Python :: 3.8 Classifier: Programming Language ::
 Python :: 3.9 Classifier: Programming Language :: Python :: 3.10 Classifier:
@@ -74,15 +74,15 @@
 å¦æä½¿ç¨å¾çåå¤ï¼å­ä½å¤§å° talk_with_chatgpt_font_size = 18 ``` ##
 æä»¶å½ä»¤ï¼åå¯ä¿®æ¹ï¼ï¼ | æä»¤ | è¯´æ | |:-----:|:----:| | /talk
 | å¼å§å¯¹è¯ï¼é»è®¤ç¾¤é@æºå¨äººä¹å¯ä»¥ | | /hi |
 æ²æµ¸å¼å¯¹è¯ï¼ä»éç§èï¼ | | /reset |
 éç½®å¯¹è¯ï¼ä¸ä¼éç½®é¢è®¾ï¼ | | /prompt |
 è®¾ç½®é¢è®¾ï¼äººæ ¼ï¼ï¼è®¾ç½®åä¼éç½®å¯¹è¯ | | /chatgpt |
 è®¾ç½®é¢è®¾ï¼äººæ ¼ï¼ï¼è®¾ç½®åä¼éç½®å¯¹è¯ | ## æ´æ°æ¥å¿ ### 2023/
-6/6 \[v0.6.0] * æ°å¢éç½®é¡¹ talk_with_chatgpt_send_with_img å
+6/28 \[v0.6.1] * æ°å¢éç½®é¡¹ talk_with_chatgpt_send_with_img å
 talk_with_chatgpt_ban_word ### 2023/5/30 \[v0.5.0] *
 æ´æ¢äºèªå¸¦é¢è®¾âç«å¨âçåå®¹ï¼æ°å¢éç½®é¡¹
 talk_with_chatgpt_all_group_enable å talk_with_chatgpt_group_enable_cmd
 ï¼æ°å¢å½ä»¤/chatgpt ### 2023/5/29 \[v0.4.3] *
 [æ¯ææææºå¨äººååºå½ä»¤](https://github.com/nikissXI/
 nonebot_plugins/issues/22) ### 2023/5/18 \[v0.4.2] *
 [ä¿®å¤ä¼è¯ä¸¢å¤±ä¸éç½®çé®é¢](https://github.com/nikissXI/
```


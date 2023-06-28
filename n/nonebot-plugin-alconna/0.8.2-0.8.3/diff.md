# Comparing `tmp/nonebot-plugin-alconna-0.8.2.tar.gz` & `tmp/nonebot-plugin-alconna-0.8.3.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "nonebot-plugin-alconna-0.8.2.tar", last modified: Sun Jun 25 15:31:35 2023, max compression
+gzip compressed data, was "nonebot-plugin-alconna-0.8.3.tar", last modified: Wed Jun 28 10:25:29 2023, max compression
```

## Comparing `nonebot-plugin-alconna-0.8.2.tar` & `nonebot-plugin-alconna-0.8.3.tar`

### file list

```diff
@@ -1,31 +1,31 @@
--rw-r--r--   0        0        0     1091 2022-01-24 11:14:57.524011 nonebot-plugin-alconna-0.8.2/LICENSE
--rw-r--r--   0        0        0     1524 2023-06-25 11:31:51.131389 nonebot-plugin-alconna-0.8.2/pyproject.toml
--rw-r--r--   0        0        0     8588 2023-06-22 14:46:56.528495 nonebot-plugin-alconna-0.8.2/README.md
--rw-r--r--   0        0        0     1912 2023-06-25 11:34:36.599625 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/__init__.py
--rw-r--r--   0        0        0     6259 2023-06-25 15:29:08.347891 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/__init__.py
--rw-r--r--   0        0        0      523 2023-05-31 10:32:51.256024 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/bilibili.py
--rw-r--r--   0        0        0     1052 2023-05-31 10:32:51.263057 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/console.py
--rw-r--r--   0        0        0     1661 2023-05-31 10:32:51.272058 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/ding.py
--rw-r--r--   0        0        0     2120 2023-05-31 10:32:51.280029 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/feishu.py
--rw-r--r--   0        0        0      519 2023-05-31 10:32:51.286108 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/github.py
--rw-r--r--   0        0        0     1163 2023-05-31 10:32:51.293032 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/kook.py
--rw-r--r--   0        0        0      761 2023-05-31 10:32:51.300025 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/minecraft.py
--rw-r--r--   0        0        0     3129 2023-05-31 10:32:51.308024 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/mirai.py
--rw-r--r--   0        0        0     1088 2023-05-31 10:32:51.314025 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/ntchat.py
--rw-r--r--   0        0        0     3151 2023-05-31 10:32:51.321077 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/onebot11.py
--rw-r--r--   0        0        0     2496 2023-05-31 10:32:51.327029 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/onebot12.py
--rw-r--r--   0        0        0     3251 2023-05-31 10:32:51.334314 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/qqguild.py
--rw-r--r--   0        0        0     3224 2023-06-22 16:21:04.989803 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/telegram.py
--rw-r--r--   0        0        0      579 2023-05-31 10:32:51.160062 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/argv.py
--rw-r--r--   0        0        0      405 2023-05-31 10:32:51.165611 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/config.py
--rw-r--r--   0        0        0      182 2023-05-31 10:31:14.855148 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/consts.py
--rw-r--r--   0        0        0      109 2023-05-11 15:42:43.320472 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/i18n/.config.json
--rw-r--r--   0        0        0      301 2023-05-11 15:42:18.920450 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/i18n/en-US.json
--rw-r--r--   0        0        0      262 2023-05-11 15:42:18.885191 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/i18n/zh-CN.json
--rw-r--r--   0        0        0     2277 2023-06-01 08:39:16.821566 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/matcher.py
--rw-r--r--   0        0        0     1091 2023-05-31 10:32:51.198463 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/matcher.pyi
--rw-r--r--   0        0        0     1478 2023-05-31 10:32:51.204511 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/model.py
--rw-r--r--   0        0        0     3830 2023-05-31 10:32:51.214457 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/params.py
--rw-r--r--   0        0        0     8722 2023-05-31 10:32:51.231456 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/rule.py
--rw-r--r--   0        0        0     2295 2023-06-22 14:54:15.807613 nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/typings.py
--rw-r--r--   0        0        0     8665 1970-01-01 00:00:00.000000 nonebot-plugin-alconna-0.8.2/PKG-INFO
+-rw-r--r--   0        0        0     1091 2022-01-24 11:14:57.524011 nonebot-plugin-alconna-0.8.3/LICENSE
+-rw-r--r--   0        0        0     1524 2023-06-28 10:25:15.563405 nonebot-plugin-alconna-0.8.3/pyproject.toml
+-rw-r--r--   0        0        0     8588 2023-06-22 14:46:56.528495 nonebot-plugin-alconna-0.8.3/README.md
+-rw-r--r--   0        0        0     1912 2023-06-28 10:25:15.573556 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/__init__.py
+-rw-r--r--   0        0        0     6259 2023-06-25 15:29:08.347891 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/__init__.py
+-rw-r--r--   0        0        0      523 2023-05-31 10:32:51.256024 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/bilibili.py
+-rw-r--r--   0        0        0     1052 2023-05-31 10:32:51.263057 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/console.py
+-rw-r--r--   0        0        0     1661 2023-05-31 10:32:51.272058 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/ding.py
+-rw-r--r--   0        0        0     2120 2023-05-31 10:32:51.280029 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/feishu.py
+-rw-r--r--   0        0        0      519 2023-05-31 10:32:51.286108 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/github.py
+-rw-r--r--   0        0        0     1163 2023-05-31 10:32:51.293032 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/kook.py
+-rw-r--r--   0        0        0      761 2023-05-31 10:32:51.300025 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/minecraft.py
+-rw-r--r--   0        0        0     3129 2023-05-31 10:32:51.308024 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/mirai.py
+-rw-r--r--   0        0        0     1088 2023-05-31 10:32:51.314025 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/ntchat.py
+-rw-r--r--   0        0        0     3151 2023-05-31 10:32:51.321077 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/onebot11.py
+-rw-r--r--   0        0        0     2496 2023-05-31 10:32:51.327029 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/onebot12.py
+-rw-r--r--   0        0        0     3251 2023-05-31 10:32:51.334314 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/qqguild.py
+-rw-r--r--   0        0        0     3224 2023-06-22 16:21:04.989803 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/telegram.py
+-rw-r--r--   0        0        0      579 2023-05-31 10:32:51.160062 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/argv.py
+-rw-r--r--   0        0        0      405 2023-05-31 10:32:51.165611 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/config.py
+-rw-r--r--   0        0        0      182 2023-05-31 10:31:14.855148 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/consts.py
+-rw-r--r--   0        0        0      109 2023-05-11 15:42:43.320472 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/i18n/.config.json
+-rw-r--r--   0        0        0      301 2023-05-11 15:42:18.920450 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/i18n/en-US.json
+-rw-r--r--   0        0        0      262 2023-05-11 15:42:18.885191 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/i18n/zh-CN.json
+-rw-r--r--   0        0        0     2277 2023-06-01 08:39:16.821566 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/matcher.py
+-rw-r--r--   0        0        0     1091 2023-05-31 10:32:51.198463 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/matcher.pyi
+-rw-r--r--   0        0        0     1478 2023-05-31 10:32:51.204511 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/model.py
+-rw-r--r--   0        0        0     3830 2023-05-31 10:32:51.214457 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/params.py
+-rw-r--r--   0        0        0     8779 2023-06-28 10:23:05.446107 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/rule.py
+-rw-r--r--   0        0        0     2295 2023-06-22 14:54:15.807613 nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/typings.py
+-rw-r--r--   0        0        0     8665 1970-01-01 00:00:00.000000 nonebot-plugin-alconna-0.8.3/PKG-INFO
```

### Comparing `nonebot-plugin-alconna-0.8.2/LICENSE` & `nonebot-plugin-alconna-0.8.3/LICENSE`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/pyproject.toml` & `nonebot-plugin-alconna-0.8.3/pyproject.toml`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [project]
 name = "nonebot-plugin-alconna"
-version = "0.8.2"
+version = "0.8.3"
 description = "Alconna Adapter for Nonebot"
 authors = [
     { name = "RF-Tar-Railt", email = "rf_tar_railt@qq.com" },
 ]
 dependencies = [
     "nonebot2>=2.0.0rc4",
     "arclet-alconna<2.0.0, >=1.7.7",
```

### Comparing `nonebot-plugin-alconna-0.8.2/README.md` & `nonebot-plugin-alconna-0.8.3/README.md`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/__init__.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/__init__.py`

 * *Files 7% similar despite different names*

```diff
@@ -18,15 +18,15 @@
 from .params import assign as assign
 from .params import match_path as match_path
 from .params import match_value as match_value
 from .rule import alconna as alconna
 from .rule import set_output_converter as set_output_converter
 from .config import Config
 
-__version__ = "0.8.2"
+__version__ = "0.8.3"
 
 _meta_source = {
     "name": "Alconna 插件",
     "description": "提供 [Alconna](https://github.com/ArcletProject/Alconna) 的 Nonebot2 适配版本与工具",
     "usage": "matcher = on_alconna(...)",
     "homepage": "https://github.com/ArcletProject/Alconna",
     "type": "library",
```

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/__init__.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/__init__.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/bilibili.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/bilibili.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/console.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/console.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/ding.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/ding.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/feishu.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/feishu.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/github.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/github.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/kook.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/kook.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/minecraft.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/minecraft.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/mirai.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/mirai.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/ntchat.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/ntchat.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/onebot11.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/onebot11.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/onebot12.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/onebot12.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/qqguild.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/qqguild.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/adapters/telegram.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/adapters/telegram.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/argv.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/argv.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/matcher.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/matcher.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/matcher.pyi` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/matcher.pyi`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/model.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/model.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/params.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/params.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/rule.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/rule.py`

 * *Files 2% similar despite different names*

```diff
@@ -89,18 +89,19 @@
     def __hash__(self) -> int:
         return hash(self.command.__hash__())
 
     async def handle(self, bot: Bot, event: Event, msg: Message):
         interface = CompSession(self.command)
         if self.comp_config is None:
             return self.command.parse(msg)
-
+        res = None
         with interface:
             res = self.command.parse(msg)
-
+        if res:
+            return res
         meta = CommandMeta(compact=True, hide=True)
         _tab = Alconna(self.comp_config.get("tab", ".tab"), Args["offset", int, 1], [], meta=meta)
         _enter = Alconna(self.comp_config.get("enter", ".enter"), Args["content", AllParam, []], [], meta=meta)
         _exit = Alconna(self.comp_config.get("exit", ".exit"), [], meta=meta)
 
         _waiter = on_message(priority=self.comp_config.get('priority', -1), block=True)
         _futures: Dict[str, asyncio.Future] = {}
```

### Comparing `nonebot-plugin-alconna-0.8.2/src/nonebot_plugin_alconna/typings.py` & `nonebot-plugin-alconna-0.8.3/src/nonebot_plugin_alconna/typings.py`

 * *Files identical despite different names*

### Comparing `nonebot-plugin-alconna-0.8.2/PKG-INFO` & `nonebot-plugin-alconna-0.8.3/PKG-INFO`

 * *Files 0% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: nonebot-plugin-alconna
-Version: 0.8.2
+Version: 0.8.3
 Summary: Alconna Adapter for Nonebot
 License: MIT
 Keywords: command,argparse,cli,alconna,nonebot
 Author-email: RF-Tar-Railt <rf_tar_railt@qq.com>
 Requires-Python: >=3.8
 Project-URL: repository, https://github.com/ArcletProject/nonebot-plugin-alconna
 Description-Content-Type: text/markdown
```


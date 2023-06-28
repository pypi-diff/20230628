# Comparing `tmp/ampalibe-1.1.9.tar.gz` & `tmp/ampalibe-1.2.0.1a0.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ampalibe-1.1.9.tar", last modified: Wed Jun 28 15:47:14 2023, max compression
+gzip compressed data, was "ampalibe-1.2.0.1a0.tar", last modified: Thu Mar 16 04:13:44 2023, max compression
```

## Comparing `ampalibe-1.1.9.tar` & `ampalibe-1.2.0.1a0.tar`

### file list

```diff
@@ -1,30 +1,31 @@
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:47:14.362877 ampalibe-1.1.9/
--rw-r--r--   0 runner    (1001) docker     (123)     1064 2023-06-28 15:46:58.000000 ampalibe-1.1.9/LICENSE
--rw-r--r--   0 runner    (1001) docker     (123)     9150 2023-06-28 15:47:14.362877 ampalibe-1.1.9/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)     6542 2023-06-28 15:46:58.000000 ampalibe-1.1.9/README.md
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:47:14.362877 ampalibe-1.1.9/ampalibe/
--rw-r--r--   0 runner    (1001) docker     (123)     5395 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/__init__.py
--rw-r--r--   0 runner    (1001) docker     (123)        0 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/__main__.py
--rw-r--r--   0 runner    (1001) docker     (123)      560 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/cmd.py
--rw-r--r--   0 runner    (1001) docker     (123)     1489 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/constant.py
--rw-r--r--   0 runner    (1001) docker     (123)     4153 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/core.py
--rw-r--r--   0 runner    (1001) docker     (123)     1163 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/decorators.py
--rw-r--r--   0 runner    (1001) docker     (123)     1285 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/logger.py
--rw-r--r--   0 runner    (1001) docker     (123)    38953 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/messenger.py
--rw-r--r--   0 runner    (1001) docker     (123)    10473 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/model.py
--rw-r--r--   0 runner    (1001) docker     (123)     1953 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/payload.py
--rw-r--r--   0 runner    (1001) docker     (123)     2650 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/source.py
--rw-r--r--   0 runner    (1001) docker     (123)     4163 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/tools.py
--rw-r--r--   0 runner    (1001) docker     (123)    11062 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/ui.py
--rw-r--r--   0 runner    (1001) docker     (123)     2006 2023-06-28 15:46:58.000000 ampalibe-1.1.9/ampalibe/utils.py
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:47:14.362877 ampalibe-1.1.9/ampalibe.egg-info/
--rw-r--r--   0 runner    (1001) docker     (123)     9150 2023-06-28 15:47:14.000000 ampalibe-1.1.9/ampalibe.egg-info/PKG-INFO
--rw-r--r--   0 runner    (1001) docker     (123)      493 2023-06-28 15:47:14.000000 ampalibe-1.1.9/ampalibe.egg-info/SOURCES.txt
--rw-r--r--   0 runner    (1001) docker     (123)        1 2023-06-28 15:47:14.000000 ampalibe-1.1.9/ampalibe.egg-info/dependency_links.txt
--rw-r--r--   0 runner    (1001) docker     (123)       89 2023-06-28 15:47:14.000000 ampalibe-1.1.9/ampalibe.egg-info/requires.txt
--rw-r--r--   0 runner    (1001) docker     (123)        9 2023-06-28 15:47:14.000000 ampalibe-1.1.9/ampalibe.egg-info/top_level.txt
-drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-06-28 15:47:14.362877 ampalibe-1.1.9/bin/
--rwxr-xr-x   0 runner    (1001) docker     (123)     2789 2023-06-28 15:46:58.000000 ampalibe-1.1.9/bin/ampalibe
--rw-r--r--   0 runner    (1001) docker     (123)     1036 2023-06-28 15:46:58.000000 ampalibe-1.1.9/bin/ampalibe.bat
--rw-r--r--   0 runner    (1001) docker     (123)      809 2023-06-28 15:47:14.362877 ampalibe-1.1.9/setup.cfg
--rw-r--r--   0 runner    (1001) docker     (123)     1470 2023-06-28 15:46:58.000000 ampalibe-1.1.9/setup.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-16 04:13:44.027667 ampalibe-1.2.0.1a0/
+-rw-r--r--   0 runner    (1001) docker     (123)     1064 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/LICENSE
+-rw-r--r--   0 runner    (1001) docker     (123)     9156 2023-03-16 04:13:44.027667 ampalibe-1.2.0.1a0/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)     6544 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/README.md
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-16 04:13:44.023667 ampalibe-1.2.0.1a0/ampalibe/
+-rw-r--r--   0 runner    (1001) docker     (123)     5984 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/__init__.py
+-rw-r--r--   0 runner    (1001) docker     (123)        0 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/__main__.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4060 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/admin.py
+-rw-r--r--   0 runner    (1001) docker     (123)      560 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/cmd.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1602 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/constant.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4065 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/core.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1163 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/decorators.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1285 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/logger.py
+-rw-r--r--   0 runner    (1001) docker     (123)    38953 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/messenger.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11106 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/model.py
+-rw-r--r--   0 runner    (1001) docker     (123)     1953 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/payload.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4541 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/source.py
+-rw-r--r--   0 runner    (1001) docker     (123)     4596 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/tools.py
+-rw-r--r--   0 runner    (1001) docker     (123)    11062 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/ui.py
+-rw-r--r--   0 runner    (1001) docker     (123)     3312 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/ampalibe/utils.py
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-16 04:13:44.027667 ampalibe-1.2.0.1a0/ampalibe.egg-info/
+-rw-r--r--   0 runner    (1001) docker     (123)     9156 2023-03-16 04:13:43.000000 ampalibe-1.2.0.1a0/ampalibe.egg-info/PKG-INFO
+-rw-r--r--   0 runner    (1001) docker     (123)      511 2023-03-16 04:13:43.000000 ampalibe-1.2.0.1a0/ampalibe.egg-info/SOURCES.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        1 2023-03-16 04:13:43.000000 ampalibe-1.2.0.1a0/ampalibe.egg-info/dependency_links.txt
+-rw-r--r--   0 runner    (1001) docker     (123)      113 2023-03-16 04:13:43.000000 ampalibe-1.2.0.1a0/ampalibe.egg-info/requires.txt
+-rw-r--r--   0 runner    (1001) docker     (123)        9 2023-03-16 04:13:43.000000 ampalibe-1.2.0.1a0/ampalibe.egg-info/top_level.txt
+drwxr-xr-x   0 runner    (1001) docker     (123)        0 2023-03-16 04:13:44.027667 ampalibe-1.2.0.1a0/bin/
+-rwxr-xr-x   0 runner    (1001) docker     (123)     2789 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/bin/ampalibe
+-rw-r--r--   0 runner    (1001) docker     (123)     1066 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/bin/ampalibe.bat
+-rw-r--r--   0 runner    (1001) docker     (123)      812 2023-03-16 04:13:44.027667 ampalibe-1.2.0.1a0/setup.cfg
+-rw-r--r--   0 runner    (1001) docker     (123)     1529 2023-03-16 04:13:34.000000 ampalibe-1.2.0.1a0/setup.py
```

### Comparing `ampalibe-1.1.9/LICENSE` & `ampalibe-1.2.0.1a0/LICENSE`

 * *Files identical despite different names*

### Comparing `ampalibe-1.1.9/PKG-INFO` & `ampalibe-1.2.0.1a0/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ampalibe
-Version: 1.1.9
+Version: 1.2.0.1a0
 Summary: Ampalibe is a lightweight Python framework for building Facebook Messenger bots faster.
 Home-page: https://github.com/iTeam-S/ampalibe
 Author: iTeam-$
 Author-email: contact@iteam-s.mg
 License: UNKNOWN
 Project-URL: Bug Tracker, https://github.com/iTeam-S/ampalibe/issues
 Description: # Ampalibe
@@ -123,15 +123,15 @@
         from ampalibe.messenger import Action
         
         chat = Messenger()
         query = Model()
         
         @ampalibe.before_receive()
         def before_process(sender_id, **ext):
-            #  Put a view for each message received
+            #  Mark as seen for each message received
             chat.send_action(sender_id, Action.mark_seen)
             return True
         
         @ampalibe.command('/')
         def main(sender_id, cmd, **ext):
             """
             No need to manage weebhooks and data: messages are received directly in a main function
```

### Comparing `ampalibe-1.1.9/README.md` & `ampalibe-1.2.0.1a0/README.md`

 * *Files 1% similar despite different names*

```diff
@@ -114,15 +114,15 @@
 from ampalibe.messenger import Action
 
 chat = Messenger()
 query = Model()
 
 @ampalibe.before_receive()
 def before_process(sender_id, **ext):
-    #  Put a view for each message received
+    #  Mark as seen for each message received
     chat.send_action(sender_id, Action.mark_seen)
     return True
 
 @ampalibe.command('/')
 def main(sender_id, cmd, **ext):
     """
     No need to manage weebhooks and data: messages are received directly in a main function
```

### Comparing `ampalibe-1.1.9/ampalibe/__init__.py` & `ampalibe-1.2.0.1a0/ampalibe/__init__.py`

 * *Files 6% similar despite different names*

```diff
@@ -2,15 +2,15 @@
 import sys
 import time
 import inspect
 import colorama
 import tempfile
 from . import source
 
-__version__ = "1.1.9"
+__version__ = "1.2.0.1a"
 __author__ = "iTeam-$"
 
 
 colorama.init()
 
 
 def typing_print(text):
@@ -30,17 +30,31 @@
 
 
 def create_lang(path):
     print(source.LANGS, file=open(f"{path}/langs.json", "w"))
     typing_print("~\033[32m 👌 \033[0m | Langs file created")
 
 
+def create_models(path):
+    print(source.MODELS, file=open(f"{path}/models.py", "w"))
+    typing_print("~\033[32m 👌 \033[0m | Models file created")
+
+
+def create_resources(path):
+    print(source.RESOURCES, file=open(f"{path}/resources.py", "w"))
+    typing_print("~\033[32m 👌 \033[0m | Resources file created")
+    os.makedirs(f"{path}/templates", exist_ok=True)
+    print(source.OTHER_HTML, file=open(f"{path}/templates/other.html", "w"))
+
+
 def init_proj(path):
     create_env(path)
     create_lang(path)
+    create_models(path)
+    create_resources(path)
     print(source.CORE, file=open(f"{path}/core.py", "w"))
     typing_print("~\033[32m 👌 \033[0m | Core file created")
 
     print(source.CONF, file=open(f"{path}/conf.py", "w"))
     typing_print("~\033[32m 👌 \033[0m | Config file created")
 
     for folder in {"public", "private"}:
@@ -150,15 +164,21 @@
     from .constant import *
     from .model import Model
     from .logger import Logger
     from aiocron import crontab
     from .payload import Payload
     from .messenger import Messenger
     from .core import webserver, Init as init
-    from .utils import translate, download_file, simulate
+    from .utils import (
+        translate,
+        download_file,
+        async_download_file,
+        simulate,
+        async_simulate,
+    )
     from .decorators import (
         event,
         action,
         command,
         before_receive,
         after_receive,
     )
```

### Comparing `ampalibe-1.1.9/ampalibe/cmd.py` & `ampalibe-1.2.0.1a0/ampalibe/cmd.py`

 * *Files identical despite different names*

### Comparing `ampalibe-1.1.9/ampalibe/constant.py` & `ampalibe-1.2.0.1a0/ampalibe/constant.py`

 * *Files 6% similar despite different names*

```diff
@@ -1,9 +1,11 @@
 from enum import Enum
 
+AMPALIBE_LOGO = "https://raw.githubusercontent.com/iTeam-S/Ampalibe/main/docs/source/_static/ampalibe_logo.png"
+
 
 class Content_type:
     text = "text"
     user_phone_number = "user_phone_number"
     user_email = "user_email"
```

### Comparing `ampalibe-1.1.9/ampalibe/core.py` & `ampalibe-1.2.0.1a0/ampalibe/core.py`

 * *Files 10% similar despite different names*

```diff
@@ -11,19 +11,24 @@
 from fastapi.staticfiles import StaticFiles
 from fastapi import FastAPI, Request, Response
 from .tools import funcs, analyse, before_run, send_next, verif_event
 
 _req = Model(init=False)
 loop = asyncio.get_event_loop()
 
-webserver = FastAPI(title="Ampalibe server")
+
+webserver = FastAPI()
 if not os.path.isdir("assets/public"):
     os.makedirs("assets/public", exist_ok=True)
 
 webserver.mount("/asset", StaticFiles(directory="assets/public"), name="asset")
+if hasattr(Configuration, "ADMIN_ENABLE") and Configuration.ADMIN_ENABLE:
+    from .admin import init_admin
+
+    init_admin(webserver)
 
 
 class Init:
     def __init__(self, *args):
         self.query = Model()
         self.chat = Messenger()
 
@@ -77,15 +82,15 @@
         except json.decoder.JSONDecodeError:
             return "..."
 
         # data analysis and decomposition
         sender_id, payload, message = analyse(data)
 
         if payload.webhook in ("read", "delivery", "reaction"):
-            verif_event(sender_id, payload, message, testmode)
+            await verif_event(sender_id, payload, message, testmode)
             return {"status": "ok"}
 
         _req._verif_user(sender_id)
         action, lang = _req.get(sender_id, "action", "lang")
 
         if payload in ("/__next", "/__more"):
             send_next(sender_id, payload)
@@ -105,37 +110,28 @@
         )
 
         command = funcs["command"].get(payload.split()[0])
 
         if command:
             _req.set_action(sender_id, None)
             if testmode:
-                return before_run(command, **kw)
-            else:
-                Thread(
-                    target=before_run,
-                    args=(command,),
-                    kwargs=kw,
-                ).start()
+                return await before_run(command, **kw)
+            asyncio.create_task(before_run(command, **kw))
         elif action:
             action, kw_tmp = Payload.trt_payload_in(action)
             kw.update(kw_tmp)
 
             if funcs["action"].get(action):
                 if testmode:
-                    return before_run(funcs["action"].get(action), **kw)
-                Thread(
-                    target=before_run,
-                    args=(funcs["action"].get(action),),
-                    kwargs=kw,
-                ).start()
+                    return await before_run(funcs["action"].get(action), **kw)
+                asyncio.create_task(before_run(funcs["action"].get(action), **kw))
             else:
                 Logger.error(f'⚠ Error! action "{action}" undeclared ')
         else:
             command = funcs["command"].get("/")
             if command:
                 if testmode:
-                    return before_run(command, **kw)
-                Thread(target=before_run, args=(command,), kwargs=kw).start()
+                    return await before_run(command, **kw)
+                asyncio.create_task(before_run(command, **kw))
             else:
                 Logger.error("⚠ Error! Default route '/' function undeclared.")
         return {"status": "ok"}
```

### Comparing `ampalibe-1.1.9/ampalibe/decorators.py` & `ampalibe-1.2.0.1a0/ampalibe/decorators.py`

 * *Files identical despite different names*

### Comparing `ampalibe-1.1.9/ampalibe/logger.py` & `ampalibe-1.2.0.1a0/ampalibe/logger.py`

 * *Files identical despite different names*

### Comparing `ampalibe-1.1.9/ampalibe/messenger.py` & `ampalibe-1.2.0.1a0/ampalibe/messenger.py`

 * *Files identical despite different names*

### Comparing `ampalibe-1.1.9/ampalibe/model.py` & `ampalibe-1.2.0.1a0/ampalibe/model.py`

 * *Files 6% similar despite different names*

```diff
@@ -19,14 +19,32 @@
             "password": conf.DB_PASSWORD,
             "database": conf.DB_NAME,
         }
         if conf.DB_PORT:
             db_conf["port"] = conf.DB_PORT
         return db_conf
 
+    def get_db_url(self, conf=Configuration):
+        """
+        function to configure the standart database
+        """
+        if conf.ADAPTER == "SQLITE":
+            return f"sqlite:///{conf.DB_FILE}"
+        elif conf.ADAPTER == "MONGODB":
+            return self.mongodb(conf)
+        else:
+            url = f"{conf.ADAPTER}://{conf.DB_USER}"
+            if conf.DB_PASSWORD:
+                url += f":{conf.DB_PASSWORD}"
+            url += f"@{conf.DB_HOST}"
+            if conf.DB_PORT:
+                url += f":{str(conf.DB_PORT)}"
+            url += f"/{conf.DB_NAME}"
+            return url.lower()
+
     def mongodb(self, conf=Configuration):
         """
         function to configure the mongodb database
         """
 
         url = "mongodb"
         if hasattr(conf, "SRV_PROTOCOL"):
@@ -130,22 +148,24 @@
                     `lang` varchar(5) DEFAULT NULL,
                     PRIMARY KEY (`id`),
                     INDEX (last_use)
                 ) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4;
             """
         elif self.ADAPTER == "POSTGRESQL":
             req = """
-                CREATE TABLE IF NOT EXISTS amp_user (
-                    id SERIAL PRIMARY KEY,
-                    user_id VARCHAR UNIQUE NOT NULL,
-                    action TEXT DEFAULT NULL,
-                    last_use TIMESTAMP NOT NULL DEFAULT CURRENT_TIMESTAMP,
-                    lang VARCHAR DEFAULT NULL
-                );
-                CREATE INDEX IF NOT EXISTS last_use_index ON amp_user(last_use);
+                CREATE TABLE IF NOT EXISTS  "amp_user" (
+                    id SERIAL,
+                    user_id VARCHAR NULL DEFAULT NULL,
+                    action TEXT NULL DEFAULT NULL,
+                    last_use TIMESTAMP NULL DEFAULT NOW(),
+                    lang VARCHAR NULL DEFAULT NULL,
+                    PRIMARY KEY (id),
+                    UNIQUE (user_id),
+                    INDEX (last_use)
+                )
             """
         elif self.ADAPTER == "MONGODB":
             if "amp_user" not in self.db.list_collection_names():
                 self.db.create_collection("amp_user")
                 # self.db.amp_user.create_index("user_id", unique=True)
             return
         else:
```

### Comparing `ampalibe-1.1.9/ampalibe/payload.py` & `ampalibe-1.2.0.1a0/ampalibe/payload.py`

 * *Files identical despite different names*

### Comparing `ampalibe-1.1.9/ampalibe/tools.py` & `ampalibe-1.2.0.1a0/ampalibe/tools.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,22 +1,30 @@
 import os
 import pickle
+import inspect
+import asyncio
 from .cmd import Cmd
-from threading import Thread
 from .messenger import Messenger
 
 funcs = {
     "command": {},
     "action": {},
     "event": {},
     "before": None,
     "after": None,
 }
 
 
+async def verif_func(func, **kwargs):
+    """
+    function verify if the function is a coroutine or not before running it
+    """
+    return await func(**kwargs) if inspect.iscoroutinefunction(func) else func(**kwargs)
+
+
 def analyse(data):
     """
     Function analyzing data received from Facebook
     The data received are of type Json .
     """
 
     for event in data["entry"]:
@@ -81,43 +89,48 @@
                 elif message["optin"].get("type") == "notification_messages":
                     optin.token = message["optin"]["notification_messages_token"]
                 return sender_id, optin, message
 
     return None, Cmd(""), None
 
 
-def before_run(func, **kwargs):
+async def before_run(func, **kwargs):
+    """
+    Function to be executed before running the function
+    called by the user command
+    """
+
     res = None
     if funcs["before"] and hasattr(funcs["before"], "__call__"):
-        if funcs["before"](**kwargs):
-            res = func(**kwargs)
+        if await verif_func(funcs["before"], **kwargs):
+            res = await verif_func(func, **kwargs)
     else:
-        res = func(**kwargs)
+        res = await verif_func(func, **kwargs)
 
     if funcs["after"] and hasattr(funcs["after"], "__call__"):
         kwargs["res"] = res
-        funcs["after"](**kwargs)
+        await verif_func(funcs["after"], **kwargs)
 
     return res
 
 
 def send_next(sender_id, payload):
     chat = Messenger()
     if os.path.isfile(f"assets/private/.__{sender_id}"):
         elements = pickle.load(open(f"assets/private/.__{sender_id}", "rb"))
         if payload == "/__next":
             chat.send_generic_template(sender_id, elements[0], next=elements[1])
         else:
             chat.send_quick_reply(sender_id, elements[0], elements[1], next=elements[2])
 
 
-def verif_event(testmode, payload, sender_id, message):
+async def verif_event(testmode, payload, sender_id, message):
     if funcs["event"].get(payload.webhook):
         kw = {
             "sender_id": sender_id,
             "watermark": payload,
             "message": message,
         }
         if testmode:
-            funcs["event"][payload.webhook](**kw)
+            await verif_func(funcs["event"][payload.webhook], **kw)
         else:
-            Thread(target=funcs["event"][payload.webhook], kwargs=kw).start()
+            asyncio.create_task(verif_func(funcs["event"][payload.webhook], **kw))
```

### Comparing `ampalibe-1.1.9/ampalibe/ui.py` & `ampalibe-1.2.0.1a0/ampalibe/ui.py`

 * *Files identical despite different names*

### Comparing `ampalibe-1.1.9/ampalibe/utils.py` & `ampalibe-1.2.0.1a0/ampalibe/utils.py`

 * *Files 16% similar despite different names*

```diff
@@ -1,10 +1,11 @@
 import os
 import sys
 import json
+import httpx
 import requests
 from .payload import Payload
 from conf import Configuration  # type: ignore
 
 
 LANGS = None
 
@@ -86,7 +87,62 @@
     header = {"content-type": "application/json; charset=utf-8"}
     return requests.post(
         f"http://127.0.0.1:{Configuration.APP_PORT}/",
         json=data_json,
         headers=header,
         params=params,
     )
+
+
+async def async_simulate(sender_id, text, **params):
+    """
+    Simulate a message send by an user
+
+    Args:
+        sender_id: <str>
+        text: <str> |<Payload>
+    """
+    if isinstance(text, Payload):
+        text = Payload.trt_payload_out(text)
+
+    data_json = {
+        "object": "page",
+        "entry": [
+            {
+                "messaging": [
+                    {
+                        "message": {
+                            "text": text,
+                        },
+                        "sender": {"id": sender_id},
+                    }
+                ]
+            }
+        ],
+    }
+    headers = {"content-type": "application/json; charset=utf-8"}
+    async with httpx.AsyncClient() as client:
+        response = await client.post(
+            f"http://127.0.0.1:{Configuration.APP_PORT}/",
+            json=data_json,
+            headers=headers,
+        )
+
+    return response
+
+
+async def async_download_file(url, file):
+    """
+    Downloading a file from an url.
+
+    Args:
+        url: direct link for the attachment
+
+        file: filename with path
+    """
+    async with httpx.AsyncClient() as client:
+        response = await client.get(url, follow_redirects=True)
+
+    with open(file, "wb") as f:
+        f.write(response.content)
+
+    return file
```

### Comparing `ampalibe-1.1.9/ampalibe.egg-info/PKG-INFO` & `ampalibe-1.2.0.1a0/ampalibe.egg-info/PKG-INFO`

 * *Files 2% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ampalibe
-Version: 1.1.9
+Version: 1.2.0.1a0
 Summary: Ampalibe is a lightweight Python framework for building Facebook Messenger bots faster.
 Home-page: https://github.com/iTeam-S/ampalibe
 Author: iTeam-$
 Author-email: contact@iteam-s.mg
 License: UNKNOWN
 Project-URL: Bug Tracker, https://github.com/iTeam-S/ampalibe/issues
 Description: # Ampalibe
@@ -123,15 +123,15 @@
         from ampalibe.messenger import Action
         
         chat = Messenger()
         query = Model()
         
         @ampalibe.before_receive()
         def before_process(sender_id, **ext):
-            #  Put a view for each message received
+            #  Mark as seen for each message received
             chat.send_action(sender_id, Action.mark_seen)
             return True
         
         @ampalibe.command('/')
         def main(sender_id, cmd, **ext):
             """
             No need to manage weebhooks and data: messages are received directly in a main function
```

### Comparing `ampalibe-1.1.9/bin/ampalibe` & `ampalibe-1.2.0.1a0/bin/ampalibe`

 * *Files identical despite different names*

### Comparing `ampalibe-1.1.9/bin/ampalibe.bat` & `ampalibe-1.2.0.1a0/bin/ampalibe.bat`

 * *Files 8% similar despite different names*

```diff
@@ -1,53 +1,53 @@
 @ echo off
 
 IF /I "%1" == "env" (
     python -m ampalibe env
-    exit
+    exit /B
 )
 
 IF /I "%1" == "lang" (
     python -m ampalibe lang
-    exit
+    exit /B
 )
 
 IF /I "%1" == "create" (
     IF exist "%2" (
         echo ERROR !! %2 already exists  1>&2
-        exit
+        exit /B
     )
     python -m ampalibe create %2
-    exit
+    exit /B
 )
 IF /I "%1" == "init" (
     python -m ampalibe init
-    exit
+    exit /B
 )
 IF /I "%1" == "run" (
 
     IF NOT exist "core.py" (
         echo ERROR !! core.py not found  1>&2
         echo Please, go to your dir project.
-        exit
+        exit /B
     )
 
     IF NOT exist "conf.py" (
         echo ERROR !! conf.py not found  1>&2
-        exit
+        exit /B
     )
 
     call .env.bat
     python -m ampalibe run
     IF /I "%2" == "--dev" (
         watchmedo auto-restart --patterns="*.py;langs.json" --recursive -- python -c "import core;core.ampalibe.init.run()"
-        exit
+        exit /B
     )
     python -c "import core;core.ampalibe.init.run()"
-    exit
+    exit /B
 )
 
 IF /I "%1" == "version" (
     python -m ampalibe version
-    exit
+    exit /B
 )
 
 python -m ampalibe usage
```

### Comparing `ampalibe-1.1.9/setup.cfg` & `ampalibe-1.2.0.1a0/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 [metadata]
 name = Ampalibe
-version = 1.1.9
+version = 1.2.0.1a
 author = iTeam-$
 author_email = contact@iteam-s.mg
 description = Ampalibe is a lightweight Python framework for building Facebook Messenger bots faster.
 long_description = file: README.md
 long_description_content_type = text/markdown
 url = https://github.com/iTeam-S/ampalibe
 project_urls =
```

### Comparing `ampalibe-1.1.9/setup.py` & `ampalibe-1.2.0.1a0/setup.py`

 * *Files 10% similar despite different names*

```diff
@@ -1,15 +1,15 @@
 import setuptools
 
 with open("README.md", "r") as fh:
     long_description = fh.read()
 
 setuptools.setup(
     name="ampalibe",  # This is the name of the package
-    version="1.1.9",  # The release version
+    version="1.2.0.1a",  # The release version
     author="iTeam-$",  # Full name of the author
     description=(
         "Ampalibe is a lightweight Python framework for building Facebook"
         " Messenger bots faster."
     ),
     long_description=long_description,  # Long description read from the readme
     long_description_content_type="text/markdown",
@@ -31,11 +31,14 @@
         "retry",
         "requests",
         "colorama",
         "requests_toolbelt",
         "watchdog!=2.2.0",
         "aiocron",
         "tinydb",
+        "httpx",
+        "sqlmodel",
+        "sqladmin"
     ],  # depandance
     include_package_data=True,  # Include all data file with the package
     scripts=["bin/ampalibe", "bin/ampalibe.bat"],
 )
```


# Comparing `tmp/ttbotlib-0.6.tar.gz` & `tmp/ttbotlib-0.7.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "ttbotlib-0.6.tar", last modified: Mon Apr 10 17:01:42 2023, max compression
+gzip compressed data, was "ttbotlib-0.7.tar", last modified: Wed Jun 28 11:56:30 2023, max compression
```

## Comparing `ttbotlib-0.6.tar` & `ttbotlib-0.7.tar`

### file list

```diff
@@ -1,24 +1,24 @@
-drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-04-10 17:01:42.950729 ttbotlib-0.6/
--rw-r--r--   0 scailer   (1000) users      (985)     1070 2020-01-16 11:25:02.000000 ttbotlib-0.6/LICENSE.md
--rw-r--r--   0 scailer   (1000) users      (985)     3317 2023-04-10 17:01:42.950729 ttbotlib-0.6/PKG-INFO
--rw-r--r--   0 scailer   (1000) users      (985)     2548 2023-02-16 14:30:46.000000 ttbotlib-0.6/README.md
-drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-04-10 17:01:42.947396 ttbotlib-0.6/example/
--rw-r--r--   0 scailer   (1000) users      (985)     1664 2023-02-16 14:30:46.000000 ttbotlib-0.6/example/app.py
--rw-r--r--   0 scailer   (1000) users      (985)     2290 2023-04-10 17:01:27.000000 ttbotlib-0.6/pyproject.toml
--rw-r--r--   0 scailer   (1000) users      (985)       63 2023-04-10 17:01:42.950729 ttbotlib-0.6/setup.cfg
--rw-r--r--   0 scailer   (1000) users      (985)       38 2023-04-10 17:01:27.000000 ttbotlib-0.6/setup.py
-drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-04-10 17:01:42.950729 ttbotlib-0.6/tests/
--rw-r--r--   0 scailer   (1000) users      (985)     1442 2023-02-16 14:30:46.000000 ttbotlib-0.6/tests/test_client.py
--rw-r--r--   0 scailer   (1000) users      (985)     4590 2023-04-10 17:01:27.000000 ttbotlib-0.6/tests/test_server.py
-drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-04-10 17:01:42.950729 ttbotlib-0.6/ttbot/
--rw-r--r--   0 scailer   (1000) users      (985)      179 2023-04-10 17:01:27.000000 ttbotlib-0.6/ttbot/__init__.py
--rw-r--r--   0 scailer   (1000) users      (985)     1120 2023-02-16 14:30:46.000000 ttbotlib-0.6/ttbot/client.py
--rw-r--r--   0 scailer   (1000) users      (985)        0 2023-04-10 17:01:27.000000 ttbotlib-0.6/ttbot/py.typed
--rw-r--r--   0 scailer   (1000) users      (985)     8065 2023-04-10 17:01:27.000000 ttbotlib-0.6/ttbot/server.py
--rw-r--r--   0 scailer   (1000) users      (985)      632 2023-02-16 14:30:46.000000 ttbotlib-0.6/ttbot/types.py
-drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-04-10 17:01:42.950729 ttbotlib-0.6/ttbotlib.egg-info/
--rw-r--r--   0 scailer   (1000) users      (985)     3317 2023-04-10 17:01:42.000000 ttbotlib-0.6/ttbotlib.egg-info/PKG-INFO
--rw-r--r--   0 scailer   (1000) users      (985)      350 2023-04-10 17:01:42.000000 ttbotlib-0.6/ttbotlib.egg-info/SOURCES.txt
--rw-r--r--   0 scailer   (1000) users      (985)        1 2023-04-10 17:01:42.000000 ttbotlib-0.6/ttbotlib.egg-info/dependency_links.txt
--rw-r--r--   0 scailer   (1000) users      (985)      204 2023-04-10 17:01:42.000000 ttbotlib-0.6/ttbotlib.egg-info/requires.txt
--rw-r--r--   0 scailer   (1000) users      (985)       14 2023-04-10 17:01:42.000000 ttbotlib-0.6/ttbotlib.egg-info/top_level.txt
+drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-06-28 11:56:30.508375 ttbotlib-0.7/
+-rw-r--r--   0 scailer   (1000) users      (985)     1070 2020-01-16 11:25:02.000000 ttbotlib-0.7/LICENSE.md
+-rw-r--r--   0 scailer   (1000) users      (985)     3317 2023-06-28 11:56:30.508375 ttbotlib-0.7/PKG-INFO
+-rw-r--r--   0 scailer   (1000) users      (985)     2548 2023-02-16 14:30:46.000000 ttbotlib-0.7/README.md
+drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-06-28 11:56:30.508375 ttbotlib-0.7/example/
+-rw-r--r--   0 scailer   (1000) users      (985)     1664 2023-02-16 14:30:46.000000 ttbotlib-0.7/example/app.py
+-rw-r--r--   0 scailer   (1000) users      (985)     2290 2023-04-10 17:01:27.000000 ttbotlib-0.7/pyproject.toml
+-rw-r--r--   0 scailer   (1000) users      (985)       63 2023-06-28 11:56:30.508375 ttbotlib-0.7/setup.cfg
+-rw-r--r--   0 scailer   (1000) users      (985)       38 2023-04-10 17:01:27.000000 ttbotlib-0.7/setup.py
+drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-06-28 11:56:30.508375 ttbotlib-0.7/tests/
+-rw-r--r--   0 scailer   (1000) users      (985)     1442 2023-02-16 14:30:46.000000 ttbotlib-0.7/tests/test_client.py
+-rw-r--r--   0 scailer   (1000) users      (985)     4624 2023-06-28 09:53:44.000000 ttbotlib-0.7/tests/test_server.py
+drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-06-28 11:56:30.508375 ttbotlib-0.7/ttbot/
+-rw-r--r--   0 scailer   (1000) users      (985)      179 2023-06-28 11:45:38.000000 ttbotlib-0.7/ttbot/__init__.py
+-rw-r--r--   0 scailer   (1000) users      (985)     1120 2023-02-16 14:30:46.000000 ttbotlib-0.7/ttbot/client.py
+-rw-r--r--   0 scailer   (1000) users      (985)        0 2023-04-10 17:01:27.000000 ttbotlib-0.7/ttbot/py.typed
+-rw-r--r--   0 scailer   (1000) users      (985)     8088 2023-06-28 09:34:59.000000 ttbotlib-0.7/ttbot/server.py
+-rw-r--r--   0 scailer   (1000) users      (985)      649 2023-06-28 09:29:49.000000 ttbotlib-0.7/ttbot/types.py
+drwxr-xr-x   0 scailer   (1000) users      (985)        0 2023-06-28 11:56:30.508375 ttbotlib-0.7/ttbotlib.egg-info/
+-rw-r--r--   0 scailer   (1000) users      (985)     3317 2023-06-28 11:56:30.000000 ttbotlib-0.7/ttbotlib.egg-info/PKG-INFO
+-rw-r--r--   0 scailer   (1000) users      (985)      350 2023-06-28 11:56:30.000000 ttbotlib-0.7/ttbotlib.egg-info/SOURCES.txt
+-rw-r--r--   0 scailer   (1000) users      (985)        1 2023-06-28 11:56:30.000000 ttbotlib-0.7/ttbotlib.egg-info/dependency_links.txt
+-rw-r--r--   0 scailer   (1000) users      (985)      204 2023-06-28 11:56:30.000000 ttbotlib-0.7/ttbotlib.egg-info/requires.txt
+-rw-r--r--   0 scailer   (1000) users      (985)       14 2023-06-28 11:56:30.000000 ttbotlib-0.7/ttbotlib.egg-info/top_level.txt
```

### Comparing `ttbotlib-0.6/LICENSE.md` & `ttbotlib-0.7/LICENSE.md`

 * *Files identical despite different names*

### Comparing `ttbotlib-0.6/PKG-INFO` & `ttbotlib-0.7/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ttbotlib
-Version: 0.6
+Version: 0.7
 Summary: pararam.io bot framework
 Author-email: Tamtam team <support@tamtamteam.com>
 License: MIT License
 Keywords: pararam.io,async,bot
 Classifier: Development Status :: 4 - Beta
 Classifier: Environment :: Plugins
 Classifier: Intended Audience :: Developers
```

### Comparing `ttbotlib-0.6/README.md` & `ttbotlib-0.7/README.md`

 * *Files identical despite different names*

### Comparing `ttbotlib-0.6/example/app.py` & `ttbotlib-0.7/example/app.py`

 * *Files identical despite different names*

### Comparing `ttbotlib-0.6/pyproject.toml` & `ttbotlib-0.7/pyproject.toml`

 * *Files identical despite different names*

### Comparing `ttbotlib-0.6/tests/test_client.py` & `ttbotlib-0.7/tests/test_client.py`

 * *Files identical despite different names*

### Comparing `ttbotlib-0.6/tests/test_server.py` & `ttbotlib-0.7/tests/test_server.py`

 * *Files 4% similar despite different names*

```diff
@@ -8,16 +8,17 @@
 class TestServer(Server):
     async def message_handler(self, post: Post) -> str:
         return 'test'
 
     async def action_handler(self, action: Action) -> dict:
         assert action == Action(
             action='check',
+            user_id=1,
             params={'param1': 7},
-            post=Post(user_id=1, chat_id=2, post_no=3, team_id=None, text='')
+            post=Post(user_id=0, chat_id=2, post_no=3, team_id=None, text='')
         )
         return {'res': '№'}
 
     async def api_handler(self, request: Request) -> dict:
         assert request == Request(
             method='POST',
             path='/api',
@@ -37,16 +38,16 @@
     with pytest.raises(NotImplementedError):
         request = Request(method='POST', path='/api', query={}, headers={}, data={})
         await Server().api_handler(request)
 
 
 async def test_act_interface_ok():
     with pytest.raises(NotImplementedError):
-        post = Post(user_id=1, chat_id=2, post_no=3, text='')
-        await Server().action_handler(Action(post=post, action='act', params={}))
+        post = Post(user_id=0, chat_id=2, post_no=3, text='')
+        await Server().action_handler(Action(post=post, action='act', params={}, user_id=1))
 
 
 async def test_bot_interface_ok():
     with pytest.raises(NotImplementedError):
         await Server().message_handler(Post(user_id=1, chat_id=2, post_no=3, text=''))
```

### Comparing `ttbotlib-0.6/ttbot/client.py` & `ttbotlib-0.7/ttbot/client.py`

 * *Files identical despite different names*

### Comparing `ttbotlib-0.6/ttbot/server.py` & `ttbotlib-0.7/ttbot/server.py`

 * *Files 1% similar despite different names*

```diff
@@ -127,18 +127,19 @@
         data = await self._load_json(scope, receive)
 
         if missed_fields := {'user_id', 'chat_id', 'post_no', 'action'} - set(data.keys()):
             await self._send_json({'error': f'Missed fields: {missed_fields}'}, send)
             return None
 
         action = Action(
+            user_id=data.pop('user_id'),
             action=data.pop('action'),
             params=data,
             post=Post(
-                user_id=data.pop('user_id'),
+                user_id=0,
                 chat_id=data.pop('chat_id'),
                 post_no=data.pop('post_no'),
                 team_id=data.pop('organization_id', None),
                 text=data.pop('text', '')
             )
         )
```

### Comparing `ttbotlib-0.6/ttbot/types.py` & `ttbotlib-0.7/ttbot/types.py`

 * *Files 1% similar despite different names*

```diff
@@ -28,10 +28,11 @@
     query: dict
     headers: dict
     data: dict
 
 
 @dataclass
 class Action:
+    user_id: int
     post: Post
     action: str
     params: dict
```

### Comparing `ttbotlib-0.6/ttbotlib.egg-info/PKG-INFO` & `ttbotlib-0.7/ttbotlib.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: ttbotlib
-Version: 0.6
+Version: 0.7
 Summary: pararam.io bot framework
 Author-email: Tamtam team <support@tamtamteam.com>
 License: MIT License
 Keywords: pararam.io,async,bot
 Classifier: Development Status :: 4 - Beta
 Classifier: Environment :: Plugins
 Classifier: Intended Audience :: Developers
```


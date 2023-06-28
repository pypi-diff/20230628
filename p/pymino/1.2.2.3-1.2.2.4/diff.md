# Comparing `tmp/pymino-1.2.2.3.tar.gz` & `tmp/pymino-1.2.2.4.tar.gz`

## filetype from file(1)

```diff
@@ -1 +1 @@
-gzip compressed data, was "C:\Users\12095\Desktop\pymino\pymino\dist\.tmp-jdhp3kqr\pymino-1.2.2.3.tar", last modified: Tue Jun 27 07:23:04 2023, max compression
+gzip compressed data, was "C:\Users\12095\Desktop\New folder\pymino\dist\.tmp-esawe27c\pymino-1.2.2.4.tar", last modified: Wed Jun 28 10:21:37 2023, max compression
```

## Comparing `pymino-1.2.2.3.tar` & `pymino-1.2.2.4.tar`

### file list

```diff
@@ -1,61 +1,62 @@
-drwxrwxrwx   0        0        0        0 2023-06-27 07:23:04.298522 pymino-1.2.2.3/
--rw-rw-rw-   0        0        0     1085 2023-06-27 02:23:25.000000 pymino-1.2.2.3/LICENSE
--rw-rw-rw-   0        0        0     7424 2023-06-27 07:23:04.299017 pymino-1.2.2.3/PKG-INFO
--rw-rw-rw-   0        0        0     6706 2023-06-27 05:01:27.000000 pymino-1.2.2.3/README.md
-drwxrwxrwx   0        0        0        0 2023-06-27 07:23:04.163114 pymino-1.2.2.3/pymino/
--rw-rw-rw-   0        0        0      721 2023-06-27 07:22:36.000000 pymino-1.2.2.3/pymino/__init__.py
--rw-rw-rw-   0        0        0    11011 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/async_bot.py
--rw-rw-rw-   0        0        0    30258 2023-06-27 06:01:55.000000 pymino-1.2.2.3/pymino/bot.py
--rw-rw-rw-   0        0        0    36835 2023-06-27 04:14:26.000000 pymino-1.2.2.3/pymino/client.py
-drwxrwxrwx   0        0        0        0 2023-06-27 07:23:04.219657 pymino-1.2.2.3/pymino/ext/
--rw-rw-rw-   0        0        0      528 2023-06-27 04:04:07.000000 pymino-1.2.2.3/pymino/ext/__init__.py
--rw-rw-rw-   0        0        0    11204 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/account.py
--rw-rw-rw-   0        0        0   343766 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/async_community.py
--rw-rw-rw-   0        0        0    19900 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/async_context.py
--rw-rw-rw-   0        0        0    27187 2023-06-27 07:14:57.000000 pymino-1.2.2.3/pymino/ext/async_event_handler.py
--rw-rw-rw-   0        0        0     7238 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/async_socket.py
--rw-rw-rw-   0        0        0   342510 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/community.py
--rw-rw-rw-   0        0        0     3040 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/console.py
--rw-rw-rw-   0        0        0    45276 2023-06-27 07:22:04.000000 pymino-1.2.2.3/pymino/ext/context.py
--rw-rw-rw-   0        0        0     1856 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/dispatcher.py
-drwxrwxrwx   0        0        0        0 2023-06-27 07:23:04.275705 pymino-1.2.2.3/pymino/ext/entities/
--rw-rw-rw-   0        0        0      428 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/__init__.py
--rw-rw-rw-   0        0        0     8044 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/acm.py
--rw-rw-rw-   0        0        0     9014 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/admin_log.py
--rw-rw-rw-   0        0        0     1670 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/api_response.py
--rw-rw-rw-   0        0        0    17769 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/bubble.py
--rw-rw-rw-   0        0        0    20322 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/chat_threads.py
--rw-rw-rw-   0        0        0    13223 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/comments.py
--rw-rw-rw-   0        0        0      765 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/enums.py
--rw-rw-rw-   0        0        0    15640 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/exceptions.py
--rw-rw-rw-   0        0        0    43596 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/general.py
--rw-rw-rw-   0        0        0     4802 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/handlers.py
--rw-rw-rw-   0        0        0     5127 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/link_info.py
--rw-rw-rw-   0        0        0     3831 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/member.py
--rw-rw-rw-   0        0        0    42520 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/messages.py
--rw-rw-rw-   0        0        0     1839 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/notification.py
--rw-rw-rw-   0        0        0    31711 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/sticker.py
--rw-rw-rw-   0        0        0     6185 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/threads.py
--rw-rw-rw-   0        0        0    31609 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/userprofile.py
--rw-rw-rw-   0        0        0     2451 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/entities/wsevents.py
--rw-rw-rw-   0        0        0    70180 2023-06-27 04:58:30.000000 pymino-1.2.2.3/pymino/ext/global_client.py
--rw-rw-rw-   0        0        0      543 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/handle_queue.py
--rw-rw-rw-   0        0        0     6657 2023-06-27 07:21:56.000000 pymino-1.2.2.3/pymino/ext/socket.py
-drwxrwxrwx   0        0        0        0 2023-06-27 07:23:04.297530 pymino-1.2.2.3/pymino/ext/utilities/
--rw-rw-rw-   0        0        0      234 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/utilities/__init__.py
--rw-rw-rw-   0        0        0    11320 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/utilities/async_request_handler.py
--rw-rw-rw-   0        0        0    11309 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/utilities/chat_console.py
--rw-rw-rw-   0        0        0     6280 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/utilities/commands.py
--rw-rw-rw-   0        0        0     2078 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/utilities/community_console.py
--rw-rw-rw-   0        0        0     1110 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/utilities/generate.py
--rw-rw-rw-   0        0        0     2911 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/utilities/menu.py
--rw-rw-rw-   0        0        0     2106 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/utilities/profile_console.py
--rw-rw-rw-   0        0        0    10322 2023-06-27 02:23:25.000000 pymino-1.2.2.3/pymino/ext/utilities/request_handler.py
-drwxrwxrwx   0        0        0        0 2023-06-27 07:23:04.182955 pymino-1.2.2.3/pymino.egg-info/
--rw-rw-rw-   0        0        0     7424 2023-06-27 07:23:04.000000 pymino-1.2.2.3/pymino.egg-info/PKG-INFO
--rw-rw-rw-   0        0        0     1533 2023-06-27 07:23:04.000000 pymino-1.2.2.3/pymino.egg-info/SOURCES.txt
--rw-rw-rw-   0        0        0        1 2023-06-27 07:23:04.000000 pymino-1.2.2.3/pymino.egg-info/dependency_links.txt
--rw-rw-rw-   0        0        0      117 2023-06-27 07:23:04.000000 pymino-1.2.2.3/pymino.egg-info/requires.txt
--rw-rw-rw-   0        0        0        7 2023-06-27 07:23:04.000000 pymino-1.2.2.3/pymino.egg-info/top_level.txt
--rw-rw-rw-   0        0        0      873 2023-06-27 07:23:04.305466 pymino-1.2.2.3/setup.cfg
--rw-rw-rw-   0        0        0     1394 2023-06-27 04:33:02.000000 pymino-1.2.2.3/setup.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:21:37.165024 pymino-1.2.2.4/
+-rw-rw-rw-   0        0        0     1085 2023-06-28 09:49:18.000000 pymino-1.2.2.4/LICENSE
+-rw-rw-rw-   0        0        0     7424 2023-06-28 10:21:37.165518 pymino-1.2.2.4/PKG-INFO
+-rw-rw-rw-   0        0        0     6706 2023-06-28 10:21:17.000000 pymino-1.2.2.4/README.md
+drwxrwxrwx   0        0        0        0 2023-06-28 10:21:37.089630 pymino-1.2.2.4/pymino/
+-rw-rw-rw-   0        0        0      721 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/__init__.py
+-rw-rw-rw-   0        0        0    11011 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/async_bot.py
+-rw-rw-rw-   0        0        0    30258 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/bot.py
+-rw-rw-rw-   0        0        0    36824 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/client.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:21:37.127327 pymino-1.2.2.4/pymino/ext/
+-rw-rw-rw-   0        0        0      528 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/__init__.py
+-rw-rw-rw-   0        0        0      192 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/_global.py
+-rw-rw-rw-   0        0        0    11196 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/account.py
+-rw-rw-rw-   0        0        0   343766 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/async_community.py
+-rw-rw-rw-   0        0        0    21404 2023-06-28 10:17:31.000000 pymino-1.2.2.4/pymino/ext/async_context.py
+-rw-rw-rw-   0        0        0    25866 2023-06-28 10:17:41.000000 pymino-1.2.2.4/pymino/ext/async_event_handler.py
+-rw-rw-rw-   0        0        0     7238 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/async_socket.py
+-rw-rw-rw-   0        0        0   342510 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/community.py
+-rw-rw-rw-   0        0        0     3040 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/console.py
+-rw-rw-rw-   0        0        0    45497 2023-06-28 10:17:36.000000 pymino-1.2.2.4/pymino/ext/context.py
+-rw-rw-rw-   0        0        0     1856 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/dispatcher.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:21:37.152126 pymino-1.2.2.4/pymino/ext/entities/
+-rw-rw-rw-   0        0        0      428 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/__init__.py
+-rw-rw-rw-   0        0        0     8044 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/acm.py
+-rw-rw-rw-   0        0        0     9014 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/admin_log.py
+-rw-rw-rw-   0        0        0     1670 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/api_response.py
+-rw-rw-rw-   0        0        0    17769 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/bubble.py
+-rw-rw-rw-   0        0        0    20322 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/chat_threads.py
+-rw-rw-rw-   0        0        0    13223 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/comments.py
+-rw-rw-rw-   0        0        0      765 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/enums.py
+-rw-rw-rw-   0        0        0    15640 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/exceptions.py
+-rw-rw-rw-   0        0        0    43596 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/general.py
+-rw-rw-rw-   0        0        0     4802 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/handlers.py
+-rw-rw-rw-   0        0        0     5127 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/link_info.py
+-rw-rw-rw-   0        0        0     3831 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/member.py
+-rw-rw-rw-   0        0        0    42520 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/messages.py
+-rw-rw-rw-   0        0        0     1839 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/notification.py
+-rw-rw-rw-   0        0        0    31711 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/sticker.py
+-rw-rw-rw-   0        0        0     6185 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/threads.py
+-rw-rw-rw-   0        0        0    31609 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/userprofile.py
+-rw-rw-rw-   0        0        0     2451 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/entities/wsevents.py
+-rw-rw-rw-   0        0        0    70180 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/global_client.py
+-rw-rw-rw-   0        0        0      543 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/handle_queue.py
+-rw-rw-rw-   0        0        0     6657 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/socket.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:21:37.164032 pymino-1.2.2.4/pymino/ext/utilities/
+-rw-rw-rw-   0        0        0      234 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/utilities/__init__.py
+-rw-rw-rw-   0        0        0    11320 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/utilities/async_request_handler.py
+-rw-rw-rw-   0        0        0    11309 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/utilities/chat_console.py
+-rw-rw-rw-   0        0        0     6280 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/utilities/commands.py
+-rw-rw-rw-   0        0        0     2078 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/utilities/community_console.py
+-rw-rw-rw-   0        0        0     1110 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/utilities/generate.py
+-rw-rw-rw-   0        0        0     2911 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/utilities/menu.py
+-rw-rw-rw-   0        0        0     2106 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/utilities/profile_console.py
+-rw-rw-rw-   0        0        0    10322 2023-06-28 09:49:18.000000 pymino-1.2.2.4/pymino/ext/utilities/request_handler.py
+drwxrwxrwx   0        0        0        0 2023-06-28 10:21:37.105999 pymino-1.2.2.4/pymino.egg-info/
+-rw-rw-rw-   0        0        0     7424 2023-06-28 10:21:37.000000 pymino-1.2.2.4/pymino.egg-info/PKG-INFO
+-rw-rw-rw-   0        0        0     1555 2023-06-28 10:21:37.000000 pymino-1.2.2.4/pymino.egg-info/SOURCES.txt
+-rw-rw-rw-   0        0        0        1 2023-06-28 10:21:37.000000 pymino-1.2.2.4/pymino.egg-info/dependency_links.txt
+-rw-rw-rw-   0        0        0      117 2023-06-28 10:21:37.000000 pymino-1.2.2.4/pymino.egg-info/requires.txt
+-rw-rw-rw-   0        0        0        7 2023-06-28 10:21:37.000000 pymino-1.2.2.4/pymino.egg-info/top_level.txt
+-rw-rw-rw-   0        0        0      873 2023-06-28 10:21:37.171966 pymino-1.2.2.4/setup.cfg
+-rw-rw-rw-   0        0        0     1394 2023-06-28 09:49:18.000000 pymino-1.2.2.4/setup.py
```

### Comparing `pymino-1.2.2.3/LICENSE` & `pymino-1.2.2.4/LICENSE`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/PKG-INFO` & `pymino-1.2.2.4/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pymino
-Version: 1.2.2.3
+Version: 1.2.2.4
 Summary: Easily create a bot for Amino Apps using a modern easy to use synchronous library.
 Home-page: https://github.com/forevercynical/pymino
 Author: forevercynical
 Author-email: me@cynical.gg
 License: MIT
 Keywords: amino,pymino,narvii,amino-api,narvii-bots,aminoapps,amino-bot,amino-bots
 Classifier: Programming Language :: Python :: 3
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: pymino Version: 1.2.2.3 Summary: Easily create a
+Metadata-Version: 2.1 Name: pymino Version: 1.2.2.4 Summary: Easily create a
 bot for Amino Apps using a modern easy to use synchronous library. Home-page:
 https://github.com/forevercynical/pymino Author: forevercynical Author-email:
 me@cynical.gg License: MIT Keywords: amino,pymino,narvii,amino-api,narvii-
 bots,aminoapps,amino-bot,amino-bots Classifier: Programming Language :: Python
 :: 3 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
```

### Comparing `pymino-1.2.2.3/README.md` & `pymino-1.2.2.4/README.md`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/__init__.py` & `pymino-1.2.2.4/pymino/__init__.py`

 * *Files 0% similar despite different names*

```diff
@@ -1,12 +1,12 @@
 __title__ = 'pymino'
 __author__ = 'cynical'
 __license__ = 'MIT'
 __copyright__ = 'Copyright 2023 Cynical'
-__version__ = '1.2.2.3'
+__version__ = '1.2.2.4'
 __description__ = 'A Python wrapper for the aminoapps.com API'
 
 from .bot import Bot as Bot
 from .async_bot import AsyncBot as AsyncBot
 from .client import Client as Client
 
 from requests import get
```

### Comparing `pymino-1.2.2.3/pymino/async_bot.py` & `pymino-1.2.2.4/pymino/async_bot.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/bot.py` & `pymino-1.2.2.4/pymino/bot.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/client.py` & `pymino-1.2.2.4/pymino/client.py`

 * *Files 0% similar despite different names*

```diff
@@ -782,15 +782,15 @@
 
         This method uploads an image to amino servers. The image data is passed as a string argument. The method calls the
         `upload_image` method of the `account` object with the `image` parameter set to the given image data. The result is
         a `mediaValue` object that contains the URL of the uploaded image.
 
         The method returns the URL of the uploaded image.
         """
-        return self.account.upload_image(image=image).mediaValue
+        return self.account.upload_image(image=image)
 
 
     @authenticated
     def fetch_profile(self) -> UserProfile:
         """
         Fetches the user profile of the authenticated user.
```

### Comparing `pymino-1.2.2.3/pymino/ext/__init__.py` & `pymino-1.2.2.4/pymino/ext/__init__.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/account.py` & `pymino-1.2.2.4/pymino/ext/account.py`

 * *Files 1% similar despite different names*

```diff
@@ -158,15 +158,15 @@
         bot.run(email=email, password=password)
         response = bot.fetch_account()
         print(response)
         ```
         """
         return ApiResponse(self.session.handler(method = "GET", url="/g/s/account"))
 
-    def upload_image(self, image: str) -> ApiResponse:
+    def upload_image(self, image: str) -> str:
         """
         `**upload_image**` - Uploads an image to the server.
 
         `**Parameters**`
 
         - `image` - The image to upload.
```

### Comparing `pymino-1.2.2.3/pymino/ext/async_community.py` & `pymino-1.2.2.4/pymino/ext/async_community.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/async_context.py` & `pymino-1.2.2.4/pymino/ext/async_context.py`

 * *Files 9% similar despite different names*

```diff
@@ -1,8 +1,9 @@
 import asyncio
+from functools import wraps
 import aiohttp
 from diskcache import Cache
 from base64 import b64encode
 from contextlib import suppress
 from time import sleep as delay, time
 from asyncio import AbstractEventLoop
 from typing import BinaryIO, Callable, List, Union
@@ -14,20 +15,21 @@
     `Context` - This handles the event context.
 
     `**Parameters**``
     - `message` - The message which triggered the event.
     - `session` - The session we will use to send requests.
 
     """
-    def __init__(self, message: Message, loop: AbstractEventLoop, session, intents: bool):
-        self.intents:   bool = intents
-        self.request    = session
-        self.loop:      AbstractEventLoop = loop
+    def __init__(self, message: Message, bot):
+        self.bot = bot
         self.message:   Message = message
-        self.userId:    str = session.userId
+        self.loop:      AbstractEventLoop = self.bot.loop
+        self.intents:   bool = self.bot.intents
+        self.request    = self.bot.request
+        self.userId:    str = self.request.userId
 
 
     @property
     def author(self) -> MessageAuthor:
         """The author of the message."""
         with suppress(AttributeError):
             return self.message.author
@@ -65,14 +67,22 @@
 
     @property
     def __message_endpoint__(self) -> str:
         """The message endpoint."""
         return f"/{self.communityId}/s/chat/thread/{self.message.chatId}/message"
 
 
+    def __typing__(func: Callable) -> Callable:
+        @wraps(func)
+        def wrapper(*args, **kwargs):
+            args[0].loop.create_task(args[0].__rt__(args[0].comId, args[0].chatId))
+            return func(*args, **kwargs)
+        return wrapper
+
+
     def _run(func: Callable) -> Callable:
         async def wrapper(*args, **kwargs):
                 if isinstance(args[0], AsyncContext):
                     return await func(*args, **kwargs)
                 else:
                     raise MustRunInContext
         return wrapper
@@ -124,14 +134,46 @@
             await self.request.handler(
                 method = "POST",
                 url = self.__message_endpoint__,
                 data = await self.__message__(**kwargs)
             ))
 
 
+    async def __st__(self, comId: str, chatId: str):
+        return await self.bot.send_websocket_message({
+            "o":{
+                "actions":["Typing"],
+                "target":f"ndc://x{comId}/chat-thread/{chatId}",
+                "ndcId":comId,
+                "params":{"topicIds":[],"threadType":2},
+                "id":randint(0, 100)},
+                "t":304
+                })
+
+
+    async def __et__(self, comId: str, chatId: str):
+        async def wrapper():
+            return await self.bot.send_websocket_message({
+                "o":{
+                    "actions":["Typing"],
+                    "target":f"ndc://x{comId}/chat-thread/{chatId}",
+                    "ndcId":comId,
+                    "params":{"duration":0,"topicIds":[],"threadType":2},
+                    "id":randint(0, 100)},
+                    "t":306
+                    })
+        await asyncio.sleep(2.5)
+        return await wrapper()
+
+
+    async def __rt__(self, comId: str, chatId: str):
+        await self.__st__(comId, chatId)
+        await self.__et__(comId, chatId)
+
+
     async def _delete(self, delete_message: CMessage, delete_after: int = 5) -> ApiResponse:
         delay(delete_after)
         return ApiResponse(
             await self.request.handler(
                 method = "DELETE",
                 url = f"/{self.communityId}/s/chat/thread/{self.message.chatId}/message/{delete_message.messageId}"
             ))
@@ -198,14 +240,15 @@
                 await asyncio.sleep(0.1)
 
             cache.clear(f"{self.message.chatId}_{self.message.author.userId}")
             return 500
 
 
     @_run
+    @__typing__
     async def send(self, content: str, delete_after: int= None, mentioned: Union[str, List[str]]= None) -> CMessage:
         """
         `send` - This sends a message.
 
         `**Parameters**``
         - `content` - The message you want to send.
         - `delete_after` - The time in seconds before the message is deleted. [Optional]
@@ -231,14 +274,15 @@
 
         self.loop.create_task(self._delete(message, delete_after)) if delete_after else None
 
         return message
 
 
     @_run
+    @__typing__
     async def reply(self, content: str, delete_after: int= None, mentioned: Union[str, List[str]]= None) -> CMessage:
         """
         `reply` - This replies to the message.
 
         `**Parameters**``
         - `content` - The message you want to send.
         - `delete_after` - The time in seconds before the message is deleted. [Optional]
@@ -289,14 +333,15 @@
                 "Mentioned: " + ", ".join(mentioned), mentioned=list(mentioned_users)
             )
         """
         return [f"\u200e\u200f@{mentioned[user_id]}\u202c\u202d" for user_id in mentioned]
 
 
     @_run
+    @__typing__
     async def send_link_snippet(self, image: str, message: str = "[c]", link: str = "ndc://user-me", mentioned: list = None) -> CMessage:
         """
         `send_link_snippet` - This sends a link snippet.
 
         `**Parameters**``
         - `image` - The image you want to send. Recommended size: 807x216
         - `message` - The message you want to send.
@@ -334,14 +379,15 @@
             ] if isinstance(mentioned, list) else None
             })
 
         return message
 
 
     @_run
+    @__typing__
     async def send_embed(
         self,
         message: str,
         title: str,
         content: str,
         image: str,
         link: str = "ndc://user-me",
@@ -423,14 +469,15 @@
                 url = "/g/s/media/upload",
                 data = media,
                 content_type = content_type
             )).mediaValue
 
 
     @_run
+    @__typing__
     async def send_sticker(self, sticker_id: str) -> CMessage:
         """
         `send_sticker` - This sends a sticker.
 
         `**Parameters**``
         - `sticker_id` - The sticker ID you want to send.
```

### Comparing `pymino-1.2.2.3/pymino/ext/async_event_handler.py` & `pymino-1.2.2.4/pymino/ext/async_event_handler.py`

 * *Files 2% similar despite different names*

```diff
@@ -222,21 +222,18 @@
         command = self._commands.fetch_command(command_name)
 
         if command is None:
             if command_name == "help" and data.content == f"{self.command_prefix}help":
                 return await context.reply(self._commands.__help__())
             
             if self._events.get("text_message"):
-                await self.__rt__(data.comId, data.chatId)
                 return await self._handle_all_events(event="text_message", data=data, context=context)
 
         if data.content[:len(self.command_prefix)] != self.command_prefix:
             return None
-        else:
-            await self.__rt__(data.comId, data.chatId)
 
         response = await self._check_cooldown(command.name, data, context)
 
         if response != 403:
             func = command.func
             return await func(*await self._set_parameters(context=context, func=func, message=message))
 
@@ -270,47 +267,14 @@
             cache.add(
                 key=f"{chatId}_{userId}",
                 value=content,
                 expire=90
                 )
 
 
-    async def __st__(self, comId: str, chatId: str):
-        return await self.send_websocket_message({
-            "o":{
-                "actions":["Typing"],
-                "target":f"ndc://x{comId}/chat-thread/{chatId}",
-                "ndcId":comId,
-                "params":{"topicIds":[],"threadType":2},
-                "id":randint(0, 100)},
-                "t":304
-                })
-
-
-    async def __et__(self, comId: str, chatId: str):
-        async def wrapper():
-            return await self.send_websocket_message({
-                "o":{
-                    "actions":["Typing"],
-                    "target":f"ndc://x{comId}/chat-thread/{chatId}",
-                    "ndcId":comId,
-                    "params":{"duration":0,"topicIds":[],"threadType":2},
-                    "id":randint(0, 100)},
-                    "t":306
-                    })
-
-        await asyncio.sleep(2.5)
-        return await wrapper()
-
-
-    async def __rt__(self, comId: str, chatId: str):
-        await self.__st__(comId, chatId)
-        self.loop.create_task(self.__et__(comId, chatId))
-
-
     def on_error(self):
         """
         `on_error` - This is an event that is called when an error occurs.
         """
         return self.register_event("error")
 
 
@@ -748,24 +712,24 @@
         ) -> Union[AsyncContext, None]:
         """
         `_handle_event` is a function that handles events.
         """      
         with suppress(KeyError):
 
             if event == "text_message":
-                context = self.context(data, self.loop, self.request, self.intents)
+                context = self.context(data, self)
                 if all([self.intents, not self.command_exists(
                     command_name=data.content[len(self.command_prefix):].split(" ")[0]
                     )]):
                         self._add_cache(data.chatId, data.author.userId, data.content)
 
                 return await self._handle_command(data=data, context=context)
             
             if event in self._events:
-                context = self.context(data, self.loop, self.request, self.intents)
+                context = self.context(data, self)
 
                 if event in {
                     "user_online",
                     "member_set_you_host",
                     "member_set_you_cohost",
                     "member_remove_your_cohost",
                 }:
```

### Comparing `pymino-1.2.2.3/pymino/ext/async_socket.py` & `pymino-1.2.2.4/pymino/ext/async_socket.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/community.py` & `pymino-1.2.2.4/pymino/ext/community.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/console.py` & `pymino-1.2.2.4/pymino/ext/console.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/context.py` & `pymino-1.2.2.4/pymino/ext/context.py`

 * *Files 2% similar despite different names*

```diff
@@ -17,19 +17,21 @@
     `Context` - This handles the event context.
 
     `**Parameters**``
     - `message` - The message which triggered the event.
     - `session` - The session we will use to send requests.
 
     """
-    def __init__(self, message: Message, session, intents: bool):
-        self.intents:   bool = intents
-        self.message:   Message = message
-        self.userId:    str = session.userId
-        self.request    = session
+    def __init__(self, message: Message, bot):
+        self.message:   Message = message 
+        self.bot        = bot
+        self.request    = self.bot.request
+        self.userId:    str = self.request.userId
+        self.intents:   bool = self.bot.intents
+
 
     @property
     def author(self) -> MessageAuthor:
         """The author of the message."""
         with suppress(AttributeError):
             return self.message.author
 
@@ -59,71 +61,120 @@
         return Cache("cache")
 
     @property
     def __message_endpoint__(self) -> str:
         """The message endpoint."""
         return f"/{self.communityId}/s/chat/thread/{self.message.chatId}/message"
 
+
+    def __typing__(func: Callable) -> Callable:
+        @wraps(func)
+        def wrapper(*args, **kwargs):
+            Thread(target=args[0].__rt__, args=(args[0].comId, args[0].chatId)).start()
+            return func(*args, **kwargs)
+        return wrapper
+
+
     def _run(func: Callable) -> Callable:
         def wrapper(*args, **kwargs):
                 if isinstance(args[0], Context):
                     return func(*args, **kwargs)
                 else:
                     raise MustRunInContext
         return wrapper
 
+
     def __purge__(self, data: dict) -> dict:
         return {k: v for k, v in data.items() if v is not None}
 
+
     def __prepare_message__(self, **kwargs) -> dict:
         return self.__purge__(self.__parse_kwargs__(**kwargs))    
-    
+
+
     def __read_image__(self, image: Union[str, BinaryIO]) -> BinaryIO:
         try:
             return get(image).content if image.startswith("http") else open(image, "rb").read()
         except InvalidImage as e:
             raise InvalidImage from e
 
+
     def __parse_kwargs__(self, **kwargs) -> dict:
         return {
             "content": kwargs.get("content"),
             "type": kwargs.get("type"),
             "mediaType": kwargs.get("mediaType"),
             "mediaValue": kwargs.get("mediaValue"),
             "mediaUploadValue": kwargs.get("mediaUploadValue"),
             "stickerId": kwargs.get("stickerId"),
             "attachedObject": kwargs.get("attachedObject"),
             "uid": self.userId
             } 
 
+
     def __message__(self, **kwargs) -> dict:
         return PrepareMessage(**kwargs).json()
 
+
     def __send_message__(self, **kwargs) -> CMessage:
         return CMessage(self.request.handler(
             method = "POST",
             url = self.__message_endpoint__,
             data = self.__message__(**kwargs)
             ))
 
+
+    def __st__(self, comId: str, chatId: str):
+        return self.bot.send_websocket_message({
+            "o":{
+                "actions":["Typing"],
+                "target":f"ndc://x{comId}/chat-thread/{chatId}",
+                "ndcId":comId,
+                "params":{"topicIds":[],"threadType":2},
+                "id":randint(0, 100)},
+                "t":304
+                })
+
+
+    def __et__(self, comId: str, chatId: str):
+        def wrapper():
+            return self.bot.send_websocket_message({
+                "o":{
+                    "actions":["Typing"],
+                    "target":f"ndc://x{comId}/chat-thread/{chatId}",
+                    "ndcId":comId,
+                    "params":{"duration":0,"topicIds":[],"threadType":2},
+                    "id":randint(0, 100)},
+                    "t":306
+                    })
+        delay(2.5)
+        return wrapper()
+
+
+    def __rt__(self, comId: str, chatId: str):
+        self.__st__(comId, chatId)
+        self.__et__(comId, chatId)
+
+
     def _delete(self, delete_message: CMessage, delete_after: int = 5) -> ApiResponse:
         """
         `delete` - Deletes a message.
         
         `**Parameters**`
         - `delete_message` - The message to delete.
         - `delete_after` - The time to delay before deleting the message.
         
         """
         delay(delete_after)
         return ApiResponse(self.request.handler(
             method = "DELETE",
             url = f"/{self.communityId}/s/chat/thread/{self.message.chatId}/message/{delete_message.messageId}"
             ))
-    
+
+
     def wait_for_message(self, message: str, timeout: int = 10) -> int:
         """
         `wait_for_message` - This waits for a specific message within a certain timeout period. 
         
         `**Parameters**`
         - `message` : str
             The specific message to wait for in the cache.
@@ -180,15 +231,17 @@
                 if all([cached_message is not None, cached_message != message]):
                     cache.clear(f"{self.message.chatId}_{self.message.author.userId}")
                     return 404
 
             cache.clear(f"{self.message.chatId}_{self.message.author.userId}")
             return 500
 
+
     @_run
+    @__typing__
     def send(self, content: str, delete_after: int= None, mentioned: Union[str, List[str]]= None) -> CMessage:
         """
         `send` - This sends a message.
 
         `**Parameters**``
         - `content` - The message you want to send.
         - `delete_after` - The time in seconds before the message is deleted. [Optional]
@@ -209,15 +262,17 @@
             "mentionedArray": [{"uid": user} for user in mentioned] if mentioned else None
             })
 
         Thread(target=self._delete, args=(message, delete_after)).start() if delete_after else None
 
         return message
 
+
     @_run
+    @__typing__
     def reply(self, content: str, delete_after: int= None, mentioned: Union[str, List[str]]= None) -> CMessage:
         """
         `reply` - This replies to the message.
 
         `**Parameters**``
         - `content` - The message you want to send.
         - `delete_after` - The time in seconds before the message is deleted. [Optional]
@@ -239,14 +294,15 @@
             "mentionedArray": [{"uid": user} for user in mentioned] if mentioned else None
             })
         
         Thread(target=self._delete, args=(message, delete_after)).start() if delete_after else None
         
         return message
 
+
     def prepare_mentions(self, mentioned: list) -> list:
         """
         `prepare_mentions` - This prepares the mentions for the message.
         
         `**Parameters**``
         - `mentioned` - `ctx.message.mentioned_user_names`.
         
@@ -264,15 +320,17 @@
             mentioned = ctx.prepare_mentions(mentioned_users)
             return ctx.reply(
                 "Mentioned: " + ", ".join(mentioned), mentioned=list(mentioned_users)
             )
         """
         return [f"\u200e\u200f@{username}\u202c\u202d" for username in mentioned]
 
+
     @_run
+    @__typing__
     def send_link_snippet(self, image: str, message: str = "[c]", link: str = "ndc://user-me", mentioned: list = None) -> CMessage:
         """
         `send_link_snippet` - This sends a link snippet.
 
         `**Parameters**``
         - `image` - The image you want to send. Recommended size: 807x216
         - `message` - The message you want to send.
@@ -304,16 +362,18 @@
                 "mediaUploadValueContentType": "image/png",
                 "link": link
                 }],
             "mentionedArray": [{"uid": user} for user in mentioned] if mentioned else None
             })
 
         return message
-    
+
+
     @_run
+    @__typing__
     def send_embed(
         self,
         message: str,
         title: str,
         content: str,
         image: str,
         link: str = "ndc://user-me",
@@ -354,14 +414,15 @@
                 },
             extensions = {
                 "mentionedArray": [{"uid": user} for user in mentioned] if mentioned else None
             })
         
         return message
 
+
     def __handle_media__(self, media: str, content_type: str = "image/jpg", media_value: bool = False) -> str:
         response = None
         
         try:
             if media.startswith("http"):
                 response = get(media)
                 response.raise_for_status()
@@ -382,23 +443,26 @@
 
         return media
     
 
     def encode_media(self, file: bytes) -> str:
         return b64encode(file).decode()
 
+
     def upload_media(self, media: Union[str, BinaryIO], content_type: str = "image/jpg") -> str:
         return ApiResponse(self.request.handler(
             method = "POST",
             url = "/g/s/media/upload",
             data = media,
             content_type = content_type
             )).mediaValue
-    
+
+
     @_run
+    @__typing__
     def send_sticker(self, sticker_id: str) -> CMessage:
         """
         `send_sticker` - This sends a sticker.
 
         `**Parameters**``
         - `sticker_id` - The sticker ID you want to send.
 
@@ -416,14 +480,15 @@
             type=3,
             stickerId=sticker_id,
             mediaValue=f"ndcsticker://{sticker_id}"
             )
         
         return message
 
+
     @_run
     def send_image(self, image: str) -> CMessage:
         """
         `send_image` - This sends an image.
 
         `**Parameters**``
         - `image` - The image link or file you want to send.
@@ -443,15 +508,16 @@
                 self.__handle_media__(
                     media=image,
                     content_type="image/jpg",
                     media_value=False
             )))
 
         return message
-            
+
+
     @_run
     def send_gif(self, gif: str) -> CMessage:
         """
         `send_gif` - This sends a gif.
 
         `**Parameters**``
         - `gif` - The gif link or file you want to send.
@@ -473,14 +539,15 @@
                     media=gif,
                     content_type="image/gif",
                     media_value=False
             )))
         
         return message
 
+
     @_run
     def send_audio(self, audio: str) -> CMessage:
         """
         `send_audio` - This sends an audio file.
         
         `**Parameters**``
         - `audio` - The audio link or file you want to send.
@@ -501,14 +568,15 @@
                     media=audio,
                     content_type="audio/aac",
                     media_value=False
             ))
         
         return message
 
+
     @_run
     def join_chat(self, chatId: str=None) -> ApiResponse:
         """
         `join_chat` - This joins a chat.
 
         `**Example**``
         ```py
@@ -518,14 +586,15 @@
         ```
         """
         return ApiResponse(self.request.handler(
             method="POST",
             url=f"/{self.communityId}/s/chat/thread/{chatId or self.chatId}/member/{self.userId}"
             ))
 
+
     @_run
     def leave_chat(self, chatId: str=None) -> ApiResponse:
         """
         `leave_chat` - This leaves a chat.
 
         `**Example**``
         ```py
@@ -762,22 +831,18 @@
         command = self._commands.fetch_command(command_name)
 
         if command is None:
             if command_name == "help" and data.content == f"{self.command_prefix}help":
                 return context.reply(self._commands.__help__())
             
             if self._events.get("text_message"):
-                self.__rt__(data.comId, data.chatId)
                 return self._handle_all_events(event="text_message", data=data, context=context)
 
         if data.content[:len(self.command_prefix)] != self.command_prefix:
             return None
-        else:
-            self.__rt__(data.comId, data.chatId)
-
 
         response = self._check_cooldown(command.name, data, context)
 
         if response != 403:
             func = command.func
             return func(*self._set_parameters(context=context, func=func, message=message))
 
@@ -811,46 +876,14 @@
             cache.add(
                 key=f"{chatId}_{userId}",
                 value=content,
                 expire=90
                 )
 
 
-    def __st__(self, comId: str, chatId: str):
-        return self.send_websocket_message({
-            "o":{
-                "actions":["Typing"],
-                "target":f"ndc://x{comId}/chat-thread/{chatId}",
-                "ndcId":comId,
-                "params":{"topicIds":[],"threadType":2},
-                "id":randint(0, 100)},
-                "t":304
-                })
-
-
-    def __et__(self, comId: str, chatId: str):
-        def wrapper():
-            return self.send_websocket_message({
-                "o":{
-                    "actions":["Typing"],
-                    "target":f"ndc://x{comId}/chat-thread/{chatId}",
-                    "ndcId":comId,
-                    "params":{"duration":0,"topicIds":[],"threadType":2},
-                    "id":randint(0, 100)},
-                    "t":306
-                    })
-        delay(2.5)
-        return wrapper()
-
-
-    def __rt__(self, comId: str, chatId: str):
-        self.__st__(comId, chatId)
-        Thread(target=self.__et__, args=(comId, chatId)).start()
-
-
     def on_error(self):
         """
         `on_error` - This is an event that is called when an error occurs.
         """
         return self.register_event("error")
 
 
@@ -1288,24 +1321,24 @@
         ) -> Union[Context, None]:
         """
         `_handle_event` is a function that handles events.
         """
         with suppress(KeyError):
 
             if event == "text_message":
-                context = self.context(data, self.request, self.intents)
+                context = self.context(data, self)
                 if all([self.intents, not self.command_exists(
                     command_name=data.content[len(self.command_prefix):].split(" ")[0]
                     )]):
                         self._add_cache(data.chatId, data.author.userId, data.content)
 
                 return self._handle_command(data=data, context=context)
             
             if event in self._events:
-                context = self.context(data, self.request, self.intents)
+                context = self.context(data, self)
 
                 if event in {
                     "user_online",
                     "member_set_you_host",
                     "member_set_you_cohost",
                     "member_remove_your_cohost",
                 }:
```

### Comparing `pymino-1.2.2.3/pymino/ext/dispatcher.py` & `pymino-1.2.2.4/pymino/ext/dispatcher.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/acm.py` & `pymino-1.2.2.4/pymino/ext/entities/acm.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/admin_log.py` & `pymino-1.2.2.4/pymino/ext/entities/admin_log.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/api_response.py` & `pymino-1.2.2.4/pymino/ext/entities/api_response.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/bubble.py` & `pymino-1.2.2.4/pymino/ext/entities/bubble.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/chat_threads.py` & `pymino-1.2.2.4/pymino/ext/entities/chat_threads.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/comments.py` & `pymino-1.2.2.4/pymino/ext/entities/comments.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/enums.py` & `pymino-1.2.2.4/pymino/ext/entities/enums.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/exceptions.py` & `pymino-1.2.2.4/pymino/ext/entities/exceptions.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/general.py` & `pymino-1.2.2.4/pymino/ext/entities/general.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/handlers.py` & `pymino-1.2.2.4/pymino/ext/entities/handlers.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/link_info.py` & `pymino-1.2.2.4/pymino/ext/entities/link_info.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/member.py` & `pymino-1.2.2.4/pymino/ext/entities/member.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/messages.py` & `pymino-1.2.2.4/pymino/ext/entities/messages.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/notification.py` & `pymino-1.2.2.4/pymino/ext/entities/notification.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/sticker.py` & `pymino-1.2.2.4/pymino/ext/entities/sticker.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/threads.py` & `pymino-1.2.2.4/pymino/ext/entities/threads.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/userprofile.py` & `pymino-1.2.2.4/pymino/ext/entities/userprofile.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/entities/wsevents.py` & `pymino-1.2.2.4/pymino/ext/entities/wsevents.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/global_client.py` & `pymino-1.2.2.4/pymino/ext/global_client.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/handle_queue.py` & `pymino-1.2.2.4/pymino/ext/handle_queue.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/socket.py` & `pymino-1.2.2.4/pymino/ext/socket.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/utilities/async_request_handler.py` & `pymino-1.2.2.4/pymino/ext/utilities/async_request_handler.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/utilities/chat_console.py` & `pymino-1.2.2.4/pymino/ext/utilities/chat_console.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/utilities/commands.py` & `pymino-1.2.2.4/pymino/ext/utilities/commands.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/utilities/community_console.py` & `pymino-1.2.2.4/pymino/ext/utilities/community_console.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/utilities/generate.py` & `pymino-1.2.2.4/pymino/ext/utilities/generate.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/utilities/menu.py` & `pymino-1.2.2.4/pymino/ext/utilities/menu.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/utilities/profile_console.py` & `pymino-1.2.2.4/pymino/ext/utilities/profile_console.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino/ext/utilities/request_handler.py` & `pymino-1.2.2.4/pymino/ext/utilities/request_handler.py`

 * *Files identical despite different names*

### Comparing `pymino-1.2.2.3/pymino.egg-info/PKG-INFO` & `pymino-1.2.2.4/pymino.egg-info/PKG-INFO`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 Metadata-Version: 2.1
 Name: pymino
-Version: 1.2.2.3
+Version: 1.2.2.4
 Summary: Easily create a bot for Amino Apps using a modern easy to use synchronous library.
 Home-page: https://github.com/forevercynical/pymino
 Author: forevercynical
 Author-email: me@cynical.gg
 License: MIT
 Keywords: amino,pymino,narvii,amino-api,narvii-bots,aminoapps,amino-bot,amino-bots
 Classifier: Programming Language :: Python :: 3
```

#### html2text {}

```diff
@@ -1,8 +1,8 @@
-Metadata-Version: 2.1 Name: pymino Version: 1.2.2.3 Summary: Easily create a
+Metadata-Version: 2.1 Name: pymino Version: 1.2.2.4 Summary: Easily create a
 bot for Amino Apps using a modern easy to use synchronous library. Home-page:
 https://github.com/forevercynical/pymino Author: forevercynical Author-email:
 me@cynical.gg License: MIT Keywords: amino,pymino,narvii,amino-api,narvii-
 bots,aminoapps,amino-bot,amino-bots Classifier: Programming Language :: Python
 :: 3 Classifier: Programming Language :: Python :: 3.7 Classifier: Programming
 Language :: Python :: 3.8 Classifier: Programming Language :: Python :: 3.9
 Classifier: Topic :: Software Development :: Libraries :: Python Modules
```

### Comparing `pymino-1.2.2.3/pymino.egg-info/SOURCES.txt` & `pymino-1.2.2.4/pymino.egg-info/SOURCES.txt`

 * *Files 4% similar despite different names*

```diff
@@ -8,14 +8,15 @@
 pymino/client.py
 pymino.egg-info/PKG-INFO
 pymino.egg-info/SOURCES.txt
 pymino.egg-info/dependency_links.txt
 pymino.egg-info/requires.txt
 pymino.egg-info/top_level.txt
 pymino/ext/__init__.py
+pymino/ext/_global.py
 pymino/ext/account.py
 pymino/ext/async_community.py
 pymino/ext/async_context.py
 pymino/ext/async_event_handler.py
 pymino/ext/async_socket.py
 pymino/ext/community.py
 pymino/ext/console.py
```

### Comparing `pymino-1.2.2.3/setup.cfg` & `pymino-1.2.2.4/setup.cfg`

 * *Files 1% similar despite different names*

```diff
@@ -1,10 +1,10 @@
 00000000: 5b6d 6574 6164 6174 615d 0d0a 6e61 6d65  [metadata]..name
 00000010: 203d 2070 796d 696e 6f0d 0a76 6572 7369   = pymino..versi
-00000020: 6f6e 203d 2031 2e32 2e32 2e33 0d0a 6175  on = 1.2.2.3..au
+00000020: 6f6e 203d 2031 2e32 2e32 2e34 0d0a 6175  on = 1.2.2.4..au
 00000030: 7468 6f72 203d 2066 6f72 6576 6572 6379  thor = forevercy
 00000040: 6e69 6361 6c0d 0a61 7574 686f 725f 656d  nical..author_em
 00000050: 6169 6c20 3d20 6d65 4063 796e 6963 616c  ail = me@cynical
 00000060: 2e67 670d 0a64 6573 6372 6970 7469 6f6e  .gg..description
 00000070: 203d 2045 6173 696c 7920 6372 6561 7465   = Easily create
 00000080: 2061 2062 6f74 2066 6f72 2041 6d69 6e6f   a bot for Amino
 00000090: 2041 7070 7320 7573 696e 6720 6120 6d6f   Apps using a mo
```

### Comparing `pymino-1.2.2.3/setup.py` & `pymino-1.2.2.4/setup.py`

 * *Files identical despite different names*

